# pomdp-py

Python POMDP library.

Cython algorithm implementation.


## Development

For development, please run
```
pip install -e .
```
to build and install this package. This will build `.so` files and copy them to the python source directory.
When you make changes to `.pyx` or `.pyd` files, run
```
make build
```
to rebuild those `.so` libraries, so that the python imports can get those changes you made.
