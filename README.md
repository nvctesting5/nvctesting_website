# Boilerpipe-Resistant Static Website

A GitHub-ready single-page website designed to be visually readable for people while avoiding a long, article-like HTML body that older content extraction tools such as Boilerpipe often rely on.

## Files

- `index.html` — complete website in one file
- `.gitignore` — basic ignore rules
- `LICENSE` — MIT license placeholder

## Run locally

Open `index.html` in your browser.

Or run a tiny local server:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

Your site will be published at:

```text
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/
```

## Notes

This is not a security feature. It only reduces the usefulness of simple HTML text extraction. Anything visible in a browser can still be copied, screenshotted, OCRed, or read by more advanced crawlers.
