# Project README

## Overview
This project is a simple 3D engine implemented in C. It uses ASCII characters to render basic wireframes of 3D objects on the terminal.

## Features
- Basic rendering of 3D wireframe shapes (cube, pyramid).
- User input for rotating the shape.
- Terminal-based user interface for displaying the rendered 3D scene.

## Project Structure
```
Cmd_3D_Engine_1/
├── build/              # .exe files produced by Main.c
├── src/                # src code
│   ├── Main.c          # Entry point
│   └── Console.h       # Header file for console functions
├── Makefile.linux      # Linux Build configuration
├── Makefile.windows    # Windows Build configuration
├── Makefile.wine       # Wine Build configuration
└── README.md           # This file
```

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build the project, navigate to the root directory of the project and run:
```bash
make -f Makefile.linux all  # For Linux
```
or
```bash
make -f Makefile.windows all  # For Windows
```

After building, you can run the executable with:
```bash
make -f Makefile.linux exe  # For Linux
```
or
```bash
make -f Makefile.windows exe  # For Windows
```

For clean rebuild, use:
```bash
make -f Makefile.linux clean  # For Linux
```
or
```bash
make -f Makefile.windows clean  # For Windows
```