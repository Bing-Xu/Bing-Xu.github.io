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


* **Principal Component Analysis (PCA)**

Given: feature vectors \bm{x_1, x_2, ...,x_n} 

1. Put feature data in nxd matrix A
2. Find the Top k eigenvectors/eigenvalues of 1/n A ^T A and put in matrix V=[v1|v2|...|vk]
3. Project each x_i onto the subspace eigenvectors
4. A is transformed to phi(A), n x k matrix

Goal: feature transformation \Phi : \mathbb{R}^d \rightarrow \mathbb{R}^k
* **Single Value Decomposition (SVD)**