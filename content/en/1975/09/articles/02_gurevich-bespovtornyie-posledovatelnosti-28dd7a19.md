---
id: 1975-9-gurevich-bespovtornyie-posledovatelnosti-28dd7a19
issue: kvant_1975_9
year: 1975
number: "9"
title: Repeatless sequences
authors:
  - Гуревич Г. А.
rubric: osnovnye-stati
page_first: 9
page_last: 13
page_labels: 7-11
tag: 5QQU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 345f916082b7ab1914b26729fc65595a7515d77d43fe66d9435d27eef33ba977
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/02_gurevich-bespovtornyie-posledovatelnosti-28dd7a19.md
source_content_sha256: c20b40cfe6d2c2e1647a77273c630894a3a97f856a7c97d8866bffdb3573ee28
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 7⟧

Repeatless sequences

G. A. Gurevich

Arshon sequences

Let's call a sequence of digits a *repeated sequence* if it contains at least one pair of standing identical groups of digits. For example, the sequences 1, 2, 3, 4, 2, 3, 4, 2, 1 and 1, 2, 2, 7, 6, 2, 7, 6, 8 are repeated, but the sequences 4, 2, 1, 2, 3, 4, 2, 3 and 3, 2, 3, 1, 2, 7 are not repeated. We will call non-repeated sequences *non-repeated*. Let B(n) denote the set of sequences of length n, and |B(n)| - their number.

It is intuitively clear: the longer the sequence, the more likely it is that it contains two identical groups of numbers standing next to each other. And in fact, if you scientifically write out a sufficiently long sequence, then this sequence will probably be repeated.

Let us give this statement a precise meaning.

Problem 1. Prove that for any number ε > 0 it is possible to specify n such that among all sequences of length n the proportion of repeat-free sequences will be less than ε, that is, $$\frac{|\text{Б}(n)|}{10^n} < \varepsilon.$$

It is easy to prove that all sequences of length greater than three, composed of two digits 1 and 2, are repeated.

However, from three different digits it is already possible to create a angular, non-repetitive sequence.

This fact was proved in 1937 by the Soviet mathematician S. E. Arshon, who proposed an inductive method for constructing repetition-free sequences, which is as follows.

Let us denote by $K_1$ the repetition-free sequence 1, 2, 3. Let us assume that the repetition-free sequence $K_n$ has already been constructed. The sequence $K_{n+1}$ is obtained from it like this.

If the number $n+1$ is even and the $n+1$th place in the sequence $K_n$ is 1, then the sequence $K_n$ is assigned a triple of digits 3, 2, 1; if it costs 2, then the triple is 1, 3, 2; if it costs 3, then the triple is 2, 1, 3.

If the number $n+1$ is odd and the $n+1$th place in the sequence $K_n$ is 1, then the triple 1, 2, 3 will be added to the sequence $K_n$; if it costs 2, then the triple is 2, 3, 1; if it costs 3, then the triple is 3, 1, 2.

In part,

$$K_2 = 1, 2, 3, 1, 3, 2$$
($n = 2$ is an even number, and the second place in $K_1$ is 2),

$$K_3 = 1, 2, 3, 1, 3, 2, 3, 1, 2, 3, 2, 1$$
($n = 3$ is an even number, and the third place in $K_2$ is 3),

$$K_4 = 1, 2, 3, 1, 3, 2, 3, 1, 2, 3, 2, 1$$
($n = 4$ is an even number, and the fourth place in $K_3$ is 1), etc.

The proof of the non-repetition of sequences obtained using Arshon’s method is quite formidable.

⟦folio 8⟧

is cumbersome, and we will not present it here *).

Let us now try to estimate the number $|B(n)|$ of repeat-free sequences of length $n$ (of ten digits). If we can show that for any positive integer $n$ this number is greater than zero, then we will have yet another—no longer constructive—proof of the existence of arbitrarily long repetition-free sequences. In fact, we will now derive a significantly stronger inequality $|B(n)| > 8^n$, (1)

In this way we will not only prove the existence of arbitrarily long repetition-free sequences, but also give a sufficiently good lower bound for their number.

Problem M310

Now let's remember problem M310 from the “Problem Book «Kvant» - see «Kvant» No. 2 for 1975.

Prove that among $n$-digit numbers there are more than $8^n$ maxims; in the decimal notation of composite numbers, no group of digits (in particular, no digit) appears twice in a row.

It is clear that the solution to problem M310 consists in proving inequality (1). We will first prove some auxiliary inequality, which will be useful to us later.

Auxiliary inequality. Let us assume that all repetition-free sequences of length $n$ have been written down—there are $|B(n)|$ pieces in total, and we want to write down all repetition-free sequences of length $n+1$.

Let us take an arbitrary sequence $a_1, a_2, \dots, a_n$ from the set $B(n)$. Let's write the new ten as follows - length $n+1$:

$$a_1, a_2, \dots, a_n, 0, a_1, a_2, \dots, a_n, 1, a_1, a_2, \dots, a_n, 9.$$

We do this with all sequences from the set $B(n)$. We obtain a certain set of sequences; let's denote it by $B^*(n+1)$. Among the sequences of the set $B^*(n+1)$, we choose those that have two identical digits at the end. We denote the set of such sequences by $B_1(n+1)$. Similarly, by $B_2(n+1)$ we denote the set of such sequences from $B^*(n+1)$ that end with the same subsequence of length $i$ twice in a row. Since all sequences of $B^*(n+1)$ have length $n+1$, the maximum $i=n_1$ for which the set $B_i(n+1)$ is not empty is $\left[\frac{n+1}{2}\right]$.

All sequences belonging to the sets $B_1(n+1), B_2(n+1), \dots, B_{n_1}(n+1)$ are repeated. Prove yourself that these mismatches sequences are exhausted by the repeat sequences of the set $B^*(n+1)$ and that the set $B^*(n+1)$ contains all repeat-free sequences of length $n+1$.

Therefore, if from the set $B^*(n+1)$ we delete all sequences belonging to the set $B_i(n+1), i=1, 2, \dots, n_1$, then we get the set $B(n+1)$. Hence,

$$|B(n+1)| \geq |B^*(n+1)| - |B_1(n+1)| - |B_2(n+1)| - \dots - |B_{n_1}(n+1)|.$$ (2)

⟦folio 9⟧

By constructing the set $B^* (n+1)$ we have: $|B^* (n+1)| = 10 \cdot |B(n)|$, and we only need to estimate the number of elements of each set $B_i (n+1)$. It turns out $|B_i (n+1)| \leq |B (n+1-i)|$. (3)

From inequalities (2) and (3) follows an important inequality, which we call auxiliary: $|B (n+1)| > 10 \cdot |B(n)| - (|B(n)| + |B(n-1)| + \dots + |B(1)|)$. (4)

So, we need to prove inequality (3).

Minor absence

Let $A$ and $B$ be two finite sets, and we want to know which one has more elements. The first thing that comes to mind is to count the number of elements of the set $A$ and the set $B$, and then compare the resulting numbers. But if a set contains a lot of elements or is somehow “tricky” in design, then calculating its number of elements can be quite difficult. And it is no longer clear what to do if the sets $A$ and $B$ are infinite. It turns out that there is a universal way that allows you to compare even infinite sets. Let's describe this method with an example.

Let $A$ be the set of schoolchildren brought to the theater, and $B$ be the set of places in the theater. Let's seat the schoolchildren in their places. If there are still free places, then $|B| > |A|$. If all the places are occupied and some students are left without a place, then $|A| > |B|$. And finally, if it turns out that all the places are occupied and all the students have been told, then $|A| = |B|$.

What is the method described above? We assigned the elements of the set $A$ to the elements of the set $B$. If the elements of the set $A$ were the first to be exhausted, then $|B| \geqslant |A|$, and if the elements of the set $B$ were the first to be exhausted, then $|A| \geqslant |B|$. It is important that different elements from $A$ were matched with different elements from $B$ (we did not allow one student to study places at once) and, conversely, different elements from $B$ corresponded to different elements from $A$ (we did not allow each student to occupy one place at once). This correspondence is called cd-valued.

Proof of inequality (3)

Let us now try to establish a one-to-one correspondence between the sets $B_i (n+1)$ and part of the set $B (n+1-i)$ ($i=1,2,\dots,n_1$). Recall that sequences from the set $B_i (n+1)$ have the form $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i, b_1, b_2, \dots, b_{i-1}$ - wireless. This means that the sequence $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i$ is also wireless. Let us associate sequence (5) from the set $B_i (n+1)$ with the sequence $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i$ from the set $B (n+1-i)$:

$a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i, b_1, b_2, \dots, b_i$

Obviously, this correspondence is one-to-one, and for each sequence from $B_i (n+1)$ there is a corresponding sequence from $B (n+1-i)$. This means that $|B_i (n+1)| \leqslant |B (n+1-i)|$ and inequality (3), and hence (4), are proven.

Solution to problem M310

Let us now prove (by induction on $n$) another inequality:

$|B (n+1)| > 8 \cdot |B (n)|$; (6)

⟦folio 10⟧

it is clear that we need inequality (1); it follows from it, since
$$|\beta(n)| > 8 \cdot |\beta(n-1)| > 8^2 \cdot |\beta(n-2)| > \dots > 8^{n-1} \cdot |\beta(1)|,$$
and $|\beta(1)| = 10$.

Induction base. $n = 1$.
$$|\beta(2)| > 8 \cdot |\beta(1)|,$$
since $|\beta(1)| = 10$ and $|\beta(2)| = 90$.

Induction step. Suppose it has already been proven that
$$|\beta(n)| > 8 \cdot |\beta(n-1)|,$$
$$|\beta(n-1)| > 8 \cdot |\beta(n-2)|,$$
$$|\beta(2)| > 8 \cdot |\beta(1)|;$$

we need to prove inequality (6).
From inequalities (7) it follows that
$$|\beta(n)| > 8^i \cdot |\beta(n-i)|,$$
or
$$|\beta(n-i)| < \frac{|\beta(n)|}{8^i},$$
$$i = 1, 2, \dots, n-1.$$

Let us substitute the found estimates (7') for $|\beta(n-i)|$, $i = 1, 2, \dots, (n-1)$ into inequality (4); we get
$$\beta(n+1)| > 10 \cdot |\beta(n)| - |\beta(n)| \cdot \left(1 + \frac{1}{8} + \dots + \frac{1}{8^{n-1}}\right).$$

Because
$$1 + \frac{1}{8} + \dots + \frac{1}{8^{n-1}} < 2,$$
then $|\beta(n+1)| > 8 \cdot |\beta(n)|$.

Let us now formulate several problems.

2. Construct a wireless sequence such that when you add any number to the end of it, you will always get a repeat sequence.

3. Using S. E. Arshon’s sequence, prove the existence of angularly long sequences composed of the numbers 1 and 2, which do not have three identical adjacent groups of numbers.

4. Prove that for any natural number $n$ wireless sequences of length $n$ composed of four digits 1, 2, 3, 4 are greater than $2^n$.

Problem 4 implies the existence of an angularly long wireless sequence of four different digits. S. E. Arshon showed that in fact, the existence of a wireless sequence of any length is sufficient even for three digits.

Endless wireless sequences

So, we have proven the existence of angularly long wireless sequences. In this section we will prove the existence of an endless wireless sequence (note that the first does not yet imply the second).

Task 5. Prove that if there is at least one endless wireless sequence, then there are infinitely many such sequences.

Let $B$ denote the set of all finite wireless sequences. Since the set $B$ is infinite, and there is a finite number of different digits (10 in total), then there is at least one digit with which the infinite set of sequence of $B$ begins. Let's denote this number by $a_1$. Let's remove from $B$ those sequences that do not begin with the number $a_1$. We obtain an infinite set $B^{(1)}$. Similarly, there is a digit $a_2$ that is in second place in an infinite number of sequences of $B^{(1)}$. Let us remove from $B^{(1)}$ those sequences whose second digit differs from $a_2$. We get an infinite set $B^{(2)}$ and so on.

Let us now consider the infinite sequence $a_1, a_2, \dots$; Let's prove that it is wireless.

To do this, it is enough for us to show that for any natural number $n$ the wireless finite sequence is $a_1, a_2, \dots, a_n$. But by construction, all sequences of the set $B^{(n)}$ begin with the sequence $a_1, a_2, \dots, a_n$, and the set $B^{(n)}$ is a subset of the set

⟦folio 11⟧

va B, and therefore all sequences from B^{(n)} are repeatless. Any beginning of a repeat-free sequence is itself a repeat-free sequence.

Problem 6. Prove that among any eleventh infinite decimal fractions, you can choose two fractions that have the same digits in an infinite number of digits.

Generalization

Let us denote by the letter P the property “to be a repetition-free sequence.” Then the statement just proved has the following structure:

Premise Consequence

There is an arbitrarily long sequence with property P

There is an infinite sequence with property P

Will this statement remain true if we assume that P is an arbitrary property of number sequences? In general, no. Let's give an example: consider the property “to be a finite sequence.” Obviously, there are arbitrarily long finite sequences, but there is no such thing as an infinite finite sequence.

Let us now note that, in proving the existence of an infinite repetition-free sequence, we relied only on the following two facts, which directly follow from the definition of a repetition-free sequence.

1°. Every beginning of a sequence that has property P also has this property.

2°. an infinite sequence whose beginning is arbitrarily long has property P also has this property.

About the limit. An arbitrary property of number sequences that satisfies condition 1°

and 2°, we call it a hereditary property.

For example, the properties “do not contain the number 3”, “consist only of the numbers 1, 2, 3”, “begins with the number 7” are hereditary properties, but the properties “contain an endless number of 4”, “ends with the number 7” are not hereditary properties.

Theorem. Let P be an arbitrary hereditary property. Then, if there are arbitrarily long sequences that have property P, then there also exists an infinite sequence that has this property.

We will not dwell on the proof of this theorem, since it completely repeats the proof given in the previous paragraph.

Application

Let's consider number sequences made up of three digits: 1, 2, 3. Let's make some sequences (of length two or more) forbidden. It is known that all forbidden sequences have different lengths.

Let us make sequences that do not contain forbidden sequences correct.

Let us turn again to “Problem Book «Kvant» - to Problem M300 (see «Kvant» No. 12 for 1974).

From statement problem M300 it follows that there are arbitrarily long regular sequences. Now let us note that the property “to be a regular sequence” is always an inherited property (provable!) This means that the statement about the existence of arbitrarily long regular sequences can be replaced by a stronger one - about the existence of an infinite regular sequence, and the statement problem M300 is a statement about the existence of an infinite word without forbidden letter combinations.
