---
id: 1978-11-geronimus-sravneniya-po-prostomu-modulyu-217c4b56
issue: kvant_1978_11
year: 1978
number: "11"
title: Comparisons modulo prime
authors:
  - Геронимус А. Ю.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
tag: M5KF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7eee40bcafa5589b20ea4c8d6fe5378b5313eec574f28837f0cb95e2a40ea3b2
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/04_geronimus-sravneniya-po-prostomu-modulyu-217c4b56.md
source_content_sha256: 0c75e16e721ef0ca27465aaa84f1465f6be23b084a0e0b940d5b381b2315ba55
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

Comparisons modulo prime

In the article “Comparisons and classes of residues”*) the set $F_m$ of residue classes modulo $m$ was considered and three operations were defined - addition, subtraction and multiplication classes. There it was proven that in the case when the comparison model is a prime number, division by any non-zero class can be defined. Thanks to this comparison with a simple modulo, they have a number of interesting and subtle properties that comparisons with an arbitrary modulo do not have. We will introduce some of these properties here. In what follows, we will always assume that the model is a prime number; so as not to forget about this, we will denote it by $p$.

Existence of a primitive root

Let us call the order of the residue class $\bar{a} \in F_p$ the smallest natural number $k$ for which $\bar{a}^k = 1$. At the end of the article “Comparisons and classes of residues” it was said that in the set $F_p$ there is a class whose order is $p-1$. A class with this property is called a primitive root. The theorem about the existence of such a class was first proven by Legendre (1752-1833). Let us present a proof of Legendre's theorem, close to Legendre's own proof.

*) See «Kvant» No. 10.

Let us first prove that if the orders $l$ and $m$ of two classes $\bar{a}$ and $\bar{b}$ are coprime, then the order of the product $\bar{a}\bar{b}$ is equal to $lm$. Indeed, $(\bar{a}\bar{b})^{lm} = \bar{a}^{lm} \cdot \bar{b}^{lm} = (\bar{a}^l)^{m} \cdot (\bar{b}^m)^{l} = 1$ (since $\bar{a}^l = 1$ and $\bar{b}^m = 1$). The class order $\bar{a}\bar{b}$ must therefore be a divisor of the number $lm$. Let's denote it by $l'm'$, where $l'$ is the divisor of $l$, and $m'$ is the divisor of $m$ (l and m are coprime!)*. So,

$$\bar{a}^{l'm'} \cdot \bar{b}^{l'm'} = (\bar{a}\bar{b})^{l'm'} = 1.$$

Let us raise both sides of this equality to a power $l''$ such that $l'l'' = l$. Popular then is $(\bar{a}^l)^{m'} \cdot \bar{b}^{lm'} = 1$, and since $l$ is the order of $\bar{a}$, then $(\bar{a}^l)^{m'} = 1$ and therefore $\bar{b}^{lm'} = 1$. This means that $lm'$ is divisible by $m$ (order $\bar{b}$), but $l$ is coprime with $m$, and $m'$ is a divisor of $m$, so $m' = m$, similar to $l' = l$; our statement has been proven.

Let us now move directly to the theorem.

Consider the class $\bar{a}$ with the most possible order $N$. We want to prove that this is the primitive root. To do this, it is sufficient to verify that any other class $\bar{b}$ is a power of $\bar{a}$. Suppose the order of $\bar{b}$ is equal to $n$. There are two possible cases at $n$. Let's consider $n$ classes $\bar{a}^k \cdot N/n$ with $0 \leq k < n$. They are all different roots of degree $n$ of ones, i.e. solutions to the equation $\bar{x}^n - 1 = 0$ (check). The class $\bar{b}$ is also a root of the power $n$ of units by definition of order. In the appendix to this article we will prove that any polynomial of degree $n$ with coefficients of $F_p$ and, in particular, a polynomial $\bar{x}^n - 1$ cannot have more than $n$ roots. Therefore, $\bar{b}$ is one of the elements of $\bar{a}^k N/n$, that is, it is a power of $\bar{a}$.

2) $N$ is not divisible by $n$. Let $r$ be the most possible common divisor of $N$ and $n$.

*) The possibility of such a representation of an arbitrary number $lm$ follows from the Fundamental Theorem of Arithmetic, proven in the appendix to this article.

⟦folio 7⟧

The order of class $\bar{b}^r$ is $n/r$ (check). The numbers $N$ and $n/r$ are coprime. Therefore the order of class $\bar{ab}^r$ is $N \cdot n/r > N$. This contradicts the maximality of $N$. The second case is impossible.

The theorem on the existence of the first root has been proven.

Artin's conjecture

The above proof is not constructive: we cannot indicate explicitly which of the residues $\bar{1}$, ..., $\bar{p-1}$ is a primitive root modulo $p$.

The American mathematician E. Artin (1898–1962) put forward the following conjecture: if the integer $n$ is not a perfect square, then there are an infinite number of prime numbers $p$ for which the class of residues mod $p$ containing $n$ is a primitive root mod $p$. This hypothesis has not yet been proven. If we could explicitly specify the primitive roots mod $p$ for all $p$, it would be easy to find out whether this conjecture is true. (Check that if $n=m^2$ is for some $m$, then the prime numbers $>2$ mentioned in the conjecture do not exist at all.)

Root extraction

Legendre's theorem allows us to find out when roots can be extracted in the set $F_p$.

It is natural to call a root of degree $n$ from the residue class $\bar{b}$ a class $\bar{x}$ such that $\bar{x}^n = \bar{b}$.

Let $\bar{a}$ be some primitive root in $F_p$. There is a natural number $k$ such that $\bar{b} = \bar{a}^k$. If, according to $\bar{x}^n = \bar{b}$, $\bar{x}$ is replaced by $\bar{a}^y$, then it can be rewritten as $\bar{a}^{yn} = \bar{a}^k$ or $\bar{a}^{yn-k} = \bar{1}$.

From the last match we can see that $yn-k$ is divisible by $p-1$.

This divisibility is equivalent to the following equality in the set $F_{p-1} : \bar{yn} = k$.

Conversely, if $\bar{m}$ in the set $F_{p-1}$ is a solution to the equation $\bar{yn} = \bar{k}$, then $\bar{a}^m$ is the root of the power $n$ of $\bar{b}$ (in $F_p$).

Thus, we reduced the problem of extracting roots in the set $F_p$ to the problem of division in the set $F_{p-1}$.

In the article “Comparisons and classes of residues” it was stated that if $d$ is the most common divisor of the numbers $n$ and $p-1$ and $k$ is divisible by $d$, then the equation $\bar{yn} = \bar{k}$ has exactly $d$ solutions; if it is not divisible, then equation $\bar{yn} = \bar{k}$ has no solutions at all.

Now the question about roots of degree $n$ from the class of residues $\bar{b}$ is completely clear:

Theorem. If index*) $k$ of class $\bar{b} \in F_p$ is divided by the most common divisor $d$ of numbers $n$ and $p-1$, then there is a dynamic stem $n$ from class $\bar{b}$; in the other case, it is impossible to extract the root stem $n$ from class $\bar{b}$.

Example: $p = 11$.

Let us write down all the stems of class $\bar{2}$ in the set $F_{11}$. In Table 1, the first line contains the stele indicator, in which you need to build $a$ to get $\bar{b}$. In the formulation of the theorem, it does not exist which antiderivative root is chosen.

*) Let us recall (see «Kvant» No. 10, p. 8) that the index of the class $\bar{b}$ to the base $\bar{a}$ (hereinafter referred to as the primitive root) is the exponent of the stem in which $a$ must be raised to obtain $\bar{b}$. In the formulation of the theorem, it does not exist which antiderivative root is chosen.

**) The easiest way is to calculate the stems of a two (or other element) sequentially: $\bar{2}^k = \bar{2}.\bar{2}^{k-1}$; first erecting 2 in column $k$, and then bringing mod 11 is a more labor-intensive task.

⟦folio 8⟧

met, for example, class 3. Its index is 8. We need to solve the equation $3y=8$ in the set $F_{10}$. We will multiply all classes in $F_{10}$ by 3 (Table 2). From the table it is clear that from

$$\begin{array}{c|cccccccc}
k \in F_{10} & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 0 \\
\hline
3k \in F_{10} & 3 & 6 & 9 & 2 & 5 & 8 & 1 & 4 & 7 & 0
\end{array}$$

vet - 6, which means that in the set $F_{11}$ $2^6=9$ is the cube root of 3. Indeed, $9^3=3$.

Let now $n=5$, then $d=5$ and from all classes except classes 1 and 10 (with indices 10 and 5), the root of degree 5 is not extracted. Let us first find roots of degree 5 from 1. It is easy to say that these are all classes with four indices. (Indeed, the class with the fourth index 2r is equal to $2^2r$; $(2^2r)^5=(2^r)^{10}=1$ by Fermat’s little theorem for $p=11$.) There are a lot of such classes, the fifth ones are 1, 3, 4, 5 and 9. According to the theorem, in the set $F_{11}$ there should be a fifth root of degree 5 of 1.

Let us now deal with roots of degree 5 out of 10. One such root can be seen from the table - this is 2, indeed, $2^5=10$. To get all the roots, we need to multiply 2 by all the roots of degree 5 of 1 that we have already found. Indeed, if $x^5=1$, then $(2x)^5=2^5\cdot x^5=10\cdot 1=10$. Answer: classes 2, 6, 7, 8, 10, that is, all classes with four indices. The fact that 10 is a root of the power of 5 of itself is not surprising - after all, $10=-1$.

Square deductions and non-deductions

Let us now consider a special case - extracting square roots. First of all, we need to consider the most common divisor $d$ of the numbers 2 and $p-1$. If $p=2$, then $d=1$; if $p>2$, then $p$ is odd, so $p-1$ is even and $d=2$. Let's consider the case of odd $p$ (you can easily study the case $p=2$ yourself). We found out that a square root can be taken from a class with a four index (and there will be two of them for each class), but a square root cannot be taken from a class with a four index. Classes with four indices are called square residues, and those with odd indices are called square non-residues. Since among all possible index values ​​from 1 to $p-1$ there are $\frac{p-1}{2}$ even numbers and $\frac{p-1}{2}$ odd numbers, then among the $p-1$ non-sensory classes of square residues and square non-residues there are equal numbers. It is also interesting that the product of a deduction by a deduction or a non-deduction by a deduction gives a square deduction, and the product of a square deduction by a deduction gives a non-deduction. This follows from the fact that when classes change, their indices add up. Similar statements are true for the particular. For example, the quotient of non-deduction divided by non-deduction is necessarily a square deduction.

Let's turn again to $p=11$. Square residues are elements with four indices, that is, all classes with four indices, that is, all roots of degree 5 of 1. This hidden symmetry occurs for all $p$, not just for $11^*$).

Rational and irrational classes of residues

So, not all classes can be rooted. For example, the square root, as we have seen, can only be taken from the positive of non-sensory classes.

This phenomenon also occurs for general numbers. You are well aware that in the field of rational numbers the number 2, for example, cannot be taken as a square root. Do you know-

*) You can read about square deductions and non-deductions in «Kvant» No. 1 for 1973 (p. 2-9).

⟦folio 9⟧

also that if we expand the set of rational numbers and consider the set $R$ of all real numbers, then in this larger set we can extract the square root of the number 2, and $\sqrt{2}$ is a number from the set $R$, only irrational.

Let's do the same with the deduction classes. For clarity, consider $p=11$ again. We have seen that class $\overline{2}$ is a square non-residue; the square root cannot be extracted from it. Let us construct a large set $G \supset F_{11}$ in which there will be a square root of the class $\overline{2}$, that is, an element $\alpha$ such that $\alpha^2=\overline{2}$.

In the same way as with geometric constructions, we will carry out an analysis. First of all, let us clarify the statement of the problem. For the equality $\alpha^2=\overline{2}$ to make sense, it is natural to assume that for any pair of elements of the set $G$ their product is defined. We also require that the sum of any two elements in the set $G$ be determined. In this case, $G$ must contain all possible two elements $\overline{a}+\overline{b}\alpha$, where $\overline{a}, \overline{b} \in F_{11}$. It turns out that this is already quite enough. We can usually determine the sum of two lenins: $(\overline{a}+\overline{b}\alpha) + (\overline{c}+\overline{d}\alpha) = (\overline{a}+\overline{c}) + (\overline{b}+\overline{d})\alpha$. For example, $(\overline{5}+\overline{2}\alpha) + \overline{9}\alpha=5$.

When multiplying, terms with $\alpha^2$ appear. We will replace $\alpha^2$ with $\overline{2}$. For example, $(\overline{3}+\overline{7}\alpha)(\overline{5}+\overline{2}\alpha) = \overline{3}\cdot\overline{5} + (\overline{7}\cdot\overline{5}+\overline{2}\cdot\overline{3})\alpha + \overline{2}\cdot\overline{7}\alpha^2 = 10+\overline{8}\alpha$.

There are as many elements $\overline{a}+\overline{b}\alpha$ in the set $G$ as there are pairs $\overline{a}, \overline{b} \in F_{11}$, that is, $11^2=(121)$. Therefore, the designation $F_{11^2}$ is adopted for it. There is no need for this set with a set of $F_{121}$ residue classes modulo 121, which also has 121 elements. Unlike $F_{121}$, in $F_{11^2}$ there is a quotient of $\overline{a}+\overline{b}\alpha$ divided by $\overline{c}+\overline{d}\alpha$ unless $\overline{c}$ and $\overline{d}$ are both equal to zero. This statement is proven in two stages. First, consider the case when $\overline{d}=0$. It's easy to check that $(\overline{a}+\overline{b}\alpha) : c = \overline{a}/\overline{c} + (\overline{b}/\overline{c})\alpha$. The general case is

This can be achieved by multiplying the dividend and the divisor by $\overline{c}-\overline{d}\alpha$. Then you have to divide by $\overline{c}^2-2\overline{d}^2$. This set element $F_{11}$ is distinct from zero, otherwise we would have $\overline{c}^2=2\overline{d}^2$, $\overline{2}=\left(\frac{\overline{c}}{\overline{d}}\right)^2$, and $2$ would be a square residue in $F_{11}$. Therefore division is possible.

In the set $F_{11^2}$ the square roots are known not only from $\overline{2}$, but also from all classes $\overline{r} \in F_{11}$. Indeed, if $\overline{r}$ is a square residue, the square root is already taken at $F_{11}$. If $\overline{r}$ is a non-residue, then, as we saw earlier, the quotient of $\overline{r}$ divided by $\overline{2}$ is a quadratic residue and therefore there is a class $\overline{s}$ such that $\overline{r}=2\overline{s}^2$. In this case $\sqrt{\overline{r}}=\sqrt{2}\cdot\overline{s}^2=\overline{s}\alpha$.

In a similar way, we can construct $F_{p^2}$ for an arbitrary $p$. In connection with the knowledge of roots of higher degrees, sets $F_{p^3}, F_{p^4}$, etc. arise. The set $F_{p^2}$ has a primitive root, that is, an element of the maximum possible order $p^2-1$. It is interesting that we have actually already proven this statement: when proving Legendre’s theorem, we use only the existence of four actions and the finiteness of the set under study.

Task and

1. Find all antiderivative roots in the set $F_{13}$.
2. The equation $\overline{x}^2+\overline{y}^2=0$ has a solution in the set $F_p$ ($p>2$) other than $\overline{x}=\overline{y}=0$ if and only if the remainder of $\overline{p}$ divided by 4 is 1.
3. How many solutions does the equation $\overline{x}^2-\overline{5x}+7=0$ have in the set $F_5$? and in $F_7$?
4. How many elements are cubes in $F_{13}, F_5, F_{11}$, in $F_p$? k-min degrees?
5. How many primitive roots are there in the set $F_p$?
6. How many elements in the set $F_{11^2}$ are squares?

Application

Fundamental Theorem of Arithmetic

Any natural number $n>2$ can be represented as a product of prime factors; with a monoview up to the order of multiplicities, a single view can be represented.

A. First, using the method of mathematical induction, we prove the existence
