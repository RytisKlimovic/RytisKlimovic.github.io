# Rytis Klimovič — CV / Portfolio

Single-page portfolio. Pure HTML/CSS/JS — no build step, no dependencies.

## Files
- `index.html` — content / structure
- `styles.css` — styling (dark + gradient theme)
- `script.js` — nav, mobile menu, scroll reveal
- `CONTENT.md` — **fill in missing info here**, then ask Claude to "atnaujink"
- `assets/` — put `profile.jpg` (photo) and optional `cv.pdf` here

## Preview locally
Just open `index.html` in a browser. Or run a tiny server:

```powershell
# PowerShell
python -m http.server 8000
# then open http://localhost:8000
```

## Add your photo
1. Drop a square image at `assets/profile.jpg`
2. In `index.html`, find the `photo-placeholder` div and replace with:
   ```html
   <img src="assets/profile.jpg" alt="Rytis Klimovič" />
   ```

## Deploy (free) — GitHub Pages
1. Create a GitHub repo, push these files.
2. Repo → Settings → Pages → Source: `main` branch, `/root`.
3. Site goes live at `https://<username>.github.io/<repo>/`.

Alternatives: Netlify or Cloudflare Pages — drag-and-drop the folder.
