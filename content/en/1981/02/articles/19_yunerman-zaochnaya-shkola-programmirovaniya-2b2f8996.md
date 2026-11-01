---
id: 1981-2-yunerman-zaochnaya-shkola-programmirovaniya-2b2f8996
issue: kvant_1981_2
year: 1981
number: "2"
title: Correspondence School of Programming
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 58
page_labels: 54-56
tag: K0WP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 189d322ab8dab8188cdc93991d69d5c865f28ddac72d7446ada249a0f0d40dae
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/19_yunerman-zaochnaya-shkola-programmirovaniya-2b2f8996.md
source_content_sha256: c1da58971069e865e8e21aa94ee6d7e7a6fc724d3eabf4d36ca7cd511dbf42bb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

Correspondence School of Programming

Lesson 13: Approximate solution of an equation using a computer

From your school mathematics course, you are familiar with linear and quadratic equations, the roots of which can be found using formulas known to you. There are such formulas for solving equations of the third and fourth degree. But the equation promised to be of the fifth and higher powers is unsolvable in radicals: solutions to such equations (in the general case) cannot be expressed in terms of coefficients using arithmetic operations and extracting roots*). The problem becomes even more complicated if we consider non-algebraic equations**). In this case, it is impossible to find explicit expressions for the roots, with rare exceptions. But does this mean that such equations cannot be solved?

Typically, to find the roots of the equation that arise when solving most applied problems, you do not need an exact formula. Most often, for such problems it is enough to obtain an answer with a certain degree of accuracy. Therefore, it is important to be able to use one or another method of calculating the root of an equation with the required degree of accuracy. A number of methods for approximate solution of the equation are known. This lesson is devoted to the description of some of them.

Let's consider one of them using the example of solving Problem 26 of the Programming Olympiad («Kvant», 1980, No. 3): let F1(M) be a function described in Rapier with one parameter (M). We need to find and print all the integer roots of the equation F1(M) ​​= 0 lying on the segment [0; 100].

Most of the guys who took part in the Olympics coped well with this task. Indeed, the algorithm for solving it is simple. First, calculate F1(M) for M = 0. If the result is zero, then the number 0 is the root of the given equation. Now let’s find the value of F1(M) for M = 1 and again compare the resulting value with zero. Sequentially calculate the values ​​of F1(M) ​​for all integers M ∈ [0; 100], we will find those for which F1(M) = 0. These values ​​of M are the roots of the equation F1(M) = 0. Note that in this case the exact values ​​of the roots have been found.

The implementation of this algorithm is sent to any schoolchild who has the ability to find the meaning of expressions and compare them with zero. But how long will it take to solve the equation manually this way? What if the left side of the equation is quite complex and the segment on which you need to look for solutions is large? This is where computer technology comes to the aid of people. Check that the following program will print all integer solutions of the equation F1(M) = 0 from the interval [0; 100], and their number accumulates in the root counter COUNTERCOR.

PRINT('SOLUTIONS ON [0; 100]');
0->M; 0->COUNTER;
BYE M = <100::
IF F1(M) = 0 TO
PRINT(M);
COUNTER+1 -> COUNTER
ALL;
1+M -> M
ALL;
IF COUNTER=0 TO
PRINT('NO ROOTS') ALL;

What if you need to organize a search for the required solutions on various segments? In this case it is convenient

⟦folio 55⟧

describe a procedure with two parameters NATCH and KON, which organizes the search for all integer solutions of the equation F1(M)=0 on the interval [NACH; CON].

PERC SEARCH START CON;
PRINT('SOLUTIONS ON [',
START,'',CON,']');
START—>M; 0—>COUNTER;
BYE M=<CON::
IF F1(M)=0 TO PRINT(M);
COUNTER+1—>COUNTER ALL;
M+1—>M
ALL;
IF COUNTER=0 TO
PRINT('NO ROOTS') ALL;
KSC;

Task 13.1. Create a program to find all integer solutions to the equation X³—10X²—27X+36=0 on the segments [−10; 0], [1; 100].

* Task 13.2. Create a program that will find all pairs of integers of the form (X; Y), which are solutions to the equation 2Y—X²=4, if X ∈ [−50; 25], Y ∈ [100; 300].

Before moving on to describing other methods for solving the equation, we will make several substitutions. We will assume the functions under consideration are continuous, that is, having linear graphs without breaks*. In addition, we use from consideration the case when the graph of the function touches the OX axis on one side (Fig. 1). Then it is easy to see **) that

1°. If the equation F(X)=0 has N different roots on a certain interval, then the graph of the function F intersects the OX axis on this interval also N times (Fig. 2,a).

2°. If at the ends of the segment [A; B] of the function F takes values ​​of different signs, then the equation F(X)=0 has an odd number of roots on this segment (Fig. 2,a), and if it has the same sign, then it has an even number of roots (Fig. 2,b,c). Note that in the latter case there may be no roots (0 is also an even number!).

You can check whether the signs of y F(A) and F(B) are the same or different in a simple way: if the product F(A)·F(B) is different, then F(A) and F(B) have different signs, and if it is positive, they have the same signs.

Positional division method

We will look for the roots of the equation F(X)=0 on the interval [A; B] with an accuracy of 0.001. We will assume that C is the root of the equation to within 0.001 if |F(C)|<0.001. (Note that Rapier has a standard function ABS(X) that calculates the modulus of an expression X.)

Of course, |F(C)|<0.001 does not mean F(C)=0; therefore "the root of the equation is accurate to 0.01"

*) The exact definition of continuity, which is not required here, can be read in the manual “Algebra and the beginnings of analysis 9-10”, paragraph 13.
**) We will not provide a proof.

⟦folio 56⟧

Fig. 3.
is not necessarily the root.
Let's consider the case when there is exactly one root of this equation on this segment (in order to isolate such a segment, there are special methods; one of them is discussed below) and the numbers F(A) and F(B) have different values. For the definition, assume that F(A) < 0, F(B) > 0 (Fig. 3). Midpoint of the segment [A; B] has abscissa C = (A + B)/2. Let us calculate |F(C)| and compare it with 0.001. If it turns out that |F(C)| < 0.001, then C is the desired number. If |F(C)| ≥ 0.001, we proceed as follows: from the segments [A; C] , [C; B] choose the one at the ends of which the function F takes the values ​​of different symbols; Let us now denote it by [A; B]. Make sure that the desired segment can be selected using the following sentence:
IF F(C)*F(B) < 0 TO C -> A ELSE C -> B ALL;
By construction, for the new segment [A; B] fair correspondence F(A) < 0, F(B) > 0. The reader is probably already deciding what to do next. Let us again consider the middle of the segment [A; B], we calculate the value of the function F in it and compare

Fig. 5.
the modulus of this value is 0.001. If the new value of C satisfies the conditions |F(C)| < 0.001, then this is the desired number. Otherwise, again from two segments [A; C] and [C; B] you need to choose the one at the ends of which the function F takes on the values ​​of different symbols. The described process must be continued until the desired number is found.

An attentive reader may have noticed that this method does not always give the desired answer: the case where a “fake” root is obtained already at the first step is shown in figure 4.

Task 13.3. Project the solution to the equation X³ + 3X - 1 = 0 on the segment [A; B] with EPSILON precision using the polyvine division method.

Backtracking method
Let us again consider the problem of finding the root of the equation F(X) = 0 with an accuracy of 0.001 on the interval [A; B], but this time we will not make any assumptions about the presence of roots on the segment.
Consider the segment [A; A + H], where H is an arbitrary “small” number

Fig. 4.
Fig. 6.
