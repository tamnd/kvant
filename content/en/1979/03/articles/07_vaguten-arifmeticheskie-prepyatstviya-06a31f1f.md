---
id: 1979-3-vaguten-arifmeticheskie-prepyatstviya-06a31f1f
issue: kvant_1979_3
year: 1979
number: "3"
title: Arithmetic obstacles
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 32
page_labels: 22, 23, 24, 25, 26, 27, 29, 30
tag: 9DYL
lang: en
source: kvant_digital
extraction: vision
content_sha256: e55d93be3d2c8db1111b4c15833be5f041bce073ae06431e3dbffac8c6efd7f6
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/07_vaguten-arifmeticheskie-prepyatstviya-06a31f1f.md
source_content_sha256: d7398fb1284f2729dbbe77303c84d1239c729752211260ee0c5cc29d3dc8bedb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Arithmetic obstacles

In many mathematical theory and applied problems, as well as in mathematical games and puzzles, questions of this kind arise: is it possible to move from one position to another using some “valid” operations (moves)? How to find the required integer-move if it exists, or prove that the transition is impossible? In this article we will analyze several tasks of this type. They are also united by their external state: in each of them integers appear, and the “obstacles” to transitions, as a rule, are of an arithmetic nature.

Examples with which the discussion of each problem begins are accessible even to elementary school students. The constellation exercises and proofs of general results require serious thought from the reader. The article ends with difficult Olympic problems, the last of which is applied to the non-elementary, rapidly developing theory of arthmetic groups.

1. Problem about the horse

Problem 1. Given natural numbers m and n. On one of the fields of an infinite chess point there is a figure that moves “with the letter Γ” on m fields in one of the directions and on n in the perpendicular one; call it {m; n}-kone. Which field can this horse go to?

An ordinary chess knight ({1; 2}-knight) can get from any initial square O to any other: in three moves it can get to a square adjacent to O, and with elementary steps one can, of course, arrive anywhere.

But {1; The 3}-knight, whose several moves are shown on figure 1, cannot possibly get to the adjacent (horizontally) square to the initial square. On a chessboard it is very easy to explain what prevents such a transition: {1; 3}-knight always moves on squares of the same color. On the other hand, it is not difficult to show that {1; A 3}-knight can bypass all squares of the same color: in three moves it can merge diagonally onto an adjacent square of the same color (Fig. 1), and with elementary steps it can easily bypass all single-point squares.

Try to solve problem 1 for numbers a) 2 and 5; b) 10 and 25; d) 19 and 79.

It turns out that {m; The n}-knight can occur in any case where m and n have different parities and their most common divisor is 1.

The complete answer to problem 1 is given at the end of point 3 (exercise 10). Now we will deal with a simpler issue. The result we get is useful both for the horse problem and for more server-side mathematical problems.

Fig. 1. {1; 3}-knight can get to an adjacent (diagonally) square of the same color; With such steps he can bypass all single-weight fields.

⟦folio 23⟧

2. GCD representation
Problem 2. Given natural numbers a and b. In one move, the cut is to add one of the numbers a, b to some integer or subtract one of these numbers from it. Is it possible to get the number c from the number 0 in the maximum way?

In this problem, the possible “position” is the set Z of all integer points on the number line.

Let's start with a specific example. Let’s assume that the buyer and the cashier only have 10 and 25 ruble bills, and (they don’t exist in mathematical problems!) in unlimited quantities. It is clear that the buyer can schedule c rubles to the cashier if and only if c is a multiple of 5.

Another example. Let moves ±19 and ±79 be allowed on set Z. With these moves you can get any integer: their combination allows you to move to a distance of 3, and then to a distance of 1 (Fig. 2, a).

A more complex example: a=819, b=357. In this case, the same technique manages to find the shortest sdigg - at 21 (Fig. 3, a). Thus, here it is possible to make a transition to any distance that is a multiple of 21. On the other hand, both a and b are divisible by 21, so no other transitions are possible.

Note that 21 is the most common divisor of 819 and 357 (check this out!).

Difference 1. a) Prove that if the buyer and the cashier have (in unlimited quantities) three rubles and fives, then the buyer can plan any number of rubles.

6) Is it possible to go from 0 to 1000 if a=123, b=456? if a=589, b=1984?

b) What transitions are possible at a=18, b=81?

Now let’s formulate the answer to problem 2 in general form. Let the most

⟦folio 24⟧

The greatest common divisor (GCD) of numbers a and b is equal to d. Then the transition from 0 to c is possible in either case, when the number c is divisible by d. Try to prove it.

We will obtain this result in a slightly different form in the next section.

Have a womanized
2. Prove that the answer to Problem 2 does not change if the number a can only be added, and b can only be subtracted.
3. Is it possible to answer a) 150 g on a cup scale using weights of 36 g and 60 g (these weights are available in unlimited quantities and can be placed on both cups of scales); b) 132 g?

3. Euclid's algorithm
In the next problem, the positions will be pairs of integers.

Problem 3. Three atoms print pairs of integers on cards. Each atom, having read a certain card, is given a new card: the first atom, having read a card with a pair (x; y), is given a card (x-y; y), the second is given a card (x+y; y), the third is given a card (y; x).

Let there initially be one potato with a pair of numbers (1; 2). Is it possible, using atoms in any order, to obtain a card (19; 79)? (819; 357)?

What general cards can you get if you initially have a potato with a pair of numbers (a; b)?

Fig. 4. Each “march” of this staircase is one step of the Euclidean algorithm.

Let's denote the operations that the automata perform, respectively, as L, R and S. Let's start again with numerical examples.

A pair (19; 79) can be obtained from a pair (1; 2) using the operations L, R, S. To make the necessary transition, it is more convenient not to ascend from (1; 2) to (19; 79), but to descend in the opposite direction (Fig. 4).

By writing the resulting integer in reverse order (and, of course, replacing L and R), we get a “rise” from (1; 2) to (19; 79).

At figure 4 "descent" from (19; 79) to (1; 2) we continued to the pair (1; 0); a shortened version of this “descent” is given at figure 2, in (Lᵉ means that the operation L is performed k times in a row). As a matter of fact, we have already performed the same descent in accordance with the example to the previous problem (Fig. 2, a).

The descent starting with the pair (819; 357) is abbreviated as figure 3, write it down in detail. Here the pair (1; 2) (or 1; 0) does not work. And not surprisingly, there is an advantage to this: all the resulting numbers are divisible by 21. No matter in what order we apply the operations L, R, S, we can get rid of this advantage of inaccessibility, since, as is easy to prove, these operations preserve the common divisors of the numbers on the card: GCD (x-y, x) = GCD (x+y, y) = GCD (x, y). Therefore, the answer from the pair = (819; 357) to the pair (1; 2) or vice versa is impossible.

In razzhenne 4. Is it possible, using the operations L, R, S, to move a) from the pair (1; 10) to the pair (5; 25)? 6) from (18; 81) to (36; 63)? in from (589; 1984) to (31; 1953)?

Now we can formulate an answer to the last, general question of Problem 3: the pair (a; b) can be translated into a pair (p; q) in this and that case, when gcd (a; b) = gcd (p; q). This condition is necessary because, as we have already said, our operation preserves the gcd. But it is also sufficient: if gcd (a, b) = gcd (p, q) = d, then each of these pairs of operations L, R, S can be reduced to a pair (d; 0); by starting from (a; b) to (d; 0) and then ascending from (d; 0) to (p; q), we get an integer from (a; b) to (p; q).

⟦folio 25⟧

Fig. 5. Using the operations L, R, S you can change the sign of one number on a card.

Let us show why we can go from any pair $(a; b)$ to the pair $(d; 0)$. Note that if one of the elements of the pair is negative, then it is easy to make it positive (Fig. 5). And the pair $(a; b)$ with naturals and $b$ can be reduced to the pair $(d; 0)$ in the same way that we used in the examples: at each step (except for symmetry permutations), the larger element of the pair is reduced until we come to the final $\rightarrow (d; d) \rightarrow (0; d) \rightarrow (d; 0)$.

Solving problem 3, we got a convenient way to find the most common divisor of two numbers: from the pair $(a; b)$, where $a > b > 0$, we go to the pair $(b; r)$, where $r$ is the remainder of the division of $a$ by $b$, and repeat this operation until we get the pair $(d; 0)$. The last non-zero remainder $d$ is the GCD $(a; b)$ (Fig. 2, b, 3, b). This method is called the Euclidean algorithm.

At the right
5. Prove that from the pair (1357; 2468) it is impossible to obtain the pair (1234; 5678); from the pair (123; 457) it is impossible to obtain (7890; 1979).

6. Give examples showing that the operation of Problem 3 is not commutative: $LS \neq SL, RS \neq SR$ (of course, $LR=RL$).

7. Using the Euclidean algorithm, find GCD (589, 1984), GCD (123456789, 987654321).

An integer lattice $Z^2$ is the set of all points of the plane with integer coordinates.

Fig. 6. “Left fringe” $L(x; b) \rightarrow (x-b; b)$, “right fringe” $R(x; b) \rightarrow (x+b; b)$, “symmetry” $S(x; b) \rightarrow (b; x)$ are linear transformations of the plane that carry out one-to-one mappings of the integer lattice $Z^2$ onto itself.

⟦folio 26⟧

The following exercises and figure 6 clarify the geometric meaning of problem 3:

8. Prove that if the segment $OA$, where $O$ is the origin of coordinates, $A$ is a node of the integer lattice $Z^2$, is divided by other nodes into $d$ parts, then the operations $L$, $R$ and $S$ node $A$ can be translated into nodes $(d; 0)$ and $(-d; 0)$ and cannot be translated to any other points on the $Ox$ axis.

Exercises 9 and 10 generalize problems 1 and 2:

9*. Let $n$ natural numbers $a_1, a_2, \dots, a_n$ be given. Prove that the integer $c$ can be obtained from 0 by moves $\pm a_1, \pm a_2, \dots, \pm a_n$ if and only if $c$ is divisible by $HOД$ ($a_1, a_2, \dots, a_n$).

10*. a) Let $n$ vectors $v_1, v_2, \dots, v_n$ with integer coordinates be given on the plane $Oxy$. Prove that the set of points $D$ of the plane, which can be reached from point $O$ by moves $\pm v_1, \pm v_2, \dots, \pm v_n$, is the set of vertices of some cosugular lattice (this is the name of the set of vertices of parallelograms on which two families of equilateral parallel lines cut the plane).

6) Let, along with each vector $v_i$, in the family of vectors $v_1, v_2, \dots, v_n$ there be one equal in length and perpendicular. Then the set of “reachable” points $D$ will be the set of vertices of some square lattice.

Now it is not difficult to find the answer to problem 1: let $m=dm_1, n=dn_1$, where $d=HOД(m, n)$; then, if $m_1+n_1$ is odd, all fields $(dx; dy)$ are reachable, where $x$ and $y$ are arbitrary integers (lattice with step $d$); if $m_1+n_1$ is even, fields $(dx; dy)$, where $x \in Z, y \in Z$ and $x+y$ are even (grid with step $d\sqrt{2}$, rotated at angle $45^\circ$ with respect to linear docks).

4. Some results

In the final part of the article, we will introduce you to two rather difficult problems. But first, looking back, let’s try to express general messages that helped us - and will help us in the future - to find out whether it is possible to move from one “position” to another, and let’s name the mathematical “names” of those concepts that we encountered in the problems.

1°. To prove the impossibility of this or that transition, we discovered a certain solution - a characteristic of the position that remains (as they say, invariant) for all admissible moves, but is different for the initial and final positions; Thus, the proof of the impossibility of one or another transition was reduced to the denial of the invariant. Such an invariant in the problem o {1; 3}-kone is the color of the field, in problem 2 - the remainder of dividing the number by $HOД(a, b)$, in problem 3 - the gcd of a pair of numbers on the cards. You can read more about this in «Kvant» 1974, No. 2 (p. 26), 1976, No. 2 (p. 32) and 1976, No. 12 (p. 19).

2°. To construct an integral transition on a lattice, it is often useful to find some elementary “key” move (or combination of moves), or to reduce it to some simple canonical position, and then formulate a general rule (algorithm) for finding transitions. So, in the problem o {1; 3}-knight just needs to learn how to move diagonally, in task 2 - shift by $d=HOД(a, b)$, in task 3 - “descent” of the canonical position (d; 0).

3°. In all the considered displays, the transitions were directed to position $A$, it was possible to move to position $B$, then it was possible to return back - from $B$ to $A$. In such problems, the entire set of positions is divided into equivalence classes: within one class, one can go from each position to any other, and no transitions between positions from different classes are possible.

Now we will consider a problem in which the relations $1^\circ$ and $2^\circ$ are invertible.

5. Getting rid of the two

Problem 4. Three authors print pairs of natural numbers on cards. The machines work as follows: the first author, having read the card $(a; b)$, issues a card $(a+1; b+1)$; the second author, having read card $(a; b)$, issues card $(a/2; b/2)$ (it works only if the numbers a and b are even); the third authority, using two cards $(a; b)$ and $(b; c)$, issues card $(a; c)$.

Let the card $c$ initially have a pair of numbers (5; 19). Is it possible, using authorates in

⟦folio 27⟧

all right, get card a) (1; 50)? b) (1; 100)?

c) Let initially there be a card (a; b), a < b, and we want to get a card (1; n). Under what conditions can it be done?

This problem was proposed at the XII All-Union Mathematical Optimization for students in grades 8–10*. However, even a fifth-grader will have enough knowledge to solve it.

Let us denote the operations that our new automata perform, corresponding to them by I, H and T. On figure 7 we show how to get the “simplest” card (1; 8) from card (5; 19) and then card (1; 50) (instead of “apply operation I k times” we again write I^k). Thus, in problem a) the answer is positive.

But card (1; 100), which he asks about in problem 6), cannot be obtained from card (5; 19). The obstacle can be discovered by carefully studying the same figure 7: the difference between the numbers on each card is divisible by 7. No matter in what order we used the machines, we could not get rid of this property - it is preserved by the operations I, H and T. (For I this is very indo. For H: if a and b are even and b - a is divisible by 7, then b/2 - a/2 is divisible by 7. For T: if the differences b - a and c-a is divisible by 7, then c-a=(c-b)+(b-a) is divisible by 7.) But the difference 100-1=99 is not divisible by 7, so the answer to 6) is negative.

Exercise 11. Is it possible, using the machines I, H and T, a) from card (3; 33) to obtain cards (5; 29), (1; 101), (1; 1978)?

6) From the card (5; 29) get (3; 33), (1; 100), (1; 1979)?

Let us now form an answer to the last, general question in) problem 4: from a card (a; b), in which b—a=2^md, where d>0 and odd, we can obtain me and only me cards (p; q), in which the difference p—q>0 is divisible by d. Thus, it is possible to get rid of all two in the b-a expansion, but the odd divisor of the difference b-a is an insurmountable obstacle.

*) See also problem M516 from Problem Book «Kvant» («Kvant», 1978, No. 8).

Fig. 7. Using the operations I^q (increase by q), H (halving), T (“transitive” transition) from 519 we obtain 150

Fig. 8. A large number b on a card can be reduced (d=b—a; a>1 or a=1, b odd).

In fact, as we have already said (for d=7), from cards whose difference is divisible by an odd number d, using the operations I, H, T, only cards with the same properties are obtained. On the other hand, from card (a; b), where b—a=2^md (d odd), you can go to card (1; d+1). (One step of such a transition is shown in figure 8.) Having received the card (1; d+1), it is easy to make any card (1; kd+1) (as

⟦folio 29⟧

Fig. 9. Reduction to canonical form. For all transformations $L, R, S$ the area of ​​the parallelogram and the location of the nodes of the integer lattice inside it are preserved.

$\begin{pmatrix} 1 & 1 \\ 2 & 2 \end{pmatrix}$ will result in a matrix with identical columns $\begin{pmatrix} p & p \\ q & q \end{pmatrix}$.

c) Matrices $\begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix}$ and $\begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$ are also not equivalent; here a new obstacle arises: the magnitude

$$\Delta = \Delta \begin{pmatrix} a & c \\ b & d \end{pmatrix} = |ad - bc|.$$

It is preserved under all transformations $L, R, S$ of the matrix $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$. Let's check this for $L: (a-b)d-b(c-d) = ad-bc$. (For $R$ and $S$, check the check yourself.) Since $\Delta \begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix} = 3,$ is $\Delta \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = 1$, these matrices are not equivalent. Note that

$$\Delta \begin{pmatrix} p & p \\ q & q \end{pmatrix} = 0.$$

The quantity $ad-bc$ appears very often in various problems about matrices and is called the *definition* of the matrix $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$.

d) Matrices $\begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix}$ and $\begin{pmatrix} 1 & 2 \\ 0 & 3 \end{pmatrix}$ are equivalent: integer transformations leading the first vector $\begin{pmatrix} 1 \\ 2 \end{pmatrix}$ to the canonical form $\begin{pmatrix} 1 \\ 0 \end{pmatrix}$, and small additional modifications of them lead to the integer (Fig. 9). On figure 9 our invariant $\Delta$ is clearly visible: this is the area of ​​a parallelogram constructed on the vectors $\begin{pmatrix} a \\ b \end{pmatrix}$ and $\begin{pmatrix} c \\ d \end{pmatrix}$.

⟦folio 30⟧

Fig. 10. In parallelograms for the matrix $(\begin{matrix} 1 & 1 \\ 0 & 3 \end{matrix})$ and $(\begin{matrix} 1 & 2 \\ 0 & 3 \end{matrix})$ the location of the nodes of the integer lattice is different.

It remains to find out whether the matrices $(\begin{matrix} 1 & 1 \\ 0 & 3 \end{matrix})$ and $(\begin{matrix} 1 & 2 \\ 0 & 3 \end{matrix})$ are equivalent. It turns out that this is not the case, although it is not so easy to indicate the precedence here. Its geometric meaning is clear from figure 9 and 10.

Now we can give an answer to the general question of Problem 5. Any reduced matrix of the operation $L, R, S$ can be transformed to the canonical form

$$\begin{pmatrix} 1 & r \\ 0 & \Delta \end{pmatrix}, \quad \text{где } 0 \leq r < \Delta,$$

(1)

$$\text{НОД}(r, \Delta) = 1,$$

or

$$\begin{pmatrix} 1 & 1 \\ 0 & 0 \end{pmatrix} \quad (\text{если } \Delta = 0).$$

Two matrices are equivalent to a model and a molko model when conditions (*) are met and the corresponding reduced matrices have the same canonical form. (The equivalence criterion is formulated somewhat differently in Exercise 20.)

Indeed, any reduced matrix can be transformed to canonical form in the same way as we transformed the matrix $(\begin{matrix} 1 & 5 \\ 2 & 7 \end{matrix})$ (see Fig. 9). The fact that $r$ is an invariant follows from Exercises 14, 15.

Exercises

14*. Let the matrix $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$ have the canonical form (1). Then inside the parallelogram $OABC$, constructed on the vectors $\overrightarrow{OA} = (a; b)$ and $\overrightarrow{OC} = (c; d)$, lies $\Delta-1$ an integer point. All these points $M_1, M_2, \dots, M_{\Delta-1}$ can be obtained using vector equalities:

$$\overrightarrow{OM}_j = \{j/\Delta\} \overrightarrow{OC} + \{j(1-r/\Delta)\} \overrightarrow{OA},$$

where $\{x\}$ is the fractional part of the number $x$.

15. Let $\text{НОД}(a, b) = \text{НОД}(c, d) = 1, \Delta = |ad-bc| \neq 0$. Then there is a unique $r$ such that $0 \leq r < \Delta$, $\text{НОД}(r, \Delta) = 1$ and the numbers $ra-c, rb-d$ are divisible by $\Delta$, and this $r$ is preserved under the transformation $L, R, S$ of the matrix $(\begin{pmatrix} a & c \\ b & d \end{pmatrix})$.

This exercise is useful for specific calculations of the number $r$ if $\Delta$ is not large.

16. Which environmental matrices of the following are equivalent and which are not:

$$\begin{pmatrix} 5 & 1 \\ 7 & 2 \end{pmatrix}, \quad \begin{pmatrix} 1 & -5 \\ 2 & 7 \end{pmatrix}, \quad \begin{pmatrix} 1 & 3 \\ 3 & 9 \end{pmatrix}, \quad \begin{pmatrix} 4 & 7 \\ 5 & 8 \end{pmatrix},$$

$$\begin{pmatrix} 6 & 14 \\ 17 & 39 \end{pmatrix}, \quad \begin{pmatrix} 5 & 13 \\ 19 & 50 \end{pmatrix}, \quad \begin{pmatrix} 19 & 1 \\ 79 & 4 \end{pmatrix}, \quad \begin{pmatrix} 39 & 60 \\ 50 & 77 \end{pmatrix}?$$

17. Above, we did not consider matrices in which one of the columns is zero. When are matrices equivalent?

18. Prove that any matrices with $\Delta=1$ are equivalent.

19*. How many classes of non-equivalent matrices with $\Delta=3, \Delta=4, \Delta=5, \Delta=10, \Delta=12$ are there? How many average abbreviations? For each class of matrix, draw the arrangement of nodes in accordance with the parallelogram (as in figure 10).

20. Prove that for any matrix the essential equivalent matrix is ​​$(\begin{pmatrix} k & l \\ 0 & m \end{pmatrix})$, where $k \geq 0, m \geq 0, l \geq 0$ and $l < m$ for $m \neq 0$.

Another possible approach to problems 3 and 5 is to find out what kind of integer lattice transformation can be obtained by compositions of operations $L, R, S$ (similar to how in problem 2 we found out what kind of cdwgi can be obtained by compositions of cdwgov ±a, ±b). It turns out that all these lattice transformations have the form $(x; y) \rightarrow (ax+by; cx+dy)$, where $a, b, c, d$ are integers and $|ad-bc|=1$. But this is already the topic of a separate article devoted to linear algebra.
