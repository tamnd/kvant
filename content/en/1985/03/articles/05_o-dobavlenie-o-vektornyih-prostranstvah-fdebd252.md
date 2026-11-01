---
id: 1985-3-o-dobavlenie-o-vektornyih-prostranstvah-fdebd252
issue: kvant_1985_3
year: 1985
number: "3"
title: Addendum about vector spaces
authors:
  - О. М.
rubric: smes
page_first: 7
page_last: 7
page_labels: "5"
tag: XW5N
lang: en
source: kvant_digital
extraction: vision
content_sha256: c1217b0af2a361b067d11385b37a06bb7b3a99f90e8319f159a48741bab6bf0c
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/05_o-dobavlenie-o-vektornyih-prostranstvah-fdebd252.md
source_content_sha256: 5c0643f2224f9ded0b39cbde8d0b7a4ca86525478ee2cecb2e49cae96ac75eed
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

$$k^2 = -1; \quad ki = -ik = j; \quad jk = -kj = i.$$
Thus, for the value $i, j, k$ (85)

all conditions that apply to quaternion units are met (see «Kvant» No. 2, p. 11). If now any element $z$ of $I$ linearly depends on the value $i, j, k$, then $L$ coincides with the set of all quaternions.

It remains to consider the case when $L$ contains an element $z$ that is linearly independent of the value $i, j, k$. Let us put (see (59))

$$iz = a_1 + z_1; \quad jz = a_2 + z_2; \quad kz = a_3 + z_3.$$ (86)

Let us also put

$$l = a(z + a_1i + a_2j + a_3k).$$ (87)

It is easy to check that for an arbitrary value of the real number $a \neq 0$ the value $l$ belongs to $I$ and is not equal to zero. We choose the number $a$ in such a way that the condition is satisfied

$$l^2 = -1.$$ (88)

From correspondence (80) it follows that

$$il = -li; \quad jl = -lj; \quad kl = -lk.$$ (89)

Now consider the quantities $ilj$. We have

$$ilj = i(-jl) = -kl; \quad ilj = -lij = -lk = kl.$$ (90)

Thus, we come to the conclusion that $-kl = kl$, which is impossible since $(kl)^2 = -1$. So, we have arrived at a contradiction - Frobenus's theorem has been proven.

Addendum about vector spaces

Consider the set $V_3$ of all vectors in three-dimensional space with origin at a fixed point $O$. If we introduce a coordinate system $x_0, x_1, x_2$ in space with the origin at point $O$, then any vector $v \in V_3$ is uniquely represented in the form

$$v = x_0i_0 + x_1i_1 + x_2i_2,$$ (1)

ede $i_0, i_1, i_2$ are the only vectors of the $Ox_0, Ox_1, Ox_2$ axes, and $x_0, x_1, x_2$ are some numbers (called the coordinates of the vector $v$). When adding vectors, their coordinates are added, and when multiplying a vector by a number, its coordinates are multiplied by this number, that is

$$v + v' = (x_0i_0 + x_1i_1 + x_2i_2) + (x'_0i_0 + x'_1i_1 + x'_2i_2) =$$

$$= (x_0 + x'_0)i_0 + (x_1 + x'_1)i_1 + (x_2 + x'_2)i_2;$$ (2)

$$av = a(x_0i_0 + x_1i_1 + x_2i_2) =$$

$$= (ax_0)i_0 + (ax_1)i_1 + (ax_2)i_2.$$ (3)

After the coordinates are introduced, we can assume that the vectors in the space space are triplets of numbers $(x_0, x_1, x_2)$ and forget about their geometric origin. With that

whose approach the study becomes purely algebraic and is based on formula (1) - (3).

The algebraic approach makes it possible to easily determine a vector space with a number of changes greater than three. Namely, for any $n \geq 1$ an n-dimensional (arithmetic) vector space is the set of collections $v = (x_1, x_2, \dots, x_n)$ of $n$ real numbers in which addition operations are introduced:

$$u + v = (x_1, x_2, \dots, x_n) + (y_1, y_2, \dots, y_n) =$$

$$= (x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) = w$$ (4)

and multiplication by the number $a \in R$:

$$au = a(x_1, x_2, \dots, x_n) =$$

$$= (ax_1, ax_2, \dots, ax_n).$$ (5)

In this case, the sets $(x_1, x_2, \dots, x_n)$ are called $n$-dimensional vectors. They can be written in the form $(x_1i_1 + x_2i_2 + \dots + x_ni_n)$ or in the form $x_0 + x_1i_1 + \dots + x_{n-1}i_n$, as was done in the article by L. S. Pontryagin (see p. 2).

The main concept when studying a $n$-dimensional vector space is linear dependence: a set of vectors $v_1, v_2, \dots, v_k$ is said to be linearly dependent if there are numbers $a_1, a_2, \dots, a_k$, not all equal to zero, such that

$$a_1v_1 + a_2v_2 + \dots + a_kv_k = 0.$$

It can be shown that any set of more than $n$ vectors in a $n$-dimensional space is linearly dependent; In addition, in this space you can specify a set of $n$ linearly independent vectors (such a set depends on the basis), for example, a set $i_1 = (1, 0, 0, \dots, 0), i_2 = (0, 1, 0, \dots, 0), \dots, i_n = (0, 0, \dots, 0, 1).$

Exercises

1. Prove the statement about $V_3$ in italics at the beginning of this Appendix.
2. Prove that two vectors in space are linearly dependent if and only if they lie on the same line, and three vectors - when they lie in the same plane.
3. Prove (geometric) that any four in space are linearly dependent.
4*. Prove that any $n+1$ vectors in a $n$-dimensional space are linearly dependent.
5*. Show that the collection of polynomials of degree less than or equal to the volume of an aprithmetic vector space of dimension four, the basis of which can be the polynomials $x^3, x^2, x, 1$.

O.M.
