# pypi-rpm

Placeholder package to make the RPM Python API available through PyPI.

Right now, this package just reserves the `rpm` name on PyPI to avoid the
potential for a name conflict with the `python2-rpm` and `python3-rpm`
Python bindings on RPM-based Linux distros.

Unlike libsolv and libdnf (which use CMake, and are hence amenable to PyPI
compatible build automation with scikit-build), rpm itself still uses autotools,
to create