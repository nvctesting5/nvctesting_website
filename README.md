# Boilerpipe Test Site

A small static website for testing Boilerpipe and Site Audit behavior.

## Test cases

### Similar / duplicate content

Compare:

- `espresso-machine-review.html`
- `espresso-machine-guide.html`

Both pages share some article text, but they also share repeated header/sidebar/footer boilerplate.

Without Boilerpipe, template text can make the pages look more similar than they really are.

### Link Opportunities

`espresso-machine-guide.html` contains these unlinked mentions:

- `coffee bean storage` -> should suggest `coffee-beans.html`
- `espresso-machine-review` -> should suggest `espresso-machine-review.html`

### Boilerplate-heavy layout

Each page contains repeated:

- header navigation
- sidebar popular posts
- footer links

This helps test whether Boilerpipe removes non-main content correctly.

## GitHub Pages

Upload these files to a GitHub repository, then enable GitHub Pages from the repository settings.
