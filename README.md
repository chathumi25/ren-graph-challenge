<<<<<<< HEAD
# Ren Graph Processing Challenge
This repository contains my solution to the Ren Systems Engineering coding challenge.  
The task involves reading a directed graph in CSV format, computing several graph metrics,  
and running PageRank over 20 iterations with a damping factor of 0.85.

## Features Implemented
The program outputs the following metrics for any given graph:
- **is_dag**  whether the graph is a Directed Acyclic Graph  
- **max_in_degree**  maximum in-degree among all nodes  
- **max_out_degree**  maximum out-degree among all nodes  
- **pr_max** maximum PageRank value after 20 iterations  
- **pr_min** minimum PageRank value after 20 iterations  

## Project Structure
ren-graph-challenge/
│
├── graph_solution           
├── graph_solution.py        
├── README.md
├── requirements.txt          
│
└── test_cases/
    ├── graph1.csv
    ├── graph1_output.txt
    ├── graph2.csv
    ├── graph2_output.txt
    ├── graph3.csv
    ├── graph3_output.txt

## How to Run the Program
### 1. Make the wrapper executable (Linux/macOS)
chmod +x graph_solution

## 2. Run the program
./graph_solution test_cases/graph1.csv

# Example output:
is_dag: true
max_in_degree: 1
max_out_degree: 1
pr_max: 0.000008
pr_min: 0.000001

# Algorithms Implemented
Cycle detection using DFS → determines is_dag
In-degree and out-degree computation
Custom PageRank implementation
20 iterations
Damping factor 0.85
Dangling-node fix: distribute rank uniformly
Uniform initialization
Row-stochastic transition handling


# Dependencies
This project uses only Python standard libraries:
 csv
 sys
Since there are no external dependencies, requirements.txt is intentionally empty.






=======
# ren-graph-challenge
Solution for Ren Systems Engineering Graph Processing Challenge.
>>>>>>> 4cbcbe50692d2ebddd9fea0ba30bc9e9a848c8ff
