**Intro to Econometrics Notes**

**Table of Contents**

Ch 1. The Nature of Econometrics and Economic Data

------------- Regression Analysis with Cross-Sectional Data -------------

Ch 2. The Simple Regression Model

Ch 3. Multiple Regression Analysis: Estimation

Ch 4. Multiple Regression Analysis: Inference

Ch 5. Multiple Regression Analysis: OLS Asymptotics

Ch 6. Multiple Regression Analysis: Further Issues

Ch 7. Multiple Regression Analysis with Qualititive Information: Binary (or Dummy) Variables

Ch 8. Heteroskedasticity

Ch 9. More on Specification and Data Issues

------------- Regression with Time Series Data -------------

Ch 10. Basic Regression Analysis with Time Series Data

Ch 11. Further Issues in Using OLS with Time Series Data

Ch 12. Serial Correlation and Heteroskedasticity in Time Series Regressions

------------- Advanced Topics -------------

Ch 13. Pooling Cross Sections across Time: Simple Panel Data Methods

Ch 14. Advanced Panel Data Methods

Ch 15. Instrumental Variables Estimation and Two Stage Least Squares

Ch 16. Simultaneous Equations Models

Ch 17. Limited Dependent Varibale Models and Sample Selection Corrections

Ch 18. Advanced Time Series Topics

Ch 19. Carrying Out an Empirical Project

Appendix

**Cross-Sectional Data**: consist of a sample of individuals, households, firms, cities, states, countries, or a variety of other units, taken **at a given point in time**. (In a pure cross-sectional analysis, we would ignore any minor timing differences in collecting the data. ex. if a set of families was surveyed during different weeks of the same year, still view as cross-sectional data) 
1. can be assumed to be obtained by *random sampling*. (sometimes cannot be assumed random sampling becasue for example richer family less likely to reveal their wealth when we're trying to study family wealth; data are not independent, ex. study business activity across states, nearby states are influenced by each other; usually ignore this even though not right)
2. 

**Time Series Data**: consist of observations on a variable or several variables over time.
1. more difficult to analyze than cross-sectional data: rarely can be assumed to be independent across time.
2. data frequency at whcih the data are collected is important

**Pooled Cross Section**: cross-sectional data collected in different time perieods.

**Panel or Logitudinal Data**: consists of a time series for each cross-sectional member in the data set. (ex. we have wage, education, and employment history for a set of individuals followed over a ten-year period)
1. different from pooled cross section is that the *same* cross-sectional units(individuals, firms, or counties in the preceding examples) are followed over a given time period, whereas pooled cross sectional data can be different individuals (ex. the houses sold in 1993 are likely to be different in 1995; if there are any duplicates, the number is likely to be so small as to be unimportant)
2. having multiple observations on the same units allows us to control for certain unobserved characteristics of individuals, firms, and so on.
3. use of more than one observation can facilitate causal inference in situations where infeering causality would be very difficult if only a single cross section were available.
4. panel data allows us to study the importance of lags in behavior or the result of decision making.(it's significant bcz many economic policies can be expected to have an impact only after some time has passed)

------------- Regression Analysis with Cross-Sectional Data -------------
Chapter 2. The Simple Regression Model

**Population Regression Function (PRF)**: E(y|x) = bete0 + beta1 * x.
**Sample Regression Function (SRF)**: y_hat = bete0_hat + beta1_hat * x
**R-squared**: SSE/SST=1-SSR/SST, also is equivalent to the square of Correlation Coefficient between y_i and y_i_hat 




* **Principal Component Analysis (PCA)**

Given: feature vectors \bm{x_1, x_2, ...,x_n} 

1. Put feature data in nxd matrix A
2. Find the Top k eigenvectors/eigenvalues of 1/n A ^T A and put in matrix V=[v1|v2|...|vk]
3. Project each x_i onto the subspace eigenvectors
4. A is transformed to phi(A), n x k matrix

Goal: feature transformation \Phi : \mathbb{R}^d \rightarrow \mathbb{R}^k
* **Single Value Decomposition (SVD)**
