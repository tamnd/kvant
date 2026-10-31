---
id: 1973-8-berezina-o-grafah-s-tsvetnyimi-rebrami-cdd55db2
issue: kvant_1973_8
year: 1973
number: "8"
title: On graphs with colored edges
authors:
  - Березина Л. Ю.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 51
page_last: 54
page_labels: 49-52
tag: UQTC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 015c1f3db0b379307131a38196ed563dc9d8f0d5bcf580111787d805587d006b
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/09_berezina-o-grafah-s-tsvetnyimi-rebrami-cdd55db2.md
source_content_sha256: c42747bc2a254fc7bdb03203a17dd107c8dc840c7616c5f6b5bdb468b7a90dbf
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

About graphs
with colored ribs
L. Yu. Berezina

If there are several points and a line on the plane, each of which connects a pair of our points, then we say that a graph is given. The points are called the vertices of the graph, and the line is its edges. The edges of a graph can be colored in several colors, then it is called a graph with colored edges. figure 1a shows a graph with fifth vertices and edges of two colors. This graph can be depicted with other dissimilar figures, for example, 16 and 1c*).

This article considers only those graphs in which each

*) Indeed, a graph with colored edges can be specified by a table with $n$ rows and $n$ columns, where $n$ is the number of vertices. To do this, you need to number the vertices, and at the intersection of the $i$th row and the $j$th column of the table write the color of the edge connecting the $i$th and $j$th vertices. It is easy to imagine that it is possible to number the vertices of the graphs in Figures 1a, 6 and c so that the tables turn out to be the same. That is why we say that this is the same graph.

This pair of vertices is connected by an edge. Such graphs are called complete. However, since other graphs are not considered here, we will not write the word “complete” every time.

The use of graphs with colored edges simplifies the solution of some problems and makes them more meaningful.

Let's now move on to solving problems.

Task 1. Six cyclists participate in a chess game, which is played in one round. Prove that among them there will always be a Murire participant who has already held all the meetings with each other, or who have not yet met with each other of any party.

Solution. Any two participants in the tour are invariably in one of two relationships with each other: they have either already played a game with each other, or have not yet played. We assign each participant a vertex of the graph. Connect the vertices in pairs with edges of two colors

Fig. 1a. Fig. 16. Fig. 1st century.

⟦folio 50⟧

Comrade Let the red edge indicate that two have already played with each other, and the blue one that they have not played. We got a graph with six vertices and edges of two colors. Now, to solve the problem, it is enough to prove that in such a graph there must be a “triangle” with one-sided sides.

Note that from an arbitrary vertex of our graph at least three edges of the same color will inevitably go to the heel of the others (prove this). For example, let three edges of red color (Fig.2) come out of vertex A. What color edges can connect vertices B, C and D? If at least one of them turns out to be red, as in figure 3, then you get a triangle with red sides. If all these edges are blue, as in figure 4, then they form a triangle with blue sides.

The problem is completely solved. In addition, when solving it, two properties were proved.

Property 1. Any vertex in a graph with six or more vertices and edges of two colors will produce at least three edges of the same color.

Property 2. In any graph with six or more vertices and edges of two colors there is at least one triangle with one-point sides.

Task 2. Five cities were selected on a geographical map. It is known that of any three of them there will be two connected by avalinium, and two not connected. Prove that it is true:

1. Each city is connected by avalinium to two and only two other cities.
2. Having departed from any city, you can make the path of the remaining cities easier by increasing each one once, and return back.

Solved and e. Each two cities are in one of two relationships - they are either connected by avalinium, or not connected. Let the vertices of the graph correspond to cities, the red edge to the presence of avalinia, and the blue edge to the absence. According to the condition, among the three edges connecting any three vertices, one edge is red, the second is blue, which means that the graph does not have a single triangle with one-piece sides. It remains to show that in a graph with a fifth vertex and edges of two colors, each vertex belongs to two red and two blue edges, and the red edges form a closed line passing through each vertex only once, or otherwise, that in such a graph there is a “pentagon”, all of whose sides are red, and all of whose diagonals are blue.

It is clear that from each vertex of the graph there are two red edges and two blue edges, since otherwise a triangle with one

⟦folio 51⟧

non-colored sides. Consequently, each city is connected by aunalia to two and only two cities.

Now let's select one of the vertices, for example $A$, and let's say the edges $AB$ and $AC$ (Fig. 5) will be red. Edge $CB$ cannot be red, therefore one of the edges either $CD$ or $CE$ is red. Let red be $CD$. If we now connect vertices $B$ and $D$ with a red edge, then vertex $E$ must be connected by red edges with vertices that already belong to two red edges. According to the condition, this is not possible. It remains to connect the vertices $D$ and $E$, $B$ and $E$ with red edges. The remaining ribs should be blue (Fig. 1a).

Together with the solution of the problem, one more property of the graph was obtained.

Property 3. If a graph with fifth vertices and edges of two colors does not have a triangle with one-point sides, then the graph can be depicted as a “pentagon” with red sides and blue diagonals.

Task 3. Less than half of the six melephone subscribers may or may not trust each other over the melephone. Prove that it is always possible to find two triplets of subscriptions, in each of which either everyone has spoken to each other, or everyone has not spoken. (This task generalizes task 1).

Solution. Let a graph with six vertices $A, B, C, D, E, F$ have red edges corresponding to parameters who spoke to each other on the phone, and blue edges to those who did not speak. Then there is at least one triangle with single-arm sides, for example, triangle $ABF$ with red sides. Temporarily excludes from consideration one of its vertices, say $A$, along with the edges emerging from it. Is there a triangle with one-point sides in the remaining graph with five vertices? If found, then it is also contained in the original graph. Otherwise, we get a fifth triangle with red sides and blue diagonals (Fig. 6). Now restores the sixth vertex $A$ with its edges. Ribs $AF$ and $AB$ are red. If edge $AE$ or $AC$ is also red, then at least one more triangle with red sides $AEF$ or $ABC$ is formed. If these edges are blue, then a triangle $ACE$ with blue sides will appear.

A graph property has been established, which is a generalization of property 2.

Property 4. In any graph with six or more vertices and edges of two colors, there will always be two triangles with one-point sides. These two triangles may have a common vertex or even a common edge.

If two triangles have a common vertex or a common edge, then they are called linked.

Task 4. An isozem group of plants is “homogeneous” if any two plants from this group are familiar, or

⟦folio 52⟧

Fig. 8. On the contrary, we don’t know each other. Prove that among all the people who meet by chance, there will always be two homogeneous groups, consisting of three people each, and no one from the first group is included in the second.

In other words, we are trying to prove that in a graph with eight vertices and edges of two colors there will always be two unjoined triangles with homogeneous sides.

Solution. Consider in the graph one of the triangles, for example KLM, with one-year sides. If the remaining five vertices and the edges connecting them in pairs contain a triangle with one-year sides, then it will be the second required triangle. If the remaining five vertices A, B, C, D, E do not contain a triangle with one-year sides, then they form a pentagon with red sides and blue diagonals (property 3). figure 7 does not show all the edges of the graph, but only the triangle KLM with red sides and the pentagon ABCDE with red sides and blue diagonals. Let us show that if any vertex of the triangle KLM is connected to two vertices of the pentagon taken through one, for example, K with A and C (Fig. 8), then there is one triangle with one-year sides that is not integral with the triangle ACK. Indeed, let's look at the pentagon BDELM. It is clear that it is impossible to color the edges BL and BM so that it turns into a pentagon with red sides and blue diagonals. Therefore, it necessarily contains a single-element triangle, not integral with the triangle ACK (Fig. 9).

It remains to consider the case when each vertex of the triangle KLM is connected by red edges to at least three consecutive vertices of the pentagon ABCDE. Let, for example, vertex K be connected by red edges to vertices A, B and C. Then vertices L and M are connected by red edges to A, B and C. Otherwise, there are two unshaped triangles with vertices K, L or M and bases - sides of the pentagon ABCDE. But then (see Fig. 10) we find two triangles CLM and ABK with red sides. Thus, in all cases there are two unmelted triangles with one-year sides.

Let us now solve the problem proposed at the Sixth International Mathematical Olympiad.

Task 5. Which of the 17 scientists corresponds with the rest. In their search for ribs, we will find three places. Which pair of scientists corresponds with each other in only one place. Prove that at least three scientists correspond with each other in the same place.

Solution. The conditions of the problem correspond to a graph with seventeen vertices and edges of color points.
