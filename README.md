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

- Update the resume source from `/Users/zack/Downloads/2026 resume full info.md` when job history changes.
- Keep the resume PDF filename in sync with the links in `index.html`.
- Bootstrap and Bootstrap Icons are loaded from jsDelivr CDN links in `index.html`.
