---
id: 1983-4-matveev-raspravlenie-konturov-na-ploskosti-58eefc18
issue: kvant_1983_4
year: 1983
number: "4"
title: Straightening contours on a plane
authors:
  - Матвеев С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 24
page_last: 28
page_labels: 22-26
tag: VMHL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a3a1d7d31887d640eee650147cc4670437a467077b6dd079ab6a4009692331a
prompt_sha256: draft-1
translated_from: content/ru/1983/04/articles/10_matveev-raspravlenie-konturov-na-ploskosti-58eefc18.md
source_content_sha256: 13eb37dffa47c5ab15b71e27401bcc78cc57c3913a5419fe91fa300efc4bbac7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Straightening contours on a plane

Candidate of Physical and Mathematical Sciences S. V. MATVEEV

Let's make a circle out of thin wire, gently bend it in space, give it a more complex shape, and throw it onto a plane, pressing it tightly to it (Fig. 1). Is it possible to straighten the resulting flat wire contour into a circle without tearing it away from the plane?

We assume that the thickness of the wire is zero, so that at those points where one section of the ring passes over another (at the so-called double points), the upper section also lies on the plane. The wire is very flexible, but not infinitely flexible - the radius of curvature should not be zero, otherwise the wire may melt. In particular, the operation of tightening the loops, shown in figure 2, is prohibited.

Of course, it is always possible to straighten our contour in space. After all, we started with a wire circle: it can be restored by polishing the bends we made in the reverse order. By starting with a circle, we bypassed all the difficulties associated with nodes: if we started with such a knotted contour as in figure 3, we would not have been able to completely straighten it into a circle, not only on the plane, but even in space (see «Kvant», 1981, No. 3, p. 8). Let's return to our question. At first

Let's experiment a little and think about it

Let's start with the wire contour on figure 1. After fiddling a little with the real wire (you can also use a thread), you can easily make sure that this contour can be straightened (the straightening process is shown in figure 4).

Now try to straighten the contours a - e shown in figure 5.

I will find that the reader was able to straighten the contours b, d, f. The futility of attempts to straighten the contours a, c, f convinces us of the existence of unstraightened contours. But as proof

Fig. 1.

Fig. 2.

Fig. 3

⟦folio 23⟧

Do you mean that some contour cannot be straightened?

To prove the impossibility of a particular construction or process, mathematicians often use the following technique. With each state the object being considered is associated with a certain number that remains unchanged in this process (such a number is called an invariant or transition); then the invariant counts for the initial and final state of the object; if different numbers are obtained, then the process of transition from the initial state to the final state is impossible: after all, an invariant cannot change in the process, that’s why it is an invariant!

Let's try to associate a number with each flat wiring circuit. The first thing that comes to mind is the number of double contour points. Alas! This is not an invariant, as can be seen, for example, from the process of straightening the contour on figure 4. However, examining this figure carefully, you can notice that double points appear and disappear in pairs. This suggests that the parity of the number of double points does not change, that is, that the remainder of dividing the number of double points by two is invariant.

So it is (we will return to this later). From this statement

⟦folio 24⟧

possible detour directions. We will move along the contour from point A with a single speed in the chosen direction, and the velocity vector will be plotted from a fixed point A'. Then the velocity vector will rotate around A', and its end will move in a single circle (with the center at point A'). Since at the moment of completing the bypass of the contour and returning to point A, the velocity vector will take its original position, the total number of revolutions that it will make around point A' is an integer. In this case, revolutions in a positive direction (counterclockwise) are counted with a “+” sign, and in a different direction (clockwise) - with a “-” sign.

Look at figure 6. On it, the path of the end of the velocity vector is placed with a red line and for clarity, it is moved from a circle. In fact, the red curve wraps tightly around the circle, and points 1' - 6' coincide. In total, the velocity vector makes (-1) revolution: from point 1' to point 2' - one revolution, from point 2' to point 3' and from point 5' to point 6' there is no revolution, and from point 3' to point 4' and from point 4' to point 5' one revolution is made in the printed direction.

The invariant we promised (let’s denote it V) is equal to modulo of the total number of revolutions of the velocity vector. It does not depend, very much, on the choice of the starting point A; it also does not depend on the choice of the direction of the bypass, since when the direction of the bypass changes, the total number of revolutions only changes sign. For example, for a contour on figure 6 the invariant V is equal to 1.

Let us show (without providing a detailed proof) that V is indeed an invariant. During the straightening process, all positions of the velocity vectors change smoothly, without jumps, so the number V should also change continuously; however, V is always an integer; it can only change into another integer by jumps, which contradicts continuity. Therefore, V remains unchanged and is an expansion invariant.

Now we can deal with contour 5, e. For it, V=3 (check!), so it does not straighten out in a circle (for which V=1).

If you really checked that for circuit 5, e V=3, you probably noticed that calculating the number of revolutions of the velocity vector in practice is not very convenient, it’s easy to make a mistake. However, V can be found more easily.

To do this, we choose a definition on the plane, say, the direction of the Oy axis (see Fig. 6), and mark the points at which the velocity vector is directed in the same way as the Oy axis. Let's put the number +1 next to each canceled point if the small section of the contour containing it is to the left of it; and -1 if on the right (if the contour at the canceled point has an inflection - that is, lies on both sides of the vector - we do not put any number).

Then the invariant V is equal to the modulo sum of the given numbers.

⟦folio 25⟧

Fig. 7.

For example, near points 1 and 2 on figure 6 you should put +1, near points 3, 4, 5 you should put (-1). Therefore, for a contour on figure 6, the invariant V is equal to 1. Prove on your own that the indicated method really allows you to calculate V for any contour.

On figure 7 for each non-negative integer n there is a contour with the invariant V=n. Let us recall that if a contour expands into a circle, then its invariant V must be equal to the invariant of the circle, that is, one.

Invariant R

The equality V=1 is a necessary condition for straightening the contour into a circle. Is this condition sufficient? I thought that question had been answered. However, flawless attempts to straighten my own trouser belt, placed as at figure 8, a, convinced me of the opposite and at the same time prompted me to an important observation: lifting the belt (Fig. 8, b) from the floor turned out to be twisted twice!

Let us replace the contour with a tape lying on the plane so that the contour coincides with its midline (Fig. 9, a). Having straightened the contour in space (for example, I return it to its original position before throwing it onto the plane), we get a twisted tape. We denote the number of “twists” by R. This is the second invariant, the equality of which to 0 is necessary for straightening the contour into a circle. It should be clarified that the number of twists is taken with a “+” sign if the tape is twisted as in figure 8, b, and with a “—” sign if the tape is twisted as in

⟦folio 26⟧

figure 8, in (remember the difference between right and left threads).

Let us prove that the number R is indeed an invariant, that is, that it does not change when the contour is straightened on the plane. To do this, it is enough to replace that the straightening of the contour determines the straightening of the tape on the plane, and the number of rounders does not change not only when the tape is straightened on the plane, but also when the tape moves arbitrarily in space.

It can be proven (we will not dwell on this) that the invariant R is calculated as follows. Let us select the direction of traversal on the contour. Let us put the number +1 near each double point if the lower velocity vector is directed to the left of the upper one, and -1 if to the right (it is easy to see that with a different direction of traversal the same numbers are obtained). The invariant R is equal to the sum of the given numbers. For example, the contour on figure 9, b has 3 positive and 4 negative double points, so its invariant R is equal to -1. Consequently, this contour cannot be straightened on the plane.

Necessary and sufficient conditions

We have seen that the conditions V=1 and R=0 are necessary so that the contour can be straightened into a circle. Are these conditions sufficient? In other words, is it possible, by calculating the invariants V and R and making sure that V=1 and R=0, to conclude that the contour expands into a circle? It turns out yes.

Main theorem. In order for a contour to be straightened into a circle on a plane, it is necessary and sufficient that its invariant V be equal to one, and its invariant R equal to zero.

This theorem provides a complete answer to the question posed at the beginning of the article. The simple methods of calculating the invariants V and R described above allow you to quickly check the necessary and sufficient condition formulated in it. I invite the reader to verify this at
