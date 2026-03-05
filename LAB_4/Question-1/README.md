# Real-Time Username Availability Checker

This project implements a registration form that checks username availability in real-time using AJAX (Fetch API) against a local JSON file.

## How to Run

**Important:** Due to browser security restrictions (CORS), you cannot simply open `index.html` directly in your browser (using the `file://` protocol) because the `fetch` API will be blocked from reading the local `users.json` file.

You need to serve the files using a local web server.

### Option 1: VS Code Live Server Extension (Recommended)
1. Open this folder in VS Code.
2. Right-click on `index.html`.
3. Select "Open with Live Server".

### Option 2: Python Simple HTTP Server
If you have Python installed, you can run a simple server from the command line:

1. Open your terminal/command prompt.
2. Navigate to this directory:
   ```bash
   cd "c:\Users\kssar\Desktop\GITHUB\WebTechnologyLab\LAB_4\Question-1"
   ```
3. Run one of the following commands:
   - For Python 3: `python -m http.server`
   - For Python 2: `python -m SimpleHTTPServer`
4. Open your browser and go to `http://localhost:8000`.

## Files
- `index.html`: The main registration form.
- `style.css`: Simple styles for the form and validation feedback.
- `script.js`: Handles the input event, debouncing, and fetching the JSON data.
- `users.json`: A list of taken usernames acting as a database.
