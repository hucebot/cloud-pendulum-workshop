# CloudPendulum Workshop 2026

Website for **Education and Research Using CloudPendulum Technology**, 24–25 November 2026, Nancy, France.

## Local preview

From the repository folder, run:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>. Press `Ctrl+C` to stop the server.

## Editing

- `index.html`: workshop content and links.
- `static/css/index.css`: styles and layout.
- `static/js/index.js`: mobile navigation.
- `static/images/workshop/`: logos and images.

No build step is required.

## GitHub Pages

1. Push the files to the repository, including `index.html`, `static/`, and `.nojekyll`.
2. Go to **Settings → Pages**.
3. Select **Deploy from a branch**, choose **main** and **/ (root)**, then save.

Updates to `main` are published automatically.
