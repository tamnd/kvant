---
id: 1984-12-toom-skolko-ploschadey-u-mnogougolnika-f67f7827
issue: kvant_1984_12
year: 1984
number: "12"
title: How many areas does a polygon have?
authors:
  - Тоом А. Л.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 9-12
tag: PFCS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 17216aa08439e2cdb4131ac59ca31c1745387dc6908522472689bd14aa2cde2c
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/03_toom-skolko-ploschadey-u-mnogougolnika-f67f7827.md
source_content_sha256: 9179597f28e74afde38a908ae8472d92b8ad37c454b86e6fcd0d2d016bfe73b1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

How many areas does a polygon have?

Candidate of Physical and Mathematical Sciences
A. L. TOOM

This article does not outline the general theory of areas, but simply talks about various approaches to determining the area of ​​a polygon. In the first part we are talking about a very simple (but unexpected for many!) question: is the trained determination of the area of ​​a triangle and a convex polygon correct? The second part discusses the concept of area of ​​"self-resexing" polygons; it turns out to be connected with two completely different physical questions.

Areas of a triangle and a convex polygon

Everyone knows that the area is equal to half the product of the lengths of the base and the height. But in a triangle, either side can be taken as the base. Thus, the triangle shown at figure 1 has three areas:

$$S_1 = \frac{1}{2} ah_a, \quad S_2 = \frac{1}{2} bh_b, \quad S_3 = \frac{1}{2} ch_c,$$

where $h_a, h_b, h_c$ are the lengths of the heights lowered to sides with lengths $a, b, c$, respectively. Would you say $S_1 = S_2 = S_3$? Yes, that's right. Why? Because both of them and the third are area triangles? This argument doesn't work at all. Because we give the same name “area” to some three values, they do not have to become equal. On the contrary, this is why we can call all three written quantities with the same name “area” because they are equal. And that they are equal - this must be proven.

Problem 1. Prove that for any triangle

$$ah_a = bh_b = ch_c.$$

Problem 2. Professor Honsens proposed considering a new value - the “boulevard” of a triangle, equal to the sum of the lengths of its base and the height lowered onto this base. According to this proposal, equalities must hold (see Fig. 1)

$$a + h_a = b + h_b = c + h_c.$$

Is this true? Is Professor Honsens's proposal valid? (The answer must be justified.)

The two problems above illustrate the important mathematical concept of correctness of definition. Often a habit replaces a concept and a proof, and we naively think that the meaning of each word is always the same. However, in mathematics everything must be strictly justified, and if the results of two different calculations are called the same, it does not follow from this that they are equal. On the contrary, one must prove that they will always be equal in order to have the right to call them the same. A definition whose formulation allows for several different paths of calculation or construction is said to be correct if all of these paths lead to the same result. Thus, the first definition (the area of ​​a triangle) turns out to be correct, but the second (“the boulevard” by Professor Honsens) turns out to be incorrect. Please note: we had to prove the correctness of the definition. This must be done in all cases when there is some arbitrariness in the definition itself - ambiguous construction, freedom of choice of some element, etc.

Let's look at another example. To school

⟦folio 10⟧

In the ninth grade textbook, the magnitude of a dihedral angle is defined as the magnitude of its linear angle (angle PAQ at figure 2). But the linear angle can be plotted from an arbitrary point A on the edge AA' of the dihedral angle; consider, for example, the angle P'A'Q'. Why will it be the same value?

Task 3. Prove the correctness of the definition of the dihedral angle.

Problem 4. Remember the definition of the angle between intersecting lines. What is arbitrary in this definition? Prove its correctness.

Let's talk now about the area of ​​a quadrilateral. If this is not some special quadrilateral, for example a trapezoid, then the general recipe for calculating its area is as follows: cut the quadrilateral diagonally into two triangles and take the sum of their areas. But a convex quadrilateral can be cut diagonally in two different ways. What if in one case it turns out to be one thing, and in another case it turns out to be another? And for a polygon with a large number of sides, there are even more ways to cut it into triangles. On what basis are we sure (if we are sure) that with all these cuts the sum of the areas of the resulting pieces will be the same? From practice? But all practical changes ensure accuracy only to a certain number of digits. The theory of relativity showed that the general formula for adding velocities is only approximately correct, and only for velocities significantly lower than the speed of light! Perhaps traditional ideas about the area of ​​polygons are only approximately correct? Here, for example, is a drawing we borrowed from a brochure by Ya. S. Dubnov*).

Here the square on the side 21 cm is cut into pieces, from which, as figure 3 shows, it seems that it is possible to fold a rectangle on the sides 34 cm and 13 cm.

Since
$$21^2=441\neq 442=34\cdot 13,$$
The area of ​​a figure changes when its parts are rearranged. And why not, actually?

Task 5. Figure out what’s wrong with figure 3.

Problem 6. Prove that if a polygon is cut into a triangle by dihedral methods,

*) Ya. S. Dubnov. Errors in geometric proofs. M., Gostekhidat, 1953, p. 10.

Areas of self-intersecting polygons

We discussed the correctness of the school definition of the area of ​​a polygon and a triangle - their internal consistency. But the definition in mathematics is subject to not only the formulaic requirement of correctness. The definition must still “work”. Let us explain this with the following example, also related to the area of ​​a polygon.

Is it possible, and if so, how can one reasonably and naturally determine the areas of self-intersecting polygons? For example, what is the area of ​​a five-pointed star (Fig. 4)?

Formulaically speaking, there are many correct ways to assign a number to each self-intersecting polygon and call this number its area. But not every such method deserves to be spoken about silently. In general, definitions in mathematics are formed relatively unprincipled, not “out of the blue.” In many (and, perhaps, in the final estimate and in all) cases, mathematical definitions

⟦folio 11⟧

lenitions are included in the natural. Let us remember where in physics the area of ​​a polygon is determined. Here are two cases that came to mind.

1) In electronics, an important concept is the flux of magnetic induction (magnetic flux) Ф through a section of a surface bounded by a conductive circuit. Let the contour lie in a plane, and the vector $\vec{B}$ of magnetic induction is the same at all points in space and is overridden by the plane of the contour. Then

$$\Phi = BS,$$

(1)

where $S$ is the area of ​​the figure bounded by the contour. From a physical point of view, the wave is pertinent to the question of what the magnetic flux F is equal to if the contour has the form of a self-intersecting polygon.

In fact, let us arrange an insulated wire in the form of a self-intersecting polygon in a plane, the redistribution vector $\vec{B}$ of magnetic induction is equal to the field (Fig. 5), and connect the ends of the wire to an ampere. What will the ampere show if you start “moving” this wire? After all, he will show something! For example, will the ampere needle deflect when moving triangle $MNA$ to position $M'N'A$? Put the shaded part does not change. However, wire $MN$ in its movement crosses magnetic lines of force and therefore an induced emf occurs. Current should flow. And he is a real current!

This means that the magnetic flux F changes. Since we want the formula $\Phi = BS$ to hold, then $S$ must change (unlike the shaded area). So what is $S$ - “area of ​​a self-intersecting polygon”?

It is easy to understand that the sum of the total areas of limited parts of the plane (shaded on figure 5) is not suitable here as $S$. How to determine $S$ in the general case?

2) In thermodynamics, the work performed by the working fluid in an arbitrary closed process varies by the area bounded by a line, depicting this process on the $(p-V)$-diagram $(p - \text{dавление}, V - \text{объем})$. It is natural to assume that this is also true for the process depicted on the $(p-V)$-diagram of a self-intersecting broken line.

In both physical examples given, we had a need to indicate the area of ​​self-intersecting flat polygons. It is remarkable that in both cases the same concept of area will arise, despite the fact that these examples are taken from different areas of physics. And this concept of areas has already been developed by mathematicians. It is described, for example, in an article by N. Vaguten*). It gives several definitions of this concept that are equivalent to each other; We'll stop at the next one.

Let's choose the direction of traversal of our polygon and designate its vertices in the order in which we traverse it: $A_1, A_2, ..., A_n$. Let us mark an arbitrary point $P$ on the plane that does not lie on the contour of the polygon. We will go around the polygon along its contour: subdem along $A_1A_2$, then along $A_2A_3$ and so on, and return to point $A_1$. In this case, the radius vector, starting at point $P$ and ending at the point where we are, will rotate either in a plane direction (that is, counterclockwise) or in a negative direction. In the final case, it surfaces at an angle $360^\circ \cdot n$, where $n$ is an integer indicating how many times we go around the point $P$, or along the path $A_1, A_2, ..., A_n, A_1$. So, if the point $P$ is taken at the center of the heel of the final star (see Fig. 4), then we get $n=2$.

Our polygon divides the plane into regions: one infinite and several finite. The number $n$ is constant in every region, and infinitely

⟦folio 12⟧

ny region $n=0$ (on figure 6, a, b the values ​​$n$ are placed in all finite regions). So, let's call the oriented area of ​​our polygon the sum

$$S_1n_1 + S_2n_2 + \dots + S_kn_k,$$

It is interesting that the definition developed from purely mathematical messages turned out to be in agreement with two modernly different physical laws. This has happened more than once in the history of science, and it will be written about in «Kvant».

Electrical resistance is a quantum phenomenon

(For the beginning, see p. 2)

Expressing the y part from formula (**) and substituting it into the expression for the Debye temperature - $\theta = \frac{hv}{k}$ - we obtain that

$$\theta = \frac{hc}{k} \sqrt[3]{\frac{n}{4\pi}}.$$

So, we have obtained the relationship between the Debye temperature $\theta$ and the speed of sound in a solid $c$. Using this formula and the graph presented on figure 8 (see p. 8), you can solve the problems that we will offer you. They are simple and do not require special ingenuity, but are interesting and respectful in two respects. First, you will see an unexpected connection between such different things as the speed of sound and the dependence of electrical resistance on temperature. Secondly, you will become familiar with generalized curves, which are very useful in many cases where theoretical formulas cannot be used. The dependence $R=f(T)$ is the same for each metal, but since they can be combined on a generalized curve (see figure 8), it means that these dependences and the expression of their curves are similar. This has a broader meaning here than in school geometry: it means that curves can be combined by independently changing the scales along two coordinate axes.

Now try solving the following problems:

1. The speed of sound in iron is 5200 m/s, the specific resistance at minus 100 °C is 0.592 Ohm mm²/m. Find the resistivity of iron at a temperature of +200 °C.

2. Using the dependence of copper resistance on temperature (see figure 1 on p. 3), determine the speed of sound in copper.
