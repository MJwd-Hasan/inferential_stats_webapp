# Inferential Stats Webapp

A scroll-guided visual lesson on statistical inference, designed from the supplied course PDF and visually inspired by the playful, immersive scrolling language of the provided reference site.

## Learning sequence

1. Population vs. Sample
2. Parameters vs. Statistics
3. Point Estimation
4. Confidence Intervals
5. Hypothesis Testing
6. p-values

The page intentionally does **not** include an "Introduction to Statistical Inference" section.

## Visual direction

- Palette: `#15370D #728E6D #E5CD82 #FFF2B4 #FFEAD3 #BFE7EA #E89B5B #D46743 #7C0E44 #AA5E7A #D49A9A #F2DACE`
- Rounded, cartoon-like statistical symbols/charts
- Large readable typography
- Smooth scroll
- IntersectionObserver blur/reveal transitions
- Parallax/floating symbols
- Medium visible paper/grain texture
- Responsive layout and reduced-motion support

## Fonts

The CSS includes named hooks for Amoria, Bremlin, and Verve, with safe fallbacks.

Amoria and Bremlin are distributed by their authors as personal-use-only fonts, so their font files are intentionally **not** committed to this public repository. If you obtain the appropriate license, place the font files in an `assets/fonts/` folder and add corresponding `@font-face` rules.

Verve is listed as 100% free by its DaFont page; it can likewise be self-hosted later if desired.

## Netlify

This is a static site. Connect this GitHub repository to Netlify and deploy from the repository root. No build command is required.
