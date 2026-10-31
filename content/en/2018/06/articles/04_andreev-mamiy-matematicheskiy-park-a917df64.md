---
id: 2018-6-andreev-mamiy-matematicheskiy-park-a917df64
issue: kvant_2018_6
year: 2018
number: "6"
title: Mathematical park
authors:
  - Андреев Н. Н.
  - Мамий Д. К.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 26
page_last: 29
page_labels: "27"
tag: 9LZH
lang: en
source: kvant_digital
extraction: native
content_sha256: ad760b987ec1913e4fd9e8b2645a7d20e65da1aead93d90625d234332f21ca11
prompt_sha256: draft-1
translated_from: content/ru/2018/06/articles/04_andreev-mamiy-matematicheskiy-park-a917df64.md
source_content_sha256: eb4db5e2d67be999b2f9a15e26c628e654306cd09022b1f9dd5e27e3e02d403c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

The open-air museum of mathematics “Mathematical Park” is a collection of art objects integrated into the urban space that illustrate mathematical facts and concepts. The goal of the project is to popularize mathematics, awaken interest and motivation to study this science in children and adults. A mathematics park was created in the city of Maykop, in the Republic of Adygea, on the basis of the Republican Science and Mathematics School (REMSH). For the past 20 years, she has been preparing the best schoolchildren from the Republic of Adygea to the level of prize-winners and winners of the All-Russian Olympiad in various subjects. About 50 graduates annually enter the best universities in the capital. The red carpets in the REMSH courtyard illustrate the famous problem of the Königsberg bridges, and the gazebo illustrates triangulation. The Möbius strip (see page 1 of the cover), which is the REMSH logo, is made of dolomite. On its one-sided surface are engraved three images of world-famous archaeological finds discovered in the burial mounds of Adygea: a silver rhyton vessel with a sculptural ending in the form of a winged horse Pegasus, a gold plaque-plate in the form of a lying deer, a protective gold plaque in the form of a panther. These finds indicate rich

⟦column⟧

our historical and cultural heritage of Adygea. The flying deer, found in a mound in the city of Maykop, belongs to the oldest known culture that existed on the territory of modern Russia (late 4th – mid 2nd millennium BC). This culture was called Maikop. The dodecahedron is one of the five regular polyhedra in three-dimensional space.

The idea of ​​the sculpture belongs to Asya Eutykh, a member of the Union of Artists of Russia, People's Artist of the Republic of Adygea, and the execution is by Tatyana Vaganova, designer, member of the Union of Artists of Russia. Classic geometric interpretation of the Pythagorean theorem, with squares, post-

⟦folio 27⟧

PROBLEM WORKER

on). It is known that when any child is identified, the remaining 99 children can be divided into 33 groups of three so that in each group all three are friends in pairs. Find the smallest possible number of pairs of friendly children.

Answer: 198. Let's translate the problem into the language of graphs, matching a child with a vertex and friendship with an edge. Then we know that in a given graph with 100 vertices, if any vertex is removed, the remaining ones can be divided into 33 triples so that the vertices in each triple are connected in pairs. What is required is to find the minimum possible number of edges in such a graph. First, let's build an example with exactly 198 edges. Let's divide 99 vertices, except vertex A, into 33 groups of 3 vertices. Let's connect the vertices in each triple in pairs; finally, connect A to all other vertices. Then the conditions of the problem are satisfied: when A is removed, the partition into triples is already reduced, and when any other vertex B in the same partition is removed, it is enough to replace B with A. Moreover, in the described graph there are only 33 3 99 198 edges. It remains to prove that this quantity is the smallest. Let's call a graph with 3k + 1 vertices good if, when removing any vertex, the remaining 3k vertices are split into k pairwise connected triplets. Let us prove by induction on k that a good graph has at least 6k edges on 3k + 1 vertices; for k = 33 we obtain the required estimate. The base for k = 1 is simple: since when any vertex is removed, the other three are connected in pairs, any two vertices must be connected, i.e. the number of edges is $C_{4}^{2} 6$. Let us prove the transition of induction. If there are at least 4 edges coming out of each vertex, the total number of edges is at least 3 k 1 4 2 2 3 k 1, which is even more than the required 6k. Otherwise, there is a vertex A connected to at most three others. If you remove any vertex except A, then A will end up in some kind of triple, which means it is connected at least

"QUANTA"

⟦column⟧

with two peaks. If one of these vertices is removed, A will remain at least two adjacent ones, i.e. there were at least three of them. So, A is connected to exactly three vertices B, C and D. Then when, say, B is removed, the vertices A, C and D form a triple, i.e. C and D are connected; similarly we find that B, C and D are connected in pairs. Let us now remove vertices A, B, C and D from our graph, and instead add one vertex X, connected to all with which at least one of the vertices B, C and D was connected. Note that in this case the number of edges decreased by at least 6 (i.e. by the number of edges between A, B, C and D). Let us show that the resulting new graph is good; from here the transition of induction will follow, because then the new graph will have at least 6 k 1 edges, which means that the original graph will have at least 6 k 1 6 6 k edges. Let some vertex Y z X be removed from the new graph. If it is removed from the original graph, the remaining vertices will be divided into triplets; Let vertex A be, for definiteness, in a triple with B and C, and vertex D in another triple. Then you can split the new graph in the same way, placing vertex X in the triple where vertex D was. Finally, if you remove vertex X from the new graph, you can do the same operation, assuming that vertex D was removed from the original graph (then A, B and C will automatically be in the same triple). Thus, the induction transition is proven. Note that the example given in the problem is not the only one. The reasoning from the second part of the solution essentially shows that many different optimal examples can be constructed in the following inductive way. For k = 1, take 4 vertices and connect all pairs with edges. When moving from k to k + 1, we will add three vertices B, C, D, connect them in pairs with each other, and also connect them all with some existing vertex A. In this example there will always be 6k edges, and it will satisfy the conditions of the problem. S. Berlov, N. Vlasova
