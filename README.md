# Trefoil — Emotion States

Single-file demo: a morphing trefoil knot with per-mood animation presets (Streaming + Header categories). Tweak sliders in the panel, preview in the SVG, and share your settings.

## Files

| File | Purpose |
|------|---------|
| `trefoil-demo.html` | Full app (HTML, CSS, JS). Open this in a browser. |
| `index.html` | Redirects to `trefoil-demo.html` and **preserves** `?data=...` (for shorter GitHub Pages URLs). |

## Run locally

Open `trefoil-demo.html` in a browser (double-click or drag into Chrome/Safari/Firefox). No build step.

## Live site (GitHub Pages)

After Pages is enabled on this repo (**Settings → Pages → Deploy from branch `main` / root**):

- **https://swicknick.github.io/trefoil-demo/trefoil-demo.html**
- Shorter entry: **https://swicknick.github.io/trefoil-demo/** (redirects to the demo and keeps share links intact)

## Share settings

1. Open the **hosted `https://…`** page (not a `file://` link—those only work on your machine).
2. Adjust presets; the address bar updates with a `?data=` parameter (compressed state).
3. Use **Copy share link** in the panel, or copy the full URL from the address bar, and send it. Opening that link restores the same moods and globals.

If a chat app truncates a very long URL, use **Copy All Presets** and send the JSON instead.

## Git

```bash
git clone https://github.com/swicknick/trefoil-demo.git
cd trefoil-demo
# open trefoil-demo.html
```

## Presets in code

`window.setTrefoilEmotion('working')` etc. are available for embedding or tests—see the script in `trefoil-demo.html`.
