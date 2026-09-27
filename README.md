# Lineager
 
An interactive family tree you can explore from anyone's point of view. Pan and zoom across generations back to 1400, switch the viewpoint to any person and every label updates to their perspective (your dad becomes your uncle's brother), and scrub the timeline on the right to jump generation by generation.

**Live:** https://julianhilgemann.github.io/lineager/

On iPhone or iPad, open the link in Safari and choose Share → Add to Home Screen to use it full-screen like an app.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: markup, styles, data model and logic in one file |
| `manifest.webmanifest`, `*.png` | Home-screen icon and standalone app mode |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Updating

Replace `index.html` with a new version and commit. GitHub Pages redeploys within about a minute.

## Data and privacy

The tree currently contains generated sample people. Edits and photos made in the app are stored only in that browser (localStorage) and are never uploaded. This site is publicly reachable, so don't commit real family data into this repository unless you're fine with it being public.
