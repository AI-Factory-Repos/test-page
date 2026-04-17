# Test Page

A simple static HTML page displaying test text for deployment testing purposes. This project serves as a minimal example for testing deployment processes across various hosting platforms.


> 📸 *Screenshot is captured automatically after the site finishes its first build.*

![Test Page — Live Preview](https://s0.wordpress.com/mshots/v1/https%3A%2F%2Fkaleidoscopic-marshmallow-713f25.netlify.app?w=1200&h=630)

## Live Demo

[View the live site](https://kaleidoscopic-marshmallow-713f25.netlify.app)

## Features

- Single static HTML page with test content
- Semantic HTML5 structure
- Basic accessibility features
- Platform-agnostic deployment ready
- Minimal file structure for easy deployment testing

## Tech Stack

- **Frontend:** HTML5
- **Deployment:** Netlify (with netlify.toml configuration)

## Getting Started

### Prerequisites

- A web browser
- Basic web server (optional for local development)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd test-page
```

2. Open the HTML file directly in your browser:
```bash
# Navigate to the frontend directory
cd frontend
# Open index.html in your default browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

Alternatively, serve it with a simple HTTP server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server frontend
```

## Project Structure

```
test-page/
├── README.md
├── netlify.toml          # Netlify deployment configuration
└── frontend/
    └── index.html        # Main HTML page
```

## License

MIT