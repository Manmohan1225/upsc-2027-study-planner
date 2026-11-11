# UPSC 2027 Personal Study Planner

A static, mobile-friendly UPSC study planner designed for GitHub Pages.

## Features

- Dated preparation roadmap from November 2026 through the planned Mains preparation period.
- Daily 9-hour study checklist.
- GS and Chemistry Optional topic tracker.
- January-onward test calendar.
- Test marks and mistake notes.
- Browser-local progress saving using `localStorage`.
- PWA manifest and service worker for installability and offline app-shell access.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `upsc-2027-planner`.
2. Upload **all files and folders in this package** to the repository's root:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`
   - `README.md`
   - `.nojekyll`
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your URL will look like:
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Install on Android

1. Open your published GitHub Pages URL in Chrome.
2. Open Chrome's three-dot menu.
3. Choose **Install app** or **Add to Home screen** if offered.

## Important data note

Progress and test records are stored in the browser's local storage on that device. They are not synced to GitHub or other devices. Clearing browser data can erase them, so keep a separate backup of important scores and notes.

## Editing the plan

Edit `index.html` to change topics, dates, timetable or tests. Commit the updated file to GitHub; Pages will redeploy automatically.

## Exam-date note

The dates in this planner are planning assumptions based on the calendar used when it was created. Check the latest official UPSC notification/calendar for changes.
