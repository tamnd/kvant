---
id: 1973-10-sadovskiy-sadovskiy-kak-izmeryayut-ploschad-2978579a
issue: kvant_1973_10
year: 1973
number: "10"
title: How to measure area
authors:
  - Садовский Л. Е.
  - Садовский А. Л.
rubric: osnovnye-stati
page_first: 24
page_last: 31
page_labels: 22-29
tag: PRBH
lang: en
source: kvant_digital
extraction: vision
content_sha256: f9a370fbde08c56e029052eb007c5f7f74a279f1940c99a3e2fe5a44d9c4f477
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/07_sadovskiy-sadovskiy-kak-izmeryayut-ploschad-2978579a.md
source_content_sha256: 5630e72bb0acd71cdb96510ef8499a4392a84ac33e65b930e6008e4826e005ff
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

How the area is changed

The problem of changing the area of ​​a figure bounded by a certain closed line has to be solved by people of various specialties: mathematicians, surveyors, physicists...

First of all, two closely related questions arise: what is area and what does it mean to change it?

These questions are not so simple, and a school geometry course provides answers to them gradually and only for some special cases. First for a number of simple shapes - square, rectangle, triangle, and then for a polygon, circle and some of its parts (sector, segment).

Recall that a square whose side is equal to one unit of length has an area equal to one (area). This condition is an axiom (unit area axiom). If, further, the figure (Fig. 1) consists of two parts that have no more than a finite number of common segments and points, and if the areas of the parts are determined, then the sum of the areas of these parts is taken as the area of ​​the entire figure. This condition is called the axiom of area addition (area additivity *)). Finally, the conditions are that the figures must be equal in area (axiom of congruence).

*) The property of additivity of some quantities was discussed in the articles: Ioni and Yu. I. Intergal. «Kvant», 1972, No. 9 and Smorodinsky Ya. A. Inert mass. «Kvant», 1972, No. 3.

Fig. 1.

⟦folio 23⟧

Fig. 2.

$F_k$ completely covers the figure $F$ and may even extend beyond its border $C$. The area $F_k$, according to the axiom of additivity, is equal to the sum $S_k$ of the areas of these squares (it is proportional to the number of squares making up $F_k$). It is natural to take the value $S_k$ as an approximation to the value of the area of ​​the figure $F$ (with an excess).

Let us now calculate the sum $S_k$ of the areas of those squares of the discharge grid $k$ that are entirely contained in $F$. These squares make up the polygon $f_k$ (it is colored green), which does not extend beyond the outline $C$. It is clear that for any $k$ the inequality $S_k \leq S_k$ is valid. It is natural to take $S_k$ as an approximation of the area value $F$ (with a disadvantage).

Note that the contour $C$ itself turns out to be contained in a certain polygonal region $\varphi_k$ (it is colored yellow), lying between the boundaries of the polygons $F_k$ and $f_k$; the area of ​​$\varphi_k$ is equal to $S_k - S_k$.

You can verify (check this!) that when passing from the grid of the $k$ to the grid of the $k+1$ the inequality $S_k \geq S_{k+1}$ is satisfied. Moreover, each number $S_k$ is non-negative, so the polygonal and limited sequence

$$S_1 \geq S_2 \geq S_3 \geq \dots \geq S_k \geq \dots$$

must have a limit of $S = \lim_{k \to \infty} S_k$.

Similarly, the multi-relation sequence

$$s_1 \leq s_2 \leq \dots \leq s_k \leq \dots$$

also has some limit $s = \lim_{k \to \infty} s_k$.

Let us assume that with an unlimited increase in the digit $k$ of the grid (and, consequently, as $h_k$ tends to zero), sequences (1) and (2) have the same limit: $s = S$. In this case, the figure $F$ is called squarable and its area is taken equal to $S^*$). If $F$ is squarable, then its boundary $C$, as follows from the previous one, can be enclosed in a polygonal region $\varphi_k$, the area $S_k - s_k$ of which decreases indefinitely when $k$ appears. Therefore, it is completely logical to assume that the area of ​​such a contour $C$ is equal to zero. Thus, if the region $F$ is squarable, then the area of ​​the contour bounding it is equal to zero.

Of course, the converse statement is also true (prove it): if the area of the contour $C$ is equal to zero (this means that $C$ can be covered by the polygonal area $\varphi_k$, composed of quadriarms of the grid of the category $k$, the area of which tends to zero as $k$ tends to infinity), my figure $F$ squarable.

In most practical cases we end up with lines $C$ of zero area. Among them

*) Note that all reasoning does not actually depend on the orientation of the palestino relative to the figure. If for one orientation of the grids the figure $F$ turns out to be squarable, then it turns out to be the same for an arbitrary mixture of grids. And although with a new position of the grids the numerical sequences themselves (1) and (2) change, their limit $S$ remains the same.

The reasoning carried out here is completely similar to those in geometry textbooks that lead to the definition of the area of ​​a circle as the limit of the sequence of areas of right inscribed (circumscribed) polygons with an unlimited increase in the number of their sides.

⟦folio 24⟧

Fig. 3.

refers to a line studied by the French mathematician Camille Jordan (1838-1922). These are the so-called Jordan curves. If the Jordan curve is considered as a trajectory of motion (in the plane) of a point, then its rectangular coordinates $x$ and $y$ can be specified as continuous functions

$$x = x(t), \quad y = y(t)$$

time $t$ ($t_0 \leq t \leq t_1$).

Jordan proved that every closed Jordan line $C$ without self-intersection points splits the entire plane into two parts: internal and external (Fig. 3); for each of them $C$ serves as a common boundary. Any two points belonging to the same part of the figure (for example, internal) can be connected by a polyline that does not intersect $C$. Any broken line connecting two points from different parts inevitably intersects $C$. Since the area of ​​a closed and non-self-intersecting Jordan curve is zero, then the figure $F$ (it is bounded) is squarable, that is, for it the sequences (1) and (2) have a common limit $S$.

Area Measurement

Now it becomes clear what it means to measure the area of ​​the squared figure $F$. This means finding the number $S$ - the limit of the sequence of numbers $S_h$ (or $s_h$). Each of the numbers $S_h$ gives only an approximation of the area value with an excess ($s_h$ - with a deficiency). This excess (deficiency) is smaller, the larger the rank $k$ of the grid.

Naturally, in practice they do not calculate the limit $S$, but limit themselves to determining its approximate value $S_h$ using a grid of a suitable category *).

However, a need arose for more advanced instruments than a palette, allowing one to measure the area faster, more accurately and, if possible, automatically. The first such devices, called *planimeters*, were created more than years ago and, as very often happens in matters of great practical or scientific importance, almost simultaneously in different countries. However, the first planimeter (planimeter-scooter) was invented in 1854 by the Russian mechanic P. A. Zaar and Nina M (1816-1886). In the same year, a different planimeter design was proposed by the Swiss mathematician J. Amsler (1823-1912).

These and similar planimeters are based on a rather simple and at the same time very fruitful idea (we will only present the idea itself and omit the structure of the proof).

Let us consider two arbitrary positions of a certain segment (rod) in the drawing plane. You can transfer a segment from the initial position $A_0B_0$ to the final position - $AB$ (Fig. 4a) using three types of movements:

(1) by rotating around the middle $C_0$ of the rod through an angle $\alpha \geq 0$ to a position $A_1B_1$ parallel to $AB$;

(2) translational movement by an amount $h \geq 0$ in the direction perpendicular to $A_1B_1$, moving the segment to position $A_2B_2$ on the straight line $AB$;

*) Note that the methods of integral calculus make it possible, in most practical cases, to determine the number $S$ without using sequence (1) or to find an approximation of the value $S$ in a more economical way than by counting quadratic ones on a grid (on the concept of the integral, see the article: And he and Yu. I. Integral. “Quant”, 1972, No. 9).

⟦folio 25⟧

(3) with dwг on $g \geq 0$ in the direction $AB$, combining the point $A_2$ with the point $A$.

However, it is known from the physics course that the last two movements can be replaced by one - a translational movement that transforms $A_1B_1$ immediately into $AB$. In this case, the segment will “sweep out” a parallelogram $B_1A_1AB$ with a height $h$ and a base equal to the length $l$ of the segment.

Let's calculate the entire area, replacing it with a segment when moving from $A_0B_0$ to $AB$. First, however, acceptance is an important rule.

The conditions are to assign (looking from $B$ to $A$) the area a positive sign if it remains to the right of it when moving the rod, and an imprint sign if it remains to the left (Fig. 4a).

Taking into account this rule, it is clear that the total area replaced by a segment as a result of the first type of movement is equal to zero.

Fig. 4a.

Fig. 46.

Naturally, the area replaced when moving a third of the type is equal to zero. Only the area of ​​the rectangle, replaced during translational movement of the second type, turns out to be different from zero; it is equal to $lh$ (the same value is equal to the area of ​​the parallelogram $B_1A_1AB$).

If now it makes an arbitrary movement from position $A_0B_0$ to position $AB$, then at any moment this movement can be decomposed into three: types (1), (2) and (3). At the same time, movements (1) and (3) do not allow the inclusion of movement in the direction perpendicular to the segment (type (2)), its replacement is completely determined by the area (this is the most “subtle” place in our reasoning, it is here that we do not present the structure of the proof).

Thus, to determine the total area (more precisely, the algebraic sum of areas), replaced by a segment of known length $l$, it is enough to have a device that changes the total displacement of the segment in the perpendicular direction (Fig. 46).

It turned out that such a device could be a small wheel $R$ with rounded edges, mounted in the middle (at point $C_0$) of the rod and connected to it so that it can only rotate. It is clear that during movements of the first and third types, the wheel will not rotate, and the one carried by the rod will only slide along the surface of the drawing. But when moving the second type, it will roll along the drawing practically without sliding, turning relative to the rod. In this case, it will turn exactly an arc equal to $h$.

Keep in mind that the wheel can be placed at any point on the rod. At the same time, it remains possible to use it to change the area. Try to see for yourself that if the wheel is shifted by amounts $\lambda$ relative to the middle of the rod, then its readings will change to $\lambda\alpha$, where $\alpha$ is the angle (in radians) formed by the initial and final positions of the rod.

⟦folio 26⟧

Fig. 5.

If the circumference of the wheel is divided into a certain number of divisions, and the indicator is fixed on the rod, then it becomes possible to monitor how much the wheel turns. A simple mechanism will arise. We immediately notice that the second one is not always missing (after the circle) but turns out to be larger than the first (before the circle), it all depends on which direction the wheel turns. If you move the rod from position $A_0B_0$ to position $AB$, and then return it to its original position, then the result will remain unchanged, that is, the pointer will stand against the same division at the beginning and at the end of these two movements. This is natural, since the rod crossed twice over the parallelogram $B_1A_1AB$; one time the area was assigned a positive sign, the other time a negative sign.

Let us use the results obtained to calculate the area $S$ of the figure $F$ with a curved boundary, for example, such as in figure 5. To do this, we will move one of the ends $B$ of the rod along the boundary $F$ in the direction of the arrow. The end $A$ is empty and moves in a straight line $LA$. figure 5 shows several positions of the rod as it moves from the boundary point $P$ to the points $Q$, $R$ and $T$.

We notice that above the definition of area $S$, rod $AB$ is read only once - when moving from point $Q$ to points $R$, $T$, $P$. But the area lying outside the border is

⟦folio 27⟧

the count corresponds to their sum. Because
$$lh = S \pm s.$$ (3)

As the boundaries of s, you can choose a circle of radius r; then s = $\pi r^2$ and the required area will be
$$S = lh \pm \pi r^2.$$

In this formula, the sign of the plane is chosen, for example, also when s lies inside S (Fig. 8).

All of the above means that a rod with a wheel (often called an integrating rod) can serve as a planeter. However, such a simple device is inconvenient to use and introduces large errors. In reality, the planetaire is somewhat more complicated, although the principle of its operation remains the same. There are many types of planetaries produced by various precision mechanics factories. They differ from each other in the designs of the individual elements, as well as in the choice of the curve along which the end A of the rod moves. For such a curve, one usually chooses either a straight line (linear planetae) or a circle (polar planetae).

Planetar designs

Figure 9 gives an idea of ​​the general appearance of the polar planet. The polar lever p and the bypass lever l are connected by a hinge b and can be separated from each other; at the end of the bypass lever there is a sharp pin F, which outlines the boundary of the area, and a stop f, which protects the drawing from damage by the pin. The polar arm rotates around the end (pole), which is hinged to the heavy plate Π (it does not allow the strip to move). The counting mechanism (Fig. 10) is connected to the bypass lever. It can be moved along this lever and secured in the desired position with screw q. The counting mechanism rests on an adjustment wheel R and an additional support roller C, which gives the device stability. The rotation of the wheel R is transmitted through the stroke wheel to the counting disk Z. One full revolution of the wheel causes the disk to rotate by one of the ten divisions marked on it. The perimeter of the counting drum T connected to the roller is divided into one hundred small divisions. Using the vergebra V located next to it, you can count the ten beats of the snare drum T.

Fig. 9. Polar planetr

⟦folio 28⟧

Fig. 10. Counting mechanism of a polar planometer.

Each report is a four-digit number: first the number of full divisions on the Z disk is recorded, then the number of major divisions on the T drum, then the number of complete minor divisions on it, and finally the number of tenths of the minor division.

To determine the area S in planmeter divisions, you should set a common pin F at a certain point on the boundary, then at the initial reading, objectively the boundary, and, returning to the starting point, record a new reading. Then subtract the second from the first count; then their difference (up to sign) will give a number that, to obtain the initial value h, must be multiplied by the radius p of the wheel. In order for each length l to be equal to the value h, calculate in advance what one planometer division corresponds to (the so-called “division price” of the planmeter) when determining the length of the common lever l. To do this, outline a figure (for example, a square or a circle), the area of ​​which can be calculated using the geometry formula. Then divide this area by the difference in the reading at the end and at the beginning of the contour.

The special passport, which is attached to each device, indicates the division price for different lengths l of the bypass lever. This length can be changed by moving the counting mechanism. When the counting mechanism shifts, the variable quantity shifts from the midpoint by one or another value λ. Nevertheless, it can be proven that the formula derived above remains valid as before. An exception is the case when, as a result of circling the boundary, lever l makes a full revolution. In this case, the difference in readings must be increased by 2πlλ.

Homemade planometer

There is one average planometer scale that is extremely simple. This is the so-called “Price hatchet planmeter” (1886). It can be made from a piece of objective wiring, according to the form of a stretched letter P (Fig. 11). One of the curved ends k is pointed and serves as a bypass pin, the other end T is located and looks like a hatchet, the blade of which lies in the same plane as the tip. Point k is installed at a certain point O inside the variable area (preferably towards the center of gravity of the outlined figure). The position of the point T₀ of contact of the hatchet blade with the drawing is offset; then, holding the hatchet in response, they lead the blade to the border, circle the entire border and return to the starting point O. At the same time, the hatchet describes a certain curve (if the blade is absent, it turns out to be

Fig. 11.

⟦folio 29⟧

scribbled on the drawing). One of these lines - the pursuit line *), which appears when circling the circle, is shown at figure 12. Having returned to the starting point $O$, mark the new position $T_1$ of the blade. To now determine the position of the outlined figure, you need to change the angle $\varphi = \frac{l}{2}\varphi$ in radians between the initial and final position of the planmeter and multiply it by $l^2$. If the angle is not large, then instead it is enough to change the chord $T_0T_1$ and create the product $l \cdot T_0T_1$. This rule can be obtained from the general theory of planmeter**). This means that the planometer-tooric does not even need an adjustment wheel.

Indeed, let us assume that the planometer-toorik is nevertheless equipped with a variable wheel, mounted

*) A hare hunter should follow such a curve if he, having “caught the hare at gunpoint,” wants to keep it under targeted fire throughout the entire chase and at the same time not change the direction of the gun relative to the body.

**) The elementary geometric theory of the planometer-tooric was given by Academician A. N. Krylov in 1904 in the article “On the hatchet planimeter” (Collected works. Vol. V).

nom at its end (next to the blade). Then, when circling the boundary of the figure $F$, the wheel will only slide, and therefore its rotation turns out to be zero. If, however, the wheel is placed in the middle of the hatchet, then its rotation will be $\frac{l}{2}\varphi$ (why?). This angle $\frac{l}{2}\varphi$ will turn the wheel when turning the rod from position $OT_0$ to $OT_1$, and in total - to $l\varphi$. Therefore, the algebraic sum of the areas swept by the planmeter turns out to be equal to $l^2\varphi$. It remains only to note that this value is equal to the algebraic sum of the required area $S$ and the area $s$, limited by the pursuit curve (it is closed by turning the planmeter through an angle $\varphi$). It can be proven that if the starting point $O$ of the contour is located close to the center of gravity $F$, then $s$ is close to zero, and formula (3) gives:

$$l^2\varphi = S.$$

A planmeter-toorik can easily be made by each of you. But a polar planometer requires a high level of arbitrariness; it measures an area ten times more accurately than a tooric planmeter. High precision (precision) planometers will measure the area ten times more accurately than conventional ones (the error is only 0.0001 of the encircled area). In these devices, the measuring wheel does not roll along the drawing, which may have folds or other irregularities, but along a special metal disk or ruler.

Hairstyle. The traversal of the boundary of the figure $F$ is not always accompanied by movement of the end $A$ in the direction $L$ strictly in one direction and ends with its complete traversal: a counterclockwise movement can be replaced by a clockwise movement and vice versa. It all depends on the relative position and configuration of $F$ and $L$. In this regard, figure 6, 7 and 8 are purely schematic.
