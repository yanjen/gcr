This is a MATLAB code for the Generalized Conjugate Residual (GCR) method.

The GCR algorithm can be found in _Iterative methods for sparse linear systems_ by __Yousef Saad__.

The code is written by __Yen-Chen Chen__

The GCR method is an iterative solver for the linear system $Ax=b$.

The system matrix $A$ should be a square matrix (with the same number of row and column), and the righthand side $b$ is a set of column vectors. This function supports multiple righthand side.

The basic usage of the function is
```
[x, iter] = gcr(A, b, x0, max_iter)
```
