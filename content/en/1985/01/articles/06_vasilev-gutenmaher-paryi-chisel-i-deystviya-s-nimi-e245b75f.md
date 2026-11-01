---
id: 1985-1-vasilev-gutenmaher-paryi-chisel-i-deystviya-s-nimi-e245b75f
issue: kvant_1985_1
year: 1985
number: "1"
title: Pairs of numbers and operations with them
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 26
page_labels: 19-24
tag: HH1D
lang: en
source: kvant_digital
extraction: vision
content_sha256: fef6f373b7d14868a76233915a5cc420e753ddb3b024aa6de9bb29687b0dcd8e
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/06_vasilev-gutenmaher-paryi-chisel-i-deystviya-s-nimi-e245b75f.md
source_content_sha256: 0383909d75b630b1d933be0e11ef0566b10080d78310c209ded62cec868496f7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

Pairs of numbers and operations with them

Candidate of Physical and Mathematical Sciences
N. V. VASILIEV,
Candidate of Physical and Mathematical Sciences
V. L. GUTENMACHER

The content of this article is mainly accessible to students of the first grade. However, we also recommend it for high school students. The article deals with solutions to equations with two variables in integers. In this regard, various rules for multiplying pairs of numbers are considered, including the multiplication of complex numbers.

1. Equation $ax - by = c$
in whole numbers
Consider the equation
$$8x - 5y = 19.$$

Using this equation as an example, we will demonstrate a method for solving linear equations of the form $ax - by = c$ with integers $a, b$ and $c$ in integers.

Since $8 \cdot 3 - 5 \cdot 1 = 19$, the pair of numbers $x = 3, y = 1$ is a solution to the original equation. We found this solution by simple selection.

Let us now show how, having one solution, we can write down all the other solutions (there are an infinite number of them). Subtracting the equality $8 \cdot 3 - 5 \cdot 1 = 19$ from the equation $8x - 5y = 19$, we obtain $8(x - 3) - 5(y - 1) = 0$, or $x - 3 = 5(y - 1)/8$. From the last equality it is clear that the number $x - 3$ will be an integer if and only if $y - 1$ is divisible by 8, that is, $y - 1 = 8n$, where $n$ is some integer. Substituting $y - 1 = 8n$ into the numerator of the fraction $5(y - 1)/8$ and reducing it by 8, we get $x - 3 = 5n$.

Thus, all integer solutions of the original equation can be written in the following form:

$$\begin{cases} x = 3 + 5n, \\ y = 1 + 8n, \end{cases}$$

or $(x/y) = \frac{3}{1} + n\frac{5}{8}$;

here $n$ is any integer.

The second type of notation will be explained in detail in the next paragraph, but now we note that the same method produces a formula for all integer solutions of any equation $ax - by = c$ (where $a$ and $b$ are coprime numbers):

$$(x/y) = \left( \frac{x_0}{y_0} \right) + n\left( \frac{b}{a} \right),$$

where $(x_0; y_0)$ is any one of its integer solutions.

To solve the problems proposed below, you must keep in mind the following points. If the integers $a$ and $b$ have common divisors (except 1 and -1), then we must divide all integer equations by their most common divisor. In the case when $c$ is not divisible by it, the equation obviously does not have entire solutions, and in the case when it is divisible, such solutions exist - you just need to select one solution and write all the others using the formula (*).

For any numbers $a$ and $b$ there is a general method for finding one solution to the equation: this method is based on the Euclidean algorithm (see [1] and [5]).

Task and

1. Do the following equations have solutions in integers: a) $7x - 5y = 0$; b) $7x - 5y = 1$; b) $15x - 9y = 6$; d) $39x - 63y = 47$?

If the equation has solutions, then indicate one of them and write down all its solutions using the general formula.

2. How many solutions in natural (positive integers) $x, y$ does the equation have: a) $19x + 85y = 1985$; b) $7x + 5y = 99$?

3*. The machine makes blue marks on a tape 2 m long from its beginning every 7 cm and red marks also from its beginning every 5 cm. How many times will the bright and red marks be at a distance of 1 cm from each other?

2. Number pairs

If equations with one variable $x$ represent individual numbers, then an equation with two variables $x$ and $y$ are already pairs of numbers. In the previous paragraph, we showed how to obtain all other solutions from one integer solution of the equation $ax - by = c$: you need to add to one of its solutions - the pair of numbers $(x_0; y_0)$ - the pair of numbers $(b; a)$, multiplied by some integer. Now we will give the exact meaning of adding pairs of numbers and multiplying them by numbers.

For greater clarity, it is convenient for us to write pairs of numbers $(x; y)$ in the form of a column $(x/y)$; and the numbers themselves $x$ and $y$ will be called the first and second components of a given pair (column), respectively. (No need for column $(x/y)$ with fraction $\frac{x}{y}$!)

⟦folio 20⟧

Two so many are considered equal if and only if their components are equal:

$$\binom{x_1}{y_1} = \binom{x_2}{y_2},$$

only if $\begin{cases} x_1 = x_2, \\ y_1 = y_2. \end{cases}$

Adding two so many means adding their components:

let $u = \binom{x_1}{y_1}, v = \binom{x_2}{y_2},$

then $u + v = \binom{x_1 + x_2}{y_1 + y_2}$.

Since changing the places of the terms does not change the sum of the numbers: $a + b = b + a$, the same can be said about so many: $u + v = v + u$. For so many, the rule $(u + v) + w = u + (v + w)$ is also true.

Multiplying so many $u$ by the number $k$ means multiplying both of its components by $k$:

if $u = \binom{x}{y},$ then $ku = \binom{kx}{ky}$.

A special role, similar to the one played by the number 0 for numbers, is played by the zero number $\binom{0}{0}$ for numbers. If this does not lead to confusion, then it is also denoted by “0”. For every number of $u$ the equality $u + 0 = u$ is true.

It would seem natural to introduce multiplication as follows:

$$\binom{x_1}{y_1} \binom{x_2}{y_2} = \binom{x_1 x_2}{y_1 y_2}.$$

For such multiplication, all the same properties are fulfilled as for multiplication of numbers: 1) $uv = vu$, 2) $u(vw) = (uv)w$, 3) $(u + v)w = uw + vw$. The role of “one” is played by so many $e = \binom{1}{1}$.

But unlike numbers, division by zero is not always possible. For example, if $u = \binom{1}{0}$, then there are not as many $v$ as $uv = e$.

At the end of the article we will get acquainted with other, as it turns out, also natural and more meaningful rules for multiplying pairs of numbers:

$$\binom{x_1}{y_1} \binom{x_2}{y_2} = \binom{x_1 x_2 - y_1 y_2}{x_1 y_2 + x_2 y_1}.$$

This rule is replaceable in that for it the inverse operation - division by zero - is always possible.

A pair of numbers $(x; y)$, written not as so many, but as a line, is usually used to indicate the coordinates of a point on the coordinate plane $Oxy$. The coordinate method allows us to connect algebra with geometry. So, for example, the equation $ax - by = c$ corresponds to a line on the coordinate plane, and integer solutions of this equation correspond to points with integer coordinates (Fig. 1). Using the rules for adding pairs of numbers and multiplying them by a number, you can write formulas for the coordinates of a point on a line, for example, if $A = (x_1; y_1), B = (x_2; y_2)$ are two points, then the point

$$C = \frac{1}{2} \left( (x_1; y_1) + (x_2; y_2) \right) =$$

$$= \left( \frac{x_1 + x_2}{2}; \frac{y_1 + y_2}{2} \right)$$

— the middle of the segment $AB$.

Task and
4. So much data

$$u = \binom{7}{-1}, v = \binom{-2}{5}, w = \binom{1}{3}.$$

Find the following numbers: a) $2u$; b) $2u - v$; b) $u + 2v - 3w$.

5. Find the numbers $x$ and $y$ satisfying the equality

$$x \binom{-7}{-1} + y \binom{-2}{5} = \binom{1}{3}.$$

Compare the results with 4 c).

6. a) Let the given points be $A = (7; -1)$ and $B = (-2; 5)$. Find the coordinates of a point $C = (x; y)$ such that $B$ is the midpoint of the segment $AC$. 6) Find the coordinates of the points $D$ and $E$, which divide the segment $AB$ into three equal parts.

3. Equation $x^2 - dy^2 = 1$ in integers

In the first paragraph, we showed how, starting from one solution of the equation $ax - by = c$, we can obtain and write an infinite series of its solutions. We will get a similar result for the equation $x^2 - dy^2 = 1$, where $d$ is a natural number that is not a perfect square. But this will require your own, more complex method. We will demonstrate it using the example of the equation

$$x^2 - 2y^2 = 1.$$

This equation has very solutions (1; 0) and (-1; 0). It is clear that if $(x; y)$ is a solution to the equation, then $(-x; y), (x; -y)$ and $(-x; -y)$ are also solutions. Therefore, we can limit ourselves to searching only for positive (natural) solutions. Here are two such solutions: (3; 2), (17; 12) - farthest in their

⟦folio 21⟧

It is difficult to advance in Japan.

The playing number $\sqrt{2}$ turned out to be an unexpected help here. User, using the identity $a^2 - b^2 = (a + b)(a - b)$, we factorize the left side of the equation $x^2 - 2y^2 = 1$

$(x + y\sqrt{2}) (x - y\sqrt{2}) = 1$

and substitute here our first solution in natural numbers $x = 3, y = 2$:

$(3 + 2\sqrt{2}) (3 - 2\sqrt{2}) = 1.$

It turns out that the second solution can be obtained if, using the identity $(a + b)^2 = a^2 + 2ab + b^2$, we square the number $3 + 2\sqrt{2}$ (or $3 - 2\sqrt{2}$):

$(3 + 2\sqrt{2})^2 = 9 + 12\sqrt{2} + 8 = 17 + 12\sqrt{2},$

$(3 - 2\sqrt{2})^2 = 9 - 12\sqrt{2} + 8 = 17 - 12\sqrt{2}.$

The pair (17; 12) is the second solution. Let's check this as follows. Let us square both sides of the correct equality (2):

$(3 + 2\sqrt{2})^2 (3 - 2\sqrt{2})^2 = 1$

and we get

$(17 + 12\sqrt{2}) (17 - 12\sqrt{2}) = 1$, or

$17^2 - 2 \cdot 12^2 = 1.$

The following new solution can be obtained by cubeing the number $3 + 2\sqrt{2}$:

$(3 + 2\sqrt{2})^3 = (3 + 2\sqrt{2})^2 (3 + 2\sqrt{2}) = 99 + 70\sqrt{2}.$

In exactly the same way we obtain $(3 - 2\sqrt{2})^3 = 99 - 70\sqrt{2}$. Since $(3 + 2\sqrt{2})^3 (3 - 2\sqrt{2})^3 = 1$, we have $(99 + 70\sqrt{2}) (99 - 70\sqrt{2}) = 99^2 - 70^2 \cdot 2 = 1$, that is, $(99; 70)$ is also a solution to the equation $x^2 - 2y^2 = 1.$

Now, probably, the way to obtain new solutions is already clear - we must continue to raise $3 + 2\sqrt{2}$ to a power, that is, if

$(3 + 2\sqrt{2})^n = x_n + y_n\sqrt{2},$

where $x_n$ and $y_n$ are natural numbers, then the pair $(x_n; y_n)$ is a solution to the equation $x^2 - 2y^2 = 1$. It can be proven that this method gives all its solutions in natural numbers.

Let us now consider more general equations of this form:

$x^2 - dy^2 = 1,$

where $d$ is a natural number that is not a perfect square.

It turns out that all its solutions in natural numbers are obtained by the same method. Guess at least its solution $(x_0; y_0)$ and raise the number $x_0 + y_0\sqrt{d}$ to the power $n$:

$(x_0 + y_0\sqrt{d})^n = x_n + y_n\sqrt{d}.$

(The smallest solution is a solution $(x_0; y_0)$ such that for any other solution $(x; y)$ the inequality $x_0 + y_0\sqrt{d} < x + y\sqrt{d}$ holds.)

For any numbers $d$ has a general method for finding the smallest natural solution, based on decomposing numbers into integer fractions (see [1] and [2]).

Task 1.

7*. Find even solutions in natural numbers to the equation: a) $x^2 - 3y^2 = 1$; b) $x^2 - 5y^2 = 1$; b) $x^2 - 2y^2 = -1$.

8*. Prove that

$x_n = \frac{1}{2} ((3 + 2\sqrt{2})^n + (3 - 2\sqrt{2})^n),$

$y_n = \frac{1}{2\sqrt{2}} ((3 + 2\sqrt{2})^n - (3 - 2\sqrt{2})^n) -$

integers satisfying the equation $x^2 - 2y^2 = 1$, a) for $n = 1, 2, 3, 6$ for any natural number $n$.

9. Find all integer solutions of the equation $x^2 - 4y^2 = 13$.

10*. Prove that the equation $x^2 - 3y^2 = -1$ has no integer solution.

4. Numbers of the form $p + q\sqrt{2}$

Let us pay attention to the interesting circumstance that numbers of the form $p + q\sqrt{2}$ with heterononal $p$ and $q$ can naturally be associated with a pair of numbers $(p; q)$. Moreover, the equality of two numbers $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ occurs if and only if $\binom{p_1}{q_1} = \binom{p_2}{q_2}$.

Indeed, let $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ and $q_1 \neq q_2$; then it turns out that $\sqrt{2}$ is equal to the number $(p_1 - p_2)/(q_2 - q_1)$, but this is false. Therefore, the equality $q_1 = q_2$ must hold; but then from the equality $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ we immediately obtain that $p_1 = p_2$.

⟦folio 22⟧

The rule for adding numbers $p_1 + q_1\sqrt{2}$ and $p_2 + q_2\sqrt{2}$ is the same as for stolniki:
$$p_1 + q_1\sqrt{2} + (p_2 + q_2\sqrt{2}) = (p_1 + p_2) + (q_1 + q_2)\sqrt{2},$$
$$\binom{p_1}{q_1} + \binom{p_2}{q_2} = \binom{p_1 + p_2}{q_1 + q_2}.$$

Now the variable numbers $p_1 + q_1\sqrt{2}$ and $p_2 + q_2\sqrt{2}$:
$$p_1 + q_1\sqrt{2}(p_2 + q_2\sqrt{2}) = (p_1 + p_2) + (q_1 + q_2)\sqrt{2}.$$
As a result, we arrive at a number of the same form and obtain a new multiplication rule for numbers with rational complexes $p_1, q_1, p_2, q_2$:
$$\binom{p_1}{q_1}\binom{p_2}{q_2} = \binom{p_1 p_2 + 2 q_1 q_2}{p_1 q_2 + p_2 q_1}.$$

(3)

If you follow this rule, you can write the solution to the multiplication $x^2 - 2y^2 = 1$ like this:
$$\binom{x_n}{y_n} = \binom{3}{2}^n$$ (weigh the stolnik $n$ times on yourself).

For rule (3), the general properties of multiplication are satisfied; the role of one here is played by the stolnik $\binom{1}{0}$, since it corresponds to the number $1 = 1 + 0\sqrt{2}$.

An interesting symmetry in the set of such numbers helps a lot in operating with the numbers $p + q\sqrt{2}$: each number $a = p + q\sqrt{2}$ corresponds to the number $\bar{a} = p - q\sqrt{2}$, which is called conjugate to $a$. (For stolniks, the transition to the conjugate is simply a change in the sign $y$ of the second component.)

The pairing operation has the following properties:
$$\bar{a} + \bar{b} = \bar{a} + \bar{b}, \bar{a}\bar{b} = \bar{a}\bar{b}, \bar{a} = a.$$

But the most important thing is that the product of conjugates $(p + q\sqrt{2})(p - q\sqrt{2}) = p^2 - 2q^2$ no longer contains $\sqrt{2}$; $\bar{a}\bar{b}$ is a rational number. This allows you to divide numbers of the form $p + q\sqrt{2}$ by each other, thereby obtaining a number of the same form. To divide $\beta$ by $a$, simply multiply $\beta$ by $\bar{a}$ and divide the result by $\bar{a}\bar{b}$.

We have already used the parameters of conjugate numbers when solving the multiplication $x^2 - 2y^2 = 1$. We represented the left side $x^2 - 2y^2$ as the product of two conjugate numbers
$$a = x + y\sqrt{2}, \bar{a} = x - y\sqrt{2}.$$

Let us now take two numbers $a = x_1 + y_1\sqrt{2}$ and $\beta = x_2 + y_2\sqrt{2}$ and their conjugates $\bar{a} = x_1 - y_1\sqrt{2}$ and $\bar{b} = x_2 - y_2\sqrt{2}$. Let's look at the product $\alpha\bar{a}\beta\bar{b}$. Performing the calculation in a certain order - first $\bar{a}\bar{b}$, then $\beta\bar{b}$ and then $(\alpha\bar{a})(\beta\bar{b})$ - we get:
$$\alpha\bar{a}\beta\bar{b} = (x_1^2 - 2y_1^2)(x_2^2 - 2y_2^2).$$

(4)

If we calculate the same product $\alpha\bar{a}\beta\bar{b}$ in a different order, then we get
$$\alpha\bar{b} = (x_1x_2 + 2y_1y_2) + (x_1y_2 + x_2y_1)\sqrt{2},$$
$$\bar{a}\bar{b} = (x_1x_2 + 2y_1y_2) - (x_1y_2 + x_2y_1)\sqrt{2},$$
$$\alpha\bar{a}\beta\bar{b} = (x_1x_2 + 2y_1y_2)^2 = 2(x_1y_2 + x_2y_1)^2.$$

(5)

From equalities (4) and (5) we also obtain $(x_1^2 - 2y_1^2)(x_2^2 - 2y_2^2) = (x_1x_2 + 2y_1y_2)^2 - 2(x_1y_2 + x_2y_1)^2.$

This also leads to an interesting connection between integer solutions of multiplication of the more general form $x^2 - 2y^2 = c$.

If the pair of integers $(x_1; y_1)$ satisfies the equality $x_1^2 - 2y_1^2 = c_1$, and the pair of integers $(x_2; y_2)$ satisfies the equality $x_2^2 - 2y_2^2 = c_2$, then the pair of integers $(x_1x_2 + 2y_1y_2; x_1y_2 + x_2y_1)$ is a solution to the multiplication $x^2 - 2y^2 = c_1c_2$.

Everything said about numbers of the form $a + b\sqrt{2}$ is also true for numbers of the form $a + b\sqrt{d}$, where $d$ is a prime number (or a natural number, not divisible by a square). In particular, it is also true for $d = -1$; The resulting identity will play a central role in the next point.

Tasks
11. Rearrange the numbers $(2 - \sqrt{3})(7 - 4\sqrt{3})(2 + \sqrt{3})(7 + 4\sqrt{3})$.

12. Divide the numbers depicted from the irrationality in the denominator
a) $\frac{9 + 4\sqrt{5}}{9 - 4\sqrt{2}}$; b) $\frac{p_1 + q_1\sqrt{d}}{p_2 + q_2\sqrt{d}}$.

13*. Prove that the product of numbers of the form $x^2 + 5y^2$, where $x$ and $y$ are integers, is again a number of the same type. Find all such numbers less than 100.

5. Remarkable identity and composition of Vieta

Any two pairs of numbers $(a_1; b_1)$ and $(a_2; b_2)$ are connected by the following identity, known to Diophantus:
$$a_1^2 + b_1^2)(a_2^2 + b_2^2) = (a_1a_2 - b_1b_2)^2 + (a_1b_2 + a_2b_1)^2.$$

It is obtained from identity (8) for $d = -1$ and is often used in algebra and number theory. We will discuss here another application of it: an interesting method that allows you to obtain from two right triangles a new right triangle with a hypotenuse equal to the product of their hypotenuse.

Take one right triangle with squares $a_1, b_1$ and hypotenuse $c_1$ and another with squares $a_2, b_2$ and hypotenuse $c_2$. Since according to the Pythagorean theorem
$$a_1^2 + b_1^2 = c_1^2$$ and $a_2^2 + b_2^2 = c_2^2,$
the same thing (9) can be written as follows:
$$(c_1c_2)^2 = (a_1a_2 - b_1b_2)^2 + (a_1b_2 + a_2b_1)^2.$$

⟦folio 23⟧

From this equality it is clear that there exists a right triangle with squares $|a_1a_2-b_1b_2|$, $a_1b_2+a_2b_1$ and hypotenuse $c_1c_2$. Apparently, this was first noticed in the 16th century by the French mathematician Francois Viète (see [7]), so let’s call this method of obtaining a new right triangle from two right triangles “Viète’s composition.”

Let us consider two identical right triangles with squares $m, n$ and put $a_1=a_2=n$, $b_1=b_2=m$ in identity (9). We get

$$(m^2+n^2)^2=(m^2-n^2)^2+(2mn)^2.$$

We see that Vieta's composition produces a new right triangle with squares $|m^2-n^2|$, $2mn$ and hypotenuse $m^2+n^2$. It is interesting that all right triangles with integer (coprime) sides $a, b$, $c$ - the so-called “Pythagorean triples” - can be obtained using these formulas

$$c=m^2+n^2, a=m^2-n^2, b=2mn, (10)$$

where $m$ and $n$ are (coprime) natural numbers of different parities, $m>n$.

The most important thing is that the Vieta composition of two right-angled triangles produces a new right-angled triangle (Fig. 2), whose angle against the square $a_1b_2+a_2b_1$ is equal to the sum $\varphi+\psi$ of the angles $\varphi$ and $\psi$ of the original triangles against the squares $b_1$ and $b_2$ (if $\varphi+\psi<90^\circ$; if $\varphi+\psi>90^\circ$, then this angle is equal to $180^\circ-(\varphi+\psi)$). Thus, Vieta's composition can be given a geometric number. The Vieta composition of two right triangles is a right triangle with hypotenuse $c_1c_2$. Apparently, this was first noticed in the 16th century by the French mathematician Francois Viète (see [7]), so let’s call this method of obtaining a new right triangle from two right triangles “Viète’s composition.”

Let us consider two identical right triangles with squares $m, n$ and put $a_1=a_2=n$, $b_1=b_2=m$ in identity (9). We get

$$(m^2+n^2)^2=(m^2-n^2)^2+(2mn)^2.$$

We see that Vieta's composition produces a new right triangle with squares $|m^2-n^2|$, $2mn$ and hypotenuse $m^2+n^2$. It is interesting that all right triangles with integer (coprime) sides $a, b$, $c$ - the so-called “Pythagorean triples” - can be obtained using these formulas

$$c=m^2+n^2, a=m^2-n^2, b=2mn, (10)$$

where $m$ and $n$ are (coprime) natural numbers of different parities, $m>n$.

The most important thing is that the Vieta composition of two right-angled triangles produces a new right-angled triangle (Fig. 2), whose angle against the square $a_1b_2+a_2b_1$ is equal to the sum $\varphi+\psi$ of the angles $\varphi$ and $\psi$ of the original triangles against the squares $b_1$ and $b_2$ (if $\varphi+\psi<90^\circ$; if $\varphi+\psi>90^\circ$, then this angle is equal to $180^\circ-(\varphi+\psi)$). Thus, Vieta's composition can be given a geometric number. Vieta's composition of two right triangles results in the newest straight line of the triangle with vertices $a, b, c$.

Exercise

14. On a clipart table depicted in ancient Babylon around 1500 BC. e., among other Pythagorean triangles the following is indicated: 4961, 6480, 8161. Which $m$ and $n$ in formulas (10) does it correspond to?

15*. Find cos $75^\circ$ using Vieta composition for two right triangles with angles $30^\circ$ and $45^\circ$.

16. In Pythagorean triangles, on sides 5, 12, 13 and 7, 24, 25, the hypotenuse is 1 greater than one of the legs.

a) Find two more such Pythagorean triangles.

b) Find a general formula for the sides of such triangles.

b) Identify among them the triangles whose hypotenuse is a perfect square (like the triangle 7, 24, 25 = 5²).

6. Complex numbers $a+bi$

In the previous paragraphs, using the numbers visible $a+b\sqrt{d}$, we arrived at identity (8), which turns out to be true for any $d$. Then we put the identity $d=-1$ in this; at the same time, the expressions $a+b\sqrt{d}=a+b\sqrt{-1}$ themselves lost their meaning, since there is no $\sqrt{-1}$ among the numbers - after all, the square of any number is a non-negative number. Nevertheless, it turns out to be advisable to use a new “minimum” number, the square of which is equal to -1. It is denoted by the letter $i$ (from the Latin word imaginary - mine, imaginary).

An expression of the form $a+bi$, where $a$ and $b$ are common numbers, is called complex numbers. Two complex numbers, by definition, are equal if and only if their components are equal:

⟦folio 24⟧

$a_1 + b_1 i = a_2 + b_2 i$ only if $a_1 = a_2$ and $b_1 = b_2$.

Addition and multiplication of complex numbers $a + bi$ is performed in the same way as they were performed for numbers of the form $a + b\sqrt{2}$ with rationals $a$ and $b$. However, here $a$ and $b$ can be any numbers, and $i^2 = -1$. As a result of these operations we again obtain an expression of the form $a + bi$:

$$(a_1 + b_1 i) + (a_2 + b_2 i) = (a_1 + a_2) + (b_1 + b_2) i,$$
$$(a_1 + b_1 i)(a_2 + b_2 i) = (a_1 a_2 - b_1 b_2) + (a_1 b_2 + a_2 b_1) i.$$

We now see where the multiplication (1) of so many, which we indicated in paragraph 2, came from. This multiplication was essentially already discussed in the previous paragraph - as Vieta’s composition of two right triangles with legs $(a_1; b_1)$ and $(a_2; b_2)$.

A special role is played by the zero complex number $0 = 0 + 0i$, the unit $1 = 1 + 0i$ and the minus unit $i = 0 + 1i$. Note that if any component $a$ or $b$ of the complex number $a + bi$ is equal to zero, then the corresponding part of the complex number is omitted when writing.

In the world of complex numbers, one can divide by any number other than zero $0 = 0 + 0i$. When calculating the quotient of two numbers, it is convenient to multiply both of these numbers by conjugating the number $c - di$ to the division $z = c + di$:

$$\frac{a + bi}{c + di} = \frac{(a + bi)(c - di)}{(c + di)(c - di)} = \left( \frac{ac + bd}{c^2 + d^2} \right) + \left( \frac{bc - ad}{c^2 + d^2} \right) i.$$

Complex numbers first appeared in algebra, in problems about solving algebraic equations of triangles and higher degrees. However, the applications of complex numbers cover almost all the main areas of mathematics and physics - geometry, number theory, mathematical analysis and probability theory, calculation of electrical purposes, hydrodynamics and quantum mechanics.

We obtained complex numbers as pairs of real numbers, defining multiplication for them by rule (1), satisfying natural conditions - commutativity, associativity, distributivity. For mathematics, the problem of classifying all such pairs is interesting. It turns out that they all fit into the general scheme: pairs $(x, y)$ are written in the form of “generalized complex numbers” $x + yj$ and $j^2$ in calculations are replaced by $r + sj (r, s$ - fixed numbers, see problem 19); here there are possible three essentially different servants (to which the others can be reduced):

$$(1) j^2 = 1$$

(the rule $j^2 = 2$, which we studied in detail, belongs to this type); (2) $j^2 = 0$ (curiously, the corresponding multiplication rule written for columns):

$$\left( \frac{x_1}{y_1} \right) \left( \frac{x_2}{y_2} \right) = \left( \frac{x_1 x_2}{x_1 y_2 + x_2 y_1} \right)$$

is a reversal of the rule for adding fractions

$$\frac{y_1}{x_1} + \frac{y_2}{x_2} = \frac{y_1 x_2 + x_2 y_1}{x_1 x_2}$$

and finally (3) $j^2 = -1$ are real complex numbers.

Task and

17. We will represent the complex number $x + iy$ by the point $(x; y)$ on the coordinate plane. Let $u = 1 - i$, $v = -2 + 5i$. Find a) $u$; 6) $v$; b) $uv$; d) $u/v$ and draw all these numbers on the coordinate plane.

18. Let $z = \frac{1 + i}{\sqrt{2}}$, $w = \frac{1 - i \sqrt{3}}{2}$. Find a) $z^2, z^4, z^8$; 6) $w^2, w^3, w^6, w^2 + w + 1$.

19*. Let $r$ and $s$ be two fixed numbers. Let us define multiplication on pairs of numbers (all, not just rational ones) by the formula

$$\left( \frac{x_1}{y_1} \right) \cdot \left( \frac{x_2}{y_2} \right) = \left( \frac{x_1 x_2 + ry_1 y_2}{x_1 y_2 + x_2 y_1} \right).$$

(This rule corresponds to the multiplication of “generalized complex numbers” $x + jy$, where $j^2 = r + sj$.) a) Check that for this multiplication the basic properties 1) - 3) from point 2 are satisfied. b) Which pair $e$ plays the role of unit? b) For what $r$ and $s$, for any pair $u$ other than $0 = \left( \begin{array}{c} 0 \\ 0 \end{array} \right)$, is there a $v$ such that $uv = e$? r) For which $r$ and $s$ is there a pair $u \neq 0$ such that $u^2 = 0$? 20. Let us define the multiplication of pairs of numbers $(a; b)$ as follows: each pair of numbers $(a; b)$ corresponds to a linear function $u(t) = at + b$, and the product $(a_1; b_1)$ by $(a_2; b_2)$ corresponds to the composition of the function $u_1(t) = a_1 t + b_1$ and $u_2(t) = a_2 t + b_2$, that is, substitution of the first into the second $u_2(u_1(t)) = a_2(a_1 t + b_1) + b_2 = a_2 a_1 t + a_2 b_1 + b_2$, or

$$\left( \begin{array}{c} a_1 \\ b_1 \end{array} \right) \left( \begin{array}{c} a_2 \\ b_2 \end{array} \right) = \left( \begin{array}{c} a_1 a_2 \\ a_2 b_1 + b_2 \end{array} \right).$$

Which of the following laws holds for this multiplication: $uv = vu$, $(uv)w = u(vw)$, $u(v + w) = uv + uw$, $(u + v)w = uw + wv$?

List of additional literature

1. Gelfond A. O. Solving equations in integers. M.: Nauka, 1983. - (Popular lectures on mathematics, issue 8).
2. Nesterenko Yu. V., Nikshin E. M. Essay on whole fractions. Kvant, 1983, No. 5, 6.
3. Vaguten N. Conjugate numbers. Kvant, 1980, No. 2.
4. Ashmanov S. Numbers and polynomials. Kvant, 1980, No. 2.
5. Correspondence mathematical algebras. M.: Nauka, 1981.
6. Pontryagin L. S. Complex numbers. Kvant, 1982, No. 4.
7. Bashmakova I. G. Formation of algebra. M.: Znanie, 1979.
