---
id: 1985-7-dvoryaninov-yasinovyiy-kak-poluchayutsya-simmetrichnyie-neravenstva-e13a15dd
issue: kvant_1985_7
year: 1985
number: "7"
title: How to obtain symmetric inequalities
authors:
  - Дворянинов С. В.
  - Ясиновый Э. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 38
page_labels: 33-36
tag: M72N
lang: en
source: kvant_digital
extraction: vision
content_sha256: aab7c15b2d301039798589283f2d84bb3ee1e60744929221dca7eb47f85a3390
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/10_dvoryaninov-yasinovyiy-kak-poluchayutsya-simmetrichnyie-neravenstva-e13a15dd.md
source_content_sha256: 2ecc0e7be04f5b48d586250e3deee13f6398c0fbc7d0d1cdd4f5d55d447b2ca1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

How to obtain symmetric inequalities

Candidate of Physical and Mathematical Sciences
S. V. DVORYANINOV,
Candidate of Pedagogical Sciences
E. A. YASINOVY

In many problems in algebra and analysis, in mathematical olympiads, and sometimes in exams, there are problems in which you need to prove an inequality with several variables. The simplest of them are available to students in grades 5-6. Numerous mathematical statists, reviews, and monographs are devoted to various methods of their proof and general theorems on substitution inequalities. A lot of articles on inequalities have accumulated in the portfolio of our “Mathematics Circle”.

This note describes Muirhead's theorem on inequalities relating symmetric polynomials of a special form (sums of all possible same-year polynomials with the same exponents). This theorem, proven in 1903, is remarkable not only for its generality and finality, but also for the fact that combinatorial concepts arose in connection with it (“Young diagrams” and their comparison - “majorization”) after a natural appearance in various branches of theoretical and applied mathematics, which have been actively developing in recent times.

Introduction

We will deal with inequalities of this type:

$$x^2 + y^2 \geq 2xy,$$
(1)
$$x^5 + y^5 \geq x^3y^2 + y^3x^2,$$
(2)
$$x^2 + y^2 + z^2 \geq xy + yz + zx,$$
(3)
$$x^3 + y^3 + z^3 \geq 3xyz,$$
(4)

$$x^2y^2 + y^2z^2 + z^2x^2 \geq x^2yz + y^2xz + z^2xy,$$
(5)
$$x^4 + y^4 + z^4 + w^4 \geq 4xyzw.$$
(6)

These inequalities are valid for all non-negative values ​​of the letters included in them. For the case of two variables, it is also easy to prove the inequalities by grouping the terms and factoring them. Let us prove, for example, that for any non-negative x and y inequality (2) holds. To do this, consider the difference

$$x^5 + y^5 - x^3y^2 - y^3x^2 = x^3(x^2 - y^2) - y^3(x^2 - y^2) = (x^3 - y^3)(x^2 - y^2).$$

After it, the product is obviously non-negative; both brackets are not less than 0 for $x \geq y \geq 0$ and not more than 0 for $y \geq x \geq 0$.

It is difficult for Vollee to achieve a symmetrical proof of inequality with a crown or a large number of variables. Let us demonstrate the general idea using one example (5). Here it is convenient to cross all the terms to the left side of the inequality, multiply them by 2 and collect them into three groups:

$$x^2(y^2 - 2yz + z^2) + y^2(x^2 - 2xz + z^2) + z^2(x^2 - 2xy + y^2) = x^2(y - z)^2 + y^2(x - z)^2 + z^2(x - y)^2 \geq 0.$$

Exercise 1. Try to prove inequalities (1), (3) and (6).

To learn how to prove all kinds of inequalities of this type and formulate a general theorem, you need to become familiar with non-negative new concepts. Now we will describe them.

Symmetrization of a monomial

Let us have several non-negative variables - for definition, three variables x, y and z. In addition, let a set of the same number of non-negative integers be given, $\alpha = (k; j; i)$, where $k \geq j \geq i$; Let's call them an indicator. Let's draw a table of three squares and write the corresponding indicator in the upper right corner of each. We put three letters x, y, z into these squares and, looking at the table, write the monomial $x^k y^j z^i$. Now in the same table we add variables in another

⟦folio 34⟧

In order; we obtain, for example, the following monomial $y^k x^j z^i$, and so on (Fig. 1).
(It’s not difficult to count how many different monomials we’ll get. You can put any of the three letters $x, y, z$ in the first square - this gives three options; in the second square - any of the two remaining letters, so there are $3 \cdot 2 = 6$ options in total.) Then add up all the written monomials; the resulting polynomial in three variables $x, y, z$ will be denoted by $T_{(k,j,i)}(x,y,z)$, or $T_u(x,y,z)$, or simply $T_u$ (T - from the word “table”). This polynomial will be, as they say, “symmetric”; it does not change with any permutation of variables. The degree of each of its monomials is $s=k+j+i$.

For example,

$$T_{(2;1;0)}(x, y, z) = x^2 y + y^2 x + z^2 x + x^2 z + z^2 y;$$

$$T_{(3;1;1)}(\dot{x}, y, z) = x^3 y z + y^3 x z + z^3 x y + x^3 z y + y^3 z x + z^3 y x;$$

$$T_{(2;2;2)}(x, y, z) = 6 x^2 y^2 z^2.$$

The last two examples show that when there are equal exponents, similar terms can be added to the polynomial $T_u$ and written shorter.

If the set of indicators $\alpha = (\alpha_1, \alpha_2, \dots, \alpha_n)$ consists of $n$ numbers, then you need to draw a table with $n$ squares and take $n$ variables $x_1, x_2, \dots, x_n$. Moreover, in the polynomial $T_u(x_1, \dots, x_n)$ there will be $n! = 1 \cdot 2 \cdot \dots \cdot n$ monomials before similar ones are reduced.

So, for each set of integers $\alpha = (\alpha_1; \alpha_2; \dots; \alpha_n)$, where $\alpha_1 \geqslant \alpha_2 \geqslant \alpha_3 \geqslant \dots \geqslant \alpha_n \geqslant 0$ corresponds a polynomial $T_u$ is a “symmetrization” of a monomial with exponents $\alpha_1, \alpha_2, \dots, \alpha_n$.

We will depict each such set $\alpha$ as a ladder of $n$ steps: the height of each step is equal to the corresponding indicator, the width is one. It is convenient to draw such a ladder on checkered paper; the total number of cells - “bricks” $1 \times 1$, of which the ladder consists, is equal to $s = \alpha_1 + \dots + \alpha_n$ - the degree of the polynomial $T_u$. figure 2 shows ladders corresponding to some of the polynomials $T_u$ encountered in our inequalities.

The scientific name for these ladders, which are useful in various problems of combinatorics, algebra and analysis, is “Young diagrams” (see [3]).

Exercise 2. Write the polynomials $T_u$ and draw their corresponding ladders for the following sets $\alpha$: (3, 2); (3, 2, 1); (3, 3, 0, 0); (4, 1, 1, 0); (5, 0, 0, 0, 0); (1, 1, 1, 1, 1).

Comparison of Young diagrams

figure 3 shows pairs of ladders corresponding to inequalities (1)–(6) from the introduction. We see that the larger of the two polynomials corresponds to the larger ladder: the second, flatter one, can be obtained from the first by connecting several kippei to the right - down (see Fig. 4). Let us formulate more precisely what the words “larger” mean here, first for staircases of three steps.

Let $\alpha = (\alpha_1; \alpha_2; \alpha_3)$ and $\beta = (\beta_1; \beta_2; \beta_3)$ be two sets of integers with the same sum $s = \alpha_1 + \alpha_2 + \alpha_3 = \beta_1 + \beta_2 + \beta_3; \alpha_1 \geqslant \alpha_2 \geqslant \alpha_3 \geqslant 0$ and $\beta_1 \geqslant \beta_2 \geqslant \beta_3 \geqslant 0$. We will assume that $\alpha > \beta$ (and maximizes $\beta$), if the following condition is met:

$\beta$ can be obtained from $\alpha$ by continuing several times (perhaps

⟦folio 35⟧

There is only partial between sets - it happens that two sets with the same sum are not comparable (see Exercise 6).

Exercises

3. Check that the pairs of Young diagrams on Fig. 3 satisfy conditions (*) and (**).

4. Prove that conditions (*) and (**) are equivalent (that is, if inequalities (**) are satisfied, then the set β can be obtained from α “by dumping bricks” and vice versa).

5. Draw all the stairs of s=4 bricks in descending order, starting from the steepest (4;0;0;0) and ending with the flattest (1;1;1;1); the same for ladders of 5 bricks.

6. a) Check that the Young diagrams (4;1;1) and (3;3;0) are not comparable—neither of them maximizes the other. Are there any other unequal sets with sum 6?

6) Find all such pairs of sets for s=7.

**Muirhead's theorem**

Now everything is ready to form the main theorem.

Let α=(α1;α2;...;αn) and β=(β1;β2;...;βn) be two sets of indicators with the same sum. If α>β, then for all non-organizational x1, x2, ..., xn
Tα(x1, x2, ..., xn)>Tβ(x1, x2, ..., xn).
Conversely, if such an inequality holds, then α>β.

We will not give a formulaic proof of the theorem in general form (it can be found in books [1], [2] - the second of them is entirely devoted to various versions of the “maximization” relation, its applications and generalizations), but instead we will describe its main ideas and demonstrate them with specific examples.

The proof of the second part of the theorem—the necessity of the condition α>β—follows from the simple fact that of two polynomials in one variable t (with positive leading coefficients), for large values ​​of t, the one with the greater degree is greater (see Exercise 8).

The proof of the sufficiency of the condition α>β is based on two ideas. The first is “dumping bricks”: two sets α>β can be connected by an integer of sets so that the neighboring sets in this integer differ only in two places, so that from each set to the next one can move, “dumping a brick” from one step to another on the corresponding ladder. The second is “symmetric grouping”: the difference of polynomials for neighboring sets can be written as the sum (over all parameters x, y) of identical groups of the form
(xp+r yq+p r xq−p r yq+p r)Z
(see Fig. 5), where Z is the product of the remaining variables corresponding to the same indicators in neighboring sets. Last you-

⟦folio 36⟧

Fig. 5.

the decomposition is decomposed into a set and, as is easy to see, for $p > q$, $r \geq 0$, it is non-negative. (Check!)
All this will become clear to those who carefully, writing out all the calculations in detail, analyze several examples. We will give two.

Inequality between the arithmetic means and the geometric mean of three non-negative numbers

$$\frac{a_1 + a_2 + a_3}{3} \geq \sqrt[3]{a_1 a_2 a_3}$$

after redesignation $a_1 = x^3$, $a_2 = y^3$, $a_3 = z^3$ turns into inequality (4), which was already mentioned above. Let us show how it proves it using Muirhead's method. Looking at figure 4 a), we see that we need to prove two inequalities:

$$T_{(3; 0; 0)}(x, y, z) \geq \geq T_{(2; 1; 0)}(x, y, z)$$

Let's consider the first of them and make up the difference

$$R_1 = T_{(3; 0; 0)}(x, y, z) - T_{(2; 1; 0)}(x, y, z) = 2(x^3 + y^3 + z^3) - x^2y - y^2z - z^2x - x^2z - y^2x - z^2y.$$

Let us now group the terms by four according to the following principle: for each pair of variables, one group includes terms in which the indicators for these variables change from (3, 0) to (2, 1) (and the overall indicator in the sets here 0 is in last place). We get

$$R_1 = (y^3 + z^3 - y^2z) + (x^3 + y^3 - x^2y - y^2x) + (z^3 + x^3 - z^2x - x^2z) = (y^2 - z^2)(y - z) + (x^2 - y^2)(x - y) + (z^2 - x^2)(z - x) \geq 0$$

for all non-negative $x, y, z$.

Now let's prove the second inequality

$$R_2 = T_{(2; 1; 0)}(x, y, z) - T_{(1; 1; 1)}(x, y, z) = x^2y + y^2z + z^2x + x^2z + y^2z - 6xyz.$$

Here, in the exponents, the common unit is in second place, and (2; 0) turns into (1, 1). In accordance with this, we get:

$$R_2 = x(y^2 + z^2 - 2yz) + y(z^2 + x^2 - 2zx) + z(y^2 + z^2 - 2yz) = x(y - z)^2 + y(z - x)^2 + z(x - y)^2 \geq 0.$$

This proves inequality (4).

Solution to problem M762.

In this problem (from the “Problem Book «Kvant» No. 9, 1982) it was necessary to prove the inequality for positive $a, b, c$

$$a + b + c \leq \frac{a^2 + b^2}{2c} + \frac{b^2 + c^2}{2a} + \frac{c^2 + a^2}{2b} \leq \frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}.$$

The reader suggested several different methods for solving them. One of them is the Muirhead method (we hope to return to the others in one of the next issues «Kvant»). By multiplying these inequalities by 2abc, we reduce them to the following “Mirhead” form:

$$2(a^4 + b^4 + c^4) \geq \geq a^3b + b^3a + b^3c + c^3a + a^3c,$$

$$a^3b + b^3a + b^3c + c^3a + a^3c \geq 2(a^2bc + b^2ac + c^2ab).$$

The corresponding Young diagrams are shown in figure 4, 6. The difference between the left and right sides of each inequality can be written, as above, as the sum of three groups of four annuals. To save space, we will write only one group - the other two are obtained by replacing the letter $a, b, c$ with $b, c, a$ and $c, a, b$.

Proof (7):

$$(a^4 + b^4 - a^3b - b^3a) + \dots = (a^3 - b^3)(a - b) + \dots \geq 0.$$

Proof (8):

$$(a^3b + c^3b - a^2cb - c^2ab) + \dots = b(a^2 - c^2)(a - c) + \dots \geq 0.$$

Thus, the M762 problem is solved.

A few more exercises and problems to explore

7. Write down all Muirhead's inequalities for polynomials of degree 4.

8. a) Let $T_{(a_1; a_2; a_3)}(x, y, z) \geq T_{(\beta_1; \beta_2; \beta_3)}(x, y, z)$ for all non-negative $x, y, z$. Prove that then inequality (**) is satisfied. (Indicate. Consider several cases: $x = y = z = t; x = y = t, z = 1; x = t, y = z = 1$ and compare the degrees of the resulting polynomials from $t$.)

9. Prove the following inequalities (for non-negative $x, y, z, v, w$):

a) $x^4y^2z + y^4x^2z + z^4yx^2 + x^4z^2y + z^4x^2y \geq 2(x^3y^2z + y^3z^2x + z^3x^2y^2);$

b) $x^5 + y^5 + z^5 \geq x^2y^2z + y^2z^2x + z^2x^2y;$

b) $x^3 + y^3 + z^3 + v^3 \geq xyz + xyv + xzv + yzv.$

10. Derive from Muirhead's theorem inequalities for arithmetic and geometric means $n$ non-negative numbers.

How many “bricks” do you need to knock down to move from a set $(n, 0, 0, \dots, 0)$ of $n$ numbers to a set (1, 1, ..., 1)?

11. Form and prove Muirhead's theorem for any non-negative (not necessarily integer) exponents.

12. For some sets of exponents (with an even sum $s$), the inequality discussed in Muirhead's theorem is true for all, not just for non-negative values ​​of the variables. Try to describe all such cases.

Literature

1. Hardy G. G., Littelwood D. E., Polina G. Inequalities - M.: IL, 1948.
2. Marshall A., Olkin I. Inequalities: maximization theory and its applications. - M.: Mir, 1983.
3. Correspondence mathematical olympiads (problems 5-9). - M.: Nauka, 1981.
