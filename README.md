## Hello, I am Eitan Berenfeld

I am an aspiring Data Scientist/Tech Economist passionate about the marketing space. I am interested in exploring causal inference methodologies and their application to incrementality testing. I hope to continue studying quasi-experimental methods and their application in marketing settings.

Currently: B.S. Artificial Intelligence and Economics (May 2027) and M.S. Economics, Data Science for Economics concentration (Dec 2027), Northeastern University. Data Analyst co-op on Consumer Insights at Wayfair.

### Projects

**[e_commerce_testing](https://github.com/eitan-berenfeld/e_commerce_testing)**: What multiple-comparisons correction actually costs you. Welch's t-test with Benjamini-Hochberg and Bonferroni across 396 real ASOS A/B tests, then a Monte Carlo of how false-discovery risk compounds when you test every week rather than once. The point of it is that per-batch FDR control and the cumulative risk of *any* false win are different quantities, and only one of them stays flat.

**[maintainer-burnout-bayesian](https://github.com/eitan-berenfeld/maintainer-burnout-bayesian)**: A Negative Binomial changepoint model with a hand-written Metropolis-within-Gibbs sampler, estimating *when* an open-source maintainer's activity shifted and how confident that timing is. The output is a posterior over the changepoint week, not a point estimate. The README also documents an extraction bug in the underlying data and shows what the result looks like once the affected series are excluded.

**[causal_retail_analysis](https://github.com/eitan-berenfeld/causal_retail_analysis)**: A geo-aware pipeline for retail interventions where nearby stores contaminate each other's comparisons: DBSCAN spatial clustering, spillover-buffer selection, propensity matching, and IPW-weighted difference-in-differences with clustered standard errors. Exercised against a synthetic treatment assignment, so it demonstrates the machinery rather than measuring a real intervention — the README is explicit about that and about where the limits are.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eitanberenfeld/)
