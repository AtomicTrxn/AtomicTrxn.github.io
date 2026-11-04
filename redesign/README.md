# Portfolio redesign (draft)

Design exploration for the portfolio. Not the live site: nothing here is linked from the root `index.html`.

- `Portfolio.dc.html` — working page (palette toggle, tech filter, gallery, scroll-spy)
- `Portfolio System.dc.html` — tokens, type, components, motion spec, rationale
- `DeviceFrame.dc.html` — browser / phone / macOS / desktop frames used by both
- `support.js`, `image-slot.js`, `_ds/` — runtime and Broadsheet styles; keep paths as-is

Preview on GitHub Pages at `/redesign/Portfolio.dc.html`.

- Content is the `PROJECTS` array near the bottom of `Portfolio.dc.html`, in two groups: projects I own, then projects I contribute to.
- Screenshots live in `img/<project>/` as WebP and are passed to `DeviceFrame` through its `src` prop. Projects without screens use a step diagram (`frame: 'diagram'`, `steps`).
- Conduit for Android still needs screenshots (placeholder shown).

## Add to the repo

```sh
cd AtomicTrxn.github.io
git checkout main && git pull
git checkout -b redesign-draft
# copy this redesign/ folder into the repo root
git add redesign
git commit -m "Add portfolio redesign draft in /redesign"
git checkout main
git merge --no-ff redesign-draft
git push origin main
```
