Geogram Tools
=============

[![Build Status](https://travis-ci.com/jdumas/geotools.svg?branch=master)](https://travis-ci.com/jdumas/geotools) [![Build status](https://ci.appveyor.com/api/projects/status/no8bbegc7sf2bpwf?svg=true)](https://ci.appveyor.com/project/jdumas/geotools)


A collection of small utilities made using the [geogram](http://alice.loria.fr/software/geogram/doc/html/index.html) library (mostly).

Compilation
-----------

Compile with CMake:

```
mkdir build
cd build
cmake ..
make -j4
```


[Normalize Mesh](normalize_mesh)
---------------------------

Rescale a mesh to fit in a unit box, and set its min corner to 0.

[Poisson Disk Sampling](poisson_disk)
------------------------------------

Simple Poisson disk sampling in a 3D grid based on Bridson's 2007 [paper](http://dx.doi.org/10.1145/1278780.1278807).

[VoxMesh](voxmesh)
------------------

A simple voxelization program, which takes a surface mesh as input.
