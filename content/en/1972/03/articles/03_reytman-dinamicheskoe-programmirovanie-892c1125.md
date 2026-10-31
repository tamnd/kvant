---
id: 1972-3-reytman-dinamicheskoe-programmirovanie-892c1125
issue: kvant_1972_3
year: 1972
number: "3"
title: Dynamic programming
authors:
  - Рейтман М. И.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6, 8, 10, 11, 12
tag: QZQV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 976195e087af03e801d7798032c374c01a53df22ba10fdb876c1e0dbe08b6e79
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/03_reytman-dinamicheskoe-programmirovanie-892c1125.md
source_content_sha256: e9d03df10ffda295c867aea6e7da4957c9aa039af0450cb516cd062a39b09750
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

DYNAMIC
PROGRAMMING

Pharaoh's staircase

The pharaoh's palace was famous for its Russian style: pearl curtains, walls decorated with amber, gold dishes - there's just so much to list. But what struck most of all those who were allowed into the throne room of the palace was the golden staircase that led to the throne. What this staircase looked like in cross-section, if you convert the ancient Egyptian measures into actual ones, you can see on figure 1.
Archaeologists did not have to rack their brains for long to understand that the steps of the staircase were so low, everything was explained simply: the presented pharaoh did not want his subjects to see how hard it was for him to climb to the throne, they could lose respect, and who knows how this could end?
It was then that he ordered the leading jewelers to make a staircase with such low steps, no higher than 1.5 inches.
But time passed, and the old pharaoh died. His young son took over the kingdom.
The young pharaoh had heard before how the courtiers took turns at his father’s naive cunning. And although he himself soared to the throne, jumping three steps, the rumors continued. And the young pharaoh decided to put an end to him by building up the ladder. To do this, he called the court jewelers and the treasurer and told them:
- Listen to me! I command you to build the ladder so that it has at most four steps. Arrange them wherever you want, but make sure there are no more than four of them!
“But sir,” the treasurer timidly stepped forward, “where did you get so much gold?” Here I pinned it on a piece of paprius (and the treasurer showed what is shown on the figure staircase with a dotted line). The staircase is 1 m wide, or 10 dm. This means that to increase it you will need [3×1.5+1.2×(5+1)+1×1+1×3+0.8(3+4)+1.2×11]×10 = 345 dm³ of gold! Alas, sir, so much will not be found in our treasury, devastated by the war with Efyupne.
- Despicable! You cast a shadow on my power! If in 7 days the ladder is not ready, I myself will drown you in the Holy Nile, and the jewelers will be sold at work. And don’t think about meddling with your stupid drawings again!
The dejected treasurer left the pharaoh and fell back to his friend. There was no more skillful person when it came to planning a paradise or calculating land allotments. Although the friend was the priest of the capital’s temple, he was heard to be a prudent and practical man. Having learned about the trouble, he asked:
— How much gold is left in the treasury?
- 200 dm³.
- Not too much! Or maybe you can get by with less if you plan the steps differently?

⟦folio 8⟧

increase either the second or the first step, and the min sign indicates that you need to take the smallest of them. Let us substitute the values ​​$f_1(1)$ and $f_1(2)$ into brackets, found to be equal:
$$f_2(3) = \min\{(0+0,7\times4), (4,5+0)\} = 2,8.$$
Now it is already clear that if there are only three steps in the leaf, and their number needs to be reduced to two, then the second step needs to be increased.
— What if there were 4 steps?
- Then
$$f_2(4) = \min\{(f_1(1) + 0,7\times4 + 1\times(4+1)), (f_1(2) + 1\times1), (f_1(3) + 0)\} = \min\{(0+7,8), (4,5+1), (9,4+0)\} = 5,5$$
that is, if there were 4 steps in the leaf, and we replace them with two, then the first one will best finish on the second old one (Fig. 4).
“Wait, I want to make sure I understand,” the first is his treasurer. - So, to find $f_2(5)$, you need to act like this:
$$f_2(5) = \min\{(0+7,8+1,2\times(4+1+5)), (4,5+1\times1+1,2\times(1+5)), (9,4+1,2\times5), (17,4)\} = \min\{(19,8), (12,7), (15,4), (17,4)\} = 12,7.$$
“The question is, the wise ones look after the state treasury,” they used.

Fig. 2.
8

priest. - And then
$$f_2(6) = \min\{(0+19,8 + 1\times(4+1+5)), (4,5+8,2+1\times(1+5+3)), (9,4+1,2\times5+8), (17,4+1\times3), (33+0)\} = \min\{(0+32,8), (4,5+17,2), (9,4+14,0), (17,4+3), (33+0)\} = \min\{(32,8), (21,7), (23,4), (20,4), 33\} = 20,4.$$
We could go on and find $f_2(7)$, but this is not necessary, as you will soon see. Let us now move on to the case when the ladder is replaced by three steps.
Let's start by finding $f_3(4)$, that is, the most reasonable option for increasing the first four steps. After all, $f_3(1)$ and $f_3(2)$ are meaningless (you shouldn’t replace one or two steps with a tray), and $f_3(3)=0$ - increasing three steps to three does not require any consumption of gold. To find $f_3(4)$, let's look at where the second rung might end. Of course, either on the 2nd or 3rd old one. Means,
$$f_3(4) = \min\{f_2(2)+1\times1), (f_2(3)+0)\} = \min\{0+1), (2,8+0)\} = 1.$$
Therefore, building up 4 steps so that there are 3 of them, you need to complete a new second step.

⟦folio 10⟧

actions - addition and multiplication (except for a certain fee to the priest, where subtraction was required), and they were well known in Ancient Egypt. Well, a little more common sense is used. Meanwhile, a mathematical apparatus is used here that became widespread only about twenty years ago; it's called dynamic programming.

Let's think about why we were able to find the optimal solution without considering all the possible options for building a staircase (and there are a lot of them, and the priest really wouldn’t have enough time to study them completely). The fact is that at each step we break the general problem into a number of simpler ones.

Let it be necessary to build up a staircase that has $N$ steps, so that it has $n$, where $N \gg n$, that is, $N$ is much larger than $n$. Let us assume that we already know the optimal distribution of steps when there are $j$ in the new staircase, where $j \leq n$. Let $S_j$ be the number of the old steps on which the $j$th new one ends. Obviously, this $j$th step begins on the $(S_{j-1}+1)$th old one. The additional area of ​​the staircase, shown in figure 6 by hatching, will depend on $S_{j-1}$ and $S_j$, that is, on where the $j$th step begins and ends; let's denote it by $g(S_{j-1}, S_j)$. Let $f_j(S_j)$ be the minimum area for a staircase of $S_j$ steps replaced by $j$ steps, and $f_{j-1}(S_{j-1})$ be the minimum area of ​​a staircase of $S_{j-1}$ steps replaced by $j-1$ steps. Let us establish the relationship between these quantities, that is, we will find such values ​​of the variables $S_j$ that give the smallest value of the additional area:

$$g(S_1, S_2) + g(S_2, S_3) + \dots + g(S_{n-1}, S_n), \quad S_n = N.$$

Let's introduce the function

$$f_j(S_j) = \min \left[ g(S_1, S_2) + \dots + g(S_{j-1}, S_j) \right],$$

where $j=1, 2, \dots, n$. Note that $g(S_{j-1}, S_j)$ is independent of $S_1, \dots, S_{j-2}$. Therefore, $g(S_{j-1}, S_j)$ can be taken out as a sign of minimization along $S_1, S_2, \dots, S_{j-2}$ (similar to how paraboly can be taken along the $OY$ axis - the lowest point of paraboly will not change from this):

$$f_j(S_j) = \min \left\{ g(S_{j-1}, S_j) + \min \left[ g(S_1, S_2), \dots, g(S_{j-2}, S_{j-1}) \right] \right\}.$$

But we denoted the second term in the formula in brackets by $f_{j-1}(S_{j-1})$. From here we get

$$f_f(S_f) = \min \left\{ g(S_{j-1}, S_f) + f_{j-1}(S_{j-1}) \right\}.$$

This is R. Bellan's equation, which underlies dynamic programming. Capacity in carrying out numerical calculations, and you will see that we get them

⟦folio 11⟧

At every step. It should be understood as follows: to find the minimum, one should assign $S_j$ all possible values, starting from 1, and for each, find and fill in the value $S_{j-1}$, which delivers the smallest value $f_j(S_j)$. And then, working until the last value $j=n$, you need to “back away” and go back and find all the optimal values ​​$S_j$.

Introduction to the method and a little history

Let us pay attention to the fact that in the described method no conditions are imposed on the form of the function $g(S_{j-1}, S_j)$. In this way, dynamic programming differs favorably from linear programming *), in which it is required that all the dependencies under consideration be linear and the variables change continuously. Therefore, R. Bellan's equation and the above method were now used very widely. But, of course, not to satisfy the whims of the pharaohs. Without it, try to find the optimal match for the weights of the stages of a space rocket, determine the best principle for unifying parts, and build a schedule that would have the least amount of downtime! You will find yourself in a desperate position as a treasurer, overwhelmed by the abundance of possible options. Of course, using dynamic programming, you can almost

*) See, for example, the article: A. V. Katok, Economics and linear inequalities, «Kvant» No. 3, 4, 1971.

they don't count. This method is well suited for calculation on electronic computers; the method is easy to program and does not contain any “pitfalls” that, unfortunately, are found in linear programming.

The idea of ​​the dynamic programming method has been around for a long time. To some extent, it was also used by C. Maclaurin (1698-1746). However, it finally took shape in the works of the American mathematician R. Bellan and is associated with his name.

Here we have shown the application of dynamic programming to a simple scale problem. The thought immediately arises: how applicable is this method to more complex problems? It must be answered with some caution. The fact is that this creates a specification difficulty, which was called the “curse of dimensionality.” You have to try so many different possibilities and remember so many results that the method loses its positive features.

Another application

The sounds of life either grew threateningly or moved away, but it was clear that everything was final. In his absence, the pharaoh sat in front of his shagar, surrounded by dejected courtiers. A bloody messenger ran up staggering:

- Sovereign! Nomad reinforcements are approaching! We are dying!

- We'll have to retreat. We need to see how to cross it,” the pharaoh squeezed out with a groan, his eyes on the map. - But which way should we go? Tell me! “You are skilled in calculations and have already helped me once,” he turned to the treasurer.

- Oh, Osiris! - exclaimed the treasurer. - But that was a completely different task! Now ask your commanders!

- I don't believe them. These fools predicted victory for me.

“Now I’m lost,” thought the treasurer, peering at the map (Fig. 7).

⟦folio 12⟧

Fig. 7. The names of the points are replaced by numbers in circles, and the numbers between them show the length of the transitions in days.

Suddenly it dawned on him: “But the priest’s thinking can be used here too!”

Let's first consider the path from battle site 1 to the nearest points 2, 3 and 4, the numbers of which we will write in each circle on the left (Fig. 8), and on the right we will show the length of the path (in red). For example, it takes 8 days to reach point 4.

Now consider the entire path from points 2, 3, 4, without paying attention to point 1 (Fig. 9). Some paths have already led to the goal. So, in paragraph 5 two ways were given. Let's leave the best of them (it took 18 days), and exclude the worst by marking it with a minus sign. At the same time, we eliminate the path to point 7 (it took 21 days), to point 6 (it took 24 days) and to point 2 (at the first step we had the best path in 2 days). There are only 3 points left to check: 3, 4, 5.

Analysis of Figure 10 shows that the best path takes 16 days and leads through points 2, 3, 5.

Note that at the last stage the treasurer was no longer interested in how the army got to points 3, 4 (compare with the ladder problem!). That is, the best further path does not depend on how we ended up at any point. This general rule is called the “optimality reason” and is the basis of Dianic programming.

Exercises

1. For the school workshop, we first decided to buy 9 different lathes with a cost of 10, 20, 40, 60, 75, 100, 130, 160,
