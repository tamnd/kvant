---
id: 2024-3-zadachi-cbe27c03
issue: kvant_2024_3
year: 2024
number: "3"
title: Tasks
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 37
page_last: 44
page_labels: 37-42
tag: DS90
lang: en
source: kvant_digital
content_sha256: f0bcf190d10e5f0d8e8f580170dc4dcd2c4ffd0cbad513e767711c22ffa817f3
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/08_zadachi-cbe27c03.md
source_content_sha256: be2da87c8c2fd86abe6e115454e300151798b878d408b17dd69e79ff6191eb38
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

1.

Tasks

⟦folio 37⟧

MATHEMATICAL

wrote Petya, the numbers that the computer will print according to his program will also begin to repeat periodically. So, the computer can only print decimal expansions of rational numbers. As you can see, Petino’s intention is not feasible due to the limited size of a real computer. If the number of computer memory cells were unlimited, then writing a program to calculate the root of two would not be difficult.

Exercise 10. For what sequence of numbers can you construct an automaton with no more than 100 states that can print it?

However, there are tasks that even a computer of infinite size cannot handle. Such problems are called algorithmically unsolvable. You may have already dealt with integer equations and know how difficult it can be to find a solution. This is not accidental - as Matiyasevich’s remarkable theorem shows (see «Kvant» No. 5, 1975), the problem of solving such equations is algorithmically unsolvable. However, even without resorting to the services of a computer, it is possible to demonstrate that even an automatic device capable of executing programs of any complexity and length is still not capable of solving many very simply formulated problems. The idea of ​​periodicity will help us with this again. Let's look at a very simple-looking machine - the Draftsman. He can move along a checkered sheet of paper, coloring the cells. We will depict the direction of the Draftsman's movement with an arrow. For the Draftsman, only three actions are allowed: 1. “PAINT” – paint over the cell. 2. “LEFT” – turn 90 degrees to the left around the beginning of the arrow. 3. “JUMP” – jump to the center of the adjacent cell in the direction of the arrow. In addition, the Draftsman knows how to check the condition “THE EDGE AHEAD”. At first glance, it seems that the Draftsman is even more primitive than the Minotaur: he does not even understand the “RIGHT” command. But simplicity is deceptive. To get used to the Draftsman and make sure that it is not trivial, try to cope with exercises 10–11.

CIRCLE

⟦column⟧

Programs for the Draftsman can be written in any form convenient for you, using any methods of writing branches, loops and subroutines. You just can’t force the Draftsman to carry out commands that are impossible for him (for example, “RIGHT”) and check conditions that he doesn’t understand (for example, the condition “LEFT EDGE”). And what is also very important - the Draftsman does not know how to count. It is not capable of looping with parameters or working with numeric (or any other) variables. If the reader is uncomfortable working with a program in an “arbitrary” language, then we will use BLACK BASIC: each line contains a command number and a command only of the form GOTO N (go to command number N), “PAINT,” “LEFT,” “JUMP” or a conditional jump IF EDGE, THEN GOTO N. And if there is no transition, then the command with the next number will be executed next.

Exercises

11. Write a program for the Draftsman, according to which he, on any sheet of paper: a) will reach the corner of the sheet, wherever we place it; b) paint all the cells of the sheet; c) will move away from the edge of the sheet if it is placed at the edge; d) determine whether he is in the corner or not, paint the corner square if he is in the corner, and remain in his original position if not. 12. Write a program for the Draftsman, according to which he, on any square sheet of paper: a) starting from the position at figure 2, draws a strip of k 2 cells if k is even, and returns to the original position without painting anything if k is odd; b*) will paint all the cells of the square, except for the cells containing its center (depending on the parity of the length of the side of the sheet, the center is one cell or four cells).

Fig. 2

⟦folio 38⟧

---
running_head:
folio:
---

To finally convince you of the non-triviality of the Draftsman, we present without proof a statement showing that the Draftsman is nothing simpler than a computer with infinite memory.

Amazing fact. Let $a_1, a_2, \dots$ be a sequence of natural numbers, and there is a program in which a computer (with infinite memory) for each n calculates $a_n$. Then there is a program for the Draftsman, according to which he, for any n, starting from position $2^n$ to figure 3, will paint a strip of $2^{a_n}$ terminals, if the sheet of paper is a color plane.

Fig. 3

For smaller exponentiations and logarithms, the draftsman can replace the computer. (This means, speaking in the strict language of logicians, that with its help you can calculate any computational function $a(n)$.)

Thus, a Draftsman, who is not at all familiar with numbers, can be taught to calculate everything that a computer with infinite memory can calculate, for example, numbers in the tenth expansion of the root of two (for more information about algorithms, see the book by V.A. Uspensky “The Post Machine”).

Nevertheless, there are very simple tasks of coloring a sheet - the main activity of the Draftsman, which he cannot learn to perform with all our and his desire. Here is an example of such a task.

Problem 13. Prove that there is no program according to which a draftsman will paint over the terminals containing the chain of the sheet on any square sheet of paper, regardless of the initial position. (It’s amazing that the Draftsman can paint over all the terminals, except for the main terminals.)

Solution. It is clear that for a sheet of given sizes the required programs must be written down several times. This means that the whole point is that you need to create a program ready for any number of sheets of paper.

Let's imagine a short program to determine 1000 lines, and a very large sheet of paper, say, several hundred thousand cells. And so the Draftsman stood in the corner of the sheet and hit the road, guided by our program. A lot of time will pass before he reaches the center and paints the cell there. Before this, he will have to walk for a long time away from the edges of the sheet. How does the Draftsman behave away from the edge? To understand this, let’s assume that the sheet has no edges at all—the sheet is infinite.

Maybe then the Draftsman moves periodically? Our experience says that as the state of the Draftsman we must take the place of the program line being executed at the moment and the orientation of the Draftsman on the plane (one of four: up, down, right, left). If the number of lines in the program is n, then the possible state is $4n$. We will change the time in such program work. You can, of course, use the periodicity theorem, but we will still study the Draftsman.

Now let the state repeat at moments of time $T, T + \Delta T$. (We can assume that $\Delta T < 4n$. Why?) During this time, the Draftsman will syndicate to the vector $a$, and in the future for each period of time $\Delta T$ he will syndicate to this vector. The movement of the Draftsman, if viewed from a bird's eye view, is like a body on which no external forces act - “straightforward and uniform,” i.e. it moves along a straight line, deviating from it to a limited distance and drawing a periodically repeating pattern.

Exercise 13. a) Show that any periodic motion is possible along a straight line with a rational angle of inclination.

6) What is the size of a square that can be drawn using a program consisting of n statements? Note. Let the internal state of the Draftsman be only a place in the program.

c) Show that if the Draftsman goes “to infinity”, then both his internal state and orientation repeat with period $\Delta T < n$.

The movement of the Draftsman resembles the behavior of an elementary particle. If it arrives on a sheet of paper “from a bird’s eye view”

⟦folio 39⟧

---
running_head:
folio:
---

flight", then we see what we saw from the edge
leaf (or along the edge) it can move
in a finite number of ways. In the event of a “collision”
neither" with a wall or corner will occur "dis-
haying", and from one method of movement, according to
some law, the draftsman proceeds to
another method of movement (depending
from what it collides with - a wall or
angle, orientation, and also “phase” –
in what internal state it will collide).
An amazing fact tells us about the unlimited difficulty of multiple scattering problems.

Exercise 14 (another proof of the periodicity of the Draftsman's movement). Prove that a program for a Draftsman working on an unlimited sheet of paper can be rewritten in such a way that the Draftsman's behavior does not change, and there is only one command to go to another line (at the end of the program).

Note. Replace all transition conditions with unconditional ones (why can this be done?), then designate the lines of the program containing the commands “LEFT”, “JUMP”, “PAINT” with dots, and with arrows - which next command is executed. What is the path along the arrows?

As you can see, away from the edges of the sheet, the Draftsman is no smarter than the Minotaur, only the presence of the edges makes him comparable to a computer. Freedom is not always good!

Let's return to the solution to Problem 13. We can conclude: far from the edges of the sheet, the Draftsman moves periodically with a period and pre-period not exceeding the length of the program. Therefore the pre-period will end long before the Draftsman has to reach the center. Having reached the center, he must execute the command “PAINT”. This means that this command is included in the period, and the Draftsman had to execute it many times on the way to the center of the sheet.

Exercise 15. The given solution to problem 13 is not entirely clear, “smooth out” it. Namely: let the program for the Draftsman contain $n$ lines. Estimate the size of the sheet of paper that needs to be taken so that the Draftsman cannot paint only the central cells.

Perhaps here you (like me at first) had doubts about an amazing fact. After all, if the number $n$ is very large, then, for example, in the process of transition from $2^n$ to $2^{n^2}$ the Draftsman will have to go off the edge many times, and then two states are necessarily repeated for him, a period begins, and the Draftsman cannot stop. Let's clarify these messages. By the transition from the number $k$ to the number $l$ we will understand the transition from a position on the edge at a distance of $k$ from the vertex of the corner to a position on the edge at a distance of $l$ from the vertex. We will define the “state at the edge” as follows: first, we take into account the number of the command being executed in the program and the orientation on the plane. Of course, this is not enough: after reflection, the Draftsman can come to another wall in different “phases”, i.e. in an arbitrary place in the period of “internal states”. Therefore, in understandable states we will also include the remainder of dividing the distance to the vertex of the corner by the common multiple of all possible periods of sequences of internal states when the Draftsman moves along an unlimited plane (for example, by $k!$, where $k$ is the number of commands in the program).

Now the repetition of two bleibt states is followed by not only the same “departure” from the wall, but also the same “arrival” to the other wall (why?).

If you yourself find an error in the previous reasoning, the amazing fact becomes more clear to you.

Let's try to explain it in general terms.

First of all, by moving along a straight line with a rational angle of inclination (see Exercise 12,a), you can move from the number $2x$ to the number $3x$, $5x$, etc. (show how). In addition, you can IMIT check the distance to a vertex for parity (see Exercise 10,a), as well as divisibility by $3,5,7$, etc.

figure 4 shows block diagrams of algorithms for moving from $2^n$ corresponding to $3^n$ and $2^{2^n}$. Of course, these flowcharts still need to be written out in detail to be understood by the Draftsman.

Problem 14*. a) Do this. b) Draw a similar block diagram for the transition from the number $2^n$ to the $n$th decimal digit of the root two decimal expansion. (If the flow diagram for a certain procedure has already been violated, then it can be further denoted by one action.)

An amazing fact is explained by the fact that the indexes used by the computer can be

⟦folio 40⟧

KVA NT 2024/No.3

⟦column⟧

The adjective “model” is not accidental - it is very similar to what natural scientists do, discarding part of the properties of a natural phenomenon in order to make it visible. Frequently encountered ideas, “standard reasoning” (for example, the Dirichlet principle, cyclicity) can also be looked at as models of situations. These models are so schematic that they look trivial, but knowing such “trivialities” makes life much easier.

Exercises

16. Let’s assume that the Draftsman can not only paint, but also erase paint from a painted cell (say, using the “ERASE” command). a) Write a program for the Draftsman, according to which he will paint the central cells and only them. b) Prove that it is impossible to create a program for the “erasing” Draftsman, according to which he will draw a system of nested squares (Fig. 5) on any square sheet of paper.

⟦figure⟧

Fig. 4

but model using exponents for prime numbers - where there is one index, there are many. From this fact one can extract the algorithmic undecidability of a number of statements - for example, the already mentioned Matiyasevich theorem. You've seen how the idea of ​​cycling works. Although it looks quite simple, problems in which this idea is the main one are not always easy. What's the matter here? It turns out that even very simple key ideas are good to know in advance, otherwise they will be difficult to discover among other ideas and technical complexities. If the key idea is unknown, and technical difficulties are present, then the idea must be “extracted”, but not directly, but with the help of other tasks. After all, the problem does not exist on its own, but surrounded by related ones (even to solve the “single-cell” problem 1 it was necessary to consider the last digits of all powers of two). Therefore, they study problems that are ideologically related to this one (this is how the solution to problem 13 about the center of a square was invented). Often, for this purpose, the most important special cases or other model problems are considered, in which the difficulties are present in a “weakened form” and there are fewer technical difficulties.

⟦figure⟧

Fig. 5

17. Write interpreters for the Minotaur and Draftsman languages.

Generalization of the idea of ​​cyclicity

Generalizations of the idea of ​​cyclicity are common. We saw how this idea works in the “discrete” case, when we became acquainted with only some applications of the idea of ​​cyclicity, and with the “discrete” case when the number of states is finite. But even in the “continuous” case, with an infinite number of states, periodicity or, more accurately, “almost periodicity” often arises, when states are not repeated absolutely exactly, but only approximately. So, every summer is both similar and different from the previous one. The ancients thought about this, and we will tell you another time. Let's look at a typical example.

⟦folio 41⟧

---
running_head:
folio:
---

Task 15. On a round stadium (the length of the bulb is 1 stage) we jump Centavar. The width of his jump, m.e. The arc along which it constantly shifts is constant and equal to a. Prove that the Centavar will come as close as possible to its initial position.

Solution. The state of Centavar is, of course, the place where he stands, i.e. point on a circle. The number of states is infinite, and exact repetition of states is not necessary. (There will be no repetition, for example, if a is irrational.)
What does the Dirichlet principle provide in this case? Repetitions of states with any precision are called “almost repetitions.”
Let's look at this in more detail. Let the Centavar make n jumps. Let us mark each position of the Centavar with a point; these n + 1 points divide the circle into n segments, some of which have a length of no more than 1/n. The conditions “almost repeated themselves.”
Each state determines both the subsequent and the previous one; I would like to apply the idea of ​​“reverse motion”, however...

An unpleasant example. Bloxa jump along the segment [0; 1]. If she is now at point X, then with the next jump she ends up at point X². There is an “almost repetition”, a return to mute.
The reason is that although for some n both the i-e and (n + i)-th states are close, the degree of closeness depends on n and i. If the reverse motion is applied to them n times, then they can disperse.
In the Centavar problem, however, this does not happen, since the distance between two states is the same as between the next ones and between the previous ones.

Exercise 18. Complete the proof. Prove also that in no later than n jumps the Centaur will return to a distance no more than 1/n from the starting point.

Problem 16. If a is irrational, then Centavar will sooner or later end up on any arc of a circle. Prove it.

Note. If in n jumps the Centavar turns to a small arc ε, then in k · n jumps he turns to k · ε, and since a is irrational, then ε can be small, different from 0.

What if two centaurs are jumping (each has its own jump length)? When will both be less than 1/n away from the starting position? This wait is no longer than n² seconds (the jump is done in 1 second). Here the state is a pair of points on a circle. Let us show that among n² + 1 states there are two close ones, i.e. The positions of the corresponding centaurs differ by no more than 1/n.

Let us depict the state of a pair of centaurs as a point of a single square. The x coordinate means the position of the first, the y coordinate means the second. Square points whose coordinates differ by an integer represent the same state. (What are these dots?)

Let's divide the square into n² squares, each with a side of 1/n. Then some 2 points from n² + 1 marked ones will fall into one square. They will depict close states for which the positions of the corresponding centaurs differ by no more than 1/n.

Exercise 19. Complete the proof.

Problem 17. Distance of chance from the centaurs. Prove that no later than in n² seconds all centavarras will be at a distance of no more than 1/n from the initial position at the same time. (In the beginning, all the centawarra are in one place.)

Interestingly, the (actually discrete) case of a rational jump for one centaur is equivalent to the statement that an arithmetic progression with a rational step, passing through 0, contains infinitely many integers. It is natural to expect that an arbitrary arithmetic progression passing through 0 will come arbitrarily close to an integer.

Tasks

18. a) Prove that for any real number a there are integers p and q such that |p·a - q| < 1/q (or, what is the same, |a - p/q| < 1/q²), so the fraction p/q is “well approximated” by a.

b*) Show that for any numbers a(i), i = 1, ..., n, there are also p and q, such that |p·a(i) - q| < (1/q)¹/n for all i = 1, ..., n.

Note. The state of a number a·q is its fractional part.

⟦folio 42⟧

KVANT 2024/№3

19**. Let a be an irrational number and b an arbitrary number from the interval 0; 1, q m is the minimum of the fractional part n a, where $n <^{m}$ is an integer. Similarly, r m is the minimum of fractional $части^{b} n ^{a}$. Prove that q m! r m for infinite $многих^{m.} 20.$ a) Prove that numbers divisible by 2 can be as close as you like to numbers $вида^{n} 1 2$, where n is a natural number. b*) Prove that a power of two can begin with any number of nines. Note. Take the base 10 logarithm of the inequality $0,9^{…} 9$ $10^{k} 2^{l} 10^{k}$. Use the irrationality of log 2. c*) What is the probability of a randomly chosen power of two starting with one? d*) Prove that there is n such that the numbers $2^{n}$ and $3^{n}$ simultaneously begin with the digits $1000...^{21*.}$ Let the mapping F take the unit square K into itself and preserve the area of ​​each of its subsets. Prove that for any subset of the square U whose area is greater than zero, there is a point x from U such that for some $n > 0 точка^{F} …^{x}$ ... (n times) also belongs to U. A somewhat more general statement is called Poincaré's recurrence theorem. This theorem leads to a somewhat unexpected conclusion: if you open a bottle of perfume in a sealed room, then almost certainly after some time all the molecules of the odorous substance will gather in the bottle again (though “some” time is much longer than the lifetime of the Universe). The proof of this fact is reminiscent of the reasoning in problems about a herd of minotaurs or centaurs: the position of all molecules is described in approximately the same way by a point in state space (phase space), the return is established using Poincaré's theorem. Often the reason for periodicity in nature is that if the set of states is limited, then two states will “almost repeat” and will remain close for some time. The ancients thought about this. We will end this article on the return by returning to Ecclesiastes: “The sun rises, and the sun sets, and hastens to its place where it rises. The wind goes to the south, and goes to the north, spins, spins as it goes, and the wind returns in circles

⟦column⟧

their. All rivers flow into the sea, but the sea does not overflow; to the place from which the rivers flow they return to flow again... What has been is what will be; and what has been done will be done, and there is nothing new under the sun.”

* * * Here are a few more problems on the topics discussed.

1*. Is the function y cos $x cos^{5} 2 x cos^{5} 4x cos^{5} 8x$ periodic?

2. Can the sum of two periodic functions with smallest periods 1 and 2 be a periodic function again? 3**. General statement: let $a_{1}$, … $, a_{n}$ – real numbers such that none of them can be expressed in terms of others using a linear combination with rational coefficients. Then for any set $0 b_{i} 1$ and any H! 0 there is an L such that for all i the inequality L a i b i H is true (for a randomly chosen L this holds with probability $H^{n} ). 4.$ Checked paper is given. Parallel lines are drawn through two nodes. Prove that the resulting closed strip contains infinitely many grid nodes. 5. a) Prove that if the radius of a circle tends to infinity, then the distance from it to the nearest integer point tends to zero. b) The ratio of the number of integer points falling on a circle to its radius also tends to zero. 6. Five scientists walk along the corridor of the MIMINO Institute, reaching the end of the corridor, each turns back. While the Chief goes through the corridor once, the Lead goes through twice, the Senior - three, the Middle - five, the Junior - seven times. Prove that there is a moment when they all move towards the same end. 7. Explicitly indicate such a power of five that in its decimal notation there will be more than 1000 zeros in a row. And such that there is a combination of exactly 1000 zeros in a row? 8. Prove that there is a power of three that begins with the same 1000 digits as it ends. 9. Given two straight lines forming an angle M. A point M is taken on one and a flea sits at this point and jumps from one line to another exactly 1 cm, and always to a point different from the previous one. Prove that if the flea is back at the starting point, then the number M S is rational. 10. If the cosine of an angle is 1 3, then its degree measure is irrational. Prove it. Summarize the problem.
