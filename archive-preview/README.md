# Distinct Archives — Minimal Index / V2

A restrained archive prototype, independent from the live homepage.

## Preview
`https://distinctarchives.com/archive-preview/`

## Visual direction
- Paper white (#fafaf8) and black/grey only
- Small, systematic typography; wide editorial margins; hairline rules
- Quiet alphabetical/numeric archival framing and whitespace
- No oversized hero, gradients, color-block mockups, artificial project images, decorations or unnecessary motion
- 4-item index: Capo, New Age, Distinct: Uncensored and original /404
- Minimal functional filters (All, Commissioned, Independent), native expandable project records
- Mobile responsive and keyboard accessible via native HTML details

## Image accuracy
The /404 project includes the **original supplied artwork**. The other three project imagery slots deliberately do **not** contain fabricated logos or mockups; they await actual project files.

## Deployment and editing
The preview is fully self-contained in `archive-preview/index.html` (HTML + CSS + very small JS filter). No external third-party libraries. Favicon uses the original studio logo from `../favicon.svg`.

`archive-preview/style.css` and `archive-preview/app.js` are **legacy V1 artifacts** and are **no longer loaded** by V2; they can be removed after design approval.

The public site's `/index.html`, `/404.html`, `/CNAME` and website DNS records are unchanged. This prototype is in a separate route and has a noindex directive, but remains publicly accessible by URL. Do not include private client work in this preview.
