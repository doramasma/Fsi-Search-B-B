# Fsi-Search-BranchAndBound
Se han desarrollado dos fuciones, branch_Bound_g(Queue) & branch_Bound_estimate(Queue). El primer caso no se basa en una heurística, se visitan los nodos que tengan menor coste en la cola. En el segundo algoritmo se trata con una heurística que representa el coste del camino, por tanto, vamos expandiendo por el camino mínimo hasta esa instancia.

- From A to B
```
breadth_first
[<Node B>, <Node F>, <Node S>, <Node A>]
El número de nodos visitados es:16
---------------------------------------------
depth_first
[<Node B>, <Node P>, <Node C>, <Node D>, <Node M>, <Node L>, <Node T>, <Node A>]
El número de nodos visitados es:10
---------------------------------------------
Branch and bound 
[<Node B>, <Node P>, <Node R>, <Node S>, <Node A>]
El número de nodos visitados es:24
---------------------------------------------
Branch and bound with subestimation
[<Node B>, <Node P>, <Node R>, <Node S>, <Node A>]
El número de nodos visitados es:6
---------------------------------------------
```
- From D to P
```
breadth_first
[<Node P>, <Node C>, <Node D>]
El número de nodos visitados es:8
---------------------------------------------
depth_first
[<Node P>, <Node C>, <Node D>]
El número de nodos visitados es:3
---------------------------------------------
Branch and bound 
[<Node P>, <Node C>, <Node D>]
El número de nodos visitados es:9
---------------------------------------------
Branch and bound with subestimation
[<Node P>, <Node C>, <Node D>]
El número de nodos visitados es:4
---------------------------------------------
```

- From B to L
```
breadth_first
[<Node L>, <Node M>, <Node D>, <Node C>, <Node P>, <Node B>]
El número de nodos visitados es:41
---------------------------------------------
depth_first
[<Node L>, <Node M>, <Node D>, <Node C>, <Node P>, <Node R>, <Node S>, <Node F>, <Node B>]
El número de nodos visitados es:13
---------------------------------------------
Branch and bound 
[<Node L>, <Node M>, <Node D>, <Node C>, <Node P>, <Node B>]
El número de nodos visitados es:37
---------------------------------------------
Branch and bound with subestimation
[<Node L>, <Node M>, <Node D>, <Node C>, <Node P>, <Node B>]
El número de nodos visitados es:19
---------------------------------------------
```

- From C to E
```
breadth_first
[<Node E>, <Node H>, <Node U>, <Node B>, <Node P>, <Node C>]
El número de nodos visitados es:43
---------------------------------------------
depth_first
[<Node E>, <Node H>, <Node U>, <Node B>, <Node P>, <Node C>]
El número de nodos visitados es:35
---------------------------------------------
Branch and bound 
[<Node E>, <Node H>, <Node U>, <Node B>, <Node P>, <Node C>]
El número de nodos visitados es:36
---------------------------------------------
Branch and bound with subestimation
[<Node E>, <Node H>, <Node U>, <Node B>, <Node P>, <Node C>]
El número de nodos visitados es:8
---------------------------------------------
```




