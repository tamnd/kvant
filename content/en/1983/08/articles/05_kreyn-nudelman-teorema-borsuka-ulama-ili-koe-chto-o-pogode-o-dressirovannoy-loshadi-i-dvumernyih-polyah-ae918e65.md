---
id: 1983-8-kreyn-nudelman-teorema-borsuka-ulama-ili-koe-chto-o-pogode-o-dressirovannoy-loshadi-i-dvumernyih-polyah-ae918e65
issue: kvant_1983_8
year: 1983
number: "8"
title: The Borsuk-Ulam theorem, or Something about the weather, a trained horse and two-dimensional fields
authors:
  - Крейн М. Г.
  - Нудельман А. А.
rubric: osnovnye-stati
page_first: 22
page_last: 26
page_labels: 20-24
tag: USG2
lang: en
source: kvant_digital
extraction: vision
content_sha256: dbd3ae226d7e397b97b961a0feb1179f47bdfff151337c8f16d8e57fc061ad92
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/05_kreyn-nudelman-teorema-borsuka-ulama-ili-koe-chto-o-pogode-o-dressirovannoy-loshadi-i-dvumernyih-polyah-ae918e65.md
source_content_sha256: c8143116ea3350b94248044c7f6ea0d4202da532f407230fc618230b22b4371f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

Weather
is considered topologically

Theorem
Borsuka -
Ulama

or
Something about the weather
about a trained horse
and two-dimensional fields

Corresponding Member of the Academy of Sciences of the Ukrainian SSR
M. G. CRANE,
Candidate of Physical and Mathematical Sciences
A. A. NUDELMAN

The weather is capricious and capricious. The parameters that describe it (for example, pressure, temperature, humidity) continuously change over time and when moving from one area to another. On weather maps, isobars can have the most whimsical (and, alas, not always predictable) shapes. And yet, no matter how bizarre the weather map of the globe may look, there is

Weather theorem. At every moment of time on the globe there is a pair of diametrically opposite points (“antipodes”), at which both temperature and pressure are the same.

This statement, clothed in a “meteorological” form, actually reflects not the properties of the earth’s atmosphere, but the properties of functions that are defined and continuous on the sphere. It belongs to topology - a branch of mathematics that, in particular, deals with the study of the properties of functions, or sets of functions, that are continuous on certain sets.

Some properties of such functions are determined by the structure of the set on which they are continuous. For example, for numerical functions studied in school, the geometric value is valid.

Theorem about the zero function. If the function f is continuous on the interval [a; b] and at its ends takes on the value of opposite signs, then between a and b there is a point x₀ at which f(x₀) = 0.

We do not provide a proof of this clearly obvious theorem, since, as it turns out, it is not elementary.

For the validity of the zero theorem, both the continuity of the function (why?) and that property of the segment, which is called connectedness, are essential

⟦folio 21⟧

(there are no “gaps” or “gaps” in the segment). Thus, the function $f(x) = \sqrt{(x^2 - 1)(4 - x^2)} + 2x$ is continuous on its domain of definition $[-2, -1] \cup [1, 2]$, negative on $[-2, -1]$ and positive on $[1, 2]$, and it does not vanish at any point.

This article talks about some properties of pairs of functions that are defined and continuous on the sphere. But we will teach from a simpler case - from one unexpected property of functions that are continuous on the circle.

Circle case: without raced horse

Let the circle horse, at the command of the trainer, start running around the rental circle from point $A$ and, finishing the turn, leave the lap at the same point. It turns out that no matter how its speed changes during the beta, it is possible to indicate two diametrically opposite rental points at which the horse’s speed has the same value.

Of course, the point here is not in the layout of the horse (which we will further imagine as a point), but in the property of continuous functions, which we will now understand.

We will determine the position of the horse $J$ on a circle with the area of ​​the angle $\Theta$ ($0 \leq \Theta \leq 2\pi$), which the radius $OJ$ forms with the radius $OA$ drawn at the initial point (Fig. 1); We denote the corresponding speed value by $v(\Theta)$. It is assumed that the function $v$ is continuous on $[0; 2\pi]$ (movement and stops are smooth), according to the condition $v(0) = 0$, $v(2\pi) = 0$. Point $J'$, diametrically opposite to point $J$, corresponds to angle $\Theta + \pi$ at $0 \leq \Theta \leq \pi$. It is required to prove the existence of such

Fig. 1.

for whom $\Theta_0 \in [0; \pi]$, for whom $v(\Theta_0) = v(\Theta)$.

Consider the function $u(\Theta) = v(\Theta + \pi) - v(\Theta)$. We need to find a $\Theta_0 \in [0, \pi]$ for which $u(\Theta_0) = 0$. The function $u$ is continuous on the segment $[0; \pi]$ (as the difference of continuous functions) and at the ends of this segment its values $u(0) = v(\pi) - v(0) = v(\pi)$ and $u(\pi) = v(2\pi) - v(\pi) = -v(\pi)$ either have opposite signs (if $v(\pi) \neq 0$, or are equal to zero (if $v(\pi) = 0$). In the latter case, $\Theta_0 = 0$; if $v(\pi) \neq 0$, then the existence of $\Theta_0$ follows from the zero theorem.

It is easy to understand that to prove the non-existence of the non-negativity of the function $v(\Theta)$ (while running around the arena, the horse can move in the opposite direction from time to time) and the conditions $v(0) = 0$, $v(2\pi) = 0$, only the equality $v(0) = v(2\pi)$ is essential (the horse can pass point $A$ from acceleration; it is important that it returns to this point with the same instantaneous speed).

It is obvious that $v$ can be considered as a function not of the number $\Theta$, but of the point $J$, therefore the proven theorem can be formulated as follows:

The theorem about the horse. If a certain function is defined on a circle and is continuous on it, then there are two diametrically opposite points on the circle at which this function takes the same values.

Mathematical formulas for theorems on paths

Let's translate the weather theorem into mathematical language. At a given point in time, each point $P$ of the earth's surface $S$ is assigned two numbers - pressure $f(P)$ and temperature $g(P)$ at this point. Thus, two functions are defined on the sphere $S$, which are assumed to be continuous on $S$ - with small changes in the position of the point $P$ the values ​​of these functions change little.

The exact definition of the continuity of a function on an arbitrary exact set $X$ (aligned on a line, in a plane or in space) can be formulated as follows:

⟦folio 22⟧

a function $\varphi$ is said to be continuous at a point $P_0 \in X$ if for any $\varepsilon > 0$ one can specify a $\delta > 0$ such that for every point $P \in X$ removed from $P_0$ by a distance less than $\delta$, the inequality $|\varphi(P) - \varphi(P_0)| < \varepsilon$ holds; a function is continuous on the set $X$ if it is continuous at every point of this set.

Let us agree that the antipode of the point $P \in S$ is denoted by $P'$ ($P$ and $P'$ are the ends of the same diameter of the sphere).

Abstracting from the “meteorological” meaning of the functions $f$ and $g$, we formulate the theorem in general form:

Borsuk-Ulam theorem a*). If the function $f$ and $g$ are defined and continuous on the sphere $S$, then on this sphere there are diametrically opposite points $P_0$ and $P'_0$, at which $f(P'_0) = f(P_0)$ and $g(P'_0) = g(P_0)$.

Let us introduce two functions $F(P) = f(P') - f(P)$ and $G(P) = g(P') - g(P)$. Both of them are continuous on $S$ and have the antisymmetry property; $F(P') = -F(P)$, $G(P') = -G(P)$, as, for example, $F(P') = f((P')') - f(P') = f(P) - f(P') = -F(P)$. For points $P_0 \in S$, in which there are $f(P'_0) = f(P_0)$, $g(P'_0) = g(P_0)$, and only for such points $F(P_0) = 0$ and $G(P_0) = 0$.

Therefore, the Borsuk-Ulam theorem follows from the following theorem:

Common zero theorem. If the function $F$ and $G$ are continuous on the sphere $S$ and have the antisymmetry property, then on the sphere $S$ there is a point $P_0$ at which both functions are equal to zero: $F(P_0) = G(P_0) = 0$.

**Theorema about zeros of vector fields**

The zero theorem gives sufficient conditions under which a function that is continuous on an interval has a “zero” on the interval. Now we will consider a theorem that gives a sign of the existence of a common “zero” for two functions that are continuous on the circle.

Let each point $Q$ of some flat set $K$ (in our case this will most often be a circle) be associated with a non-ctor vector $\vec{a}(Q)$ lying in the same plane. In this case, we say that the set $K$ is given a two-dimensional vector field (Fig. 2). A vector in a plane is specified using two coordinates, so specifying a two-dimensional vector field is equivalent to specifying two functions: $\vec{a}(Q) = (x(Q); y(Q))$.

A vector field is said to be continuous at the point $Q_0$ if both functions $x(Q)$, $y(Q)$ are continuous at this point; a field is continuous on a given set if it is continuous at every point. A vector field is called degenerate in the set $K$ if for some point $Q_0 \in K$ the vector $\vec{a}(Q_0)$ is zero. We need sufficient conditions for the degeneracy of a vector field continuous on the disk.

We first give a vector interpretation of the null theorem. On a straight line, a vector is given one coordinate. Therefore, specifying a function on a segment can be used as specifying a one-dimensional vector field (consisting of vectors that are located on the same straight line), and the null theorem can be formulated as follows:

Theorem on the zero of a one-dimensional field. If a segment is given a continuous one-dimensional vector field, and at the ends of the segment the corresponding vectors have opposite directions, then this field is degenerate (Fig. 3, a).

For the case of a two-dimensional field, this theorem is generalized as follows:

Theorem on the zero of a two-dimensional field. If a continuous two-dimensional vector field is given on a circle, and at any diametrically opposite points of its circle the corresponding vectors have opposite directions, then this field is degenerate (Fig. 3, b).

Like the one-dimensional null theorem, this theorem can be proven by means that go beyond the scope of the school course. But while in the theorem on the zero of a one-dimensional field this was compensated for visually, this cannot be said about the two-dimensional theorem. Therefore, we will present a “plausible reasoning” that we hope will convince the reader of the validity of this theorem.

⟦folio 23⟧

Let $O$ be the center of the circle and $K, r$ be its radius. The boundary circle of the circle $K$ is shaped by $C$, and by $C_u$ we are shaped by a concentric circle of radius $ar(C = C_1)$. Let $\vec{a}$ be a continuous vector field on $K$.
If $\vec{a}(Q) \neq 0$ is for all $Q \in C_u$, then when $Q$ moves along $C_u$ the vector $\vec{a}(Q)$ will somehow rotate. Let us denote by $v(C_u)$ the number of counterclockwise revolutions made by the vector $\vec{a}(Q)$ applied to a fixed point $I$ when the point $Q$ runs through the circle $C_u$ once counterclockwise $^*$). The integer $v(C_u)$ can be positive, zero or negative.
Let us clarify that if in the process of moving $Q$ along a certain arc of a circle $C_u$ the vector $\vec{a}(Q)$ makes several revolutions counterclockwise and the same number of revolutions clockwise, then when counting $v(C_u)$ these revolutions “mutually cancel out.”
We advise the reader to find $v(C)$ for the fields shown in figure 4 (the velocity field of the turning circle and the field formed by parallel transfer).

Let $\vec{a}(Q), Q \in K$ be a vector field satisfying the conditions of the theorem. By contradiction, suppose that $\vec{a}(Q) \neq 0$ for all $Q \in K$. Then, in particular, $\vec{a}(Q) \neq 0$. Due to the continuity of the field, since 0 all vectors $\vec{a}(Q)$ differ little in direction from $\vec{a}(0)$. This means that for small $\varepsilon_0 > 0$ we have $v(C_{\varepsilon_0}) = 0$ (see Fig. 5 - since the vectors on $C_{\varepsilon_0}$ are directed “almost in the same way” as $\vec{a}(0)$, the vector $\vec{a}(Q)$ does not completely increase $\varepsilon$ to the extreme value $\varepsilon = 1$. Since $\vec{a}(Q) \neq 0$ is everywhere, the number $v(C_{\varepsilon})$ is defined for all values of $\varepsilon, 0 < \varepsilon \leq 1$, that is, $v(C_{\varepsilon})$ is a function of $\varepsilon$ defined everywhere on $(0, 1]$. This function is continuous (since our field is continuous) and takes only the target value. But the integer function only changes.

*) Readers who have read the articles of S.V. Matveev in «Kvant», 1983, No. 4, are advised to compare this number with the “invariant $V$”.

⟦folio 24⟧

to jumps (in magnitude $\geqslant 1$), it is either discontinuous or constant. This means that in our case $v(C_\varepsilon) = \text{const}$, hence $v(C) = v(C_{\varepsilon_0}) = 0$.

Let us now take a point $A$ and a point diametrically opposite to it $A'$ (Fig. 6) on the circle $C$. Since the directions of vectors $\vec{a}(A)$ and $\vec{a}(A')$ are opposite, when point $Q$ moves along the semicircle $AmA'$ from point $A$ to point $A'$, vector $\vec{a}(Q)$ makes an odd number of half-turns. With further movement of the point $Q$ along the semicircle $A'nA$ from $A'$ to $A$, the vector $\vec{a}(Q)$ will make the same (and, moreover, in the same direction) number of half-turns. Consequently, $v(C)$ is an odd number, which contradicts the proven equality $v(C) = 0$ and completes our reasoning.

Proof of the common zero theorem

So, let the sphere $S$ be given continuous functions $F$ and $G$, which have the antisymmetry property $F(A') = -F(A)$, $G(A') = -G(A)$.

Let us draw a plane through the center $O$ of the sphere $S$. The circle obtained in the section will be denoted by $K$, and its circumference by $C$. Let us introduce in the secant plane some rectangular coordinate system with the origin $0$ and each point $Q \in K$ assign a vector $\vec{a}(Q)$ with coordinates $F(P)$ and $G(P)$, where $P$ is the point of the upper hemisphere that is projected to the point $Q$ (Fig. 7). We leave it to the reader to verify that the resulting vector field is continuous on $K$. Due to the property of antisymmetry on the sphere of functions $F$ and $G$, for all $Q \in C$ we have

$$\vec{a}(Q) = -\vec{a}(Q')$$

By the zero field theorem, there is a point $Q_0 \in K$ at which $\vec{a}(Q_0) = \vec{0}$. This means that $F(P_0) = 0$, $G(P_0) = 0$, where $P_0$ is a point on the sphere projecting to the point $Q_0$. The theorem has been proven.

One geographical consequence

One corollary follows from the Borsuk-Ulam theorem, which is distressing for geographers. The position of a point on the globe is usually indicated using geographic coordinates - latitude $\theta$ and longitude $\varphi$. They can be considered as functions of points on the earth's sphere. In this coordinate system, the poles occupy a special position: the latitude of each of them is $90^\circ$ (northern or southern), and any latitude can be assigned to it. Therefore, if you move, say, to the north pole along one meridian, and when you reach it, continue moving along any other meridian, then with this continuous movement the latitude will change continuously, and the latitude will experience a jump. If we agree to assign a “plus” sign to the eastern longitude and a “minus” sign to the western longitude, then the longitude experiences a jump when moving from the Western Hemisphere to the Eastern hemisphere along the meridian, which is the antipode of the Hryvnych meridian. The question arises: is it impossible to introduce coordinates over the entire surface of the sphere so that they are continuous functions of the corresponding point on the sphere? In this case, naturally, there should not be different points with the same coordinate parameters.
