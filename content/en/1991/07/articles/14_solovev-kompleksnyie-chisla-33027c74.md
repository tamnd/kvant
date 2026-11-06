---
id: 1991-7-solovev-kompleksnyie-chisla-33027c74
issue: kvant_1991_7
year: 1991
number: "7"
title: Complex numbers
authors:
  - Соловьёв Ю. П.
rubric: shkola-v-kvante
page_first: 49
page_last: 55
page_labels: 47, 49, 50, 51, 52, 53
lang: en
source: kvant_digital
extraction: vision
content_sha256: d9265b42d73557b19a8bed912c8eb385e122c405aef1e1c9c52494a6d0c2fefb
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/14_solovev-kompleksnyie-chisla-33027c74.md
source_content_sha256: 78904b3e41ba58650dfdb72a26edd0bdd52696331fc8a8f11f8693baa9d23161
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

Matematika 9 — 11
Complex numbers
Doctor of Physical and Mathematical Sciences
Y. SOLOVIEV

Already in ancient times, when solving problems written in modern language as quadratic equations, mathematicians encountered situations in which it was necessary to extract roots from negative numbers. In such cases, the problem was considered unsolvable. However, the solution in radicals of the cubic equation, found by Illyan mathematicians in the first half of the sixteenth century, led to the expression of the real roots of the equation in terms of square roots of negative numbers. This forced mathematicians to operate with new numbers, applying to them the same rules of operation that real numbers obey.

Consider the problem of extracting the square root of a negative number $\sqrt{-a}$. Since the square of a real number is always positive, such a problem in the field of real numbers is impossible. We need some new numbers:

$$\sqrt{-a} = \sqrt{a} \cdot \sqrt{-1} = \sqrt{a} \cdot i,$$

where $i = \sqrt{-1}$, $i^2 = -1$ is the designation of a new, non-real number called the minimum unit.

Numbers of the form

$$a + bi,$$

where $a$ and $b$ are real numbers, called complex numbers; the number $a$ is called the real part, and the number $b$ is called the minimum part. At $a = 0$ the complex number becomes the minimum number $bi$; with $b = 0$ we get the number $a + 0i$, which is considered as a real number $a$.

Complex numbers of the form $z = a + bi$ and $z = a - bi$ are called conjugates, complex numbers of the form $a + bi$ and $-a - bi$ are called opposites. The set of complex numbers is usually denoted by $C$.

Conditions to consider complex numbers $a + bi$ and $c + di$ equal if and only if $a = c$ and $b = d$.

From this definition it follows that the complex number $a + bi$ is equal to zero if and only if $a = 0$ and $b = 0$. In fact, the real number 0 can be represented as a complex number as $0 + 0i$. Based on the definition, the equality $a + bi = 0 + 0i$ will only hold if $a = 0$ and $b = 0$ are met.

Note that with regard to complex numbers, it is not agreed upon which one is considered greater than the other.

Utterance
1. Find $x$ and $y$ for which

$$(2x + 3y) + (x - y)i = 2 + (2x + y)i.$$

2. Find complex numbers, opposites and conjugates of numbers

a) $2 + i$; 6) $1 + i$.

3. What complex numbers coincide with the properties of their conjugates? Opposite?

⟦folio 49⟧

---
running_head:
folio:
---

$$a + bi = (x + yi)^2 = (x^2 - y^2) + 2xyi,$$
i.e.
$$x^2 - y^2 = a, 2xy = b.$$

Consequently, the task comes down to finding real solutions to this system. By squaring both equations and then adding them, we get $(x^2 + y^2)^2 = a^2 + b^2; x^2 + y^2 = \sqrt{a^2 + b^2},$ (only the positive root is taken, since $x^2 + y^2 > 0$). Now from the equation
$$x^2 + y^2 = \sqrt{a^2 + b^2}, x^2 - y^2 = a$$
we find
$$x^2 = \frac{\sqrt{a^2 + b^2} + a}{2}, y^2 = \frac{\sqrt{a^2 + b^2} - a}{2}.$$

For $x$ and $y$ we have two values ​​each, which gives four combinations $(x; y)$, however, from the conditions $xy = b/2$ it follows that the sign of the product $xy$ must coincide with the sign of the number $b$; this gives only two pairs of values ​​of $(x; y)$, i.e. two roots:

$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} + i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b > 0,$$
$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} - i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b < 0.$$

Exercise 6. Calculate
a) $\sqrt{1 + i}$; 6) $\sqrt{3 + 4i}$;
b) $\sqrt{4 - 3i}$;
d) $\sqrt{\cos \alpha + i \sin \alpha}$ ($0 < \alpha < \pi$);
e) $\sqrt{\cos 2\alpha - i \sin 2\alpha}$.

Solving a quadratic equation
It is well known that not every quadratic equation can be solved in real numbers; the condition for solvability is the non-negativity of its discriminant $D = b^2 - 4ac$. In number complexes this exception disappears. If $D < 0$, then the solution to the quadratic equation is found by the formula
$$x_{1,2} = \frac{-b \pm \sqrt{|D|} \cdot i}{2a}.$$

In other words, whatever the coefficients $a, b$ and $c$ of the quadratic equation
$$ax^2 + bx + c = 0,$$
 its solution is found by the formula
$$x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}.$$

Note also that this formula allows you to solve quadratic equations with complex coefficients $a, b, c$. After all, we already have known square roots of any complex numbers.

Exercises
7. Solve Quadratic Equations
a) $x^2 + 2x + 2 = 0$;
b) $x^2 + (1 + i)x + i = 0$;
b) $ix^2 - 2x + 1 = 0.$

8. Find all roots of the (complex) equation
a) $x^3 = 1$;
b) $x^4 = -1$;
b) $x^4 + x^2 + 1 = 0.$

Geometric interpretation of complex numbers

The word “complex” translated from Latin means “composite”, “complex”. Despite the fact that operating with complex numbers is no more difficult than with real numbers, until the beginning of the nineteenth century complex numbers were considered a very complex, dark, almost mystical object. With tenacity worthy of better use, weight is a long struggle between the parties and opponents of the “minimum” numbers. The main objection of opponents was the following: an expression of the form $a + bi$ is meaningless, since $i$ is not a real number, and therefore is not a number at all; therefore $i$ cannot be multiplied by real numbers.

⟦folio 50⟧

---
running_head:
folio:
---

To put the theory of complex numbers on a solid foundation, it was necessary to have an explicit construction of them, preferably a geometric one. The desire to have a geometric realization of a set of complex numbers is not accidental, if we remember that the set of real numbers is not separable for us from a “real straight line” with a fixed point on it representing zero, and with a fixed scale determined by the position of the number 1.

For the first time, a geometric representation of actions on complex numbers was given by the children's surveyor K. Vesel in 1799 and, independently of him, by the French mathematician J. Arganov in 1806. However, it received general recognition only in the thirties, centuries after the work of the German mathematician F. Gauss and the English mathematician W. Hamilton. The idea of ​​the geometric interpretation of complex numbers is that they are represented not by points on a line, like real numbers, but by points on a plane.

So, let's construct a set whose elements were points of the plane, and the addition and multiplication of points would obey all the rules of operations with real numbers.

Let us choose a direct coordinate system in the plane with the abscissa axis $x$ and the ordinat axis $y$. Let us denote by $(a; b)$ the point with the abscissa $a$ and ordinate $b$. For points $(a; b)$ and $(c; d)$ we determine the sum and product according to the rules:

$$
(a; b) + (c; d) = (a + c; b + d),
$$

$$
(a; b) \cdot (c; d) = (ac - bd; ad + bc).
$$

Direct verification easily establishes that the operation of addition and multiplication of points has commutative and associative properties:

$$
(a; b) + (c; d) = (c; d) + (a; b),
$$

$$
((a; b) + (c; d)) + (e; f) = (a; b) + ((c; d) + (e; f)),
$$

$$
(a; b) \cdot (c; d) = (c; d) \cdot (a; b),
$$

$$
((a; b) \cdot (c; d)) \cdot (e; f) =
= (a; b) \cdot ((c; d) \cdot (e; f)).
$$

The distributed law is also fulfilled:

$$
((a; b) + (c; d)) \cdot (e; f) =
= (a; b) \cdot (e; f) + (c; d) \cdot (e; f).
$$

The point (1; 0) serves as a unit, i.e. for any point $(a; b)$

$$
(a; b) \cdot (1; 0) = (1; 0) \cdot (a; b) = (a; b).
$$

And finally, for any point $(a; b) \neq (0; 0)$ there is also a unique point $(x; y)$ such that

$$
(a; b) \cdot (x; y) = (1; 0).
$$

Let's prove the last property. Let's take some non-zero point $(a; b)$ (this means, in particular, that $a^2 + b^2 > 0$). We need to find a point $(x; y)$ such that $(a; b) \cdot (x; y) = (1; 0)$. But

$$
(a; b) \cdot (x; y) = (ax - by; ay + bx).
$$

Consequently, we obtain a system of equations

$$
ax - by = 1, ay + bx = 0.
$$

Solving this system of equations for $x$ and $y$, we find

$$
x = \frac{ac + bd}{a^2 + b^2}, y = \frac{ad - bc}{a^2 + b^2}.
$$

This has proven everything.

So, we have turned points in the plane into a numerical set, that is, a set with the operations of addition and multiplication for which all the properties of addition and multiplication of general real numbers are true. The real numbers contained in this set are points of the form $(a; 0)$. In fact, adding and multiplying such points is simply adding and multiplying real numbers:

$$
(a; 0) + (c; 0) = (a + c; 0),
$$

$$
(a; 0) \cdot (c; 0) = (ac; 0).
$$

⟦folio 51⟧

---
running_head:
folio:
---

Now let's take the point (0; 1). Let's see what happens if we square it, that is, multiply the sum by ourselves:
$(0; 1)^2 = (0; 1) \cdot (0; 1) = (-1; 0)$.
Thus, $(0, 1)^2$ is a real number - 1. This means that the point (0, 1) can be interpreted as the minimum unit $i$, thereby removing the mystical veil from it. Finally, any point $(a; b)$ can be represented as
$(a; b) = (a; 0) + (0; b) = (a; 0) + (b; 0) \cdot (0; 1)$.
If $(a; 0)$ and $(b; 0)$ are denoted as primes by $a$ and $b$, and $(0, 1)$ by $i$, then we get
$(a; b) = a + bi$.
i.e. now the formula expression $a + bi$ has become on a solid basis - it is just a point with coordinates $(a; b)$ on the plane with the above operations of addition (1) and multiplication (2).
In addition to its purely theoretical value, the geometric implementation of complex numbers has important practical significance - with its help, complex numbers can be represented in the so-called trigonometric form, which is convenient in numerous applications.
Exercises
9. Draw the complex numbers $2 + i, 1 + i, -1 - i, -3 - 2i$ as points on the plane.
10. Prove that the sum $z_1 + z_2$ of complex numbers $z_1$ and $z_2$ is represented by the fourth vertex of a parallelogram whose two adjacent sides are the segments connecting the points $z_1$ and $z_2$ with the point $O$.
11. Points $z_1, z_2, z_3$ are the vertices of the triangle on the plane. Write down the number that represents the center of gravity of this triangle.

Trigonometric form of a complex number

Let us consider the coordinate system $xOy$ on the straight plane. Let the point $P$ represent the complex number $z = a + bi$ (Fig. 1).
Let us denote the distance $OP$ from the point $P$ to the origin of coordinates by $r$, and by $\varphi$ the angle (see Fig. 1) formed by the ray $OP$ with the positive direction of the axis $Ox$ and absent counterclockwise $(0 < \varphi < 2\pi)$. (At figure 1 the angles $\varphi$ are shown for different cases of the location of the point $P$.)
From the definition of trigonometric functions it follows that
$a = r \cos \varphi, b = r \sin \varphi$,

Fig. 1.

⟦folio 52⟧

---
running_head:
folio:
---

$$z = r(\cos \varphi + i \sin \varphi).$$

This is the trigonometric form of a complex number. The quantity $OP = r$ is called the modum of the complex number $z$ and is denoted by $|z|$, and the magnitude of the angle $\varphi$ is the main argument of the number $z$ and is denoted by arg $z$.

Since $OP$ is the hypotenuse of the primangular triangle $OAP$, then
$$|z| = r = \sqrt{a^2 + b^2},$$
$$\arg z = \left\{ \begin{array}{l} \arccos \frac{a}{\sqrt{a^2 + b^2}} \text{ при } b \geqslant 0; \\ 2\pi - \arccos \frac{2}{\sqrt{a^2 + b^2}} \text{ при } b < 0. \end{array} \right.$$

From these formulas it follows that $|z|$ is uniquely determined and equal to zero if and only if $z = 0$.

The main argument for $z = 0$ is undefined. For $z \neq 0$, every angle that differs from arg $z$ by a term that is a multiple of $2\pi$ is called the argument of $z$.

For example, since arg $i = \frac{\pi}{2}$, then all arguments of the number $i$ are of the form $\frac{\pi}{2} + 2k\pi$. Likewise, arg is $(-1) = \pi$, and all other arguments are numbers $\pi(2k + 1)$.

Exercises.
12. Find $|z|$ and arg $z$ if
a) $z = -2$; 6) $z = 1 + i$; b) $z = -1 - i$; c) $z = -i$; d) $z = 1 - i\sqrt{3}$; e) $z = -3 - 4i$.

13. Write the trigonometric form of numbers
a) 1; 6) -1; b) 12 + 5i; c) 12 - 5i; d) -12 - 5i; e) $\sin \alpha + i \cos \alpha$ ($0 < \alpha < \pi$).

14. Prove that the distance between points $z_1$ and $z_2$ is $|z_1 - z_2|$. Use this to draw points on the plane for which
a) $|z - i| = 1$; 6) $|z - 1| = |z + 1|$; b) $|z - i| = |iz - 1|$; c) $1 \leqslant |z - i| \leqslant 2$.

15. Draw the points of the plane for which
a) arg $iz = \pi/4$; b) arg $(iz - 1) = \pi/3$.

All algebraic operations with complex numbers given in trigonometric form coincide according to the same rules as with complex numbers given in algebraic form. Adding and subtracting complex numbers is easier and more convenient when they are given in algebraic form, and multiplying and dividing in trigonometric form.

Theorem 1. When multiplying any finite number of complex numbers, their modi converts, and the arguments add up.

Proof. Let's limit ourselves to two factors; the general case can be easily obtained by induction. So we must prove that
$$(r_1(\cos \varphi_1 + i \sin \varphi_1)) \cdot (r_2(\cos \varphi_2 + i \sin \varphi_2)) = (r_1 r_2)(\cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2)).$$

But
$$(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 + i \sin \varphi_2) = (\cos \varphi_1 \cos \varphi_2 - \sin \varphi_1 \sin \varphi_2) + i(\cos \varphi_1 \sin \varphi_2 + \sin \varphi_1 \cos \varphi_2) = \cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2),$$
whence the non-chaired equality (3). Since $r_1 \geqslant 0, r_2 \geqslant 0$ implies that $r_1 r_2 \geqslant 0$, then $r_1 r_2$ is the modulus, and $\varphi_1 + \varphi_2$ is the argument of the product of two given numbers. The theorem has been proven.

From this theorem it follows that the product of the complex number $z$ by the complex number $a$ is obtained from the point $z$ as follows: you need to rotate the ray $Oz$ by the angle $\alpha = \arg a$ counterclockwise and then take on the resulting ray a point removed from $O$ by a distance $|a| \cdot |z|$ (Fig. 2). In other words, the transformation of the plane taking the universal point $z$ to the point $az$ is

⟦folio 53⟧

---
running_head:
folio:
---

the product of rotation by angle $\alpha$ and preparation with coefficient $|a|$ and center $O$.

Exercise 16. Prove the following equalities

a) $|z|^2 = zz'$; 6) $\frac{z_1}{z_2} = \frac{z_1\bar{z}_2}{|z_2|^2}$;

b) $|z_1 + z_2| \leqslant |z_1| + |z_2|$ (find out at which $z_1$ and $z_2$ there will be equality);

d) $|z_1 + z_2|^2 + |z_1 - z_2|^2 = 2(|z_1|^2 + |z_2|^2)$.

What is the geometric meaning of this too?

Theorem 2. When dividing complex numbers, their moduli are divided and the arguments are subtracted.

In more detail,

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)} = \frac{r_1}{r_2}(\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2))$$.

Proof. Converting a fraction

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)},$$

multiplying its numerator and denominator by $\cos \varphi_2 - i \sin \varphi_2$. As a result we get

$$\frac{r_1}{r_2} \cdot \frac{(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 - i \sin \varphi_2)}{(\cos \varphi_2 + i \sin \varphi_2)(\cos \varphi_2 - i \sin \varphi_2)}$$.

Since $i^2 = -1$, the denominator of the second fraction is $\cos^2 \varphi_2 + \sin^2 \varphi_2 = 1$. The numerator can be written like this:

$$(\cos \varphi_1 + i \sin \varphi_1)(\cos (-\varphi_2) + i \sin (-\varphi_2))$$.

Applying the multiplication rule, we get

$$\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2)$$,

Q.E.D.

When the factors coincide, Theorem 1 yields the so-called Myabra formula

$$(r_1(\cos \varphi + i \sin \varphi))^n = r^n(\cos n\varphi + i \sin n\varphi).$$

Theorem 3. Let $z$ be a complex number and $n$ a natural number. In the set of complex numbers, the expression $\sqrt[n]{z}$ for $z = 0$ has a single value - 0, and for $z \neq 0$ - it has different values. If

$$z = r(\cos \varphi + i \sin \varphi),$$

then these values ​​are found by the formula

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2\pi k}{n} + i \sin \frac{\varphi + 2\pi k}{n} \right),$$

$k = 0, 1, \dots, n - 1$.

Proof. Since $0^n = 0$ and from $z^n = 0$ it follows that $z = 0$.

Let it now

$$z = r(\cos \varphi + i \sin \varphi) \neq 0.$$

Denoting by $\rho$ and $\alpha$ the corresponding model and argument of the root, we have

$$\sqrt[n]{r(\cos \varphi + i \sin \varphi)} = \rho(\cos \alpha + i \sin \alpha).$$

Hence, according to the Myabra formula

$$r(\cos \varphi + i \sin \varphi) = \rho^n(\cos n\alpha + i \sin n\alpha).$$

Therefore, they must comply

$$\rho^n = r, n\alpha = \varphi + 2k\pi,$$

where

$$\rho = \sqrt[n]{r}, \alpha = \frac{\varphi + 2k\pi}{n},$$

i.e.

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2k\pi}{n} + i \sin \frac{\varphi + 2k\pi}{n} \right).$$

How many different values ​​will we get? It is easy to see that if we substitute the values ​​$k = 0, 1, 2, \dots, n - 1$ into the last formula, all the resulting values ​​of the root will be different, since their arguments will be different. For $k = n$ we get

$$\frac{\varphi + 2\pi n}{n} = \frac{\varphi}{n} + 2\pi,$$

and the root will be equal

$$\sqrt[n]{r} \left( \cos \left( \frac{\varphi}{n} + 2\pi \right) + i \sin \left( \frac{\varphi}{n} + 2\pi \right) \right) =$$

$$\sqrt[n]{r} \left( \cos \frac{\varphi}{n} + \sin \frac{\varphi}{n} \right),$$
