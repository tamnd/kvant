---
id: 1970-1-kolmogorov-chto-takoe-funktsiya-fa7fa494
issue: kvant_1970_1
year: 1970
number: "1"
title: What is a function
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 29
page_last: 38
page_labels: 27-36
lang: en
source: kvant_digital
extraction: vision
content_sha256: d01c234d23062c1aa4d28eb61f76f059f999c8ce4b20d3bf716f9d1055c73f61
prompt_sha256: draft-1
translated_from: content/ru/1970/01/articles/07_kolmogorov-chto-takoe-funktsiya-fa7fa494.md
source_content_sha256: 7f487960b6dea9cf61443221bafdc4b86fa65d5887aaeec1ed4e83d5c8a71ed6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

---
running_head:
folio:
---

A. N. KOLMOGOROV

This article declares modern
general understanding of the word “function”.
The article is not for easy reading:
it requires the reader to pay attention to every word,
although it does not require any special knowledge,
beyond high school.
This also means
that readers know how to handle words
"set" and "element of set".

1. INTRODUCTION

To the question “What is a function?” Schoolchildren often answer: “A function can be specified by a table, graph or formula.” It is clear that this is not certain. But schoolchildren who shy away from formulating an explicit definition and immediately move on to describing how functions are written are not entirely wrong. Mathematics cannot begin with definitions. When I formulate the definition of a certain concept, we inevitably use some other concepts in this very definition. Until we understand the meaning of any concepts, we will not get anywhere and will not be able to formulate a single definition. Therefore, the presentation of any mathematical theory begins with the fact that some basic concepts are accepted without definition. Using them, it is already possible to formulate the definition of further arbitrary concepts.

How do people communicate to each other their understanding of the meaning of basic concepts? There is no other way for this than clarification with examples and with the help of a detailed description of the characteristics of the properties of the things being defined. These descriptions may not be entirely clear in detail and may not be exhaustive at first. But gradually from them the meaning of the concept emerges with sufficient clarity. This is how we approach the concept of function, considering it one of the basic mathematical concepts that are not subject to formal definition.

[True, it will be said later that a function is nothing more than a mapping of one set onto another (the domain of definition of a function onto the set of its values). But here the word display is simply a synonym for the word function. These are two names for the same concept. The explanation of one word by another equally significant cannot replace the definition of the concept it expresses.]

⟦folio 28⟧

Example 1. We will assume that the letters $x$ and $y$ stand for real numbers. The sign $\sqrt{1-x^2}$ will be considered a sign for extracting the argument of the square root. Equality

$$y = \sqrt{1-x^2}$$

indicates that the conditions are met

$$x^2 \leq 1, \quad y \geq 0, \quad x^2 + y^2 = 1.$$

Points whose coordinates satisfy these conditions form a semicircle, depicted by the red line at Fig. 1.

Figure 1 makes clear the following facts, which you can prove purely algebraically:

1) formula (1) allows for any $x$ satisfying the conditions

$$-1 \leq x \leq 1,$$

calculate the corresponding $y$, which satisfies inequality (4), corresponds to at least one such $x$, which according to formula (1) corresponds to this given $y$.

We can say that formula (1) specifies a mapping from the set of numbers $x$ satisfying inequalities (3) to the set of numbers $y$ satisfying inequalities (4). Mathematicians often (especially recently) use an arrow to denote mappings. The mapping we are interested in can be written using an arrow like this:

$$x \rightarrow \sqrt{1-x^2}.$$

For example:

$$\begin{align*}
-1 &\rightarrow \sqrt{1-(-1)^2} = 0, \\
-\frac{4}{5} &\rightarrow \sqrt{1-(-\frac{4}{5})^2} = \frac{3}{5}, \\
\frac{3}{5} &\rightarrow \sqrt{1-(\frac{3}{5})^2} = \frac{4}{5}, \\
0 &\rightarrow \sqrt{1-0^2} = 1.
\end{align*}$$

Note: the mapping is fully specified if

a) given the set $E$, which is displayed,

b) for each element $x$ of this set $E$ there is given an element $y$ on which element $x$ is mapped.

Fig. 1.

Fig. 2.

⟦folio 29⟧

The set of all values ​​of $y$ is denoted by the letter $M$. In example 1, $E$ is the set of numbers satisfying condition (3), and $M$ is the set of numbers satisfying condition (4) *).

Example 2. Rules

1) $x \to \sqrt{x^2}$,
2) $x \to \begin{cases} x, \text{ если } x \geqslant 0, \\ -x, \text{ если } x < 0 \end{cases}$

define the same mapping

$$x \to |x|$$

(7)

real numbers $x$ on their model (absolute values) $|x|$ (Fig. 2).

Mapping (7) displays the set of all real numbers

$$R = (-\infty, \infty)$$

for many

$$R_+ = (0, \infty)$$

non-negative real numbers.

Instead of the word mapping, you can say function and write mapping (5) like this:

$$f(x) = \sqrt{1-x^2},$$

(8)

and display (7) is like this:

$$f(x) = |x|.$$

(9)

The partial values ​​of function (8), listed in formulas (6), will then be written in the following form:

$$f(-1) = 0, \quad f\left(-\frac{4}{5}\right) = \frac{3}{5}, \quad f\left(\frac{3}{5}\right) = \frac{4}{5}, \quad f(0) = 1.$$

The domain of function (9) is the set of all real numbers $R$. The set of its values ​​is the set $R_+$ of non-negative real numbers.

Example 3. Petya, Kolya, Sasha and Volodya live in a dorm room. For February they set the following activity schedule:

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | . . . | 28 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Petya | ■ | | | | ■ | | | | ■ | | | | ■ | | . . . | |
| Kolya | ■ | | | | ■ | | | | ■ | | | | | | . . . | |
| Sasha | ■ | | | | ■ | | | | ■ | | | | | | . . . | |
| Volodya | ■ | | | ■ | | | | ■ | | | | | | | . . . | |

*) A set can be denoted by any letter. Here we take the letters $E$ (from the French word ensemble - set) and $M$ (German - Menge; by chance the Russian word “set” begins with the same letter). But this is not necessary: ​​in the next example we will denote the set of real numbers, as is customary, by the letter $R$ (French gel - real, real).

⟦folio 30⟧

The similarity of this table with the graphs of functions familiar to you from the school algebra course is immediately striking. Does this analogy make precise logical sense? Have the boys here established a mapping from one set to another, that is, have they defined some function? And didn't they draw a graph of this function? (Pay attention to the everyday expression “established the graph of the function”!)

2. GENERAL CONCEPT OF FUNCTION

It is easy to see that in example 3 a certain duty officer is assigned for each of the 28 days of February. In other words, many days in February are reflected in many boys, sharing duty among themselves. We can agree that the letter x stands for any day in February, and y=f(x) stands for the person on duty on day x. There is no reason to refuse display

day x→y = duty officer for day x

in the right to call it a function and write this mapping like this:

y=f(x).

We will call any mapping f a set E onto a set M a function with a domain of definition E and a set of values ​​M.

Don't forget that when we talk about mapping f from set E to set M, we mean that y=f(x) is defined for any x from E and

Mapping E to M

Mapping E to M

only for x from this set, and the value y of the function f necessarily belongs to the set M, and each y from this set M is the value of the function f for at least one value of the argument x.

If it is known only that the values ​​of functions f necessarily belong to the set M, but it is not stated that every element of this set is the value of the function f, then we say that the function maps its domain of definition E into the set M or that the mapping f is a mapping of the set E into the set M.

Thus, it is necessary to strictly distinguish the meaning of the expressions

"mapping to set M"
“mapping to set M”*).

*) Note also that every mapping “on” can also be called a mapping “in”, but not vice versa.

⟦folio 31⟧

For example, about the image

$$x \rightarrow |x|$$

we can say that it is the map of $R$ to $R$, but we cannot say that it is the “map of $R$ to $R$”.

From a purely logical point of view, the simplest case is the case when the domain of definition of the functions is finite. It is clear that a function whose domain consists of $n$ elements cannot take more than $n$ different values. Thus, functions defined on finite sets carry out mappings of finite sets onto finite sets. Such images are one of the subjects of studying an important part of mathematics - compinatorics (see problems 8, 11, 18, 19).

Example 4. Consider functions whose domains of definition are many

$$M = \{A, B\}$$

of two letters $A$ and $B$ and whose values ​​belong to the same set, i.e., images of the set $M$ into itself.

There are only four such functions. Let's assign them to tables in the following way:

| $x$ | $f_1(x)$ | $f_2(x)$ | $f_3(x)$ | $f_4(x)$ |
| :--- | :--- | :--- | :--- | :--- |
| $A$ | $A$ | $B$ | $A$ | $B$ |
| $B$ | $A$ | $B$ | $B$ | $A$ |

The functions $f_1$ and $f_2$ are constants, that is, constants: the set of values ​​of each of these functions consists of one single element.

The functions $f_3$ and $f_4$ map the set $M$ onto itself. The function $f_3$ can be given by the formula

$$f_3(x) = x.$$

This is an image concept: each element of the set $E$ is processed in itself.

To complete the clarification of the meaning of the very concept of “function”, it remains to pay attention to the fact that the choice of letters to denote an “independent variable”, i.e. an arbitrary element of processing, and a “dependent variable”, i.e. an arbitrary element of a set of values, perfect non-existence. Posts

$$x \rightarrow \sqrt{x}, \quad \xi \rightarrow \sqrt{\xi}, \quad y \rightarrow \sqrt{y},$$

$$f(x) = y = \sqrt{x}, \quad f(\xi) = \eta = \sqrt{\xi}, \quad f(y) = x = \sqrt{y}$$

define the same function $f$, which processes a non-negative number into the arithmetic square root of it. Use any of these entries, we will get

$$f(1) = 1, \quad f(4) = 2, \quad f(9) = 3$$

etc.

⟦folio 32⟧

3. REVERSIBLE FUNCTION

Function

$$y = f(x)$$

called *reversible*), if each value it takes one -
the only time. These are the functions $f_3(x)$ and $f_4(x)$ from example 4. The functions
$f_1(x)$ and $f_2(x)$ of Example 4 and the functions of Examples 1, 2 and 3 are inorganic.

To prove that any function is irreversible, it is enough to indicate
take any two values ​​of the argument $x_1 \neq x_2$ for which

$$f(x_1) = f(x_2).$$

In example 3, it is enough to note that Petya is on duty both on the 1st and on the 5th
February. Therefore, the function of example 3 is irreversible.

Example 5. Function $f$

$$x \xrightarrow{f} y = -\sqrt{x}$$

reversible. It is defined on the set $R_+$ of non-negative numbers. Multi-
the gesture of its meanings is the multitude

$$R_- = (-\infty, 0]$$

all non-positive numbers. Given any $y$ from the set $R_-$, one can find
corresponding to $x$ by the formula $x = y^2$.

Function $g$

$$y \xrightarrow{g} x = y^2$$ at $y \leqslant 0$

There are functions *inverse* to the function $f$. It maps the set $R_-$ to the set $R_+$. As already mentioned, there is no choice of letters to denote the independent and dependent variable. The functions $f$ and $g$ can be written as

$$f(x) = -\sqrt{x}$$ for $x \geqslant 0$, $g(x) = x^2$ for $x \leqslant 0$.

figure 3 shows the graphs of mutually inverse functions $f$ and $g$.

Fig. 3.

Fig. 4.

*) The origin of the name will become clear later: a function is invertible if for it
there is an inverse function.

⟦folio 33⟧

Example 6. Function $f$ given by table

$$\begin{array}{c|cccc}
x & A & B & B & \Gamma \\
y = f(x) & 3 & 1 & 2 & 5 & 4
\end{array},$$

is defined by the set of the first five letters of the Russian alphabet, and the set of its values ​​is the set of the first five natural numbers. The inverse function $g$ is given by the table

$$\begin{array}{c|cccc}
x & 1 & 2 & 3 & 4 & 5 \\
y = g(x) & B & B & A & D & \Gamma
\end{array}.$$

figure 4 shows the graphs of these functions.

Let us give precise definitions. Let $f$ be a mapping from the set $E$ to the set $M$. If for any element $y$ from the set $M$ there is one and only element

$$x = g(y)$$

set $E$ for which

$$f(x) = y,$$

then the mapping $f$ is inverse, and

$$y \rightarrow x$$

is called the inverse mapping to the mapping $f^*$.

Reversible mapping of $E$ to $M$

Reversible mapping of $E$ to $M$

Thus, the invertibility of the mapping $f$ means that it has an inverse mapping $g$. The inverse of $f$ is usually denoted by $f^{-1}$. For example, if

$$f(x) = x^3,$$

That

$$f^{-1}(x) = \sqrt[3]{x}.$$

Since the word “function” is simply a synonym for the word “mapping,” we have thereby defined the meaning of the expression “inverse function.”

*) Such mappings are also called one-to-one mappings $E$ onto $M$.

⟦folio 34⟧

Try to repeat what was said above yourself, using the words “mapping” together with the word “function”.

It is clear that the domain of the inverse function $f^{-1}$ is the set of values ​​of the function $f$, and the set of values ​​$f^{-1}$ is the domain of the function $f$.

The inverse function of the inverse function $f^{-1}$ is the original function $f$:

$$(f^{-1})^{-1} = f.$$

Thus, the functions $f$ and $f^{-1}$ are always mutually inverse.

Example 7. There are functions that are their own inverse. Such functions

a) $f(x) = x,$
b) $f(x) = \frac{1}{x},$
b) $f(x) = \frac{x}{x-1}$.

Check it out! The graphs of these functions are given on figure 5. Note that all these graphs are symmetrical with respect to the bisector of the first and third squares, i.e. the line $y=x$.

Let us schematically depict the correspondences between different types of mappings from the set $A$ to the set $B$ and $A$ to the set $B$.

Let us recall once again that the most general concept is the concept of the mapping $A$ to $B$. If with such a mapping the image $A$ coincides with $B$, we speak of a mapping $A$ onto $B$.

⟦folio 35⟧

Invertible mappings are also called one-to-one mappings. You will often come across this term in books. But it is not customary to talk about “one-to-one functions.” Since we consider the words “function” and “mapping” to be synonymous, together with the words “one-to-one” we have chosen to use the words “mapped function” or, which is the same thing, “mapped mapping”.

Recently, French terminology has become widespread in our literature:

1) the mapping of $A$ to $B$ is called “surjective” or “surjective” by the French;
2) the mappings $A$ to $B$ are called "injective" or "injections";
3) mapped mappings $A$ onto $B$ are called “bijective” or “bijections” in French terminology.

Please note that with a visiting attitude to the use of the prepositions “in” and “on” such general terms are unnecessary.

3 ADACS

Very easy questions are marked with a zero, by answering which you can check whether you understood what was written in the status. More difficult tasks are marked with an asterisk. It is not necessary to solve them all.

1. Introduction

1.0. Find the domains and set of values ​​of the following functions:

a) $y = f(x) = \frac{1}{x^2}$, 6) $y = f(x) = \sqrt{x^2 - 1}$.

2. The integer part of the number $x$ is the most integer number not exceeding $x$. The whole part $x$ represents $[x]$. For example,

$$[0] = 0, [7,5] = [7] = 7, [-0,3] = -1, [-\pi] = -4.$$

The difference $x - [x]$ is called the fractional part of the number $x$ and denotes $\{x\}$. Plot graphs of the following functions and find their domains and sets of values:

a) $f_1(x) = [x]$, 6) $f_2(x) = \{x\}$, b) $f_3(x) = \{x\} - \frac{1}{2}$, r) $f_4(x) = \left| \{x\} - \frac{1}{2} \right|$,

$$d^*) f_5(x) = \left[ \frac{1}{x} \right], e^*) f_6(x) = \frac{1}{[x]}, j^*) f_7(x) = \left\{ \frac{1}{x} \right\}, 3^*) f_8(x) = \frac{1}{[x]}.$$

3*. For any natural number $n$ we define $s(n)$ as the sum of the divisors of the number $n$ (not counting $n$ itself). For example,

$$s(1) = 0, s(2) = 1, s(6) = 6, s(12) = 16, s(28) = 28, \dots$$

Prove that $s(n)$ does not take the values ​​2 and 5.

2. Function

4.0. Two wholes ($A$ and $B$) can share two rooms in four ways:

How many ways can you accommodate: a) two wholes in three rooms, b) three wholes in two rooms, b) three wholes in two rooms so that none of the rooms is left unoccupied?

⟦folio 36⟧

5. The set $M$ consists of three elements, and the set $N$ consists of two elements. How many mappings are there: a) mappings $M$ to $N$, b) mappings $M$ to $N$, c) mappings $N$ to $M$, d) mappings $N$ to $M$?

6. How many seven-digit phone numbers are there? Which number is formed only by the numbers 0, 1, 2 and 3?

7. Prove that there are more than a million functions that take only two values, 0 and 1, and are defined on the set of the first twenty natural numbers.

8. The set $M$ consists of $m$ elements, and the set $N$ consists of $n$ elements. How many functions are there defined on the set $M$ with values ​​taking $N$?

Let us also note that Tasks 8, 11, 18, 19 are considered among the main problems of combinatorics. We present them here to show that combinatorics has a significant connection with parts and is concerned with counting the number of mappings of one or another type of finite sets into finite sets.

9. How many ways can you seat: a) two guests on two chairs, b) three on three chairs, c) six on six chairs?

10. The set $E$ consists of six elements. Show that there are exactly 720 functions for which $E$ is both the domain and the set of values.

11. The mapping of a finite set onto itself is called a substrange one. The number of different permutations of a set depends only on the number of its elements $n$ and is denoted $n!$. Show that

$$1! = 1, \ 2! = 2, \ 3! = 6, \ 4! = 24, \ 5! = 120, \ 6! = 720.$$

Indicate a general method for calculating $n$!

3. Inverse function

12.0. Which of the following functions are inverse and which are not inverse?

$$f_1(x) = x^3, \ f_2(x) = x^4, \ f_3(x) = x^{17}, \ f_4(x) = x^{18}$$

13. In the class, no more than two people sit behind each pair. Let us assign each student his desk neighbor, and if he is sitting alone, then himself. What will be the return?

14. Let each word of the Russian language be given a corresponding word, written with the same letters, but in reverse order (a word is a sequence of letters). Is this function inverse? If yes, what is the inverse function?

15. A mapping of a finite set onto itself is always invertible. Give an example of a non-inverse mapping of a set of natural numbers onto itself.

16. Nine tourists must be accommodated in three boats. In how many ways can they do this if it is required that a) there are three people in each boat, b) there are no more than four and no less than two people in each boat, b) there is at least one tourist in each boat? (Boats have numbers: No. 1, No. 2, No. 3.)

17*. If the hosts have students, then it is not customary to say for one student one guest: many guests are reflected in many students in the opposite way. If there are only six students in the room, in how many ways can you seat them: a) one guest, b) two guests, c) four, d) heels, e) six guests?

18*. The inverse mappings of one finite set $M$ into another finite set $N$ are called placement (guests are “placed” on chairs). The number of mappings of the set $M$ into the set $N$ depends only on the number of elements $m$ of the set $M$ and the number $n$ of elements of the set $N$ and is denoted $A_m^n$. Show that

$$A_1^1 = 1, \ A_2^1 = A_2^2 = 2, \ A_3^1 = 3, \ A_3^2 = A_3^3 = 6, \ A_1^2 = 90,$$

and the general rule for calculating $A_n^m$ is established. Show that it is always $A_n^{n-1} = A_n^n$.

19*. Task 16c can be formed abstractly: how many mappings are there of a set of ninth elements onto a set of three elements. Let $D_n^m$ denote the number of mappings of a set of $n$ elements onto a set of $m$ elements. Check that

$$D_3^2 = 6, \ D_4^2 = 12, \ D_4^3 = 36, \ D_n^n = n!$$

Try the general rule for calculating $D_n^m$ (this is a slightly more difficult problem than problems 8, 11 and 18).

20*. How many functions are there, defined on a set of 28 elements, that take each of the four values ​​P, K, C and B six times?

This is a problem about the number of ways to fairly distribute duty in February between Petya, Kolya, Sasha and Volodya (example 3 on page 29).
