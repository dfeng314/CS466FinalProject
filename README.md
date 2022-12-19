# CS466FinalProject
Low-degree Polynomial time heuristics for LPPF: Codebase and other documents
Daniel Feng

Here's some resources of code and data!

Python Code for solving any specific input with GreedySum and visualizing found solution:
https://colab.research.google.com/drive/1dGl0_EIyg7qBF-w9FgSt4QZgF5PvTcFy?usp=sharing

This will allow you to better understand GreedySum; the code given here allows for visualizing the solution, provides debugging tools, and gives notifications / status of the matrix input after each step of the decomposition.
Options are given and commented in the file! Other comments denote specific functions and work.


Python Code for creating a scatterplot on data, comparing a heuristic with the optimal (used to develop figures):
https://colab.research.google.com/drive/1hyrTVyYfXgAmisPtq32YOiFMIz9u8tBc?usp=sharing

This will allow you to analyze the heuristics built here on various datasets.
You can either create a new dataset, or load in a previous, already-built dataset solved to optimality (saving time and providing deterministic output).
Options are given and commented in the file! They include printing solutions, giving feedback on the generated matrices, and searching for a specific returned solution.
Other comments denote specific functions and work.


Python Code for generating a storing a large dataset of matrices and optimal solutions for further use:
https://colab.research.google.com/drive/1qJK2qvc5e58M5eN1PxGwL0nSbN0gN-oC?usp=sharing

This will allow you to create deterministic datasets, solve them to optimality, and save your answers to prevent doing the long NP-Hard computation again.
Options are given and commented in the file, such as denoting the progress of the file generation! Other comments denote specific functions and work.


Text file of synthetic 1000 (5 x 5) matrix dataset with optimal solutions:
https://drive.google.com/file/d/1INxLIuCEmCuQB2QwgpAWROxRK-Mbi0zo/view?usp=sharing

This is the true dataset used for developing the figures seen.


The name of the function that solves LPPF to optimality is bruteSolve.

The name of the GreedySum function (see write-up) in code is greedySum.

The name of the CoverSolve function (see write-up) in code is coverSolve.

The name of the CoverSolve function, altered to only resolve initial conflicts, (see write-up) in code is coverSolveInitial.

Thank you!
