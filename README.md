# Monolift Marketing Site

Static landing page for [monolift.app](https://monolift.app).

## Stack
- Plain HTML/CSS (no build step)
- Hosted on GitHub Pages
- Custom domain via `CNAME` file
- Free SSL via GitHub Pages auto-provisioned cert

## Structure
```
index.html          Landing page
privacy.html        Privacy policy
terms.html          Terms of service
support.html        FAQ + contact
CNAME               Custom domain (monolift.app)
screenshots/        App screenshots (PNG, ~390x844)
```

## Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy
Push to `main` — GitHub Pages auto-deploys.

## Required edits before launch
- [ ] Replace `YOUR_FORM_ID` in `index.html` with real Formspree form ID
- [ ] Add screenshots: `hero.png`, `logging.png`, `coach.png`, `monkey.png`
- [ ] Add `og-image.png` (1200x630) for social card previews
- [ ] Add `favicon.png`
- [ ] In `terms.html`, replace `[YOUR STATE]` and `[YOUR COUNTY, STATE]` with actual jurisdiction
