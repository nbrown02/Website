# Nicolas Brown static site

Static replacement for the Squarespace site.


Local testing: double-click index.html. Links and styling now use relative paths so it also works on Cloudflare Pages/GitHub Pages.


## Organisation logo carousel

The homepage carousel uses local placeholder SVG files in `assets/logos/`.

Replace these files with the real organisation logos, keeping the filenames exactly the same:

- `assets/logos/asos.png` — ASOS
- `assets/logos/pwc.png` — PwC
- `assets/logos/psychiatry-uk.png` — Psychiatry UK
- `assets/logos/kingfisher.png` — Kingfisher PLC
- `assets/logos/nationwide.png` — Nationwide
- `assets/logos/royal-mail.png` — Royal Mail
- `assets/logos/hiscox.png` — Hiscox
- `assets/logos/red-gazette.png` — Red Gazette
- `assets/logos/gov-uk.png` — GOV.UK
- `assets/logos/alpitour-world.png` — Alpitour World
- `assets/logos/abn-amro.png` — ABN AMRO
- `assets/logos/thycotic.png` — Thycotic
- `assets/logos/kongsberg-digital.png` — Kongsberg Digital
- `assets/logos/novia-financial.png` — Novia Financial
- `assets/logos/stedin.png` — Stedin
- `assets/logos/allegion.png` — Allegion
- `assets/logos/scor.png` — SCOR
- `assets/logos/att.png` — AT&T
- `assets/logos/natwest.png` — NatWest

Recommended replacement format: SVG where possible. PNG is also fine, but keep the same filename extension if you do not want to edit the HTML.
The CSS forces each logo into the same display frame, so different source dimensions will still render consistently in the carousel.
