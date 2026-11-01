---
id: 1978-1-matiyasevich-modeli-mnogogrannikov-cef5fdcf
issue: kvant_1978_1
year: 1978
number: "1"
title: Models of polyhedra
authors:
  - Матиясевич Ю. В.
rubric: osnovnye-stati
page_first: 10
page_last: 19
page_labels: 8, 12, 13, 14, 16, 17
tag: B4FQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2c5bf2cbb2df842441515df8731d81b9fa7d052039f38f22483653c82632ba33
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/05_matiyasevich-modeli-mnogogrannikov-cef5fdcf.md
source_content_sha256: cd337ba4bda290d73de5db0eb6f38a4c3d46f5e83c2035e87f8387d7f8e362ca
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

Yu. Matiyasevich

Models
polyhedra

In a recently published translation of the book
M. Wenninger “Models of Polyhedra” (M., “Mir”, 1974) tells how you can make models of symmetrical polyhedra yourself, and shows photographs of the model taken by the author. These are undoubtedly very beautiful models that can decorate a math corner at school or a young mathematician’s room. However, this is what the author writes about their creation: “On average, each model took me about a thousand hours; I spent another three to four hours preparing the source material.”

This article talks about the designer invented by the American architect Fred Basseyti. Taking two hours to make it, readers will have the opportunity to assemble the desired polyhedron in a few minutes. Of course, the resulting models are not only beautiful, like kleeeen, but the ease of production, as well as the possibility of disassembling the model and reusing parts of them, makes up for this drawback. The assembly process of the cutters will undoubtedly bring

⟦folio 12⟧

There are two polygons that are mirror images of each other. They both have the same name and are considered one polygon when talking about the 13 Archimedean solids. Similarly, the two mirror variants have a flat dode-frame.

The most interesting picture arises when assembling the last Archimedean solid - the rhombicuboctadron. Here, after unambiguously surrounding the triangular face with square ones, it will be possible to choose between continuation trays - see the diagram on figure 3. The first two options have an unambiguous completion, but in the third, after unambiguously surrounding the second triangle, five ways of attaching the third triangle arise - see the diagram on figure 4.

How many different polyhedrons are there? Seven? No, just two. Options a, b, c1, c3 and c4 lead to the same polyhedron shown in figure 5, and options c2 and c5 lead to this polyhedron and to the polyhedron shown in figure 6. It is this last polyhedron that is called a rhombicuboctadron, and only it is an Archimedean solid.

What is the difference between a polyhedron with figure 5 and the other 13 Archimedean solids? Recall that at the beginning of this section we abandoned the requirement that the faces be identical, but we retained the requirement that the vertices be identical. We can consider that two vertices are identical if they can be combined in such a way that the convergence of the faces in them pairwise coincides with each other (in this case, replacement with mirror reflections is allowed). In the sense of this definition, all vertices of a polytope with figure 5 are the same. Why then is the given definition of the sameness of vertices so bad? The fact is that this definition is local in nature - it talks about the pairwise coincidence of only those faces that converge at the vertices being separated. Archimedean bodies have a stronger property: any two vertices can coincide so that all faces are multi-

Fig. 5.

Fig. 6.

the borders coincide in pairs with each other. A polytope with figure 5 does not have this property. The ancient Greeks had a highly developed sense of harmony and it is not surprising that this polyhedron was not included in the Archimedean solids. For two thousand years it was “in the shadows” and was “invented” independently in the middle of our country by several mathematicians in different countries. In our literature, this polyhedron is often called the Ashkinuse body, named after the Soviet mathematician who first drew attention to it.

How can you find out if there are still any semi-regular polyhedra? Distribution scheme

⟦folio 13⟧

The proposition here is in principle the same as in the case of the Platonic solids. At least three and no more than five faces must converge at the top (why?), therefore, it is enough to consider three types of vertices: $x \cdot y \cdot z$, $w \cdot x \cdot y \cdot z$, $u \cdot w \cdot x \cdot y \cdot z$ (the middle ones $u, w, x, y, z$ can be the same numbers). The correspondence results in three inequalities similar to inequality (1):

$$1 < \frac{2}{x} + \frac{2}{y} + \frac{2}{z},$$

(2)

$$2 < \frac{2}{w} + \frac{2}{x} + \frac{2}{y} + \frac{2}{z},$$

(3)

$$3 < \frac{2}{u} + \frac{2}{w} + \frac{2}{x} + \frac{2}{y} + \frac{2}{z}.$$

(4)

We must find all solutions to these inequalities in integers $u, w, x, y, z$ that are at least 3.

Let's start with the last inequality. Just as in the case of Platonic solids, from the inequalities $u \geq 3, w \geq 3, x \geq 3, y \geq 3$ and $z \geq 3$ and inequality (4) it is easy to deduce that $u \leq 5, w \leq 5, x \leq 5, y \leq 5, z \leq 5$. What remains (for the readers) is a final search of possibilities.

Inequality (3) holds for any $z$ if $w = x = y = 3$. This gives an infinite series of semiregular polyhedra of type $3^3 \cdot z$, called antiprisms. No other semiregular polyhedron (with four faces converging at one vertex) can have more than the same angular face, or the system of inequalities $w \geq 3, x \geq 3, y \geq 4, z \geq 12$ contradicts (3). Thus, the data can assume that $w \leq 11, x \leq 11, y \leq 11, z \leq 11$, and again we are left with a finite search.

The first inequality, which has many solutions, including those that do not correspond to any semiregular polyhedron, causes a lot of trouble. Here another condition will help us, which is an analogue of the triangle inequality: the sum of the plane angles of two faces is greater than the plane angle of the triangle. This leads to inequality

$$\frac{2}{x} + \frac{2}{y} - \frac{2}{z} < 1$$

(5)

(without loss of generality, we assume that $x \leq y \leq z$ and do not write down two more similar inequalities). Both inequalities (2) and (5) are satisfied for any $z$, if $x = 3, y = 6$ or $x = y = 4$. In the latter case, we obtain an infinite series of semiregular polyhedra of type $4^2 \cdot z$, called prisms. A semiregular polytope of type $3 \cdot 6 \cdot z$ exists only for $z = 6$ (why? what is it called?). For any other values ​​of $x$ and $y$ either $2/x + 2/y < 1$, and then $z$ cannot be as angular as large according to (2), or $2/x + 2/y > 1$, and then the upper limit $z$ is obtained from (5). In any case, the matter again comes down to the final search.

The patient reader, having considered all the remaining cases, will come to the conclusion that except for 5 Platonic solids, 13 Archimedean solids, an Ashkinuse solid and an infinite series of prisms and antiprisms, no other semiregular polyhedra exist (further with the local definition of the sameness of vertices).

Regular polyhedra

Let us finally discard both the conditions for the faces to be identical and the vertices to be identical, but we will retain the requirement that the faces be regular polygons and that the polyhedron itself be convex. How many more polyhedrons were you able to collect? It turns out that the number of new polyhedrons is finite.

The proof of this fact is used by a theorem similar to that from the school course that the sum of the external angles of any polygon is equal to 2π. An exterior angle is the complementary angle of a polygon up to its limit value of π. Similarly, we will call the curvature at a vertex of a polygon the difference between 2π (the limiting value) and the sum of the plane angles of all faces converging at this vertex. For example, the curvature of a vertex of type $3 \cdot 4 \cdot 3 \cdot 6$ is π/6. It turns out that if we sum up the curvature

⟦folio 14⟧

Well, over all the vertices of a convex polyhedron, then you will always get 4π (this can be checked on any model; the proof is easily obtained if we apply Euler’s theorem - see “Quant”, 1974, No. 4, p. 29; No. 5, p. 32; No. 10, p. 17). Consequently, there can be no more vertices of type 3·4·3·6 than 4π: π/6 = 24. The limit on the number of vertices of any other type is obtained similarly. The number of types of vertices is, generally speaking, infinite, but, going through all the possibilities in determining the number of semiregular polyhedra, we have established that all vertices, with the exception of a finite number of types, fall into one of the series 4²·z, 3³·z or 3·6·z. It remains for Telery to show that for a sufficiently large z, a regular convex polyhedron with a vertex from the first series is obligatory, a vertex from the second series is an antiprism, and a vertex from the third cannot exist.

After obtaining a qualitative result about the finiteness of the number of regular polyhedra, other than prisms and antiprisms, I would like to know their exact number. Эта задача была полностью решена ленинградским математиком В. А. Залгаллером. Its solution required consideration of a huge number of options, and members of the mathematical circle of 239 schools in Leningrad were brought to this work. In the book by V. A. Zalgaller “Convex polyhedra with regular faces” (Leningrad, 1967) many lemmas are given and their names are written by schoolchildren who by that time had become students. The author of the book thanks them and points out that without their active participation the work of the vedla would have been completed. In addition, another active participant in this research was the computer, which “considered” many cases and “proved” the corresponding lemmas (the nature of the computer’s contribution is discussed in more detail below).

The result obtained by V.A. Zalgaller is as follows: in addition to 5 plateau bodies, 13 Archimedean bodies, recognition and antiprisms, there are also significantly more

ровно 92 выпуклых многогранника с правильными граями. Интересно, сколько из них удался собственным «Кваента»? All ninety-two? Let us point out that for this it is sufficient to have faces of the same types that were necessary when assembling Archimedean solids, i.e. 3-, 4-, 5-, 6-, 8- and 10-gonal.

Or maybe one of the readers will assemble 93 new polyhedra from the construction set? Don’t be surprised, this is, generally speaking, possible, because assembling a polyhedron from construction kit parts does not guarantee its “mathematical existence.” To understand what the difference is here, consider an example of a polyhedron, the development of which is shown on figure 7, and the general view is shown on figure 8. The assembly of this polyhedron does not cause any difficulties, but let’s follow it closely.

For the purpose of definition, let the length of the sides of all polygons be equal to one. Faces A, B and D form a rigid trihedral angle and thereby fix the spatial relative position of points 1-8. Now we want to add face C. We managed to do this, or points 3 and 7 are located symmetrically to points 2 and 6 and, therefore, the distance between them is equal to 1. In the same way, it will be possible to separately assemble faces K, L, M, N into a rigid structure. Since both assembled parts are identical, then the distances between points 1 and 8 in them are equal, and we can combine these points in pairs (see figure 9). The resulting structure has only one degree of freedom, namely, the two assembled rigid parts can rotate relative to each other around an axis passing through points 1 and 8. In fact, from the assembled symmetrical one, the relative position of these parts is already fixed, for example, by the requirement that segments 4-5 and 11-12 are parallel. So, by this moment the spatial location of all points 1–14 others relative to each other is fixed. But we still need to add faces E, F, G, H, I, J. Can we do this? From the assembled symmetrical one it is clear that the distance between points 2 and 13 is equal to the distance between points

⟦folio 16⟧

6 and 9, 3 and 14, 7 and 10; Let's denote this distance by $a$. The possibility of practical assembly shows that with sufficiently high accuracy $a \approx 1$, but is there a strict equality $a = 1$, which is necessary and sufficient for the existence of the polyhedron under consideration? In such cases, a computer can come to the rescue. Of course, if the machine calculates that $a = 1,00000000$, then this does not mean at all that the polyhedron exists, or the machine performs all calculations with limited accuracy and $a$ may differ from one, say, in the twelfth digit. However, if the machine found that, for example, $a = 0,99998532$, and we are increased, that at least six signs of the machine are always correct, then this would immediately prove the lemma that the polyhedron with the development given in figure 7 does not exist. The majority of readers «Kvant» apparently do not yet have access to a computer, and they will have to use their art of trigonometric transformations here.

The considered example shows that a flat figure, which has all the external signs of a development of a polyhedron, may, generally speaking, not be a development of any three-dimensional body. To give a precise meaning to the words “external signs”, let’s introduce the concept of a workpiece. Namely, we will understand by a blank an arbitrary system of convex polygons, not necessarily correctly, whose vertices are assigned natural numbers (which will be the numbers of the vertices if a polyhedron can be glued together from the blank), so that if two neighboring vertices of a polygon are given numbers $i$ and $j$, then there is exactly one more polygon in which two neighboring vertices also have numbers $i$ and $j$, in addition, the edge connecting vertices $i$ and $j$ in one polygon has the same length as in the other polygon. We have already met with the crown conditions, easily verified by the workpiece, which are necessary for the existence of a convex polyhedron:

I. At least three faces must meet at each vertex,

II. The sum of the plane angles of the faces meeting at each vertex is less than 2π.

III. The sum of the curvatures of all vertices is 4π.

Obviously, the following conditions must also be met:

IV. For any two faces $A$ and $B$ there is a sequence of faces $C_1, \dots, C_k$ also that the faces $A$ and $C_1, C_1$ and $C_2, \dots, C_{k-1}$ and $C_k, C_k$ and $B$ have on a common edge.

It turns out that the four conditions listed above are sufficient - if the workpiece has properties I-IV, then some convex polyhedron can be glued together from it.

For work in which this global geometric result is central, A. D. Aleksandrov, now an academician of the USSR Academy of Sciences, was awarded the USSR State Prize in 1942.

Let us now return to figure 7. It is easy to verify that all four conditions I–IV are satisfied; therefore, a convex polyhedron can be glued from this blank. But why then did we encounter difficulties and doubts? The fact is that Alexandrov’s theorem does not state that the original system of polygons will be the system of faces of the polyhedron. Conditions I-IV are sufficient only if we allow some polygon to “break” during gluing. For example, according to Aleksandrov’s theorem, figure 10 shows a blank of some convex polyhedron. At first glance, it has two square and eight triangular faces, although in fact, when glued together, the result will be a generic cube. In the case of a workpiece with figure 7, the pentagonal faces may, for example, break along the dotted lines, thereby increasing the value of $a$. Sometimes, when assembling any polygon, the angles of breaking of the edges of the present are close to l, so that the fractures are not noticeable to the eye, and readers must remember to prove

⟦folio 17⟧

Attention
students
high school!

Store No. 8 “Technical Book” of Moscow sells and sends cash on delivery (without deposit) the following books:

Mathematics
Golomb S.V. Polymno (“Peace”), c. 46 k.
Dorofeev G.V. et al.
A manual on mathematics for university applicants (selected questions of elementary mathematics) (“Hayka”), c. 1 rub. 04 k.

Kantor I. L., Solodovnik A. S. Hypercomplex numbers (“Hayka”), c. 22 k.
Leetwood J. Mathematical mixture (“Hayka”), c. 37 k.
Rudnik A.E. et al. Collection of problems in elementary mathematics for technical “Hayka”), c. 55 k.
VYGODSKY M. Ya. Handbook of higher mathematics (“Hayka”), c. 2 r. 60 k.

Physics
Trigg J. Crucial experiments in modern physics ("World"), ts. 41 k.
Collection of problems and questions in physics for secondary specialized educational institutions (“Hayka”), c. 70 k.
Physics. Part I. Universe (“Hayka”), c. 1 rub. 30 k. Elementary textbook of physics (edited by G. S. Landsberg). Volume 3. Oscillations, waves. Optics. Structure of atoma (“Hayka”), c. 1 rub. 13 k. Shakhmaev N. M. Physics. Part I. Molecular physics. Electricity (“Vycisaya school”), c. 50 k.

Shakhmaev N. M. Physics. Part 2. Oscillations and waves. Optics. Structure atoma (“High School”), c. 53 k. Bytko N. D. Physics. Part 1 and 2. Mechanics, molecular physics and heat (“High School”), v. 51 k.
Bytko N.D. Physics. Part 3 and 4. Electricity, optics and structure of atoma (“High School”), c. 58 k.

Send orders (by postcards) to the address: 103031, Moscow, Petrovka, 15. Store No. 8 “Technical Book”.
