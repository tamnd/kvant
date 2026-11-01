---
id: 1982-7-tadeev-prostyie-dvoynyie-garmonicheskie-7292a876
issue: kvant_1982_7
year: 1982
number: "7"
title: Simple, double, harmonic
authors:
  - Тадеев В. А.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 4, 5, 7, 8, 9
tag: PIFQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: bcfa82d58352e21fcc998aa3d2450dff54436eba9542daab69721733273a67eb
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/03_tadeev-prostyie-dvoynyie-garmonicheskie-7292a876.md
source_content_sha256: ca21bd26bcad3f46a07b9252a88a9c1de54b7cdf0224db5c0895bc336f460005
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

V. Tadeev

Simple, double, harmonic

No one now knows exactly how in 1640 seventeen-year-old Blaise Pascal (about his life, see S. G. Gindikin’s brochure “Stories about Physicists and Mathematicians” (M., “Nauka”, 1981)) came up with the theorem that bears his name. Perhaps, for some reason, continuing the sides of the hexagon inscribed in the circle, he simply noticed that the intersection points M, N and K were on the same straight line (see screensaver). Is it audible? The young man took another hexagon, but points M, N and K stubbornly fell on one straight line.

We do not know what emotions arose in his soul. It is only known that he rather quickly continued the proof of the red fact he discovered and immediately generalized it. And then... then from the theorem, as from a kind of abundance, a corollary was sent. Subsequently, Pascal's theorem turned out to be one of the most important provisions of a new branch of mathematics - projective geometry, which found interesting applications in geodesy and cartography.

In this article we will prove Pascal's theorem for the circle and discuss some "design concepts" that allow us to generalize it.

Simple relationships

Let points A, B and C (Fig. 1) be given on line l. For collinear vectors $\vec{AC}$ and $\vec{CB}$ there is a (singular) number $\lambda$ such that $\vec{AC} = \lambda \cdot \vec{CB}$. This number $\lambda$ is called the simple ratio of point A, B, C; it is denoted by (ABC). When points B and C coincide, the simple relation (ABC) is not defined. From the definition it is clear that

$$|(ABC)| = \frac{|\vec{AC}|}{|\vec{CB}|}.$$

More precisely, $(ABC) = \frac{|\vec{AC}|}{|\vec{CB}|}$, if point C

⟦folio 3⟧

located between $A$ and $B$, and $(ABC) = -\frac{|\overrightarrow{AC}|}{|\overrightarrow{CB}|}$ otherwise.

We now fix the points $A$ and $B$ on $l$ and examine how the simple relation $(ABC)$ changes depending on the position of the point $C$. To do this, we place the origin of coordinates at point $B$, and direct the abscissa axis along $l$ from $A$ to $B$ (Fig. 2). If we denote the abscissa of the point $C$ by $x$ and put $|AB| = a$, then $|\overrightarrow{AC}| = a + x$ and $|\overrightarrow{CB}| = x$. It's easy to see that $(ABC) = v(x) = -\frac{a+x}{x}$. (1)

From the graph of the function $v$ (Fig. 2) it is clear that the position of the point $C$ on the line $AB$ is uniquely determined by the number $(ABC)$.

Let us take lines $l$, $l'$ on the plane and a point $P$ outside them. To an arbitrary point $A$ of a straight line $l$ we assign a point $A' = (PA) \cap l'$ to a straight line $l'$. This mapping of the line $l$ into the line $l'$, which is naturally called the central projection (primarily $l$ into the line $l'$), will play an important role in the future.

Unfortunately, if $l \parallel l'$, the simple point relation under central projection is not preserved (Fig. 3). However, another relation can easily be built from it, which already has the property we need.

Dual relationships

Let points $A, B, C$ and $D$ (Fig. 4) be given on the line $l$. The number $\frac{(ABC)}{(ABD)}$ is called the double (or complex or anharmonic) ratio of the point $A, B, C, D$; it is denoted by $(ABCD)$. Thus,

$$|(ABCD)| = \frac{|\overrightarrow{AC}|}{|\overrightarrow{CB}|} : \frac{|\overrightarrow{AD}|}{|\overrightarrow{DB}|}.$$

When the points $A$ and $D$ coincide, $(ABD) = 0$ (see (1)); in this case the double relation $(ABCD)$ is undefined. It is, of course, also undefined for $B = C$. For $B = D$ it is natural to put $(ABCD) = 0$.

Now we fix the points $A, B$ and $C$ on $l$. Place the origin of coordinates at point $B$ and direct the x-axis

⟦folio 4⟧

Fig. 5.

6) $(BACD) = (ABDC) = (CDBA) = (DCAB) = \frac{1}{\omega}$;
7) $(BDAC) = (DBCA) = (ACBD) = (CADB) = 1 - \omega$;
8) $(DACB) = (ADBC) = (CBDA) = (BCAD) = 1 - \frac{1}{\omega}$;
9) $(DBAC) = (BDCA) = (ACDB) = (CABD) = \frac{1}{1 - \omega}$;
10) $(ADCB) = (DABC) = (CBAD) = (BCDA) = \frac{1}{1 - \frac{1}{\omega}}$.

Let us prove that the double relation is preserved under central projection (Fig. 5). Let us denote, respectively, by $h$ and $h'$ the distances from $P$ to the lines $l$ and $l'$. Considering the areas of, for example, triangles $PAC$ and $PA'C'$, we obtain

$$\frac{h \cdot |AC|}{h' \cdot |A'C'|} = \frac{|PA| \cdot |PC|}{|PA'| \cdot |PC'|}.$$

From here

$$|A'C'| = |AC| \cdot \frac{|PA'| \cdot |PC'|}{|PA| \cdot |PC|} \cdot \frac{h}{h'}$$

From similar equalities for $|C'B'|$, $|A'D'|$ and $|D'B'|$ we obtain

$$\frac{|A'C'|}{|C'B'|} : \frac{|A'D'|}{|D'B'|} = \frac{|AC|}{|CB|} : \frac{|AD|}{|DB|}$$

Since the points $A, B, C, D$ on $l$ and $A', B', C', D'$ on $l'$ are in the same order, the prime relations $(ABC)$ and $(A'B'C')$, and $(ABD)$ and $(A'B'D')$ have the same signs. So, $(A'B'C'D') = (ABCD)$.

Fig. 6.

Pascal triples

Now we can reap the fruits of our labors.

Construct (only carefully) the hexagon $ABCDEF$ inscribed in the circle and the extension of the side pair $FE$ and $BC$, ED and $AB$, DC and $FA$ to the intersection at points $M, N, K$ respectively*). If you carry out these constructions accurately enough, you will see that the points $M, N, K$ lie on the same line (Fig. 6). This triple of points is called the Pascal triple, and the statement about their collinearity is called Pascalai’s theorem.

By the way, how old are you? Seventeen? If you pay attention, read the previous ones

*) The case when at least one pair of lines does not intersect will be discussed below.

⟦folio 5⟧

pages, you find yourself on an equal footing with Pascal, who has just made his observation. Would you like to see how long it takes you to find a proof of Pascal's theorem on your own?

Let's prove this theorem. Let's consider two quadruples of lines: FE, FD, FC, FA and BE, BD, BH, BN. They are congruent because the angles between the corresponding lines are equal (for example, EFD = EBD, or they are based on a common arc DE). This means, by what was proven in the previous section, (RDCK) = (EDHN) (here R = (FE) ∩ (CD), H = (BC) ∩ (ED)).

Let us denote the point of intersection of the lines MK and EH by N'. Then (EDHN') = (RDCK). Therefore, (EDHN) = (EDHN'), whence N' coincides with N.

Exercises

2. By choosing in every possible way pairs of straight lines connecting the vertices of the hexagon ABCDEF inscribed in a circle, make sure that there are 60 parallel tracks.

3*. Explore the relative positions of the 60 pairs on which these tracks lie.

4. Form and prove Pascal's theorem for a pentagon inscribed in a circle (Hint: Consider it as a hexagon with coinciding vertices E and F, and the tangent at point E as the limit position of the secant EF), a quadrilateral and a triangle.

5. Construct a tangent to a given circle from a given point with one ruler.

* * *

In order to obtain the corollaries from Pascal’s theorem that were discussed at the beginning of the article, you will first have to spend a little time. We will study two important types of plane transformation - parallel projection and central projection. These transformations are the basis of design.

You know that plane movements leave the distances between points unchanged; therefore, they retain the size and shape of the figures. With similarities, only distance relationships are preserved - the figures can change in size, but retain their shape. The situation is worse with parallel and central design - they also distort the shape of the figures. For example, in parallel design

⟦folio 7⟧

lazy The appearance of a shadow from a flat object on the screen models the central projection (Fig. 12).

The mathematical definition here is as follows: the planes π and π' (parallel or intersecting) and the point P outside these planes are empty; to each point A ∈ π we associate the point A' ∈ π' of the intersection of the straight line PA with the plane π' (Fig. 13); the resulting mapping of the plane π into the plane π' is called the central projection (of the plane π into the plane π' from the center P).

Unfortunately, if the π and π' planes are not parallel, the central projection is neither a mapping into the π plane nor a mapping onto the entire π' plane. In fact, if a plane π₁ parallel to π' is drawn through P, then the points of the straight line l = π₁ ∩ π are not mapped in any way under the central projection from P (Fig. 14, a). Similarly, if a plane π₂ parallel to π is drawn through P, then the central projection from P does not transfer any points of the plane π to the points of the line l' = π₂ ∩ π' (Fig. 14, a).

Let us see what is done during central projection with the straight lines of the π plane. As has already been said, the straight line l (and any of its points) does not transform into anything. Any straight line in the plane π parallel to l goes into a straight line in the plane π' parallel to l' (Fig. 14, b). Taking the plane π intersecting l without an intersection point—a “pierced straight line” of the plane π'—into a straight line without its point of intersection with l' (Fig. 14, c). (In the future, in order not to clutter up the wording with flaps, in such situations we will allow the speech to fluctuate and say briefly that a straight line turns into a straight line.)

Note further that intersecting lines, if their point of intersection does not lie on the selected line l, go into intersecting lines (Fig. 14, f), otherwise they go into parallel lines (Fig. 14, e).

⟦folio 8⟧

Thus, we can say that with central design, basically straight lines turn into straight lines, and intersecting lines into intersecting ones. The words “substantially” means “except for the exceptions and qualifications set forth above.”

Exception clauses in design statements can be avoided by assuming that “parallel lines intersect at a point at infinity” and that “all points at infinity in a given plane lie on the same (infinity) line.” Moreover, words as quality can be given a precise mathematical meaning; then, by adding its “infinitely distant points” to our edge (Euclidean) plane, we obtain the so-called “projective plane”.

On the projective plane, Pascal's theorem holds without reservation: even in the case of a regular hexagon, opposite (parallel) lines “intersect at three points at infinity, which all lie on the same (infinitely distant!) line.”

However, we will not deal with the mathematical object of these countries here. «Kvant» will return to this topic soon.

Conch sections

Let us now use the example of a circle to see to what extent the central projection distorts the shape of the figures. Consider a circle S lying on the plane π and a point P above this plane (Fig. 15). What will circle S become?

Fig. 15.

when centrally projecting from point P, it depends, of course, on the location of the plane π′ on which we are projecting. figure shows four hearings (planes π′1, π′2, π′3, π′4); this produces a correspondence, an ellipse, a parabola, a hyperbola and a pair of intersecting lines. On figure it is clearly visible that the set of projected straight lines forms a cone; Therefore, the listed curves are called conical sections.

If central projection distorts the shape of figures so much, then what does it still preserve? We know that it transforms lines into straight lines, that is, it preserves the collinearity of points (here we just need to remember the reservations made above!). Also, it preserves the double ratio of the four points, which we actually proved earlier. It turns out that these two facts are enough to obtain many deep geometric theorems, in particular, a corollary from Pascal’s theorem.

Exercises

8. Form and prove Pascal's theorem for a hexagon inscribed in an ellipse, a parabola, and a hyperbola.

9. Prove that an ellipse, a parabola and a hyperbola are uniquely determined by fives.

10. Indicate a method for constructing one ruler along the heel points of the ellipse of its other points.

11. Using one ruler, construct a tangent to the given ellipse from a given point. The same goes for paraboles and hyperboles.

Harmonic four

Even ancient Greek mathematicians called the collinear of four points A, B C, D harmonic if (ABCD) = -1.

Let's give an example. Let's take an arbitrary triangle NAB and draw the bissertis NC of the “internal” angle ANB and the bissertis ND of the “external” angle KNB (Fig. 16). As is known (“Geometry 6-8”, problem 914), $\frac{|AC|}{|CB|} = \frac{|NA|}{|NB|}$. This statement can also be written like this:

$$ABC = \frac{|NA|}{|NB|}.$$

⟦folio 9⟧

Let $A$ be a point on the optical axis, $A'$ its image, $F$ the focus of the mirror, $a$ its center ($|PF| = |FO|$). Then the quadruple of points $P, O, A', A$ is harmonic. Prove it yourself, use the formula

$$\frac{1}{d} + \frac{1}{f} = \frac{1}{F},$$

known from a physics course.

Ancient Greek scientists, in addition to arithmetic ($a - b = c - d$) and geometric ($\frac{a}{b} = \frac{c}{d}$), also considered harmonic proportion:

$$\frac{1}{a} - \frac{1}{b} = \frac{1}{c} - \frac{1}{d}$$ (this equality is satisfied by the coordinates $a, b, c, d$ of the harmonic quadruple of points $A, B, C, D$). In the case where $b = c$ (in this case the proportions are called continuous), the arithmetic mean $b = \frac{a+d}{2}$, the geometric mean $b = \sqrt{ad}$ and the harmonic mean $b = \frac{2ad}{a+d}$ are obtained.

According to legend, even Pythagoras, while studying the mathematical theory of music, established that the lengths of the strings that sound at the same tension of the note $do, mi, colb$ (components of a major three-note note) are proportional to the number 1, $\frac{4}{5}, \frac{2}{3}$. But $\frac{4}{5}$ is the harmonic mean of the numbers 1 and $\frac{2}{3}$. This is where the concept of harmony came into mathematics.

It is also easy to prove that

$$(ABD) = -\frac{|NA|}{|NB|}.$$

(Hint: Consider the ratio of the areas of triangles $NAD$ and $NBD$, taking as bases first $[NA]$ and $[NB]$, and then $[AD]$ and $[BD]$.) Therefore, $(ABCD) = -1$, that is, the quadruple of points $A, B, C, D$.

Exercise 12. Indicate a method for constructing such a point using a ruler. Note. See Fig. 17. Points $P$ and $Q$ in steps 1 and 5 are chosen randomly.

Harmonic quadruples are found in optics. Let us consider the path of rays in wavy mirror 3 (Fig. 18).
