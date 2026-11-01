---
id: 1977-7-ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54
issue: kvant_1977_7
year: 1977
number: "7"
title: Mean value of function
authors:
  - Ионин Ю. И.
  - Плоткин А. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 32
page_labels: 26-30
tag: 1YAJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 83be07d3a14457dbf424d68ccf43dcb0a93e380427a9a6004f7307a4545cc56a
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/08_ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54.md
source_content_sha256: f8bc7acc9952579c4b2606897992c7bb608a361547d6e3b4dcdb4e3ce88c4830
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Mean value of function

In this article, the concept of the arithmetic mean $n$ of numbers is generalized to functions defined on the segment, circle and sphere. In addition, it solves problem M394 («Kvant», 1976, no. 7).

1. On a finite set

Speaking at a class meeting, Makar Livanov said: “Let's fight to ensure that the performance of every student in our class is above average!” Apparently, Makar did not know mathematics very well. Let's figure it out.

As is known, the arithmetic mean $n$ of the numbers $x_1, x_2, \dots, x_n$ is the number $M = M(x_1, x_2, \dots, x_n)$ given by the equality

$$M(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2 + \dots + x_n}{n}.$$ (1)

Following Makar's recognition, we would have to achieve the simultaneous fulfillment of the inequalities $x_1 > M, x_2 > M, \dots, x_n > M$. Adding these $n$ inequalities, we obtain a contradiction with (1).

Let us note some important properties of the arithmetic mean:

I. $M(x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) = M(x_1, x_2, \dots, x_n) + M(y_1, y_2, \dots, y_n)$.

II. $M(\alpha x_1, \alpha x_2, \dots, \alpha x_n) = \alpha M(x_1, x_2, \dots, x_n)$.

III. $\min(x_1, x_2, \dots, x_n) \leqslant M(x_1, x_2, \dots, x_n)$.

In the yarn 1. Prove properties I-III.

U 2. Prove the inequality $C_{2n}^n > \frac{2^{2n-1}}{n}$ for $n > 1$. This is easy to do using the method of mathematical induction, but it can be done using property III.

Property III is often used as follows: to establish that the averages $x_1, x_2, \dots, x_n$ are numbers greater than $d$, it suffices to check that $M(x_1, x_2, \dots, x_n) > d$. Let us consider, for example, a problem proposed at the X All-Union Mathematical Olympiad.

Problem 1. Somehow there are 50 regularly running round clocks on a round table. Prove that at some moments the sum of the distances from the center of the table $O$ to the ends of the minute hands at the time $t$ hour, and after $d$ the sum of the distances from the point $O$ to the center of the clock. We need to prove that $f(t) > d$ is $t$ at some points. We will show that there is $t_0$ for which $M(f(t_0), f(t_0 + \frac{1}{2})) > d$.

This means that one of the moments $t_0$, $t_0 + \frac{1}{2}$ is exceptional.

Let us denote by $O_i$ the center of the $i$ hours, by $A_i$ the end of the minute hand of this clock at some moments $t$, by $B_i$ the end of the minute hand of the same hours half an hour later, i.e. at the moment $t + \frac{1}{2}$. Since, by condition, all clocks “run correctly,” there is a moment $t_0$ at which points $O, A_1$ and $B_1$ do not lie on the same straight line. Consider the triangle $OA_1B_1$ and the median $OO_1$ in it (Fig. 1). It is easy to prove that in any triangle the length of the median is less than half the sum of the lengths of the sides between which it is enclosed (prove it!). Therefore, at moment $t_0$ we have

⟦folio 27⟧

Fig. 1.

$$\frac{OA_1 + |OB_1|}{2} > |OO_1|.$$ For the remaining hours at this moment $$\frac{|OA_i| + |OB_i|}{2} \geq |OO_i|$$ (why only $\geq$ and not >?). Adding 50 inequalities, we get $M(f(t_0), f(t_0 + \frac{1}{2})) > d$.

2. On the segment

In Problem 1 it turned out to be sufficient to estimate the arithmetic mean of two function values. Is it possible to consider the average of all values? To resemble the definition of this concept, let us give a geometric meaning to the average $n$ of positive numbers $x_1, x_2, \dots, x_n$.

Divide some segment $[a; b]$ into $n$ equal parts and construct a stepped funkru consisting of rectangles, the bases of which are the resulting segments of length $\frac{b-a}{n}$, and the heights are, respectively, $x_1, x_2, \dots, x_n$ (Fig. 2). The area of ​​this step function is $M(x_1, x_2, \dots, x_n) \cdot (b-a)$. Thus, $M(x_1, x_2, \dots, x_n)$ is the height of a rectangle with base $[a; b]$, equal in area to the corresponding curve of the linear trapezoid (Fig. 3). Since in the case under consideration the area

Fig. 2.

this trapezoid is equal to $$\int_a^b f(x) \, dx$$ (Algebra and Elements of Analysis 10, item 101), $M(f)$ is defined by the formula

$$M(f) = \frac{1}{b-a} \int_a^b f(x) \, dx. \quad (2)$$

Definition (2) is suitable not only for a continuous and non-negative function, but also for any function defined on $[a; b]$, for which the right side of equality (2) makes sense.

So the definition of average value has properties similar to properties I-III:

I'. $M(f + g) = M(f) + M(g)$.

II'. $M(\alpha f) = \alpha M(f)$.

III. $$\min_{[a; b]} f \leqslant M(f) \leqslant \max_{[a; b]} f.$$ Exercise 3. Prove properties I'—III'.

Expression from I'-III' of property IV'. If $f(x) \leqslant g(x)$ for all $x \in [a; b]$, then $M(f) \leqslant M(g)$.

You have already come across the average value of a function on a segment in A. Vilenkin’s note “Buffon’s Needle” («Kvant», 1977, No. 5). Let us give another example of the application of this concept.

Task 2. On the data plane there are vectors $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ whose sum is 0. Prove the inequality

$$|\vec{a}| + |\vec{b}| + |\vec{c}| + |\vec{d}| \geqslant |\vec{a} + \vec{d}| + |\vec{b} + \vec{d}| + |\vec{c} + \vec{d}|. \quad (3)$$

Our solution to this problem will be based on its one-dimensional version:

⟦folio 28⟧

Fig. 3.

Exercise 5. Prove that if $a, b, c, d$ are real numbers whose sum is 0, then $|a| + |b| + |c| + |d| \geq |a+d| + |b+d| + |c+d|$.

Solution. If in (3) the vectors $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ are replaced by their projections onto some axis (“Geometry 9”), we get (4). An idea arises: prove (3) by considering the projections of these vectors $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ onto all possible axes. Let's try to implement it.

Let $\vec{p}$ be a vector. Let us introduce the auxiliary function $p$ as follows: fix some axis $l_0$; let us denote by $p(\alpha)$ the projection of the vector $\vec{p}$ onto the axis $l$, forming an angle $\alpha$ (Fig. 4) with the axis $l_0$. If $\varphi$ is the angle between the vector $\vec{p}$ and the axis $l_0$, then $p(\alpha) = |\vec{p}| \cos(\varphi - \alpha)$.

Consider the average value $M(|p|)$ of the function $\alpha \rightarrow |p(\alpha)|$ on the interval $[0; 2\pi]$. From definition (2)

$$M(|p|) = \frac{1}{2\pi} \int_{0}^{2\pi} |p(\alpha)| d\alpha =$$

$$= \frac{1}{2\pi} \int_{0}^{2\pi} |\vec{p}| \cos(\varphi - \alpha)| d\alpha =$$

$$= \frac{|\vec{p}|}{2\pi} \int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha.$$

Let us show the existence of a $k \neq 0$ such that for any vector $\vec{p}$ the equality

$$M(|\vec{p}|) = k |\vec{p}|.$$

(6)

By virtue of (5), it is sufficient to prove that the integral $\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha$ does not depend on the vector $\vec{p}$, that is, does not depend on the angle $\varphi$.

$$\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha = \int_{0}^{2\pi} |\cos(\alpha - \varphi)| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha = \int_{0}^{2\pi} |\cos \alpha| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha.$$

(7)

This calculation uses two properties of integrals:

$$\int_{a}^{b} f(x + p) dx = \int_{a+p}^{b+p} f(x) dx,$$

$$\int_{a}^{b} f(x) dx = \int_{a}^{c} f(x) dx + \int_{c}^{b} f(x) dx$$

⟦folio 29⟧

“Algebra and principles of analysis 10”, paragraph 106 and task No. 512). The central point of the calculation is to use the fact that $2\pi$ is the period of the function $\alpha \rightarrow \cos \alpha$.

The integral $\int_0^{2\pi} |\cos \alpha| d\alpha$ can be calculated (it is equal to 4), but all that is important to us is that it does not depend on $\varphi$ and is different from 0.

If $\vec{a} + \vec{b} + \vec{c} = 0$, then for any $\alpha$ we have $a(\alpha) + b(\alpha) + c(\alpha) + d(\alpha) = 0$. In force (4)

$$|a(\alpha)| + |b(\alpha)| + |c(\alpha)| + |d(\alpha)| \geq |a(\alpha) + d(\alpha)| + |b(\alpha) + d(\alpha)| + |c(\alpha) + d(\alpha)|.$$

(8)

Since (8) is satisfied for any $\alpha \in [0; 2\pi]$, it follows from properties IV' and I'

$$M(|a|) + M(|b|) + M(|c|) + M(|d|) \geq M(|a+d|) + M(|b+d|) + M(|c+d|).$$

From (6)

$$k|\vec{a}| + k|\vec{b}| + k|\vec{c}| + k|\vec{d}| \geq k|\vec{a}+d| + k|\vec{b}+d| + k|\vec{c}+d|.$$

Reducing by $k$, we get (3).

3. On the circle and sphere

Task 3. In the data space there are vectors $\vec{a}, \vec{b}, \vec{c}, \vec{d}$, the sum of which is 0. Prove inequality (3) for them.

I would like to prove (3) by changing the “flat dissection” (from task 2) into space. To do this, we need to somehow determine the average value of the model of vector projections onto all possible axes in space. To explain how this is done, consider first the function defined on a circle of unit radius.

Let $f$ be such a function. For an arbitrary $\alpha$ we set $f(\alpha) = f(A)$, where $A$ is the end of the path of our circle with radian measure $\alpha$ (Fig. 5). Thus, we associate an arbitrary function $f$, defined on the unit circle, with a certain function $f$,

defined on the entire straight line. Obviously, $f$ is a periodic function with period $2\pi$. Let us now define the average value $M(f)$ of the function $f$ on the circle as the average value of the function $f$ on the segment [0; 2π].

In the above solution to Problem 2, the key role was played by the inequality of the mean $M(|p|)$ from the direction of the vector $p$. This inequality is a partial case of the following general property of the average values ​​of a function on a circle:

$V'$. Let $f$ and $g$ be functions defined on a circle, and there is a maximum $\alpha$, which for any $A$ circle $g(A) = f(R^\alpha(A))$ (here $R^\alpha$ is the rotation of the vector of a given circle by an angle $\alpha$). Then $M(g) = M(f)$.

Exercise 6. Prove the property $V'$.

Going to Problem 3, consider a sphere of unit radius in space with the center at the origin $O$. For a function given on this sphere, the average value can be determined in such a way that properties $I$ - $V'$ are satisfied. We cannot explain here how this is done, since for this we would have to introduce interiorization by sphere. (This can be done using interral sums in approximately the same way as interAL is defined on a line in paragraph 104 of the textbook “Algebra and Elements of Analysis 10”.) Let us assume that the average value $M(f)$ of the function $f$ on the sphere is somehow determined, and the properties $I'$ - $V'$ are satisfied. (Thus, we consider the axiomatic assignment of the average value of the function

⟦folio 30⟧

tsini on the sphere. It is interesting to note that it is determined uniquely by the “axioms” $I' - V'$.)

Let $p$ be a vector. Let us introduce the auxiliary function $p$ as follows: for any point $A$ of our sphere we denote by $p(A)$ the projection of the vector $p$ onto the axis defined by the vector $\vec{OA}$.

Consider the average value $M(|p|)$ of the function $A \rightarrow |p(A)|$ on the sphere. Let us show the existence of a $k \neq 0$ such that for any vector $p$ (6) is satisfied. To do this, having deduced the properties of $II'$, it is enough to prove that $|\vec{p}| = |\vec{q}|$ implies $M(|p|) = M(|q|)$.

Do practice 7. Show that this is enough.

Let $|\vec{p}| = |\vec{q}|$. Let us denote by $R$ some rotation of the space around the axis passing through the point $O$, which transforms the ray with the direction vector $\vec{q}$ into the ray with the direction vector $p$. then for any point $A$ of the sphere $q(A) = p(R(A))$. From $V'$ follows $M(|q|) = M(|p|)$.

The further solution of problem 3 should repeat the solution of problem 2. (Exercise 5 and problems 2, 3 will exhaust problem M394.)

4. Length over width

The idea on which the solution to problems 2 and 3 is based can be used to calculate the length of a flat closed convex polyline.

Let $J$ be such a broken line, $a_1, a_2, \dots, a_n$ its links. We fix some axis $l_0$. Let $l_\alpha$ be the axis forming an angle $\alpha$ with the $l_0$ axis. Let us denote by $Ш(\alpha)$ the “width” of our broken line in the direction of the $l_\alpha$ axis, i.e., the length of its projection onto the $l_\alpha$ axis. It turns out that if you know the “width” of the broken line $J$ in an arbitrary direction, that is, be able to calculate the function $\alpha \rightarrow Ш(\alpha)$, then you can find its length $L$. We'll show you how to do it.

Let us denote by $a_i(\alpha)$ the length of the projection of link $a_i$ onto the axis $l_\alpha$.

Practice 8. Prove that $Ш(\alpha) = \frac{1}{2} [a_1(\alpha) + a_2(\alpha) + \dots + a_n(\alpha)]$.

In solving Problem 2, it was shown that the average value of the function $\alpha \rightarrow a_i(\alpha)$ is proportional to $|a_i|$. From (5) and (7), the proportionality coefficient is equal to $\frac{1}{2\pi} \int_0^{2\pi} |\cos \alpha| d\alpha = \frac{2}{\pi}$.

From Exercise 8 and the properties $I'$, $II'$, the average value $M(Ш)$ of the function $Ш$ is equal to the average value of the function $\alpha \rightarrow a_i(\alpha)$. Hence,

$$M(Ш) = \frac{1}{2} \left( \frac{2}{\pi} |a_1| + \right. \\ + \frac{2}{\pi} |a_2| + \dots + \frac{2}{\pi} |a_n|) = \\ = \frac{1}{\pi} \left( |a_1| + |a_2| + \dots + |a_n| \right) = \frac{1}{\pi} L.$$

From here and from (2)

$$L = \pi \cdot M(Ш) = \pi \cdot \frac{1}{2\pi} \int_0^{2\pi} Ш(\alpha) d\alpha = \\ = \frac{1}{2} \int_0^{2\pi} Ш(\alpha) d\alpha (9)$$

Thus, knowing the function $Ш$, we can find the length $L$ of the broken line $J$.

Practice 9. Prove that if the lengths of all sides and diagonals of a convex polygon are less than $d$, then its perimeter is less than $πd$.

Formula (9) is valid for any flat closed convex curve. The outlined method for determining length “through width” was proposed in 1930 by the famous Polish mathematician G. Steinhuz.

5. Amount length

Problem 4. On the data plane, there are vectors $a_1, a_2, \dots, a_n$ whose sum of length is equal to 1. Prove that the averages can be chosen for several vectors whose sum length is not less than $\frac{1}{\pi}$.

Solve this problem by following the plan below. Let $3$ be a subset of the set $\{a_1, a_2, \dots\}$.
