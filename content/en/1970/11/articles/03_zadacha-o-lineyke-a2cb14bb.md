---
id: 1970-11-zadacha-o-lineyke-a2cb14bb
issue: kvant_1970_11
year: 1970
number: "11"
title: '[Ruler problem]'
rubric: smes
page_first: 12
page_last: 17
page_labels: 10, 12, 14, 15
tag: P4D3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3bf506d8b05a24c0ea596fd4e66ebf7061e0f22ccea85edbdb54fd440f37a131
prompt_sha256: draft-1
translated_from: content/ru/1970/11/articles/03_zadacha-o-lineyke-a2cb14bb.md
source_content_sha256: 268df441e1b6132de333aef26167840f070b39ab7eadc65e150a5b382f67ab2d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

So that at this point there is no force acting on it (the voltage was zero) and so that when the charge is deflected in any direction, a force acts on it, it returns to the point at which the charge is located (the field voltage vectors at all surrounding points must be directed to the point at which the charge is located, there must still be a charge of the opposite sign! Thus, when the charge is mixed, the balance will necessarily be disrupted, and the charges will either collide or fly apart.

The concept of electrons rotating around nuclei was first introduced by Rutherford. And although the range model of the atom with electrons rotating around the nucleus encountered many seemingly insoluble difficulties, the further development of physics showed it to be correct. But this is a topic for another story.

Exercise

1. Draw an approximate picture of the linear force field of two charges of different types and sizes.
2. Can linear electrostatic fields of force be closed?
3. Sometimes they say that lines of force are the trajectories along which a positive charge would move in a field if it were introduced into this field and left to itself. Is this statement correct?
4. There are two concentric spheres with radii $R_1$ and $R_2$ and charges $q_1$ and $q_2$ ($R_1 < R_2$). How does the voltage of the field of charges on a sphere depend on the distance to their common center?
5. How does the field voltage of a uniformly charged ball depend on the distance to the center of the ball?
6. Find how the field voltage of an infinite uniform charging filament depends on distance.
7. Find the field voltage of a very long uniform charging cylinder.
8. Show that inside a hollow conductor the field is zero regardless of the shape of the conductor and the cavity (shielding).

The simplest simple nine-digit (or longer) numbers do not exist.

Although this ruler only has 4 divisions, it can be used to change all (integer) distances from 1 to 13 cm.

What is the smallest number of divisions that must be placed on a ruler 9 cm long so that it changes all distances from 1 to 9 cm?

What about a 12cm ruler?

⟦folio 12⟧

Definition. The greatest common divisor of numbers or polynomials is their common divisor that is divisible by any of their common divisors without a remainder.

We will denote the gcd of numbers or polynomials $a, b$ as follows: gcd $(a, b)$. For example, GCD $(5, 10) = 5$; GCD $(x^2, 3x-x^2) = x$; GCD $(x^3-x^2,x-1) = x-1$.

Japanese most common divisor

For numbers, there are two known ways to find GCD.

Method 1. We decompose both numbers into prime factors and take the product of those of them that appear in both numbers. For example, reducing the fraction $\frac{3770}{9425}$, you can write: $\frac{3770}{9425} = \frac{2\cdot 5\cdot 13\cdot 29}{5\cdot 5\cdot 13\cdot 29}$;

GCD $(3770, 9425) = 5\cdot 13\cdot 29 = 1885$, $\frac{3770}{9425} = \frac{2}{5}$

What's wrong with this method? First, you must first prove that any natural number can be factorized into prime factors and, moreover, in a unique way. Secondly, in order to find this decomposition, a lot of work will have to be done, mainly in the direction. After all, we will find all the divisors of each of the numbers, but we only need their most common divisor.

As we will see later, it will be even worse to bypass the matter with polynomials: the expansion always exists, but, generally speaking, it is impossible to find it, unless someone specially arranged it so that the expansion is easy to find (as happens in specific examples).

But you don’t have to decompose numbers into polynomials.

Method 2. Euclidean algorithm. It is based on the following lemmas.

Lemma 1. Any natural number $q$ can be divided with a remainder by another natural number $p$, that is, represent $q$ as $q = kp+p_1$, where $0 \leq p_1 < p$.

Lemma 2. If the number $d$ is the GCD of the numbers $p$ and $q$.

Note that this lemma allows us not only to find, but also to prove the existence of the GCD of two numbers, because it reduces questions about the existence and location of the GCD to smaller numbers.

Prove these lemmas yourself. In Lemma 1, we need to break the number line into pieces by points $0, p, 2p, 3p, \dots$ and find which of them contains the point $q$. In Lemma 2, we must assume that the number $d$ is divisible by any common divisor of the numbers $p$ and $p_1$, and also that both numbers $p, p_1$ are divisible by $d$, and prove that the number $d$ has the same two properties relative to the numbers $p$ and $q$.

Now, using the example discussed in method 1, we will outline the Euclidean algorithm itself - a sequence of actions that allows you to find the gcd of the numbers $q$ and $p$. Next we write the sequence of formulas in general form, and on the right - for example.

Step 1. Using Lemma 1, divide $q$ by $p$. Let's say:
$q = k_0p+p_1, 0 \leq p_1 < p$; $9425 = 2\cdot 3770+1885, 0 \leq 1885 < 3770$.
Based on Lemma 2, we conclude that
GCD $(q, p) = \text{НОД}(p, p_1)$; $\text{НОД}(9425, 3770) = \text{НОД}(3770, 1885)$.

Step 2. See if $p_1$ is equal to zero.
If $p_1$ is equal to zero, then we end the process and go to step 3.

⟦folio 14⟧

In Lemma 1, the number $p_1$ was smaller than $p$ in magnitude, and for polynomials, the “size” is taken to be the degree of the polynomial. An example of dividing polynomials with a remainder is given below, using it you yourself will prove this lemma.

Example. Divide the polynomial $2x^5 + 4x^4 - 2x^3 - x + 1$ by the polynomial $x^2 + 2x + 5$ using a corner. It turns out:

$$\frac{-2x^5 + 4x^4 - 2x^3 - x + 1}{2x^5 + 4x^4 + 10x^3} = \frac{x^2 + 2x + 5}{2x^3 - 12x + 24}$$

$2x^5 + 4x^1 - 2x^3 - x + 1 = (2x^3 - 12x + 24)(x^2 + 2x + 5) + (11x - 119)$. Now we have the required lemmas and we can act according to the Euclidean algorithm, that is, construct a sequence of divisions with remainders (for polynomials!), in which the polynomial is successively decreased:

$$Q(x) = K_0(x) P(x) + P_1(x),$$
$$P(x) = K_1(x) P_1(x) + P_2(x),$$
$$P_1(x) = K_2(x) P_2(x) + P_3(x),$$

$$P_{m-2}(x) = K_{m-1}(x) P_{m-1}(x) + P_m(x),$$
$$P_{m-1}(x) = K_m(x) P_m(x).$$

In this case, GCD $(Q(x), P(x)) = \text{НОД}(P(x), P_1(x)) = \dots = \text{НОД}(P_{m-1}(x), P_m(x)) = \text{НОД}(P_m(x), 0) = P_m(x)$. The last quotient $P_m(x)$ is the gcd of the original polynomials (check all this).

These practical formulas are obtained by dividing with a corner, which in the very first example looks like this:

$$\frac{x^9 - x^8 - x^7 - 3x^6 + x^5 + 4x^4 + 4x^3 + x^2 - 2x - 1}{x^9 - x^8 - 3x^6 + x^5 + x^4 + 2x^3 - x} = \frac{x^8 - x^7 - 3x^5 + x^4 + x^3 + 2x^2 - 1}{x^8 - x^7 - 3x^5 + x^4 + x^3 + 2x^2 - x - 1}$$

Now it remains to reduce the algebraic fraction (2) by the last divisor $-x^7 + 3x^4 + 2x^3 + x^2 - x - 1$, that is, divide the numerator and denominator in (2) by the resulting gcd. Having done all this, we get $\frac{x - 1}{x^2 - x - 1}$.

This is the answer.

If you read N.M. Beskin’s article “Continued Fractions” («Kvant» No. 8), you may notice that the procedure described here is exactly the reduction of polynomials by expansion into whole fractions, carried out in the same way as for rational numbers. We rewrote the fraction $\frac{P(x)}{Q(x)}$ as follows:

$$\frac{P(x)}{Q(x)} = \frac{P(x)}{K_0(x) P(x) + P_1(x)} = \frac{1}{K_0(x) + \frac{P_1(x)}{P(x)}}$$,

⟦folio 15⟧

$$\frac{P(x)}{Q(x)} = \frac{1}{K_0(x) + \frac{P_1(x)}{K_1(x) P_1(x) + P_2(x)}} = \frac{1}{K_0(x) + \frac{1}{K_1(x) + \frac{P_2(x)}{P_1(x)}}}$$

and so on. In the end $\frac{P_m(x)}{P_{m-1}(x)} = \frac{1}{K_m(x)}$, all that remains is to turn the virgin fraction from polynomials. In the example under consideration, this is done like this: $\frac{1}{x + \frac{1}{-x+1}} = \frac{x-1}{x^2-x-1}$.

Simplify expressions:

1. $\frac{x^4 - 3x^2 + 1}{(3x^2 + 3x - 3)^2}$.
2. $\frac{x^3 + a^3}{x^4 + a^2x^2 + a^4}$.
3. $\frac{a(x^2 + 2) - 2ax - (x-1)^2 - 1}{x^4 + 4}$.
4. $\frac{x^2 + 6}{2(x^4 + 4x^2 - 12) + \frac{1}{7}(x^4 + 11x^2 + 30)}$.

TYPOS NOTED

The following should appear in the places marked below:

«Kvant» № 6

Page 6, right column. In figure for task 3 the bottom line is redundant; the entire figure is upside down.

Page 21, right column, 1 line from top: ...=(1+x^t)[(1+x)^p-(1+x^p)]×...;
7th line from the top: x^{kp+s}...
2nd line blue: ...C_{119}^3 ≡ C_{23}^6 C_{4}^3...;

Page 22, left column, 2nd line from top: ...C_{23}^6 ≡ C_4^1 C_3^1...;

Page 30, right column. In the solution to task 3, the constraint $b \geq 0$ is redundant; the case $b < 0$ must be considered separately.

Page 31, left column, 6th line:
$$x = \frac{a(2+tg\alpha)}{tg\alpha};$$
Line 3 blue:
$$V = \frac{a^3(2+tg\alpha)^3}{6tg^2\alpha};$$

Page 4, in task 15 of the system has the form:
$$\begin{cases} x+3y=3, \\ ax+4y=6. \end{cases}$$

in task 35 of the system has the form:
$$\begin{cases} 3|x|-5y=-3, \\ 2x+|y|=11. \end{cases}$$

Page 35, in task 3 (varnant 2) the equation is:
$$\log_3(\log_2x-1)^2=\sqrt{5}^{-\log_54}.$$

Page 52, right column, 3rd line blue: ... $p^2+13=17$...

Page 59, right column. In task 4, 6) answer: 5(11) 540; There was an error in dividing.

Page 60, right column,
8. $\frac{5}{6} < x < 2.$ 23. $S_\sigma = \frac{1}{2}\pi b^2$.
24. $V = -\frac{2}{3}l^2$.
Page 61, left column, 37. $0 < t \leq 0,1$.
Page 63, right column, 11th line:
$$\begin{cases} 500-80=420=100a+b, \\ 2500-496=2004=100b+a. \end{cases}$$
3 pages cover, crossword facing $90^\circ$.

«Kvant» № 7

Page 43. At the intersection of row 5 and column 8 there should be 256;
12 » » » » 46656;
14 » » » » 823 543.
Page 49, right column, 14th line from top:
$$\frac{4}{9}$$.
Page 52, right column, 15 line from top:
$$\sqrt{4r^2-h^2} = \frac{r}{\sin \frac{\pi}{n}}$$
left column, 14th line blue: ... $A_nA_1 = 2r$.
Page 59, task 1234: ... using four weighings...
