---
id: 1981-12-demkov-povorachivaem-kubiki-72d507f6
issue: kvant_1981_12
year: 1981
number: "12"
title: Rotating the cubes
authors:
  - Демков Ю.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11-16
tag: NRPA
lang: en
source: kvant_digital
extraction: vision
content_sha256: c5fd9d4387ccace479b71c810a0a57b08f6e228f96624d00c581be0b6c607b91
prompt_sha256: draft-1
translated_from: content/ru/1981/12/articles/06_demkov-povorachivaem-kubiki-72d507f6.md
source_content_sha256: f913ea4c2068a008e991fe1adb24a2a39a8b1a5ea421e063240b4b8e4362d028
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

Rotating the cubes

No, this article does not discuss the “Hungarian articulated cube” (see «Kvant», 1980, no. 12, p. 17) - a puzzle born in the hands of the Hungarian architect Ernő Rubik and which has attracted shareholders all over the world, especially in Hungary and the USA, where it is produced in millions of copies. «Kvant» will return to this difficult and interesting game soon, but here we will talk about a much simpler puzzle that anyone can master in a few minutes and for which you can build a few and complete mathematical theories.

Take 8 cups and form them into a cube twice the size*). Let's color three pairs of opposite faces of this cube, respectively, in white and yellow, red and orange, green and blue. Then each of the small cups will have three sides painted in different colors. Now let’s take the cube in our hands and rotate the layer of four cups adjacent to each other by 180° relative to the other four (clockwise or counterclockwise, it doesn’t matter - the result doesn’t depend on it). Obviously, this can be done in a third different ways. Let us use these three turns as elements of the operation or moves. Repeating these moves in different orders several times, we will get different distributions

colors along the faces of the cube. Let us identify each such distribution of colors of the state of the cube, and all distributions that differ in the rotation of the cube as a whole will be considered one and the same state. Let us define as zero the state in which each face of the cube is colored with the same color.

The following questions arise. How many different states are there that can be obtained from zero by some sequence of moves? What is the smallest number of moves that convert a given arbitrary state to zero? What is the minimum number of moves that convert a given arbitrary state to zero?

Status display and move recording

To answer these questions, we will first learn to describe the state of the cube and introduce a special notation for moves. First, let's fix the position of the cube in space, assuming that one of the small cups remains motionless during all transformations, for example, the one whose three outer faces are painted white, orange and green.

On figure 1, the image of a cube and 12 faces of small cups facing us is supplemented by an image of 9 rear faces, as if reflected in a round concave mirror. When the edges of the back small cube remain motionless, the figure cubes are painted in white, orange and green colors.

Let's denote the rotation of the front four cups 180° around the x-axis by X, the rotation of the four right cups by Y, and the rotation of the top four cups by Z (Fig. 2). During all these moves, the back small cube will remain motionless, so by performing moves X, Y, Z, we will never rotate the cube as a whole. The states that are obtained from zero using the operations X, Y, Z are depicted in Fig. 1, where they are numbered 2-4.

Composition of moves and matching

We will call the composition (sequential execution) of moves

⟦folio 12⟧

Fig. 1.

also by multiplication; We will write the product of moves from left to right. For example, $YZX$ is the sequential execution of moves $Y, Z, X$; $X^3 = XXX$ is the execution of three moves $X$. We will consider two products of moves to be equal if they have the same effect on each state of the cube.

Multiplying moves is, of course, not commutative; for example, all six “paired” products are not equal (numbers 5–10 on figure 1).

Let us denote $I$ the “identical” move that leaves the cube unchanged. Obviously,

$$X^2 = Y^2 = Z^2 = I.$$

It is easy to check that all “paired” products repeated three times do not change the state of the cube:

$$(XY)^3 = (YZ)^3 = (ZX)^3 = (YX)^3 = (ZY)^3 = (XZ)^3 = I.$$

Besides,

$$(XYZY)^2 = (XZYZ)^2 = (YXZX)^2 = (YZXZ)^2 = (ZXYX)^2 = (ZYXY)^2 = I$$

From the equalities (*), (**), (***) it is easy to obtain (without turning to the cube!) many new equalities. For example (check!), $XYX = YXY$ (see also problem 1 on p. 16).

So, we have obtained three groups of equalities, according to which all three moves $X, Y, Z$ are “square roots of units” (*), and all six paired moves are “cube roots of units” (**), and six more combinations of moves of a special type $(XYZY, YZXZ, ...)$ are also.

⟦folio 13⟧

Fig. 2.
are “square roots of units” (***).

State graph
We learned to depict the states of the cube (and assigned them numbers 1-24, Fig. 1), learned to write moves and found correspondences between moves. I would like to be able to more clearly depict the connection between states and moves. For this purpose, use the state graph shown in figure 3. On it, points (vertices) indicate states, and segments represent moves that allow you to move from one state to the “neighboring” one. Thus, in the center figure the thick dot represents the zero state; three segments emerge from it, corresponding to the moves X, Y, Z; from the point at the ends of these segments, three segments also emerge: one returns to the zero state, the rest lead to two new states, etc. Continuing this process indefinitely, we can consider the whole plane covered with a hexagonal grid - a state graph.

The relations (*) on the graph correspond to the movement back and forth along one of the segments, and the relations (**) correspond to the traversal of the hexagon (check it!).

The resulting picture has a very drawback - it has an infinite number of vertices (states), while our cube has only a finite number of states. This means that some (different) vertices correspond to the same state. To figure this out, list (for example, directly on figure 3) all the vertices of the graph numbered 1-14, use figure 1.

You will then see which vertices should coincide with each other. For example, the bold point in the upper part figure 3 also corresponds to the zero state (and in total there are 7 such points on figure). By the way, the path from the “central” zero point to the “upper” corresponds to the relations

$$XZYZXZYZ = 1,$$

that is, one of the ratios (***).

Fig. 3. State graph of the cube. The sides of the hexagons indicate the elements of the operation (they are placed with the letters X, Y, Z), the vertices of the hexagons indicate states, and the bold dots correspond to the zero state. Blue, red and green lines highlight fundamental areas.

⟦folio 14⟧

Having a numbered state graph in front of your eyes, it is easy to answer the questions posed at the beginning of the article. There are only 24 states (and 24 classes of equal sequences of moves). Of these, 3 states can be obtained from the zero state in one move, 6 in two moves, 9 in a third move, and 5 in four moves. In general, to find the minimum integer connecting these two states, it is enough to find two vertices on the graph with the corresponding numbers and connect them with the shortest broken line that indicates the required moves, and the number of these moves is always ≤4.

Fundamental Areas

In the last phrase, the careful reader should have noticed that it is not common to take not just any “two vertices with corresponding numbers”, but also those located “in the neighborhood”, otherwise an extra path like (***) may appear.

In this regard, it is convenient to “open” our graph into cells, inside of which there are no coinciding vertices and which contain all 24 states. figure 3 shows three ways to carry out such cutting: into red hexagons, into blue diamonds and into green “rectangles with broken sides”.

In mathematics, cells are also often called fundamental regions. Check that after the non-general relations of the boundary points of each of the specified cells, the real contains 24 different vertices - states.

Spatial state graph

Not being afraid of the latest “the best is the enemy of the good,” let’s try to get an even more accurate model of the states of our cube, starting from the fundamental areas. To do this, you have to go out into three-dimensional space.

Let us first select the fundamental area, depicted by green lines on figure 3 and straight horizontal broken lines. Then the fundamental region of transformation

Fig. 4.

turns into a rectangular structure, and the bundle of paths is presented in the form of a regular brick class of ten “bricks” and four “half-crickets” (Fig. 4). By bending the top and bottom sides of the rectangle, we get a tube. Next, twist this tube half a turn and, bending it, glue the ends together. We obtain the surface shown in figure 5, called a mountain. It is covered with a mesh of 12 hexagons with 24 vertices and 36 edges. If for each vertex we write down its number (which turns out to be numbered figure 3), then the resulting graph in theory gives a complete description of our geopuzzle. Indeed, each of the 24 vertices on the theory corresponds to one of the 24 states of our cube, and one can move from state to state in one move if and only if the corresponding vertices on the theory are connected by a (black) edge (see Fig. 5).

Geometric problem. Show that the ratio of the boundaries of other fundamental regions (see Fig. 3; red hexagons and blue diamonds) according to the above rules gives a torus with a right-handed graph on it. Compare this graph with the previous one.

Fig. 5.

⟦folio 15⟧

Conversion Groups

While we are carried away by the unexpected geometry that has arisen here, we should not lose sight of the algebraic nature of our investigations related to the important concept of a transformation group. A non-empty collection $G$ of transformations of a certain set*) is called a *transformation group* if

$$1^\circ \text{композиция любых двух преобразований из } G \text{ также является преобразованием из } G:$$

$$f, g \in G \Rightarrow f^\circ g \in G;$$

$$2^\circ \text{преобразование, обратное к любому преобразованию из } G, \text{ также содержится в } G:$$

$$f \in G \Rightarrow f^{-1} \in G.$$

From the properties of $1^\circ$ and $2^\circ$ it immediately follows that the identical transformation $1$ is always contained in $G$ (since $f^{-1} \circ f = 1$).

It is easy to see that for our game the set of all transformations (that is, sequences of moves) of the cube is the transformation group of the set of all its states. Indeed, the property $1^\circ$ is very visible, while the property $2^\circ$ follows from the fact that any move is inverse to itself (see (*)), and the transformation inverse to any sequence of moves is the same sequence, only written out in reverse order (check it!).

As other examples of transformation groups, we name the family of all displacements of the plane and the set of all one-to-one transformations of a finite set (of $n$ elements) onto itself. The last group is called the *substitution group* (of $n$ elements) and is denoted $S_n$. (Check properties $1^\circ$ and $2^\circ$ for it and show that $S_n$ has $n! = 1 \cdot 2 \cdot \dots \cdot n$ elements.)

From an algebraic point of view, it does not exist what the nature of the elements being transformed is, but what is important is the algebraic structure of the transformations themselves, that is, how the multiplication operation $\circ$ (composition) in the aggregate $G$ is structured. Algebraic consider two transformation groups $G$ and $H$ the same if they are isomorphic; this means that there is a one-to-one mapping $\alpha : G \rightarrow H$ of the group $G$ and $H$ that preserves the composition operation, that is, satisfies the property

$$g, g' \in G \Rightarrow \alpha(g \circ g') = \alpha(g) \circ \alpha(g').$$

For example, the set of all displacements of a plane that takes some fixed equilateral triangle into itself is a group (why?) and this group is isomorphic to the permutation group of the set of three elements $S_3$ (check!).

More details about transformation groups and the important concept of an (abstract) *group can be read in the book by P. S. Aleksandrov “Introduction to Group Theory” (Library «Kvant», issue 7, M., 1980).

Algebraic model of the game

We will show that the *transformation group* of the named cube is isomorphic to the *group $S_4$ of permutations of four elements*. To do this, number the vertices of the cube (or, what is the same, small cubes) with numbers from 1 to 8, as shown in figure 2. It is easy to see that the vertices $1-4$ and $5-8$ are the vertices of tetrahedra inscribed in the cube, and with all our transformations the vertices $1-4$ and $5-7$ transform into each other (and the vertex $8$ remains in place). Thus, our transformations carry out a permutation of the vertices $1-4$ and twenty-fourREM transformations of the cube are one-to-one mapped to the $4! = 24$ permutations of fourREM to fourREM.

Three moves $X, Y, Z$ correspond to permutations of two vertices: move $X$ - vertices $1, 2$, move $Y$ - $1, 3$ and move $Z$ - $1, 4$. Thus, we connected our original problem with a rather simple problem of representing all elements of the group of arrangements fourREM fourREM in the form of a product of three basic paired arrangements of one selected element with the trays of the rest and showed that

⟦folio 16⟧

All other elements of the group can be constructed as products of no more than four basic elements.

Along with the geometric one, we received an algebraic model of our game.

Algebraic problems. 1. Show that the transformed group of our cube is uniquely described by the basic correspondences (*); (**), (***). This means that any correct relationship between moves X, Y, Z can be obtained from basic insertions and cuts. (Insertion is an operation on relations in which one of the left parts of the main relations is inserted directly into any place of the already obtained relation

$$XYXY = I \Rightarrow XY(ZZ)XY = I,$$

and reduction is the inverse operation of insertion, for example:

$$ZXY(ZZ)YXZ = I \Rightarrow ZXYYXZ = I).$$

2. Show that the relation (*), (**) uniquely describes the group of those plane movements that combine the hexagonal mesh with itself. (Indication: The move X corresponds to the symmetry of the plane relative to the perpendicular bisector of the segment X - see Fig. 3).

Is it just a game?

Let us note in conclusion that in nature there are objects that have properties similar to the properties of our cube. These are the so-called molecules with internal physics.

The simplest such molecule is the ethane molecule CH₃—CH₃, in which one methyl radical can rotate relative to the other (Fig. 6). The symmetry properties of such molecules, described by transformation groups that leave the molecules unchanged, are currently being intensively studied. And although a molecule is not yet known that has exactly the same internal symmetry as the distance cube, it is not excluded that it can be found. There is a "cube" molecule consisting of eight carbon atoms and eight hydrogen atoms (Fig. 7), similar to the model discussed here; but, apparently, free alignment of one face relative to a parallel face does not occur.

Note also that the double periodic structure that is visible in figure 3 occurs in the resulting crystals. In this case, the small hexagonal cells correspond to the elementary cells of the crystal, consisting of atoms, while the larger cells are associated with the more subtle properties of the crystal - the orientation of the spins of the atoms, the placement of various isotopes, etc.

From this it is clear that the studied symmetry groups of this type can also turn out to be interesting from a physical point of view.

Amendment

In the program on p. 56 «Kvant», 1981, No. 9 includes several statements, of which it indicates the absence of a 1 mark before the fifth statement and the omission of continuation characters in the DATA statement entry. Us. 55 together CALL STR should be read CALL STR.
