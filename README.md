# Academic website — Marcelo Gantier-Mita

Live at https://marcelogantier.github.io. Plain HTML + CSS, no build step.

## Files

- `index.html` — all content, plus a small script that highlights the active nav item on scroll
- `style.css` — styles (Lora headings, Lato body, accent #1b3a5c, text #2B2B2B, white background)
- `photo.jpg` — headshot (add your own; square image, ~600×600 px)
- `files/` — put PDFs here (CV, JMP, policy brief) and link to them as `files/name.pdf`

## Deploy on GitHub Pages

1. Create a public repository named `<username>.github.io` (site served at `https://<username>.github.io`), or any other name (served at `https://<username>.github.io/<repo>`).
2. Push these files to the `main` branch.
3. In the repository: Settings → Pages → Source "Deploy from a branch", Branch `main`, folder `/ (root)` → Save.
4. Wait one or two minutes and open the URL shown on that page.

To edit content, open `index.html` and change the text inside each `<section>`. Nothing needs to be compiled.
