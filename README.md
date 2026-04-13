# BJJ Concepts - A Foundational Curriculum

A concept-first Brazilian Jiu-Jitsu curriculum delivered as a mobile-first digital reader. Seven levels from foundational mechanics to complete system integration.

## Structure

| Section             | Contents                                                                                                                                   |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **The Blueprint**   | Introduction, how to use the book, core mechanics, positional hierarchy, decision framework                                                |
| **Levels 1–7**      | Foundational Mechanics → Defensive Systems → Top-Position Control → Guard Play → Guard Passing → Submission Mechanics → System Integration |
| **The Field Guide** | Positional reference, level transitions, training plan, drill index, troubleshooting, quick reference sheets, glossary                     |

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- [Marked.js](https://github.com/markedjs/marked) for Markdown rendering
- [Material Symbols](https://fonts.google.com/icons) for icons
- Google Fonts (Inter, Merriweather)

## Getting Started

Serve the project directory with any static file server:

```bash
npx serve .
```

Then open `http://localhost:3000` in a browser.

## Features

- Mobile-first responsive design with bottom tab navigation
- Desktop sidebar table of contents (always visible at 1024px+)
- Sequential reading with prev/next chapter navigation
- Full-text search across all documents (title, keywords, and cached content)
- Background content prefetch for faster navigation
- Hash-based URL routing for direct linking to chapters

## Author

Michael Kelly - michael.kelly.hash@gmail.com

## License

All rights reserved.
