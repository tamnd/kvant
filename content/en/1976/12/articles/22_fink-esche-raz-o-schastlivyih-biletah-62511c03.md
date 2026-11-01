---
id: 1976-12-fink-esche-raz-o-schastlivyih-biletah-62511c03
issue: kvant_1976_12
year: 1976
number: "12"
title: Once again about lucky tickets
authors:
  - Финк Л. М.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 70
page_last: 72
page_labels: 68-70
tag: XMDA
lang: en
source: kvant_digital
extraction: vision
content_sha256: a6735c3f96b9e9aa5ef97ace0693c4bdb77d0a3c49b615e7e12a001477a76a84
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/22_fink-esche-raz-o-schastlivyih-biletah-62511c03.md
source_content_sha256: 8a940217e4568c7566f48dba402cb83074dbe860fcdbada4b429a4a9e8a67541
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 68⟧

L. Fink

Once again about lucky tickets

Yesterday my nephew Misha ran up to me exclaiming: “Uncle, I think I’ve made up my mind!”
- What did you decide?
— The problem of a lucky ticket. Do you remember how once on the tram you and I tried to count how many “lucky” tram tickets there were, for which the sum of the first three digits of the number was equal to the sum of the last three digits?
- Of course, I remember. This conversation of ours was even published in «Kvant» (see No. 7, 1975, pp. 67-70). So, you found the exact number of lucky tickets without using a brute force method?
- Almost.
— What do you mean “almost”? Almost exact number?
- No, the number is exact. But I still use the brute force method. True, I’m not looking at a million six-digit numbers, but a thousand times less.
- Tell me how you do it.
— I calculated how many lucky tickets have a given sum of the first and last three digits equal to a certain number, for example $k$. Let us denote the number of three values ​​of numbers with a sum of digits equal to $k$ by $N(k)$. To get a lucky ticket with the sum of the first three and last three digits equal to $k$, you can choose any of these $N(k)$ three-digit numbers for the left half of the ticket number and any other (or the same) for the right. For example, with a sum of digits $k = 1$ there are three three-digit numbers: 001, 010 and 100. Combining them, we get 9 six-digit lucky ticket numbers:

$$\begin{array}{ccc}
001001 & 001010 & 001100 \\
010001 & 010010 & 010100 \\
100001 & 100010 & 100100
\end{array}$$

In the general case, lucky tickets with a sum of digits equal to $k$ in each “half” will be $[N(k)]^2$. The smallest possible value of $k$ is 0 (for number 000), and the highest is 27 (for number 999). By summing the value of $[N(k)]^2$ by $k$ from 0 to 27, we get the number of all possible lucky tickets. Having done this, I found the answer - the number of lucky tickets $C = 55252$. That is, on average, one out of 18 tickets is lucky.

Misha was as happy as if he had torn off several lucky tickets at once.

“Congratulations on your decision,” I said. — But it’s not clear to me how you determined the values ​​of $N(k)$.

- Very simple. I wrote down a thousand three-digit numbers from 000 to 999 and calculated the sum of the digits for each. “I managed it without any computers—in just one Sunday,” Misha answered proudly.

- Well, please, it would be more useful to understand the formula or rule that allows you to find $N(k)$ without brute force.
- I tried, uncle, honest word! But nothing worked out.

- Let's try together. First, you need to change the notation: instead of $N(k)$ it will be written $N_3(k)$.

— What does this triple visa mean?

⟦folio 69⟧

That we will consider three-digit numbers.
But this is already clear!
That's not the point. We will generalize the problem and look for $N_n(k)$ - the number of $n$-digit numbers with a sum of digits equal to $k$.
Dude, I can’t solve the problem for three-digit numbers, but you want to solve it for both four-digit and five-digit numbers... After all, this is much more difficult!
Of course, it’s more difficult if you use brute force. But it’s easier if you think logically. By the way, in the history of mathematics there are many problems that were solved only after they were formulated in a general form. Try to find $N_1(k)$ first.
I'll think about it now. We need to determine how many single-digit numbers the sum of digits $k$ has. But for a single-digit number, the sum of the digits is the same as the number itself. There is nothing to decide here. There is one single-digit number with a sum of digits equal to zero - this is 0; one single-digit number with a sum of digits equal to one is 1, one number with a sum of digits equal to two is 2, etc. So $N_1(k) = 1$ if $k$ takes values ​​from 0 to 9, and for other values ​​$k - N_1(k) = 0$.
Great! Let's move on. Let us now assume that we already know the values ​​of $N_{n-1}(k)$ for all $k$. Let's try to express $N_n(k)$ through them. In other words, let's try to find the number of $n$-digit numbers with a sum of digits equal to $k$, assuming that for $(n-1)$-digit numbers the problem has already been solved.
“I see,” Misha answered. We already know the meanings of $N_1(k)$; so we only need to find a way to move from $n-1$ to $n$. Then we can sequentially determine the values ​​of $N_2(k)$, $N_3(k)$, etc. Well, let's try. Let the first digit of a $n$-digit number be the number $l$. For the sum of the digits of this number to be equal to $k$, the remaining digits must add up to $k-l$. There are $N_{n-1}(k) - l$ such $(n-1)$-digit numbers. The digit $l$ can be any single-digit integer not exceeding $k$ (i.e. $0 \leqslant l \leqslant 9$, $l \leqslant k$), and each of these digits corresponds to $N_{n-1}(k-l)$ $n$-digit numbers with a sum of digits equal to $k$, all of which are different. This means that there will be a total of such numbers
$N_n(k) = N_{n-1}(k) + N_{n-1}(k-1) + N_{n-1}(k-2) + N_{n-1}(k-3) + N_{n-1}(k-4) + N_{n-1}(k-5) + N_{n-1}(k-6) + N_{n-1}(k-7) + N_{n-1}(k-8) + N_{n-1}(k-9)$; (*) moreover, if $k < 9$, then for $l > k$ the corresponding value $N_{n-1}(k-l)$ we will consider equal to zero.
Using formula (*), you can calculate the values ​​of $N_n(k)$ for all $k$ if the values ​​of $N_{n-1}(k)$ are known. And since we already know the values ​​of $N_1(k)$, the problem is solved!
Absolutely right,” I said. Formulas similar to formula (*) are called *recurrent*. Of course, in order to calculate all the values ​​of $N_3(k)$ using the formula (*), it will take 10-15 minutes, but not the whole day. But the point is not in time, but in obtaining a regular, non-exhaustive solution. Using the resulting formula, you can calculate the number of lucky tickets not only for our trams, but also for trams with eight-digit, ten-digit and generally 2$n$-digit numbers. I remember I read in one science fiction novel that in the auto bookstores of the main planet of the $\alpha$ Centauri system, eight-digit numbers are used for tickets. Let's find out whether the inhabitants of this planet get lucky tickets more often than we do?
Misha took a piece of paper and began to draw a table. First of all, he filled the column for $n=1$ with ones for $k$ ranging from 0 to 9. The remaining cells of this column could have been filled with zeros, but he decided not to write them. Misha obtained the column for $n=2$ using the recurrent formula (*), adding the corresponding values ​​$N_1(k)$, $N_1(k-1)$, ..., $N_1(0)$

⟦folio 70⟧

Yes, $N_2(6) = N_1(6) + N_1(5) + N_1(4) + N_1(3) + N_1(2) + N_1(1) + N_1(0) = 7$. Columns for $n = 3$ and $n = 4$ were then constructed using the same formula.

Table of values ​​$N_n(k)$

| $k$ | 1 | 2 | 3 | 4 |
| :--- | :--- | :--- | :--- | :--- |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 1 | 2 | 3 | 4 |
| 2 | 1 | 3 | 6 | 10 |
| 3 | 1 | 4 | 10 | 20 |
| 4 | 1 | 5. | 15 | 35 |
| 5 | 1 | 6 | 21 | 56 |
| 6 | 1 | 7 | 28 | 84 |
| 7 | 1 | 8 | 36 | 120 |
| 8 | 1 | 9 | 45 | 165 |
| 9 | 1 | 10 | 55 | 220 |
| 10 | | 9 | 63 | 282 |
| 11 | | 8 | 69 | 348 |
| 12 | | 7 | 73 | 415 |
| 13 | | 6 | 75 | 480 |
| 14 | | 5 | 75 | 540 |
| 15 | | 4 | 73 | 592 |
| 16 | | 3 | 69 | 633 |
| 17 | | 2 | 63 | 660 |
| 18 | | 1 | 55 | 670 |
| 19 | | | 45 | 660 |
| 20 | | | 36 | 633 |
| 21 | | | 28 | 592 |
| 22 | | | 21 | 540 |
| 23 | | | 15 | 480 |
| 24 | | | 10 | 415 |
| 25 | | | 6 | 348 |
| 26 | | | 3 | 282 |
| 27 | | | 1 | 220 |
| 28 | | | | 165 |
| 29 | | | | 120 |
| 30 | | | | 84 |
| 31 | | | | 56 |
| 32 | | | | 35 |
| 33 | | | | 20 |
| 34 | | | | 10 |
| 35 | | | | 4 |
| 36 | | | | 1 |

Having done this, Misha received:
for two-digit numbers $C = 10$,
for four-digit $C = 670$,
for six-digit characters $C = 55252$,
for reminiscent $C = 4840030$.

“Thus,” Misha summed up, “on the planet of the α Centauri system, for every 100 million tickets there are a little more than 4.8 million happy ones.” On average, about one lucky ticket out of 21, and not out of 18, like ours. It is more difficult for them than for us to add their own “happiness”.

“Now,” I said, “we can consider the task solved.”

— Are there other ways to solve it? - Misha asked.

- Probably there is. Maybe readers «Kvant» will come up with them and share them with us? It is not necessary to find the exact number of lucky tickets; you can limit yourself to an estimate or an approximate formulation; these estimates provide a small relative error. Here, for example, is one simple formula expressing the number of $2n$-lucky tickets for any $n$ with a relative error of no more than 4%:

$$C \approx 10^{2n} / \sqrt{33n\pi}.$$

As $n$ increases, the relative error decreases rapidly.

- How did you get this formula, uncle?

- Now it’s difficult to explain. I used the methods of probability theory; I find that after a few years you became acquainted with this theory.

“Now,” Misha said after finishing the table, “you can calculate the number of lucky tickets with two values, four-digit, six-digit and recalling numbers.” To do this, the numbers in the $n$th column of my table need to be squared and added.
