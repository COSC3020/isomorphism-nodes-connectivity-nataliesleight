# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Two conditions that may be checked before testing directly for isomorphism are testing if the two graphs have the same number of vertices/nodes and if the list of the degrees of each node of the two graphs are equal to each other. Our two conditions for graphs $A$ and $B$ are that they do have the same number of nodes and that they are completely connected. By definition, a completely connected graph (or complete graph) states that there is an "edge between every pair of vertices." This means that each node/vertex will have $v-1$ edges (where $v$ is the number of vertices in the graph) because it will point to each vertex except itself. Thus, both graphs $A$ and $B$ have degrees of $v-1$ for all of their nodes. Therefore the two predonditions to testing isomorphism have been satisfied. 

The main test for isomorpism is if there exists a bijective function that would transform the vertices of one graph to another such that the two graphs would become equivalent in terms of vertices and edges. This assumes the "edge structure" is the same and that only the vertices need rearranged to make the graphs equal. Going back to the graphs being completely connected, if from one vertex there is an edge to every other vertex for all vertices, then that means the two graphs will have the same "edge structure." Each node has a path to every other node. Then there exists a function that rearranges the vertices to match the vertices and edges of the other graphs (as the vertices only need to be rearranged). The mapping must exist because every single vertex connects to every other one for each vertex, giving all the vertices the same properties as all of the others. By mapping each vertex in the first graph to a unique vertex in the second graph, the function will be one-to-one and onto. 

For example, let graphs G1 = (V1, E1) and G2 = (V2, E2) have the same number of nodes and be completely connected. Thus each nodes has the same number of degrees. Let the function $f$ be from G1 to G2. Then the first node of G1 corresponds to the first node of G2, then second node of G1 corresponds to the second node of G2, etc. And thus the two graphs are isomorphic to each other.

Thus if two graphs $A$ and $B$ have the same number of nodes and are completely connected, then they are isomorphic.

I received help from the lab TA. 

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.” - Natalie Sleight


