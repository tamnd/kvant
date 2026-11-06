---
id: 1991-3-alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4
issue: kvant_1991_3
year: 1991
number: "3"
title: Minimum amount and minimum amount
authors:
  - Алексеев Р.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 51
page_last: 53
page_labels: 49, 51
lang: en
source: kvant_digital
extraction: vision
content_sha256: f268c664c236eae8a7ba676331fff93edab79c49a3366ef0572776c0d146396e
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/16_alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4.md
source_content_sha256: d44734c71d310315eace7ed1bc3e7f2c04120a36de3509418ad32267b4a4db3d
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 49⟧

Minimum amount and minimum amount

R. ALEXEEV,
L. KURLYANDCHIK

This article will discuss one general method with which you can prove many significant inequalities. The original idea is very simple. Two arbitrary functions $f(x)$ and $g(x)$, defined, say, on some segment $[a,b]$, reach their minima (generally speaking) at different points (Fig. 1). Inequality is fair

$$\min f(x)+\min g(x) \leqslant \min (f(x)+g(x)).$$

Fig. 1.

⟦folio 51⟧

---
running_head:
folio:
---

6) $(a_1^p + \ldots + a_n^p)^p \cdot (b_1^q + \ldots + b_n^q)^q \geq a_1 b_1 + \ldots + a_n b_n$ if $p > 0$, $q > 0$ are the same numbers as $\frac{1}{p} + \frac{1}{q} = 1$ (Hölder’s inequality).

Solution. As usual, let's consider $n$ functions
$$f_1(x; y) = a_1 x + b_1 y,$$
$$f_n(x; y) = a_n x + b_n y.$$

The most important thing is to choose the right set on which we consider our function. After all, our function is defined on the plane and we can find minima on any figure!

a) Consider a circle of radius 1 with center at the origin (Fig. 2). What does the geometric linear function $f(x; y) = ax + by$ mean? This is the scalar product of vectors with coordinates $(a; b)$ and $(x; y)$. But the scalar product is the product of the length of the vectors and the coisine of the angle between them. The cosine of the angle is minimal for collinear vectors, and the length of the vector $(x; y)$ does not change if the end of the vector lies on the circle. This means that the minimum of the function $f(x; y)$ is achieved on a vector with coordinates $(x_0; y_0)$, collinear $(a; b)$ (Fig. 3). Such a vector is equal to $(x_0; y_0) = \left( \frac{a}{\sqrt{a^2 + b^2}}; \frac{b}{\sqrt{a^2 + b^2}} \right)$, and the scalar product is equal to $(x_0; y_0) \cdot (a; b) = \sqrt{a^2 + b^2}$.

So, in the case of a circle
$$\min (ax + by) = \sqrt{a^2 + b^2}.$$

Now it costs us nothing to prove inequality a). On the left it contains the minimum values ​​of the functions $f_1, \ldots, f_n$

Fig. 3.
on the circle, and on the right is the minimum of their sum.

6) Let us take a set that consists of points $(x; y)$ for which
$$x^{\frac{1}{p}} \cdot y^{\frac{1}{q}} = 1.$$

Let us find the minimum of the function $f(x; y) = ax + by$ on this set. Of course, we could solve this not entirely simple analytical problem (and we advise readers to try to do this), but, fortunately, the stock of knowledge we have accumulated allows us to avoid this. Let's use inequality b) from Exercise 3:

$$ax + by = \frac{1}{p} \cdot pax + \frac{1}{q} \cdot qby \geqslant \frac{1}{p} \cdot (qby)^{\frac{1}{q}} = (pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}.$$

Check that the inequality is achieved if $\frac{x}{y} = \frac{b}{a}$. So, the minimum of the function $f(x; y)$ on our set is equal to $(pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}$. If we set $a = \frac{c^p}{p}$, $b = \frac{d^q}{q}$ (i.e., we take the linear function $\frac{c^p}{p} x + \frac{d^q}{q} y$), then this minimum turns out to be equal to cd. Well, what if we do the same with each of our functions $f_1, \ldots, f_n$:

$$a_1 = \frac{c^p}{p}, b_1 = \frac{d^q}{q}, \ldots,$$

$$..., a_n = \frac{c^p}{p}, b_n = \frac{d^q}{q},$$

then we get Hölder's inequality!

Now let's compare the Cauchy-Bunyakovsky inequality with the inequality

(For the ending see p. 55)
