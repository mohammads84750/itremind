# iTremind

A personal Life OS: dashboard, tasks, habits, goals, routine, calendar, notes and progress.

## What this is
A static web app. One file (`index.html`) holds all HTML, CSS and JavaScript.
There is no build step and no dependencies to install.
The only external request is the Sora font from Google Fonts, with a system-font fallback.
Data is saved in the browser's localStorage (keys start with `itremind.`), so it stays on each device.
Navigation uses `#/section` links, so no server rewrite rules are needed.

## Run locally
Open `index.html` in a browser, or run `npm start` and visit http://localhost:3000.

## Deploy
- **Netlify:** drag the project folder onto https://app.netlify.com/drop, or connect the repo. No build command; publish directory is `.`.
- **Vercel:** import the repo or run `npx vercel`. Framework preset: Other. No build command; output directory is `.`.
- **GitHub Pages / Cloudflare Pages:** publish the folder root. No build command.
