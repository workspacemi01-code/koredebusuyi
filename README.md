# koredebusuyi

Portfolio for **Korede Oluwabusuyi Joshua** — Senior Product Manager & Technical Product Leader.

## What this is

One static page. No build step, no dependencies, no framework.

```
index.html     the whole site — markup, styles and the small amount of script
portrait.jpg   hero portrait (839×1000, ~216KB)
```

Fonts come from Google Fonts. Everything else is inline.

## Run it locally

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Deploy

Any static host serves it as-is — no configuration needed.

- **Vercel** — import the repo, framework preset "Other", leave build and output empty
- **Netlify** — publish directory `.`
- **GitHub Pages** — Settings → Pages → deploy from branch `main`, folder `/ (root)`

## Still to fill in

- `[VERIFY]` markers on TheOutlet.ng and davidwej.com — dates and job titles
- LinkedIn and GitHub links in the Contact section
- A downloadable CV
- Product screenshots for case studies 01–03

Search `VERIFY`, `ADD LINK` and `ADD FILE` in `index.html` to find them.
