# Portfolio — Mathan Raj Krishnan

This is a simple, elegant single-page portfolio generated to match the attached resume.

What's included
- `index.html` — the single-page portfolio.
- `styles.css` — minimal responsive styling.
- `assets/profile.svg` — placeholder avatar (edit or replace with a real photo).

Quick edits you should make
1. Replace the placeholder email `you@example.com` in `index.html` with your real contact email.
2. Replace `resume.pdf` with your actual PDF resume file in the project root (the "Download Resume" button links to `resume.pdf`).
3. Update the Experience, Education, and Projects sections to match exact dates, employers, and project links.

How to preview locally
- Quick preview using a simple static server (Python 3):

```bash
# from this project folder
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Hosting on GitHub Pages
1. Create a new repo (or push this folder to an existing repo).
2. In GitHub, enable Pages from the repository settings and choose the `main` branch (or `gh-pages`) pointing to `/` root.
3. Replace `resume.pdf` in the repository root so the Download Resume button works.

Customization tips
- Swap `assets/profile.svg` with a proper `profile.jpg` or PNG. Update the `img` tag in `index.html`.
- Tweak colors in `styles.css` (CSS variables at the top) to match your personal brand.

If you want, I can:
- Pull exact text from your attached resume PDF and replace placeholders with accurate entries.
- Add social links (GitHub, LinkedIn) and micro-animations.
- Convert this to a small static site with a build pipeline (if you want a longer-term site).
