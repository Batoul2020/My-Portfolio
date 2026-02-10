# Portfolio Website - How to View

## The Problem
When you double-click HTML files to open them in a browser, CSS and JavaScript files may not load due to browser security restrictions (CORS policy).

## Solutions (Choose One)

### Option 1: Use VS Code Live Server (RECOMMENDED)
1. Open the portfolio folder in VS Code
2. Install the "Live Server" extension by Ritwick Dey
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. Your browser will open with the portfolio fully working!

### Option 2: Use Python Simple Server
1. Open terminal/command prompt
2. Navigate to the portfolio folder: `cd path/to/portfolio-fixed`
3. Run: `python -m http.server 8000` (or `python3 -m http.server 8000`)
4. Open browser and go to: `http://localhost:8000`

### Option 3: Use Node.js http-server
1. Install: `npm install -g http-server`
2. Navigate to portfolio folder in terminal
3. Run: `http-server`
4. Open the URL shown in terminal

### Option 4: Upload to GitHub Pages or Netlify
Upload the files to a hosting service and they'll work perfectly online.

## Files Included
- `index.html` - Home page
- `about.html` - About page
- `projects.html` - Projects page
- `contact.html` - Contact page
- `styles.css` - All styling (28KB of CSS)
- `script.js` - Navigation functionality

## Note
All files are present and working correctly. The CSS and JS just need to be served through a web server to load properly.
