# sqlfmt

> **Retired.** This repository is no longer maintained or deployed.
> [sqlfum.pt](https://sqlfum.pt/) is served from GitHub Pages by
> [madelynnblue/sqlfmt](https://github.com/madelynnblue/sqlfmt), where
> development continues. To format SQL locally, use `cockroach sqlfmt`.

Experimental SQL formatter with width-aware output

Based on http://homepages.inf.ed.ac.uk/wadler/papers/prettier/prettier.pdf.

# Deployment

This used to run as the `sqlfmt` deployment on the `prime` GKE cluster in
`cockroach-dev-inf`, behind the `sqlfum.pt` host on `crdb-dev-ingress`.
After sqlfum.pt's DNS moved to GitHub Pages in 2025, that deployment got only
scanner traffic, so it was removed (DEVINF-1960).
