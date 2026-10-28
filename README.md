# ezhuthu-packs

These are the public template packs and the font catalogue for the **Ezhuthu** Malayalam typography app. The app reads them from `raw.githubusercontent.com`, and they need no key.

- `index.json` lists the packs. Each pack has `presets`, which use the same fields as the app's built-in presets, and `stickers`, which are inline SVG.
- `fonts.json` points only to SIL OFL 1.1 Malayalam fonts in github.com/google/fonts. Each entry includes its licence URL.
- All artwork here is original and contains no third-party images.

To add a pack, add `packs/<id>.json` and list it in `index.json`. The app picks it up without an update.
