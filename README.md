# Boilerpipe Site Audit Test Site V2

This static website is designed for GitHub Pages and for testing Site Audit features where Boilerpipe or fallback text extraction is used.

## Test goals

### Similar / duplicate content

Compare:

- `espresso-review.html`
- `espresso-guide.html`

Expected:

- These two pages should be detected as similar because their main article text is highly overlapping.
- Boilerplate header/sidebar/footer text should not be the main reason they are considered similar.

### Link Opportunities

Pages with unlinked mentions:

- `espresso-review.html`
- `espresso-guide.html`
- `fallback-keyword-page.html`

Unlinked phrases:

- `coffee bean storage` should suggest `bean-storage.html`
- `milk frothing basics` should suggest `milk-frothing.html`
- `espresso-review` should suggest `espresso-review.html`

### Fallback text extraction

Use:

- `fallback-keyword-page.html`

Expected:

- If Boilerpipe text is unavailable or weak, simple HTML text extraction should still find:
  - `coffee bean storage`
  - `milk frothing basics`

## GitHub Pages

1. Create a GitHub repository.
2. Upload all files.
3. Go to Settings > Pages.
4. Deploy from the main branch root.
5. Crawl the published GitHub Pages URL.
