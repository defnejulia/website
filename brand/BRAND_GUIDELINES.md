# D.AGENCY — Brand Guidelines

> Source: **D.AGENCY Brand Bible, June 2025** (`brand/D.AGENCY_Brandbible.pdf`).
> This is the single source of truth for all D.AGENCY website development. When building
> any UI, pull colors, type, logos, and the Spark element from here.

## About the brand

**D.AGENCY** is the new creative force in social media. From strategy to content, we help
brands grow, engage, and stand out across all platforms. **Bold ideas, real results — always on trend.**

- **Voice:** bold, confident, energetic, trend-aware, creative.
- **Personality:** expressive, playful, modern, premium.

---

## Logos

Three official lockups. Source vectors live in `brand/logos/source/` (`.ai` + `.eps`);
web-ready transparent PNGs are in `brand/logos/`.

| # | Name | Usage |
|---|------|-------|
| **Logo 01** | Compact with Text Logo | Tight spaces or as a standalone brand mark |
| **Logo 02** | Compact with Text Logo | Small or square spaces where clarity is key |
| **Logo 03** | Text Logo | Clean horizontal surfaces, for optimal visibility/legibility |

Available compact-mark files:
- `brand/logos/dagency-compact-orange.png` — primary (Spicy Orange)
- `brand/logos/dagency-compact-pink.png` — Baby Pink variant

> Only the Orange and Pink compact marks were supplied as vectors. If you need the text
> logo (Logo 03) or other color variants for the site, ask Defne for the source files.

---

## Colours

Primary brand color is **Spicy Orange**. The full palette:

| Name | HEX | RGB | CMYK | Role |
|------|-----|-----|------|------|
| **Spicy Orange** | `#f82303` | 248 / 35 / 3 | 0 / 92 / 100 / 0 | Primary — logo, CTAs, accents |
| **Sandy Beige** | `#eeeae1` | 238 / 234 / 225 | 8 / 7 / 13 / 0 | Light background / surface |
| **Azure Blue** | `#1a4999` | 26 / 73 / 153 | 97 / 75 / 1 / 0 | Secondary accent |
| **Baby Pink** | `#ffb2c2` | 255 / 178 / 194 | 0 / 36 / 10 / 0 | Soft accent / highlight |
| **Little Red** | `#890033` | 137 / 0 / 51 | 37 / 100 / 66 / 35 | Deep accent / contrast |

> Note: the Brand Bible prints Sandy Beige's RGB as "238/234/25" next to hex `#eeeae1`.
> `#eeeae1` = RGB 238/234/**225**, so the "25" is a truncated "225". We use `#eeeae1`.

---

## Typography

| Font | Weight | Use for |
|------|--------|---------|
| **Hanken Grotesk** | Bold | Headlines & sublines |
| **Hanken Grotesk** | Regular | Body / flowing text |
| **Anton** | Regular | Very expressive, oversized headlines |
| **Qwitcher Grypen** | Regular | Small handwritten-style accents |

- **Hanken Grotesk** and **Anton** are on Google Fonts.
- **Qwitcher Grypen** is on Google Fonts (use sparingly, for accents only).
- Default headline = Hanken Grotesk Bold. Reach for **Anton** when a headline should shout.

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Hanken+Grotesk:wght@400;700&family=Qwitcher+Grypen:wght@400;700&display=swap" rel="stylesheet">
```

---

## Design elements

### The Spark
The signature 4-point sparkle. It IS the brand mark's accent and the core graphic device.
SVGs in `brand/elements/`:
- `spark.svg` — uses `currentColor` (recommended; color it with CSS)
- `spark-orange.svg`, `spark-pink.svg`, `spark-blue.svg`, `spark-beige.svg`, `spark-red.svg`

Use the Spark for:
- **Bullet points** (replace list markers)
- **A little extra glow** — scatter as decorative accents around hero text/imagery
- Loading/sparkle moments and hover delights

### Arrow `->`
Directional accent for links, CTAs, "next" affordances.

### Call-to-action badges
Bold pill/sticker labels in Spicy Orange, e.g. **NEW**, **REEL**, **GIVEAWAY**, **BOOK NOW!**
Use uppercase, heavy weight (Anton or Hanken Grotesk Bold), high contrast.

---

## Quick usage

- Tokens: `brand/design-tokens.css` (CSS variables) and `brand/tokens.json`.
- Default to **Sandy Beige** backgrounds with **Spicy Orange** as the hero accent;
  use Azure Blue / Baby Pink / Little Red as secondary accents, not as primary fills.
- Pair **Anton** display headlines with **Hanken Grotesk** body for the on-brand contrast.
