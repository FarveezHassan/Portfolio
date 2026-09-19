# Farveez Hassan — Portfolio Website

A dark, purple-accented one-page portfolio built with plain HTML, CSS and JavaScript. No build tools, frameworks, or dependencies required.

## Files

```
portfolio/
├── index.html          Main page (all content and structure)
├── css/
│   └── style.css        All styling
├── js/
│   └── script.js         Mobile menu, LinkedIn link, contact form logic
├── assets/
│   └── profile.jpg       Profile photo used in the hero section
└── README.md
```

## Running it locally

**Easiest — just open the file:**
Double-click `index.html`, or drag it into your browser. Everything (styles, script, image) loads via relative paths, so it works straight away.

**In VS Code (recommended for editing):**
1. Open the `portfolio` folder in VS Code (`File → Open Folder…`).
2. Install the **Live Server** extension (by Ritwick Dey) if you don't already have it.
3. Right-click `index.html` in the file explorer and choose **"Open with Live Server"**.
4. The site opens at `http://127.0.0.1:5500/index.html` (or similar) and auto-reloads whenever you save changes.

Live Server isn't required — opening `index.html` directly also works — but it gives you auto-refresh while you edit, and avoids any browser restrictions on local file access.

## What to update before publishing

- **LinkedIn URL** — set in `js/script.js` (search for `linkedinURL`). It's currently a placeholder: `https://www.linkedin.com/in/farveez-hassan/`.
- **Project links** — the "View Project" / "View Details" buttons for both projects in `index.html` are placeholder `#` links (search for `placeholder-note`). Add real URLs (e.g. GitHub repo, live demo) once available.
- **GitHub URL** — not yet included anywhere; add a link/icon in the footer or contact section if you'd like one.

## Notes

- The contact form doesn't submit anywhere on its own — it opens the visitor's email app with a pre-filled message addressed to `Farveeshassan@gmail.com` (via a `mailto:` link). This works with no backend, but only if the visitor has an email client configured on their device.
- Fonts (Sora, Inter) load from Google Fonts over the internet — an internet connection is needed the first time the page loads for fonts to display correctly. Everything else works fully offline.
