---
id: 1974-4-sidorov-argument-kompleksnogo-chisla-cdaff03f
issue: kvant_1974_4
year: 1974
number: "4"
title: Complex Number Argument
authors:
  - Сидоров Ю. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: QDOI
lang: en
source: kvant_digital
extraction: vision
content_sha256: cc119bb9c85e5d7f5a6ce7a362e1fb76e5e9f9193d1d28d04f72c09988c6aa30
prompt_sha256: draft-1
translated_from: content/ru/1974/04/articles/09_sidorov-argument-kompleksnogo-chisla-cdaff03f.md
source_content_sha256: 8c0534a137c12a5563f190bd57fea82b37ba5c73af4ccd4007256e92c183d202
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

Complex Number Argument
Yu. V. Sidorov

This article examines the concept of the argument of a complex number and the trigonometric form of writing a complex number. It is assumed that the reader knows the definition of a complex number, the concept of a model and the geometric interpretation of a complex number *).

Definitions
Let's start by defining the argument of a complex number. Most often there are two definitions.

Definition 1. The argument of a complex number $z \neq 0$ is the angle between the real axis and the vector $\vec{Oz}$, described from the positive direction of the real axis. At the same time, if

*) See, for example, V. G. Boltyansky, Yu. V. Sidorov, M. I. Shabunn, “Lectures and problems in elementary mathematics”, M., “Nauka”, 1971, as well as V. V. Pekarskaya, “Geometry of complex numbers”, «Kvant», 1973, No. 6, p. 54.

The counting is carried out arbitrarily in the clockwise direction, but the value of the value is calculated as positive, and if not in the clockwise direction, it can be negative (see figure).

Definition 2. The argument of a complex number $a + bi \neq 0$ is an angle φ that simultaneously satisfies two equalities:

$$\begin{align*}
\sin \varphi &= \frac{b}{\sqrt{a^2 + b^2}}, \\
\cos \varphi &= -\frac{a}{\sqrt{a^2 + b^2}}.
\end{align*}$$

To fully understand the definition of an argument, it is necessary to stipulate the following.

1°. In both definitions, an angle can be expressed in both degrees and radians. In a school mathematics course, both entries are equal. For clarity, contracts in this article change angles only in radians, and the word “radIAN”, as usual, will be omitted. This choice is not accidental - in higher mathematics it is the radian change in angles that is most often used. Therefore, the argument of a complex number should be considered an abstract number.

Thus, in Definition 1, the word “angle” must be remembered as an “algebraic angle,” that is, an abstract number expressing the number of radians of the “geometric angle” value. Similarly, in Definition 2, the number φ means the number of radians, not degrees.

⟦folio 42⟧

2°. Definitions 1 and 2 are equivalent: if φ is the argument of the number z = a + bi ≠ 0 in the sense of Definition 1, then equalities (1) are satisfied; conversely, if φ is the argument of the complex number z = a + bi ≠ 0 in the sense of Definition 2, then φ is the angle between the positive direction of the real axis and the vector z. This statement for a > 0, b > 0 follows directly from figure (see p. 41) and the definitions of sine and cosine. For other numbers z the proof is similar (check it!).

Thus, it does not matter which of definitions 1 or 2 is chosen as the initial one - the other will be a necessary and worthy criterion.

3°. For the number z = 0, the concept of argument does not exist. Therefore, for brevity, in all further discussions related to the concept of argument, we will assume (and this must not be forgotten!) that z ≠ 0.

4°. For a fixed complex number z ≠ 0, the argument is determined ambiguously: if φ₀ is a non-actor argument of the number z, then each of the numbers

$$\varphi_0 + 2k\pi, \quad k = 0, \pm 1, \pm 2, \dots,$$

is also an argument of the same number z, and no number that does not coincide with any of the numbers indicated in (2) is an argument of the number z (prove it!).

Thus, for every fixed number z ≠ 0 there is an infinite number of arguments, of which every two negative dyres of dyres is a multiple of 2π.

5°. The ambiguity of the argument, described in 4°, makes it difficult to understand the operations on the argument of a complex number. But often it is thanks to this ambiguity that it is possible to solve rather difficult problems.

In some recent elementary mathematics, the definition of the argument includes a restriction of the form 0 ≤ φ < 2π, that is, it is believed that the argument of a complex number z is the smallest non-negative angle between the positive axis and the vector z. Then for each number z the argument is determined uniquely, and at first glance it seems that the whole theory should be simpler. However, such a restriction only further complicates the correct operation of the arguments (for example, the sum of the arguments of two complex numbers is not always the argument of any complex number). Sometimes this leads to significant non-obvious *), so it is better to stick to the general priority of the definition (1 or 2).

Complex number argument

Let's consider the question of finding the argument of a complex number. But first, let's agree on the notation.

To indicate the fact that the number φ is the argument of the complex number z, we write

$$\varphi = \arg z \text{ или } \arg z = \varphi.$$

(3) For example, which of the correspondences

$$\frac{\pi}{2} = \arg i$$

And

$$\arg i = \frac{\pi}{2}$$

means only that the number π/2 is the argument of the number i.

Note that correspondences (3), although formally looking like equalities, are non-countable. However, among the properties of ordinary equalities is, for example, the following: if A = B and B = C, then A = C (A, B, C are numbers or geometric figures). But equalities (3) do not have this property. For example, we can write that

$$\frac{\pi}{4} = \arg (1 + i), \arg (1 + i) = \frac{9\pi}{4},$$

*) See, for example, V.V. Zaitsev, V.V. Ryzhkov, I.M. Skanavi, “Elementary Mathematics”, M., “Nauka”, 1967, p. 41: in formula (15.1) the sum φ₁ + φ₂ can be greater than 2π, and therefore the meaning of the theorem after this formula is unclear. A similar non-obviousness was admitted on the same page in formula (15.2) and in the text after it.

And unedited. A new, revised edition of this book is now being prepared; it will be published in 1974.

⟦folio 43⟧

$\frac{\pi}{4} \neq \frac{9\pi}{4}$.

Thus, correspondences (3) can be read as follows: “φ equals the argument of the number $z$ or “the argument of the number $z$ equals $\varphi$”, but the meaning of these phrases is only one: $\varphi$ is the argument of the number $z$ or, in other words, $\varphi$ is one of the arguments of the number $z$, as noted in (2). This fact is written in the form of a formula

$$\arg z = \varphi_0 + 2k\pi,$$

$$k = 0, \pm 1, \pm 2, \dots$$

For example, all values ​​of the argument of the number $i$ are contained in the formula

$$\arg i = \frac{\pi}{2} + 2k\pi, k = 0, \pm 1, \pm 2, \dots$$

Note that the “equalities” seen in (4) are often encountered when solving trionometric equations. For example, the solution to the equation $\sin x = 1$ is written as follows:

$$x = \frac{\pi}{2} + 2k\pi, k = 0, \pm 1, \pm 2, \dots$$

The meaning of the last “equality” is the same as the correspondence (4): for each integer $k$, the number $\frac{\pi}{2} + 2k\pi$ satisfies the equation $\sin x = 1$ and only these numbers are the roots of the equation $\sin x = 1$.

To find all values ​​of the argument of a complex number $z = a + bi \neq 0$, you need to find all numbers $\varphi$ that satisfy both equality (1), that is, solve equations (1) together.

Example 1. The names of all the values ​​of the argument of the number $z = -5$.

Since $a = \text{Re} z = -5, b = \text{Im} z = 0$, the solutions of the first equation $\cos \varphi = -1$ from system (1) are the numbers $\varphi = \pi + 2k\pi, k = 0, \pm 1, \pm 2, \dots$, and the solutions of the second equation $\sin \varphi = 0$ are the numbers $\varphi = n\pi, n = 0, \pm 1, \pm 2, \dots$.

The common roots of the equation are numbers

$$\varphi = \pi + 2k\pi, k = 0, \pm 1, \pm 2, \dots$$

Answer: $\arg (-5) = \pi + 2k\pi, k = 0, \pm 1, \pm 2, \dots$.

Note that the answer in example 1 can be written in another form, for example:

$$\arg (-5) = -\pi + 2n\pi, n = 0, \pm 1, \pm 2, \dots,$$

or

$$\arg (-5) = 3\pi + 2m\pi, m = 0, \pm 1, \pm 2, \dots$$

It must be borne in mind that all these formulas are different entries are equivalent (each of these answers contains all the values ​​of the arguments of the number $-5$), that is, these are the same answers written in different formulas.

Argument of complex number $z = a + bi \neq 0$ you can find the procedure first point $z = a + bi$ (for example, using the geometric interpretation of a complex number), and then use one (any) of equations (1) (demonstrative answer according to formula (4)).

Answer: $\arg (-1 + i) = \frac{3\pi}{4} + 2k\pi, k = 0, \pm 1, \pm 2, \dots$.

Note that if $\varphi = \arg (a + bi), a \neq 0$, then

$$\tg \varphi = \frac{b}{a}.$$

However, the converse statement is not true: from equation (5) it is impossible

⟦folio 44⟧

read that $\varphi = \arg(a + bi)$. For example, for the number $-1 + i$ the value $\varphi = -\pi/4$ is a solution to equation (5), but is not an argument of this number.

But if we first determine in which quadrant the point $a + bi$ is located, and then also find the solution to equation (5), which is the angle in this quadrant, we obtain the argument of the number $a + bi$ (proof!).

Example 3. Name from the arguments of the number $1 - i\sqrt{3}$.

Point $1 - i\sqrt{3}$ lies in the fourth quarter. We find some solution to equation (5), that is, $\arg(\varphi) = -\sqrt{3}$, which is the angle in this quarter, for example: $\varphi = -\pi/3$.

Answer: $\arg(1 - i\sqrt{3}) = -\frac{\pi}{3}$.

In this example, the meaning of the question is ambiguous. The following answers are also correct:

$$\arg(1 - i\sqrt{3}) = \frac{5\pi}{3},$$
$$\arg(1 - i\sqrt{3}) = -\frac{7\pi}{3},$$
$$\arg(1 - i\sqrt{3}) = \frac{41\pi}{3}$$

and others.

Example 4. Name of the number $\sqrt{3} + i$.

Similar to how it was done in examples 2 or 3, we find (find!):

$$\arg(\sqrt{3} + i) = \frac{\pi}{6}$$

(that is, $\pi/6$ is one of the arguments of the number $\sqrt{3} + i$). It remains to figure out how to write the answer: is it enough to indicate one argument value or do you need to find all of them?

Let us recall, for example, the problem: solve the equation $x^2 = 1$. This equation has two roots $x_1 = 1$ and $x_2 = -1$. For the answer to be complete, both roots must be included. Necessary answers are often found in geometric problems. For example, find side $AB$ of triangle $ABC$ if $AC = 8$ cm, $BC = 7$ cm, $\angle A = \pi/3$. The full answer should be: $AB = 3$ cm or $AB = 5$ cm (proof!).

It’s the same in our example 4: for the answer to be complete, you need to find all the values ​​of the argument of the number $\sqrt{3} + i$. Since one argument $\pi/6$ has already been found, we find all the values ​​of the argument of this number using formula (4).

Answer: $\arg(\sqrt{3} + i) = \frac{\pi}{6} + 2k\pi, k = 0, \pm 1, \pm 2, \dots$.

So question 4 is a simple short version of question 2.

Let's pay attention to one common mistake. Otherwise, applicants try to find the argument of the number $a + bi$ using the formula $\varphi = \arctg\frac{b}{a}$, and some even take this formula as the definition of the argument. However, for each $x$ the argument function $x$ has only one value, $-\frac{\pi}{2} < \arctg x < \frac{\pi}{2}$. This means that the formula $\arg(a + bi) = \arctg\frac{b}{a}$ is valid only for $a > 0$, and it gives only one of the values ​​of the argument.

It is possible to prove (prove!) the validity of the following formula:

$$\arg(a + bi) = \begin{cases} \frac{\pi}{2}, \text{ если } a = 0, b > 0; \\ -\frac{\pi}{2}, \text{ если } a = 0, b < 0; \\ \arctg\frac{b}{a}, \text{ если } a > 0; \\ \pi + \arctg\frac{b}{a}, \text{ если } a < 0. \end{cases}$$

Using this formula, you can find one of the values ​​of the argument, but it is often easier to do as done in examples 2 or 3.

⟦folio 45⟧

Trigonometric form of a complex number

Let's consider the concept of the trigonometric form of a complex number. Recall that the modulus of a complex number $z = a + bi$ is the number

$$r = |a + bi| = \sqrt{a^2 + b^2}.$$

Let $\varphi = \arg(a + bi)$, let us rewrite formulas (1) as follows:

$$\cos \varphi = \frac{a}{r}, \sin \varphi = \frac{b}{r},$$

where $a = r \cos \varphi, b = r \sin \varphi$ comes from, and then

$$a + bi = r(\cos \varphi + i \sin \varphi).$$

Thus, any complex number $a + bi \neq 0$ can be written in the form (6), if $r$ is the modulus of the number $a + bi$, and $\varphi$ is one of the arguments of this number:

$$r = |a + bi|, \varphi = \arg(a + bi).$$

The converse statement is also true (proof!): if the complex number $a + bi$ is represented in the form (6), if $r > 0$, then

$$r = |a + bi|, \varphi = \arg(a + bi).$$

Definition. Representation of the complex number $z$ in the form

$$z = r(\cos \varphi + i \sin \varphi),$$

(7) if $r > 0$, is called the trigonometric form of writing a complex number.

The above means that each complex number $z \neq 0$ can be represented in trigonometric form (7), and

$$r = |z|, \varphi = \arg z.$$

In order to find the trigonometric form of a given complex number, you need to find a method of the number, some argument of this number, and then write this number in the form (7). If in this case $|z| = r = 1$, then the whole $r$ in formula (7), as usual, is omitted, that is, in this case the trigonometric form of notation has the form

$$z = \cos \varphi + i \sin \varphi.$$

For example, for the number $i$ the entry

$$i = \cos \frac{\pi}{2} + i \sin \frac{\pi}{2}$$

is the trigonometric form of writing this number.

Note that, due to the polysemy of arg $z$, the trigonometric form of a fixed complex number is also ambiguous. For example, for the number $i$ the trigonometric form is also written

$$i = \cos \frac{5\pi}{2} + i \sin \frac{5\pi}{2},$$

$$i = \cos \left(-\frac{3\pi}{2}\right) + i \sin \left(-\frac{3\pi}{2}\right)$$

and others.

It is necessary to emphasize that not every representation of a complex number through trigonometric functions is a trigonometric form of this number. For example, writing the number $i$ as $i = \cos \frac{\pi}{2} + i \sin \frac{5\pi}{2}$ or $i = (-1)\left(\cos \frac{3\pi}{2} + i \sin \frac{3\pi}{2}\right)$ is not a trigonometric form of the number $i$. Since the arguments of the number $i$ are numbers $i$ is the number $i$.

$$\frac{\pi}{2} + 2k\pi, k = 0, \pm 1, \pm 2, \dots,$$

and only they, then the trigonometric form of the number $i$ necessarily has the form

$$z = 1 + \cos \frac{10\pi}{9} + i \sin \frac{10\pi}{9}$$

can be represented in the form (check it!):

$$z = 2 \cos \frac{5\pi}{9} \left(\cos \frac{5\pi}{9} + i \sin \frac{5\pi}{9}\right) =$$

$$= 2 \cos \frac{14\pi}{9} \left(\cos \frac{14\pi}{9} + i \sin \frac{14\pi}{9}\right).$$

The second of these entries is

⟦folio 46⟧

trigonometric form of this number, but the first one is not, since $\cos \frac{5\pi}{9} < 0$.

So, if $r = |z|$, $\varphi_0 = \arg z$ (perhaps $\varphi_0$ is one of the arguments of the number $z$), then for each integer $k$ the notation $z = r[\cos(\varphi_0 + 2k\pi) + i\sin(\varphi_0 + 2k\pi)]$ is the trigonometric form of the complex number $z$, and no other notation is the trigonometric form of this number.

This concludes the consideration of the properties of the argument of a complex number in the school mathematics course.

One argument property

Using trigonometric form, you can easily derive the following rules for multiplying and dividing complex numbers (check it out!): if

$$z_1 = r_1(\cos \varphi_1 + i\sin \varphi_1),$$
$$z_2 = r_2(\cos \varphi_2 + i\sin \varphi_2),$$

mo

$$z_1z_2 = r_1r_2[\cos(\varphi_1 + \varphi_2) + i\sin(\varphi_1 + \varphi_2)],$$
$$\frac{z_1}{z_2} = \frac{r_1}{r_2}[\cos(\varphi_1 - \varphi_2) + i\sin(\varphi_1 - \varphi_2)].$$

The following important theorem follows indefinitely from this rule: Let $\varphi_1 = \arg z_1$ and $\varphi_2 = \arg z_2$. Then

$$\varphi_1 + \varphi_2 = \arg(z_1z_2),$$
$$\varphi_1 - \varphi_2 = \arg\frac{z_1}{z_2}.$$

Recall that the notation $\varphi = \arg z$ means only the fact that the number $\varphi$ is one of the arguments of the complex number $z$. This means that the formulas in the theorem should be read as follows: the sum of the arguments of the complex number $z$ is the argument of the product, and the difference of the arguments of the dividend and the dividend is the argument of the quotient.

Let's pay attention to one common mistake. Nord of the first particular theorem written in the form of a “formula”

$$\arg(z_1z_2) = \arg z_1 + \arg z_2,$$

which makes no sense, since arg $z$ is a multi-valued function, and the school mathematics course does not cover the concept of sum and equality of two multi-valued functions.

It should be kept in mind that if $\varphi_1 = \arg z_1$, $\varphi_2 = \arg z_2$ and $\varphi = \arg(z_1z_2)$ then
