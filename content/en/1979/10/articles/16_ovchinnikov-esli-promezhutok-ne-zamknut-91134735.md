---
id: 1979-10-ovchinnikov-esli-promezhutok-ne-zamknut-91134735
issue: kvant_1979_10
year: 1979
number: "10"
title: If the gap is not closed...
authors:
  - Овчинников С. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 50
page_labels: 44-48
tag: 7LJF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6dc9e90770d8d96a6d848b3590a9a06fe9581b2cdb0a601beb152879faf61460
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/16_ovchinnikov-esli-promezhutok-ne-zamknut-91134735.md
source_content_sha256: c5b7668e7e75feed94392623f32f6f5924bc28e096d68b8600defcae1093263f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

S. Ovchinnikov

If the gap is not closed...

When solving geometric problems of finding the most (or most) value, it is sometimes forgotten that the sought quantities usually satisfy certain restrictions due to their geometric meaning. In many such problems, the study of the function under consideration at the boundaries of its domain is determined by itself as an existing part of the solution.

Below are examples of such research.

Problem 1. The name of the value of the perimeter of a rectangle is written in a given circular segment so that its two vertices lie on the chord of a given segment.

Solution. Let $2a$ be the length of the chord of the segment, and $h$ its height (Fig. 1). It is easy to see that the radius of the circle is $R = \frac{a^2 + h^2}{2h}$.

Denoting by $x$ half the length of the base of the inscribed rectangle

Fig. 1.

So, find the length of the second side:

$$y = \sqrt{R^2 - x^2} - R + h.$$

From here we find the perimeter $P$ of the rectangle as a function of the variable $x$:

$$P(x) = 4x + 2\sqrt{R^2 - x^2} - 2R + 2h.$$

Moreover, $x \in ]0; a[$ if $h \leq R$, and $x \in ]0; a[$ if $h > R$ (check!).

Let us find the critical points of the function $P$ and study them. We have

$$P'(x) = 4 - \frac{2x}{\sqrt{R^2 - x^2}}.$$

From here

$$P'(x) = 0 \Leftrightarrow 2\sqrt{R^2 - x^2} = x.$$

Solving the last equation, we find the critical point $x_0 = \frac{2\sqrt{5}}{5}R$.

The function $\frac{2x}{\sqrt{R^2 - x^2}}$ is age. Therefore, the derivative of $P'(x)$ is positive at $x < x_0$ and negative at $x > x_0$. Thus, the point $x_0$ is the maximum point of the function $P$. It remains to investigate the question of when this point gives the maximum perimeter value and what happens when the maximum value at this point is not achieved. In this study, the interval on which the function $P$ is defined plays a significant role. For example, that for $h \leq R$ this is the interval $]0; a[$, and for $h > R$ the resulting interval is $]0; a[$.

In both cases, if the critical point $x_0$ belongs to the interval $]0; a[$, then the function $P$ takes its maximum value in it. We have

$$x_0 \in ]0; a[ \Leftrightarrow \frac{2\sqrt{5}}{5}R < a \Leftrightarrow \frac{\sqrt{5}}{5} \cdot \frac{a^2 + h^2}{h} < a.$$

Solving the last equation, we find $\frac{h}{a} \in \left[ \frac{\sqrt{5} - 1}{2}; \frac{\sqrt{5} + 1}{2} \right]$.

For all such values ​​$a$ and $h$ the most perimeter value is equal to

$$P(x_0) = \frac{(\sqrt{5} - 1)a^2 + (\sqrt{5} + 1)h^2}{h}.$$

⟦folio 45⟧

Now let the critical point $x_0$ not belong to the interval $]0; a[$, i.e. $x_0 \geqslant a$. In this case, the product $P'(x)$ is positive for all $x$ of $]0; a[$ and the function $P$ returns on the interval $]0; a[$.

Let $h \leqslant R$. Together with the conditions $x_0 \geqslant a$ this gives us $\frac{h}{a} \leqslant \frac{\sqrt{5}-1}{2}$.

Since at $h \leqslant R$ the function $P$ is defined on the interval $]0; a[$, we conclude that it does not reach its maximum value.

If $h > R$, then together with the conditions $x_0 \geqslant a$ we obtain $\frac{h}{a} \geqslant \frac{\sqrt{5}+1}{2}$. Since in this case the function $P$ is defined on the semi-literal interval $]0; a[$, it reaches its maximum value at $x = a$. This value is $P(a) = 4a + 2 \cdot \frac{h^2 - a^2}{h}$.

Let us give a clear geometric illustration of the results obtained. Let us select two parallel “critical” chords in a circle of radius $R$, located at a distance $\frac{\sqrt{5}}{5} R$ from the center of the circle (Fig. 2), and construct them to a rectangle. We will consider only the “upper” segments with chords parallel to the selected ones.

If a chord of a given segment is located between the selected chords, then $a > \frac{2\sqrt{5}}{5} R$ and the rectangle of maximum perimeter inscribed in our segment is the intersection of this segment with the rectangle built on the selected chords (see Fig. 2).

If a chord of a given segment is above both selected chords, then $h < R$ and $a \leqslant \frac{2\sqrt{5}}{5} R$; in this case, the perimeters of the inscribed rectangles do not reach the maximum value (Fig. 3).

Finally, if a chord of a given segment is above both selected chords, then $h > R$ and $a \leqslant \frac{2\sqrt{5}}{5} R$; in this case, the inscribed rectangle most perimeter has this chord as its base (Fig. 4).

Fig. 5.

Task 2. From a rectangle with a cut-off “walk” (Fig. 5), you need to cut a rectangle with the flattest area, parallel to the sides of this rectangle.

Solution. Let us introduce a coordinate system, as shown in figure 6, and continue the linear “medium” until it intersects with the coordinate axes. Let

⟦folio 46⟧

its intersection points with the coordinate axes are $A(a, 0)$ and $B(0, b)$. Let us solve the following auxiliary problem: inscribe into triangle AOB a rectangle of the largest area, one of the vertices of which is $O$. Let the magnitude of the auxiliary rectangle be $x$. Then its height is $b - \frac{b}{a}x$. Hence the area of ​​the rectangle, considered as a function of $x$, is

$$S(x) = x \left( b - \frac{b}{a}x \right).$$

Obviously, $S(x)$ takes its maximum value at $x_0 = \frac{a}{2}$. In this case, the function $S$ returns $0; \frac{a}{2}$ on the resulting interval and kills $\left[ \frac{a}{2}; a \right]$ on the resulting interval.

The conducted study of the function $S$ allows us to give the following visual solution to the original problem. If the middle $K$ of the segment $[AB]$ belongs to the “cut” $[CD]$, then it should be taken as the vertex of the desired rectangle. If point $K$ is “above” cut $[CD]$, then point $C$ should be taken as the vertex of the desired rectangle. If it is “below” the cut $[CD]$, then the point $D$ is taken as the vertex of the desired rectangle.

Problem 3. Hang a cylinder with the largest total surface area in a cone with an angle $2\alpha$ at the vertex of the main section and a base radius $R$.

Solution. figure 7 shows the mastered section of this cone. Denoting by $x$ the radius of the base of the suspended cylinder, we easily find that its height ($R-x$) stg $\alpha$. Hence the total surface, as a function of the variable $x$, is

$$S(x) = 2\pi \cdot \text{ctg} \alpha \left[ (\text{tg} \alpha - 1) x^2 + Rx \right].$$

This function is defined by the conditions of the problem on the interval $]0; R[$. For $tg \alpha \neq 1$ we easily find the critical point $x_0 = \frac{R}{2(1-tg \alpha)}$ function $S$.

Depending on the location of the critical point relative to the interval $]0; R[$, three cases are possible:

1) $x_0 < 0 \Leftrightarrow \text{tg} \alpha > 1$.

In this case, obviously, the function $S$ is increasing on the interval $]0; R[$. In this case, the function $S$ does not reach its maximum value.

2) $x_0 \in ]0; R[ \Leftrightarrow 0 < \frac{R}{2(1-tg \alpha)} < R \Leftrightarrow \text{tg} \alpha < \frac{1}{2}$.

In this case, the critical point $x_0$ is obviously the maximum point of the function $S$, and on the interval $]0; x_0]$ the function $S$ returns on the interval $[x_0; R[$ kills; therefore, the greatest value of this function is $S(x_0) = \frac{\pi R^2 \cdot \text{ctg} \alpha}{2(1-tg \alpha)}$.

3) $x_0 \geqslant R \Leftrightarrow \frac{1}{2} \leqslant \text{tg} \alpha < 1$.

In this case, the function $S$ is increasing on the interval $]0; R[$. To summarize the study of the function $S$, we can say that for $tg \alpha < \frac{1}{2}$ a cylinder with the largest total surface area can be inscribed in the cone. If $tg \alpha \geqslant \frac{1}{2}$, then it is possible that the values ​​of the functions $S$ are the opening interval $]0; 2\pi R^2$ (“Algebra and the beginnings of analysis 10”, p. 84) and the function $S$ does not reach its greatest value.

Problem 4. One of the angles of a triangle inscribed in a circle of radius $R$ is equal to $\alpha$. Find the most

⟦folio 47⟧

neck the value of the length of the height of the triangle.

Solution e. Let us denote the lengths of the side of the triangle by $a$, $b$ and $c$ (Fig. 8) and the empty angle opposite the side $a$ is equal to $x$.

Obviously $x \in ]0; \pi - \alpha[$. Note that the conditions do not indicate which of the three altitudes of the triangle we are talking about. Therefore, when solving “at any”, it is necessary to find the maximum value of the length of each height, and then from the found values ​​determine the maximum value equal to $2R\cos^2\frac{\alpha}{2}$.

Denoting the lengths of the altitudes of the triangle dropped to the sides $a$, $b$ and $c$, respectively, by $h_a$, $h_b$ and $h_c$, we calculate them as a function of the angle $x$. Using the sine theorem and the formula for the plane of a triangle, we find

$$h_a(x) = \frac{bc}{a}\sin x = 2R\sin \alpha \sin (x + \alpha),$$

$$h_b(x) = \frac{ac}{b}\sin (x + \alpha) = 2R\sin \alpha \sin x,$$

$$h_c(x) = \frac{ab}{c}\sin \alpha = 2R\sin x \sin (x + \alpha).$$

Consider the function $h_a$ for $x \in ]0; \pi - \alpha[$. Obviously, at $\alpha < \frac{\pi}{2}$ this function reaches its maximum value $2R\sin \alpha$ at $x_0 = \frac{\pi}{2} - \alpha$.

If $\alpha \geq \frac{\pi}{2}$, then the function $h_a$ kills on the interval $]0; \pi - \alpha[$ and has no significance. Similarly, we find that the function $h_b$ for $\alpha < \frac{\pi}{2}$ reaches the maximum value $2R\sin \alpha$ at $x_1 = \frac{\pi}{2}$, but for $\alpha \geq \frac{\pi}{2}$ it has no value.

Consider ending the function $h_c$. $h_c'(x) = 2R[\cos x \cdot \sin (x + \alpha)] + \sin x \cdot \cos (x + \alpha)] = 2R \cdot \sin (2x + \alpha)$. Obviously, on the interval $]0; \pi - \alpha[$ $h_c'(x) = 0 \Leftrightarrow \sin (2x + \alpha) = 0 \Leftrightarrow 2x + \alpha = \pi$.

The critical point is $x_2 = \frac{\pi - \alpha}{2}$. This time $\alpha \in ]0; \pi - \alpha[$ for any valid $\alpha$. The interval $]0; \pi - \alpha[$ is followed by a positive, and to the right is a negative. Therefore, at point $x_2$ the function $h_c$ reaches its maximum value, equal to $2R\cos^2\frac{\alpha}{2}$.

So, for each value of the angle $\alpha$, we just have to find the most values ​​from the most found values ​​of heights.

Let us first consider the case $\alpha < \frac{\pi}{2}$. With such $\alpha$ the height values ​​are reached and take two values: $2R\sin \alpha$ and $2R\cos^2\frac{\alpha}{2}$. Let's transform the difference

$$2R\sin \alpha - 2R\cos^2\frac{\alpha}{2} = 2R\cos^2\frac{\alpha}{2} \left(2\tg \frac{\alpha}{2} - 1\right).$$

From this we can conclude:

a) at $\alpha < 2\arctg \frac{1}{2}$ the maximum height is $2R\cos^2\frac{\alpha}{2}$;

b) at $2\arctg \frac{1}{2} \leq \alpha < \frac{\pi}{2}$ the maximum height is $2R\sin \alpha$.

Let now $\alpha \geq \frac{\pi}{2}$. We noted above that the maximum value of the height $h_c$ is equal to $2R\cos^2\frac{\alpha}{2}$. Easily

⟦folio 48⟧

see that the values ​​of the functions $h_a$ and $h_b$ fill the interval $]0; 2R \sin^2 \alpha[$.
In the case under consideration, $2R \sin^2 \alpha > 2R \cos^2 \frac{\alpha}{2}$.
This means that at $\alpha \geq \frac{\pi}{2}$ the maximum height value is not achieved.

This problem can be solved more elegantly by using geometric considerations. Obviously $h_a \leq c$ and $h_b \leq c$. Therefore, at $\alpha < \frac{\pi}{2}$ the largest values ​​of $h_a$ and $h_b$ are $c$ (Fig. 9). This means that in this case we need to choose the larger numbers $h_c$ and $c$. When $\alpha$ is fixed, $c = 2R \sin \alpha$ is also fixed. $h_c$ obviously has the greatest value in an equilateral triangle (Fig. 10). Thus, in the case under consideration, we, as above, need to choose the largest of the numbers $2R \cos^2 \frac{\alpha}{2}$ and $2R \sin \alpha$.

If $\alpha \geq \frac{\pi}{2}$, then $h_a \geq h_c$ and $h_b \geq h_c$, and $h_a$ and $h_b$ do not reach the largest value equal to $c \sin(\pi - \alpha) = 2R \sin^2 \alpha$ (Fig. 11).

The attentive reader, of course, noticed that in all the problems analyzed we did not follow the rules from paragraph 59 of the manual “Algebra and the beginnings of analysis 9”. Essentially, this rule applies only to the case of a closed interval. If the interval of openings turns out to be the case, as was the case in almost all of our problems, the behavior of the functions on this interval requires special analysis!

The same problem will arise in the case of infinite intervals.

At the wife's
1. In a parabolic segment, the chord of which is perpendicular to the axis of symmetry of the paraboles (Fig. 12), inscribe a rectangle of the largest perimeter. (Chord length - $2a$, height - $h$).

Fig. 12.

2. In a triangle with base $a$ and height $h$ inscribe a rectangle of the largest perimeter, the two vertices of which lie on the base of the triangle.

3. Find the largest chord of the ellipse $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ passing through $B(0; -b)$.

4. Find the greatest and smallest distances from a point lying on the diameter of the resulting object to the points of the semicircle limiting it. Same question for the circular segment.

5 (DSU, Faculty of Biology, 1978). Find the largest and smallest values ​​of the functions $y = \sin 2x - x$ on [0; $\pi$].

6 (LSU, Faculty of Applied Mathematics - Control Processes, 1977). For what values ​​of the parameter $p$ is the smallest value of the cubic trinomial $x^3 - 2px^2 + 1$ on the interval $[0; 1]$ achieved at the right end of the interval?

7 (KhSU, physics department, 1978). Find the smallest value of the functions $y = \frac{1}{x} + \frac{q^2}{6 - x}$ on the interval [2; 3] depending on parameter $q$.
