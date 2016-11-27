## Synopsis

Libigl's bbw method requires some Eigen3 LGPL'd code (SimplicialCholesky). This files provide a workaround to use MPL2 Cholesky factorization in Eigen3.

## Installation

Replace the files in your libigl directory.
Disable the LGPL'd code (SparseCholesky and IterativeLinearSolvers) in the Eiglen/Sparse module file.
Make sure your code compiles using the EIGEN_MPL2_ONLY preprocessor symbol defined.

## License

Mozilla Public License v. 2.0