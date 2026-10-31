---
id: 1976-1-ovchinnikov-ploskie-pereklyuchatelnyie-shemyi-093defef
issue: kvant_1976_1
year: 1976
number: "1"
title: Flat switching circuits
authors:
  - Овчинников С. В.
rubric: osnovnye-stati
page_first: 14
page_last: 19
page_labels: 12-17
tag: AO43
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6d3eea0b2c398e12009f9c2df13fe91632975d2518405059a200ebcf493ccc04
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/03_ovchinnikov-ploskie-pereklyuchatelnyie-shemyi-093defef.md
source_content_sha256: e8dbfdbdb32362c30ea7f43c23c2662c9195a96515436879e3e3ccbae8c36976
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

S. Ovchinnikov

Flat switching circuits

What a switching circuit is can be easily understood from figure 1. There are two groups of $n$ poles - a group of inputs and a group of outputs (at Fig. 1 $n = 4$). Each input lane is connected to one and only one output lane. Readers familiar with the concept of *graph* may notice that a switching circuit is a special kind of graph. Such graphs are called *sevens*.

When creating technical devices that use switching circuits, it is required that the intersecting connections be isolated from each other. In conventional devices, the connections are made by wires, and therefore this requirement is easily satisfied. An example of such a device is a switching circuit,

Fig. 1.

Fig. 2.

⟦folio 13⟧

shows a circuit that implements the symmetry of $n$ numbers: the $i$-th input is connected to the $(n-i+1)$-th output. This circuit requires a $n$ layer, since each bond pair must lie in different layers.

Let us now formulate strictly the conditions of the problem and prove the main theorem.

Let us be given a switching circuit with $n$ inputs and $n$ outputs; numerate them with integers 1, 2, ..., $n$. Each such scheme defines a one-to-one mapping onto itself of the set of numbers $\{1, 2, ..., n\}$; in other words, the circuit specifies a permutation $P$ set of numbers $\{1, 2, ..., n\}$, which matches the number of the input to the number of the output connected to it. For example, the switch circuit at figure 1 corresponds to the permutation $1 \rightarrow 2, 2 \rightarrow 4, 3 \rightarrow 1, 4 \rightarrow 3$. It is obvious that each permutation, in turn, corresponds to a certain switching circuit. Therefore, in what follows we will not distinguish between switching circuits and their corresponding permutations.

The number $n$ is called the power of the permutation $P$. The connection connecting the input $i$ with the output $j$ will be denoted by $(i, j)$. Then the permutation $P$ can be defined as the set $\{(i, j)\}$ of all connections.

Let's look at some examples. The circuit on figure 1 corresponds to a permutation of degree 4, which can be written as a set of connections:

$$P_1 = \{(3, 1), (1, 2), (4, 3), (2, 4)\}.$$

Permutations of degree $n$, corresponding to the schemes in Figures 3 and 4, are written as follows:

$$P_2 = \{(1, 1), (2, 2), ..., (n, n)\},$$
$$P_3 = \{(n, 1), (n-1, 2), ..., (1, n)\}.$$

Problem 1. Prove that two connections $(i, j)$ and $(p, q)$ intersect if and only if $(i-p)(j-q) < 0$.

A subset of links is called a “permutation layer $P$” if no two links from this subset intersect. figure2 shows two layers of the permutation $P_1$. The permutation $P_2$ is itself a layer, and for the permutation $P_3$ each layer consists of exactly one connection.

The thickness of a permutation $P$ is the minimum number of layers on which it can be expanded. In our examples, the thickness of $P_1$ is 2, the thickness of $P_2$ is 1, and the thickness of $P_3$ is $n$. Obviously, the thickness of any permutation does not exceed its degree $n$.

Problem 2. Prove that for any integer $p \leq n$ there is a permutation $P$ of degree $n$ and thickness $p$.

Permutations of thickness 2 are called 2-realizable (they can be decomposed smoothly into two layers) and have the following properties. We place the connection $(i, j)$ on the right if $i \geq j$, and on the left if $i < j$ (at figure 5 a permutation is depicted, the right connections of which are highlighted in red, and the left ones are highlighted in blue). It turns out that the set of all left connections of a 2-realizable permutation is a layer. (Prove it.)

For example, the permutation on figure 5 is not 2-realizable: its left

⟦folio 14⟧

Fig. 5.

connections (2, 5) and (3, 4) intersect. Opposite in meaning to the concept of a layer is the concept of a sheaf. A subset of links is called a bundle if any two links from this subset intersect. The thickness of a bundle is the number of bonds included in it. We will consider each link to be a beam of thickness 1.

Let's return to our examples. The permutation $P_1$ (see Fig. 1) has three pencils of thickness 2:
$\{(3, 1), (1, 2)\}, \{(3, 1), (2, 4)\}$ and $\{(4, 3), (2, 4)\}$.

All sheaves of the permutation $P_2$ (Fig. 2) have thickness 1. For the permutation $P_3$ (Fig. 3) any subset of the link is a sheaf. In particular, the permutation $P_3$ itself is a sheaf.

Among the beams of this permutation, the beams of maximum thickness are of particular interest. We call such bundles maximal.

Problem 3. Prove that the maximal sheaf of an arbitrary permutation cannot consist only of its left connections.

There is an obvious relationship between the thickness of a permutation and the thickness of its maximum beam: the thicker the beams a permutation has, the thicker it is. The following theorem specifies this dependence.

Theorem 1. The thickness of a permutation is equal to the thickness of its maximal pencil.

Since a link from a maximal bundle must lie in different layers, the number of words cannot be

less than the beam thickness. Therefore, to prove the theorem, it is enough to construct a decomposition of a given permutation whose number of words is equal to the number of links in the maximal pencil. In other words, each layer of such a decomposition must contain exactly one connection from the maximal bundle.

Before proving Theorem 1, let us establish one important property of a maximal pencil.

Lemma. Let
$(i_1, j_1), (i_2, j_2), \dots, (i_p, j_p)$
— connections included in the maximal bundle, and
$j_1 < j_2 < \dots < j_p$.

If some connection $(i, j)$ intersects the connection $(i_1, j_1)$, then $i < i_1$.

Proof. Assuming the opposite, from the result of Problem 1 we obtain that $j < j_1$. But then the link $(i, j)$ intersects all links of the Dann bundle, and this contradicts its maximal one.

We will say that connecting $(i, j)$ begins in the full $j$. then the proven geometric property means that any connection starting to the left of the maximal pencil does not intersect its leftmost connection. Similarly, any link starting to the right of a maximal pencil does not intersect its rightmost link. Rearranging to figure 6 or will construct our lemma. Marked in red are the connections of the maximum beam. (1, 5) is the rightmost connection of the maximal bundle, (4, 2) is the leftmost one. Note, by the way, that there can be several maximal sheaves. To rearrange to Fig.

⟦folio 15⟧

Sunka 6 there are three of them:
{(4, 2), (3, 4), (1, 5)}, {(7, 3), (3, 4), (1, 5)} and {(7, 3), (6, 6), (5, 7)}.

Proof of Theorem 1.

We give a constructive proof, that is, we indicate a process by which each permutation can be decomposed into a minimum number of words.

Let us denote only the inn of the maximal pencil by $p$. Let us assign the connection $(u_1, 1)$ (that is, the leftmost connection of the permutation) to the first layer and denote it $(u_1, v_1)$. Among all the connections $(i, j)$ that do not intersect $(u_1, v_1)$, consider the connection with the most shimmy $j$. Its own $(u_2, v_2)$ and is also included in the first layer. By sorting through the connections in a row, starting from the leftmost one, and assigning to the first layer those that do not intersect the already selected ones, we obtain a set of pairwise disjoint connections $(u_1, v_1), (u_2, v_2), \dots, (u_h, v_h)$, which form the first layer.

The connections that are not included in the first layer themselves form a certain permutation. Applying the previous construction to this permutation, we get the second layer and so on.

Let us see what happens to the maximum beam during this construction. Let us denote the connections included in this bundle by $(i_1, j_1), (i_2, j_2), \dots, (i_p, j_p), j_1 < j_2 < \dots < j_p$. According to the lemma, the connection $(i_1, j_1)$ does not intersect with any connection starting to its left, and therefore must fall into the first layer. No other connections from this maximal bundle will fall into the first layer, since they intersect the connection $(i_1, j_1)$. Therefore, from each maximal bundle, one connection will fall into the first layer.

Let's select the first layer from our permutation. It is easy to see that in the remaining permutation the maximal sheaves have only $p-1$. By selecting the second layer, we obtain only $p-2$ maximal sheaves in the remaining permutation. Continuing this process of word selection, at the $(p-1)$th step we obtain a permutation whose maximal bundles have only 1. But this means that the connections in this permutation do not intersect, and, therefore, it itself forms the last $p$th layer.

So, we have shown that any permutation can be decomposed into layers, the number of which is equal to only the maximum sheaf; This expansion proves the theorem.

Strengthening. Check the validity of the theorem for $P_1, P_2$ and $P_3$.

Let us consider switching circuits corresponding to permutations only 2, that is, 2-realizable permutations; they are of particular interest because they require only two conductive layers to be produced. Let two such switching circuits be connected as shown in figure 7. Obviously, the resulting circuit in figure 7 is equivalent to the switching circuit in figure 8. Let us denote the permutation corresponding to circuit figure 8 by $P$, and the permutations corresponding to the upper and lower circuits figure 7 by $P_1$ and $P_2$ corresponding. We will say that the permutation $P$ is equal to the product of the permutations $P_1 \cdot P_2$.

In a similar way, you can define the product of any number of permutations. The order of the factors in such a product is important: for example, if we take the permutation

⟦folio 16⟧

It turns out that any permutation can be decomposed into a product of several 2-realizable ones! (Prove it.)

If a permutation is represented as a product of s “pieces” of 2-realizable permutations, then it is said to be s-cascade realizable. (Thus, the permutation P (thickness 3) depicted in figure 8 is 2-cascade realizable; the decomposition of P into 2 cascades of 2-realizable permutations is carried out by the permutations P₁ and P₂ figure 7.) Technologies s-cascade realizable permutation has two conducting layers and one insulating, interchanged s - 1 time. The first layer of the insulating layer corresponds to the gap between the cascades; It is obvious that in the rupture of the insulating layer, no intersection of bonds will occur. Each insulating layer corresponds to a break in the 2-implementable) passes through each stage, but perhaps in different wires of the layer - see figure 10; connections lying in the same conductive layer are indicated by the same color.

So, as we said, for any permutation a cascade decomposition exists. What is the minimum number of cascades required for the cascade decomposition of a given permutation? Let's try to find out.

Let's start with the permutation Kₚ, which corresponds to the number i with the number p - i + 1, that is, realizing the symmetry of p numbers.

As already noted, the permutation Kₚ coincides with its maximal sheaf and only has the same value as p. Now we will construct some cascade decomposition of the permutation Kₚ into two-layer permutations and then show that the constructed decomposition is minimal.

For p = 2, the permutation K₂ is itself a cascade (unit). How to decompose the permutation K₄ (p = 4) can be seen from figure 11. Using the idea of ​​cascade decomposition

⟦folio 17⟧

For the permutation $K_4$, we construct a cascade decomposition of the permutation $K_8$ ($p = 8$) - see figure 12. Now it is clear how to construct a cascade decomposition of the permutation $K_p$ if $p$ is equal to a power of two. The upper cascade (for $p = 2^r$) is depicted at figure 13. The remaining cascades symmetrically implement the permutations of positives 1, 2, ..., $2^{r-1}$ and positives $2^{r-1} + 1$, $2^{r-1} + 2$, ..., $2^r$; in this case, the $k$-th cascade of permutation of degree $2^r$ is obtained by combining two identical ($k-1$)-th cascades of permutation of degree $2^{r-1}$. Obviously, the number of cascades in the constructed cascade decomposition of the permutation $K_2^r$ is equal to $r$.

Let now $p$ not be a power of two; then there exists $r$ such that $2^r < p < 2^{r+1}$. Let us consider the cascade decomposition of the permutation $K_{2r+1}$ of degree $2^{r+1}$ and see in it connections starting at positions with numbers not exceeding $p$. Obviously, these connections define the permutation $K_p$ (inputs with numbers $2^{r+1} - p + 1$, $2^{r+1} - p + 2$, ..., $2^{r+1}$ need to be re-ordered, starting with ones: 1, 2, ... $p$), and this cascade decomposition of the permutation $K_{2r+1}$ also carries out the decomposition of the permutation $K_p$. For example, on figure 14 the cascade expansion for the permutation $K_6$ is separated from the expansion for $K_8$.

So, for permutations $K_p$, which are sheaves, we have constructed cascade expansions. If $p$ is such that $2^{r-1} < p \leq 2^r$, then the number of stages is $r$. Otherwise, it can be written like this: $r = \log_2 p$, where $|a|$ denotes the smallest integer, not less than $a$.

Let us now show that the constructed cascade expansions of the permutations $K_p$ consist of a minimum number of cascades. For this example, index by $p$. Note that if $p < q$, then the minimal cascade decomposition of a permutation of degree $q$ requires no fewer cascades than the minimal decomposition of a permutation of degree $p$.

For $p = 2$ our statement is obvious. Let the statement be proven for $p = k$. Let's consider two cases.

a) $2^{r-1} < k < 2^r$.

For a permutation $K_k$ of degree $k$ we have a $r$-cascade decomposition. When moving from $k$ and $k+1$, the number of cascades, as follows from our remark, does not decrease. But since $k$ is an integer, then $k+1 \leq 2^r$, and therefore we can construct a $r$-cascade expansion of the permutation $K_{k+1}$ of degree $k+1$; It is now clear that it is the minimum.

b) $k = 2^r$.

 Let's consider the permutation $K_{k+1} = K_{2r+1}$. Since $2^{r+1} < 2^{r+1}$, we can construct a $(r+1)$-cascade decomposition for the permutation $K_{k+1}$. Let us show that $r$ cascades are not enough to decompose the permutation $K_{k+1}$ (then the $(r+1)$-cascade decomposition will be the minimal one).

Let us assume the opposite: let there be a $r$-cascade decomposition of the permutation $K_{2r+1}$ of degree $2^{r+1}$. Let's consider the upper cascade of this time-
