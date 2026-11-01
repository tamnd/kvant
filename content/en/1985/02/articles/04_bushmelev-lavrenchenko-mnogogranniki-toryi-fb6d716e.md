---
id: 1985-2-bushmelev-lavrenchenko-mnogogranniki-toryi-fb6d716e
issue: kvant_1985_2
year: 1985
number: "2"
title: Tori polyhedra
authors:
  - Бушмелев А. В.
  - Лавренченко С. А.
rubric: osnovnye-stati
page_first: 5
page_last: 6
page_labels: 3-4
tag: XK38
lang: en
source: kvant_digital
extraction: vision
content_sha256: f3e4e7dfa92ff67bd12e90819fdfecd6dc3d89d339c0b4fa0be39f358086e53d
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/04_bushmelev-lavrenchenko-mnogogranniki-toryi-fb6d716e.md
source_content_sha256: 641accf2381c612fc9d0f91802966c10f2d895441568f5899f2bbe03f1a1f662
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 3⟧

Tori polyhedra

A. V. BUSHMELEV, S. A. LAVRENCHENKO

This note talks about how to find a torus (donut) shaped polyhedron with the fewest number of vertices. Cardboard models of such “record” torus polyhedra (with 7 and 8 vertices) are shown in the photographs above. The note talks not only about the theory of the issue, but also gives recipes for making such models.

A polyhedron is a surface that bounds a certain volume and consists of a finite number of flat polyhedrons—the faces of the polyhedron. The sides of the faces are called edges. Each edge is adjacent to exactly 2 faces. You can move from any face to another by passing through the edges. Faces can intersect either at one vertex or along one entire edge.

Let’s assume that our polyhedra are rubber, and therefore, after “inflating” them like balloons, one of them will resemble a sphere, others will resemble a torus, others will resemble a crepe, etc. (Fig. 1). In the future, polyhedra will only include polyhedra with triangular faces.

Triangular networks on the surface

When a given polyhedron is “inflated,” the edges and faces are curved, and a network of curved triangles is formed on the “inflated” polyhedron. Thus, each polyhedron corresponds to a triangular network on a sphere (if the polyhedron is of the sphere type) or on a torus (if the polyhedron is of the torus type).

Such a triangular network can be drawn directly on the surface of a sphere or torus. To do this, you need to mark a certain number of points (nodes) on the surface, connect them with non-intersecting lines without self-intersections (arcs) so that the surface is divided into parts (regions), each of which is limited by treyagums and treyaguses, and the intersection of two regions is either empty, or consists of one node, or consists of one edge.

Implementation of polyhedra networks

Now it is natural to pose the following question: is every triangular network drawn in the above manner on the surface of a sphere or torus obtained from the vertices, edges and faces of some of the polyhedron of its “inflation”? In other words, can any triangular network on a sphere or torus be realized as a real polyhedron so that the nodes

⟦folio 4⟧

and vertices, arcs and edges, regions and faces would correspond one-to-one with each other while preserving contiguity (that is, so that nodes connected by another would correspond to vertices connected by the corresponding edge, and arcs bounding a region would correspond to edges bounding the corresponding face)?

For the positive sphere, the answers were established long ago by the German mathematician Steinitz, who also proved that a polyhedron realizing a network can always be convex. A generalization of Steinitz's theorem has now been proven to cover the following case: every triangular network on a torus is realized by a polyhedron.

Examples of triangular networks on a torus

In order to give such examples, you can take a rubber tube in the shape of a torus, mark the nodes on it and draw the arcs of the network. However, what will result will be difficult to depict on a sheet of paper, so we will use the following development of a torus on a plane. Let's draw two closed lines on our camera - $C_1$ and $C_2$ (Fig. 2a)). Then we cut the chamber along line $C_1$ (Fig. 26)), after which the chamber can be deformed into a cylinder (Fig. 2c)). We cut this cylinder along the lines $C_2$, and what we get (Fig. 2d)) is stretched on a plane in the form of a square (Fig. 2d)). So, the torus can be depicted on a plane in the form of a square with the ratio of opposite sides.

Without proof, we report that the list of triangular networks on a torus with 7 and 8 nodes is exhausted by figure 3.

Task. Prove that there are no torus-type polyhedra with fewer than 7 vertices.

Note. Use Euler's formula $\Gamma - P + B = 0$ and the correspondence $3\Gamma = 2P$ (following from the fact that for triangular networks, each edge is adjacent to 2 edges, and each edge is bounded by 3 edges), where $\Gamma$, $B$, $P$ are the number of faces, vertices and edges, respectively.

Methodology for implementing networks with a small number of nodes

Let's start with the implementation of network 6) (Fig. 3) (the model is shown on page 3 on the right). Six vertices are located in some plane $a = (v_2v_5v_7)$ (Fig. 4). In the same plane $a$ there are 4 faces - $v_7v_2v_3$, $v_7v_3v_8$, $v_8v_4v_5$, $v_2v_4v_5$. Let's place the vertex $v_1$ somewhere above $a$, and $v_6$ somewhere below it. For each face emanating from $v_1$ (from $v$), the edge opposite to vertex $v_1$ (vertex $v_6$) lies in the plane $a$; all such edges are placed in red (red) on figure 4.

Let's move on to implementing the remaining networks. We will need the polyhedron rearrangement transformation (Fig. 5), which can be applied to the pale of faces that, when combined, give a flat convex quadrilateral. In the above construction, we place $v_1$ above the edge $v_7v_5$, and $v_6$ below it. The rearrangement applied to grams $v_1v_7v_5$ and $v_6v_7v_5$ results in
