# The Deep — website

Static one-page site for The Deep, the MIT AeroAstro prototyping shop and makerspace.
No build step and no JavaScript.

## Files

- `index.html` — all page content. Each section starts with a comment block explaining how to edit it.
- `css/style.css` — all styles. Colors, fonts, and spacing are variables at the top of the file.
- `images/` — photos. Use lowercase, hyphenated file names.

## Publish on GitHub Pages

1. Push these files to the repository's default branch.
2. In the repository, open Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select the branch and the `/ (root)` folder, and save.

## Style

Colors and fonts follow the AeroAstro style guide: blue `#004d90`, gray `#808084`, the supplemental palette, Roboto for headings, and Barlow for text. All are variables in section 1 of `css/style.css`.

## Open items

Search `index.html` for `TODO` to find them.

- Logo files (header currently uses a text wordmark)
- Headshots for the team section
- Price list
- Cost object payment link
- Building, room number, and hours
- Team website links
- Final hero image, if different

## Accessibility checklist for edits

- Every image needs `alt` text that describes the photo.
- Every `<iframe>` needs a `title`.
- Keep headings in order (`h2` for sections, `h3` inside them).
- Link text should say where the link goes.
