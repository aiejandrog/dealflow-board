# DEALFLOW — published site

This repository holds **only the built pages** that GitHub Pages serves at
<https://aiejandrog.github.io/foreclosure-leads/>:

| Path | What it is |
| --- | --- |
| `docs/index.html` | the DEALFLOW board |
| `docs/call/`, `docs/call/carlos/` | Call Mode, one page per caller |
| `docs/hm-balloon-q7v3n8/` | the hard-money balloon book |
| `docs/img/` | property photos (Street View / aerial / listing) |

Everything personal on these pages — owner names, addresses, phone numbers,
what a homeowner wrote back — is **encrypted** into the page and only appears
after an access code is entered. Nothing readable is published here.

The engine that builds these pages (the scrapers, the enrichment chain, the
lead data, the send bridge) lives in the private `dealflow` repository. This
repo is a publish target: it is written to by the nightly refresh via
`publish_site.py`, and nothing is ever edited here by hand.
