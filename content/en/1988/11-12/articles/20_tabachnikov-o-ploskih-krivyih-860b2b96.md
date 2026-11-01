---
id: 1988-11-12-tabachnikov-o-ploskih-krivyih-860b2b96
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: About plane curves
authors:
  - Табачников С. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 61
page_last: 65
page_labels: 59, 61, 62, 63
tag: I9CG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4064804eebd0f42b8d5768daf4935373b5d3ab58730ce2004aabdb34027981df
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/20_tabachnikov-o-ploskih-krivyih-860b2b96.md
source_content_sha256: 3c6d3c605b2adb9a8949a1330611f7962140ac208ba7e0c8b1a05d08a22ff987
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

ABOUT PLANT CURVES

Candidate of Physical and Mathematical Sciences
S. L. TAVACHNIKOV

Self-intersection points
double tangents and points
inflection

Throw a long rope on the table
loop and it forms a closed curve. Such curves are our main
subject of research.

The points at which the curve intersects itself are called self-intersection points. For example, a figure eight has one such point, but a circle does not have them. A double tangent is a line that touches a curve twice. Double tangents are of two types: external, if small pieces of curves at the points of tangency lie on one side of the tangent, and internal, if on different sides (Fig. 1). The entire curve does not have to lie on one side of the outer double tangent - only small sections of it have this property.

We will also be interested in the inflection points of the curve. Let's imagine that we are moving along a curve and turning, for example, to the left - the red section at figure 2. At some points the direction of the turn may change - the blue section. This point, bordering between the blue and red sections, is called the inflection point. If a curve has no inflection points, then it always turns in one direction (Fig. 3).

Let's go around the curve, coloring it in two colors, as in figure 2, and return to the starting point. Red and blue areas alternate, so there are equal numbers of both. The number of inflection points is equal to the total number of red and blue sections, i.e. even. We have proved the first theorem about plane closed curves:

the number of inflection points is even.

⟦folio 61⟧

we go through twice. To calculate the contribution of double tangents, we divide their total number into three terms in accordance with figure 7. The contribution of double tangents per round turns out to be equal to $2(p_1+2p_2)-2(q_1+2q_2)$. After the traversal, the number of points of intersection of the ray with the curve has not changed, so
$$-r-2n+2p_1+4p_2-2q_1-4q_2=0.$$
Now we'll go around the curve in the opposite direction. In this case, the arrows on figure 7 place the directions, i.e. the numbers $p_2$ and $p_3$, $q_2$ and $q_3$ are placed in places. We get the equation
$$-r-2n+2p_1+4p_3-2q_1-4q_3=0.$$
To prove the theorem, all that remains is to add the two equalities obtained and divide the result by 4.
This theorem contains the necessary conditions that the numbers $p, q, r$ and $n$ are equal to the numbers of external and internal double tangents, inflection points and double points of a plane curve. What about enough?
Let the curve have neither double points nor inflection points, i.e. $r=n=0$. then the curve is convex, and it also does not have double tangents. However, the equality $p=q+r/2+n$ does not prohibit the equal positives $p$ and $q$. This means that the conditions of the theorem are not sufficient.
However, this condition becomes sufficient when the curve has inflection points:
if $r$ is an even positive number $p=q+r/2+n$, then there exists a closed plane curve with data $p, q, r, n$.
The case of curves without an inflection point is more complex:
if $r=0$, then the number of internal double tangents $q$ is even and $q \leqslant (2n+1)(n-1)$;
if $q \leqslant n(n-1)$ and $p=q+n$, then there is a closed plane curve $c=r=0$ and data $p, q, n$.
Proofs of these theorems are beyond the scope of this article. The results themselves are quite “fresh” - they were obtained by the American mathematician B. Halpern about 10 years ago. And the main theorem of this point is

⟦folio 62⟧

Kazan by the Danish mathematician F. Fabricius-Bjerre in 1962.

At the right
3. Think of a curve that has $p=3$, $q=0$, $r=2$, $n=2$.
4. Given a point that does not lie on a plane curve. Prove that the number of tangents through this point is even. Hint: draw a straight line through the point and rotate it.
5. Given two plane curves. Let $p$ be the number of their common internal double tangents, $q$ the number of external double tangents, $n$ the number of intersection points of the curves. Prove that $p=q+n$.

Curve rotation number
Let's go around the flat curve and return to the starting point. During the traversal, the tangent vector somehow turned and at the end returned to its original position. This means that the tangent vector has made an integer number of rotations. This (non-negative integer) number is called the rotation number of the curve. For example, the number of a circle is 1, and the number of a circle of eight is zero.

Rule 6. What are the rotation numbers of the curves from exercise 1?

When the curve changes intermittently, the rotation number does not change. Indeed, with little movement, the rotation number can only change slightly. But the number is an integer, and an integer can only change abruptly. Therefore, with an irregular change in the curve, the rotation number does not change at all. This property can be used when calculating the rotation number. For example, a curve at figure 8 can be “inflated” into a circle, so its rotation number is the same as that of a circle, i.e. 1.

The proven theorem is a fairly necessary sign that one curve can be deformed into another: their rotation numbers must be equal. And here again the question of sufficiency arises: is it true that if the rotation numbers are equal, then the curves can be deformed into each other? The answer to this question is yes, but we will not prove it.*)

*) See, for example, the article by S. V. Matveev “Straightening contours on a plane” («Kvant», 1983, No. 4).

⟦folio 63⟧

Exercises
7. What is the number of rotations of a curve without double points?
8. Prove that if the rotation number of a curve is zero, then the curve has inflection points.

There is another method that almost automatically leads to the calculation of the curve rotation number. Let’s choose a direction on the curve and make a “crossover” at each double point, as shown in figure 9. The curve breaks up into several non-intersecting curves (Fig. 10). Let's count the number of such curves oriented clockwise and counterclockwise and find the modulus of the difference between these two numbers. This is the rotation number of the original curve. For example, for a curve at figure 10, the rotation number is 2—1=1.

We defined the rotation number and showed how to calculate it. How is it related to the number of double points on the curve? To answer this question, note that each re-handling increases the number of curves by figure by no more than 1. Therefore, if the original curve had n double points, then in the end there will be no more than n+1 curves. So,

the number of rotation does not exceed the number of its double points plane 1.
This inequality was obtained by the famous American mathematician H. Whitney.

Exercise 9. Prove the following theorem:
The rotation number of a curve has the same parity as the number of its double points on the plane 1.

Degree of curve relative to point
A curve divides a plane into parts. Let's take point O in one of these parts. Let point A go around the curve; We will follow the OA beam. When point A returns to its original position, beam OA will complete an integer number of revolutions. This (non-negative integer) number is called the degree of the curve relative to point O. If point O moves along the plane without falling on the curve, then the degree does not change. If a point jumps over the curve, the degree may change.

Applying the rearrangements from the previous paragraph allows you to calculate the degree of the curve relative to the point. This is done in the same way as when calculating the rotation number; - after rearrangements, the curve splits into several non-intersecting curves, and then counts the number of these curves containing point O inside and oriented clockwise and counterclockwise. The modulus of the difference between these two numbers is the degree of the curve. On figure 10 in each of the parts, on which is written the odd degree value (Fig. 12). Let there be another curve intersecting this one. This second curve also turns out to be painted in two colors, with blue and red areas alternating on it. This means that there are equal numbers of both. The intersection points of the curves separate the multi-colored areas, so they are in a column, how many of them are there together. Hence,

the number of intersection points of two closed plane curves is even.

This last theorem takes us back to the beginning of the article, where we proved that the number of inflection points is even. The curve of our story has closed and we have to put an end to it.

Exercise 11. Number the self-intersection points of the curve in an arbitrary way. We will go around the curve, write down the number of double points in the order in which they are encountered during the traversal. For example, the curves at figure 13 correspond to the sequences 123123 and 112233. In each subsequence, each number occurs twice. Prove that between any two identical numbers there is an even number of terms in the sequence (Gauss's theorem).

Hint: do one rebuild and use the last theorem.
