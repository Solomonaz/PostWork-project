# Weather Logger

Simple client-side weather logger that stores entries in the browser's localStorage.

## Files
- [index.html](index.html) — main app and embedded script.  
  Referenced functions in the script: [`loadData`](index.html), [`saveData`](index.html), [`displayData`](index.html).  
  Important element IDs: `weatherForm` ([`weatherForm`](index.html)) and `weatherData` ([`weatherData`](index.html)).

## Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari).
- Optional: Python 3, Node.js, or VS Code Live Server for running a local static server.

## Run locally

Option A — Open directly (quick)
1. Open the project folder and double-click [index.html](index.html) or open it in your browser.
2. The app should work immediately. (If you see issues with scripts, use Option B below.)

Option B — Using Python (recommended for consistent behavior)
1. Open a terminal in the project folder:
   - Windows PowerShell / Command Prompt:
     ```
     cd "c:\Users\user\OneDrive\Desktop\PostWork-project"
     python -m http.server 8000
     ```
2. Open http://localhost:8000 in your browser and click [index.html](index.html).

Option C — Using Node (http-server)
1. Install and run:
```
npm install -g http-server
http-server -s
```
