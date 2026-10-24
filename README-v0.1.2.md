# Gameston Icons v0.1.2

Browser-safe rebuild of the v0.1.1 category glyph additions.

Preserves all 50 glyphs from v0.1.0 and adds 7 category glyphs:

| Codepoint | Class | Source |
|---|---|---|
| U+F300 | gs-playstation-brand | Ionicons `logo-playstation` |
| U+F301 | gs-xbox | Tabler `brand-xbox` |
| U+F302 | gs-nintendo | Tabler `device-nintendo` |
| U+F303 | gs-mobile | Tabler `device-mobile` |
| U+F304 | gs-anime | Tabler `mask` |
| U+F305 | gs-pop-culture | Tabler `sparkles` |
| U+F306 | gs-tips | Tabler `bulb` |

The existing `gs-playstation` glyph is preserved unchanged and remains the controller icon.

Technical fix from v0.1.1: SVG cubic curves are explicitly converted to quadratic TrueType outlines before font generation, making the resulting TTF/WOFF2 accepted by Chromium/browser FontFace validation.

The font family name remains `Gameston Icons` for compatibility with the existing Wuzz template CSS.

Serve the WOFF2 from the `v0.1.2` GitHub tag.
