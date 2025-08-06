# AI Researcher Portfolio - Local Development

## Quick Start Options

### Option 1: Python HTTP Server (Recommended)
```bash
# Navigate to project directory
cd mysite

# Start Python HTTP server
python -m http.server 8000
```
Then open: http://localhost:8000

### Option 2: Use the Batch Script (Windows)
```bash
# Double-click or run in terminal
start-server.bat
```

### Option 3: Node.js Live Server
```bash
# Install live-server globally
npm install -g live-server

# Start server with auto-reload
live-server --port=8000
```

### Option 4: VS Code Live Server Extension
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Development Notes

- **Port**: Default is 8000, change if needed
- **Auto-reload**: Use live-server for automatic page refresh
- **Theme Testing**: Toggle between light/dark modes
- **Mobile Testing**: Use browser dev tools
- **Blog Posts**: Test individual post pages with `blog-post.html?id=1`

## File Structure Check
Make sure these files exist:
- `index.html` (homepage)
- `data/projects.json` (project data)
- `data/blogs.json` (blog data)  
- `data/profile.json` (profile data)
- `data/research.json` (research data)
- `css/style.css` (styles)
- `js/main.js` (main functionality)

## Testing Features
- ✅ Theme toggle (light/dark)
- ✅ Navigation between pages
- ✅ Project filtering and search
- ✅ Blog post individual pages
- ✅ Contact form validation
- ✅ Responsive design on different screen sizes
