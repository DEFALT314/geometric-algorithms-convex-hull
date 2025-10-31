# Geometric Algorithms: Convex Hull Project

This project provides a comprehensive implementation, visualization, and performance analysis of classical algorithms for computing the convex hull of a set of points in a 2D plane. This project provides a practical exploration of fundamental concepts in computational geometry.
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

- **Step-by-Step Visualization:** Each algorithm includes a visual version showing, step by step, how the convex hull is built.
- **Performance Analysis:** The implemented algorithms are analyzed using various test datasets. Results, including execution times across different point distributions, are saved in the `results/` directory.



## Project Structure

```
geometric-algorithms-convex-hull/
├── algorithms/                 # Source code for all implemented convex hull algorithms.
├── results/                    # Output directory for generated CSV files with performance data.
├── main.ipynb                  # The main Jupyter Notebook for running experiments, visualizations, and analysis.
├── convex-hull-algorithms-analysis-and-results.pdf # Detailed project report and documentation.
└── README.md                   # This file.
```



### Prerequisites

This project depends on the [`bit-alg`](https://github.com/aghbit/Algorytmy-Geometryczne) Conda environment, which contains all necessary dependencies. To set it up:

```bash
# Clone the bit-alg repository
git clone https://github.com/aghbit/Algorytmy-Geometryczne.git
cd Algorytmy-Geometryczne

# Create and activate conda environment
conda create --name bit-alg python=3.9
conda activate bit-alg

# Install the package locally
python3 setup.py sdist
python3 -m pip install -e .
```

### Usage

1.  Clone the repository:

    ```bash
    git clone https://github.com/DEFALT314/geometric-algorithms-convex-hull.git
    cd geometric-algorithms-convex-hull
    ```
2. Make sure the bit-alg environment is active:
     ```bash
    conda activate bit-alg
     ```
3.  Run Jupyter Notebook:

    ```bash
    jupyter notebook main.ipynb
    ```

## Documentation
A detailed technical report, including theoretical descriptions of the algorithms, analysis of the results, and conclusions, is available in the project documentation.

➡️ [View Full Project Documentation (PDF)](./convex-hull-algorithms-analysis-and-results.pdf)
