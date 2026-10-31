---
id: 1970-5-egorov-sravneniya-po-modulyu-i-arifmetika-ostatkov-20d66909
issue: kvant_1970_5
year: 1970
number: "5"
title: Modulo comparisons and remainder arithmetic
authors:
  - Егоров А. А.
rubric: osnovnye-stati
page_first: 29
page_last: 35
page_labels: 27-33
tag: 7O65
lang: en
source: kvant_digital
extraction: vision
content_sha256: ec5ac5c9d50c28b8ea2d216e134ab21b569b438f79a1eef960469eea854cbea9
prompt_sha256: draft-1
translated_from: content/ru/1970/05/articles/06_egorov-sravneniya-po-modulyu-i-arifmetika-ostatkov-20d66909.md
source_content_sha256: 7fd9df84fa37c171bcde782f0d1918e107c6aba9aaba5112acf7631434c66f28
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

1. DIVISION WITH REMAINDER

You are about to take the subway. The fare is 5 kopecks; control at the entrance is automatic: in response to the machine you need to throw in a nickel, and if you don’t have one, then exchange your money for nickels at the change desk.

Let's assume that you have a 20-kopeck coin. How many nickels can you get from the cash register? Everyone will say that 4.

Well, what if you have 19 kopecks without nickels? It is clear that you can get only 3 nickels and another 4 kopecks in change. Let's write it like this: $19 = 3 \cdot 5 + 4$. This is a record of dividing the number 19 by 5 with a remainder.

Let us now imagine that there are coins of any denomination, that is, 1 kopeck, 2 kopecks, 3 kopecks, 4 kopecks, etc., and you need to exchange a $a$-kopeck coin so as to get the maximum number of $b$-kopecks. We ask how to do this?

It is clear that if you are taught to reprimand $b$-kopeck coins:

$b, 2b, 3b$, etc.,

then eventually there is a moment when, having received several $b$-kopeck coins, you will no longer be able to get the next one; they will give you something

⟦folio 28⟧

the number of $b$-kopeck coins and some other remainder, say $r$ kopecks. In this case, $r$ will certainly be less than $b$ (it is not excluded, of course, that $r = 0$).

The result of such an exchange can be written as follows:

$$a = kb + r, \quad r < b.$$

In this formula, the numbers $a, b$ are natural, that is, positive integers, and $k$ and $r$ are non-negative integers.

On the limit of division with a remainder. Dividing the integer $a$ by the natural number $b$ means representing $a$ as

$$a = kb + r,$$

where $k, r$ are integers, $b > r \geq 0$.

In this case, the number $k$ is called the quotient, and $r$ is the remainder of the division of $a$ by $b$.

In practice, division with a remainder is performed in the usual way, that is, “division by an angle.” For example,

$$\frac{175}{14} = \frac{14}{12};$$

$$\frac{28}{7}$$

here immediately there is a remainder and a quotient: $175 = 12 \cdot 14 + 7$.

Note that in this definition we do not require that $a$ be less than $b$, and we do not even require that $a$ be positive. You can, for example, divide

a) 5 by 7: $5 = 0 \cdot 7 + 5 \quad (k = 0, r = 5)$,

b) -13 to 7: $-13 = (-2) \cdot 7 + 1 \quad (k = -2, r = 1)$,

b) -224 by 7: $-224 = (-32) \cdot 7 \quad (k = -32, r = 0)$.

In the case where the remainder is zero, that is, $a = kb$, saying that $a$ is divisible by $b$.

It is clear that if the numbers $a$ and $b$ are divisible by the number $c$, then $a+b$ and $a-b$, as well as $ka, kb$ (k - natural) are divisible by $c$.

2. COMPARISON OF INTEGERS BY MODULE

Often there are problems in which the main role is played not by the numbers themselves included in the problem statement, but by the remainders from the division of these numbers.

Example one. Psesid goes from city $A$ to city $B$ 78 hours. He leaves $A$ at 10 o'clock in the morning. What time will he leave at $B$?

Remember that there are 24 hours in a day, divide the number 78 by 24:

$$78 = 3 \cdot 24 + 6$$

This means it will take three days and 6 hours to travel from $A$ to $B$. Therefore, he will arrive at $B$ at 16:00.

Please note that exactly the same result would have been obtained if it took not 78, but 54, 30 or 126, 102 and generally $24 \cdot k + 6$ hours to travel from $A$ to $B$ for any integer $k$.

Example two. A mathematics teacher conducts tests in class using the following system, which, in his opinion, ensures the need for mutual assistance among students. He gives them a piece of paper in a row with the conditions of the problem (“variants”), alters them according to the number of students in the class, and informs them that all the options are different. Indeed, students sitting close to each other solve various problems.

In fact, the teacher prepares only 7 different options: option 8 coincides with option 1, 9 - with 2, ..., 14 - with 7, 15 - with 1, etc.

⟦folio 29⟧

---
running_head:
folio:
---

The students soon figured out the teacher’s system, and at the next test, friends Ivanov and Petrov, sitting at opposite ends of the class, agreed to solve the same problems. The strong student Ivanov showed Petrov the number of his option with gestures, and Petrov exchanged options with a student sitting close to him, accurately establishing which option number he should have in order to receive a thank you cheat sheet from Ivanov.

You are probably reporting that Petrov figured out the numbers of the options - Ivanov's and his own - by 7 and was only interested in the remainders of these divisions: he had to fill in the option with a number that gives the same remainder as the remainder of Ivanov's option. The option numbers themselves were not significant—only the remainders were important.

For example, if Ivanov received option 10 (or 3, or 17), and Petrov received 26 (or 33, or 40), then dividing 10 and 26 by 7:

$$10 = 1 \cdot 7 + 3, \quad 26 = 3 \cdot 7 + 5,$$

Petrov exchanged options with a student who had an option

$$24 = 3 \cdot 7 + 3.$$

Example three. Let's find out which digit the number $2^{999}$ ends up on. Consider successive powers of two:

$$2^1 = 2, \quad 2^2 = 4, \quad 2^3 = 8, \quad 2^4 = 16, \quad 2^5 = 32, \quad 2^6 = 64, \quad 2^7 = 128, \quad 2^8 = 256, \dots$$

It is easy to see that the last digits of these numbers are repeated after 4.

This means that the last digit of the number $2^n$ depends only on what remainder $n$ gives when divided by 4:

when $n$ is divisible by 4, that is, when $n = 4k$, all numbers of the form $2^n$ turn out to be 6,

at $n = 4k+1$ — » » 2,

at $n = 4k+2$ — » » 4,

at $n = 4k+3$ — » » 8.

The remainder of 999 divided by 4 is 3, so $2^{999}$ is 8.

Since solving this example it turned out that we only need to know what remainder $n$ gives when divided by 4, the possibility of all numbers was divided into four classes consisting of numbers $n$ of the form

$$4k, 4k+1, \quad 4k+2 \quad \text{и} \quad 4k+3.$$

And in the second example (with test options), the possibility of all options was divided into 7 classes of the form

$$7k, \quad 7k+1, \quad 7k+2, \dots, \quad 7k+6.$$

In general, if we are interested in remainders when divided by some fixed number $m$, then the set of all integers (not only positive ones!) is divided into $m$ classes. Each class consists of numbers that give identical remainders when divided by $m$. These are the classes:

0) numbers $a$ of the form $a = km,$

1) » $a$ » $a = km+1,$

2) » $a$ » $a = km+2,$

... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ... ...

⟦folio 30⟧

Let us now introduce the following definition:

Defined. If the integers $a$ and $b$ it is possible that their difference is divisible by the natural number $m$, then saying that $a$ and $b$ are comparable modulo $m^*$).

Let's compare the numbers $a$ and $b$ modulo $m$ written like this:

$$a \equiv b \pmod{m}.$$

It is clear that two numbers are comparable modulo $m$ if and only if they give identical remainders when divided by $m$, that is, they belong to the same class.

For example,

$$27 \equiv 7 \pmod{10}, \quad 78 \equiv 6 \pmod{24}, \quad 6 \equiv 0 \pmod{3}, \quad 25 \equiv -1 \pmod{13}.$$

Clear comparability of numbers turns out to be useful in solving many problems.

Problem 1. For what natural numbers $n$ is the number $n^2+2$ divisible by 3, that is, $n^2+2 \equiv 0 \pmod{3}$?

Solution.

If $n \equiv 0 \pmod{3}$, then $n^2+2 \equiv 2 \pmod{3}$,

» $n \equiv 1 \pmod{3}$, » $n^2+2 \equiv 0 \pmod{3}$,

» $n \equiv 2 \pmod{3}$, » $n^2+2 \equiv 0 \pmod{3}$.

So, $n^2+2 \equiv 0 \pmod{3}$ if and only if $n$ is not divisible by 3.

The basic properties of comparison are reminiscent of the properties of general equalities. It is comparisons that can be obtained by adding, subtracting and multiplying:

if $a \equiv b \pmod{m}$, and $c \equiv d \pmod{m}$, then

$$a + c \equiv b + d \pmod{m}, \quad a - c \equiv b - d \pmod{m}, \quad ac \equiv bd \pmod{m}.$$

Let us prove, for example, that comparisons can be multiplied. Since $a \equiv b \pmod{m}$ and $c \equiv d \pmod{m}$, then $a-b$ and $c-d$ are divisible by $m$. From equalities

$$ac - bd = ac - ad + ad - bd = a(c-d) + d(a-b)$$

it is clear that $ac-bd$ is also divisible by $m$, that is

$$ac \equiv bd \pmod{m}.$$

As an exercise, prove that the comparison can be added and subtracted.

Let $a \equiv b \pmod{m}$. From the above properties of comparison it follows that $a^k \equiv b^k \pmod{m}$ for any natural number $k$ (that is, that both sides of the comparison can be raised to a power) and, in addition, that $ac \equiv bc \pmod{m}$, where $c$ is any integer (that is, that both sides of the comparison can be multiplied by any integer).

Problem 2. What remainder when divided by 3 gives the number $(2^2+1)(3^2+1)(4^2+1) \dots (1000^2+1)$?

Solution. This remainder will not change if each of the numbers is 2, 3, . . . , 1000 in this expression, replace it with the remainder when divided by 3. Thus, the number of interest modulo 3 is equal to $(2^2+1)^{333} (3^2+1)^{333} (1^2+1)^{333} \equiv 5^{333} \cdot 10^{333} \cdot 2^{333} \equiv 2^{333} \cdot 1^{333} \cdot 2^{333} \equiv 2^{2 \cdot 333} \equiv 4^{333} \equiv 1^{333} \equiv 1$, i.e., the required remainder is 1.

*) The word “module” (from the Latin “modulus” - measure) is used in various areas of mathematics and its applications; it is assigned to a number of particular importance; for example, counting or measuring is carried out in relation to it.

⟦folio 31⟧

Task 3. Prove that every natural number $n$ is comparable modulo 9 to its sum of digits.

Solution. Let

$$\overline{a = a_n a_{n-1} \dots a_0},$$

where $a_0, a_1, \dots, a_n$ are the digits of the number $a$. We have

$$a = a_n \cdot 10^n + a_{n-1} \cdot 10^{n-1} + \dots + a_0.$$

Let us now write down the following estimated comparisons:

$$1 \equiv 1 \pmod{9}, \quad 10 \equiv 1 \pmod{9}, \quad \dots, \quad 10^n \equiv 1 \pmod{9}.$$

Multiplying these comparisons by $a_0, a_1, \dots, a_n$ respectively and adding, we get

$$a_0 + 10 \cdot a_1 + \dots + 10^n a_n = a \equiv (a_0 + a_1 + \dots + a_n) \pmod{9}.$$

From here, by the way, we immediately get the well-known sign of divisibility of numbers by 9 (and 3).

3. ARITHMETICS OF REMAINS ACCORDING TO THIS MODULE

Let a natural number $m$ (modulo) be given. Considering all possible integers, we will be interested only in their remainders when dividing them by $m$. Thus, we will not distinguish numbers comparable modulo $m$ from each other. Under this condition, we have a remainder of $m$ of “different” objects - remainders from division by $m$:

$$0, 1, 2, 3, \dots, m-1,$$

and for them we can define new rules for “addition” and “multiplication”: namely, if $r_1$ and $r_2$ are two remainders, then “sum” $r_1 + r_2$ we will call the remainder that gives the number $r_1 + r_2$ when divided by $m$, and “product” $r_1 \cdot r_2$ is the remainder when dividing $r_1 \cdot r_2$ to $m$. For example, for $m = 10$ the remainder when divided by 10 is the last digit of its decimal notation. Therefore, in arithmetics of remainders modulo 10 will be true, for example, also the equalities

$$7 + 3 = 0, \quad 1 + 2 = 3, \quad 7 + 5 = 2, \quad 7 \cdot 5 = 5, \quad 7 \cdot 6 = 2, \quad 2 \cdot 5 = 0.$$

In the .ariphmetic of modulo 2 remainders there are only two remainders: 0 and 1, so this .ariphmetic is quite simple:

$$0 + 0 = 0, \quad 1 + 0 = 1, \quad 1 + 1 = 0,$$

$$0 \cdot 0 = 0, \quad 1 \cdot 0 = 0, \quad 1 \cdot 1 = 1.$$

For $m = 6$ we get

$$5 + 3 = 2, \quad 4 + 2 = 0, \quad 3 + 3 = 0, \quad 3 \cdot 2 = 0, \quad 3 \cdot 4 = 0$$, etc.

Thus, whichever modulo $m$ corresponds to its own ariphmetic. For the sake of brevity, we will call it $m$-ariphmetic*).

⟦folio 32⟧

As an example, we give multiplication and addition tables in 7-arithmetic.

Multiplication table

| × | 1 | 2 | 3 | 4 | 5 | 6 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 1 | 2 | 3 | 4 | 5 | 6 |
| 2 | 2 | 4 | 6 | 1 | 3 | 5 |
| 3 | 3 | 6 | 2 | 5 | 1 | 4 |
| 4 | 4 | 1 | 5 | 2 | 6 | 3 |
| 5 | 5 | 3 | 1 | 6 | 4 | 2 |
| 6 | 6 | 5 | 4 | 3 | 2 | 1 |

Addition table

| + | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
| 1 | 1 | 2 | 3 | 4 | 5 | 6 | 0 |
| 2 | 2 | 3 | 4 | 5 | 6 | 0 | 1 |
| 3 | 3 | 4 | 5 | 6 | 0 | 1 | 2 |
| 4 | 4 | 5 | 6 | 0 | 1 | 2 | 3 |
| 5 | 5 | 6 | 0 | 1 | 2 | 3 | 4 |
| 6 | 6 | 0 | 1 | 2 | 3 | 4 | 5 |

These tables are devices like this: at the intersection of rows and columns, they build the product (correspondence - sum) of the remainders at the beginning of these rows and columns.

From the properties of comparison and the usual rules of action on numbers it is clear that in $m$-arithmetic the given rules of ordinary arithmetic are satisfied, that is, for any remainders $a, b, c$ there will be

$$a+b = b+a \text{ — коммутиативность (переместительность) сложения},$$
$$(a+b)+c = a+(b+c) \text{ — ассоциативность (сочетательность) сложения},$$
$$ab = ba \text{ — коммутиативность умножения},$$
$$(ab)c = a(bc) \text{ — сочетательность умножения},$$
$$a(b+c) = ab+ac \text{ — дистрибутивность (распределительность) умножения относительно сложения}.$$

Thus, in our arithmetics, for example, the following formulas will be correct:

$$(a+b)^2 = a^2 + 2ab + b^2,$$
$$(a+b)(c+d) = ac + ad + bc + bd.$$

Let's consider several problems using $m$-arithmetic.

Task 4. Find the remainder when $2^{1000}$ is divided by 7.

Solution. We need to figure out what $2^{1000}$ is equal to in 7-arithmetic. It is easy to see that $2^{1000} = (2^3)^{333} \cdot 2 = 1^{333} \cdot 2 = 2$.

Task 5. Find the last digit of the number $7^{7^{1000}}$.

Solution. We have to figure out what this number is equal to in 10-arithmetic. To do this, consider the successive powers of the number 7 in 10-arithmetic:

$$7^1 = 7, 7^2 = 9, 7^3 = 3, 7^4 = 1, 7^5 = 7 \text{ и т. д.}$$

It's clear that

$$7^{4n} = 1, 7^{4n+1} = 7, 7^{4n+2} = 9, 7^{4n+3} = 3.$$

So, we need to find out the remainder when dividing the number $7^{1000}$ by 4. To do this, consider $7^{1000}$ in 4-arithmetic. Since $7^{1000} = 3^{1000}$, we now consider the sequence of remainders in 4-arithmetic:

$$3^1 = 3, 3^2 = 1, 3^3 = 3, 3^4 = 1, 3^5 = 3, \dots,$$

⟦folio 33⟧

$$3^{2n+1} = 3, \quad 3^{2n} = 1.$$

But 1000 is an even number; means $7^{1000} = 1$, that is $7^{1000} = 4n+1$. Therefore, in 10-arithmetic $7^{71000} = 7^{4n+1} = 7^{4n} \cdot 7 = 7$.

Answer: the number $7^{71000}$ ends in 7.

Problem 6. Prove that if $a^2+b^2$ is divisible by 3, then both $a$ and $b$ are divisible by 3.

Solution. Passing to remainders from division by 3, we obtain the 3-arithmetic equality $a^2+b^2 = 0$. There are three remainders in 3-arithmetic: 0, 1, 2.

We have: $1^2 = 1, 2^2 = 1$. It is easy to see that for $a \neq 0$ $a^2+b^2 \neq 0$, that is, from the equality $a^2+b^2 = 0$ it follows $a = 0$ and $b = 0$. This means that $a$ and $b$ are simultaneously divisible by 3.

TASKS *)
1. Division with remainder
1.0. Divide with the remainder -297 by 31, -1005 by 98.
2. Prove that the number of divisors of any natural number $N$ does not exceed $2\sqrt{N}$.
3. Find remainders from division of numbers ($n$ - natural): a) $n$ by $(n-1)$ and by $(n-2)$; b) $(n^2+n+1)$ on $(n+1)$ and on $(n+2)$; c) $(n^4+1)$ to $(n+3)$ (at $n \geqslant 80$).
4. Find all integers $n$ for which $\frac{n^2+1}{n-1}$ is also an integer.
5. Prove that the product of any three consecutive integers is divisible by 6.
6. Prove that if $a+b+c$ is divisible by 6, then $a^3+b^3+c^3$ is also divisible by 6 ($a, b, c$ are integers).
7*. 15 prime numbers form an arithmetic progression. Prove that its difference is greater than 30,000.

2. Comparing integers modulo
8.0. Find all natural numbers $n$ for which the number $n^3+n+1$ is divisible by 3.
9.0. Solve the comparison $6n+5 \equiv 0$ (mod 7).
10. Prove the following test for divisibility by 11:
$$a = \overline{a_n a_{n-1} \dots a_0} \equiv 0 \pmod{11}$$

then and only when
$(-1)^n a_n + (-1)^{n-1} a_{n-1} + \dots + a_n \equiv 0 \pmod{11}$.
11. Using the fact that $1000 \equiv -1$ (mod 7), as well as $1000 \equiv 1$ (mod 37), obtain divisibility criteria for 7 and 37.
12. Prove that if the numbers $A$ and 5$A$ have the same sum of digits, then $A$ is divisible by 9.
13. Prove that the equation $15x^2-7y^2=9$ has no integer solution.
14. Prove that for no integer $n$ the number $n^2+3n+5$ is divisible by 11.
15. Prove that numbers of the form $3n+2, 5n \pm 2, 7n+3, 7n-1, 7n-2$ are not perfect squares for any natural number $n$.
3. Arithmetic of remainders for a given modulus
16.0. Construct addition and multiplication tables in 4-, 6-, 8-, 11-, and 13-arithmetic.
17. Construct tables of squares and cubes in 9-arithmetic.
18. Using the table of cubes obtained in Problem 17, prove that numbers of the form $9n+5$ and $9n+4$ cannot be represented as the sum of the cubes of three numbers.
19. Prove that in $p$-arithmetic, where $p$ is a prime number, from the equality $ab=0$ with $a \neq 0$ it follows that $b=0$.
20. Prove that in $m$-arithmetic for any remainder $a$ there is a unique remainder - $a$ such that $a+(-a)=0$. Deduce from this that the equation $a+x=b$ has a solution in any $m$-arithmetic for any $a$ and $b$.
21. Prove that for composite $m$ in $m$-arithmetic there are remainders $a \neq 0$ and $b \neq 0$ as well as $ab=0$.
22. Using 31 arithmetic, prove that $1^{255}+2^{255}+\dots+30^{255}$ is divisible by 31.

*) Easy tasks are marked with a zero, and the most difficult ones are marked with an asterisk.
