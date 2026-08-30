# fleet-assets
Static assets for the J Noir Wix properties (visithaverhill, noahsarkmerch,
winthropbythesea, rumblytummy). Served via raw.githubusercontent.com.
Public on purpose — nothing sensitive lives here, ever.

## newtv/

`newtv/index.html` — the NEW TV portal. Single self-contained page; all
content streams from the Internet Archive at runtime. Intended to be served
over HTTPS (GitHub Pages) and embedded in Wix via Embed-a-Site.

`newtv/newtv-portal.js` — the same portal as a Wix custom element
(tag `newtv-portal`), for sites wired to Wix Git Integration. Destined for
`src/public/custom-elements/` in a site's Velo repo; staged here until that
repo exists.
