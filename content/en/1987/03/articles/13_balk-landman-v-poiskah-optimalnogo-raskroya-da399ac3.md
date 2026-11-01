---
id: 1987-3-balk-landman-v-poiskah-optimalnogo-raskroya-da399ac3
issue: kvant_1987_3
year: 1987
number: "3"
title: In search of optimal cutting
authors:
  - Балк М. Б.
  - Ландман Г. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 46
page_last: 50
page_labels: 44-48
tag: S9UN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 62bc4a41e2d36d816a6a07bf24a7192139f25071aae441753058b18dc8334b6b
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/13_balk-landman-v-poiskah-optimalnogo-raskroya-da399ac3.md
source_content_sha256: aaf5de8e8693f6f5ea2eaeb1c50ed7f0fd712b82a90de9c998703d44ffb483f5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

In Japanese optimal cutting

Candidate of Physical and Mathematical Sciences
M. V. VALK,
G. M. LANDMAN

The children's toy factory was present for the mass production of a new product, one of the parts of which was a small polygon defining the shape and size (Fig. 1) made of thin tin. The factory had a machine that could easily and quickly cut rectangles of any given size from a sheet of tin. Therefore, technically, a decision was made: first cut identical rectangular blanks of the appropriate sizes, and then cut each such rectangular piece so as to obtain the required polygonal part from it. And the dimensions of the rectangles should, of course, be chosen so that the waste for trimmings is minimal. This is how a mathematical problem arose, the solution of which we will discuss in this article.

Main task. Specify an algorithm that allows, among all the rectangles P, which together contain the given polygon M, to select the one that has the smallest area.

We will call a rectangle that satisfies the conditions of this problem optimal. If any rectangle is a polygon M in itself, and there is not a single vertex of the polygon on the contour of the rectangle, then you can flatten the rectangle, that is, replace it with another rectangle of a smaller area, also containing the polygon M. To do this, it is enough to translate parallel to itself each of the four straight lines containing the sides of the rectangle M so that they (after the change) already pass through some vertices of the polygon M. To figure 1, such a “improved” rectangle (compared to P) is P′.

It is customary to call a support line for a given polygon M any line that contains at least one point on the contour of the polygon and does not contain any of its internal points (for example, on figure 1 lines a and b are support lines for the polygon M, and line c is not a support line). A rectangle, all four sides of which lie on the supporting lines for the polygon M, will be called circumscribed about M. Such

⟦folio 45⟧

The rectangle $\Pi'$ is on figure 1. As soon as we have chosen the reference line $(a)$ for the given polygon $M$ (Fig. 1), we have thereby already uniquely defined the rectangle described around $M$. The rectangle described around $M$ obviously has the property that at least one vertex of the polygon (Fig. 1) can be placed on each of its sides (perhaps at its end). Of the two rectangles described around a given polygon $M$, we will call the one with the smaller shifu area the best. The optimal rectangular shape discussed in the main problem should obviously be sought among the rectangular shapes described around $M$.

Plant technologists expressed two hypotheses:

Hypothesis I. The optimal rectangle for the polygon $M$ is the described rectangle in which one side contains the most diverging side of the polygon.

Hypothesis II. The optimal rectangle is that described rectangle in which one side is parallel to the widest point of the polygon.

At this stage the problem was proposed to mathematics.

Where did the mathematician start?

Matematik began with a completely seemingly uninteresting and sparsely meaningful question: “Is the optimal rectangular shape even essential?”

Let us select some point $O$ on the plane and draw the axis $l_0$ (Fig. 2a) through it. Then we draw an arbitrary ray $l = l_\varphi$ through $O$ and empty it forms an angle $\varphi$ with the axis $l_0$. We can construct for the polygon $M$ a reference line parallel to the ray $l$, and then that (uniform) circumscribed rectangle $P$, two sides of which are parallel to the ray $l$; Let's denote its area by $S(\varphi)$. We will change the angle $\varphi$; empty this angle increases from 0 to $\pi$; in this case, the rectangle $P$ will also change, and we will obtain all possible rectangles described around $M$; $S$ will also continuously change (i.e., with a small change in the angle $\varphi$, the value $S(\varphi)$ will also change little). But a function that is continuous on a certain segment (in our case, on the segment [0; $\pi$]) must take at some (at least one) value $\varphi$ from this segment its minimum value (“Algebra and Principles of Analysis 9-10”, p. 89). This means that there is an angle $\varphi$ such that the corresponding rectangle described around $M$ will have the smallest possible area (will be optimal). In other words, among the rectangles described around the polygon $M$, calling there (at least one) optimal.

Having confirmed the existence of a solution, the mathematician began to search for it.

Consider an arbitrary polygon - non-convex or convex. Listen for a non-convex polygon, however, it is easy to apply the properties to the case of a convex polygon. Indeed, empty $M$ is a non-convex polygon. Consider the smallest convex polygon $M'$ containing the polygon $M$ ($M'$ is called the convex hull of the polygon $M$, Fig. 26). It is easy to understand that the rectangle $P$ contains the polygon $M$ if and only if it contains its convex hull $M'$. Therefore, the problem of finding an optimal rectangle for the polygon $M$ is equivalent to the same problem for the convex polygon $M'$.

To get rid of it, try it first in the simplest special case, when $M$ is a triangle.

Solving the problem for a triangle

Let $M$ be the triangle $ABC$, and $P$ be some rectangle described around $M$. There must be at least one triangle vertex on each of the four sides of the rectangle. Therefore, at least one vertex of the triangle “serves” two

⟦folio 46⟧

sides of the rectangle $\Pi$, being their common end. However, the remaining two vertices can be located differently on the sides (or inside) of the rectangle, and there may be 4 fundamentally different cases (figure 3, $a-ε$) depending on their location.

Let us denote the area of ​​the triangle $ABC$ by $\sigma$, and by $S$ the area of ​​the rectangle $\Pi$.

In the case of $\sigma$ we obviously have: $S=2\sigma$.
In case of $\varepsilon$ and $\varepsilon$): $S>2\sigma$.

What is the situation in the case of $a$)? Let us draw a parallel through $B$ to side $AK$ of the rectagon and mark the points $F$ and $D$ of its meeting with the side of the triangle and the side of the rectagon. Then
$$S=S_{AKBD}+S_{BDNL}>2S_{BFA}+2S_{BFC}=2\sigma,$$
i.e. $S>2\sigma$.

We see that the optimal rectangle appears only in the case $\sigma$). Thus, among the described rectangles containing a given triangle $M$, the optimal one is one whose base coincides with the side of the triangle; in this case, the area of ​​optimal rectangular input is greater than the area of ​​the triangle. It is clear that if a triangle is obtuse, then there is only one such optimal rectangle. In the case of a scalene acute triangle, there are three optimal rectangles. It is also possible that there are two optimal rectangles (for example, if the triangle is rectangular).

The algorithm for obtaining the optimal rectangle is very complex.

But what about the quadrilateral?

The method of solving the present discussed above is simple, and it doesn’t even occur to you to look for another method. Meanwhile, our method has one major drawback: it does not transfer to the case of a polygon with more than three sides. Therefore, let's figure out what other, more promising approach could - in the case of a triangle - lead us to a solution. In the case of $a$), we could calculate the total area of ​​the cut triangles (we denote it by $T$), expressing it through the angle $t$ (the angle of inclination of the side of the triangle $AB$ to the reference line $AK$) and through the elements of the triangle; it can be shown that this sum has the form
$$T=T(t)=A_1\sin 2t+A_2\sin(2t+\theta_2)+A_3\sin(2t+\theta_3),$$
where $A_1, A_2, A_3, \theta_2, \theta_3$ are some numbers that do not depend on $t$ (but depend only on the elements of the triangle $ABC$). We could then try to discard those values ​​of $t$ for which this sum complete does not take a minimum value. This method in the case of a triangle may seem unreasonably cumbersome, but in the case of a quadrilateral and other polygons it leads to a solution - and, as it turns out, is not so difficult.

Let's form two simple facts in the form of problems that we will need in the future (solutions in one of the following issues).

Task 1. Each sum of the form
$$T(t)=A_1\sin(2t+\theta_1)+A_2\sin(2t+\theta_2)+\dots+A_m\sin(2t+\theta_m)$$
can always be brought to mind
$$T(t)=\rho\sin(2t+\theta),$$
(1)
where $\rho \geq 0$ and the numbers $\rho$ and $\theta$ depends only on the numbers $A_1, \dots, A_m, \theta_1, \dots, \theta_m$ (but does not depend on $t$).

Task 2. If for all values ​​$t$ from some integral of the form $(t_0-\varepsilon; t_0+\varepsilon)$ (the ends are not included) the function $\sin(2t+\theta)$ is non-negative, then there is a value $t_1$ on this integral such that the strict inequality is true:
$$\sin(2t_1+\theta)<\sin(2t+0).$$
(2)

The case of an arbitrary $n$-gon

Let $M$ be an arbitrary convex $n$-gon ($n \geq 4$), and $\Pi_0$ be a

⟦folio 47⟧

Somebody described about him is a rectangular one. First, consider those cases when no side of the polygon $M$ lies on the side of the rectangle $\Pi_0$. With this requirement, there can be no more than four vertices of the polygon $M$ on the contour of the rectangle $\Pi_0$. In this case, the following three options are possible:

I. Two vertices of the polygon $M$ serve as the ends of the diagonal of the rectangle $\Pi_0$, and the remaining vertices $M$ - inside $\Pi_0$, Fig. 4, a).

II. One vertex of the polygon $M$ serves as a vertex of the rectangle $\Pi_0$, two vertices of the polygon $M$ are internal points of two sides $\Pi_0$, and the remaining vertices $M$ are inside $\Pi_0$, Fig. 4, c).

III. Some four vertices of the polygon $M$ are interior points of the four sides of the rectangle $\Pi_0$, and the remaining vertices of the polygon $M$ lie inside $\Pi_0$, Fig. 4, c).

All three options are considered using the same method: the area of ​​the described rectangle is calculated and it is found out whether it is possible to improve it by “small movement”, that is, to obtain a described rectangle with a smaller area; if it turns out that it is possible, then the rectangle $\Pi_0$ under consideration is not optimal.*)

We will consider here option I - the simplest. Let us denote by $A$ and $C$ those two vertices $M$ that serve as the ends of the diagonal of the described rectangle $\Pi_0$ ($F_0K_0L_0N_0$). Let $AB$ be the side of $M$ lying inside $\Pi_0$ (except for the end $A$); we can assume that $AB$ is in $\triangle F_0K_0L_0$. Let us denote the values ​​of the angle $BAK_0$ by $t_0$, the values ​​of the angle $CAB$ by $\lambda$. We calculate the area $S_{\Pi_0}$:

$$S_{\Pi_0} = \frac{1}{2} AC^2 \sin (2t + 2\lambda).$$

By virtue of Problem 2, there is an angle $t$ on the interval $(t_0 - \varepsilon; t_0 + \varepsilon)$ such that $\sin (2t + 2\lambda) < \sin (2t_0 + 2\lambda)$, and therefore $S_{\Pi_0} < S_{\Pi_0}$. This means that the rectangular $\Pi_0$ appearing in option I is not optimal: it can be “improved”. We leave the analysis of the remaining two cases to the reader as tasks.

Task 3. Prove that in option III the rectangle $\Pi_0$ is not optimal.

Task 4. Prove that in option II the rectangle $\Pi_0$ is not optimal.

We see that so far the described rectangle does not contain any side of the polygon $M$ (see variant).

*) For more details on the example of “small movement” see «Kvant», 1979, No. 4, p. 4 or the book Balk M.V., Balk G.D. Poshk solutions, M.: Children's literature, 1983, p. 86.

Fig. 4.

Fig. 5.

⟦folio 48⟧

you I, II, III), it cannot be optimal. But the optimal rectangle, as we already know, exists. Thus, the mathematician obtained the following solution algorithm.

Algorithm for solving the main problem
1) If a given $n$-gon $M$ is convex, then draw all the circumscribed rectangles containing at least one side of the polygon (there are at most $n$ such rectangles).
2) Calculate the areas of these rectangles and choose among the rectangles all those whose area is the smallest. Each of them is an optimal rectangle for the $n$-gon under consideration. There are no other optimal rectangles.
3) If the polygon $M$ is non-convex, then first construct the convex hull $M'$ for it, and then find the optimal rectangle for the polygon $M'$ - it will also be the optimal rectangle for the polygon $M$.

When Japanese becomes simpler
We have seen that finding the optimal rectangle for a given convex $n$-gon $M$ involves searching through at most $n$ rectangles. There are important cases when this search is simplified. We formulate them in the form of tasks. Here it should be taken into account that a convex $n$-gon, other than a rectangle, has no more than three non-obtuse angles (otherwise the sum of the angles will not be equal to $180^\circ$ ($n-2$)).

Problem 5. Let some convex polygon $M$ have only one side to which two non-obtuse angles are adjacent. Prove that then among the rectangles described around $M$ there is only one optimal one - the smallest one. If such a thing exists, how to find it?

7. Let $M$ be a given convex $n$-gon. Let $\{A_1, A_2, \dots, A_k\}$ be all possible convexities of a $k$-gon with a given angle $a_1, a_2, \dots, a_k$ ($a_1 + a_2 + \dots + a_k = (k-2)n$), described around the $n$-gon $M$. Prove that if among these $k$-gons there is one whose area is minimal, then at least one of its sides contains the side of the $n$-gon $M$ (so there are no more optimal $k$-gons than $n$).
