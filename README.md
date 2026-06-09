# Image Gallery Boilerpipe Test Site

A GitHub Pages-ready static website with an image gallery and captions.

## Main tests

### Gallery captions

`gallery.html` has captions with unlinked mentions:

- `coffee bean storage`
- `milk frothing basics`

### Link Opportunities

Expected:

- `coffee bean storage` should suggest `bean-storage.html`
- `milk frothing basics` is intentionally unlinked and has no target page unless you add one

### Similar content

Compare:

- `gallery.html`
- `espresso-review.html`

They both mention beginner espresso setup, coffee bean storage, and milk frothing basics.

### Boilerplate

Repeated boilerplate appears in:

- header navigation
- sidebar
- footer

Boilerpipe should remove those and keep main article/gallery caption text.
