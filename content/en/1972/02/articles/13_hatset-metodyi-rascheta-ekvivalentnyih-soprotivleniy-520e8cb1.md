---
id: 1972-2-hatset-metodyi-rascheta-ekvivalentnyih-soprotivleniy-520e8cb1
issue: kvant_1972_2
year: 1972
number: "2"
title: Methods for calculating equivalent resistances
authors:
  - Хацет А. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 60
page_labels: 54, 56, 58
tag: J1P3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2778ac72062d9ad27a015276e76c75782d03192905667434551d1392d762e852
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/13_hatset-metodyi-rascheta-ekvivalentnyih-soprotivleniy-520e8cb1.md
source_content_sha256: e5f645ce8109633dc00855dc538629629b33c84238a796db636f41a14bd1e017
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

1. Equivalent node method

The idea behind the method is to treat different nodes of a circuit that have equal potential as one node. In this case, the potential in the resulting “glued” node is equal to the total potential of the original nodes.

If equivalent nodes are connected by a conductor (without resistance), then the electrical condition in all nodes and branches of the circuit does not change, since no current will flow through this conductor.

Let's look at examples.

Task 1. Find the resistance equivalent to the section of the circuit shown in figure 1, $a$ (all resistances in the diagram are the same and equal to $r$).

Solution. It is easy to understand that nodes 1, 2 and 3 have equal potential. In fact, from the symmetry messages it is clear that the currents flowing through branches A-1, A-2 and A-3 are the same. Therefore, due to the equality of the resistance of these branches, the potential drops on them are also the same and the potentials of nodes 1, 2 and 3 are the same.

Similarly, it can be shown that nodes 4, 5 and 6 also have equal potentials (equivalent).

It is clear that the circuit resistance will not change if equivalent nodes 1, 2 and 3 are connected together. The resistance of the circuit will not change if you connect the second three equivalent nodes.

Having done this, we obtain a circuit equivalent to this one (Fig. 1, 6). The resistance of this circuit is not difficult to find: the resistance of section $AN$ is $\frac{1}{3} r \left( \frac{1}{R_{AN}} = \frac{1}{r} + \frac{1}{r} \right)$, the resistance of section $NM$ is $\frac{1}{6} r$, and the resistance of section $MB$ is $\frac{1}{3} r$. Therefore $R_{AB} = \frac{5}{6} r$.

⟦folio 56⟧

Fig. 3.

Actually, no current flows through section $FF'$. Pozny can remove section $FF'$ and we get the equivalent circuit shown in figure 4, b. After simple transformations of the circuit (Fig. 4, θ) it is easy to calculate that its resistance is $R = \frac{7}{6} r$.

3. Method of "reproduction" of nodes

This method is also closely related to the method of equivalent nodes. If replacing several equivalent nodes with one (connecting nodes) led to an equivalent circuit, then the reverse replacement of one node with several equivalent nodes will not violate the electrical conditions in the rest of the circuit.

Let us give examples of circuits for which such a transformation is appropriate.

Task 5. Find the resistance of the circuit section shown in figure 5, a.

Let's replace node $O$ with tray nodes; $O_1$, $O_2$ and $O_3$ (Fig. 5, b). However, we still need to prove that these circuits are equivalent. For circuit equivalence, nodes $O_1$, $O_2$ and $O_3$ must be equivalent. But this is very indo, since the potential difference $\varphi_{O_2}$ - $\varphi_A$ is equal to half the potential difference of points $A$ and $B$: $\varphi_{O_2} - \varphi_A = \frac{1}{2} u_{AB}$.

Similarly, from the symmetry reports of the inclusion of resistance, it is not difficult to find that $\varphi_{O_1} - \varphi_A = \frac{1}{2} u_{AB}$ and $\varphi_{O_3} - \varphi_A = \frac{1}{2} u_{AB}$. Therefore, $\varphi_{O_1} = \varphi_{O_2} = \varphi_{O_3}$, that is, nodes $O_1$, $O_2$ and $O_3$ are equivalent. Now finding the circuit resistance is not difficult. It is equal to 0.8 $r$ (Fig. 5, θ).

⟦folio 58⟧

Fig. 7.

Task 7. Find the resistance $R$ of the circuit shown in figure 7, a.

Solution. Let us replace branch $OC$ with two parallel branches with equal resistances $2 r$. We then divide node $C$ into equivalent nodes $C_1$ and $C_2$ (their equivalence follows from the symmetric relative messages of nodes $A$ and $O$). The circuit shown at figure 7, 6 is equivalent to the circuit at figure 7, a. Let's find its resistance. Sections $BO$ and $BC_1O$ are connected in parallel. Postural resistance $R_{BO} = \frac{3}{4} r$.

Likewise, $R_{OD} = \frac{3}{4} r$. Now nodes $A$ and $O$ are connected by three parallel branches with resistances $\frac{7}{4} r, r, \frac{7}{4} r$. The total resistance of the circuit is $R = \frac{7}{15} r$ (Fig. 7, g).

5. Recurrent method

Recurrent methods for solving problems are general methods in which the problem is solved step by step, and at the $n$th step it is necessary to use the results obtained in the previous steps. Recurrent methods in problems of calculating circuit resistance are especially convenient when the circuit has a repeating structure and the number of resistances is large.

Task 8. Find the resistance of the circuit shown in figure 8, a, where $r_1 = \frac{r}{2}, r_2 = \frac{r}{2}, r_3 = r_4 = r_5 = r_6 = r$.

Solution. Let us redraw the chain as shown in figure 8, 6. It is clear that the calculation must be carried out from the end $B$. Replacing resistance $r_3, r_6$ and $r_2$ with the equivalent resistance $R = r_2 + \frac{r_3 r_6}{r_3 + r_6} = r$, we obtain the circuit shown in figure 8, c. Now the resistances $R, r_5$ and $r_1$ can again be replaced by the equivalent $R_1 = r_1 + \frac{R r_5}{R + r_5} = r$ (Fig. 8, g). The total resistance of the circuit is

$$\frac{R_1 r_4}{R_1 + r_4} = \frac{r}{2}.$$
