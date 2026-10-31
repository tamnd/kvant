---
id: 1972-7-sheyntsvit-vetvi-i-granitsyi-3979cb15
issue: kvant_1972_7
year: 1972
number: "7"
title: Branches and borders
authors:
  - Шейнцвит Р. П.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: UYY0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 21fca3eaa38fed93cf44efde849c2d4fccc16908e37e3cea1daebac3d56a14bd
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/03_sheyntsvit-vetvi-i-granitsyi-3979cb15.md
source_content_sha256: 84a63476d5da6d1143a407c48216cd6dd6f4ec0ec90dfca96f0ea51a5f2681a9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Let's consider the problem:
There are items in stock (such as
dy - one at a time), weight and cost
which are indicated in the table.

| Serial number | weight in cent-
nerah | Price
(in rubles) |
| :--- | :--- | :--- |
| 1 | 11 | 120 |
| 2 | 7 | 140 |
| 3 | 6 | 60 |
| 4 | 5 | 80 |
| 5 | 12 | 160 |
| 6 | 9 | 110 |
| Total | 50 | 670 |

The automatic load capacity is 3200 kk. The maximum value is required so that the total value of the items taken is as high as possible.

Obviously, it is more profitable to take items that have a low weight and a high value.

Let us introduce the concept of the unit cost of an item $d_i$, that is, the cost of one center of the $i$ item in rubles: $d_1=10,9$; $d_2=20$; $d_3=10$; $d_4=16$; $d_5=13,3$; $d_6=12,2$.

If you load an automatic machine with items with the most specific value - second, fourth, fifth and sixth - then the sum of their weights will be greater than the automatic load capacity ($7+15+12+9>32$).

If you take only the 2nd, 4th and 5th items, then the car turns out to be underloaded by 8 kk. You can then load only one more 3rd item, and the total cost will be equal to 440 rubles, and the car will be underloaded by 2 kk. Can you be sure that there is no better way to load the machine?

Maybe it is more profitable to leave one of the items with a higher unit cost, but will it increase the overall cost by fully using the machine's carrying capacity?

As you can see, it is difficult to solve the problem “in love”. But in real conditions, when the problem is often not about six, but about sixty objects, it is impossible to take on it without being armed with mathematical methods. Let's translate the problem into the language of mathematics (as they say, let's mathematize the situation). Let $x_i=1$ if the $i$-th object is immersed on the automaton, and $x_i=0$ otherwise ($i=1, \dots, 6$). Then the total value of the loaded items in rubles is 120 $x_1+140 x_2+60 x_3+80 x_4+160 x_5+110 x_6$, and their total weight in centners is 11 $x_1+7 x_2+6 x_3+5 x_4+12 x_5+9 x_6$.

So, abstracting from the “life” situation, we get a number mathematical task: find the values

⟦folio 3⟧

variables $x_1, \dots, x_6$ (which one can be 0 or 1), for which the function
$$f(x_1, \dots, x_6) = 120x_1 + 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$$
reaches a maximum if the condition (constraint) is met
$$11x_1 + 7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32.$$ (1)

The function $f$ is called the objective function of the problem; it is defined to the set of all ordered sixes of zeros and ones (istime vectors, each component of which is equal to 0 or 1).

In total, there are $2^6 = 64$ such vectors, and each of them provides some way to load the automation. But not each of these 64 loading methods is acceptable: vector $(1,0,1,0,1,1)$ corresponds to loading the 1st, 3rd, 5th and 6th items onto the machine, only their total weight $(38 \mu)$ exceeds the permissible limit.

It is natural to call a vector admissible if condition (1) is satisfied for it. So, the solution to the problem is a feasible vector that maximizes the objective function $f$.

Now let's say that the 1st item is loaded into automation. Then $x_1 = 1$, and we get a new problem:

The name of the variables $x_2, \dots, x_6^*)$, for which the maximum function $f_2(x_2, x_3, \dots, x_6) = 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$ is sufficient under the condition $7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32$.

If the 1st object is not immersed, then $x_1 = 0$, and we get the following problem:

The names of the variables $x_2, \dots, x_6$ that maximize the function $f(x_2, \dots, x_6) = 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$ subject to the condition $7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32$.

*) Conditions $x_i = 0$ or 1, assumed throughout the entire stat, we are not specifically limited in the future.

Thus, one problem with 6 variables can be reduced to two problems with 5 variables; these in turn are reduced to four problems with 4 variables, etc., so that in the end we get 64 problems with one variable each. But if it is necessary to solve such a system, then the process of not presently checking conditions (1) for each of the 64 possible vectors, for the admissible ones, calculate the value of the objective function and select the vector for which the value is maximum, that is, as they say, solve the problem by “exhaustive search”.

But what about in cases where the number of objects (vector components) is large? After all, even with 20 items, the number of possible options exceeds a million! It is clear that the exhaustive search method in problems of this kind is unsuitable for most applications.

We will now talk about one method that, as a rule, allows us to significantly reduce the number of compared options required to obtain a solution. We will describe this method, known as the “branch and bound method,” as we apply it to our problem.

The process of selecting items for loading onto the automated machine can be depicted as $\textcircled{2}$ graph $^*$). The starting node 0 corresponds to the set $P$ of all 64 maximal vectors. From node

*) See article by M. I. Bashmakov. "Matchings and transortin networks" in No. 4 «Kvant» for 1970. However, what follows will be clear to those who have not read this page.

⟦folio 4⟧

0 starts vectored to nodes 1 and 2 (Fig. 1). Node 1 is located to the right and below node 0. It corresponds to loading methods in which the 1st object is necessarily loaded onto the machine. Obviously, node 1 corresponds to the subset $P_1$ of those 32 vectors from $P$ that have $x_1=1$. Node 2 is located to the left and below node 0 and corresponds to the subset $P_2$ of those 32 vectors from $P$ that have $x_1=0$. The further construction of the graph is clear. figure 1 shows the graph after two branching steps.

Each node of the graph corresponds to a subset of vectors from $P$, whose non-tortic components are already fixed. If the construction of the set $P_1$ and $P_2$ is considered as the first step of branching (the first level of the graph), then at the $k$th step ($k$th level of the graph) we will receive $2^k$ nodes, each of which corresponds to a set of $2^8-k$ vectors (automation loading options). The nodes obtained at the sixth branching step represent one vector each, so that the average of these nodes is given. So, if the branching is carried out completely, then you will have to build a graph with the number of nodes $1+2+4+\dots+64=127$.

But we will try to act in such a way as to simultaneously detect “unpromising” nodes from which branches leading to a solution cannot emerge. The sooner (higher) we “cut off” these branches, the less brute force we will have to do later. For this purpose, we assign 2 numbers to each node (which we will write under the node). The top one shows the most possible total cost (eranza cost) of the items taken for any loading method, described by the vectors of this node. The number below shows how much total of all shared items is allowed at this step (this number is equal to the difference between the carrying capacity of the automation and the weight of all already loaded items). For example, let's find the upper and lower

Numbers for the 1st node. Since in all corresponding loading options the 1st item is necessarily taken, the lower number at this step is $32-11=21$. The boundary under construction (upper number) is equal to the sum of the under construction of all objects, since we have not yet ruled out the possibility of choosing any of them. Therefore, the upper number of the 1st node is 670. For the second node, the upper number is 550 (670-120), since the first item is not taken: the lower number here is 32.

Let $P_i$ be the weight of the $i$-th item, $C_i$ its cost. It is obvious that when moving from any node located at the $i$-th level of the graph, the upper number does not change, and the lower one decreases by $P_{i+1}$, while when moving from this node to the left, the lower number does not change, and the upper one decreases by $C_{i+1}$. At each stage we will identify the node whose top number is the most integer. If two nodes have the same upper numbers, then we will choose the one with the lower number. If during the branching process a node with a negative lower number is encountered, this means that with the loading methods corresponding to this node, the automation will be overloaded, and branching such a node does not make sense. By branching according to the indicated method, we will arrive at a node located at the last, sixth level of the graph, with a non-negative lower number.

This node corresponds to some acceptable loading method in which the value of the objective function is equal to the upper number. All unbranched nodes that have less than this node are insignificant to branch, since the top number cannot increase when branching. It may turn out that the top number of the node found is greater than that of any other node. Then this node provides a solution to the problem. figure 2 shows the final graph.

The construction of the graph will continue in the following stages (the numbers will familiarize you

⟦folio 5⟧

node numbers):

1) 0→1→3→5→7→9; 2) 6→11→13; 3) 8→15; 4) 2→17→19→21→23→25; 5) 12→27→29; 6) 4→31→33→35; 7) 10→37; 8) 20→39→41→43; 9) 22→45→47; 10) 32→49→51→53; 11) 14→55; 12) 34→57→59.

Further branching is useless, since node 55 is at the last level of the graph and has the highest number. This node provides a solution to the problem. It corresponds to the vector (1,1,0,1,0,1): you need to load the 1st, 2nd, 4th and 6th items onto the machine. In this case, the total cost (maximum of the objective function) is 450 rubles.

In the process of constructing the graph, over 50% of unpromising options were “cut off.” As the number of variables increases, the percentage of such options usually increases.

In addition, the process can be used to solve similar problems using the described approach. Of course, our task is quite simple: only 2 branches come out of each node, and it is not difficult to find the boundaries (upper and lower numbers). In other problems, the processes of branching and limitation may be more complex and depend on the skill and wit of those who solve it. As for the labor intensity of the process itself, electronic executing machines come to the rescue. Problems like the one under consideration are often called “backpack problems” (replace the machine gun with a tourist backpack, and its carrying capacity with the maximum capabilities of a tourist who packs and makes a difficult choice among the “absolutely necessary” items).

Of course, these problems have to be solved not only before a vacation or vacation. After all, the formation of an annual plan for an enterprise in many cases is the same task about a backpack. It is clear that the branch and bound method “works” in many economic planning problems that are of greater importance for the national economy.
