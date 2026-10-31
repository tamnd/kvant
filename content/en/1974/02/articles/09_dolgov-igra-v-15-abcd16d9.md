---
id: 1974-2-dolgov-igra-v-15-abcd16d9
issue: kvant_1974_2
year: 1974
number: "2"
title: Game at 15
authors:
  - Долгов О. Т.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 35
page_labels: 26, 27, 28, 29, 30, 32, 33
tag: EP1I
lang: en
source: kvant_digital
extraction: vision
content_sha256: d966285881ce1bbd1774060cdd87c00296fd8b2feb3e5fbc951d9dc951ddbcfa
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/09_dolgov-igra-v-15-abcd16d9.md
source_content_sha256: 9b43d7db100684737cb3634c7dc0dc341e7af442322bee33a972215945429fa1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Game at 15
O. T. Dolgov

- So this is a well-known problem!
- How is it resolved?
- Not really! The condition is known,
but I don't know the solution...
Mill. Dialogues

1. Word to Sam Loyd
In «Kvant» I already talk about Martin Gardner’s book “Mathematical Leisure” («Kvant», 1973, No. 6). The 33rd chapter of "Leisure" is called "The Game of 15 and Other Puzzles."

There are 15 checkers with numbers in a flat square box. The "normal" arrangement of checkers is shown at figure 1. At figure 2 a different arrangement is shown: checkers numbered 14 and 15 are rearranged. It is necessary, by moving one checker at a time, to transfer this arrangement to “normal”. The checkers are moved to a free adjacent space; they are not allowed to be removed from the box.

The game was invented in the 15th century by Sam Loyd in the seventies. His craze quickly swept across England, and then spread across the English Channel. Gardner uses a quote from Lloyd himself to tell his story about this:

“People literally fit on this puzzle. Stories were passed down from mouth to mouth about a shopkeeper who forgot to open his shop, about a signalman who stood under a street lamp on a long winter night in the hope of remembering how he managed to solve a problem...

One well-known editor from Baltiym says that once he left at noon for lunch and only late at night was discovered by the newspaper staff sitting at the table and pushing small pieces of pie back and forth on the plate!

In 1879, the mathematical theory of the game 15 was published, after which the game quickly fell out of fashion.

The mathematical theory that undermined interest in Lloyd's puzzle is not explained in his book by Gardner.

⟦folio 27⟧

gags. Meanwhile, this theory is simple and respectful.

2. Even and odd permutations
Let's arrange the numbers 1, ..., 15 in random order. For example, like this:
1, 2, 3, 4, 8, 7, 6, 5, 9, 10, 11,
12, 15, 14, 13, (1)
or like this:
1, 2, 3, 4, 8, 7, 6, 5, 9, 10, 11,
12, 14, 15, 13. (2)

Which of these arrangements is called a permutation.
We will say that in a given permutation the numbers i and j form a disorder if i > j, but i is to the left of j in this permutation.
Example. Numbers 8 and 6 in permutation (1).
We call a permutation odd (odd) if it has an even (odd) number of disorders.
Examples. In permutation (1) there are nine, and in permutation (2) there are eight disorders, so that (1) is an odd permutation and (2) is an even permutation.

3. Rearrangements and play at 15
Let's draw a broken line on the box for playing 15, like on figure 3. Let's follow this broken line from the upper left corner of the box and write down the numbers of the checkers that we will go through sequentially.
Examples. If the checkers are located as on figure 1, then we get permutation (1); for the location on figure 2 we get permutation (2).
Passing through an empty cell, we do not write any number. Therefore, the same permutation corresponds to sixteen different arrangements of checkers in the box. For example, permutation
1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11,
12, 13, 14, 15
 matches any of the locations on figure 4.
When playing 15 checkers, you can replay horizontally and vertically by taking the adjacent path to the square. If a checker is re-played horizontally, then both the old and new positions correspond to very indo, the same permutation (Fig. 4, a, b). If the checker is replayed vertically, then it may be that the permutation does not change (Fig. 4, b, b), but the common old and new positions correspond to different permutations (Fig. 5).
However, these permutations always turn out to have the same value (either both even or both odd).
Let's check this first in the case depicted at figure 5. The location at figure 5, a corresponds to the permutation
..., 6, 5, 11, 9, 10, ..., (a) location on figure 5, b - permutation
..., 10, 6, 5, 11, 9, ... (b) (ellipses replace the match in

⟦folio 28⟧

(a) and (6) numbers). When passing (a) to (6), one disorder (11, 10) disappears and three new ones (10, 6), (10,5) and (10, 9) arise. The total disorder count returns by 2, so (a) and (6) actually have the same parity.

In the general case, when a checker with number $n$ is moved from cell $A$ to an empty cell $B$ (Fig. 6), the proof is carried out in a similar way. On the section of the broken line between $A$ and $B$ there is always an even number of checkers. Let $y$ $m$ of them have numbers less than $n$, and $k$ have numbers greater than $n$; then $m$ of unrest when moving a checker disappears and $k$ of unrest returns to $k$ - $m$. This is an even number, since by condition the number $k + m$ is even. Thus, the permutations corresponding to the old and new arrangement necessarily have the same parity.

4. The unsolvability of the puzzle
Loyd

Permutations (1) and (2), the corresponding arrangements of checkers in Figures 1 and 2, have different parities. This means that these arrangements cannot be obtained from each other: Loyd's puzzle is unsolvable.

5. Will it work out or won't it work out?
Well, what if you randomly arrange the checkers in the box? In what cases will the puzzle work (the status is set to “normal”), and in what cases will it not work?

We already know: if the permutation corresponding to the location is even, then the puzzle will not be completed. What if it’s odd? Then, it turns out, it will definitely work out.

This statement can be proven in different ways. Below we will do this in approximately the same way as S. Bobrov in his book “The Magic Friend” *).

6. How to jump over two checkers
Let's draw a closed path on the box in the form of the letter P (Fig. 7). Along this path, checkers can be moved one after another, “in single file.” Thus, it is possible, for example, to gradually transform the arrangement depicted at figure 8, $a$ into “normal” (Fig. 8, 6, 8, 2, $\partial$). This is easy to do because the relative order of the checkers along the path P (starting with checker 1, clockwise) is the same:
{1, 2, 3, 4, 8, 12, 15, 11, 7, 6, 10, 14, 13, 9, 5}.

Let us now assume that for some arrangement of checkers this order is different, and we want to transform this arrangement into a “normal” one. To do this, it would be good for us to learn how to purposefully change the order of the checkers along the path P.

*) Bobrov S. Magic friend. Detgiz, 1946, p. 29-41, 89-117.

⟦folio 29⟧

Below we will indicate a method by which this can be done.

Let checkers with numbers $i, j$ and $k$ stand one behind the other along the path $\Pi$ (Fig. 9, a). By moving all the checkers “in single file” along $\Pi$, it is easy to ensure that the checkers $i, j, k$ and the empty cell $B$ are located as on figure 9, b. Now moving the checker $i$ to the empty cell $B$, we get the order $\{..., j, k, i, ...\}$ from the order $\{..., i, j, k, ...\}$ - the checker with the number $i$ is “bent” clockwise through two neighboring ones: $j$ and $k$.

It’s just as easy to make any checker “jump” over two adjacent ones counterclockwise. For example, in order for the checker $k$ to be “bent over” through $i$ and $j$ on figure 9, you must first move the checkers “in single file” along the path $\Pi$ to the position shown at figure 9, and then move the checker $k$ to an empty space $B$.

So, we have indicated a technique with which you can make any checker “jump” over the checkers standing on the path $\Pi$ next to it.

⟦folio 30⟧

7. All but two are in place!
Using this technique, it is easy to convert any arrangement of checkers into one of the two arrangements shown in Figures 10, a, b.

First of all, we will lead checker 2 along the path to checker 1. Jumping counterclockwise over two checkers as many times as necessary, we will bring it either to “its” place (next to the “one”), or to the neighboring one (between checker 1 and checker 1 there will be a certain checker i), - in both cases we will be left at the moment when the next jump would be over checker 1. If between the “two” and checker i will remain a “one”, let’s make it jump over two checkers (including through the “two”) clockwise - then the “two” will be cleared next to the “one” (and on the right side).

Then, in the same way, we will lead the “three” to the “one” and “two”. Then “four” - to “one”, “two” and “three”. And so on - up to checker 13.

After this, moving all the checkers “in single file” along P, we will arrive at one of the two locations shown in figure 10.

8. Good and flat locations
All checker arrangements were thus divided into two classes. Locations of the 1st class can be translated into the same as at figure 10, a, locations of the 2nd - into the same as at figure 10, b.

Let's think about why the statement made in paragraph 5 follows from here, and what else follows from here.

If a certain arrangement P can be translated into an arrangement Q, then vice versa, Q can be translated into P. Therefore, all arrangements of the 1st class can be translated into each other. According to paragraph 4, the corresponding permutations are of the same parity, and odd, since the location on figure 10, and corresponds to an odd permutation

1, 2, 3, 4, 5, 10, 11, 15, 12, 9, 6, 7, 8, 13, 14 (thirteen disorders).

All arrangements of the 2nd class are translated into each other in the same way, and even permutations correspond to them.

Thus, the “normal” location belongs to the 1st class, and the location at figure 2 – to the 2nd. We call the 1st class locations good and the 2nd class locations bad.

Let us summarize what has been proven.

Good arrangements are those and only those that correspond to odd permutations, all of which can be translated into the arrangement depicted in figure1.

All other arrangements are flat, they correspond to even permutations, they cannot be transferred to the arrangement shown in figure 1, and can be transferred to the arrangement shown in figure 2.

Comment. The messages given in paragraph 6 and paragraph 7 will actually allow

⟦folio 32⟧

any permutation of the numbers 1, . . ., n, you can go to any other permutation of the same numbers, swapping places with just a few neighboring numbers.

5. Two-story game in 31. In a box with dimensions $2 \times 4 \times 4$ we put 31 cubes “in 2 floors”: 16 cups at the bottom, 15 at the top. We will leave one place in the box empty.

We will write the numbers on the cubes: 1, . . ., 31, and on each cube we write its number twice: on the top and bottom edges.

We will make the bottom and lid of the box air-tight and make holes in front of each cube (so that the cubes do not pass through them, but they can be easily moved without removing them from the box). Now the box can be rearranged as desired: it no longer has a “constant top” and a “constant bottom.” The cubes can be mixed on each floor and moved from floor to floor.

The result was a “two-story game of 31.” Develop a theory for this game.

6. Playing 15 on a cylinder. We cut the hollow cylinder (Fig. 12) into 16 curved pieces, one each, making 4 vertical and 3 horizontal cuts. Let's throw away one checker. We change the rest of the numbers 1, . . ., 15 and place it in a special box in the shape of a cavity between two cylinders. Let's make 16 holes in the outer hole cylinder - the “game of 15 on the cylinder” is ready (Fig. 13).

As in a regular game of 15, checkers are allowed to be moved one at a time to an empty adjacent space; in addition, it is allowed to simultaneously rotate 4 checkers (Fig. 14), like bypassing a ball bearing.

Is it possible to convert any arrangement of checkers into any other?

Comment. It is not necessary to make the box and checkers cylindrical. It is possible to use the normal game in 15, by additionally allowing "cyclic row cdvs" (Fig. 15): for example, "cyclic cdvgs of the 1st row" translates the layout depicted at figure 15, and into the layout depicted at figure 15, 6.

After it, the replacement will help you cope with control 6 and will make it easier for us to formulate the next task.

⟦folio 33⟧

7. Game of 16 on a torus. To make a cylinder out of a rectangle, you need to glue the opposite vertical edges together. If you then glue the opposite horizontal edges (Fig. 16) together, you get a mop (donut surface).

To make a “game of 16 on a torus”, it is not necessary to cut checkers from a donut. In a normal game of 15, it is enough to fill the empty cell with a checker number 16 and cut the “cyclic cdwgi and rows and columns” (Fig. 17).

a) Is it possible to translate the arrangement shown on figure 18, a, into the arrangement shown on figure 18, b?

b) Can any location be converted to any other?

b) Solve the general problem of playing $n^2$ on a torus.

This article was already prepared for publication when the editors of «Kvant» received a letter about the game at 15 from a schoolboy - tenth
