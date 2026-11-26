# E‑Rickshaw Gully Rush 3D

A third‑person 3D rickshaw game — now with **curved roads** and a **drift system**.
Runs in any modern browser on phone, tablet and desktop. No build step, no dependencies to install.

## Controls

| | Desktop | Phone / Tablet |
|---|---|---|
| Steer | ← → or A D | Drag a finger anywhere |
| Drift | Hold **Shift** or **X** while steering | Hold the **DRIFT** button |
| Boost / Slow | ↑ W / ↓ S | **BOOST** button |
| Horn | Space | – |

**Drifting:** start a drift while steering. The rickshaw slides, smokes and leaves skid marks while a meter charges
(blue → orange → purple). Release to get a mini‑turbo. Roads curve and push you toward the outside — drifting *into*
the bend cancels most of that push, charges twice as fast and scores bonus points. Scraping the road edge drains your charge.

## Put it live on GitHub Pages

1. Create a new repository on GitHub (e.g. `gully-rush`), set it to **Public**.
2. Click **Add file → Upload files**, drag in **`index.html`** (keep that exact name), and commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
5. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`

On a phone, open the link and use **Share → Add to Home Screen** to play full‑screen.

## Notes

* three.js is loaded from a CDN (cdnjs, with a jsDelivr fallback), so players need an internet connection.
* Best score is saved in the browser's local storage.
