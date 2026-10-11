# Supported-language artwork

Lossless WebP copies of existing game assets from
`/Users/bentiden/code/edex/Assets/NewUI/Images/Flags/`.

The original 256×256 PNGs use identical transparent padding. Their visible
flag area was cropped to `(6, 53, 250, 203)` (left, top, right, bottom),
preserving every nontransparent pixel and a one-pixel surrounding margin.
Italy, Korea, and Poland are opaque rectangular source images, so their full
contents and native dimensions are preserved. No images were upscaled.
Use CSS on the containing frame for consistent rounded corners.

The landing page uses `ja-flat.svg` for Japan: a white field and red disc,
without the outline baked into the original game artwork. The shared CSS clips
the flags to rounded corners, with no surrounding background, border, or shadow.

`mx.webp` comes from the game's `es-flag.png`, visually verified as Mexico.
Chinese assets display the existing 简体 and 繁體 characters, respectively.
All outputs were decoded and verified to preserve alpha and every visible
source pixel exactly after the padding crop.

| File | Dimensions | Bytes | Source |
| --- | --- | ---: | --- |
| `de.webp` | 244×150 | 520 | `de-flag.png` |
| `fr.webp` | 244×150 | 580 | `fr-flag.png` |
| `ja.webp` | 244×150 | 1,422 | `ja-flag.png` |
| `mx.webp` | 244×150 | 9,472 | `es-flag.png` |
| `nl.webp` | 244×150 | 536 | `nl-flag.png` |
| `zh-hans.webp` | 244×150 | 2,628 | `zh-simple-flag.png` |
| `zh-hant.webp` | 244×150 | 4,718 | `zh-trad-flag.png` |
| `kr.webp` | 320×213 | 1,974 | `kr-flag.png` |
| `it.webp` | 320×213 | 106 | `it-flag.png` |
| `pl.webp` | 320×200 | 50 | `pl-flag.png` |
