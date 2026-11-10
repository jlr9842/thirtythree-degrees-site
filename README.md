# 33degrees.studio

The public website of Thirty-Three Degrees Studio. Static HTML/CSS, no build step, no trackers, no outside fonts
(the logo is vector outlines). Served by GitHub Pages from `main` at https://33degrees.studio (`CNAME`).

- `index.html`: the page. The hero logo is inline SVG so its parts animate (`.m-white`, `.m-low`, `.m-high`,
  `.m-bank`, `.m-name`, `.m-deg`; animation is off with Reduce Motion).
- `style.css`, `img/` (logo SVGs, icons, share image, game images from poolposition.app).
- Logos come from the brand generator in `jlr9842/thirtythree-degrees-studio` (`brand/`), not drawn here.

Publish: commit and push to `main`; Pages redeploys in a minute. Check the live page on desktop and at 375 px wide.
Public: nothing private goes in this repo.
