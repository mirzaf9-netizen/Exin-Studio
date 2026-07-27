# ExIn Studio

Marketing website for ExIn Studio — a presentation and editorial design studio for organizations with complex, high-volume content needs.

**Live site:** [exinstudio.com](https://exinstudio.com)

## About the name

ExIn combines **Ex**trovert and **In**trovert — external forces driving internal results. The studio designs for content that speaks outward (to clients, funders, audiences) and content that drives things inward (training, alignment, internal standards).

## Structure

This is a single-file HTML site (no build step) deployed via Vercel, connected to this GitHub repo.

```
index.html          — the entire site (all pages, styles, and JS in one file)
logo-full.svg        — full horizontal logo lockup (mark + wordmark), for light backgrounds
logo-mark-light.svg  — icon only, no background, for light backgrounds
logo-mark-dark.svg   — icon only, circular badge, for dark backgrounds
favicon.svg          — browser tab icon (based on logo-mark-dark)
robots.txt           — search engine crawl rules
sitemap.xml          — sitemap for search engines
```

## Pages

The site is a single-page app — "pages" (Home, Work, Services, About, Contact) are `<div>` sections toggled via JavaScript (`showPage()`), not separate URLs. All content lives in `index.html`.

## Making changes

1. Edit `index.html` directly (or use Claude Code locally).
2. Commit and push to this repo.
3. Vercel auto-deploys within ~30 seconds — no build step required.

## Brand assets

- Primary gradient: `#5B3CF5` → `#9B59F5` → `#C084FC`
- Font: Plus Jakarta Sans
- Logo files are vector (SVG) and scale cleanly at any size.

## Contact

hello@exinstudio.com
