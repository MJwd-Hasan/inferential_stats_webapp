# Inferential Stats Webapp

A long-form, scroll-guided visual course on statistical inference. It begins with the concepts in the supplied PDF and then extends into intermediate and advanced inference.

## Visual system

- Single background: `#FFF2B4`
- Restricted palette only:
  - `#15370D`
  - `#728E6D`
  - `#E5CD82`
  - `#FFF2B4`
- Two-zone layout: text and animation are structurally separated
- Graphics remain clipped inside dedicated visual stages
- Scroll-driven sticky chapters
- IntersectionObserver blur annotations
- Responsive mobile layout
- Paper/grain texture

## Course map

### PDF foundation
1. Population vs. Sample
2. Parameters vs. Statistics
3. Sampling Distributions
4. Point Estimation and Standard Error
5. Confidence Intervals
6. Hypothesis Testing
7. p-values
8. Type I Error, Type II Error, and Power
9. Likelihood and Maximum Likelihood
10. Bayesian Updating

### Extended inference
11. Law of Large Numbers and Central Limit Theorem
12. Bias, Variance, MSE, Consistency, and Efficiency
13. Sufficiency
14. t, Chi-square, and F Distributions
15. Pivotal Quantities
16. Likelihood Ratio, Wald, and Score Tests
17. Fisher Information and the Cramér–Rao Bound
18. Bootstrap Inference
19. Permutation and Randomization Tests
20. Rank-based and Nonparametric Inference
21. Multiple Comparisons, FWER, and FDR
22. Effect Sizes and Practical Significance
23. ANOVA and Variance Decomposition
24. Regression Inference
25. Categorical-data Inference
26. Model Assumptions and Diagnostics
27. Robust and Sandwich Standard Errors
28. Bayesian Credible Intervals and Posterior Predictive Inference
29. Bayes Factors and Bayesian Model Comparison
30. Statistical Decision Theory
31. Sequential Inference and Optional Stopping
32. Statistical vs. Causal Inference
33. Missing Data and Inferential Validity
34. Meta-analysis

The website intentionally does **not** include a generic "Introduction to Statistical Inference" chapter.

## Source boundary

Chapters covering populations/samples, parameters/statistics, point estimation, confidence intervals, hypothesis testing, and p-values are grounded in the supplied PDF. The broader advanced curriculum is an extension beyond that source.

## Fonts

The CSS retains named hooks for Amoria, Bremlin, and Verve with safe fallbacks. Restricted font files are not redistributed in this public repository.

## Netlify

Static site. Publish from the repository root. No build command is required.
