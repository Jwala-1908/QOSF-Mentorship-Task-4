# QOSF Mentorship Program- Screening Task 4
This repository contains my solution to Screening Task 4 for the 3rd cohort of [Quantum Open Source Foundation's Mentorship Program](https://qosf.org/qc_mentorship/), submitted February 2021.  

There are two notebooks in this repository.  

* **Task_4.ipynb**: Main solution notebook. This notebook detailing the algorithm and _Cirq_ code implementation for the task.  

* **Task_4_(additional).ipynb**: Contains only code implementation, in _Qiskit_.

If you face trouble opening the notebooks, try refreshing the page. If that doesn't work, please refer to the following links-
* [Task_4.ipynb](https://nbviewer.jupyter.org/github/Jwala-1908/QOSF-Mentorship-Task-4/blob/main/Task_4.ipynb)
* [Task_4_(additional).ipynb](https://nbviewer.jupyter.org/github/Jwala-1908/QOSF-Mentorship-Task-4/blob/main/Task_4_(additional).ipynb)

or the PDFs (of the same name) contained in the repository.

---

This task was my first experience with the Quantum Approximate Optimization Algorithm (QAOA), as well as Cirq. I found many helpful online tutorials implementing the MaxCut problem, and sources describing the underlying concepts, some of which are linked in the references below.  

The task statement was as follows:  
#### Task 4
_[The MaxCut Problem](https://en.wikipedia.org/wiki/Maximum_cut) is a well-known optimization problem in which the nodes of a given undirected graph have ot be divided in two sets (often referred as the set of "white" and "black" nodes) such that the number of edges connecting a white node with a black node are maximized. The MaxCut Problem is a problem on which the QAOA algorithm has proved to be useful (for an explanation of the QAOA algorithm you can read [this blogpost](https://www.mustythoughts.com/quantum-approximate-optimization-algorithm-explained).  
At [this link](https://lucaman99.github.io/new_blog/2020/mar16.html) you can find an explicit implementation of the QAOA algorithm to solve the MaxCut Problem for the simpler case of an unweighted graph. We ask you to generalize the above code to include also the solution for the case of weighted graphs. You can use the same code or you can also do an alternative implementation using, for example, qiskit. The important point is that you do not make use of any built-in functionalities._

---

It is always a rewarding experience embarking on something new. As the quote goes:  

_I find that a great part of the information I have was acquired by looking up something and finding something else along the way._  
-Franklin P. Adams


## References
* Fun With Graphs and QAOA (https://lucaman99.github.io/new_blog/2020/mar16.html)
* Quantum Approximate Optimization Algorithm Explained (https://www.mustythoughts.com/quantum-approximate-optimization-algorithm-explained)
* QAOA: Max-Cut (https://quantumai.google/cirq/tutorials/qaoa)
* Quantum approximate optimization algorithm for the Ising Model (https://quantumai.google/cirq/tutorials/educators/qaoa_ising)
* Matrix Exponentials - Qiskit Textbook (https://qiskit.org/textbook/ch-appendix/linear_algebra.html#Matrix-Exponentials)
* https://quantumcomputing.stackexchange.com/questions/2486/how-to-implement-a-matrix-exponential-in-a-quantum-circuit
* Solving combinatorial optimization problems using QAOA - Qiskit Textbook (https://qiskit.org/textbook/ch-appendix/linear_algebra.html#Matrix-Exponentials)
* QAOA for MaxCut(https://pennylane.ai/qml/demos/tutorial_qaoa_maxcut.html)
* _Quantum Computing for Computer Scientists_ by Noson S Yanofsky and Mirco A. Mannucci
