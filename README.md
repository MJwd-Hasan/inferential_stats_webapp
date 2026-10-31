# Inferential Stats Webapp

A scroll-guided visual lesson on statistical inference, built from the supplied course PDF and extended into more advanced inferential topics.

## Design

- Single background color: `#FFF2B4`
- Restricted palette only:
  - `#15370D`
  - `#728E6D`
  - `#E5CD82`
  - `#FFF2B4`
- Large but controlled typography
- Strict two-zone layout: text and animation never share the same positioning plane
- Scroll-driven sticky chapters
- Graphics are clipped inside dedicated animation stages
- IntersectionObserver blur pop-ups for annotations
- Responsive mobile layout
- Medium paper/grain texture

## Learning sequence

### Foundation from the supplied PDF
1. Population vs. Sample
2. Parameters vs. Statistics
3. Point Estimation
4. Confidence Intervals
5. Hypothesis Testing
6. p-values

### Extended topics added beyond the supplied PDF
7. Sampling Distributions
8. Standard Error and Precision
9. Type I / Type II Errors and Statistical Power
10. Likelihood and Maximum Likelihood Estimation
11. Bayesian Updating and Frequentist-vs-Bayesian Interpretation

The website intentionally does not include an "Introduction to Statistical Inference" section.

## Fonts

The CSS includes named hooks for Amoria, Bremlin, and Verve, with safe fallbacks.

Restricted font files are not redistributed in this public repository. Licensed font files can be added later with `@font-face` rules.

## Netlify

This is a static site. Publish from the repository root. No build command is required.
