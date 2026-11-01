---
id: 1985-2-pontryagin-obobschenie-chisel-3a0cce19
issue: kvant_1985_2
year: 1985
number: "2"
title: Generalization of numbers
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 8
page_last: 13
page_labels: 6, 7, 8, 9, 11
tag: JGQZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: b17254a263a73d1776d95e255fdc3e5d73210bfafb0b0835c4d1fafeffb30c0a
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/05_pontryagin-obobschenie-chisel-3a0cce19.md
source_content_sha256: 9b7894db3ff51413320c72421304a9f2156150a189f3741d2387be200a4fdd56
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

Generalization of numbers

Academician L. S. PONTRYAGIN

This article discusses the development of the concept of number - from counting objects in ancient times to the creation of real numbers, complex numbers and quadrions. In the second part of the article (in the next issue «Kvant»), based on modern elementary properties of numbers, vectors and polynomials, it will be explained why further generalization of the concept of number is impossible.

As new practical applications of numbers emerged and the concept of number evolved as a result of developments in theoretical mathematics, new numbers appeared. The first practical use of numbers was counting objects. For this purpose, positive integers were used, which are commonly called natural numbers. When changing the length and when making trade calculations, we had to divide the integers by each other. Moreover, the result of division was not always an integer. Therefore, the need arose for fractional or, what is the same, rational numbers. In order to make subtracting a rational number from another rational number always possible, negative rational numbers had to be introduced. Thus a stock, or set, of all rational numbers was formed.

Even in ancient times, long before the appearance of negative numbers, which began to be considered in the middle of our millennium, it was established that the ratio of the lengths of the diagonal of a square to the length of its side is not a rational number. It became necessary to introduce new numbers, which are called irrational. Thus arose the stock, or set, of all real numbers.

§1. Complex numbers

As algebra developed, mathematicians began to consider square roots of negative numbers. Square roots of negative numbers were encountered during calculations, the results of which turned out to be training real numbers. Thus, the need arose to add new numbers - square roots of negative numbers. In fact, it is enough to add only one “new” number, the so-called minimum unit i, which is determined by the condition

$$i^2 = -1.$$

This new number i was added to the set of all real numbers. With the numbers that arose in this way, all sorts of algebraic calculations had to be done, so we had to consider a polynomial for i. Taking into account condition (1), a polynomial of any degree with respect to

⟦folio 7⟧

but $i$ turns into a polynomial of the first degree, that is, written in the form $z=x+iy=x+yi$, (2)

where $x$ and $y$ were ordinary real numbers. Numbers of the form (2) were called complex numbers. The operations of addition and multiplication of complex numbers were defined as operations on polynomials with respect to $i$, taking into account condition (1) as follows. If $z_1=x_1+y_1i; z_2=x_2+y_2i$ (3) are two complex numbers, then their sum is determined by the formula

$$z_1+z_2=(x_1+y_1i)+(x_2+y_2i)=\left(x_1+x_2\right)+\left(y_1+y_2\right)i.$$ (4)

A special role among all complex numbers is played by the number zero, defined by the formula

$$0=0+0i.$$ (5)

It has the remarkable property that

$$0+z=z+0=z.$$ (6)

Each complex number corresponds to its opposite number $-z$, determined by the condition

$$z+(-z)=0.$$ (7)

The existence of an opposite number provides the possibility of subtraction. Exactly

$$z_1-z_2=z_1+(-z_2).$$ (8)

The product of the numbers $z_1$ and $z_2$ as polynomials in $i$, taking into account correspondence (1), gives the following result:

$$z_1z_2=(x_1+y_1i)(x_2+y_2i)=x_1x_2+x_1y_2i+\left(y_1x_2+y_1y_2\right)^2=x_1x_2-y_1y_2+\left(x_1y_2+x_2y_1\right)i.$$ (9)

Among all complex numbers for multiplication, the unit, defined by the formula, plays a special role

$$1=1+0i.$$ (10)

It has the following properties:

$$1z=z1=z.$$ (11)

In order to divide the complex number $z_1$ by the complex number $z_2$, it is enough to determine the quantities $1/z_2=z_2^{-1}$. The number $z_2^{-1}$ is called the reciprocal of the number $z_2$. For a complex number $z=x+yi$ the reciprocal is given by

$$z^{-1}=\frac{x}{x^2+y^2}-\frac{y}{x^2+y^2}i.$$ (12)

From this formula it is clear that the number $z^{-1}$ always exists when $z \neq 0.$

It is easy to check that if the number $z^{-1}$ is defined by formula (12), then we have

$$z \cdot z^{-1}=z^{-1}z=1.$$ (13)

Now the division of the complex number $z_1$ by the complex number $z_2 \neq 0$ is determined by the formula

$$z_1/z_2=z_1\left(z_2^{-1}\right).$$ (14)

Thus, a stock or set of two complex numbers arose, among which the set of all real numbers is contained. Namely, these are complex numbers of the form

$$z=x+0i.$$ (15)

In fact, when adding and multiplying two complex numbers of the form (15) $z_1=x_1+0i, z_2=x_2+0i$ according to formulas (4) and (9), respectively, we obtain (check!) $z_1+z_2=(x_1+x_2)+0i$ and $z_1z_2=x_1x_2+0i$, that is, simply viewing the addition and multiplication of real numbers $x_1$ and $x_2$. Thus, the complex does not need the number $z=x+0i$ and the real number $x$, we can consider the real numbers to be part of the complex. Therefore, polynomials of complex numbers are called extensions of polynomials of real numbers.

Exercise
1. Find $a^2, a+b^2, ab^{-1}$ if $a=2+3i, b=5-i$.
2. Solve the equations $az+b=0, az^2=b$ if $a=3+i, b=2-3i$.

§ 2. Fundamental theorem of algebra

In order to obtain all the complexes of a number, we started by adding to the real numbers only one number $i$, which is the root of the algebraic equation

$$z^2+1=0.$$ (16)

However, it turns out that we have thereby arrived at a stock of numbers for which any algebraic equation already has at least one root. This is the fundamental theorem of algebra, proven by the great German mathematician K. F. Gauss at the turn of the 18th and 19th centuries. Let us formulate this theorem more precisely.

Let

$$f(z)=a_0z^n+a_1z^{n-1}+\dots+a_{n-1}z+a_m,$$ (17)

where $a_0 \neq 0$ is an arbitrary polynomial of degree $n \geq 1$ with respect to $z$ with real coefficients. Then

⟦folio 8⟧

Carl Friedrich Gauss (1777–1855), great German mathematician, as well as astronomer, physicist and surveyor. Gauss's outstanding mathematical ability was evident in early childhood. By the time he submitted his doctoral dissertation, at age 22, he was the author of many striking discoveries, including the first rigorous proof of the fundamental theorem of algebra. He treated this theorem with particular passion, and subsequently found no less than six other proofs of it! It is difficult to name a branch of theoretical and applied mathematics in which Gauss did not make a significant contribution. Of the issues raised in this article, we note another one invented from the geometric interpretation of complex numbers, as a result of which the last possibilities against the use of complex numbers in mathematics disappeared.

$f(z)$ has at least one root, that is, there is a complex number $a$ such that

$$f(a) = a_0 a^n + a_1 a^{n-1} + \dots + a_{n-1} a + a_n = 0.$$

(18)

This theorem was proved by Gauss for real coefficients $a_0, a_1, \dots, a_n$. This theorem was subsequently proven for the case when the coefficients of the polynomial $f(z)$ are complex numbers.

Note that for complex numbers, multiplication is commutative, that is, multipliers can be swapped:

$$z_1 z_2 = z_2 z_1.$$

(19)

After complex numbers have been constructed and studied, whether or not further generalizations have arisen. Is it possible to construct quantities with several minimal units, $i_1, i_2, \dots, i_k$, that is, a set of quantities - “generalized numbers” - of the form

$$x = x_0 + x_1 i_1 + x_2 i_2 + \dots + x_k i_k,$$

(20)

where $x_0, x_1, \dots, x_k$ are real numbers, and for these quantities determine addition and multiplication, which have general properties of addition and multiplication of numbers. It turns out that such quantities can be constructed with third units $i_1, i_2, \dots, i_k$. They are called quaternions. For them, the general properties of addition and multiplication of numbers are fulfilled, except for the law of commutativity of multiplication (see (19)). At the end of the century, the outstanding German mathematician F. G. Frobenius proved that further along this path was no longer possible. The proof of this Frobenius theorem, which forms the main content of this article, will be presented in the next issue.

To prove Frobenius's theorem, I will have to use some results from algebra, not included in the above-mentioned high school curriculum, concerning the division and factorization of polynomials.

§ 3. Division of polynomials

When dividing the positive integer $a$ by the positive integer $b$, we arrive at the equality

$$a = bh + k,$$

(21)

where $h$ and $k$ are non-negative integers, $k < b$. The number $h$ is called the quotient, and $k$ is the remainder when dividing the number $a$ by the number $b$.

The method of dividing numbers is well known from arguments. But just like integers, polynomials can be divided by each other. We will start from two polynomials:

$$a(z) = a_0 z^p + a_1 z^{p-1} + \dots + a_p,$$

$$b(z) = b_0 z^q + b_1 z^{q-1} + \dots + b_q.$$

(22)

We will assume here that the numbers $a_0$ and $b_0$ are not equal to zero, so that the polynomial $a(z)$ has degree $p$ and the polynomial $b(z)$ has degree $q$. As a result of dividing the polynomial $a(z)$ by the polynomial $b(z)$ we arrive at the following result, similar to the equality

⟦folio 9⟧

in (21):

$$a(z) \equiv b(z) h(z) + k(z),$$

where the degree of the polynomial $k(z)$ is less than $q$. The polynomials $h(z)$ and $k(z)$ are called respectively the quotient and remainder when dividing the polynomial $a(z)$ by the polynomial $b(z)$.

If $k(z)$ is identically zero, then saying that the polynomial $a(z)$ is divisible by the polynomial $b(z)$, and $h(z)$ is the quotient of their division.

Equality (21) has been proven in arithmetic, and identity (23) must be proven in algebra. But dividing polynomials is not included in the current school curriculum. To prove (23), we must construct polynomials $h(z)$ and $k(z)$ that satisfy this identity. The process of this construction is a very important algorithm. This algorithm is very similar to the usual corner division algorithm. Therefore, before analyzing it in general terms, I advise you to look at a practical example of dividing two polynomials, shown in figure 1.

Let us now describe the algorithm for dividing a polynomial $a(z)$ of degree $p$ by a polynomial $b(z)$ of degree $q$ in the general case. If $p < q$, then $h(z) \equiv 0$, $k(z) \equiv a(z)$ and identity (23) is satisfied.

Now we can construct the polynomials $h(z)$ and $k(z)$ under the assumption that $p \geq q$. First we construct the identity

$$a(z) \equiv b(z) h_1(z) + a_1(z),$$

in which the degree of the polynomial $a_1(z)$ is less than $p$. To do this, let's put

$$h_1(z) = \frac{a_0}{b_0} z^{p-q}.$$

Then the difference

$$a(z) - b(z) h_1(z) \equiv a_1(z)$$

has a degree less than $p$, since in this polynomial the coefficient of $z^p$ is zero. The remaining powers $z$ included in this polynomial are very less than $p$. Thus, identity (24) is constructed.

If the polynomial $a_1(z)$ has a degree less than $q$, then identity (24) is already identity (23). Otherwise, we apply to the polynomial $a_1(z)$ the same procedure that was applied to the polynomial $a(z)$ when constructing identity (24). Then we get for it the identity

$$a_1(z) \equiv b(z) h_2(z) + a_2(z),$$

and the degree of the polynomial $a_2(z)$ is already less than the degree of the polynomial $a_1(z)$. If the polynomial $a_2(z)$ already has a degree less than $q$, then, substituting $a_1(z)$ from the last identity into identity (24), we obtain the identity

$$a(z) \equiv b(z)(h_1(z) + h_2(z)) + a_2(z),$$

which is already identity (23). If the polynomial $a_2(z)$ also has a degree greater than $q$, then we will continue our

We will construct further and finally prove the required identity (23).

Here we described the process of dividing the polynomial $a(z)$ by the polynomial $b(z)$, that is, finding the polynomials $h(z)$ and $k(z)$ included in identity (23). Let us now prove that these polynomials are uniquely determined by the polynomials $a(z)$ and $b(z)$. Let us assume that if we violate identity (23), we have the identity

$$a(z) \equiv b(z) h_0(z) + k_0(z),$$

and the degree of the polynomial $k_0(z)$ is less than $q$. Subtracting identity (25) from (23), we obtain

$$b(z)(h(z) - h_0(z)) = k_0(z) - k(z).$$

Since the degree of the polynomial $b(z)$ is equal to $q$, and the degree of the polynomial $k_0(z) - k(z)$ is less than $q$, the latter identity can only hold under the condition $h(z) - h_0(z) \equiv 0$, so that $k_0(z) - k(z) \equiv 0$.

Let us note in conclusion that in the process of dividing the polynomial $a(z)$ by the polynomial $b(z)$, complex numbers cannot appear, so if the polynomials $a(z)$ and $b(z)$ have real coefficients, then the polynomials $h(z)$ and $k(z)$, included in identity (23), also have real coefficients.

Practice 3. Divide the polynomial $x^8 + 2x^5 + 2x^4 + x^2 + 2x$ by the polynomial $x^3 + 1$.

§ 4. Decomposition of polynomials into irreducible multipliers

Let

$$f_0(z) = z^n + a_1z^{n-1} + \dots + a_n$$

is a polynomial of arbitrary positive degree $n$ with arbitrary real or complex coefficients. As noted earlier, this polynomial has at least one complex root $a$. Let us now prove that if $f_0(z)$ has an asoid root, that is

$$f_0(a) = 0,$$

then the polynomial $f_0(z)$ is divisible by the bivariate $z - a$, so the equality holds

$$f_0(z) \equiv (z - a)f_1(z),$$

where obviously $f_1(z)$ has degree $n-1$.

⟦folio 11⟧

Fig. 2.

is an irreducible polynomial of the first or second degree with real coefficients, so that the quotient $f_2(z)$ of the division of new ones is a polynomial with real coefficients. This means that the polynomial $f_0(z)$ decomposes into real irreducible polynomials of degree 1 or 2.

An important conclusion follows from this:

An arbitrary root a of the polynomial $f_0(z)$ is the root of an irreducible polynomial of the first or second degree.

Exercise 4. Decompose the polynomial $2x^4 - 3x^3 + 2x^2 - 8x$ into irreducible polynomials 1 and 2.

§ 5. Quaternions

As mentioned, quaternions have three minimum units. These units are usually denoted by $i, j, k$.

(37) Thus, each quaternion is written in the form

$$x = x_0 + x_1 i + x_2 j + x_3 k,$$

(38) where $x_0, x_1, x_2, x_3$ are real numbers called coordinates of the quaternion $x$.

Let

$$y = y_0 + y_1 i + y_2 j + y_3 k$$

- second quaternion. Quaternions $x$ and $y$ are considered equal if and only if their coordinates are equal, that is, when equality holds

$$x_0 = y_0, x_1 = y_1, x_2 = y_2, x_3 = y_3.$$

(40) The addition of quaternions $x$ and $y$ is performed according to the rules

$$x + y = x_0 + y_0 + (x_1 + y_1) i + (x_2 + y_2) j + (x_3 + y_3) k.$$

(41) We can say that quaternions are added coordinatewise, that is, in the same way as vectors of a 3-dimensional vector space are added by adding their coordinates. (Only the quaternion has not three, but four coordinates.) In this sense, quaternions can be considered as vectors of “four-dimensional space”. It is, of course, difficult to imagine four-dimensional space. This is where analysis with 3D space (Fig. 2) can help you.

When multiplying quaternions, real numbers can be rearranged with units $i, j, k$. Therefore, to set the rules for multiplying quaternions, you should set the rules for multiplying units (37). It follows:

$$i^2 = j^2 = k^2 = -1;$$

(42)

$$ij = -ji = k; \quad jk = -kj = i; \quad ki = -ik = j.$$

(43)

In general form, the formulas for addition and multiplication of quaternions can be found in «Kvant», 1983, No. 9, p. 13. In order to define a quaternion inverse to the quaternion $x$, we introduce the concept of the conjugate quaternion $\bar{x}$. We will define it by the formula

$$\bar{x} = x_0 - x_1 i - x_2 j - x_3 k.$$

(44)

Simple calculations give

$$x\bar{x} = x_0^2 + x_1^2 + x_2^2 + x_3^2 = |x|^2.$$

(45)

The quaternion $x^{-1}$, the inverse of $x$, is given by

$$x^{-1} = \frac{\bar{x}}{|x|^2}.$$

(46)

For it there is a correspondence $x^{-1}x = xx^{-1} = 1$.
