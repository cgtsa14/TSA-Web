# TSA Website Deployment

Static marketing site for Technical & Scientific Application, Inc. (TSA). Built with plain HTML/CSS and a small amount of inline JavaScript.

## Pages

- `index.html` — Homepage
- `contact.html` — Contact page
- `under-construction/index.html` — Under‑construction landing page

## Structure

- `styles.css` — Global styles for the main site
- `assets/` — Images, logos, icons
- `under-construction/` — Separate styles and assets for the under‑construction page

## Files Included

```
.
├── index.html                 # Main homepage
├── contact.html               # Contact page
├── styles.css                 # Global site styles
├── assets/                    # Images, logos, icons
│   ├── tsa_pri_pos_rgb.svg     # Primary TSA logo
│   ├── solution-card-1.webp
│   ├── solution-card-3.webp
│   ├── data-center.webp
│   ├── building-relationships.webp
│   ├── Web_Arrow.svg
│   └── Icon/                   # Icon assets
│       ├── Arrow-Right.png
│       └── Arrow-Right-1.png
└── under-construction/
    ├── index.html              # Under-construction page
    ├── styles.css              # Under-construction styles
    └── assets/
        ├── tsa_pri_pos_rgb.svg  # TSA logo (UC page)
        └── Web_Arrow.svg        # Watermark element
```

## Deployment Instructions

1. Upload all files and folders to your web server
2. Ensure the folder structure is maintained
3. Set `index.html` as the default document for your domain

## Local Preview

Open the HTML files directly in a browser:

- `index.html`
- `contact.html`
- `under-construction/index.html`

No build step or server required.

## Notes

- The footer “Navigation” block is aligned to the top “Contact Us” button using a small inline script in `index.html` and `contact.html`.
- The footer divider uses full‑bleed styling (`100vw`) so it spans edge‑to‑edge.

## Editing Tips

- Update global styles in `styles.css`.
- Keep images in `assets/` and reference them by relative path.
- If you change nav button sizing, recheck footer alignment.

## Features

- ✅ Brand-compliant design per TSA Brand ID Standards Guide
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Contact information for all three offices (Houston, Birmingham, Atlanta)
- ✅ Utilizing Cookiebot for Cookies
- ✅ Fast loading with optimized assets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All assets use relative paths for easy deployment
- Page is completely self-contained with no external CDN dependencies
- Uses modern CSS Grid and Flexbox for layout
- System fonts ensure consistent appearance across all platforms
