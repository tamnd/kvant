---
id: 1991-11-tomu-kto-lyubit-prekrasnoe-cfbbcae4
issue: kvant_1991_11
year: 1991
number: "11"
title: For those who love beauty
rubric: smes
page_first: 53
page_last: 56
page_labels: 51, 53, 54
lang: en
source: kvant_digital
extraction: vision
content_sha256: 959e0bf8e420290333a8d6f7be7c23333bbcdeb3ab27128f5c0cf30c7c510ebd
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/17_tomu-kto-lyubit-prekrasnoe-cfbbcae4.md
source_content_sha256: 2a35c44822c443bec385b3c7810cc3aa6a48656894814876b42200d7d156a542
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 51⟧

For those who love beauty

You can observe excellent systems if you make a spectroscope and use our colorographic diffraction gratings.

To receive a diffraction grating and instructions for assembling the spectrosock, send 6 rubles by postal order to the following address:

427600, Glazov, st. K. Marka, 27, PO Box 76, SIP “Arzon”.

Please clearly indicate the return address on the transfer bank.

⟦folio 53⟧

---
running_head:
folio:
---

them, and the third - the second. Now we can transfer $n$ of the upper disks from the first rod to the third by performing $2^n$ - 1 action. There is only one disk left on the first rod. Let's change it to the free second rod. Let's change the rods again: give the second rod number three, give the first one number two, and give the third one number one. Now we have $n$ disks on the first rod, the second is free, and the largest disk is on the third. It remains to transfer from the first rod to the third $n$ disks, which we can do in $2^n$ - 1 operation. We all collected all $n+1$ disks on the third rod, performing $(2^n-1)+1+(2^n-1)=2^{n+1}-1$ action.

From here, in accordance with the principle of mathematical induction, it follows that for any natural number $k$ it is possible, having a primuda with $k$ disks, to transfer them from the first rod to the third, free rule, in $2^k$ - 1 action.

The above proof is easy to formulate in the form of an action algorithm. It is precisely this algorithm that is offered to programmers in the mentioned books for writing it in one or another algorithmic language.

It is not difficult to show that in less than $2^k$ - 1 action it is impossible to transfer $k$ disks from the first rod to the third. Therefore, Legendary Priests will need $2^{64}$ - 1 action to use their work. If you spend only one second on each action, then it will take 18,446,744,073,709,551,615 s, i.e. more than 500 billion years.

Let's take a closer look at the process of transferring disks. To do this, we change them in ascending order: the first is the smallest, etc. Now we begin to transfer the disk in accordance with the algorithm and write down the numbers of the transferred disks:

1213121412131215121312141...

Interestingly, every odd transfer is a transfer of the first disk. Another observation: place the rods at the vertices of an equilateral triangle (Fig. 2) and follow the movement of the first disk. It turns out that he is moving in a circle in the same direction; Moreover, if the initial number of disks is even, then clockwise, and if odd, counterclockwise. These observations made it possible in 1961 to formulate the following disk transfer algorithm:

first we transfer the first disk, then not the first, then again the first, then not the first, etc., and the first disk is transferred in one direction: clockwise in the case of an even number of disks and counterclockwise in the case of an odd number.

Note that the indication “not the first disk is being transferred” completely determines which disk and where should be transferred at a given moment, since the smaller disk is always classified as a larger one.

Recently, a student from Perm, Misha Fedorov, proposed another algorithm that, like the one just described, transfers $k$ disks from the first rod to the third in $2^k$ - 1 action.

Misha introduces the concept of an “empty tower”. He calls rods with disks lowered on them towers, and calls a tower that is not involved in the operation of transferring the disk at this moment empty. M. Fedorov’s algorithm is formulated very briefly:

during the repositioning process, the empty tower must be called in a circle in the same direction: clockwise if the number of disks is odd, and counterclockwise if their number is even.

Misha Fedorov successfully presented his work at the All-Union Scientific and Technical Conference of Schoolchildren. Note that if the first algorithm leads to a necessary result by construction, then the validity of the second and third ones must be proven, and this is not very simple. Although in reality all three algorithms are simply different entries of the same disk transfer process.

A significantly different process occurs in the event that a successful correct transfer to the third one, in which the first disk would never end up on

⟦folio 54⟧

---
running_head:
folio:
---

second rod. He claims that such a procedure is possible in $2 \cdot 3^{k-1} - 1$ steps. If, however, the second disk ends up on the second rod, then the number of shifts becomes equal to $2^2 \cdot 3^{k-2} - 1$. And in general, if you forbid placing the $n$ disk on the second rod, then the $2^n \cdot 3^{k-n} - 1$ action will be hit.

We wrote about another modification of this puzzle in the previous issue of the magazine (on page 4 of the cover). V. Pinaev suggests considering the question: is it always possible to move the disks from the first rod to the third, if initially they lay on the first rod in any order. We provide proof that such a shift is always possible.

To prove the possibility of such a shift, we first consider a simpler problem. Suppose you need to assemble a paramid from disks strung on two rods, with a third free, and the disks are located on the rods in increasing diameters. In addition, let’s assume that we already have to solve this problem for any smaller number of disks.

Let the largest disk be on the first rod, then to assemble the paramid on the third rod, three operations must be performed:

1) assemble a paramid without the largest disk on the second rod;
2) move the largest disk to the third rod;
3) move the paramid from the second rod to the third.

We can do all three operations. Indeed, we can perform the first operation by assumption, the second operation is very simple, and the third is a general movement in the Hanoi Basin puzzle, which we have already learned to perform.

Now let's get back to the main task. The first rod contains disks in a random order, the second and third rods are free. Let's try to arrange the disks on the second and third rods in ascending order. Let's also start shifting and continue it as long as possible. In this case, we will rearrange at least two disks. If we are lucky, we will immediately transfer all the disks and move on to an already solved problem. What if you're unlucky? Suppose some disk can no longer be placed on either the second or third rod. Let us mentally separate disks on these rods that are smaller than the considered disk. Let's connect these parts together on the second rod. We have already learned to do this. Now we will transfer the complexity of the disk to the third rod and thereby we will eliminate the difficulty that has arisen. You can continue shifting. As a result, all the disks end up on the second and third rods, and now we can assemble a base from them. So the proof is legitimate.

You can also consider the following problem: all the disks are laid out in random order on all three rods; you need to assemble them on one. This problem is also always solvable.

V. Pinaev suggests the name of the puzzle $\Pi$-tower, well, we can agree with this name. Note that the idea of ​​this puzzle comes from the Rubik's cube: we confuse the location of the puzzle piece, and then let us bring it back to its original form using the allowed actions.

In the literature, “Hanoi Bazni” is considered with a large number of cores, for example, in the recently published book by J. Arsac “Programming and Gears and Puzzles” (M.: Nauka, 1990).

The publication was prepared by A. Savin

Amendment

In «Kvant» No. 9 for 1991 on p. 73, under the conditions of problem No. 4 of the Spanish Mathematical Olympiad, surgery was allowed. The problem question should be read as follows: “Is there a natural number $m$ such that

$$\sum_{n=1}^{m} |a_n - a_{n+1}| = 1990?$$

We apologize to our readers.
