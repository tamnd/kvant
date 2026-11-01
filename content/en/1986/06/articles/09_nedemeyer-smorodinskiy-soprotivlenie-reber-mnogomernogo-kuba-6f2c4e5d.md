---
id: 1986-6-nedemeyer-smorodinskiy-soprotivlenie-reber-mnogomernogo-kuba-6f2c4e5d
issue: kvant_1986_6
year: 1986
number: "6"
title: Resistance of the edges of a multidimensional cube
authors:
  - Недемейер Ф.
  - Смородинский Я. А.
rubric: raznoe
page_first: 24
page_last: 26
page_labels: 22-24
tag: SLAJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: d69fbe3164b9e6e4bc20e66cc4d8727847d06ac80579e61faed2265af9671c6d
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/09_nedemeyer-smorodinskiy-soprotivlenie-reber-mnogomernogo-kuba-6f2c4e5d.md
source_content_sha256: 97356178e9b83a0a9924e7470899a365cd10dc11a4bd61f5a304b6ddfcc070e2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

gets angry - is it conceivable to carry out such an account?

Meanwhile, beautiful geometric and algebraic patterns are hidden in these problems (it is not for nothing that this seemingly physical problem is considered in mathematical circles), which allows them to be solved without any “numbing calculations”, as well as to generalize them in an unexpected way.

The case of three-dimensional and four-dimensional cubes

Let's start with an obvious geometric observation: the pattern on figure 1 is the pattern of the edges of a general cube (compare figure 1 and 3, a). As a model of our cube, consider a standard single cube in the coordinate system $Oxyz$, associating the points $O$ and $I$ with the vertices (0; 0; 0) and (1; 1; 1), implying the presence of a resistance of 1 Ohm on all edges of the cube. Note that the coordinates of the vertices of the cube (and only the coordinates of these 6 points) will consist of only zeros and ones. Let us define the sum of the coordinates of any vertex by its $p$ang. If a potential is created between points $O$ and $I$, then the potential of vertices of the same rank is the same (this is very much a symmetry message). Therefore, it is possible, without changing the resistance of the circuit, to short-circuit vertices of the same rank, obtaining a circuit consisting of three consecutive groups of parallel resistances (Fig. 4). For such a circuit, the problem is solved orally (see Fig. 4): resistance $R_3$ is equal to 5/6 Ohms.

To calculate the resistance of the second circuit (see Fig. 2), we note that this circuit is a circuit of the edges of a four-dimensional cube *). This is a less obvious geometric observation. The reader can produce it by comparing figure 2 with figure 7 on p. 6. Next, the calculation is performed in exactly the same way as in the case of a regular cube. The calculation (shown at figure5) takes advantage of the fact that the vertices of the same rank have the same potential and can therefore be short-circuited (without changing the total resistance between points $O$ and $I$). The answer is: $R_4 = 2/3$ Ohm.

Problem 1. Calculate the resistance of the edges $R_5$ of a five-dimensional cube between its diametrically opposite vertices, provided that the resistance of each edge is 1 Ohm.

Resistance of the edges of a $n$-dimensional cube

The problem of the resistance of the edges of a cube can be generalized further by considering cubes of dimension $n=5, 6, 7, 8$, etc. This can be done according to the same scheme as for $n=2, 3, 4$, however, we will not have the right to consider ourselves mathematicians if we cannot immediately manage the resistance of a $R_n$ $n$-dimensional cube between its opposite vertices for any $n$ (definition $n$-cube, see p. 7).

The reader may ask whether such a formulation of the problem is legitimate, since a $n$-dimensional cube for $n>3$ is only

*) You can get acquainted with the concept of a four-dimensional cube in the article by S.V. Duzhin and V.N. Rubtsov in this issue «Kvant».

⟦folio 23⟧

Rank 0 1 2 Σ

Number of vertices 1 + 2 + 1 = 4
Number of edges 2 + 2 = 4
Scheme
Resistances 1/2 + 1/2 = 1

Rank 0 1 2 3 Σ

Number of vertices 1 + 3 + 3 + 1 = 8
Number of edges 3 + 6 + 3 = 12
Scheme
Resistances 1/3 + 1/6 + 1/3 = 5/6

Fig. 4.

Rank 0 1 2 3 Σ

Number of vertices 1 + 4 + 6 + 4 + 1 = 16
Number of edges 4 + 12 + 12 + 4 = 32
Scheme
Resistances 1/4 + 1/12 + 1/12 + 1/4 = 2/3

Fig. 5.

Fig. 6.

Rank 0 1 2 ... k - 1 k ... n - 1 n

Number of vertices 1 + n + $\frac{n(n-1)}{2}$ + ... + $C_n^k$ + ... + n + 1 = $2^n$

Number of edges n + n(n-1) + ... + (n-k) $C_n^k$ + ... + n = ?

Resistances $\frac{1}{n}$ + $\frac{1}{n(n-1)}$ + ... + $\frac{1}{n C_{n-1}^k}$ + ... + $\frac{1}{n}$ = ?

⟦folio 24⟧

a mathematical abstraction, it does not “really” exist, so it is unclear what the point of calculating the resistance of its ribs is. We answer. There is a meaning, the task set is a very real physical task. The point is that although the $n$-cube itself with $n > 3$ cannot be placed in three-dimensional space, the diagram of its edges can easily be placed in ordinary space. So, on figure 2 (or 5) you can see how this is done for a four-dimensional cube, and the magazine cover even shows a diagram of the edges of an eight-dimensional cube! In the general case ($n$ - any) the mapping of the edges of a $n$-cube into three-dimensional space is a simple mathematical theorem, the proof of which we will not dwell on.

It is interesting to note that the pattern of edges of a three-dimensional cube can be placed on a plane without self-intersections (see Fig. 1), however, it has been proven (this is already a difficult theorem) that the pattern of edges of a four-dimensional (and in general $n$-dimensional for $n \geq 4$) cube cannot be placed on a plane without self-intersections.

As the reader has probably agreed, $R_n$ is counted in the same way as $R_3$ and $R_4$. You can follow him using figure 6. The answer is:

$$R_n = \sum_{k=0}^{n-1} \frac{1}{(n-k)C_k^n},$$

where $C_k^n$ is the binomial coefficient (see «Kvant», 1986, No. 1, p. 23).

When counting, we take advantage of the fact that vertices of the same rank have the same potential, and therefore all the properties of counting the number of edges connecting vertices of neighboring ranks. It is clear that the number of vertices of rank $k$ is equal to $C_k^n$ (their column, how many ways does $k$ have digits 1 in $n$ places), and the number of edges emanating from each vertex of rank $k$ is $n-k$ (why?); This means that the number of edges with vertices of $k$ and $(k+1)$ rank is $(n-k)C_k^n$. These edges can be considered parallel connected, so we get (1).

Tasks

2. Check that $(n-k)C_k^n = nC_{n-1}^k$, thereby justifying the correspondence.

$$R_n = \frac{1}{n} \sum_{k=0}^{n-1} \frac{1}{C_{n-1}^k}.$$

3. Using formula (2), prove that

$$R_n = \sum_{k=0}^{n-1} \frac{1}{(n-k)2^k}.$$

4. Establish a recurrence relation

$$R_n = \frac{1}{n} + \frac{1}{2} R_{n-1}$$

algebraic (using formula (3)) and geometric. Check our calculations of $R_3, R_4, R_5$ based on this ratio and the $R_1 = R_2 = 1$ equalities.

Other generalizations

The counting methods proposed here can be applied to other problems, for example this one:

Problem 5. Calculate the resistance of a three-dimensional cube between adjacent vertices, provided that the resistance of each edge is 1 ohm. Generalize to any $n$.

It is more interesting to change not the application points of the meter, but the configuration of the circuit under consideration. Our reasoning remains valid for any circuit in which the same number of edges (resistance of 1 ohm) is connected to each node.

Problem 6. Show that the resistance between adjacent nodes of a circuit of $m$ nodes, each of which contains $s$ resistances of 1 ohm, is equal to

$$R = \frac{2}{s} \left(1 - \frac{1}{m}\right).$$

For example, for an infinite two-dimensional square grid the simple answer is $R = 1/2$ ($s = 4, m = \infty$). For a mesh of trigons ($s = 6, m = \infty$) $R = 1/3$, for a mesh of hexagons ($s = 3, m = \infty$) $R = 2/3$, for a tetrahedron ($s = 3, m = 4$) $R = 1/2$. For a $n$-cube we get ($s = n, m = 2^n$):

$$R = \frac{2}{n} \left(1 - \frac{1}{2^n}\right).$$

Even more interesting (but, alas, not elementary!) is the problem of calculating the resistance between diagonally adjacent nodes of an infinite square grid of resistances of 1 ohm. The answer turns out to be $2/\pi$ Ohm, although there is not a hint of a circle in the diagram!
