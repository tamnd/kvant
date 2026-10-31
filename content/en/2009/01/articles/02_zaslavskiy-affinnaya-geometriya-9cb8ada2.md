---
id: 2009-1-zaslavskiy-affinnaya-geometriya-9cb8ada2
issue: kvant_2009_1
year: 2009
number: "1"
title: Affine geometry
authors:
  - Заславский А. А.
rubric: osnovnye-stati
page_first: 10
page_last: 13
page_labels: 8, 11
tag: L126
lang: en
source: kvant_digital
extraction: native
content_sha256: da35a9c974f7f260f1af434266da6fc49e6655f4bac98bb33d30e949dc61ea97
prompt_sha256: draft-1
translated_from: content/ru/2009/01/articles/02_zaslavskiy-affinnaya-geometriya-9cb8ada2.md
source_content_sha256: 215ff509d4e657b7c28892251191cf8038b622094bb3e950120aea81010b7dbc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

KVANT 2009/№1

Affine geometry

A. ZASLAVSKY

ALTHOUGH ALL SCHOOLCHILDREN TAKE GEOMETRY, few can clearly formulate what exactly they are learning. When I asked schoolchildren this question, I usually received an answer like: “Geometry studies the geometric properties of shapes.” At the same time, to the next question: “What exactly are the properties of figures that are geometric?” – it was no longer possible to get an answer. In fact, the object of study of traditional school geometry is those properties of figures that do not change during similarity transformations. For example, two regular triangles, one of which is drawn with chalk on a blackboard, and the other with a pencil in a notebook, are the same from the point of view of geometry. However, it is often of interest to go deeper

⟦column⟧

parallel), as a result of which an image of this drawing appears on the wall. If the planes of the glass and the wall are parallel, the image exactly repeats the drawing, but otherwise it may be subject to significant distortion. For example, equal segments can become unequal, angle values ​​are not preserved, etc. However, it is easy to see that the following properties of the drawing are preserved in the image. 1. Any straight line in the drawing corresponds to a straight line in the image, and parallel lines correspond to parallel lines. 2. The ratios of the lengths of parallel segments are preserved. 3. The ratio of the area of ​​any figure to the area of ​​its image is constant for all figures. Let us note one more important property of parallel projection. Statement 1. Any triangle can be converted into a regular triangle by parallel projection. Proof. Let triangle ABC lie in the plane $\pi$. Take the plane $\pi ¢$ intersecting $\pi$ along the line AB, and a regular triangle ABC¢ located in it. It is obvious that the projection $\pi$ onto $\pi ¢$ parallel to the line CC¢ is the required one.

Exercise. Prove that any triangle can be transformed into any other composition (sequential application) of several parallel projections. Note. Show that the composition of two projections can transform one regular triangle into another.

properties that are preserved not only under similarities, but also under other transformations. First of all, this applies to the so-called affine transformations, which we have to deal with even in the regular school curriculum. For example, when making a drawing of a cube, we do not try, and would not be able to depict all its faces as squares, but we draw them in the form of parallelograms, i.e. The essential property for us is not the equality or perpendicularity of the edges of the cube, but their parallelism.

Parallel projection and its properties

Suppose that some drawing made on glass is illuminated by the sun (the sun's rays are considered

01_24.p65

From Statement 1 it follows that any property of a triangle that relates only to the ratio of the lengths of parallel segments or areas is sufficient to prove for a triangle of a special type, for example, regular. A similar statement is true for parallelograms, since one can cut each parallelogram diagonally into two equal triangles and project “half” of one parallelogram into “half” of the other. In particular, the theorem that the medians of a triangle intersect at one point and divide each other in the ratio 2: 1 becomes completely obvious - since it only talks about the relations of segments lying on the same straight line, and these relations do not change during parallel projection, it is enough to prove it for a regular triangle. Let's consider several problems. Problem 1. Prove that the point of intersection of the diagonals of a trapezoid, the point of intersection of its sides and the middle of the bases lie on the same straight line. Solution. Let the lateral sides of the trapezoid AB and CD

⟦folio 11⟧

AFFINE

The orthogonal projection used in drawing can be considered compression relative to a straight line. If two non-perpendicular planes $\pi$ and $\pi ¢$ intersect along a straight line l, then the ratio of the distances to l from any point X of the plane $\pi$ and its projection X¢ onto $\pi ¢$ is constant. In addition, the projections of X and X¢ onto l obviously coincide. Therefore, if we consider $\pi$ and $\pi ¢$ to be two copies of the same plane, then the orthogonal projection will be a compression relative to l with a coefficient equal to the cosine of the angle between the planes. It turns out, however, that any affine transformation is a contraction with respect to a line in a certain sense. More precisely, the following theorem is true. Theorem 2. Any affine transformation can be represented as a composition of compression with respect to a line and similarity. Proof. Let us take an arbitrary square lattice on the plane. This affine transformation transforms it into a lattice of parallelograms. If these parallelograms are rectangles, the theorem is obvious. Otherwise, consider some square of the lattice OACB. Let the angle A ¢ O ¢ B ¢ be acute in the corresponding parallelogram O ¢ A ¢ C ¢ B ¢. We will rotate the square lattice around point O. The parallelogram O ¢ A ¢ C ¢ B ¢ will rotate around O¢, changing its shape. When the square lattice rotates through a right angle, the point A¢ will go to B¢, and B¢ to the vertex of the parallelogram adjacent to O ¢ A ¢ C ¢ B ¢, and the angle A ¢ O ¢ B ¢ will become obtuse (Fig.6). Therefore there is

⟦figure⟧

Fig. 6

intermediate value of the rotation angle at which this angle is right. The square lattice corresponding to this angle transforms into a rectangular one, which proves the theorem. Note that compression relative to a straight line is easy to implement using the parallel projection discussed at the beginning of the article. Indeed, if the direction of projection is perpendicular to the line of intersection of the glass and wall planes, the result of projection will be compression relative to this line. By changing the angle between the planes and the direction of projection, it is possible to ensure that the compression ratio takes on any given value. Thus, parallel projection can be considered a universal example of an affine transformation. The following problem is easily solved by applying Theorem 2.

01_24.p65

GEOMETRY

⟦column⟧

Problem 8. Prove that the affine transformation transforming a given circle into a circle is a similarity. Solution. Let us describe a square around a given circle and rotate it so that this transformation transforms it into a rectangle. The circle, which is the image of the given one, will be inscribed in this rectangle. But a circle cannot be inscribed in a rectangle other than a square. Therefore, this transformation transforms a square lattice into a square one and, therefore, is a similarity. Let us give two more interesting examples of affine transformations. Let's choose a coordinate system on the plane and consider a transformation that takes a point with coordinates ( x, y ) to a point ( x ¢, y ¢ ), where x ¢ = kx, y ¢ = y k, k > 0. This transformation is affine, since it can be represented as a composition of two compressions to the coordinate axes. In addition, it is obvious that xy = x ¢ y ¢. This means that any hyperbola with the equation xy = c goes into itself, and by choosing the value of the parameter k, you can transfer any point of the hyperbola to any other point (Fig.7). Thus, under the influence of this transformation, each such hyperbola seems to slide on its own, just as they slide on their own under the action of rotation around the origin of coordinates $окруж-^{Рис.} 7$ with equations $x^{2} + y^{2} = R^{2}$. Therefore, such a transformation is called a hyperbolic rotation. Problem 9. The tangent to a hyperbola intersects the coordinate axes at points X, Y. Prove that the area of ​​triangle OXY does not depend on the point of tangency. Note. Prove that hyperbolic rotation preserves area. Problem 10. A straight line intersects a hyperbola at points A, B, and the coordinate axes at points X and Y. Prove that AX = BY. Solution. Using a hyperbolic rotation, we transform points A, B to points A¢, B¢, symmetrical with respect to the bisector of the angle XOY. Then, using symmetry with respect to the bisector, we swap points A¢, B¢ and by an inverse hyperbolic rotation we transfer them to points B, A. As a result, the segments AX and BY will transform into each other, and their relationship will be preserved, which is only possible if AX = BY. Having considered the degenerate case of this problem, when the line touches the hyperbola, we find that the point of tangency divides the segment XY in half. Let us now consider a transformation that takes the point ( x, y ) to the point ( x ¢, y ¢ ), where x ¢ = x + v 2, y ¢ = vx +

$+ y + v^{2} 4$. It is immediately verified that this transformation transforms lines into lines, and y ¢ $- x ¢^{2} = y - x^{2}$. Therefore, this transformation preserves parabolas with equations $y = x^{2} + c$.
