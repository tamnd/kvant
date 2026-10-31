---
id: 1970-7-varpahovskiy-kolmogorov-o-reshenii-desyatoy-problemyi-gilberta-dec16bb0
issue: kvant_1970_7
year: 1970
number: "7"
title: On the solution to Hilbert's tenth problem
authors:
  - Варпаховский Ф. Л.
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 41
page_last: 46
page_labels: 39, 40, 41, 42, 44
tag: L6M4
lang: en
source: kvant_digital
extraction: vision
content_sha256: dd4654a6a361e91eb84eb9dafca25e837802951d13cbb48de116ff2c3fabf8e6
prompt_sha256: draft-1
translated_from: content/ru/1970/07/articles/07_varpahovskiy-kolmogorov-o-reshenii-desyatoy-problemyi-gilberta-dec16bb0.md
source_content_sha256: c20a81f9f1d013b3f5638da69a142cf6b8c1a163980e2129cefbb63cb558de9c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

The third issue of Kwan reported on the outstanding success of the young Leningrad mathematician Yu. V. Matiyasevich, who recently managed to take the final step in solving one of the meanings of the “Hilbert problems” posed back in 1900. The work of Yu. V. Matiyasevich was published in the Reports of the USSR Academy of Sciences *). And what happens rarely is that a thoughtful student can independently understand the main content of this work, which is important for modern mathematical science. The fact is that the original part of Yu. V. Matiyasevich’s work is devoted to the proof of the theorem, the formulation of which is quite elementary and is given in the article we publish. The methods of proof are also elementary. It is more difficult to explain the rules in a language understandable to a schoolchild, why this theorem about Fibonacci numbers is of such significant interest for server-side mathematical science. In its formulation and methods of proof, it rather resembles a clever optimization problem.

1. Fibonacci number theorem

Throughout what follows we will deal only with integers. Consider the following property of a pair of numbers (a, b):

"b is divisible by a."

This property of a pair of numbers can be expressed as follows:

“there is a number x such that ax—b=0.”

We expressed our property of the pair of numbers (a, b) through the existence of a solution to the equation

ax—b=0

(let us recall once again that we are dealing only with integer numbers and, therefore, only with integer solutions). The equation for this is

P(a, b, x) = 0,

where P is a polynomial in three variables a, b, x.

Let us now introduce a general definition; a property of a finite sequence of numbers (a₁, a₂, ..., aₘ) is called Diophantine if there exists such a polynomial in m + n variables

P(a₁, a₂, ..., aₘ), that the sequence (a₁, a₂, ..., aₘ) has our property in that

*) Here is the title and exact “address” of the article: Yu. V. Matiyasevich. Diophantine property of the listed sets, DAN SSSR, 1970, volume 191, no. 2.

⟦folio 40⟧

only if there are numbers $x_1, x_2, \dots, x_n$ for which $P(a_1, a_2, \dots, a_m, x_1, x_2, \dots, x_n) = 0$.

Matiyasvich's main achievement is precisely the proof of the Diophantine property of a certain special property of pairs of numbers $(a, b)$.

Many of you are familiar with Fibonacci numbers.

$$\psi_0 = 0, \quad \psi_1 = 1,$$
$$\psi_2 = \psi_0 + \psi_1 = 1,$$
$$\psi_3 = \psi_1 + \psi_2 = 2,$$
$$\psi_4 = \psi_2 + \psi_3 = 3,$$
$$\psi_5 = \psi_3 + \psi_4 = 5,$$

an infinite sequence of which is determined by the recurrent formula

$$\psi_{n+1} = \psi_{n-1} + \psi_n.$$

The property of the pair of numbers $(a, b)$ that Matiyasviči deals with is:

"$b$ is the Fibonacci number

with number $2a$", i.e. $b = \psi_{2a}$.

It is clear that pairs have this property

$(0,0), (1,1), (2,3), (3,8)$

etc. The statement that the Matiyasvich property is Diophantine means that there is a polynomial

$$Q(a, b, x_1, x_2, \dots, x_n)$$

such that $b$ will be a Fibonacci number with number $2a$ if and only if there exist numbers $x_1, x_2, \dots, x_n$ such that

$$Q(a, b, x_1, x_2, \dots, x_n) = 0.$$

The polynomial $Q$ with integer coefficients could, in principle, be written out explicitly. Matiyasvich does not do this and does not even indicate what the number $n$ of additional variables is.

As for the proof of the formulated theorem, then, as already said, it is quite elementary. Matiyasvich refers to one lemma proven in N. N. Vorobyov’s book “Fibonacci Numbers,” intended for schoolchildren, and one result proven in a more scientific book by A. I. Maltsev, but also elementary. In Matiyasvich's work itself, nineteen lemmas are given without proof, but the proof of each of them separately is no more difficult than typical problems for schoolchildren. The difficulty was only to find that particular combination of elementary proposals that leads to the final goal.

2. Why is all this so important?

If the polynomial $Q$ Matiyasvich was really needed by a mathematician to carry out any calculations, then it is believed that Matiyasvich would not be too lazy to write it down explicitly. But in reality, the very appeal to the Fibonacci numbers is eurysimable for sequentially writing out all pairs possessing this property

$(0,0), (1,1), (2,3), (3,8), (4,21), (5,55), \dots$

Since the polynomial of these pairs is infinite, the process of writing them out will never end. But we have a rule according to which our pairs can be written out one after another with magnification in that

1) Only pairs with the Matiyasvich property will be written out,
2) any pair possessing the Matiyasvich property will sooner or later be discharged.

A property (in more scientific language, a “predicate”) of a finite sequence of numbers $(a_1, a_2, \dots, a_m)$ is called an enumeration if there is a rule that allows, through the mechanical application of this rule, to obtain sequences one after another that consistently have a given property, and moreover, in such a way that any sequence

⟦folio 41⟧

A property with this property will sooner or later be obtained.

From a modern point of view, the most significant consequence of Matiyasvich's theorem on Fibonacci numbers is

Theorem 1. Any enumeration property of a finite sequence of numbers is Diophantine.

Before 1961, this theorem would have seemed extremely surprising. But some weaker results by Davis, Putnam and Robinson, proven in 1961, made such a hypothesis no longer so incredible. Considerable effort was spent on proving her mathematics. Matiyasvich took advantage of some, so to speak, “reductions” of the problem to more special problems. But the idea of ​​reducing everything to the properties of Fibonacci numbers was also unexpected in the situation that had developed by 1970.

Thus, Matiyasvich’s major success required combining an understanding of the big problems of modern mathematics and erudition in his field with the art of finding unexpected, completely elementary ways to solve special problems.

3. In what sense did Matiyasvich solve Hilbert's tenth problem?

In Hilbert's tenth problem*) he solved equations of the form

$$P(x_1, x_2, \ldots, x_n) = 0,$$

where $P$ is a polynomial with integer coefficients. The degree of such an equation is called the degree of the polynomial $P$. When the question is asked about finding their solution in integers, these equations are called “Diophantine”. For example, the equation

$$x^2 + y^2 = 1$$

has even solutions in integers

$$x = \pm 1, \quad y = \pm 1,$$

*) More details about Hilbert’s problems can be read in the book D. Hilbert, “Mathematical Problems”, “Science”, 1969.

and the equation

$$x^2 + y^2 = 3$$

has no solutions in integers.

Now let's give the floor to Hilbert himself:

“Let an arbitrary diophantine equation with an arbitrary number of unknowns be given...; We need to indicate a general method, the following procedure could be used to find out in a finite number of steps whether we have a given equation of solution in integers ... or not.”

Hilbert was apparently convinced that the general method he was looking for existed, and the only question was to find it. A lot of effort was spent to find this method, but no encouraging results were obtained.

The problem of integer solutions to an arbitrary equation can easily be reduced to the problem of natural (integer non-negative) solutions. Further, it is not at all difficult to show that it is sufficient to restrict ourselves to Diophantine equations of degree no higher than four. For diophantine equations of degree no higher than the second, the sought general method was found, but equations of the third degree were no longer fed into any numbers.

In connection with the failures in this direction, the suspicion arose that the general method that Hilbert’s formulation was supposed to find simply did not exist! A similar situation has developed in a number of other problems of a similar nature. However, it is one thing to find the required general method - here it was enough just to present this method and directly verify that it satisfies the conditions put forward by Hilbert.

But in order to prove the non-existence of a certain method for solving a series of problems, it was necessary to give an exact definition of what this general method is, how and by what means it can be implemented.

At the beginning of the thirties, the corresponding definitions were expanded

⟦folio 42⟧

nerds in the works of the American scientist Church and the English scientist Tyorig. These definitions laid the foundation for the theory of algorithms. Looking back on the path traveled, mathematicians should be grateful to Hilbert's ten problems for the fact that it served as one of the incentives for the creation of this theory.

Within the framework of the theory of algorithms, a precise definition of the concept “enumerable property” was obtained, which we used in the previous paragraph.

It turned out that from the Diophantine property of any enumerated property of a finite number sequence it follows

Theorem 2. It is impossible to have a general method (algorithm) that allows us to determine for any given Diophantine control whether it has solutions in integers or not.

Matiyasevich from his theorem on the Diophantine property of a special property of a pair of numbers (a, b)

$$b = \psi_{2a}$$

derived a proof of Theorem 1, from which, as was already known, Theorem 2 follows, i.e., a negative solution to Hilbert’s ten problems.

For a final understanding of everything that has been said, you only need a clear knowledge of what an “algorithm” is (a general method for solving an infinite series of problems) and what an “enumerable property” (an enumerative predicate) is. But this is already a much more difficult topic.

4. Definitions and facts of the theory of algorithms

1. Among the functions defined on the set N of natural numbers and taking natural values, the class of primitive recursive functions is distinguished as follows.

Consider the function S(n) n+1 and q(n)=n-p, where p²≤n<(p+1)². From the functions f(n) and q(n) it is cut to form the function h₁(n)=f(n)+q(n) (addition operation), $h_2(n)=f(q(n))$ (substitution operation), and from one function f(n) - a function defined by the equalities h₃(0)=0, h₃(n+1)=f(h₃(n)) (ineration operation). The class of primitive recursive functions consists of the functions S, q and all those functions that can be obtained from them by a finite number of additions, substitutions and iterations.

For example Let us show that the function φ(n)=2n and φ(n)=2n+1 are primitively recursive. Let us first apply the ineration operation to the function S(n)=n+1. Then h(0)=0, h(n+1)=S(h(n))=h(n)+1. Therefore, h(n)=n and φ(n) is obtained by applying the addition operation to two functions, each of which is equal to h(n): φ(n)=h(n)+h(n)=n+n=2n. Finally, the function φ(n) is obtained by a substitution operation applied to the functions S(n)=n+1 and φ(n)=2n: φ(n)=S(φ(n))=S(2n)=2n+1.

2. A set M of natural numbers is called enumerative if it coincides with the set of values ​​of some primitive recursive function.

For example, the set of even numbers is enumerable, since it is the set of values ​​of the primitive recursive function φ(n)=2n. The set of odd numbers coincides with the set of values ​​of the primitive recursive function φ(n)=2n+1, and is also enumerable.

3. A set M is called decidable if it is enumerable together with its complement N - M (where N is the set of all natural numbers).

In particular, a solvable set of numbers, since it is enumerable along with its complement (the set of odd numbers).

4. There are enumerable but undecidable sets.

It is possible to give a specific example of such a set, but the corresponding construction is technically too complex to be carried out within the framework of this comment.

Now let this be a set of M natural numbers. One may ask whether there is a general method that, given every positive integer n, determines in a finite number of steps whether that n belongs to the set M or not. The main position of the theory of algorithms (Church's theory) states that any method (algorithm) exists, model and model, when the set M is solvable.

⟦folio 44⟧

It is certain that the inequality $v > u^n$ will be true. This circumstance can be constructed in the table given on page 43. (It highlights those cells in which the numbers $u^k$ are less than the corresponding numbers $v$).

After the indicated property was verified, Matiyasevich “corrected” the Fibonacci sequence, removing odd terms from it. Namely, he considered the sequence given by the corresponding ones: $\varphi_0 = 0, \varphi_1 = 1, \varphi_{n+1} = 3\varphi_n - \varphi_{n-1}$. The result is exactly a sequence of four members of the first sequence: $\varphi_0 = 0, \varphi_1 = 1, \varphi_2 = 3, \varphi_3 = 8, \varphi_4 = 21, \varphi_5 = 55, \varphi_6 = 144, \varphi_7 = 377$, etc. By taking $u$ as the number of the sequence member, and $v$ as the sequence member with number $u$, i.e. $\varphi_u$, we find that the required property is again satisfied for $u$ and $v$. Terer only had to construct the equation $P(u, v, x_1, \dots, x_k) = 0$, which would have a natural solution if and only if $v = \varphi_u$ - the rest was based on the result of Julia Robinson! To do this, it was enough to construct a system of diffant equations $P_1 = 0, \dots, P_n = 0$ in variables $u, v, x_1, \dots, x_k$, which has a solution if and only if $v = \varphi_u$ - this system has exactly the same solutions as the only equation $P_1^2 + \dots + P_n^2 = 0$.

This is the form in which Matiyasevich obtained the required system of equations:

1) $u + (a - 1) = v$,
2) $v + b = l$,
3) $l^2 - lk - k^2 = 1$,
4) $g^2 - gh - h^2 = 1$,
5) $l^2c = g$,
6) $ld = r - 2$,
7) $(2h + g)e = r - 3$,
8) $x^2 - rxy + y^2 = 1$,
9) $lp = x - u$,
10) $(2h + g)q = x - v$.

To prove that the existence of a natural solution to this system is equivalent to the corresponding $v = \varphi_u$, Matiyasevich used the following characteristic property of the sequence $\{\varphi_k\}$:

a pair of conditions $x < y$ and $x^2 - 3xy + y^2 = 1$ is equivalent to the existence of a $k$ such that $x = \varphi_k$ and $y = \varphi_{k+1}$.

We recommend that the interested reader try his hand at proving this equivalence.

Let us point out in conclusion that the found solution to the ten problems has a number of interesting consequences, of which, perhaps, the most effective is the following: you can specify a specific linear polynomial, the set of positive values ​​of which coincides with the set of all prime numbers!

Mathematical science has recorded a server and honorable achievement.

Task 1

1. Show that for any $k$ the numbers $\varphi_k$ and $\varphi_{k+1}$ are coprime.
2. Prove compliance: $\varphi_{k+1} = \varphi_k + 1$.
3. Show that the diffant equation $P(y, x_1, \dots, x_k) = 0$ has a solution for positive numbers if and only if the equation has such a solution

$$Z = (1 - (P(z, x_1, \dots, x_k))^2) - y.$$

Due to the fault of the printing house, in «Kvant» No. 5 (p. 64, task 1226), the formula for dividing numbers was typed incorrectly. It should look like this:

$$\frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2}$$
