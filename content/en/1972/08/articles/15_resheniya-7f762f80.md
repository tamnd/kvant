---
id: 1972-8-resheniya-7f762f80
issue: kvant_1972_8
year: 1972
number: "8"
title: Solutions to problems M110—M122; F131—F137
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 60
page_last: 74
page_labels: 58, 59, 61, 62, 64, 66, 68, 70, 71, 72
tag: RDDV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 68e9273818ca4115df8f34c67e79aaddb548b74d8a439fd2deacc4b6f963a35a
prompt_sha256: draft-1
translated_from: content/ru/1972/08/articles/15_resheniya-7f762f80.md
source_content_sha256: baea7641b9d379546019e4e799fc6c81519187c6e750e0ee62f8248ae4ea1ffa
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

Solutions
In this issue we publish solutions to problems M110—M122

M110
On an infinite sheet of checkered paper N cells are painted black. Prove that a finite number of squares can be cut from a sheet so that two conditions are satisfied:
1) all black cells will lie in the cut out squares;
2) in any cut square K, the area of ​​black cells is not less than 1/5 and not more than 4/5 of the area of ​​K.

We will call acceptable squares that are shaded no more than 4/5 and no less than 1/5. Let's take n such 2x2 squares, each of which is shaded less than 4/5. Those squares that contain at least one black cell are already 1/4 shaded and therefore acceptable. The remaining 2x2 squares will not contain filled cells, therefore, all black cells will fall into valid squares and thus require a covering to be built.

The problem can be generalized to the three-dimensional case, with 1/5 and 4/5 replaced by 1/9 and 8/9, respectively.

M111
The square on side 1 contains a figure whose distance between any two points is not equal to 0.001. Prove that the area of ​​this figure does not exceed 0.34.

Try to get a more accurate estimate and prove a similar theorem in space.

Let us denote our figure by F, and by S its area. Consider the figure F₁ obtained by dwga F by 0.001 in a direction parallel to the side of the square. The figure F₂ is F shifted by 0.001 in direction 2, making an angle of 60° with direction 1 (Fig. 2, a). The figures F₁ and F do not have common points. Indeed, let point A belong to F and at the same time belong to F₁, that is, obtained by dwth of some point B of the figure F by 0.001. Then the distance between A and B will be 0.001,

⟦folio 59⟧

Fig. 2.

contrary to the conditions of the task. Similarly, $F$ does not intersect with $F_2$ and $F_1$ with $F_2$. All three figures under consideration have the same area $S$ and lie within the square on side 1.001. Therefore, the inequality $3S < 1,001^2$ is true, hence $S < 0,335$.

This estimate can be somewhat refined (in the third or fourth decimal place) through a more accurate study of the part of the figure $F$ lying near the boundaries of the square. We will, however, prove a significantly better estimate, namely $S < 0,287$.

Consider the figures $F_3$ and $F_4$ obtained from $F$ with a shift of 0.001 $\sqrt{3}$ in two directions, 3 and 4, forming an angle arcsin $\left(\frac{1}{2\sqrt{3}}\right)$; $F_4$ can be obtained from $F_3$ with a shift of 0.001, so $F_3$ and $F_4$ do not intersect (Fig. 2, b). From these, let’s choose the one (for example, $F_3$) that has less intersection with $F$. The area of ​​this intersection is no more than $S/2$, so the total area occupied by $F$ and $F_3$ will be no less than $3S/2$. Let us now construct figures $F_5$ and $F_6$, shifting $F$ by 0.001 in directions 5 and 6, forming an angle $30^\circ$ with $3$ (Fig. 2, c). The figure $F_3$ can be obtained from $F_5$ with a shift of 0.001 in direction 6 and from $F_6$ with a shift of 0.001 in direction 5. Therefore, $F_5$ and $F_6$ do not intersect with either $F$; They do not intersect with each other either. Therefore, the area occupied by $F$, $F_3$, $F_5$ and $F_6$ is not less than $7S/2$. All these figures must be contained in a square on the $1 + 0,001\sqrt{3} < 1,0018$ side, so $S < \frac{2}{7}(1,0018)^2 < 0,287$. This estimate was to be proved by A. Golberts (Moscow).

The question of whether there is a significant better estimate remains open. All examples that can be constructed give a value of $S$ less than 0.25.

G. V. Rosenblom

M112

The table $m \times n$ contains numbers in such a way that for any two rows and any two columns, the sum of the numbers in two opposite vertices of the triangle formed by it is equal to the sum of the numbers in its two other vertices. Frequent erases, but the remaining erasers can be restored. Prove that there are at least $(n+m-1)$ numbers left.

For a mathematician, the idea of ​​our proof can be stated as follows. Tables that satisfy the conditions of the problem form a linear space of dimension $n+m-1$. On the other hand, if the numbers in some s cells uniquely define the table, then the dimension of the “table space” does not exceed s, so $s \geq n+m-1$.

Let us now move on to a detailed presentation of the proof. Conditions name the numbers in the table, its elements. We will denote by $a_{ij}$ the table element $A$ located at the intersection of the i-th row and the j-th column.

Naturally, the sum of the table and the multiplication of the table by the number are determined.

The addition of two tables $A$ and $B$ with elements $a_{ij}$ and $b_{ij}$, then their sum $C = A+B$ is called a table with elements $c_{ij} = a_{ij}+b_{ij}$.

Multiplying a table by a number. If we are given a table $A$ with elements $a_{ij}$, then table $\lambda A$ is a table $B$ with elements $b_{ij} = \lambda a_{ij}$.

It is easy to check that if tables that satisfy the conditions of the problem are added together and multiplied by numbers, then we get tables that again satisfy the conditions of the problem. Since all meetings of the table satisfy the conditions of the problem, we do not specify this anymore.

Let us now introduce the very important concept of linear dependence. Let us create a table consisting of linear dependences if it is possible to indicate such numbers $\lambda_1, \lambda_2, \dots, \lambda_r$, not all of which are equal to zero, that the table $\lambda_1A_1 + \lambda_2A_2 + \dots + \lambda_rA_r$ is zero.

(For example, if among the tables $A_1, A_2, \dots, A_r$ some two tables are identical ($a_{ij} = a_{jj}$), then such a set of numbers $\lambda_1, \lambda_2, \dots, \lambda_r$ can be indicated: $\lambda_i = 1$, $\lambda_j = -1$, and all the rest are zero.) If for the table $A_1, A_2, \dots, A_r$ such numbers $\lambda_1, \lambda_2, \dots, \lambda_r$ do not exist, then they are called linearly independent.

We challenge the reader to prove that from any set of table $B_1, B_2, \dots, B_s$, not all of which are equal to zero, one can select a maximal linearly independent set $B_{l_1}, B_{l_2}, \dots, B_{l_r}$, that is, a set such that if another maximal set $B_{j_1}, B_{j_2}, \dots, B_{j_r}$ is specified, then $r = t$.

Let us now return to our task. Let there be s numbers left that have not been erased and the table can be reconstructed uniquely from them. Let us prove that only the zero table has zeros in our s cells (in those cells where the numbers are not erased). Indeed, if we found a non-zero table $B$, which had zeros in our s cells, then it would be possible to restore not only some table $A$, but also tables $A + \lambda B$, where $\lambda$ -

⟦folio 61⟧

Fig. 4.

then after their rearrangement the sum (1) will increase. Indeed, if $x_i$ and $x_{i+1}$ can be rearranged, then $(x_{i-1}-x_{i+2})(x_i-x_{i+1})<0$, and this inequality can be written as follows: $x_{i-1}x_i+x_{i+1}x_{i+2}<x_{i-1}x_{i+1}+x_{i+1}x_i+x_{i+2}$.

But in total there is a finite number of possible permutations of the numbers $x_1, x_2, \dots, x_n$ around the circle, therefore the sum (1) can take only a finite number of values. Therefore, our operation can only be performed a finite number of times: otherwise we would get an infinite sequence of different values ​​for the sum (1) $s_1<s_2<s_3<\dots$.

M115

A whole number of liters of water are poured into three vessels. It is allowed to pour into any vessel as much water as it already contains from any other vessel. Prove that several such transfusions can free one of the vessels. (The vessels are large enough: everyone can take all the water together.)

Let there be $a$ liters of water in the first vessel, $b$ liters in the second, $c$ liters in the third, and $a \leq b \leq c$ liters.

Let us first consider the case when $a=1$. If you add water only to the first vessel, then with the first transfusion you will need to add 1 liters of water, with the second - two liters, with the third - four liters, generally with the $i$th transfusion - $2^{i-1}$ liters.

Let us now, of course, divide the number, conditionally, of water in the second vessel into portions: $2^{i_0}, 2^{i_1}, \dots, 2^{i_k}$, where $i_0 < i_1 < \dots < i_{k-1} < i_k$. (To do this, we find a $i_k$ such that $2^{i_k} \leq b$, and $2^{i_k+1} > b$, then $b=2^{i_k}+b_1$, where $b_1 < 2^{i_k}$; for it, in turn, we find $2^{i_k-1}$, etc.)

If $i_0=0, i_1=1, i_2=2, \dots, i_k=k$, then we won’t need the third vessel. Let's start pouring from the second vessel into the first. After the first transfusion, there will be two liters in the first vessel, and $2+2^2+2^3+\dots+2^k$ liters in the second, after the second there will be $2^2$ and $2^2+2^3+\dots+2^k$, after the third - $2^3$ and $2^3+ \dots+2^k$, after the $k$ - $2^k$ and $2^k$ and after the $k+1$ - $2^{k+1}$ and 0.

If some powers of two, less than $2^{i_k}$, are missing from the “portions”, then we will highlight insufficient portions in the third vessel (there is enough water in it for this; indeed, we have enough $1+2+2^2+ \dots+2^{i_k-1}=2^{i_k}-1$ liters of water, this is less than $b$ liters, and $b$, in turn, is less than $c$).

Now we will pour it like this: each time we will use a small vessel in which the corresponding portion is allocated. After the $i_k+1$ transfusion, the second vessel will be empty.

The general case ($a \neq 1$) is actually nothing more complicated. Let's represent $b$ and $c$ like this: $b=b_1a+b_2$, $c=c_1a+c_2$, where $b_1, b_2, c_1, c_2$ are natural numbers, and $b_2<a, c_2<a$ (such a representation is unique). If we now forget about the “extra” $b_2$ and $c_2$ liters, and declare $a$ liters a new unit of volume, then since $b_1 \leq c_1$, we can arrange a transfusion so as to pour $b_1$ liters from the second vessel. After this, there will be $b_2$ liters left in it, with the integer $b_2$ being less than $a$. So, we managed to move from vessels with $a \leq b \leq c$ liters of water to vessels with $a' \leq b' \leq c'$. liters of water, and $a>a'$. By repeating our procedure, we will successively obtain vessels with less and less water: $a>a'>a'' \dots$. Since one of the sequences is an integer number of liters, after a finite number of steps we will obtain an empty vessel.

Note that this problem first appeared in one of the works of the famous Soviet algebraist A.I. Shirshov. He needed it to build a server-side mathematical theory. By the way, this is not the only problem proposed for optimization, taken from a wave of server-side mathematical work.

L. G. Limanov

M116

Prove that if you connect the midpoints of successive sides of a convex $n$-gon $M$ (Fig. 5), then the resulting polygon

⟦folio 62⟧

a) the perimeter is not less than half the perimeter $M$ ($n \geqslant 3$);
b) the area is not less than half the area $M$ ($n \geqslant 4$).

Let $A_1 A_2 \dots A_n$ be the given polygon $M$, $B_k$ the midpoint of side $A_{k-1} A_k$ (here and below $k=1, 2, \dots, n$, and it is assumed that $A_{n+1}=A_1$, $A_0=A_n$, etc.), $S$ and $S'$ the areas, $P$ and $P'$ are the perimeters of polygons $A_1 A_2 \dots A_n$ and $B_1 B_2 \dots B_n$, respectively; $n \geqslant 4$.

Note that the diagonal $A_{k-1} A_k+1$ cuts off the triangle $A_{k-1} A_k A_{k+1}$ from the polygon, in which $B_k B_{k+1}$ is the midline (Fig. 6), so
a) $A_{k-1} A_{k+1}=2B_k B_{k+1}$;
b) $S(\Delta A_{k-1} A_k A_{k+1})=4S(\Delta B_k A_k B_{k+1})$.
(These relationships played a major role in most solutions submitted by readers.) It is clear that of all the diagonals $A_{j-1} A_{j+1}$ (where $j=1, 2, \dots, n$; $j \neq k$) a given triangle $A_{k-1} A_k A_{k+1}$ intersects only two: $A_{k-2} A_k$ and $A_k A_{k+2}$, and the corresponding intersection points $C_k$, $C_{k+1}$ of these diagonals with $A_{k-1} A_{k+1}$ are located in such an order that the segments $A_{k-1} C_k$ and $C_{k+1} A_{k+1}$ (and, therefore, the triangles $A_{k-1} A_k C_k$ and $C_{k+1} A_k A_{k+1}$) do not overlap each other. Now the statement of the problem is proved as follows (sums $\Sigma$ are taken over all $k$):
a) $2P'=2\Sigma B_k B_{k+1}=\Sigma A_{k-1} A_{k+1} > \Sigma A_{k-1} C_k + \Sigma C_{k+1} A_{k+1} =$
(blue segments at Fig. 7)
$= \Sigma (A_{k-1} C_k + C_k A_k) > \Sigma A_{k-1} A_k = P$
(triangle inequality for $\Delta C_k A_{k-1} A_k$), whence $P' > P/2$;
b) $4(S-S')=4\Sigma S(\Delta B_k A_k B_{k+1}) = \Sigma S(\Delta A_{k-1} A_k A_{k+1}) \leqslant 2S$ (since triangles $A_{k-1} A_k A_{k+1}$ ignore a polygon of more than two layers), whence $S' \geqslant S/2$; equality here is achieved only for $n=4$ (in case a) - only for $n=3$).

The correct solution to both problems a) and b) is added by A. Merkuryev and A. Kolobsky from Leningrad, M. Rozov and A. Chernaya from Minsk, M. Illarina, A. Glushko and B. Korenyako from Voronezh, V. Shikhman, I. Shparlinsky and M. Kolodochki from Moscow, B. Khafizov from the village. The rich Saby of the Tatar Autonomous Soviet Socialist Republic, E. Turkevich from Chernivtsi, L. Pugach and S. Lyagushiin from Dnepropetrovsk, A. Tsanava from Tbilisi, A. Ryabkin from the city of Rechitsa, Gomel region, A. Gordienko from the village. Poltavensky Krasnoarsk Territory, A. Smirnov from Gorky, V. Maltsenko from Slavyansk in the Kuban, N. Chernov from Krivoy Rog, A. Makriev from Lvov, A. Zhumadildaev from Alma-Ata, S. Malevakin from Fedosin, G. Filkovsky from Baku, V. Chukhin from Volsk, Mari Autonomous Soviet Socialist Republic, Yu. Kisin from St. Russians.

Thus, it has been proven that the ratios $P'/P$ and $S'/S$ (respectively, for $n \geqslant 3$ and $n \geqslant 4$) lie in the range from 1/2 to 1. A natural question arises - its discussion is not

⟦folio 64⟧

Fig. 9.

odd observables are less than one, then the number of odd observables must be greater than $\left(\frac{t}{2}\right)$. This means that the snail could not crawl the path changing $\left(\frac{t}{2}\right) + 1$. This is the answer to the second question of the problem. The graph (see Fig. 9) shows how the snail must move for this minimum to be achieved.

Task a. Now try to correctly formulate the lemma mentioned in the first paragraph of our solution.

N. N. Konstantinov

M118

On four sides of the chessboard of size $n \times n$ there is a border two fields wide.

Prove that this border can be bypassed by a chess knight by raising on each square once and only once, if and only if $n-1$ is a multiple of 4.

To solve the problem, it is enough to show that a four-sided border of width 2 can be bypassed with a knight for $n=4t+1$, but not for $n \neq 4t+1$.

Fig. 10. Here which field is connected by black segments with those fields in which you can get from it with one move of the knight. The red line is a path with ends A and B, passing through all fields once. [Note that if together with the segment $A_1B_1$ we include the segments $AA_1$ and $BB_1$ in the path, then it splits into two closed paths].

Fig. 12. Inserted blocks are highlighted with its color.

hard $A_1, A_2, \dots, A_k$, which contain m fields, and

1) these subsets do not have common fields;
2) from any field of the subset $A_i$ the knight cannot go to any field of the subset $A_j$ at $i \neq j$;
3) $g - m < k - 1$, then the region G cannot be bypassed by the knight.

The proof of the lemma is sufficiently appreciated. Indeed, if the knight managed to go around the entire region G, then the knight’s path must go through all k subsets. Moreover, due to condition 2) of the lemma, when moving from subset to subset, the knight will have to increase at least k-1 times outside the subsets, but outside the subsets by condition

⟦folio none⟧

Fig. 13. Color cells are a subset of $A_1$. All other cells are $A_2$.

3) Lemma there is no such number of fields. The lemma is proven.

Let's consider three cases: 1) $n=4t$; 2) $n=4t+2$ and 3) $n=4t+3$.

Let's start with the easier case 3), when $n=4t+3$. Let's divide the entire border into two subsets $A_1$ and $A_2$ as shown in figure 13. (Here $t=0$; in order to get figure with others $t$, you need to leave the blocks shown in Fig. 11.)

It is easy to see that it is impossible to get from the subset $A_1$ to the subset $A_2$ by moving the knight. Therefore, we can apply Lemma ($k=2$, $m=g$).

In the remaining two cases $n=4t$ and $n=4t+2$ the main difficulty is the description of fields that will not be included in any of the subsets. We will call them neutral.

Case 1) ($n=4t$). For $t>0$ we declare neutral fields that have one common side with the corner fields of the bordered board. (On figure 14 they are placed with the letter Z.) There will be 8 of them. There will be 10 subsets of them - they are determined as follows: we take an unoccupied field and all those fields in which you can “pass” from it with a knight, without using neutral cells. All these fields form one subset. In order to obtain figure from figure 14 for any $t>0$, you need to leave the blocks shown in figure 11. For $t=0$ neutral fields and subsets are shown in figure 15.

Case 2) ($n=4t+2$) is analyzed in a similar way. Here, at $t>0$, the number of neutral fields is 12, and the number of subsets is 14. How to choose neutral fields at $t>0$ and at $t=0$ can be seen from figure 16 and 17.

Problem M118 is a special case of such a problem: given a “graph” (a system of “vertices”, some of which are “connected by edges”), it is required to find a path that goes around the ruffs once at a time - the so-called “Miltonian path”.

Note that in the general case this problem has not been solved - no simple algorithm has been found that allows one to construct a Hamiltonian path for an arbitrary graph and even find out

⟦folio 66⟧

does such a way exist? A similar task—finding a path by going through all the edges once—is much simpler.

Yu. Yu. Sorkin

M119

Prove that if you select a point on each face of a convex polyhedron and draw from this point a vector that is directed perpendicular to the corresponding face to the outside and whose length is equal to the area of ​​this face, then the sum of such vectors will be equal to zero.

Verification and a short proof can be obtained from physical communications. Let's imagine that a closed vessel, the internal cavity of which has the shape of our polyhedron, is filled with gas under pressure $P$ and placed in a void (there are no external forces - weight, etc.). Then the gas pressure force on the face of the area $S$ is equal to $PS$ and is directed perpendicular to this face to the outer side (as they say briefly, “along the outer normal” to the face). Of course, we can take $P$ equal to 1; then the forces acting on the edge will be equal to the vectors discussed in the conditions of the problem. Since the vessel cannot move by acceleration under the influence of only internal forces, the vector sum of these forces, that is, the sum of our vectors, is equal to zero.

We also present a number of mathematical proofs. (We will not discuss here in detail the interesting question of the extent to which the above reasoning can be considered a “rigorous proof”. Let us note that all the physical concepts and laws used in it could be introduced within the framework of a strict mathematical “deductive” theory: the concepts would receive precise definitions, the laws would receive the structure of proof, and experimental data would be considered as confirmation of the usefulness of definitions and theorems; but in a school - and not only in a school - physics course, such an approach is not very popular. Moreover, to carry out such a “formalization” of the physics course, a school mathematics course was clearly not enough to solve our problem.)

We will need the following lemma (we give its proof at the end of the solution): if a polygon has area $S$ and its plane forms an angle $α$ ($0° < α < 90°$) with some plane $π$, then the area of ​​the projection of this polygon onto the plane $π$ is equal to $S \cos α$.

Let us take an arbitrary axis (directed straight line) $l$ and a plane $π$ perpendicular to it. Project all the faces of our polygon onto the $π$ plane, and their corresponding vectors onto the $l$ axis. If the area of ​​one of the faces is $S$, and the angle formed by its “outer normal” with the axis is $l$,

Fig. 18. a) upper faces: $0 \leqslant α \leqslant 90°$; b) bottom edges: $90° < α \leqslant 180°$.

is equal to $α$, then the projection of the vector onto the axis $l$ is equal (taking into account the sign) $S \cos α$, and the area of ​​the projection of the face onto the plane $π$ is equal to $|S \cos α|$. We write the model sign because the angle $α$ can be not only acute (Fig. 18a; faces for which we call $α \geqslant 0$ upper), but also obtuse (Fig. 18b; faces for which $α < 0$ we call lower).

Let us now consider the polygon in which our polygon is projected (on the plane $π$). This polygon, as can be seen from figure 18a and 186, can be composed from the projections of all upper faces, or from the projections of all lower faces. (Here we take advantage of the fact that the polygon is convex, therefore, on each line parallel to $l$ and intersecting the polygon, there is one point belonging to the upper edges and one to the lower edges). Therefore, if we separate the average numbers $S \cos α$ positive and negative, then the sum of both according to the model will be the same. Therefore, the sum of all numbers $S \cos α$ corresponding to different edges is equal to 0. So, the sum of the projections of our vectors

⟦folio 68⟧

group are large $A$, then the arithmetic mean of all numbers is large $A$ (indeed, if the sum of the numbers in the first group is large $(n - n_1) A$, in the second - large $(n_1 - n_2) A$ ..., in the last - large $n_r A$, then the sum of all large $n_A$). But by $A$ we just denoted the average of all $n$ numbers. The resulting contradiction proves that our assumption is incorrect.

Many of our readers think differently. For example, it is useful to subtract the value $A$ (their arithmetic mean) from each of the given numbers. Then the problem will be reduced to the special case when the arithmetic mean of all numbers is equal to zero. After this, you can discard the denominator and talk not about averages, but about sums of numbers and their signs, and the problem is posed as a simple consequence of this problem: if several numbers are written around a circle, the sum of which is equal to 0, then there is a number such that it itself is non-negative, its sum with the next clockwise is non-negative, its sum with the next two is non-negative, etc. up to the sum of all $n$ numbers. This problem (in a slightly different formulation) was already discussed in «Kvant» (see «Kvant» No. 1, 1972, p. 42, solution to problem M82).

M122

Pentagon ABCDE is inscribed in a circle. It is known that the distances from the point $E$ to the lines $AB, BC, CD$ are equal to $p, q, r$, respectively. Find the distance from point $E$ to line $AD$.

If a circle is given and there are two points $P$ and $Q$ on it, then by $s$ ($PQ$) we will denote the sine angle subtended by the arc $PQ$ (since $\sin \alpha = \sin (180^\circ - \alpha)$ does not depend on which of the two arcs the point $M$ lies).

We come across the following two facts.

1°. Let $PQ$ be a chord of a circle of radius $R$. Then $PQ = 2Rs$ ($PQ$).

2°. If $P, Q$ and $E$ are three different points on a circle of radius $R$, then the distance from point $E$ to line $PQ$ is $2Rs(EP)$ ($s(EQ)$).

Statement 1° is well known (from it the “sine theorem” for a triangle is generally derived), and 2° can most easily be derived from 1° by calculating the area of ​​the triangle $PQE$ in two ways. If $\alpha$ is the angle at the vertex $E$ of this triangle, $h$ is the height omitted from this vertex, then the double area is $h \cdot PQ = EP \cdot EQ \cdot \sin \alpha$, whence, taking into account the fact that $EP = 2Rs(EP)$, $EQ = 2Rs(EQ)$, $PQ = 2Rs(PQ) = 2R \sin \alpha$, we obtain $h = 2Rs(EP)$ ($s(EQ)$).

Now problem M122 can be solved instantly: according to the condition

$$p = 2Rs(EA) s(EB),$$
$$q = 2Rs(EB) s(EC),$$
$$r = 2Rs(EC) s(ED),$$

Consequently, the distance from point $E$ to line $AD$ is

$$2Rs(EA) s(ED) = pr/q.$$

This problem was proposed in one of the versions of the written exam in mathematics at Moscow State University in physics in 1971 (where it was the most difficult).

N. B. Vasiliev

In this issue we publish solutions to problems F131—F137

F131

A light glass tube of length $l$ and cross-section $S$, filled with a cylinder and sealed at one end, is located horizontally in a tank with a jet near the surface. What minimum work must be done to move the tube to a vertical position in which its open end touches the surface of the mercury?

The work required to move the tube is independent of the method in which we move the tube to a vertical position. You can, for example, rotate the tube around the end, you can rotate the tube around the middle and then grow it out of mercury, and finally you can rotate it around the end and then grow it out of mercury again. It is most convenient to consider the last method.

When moving mercury inside a tank from one place to another, no work is expended, since the potential

the energy of the system does not change. Therefore, no work is wasted when turning the tube around the end. Therefore, only the work required to “pull” the tube out of the mercury needs to be taken into account.

If the end of the tube is above the surface at a height of $x$ (Fig. 20), then the atmospheric pressure force $F_1 = P_0S$ acts on it from above, and the force $F_2 = P \cdot S$ acts on the bottom of the tube from below, where $P$ is the pressure on the bottom. $P$ can be found by writing down the conditional equilibria of a column of mercury in a tube

$$P + \rho gx = P_0.$$

(The pressure at point $B$ must be equal to $P_0$.) Hence

$$P = P_0 - \rho gx.$$

The force with which you need to pull out the tube is very much equal to the difference between the forces $F_1$ and $F_2$:

$$F = F_1 - F_2 = \rho gxS.$$

This force is proportional to $x$.

⟦folio none⟧

Fig. 20.

Fig. 21.

However, this is only true until $P$ becomes zero, that is, at $x \leq \frac{P_0}{\rho g} = 0,76$ m.

If the length of the tube $l$ is greater than $x_1 = P_0/\rho g = 0,76$ m, then at $x > x_1$ $P = 0$ (the rutin vapor pressure can be neglected), and the force with which it is necessary to “pull” the tube is equal to a simple $F_1 = P_0 S$.

Let's draw a graph of the force $F$ versus $x$ (Fig. 21). The work required to pull out the tube is equal to the area of ​​the figure below this graph. Therefore, if $l < x_1$, then

$$A = \frac{1}{2} \rho g l S \cdot l = \frac{1}{2} \rho g S l^2.$$

At $l > x_1$

$$A = \frac{1}{2} \rho g S x_1^2 + P_0 S (l - x_1) =$$

$$= \frac{1}{2} P_0 S x_1 + P_0 S (l - x_1) =$$

$$= P_0 S \left( l - \frac{1}{2} x_1 \right).$$

F132

The mass cylinder $m$ was untwisted and placed between two fixed planes located at an angle $2\alpha$ to each other (Fig. 22). Knowing that the coefficient of friction between the cylinder and the planes is $k$, determine the force with which the cylinder acts on the plane.

Consider the equilibrium of a cylinder. It is acted upon by the forces $N_1$ and $N_2$ of the normal reactions of the planes, the friction forces $F_1$ and $F_2$ and the gravity force $mg$. The surface of the cylinder slides along the planes, therefore $F_1 = k N_1$ and $F_2 = k N_2$.

Since the cylinder is in equilibrium, the sum of the projections onto any axis of all forces acting on it must be equal to zero. Let's project all the forces onto two mutually perpendicular axes - horizontal and vertical:

$$-N_1 \cos \alpha + N_2 \cos \alpha + F_1 \sin \alpha + F_2 \sin \alpha = 0,$$

$$N_1 \sin \alpha + N_2 \sin \alpha + F_1 \cos \alpha - F_2 \cos \alpha - mg = 0.$$

Substituting the values ​​$F_1 = k N_1$ and $F_2 = k N_2$ into these equations, dividing the left and right sides by cos $\alpha$, we obtain:

$$(N_1 + N_2) k \mathrm{tg} \alpha - N_1 + N_2 = 0,$$

$$(N_1 + N_2) \mathrm{tg} \alpha + k N_1 - k N_2 = \frac{mg}{\cos \alpha}.$$

Solving the equation jointly, we get

$$N_1 = \frac{mg}{\cos \alpha} \cdot \frac{1 + k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)},$$

$$N_2 = \frac{mg}{\cos \alpha} \cdot \frac{1 - k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)}.$$

Therefore, the friction forces

$$F_1 = \frac{mg k}{\cos \alpha} \cdot \frac{1 + k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)},$$

$$F_2 = \frac{mg k}{\cos \alpha} \cdot \frac{1 - k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)}.$$

Knowing the forces acting on the cylinder, it is not difficult to find the forces acting with

⟦folio 70⟧

sides of the cylinder on a plane. According to Newton's third law, these forces are equal in magnitude and opposite in direction. On figure they are marked with blue vectors.

Since the force $N_2$ cannot be negative, the solution is valid for $k \text{tg} \alpha \leq 1$. If $k \geq \frac{1}{\text{tg} \alpha}$, then $N_2 = 0$ and $F_2 = 0$. In this case, the cylinder either ends without touching the left inclined plane, or rises up along the right inclined plane.

F133

A closed metal chain is connected by a thread to the axis of the centering machine and rotates with an angular velocity $\omega$ (Fig. 23). In this case, the thread makes an angle $\alpha$ with the vertical. Find the distance from the center of the chain's weight to the axis of rotation.

The forces acting on the chain are shown at figure; $T$ is the thread tension force, $mg$ is the tension force. Since the center of the heavy stack of the chain moves along a circle of radius $x$, then, according to Newton’s second law, the sum of the projections of all forces acting on the chain onto the horizontal direction must be equal to the product

Fig. 23.

mass of the chain on the centripetal acceleration of its center of mass. That is

$$T \sin \alpha = m \omega^2 x.$$ (1)

The chain does not move in the vertical direction; therefore, the sum of the projections of all forces acting on the chain onto the vertical direction is equal to zero:

$$T \cos \alpha - mg = 0.$$ (2)

Eliminating $T$ from these equations, we find

$$x = \frac{g}{\omega^2} \text{tg} \alpha.$$ (3)

F134

A heavy plate moves with a speed $v$ in a direction perpendicular to its plane. At an angle $\alpha$ to the direction of motion of the plate, a light ball flies at a speed $u$. Determine the magnitude and direction of the speed of the ball after its elastic collision with the plate.

a) Distance the case when the speed of the ball is directed towards and away from the plate.

b) How does the answer change if the plate moves in a direction making an angle $\beta$ with its plane?

a) Since the speed of the plate does not change during the collision, the plate-ball system is not isolated and the law of conservation of momentum cannot be used to solve the problem. So let's do it this way. Let's decompose the speed of the ball into components - parallel to the plate and perpendicular to it - and move to the coordinate system associated with the plate. In this coordinate system, the component of the ball's velocity parallel to the plate is $u \sin \alpha$, and that perpendicular to the plate is $u \cos \alpha + v$ (Fig. 24). After an elastic collision of the ball with the plate, the component of the ball’s velocity parallel to the plate will not change, and the component perpendicular to the plate will be the same in value, but opposite in direction.

Now let's “return” to the fixed coordinate system. Here the velocity components of the ball after hitting the plate will be $u \sin \alpha$ and $(u \cos \alpha + v) + v = u \cos \alpha + 2v$.

This means that the speed of the ball after hitting the plate in a fixed coordinate system is equal to

$$u' = \sqrt{u^2 \sin^2 \alpha + (u \cos \alpha + 2v)^2} = \sqrt{u^2 + 4v^2 + 4vu \cos \alpha}.$$ (1)

This speed is determined by the direction

⟦folio 71⟧

Fig. 25.

motion of the plate angle γ such that

$$\text{tg} \gamma = \frac{u \sin \alpha}{u \cos \alpha + 2v}.$$ (2)

We examined in detail the case when the speed of the ball is directed towards the plate. It is clear that if the speed of the ball is directed away from the plate, then $u \cos \alpha < v$, the solution remains correct, only in all formulas it is necessary to replace $u \cos \alpha$ with $-u \cos \alpha$. At $u \cos \alpha \geq v$ the ball will not collide with the plate.

6) It is not difficult to generalize the problem to the case when the plate moves in a direction making an angle β with its plane. It is clear that in this case, when the ball collides with the plate, only the component of its velocity perpendicular to the plate will change. Its change is the same as in the case when the plate moves in a direction perpendicular to its plane with a speed $v' = v \sin \beta$ (Fig. 25). Therefore, we will get the correct answer if we substitute $v'$ in formulas (1) and (2) together with $v$. Then

$$u' = \sqrt{u^2 + 4v^2 \sin^2 \beta + 4uv \cos \alpha \sin \beta},$$

$$\text{tg} \gamma = \frac{u \sin \alpha}{u \cos \alpha + 2v \sin \beta}.$$

F135

A mine lying on the ground explodes from detonation. The mine fragments begin to move symmetrically in all directions with the same speeds $v$. Dimensions of all velocities, what fraction of the scorches will fall outside the circle of radius $R$ centered at the point of explosion?

Let us write down the kinematic equations of motion along the $X$ and $Y$ axes for the sap that fell at an angle $\alpha$ to the horizon:

$$x = vt \cos \alpha, \quad y = vt \sin \alpha - gt^2/2.$$ (1)

Let us find from these equations the flight distance of the rock. At the moment the rock falls to Earth, its coordinate $y$ is equal to zero, and the coordinate $x$ is the flight distance $l$. So, at this moment

$$vt_0 \cos \alpha = l, \quad vt_0 \sin \alpha = gt_0^2/2.$$ (3)

(Here $t_0$ is the flight time of the salt.) Consequently, the flight distance of the salt

$$l = v \cos \alpha \cdot \frac{2v}{g} \sin \alpha = \frac{v^2}{g} \sin 2\alpha.$$ (2)

It is not difficult to determine at what angles of exposure of fragments their flight range is greater than $R$:

$$\frac{v^2 \sin 2\alpha}{g} > R, \quad \sin 2\alpha > \frac{gR}{v^2},$$

$$\alpha_0 \leq \alpha \leq \pi/2 - \alpha_0,$$

where $\alpha_0 = \frac{1}{2} \arcsin \frac{gR}{v^2}$.

Let us mentally draw a hemisphere of radius $a$ around the mine. Obviously, part of the fragments $n$ emitted in the angle interval $\alpha_0 \leq \alpha \leq \pi/2 - \alpha_0$ is equal to the relative area $S$ of the lateral surface of the spherical layer, which is visible from the center of the hemisphere in this angle interval, to the area of ​​the hemisphere:

$$n = \frac{S}{\pi a^2}.$$

In order to find $S$, we divide the spherical layer into thin elephants, which are visible from the center of the hemisphere in a small interval of angles $\Delta \alpha$. The area $S$ of the lateral surface of such a thin layer with $\Delta \alpha = \alpha_2 - \alpha_1$ is equal to its width $a \Delta \alpha = a (\alpha_2 - \alpha_1)$, multiplied by the circumference of the middle section of the layer - its radius is $a \cos \frac{\alpha_1 + \alpha_2}{2}$:

$$s = 2\pi a \cos \frac{\alpha_1 + \alpha_2}{2} \cdot 2a \frac{\alpha_2 - \alpha_1}{2}.$$

Since $\Delta \alpha = \alpha_2 - \alpha_1$ is small, then

$$\frac{\alpha_2 - \alpha_1}{2} \approx \sin \frac{\alpha_2 - \alpha_1}{2},$$

$$s \approx 4\pi a^2 \sin \frac{\alpha_2 - \alpha_1}{2} \cos \frac{\alpha_1 + \alpha_2}{2} = 2\pi a^2 (\sin \alpha_2 - \sin \alpha_1).$$

The area $S$ of the lateral surface of the entire layer is equal to the sum of the areas of the lateral surfaces of thin words:

$$S = s_1 + s_2 + \dots = 2\pi a^2 (-\sin \alpha_0 + \sin \alpha_1 - \sin \alpha_2 + \dots) = 2\pi a^2 \left[ \sin \left( \frac{\pi}{2} - \alpha_0 \right) - \sin \alpha_0 \right] = 2\sqrt{2} \pi a^2 \sin \left( \frac{\pi}{4} - \alpha_0 \right).$$

But

$$\sin \left( \frac{\pi}{4} - \alpha_0 \right) = \sqrt{\frac{1 - \sin 2\alpha_0}{2}}.$$

⟦folio 72⟧

Hence,

$$S = 2\sqrt{2}\pi a^2 \frac{1 - \sin\left(\frac{gR}{v^2}\right)}{2} = 2\pi a^2 \sqrt{1 - \frac{gR}{2}}$$

And

$$n = \frac{S}{\pi a^2} = 2\sqrt{1 - \frac{gR}{v^2}}.$$

F136

A parallel plate capacitor has a capacitance of $C$. A charge +$q$ was placed on one of the capacitor plates, and a charge +4$q$ was placed on the other. Determine the potential difference between the plates of the capacitor.

If there are charges +$Q$ and -$Q$ on the plates of a flat capacitor, then the field voltage between the plates is known to be $E = \frac{Q}{Cd}$. This field is equal to the sum of the identical fields of the two plates. Therefore, the field voltage of one plate with a uniformly distributed charge is $\frac{1}{2} \frac{Q}{Cd}$.

The field voltage of a plate with charge +$q$ is $\frac{1}{2} \frac{q}{Cd}$, and the field voltage of a plate with charge +4$q$ is $\frac{2q}{Cd}$. Unlike random capacitor charges, when the field voltages of the plates are directed in one direction and add up, in our case the field voltages created by the plates are directed in different directions. Therefore, the voltage of the single-field field between the plates is equal to the difference in the field voltage of each of the plates (Fig. 26):

$$E' = \frac{2q}{Cd} - \frac{1}{2} \frac{q}{Cd} = \frac{3}{2} \frac{q}{Cd}.$$

Now it is not difficult to find the difference between the potential plates. It is equal to equal, not

$$P_0 = \frac{mg}{S}.$$

From here

$$m = \frac{P_0 S}{g}.$$

Multiplying $m$ by $\alpha$, we obtain the mass of methane in this column:

$$m_{CH_4} = \alpha m = \frac{\alpha P_0 S}{g}.$$

Now let’s find the layer of thickness $x$ this mass of methane would constitute under normal conditions (the area of ​​the base of the cylinder is still equal to $S$).

Let us write the equation of the gas state:

$$P_0 Sx = \frac{m_{CH_4}}{\mu} RT,$$

where $Sx$ is the volume of the mass of methane $m_{CH_4}$, $\mu$ is the mass of one kilomole of methane ($\mu = 16 \frac{\kappa}{kmol}$), $R = 8,3 \cdot 10^3 \frac{\partial x}{\partial p} \cdot \frac{\partial p}{\partial T}$ is the gas constant, $T = 273^\circ K$ is the normal temperature and $P_0 = 1 \text{ atm}$ is the normal pressure. Substituting the expression for the mass of methane into this equation, we find

$$x = \frac{\alpha RT}{g\mu} (m).$$
