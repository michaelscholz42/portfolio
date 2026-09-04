# Getting your site live on GitHub Pages

No VS Code, no command line, no server to maintain — this is one static HTML file, and GitHub Pages hosts it for free. Total time: about 10 minutes, and updates after that are just re-uploading the file.

## One-time setup

1. **Create a free GitHub account** at github.com, if you don't have one.
2. Click the **+** in the top-right corner → **New repository**.
   - Name it `portfolio` (or, if you want the site at the shortest possible address, name it exactly `<your-github-username>.github.io`).
   - Set it to **Public**.
   - Don't add a README — just click **Create repository**.
3. On the empty repo page, click **uploading an existing file**.
4. Drag in `index.html` from this download. Commit the upload (the default message is fine).
5. Go to the repo's **Settings** tab → **Pages** (left sidebar).
6. Under "Build and deployment," set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save**.
7. Wait about a minute, then refresh — GitHub shows your live URL at the top of that Pages settings screen. It'll look like:
   - `https://<your-username>.github.io/portfolio/` (if you named the repo `portfolio`), or
   - `https://<your-username>.github.io/` (if you named the repo `<your-username>.github.io`)

That's it — it's live, HTTPS by default, and there's no database or server for anyone to attack. GitHub hosts and patches everything underneath it.

## Updating it later

Go to the repo, click on `index.html`, click the pencil (**Edit**) icon, make your change, and commit. It's live again within a minute. No local setup required — you can even do this from your phone's browser.

## Custom domain (optional)

If you want it at your own domain instead of `github.io`, buy the domain anywhere (Namecheap, Google Domains successor, etc.), then in the same Pages settings screen enter it under "Custom domain" and follow GitHub's DNS instructions. GitHub issues the HTTPS certificate for you automatically.

## Accessibility (ADA / WCAG)

There's no official "ADA certification" for a personal site — ADA lawsuits and accessibility audits use the **WCAG 2.1 Level AA** guidelines as the practical standard, so that's what this file was built and tested against (using the same automated checker, axe-core, that professional audits use — it currently returns zero violations). Specifically:

- Every text color meets the 4.5:1 contrast minimum against its background, in both light and dark viewing modes.
- The page has a real heading structure, landmark regions, and a "skip to main content" link for keyboard and screen-reader users.
- All interactive elements (menu, links) are reachable and operable by keyboard, with a visible focus outline.
- Decorative icons are hidden from screen readers so they don't add noise; meaningful icons/links have text labels.
- Motion (the small pulse animation) respects a visitor's OS-level "reduce motion" setting.

Because this is a static informational page with no forms, no file uploads, and no user accounts, there's nothing here that degrades over time — you don't need to re-audit it unless you add something interactive (a contact form, a comment box, etc.) or restyle colors, in which case just send it back to me and I'll re-check contrast and structure before you publish.

## What's still a placeholder

Once you send me your real TikTok video link(s) and the LinkedIn post you want featured, I'll swap in the actual embeds (TikTok and LinkedIn both provide official embed code for exactly this) so they play/preview right on the page — no separate "app" needed for that, it's just their standard embed widget. Until then, the current cards are clearly marked as placeholders so nothing looks broken or fake in the meantime.
