# Distinct Archives — Archive preview (v.01)

This is a deliberately isolated, first-pass portfolio concept at `/archive-preview/`. It does not replace the site's existing `/404` homepage.

## Concept
An evolving editorial index of commissions, independent work and research. Built with plain HTML, CSS and JavaScript, no frameworks or paid hosting.

## Included
- Responsive editorial homepage and typographic hero
- Numbered archive records: Capo, New Age, Uncensored, original /404 artwork, Visual Studies (future collection)
- List/grid switch, discipline filters and live text search
- In-page project record overlays with metadata and credits, hash URLs
- Keyboard support: `/` focuses search, `Esc` closes detail
- Respect for reduced-motion preferences; no tracking scripts

## Editorial accuracy
All Capo, New Age, Uncensored and Visual Studies cover art shown here is original *website-interface placeholder art*. It is **not** asserted to be approved client branding or real portfolio imagery. The /404 image is the original Distinct Archives graphic supplied for the holding page. Detailed project content must be reviewed and replaced with client-approved material before turning this into the public homepage. Current source copy is based on previously prepared Distinct Archives portfolio materials; the live Framer site was not retrievable for asset-by-asset migration.

## Edit
Project data and copy: `app.js`, `ITEMS` array. Visual covers: `visual(item)` in `app.js` plus `.visual-plate` selectors in `style.css`. Typography, color and layout: `style.css`.

## Deployment
Site files are at `archive-preview/index.html` in the public `distinctarchives/distinct-website` repository and should publish under the GitHub Pages site on its existing custom domain. `index.html` and `CNAME` at the repo root are unchanged; therefore the holding page remains the homepage. All prototype pages include `noindex,nofollow` (note: this does not make a public preview private).

When the design is approved, the archive can be moved to the repository root as the homepage, with the holding-page artwork retained in a `404.html` record.
