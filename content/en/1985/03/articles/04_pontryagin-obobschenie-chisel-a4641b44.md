---
id: 1985-3-pontryagin-obobschenie-chisel-a4641b44
issue: kvant_1985_3
year: 1985
number: "3"
title: Generalization of numbers
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2-4
tag: ASM5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3e93bcc675484bf01d061a00f0d97dace1e93bdcf45a4f2756d90b1a6be6ab1d
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/04_pontryagin-obobschenie-chisel-a4641b44.md
source_content_sha256: db4e404f08167c921b05025baf585470f08ef56287221947f22620247df3ee3c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Generalization of numbers

Academician L. S. PONTRAGIN

This article continues the story about possible generalizations of the concept of number, begun in the previous issue «Kvant»*). Here it is shown that it is impossible to rotate the data in this direction, that is, to think through further generalizations of numbers different from those discussed in the previous article.

§ 6. Frobenus's theorem

Let $L$ be a certain set of quantities $x$, which are written in the form

$$x = x_0 + x_1 i_1 + x_2 i_2 + \dots + x_n i_n,$$

where $x_0, x_1, x_2, \dots, x_n$ are real numbers (coordinates of the value $x$), and symbols

$$i_1, i_2, \dots, i_n$$

are called minimum units.

Together, $L$ defines addition and multiplication. Let $y$ be some other value of the aggregate $L$

$$y = y_0 + y_1 i_1 + \dots + y_n i_n.$$

The quantities $x$ and $y$ are considered equal if and only if their coordinates are equal, that is, equality holds

$$x_0 = y_0, x_1 = y_1, \dots, x_n = y.$$

The addition of the quantities $x$ and $y$ occurs according to the rule

$$x + y = (x_0 + y_0) + (x_1 + y_1) i_1 + \dots + (x_n + y_n) i_n.$$

Thus, the quantities from $L$ are added coordinatewise. Values ​​from $L$ can also be multiplied by any real number, also coordinatewise:

$$\lambda x = \lambda x_0 + (\lambda x_1) i_1 + \dots + (\lambda x_n) i_n.$$

In order to set the rule for multiplying the quantities $x$ and $y$ from $L$, we must first of all accept that the real numbers are permutable with minimum units (51) having in $L$, that is, when changing

$$*) См. «Кванта», № 2, c. 6.$$

expressions (50) and (52) open the parentheses and group the terms, in particular, $(x_1 i_1) \times (y_2 i_2) = (x_1 y_2)(i_1 i_2)$, etc. In addition, you need to determine by what variable rule the minimum units (51), for example, indicate what $i_1 i_2$ is equal to. In this case, it is assumed that the product of any two minimal units of system (51) is some quantity from $L$, however, we do not require that the multiplication of minimal units be commutative. Frobenous's result is that the set of the quantity $L$ coincides with either the set of all real numbers, in which case which quantity is written in the form $x = x_0$, or with the set of all complex numbers, in which case which quantity of $L$ is written in the form

$$x = x_0 + x_1 i,$$

(55)

or with the totality of all squares, in which case the value from $L$ is written in the form

$$x = x_0 + x_1 i + x_2 j + x_3 k.$$

§ 7. Several auxiliary statements

When proving Frobenus's theorem, I will assume that the concept of a vector space $R^m$ of arbitrary dimension $m^*$ is known. For example, that each vector in the space $R^m$ is given by a sequence of $m$ real numbers, called the coordinates of the vector. In this space, the addition of vectors is defined, which occurs coordinate-by-coordinate, the multiplication of a vector by a real number, in which all the coordinates of the vector are multiplied by this real number. A zero vector is a vector whose coordinates are all zero.

Let

$$u_1, u_2, \dots, u_k$$

is a certain set of vectors in the space $R^m$. Vectors (57) are called linearly dependent if there are real numbers, and $a_1, a_2, \dots, a_k$, not all equal to zero, such that

$$a_1 u_1 + a_2 u_2 + \dots + a_k u_k = 0.$$

The result, which I have used here without proof, is

*) The necessary information about vector spaces can be read in the Addendum to this article (p.5).

⟦folio 3⟧

in the next one. In a vector space of dimension m, any system of k vectors, where k > m, is linearly dependent.

Let us now move on to the preparatory part of the proof of Frobenus's theorem. A quantity included in the set of quantities L will be considered a real number if only its coordinate $x_0$ is different from zero, the rest are equal to zero. Let us choose from L such values ​​z that satisfy the following condition: $z^2$ is a real non-positive number, that is, it is either negative or equal to zero. We denote the set of such quantities by I. Note that the set R of real numbers and the set I have only one common element - zero.

Let us now prove the following:

Each value x of L can be represented as a sum

$$x = a + z, \quad a \in \mathbb{R}, \quad z \in I$$

in a unique way.

To prove this statement, let's create a sequence of values ​​x, starting from zero to n+1. Since sequence (60) contains n+2 quantities, and the dimension of the vector space L is equal to n+1, then quantities (60) are linearly dependent. This means that there is a polynomial f(u) of some variable u with real coefficients, the root of which is x, that is, the condition is satisfied

$$f(x) = 0.$$

Since x is the root of the polynomial f(u), the number x will be the root of an irreducible polynomial with real coefficients of degree one or two, as was proved at the end of § 5. If this irreducible polynomial is of degree one, that is, of the form u - a, where a is a real number, then x - a = 0, and therefore x is a real number a. If the irreducible polynomial q(u) has the second degree and its roots are not real, then it can be easily transformed to the form

$$q(u) = (u-a)^2 + b,$$

where b is a positive number. Since x is the root of this polynomial, (x-a)^2=-b and x is written in the form

$$x = a + z,$$

where a is a real number and z ∈ I, or z^2=-b. Thus, formula (59) is proven.

Let us now prove that the terms a and z in expansion (59) are uniquely determined by the quantity x. This statement is easily verified in the case where x is a real number, since then z=x-a, and R and I have only one element in common - zero, so z is zero. Let us assume that if we violate expansion (59), another expansion takes place:

Hermann Grassmann (1809-1877), German mathematician, physicist and philologist, creator of the general concept of vector space and (along with A. Cayley and Y. Hamilton) the theory of quaternons.

$$x = a_0 + z_0.$$

The case when one of the values ​​z or z₀ is equal to zero has already been discussed by us. In what follows, we will assume that they are both nonzero. Correspondences (59) and (63) imply the equality

$$z = z_0 + (a_0 - a).$$

Raising this correspondence by squaring, we get

$$z^2 = z_0^2 + 2z_0(a_0 - a) + (a_0 - a)^2.$$

Since z² and z₀² are real numbers, it follows from this correspondence that the product z₀(a₀ - a) is a real number. Since z₀ is not zero, this is only possible when a₀—a=0. Thus, the unique expansion (59) is established.

Note that with any element z from the set I, it includes the product of this element by any real number. Along with the element z≠0, I also includes the element z⁻¹, inverse to z. Let's write this in the form of formulas:

$$\text{При } a \in \mathbb{R}, \quad z \in I \quad \text{имеем } az \in I.$$

$$\text{При } 0 \neq z \in I \quad \text{имеем } z^{-1} \in I.$$

Let us now prove the following:

I is a linear space with respect to real numbers, that is, with two quantities u and v from I, I also includes their linear combination with real coefficients

⟦folio 4⟧

entami $a$ and $b$. Let us write this statement as a formula:

$$\text{При } a \in \mathbb{R}, b \in \mathbb{R}; u \in I, v \in I \text{ имеем } au + bv \in I. \tag{67}$$

To prove the last statement, it is enough for us to consider the case when $a$ and $b$ are not equal to zero, since the case when at least one of these numbers is equal to zero is contained in the already proven statement (65). By virtue of expansion (59) we have

$$au + bv = z_1 + a_1, \text{ где } z_1 \in I, a_1 \in \mathbb{R}. \tag{68}$$

Let us square correspondence (68). Then we will get

$$a^2u^2 + b^2v^2 + ab(uv + vu) = 2a_1z_1 + a_1^2 + z_1^2. \tag{69}$$

By virtue of expansion (59) we have

$$uv + vu = z_0 + a_0, \text{ где } z_0 \in I, a_0 \in \mathbb{R}. \tag{70}$$

Here the values ​​$z_0$ and $a_0$ do not depend on the numbers $a$ and $b$, but depend only on $u$ and $v$. Due to the uniqueness of expansion (59), the equality follows from (68) and (70)

$$abz_0 = 2a_1z_1. \tag{71}$$

And since the numbers $a$ and $b$ are both assumed to be non-zero. We get

$$z_0 = \frac{2a_1}{ab}z_1. \tag{72}$$

From the last equality it follows that if $z_0 \neq 0$, then $a_1 \neq 0$. (73)

Moreover, $a_1 \neq 0$ for any values ​​of $a$ and $b$, since $z_0$ does not depend on $a$ and $b$. Taking into account the last equality, we can rewrite correspondence (68) in the form:

$$au + bv = cz_0 + d, \tag{74}$$

where $c = ab/(2a_1)$ is a non-zero real number. Let us now choose two numbers $a'$ and $b'$, not proportional to $a$ and $b$, that is, such that the equality does not occur

$$\frac{a}{a'} = \frac{b}{b'}. \tag{75}$$

Then, by virtue of what has been proved, we have

$$a'u + b'v = c'z + d', \tag{76}$$

where the number $c'$ is not equal to zero. Let us now subtract from correspondence (74) correspondence (76), multiplied by a real number $a$, so that the equality $c - ac' = 0$ holds. Then we will have

$$a''u + b''v = d'', \tag{77}$$

where $a''$, $b''$ and $d''$ are real numbers. Or, in other words,

$$a''u = -b''v + d''. \tag{78}$$

Since the left side of this equality belongs to $I$, the right side of this equality must contain an element from $I$ (due to the uniqueness of decomposition (59)), that is, $d'' = 0$. We come to the conclusion that the vectors $u$ and $v$ are proportional to each other. For this case, our statement (67) is critical. Thus, statement (67) is proven.

It follows from what has been proven that, in accordance with (68), the real number $a_1$ is always equal to zero and, therefore, due to correspondence (72), the value $z_0$ is also always equal to zero. And so

$$uv + vu = a_0 \tag{79}$$

is a real number. From this
