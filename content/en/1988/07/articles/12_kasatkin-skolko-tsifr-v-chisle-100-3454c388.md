---
id: 1988-7-kasatkin-skolko-tsifr-v-chisle-100-3454c388
issue: kvant_1988_7
year: 1988
number: "7"
title: How many digits are there in 100!?
authors:
  - Касаткин В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 61
page_labels: 57-59
tag: CUF9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6261f3a57e17768770d94d1bf55e04a6526cf74650caae75a6d8d7ecfdec8c48
prompt_sha256: draft-1
translated_from: content/ru/1988/07/articles/12_kasatkin-skolko-tsifr-v-chisle-100-3454c388.md
source_content_sha256: 4a2023e4be37ab160af4f22e4dffde582017ad4780d6bba1041131b92e6c1241
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

How many digits are there in 100!?

V. N. KASATKIN

This seems like an easy question to answer. In fact, below is a program for calculating the factorials of the number $N$; work on such a program, the computer will calculate and display or print the number 100!. All we have to do is count the number of digits in the machine-generated number.

But attempts to apply this approach to large numbers $N$ lead to failures - the fact is that most personal computers cannot display a number containing more than 15 digits on the screen.

Here are the factorials of several numbers greater than 10, calculated on a Corvette-type computer:
$$10! = 3628800;$$
$$11! = 39916800;$$

$$12! = 479001600;$$
$$13! = 6227020800;$$
$$14! = 87178291200;$$
$$15! = 1307674368000;$$
$$16! = 20922789888000;$$
$$3.55687428096E+14 = 17!$$

The factorial number 17 no longer fit on the screen - the bit grid overflowed and the computer, together with the exact result 355687428096000, gave the value of the number 17! in a normalized form. The computer suggested that we assume that
$$17! = 3.55687428096E+14 = 3,55687428096 \cdot 10^{14}.$$

Does this mean that we, in principle, cannot obtain the factorIAL of a large number on a computer, for example 100!. The answer is simple: no, it doesn’t. We can use a computer to obtain a complete record of the number 100! without losing a single digit.

This is achieved by using programmer ingenuity. The problem we are going to solve is

⟦folio 58⟧

Fig. 1.

quite remarkable for programming. We will talk about how a person uses a computer: does he act according to a template, or, having delved into the features of the machine, makes it work in an unusual, non-standard way.

Before we talk about an almost natural program for finding all the digits of the number 100!, for example, about several tools of the BASIC language that are necessary in the future.

The program will use the “integer part of the argument value” function. In BASIC this function is denoted INT(X) - for any real X the value of the INT(X) function is equal to the integer value of X not exceeding it, for example:

$$\text{INT}(2.5) = 2, \text{INT}(0.002) = 0,$$
$$\text{INT}(-6.3) = -7.$$

Conditions: All digits of the resulting factorial numbers are considered to be the values ​​of the variables $a_i$, where $i=1, 2, \ldots$. Before the calculation of $N!$ begins, each variable $a_i$ is zero; Let's start the calculations (Fig. 1).

During the calculation process, the values ​​of the variables $a_i$ change.

Recall that if the factoral of the number $(k-1)$ is known, then it is easy to find the factoral of the number $k$:

$$k! = k \cdot (k-1)!.$$

Let's apply this rule to obtaining 4!, if we know that 3!=6. It works like this: we multiply 6 by 4 and get 24. We make the number 4 the value of the variable $a_1$, and the number 2 - the value of the variable $a_2$. All these actions can be schematically depicted as shown in figure 2.

Let's continue our work: calculate 5!. To do this, multiply 4!=24 by 5 and make the corresponding numbers the values ​​of the variables (see figure 3).

Let's take a closer look at the process of changing the numbers $k$ and $(k-1)!$. Multiplying one multi-digit number by another comes down to multiplying and adding digits. At the same time, we can clearly distinguish between the digits of the low-order digit and the digits of the highest digits.

Let's pause the discussion of the problem as a whole and learn how to solve a small, but important for further problem: we will teach a computer to separate the tens digit and the units digit in a two-digit decimal number.

It is necessary to create a program, the work of which, on a computer, after presenting it with a two-digit number, the variable $a_1$ gives a value equal to the number of units, and the variable $a_2$ gives a value equal to the number of tens.

Let the variable $A$ have a value equal to a two-digit decimal number (for example, 73). Divide the value $A$ by 10 and take the whole part from the result - this will be the tens digit:

$$\text{LET}A(2) = \text{INT}(A/10),$$
$$\text{t. e. } a_2 = [7,3] = 7.$$

If now from the value $A$ obtains $a_2 \cdot 10$, then we get the digit of ones in the original number $A$:

$$\text{LET}A(1) = A - A(2)*10,$$
$$\text{t. e. } a_1 = 73 - 7 \cdot 10 = 3.$$

Let's get back to the problem of getting the number 5! We remember that for this we add the number 4!=24 multiplied by 5. We also remember that the number

⟦folio 59⟧

Fig. 4.

4!=24 is stored unusually: the number 4 is the value of the variable $a_1$, and the number 2 is the value of the variable $a_2$. We can figuratively say that the numbers 2 and 4 are stored in cells $a_2$ and $a_1$, respectively.

Multiplying the contents of cell $a_1$ by 5 gives the two-digit result: $4 \times 5=20$. We will consider the low-order digit (in this case zero) to be the new value of the variable $a_1$, and keep the digit 2 “in our minds” for now. After this, we should multiply the number stored in $a_2$ by 5 and add the number 2 to the resulting product, having previously taken it from our memory. Result of the action: $5!=5 \cdot 4!=5 \cdot 24=120$ (Fig. 4). After completing all the actions, the variables $a_1$, $a_2$ and $a_3$ received new values ​​$a_1\neq0$, $a_2=2$ and $a_3=1$.

Even if the number is $(k-1)$! contains not two, but three or more digits, a scheme for obtaining the digits of the number $k$! remains the same (Fig. 5).

Fig. 5.

cents $m_i$ can be multi-digit numbers.

Use the following program text:

```basic
REM ВЫЧИСЛЕНИЕ ФАКТОРИАЛА ЧИСЛА N
DIM A(100)
INPUT N
FOR I=2 TO 100
A(I)=0:NEXT I
A(1)=1:L=1
FOR K=1 TO N
R2=0:R1=0:I=1
IF R2=0 THEN IF I>L THEN 80
R=A(I)*K+R2
R2=INT(R/(10000!))
R1=R-R2*(10000!)
A(I)=R1
I=I+1
GOTO 40
L=I-1
NEXT K
FOR J=1 TO I-1
PRINT A(I-J);
NEXT J
END
```

As a result of using the program we get*:

```text
100!=93 326215 443944 152681 699238 856266 700490 715968 264381 6214
963 895217 599993 229915 608941 463976 156518 286253 697920 8272
251 185210 916864 0 0 0
```

Naturally, the number $k$ can be not only single-digit, but also two-digit. In this case, the coefficients Itak, the number has 100! there are 158 digits - the concept of a gigantic number!

*) When a machine prints out a number, it writes it in groups of 6 digits, while skipping the initial zero. So, in the above printout, the group of digits 6214 should be perceived as the group $\odot 6214$, the group 963 - as $\odot 963$, 8272 - as $\odot 8272$, 251 - as $\odot 251$ and as another $\odot$ as a group $\odot 0$
