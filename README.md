# dogheartpdx.com

Website for **Dog Heart PDX** — Yarree's force-free pet care business in inner East Portland.

Single-page static site, no build step. `index.html` is the whole site (inline CSS, inline SVG logo + service-area map). The wreath logo is generated — see `yarree-career-ops/website/build_tally_form.py`'s sibling `gen_logo.py` in the career-ops project for the generator.

- **Contact forms:** Tally embeds — inquiry `jaAlJ1` (embedded at #contact), testimonials `2EGKlM` (linked from Kind Words)
- **Hosting:** GitHub Pages, custom domain `dogheartpdx.com` (see `CNAME`)
- **Planning docs:** `../yarree-career-ops/website/` (questionnaire, responses, site plan)

Local preview: `python -m http.server` in this folder.
