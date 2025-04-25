Github complementing the bachelor thesis "Gauss and Clenshaw-Curtis quadrature" by Michal Döme.
The purpose of this library is to provide the scripts used for the numerical experiments presented in the thesis.
For using these codes, you need to have Chebfun installed.

Description of the functions:
setup.m adds chebfun path to Matlab.
vahyexplicit.m computes explicit weights of Clenshaw-Curtis quadrature
imtqlx.m diagonalises a symmetric tridiagonal matrix (from https://people.sc.fsu.edu/~jburkardt/m_src/quadrature_golub_welsch/quadrature_golub_welsch.html)
legendre_ek_compute.m calculates weights and nodes for Gauss quadrature

GaussSrovnani.m compares two implementations of Gauss quadrature - Golub-Welsch and Hale-Townsend algorithms.
ImplVsExpl.m compares two implementations of Clenshaw-Curtis quadrature - Explicit computation of weights and FFT algorithm.
GaussVsClenshaw.m compares Gauss quadrature (implemented by Hale-Townsend algorithm) and Clenshaw-Curtis quadrature (implementation by Chebfun)
These three codes provide time comparison and create a plot.

To compare the quadrature using the last 3 files, just change the function in the beginning of the respective code. 