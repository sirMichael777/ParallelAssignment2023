
---

# ParallelAssignment2023

## Overview
This repository hosts the Java implementation of a parallelized Monte Carlo method for function optimization. The goal is to find the global minimum of a 2D mathematical function across a specified range using a shared memory parallel programming approach in Java. This project is part of the CSC2002S course assignment, designed to provide hands-on experience with parallel algorithms and their efficiency against serial implementations.

## Installation

### Prerequisites
- Java JDK 11 or higher
- Make sure Java PATH is set correctly

### Cloning the Repository
```bash
git clone https://github.com/sirMichael777/ParallelAssignment2023.git
cd ParallelAssignment2023
```

## Usage
To run the parallel implementation, navigate to the project directory and use the following command:

```bash
java -cp . MonteCarloMinimizationParallel <rows> <columns> <xmin> <xmax> <ymin> <ymax> <search density>
```
Replace `<rows>`, `<columns>`, `<xmin>`, `<xmax>`, `<ymin>`, `<ymax>`, `<search density>` with your specific parameters.

## Features
- Parallel implementation using Java's Fork/Join framework.
- Ability to handle large data grids with variable densities of search points.
- Benchmarking tools for comparing performance against serial code.

## Contributing
To contribute to this project:
1. Fork the repo.
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin my-new-feature`).
5. Create a new Pull Request.

## Contact
If you have any questions or feedback, feel free to open an issue in this repository or contact the maintainer directly at michaelcmcmaseko@gmail.com.

## Assignment Submission Requirements
- Ensure the repository contains:
  - Java files: `TerrainArea.java`, `SearchParallel.java`, `MonteCarloMinimizationParallel.java`.
  - A Makefile for compilation.
  - This README file.
  - A GIT usage log (`git log --all > gitlog.txt`).

Make sure to review your files and upload them correctly as per the assignment's submission guidelines.

---

