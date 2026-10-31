---
id: 1989-5-matizen-perekatyivanie-mnogogrannikov-5a34b6bb
issue: kvant_1989_5
year: 1989
number: "5"
title: Rolling polyhedra
authors:
  - Матизен В. Э.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 65
page_last: 67
page_labels: 63-65
tag: I5GK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7e3c73aa6b58f656817cbbe31ded9a71b3c5f3d8757f48be90b1ba4768b6b150
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/13_matizen-perekatyivanie-mnogogrannikov-5a34b6bb.md
source_content_sha256: c5d4e79a09d7d2a2ef54e314b4cf48743ef6a52cc02a9548ae909fae7721a32e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 63⟧

Rolling polyhedra

V. E. MATIZEN

Despite the strict warning (see screensaver), you've probably had to tip boxes, that is, roll them over the edges. This simple activity is not useful for a mathematician, since it leads to the next interesting problem. Let us place a convex polyhedron on its face (without paying attention to whether its state is stable). Let's roll the polyhedron through some of its edges so that it eventually returns to the original face. The result is a polyhedron surface at some angle. What is the magnitude of this angle?

Let's start with the simplest case, when the polyhedron rolls clockwise through all the edges emerging from some of its vertices O. figure 1 shows the trace of the polyhedron on the plane. From figure it is clear that the surface polyhedron is in the positive direction (i.e. counterclockwise) by an angle equal to the difference of 2π and the sum of the plane angles at the vertex. This difference has a special name - the curvature of the vertex (why is it called that?

Fig. 1.

63

⟦folio 64⟧

Fig. 2.

you can learn from the article by S. L. Tabachnikov “On curvature”, published in this issue of the journal). So, in the simplest case, the angle of rotation is equal to the curvature of the vertex. Probably, in the general case, the magnitude of the rotation is related to the curvature of the vertices of the polyhedron?

Let's move on to the general case. Let the polyhedron depicted at figure 2 roll over the edges $P_1, P_2, P_3, P_4, P_5$ (we are looking at the polyhedron from the outside). By connecting the midpoints of these edges, we get a closed contour - blue arrows on figure 2.

Control 1. Prove that the angle at which the polyhedron rotates depends only on the contour, but not on which arrow of the contour is considered first.

We will assume that the contour arrows show the angles between the edges whose midpoints they connect. These angles are considered positive if the arrow shows a rotation around the point of intersection of the edges (or their extensions) in a positive direction, i.e. counterclockwise, and negative if in a negative direction. The angle between edges $P_i$ and $P_j$ is denoted by $\hat{P}_i\hat{P}_j$. Then the angles $\hat{P}_2\hat{P}_3, \hat{P}_3\hat{P}_4, \hat{P}_4\hat{P}_5$ and $\hat{P}_5\hat{P}_1$ on figure 2 are positive, and the angle $\hat{P}_1\hat{P}_2$ is negative.

Let us formulate a preliminary statement:

The repeatability of the polyhedron when it is rolled over the edges $P_1, P_2, ..., P_k$ is equal to $-(\hat{P}_1\hat{P}_2 + \hat{P}_2\hat{P}_3 + ... + \hat{P}_{k-1}\hat{P}_k + \hat{P}_k\hat{P}_1)$.

(1)

To prove this, let's draw a trace of the polyhedron on the plane when rolling - figure 3. Please note that when imprinting on the plane, blue arrows placed the direction. Let's look at this figure. The angle of rotation of the polyhedron is equal to the angle between the lines $P_1$ and $P'_1$. The transition from $P_1$ to $P'_1$ is the result of an integer transformation

$$P_1 \rightarrow P_2 \rightarrow P_3 \rightarrow P_4 \rightarrow P_5 \rightarrow P'_1.$$

Each transformation in an integer is a rotation around the intersection point of adjacent edges $P_i$ and $P_{i+1}$ by an angle equal to $-\hat{P}_i\hat{P}_{i+1}$ (the minus sign is due to the fact that during printing the direction of rotation is reversed). So, the transition from $P_1$ to $P'_1$ is a composition of turns at angles $-\hat{P}_i\hat{P}_{i+1}$.

Let us take advantage of the fact that the composition of rotations by angles $\alpha_1, ..., \alpha_k$ is a rotation by the total angle $\alpha_1 + \alpha_2 + ... + \alpha_k$, if $\alpha_1 + ... + \alpha_k \neq 2\pi n$, or a parallel translation, if $\alpha_1 + ... + \alpha_k = 2\pi n$. If you are not familiar with this property of rotations, try to prove it or read the proof in the article by E. G. Gottman “Geometric Transformations” («Kvant», 1989, No. 2). According to this property, the angle between lines $P_1$ and $P'_1$ is equal to $-(\hat{P}_1\hat{P}_2 + \hat{P}_2\hat{P}_3 + ... + \hat{P}_k\hat{P}_1)$, which proves statement (1).

Let us now first try the sum of angles $\hat{P}_i\hat{P}_{i+1}$ with the curvatures of the vertices of the polyhedron. We cut the surface of the polyhedron into figure 2 along the blue contour, and in turn cut the inner region of the contour along the edges lying inside

⟦folio 65⟧

contour. Some of the resulting pieces are shown on figure 4. We outline each vertex of the polyhedron inside the contour on figure 2 in the negative direction with red arrows; these arrows are also shown on figure 4.

Let's look at one of the pieces. What is the total value of the syn and red angles? Let us denote by $m$ the number of edges, i.e., the number of straight segments on the boundary of this piece. Then the sum of the syn and red angles is equal to $\pi(2-m)$.

Exercise 2. Prove this statement. Hint: The sum of the angles of a $m$-gon is $\pi(m-2)$.

Therefore, the blue angle of each piece is equal to $\pi(2-m)$—a, where $a$ is the sum of the red angles of this piece. Summarizing over all pieces, we find that the sum of all synchronic angles is equal to $\pi(2-m)+\pi(2-m)+\dots-(a_1+a_2+\dots)$.

Here $m_1, m_2, \dots$ are the numbers of edges of the corresponding pieces, and $a_1, a_2, \dots$ are the sums of the red corners of these pieces. Note that the sum $a_1+a_2+\dots$ includes all the red corners at the vertices of the polyhedron inside the rotation contour once.

The sum of the red angles at one vertex is equal to its curvature minus 2π (did you remember that there are no red angles in the negative direction?). Therefore, the sum $a_1+a_2+\dots$ is equal to the sum of the curvatures of the vertices inside the contour without some multiple of 2π. This number does not affect the amount of rotation, so we discard it. So, $a_1+a_2+\dots$ is the sum of the curvatures of the vertices of the polyhedron lying inside the contour on figure 2.

Now we will deal with the terms $\pi(2-m)+\pi(2-m)+\dots$ in expression (2). Each edge counts twice in this sum, since after cutting the surface of the polyhedron, each edge occurs twice as a boundary of pieces on figure4.

Therefore, all these sums are a multiple of 2π and do not affect the magnitude of the rotation we are interested in. Consequently, formula (2) means that the sum of the synchronic angles is opposite to the sum of the curvatures of the vertices of the polyhedron inside the rotation contour.

It remains to recall statement (1) that the angle of the surface of the polyhedron that interests us is opposite to the sum of the synchronous angles. We came to the final conclusion:

please repeat it rolled along a closed contour is equal to the sum of the curvatures of its vertices lying inside the contour.

Exercise 3. Consider two adjacent vertices of the polyhedron depicted in figure 5. Prove that rolling through edges $P_1, P_2, P_3$, then through edges $P_1, P_4, P_5$, then through edges $P_3, P_2, P_1$, and finally through edges $P_5, P_4, P_1$ leads to a parallel re-extension of the polyhedron.

It is interesting to study the set of trace-perfect polyhedrons when it is rolled out of some possible initial position. This set has rich symmetry and can have a different structure - for some polyhedra it is discrete, but for others it is continuous. One can list all the polyhedra that, like a cube or a regular tetrahedron, “print” a pattern on a regular plane. But this is a topic for another conversation...
