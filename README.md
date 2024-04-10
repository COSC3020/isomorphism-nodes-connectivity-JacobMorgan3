[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Proof
To be isomorphic the mapping of one graphs nodes to the others nodes must be one-to-one and unto. So for A to be isomorphic to B it's mappings must be one-to-one and onto. To be one-to-one, A's nodes map to distinct nodes of B. And to be onto, A's nodes must have a map to every node in B. For a graph to be completely connected every node has an edge to every other node. <br/>
<br/>
If two graphs have the same number of nodes and are completely connected, then using the informal definition of isomorphism, "two graphs are isomorphic if they have the same structure (ignoring vertex names)" we can clearly see that two graphs with the same number of nodes and are both completely connected have to be isomorphic. There structures have to be the same if they have equal number of nodes and are completely connected. 
