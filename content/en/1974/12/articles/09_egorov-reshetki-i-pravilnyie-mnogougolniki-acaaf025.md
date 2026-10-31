---
id: 1974-12-egorov-reshetki-i-pravilnyie-mnogougolniki-acaaf025
issue: kvant_1974_12
year: 1974
number: "12"
title: Lattices and regular polygons
authors:
  - Егоров А. А.
rubric: osnovnye-stati
page_first: 28
page_last: 35
page_labels: 26-33
tag: 92BR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 77facecd8aa471145879721c33c9ce9afe445d354a82fd0ffedd66ebf004a603
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/09_egorov-reshetki-i-pravilnyie-mnogougolniki-acaaf025.md
source_content_sha256: 06b145604d4e4271abc96c446f21e19ab8818723e601deb36303825119c2054c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

This article examines three test-related questions.
1) Is it possible to arrange a regular $n$-gon on a sheet of lined paper - in a straight or oblique square - so that its vertices fall at the points of intersection of the lines?
2) At what angles $\alpha$, commensurate with the total - that is, containing an integer or rational number of degrees, are the values ​​of sine, cosine or tangent $\alpha$ rational?
3) The position can be the center of a regular $n$-gon, which is cut by rolling along a plane (the last question was the content of problem M252 from “Task «Kvant»”).

§ 1. Point lattices on the plane
Let us consider a grid on the plane formed by two families of parallel lines, cutting the plane into identical parallelgrams (Fig. 1).

We call the set of all vertices of these parallelgrams *urine lattice*, the vertices themselves are lattice nodes, and any of the partition parallelgrams is called the main partition parallelgram, or the parallelgram *generating* the lattice.

Note that the same lattice can be obtained from different grids of lines: figure 2 shows the so-called *integer lattice*, that is, a set of points that have integer coordinates in the Cartesian coordinate system. An integer lattice, together with a grid of lines parallel to the coordinate axis, can be thought of as an infinite sheet of checkered paper (then the main parallelgram will be a square with side 1). The same integer lattice can be obtained with straight red wires (then the main parallelgram is the parallelgram *ABCD*).

Thus, the concept of a basic parallelgram lattice is related

Fig. 1, Fig. 2.

⟦folio 27⟧

not only with the lattice itself, but also with the network of lines that generate this lattice.

Among the simplest properties of lattices, we note the following for now.

1°. Any parallel transfer that transfers a certain lattice node to another node transfers the lattice into itself.

2°. (Lemma about the fourth vertex of a parallelogram). If three vertices of a parallelogram are nodes of some lattice, then the fourth vertex is also a node of this lattice.

3°. If a straight line is drawn through arbitrary two lattice nodes Q and R, then this straight line will pass through an infinite number of nodes. In this case, all distances between neighboring nodes lying on a straight line will be equal (see Fig. 1).

4°. If a parallelogram with vertices at the nodes of a certain lattice does not contain other nodes on the sides and inside itself, then it generates this lattice.

In practice
1. Prove property $1^\circ - 4^\circ$.
2. Let $a$ and $b$ be any real numbers. Prove that the set of all points with coordinates $(ka, lb)$, where $k$ and $l$ are integers, is a lattice.

An important property of lattices is reflected in the following problem - a joke:
At some node $A$ of the lattice there is a hunter, and at the remaining nodes there are identical and identically located hares (see Fig. 3, a). The hunter will aim the arrow (the trajectory of the bullet is a ray emerging from point $A$). Will he return home with the dobie? (Hares are called “thick”).

It is clear that if the bullet trajectory passes through a node (other than point $A$), then the hare sitting at this node will be killed. Therefore, the only case of interest is when node $A$ is the only one on the bullet’s trajectory; it turns out that in this case some hare will be killed. The proof is contained in the following lemma.

⟦folio 28⟧

It is easy to see that among all possible pairwise distances between the nodes of any lattice there is a smallest one (prove!).

This property, together with the property of the 2° lattice, can be taken as a certain lattice.

Theorem. Let a set M on the plane have the following properties:

a) the distance between any two of its points is not less than some positive number d;

b) if three points A, B, C of a set M are vertices of some parallelogram ABCD, then the colored vertex D of this parallelogram belongs to the polygon M.

Then M is a lattice.

Proof. Let us take an arbitrary point B belonging to the multiplicity M.

Let A be the point from M closest to B (Fig. 4, a); such a point exists, since all pairwise distances between points of the polygon M are greater than d).

Draw a straight line through points A and B. Among the polygon points M that do not lie on this line, we choose the point C closest to point B - point C - and construct a parallelogram ABCD. By virtue of property 6), the point D also belongs to the polygon M.

Let us construct a lattice generated by the parallelogram ABCD. Let us prove that the polygon M coincides with the constructed lattice.

From property 6) of the polygon M it follows that all nodes of this lattice belong to it

Fig. 4.

Fig. 5.

Razzhentse 3. Prove it.

Pozny only needs to check that neither on the boundary nor inside the parallelogram ABCD are there any polygon points M different from its vertices.

This is almost obvious: if the point S lies inside the parallelogram (Fig. 4, 6), then at least one of the angles $\widehat{ASB}$, $\widehat{BSC}$, $\widehat{CSD}$ and $\widehat{ASD}$ will be obtuse or straight, and therefore the distance from S to one of its vertices turns out to be less than some of its sides (if S lies on the boundary - the same thing); Let, for example, be the distance SC. Let us construct a parallelogram BCSS' (S' belongs to M). Then BS' is less than either BC or BA, but this contradicts the choice of either point C or point A.

Find out the rest of the cases yourself.

The theorem has been proven.

Do you get married?

4. Let $\alpha$ be an arbitrary irrational number. Prove that for any $\epsilon > 0$ and any real number $\beta$ there are integers m and n such that $|m\alpha + n - \beta| < \epsilon$.

5*. Prove that the decimal notation of the number $2^n$ can begin with any predetermined combination of digits.

§ 2. Regular polygons

Let's take a sheet of checkered paper. It is clear that a square with vertices at the nodes of such a lattice can be drawn in many ways (Fig. 5, a). Is it possible to draw a regular triangle on checkered paper? Regular hexagon?

⟦folio 29⟧

It turns out you can't.

Exercise 6. Prove it.

At the same time, it is easy to construct a lattice on which a regular triangle can already be “placed” (Fig. 5, 6).

The question is, what about the rest of the regular polygons? Is there, for example, a lattice on which it would be possible to “place” a regular pentagon so that all its vertices turn out to be nodes of this lattice?

It turns out that there is no such grid. Indeed, suppose that we managed to construct a lattice so that the vertices of a regular pentagon are at its nodes (see Fig. 6). Let's draw the diagonals of this pentagon. By Lemma 2 § 1, the intersection points of the diagonals are lattice nodes: each of them serves as the fourth vertex of a parallelogram, the other three vertices of which are lattice nodes (point $A_1$, for example, is the vertex of parallelogram $A_1CDE$). These points form a regular pentagon with sides $k = \frac{A_1B_1}{AB}$ times the size of the original pentagon. Drawing the diagonals of the new pentagon, we get an even smaller pentagon with vertices at the nodes of our lattice, and so on. Eventually, the side of the pentagon becomes less than the minimum distance between lattice nodes,

Fig. 6.

and this is in contradiction with the fact that the vertices are pentagons - lattice nodes.

Exercise 7. Find $k$.

So, a regular pentagon cannot be “drawn” on any lattice.

Let us prove that the situation is exactly the same with the remaining regular $q$-gons for $q \geq 7$.

The proof is based on the same idea; it is assumed that a regular $q$-gon with vertices at the lattice nodes exists, and a smaller $q$-gon with vertices at the nodes is constructed. The construction process is then repeated. In the end, we get a regular $q$-gon with sides less than the minimum distance between the nodes. Therefore, we only need to indicate how, given a regular $q$-gon with vertices at lattice nodes, we can construct a smaller regular $q$-gon, the vertices of which will also be at the nodes of our lattice.

Let $A_1, A_2, \dots, A_q$ be the nodes of some lattice that are the vertices of a regular $q$-gon, and let $M$ be an arbitrary lattice node (Fig. 7). Let us plot from the point $M$ the segments $MA'_1, MA'_2, MA'_3, \dots, MA'_q$, equal, parallel and also on-

⟦folio 30⟧

straightened as the side $A_qA_1, A_1A_2, A_2A_3, \dots, A_{q-1}A_q$ of the called polygon. The points $A'_1, A'_2, A'_3, \dots, A'_q$ are lattice nodes, since each of them is the fourth vertex of a parallelogram, the other three vertices of which are nodes.

It is easy to see that the polygon $A'_1A'_2 \dots A'_q$ is regular, and the length of its side is $k_q = \frac{|A_1A_2|}{|OA_1|}$ times greater than the length of the side of the original $q$-gon.

Thus, the question of regular polygons “fitting” on exact lattices is completely resolved: the maximum of a polygon is molleco squares, regular triangles and regular hexagons.

I have no practice
8. Find $k_q$.
9. Are there any lattices other than an integer one on which a square can be placed?
10. Give an example of a lattice, different from the one shown in figure 5, 6, on which a regular triangle can be placed.
11. Is there a grid on which both a square and a regular triangle fit?
12. (N.B. Vasiliev). Parallel lines are drawn on the plane at equal distances from each other (“ruled notebook”). Can regular $n$-gons be right-handed on the plane so that all the vertices lie on the drawn straight lines?

§ 3. Irrational value of trigonometric functions.

Can you answer this question: are the numbers $\sin 1^\circ, \cos \frac{\pi}{19}, \tg \frac{7}{55} \pi$ rational or irrational?

Or this: are the numbers $\pi$ and arctg $\frac{1}{3}$ comparable?

*) Recall that two numbers $\alpha$ and $\beta$ are called commensurate if their ratio is rational, that is, $\frac{\alpha}{\beta} = \frac{p}{q}$ where $p$ and $q$ are the numbers of the number and $q > 0$.

And in general: for what angles $\alpha = \frac{p}{q} \pi$ ($p$ and $q$ are integers) the following numbers will be rational: a) $\cos \alpha$; b) $\sin \alpha$; b) $\tg \alpha$?

It is clear that $\cos \alpha$ is rational for $\alpha = \frac{k\pi}{2}$ and $\alpha = \frac{\pi}{3} (3k \pm 1)$;

$\sin \alpha$ — for $\alpha = \frac{k\pi}{2}$ and $\alpha = \frac{\pi}{6} (6k \pm 1)$;

$\tg \alpha$ - for $\alpha = k\pi$ and $\alpha = \pm \frac{\pi}{4} + k\pi$ ($k$ - integer).

We see that for the remaining $\alpha = \frac{p}{q} \pi$ the values ​​of all three functions are irrational.

To prove it, we need the following simple facts from trigonometry:

1. For every natural number $n$ the function $\cos nx$ is a polynomial of the $n$th degree in $\cos x$ with integer coefficients, that is
   $$\cos nx = P_n(\cos x),$$
   where $P_n(y)$ is a polynomial with integer coefficients of degree $n$.

2. The function $\sin nx$ is the product of the function $\sin x$ by some polynomial of degree $n - 1$, with respect to $\cos x$, with integer coefficients, that is
   $$\sin nx = \sin x \cdot Q_{n-1}(\cos x),$$
   where $Q_{n-1}(y)$ is a polynomial with integer coefficients of degree $n - 1$.

Practice 13. Prove these statements.

Let us note simple consequences:
a) if $\cos x$ is a rational number, then $\cos nx$ can be a rational number, and the numbers $\sin x$ and $\sin nx$ are the same (for $\sin nx \neq 0$);
b) if $p$ and $q$ are relatively prime numbers and $\cos \frac{p}{q}$ π is a rational number.
Let us prove 6) (property a) is obvious.
Note that if $p$ and $q > 1$ are coprime, then there exists a natural number

⟦folio 31⟧

Let $A_0, A_1, A_2, \dots, A_{2q-1}$ be the points of intersection of these rays with the unit circle (Fig. 8).

The polygon $A_0, A_1, A_2, \dots, A_{2q-1}$ is regular; point $A_k$ has the following coordinates:

$$\left( \cos \frac{k}{q} \pi, \sin \frac{k}{q} \pi \right).$$

Since $\cos \frac{\pi}{q}$ is rational, the abscissa of the point $A_k$ is the number of the rational number $Q_k \left( \cos \frac{\pi}{q} \right) = \frac{r_k}{s_k}$ by the number $\sin \frac{\pi}{q}$ (see Exercises 13 and 14; $k=1, 2, \dots, 2q-1$; coordinates of the point $A_0=(1, 0))$.

So,

$$A_k = \left( \frac{m_k}{n_k}, \frac{r_k}{s_k} \cdot \sin \frac{\pi}{q} \right).$$

Let us reduce all fractions $\frac{m_k}{n_k}, \frac{r_k}{s_k}$ to a common value; let's denote it by $D$. Then

$$A_k = \left( \frac{M_k}{D}, \frac{N_k}{D} \cdot \sin \frac{\pi}{q} \right),$$

$M_k$ and $N_k$ are integers, $k=1, 2, \dots, 2q-1$.

Let us now consider all points with coordinates

$$\left( \frac{i}{D}, \frac{j}{D} \cdot \sin \frac{\pi}{q} \right)$$

($i$ and $j$ are integers) - these points form a lattice (see Exercise 2), and the vertices of our regular $2q$-gon $A_0 A_1 \dots A_{2q-1}$ are its nodes. But this cannot be (see § 2), since $2q \geq 8$. Therefore, our assumption that at $q>3$ the number $\cos \frac{\pi}{q}$ is rational was incorrect, and therefore all the numbers $\cos \frac{p}{q} \pi$ ($q>3$, $p$ and $q$ are coprime) are irrational!

⟦folio 32⟧

Fig. 9.

Exercise 15. Let $q \geq 3$, $p$ and $q$ be coprime. Prove that

a) the numbers $\sin \frac{p}{q}$ for $q \neq 6$ are irrational;

b) the same for numbers $\lg \frac{p}{q}$, if $q \neq 4$.

The results obtained can also be formulated as follows: the numbers $\arcsin \frac{p}{q}$, $\arccos \frac{p}{q}$ with $\frac{p}{q} \neq 0, \pm \frac{1}{2}, \pm 1$, as well as the numbers $\arctg \frac{p}{q}$ with $\frac{p}{q} \neq 0, \pm 1$ (and coprime $p$ and $q$) are incommensurable with the number $π$.

§ 4. Solution of Problem M252

So problem M 252: a) On the plane lies a regular auxiliary with side a. It is allowed to “roll” along the plane, turning it over (symmetrically) relative to any side. Prove that for any point $A$ of the plane and any $\varepsilon > 0$ it is possible to roll the object into such a position that its center is located from the point $A$ at a distance less than $\varepsilon$.

b) Solve a similar problem for a regular rectangle.

c) For which regular $q$-receivers is a similar statement true?

We will present two solutions to this problem. The first solution will describe the irrationality of the numbers $\cos \frac{2\pi}{q}$ for $q > 4, q \neq 6$. The second is based on the theorem proved in §1.

First of all, we note that the statement of the problem is not true for regular triangles and hexagons, as well as for a square: in these cases, the points at which the center of the corresponding polygon falls as a result of “rolling” form a lattice (this is proof!). It turns out that for all other regular $q$-walkers the statement of the problem is correct - we will prove that whatever the points $A$ and $\varepsilon > 0$ are, the center of any regular $q$-walker at $q \neq 3, q \neq 4, q \neq 6$ after a certain number of “rolls” falls into a circle of radius $ε$ with the center at the point $A$.

Before proceeding with the proof, let us clarify some properties of the set $M$ of those points in the plane at which the center of the regular $q$-walker $P$ passes after the fourth number of “rolls”. Note that the $q$-walker $P'$, obtained from $P$ after the fourth number of “rolls”, is located in such a way that its sides are parallel to the sides of the original one. Therefore, we can consider that $P'$ is obtained from $P$ by parallel transfer.

Lemma 1. If the vertices of a parallelogram $A, B$ and $C$ belong to $M$, then its colored vertex $D$ also belongs to $M$.

Proof. Let the points $A, B$ and $C$ belong to $M$ (see Fig. 9) and $D$ be the fourth vertex of the parallelogram. It is clear that we can go from point $C$ to point $D$, carrying out the same parallel transitions as when moving from point $B$ to point $A$.

Fig. 10.

⟦folio 33⟧

Lemma 2. The set $M$ transforms into itself when rotated by an angle $\frac{2\pi}{q}$ around any of its points.

Proof. Let's construct a chain of $q$-gons adjacent to each other along the side and “connecting” our $q$-gon with a center at a given point $O$ with a $q$-gon with a center at any other point $A$ set $M$ (Fig. 10). When rotated by an angle $\frac{2\pi}{q}$ around point $O$, this chain of polygons transforms into another chain that connects the original polygon with a polygon whose center is point $A'$, obtained from $A$ by rotation. Therefore, the point $A'$ also belongs to the polygon $M$.

Let's move on to the proof of the statement made.

First proof. Let us first examine the case of correct memory. (We will assume that the apothem of the polygon is 1.)

Let us introduce a coordinate system on the plane as shown in figure 11, and see what happens to the coordinates of the centers when “rolling” through the sides of the polygon $P$.

When “rolling” along the $Ox$ axis, the ordinals of the centers do not change, and the abscissas increase or decrease by 2. When rolling along the bissertrix of the first coordinate angle, the coordinates of any points increase or decrease by $\sqrt{2}$.

If we take $n$ steps along this bissertrix to the right - up, then $m$ steps along the $Ox$ axis to the left and $m$ steps along the $Oy$ axis down, then we will get to point $N$ with coordinates $(n\sqrt{2}-2m, n\sqrt{2}-2m)$ (see Fig. 11); since $\bar{2}$ is an irrational number, then (see § 1) one will also find natural $m$ and $n$, which

$$0 < n, \bar{2} - 2m < \frac{\varepsilon}{4},$$

where $\varepsilon$ is any positive number.

Note that we can also attach to point $N'$, obtained from $N$ by rotating by angle $45^\circ$ clockwise, and to point $N''$, resulting from $N$ by rotating by angle $45^\circ$ counterclockwise.

Let us complete the triangle $ON'N''N''$ and consider the lattice generated by it.

Since the sides and diagonals of the square $ON'N''N''$ are less than $\varepsilon$ (see (*) and figure 11), then in every circle $L$ of radius $\varepsilon$ there is at least one lattice node. But according to Lemma 1, all nodes of this lattice can be obtained by “rolling” from the center of the memory.

This proves everything about memories.

For the remaining polygons (regular, of course), the proof follows the same scheme.

Second solution. This solution is somewhat shorter than the first and, perhaps, more visual, but it uses a difficult theorem from § 1.

As we have seen, it is enough to prove that in the set $M$ one can find how many angularly close points.

Suppose that this is not the case, that is, suppose that between the points of the polygon $M$ there is more than some positive number $d$.

By the theorem from § 1 and Lemmas 1 and 2, a polygon is a lattice, which, moreover, transforms into itself when rotated through an angle $\frac{2\pi}{q}$. It immediately follows that there exists a regular $q$-gon with vertices at its nodes, and this is only possible for $q = 3$, $q = 4$ or $q = 6$.

The decision is legal.
