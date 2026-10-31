---
id: 2020-7-knop-okruzhnosti-karleylya-ili-kak-reshat-kvadratnyie-uravneniya-tsirkulem-i-lineykoy-9e16bc10
issue: kvant_2020_7
year: 2020
number: "7"
title: Carlyle's circles, or How to solve quadratic equations with compasses and ruler
authors:
  - Кноп К. А.
rubric: osnovnye-stati
page_first: 11
page_last: 15
page_labels: "13"
tag: ECR0
lang: en
source: kvant_digital
extraction: native
content_sha256: a20bd48b25e92a8c61e3af70ed62bbcbc78af7077a8e91261a51916dc0021e47
prompt_sha256: draft-1
translated_from: content/ru/2020/07/articles/01_knop-okruzhnosti-karleylya-ili-kak-reshat-kvadratnyie-uravneniya-tsirkulem-i-lineykoy-9e16bc10.md
source_content_sha256: 2f2d4cd31aa1d6c43d1a85584aad161d0f7239c5190c581eff6bb06628499f37
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Carlyle's circles, or How to solve quadratic equations with compasses and ruler

K.KNOP

IT WOULD SEEM, WHAT COULD THERE be a connection between quadratic equations and geometric tools - compasses and rulers? However, this connection exists, and its study from different angles is a fascinating task, closely related to both geometry and algebra. And what does Thomas Carlyle have to do with it? According to Wikipedia, he is a British writer, publicist, historian and philosopher, author of the multi-volume works “The French Revolution” (1837), “Heroes, Hero Worship and the Heroic in History” (1841), “The Life History of Frederick II of Prussia” (1858–1865). Almost nothing is known about his studies in mathematics, and yet a class of circles that help solve quadratic equations is named after him. And now - about everything in order.

What do we mean by solving equations with compass and ruler?

In school geometry textbooks there is some mention of the possibility of constructing quadratic irrationalities using geometric tools, but mainly not in the form of practical construction algorithms, but as an existence theorem. The only school example of a specific algorithm

DOI: https://doi.org/10.4213/kvant20200702

⟦column⟧

Thomas Carlyle. Daniel McLees's portrait of rhythm, somehow related to quadratic equations, is the construction of a geometric mean. Let's start with this task too. Problem 1. Given segments a and b. Construct a segment equal to ab. Solution. Let's put it on one straight line

⟦folio 13⟧

OK

KAR LEYLA,

naty cos 72 q; sin 72 q, cos 72 q; sin 72 q, cos144 q; sin144 q and cos144 q; sin 144 q, i.e. Angles AOB and AOE are 72 degrees. and angles AOC and AOD are 144 degrees. And this means that they are the vertices of a regular pentagon. The proof of the correctness of the construction is now complete.

On the complexity of constructions and “geometography” by Emile Lemoine

The Frenchman Emile Michel Hyacinthe Lemoine is rightfully considered one of the fathers of modern “triangle geometry”. You've probably heard of Lemoine's point in a triangle or Lemoine's circles. In 1892, he published the work “Geometrography, or the art of geometric constructions” (“L a Géométrographie ou l’art des constructions géométriques”), in which he first proposed comparing various geometric constructions according to the number of required elementary operations (and the best construction is considered to be the one that requires fewer operations). Lemoine calls the optimal (“geometrographic”) method the most economical of the known construction algorithms. Lemoine counted five elementary operations: $S_{1}$ – apply a ruler to a certain point; $S_{2}$ – draw a straight line; $C_{1}$ – place the leg of the compass at a certain point; $C_{2}$ – change the radius of the compass by placing the leg with a pencil at a certain point; $C_{3}$ – draw a circle with a compass. At the same time, Lemoine considered the compass to be stable, i.e. after drawing a circle, maintaining the set radius. Thus, the next circle of the same radius, according to Lemoine, no longer requires three operations: $C_{1} C_{2} C_{3}$, but only two: $C_{1} C_{3}$. Let us count, for example, the number of operations in constructing the roots of an equation using the Carlyle circle, shown in figure 5. The coordinate axes and points $A, B_{1}$ and $B_{2}$ are given. Construction of the median

OR

HOW

$Р_{ЕШАТЬ}...$

⟦column⟧

perpendicular to the segment $OB_{1}$ – these are two circles of equal radii and one straight line, i.e. $2 C_{1} C_{2} 2 C_{3} 2 S_{1} S_{2}$. The next perpendicular bisector is $2 C_{1} 2 C_{3} 2 S_{1} S_{2}$, because we construct it without changing the radius of the compass. Thus, we built the center, spending 15 elementary operations. And finally, the Carlyle circle itself is also $C_{1} C_{2} C_{3}$. The total “complexity” of construction $5 C_{1} 2 C_{2} 5 C_{3} 4 S_{1} 2 S_{2}$ is 18.

Exercise 1. Think of another way to construct a Carlyle circle that has a difficulty of 17 or less.

Clue. The center of this circle is the middle of the segment, one of the ends of which is $B_{1}$. First construct the second end of this segment.

The modern computer puzzle game Euclidea (www.euclidea.xyz) also requires problem solvers to find the most economical construction, but, unlike Lemoine, does not count the preliminary operations $S_{1}, C_{1}$ and $C_{2}$, but only counts the number of lines drawn (i.e. $S_{2} C_{3}$ in Lemoine's terminology). From the point of view of Euclidea, constructing a Carlyle circle has a difficulty of 7.

Is it possible to find the roots of a quadratic equation with less complexity? When the author began writing this article, he assumed that this question would be hung as the final smile of the Cheshire Cat and left to the reader to decide for himself. However, plans have changed a little, and now I want to show a more economical method, and invite readers to think about whether it is possible to find an even better one. First, let's abandon the y-axis. Why is it needed if we look for all the roots on the x-axis? Let us have only one axis, and on it there are four known points O 0, E 1, S X Y and P XY. The last two points correspond to the coefficients of the equation we want to solve. Figure 7 corresponds to the situation where 0 XY 1 X Y, but this is not very critical
