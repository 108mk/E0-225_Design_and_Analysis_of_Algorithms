# E0-225_Design_and_Analysis_of_Algorithms
This is my personal repository for E0225: Design and Analysis of Algorithms. It is a foundational course at the Computer Science department, IISc Bengaluru. It aims to develop algorithmic thinking in students. You can find my codes and assignment solution along with class notes. Feel free to fork and use. Don't hesitate to report mistakes if you find them in the documents.

:accessibility: Highlights of important algorithmic paradigms and their real-world applications:
## Part-I: Greedy, Divide & Conquer and Dynamic Programming
### Paradigm-I: Greedy Algorithm

$\bullet$ Stable Matching Problem: Galey-Shapley Algorithms and its connection to Boston-Pool algorithm
 
$\bullet$ Interval Scheduling: Where Greedy approach fits like a champ(!)

$\bullet$ Minimum Spanning Tree (Weighted Graph): $\bullet$ Boruvka algorithm $\bullet$ Prin-Jarnik algorithm and $\bullet$ Krushkal Algorithms 

⭐ (Graphic) Metroid Scheme: Power and limitations of Greedy approach

### Paradigm-II: Divide and Conquer

🎯 $\bullet$ Breaking $\mathcal{O}(n^2)$ barrier for Multiplication: Karastuba $\mathcal{O}(n\cdot log(n))$ algorithm
 
🎯 $\bullet$ Breaking $\mathcal{O}(n^2)$ barrier for Discrete Fourier Transform: Cooley-Tuckey $\mathcal{O}(n\cdot log(n))$ algorithm a.k.a Fast Fourier Transform

$\bullet$ Recurrence Relation and Master Theorem for Divide & Conquer runtime analysis

### Paradigm-III: Dynamic Programming

$\bullet$ Weighted Interval scheduling problem

⭐ Shortest path in a weighted graph G(V,E):
 
$\bullet$ Bellman-Ford $\mathcal{O}(|E| \cdot |V|)$ algorithm
 
$\bullet$ Dijkstra $\mathcal{O}(|E| + |V|log|V|)$ algorithms

⭐ All pair shortest path problem (APSP): Floyd-Warshall $\mathcal{O}(|V|^3)$ algorithm

⭐ Knapsack problem using dynamic programming

## Part-II: Maximum Flow and Minimum Cut (MFmC) Theorem
$\textbf{Maximum Flow Problem in a Graph(V,E)}:$ 

$\textbf{Relation of Max-Flow with Min-Cut using MFmC algorithm}:$

 🌟 Ford-Fulkerson $\mathcal{O}(E\cdot 2^{[log(f)]})$ Algorithm, where 'f' is the maximum edge flow.

 🌟 Improvement in Ford-Fulkerson algo. by Edmond-Karp $\mathcal{O}(V\cdot |E|^2)$ algorithm via Breath first search
 
 ⭐ Orlin's Algorithm: $\mathcal{O}(V\cdot |E|)$ [Without Proof]

 Applications in $\bullet$ Densest Subgraph Problem   $\bullet$ Baseball elimination estimation   $\bullet$ Project-resource selection problem  $\bullet$ Maximum bipartile matching 


## Part-III: Linear Programming and Dual Problem
$Standard\ LP\ Template:$

 
 Find a vector: $\vec{x}$
 
 that maximize: $c^T \vec{x}$
 
 subjected to:  $A\vec{x} \le b$
 
 and: $\vec{x}> 0$ 
 

$\textbf{Casting problems as Linear programming problem}:$

 🌟 Maximum Flow problem in Linear programming template 

 🌟 Linear Regression with absolute error loss function
 
 ⭐ Linear Classification via Support vector machine (Hinge Loss)

 ⭐ Maximum weight bipartile matching

 ⭐ Shortest path in a weighted graph

$\textbf{Duality in Linear Programming}:$

### Primal Form:

Find a vector: $\vec{x}$
 
that maximize: $c^T \vec{x}$
 
subjected to:  $A\vec{x} \le b$
 
and: $\vec{x}> 0$


### Dual Form:
 
 Find a vector: $\vec{y}$
 
 that minimize: $b^T \vec{y}$
 
 subjected to:  $A^{T}\vec{y} \ge c$
 
 and: $\vec{y}> 0$


$\textbf{Max-Flow and Min Cut as Primal-Dual LP problem}:$

$\bullet$ Primal problem: Maximum Flow in a network

$\bullet$ Dual problem: Minimum Cut in a graph 

🎯 Interpretation of Primal and Dual problem

🎯 $\textbf{Weak and Strong Duality Theorem}$ for Linear Programming [Proof Omitted]

### Part-IV: Skyline Problem
2-D and 3-D skyline using $\mathcal{O}(n\cdot log(n))$ algorithms

Sweep line technique with sorted points.
 
Binary tree data structure (BST) with the doubly linked list; Successor and Predecessor Query in BST

Chan Algorithms:  $\mathcal{O}(n\cdot log(k))$; $k$ is number of skyline point

High dimensional generalization: More elaborate Data structures to solve these problems

### Part-V: Approximate Algorithms
Polynomial time approximation algorithms for NP-completes problems

⭐ Minimum set cover via Greedy algorithms

> Greedy is the optimal approach if P is not NP: log(n)-approximate algorithms 

⭐ Optimal Machine-Job scheduling problem:
 
>  Naive greedy algorithms: 2-approximate algorithms
> 
> Greedy on the sorted dataset: 3/2-approximate algorithm

⭐ Vertex cover via linear programming with rounding: 2-approximate algorithms
>
> Vertex cover and set cover interconversion


### Part-VI: NP-Completeness 
> P and NP classes
>
> Polytime primality test (Lucas test)
> 
> Karp Reduction
> 
> 3-SAT reduction to IND-SET
>
> IND-SET reduction to vertex cover

### Randomized Algorithms



