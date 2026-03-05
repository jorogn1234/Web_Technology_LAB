# Student Record System

A CRUD application for managing student records using HTML, CSS (Glassmorphism), and Vanilla JavaScript.

## 🚀 How to Run

⚠️ **Important Note:** This application uses the `Fetch API` to load data from `students.json`.  
Browsers block `fetch` requests for local files (`file://` protocol) due to CORS (Cross-Origin Resource Sharing) security policies.

**You must run this project using a local server.**

### Option 1: VS Code Live Server (Recommended)
1. Open this folder in VS Code.
2. Install the "Live Server" extension if you haven't already.
3. Right-click on `index.html` and select **"Open with Live Server"**.

### Option 2: Using Python
If you have Python installed:
```bash
# Python 3
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

### Option 3: Using Node.js
```bash
npx serve .
```

## ✨ Features
- **Create**: Add new students with validation.
- **Read**: View all students in a responsive table.
- **Update**: Edit course and marks dynamically.
- **Delete**: Remove records with confirmation.
- **Search**: Filter students by name or course.
- **Persistence**: Data is saved to `localStorage` so it persists after refresh.
- **Design**: Modern Dark Mode with Glassmorphism effects.
