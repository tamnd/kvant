---
id: 1988-1-boltyanskiy-programmyi-perebora-13214d25
issue: kvant_1988_1
year: 1988
number: "1"
title: Search programs
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 5
page_last: 8
page_labels: 3-6
tag: UDLQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 988a5fbca6728690a878523604acfac9744fc6b0f531ba0f28861c7f0d58f974
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/04_boltyanskiy-programmyi-perebora-13214d25.md
source_content_sha256: 3ec641f87cfad729db71685a86aa6b3311d108f91e6024747f23be6896455d44
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 3⟧

SEARCH PROGRAMS

Corresponding Member of the Academy of Pedagogical Sciences of the USSR
V. G. VOLTYANSKY

Isn't it true that a steam locomotive "runs" better than a human - at least faster? And if you need to get to another city, you will be happy to resort to his help. A person has a lot of other help. Robots carry heavy parts to the processing site, communications help transmit information, clocks answer the question “what time is it?” etc.

And there are new, relatively recently appeared assistants, equipped with human intellectual activity. These are computers. They can not only quickly make calculations, but also cope with tasks, when thinking about which a person searches through options, searches for solutions, and performs logical operations. Of course, a computer does not literally “think” in the same way as a human (after all, a steam locomotive “runs” in its own way, and does not walk like us). Although the computer obediently performs its “mental” activities in accordance with a program compiled in advance by a person, thanks to its enormous speed, it copes with many tasks much faster than a human. And not only with computational problems, but also with those that require thinking and racking your brain to solve. Let's look at an example.

Problem 1. How many two-digit numbers are there whose sum of squares of digits is divisible by 13?

Of course, to solve it, you can carry out a “dumb” search: there are not so many two-digit numbers, and if it is searched after another and checks for which of them the sum of the squares of the digits is divisible by 13, then we can find the answer. However, it is long and boring. And we use logical reasoning, which allows us to get a solution more easily and beautifully. To do this, let's create the following table:

| number | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| its square | 0 | 1 | 4 | 9 | 16 | 25 | 36 | 49 | 64 | 81 |
| remainder | 0 | 1 | 4 | 9 | 3 | 12 | 10 | 10 | 12 | 3 |

The bottom line contains the remainders from dividing the numbers in the second line by 13. You need to pick up two numbers whose sum of squares is divisible by 13, i.e., two numbers in the top line for which the sum of the corresponding numbers in the bottom line is 13. For example, you can take the numbers 1 and 5 (pick up the bottom line for 1 and 12); we obtain two two-digit numbers 15 and 51 that satisfy the required condition. You can also take the numbers 1 and 8 (under which 1 and 12 are also signed) - this gives two more required numbers (18 and 81). Another combination of numbers is 2 and 3 (raise the 4 and 9 written down), which gives two more numbers (23 and 32). Finally, you can combine one of the numbers under which the number 3 is written with the number under which the number 10 is written. In total, we get 14 required numbers:

15 and 51, 18 and 81, 23 and 32, 46 and 64, 47 and 74, 69 and 96, 79 and 97.

Although here it was necessary to think a little and tell how to find solutions, but, of course, such a solution is better than a “dumb” search.

What if we, like a computer, could perform hundreds of thousands or even millions of operations per second? Would it be advisable in this case to rack our brains to find a solution? Wouldn't the numbers from 10 to 99 be processed with such a rapid process? Apparently it passed!

Let us consider in advance 1 how enumeration problems are solved using a computer. We will present the program in a very common and commonly used programming language.

⟦folio 4⟧

learning BASIC (see computer science textbook for 10th grade, p. 71). But first we give a description of the INT function available in BASIC. Here is an example entry:

A=INT(56/13)

It means that variable A is assigned a value equal to the whole part of the fraction 56/13 (from the English word `integer` - whole). Since 56/13==4.30769..., we will have A=4.

Now we present the program *) for solving problem 1:

```basic
FOR N=10 TO 99
A=INT(N/10)
B=N-10*A
S=A*A+B*B
R=S-13*INT(S/13)
IF R=0 THEN PRINT N;
NEXT N
END
```

Comment. The lines of the program are skipped, not in a row, but after 10 numbers. This example is very convenient: if during the process of writing the program it turns out that you missed any operations needed for the solution, then they can then be written down in the form of lines with intermediate numbers.

Line 10 contains a loop operator, which is specifically designed to enumerate all natural numbers from 10 to 99 (that is, all two numbers) and for each of them carry out the activity specified in the subsequent lines. Line 70 is the end of the activity carried out with the next digit number, i.e., an order to move on to the next number.

Now let's look at intermediate lines 20-60, which describe the activity carried out with the number N. Line 20 contains the built-in INT function, which was mentioned above. Thus, the variable A is assigned a value equal to the integer part of the number N/10, i.e. A is a digit

*) The programs in this article are written in BASIC MSX.

⟦folio 5⟧

4. The square of a three-digit number is surrounded by three digits that make up the exact number. Find all such numbers.

5. Find a four-digit number that when divided by 133 leaves a remainder of 125 and when divided by 134 leaves a remainder of 111.

6. Sew three such digits on the right to 523*** so that the resulting six-digit number is divisible by 7, 8 and 9.

7. Sew three numbers on the right to ***999 so that the resulting six-digit number is divisible by 13, 17 and 19.

Let us now consider another problem, the solution of which allows us to introduce further programming techniques in the BASIC language.

Problem 8. The debtor (i.e., a whole person who has lived for more than a hundred years) replaced that if the number of his birthday (i.e., any of the numbers from 1 to 31) is added to the sum of the squares of the digits of his age, then his age will be obtained. How old should it be?

Here is a program to solve this problem:

```
FOR K=1 TO 9
FOR L=0 TO 9
FOR M=0 TO 9
N=100*K+10*L+M
S=K*K+L*L+M*M
IF N<S+1 GO TO 90
IF N<S+32 THEN PRINT N;
NEXT M
NEXT L
NEXT K
END
```

Comment. Here, instead of one, it uses three nested loops. Consider lines 10, 20, 90, 100:

```
FOR K=1 TO 9
FOR L=0 TO 9
NEXT L
NEXT K
```

Having started activities at K=1, we will immediately find ourselves in the inner loop (lines 20 and 90), and until it ends, we will not move through line 90 further, i.e., we will not move on to the next value of K. Thus, at K=1 we will loop through all the values L=0,1, ..., 9, then move on to K=2 and again loop through all the values L=0,1, ..., 9, etc. From here it is clear that that lines 10, 20, 90, 100 ensure the search of all pairs K, L (within the specified limits). Further, there is a third cycle inside M (lines 30, 80). Together, these three cycles give an enumeration of all three K, L, M (within the specified limits). Now line 40 shows that as a result of this we are iterating over all three-digit numbers from 100 to 999.

Lines 50-70 are intended to check whether the three-digit number under study is suitable as the age of the debtor. First of all, S is calculated - the sum of the squares of the digits of this three-digit number (line 50). If N<S+1, то рассматриваем трехзначное число не годится и, более того, увеличивая цифру единиц M, мы подавно будем получить непригодные числа. Поэтому в строке 60 применен оператор условия перехода: если N<S+1 то ПЕРЕЙТИ к строке 90. Если же условие N<S+1 не выполнено, т. е. N>S, then you also need to check how many units the number N is greater than S. If N exceeds S by 32 or more, then the difference N—S cannot be the birthday number. Therefore, only under the condition N<S+32 is the number N suitable as the age of the debtor (and then it should be printed).

Enter this program into the computer, and you will find out the age of the debtor: he is 109 years old.

Task 9. Find a three-digit number whose square is surrounded by three digits other than zero.

10. Substitute numbers into the notation 42*4* together with asterisks such that the resulting five-digit number is divisible by 72.

11. Find a four-digit number that is a perfect square, in which the first two digits are the same and the last two are also the same.

Note e. BASIC has a built-in SQR function that is useful for extracting square roots; in other words, the operator M=SQR(A) assigns to the variable M a value equal to the square root of the value of the variable A.

12. The store has mastic in boxes of 16 kg, 17 kg, 21 kg. How can some organization obtain 185 kg of mastic without opening the boxes?

13. The great mathematician Pierre Fermat, who worked extensively on number theory, hypothesized that all numbers of the form

⟦folio 6⟧

(n natural) are simple. When $n=1, 2, 3, 4$ is true, this statement is easy to check, but when $n=5$, checking “manually” becomes too difficult. However, another great mathematician, Leonhard Euler, with a clever artificial technique, established that just at $n=5$ Fermat’s statement is erroneous, i.e. the number (*) turns out to be composite in this case. Write a program that allows you to verify the correctness of Euler’s statement for $n=5$, that is, find the divisor of a number (*) different from this number and one.

Note. Using a general program written in BASIC, the computer performs calculations with six digits. Meanwhile, the number (*) receiving at $n=5$ has 10 significant digits. Keep this in mind when creating your program. Notation 2^16 means: raise 2 to the 16th power.

14. Find all three-digit numbers equal to the sum of the cubes of their digits.

15. In a three-digit number, the first digit on the left is crossed out; when the resulting two-digit number was multiplied by 7, the original three-digit number was obtained. Find him.

16. In a three-digit number, all of whose digits are odd, the middle digit is crossed out. It turns out that the resulting two-digit number is a divisor of the original number. Find all such three-digit numbers.

Hint: line

10 FOR A=1 TO 9 STEP 2
means A runs through numbers in increments of 2 (i.e. 1, 3, 5, ...).

17. The sum of the digits of a three-digit number is a multiple of 7. The number itself is also divisible by 7. Find all such numbers.

Note: The entry R<>0 means that R is not equal to zero.

18. A four-digit number, as well as a number written with the same digits in reverse order, are both perfect squares. Find these numbers.

19. Solve the following arithmetic solutions (instead of each letter you need to substitute a certain number, with the same letters meaning the same numbers, and different letters meaning different numbers):

a) WHO + CAT = CURRENT;
b) ABBA = AA² + BB²;
b) KIO * IO = TOKYO.

20. Find all two-digit numbers whose sum of digits does not change when multiplied by 2, 3, 4, 5, 6, 7, 8, 9.

Often, when solving problems on a computer, work variables are used, which in the program play the role of “counters”, “storage”, “custodians” of intermediate results. Let's look at this using the following examples.

Problem 21. Find the maximum value of the sum $M^2+N^2$ when M and N run through all values ​​from 1 to 100,

Comment. Here, a customized ABS function is used, designed to find the module (or, as they used to say, the absolute value) of a number; in other words, the operator H=ABS(Q) assigns the value |Q| to the variable H. Further, P, K, L are working variables (“custodians”), designed to store the obtained intermediate results for some time during the program’s operation. The variable P is intended to store the available value $M^2+N^2$: initially P=0 (line 10), and each time (under conditions imposed on M, N) a sum of squares is obtained that is greater than it was equal to, the variable P is assigned a new value equal to this sum of squares. However, temporarily the variables K, L receive (and store until the next change) those values ​​of M, N for which it is greater than the value of the sum of squares was obtained. After the entire search, the highest value of the sum of squares and those M, N at which it is greater than the available value are printed. Note that there are commas (rather than semicolons) between the letters P, K, L in line 110: with this printing method, the numbers displayed on the display are further apart (which number occupies 15 positions).

Problem 22. How many “lucky” six-figure tickets are there (i.e., those with the amount
