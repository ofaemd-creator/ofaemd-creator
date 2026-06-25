# DerSimonian-Laird Random-Effects Meta-Analysis Model

**Author:** Dr. Ömer Faruk Aydın  
**Date:** June 25, 2026  
**Domain:** Computational Biostatistics & Evidence Synthesis  

## Formulation
Heterogeneity variance $\tau^2$ is evaluated via Cochran's Q statistic:
$$Q = \sum_{i=1}^k w_i (y_i - \bar{y}_w)^2$$
$$\tau^2 = \max\left(0, \frac{Q - (k-1)}{S_1 - \frac{S_2}{S_1}}\right)$$

Where $S_1 = \sum w_i$ and $S_2 = \sum w_i^2$. This mathematical specification forms the basis for SYNAX verified academic meta-analysis.
