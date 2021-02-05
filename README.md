# k-evolution basen on gevolution N-body code

## Compilation and usage

Before compilation, make sure that all required external libraries are
installed:

* LATfield2 [version 1.1](https://github.com/daverio/LATfield2.git)
* FFTW version 3
* GNU Scientific Library (GSL) including CBLAS
* HDF5

Make sure that the include paths are set properly, or add them to the
makefile. Also check the compiler settings in the makefile. The code is
compiled by typing:

    make

A typical command to run a simulation looks like this:

    mpirun -np 16 ./gevolution -n 4 -m 4 -s settings.ini

For further about gevolution information, please refer to the User Manual (manual.pdf)

## Credits

If you use gevolution for scientific work, we kindly ask you to cite
*Adamek J., Daverio D., Durrer R., and Kunz M., Nature Phys. 12, 346 (2016)*
in your publications.

For bug reports and other important feedback you can contact the authors,
julian.adamek@qmul.ac.uk (for queries related to gevolution)
developers@latfield.org (for queries related to the LATfield2 library)

