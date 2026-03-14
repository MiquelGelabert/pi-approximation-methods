# Pi Approximation Methods: A Comparative Study

> **Note:** The notebooks in this repository are written in **Spanish**.

This repository contains a detailed exploration of the mathematical and computational methods used to calculate the digits of $\pi$. From ancient geometric approaches to modern high-performance algorithms, this project analyzes how our ability to calculate this universal constant has evolved.

## About this Project

This is my **very first programming project**. I am sharing it to document my starting point and my passion for problem-solving through code. While the implementation is straightforward, it represents my enthusiasm for learning and my commitment to continuous improvement. I look forward to looking back at this repository in the future to see how much I've grown as a developer.

## Project Overview

The project is divided into two main notebooks that cover different aspects of the number $\pi$:

### 1. General Study of $\pi$ Digits (`Cálculo de los decimales del número pi`)
This section focuses on the theoretical and historical context:
* **Historical Review:** From the Egyptian approximations to the modern era.
* **Statistical Analysis:** A study of digit frequency distribution in the first 10,000 decimals to check for randomness.
* **Sequence Searcher:** A functional tool to find specific numeric patterns (like birthdays) within $\pi$.

### 2. Performance Comparison (`Comparación de Métodos de Cálculo`)
This section evaluates the efficiency of different algorithms:
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
You will need Python 3.x and the following libraries installed:
```bash
pip install numpy matplotlib mpmath pandas
