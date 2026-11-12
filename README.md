# SmartFit Next — independent project

This is a brand-new, standalone smartwatch landing-page project. It does not overwrite or depend on your old CodeNow-Assignment project.

## Folder structure
- `index.html` — page content
- `style.css` — responsive visual design
- `script.js` — mobile navigation and contact form behavior
- `assets/images/watch-hero.svg` and `watch-detail.svg` — original local smartwatch illustrations

## Run it
1. Extract the ZIP.
2. Open the `SmartFit-Next` folder.
3. Open `index.html` in Chrome or another browser.

No npm, React, build command, or installation is needed. Internet is only used for optional Google Fonts; the watch illustrations are local files.

## Publish as a separate GitHub + Vercel project
1. Sign in to GitHub and create a **new repository** named `SmartFit-Next`. Do not choose your old CodeNow-Assignment repository.
2. Upload the contents of this extracted folder (upload the files and the `assets` folder, not the ZIP itself).
3. Commit the files to the new repository's `main` branch.
4. Sign in to Vercel and choose **Add New → Project**.
5. Import the new `SmartFit-Next` GitHub repository.
6. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank or `.` if Vercel asks.
7. Click **Deploy**. Vercel will provide a new, separate live URL.
8. Later changes pushed to this new GitHub repository will trigger a new deployment.

## Contact form note
The demo form opens the visitor's default email app. It does not store messages. Replace `hello@smartfitnext.example` in `index.html` and `script.js` with a real email address before publishing.
