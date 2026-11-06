---
id: 1990-9-genkin-kurlyandchik-chislovyie-konstruktsii-25f8889d
issue: kvant_1990_9
year: 1990
number: "9"
title: Numeric constructions
authors:
  - Генкин С. А.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 60
page_last: 62
page_labels: 58-60
lang: en
source: kvant_digital
extraction: vision
content_sha256: cb09143ec8cc2ccea0126da2daf94fc69c3a40ddbe44fa853e76d09d9d63c762
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/19_genkin-kurlyandchik-chislovyie-konstruktsii-25f8889d.md
source_content_sha256: 72e853c98c990a3c2a07a9b95724da87fb5a5a5c5afc0624189f1052f32cdbcc
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 58⟧

---
running_head:
folio:
---

Numeric constructions

S. GENKIN,
L. KURLYANDCHIK

In this article, solve the same construction, the material for which is natural numbers. To the question of the existence of the required structure, two answers arise: yes or no.

Find the sum

Problem 1. Is it possible to divide the natural numbers from 1 to 21 into several groups, in each of which the largest number is equal to the sum of all other numbers?

Solution. Let us assume that such a partition is possible. It is clear that the sum of the numbers in each group is even (it is twice the largest number in the group). Therefore the sum of all numbers is even. However, 1+2+...+21=21·11 is an odd number. This means that such a partition is impossible.

Problem 2. Is it possible to choose five integers so that all their pairwise sums make up ten consecutive integers?

Solution. Let's assume that we managed to find five such numbers. Let s be the sum of all these numbers, and n be the smallest of their pairwise sums. Then ten pairwise sums are the numbers n, n+1, ..., n+9. Now let’s calculate the sum of all pairwise sums in two different ways. On the one hand, it is equal to n+(n+1)+...+(n+9)=5(2n+9). On the other hand, it is equal to 4s, since it contains each original number exactly four times. Therefore 4s=5(2n+9), which is impossible. This means that such five numbers cannot be selected.

Let us analyze the solution to these two problems. The main point of each of them is to calculate some amount in two different ways. But with the help of this technique one can only prove that a given set of numbers does not have the specified property. However, there are often problems in which it is necessary to find not only a necessary, but also a sufficient condition for the fulfillment of a specified property.

Problem 3. Of the numbers 1, 2, 3, ..., n+1, one was crossed out, and the rest were arranged in the sequence a₁, a₂, ..., aₙ in such a way that all n numbers |a₁−a₂|, |a₂−a₃|, ..., |aₙ−a₁| are different. For such n≥3, can this be done?

Solution. Firstly, the numbers a and |a| have the same parity. Therefore, the sum |a₁−a₂|+|a₂−a₃|+...+|aₙ−a₁| also has parity, like the number (a₁−a₂)+(a₂−a₃)+...+(aₙ−a₁)=0. So this sum is even. On the other hand, |a₁−a₂|, |a₂−a₃|, ..., |aₙ−a₁| - these are n different natural numbers, not exceeding n, i.e. these are the numbers 1, 2, 3, ..., n. Therefore, their sum is 1+2+...+n=n(n+1)/2, and this is an even number.

Posny n=4k or n=4k−1. So, the necessary conditions have been found. To prove it, it is enough to show that for such n it is required

⟦folio 59⟧

---
running_head:
folio:
---

possible locations exist. They are listed at figure.

Problem 4. What is the maximum number of triplets of numbers that do not have pairwise common elements that can be chosen from the set of natural numbers from 1 to $n$ in such a way that the sums of the numbers of each triple are different and do not exceed $n$?

Solution. Let $k$ triples of numbers be chosen. Let's add all the selected $3k$ numbers and denote the resulting sum by $s$. It is clear that $1+2+\dots+3k \leqslant n+(n-1)+\dots+(n-k+1)$. So, $\frac{3k(3k+1)}{2} \leqslant \frac{(2n-k+1)k}{2}$. From here we obtain the necessary condition $k \leqslant \frac{n-1}{5}$.

It remains to provide a set of $\left[ \frac{n-1}{5} \right]$ triples of numbers that satisfy the conditions of the problem. Let's denote the number $\left[ \frac{n-1}{5} \right]$ by $a$ and arrange the numbers from 1 to $3a$ as follows:

1 2 3 ...a-1 a
2a 2a-1 2a-2 ...a+2 a+1
2a+1 2a+2 2a+3 ...3a-1 3a

The numbers in the first column form the first three, those in the second column form the second three, and so on.

Binary number system

As you most likely know, every natural number $n$ represents-

Vischeknuyu number $3k$

is expressed in the form $n=a_k \cdot 2^k+a_{k-1} \cdot 2^{k-1}+\dots+a_1 \cdot 2+a_0$, where the numbers $a_i$ are equal to 0 or 1, and such a representation is unique. The double number system is based on this fact, in which every natural number is written using ones and zeros: $n_2=a_k a_{k-1} \dots a_0$. For example, $1_2=1$, $2_2=10$, $3_2=11$, $4_2=100$, $5_2=101$, $6_2=110$, $7_2=111$, and so on.

Before formulating the next problem, we introduce the following notation: $N_0$ is the set of natural numbers, complemented by zero.

Problem 5. Construct two infinite subsets $A$ and $B$ set $N_0$ such that each number from $N_0$ is uniquely represented as the sum $n=a+b$, where $a \in A$, $b \in B$.

Solution. Here it is convenient to use double notation of natural numbers. Consider two sets $A$ and $B$, devices like this. The set $A$ consists of zero and all natural numbers, in double notation of which the unit is in odd (counting from the right) digits ($A=\{0,1,4,5,16,17,20,21,\dots\}$). The set $B$ consists of zero and all natural numbers, in double notation of which the unit is in the even (counting from the right) digits ($B=\{0,2,8,10,32,34,40,42,\dots\}$). It is obvious that any non-negative integer $n$ is uniquely represented as the sum $n=a+b$, where $a \in A$, $b \in B$.

⟦folio 60⟧

---
running_head:
folio:
---

This design is also key in solving the following two problems. To form them, we give a definition: two subsets of the set $N_0$ are called congruent if one can be obtained from the other with a difference by an integer.

Problem 6. Prove that the set $N_0$ can be divided into an infinite number of disjoint infinite congruent subsets.

Solution. Let $A$ and $B$ be the sets constructed by solving Problem 5. For each number $b \in B$ we denote by $A_b$ the result of the subdivision of the set $A$ by this number $b$, i.e. $A_b$ is the set of numbers of the form $a+b$, where $a \in A$. Let us show that the collection of the set $A_b$ forms the required partition of the set $N_0$ into congruent sets. Since each number $n$ from the set $N_0$ is representable as a sum $n = a+b$ ($a \in A, b \in B$), then the sets $A_b$ cover the entire set $N_0$, and from the fact that this is a unique representation, it follows that these sets are pairwise disjoint.

The next problem is problem M685 from the Quantum Problem Book. In the first issue of Quantum in 1982, an incorrect solution to this problem was published. We will recount this solution, and then show what the error is and how to fix it.

Problem 7. Is it possible to split the set of natural numbers into an infinite number of infinite congruent sets?

Solution. In the solution given in “Kvanita”, two sets $A$ and $B$ are written out. The set $A = \{1, 4, 5, 16, 17, 20, \dots\}$ is the set of natural numbers in whose double notation the unit is in odd places. The set $B = \{0, 2, 8, 10, 32, 34, \dots\}$ is a set consisting of zero and numbers in whose double notation the unit is in even places. The solution states that every natural number $n$ is represented as $n=a+b$, where $a \in A, b \in B$. Meanwhile, it is immediately clear that none of the numbers included in the set $B$ can be represented in this form!

Let's fix this decision. To do this, consider the sets $A$ and $B$, constructed in solving Problem 5. In solving Problem 6, we have already proven that the corresponding sets $A_b$ form the required partition of the set $N_0$. Let us now consider together the sets $A$ set $A_1$ - shift the set $A$ by one: $A_1 = \{1, 2, 5, 6, 17, 18, 21, 22, \dots\}$. It is clear that for any number $b \in B$ the set $(A_1)_b$ is the set $A_b$ shifted by one. Therefore, the sets $(A_1)_b$ form the required partition of the set of natural numbers.

Design by induction

In this section, we will look at four examples of propagation algorithms from simpler to more complex structures.

Problem 8. Given $n$ digits whose masses are equal to the corresponding 1, 2, ..., $n$ grams. For which $n$ can these numbers be decomposed into three piles of equal masses?

Solution. It is clear that such a construction (decomposition into three heaps) does not exist for all $n$. To do this, it is necessary that the total mass of all digits $1+2+\dots+n = \frac{n(n+1)}{2}$ is divisible by three. Therefore, either $n$ or $n+1$ must be divisible by three. Let us now prove that for all such $n \geq 5$ the required construction exists. First, we specify an algorithm for propagating the construction from a set of $k$ digits to a set of $k+6$ digits. To do this, let’s decompose six numbers with masses $k+1, k+2, k+3, k+4, k+5, k+6$ into three piles of equal masses: $(k+1, k+6); (k+2, k+5); (k+3, k+4)$. It remains to show how you can decompose five, eight and nine digits (how to decompose six digits is clear from the previous one). This can be seen from the following table:

$$
\begin{array}{c c c}
n = 5 & (1, 4); (2, 3); 5 \\
n = 8 & (1, 2, 3, 6); (4, 8); (5, 7) \\
n = 9 & (1, 2, 3, 4, 5); (6, 9); (7, 8)
\end{array}
$$
