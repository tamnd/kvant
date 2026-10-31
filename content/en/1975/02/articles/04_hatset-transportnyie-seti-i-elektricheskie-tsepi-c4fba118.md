---
id: 1975-2-hatset-transportnyie-seti-i-elektricheskie-tsepi-c4fba118
issue: kvant_1975_2
year: 1975
number: "2"
title: Transport networks and electrical circuits
authors:
  - Хацет А. Б.
rubric: osnovnye-stati
page_first: 12
page_last: 19
page_labels: 10-16
tag: HH2N
lang: en
source: kvant_digital
extraction: vision
content_sha256: 435819b6ed0be8850716cc3982684c589db8124cc77fd2fa20d83546a0924144
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/04_hatset-transportnyie-seti-i-elektricheskie-tsepi-c4fba118.md
source_content_sha256: 287c874e504e895bced702185aee7c76ca167f5b6a64b358705f62b44947a3a0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

1. The solution must be optimal
It is necessary to organize uninterrupted delivery of goods from point A to locality B. There is a sufficient, practically unlimited amount of automated tonnage to point A, but the amount of goods sent from A to B per unit of time is limited due to road conditions.

Points A and B are connected by a network of roads, the diagram of which is shown on figure 1. Number 1 on this diagram indicates the departure point A, number 5 - destination B, numbers 2, 3, 4 - intermediate points - road intersections. The direction of movement is indicated by arrows. Each section of the track can pass in a unit of time no more than a certain number of tons of cargo (determined by the width of the track section at its narrowest point, the nature of the surfaces, the condition of the places, etc.). Let's call this number the capacity and assume it is known for each of the sections of the path connecting one or two points on our diagram.

⟦folio 11⟧

The capacity of the section leading from point $i$ to point $j$ (section $i - j$) will be expressed through $a_{ij}(T/\mu a c)$.

Let us assume that we strive to send as much cargo as possible in each time unit from $A$ to $B$. You should not, however, think that for this you need to send $a_{12}$ tons daily along section $1 - 2$ and $a_{13}$ tons along section $1 - 3$: after all, it may turn out that due to insufficient capacity of other sections of the route, “traffic jams” will form at some intermediate points, as a result of which traffic will be disrupted or stop completely. For example, if $a_{12} > a_{23} + a_{24}$, then a “traffic jam” will occur at intersection 2. This means that for the best organization of cargo transportation from $A$ to $B^*$) we need to solve the following problem: determine how many tons of cargo are needed daily for each section of the road network connecting points $A$ and $B$, so as not to exceed the capacity of any section of the network, not to create a single “traffic jam” at intermediate points and so that the number of goods delivered daily at $B$ is the greatest.

*) Such a supply organization is called optimal.

The required amount of cargo transported through section $i - j$ daily (volume of transportation) will be denoted by $x_{ij}(T/\mu a c)$.

So, the task has been set. But how to solve it?

2. Flipping through old numbers «Kvant»

Looking through the set of magazine «Kvant» for 1970, in the section “Networks and Flows” of M.I. Bashmakov’s article “Matchings and Transport Networks” we find our problem, only in slightly more “discounted” clothes.

It turns out that diagrams made up of points and arrows (as in figure 1) are called directed graphs, with the points being the vertices and the arrows being the edges of the graph. Each arc has a certain direction (hence the name - directed graph), therefore one of the connections of its vertices is the initial one, the other is the final one; they also say that the arc leaves the initial vertex and enters the final one. A vertex that is the initial (final) for all arcs connected to it is called the input (to the output) of the graph (on figure 1 - vertices 1 and 5, respectively). A directed graph with one input and one output is the boundary network (this is the graph on figure 1). Network transport vertices that are not input or output are called projector vertices.

Let's stop this flow of terms for a minute and translate two. Of course, replacing the words “road network” with “transport network”, “point” with “vertex”, “section of route” with “arc” did not bring us any closer to a solution. But it turned out that we were not particularly interested in such a gap. With a little more patience, you will arrive at the formulation of our problem, which is widely known in mathematics.

The required value of traffic volume $x_{ij}$ is called flow along

⟦folio 12⟧

arc $i-j$, and the sum of flows along all arcs leaving the network input (in our case $x_{12} + x_{13}$) is the flow through the network. Now, finally, our task can be given a “ceremonial form”.

Maximum flow problem. A transport network is given, and the capacity is indicated for each Komori arc. It is required to determine flows along network arcs that do not exceed the corresponding throughput capacities, so that for any intermediate vertex the sum of flows along incoming arcs is equal to the sum of flows along outgoing arcs (“flow continuity condition”) and so that the flow through the network is the lowest possible.

So, our problem is a special case of the maximum flow problem (the condition of continuous flow is the familiar condition for the absence of traffic jams). Using the above notation, it can be formed as follows:

Find the maximum $x_{ij}$ flows along the arcs, at which the maximum value of the flow through the network is achieved
$$X = x_{12} + x_{13}$$

(1)
under the following conditions:
a) determination of arc capacity
$$x_{12} \leq a_{12}, x_{13} \leq a_{13}, x_{23} \leq a_{23},$$
$$x_{24} \leq a_{24}, x_{34} \leq a_{34}, x_{35} \leq a_{35},$$
(2)
continuity of flow at passing vertices
$$x_{12} - x_{23} - x_{24} = 0,$$
$$x_{13} + x_{23} - x_{34} - x_{35} = 0,$$
$$x_{24} + x_{34} - x_{45} = 0.$$

(3)
With a steady flow, the number of goods exported from entrance 1 must be equal to the number of goods arriving at exit 5 at the same time (otherwise the conditions of continuity of flow would be violated):
$$X = x_{12} + x_{13} = x_{35} + x_{45}.$$

(4)
Since we found the formulation of our problem in M.I. Bashmakov’s article, it is natural to find a solution there too. And indeed, having delved deeper into the reading, we find a presentation of the Ford-Folkerson algorithm, with the help of which you can determine all the values ​​of $x_{ij}$ (assuming, however, that these are integers). Just be patient; To understand the algorithm and be able to apply it, you will have to work hard. It would not be surprising if readers who don’t like calculations would ask at this point: is it possible to do it differently?

3. Oh full of analogies

Look externally at equation (3). In some way they are very familiar to us... Bah, but if the transport network is considered an electrical circuit, and the volumes of transportation $x_{ij}$ are the magnitudes of currents in accordance with their branches of the circuit, then equations (3) simply express Kirchhoff’s 1st law for intermediate nodes of the chain: by allegation, the sum of currents in a node is equal to zero (that is, the sum of currents flowing into a node is equal to the sum of currents flowing from node)!

True, this analogy is not complete, since Kirchhoff’s law is usually formulated for a closed circuit and applies to any non-closed circuit, and conditions like (3) are not true for extreme nodes 1 and 5. However, it is possible to change the flow problem in such a way that the noted divergence of the device. For this purpose, we will not introduce an additional limiting arc into the transport network, but use the flow along it equal to $X$, that is, the flow through the network. According to the resulting generalized network, the flow will make a closed path from the entrance to the exit along a given transport network, and then from the exit to the entrance along an additional arc.

Then our problem can be reformulated as follows: also determine the generalized transportation $x_{ij}$, for which

⟦folio 13⟧

Fig. 2.

we access the maximum value $X$ (seven assists) under restrictions (2) and conditions (3) and (4) of flow continuity at all nodes:

$$X - x_{12} - x_{13} = 0,$$
$$x_{12} - x_{23} - x_{24} = 0,$$
$$x_{13} + x_{23} - x_{34} - x_{35} = 0,$$
$$x_{24} + x_{34} - x_{45} = 0,$$
$$x_{35} + x_{45} - X = 0.$$

The result was a complete analogy with Kirchhoff’s law, and therefore the question arises: is it possible to build an electrical model of a transport network in which the required flows along the arcs would correspond to currents in the branches, determined directly by measurement without any calculations?

We will show that such a model can be built.

Naturally, the arcs of the network in this model should correspond to the branches of the electrical circuit, and the apex should correspond to the nodes of the circuit.

Swept it up. We will use the following notation: $\sigma$ - source of current in the indicated direction, $a$ - current strength in the branch; $\mu$ — source of direction, $u$ — direction magnitude in the branch; $\beta$ is a diode that passes current in the direction from left to right.

For current to flow through a circuit, there must be some electrical force present in it. Therefore, in the additional branch of the circuit the source of a single direction

⟦folio 14⟧

Fig. 4.

At the same time, nodes $\alpha$ and $\beta$ appeared in the branch diagram, which were not transported. The direction and magnitude of the current in branch $\alpha - M - \beta$ containing the current source are carried out by this source; the direction of the current in branch $\alpha - N - \beta$ is determined by the diode; We denote the magnitude of the current in it by $I_{ij}$. We denote the currents in branches $i - \alpha$ and $\beta - j$ by $\tilde{x}_{ij}$ and $\tilde{y}_{ij}$, respectively; the directions of these currents are indicated in the diagram.

Application of Kirchhoff's law gives:
1) at node $\alpha$: $\tilde{x}_{ij} + I_{ij} = a_{ij}$ or $I_{ij} = a_{ij} - \tilde{x}_{ij}$ by property of diode $I_{ij} \geq 0$, therefore,
$$\tilde{x}_{ij} \leq a_{ij},$$
(6)
2) at node $\beta$: $a_{ij} = \tilde{y}_{ij} + I_{ij}$, that is
$$\tilde{y}_{ij} = \tilde{x}_{ij}.$$
(7)

This means that along the main branch $i - j$ of the circuit there is a current of a given direction (from node $i$ to node $j$), the value of which $\tilde{x}_{ij}$ does not exceed the capacity $a_{ij}$, respectively; according to the rules for constructing the model $U = 1$.

We claim that the current $\tilde{x}_{ij}$, established in the main branches of the electric transportation model, is numerically equal to the volume of transportation along the corresponding arcs and provides a solution to the problem of maximum

⟦folio 15⟧

nom stream for this network. In this case, the current $\tilde{X}$ in the additional branch of the model is numerically equal to the maximum flow through the network.

If we manage to prove this, then the constructed model completely solves our problem: it’s enough, let’s put the model into action, to change the currents $x_{ij}$ in the branches with an amperator!

4. So - let's get to work

To make sure that the numerical values ​​of currents $\tilde{x}_{ij}$ in the branches of the model are traffic volumes that provide a solution to the maximum flow problem, it is necessary to prove that at $\tilde{x}_{ij} = \tilde{x}_{ij}$ conditions (2) and (3) are satisfied and that the value of flow $X$ in the network is taken to be the most possible value.

We have already proven not the first part of this statement. In fact, having written inequalities (6) for all branches of the model $\tilde{x}_{12} \leq a_{12}, \tilde{x}_{13} \leq a_{13}, \tilde{x}_{23} \leq a_{23}, \tilde{x}_{24} \leq a_{24}, \tilde{x}_{34} \leq a_{34}, \tilde{x}_{35} \leq a_{35}, \tilde{x}_{45} \leq a_{45}$, (9) we obtain that for currents $\tilde{x}_{ij}$ conditions (2) are satisfied, and applying Kirchhoff’s 1st law to all main nodes of the model, we obtain five corresponding conditions (3) for currents $\tilde{x}_{ij}$.

This means that all that remains is to prove that the value $\tilde{X}$ in the electric circuit is the most possible value of the flux $X$, compatible with conditions (2) and (3). The proof of this fact consists of two parts.

1. Let us first show that for any values ​​of the variables $x_{ij}$ satisfying conditions (2) and (3), the inequality
$$\tilde{X} = x_{12} + x_{13} \leq \sum_{i,j} a_{ij}u_{ij},$$ (11)

where $u_{ij}$ is the numerical value of the voltage in branch $i - j$, and the sum is taken over all branches of the electrical circuit *), that is, we will show that for any permissible volumes of transportation along the network transportation arcs, the flow $X$ through the network does not exceed the number $\sum_{i,j} a_{ij}u_{ij}$.

Due to inequalities (2) and the non-negativity of $u_{ij}$ (see (8)), we have $x_{ij}u_{ij} \leq a_{ij}u_{ij}$; hence,
$$\sum_{i,j} x_{ij}u_{ij} \leq \sum_{i,j} a_{ij}u_{ij}.$$ (12)

Let us now remember that $u_{ij} = p_i - p_j$, where $p_i, p_j$ are the potentials corresponding to the nodes. That's why
$$\sum_{i,j} x_{ij}u_{ij} = \sum_{i,j} x_{ij}(p_i - p_j) = x_{12}(p_1 - p_2) + x_{13}(p_1 - p_3) + x_{23}(p_2 - p_3) + x_{24}(p_2 - p_4) + x_{34}(p_3 - p_4) + x_{35}(p_3 - p_5) + x_{45}(p_4 - p_5) = p_1(x_{12} + x_{13}) + p_2(-x_{12}) + p_2(x_{13} - x_{23}) + p_3(-x_{13} - x_{23}) + p_4(-x_{24} - x_{34}) + p_5(-x_{35} - x_{45}).$$

The expressions in parentheses at $p_2, p_3$ and $p_4$ are equal to zero (see (3)); when $p_1$ and $p_5$ are equal to $X$ and $-X$ (see (4)), $p_1 - p_5 = U = 1$; That's why
$$\sum_{i,j} x_{ij}u_{ij} = p_1X - p_5X = (p_1 - p_5)X = X.$$ (13)

Taking (12) into account, we obtain the required inequality
$$\tilde{X} \leq \sum_{i,j} a_{ij}u_{ij}.$$ (14)

*) The symbol $\sum_{ij}$ denotes the sum of terms of the type under consideration, corresponding to all the possible set of index values ​​$i, j$ for a given problem. In our case
$$\sum_{i,j} a_{ij}u_{ij} = a_{12}u_{12} + a_{13}u_{13} + a_{23}u_{23} + a_{24}u_{24} + a_{34}u_{34} + a_{35}u_{35} + a_{45}u_{45}.$$

⟦folio 16⟧

Fig. 5.

This will mean that $\tilde{X}$ is the most possible value of $X$.

To prove equality (14), we use correspondence (8), which describes the property of an ideal diode:

$$u_{ij} (a_{ij} - \tilde{x}_{ij}) = 0$$ or $a_{ij} u_{ij} = \tilde{x}_{ij} u_{ij}$.

It immediately follows that

$$\sum_{i,j} a_{ij} u_{ij} = \sum_{i,j} \tilde{x}_{ij} u_{ij}.$$ (15)

Since the currents $\tilde{x}_{ij}$, $\tilde{X}$ satisfy the same correspondences (1), (4) as for $x_{ij}$ and $X$, then

$$\sum_{i,j} \tilde{x}_{ij} u_{ij} = \tilde{X}.$$ (16)

5. Try it yourself

From the same (idealized!) elements—current sources, voltage sources, and diodes—electrical models can be built to solve other optimization problems associated with transport networks. Let us consider here one such problem that has more significance in economics.

The problem of minimizing transport costs. Let there be a transport network and it is known that the cost of transporting a unit of cargo along duée $i - j$ is equal to $c_{ij}$ (see Fig. 5). It is required to determine the volume of transportation $x_{ij}$ by air

Fig. 6.

⟦folio none⟧

gam of the network, in which 1 unit of cargo will be transported from the input of the network to its output, and the total cost of transportation will be minimal.

Transporting $x_{ij}$ units of cargo along an arc $i-j$ costs $c_{ij}x_{ij}$.

Therefore, the total transportation costs are equal to

$$S = \sum_{i,j} c_{ij} x_{ij}. \tag{17}$$

It is necessary to find such values ​​of quantities $x_{ij}$ at which $S$ takes the smallest possible value and which satisfy the conditions:

a) continuity of flow at intermediate nodes (see (3));

b) non-negativity of traffic volumes: $x_{ij} \geqslant 0$;

c) equal to one unit of the total flow through the network:

$$X = x_{12} + x_{13} + x_{35} + x_{45} = 1. \tag{18}$$

To build an electrical model of the transport network for this problem, it is necessary to replace each arc $i-j$ with a branch with a diode and a voltage source connected in series, the value of which is numerically equal to $c_{ij}$, and to include a single current source in the additional branch from the output to the input of the network. The corresponding diagram is presented in figure 6.

It can be proven...

But it’s time for us to put an end to it. Readers interested in these questions can try their hand at solving the following

Exercises

1. Prove that the currents $x_{ij}$, which are installed in the branches of the electrical circuit shown in figure 6, provide a solution to the problem of minimizing transport costs.

2. Prove that every non-zero current along a branch of this circuit is necessarily equal to 1, i.e., that in reality the current does not branch at the nodes, but goes from input to output along a certain path (“the path of minimum cost”).

3. Using the problem of minimizing transport costs, show how the same model (Fig. 6) can be used to determine the shortest path along the arcs of a transport network leading from the entrance to the exit.

2 Quantum No. 2

⟦column⟧
