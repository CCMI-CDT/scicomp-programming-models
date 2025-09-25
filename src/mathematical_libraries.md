# Presentations on mathematical libraries

The morning session on Thursday focuses on mathematical libraries.
We will hear from a range of projects spanning core linear algebra
up to complex multiphysics environments.

Each presentation should be at most 15 minutes in length, talk about the software and perform a small demonstration of the software.
The order of talks will be randomly decided on the day.

- **[Blas](https://www.netlib.org/blas/)/[Lapack](https://www.netlib.org/lapack/lug)** are the core of almost any modern dense linear algebra package. **Blas** is a definition of basic matrix operations, implemented through fast low-level libraries (e.g. [Openblas](http://www.openmathlib.org/OpenBLAS/), [Blis](https://github.com/flame/blis), [Apple Accelerate](https://developer.apple.com/documentation/accelerate)). **Lapack** implements many standard matrix decompositions (e.g. LU, SVD, QR, etc.) based upon efficient Blas calls. **(Maciej, Bryce)**
- **[PETSc](https://petsc.org/release/)** is widely used package on HPC systems for linear and nonlinear solvers, supported by huge community of users and developers. **(Shany, Anees)**
- **[Suitesparse](https://people.engr.tamu.edu/davis/suitesparse.html)** is a widely used package specialising on sparse matrix solvers. The solvers built into Matlab, Julia, and many other mathematical environments are built around Suitesparse. **(Ross, Callum, Jose Miguel)**
- **[Gmsh](https://gmsh.info/)** is a powerful package for mesh discretisation and visualization. **(Lewis, Louis)**
- **[Firedrake](https://www.firedrakeproject.org/)** is a popular
  PDE solver package based on just-in-time code generation.
**(Anastasia, Kelan)**
- **[VTK](https://vtk.org/)** is an essential visualization library and also data-exchange format for grid based data in scientific computing. [Paraview](https://www.paraview.org/) and other visualization tools are built around VTK. **(Divij, Ammar)**
- **[FMM3D](https://fmm3d.readthedocs.io/en/latest/)** is an outstanding library for the fast solution of n-body interactions.
- **[Chebfun](https://www.chebfun.org/)** allows the solution of many ODEs and related problems to almost machine precision accuracy. **(Benjamin, Lucas)**
- **[scikit-learn](https://scikit-learn.org/stable/)** delivers a range of simple to use algorithms for machine learning. **(Skye, Oliver, Advaith)**
