---
id: 1977-4-shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84
issue: kvant_1977_4
year: 1977
number: "4"
title: About the equation C_n^m = C_n+1^m-1
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 23
page_last: 24
page_labels: 21-22
tag: XJIO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 151af3368c476383023572d835d01d7952dd9cf0afe71ba62c3c32803075e7fd
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/07_shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84.md
source_content_sha256: 5e62f3bf2a8f73fcf648302c7e5d545f6df3f4c43868fee98ba718aaeb5c433c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

About the equation
$$C_n^m = C_{n+1}^{m-1}$$

A. Shirshov

I came to the equation indicated in the title by considering the 14th line of Pascal's triangle:
1, 14, 91, 364, 1001, 2002, 3003, 3432, 3003, 2002, 1001, 364, 91, 14, 1.

Pascal's triangle is discussed in paragraphs 7 and 8 of the textbook “Algebra and Basic Analysis 9”.

Let’s briefly talk about him for those who are not yet familiar with him.

In the n-th line of Pascal's triangle, in the m-m place there is the number $C_n^m$, and the numbering of both lines and numbers in each line starts from zero (the first 15 lines of Pascal's triangle are given at figure).

To understand the article, it is enough to know only one thing about the numbers $C_n^m$:
$$C_n^m = \frac{n!}{m!(n-m)!}$$

($n! = 1 \cdot 2 \cdot \dots \cdot n; 0! = 1$). From (1) it is easy to deduce
$$C_n^m + C_{n+1}^{m+1} = C_{n+1}^{m+1}.$$

Using this correspondence, you can construct Pascal’s triangle without using formula (1) (see figure).

In the 14th line it is striking that 1001+2002=3003, that is
$$C_{14}^4 + C_{14}^5 = C_{14}^6.$$

In view of (2), this equality can be rewritten as follows:
$$C_{15}^5 = C_{14}^6.$$

Equality (3) shows that pair (6, 14) is a solution to the equation indicated in the title.

What other pairs of numbers are the solution to this equation? The article provides an answer to this question. To make the answer more beautiful, let’s replace m in our equation with y, and n with x-1. Then the following theorem is true. All solutions of equation $C_x^{y-1} = C_x^{-1}$ have the form
$$x_k = \gamma_{2k} \gamma_{2k+1}; \quad y_k = \gamma_{2k-1} \gamma_{2k}, \quad k = 1, 2, 3, \dots, \text{еде } \gamma_n - n-\text{й член последовательности Фибоначчи}^*): 1, 1, 2, 3, 5, 8, 13, 21, 34, \dots$$

Proof.
1. Let's use formula (1) and rewrite our equation:
$$\frac{x!}{(y-1)!(x-y+1)!} = \frac{(x-1)!}{y!(x-y-1)!}.$$

After obvious transformations it is reduced to the following form:
$$(x-y+1)(x-y)=xy.$$

Let us denote by w the most common divisor of the numbers x and y. Then x=uw, y=vw, where u and v are coprime. Substituting the expressions for x and y into (4), after canceling by w, we obtain that $(u-v)[(u-v)w+1]=uvw.$

The numbers u and v are coprime. Therefore u-v and uv are also relatively prime. The numbers w and $(u-v)w+1$ are also mutually prime. But then the following equalities must hold:
$$\begin{cases} (u-v)w+1=uv, \\ u-v=w. \end{cases}$$

*) For this sequence $\gamma_n = \gamma_{n-1} + \gamma_{n-2}$ for n > 2.

⟦folio 22⟧

This system is equivalent to the following system:

$$\begin{cases} v^2 + vw - w^2 = 1, \\ v + w = u. \end{cases}$$

Therefore, the solution to our equation coincides with the solution to the equation

$$v^2 + vw - w^2 = 1$$

in natural numbers.

2. Let's make three simple changes to solve equation (7). Let the pair $\langle v, w \rangle$ be a solution to equation (7). Then

a) $v$ and $w$ are coprime;
b) if $v = w$, then $v = w = 1$;
c) $v \leq w < 2v$;
d) the pairs $\langle v + w, v + 2w \rangle$ and $\langle 2v - w, w - v \rangle$ are solutions to the equation.

Recall that $v$ and $w$ are natural numbers.

c) follows from the equality $w = \frac{v + \sqrt{5v^2 - 4}}{2}$, obtained if (7) is considered as an equation for $w$, and d) can be verified by substituting the corresponding pairs into equation (7).

Using transformation

$$\langle v, w \rangle \Rightarrow \langle v + w, v + 2w \rangle,$$

Based on the solution $\langle 1, 1 \rangle$, we construct a sequence of solutions $\langle 2, 3 \rangle, \langle 5, 8 \rangle, \langle 13, 21 \rangle, \langle 34, 55 \rangle, \dots$.

The written solutions have the form

$$v_h = \gamma_{2h-1}, w_h = \gamma_{2h}.$$

Let us prove that equation (7) has no other solutions. Let us assume that the pair $\langle v, w \rangle$ is a solution to equation (7). Let us prove that it is one of the pairs (8).
