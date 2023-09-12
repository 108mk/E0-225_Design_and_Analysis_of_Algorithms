# E0-225_Design_and_Analysis_of_Algorithms
E0225: Design and Analysis of Algorithms is a foundational course at the Computer Science department, IISc Bengaluru. It aims to develop algorithmic thinking in students.

:accessibility: Highlights of important algorithmic paradigms and their real-world applications:
## Part-I: Greedy, Divide & Conquer and Dynamic Programming
$\textbf{Paradigm-I: Greedy Algorithm}$
> $\bullet$ Stable Matching Problem: Galey-Shapley Algorithms and its connection to Boston-Pool algorithm
> 
> $\bullet$ Interval Scheduling: Where Greedy approach fits like a champ(!)
>
> $\bullet$ Minimum Spanning Tree (Weighted Graph): $\bullet$ Boruvka algorithm $\bullet$ Prin-Jarnik algorithm and $\bullet$ Krushkal Algorithms 

⭐ (Graphic) Metroid Scheme: Power and limitations of Greedy approach

$\textbf{Paradigm-II: Divide and Conquer}$

🎯 $\bullet$ Breaking $\mathcal{O}(n^2)$ barrier for Multiplication: Karastuba $\mathcal{O}(n\cdot log(n))$ algorithm
> 
🎯 $\bullet$ Breaking $\mathcal{O}(n^2)$ barrier for Discrete Fourier Transform: Cooley-Tuckey $\mathcal{O}(n\cdot log(n))$ algorithm a.k.a Fast Fourier Transform

> $\bullet$ Recurrence Relation and Master Theorem for Divide & Conquer runtime analysis

$\textbf{Paradigm-III: Dynamic Programming}$
> $\bullet$ Weighted Interval scheduling problem

> ⭐ Shortest path in a weighted graph G(V,E):
> 
> $\bullet$ Bellman-Ford $\mathcal{O}(|E| \cdot |V|)$ algorithm
> 
> $\bullet$ Dijkstra $\mathcal{O}(|E| + |V|log|V|)$ algorithms

> ⭐ All pair shortest path problem (APSP): Floyd-Warshall $\mathcal{O}(|V|^3)$ algorithm
>
> ⭐ Knapsack problem using dynamic programming

## Part-II: Maximum Flow and Minimum Cut (MFmC) Theorem
$\textbf{Maximum Flow Problem in a Graph(V,E)}:$ 

$\textbf{Relation of Max-Flow with Min-Cut using MFmC algorithm}:$
>
> 🌟 Ford-Fulkerson $\mathcal{O}(E\cdot 2^{[log(f)]})$ Algorithm, where 'f' is the maximum edge flow.

> 🌟 Improvement in Ford-Fulkerson algo. by Edmond-Karp $\mathcal{O}(V\cdot |E|^2)$ algorithm

> Applications in $\bullet$ Densest Subgraph Problem   $\bullet$ Baseball elimination estimation
>

