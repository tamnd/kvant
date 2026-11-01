---
id: 1981-4-yaglom-soedinim-dve-tochki-otrezkom-6b6c2052
issue: kvant_1981_4
year: 1981
number: "4"
title: Connect two points with a segment
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 14
page_last: 18
page_labels: 12-16
tag: DRDQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: b3e3afea2870993c19cf4f98c9252cfec7d59ac585566334be32b653f6fc6cb3
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/05_yaglom-soedinim-dve-tochki-otrezkom-6b6c2052.md
source_content_sha256: 397e9f2eb69caa7497931f608763f309c556c7c13e885bb864b619b8fb36dc42
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

I. Yaelom

Connect two points with a segment

The ancient Greeks understood mathematics primarily as geometry. For example, they proved the algebraic equality $(a+b)^2=a^2+2ab+b^2$ using the drawing (Fig. 1). Today, mathematics, for example, is rapidly becoming algebraic—algebra, in its relationship with geometry, is taking revenge. In recent years, the presentation of geometry is most often based on one or another calculus (for example, vector calculus). One of these calculations, very simple but unexpected, will be discussed in the article.

Multiplying points and shapes

A segment with endpoints $A$ and $B$ is often denoted by the symbol $AB$ (Fig. 2). This entry suggests unexpected terminology: we call the segment $AB$ the product of the points $A$ and $B$. Similarly, by the product αβ of figures α and β we mean the circled sum of all segments $AB$, where $A \in \alpha$, $B \in \beta$, that is, the circled circle of all possible products of points of figure α by points of figure β (Fig. 3). We are sure that there is no way this unexpected product of points and figures with the usual product of numbers.

What are the properties of such a multiplication of points? The first ones are obvious:

(a) Multiplication of points commutingly:

$$AB=BA$$

(b) Multiplying points associatively:

$$(AB)C=A(BC)$$

for any points $A, B$ and $C$.

Indeed, the product $(AB)C$ is the union of all segments connecting the points of the segment $AB$ with the point $C$ (Fig. 4,a), and the product $A(BC)$ is the union of segments connecting $A$ with the points of the segment $BC$ (Fig. 4,b). Thus, $(AB)C=A(BC)=ABC$, where $ABC$ is a triangle with vertices $A, B, C$.

Here it will be convenient for us to call the union of figures α and β their sum; accordingly, together α and β we will write α+β.

(c) Multiplication of points is distributive with respect to their addition:

$$(A+B)C=AC+BC$$

for any points $A, B$ and $C$.

This is clear, since the product of the pair of points $A+B$ and the point $C$ is the union of the segments $AC$ and $BC$ (Fig. 5).

The following property of multiplying points already differs from the properties of multiplying numbers that have been taught to us:

(d) Dot multiplication is identical:

$$AA=A$$

for any point $A$.

Indeed, the segment $AA$ with merged ends is just the point $A$.

Properties (a) - (c) of point multiplication carry over to arbitrary figures:

(A) Multiplication of figures commutatively:

$$\alpha\beta=\beta\alpha.$$

(B) Multiplying figures associatively:

$$(\alpha\beta)\gamma=\alpha(\beta\gamma).$$

The figure $(\alpha\beta)\gamma=\alpha(\beta\gamma)$ is appropriately denoted by αβγ; it represents the union of all possible triangles $ABC$, where $A\in \alpha$, $B\in \beta$, $C\in \gamma$.

⟦folio 13⟧

Fig. 1.
Fig. 2.
Fig. 3.
Fig. 4.
Fig. 5.
Fig. 6.
(C) Multiplication of figures is distributive with respect to their addition:
$(\alpha + \beta)\gamma = \alpha\gamma + \beta\gamma$
(Fig. 6).
However, the idempotency of multiplication of figures, generally speaking, has no place. One can only say that
(D) The product of any figure with itself contains this figure:
$\alpha\alpha \supset \alpha$.
Figure 7 shows that the figure $\alpha\alpha$ may not be the same as $\alpha$. Moreover, it is easy to see that for any figure $\alpha$
$\alpha^n \subset \alpha^{n+1}$, where $\alpha^n$, as usual, means the product $\underbrace{\alpha\alpha \dots \alpha}_{n\text{ раз}}$.
Exercises
1. Let $A, B, C$ and $D$ be arbitrary points (planes or spaces). Prove that
$(AB)(CD) = (AD)(BC) =$
$= (AC)(BD) = A(BCD) = B(ACD) =$
$= C(ABD) = D(ABC)$.
What is this product of four points (it can be denoted simply by $ABCD$ without parentheses)?
2. Prove that $(AB)(AC) = ABC$.
3. What do the figures $a)(A+B)(A+C); 6)(A+B)(C+D);$ represent?
$b)(A+B+C)D; 7)(A+B+C)(D+E)$?
(In problems 6) - d) separately consider the case when all points belong to the same plane and when these are arbitrary points in space.)
4. What is the product of a) a point and a circle; 6) points and circles;$
$b) points and triangles; 7) points and outline of the triangle; 8) dots and squares; e) two circles; g) two triangles; h) two squares; i) circle and square?
5. What is the product of two lines if these lines are a) parallel; 6) intersect; c) interbreed?

When $\alpha\alpha = \alpha$
In arguments and in algebra, a special role is played by those numbers for which $a \cdot a = a$. It is clear that only the numbers 1 and 0, which are remarkable in many other respects, have this property.

⟦folio 14⟧

In geometry it is also interesting to specifically consider such figures $\alpha$ for which $\alpha^2 = \alpha \alpha = \alpha$. Each such figure is characterized by the fact that it belongs to any segment connecting two points of this figure (Fig. 8). Such figures, as you know, are called *convex*.

The definition of a convex figure can also be given the following elegant form: a set of points $\alpha$ is called *convex* if it is closed under the operation of multiplication of points, that is, along with any two points $A$ and $B$, the figure $\alpha$ also contains the product $AB$ of these points.

It is easy to come up with a flat figure $\beta$ for which $\beta^2$ is not convex. It can be proven that for any flat figure $\beta$ the figure $\beta^3$ is convex; it is represented by the smallest convex figure containing $\beta$ and is called the *convex hull* of $\beta$. For a figure $\beta$ located in three-dimensional space, the convex hull will be $\beta^4$.

In general, for any figure $\beta$ located in $n$-dimensional eclidean space, the figure $\beta^{n+1}$ is convex, and therefore all figures $\beta^{n+2}, \beta^{n+3}, \dots$ coincide with $\beta^{n+1}$.

The theory of convex figures occupies a prominent place in mathematics today.

Exercises

6. Prove that the product of two convex figures is convex.

7. What do the figures $\beta^2; \beta^3; \beta^n$ represent if $\beta$ is the union of: a) three points of the plane; b) four points in space; c) vertices of a regular pentagon; d) a circle and a point that does not lie in the plane of the circle and is orthogonally projected into its center.

Where there is multiplication, there is division

In the field of numbers, division is defined as the inverse operation of multiplication: the number $q$ is called the quotient of the numbers $a$ and $b$ (notation: $q=a/b$) if $a$

⟦folio 15⟧

There is a product of $b$ and $q$. In other words, the entries $q=a/b$ and $a=bq$ have the same meaning. Similarly, we carry out the operation of dividing points as the inverse for their multiplication: if $A \neq B$, then by $A/B$ we denote the set of points $Q$ for which $A \in BQ$; Let us also put, by definition, $A/A=A$.

By virtue of the definition of point multiplication, the condition $A \in BQ$ means that $A$ belongs to the segment $BQ$ (Fig. 9); thus, point $Q \in A/B$ lies on the passing line $A$ and $B$ and is located on the other side of $A$ than point $B$. So, the quotient $A/B$ of two points is a ray with origin $A$, the continuation of which passes through the line $B$. We can also say that $A/B$ is the shadow cast by the “ring” $A$, illuminated by the “lantern” $B$ (Fig. 10).

We define the quotient $\alpha/\beta$ of two figures $a$ and $b$ as both names of all rays $A/B$, where $A \in \alpha, B \in \beta$, that is, the union of all possible partial points of the figure $a$ into points of the figure $b$ (Fig. 11). For example, if $A$ is a point, then $\alpha/A$ is the shadow cast by the figure $a$, illuminated by the “lantern” $A$ (Fig. 12).

As is easy to see (see Fig. 13-17), for each three points $A, B$ and $C$ the following relation is valid (the first two of them are based on the properties of numbers):

$$(A/B)/C = A/(BC),$$
$$(A+B)/C = (A/C) + (B/C),$$
$$A/(B+C) = (A/B) + (A/C),$$
$$(AB)/C = (A/C)(B/C)$$
$$A/(BC) = (A/B)(A/C).$$

It is clear that for any figure $a$ the inclusion $\alpha/\alpha \supset \alpha$ is valid. Of general interest are figures $\lambda$ for which $\lambda/\lambda = \lambda$. We will call such figures linear (see Fig. 18).

Battles

8. What do the figures $A)$ $(ABC)/D; 6)$ $(AB)/(CD); 8)$ $A/(BCD)?$ represent?

9. What do the figures $\alpha/\alpha; (\alpha/\alpha)/\alpha; [(\alpha/\alpha)/\alpha]/\alpha; ...$ represent?

if $\alpha$ is the union of three points that do not lie on the same line?

10. Write down, using the operations of multiplication and division of points, the regions on which the points $A$ and $B$ divide the line;

6) three straight lines connecting points $A, B$ and $C$ in pairs divide the plane;

c) four planes connecting three given points $A, B, C$ and $D$ divide the space.

In ex. 11-13 the following notations are adopted: $A$ - dot; $\lambda, \lambda_1, \lambda_2$ - straight; $\pi, \pi_1, \pi_2$ - planes; $\sigma, \sigma_1, \sigma_2$ - circles; $x, x_1, x_2$ - circles; $\tau, \tau_1, \tau_2$ - triangles.

11. What do the figures $a)$ $(A/\lambda; 6)$ $\lambda/A; b)$ $A/\pi; \Gamma)$ $A/\sigma; e)$ $\sigma/A; jx)$ $A/x; 3)$ $x/A; i)$ $A/\tau; k)$ $\tau/A; l)$ $\lambda/\pi; m)$ $\pi/\lambda$ represent?

12. What do the figures $a)$ $\sigma_1/\sigma_2; 6)$ $x_1/x_2; b)$ $\tau_1/\tau_2; \Gamma)$ $\lambda_1/\lambda_2; d)$ $\pi_1/\pi_2$ represent?

In ex. d) separately consider the case when $\lambda_1$ and $\lambda_2$ intersect; parallel; interbreed.

13. What do the figures $a)$ $\sigma/\sigma; 6)$ $x/x; b)$ $\tau/\tau; \Gamma)$ $\lambda/\lambda; d)$ $\pi/\pi$ represent?

14. Prove that for any points $A, B, C$ the following relation holds:

a) $A(B/C) \subset (AB)/C; 6)$ $A/(B/C) \subset (AC)/B; b) (A/B)(C/D) \subset (AC)/(BD); g) (A/B)/(C/D) \subset (AD)/(BC).$

(Similar properties of fair ones for arbitrary figures.)

15. Prove that for any figures $a, b, \gamma$ $(\alpha/\beta)/\gamma \subset (\alpha/\gamma)\cap(\beta/\gamma); 6)$ $(\alpha+\beta)/\gamma = (\alpha/\gamma)+(\beta/\gamma); b) \alpha/(β+\gamma) = (\alpha/\beta)+(\alpha/\gamma); g) (\alpha/\beta)/\gamma = (\alpha/\gamma)(\beta/\gamma); d) \alpha/(β\gamma) = (\alpha/\beta)(\alpha/\gamma).$

17. Prove that a linear figure is necessarily convex.

18. Prove that all linear figures of the plane are exhausted by points, straight lines and all by the plane; in space, linear figures are points, straight lines, planes and all space.

19. Conditions write $\alpha \approx \beta$ if the figures $a$ and $b$ have at least one common point (for comparison, note that $\alpha = \beta$ if $a$ and $b$ all points are common).

Prove that the following elegant rule of proportion holds: if the figures $a, b, \gamma, \delta$ are such that $\alpha/\beta \approx \gamma/\delta$, then $\alpha\delta \approx \beta\gamma$ (the distance is first the case when $a, b, \gamma, \delta$ are points; Fig. 18). Prove also that $\alpha/\beta \approx \gamma\Leftrightarrow \beta\gamma \approx a$.

“Non-ενClidean” multiplication of points and figures

The content of this article is based on recent research by the American geometer Walter Penrowitz. The idea of ​​Penrowitz's research (not at all intended for beginner mathematicians, such as the readers of this journal) is to consider a wide class of new “geometries”, different from the “school” geometrics that attracted you.

⟦folio 16⟧

Euclid's metrics; these geometries can be called “non-ενClidean” geometries. Here are two examples of “non-ενClidean point multiplication” according to Penrowitz:

I. The product AB of points A and B on the coordinate plane is a rectangle with sides parallel to the coordinate axes, “spanned” by A and B (Fig. 19); if the line passing through points A and B is parallel to any of the coordinate axes, then the rectangle degenerates into a segment and the product AB coincides, by definition, with the product that we defined earlier.

II. We fix the figure P, formed by three rays emerging from one point O (Fig. 20). This figure will be our “universe”: we will further consider only points belonging to P and figures that are subsets of the set P. By the product AB of points A∈P and B∈P, we mean the shortest broken line that connects A and B inside the figure P.

After the product of points is determined, literally the same as before, the product of figures, convex figures, quotient of points, quotient of figures, linear figures are sequentially determined. figure 21 shows the quotient of points A/B for example I, and figure 22 shows the quotient A/B for example II (with different locations of points A and B).

It turns out that the theory of convex figures in “Penrowitz geometries” has a lot of promise with the corresponding theory in general ενClidean geometry.

Exercises

20. Check that the product AB and the quotient A/B of points for example I satisfies all the properties listed in the main part of the article and in the exercises. Which figures are convex in this “geometry”? Which ones are linear?

21. The same for example II.

The editorial collection of the magazine «Kvant» with deep regret informs readers about the untimely death of a member of the editorial collection of the famous Soviet mathematician, corresponding member of the USSR Academy of Sciences Anatoly Illarionovich Shirshov, which followed on February 28, 1981.
