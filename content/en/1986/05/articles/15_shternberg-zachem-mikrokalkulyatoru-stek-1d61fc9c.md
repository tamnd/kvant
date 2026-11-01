---
id: 1986-5-shternberg-zachem-mikrokalkulyatoru-stek-1d61fc9c
issue: kvant_1986_5
year: 1986
number: "5"
title: Why does a microcalculator need a stack?
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 41
page_last: 45
page_labels: 39-43
tag: ZTQD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1b15a7ec8bc7ed562f599baf516c4c9589368703823bdd8b54addfd9d411a6a1
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/15_shternberg-zachem-mikrokalkulyatoru-stek-1d61fc9c.md
source_content_sha256: 80ad97faf14b92ff695791a15e6ec32374842e71cff91e5ffd7c2cffe7b03680
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Why a microcalculator stack

Candidate of Physical and Mathematical Sciences
L. F. STERNBERG

This article is intended primarily for ninth-graders who will use a programmable microcalculator when studying the basics of information technology course. However, the article will be useful and powerful for other users of calculators (programmable or not), since it talks about the use of notation - a very simple example that can greatly simplify the organization of calculations.

On the programmable calculators "Electronics" BZ-34, MK-56, MK-54 there is an interesting device - a stack, which consists of four registrations: X, Y, Z, T, used at first glance in a rather strange way. The ↑ command advances information on the stack - the contents of T are destroyed, the contents of Z are entered into T, the contents of Y are entered into Z, the contents of Y are entered into Y, which remains in X:

The command F ↑ moves the contents of the stack in the opposite direction, only the contents of X are not destroyed, but are transferred to T.

There is an XY command that exchanges the contents of X and Y and does not affect the rest of the registrations. If one of the operations ↑ or C was not performed before entering a number into X or calling a number from registration, then before entering a new value into X, ↑ is automatically performed, that is, Z is sent to T, Y to Z and X to Y.

When performing operations on two numbers (for example, X+Y or X×Y), these numbers are taken from Y and X, the result is sent to X, and the weight of the stack is shifted:

(keep in mind that this is not how the X^Y operation works). But when performing operations on one number (for example, sin X), everything is done in a very different way: the argument is taken from X, the result remains in X, and nothing else moves.

Why does the stack work this way and how should it be used? Let's try to work with the stack.

Let's calculate the expression a×b−c/d. Let's assume that the value of a, b, c and d is in registration a, b, c and d respectively. Let's leave the intermediate result on the stack without sending it to memory, and continue the calculations - let's see what comes of it.

Table 1

| № | Teams | Stack Contents | X | Y | Z | T |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 00 | IP a | a | | | | |
| 01 | IP b | b | a | | | |
| 02 | × | a×b | | | | |
| 03 | IP c | c | a×b | | | |
| 04 | IP d | d | c | a×b | | |
| 05 | ÷ | c/d | a×b | | | |
| 06 | — | a×b−c/d | | | | |

It is easy to see that this program is the best available of all possible ones, since there is not a single extra command in it: you need to call up the original data from the registration - which means you can’t do without four UI commands, and during the operation you need to execute,

⟦folio 40⟧

and there is nothing else in the program. It looks like the stack is a substitute thing: let’s try to work with it some more, but let’s take a more complicated expression:

$$\frac{p - \frac{d}{(a+b)}}{(e+f)} \times (k+l).$$

We will not distribute the registers (they can be distributed as desired).

Team | Stack Contents | X | Y | Z | T | Comments
--- | --- | --- | --- | --- | --- | --- | ---

00 | IP a | a | | | | | As we learned in first grade, we start with expressions in brackets

01 | IP b | b | a | | | | Let's leave the intermediate result on the stack: let's see where it ends up.

02 | + | a+b | | | | | And we will leave this intermediate result on the stack.

03 | IP e | e | a+b | | | |

04 | IP f | f | e | a+b | | |

05 | + | e+f | a+b | | | | And we will leave this intermediate result on the stack.

06 | IP k | k | e+f | a+b | | |

07 | IP l | l | k | e+f | a+b | The stack is at its limit - now we'll lose a+b!

08 | + | k+l | e+f | a+b | a+b | No, it's gone! (a+b) is preserved.

09* | F⊙ | e+f | a+b | a+b | k+l | Now we should divide d by (a+b), but (a+b) is somewhere deep and deep. With difficulty we got three extra teams.

10* | F⊙ | a+b | a+b | k+l | e+f |

11* | F⊙ | a+b | k+l | e+f | a+b |

12 | IP d | d | a+b | k+l | e+f | The values ​​d and a+b are called, but they are not in those registrations: they will have to be swapped.

13* | XY | a+b | d | k+l | e+f | And again we leave the result on the stack.

14 | ÷ | $\frac{d}{a+b}$ | k+l | e+f | e+f | And again we leave the result on the stack.

15 | IP p | p | $\frac{d}{a+b}$ | k+l | e+f |

16* | XY | $\frac{d}{a+b}$ | p | k+l | e+f | Again the numbers are not in the right order and less is needed.

17 | - | $p - \frac{d}{a+b}$ | k+l | e+f | e+f | It looks like the stack is working on us: the necessary intermediate results are in the most inconvenient places - it’s not immediately clear where they are and how to get them.

18* | F⊙ | k+l | e+f | e+f | $p - \frac{d}{a+b}$ |

19* | F⊙ | e+f | e+f | $p - \frac{d}{a+b}$ | k+l |

20* | F⊙ | e+f | $p - \frac{d}{a+b}$ | k+l | e+f | At least I was lucky during the last operation: the necessary intermediate results were right there.

21 | ÷ | $\frac{(p - \frac{d}{a+b})}{e+f}$ | k+l | e+f | e+f |

22 | × | answer | e+f | e+f | e+f |

⟦folio 41⟧

in the program). Obviously, if we had memorized these results in time in the memory registration, we would have taken into account at least half of these 8 extra commands. Yes, as long as you report where the result is now in the stack... It’s better without a stack!

But before we abandon the stack, let’s try to understand why in the first program the stack “behaved” so well, and in the second, on the contrary, it “behaved” so badly. To do this, we will have to go back 60 years to visit the useful mathematician Jan Łukasiewicz, who did not have the slightest idea about microcalculators, but still depicted one remarkable design, now well known to those who write compilers for computers, and called the user inversion notation.

In operations on two numbers, we put a sign between the numbers; above one number - before this number. Lukasiewicz suggested putting the sign always before the numbers (direct notation) or always after them (inversion of the notation - this is what will interest us), that is, instead of a-b write ab - and together lg a write a lg.

First impression: “So what? You can write like this. It’s just uncomfortable and continuous.” Continuously? Yes. But is it inconvenient? Let us write the expressions “(a+b)×c” and “a+b×c” in inversion. In the first of them, the expression a+b (which itself must be written in ab+) and the number c are multiplied; in the second, a and the expression b×c (written as bc×) are added. So:

Red shows which numbers the operation captures. Look at the user notation: the parentheses have disappeared - they are not needed, the operations are lined up in the order in which they are performed, and you can forget about the precedence of operations: the operations are simply performed in order - next to the right. (If only we had been taught these rules of arithmetic from the first grade! How much easier it would be!)

Let us now write in user notation the expression for which we compiled the first program:

$$ab \times cd \div —$$

Now just look at the program... and everything will become clear: our program is an exact copy of use.

The user notation for the expression (*) is:

Now let's take a look at our program for calculating this expression... and it will immediately become clear what we did there and why the stack behaved badly. If you write a program exactly according to the used entry, you will get exactly 15 commands - not a single extra one!

- Amazing! - the reader will say. — But how to get a user record from a general record?

Very simple. Let's write the expression (*) in linearized notation (that is, without multi-step formulas):

$$p - (d/(a+b))/(e+f) \times (k+l)$$

and apply 3 simple rules:

1. Let's write down the numbers and variables in the order in which they are written: pdabefkl.
2. Let's write down the operations in the order in which they should be performed (provided that the first operation that can already be performed is always performed): +/-++/+×
3. Let's insert the operations directly after the corresponding numbers.

In fact, it is not necessary to create a user record in advance; you can do this while writing the program. We program the same example, reading the linear iso-

⟦folio 42⟧

bathroom entry with a symbol (only the brackets are not read, but taken into account; see Table 3).
We obtained the optimal program: 8 data calls and 7 operations.
And the stack “behaves” perfectly: pay attention to how the intermediate results “swing” in the stack, but at the right moment they are always in place and in the appropriate order. It can be mathematically proven that this will always happen. (Only the operation $X^Y$ behaves differently: the fact is that... it is simply implemented incorrectly - all operations on two numbers have the first in $Y$, the second in $X$, this one has the opposite; all operations on two numbers are different)

| Readable character | Reasoning | Recorded command | |
| :--- | :--- | :--- | :--- |
| $p$ | Numbers and variables are always written to the stack | IP $p$ | 1 |
| — | The operation cannot be performed - there is nothing to do with it! - we skip. | | |
| $d$ | The variable is on the stack. | IP $d$ | 2 |
| / | The operation is not ready for execution—we skip it. | | |
| $a$ | The variable is on the stack. No operation can be performed yet. | IP $a$ | 3 |
| + | The variable is on the stack. No operation can be performed yet. | | |
| $b$ | On the stack. | IP $b$ | 4 |
| | Finally we came across an operation for which both numbers were on the stack. Let's do it. | + | 3 |
| | Do we have any pending operations for which the data is ready? Yes - division. Let's carry it out (where are the necessary numbers? - you don't have to worry - just on the ground). | ÷ | 2 |
| | And again an operation has appeared for which the data is ready - let’s perform it. | — | 1 |
| / | There is nothing to do with large ones - we read the next symbol and postpone the operation - it is not ready. | | |
| $e$ | On the stack. There is nothing to do yet. | IP $e$ | 2 |
| + | Let's pass - she's not ready. | | |
| $f$ | On the stack. | IP $f$ | 3 |
| | The numbers are ready for addition - let's do it. | + | 2 |
| | The data is ready for division - let's do it. | ÷ | 1 |
| × | Let's skip - there's nothing to worry about | | |
| $k$ | On the stack. For "×" and "+" the data is still not ready. | IP $k$ | 2 |
| + | On the stack. And you can do “+” | IP $l$ | 3 |
| | Let's do the addition. Everything is ready for multiplication. | + | 2 |
| | Let's do the multiplication. End. | × | 1 |

Table 3

⟦folio 43⟧

stack, this one is not; so when programming it using the indicated method you will have to write $\vec{XY}$, $FX^Y$, $\vec{XY}F$ or write $e^{Y \times \ln X}$ together with $X^Y$ - then everything will work out.)

Now it has become clear why the stack of work is this way, and it turns out that you don’t even need to keep track of where each result is at each moment: at the right moment it will be where it is needed.

But... what if we don’t have enough 4 stack registers? Then the intermediate result must be written into memory. But how can we determine whether we have enough stack or not? Do you need to keep track of all the stack swings? No, actually everything went through: let's look at the table column that has no header; - there are some numbers in it - they show how many stack registrations are occupied (you don’t need to write the entire stack table, but you need to write these numbers). The rule for filling the column is very simple: which PI command adds one, which operation on two numbers decreases the previous number by one, operations on one number do not change it. And if the number 5 appears, then at that moment, during the next “pumping” of the stack, one of the intermediate results will be lost.

How is life then? It is not possible to answer this question in detail by cheating the stats. We will only note that in such a situation you can always use memory registration, but it is often possible to reorganize the formula used for calculations so that a stack overflow does not occur.

In conclusion, we note that using inversion to record weight is convenient when organizing calculations on a (non-programmable) engineering calculator: it is used to prevent multichrome results from being copied from the indicator.

On the mathematics of harmonic oscillations
(See beginning on p. 9)

into the model of sound waves created by I. Newot: at the prima level in the direction of sound propagation, a system of massive oscillating precision weights connected by small springs devoid of mass is considered. The kinetic energy of this system is concentrated in the weights, and the potential energy is stored in the springs. Such a system is called a system of coupled oscillators on the prima. Such systems can be considered both on a plane and in space.

Systems of coupled oscillators are conveniently modeled in many branches of mechanics and physics. Further, such a very simple science as elementary particle physics uses a system of coupled oscillators as one of its foundations - a model of physical vacuum. From this point of view, a vacuum can be considered as a very complex musical instrument that responds with certain vibrations to any external influence.

Using the area...
(See beginning on p. 16)

Exercises

1. Given a regular triangle $ABC$ and a point $O$ inside it; $A', B'$ and $C'$ are the projections of this point onto the heights $AA_1$, $BB_1$ and $CC_1$, respectively. Prove that the value $AA' + BB' + CC'$ does not depend on the choice of point $O$.

2. Prove that in a convex polygon, all angles of which are equal, the sum of the lengths of the perpendiculars drawn from any interior point $O$ to the sides of the polygon (or to their extensions) does not depend on the position of the point $O$.

3. Prove that if the opposite sides of a quadrilateral are not parallel, then the midpoint of the segment connecting the intersection points of the opposite sides lies on the line connecting the midpoints of the diagonals.

4. Prove that the bisector of angle $B$ of triangle $ABC$ is equal to $\frac{2ac}{a+c} \cos \frac{\beta}{2}$.

5. Prove using area that each median of a triangle is divided by every other median in the ratio 2:1, counting from the vertex, and thus the medians of the triangle intersect at one point.

6. On the side $AC$ of the triangle $ABC$ the point $D$ is taken. Prove that the sum of the radii of the inscribed circles of triangles $ABD$ and $BCD$ is greater than the radius of the inscribed circle of triangle $ABC$.
