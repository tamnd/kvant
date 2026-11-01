---
id: 1982-8-dubrovskiy-matematika-volshebnogo-kubika-4b89e44f
issue: kvant_1982_8
year: 1982
number: "8"
title: Magic Cube Mathematics
authors:
  - Дубровский В. Н.
rubric: osnovnye-stati
page_first: 24
page_last: 29
page_labels: 22, 23, 24, 26, 27
tag: O2V3
lang: en
source: kvant_digital
extraction: vision
content_sha256: e2e9d48c857ba700d2eccafe60479c5790d435a20210918c15ac36f7e7352cd7
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/08_dubrovskiy-matematika-volshebnogo-kubika-4b89e44f.md
source_content_sha256: b3f5d8b2938c16a27a5325d6aed22202a70b639c0f24111d0f38a5d29d5325e4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

V. Dubrovsky

Mathematics
magic cube

«Kvant» already talks in detail about the design of the Hungarian “magic cube” and the algorithms for solving this puzzle *). Following the cube, a whole series of games similar to it were born. Our article is devoted to the mathematical theory of such games. And for fans of practical cube play, we present a schematic diagram of a record-breaking short magic cube algorithm based on this theory.

Magic cube asks questions
Let us agree to call the various options for assembling a magic cube that arise when 8 corner small cups are randomly placed along the vertices of the magic cube and 12 medium ones along the edges, its states. The central cubes in all states are located the same way - the same as in the zero state, when each face of the magic cube turns out to be legal, that is, is it possible, by collecting small cubes in a random order, to then obtain the zero state by turning the faces? If not, how can you find out whether a given state is legal and, in general, whether two given states are related? How many legal ones are there?

*) «Kvant», 1980, No. 12, p. 17; 1982, No. 3, p. 20 and No. 7, p. 22; see also “Nuuka and Life”, 1981, No. 3, p. 131 and 1982, no. 2, p. 97.

⟦folio 23⟧

Fig. 1. Zero state. The hidden corner cube has number 9, the hidden corner cube has numbers 10, 11, 12. On the hidden edges, the arrows are aligned with the arrows on the edges that are symmetrical to them relative to the center of the cube.

states, in other words, how many different colors of a magic cube can you get by rotating its faces? What is the maximum number of pairwise unconnected states? First of all, let's figure it out

How to set the state

To fully describe the state of the magic cube, you need to indicate for each small cube the place it occupies and its orientation in this place - each corner cube can be placed in the same “slot” of the tray, and the middle one can be placed in two ways.

Let's imagine that the magic cube is in the zero state. Let's renumber its vertices and the corner cubes in them with numbers from 1 to 8, and the edges and the corresponding middle cubes with numbers from 1 to 12. In addition, on each edge of the magic cube we will choose a certain direction (mentally on Fig. 1) and draw an arrow of the same direction on the corresponding middle cube (Fig. 1).

Now the location of the $i$-th corner ($j$-middle) cube in state $S$ can be specified by the number $\sigma_s(i)(\tau_s(j))$ of the vertex (of that edge) where it is located (here $i=1$, ..., 8, $j=1$, ..., 12).

To set the orientation of the corner cups, select a pair of opposite faces of the magic cube, for example its horizontal faces. To determine this, let us assume that the top central cube is

blue, and the bottom one is green*). Each corner cube has either one blue side or one green side; the angle $\alpha(\alpha=0^\circ, 120^\circ$ or $240^\circ)$, at which this cube follows in its “nest” around the diagonal of the large cube counterclockwise**), so that this (blue or green) face becomes horizontal, we will call the angle of rotation of this corner cube in the state $S$ and denote it $\alpha_s(i)$, where $i$ is the number of the cube.

Orientation of the $j$-th middle cube in the $S$ state by a given angle $\beta_s(j)$ between the direction of the arrow on it and the direction of the edge on which it is located (the $\tau_s(j)$-th edge). Angle $\beta_s(j)$ can equal $0^\circ$ or $180^\circ$; we will call it the rotation angle of the $j$-th middle cube in the $S$ state.

What do linked states have in common?

We need to find out in what case two states are related to each other. For this purpose, let us trace how the characteristics of the state $\alpha_s, \beta_s, \sigma_s$ and $\tau_s$ change when the faces are rotated. Let's start with corner turns. It's easy to check that

A. The angles of rotation of the corner cups do not change when the four vertical faces are rotated by $180^\circ$ and when the horizontal faces are arbitrarily rotated.

B. The angles of rotation of the middle cups do not change when two opposite (right or left on Fig. 1) faces are rotated by $180^\circ$ and when the 对立 faces are rotated arbitrarily.

B. When any vertical face is rotated by $\pm 90^\circ$, $120^\circ***$) is added to the rotation angles $\alpha_s$ of two cups standing at its opposite vertices, and to the corners

*) By the way, the cube is colored differently. We mean a cube whose green and blue sides are opposite.

**) Of course, without destroying the magic cube, it is impossible to actually rotate its corner cube in its nest - we are defining a theoretical concept here.

***) As is customary, we add the rotation angles with an accuracy of $360^\circ$, for example $240^\circ + 240^\circ = 120^\circ, 180^\circ + 180^\circ = 0^\circ$, etc.

⟦folio 24⟧

Fig. 2. After rotating the right edge 90° clockwise. Here $\tau(1)=2$, $\tau(4)=1$, $\tau(2)=3$, $\alpha(1)=\alpha(3)=120^\circ$, $\alpha(2)=\alpha(4)=240^\circ$, $\beta(1)=\beta(2)=\beta(3)=\beta(4)=180^\circ$.

the rotations of its other two corner cups are added by 240°.

D. When you rotate the right or left (Fig. 2) face by ±90°, the angles of rotation of all four middle cups of this face change.

From here it immediately follows that the sums of the angles of rotation of all corner and all middle cups

$$A(S) = \alpha_S(1) + \alpha_S(2) + \ldots + \alpha_S(8),$$
$$B(S) = \beta_S(1) + \beta_S(2) + \ldots + \beta_S(12)$$
remain constant for all rotations of the faces. Such characteristics of a state are called invarants (from the Latin “unchanging”). The values ​​of any invarant for two bound states $S_1$ and $S_2$ obviously coincide. Therefore, the equalities $A(S_1) = A(S_2)$ and $B(S_1) = B(S_2)$ are necessary conditions for the connectedness of states. We will soon see that by adding to them a similar equality for another invarant, we will obtain sufficient conditions. But, before defining this third invarant, we have to make a small absence

About permutations

A permutation of a finite set is any mapping of this set onto itself. Thus, the function $\sigma_S$ defined above, defined on the set {1, ..., 8}, is a permutation of this set, and $\tau_S$ is a permutation of the set {1, ..., 12}. Any operation $F$ is also associated with two permutations $\sigma_F$ and $\tau_F$ of the same set: if the zero state $S_0$ is transferred by the operation $F$ to the state $S$, then, by definition, $\sigma_F(i) = \sigma_S(i)$, $\tau_F(j) = \tau_S(j)$. In other words, $\sigma_F(i)$ and $\tau_F(j)$ are the numbers of those places (see Fig. 1) that, as a result of the operation $F$, are occupied by the corner cube standing in the $i$th place and the middle cube standing in the $j$ place.

Perform one after another permutations $\sigma_1$ and $\sigma_2$ of the same set, we again obtain its mapping onto itself - the permutation $\sigma$. It is called `композицией` $\sigma_1$ and $\sigma_2$: $\sigma = \sigma_1 \circ \sigma_2$.

Problem 2. Let operation $F$ move the magic cube from state $S'$. Prove that $\sigma_S' = \sigma_S \circ \sigma_F$, $\tau_S' = \tau_S \circ \tau_F$. Prove also that $\sigma_{F_1} \circ F_2 = \sigma_{F_1} \circ \sigma_F, \tau_{F_1} \circ F_1 = \tau_{F_1} \circ \tau_F$, where $F_1 \circ F_2$ is the composition of the operations $F_1$ and $F_2$.

Let $\sigma$ be an arbitrary permutation of the set {1, 2, ..., $n$}. Let's draw two lines of $n$ dots, one below the other. If during the permutation $\sigma$ the number $i$ goes into $j$, we connect the $i$th point of the upper line with a segment to the $j$th point of the lower line - we get the permutation graph $\sigma$ (Fig. 3). Let us denote by $N(\sigma)$ the number of the intersection point of the graph segments (we count the point at which more than two segments intersect as many times as there are pairs of segments it contains). The permutation $\sigma$ is called `четной` (odd) if

⟦folio 26⟧

The edge of the selected medium cube is marked with a white sticker, and the white edge is marked with a blue sticker. We get state $S_1^1$. Let's translate it into $S_2^1$ and the symmetry of the sticker - we get state $S_2^1$. Therefore, states $S_1$ and $S_2$ are connected. Similarly, it is proved that any two states with the same invariants are related. Thus, each of the $3 \times 2 \times 2 = 12$ sets of values of the invariants $A$, $B$ and $E$ (A takes three values: $0^\circ$, $120^\circ$ and $240^\circ$, $B$ - two: $0^\circ$ and $180^\circ$, $\varepsilon$ - also two: 1 and -1) defines a class of pairwise related states with this set of invariants, and states from different classes are not related; one of the classes is formed by legal states.

Problem 4. Prove that the number of states in all classes is the same and equal to $8! \cdot 3^8 \cdot 11! \cdot 2^{12}$.

Problem 5. Prove that the values ​​of the invariants $A$, $B$, $\varepsilon$ depend only on the state of the magic cube, but not on the choice of a pair of faces directed to the edges and the numbering of vertices and edges.

Record algorithm

The journal Scientific American (1981, No. 3) describes the general idea of ​​a remarkably short magic cube algorithm, invented by the English mathematician M. Thistlethwaite. Having obtained this algorithm, you can go from any legal state to a zero state in no more than 52 moves*). Thistlethwaite's algorithm is fundamentally different from the algorithms that are described in the articles we mentioned above. In general terms, its scheme is as follows.

Let us introduce three restrictions on permissible rotations of faces:

1) it is prohibited to rotate two opposite vertical faces (for example, the right or left one at Fig. 1) by ±90°;
2) it is prohibited to rotate any vertical edge by ±90°;
3) All rotations of the edges by ±90° are prohibited.

Let us denote by $\Phi_1$, $\Phi_2$, $\Phi_3$ the set of all operations that satisfy the correspondence (for example, $\Phi_3$ are all possible sequences of rotations of faces on

*) The same magazine reports that in reality 23 moves are always enough (!), and this number cannot be reduced. Apparently, a short column of a realizable algorithm for solving the cube has not yet been found.

180°), and through $\Sigma_1$, $\Sigma_2$, $\Sigma_3$ the class of all states obtained from the zero operation from $\Phi_1$, $\Phi_2$, $\Phi_3$. It is clear that $\Sigma_1 \supset \Sigma_2 \supset \Sigma_3 \supset S_0$ and that any two states from the class $\Sigma_k$ are related to each other by the operation from $\Phi_k$. The entire algorithm is divided into four stages. The first one performs the following operation $F$ (without restrictions on moves), which transfers the initial state $S$ to some state $S_1 \in \Sigma_1$. In the future, only operations from $\Phi_1$ will be expanded. At the second stage, using operation $F_1 \in \Phi_1$, it is executed in state $S_2 \in \Sigma_2$, in the third, using operation $F_2 \in \Phi_2$, it is executed in state $S_3 \in \Sigma_3$. Finally, at the fourth stage, rotating the faces only by 180°, we must obtain from the state $S_3$ the zero state $S_0$.

Obviously, once we get to class $\Sigma_k$ after the next stage, we never leave it, so the achievements of all previous stages are saved automatically. In addition, until the last stage there is no need to “sunbathe” small places. But the main advantage of this scheme is that it is much better than sensory devices for computer calculations. It is believed that this played a decisive role in “establishing a world record.”

Before constructing an algorithm according to this scheme, it is necessary to find out what the state classes $\Sigma_1$, $\Sigma_2$, $\Sigma_3$ are. This is where invariants come in handy. Classes $\Sigma_1$ and $\Sigma_2$ are easy to understand. Let us recall the properties $A$ and $B$ of the rotation angles of small cups, we see that the smile of repeated middle cups $\beta_S(j)$ is invariant to the relative operation from $\Phi_1$ (property $B$), the smile of repeated corner cups $a_S(i)$ is invariant to the relative operation from $\Phi_2$ (property $A$). It is also easy to notice that during operations from $\Phi_2$ the four middle cubes located in the horizontal “middle layer” between the top and bottom faces can only change places among themselves, so that the composition of this layer remains unchanged.

Problem 6. Prove that the quantities $A(S)$, $\varepsilon(S)$ and $\beta_j(S)$ (j=1, ..., 12) form a complete system of invariants of the relative operation of $\Phi_1$, and $\varepsilon(S)$, $\alpha_i(S)$ (i=1, ..., 8), $\beta_j(S)$ (j=1, ..., 12) and composition horizontal middle layer - relative operation from $\Phi_2$.

It is equally easy to verify that with operations from $\Phi_3$, in addition to the invariants listed in task 6, the compositions of the two vertical middle layers and the compositions of the two quadruples of corner cups forming regular tetrahedra (on Fig. 1 into one) are also preserved

⟦folio 27⟧

one of them includes corner cubes 1, 3, 5, 7, and the other - 2, 4, 6, 8). But that's not all! There is one more invariant with respect to the set of operations $\Phi_3$, which describes the dependence between permutations of corner cups inside quadruples. Take any two cubes of one of the fours. They are adjacent to one of the faces of the cube. If this is the right or left side, then we say that these cubes occupy the 1st position, if the front or back - then the 2nd, if the top or bottom - then the 3rd. It is clear that the second pair of cups of this four always occupies the same position as the first. For simplicity, we restrict ourselves to states $S$, in which the composition of quadruples is “correct” (as in the zero state). Consider the first quadruple and define the permutation $p_S$ set {1, 2, 3} by putting $p_S(i) = j$ if the pair of cups of this quadruple, occupying the i-th position in the state $S_0$, occupies the j-th position in the state $S$. Similarly, for the second quadruple we define the permutation $q_S$. Our final invariant is the permutation $\delta_S = p_S \cdot q_S^{-1}$). It can take any of 3!=6 values.

Problem 7. Prove that $\delta_S$ is indeed invariant with respect to $\Phi_3$ and that, together with the invariants listed above, it forms a complete system for $\Phi_3$.

It is now clear that at each stage of the algorithm we should strive to ensure that the values ​​of the next portion of the invariants we found become the same as for the zero state.

We invite readers to independently develop an algorithm or its individual stages according to the specified scheme and send their versions to the editor. The best of them will be published.

Pongogram to other games

Further, people unsophisticated in mathematics will immediately recognize the magic cube as a “relative” of the replaced puzzle “15” by Sam Loyd, although in appearance they are completely different. The similarity lies in the general structure of these games, which can be described as follows: there is a certain system capable of operating in various states, among which one (“zero”) state is highlighted. The task is to transfer an arbitrary given state to zero, using a certain set of standard transformations of the system (in the case of a magic cube - rotations of the faces by $\pm 90^\circ$ or $180^\circ$), which can be called elementary operations or moves. Moreover, any move is reversible (that is, having made it, we can always return to the original state with one move).

Just as for the magic cube, in the general case the concepts of an operation, associated with states, and an invariant are defined. Another useful concept is a state orbit: this is the name given to the set of all states associated with a given one. In particular, as we have seen, the state set of the magic cube splits into 12 orbits.

We offer the reader a number of problems devoted to the study of the played type. Problems 8-10 require proving some general properties of these games (only their formulations are given). Problems 11-16 examine various examples, and only give a description of the game, but you need to answer the following questions: 1) what is the complete set of invariants of this game? 2) how to transfer one of two connected states to another? 3) what is the number of orbits and states in one orbit?

Task 8.

8. We will write $S_1 \approx S_2$ if states $S_1$ and $S_2$ are connected. Then for any state $S_1, S_2, S_3$ 1) $S_1 \approx S_1, 2) S_1 \approx S_2 \Rightarrow S_2 \approx S_1, 3) S_1 \approx S_2, S_2 \approx S_3 \Rightarrow S_1 \approx S_3$. In other words, the relation $S_1 \approx S_2$ is an equivalence relation.

9. The orbits of any two states $S_1$ and $S_2$ either coincide (if $S_1 \approx S_2$) or do not have common elements.

10. If any operation that transforms at least one state into itself also transforms any other state, then the number $N_0$ state in all orbits is the same, and the number of all states is $N = N_0 \cdot k$, where $k$ is the number of orbits. Check that the specified properties of the operation are true for the magic cube.

11. Explore games that differ from the “magic cube” only in a set of operation elements: 1) only 2 (3, 4 or 5) faces are allowed to be rotated; 2) a move is a rotation of a pair of opposite faces (one clockwise and the other counterclockwise) at the same angle; 3) respectively, both faces clockwise.

(For the end see page 48)
