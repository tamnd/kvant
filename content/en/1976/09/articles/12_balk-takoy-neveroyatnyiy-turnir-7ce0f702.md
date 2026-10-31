---
id: 1976-9-balk-takoy-neveroyatnyiy-turnir-7ce0f702
issue: kvant_1976_9
year: 1976
number: "9"
title: Such an incredible tournament...
authors:
  - Балк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 47
page_labels: 39-45
tag: 94JV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 33f0f52421556c1f40f3fffde2188bb5d1bf7d8f524b67e78883b4707f85237d
prompt_sha256: draft-1
translated_from: content/ru/1976/09/articles/12_balk-takoy-neveroyatnyiy-turnir-7ce0f702.md
source_content_sha256: 3a96ca3b55a0a233ea0b6a12ce9b89cc97e18d84224d3d437e968072a0aa1ba5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Between the first acquaintance with a “non-standard”, “non-standard” problem and the final, compact presentation of its solution lies a period of inconsistency of this solution. How to conduct this search? There is no single, “universal” method to achieve this goal. However, there are simple general techniques that help you find a way to solve this specific problem. The excellent books by D. Polya, “How to Solve a Problem,” “Mathematics and Plausible Reasoning,” “Mathematical Discovery,” as well as a number of books and articles by other authors, are devoted to discussions of such techniques. In this outline, which we bring to the attention of the reader, we will try to trace how such general techniques work.

First meeting
March 11, 8 a.m.
Every day they walked along the same quiet street - rural class student Sasha Tikhomirov and mathematics teacher Georgy Danilovich Selivanov. They had been crushing on each other for a long time, and since last year Sasha began going to the city mathematical circle, which was led by Georgy Danilovich. Today, seeing Sasha, the pointer teacher asked:
- Well, have you already sent the introductory test to the Correspondence School? After all, the deadline expires on March 20 *).
“Not yet,” answered Sasha, “out of 11 problems, I have solved 10 so far, but I can’t cache the first one.”
- What kind of insidious task is this?
Sasha took out the magazine «Kvant» No. 1 for 1974 from his briefcase, opened it to page 73 and began to read.
“Problem 1. Three friends played a certain number of games of chess, and each played the same number of games with each other. They began to decide who won. The first one said: “I have more than each of you who have done it.” The second one said: “I have less than each of you, more than each of you.” But when the points were counted, it turned out that okonven scored the most prizes (winners - 1 point, draw - 1/2 point, winners - 0). Is it possible to be a model? If not, then prove it; if yes, please give an example.”
- Interesting task! - said Selivanov. “You know, even I don’t immediately see how to solve it.” Come to me this evening, let's think about it together.

*) This refers to the Worldwide Correspondence Mathematical School (VZMS).

⟦folio 40⟧

Second meeting
March 11, 7 p.m.
Having sat down in “his” chair in Selivanov’s room, Sasha tells.

— I looked at specific cases when each of the guys played 2, 3, 4, 5 games with each of the others. But I never succeeded in the way required by the task conditions.

“But perhaps,” the teacher thought dryly, “this will work out with a larger number of games?”

“Perhaps,” Sasha sighed. — They say that someone went through 237 options for possible tours until he came across the required one. But is going over everything really the solution? Mathematics must suggest a smarter path! How can I find it? I don't even know where to start.

— You see, one of the first questions that is useful to ask yourself when solving any problem is: “What is being sought in the problem?” How would you answer it?

“Looking for...” Sasha shrugged. — We are looking for a rather untrained thing: a turir.

- Right. But here’s another important question: “Is it possible to reduce the solution to the problem to asking some numbers?”

“I think I can do it,” he said. Sasha. - To restore the vita tourir, I need to find out how many games the first one won against each of the other two, how many games he lost to each of them, how many draws he played with each of them. There are already 6 unknowns. And, better yet, unknowns must also be entered for the second and third... 18 unknowns are collected! Too much...

“Is it possible to “gather all these unknowns into one handful,” the teacher thought dryly. — It would be nice to imagine them clearly, to depict them on a diagram...

“I can do this,” said Sasha. — Recently, Kolya, Vitya, and I played two games against each other, and this is the final table we got (see Table 1). I won one game against each of them, in the table this is indicated by “+1”, and one par-game, this is indicated by “-1”. And we denoted the numerical players with an equal sign, here in the table it says “=2” - it was Kolya and Vitya who played both games. And in our problem, we can create a similar table (see Table 2), each row of which contains the information we need about the game - how many games and to whom he lost, how much he won, how much he made. True, all these numbers are unknown and are indicated by letters. For example, the second player won s games against the third player, lost f games to him, and played k games with him. A

| | Sasha | Kolya | Vitya | Total | points |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Sasha | | +1 -1 =0 | +1 -1 =0 | +2 -2 =0 | 2 |
| Kolya | +1 -1 =0 | | +0 -0 =2 | +1 -1 =2 | 2 |
| Vitya | +1 -1 =0 | +0 -0 =2 | | +1 -1 =2 | 2 |

Table 1.

Table 2.

⟦folio 41⟧

after all, it turns out that the unknowns are not 18,
but only nine!
“It’s a good scheme,” he approved.
table Georgy Danilovich, - What
what do you intend to do next?
— Match numbers $a, b, \dots, k$
so that all the conditions of the problem are fulfilled. Or maybe something like this
no set of numbers? Then how to prove it? I don't see...
- What do you know about the exceptions?
numbers? Is it possible to write this down in
in the form of an equation or inequality? Think about it at home, and let's meet tomorrow.

Meeting three
March 12, 7 p.m.
— I filled the empty cells at home
in table 2,” said Sasha, “and from
the conditions of the problem turned out to be inequalities

$$\begin{cases}
a+b>c+d, \\
a+b>e+f, \\
a+f<d+e, \\
a+f<b+c, \\
e+\frac{1}{2}h+f+\frac{1}{2}k> \\
>a+\frac{1}{2}g+b+\frac{1}{2}h, \\
e+\frac{1}{2}h+f+\frac{1}{2}k> \\
>d+\frac{1}{2}g+c+\frac{1}{2}k.
\end{cases}$$

- Is that all? - asked the teacher.
- No. If we denote by $n$ the number of games played by each
player with each of the others, then
$$a+d+g=b+e+h=c+f+k=n.$$

Moreover, all these 10 numbers are integers and
non-negative. With the help of
I managed to extract the last equalities from the inequalities $g, h$ and $k$. The result is the following system:

$$\begin{cases}
a+b-(c+d)>0, \\
a+b-(e+f)>0, \\
d+e-(a+f)>0, \\
b+c-(a+f)>0, \\
d+2e+f-(a+2b+c)>0, \\
a+2f+e-(b+2c+d)>0, \\
a+d+g=b+e+h= \\
=c+f+k=n.
\end{cases}$$

- How are you going to solve it?
- I can’t even imagine. After all
We didn’t go through this at school.
— Is it possible to reduce this problem to another, simpler one?
- What does “simpler” mean? Why is there less inequality? Or
Why are there fewer unknowns in inequalities?
- Please.
- Well, the first six lines are six inequalities with six unknowns. If we solve this system, that is, find $a, b, c, d, e, f$, then in the last equalities we can set $n$ equal to a sufficiently large natural number and find $g, h$ and $k$. This means that we only need to solve a system of six inequalities with six unknowns.
— Is it possible to simplify inequalities by introducing new unknowns?
- I'll try. The first inequality involves four unknowns. It would probably be easier to deal with only two. And the picture is similar in other inequalities. I'll put it down

$$\begin{cases}
a+b=x, \\
c+d=y, \\
e+f=z, \\
a+f=t, \\
d+e=u, \\
b+c=v.
\end{cases}$$

Then the inequalities of system (1) will become simpler:

⟦folio 42⟧

Or you can simplify it further, introduce unknowns... here, there will be only four of them:

$$\begin{cases}
x - y > 0, \\
x - z > 0, \\
u - t > 0, \\
v - t > 0, \\
z + u - (x + v) > 0, \\
z + t - (y + v) > 0.
\end{cases}$$

Or you can simplify it further, introduce unknowns... here, there will be only four of them:

$$\begin{cases}
x - y = \alpha, \\
x - z = \beta, \\
u - t = \gamma, \\
v - t = \delta,
\end{cases}$$

and then system (3) will take the form

$$\begin{cases}
\alpha > 0, \\
\beta > 0, \\
\gamma > 0, \\
\delta > 0, \\
\gamma - (\beta + \delta) > 0, \\
\alpha - (\beta + \delta) > 0.
\end{cases}$$

And to find a solution to system (5) is our request,” Sasha finished cheerfully.

- How so: a request?
- Look, Georgy Danilovich. After all, you can take any natural numbers, say ones, as the numbers β and δ, and then take slightly larger γ and α... triplets.
- Yes, you can. What's next?
— Next I will find x, y, z, u, t, v from system (4), and then from system (2) I will find a, b, c, d, e, f. Solving it is a futile matter.
“Let’s say,” said the teacher. - I would like to see what the result will be. We'll bring it in tomorrow.

Meeting four

March 15, 7 p.m.
“You see,” Sasha began with a smile, “system (4) seems to be simple, but unknowns cannot be found from it.” There are only four equations, but there are six unknowns, and they cannot be found.

— Yes, such systems are called “uncertain” because the unknown ones are not definitely found. Such systems have either infinitely many solutions or none.

- Why do I need “infinitely many”? One is enough for me. Maybe take x and t arbitrarily? Then the system can be solved?

- Well, in any case, you will have four equations and four unknowns in system (4). But will it be possible to solve system (2) after this? For now, I advise you to send solutions to the remaining 10 problems to the Correspondence Scale, because they write that it is not necessary to solve all the problems.

Fifth meeting

March 21, 7 p.m.
- Georgy Danilovich! I'm getting some nonsense!
- What's the matter?
— I put x=4, t=1. But then for β=δ=1 and α=γ=3 from system (4) we get y=1, z=3, u=4, v=2. System (2) takes the form

$$\begin{cases}
a + b = 4, \\
c + d = 1, \\
e + f = 3, \\
a + f = 1, \\
d + e = 4, \\
b + c = 2.
\end{cases}$$

I turned it this way and that, but I couldn’t decide! Then I tried to find the sum of all six unknowns. I added the first equation and got a+b+c+d+e+f=8.

And I added the last three and got a+b+c+d+e+f=7.

It wasn't like that! So the system

⟦folio 43⟧

(6) has no solutions, and the required tournament could not exist! What about saying that someone found it?

- Well, you're not entirely right. System (6) really has no solutions; but you chose x and t completely arbitrarily. Perhaps they should be selected more carefully?

- How to select them? After all, I no longer have the equation.

- Why? You have it that it should be x+y+z=t+u+v. Or maybe there are some other matches?

- How to look for such correspondences?

“How to look for them is another question.” We now need to find at least one solution to the problem. By the way, the deadline for submitting a decision to the Correspondence School has expired. I hope you sent your work?

- Yes, I sent the solutions to the ten problems. But I can’t get the problem about chess players out of my head. Of course it’s quarter time, I have to prepare for the test, but I’m only thinking about this tournament.

- Well, let's think together. Why do we need to solve system (4) for a random set of numbers x, t, α, β, γ, δ? Isn’t it better to express from it, say, y, z, u, v in terms of x, t, α, β, γ, δ, substitute them into system (2) and solve it by eliminating the unknowns? You'll be on vacation soon, you'll have plenty of time, try it. For now, put this task aside and get ready for your tests.

- Okay, I'll do that.

Meeting six

April 3, 2 p.m.

- Georgy Danilovich! “I found it,” the teacher shouted when he finished. - I solved this problem!

- And what is the answer?

- This could happen! Here is the standings (see Table 3). And, probably, it is not the only possibility.

- How did you find her?

- And I decided not to look for f at first, temporarily consider it known, and then pick it up. In addition, the equation that we found - x+y+z=t+u+v, gives after substitution (from system (4))

3x=3t+α+β+γ+δ, whence

x=t+\frac{1}{3}(\alpha+\beta+\gamma+\delta),

and it is clear that the sum in brackets must be divisible by three. And then, sequentially from the fourth, first, sixth, second and fifth equations of system (2), uses (4), I found:

$$\begin{align*}
a &= t-f, \\
b &= x-a = \frac{1}{3}(\alpha+\beta) + \gamma+\delta) + f, \\
c &= v-b = t-\frac{1}{3}(\alpha+\beta) + \gamma+\delta) - f + \delta, \\
d &= y-c = \frac{2}{3}(\alpha+\beta) + \gamma+\delta) - \alpha-\delta + f, \\
e &= u-d = t-\frac{2}{3}(\alpha+\beta) + \gamma+\delta) - f + \alpha+\delta + \gamma.
\end{align*}$$

After that, I selected natural numbers α, β, γ, δ, t, f such that the numbers a, b, c, d, e were integers and non-negative. I put α=5, β=1, γ=4, δ=2, t=10, f=2.

Table 3.

⟦folio 44⟧

And then I took $n=18$ and from the equalities of system (1) I found
$$g=7, h=1, k=10.$$
That's it!
“Yes, that’s right,” Georgy Danilovich smiled. — Only I put $n=17$ and reduced the numbers. After all, $h$ can equal zero!

“Once again - and better!”
(D. Polya)

They returned to the problem of “three chess players” a year and a half later, when they were thinking about the next lesson of the mathematical circle. Sasha was preparing a message about general techniques for finding solutions to problems. After reviewing the old solution, they thought about the following problem: to indicate a way to find sex tournaments that satisfy the conditions of Problem 1.
“This task,” Sasha noted, “is very different, equivalent to this: to indicate a way to find sex tournaments that satisfy the conditions of task (1).
“Of course,” confirmed Georgy Danilovich.
“One circumstance confuses me about our old reasoning,” Sasha continued. — We entered the auxiliary unknowns $x$, $y$ and $t$. D., and then were freed from them. What if they are immediately freed from them? Then, for example, together with the inequalities $a+b-(c+d)>0$ we immediately obtain the equality $a+b-(c+d)=\alpha$. And exactly the same with the rest of the inequalities of system (1).
“Good idea,” said the teacher. “I used it to give a compact final solution to the problem in the circle class.”
...This is the solution.
“The problem boils down to finding all possible sets of ten non-negative integers
$$a, b, c, d, e, f, g, h, k, n, (*)$$
satisfying system (1) (here Sasha explained exactly how she

Unfortunately, we are not presenting this story).
Let's write it in the form of a control system
$$\begin{cases}
a+b-c-d & =\alpha, \quad (8_1) \\
a+b & -e-f =\beta, \quad (8_2) \\
-a & +d+e-f =\gamma, \quad (8_3) \\
-a+b+c & -f =\delta, \quad (8_4) \\
-a-2b-c+d+2e+f =p, \quad (8_5) \quad (8) \\
a-b-2c-d+e+2f =q, \quad (8_6) \\
g=n-a-d, \quad (8_7) \\
h=n-b-e, \quad (8_8) \\
k=n-c-f \quad (8_9)
\end{cases}$$

and we will look for its solution in non-negative integers for natural numbers $\alpha, \beta, \gamma, \delta, p, q$. First, let's solve the system of the first six equations for $a, b, c, d, e, f$.

Adding equations (8$_2$) and (8$_4$) term by term and subtracting this sum from equation (8$_3$), we obtain
$$-a-2b-c+d+2e+f=\gamma-(\beta+\delta),$$
and subtracting this sum from equation (8$_1$), we obtain
$$a-b-2c-d+e+2f=\alpha-(\beta+\delta).$$
Comparing these two equations with (8$_5$) and (8$_6$), we see that for the compatibility of system (8) it is necessary to satisfy the equalities
$$\gamma=\beta+\delta+p, \alpha=\beta+\delta+q,$$
and then equations (8$_5$) and (8$_6$) will follow equations (8$_1$) - (8$_4$). Of these four equations, any of the six unknowns $a, b, c, d, e, f$ can be expressed as une-l in terms of the other two and free terms. Note also that from equations (8$_5$) and (8$_6$) it follows
$$-b-c+e+f=\frac{p+q}{3},$$
from which it is clear that the number $s=\frac{1}{3}(p+q)$ is a natural number, and $q<3s$, $p=3s-q$. Now let's express $a, b, d, e$ in terms of $c, f, \beta, \delta, q, s$ (excluding variables). We get

⟦folio 45⟧

$$a = c + \beta + s, \quad (9_1)$$
$$b = f + \beta + \delta + s, \quad (9_2)$$
$$d = f + \beta + 2s - q, \quad (9_3)$$
$$e = c + \beta + \delta + 2s. \quad (9_4)$$

It can be seen that $b + e > a + d > c + f$, that is, $k > g > h$. Now from equation $(8_8)$

$$n = c + f + h + 2\beta + 2\delta + 3s, \quad (9_5)$$

and from $(8_7)$ and $(8_9)$

$$g = h + 2\delta + q, \quad (9_6)$$
$$k = h + 2\beta + 2\delta + 3s. \quad (9_7)$$

So, if non-negative integer numbers (*) satisfy system (1), then there is a set of non-negative integer numbers $\beta, \delta, s, q, c, f, h$ ($\beta > 0, \delta > 0, s > 0, 0 < q < 3s, q \leqslant f + \beta + 2s, c \geqslant 0, f \geqslant 0, h \geqslant 0$) such that the numbers (*) are related to them by correspondences (9).

Conversely, it is not difficult to verify (for example, by direct substitution) that for any choice of integers $\beta, \delta, s, q, c, f, h$ satisfying the listed conditions, the numbers (*) defining formulas (9) will satisfy system (1). Consequently, for all possible such sets of “parameters” $\beta, \delta, s, q, c, f, h$, all solutions to the problem of three chess players are obtained.

“A good solution to a difficult problem,” said the teacher. - But “all ends are carefully left in the input.” How can you agree that two equations in the system are consequences of the others, that you should add the equations $(8_5)$ and $(8_6)$ and find $\frac{1}{3}(p + q)$?

“To myself,” answered Sasha, “I always had in mind the reasoning that was previously carried out when searching for a solution.” Look: now I have designated a certain expression - the left side of the fifth inequality of system (1) - as $p$; and earlier, during the search for a particular solution, I had already worked with the same expression (see (1), (3), (5)) and saw that it was equal to $\gamma - (\beta + \delta)$; that means it should be: $\gamma - (\beta + \delta) = p$.

During the solution, I show the correctness of this equality, minutes of calculation that are unnecessary for the final solution. The same is true with the equality $\alpha = \beta + \delta + q$. In addition, while searching for a solution, I came across the expression $\frac{1}{3}(\alpha + \beta + \gamma + \delta)$ (see (7)), which should be a natural number. But this expression is equal to $\beta + \delta + \frac{1}{3}(p + q)$. So $\frac{1}{3}(p + q)$ must be an integer. And in order to show this during the final solution, I added the equalities $(8_5)$ and $(8_6)$ term by term.

- Well, why did you choose $f$ and $c$ as “free variables”, and not, say, $a$ and $b$?

— I had before my eyes system (7), obtained during the search: if it frees itself from the extra variable $t$ (for example, take into account that $t = a + f$, and put this expression in the remaining equalities (7)), then it is immediately clear that it is convenient to choose $f$ and $c$ as “free variables”.

* *

Looking back at Sasha’s Japanese survey, we can highlight the following questions:

1. “What are you looking for in the problem?”
2. “Is it possible to reduce the problem to asking some numbers?”
3. “What is known from the formulation of the problem of exceptions? Could this be written in the form of an equation or inequality?
4. “Is it possible to reduce this problem to another, simpler one?”
5. “Is it possible to improve the solution (get a simpler or more compact solution, solve a more general problem, etc.)?”

Questions to Consider

1. What is the minimum number of games that each of the three chess players must play in a trinaire so that they can fulfill the conditions of task 1?
2. Are there any extra conditions in problem 1?
