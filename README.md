# Project Euler in C++

This repository is for my C++ solutions to selected [Project Euler](https://projecteuler.net/) problems. I add a solution after reviewing the code and being able to explain the approach.

## Organization

Solutions go in `solutions/`, named `p001.cpp`, `p002.cpp`, and so on. Each file can be compiled and run on its own.

For example, from the repository root:

```sh
clang++ -std=c++20 -O2 solutions/p001.cpp -o p001
./p001
```

Replace `p001` with the number of the solution you want to run. On Linux, `g++` can be used in place of `clang++`.

## Publishing scope

I publish only solutions to problems 1–100, in line with Project Euler's sharing policy. Solutions to later problems stay private. I do not reproduce the full problem statements here.
