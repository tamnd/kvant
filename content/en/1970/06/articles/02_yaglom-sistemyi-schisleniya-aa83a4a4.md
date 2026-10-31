---
id: 1970-6-yaglom-sistemyi-schisleniya-aa83a4a4
issue: kvant_1970_6
year: 1970
number: "6"
title: Number systems
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 5
page_last: 11
page_labels: 3, 4, 6, 8, 9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 848f9e6a5d7219de62588158661592416e59acad13b6c2f4014c21fa0e7143d7
prompt_sha256: draft-1
translated_from: content/ru/1970/06/articles/02_yaglom-sistemyi-schisleniya-aa83a4a4.md
source_content_sha256: e21ceb0e1f7cf8943a998a6fe738d5cd607ed2d6baebf4294158defae61d6e9e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

It would be inconvenient to do the same with all numbers encountered in practice. Further, if our needs were limited to counting within thousands, we would need to remember a thousand special characters. Naturally, for a long time people began to choose one or another series of “key” numbers and only designate them with special signs. This is, for example, the Roman numbering system, based on key numbers
1, 5, 10, 50, 100, 500 and 1000.
These numbers in the Roman numeral system represent the letters I (“i”), V (“ve”), X (“ix”), L (“el”), C (“ce”), D (“de”) and M (“em”).

Such designations were often derived from figure, once depicted corresponding numerals (I - finger, V - five with fingers placed, X - two fives), and are often abbreviations of Latin words (centum - one hundred, demimille - five hundred, mille - thousand).

Since we need the Roman numbering system only as an example, we will consider it in an older, simplified version, when the number “four” was written in the form IIII, and not in the form IV. The number 3477 in this old Roman system is written as follows: MMMSSSSCLXXVII=3·1000+4·100+50+2·10+5+2.

The cashier does the same, having banknotes in denominations of 100 rubles, 50 rubles, 25 rubles, 10 rubles, 5 rubles, 3 rubles and 1 ruble. For a cashier, numbers are key

100, 50, 25, 10, 5, 3 and 1.
Wanting to pay, say, 499 rubles, he first issues as many hundred-dollar bills as possible,

to give away too much:
499 = 4·100 + 99.

Then he issues as many 50-ruble couporas as possible in order to issue no more than the remaining 99 rubles to be paid:
499 = 4·100 + 1·50 + 49,
etc. Sometimes he may end up with a remainder less than the next key number. This will be the case in our example after issuing two ten rubles:
499 = 4·100 + 1·50 + 1·25 + 2·10 + 4.

The next key number is 5, however, since 4 < 5, there will be no need to give out five rubles. But for the painting, we can assume that 0 five rubles were given out, and include the term 0·5 in the sum. The entire procedure for issuing 499 rubles will be written like this:
499 = 4·100 + 1·50 + 1·25 + 2·10 + 0·5 + 1·3 + 1·1.

Let us now try to generalize what has been said, taking as a sequence of key numbers (“basis”) any sequence of increasing numbers:
$q_0 = 1 < q_1 < q_2 < \dots < q_n < \dots$ (1)
Let us describe how to obtain a notation for an arbitrary number $N$ in a system of numbers with basis (1).

In sequence (1) of key numbers there is the largest number $q_n$, not exceeding $N$. Delim $N$ by $q_n$ and we get the (incomplete) quotient $a_n$ and the remainder $r_{n-1}$:
$N = a_nq_n + r_{n-1}$, where $0 \leqslant r_{n-1} < q_n$.

The first remainder $r_{n-1}$ is divided by the next key number $q_{n-1}$. We put
$r_{n-1} = a_{n-1}q_{n-1} + r_{n-2}$,
where $0 \leqslant r_{n-2} < q_{n-1}$, or
$N = a_nq_n + a_{n-1}q_{n-1} + r_{n-2}$.

(Note that we do not exclude here the case when $r_{n-1} = 0$ - in this case, all subsequent quotients

⟦folio 4⟧

and the remainders will be equal to zero!) Terrier new remainder $r_{n-2}$ divided by $q_{n-2}$; we get

$$r_{n-2} = a_{n-2}q_{n-2} + r_{n-3},$$

Where

$$0 \leqslant r_{n-3} < q_{n-2},$$

or

$$N = a_nq_n + a_{n-1}q_{n-1} + a_{n-2}q_{n-2} + r_{n-3}$$

etc.

Finally, dividing the penultimate remainder $r_1$ by $q_1$, we get

$$N = a_nq_n + a_{n-1}q_{n-1} + \dots + a_2q_2 + a_1q_1 + r_0,$$

where $0 \leqslant r_0 < q_1$.

(Since $q_0 = 1$, then dividing the “last remainder” $r_0$ by it is redundant: it is clear that $r_0 = a_0q_0 = a_0$.) In practice, such multiple division is usually written together. We will show how this is done using the already discussed example of recording the amount of 499 rubles. in the “cashier system”:

$$499 \times 100 + 499 \times 50 + 499 \times 25 + 499 \times 10 + 499 \times 5 + 499 \times 1 + 499$$

(Here all partials $a_n, a_{n-1}$, etc. are typed in red numbers, and the number itself $N$ and remainders $r_{n-1}, r_{n-2}$, etc. are in blue.)

§ 2. Positional number systems

You have probably already agreed that in the case of a basis

$$q_0 = 1, \quad q_1 = 10,$$

$$q_2 = 10^2, \dots, q_n = 10^n, \dots$$

we will be dealing with the commonly used children's number system. But instead of writing, say,

$$4 \cdot 10^5 + 0 \cdot 10^4 + 3 \cdot 10^3 + 0 \cdot 10^2 + 1 \cdot 10 + 7$$

we simply write 403017.

A distracted or overly punctual cashier could prepare a record of his output, where the number of issued bills of different denominations would be recorded in separate columns. In this format, issuing 499 rubles would look like this:

| | 100 | 50 | 25 | 10 | 5 | 3 | 1 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 499 | 4 | 1 | 1 | 2 | 0 | 1 | 1 |

We can say that in the “cashier number system” the number 499 is written as

$$4112011.$$

Number systems related to those discussed in the last two examples (i.e., the decimal number system and the “cashier system”) are called positional (we will talk about the meaning of this expression below). Instead of cumbersome recording

$$N = a_nq_n + a_{n-1}q_{n-1} + \dots + a_2q_2 + a_1q_1 + a_0$$

in a positional number system with basis (1), it is convenient to use a more compact notation from $n+1$ “digits”:

«$a_na_{n-1} \dots a_2a_1a_0$».

It is assumed that the “digits” $a_k$ are obtained in the same way (algorithm) as described above.

From this description it is clear that in a given basis of each natural number $N$ is written in a unique way. Further, since the “major digit” $a_n$ is obtained as the quotient of the number $N$ divided by $q_n$, which by convention is less than $q_{n+1}$ (for otherwise we would start by dividing $N$ by $q_{n+1}$, and not by $q_n$!), then $a_n < q_{n+1}/q_n$. That's why,

⟦folio 6⟧

The existence and special designation for zero, which resembled a half-closed eye:

Here are some examples of writing numbers in the Mayan system:

$$[1 \cdot 20 + 0 = 20, \quad 19 \cdot 360 + 13 \cdot 20 + 13 = 7113, \quad 10 \cdot 360 + 7 = 3607]$$

The main line of recording numbers in the Varian number system and the Mayan system from the Roman numbering lies precisely in the “positional” principle of these systems: while among the Romans the letter I always means one, and V - five, regardless of where these letters are located, among the ancient Babylonians and among the Mayan Indians the meaning of the “number” depends on its place, or “position”. That is why such systems for recording numbers (which includes the commonly used “decimal system” created in India in the 8th-9th centuries or a little earlier) are called positional.

Exercises

1. Write down in the “complete cashier system” (where the “key” numbers are the following: 10000, 5000, 2500, 1000, 500, 300, 100, 50, 20, 15, 10, 5, 3, 2 and 1, corresponding to the values of all existing paper money and all coins expressed in kopecks, the amount of 233 rubles. 87 kopecks Record the transaction of transferring 23387 kopecks to the “cashier system” using “continuous division” (see page 4).

2. Read a number written in the Varian system

3. Read a number written in the Mayan system

(This is the largest number found in a Mayan site.)

§ 3. Number systems with a given base

This is the name for number systems with a basis

$$q_0 = d^0 = 1, \quad q_1 = d^1 = d, \quad q_2 = d^2, \quad q_3 = d^3, \quad q_4 = d^4, \dots, (2)$$

where $d$ is any integer greater than one. This number $d$ is called the basic number system.

These systems include the general tenth number system with the base $d=10$, the Varian six-decimal number system ($d=60$) and the double number system ($d=2$), which has recently been widely used in connection with the needs of computer technology. In the case of an arbitrary base $d$ one speaks of a “d-ary” number system.

In the $d$-ary number system, the notation $N = \langle a_n a_{n-1} \dots a_2 a_1 a_0 \rangle$ has the following meaning:

$$N = a_n d^n + a_{n-1} d^{n-1} + \dots + a_2 d^2 + a_1 d + a_0.$$

⟦folio 8⟧

1, different or identical.
In such a number system, the numbers are written

$$N = \lceil a_n a_{n-1} \dots a_2 a_1 a_0 \rceil$$

the first digit from the end $a_0$ can take $d_0$ values ​​0, 1, 2, ..., $d_0$ - 1. the next digit $a_1$ can take $d_1$ values ​​from 0 to $d_1$ - 1; the digit $a_2$ can take values ​​from 0 to $d_2$ - 1, etc.

Moreover, in the number system with basis (3), as well as in the $d$-ary number system (in which our system is reversed in the case of $d_0 = d_1 = d_2 = d_3 = \dots = d$), any entry makes sense

$$N = \lceil a_n a_{n-1} \dots a_2 a_1 a_0 \rceil,$$

where $a_0, a_1, a_2, \dots, a_n$ are natural numbers such that $a_0 < d_0, a_1 < d_1, a_2 < d_2$, etc. In fact, it is easy to check that when converting the number $N = a_n q_n + a_{n-1} q_{n-1} + \dots + a_2 q_2 + a_1 q_1 + a_0$ into our number system using the “continuous division” method (see p. 4 above), the following numbers are obtained:

$$a_n, a_{n-1}, a_{n-2}, \dots, a_1, a_0.$$

We will show that such a favorable situation is not a general law using the example of one very simple “number system”.

2° “Even” number system.

Taking all even numbers (and the number $q_0 = 1$) as the basis of the number system:

$$q_0 = 1, \quad q_1 = 2, \quad q_2 = 4, \quad q_3 = 6,$$

$$q_4 = 8, \quad q_5 = 10, \quad q_6 = 12,$$

Since here

$$\frac{q_1}{q_0} = q_1 = 2$$

And

$$\frac{q_{n+1}}{q_n} = \frac{2(n+1)}{2n} = \frac{n+1}{n} = 1 + \frac{1}{n} < 2$$ for all $n > 1$,

then this number system, like the double number system, knows only two “digits”: 0 and 1. The conditions are to designate the numbers written in this “even” number system in red. Then, very indo,

$$2 = 10, \quad 3 = 11, \quad 4 = 100, \quad 5 = 101, \quad 6 = 1000, \quad 7 = 1001, \quad 8 = 10000, \quad 9 = 10001$$, etc.

And in general, all numbers are depicted either as one with one or another number of zeros at the end (even numbers), or the vast majority of the sequence of zeros and ones do not express any numbers in the “even” number system, since in it one can only appear in the first place and - sometimes - in the last place.

And finally, one more example.

3° "Salesman System". A standard set of weights for cup scales in a store generally includes weights: 10 e, 20 e (2), 50 e, 100 e, 200 e (2), 500 e, 1 ke, 2 ke (2) and 5 ke.

The seller uses this set of weights like a banknote cashier, available at the cash register. Namely, when answering a product, he first of all places on the scales the heaviest of the weights that do not overhang the goods, then he places the highest of the remaining weights, etc.

So, for example, when weighing a piece of meat weighing 3 ke 460 e, he uses the weights shown at figure.

⟦folio 9⟧

Generalizing this well-known system of numbers (weights) “represented by numbers (weights) using a given system of weights”, well known to all sales employees and all business owners, we arrive at a number system with a basis
1, 2, 5, 10, 20, 50, 100, 200, 500, ...
in which 3 kcal 460 g will be written like this
11020101000.

In this number system in the record
$$N \ll a_n a_{n-1} \quad a_2 a_1 a_0$$
the last digit $a_0$ can only equal 0 or 1 (because $q_1 = 2$); the penultimate digit $a_1$ can take the values ​​0, 1 or 2 (since $2 < q_2/q_1 < 3$); the third digit from the end $a_2$ can again take only the values ​​0 and 1 (since $q_3/q_2 = 2$); the digit $a_3$ can also only take the values ​​0 and 1, but the digit $a_4$ can again take the values ​​0, 1 and 2 (because $2 < q_5/q_4 < 3$).

And in general in this number system all the numbers
$$a_1, a_4, a_7, a_{10}, \dots, a_{3k+1}$$
can take on the values ​​0, 1 and 2, and all other numbers can only have the values ​​0 and 1 (For a shop assistant, it is enough to have two two-gram weights and only one weight each for 1 kcal and 5 kcal.)
