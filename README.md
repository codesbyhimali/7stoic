# 7stoic - Blackout Motivation

A minimalist, blackout-themed quote generator that serves powerful reminders to the subconscious. Built with HTML, CSS, and JavaScript, it fetches stoic-style motivational quotes from an external API having fallback quotes for offline resilience. Users can explore by mood, save favorites, and share them seamlessly.

## Live Demo
[View 7stoic in your browser](https://codesbyhimali.github.io/7stoic/) <!-- Replace with GitHub Pages or other live link if hosted -->

## Features

- Random Stoic-Inspired Quotes  
- Category-based Filtering (`Motivational`, `Wisdom`, `Happy`, `Love`, `Sad`)  
- Local Save: Store and view your favorite quotes  
- Share Button: Share directly via device-native options or copy to clipboard  
- Fallback Quote Support if the API is unavailable  
- Dark, Minimalist UI with responsive design  
- No Dependencies – Pure HTML/CSS/JS  

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript (Vanilla)
- API: Base64-decoded endpoint powered quote API
- Storage: localStorage for saved quotes
- Responsive: Mobile-friendly design with media queries

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/7stoic.git
   ```
2. Navigate to the project folder:
   ```bash
   cd 7stoic
   ```
3. Open `index.html` in your browser.

## Project Structure

```
7stoic/
├── index.html     # Main application file
└── README.md      # You're reading it!
```

## Usage Guide

1. Open the app → Displays a random quote on load.
2. Choose a category → Filter quotes based on mood.
3. Click 'Random Quote' → Fetch new content.
4. Click 'Save' → Store quotes locally.
5. Click 'Share' → Share via mobile or copy to clipboard.
6. View Saved Quotes → Scroll to the saved section below.
7. Remove or Clear All quotes as needed.

## Notes

- This project is front-end only and uses a public-facing quote API (obfuscated via Base64 in code).
- Fallback quotes will be used if the API is unreachable.
- Works offline for saved content and UI interaction.

## License

© 2025 Himali M Suresh. All rights reserved.  
This project is released for educational and non-commercial use. For other uses, please seek permission.

## Contributing

Feel free to fork and modify.  
If you'd like to contribute quotes, style themes, or features, open an issue or PR.  
Let’s keep 7stoic calm, clean, and effective.

## Acknowledgments

- Inspired by Stoicism, Calm Design, and Personal Reflection
- Uses [VerceI Gama's Quote API](https://quotify.dazzelr.tech)
