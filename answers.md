# CMPS 2200 Recitation 10## Answers

**Name:____Charles Zhang_**
**Name:**___Yundan Yang__


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**

- $W(m,n) = W(2m) + W(n) + O(1) = O(m+n)$
-   

- **4)**

-  In the worst case, we select a starting node and call reachable once. It will traverse the entire graph, and if it reaches every node, then the graph is connected. If any node is not reached by this process, then the graph is not connected. Therefore, `reachable` will only be called once in all cases.
-  

- **5)**

- $W(m,n) = W(2m) + W(n) +O(1) = O(m+n)$
- 

- **7)**

- the work of the `reachable` function changes primarily because finding all neighbors of a node becomes a $O(n)$ operation, where $n$ is the number of nodes. You must check the entire row in the matrix to see which nodes are connected to the current node, resulting in $O(n)$ work per node, and since this check happens for every node, the total work in the worst case becomes $O(n^2)$. 
