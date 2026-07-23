# QMH-TSP

A Quantum-Inspired Multi-Phase Hybrid (QMH) framework for solving the Traveling Salesman Problem (TSP) on classical hardware.

## Overview

This project implements a Quantum-Inspired Multi-Phase Hybrid (QMH) optimization framework that combines:

- Quantum Swarm Core (QSC)
- Quantum Evolutionary Core (QEC)
- Differential Annealing Core (DAC)

The framework is designed to efficiently solve Traveling Salesman Problem (TSP) instances and is evaluated using TSPLIB benchmark datasets.

## Features

- Quantum-inspired optimization on classical hardware
- Multi-phase hybrid optimization
- TSPLIB dataset support
- Route visualization
- Performance comparison with a classical 2-opt heuristic

## Configuration

Several parameters can be adjusted to influence the performance of the algorithm. These include:

- Population size
- Number of iterations
- Rotation angle and update parameters
- Annealing temperature and cooling schedule
- Other algorithm-specific hyperparameters

The number of independent runs can also be changed. Increasing the number of runs may improve the chance of finding a better solution but will increase the total execution time.

Users are encouraged to experiment with these parameters to balance solution quality and computational cost for different TSPLIB instances.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Qiskit
- Jupyter Notebook

## Usage

1. Open the Jupyter notebook.
2. Place the desired TSPLIB `.tsp` file in the project directory.
3. Update the filename in the notebook if necessary.
4. Run all cells to execute the QMH framework and view the results.

## Repository Contents

- `QMH.ipynb` – Main implementation of the QMH framework.
- `README.md` – Project description.

## License

This project is provided for educational and research purposes.
