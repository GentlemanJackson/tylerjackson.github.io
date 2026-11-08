# PC Retail Portfolio — deployment package

This is a self-contained static website. No build step, package manager, server-side code, or external runtime dependencies are required.

## Files

* `index.html` — page markup and portfolio content
* `styles.css` — responsive styling and accessibility-focused states
* `images/` — all image and SVG assets referenced by the page

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server. A local server is recommended for final testing:

```text
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Publish

Upload the complete contents of this folder to your approved static hosting provider. Keep the `images` directory beside `index.html`; the page uses relative asset paths.

## Before launch

1. Confirm image rights and final copy.
2. Test the page on mobile and desktop, including navigation anchors and the contact link.
3. If deploying under a subdirectory, keep the relative paths unchanged.

