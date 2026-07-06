# Roast Me Generator

A playful coding roast generator built with HTML, CSS, and vanilla JavaScript.

Users type something about their coding life, language, tool, or experience level, and the app generates a random lighthearted roast based on keyword categories.

## Live Links

- GitHub Repository: https://github.com/fazal305/roast-me-generator
- Live Demo: https://fazal305.github.io/roast-me-generator/

## Overview

Roast Me Generator is a small browser app designed for quick laughs and simple JavaScript practice. It detects keywords from the user's input, chooses a matching roast category, displays a random response, and supports copy-to-clipboard, sound feedback, mobile vibration, and a clear/reset flow.

This project works well as a Fun Lab mini-project because it is easy to understand, easy to demo, and shows personality without needing a framework.

## Features

- Random coding roast generator
- Keyword-based category detection
- Roast Again button
- Copy Roast button
- Empty-input shake animation
- Category label feedback
- Sound effect using the Web Audio API
- Mobile vibration support
- Responsive dark interface
- Keyboard support with the Enter key

## Roast Categories

- CSS and layout
- JavaScript
- Python
- Beginner developers
- Git and GitHub
- WordPress
- React
- VS Code
- Firebase
- Stack Overflow
- Pakistani developer humor
- General developer chaos

## Tech Stack

- HTML5
- CSS3
- JavaScript
- DOM manipulation
- Web Audio API
- Vibration API
- Clipboard API

## Folder Structure

```text
roast-me-generator/
  index.html
  style.css
  script.js
  README.md
  LICENSE
  .gitignore
```

## Getting Started

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Type something about your coding life.
4. Click `Roast Me`.

No build tools or dependencies are required.

## Architecture Notes

The project is split into three main files:

- `index.html` defines the app layout.
- `style.css` handles the dark interface, responsive layout, animations, and button states.
- `script.js` manages category detection, random roast selection, sound, vibration, copy-to-clipboard, and reset behavior.

## Accessibility

- The input has a visible label.
- The output area uses live-region attributes for generated roasts.
- Buttons are keyboard accessible.
- Focus states are visible.
- Reduced-motion preferences are respected in CSS.

## Performance

The project is lightweight and dependency-free. It runs fully in the browser and does not require a backend, package manager, or external assets.

## Lessons Learned

- How to organize keyword-based logic
- How to select random responses from arrays
- How to update page content with JavaScript
- How to use browser APIs for sound, vibration, and clipboard actions
- How to make a small project feel polished with UX details

## Future Improvements

- Add roast intensity levels
- Save favorite roasts with `localStorage`
- Add share buttons
- Add category filters
- Add a no-sound toggle
- Add more response packs

## Fazal Labs Ecosystem

Part of **Fazal Labs** under the **Fun Lab** suite.

This is a playful JavaScript mini-project built to show DOM interaction, browser APIs, and product personality.

## License

MIT License
