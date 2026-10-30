---
title: willwiz
---

# :sparkles: Will Zhang's Personal Repositories

Github [github.com/willwiz](https://github.com/willwiz).

## Current Public Projects

### Pytools

A lightweight Python package for some commonly used tools:

> **source**: [github.com/willwiz/pytools](https://github.com/willwiz/pytools)

> **documentation**: [willwiz.github.io/pytools](https://willwiz.github.io/pytools)

- Typing: stub only module to provide shortened type hints for numpy arrays and DTypes.
- Logging: a simple logging utility to structural logging with no setup required.
- Results: a **rust** style `Result` sum type for error handling using structural pattern matching.

### CheartPy

A Companion python package for working with Finite Element Analysis (FEA) using Cheart (DOI: https://doi.org/10.1137/15M1014097)

> **source**: [github.com/willwiz/cheartpy](https://github.com/willwiz/cheartpy)

> **documentation**: [willwiz.github.io/cheartpy](https://willwiz.github.io/cheartpy)

- Paraview: A command line utility to convert Cheart output files to VTU format for visualization in Paraview.
- IO: A library for reading/writing Cheart input and output files, including mesh, boundary conditions, and variables.
- Mesh: A library for generating and manipulating Cheart meshes, including reading/writing Cheart mesh files, and converting to/from other mesh formats.

=== "C"

    ```c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ```c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
