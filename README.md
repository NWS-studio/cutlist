# Cutlist Optimizer

Self-contained cut-planning tool. Linear stock and sheet goods, kerf, remnants,
and least-cost stock selection against real yard pricing.

**Live:** https://nws-studio.github.io/cutlist/

Runs entirely in the browser — no login, no install, nothing sent anywhere.
Paste a parts list (a Grasshopper dump works as-is — one per line, 1 of each),
adjust quantities per line, set stock and kerf, optimize. Export the plan as
text, CSV, or PDF (via print), or copy a link that encodes the whole cutlist.

**Parts longer than the stock** (linear mode): tick *Join stock for parts longer
than the stock*. Each over-length part is split into full-length sticks plus one
shorter piece, and those pieces are packed with the rest of the list. A
*Joined parts* table says where each piece is cut. An optional minimum piece
length keeps joints off slivers.

## Editing
`index.html` is the entire app. Edit it, commit to `main`, and GitHub Pages
redeploys automatically.
