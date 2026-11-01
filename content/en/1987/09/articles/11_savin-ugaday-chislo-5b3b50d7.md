---
id: 1987-9-savin-ugaday-chislo-5b3b50d7
issue: kvant_1987_9
year: 1987
number: "9"
title: Guess the number
authors:
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 38
page_labels: 34-36
tag: SYOC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5aaa951515f889ff22be657d343ecc90a64dbe4571fdbece4cbe15c7f2d8714b
prompt_sha256: draft-1
translated_from: content/ru/1987/09/articles/11_savin-ugaday-chislo-5b3b50d7.md
source_content_sha256: 2272daebffa6a406f2821361972699f1d515b22b42e32b73d95c31d626c8585e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

GUESS THE NUMBER

Have you played the game "Guess the Number"? Haven't you even heard? This is a very simple game. Let's say I guess a natural number, less than 100, by writing it down on paper (so that there is no possibility of cheating), and you try to guess it by asking questions that can only be answered “yes” or “no.” Then you guess a number, and I try to guess it. Whoever guesses the number of questions for me wins.

How many questions will it take you to guess my number? Don't know? You say that maybe right away, or maybe these questions will come up? I undertake to guess your number in just seven questions. How? Here's how, for example. Let you guess a number. I ask: “Is it different than 64?” - “Yes.” - “Less than 32?” - “Yes.” - “Less than 16?” - “Yes.” - “Less than 8?” - "No". - “Less than 12?” - "No". - “Less than 14?” - “Yes.” - “Less than 13?” - "No". - “The number 13 is planned.”

It's clear? I divide the set of possible numbers in half, so the remaining half is halved again, and so on, until the remaining half contains only one number. Why did I start with the number 64 and not with the number 50? More on that later; it was possible to start with the number 50. It is not difficult to check that for numbers that change 64, six questions are enough, and in seven questions you can guess any number not exceeding 128.

34

⟦folio 35⟧

Hello, I’m looking at this cheat sheet:

| blue | red | black | green |
| :--- | :--- | :--- | :--- |
| 1 | 0 | 1 | 2 |
| 2 | 0 | 4 | 8 |
| 3 | 0 | 16 | 32 |

If you answered the questions, let’s say: “Blue, green, red,” I add up three numbers 0, 12, 16, standing at the intersection of columns and rows corresponding to the named colors in the corresponding tables. Check that the number 28 is valid and has the named colors in the tables (and only it).

Now let's reveal the secret of this trick. From early childhood we were taught to write numbers in the decimal number system. For example, we deciphered the sequence of numbers 1987 as $1 \cdot 10^3 + 9 \cdot 10^2 + 8 \cdot 10^1 + 7 \cdot 10^0$. Counting is done in tens, ten units of one digit is a unit of the next digit. If the base of the number system is taken to be the number 4, and not 10, only 4 numbers will appear: 0, 1, 2 and 3. But why numbers? You can, for example, use colored circles: © - for zero, ¶ - for 1, ¶ - for 2 and 3 - for 3. The number 28 is written in the quadricular number system as $1 \cdot 4^2 + 3 \cdot 4^1 + 0 \cdot 4^0 = 130_4$ (the four from the number 130 means that it is written in the quadricular number system). And in our color notation it will be written as $\textcircled{3}$$\textcircled{3}$$\textcircled{3}$.

If you read this entry from right to left, you get “blue - green - red”. We called this combination of colors when, having conceived the number 28, we reported its colors in tables A, B, B!

Let's take another look at our tables. In table A, the colors of the numbers are moved through four in this way to determine the second digit in the quadricular record of the number, and in table B - the third digit. The same thing is said by the “cipar-galka”, with the help of which we identified the number by its colors in the tables. (We placed numbers in tables A, B, B of size $7 \times 9$ in order to confuse you a little: if you use

⟦folio 36⟧

tables $A_1, B_1, B_1$ of size $8 \times 8$, the system can be detected much faster.) Tables compiled in a similar way, but using 3 colors, will correspond to the representation of the number in the ternary number system; using 2 colors - in girlish. How is the number 100 written in the double number system? This
$$64 + 32 + 4 = 1 \cdot 2^6 + 1 \cdot 2^5 + 0 \cdot 2^4 + 0 \cdot 2^3 + 1 \cdot 2^2 + 0 \cdot 2^1 + 0 \cdot 2^0,$$
i.e. $1100100_2$. We see that numbers changing one hundred (hereinafter changing 128) are written in the double number system with no more than seven signs. Remember that I took seven questions to guess the changing number 100!
For the number 13, the following sequence of answers was obtained: yes-yes-yes-no-no-no. Let's write the number 13 in the double number system and add three zeros: 0001101$_2$. What is the relationship between the sequence of “yes-no” answers and the resulting numbers? Well, of course, it’s completely straightforward: the answer “yes” corresponds to the number 0, and the answer “no” corresponds to the number 1.

Thus, instead of my “large-size” questions, one could present seven tables with blue and red numbers. I don’t know about you, but the halving method worked better for me. By the way, it is used quite often in practice. Let's say I need to find task number 1372 in the task. I open its middleware and look at some task number on this page. If it's greater than 1372, I halve the first half of the job and look at the numbers there; and if it’s less, then I do this procedure with the second half. The number of pages that can contain this task is halved each time, and twice as quickly you find what you were looking for. This method is called “dichotomy” from the Greek “dikha” - into two parts - and “tom” - section.

The principle of dichotomy is also embedded in the Optimian system for identifying a champion: first, all sections are divided into pairs, and the strongest is determined in each pair, further victories - half of the sections - are excluded from the perfect one, and the winners are again divided into pairs, etc. Until only one pair is stopped, in the meeting of which the champion is determined. This system is perfect if the number of sections is a power of 2; then in each perfect krita all areas are occupied, but what if in some kritas the number of areas is odd? Then one of the teams moves on to the next crit without progressing with the other crits. It is curious that if a section is one greater than a power of two, then the described situation will occur in every perfect crit (for example, with 9 or 17 sections), and you need to make sure that the same team does not turn out to be “extra” in each crit and thus not reach the finals without playing a single game.

(For the end see p. 50)
