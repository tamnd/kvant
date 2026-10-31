---
id: 1976-1-haplanov-transtsendentnyie-chisla-7f19f713
issue: kvant_1976_1
year: 1976
number: "1"
title: Transcendental numbers
authors:
  - Хапланов М. Г.
rubric: osnovnye-stati
page_first: 26
page_last: 29
page_labels: 24-27
tag: OA6W
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 7f3ef1052f1f236290d39454233fc656e645db4bccf7e9c5e142a746c6552131
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/06_haplanov-transtsendentnyie-chisla-7f19f713.md
source_content_sha256: 7043e2607631f2d2c5b0d672b3fac3899b057728e3d5daa8387695d921d8b2d4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Transcendental numbers

The concept of *number* has been formed over thousands of years. And only two hundred years ago - primarily in the works of L. Euler (1707-1783) - complex numbers entered mathematics, and the development of the concept of number was completed.

Let us recall the stages (non-chronological) of this development:

1. *natural numbers* 1, 2, 3, $\ldots$;
2. *integers* $\ldots$, $-3$, $-2$, $-1$, 0, 1, 2, 3, $\ldots$;
3. *rational numbers*, i.e. numbers of the form $\dfrac pq$, where $p$ is an integer, $q$ is a natural number;
4. *real numbers*, i.e. numbers expressed in infinite decimal fractions;
5. *complex numbers*, i.e. numbers of the form $a+bi$, where $a$ and $b$ are real numbers, and the symbol $i$ is determined by the condition $i^2=-1$.

In this sequence, each subsequent class contains all the numbers of the previous class and additionally “new” numbers. With each expansion of the class of numbers, we acquire the ability to perform in all cases certain actions that are not always feasible in “old” numbers. Thus, in the class of integers, subtraction is always feasible, and in the class of rational numbers, in addition, division is always feasible; in the class of real numbers, not only four arithmetic operations are always feasible, but - for positive numbers - extracting the root, and in general raising to any real power, as well as finding the logarithm. Finally, as Gauss (1777–1855) proved in 1799, *algebraic equations* of any degree are always solvable in complex numbers: equation
$$
a_0z^n+a_1z^{n-1}+\ldots+a_n=0,\tag1
$$
where $n$ is a natural number and the coefficients are complex, has $n$ complex roots. Even earlier (1748), Euler constructed the theory of exponential, logarithmic, trigonometric and their inverse functions of a complex argument.

In this article we will look at another classification of numbers, namely, dividing them into *algebraic* and *non-algebraic* (otherwise - *transcendental*).

Definition. *A number is called algebraic if there is an algebraic equation with integer coefficients whose root it is.*

We emphasize that in order for a number to be algebraic, the equation (1) that it satisfies must have integer coefficients (or can be reduced to such an equation).

Obviously, rational numbers are algebraic: $\dfrac pq$ is the root of the equation $qz-p=0$ with integer coefficients $q$ and $-p$. Algebraic numbers are the roots of quadratic equations with integer coefficients, for example: the number $i$ (the root of the equation $z^2+1=0$), the number $-\sqrt5-1$ (the root of the equation $z^2+2z-4=0$), the number $1-i\sqrt5$ (the root of the equation $z^2-2z+6=0$).

### Do transcendental numbers exist?

The question naturally arises: are there transcendental numbers at all?

A positive answer to it was given in 1844 by the French mathematician Liouville (1809-1882). In 1873, Hermite proved the transcendence of the number $e$, in 1882 Lindemann - the transcendence of the number $\pi$. In 1900, at the II International Congress of Mathematicians in Paris, D. Hilbert (1860-1940), among the 23 problems he posed and became famous, formulated the seventh problem: *are numbers of the form $\alpha^\beta$ transcendental, where $\alpha$ is an algebraic number different from zero and one, and $\beta$ is an irrational one algebraic number*?

A positive answer to this question was given in 1934 by the outstanding Soviet mathematician A. O. Gelfond (1906-1968).

### Liouville results

In what follows, we will assume that algebraic and transcendental numbers are real, although everything remains true for complex numbers (see exercises at the end of the article).

Theorem 1. *Let $\alpha$ be an irrational number that is the root of the equation*
$$
f(z)\equiv a_0z^n+a_1z^{n-1}+\ldots+a_n=0.\tag2
$$
*Using the coefficients of the equation and an arbitrary $A\ge|\alpha|$, one can find a number $M$ such that for any fraction $\dfrac pq$, $\left|\dfrac pq\right|\le A$ that is not a root of equation (2), the following inequality is true*
$$
\left|\alpha-\dfrac pq\right|\ge\dfrac1{Mq^n}.\tag3
$$

Proof. According to the conditions of the theorem we have:
$$
\begin{gather*}
f(\alpha)=a_0\alpha^n+a_1\alpha^{n-1}+\ldots+a_{n-1}\alpha+a_n=0,\\
f{\left(\dfrac pq\right)}=a_0{\left(\dfrac pq\right)^n}+a_1{\left(\dfrac pq\right)^{n-1}}+
a_{n-1}\dfrac pq+a_n\ne0.
\end{gather*}
$$
From here
$$
\begin{gather*}
f{\left(\dfrac pq\right)}=f{\left(\dfrac pq\right)}-f(\alpha)=a_0{\left[{\left(\dfrac pq\right)^n}-\alpha^n\right]}+a_1{\left[{\left(\dfrac pq\right)^{n-1}}-\alpha^{n-1}\right]}+
\ldots+a_{n-1}{\left(\dfrac pq-\alpha\right)}=\\
={\left(\dfrac pq-\alpha\right)}{\left\{a_0{\left[{\left(\dfrac pq\right)^{n-1}}+
{\left(\dfrac pq\right)^{n-2}}\alpha+\ldots+\dfrac pq\alpha^{n-2}+\alpha^{n-1}\right]}+{}\right.}\\
{\left.{}+a_1{\left[{\left(\dfrac pq\right)^{n-2}}+{\left(\dfrac pq\right)^{n-3}}\alpha+\ldots+\alpha^{n-2}\right]}+\ldots+a_{n-1}\right\}}.
\end{gather*}
$$
Since $|\alpha|\lt A$, $\left|\dfrac pq\right|\le A$, then $$
\left|f{\left(\dfrac pq\right)}\right|\le{\left|\dfrac pq-\alpha\right|}M,\tag4
$$
where $$
M=|a_0|nA^{n-1}+|a_1|(n-1)A^{n-2}+\ldots+|a_{n-1}|.\tag5
$$
But $$
\left|f{\left(\dfrac pq\right)}\right|=\dfrac{|a_0p^n+a_1p^{n-1}q+\ldots+a_nq^n|}{q^n}.\tag6
$$

In the numerator of the fraction (6) $a_0$, $a_1$, $\ldots$, $a_n$, $p$, $q$ are integers, so the numerator (6) is an integer, and since $f{\left(\dfrac pq\right)}\ne0$, it is not less than one. Hence,
$$
\left|f{\left(\dfrac pq\right)}\right|\ge\dfrac1{q^n}.\tag7
$$
From (4) and (7) follows (3). The theorem has been proven.

Theorem 2. *Number*
$$
\alpha=c_0+\dfrac{c_1}{10}+\dfrac{c_2}{10^{2!}}+\dfrac{c_3}{10^{3!}}+\ldots+\dfrac{c_k}{10^{k!}}+{\ldots},
$$
*where $c_0$ is an arbitrary integer, and $c_1$, $c_2$, $\ldots$ take one of the values* 0, 1, 2, $\ldots$, 9 *and are not equal to zero in a row, starting from a certain point - transcendental.*

Proof. Let's put
$$
c_0+\dfrac{c_1}{10}+\dfrac{c_2}{10^{2!}}+\ldots+\dfrac{c_k}{10^{k!}}=\dfrac pq.\tag8
$$
Then
$$
\alpha-\dfrac pq=\dfrac{c_{k+1}}{10^{(k+1)!}}+\dfrac{c_{k+2}}{10^{(k+2)!}}+\ldots\gt0,
$$
and since $q=10^{k!}$, then $$
\alpha-\dfrac pq=\dfrac{c_{k+1}}{q^{k+1}}+\dfrac{c_{k+2}}{q^{(k+1)(k+2)}}+{\ldots}.
$$
From here
$$
\alpha-\dfrac pq\le9{\left(\dfrac1{q^{k+1}}+\dfrac1{q^{(k+1)(k+2)}}+\ldots\right)}\lt\dfrac9{(q-1)q^k}.\tag9
$$

To prove the transcendence of the number $\alpha$, let us assume the opposite—that it is algebraic; then $\alpha$ satisfies equation (1), the coefficients of which are integers. Let us denote by $d$ the shortest distance from the root $\alpha$ to the other real roots of the equation.

Putting $A=|\alpha|+d$, we calculate the number $M$ using formula (5) and choose the natural number $k$ so large that the following three inequalities are simultaneously satisfied:
$$
k\gt n,\quad\dfrac9{(q-1)q^k}\lt d,\quad\dfrac9{(q-1)q^{k-n}}\lt\dfrac1M.\tag{10}
$$

Due to inequality (9) and the average of conditions (10), $\dfrac pq$ is less than $\alpha$. on $d$, and therefore is not a root of equation (1). Since $$
\left|\dfrac pq\right|=\left|\alpha-\left(\alpha-\dfrac pq\right)\right|\le|\alpha|+\left|\alpha-\dfrac pq\right|\lt|\alpha|+d=A,
$$
then the conditions of Theorem 1 are satisfied, and, consequently,
$$
\left|\alpha-\dfrac pq\right|\ge\dfrac1{Mq^n}.\tag{11}
$$

On the other hand, from inequality (9) and the last of conditions (10)
$$
\left|\alpha-\dfrac pq\right|\lt\dfrac1{Mq^n}.\tag{12}
$$

Thus, the assumption that $\alpha$ is an algebraic number led to contradictory inequalities (11) and (12). Therefore, $\alpha$ is a transcendental number.

So, Theorem 2 allows us to construct transcendental numbers. Namely, a transcendental number can be obtained from any infinite fraction in which not all digits, starting from some, are zeros, using the following method: you need to put the $k$th digit after the decimal point in the place with the number $k!$, and fill the remaining places with zeros. For example, from the number $0{,}314159\ldots$ the following transcendental number is obtained:
$$
\def\A#1{\mathclap{\footnotesize\begin{array}{c}\text{#1-е}\\\text{место}\end{array}}}
\def\colsep#1#2{#2}
\colsep{0pt}{\begin{array}{ccccccc}
0{,}31000&4&0\ldots0&1&0\ldots0&5&0\ldots\\
&\mathclap\downarrow&&\mathclap\downarrow&&\mathclap\downarrow&\\
&\A{6}&&\A{24}&&\A{120}&
\end{array}}
$$

### Conclusion

On the one hand, the real transcendental numbers form part of all real numbers. But the example given at the end of the previous paragraph shows that in a sense there are “as many” transcendental numbers as there are real ones, precisely in the sense that from every real number (except for finite decimal numbers) a transcendental one can be formed.

However, in some other sense *almost all real numbers are transcendental, while algebraic numbers constitute only an insignificant part of real numbers*!

In 1878, the German mathematician G. Cantor (1845-1918) proved that algebraic numbers can be numbered in such a way that each algebraic number will receive its own number, and under each number there will be an algebraic number (see Appendix). Let us take a segment of arbitrarily small length, for example the length $\eps=10^{-15}$ cm (recall that the electron radius is approximately $10^{-12}$ cm). Having depicted real numbers as points on the number line, we cover algebraic point No. 1 with a segment of length $\dfrac12\eps$, algebraic point No. 2 - a segment of length $\dfrac1{2^2}\eps$, algebraic point No.$n$ - a piece of length - $\dfrac1{2^n}\eps$ etc. The sum of the lengths of the covering segments is equal to $\eps$, although they partially overlap each other and cover not only all algebraic numbers, but also some transcendental ones. The entire number axis is infinite, and the sum of the lengths of the segments covering the algebraic points is only a thousandth of the radius of the electron! This clearly shows that almost all numbers are transcendental, while algebraic numbers are rare exceptions.

### Application

Let us call the *rank of equation* (1) the number $r$:
$$
r=n+|a_0|+|a_1|+\ldots+|a_n|;\tag{13}
$$
here $n\ge1$, $|a_0|\ge1$, therefore $r\ge2$.

For each natural number $r\ge2$, the indefinite equation (13) has a finite number of solutions in non-negative integers. Consequently, there is a finite number of equations of each rank. For example, rank 2 - two equations: $\pm x=0$; rank 3 - six equations:
$$
\pm x^2=0,\quad \pm x\pm1=0;
$$
rank 4 - equations
$$
\pm x^3=0,\quad\pm x^2\pm x=0,\quad\pm x^2\pm1=0,\quad\pm x\pm2=0,\quad\pm2x\pm1=0.
$$
Let's find the roots of these equations and write them out one after another: first, the roots of equations of rank 2, then the roots of equations of rank 3, etc.; We write out the roots of equations of the same rank in any order, and if a number is the root of several equations, then we write it out only once. We get a sequence of numbers:
$$
0,~1,~{-1},~i,~{-i},~2,~{-2},~\dfrac12,~{-\dfrac12},
$$
further - roots of equations of rank 5, etc.

Each algebraic number will thus be written out and receive its own serial number in the sequence. If one is only interested in real algebraic numbers, then the complex numbers are omitted.

### Exercises

1. Prove that the number
$$
\alpha=c_0+\dfrac{c_1}2+\dfrac{c_2}{2^{2!}}+\ldots+\dfrac{c_k}{2^{k!}}+{\ldots},
$$
where $c_0$ is an integer, and $c_1$, $c_2$, $\ldots$ take one of the values ​​0 or 1, and are transcendental.
2. Prove that Theorem 2 is also true if the numbers $\{c_k\}$ take any integer values ​​bounded in the aggregate, that is, if there is a constant $B$ such that $|c_k|\lt B$ for all values ​​of the index $k$.
3. Prove that in Theorem 2 we can put
$$
\alpha=c_0+\dfrac{c_1}{10^{n_1}}+\dfrac{c_2}{10^{n_2}}+{\ldots},
$$
where $\{n_k\}$ is any sequence of natural numbers subject to the condition
$$
n_{k+1}\ge\lambda_kn_k,\quad k=1{,}~2{,}~{\ldots},
$$
and $\{\lambda_k\}$ is an arbitrary infinitely increasing sequence of real numbers, for example, $\lambda_k=\lg k$.

In the following exercises, by *integer complex number* we mean a number of the form $a+bi$, by *rational complex* we mean the number $\dfrac{a+bi}q$, where $a$, $b$ are integers, $q$ is a natural number, and $i$ is such that $i^2=-1$.

1. Prove that if the number $\alpha$ satisfies equation (1) with complex integer coefficients, then it is algebraic.
2. Prove that Theorem 1 is true if, under its conditions, $\alpha$ is a complex irrational number and $\dfrac pq$ is a complex rational number.
3. Prove that Theorem 2 and statements in exercises 1, 2, 3 are also valid when the coefficients $\{c_k\}$ take complex integer values.
