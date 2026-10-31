---
id: 1974-9-klumova-igra-zhizn-9f98742a
issue: kvant_1974_9
year: 1974
number: "9"
title: Game of Life
authors:
  - Клумова И. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 32
page_labels: 26-30
tag: BQX2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0fb119a3ec32bf254ae87c5c5b6d9ca5967fe1cfce3d5d03d966e7549877120c
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/09_klumova-igra-zhizn-9f98742a.md
source_content_sha256: 7e7b5faee20c6ceb47260e5e3721d8abd65580330989c230a7824950daa5e89d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Game
"Life"
I. N. Klumova

- Or maybe you disappear and appear not so suddenly? - asked Alice. - Let’s go around in a circle.
“Okay,” said Kom and disappeared—very slowly this time. The first to disappear was the tip of his tail, and the last was his smile. She hovered in the air for a long time, when everything else had already flown.
“Y-yes,” thought Alice. “I’ve seen coms without smiles, but a smile without a com!” I have never seen anything like this in my life.
Lewis Carroll. "Alice in Wonderland."

In the October 1970 issue of Scientific American magazine, a description of the most fascinating game, “Life,” invented by the modern American mathematician John Horton Conway, appeared. It is beautifully described in the book of the famous American specialist in the field of intriguing mathematics M. Gardner. This game is very different from all the others; Only a computer makes it possible to fully experience how unusual and beautiful this game is.
You can play the game “Life” alone, without a partner. For an attentive and already very experienced player, it is enough to have a large sheet of checkered paper and a pencil to make moves. But for a beginner in the game, it is better to stock up on a dock, divided into squares, and chips of their colors, for example, black and white (both the sheet and the board are considered infinite).

Rules of the game
The idea of ​​the game is to start with some simple arrangement of black pieces (“organisms”) on the board, and see what will happen to this initial position (“column”) under the influence of Conway’s “genetic laws.” “Genetic laws” are the rules of the game; they govern the separation and death of chips on the board.

Note that each cell of the dock can be in one of two states - either it is empty, or there is one black chip on it - and that it has eight neighboring cells (four have common sides with it, and another four have common vertices). We will call the column that receives from the previous one as a result of one move the next generation. Let us now formulate the rules of the game, that is, we will determine when a piece “dies”, when it is “born” and when it “survives”.

The piece survives (remains on the board in its place) and goes to the next generation if it has two or three neighbors of the piece.

A piece is destroyed - removed from the dock - if it has more than three or less than two neighbors (matching due to mobility or loneliness).

A chip is born in some cases, if the cells have neighbors with this empty cell, it is worth checking three chips. The processes of “birth” and “death” will occur simultaneously.

Conway recommends making moves as follows. Determine which chips you should receive and put one more black chip on each of them. Then determine in which cells the chips should be “born” and place a white chip in each such cell. Carefully check again whether everything has been done correctly (it’s very easy to make a mistake, especially if you’re playing for the first time), and then remove all the columns of black chips from the dock, and replace the white chips with black ones - this will result in the next generation of the original colony (for this we need chips of two colors).

Once you start the game, you will discover that the original column can undergo the most unexpected and sometimes very beautiful changes. Sometimes the column dies out (all cells disappear from the dock); This may not happen immediately, but only after many generations have passed. But most often, the initial configurations either turn into stable ones, that is, they rearrange the changing generalities (Conway calls them “lovers of capable life”), or “enter the oscillatory mode,” that is, experience a cycle of transformations with a certain period. In all these three cases, the evolution of the configuration is considered complete.

Origin of "species"
Let's see what happens with some simple configurations.

⟦folio 27⟧

One or two chips always die after the first move. A configuration of three chips (Conway calls it a triplet) most often dies. figure 1 shows five triplets. The first three die already on the second turn. Triplet (2) goes into a stable configuration of four chips, called a “block”. Triplet (3) Conway calls a “mtsalka” - it turns alternately into a vertical row, then again into a horizontal row.

Let us also note that any diagonal row of chips gradually dies out: with each move, the number of chips on the board decreases by two (“the outermost chips die”).

figure 2 depicts the evolution of a terramino heel, which is what Gardner calls a configuration of four squares connected by the move of a rook. Configuration (a) is already known to us - this is a “block”, terramino (b), (c) and (2) also goes into a stable configuration called a “hive”: (b) and (c) - on the second move, and (2) - on the third. Configuration (δ) is called “navigation axes”; it is substitutive in that on the ninth move it breaks up into four separate “flashing lights”, the further transformation of which into

Fig. 1. Evolution of the heel of triplets

Fig. 2. Evolution of the Terramino heel

⟦folio 28⟧

Fig. 3. Stable configurations

Fig. 4.

Fig. 5. “Glider”

actually resemble the “effectiveness” of traffic lights.

figure 3 depicts the eleventh most common stable configurations - “lovers of a quiet life”.

Task 1. There are two eleventh configurations of a heel of cells connected to each other by the move of the rook (“pentamino”). The most difficult of them is the pentamino in the shape of the letter g (Fig. 4 a). This configuration becomes stable only after the one thousand one hundred and third move, breaking up into eight “blocks”, four “flashing lights”, four “hives”, “loaf”, “boat” and “ship” (see Fig. 3!) It would, of course, be impossible to achieve this result without a computer; At the same time, the calculating machine must have a device that allows output data to be displayed on the screen - only then will we be able to observe all the changes occurring on the board. Try to figure out what will happen with the rest of the same configurations.

Task 2. Find out the fate of the configurations depicted in figure 4b-e.

Let us only note that if the evolution of the letter N ends quickly, then the letter P (or “gate”), unexpectedly, turns out to be “long-lived” - only after 173 moves it breaks up into a heel of “flashing lights”, six “blocks” and two “ponds”!

figure 5 depicts the fiche heel configuration, which Gardner considers one of the most amazing discoveries of the Game of Life; Conway called it a "glider." The remarkable thing here is that the “glider” is a piece that actually moves around the board (“flying”): after the second move, it “enters a picque”, and on the fourth move it turns into itself, moving one square to the right and one down relative to the initial position. In the Game of Life, the speed at which

⟦folio 29⟧

Fig. 6. “Spaceships”

A chess king moves across the board, called the “speed of light.” This is due to the fact that high speeds are simply not achieved in this game: no configuration reproduces itself fast enough to move at such a speed. Conway's speed of movement of a figure is equal to a dubie, the denominator of which is the number of moves required to reproduce the figure, and the numerator is the number of cells on which it will be mixed. The speed of the "glider" (diagonally) is 1/4 the speed of light (check it out!). Conway proved that in Life such a speed (diagonally) would be maximum and that the speed of any finite figure, moving vertically or horizontally, could not exceed half the speed of light. figure 6 shows three "spaceships" (the "glider" being the "lightest" of all the "spaceships") moving horizontally at half the speed of light. “In flight, “sparks” fly out of them,” writes Gardner, “which then go out as the “ship” moves further. It turns out that “supercharged spaceships” (their horizontal row consists of more than six chips) already require an escort of two or more “ships”. Smaller sizes, otherwise small figures will appear on the board, interfering with movement. figure 7 depicts the heaviest of the “spaceships”, which has two accompanying lighter “ships”. As Conway calculated, a “ship” 100 cells long needs an escort consisting of thirty ships.

THE PROBLEM OF "GROWTH"

Please, the most difficult task of the game “Life” was the following: the essence of imitation is a finite initial column, the number of “organisms” of which would simply be infinite when passing from generation to generation.

After publishing his game, Conway promised a premio to anyone who found the answer to this question. The problem was solved in November 1970 by a group of mathematicians Massachu-Fig. 8. “Glider gun”

⟦folio 30⟧

I wish I could sow the field at the same speed with which the live animal harvests it.”
And finally, we note that the Game of Life is far from just a game; it rightfully occupied a prominent place in the “theory of cellular automata”, arousing the interest of many scientists dealing with the problems of using computers. “For example, the creation of a “glider gun,” writes Gardner, “opens up the exciting possibility of simulating in Conway’s game a Turing machine* capable (in principle) of voluntarily performing all the actions that are possible with the most advanced of modern computers.”
For readers interested in Conway's game, we offer a few more problems.
Task 3. What happens to horizontal rows of n chips when n=5, 6, ..., 9?
Task 4. How do the configurations shown in figure 11a, 6, 8 (“figure eight”, letter Z, two “gliders” flying towards each other) behave?

Fig. 9. “Cheshire Cat”

Fig. 10. “Reaper”

Fig. 11.

*) A Turing machine is an ideal automaton capable of arbitrary calculations, depicted by the English mathematician A. M. Turing.
