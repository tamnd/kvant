---
id: 1984-3-vasilev-iz-pisem-chitateley-a5d322b5
issue: kvant_1984_3
year: 1984
number: "3"
title: From letters from readers
authors:
  - Васильев Н. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 49
page_last: 50
page_labels: 47-48
tag: OXBZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0fe0155753d66d3bc5e27c210dae6cf7d338ced9b69b3e698892e8b93ca7e77a
prompt_sha256: draft-1
translated_from: content/ru/1984/03/articles/14_vasilev-iz-pisem-chitateley-a5d322b5.md
source_content_sha256: b4ee1410d1f537a3866e83110e26628449806989eaae5f0574face05acea3f89
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

$$F \sim \varrho_1 \varrho_2 = \frac{\varrho_2}{\varrho_1} \varrho_1 \varrho_2 = \frac{\varrho_1}{\varrho_2} \varrho_2.$$

From the resulting relationship it is clear that to find the force of interaction between two halves with different charge densities, you can find the force of interaction between two identical halves with the same charge density $\varrho_1$ (or $\varrho_2$), and then multiply the found value by $k = \frac{\varrho_2}{\varrho_1}$ ($\ln \frac{1}{k} = \frac{\varrho_1}{\varrho_2}$).

So, let's find the force acting on a hemisphere with charge density $\varrho_1$ from a hemisphere with the same charge density. Divide the hemisphere into many layers so thin that they can be considered hemispheres. At each point of the hemisphere the direction of the electric field is equal to

$$E = \frac{4}{3} \pi r^3 \varrho_1 \frac{1}{4 \pi \varepsilon_0 r^2} = \frac{1}{3 \varepsilon_0} \varrho_1 r,$$

where $r$ is the radius of the hemisphere. The vertical projection of the force $\Delta f$ acting on an element of the surface of the hemisphere, the area of ​​which is equal to $ds$, is equal to (see figure)

$$df = E \varrho_1 \cdot ds \cdot dr \cdot \cos \alpha = \frac{\varrho_1^2 r}{3 \varepsilon_0} ds' \cdot dr,$$

where $dr$ is the thickness of the spherical layer, $ds'$ is the projection area of ​​the element $ds$ on the horizontal plane. It is obvious that the vertical projection of the force acting on the entire hemisphere is proportional to the area of ​​the projection of the hemisphere on the horizontal plane, that is

$$f = \frac{\varrho_1^2 r}{3 \varepsilon_0} \pi r^2 dr.$$

The horizontal projection of the force acting on the hemisphere is equal to zero.

Thus, the force of interaction between two halves with the same charge density is equal to

$$F = \int_0^R \frac{\varrho_1^2 r^3}{3 \varepsilon_0} dr = \frac{\varrho_1^2 R^4}{12 \varepsilon_0}.$$

And to find the force of interaction between two halves with charge densities $\varrho_1$ and $\varrho_2$, you need to multiply the resulting expression by $k = \frac{\varrho_2}{\varrho_1}$:

$$F' = \frac{\varrho_2}{\varrho_1} \frac{\varrho_1^2 R^4}{12 \varepsilon_0} = \frac{\pi R^4}{12 \varepsilon_0} \varrho_1 \varrho_2.$$

I. V. Grebnets

From readers' drawings

Regular readers of the «Kvant» model will notice a change in the traditions of the Quantum Assignor over the past year. Solutions to most problems are now published only three months after the condition. (The solutions to the remaining problems, as a rule, are included in small notes published as part of the “Problem Book”.) This reduction in the gap in the publication of the problem and their solution was positively assessed by many schoolchildren and teachers, but instead a solution to the problem M765 on triangulation, completely different from the author’s, was proposed by M. Kontsevich (Moscow). In this problem it was necessary to prove that for any finite set of points $B$ of the plane (not belonging to one straight line) it is possible to construct a system of triangles - a triangulation (with vertices at all points $B$ and only at them), which has the following property: the circumscribed circle of each of them triangles does not contain points $B$ inside itself, and for a set of points $B$ of general position (when no four of them they do not belong to the same circle) such triangulation is unique.

Let's project our plane onto a sphere touching it at point $T$ from the point $C$ diametrically opposite $T$. Let’s start with the “rubber band” set of points of the sphere $B'$ obtained from $B$ (and the point $C$) - take their convex hull. The result will be a convex polyhedron with triangular (in the general case) grams, and the plane of each face will intersect the sphere along the circumscribed vector face of the circle, and all the vertices of the polyhedron will lie on one side of the plane of the circle

⟦folio 48⟧

it does not allow the editors of the magazine to read, if necessary, decisions from all readers’ letters regarding the “Assignment”. The most interesting postcards from readers, additional already published solutions, prompted us to return to some problems. We hope to provide such an overview of one of the Assignment traditions. This issue is about mathematics.

(these are the conditions for the convexity of a polyhedron!). By projecting the edges of the polyhedron back onto the plane, we obtain the required triangular structure.

Here we use the following property of stereographic projection (that is, the projection of a sphere from its point onto a plane touching it at a diametrically opposite point): any circle on the sphere that does not pass through the line of the projection goes into a circle on the plane (see, for example, «Kvant», 1978, No. 12, p. 51). The reader with some knowledge of four-dimensional geometry can easily tell how the spatial version of problem M765 is solved in the same way.

* * *

The author of problem M748 A. Kuzminykh and some other readers drew attention to inaccuracies in the depiction of solutions to this problem. Here is a short solution that highlights the main idea more clearly. We are talking about the following statement (point 6) of the problem: if several cones in space do not intersect in pairs, then they cannot be translated so that they cover the entire space. (Here the cone is a body obtained by rotating an angle less than the unfolded angle around the Bisserritsa.) The idea of ​​the solution is to consider the set of all directions in space. We will associate each direction with a ray with a beginning at a fixed point O. Even better: let’s take a sphere (say, radius 1) with a center at point O - each of its points M corresponds to the definition of direction OM in space. Each cone K has a “cap” on the sphere - the intersection of the sphere with the cone K₀, obtained from K by parallel transfer of the vertex to point O; Moreover, for any point M inside K₀ better than the direction OM intersects the cone K along some ray, and for a point M outside K₀ - along more than a segment (perhaps it does not intersect K at all); to see this, it is useful to project the plane through the ray OM and the vertex of the cone K. If two cones do not intersect in space, then their corresponding caps on the direction sphere also cannot have common internal points: for such a point M, the ray OM would have to intersect with each of the two cones along a ray, that is, the cones would have to have a common ray. Thus, the caps for the data in the conditions of cones have a total area less than the area of ​​the sphere, so no matter how we dilute the cone, the caps will not be able to cover the sphere. But for any uncovered or point M the ray OM intersects each of the (translated) cones at most along a segment, so the cones do not cover the space.

* * *

Our reader from Bulgaria Ivan Topov (Sofia) received the final result related to the following question: for what natural numbers n>1 can 2n points dividing a circle into 2n equal arcs be connected in pairs by n chords of different lengths? In solving problem M789 («Kvant», 1983, No. 5, p. 46) from the messages of fourness it was deduced that for n=4m+2 and n=4m+3 this cannot be done, and the hypothesis was expressed that for other n it is possible; this was proved by I. Topov. Here is its construction. For n=4m, we number all 2n=8m points in order (say, clockwise) with numbers from 1 to 4m:

$$4m, 4m-2, 4m-4, ..., 4, 2; \quad 4m-1; \quad 2, 4, ..., 4m-2, 4m;$$

$$4m-3, 4m-5, ..., 2m+3;$$

$$2m-1, ..., 5, 3; \quad 2m+1; \quad 4m-1; \quad 3, 5, ..., 2m-1; \quad 1; \quad 1;$$

$$2m+3, ..., 4m-3; \quad 2m+1.$$

Then each number k≤4m will be assigned to two points, between which (along a shorter arc of a circle) there are exactly k-1 points. Similarly, for n=4m+1 numbering is suitable; 4m-2, 4m-4, ..., 6, 2; 4m; 2, 4, ..., 4m-2; 2m+1; 4m+1, 4m-1, ..., 2m+3; 2m-1, ..., 5, 3; 2m+1; 3, 5, 2m-1; 1, 1; 2m+3, ..., 4m-1, 4m+1. (See figure for m=3.)
