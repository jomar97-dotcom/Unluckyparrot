# Unlucky Parrot Shooter

A lightweight, mobile-friendly arcade mini-game built with plain HTML, CSS, and JavaScript. No build step or external libraries required.

## Run locally
Open `index.html` in a modern browser.

## Deploy to Vercel
1. Create a new GitHub repository and upload `index.html` and `vercel.json`.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Keep the framework preset as **Other**. No build command is needed.
4. Set the output directory to `.` (or leave it blank if Vercel detects the static site).
5. Click **Deploy**.

## Controls
- Tap/click anywhere in the play area to shoot toward that point.
- Hit fruit for points. Bombs add two misses.
- Five missed fruit / bomb penalties ends the run.
- Best score is saved in the browser on the same device.

## Customization
All game art is drawn with Canvas shapes in `index.html`, so you can change colors, spawn rates, scoring, and title without managing image assets.
