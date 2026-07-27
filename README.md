# ARRC Website

Live site built as static pages for GitHub Pages.

## URLs (once published)
- `/`                              Home
- `/Research`                      Research agenda
- `/Pillars`                       Research pillars
- `/Pillars/workforce-and-expertise`
- `/Pillars/governance-capacity`
- `/Pillars/structural-and-societal-impacts`
- `/Pillars/data-and-analytical-infrastructure`
- `/People`                        People & members
- `/Events`                        Calendar & events
- `/News`                          News & press
- `/Join`                          Get involved

## How it works
Every page is a self-contained HTML file. Navigation between sections uses real
links, so each section has its own shareable address and the browser Back/Forward
buttons work.

## Editing content
The editable source is `ARRC Site.dc.html` (kept in the project workspace). All
text — pillars, members, news, events, the stipend count — lives in one data
section near the bottom of that file. After editing the source, the static pages
in this folder are regenerated from it.

## Publishing (GitHub Pages)
1. Push this `arrctest/` folder's contents to the repo root (or set Pages to serve
   from this folder).
2. Settings → Pages → Deploy from a branch → main → root → Save.
3. Your site appears at https://<username>.github.io/arrctest/
