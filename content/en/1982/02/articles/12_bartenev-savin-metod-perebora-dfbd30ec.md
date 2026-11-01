---
id: 1982-2-bartenev-savin-metod-perebora-dfbd30ec
issue: kvant_1982_2
year: 1982
number: "2"
title: Brute force method
authors:
  - Бартенев Ф. А.
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 38
page_last: 40
page_labels: 36-38
tag: UJ2R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 33a700527a486bfdedd6287958b0a9fce7cc637b3aaaafbfa3ae57363df8ed2c
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/12_bartenev-savin-metod-perebora-dfbd30ec.md
source_content_sha256: 90c0eee8e4912cc70e5db0754a9d87e47a7d4b2d645a3aa94c5fb21f99a55945
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

F. Bartenev, A. Savin

Brute force method

They say that one day Sherlock Holmes' nephew Jack approached his famous uncle with a request for help in solving the following problem*): They bought several identical books and identical albums. They paid 10 rubles for the books. 56 kopecks How many books did you buy if the price of one book is more than 1 ruble higher than the price of an album, and you bought 6 more books than albums?

Having read the conditions, the famous detective walked from the table to the window, then returned to the table, stood near it, stood at the ceiling, and finally said: “8 books were bought.”

“How did you install this?” - Jack exclaimed in one voice

*) In this formulation, the problem was actually given at the application exams in mathematics at the Faculty of Physics of Moscow State University (1968).

and Mr. Watson, who was present.

“Oh, it was quite simple! - Sherlock Holmes answered, sitting down in a chair. — Looking at the words “they bought 6 more books than albums,” I immediately realized that they bought at least 7 books. From the fact that “the price of one book is more than 1 ruble higher than the price of an album,” I concluded that each book costs more than 1 ruble, and since 10 rubles were paid for them. 56 kopecks, no more than 10 books were bought. Thus, all numbers greater than 10, and all numbers less than 7, were beyond suspicion. Having checked each of the numbers 7, 8, 9, 10, I found that the number I was looking for could only be 8: the rest do not divide 1056.”

The brute force method that Sherlock Holmes used here is apparently the oldest method of solving problems. For a long time it was classified as a “second-class” method; “overkill” solutions were considered ugly. However, in recent years, the brute force method has been used more and more often in problems where the desired value takes only integer values.

⟦folio 37⟧

The search is carried out by the computer

There are many serious problems that mathematicians cannot solve otherwise than using the brute-force method. True, in this case the search will be carried out by an electronic computer, and the mathematician will only instruct it how this search should be done. The famous American mathematician S. Golomb writes about this*): “Unlike a human, a machine, when solving problems, will perform monotonous calculations, which seem so boring to us, with unimaginable speed. But at the same time, she will not notice a way to calculate or improve the solution if this method is not taken into account in advance by the programmer who draws up detailed instructions for the operation of the computer.”

Nevertheless, in recent years, the increase in speed and memory capacity of computers, their greater availability and low cost make it possible to increasingly use them to solve search problems. Thus, the famous “four-color problem” (Can any geographical map be painted with four colors so that countries of the same color do not have common border areas?) was solved - by a very cunning search - only with the help of a computer. Recently, one of the most famous problems about polyominoes from the book by S. Golomb was also solved by brute force using a computer.

Tourist packing backpack

Among the problems solved by the brute-force method is the so-called “backpack packing problem”: Place objects from a given set into a backpack so that their total mass is the greatest (and the total volume does not exceed the volume of the backpack).

In this formulation, the problem looks like a toy, but replace “riokzak” with “rebound in the triome of a transport vehicle” and you will see that this problem has significant national significance.

In Urazhda, for 5 cities the number of options is 24, for 6 cities there are 120, for seven - 720, for ten - 362880. To avoid a complete search, mathematicians came up with various tricks**. This is not done in vain - solving such a problem is necessary to find the best route for a van delivering magazines and newspapers to kiosks, a bus,

*) S. V. Golomb. “Polimino” (M., “Mir”, 1975).

The traveling salesman hits the road

Another well-known problem solved by enumerating options is the “traveling salesman problem”*): How to compress several cities, between each two of which there is a railway connection, spending as little time as possible, given the city in which the path begins and ends?

*) A traveling salesman is a traveling representative of a trading company.
*) See, for example, «Kvant», 1978, No. 6, p. 11.

⟦folio 38⟧

recruiting villagers to work, etc.

Exercise 2. figure shows a map of the area on which 5 cities are located: Ax, Ox, Ekh, Ukh and Their, and the table shows the distances between them by rail. Find the shortest route for a traveling salesman who must leave the city of Ukh, go around other cities and return to Ukh.

| | Ax | Their | Ox | Wow | Eh |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Ax | 0 | 60 | 40 | 50 | 20 |
| Their | 60 | 0 | 30 | 35 | 45 |
| Ox | 40 | 30 | 0 | 55 | 50 |
| Wow | 50 | 35 | 55 | 0 | 20 |
| Eh | 20 | 45 | 50 | 20 | 0 |

Let's reduce the search

To solve such problems, complex methods were created that reduced the search for options. They constitute a new mathematical science called “integer programming.”

Some ideas about the possibilities of reducing enumeration can be solved by the following problem:

It is known that $\sqrt[3]{****3}$ is a natural number. Find him.

The first thing that comes to mind is to sort through five-digit numbers ending in 3 and see if there are any exact cubes among them: 10003, 10013, 10023,... But when will we get to 99993, and how will we know whether a given number is a cube or not?

It’s better to cube the number and see which of them will be five-digit and ending in 3. We get $1^3=1$, $2^3=8$, $3^3=27$, $4^3=64$, $5^3=125$, $6^3=216$, $7^3=343$, $8^3=512$, $9^3=729$, $10^3=1000$.

That won't work either. Why do we need cubes of small numbers? Let's see what the smallest number $x$ is equal to, the cube of which is a five-digit number. It is not less than $\sqrt[3]{10000}=10\sqrt[3]{10}$, but $\sqrt[3]{10}$ is greater than 2, since $2^3=8$; therefore $x$ is greater than 20. Let's estimate the number from above, that is, let's see what number it cannot exceed. This number, very clearly, is equal to $\sqrt[3]{10000}=10\sqrt[3]{100}$. But $\sqrt[3]{100}$ is less than 5, since $5^3=125$. This means you need to sort through numbers from 21 to 49.

Let's see if the fact that the number under the radical ends in 3 will help us shorten the search. Let's study the cubes of the first ten natural numbers that we wrote out. Of these, only 7 ends in 3. If you now think a little, it is not difficult to say that the cube of a natural number will end in 3 if and only if it ends in 7.

Now we only have three numbers left to sort through: 27, 37 and 47. $27^3=19683$, $37^3=50653$, $47^3=103823$, but the last number is already six-digit, so only the numbers 27 and 37 remain.

Exercise 3.

30 students (from the pedagogical institute) from all fifth courses took part in the preparation of 40 problems (for schoolchildren). Any two classmates came up with the same number of problems. Any students of different courses came up with a different number of problems. How many students came up with one problem each?

4. How many zeros can the number $9^n+1$ end in?

5. The buffet sold ippiki for 5 kopecks, cupcakes for 6 kopecks, cupcakes for 7 kopecks, puff pastries for 8 kopecks, and crusts for 10 kopecks. A group of guys bought 14 different types of products with a ruble. If one representative of each purchased species is taken, then their total price will be equal to 21 kopecks. How many and what products were purchased, if it is additionally known that no more than six products were purchased and no products were purchased equally?

6. Find two positive integers whose square difference is 455.

7. Over the course of 5 years of study, the student took 31 exams. In each subsequent year he passed more exams than in the previous one. In the fifth year there were more exams in the second year than in the first year. How many exams were there in the fourth year?
