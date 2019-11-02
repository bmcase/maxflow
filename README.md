# maxflow
Implementation of a preflow-push (i.e. push-relabel) algorithm for finding the max flow (= min cut) of a directed graph with no loops or multiedges.  Implemented in Python 3 (uploaded as Jupyter notebook); inputs were generated using NetGen  (https://pubsonline.informs.org/doi/abs/10.1287/mnsc.20.5.814) and several sample graphs are included.

Code Sources: The max heap code is from: https://github.com/DanielStutzbach/heapdict/blob/master/heapdict.py. The graph data structure code accompanies the Goodrich, Tamassia, Goldwasser textbook. We have made a couple modifications including adding the set_element() methods to the Vertex and Edge classes.

Completed as an assignment in MATH 8160 Network Algorithms and Data Structures, Spring 2019 with Prof. Matthew Saltzman.
