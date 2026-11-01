---
id: 1979-9-zemlyakov-billiardyi-i-poverhnosti-e498e740
issue: kvant_1979_9
year: 1979
number: "9"
title: Billiards and surfaces
authors:
  - Земляков А. Н.
rubric: osnovnye-stati
page_first: 2
page_last: 10
page_labels: 1-8
tag: SJKW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9186b55972ee02dd3275e4b302c029c8db8fa126c70d74b43bdc3f88c659f2c6
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/02_zemlyakov-billiardyi-i-poverhnosti-e498e740.md
source_content_sha256: a8a59a9437b77776b8fb5fd5d789a9294f8291568e461063d8a7dd66ec0e7e13
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

This figure shows how, reflecting from the walls, a billiard ball moves towards a triangle with an vertex angle of π/6. No, no, that's not a typo. The fact is that with the usual depiction of a trajectory on a triangle, the number of kinks and self-intersections is very large, the picture turns out to be extremely confusing. A much clearer (and more beautiful!) picture arises if we cleave an equal 12-gon from 12 copies of our triangle, and then identify its opposite sides. Then you get a closed surface with trays of “handles”, and the trajectory floats around it. You can read why and how this is done in the article “Billiards and surfaces” on p. 2.

⟦folio 1⟧

Described in 1970
QUANTUM
9
1979

Popular science
physico-mathematical
magazine
Academy of Sciences of the USSR
and Academy of Pedagogical Sciences of the USSR

Publishing house "Science"
Main editorial office
physical and mathematical literature

IN THE ROOM:

2 A. Zemlyakov. Billiards and surfaces
10 A. Mikhailov. When is noon?
15 M. Dazaev. Disappearance of the ring of Saturn
Laboratory «Kvant»
17 V. Mayer. Tornado models
Math circle
19 A. Shirtsov. About one combinatorial problem
Problem «Kvant»
21 Premin «Kvant»
22 Problem M581 — M585; F593 — F597
24 Solutions to problems M528, M529; F538 — F541
Through the pages of school textbooks
29 V. Gutenacher. Fixed sum inequalities
«Kvant» for younger students
33 Problems
34 N. Mikhailov. Capacity
Applicant's workshop
38 J. Sukonic, P. Gorshtein. Geometric solutions to geometric problems
The Art of Programming
44 Introducing a new section
47 A. Ershov, G. Zvenitsorodsky. Why do you need to know how to program?
52 G. Zvenitsorodsky. Programming Correspondence School, Lessons 1 and 2
Information
58 Correspondence physical school
Reviews, bibliography
60 I. Klumova, M. Smolyansky. New books
62 I. Slobodetsky. New popular science series from the Nauka publishing house - Library «Kvant»
63 I. Petrakov. A wonderful collection of first-class mathematics sources
64 Answers, directions, solutions
Blend (p. 9, 14, 16, 36, 43, 59)

© Main editorial office of physical and mathematical literature
Publishing house "Science", «Kvant», 1979

⟦folio 2⟧

A. Zemlyakov

Billiards and surfaces

Reflecting from the walls, an accurate ball moves along a polygonal billiard table. Under what conditions will its movement be periodic? With a given non-periodic motion, are there areas where the ball will never hit?

To answer these simply formulated but difficult questions, this article considers motion without reflections on a surface together with motion with reflections on a plane. It turns out that you can go from billiards in a polygon to motion on a surface by some gluing of polygons.

At the beginning of the article, this transition appears in the example of a mogul billiard. After the need to talk about gluing surfaces, the general case is considered. In particular, problems 16 and 17 from the article “Mathematics of Billiards” («Kvant», 1976, No. 5) are solved.

1. Billiards in rectangular and torus windings

We are interested in the following question: what could be the trajectories of a billiard ball moving in a rectangle P? We consider the ball to be a point and are interested in infinite trajectories - never falling into the vertices of the rectangle (Fig. 1). On the face of numerous reflections from the walls of the billiard, it greatly complicates the study of the trajectories of the ball. However, each billiard trajectory can be “straightened” with the help of successive reflections of its segments relative to the side of the rectangle - as shown in figure 2. If from the very beginning, with the help of reflections, the entire plane of the rectangle is “tiled” with congruent P, then, with inverse reflections, the techniques on the plane will give billiard trajectories in the rectangle P. It turns out that there is no need to consider an infinite number of reflected rectangles - you can get by with four, forming a “large” rectangle P' (Fig. 3), if we assume that the ball, one to its side, “re-bends” in accordance with the point of the opposite sides (C→C', E→E', ..., K→K', L→L', ..., S→S') and moves in the same direction until the next hit on one of its sides. Indeed, by adding (with the help of symmetry) the rectangle P from P', we obtain billiard trajectories in P from the conjugating trajectories in P' of the present.

Thus, we were able to get rid of the reflections of the trajectory, but it began to have “jumps”. To get rid of them, roll the rectangle P' into a cylinder and clip the sides XY and X'Y'; in this case, the points L and L', N and N', ..., I and I' (Fig. 3) will merge with each other, and the trajectory will smoothly wrap around the cylinder (Fig. 4). However, there remain

⟦folio 3⟧

2. Billiard trajectories in a rectangle

The torus can also be obtained by rotating the circle Γ about the ZZ' axis that does not intersect it and lies in the plane of the circle (Fig. 6). Moreover, each point of the circle Γ will give a circle on the torus, which we call *parallel* tora. The circle that receives from Γ at each specific rotation is naturally called *meridans* tora (Fig. 6). Finally, the large rectangular piece P', from which the torus was assembled, can be conveniently considered as a *map* of the tora. Although the trajectory from step 1 is wrapped along the tora, you can follow it, as in navigation, on the map.

Let the ball move with unit speed at an angle α to side “a” of the rectangular P. Then the components of the speed of movement along the map tora P' along the parallels and meridans are equal to cos α and sin α, respectively. Parallels on the tora map have

$$\varphi = 2\pi \frac{l_0}{2b} = 2\pi \frac{a}{b} \text{tg} \alpha$$

(here 2b is the length of the tora meridans on the map). Consequently, the trajectory on the torus will be closed, i.e., periodic, if a certain integer number of rotations through the angle φ gives rise to

⟦folio 4⟧

Fig. 7.

mouth by an integer multiple of 2π, that is, $n\varphi = 2\pi m$ or $\frac{a}{b} \mathrm{tg} \alpha = \frac{m}{n}$ is a radional number. If the number $(a/b) \mathrm{tg} \alpha$ is irrational, then the trajectory on the torus will be open - non-periodic. The intersection points of the trajectory with each fixed meridian are located on it `всюду пломно`, i.e., so that they fall into any neighborhood of any of its points*).

Due to the arbitrariness of the choice of meridiana, a non-periodic trajectory will be everywhere dense on the entire torus, the corresponding trajectory will be everywhere dense on the map of the torus $\Pi'$, and the billiard trajectory will be everywhere dense in the rectangle $\Pi$. It can be put simply this way: no matter how we make two holes (radus $r > 0$) in a rectangular billiard table, a powerful billiard ball, swelling at the maximum angle $\alpha$ to the side $a$, that the number $(a/b) \mathrm{tg} \alpha$ is irrational, sooner or later will appear in the hole.

So, we have reduced the billiards in the rectangle to the “windings” of the torus and established the following important fact: any billiard trajectory that does not fall into the vertices of the rectangle is either periodic (in the case of $(a/b) \mathrm{tg} \alpha \in Q$) or everywhere dense in the rectangle (in the case of $(a/b) \mathrm{tg} \alpha \notin Q$). Thus, problem 16 from the article “Matematika of billiards” is solved. Without wanting to deprive the reader of satisfaction, we will present problem 17 from the same article in the form of the following tasks:

*) See Jacobi's theorem in the article "Matematika of billiards".

Problem 1. In a similar way, prove that any billiard trajectory in an isosceles right triangle that does not fall into the vertices is either periodic or densely fills the corresponding trajectory everywhere.

Problem 2. Prove the same for: a) an equilateral triangle, b) a right triangle with an angle of 30°.

If task 2 does not work out, reject it before reading paragraphs. 3, 4.

3. Surfaces and their gluing

Of course, it will be interesting to see what happens for billiards in other polygons (other than the rectangle and triangles from problems 1, 2). Is it possible to generalize the construction from point 1 to an arbitrary case? First, however, let's deal with surfaces and gluing.

In § 47 of the textbook “Geometry 10”, a closed polygonal surface is defined as a set of points in space, composed of polygons and satisfying non-octorional conditions. The main property of such a surface is that each of its points $M$ has a neighborhood that can be continuously transformed into a general circle centered at the point $M$ (Fig. 7). By the neighborhood of the point $M$ we mean the set of surface points distant from $M$ by no more than a distance $\varepsilon > 0$. During our continuous transformations, the neighborhood can be bent, compressed or stretched in places, but it is forbidden to “knead” its points together and “tear” the neighborhood. If we imagine the neighborhood of point $M$ made of rubber, then the necessary transformation can be obtained by putting the neighborhood under a press and, slowly stretching it (so that no folds or tears occur), position it.

This basic property is possessed not only by closed polygonal surfaces, but also by curved surfaces - for example, a sphere or a torus. If you cut two holes in a sphere and seal them in a suitable manner,

⟦folio 5⟧

bent “handle” - the side surface of the cylinder, you get a “sphere with a handle”, which can be transformed into a torus (Fig. 8). By gluing two handles to the sphere in the same way, we get the so-called “pretzel”, or a sphere with two handles; on figure 9 this surface is presented in heel views.

You can build a sphere $S_p$ with any number of glued handles $p \geq 0$. It is easy to see that all spheres with handles have the basic property.

The full surface of the cylinder also has this property, but its lateral surface does not: the points $M$ on the circle of the bases have a neighborhood in the form of a curved semicircle; they cannot be deformed without breaking and gluing into a circle with the center at point $M$ (Fig. 10). Further, the surface of a double cone and the union of two intersecting or touching spheres do not have the basic property (Fig. 11), but the union of two disjoint spheres does.

We want to exclude from consideration surfaces consisting of several separate pieces. We therefore require that any two points

surfaces could be connected by a continuous line running along the surface. This property is called "surface connectivity".

We do not want to consider infinitely extended surfaces—such as a plane or an infinite cylindrical surface—or surfaces such as a circle without boundaries. Therefore, we will impose one more condition (let's call it finiteness): we will require that the surface can be divided ("cut") into a finite number of "curvilinear polygons", each of which, without breaks or gluing, is transformed into a flat convex polygon (with boundaries). For example, a sphere along the equator and four meridians is cut into 8 curvilinear triangles, but a plane cannot be divided into a finite number of polygons.

So, further we will consider only those surfaces (sets of points in space) that have the three listed properties: the basic property, the property of finiteness and connectedness.

Two such surfaces are considered equivalent (mathematically equivalent)

Fig. 8.

Fig. 9.

⟦folio 6⟧

mi"), if there is an inverse mapping of one of them to the other, in which there are no breaks or splices (but stretching, rolling, bending and straightening are allowed). For example, the surface of a terrahedron is equivalent to a sphere, the last two surfaces on figure 8 are equivalent to a torus, all five surfaces on figure 9 are equivalent to each other. It can be proven*) that any surface in space (in our sense) is equivalent to one of the spheres with p handles (i.e., either a sphere, or a torus, or a fortress, or a sphere with p handles for some $p>2$).

Problem 3. Show that a mor, a crepedel and, in general, a sphere with any number of handles have the property of finiteness, i.e., by showing their partition into a finite number of crulley polygons.

Task 4. For each of the surfaces listed below, indicate the sphere with what number of handles it is equivalent to: a) the surface of a bowl

*) See, for example, the article by V. A. Efremovich “Basic topological concepts” in book V of the “Encyclopedia of Elementary Mathematics” (M., “Nauka”, 1966) or chapter 3 in the book by G. Ringel “Theorem on the coloring of a map” (M., “Mir”, 1977).

ki (Fig. 12a); b) smooth surface (Fig. 126); c) the surface of the window frame (Fig. 128)).

Problem 5*. Show that pestilence and sphere are not equivalent.

Note. Find a property that is preserved under the transformations under consideration and which one of these surfaces has and the other does not.

A surface with the finite property is cut into polygons and can therefore be glued together from polygons. It turns out that you can get by with just one polygon. We have already seen that a torus can be obtained by gluing together the opposite sides of a square (or by direct gluing). So, from any 2n-gon, after pairwise gluing of its opposite sides, a surface of our type is obtained, i.e., a sphere with a certain number of handles. For example, figure 13 shows how, when gluing the sides of a recliner, a crepedel is obtained.

Problem 6. Find the number of handles p of the surface $S_p$, glued in the above manner from a 2n-gon.

In principle, the law for gluing the sides of a 2n-gon can be specified arbitrarily; but this will not always result in a surface of our type.

⟦folio 7⟧

Task 7. Glue together figures 14a, 6. (In case 14a, you will get a self-intersecting surface - the so-called “Klein bottle.”)

4. Billiards and surfaces

Let's return to Billiards: let's try to generalize the construction from point 1 to the case of an arbitrary polygon. We will show what can happen in this case using the example of a right triangle $T=ABC$ with an acute angle $\hat{A}=\pi/8$.

To straighten the Billiard trajectory in $T$ we again use successive reflections. Such reflections relative to the sides emanating from the vertex $A$ give, as shown in figure 15a, a regular octagon composed of 16 triangles $T_1=T$, $T_2$, $T_3$, ..., $T_{16}$, congested triangles $T$. Note that it is impossible to tile the entire plane of a triangle with constructive $T$ using reflections. Now we will see that this is not necessary - we can get by with the 16 indicated triangles.

Let the trajectory [PM] reach the point $M$ on the side of the octagon $Q$. The continuation of [PM] beyond the point $M$ in the case depicted in figure 15a should be drawn in the triangle $T_5'$, symmetrical to $T_5$. Note that among the triangles $T_i$ there is a triangle $T_{12}$, from which $T_5'$ is obtained by parallel translation. It is easy to see that this transfer can be performed as a sequential composition of symmetries:

$$T_{12} \rightarrow T_{11} \rightarrow T_{10} \rightarrow \dots \rightarrow T_6 \rightarrow T_5 \rightarrow T_5'.$$

Moreover, the ray drawn through the corresponding point $M'$ (such that $|A'M'|=|AM|$ - Fig. 15a) on the side of the triangle $T_{12}$ is parallel to the ray [PM], with the indicated composition of the mapping to the continuation of the ray [PM] beyond the point $M$. Therefore, we can assume that the ball breaks from point $M$ to point $M'$ and proceeds

⟦folio 8⟧

Fig. 15.

should move in the same direction along the triangle $Q$: the conjugating trajectory in $Q$ after the reflection one will give a billard trajectory in the triangle $T$. The same reasoning applies in all other cases, no matter which of the triangles $T_i$ the trajectory is going to leave, going beyond the boundaries of the triangle $Q$. Thus, as above (in paragraph 1), the billard trajectories in the triangle $T$ correspond to the trajectories of a ball moving in the same direction inside the triangle $Q$ and jumping - upon reaching its sides $Q$ - to the corresponding points of resistance of the sides (the beginning of one of such trajectories is depicted on figure 156).

To make the concatenating trajectories continuous, you need to merge the resistances of the side of the osmutolnik $Q$. As we saw in paragraph 3, this will result in a crepe, and the billard trajectories in the triangle $T$ will correspond to the curves wrapping around this crepe!

Although it is impossible to enter coordinates well on the crepe, nevertheless, using the described construction it is possible to prove that any billard trajectory in a right triangle with an acute angle $\pi/8$ that does not fall into the vertices, either the period, or the water, fills the triangle completely. We leave the proof of this statement as the weight of the hard problem (without a number).

Problem 8. Construction of a surface corresponding to billards: a) in a right triangle with angle $\pi/12$, b) in a right triangle with angle $\pi/5$, b) in a square with a square hole cut out in it (the sides of the hole are parallel to the sides of the square).

It turns out that a billard in any polygon, the values ​​of all angles of which are commensurate with $\pi$, has the property of moving on the corresponding surfaces - a sphere with handles (where $p$ is greater than 1 in all cases, except for the rectangular triangle and triangles from Problem 1, 2). We present the proof of this fact in the form of a series of problems.

Problem 9*. a) The billard ball moves at an angle $\alpha$ to the fixed side $a$ of the polygon $\Phi$ and, having reflected from the side forming an angle $\beta$ with $\alpha$, continues to move at a new angle $\alpha'$ to side $a$. Express $\alpha'$ in terms of $\alpha$ and $\beta$.

Let us now assume that the magnitudes of all the angles of the polygon $\Phi$ are commensurate with $\pi$ or, what is the same, that the sides $\Phi$ form angles $\beta_i = \frac{m_i}{n_i} \pi$ with the fixed side $a$, where $m_i$ and $n_i$ are integers.

6) Prove that if the initial segment of a billard trajectory in the polygon $\Phi$ is directed at an angle $\alpha$ to side $a$, then all subsequent segments of this trajectory can be directed to side $a$ only at a finite number of angles $\alpha_1 =$
