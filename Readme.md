# GEMINI TRIAL

This project is a single-page QR attendance prototype built with React, Tailwind CSS, and browser-based QR tools. The main page renders the attendance app, while the styling and application logic now live in separate files for easier maintenance.

## Project Files
- `qr_attendance_synopsis.html` - main HTML entry point
- `styles.css` - custom UI styles and theme rules
- `scripts.js` - React app, state handling, QR flow, and dashboard logic

## What It Does
- Student login and signup
- Admin dashboard for student records and attendance logs
- Faculty scanner for QR attendance marking
- Student QR preview and download
- Light and dark theme switching with local storage persistence

## How To Run
1. Open `qr_attendance_synopsis.html` in a modern browser, or serve the folder from a local web server.
2. Make sure the external CDN resources can load.
3. For camera scanning, use `localhost` or HTTPS so the browser allows camera access.

## Notes
- The UI and behavior are driven by the linked `styles.css` and `scripts.js` files.
- If you edit the HTML, keep the CSS and script references intact so the app continues to work.

Naveen Kumar Sotwre Developer
