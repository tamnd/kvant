---
id: 1985-3-vasilev-zadacha-o-vosmi-tochkah-5734db06
issue: kvant_1985_3
year: 1985
number: "3"
title: Eight Point Problem
authors:
  - Васильев Н. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 42
page_labels: 39-40
tag: L0OU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 319c542df4fc2198f25f45ea5410136456cbc293a338625ffaadab3d75c51314
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/18_vasilev-zadacha-o-vosmi-tochkah-5734db06.md
source_content_sha256: 210617e89255f94148c8cd1ea093e3d38cb48fe9cb6be77909bfbbabf9362613
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Problem
about eighth points

Candidate of Physical and Mathematical Sciences
N. V. VASILBEV

This note is about a problem that was proposed to tenth graders in April last year at the last All-Union Optimide in Mathematics in Ashgabat.*) Let us present its formulation with minor changes.

Problem 1. A circle is circumscribed around triangle ABC. Through an arbitrary point P in the plane of the triangle (not lying on the circle), straight lines AP, BP, CP are drawn and the second points of their intersection with the circle are offset. Prove that there are at most 8 points P for which the offset of the point does not coincide with any of the points A, B, C and the vertex of a triangle equal to triangle ABC.

This task turned out to be quite difficult. Some participants solved it by trying different locations of the point P relative to the lines AB, BC, CA and the circle. Here is another, more honorable solution to this problem, using the “language of movement”: we will imagine that the individual elements of our configuration are rotating, and at some point the desired figure will appear.

First, let's solve the following “inverse” problem.

Rotation and line intersections

Problem 2. Two (not necessarily equal) triangles ABC and A1B1C1 are inscribed in a circle. Triangle ABC is fixed, and triangle A1B1C1 is healed around the center of the circle. At what position will the lines AA1, BB1 and CC1 intersect only once at one point (and in some “pronounced” cases there will be no such position at all).

Solve problem 2 using the geometric locus method.

Lemma. Let the chord AB of the circle be fixed, and the chord A1B1С1 slide with its ends along the circle. Then the angle between lines AA1 and BB1 remains unchanged, and the point M of the intersection of these lines (if φ≠0) describes a circle passing through points A and B (Fig. 1).

Let us begin the proof of the lemma. If points A1 and B1 move uniformly along the circle with the same speed, then lines AA1 and BB1 rotate uniformly with the same angular speed around points A and B, which means the angle between them remains constant (at figure 1 for points M on one side of straight AB, angle AMB is equal to φ - the angle between the lines, and for points M on the other side of AB, angle AMB is equal to φ). If at the initial moment straight lines AA1

*) Other problems of the oimpida were developed in «Kvant» No. 11 for 1984.

Fig. 1. If points A and B are fixed, and points A1 and B1 move at the same angular speed (moving in a circle), then straight lines AA1 and BB1 are adjusted with angular speed /2, and their intersection point M1 moves along the red circle (with angular speed)).

and BB1 intersected at a certain point M1, then the circumscribed circle of the rounder ABM1 will be the desired trajectories of the point M, and M also moves uniformly along the circle (the angular velocity of rotation of the straight lines is equal to the polyline of the angular velocity of rotation along their circles of points A1, B1 and M).

Hidden behind this visual reasoning “in the language of rotations,” as is easy to see, is the repeated use of the theorem about the magnitude of the inscribed angle.*)

Two clarifications need to be made to the lemma, which will be rounded off to the essential ones later.

1°. The special case φ=0 arises if the chords AB and A1B1 are equal in length, and at some initial moment of time point A1 coincides with B, and B1 with A. In this case, at the initial moment of time, the straight lines AA1 and BB1 coincide, and with further movement they will always be parallel to each other.

2°. At the moment of time when A1 coincides with A (or B1 with B), the straight line AA1 (corresponding to BB1) “by continuity” must be considered directed tangent to the given circle (or, if this is not done, the corresponding two points must be excluded from the found geometric location - the circle).

Let's return to problem 2. Using the lemma, let's construct two circles - geometric places of the intersection point of lines AA1 and BB1, as well as BB1 and CC1 (Fig. 2). The first one goes through points A and B, the second one goes through points B and C. For the role of point P, where all three straight lines AA1, BB1 and CC1 must intersect (it, of course, cannot lie on a given circle), only one point is suitable - different from B, the point of intersection of the two constructed circles. (We do not have the necessary lines for the geometric location of the intersection point AA1 and CC1 - the third circle passing through A and C - it, of course, will automatically pass through the same point P of the intersection of the two constructed circles.) So, generally speaking, there is only one position of the triangle A1B1C1 that satisfies the required condition. In any case, taking into account the clarifications made above, we can assert that there is at most one required point P (special

⟦folio 40⟧

Fig. 2. Point P is located at the intersection of two geometric places: the coefficient BB1 is checked against the position BP, then AA1 and CC1 coincide with AP and CP.

the case is depicted in figure 3). Problem 2 is solved.

Now we can take up Problem 1. For each point P that does not lie on the circle, we denote by A1, B1 and C1 the second points of intersection with the circle of the lines AP, BP and CP. The problem condition identifies those points P for which triangle A1B1C1 is equal to triangle ABC; at first glance it may seem that, taking equal triangles in task 2, we will find only one required ΔA1B1C1 (symmetrical to triangle ABC relative to the center of the circle). But there is a subtlety here, not so much geometric as logical. We will announce it after a short retreat.

Permutation of vertices and symmetries

Everyone knows that equal (in other terminology “congruent”) triangles, by definition, have corresponding equal angles and sides, so that they can be combined by overlapping. In the textbook by Academician A.V. Pogorelov “Geometry 6-10”, the equality of triangles ΔABC = ΔDEF, the vertices of which are indicated by letters, is always written so that the corresponding vertices are in the same order (that is, so that A = D, B = E, C = E, AB = DE, etc.).

Fig. 3. Baseline φ=0, coefficient P does not exist (lines AA1, BB1 and CC1 remain parallel).

Fig. 4. Basic situation: point P appears at the moment the triangles coincide.

Having read the conditions of Problem 1 again, you can see that in this sense our ΔA1B1C1 does not have to be equal to the triangle ABC - it can be equal (taking into account the correspondence of the vertices) to any of the six triangles ABC, BCA, CAB, BAC, ACB, CBA. And this number of variants needs to be doubled, already for a purely geometric reason: ΔA1B1C1 can be, as they say, “actually equal” to the triangle ABC - that is, it can be combined with it by continuous movement in the plane (in our problem - by turning R), or “mirror equal” - in this case, to combine the triangles, one of them needs to be “turned over” (in our problem it is enough to make S symmetry relative to some straight line; all triangles A1B1C1, mirror equal to triangle ABC, will be obtained from each other by rotations). To differentiate these situations, we will write the letter R or S over the equality of triangles. And for each of the 2 6 = 12 options, we, using Problem 2, can construct (no more than) one required point P.

Vollee, this reasoning can be visually summarized as follows: we take a cardboard triangle T (with the same radius of the circumscribed circle as triangle ABC), place its vertices on the circle, placing one or the other side on the plane, designate them with the letters A1, B1, C1 (6 ways) and, rotating it as in task 2, find point P for each of the 2·6 options.

To complete the solution to Problem 1, it remains to explain why in the case of T=ΔABC 4 options are excluded. However, of these (the case ΔABC = ΔDEF, the vertices of which are designated by letters, it is customary to always write it so that the corresponding vertices are in the same order (that is, so that A = D, B = E, C = E, AB = DE, etc.).

Fig. 3. Baseline φ=0, coefficient P does not exist (lines AA1, BB1 and CC1 remain parallel).
