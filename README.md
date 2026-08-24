# 5critP5H-free
This repository is for the graph6 files of 5-vertex-critical $(P_5,H)$-free graphs for various graphs $H$.
It is currently focused on fringe cases where we know there are infinitely many $k$-vertex-critical $(P_5,H)$-free graphs for all $k > k'$, and we are trying to fill in the gaps for smaller values of $k$.
In particular, graphs $H$ that contain an induced $C_5$ fall into this for all $k > 5$, and it is open only for $k = 5$.

All graphs are generated using [Jorik Jooken's program](https://github.com/JorikJooken/kVertexCriticalGraphs). 

The files currently available are:

- All 5-vertex-critical $(P_5, twin-C_5)$-free graphs ($twin-C_5$ is: the graph of order 6 with graph6 string: [EhdG](https://graphclasses.org/smallgraphs.html#twinC5))
- All 5-vertex-critical $(P_5, \overline{X_{37}})$-free graphs ($\overline{X_{37}}$ is the graph of order 6 with graph6 string: [EUpo](https://graphclasses.org/smallgraphs.html#X37))
- All 5-vertex-critical $(P_5, \overline{C_6})$-free graphs ($\overline{C_6}$ is the complement of the 6-cycle $C_6$)


Despite the name of the repository, some 6-vertex-critical graph files have started to sneak in. 
For H = $\overline{C_6}$, it is also open for $k=6$ if there are only finitely many $k$-vertex-critical $(P_5,H)$-free graphs.
Thus, we have computed all $6$-vertex-critical $(P_5,\overline{C_6})$-free graphs of order $20$ and fewer, of which there are $11,277$. 
With $16,009,686$ non-terminating graphs at level $19$, it is very unlikely to be able to use Jorik's program to compute these for larger orders.
