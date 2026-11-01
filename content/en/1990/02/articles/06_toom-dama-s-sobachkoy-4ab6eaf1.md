---
id: 1990-2-toom-dama-s-sobachkoy-4ab6eaf1
issue: kvant_1990_2
year: 1990
number: "2"
title: Lady with a dog
authors:
  - Тоом А. Л.
rubric: raznoe
page_first: 12
page_last: 28
page_labels: 10, 12, 13, 14, 15, 16, 26
lang: en
source: kvant_digital
extraction: vision
content_sha256: a02bc978fbefdd0b08edf6ebda33b9b0db740c12b11390bd97d2a628688bc28b
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/06_toom-dama-s-sobachkoy-4ab6eaf1.md
source_content_sha256: 137baa669763b5002a737662197ce0619193eb74ffa1e6a1829e4f70b30489a2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

LADY WITH A DOG

Candidate of Physical and Mathematical Sciences
A. TOOM

A long time ago, when I was a mechanical engineering student at Moscow State University, one of my older friends asked me: “Do you know “The Lady with the Dog”?” “Well, of course,” I answered, referring to A.P. Chekhov’s story. “No,” said the interlocutor, “I’m talking about something else. There is such a proof of the main theorem of al-
gebras." And then he told me a very beautiful (although not rigorous) argument, which in the end turned out to be one of my most vivid impressions in all my years of study. However, despite its clarity, the proof of this, which has long been included in “mathematical folklore”, in my opinion, has not yet been written down in its most accessible form.

The screensaver uses J. Ball's painting “Dog on a Leash” (1912).

⟦folio 12⟧

---
running_head:
folio:
---

multiplication by a real number $k$ corresponds to a homothety with center $O$ and coefficient $k$.

Multiplication of arbitrary complex numbers is based on numbers

$$i^2 = -1.$$

Use it, we get

$$(x_1 + iy_1)(x_2 + iy_2) = (x_1x_2 - y_1y_2) + i(x_1y_2 + x_2y_1).$$

Division of complex numbers can also be defined as the inverse action of multiplication. The expression $z_1/z_2$ has an unambiguous meaning whenever $z_2 \neq 0$, and is defined by the formula

$$\frac{x_1 + iy_1}{x_2 + iy_2} = \frac{(x_1 + iy_1)(x_2 - iy_2)}{(x_2 + iy_2)(x_2 - iy_2)} = \frac{x_1x_2 + y_1y_2}{x_2^2 + y_2^2} + i \frac{x_2y_1 - x_1y_2}{x_2^2 + y_2^2}.$$

In particular,

$$\frac{1}{x + iy} = \frac{x - iy}{x^2 + y^2}.$$

The complex number $\bar{z} = x - iy$ is called the conjugate of the number $z = x + iy$. Obviously, each complex number is conjugate to its conjugate: $\bar{z} = z$, and the points $\bar{z}$ and $z$ are symmetrical to each other about the real axis.

With complex numbers, you can do all four operations of the argument, and those algebraic correspondences that allow grafting transformations (transferring terms from one part of the equality to another, reducing similar terms, putting them out of brackets) are correct. In mathematical language, this means that complex numbers form a field.

Exercises
1. Follow the steps
   a) $(1 + i)(1 - i)$; 6) $(1 + i)/(1 - i)$; b) $(1 + i)^4 - (1 - i)^4$.
2. For each integer $n$ indicates what is equal to: a) $i^n$; 6) $(1 + i)^n$.
3. Let us consider a geometric transformation of the complex plane that takes each point $z$ to the point $1/z$. a) What does this transformation transform the straight line $(1 + iy)$ into? 6) Prove that this transformation transforms the circle passing through the point $O$ into a straight line, and the circle not passing through the point $O$ into a circle.

Solving the equation
Historical complex numbers arose in mathematics thanks to the desire to make the theory of solving algebraic equations more harmonious, i.e., equations of the form

$$P(z) = 0,$$

where $P(z)$ is an algebraic polynomial of $n$ degree;

$$P(z) = z^n + a_{n-1}z^{n-1} + \dots + a_1z + a_0.$$

The root of equation (1) or, which is the same thing, of polynomial (2), is the value $z$ for which (1) is true. Solving an equation means finding all its roots.

In order to find all the roots of a polynomial, it would be easy to know in advance how many there are. By constructing a suitable system of definitions, mathematicians managed to create a situation in which the number of roots of a polynomial is always equal to its degree. Let's use the example of quadratic equations to show how they managed to do this. Consider the reduced quadratic equation with real coefficients

$$z^2 + pz + q = 0.$$

As is known, its roots are expressed by the formula

$$z_{1,2} = \frac{-p \pm \sqrt{D}}{2},$$

where discriminant $D = p^2 - 4q$. But, as long as we work only with real numbers, this formula loses its meaning at $D < 0$, and our equation has no roots. It turns out differently: non-toric quadratic equations have two roots, non-toric quadratic equations have none. This different publication caused a feeling of dissatisfaction among mathematicians, which led to the development of the theory of complex numbers. In the field of complex numbers, formula (4) also makes sense for $D < 0$, taking the form

$$z_{1,2} = \frac{-p \pm i\sqrt{-D}}{2}.$$

Substituting these expressions into equation (3), it is easy to verify that a true equality is obtained.

⟦folio 13⟧

---
running_head:
folio:
---

However, there is still the case when $D=0$: in this case there is only one root $z_1=z_2$. But we will assume that this root is double, because in this case, as in all others, our square triangular is factorized

$$z^2+pz+q=(z-z_1)(z-z_2).$$

A more cumbersome, but essentially not so difficult, reasoning shows that even for arbitrary complex values ​​of the coefficients $p$ and $q$, equation (3) also has two complex roots.

So, by introducing suitable definitions, we have arrived at a situation in which every quadratic equation has two roots. The same is true for all degrees.

The main point we seek to make in this article is the following. Every polynomial of $n$th degree (2) can be decomposed into $n$ factors in the field of complex numbers

$$p(z)=(z-z_1)(z-z_2)...(z-z_n),$$

where $z_1, z_2, ..., z_n$ are all the roots of our polynomial (some of them may coincide with each other). In this case, the coefficients of the polynomial (2) can be complex.

In any case, the hardest step is the first step. So it is here: the most difficult thing to prove is that every polynomial of degree $n \ge 1$ has at least one complex root. This last statement (perhaps precisely because it contains the main difficulty) is called the general fundamental theorem of algebra.

Let us pay attention to one particular case when the statement of the main theorem of algebra is relatively very strong. Let all coefficients of the polynomial (2) be real numbers and $n$ odd. In this case, the polynomial depends on at least one real root. To see this, consider the graph $P(x)$, where $x$ runs along the real number axis, namely, the behavior of this graph with $x$ moving away along the axis to infinity to the left and right. For large absolute values ​​of $x$, the behavior of the polynomial is determined by the behavior of its leading term $x^n$, compared to which the sum of all other terms is a trifle that can be claimed. Together with $x^n$, our polynomial goes to “flat infinity” at $x \rightarrow \infty$ and to “minus infinity” at $x \rightarrow -\infty$. Therefore, $P(x)$ takes both positive and negative values. But the graph of a polynomial is a continuous curve, and since this curve is located above the x-axis in one place, and below in another place, then it must intersect this axis at least once. Of course, this is rigorous reasoning, but before learning to reason strictly, it makes sense to familiarize yourself with those ideas for the sake of which it is worth building a complex apparatus of strict reasoning.

A little later we will give the same rigorous proof of the fundamental theorem of algebra. But first, let's discuss the geometric meaning of multiplying complex numbers.

Exercises
4. Solve equations
a) $z^2+iz=0$; 6) $z^2+i=0$; c) $z+\frac{1}{z}=1$.
5. Prove that if all the coefficients of an equation are real numbers, then the set of its roots in the complex plane is symmetrical about the real axis. From here deduce once again that an equation of odd degree with real coefficients has at least one real root.
6. For an arbitrary complex number $p+iq$, solve the equation

$$z^2=p+iq.$$

7. Prove Vieta's theorem

$$z_1+z_2=-p, z_1 \cdot z_2=q,$$

where $z_1$ and $z_2$ are the roots of equation (3), $p$ and $q$ are any complex numbers.
8. Solve equations in complex numbers and show their roots in the complex plane
a) $z^4-1=0$; 6) $z^3-1=0$; c) $z^6-1=0$.

When several complex numbers are variable, their modules are variable, and the arguments add up

As is known, the modulus of a real number is equal to the distance from the point

⟦folio 14⟧

---
running_head:
folio:
---

$x$ to point $O$ on the number line. Similarly, the model of a complex number is the distance from the corresponding point to the point $O$ on the complex plane. From the Pythagorean theorem we can derive the following formula

$$|x + iy| = \sqrt{x^2 + y^2}.$$

The modulus of the difference between two complex numbers is equal to the distance between the images of their points on the complex plane.

Let us prove that the model of the product of two complex numbers is equal to the product of their models:

$$|z_1 z_2| = |z_1| \cdot |z_2|.$$

Let

$$z_1 = x_1 + iy_1, \quad z_2 = x_2 + iy_2.$$

Then

$$|z_1 z_2| = \sqrt{(x_1 x_2 - y_1 y_2)^2 + (x_1 y_2 + x_2 y_1)^2} = \sqrt{x_1^2 x_2^2 + y_1^2 y_2^2 + x_1^2 y_2^2 + x_2^2 y_1^2} = \sqrt{(x_1^2 + y_1^2)(x_2^2 + y_2^2)} = |z_1| \cdot |z_2|,$$

Q.E.D.

Now we need to introduce quantities that characterize the “direction” of a complex number. The argument $\text{Arg}(z)$ of the complex number $z$ is the angle at which the ray $Oz$ is rotated relative to the positive pole $Ox$. A counterclockwise turn is considered positive, a clockwise turn is considered negative. Only zero has no argument. Every complex number $z \neq 0$ has an argument that determines, up to the term $360^\circ \cdot n$, where $n$ is any integer. For example,

$$\text{Arg}(1) = 360^\circ \cdot n,$$
$$\text{Arg}(i) = 90^\circ + 360^\circ \cdot n,$$
$$\text{Arg}(-1) = 180^\circ + 360^\circ \cdot n,$$
$$\text{Arg}(-i) = 270^\circ + 360^\circ \cdot n.$$

However, all these formulas can be written in another form, for example

$$\text{Arg}(-i) = -90^\circ + 360^\circ \cdot n.$$

Let us choose a complex number $z_0$ whose model is equal to one, and show that multiplying all complex numbers by $z_0$ is a rotation of the complex plane around the point $O$ by the argument $z_0$.

Before reading the data, consider the geometric meaning of multiplication by $z_0$ in four special cases:

$$z_0 = \pm 1 \text{ и } z_0 = \pm i.$$

In all four cases, the result is a rotation around the point $O$ by some angle, isn’t it?

So, consider multiplication by an arbitrary number $z_0$, the model of which is equal to one. We said above that the distance between points $z_1$ and $z_2$ is a model of the difference between the numbers $z_1$ and $z_2$. We use this to show that when multiplied by $z_0$, the distance between points is preserved:

$$|z_1 z_0 - z_2 z_0| = |(z_1 - z_2) z_0| = |z_1 - z_2|.$$

Any geometric transformation in which the distance between points does not change is called motion (the concept of a rigid body in physics is close to it). In this case, the movement leaves the point $O$ in place and does not leave any other point in place, and such a movement is a rotation around the point by a certain angle. At what angle? At the same angle at which the beam $Oz_0$ is rotated relative to the positive pole $Ox$, i.e. at $\text{Arg} z_0$.

Now let's figure out what happens to complex numbers when they are multiplied by an arbitrary number $z_0$, different from zero. To do this, we decompose $z_0$ into two factors, one of which is real and equal to $|z_0|$, and the other has model 1 and is equal to $z_0/|z_0|$. Multiplication by the first factor - the prepared argument does not change, but the model is multiplied by $|z_0|$. Multiplication by the second factor is a rotation in which the model does not change, but the argument increases by $\text{Arg} (z_0)$.

So we have proven that when changing two arbitrary complex numbers, their models are variable, and the arguments add up. Based on this, it is easy to prove a similar statement for any number factor.

An important part of the case: if a complex number is raised to the $n$th power, then its model is raised to the $n$th power

⟦folio 15⟧

---
running_head:
folio:
---

degree, and the argument is multiplied by $n$. The formula expressing this statement is called Moivre's formula. Thanks to this fact, we can understand how the roots of the equation are located on the complex plane
$$z^n - 1 = 0.$$ (6)

These roots are the vertices of a regular $n$-gon with center at point $O$, one of the vertices of which is point 1. Solving equation (6) algebraically (if this can be done), we obtain expressions for trigonometric functions of angles of the form $k \cdot 360^\circ/n$.

Battles
9. Prove that three distinct points $z_1$, $z_2$ and $z_3$ lie on the same line if and only if
$$(z_3 - z_1) / (z_2 - z_1)$$
is a real number.
10. Prove that triangle $z_1z_2z_3$ is similar to triangle $z'_1z'_2z'_3$ if and only if
$$\frac{z_3 - z_1}{z_2 - z_1} = \frac{z'_3 - z'_1}{z'_2 - z'_1}.$$
11. Prove that the points $z_1$, $z_2$ and $z_3$ are the vertices of a regular triangle with center $O$ if and only if
$$\begin{cases} z_1 + z_2 + z_3 = 0, \\ |z_1| = |z_2| = |z_3| > 0. \end{cases}$$
12. What geometric figure on the complex plane is formed by the solutions of the equation
$$3|z| = 2|z - 5|?$$
13. Solve the equation
$$z^5 - 1 = 0$$
two different ways: using the Moivre formula and without it. Based on the data obtained, calculate the sines and cosines of the angles $72^\circ$ and $144^\circ$. This is a method of constructing a regular pentagon with a compass and a ruler.

Fig. 4.

14. Suppose we need to calculate the sum
$$\sin \alpha + \sin (\alpha + \beta) + \sin (\alpha + 2\beta) + \dots + \sin (\alpha + n\beta).$$
Using complex numbers, reduce this problem to calculating the sum of a geometric progression.

Date leaving home
Remember how at the end of the second section of the article we were helped by the fact that we considered a larger absolute value of the variable. We will do the same now, with the difference, however, that now we have not real, but complex numbers. Let us fix a larger radius $R$ and assume that the complex number $z$ goes around a circle of radius $R$ with center $O$. Let $z$ begin its path at point $R$ (i.e., at the point with coordinates $(R, 0)$), move along the circle in the positive direction (counterclockwise) and end its path at the same point $R$ (Fig. 4).

The point $z^n$ moves along a circle of radius $R^n$ (since the model of the number $z^n$ is the $n$ power of the module $z$), but goes around it not once, but $n$ times (since the argument $z^n$ is equal to the argument $z$ multiplied by $n$). Since point $z^n$ behaves so well and decorously, we will call her Lady. The lady leaves her house, located at point $R^n$, makes a move, going $n$ times around a circle of radius $R^n$ with center $O$, and returns home.

The polynomial $P(z)$ (see formula (2)) plays the role of the Dog in this story, because its path to trace the city is more difficult. In any case, we know that $P(z)$ also continuously moves along the complex plane, starting and ending its path at the point $P(R)$ - at the end.

Let's estimate the distance between the Lady and the Dog:
$$|P(z) - z^n| = |a_{n-1}z^{n-1} + a_{n-2}z^{n-2} + \dots + a_1z + a_0| \leq |a_{n-1}z^{n-1}| + |a_{n-2}z^{n-2}| + \dots + |a_1z| + |a_0| = |a_{n-1}| \cdot R^{n-1} + |a_{n-2}| \cdot R^{n-2} + \dots + |a_1| \cdot R + |a_0| \leq (|a_{n-1}| + |a_{n-2}| + \dots + |a_1| + |a_0|) \times R^{n-1} = L.$$

We took advantage of the fact that the module

⟦folio 16⟧

---
running_head:
folio:
---

the sum of complex numbers is no greater than the sum of their models. Geometrically, this is obvious: the length of a broken line composed of vectors corresponding to these numbers does not exceed the distance between its ends. Moreover, in the last inequality we assumed that $R \geq 1$; this is not surprising since we already said that $R$ is a large number. $L$ is the length of the leash on which the Lady holds the Dog: for each value $z$ the Dog cannot move away from the Lady at a distance greater than $L$. Now we can give a precise meaning to the words “$R$ is a large number”, namely, we give $R$ the meaning

$$R_0 = |a_{n-1}| + |a_{n-2}| + \dots + |a_1| + |a_0| + 1.$$

It is clear that in this case the values ​​$R$ the length of the leash $L$ is less than the radius $R^n$ of the circle along which the Lady is walking. It follows that on its way the Dog, like the Lady, goes around the point $O$ $n$ times.

To convey this important message, for clarity, let's assume that a ball of thread is suspended from the Dog's evaluator, the end of which is fixed in the kennel. When the Dog makes its way, the ball is blurred, and the thread remains lying on the plane, offsetting the Dog’s trajectory. The ends of the thread match. So, the trajectory of the Dog is displaced by a closed thread laid on the plane so that it makes $n$ loops around the point $O$.

Now take it out: the most crucial moment of our reasoning is coming! We'll start changing the parameter $R$ from $R_0$ to zero. We will call this process contraction. When contracting, the radius of the circle in which the Lady walks decreases, but she still walks $n$ circles with a center $O$. Only when $R$ becomes zero do these circles contract to the point $O$. How the trajectory of the Dog changes during the contraction process is a complex question, but in any case, its trajectory changes continuously, and at $R=0$ it contracts to the point $a_0$, and at $R$, which is close to zero, the trajectory is close to the point $a_0$.

Let's exclude the case $a_0=0$ from consideration, because in this case the statement of the theorem is obvious: our polynomial has root 0. Then, with $R$ close to zero, the trajectory of the Dog, being close to $a_0 \neq 0$ for all $z$, does not go around the point $O$ even once.

So, in the process of contraction, the number of rounds of the Dog’s trajectory around the point $O$ decreases from $n$ to zero. Since the number is an integer, it changes with rolling pins, i.e., it is a discontinuous function of $R$. Let's choose some value $R$, which is the break point of this function, and think about what the trajectory of the Dog is for this value $R$. It is clear that at this value $R$ the trajectory of the Dog passes through the point $O$. But each point of this trajectory is the value of our polynomial. If at least one of these points coincides with zero, then the polynomial has a root!

So, we have proven that every polynomial $P(z)$ of non-zero degree has at least one root $z_1$. Then, according to Bezout’s theorem (see the note “Equations that can be solved” in this issue of the magazine), this polynomial is expanded into the product

$$P(z) = (z - z_1) \cdot P_1(z).$$

To $P_1(z)$ (if its powers are positive) we can apply the same reasoning and prove that it also has at least one root $z_2$, and again apply Bézout’s theorem, we get

$$P(z) = (z - z_1)(z - z_2) \cdot P_2(z).$$

Repeating this reasoning $n$ times, we finally obtain expansion (3) of an arbitrary polynomial of $n$ degree into $n$ factors, which we have been striving for all along.

Defeat

15. Let a complex number $z$ leave point 1, go around a circle of radius 1 with center $O$ and return to the same point 1. Draw a line along which the point moves:

a) $1/z$; b) $z^2 + z + 1$; c) $(z - 1)^n$.

⟦folio 26⟧

---
running_head:
folio:
---

century in such an experiment mentally rotates the image of the perceived figure (and according to a number of psychological experiments, rather, the standard figure stored in memory) with a constant angular speed and even determined this speed. The result was 450°/s. However, it is impossible to prove the “mental rotation” hypothesis with such experiments, since it remains unknown what is actually happening in the heads of the subjects.

Georgopoulos, having acquired the ability to “spy” on the work of neurons in the brain of a monkey, obtained data in 1989 that makes the mental rotation hypothesis more reliable.

Now the monkey has been taught to pull its paw not to the light bulb that is burning, but to the one that is at an angle of 90° to it. The experimenters were able to find out what was happening in the monkey's brain from the moment the lamp was lit until the paw began to move. It turned out that after the flash, the vector is directed directly at the light bulb, then begins to rotate, when it turns 90°, the paw begins to move. Rotation speed

Lady
with the Dog

(See beginning on p. 10)

Some information
from the history of complex numbers

1545 D. Kardanov (Italy) publishes the book “Great Art, or On the Rules of Algebra,” where he introduces minimum values.

1629 A. Girard (Holland) publishes the book “New Discoveries in Algebra,” where he formulates the main theorem of algebra.

1707 A. de Moivre (England) introduces the rules for exponentiation and root extraction of complex numbers (Moivre's formulas).

1746 D Alembert (France) publishes the first (not entirely rigorous) proof of the fundamental theorem of algebra.

1770s. L. Euler (Russia) introduces the concept of a function as a complex variable.

1799 K. Gauss (Germany) publishes the first rigorous proof of the fundamental theorem of algebra.

1799 K. Wessel (Denmark) describes for the first time the geometric interpretation of complex numbers.

Literature
Courant R., Robbins G. What is mathematics. M., Education, 1968.

Markushevich A. I. Complex numbers and mapping conformals. M., 1979.

Yaglom I.M. Complex numbers and their application in geometry. M., 1963.

Books from the series “Popular lectures on mathematics” (Nauka publishing house):

Bakelman I. Ya. Inversion (issue 44).

Markushevich A.I. Complex numbers and mapping conformals (issue 13).

Shafarevich I. R. On solving equations for calculating degrees (issue 15).

Shervatov V. G. Hyperbolic function (issue 16).
