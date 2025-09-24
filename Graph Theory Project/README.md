# Graph Analysis Project

This project contains Python code for analyzing **undirected graphs** using **NetworkX** and **NumPy**. The main focus is on:

- Generating random graphs using the **Erdős–Rényi model**
- Computing **adjacency matrices** and the number of **paths of length two**
- Checking **graph connectivity** using iterative methods
- Visualizing graphs in Google Colab

---

## Files

- `YourNotebook.ipynb` — main Colab notebook containing all code, functions, and examples
- (Optional) Any additional scripts, data files, or notebooks can be included here in this folder

---

## Features

1. **Random Graph Generation**
   - Create graphs with `n` nodes and edge probability `p`.
   - Visualize graphs with circular layout.

2. **Paths of Length Two**
   - Compute the number of paths of length two between any pair of nodes.
   - Verify adjacency matrix squared (`A @ A`) corresponds to path counts.

3. **Connectivity Checks**
   - Determine if the graph is connected using an iterative matrix closure method.
   - Includes a helper function `has_all_ones` for reachability checks.

---

## Usage

1. Open the notebook in Google Colab.  
2. Run each cell sequentially to generate graphs, compute paths, and check connectivity.  
3. Modify parameters (`n` for nodes, `p` for edge probability) to experiment with different graphs.

---

## Requirements

- Python 3.x
- Packages:
  - `networkx`
  - `numpy`
  - `matplotlib` (for visualization)

Install missing packages using:

```bash
pip install networkx numpy matplotlib
