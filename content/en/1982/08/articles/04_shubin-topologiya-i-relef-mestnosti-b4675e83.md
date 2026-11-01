---
id: 1982-8-shubin-topologiya-i-relef-mestnosti-b4675e83
issue: kvant_1982_8
year: 1982
number: "8"
title: Topology and... terrain
authors:
  - Шубин М. А.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10-14
tag: GLV2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 786ab3093e4c8b9efdc7b57b620c63c413538fcfe711765c8d29f4ab2a63a9f2
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/04_shubin-topologiya-i-relef-mestnosti-b4675e83.md
source_content_sha256: 06f2b63beaafe503175853aa23ebc42b6f57bf4d68db3dad4fe033da226deca6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

M. Shubin

Topology and...
terrain

Topology—unlike topography—does not specifically deal with terrain maps. This science studies, as is commonly believed, the most profound properties of geometric figures. Such properties (they are called topological) can be the same in outwardly completely different people.

similar figures - M. Gardner once wrote that “topology is usually called the mathematician who cannot distinguish a coffee cup from a bagel.” Sometimes topological properties and quantities are obtained as combinations of very simple geometric properties and quantities. This is exactly how Euler’s theorem on polytopes* puts the matter into perspective. Now we will get acquainted with another example of the same kind - one theory from the “Morse theory**). The solution will appear there.

On geographic maps, the terrain is usually shown using a line level connecting points representing points on the earth's surface located on a given

*) See, for example, the chapter on topology in the book by P. Courant and G. Robbins “What is mathematics?” (M., “Prosveshcheniye”, 1967), as well as Theorem 2 below.

**) Harold Marston Morse (1892-1977) is a remarkable American mathematician who created a theory that was later called and represents one of the important sections of modern topology.

Fig. 1.
Fig. 2. Examples of surfaces.

⟦folio 11⟧

altitude above sea level (Fig. 1). A mathematical model of a limited area of ​​the earth's surface serves as a geometric surface in space, specified by an equation of the form $z=f(x,y)$. Several examples of the surface are shown in figure 2. On each surface, sets of points lying at a given height $z=const$ are drawn, and the level lines are the projections of these sets onto the plane $Oxy$. Thus, a level line is a set of points $(x,y)$ satisfying the equation $f(x,y)=const$, where the constant on the right side determines the distance between the level lines, so that the level lines are, as it were, numbered by such a constant. At figure 2 we placed the corresponding linear level families under each surface.

We will be primarily interested in the behavior of the solution near its characteristic points - peaks, basins and passes, as well as near its slope point.

Vertex. The characteristic behavior of the linear rebluff level near the top is shown in figure 3. It would seem that the top can be defined simply as the highest point of a certain area of ​​\u200b\u200bthe terrain surrounding it. However, the neighborhoods of such points may have cities with a more complex structure than in figure 3. For example, one can imagine that in no matter how small a neighborhood of such a point there are somehow other points that have the same properties, but are located below this one (Fig. 4). Wanting to exclude such a situation (and similar ones), we will call a point *vertex* if it is the highest point of some area of ​​terrain surrounding it and in its neighborhood the linear level is arranged as in figure 3, that is, they are closed curves without self-intersections, covering the distance of the point, and $z_0>z_1>z_2>...$.

The basin (Fig. 5) is the “vertex in reverse”, that is, the point

![Рис. 3.](image1.png)
[Рис. 5.](image2.png)
[Рис. 7.](image3.png)
[Рис. 6.](image4.png)

which will become a vertex if the sign of the distanced function changes. Thus, we call the basin the point at which the linear level is arranged as shown in figure 5, and $z_0<z_1<z_2<...$.

Pass. The pass can be described as a point near which a ridge is built like a saddle (Fig. 6). Near a pass, the linear level is located like this: at the pass point there are two such directions that, ideally, one of them is forward or

⟦folio 12⟧

back, we will go up, but I’m going the other way - to go down. Moreover: directions of the first type will fill two vertical angles, and directions of the second type will fill two other vertical angles, so that the straight lines dividing them, given by these two pairs of vertical angles, must touch the linear line passing through the saddle point. So, we will call a point a pass in the vicinity of which the linear level is arranged in accordance with the description just given.

Tilt point (Fig. 7). Burning figuratively, the point of inclination is such a point on the edge that if a ball is placed at it, it will appear, while a ball carefully placed at the point is a peak, basin or pass, it will appear (although in the case of a peak or pass its equilibrium will be unstable). Let us use the point of inclination to define the point of the edge that is located near the non-linear level, as in figure 7, and ... <z₂< <z₁< <z₁< <z₂< ...

More precisely, the linear family must be such that it can be obtained from the family of parallel lines by the so-called homeomorphism, that is, a one-to-one and mutually continuous transformation of a map section.

Note that on the map the slope point is usually large. For example, all peaks, basins and passes are isolated and surrounded by slope points.

Of course, in addition to peaks, basins, passes and inclination points, there are other types of points. For example, on a geographic map there are plateaus - entire areas whose point height is constant. A constant maximum height can be on an entire line, as, for example, on figure 2, in. There are also more “cunning” points, for example, “monkey saddles” (Fig. 2, 2) and points of clusters of vertices (Fig. 4). However, all points that are not slope points, except peaks, basins and passes, can be established in order to correct the terrain reflux; they disappear or are replaced by several peaks, basins, passes*). Therefore, in addition to the slope point, we will only consider these three types of points.

Now we can formulate our main theorem, which is one of the simplest Morse theorems.

Theorem 1. Let an island in the sea be given with such an edge that all points of the island are either points of inclination, or peaks, or basins, or passes, and all the coastal points of the island are points of inclination. Let B be the number of vertices of this edge, K the number of basins, P the number of passes. Then

B+K−Π=1.

Proof 1) Let's call the highest peak of our

*) This fact (in a more strict formulation) is one of Morse's theorems; we won't need it.

⟦folio 13⟧

the islands are Everest (if there are several such peaks at the same height, we call any of them Everest), and the deepest basin is called the Marshan Valley. Can change the topography of the island without changing the numbers B, K, Π and without violating the conditions of the theorem so that the following conditions are satisfied:

a) all peaks have the same height (equal to the height of Everest);
b) all basins are at sea level;
b) all passes are at different heights.

The easiest way is to satisfy conditions a) - for this it is enough to “build up” all the peaks to the level of Everest (Fig. 8).

Let's dig all the basins down to the depth of the Marshan Vladina - we will need this to subsequently ensure condition 6). It is not so easy to fulfill these conditions - if one tries to “fill up” the boiler

Fig. 8.

Fig. 9. Raising the saddle point: the blue part of the surface (which we consider rigid) moves slightly upward, and the pink part (which can be imagined as made of a thin rubber film) stretches slightly from the fixed outer boundary.

Now, you might stumble upon a pass. However, there is a simple way out: “dry up the sea.” Namely, we can assume that under water the shores of the island go down in a circle to a depth exceeding the depth of the Marshan Vladina. Then you just need to “dry” it evenly to this depth.

To ensure condition c) it is necessary to reduce the part, raise or lower the vicinity of a given pass, without specifying other peaks, basins and passes and without creating new peaks, basins and passes. This can be done, for example, by lifting the entire part of the relief, located inside a circle of small radius ε with the center at a given saddle point (Fig. 9, a), without touching the points lying outside the circle of radius 2ε (with the same center), and delivering the relief between the neighborhoods of radii ε and 2ε as shown in figure 9, b.

So, we will assume that the topography of our island satisfies conditions a) - c).

2) Now we will arrange a “global flood”. Let it gradually flood the island, raising the water level evenly everywhere (in the basins and in the sea) from sea level to the height of Everest. At the same time, deposits on the island in the basins form internal lakes, and it can later be formed into smaller islands. We will monitor how the number of lakes and islands changes as the flood progresses. We will not consider the sea a lake.

At the beginning of the flood, K lakes form on the bottoms of the basins. At the end of the flood, all the lakes merge with the sea, and only the tops of all the mountains remain above the water (that’s what they were built for!), so the number of lakes and islands is given by the following table:

| | Lakes | Islands |
| :--- | :--- | :--- |
| The beginning of the flood | K | 1 |
| Before complete flooding | 0 | B |

3) Let's see when the number of lakes and islands changes in the process

⟦folio 14⟧

flood It is clear that if water fills only the points of inclination, then these numbers do not change. Let's see what happens when water covers some pass (Fig. 10). There are two possibilities:

a) the waters of the same lake merge; then the number of lakes does not change, but a new island sunbathes (Fig. 11);

6) two different lakes merge (Fig. 12); then the number of lakes decreases by 1, but the number of islands does not change.

So, with each covering of water, the pass will either decrease by 1 number of lakes or increase by 1 number of islands. But in total the number of lakes decreases by K, and the number of islands increases by B-1, so K+(B-1)=Π, that is, B+K−Π=1, which is what needed to be proven.

Consequence. Let all the points of the globe be points of inclination, peaks, hatches, and passes. Then B+K−Π=2.

Proof. We will assume that the bottom of the deepest of the basins is filled with water (this can be achieved by draining all the seas and oceans and leaving water only at the bottom of the Marina Platinum). Then everything else can be considered an island, and the water at the bottom of this basin is the sea. But the whole Earth has the same number of peaks and passes as this island, and one more basin. It remains to use Theorem 1, and the corollary is proven.

An example of a solution to which this corollary applies is any polyhedron, inside which one can find a point O such that all perpediculars dropped from it on the faces end up on the faces themselves (and not on their extensions).

Then, if we call the height of the rebef at a given point of the polyhedron the distance from it to point O, then the bases of the perediculars dropped from O on the edge (and only they) will be basins, the vertices of the rebef will lie at the vertices of the polyhedron, and the passes will be at the bases of the perpediculars dropped from point O to the edges (check it!). It follows from this that for such polyhedra the following is true:

Theorem 2 (Euler's theorem on polyhedra). Let Γ, B and P be the numbers of faces, vertices and edges of a convex polyhedron. Then

$$\Gamma + B - P = 2.$$

As we will see below, this theorem is in fact true for any convex polyhedron - without the additional condition stated before it. It can be easily deduced from the following theorem.

Theorem 3 (Euler's map theorem). Let the bottom be a polytechnic map of the island, bounded by a closed curve, and the following conditions are met:

a) the number of countries is greater than or equal to 2;

b) each country is enclosed by a closed curve without self-intersections;

b) there are no countries lying one inside the other (such as Monaco, Batikana or San Marino).

Let C be the number of countries, B be the number of vertices (points where borders or
