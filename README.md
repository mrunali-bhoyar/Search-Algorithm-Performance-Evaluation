# Search Algorithm Performance Evaluation

## Overview
This project implements and evaluates different Artificial Intelligence search algorithms for solving a city route-finding problem and the N-Queens Constraint Satisfaction Problem.

## Algorithms Used
- Breadth First Search (BFS) – Uninformed Search
- Depth First Search (DFS) – Uninformed Search
- Greedy Best-First Search – Informed Search
- A* Search – Informed Search
- Hill Climbing – Local Search
- Backtracking – Constraint Satisfaction Problem

## Problem
Find a route from **Pune to Mumbai** using different search algorithms and compare their performance.

The project measures:
- Path cost
- Nodes explored
- Execution time
- Solution quality

## Technologies
- Python 3
- `heapq`
- `collections`
- `time`

## Results
The optimal route is:

**Pune → Ahmednagar → Mumbai = 280 km**

Greedy Best-First Search selects:

**Pune → Satara → Mumbai = 300 km**

This demonstrates that A* can provide a better route by considering both actual and estimated cost.

## CSP
The project also solves the **4-Queens problem** using Backtracking.

## Author
Mrunali Bhoyar
