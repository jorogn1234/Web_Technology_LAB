# Employee Management System (XML + AJAX)

A fully functional Employee Management System that performs CRUD operations on a local XML file using AJAX and DOM manipulation.

## 🚀 Features

-   **AJAX Data Fetching:** Loads employee data from `employees.xml` without page reload.
-   **Client-Side CRUD:**
    -   **Create:** Add new employees to the table dynamically.
    -   **Read:** Parses XML to display employee details.
    -   **Update:** Edit existing employee details (salary, department, etc.).
    -   **Delete:** Remove records from the view.
-   **XML Parsing:** Uses `responseXML` and `getElementsByTagName` as requested.
-   **Modern UI:** Glassmorphism design, dark mode, and responsive layout.
-   **Error Handling:** Manages network errors and malformed XML.

## 🛠️ Tech Stack

-   **HTML5**
-   **CSS3** (Glassmorphism, Animations, Variables)
-   **JavaScript** (ES6+, DOM Manipulation, XMLHttpRequest)

## ⚠️ Important Usage Note

Due to browser security policies (CORS), **AJAX requests to local files (`file:///`) are often blocked**.

### How to Run:

1.  **VS Code "Live Server" (Recommended):**
    -   Right-click `index.html` and select "Open with Live Server".
2.  **Local Python Server:**
    -   Open terminal in this directory.
    -   Run: `python -m http.server 8000`
    -   Go to `http://localhost:8000` in your browser.
3.  **Firefox:**
    -   Firefox *may* allow local file access by default, but a server is always recommended.

*Note: Changes made (Add/Update/Delete) are simulated in the browser memory for the current session. Browsers cannot write back to the local `employees.xml` file directly for security reasons.*
