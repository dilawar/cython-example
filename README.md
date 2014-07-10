cython-example
==============

A small example of cython 

Two classes are written in C++: `class A` is in `A.h` and `class B` is in `B.h`.
Class B has a member of type A.

This folder contains `pxd` files for both class A and B, and a wrapper file
`ab.pyx`. Python file `setup.py` can be reused with minimal changes.

This is not intended for beginners.
