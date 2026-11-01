---
id: 2025-5-6-knop-ispyitaniya-dlya-barona-m-04e602e3
issue: kvant_2025_5-6
year: 2025
number: 5-6
title: Tests for Baron M.
authors:
  - Кноп К. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 44
page_labels: 39-42
tag: YMZW
lang: en
source: kvant_digital
extraction: native
content_sha256: 59b792ad360e73092272177439ec47984453763712090c00cae1d98ed057d3d3
prompt_sha256: draft-1
translated_from: content/ru/2025/05-06/articles/04_knop-ispyitaniya-dlya-barona-m-04e602e3.md
source_content_sha256: 069d1017a43ad05b130d418c549c5b7ac2d694a92e2defff7a0e303d652dd9d1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Tests for Baron M.

K.KNOP

IN THE MOST STANDARD Plot of weighing problems, there are scales (or another device) and some information about unknown objects (coins) is given. For example, it says how many “fake” coins there are, and also says whether they are lighter than real coins (or it is said that they may not only be lighter, but also heavier). However, there is a separate class of tasks in which all this is supplemented by a powerful tool - the most honest expert Baron M., who knows everything necessary about all coins. The main difficulty is that the baron must strictly prove all the information known to him using weighings. And since scales are a traditional symbol of Themis, the second character in such tasks is the judge. The judge knows some of the information from the problem statement, but not all the information known to the expert. What tests will the baron face in such evidentiary exercises? What's the math behind this? Without pretending to fully cover all possible problems, we will dwell on some of them.

DOI: https://doi.org/10.4213/kvant20250504

⟦column⟧

Test 1. Uninteresting Baron M. has 12 coins. Half of them weigh 4 g, and the other half weigh 5 g. The judge knows this information, but does not know which coins weigh what. Will the baron be able to prove to the judge the mass of each coin in one weighing? Note. All light coins together weigh 24 g, and five heavy coins weigh 25 g. Test 2. Uninteresting Baron M. has 6 coins of 4 g, 5 coins of 5 g and 4 coins of 6 g. How can he prove to the judge the mass of each coin in one weighing? Note. Exactly 24 g must be placed on each scale. Test 3. Eight weights, one weighing The baron presented 8 weights to the court. He knows the mass of each weight, but the judge only knows that the masses of the weights are consecutive integers from 1 to 8. The Baron is allowed to demonstrate only one weighing. How can he prove to the judge the mass of any one weight? Let's give the floor to the expert - Baron M. - Your Honor, I put 5 weights on the left pan of the scale, and two on the right. Do you see that the scales are in balance? This means that the mass of my 5 weights is the same as that of the other two. But the mass of any two weights available is no more than 7 + 8 = 15 g, and any five weights are no less than 1 + 2 + 3 + 4 + + 5 = 15 g, which means equality is possible only when there is exactly 15 g on each bowl, i.e. on

⟦folio 39⟧

MATHEMATICAL

The left bowl actually contains weights weighing from 1 to 5 g, and the right bowl contains weights of 7 and 8 g. This means that the only unweighed weight should have a mass of 6 g! Test 4. Six weights, two weighings The baron presented 6 weights to the court. He knows the mass of each weight, but the judge only knows that the masses of the weights are consecutive integers from 1 to 6. How should the baron perform two weighings to prove to the judge the mass of each weight? Baron proposed these two weighings: 1 + 2 + 3 = 6, 1 + 6 < 3 + 5. Why are the results of these two weighings evidence? As a judge, we must make sure that no non-identical permutation of the numbers 1, 2, 3, 4, 5, 6 can give the same two results. Let's analyze. The first weighing says that the mass of one of the weights is the same as that of the other three weights together. But the mass of the three smallest weights is no less than 1 + 2 + 3 g, and the largest weight is no more than 6 g. Equality is achieved only when a weight of 6 g lies on the right bowl, and weights 1, 2, 3 g in some order on the left. Thus, the result of this weighing allows the judge to distribute all the weights into three sets {1, 2, 3}, {6} and the remainder {4,5}. Permutations are now only possible within each set, but not between sets. What happens at the second weigh-in? On the left pan of the scales there is a weight of 6 g (already determined) and one of the weights of the first set, and on the right - one weight each from the first and last sets. The left bowl is lighter. And what? Shall we go through all the remaining options? No. Let's apply the analysis based on inequalities again: on the left side there is at least 7 g, because there is the sum of the masses of weight 6 and one of weights 1–3. On the right bowl there is no more than 8 g, because on it the sum of the masses of one of the weights 4–5 and one of the weights 1–3. This means that the right bowl can be heavier than the left only if it has 8 g, and the left one has 7 g. In other words, the mass of the unknown weight on the left bowl is 1 g, and the masses of the weights on the right bowl are 3 g and 5 g (it is clear which has what mass, because they are from different sets!). This means that the masses of weights 1, 3, 5 have already been proven. But then

CIRCLE

⟦column⟧

The masses of the other two were also proven, since they remained the only ones unidentified in their sets. Problem 1. How to prove to the court in two weighings the correct masses for such a set of eight weights: 10, 20, 25, 30, 35, 201, 203, 207 g? Test 5. Nine weights, two weighings. Evaluation This time the baron has as many as 9 weights, the masses of which he knows. Is there such a set of weights that he can prove their mass to the judge in two weighings? The baron's speech in court will long be remembered by all lovers of logical reasoning. - Your Honor! You have not just given me a difficult task - no, it is not difficult. It is insoluble! Let's mentally imagine what I could do now? So I put some weights on the scales, weigh them, and we look at the result. Then we do the same with another set of weights. In other words, I assign each weight a two-digit “label” from 00 to 22, indicating in which weighing I put it on the left pan (1), on the right pan (2), or not using it (0). In order for the weighing results to prove the mass of each weight, all the marks must be different - after all, two weights with the same marks are indistinguishable. So, my weighings should be like this (I indicate the marks of the weights, not their masses!): 10 11 12? 20 21 22, 01 11 21? 02 12 22. But let's look at the possible results. If the result of weighing is two equilibria, then with a pair exchange of weights 10 with 01, 20 with 02 and 12 with 21, the first weighing will “transition” into the second, and vice versa. In other words, we will not be able to unambiguously find out which weight corresponds to which of the marks. The same exchange of weights with preservation of the results will occur in two identical disequilibria. Further, if we get two different inequalities, then we can consider the pair exchange of 01 with 20, 10 with 02 and 11 with 22 - both inequalities will remain, and we will again not be able to identify the mass. If in the first weighing there was equality, and in the second there was one of the inequalities, then an exchange of 10 with 20, 11 with 21 and 12 with 22 will give a similar effect. And, finally, if there was equilibrium only in the second weighing, then

⟦folio 40⟧

KVANT 2025/№5–6

the exchange of 01 with 02, 11 with 12 and 21 with 22 is used. Thus, for all possible outcomes we cannot be guaranteed to identify all nine coins. Problem 2. If Baron M. had scales with a pointer instead of cup scales, could Baron M. be able to prove to the court the mass of each weight in three weighings? Test 6. Forty-five weights, two weighings. “Divide and conquer” At the next meeting, the judge was discouraged: Baron M. brought a whole box of weights. The inventory of the box, certified by the court secretary, stated that there was one weight weighing 9 g, two weights weighing 8 g, three weights weighing 7 g, ..., nine weights weighing 1 g. “How many weighings do you need to prove all this?” – asked the judge. “Only two,” Baron M answered with the dignity of a nobleman. How should he act? The secret of the baron’s manipulations is very simple: k weights weighing (10 – k) g are equal in mass to (10 – k) weights weighing k g each. Therefore, if you put 9 + 8 + 7 of the lightest weights on one pan of the scales, and 1 + 2 + 3 of the heaviest ones on the other, then there will be a balance on the scales - and it will allow the baron to divide all the weights into three sets {1, 2, 3}, {4, 5, 6} and {7, 8, 9}. Similarly, if by the second weighing we weigh 9 + 6 + 3 weights of masses 1, 4 and 7 g with 7 + 4 + 1 weights of masses 3, 6 and 9 g, respectively, then equality in this weighing will allow us to determine exactly the masses of all weights within all sets (2, 5 and 8 will be determined by elimination, similar to how 2 and 4 were determined in the problem of six weights). Problem 3. Is there a set of even more weights for which Baron M. could prove to the judge the masses of all the weights in two weighings? Test 7. Three weighings, 19 weights. Trans inequality When the judge and the baron met the next time, the baron had in his hands a whole set of weights, the inventory of which certified that there were weights weighing from 1 to 19 g, one of each mass. “I’ll give you only three weighings, dear Baron!” – the judge declared, hitting the table with his gavel. The Baron silently wrote on each weight a number from 1 to 19 (which most likely

⟦column⟧

should have meant its mass), placed in front of him a piece of paper on which the numbers 12, 7 and 3 were written, bowed and began weighing:

1 + 2 + 3 + 4 + 5 + 7 + 8 + 10 + 13 = = 16 + 18 + 19,

1 + 2 + 3 + 6 + 9 + 11 + 16 = = 8 + 10 + 13 + 17,

1 + 4 + 6 + 8 + 12 + 18 = = 3 + 7 + 11 + 13 + 15. The judge and everyone else present looked at the baron with bated breath, but did not understand anything. Finally, the judge could not stand it: “What are you doing, Baron?” Until now, you at least looked like a reasonable person - you put the heaviest weights on one scale, the lightest on the other. How are you going to prove something to us? - Your Honor! Let's bring the experiment to the end. To do this,” here the baron looked at the piece of paper, “let’s multiply all the numbers in the first equality by 12, in the second by 7, and in the third by 3 and add it all together. - Having said this, the baron began to slowly write out the expression

$22 m_{1} 19 m_{2} 16 m_{3} 15 m_{4} 12 m_{5} 10 m_{6} 9 m_{7} 8 m_{8} 7 m_{9}^{5} m_{10}^{4} m_{11} 3 m_{12} 2 m_{13}^{3m} 15 5 m_{16} 7 m_{17} 9 m_{18} 12 m_{19}$.

– You, of course, cannot know the mass of the weight that I called “1”, as well as all the other masses. But you see that on the left side of the equality the coefficients decrease monotonically. According to $транснеравенству^{1}$, the smallest possible value of the left-hand side is

22  1 19  2 16  3 15  4 12  5 10  6 9  7 8  8 7  9 5  10 4  11 3  12 2  13 634.

1 More information about rearrangement inequality can be found, for example, in A.V. Arbit’s book “Inequalities and Basic Methods for Proving Them” (supplement to the journal «Kvant» No. 3, 2016) or from the book “Elements of Mathematics in Problems. Through Olympiads and clubs - to the profession" edited by A.A. Zaslavsky and others.

⟦folio 41⟧

MATHEMATICAL

However, on the right side the coefficients increase monotonically, so its largest possible value is equal to

12  19 9  18 7  17 5  16 3  15

634.

As in previous problems, equality means that all equalities $m_{i} i$ are achieved simultaneously. – Yes, I see that you are right again, dear Baron! Problem 4. How many weights could Baron M. prove if he allowed not three, but four weighings? The baron faced the next three trials in the same case, so we did not number them differently. Test $8-1.^{2}$ Eighteen coins of two masses. System of Inequalities It seemed that no tricks with weighing could surprise the judge. But... the baron presented 18 coins, about which the judge only knew that the masses of some of them were 10 g, and the rest - 11 g, and he undertook to prove this in just three weighings. - But how, Baron?! Okay, in one weighing you will be able to prove to me one heavy coin and one light one. During the next weighing, if you add two heavy ones to a light bowl, and two light coins to a bowl with a heavy coin, then the weighing result will change, which means you can prove the mass of 2 more heavy and 2 light coins. For the third weigh-in – another 4 + 4, for a total of 7 heavy and 7 light. But you don’t have 7 of them, but 9 of each type! – Nothing is impossible here, your honor! Let's just first sort the coins into piles. I will put 2 coins in the first two piles and prove that one of them contains 2 heavy coins, and the other contains 2 light coins (I will label them “2t” and “2l”). In the next two - 3 coins each (“3t” and “3l”), and in the last two – 4 each (“4t” and “4l”) and I will do the following weighings: 2t + 3l < 2l + 3t, ​​3t + 4l < 3l + 4t, 4t + 2l + 3l < 4l + 2t + 3t.

2 In the simple case of 14 coins, this problem was proposed at the VII All-Union Olympiad, and was also placed in the “Problem Book «Kvant» (M212). The author of the problem about 18 coins and the next problem about 12 + 12 coins is S. Tokarev.

CIRCLE

⟦column⟧

- Yes, Baron, I see the results of the weigh-ins. But what exactly do they prove? “You are too impatient, your honor.” I'll need just a little algebra. Let x be the difference in mass between the piles “2t” and “2l”, and y and z the differences between the piles “3t” and “3l” and “4t” and “4l”, respectively. It's not too difficult, is it? - No. Carry on! – Next, x, y, z are integers. The first weighing showed that x < y, the second - that y < z, and the third - that z < x + y. Is it clear why? - Yes. – Let's replace strict inequalities between integers with non-strict ones: x 1 d y, y 1 d z, z 1 d x y. I want to deduce from this that x = 2, y = 3, z = 4. Once this is proven, it will become clear that the mass of each pile is exactly the same as I claim - after all, the difference between the masses of a pair of coins does not exceed 1, which means that for two pairs the difference is always no more than 2, for three pairs - no more than 3, and for four - no more than 4, and equality is achieved only if in some piles there are only heavy coins, and in others only light ones. Right? - Agree. - Well, let's multiply the first inequality by 2, the second by 4, the third by 3 - and add everything up. We get 9 d x y z. This actually means that the equalities x = 2, y = 3, z = 4 are satisfied simultaneously. I have everything, your honor! Test 8-2. Two dozen coins. Another system of inequalities About the next 24 coins presented by the baron, the judge knew that the masses of 12 of them were 10 g, and the remaining 12 – 11 g. However, the restless baron again proved the masses of each coin in just three weighings! How? Let us carefully follow the baron’s reasoning from the previous decision. First, he laid out the coins in piles, and then looked at the difference in mass between the piles, proving that for each pile this difference is equal to the number of coins in it. From here, of course, everything necessary follows. Therefore, let's immediately see what will change in the values ​​of x, y, z, if the total number of coins is now equal to 24, and the inequalities

⟦folio 42⟧

KVANT 2025/№5–6

x < y, y < z, z < x + y will be proven using weighting? It is clear that in this problem x y z d 12, and Baron's goal is to prove equality in the last inequality. More precisely, the baron should show that x = 3, y = 4, z = 5, i.e. break the coins into piles of exactly the same size. Unfortunately, the above system of inequalities does not have a unique solution - for example, z = 5, y = 4, z = 2 with a sum of 11 is also suitable. How could the baron act if his previous solution did not work? It turns out that the baron still acts exactly the same! After all, if the total mass of all coins is even, then the value x + y + z must also be even, and therefore cannot be equal to 11. For example, you can act in the spirit of the previous replacement of strict inequalities with non-strict ones: x 1 d y, y 1 d z, z 2 d x y. In the last inequality, 2 appeared instead of 1, because in it all the coins with an even total mass of 12 11 10 are laid out on the scales, and if one bowl outweighs, then the difference between the bowls is at least 2. Well, now if we multiply the first by 2, the second by 4, and the third by 3, then after summation we get x y z t 12, which is what was required. Test 8-3. Two times thirty coins, 4 weighings How many coins could the baron be able to present (with proof) if he were allowed to do four weighings instead of three? It is clear, for example, that from the previous solutions the method for 20 + 20 coins immediately follows: with the fourth weighing, the baron puts 9 already identified as light and 11 unknown on one scale, and on the other - 9 identified heavy and 11 unknown. If the first bowl turns out to be heavier, then the 11 unknown coins on it should be heavy, and the 11 unknown coins from the other bowl should be light, because there are only 20 unknown heavy coins - 9 = 11, and if they were decomposed into different bowls, then the scales would be in balance. Is it possible to do more? Yes, quite. We will show a method for 30 + 30 coins, for which they need to be divided into piles 3 + 3, 7 + 7, 9 + 9 and 11 + 11. Each pair of piles with the same number is laid out on different scales, and if the differences in their masses

⟦column⟧

are equal to x, y, z, t, then weightings are carried out demonstrating the fulfillment of the system of inequalities z < x + y, x + y < t, t < x + z, x + t < y + z. Similar to the reasoning from the previous problems, strict inequalities here can be replaced by non-strict ones, and in the last inequality the minimum possible difference of parts will be equal to 2: x y z t 1, t x z t 1, x z t t 1, y z x t t 2. If we now multiply the first by 8, the second by 10, the third by 6, the fourth by 3 and add everything up, we get the inequality x y z t t 30, which proves everything necessary. Comment. The sequence of values ​​(10 + 10 and 30 + 30) found by the baron in trials 8-1 and 8-3, of course, does not end with four weighings. It is known (proved by computer search) that it continues: 114 + 114 – for five weighings and 454 + 454 – for six (https: oeis.org A280432). This sequence is closely related to such an algebraic construction as Hadamard matrices. As we have seen in the examples, weighing problems involving an expert are much less combinatorial (in spirit and content) and much more algebraic than classical problems about finding counterfeit coins. But they contain many more undisclosed secrets - for example, for almost no complex problems from the latest tests it has not yet been possible to prove without exhaustion not only the exact (upper) estimates, but also those that would be close to the exact ones.
