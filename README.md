# README

## Overview
This is a simple static page that:
- Fetches `input.md`
- Converts it to HTML using Marked
- Renders the result inside the `#markdown-output` element
- Loads Highlight.js to syntax-highlight code blocks

## Setup
- Place `index.html` and `input.md` in the same directory.
- Serve the directory with any static file server.

Examples:
- Using Node.js http-server: `npx http-server .`
- Using Python 3: `python3 -m http.server`
- Or open `index.html` directly in a modern browser; some browsers may restrict fetch of local files, so a local server is recommended.

## Usage
- Start a local server in the directory.
- Navigate to `http://localhost:8080` (or the port used by your server).
- The content of `input.md` will be rendered as HTML in the page, and any code blocks will be highlighted automatically.