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
To prove that an two graphs (A and B) that have the same number of nodes and are completely connected must be isomorphic, I will provide steps to form the mapping so they are always isomorphic. <br/>
<br/>
Step 1, One-To-One: Create mappings from A to B. To be one-to-one every node in A must map to a distinct node in B, meaning that no two nodes in A map to the same node in B. Since both graphs are completely connect it doesn't matter where you start, so start at any node in A and map it to any node in B that is not already mapped to. Then continue until every node in A has a map to a node in B. Since both graphs have the same number of nodes no node will not have a mapping.
<br/>
Step 2, Onto: Ensure that every node in B has a mapping to it. This is already done because both graphs have the same number of nodes and we created our mappings to be one-to-one. Every node in A maps to a distinct node in B and since both graphs have the same number of nodes this means that every node in B must already have a mapping to it. <br/>
<br/>
Step 3, Ensure that if an edge between two nodes exists in A then after the mapping that edge must exists in B to be isomorphic. Since both graph A and B are completely connected, any edge between 2 nodes in A will also exist in B. 
