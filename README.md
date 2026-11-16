# GeoStreamFusion — project site

Static website for the GeoStreamFusion M.Tech project (IIT Tirupati, 2026).

| Path | What it is |
|---|---|
| `index.html` | Landing page |
| `architecture/` | Animated architecture walkthrough (single self-contained HTML file) |
| `viewer/` | Side-by-side 3D viewer: our reconstructions vs the native-4K reference, plus the input video |
| `poster/` | A1 poster (PDF and LaTeX source with figures) |

## Hosting with GitHub Pages

1. On GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
3. After a minute the site is live at `https://<user>.github.io/3D_construction/`.

The site has no build step. `.nojekyll` makes GitHub serve every file as is.

## Notes

- The 3D models are reduced web copies (about 20–35 MB each). The full-resolution combined model (112 MB) is left out because GitHub rejects files over 100 MB.
- All timings were measured on one GPU shared with another training job.
- F-scores are measured against the native-4K reconstruction at 1% of scene size, in the same camera frame.

Venkatasai Eswar Nandu · Atul Tripathi · M Rajvardhan · Supervisor: Dr. Chalavadi Vishnu
