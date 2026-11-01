---
id: 1977-5-boltyanskiy-o-ponyatiyah-ploschadi-i-obema-c97d2970
issue: kvant_1977_5
year: 1977
number: "5"
title: On the concepts of area and volume
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 7, 8
tag: N9MW
lang: en
source: kvant_digital
extraction: vision
content_sha256: f70768c1495099cd0beb7bc5bf6a0015a03975c8d947174fd42525c6ee710972
prompt_sha256: draft-1
translated_from: content/ru/1977/05/articles/04_boltyanskiy-o-ponyatiyah-ploschadi-i-obema-c97d2970.md
source_content_sha256: 1fdb16a56646a4eccf37df16d81a8b84f10a41794904005a6e5014341ee85990
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

It is usually said that the area $S(F)$ of a figure $F$ is a number showing how many units of area this figure is “composed” of (a unit of area is taken to be a square whose side is equal to a unit of length). However, such a visual representation cannot serve as an exact mathematical definition of the concept of area. It is unclear, for example, how a circle of a given radius is “made up” from units of area.

One of the ways to clarify the concept of areas is based on the consideration of *palette* - dividing the plane into congested squares. Let the side of a palette square have length 1. At figure 1, the figure $F$ contains a figure composed of 9 palette squares, and is contained in a figure composed of 29 squares; therefore $9 \leq S(F) \leq 29$. For a more accurate estimate, you can use a palette whose squares have sides 1/10 long (so that each square contains 100 squares of a new palette). If, say, $F$ contains a figure composed of 1716 squares of the new palette, and is contained in a figure composed of 1925 such squares, then $17,16 \leq S(F) \leq 19,25$. By once again reducing the palette (i.e., reducing the length of the side of the squares by 10 times), we will be able to estimate $S(F)$, etc. even more accurately.

The measurement process described is used not only to calculate area, but also for the very *definition* of the concept of area. Namely, consider a palette whose side lengths of squares are equal to $1/10^k$. Let $F$ contain a figure composed of $a_k$ squares of this palette, and be contained in a figure composed of $b_k$ such squares (for example, above we have $a_1 = 1716$, $b_1 = 1925$). Then we can say that $\frac{a_k}{10^{2k}}$ is the value of the area of ​​the figure $F$ with a deficiency, and $\frac{b_k}{10^{2k}}$ with an excess.

Increasing $k$ without limit, we can consider the previous

$$S(F) = \lim_{k \to \infty} \frac{a_k}{10^{2k}}, \quad S(F) = \lim_{k \to \infty} \frac{b_k}{10^{2k}},$$

⟦folio 4⟧

internal points, then $S(F_1 \cup F_2) = S(F_1) + S(F_2)$;
($\gamma$ function $S$ is invariant with respect to displacements, i.e. if $F_1 \cong F_2$, then $S(F_1) = S(F_2)$;
($\delta$ a single square has area 1.

After considering these properties, a turning point comes in the theory of areas. The point is that the following existence and uniqueness theorem is valid: on the class of all quadrium figures there exists, and only one, a function $S$, which has the property $(\alpha), (\beta), (\gamma), (\delta)$. This theorem plays an important role. The above definition of area (using palettes) can be called constructive, since the area is determined using the described structure (measurement process). Now we can give another description of the concept of area; roughly speaking, area is “that which has the property $(\alpha), (\beta), (\gamma), (\delta)$”. In fact, according to the theorem of existence and uniqueness, besides area, there is no other function that has the indicated property. More precisely, we can now say that area is a numerical function defined on the set of all quadrium figures and satisfying the condition $(\alpha), (\beta), (\gamma), (\delta)$. With this approach, properties $(\alpha), (\beta), (\gamma), (\delta)$ do not need to be proven (they are considered as area axioms), and the definition itself becomes axiomatic, and not constructive, as before.

With the axiomatic definition of the area, the palettes become inescapable $^*$), and all further properties of the area are derived from the axioms $(\alpha), (\beta), (\gamma), (\delta)$ as theorems. For example, from the axioms it can be deduced that for $F \supset G$ the inequality $S(F) \geq S(G)$ is valid (the property of monomony of the area); that for any quadrium figures $F_1, F_2$ the correspondence $S(F_1 \cup F_2) = S(F_1) + S(F_2) - S(F_1 \cap F_2)$ is valid; that the ratio of areas of similar figures is equal to the square of the similarity coefficient, etc.

Let us finally move on to the question of calculating areas. The simplest method for calculating areas, known since ancient times, is the decomposition method. To understand this method, consider the figures $F$ and $H$, depicted in figure 3. The dotted lines divide these figures into the same number of corresponding congruent parts, i.e., the figures $F$ and $H$ are equally composed. In general, two figures are called equivalent if, cutting one of them into a finite

**Fig. 3.**

number of parts, it is possible (by arranging these parts differently, that is, by considering figures congruent to these parts) to compose a second figure from them.

From the axioms $(\beta)$ and $(\gamma)$ it follows that two equilateral figures are equal in size, that is, they have the same area. The decomposition method is based on this: the figure, the area of ​​which needs to be calculated, is divided into a finite number of parts so that from these parts a simpler figure (the area of ​​which is already known) can be composed. For example, a parallelgram is equivalent to a right angle, having the same base and the same height (Fig. 4), and therefore, knowing the formula for the area of ​​a right angle, we establish the formula for the area of ​​a parallelgram. The triangle is equivalent to a parallelgram, which has the same base and half the height (Fig. 5), and this allows us to calculate the area of ​​the triangle.

You can easily calculate the area of ​​a triangle, it is easy to calculate the area

⟦folio 7⟧

and for all negative $\Delta x$ unless $-\delta < \Delta x < 0$. Thus, for any $\varepsilon > 0$ there is a $\delta > 0$ such that for $0 < |\Delta x| < \delta$ inequality (*) holds. By definition of a limit, this means that

$$\lim_{\Delta x \to 0} \frac{\Delta S(x)}{\Delta x} = f(x),$$

i.e.

$$S'(x) = f(x).$$

The proven equality allows us to calculate the area of ​​the function $F$. Let $\varphi$ be some antiderivative for the function $f$. Since $S$ is also an antiderivative for this function, then $\varphi$ and $S$ differ by a constant, i.e. there is a number $c$ such that $\varphi(x) = S(x) + c$ for any $x \in [a, b]$.

Hence,

$$\varphi(b) - \varphi(a) = (S(b) + c) - (S(a) + c) = S(b) - S(a) = S(F)$$

(since $S(a) = 0$ and $S(b)$ is the area of ​​the entire function $F$). So, if $\varphi$ is some antiderivative for the function $f$, then the difference $\varphi(b) - \varphi(a)$ is equal to the area of ​​the function $F$, i.e. $S(F) = \int_a^b f(x) dx$.

If, for example, $F$ is a “curvilinear triangle” bounded by the parabola $y = x^2$ and the lines $y = 0$, $x = b$ (Fig. 11), then the straight line that passes through the point $x$ of the segment $[0, b]$ and is parallel to the ordinat axis cuts out from this “triangle” $F$ is a segment of length $x^2$, i.e. in this case $f(x) = x^2$. For the function $f(x) = x^2$ one of the antiderivatives is the function $\varphi(x) = \frac{1}{3} x^3$. Therefore, the area of ​​the function $F$ is found by the formula

$$S(F) = \varphi(b) - \varphi(0) = \frac{1}{3} b^3.$$

Note that subtracting from the area of ​​the rectangle $ABCD$ (Fig. 12) satisfying the area of ​​the “triangle” $F$, we obtain the area of ​​the parabola segment, which thus turns out to be equal to $\frac{4}{3} b^3$. As you can see, with the help of the antiderivative, we simply obtain the result that Archimedes derived using a complex calculation based on the use of the exhaustion method *). Today's schoolchildren know much more than what was known to the great Archimedes!

Concluding the story about the concept of area, let's consider the so-called Cavalieri pricil**). Let

*) For more details on this, see the article by A.D. Bendukidze “Archimedes and the quadrature of the parabola” (Kvant), 1971, No. 7, p. 7).

**) Cavalieri's principle for areas has already been mentioned on pages «Kvant» - in the article by S. Verov “Secrets of the Cyclops” («Kvant», 1975, No. 8, p. 21) and in the article by S. Pukhov “The problem of convex bodies” («Kvant», 1977, No. 2, p. 30).

⟦folio 8⟧

In addition to $F$, there is another figure $H$ (Fig. 13), whose projection based on the merger is the same segment $[a, b]$. Suppose, in addition, that each straight line parallel to the ordinat axis intersects the figures $F$ and $H$ along congruent segments. Then the area of ​​the figure $H$ is expressed by the same integral as the area of ​​the figure $F$, i.e. $S(H) = \int_{a}^{b} f(x) dx$, and therefore $S(F) = S(H)$. So, if any straight line parallel to a given fixed line (for example, the ordinat axis) intersects the figures $F$ and $H$ along congruent segments, then the figures $F$ and $H$ are equal in size: $S(F) = S(H)$. These are the Cavalieri principles (for squares). We derived it using a formula expressing the area of ​​a figure through an integral. Cavalieri expressed his principle (and applied it to calculate areas and volumes) even before, in the works of Newton, Leibniz and other scientists

Fig. 13.

Fig. 14.

the concepts of first and integral were introduced.

figure 14 shows two figures that, by virtue of the Cavalieri principle, are equal in size. However, the equality of the areas of these figures can be easily established by the method of partitioning (how?).

The concept of volume is introduced similarly to the concept of area. During the constructive definition, cubillages (analgories of pallets) will be considered, i.e., divisions of space into congruent cubes. Consider a cubillage in which the length of the edges of the cubes is equal to $1/10^k$. Let the spatial figure $F$ contain a figure composed of $a_h$ cubes of this cubillage, and be contained in a figure composed of $b_h$ such cubes. Then $\frac{a_h}{10^{3k}}$ is the value of the volume of the figure $F$ with a deficiency, and $\frac{b_h}{10^{3k}}$ with an excess. If the figure $F$ is such that the limit

$$V(F) = \lim_{k \to \infty} \frac{a_k}{10^{3k}}, \quad V(F) = \lim_{k \to \infty} \frac{b_k}{10^{3k}}$$

coincide, then the figure $F$ is called cubed, and the number $V(F) = \overline{V}(F)$ is called the volume of the figure $F$ and is denoted by $V(F)$. The volume $V$ is a function defined on the class of all cubed figures and taking on numerical values.

Like area, volume can be defined axiomatically, and the axioms on which the concept of volume is based are completely similar to the axioms of area:

(α) the function $V$ is non-negative, i.e. $V(F) \geq 0$ for any cubed figure $F$;

(β) the function $V$ is additive, i.e. if $F_1$ and $F_2$ are cubed figures that do not have common interior points, then

$$V(F_1 \cup F_2) = V(F_1) + V(F_2);$$

(γ) function $V$ is invariant under displacements, i.e. if $F_1 \cong F_2$, then $V(F_1) = V(F_2);$

(δ).ed unit cube (i.e. a cube whose edge has length 1) has volume 1.
