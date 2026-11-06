---
id: 1990-7-vakarelov-kalinin-prevrascheniya-golovolomki-admirala-makarova-0e757d4a
issue: kvant_1990_7
year: 1990
number: "7"
title: Transformations of Admiral Makarov's puzzle
authors:
  - Вакарелов Д. И.
  - Калинин А. Т.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 72
page_last: 77
page_labels: 70-75
lang: en
source: kvant_digital
extraction: vision
content_sha256: c51efb5546f67573f4856540b11dd89439ed7995c0dd391ab53b8ba8c4010970
prompt_sha256: draft-1
translated_from: content/ru/1990/07/articles/22_vakarelov-kalinin-prevrascheniya-golovolomki-admirala-makarova-0e757d4a.md
source_content_sha256: 40a8ce36a82225a7dc46ddd271fdb357aef072b16e6a6d758b31f6ac901d4504
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 70⟧

---
running_head:
folio:
---

Transformations
puzzles
admiral
Makarova

D. VAKARELOV, A. KALININ

The world is designed in such a way that things in it can live longer than lodi, has different names at different times and in different countries. The toy you see on figure is known in our country as the “Admiral Makarov puzzle”. In other countries it has other names, the most common of which are “devil’s cross” and “devil’s knot”.

This knot is connected from 6 square bars. There are times in the bars, thanks to which it is possible
You can cross the bars in the center of the knot. One of the bars does not have times; it is placed last in the assembly, and when disassembled, it is removed first.

The author of this puzzle is unknown. It appeared many centuries ago in China. In the Leningrad Museum of Antipology and Ethnography named after. Peter the Great, known as the “Kunstkamera”, there is an ancient sandalwood box from India, in the 8 corners of which the intersections of the frame bars form 8 puzzles. In the Middle Ages, sailors and merchants, wars and diplomats amused themselves with such puzzles and took them around the world. Admiral Makarov, who visited China twice before his last trip and death in Port Arthur, brought the toy to St. Petersburg, where it entered into fashion in secular salons. The puzzle also penetrated into the depths of Russia through other roads. It is known that the devil’s bundle was brought to the village of Olsufyevo in the Bryansk region by a soldier returning from the Russian-Turkish war.

Nowadays you can buy a puzzle in a store, but it’s more pleasant to make it yourself. The most suitable size of bars for a homemade structure: 6 × 2 × 2 cm.

Variety of damn knots

Before the beginning of our century, over several hundred years of the toy’s existence in China, Mongolia and India, more than a hundred variants of the puzzle were invented, differing in the configuration of the cutouts in the bars. But two options remain the most popular. The one shown at figure 1 is quite easy to solve, just make it. This is the design used in the ancient Indian box. A puzzle called the “Devil’s Knot” is made from the bars of Figure 2. As you agree, it got its name due to the difficulty of solving it.

In Europe, where, starting at the end of the century, the “Devil’s Knot” became widely known, enthusiasts began to invent and make sets of bars with different configurations

⟦folio 71⟧

---
running_head:
folio:
---

cutouts One of the most successful sets allows you to get 159 puzzles and consists of 20 bars of 18 types. Although all the nodes are externally indistinguishable, they have completely different structures inside.

The Bulgarian artist, professor Petr Chukhovski, the author of many familiar and beautiful wooden knots from different numbers of bars, also worked on the “Devil's Knot” puzzle. He developed a set of bar configurations and explored all possible combinations of 6 bars for one simple subset of it.

The real master of such Japanese was the puzzling mathematics professor Van de Boer, who with his own hands made a set of several hundred bars and compiled tables showing how to assemble 2906 variants of knots.

This was in the 60s, and in 1978, the American mathematician Bill Cutler wrote a computer program and, using exhaustive search, determined that there were 119,979 variants of a 6-element puzzle, differing from each other in the combination of protrusions and valleys in the bars, as well as the placement of the bars, provided that there were no voids inside the node.

Surprisingly large number for such a small toy! Therefore, a computer was needed to solve the problem.

How does a computer solve puzzles?

Of course, not like a person, but not in some magical way either. The computer solves puzzles (and other problems) according to a program, programs write programs. They write as they please, but in a way that the computer can understand. How does a computer manipulate wooden blocks?

We will proceed from the fact that we have a set of 369 bars, differing from each other in the configurations of the protrusions (this set was first determined by Van de Boer). Descriptions of these bars must be kept in the computer. The minimum cutout (or protrusion) in a block is a cube with an edge equal to 0.5 of the thickness of the block. Let's call it a single cube. The whole block contains 24 such cubes (figure 1). In a computer, for each block a “small” array of $6 \times 2 \times 2 = 24$ numbers depends. A block with cutouts is specified by a sequence of 0s and 1s in a “small” array: 0 corresponds to a cutout cube, 1 to a whole one. Each of the "ma-

Fig. 1. The simplest version of the “devil’s knot” puzzle.

Fig. 2. The bars of the classic version of the “devil’s knot” puzzle - “Admiral Makarov’s puzzle.”

⟦folio 72⟧

---
running_head:
folio:
---

arrays has its own number (from 1 to 369). Each of them can be assigned a number from 1 to 6, corresponding to the position of the block inside the puzzle.

Let's move on to the puzzle now. Let's imagine that it fits inside a cube of size $8 \times 8 \times 8$. In a computer, this cube corresponds to a “large” array consisting of $8 \times 8 \times 8 = 512$ number cells. Placing a certain block inside a cube means filling the corresponding cells of a “large” array with numbers equal to the number of a given block.

Comparing 6 “small” arrays and the main one, the computer (i.e., the program) seems to add 6 bars together. Based on the results of adding numbers, it determines how many and what “empty”, “filled” and “overcrowded” cells were formed in the main array. “Empty” cells correspond to empty space inside the puzzle, “filled” cells correspond to protrusions in the bars, and “crowded” cells correspond to an attempt to connect two single cubes together, which, of course, is prohibited. Such a comparison is made many times, not only with different bars, but also taking into account their turns, the places they occupy in the “cross”, etc.

As a result, those options are selected that do not have empty or overfilled cells. To solve this problem, a “large” array of $6 \times 6 \times 6$ cells would be sufficient. It turns out, however, that there are combinations of bars that completely fill the internal volume of the puzzle, but it is impossible to figure them out. Therefore, the program must be able to check the assembly for the possibility of disassembly. For this purpose, Cutler took the array $8 \times 8 \times 8$, although its size may not be sufficient to check all cases.

It fills in information about a specific puzzle variation. Inside the array, the program tries to “move” the bars, i.e., moves parts of the bar of size $2 \times 2 \times 6$ cells in the “large” array. The movement occurs by 1 cell in each of 6 directions parallel to the axes of the puzzle. The results of those 6 attempts in which no “overfilled” cells are formed are filled in as the starting positions for the next six attempts. As a result, a tree of all possible movements is built until some block completely leaves the main array or, after all attempts, the cells remain “overfilled,” which corresponds to an option that is impossible to understand.

This is how 119,979 variants of the “Devil’s Knot” were obtained on a computer, including not 108, as the ancients believed, but 6402 variants with 1 goal, without cutouts.

Supernode

Let us note that Cutler refuses to study the general problem - when the node also contains internal voids. In this case, the number of nodes consisting of 6 bars increases greatly and the exhaustive search required to find feasible solutions becomes unrealistic even for a modern computer. But as we will see now, the most interesting and difficult puzzles are contained precisely in the general case - disassembling the puzzle can then be done without even a trivial task.

Due to the presence of voids, it becomes possible to move several bars sequentially before being able to completely separate any bar. The moving bar unhooks some bars, allows the movement of the next bar and simultaneously engages other bars.

The more manière you need to do when disassembling, the more interesting and difficult the puzzle version. The grooves in the bars are arranged so cleverly that the search for a more accurate solution to help the dark labyrinth, in which you constantly bump into walls or dead ends. This type of knot certainly deserves a new name; we'll call it a "supernode". The measure of complexity is super-

⟦folio 73⟧

---
running_head:
folio:
---

knot we call the colic movements of the individual bars that must be made before the first element is separated from the puzzle.

We don't know who came up with the first supergreen. The most famous (and most difficult to solve) are two superkits: the “Bill's ring” of difficulty 5, invented by W. Cutler, and the “Dubya superknot” of complexity 7. Until now, it was believed that the degree of difficulty 7 could hardly be surpassed. However, the first of the authors of this article managed to improve the “Dyubya knot” and increase the difficulty to 9, and then, using some new ideas, get super-evils with difficulties of 10, 11 and 12. But the number 13 remains insurmountable. maybe the number 12 is the biggest difficulty of super evil?

Super Evil Solution

Providing blueprints for such difficult puzzles as superevils without revealing their secrets would be too harsh on even a puzzle expert. We give the solution to superevils in a compact, algebraic form.

Before disassembling, we take the puzzle and orient it so that the numbers match figure 1. The disassembly sequence is written down as a combination of numbers and letters. The numbers indicate the numbers of the bars, the letters indicate the direction of movement in accordance with the coordinate system shown in Figures 3 and 4. A line above a letter means movement in the imprinted direction of the coordinate axis. One step is to move the block 1/2 of its width. When a block moves two steps at once, its movement is written in brackets with an exponent of 2. If several parts that are interlocked are moved at once, then their numbers will be enclosed in brackets, for example (1, 3, 6) x. The separation of the block from the puzzle is indicated by a vertical arrow.

Let us now give examples of the best superevils.

W. Cutler's puzzle (“Bill's little name”). It consists of parts 1, 2, 3, 4, 5, 6, shown in figure 3. An algorithm for solving it is also given there. It is curious that the journal Scientific American (1985, No. 10) gives another version of this puzzle and reports that “Bill's name” has a unique solution. The difference between the options is in just one block: parts 2 and 2 B on figure 3.

Fig. 3. “Bill's name” puzzle, developed using a computer.

⟦folio 74⟧

---
running_head:
folio:
---

$(6\bar{z})^2, 3\bar{x}, 1z, 4x, 2x, 2y, 2z \uparrow$
$(4\bar{x})^2, 1\bar{z}, 1\bar{x}, 6\bar{y} \uparrow$

Fig. 4. Superknot F. Dubya difficulty 7.

$(6\bar{z})^2, 3\bar{x}, 1z, 4x, 2x,$
$2y, 5x, 5y, 3z \uparrow$ (9)

Fig. 5. Superknot D. Vakarelova difficulty 9.

$4\bar{z}, 1\bar{z}, 3x, 2x, 2\bar{z}, 3\bar{x}$
$1z, 6z, 3\bar{x}, 1\bar{x}, 6\bar{y} \uparrow$ (11)

Fig. 6. Superknot D. Vakarelova difficulty 11.

74

⟦folio 75⟧

---
running_head:
folio:
---

4z, 1z, 3x, 2x, 2z, 3x,
6z, 1z, (1,3,6)x, 5y ↑ (12)

Fig. 7. Superknot D. Vakarelova difficulty 12.

Due to the fact that part 2B contains fewer cuts than part 2, inserting it into “Bill’s thorn” according to the algorithm specified in figure 3 is not removed. It remains to be assumed that the puzzle from Scientific American is assembled in some other way.

If this is the case and we assemble it, then after that we can replace part 2B with part 2, since the latter takes up less volume than 2B. As a result, we will get the second solution to the puzzle. But “Bill's thorn” has a unique solution, and from our contradiction we can only make one choice: in the second option, an error was made at figure.

A similar mistake was made in another publication (J. Slocum, J. Botermans “Puzzles old and new”, 1986), but in a different block (detail 6C on figure 3). What was it like for those readers who tried and, perhaps, are still trying to solve these puzzles?

Puzzle by Philippe Dubois (Fig. 4). It can be solved in 7 moves using the following algorithm: $(6z)^2, 3x, 1z, 4x, 2x, 2y, 2z↑$. figure shows the location of parts for step 6 of disassembly. Starting from this position, using the reverse order of the algorithm and changing the directions of movement to the opposite, you can assemble the puzzle.

Three supernodes by D. Vakarelova. The first of his puzzles (Fig. 5) is an improved version of the Dubois puzzle, it has a difficulty of 9. This superknot is more like a labyrinth than others, since when disassembling it, false passages appear that lead to dead ends. An example of such a dead end is the moves 3x, 1z at the beginning of the showdown. And the correct solution is:

$(6z)^2, 3x, 1z, 4x, 2x, 2y, 5x, 5y, 3z↑$.

The second puzzle of D. Vakarelov (Fig. 6) is solved according to the formula:

$4z, 1z, 3x, 2x, 2z, 3x, 1z, 6z, 3x, 1x, 6y↑$ and has a difficulty of 11. It is a replacement of the body that bar 3 on the third move makes a step 3x, and on the sixth move returns back $(3z)$; and block 1 at the second step moves along 1z, and at move 7 the reverse move is made.

The third puzzle (Fig. 7) is one of the most difficult. Her solution:

$4z, 1z, 3x, 2x, 2z, 3x, 6z, 1z, (1,3,6)x, 5y↑$ repeats the previous puzzle until the seventh move, then, on move 9, it encounters a completely new situation: unexpectedly, all the bars stop moving! And here you need to figure out how to move 3 bars (1,3,6) at once, and if this movement is counted as 3 moves, then the complexity of the puzzle will be 12.
