# Martin Gabriel Rodriguez — Personal Website

Single-page personal site for [Martin Gabriel Rodriguez](https://www.linkedin.com/in/martin-rodriguez22/), built as static HTML/CSS/JS for GitHub Pages.

**Live URL (after enabling Pages):** https://themgr111.github.io/PersonalWebsite/

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | Page content (About, Experience, Projects, Skills, Education, Contact) |
| `styles.css` | Layout and design system |
| `script.js` | Mobile nav, active section highlight, scroll reveal |
| `assets/Martin_Rodriguez_Summer_2026.pdf` | Downloadable resume |

## Enable GitHub Pages

1. Open the repo on GitHub: **Settings → Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Choose branch **`main`**, folder **`/` (root)**, then **Save**
4. Wait a minute, then visit https://themgr111.github.io/PersonalWebsite/

If you merge via pull request, Pages will serve whatever is on `main` after merge.

## Edit content later

- Update copy and sections in `index.html`
- Adjust colors/fonts in the `:root` variables at the top of `styles.css`
- Replace the PDF in `assets/` and keep the filename (or update the download link in `index.html`)

## Local preview

Open `index.html` in a browser, or from the repo root:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
