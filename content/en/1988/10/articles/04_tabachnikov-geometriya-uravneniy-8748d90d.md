---
id: 1988-10-tabachnikov-geometriya-uravneniy-8748d90d
issue: kvant_1988_10
year: 1988
number: "10"
title: Geometry of equations
authors:
  - Табачников С. Л.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10, 12, 13, 14
tag: 78MB
lang: en
source: kvant_digital
extraction: vision
content_sha256: b10529f4a243a94dc0cd19a855f5a4ab497f2f2dd6f8a39161a576458075576d
prompt_sha256: draft-1
translated_from: content/ru/1988/10/articles/04_tabachnikov-geometriya-uravneniy-8748d90d.md
source_content_sha256: 4946103164b5a01900ed8d38d3d3134e074190a9a61c8d05dc80e606bc9d8835
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

GEOMETRY OF EQUATIONS

Candidate of Physical and Mathematical Sciences
S. L. TAVACHNIKOV

The reader has probably seen funny pictures, the eyes of which are difficult to decide what exactly is depicted. Here in front of you is a bizarrely shaped base; suddenly, instead of a cry, you see two profiles formed towards each other... In mathematics, too, sometimes it is possible to look at a familiar thing in a new way, and this new look often turns out to be fruitful.

Equation $x^2+px+q=0$

What do you see, eyes on equality $x^2+px+q=0$? Well, of course, a quadratic equation with parameters $p$ and $q$, that is, a family of quadratic equations, one for each pair of values ​​$p$ and $q$. Let's look at the equation $x^2+px+q=0$ differently - as a linear relative of the variables $p$ and $q$; $x$ will be a parameter in this case. For example, with $x=-1$ you get the equation $1-p+q=0$, and with $x=2$ you get the equation $4+2p+q=0$. In general, for each $x$ you get your own linear equation with the variables $p$ and $q$. A linear equation defines a straight line on a plane with coordinates $(p, q)$. Consequently, the equation $x^2+px+q=0$ defines a family of lines on the $(p, q)$-plane - one for each value $x$.

Let's draw several straight lines of this family - figure 1. Looking at this figure, it is difficult to resist the temptation to check the curve that touches all the drawn straight lines. Such a curve, similar to a parabolic, is depicted in figure 2. This curve is called the *ozibating* of this family of lines. We see a little later that what is depicted in this case will really be parabolic. For now, we will consider the family of lines $x^2+px+q=0$ on the $(p, q)$-plane as a family of tangents to this image.

By the way, the existence of an envelope is not a specific property of the family of lines depicted in figure 1. For any one-parameter family of lines in general position, that is, a family in which lines with close parameter values ​​are not parallel and do not pass in threes through one point, an envelope can be constructed. Moreover, the envelope exists not only for a family of straight lines, but also for a family of curves on a plane.

On figure 1 on each line its “number” is written, i.e. the value $x$ at which the equation $x^2+px+q=0$ defines exactly this line. It is more convenient to write the number of the line on the envelope at the point of its tangency with this line. Then a box will appear on the envelope, “numbering” the lines of our family (Fig. 2).

Figure 2 can be used as a “machine” for solving the quadratic equation $x^2+px+q=0$: if the values ​​$p$ and $q$ are given, you need to pass through the point with coordinates $(p, q)$ the tangent to the envelope and read the value of the root of the equation $x^2+px+q=0$ on the cabinet at the point of tangency. In particular, the number of roots for the given $p$ and $q$ is equal to the number of tangents that can be drawn from the point $(p, q)$ to the envelope (Fig. 3).

It is clear that if the point $(p, q)$ lies under the envelope, then there are two such tangents; and if higher, then none. What about the points of the envelope itself? Only one tangent can be checked through these points. Therefore, the corresponding quadratic equations each have one (multiple) root.

So, the envelope of our family of lines is the set of points $(p, q)$ such that the equation $x^2+px+q=0$ has a multiple root. It's time to remember that we can solve a square -

⟦folio 12⟧

the number of roots of the equation, and the numbers of these lines are equal to the roots. Therefore, figure 6 is a cubic equation solving machine.

Figure 7 shows how the number of solutions depends on the position of the point $(p, q)$. We see that in any case at least one tangent to the tank will be found, so

A cubic equation has at least one root.

The final result of the study is presented on figure 8. This could be the end of the study of the cubic equation, if not for one circumstance: we still do not know what equation defines the curve in Figures 6-8.

Exercises
3. Prove that any polynomial of odd degree has a root. Hint: Find the sign of the polynomial at $x=-\infty$ and $x=+\infty$.
4. Investigate the geometric number of roots of the polynomial $x^3+px+q$ on the segment $[-1; +1]$.

A digression on multiple roots

The curve shown in Figures 6-8 consists of points $(p, q)$ such that the equation $x^3+px+q=0$ has a multiple root. With the same $p$ and $q$ will this happen?

If the number $t$ is the root of the polynomial $f(x)$, then $f(x)$ is divisible by $x-t$. If the number $t$ is a multiple root, then $f(x)$ is divisible by $(x-t)^2$. For example, 1 is a multiple root of the polynomial $x^3-3x+2=(x-1)^2(x+2)$.

Let us write the equality $f(x)=(x-t)^2g(x)$ and calculate the derivative:

$$f'(x)=2(x-t)g(x)+(x-t)^2g'(x).$$

If we substitute $x=t$ into this equality, then the right part will go to zero. So, $f'(t)=0$. Hence,

The number $t$ is a multiple root of a polynomial if and only if $t$ is the common root of that polynomial and its derivative.

(To be honest, we have only proven the postulate of this theorem: if $t$ is a multiple root, then $f'(t)=0$. By-

⟦folio 13⟧

try to prove the second half of the theorem yourself.)

Let us apply the multiple root test to the polynomial $x^3+px+q$. If the number $t$ is a multiple root, then $t^3+pt+q=0$ and $3t^2+p=0$ are. Expressing $p$ from the second and $q$ from the first equation, we get

$$p=-3t^2, q=2t^3 \quad (t \text{ — любое число}).$$

These equations define the envelope in parametric figures 6–8: when $t$ changes from $-\infty$ to $+\infty$, point $(-3t^2, 2t^3)$ runs through the entire curve with the beak. If it’s more pleasant for you to define the curve with one equation, then you need to get rid of $t$ (raising the first equation into a cube, and the second - into a square):

$$4p^3+27q^2=0.$$

This equation also defines our beak curve. From the equation we can see that $q$ is proportional to $p^{3/2}$. Therefore, the curve is called a semi-cubic parabola (if $q \sim p^3$, then the parabola is cubic; our exponent is half as large, so the parabola is semi-cubic).

The expression $4p^3+27q^2$ is called the discriminant of the cubic equation. The number of roots of the equation depends on the sign of the discriminant.

Exercise 5. How many roots does the polynomial $x^3-10x+12$ have?

6. Investigate the geometric dependences of the number of roots of the polynomial $x^5+px^2+q$ on its coefficients.

7. Prove that the equation $x^{1988}+px+q=0$ has at most two roots, and the equation $x^{1989}+px+q=0$ has at most three roots.

Dual curves

Consider the equation

$$l+kp+q=0. \quad (*)$$

For each pair of values ​​$k$ and $l$, this equation defines a non-vertical line in the plane with coordinates $p$ and $q$, and in this way all non-vertical lines are obtained. This means that the set of non-vertical lines of the $(p, q)$-plane can be identified with the set of pairs of $(k, l)$, i.e., from the point of the $(k, l)$-plane. Let's look at equation (*) again. For each pair of values ​​$p$ and $q$, this equation defines a non-vertical line on the $(k, l)$-plane. This means that the points of the $(p, q)$-plane can be identified with the non-vertical straight line of the $(k, l)$-plane.

So, we have two planes - with coordinates $(p, q)$ and with coordinates $(k, l)$. The points of each of them can be perceived as non-vertical straight lines of the other. These planes are called `двойственными`. On figure we will depict the $(p, q)$-plane with it in color, and the dual $(k, l)$-plane in red. Points on the blue plane are designated by capital letters, straight lines by lowercase letters. On the red plane, everything is reversed: the straight lines corresponding to the points are indicated by the same capital letters, and the points corresponding to the straight lines are indicated by the same lowercase letters. Look at figure 9. It shows simple figures consisting of a point and lines, and their corresponding figures on the dual plane.

Exercise 8. What figures are dual to the last two figures on figure 9?

Let the curve $\gamma$ be drawn on the blue plane. It would be nice to determine the corresponding dual curve on the red plane. The points on the red plane are straight blue; Therefore, it is necessary to associate with the curve $\gamma$ a family of straight lines of the blue plane. You have probably already agreed on how to do this: with the curve $\gamma$ you need to associate a family of its tangent lines. So, the definition:

Let $\gamma$ be some curve. A dual curve (on a dual plane) is a curve consisting of all tangent lines to the curve $\gamma$.

The dual curve is denoted by $\gamma^*$.

Of course, this definition assumes that $\gamma$ has no vertical tangents.

The definition of this, but how to use it is unclear. For example, what curves are dual to quadratic and cubic parabolas? It would be possible, of course, to set parabolas

⟦folio 14⟧

equations, write down the tangent equations, find their angular coefficients $k$ and free terms $l$ and construct the corresponding curves on the $(k, l)$-plane. However, this path is not very attractive. Let's try to understand the behavior of dual curves without calculations.

Let the curve $\gamma$ rotate smoothly in one direction (see Fig. 10,a). The tangent to $\gamma$ also rotates, i.e. the dual curve moves in the same direction. But now the curve $\gamma$ begins to turn in the other direction - a *over-tooth* appears at the point. What happens to the tangent? Before the moment of inflection, the tangent moved in one direction, and after the inflection, in the other. This means that the dual curve $\gamma^*$ changes the direction of movement to the opposite at the moment of inflection (see Fig. 10, b). On the dual curve there is an acute one! These messages are already sufficient to avoid curves dual to quadratic and cubic parabolas (Fig.11).

Exercises
9. How will the presence of a double tangent at the curve $\gamma$ - figure 12,a - be reflected on the dual curve?
10. Draw a curve dual to the curve at figure 12b.

The dual planes are completely equal - each of them is reflected with many non-vertical straight lines of the other. What about dual curves? Is it true that if we construct from the blue curve $\gamma$ the red curve $\gamma^*$, and then from the red curve $\gamma^*$ the blue curve $(\gamma^*)^*$ dual to it, then we get the original curve $\gamma$? Iltucia suggests an affirmative answer; To justify it, let’s figure out how the curve $(\gamma^*)^*$ is structured.

Consider the curve $\gamma^*$. To determine the curve dual to it, we need to consider the tangents to $\gamma^*$. Instead of a tangent, we take two close points $l$ and $m$ on $\gamma^*$ and draw a straight line $A$ through them - see the red part figure 13. What picture appears on the blue plane? Points $l$ and $m$ correspond to straight lines $l$
