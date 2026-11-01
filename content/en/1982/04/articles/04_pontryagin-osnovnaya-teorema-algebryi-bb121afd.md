---
id: 1982-4-pontryagin-osnovnaya-teorema-algebryi-bb121afd
issue: kvant_1982_4
year: 1982
number: "4"
title: Fundamental theorem of algebra
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 6
page_last: 11
page_labels: 4-9
tag: AG6B
lang: en
source: kvant_digital
extraction: vision
content_sha256: ba817f1ccadca6d93d4b8fff47a989411c44cf6f3265a2c37cc44b9c82f1b4c2
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/04_pontryagin-osnovnaya-teorema-algebryi-bb121afd.md
source_content_sha256: a680041c105f3f03f55028c0c59c3e548fa06c69a2eee25011ad896dbd0597e4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

movement, and not the line that the moving point describes. However, the same line can be described in different ways.

In the process of motion, the point $z(t)$ at different moments of time can fall into the same point of the plane, so the equality is not excluded

$$z(t_2) = z(t_3)$$ at $t_2 \neq t_3$.

Thus, let may have self-intersections. It may even consist of one point, precisely in the case when the point $z(t)$ does not move at all when $t$ changes.

In what follows, unless this is specifically stated, we will always assume that let does not pass through the origin of coordinates, that is, that the quantity $z(t)$ does not vanish for any value $t$.

The point $z(t_0) = z_0$ is called the beginning of the path, and the point $z(t_1) = z_1$ is its end.

If the equality $z_0 = z_1$ holds, then let it be called closed (Fig. 2).

Since the complex number $z(t)$ does not vanish, for any value $t$ the argument $\varphi(t)$ is defined as the complex number $z(t)$; but it is defined only up to the term $2k\pi$. This ambiguity is not desirable for us. In order to get rid of it, we will choose a well-defined argument $\varphi_0 = \varphi(t_0)$ for the starting point $z_0$.

Then, as $t$ increases, we will choose the argument $\varphi(t)$ of point $z(t)$ so that with small changes $t$ it changes little. This argument selection ambiguity will be removed. Adding the number $2k\pi$ to the argument at $k \neq 0$ would immediately lead to a sharp change in the value $\varphi(t)$. By choosing the initial value of the argument $\varphi(t_0) = \varphi_0$ and ensuring that the argument $\varphi(t)$ of the point $z(t)$ changes along with $t$ continuously, we obtain a well-defined function $\varphi(t)$, changing continuously, that is, without jumps. If you choose the initial value of the argument $\varphi_0$ differently, changing it to $2k\pi$, then it will differ from the previously selected one by exactly $2k\pi$ throughout the change $t$. It follows that with this method of constructing the function $\varphi(t)$ the value

$$\varphi(t_1) - \varphi(t_0)$$

does not depend on the randomly chosen initial value of the argument of the number $z_0$.

If let be closed, then the points $z_0$ and $z_1$ coincide and, therefore, their arguments $\varphi(t_0)$ and $\varphi(t_1)$ can differ only by $2k\pi$. Therefore, number (1) in the case of a closed path is $2k\pi$. The integer $k$ is called the index of a closed path in the plane of the complex primeval $z$. It should be emphasized once again that the index of a closed path can be determined only if it does not pass through the origin of coordinates.

The index $k$ has a simple geometric meaning. Namely, it indicates how many times the point $z(t)$, describing a closed path, goes around the origin of coordinates (Fig. 3).

Let's look at a simple example. Let $1 + r(\cos t + i \sin t); 0 \leq t \leq 2\pi$ be closed. It describes a circle with center at point 1 and radius $r$ and passes the circle

⟦folio 5⟧

over time $t$ uniformly counterclockwise. If the number $r$ is less than 1, then the circle does not contain the origin and the path index is 0. If $r > 1$, then the circle contains the origin and the path index is 1 (check this yourself). In the case of $r = 1$, let it pass through the origin and its index is not defined. If the number $r$ is less than 2, as stated, the deformation of a closed path does not change its index, unless at some point the deformation passes through the origin.

By saying that let it be described by the movement of a point in time, we only wanted to make the definition of a path more intuitive. In reality, we are talking about the dependence of the complex variable $z$ on some action parameter $t$ (which can be denoted by another letter). So, for example, let (2) be written in the form $1 + r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi,$ (3) where the parameter is no longer $t$, but $\alpha$. It is clear that let (3) be described by the point $1 + z$, when the point $z$ describes let

$$r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi.$$

Here $r$ is a numerical parameter on which let itself depends. Saying that when $r$ changes, let (3) be deformed.

Let us introduce the concept of path deformation. Let us assume that let the deformation, if it gradually changes

$$r( \cos \alpha + i \sin \alpha ); 0 \leqslant \alpha \leqslant 2\pi.$$

Fig. 4.

Path deformation 1+r(cosα+i sinα) with changing $r$

Fig. 5.

⟦folio 6⟧

to 2π, the point argument $z^n$ changes from 0 to $2n\pi$. Thus, the index of path (5) is $n$ (see Fig. 6, which shows the case $n=3$ schematically).

Complex functions of a complex variable

If the numerical value of a complex variable $w$ can be found by knowing the numerical value of another complex variable $z$, then the variable $w$ is called a function of the variable $z$, which is written in the form

$$w = f(z).$$

If the complex function $f(z)$ of a complex variable $z$ is arbitrary, then it is called an analytic function. The theory of analytic functions is now one of the most important branches of mathematics. Here we will be interested only in analytical functions of a very particular type, namely polynomials.

Consider the polynomial

$$w = f(z) = z^n + a_1 z^{(n-1)} + \dots + a_{(n-1)} z + a_n,$$

where $a_1, a_2, \dots, a_n$ are complex coefficients and $n$ is a non-negative integer called the degree of the polynomial. The goal of our research will be to prove that the polynomial (6) of positive degree has a root, that is, that the equation

$$f(z) = 0,$$

where $f(z)$ is the polynomial (6) and $n > 0$ has a solution. To prove this we consider a closed path

$$f(r(\cos \alpha + i \sin \alpha)); 0 \leqslant \alpha \leqslant 2\pi,$$

which point $f(z)$ describes when point $z$ describes a closed path

$$r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi.$$

The case when the free term $a_n$ of the polynomial $f(z)$ is equal to 0 does not require consideration, since in this case the polynomial $f(z)$ has a very strong root $z = 0$. Therefore we will assume that $a_n \neq 0$. The closed path (7) depends on the parameter $r$ and when the parameter $r$ changes, it becomes deformed. At $r = 0$, the number $z$ is 0, and the path $f(z)$ consists of the fixed point $a_n$. Thus, its index at $r = 0$ is 0. We will prove that if we take $r$ large enough, then the index of path (7) is $n$. But according to the assumption $n \neq 0$, therefore, when the numbers $r$ change from a large value to zero, path (7) is deformed, passing through the origin of coordinates at some value $r$, and this means that at some value $z$ the function $f(z)$ will vanish, that is, the root of this polynomial exists (Fig. 7).

To prove that for a sufficiently large $r$ the closed path (7) has an index equal to $n$, we continue this path into a simpler one, the index of which is easy to calculate.

First of all, we will decompose the polynomial $f$ into the sum of two

$$f(z) = z^n + g(z),$$

where $g(z)$ is given by

$$g(z) = a_1 z^{n-1} + a_2 z^{n-2} + \dots + a_{n-1} z + a_n.$$

The polynomial $g(z)$ are well-defined numbers, then they all do not exceed in modulo some constant $C$. From inequality (8) proven in the previous article (see «Kvant», 1982, No. 3), extended to an arbitrary number of terms, it follows that for $|z| > 1$

$$|g(z)| \leqslant nC|z^{n-1}|.$$

Consider the polynomial $f(z, s)$, depending on the parameter $s$, $0 \leqslant s \leqslant 1$, given by the following formula:

$$f(z, s) = z^n + sg(z).$$

We have equality

$$z^n = f(z, s) - sg(z),$$

where

$$|z^n| \leqslant |f(z, s)| + |-sg(z)| \leqslant |f(z, s)| + nC|z^{n-1}| \leqslant |f(z, s)| + nC|z^{n-1}|,$$

⟦folio 7⟧

Fig. 7.

(see (8)). It follows
$$|f(z, s)| \geq |z^n| - nC |z^{n-1}|.$$

Let us denote $|z|$ by $r$, then the last inequality takes the form
$$|f(z, s)| \geq r^n - nCr^{n-1} = r^{n-1}(r - Cn).$$

Thus, at $r > Cn$ the right part of the previous inequality is positive. Therefore, the model of the function $f(z, s)$ does not vanish for any value of $S$ unless $0 \leq s \leq 1$.

Let us now pay attention to the fact that at $s = 0$ the polynomial $f(z, s)$ turns into the polynomial $z^n$ known to us. And the path index $z^n$, when $z$ describes the circle $r(\cos \alpha + i \sin \alpha)$, has already been calculated by us (see (5)). It is equal to $n$. At $s = 1$ the polynomial $f(z, s)$ turns into a polynomial $f(z)$ and the path (7) determined by it has an index also equal to $n$. So, we have proven that the path index (7), determined by the polynomial $f(z)$, at $r > Cn$ is equal to $n$. From this, as stated above, it already follows that the polynomial $f(z)$ vanishes at some value $z$, where $|z| < Cn$.

So, the main theorem of algebra is proven.

Division of polynomials

When dividing the positive integer $a$ by the positive integer $b$ we arrive at the equality
$$a = bh + k,$$
where $h$ and $k$ are non-negative integers and $k < b$. The number $h$ is called the quotient, and $k$ is the remainder when dividing the number $a$ by the number $b$.

A good method of dividing numbers from arithmetic. But just like integers, polynomials can also be divided by each other. We will start from two polynomials
$$a(z) = a_0 z^p + a_1 z^{p-1} + \dots + a_p,$$
$$b(z) = b_0 z^q + b_1 z^{q-1} + \dots + b_q.$$

We will assume here that the numbers $a_0$ and $b_0$ are not equal to zero, so that the polynomial $a(z)$ has degree $p$ and the polynomial $b(z)$ has degree $q$. As a result of dividing the polynomial $a(z)$ by the polynomial $b(z)$ we can arrive at the following equality, similar to equality (9):
$$a(z) = b(z)h(z) + k(z),$$
(10)

where the degree of the polynomial $k(z)$ is less than $q$. The polynomials $h(z)$ and $k(z)$ are called, respectively, the quotient and remainder when dividing the polynomial $a(z)$ by the polynomial $b(z)$.

If $k(z) = 0$, then the polynomial $a(z)$ is said to be divisible by the polynomial $b(z)$, and $h(z)$ is the quotient of their division.

Equality (9) is proven in arithmetic, and equality (10) must be proven in algebra. But dividing polynomials is not included in the current school curriculum. To prove (10), we must construct polynomials $h(z)$ and $k(z)$ that satisfy this equality. The process of this construction is a very important algorithm. Let's describe it.

If $p < q$, then $h(z) = 0$, $k(z) = a(z)$, and equality (10) is satisfied.

We will now construct the polynomials $h(z)$ and $k(z)$ under the assumption that $p \geq q$. First we construct the equality
$$a(z) = b(z)h_1(z) + a_1(z),$$
(11)
in which to construct the polynomial $a_1(z)$ less than $p$. To do this, let's put
$$h_1(z) = \frac{a_0}{b_0}z^{(p-q)}.$$

Then the difference
$$a(z) - b(z)h_1(z) = a_1(z)$$
has a degree less than $p$, since in this polynomial the coefficient of $z^p$ is zero, and the remaining degrees $z$ included in this polynomial are very less than $p$. Thus, equality (11) is constructed.

⟦folio 8⟧

If the polynomial $a_1(z)$ has a degree less than $q$, then equality (11) is already equality (10). In the opposite case, we apply to the polynomial $a_1(z)$ the same procedure that was applied to the polynomial $a(z)$ when constructing equality (11). And then we get equality for it

$$a_1(z) = b(z)h_2(z) + a_2(z),$$

and the degree of the polynomial $a_2(z)$ is already less than the degree of the polynomial $a_1(z)$. If the polynomial $a_2(z)$ already has a degree less than $q$, then substituting $a_1(z)$ from the last equality into equality (11), we get

$$a(z) = b(z)(h_1(z) + h_2(z)) + a_2(z),$$

which is already equality (10). If the polynomial $a_2(z)$ also has a degree greater than $q$, then we will continue our construction further, and in the end we will prove the desired equality (10).

Here we described the process of dividing the polynomial $a(z)$ by the polynomial $b(z)$, that is, finding the polynomials $h(z)$ and $k(z)$ included in equality (10). Let us now prove that they are uniquely determined by the polynomials $a(z)$ and $b(z)$. Let us assume that if we violate equality (10), we have the equality

$$a(z) = b(z)h_0(z) + k_0(z),$$

and the degree of the polynomial $k_0(z)$ is less than $q$. Subtracting equality (12) from equality (10), we obtain

$$b(z)(h(z) - h_0(z)) = k_0(z) - k(z).$$

Since the degree of the polynomial $b(z)$ is equal to $q$, and the degree of the polynomial $k_0(z) - k(z)$ is less than $q$, the last equality can only hold under the condition $h(z) - h_0(z) = 0$, so that $k(z) - k_0(z) = 0$.

Polynomials with arbitrary complex coefficients

Now, according to the fundamental theorem of algebra, the root of the polynomial $f(z)$ with complex coefficients will be denoted by $z_1$. Let us prove that the polynomial $f(z)$ is divisible by the bivariate $(z - z_1)$. By dividing the polynomial $f(z)$ by the first degree polynomial $(z - z_1)$ according to the rules described in the previous section, we obtain a quotient, which we denote by $f_1(z)$, and some remainder in the form of a polynomial of degree zero, that is, a number that we denote by $k$. Thus we have

$$f(z) = f_1(z)(z - z_1) + k.$$

Since $f(z_1) = 0$, then putting $z = z_1$ in the previous equality, we obtain $k = 0$.

So the polynomial $f(z)$ is divided by $(z - z_1)$ and we have

$$f(z) = (z - z_1)f_1(z),$$

where $f_1(z)$ is a polynomial of degree $n-1$, which obviously starts with the term $z^{n-1}$. If $n > 1$, then $n-1 > 0$; then the polynomial $f_1(z)$ will be of positive degree and, according to what was proven earlier, has some root $z_2$. Thus, by what has just been proven, the polynomial $f_1(z)$ is divided into the polynomial

$$f_1(z) = (z - z_2)f_2(z).$$

(13)

Continuing this process further, we obtain the decomposition of $f(z)$ into $n$ linear polynomials

$$f(z) = (z - z_1)(z - z_2) \dots (z - z_n).$$

The numbers $z_1, z_2, \dots, z_n$ are the roots of the polynomial $f(z)$, and the polynomial $f(z)$ obviously has no other roots. It may, however, turn out that the same root appears several times in this expansion. Grouping roots equal to each other, we obtain the decomposition

$$f(z) = (z - z_1)^{k_1}(z - z_2)^{k_2} \dots (z - z_q)^{k_q},$$

where all roots $z_1, z_2, \dots, z_q$ are distinct. The number $k_1$ is called the multiplicity of the root $z_1$, the number $k_2$ is the multiplicity of the root $z_2$, and so on, the number $k_q$ is the multiplicity of the root $z_q$. Thus, the number of different roots of the polynomial $f(z)$ may be less than $n$. However, if we take into account the multiplicity of each root, then the sum of the multiplicities is exactly $n$. In this sense, the polynomial $f(z)$ has exactly $n$ roots.

Polynomials with real coefficients

Let us now consider the case when all coefficients of the polynomial $f(z)$ are real numbers. About the roots

⟦folio 9⟧

whom the polynomial can express some scales interesting additional messages.

To consider a polynomial with real coefficients, we introduce the concept of a number $\bar{z}$, the complex conjugate of a given complex number $z$. Exactly if
$$z = x + iy,$$
then, by definition, the number
$$\bar{z} = x - iy$$
(14)

is called complex conjugate to $z$. Thus, the number $\bar{z}$, complex conjugate to the number $z$, is the mirror image of the number $z$ relative to the axis of real numbers.

If
$$z = r(\cos \alpha + i \sin \alpha),$$
That
$$\bar{z} = r(\cos \alpha - i \sin \alpha) = r(\cos (-\alpha) + i \sin (-\alpha)).$$
(15)

Thus, the arguments of two complex conjugate numbers differ only in sign. From formula (14) it follows that
$$\bar{z}_1 + \bar{z}_2 = \bar{z}_1 + \bar{z}_2.$$
From formula (15) it follows that
$$\bar{z}_1 \bar{z}_2 = \bar{z}_1 \cdot \bar{z}_2.$$
Note also that the equality
$$\bar{z} = z$$
holds if and only if $z$ is a real number.

From the three previous formulas it is easy to see that for polynomials $f(z)$ with real coefficients the equality holds
$$\bar{f}(\bar{z}) = f(\bar{z}).$$
From this equality it follows that if $z_1$ is the root of the polynomial $f(z)$ with real coefficients, then $\bar{z}_1$ is also its root. If $z_1$ is a real number, then this statement is meaningless. If $z_1$ is not a real number, then the statement indicates the existence, along with the root $z_1$, of a different root $\bar{z}_1$. Thus, if $z_1$ is not a real number, then the polynomial $f_1(z)$ (see (13)) has a divisor $(z - \bar{z}_1)$, and we get the factorization

$$f(z) = (z - z_1)(z - \bar{z}_1)f_2(z).$$
Polyaga in this equality
$$z_1 = x_1 + iy_1,$$
we get
$$f(z) = (z^2 - 2x_1z + x_1^2 + y_1^2)f_2(z).$$

Thus, we saw that the polynomial $f(z)$ has a real quadratic factor $z^2 - 2x_1z + x_1^2 + y_1^2$. It follows that the polynomial $f_2(z)$ is also a polynomial with real coefficients, since it is obtained by dividing the polynomial $f(z)$ by a real quadratic trinomial. Consequently, this polynomial $f_2(z)$ has complex roots that are again pairwise conjugate. If he finds a root equal to the already found root $z_1$, then he will also find a root $\bar{z}_1$. Thus, in this case, one quadratic factor is extracted from the polynomial $f_2(z)$, equal to the previous quadratic factor. From this it is clear that the multiplicity of the complex root of the polynomial $f(z)$ with real coefficients is equal to the multiplicity of the conjugate root, and we obtain the decomposition of the polynomial $f(z)$ into real factors:

$$f(z) = (z^2 - 2x_1z + x_1^2 + y_1^2)^{k_1} \dots (z^2 - 2x_pz + x_p^2 + y_p^2)^{k_p} \times (z - z_{p+1})^{k_{p+1}} \dots (z - z_q)^{k_q}.$$

Note that quadratic factors of the form
$$z^2 - 2x_i z + x_i^2 + y_i^2, \quad i = 1, 2, \dots, p,$$
in which all $y_i$ are not equal to zero, can no longer be factorized into real factors.
