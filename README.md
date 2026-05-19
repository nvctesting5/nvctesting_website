# Coffee Boilerpipe Test Site - Updated

This updated version keeps the same original pages but adds clear test cases.

## Similar / duplicate content

Compare:

- espresso-machine-review.html
- espresso-machine-guide.html

Expected: these should be detected as similar because their main article text is intentionally very similar.

## Link Opportunities

Unlinked phrases:

- coffee bean storage -> coffee-beans.html
- espresso-machine-review -> espresso-machine-review.html
- milk frothing basics -> target page does not exist, useful as a negative/control case

Expected: Site Audit should detect unlinked mentions when the phrases are in extracted page text.

## Fallback text extraction

Use:

- contact.html

Expected: if Boilerpipe text is unavailable, simple HTML text extraction should still find coffee bean storage and espresso-machine-review.

## Note

Do not validate this only using a links CSV. Boilerpipe affects extracted page text, not normal link discovery.
