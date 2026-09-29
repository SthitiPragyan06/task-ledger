# Task Ledger

A lightweight, dependency-free to-do list app built with vanilla HTML, CSS, and JavaScript. Designed to look and feel like a physical ledger, with priority tracking, due dates, and drag-and-drop reordering — all persisted in the browser via `localStorage`.

**Live demo:** https://sthitipragyan06.github.io/task-ledger/

## Features

- **Add, complete, and delete tasks** with a single click or `Enter` key
- **Priority levels** — High / Medium / Low, each color-coded
- **Categories/tags** for grouping related tasks
- **Due dates** with automatic overdue detection and highlighting
- **Filtering** — view All, Active, or Done tasks
- **Live search** across task titles
- **Drag-and-drop reordering** of tasks
- **Progress tracking** — open, done, overdue counts and a completion percentage bar
- **Persistent storage** — tasks are saved to `localStorage`, so they survive page reloads
- **Fully responsive** — works on mobile and desktop
- **No frameworks, no build step** — a single self-contained HTML file

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, no external CSS framework)
- Vanilla JavaScript (ES6+)
- Browser `localStorage` API for persistence
- Google Fonts: Fraunces, Inter, JetBrains Mono

## Getting Started

No installation or build tools required.

1. Clone the repo:
   ```bash
   git clone https://github.com/SthitiPragyan06/task-ledger.git
   ```
2. Open `index.html` in any modern browser.

That's it — the app runs entirely client-side.

## Deploying with GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/root`.
4. Save. The app will be live at `https://github.com/SthitiPragyan06/task-ledger.git`.

## Project Structure

```
task-ledger/
├── index.html   # markup, styles, and app logic (single file)
└── README.md
```

## Possible Future Enhancements

- Sync tasks to a backend (Node/Express + database) for cross-device access
- User authentication for multiple task lists
- Recurring tasks and reminders
- Export/import tasks as JSON or CSV

## Author

**Sthiti Pragyan Mohapatra**
[GitHub](https://github.com/SthitiPragyan06/task-ledger.git)
