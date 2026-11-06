---
id: 1991-6-dubrovskiy-kommutativnaya-golovolomka-erne-rubika-ffda7f22
issue: kvant_1991_6
year: 1991
number: "6"
title: Erne Rubik's commutative puzzle
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 62
page_last: 65
page_labels: 60, 61, 63
lang: en
source: kvant_digital
extraction: vision
content_sha256: e0fecfc626d4fac596ce6c29fa8e331941d8e459f1bb0c4e541a4f28af0db2f2
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/18_dubrovskiy-kommutativnaya-golovolomka-erne-rubika-ffda7f22.md
source_content_sha256: f158af4b8f0376a4fde9bbebf5278a743fc052ab87e25433b89cf23d7fbaca25
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 60⟧

---
running_head:
folio:
---

Commutative
puzzle
Erne Rubik

Last year we introduced readers «Kvant» to the “Rubik clock” (see page 4 of the cover of issue 4). Although this puzzle was patented by the famous inventor in 1988, it is still little known among us (and, perhaps, it will remain so). However, we received letters asking us to fulfill the promise we made almost a year ago and tell us more about the “watch”. We hope that our story will be of interest to all lovers of puzzles, and not just the few owners of the “Rubik’s clock,” especially since this puzzle is both structured and solved easier than, say, the “magic cube,” and therefore, having understood how the “clock” works, you can try to come up with an algorithm “at the tip of the pen.”

Figure 1 shows what a Rubik's clock with two

On each side of the round case there are 9 windows with rotating dial circles on which arrows are drawn. There are 4 gears protruding from the side of the body, which can be rotated to move the arrows. A hidden gear mechanism—the “gearbox”—allows different sets of dials to be connected to the rotation. The “gearbox” is controlled by buttons; There are 4 of them on each side of the case, but in fact there are 4 rods protruding from both sides: if you press the rod on the front side, it will pop out from the back, and vice versa. The problem is set in the same way as for the “cube” and many other similar puzzles - having “confused” the clock readings, you need to return them all to the “correct” state, namely, set them to 12 o’clock.

Before solving this problem, it is necessary, of course, to understand how the “clock” is controlled, which hands are connected to the rotated gear when using one or another variant of pressing the horse-horses (“gear”). Anyone who has a puzzle must simply try all the options. For the rest, we suggest you immediately look inside the “clock.” On figure 2 you see that the driving (corner) gears protruding from the body have 2 dials - on the back and front sides; Also, paired dials always rotate synchronously. This six is ​​with the six on the nearest button, and it, in turn, is connected either with the sixes of the three adjacent rear dials (central and two side), if the button is pressed, or with the crown of the corresponding dials on the front side, if the button is pressed. With these gears, depending on the “gear,” the rotation can spread even further. Obviously, interlocking dials can only rotate simultaneously, in one direction and at the same speed. We can say that the “Rubik's clock” has 14 “degrees of freedom”, corresponding to 4 corner dials and 10 more single dials, each

⟦folio 61⟧

---
running_head:
folio:
---

Fig. 2. “Rubrik Watch” in section (with a plane passing through the axes of the corner and central dials): a) a pair of corner dials mounted on the drive gear, b) a button with a gear for reversing gears, c) the front central dial, d) the tilny central dial, e) the puzzle body.

of which, in principle, can be turned independently of the others. Therefore, the number of different arrow arrangements does not exceed $12^{14} \approx 1,28 \cdot 10^{15}$. We will see later that all these expansions can indeed be obtained.

Now let's see what options we have when translating the arrows. Each of the buttons can be in two positions, so there are $2^4 = 16$ “gears” in total in the puzzle. Whenever you press the buttons, you can distinguish two groups of dials connected to each other: one includes angular pairs and face dials surrounding the unpressed buttons, the other is determined in the same way only if you look at the “clock” from the back side. Each pair of corner dials will necessarily fall into one of the groups, but non-rotary “single” dials may not be linked with others. Thus, given the position of the buttons, there are, generally speaking, two ways to rotate the arrows - you can rotate any of the two groups. But in two cases - when all the buttons are pressed or released - only one group is formed, so the total number of rotation methods is $2 \cdot 16 - 2 = 30$. However, if we consider as equivalent those methods of rotation that are obtained from each other by rotating the puzzle in its plane or by turning it over, then only 5 equivalent options remain. All of them are shown on figure 3. (Check that there are 2 ways of rotation equivalent to option A, 8 ways each equivalent to B, C and E, and 4 ways equivalent to D.) If you turn the drive wheel to $360^\circ/12 = 30^\circ$, then depending on the “gear” engaged, certain dials (on figure 3 they are placed with arrows) turn to that same angle, i.e. for 1 hour. We will call such operations elementary; for the "gears" shown in figure 3, we will denote them corresponding to A, B, C, D, E. The result of the operation can be written using a table of zeros and ones:

$$
\begin{align*}
A &= \begin{pmatrix} 1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix}, \\
B &= \begin{pmatrix} 0 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix} \\
C &= \begin{pmatrix} 0 & 0 & 0 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix}
\end{align*}
$$

Fig. 3. Five fundamentally different gears of the “Rubik’s clock” (view from the front side): unpressed buttons are shown in yellow, pressed ones in black, the teeth are highlighted on the rotating gear.

⟦folio 63⟧

---
running_head:
folio:
---

3). Operation $t(A-B)$, where $t=0, 1, \dots, 11$, rotates the upper left pair of corner dials by $t$ divisions. Similarly, you can rotate the other 3 corner pairs separately. These operations are convenient to use at the end of a solution because they will not destroy what has already been achieved.

Now I would like to find a similar operation for the side dials. Moreover, it can also rotate the corner dials, because we will install them later anyway. You probably already found the answer:

$$A-C = \begin{pmatrix} 1 & 1 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}.$$

This operation moves the top hand on the front line (and the adjacent corner hands) forward 1 hour. It is clear that the puzzle can be rotated so that any of the 7 other side dials are on the “top face” position.

So, we have 8 equivalent operations for installing side dials and 4 for corner dials. Let's add two more operations to them for the central dials, for example, $A$ and a similar “rear” operation. The result is 14 operations, which are enough to solve the puzzle (remember the system of 14 equations!). You can do this:

1) by operation $A$ (more precisely, $tA$, where $t=0, 1, \dots, 11$) we set the central hand of the front side to 12 o’clock;
2) using operations of the form $t(A-C)$ we set the front side arrows (the central one remains motionless);
3) turn the puzzle over and repeat the first two steps;
4) Using operations of the form $t(A-B)$ we set the corner arrows.

It would be possible to end here, but our algorithm allows for improvement, or rather, it can be shortened. If we consider as a “move” the rotation of one of the gears with a fixed “gear”, then the number of moves for the 1st step is 1, for the 2nd - 2·4=8 (for each tract dial there are 2 moves - $tA$ and - $tC$), for the 3rd - another 1+8=9, for the 4th - 2·4=8, and in total - 26. But after all, we used only 14 different elements of operations ($A, B, C$ and the puzzles resulting from them by rotation), which means that by changing their order, we can reduce everything to 14 moves. Here's how it's done:

1) using an operation of the form $tC$ we set the central front arrow parallel to the top front one; turning the body by $90^\circ$, we repeat this procedure 3 more times - as a result, 5 arrows (central and side) on the front side will become parallel;
2) using an operation of the form $tA$ we set these 5 hands to 12 o’clock;
3) turn the puzzle over and repeat step 1;
4) using an operation of the form $tC$ (on the back side!) we set all 5 non-corner arrows parallel to the upper left corner and repeat this 3 more times, turning the puzzle by $90^\circ$ - as a result, all 9 arrows will become parallel;
5) Using operation $tA$ (again on an inverted puzzle, i.e. on the back side) we set all hands to 12 o’clock. All.

Let us conclude with a few more comments. It is clear that our algorithm allows us to obtain any of the $12^{14}$ possible arrow arrangements. In this case, we use 14 moves, each of which is a repetition (from 0 to 11) of one of the 14 elements of operations $A, B, C$ and equivalent ones. Taking into account commutativity, there are only $12^{14}$ different combinations of these operations. This means that they are all different and only one such combination corresponds to each arrangement of arrows.

So, if the operation is only the 14 operations we have identified, we can say that

You can move from any arrangement of arrows to any other without
