# AGENTS.md

## Repository Overview
Static HTML/CSS CV website hosted on GitHub Pages. No build tools, no dependencies, no test framework.

## Commands
No build, test, or lint commands exist. This is a static site served directly.

## Permission Configuration
`opencode.json` sets `"*": "ask"` - all tool actions require user approval.

## GitHub Pages
- Live at: https://scripter007-star.github.io/webcv/
- Source: `master` branch, root path `/`
- Updates deploy automatically on push to `master`

## File Structure
- `index.html` - Main CV page (Japanese language, Momoka Nohara)
- `style.css` - Styles with gradient header (#667eea to #764ba2)
- `opencode.json` - OpenCode permission config

## Notes
- No JavaScript framework - vanilla HTML/CSS only
- Responsive design included (breakpoint 768px)
- Profile photo from Unsplash (120px circle, object-fit: cover)
- Japanese text with proper lang="ja" attribute
