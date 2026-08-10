# Assisting Seniors, Inc. — website

The public website for Assisting Seniors, Inc., a non-medical home care company serving
Valparaiso and the surrounding Northwest Indiana communities.

**Live at:** <https://quantumintelligenceworks.github.io/assistingseniorsnwi/>

## Contact

- Phone: (219) 265-1581
- Email: assistingseniorsnwi@gmail.com

## About this build

A single static page. No build step, no framework, no dependencies beyond Google Fonts.

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, and structured data in one file. |
| `404.html` | Not-found page. |
| `assets/asi-logo.png` | Company logo. |
| `robots.txt`, `sitemap.xml` | Search engine basics. |
| `.nojekyll` | Serve files as-is on GitHub Pages. |

The site collects no data: no forms, no cookies, no analytics, no tracking, and no
executable JavaScript. A Content-Security-Policy on both pages allows Google Fonts and
nothing else. Enquiries go to the phone number and email address above.

## Editing

Open `index.html`, change what you need, then:

```bash
git add -A && git commit -m "content: what changed" && git push
```

GitHub Pages redeploys in about a minute.

## Local preview

```bash
npx --yes serve .
```

Or open `index.html` directly in a browser.

---

Built by [Quantum Intelligence Works](https://github.com/quantumintelligenceworks).
