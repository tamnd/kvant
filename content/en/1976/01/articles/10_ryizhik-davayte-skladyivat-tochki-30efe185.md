---
id: 1976-1-ryizhik-davayte-skladyivat-tochki-30efe185
issue: kvant_1976_1
year: 1976
number: "1"
title: Let's connect the dots...
authors:
  - Рыжик В. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 46
page_last: 50
page_labels: 44-48
tag: H0S1
lang: en
source: kvant_digital
extraction: vision
content_sha256: bbe426f30b5a05d03dd36d9c4f0e483c61d84bb9c2a438b9a439e056bb9a3719
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/10_ryizhik-davayte-skladyivat-tochki-30efe185.md
source_content_sha256: 30b9fde58dbf26a8bbffaee14abcf01eb23a245e0f95f31403555d4e45d2006a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

V. Ryzhik

Let's connect the dots...

Mathematics can be studied in different ways. You can listen to lectures or take just a book and read it in a row: definitions, theorems, proofs. Or you can act more actively: read only the definitions and statements of the theorems, put the book aside and come up with proofs yourself. The first method allows the target to move faster. But mismo of those who adhere exclusively to this method of information technology, often go through the techniques and methods with the help of which the results in question were obtained. The reader has no idea how much he will miss out on interesting, fascinating, useful things, dooming himself to the role of a passive perceiver of truths.

The second method, although it takes more time, allows you to deeply understand mathematical theory, teaches you to highlight what is most important in a given context, makes it possible to remember the results obtained through your own work for a long time, develops the mathematical abilities of schoolchildren and opens up new ways for them to apply mathematical knowledge. Therefore, it is precisely this method - the independent discovery of known truths (sometimes in violation of which previously unknown ones are discovered) that determined the use of mathematical seminars, schools and circles in the work.

It is precisely this kind of active work that the reader is intended to do in the articles published in the “Mathematics Circle” section. A significant part of the content of the article is usually presented in the form of tasks. Some of them are solved in the text, but most - both in lectures and difficult ones - are left for the reader to decide independently. Brief solutions to these problems, instructions or answers to them are sometimes placed on the last pages of the magazine, but we advise you to try to solve the problems without a hint.

As a rule, our “Math Club” is available to students of 8-9, and sometimes 7th grade. Letters with comments and suggestions regarding this section should be sent using the “Math circle” on the envelope.

⟦folio 45⟧

but, the point $D$, which is obtained if the vector $\overrightarrow{OB}$ is subtracted from the vector $\overrightarrow{OA}$, is called the difference of the points $A$ and $B$: $D = A - B$.

It is clear that the sum of the points depends on where we chose the stripes. But as soon as the stripes are fixed, the addition of points is similar to the addition of vectors.

Exercises
1. How should stripes be chosen so that the sum of two points $A$ and $B$ lies on the line $AB$? On beam $AB$? On the segment $AB$?
2. Add up the three vertices of an equilateral triangle with different choices of stripes: at the vertex of the triangle, at its center, at an arbitrary point.
3. $A, B, C$ - any three points that do not lie on the same line. Select the stripes so that their sum lies inside the triangle $ABC$; outside of it.
4. Let $A_1, A_2, \dots, A_n$ be a regular polygon. Where should the stripes $O$ be chosen so that the equality $A_1 + A_2 + \dots + A_n = O$ holds? Is the band uniquely determined by this condition?
5. Prove that the quadrilateral $ABCD$ is a parallelogram if and only if $A + C = B + D$.

Now it’s easy to tell what it means to multiply a point by a number. Let strip $O$ be given. Let's take the primordial point $A$. Let's assume that it needs to be multiplied by 2. Multiply the vector $OA$ by 2, we get the vector $OB$; point $B$ will be the desired one. We write: $B = 2A$. In general, if $\overrightarrow{OB} = \lambda \cdot \overrightarrow{OA}$, then we will call the point $B$ the product of the point $A$ and the number $\lambda$: $B = \lambda A$. Since we defined the multiplication of points by numbers through the multiplication of vectors by numbers, then to multiply points by numbers the equalities $1^\circ - 3^\circ$ are satisfied if we replace the vectors with points in them.

Let's call the expression $\alpha \cdot A + \beta \cdot B$, where $\alpha$ and $\beta$ are numbers, a linear combination of the points $A$ and $B$.

Exercises
6. Construct the difference between points $A$ and $B$. Construct, taking points $A, B$ and stripes $O$ not on the same line, points $-B, -A, -A-B, -A+B$.
7. Prove that if the strip does not lie on the same straight line from the points $A$ and $B$, then every point in the plane can be represented as a linear combination of the points $A$ and $B$, and in a unique way.
8. The stripes are selected at the center of the correct hexagon $A_1A_2 \dots A_6$. Write points $A_3, A_4, A_5, A_6$ as linear combinations of points $A_1$ and $A_2$.
9. Can the point $2 \cdot A + 3 \cdot B$ lie on the line $AB$? Under what conditions?

In previous tasks, the results of actions with dots depended on the choice of stripe and were thus ambiguous. However, there is a way of operating with an arbitrary point system, the result of which no longer depends on this choice (this method turns out to be useful to us in the future, when solving “real” geometric problems). Let's see when the linear combination of two points $A$ and $B$ does not depend on the choice of stripe.

Let $X_1 = \alpha \cdot A + \beta \cdot B$ if the point $O_1$ is a stripe, and $X_2 = \alpha \cdot A + \beta \cdot B$ if the point $O_2$ is a stripe. We want points $X_1$ and $X_2$ to match; for this it is necessary and sufficient that the equality $\overrightarrow{O_1X_1} = \overrightarrow{O_1X_2}$ be satisfied. We have: $\overrightarrow{O_1X_2} = \overrightarrow{O_1O_2} + \alpha \cdot \overrightarrow{O_2A} + \beta \cdot \overrightarrow{O_2B} = \overrightarrow{O_1O_2} + \alpha \cdot (\overrightarrow{O_1A} - \overrightarrow{O_1O_2}) + \beta \cdot (\overrightarrow{O_1B} - \overrightarrow{O_1O_2}) = \alpha \cdot \overrightarrow{O_1A} + \beta \cdot \overrightarrow{O_1B} + [1 - (\alpha + \beta)] \cdot \overrightarrow{O_1O_2} = \overrightarrow{O_1X_1} + [1 - (\alpha + \beta)] \cdot \overrightarrow{O_1O_2}$. For equality of vectors $\overrightarrow{O_1X_2}$ and $\overrightarrow{O_1X_1}$

⟦folio 46⟧

it is necessary and sufficient that $\alpha + \beta = 1$.

In the same way, a similar statement is proved for the $n$ points: the linear combination $\alpha_1 \cdot A_1 + \alpha_2 \cdot A_2 + \dots + \alpha_n \cdot A_n$ determines the only point of the moed and the milk moed, the coed $\alpha_1 + \alpha_2 + \dots + \alpha_n = 1$. Prove it.

We will call a linear combination of points normalized if the sum of the coefficients in this linear combination is equal to 1. In the future, we will work mainly with normalized linear combinations of points, without limiting this each time.

The concept of a normalized linear combination of $n$ points has a simple mechanical meaning: let the points $A_1, A_2, \dots, A_n$ contain masses $\mu_1 > 0, \mu_2 > 0, \dots, \mu_n > 0$, and $\mu_1 + \mu_2 + \dots + \mu_n = 1$. The linear combination $\mu_1 A_1 + \mu_2 A_2 + \dots + \mu_n A_n$ is the center of gravity C of the $n$ mass system (see exercise 14) *).

The following theorem obliges the visual geometric meaning of an arbitrary normalized linear combination of two points.

*) With the help of this mechanical interpretation, you can obtain many beautiful facts and theorems of geometry - see, for example, the article by Z. A. Skorets “The distance between the centers of two systems of points” (Kvant, 1975, No. 3). However, in our note we derive all the concepts we need from operations on vectors on the plane and in space. (One of the advantages of such a presentation is that one can immediately consider linear combinations in which the non-negative “mass” $\mu_1, \mu_2, \dots, \mu_n$ are negative).

Let us now see what the proof of the theorem on medians of a triangle will look like if they are used at one point and divided

⟦folio 47⟧

Fig. 3.

it in a ratio of 2:1, counting the apexes.

Let the medians AE and BK be drawn in triangle ABC, and let H be the point from the intersection (Fig. 3). Let us select stripes at point A.

Then $H = \lambda E = \lambda \left( \frac{1}{2} B + \frac{1}{2} C \right) = \frac{\lambda}{2} B + \frac{\lambda}{2} C$

(we don’t know what the number $\lambda$ is equal to). On the other hand, point H lies on line BK; therefore $H = \alpha B + \beta K = \alpha B + (1 - \alpha) K$, that is $H = \alpha B + \frac{1 - \alpha}{2} C$.

Due to the unique representation of point H as a linear combination of points B and C (see exercise 7)

$$\begin{cases} \frac{\lambda}{2} = \alpha, \\ \frac{\lambda}{2} = \frac{1 - \alpha}{2}. \end{cases}$$

Having solved this system, we obtain $\lambda = \frac{2}{3}$, $\alpha = \frac{1}{3}$, whence $\beta = \frac{2}{3}$. These coefficient values ​​give the following ratios of the lengths of the segments: $|AH| : |HE| = 2:1$, $|BH| : |HK| = 2:1$. It remains to show that H belongs to the median of the triangle. Since $H = \frac{2}{3} E$, then $H = \frac{1}{3} (B + C)$. But $B = 2T$, where T is the midpoint of side AB. Therefore $H = \frac{1}{3} (2T + C)$, that is $H = \frac{2}{3} T + \frac{1}{3} C$. The sum of the coefficients is 1, both of them are positive, so H is a point on the segment CT dividing it in the ratio 2:1.

The reasoning we used in proving the Omega Theorem helps in many cases, together with additional constructions, consideration of similar triangles, etc. make do with simple calculations.

The general scheme of the discussion is as follows:

1) we select stripes at the most convenient point for the solution (if we work with normalized linear combinations, then this does not affect anything);

2) for each point we obtain two representations in the form of a linear combination of two points that do not lie on the same straight line with the strip;

3) we solve a system that connects the coefficients of the resulting linear combinations with each other (in normalized combinations, another condition appears that the sum of the coefficients is equal to 1).

Try using this scheme in the following problems.

Exercises

15. In triangle ABC, points K and E are placed on sides AC and BC so that $|AK| = \frac{1}{n} |AC|$, $|BE| = \frac{1}{n} |BC|$. In each relation, are the segments AE and BK divided by the point of intersection? Does it lie on the median drawn from vertex C?

16. In triangle ABC, segments AK, CE and BM are plotted on sides AC, CB and BA so that each of them is $\frac{1}{3}$ of the corresponding side. Sections AE, CM, BK were carried out. In each relation they were separated by points of intersection?

17. The prime intersects triangle ABC so that side AB is divided in the ratio of 2:1, side BC in the ratio of 3:1. In each relation, is the segment AE divided by vertex C from vertex A to the point E of the intersection of line AC with this line? Try to generalize this problem.

18. The vertex of the parallelogram is connected to the midpoints of the opposite sides. In each relation, do the drawn segments divide the diagonal of the parallelogram opposite the given vertex?

Basically everything we have done so far has happened on the plane. Now let’s “go out” into space.

Theorem 2. Every point of the plane ABC is normalized

⟦folio 48⟧

linear combination of points A, B and C.

Proof. Let the point X belong to the plane ABC (Fig. 4). We have $\overrightarrow{OX} = \overrightarrow{OA} + \overrightarrow{AX}$. Since points A, B, C do not lie on the same line, then $\overrightarrow{AX} = \lambda_1 \cdot \overrightarrow{AB} + \lambda_2 \cdot \overrightarrow{AC}$. Now we get: $\overrightarrow{OX} = \overrightarrow{OA} + \lambda_1 \cdot \overrightarrow{AB} + \lambda_2 \cdot \overrightarrow{AC} = \overrightarrow{OA} + \lambda_1 \cdot (\overrightarrow{OB} - \overrightarrow{OA}) + \lambda_2 (\overrightarrow{OC} - \overrightarrow{OA}) = (1 - \lambda_1 - \lambda_2) \cdot \overrightarrow{OA} + \lambda_1 \cdot \overrightarrow{OB} + \lambda_2 \cdot \overrightarrow{OC}$. The sum of the coefficients is equal to 1. Let us denote the number 1 - $\lambda_1 - \lambda_2$ by $\alpha$, the number $\lambda_1$ - by $\beta$ and $\lambda_2$ - by $\gamma$; then $X = \alpha A + \beta B + \gamma C$, where $\alpha + \beta + \gamma = 1$.

Exercise

19. Prove the converse: every normalized linear combination of points A, B and C that do not lie on the same line belongs to the ABC plane.

20. If three points and stripes do not lie in the same plane, then every point in space is uniquely represented as a linear combination of these three points. Prove it.

Solving elementary stereometric problems using actions on points is based on the same principles as solving planimetric problems. Consider, for example, the following problem: in parallelind $ABCEA_1B_1C_1E_1$ the diagonal AC$_1$ is drawn; prove that planes A$_1$BE and B$_1$E$_1$C divide this diagonal into three segments of equal length.

To prove this, we choose stripes at point A (Fig. 5). Let K be the intersection point of the line AC$_1$ and the plane A$_1$BE. Then K = $\lambda \cdot C_1$, that is, K = $\lambda \cdot (B + E + A_1)$. On the other hand, K belongs to the plane A$_1$BE; therefore K = $\alpha \cdot A_1 + \beta \cdot B + \gamma \cdot E$, where $\alpha + \beta + \gamma = 1$. We get the system:

$\alpha = \lambda$; $\beta = \lambda$; $\gamma = \lambda$; $\alpha + \beta + \gamma = 1$, from which is found that $\lambda = \frac{1}{3}$. Thus, $|AK| = \frac{1}{3}|AC_1|$. Let now M be the intersection point of the line AC$_1$ and the plane B$_1$E$_1$C. Similar reasoning shows that M = $\frac{2}{3}C_1$, hence $|AM| = \frac{2}{3}|AC_1|$.

Exercise

21. Prove that all diagonals of a paralleliped intersect at one point.

Note that calling the operations “addition” and “multiplication by a number”, which we introduced for points, is not generally accepted. Obviously they do not speak about linear combinations of points $\alpha_1A_1 + \ldots + \alpha_nA_n$, but about linear combinations of vectors $\alpha_1\overrightarrow{OA}_1 + \ldots + \alpha_n\overrightarrow{OA}_n$, explicitly indicating the choice of the “pole” O. This, of course, does not change the existing division - the difference is only in the notation; It is precisely in the brevity of the notation that the main advantage of the “algebra of points” that you became acquainted with in this article lies.
