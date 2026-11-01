---
id: 1987-2-sosinskiy-konechnyie-gruppyi-40408c65
issue: kvant_1987_2
year: 1987
number: "2"
title: Finite groups
authors:
  - Сосинский А. Б.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8, 10
tag: 49L1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2c5a01e34c60d99b7c0388ddba0484a62f9e1e4090c92ca259272c8329124eae
prompt_sha256: draft-1
translated_from: content/ru/1987/02/articles/02_sosinskiy-konechnyie-gruppyi-40408c65.md
source_content_sha256: fa983dd53c9bc7516f39a409aab562c63d76ae0477ad730b3e4b75315da60166
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

FINITE GROUPS

Candidate of Physical and Mathematical Sciences
A. V. SOSINSKY

The concept of a group, in particular a finite group, is one of the most important concepts in mathematics. And at the same time, one of the most common and most useful for applications.

Without finite groups, it is impossible, for example, to indicate which algebraic equations are solvable in radicals and which are not, to describe how crystals are structured, or to create error-correcting codes. However, we will not talk about this here, but will limit ourselves to the simplest examples of finite groups.

Illustrations: Action Groups

A non-empty set of some actions that can be performed sequentially is called a group if this set necessarily contains its inverse for each action, and the result of sequential execution of any two actions is also an action from this set.

As an illustration, let’s consider the actions of a delivery officer executing drill commands (Fig. 1). These action chains form groups $R(\square) = \{C, \Pi, J, K\}$. Thus, the result of sequential execution of actions P and K (to the right and steeply) will coincide with the result of action L (to the left); this is written as $K \cdot \Pi = J$. Likewise $J \cdot \Pi = \Pi \cdot J = K \cdot K = C$. The remaining correspondences in the group can be extracted from its multiplication table shown in figure 1. A special role is played here by the action C, which can be called “nothing week”. (Such an action is sure to exist in any group: we get it by performing an arbitrary action, and then the reverse to it). Our actions P and L are inverse to each other, the action K is inverse to itself, etc.

Let's consider another group, also consisting of repetitions. Namely, a group of repetitions of a five-pointed star $\Pi(\star)$ relative to its center (Fig. 2). “No-division” (in this case, the repeat on $0^\circ$) is denoted by $R_0$, and the remaining repeats (on $72^\circ, 144^\circ, 216^\circ, 288^\circ$) by $R_1, R_2, R_3, R_4$. Here $R_2 \cdot R_1 = R_1 \cdot R_2 = R_3$,

Fig. 2.

$R_3 \cdot R_3 = R_1, R_1 \cdot R_4 = R_0$ (the latter means $R_4$ back to $R_1$), etc. The set $\Pi(\star) = \{R_0, R_1, R_2, R_3, R_4\}; \circ$ forms a group.

Finally, consider the “putting on a sock group” (Fig. 3), consisting of the following actions:

$O = \text{Оставь, как есть}$,
$\Pi = \text{Сними и надень на другую ногу}$,
$B = \text{Сними, выверни и надень на ту же ногу}$,
$\Pi' = \text{Сними, выверни и надень на другую ногу}$.

Does nothing here - this is $O$, then $\Pi \cdot B = \Pi', \Pi \cdot B = \Pi' \cdot \Pi' = 0, \Pi' \cdot \Pi = B$, etc.

The group $H = \{O, \Pi, B, \Pi'; \circ\}$ is again obtained, consisting, like $R(\square)$, of four actions. Groups $H$ and $R(\square)$, however, are considered different: their multiplication tables differ not only in the designation of elements, but also in their structure. Thus, along the diagonal of the multiplication table $H$ there is the same action $O$, while on this diagonal $y R(\square)$ there are different elements.

I suspect that the most server-oriented readers are becoming increasingly aware of some kind of training, putting on socks - what nonsense, too, it’s not all scientific! I hasten to object: scientifically, even very much so. Do you know what a set of surrender actions is actually called? A cyclic group of 4th order or a residue group modulo 4. And our “toe-on” group is a Klein group. The rotations of a star are one of the so-called simple finite groups, about which an entire article was written in this issue of Kvanat (see p. 2), and thousands of articles in other journals.

⟦folio 10⟧

Trupla $Z_{12} = \{R^{25/12} = £, £^2, £^3, \dots, £^{10}, £^{11}, £^{12} = e\}$
1 second order element: $\{Z_6, e\} \cong Z_2$
2nd order element: $\{Z^4, Z^8, e\} \cong Z_3$
2nd element IV order: $\{Z^3, Z^6, Z^9, e\} \cong Z_4$
2nd element VII order: $\{Z^2, Z^4, Z^6, Z^8, Z^{10}, e\} \cong Z_6$
4th element XII order: $Z, Z^5, Z^7, Z^{11}$

Trupla $S_4 = \{(1 2 3 4)_{i_1 i_2 i_3 i_4} : \text{всего } 4! = 24\text{ перест.}\}$
Yadels II order $A_4 = e$
Yadels III order $B_4 = e$
Bdeli II order $(2341), (3412), (4123), e \cong Z_4$
$(2431), (4312), (3124), e \cong Z_4$
$\{(12), (34), (12), (34), e\} \cong K$ (gr. Zilina)
$\{(12, 34), (12), (34), e\} \cong S_3 \cong S(\Delta)$

Trupla $S_5 = \{(1 2 3 4 5)_{i_1 i_2 i_3 i_4} : i_n \in \{1, 2, 3\} \cong S_3 \cong S(\Delta)\}$
There are elements of orders II, III, IV, V, VII;
committed element of order VII: $(1 2 3 4 5)_{2 1 4 5 3}$.
There are subgroups identical to $Z_2, Z_3, Z_4, Z_5, Z_6$.
There are subgroups identical to $S_3, S_4, u.K.$
There are subgroups, identines $A_4$ ($12^{20}$ order).
There is a single subgroup $A_5$ of order 60.
