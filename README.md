# Project

* Original Mirror
 * Forked from http://llvm.org/git/llvm
* Tools/Examples Location
 1. llvm/tools/xxx
 2. llvm/examples/xxx
 3. llvm/toosl/clang/tools/xxx
 4. llvm/toosl/clang/examples/xxx
* Recommendable examples to study firstly
 1. llvm/examples/Fibonacci
 2. llvm/examples/ModuleMaker
 3. llvm/examples/HowToUseJIT
* Advanced Learning
 1. I don't know now...

# Compile

```
$ mkdir build
$ cd build
$ cmake ..
$ make xxx # xxx is the target which you need to build
```

* Requirements
 1. cmake >= 3.4.3

# Clang

* clang located at llvm/tools/clang
* compile commands
```
$ cd build
$ make clang # need 10G memory(final link stage) and half an hour
```

# CMake

* tutorial from https://cmake.org/cmake-tutorial/
* manual from https://cmake.org/cmake/help/latest/
