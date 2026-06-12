# Anna Nam Lab

This repository contains the static website for the Anna Nam Lab at Weill Cornell Medicine.

The site is organized for straightforward editing on GitHub Pages. Each public page has its
own `index.html`, shared styling lives in one CSS file, and site images are stored with
readable filenames.

## Site Structure

- `index.html` - home page
- `research/index.html` - research overview
- `team/index.html` - lab members and bios
- `publications/index.html` - selected publications
- `funding/index.html` - funding acknowledgments
- `labnews/index.html` - lab news and awards
- `contact-us/index.html` - contact and join information
- `assets/css/site.css` - shared site styling
- `assets/js/site.js` - mobile navigation behavior
- `assets/images/` - page images, portraits, figures, and logos

## Editing Content

Most content edits only require changing the HTML file for that page.

Look for comments that start with `EDIT`, `ADD`, `REMOVE`, or `COPY`. They mark the safest
places to change page text, duplicate a team member, add a publication, or update a logo.

For images, add the file under the relevant folder in `assets/images/`, then update the
matching `<img src="...">` line in the page HTML.

## Publishing

GitHub Pages serves this repository from the `main` branch. After edits are committed and
pushed, GitHub Pages will rebuild and publish the site automatically.
