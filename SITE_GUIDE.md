# Your Academic Astronomy Website — visual design guide

This version keeps the original Strata template but adds a dark astronomy theme.

## Current design
- Modern academic structure
- Circular profile photo
- Dark galaxy background
- Light blue/icy blue accent color
- Serif typography
- Hybrid navigation: homepage + Research + Publications + CV pages
- Responsive layout for phones/tablets

## The easiest file to edit for appearance
`assets/css/custom.css`

At the top of that file you will find the main visual settings:

- `--bg` = overall dark background
- `--text` = normal text
- `--heading` = headings
- `--accent` = links and blue accents
- `--border` = borders/dividers

You can also change the font and sizes in the same file.

## Photos
Replace `images/avatar.jpg` with your own headshot. Keep the filename `avatar.jpg` if you want to avoid changing HTML.

## Galaxy background
The current file is `images/galaxy-placeholder.svg`. Replace it later with your own galaxy image if you have one. If you name your image `galaxy.jpg`, change the two references in `assets/css/custom.css` from `galaxy-placeholder.svg` to `galaxy.jpg`.

## Content
- `index.html` = homepage
- `research.html` = detailed research
- `publications.html` = full publication list
- `cv.html` = web CV
- `files/CV.pdf` = downloadable CV

## Important
You do not need to edit the original `assets/css/main.css`. The new `custom.css` is loaded after it and overrides the visual choices. This makes future customization much easier.
