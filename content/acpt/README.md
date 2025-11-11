# Notes normalization

This folder contains various `.md` notes. The `scripts/normalize_markdown.py` script standardizes them to cleaner Markdown and fixes image references.

What it does:

- Converts HTML underline headings like `<u>Title</u>` and `**<u>Title</u>**` to `#`/`##` Markdown headings
- Rewrites `<img ...>` tags to Markdown image syntax `![alt](path)`
- If an image path ends with `.tmp`, it tries to replace it with a real image next to it: prefers `.png`, then `.jpg`/`.jpeg`, `.webp`, `.gif`
- Normalizes list bullets to `- ` and improves spacing around headings
- Wraps obvious code-like lines into fenced code blocks when possible
- Adds minimal YAML front matter with `title` (derived from the first heading or filename) if none exists

Run it:

```bash
python3 scripts/normalize_markdown.py .
```

After running, spot-check a few files to ensure headings, lists, and images look correct. If a `.tmp` image has no matching real file, the original reference is kept.

## Hugo sites: rewrite image paths to static

If you've moved images into your Hugo `static/media/` directory, update Markdown image links from relative `media/media/...` to absolute `/media/...` with:

```bash
python3 scripts/update_image_paths.py .
```

This will turn:

- `![alt](media/media/image1.png)` -> `![alt](/media/image1.png)`
- `<img src="media/media/image1.png">` -> `![image1](/media/image1.png)`

Adjust the `ROOT_MEDIA_PREFIX` constant in `scripts/update_image_paths.py` if your site uses a different static subfolder (e.g., `/images/`).
