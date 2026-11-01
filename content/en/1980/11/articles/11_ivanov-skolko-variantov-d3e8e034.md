---
id: 1980-11-ivanov-skolko-variantov-d3e8e034
issue: kvant_1980_11
year: 1980
number: "11"
title: How many options?
authors:
  - Иванов Ю.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 36
page_last: 38
page_labels: 34-36
tag: JOKO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0332023fc15b078331aa766ec688d31d211f72fba3ac5d3f57c12fc39f5f8617
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/11_ivanov-skolko-variantov-d3e8e034.md
source_content_sha256: e7b11c06856972291653ad31aa9dc0b936bcea22f3d81b0dbf926ebd0ce41a2f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

xsem, similar to the one shown in figure 1. In this case, it is not necessary to draw a diagram - it is enough just to imagine it, especially since with a large number of options it is impossible to draw a diagram.

Let's now look at several problems.

Problem 1. How many four-digit numbers are there in whose decimal notation all the digits are different?

Solution. The construction of each four-digit number that satisfies the conditions of the problem can be divided into four steps. In the first step, the first digit of the number is selected. This choice can be made in nine ways (digit 0 cannot be the first digit of the number), so that the first line of the imaginary diagram has 9 digits. In the second step, the second digit of the number is selected. Although the choice of the second digit depends on the choice of the first digit (the second digit must be different from the first), the number of possibilities for choosing the second digit, regardless of the number chosen on the first chalet, is 9. Therefore, from each digit of the first line of the imaginary diagram, 9 arrows will come out into the second line, which, therefore, will have 9 9 digits. On the third chalet, the third number is selected; since it must be different from the number chosen in the first two steps, regardless of the decision we made in the first two steps, in the third chalet we are given a choice of possibilities. Therefore, the third line of the scheme will have 9·9·8 digits. On the fourth chalet we can choose any of the seven digits not used in the first three steps, and therefore the number of digits in the bottom line is 9 9 8 7 = 4536. Since the number of digits in the bottom line is obviously equal to the number of paths from the top line to the bottom, 4536 is the required number.

Exercise 1. How many four-digit numbers are there in whose decimal notation all the digits are different?

Problem 2. How many different natural divisors does the number 2³·3¹⁰·7¹⁵·11⁹ have?

Solution. It is clear that each divisor of such a number has the form

2ⁿ·3¹ⁿ·7ⁿ·11ⁿ, where 0≤k≤7, 0≤l≤10, 0≤m≤15, 0≤n≤9. The selection of each divisor can therefore be broken down into four steps: selection of k, selection of l, selection of m, selection of n. Since we can carry out the first step in eight ways, on the second chalet, regardless of the first two steps, there are 16 possibilities and, finally, regardless of the first three steps, we can carry out the fourth step in ten ways, calculating in the same way as in the previous problems, we will arrive at the answer 8 11 16 10 = 14080.

Similar reasoning leads to a general formula for the divisor number τ(n) of a natural number n, if the decomposition of n into prime factors is known. Namely, if n=p₁^k₁·p₂^k₂·…·p₅^k₅, where p₁, p₂, …, p₅ are distinct prime numbers, k₁, k₂, …, k₅ are natural numbers, then

τ(n)=(k₁+1)(k₂+1)…·(k₅+1).

Exercise 2. How many different natural divisors does the number 20 have!=1·2·3·…·20?

Product rule

In all the analyzed problems, counting the number of interrelated objects (Varinian numbers, four-digit numbers with non-repeating digits, the divisor of a given number) was carried out according to the same scheme: we imagined the construction of any of the listed objects as a sequence of several steps, at each of which the number of possible choices was easily found and did not depend on the decisions made in the previous steps. The product of these numbers gave the answer to the problem. These solution schemes are usually called the “product rule”:

Suppose we need to count the number of items that satisfy certain conditions. Let us assume that the construction of an arbitrary such object takes several successive steps, and at the first chalet we have a choice from a₁ possible

⟦folio 35⟧

ste; regardless of the result of the first step, we have $a_2$ different possibilities on the second chalet; Regardless of the results of the first two steps, there are $a_3$ ways to carry out the third step, etc.; finally, regardless of the decisions made in the previous steps, we have $a_n$ possibilities of carrying out the last step. Then the total number of listed items is equal to the product $a_1 \cdot a_2 \cdot \dots \cdot a_n$.

Pravanne has 3. In the automatizite number, there are three letters of the Russian alphabet (containing 33 letters) at the beginning, and then four numbers. How many different automation numbers can you create?

Pravanne has 4. There are 88 keys on the piano. How many ways can you produce 6 sounds in succession?

Let us now consider a slightly more difficult problem.

Problem 3. How many four-digit numbers are there, made up of the digits 1, 3, 4, 6, 7, each of which has different adjacent digits?

Solution. If on the first chalet we choose the first digit of such a number, on the second chalet - the second digit, etc., then on the first chalet we have 5 possibilities, on the second and third steps there are 4 possibilities each (at each of these steps we can choose any number except the one chosen on the previous chalet). However, when performing the fourth step, the number of possibilities depends on the result of the previous step: since the last digit must be even and different from the penultimate digit, then we have two possibilities on the last chalet if one of the numbers 1, 3, 7 was chosen on the third chalet, and one possibility if we chose 4 or 6 as the third digit.

It turns out that the product rule is not applicable to solving this problem? This conclusion was previously overdone. The product rule is not applicable due to the unsuccessful sequence of steps we chose to construct a four-digit number with the required properties. If we choose the fourth number at the first chalet, and then the third, second and third, then we will have 2 possibilities at the first chalet and 4 possibilities at each of the subsequent steps. According to the product rule, the required number of four-digit numbers is $2 \cdot 4^3 = 128$.

The art of solving combinator problems (as the intersection problems we are considering are called) largely lies in the ability to choose the sequence of steps leading to the construction of the objects to be intersected. As a rule, this sequence is chosen so that in the first steps it satisfies the maximum number of restrictions imposed by the conditions of the problem to zero.

Pravanne has 5. How many five-digit numbers $n$ are there that satisfy the conditions:

a) $n$ ends with two sevens;
b) $n$ starts with two identical digits;
b) all digits of the number $n$ are distinct, with the second and fourth digits being odd;
d) $n$ is divisible by 4, are its neighboring digits distinct and different from 0, 4, 8?

Pravanne has 6*. All kinds of broken lines are drawn on the coordinate plane, all of whose vertices have integer coordinates, and the links are parallel to the coordinate lines and do not pass through the same vertex twice; $L_n$ is the number of broken lines extending from the origin and having length $n$. Prove that $4 \cdot 2^n \leq L_n \leq 4 \cdot 3^n$.

Rearrangements

Let's start with this task.

Problem 4. How many ways can you write the names of 30 students in a column?

Solution. Here the sequence of steps takes: first we select a student for the first place, then a student for the second place, etc. On the first chalet we have 30 possibilities, on the second - 29 possibilities, on the third - 28 possibilities, etc., finally, on the last, thirtieth chalet, we have 1 possibility left: recording a student whose last name was not written in any of the 29 previous steps. The answer to the problem is therefore the number $30! = 30 \cdot 29 \cdot 28 \cdot \dots \cdot 3 \cdot 2 \cdot 1$.

We present this task here only because it is part of the next important task.

⟦folio 36⟧

Task 5 (number of permutations of $n$ elements). In how many ways can a given set consisting of $n$ elements be ordered?

To order a set means to arrange its elements in some order. Each such arrangement is called a permutation of the data set. Thus, the problem can be formulated as follows: how many permutations of a set of $n$ elements are there? Arguing in the same way as in the problem with a list of students (what kind of list is a permutation of the set of students), we find that the number of permutations of a $n$-element set is $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$.

Exercise 7. How many permutations of the numbers 0, 1, 2, ..., 9 are there, in which the number 0 is in third place, number 4 is in fifth place, and number 7 is in seventh place?

Exercise 8. In how many ways can 8 identical rooks be placed on a chessboard so that no two of them are adjacent to each other?

Exercise 9. How many permutations of the numbers 0, 1, 2, ..., 9 are there in which the number 6 immediately follows the number 9?

Let us now analyze two problems, the solution of which uses both a formula for the number of permutations and product rules.

Task 6. How many permutations of the numbers 0, 1, 2, ..., 9 are there in which the number 0 occupies one of the first four places, and the number 9 takes one of the last three places?

Solution. We will divide the construction of an arbitrary such permutation into three steps: choose a place for the number 0 (first step), choose a place for the number 9 (second step), place the remaining eight digits in the remaining eight places (third step). In the first step we have 4 possibilities; no matter which option we choose, we have 3 possibilities in the second step and finally, no matter how we arrange the numbers 0 and 9, we will have 8! possibilities for placing the remaining eight digits in eight places. According to the product rule, the number $4 \cdot 3 \cdot 8! = 12 \cdot 8!$ is a solution to the problem.

As you can see, in the third step we used the previously solved problem about the number of permutations of eight objects. When solving combinator problems involving enumeration of options, it is possible to effectively use the accumulated experience: any solved problem can help at one of the steps in a more complex problem.

Task 7. In how many ways can 15 boys and 15 girls be seated in 15 pairs so that there is a boy behind each pair and girls on the right?

Solution. We will divide the construction of an arbitrary seating arrangement into two steps: we will seat 15 boys in fifteen places, and then we will seat 15 girls in fifteen places. At each step, we solve the problem of rearranging the fifteenth collection of the collection so that the volumes of each collection of the collection stand in a row, although not necessarily in the order of the volumes?

Exercise 10. In how many ways can four ten-volume collections of the collection be arranged on a shelf so that the volumes of each collection are in a row, although not necessarily in the order of the volumes?

Exercise 11. How many permutations of the numbers 0, 1, 2, ..., 9 are there, in which there are three other numbers between the numbers 2 and 3?

Subset number of a finite set

The number given in the subtitle is often found in problems. Try to find it in special cases.

Let's write down all the subsets of each of the sets:

$A = \{a_1; a_2\}, B = \{a_1; a_2; a_3\},$
$C = \{a_1; a_2; a_3; a_4\}$.

Subsets of the set $A$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_1; a_2\}$.

Subsets of the set $B$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_3\}, \{a_1; a_2\},$
$\{a_1; a_3\}, \{a_2; a_3\}, \{a_1; a_2; a_3\}$.

Subsets of the set $C$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_3\}, \{a_1; a_2\}, \{a_1; a_3\},$
$\{a_1; a_4\}, \{a_2; a_3\}, \{a_2; a_4\}, \{a_3; a_4\},$
