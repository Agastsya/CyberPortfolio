# SOC QUEST — Agastsya Joshi

An interactive **16-bit pixel-art portfolio** styled like a SNES platformer, built for a
SOC Analyst / Security Operations job search.

The entire site is a single self-contained file — `index.html` — containing the HTML, CSS,
and JavaScript, with original pixel sprites drawn in-code and chiptune sound effects via the
Web Audio API. No build step, no external assets, works fully offline.

## Run locally

```bash
npm install
npm start
```

Then open the URL it prints (defaults to <http://localhost:3000>).

Since it's a single static file, you can also just open `index.html` directly in a browser,
or run `npx serve .` without installing anything.

## Deploy

It's pure static HTML, so any static host works with zero configuration:

- Drag the folder onto **Netlify**, run **`vercel`**, or push to a `gh-pages` branch for **GitHub Pages**.
- Point a custom domain (e.g. agastsya.com) at the host.

## What's inside

- Title screen with an animated hooded-hacker character (types, grins, throws a laptop).
- Clickable pixel sprites that open retro dialogue boxes: about, experience, projects (as
  "bosses" with HP bars), skills (filterable power-ups), hackathon awards, certifications,
  a timeline, and a contact screen with an embedded résumé download.
- HUD with lives, a coin counter, world labels, and a sound toggle.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The entire game / portfolio (HTML + CSS + JS, self-contained) |
| `package.json` | Local dev-server config (`serve`) |
| `.gitignore` | Ignores `node_modules` etc. |

---

© 2026 Agastsya Joshi · [Portfolio](https://www.agastsya.com/) · [GitHub](https://github.com/agastsya) · [LinkedIn](https://www.linkedin.com/in/agastsya/)
