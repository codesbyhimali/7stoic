# GitHub Environment Variable Setup

## Setting up the API Key as a GitHub Secret

### Step 1: Add GitHub Secret

1. Go to your GitHub repository
2. Click on **Settings** → **Secrets and variables** → **Actions**
3. Click **New repository secret**
4. Name: `QUOTIFY_API_KEY`
5. Value: Your API key (`qapi_`)
6. Click **Add secret**

### Step 2: GitHub Actions Workflow

The `.github/workflows/deploy.yml` file is already configured to:
- Replace `GITHUB_API_KEY` placeholder in `index.html` with your secret
- Deploy to GitHub Pages automatically

### Step 3: Verify

After pushing to the `main` branch:
- GitHub Actions will automatically run
- The API key will be injected into `index.html`
- Your site will be deployed with the secure API key

## Manual Replacement (Alternative)

If you prefer not to use GitHub Actions, you can manually replace `GITHUB_API_KEY` in `index.html` with your actual API key before deploying.

## Security Notes

- ✅ API key is stored securely in GitHub Secrets
- ✅ Never commit the actual API key to the repository
- ✅ The placeholder `GITHUB_API_KEY` is safe to commit
- ✅ Only GitHub Actions can access the secret during deployment

