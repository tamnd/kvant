---
id: 1987-7-dubrovskiy-perevertyishi-6168e4f1
issue: kvant_1987_7
year: 1987
number: "7"
title: Changelings
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 56
page_last: 59
page_labels: 54, 55, 57
tag: 3PHZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 92a8f21fc543caa92034300553d39d7e67d2c68f4a68fcd1de8400a3630227e4
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/16_dubrovskiy-perevertyishi-6168e4f1.md
source_content_sha256: 421ff9818d4d2dc3ed8571fa869daa823fb2860fd70e52f35dc3e3390f3ac490
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

Changeling

Candidate of Physical and Mathematical Sciences
V. N. DUBROVSKY

Revealing the secret to solving a puzzle is as dishonest as telling an avid fan of a soccer match before its television broadcast the next day. Therefore, in our coloring book about two “reversal” puzzles, familiar to the reader from the covers of the 1st and 2nd issues «Kvant» for this year, there will be more questions than answers. But before asking and answering questions, let us remind you how these puzzles work.

In one puzzle, 8 cubes of size 1x1x1, identically colored in six colors, are placed next to each other in a square box of size 3x3 (Fig. 1). In another puzzle, together with cubes, 23 identical paramidics (regular notebooks) are taken with the vertices painted in four colors (Fig. 2,a), which are placed in a box shaped like a regular hexagon with sides twice as large as the edges of the paramidiki (Fig. 2,b). In both puzzles, one place is empty - a “hole”, which allows you to rearrange elements (cubes and paramidics) by rolling them over an edge. The problems we will discuss sound different for the two puzzles. Paramaidiki must be learned to be transferred to the “correct” or “initial” position shown in figure 2, b, after it has been destroyed by arbitrary rolling. The cubes have many correct positions (what these are is clear from figure 1; check that there are 24 correct positions); it is necessary to transform one of them into another. But both of these problems are special cases of a problem common to all “permutation” puzzles: for any two arrangements of elements, find out whether one translates into the other, and if so, how.

Cubes

Let's try to come up with operations that would rotate the cube while leaving it in place - then it will be possible to rotate all the cubes one by one. Let's put only one cube in the box and roll it along a 2x2 square around one of the vertices of base A (Fig. 3). When it returns to its place, we will see that it has rotated relative to its original position by 120° near the diagonal emerging from vertex A. In the same way, you can roll 3 cubes around the square - whole: after four moves, the hole will return to its place, and the cyclic cubes will be rearranged (Fig. 4) - this operation, when the rearrangement occurs counterclockwise around point A, is denoted by C_A. It is clear that the operation C^3_A (repeated C_A three times) returns all 3 cubes to their original places, each of them being rotated 120° around its diagonal emanating from A (see Fig. 4). To rotate these cubes in the opposite direction, you need to perform the reverse operation C^-3_A =

⟦folio 55⟧

$$= \left( C_A^{-1} \right)^3,$$
where $C_A^{-1}$ is a clockwise traversal of the hole around the point $A$.

So, we can rotate the cubes in their places, but so far only in groups of 3. Now it is not difficult to come up with operations that would rotate only one cube. A field of size $3 \times 2$ cells is enough for them. Let the free cell be located at the top (Fig. 5), it belongs to two squares $2 \times 2$ with centers $A$ and $B$. Operation $C_A$ does not affect the two right cubes, and operation $C_B$ does not affect the two left ones, therefore operations $R_1 = C_A^3 C_B^3 C_A^{-3} C_B^{-3}, R_2 = C_A^{-3} C_B^3 \times C_A^3 C_B^{-3}$) and similar ones (see problem 1) routinely leave these 4 outer cubes motionless; the fifth cube (let’s call it “side”), as you can check, rotates in both cases by $180^\circ$: with $R_1$ - around an axis parallel to $AB$, with $R_2$ - around a “horizontal” axis perpendicular to $AB$. An operation of the form $[X, Y] = XYX^{-1}Y^{-1}$ is called a commutator of operations $X$ and $Y$. Switches prove to be very useful in all swapping puzzles; there are, for example, algorithms for solving the Rubik's cube, entirely based on commutators (see the article by V. and S. Zalgallerov “The Hungarian hinged cube” in «Kvant» No. 12 for 1980).

Exercise
1. Consider all possible operation switches $C_A^{\pm 3}, C_B^{\pm 3}$. Show that they all act like $R_1$ or $R_2$ or like $R_1 R_2$ (rotating the cube by $180^\circ$ about a vertical axis).

2. Show that there are 24 ways to place a cube on a given square; of these, only 12 can be obtained from the initial position by rolling along a closed route, and of these 12 only 4 are obtained

*) The order of operations is from left to right; for example, for $R_1 = C_A^3 C_B^3 C_A^{-3} C_B^{-3}$, operation $C_A^3$ is performed first, then $C_B^3, C_A^{-3}$, and finally $C_B^{-3}$.

Fig. 3.

Fig. 4. Blue arrows show the movement of the cups during operation $C_A$, red arrows indicate the rotation of the cups during operation $C_A^3$.

Fig. 5.

under the action of commutators $[X, Y]$, where $X$ and $Y$ are arbitrary operations that return the cube to its original place. Come up with the shortest chain of moves when the commutator performs operations $X$ and $Y$. Switches prove to be very useful in all swapping puzzles; there are, for example, algorithms for solving the Rubik’s cube, entirely based on commutators (see the article by V. and S. Zalgaller “The Hungarian hinged cube” in «Kvant» No. 12 for 1980).

So, we have learned how to rotate 4 “side” cubes. To rotate the corner cube, it is enough to put it in place of the side one, apply the operation $R_1$ or $R_2$, and then return it back: for example (see Fig. 5), the operation $R_2' = C_A R_2 C_A^{-1} = C_A^{-2} C_B^3 C_A^{-3} C_B^{-3} C_A^{-1}$ rotates the lower left cube by $180^\circ$ around the “horizontal” axis, repredicular $AB$ (a similar operation for the lower right make the cube yourself).

Now we reduce all the cubes, but probably not in the shortest way (the number of moves we have is 8·48=384): after all, each cube is rotated separately and also remains in place, which is not necessary*).

*) For the case when the empty space is not in the center, but at the bottom left, A.V. HodULEV came up with a solution of 100 moves, and the cubes are rotated here not by $180^\circ$, but by $90^\circ$: $JH^2 \Pi B^2 \Pi H(\Pi B J H)^3 H J B^2 \Pi H(J B J H)^2 H J B J H^2 B^2 J^2 H^2 J B J H^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2$.

*) For the case when the empty space is not in the center, but at the bottom left, A.V. HodULEV came up with a solution of 100 moves, and the cubes are rotated here not by $180^\circ$, but by $90^\circ$: $JH^2 \Pi B^2 \Pi H(\Pi B J H)^3 H J B^2 \Pi H(J B J H)^2 H J B J H^2 B^2 J^2 H^2 J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2$.

Fig. 5.

⟦folio 57⟧

Jan Heveli

(For the beginning, see p. 53)

astronomical instructions. The fire also destroyed all his property. But he bravely endured this misfortune and, at the first retribution, resumed his research.

Today we know much more about the Moon than in the time of Hevelius. The relief of its reverse side was photographed and studied in detail. Spacecraft examined its surface and brought us samples of ray soil. More astronauts have been to the Moon.

On the second page of the cover, a fragment of the map of the Moon is reproduced, which depicts a section of the reverse side adjacent to the Moscow Sea (the diameter of this sea is 460 km). It was first discovered in photographs taken by the Soviet automatic international station Luna 3 in 1959. In 1961, the International Astronomical Union approved eighteen named objects on the far side of the Moon, and the middle ones - the Sea of ​​​​Moscow. Below them, even more patiscot was added, called details of the lunar relief of the far side of the Moon. The International Astronomical Union has approved the named objects on the far side of the Moon. The International Astronomical Union approved the named objects of the far side of the Moon, and the technical details of science and technology - Lomonosov, Tsiolkovsky, Korolev, Lebedev, Mandelstam, Kurchatov, Artsimovich, Pasteur, Curie, Fermi and many others. The archery nomenclature also included the names of deceased cosmonauts - Komarov, Volkov, Dobrovolsky, Patsaev, Grissom, White, Chaffee. In the vicinity of the Moscow Sea there are craters named after Soviet cosmonauts Titov, Nikolaev, Tereshkova, Belyaev, Leonarov, Shatalov, Feoktistov. They are clearly visible on the fragment of the lunar map shown on the second page of the cover. In the area of ​​the Apollo Basin and the Sea of ​​Tranquility, six craters bear the names of American astronauts - participants in lunar expeditions. These are the craters Armstrong, Aldin, Collins, Anders, Borman and Lovell.

Zh. F. Rodionova, V. A. Leshkovtsev
