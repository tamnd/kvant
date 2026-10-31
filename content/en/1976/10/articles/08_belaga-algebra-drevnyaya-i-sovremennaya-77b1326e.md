---
id: 1976-10-belaga-algebra-drevnyaya-i-sovremennaya-77b1326e
issue: kvant_1976_10
year: 1976
number: "10"
title: Algebra - ancient and modern
authors:
  - Белага Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 32
page_labels: 24, 25, 26, 27, 28, 30
tag: 9G9S
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4430d790cd792cdeb20146704ff781a33dd08aea0d091772acb41b26d19b91c1
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/08_belaga-algebra-drevnyaya-i-sovremennaya-77b1326e.md
source_content_sha256: 2edcfd12177bb775a1c54f503bbb70adb9b3dbdcf880af3d3e3e8f231947efd2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

E. Belaga
ALGEBRA -
ANCIENT
AND MODERN

You have already read the articles by A. Kolmogorov “Transformation Groups” and L. Sadovsky and M. Arshinov “Groups”, in which the concepts of a binary operation and a group are introduced. To attract attention to these concepts that are new to you, you need to look at several examples “with a pencil in your hand.” The article below will help you with this. It talks about the multiplication of words, self-combinations of regular polyhedra, knots and substitutions, and the application of abstract theory to solving specific problems. An attentive and patient reader will be able to independently deduce many replacement properties of operations on these objects, breaking down the conditions and finding solutions to problems (they serve as a continuation of the main text). The most interesting and, as a rule, quite difficult tasks are marked with an asterisk.

I. EVERYTHING ELSE IS THE WORK OF HUMAN HANDS...

Among primitive tribes, the names of numbers were inseparable from the names of the items being listed. Not “two” or “tri”, but only “two rivers” or “three warriors”. With the advent of the abstract concept of number, mathematics was born. Perhaps this is why the outstanding German mathematician Leopold Kronecker once uttered his phrase, which was as paradoxical as it was famous: “God created the integer, everything else is the work of man.”
It took several thousand for a person to learn, for a person to learn problems in the form of formulas. Then letters appeared in these formulas instead of numbers. The new “literal” arithmetic began to be called algebra. And then algebraic symbols and algebraic operations were extended to a wide variety of objects of non-arithmetic nature - substitutions, matrices, geometric transformations, etc., and the number line (or complex plane) turned out to be just one of many, many algebraic structures studied in the new algebra.

II. ABOUT “THINGS” THAT CAN BE “MULTIPLIED” AND SOMETIMES DIVIDED, ALTHOUGH THEY ARE NOT NUMBERS

We are taught very early that numbers can be added, multiplied, subtracted and divided. It’s surprising—and you also need to get used to this—that you can “add” (or “multiply”) even “things” that are not of a numerical nature.

Example one: words
We will call any collection of symbols an alphabet. We will limit ourselves to finite alphabets (in algebra and mathematical logic of the Polish

⟦folio 25⟧

are also infinite). Here are two examples of alphabets:

$A_1$. An alphabet consisting of two Greek letters: α and β.

$A_2$. Argumentative alphabet: numbers from 0 to 9, argumentative symbols, equal sign and parentheses:

$$\{0, 1, 2, 3, 4, 5, 6, 7, 8, 9, +, -, :, \times, =, ),\}$$.

We will call any finite sequence of symbols from $A$ a word above the alphabet $A$. Here are examples of words above the two alphabets described above (to separate the word entry from the surrounding text, we “pack” it in angle brackets):

$$(A_1): \langle \alpha\beta \rangle, \langle \alpha\beta\alpha\beta \rangle, \langle \rangle;$$
$$(A_2): \langle 1976 \rangle, \langle 2 + 2 = 4 \rangle,$$
$$\langle - \rangle +): \langle 3 \rangle).$$

A word can also be “empty”, that is, not contain any characters at all (the last “word” in the first example), such a word is denoted by the letter $\lambda$: $\lambda = \langle \rangle$. We denote the set of words over a given alphabet $A$ by $C(A)$. We will denote its elements, that is, words, in small Latin letters (they do not belong to the alphabets that we come to consider here).

The product, or composition, of two words $a$ and $b$ from $C(A)$ we will call the word $c$ (and write: $c = a \otimes b$), the resulting word is attributed to the word $a$ to the right of it the words $b$. Here are examples of word combinations:

$$(A_1): a = \langle \alpha \rangle, b = \langle \alpha\beta \rangle,$$
$$c = a \otimes b = \langle \alpha\alpha\beta \rangle;$$
$$(A_2): a = \langle 2 + 2 \rangle, b = \langle 4 \rangle,$$
$$c = a \otimes b = \langle 2 + 2 = 4 \rangle.$$

An empty word does not contain any characters, so $a \otimes \lambda = \lambda \otimes a = a$ for any word $a$ of $C(A)$, that is, the empty word $\lambda$, when rearranging words, behaves like a unit when rearranging numbers.

If we continue to search for similarities and differences between multiplying words and multiplying numbers, we will notice that the operation “⊗” is associative:

$$(a \otimes b) \otimes c = a \otimes (b \otimes c),$$

In other words, the notation $a \otimes b \otimes c$ makes sense.

Problem 1. For any word $a$ from $C(A)$ we determine its non-negative powers by putting $a^0 = \lambda$, $a^1 = a$, $a^2 = a \otimes a$, and in general $a^{n+1} = a \otimes a^n$. Prove that for any non-negative integers the equality

$$a^m \otimes a^n = a^{m+n}.$$

The equality after it allows us to abbreviate the notation of non-negative words: together $a = \langle \alpha \rangle^3 \otimes \langle \beta \rangle^3 \otimes \langle \alpha \rangle^4$ or, allowing non-negative waviness of the notation, $a = \langle \alpha^3\beta^3\alpha^4 \rangle$. But changing the order of letters into words, generally speaking, cannot be said “⊗” may not be commutative, that is, $a \otimes b$ may not coincide with $b \otimes a$.

Problem 2. a) Over which alphabet is the operation “⊗” commutative, that is, for any words $a$ and $b$ there will be $a \otimes b = b \otimes a$?

6)* How should two words $a$ and $b$ be arranged over an alphabet $A$ containing two or more characters so that the composition of these words does not depend on their order?

Example two: self-alignment

As is known, congruity (they used to say “equality”) of figures and bodies in geometry is established by change: if there is a movement of the plane (or space), in which one figure is mapped onto another, then these figures are congrugis. A movement in which the value is non-negative on itself will be called self-alignment.

For a cube, for example, there are only 48 different self-alignments. Indeed, let's paint one face of the cube and mark the direction on one of the edges bounding this face (Fig. 1). Then the self-alignment of the cube is determined by which face of the cube the colored face is mapped to, which edge of this face the marked edge goes to, and which end of this edge the arrow is directed to (from these data it is uniquely determined

⟦folio 26⟧

Fig. 1.
The position of the cube is divided). A cube has 6 faces, each face has 4 edges, each edge has 2 ends, a total of $6 \times 4 \times 2 = 48$ ways.

The product $c = a \circ b$ of the self-alignments $a$ and $b$ of the regular polyhedron $\Delta$ is defined as the general composition of displacements: first $b$ is performed and then $a^*$). Check that $(a \circ b) \circ c = a \circ (b \circ c)$ for any three self-alignments $a, b, c$ from the set $\Gamma (\Delta)$ of all self-alignments of the body $\Delta$ (associativity; compare with the description of the group on p. 8 and the axim of group III there).

Task 3. Prove that the sequential execution of two rotations of the cube: first around the axis $AB$ (Fig. 2) by an angle $90^\circ$, and then around the axis $CD$ by an angle $120^\circ$, can be written as one rotation around the axis $EF$ by $180^\circ$, which is the product of two rotations. Does this product depend on the order in which the turns are performed?

*) This recording order is convenient in that the image $(a \circ b)(M)$ of the point $M$ when mapped $a \circ b$ will be $a(b(M))$.

Fig. 2.
Task 4. Prove that there are only four different self-alignments of the rectilinear in space (Fig. 3): identical $e$, rotation $a$ around $AB$, $b$ – around $CD$, $c$ – around $EF$, and $a^2 = b^2 = c^2 = e$, $a \circ b = b \circ a = c$, $b \circ c = c \circ b = a$, $a \circ c = c \circ a = b$.

The last equality of problem 4 can be written in the form of the following multiplication table:

| $e$ | $a$ | $b$ | $c$ |
| :--- | :--- | :--- | :--- |
| $e$ | $e$ | $a$ | $b$ |
| $a$ | $a$ | $e$ | $c$ |
| $b$ | $b$ | $c$ | $e$ |
| $c$ | $c$ | $b$ | $a$ |

It is obvious that any self-alignment $a$ of a figure or body $\Delta$ corresponds to a single “inverse” $a^{-1}$, returning the body to its initial position ($a^{-1}$ may coincide with $a$, as in task 4). Moreover, if $a^{-1}$ is the reverse $a$, then $a$ is the reverse $a^{-1}$:

$a \circ a^{-1} = a^{-1} \circ a = e$.

⟦folio 27⟧

Fig. 5.

Now we can define any integer degree $a^k$ of self-alignment $a$:
$$a^0 = e, a^1 = a, a^2 = a \circ a, \dots, a^{k+1} = a \circ a^k, a^{-k-1} = a^{-1} \circ a^{-k}.$$
It is easy to verify that $a^k \circ a^l = a^{k+l}$ for any $a$ of $\Gamma(\Delta)$ and any integers $k$ and $l$; in particular, $a^k$ and $a^{-k}$ are mutually inverse. (Compare with the description of the group on page 8 and Axiom II.)

Problem 5. Find all self-alignments of a regular terrahedron, octahedron and icosahedron (Fig. 4). Which of them satisfy the equality $a^2 = e$? Equality $a^3 = e$? Equality $a^5 = e$? Make a multiplication table for the self-combinations of the terrahedra and cube.

Problem 6. Prove that any self-alignment of an icosahedron can be obtained by “multiplications” of some two rotations (by $72^\circ$) around two adjacent vertices; more precisely, if we denote these rotations by the letters $a, b$, then any self-alignment of the icosahedron can be written as a product of several self-alignments, each of which is either $a$ or $b$.

Example three: substitutions

Genetics, as the reader probably knows, began with peas. Group theory began with substitutions - they were the first “non-numerical” object and tool of the new algebra for Joseph-Louis Lagrange, Paolo Ruffini and Evariste Galya.

The main property of substitution is to rearrange or swap numbers or letters from a certain sequence. figure 5 shows substitutions of letters in anagram words, changing the meaning of these words; The general “two-story” numerical records of these substitutions are written nearby.

Substitutions are discussed in the article “Groups”; we just recall that two substitutions $b, a$ of the same set of elements, performed one after the other, give the required substitution $c = a \circ b$, called their product. Figure6 illustrates this brief definition. The set of all permutations of the set $(1, 2, 3, \dots, n)$ will process a group called the "symmetric group of degree $n$" and denoted by $S_n$. This group contains $n!$ substitutions.

Problem 7. Let $a$ be some substitution. Prove that if $k$ is the smallest positive integer for which $a^k = e$, then the equality $a^l = e$ implies that $k$ divides $l$. Next, prove that $k$ divides $n!$ and does not exceed $3^{n/3}$).

Problem 8*. Prove that any substitution from $S_n$ can be obtained by sequentially performing some

*)This problem has already been proposed to the reader «Kvant» (see «Kvant», 1975, No. 11, M355, and also «Kvant», 1976, No. 8, p. 39).

Fig. 6.

⟦folio 28⟧

Fig. 7.
Fig. 8.

Numbers (and in appropriate order) of substitutions
$$\begin{pmatrix}
1 & 2 & 3 & \dots & n-1 & n \\
2 & 3 & 4 & \dots & n & 1 \\
\end{pmatrix}
$$
And
$$\begin{pmatrix}
1 & 2 & 3 & \dots & n \\
2 & 1 & 3 & \dots & n \\
\end{pmatrix}.$$

Example four and last: nodes
A node is a closed spatial curve that does not have a self-intersection point. Knots are studied in topology, but algebraic methods play a decisive role both in the description of individual nodes and in the study of the set $Y$ of all nodes. We will look at the properties of node composition here. The definition of the composition $c = a \# b$ of two nodes $a$ and $b$ is clear from figure 7.

Problem 9. Prove that composition is an associative and commutative (which is somewhat unexpected) operation. Which node plays the role of one in this?

Three more remarkable properties of the knot composition operation can be proven.

a) Any “non-unit” (that is, not untied without breaks) knot is irreversible. In other words: you cannot untie a knot by tying another one next to it; or another way: nodes can be multiplied, but not divided by each other.

6) There are “simple” ones; they cannot be represented as a product of two other nodes, each of which differs from the “unit” (for example, the nodes $a$, $b$ on figure 7 and $m$, $n$ on figure 8 are simple).

c) Any node is either itself simple, or it is a composition of simple ones, and such a representation is unique. What a striking resemblance to the property of integers!
(Knots are described in detail in «Kvant», 1975, No. 7).

What the algebraist saw in our examples

An algebraist is like a topographer - he looks at mathematical objects “from a bird's eye view” and notices and explores only the most general connections and patterns. But its results are of the most general and universal nature. (Losses are also inevitable, of course, since the topographer is unable to access the beauty of the country’s landscapes, the map of which he compiles using aerial photographs.)

To observe that a table merges dissimilar “things”, such as words, nodes, substitutions and self-combinations, can be expressed in the language of definitions and axioms formulated in the article “Groups” (see pp. 7-8). In each of these examples, a set will arise on which a binary operation is specified. The operation does not always have the opposite, but in all examples this operation is associative. A set with an associative binary operation (axiom of group III) is called a semi-urn. As you can see, the existence of unity and the invertibility of elements (axioms of groups I and II) are not assumed in the semi-urn.

All the examples we have considered are semi-urns, and self-combinations and substitutions even form groups - both axioms I and II are satisfied in them.

The reader is well familiar with the multi-scale $N$ of all natural numbers with the operation of multiplication, the multi-scale of all

⟦folio 30⟧

Around Lagrange's theorem

Without giving a proof of Lagrange's theorem (it can be found in textbooks on group theory), we will illustrate with examples how this theorem “works”.

And illustration 1 (algebraic). If in a finite group $G$ there is an element $g$ whose order $k$ is equal to the order $r(G)$ of the group $G$, then any element $a$ of $G$ is some power of $g: a = g^m$ ($0 \leqslant m \leqslant k-1$). Such a group $G$ is called cyclic; she is always a commutina.

An example of a cyclic group is the group of self-alignments of a regular $n$-gon (see p. 9), in which the element $g$, which “generates” the entire group, is a rotation through the angle $360^\circ/n$.

Problem 11. Prove that in a cyclic group the number of solutions to the equation $x^n = e$ is equal to the largest divisor of the numbers $n$ and $r(G)$.

Problem 12*. Prove that if the order $r(G)$ of a finite group $G$ is a prime number, then the group $G$ is cyclic.

And illustration 2 (geometric). The order of the group $\Gamma(D)$ of self-alignments of the dodecahedron $\Delta$ (the symmetry group of the dodecahedron) is divisible by 30. This fact can be deduced from Lagrange’s theorem without any calculations - simply from the existence of three types of self-alignments of the dodecahedron (see Fig. 9): rotations around the vertex “on one face” (on $120^\circ$), rotations around the middle of the edge at $180^\circ$, and rotations around the center of the face at $72^\circ$. The orders of these elements from the group $\Gamma(D)$ are obviously 3, 2 and 5 respectively, so the order of the group $\Gamma(D)$ is divisible by $3 \cdot 2 \cdot 5 = 30$.

And illustration 3 (arithmetic). Number divisibility problems are often very beautiful; For example, try to prove that the numbers $7^8-1$, $11^8-1$, $13^8-1$, $17^8-1$, $19^8-1$, $23^8-1$, $29^8-1$ are divisible by 30. Once you find the solution, you will be pleased to know that this fact is one of the consequences of Lagrange’s theorem.

Fig. 9.

Let us denote by $\Phi(m)$ the set of natural numbers less than $m$ and coprime with $m$. Let us introduce on the set $\Phi(m)$ the operation "" of multiplication modulo $m: a * b$ equal to the remainder of the division of the common product $a \cdot b$ of the numbers $a$ and $b$ by $m$ (for example, if $m = 30$, then $7 \cdot 17 = 29$, since $7 \cdot 17 = 119 = 3 \cdot 30 + 29$).

Problem 13. Prove that $\Phi(m)$ forms an Abelian group, that is

a) $a * b$ belongs to $\Phi(m)$, and $a * b = b * a$;

b) the number 1 always belongs to $\Phi(m)$, and $a * 1 = a$ for any $a$ of $\Phi(m)$;

b) for any $a$ from $\Phi(m)$ there is a $b$ such that $a * b = 1$.

So, $\Phi(m)$ is a group. Let us denote its order by $\Phi(m)$, then for any $a$ from $\Phi(m)$ there will be $a^{\Phi(m)} = 1$ (Lagrange’s theorem in the second formulation!). Here, raising to the power $\Phi(m)$ is arbitrary in the group $\Phi(m)$, and for general powers of integers this means that $a^{\Phi(m)}$ leaves a remainder of 1 when divided by $m$, that is, that $a^{\Phi(m)} - 1$ is divisible by $m$. If $m = 30$, then $\Phi(m) = \{1, 7, 11, 13, 17, 19, 23, 29\}$, $\varphi(m) = 8$, and we immediately get that the numbers $7^8-1, 11^8-1, \dots$ are divisible by 30.

Topics for Thought

About words. Using the alphabet $A$, let's construct an alphabet $\hat{A}$ of symbols and “antisymbols”: if $A$ includes the symbol $a$, then $\hat{A}$ includes $a$ and $a$.
