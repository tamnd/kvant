---
id: 2020-8-knop-volshebniki-dzhona-konveya-1cd5a016
issue: kvant_2020_8
year: 2020
number: "8"
title: The Wizards by John Conway
authors:
  - Кноп К. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 43
page_last: 45
page_labels: 42-43
tag: LF8A
lang: en
source: kvant_digital
extraction: native
content_sha256: bbc64c26493e8e96e2cc2222705e64ae2e4c185eaf5e1632cd53c713f8cee553
prompt_sha256: draft-1
translated_from: content/ru/2020/08/articles/06_knop-volshebniki-dzhona-konveya-1cd5a016.md
source_content_sha256: 500f4c9043d74d28a7f91d9e644276bc09554c5fb552f7f678f09691120cde36
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

The Wizards by John Conway

K.KNOP

REMARKABLE MATHEMATICAL John Horton Conway is famous not only for his development of combinatorial game theory, but also for his enormous contributions to entertaining mathematics. I first heard one of Conway’s most intriguing problems in a retelling by T. Khovanova [1], and it was this story that served as the basis for this article. Here is the problem: Last night I was on the same bus with two wizards and overheard their conversation: A: I have several children, the age of each of them is a positive integer, and their sum is equal to the number of this bus, and the product is my own age. B: How interesting! Perhaps if you tell me your age and the number of your children, I can calculate their ages? A: No, you can't. B: Yeah! Finally I found out your age. What was the number of the bus we were on? I'll start with some comments. The author of the puzzle, John Conway, carefully thought through its entire surroundings. In particular, the bus (bus) was chosen as the setting because, together with the age of the first wizard (age) and the number of his children (children), Conway obtained convenient notations for three numerical values ​​- a, b, c. Perhaps I will also keep these designations. So, let a be the age of the first wizard, b be the bus number (unknown to us, but known to the second wizard), and c be the number of children of the first wizard. The second remark concerns wizard A's phrase "No, you can't." In this statement, the wizard does not doubt his friend’s intellectual abilities at all. It means that even given a completely known triple of numbers a, b, c it is impossible

DOI: https://doi.org/10.4213/kvant20200804

⟦column⟧

clearly determine the age of children. In other words, there are several different sets of children's ages that give the same values ​​of a, b, c. Let's call such sets of ages Conway, or K-sets. What makes this puzzle incredibly beautiful is that it is very difficult to approach. If we knew the age of the wizard (the number a), then we could go through his divisors and find all the variants of their sums. If the bus number (b) was known, it would be possible to decompose it in various ways into the sum of terms and obtain variants for their products. And even if we only knew the number of children (c), the size of the search would still be significantly smaller. Some of my friends spent several hours programming and trying out options and only then figured out how to approach the right decision. Isn’t it true, the task seems completely underdetermined, i.e. allowing different solutions? Here is one of the typical arguments. Let's say they are traveling on bus number 21 (b 21), the wizard is 96 years old (a 96) and has three children (c 3). This means that their ages are three natural numbers with a sum of 21 and a product of 96. There are two such triplets of numbers: 1, 8, 12 and 2, 3, 16, i.e. Indeed, even if the second wizard finds out all this, he will not be able to determine the age of the children. Isn't this answer any good? Why? Haven't we found numbers that satisfy all the conditions from the wizards' dialogue? No, they didn't find it. The answer “96 years old, bus number 21, 3 children” is not good because it does not take into account the very last line - that wizard B was able to find out the age of wizard A. Could he have done this if he only knew the bus number? In other words, are there other K-tuples of numbers with the same b, but a different a? To answer this question, let's pose it differently. Are there other K-triples of numbers with a smaller b and a different a? After all, if they are found, then you can simply add several one-year-old children to them so that the total sum of numbers (number b) in the resulting Set turns out to be equal to 21. In this case, the product (number a, i.e. the age of the wizard) will not change and will remain different from the old one. Indeed, such K-triples are easy to find: for example, these are 1, 5, 8 and 2, 2, 10. Add-

⟦folio 42⟧

KVA NT 2020/No.8

By adding one-year-old children to them, you can get a K-set with any b! 14 (and the age of the wizard is 40 years). And from K-tuples 1, 6, 6 and 2, 2, 9, a similar operation gives a K-tuple with any b! 13, while the wizard is 36 years old. Thus, the bus number cannot be more than 13 - because in this case, wizard B would not be able to understand whether his partner is 40 years old or 36 (and perhaps there would be some other options). It seems that we have grabbed this puzzle by the right “tail”. We need to find the smallest bus number that gives two K-sets - and then all subsequent numbers will not work.

Lyrical digression

Could wizard A have only one child? Obviously not: then his age would coincide with both the bus number and the age of A, and this is the only case when b a. Consequently, having learned (calculated) a, wizard B would immediately determine the number of children (from 1) and the age of this child - but we must believe A, who claims that this cannot be done. What about two children (c 2)? Then, having calculated the age of a and knowing the bus number of b, wizard B would know the sum and product of two natural numbers. Can he find the numbers themselves? The geometric analogy of this problem is that the semi-perimeter and area of ​​the rectangle whose sides we want to find (Fig.1) are known. It turns out that in

⟦figure⟧

Fig. 1

In this case, you can find out the numbers themselves (in the geometric version, the sides of a rectangle) even if they are not integers, but for this you need to be able to solve quadratic equations. In our case, we can get by with a simple search: find all pairs of numbers with a given sum, starting with the pair 1 and b 1, and then “bringing together” the numbers - their product will increase. At the moment when the product is equal to a, the required numbers are found. Thus, even for two children, A could not say “No.” Therefore, when enumerating, you can discard all options with one and two children.

⟦column⟧

Is there anything else that can be discarded? Yes. Since we want to find the minimum bus number that gives ambiguity in the choice of children’s ages, there should not be matching numbers in different KSets - because if there were, they could be removed from each set, and then the bus number (sum) would be even smaller. For example, if one of the sets contains a one-year-old child, then the other should not have it. Therefore, in one of the K-sets all children are over one year old. Let's sum up the intermediate results. We will now look for decompositions of the bus number b into the sum of several natural terms greater than 1. In this case, we consider only those decompositions in which the number of terms is not less than 3, and the bus number itself is not more than 12 (because for 13 we already know the required pair of K-tuples, and we want to either find an even smaller one, or make sure that it does not exist). Let's go! Going through options is certainly not the most pleasant job, but sometimes necessary for successfully solving life’s problems. In our search, we will mark with an icon the lines with those values ​​of a that occur (in the entire search) more than once, and with different b. First, we list the expansions in which each term is greater than 1: 6 2 + 2 + 2 (a 8) 7 2 + 2 + 3 (a 12) 8 2 + 2 + 2 + 2 (a 16) 8 2 + 2 + 4 (a 16) 8 2 + 3 + 3 (a 18) 9 2 + 2 + 2 + 3 (a 24) 9 2 + 2 + 5 (a 20) 9 2 + 3 + 4 (a 24) 9 3 + 3 + 3 (a 27) 10 2 + 2 + 2 + 2 + 2 (a 32) 10 2 + 2 + 2 + 4 (a 32) 10 2 + 2 + 3 + 3 (a 36) 10 2 + 2 + 6 (a 24) 10 2 + 3 + 5 (a 30) 10 2 + 4 + 4 (a 32) 10 3 + 3 + 4 (a 36) 11 2 + 2 + 2 + 2 + 3 (a 48) 11 2 + 2 + 2 + 5 (a 40) 11 2 + 2 + 3 + 4 (a 48) 11 2 + 3 + 3 + 3 (a 54) 11 2 + 2 + 7 (a 28) 11 2 + 3 + 6 (a 36) 11 2 + 4 + 5 (a 40) 11 3 + 3 + 5 (a 45) 11 3 + 4 + 4 (a 48) 12 2 + 2 + 2 + 2 + 2 + 2 (a 64)

⟦folio 43⟧

MATHEMATICAL

12 2 + 2 + 2 + 2 + 4 (a 64) 12 2 + 2 + 2 + 3 + 3 (a 72) 12 2 + 2 + 2 + 6 (a 48) 12 2 + 2 + 3 + 5 (a 60) 12 2 + 2 + 4 + 4 (a 64) 12 2 + 3 + 3 + 4 (a 72) 12 3 + 3 + 3 + 3 (a 81) 12 2 + 2 + 8 (a 32) 12 2 + 3 + 7 (a 42) 12 2 + 4 + 6 (a 48) 12 2 + 5 + 5 (a 50) 12 3 + 3 + 6 (a 54) 12 3 + 4 + 5 (a 60) 12 4 + 4 + 4 (a 64) The search is not over yet: after all, there are still Ksets with one, and there are probably more of them. What to do with them? We will not write them out separately, but we will add sets of one and two terms to those already written out, and then we will track each of the options according to the already written table - after all, adding one or several units (i) preserves the product; (ii) increases the number of children by some amount; (iii) increases the number b by the same amount, i.e. the sum of the children's ages. To the previously written sets are added: 2 2 (a 2) 3 3 (a 3) ... 11 11 (a 11) 4 2 + 2 (a 4) 5 2 + 3 (a 6) 6 3 + 3 (a 9) 6 2 + 4 (a 8) 7 3 + 4 (a 12) 7 2 + 5 (a 10) 8 4 + 4 (a 16) 8 3 + 5 (a 15) 8 2 + 6 (a 12) 9 4 + 5 (a 20) 9 3 + 6 (a 18) 9 2 + 7 (a 14) 10 5 + 5 (a 25) 10 4 + 6 (a 24) 10 3 + 7 (a 21) 10 2 + 8 (a 16) 11 5 + 6 (a 30) 11 4 + 7 (a 28) 11 3 + 8 (a 24) 11 2 + 9 (a 18) We will no longer write out sums 12 and above, since after adding units they will increase.

CIRCLE

⟦column⟧

Since K-tuples must have the same a, we will only be interested in the rows marked with a. Let's write out all the sets again, ordering them in ascending order a: 5 2 + 3 (a 6) 6 6 (a 6)

6 8

2 + 2 + 2 8 (a 8)

2 + 4 (a 8)

6 9

3 + 3 (a 9) 9 (a 9)

7 2 + 5 (a 10) 10 10 (a 10)

7 8

2 + 2 + 3 3 + 4 (a 12) 2 + 6 (a 12)

8 2 + 2 + 2 + 2 2 + 2 + 4 10 2 + 8 (a 16)

4 + 4 (a 16)

8 2 + 3 + 3 (a 18) 9 3 + 6 (a 18) 11 2 + 9 (a 18)

9 2 + 2 + 2 + 3 2 + 3 + 4 (a 24) 10 2 + 2 + 6 (a 24)

10 11

2 + 3 + 5 (a 30) 5 + 6 (a 30),

10 2 + 2 + 2 + 2 + 2 2 + 4 + 4 (a 32) 12 2 + 2 + 8 (a 32)

10 11

2 + 2 + 2 + 4

2 + 2 + 3 + 3 3 + 3 + 4 (a 36) 2 + 3 + 6 (a 36)

11 2 + 2 + 2 + 2 + 3 2 + 2 + 3 + 4 3 + 4 + 4 (a 48) 12 2 + 2 + 2 + 6 2 + 4 + 6 (a 48)

11 2 + 3 + 3 + 3 (a 54) 12 3 + 3 + 6 (a 54) Well, now you can complete the puzzle to the end in any way you like - for example, discard all options containing equal terms (because if there are such terms, then after discarding them, you get another set, with a smaller sum and a smaller product). And we can take into account that a larger value of the sum b in another K-set corresponds to a larger number of children. One way or another, of all the lines written out, only two suit us -

11 12

3 + 4 + 4 (a 48) 2 + 2 + 2 + 6 (a 48)

They lead to two such K-sets: 12 1 + 3 + 4 + 4 2 + 2 + 2 + 6. So, we were driving
