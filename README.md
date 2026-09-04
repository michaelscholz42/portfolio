# Portfolio site

Single-file static site (`index.html`, plain HTML/CSS/JS, no build step, no dependencies) plus its images and PDFs. Built to be edited directly and hosted on GitHub Pages.

## Working on it in VS Code

1. Open this folder in VS Code (`File → Open Folder…`).
2. Edit `index.html` directly — everything (styles, script) lives in that one file.
3. Preview changes by opening `index.html` in a browser, or use a VS Code extension like "Live Server" for auto-reload while editing.
4. No install/build step is needed — it's plain HTML/CSS/JS.

## Files

- `index.html` — the site itself.
- `michael-avatar.jpg` — nav headshot.
- `michael-about.jpg` — About section photo.
- `awlf-thesis-scholz.pdf` — AWLF master's thesis, linked from the Research section and the About pull-quote.
- `securing-ai-systems-scholz.pdf` — second research paper, linked from the Research section.
- `spong-cpong-poster.pdf` — the ODU Knowledge & Creativity Expo poster, linked from the sPONG/cPONG project card.
- `SETUP.md` — step-by-step guide to publishing this on GitHub Pages and a note on accessibility/WCAG compliance.

## Publishing / updating on GitHub Pages

See `SETUP.md` for the full walkthrough. Short version once this repo has a GitHub remote:

```
git add -A
git commit -m "Update site"
git push
```

GitHub Pages redeploys automatically within about a minute of a push to the branch it's configured to serve from.
