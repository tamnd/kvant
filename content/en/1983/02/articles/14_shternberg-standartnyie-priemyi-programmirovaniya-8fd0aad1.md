---
id: 1983-2-shternberg-standartnyie-priemyi-programmirovaniya-8fd0aad1
issue: kvant_1983_2
year: 1983
number: "2"
title: Standard Programming Techniques
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 57
page_labels: 54-55
tag: CWJS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 27b8a021cabeb9cd6214a18d251a1d606db68c84379c28846c3d5a045e2fc85d
prompt_sha256: draft-1
translated_from: content/ru/1983/02/articles/14_shternberg-standartnyie-priemyi-programmirovaniya-8fd0aad1.md
source_content_sha256: 2bab37529391d5d0cf4d62e230ec6fd09fb78e986cd937559c947de89b567653
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

Traditional programming techniques

Lesson 5. How much is 2x2 on a computer, or Machine Arthmetic and how to deal with it

Knowing the answer to the question “What is 2x2?” is a modern necessity for a person who aspires to the importance of mathematics at least in the scope of the initial scale. How does a computer answer this question? The surprise is that on a computer

$$2 \times 2 = 4$$
but $2.0 \times 2.0 \neq 4.0$, more precisely $2.0 \times 2.0 \approx 4.0^*$

The fact is that integers are exact, and real numbers are approximate. Moreover, all numbers still have a limited range of change. What conclusions should a programmer draw from this?

Let us consider the solutions to the preparatory problems given in the table. The tasks apparently seemed extremely easy to you, and the solutions given are beyond doubt. Nevertheless, all decisions are wrong; more precisely, there may be incorrect results or no results at all. And this happens due to the peculiarities of machine arithmetic.

Real numbers in a computer are represented in the so-called floating point form, that is, the number a is represented in the form $a \cdot n^6$, where $1/n < |a| < 1$, n is the base of the number system in which this computer operates (as a rule, this is a binary or hexadecimal system, which, however, is completely unimportant for understanding the day of the matter). Let's assume that our computer operates in the decimal number system and has 4 digits for mantisu and 1 digit for order. Godda (see Fig. 1) in the memory cell only the numbers and the mantissa and order sign are remembered, the dot is implied before the first digit of the mantissa, and the order shows in which direction and how many digits the point actually “floats” (hence the term “floating point”). Thus, the maximum representation of a number in our computer is $0.9999 \times 10^9$, that is, about a billion.

Now consider Problem 2 and assume that $n = 1000$ and all $a_i$ have values ​​around $2 \times 10^6$. Then an attempt to obtain the sum of the array elements does not give a result, since this sum cannot be written into the computer memory. To avoid this, the formula for the arithmetic mean must be rewritten in the form

$$m = \sum_{i=1}^{n} \frac{a_i}{n}$$

and program division by $n$ of each $a_i$. Of course, this replaces the program, but our shorter program shown in the table may simply not produce the result.

Now, with the same $n = 1000$, let us assume that

$$\sum_{i=1}^{900} a_i = 9555, a_{901} = a_{902} = \dots = a_{1000} = 0.2.$$

When adding $a_{901}$ with the accumulated sum we get $0.95552 \times 10^4$, but the computer will discard the last sign “2” (bits that go beyond the boundaries of the bit grid are lost). Thus, the last 100 components will not contribute to the result and a gross error will result (equal to $0.2 \times 100 = 20.0$).

(In this case, it would be necessary to separately sum all numbers with small orders of magnitude, and then use the resulting sum as an element for further summation.)

Examples of associative and distributive laws can be given*).

Real computers work with a much larger range and greater accuracy in representing numbers, so in most cases the difference between machine and conventional arithmetic is not felt. Nevertheless, there are cases when a Fortran program, when transferred from a BESM-6 computer (which works with an accuracy of about 12 decimal places on an EC series computer (precision of about 7 decimal places), is written: the low accuracy of the EC computer led to errors due to the accumulation of errors.

As a rule, the range and accuracy of a computer is sufficient to avoid. Thus, adding numbers with sharply different orders once does not bother us: when the count is in the millions, tenths are not important; and to lose accuracy when repeatedly adding numbers of close orders, you need to do about $10^8$ additions on an EC computer and about $10^{13}$ on a BESM-6. The peculiarities of machine arithmetic begin to affect if you need accuracy close to that of a computer, or if the volume of calculations approaches critical for a given computer.

*) For admitted readers, we will inform you that $2.0 \times 2.0$ is still exactly equal to 4.0, since both 2.0 and 4.0 represent exact in memory. But if one of the components turns out to be computable, then the result may no longer be exact: $(1.0/3.0) \times 6.0 \neq 2.0$, since the intermediate result 1/3 cannot be represented accurately on computers operating in the double or decimal number system.

⟦folio 55⟧

Solving preparatory problems

Task 1 (table of values ​​$x^2$)

$$x := a;$$
while $x < = b$ do
begin writeln $(x, '**2 =', x**2);$
$$x := x + h$$
end;

Task 2 (arithmetic mean).

$$s := 0;$$
for $i := 1$ to $n$ do $s := s + a[i]$:
$$s := s/n$$;

Task 3 (popsk of a given number).

$$k := 0; i := 1;$$
while $(i < = n)$ AND $(k = 0)$ do
begin if $a[i] = x$ then $k := i;$
$$i := i + 1$$
end;

In the mentioned example with a Forteran program, an accuracy of $10^{-5}$ was needed with a computer accuracy of $10^{-7}$, and the accuracy of $10^{-3}$ of a program on an EC computer was provided.

What conclusions follow from all of the above? There is only one conclusion: the programmer must be mentally prepared to meet an arithmetic machine. What exactly should he do when he meets her? There is no general method, and you have to choose from the following options.

a) Prove that for a given algorithm the errors of the arithmetic machine do not exceed acceptable limits.

b) Prove the same under additional conditions on the original data (establish that with your data everything will be in order, although this cannot be guaranteed in the general case).

c) Develop an algorithm that compensates for errors.

e) Use calculations with increased accuracy (implemented in hardware or software), in particular, calculate the program on a different computer model with more accurate arithmetic.

In practice, options e) or e) are most often used. In some programming languages ​​(Fortran and PL/1, for example), it is possible to specify that calculations should be carried out with increased accuracy. This is implemented on the EC computer in hardware (with some slow software), and on BESM-6 - in software (with significant slow software).

It is better not to compare real numbers for equality,

since with almost a hundred percent probability we get the result “not equal”. Therefore, the operator in task 3

if $a[i] = x$ then...
should be replaced with
if abs $(a[i] - x) < eps$ then...

where eps is a constant described, for example, as eps = 0.0001 (depending on the accuracy of the computer and the accuracy you need). Then the action numbers are considered equal if they differ by no more than some ε.

In task 1, if $a = 0, b = 1, a h = 0,1$, then we have no guarantee that we will get all 11 function values: after adding $x$ with $h$ 10 times, we can get a value a little less than $b$, or a little more than $b$, and in the latter case the loop will no longer work for it. To achieve the desired result, you need to either organize a loop with the conditions while $(x < b + h/2)$, or calculate in advance the number of repetitions of the loop $n := \text{round}((b - a)h)$ and organize a loop for $i := o$ to $n$ do... However, this path may not lead to the desired result: if the value $n$ (the required number of steps) turns out to be large enough, then when the operator is executed repeatedly $x := x + h$ may accumulate error exceeding the value $h$. Then the loop organized through while will be executed one (or even several) times less or more, and the loop organized through for will be executed the required number of times, but the last value will be far from $b$. To compensate for this, we will have to organize the loop like this:

$$n := \text{round}((b - a)/h);$$
for $i := 0$ to $n$ do
begin $x := a + i*h;$
writeln $(x, '**2 =', x**2)$
end;

(Of course, this program will be slower, since each calculation of the argument value requires large operations.)

Using three simple examples, we examined the implementation of option e) - the development of a special algorithm. Note that options e) and e) require steps $a$ and $b$ to be performed as part of the process to ensure that the developed algorithm produces the desired effect. Otherwise it's simple. So, for example, it is very indo that

$$\sum_{i=1}^{k} \frac{a_i}{n} < \max\{a_i\} (k < n),$$

Posibly, when calculating using the formula $\sum \frac{a_i}{n}$, overflow does not bother us—variant $a$ has been proven. But if $n \cdot \max\{a_i\}$ is less than the maximum representable number, then you can work according to the formula $\frac{1}{n} \sum_{i=1}^{k} a_i$ - this is option e):

Given our data, it can work, although, generally speaking, the tant algorithm is dangerous. The proofs here were performed only exemplarily; it is suggested that you perform them in more detail on your own (for these simple cases this is available to you). In other cases, the required proofs $a$ or $b$ may be complex.

Control job

5.1. Given a computer operating in a $p$-ary number system with a mantissa length of $n$ digits. For task 1, developed above, determine under what correspondences between $a, b, h, p$ and $n$ it is possible to build a table using a while loop with sequential increase in $x$ by amounts $n$ in order to guarantee the correct repetition of the loop.

(Preparatory tasks for the next (last) lesson are not given!)
L. F. Sternberg
