# Kumpula Front Door — prototype

Prototype of kumpula.science (see the strategy: "The Kumpula Front Door").

## Pages
- `index.html` — front page: live proof strip, working search over the 129-group Kumpula Graph (v8 snapshot embedded), four ways in
- `group.html` — sample group page (Atmospheric Aerosols Research Group, INAR)
- `partner.html` — partner journey with the two-working-day promise
- `city-blend.html` — front page variant blended toward hel.fi / Helsinki Design System conventions

## Publish
1. Create a repo (e.g. `kumpula-front-door`), push these files.
2. Settings → Pages → Deploy from branch → main, root.
3. Site appears at `https://<user>.github.io/kumpula-front-door/`.

## Data
Group data is embedded in `index.html` (`<script id="kumpula-graph">`), extracted from the
Kumpula Innovation Dashboard v8. To refresh: re-export the graph to JSON and replace that block —
or, next step, move the data to `groups.json` and `fetch()` it, plus live publication counts from
the kumpula-pubs Cloudflare Worker (no CSP restrictions on GitHub Pages).

All figures marked with a small circle are illustrative. "Ask Kumpula" buttons mail kumpula-inno@helsinki.fi.
