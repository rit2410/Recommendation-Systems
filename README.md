# Recommendation-Systems

## SGD (Stochastic Gradient Descent):

1. SGD is an optimization algorithm commonly used in machine learning to train models.
2. It aims to find the optimal set of parameters (weights and biases) that minimize a given loss function.
3. Unlike traditional gradient descent, which computes the gradient using the entire dataset, SGD updates the parameters using a randomly selected subset (batch) of the data in each iteration.
4. This randomness introduces noise but allows for faster and more frequent updates, making SGD well-suited for large datasets. Variants of SGD, such as **Mini-Batch Gradient Descent, Adam, and RMSprop, improve upon its performance by adapting the learning rate and incorporating momentum.
**
## SVD (Singular Value Decomposition):

1. SVD is a matrix factorization technique used in linear algebra and data analysis. Given a matrix, SVD decomposes it into three matrices: * U
* Σ (Sigma), and
* V^T (the transpose of V), where U and V contain orthogonal vectors, and Σ contains singular values.
3. SVD is widely used in various applications, such as dimensionality reduction, noise reduction, and collaborative filtering in recommendation systems. In the context of collaborative filtering, SVD can be applied to factorize a user-item interaction matrix, allowing the discovery of latent features and making personalized recommendations.

