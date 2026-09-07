# diyarpolat.de

Personal site — a single static `index.html`, no build step, no dependencies.

Deployed on Cloudflare Pages:
- Build command: *(empty)*
- Output directory: `/`

Preview locally by opening `index.html` in a browser. There is nothing to run.

## Editing

Everything lives in `index.html`, split into commented sections: header,
about, experience, projects, education, honors, skills, contact. To add a
project, copy an `<article class="project">` block and edit it.

- The CV download link in the header is commented out. Drop a `cv.pdf` next to
  `index.html` and uncomment it to enable.
- The Kanoodle demo it links to is served separately, from a Jetson Xavier NX
  at `kanoodle.diyarpolat.de` (see the kanoodle-solver repo).

## Legal pages (German law)

`impressum.html` (§ 5 DDG) and `datenschutz.html` (Art. 13 GDPR) are linked
from the footer of every page. Both are `noindex` so the postal address stays
out of search results — the footer link keeps them legally reachable.

**Before deploying:** fill in the c/o address, marked `VORNAME NACHNAME
BRUDER / STRASSE HAUSNUMMER / PLZ ORT` in both files. It must be an address
where postal mail and formal court service reliably reach you.

Keep the two addresses identical, and update them if that address changes.
