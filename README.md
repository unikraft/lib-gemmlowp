gemmlowp for Unikraft
=============================

This is the port of gemmlowp as a Unikraft external library. It
depends on the following libraries that need to be added to `Makefile`
in this order:

* CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`, `libcxx`
* `libc`, e.g. `newlib`

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
