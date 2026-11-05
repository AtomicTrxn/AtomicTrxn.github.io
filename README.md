# AtomicTrxn.github.io

Personal portfolio site, served by GitHub Pages from `main`. Static files, no build step.

- `index.html`: the page. It renders client-side through `support.js`, so all content is data near the bottom of the file: `PROJECTS` (two groups, projects I own then projects I contribute to), `STATS` and `HOW`. Card tile sizes are in `TILE` and the reading order in `ORDER`.
- `DeviceFrame.dc.html`: browser, phone, macOS and desktop frames for screenshots (loaded by name from this folder).
- `Portfolio System.dc.html`: design tokens, type, components and motion notes.
- `support.js`, `image-slot.js`, `_ds/`: runtime and Broadsheet styles; keep paths as they are.
- `img/<project>/`: screenshots as WebP. Projects without screens use a step diagram (`frame: 'diagram'`, `steps`).
- `Tom_Hess_Resume.pdf`: the public resume (no phone number or ZIP).
- `redesign/Portfolio.dc.html`: redirect from the old preview URL to the root.

Never publish a phone number or ZIP code on this site.
