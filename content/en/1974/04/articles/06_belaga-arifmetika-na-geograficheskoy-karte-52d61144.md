---
id: 1974-4-belaga-arifmetika-na-geograficheskoy-karte-52d61144
issue: kvant_1974_4
year: 1974
number: "4"
title: Arithmetic on a geographical map
authors:
  - Белага Э. Г.
rubric: osnovnye-stati
page_first: 25
page_last: 31
page_labels: 23-29
tag: 0UHP
lang: en
source: kvant_digital
extraction: vision
content_sha256: a66e1a9f9310762e01319cf0c243f43c2113ab81ff88447c274277e8a7ca29cc
prompt_sha256: draft-1
translated_from: content/ru/1974/04/articles/06_belaga-arifmetika-na-geograficheskoy-karte-52d61144.md
source_content_sha256: 23344b94440ac3a7ab298309db9dbcc02788920587278360e61558a5a9c34873
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

One of the chapters of an excellent book on graph theory *) begins with a description of ... the problem:

“The four-color hypothesis can rightfully be called the “four-color disease,” since it is in many ways similar to the disease. It is highly contagious. Sometimes it proceeds relatively easily, but in some cases it becomes protracted or even threatening. There are no vaccinations against it...”

This statement by the American mathematician F. Harari, very similar to the memo of an epidemiologist, is worth adding to the famous mathematician and teacher O. Ore:

“Nibolieu is famous among these problems **) - the problem of four colors, first posed to mathematicians by De Morgan around 1850. No other gap has generated so many and ingenious works in graph theory. Thanks to its simple formulation and striking elusiveness, it still provides a powerful stimulus for the study of various properties of graphs” ***).

*) F. Harari, Graph Theory, translation from English. Publishing house "Mir", M., 1973.
**) This refers to graph theory problems. — Approx. ed.
***) O. Ore, Graph Theory, translation from English, Nayka Publishing House, M., 1968.

Apparently, it is precisely the “irritating elusiveness” of this problem-hypothesis that is the main causative agent of the disease described by F. Harari; As for the “simple formulation”, it is probably known to most readers: any map on the sphere can be colored in no more than four colors, poppy, so that any two sessions of the country are painted in different colors.

This refers, of course, to an idealized map: on geographic maps, one color (blue) always corresponds to water surfaces. We will assume that they are not on our maps, just as there are no countries consisting of two or more unrelated parts (this is the case, for example, with Danna and its overseas province of Greenland). These examples show that the concept of a map needs clarification.

Our goal is to talk about one of the earliest and, perhaps, the most ingenious approaches to solving this problem - it can conventionally be called argumentative; work in this direction continues and the concept continues, and our story will bear almost no resemblance to a personal presentation of personal discoveries.

The conditions of the tasks, the solutions of which are given at the end of the issue, are actually part of the text; some of them are no more complicated than pictures from “Color It Yourself” albums.

⟦folio 24⟧

Maps on the sphere
We will call a map on a sphere any partition of the sphere by segments of smooth curves into a finite number of areas—countries of the map. Regarding these curve segments, the following are naturally assumed:
1) each of them has no self-intersections;
2) any two of them either do not intersect at all or intersect at their end points;
3) the end points of any of them are among the end points of one or more other segments, that is, they are not “hanging”.
It is clear that each of these segments, which together make up the boundaries of the map, is part of the border of two countries (or this entire border); We will also call countries neighboring. Let us note, by the way, that a rigorous proof of the statement beginning above with the words “it is clear that...” and called Jordan’s theorem is extremely cumbersome, despite all its very apparent appearance.
It is convenient to draw spherical maps in the form of a “continent” divided into countries, surrounded by an “ocean” - one of the countries (at figure 1).

Fig. 1. Map (countries A to N), correctly colored in four colors.

Fig. 2. A map for which the number of unconnected pieces of the boundary graph (the number of “islands” in the “ocean” A) is equal to trem (Krp = 3).

ke 1 country A; There can be several “continents”, as on figure 2). Countries M and E at figure 1 are not neighboring countries, although they have a common border point; countries D and E even have two separate sections of a common border.

We also require that there be no countries on the map that have only one neighbor (“islands” in the “ocean”); Maps with such countries are, of course, no more difficult to color, but the presentation is complicated by exceptions and clarifications.

Card coloring pages
A coloring of a map in n colors is called a regular n-coloring if any pair of neighboring countries are colored in different colors. Having drawn several spherical maps and colored them, you can easily see that although there are maps for which three or even two colors are enough for proper coloring, such maps are “atypical” - a total of four colors are needed.

Task 1. Draw a map of four countries that could not be colored correctly with two or three colors.

Task 2. a) n circles are given on a plane. Prove that for any arrangement of these

⟦folio 25⟧

independently find proof of this fact, established at the end of the 19th century.

Map graphs

Any system of points and lines connecting some of these points and not intersecting in pairs is called a graph; points are called vertices, lines are called edges of the graph.

As can be seen from the definition and properties 1) - 3) of a map on a sphere, it is characterized by its boundary graph; its vertices are points at which at least three countries converge, its edges are sections of the boundaries between the vertices (Fig. 3). We will also define a capital graph and a road map; its vertices are the “capitals” of countries (arbitrary but fixed points, chosen one by the interior of each country), the edges are “roads” connecting the capitals of neighboring countries (one on each pair of neighbors) and the passage through the section of borders between them (Fig. 4, 5).

The coloring of the map can be replaced by the coloring of the vertices of the capital graph and the road of this map; the correctness of the coloring has the same meaning if the conditions are two vertices of any graph

Fig. 3. Map boundary graph.

circles, the map they form can be correctly colored with two colors.

b) Create the conditions necessary and sufficient for the map to be correctly colored with two colors.

As a result of many years of short work, it was proven that any map containing no more than 41 countries has a correct 4-coloring. From this it is clear that if there is an example that refutes our hypothesis, it is difficult to construct it. At the same time, a regular 5-coloring exists for any spherical map. Try

Fig. 4. Countries from A to N, their capitals and roads.

Fig. 5. Graph of capitals and map roads and its regular 4-coloring.

⟦folio 26⟧

Fig. 6. The red lines depict the edges; the graph of capitals and roads of the map of Figure 1 is enough to reach the triangulation graph; These edges could be constructed in a different way (for example, ME together with NI, etc.).

fa are considered adjacent when they are connected by an edge.

Starting to color the vertices of the graph of capitals and roads of the map on the sphere, let’s check whether it can be supplemented with an edge that does not intersect other edges of the graph, and if so, then we will supplement it (for example, the graph in Figure 5 with edge AK). Any correct 4-coloring of the resulting graph will also be correct for the original graph; the converse, generally speaking, is not true - two unconnected vertices have become adjacent and must be of different colors. We will continue this process of adding edges.

Task 3. Prove that this process ends at the moment when the graph partitions the sphere into curved extrusions. (figure 6 shows a graph derived from the graph in Figure 5.)

Such a graph is called a sphere triangulation graph *), and the triangle is called the edges of the graph. figure 7 depicts a graph of vertices and edges (in the traditional geometric understanding of these words - “vertex of a tetrahedron”, “edge of a cube”) of a regular 2decahedron - icosahedron; Line 20 looks like the outer part of the XYZ triangle.

Task 4. What should a map be like for its graph to flatten and become a triangulation graph?

Task 5. a) Prove that the graph of vertices and edges of a regular octahedron - a windowhedron - can be correctly colored by threes.

b) Formulate the conditions necessary and sufficient for the triangulation graph to have a 3-coloring.

Geometry coloring book

A correct 4-coloring of the vertices of any triangulation graph of a sphere can be given a simple and red geometric meaning. This explains our desire to move from the graph of capitals and roads of the map to its triangulation graph, although the task of coloring itself is at first glance a condition.

Consider a neoctor tetrahedron, which of its four vertices is colored in its own color (Fig. 8, d). Suppose now that the non-actor graph triangulates the sphere correctly

*) Triangulation (geodesic term) - dividing the terrain into triangles.

⟦folio 27⟧

Fig. 8. The process of superimposing the surface of an octahedron on the surface of a tetrahedron.

painted in the same four colors. Thus, each of its vertices corresponds to a vertex of the tetrahedron, and any two neighboring ones are different. And this means that each edge and each face of the graph corresponds to a certain edge and a certain face of the tetrahedron: an edge of the graph is an edge of the tetrahedron, the vertices of which are painted in the same two colors as the vertices of the graph edge, and the faces of the graph are a similarly defined face of the tetrahedron. We can imagine this correspondence as the superposition of the colored triangulated surface of a sphere on the tetrahedral surface of a tetrahedron, the vertices of which symbolize the four coloring colors. This overlap can be found with any triangulation vertex colored in some color by combining it with a tetrahedron vertex of the same color. Moving to the adjacent vertex of the triangulation and combining it with the corresponding color vertex of the tetrahedron (which is always different from the first!), we simultaneously obtain the alignment of the edge of the triangulation with the edge of the tetrahedron. In the same way, we combine the triangulation face with the tetrahedron face, and then, step by step, add the desired overlay.

The described superposition process is depicted in figure 8 (a - e) for the surface of a regular octahedron - an octahedron. Having carefully traced the details of this process using the example figure 8, it is not difficult to understand why such an overlap with the 4-coloring is possible and how it occurs (in part, the surface of the sphere must be considered flexible and allowing self-intersection if necessary).

Arithmetic coloring book

If, when applying a specific triangulation vertex, it is enough to indicate the vertex of the tetrahedron in which it passes (that is, the color of the color), and when applying a specific face, it is not enough to indicate the face of the tetrahedron - you also need to know which side it is superimposed on this face - “front” or “back”. This can be seen using the example of the overlay shown in figure 8. Let us now form the following rules.

(*) If, when a face of the assignment graph is superimposed on a face of the metrahedron, its outer side overlaps with the outer side of the face of the metrahedron, then we assign the number +1 to this face of the assignment graph; if on the inside, then - 1 (see Fig. 8, a).

⟦folio 28⟧

These numbers are called coloring Heawood numbers - in honor of the English mathematician P. Heawood, the pioneer of coloring problems and the discoverer of “arithmetic” laws in the four-color problem.

The main, albeit obvious, property of Heawood numbers is the following:

Lemma. If the Heawood numbers of two adjacent faces of the trenagulation are equal, then these faces are mapped onto different (but, of course, all-neighboring) faces of the metrahedron; if they are not equal, then these faces are mapped onto one face of the metrahedron, one with the “front” side, the other with the “soap” side.

This lemma only details the definition of Heawood numbers; but the following three arithmetic properties of these numbers are quite unexpected at first glance:

1) The sum of all Heawood numbers of the correct coloring of the vertices of a trenagulation graph is divisible by 4 (this property became known recently).

2) Let's take any vertex of the trenagulation; the sum of the Heawood numbers of the faces meeting at this vertex is divisible by three (this fundamental fact was discovered by Heawood in 1898).

3) On the contrary, if we manage to select numbers ±1 for the faces of the trenagulation graph so that they satisfy condition 2), then the coloring problem is solved - we can impose trenagulation on the surface of the metrahedron, observing the rule (*); condition 2) will ensure the feasibility of such an imposition.

Statements 1), 2), 3) can be illustrated by figure 9, which depicts the icasedron graph and its regular 4-coloring.

We will prove only statement 1); the proof of statement 2) is similar and constitutes the content of task 6; proof 3) is not entirely elementary, and we do not present it. Let us only note that divisibility by three is due to the fact that in

⟦folio 29⟧

We will prove that the sums of the Heawood numbers of the faces included in each of these groups are equal to each other (if one of the groups is empty, that is, does not contain a single face, then it is natural to consider the corresponding sum equal to zero; then the other sums will also be equal to zero). Since the sum of all Heawood numbers decomposes into sums over four groups of faces, then from the equality of these sums over groups the divisibility by evens will follow.

Let us arbitrarily choose two faces of the tetrahedron. Let us consider the corresponding groups of triangulation faces and compose the sums of the Heawood numbers of the faces for each of these groups. Let us now take any triangulation graph included in one of these groups, and its edge that maps to the common edge of the two edges of the tetrahedron that we selected at the beginning. Let us consider the triangulation graph that has this common edge with the first nominal one; It is clear that such a connecting face is uniquely determined. Moreover, it can be mapped onto only one of the selected faces of the tetrahedron and therefore either belongs to the same group of faces as the first - then, by the lemma, the Heawood numbers of these faces are not equal, or enters the second of these groups - and then, by the same lemma, the Heawood numbers of these two faces are equal. It follows that if one of the two sums we are considering includes a term (the Heawood number of a certain face), then either the other sum includes an equal term (the Heawood number of the only neighboring face from the second group), or the same sum includes a term equal in value but opposite in sign (the Heawood number again of the only neighboring face, but this time from the same group). These equality of the two sums has been proven.

Task 6. Prove property 2) of Heawood numbers using the same method.

Don't color, but calculate

Property 3) of Heawood numbers allows us to begin the problem of finding a correct 4-coloring with some arithmetic problem on a graph: we look for the values ​​of the unknowns $x$ (Heawood numbers)
