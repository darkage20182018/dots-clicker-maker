# DOTS Clicker Maker

Free and open-source, fully client-side tool that turns any 3D model or image into a two-part snap-click fidget toy.

## What it does

- Upload any STL (binary or ASCII) or OBJ model
- Or upload an image (PNG, JPG, WebP) and turn it into a raised relief plaque clicker
- Or turn a photo into a full 3D model, free, via public Hugging Face Spaces (no account or key; TRELLIS.2 first, then Stable Fast 3D and TripoSR; free use is capped at roughly 1-2 heavy generations per person per day)
- Parametric snap-click cutter: size 8-30 mm, finger thickness, lip depth, clearance
- Auto-placement at mid-height, auto-scale for small models (applied scale shown)
- Move the cutter with X/Y/Z steppers, numeric inputs, or drag
- Regular (flat seam) and Embedded (hidden seam) styles
- Exploded preview and per-part visibility toggles
- Export Bottom STL, Top STL, or both as a ZIP (binary STL, 1 unit = 1 mm)
- Print settings panel: 0.16-0.20 mm layers, 3-4 walls, 20-30% infill, PLA/PETG, cut-side-down, brim for small parts

## Use

Open `index.html` in any modern browser. No install, no signup, no server. Your model never leaves your computer, except the optional Photo to full 3D step, which sends your photo to a public Hugging Face Space to generate the model.

## License

MIT - see LICENSE. Original implementation by DOTS.
