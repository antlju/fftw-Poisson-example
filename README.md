# fftw-Poisson-example
An example of a solution to the 3D Poisson's equation using in-place, real-to-complex, discrete Fourier transform with the FFTW library (fftw.org).

When I started to look into how to use FFTW3 for an optimised Poisson solver (that is in-place and real-to-complex for most physical problems)
I had a hard time finding good examples. Most were either out-of-place or in-place but complex-to-complex. The point of this repository is to remedy this situation.
