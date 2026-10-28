# hix-pro.github.io

**Live: [hix-pro.github.io](https://hix-pro.github.io/)**

The front door for [hix tools](https://github.com/hix-pro) — eight local-first developer tools that catch what CI misses. One static page, no build step.

## What's here

- The eight-tool suite, with browser demos and install links
- Three featured posts from the [writing site](https://hix-pro.github.io/blog/)
- A short explanation of the local-first approach
- RSS, sitemap, and social metadata

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

GitHub Pages serves this repository from `main` at the repository root. Push to `main`; no workflow is required.

## Structure

```text
index.html          the page
assets/style.css    styles
assets/og.png       1200×630 social card
assets/banner.svg   hero banner
assets/*.png        writing covers
```

## License

MIT for the site code. The hix tools name, banner, and covers are © hix.
