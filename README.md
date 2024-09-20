# umap
Uniform Manifold Approximation &amp; Projection is a nonlinear reduction method used to represent higher dimensional data in lower dimensions. Features of the higher dimensional dataset are retained as much as possible. A lower dimensional model is produced and refined using stochastic gradient descent, Adam or other optimization algorithms. 

## Procedure 
An input dataset of dimensionality `m` is inputted. <br/> A neighborhood map is created for the k-nearest neighbors an a distance and probability matrix are computed for the higher dimensionality dataset. <br/> The same is done for the lower dimensional model. <br/> A loss function is computed and optimized.

