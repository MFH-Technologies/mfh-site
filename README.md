# mfhtechnologies.co.za

The MFH Technologies website: plain HTML and CSS, no build step, no outside scripts, fonts or cookies. GitHub Pages
serves this repository's `main` branch at mfhtechnologies.co.za (the `CNAME` file holds the domain).

- `index.html`: panels set into a white sheet. A stage with the statement across its foot and the gradient mark in
  the upper right; then full panels that stack over one another as you scroll (on screens at least 900 px wide and
  680 px tall): Tiekie on charcoal, with its platform drawn as its four parts and data moving between them;
  DalaDish in its own cream and chilli, with its logo and the real app (Today, the week, the list) turning in a phone
  in front of a slow wall of its suppers; and a charcoal panel to get in touch. Each product ends in a short register
  of owner and licensee or status. Say little on purpose: no client names, numbers or claims beyond these without
  Stephan's go-ahead.
- `assets/work/`: the DalaDish logo (light and dark, the same paths as on daladish.co.za), 18 dish photos and three
  app screens (from `docs/play-store/screenshots` in the DalaDish repository, resized to 506 x 900).
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

Motion: the statement rises word by word and the mark is drawn in from left to right on load; the mark drifts a few
pixels with the pointer, as one piece (it is never reshaped); scrolling away, the stage settles back slightly
(scroll-driven CSS, where the browser supports it). The product names and "Talk to us." rise once as they scroll
into view, the Tiekie parts appear one by one with points of data travelling between them, and the DalaDish app
turns every 3.4 seconds while its photos drift; both only while their panel is on screen. Nothing moves with
reduced motion, and without JavaScript everything simply shows.

Preview: `python3 -m http.server 8091` in this folder, then open http://localhost:8091. Publish: commit and push to `main`.
