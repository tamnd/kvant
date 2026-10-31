---
id: 2020-11-12-protasov-kratchayshie-puti-i-gipoteza-puankare-3ef7b853
issue: kvant_2020_11-12
year: 2020
number: 11-12
title: Shortest paths and Poincaré's conjecture
authors:
  - Протасов В. Ю.
rubric: osnovnye-stati
page_first: 10
page_last: 14
page_labels: 11-12
tag: 76X5
lang: en
source: kvant_digital
extraction: native
content_sha256: 238000c4df057a78286df454aba03c20a29ca8f61520cbda1e1aab7c765c3d27
prompt_sha256: draft-1
translated_from: content/ru/2020/11-12/articles/01_protasov-kratchayshie-puti-i-gipoteza-puankare-3ef7b853.md
source_content_sha256: 76d2ff642af03bde9a3f4b771b35f5877f74f8fd71a9e4d35327269f65513f85
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Shortest paths and Poincaré's conjecture

V.PROTASOV

Controlling every step, They led me, drove me in a fantastic zigzag along an unknown spiral. M. Shcherbakov. Hallelujah

Geodetic lines

Why does a plane from Moscow to Montreal fly through Greenland? Moscow is located at latitude 56, Montreal is at latitude 45, and all of Greenland is north of 60. Why did the plane fly there? But because they try to lay out the route along the shortest path on the surface of the Earth. And, oddly enough, it passes through Greenland. This often goes against our geographical intuition. The shortest route from Yekaterinburg to Los Angeles goes through the North Pole. The shortest path along a given surface goes along a geodesic line. The word “geodetic” itself comes from the science of geodesy, literally in Greek JHZGDLVLc D - “division of the earth.” And if geodesics on a plane are straight lines, then finding geodesics on other surfaces is sometimes very difficult. The greatest mathematician Leonhard Euler (1707–1783) derived the general equation of geodesic lines in 1732. Later they were transformed into the Euler–Lagrange equations and became the main tool not only for constructing geodesics on surfaces, but also in other extremal problems. The main application of surveyors at that time was cartography (hence the name). The distance between two points on the map must always be measured using a geodesic, and this should be done taking into account

DOI: https://doi.org/10.4213/kvant20201102

⟦column⟧

terrain. Then geodesics began to be used to construct the internal geometry of an arbitrary surface, where it is natural to take the shortest distance along the surface as the distance between points. However, it is necessary to distinguish geodesic lines from shortest lines! What is "geodesic"? A geodesic on a surface is a line that is locally shortest at each of its points. This means that for any point M lying on a line, the following is true: whatever points A and B are taken on the line that are sufficiently close to M, the geodesic arc AB is the shortest path along the surface between A and B. A mathematician will formulate the locally shortest property as follows: for any two points lying in some neighborhood of the point M, the geodesic arc is the shortest path along the surface between them. Note that the shortest path between any two points is a geodesic line, but the reverse is not always true. The red line on figure 1 is geodesic, although the shortest path from point A to point C does not go along this line - there is a shorter one. But for

Fig. 1. Geodesic – locally shortest line

⟦folio 11⟧

SHORTEST

WAYS

AND

has been proven. This was done by Soviet mathematicians Lazar Aronovich Lyusternik (1899–1981) and Lev Genrikhovich Shnirelman (1905–1938), and for this they developed a new theory of topological methods in variational problems. Well, much later, in 1992, American mathematicians J. Franks and W. Bangert proved that in fact on any smooth convex surface there are not three, but infinitely many closed geodesics. Stop, stop! How infinitely many? We know that there are three of them on the ellipsoid! No, something is wrong here. We open “Visual Geometry” by Hilbert and Cohn-Vossen, we read: “So it can be shown that on a triaxial ellipsoid the only closed geodesic lines without self-intersections are those three ellipses that are obtained at the intersection of this surface with three planes of symmetry.” This means “it can be shown.” But the authors do not write how exactly. Didn't they become victims of self-deception, like P. Fermat, who “didn’t have enough space” in the margins of the book to prove his Great Theorem? After all, according to the Franks-Bangert theorem, there are infinitely many geodesics on any smooth convex surface, which means on an ellipsoid too. It turns out that Hilbert and Cohn-Vossen were wrong? And Poincaré, who did not question the fact that there are exactly three of them on a different-axial ellipsoid? And Uryson, and Lyusternik, and Shnirelman - were they all wrong? Yes! Moreover, they all missed the elementary example of a “fourth” geodesic on an ellipsoid. This example appeared in 1982 in W. Klingenberg’s book “Riemannian geometry”, and then many times $переоткрывался.^{1}$ The fourth geodesic on an ellipsoid. This example is so clear and wonderful that it can be analyzed

1 For example, it was independently invented in 2004 by the Russian mathematician S.S. Anisov, who reported it to the author. Only much later did we learn that the same example was contained in Klingenberg's book.

HYPOTHESIS

POINCARE

⟦column⟧

during lessons at school. Everyone has seen how they tie up boxes of candy: they run part of the tape down, along the bottom of the box, then lead it up, along the lid, then lower it down again, and then up again. The result is a line of four parts - two opposite parts at the bottom and two at the top (Fig. 5). And now we need to do Fig. 5. The dressing is the same, but not on a spinning box, but on a round one. Now we will build this line on an ellipsoid. Let's take an ellipsoid in which one axis is much smaller than the other two. Almost flat. Let us denote the ends of the long semi-axes (in order) A, B, C, D. Let us connect A and B with the shortest line running along the surface of the ellipsoid. Since the ellipsoid is almost flat, this line will be close to segment AB and certainly will not go along the equator, because the length of the equatorial arc is greater than segment AB. Now let's draw the same arc AD along the other (lower) side of the ellipsoid. In other words, arc AD transforms into arc AB upon rotation $на^{180q}$ relative to axis AC. Next, let's run the same DC arc along the top side and end with a CB arc on the bottom side. We got a closed line consisting of four equal arcs (Fig.6). It turns out that it will be geodesic.

⟦figure⟧

Fig. 6. “Fourth” geodesic on an ellipsoid

Theorem 1. The constructed closed line ABCD is a geodesic on the surface of the ellipsoid. Proof. At each interior point of the arc AB the line is locally

⟦folio 12⟧

KVANT 2020/№11–12

the shortest. If not, just replace its small piece with a shorter one and get a shorter path $из^{A} в^{B,}$ which is impossible. The same goes for the other three arcs. Thus, everything is fine at the interior points of the arcs. The problem occurs at the ends of the arcs. Why, say, in $точке^{A}$ Is our line locally the shortest? Let's take it nearby $с^{A}$ two $точки^{M} и^{N}$ on different arcs. Why $путь^{MN}$ along a line is the shortest path on the ellipsoid? This does not follow from the construction. Let's assume that $дуга^{AM}$ longer $дуги^{AN.}$ Then let's continue $дуги^{AN}$ for $точку^{N}$ point M c for which $дуга^{AM} c$ equal to $дуге^{AM}$ (Fig.7,a). Clear,

⟦figure⟧

Fig. 7

$что^{M} и^{M} c$ transform into each other when rotated by 180q relative to $оси^{AC.}$ If $дуги^{AM} и^{AN}$ are equal, then simply $обозначим^{M} c^{N}$. Now suppose the opposite: there is a shorter path on the surface of the ellipsoid between $точками^{M} и^{N.}$ By adding $дугу^{NM} c$ to this path, we get a shorter path along the surface $между^{M}$ and M c. This means that the shortest path $между^{M} и^{M} c$ does not coincide with the arc of our line MM c. Let's make a turn by 180q relative to $оси^{AC.} Точки^{M}$ and M c will change places, and the shortest path between them should turn into itself - after all, it is the only one! Let us denote $через^{P}$ the middle of this shortest path (distances are measured along the path). A rotation of 180° relative to $оси^{AC}$ leaves this point in place. But then it lies on the axis of rotation - $прямой^{AC.}$ And since it is on the surface of the ellipsoid, it coincides with either $с^{A,}$ or $с^{C.}$ Until $точки^{C}$ is too far, the shortest path does not go there. $Значит,^{P} A.$ So, the middle of the shortest path $из^{M}$ in M ​​c is in $точке^{A}$ (Fig.7, b). This means that the shortest path $из^{A} в^{M}$ goes along our line. Otherwise, we will put it instead of $дуги^{AM}$ and thereby reduce the length of $дуги^{AB,}$, which is impossible. This means that the shortest path $из^{M}$ in M ​​c

goes along our line, which contradicts the assumption. Now everything is proven.

⟦column⟧

Well, they promised a very elementary example... But it required a rather subtle reasoning. Yes, but this is for proof. And the construction of this example is really very simple. If a primary school teacher gives the children a similar flat ellipsoid and asks them to pull a rubber ring on it differently than along one of the three equators, they will undoubtedly succeed. Hook it with a loop at the top, thread it through the bottom, then with another loop at the top. It is all the more surprising that for many decades no one thought of this example. And no one, including the greatest mathematicians of the 20th century - Poincaré and Hilbert, allowed the idea that there could be a fourth geodesic on an ellipsoid. Miracles happen! In fact, this is not the only example of an “irregular” geodesic on an ellipsoid. There is more. In Exercise 5 we invite you to build them. And polyhedra are waiting for us!

Exercises

1. The surface of the mountain has the shape of a cone, the development of which is a third of a circle with a radius of 1 km. The two villages are located at the foot of the mountain, on opposite sides of the base. What is the length of the shortest path between them? 2. A traveler came out of one of the villages from the previous task, wanting to go around the mountain and return to the village. What is the length of the shortest route? Will this route be a closed geodetic? 3. On a right circular cylinder there are two obvious closed geodesics: the "belt" (a circle parallel to the base) and the "handle" (a rectangle containing two parallel diameters). Or maybe there are others? 4. The generatrix of the cone is twice the radius of the base. Construct a closed geodesic on its surface. What is its length if the base radius is 1? 5. Consider an ellipsoid in which one semi-axis is small and the other two are equal. Construct several new types of closed geodesics on it. Note. The geodesic from Theorem 1 can be called "quadrilateral" because it consists of four parts. Construct “hexagonal”, “octagonal” and similar geodesics.

(To be continued)
