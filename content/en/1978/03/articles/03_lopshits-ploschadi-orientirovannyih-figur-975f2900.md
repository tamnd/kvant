---
id: 1978-3-lopshits-ploschadi-orientirovannyih-figur-975f2900
issue: kvant_1978_3
year: 1978
number: "3"
title: Areas of oriented figures
authors:
  - Лопшиц А. М.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 4, 7, 8, 9
tag: 3BBG
lang: en
source: kvant_digital
extraction: vision
content_sha256: bed01a2790537751ffa8aed3cf340a96a6a23ea99806f31e166a051fd1b78fc6
prompt_sha256: draft-1
translated_from: content/ru/1978/03/articles/03_lopshits-ploschadi-orientirovannyih-figur-975f2900.md
source_content_sha256: 5ad201fd211f7148c6c0ee90eb674885e18455bdc1e7cd23294d54f6ad202d83
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A. Lopshitz

Areas of oriented figures

The reader of our magazine often came across various problems in which areas were discussed. Their solutions were also obtained in a variety of ways. In «Kvant» No. 3 for 1977, we talked about the idea of ​​Möbius - to measure the areas of oriented polygons not only by positive ones, as is done in school, but also by negative numbers. We promised to return to the consideration of these issues and introduce the reader to the solution to the problem posed by Mobius and the problems that naturally continue them. Currently, we propose to first measure the areas of oriented polygons—this is the focus of the first part; the conditions of the material presented in it will make the reader prepared to independently solve not only those problems about areas that were posed in our magazine, but also many others.

1. Basic properties of areas of oriented figures

1. The need to measure the areas of flat figures was, as historians believe, one of the basic principles of the emergence and development of geometry: the ancient Egyptians had to restore - after the next flood of the Nile - the boundaries of their land plots flooded by spring waters, and change their areas again.

Already in the village class, the student learned the simplest rule for finding the areas of parallelograms, triangles, and trapezoids. The mathematical derivation of these rules used polygons whose area is equal to the sum of the areas of triangle $A_1A_2A_3$ and polygon $A_1A_3A_4 \dots A_n$:

$$\text{пл. } A_1A_2 \dots A_n = \text{пл. } A_1A_2A_3 + \text{пл. } A_1A_3A_4 \dots A_n.$$

One glance at figure 1, and it seems enough to accept this property, i.e., according to the fact that the mathematical sentence expressed by it is real. However, for the polygon shown in figure 1, 6, this property does not hold; in this case

$$\text{пл. } B_1B_2 \dots B_n = \text{пл. } B_1B_3B_4 \dots B_n - \text{пл. } B_1B_2B_3.$$

Therefore, we will have to change the formulation: the area of ​​the polygon $A_1A_2 \dots A_n$ is equal to either the sum or the difference of the areas of the polygon $A_1A_3A_4 \dots A_n$ and the triangle $A_1A_2A_3$.

This statement holds true for both convex and non-convex polygons, but, alas! - a significant drawback: to use it, you need to look at the drawing every time and select the “plus” or “minus” sign.

2. The way out of this situation was indicated (back in 1827) by the sign geometer Möbius. He proposed to assign a positive value to the area of ​​the triangle $B_1B_2B_3$ only if

⟦folio 3⟧

the vertices $B_1, B_2, B_3$ are located clockwise (Fig. 2, a), and otherwise (Fig. 2, b), the “area” of triangle $B_1B_2B_3$ is considered to be a negative number, the modulus of which is equal to the total area of ​​this triangle.

The usefulness of this new perspective is clearly illustrated by the following example. If the point $P$ is located inside the triangle $ABC$, then (Fig. 3). pl. $ABC =$ pl. $PAB +$ pl. $PBC +$
+ pl. $PCA$. (*)

However, if the point $P$ is located outside the triangle $ABC$, then this equality must be replaced by another, for example, in the case given in figure 4, and the equality

pl. $ABC =$ pl. $PAB +$
+ pl. $PBC -$ pl. $PCA$.

The reader can easily see that, depending on the location of the point $P$, five more “similar equalities” are valid (Fig. 4, b, b; 5, a, b, b). However, if we use Möbinus’s rule, then, as can be easily verified, “all these” seven equalities can be written in the form (*) (Fig. 6).

So, the correct Möbinus makes it possible to assert that it is fair.

Theorem 1. No matter how the triangle is located in the plane,

⟦folio 4⟧

naka $ABC$ point $P$,
pl. $ABC = \text{пл. } PAB + \text{пл. } PBC + \text{пл. } PCA$.

Instead of seven theorems - one! Is it then possible to agree on the expediency of the Mobinus rule?

3. Let us now give a strict definition of area using the Mobinus rule.

First of all, let us clarify the area of ​​which figures we will be talking about. Let us call an arbitrary closed broken line a multivertex for which the order of vertices $^*$ is indicated.

The notation $\overline{A_1A_2 \dots A_n}$ would mean that vertex $A_2$ follows vertex $A_1$, $A_3$ follows $A_2$, ..., $A_n$ follows $A_{n-1}$ and finally, and very importantly! — $A_1$ follows $A_n$. This order is called circular (or cyclic). From this definition it follows that for decent $n$-vertices $\overline{A_1A_2 \dots A_n}$ can also be denoted as follows: $\overline{A_2A_3 \dots A_nA_1}$. Thus, the entries $\overline{ABC}$, $\overline{BCA}$, $\overline{CAB}$ mean the same ordered three-vertex, and the entries $\overline{BAC}$, $\overline{ACB}$, $\overline{CBA}$ mean a different ordered three-vertex. We will say that the three-vertex $\overline{ABC}$ and $\overline{BAC}$ are oriented against the position.

It is for oriented (ordered) multivertex structures that we want to define the concept of area.

Let's do it this way. Let us indicate some of its main properties. These properties will not be proven, but all other statements about the area of ​​oriented multivertex structures will be deduced from these properties. (This method of definition, understood in mathematics, is called axiomatic.) So, we believe that each multivertex $\overline{A_1A_2 \dots A_n}$ is assigned a certain number - pl. $\overline{A_1A_2 \dots A_n}$; it can be not only positive, but also negative, and even equal to zero; in this case the following properties are fulfilled:

(I) $\overline{ABC} = -\text{пл. } \overline{BAC}$;

(II) $\overline{A_1A_2A_3 \dots A_n} = \text{пл. } \overline{A_1A_2A_3} + \text{пл. } \overline{A_1A_3A_4 \dots A_n}$. If we take into account that the multivertex $\overline{A_1A_2 \dots A_n}$ coincides with the multivertex $\overline{A_2A_3 \dots A_nA_1}$, then this property can be written as follows:

(II') $\overline{A_2A_3 \dots A_nA_1} = \text{пл. } \overline{A_2A_3A_4} + \text{пл. } \overline{A_2A_4 \dots A_nA_1}$.

Now let’s return to Theorem 1. The underbelly of correspondences (I) and (II), it can already be built and proven! In fact, no matter how the points $PABC$ are located in the plane of four, the equalities take place - according to (II) and (II'): pl. $\overline{PABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC}$; pl. $\overline{PABC} = \text{пл. } \overline{ABCP} = \text{пл. } \overline{ABC} + \text{пл. } \overline{ACP}$ and therefore pl. $\overline{PAB} + \text{пл. } \overline{PBC} = \text{пл. } \overline{ABC} + \text{пл. } \overline{ACP}$, i.e. pl. $\overline{ABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC} - \text{пл. } \overline{ACP}$. Taking into account that by virtue of (I), pl. $\overline{ACP} = -\text{пл. } \overline{PCA}$, we get pl. $\overline{ABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC} + \text{пл. } \overline{PCA}$.

Now try to figure out the necessary notation for Theorem 1:

Theorem 2. No matter how the point $P$ is located in the plane of the ordered multivertex $\overline{A_1A_2 \dots A_n}$, the equality pl. $\overline{A_1A_2 \dots A_n} = \text{пл. } \overline{PA_1A_2} + \text{пл. } \overline{PA_2A_3} + \dots + \text{пл. } \overline{PA_nA_1}$.

Derive a corollary from this

⟦folio 7⟧

Fig. 12, a.

Problem 4. Prove $(A_3)$ if
a) $\lambda$ is a positive integer,
b) $\lambda$ is a rational positive number,
c) $\lambda$ is a negative rational number.

The correspondence $(A'_3)$ $S(\lambda AB, MN) = S(AB, MN) \cdot \lambda$ is also valid. (You should only use $(A_3)$ and $(A_2)^*$.))

To conclude this list of formulas, we will show that they imply a very important theorem for the entire theory of planes:

If the segments $AB$ and $CD$ are collinear (i.e., either lie on parallel lines or on the same line), then

$$S(\overrightarrow{AB}, \overrightarrow{CD}) = 0^*.$$

Indeed, due to $(A_2)$ we have

$$S(\overrightarrow{AB}, \overrightarrow{AB}) = -S(\overrightarrow{AB}, \overrightarrow{AB}),$$

and therefore

$$S(\overrightarrow{AB}, \overrightarrow{AB}) = 0.$$

If the segment $\overrightarrow{CD}$ is collinear with the segment $\overrightarrow{AB}$, then $\overrightarrow{CD} = \lambda \overrightarrow{AB}$; That's why

*) The validity of the formulas $(A_3)$ and $(A'_3)$ for irrational $\lambda$ cannot be established based on the formula $(A_1)$. In order to extend these formulas to irrational $\lambda$, it is necessary to impose neokotny restrictions on the expression $S(\overrightarrow{AB}, \lambda MN)$ as a function of $\lambda$. It is enough, for example, to assume that this function is monotonic.

**) Yes, this is very cool! - the reader will say.

After all, the parallelogram $PQRS$, built on collinear segments, is expressed as follows: all its vertices lie on the same straight line and therefore its area is zero. However, using the word “posto” in this “de-wonder” is logically not at all justified - only in those cases we can say “posto” when we rely either on the main provisions of I, II, III, or on theorems already proven with their help.

⟦folio 8⟧

III. Calculation of the oriented plane of an arbitrary ordered planar multivertex

7. Let $O$ be an arbitrarily chosen point of the plane, and let the vectors $\overrightarrow{OE}_1$ and $\overrightarrow{OE}_2$ located in it be non-circular.

If $x_1$ and $x_2$ are two arbitrary numbers, then the vector $x_1\overrightarrow{OE}_1+x_2\overrightarrow{OE}_2$ is called a linear combination of the vectors $\overrightarrow{OE}_1$ and $\overrightarrow{OE}_2$.

Let

(1) $x_1\overrightarrow{OE}_1+x_2\overrightarrow{OE}_2=\overrightarrow{OP}$.

Thus, specifying an ordered pair of numbers ($x_1; x_2$) simultaneously determines the point $P$ (corresponding to this pair). It is common to say that $x_1$ is the first coordinate of the point $P$, $x_2$ is the second coordinate of the point $P$ relative to the coordinate system $\langle O; E_1, E_2 \rangle$ defined by the origin $O$ and the “scale vectors” $\overrightarrow{OE}_1$ and $\overrightarrow{OE}_2$.

In the following presentation, we will assume that the point $O$ and the vectors $\overrightarrow{OE}_1$ and $\overrightarrow{OE}_2$ are fixed and we will use notation (1) together with the short notation: $P=(x_1, x_2)$.

Problem 6. Where are the points of the plane ($O, E_1, E_2$):

a) whose first coordinate (in the system $\langle O; E_1, E_2 \rangle$) is some positive (negative) number, and the second coordinate is zero,

b) both coordinates of which are positive (negative) numbers,

b) whose first coordinate is positive (negative), and the second coordinate is positive)?

Giving the numbers $x_1$ and $x_2$ all possible values ​​in formula (1), we obtain all possible vectors $\overrightarrow{OP}$ of the plane containing the points $O$, $E_1$, $E_2$; in other words, each point $P$ of this plane has its own pair of coordinates: $x_1; x_2$ (Fig. 13). It is easy to see that they can be calculated using the following formulas:

(2) $x_1 = \frac{\pi l. \overrightarrow{OPE}_2}{\pi l. \overrightarrow{OE}_1 E_2}; \quad x_2 = \frac{\pi l. \overrightarrow{OPE}_1}{\pi l. \overrightarrow{OE}_2 E_1}$.

In fact, multiplying (obliquely!) times

⟦folio 9⟧

IV. The Möbius problem and its products

10. In the article with this title (in the third issue of our journal last year), we proposed to prove that no matter how the pentacles A, B, C, D and E are located in the plane, the area x of the pentagon $\overline{ABCDE}$ is the root of the quadratic equation

(3) $x^2 - x(a + b + c + d + e) + (ab + bc + cd + de + ea) = 0$,

in which a, b, c, d, e are the areas of oriented three-vertex $\overline{ABC}, \overline{BCD}, \overline{CDE}, \overline{DEA}, \overline{EAB}$.

The special interest that this problem arouses is due to the fact that the quintuple $\overline{ABCDE}$ can be non-convex and even one whose sides intersect (Fig. 14); It is therefore not surprising that the numbers a, b, c, d and e can also be negative.

The elegant proof that Möbius gave uses the special mathematical apparatus he depicted - barycentric calculus (barycenter - center of gravity), which Möbius discovered as a result of studying issues of solid body mechanics. Modern vector algebra also arose under the influence of these ideas of Möbius. We will introduce the reader to the vector proof of the Möbius problem - it uses the theory of oriented areas depicted above, more precisely, the “Möbius identity” proved in paragraph 8 - which we will write as follows:

pl. $\overline{ABC} \cdot$ pl. $\overline{ADE}$ +
(4) + pl. $\overline{ADB} \cdot$ pl. $\overline{ACE}$ +
+ pl. $\overline{ABE} \cdot$ pl. $\overline{ACD} = 0$.

Due to the properties of oriented areas pl. $\overline{ABCDE} = x =$ pl. $\overline{ABC}$ +
+ pl. $\overline{ACD} +$ pl. $\overline{ADE} = a +$ pl. $\overline{ACD} +$d;

x = square $\overline{CDE} +$ pl. $\overline{CEA}$ +
+ pl. $\overline{CAB} = c +$ pl. $\overline{CEA} + a$,

x = square $\overline{DEA} +$ pl. $\overline{DAB}$ +
+ pl. $\overline{DBC} = d +$ pl. $\overline{DAB} + b$, and therefore
