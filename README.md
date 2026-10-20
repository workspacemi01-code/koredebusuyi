# koredebusuyi

Portfolio for **Korede Oluwabusuyi Joshua** — Senior Product Manager & Technical Product Leader.

## What this is

One static page. No build step, no dependencies, no framework.

```
index.html           the whole site — markup, styles, routing
portrait.jpg         hero portrait
fazsion-team.jpg     Fazsion working session
event.jpg            Lagos technology event
portrait-formal.jpg  spare portrait, unused
```

Navigation is hash-based, so every section has a shareable link:
`#/record`, `#/obana`, `#/fazsion`, `#/iotech`, `#/bizinc`, `#/appcake`,
`#/earlier`, `#/calls`, `#/practice`, `#/about`, `#/contact`.

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
- A downloadable CV
- **Product screenshots** for the role pages — the biggest remaining gap

Search `Verify` in `index.html` to find the markers.
