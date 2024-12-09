# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.
## ANswer

We can have a graph that is isomorphic and not completely connected, it is easy to show this by a graph with no edges at all.

$G_1 = (V_1, E_1)$ and $G_2 = (V_2, E_2)$ are two graphs where $V_1 = \{v_1, v_2, v_3\}$.

$V_2 = \{w_1, w_2, w_3\}$

$E_1 = \emptyset$

$E_2 = \emptyset$

A bijective function $f: V_1 \rightarrow V_2$ that:

$f(v_1) = w_1$

$f(v_2) = w_2$

$f(v_3) = w_3$

This shows isomorphism because
1. $f$ is bijective (one-to-one and onto)
2. For any pair of vertices $u,v \in V_1$: $(u,v) \in E_1$ if and only if $(f(u),f(v)) \in E_2$. $E_1$ and $E_2$ are empty so we can say this is true. 

Therefore, $G_1$ and $G_2$ are isomorphic despite having no edges, proving that isomorphic graphs do not need to be completely connected.

