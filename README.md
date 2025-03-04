### Headers and Static Libs

[https://icl.utk.edu/lapack-for-windows/lapack/index.html#libraries_intel](https://icl.utk.edu/lapack-for-windows/lapack/index.html#libraries_intel)

### Some LAPACKE Tests to try

[https://portal.cs.umbc.edu/help/fortran/lapack-3.5.0/DOCS/lapacke.pdf](https://portal.cs.umbc.edu/help/fortran/lapack-3.5.0/DOCS/lapacke.pdf)

### Intel Compiler Flags

[https://learn.microsoft.com/en-us/cpp/build/reference/compiler-options-listed-alphabetically?view=msvc-170](https://portal.cs.umbc.edu/help/fortran/lapack-3.5.0/DOCS/lapacke.pdf)

#### Building 3.3.25:

```console
cl /DADD_ /DHAVE_LAPACK_CONFIG_H /DLAPACK_COMPLEX_STRUCTURE /MD main.c lapacke.lib lapack.lib blas.lib
main.exe
```
