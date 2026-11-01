---
id: 1980-9-glushankov-pevzner-pereklyuchatelnaya-igra-shennona-487f718b
issue: kvant_1980_9
year: 1980
number: "9"
title: Shannon switch game
authors:
  - Глушанков Е.
  - Певзнер П. А.
rubric: osnovnye-stati
page_first: 16
page_last: 22
page_labels: 14, 15, 16, 17, 18, 20
tag: Q02F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 51a5cd967be36f4eb21a9d875d5c3c7582af917a94155e70992a6753437cd204
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/08_glushankov-pevzner-pereklyuchatelnaya-igra-shennona-487f718b.md
source_content_sha256: 8582c290bdfc67596a6df1ed260d51d2ec09636b38ca3b2c43be2ae6180199de
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

E. Glushankov,
P. Pevzner

Shanon's switch game

Is it possible without a complete search?

The rapid development of production, economics and transport in the 20th century posed new problems for mathematics. How to manage a modern enterprise, how to plan a large set of work, how to create a convenient train schedule - engineers began to turn to mathematicians with all these questions. However, the methods of classical mathematics, intended mainly for solving problems in physics and mechanics, could not answer such questions. This led to the emergence of new mathematical disciplines - game theory, graph theory, coding theory and many others, now united under the name “discrete mathematics”.

The first work on discrete mathematics (it belongs to Leonhard Euler), which appeared in 1736, was devoted to the famous puzzle about the Königsberg places: is it possible to take a walk around Königsberg (the city plan is shown at figure) in such a way that you leave the house, return back, having walked through each place once? For a long time, discrete mathematics was concerned almost exclusively with puzzles, and therefore was in the position of Cinderella among server mathematicians. However, already in the 19th century, discrete methods were used in the study of electronic circuits and molecular circuits in chemistry.

The real calculation of discrete mathematics is observed in the last two or three decades. Physics, chemistry, programming, economics, genetics, sociology, linguistics

⟦folio 15⟧

Well, antipology is only part of a long list of sciences in which the methods of discrete mathematics are used.

Recently, universal externalities have attracted some classical problems of discrete mathematics, which have been waiting for a solution for more than a hundred years. All these problems are characterized by the fact that if a “candidate answer” is given, then it is very easy to check whether it is really the answer, but it is very difficult to find such an answer; actually comes to sort through all the possible options one by one.

On the one hand, people are faced with interesting mathematics problems almost every day. This is the task of finding a proof of this theorem. In fact, if a proof is given, then in principle it is not difficult to verify its correctness. You just need to make sure that each step is made in accordance with the rules of logic, and intermediate statements follow from axioms and known theorems. But how to find this proof? Was it necessary to go through all possible arguments, starting with the axioms? If someone could explain how they "guess" when solving problems, maybe it could help mathematicians teach a machine to do the same.

Here's a simpler example: the partitioning problem. Let $A = \{s_1, \dots, s_N\}$ be a finite set containing natural numbers. It is required to split the set $A$ into two subsets $I$ and $J$ ($I \cap J = \emptyset$, $I \cup J = A$) so that the sum of elements from $I$ is equal to the sum of elements from $J$. As in the previous example, for a given partition of the set $A$ into the set $I$ and $J$ it is very easy to check whether the corresponding sums are equal. But how to find the required partition? Unfortunately, science cannot yet offer anything significantly better than trying all $2^N$ options. But even with $N = 100$ a modern computer it will take billions of years to verify such an enumeration.

Currently, there is a widespread opinion that for some problems (for example, the partition problem) nothing significantly better than exhaustive search can be proposed. That is why every example of an effective algorithm in a situation where previously we were content with brute force is of great interest to science, even if the situation itself is “toy”. One such example will be discussed in this article.

In the early 50s, the outstanding American mathematician and engineer, creator of information theory, Claude Chenon, proposed a scheme for enumerating options for a chess program. Almost all modern chess programs are of this scheme. However, the number of options iterated through programs playing according to the Shenon algorithm turns out to be so large that neither the memory nor the speed of modern computers is enough to implement them.

Shannon is trying to apply his methods to some other games. He considered a game on graphs, which is now called the switching Cenon of Chenon (abbreviated as SCH).

Currently, several approaches to game programming have been proposed. «Kvant» has already written about a method based on enumeration with the absence of unpromising (from some point of view) options. Another method (based on it in the mid-60s, A. Lehman proposed the “ideal player” in NSP), associated with a complete rejection of enumerating options, is based on some new results of discrete mathematics.

We will tell you below how you can play PIS without going through options.

Bridget

In the late 50s, the American Gale came up with the game Bridge-it. The standard field for the game Bridge-it is shown at figure 1. One player connects the blue dots with a blue pencil, the other connects the red dots with a red pencil. They “walk” (that is, play segments) of the game in turns. The winner is the one who is the first to build a broken line connecting two opposite sides of his color (at figure 2 the game ended in victory for the Reds).

*) R. S. Guter, M. V. Donskoy The machine plays chess («Kvant», 1974 No. 11).

⟦folio 16⟧

Try playing bridge-it on small fields (Fig. 3) to figure out which player has the advantage in the game, and then try to develop a winning strategy for that player.

Problem 1. Prove that there are no “draws” in the game of bridge-it.

If there are no “persons” in the church, then one of the churches had a winning strategy. Indeed, let, for example, player $A$ not have a winning strategy, that is, for any of his moves, player $B$ has such an answer that the game will not end in victory $A$. Since it is assumed that there are no “draws” in the game under consideration, the game will end in the victory of player $B$, that is, $B$ has such a sequence of moves that no matter how $A$ plays, $B$ will still win. Thus, player $B$ has a winning strategy.

The reasoning just given is pure proof of existence: it is proven that there is a strategy, but there is no word on how to find it. But this is the most interesting question.

NIPSH

To describe a winning strategy for playing Bridge-it, let's move from Bridge-it to PIP. To do this, let's change the rules of the game a little. At figure 4, all possible moves of the “blue” player are marked with blue segments, and the “red” player is marked with red segments. We will call such figure “possible move graphs”. If you have already played bridge-it, then you probably realized that it is pointless for players to carry out the segments indicated by point 4 on figure. Therefore, let’s not consider them at all and do the following: let’s pull all the top points into one and do the same with the left, right and bottom points (Fig. 5). Now the goal of the “blue” player is to connect the vertices $s$ and $t$ with a path of blue edges, and the goal of the “red” player is to connect the vertices $s'$ and $t'$ with a red path.

Notice that each red line intersects exactly one blue line. Therefore, if the “red” player makes a move, then this essentially means that he makes one (and only one) move of the “blue” player impossible, that is, the “red” player with his move is like drawing an edge of the blue graph. But instead of crossing out the blue edge, you can simply paint it red. Now we can completely remove the red graph from figure 5 and assume that the game goes like this:

Two players take turns coloring the edges of the graph whose vertices $s$ and $t$ are highlighted: one in blue, the other in red (Fig. 6). The goal of the “blue” player is to connect the selected vertices by *) from blue edges, and the goal of the “red” player is to place them (we will clarify what this means later).

*) Recall that a graph is a finite set of points (vertices of the graph) and the segments connecting them (edges of the graph). A path is a line on a graph that does not pass along any edge more than once.

⟦folio 17⟧

This is the Izra Shenon switch PISH). Only Shenon proposed it in a more general formulation: firstly, you can play on any graph and, secondly, you can select any pair of vertices on a given graph.

Each graph with two visible vertices defines a small variant of the PIP. The first move in each variation can be made by any player - both “blue” and “red”. Since the "blue" player connects the vertices, he is appropriately called a Connection or C-ceroc. And we will call the red player Cutting or P-cerok.

It is quite obvious that there are no “nothings” in the NSP - C will either connect the seen vertices or not. Therefore, one of the players in the NSP has a winning strategy. But which one? How to find this strategy?

Classification of NSP variants
Note that if the cerok, which ranks second, has a winning strategy, then it also has it in the case when the cerok is first. Indeed, the cerok is the first, he will paint over any edge with his color, and then he will respond to the opponent’s moves as he would do if he played second. If at some step it is necessary to paint an edge that he painted earlier, then he will paint an arbitrary edge. This is how he will play, having one “extra” edge of his color, which, of course, cannot allow him to win.

Thus, from the point of view of occurrence to win for each variant of the NSP, one and only one of the following three mergers has arisen:

1. connections has a winning strategy, regardless of whether he plays first or second;
2. the cutter has a winning strategy, regardless of whether he plays first or second;
3. The player who makes the first move has a winning strategy.

We will call the variants of PSPs of the first group S-cers, the second -

2 Quantum No. 9

⟦folio 18⟧

R-cerami, the third - N-cerami. Figures 7, a) - c) show graphs giving C-cer, P-cer and H-cer, respectively.

Problem 2. Prove that bridge-it is an H-game.

A little theory

Let's take a break from games for a while and give some definitions from graph theory that will come up later*.

A graph G is called connected if there is a path between any two vertices. An incoherent graph is a collection of several connected graphs, each of which is called its component. A path in which the starting and ending vertices coincide is called a cycle. If a connected graph has a cycle, then when any edge is removed from the cycle, the graph remains connected. A connected graph without cycles is called a tree. Examples of trees are given in figure 8.

It is easy to see that removing any edge from the tree results in a graph with two components, and the ends of the removed edge lie in different components (Fig. 9).

An edge of the graph with ends x and y will be denoted by [x, y]. We denote the component that is formed by removing the edge [x, y] from the tree A and contains vertex x by A(x), and the component that contains vertex y by A(y).

Lemma about two trees. Let A and B be two trees on the same set of vertices and [x, y] be an edge of tree A. Then in tree B there is an edge b, one end of which lies in A(x) and the other in A(y) (Fig. 10).

New rules of the game

To learn how to play PIP, we will again change the field and rules of the game a little. To do this, we introduce the concept of graph contraction.

*) More details about graphs are discussed, for example, in the book by L. Yu. Berezina “Graphs and Their Application” (M., “Prosveshchenie”, 1979).

⟦folio 20⟧

This lemma suggests a strategy for the connecting player.

The goal of player $C$ is to maintain in the graph the existence of two trees that satisfy the Lehmann condition (by dividing this, he ensures the existence of two paths between vertices $s$ and $t$, and player $P$ has no way of separating these two vertices). And player $C$ can actually do this if there were such two trees in the original graph. If player $P$ removes edge $a$ from one of these trees, then player $C$ must respond by removing an edge from another tree that exists by the last lemma. If player $P$ removes an edge that does not belong to either of our two trees, then player $C$ can contract an edge in one of the trees; it is clear that the new graph still contains two Lehmann trees (which ones?).

After each pair of moves, the number of vertices in each of our trees decreases by one, so vertices $s$ and $t$ will sooner or later merge and player $C$ will win.

We started you to play the $C$-game using two Lehman trees. But where are these trees located? Of course, you can use exhaustive search, but this is associated with a huge investment of time, even on modern computers. Lehmann was unable to find an efficient algorithm for finding two such trees, so for a long time it seemed that Lehmann's theorem was of only theoretical interest. Only in the early 70s did Bruno and Weinberg manage to build such an algorithm.

In fact, Lehmann completely solved the Shannon switching game: he also proved that a variant of the NIS is a $P$-game if and only if the graph has two subgraphs of a certain kind. If the PIP variant is a $H$-game, then after the first reasonable move we get a PIP variant on the new graph, which is a $P$-game or a $C$-game - depending on who made the first move: $P$ or $C$, respectively. Such a move exists. Such a move exists in a certain $H$-game. In principle, these moves can be made by brute force.

**Strategy for bridge-it**

So, we told you how to play $C$ games. But bridge-it, according to Problem 2, is a $H$-game. How can a beginner play to win?

Obviously, in the game of bridge, a beginner can be considered a $C$-player. With his first move he can capture, for example, the edge marked at figure 13 in green. The resulting graph after this move contains two Lehmann trees: they are highlighted on figure 13 in red and black. And then player $C$ can use the strategy described above for the $C$ game. At figure 13, the arrows are considered in such a way that player $P$ removes the edge at which the end of a certain arrow points.
