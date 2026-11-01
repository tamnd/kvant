---
id: 1979-8-virskiy-zvonkin-oval-vosmerka-dva-ovala-d3171cf8
issue: kvant_1979_8
year: 1979
number: "8"
title: Oval, figure eight, two ovals...
authors:
  - Вирский А.
  - Звонкин А. К.
rubric: osnovnye-stati
page_first: 23
page_last: 27
page_labels: 21-25
tag: S0H8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8693da9a172cdba937ce2ab6ee3b1980c2beab0c394912291d4e0f0db26ed008
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/08_virskiy-zvonkin-oval-vosmerka-dva-ovala-d3171cf8.md
source_content_sha256: db4fae26fc8bdd094e809bd0d33e3344074c9ae116ae65366d8386163602d565
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Oval, figure eight, two ovals...

This article discusses examples of algebraic curves of Thursday order. Recall that the algebraic curve of n-zo order is called the graph of the equation $p_n(x,y) = 0$, where $p_n(x,y)$ is a polynomial of the nth degree in the variables $x, y$). For example, a first-order algebraic curve is a straight line; algebraic curves of the second order are, in particular, the ellipse, hyperbola, parabola - curves known to you that have a number of remarkable properties **).

More interesting, and also not fully studied, are curves of higher orders. Suffice it to say that the famous “Hilbert’s sixteenth problem” for the case of a sixth-order curve was solved only very recently, and for large orders there remain many simply formulated but unsolved problems. However, we will talk about this in more detail in the Aftermath, and now let’s move on to the promised examples.

*) Let us remember what the degree of a polynomial in two variables is. The degree of the monomial $a \cdot x^k y^l$ is called the number $k+l$ (for example, $xy$ is a monomial of degree 2). The degree of a polynomial is the maximum degree of its monomials (for example, the polynomial $p(x, y) = x^3 + 2xy^4 + 11y^2 - xy$ has degree 5).

**) See «Kvant», 1975, No. 2 1, 3, 4.

Let's change one word

The geometric definition of an ellipse is well known: an ellipse is a set of points (on a plane), with the sum of the distances from which to the point $F_1$ and $F_2$ constructed: $|MF_1| + |MF_2| = 2a$. Note the one word in this definition:

$$|MF_1| \cdot |MF_2| = a^2.$$ (1)

The points $F_1$ and $F_2$, like those of the ellipse, are called foci. The Cassini Oval was born due to a mistake. It was “invented” by the French astronomer (Italian by birth) Jean Dominic Cassini (1625-1712). This outstanding scientist, member of the Paris Academy of Sciences, director of the Paris General School, who discovered the rotation of Jupiter and Mars, as well as the four satellites of Saturn, for some reason believed that the Earth’s orbit had exactly this shape. Further development of science showed that a more correct answer would be a general ellipse. But the Cassini oval remained alive. The fact is that it has one remarkable property.

Let us denote the distance between the foci by 2c and construct an equation for the Cassini oval in the coordinate system in which $F_1(-c;0)$, $F_2(c;0)$. Substituting

⟦folio 22⟧

$$|MF_1| = \sqrt{(x+c)^2 + y^2}, \quad |MF_2| = \sqrt{(x-c)^2 + y^2}$$

into equality (1) and squaring, after transformation we obtain

$$(x^2 + y^2 + c^2)^2 - 4c^2x^2 = a^4.$$

The result is an equation of four degrees. The specific type of curve depends and is placed on what values ​​we choose for the parameters $a$ and $c$. Let's, for example, fix $a$ and increase $c$ (you can do the opposite: fix $c$ and decrease $a$—the result will be the same; see Fig. 1). This is where the most interesting thing will happen: like a piece of dough that is stretched in different directions, the oval will first lengthen, then it will have a “waist”, it will become thinner, until finally our figure is torn into two parts, into two smaller ovals. A more accurate picture will be like this (Fig. 2):

1) at $c=0$ - circle;
2) at $0 < c \leq \frac{a}{\sqrt{2}}$ - a convex oval, similar to an ellipse;
3) at $\frac{a}{\sqrt{2}} < c < a$ - oval with “tale”;
4) at $c=a$ - “lying eight” (it has a separate name - Bernoulli’s lemissama);
5) at $c>a$ - two ovals; one of them contains the point $F_1$, the other contains the point $F_2$.

The indicated property of “divisibility” of Cassinni ovals was first discovered and studied in detail by another French scientist - Jean Paul de Gua de Malves (1712-1785). His work was one of the first to study singular points of algebraic curves (the singular point in this case is the self-intersection point at $c=a$). From such works a broad branch of modern mathematics was born - algebraic geometry.

Second example

Let us now consider the set of lobes $M$ for which the sum of quantities shaped like the squares considered from

$$\frac{1}{|MF_1|^2} + \frac{1}{|MF_2|^2} = \frac{1}{b^2}.$$

As before, we put $|F_1F_2|=2c$. Substituting the formulas for $|MF_1|$ and $|MF_2|$ into (2), we obtain the equation $$\frac{1}{(x+c)^2 + y^2} + \frac{1}{(x-c)^2 + y^2} = \frac{1}{b^2}.$$

Security Question. Why is equation (3) a quadruple equation?

The behavior of the resulting curve is very reminiscent of Cassinni ovals. figure 3 depicts the successive “division phases” that the curve goes through as parameter $c$ increases (parameter $b$ remains constant). Let's look at this process in a little more detail.

⟦folio 23⟧

Cutting a bagel

One simple geometric idea allows us to construct another example similar to the previous ones. Let's take the mor - the surface that fills the donut; this surface is obtained by rotating a circle around a straight line that does not intersect it (and lies in the same plane as the circle). We will intersect the torus with planes parallel to each other and parallel to the axis of rotation (Fig. 4). If we lift the cutting plane upward, we will see a familiar picture: at first the section will be a convex oval, gradually increasing in size; then the oval will acquire a waist, it will become thinner, the oval will turn into an eight, and the eight will split into two ovals. At the top of the torus, the whole process will be repeated in the reverse order: two ovals will “grow together” into an eight, the eight will turn into an oval with a waist, etc.

Now let’s translate our geometric wonders into the language of algebra.

Let us derive the torus equation for this. Let the coordinate axes be directed as at figure 4; in particular, the axis of rotation of the torus coincides with the Oy axis. Let us intersect the torus with an arbitrary plane passing through the Oy axis and consider one of the resulting circles (Fig. 5). Her equation

$$(t-R)^2+y^2=r^2.$$

Here, by $r$ we denote the radius of the circle, and by $R$ the distance from its center to the Oy axis. If we remember now

⟦folio 24⟧

Fig. 5.

thread that $t$ is the distance from the point $(x, y, z)$ to the axis $Oy$, that is, $t = \sqrt{x^2 + z^2}$, we get the equation then:

$$(\sqrt{x^2 + z^2} - R)^2 + y^2 = r^2.$$ (4)

If (4) is freed from radicals, we obtain an equation of the fourth degree. Now, to “algebraically” intersect the torus (the plane $z=c$, follows in equation 4) together with $z$ we substitute $c$.

Problem 3. Examine (using figure 4) the appearance of the curve given by the equation

$$(\sqrt{x^2 + c^2} - R)^2 + y^2 = r^2,$$

for different $c$.

Problem 4*. Let's consider the “oval with a waist”

$$\frac{1}{(x-1)^2 + y^2} + \frac{1}{(x+1)^2 + y^2} = 1.$$

Let's move it 3 units to the right (replacing $x$ with $x-3$):

$$\frac{1}{(x-4)^2 + y^2} - \frac{1}{(x-2)^2 + y^2} = 1;$$

now it does not intersect the $Oy$ axis. We form a bracing surface by rotating this oval around the axis $Oy$; the equation of this surface is obtained if we substitute $\sqrt{x^2 + z^2}$ together with $x$; if freed from radicals (which is not necessary), you will get an equation of the eighth degree. Examine the (gometric) appearance of sections of this surface of the plane $z=c$ for different $c$.

Aftermath

And now - the most interesting part. In our examples, a curve of the fourth order, if it does not have self-intersections, consists of one or two ovals (we will now also consider an oval with a waist to be an oval). You might want to know what the maximum number of ovals is for a curve of this order, and how they can be positioned relative to each other. This is what we will find out now, but first we note that these two questions make sense to formulate for a curve of any fourth order; in fact, mathematicians have been asking themselves these questions for a long time.

Back in 1876, A. Harnack proved that the maximum number of ovals that a curve of $n$ order can consist of is $\frac{(n-1)(n-2)}{2} + 1$.

In particular, for $n=4$ there are 4 ovals, for $n=6-11$ ovals, for $n=8-22$ ovals, etc. The problem of their relative position turns out to be much more complicated. At the turn of our degree, in 1900, at the Second World Mathematical Congress, the great German mathematician D. Hilbert formulated significant 23 problems that he considered the most important for the development of mathematics of the 20th century. The question that interests us was included in Hilbert's list at number 16. Since then, Hilbert's sixteenth problem has not stopped working on mathematics. D. A. Gudkov a little more than 10 years ago. For 11 ovals, three types of relative positions emerged

⟦folio 25⟧

Positions; they are shown schematically on figure 6 (configurations with fewer ovals are not shown, because there are too many of them; in total, together with the indicated trays, 56 different configurations are possible). It is unlikely that you will be able to find proof; But first, we will carry out a complete analogous study for curves of the fourth order. To do this, you are asked to solve the problems below.

Problem 5 (easy). Construct an example of a fourth-order curve consisting of two ovals placed in each other.

Problem 6 (difficult). Construct an example of a fourth-order curve with four ovals. (Indicated by e. Start with a pair of intersecting ellipses and tweak the equation so that the “flower” shown at figure 7 burns into four blue petals.)

Problem 7 (to the level of the previous one). Construct an example of a fourth-order curve with tray ovals.

If you solved problems 6, 7 (or peeked at the answer), you probably noticed that not one oval is contained in another. This is no accident:

Problem 8. Prove that a fourth-order curve containing two ovals interspersed with each other no longer contains any other points. (Indicated by e. Show that any straight line intersects a curve of fourth order in at most four points.)

The issue of interest to us has been fully investigated, if the final

Problem 9 (very difficult). Prove that a curve of fourth order cannot contain more than four ovals. (Indicated and e. Take advantage of the fact that exactly one second-order curve passes through any points.)

Tasks for our readers

(For the beginning, see p. 17)

b) $|AG_c|^2 \cdot \text{tg} \frac{\hat{A}}{2} + |BG_a|^2 \cdot \text{tg} \frac{\hat{B}}{2} + |CG_b|^2 \cdot \text{tg} \frac{\hat{C}}{2} = |AN_c|^2 \cdot \text{tg} \frac{B}{2} + |BN_a|^2 \cdot \text{tg} \frac{\hat{C}}{2} + |CN_b|^2 \cdot \text{tg} \frac{\hat{A}}{2} = |AN_b|^2 \cdot \text{tg} \frac{\hat{C}}{2} + |BN_c|^2 \cdot \text{tg} \frac{\hat{A}}{2} + |CN_a|^2 \cdot \text{tg} \frac{\hat{B}}{2} = S,$

where $S$ is the area of ​​triangle $ABC$.

2. From the vertices $B$ and $C$ (C and A, A and B) of the triangle $ABC$, perpendiculars to the sides $AB$ and $CA$ (BC and AB, CA and BC, respectively) are restored until they intersect with the bisector of the angle $\hat{A}$ ($\hat{B}, \hat{C}$, respectively) at points $B_a$ and $C_a$ ($C_b$ and $A_b$, $A_c$ and $B_c$). Let $h_a, h_b, h_c$ be the lengths of the heights omitted, respectively, from the vertices $A, B$ and $C$; $a, b, c$ - side lengths $BC, CA$ and $AB$, $r$ - radius of the circle inscribed in the triangle $ABC$, $p$ - its half-perimeter. Prove that:

a) $\frac{1}{h_a |CC_b|} + \frac{1}{h_b |AA_c|} + \frac{1}{h_c |BB_a|} = \frac{1}{h_a |BB_c|} + \frac{1}{h_b |CC_a|} + \frac{1}{h_c |AA_b|} = \frac{1}{2r^2};$

b) $\frac{ab^3}{|CA_c|^2} + \frac{bc^3}{|AB_a|^2} + \frac{ca^3}{|BC_b|^2} = \frac{a^3b}{|CB_c|^2} + \frac{b^3c}{|AC_a|^2} + \frac{c^3a}{|BA_b|^2} = p^2.$

3. $A_0, B_0$ and $C_0$ are the bases of the altitudes of the acute triangle $ABC$, dropped from the vertices $A, B$ and $C$, respectively. The lines connecting the vertices $A, B$ and $C$ with the center of the circle circumscribed about the triangle $ABC$ intersect the lines $B_0C_0, C_0A_0$ and $A_0B_0$ at points $M_a, M_b$ and $M_c$, respectively. Prove the equalities:

a) $|M_aB_0| = |M_bA_0|, |M_cB_0| = |M_aB_0|, |M_cA_0| = |M_aC_0|;$

b) $|M_aB_0| + |M_bC_0| + |M_cA_0| = d,$

where $d$ is the length of the segment connecting the bases of the height of the acute angle $ABC$ to its two other sides.

U. Alla (Võru)
