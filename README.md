# adismad.casa

Personal portfolio and résumé site for **Adam Sherman**, Systems Administrator.

**Live:** https://adismad.casa

## Stack

- Hand-written HTML and CSS. No framework, no build step, no JavaScript.
- Hosted on **GitHub Pages** from the `main` branch, with a custom domain (`CNAME`).
- System font stack, light/dark themes via `prefers-color-scheme`, and a dedicated print stylesheet.

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Single-page site with JSON-LD `Person` schema and Open Graph metadata |
| `styles.css` | All styles: theme variables, responsive breakpoints (900px / 680px), dark mode, print |
| `404.html` | Custom not-found page |
| `favicon.svg`, `apple-touch-icon.png` | Icons |
| `docs/resume.pdf` | Current résumé |
| `docs/og.png` | 1200×630 social preview image |
| `docs/qr.svg` | vCard QR code (shown in print only) |
| `docs/Adam_Sherman.vcf` | Downloadable contact card |
| `robots.txt`, `sitemap.xml` | Crawling and indexing |

## Updating

1. Edit `index.html` / `styles.css` and commit to `main`. GitHub Pages redeploys automatically.
2. When replacing the résumé, keep the filename `docs/resume.pdf` so existing links keep working.
3. Update `<lastmod>` in `sitemap.xml` after content changes.
