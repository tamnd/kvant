---
id: 1977-4-kushnirenko-tselyie-tochki-v-mnogougolnikah-i-mnogogrannikah-7809e81e
issue: kvant_1977_4
year: 1977
number: "4"
title: Integer points in polygons and polyhedra
authors:
  - Кушниренко А. Г.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 14, 15, 16, 18, 19, 20
tag: H802
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9f53001e13cb868948c2d8e9deaf727aeaa087c5ec38cffb88cbc805300889fd
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/06_kushnirenko-tselyie-tochki-v-mnogougolnikah-i-mnogogrannikah-7809e81e.md
source_content_sha256: 70439240f806bacfa0267821e49a6a53e66a32a661ed69924aaafbe52541b4b9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

Solid points in polygons and polyhedrons

In this article we will study polygons, all of whose vertices lie at integral points of the coordinate plane - at the nodes of checkered paper. Let $F$ be such a polygon, and $S(F)$ its area. If $N(F)$ is the number of nodes that fall inside and on the edge of the polygon $F$, then $S(F) \approx N(F)$. For $S(F)$ there are also exact formulas, for example, Pick’s formula («Kvant», 1974, No. 12):

$$S(F) = N(F) - B(F)/2 - 1,$$

where $B(F)$ is the number of nodes that fall on the edge $F$.

Pick's formula has one drawback: it does not have a direct analysis in space. The example given in figure 1 shows that the volume $V(F)$ of a polyhedron $F$ with vertices at the nodes of a cubic lattice cannot be expressed through $N(F)$, the number of nodes found inside and on the facet $F$, and through $B(F)$, the number of nodes found on the facet $F$. It is possible, however, to come up with similar formulas that can be perfectly generalized to the spatial case.

In this article, a small theory will be constructed that allows us to reconcile and prove all the mental analogues of the Pick formula on the plane and in space *).

*) See problem M385, «Kvant», 1976, No. 5.

§ 1. Introduction

How many solutions does the system of equations have?

$$\begin{cases} P(x, y) = 0, \\ Q(x, y) = 0, \end{cases}$$

where $P$ and $Q$ are polynomials in $x, y$ with real coefficients?

To answer this question, for each one-year polynomial $x^m y^n$, included with a non-zero coefficient in at least one of the polynomials $P$ or $Q$, we mark a point on the coordinate plane with coordinates $(m; n)$. Let us take the convex hull of the offset points - the smallest convex polygon containing all the offset points. This polygon is called the Newton polygon *) of system (1). It is convenient to draw it on checkered paper.

Having solved a couple of dozen systems of the form (1), I began to suspect that the following

Theorem 1. The number of non-zero solutions to system (1) is either infinite or does not exceed half the area of ​​its Newton polygon.

Fig. 1. $N(T_n) = 4$, $B(T_n) = 4$, $V(T_n) = n/6$.

⟦folio 14⟧

(A solution $(x_0, y_0)$ is said to be nonzero if $x_0 \neq 0$ and $y_0 \neq 0$.) In trying to prove Theorem 1, I almost proved that a similar one holds

Theorem 2. The number of non-zero solutions of system (1) is either infinite or does not exceed $N(2F) - 2N(F) + 1$, where $2F$ is a polygon obtained from $F$ with a distance twice relative to the origin (Fig. 2).

To finish the rather long proof of Theorem 2, all I had to do was show that

a) for any integer polygon $F$ the function $N(nF)$ is a second-degree polynomial in $n$ for integer $n \geq 0$ (I call a polygon integer if its vertices lie at the nodes).

Trying to understand which of theorems - 1 or 2 - is stronger, I became convinced that

b) for any integer polygon

$$2S(F) = N(2F) - 2N(F) + 1,$$

that is, Theorems 1 and 2 essentially coincide.

It turns out that both a) and b) can be derived from Pick’s formula in no time.

Exercise 1. Derive a) and b) from Pick's formula.

Task 1. Form an analogue of Theorem 1 for the system of equations $P(x, y, z) = Q(x, y, z) = R(x, y, z) = 0$ and an analogue of formula b) for polygons. Check the formula by looking at figure 3.

$$2S(F) = N(2F) - 2N(F) + 1$$

§ 2.

We will begin the construction of the theory promised above by honestly proving this simple formula. Let's denote its right side by $P(F)$. Let us show that if the integer polygon $F$ is divided by the diagonal $I$ into polygons $F_1$ and $F_2$, for which formula 6) is true, then it is also true for $F$. Indeed, since $N(F) = N(F_1) + N(F_2) - N(I)$, so does $P(F) = P(F_1) + P(F_2) - P(I)$. Obviously $S(F) = S(F_1) + S(F_2)$. Therefore $2S(F) = 2S(F_1) + 2S(F_2) = -P(F_1) + P(F_2) = P(F) + P(I)$. It is easy to check directly that for any integer segment $I$ (that is, a segment whose endpoints are integer points) $P(I) = 0$. So, $2S(F) = P(F)$. Thus, from validity 6) for triangles by induction follows the validity of 6) for $n$-gons: an integer quadrilateral can be cut into two integer triangles, a pentagon into a quadrilateral and a triangle, etc.

Formula 6) can be easily verified directly for rectangles composed of whole cells (Fig. 4). Let's take the “half” of such a rectangle $F$—right triangle $F_1$. We already know that $2S(F) = P(F)$. By symmetry $S(F_1) = S(F_2) = S(F)/2$ and $P(F_1) = P(F_2)$. Since $P(I) = 0$, then $P(F) = 2P(F_1)$, hence $2S(F_1) = P(F_1)$. Thus, formula 6) has been proven by us

Fig 3. $N(F) = (p+1)(q+1)(r+1)$,
$B(F) = N(F) - (p-1)(q-1)(r-1)$,
$V(F) = pqr$.

⟦folio 15⟧

Fig. 4 $N(F) = (p+1)(q+1)$, $N(2F) = (2p+1)(2q+1)$, $S(F) = pq$.

for right-angled triangles (with legs parallel to the axes).

An arbitrary integer triangle can be obtained by sequentially cutting off right triangles (Fig. 5) from a suitable rectangle. This means that formula 6) is true for any integer triangle, which remains to be proved.

§ 3. How we will generalize the arguments from § 2

In order to prove other formulas, for example, Pick's formula, we could repeat the reasoning of § 2 and prove the coincidence of two functions defined on the set of all integer polygons. In § 2 such functions were 2S(F) and P(F). To prove Pick’s formula, we would take S(F) and N(F)—B(F)/2—1, etc. This approach is bad in three ways. First of all, it's very boring. Secondly, this way you can prove already guessed formulas, but you cannot come up with new ones. Thirdly, acting in this way, we will never be increased in that we have received all the interesting formulas.

In two axiomatic approaches developed by a mathematician of the 20th century, we will try to immediately describe the entire class of functions to which the reasoning of § 2 is applied. To do this, we need to thoroughly analyze the solution to problem 6). The standard scheme for such analysis in our case looks like this:

Step 1. It is necessary to list those properties of functions defined on a set of integer polygons that are used in solving the original problem.

Step 2. You need to study all the functions that have these properties. (We'll call them convenient.)

Step 3. It is necessary to prove the function matching criterion and describe all convenient functions. (The criterion should be simple, and its application should immediately solve the original problem.)

Step 4. It is necessary to apply the resulting criterion to generalize the original problem.

§ 4. Remarkable functions on the set of flat integer funcurs

Polygons alone are not enough

The reader, I believe, has already noticed that in the reasoning of § 2 we encountered not only polygons, but also segments.

Definition. We will call a flat integer function (or simply functions) an integer point, an integer segment or an integer polygon. The set of all flat integer funcurs is denoted by F.

We will consider the processed Φ in the set of real numbers - functions on the set Φ.

⟦folio 16⟧

Fig. 6. “Warp”. $T(x, y) = (x+y; y);$
$T(1; 3) = (4; 3)$.
Each horizontal straight line $\{(x; y)|y=c\}$, under the influence of the “skew” $T$, is shifted along itself by a distance $c$. Each vertical line “warps” like the $y$ axis, which turns into a dotted line.

Step 1 - what functions on Ф we will consider.

We will call a function $f$ on the set $\Phi$ additive if it has the following properties:

A) if the integer functions $F, F_1, F_2$ are maxims such that $F = F_1 \cup F_2$ and $F_1 \cap F_2$ is a cardinal or segment, we can
$f(F) = f(F_1) + f(F_2) - f(F_1 \cap F_2)$.

Let us introduce coordinates $x, y$ on the plane. We will call four types of transformations acceptable:

1°. parallel transfers to integer vector $(a; b)$: $T(x; y) = (x+a; y+b)$;
2°. symmetrines: $T(x; y) = (\pm x; \pm y)$;
3°. permutation of coordinates: $T(x; y) = (y; x)$;
4°. “skews”: $T(x; y) = (x+ay; y)$, where $a$ is an arbitrary integer (Fig. 6).

A function $f$ on a set $\Phi$ is called invariant relative to the transformation $T$ if for any function $F \in \Phi$ the equality $f(TF) = f(F)$ holds.

We will call a function $f$ invariant if it is invariant under any admissible transformation.

Dilation 2. Prove that the function $R$, which takes the value 0 on any integer point, the value 2 on any integer interval, and the value $n$ on any integer $n$-gon, is invariant, but not additive.

Basic definition. We will call a function $f$ on the set $\Phi$ additive if it is additive and invariant.

Examples of convenient functions

We denote the set of all convenient functions on $\Phi$ by $Y$. Convenient functions exist. For example, the function $E$, which assigns the number 1 to each integer funcre, is convenient. Obviously, the function $N$, which assigns to each integer funcre $F$ the number $N(F)$, is convenient. It is clear that the function $S$ is additive. It is also obvious that $S(TF) = S(F)$ for any function $F$ and for any admissible transformation $T$ of types $1^\circ - 3^\circ$. The intuitively obvious invariance of the function $S$ with respect to “distortions” follows from Cavalieri’s principle (see “Algebra and the beginnings of analysis 10”, paragraph 107). This means that the function $S$ is convenient. From already known convenient functions, you can get new ones using the following rule.

Dilation 3. For any function $F \in \Phi$ we denote by $nF$ the funcra obtained from $F$ by dilating $n$ times relative to the origin. Prove that if $f \in Y$, then the function $f_n$ assigning to each funcre $F$ the number $n(F)$ is also convenient.

In particular, the function $N_n$, which assigns the funcre $F$ to the number $n(F)$, is convenient.

Task 2. Prove that every convenient function $f$ has the following properties:

B) $f$ takes the same value on all integer segments $I$, maximizing that $N(I) = 2$.

Note that the choice of axioms describing many convenient functions is largely arbitrary. We have proposed a set of axioms that is most easily generalized to the three-dimensional case; but it would be possible to get by with fewer axioms. Here's an example.

Task 3. Let us denote by $Y'$ the set of additive functions that are invariant under transformations of type $1^\circ - 2^\circ$ and added properties B). Prove that $Y' = Y$.

This problem should be solved after all convenient functions have been found.

⟦folio 18⟧

Figure 8. $F = F_1 \cup F_2$.

Another example of a convenient function
Can the main theorem be used to prove Pick's formula? The trouble is that the function $B$ is so far defined only on the set of real integer polygons. How to determine it on segments and points? If we want to extend $B$ to a convenient function on Ф, then from figure 8 it is clear that we should put $B(I) = B(F_1) + B(F_2) - B(F)$, and from the same figure it is clear that the right side of this equality is $2 + 2 \cdot (\text{число неконечных мочек отрезка } I)$. Finally, if $X$ is a dot, then for the same reason we should put $B(X) = 0$.

The law does not have 4 (oral). Prove that the function $B$ defining above is indeed convenient.

Let us now prove Peak's formula. From the definition of the function $B$ it follows that the question mark in the sixth row of Table 1 can be replaced by $B$. But above we found out that this line corresponds to the function $2N$ - $2E$ - $2S$. This means, by the main theorem, $N$—$E$—$B/2 = S$.

The question is a warning. Why doesn’t it follow from the equality $\vec{R} = \vec{B}$, where $R$ is a function from control 2, that $R = B$?

Step 4 - generalize formula 6) and Peak’s formula.

Let $e, f, g, h$ be four convenient functions, $e, f, g, h$ be the corresponding four vectors in space. However, one of them can always be represented as the sum of the other three with real coefficients. According to the main theorem, the same is true for the original functions. By choosing various convenient functions (certain purely geometric ones) as $e, f, g, h$, we will obtain new geometric formulas. Let us express, for example, $B(F)$ through $N(F)$ and $N(2F)$. Let's take four convenient functions $B, E, N, N_2$. We will look for the numbers $c_1, c_2, c_3, c_4$ as well as $B = c_1E + c_2N + c_3N_2$. This task is evidenced by the solution of the following control system (see Table 1):

$$\begin{cases} 0 = c_1 + c_2 + c_3, \\ 2 = c_1 + 2c_2 + 3c_3, \\ 3 = c_1 + 3c_2 + 6c_3. \end{cases}$$

Solving it, we obtain $c_1 = -3, c_2 = 4, c_3 = -1$, i.e. $\vec{B} = 4\vec{N} - \vec{N}_2 - 3\vec{E}$. This means that for any integer polygon $F$

$B(F) = 4N(F) - N(2F) - 3$.

The law does not have 4 (oral). Prove that the function $B$ defined above is indeed convenient.

§ 5. Remarkable functions on the set of spatial integer funcures

An integer function (or simply a figure) in three-dimensional space is an integer function, an integer segment, an integer polygon, or an integer polygon. We denote sets of integer funcures, as in the two-dimensional case, by $\Phi$.

We give a strict definition of a convenient function on the set $\Phi$ in the “Appendix”. What will be important for us now is that the function $E, N, N_n, V$ turns out to be convenient. Let $A_1, A_2, A_3, A_4$ be points in three-dimensional space with coordinates $(0; 0; 0), (1; 0; 0), (0; 1; 0), (0; 0; 1)$. Let $X_1$ be a point $A_1, X_2$ be a segment $A_1A_2, X_3$ be a triangle $A_1A_2A_3, X_4$ be a tetradron $A_1A_2A_3A_4$.

Each convenient function $f$ is comparable with four numbers - its values ​​on the function $X_1, X_2, X_3, X_4$. What four are obtained for the functions $V, E, N, N_2, N_3$ known to us is shown in lines 1-5 of Table 2.

Let us also assume that for convenient functions on the set $\Phi$ the notation of the main theorem from § 4 is valid:

If $h$ is a convenient function on Φ, and $h(X_1) = h(X_2) = h(X_3) = h(X_4) = 0$, then the function $h$ is the point of zero action.

⟦folio 19⟧

§ 6. Appendix

Proof of the main theorem.

If $X$ is an integer point, then by parallel intersection it can be transferred to the point $X_1$. Therefore $h(X) = h(X_1) = 0$.

If $I$ is an integer segment and $N(I) = 2$, then according to the solution to Problem 2 $h(I) = h(X_1) = 0$.

If $N(I) > 2$, then we divide the segment $I$ by the point $X$ into two segments $I_1$ and $I_2$ such that $N(I_1) < N(I)$, $N(I_2) < N(I)$. According to A), $h(I) = h(I_1) + h(I_2) - h(X) = h(I_1) + h(I_2)$. Taking the indication, we obtain that $h(I) = 0$ for any integer triangle $F$. From property A) and figure 5 it follows that this equality will be valid if $h$ vanishes on all rectangles on the side parallel to the coordinate axes parallel to the coordinate axes.

It turns out that if $h$ vanishes on the rectangle from the side parallel to the coordinate axes, parallel to the coordinate axes, then $h$ vanishes on the rectangle of the triangle $F$. From property A) and figure 5 it follows that this equality will be valid if $h$ vanishes on all rectangles on the side parallel to the coordinate axes parallel to the coordinate axes.

It turns out that if $h$ vanishes on the rectangle from the side parallel to the coordinate axes, parallel to the coordinate axes, then $h$ vanishes on the rectangle of the triangle $F$. From property A) and figure 5 it follows that this equality will be valid if $h$ vanishes on all rectangles on the side parallel to the coordinate axes parallel to the coordinate axes.

It turns out that if $h$ vanishes on the rectangle from the side parallel to the coordinate axes, parallel to the coordinate axes, then $h$ vanishes on the rectangle of the triangle $F$. From property A) and figure 5 it follows that this equality will be valid if $h$ vanishes on all rectangles on the side parallel to the coordinate axes parallel to the coordinate axes.

Now let $F$ be an arbitrary integer polygon. Dividing $F$ by the diagonal $I$ into two polygons $F_1$ and $F_2$ with fewer sides than $y$, we obtain, according to A), that $h(F) = h(F_1) + h(F_2) - h(I) = h(F_1) + h(F_2)$. Accepting the indication, we find that it is sufficient to prove the equality $h(F) = 0$ for any integer triangle $F$. From property A) and figure 5 it follows that this equality will be valid if $h$ vanishes on all rectangles from the side parallel to the coordinate axes, parallel to the coordinate axes.

Indeed, let us divide such a rectangle $F$ by diagonal $I$ into triangles $F_1$ and $F_2$. Then $h(F) = h(F_1) + h(F_2)$. Suppose $h(F) = 0$, then $h(F_1) + h(F_2) = 0$. Let us prove that $h(F_1) = h(F_2)$. Let $F'_1$ be a triangle symmetrical to $F_1$ relative to one of the coordinate axes, and $F'_2$ be a triangle symmetrical to $F_2$ relative to the other coordinate axis. Since $h$ is invariant with respect to the symmetric we obtain $h(F_1) = h(F_1')$, $h(F_2) = h(F_2')$. But $F'_1$ can be translated into $F'_2$ pa-

Fig. 9.

⟦folio 20⟧

Fig. 10.

rappel transfer, therefore $h(F_1') = h(F_2')$. Hence $h(F_1) = h(F_2)$ and, therefore, $h(F_1) = h(F_2) = 0$.

It remains to show that $h$ vanishes on rectangles on the side parallel to the coordinate axes. Dividing such a rectangle into smaller rectangles, we find by induction that it is sufficient to prove that $h$ vanishes on the unit square $X_3 \cup Y_3$, depicted in figure 10. According to A), $h(X_3 \cup Y_3) = h(X_3) + h(Y_3)$. By the conditions of Theorem $h(X_3) = 0$. Above we proved that $h(Y_3) = h(X_3)$, therefore $h(Y_3) = 0$. Hence $h(X_3 \cup Y_3) = 0 + 0 = 0$. The proof of the theorem is legal.

Solving problem 2.

We will say that the function $F_1$ and $F_2$ are equivalent (denoted: $F_1 \sim F_2$) if the function $F_1$ is obtained from the functions $F_2$ by an integer of admissible transformations. It is clear that every convenient function takes the same value on equivalent functions. Let us denote by $I_a,b$ the segment with ends $(0; 0)$ and $(a; b)$. Let us show that every segment $I_a,b$ is equivalent to the segment $I_{n,0}$. Transformation $1^\circ$ any segment $I$ is converted to $I_a,b$. Having made the transformations $2^\circ$ and $3^\circ$, we can assume that $a \geq b \geq 0$. If $b > 0$, then consider all the segments that can be obtained from $I_a,b$ using “warps”. From figure 11 it is clear that among such segments there is necessarily a segment $I_c,b$, where $0 \leq c < b$. Having done $3^\circ$, we get that $I_a,b \sim I_b,c$. Repeating the same discrepancies several times, we obtain that $I \sim I_{n,0}$. If it is additionally known that $N(I) = 2$, then $N(I_{n,0}) = 2$, i.e. $n = 1$. Thus, the convenient function $f$ on any segment $I$ for which $N(I) = 2$ takes the same value as the segment $I_{1,0}$.

Determination of convenient functions on Ф in the spatial case.

Aditivity. The function $f$ on the set $\Phi$ is called $\Phi$ on the function $F \in \Phi$ on the function $F_1$, ..., $F_k \in \Phi$, satisfying the conditions $F_1 \cap F_2 \cap \dots \cap F_k \neq \emptyset$ and $V(F_i \cap F_j) = 0$ for $i \neq j$,
