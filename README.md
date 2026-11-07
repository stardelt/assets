# stardelt brand assets

The stardelt mark and wordmark as SVG: the primary gradient artwork, plus solid-black and solid-white versions with and without the wordmark.

![stardelt wordmark](logo-wordmark.svg)

## Files

| File | Artwork | Use on |
|---|---|---|
| `logo.svg` | mark, primary gradient | light backgrounds |
| `logo-wordmark.svg` | mark + wordmark, primary gradient | light backgrounds |
| `logo-black.svg` | mark, solid `#000000` | light backgrounds |
| `logo-white.svg` | mark, solid `#FFFFFF` | dark backgrounds |
| `logo-wordmark-black.svg` | mark + wordmark, solid `#000000` | light backgrounds |
| `logo-wordmark-white.svg` | mark + wordmark, solid `#FFFFFF` | dark backgrounds |

All files are SVG with a transparent background. The mark is `200×200`; the wordmark is `600×160`.

## Which one?

- **Product UI and docs** — the primary gradient (`logo.svg`, `logo-wordmark.svg`), as used by `stardelt-docs` and Nova.
- **One-colour print, embossing, favicons, watermarks** — the solid black or white variant.
- **Dark backgrounds** — `logo-white.svg` or `logo-wordmark-white.svg`; never place the black variant on a dark background.

## Usage

- Keep clear space around the mark equal to at least half the mark's width.
- Do not stretch, rotate, recolour, outline, add shadows, or place the mark on a busy photo.
- Use the wordmark when the name is not already visible; use the mark alone when space is tight.
- The wordmark is live text in the platform UI font stack. For print or a fixed outline, convert it to paths in your design tool.

## Source of truth

These files are mirrored in:

- `stardelt-docs/static/img/logo.svg` and `logo-wordmark.svg`
- `stardelt-nova/frontend/public/logo.svg` and `logo-wordmark.svg`

Change the asset here first, then sync the copies.

## License and trademark

The files are licensed under the Apache License 2.0 (see `LICENSE`). The stardelt name and logo are trademarks of stardelt; the license does not grant permission to use them as a trademark for a modified product.
