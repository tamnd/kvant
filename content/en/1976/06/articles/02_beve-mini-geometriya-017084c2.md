---
id: 1976-6-beve-mini-geometriya-017084c2
issue: kvant_1976_6
year: 1976
number: "6"
title: Mini geometry
authors:
  - Беве Л.
rubric: osnovnye-stati
page_first: 7
page_last: 13
page_labels: 5, 6, 7, 8, 11
tag: Q1IY
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 91c0b7031992b6cab3d7e80cdb9603fe4cff050eed7630ff000a984c73c2b90d
prompt_sha256: draft-1
translated_from: content/ru/1976/06/articles/02_beve-mini-geometriya-017084c2.md
source_content_sha256: 0c537c2cc9ae9b2c8c0704670889bf767d6e9d2efc01068763bbbf81018fa1d0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## Mini geometry

There is a well-known parable about a smart centipede that forgot how to walk, thinking about the order in which it should rearrange its many legs. Eighty to ninety years ago, a similar story happened with mathematicians: they thought about how valid their conclusions were when proving theorems. After almost twenty years of excitement and intense work, those standards of mathematical rigor were developed, according to which any “self-respecting” theory is built today, and it finally became clear that mathematics would avoid the fate of the unfortunate centipede.

At the same time, the majestic and at the same time slender building of Euclidean geometry was saved from destruction and restored; Since then, 20 axioms described by David Hilbert in his “Foundations of Geometry” have become its eternal foundation. Euclidean geometry can be compared with the famous Cologne Cathedral (which was built, completed and rebuilt by many generations of builders, who forever settled next to the cathedral square and passed on their craft and workplace to their children).

*Finite geometries* are structured completely differently: the minimum of building material is a finite number of points, straight lines and planes, the minimum of rules for handling this material is three or four axioms governing the relationships between points, straight lines and planes.

It may seem that in this kingdom of “glass and aluminum” there are no secrets or mysteries. This is far from true, and here is an example: despite the efforts of three generations of mathematicians, it is still unknown whether there exists an *affine finite plane* (see § 1) of 100 points.

## § 1. Mini-Euclidean, or rather, finite affine plane

The elements from which the mini-plane is built are “points” and “straight lines”. (These are just names, which, as the reader will see, are far from the usual meaning of these words. D. Hilbert said that “points”, “lines” and “planes” could just as well be called “chairs”, “tables” and “circles”.) The point $A$ can lie on the line $a$; the same can be expressed differently: point $A$ belongs to line $a$, line $a$ passes through point $A$, line $a$ contains point $A$. About points and lines, any other statements that can be expressed through this basic relation are valid: the statement “lines $a$ and $b$ *intersect*” means that there is a unique point that lies on both the line $a$ and the line $B$; “lines $a$ and $b$ are *parallel*” if they do not intersect, etc.

We will call a finite collection of points and lines with the relation “lie on” or “belong to” a *finite affine plane* if the following three axioms are satisfied:

Axiom A1. *There is only one straight line through any two points on the plane.*

Axiom A2. *Through any point not lying on a line, there passes a unique line parallel to the given line.*

Axiom A3. *There are three points that do not lie on the same line.*

### Explanations for axioms A1-A3

1. The first axiom is transferred here from Euclidean geometry without changes, the second corresponds to the axiom of parallels in Euclidean geometry (the famous Fifth Postulate), the third axiom saves us from degenerate geometries, like the one depicted in Fig. 1, *a*).

2. In our mini-planimetry, the following statements are meaningless: “point $A$ belongs to segment $BC$”, segment $AB$ is congruent to segment $CD$”, “point $A$ lies inside angle $BCD$”, “angles $ABC$ and $DEF$ are congruent” and many, many other concepts and statements familiar to us.

3. All information about any line is contained in the list of points that lie on this line; Therefore, this view of things is quite acceptable (although not at all necessary): a plane is a finite set of points, lines are different sets of these points.

⟦figure⟧
Fig. 1. a) “Degenerate” geometry (Axiom A3 is violated!). b) A plane with four points and six lines. Lines $AC$ and $BD$ are parallel!

The minimal mini-plane that satisfies our three axioms contains four points and six lines; its conventional image is shown on Fig. 1, *b*. The convention of this figure and many other figure in our treatise is that on it ordinary points correspond to points of a finite plane, ordinary lines correspond to straight lines of a finite plane, and the usual relation of membership (“to lie on” or “belong”) corresponds to the relation of membership of a finite plane. But the configurations of a finite plane are not always embedded in an ordinary plane without any, sometimes funny, violations of its Euclidean structure. For example, on figure 1, *b* the diagonals of the “square” $ABCD$ are parallel to each other!

Problem 1. Prove that any finite affine plane contains at least four points and six lines. (This is why the plane at figure 1, *b*) is minimal.)

So, the foundation has been laid. We begin the construction of geometry on a finite affine plane with several obvious theorems; After reading the conditions of the next theorem, try to prove it yourself, and only then check yourself by looking at our proof (the beginning of the proof is marked with $\square$, and the end with $\blacksquare$).

Theorem A4. *If parallel lines have a common point, then they coincide.*

$\square$ By definition, parallel lines cannot have a single common point. Therefore, they have at least two common points and, according to axiom A1, they must coincide. $\blacksquare$

Theorem A5. *There are three straight lines intersecting in pairs at three different points.*

$\square$ Let three points $A$, $B$ and $C$ not lie on the same line (Axiom A3; Fig. 2); then three lines $a$, $b$ and $c$, passing through Axiom A1 through pairs of points $(B,C)$, $(A,C)$, and $(A,B)$, respectively, intersect in pairs: lines $a$ and $b$ - at point $C$, straight $a$ and $c$ - at point $B$, straight lines $b$ and $c$ - at point $A$. $\blacksquare$

⟦figure⟧
Fig. 2. Three lines $a$, $b$ and $c$ intersect at three points.

Theorem A6. *If line $a$ is parallel to line $b$, and line $b$ is parallel to line $c$, then $a$ and $c$ are parallel.*

$\square$ If any two of the lines $a$, $b$ and $c$ coincide, then the statement is obvious. If they are all pairwise distinct and the lines $a$ and $c$ intersect at a point, say $A$, then the line $b$ does not pass through the point $A$ (otherwise the lines $a$ and $b$ are not parallel). Then, according to Axiom A2, only one straight line parallel to straight line $b$ can pass through the point $A$, which leads to a contradiction. $\blacksquare$

The proofs of these three simple theorems serve, on the one hand, as a good example of how proofs are carried out in our geometry, and on the other hand, as the basis for more complex proofs of the theorems from § 2. Theorems A7 and A8 are not used further, and the reader is invited to prove them on their own.

Theorem A7. *Every line of any finite affine plane contains at least two distinct points.*

Theorem A8. *At any point of a finite affine plane at least three lines intersect.*

We compared Axioms A1-A3 with the foundation of finite affine geometry - Theorems A4-A8 form its “first floor”.

## § 2. Order of the affine plane

Of the 16 astronauts, you need to choose 4 - the crew of the spacecraft. Training is carried out with 4 crews of 4 people each. Is it possible to design a training schedule in such a way that any two cosmonauts will be in the same crew exactly once?

We can expect that all straight lines on our plane are indistinguishable from each other; at least this is the case in Euclidean geometry, where it is possible to superimpose one straight line on another. In finite affine geometry we do not have such a possibility. Therefore, we will try to make do with what we have at our disposal: draw lines, look for points of intersection of lines, etc.

Theorem A9. *Any two lines $e$ and $e'$ of a finite affine plane contain the same number of points.*

$\square$ Each of the lines $e$ and $e'$ intersects at least two of the lines $a$, $b$ and $c$ Theorem A5. Therefore, one of these three lines, say $a$, intersects both line $e$ and line $e'$. Let us now establish, using this line $a$, a one-to-one correspondence between the points of the lines $e$ and $e'$.

To do this, to each point $A$ on $e$ we associate the point $A'$ on $e'$, which is obtained from the intersection of $e$ with the line $a'$ (A2) passing through $A$ and parallel to $a$. In this case, different points on $e$ will correspond to different points on $e'$ (A2); It is also obvious that any point $B'$ on $e'$ will correspond to some point $B$ on $e$ (see Fig. 3, *a*). $\blacksquare$

Definition. *The order of a finite affine plane is the number of points on any line of this plane.*

*Order* is the most important numerical characteristic of the affine plane. As we will see, it is not difficult to construct a plane whose order is equal to any pre-specified prime number; It is more difficult (and we will not be able to devote space to this in our treatise) to construct a plane whose order is equal to the power of a prime number. It is known that there is no plane of order 6, and it is unknown whether there is a plane of order 10.

⟦figure⟧
Fig. 3. a) A pencil of parallel lines. b) There are as many lines passing through the point $A$ as there are points on the line $a$, plus one.

The theorem to which we now turn is, in a sense, an inverted image of A9: in it the points and planes have swapped places. Such theorems are called *dual* to each other.

Theorem A10. *The same number of straight lines pass through any point of the plane: for a plane of order $n$ this number is* $n+1$.

$\square$ Let $a$ be an arbitrary straight line; and let the point $A$ not belong to the line $a$ (AZ). Then there is a unique line passing through the point $A$ and parallel to the line $a$ (A2), and any other line passing through the point $A$ intersects with the line $a$ at a single point (A4), and different lines intersect (see Fig. 3, *b*) at different points (A1). It follows that the number of lines passing through the point $A$ is equal to the number of points on the line $a$, i.e., the order of affine geometry (see A9), increased by one. $\blacksquare$

Problem 2. Prove that the condition problem M364 («Kvant», 1976, No. 1, see also the epigraph) is equivalent to the statement: there exists a finite affine plane of order 4.

Theorem A11. *If the order of the plane is $n$, then any line of the plane belongs to a family (bundle) consisting of $n$ different pairwise parallel lines.*

$\square$ Let $e$ be an arbitrary line, then one of the three lines, say $a$, of Theorem A5 intersects the line $e$ at the point $E$. It is obvious that through any point on the line $a$, excluding the point $E$, there passes a single line parallel to the line $e$ (A2), and vice versa (Fig. 4), any line parallel to the line $e$ intersects the line $a$ at some point (see A6). We have established a one-to-one correspondence between the points of line $a$ and the lines of the bundle of parallel lines to which line $e$ belongs. $\blacksquare$

⟦figure⟧
Fig. 4. A bundle of lines parallel to $e$ is constructed from the points of line $a$.

⟦figure⟧
Fig. 5. Two pencils of parallel lines, intersecting, give all the points of the plane.

Theorem A12. *Any plane of order $n$ contains $n^2$ points and $n^2+n$ lines.*

$\square$ Any bundle of lines parallel to a given line will contain all points of the finite plane: otherwise, according to Axiom A2, this family could be supplemented with another line parallel to the given line and passing through a point not yet “covered” by the bundle. But in any such family there are $n$ lines (A11), and on each line there are $n$ points (A9), i.e., only $n^2$ points (Fig. 5).

Let us now count the number of lines on a finite plane of order $n$. Since through each point of the plane there are $n+1$ lines (A10), and since each family of pairwise parallel lines has its “representative” (A2) among these $n+1$ lines, then the total number of such families is $n+1$, and each family contains $n$ lines (A11), and each line falls into exactly one such family (A6). Therefore, the total number of lines in the plane is $n(n+1)=n^2+n$. $\blacksquare$

## § 3. On the benefits of military parades when they are observed by a great mathematician

Leonhard Euler came up with his famous puzzle about 36 officers, apparently while bored at one of the many St. Petersburg palace parades. Here is its formulation: among the 36 officers there are equal shares of lancers, dragoons, hussars, cuirassiers, cavalry guards and grenadiers, and, in addition, equal shares of generals, colonels, majors, captains, lieutenants, and second lieutenants, and the regiment of each of the “arms” is represented by officers of all six ranks. Is it possible to line up these officers in square $6\times6$ so that in any column and any rank there are officers of all regiments and all ranks? (The solution to this problem, when it is required to build a square of 25 officers according to the same rules, is depicted on the cover of the magazine.)

The astute reader has already associated Euler's puzzle with the problem of constructing a finite affine plane of order 6, in which the points are officers and the lines unite officers of either the same regiment or the same rank. The reader is, of course, right, but with one caveat: we will show that if for some $n$ ($n\gt2$) there exists a finite affine plane of order $n$, then there also exists the required arrangement of $n^2$ officers in a square $n\times n$ (for Euler $n=6$); however, the converse is, generally speaking, not true. For example, for $n=14$ there is no plane of order 14 (see Theorem 2 below), and Euler’s problem has a solution.

Task 3. Form 196 officers (14 officers of all 14 ranks from 14 regiments) in Euler's square $14\times14$.

According to Theorem A12, a plane of order $n$ contains $n^2$ points - they will be our officers. From the $n+1$ family of parallel lines (see A10 and A11) we choose four different families (for this the inequality $n+1\ge4$, i.e. $n\gt2$, must be satisfied). To distinguish between these families of lines, let’s assign one of them number one, the other number two, etc. We also number the lines in each of these four families in random order. All points belonging to the first line of the first family will be called hussars, the second line of this family - lancers, etc. - a total of $n$ names of regiments. We will call all points from the first line of the second family generals, the second line of this family colonels, etc. - a total of $n$ ranks.

Problem 4. Prove that among the hussars there are officers of all ranks; the same with lancers, dragoons, etc.

To build a square, we will consider the third family of parallel lines and form the first column of the square from the “officers” of the first line of the third family, the second column from the second line, etc., and the order of officers in each column will be determined by the lines of the fourth, last family: the first line of our square will contain the “participants” of the first line of the fourth family, the second line will be made up of officers from the second line, etc.

Task 5. Prove that the described method of constructing a square of arms leads to the goal.

## § 4. Red, black and blue

Euler's puzzle led us to one of the most interesting questions in the theory of finite geometries: *what are the finite affine planes*? For us, novice mini-geometers, it would be enough to find an answer to a narrower question: *for which $n$ there is a finite affine plane of order $n$*?

There is still no complete solution to this problem. Everything that is known is limited to two remarkable theorems.

Theorem 1. *If the number $n$ is prime or a power of a prime, then a plane of order $n$ exists.*

We will prove this theorem in § 5 for all primes $n$.

Theorem 2. *If the number $n$ when divided by $4$ gives a remainder $1$ or $2$ and if in the decomposition of this number into prime factors at least one prime number $p$ of the form $p=4k+3,$ occurs in an odd degree, then there is no finite affine plane of order $n$.*

The first number that satisfies the conditions of Theorem 2 is the number $n=6$: $6=4+2$ and $6=2\cdot3$. So, a plane of 36 points does not exist! (Euler’s remarkable intuition allowed him to choose the only “doubtful” case from a large number of close ones: $n^2=9$, 16, 25, 49, 64; when the plane, according to Theorem 1, safely exists).

As the reader already knows, this does not yet prove the unsolvability of Euler's puzzle (see, for example, Problem 3). However, it is truly unsolvable! This was proven in 1900 by a scrupulous search of all possible options for constructing a square.

Hard Theorem 2 was proved relatively recently (1949); it allows you to exclude infinitely many numbers from consideration, for example, the numbers 77 and 78. On figure 6 the first hundred natural numbers are shown, colored in three colors: blue are those numbers for which, according to Theorem 1, there is a plane of the appropriate order, red are numbers for which, according to Theorem 2, such a plane does not exist, and for black numbers, both the first and second possibilities are still open.

⟦figure⟧
Fig. 6. Table of “good”, “bad” and “not yet manifested” numbers.

The terra incognita of black numbers begins with the number 10 (although $10=2\cdot4+2$, but $10=2\cdot5$, and neither 2 nor 5 when divided by 4 gives a remainder of 3). Since the discovery of finite affine geometries (the beginning of the twentieth century), there have been many attempts to construct a plane of this order, including very recent ones - with the help of the most modern computers, but they all ended unsuccessfully: no one managed to construct more than six families of parallel lines to the plane being sought, although according to (A12) there should be exactly eleven such families!

## § 5. Coordinate method

Let $n$ be an integer greater than one. We will try to construct a finite affine plane of order $n$ by introducing coordinates on our set. In doing so, we imitate the great example of Rene Descartes, who systematically reduced precisely geometric problems on the Euclidean plane to corresponding algebraic problems.

So, let's arrange $n^2$ points in the form of a square $n\times n$ in the nodes of the squared paper, as was done on figure 7 for $n=5$. Let's renumber the vertical and horizontal rows of nodes with integers from $0$ to $n-1$ and assign to each point on the future final plane a pair of coordinates $(x,y)$, where $y$ is the number of the horizontal, and $x$ is the number of the vertical of the two rows at the intersection of which this point lies.

⟦figure⟧
Fig. 7. This is how coordinates on the affine plane are introduced (for example, the point $A$ has coordinates $(2,2)$). Conversely, from a set of $n^2$ points ($n=5$) given by coordinates, an affine plane can be constructed.

What are considered straight lines of a plane? Of course, any horizontal or vertical row of nodes. In addition, any set of (at least two) nodes lying on the same Euclidean line within the square $n\times n$. Let us only agree to “return” any such straight line as shown in figure 8.

⟦figure⟧
Fig. 8

Problem 6. Prove that after a certain number of such “jumps” we will again get to the original line and that the number of nodes through which we will “pass” does not exceed $n$.

We will consider the set of nodes that we have “traversed” along one “jumping” line to be a straight line.

This idea actually allows us to construct a plane of order $n$ when $n$ is a prime number. We will consider the arithmetic version of this definition of the plane, leaving the reader to carefully carry out the geometric construction we have outlined.

Problem 7. Show that if $n$ is an arbitrary natural number (not necessarily prime), then in this way we can determine $\phi(n)+1$ families of parallel lines, where $\phi(n)$ is the Euler function (!) ($\phi(n)$ is equal to the number of natural numbers less than $n$ and coprime to $n$).

So let $n=p$ be a prime number. Obviously, for any integer $m$ there is a unique number from the set of numbers $\mathrm F_p=\{0{,}~1{,}~2{,}~{\ldots}{,}~p-1\}$ equal to the remainder of division of $m$ by $p$; let's denote this number by $\{m\}_p$. Now for any two numbers $a$ and $b$ from the set $\mathrm F_p$, we define two operations: *$p$-addition and $p$-multiplication by putting*: $a\oplus_pb=\{a+b\}_p$, $a\otimes_pb=\{a\cdot b\}_p$, where $a+b$ and $a\cdot b$ are the usual sum and product of numbers $a$ and $b$. Obviously, for any two numbers $a$ and $b$ from the set $\mathrm F_p$, the *$p$-sum and $p$-product* again belong to $\mathrm F_p$. Equally obvious are the simple properties of these operations, formulated below in Theorems A1-A9 (perhaps, only Theorem A8 is more difficult than the others). The industrious reader should treat them as exercises.

Theorem A1. (*Property of zero.*) $a\oplus_p0=0\oplus_pa=a$ *for any* $a\in\mathrm F_p$.

Theorem A2. (*Property of unit.*) $a\otimes_p1=1\otimes_pa=a$ *for any* $a\in\mathrm F_p$.

Theorem A3. (*Associativity of addition.*) $(a\oplus_pb)\oplus_pc=a\oplus_p(b\oplus_pc)$ *for any* $a$, $b$, $c\in\mathrm F_p$.

Theorem A4. (*Multiplication associativity.*) $(a\otimes_pb)\otimes_pc=a\otimes_p(b\otimes_pc)$ *for any* $a$, $b$, $c\in\mathrm F_p$.

Theorem A5. (*Addition is commutative.*) *For any* $a$, $b\in\mathrm F_p$ $a\oplus_pb=b\oplus_pa$.

Theorem A6. (*Commutativity of multiplication.*) *For any* $a$, $b\in\mathrm F_p$ $a\otimes_pb=b\otimes_pa$.

Theorem A7. (*Invertibility of addition.*) *For any two elements $a$ and $b$ from $\mathrm F_p$ there is a unique element $c\in\mathrm F_p$ for which $a\oplus_pc=b$.*

Theorem A8. (*Invertibility of multiplication.*) *For any $a\in\mathrm F_p$ not equal to zero and any $b\in\mathrm F_p$ there is a unique element $c$ for which $a\otimes_pc=b$.*

Theorem A9. (*Distributive, or distributive law.*) *For any three elements* $a$, $b$, $c$ *of* $\mathrm F_p$
$$
a\otimes_p(b\oplus_pc)=(a\otimes_pb)\oplus_p(a\otimes_pc).
$$

Using the set $\mathrm F_p$ and the operations introduced on it, we now define a finite affine plane of order $p$. Points of this plane will be called pairs of numbers $(x,y)$, where $x$, $y\in\mathrm F_p$; There are $p^2$ such pairs in total. The line of this plane will be any set of such pairs whose coordinates satisfy either some equation of the form $x=s$, where $s$ is an element of the set $\mathrm F_p$, or an equation of the form $y=a\otimes_px\oplus_pb$, where both numbers $a$, $b$ belong to the set $\mathrm F_p$.

⟦figure⟧
Fig. 9. Tables of addition and multiplication of a finite field of four elements.

We provide the reader with a verification of the validity of Axioms A1–A3 with this definition of points and lines. (To prove a statement equivalent, for example, to (A1), it is necessary to show that any two points $A=(c,d)$ and $B=(e,j)$ can satisfy only one equation of either the form $x=s$ or the form $y=a\otimes_px\oplus_pb$; when checking, one should use the properties of the operations $\oplus_p$ and $\otimes_p$ formulated in Theorems A1-A9.) This will complete the proof of that part of the Theorem 1, which deals with prime values of order $n$ of the plane.

It is useful to understand that for our construction what was essential was not the arithmetic nature of the numbers from the set $\mathrm F_p$, or even the simplicity of the number $p$, but only those properties of the elements of the set that are described by Theorems A1-A9. We could consider an arbitrary finite set $\mathrm F_p$, as long as it defines: a) two operations, the first of which we will call addition, and the second multiplication, b) two special elements, the first of which we will call (and denote) zero, and the second one, and, finally, if only these operations and these two distinguished elements satisfy the requirements of Theorems A1-A9.

*The set $\mathrm F$ with such properties is called a finite field.*

Here is an example of a finite field with 4 elements: $\mathrm F_4=\{0,1,2,3\}$, the operations of which are defined according to tables figure 9. The corresponding finite affine plane of order 4 with a “red-green” coordinate grid is depicted on figure 10. At the same time, this figure serves as a solution to the already mentioned (epigraph to § 2) problem about 16 cosmonauts: each family of parallel lines is a division of 16 cosmonauts into 4 crews, each line of such a family is one crew.

⟦figure⟧
Fig. 10. Each family of parallels has its own color; for three families (blue, black, dotted), each figure shows one straight line.

We present without proof the main theorem about finite fields.

Theorem. *The number $q$ of elements of any finite field is the power of the prime number $q=p^m$. Conversely, for any $q=p^m$, where $p$ is a prime number and $m$ is an arbitrary natural number, there is a unique finite field $\mathrm F_q$, with $q$ elements*.

The validity of this theorem implies the existence of a finite affine plane of order $q=p^m$.

## § 6. Epilogue

Unlike a novel or a play, premature revelation of the plot is not a flaw in scientific research.

J. Galbraith

So, the question of the existence of finite affine planes of a given order has become somewhat clearer: there are forbidden values ​​(red numbers on Fig. 6), there are unexplored values ​​(black numbers there) and there are allowed values ​​- prime numbers and their powers (blue numbers), for which there is a way to construct a plane.

But is this the only way?! Are there any other planes for this order $q=p^m$?

Indeed, the Finite Field Theorem (§ 5) prohibits the existence of fields other than some standard fields $\mathrm F_q$ (they are called after Évariste Galois *Galois fields*); you have actually already encountered the simplest of these fields - fields $\mathrm F_p$ - on pages «Kvant» - in the article by A. Belsky and L. Sadovsky “Rings” («Kvant», 1974, No. 2 - see problems 2 and 3 on p. 7 of this issue), but does not prevent the existence of planes of the same order $q=p^m$, different from the standard ones. It was possible to show that all planes whose order does not exceed the number 8 can only be standard, and to construct a non-standard plane of order 9.

Saying goodbye to the reader, the author of the treatise warmly recommends that he read two wonderful books by E. Artin and M. Hall, where the subject of the treatise is covered in an equally interesting way, although from different angles.
