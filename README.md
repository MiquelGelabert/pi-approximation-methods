# Pi Approximation Methods: A Comparative Study

This repository contains a detailed exploration of the mathematical and computational methods used to calculate the digits of $\pi$. From ancient geometric approaches to modern high-performance algorithms, this project analyzes how our ability to calculate this universal constant has evolved.

## Project Overview

The project is divided into two main notebooks that cover different aspects of the number $\pi$:

### 1. General Study of $\pi$ Digits
Based on the notebook `Cálculo de los decimales del número pi`, this section focuses on the theoretical and historical context:
* **Historical Review:** From the Egyptian approximations to the modern era.
* **Statistical Analysis:** A study of digit frequency distribution in the first 10,000 decimals to check for randomness.
* **Sequence Searcher:** A functional tool to find specific numeric patterns (like birthdays) within $\pi$.

### 2. Performance Comparison
Based on the notebook `Comparación de Métodos de Cálculo`, this section evaluates the efficiency of different algorithms:
* **Geometric Methods:** Archimedes' exhaustion method.
* **Probabilistic Methods:** Monte Carlo simulations and Buffon's Needle.
* **Infinite Series:** Leibniz, Wallis, and Euler series.
* **Advanced Algorithms:** Implementation of the **Chudnovsky algorithm**, used for world-record calculations due to its rapid convergence.

## Key Features
- **Precision:** Usage of `mpmath` and `decimal` libraries for high-precision floating-point arithmetic.
- **Visualization:** Comparative graphs showing convergence rates and execution times.
- **Analysis:** Real-world comparison between "slow" convergent series and optimized modern formulas.

## Getting Started

### Prerequisites
You will need Python 3.x and the following libraries:
```bash
pip install numpy matplotlib mpmath pandas
