# Algorithms Course Exercises

Solved exercises prepared as teaching material for an undergraduate algorithms
course at Sapienza University of Rome, written in 2023. There are twelve exercise sets (`Esercitazione01` to `Esercitazione12`), 47 exercises
in total. Each exercise has the problem statement, the idea behind the
solution, and, for most of them, a Python implementation that is run on a
small example. Some exercises are proofs or counterexamples and have no code.

## Contents

| Folder | Topic | Exercises |
|--------|-------|-----------|
| [`Esercitazione01`](Esercitazione01/Esercitazione1.ipynb) | DFS, strongly connected components, orienting a graph into a DAG, principal nodes | 4 |
| [`Esercitazione02`](Esercitazione02/Esercitazione2.ipynb) | Graph complement connectivity, possible DFS orders, walking every edge once in each direction, bridges | 5 |
| [`Esercitazione03`](Esercitazione03/Esercitazione3.ipynb) | BFS and DFS, equidistant nodes, distance between node sets, trees as parent vectors | 6 |
| [`Esercitazione04`](Esercitazione04/Esercitazione4.ipynb) | Dijkstra with negative weights, shortest paths with fewest edges, counting shortest paths, edge removal after BFS | 4 |
| [`Esercitazione05`](Esercitazione05/Esercitazione5.ipynb) | Minimum spanning tree properties | 4 |
| [`Esercitazione06`](Esercitazione06/Esercitazione6.ipynb) | MST and cycles, shortest paths with 0/1 weights, semi-connected graphs, k-th element of two sorted arrays | 4 |
| [`Esercitazione07`](Esercitazione07/Esercitazione7.ipynb) | Divide and conquer: fixed point, zeros, integer square root, rotated array maximum, inversions, longest subarray of bounded width | 6 |
| [`Esercitazione08`](Esercitazione08/Esercitazione8.ipynb) | Dynamic programming: best buy/sell day, largest all-ones square submatrix | 2 |
| [`Esercitazione09`](Esercitazione09/Esercitazione9.ipynb) | Dynamic programming: shortest common supersequence, longest increasing path in a matrix, minimum-sum valid sequence | 3 |
| [`Esercitazione10`](Esercitazione10/Esercitazione10.ipynb) | Dynamic programming: minimum-value M-list, sequences and multisets with sum n | 2 |
| [`Esercitazione11`](Esercitazione11/Esercitazione11.ipynb) | Backtracking: strings with even runs of `a`, palindromes, sequences with gaps of at least 2, non-decreasing matrices | 4 |
| [`Esercitazione12`](Esercitazione12/Esercitazione12.ipynb) | Backtracking: strings with odd counts of `a` and `b`, sequences with bounded repetitions, binary matrices without adjacent ones | 3 |

Each folder holds one notebook and a PDF export of it (`*_Latex.pdf`).
Folders 01 to 08 also have presentation slides (`.pptx` and `*_Slide.pdf`),
and folders 01 to 05 contain PNG images.

The title cell of the notebooks in folders 11 and 12 reads "Esercitazione 10";
the folder and file names are the correct numbers.

## Opening the notebooks

The notebooks were written with Python 3.9 and open in Jupyter Notebook or
JupyterLab:

```bash
pip install jupyter networkx
jupyter lab
```

Notebooks 01 to 04 use [NetworkX](https://networkx.org/) for graphs. The other
notebooks use only the Python standard library. The PDF exports can be read
without Python.

## Language

The problem statements and explanations are in Italian. Code comments are
in Italian or English.

## Project page

<https://vincenzo.imperati.dev/projects/algorithms-course-exercises>

## Licence

MIT. See [LICENSE](LICENSE).
