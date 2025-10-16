# Overview
This is a minimal static web app that:
- Loads input.md from the same directory.
- Converts the Markdown to HTML using Marked.
- Renders the result inside the element with id "markdown-output".
- Applies syntax highlighting to code blocks using Highlight.js.

# Setup
1. Place index.html and input.md in the same directory.
2. Ensure you have an input.md file. If it is empty or missing, the page will display a helpful message.
3. No build steps required; dependencies are loaded from CDNs:
   - Marked via jsDelivr
   - Highlight.js via jsDelivr (with a default GitHub-like theme)

# Usage
- Open index.html in a modern web browser.
- Edit input.md and reload the page to see updates.
- Code blocks in the Markdown will be highlighted automatically.

Notes:
- The app fetches input.md with cache disabled to better reflect recent changes during development.