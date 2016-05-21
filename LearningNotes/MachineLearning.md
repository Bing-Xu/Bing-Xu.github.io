Machine Learning Notes

* **Principal Component Analysis (PCA)**

Given: feature vectors \bm{x_1, x_2, ...,x_n} <!--- \in \mathbb{R}^d
![A Matrix](http://bit.ly/22jA4OG) find the top k eigenvectors/eigenvalues of ![eig](http://bit.ly/1TzbAPa) Project each ![phi](http://bit.ly/22jAJzE) ---> 

1. Put feature data in nxd matrix A
2. Find the Top k eigenvectors/eigenvalues of 1/n A ^T A and put in matrix V=[v1|v2|...|vk]
3. Project each x_i onto the subspace eigenvectors
4. A is transformed to phi(A), n x k matrix

Goal: feature transformation \Phi : \mathbb{R}^d \rightarrow \mathbb{R}^k
* **Single Value Decomposition (SVD)**

