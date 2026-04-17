# CLAUDE.md

## Project Overview

Test Page is a minimal static HTML website created for deployment testing purposes. It serves developers who need to validate their deployment pipeline with the simplest possible web project. The core problem it solves is providing a basic, ready-to-deploy HTML page that displays "This is a test" text for deployment verification.

## Tech Stack

**Frontend:**
- HTML5
- No JavaScript frameworks or libraries
- No CSS frameworks or preprocessors
- Static file hosting compatible (Netlify, GitHub Pages, etc.)

**Backend:**
- None - Static site only

## Architecture

This is a single-file static website with no build process or server requirements.

**Folder Structure:**
```
/
├── index.html (main and only HTML file)
```

**Entry Point:** `index.html` - The root HTML document served by the hosting platform.

**Communication:** No frontend-backend communication - purely static content.

## Build & Development Commands

**Development:**
- Open `index.html` directly in a browser
- Use any local server for development: `python -m http.server 8000` or `npx serve .`

**Production Build:**
- No build process required
- Deploy `index.html` directly to any static hosting platform

**Installation:**
- No dependencies to install

## Environment Variables

```
# No environment variables required
```

## API Endpoints

No backend API - static site only.

## Database Schema

No database - static site only.

## Key Algorithms & Patterns

No complex algorithms or patterns. This is a minimal static HTML page with no JavaScript logic, state management, or data processing.

## What Was Built (Tickets)

### Foundation Phase
- **FE-1**: Create HTML document structure — Added complete HTML5 document boilerplate including DOCTYPE declaration, html element with lang attribute, head section with meta charset and viewport tags, and empty body element ready for content.
- **FE-2**: Add test content to HTML page — Implemented the main content "This is a test" using semantic HTML heading element (h1) within the body, ensuring proper content display and semantic structure.
- **FE-3**: Validate HTML structure and accessibility — Ensured HTML5 validation compliance, proper heading hierarchy, language attribute for accessibility, and overall document structure meets web standards.

## Known Constraints & Notes

- **Minimal by Design**: This project intentionally contains only the bare minimum HTML required for a functional web page. Any future modifications should maintain this simplicity unless specifically required for testing purposes.
- **No Styling**: No CSS was added to keep the page as minimal as possible. The page uses browser default styling only.
- **Single Purpose**: Built specifically for deployment testing - not intended as a foundation for larger applications.
- **Platform Agnostic**: Designed to work on any static hosting platform without modification.
- **HTML5 Standards**: The code follows HTML5 validation standards and includes basic accessibility attributes (lang, proper heading structure).