# AGENTS.md

## Project overview

Single-file static HTML game (`index.html`) for children's learning. Traditional Chinese (zh-TW) UI. No build system, no dependencies, no tests.

## How to run

Open `index.html` in a browser. No server needed.

## Key facts

- All CSS and JS are inline in `index.html` — no external files.
- Four sections: colors, numbers, shapes, reflection page.
- Navigation uses `showPage()` function to toggle `display: none/block` on `#main-menu` and `.game-page` elements.
- Responsive via CSS media query at 600px breakpoint.
- No linting, formatting, or typecheck commands exist.

## When editing

- Keep all code in `index.html` (single-file architecture).
- CSS is in `<style>`, JS is in `<script>` at bottom of `<body>`.
- Game pages use IDs `game1` through `game4`.
- Back buttons call `showPage('main')`.
