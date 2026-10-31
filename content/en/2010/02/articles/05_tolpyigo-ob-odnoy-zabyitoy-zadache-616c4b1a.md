---
id: 2010-2-tolpyigo-ob-odnoy-zabyitoy-zadache-616c4b1a
issue: kvant_2010_2
year: 2010
number: "2"
title: About one forgotten task
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 48
page_labels: 45-46
tag: XE3R
lang: en
source: kvant_digital
extraction: native
content_sha256: e8ede7261f1d5fe0d3a1f4091f840f0fc33daca1e0889d8ed9f437555cb27ad2
prompt_sha256: draft-1
translated_from: content/ru/2010/02/articles/05_tolpyigo-ob-odnoy-zabyitoy-zadache-616c4b1a.md
source_content_sha256: f104472697b4b578c0da89b82e79f356bcbc149b452ba4c1aaa62ec303fda9ba
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

MATHEMATICAL CIRCLE

About one forgotten task

A. TOLPYGO

And it also happens sometimes: you are struggling with some problem, but it doesn’t work out, and then you come up with some new, very cunning way to solve it. And just imagine, it doesn’t work out for you again! This seemingly completely useless work often results in unexpected benefits...

S. Bobrov. Magic bicorn

To begin with, let us formulate two problems. Problem A. Prove that from any n integers you can select several whose sum is divisible by n. Problem B. Prove that from any (2n – 1) integers you can choose n numbers whose sum is divisible by n. Problem A is widely known and can be solved using the Dirichlet principle (“if (n + 1) rabbits are to be placed in n cells, then at least one cell will contain at least two rabbits”). Namely, we need to consider the numbers $S_{0} = 0, S_{1} = a_{1}, S_{2} = a_{1} + a_{2}, S_{3} = a_{1} + a_{2} + a_{3}$, …, $S_{n} = a_{1} +^{…} + a_{n}$. The role of the “cells” in which these “rabbits” need to be seated is played by the remainders from dividing the number by n. According to the Dirichlet principle, some two of the “rabbits” end up in the same “cage”, i.e. give the same remainder when divided by n. Therefore, their difference is divided by n, and this is what is required. On the contrary, problem B (once it was published in the journal «Kvant» for 1970 under number M45) is now undeservedly forgotten. Meanwhile, there is not only a wonderful mathematical fact, but also a number of beautiful ideas around its solution. True, as will be seen later, some of them lead to proof, others do not. However, both are useful: if some of them are not sufficient to solve this problem, they will come in handy another time. It is problem B that will be discussed below. But first, let’s consider a couple more problems of a similar type.

1. Two more tasks

Problem C. Given N – 1 natural numbers $a_{1},^{…}, a_{N} -_{1}$. All of them are greater than zero and less than N. It is known that if any k, 0 < k < N, and any k numbers from this set are chosen, then their sum is not divisible by N. Prove that all numbers in the set are equal to each other. Problem D. Given 100 numbers, each of which is greater than 0 and less than 94. Prove that from them it is possible to select several numbers whose sum when divided by 101 gives a remainder of 95. Solution to Problem C. Assume that $a_{1} \ne a_{2}$. Consider the sums $S_{0} = a_{1}, S_{1} = a_{2}, S_{2} = a_{1} + a_{2}, S_{3} = a_{1} + a_{2} + a_{3},...$

⟦column⟧

…, $S_{N} -_{1} = a_{1} + a_{2} +$ … $+ a_{N} -_{1}$. (The first two sums are equal to the first two terms, the rest are the sums from the first to the corresponding). By assumption, none of these sums leaves a remainder of 0 when divided by N. Therefore, two of them give the same remainder, and it is not the first and second. But then the difference of the two corresponding sums is divided by N, and this contradicts the condition. Solution to Problem D. Let us immediately admit that we limited ourselves to the number 101, partly to make the formulation easier, and partly to “muddy the waters” a little and slightly cover up the idea. In fact, the fact is true in a fairly general situation. Namely, we replace the number 101 with any prime p, and the number 95 with any number between zero and p and prove that from (p – 1) numbers that give a non-zero remainder when divided by p, we can make a sum that gives any predetermined non-zero remainder when divided by p. Let's arrange these numbers in an arbitrary way. Let's choose any $k, 0 \le k \le ( p - 1 )$, and take the first k of our numbers. Let's make up all possible sums from them (one number or none is also a sum; the sum of an empty set of numbers is assumed to be equal to 0) and write down all the different resulting remainders from dividing these sums by p. In particular, at the first step (if k = 0) there is a single sum, and it is equal to 0. For an arbitrary k, we obtain some numbers $M_{1}$, … $, M_{n}$. If among them there are already all possible remains, then there is nothing to prove. Let it not be so. Let's add to the already selected (k + 1) number (let it be equal to r) and again write down all the sums and all the remainders. The result will be, firstly, the numbers $M_{1}$, … $, M_{n}$ (after all, the last number may not be taken), and secondly, the remainders from dividing the numbers $M_{1} + r$, … $, M_{n} + r$ by p. Now we claim that there is at least one number in the second group that does not appear in the first. In fact, let's assume the opposite. Then it turns out that if the remainder N coincides with one of $M_{i}$, then the remainder N + r also coincides with some other number from the set ${ M_{i} }$. But then also the remainder N + 2r = (N + r) + r also coincides with some other number from the set ${ M_{i} }$, the same is true for N + + 3r = (N + 2r) + r, and so on. From here it easily follows that among ${ M_{i} }$ all possible remainders from division by p already occur, and we assumed that this is not the case. Thus, until not all remainders are written out, the number of different numbers increases at each step. Since the number of steps is equal to p, then no later than at the last step the number of different residues will be at least p, which is required. Since a zero sum arose at the first step (where there were no numbers at all), there is no guarantee that it is possible to obtain a sum with a remainder of 0. And indeed, if we take all numbers equal to each other, then the remainder of 0 does not work out (and this, according to Problem C, is the only case when this remainder does not work out). All other amounts are obtained one way or another.

2. Problem B: Composite numbers

Let us now return to Problem B. For convenience, we denote its statement as BC(n) (“choice of the sum”); Thus, the notation BC(21) is a contraction of the statement “it is true that from any 41 integers we can choose 21 whose sum is divisible by 21.”

⟦folio 46⟧

KVANT 2010/№2

Note, first of all, that the estimate cannot be improved. In fact, if we take only 2p – 2 numbers, then a counterexample can be easily constructed: it is enough to take p – 1 zeros and p – 1 ones. You can also replace zeros and ones with other numbers (if n is prime - with any two different ones, we leave the case of composite n to the readers to sort out). For brevity, below we will call the set of numbers given to us (2p – 1) a “set”, and a “group” its subset of several numbers, the sum of which is divisible by p. We need to prove that there is a group of p elements. We will give the complete solution to the problem (in other words, the statement BC (n) for any n) at the end of the article, but we will start with the proof of a simple statement: if BC (p) and BC (q), then BC (pq). Proof. Let n = pq, and given 2n – 1 numbers ${ a_{k} }$; according to BC(p), from them one can choose a group of p numbers whose sum is divisible by p. Let's put this group aside and look at the remaining numbers. Since more than (2p – 1) numbers remain unused, one more group can be selected from them, the sum of which is also divisible by p. Proceeding in this way further, we will get many groups of p numbers, the sum of each of which is divisible by p; It is easy to see that you can get (2q – 1) groups. Let $S_{1} = p \cdot r_{1}, S_{2} = p \cdot r_{2}$, … $S_{2} q_{-} 1 = p \cdot r_{2} q_{-} 1$ be their sums. Since ${ r_{k} }$ are integers, from them, according to BC ( q ), we can choose q numbers whose sum is divisible by q. Then the sum of the corresponding ${ S_{k} }$ is divided by pq, and this sum contains exactly as many numbers ${ a_{k} }$ as required. It is important to note that in this proof it does not matter whether the numbers p and q are coprime or not. Therefore, it is enough to prove BC ( n ) for the case when n = p is a prime number. This is the only case we will deal with in the future. Let us now prove the statement BC(p) for some values ​​of p. Note that although we will present the proof for a specific number, the facts will be true for different numbers. Therefore, the reader is recommended to evaluate each time: whether this reasoning applies only to a given p or whether it can be generalized.

3. Proof for p = 7

3.1. Increasing the multiplicity of zero. If all 7 possible remainders are found among the given numbers, then there is nothing to prove, since 0 + 1 + 2 + ... + 6 is divisible by 7. Therefore, we can assume that among our 13 numbers there are no more than 6 different remainders. But then one of them occurs at least three times. The number of times a particular residue occurs in our set, we will call it multiplicity. We will assume that a multiplicity of three (or more) has a remainder of 0. (In Section 3.3 we will show how the general case can be reduced to this). If the multiplicity of zero is not less than 7, then again there is nothing to prove. Otherwise, there are at least 7 non-zero remainders, and, according to Problem A, one can choose several of them (say, k), the sum of which is divisible by 7. True, there is no reason to think that k = 7. Let k < 7; Let's consider two cases. a) If k > 3, then we can take these numbers and add several zeros to them (from one to three); you get a group of 7 numbers, and the statement is proven. b) Let now $k \le 3$. Here we need to do things differently. We will replace this set with a new one. It contains k numbers, the sum of which

equal to zero, all replaced by zeros, as in the table:

⟦column⟧

Original set

0 0 0 2 2 3 1 …

Changed set

0 0 0 0 0 0 1 …

(Since 2 + 2 + 3 is divisible by 7, we replaced these numbers with zeros and left the rest unchanged.) Suppose that the problem statement is verified for the new set: it contains a group of 7 numbers whose sum is divisible by 7. Then the same is true for the old set. In fact, let there be several zeros in this group (say, r zeros, $r \ge 0 ).$ If $r \le 3$, then we take the same numbers from the old set (after all, there are three zeros); if r > 3, then instead of three zeros we can take three numbers from the old set, replaced by zeros (the sum will not change from this), and the other numbers are the same as in the new set. So, we have reduced the matter to a new set, where there are zeros more than it was (let's call it this way: “the method of increasing the multiplicity of zero”). Then it is already clear: either we already have 7 zeros, or we can repeat the same reasoning. We will either get the desired set at once, or again increase the number of zeros, and so on. However, for seven it is clear that we will not have to move beyond the second step. Is it possible to apply the same reasoning for an arbitrary p? 1)/2. For large p, we cannot count on this, so we will have to look for other ways. However, the “technique of increasing the multiplicity” will be useful to us further; for now, let’s finish the proof for the case p = 7. 3.2. Induction? Obviously, it would be more natural to construct the argument using the induction method. What is the most convenient way to take n (the induction parameter)? equal to (p + 1 – k), where k is the multiplicity of zero (or the remainder that occurs most often): “if $n \le 1$, then one of the remainders occurs at least p times, and the statement is obvious; therefore, if it was possible to prove that the highest multiplicity can be increased (as we did in section 3.1), then everything is proven.” the highest multiplicity can be increased, everything would be in order, but we cannot prove this. And in the case of p = 7, the use of induction is quite correct, but... it would be “shooting sparrows with cannons”: what kind of induction is it if everything ends in a maximum of two steps? 3.3. Reducing the general case to the particular: transitivity. Our reasoning from section 3.1. assumed that the remainder 0 has the highest multiplicity. Let now, for example, the remainder 2 occur most often. Then subtract 2 from all 13 given numbers; now 0 is most often found. However, the meaning of our problem has not changed: if some group of 7 numbers had a sum divisible by 7, then after subtracting the twos, 14 is subtracted from the sum, i.e. it is still divisible by 7. Thus, the assumption that such and such a remainder has the highest multiplicity (it was convenient for us to assume that this is the remainder 0) does not violate the generality of the argument: subtracting the same thing from all given numbers, we
