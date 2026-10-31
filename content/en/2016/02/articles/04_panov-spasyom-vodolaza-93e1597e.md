---
id: 2016-2-panov-spasyom-vodolaza-93e1597e
issue: kvant_2016_2
year: 2016
number: "2"
title: Let's save the diver
authors:
  - Панов А. А.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 43
page_last: 45
page_labels: 41-43
tag: IMEB
lang: en
source: kvant_digital
extraction: native
content_sha256: c9a5a6f57e4b4c71b4ebb2cee6b8dc4b164ff994fe328f0d4df90d8f90c1c0eb
prompt_sha256: draft-1
translated_from: content/ru/2016/02/articles/04_panov-spasyom-vodolaza-93e1597e.md
source_content_sha256: 0ca8abfe9371c10aee9d2a3c9e46fb78e70ed61dd6537c5bd535a842da7d5c5f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

LABORATORY

Let's do this for all the cells corresponding to the numbers in the left column, and cross out the marked rows (they will all be different, since exactly one cell is selected in each). Since we will not cross out everything, we will be left with a “board” of 8 rows - say, k columns and 8 - k rows. Its area is then equal to k ◊ (8 - k), which is no more than 16. This means that the total number of selected cells was no more than 16 + 8 = 24. A contradiction. 2 (solution 6, variation of solution 5). First, let's mark arbitrary 32 cells, numbered with different numbers. We will call unselected cells “free”, and lines (rows or columns) where all cells are free - empty. Let's say that some line, for example the first line, is empty. Therefore, there are 8 different numbers in it, and 8 cells with corresponding numbers are marked in other lines. We argue that one of these 8 numbers is not unique either in its row or in its column, and therefore it can be replaced by an equal number from the first row without “nulling out” the other rows or columns, i.e. reduce the number of empty lines. In fact, on the entire board, except for the first row, only 24 squares are free. Therefore, there are no more than three rows in which one of the 8 numbers stands “alone”, and no more than four such columns. Therefore, no more than seven numbers are alone in their row or column, and at least one of our 8 numbers can actually be replaced. If after this there are still empty rows or columns, proceed in the same way.

3 (solution 7). There are $2^{32}$ choices of 32 cells with different numbers on them (from each pair of cells numbered the same, you must choose one). Let's estimate the number of bad choices. Let there be no selected numbers in the first column. This means that all the numbers in it are different, so there are $2^{24}$ such choices. There are 16 rows in total, so the total number of bad choices is no more than 16 ◊ $2^{24} = 2^{28} < 2^{32}$, i.e. there are many good choices.

P.S. Let's try to slightly change the condition of the original problem. Let us now have 16 numbers written in 64 cells, each 4 times. The question arises: “Is it now possible to be guaranteed to mark one cell with each number so that in each horizontal and in each

"QUANTA"

⟦column⟧

was at least one cell marked on each vertical?” And if possible, which of our solutions go into the new problem? It turns out that this fact will also be true. For example, an obvious solution arises, similar to solution 3. Each number girl will have a power of 8, since it occurs 4 times and is taken into account each time in 2 rows, while it is possible that we have taken into account some friendship up to 4 times if the number appears four times in one row. From Hall's theorem it follows that we have the required 16 weddings. How simple and beautiful everything turns out to be! And if you think about solution 2, then... the great Euler will appear here! In our graph, every vertex now has degree 4, possibly with multiple edges and loops. Then each connected component will consist only of vertices of even degree, which means that the Eulerian criterion is satisfied - each connected component will have an Eulerian cycle, i.e. a cycle that traverses all edges once, with each vertex in the cycle present twice and each Eulerian cycle of even length. This means that in each of these Eulerian cycles it is possible to color the edges in a checkerboard pattern (white, black, white, black, etc.). As a result, for example, in the graph of black edges, each vertex will have degree 2, and here the round dance lemma will work, according to which the graph of black edges is divided into one or more disjoint cycles, in which we, by analogy with solution 2, will arrange the traversal we need. Thus, we have already proven a stronger fact that in each row there will be at least 2 marked cells. How useful it is to change the condition of the problem! Other beautiful ideas will immediately pop up!

LABORATORY "QUANTA"

Let's save the diver

A.PANOV

SEVERAL YEARS HAVE PASSED SINCE THE PUBLICATION OF THE ARTICLE “K artesian diver – generation P” (see «Kvant»

No. 2 for 2012). During this time, I learned several new things that I want to share here. And I also want to correct one mistake. It turns out that the inventor of the Cartesian diver was not Descartes at all, but, most likely, the Italian monk Raffaello Magiotti (Raffaello Magiotti, 1597–1656), a follower of Galileo and friend of Torricelli. In 1648, Maggiotti published a treatise on the incompressibility of water; he used a diver to illustrate this incompressibility. Look at figure 1 (as well as on the 4th page of the cover), where Maggiotti’s author’s figure are reproduced - you will definitely recognize the two divers there.

“Le caraffine di Magiotti” is the name of the text written by Beniamino Danese and located on the website http://www.reinventore.it/. From Italian this name is translated very simply - “Bottles (or decanters) of Maggiotti.” In addition, the site has a 12-minute video (a frame from it is shown on figure 2). I watched it several times with great pleasure and I advise everyone to do so. Although last time I recommended using a regular pipette as a diver, after watching the movie I decided to return to classic glass apothecary bottles. So, let's fill a plastic bottle with water, and then... ...The bottle, partially filled with water, will be lowered upside down into the bottle. In this case, the amount of water in the bottle should be adjusted so that it has a slight positive buoyancy - with a weak push it should go under water. Now we screw the plug tighter, and the diver is ready for action. When you press on a plastic bottle, the volume of air inside the bottle decreases, and the bottle lowers -

⟦folio 42⟧

KVANT 2016/№2

⟦column⟧

⟦figure⟧

Fig. 2. Still from the film by Beniamino Danese

⟦figure⟧

Fig. 1. Maggiotti bottles

going down. Let go of the bottle - the diver floats upward... This is actually a small quote from the previous article. Now let's do some new experiments.

We will rescue the diver. It can be a shame when a diver, lowered into a bottle, immediately goes to the bottom. You have to empty the water from the bottle, get the diver out and set him up again. Let's try to do without this - save the diver and force him to climb up on his own. This can be done in several ways. Method 1: let's warm it up. Let's say a diver finds himself at the bottom and doesn't want to rise. Unscrew the cap and place the bottle with the diver in hot water. The water in the bottle will warm up, the volume of air in the bottle will increase, and the diver will float to the surface. True, when the water cools, the diver will drown again. Method 2: inhale. Let's try to do something like artificial respiration. Let's wrap our lips tightly around the neck of the bottle and inhale some of the air contained there. The pressure in the bottle will decrease, the volume of air in the bottle will again increase, and the diver will emerge. But even here, as soon as we take our mouths away from the bottle, the diver will drown. Method 3: raise. When I was given a barometer for the first time, I immediately climbed into the elevator with it and went to the top floor. The barometer needle, of course, showed that air pressure decreases with altitude. Let's take advantage of this fact and take the drowned diver in the open bottle with us into the elevator. If you rise high enough, the air pressure will decrease significantly, the air inside the bottle will expand so much that the diver will acquire positive buoyancy and rise upward. Method 4: squeeze. Let the diver find himself at the bottom and not want to rise. Unscrew the cap and squeeze the bottle with one hand so that more air comes out of it. Without reducing the compression, screw the plug with the other hand. After we let go of the bottle, elastic forces will begin to work, trying to return it to its previous shape. They counteract external air pressure and increase the volume of the bottle, including the volume of air in the bottle. The diver acquires positive buoyancy, floats to the surface and becomes ready for work.

One? Two? Three! Why does it sometimes happen that a bottle floats in a glass, but if you throw it into a bottle, it sinks? Because you don’t need to throw it, but carefully and slowly lower it into the bottle, then it will float at the top, just as it did in the glass. But the fact of drowning itself is quite interesting. Not every diver floating on top will drown if pushed down. This is only possible if it has low positive buoyancy. The fact is that when a diver goes down, the hydrostatic pressure of the liquid on him increases, the volume of air inside the bottle decreases, and the diver’s buoyancy also decreases. And if the bottle is high enough, then at a certain height the buoyancy will become negative, and the diver will sink by himself. It turns out that a well-adjusted diver with low positive buoyancy has two stable equilibrium positions inside the bottle. One when the diver is in the top position, and another when he is at rest on the bottom. If he is in one of these states, then after a small disturbance he will return there. Moreover, in the upper position its buoyancy is positive, in the lower position it is negative. But then it turns out that at some intermediate height the diver’s buoyancy should be equal to zero. And this is another balance position for the diver. Only, unlike the first two, it is unstable. If the diver moves upward slightly from this position, he will have positive buoyancy and will continue his accelerating ascent. If it deviates slightly downwards, it will develop negative buoyancy and will sink.

⟦folio 43⟧

LABORATORY

⟦figure⟧

Fig. 3. Press this way (as shown on the left), and the diver drowns, press differently (as shown on the right) - he floats up

⟦figure⟧

Fig. 4. We compress it this way (as on the left), and the cross-sectional area decreases; we compress it differently (as on the right) – it increases

Double action diver. It would be nice to have a diver who, at our request, would sink to the bottom and remain there or, if desired, would rise to the top and swim there. Here are some ways to achieve this. 1: screw/unscrew. Let's place a diver with low positive buoyancy in a bottle. Let's start screwing the plug. Its connection to the bottle will become airtight even before the cap is completely screwed on. From this moment until the cork is completely screwed in, the volume contained inside the bottle will begin to decrease. The volume of air inside the diver will also decrease, and the diver will drown. Unscrew the plug and the diver will rise. This is the first example of a double action diver. 2: squeeze and squeeze. There are bottles with an oval section (Fig.3). If you cut such a bottle with a horizontal plane, then the cross-section will look something like the one shown in figure 4. Let’s put a diver with low positive buoyancy and two states of stable equilibrium into such a bottle. If you press on the flat sides of the bottle (see Fig. 3 and 4, left), its cross-sectional area will decrease, which means the volume will decrease, and the diver will sink to the bottom. If you now press on the rounded sides (see Fig. 3 and 4, right), the volume will increase and the diver will float to the surface. 3: put on the clamp. Take a large diameter worm clamp that can be attached to a plastic bottle (Fig.5). Let's place a positive buoyancy diver in the bottle, screw on the cap and use a screwdriver to begin tightening the clamp. The air pressure inside the bottle will increase, and at some point the diver will sink to the bottom. And this process is reversible. If you loosen the clamp, the diver will rise to the top.

"QUANTA"

⟦column⟧

⟦figure⟧

Fig. 5. Bottle with clamp, very convenient for diver to control

4: Let's knock. Anyone who has already tried to create a diver with minimal positive buoyancy, having two stable states of equilibrium - at the top and bottom of the bottle, knows that this is a difficult task. This requires preliminary fine-tuning of the ratio of water and air inside the diver. Using a worm-drive clamp simplifies this problem. Let's place a positive buoyancy diver in the bottle and tighten the cap. Now we will slowly begin to tighten the clamp until the lower position of the diver “for the first time” becomes stable. Such a diver will have two stable states - above and below, and between them (at a low altitude) there will be an unstable state of equilibrium. By squeezing the bottle we will lower the diver to the bottom. If you now hit the bottom of the bottle on the table, the diver will jump up, as if on a trampoline, rise above the unstable equilibrium position, after which he will acquire positive buoyancy and rise to the top. Here's another double action diver for you. Instead of knocking the bottle on the table, you can hit the table with your fist - the effect will be the same. 5: let's raise it. Of course, banging your fist on the table is too harsh. Let's act more delicately. As in the previous case, let's create a diver with three equilibrium positions. Squeezing the bottle will send the diver to the bottom. Now let's grab the cork and lift the bottle - the diver floats to the surface. It turns out that the force of gravity, uncompensated by the reaction of the table, increases the volume of the tall round bottle, and the air pressure in it drops. 6: tilt. Let's again create a diver with three equilibrium positions and lower him to the bottom. It will be there in a state of stable equilibrium. We strongly tilt the bottle so that the height of the water column above the diver is significantly reduced. At the diver's level, the water pressure will decrease, the air in it will expand, and it will begin to rise. At some point we place the bottle vertically and the diver will be at the top. That's probably all. I’ll also add that my student Dima Gulyev taught me how to equip a diver with a worm clamp. I think this is a very good idea.
