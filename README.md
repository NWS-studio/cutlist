# Cutlist Optimizer

Self-contained cut-planning tool. Linear stock and sheet goods, kerf, remnants,
and least-cost stock selection against real yard pricing.

**Live:** https://nws-studio.github.io/cutlist/

Runs entirely in the browser — no login, no install, nothing sent anywhere.
Paste a parts list (a Grasshopper dump works as-is — one per line, 1 of each),
adjust quantities per line, set stock and kerf, optimize. Export the plan as
text, CSV, or PDF (via print), or copy a link that encodes the whole cutlist.

## Editing
`index.html` is the entire app. Edit it, commit to `main`, and GitHub Pages
redeploys automatically.
