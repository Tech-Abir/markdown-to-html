# README

## Overview
This is a minimal static web page that:
- Loads `input.md` (provided alongside the page) via fetch.
- Converts the Markdown content to HTML using the marked library.
- Injects the rendered HTML into the element with id `#markdown-output`.
- Loads highlight.js and applies syntax highlighting to code blocks.

## Setup
- Place `index.html` and `input.md` in the same directory on any static web server or local filesystem.
- No build step is required. All dependencies are loaded from CDNs:
  - marked: https://cdn.jsdelivr.net/npm/marked/marked.min.js
  - highlight.js (common languages) + GitHub theme CSS

## Usage
1. Open `index.html` in a browser.
2. The page will fetch `input.md`, convert it to HTML, and display it under “Rendering the contents of input.md below:”.
3. Code blocks within the Markdown will be syntax highlighted automatically.

Notes:
- If `input.md` cannot be loaded (e.g., file missing or server disallows fetch), the page will render a small fallback message and example code block.
- To update the content, edit `input.md` and refresh the page.