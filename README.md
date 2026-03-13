# Bunker46 Extension Website

Static landing page for [Bunker46 Extension](https://github.com/dsbaars/bunker46-extension) — a browser extension providing NIP-07 via remote NIP-46 signing.

## Deploy to GitHub Pages

### Option 1: Dedicated repo
1. Create a new repo (e.g. `bunker46-extension-website`)
2. Push the contents of this directory to the `main` branch
3. Go to **Settings → Pages → Source** → Select `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/bunker46-extension-website/`

### Option 2: gh-pages branch in the main repo
1. Create a `gh-pages` branch in `dsbaars/bunker46-extension`
2. Push these files to that branch
3. Enable Pages from the `gh-pages` branch

### Option 3: Custom domain
1. Deploy as above
2. Add a `CNAME` file with your custom domain
3. Configure DNS (CNAME to `yourusername.github.io`)

## Tech Stack
- Static HTML/CSS/JS (no build step)
- Tailwind CSS (via CDN)
- Inter font (Google Fonts)
- Fully responsive

## Structure
```
├── index.html      # Single-page landing
├── assets/
│   ├── popup-connection.png
│   ├── popup-permissions.png
│   ├── popup-settings.png
│   └── prompt-permission.png
└── README.md
```
