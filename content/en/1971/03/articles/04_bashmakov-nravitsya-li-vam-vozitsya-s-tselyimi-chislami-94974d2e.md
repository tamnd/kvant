---
id: 1971-3-bashmakov-nravitsya-li-vam-vozitsya-s-tselyimi-chislami-94974d2e
issue: kvant_1971_3
year: 1971
number: "3"
title: Do you like messing around with integers?
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 17
page_last: 21
page_labels: 15, 16, 18, 19
tag: WS2Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: b4dd53f7bebaf68e01fb5557fafa236572ac66d9122caa406fdf1e0257ddb7a8
prompt_sha256: draft-1
translated_from: content/ru/1971/03/articles/04_bashmakov-nravitsya-li-vam-vozitsya-s-tselyimi-chislami-94974d2e.md
source_content_sha256: 23b2b7204b415096747188034949eec838d594a8215621c8e80ad4e28c166e88
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

DO YOU LIKE FUCKING?
WITH WHOLE NUMBERS?

M. I. Bashmakov

Several schoolchildren were asked to answer the following question:
Find out whether the equality $3^{100} + 7^{100} = 8^{100}$ is true or false.
After a few minutes they all replied that this equation was false.
Here are the most typical obligations.

1) Let's look at the last digit of the numbers on the right and left. 3 squared is 9, 3 cubed ends in 7, in the fourth power ends in 1, in the fifth power ends in 3, in the sixth power ends in 9, etc. After four powers, the last digit is repeated, so the number $3^{100}$ has the same last digit as $3^4$, that is, 1. In the same way, it is easy to assume that the last digit of $7^{100}$ is also 1, and $8^{100}$ is 6. So, the last digit of the number is 2, and the last digit on the right is 6. Therefore, the numbers on the left and right are different.

2) $3 + 7$ is greater than 8. But $3^2 + 7^2 = 58$ is less than $8^2 = 64$. Next, $3^{100} + 7^{100} = (3^2)^{50} + (7^2)^{50} < (3^2 + 7^2)^{50} = 58^{50} < 64^{50} = 8^{100}$. We found that the number on the left is less than on the right.

3) The number on the left is divisible by 2, but not divisible by 4. Indeed, any odd number squared gives a remainder of one when divided by 4: $(2n + 1)^2 = 4n^2 + 4n + 1$. The sum of two such numbers $(3^{50})^2 + (7^{50})^2$ gives a remainder of 2. On the right is a number divisible by 4.

Is the evidence given similar to each other? It is easy to notice the similarity of the first and third: in both, the remainders from division by some integer are compared, in one - by 10 (the last digit), and in the other - by 4. But finding an analogy between this proof and the second is not at all so easy. We will try to calculate it at the end of this article. For now, let's learn how to apply the first method of reasoning to some other problems.

Computations “modulo”

Problem a 1. Prove that the equation $x^3 = 2 + 3 y^2$ has no solutions in integers.

Let us consider this equation “modulo 9”, that is, up to terms that are multiples of division *). Since each integer $x$ has the form $3n$, $3n - 1$ or $3n + 1$, where $n$ is an integer, $a(3n \pm 1)^3 = 27n^3 \pm 27n^2 + 9n \pm 1 = 9k \pm 1$, where $k$ is an integer, then any number cubed is either divisible by 9, or leaves a remainder of 1 or 8 when divided by 9.

*) In general, two integers $a$ and $b$ are said to be comparable modulo $k$ if the difference $a - b$ is divisible by $k$. For those who are not familiar with this concept, we advise you to look at the article by A. A. Egorov “Arithmetic of remainders” in «Kvant» No. 5, 1970.

Likewise, since $3(3n \pm 1)^2 = 27n^2 \pm 18n + 3$,

$3y^2$ gives a remainder of 0 or 3 when divided by 9. So, the right side of our equation modulo 9 can only equal 2 or 5, and the left side can only equal 0, 1 or 8, so they cannot coincide for any purpose. The modulo calculations themselves are easy to do. Let us formulate the basic rule of these calculations: if, when adding (or multiplying), we replace numbers comparable to them in terms of

⟦folio 16⟧

modulo $k$, then we obtain a number comparable to the sum (or product) modulo $k$. In other words, in an equality in which the operations of addition and multiplication function, we can replace numbers with modulo $k$ comparable to them whenever in the answer we are interested only in the remainder of division by $k$.

The fact that $a$ and $b$ are comparable modulo $k$ is written as follows: $a \equiv b \pmod{k}$. The rules for operations on comparisons can be written as follows:

$$\text{если } \begin{cases} a \equiv b \pmod{k}, \\ c \equiv d \pmod{k}, \end{cases}$$

$$\text{то } \begin{cases} a + c \equiv b + d \pmod{k}, \\ ac \equiv bd \pmod{k}. \end{cases}$$

Recall that by definition, $a \equiv b \pmod{k}$ means that $a - b = k \cdot q^*$.

Will engage in such a rather artificial task.

Task 2. Prove that the equality $1153^{60} + 211^{60} = 27027 \cdot 100^x + 2$ is impossible for any integer $x$.

It is clear that if for some modulus we do not obtain equality, then it cannot exist in the general sense. Modulo 2 there is no contradiction - there are even numbers on the right (zeros modulo 2). Will work on module 3. $1153 \equiv 1 \pmod{3} = 1153^{60} \equiv 1 \pmod{3}$; $211 \equiv 1 \pmod{3} = 211^{60} \equiv 1 \pmod{3}$. On the right is $27027 \equiv 0 \pmod{3}$. Therefore, the entire right-hand side gives a remainder of 2. Again, we do not obtain a contradiction. If you have enough patience, make sure that modulo all numbers up to 16 inclusive, the written equality is true. (You'll notice that $27027 \cdot 100^x, x \geq 2$ is divided by each of these numbers, leaving a remainder of 2.)

*) Be careful with division comparisons. If $ac \equiv bc \pmod{k}$, then it is not necessarily true that $a \equiv b \pmod{k}$. For example, $27 \equiv 3 \pmod{6}$ but $9 \neq 1 \pmod{6}$. However, if $c$ is coprime with the modulus $k$, then it is possible to cancel by $c$. This is a consequence of such a gentle and not simply provable fact: if $c$ is coprime with $k$, then there is a number $x$ such that $cx \equiv 1 \pmod{k}$.

If you are consistent, then modulo 17 you will get the following equalities: $(-3)(-2)^x + 2 \equiv 0 \pmod{17}$. By going through the values ​​of $x$ in a row (the cycle here will be of length 8), you will never get the desired equality. A contradiction will be found.

The calculations done will immediately raise many questions:

(1) If the equality is false, can this be detected by any modulus?

(2) Is it possible to somehow indicate those modules for which contradictions are more likely to be obtained?

(3) Is the behavior of equality across different modules related?

If we are talking about some specific numerical equality (as was the case in our very first example), then, of course, there is always a number comparable in modulus to which we find a contradiction (for example, we can take a number greater than the common parts of the equality). Equalities in which there are variables are much more interesting (this was the case in the last two examples). For equations in integers, each of the three questions posed is interesting and not always fully explored.

**A little unproven**

The first equations in integers that pose serious difficulties in solving are quadratic equations*. Mathematicians have long been interested in questions of this kind: can a given number be represented as the sum of two squares? It turned out that the solvability of equations of the form $x^2 + y^2 = a$ and other more general ones, given by polynomials of the second degree, is evidence for checking the solvability of comparison (positive

*) The theory of linear integer equations is quite simple. At the same time, it contains a number of interesting tasks that are close to elementary, and deserves a separate stat.

⟦folio 18⟧

researching questions concerning objective numbers: pose these questions “modulo $p$”, and then draw general conclusions from the behavior of all $p$. This method of strangeness was called the “Minkowski-Hasse principle.” There have been and continue to be problems for which it gives the result: a problem has a solution in terms of numbers if and only if it is solvable in any modulus. It was all the more disappointing to find examples where this principle does not work. One of the first examples of this kind (but not the very first chronologically) was an example found by the Norwegian mathematician Selmer. The equation $3x^3+4y^3+5z^3=0$ turned out to be solvable in any modulus (and, of course, in real numbers), but unsolvable in terms of numbers (other than zero). This example served as the starting point for much research on Diophantine equations (that is, equations in numerical terms) over the past 15 years. It should only be said that during this time the number of unclear questions and hypotheses has greatly increased, and the true roots of what will actually happen have not become clear.

Distances between rational numbers

The most important modern development in number theory is the new understanding of "modulo calculations". For simplicity, let's move on from whole numbers to rational ones. (This transition is often made painlessly - for example, the solutions to the equation $x^n+y^n=z^n$ in terms of numbers are very closely related to the solutions to the equation $x^n+y^n=1$ in rational numbers.) It is clear that if we want to solve an equation in rational numbers, we must find out whether it can be solved in real numbers. This solvability is much easier to check: you can extract various roots, take logarithms, write inequalities, etc.

But let’s remember how we got real numbers from rational numbers? One of the points of view is this: we can consider sequences of rational numbers, the distance between neighboring terms of which decreases without limit. For example, 1; 1.4; 1.41; 1.4142; ... Such a sequence (which can be imagined as a sequence of changes with age-related accuracy) determines a real number. How does the deviation of neighboring members of the sequence from each other change? If the sequence is written like this: $a_1; a_2; a_3; ...$, then the distance between the terms is written as $|a_m-a_n|$. Thus, the basis for obtaining real numbers from rational numbers is the distance, defined as the absolute value of the difference. Let's denote the distance between two numbers as follows: $d(a, b) = |b-a|$. Try displaying the following distance properties*:

1) $d(a, b) \geq 0$, with $d(a, b) = 0 \Rightarrow a=b$;
2) $d(a, b) = d(b, a)$;
3) $d(a, c) \leq d(a, b) + d(b, c)$ (triangle inequality);
4) $d(a+c, b+c) = d(a, b)$;
5) $d(ab, 0) = d(a, 0) \cdot d(b, 0)$.

It turned out that, in addition to the general absolute value, rational numbers have many other distances that have the 1-5 property. Let us fix an arbitrary prime number $p$. Any rational number $a$ (except zero) can be represented as $a=p^v \cdot r$, where $v=v(a)$ is an integer, and the rational number $r=r(a)$ is such that when written in

*) The first three of these properties are the main ones that satisfy the general distance on the plane and in space; these are aximons that any “metric” must satisfy (see the article by N.B. Vasiliev “Metric spaces” in «Kvant» No. 10, 1970). The fourth and fifth properties of real distance with the operations of addition and multiplication of numbers. A metric that satisfies them is said to be a field metric (for example, $d(b, a) = |b-a|$ is the metric of the field of real numbers).

⟦folio 19⟧

in the form of an irreducible fraction, $p$ is not included in either the numerator or the denominator. (Note that $v(a)$ can be either zero or a negative integer. For example, if $p=3$, $a=\frac{73}{324}=3^{-4}\cdot\frac{73}{4}$, then $v(a)=-4$.) Now take an arbitrary positive number $\lambda<1$. Let's define the distance $d_p$ as follows: $d_p(a,b)=\lambda v(a-b)$, if $a\neq b$, and $d_p(a,a)=0$. It is easy to check (try it yourself) that all distance properties will be satisfied.

Since there is a new distance, we can try to obtain new numbers by constructing sequences of rational numbers $a_1, a_2, \ldots$, so that the distances between neighboring ones decrease. This means that $\lambda v(a_{n+1}-a_n)$ as $n$ increases should become smaller and smaller and tend to zero, and then $v(a_{n+1}-a_n)$ should increase.

As a result, we obtain new numbers, which are called $p$-adic $^*$. They are very similar to real ones. Just as easily as for real numbers, questions can be explored when it is possible to take the root, logarithm, and perform other operations on $p$-adic numbers. The problem of the solvability of an equation according to the power model of a given prime number will be replaced by the problem of its solvability in $p$-adic numbers.

The question arises whether we have found all the distances between rational numbers. It turns out that yes. There is Ostrovsky’s denominator theorem (you can find it in the book on number theory cited above), which shows that all distances are exhausted by a common absolute value and the $p$-adic distances introduced by us for each prime $p$.

We have, as it were, equalized the behavior of an equation based on the model of a single prime number and its power, on the one hand, and its behavior in ordinary real numbers

$^*)$ It is easy to prove that the choice of $\lambda$ does not affect the forgiveness and properties of $p$-adic numbers. One can, if one likes, assume everywhere that $\lambda=\frac{1}{2}$ or $\lambda=\frac{1}{p}$.

numbers - on the other. In both cases, numbers are compared by their distance from each other, but these distances are chosen differently. (Then we see how the second and third solutions to the problem with which our article began are similar.)

Understanding of this fact greatly enriched number theory, again brought into it powerful methods of function theory and geometry, previously developed for general real numbers, but successfully used for $p$-adic numbers, making this sum the ancient branch of modern mathematics one of the most flourishing.)

Exercises

1. Prove that none of the equations a) $x^2+y^2=1971$, b) $19x^3-17y^3=50$, b) $3x^2-y^2=5^z$, r) $x^3+y^3+7z=3$ has integer solutions.

2. Prove that from the numbers 1, 2, 3, 4, 5, 6, 7 it is impossible to form two different seven-digit numbers, one of which is divisible by the other. (All digits must be used in each digit.)

3. Prove that a number whose decimal notation consists of thirty ones, some zeros, and some nines is not a perfect square.

4. Find the 5-adic distance (that is, the distance $d_5$) between the numbers: a) 0 and $\frac{2}{5}$; b) $1\frac{31}{45}$ and $6\frac{2}{15}$; b) 6 and 631.

5. Prove that for 3-adic numbers the equality is true

$$1+3+9+27+\ldots=-\frac{1}{2}$$

(in other words, a sequence of distances

$$\alpha_n=d_3\left(1+3+\ldots+3^n,-\frac{1}{2}\right)$$

tends to zero).

What is the sum of $1+3^2+3^4+3^6+\ldots$?
