# Zack Williams Portfolio

Static GitHub Pages portfolio for Zack Williams.

## What is here

- `index.html` - the public portfolio page
- `style.css` - custom styles layered on Bootstrap
- `ZackWilliamsResume2026.pdf` - downloadable current resume
- `img/` - local headshot, testimonial images, and company marks

## Local Preview

Because this is a plain static site, no build step is required.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Maintenance Notes

- Update `ZackWilliamsResume2026.html` first when job history changes, then regenerate `ZackWilliamsResume2026.pdf` from that HTML source.
- Keep the resume PDF filename in sync with the links in `index.html`.
- `img/starkware-logo.svg` comes from the official StarkWare media kit assets.
- Bootstrap, Bootstrap Icons, and Google Fonts are loaded from CDN links in `index.html`.
