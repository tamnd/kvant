---
id: 1971-2-yaglom-dve-igryi-so-spichkami-afa955e6
issue: kvant_1971_2
year: 1971
number: "2"
title: Two games with matches
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 6
page_last: 12
page_labels: 4, 5, 7, 8, 10
tag: 2QO1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6818ce43035a63dc4d99744ed502a35696d62fd723cf1f4e8a4dcdf0e9b38fed
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/03_yaglom-dve-igryi-so-spichkami-afa955e6.md
source_content_sha256: b7d2282426d11c961766ab991a21e091531a244c95be157ae7125f92726fb8cd
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

TWO GAMES WITH MATCHES

I. M. Yaglom

In this article we tell you about games "him"
and "Izyanshizians". Both “nim” and “izianshiz” are Chinese folk games; “Izyanshiztsy” translated means “selecting stones” (of course, replacing stones with matches in games does not change anything in its essence). Subsequently, these games penetrated into Europe; At one time the game "nim" was popular in Western Europe.

⟦folio 5⟧

Here are the rules of this game.

Game "him"
There are three piles of matches on the table. Two tserayatsy take turns taking matches from these piles, and at one time the tserayatsy can take any number of matches from one (necessarily only from one!) pile. We will endure and quote whoever takes the last back.

Game "Izyanshiztsy"
There are two piles of matches on the table. Two tserayatsy take turns taking matches from these piles, and at one time the tserayatsy can take any number of matches from one pile, or an equal number (but any number!) of matches from both piles. We will endure and quote whoever takes the last back.

The task is to determine at what initial positions (that is, the number of matches in each of the piles) the beginner can win, and at which not, and indicate the method of correct (win-win) winning.

It is very convenient for practical players to play it or izyanshiztsy at the blackboard - without any matches, but with chalk and a tripod in hand. On the board you can draw, say, three rows of fields ending at the right edge of the board, and three checkers - one in each row of fields (Fig. 1). Each player on his turn destroys one of the checkers and “replays” it any number of fields to the right (here we are talking about playing with him); The winner is the one who makes the last move. You can play Izyanshizi in the same way - only now the game board contains two rows

Fig. 1.

Fig. 2.

⟦folio 7⟧

Unfortunately, here too there is no specific law for compiling this table.

Is it possible to write Tables I and II differently?

We were unable to understand how Tables I and II were compiled, formed in the first case by the crown, and in the second by two lines of numbers. Let us now think about the possible reasons for the failure that befell us.

We have already said that tables I and II are numerical tables; they are formed by a series of numbers. Naturally, we wrote down the numbers appearing in these tables in the usual way, using the generally accepted decimal number system; so, for example, the numbers 24 and 39 that make up the last column of Table II will read: “2 tens and 4 units” and “3 tens and 9 units.” However, the decimal number system itself, the origin of which is associated with the random circumstance that a person has 10 fingers on his hands, is in no way connected with the games we are considering; Therefore, it seems reductive to attempt to write our tables differently.

The further content of this article is related to the article “Number Systems” («Kvant» No. 6). We will need the following from this article.

There are many systems for writing positive numbers using a small number of symbols (digits). Positional number systems (more precisely, positional systems for writing numbers) are constructed as follows. A certain basis, or system of key numbers, is specified, which represents an infinitely possible sequence of integers:

$$1 = q_0 < q_1 < q_2 < q_3 \dots$$

After this, each number $N$ is represented as a sum of numbers of our basis, taken with certain integer coefficients:

$$N = a_m q_m + a_{m-1} q_{m-1} + \dots + a_2 q_2 + a_1 q_1 + a_0 q_0;$$

this expression is written like this:

$$N = a_m a_{m-1} \dots a_2 a_1 a_0,$$

where $a_m, a_{m-1}, \dots$ are the “digits” of the number $N$.

For example, if the base number system is:

$$1, 2, 3, 5, 7, 11, 13, 17, 19, 23, \dots$$

then the number 27 is written as follows:

$$27 = 1 \cdot 23 + 0 \cdot 19 + 0 \cdot 17 + 0 \cdot 13 + 0 \cdot 11 + 0 \cdot 7 + 0 \cdot 5 + 1 \cdot 3 + 0 \cdot 2 + 1 \cdot 1 = \text{«1000000101»}.$$

In this case, the $k$th digit $a_k$ in the notation of any number $N$ in the number system with the basis (*) will always be less than the relative $q_k + 1/q_k$.

If the basis of the number system has the form:

$$1 = q^0, q = q^1, q^2, q^3, q^4, \dots,$$

where $q$ is some integer, then the number system is called a “q-digit”, in which all numbers are represented by sums of the power of the number $q$ and all digits in the notation of the number $N$ are less than $q$ (less than 10 in the case of the generally accepted decimal number system).

⟦folio 8⟧

The simplest of all systems for writing whole numbers is the double number system, in which all numbers are represented by sums of powers of 2. If we use this number system, then our tables I and II will take a completely different form (numbers in the double number system will be written in red numbers):

**Table Ia**

| №№ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| a | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 10 | 0 | 11 | 10 | 1 | 0 | 0 | 1 |
| b | 1 | 10 | 10 | 11 | 100 | 100 | 101 | 100 | 110 | 100 | 101 | 110 | 111 | 1000 | 1000 |
| c | 1 | 10 | 11 | 11 | 100 | 101 | 101 | 110 | 110 | 111 | 111 | 111 | 111 | 1000 | 1001 |

**Table IIa**

| №№ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| a | 1 | 11 | 100 | 110 | 1000 | 1001 | 1011 | 1011 |
| b | 10 | 101 | 111 | 1010 | 1101 | 1111 | 1111 | 1010 |

| №№ | 110 | 1000 | 10001 | 10011 | 10101 | 1101 | 1111 | 10101 | 1010 | 1010 | 1010 | 1010 | 1010 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1110 | 10000 | 10001 | 10011 | 10101 | 1101 | 1111 | 1011 | 1011 | 1011 | 1011 | 1011 | 1011 | 1011 |

**A careful study of Table Ia allows us to see in it a complete definition of the pattern: yes, of course, the disjunctive positions (a, b, c) in cerem “nim” are .me positions, meaning the sum of the digits as before the digit in the double notation of the numbers a, b, c cemena (that is, equal to 0 or 2)! However, table IIa turns out to be more insidious: it is no better than table II, and no definite pattern in the composition of losing pairs (a, b) can be discerned from it.

But why should the double number system be the key to finding a win-win system for playing Qianshi? True, we saw that this system seems to help in developing the theory of the game nim: but the Qianshizians are a completely different game, and the key that opens one door does not at all have to fit another. Is it possible to rewrite Table II in a different way: perhaps a different system of recording the image

Does this system of numbers shed more light on its structure?

A careful study of Table II allows us to notice that Fibonacci numbers often appear in it and see, for example, the 1st, 2nd, 5th and 13th columns of the table *). And this, in turn, may lead us to think about the advisability of trying to write Table II in the “Fibonacci number system”, in which all numbers are represented by sums of numbers in the Fibonacci sequence (we will write numbers in this number system in blue numbers). For example, the number 100 in Fibonacci

*) Fibonacci numbers are a sequence of numbers starting with 1 and 2 and then building according to the following law: which number of the Fibonacci sequence is equal to the sum of the two previous ones. Its first terms are: 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, ... A good brochure by N. N. Vorobyov “Fibonacci Numbers” (M., “Hayka”, 3rd ed., 1969) is dedicated to Fibonacci numbers.

⟦folio 10⟧

to the above conditions a) and 6)) in ceremonies, “it” is.me and only not the positions (a, b, c), for which the sums of all digits corresponding to one digit in the recording of numbers a, b, c in the double number system, for all digits of the cemen.

Theorem II. Procedural in ceremonies "izanyitsy" are.me and not positions (a, b), for which a, being written in the Fibonacci number system, ends with a whole number of zeros, and the number b is obtained from the number a and we add one more zero at the end.

Then ee. From Theorems I and II it follows that both games - "nim" and "izanyitsy" - are in a certain sense beneficial for the beginner: there are quite a few losers for the beginner by position (see Tables I and II) in them, that is, they are much less common than all other (winning for the beginner) positions.

The proofs of these theorems form the content of the exercises below. The answers to them are given on page 60 (however, try to find the solutions yourself). We advise you to first deal with exercises 1-4, since exercises 5-7 are much more difficult.

Exercises

1. Prove that if the position (a, b, c) in the game “him” is not a losing one, that is, does not satisfy the conditions specified in the formulation of Theorem I, then the player can make it a losing one with his own move.

2. Prove that if the position (a, b, c) in the game “nim” is not a losing one, that is, does not satisfy the conditions specified in the formulation of Theorem I, then the player can make it a losing one with a move.

3. Indicate the correct game in the game "nim" if the number of piles of matches is any predetermined number number n ≥ 2 (we leave the rest of the correct game the same). What is the evidence for a win-win game in the case of n = 2?

4. Describe the losing positions (a, b, c) in the game "nim", writing the numbers a, b, c not in the double, but in the quaternary number system (that is, representing, say, the number a in the form a = aₙaₙ₋₁...a₂a₁a₀ = aₙ4ⁿ + aₙ₋₁4ⁿ⁻¹ + ... + a₂4² + a₁4 + a₀; here 0 ≤ aᵢ ≤ 3 for all i = n, n − 1,..., 2, 1, 0 *))

5. Prove that for any positive integer p, there is one and only one losing position (a, b) in the game of odds (that is, a position that satisfies the conditions of Theorem II) such that b − a = p. Check this for the first 15 losing positions listed in Table II.

6. Prove that if position (b, a) in the game “Izyanytsy” does not satisfy the conditions of Theorem II, then the player with his own move can either immediately win or lead the position to a losing one.

7. Prove that if position (a, b) in the game “Izyanytsy” is losing, then after any move of the player it ceases to be so.

8. Indicate the correct game in the “Izyanytsy” ceremony if the number of piles is odd (the player with each of his moves has the right to take any number of matches from each one pile, or equally - and also any number! - from all piles).

Problem. Indicate the correct game in the “Izyanytsy” ceremony if the number of piles is four.

I would like to warn the reader that the author does not know the solution to the problem posed.

*) The line above the number indicates that this is a number written in digits aₙaₙ₋₁...a₂a₁a₀, and not a product of numbers.
