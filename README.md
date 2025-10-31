# Geometric Algorithms: Convex Hull Project

This project provides a comprehensive implementation, visualization, and performance analysis of classical algorithms for computing the convex hull of a set of points in a 2D plane. It offers a practical exploration of fundamental concepts in computational geometry.
### Implemented Algorithms

This repository includes Python implementations of the following convex hull algorithms:
  * Graham Scan
  * Jarvis March (Gift Wrapping)
  * Monotone Chain (Upper and Lower Hull)
  * Incremental Algorithm
  * Quickhull
  * Divide and Conquer
  * Chan's Algorithm

### Key Features

  * **Step-by-Step Visualization:** Each algorithm have special visual versions of each algorithm to show, step-by-step, how the convex hull is built.
  * **Performance Analysis:** A analysis of the implemented algorithms is conducted using various test datasets. The results, including execution times across different point distributions, are generated and saved in the `results/` directory.


## Project Structure

```
geometric-algorithms-convex-hull/
├── algorithms/                 # Source code for all implemented convex hull algorithms.
├── results/                    # Output directory for generated CSV files with performance data.
├── main.ipynb                  # The main Jupyter Notebook for running experiments, visualizations, and analysis.
├── convex-hull-algorithms-analysis-and-results.pdf # Detailed project report and documentation.
└── README.md                   # This file.
```

-----

## Getting Started

### Prerequisites

  * `pandas`
  * `numpy`
  * `matplotlib`

### Usage

1.  Clone the repository:

    ```bash
    git clone https://github.com/DEFALT314/geometric-algorithms-convex-hull.git
    cd geometric-algorithms-convex-hull
    ```

2.  Run Jupyter Notebook:

    ```bash
    jupyter notebook main.ipynb
    ```

## Documentation
A detailed technical report, including theoretical descriptions of the algorithms, analysis of the results, and conclusions, is available in the project documentation.

➡️ [View Full Project Documentation (PDF)](./convex-hull-algorithms-analysis-and-results.pdf)
