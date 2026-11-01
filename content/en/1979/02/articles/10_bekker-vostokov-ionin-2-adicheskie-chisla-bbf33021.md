---
id: 1979-2-bekker-vostokov-ionin-2-adicheskie-chisla-bbf33021
issue: kvant_1979_2
year: 1979
number: "2"
title: 2-adic numbers
authors:
  - Беккер Б. М.
  - Востоков С. В.
  - Ионин Ю. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 33
page_labels: 26-31
tag: GIF9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5007e09699af9188b20d63e196bb31a2937c671ec0fec96fb9f70c85a52f265f
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/10_bekker-vostokov-ionin-2-adicheskie-chisla-bbf33021.md
source_content_sha256: 6b5fed7703c785ca23a2cf927e4ad34e31fa359462d47fa9963582235f97be89
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

2-adic numbers

If you were asked what can be called “the distance between two rational numbers,” then, after thinking, you probably should answer: “the distance between two numbers should be called the modulus of their difference. We carry out this definition reasonably - this “distance” satisfies all the axioms of distance (see “Geometry 8”, paragraph 132). But it turns out that the distance between rational numbers that satisfies all the axioms can be calculated in another way. This was done by the German mathematician K. Hansel (1861-1941) - he even came up with a whole class of such distances. One of them is discussed in this article.

Hansel’s research turned out to be very important for algebra and mathematics in general, and his distance will help us solve two problems that, at first glance, are not related to any distances at all.

2-adic distance

Let $a$ and $b$ be rational numbers. If $a \neq b$, then we represent the number $a-b$ as $a-b = 2^k \cdot \frac{m}{n}$, where $m$ and $n$ are odd numbers, and $k$ is an integer (positive, negative or zero). The 2-adic distance between the numbers $a$ and $b$, $a \neq b$, is called the number $\rho(a, b) = 1/2^k$. If $a=b$, then put $\rho(a, b) = 0$.

Let us recall the distance axioms:

A1. $\rho(a, b) > 0$ if $a \neq b$, and $\rho(a, b) = 0$ if $a=b$.

A2. $\rho(a, b) = \rho(b, a)$.

A3. $\rho(a, c) \leqslant \rho(a, b) + \rho(b, c)$.

Properties A1 and A2 for the 2-adic distance, as well as property A3 in the case if among the numbers $a, b, c$ there are equal, very equal ones.

Let us prove property A3 for various rational numbers $a, b, c$. Let $a-b = 2^{k_1} \cdot \frac{m}{n_1}$, $b-c = 2^{k_2} \cdot \frac{m_2}{n_2}$, $a-c = 2^{k_3} \cdot \frac{m_3}{n_3}$, where all $m_i, n_i$ are odd numbers. Since $a-c = (a-b) + (b-c)$, then $k_3$ is no less than the smaller of the numbers $k_1$ and $k_2$. But then $\frac{1}{2^{k_3}}$ does not exceed the largest of the numbers $\frac{1}{2^{k_1}}$ and $\frac{1}{2^{k_2}}$, and even more so $\frac{1}{2^{k_3}} \leqslant \frac{1}{2^{k_1}} + \frac{1}{2^{k_2}}$.

So, we see that all the axioms are satisfied, so that $\rho$ can indeed be called a distance.

What changes this distance? It turns out that it changes the degree of divisibility of a rational number by 2. The more divisible a number is by 2, the closer it is to zero. For example, 8 is closer to zero than 1/2; 16 is closer to zero than 8; 480 is closer to zero than 16; 384 is closer to zero than 480.

In fact, we have proven that the 2-adic distance has property A3', which is stronger than property A3. A3'. The distance $\rho(a, c)$ does not exceed the larger of the distances $\rho(a, b)$ and $\rho(b, c)$.

Tension 1. Prove that if $\rho(a, b) \neq \rho(b, c)$, then $\rho(a, c)$ is equal to the largest of the numbers $\rho(a, b), \rho(b, c)$, and if $\rho(a, b) = \rho(b, c) \neq 0$, then $\rho(a, c) < \rho(a, b)$.

Property A3' leads to interesting consequences. Let us know that the 2-adic circle of radius $r$ with center $a$ (and a rational number, $r$ is a positive real number) is the set of rational numbers $x$ for which $\rho(a, x) < r$.

Tension 2. Prove that if two 2-adic circles have a non-empty intersection, then one of these circles is contained in the other.

⟦folio 27⟧

3. Prove that a 2-Adic circle of radius $r$ contains infinitely many pairwise disjoint 2-Adic circles of radius $r$.

By analogy with the ordinary model of a number, we define the 2-adic modulus $\|a\|$ of a rational number $a$ as the 2-adic distance from this number to zero: if $a = 2^k \frac{m}{n}$, where $m$ and $n$ are odd numbers, then $\|a\| = \rho(0, a) = \left(\frac{1}{2}\right)^k$. It is easy to set the following properties of a 2-adic module:

M1. $\|a\| > 0$ if $a \neq 0$, and $\|0\| = 0$.
M2. If $\|a\| > \|b\|$, then $\|a+b\| = \|a\|$, if $\|a\| = \|b\| \neq 0$, then $\|a+b\| < \|a\|^*$.
M3. $\|ab\| = \|a\| \cdot \|b\|$.

Emphasizing

4. Derive from properties M1–M3 the following properties of a 2-adic module:

a) $\|a\| = \|a\|$, b) if $\|a\| \neq \|b\|$, then $\|a-b\| = \|a+b\|$.
5. Prove that if $\|1-x\| < 1$ and $\|1-y\| < 1$ then $\|1-xy\| < 1$.

Square problem

figure 1 shows a square divided into circular triangles. The squares on figure2 are divided into triangles of equal area. In each of these examples the number of triangles in the partition is even.

Task a. Prove that a square cannot be divided into an odd number of triangles of equal area.

Let us choose a coordinate system on the plane in such a way that the vertices $O, A, B$ and $C$ of a given square have coordinates $O(0; 0), A(1; 0)$,

$\cdot$ So anyway $\|a+b\| \leq \|a\| + \|b\|$.

$B(1; 1), C(0; 1)$. Suppose that the square is divided into $n$ triangles of equal area. Then the area of ​​each of the triangles in the partition is equal to $1/n$. If $n$ is odd, then $\|1/n\| = 1$, and if $n$ is even, then $\|1/n\| \geq 2$. Therefore, the parity of $n$ will be proven if we establish that $\|1/n\| \geq 2$.

Let's look at a special case. Let the vertices of the partition triangles be points with rational coordinates. In this case, each vertex $(x; y)$ can be colored green, red or blue according to the following rule: if $\|x\| < 1$ and $\|y\| < 1$, then the point is colored green; if $\|x\| \geq \|y\|$ and $\|x\| \geq 1$, then the point is colored red; if $\|x\| < \|y\|$ and $\|y\| \geq 1$, then the point is colored blue (see Fig. 3). We will assume that not only the vertices are colored, but all rational points of the plane.

Exercise 6. a) Prove that if $P$ is a green point, then when $\overrightarrow{PO}$ ($O$ is the origin) intersects in parallel, each colored point retains its color.

6) Prove that no line contains points of all three colors.

Let us assume that one of the triangles in the partition has all its vertices of different colors (it is proven in the appendix that such a triangle must exist). Let $K$ be the green vertex of this triangle.

With the parallel intersection of $\overrightarrow{KO}$ we again obtain, by exercise ba), a triangle with vertices of all three colors. Let us denote by $L_1(x_1, y_1)$ the red vertex of the resulting triangle, and by $L_2(x_2, y_2)$ its blue vertex (green

⟦folio 28⟧

the vertex of this triangle is the point $O$). Since the triangle $OL_1L_2$ is obtained by parallel translation of the partition triangle, its area is equal to $1/n$. On the other hand, the area of ​​triangle $OL_1L_2$ is $1/2|x_1y_2-x_2y_1|$. (Prove it yourself.)

Thus, we get the equality $1/n=1/2|x_1y_2-x_2y_1|$. Now it is not difficult to establish the inequality $\left\|\frac{1}{n}\right\| \geq 2$. Indeed, since $L_1$ is a red dot and $L_2$ is a blue dot, then $\|x_1\| \geq \|y_1\|$, $\|x_2\| < \|y_2\|$.

Variable these inequalities, we get $\|x_1\| \|y_2\| > \|x_2\| \|y_1\|$, and, therefore, by property $M3$ $\|x_1y_2\| > \|x_2y_1\|$. Due to property $M2$ and exercise 46) $\|x_1y_2\| = \|x_1y_2\|$. Also, $\|x_1\| \geq 1$, $\|y_2\| \geq 1$, so $\|1/n\| = 2\|x_1\| \|y_2\| \geq 2$.

In order to solve the problem in the general case, it is enough to prove that the 2-Adic model has an extension to the set of all real numbers, i.e., there is a function $x \rightarrow \|x\|$ defined on the set of all real numbers, which has the property $M1-M3$ and coincides with the 2-Adic model on the set of different numbers. Such a function of the real exists, but proof of its existence requires the use of more complex means by the city than those that we have in this article.

2-adic decomposition

As you know, any natural number can be represented as a sum of powers of 2. For example, $1000 = 2^3+2^5+2^6+2^7+2^8+2^9$. Using the 2-adic consideration, this expansion can be obtained as follows. First we look for the power of 2 that is the same distance from 0 as the number 1000. Find this power $(2^3)$, subtract it from the number 1000 to get the number 2, which is the same distance from 0. Then we look for the power of 2 that is the same distance from 0 as the number $960 = 992-2^5$, and so on.

⟦folio 29⟧

Using negative powers of 2, we can obtain similar expansions of rational numbers of the form $\frac{m}{2^k}$, where $m$, $k$ are natural numbers. For example,

$$\frac{1477}{256} = \frac{1 + 2^2 + 2^8 + 2^7 + 2^8 + 2^{10}}{2^8} = 2^{-8} + 2^{-6} + 2^{-2} + 2^{-1} + 2^0 + 2^2.$$

No other rational numbers can be represented as a sum of powers of two, but it turns out that such sums can approximate any rational number as accurately as desired. Indeed, let $a$ be a rational number and $\|a\| = \frac{1}{2^{k_1}}$. Therefore $a_1 = a - 2^{k_1}$. Then $a_1$ is closer to zero than $a$ (see exercise 1).

Pozny is either $a_1 = 0$ or $\|a_1\| = \frac{1}{2^{k_2}}$, where $k_2 > k_1$. Polya $a_2 = a_1 - 2^{k_2}$, we again get that either $a_2 = 0$ or $\|a_2\| = \frac{1}{2^{k_3}}$, where $k_3 > k_2$, and so on. Thus, either some number $a_s$ is equal to zero, and then $a$ is the sum of a power of two: $a = 2^{k_1} + 2^{k_2} + \dots + 2^{k_s}$, or all $a_s$ are different from zero, and then sums of the form $2^{k_1} + 2^{k_2} + \dots + 2^{k_s}$ approximate the number $a$ as accurately as desired. In this case, it is convenient to assume that $a$ is equal to the infinite sum $a = 2^{k_1} + 2^{k_2} + \dots + 2^{k_s} + \dots$.

Definition. Let $x_1, x_2, \dots, x_n$ be a sequence of rational numbers. We will say that the rational number $a$ is equal to the infinite sum $x_1 + x_2 + \dots + x_n + \dots$ if the 2-adic consideration between the number $a$ and the finite sums $S_n = x_1 + \dots + x_n$ tends to zero as $n$ tends to infinity, that is

$$\lim_{n \to \infty} \rho(a, S_n) = 0.$$

In practice, if $\|q\| < 1$, then the infinite sum $a + aq + aq^2 + \dots + aq^n + \dots$ is defined and equal to $\frac{a}{1 - q}$.

We have proven that every rational number can be represented either as a finite sum $2^{k_1} + 2^{k_2} + \dots + 2^{k_n}$ ($k_1 < k_2 < \dots < k_n$) or as an infinite sum $2^{k_1} + 2^{k_2} + \dots + 2^{k_n} + \dots$ ($k_i$ are integers, $k_1 < k_2 < \dots$). In both cases, this representation, which we will call the 2-Adic decomposition of the number $a$, can be written as $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots + \varepsilon_{k+n} 2^{k+n} + \dots$, where $k$ is an integer, and each of the numbers $\varepsilon_{k+1}, \varepsilon_{k+2}, \dots, \varepsilon_{k+n}, \dots$ is equal to 0 or 1, with $\varepsilon_k = 1$. The numbers $\varepsilon_k, \varepsilon_{k+1}, \dots$ are called the 2-adic digits of the number $\frac{p}{q}$. It is not difficult to prove that every rational number has one and only one 2-adic decomposition.

Practice 8. Prove that $-1 = 1 + 2 + 2^2 + 2^3 + \dots + 2^n + \dots$,

$$\frac{1}{6} = 2^{-1} + 1 + 2^2 + 2^4 + \dots + 2^{2n} + \dots$$

By virtue of Exercise 8, the 2-adic digits - 1 form the sequence 1, 1, 1, ..., and the 2-adic digits of the number $\frac{1}{6}$ form the sequence 1, 1, 0, 1, 0, 1, 0, 1, ... Both resulting sequences are periodic. It can be shown that for any rational number $\frac{p}{q}$ the sequence of 2-adic digits is periodic *).

To do this, consider the sequence of numbers $a_1, a_2, \dots, a_n, \dots$ defined by the equalities $\frac{p}{q} - \varepsilon_k 2^k = \frac{a_1}{q} 2^{k+1}, \frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) = \frac{a_2}{q} 2^{k+2}, \dots,$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

Now note that the 2-adic decomposition of the number $\frac{p}{q}$ can be obtained from the 2-adic decomposition of the number $\frac{a_n}{q}$ by multiplying each term by

*) In the same sense in which a periodine is a decimal fraction representing a rational number: a periodine starting from a certain place.

⟦folio 30⟧

the last expansion into $2^{k+n}$ and adding $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots + \varepsilon_{k+n-1} 2^{k+n-1}$ to the resulting sum.

Therefore, the periodicity of the sequence $\varepsilon_k, \varepsilon_{k+1}, \varepsilon_{k+2}, \dots$ will be established if we prove that in the sequence $a_1, a_2, \dots, a_n, \dots$ some number appears twice. In fact, the sequence $a_1, a_2, \dots, a_n, \dots$ is limited, and since its terms are integers, there will definitely be equal ones among them. The boundedness of this sequence is established by the following chain of inequalities:

$$|a_n| = \left| \frac{p}{2^{k+n}} \right| - \left( \frac{\varepsilon_k}{2^n} + \frac{\varepsilon_{k+1}}{2^{n-1}} + \dots \right)$$

$$\dots + \frac{\varepsilon_k}{2^{n-1}} + \dots + \frac{1}{2} \left| q \right| \leqslant \left| \frac{p}{2^{k+n}} \right| + \left( \frac{1}{2^n} + \frac{1}{2^{n-1}} + \dots + \frac{1}{2} \right) \left| q \right| \leqslant \left| \frac{p}{2^{k+n}} \right| + \left| q \right|.$$

U Pravanice 9. Using the result of Exercise 7, prove that if $\varepsilon_k, \varepsilon_{k+1}, \varepsilon_{k+2}, \dots$ is a periodic sequence of the digits 0 and 1, then the infinite sum $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \varepsilon_{k+2} 2^{k+2} + \dots$ is a 2-adic decomposition of some rational number.

2-adic numbers

In addition to periodic expansions that define rational numbers, we can also consider non-derivative expansions, considering that they define some new numbers. These numbers, together with the rational ones, form the set $Q_2$, whose elements are called 2-adic numbers.

Elements from $Q_2$ can be added in pairs and a variable. Here's how it's done. Let $\alpha = \varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots$ Let us write $\alpha$ like an infinite fraction: $\alpha = \varepsilon_k \dots \varepsilon_0, \varepsilon_1 \varepsilon_2 \dots$.

If there are two numbers from $Q_2$ written in this way, then their sum (production) should be calculated in the same way as the sum (production) of two infinite fractions, but with transfers from left to right. (For examples, see figure 4.) We cannot dwell on this in more detail and invite the reader to check for himself that the sum and product of elements from $Q_2$ again gives an element from $Q_2$ and that these operations have properties common to multiplication and addition: they satisfy the commutative, combinational and distributive laws.

2-adic model and extend to $Q_2$:

$$\sum_{n \to \infty} x_n = 0, \text{ мо существуют}$$

$$\lim_{n \to \infty} \sum_{k=1}^{n} x_k = 0.$$

Pravanica has 13. Prove sufficient condition $\lim_{n \to \infty} \sum_{k=1}^{n} x_k = 0.$

14. Prove that the sum $1 \cdot 1! + 2 \cdot 2! + \dots + n \cdot n! + \dots$ is defined and find its value.

15. Prove that if $x \in Q_2$ and $\|x\| \leqslant \frac{1}{2}$, then the sum $\frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n} + \dots$ is defined.

2-adic logarithm

In conclusion, we will give a more natural form of solution to problem No. 434*.

To do this, consider the function $L(x) = \frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n} + \dots$ defined on the set of 2-adic numbers $x$ whose modulus is at most $\frac{1}{2}$ (see)

*) For the conditions of this problem, see «Kvant» No. 12 for 1977.

⟦folio 31⟧

To solve problem M434b it is enough to prove that $L(2)=0$. Let's introduce another function using the formula $\log x=-L(1-x)$. The equality $L(2)=0$ means that $\log(-1)=0$. The log function (called the 2-adicek logarithm) has the basic property of logarithms: $\log(xy)=\log x+\log y$. From this property it is easy to derive the equality $\log(-1)=0$. Indeed, $\log 1=\log(1\times 1)=\log 1+\log 1=2\log 1$, whence $\log 1=0$. On the other hand, $\log 1=(\log(-1)\times(-1))=\log(-1)+\log(-1)=2\log(-1)$ and therefore $\log(-1)=0$. The 2-adicec logarithm in the set of 2-adicec numbers plays the same role as the ordinary logarithm in the set of real numbers. The 2-adicec logarithm determines for those numbers $x$ for which $\|x\|=1$, since it is in this case that $\|1-x\| \leqslant \frac{1}{2}$. (In particular, we define $\log(-1)$.) The equality on which the solution of problem M434 in «Kvant» is based takes the form $L(2x-x^2)-2L(x)=0$ in the limit as $n$ tends to infinity. This equality is also a consequence of the basic property of the logarithm. Indeed, $L(2x-x^2)=-\log(1-x)^2=-2\log(1-x)=2L(x)$.

You can get acquainted with the proof of the main property of the 2-adicec logarithm and a number of other properties of 2-adicec numbers in the book 3. I. Borevich and I. R. Shafarvich “Number Theory”. In addition to the logarithm, there are other wonderful functions of a 2-adice variable. However, one of these functions is exponential - a function defined by the equality

$$\exp x=1+x+\frac{x^2}{2}+\dots+\frac{x^n}{n!}+\dots$$

U pravanke 16. Prove that exponential is defined on the set of 2-adicetic numbers $x$ satisfying conditions similar to the exponential property: $\exp(x+y)=\exp x\cdot\exp y$, $\exp(\log x)=x$, $\log(\exp x)=x$. (These equalities are valid for the values ​​of the variables for which they are defined.)

Just as the 2-adiceco consideration was defined, using an arbitrary prime $p$ one can define a $p$-adicece consideration. It turns out that all considerations between different numbers are equivalent to either the general or one of the $p$-Adicek considerations. But this is a topic for another story.

Application

All we have to do is prove the existence of a triangle with vertices of all three colors. Let us formulate and prove a more general statement:

Let the square OABC be divided into several triangles. Let us assume that the middle triangles are divided into one that has vertices of all three colors, i.e., in each triangle that is divided there are two vertices of the same color. Since each link located on the contour of the square OABC lies on the side of one dividing triangle, and each link located on the side of two dividing triangles, then from the fact that each dividing triangle has two vertices of the same color, it follows that there is an even number of links of type 3K on the contour of the square. On the other hand, on the segment OC and BC there are no such links, on the segment OA there is an even number of links. A contradiction has been obtained.
