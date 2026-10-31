---
id: 1976-5-mordkovich-smyishlyaev-ante-a80c75c7
issue: kvant_1976_5
year: 1976
number: "5"
title: Antje
authors:
  - Мордкович А. Г.
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 45
page_last: 49
page_labels: 43, 44, 46, 47
tag: H4XM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1f5e9062d9c31c831d3be74147cb2b743d06a629c38687dea859bb20c268812d
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/09_mordkovich-smyishlyaev-ante-a80c75c7.md
source_content_sha256: c98edfc659a69591a93b61a05ce7406ffc574a69c42c3ae09154164fe475eefe
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

1. Definition

In many problems of algebra, number theory, mathematical analysis, and probability theory, the occurrence of an integer not exceeding a given number (remember, for example, the determination of the characteristic of the decimal logarithm). Such an integer received a special name: “integer part of a number.”

So, the integer part of the system is the largest integer $n$, not exceeding $x$; the integer part of the number $x$ is represented by the symbol $[x]$ or (less commonly) $E(x)$ (from the French Entier (“anteche”) - “whole”). For example, $[2,3]=2$, $[-2,3]=-3$.

If $n \leqslant x < n+1$ and $n$ are integers, then $[x]=n$. Since $[x] \leqslant x < [x]+1$, we have $0 \leqslant x-[x] < 1$. The number $\alpha=x-[x]$ is called the fractional part of the number $x$ and stands for $\{x\}$. So, $0 \leqslant \{x\} < 1$. Obviously $x=[x]+\{x\}$.

The graph of function $y=[x]$ is depicted on figure 1, and function $y=\{x\}$ is depicted on figure 2.

2. Some properties

$1^\circ$. If $p$ is an integer, then $[x+p]=[x]+p$.

$2^\circ$. For any real numbers $x$ and $y$: $[x+y] \geqslant [x]+[y]$.

Proof. We have $x=[x]+\alpha, 0 \leqslant \alpha < 1; y=[y]+\beta, 0 \leqslant \beta < 1$. Then $x+y=[x]+\alpha+[y]+\beta=[x]+[y]+\gamma$, where $\gamma=\alpha+\beta$. So, $0 \leqslant \gamma < 2$.

If $0 \leqslant \gamma < 1$, then $[x+y]=[x]+[y]$.

If $1 \leqslant \gamma < 2$, i.e. $\gamma=1+\gamma'$, where $0 \leqslant \gamma' < 1$, then $x+y=[x]+[y]+1+\gamma'$ and $[x+y]=[x]+[y]+1>[x]+[y]$.

Sweeping. The property $2^\circ$ extends to any finite number of terms: $[x_1+x_2+\ldots+x_n] \geqslant [x_1]+[x_2]+\ldots+[x_n]$.

Fig. 1. Fig. 2.

⟦folio 44⟧

3°. If $[x] = [y]$, then $|x - y| < 1$.
4°. If $n$ is a natural number, then $\left[\frac{x}{n}\right] = \left[\frac{x}{n}\right]$.

Proof. Let's put $\left[\frac{x}{n}\right] = a$. Then $a \leqslant \frac{[x]}{n} < a + 1$, or $a \leqslant [x] < n (a + 1)$.

Since the numbers $an$ and $n (a + 1)$ are integers, the number $x$ must also satisfy the inequality $an \leqslant x < n (a + 1)$, hence $a \leqslant \frac{x}{n} < a + 1$, i.e. $\left[\frac{x}{n}\right] = a$.

3. Anties in equations
The solution to an equation with a variable under the “integer part” sign usually coincides with the solution to inequalities or systems of inequalities.
Let's look at a few examples.
Problem 1. Solve the equation
$$\left[\frac{5 + 6x}{8}\right] = \frac{15x - 7}{5}.$$
Solution. Let's put $\frac{15x - 7}{5} = t$. Then $x = \frac{5t + 7}{15}$, and the equation becomes
$$\left[\frac{10t + 39}{40}\right] = t.$$
From the definition of the integer part it follows that $0 \leqslant \frac{10t + 39}{40} - t < 1$. Solving these inequalities, we find
$$-\frac{1}{30} < t \leqslant 1, 3.$$

Fig. 3.
Fig. 4.

⟦folio 46⟧

Task 5. Prove that the number $C_{1976}^{976}$ is divisible by $76^2$.

Solution. Since $76 = 2^2 \times 19$, then for divisibility by $76^2$ it is necessary and sufficient that $C_{1976}^{976}$ is divisible by $2^4$ and $19^2$.

We have $C_{1976}^{976} = \frac{1976!}{976! \cdot 1000!}$. Let's find what the exponents $\alpha_1, \alpha_2, \alpha_3$ and $\beta_1, \beta_2, \beta_3$ are equal to, with which the numbers 2 and 19 appear in the prime factorizations of the numbers 1976!, 976! and 1000!. We have

$$\alpha_1 = \left[ \frac{1976}{2} \right] + \left[ \frac{1976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1976}{2^{10}} \right] = 1969,$$

$$\alpha_2 = \left[ \frac{976}{2} \right] + \left[ \frac{976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{976}{2^{9}} \right] = 971,$$

$$\alpha_3 = \left[ \frac{1000}{2} \right] + \left[ \frac{1000}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1000}{2^9} \right] = 994$$

and $\alpha_1 - \alpha_2 - \alpha_3 = 4$, that is, $C_{1976}^{976}$ is divisible by $2^4$.

Likewise

$$\beta_1 = \left[ \frac{1976}{19} \right] + \left[ \frac{1976}{19^2} \right] = 109,$$

$$\beta_2 = \left[ \frac{976}{19} \right] + \left[ \frac{976}{19^2} \right] = 53,$$

$$\beta_3 = \left[ \frac{1000}{19} \right] + \left[ \frac{1000}{19^2} \right] = 54$$

and $\beta_1 - \beta_2 - \beta_3 = 2$, that is, $C_{1976}^{976}$ is divisible by $19^2$.

Thus, $C_{1976}^{976}$ is divisible by $76^2$.

5. "Target points"

By integer points we will understand points $(x, y)$ of the coordinate plane with integer coordinates $x$ and $y$. We ask how to count the number of integer points lying inside a given plane figure?

Task 6. How many whole lobes are located on the sides and inside the triangle formed by the straight line $y = \frac{2}{3} x - \frac{1}{2}$, $x = 10$ and the x-axis (Fig. 5)?

Solution. Let us find the values ​​of the function $y = \frac{2}{3} x - \frac{1}{2}$ for integer $x = 1, 2, \dots, 10$ (note that $y = 0$ for $x = \frac{3}{4}$); we get the coordinates $\frac{1}{6}, \frac{5}{6}, \frac{3}{2}, \frac{13}{6}, \frac{17}{6}, \frac{7}{2}, \frac{25}{6}, \frac{29}{6}, \frac{11}{2}$ and $\frac{37}{6}$. It is easy to say that the total number of integer points lying in a given triangle (including on the boundary) is equal to the sum of the integer parts of these ordinators of the plane of points lying on the abscissa axis:

$$\left[ \frac{1}{6} \right] + \left[ \frac{5}{6} \right] + \left[ \frac{3}{2} \right] + \left[ \frac{13}{6} \right] + \left[ \frac{17}{6} \right] + \left[ \frac{7}{2} \right] + \left[ \frac{25}{6} \right] + \left[ \frac{29}{6} \right] + \left[ \frac{11}{2} \right] + \left[ \frac{37}{6} \right] + 10 = 1 + 2 + 2 + 3 + 4 + 4 + 5 + 6 + 10 = 37.$$

Answer: 37 whole points.

Note that inside this triangle there are only 37-10-6=21 integer points.

It turns out that integer points can be useful in proving action points!

⟦folio 47⟧

Task 7. Prove the possibility
quality

$$\left[ \frac{q}{p} \right] + \left[ \frac{2q}{p} \right] + \left[ \frac{3q}{p} \right] + \dots$$

$$\dots + \left[ \frac{(p-1)q}{p} \right] = \frac{(p-1)(q-1)}{2}$$

(p and q are mutually prime natural numbers).

Solution. Let's look directly at
a triangle with vertices $O = (0; 0)$, $A = (p; 0)$, $B = (p; q)$, $C = (0; q)$ (Fig. 6). Mark all the integer points $(x, y)$ inside the rectangle: $1 \leqslant x \leqslant p-1$, $1 \leqslant y \leqslant q-1$ (red dots on figure). The number of these points is equal to the product $(p-1)(q-1)$.

Let's draw the diagonal $OB$ of our rectangle; its equation is $y = \frac{q}{p} x$. Since $p$ and $q$ are coprime, and $x = 1$, ..., $p-1$, then numbers of the form $\frac{q}{p} x$ are not integers, i.e., there are no integer points on the diagonal $OB$, and thus in the triangle lying under the diagonal $OB$ there will be $\frac{(p-1)(q-1)}{2}$ red (whole) dots.

On the other hand, using the method described in task 6, we find that the number of these points is equal to the sum $$\left[ \frac{q \cdot 1}{p} \right] + \left[ \frac{q \cdot (p-1)}{p} \right],$$ and, therefore, the identity must be proven.

Fig. 6.

Exercises

1. Construct graphs of functions $y = [-x]$, $y = [2x]$, $y = [\sin x]$.
2. Prove action points:
a) $$\left[ \frac{n}{k} \right] + \left[ \frac{n+1}{k} \right] + \left[ \frac{n+2}{k} \right] + \dots$$
$$\dots + \left[ \frac{n+k-1}{k} \right] = n,$$
where $n$ and $k$ are natural numbers.
b) $(n+1)(n+2)(n+3) \dots (2n-1)2n = 2^n \cdot (2n-1)!!$.
(The $S!!$ denotes the product of natural numbers from 1 to $S$ of the same parity with $S$: for example, $8!! = 2 \cdot 4 \cdot 6 \cdot 8; 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$.)
3. Let $a, b, \dots, l$ be natural numbers, $a+b+\dots+l=n$. Prove that the fraction $$\frac{n!}{a!b! \dots l!}$$ is an integer.
4. Prove that if $[nx] + [ny] = [n(x+y)]$ for all natural $n$, then either $x$ or $y$ is an integer.
5. With what exponent does the prime number $p$ enter into the expansion of the number
a) $(2n)!!;$ 6) $(2n+1)!!$.
6. Solve the equations:
a) $$\left[ \frac{8x+19}{7} \right] = \frac{16(x+1)}{11};$$
b) $$\left[ \frac{x^2-2}{3} \right] = [x];$$
b) $x^4 - [x+1] = 2$.
7. The pedestrian walks at a speed of 5 km/h, stopping at separate intervals every 4 km. The duration of each stop, except the fourth, is 10 minutes, and the duration of the fourth stop is 1 hour. How far did the pedestrian travel if, having set off at 4 a.m., he arrived at the place at noon?
8. How many integer points are there in the curved trapezoid $a \leqslant x \leqslant b$, $0 \leqslant y \leqslant f(x)$, where $a$ and $b$ are natural numbers, $a = f(x)$ is a function that is continuous and positive on the segment $[a, b]$ (integer points lying on the boundary of the trapezoid are also counted)?
9. How many integer points are there in a circle of radius 6.5 centered at the origin?
10. There are 500 balls in urine, produced from 1 to 500. What is the probability that a ball drawn at random will have a number that is a multiple of any of the numbers 10, 14, 21?
