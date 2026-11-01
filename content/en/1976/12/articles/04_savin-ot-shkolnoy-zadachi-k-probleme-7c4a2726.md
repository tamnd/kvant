---
id: 1976-12-savin-ot-shkolnoy-zadachi-k-probleme-7c4a2726
issue: kvant_1976_12
year: 1976
number: "12"
title: From a school task to a problem
authors:
  - Савин А. П.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: PARE
lang: en
source: kvant_digital
extraction: vision
content_sha256: dfd2ecd3ea9c19df950724dfb40b4fe29a8ed6c170e6133ef7c4f63987ebba09
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/04_savin-ot-shkolnoy-zadachi-k-probleme-7c4a2726.md
source_content_sha256: 23b0248fd725cb7ee08dfe92c19300be63d3a109c3d8d4e044f6358a4212522b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A. Savin

FROM SCHOOL TASK
- TO THE PROBLEM

Arrangements and transpositions

One day, while flipping through my son’s textbook “Mathematics-5”, I came across the following problem *).

The volumes of the “Children's Encyclopedia” were in the following order: 1, 2, 6, 10, 3, 8, 4, 7, 9, 5. How to put them in order if you can take two adjacent volumes and place them, without changing the order, side by side in a new place (at the beginning, the end, or between two volumes)?

Quite quickly I managed to find a solution. It is depicted on figure 1. But I long ago developed the habit of analyzing a solved problem, and the question immediately arose: “What if it had been nothing else?” A method of rearrangement that did not depend on the first arrangement of the volumes immediately came to mind. First, take the 1st volume and the volume to the right of it and place them at the beginning, then the 2nd volume and the volume to the right of it and place them behind the 1st volume, etc. If the desired volume is at the end of the row, then you should first take any pair of volumes that have not yet been installed and rearrange them to the end of the row, after which the rearrangement of the desired volume will be possible.

I tried this method on the arrangement proposed in the assignment, and with four permutations I put the volumes in the desired order. Then I took the arrangement: 10, 9, 8, 7, 6, 5, 4, 3, 2, 1. After six permutations (see Fig. 2) I came to the following arrangement: 1, 2, 3, 4, 5, 6, 7, 8, 10, 9. Then I discovered that the long-range method does not work. Besides the 9th, there is only one 10th volume left, and there is nothing to move to the end of the row.

I rearranged the volumes again in the same way, but placing other pairs at the end of the row. It took longer to rearrange, but the result remained the same - again at the end of the row there is a combination of 10, 9, which my method cannot cope with. And then I remembered that a similar situation would arise in the sign game “15” *). There, by moving the body, it is impossible to move from the position at figure 3 to the position at figure 4.

The idea of ​​proving this fact is based on the “transposition” operation. The transposition of a certain sequence of numbers is called the change of any two of these numbers. At the same time, it is proved that if one sequence of numbers is obtained from another using an even number of transpositions, then it is impossible to add the same result using an odd number of transpositions, and vice versa, if the sequence

*) In the latest edition of the textbook “Mathematics-5” (M., “Prosveshcheniye”, 1976) this problem appears under number 1249.

*) See «Kvant», 1974, No. 2, p. 26.

⟦folio 3⟧

Since the number of numbers is obtained from another by an odd number of transpositions, it is impossible to obtain it by an even number of transpositions.

It remains to find out whether the operation described in the task corresponds to an even or odd number of transpositions. Moving one volume to a new place is equivalent to a series of transpositions: first with the nearest volume, then with the next one, etc., until it stands in its new place. Likewise, moving the next volume is equivalent to a series of transpositions with the same volumes as in the first case. The total number of transpositions will be equal to twice the number of transpositions when moving one volume, so our operation is equivalent to an even number of transpositions.

Therefore, some volume distances of the operations specified in the job can be ordered, but others cannot. In particular, the distances 1, 2, 3, 4, 5, 6, 7, 8, 10, 9 are obtained from the distances 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 by an odd number of transpositions, and, therefore, the distances of operations cannot be converted into it.

Please note that in our reasoning we ignore the fact that there are 10 volumes. With the same success, these reasoning can be carried out for any other number of volumes.

But the fact that we rearranged two volumes at once was very significant. Indeed, if we rearranged one volume at a time, then for any initial distance with such an operation we could arrange the volumes in order. What if you rearrange three volumes? How about four?...

Half of these questions can be answered immediately. A rearrangement of an even number of volumes corresponds to an even number of transpositions; therefore, with such an operation it is impossible to transform one arrangement into another, resulting from it with an odd number of transpositions.

⟦folio 4⟧

Hy, what if we rearrange three volumes? Let's try it! How many volumes to start with? Three is not enough, let's take four. Let's see what arrangements can be obtained from the arrangement in order: 1, 2, 3, 4 - from it 2, 3, 4, 1 and 4, 1, 2, 3, from which 3, 4, 1, 2... and that's it! Such permutations are called cyclic because they rearrange numbers in a circle - if one arrangement is written along a circle, then any other can be read starting from a certain place (Fig. 5). But no two of the arrangements
1, 2, 3, 4
1, 2, 4, 3
1, 3, 2, 4
1, 3, 4, 2
1, 4, 2, 3
1, 4, 3, 2
cannot be translated into each other by cyclic permutations, and yet each of them corresponds to three more arrangements, obtained by cyclic permutations. Thus, all 24 different arrangements of numbers 1, 2, 3 and 4 (check that there are 24 of them) are divided into 6 groups of 4 arrangements in a group, and with our operation we cannot obtain from the arrangement of one group the arrangement of another group.

Will this situation be maintained if we take not four, but five or larger volumes? It turns out not! The following sequence of arrangements plays a decisive role here:
1, 2, 3, 4, 5 → 1, 3, 4, 5, 2 → 4, 5, 2, 1, 3 → 2, 1, 3, 4, 5.

Rearranging three volumes at a time, we swapped the first and second volumes, returning the rest to their place. In the same way, we can rearrange any two adjacent volumes, not only when we have five volumes, but also for any large number of volumes. Indeed, if these two volumes are not the last, then taking the next volume after them, we rearrange these three volumes forward, then replace the first two volumes (as shown) and again

Let's return the three volumes to their old place. As a result, all volumes will be placed in their original places, except for the two volumes we selected, which are placed in places. If we want to place the last two volumes in places, then we will first take the first three volumes, put them at the end, then perform the described procedure, and finally put the volumes at the beginning in their old place.

Telery, apparently, the statement will not be unexpected for you: if the number of volumes is not less than ly, then any arrangement of these volumes can be converted into an arrangement in order, rearranging the momas in triplets *). After all, if you move neighboring volumes in places, you can first move the first volume to the first place, then the second volume to the second, etc.

What will happen if five volumes are rearranged? Seven volumes each? In general, according to 2n + 1 volume? I haven't found a solution to this problem anywhere.

You can ask: “Who needs these changes?” It turns out that they are needed, and very often, for example, the theory of permutations plays a crucial role in solving the question of whether a given algebraic equation can have roots *). Thus, we solved problem M404 («Kvant», 1976, no. 9).

⟦folio 5⟧

not the $n$th degree can be expressed using radicals (as is done for a quadratic equation). It was found that equations of the third and fourth degrees have this property, and for equations of the fifth degree and higher, the roots, as a rule, can no longer be expressed through coefficients using radicals.

This has already been discussed in «Kvant», most recently in the articles “Groups” and “Algebra - Ancient and Modern” («Kvant», 1976, No. 10). If you read them, you will immediately notice that the volume variables we are considering are permutations that generate a group (though not the entire group of permutations $S_n$ - this is the problema), and permutations around the circle of four elements form a cyclic group. maybe group theory will help you (although, most likely, this problem is solved by “combinatorial” messages).

Now, having wished success to those who decided to take on the final solution to the problem posed, we will add more interesting problems in the textbook.

One or more?

Find integer natural numbers such that the sum of the product of any three of them and 1 is divisible by an integer.

The first thing that comes to mind is to take all numbers equal to 1. Such a quadruple of real numbers satisfies the conditions of the problem. Are there any other solutions? I saw this task somewhere. I open the book by I. L. Babinskaya “Mathematical Optimization Problems” (M., “Hayka”, 1975) and find it under number 142. I am looking for an answer. I read - “For example, 1, 2, 3, 7.” This answer does not STRAINEM to me. For me, this is the same as answering: “For example, 2” to the question: “What are the roots of the equation $x^2 - 5x + 6 = 0?$.”

No... I saw a similar task somewhere else. Well, of course, “Collection of problems of Moscow mathematical optimization” (M., “Prosveshchenie”, 1965), p. 70, problem 215. Here it is.

215. The name of triplets of numbers $a, b, c$, different from 1, what about

the product of any two triplets added to one is divided by the prime number.

The answer is a single set: 2, 3, 7.

Isn't it true, the answer is very similar to the answer to our interim problem, although here we are talking not about four, but about three numbers. What happens for two numbers? For what pairs of numbers does the sum of each of them with one divide by the other? A problem with four numbers for fifth-graders, with a problem for students in grades 7-10... However, let’s muster up the courage and be present to the solution.

If one of these two numbers is 1, then the second number must be a divisor of the number 2: either 1 or 2. It is easy to check that both pairs (1, 1) and (1, 2) satisfy the conditions of the problem.

Let none of the numbers be equal to 1. Then, obviously, these numbers are coprime. Let $a < b$, then $a + 1 \leq b$, but $a + 1$ is divisible by $b$, hence $a + 1 \geq b$. It follows that $a + 1 = b$. And since $b + 1$ is divisible by $a$, then $a + 2$ is divisible by $a$, therefore 2 is divisible by $a$, and since $a \neq 1$, then $a = 2$, $b = 3$.

So, there are all three pairs of numbers such that the sum of one of them and one is divisible by the other: (1, 1), (2, 1), (3, 2).

A fairly simple solution to this problem makes me think of trying to solve the general problem at once:

“Find $n$ numbers such that the product of any $n - 1$ of them added to one is divisible by the remainder.”

Let us prove two lemmas.

Lemma 1. Let the numbers $a_1, a_2, \dots, a_n$ have the property that the product of any $(n - 1)$ of them in sum with 1 is divisible by the remainder. Then, adding the number $a_{n+1} = 1$ to them, we get a set of numbers, the product of any $n$ of which in the sum of 1 is divided by the remainder. And, conversely, if among the $n + 1$ numbers there is 1 and the product of any $n$ of them in the sum of 1 is divided by the remainder, then by removing from

⟦folio 6⟧

This is a set of one, we get a set of n numbers, the product of any n - 1 of which, in sum with one, is divided by the rest.

The formulation of the lemma is cumbersome, but the proof is trivial. It is enough to use the fact that multiplying a number by one does not change the number, and the fact that any number is divisible by one.

The second lemma is more meaningful.

Lemma 2. Let the numbers $a_1, a_2, \dots, a_n$ have the property that the product of any $(n-1)$ of them in sum with 1 is divisible by the rest. Then, adding the number $a_{n+1} = a_1 a_2 \dots a_n + 1$ to them, we get a set of numbers, the product of any n of which, in sum with unity, is divided by the rest.

To prove it, you need to check two statements.

The first is that the product of the first n numbers added to unity is divisible by $a_{n+1}$ - follows from the definition of the number $a_{n+1}$.

The second is for the case when the number $a_{n+1}$ is included in the product. Let us denote by $A_i$ the product of the first n - 1 numbers without $a_i$: we must show that $A_i a_{n+1} + 1$ is divisible by $a_i$. To do this, it is enough to note that $a_{n+1} = a_i A_i + 1$; then $A_i a_{n+1} + 1 = A_i (A_i a_i + 1) + 1 = a_i A_i^2 + (A_i + 1)$, and the first term is divided by $a_i$, the second, enclosed in brackets, is also divisible by the proposition of the lemma.

From these lemmas it follows that in the problem with numbers there will be the following solution: $(1, 1, 1), (1, 1, 2), (1, 2, 3), (2, 3, 7)$; in a problem with four numbers $(1, 1, 1, 1), (1, 1, 1, 2), (1, 1, 2, 3), (1, 2, 3, 7), (2, 3, 7, 43)$. It remains to be seen whether there are other solutions.

Obviously, there are no new solutions containing units for $n=3$ (by removing one of the units, by Lemma 1 we would obtain a new solution to the problem with two numbers, but there are no other solutions in it). Let now $(x, y, z)$ be some solution to the problem with three numbers. It is easy to prove that any two of these numbers must be relatively prime. Let $2 \leq x < y < z$.

Let's write down the correspondences:

$$\begin{align*}
xy + 1 &= k_1 z, \\
xz + 1 &= k_2 y, \\
yz + 1 &= k_3 x.
\end{align*}$$

Here $k_1, k_2, k_3$ are natural numbers. Variable these correspondences, we get: $xyz(xyz + x + y + z) + xy + yz + xz + 1 = k_1 k_2 k_3 xyz$.

It follows that $xy + yz + xz + 1$ is divisible by $xyz$, i.e.

$$xy + yz + xz + 1 = Axyz,$$

where $A$ is a natural number. Dividing both sides of this equality by $xyz$, we get

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} + \frac{1}{xyz} = A.$$

The smallest value of $A$ will be obtained at the smallest values ​​of $x, y, z$, i.e. at $x=2, y=3, z=4$ (actually $z \geq 5$). From here

$$A \leq \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \frac{1}{2 \cdot 3 \cdot 4} = \frac{27}{24},$$

and since $A$ is a natural number, it is equal to 1. So, we need to find all natural numbers $x, y$ and $z$ such that $2 \leq x < y < z$ and

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} + \frac{1}{xyz} = 1.$$

Let us show that $x=2$. Indeed, if $x \geq 3$, then $y \geq 4, z \geq 5$, therefore,

$$1 = \frac{1}{x} + \frac{1}{y} + \frac{1}{z} + \frac{1}{xyz} \leq \frac{1}{3} + \frac{1}{4} + \frac{1}{5} + \frac{1}{3 \cdot 4 \cdot 5} = \frac{48}{60}.$$

We received a contradiction. So, $x=2$. Then the correspondence is written like this:

$$1 = \frac{1}{2} + \frac{1}{y} + \frac{1}{z} + \frac{1}{2yz}.$$

Expressing $y$ from here, we get

$$y = 2 + \frac{5}{z - 2}.$$

This means that $z-2$ is a divisor of the number 5, i.e. $z=3$, or $z=7$. In the first case $y=7$, in the second $y=3$.

So, $(2, 3, 7)$ is the only solution to the problem with three numbers that do not contain units, therefore, we wrote down all the solutions to this problem.

Let's see if there are other solutions to the problem with four numbers.

⟦folio 7⟧

Obviously, here too it is sufficient to consider only those solutions that do not contain unity. i.e. natural numbers $x, y, z, u$ such that $2 \leq x < y < z < u$ and
$$xyz + 1 = k_1u,$$
$$xyu + 1 = k_2z,$$
$$xzu + 1 = k_3y,$$
$$yzu + 1 = k_4x,$$
where $k_1, k_2, k_3$ and $k_4$ are natural numbers. Variable these correspondences, we obtain, similarly to the previous case, that
$$xyz + uxy + xzu + yzu + 1 = Axyzu,$$
where $A$ is a natural number, or
$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} + \frac{1}{u} + \frac{1}{xyzu} = A.$$
Since $x \geq 2, y \geq 3, z \geq 4, u \geq 5$, then
$$A \leq \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \frac{1}{5} + \frac{1}{2 \cdot 3 \cdot 4 \cdot 5} = \frac{31}{24},$$
hence $A = 1$. Further, it is shown in a similar way that $x=2, y=3$. Now
$$\frac{1}{z} + \frac{1}{u} + \frac{1}{6zu} = \frac{1}{6},$$
where
$$z = 6 + \frac{37}{u - 6}.$$
This means that $u-6$ is a divisor of 37, i.e. either $u=7, z=43$ or $u=43, z=7$. So, again we only got existing solutions. This means that in this case all the solutions were listed.

The obtained result illustrates our hypothesis that further all solutions to the problem for $n$ numbers will be obtained from the solution to the problem for $n-1$ numbers using Lemmas 1 and 2. Alas! This hypothesis is incorrect, at least for $n-5$ - in addition to the solution (2, 3, 7, 43, 1807) obtained using Lemma 2, there is one more: (2, 3, 7, 47, 395).

What will happen next? Will solutions to the problem for a large number of numbers be obtained by applying Lemmas 1 and 2 to these now two solutions that do not contain one, or will one or even two more appear? So far this is a problem.

How many divisions?

The following “ingenuity” task also appears in many books for schoolchildren.

Fig. 6.

The length of the ruler without divisions is 13 cm. How to put 4 divisions inside the ruler so that with its help you can set aside any of the given lengths. Here you also need to indicate the corresponding length directly on the ruler, from division to division (or to the end of the ruler).

figure 6 shows one solution to this problem. It is natural to try to find out if there are other solutions, but much more interesting questions are also: why four divisions? What if there are three? What is the longest ruler on which you can mark 4 divisions with the specified property? And in general, what is the smallest number of divisions that need to be placed on a ruler of length $n$ (cm) so that it can be used to plot all integer segments from 1 cm to $n$ (cm)?

As always, we start with samples. For a ruler 1 cm long, no divisions are needed. With a length of 2 cm and

⟦folio 8⟧

Fig. 7.

3 cm is enough for one division. With a length of 4, 5, 6 cm, two divisions are enough, but one is not enough; with a length of 7, 8, 9 cm, three divisions are needed (two are not enough), with a length of 10, 11, 12, 13 cm - four divisions (three are not enough). These results were obtained by searching through the options, the corresponding arrangements are depicted in figure 7, but as the length of the ruler increases, it becomes more and more difficult to carry out a complete search. We need some general methods. Let's first try to estimate the number of divisions (top and bottom).

Let there be $k$ divisions on a ruler of length $n$ (cm). How many different segments are there (not segments of different lengths, but simply different segments) with ends at the division points or at the ends of the ruler? Since any pair of the listed points defines a segment, and there are $k+2$ of them, then there will be $(k+2)(k+1)/2$ segments. And since, according to the conditions of the problem, we should obtain $n$ of different lengths, and some of the long segments may coincide, then the inequality must be satisfied

$$n \geq \frac{(k+2)(k+1)}{2}.$$

It follows that on a segment of length $n$ it is necessary to put at least $(\sqrt{8n+1}-3)/2$ divisions (if this number is not an integer, then it is necessary to be close to it more than an integer).

How many divisions will probably be enough? Of course, $(n-1)$ is enough (all centimeter divisions can be applied), but is it possible to get by with a smaller number?

Let's try this arrangement of $k$ divisions: first we put $m$ divisions through each centimeter, then a division through $(m+1)$ (cm), again through $(m+1)$ (cm), etc., until we have placed all $k$ divisions. Let us now consider a ruler with the right end $(m+1)$ (cm) from the last division. The length of this ruler $l$ can be expressed through $k$ and $m$: $l = m + (k-m)(m+1) + m+1 = -m^2 + m(k+1) + (k+1)$.

Using the division formula with remainder $s = p(m+1) + q$, it is easy to show that for any $m$ the arrangement of divisions also satisfies the conditions of the problem.

Let us note one more important property of this arrangement of divisions - if the segment is shortened on the right by any whole number of centimeters, then the division points will still satisfy
