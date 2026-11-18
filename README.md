# Smart Attendance Pro

A responsive student attendance management Progressive Web App (PWA) for a college mini project.

## Demo login
- Username: `admin`
- Password: `admin123`

## Features
- Responsive dashboard for phone and laptop
- Add, search and delete students
- Date-wise Present / Absent attendance
- Daily attendance summary and individual percentage
- Reports and CSV export
- JSON backup and restore
- Browser-local data storage and offline cache after first load

## Run locally
Open `index.html` in a browser. For PWA installation and service-worker support, deploy the repository with HTTPS (for example, GitHub Pages).

## GitHub Pages
In the repository open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then Save. Wait for the published site URL to appear.

## Important limitations
This is a PWA source project, not a compiled native Android APK or Windows EXE. Data is stored separately in each browser and does not automatically sync between phone and laptop; use Backup & Settings to transfer it. The front-end demo login is not secure authentication. Do not use real sensitive student data without adding a secure backend and proper authentication.
