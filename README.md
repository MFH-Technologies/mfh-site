# mfhtechnologies.co.za

The MFH Technologies website: plain HTML and CSS, no build step, no outside scripts, fonts or cookies. GitHub Pages
serves this repository's `main` branch at mfhtechnologies.co.za (the `CNAME` file holds the domain).

- `index.html`: a poster in three parts. The statement set very large beside the gradient mark; the two sectors,
  each with its product (Tiekie, DalaDish) as the big name; and a charcoal band to get in touch. Say little on
  purpose: no client names, numbers or claims beyond these without Stephan's go-ahead.
- `privacy.html`: the website's privacy notice (GitHub Pages logs, email and calls only).
- `assets/`: the official MFH Technologies CI v2.0 artwork, copied unchanged from Drive
  (`Tiekie — Company/06-Brand/06-05_MFH-Technologies-CI`): the mark, lock-up and wordmark in colour and white.
  `site.css` holds the whole look.
- `assets/fonts/`: Inter 4 (Latin, variable), served from this site so visitors load nothing from other companies.
  SIL Open Font License 1.1 in `OFL.txt`.

Follow the CI: the gradient lives in the mark only; colour artwork on white, white artwork on charcoal (so dark mode
shows the white mark); Inter, headings in SemiBold, with the Arial and Helvetica fallback; no tagline; use ™ (never ®)
until MFH TECHNOLOGIES is registered. The home page header uses the wordmark because the mark sits right beside it in
the hero; other pages use the full lock-up.

Motion: the statement rises word by word and the mark is drawn in from left to right on load; the product names and
"Talk to us." rise once as they scroll into view. Nothing moves with reduced motion, and without JavaScript
everything simply shows.

Preview: `python3 -m http.server 8091` in this folder, then open http://localhost:8091. Publish: commit and push to `main`.
