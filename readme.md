# C++ Boilerplate
[![Build Status](https://travis-ci.org/dpiet/cpp-boilerplate.svg?branch=master)](https://travis-ci.org/dpiet/cpp-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/dpiet/cpp-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/dpiet/cpp-boilerplate?branch=master)
---

## Overview

A program used to find bugs using Valgrind and fixing those errors

## Standard install via command-line
```
git clone --recursive https://github.com/NJNischal/ValgrindRepo.git
cd <path to repository>
mkdir build
cd build
cmake ..
make
Run program: ./app/shell-app
```

## Running Valgrind

valgrind --leak-check=full ./app/shell-app

# install Kcachegrind

sudo apt-get install kcachegrind

# using the Memory profiler

valgrind --tool=callgrind ./app/shell-app
