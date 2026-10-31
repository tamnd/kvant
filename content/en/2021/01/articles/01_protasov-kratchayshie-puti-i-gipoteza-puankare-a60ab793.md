---
id: 2021-1-protasov-kratchayshie-puti-i-gipoteza-puankare-a60ab793
issue: kvant_2021_1
year: 2021
number: "1"
title: Shortest paths and Poincaré's conjecture
authors:
  - Протасов В. Ю.
rubric: osnovnye-stati
page_first: 14
page_last: 23
page_labels: 13, 14, 16, 20, 21
tag: Q1BZ
lang: en
source: kvant_digital
extraction: native
content_sha256: 519eb8f100e6e104a30eaa994124e4f572ea27d6674c9ce12ee8baae104118e2
prompt_sha256: draft-1
translated_from: content/ru/2021/01/articles/01_protasov-kratchayshie-puti-i-gipoteza-puankare-a60ab793.md
source_content_sha256: e1f3f70de057c9fcdbf785cae11fcc2ecac1d11de5779e70f4be89343afaf507
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Shortest paths and Poincaré's conjecture

V.PROTASOV

The “CHILDREN'S” example of the fourth geodesic on the surface of an ellipsoid (Fig. 8) that we have constructed refutes the biggest misconception associated with the Poincaré conjecture. An ellipsoid with different axial lengths can have more geodesics, which means that the “three geodesics hypothesis” itself should apparently have been formulated differently. Neither Poincaré, nor Hilbert, nor Urysohn noticed this. And not only them. Here, for example, is what Andrei Nikolaevich Kolmogorov (1903–1987), the greatest Russian mathematician, wrote:

End. The beginning is in the previous issue of the magazine.

⟦column⟧

“Poincaré’s hypothesis is that in at least three different ways a stretched rubber ring can be put on our stone so that it, trying to shorten its length, will not slip off (i.e., so that its length cannot be reduced by a small shift to the side in a small area). In this case, only arrangements of the rubber ring without self-intersections are considered (for example, not having the shape of a figure eight). On the surface of a ball there are infinitely many such ring arrangements (along any “great circle”), on a triaxial ellipsoid there are exactly three (along three

Illustration by M. Kashin

⟦folio 13⟧

SHORTEST

WAYS

AND

⟦figure⟧

Fig. 8. Non-planar geodesics on an ellipsoid – red and blue lines

main sections) (emphasis added – V.P.).” And again “exactly three”! But suggesting the idea of ​​an example would be within the power of a younger student. It turns out that even at the school level it is quite possible to make a discovery important for modern science. Of course, this case is an exception. However, elementary geometry is sometimes enough to study geodesics. For example, for geodesics on the surface of polyhedra.

Geodesics on polyhedra “What new can be said about polyhedra? – you ask. “These are also convex surfaces, which means that everything we said earlier should be true for them as well.” Not really. The surfaces of polyhedra are not smooth - they have vertices and edges. This “trifle” in this case leads to dramatic consequences. On some polyhedra there are no geodesics at all (not a single one!). So neither the Lyusternik–Shnirelman method nor the Franks–Bangert theorem applies to polyhedra. But in this case, geodesics have a very simple, “school” description. It turns out that it will be possible to build them and get different results about them without using higher mathematics. Shall we try? We will see that on some polyhedra there are infinitely many geodesics. Moreover, on a regular tetrahedron there are geodesics of arbitrarily long length. Thus, a closed geodesic with a length of, for example, 100 km can be wound around a tetrahedron with an edge of 1 cm (without self-intersections!). But let's not get ahead of ourselves.

HYPOTHESIS

POINCARE

⟦column⟧

All results on the existence of closed geodesics on smooth surfaces are theoretical, their proofs are not constructive: they do not provide recipes for construction. It is possible to find periodic solutions to the Euler–Lagrange equations, but it is difficult. And the main problem is that this task is unstable, i.e. a small change in data entails a large change in the solution. This can cause significant problems when numerically finding the solution on a computer. What if we approximate a smooth surface with a polyhedron (with a very large number of faces) and construct a geodesic on it? Good $идея!^{2}$ This means that we need to learn how to construct closed geodesics on polyhedra. How to determine geodesics on the surface of a polyhedron? Firstly, on each face the geodesic must be a straight line segment, since on the plane there is only one locally shortest line - a straight line. Therefore, any geodesic on a polyhedron is a broken line with vertices on the edges. In order not to confuse the vertices of a polyhedron and the vertices of a broken line, we will agree to call the latter nodes. Two adjacent links of a geodesic polyline must lie on different faces. If this is not the case and, say, edges AB and BC lie on the same face, then take points $A_{1}$ and $C_{1}$ on these links, respectively, very close to point B (Fig.9,a). From the definition of a geodesic, the broken line $A_{1} BC_{1}$ must be the shortest path connecting the points $A_{1}$ and $C_{1}$, which, of course, is not true: the shortest path is the segment $A_{1} C_{1}$. So, links AB and BC lie on different faces. Let's expand these two faces onto a plane. Let us again use the locally shortest property at point B and obtain that the segments AB and BC after development must be on the same straight line. Otherwise, path $A_{1} BC_{1}$ can again be replaced with a shorter one -

2 Apparently, it was first expressed by V.M. Tikhomirov, a famous mathematician and long-time author of «Kvant». He formulated the problem of classifying closed geodesics on a polyhedron.

⟦folio 14⟧

KVANT 2021/№1

⟦figure⟧

Fig. 9. Optical property of geodesic

onto the segment $A_{1} C_{1}$ (Fig.9,b), and then put the development back on the surface of the polyhedron. Thus, on the development, adjacent links of a geodesic end up on the same straight line, or, what is the same, two adjacent links of a geodesic form equal angles with the edge they intersect. The angle at which the geodesic enters the edge is equal to the angle at which it exits. It is natural to call this property optical - “the angle of incidence is equal to the angle of reflection.” Finally, a geodesic cannot pass through the vertices of a polyhedron. Why is this? All for the same reason. Let's assume that node B is at the top. The sum of the plane angles at the vertex of a convex polyhedron is less than 360q. The polyline ABC cuts the plane angles at vertex B into two parts. In at least one of them the sum of the angles will be less than 180q. Let's develop these angles onto a plane. After unwrapping, angle ABC will be less than 180°. Then we again obtain that the path $A_{1} BC_{1}$ is not the shortest - it can be replaced by the segment $A_{1} C_{1}$, and then put the development back on the surface of the polyhedron (Fig.10). So, a geodesic is a broken line that does not pass through the vertices of the polyhedron at each node

Fig. 10. Geodesic does not pass through a vertex

⟦column⟧

which fulfills the optical property - the angles formed by adjacent links with the edge are equal. It is clear that this is sufficient: any broken line with such properties is a locally shortest line. Indeed, at each internal point of the link it is locally shortest because it is straight, and at a node it is locally shortest due to the optical property. We have proven an important statement, albeit a simple one (it doesn’t qualify as a theorem), so we’ll call it a proposition: Proposition 1. A closed line on the surface of a polyhedron is geodesic if and only if it is a broken line with nodes on the edges, not passing through the vertices of the polyhedron, and each node has an optical property. For a non-closed geodesic, this is also done, with the only caveat that it can begin or end at a vertex. Let's return to closed geodesics. If we expand two adjacent faces onto a plane, then the geodesic links passing through them will end up on the same straight line. Let's take an arbitrary node of the geodesic A and begin to sequentially unfold the faces while traversing the geodesic until we get to the same point A (we denote the second point on the development as A c; Fig.11). All geode-

⟦figure⟧

Fig. 11. The geodesic straightens on the development

zical turned into segment AA c. In this case, the angles marked at figure, equal due to the optical property, became the corresponding angles at the secant AA c. This means that the segments MN and M c N c, representing the same edge, are parallel. We have proven one more property that can be considered another (already third!) definition of a geodesic on a polyhedron: Proposition 2. A closed line on the surface of a polyhedron is a geodesic if and only if

⟦folio 16⟧

KVANT 2021/№1

Some of them hit two peaks. Since the pyramid has four triangular faces, the sum of all its flat angles is equal to 360q 2. Therefore, the sum of the angles in each part will be equal to 360q. One of the parts will contain two vertices at the base of the pyramid. The sum of the angles in each is equal to 2 D 60 q, where D is the angle at the base of the side face. This means that 2 D 60 q 180 q, therefore D 60 q, i.e. the side face is a regular triangle, and this is prohibited. Construction of geodesics on polyhedra. For this we have two ways. The first method: according to Proposition 2, you need to find a suitable development in which there would be two parallel (and identically oriented!) segments representing one edge. Then you need to take a point on each of them - A and A c. They must represent the same point on the edge, i.e., the segments NA and N c A c must be equal. Now we draw segment AA c. If it does not go beyond the sweep, then it depicts a geodesic. The second method: you can do without a sweep, using Proposition 1. Estimate which edges the geodesic can intersect (for example, from physical considerations: imagining that we are stretching a rubber ring), and then find the position of the nodes using the optical property. Are there geodesics? In the light of Theorem 3, we are now not sure whether different polyhedra have closed geodesics at all? Let's say the cube has them? Yes. And the cube, and the regular octahedron, and other popular polyhedra (see exercises 9–11). Moreover, as we know, each geodesic generates infinitely many isomorphic ones. For simplicity, we will identify all isomorphic geodesics and count only different ones, i.e. non-isomorphic. Cube One geodesic is obvious - this is the square belt (Fig.12,a). It does not pass through vertices, it has an optical property (it intersects all edges at right angles). So this is a geodesic, and it is not necessary to draw a development. If you think a little, there is a second one. This is a regular hexagon

⟦column⟧

⟦figure⟧

Fig. 12. Two geodesics on a cube

passing through the middle of the ribs (Fig.12,b). The optical property is also satisfied, all angles are 45q. This geodesic (like the previous one) is flat, it lies entirely in one plane. If we move this plane parallel, we get a geodesic isomorphic to it (Fig.12,c). This is also a hexagon, but no longer regular. It has the same perimeter. We agreed to identify isomorphic geodesics, so this case does not provide anything new. But it’s not easy to find the third geodesic on a cube! Here she is, at figure 13. She

⟦figure⟧

Fig. 13. Third geodesic on a cube

⟦figure⟧

Fig. 14. Development of the third geodesic on a cube

hexagonal and not flat! Intersects all edges at angles D and 90q D, where D is an angle whose tangent is equal to 2. For convenience, we indicated figure lengths of the segments, considering the side of the cube equal to 1. The two vertices are pro-

⟦folio 20⟧

KVANT 2021/№1

“cling” to the vertices of the tetrahedron. A node L of a geodesic is called a link node if it and two nodes adjacent to it lie on three edges emerging from one vertex D of the tetrahedron and are the nodes closest to D on these edges. In this case, D is called a link vertex for a node L. Thus, a geodesic on figure 18 is linked to each vertex

⟦figure⟧

Fig. 18. A geodesic of type (2;1) is linked to vertex D by node L

well tetrahedron; for vertices B and C the link nodes are $K_{3}$ and $K_{1}$ respectively. Theorem 5. Any geodesic $типа^{n;} m$, where $n t^{m} t 1$, has exactly 4 link nodes. They make up two pairs of opposite nodes of the geodesic, each pair splits it into two parts with the same number of nodes. Each vertex of the tetrahedron is a linking vertex for one of the nodes. Let $a_{1}$ and $b_{1}$ be the links of the geodesic leaving the link node, $a_{2}$ and $b_{2}$ the following ones, etc. Then the links $a_{i}$ and $b_{i}$ lie on the same face and there are no other points of the geodesic between them. Proof. Let us represent the geodesic g as a line on the development and show that g is linked to the vertex K from the proof of Theorem 4; the reasoning is the same for other vertices. Let us draw a straight line g c symmetrical to g with respect to point K. It is clear that the strip between g and g c does not contain other nodes except those lying on $g_{1}$. (Recall that $g_{1}$ is the parallel line closest to g on the development that contains a node.) Therefore, lines g and g c intersect all 6 lattice segments emanating from K, and

⟦column⟧

each of the six intersection points represents the node on the geodesic closest to vertex K on the corresponding edge of the tetrahedron. Consequently, the geodesic is linked to K. Moreover, the lines g and g c go parallel along the lattice triangles (faces) until they intersect 6 lattice segments coming out of K. It turns out that in this way you can obtain any of the infinite number of geodesics on the tetrahedron. We “pull” the geodesic over the trihedral angle at vertex D, then wrap it around the surface of the tetrahedron, making 2 n 2 m 1 bends through the edges, and hook it to vertex C. Any geodesic is obtained in this way, and each vertex of the tetrahedron can be chosen as the initial one. The same, but more strictly: the geodesic is hooked to vertex D by links $a_{1}$ and $b_{1}$, then links $a_{2}, b_{2}$ go along one face, meet the edge of this face at adjacent nodes, then $a_{3}, b_{3}$ go along the next face, etc., until finally the geodesic hooks to vertex C with sides $a_{2} n_{2} m, b_{2} n_{2} m$. A geodesic limits a strip on the surface of a tetrahedron to pairs of sides $a_{i}, b_{i}$.

“Understand things you cannot imagine” So, on a regular tetrahedron there are infinitely many types of geodesics, each type corresponding to a pair of relatively prime integers. It turns out that that's not all. Each geodesic can be “multiplied” so that it remains non-self-intersecting. A bunch of geodesics. A geodesic on a regular tetrahedron is defined by a straight line on the net parallel to an arbitrary integer vector. Let's draw not one, but several such parallel lines. They will all be geodetic. But another thing is surprising: they will not all intersect with each other. Proving this is quite simple. If two such geodesics $g_{1}$ and $g_{2}$ intersect at some point P, then consider the points $P_{1}$

⟦folio 21⟧

SHORTEST

WAYS

AND

and $P_{2}$, depicting it on the scan. It is clear that $P_{1} z P_{2}$, since the lines $g_{1}$ and $g_{2}$ are parallel. The points $P_{1}$ and $P_{2}$ on the development represent one point on the surface of the tetrahedron, therefore $P_{1}$ must be translated into $P_{2}$ either by an integer shift or by symmetry about the node. In this case, $g_{1}$ will turn into some straight line $g_{1} c$. Since both symmetry and translation preserve parallelism, line $g_{1} c$ is parallel to $g_{2}$, and therefore coincides with it, since it intersects with it at point $P_{2}$. It turns out that the geodesics $g_{1}$ and $g_{2}$ coincide. Not only can a geodesic longer than 1 km be wound onto a tetrahedron with an edge of 1 cm without self-intersections, but as many of these geodesics can be wound as desired (at the same time!), and all of them will not intersect each other. By the way, according to Theorem 4, they will all be isomorphic and will have the same length. We proved this easily - what could be simpler than a bunch of parallel lines on a plane! But it is no longer possible to imagine this on the surface of a tetrahedron! Academician L.D. Landau said that “science allows a person to understand things that he can no longer imagine.” At figure 19 we presented a pencil of three geodesics of type 1; 1.

⟦figure⟧

Fig. 19. A pencil of three geodesics of type (1;1)

Is it only on a regular tetrahedron that there are infinitely many geodesics? No, not only that. Any isohedral tetrahedron has this property. A tetrahedron is called isohedral if all its faces are equal. Getting such a tetrahedron is simple: you need to take an arbitrary acute-angled triangle and fold it along the middle lines (Fig.20). There are many properties

HYPOTHESIS

POINCARE

⟦column⟧

⟦figure⟧

Fig. 20. Isohedral tetrahedron

and signs of an isohedral tetrahedron. We collected some of them in Exercise 14. In all our discussions about geodesics, a regular tetrahedron can be replaced by an isohedral tetrahedron - nothing will change. Only the lattice will now consist not of regular triangles, but of identical triangles equal to the face. It turns out that an isohedral tetrahedron also has infinitely many geodesics, numbered by pairs of coprime numbers n; m. They are built in the same way - on an infinite scan. Are there other surfaces with such a variety of geodesics? An isohedral tetrahedron has geodesics that are arbitrarily long. What about other tetrahedrons? It turns out not. Among all tetrahedra, only the isohedral one has this property. Any other tetrahedron can have only a finite number of non-isomorphic geodesics - and they may not even exist at all, like a regular pyramid. Can there be an infinite number of non-isomorphic geodesics for a polyhedron other than a tetrahedron? As we have seen, neither a cube nor a regular octahedron is suitable for this role. In 2008, it was proven that no other polyhedron is suitable [9]. Among all polyhedra, only the isohedral tetrahedron has arbitrarily long geodesics. The same paper hypothesized that the isohedral tetrahedron is unique not only among polyhedra, but also among all convex surfaces. For ten years the hypothesis remained open, only recently it was proved by A.V. Akopyan and A.M. Petrunin [1]: If a convex surface has arbitrarily long closed geodesics, then this is the surface of an isohedral tetrahedron.
