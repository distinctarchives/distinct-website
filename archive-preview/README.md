# Distinct Archives — Image-led Archive / V4

**Preview:** https://distinctarchives.com/archive-preview/

This is a dedicated *preview* path. The site's root homepage still displays the original /404 artwork. GitHub Pages and the domain CNAME are unchanged.

## Design
- Image-first two-column editorial gallery (one column on mobile)
- Project titles/categories as short captions under each visual
- Small navigation, restrained typography, no large hero or numbered index
- Four projects: Capo, New Age, Distinct: Uncensored, /404
- Click a thumbnail to open a large image viewer; Esc or Close exits
- No analytics, external dependencies or paid services

## Sources / publication note
- Capo thumbnail and additional view use actual images extracted from **Branding Presentation V3 - Capo.pdf**, previously supplied by the studio.
- /404 uses the studio's original supplied artwork.
- New Age and Distinct: Uncensored deliberately use *neutral image placeholders*. No fabricated client work.
- Replace or remove the Capo artwork if its public display isn't yet cleared with the client; although noindex is set, this preview URL is public to anyone who has it.

## Implementation
Everything is inside `archive-preview/index.html`; visual image data are embedded, so thumbnails need no external host. The original logo is at `../favicon.svg`. The old V1 `app.js` and `style.css` remain unused and are not loaded.

Edit image content from the HTML's `project-media` image elements and `PROJECTS` gallery map. Adjust spacing and layout inside its inline `<style>`.
