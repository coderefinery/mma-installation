

# Installation instructions for Mixed Martial Arts workshop: Interfacing Fortran, C, C++, and Python for Great Good!


## Required compilers

- C++ compiler which is C++11 compliant
- C compiler
- Fortran compiler


## Required configure and build tools

- [CMake](https://cmake.org/download/)
- [Make](https://www.gnu.org/software/make/)


## Required Python packages

We recommend to install these either through
[Anaconda](https://www.continuum.io/downloads),
[Miniconda](https://conda.io/miniconda.html), or
[Virtual Environments](http://python-guide.readthedocs.io/en/latest/dev/virtualenvs/):

- [pytest](https://docs.pytest.org)
- [cffi](https://cffi.readthedocs.io)
- [scipy](https://www.scipy.org)
- [swig](http://www.swig.org)
- [cython](http://cython.readthedocs.io)
- [boost](http://www.boost.org/doc/libs/1_63_0/libs/python/doc/html/index.html)
- [pybind11](https://pybind11.readthedocs.io)


Example installation
(using [Virtual Environments](http://python-guide.readthedocs.io/en/latest/dev/virtualenvs/)):

```shell
$ mkdir mma-workshop
$ cd mma-workshop
$ virtualenv venv
$ source venv/bin/activate
$ pip install pytest cffi scipy swig cython boost pybind11
```
