---
id: 2020-4-kanunnikov-primeryi-i-kontrprimeryi-287bf0de
issue: kvant_2020_4
year: 2020
number: "4"
title: Examples and counterexamples
authors:
  - Канунников А. Л.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 25
page_last: 28
page_labels: 23, 25, 26
tag: 9EM8
lang: en
source: kvant_digital
extraction: native
content_sha256: 5683b32c51018d2cc7c9dea999892e1a58f328df36233fc67f35c5bb37877b65
prompt_sha256: draft-1
translated_from: content/ru/2020/04/articles/03_kanunnikov-primeryi-i-kontrprimeryi-287bf0de.md
source_content_sha256: 195ed96770da47f9defa814e0cda170be9a0ae3033f405364e3384023e746109
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

"QUANTUM"

FOR

M L A D S I H

SH K O L NIK O V

Examples and counterexamples

A.KANUNIKOV

About one criterion of divisibility Let's start with this example. The test of divisibility by 3 is well known: a number is divisible by 3 if the sum of its digits is divisible by 3. A similar test of divisibility by 9 is valid. For example, 145287 is a multiple of 9, since $1 + 4 + 5 +^{2} + 8 + 7 = ( 1 + 8 ) + ( 4 + 5 ) + (^{2} + 7 ) = = 3 \cdot 9$ is a multiple of 9. Is a similar test of divisibility by 27 valid? Take, for example, the smallest number with a sum of digits of 27: 999. It is easy to see that it is a multiple of 27 (it is enough to divide it by 9 and get the number 111, a multiple of 3). Let's take another example: 11...11 (27 units). Dividing it by 3, we get the number of 9 blocks 037:

111 111 … 111: 3 = 37 037 … 037.

The sum of the digits of the resulting quotient is equal to $( 3 + 7 ) \cdot 9$ and is a multiple of 9, which means that the quotient itself is divisible by 9, and then the original number of 27 units is divided by 27. We analyzed two examples, but even if we found a million confirming examples, we would not prove the sign. On the contrary, the number 9981 shows that our criterion is incorrect: although 9 + 9 + 8 + 1 = 27, but 9981 is not a multiple of 27, since 9981: 9 = 112 is not a multiple of 3. The number 9981 refutes the incorrect criterion of divisibility by 27. In general, an example that refutes a statement is called a counterexample. Let us present a humorous “theorem”: in mathematics there are no terms in the name of which five consonants appear in a row. The very word “counterexample” is a counterexample to this “theorem”.

⟦column⟧

2*. The test for divisibility by 27 with a sum of digits is incorrect in the decimal number system. Think about why the signs of divisibility by 3 and 9 are true in it, and try to understand in which number systems a similar test of divisibility by 27 is true.

About one criterion for the equality of triangles Let's move on to geometry. It is quite obvious that if two sides and the angle between them of one triangle are respectively equal to two sides and the angle between them of another triangle, then such triangles are congruent (Fig.1). This statement is called the first criterion for the equality of triangles. Briefly they say this: triangles are equal in two sides and the angle between them. Let's think about whether a similar sign will be true if the words “between them” are replaced with the words “not between them” (Fig.2.) This hypothesis is confirmed by the well-known fact that right triangles are equal in leg and hypotenuse: the right angle lies

⟦figure⟧

Fig. 1

Exercises 1. Find the smallest counterexample to the “divisibility test by 27”, i.e. The smallest natural number, not a multiple of 27, whose sum of digits is a multiple of 27.

DOI: https://doi.org/10.4213/kvant20200403

Fig. 2

⟦folio 25⟧

"QUANTUM"

FOR

M L A D S I H

in turn, whether it is divisible by 2; by 3;... by 9. Dima answered all eight questions correctly, and the answers “yes” and “no” were equally divided. a) Can you now answer at least one of the teacher’s questions correctly, without knowing the number itself? b) How about at least two questions? Of course, if we can answer two questions, then even more so one. Therefore, “according to the laws of the genre,” most likely the answer to point a) is yes, and to point b) no. Of course, this is not guaranteed. But you must admit, it would be strange to ask two questions if we cannot even answer one clearly. Let's start by trying to come up with an example for point a). It begs to check the answer to the teacher’s first question - whether the written (and unknown to us) number N is divisible by 2. If the answer is “no”, then the number is odd and therefore is not divisible by either 4, 6, or 8. Since the answers “divisible” and “not divisible” are equal, it means that the number N must be divisible by the remaining four numbers 3, 5, 7, 9. But then it is divisible by $3 \cdot 5 \cdot 7 = 105$ and is in no way two-digit. The resulting contradiction shows that the number N is exactly divisible by 2, so the answer to point a) is affirmative. Let's move on to point b). Our intuition tells us that the answer is “no,” but we don’t know for sure. Let's call a two-digit number good if the teacher could write it on the board, i.e. if it is divisible by exactly four numbers from 2 to 9. In part a) we proved that every good number is even. We will try to prove the answer “yes” in point b), i.e. find a number from 3 to 9 that every good number is exactly divisible or not exactly divisible by. Is there, for example, a good number that is a multiple of 9? If so, then it is also a multiple of 3, and also 2, and then 6. There are already 4 divisors: 2, 3, 6, 9. The smallest such number is 18 - it is really good. Let's now try to find a good number that is a multiple of 8. It is automatically divisible by 2 and 4 - already three divisors. If it is divisible by 3, then it is divisible by 6 - there are already five divisors. But it can be divisible by 5: 40 is a good number with divisors of 2, 4, 5, 8.

SH K O L NIK O V

⟦column⟧

Examples of the numbers 18 and 40 show that it is impossible to answer unambiguously whether a good number is divisible by 3, 4, 5, 6, 8, 9 or not: each time the answers for the numbers 18 and 40 are different. We just have to decide on seven: 18 and 40 are not divisible by 7. Is there a good multiple of 7? Yes, it’s easy to give an example by taking the number $56 = 8 \cdot 7$ instead of the number $40 = 8 \cdot 5$. So we have proven that the answer to point b) is “no”. Problem 3. a) Can a company’s work be profitable for any five months, but unprofitable for the whole year? b) Can this situation continue for six years? (In other words, based on the results of any five consecutive months, the company makes a profit, and based on the results of each of the six years, it suffers a loss.) At first glance, this cannot be the case, but let’s not rush to conclusions. In paragraph b) a period of six years is indicated “to divert attention.” In fact, the described situation is impossible even for five years - after all, such a period of time is divided into 12 segments of five months and all of them are profitable according to the condition. So, in point b) the answer is “no”. Let's move on to point a), not yet knowing whether our reflections will lead to an example or a refutation. Let's reformulate the question in mathematical language: can the sum of 12 numbers be negative, while the sum of any 5 consecutive numbers is positive? If so, then the sum of the first ten numbers is positive, and then the sum of the last two is negative. On the other hand, the symmetrical conclusion is true: the sum of the first two numbers is negative, and the sum of the remaining ten numbers is positive. Finally, having considered the outer five numbers, we find that the sum of the two numbers in the middle is negative. To give an example, let us also take into account that the 1st and 12th numbers each participate in only one top five, so we will shift the “main responsibility for the loss” to them. From these considerations it is not difficult to come up with an example:

$- 5, 0,^{2,} 2,^{2,} - 1, -^{2,} 2,^{2,} 2, 0, - 5$.

⟦folio 26⟧

KVAN T 2020/№4

The entire sum is $- 2$. Carefully check each five consecutive numbers.

Who is more, or “Evaluation + example”

Very often in problems it is necessary not only to give an example, but also to prove its optimality in some sense (largest number, shortest operating time, etc.). Accordingly, solutions to such problems consist of two parts. When we give an example, we only need to show that it satisfies the condition. When proving optimality, it is not enough to give several counterexamples, saying that we couldn’t do better. It is necessary to prove that no one can do it better! Problem 4. The Rabbit poured three kilograms of honey into five pots standing in a row (not necessarily into each one and not necessarily equally). Winnie the Pooh can take any two pots that are next to each other. What is the largest amount of honey that Winnie the Pooh is guaranteed to eat? If the Rabbit spills the honey equally, then Pooh will get 6 5 kg. But the Rabbit can do something more cunning: pour a kilogram into pots 1, 3 and 5, and then Pooh will take 1 kg. Can the thrifty Rabbit save even more honey? After going through the options, we come to the hypothesis that no. Let’s prove this and at the same time show how we can come to the answer 1 kg if we didn’t immediately guess the Rabbit’s cunning method. Let Pooh be guaranteed to take only x kg and no more. This means that no matter how the Rabbit pours honey, each pair of pots $( 1,^{2} ), (^{2,} 3 ), ( 3, 4 ), ( 4, 5 )$ contains no more than x kg, and in some pair there are exactly x kg. Adding up the contents of the pairs ( 1, 2 ), ( 3, 4 ) and adding the 5th pot (which also contains no more than x kg), we obtain that the total mass is no more than 3x kg (Fig.5). But according to

Fig. 5

⟦column⟧

condition it is equal to 3 kg. So, $3 \le 3x$, i.e. $x \ge 1$. This means that the Rabbit may not hope to save more than two kilograms of honey. By the way, from this reasoning the above example and its uniqueness are obtained. Namely, for x to be equal to 1, it is necessary that there be exactly 1 kg of honey in the 5th pot. But then, symmetrically, there is exactly 1 kg in the 1st pot. Now it is clear that the 2nd and 4th pots should be empty, and the 3rd should be 1 kg.

Exercise 5. The family approached the bridge at night. Dad can cross it in 1 minute, mother in 2, son in 5, and grandmother in 10 minutes. They have one flashlight. The bridge can only support two people. If two people cross, they walk at the lower of their speeds. You cannot cross the bridge without a flashlight. You can't shine from afar. You can't carry each other in your arms. In what shortest time can a family cross the bridge?
