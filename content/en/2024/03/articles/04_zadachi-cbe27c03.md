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
page_labels: 37, 40, 42
tag: DS90
lang: en
source: kvant_digital
extraction: native
content_sha256: 732338f4e29f0ced224e08f67406266abb827af719c41b855f09a9e1871d82e9
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/04_zadachi-cbe27c03.md
source_content_sha256: 3b101c1355182fdecea6e522ff421766dcf93258dbfa4979604673c9269f3707
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

"QUANT" FOR JUNIOR SCHOOLCHILDREN

⟦column⟧

3.

The electronic clock shows the time from 00:00 to 23:59. The train departed in the morning when the clock showed the time $^{ab}$ $:^{cd}$, and arrived when the clock

Each cell of the table $3^{u} 3$ contains one natural number, and all nine numbers are different. It is known that you can cross out one by one shown $время^{cd} :^{ab}$. How long did the train travel if it is known that it traveled for more than 6, but less than 7 hours? N. Agakhanov such a number in each line that in each line the sums of the two remaining numbers will be equal to the same number x. You can also cross out one number in each column such that in each column the sums of the two remaining numbers will be equal to the same number y. Is it possible that x = y? A. Tereshin

2.

A checkered square $27 см^{u} 27$ cm (side length of the cell is 1 cm) was cut into 5 checkered rectangles of the same perimeter. Could it turn out that the total length of the cuts inside the square is 82 cm? Folklore

These problems were proposed at the municipal stage of the All-Russian Mathematics Olympiad in the Moscow region.

4.

There are 90 cards with numbers from 1 to 90 on the table. Two people play the following game. They take turns. In one move you can take any card from the table. The game ends when there are two cards left on the table. The second one wins if the numbers on the remaining cards differ by exactly 10. Otherwise, the first one wins. Who wins when played correctly? O. Podlipsky

Illustrations by D. Grishukova

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

⟦folio 40⟧

KVA NT 2024/No.3

⟦column⟧

The adjective “model” is not accidental - it is very similar to what natural scientists do, discarding part of the properties of a natural phenomenon in order to make it visible. Frequently encountered ideas, “standard reasoning” (for example, the Dirichlet principle, cyclicity) can also be looked at as models of situations. These models are so schematic that they look trivial, but knowing such “trivialities” makes life much easier.

Exercises

16. Let’s assume that the Draftsman can not only paint, but also erase paint from a painted cell (say, using the “ERASE” command). a) Write a program for the Draftsman, according to which he will paint the central cells and only them. b) Prove that it is impossible to create a program for the “erasing” Draftsman, according to which he will draw a system of nested squares (Fig. 5) on any square sheet of paper.

⟦figure⟧

Fig. 4

but model using exponents for prime numbers - where there is one index, there are many. From this fact we can extract the algorithmic undecidability of a number of statements - for example, the already mentioned Matiyasevich theorem. You've seen how the idea of ​​cycling works. Although it looks quite simple, problems in which this idea is the main one are not always easy. What's the matter here? It turns out that even very simple key ideas are good to know in advance, otherwise they will be difficult to discover among other ideas and technical complexities. If the key idea is unknown, and technical difficulties are present, then the idea must be “obtained”, but not directly, but with the help of other tasks. After all, the problem does not exist on its own, but surrounded by related ones (even to solve the “single-cell” problem 1 it was necessary to consider the last digits of all powers of two). Therefore, they study problems that are ideologically related to this one (this is how the solution to problem 13 about the center of a square was invented). Often, for this purpose, the most important special cases or other model problems are considered, in which the difficulties are present in a “weakened form” and there are fewer technical difficulties.

⟦figure⟧

Fig. 5

17. Write interpreters for the Minotaur and Draftsman languages.

Generalization of the idea of ​​cyclicity

Generalizations of the idea of ​​cyclicity are common. We saw how this idea works in the “discrete” case, when we became acquainted with only some applications of the idea of ​​cyclicity, and with the “discrete” case when the number of states is finite. But even in the “continuous” case, with an infinite number of states, periodicity or, more accurately, “almost periodicity” often arises, when states are not repeated absolutely exactly, but only approximately. So, every summer is both similar and different from the previous one. The ancients thought about this, and we will tell you another time. Let's look at a typical example.

⟦folio 42⟧

KVANT 2024/№3

19**. Let a be an irrational number and b an arbitrary number from the interval 0; 1, q m is the minimum of the fractional part n a, where $n <^{m}$ is an integer. Similarly, r m is the minimum of fractional $части^{b} n ^{a}$. Prove that q m! r m for infinite $многих^{m.} 20.$ a) Prove that numbers divisible by 2 can be as close as you like to numbers $вида^{n} 1 2$, where n is a natural number. b*) Prove that a power of two can begin with any number of nines. Note. Take the base 10 logarithm of the inequality $0,9^{…} 9$ $10^{k} 2^{l} 10^{k}$. Use the irrationality of log 2. c*) What is the probability of a randomly chosen power of two starting with one? d*) Prove that there is n such that the numbers $2^{n}$ and $3^{n}$ simultaneously begin with the digits $1000...^{21*.}$ Let the mapping F take the unit square K into itself and preserve the area of ​​each of its subsets. Prove that for any subset of the square U whose area is greater than zero, there is a point x from U such that for some $n > 0 точка^{F} …^{x}$ ... (n times) also belongs to U. A somewhat more general statement is called Poincaré's recurrence theorem. This theorem leads to a somewhat unexpected conclusion: if you open a bottle of perfume in a sealed room, then almost certainly after some time all the molecules of the odorous substance will gather in the bottle again (though “some” time is much longer than the lifetime of the Universe). The proof of this fact is reminiscent of the reasoning in problems about a herd of minotaurs or centaurs: the position of all molecules is described in approximately the same way by a point in state space (phase space), the return is established using Poincaré's theorem. Often the reason for periodicity in nature is that if the set of states is limited, then two states will “almost repeat” and will remain close for some time. The ancients thought about this. We will end this article on the return by returning to Ecclesiastes: “The sun rises, and the sun sets, and hastens to its place where it rises. The wind goes to the south, and goes to the north, spins, spins as it goes, and the wind returns in circles

⟦column⟧

their. All rivers flow into the sea, but the sea does not overflow; to the place from which the rivers flow they return to flow again... What has been is what will be; and what has been done will be done, and there is nothing new under the sun.”

* * * Here are a few more problems on the topics discussed.

1*. Is the function y cos $x cos^{5} 2 x cos^{5} 4x cos^{5} 8x$ periodic?

2. Can the sum of two periodic functions with smallest periods 1 and 2 be a periodic function again? 3**. General statement: let $a_{1}$, … $, a_{n}$ – real numbers such that none of them can be expressed in terms of others using a linear combination with rational coefficients. Then for any set $0 b_{i} 1$ and any H! 0 there is an L such that for all i the inequality L a i b i H is true (for a randomly chosen L this holds with probability $H^{n} ). 4.$ Checked paper is given. Parallel lines are drawn through two nodes. Prove that the resulting closed strip contains infinitely many mesh nodes. 5. a) Prove that if the radius of a circle tends to infinity, then the distance from it to the nearest whole point tends to zero. b) The ratio of the number of integer points falling on a circle to its radius also tends to zero. 6. Five scientists walk along the corridor of the MIMINO Institute, reaching the end of the corridor, each turns back. While the Chief goes through the corridor once, the Lead goes through twice, the Senior - three, the Middle - five, the Junior - seven times. Prove that there is a moment when they all move towards the same end. 7. Explicitly indicate such a power of five that in its decimal notation there will be more than 1000 zeros in a row. And such that there is a combination of exactly 1000 zeros in a row? 8. Prove that there is a power of three that begins with the same 1000 digits as it ends. 9. Given two straight lines forming an angle M. A point M is taken on one and a flea sits at this point and jumps from one line to another exactly 1 cm, and always to a point different from the previous one. Prove that if the flea is back at the starting point, then the number M S is rational. 10. If the cosine of an angle is 1 3, then its degree measure is irrational. Prove it. Summarize the problem.
