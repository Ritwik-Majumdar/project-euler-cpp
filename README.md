# Project Euler in C++

This repository is for my C++ solutions and short explanations for selected [Project Euler](https://projecteuler.net/) problems. I add a solution after reviewing the code and being able to explain the approach.

## Organization

Solutions go in `solutions/`, named `problem001.cpp`, `problem002.cpp`, and so on. Each file can be compiled and run on its own. I include comments or notes describing the method, rather than only a final answer.

For example, from the repository root:

```sh
clang++ -std=c++20 -O2 solutions/problem001.cpp -o problem001
./problem001
```

Replace `problem001` with the number of the solution you want to run. On Linux, `g++` can be used in place of `clang++`.

## Publishing scope

Only problems 1–100 are candidates for this public repository. Solutions to later problems stay private. I do not reproduce the full problem statements here.
