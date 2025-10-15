# Trinh_Lab3
This is lab 3 for ENMT473

# Thanh’s A* Search Path Planning Algorithm

This lab implements the **A\*** search algorithm on a **2D occupancy grid map** using **NumPy** and **OpenCV**.  
It demonstrates how to find the shortest path from a start point to a goal point while avoiding obstacles.

---

## Overview

- The environment is represented as a **300x300 grid**.  
- Obstacles are drawn using OpenCV (`rectangle`, `circle`, and `line`).  
- Obstacles are **inflated** to ensure the robot doesn’t collide with their boundaries.  
- Pathfinding is done using **A\*** search with **4-connected neighbors** and **Manhattan distance** as the heuristic.

I chose:
- **Step size:** `1` (for precise path resolution)
- **Connectivity:** `4-connected` (only up, down, left, right)
- **Heuristic:** Manhattan distance

---

## Requirements:
pip install numpy opencv-python matplotlib

## How to run script:
Open the notebook in Jupyter Lab or Jupyter Notebook:

jupyter notebook

Open Trinh_Lab3.ipynb

Run all cells in order (Kernel → Restart & Run All).

After the algorithm completes, the notebook will:

Print statistics (free cells, adjacency size, etc.)

Display visualizations of the map and the final path.


