# SPU e-Brief — July 2026 (Animated Web Edition)

A self-contained, animated web version of the SPU e-Brief. It opens in any browser and
runs page-flip transitions, page-entrance animations, zoom, thumbnails, auto-play and
fullscreen — no plugins, no internet, no account needed.

## What to publish
Use **`SPU eBrief - July 2026 (Web Ebook).html`** (crisp text, correct fonts, all animations).

## Host it on GitHub Pages (5 minutes)
1. Rename the file **`SPU eBrief - July 2026 (Web Ebook).html`** to **`index.html`**.
2. Create a new GitHub repository (e.g. `spu-ebrief`).
3. Upload **`index.html`** and the empty **`.nojekyll`** file to the repository root
   (drag-and-drop in GitHub's web uploader works).
4. In the repo: **Settings → Pages**.
5. Under *Build and deployment*: **Source = Deploy from a branch**,
   **Branch = `main`**, folder **`/ (root)`** → **Save**.
6. Wait ~1 minute, then refresh. Your live link appears at the top of the Pages settings:
   `https://<your-username>.github.io/spu-ebrief/`
7. Share that link with your client.

## Notes
- The `.nojekyll` file (already included) stops GitHub from altering the page — keep it.
- The HTML is large (~9 MB) because every page image is embedded; GitHub Pages serves it fine,
  it just loads on the first visit.
- Controls: arrow keys / on-screen arrows / click the page edges / swipe to turn pages;
  buttons for First, Pages (thumbnails), Zoom, Auto-play, Fullscreen, Last.
