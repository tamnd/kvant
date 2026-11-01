---
id: 1980-12-ivanov-skolko-variantov-38981037
issue: kvant_1980_12
year: 1980
number: "12"
title: How many options?
authors:
  - Иванов Ю.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 41
page_labels: 36-39
tag: 88V1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 65f80f0c1102b2cffc0bebf010ee88e88b94d0bd4ea4222642e2b9b37547814d
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/17_ivanov-skolko-variantov-38981037.md
source_content_sha256: c25268fb11eda21df7542a0ae2972c47cada38bd26e1b937a67c3abdaae90dc0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

How many options?

Here we continue the study of combinatorial problems according to the elective program for class IX, which began in the previous issue.

In all the problems analyzed in the previous article (and the exercises proposed for you to solve), only one argumentative action was required to obtain the answer - multiplication. Let us show in which cases other action arguments are used to count the number of options.

Subtraction and addition

Problem 1. How many four-digit numbers are there whose decimal notation contains the same digits?

Solution. Actions follow the same scheme as in the previous article, dividing the construction of a four-digit number into four steps: choosing the first, second, third, fourth digits. At the first step we have 9 possibilities, at the second and third steps we have 10 possibilities each. But the number of options for implementing a four-digit step depends on the result of the first three steps: if the averages of the three digits were equal, then at the fourth step we have 10 possibilities, but if the first three digits were different, then we must take one of these digits as the four-digit digit, and, therefore, we will have only three possibilities at this step.

Thus, the correct product does not apply. Rearranging the steps will not help either: we will still encounter the same difficulty. However, let us remember that at the beginning of the previous stat, we solved the problem opposite to the one being broken down - we found the number of four-digit numbers in which there are no identical digits. Subtracting this number (it is equal to 9·9·8·7=4536) from the number of all four-digit numbers (it is equal to 9·10·10·10=9000) we get that the number of four-digit numbers that satisfy the conditions of the problem is equal to 9000-4536=4464.

Exercises

1. How many six-digit numbers are there in which at least one digit is even?
2. How many permutations of the digits 0, 1, 2,..., 9 are there in which at least one of the first three digits is divisible by 3?
3. Problem 2. How many natural numbers are there, less than 10^5, whose decimal notation contains the same digits?

Solution. If you divide the construction of such a number into steps, at each of which one digit is selected, then for different numbers the number of steps will be different. At the same time, using product rules, it is not difficult to find separately the number of single-digit, two-digit, three-digit, four-digit and five-digit numbers that satisfy the conditions of the problem: 9, 9^2, 9^3, 9^4, 9^5. This means that in total there are 9+9^2+9^3+9^4+9^5=66429 natural numbers less than 10^5, with different neighboring digits.

Exercises

3. The alphabet consists of 10 letters. Let us define an integer as any sequence of letters of this alphabet in which no letter appears in the same sequence. How many integers are there, consisting of no more than four letters?
4. How many six-digit numbers are there in which even and odd digits are tolerable?
In problem 2 and exercises 3, 4 it is not possible to directly apply the correct product. In each of these tasks you can

⟦folio 37⟧

Fig. 1.
The items being read can be divided into several parts in such a way that the product rule can be applied to count the number of elements in each of these parts. By adding the resulting numbers, we find the solution to these problems.

Problem 3. How many permutations of the numbers 0, 1, 2,..., 9 are there in which the number 0 occupies one of the first six places, and the number 1 takes one of the last six places (Fig. 1)?

Solution. If we first choose a place for zero, then a place for ones, and after that we place the remaining eight digits in the remaining eight places, then in the second step the number of possibilities will depend on the decision made in the first step; namely, if in the first step we put the number 0 in one of the first four places, then we can choose the place for the ones in six ways; if the number 0 takes fifth or sixth place, then there will only be five possible places for ones. Therefore, from the very beginning, we will divide the set of all permutations that satisfy the conditions of the problem into two subsets: permutations in which the number 0 occupies one of the first four places, and permutations in which this number takes the fifth or sixth place. The number of elements in each of these subsets is easily calculated using the product rules: $4 \cdot 6 \cdot 8! = 24 \cdot 8!$ and $2 \cdot 5 \cdot 8!$. Answer: $24 \cdot 8! + 10 \cdot 8! = 34 \cdot 8!$.

Exercises

5. How many four digits 0, 1, 2,..., 9 are there that satisfy the conditions of the problem?

6. How many permutations of the numbers 0, 1, 2,..., 9 are there that satisfy the conditions of the problem?

6) between the numbers 0 and 1 there are three other numbers, and between the numbers 1 and 2 there are two other numbers?

7. How many functions f does it have that satisfy the following conditions: the domain of definition of the functions f is the set [1, 2, 3, 4, 5], each value of the functions f belongs to the set [1, 2, 3, 4], the number f(5) is divisible by f(3) without a remainder?

Division

The fourth argument action is also useful when solving combinator problems.

Problem 4. How many ways can 12 people be seated at a round table if there are 12 chairs at the table?

Solution. The number of different arrangements of 12 people in 12 places, that is, the number of permutations of these trees of people, is 12!, regardless of where these chairs are located - at the table, or against the wall, or somewhere else. Why, in this case, does the problem omit the fact that the chairs are at the round table? In task 4 - for nothing. But the round table allows us to give natural “variants” of problems.

A. If for each person it is not important what place he occupies at the table, but only who is his neighbor on the right and who is his neighbor on the right, then two arrangements should be postponed if, when moving from one of these arrangements to the other, neither the neighbor nor the neighbor changes for each of those sitting at the table.

B. If for each person the only thing that matters is who his neighbor is (and it does not matter which of these neighbors sits on the right and which on the left), then the two arrangements should be postponed if each of those sitting at the table has the same neighbors in both cases.

B. If the only thing that matters to each person is who sits on the neo group, then the two arrangements should be set aside if any two persons occupying diametrically opposite seats in one arrangement also occupy diametrically opposite seats in another arrangement.

Let's move on to option A. Let's break all 12! locations into groups, assigning to one group those and only those locations that need to be set aside. The number of received data

⟦folio 38⟧

Thus, groups are the answer to the problem. To find it, we first find out how many locations will be in one group. Let's choose an arbitrary group and consider the locations that fall into it. Each person in all these locations has a fixed neighbor on the right and a neighbor on the left. Therefore, in order to construct an arbitrary arrangement from a given group, it is enough to indicate the person who will occupy chair No. 1 (in both this version of the problem and in options B and C we will assume that the chairs are located in a circle with numbers from 1 to 12), after which the places of the remaining people are determined unambiguously. Since any of 12 people can be seated in seat No. 1, each group is made up of 12 locations. To now find the number of groups, all that remains is to divide the total number of locations by the number of locations in one group: $\frac{12!}{12} = 11!$

Now let's look at option B. And here we will break down all 12! arrangements into groups so that two arrangements fall into the same group if and only if they need to be identified. Let's select a group and count how many locations there are in it. Since each person in these arrangements has a permanent neighbor, an arbitrary arrangement from this group can be constructed in two steps: first, we select the person who will occupy chair No. 1 (12 possibilities), then we decide which of his two neighbors will take place No. 2 (2 possibilities), after which the places of the remaining ten people are determined “in one piece” unambiguously. According to the product rules, each group consists of 24 arrangements and therefore the number of groups is $\frac{12!}{24} = \frac{11!}{2}$.

And finally, in option B, as in previous options, neighbor, how many locations were in one group of this option. Let $A$ sit in all positions from this group to direct $A'$, $B$ to direct $B'$, $C$ to direct $C'$, $D$ to direct $D'$, $E$ to direct $E'$, and finally $F$ - by sending $F'$. These six pairs of people need to be seated on six pairs of chairs: (1, 7), (2, 8), (3, 9), (4, 10), (5, 11) and (6, 12) - one pair of chairs for each pair of people. The construction of an arbitrary arrangement from this group can therefore be divided into seven steps: first, arrange 6 pairs of places between six pairs of people (6! possibilities), on the second step, place $A$ and $A'$ on two separate places for them, on the third step, place $B$ and $B'$ on separate places for them, etc., on the next step - place places between $F$ and $F'$. Since at each of the last six steps we have two possibilities, due to the product rule, there will be $6! \cdot 2^6$ arrangements in this group (as in any other). The required number of groups is equal, therefore, located, therefore, located,

$$\frac{12!}{6! \cdot 2^6} = 3 \cdot 5 \cdot 7 \cdot 9 \cdot 11 = 10395.$$

Problem 5. Some of the sides [AB], [BC], [CD], [DA] and diagonal [AC] of the square ABCD require coloring in one of the given five colors, and all colors must be used. Two colorings are considered identical if one of the others can be obtained by unbraked movement. How many different coloring pages are there?

Solution. If you do not pay attention to the movements, then decide on the distribution of five colors over five segments. There are 5 such distributions, very conveniently! The problem statement breaks these 5! distributions into groups, each of which consists of all arrangements of colors, certain colors, indifferent colorings. The number of these groups is the answer to the problem. We will find, as before,

**Fig. 2.**

⟦folio 39⟧

de, the number of elements in one group. This number is obviously equal to the number of distinct variables that take the figure depicted at figure 2 into itself. Since with each such movement the diagonal $[AC]$ must transform into itself, the vertices $A$ and $C$ either remain in place or are placed in places. For vertices $B$ and $D$, therefore, there are also two possibilities left: to remain in place or to be placed in places. By combining each of the two options for moving vertices $A$ and $C$ with each of the two options for moving vertices $B$ and $D$, we get four different movements: identical ($A$ and $C$ stay in place, $B$ and $D$ stay in place), symmetry relative straight $BD$ ($A$ and $C$ were placed in places, and $B$ and $D$ remained in place), symmetry regarding the straight line $AC$ ($A$ and $C$ remained in place, $B$ and $D$ were placed in places) and the composition of these two symmetries - symmetry relative to the center of the square (in this case, both $A$ with $C$ and $B$ with $D$ are moved in places). Thus, each group consists of four elements and the answer to the problem is the number $\frac{5!}{4} = 30$.

Exercises

8. How many pairwise non-congestive figures can be constructed from a given regular $n$-gon and $n$ circles of pairwise different radii, if each side of the $n$-gon must touch at its center one and only one of the given circles?

9. For a banquet for 100 people, nine round tables have been prepared: three eight-seat, four ten-seat and two eighteen-seat. Two options for arranging people at tables are considered the same if each person in both options has the same neighbor and the same neighbor. How many different options are there for the arrangement of these tables?

Problem 6. How many six-digit numbers are there in which the numbers 1 and 2 appear twice, and the numbers 3 and 4 - no once?

Solution. A six-digit number with all its digits given is essentially a permutation of those six digits. But we know the formula for the number of permutations of different and members of x objects, while among the digits of the six-digit numbers under consideration there are identical ones. To still use the formula for the number of permutations, we will assume that we have two different ones: 1 and 1 and two different twos: 2 and 2, so the rebit is about 6! permutations of six-digit numbers is not equal to the number of such permutations, since some permutations, for example 3 1 2 1 4 2 and 3 1 2 1 4 2, lead to the same number. Two permutations will determine the same six-digit number if one of the others can be obtained, only me in places 1 and 1 or 2 and 2. We come to the signization sign: all 6! permutations are divided into groups, the number of which is the exclusive number of six-digit numbers. Since there are four permutations in each group, the answer is $\frac{6!}{4} = 30$.

Exercises

10. How many different seven-letter words can you get by rearranging the letters of the word "bell"? (In mathematics, a word is any finite sequence of letters of some alphabet.)

11. How many seven-letter words are there that are divisible by 25 and do not contain the numbers 0 and 2?

12. How many five-digit numbers are there that are divisible by 25 and do not contain the digits 0 and 2?

13. Some alphabet have 5 letters. How many six-letter words are there in this alphabet, each of which contains only two different letters, one of them five times?

14. How many permutations of the numbers 0, 1, 2,..., 9 are there, in which the numbers are 0, 1, 2; 3 in a row

a) in ascending order;
b) in no particular order?

15. How many four-digit numbers divisible by 9 can be made from the digits 0, 1, 2, 3, 4, 5, 6, provided that

a) each number contains each digit no more than once;
b) in each number each digit appears no more than once;

16. How many permutations of the digits 0, 1, 2,..., 9 are there in which the digit 0 occupies one of the first possible places, the digit 1 is one of the first possible places, and two other digits are located between the digits 0 and 1?

17. How many $(m+n)$-letter words can be made from $m$ letters $A$ and $n$ letters $B$?
