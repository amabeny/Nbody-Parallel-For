# Nbody-Parallel-For: Parallel N-Body Simulation

## Overview
This project simulates gravitational interactions between particles using the N-body problem. It uses OpenMP for parallelization.

## Files
- `nbody.cpp`: Main simulation code.
- `Makefile`: Compiles the code with `make`.
- `benchmark.txt`: Timing results on Centaurus cluster.
- `*.out`: Output files from simulations.

## How to Compile (on Centaurus)
bash
module load gcc
make
