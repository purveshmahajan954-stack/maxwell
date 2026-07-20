# Maxwell Home Appliances Site

A static HTML website for Maxwell (a home appliances brand), imported from a Webflow export.

## How to run

The site is served with Python's built-in HTTP server:

```
python3 -m http.server 5000
```

The workflow **Start application** is configured to do this automatically. Open the preview pane to view the site.

## Files

- `index.html` — the main page (copy of `websites.html`, served at `/`)
- `websites.html` — original imported file

## Notes

- All CSS, JS, and images are loaded from Webflow's CDN (`cdn.prod.website-files.com`), so an internet connection is required to render the page correctly.
- No build step or dependencies are needed.

## User preferences
