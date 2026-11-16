# aary25.github.io

Source for my portfolio site: **https://aary25.github.io**

## What it is

A single-page static site in one file, `index.html`. HTML, CSS, and JavaScript with no framework and no build step.

- Responsive layout with a mobile menu that sets `aria-expanded` and closes on Escape
- Scroll-reveal animations using `IntersectionObserver`
- Respects `prefers-reduced-motion`
- Open Graph and Twitter card metadata (`assets/og-image.png`)

## Run it locally

```bash
git clone https://github.com/aary25/aary25.github.io
cd aary25.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch. A push to `main` updates the live site.

## Related

- [Homelab](https://github.com/aary25/Homelab): the self-hosted DevOps stack featured on the site
