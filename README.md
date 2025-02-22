![Screenshot](https://github.com/morganbengtsson/mos-skeleton/blob/master/screenshot.png)

# MOS Skeleton
[![Build Status](https://travis-ci.org/morganbengtsson/mos-skeleton.svg?branch=master)](https://travis-ci.org/morganbengtsson/mos-skeleton)

Example project for the [MOS library](https://github.com/morganbengtsson/mos). Provides a minimal setup, for getting a
window with some graphics and sound up and running.

# Source code

To get the full source code, including submodules:

```git
git clone --recurse-submodules https://github.com/morganbengtsson/mos-skeleton
```
# Building

To build and run the project on Linux. Make a build directory, run cmake and then make:

```bash
mkdir build
cd build
cmake ..
make
./mos-skeleton
```

On Windows, create a build directory and run CMake from there:

```
cmake ..
```

An appropriate Visual studio solution should then be generated.