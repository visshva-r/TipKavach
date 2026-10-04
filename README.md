# TipKavach — Track A (Digital Fraud & Scam Resilience)

Single-file web app: open `index.html` in Chrome/Edge on phone or PC.

## Live demo (fastest if `gh` is not logged in)

1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this entire `Project` folder onto the page.
3. Copy the `https://….netlify.app` URL for Unstop.

## GitHub Pages (if logged in)

```powershell
cd Project
gh auth login
gh repo create tipkavach --public --source . --remote origin --push
gh api repos/{owner}/tipkavach/pages -f build_type=legacy -f source[branch]=master -f source[path]=/
```

Then open `https://<your-username>.github.io/tipkavach/`

## Local demo for video

Double-click `index.html` or:

```powershell
npx --yes serve .
```

Open the URL shown (e.g. `http://localhost:3000`).
