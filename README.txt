StudyFlow
=========

This is the standalone StudyFlow application. The app is implemented in index.html using embedded HTML, CSS, and JavaScript.

Run locally:
1. Open PowerShell in this folder.
2. Run: py -m http.server 8000
3. Open http://localhost:8000/index.html in a browser.
4. Stop the server with Ctrl+C.

The application stores account and planner data in this browser's local storage. Smart timetable generation plans across a rolling 31-day horizon and includes upcoming deadlines in that range. No package installation or API key is required.
