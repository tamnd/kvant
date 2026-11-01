---
id: 1978-12-geronimus-diofantovyi-uravneniya-po-prostomu-modulyu-3781c26a
issue: kvant_1978_12
year: 1978
number: "12"
title: Diophantine equations modulo prime
authors:
  - Геронимус А. Ю.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2-6
tag: 09MK
lang: en
source: kvant_digital
extraction: vision
content_sha256: cf1cf9a7e0167dd64327d7128babfd35108c9aede6bd853d3165ef6961bfcb29
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/02_geronimus-diofantovyi-uravneniya-po-prostomu-modulyu-3781c26a.md
source_content_sha256: 88815c5942334e607fc5dac5177e7b32f50ad9cf977879d41eb0f8655c934cd2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Diophantine equations modulo prime

“Most Venerable Dionysius, knowing that we zealously want to learn how to solve the problem concerning numbers, I tried to explain their nature and power, ours, from the foundations on which this science rests.

Perhaps this subject will seem difficult to me, since we are still unfamiliar with it, and beginners are not inclined to expect success. But first it is possible through your diligence and my mistakes, or a passionate love for science helps to quickly learn.”

With this dedication the Arithmetic of Diophantus of Alexandria opens.

In this book, Diophantus (he lived presumably in the 3rd century) summarized and expanded the experience accumulated before him in solving indefinite (i.e., with several variables) algebraic equations in integers or rational numbers. Since then, these equations have come to be called Diophantine equations.

Here are examples of such equations:
$$x^2 + y^2 = z^2, \quad x^2 = y^3 + 5y + 7.$$

Interest in the Diophantine equation is apparently connected with the very nature of man - preserved documents reveal its traces in the depths of thousands of years. Even in Ancient Babylon, they were searching for Pythagorean projects - integer solutions $x^2 + y^2 = z^2$.

Diophantus' "arithmetic" formed the basis of modern number theory. Since the time of Fermat (17th century), Diophantine equations have become the subject of deep research by the most eminent mathematicians and the unflagging interest of all lovers of numbers, not inferior in reven to the venerable Dionysius.

The power of the tasks spoken of in the dedication has grown and is growing. The theory of Diophantine equations has connections with almost all areas of modern mathematics.

Diophantus was mistaken in only one thing - the subject did not become intelligible.

Probably the last person to share this hope was the famous German mathematician David Hilbert. In 1900, in a report at the Second International Competition of Mathematicians, he formulated 23 problems from different areas of mathematics. The tenth problem was formulated as follows: indicates the method by which it is possible, after a finite number of installation operations, whether a given Diophantine equation is solvable in integers.

A long period of research ended in 1969 with a negative solution to this problem: it turned out that the general method mentioned in its formulation does not exist at all *).

In connection with Diophantine equations, simpler problems were also posed. When solving them, very beautiful theories arose. We discussed the beginnings of one of them - the theory of Diophantine equations modulo prime - in this country. To make this story clear to you, we advise you to re-read the articles “Comparisons and classes of residues” (No. 10) and “Comparisons by simple modulo” (No. 11).

Transition to an equation modulo prime

Let's consider some Diophantine equation. Let's assume that it has a solution and consider it together

*) For more information about this, see «Kvant», 1970, No. 7.

⟦folio 3⟧

the numbers included in the solution are their residue classes mod p. It is easy to see that the resulting set will be a solution to the given equation - the equation obtained from the given one by replacing each coefficient with its residue class mod p. Therefore, it is necessary to consider the solution of the Diophantine equation to be the existence of a solution to the reduced equation mod p for all p*).

In this section we will give two examples of the transition to mod p, and in the next we will study the dynamic Diophantine equation mod p (that is, equations with coefficients in the set F_p) themselves. Their theory is much simpler than the theory of ordinary Diophantine equations. The set F_p is finite, and it is possible to establish whether a given Diophantine equation has a solution by simple search. Therefore, it is not so surprising that for the set F_p there are general theorems that guarantee the existence of solutions. We formulate and discuss these theorems in the following sections.

What are the integer solutions to the equation

$$35x^4 + 24y^3 = 100\ 000?$$

(1)

Let's present this equation mod 3. 35 ≡ 2 (mod 3), 24 ≡ 0 (mod 3), 100\000 ≡ 1 (mod 3); therefore, mod 3, equation (1) takes the form

$$\bar{2}x^4 = \bar{1}.$$

(2)

$$\bar{2}x^4$$ for x ∈ F_3 takes values ​​0 and 2 (check), so equation (2) has no solutions, which means equation (1) has no solutions either.

Let's look at the last example:

$$5x^3 + 11y^3 + 13z^3 = 0.$$

(3)

This equation has one obvious solution: x = y = z = 0. Let's try to prove that it has no other solutions.

It is natural to consider equation (3) modulo 5, 11 or 13 - then one of the three terms will turn to 0. Which modulo should we choose?

*) Calculations “modulo” are also discussed in the article by M. I. Bashmakov («Kvant», 1971, No. 3).

Solving problem 4 of the article “Comparisons by simple modulo” will help us answer this question. It follows from it that in the sets F_5 and F_{11} all elements are cubes, and in the set F_{13} only 5 elements are cubes.

After reducing equation (3) modulo 5, it takes the form

$$y^3 + \bar{3}z^3 = \bar{0}.$$

(4)

Since any element of the set F_5 is a cube and division is possible in F_5, for any a and b they will find y and z such that y^3 = a and 3z^3 = b. Therefore, in the set F_5, equation (4) has many non-zero solutions (corresponding to pairs a, b, for which a + b = 0). A similar result is true for F_{11}. Therefore, we have not found, considering equation (3) modulo 5 or 11, to prove that it has only a zero solution.

Consider equation (3) mod 13:

$$\bar{5}x^3 + \bar{11}y^3 = \bar{0}.$$

(5)

In the set F_{13}, only the elements 0, 1, 5, 8, 12 are cubes. Let’s make a table of possible values ​​of the expression $\bar{5}a + \bar{11}b$, where a, b ∈ {0, 1, 5, 8, 12} (the intersection contains the sum $\bar{5}a + \bar{11}b$). The table shows that the only solution to equation (5) is x = y = 0.

This means that for any solution x_0, y_0, z_0, equations (3) x_0 and y_0 are divided by 13: x_0 = 13x_1, y_0 = 13y_1. Substituting these expressions for x_0 and y_0 into (3),

⟦folio 4⟧

we get $5 \cdot 13^3 x_1^3 + 11 \cdot 13^3 y_1^3 + 13 z_0^3 = 0$, from which $z_0$ is divided by 13: $z_0 = 13 z_1$. Substituting and reducing by 13: $5 x_1^3 + 11 y_1^3 + 13 z_1^3 = 0$. It follows that $x_1 = 13 x_2$, $y_1 = 13 y_2$, $z_1 = 13 z_2$, etc. Thus, $x_0, y_0, z_0$ is divisible by any power of 13, which is only possible if $x_0 = y_0 = z_0 = 0$.

**Theorems of Chevalley and Varnin**

Knowing the set $F_{13}$ allows us to inform which comparison model should be chosen to study equation (3).

What happens if the equation has not three variables, but four or five? What happens if the degree of the equation is not 3, but 4, 5 or 6? It is felt that if the number of variables x is notified, then our chances of proving the impossibility of solving the original equation by considering it according to some model are reduced; if its degree is notified, they grow. This intuitive message can be further refined.

The following remarkable Chevalley's theorem is valid: consider the set $R(x_1, x_2, \dots, x_n)$ with coefficients in the set $F_p$; let $x_1 = x_2 = \dots = x_n = 0$ be the solution to equation $R(x_1, x_2, \dots, x_n) = 0$; if the degree of the set $R(x_1, x_2, \dots, x_n)$ is less than n, then the equation $R(x_1, x_2, \dots, x_n) = 0$ has a non-zero solution.

Chevalley's theorem immediately follows from Varnin's theorem: if the degree multiplying $R(x_1, x_2, \dots, x_n) = 0$ is equal to 0 or $\ge p$. But the first case is excluded, since the equation has a zero solution. This means that he has at least p - 1 more solutions.

The proof of Varnin’s theorem is simple and beautiful, so we’ll give it here, but let’s talk first.

**About some amounts equal to zero**

What is the sum $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p$ of all elements of the set $F_p$? Let's multiply all terms by some element $\bar{a}$ from $F_p$, not equal to 0 and 1. Then the sum will be multiplied by the same element: $\bar{a} \bar{b}_1 + \bar{a} \bar{b}_2 + \dots + \bar{a} \bar{b}_p = \bar{a} (\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p)$. On the other hand, when multiplying all the elements of the set $F_p$ by some element ($\neq 0$), we again get all the elements from $F_p$; therefore $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p = \bar{a} (\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p)$. So, $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p = 0$.

What is the sum $\bar{b}_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2$ of the squares of the elements of the set $F_p$? Let's multiply all the elements again by some element $\bar{a} (\neq 0, 1)$. Then the amount, for the same reason as before, remains the same: $(\bar{a} \bar{b}_1)^2 + (\bar{a} \bar{b}_2)^2 + \dots + (\bar{a} \bar{b}_p)^2 = \bar{b}_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2$; on the other hand $(\bar{a} \bar{b}_1)^2 + (\bar{a} \bar{b}_2)^2 + \dots + (\bar{a} \bar{b}_p)^2 = \bar{a}^2 (b_1^2 + \dots + \bar{b}_p^2)$. If $\bar{a}^2 \neq 0, 1$, then $b_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2 = 0$.

And in general: if in the set $F_p$ there is an element $\bar{a}$ such that $\bar{a}^k \neq 0, 1$, then the sum of the $k$ powers of all elements from $F_p$ is equal to 0.

It is clear that if $\bar{a}^k = 1$ for the first polynomial $\bar{a}$ of $F_p$, then even more so $\bar{b}_k = 1$ for all other elements $\bar{b} \neq 0$. If $\bar{a}^k = 1$ if and only if k is divisible by p - 1. In particular, if $0 < k < p - 1$, then $\bar{a}^k \neq 1$ and the sum of the kth powers is equal to 0. Since $\bar{0}^{p-1} + \bar{1}^{p-1} + \dots + \bar{p-1}^{p-1} = \bar{p-1}$ and $x^p = x$ for $x \in F_p$ (Fermat’s Little Theorem), we found the sum of the kth powers of the elements from $F_p$ for any k ≠ 0:

$$\bar{b}_1^k + \bar{b}_2^k + \dots \bar{b}_p^k =$$

$$= \begin{cases} 0, \text{ если } k \neq 0 (\text{mod } p - 1), \\ p - 1, \text{ если } k \equiv 0 (\text{mod } p - 1) \text{ и } k \neq 0. \end{cases}$$

⟦folio 5⟧

Let us now consider some monomial $q = x_1^{k_1} x_2^{k_2} \dots x_t^{k_t}$ and all possible ordered sets $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$, where $\bar{c}_i \in F_p$ ($i = 1, 2, \dots, n$). There are $p^n$ such sets. We will assume that $t \leq n$. then for each set we can calculate the value of the monomial $q$, we accept on this set: we need to substitute the first $t$ numbers of the set instead of $x_1, x_2, \dots, x_t$. What is the sum of all these $p^n$ values? (The problem we solved about the sum of $k$ powers is a special case of this problem: $q = x_1^k, n = 1$.) We leave the reader to explore this issue.

For what follows we only need that if $t < n$ or $0 < k_i < p - 1$ for some $i$, then excluding the sum is $0$. You can easily prove this yourself.

Proof of Waring's theorem

Let us denote the degree of the polynomial $R(x_1, x_2, \dots, x_n)$ by $m$, and the number of solutions of the equation $R(x_1, x_2, \dots, x_n) = 0$ by $N(R)$. We need to deduce from condition $m < n$ that $N(R)$ is divisible by $p$.

In the set $M$ of all possible ordered sets of elements from $F_p$ of length $n$ consider the subset $M_R$ of solutions to the equation $R(x_1, x_2, \dots, x_n) = 0$. The subset $M_R$ consists of the sets $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ for which $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = 0$.

Consider the function $f_R$, which assigns to each element $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \in M$ the number 1 if $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \in M_R$, and the number 0 if $c \langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \notin M_R$.

(A function defined on some set $M$ and taking the value 1 on some subset $A \subset M$ and the value 0 on the remaining elements of $M$ is called the characteristic function of the subset $A$. Thus, the function $f_R$ is the characteristic function of the subset $M_R$.) From the very definition of the function $f_R$ it follows that the number of solutions $N(R)$ of the equation $R(x_1, x_2, \dots, x_n) = 0$ is equal to the sum of the values of the function $f_R$ over all elements of the set $M$. This statement would seem to add nothing to the definition of $f_R$. However, the reader will see that replacing the set $M_R$ with the function $f_R$ is key to the proof.

Let us now consider the function $f_R$, which differs from the function $f_R$ in that instead of the numbers 1 and 0, it takes on the solution and non-solution of the corresponding values ​​$\bar{1}$ and $\bar{0}$ from $F_p$. The sum of $S(\bar{f}_R)$ values ​​of the function $f_R$ over all sets $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ is equal to the residue class $N(R)$ (mod $p$) of the number $N(R)$. Therefore, to prove Waring’s theorem, it is enough to verify that $S(\bar{f}_R) = \bar{0}$.

Using Fermat's Little Theorem, we represent the function $f_R$ as a polynomial. To do this, consider the polynomial $Q(x_1, x_2, \dots, x_n) = \bar{1} - R(x_1, x_2, \dots, x_n)^{p-1}$. If $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) \neq 0$, then Fermat’s Little Theorem $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{0}$. If $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{0}$, then $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n)^{p-1} = \bar{0}$ and $Q(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{1}$. Therefore $f_R = Q$.

The polynomial $Q(x_1, x_2, \dots, x_n)$ is the sum of the monomials: $Q = q_1 + q_2 + \dots + q_l$.

It is enough for us to check that the sums of the values ​​of each of the monomials $q_1, q_2, \dots, q_l$ over all sets $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ are equal to $\bar{0}$. Then the sum of $S(f_R) = S(Q)$ will be equal to $\bar{0}$, since $S(Q) = S(q_1) + S(q_2) + \dots + S(q_l)$.

Take, for example, the monomial $q_1 = x_1^{k_1} x_2^{k_2} \dots x_t^{k_t}$. The degree of the polynomial $Q$ is equal to $(p - 1) m$. Therefore, the degree of the monomial $q_1$ is less than $(p - 1) n$ (by the conditions of Theorem $m < n$). So, $k_1 + k_2 + \dots + k_t < (p - 1) n$. From this inequality it follows that either $t < n$ or among $k_1, k_2, \dots, k_t$ there is an exponent $k_i$ for which $0 < k_i < p - 1$. The equality $S(q_1) = \bar{0}$ now follows from the result formed at the end of the previous section.

Weyl-Lang theorem

We have already said above that if diophant equations have a solution

⟦folio 6⟧

nitsa, then any given equation (by any simple modulo $p$) also has a solution.

The statement: “If a Diophantine equation has a non-zero solution, then any given equation has a non-zero solution” is not true. For example, the equation
$$x^2 + y^2 = 9 = 0$$
has a non-zero solution ($x = 3, y = 0$), but modulo 3 the given equation
$$x^2 + y^2 = 0$$
has no such solutions.

Nevertheless, it is clear that if the Diophantine equation has a non-zero solution, then for all $p$, starting from some, the given equation also has a non-zero solution.

The converse is not true: Eq.
$$x^2 + y^2 + z^2 = 0$$
(6)
by Chevalley’s theorem has a non-zero solution in the limit $F_p$, and the equation
$$x^2 + y^2 + z^2 = 0$$
has no non-zero solutions (not only in $Z$, but also in $R$ *).

Let us now consider again the Diophantine equation
$$R(x_1, x_2, \dots, x_n) = 0$$,
whose coefficients are integers. It is interesting to know what is the set of those primes $p$ for which there is a solution mod $p$. The answer to this question is given by the remarkable Weil-Lang theorem. If the set $R(x_1, x_2, \dots, x_n)$ is an absolute reduction, then the equation $R(x_1, x_2, \dots, x_n) = 0$ has a solution by simple modulo $p$ for all $p$, starting from some.

By absolute reduction by a polynomial we mean a polynomial that cannot be expanded into a product of two polynomials modulo $p$ for all $p$, starting from some.

*) This is not a very interesting example: the reader can check that, modulo 8, equation (6) does not have non-zero solutions. In the mentioned article by M.I. Bashmakov, an example of a Diophantine equation ($3x^3 + 4y^3 + 5z^3 = 0$) is given that does not have non-zero solutions, for which the reduction equation does not have a non-zero solution modulo $p$.

The condition of absolute irreducibility in the formulation of the theorem is essential: from tasks 2 to the article “Comparison by simple modulo” it follows that the equation $x_1^2 + x_2^2 = 0$ is solvable for $p = 4k + 1$ and unsolvable for $p = 4k + 3$. There are many prime numbers of the form $p = 4k + 3$ infinite, so the conclusion of the theorem for the polynomial $x_1^2 + x_2^2$ is not true. Of course, the premise is also false for him: from the solvability of the equation $x_1^2 + x_2^2 = 0$ modulo $p = 4k + 1$ (and there are also infinitely many prime numbers of this type) it follows that it is factorizable with respect to this modulo.

It can be proven that the "vast majority" of polynomials are absolutely irreducible.

Unlike Waring's theorem, the proof of the Weyl-Lang theorem is very difficult in the general case.

Let's consider one very special case of the equation $R(x_1, x_2, \dots, x_n) = 0$: when the polynomial $R$ is of the first degree: $R(x_1, x_2, \dots, x_n) = a_1x_1 + a_2x_2 + \dots + a_nx_n + b$ (although one of the coefficients $a_i$ is assumed to be different from 0). It is easy to see that in this case $N(R) = p^{n-1}$. Indeed, we can assume (rearranging, if necessary, unknown ie) that $a_1 \neq 0$; then, giving $x_2, \dots, x_n$ all possible values ​​from $F_p$ and putting $x_1 = -a_1^{-1}(a_2x_2 + \dots + a_nx_n + b)$, we get the solution.

The Weyl–Lang theorem can be refined: for large $p$
$$|N(R) - p^{n-1}| < c \cdot p^{\frac{n-1}{2}},$$
where $c$ is the coefficient number, depending on the polynomial $R$.

Weyl's initial proof is based on the deep connections he discovered between seemingly distant questions: the discrete, and even finite, problem of the number of solutions to the equation $R(x_1, x_2, \dots, x_n) = 0$ in a simple modulo and the geometric structure of the continuous polynomial of complex solutions of this equation, that is, those sets of complex numbers $\langle d_1, d_2, \dots, d_n \rangle$ for which $R(d_1, d_2, \dots, d_n) = 0$.

Recently, an elementary (no indirect methods were used), but nevertheless very complex proof of the Weyl-Lang theorem for the Sverldov mathematician S. A. Stepanov.
