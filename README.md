# Reversible-Quantum-Circuit-Synthesis

Course project (EE677: Foundation of VLSI CAD) : Python implementation for heuristic algotithm for synthesis of a reversible logic circuit from a given truth table minimizing quantum cost .

A truth table will be given as input and a quantum circuit will be generated . Transformations are applied such that minimum quantum cost is obtained by following a heuristic algorithm of minimization as given in this paper : https://ieeexplore.ieee.org/document/1715418 . A priority queue (max heap) is maintained and BFS traversal is applied so as to explore the nodes which minimize the cost .
