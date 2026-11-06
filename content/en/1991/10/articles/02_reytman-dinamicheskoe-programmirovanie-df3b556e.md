---
id: 1991-10-reytman-dinamicheskoe-programmirovanie-df3b556e
issue: kvant_1991_10
year: 1991
number: "10"
title: Dynamic programming
authors:
  - Рейтман М. И.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
lang: en
source: kvant_digital
extraction: vision
content_sha256: ca618b40de49b7dbc3d228cf44b68db42a65a97ad14c442b41476aaaf35d6021
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/02_reytman-dinamicheskoe-programmirovanie-df3b556e.md
source_content_sha256: 6a951a585fede7d5f612398a730722074436cd923e403983454e261f474b18d8
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 2⟧

---
running_head:
folio:
---

DYNAMIC
PROGRAMMING

M. REITMAN

Pharaoh's staircase

The pharaoh's palace was famous for its luxury: pearl curtains, walls decorated with amber, gold dishes - there's just a list. But what struck most of all those who were allowed into the throne room of the palace was the golden staircase that led to the throne. What did this staircase look like in cross-section, if you translate the ancient Egyptian measures into actions, you will get rid of figure 1. Archaeologists did not have to rack their brains for long to understand that the steps were so low, everything was explained simply: the presented pharaoh did not want his subjects to see how difficult it was for him to climb the throne, they could lose respect, and who knows how this could end? It was then that he ordered the leading jewelers to make a staircase with such low steps, no higher than 1.5 inches.

But time passed, and the old pharaoh died. His young son took over the kingdom.

The young pharaoh had heard before how the courtiers flipped over their father’s naive cunning. And although he himself soared to the throne, belching three steps at a time, the rumors continued. And the young pharaoh decided to put an end to him by building up the ladder. To do this, he called the court jewelers and the treasurer and told them:

- Listen to me! I command you to build the staircase so that it has at most four steps. Arrange them wherever you want, but make sure there are no more than four of them!

“But sir,” the treasurer timidly stepped forward, “where did you get so much gold?” So I figured out the pashiras on a piece of paper (and the treasurer showed what is shown on the figure staircase with a dotted line). The staircase is 1 m wide, or 10 dm. This means that to build it up you will need $[3 \times 1,5 + 1,2 \times (5+1) + 1 \times 1 + 1 \times 3 + 0,8 (3 + 4) + 1,2 \times 11] \times 10 = 345$ dm$^3$ gold!

Alas, sir, that much will not be found in our treasury, devastated by the war.

Fig. 1.

⟦folio 3⟧

---
running_head:
folio:
---

- Scoundrel! You want to ruin the country! Yes, I immediately see that you haven’t always thought about saving! Look! - and the pharaoh drew a red line. - You are always ready to spend extra gold!

- O wisest of pharaohs! Indeed, you're right. But this gives a gain of only 90 dm³, and we don’t have 345-90 = 255 dm³ either.

- Despicable! You cast a shadow on my power! If in 7 days the ladder is not ready, I myself will drown you in the connected Nile, and the jewelers will be sold at work. And don’t think about meddling with your stupid drawings again!

Dejected, the treasurer left the pharaoh and went to his friend. There was no more skillful person when it was necessary to plan a primada or calculate land allotments. Although the friend was the custodian of the capital’s temple, he was considered a prudent and practical man. Having learned about the trouble, he asked:

— How much gold is left in the treasury?
- 200 dm³.
- Not too much! Or maybe you can get by with fewer steps if you plan the steps differently?

“I tried,” the treasurer sighed, “but there are so many options, and time is running out.”

“Okay, friend,” said the priest. “Let me think about it, and come tomorrow.”

When the grief-stricken treasurer approached the priest the next day, he greeted him with a satisfied smile.

- Tell me, friend, can I count on the remaining gold if I get by with less?

- Oh rich! - exclaimed the treasurer, not believing his luck. - You received another dozhnaya work and so many measures of grain!

- So look! - and the priest handed him a sheet of parius, where there was another project for building a staircase. - This project requires only 171 dm³ of gold. And the remaining 29 dm³ are mine!

- But tell me, O greatest of computing, how did you find such an option? I tried this and that, but it didn’t work for me!

“Listen,” prayed the priest. “First, I examined the case when staircases of different numbers of steps are replaced by just one step.” To make the numbers simpler, I will only calculate the area f of the figure between the solid and dotted lines, and add a constant factor, the width of the stairs, later. Not returning? If the original staircase consisted of only one step, then there would be nothing to build up:

$$f_1(1)=0.$$
Formula
$$f_1(2)=1,5\times 3=4,5$$

shows that if the first two steps of the pharaoh's ladder are replaced by one step, 4.5 dm² is required. We can similarly find
$$f_1(3)=1,5\times 3+0,7\times (3+4)=9,4.$$
Well, then
$$f_1(4)=9,4+1\times (3+4+1)=17,4,$$
$$f_1(5)=17,4+1,2\times (3+4+1+5)=33,$$
and so on.

“All this is understandable,” objected the treasurer, “but why do I need one step?” After all, Pharaoh asked for four! And the staircase now has not five of them, but much more!

- Take your time! - the priest smiled. - Soon there will be more new steps - two (Fig. 2). But first, let’s find the area of ​​one step, which also begins on other steps of the first initial staircase: they are also easy to count one after another. For example, to increase the step from 2nd to 4th, you need
$$g(2,4)=2,8+1\times 5=7,8\ \text{dm}^2.$$
I wrote down all these numbers that came across in our calculations in a table that fit on one sheet of paper (Fig. 3). We have already calculated the numbers g(1,j)=f₁(j) in the “one step” column, and then it is convenient to calculate the series by charge, looking to the right and up: g(2,3), g(3,4), g(2,4),

⟦folio 4⟧

---
running_head:
folio:
---

Fig. 2. Less than all the gold is required to build up the red staircase: $f_2(4)=4,5+1=5,5$.

Fig. 3. The numbers $g(i, j)$, $1 \leq i < j \leq 9$ in the dark cells show how much gold is required for one step from the $i$th to the $j$th steps of the first ladder, and the numbers $f_k(j)$ on the left side ($k=2, 3, 4$) - what is the minimum amount of gold required from the $k$ steps up to $j$ level.

$g(2,5)$, ... Let's now calculate the minimum areas with two steps. $f_2(1)$ does not make sense; we cannot replace one step with two. To replace two steps with two new ones, you don’t have to build them up:

$$f_2(2)=0.$$

Here $f_2(3)$ is a little more difficult to calculate. Here we need to consider two options and choose the optimal one: to replace the first step with two, we must increase either the second step or the first, and $f_2(3)$ is equal to the smallest of the corresponding areas:

$$f_2(3)=\min\{g(2,3); f_1(2)\}=\min\{2,8; 4,5\}=2,8.$$

To find $f_2(4)$ you will need to find the smallest of three numbers (they are shown in different colors on Fig. 2):

$$f_2(4)=\min\{g(2,4), f_1(2)+g(3,4)\},$$

$$f_1(3)=\min\{7,8; 4,5+1; 9,4\}=5,5,$$

and so on... (All these calculations are given in the table at figure 4.)

“Wait, I figured out how to find the best two-step staircase, but a further number of options will quickly return: it’s scary to even think how many three-step staircases need to be calculated—but we need a four-step staircase!” Have you considered all the options here?

- But there is no need for this, as you will now see. For example, let's find $f_3(4)$: the smallest staircase of three steps, ending at the level of the 4th step.

⟦folio 5⟧

---
running_head:
folio:
---

$f_2(3) = \min\{2,8; 4,5\} = 2,8$
$f_2(4) = \min\{7,8; 1+4,5; 9,4\} = 5,5$
$f_2(5) = \min\{19,8; 8,2+4,5; 6+9,4; 17,4\} = 12,7$
$f_2(6) = \min\{32,4; 17,2+4,5; 14+9,4; 3+17,4; 33\} = 20,4$
$f_2(7) = \min\{46,6; 27,6+4,5; 23,6+9,4; 8,6+17,4; 3,2+33; 49\} = 26$
$f_3(4) = \min\{1; 2,8\} = 1$
$f_3(5) = \min\{0+8,2; 2,8+6; 5,5\} = 5,5$
$f_3(6) = \min\{0+17,2; 2,8+14; 5,5+3; 12,7\} = 8,5$
$f_3(7) = \min\{0+27,6; 2,8+23,6; 5,5+8,6; 12,7+3,2; 20,4\} = 14,1$
$f_3(8) = \min\{0+46; 2,8+42,8; 5,5+21,8; 12,7+12,8; 20,4+4,8; 26\} = 25,2$
$f_4(9) = \min\{0+61,8; 1+35,8; 5,5+23,8; 8,5+11,8; 14,1+3; 24,3\} = 17,1$

Fig. 4.

Let's see where its second stage may end. Of course, on the 2nd or 3rd old. But we already know which two-step staircase ends up at this level: $f_2(2) = 0$, and we have already found the area of ​​the best two-step staircase $f_2(3) = 2,8$, so

$$f_3(4) = \min\{g(3,4); f_2(3)\} = \min\{1; 2,8\} = 1.$$

“Wait, I want to make sure I understand how to find $f_3(5)$.” Of the three steps ending in the 5th, the second can end in the 2nd, 3rd or 4th old. Means,

$$f_3(5) = \min\{g(3,5); f_2(3) + g(4,5); f_2(4)\} = \min\{8,2; 2,8+6; 5,5\} = 5,5.$$

“Verily, the wise look after the treasury of the state,” user. “In the same way, you can count $f_3$ from 6, 7 and 8, and then move on to the case with four steps. Now there is no need to consider $f_4(4)$, ..., $f_4(8)$: we know for sure that the last quadruple step ends on the old ninth one (otherwise the staircase would have had more than four steps). So, all we have to do is find $f_4(9)$ at least from the sums $f_3(j) + g(j,9)$, where $j$ is one of the six numbers 3,4, ..., 8; this number is $f_3(7) + g(8,9) = 14,1 + 3 = 17,1$. This is the minimum of all four-step stairs!

This means that in total you will need $17,1 \times 10 = 171$ (dm³) gold for the stairs. Now let's figure out where the new steps should be located. Note that the optimal options are highlighted in red. The last optimal option included the cost of three new steps $f_3(7) = 14,1$; This means that the third step should end at the 7th old one. Now let's go back a step to the specific $f_3(7)$ and see that $f_3(7)$ includes the cost of the first two steps $f_2(4) = 5,5$. Consequently, the second stage must end at the 4th old one. Finally, the expression for $f_2(4)$ includes $f_1(2) = 4,5$.

This means that the first step of the new staircase must be completed on the second step of the old one. Of course, the cheapest ladder is shown at figure 5.

Fig. 5.

⟦folio 6⟧

---
running_head:
folio:
---

We do not know whether the cunning treasurer fulfilled his promise to the priest; moreover, we do not know whether the story described is a coincidence or is it fictitious. But we know that it absolutely could have happened, or in considering the problem only two arithmetic operations are used - addition and multiplication, and they were well known in Ancient Egypt (although, of course, the designations for numbers and operations that we use appeared much later). Well, a little more common sense is used. Meanwhile, a mathematical apparatus is used here, which became widespread only about forty years ago; it's called dynamic programming.

Let's think about why we were able to find the optimal solution without considering all the possible options for building a staircase (and there are a lot of them, and the priest really wouldn’t have enough time to study them completely). The fact is that at each step we divided the general problem into a number of simpler ones.

Let it be necessary to build up a staircase that has $N$ steps, so that it has $n$, where $N \gg n$, that is, $N$ is much larger than $n$. Let us assume that we already know the optimal distribution of steps when there are fewer than $n$ of them in the new staircase. Let $h_k$ be the number of the old step on which the final $k$ is the new one. Obviously, this $k$th step begins on the $(h_{k-1}+1)$th old one. Additionally, the area shown at figure 6 will be denoted by $g(h_{k-1}+1, h_k)$. The general problem is to find values ​​of $h_1, h_2, \dots, h_{k-1}$ for which the sum of $k$ quantities

$$g(1, h_1) + g(h_1+1, h_2) + \dots + g(h_{k-2}+1, h_{k-1}) + g(h_{k-1}+1, h_k)$$

(given $k=n$ and $h_k=h$) is the smallest, let us denote this smallest value by $f_n(h_n)$. Note that the sum of the first $n-1$ terms, in which $h_n$ is not included, takes the smallest value $f_{n-1}(h_{n-1})$ - this is also a problem for 1 less than the number of steps. As a result, we obtain the substitution formula of R. Bellan:

$$f_k(h_k) = \min \left\{ f_{k-1}(h_{k-1}) + g(h_{k-1}+1, h_k) \right\},$$

which allows you to sequentially find the numbers $f_k(h_k)$ (for all $k \leq n$, $h_k \leq h$) at each step. It should be understood as follows: to find the minimum, you should assign $k$ all possible values, starting from 1, and for each, find and fill in the value $h_{k-1}$, which provides the smallest value $f_k(h_k)$. And then, doit until the last value $k=n$, you need to “backtrack” and go back and find all the optimal values ​​$h_{n-1}, h_{n-2}, \dots, h_1$ (see red arrows on figure 3).

Discussion of the method and a little history

Let us pay attention to the fact that in the described method no conditions are imposed on the form of functions $g$ (in this way, dihamic programming is advantageous to differ from linear programming, in which it is required that all the considered dependencies be linear and the variables change incorrectly). The only important thing is that the function $f$, the minimum of which we

⟦folio 7⟧

---
running_head:
folio:
---

we are looking for, we can represent it as a sum of terms in which the previous one depends on a changing number of variables. Therefore, R. Bellman's equation and the described method are now used very widely. But, of course, not to satisfy the whims of the pharaohs. Without it, try to find the optimal ratio of the weights of the stages of a space rocket, determine the best prizzit for unifying parts, build a schedule in which there would be the least amount of downtime! You will clear a desperate treasurer, overwhelmed by the abundance of possible options. Of course, there is almost no calculation done manually using a dynamic program. But it is well suited for computer calculations and does not contain any “pitfalls” that, unfortunately, are found in linear programming and other methods of finding minima for functions of many variables.

The idea of ​​the dynamic program method has been around for a long time. To some extent, it was also used by C. Maclaurin (1698-1746) and even Archimedes. However, it finally took shape in the works of the American mathematician R. Bellman and is associated with his name.

We have shown here the application of a dynamic program to a very simple problem. How applicable is this method to more complex problems? This question must be answered with some caution. The fact is that this will create a specification difficulty, which was called the “curse of dimensionality.” You have to try so many different possibilities and remember so many results that the method loses its positive features. The dynamic program method gained its “second wind” thanks to the “inflammation” of calculations, which in recent years has been increasingly emphasized by programming specialists and computer designers.

Another application

One of the relatively new applications of dynamic programming is molecular biology, where “data banks” contain biological sequences (DNA, RNA, proteins) totaling many millions of “letters”, so their analysis cannot be done without computers. DNA molecules containing genetic information are long words of four letters (A, G, C, T). In the process of evolution, as a result of mutation, the sequences change: one letter may be replaced by another, dropped out, or a new one may be added. How similar are the two fragments? What is the maximum number of transformations that can be used to obtain one of them from the other? Here is the exact formulation of a problem of this type. Given two “words” (lengths m and n), consisting of the letters A, G, C, T. Find the longest subsequence included in both words. Let us describe a simple procedure, proposed in the early 70s, that solves this problem (biologists call it the Nudelman-Wunsch algorithm). Let's write one of these words - x=(X₁, X₂, ..., Xₘ) - upward, and the other - y=

C 1 2 3 4 5 6 7
T 1 2 2 3 4 5 6 7
G 1 2 2 3 4 5 6 6
G 1 2 2 3 4 5 5 5
A 1 1 2 3 4 4 4 4
T 1 1 2 3 3 4 4 4
A 1 1 2 3 3 3 3 3
C 0 1 2 2 2 2 2 2
G 0 1 1 1 1 1 1 1

Fig. 7. One of the sequences of maximum length 7: GCAGGT.

⟦folio 8⟧

---
running_head:
folio:
---

$$x = -\Gamma \zeta A T A -\Gamma \Gamma T \zeta$$
$$y = A \Gamma \zeta A -A T \Gamma \zeta$$

Fig. 8. One of the best “alignments” of two words, found at figure 7.

$= (Y_1, Y_2, \dots, Y_n)$ - from left to right next to the size table $m \times n$ (Fig. 7). Let's mark those cells of the table, in the row and column of each of which there are identical letters (in the table at figure 7 the artist painted these cells blue). Now we will fill out the table of the number $a_{ij} (i=1,2, \dots, n)$ according to the following rule: $a_{ij}$ is equal to the most of the numbers $a_{i-1,j}, a_{i,j-1}$ and (if the cell $(i,j)$ is marked!) $a_{i-1,j-1}+1$. Of course, you also need to set initial conditions. They are as follows: $a_{11}=1$, if the first letters $X_1$ and $Y_1$ of our words coincide (in this case, $a_{ij}=a_{ji}=1$ for all $i,j$); if not, then $a_{11}=a_{12}=\dots=a_{1,j-1}=0$ and $a_{1j}=\dots=a_{1n}=1$, if the first $j-1$ letters of the second word $y$ are different from $X_1$, and the $j$th letter is $Y_j=X_1$; similarly, $a_{21}=\dots=a_{i-1,1}=0$, $a_{i1}=\dots=a_{m1}=1$, if $X_i$ is the first letter of the word $x$, coincides with $Y_1$.

So, calculating each time a maximum of two or three numbers - and filling out our path, as in the pharaoh's task - we will fill out the entire table in $m \cdot n$ steps.

Check that the last number $a_{mn}$ will be equal to the length of the largest common subsequence of our two words, and this subsequence itself can be read by dividing in reverse order (sometimes it may not be the only way). Biology usually depicts the result as an “alignement” of two given words (Fig. 8). Similar fast and low-memory algorithms can be found for other similar problems: for example, replacing letters can be assigned a different “weight” than deleting (or inserting); in protein subsequences (these are words of 20 amino acid “letters”), it is reasonable to assign each pair of letters its own “weight,” reflecting the degree of their similarity (measured, for example, by the frequency of substitutions of one letter for another). The “multiple expression” task involving several words at once is also very important, but as the number of words increases, the number of necessary operations in it grows rapidly.

Exercises
1. For the school workshop, we first decided to buy 9 different lathes costing 10, 20, 40, 60, 75, 100, 130, 160, 190 rubles. Each of the subsequent machines in this row can replace any previous one, but not vice versa. For example, a machine that costs 100 rubles can process the same parts that make up a machine that costs 40 rubles. However, the school principal returned:
— Too many types of machines! It will be difficult for us to serve them - after all, we have the right words for each one. Let's buy 9 machines, but only four different types, and so that the purchased machines have no less capabilities than the original 9 machines.
— What types of machines will we take?
— Let's choose them so as to stock up for all 9 machines placed. Evgeniy Ivanovich, can you help us choose the types of machines? - he turned to the mathematics teacher.
What types of machines did the teacher suggest you choose and how much did they cost?
2. What the director proposed to do in the previous task is called unification. Obviously in practice, unification provides economic benefits. But how can this benefit be calculated?
Let there again be 9 machines on the side 16, 18, 19, 22, 23, 24, 26, 28, 33 rubles. It is necessary to compile unified series from them, as was done before, considering that combining machines in a series by simplifying maintenance results in a reduction in costs per series according to the following table:

Number of machines in series 1 2 3 4 5 6 7 8 9
Cost reduction 0 12 16 18 20 20 21 21 21

3. Additional table at figure 2 to find the most economical 5-step leaf; how much gold will it require?
