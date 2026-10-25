# AR Origami - GitHub Pages site

Site URL: https://jvebedumbava13-ai.github.io/origami-ar

## Files

- `index.html` - 3D + AR viewer for one model (`?id=01` ... `?id=20`), step controls from `models.json`
- `arena.html` - MindAR target arena (needs `assets/targets/targets.mind`)
- `vault.html` - printable backup sheets form (needs a Formspree form ID and `assets/pdf/all_20_backup_sheets.pdf`)
- `shop.html` - store page (replace the Amazon `YOUR_ASIN_*` placeholders)
- `models.json` - titles, difficulty and step hints for the 20 models (hints are placeholders)

## Still missing before the site works

1. `assets/glb/model_01.glb` ... `model_20.glb` and `assets/usdz/*.usdz` - export from `blender_origami_generator.py`.
2. `assets/targets/targets.mind` - compile `cover_arena_target.png` with the MindAR compiler.
3. Real step hints in `models.json`.
4. Formspree form ID in `vault.html`, Amazon ASINs in `shop.html`.

## Publish

Settings > Pages > Branch: `main` / root > Save.
