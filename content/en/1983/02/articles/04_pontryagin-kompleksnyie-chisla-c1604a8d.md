---
id: 1983-2-pontryagin-kompleksnyie-chisla-c1604a8d
issue: kvant_1983_2
year: 1983
number: "2"
title: Complex numbers
authors:
  - Понтрягин Л. С.
rubric: raznoe
page_first: 18
page_last: 20
page_labels: 16-18
tag: "8038"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86c76d04c3f698476ee23291a073ffdd70ef41dc1adf1987ebb0a5face76a02d
prompt_sha256: draft-1
translated_from: content/ru/1983/02/articles/04_pontryagin-kompleksnyie-chisla-c1604a8d.md
source_content_sha256: f7922042e1d98d4d9a266d9f0f4c26fa8016cca995a58ebf0e9918e8f55576b6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Complex numbers

Academician L. S. PONTRYAGIN

Here I first of all very briefly talk about how complex numbers arose in mathematics and gradually established themselves in it. Then I give a definition of complex numbers, operations on them and their geometric interpretation. Along the way, formulas for cosine and sine of a sum are proved, which are closely related to the multiplication of complex numbers.

Historical background

From the course of mathematics it is known that negative numbers are introduced primarily so that the subtraction operation, the inverse of the addition operation, is always possible. For a similar reason, complex numbers appeared in mathematics. If we consider only real numbers, then the operation of extracting the square root, the inverse of the operation of squaring, is not always possible, since it is impossible to extract the square root of a negative number. This, however, is not enough to introduce new numbers in mathematics. It turned out that if the product of a calculation according to the usual rules over expressions in which the square root of a negative number occurs, then one can arrive at a result that no longer contains the square root

Definition of complex numbers

We will assume that we know the real numbers. We know that there are two basic operations defined for them - addition and multiplication - and there are inverse actions to them - subtraction and division. For these actions, several extracted rules will be executed, which are usually used completely automatically - so I will not formulate them here. The set of objects for which the operations of addition and multiplication and their inverse actions of subtraction and division are defined, and the object rules that apply to real numbers are fulfilled, is called a field in modern abstract algebra.

Thus, from the point of view of modern abstract algebra, the sets R of all real numbers represent a field. Let us now set ourselves the task of expanding the concept of number or, as

⟦folio 17⟧

say in abstract algebra, extend the field $R$ to the field $K$ such that in this new field $K$ the equation

$$z^2 + 1 = 0$$

(1)

had a decision. We denote the field element $K$ that satisfies equation (1) by $i$. Thus, for $i$ we have

$$i^2 = -1.$$

(2)

Since the field $K$ contains all real numbers and the element $i$ and since addition and multiplication operations are possible in it, the field $K$ must contain all possible polynomials with respect to $i$ with real coefficients, in particular - all polynomials of the first degree, that is, expressions of the form

$$z = x + yi = x + iy,$$

where $x$ and $y$ are real numbers. These expressions are called complex numbers. We define actions on them as actions on polynomials, taking into account conditions (2). Complex numbers of the form

$$z = x + 0i = x$$

are real numbers. Complex numbers of the form

$$z = 0 + yi = yi$$

The numbers are called minimum numbers.

Let $z_1 = x_1 + y_1 i$, $z_2 = x_2 + y_2 i$ be two complex numbers. According to the stated rule, the sum and product of these complex numbers are determined by the equalities

$$z_1 + z_2 = (x_1 + y_1 i) + (x_2 + y_2 i) =$$

$$= (x_1 + x_2) + (y_1 + y_2) i;$$

(3)

$$z_1 z_2 = (x_1 + y_1 i) (x_2 + y_2 i) =$$

$$= x_1 x_2 + (x_1 y_2 + y_1 x_2) i + y_1 y_2 i^2 =$$

$$= (x_1 x_2 - y_1 y_2) + (x_1 y_2 + y_1 x_2) i.$$

(4)

When obtaining the last equality, we use the result

$$x_1 z_2 = x_1 x_2 + x_1 y_2 i.$$

(5)

From formulas (3) and (4) it is clear that the sum and product of two complex numbers is also a complex number.

In order to make sure that the action of subtraction, the inverse of the action of addition, exists, it is enough to find the number $-z$, the opposite of the number $z$, and in order to make sure that division is possible, it is enough for $z \neq 0$ to indicate the number $z^{-1}$, the inverse of the number $z = x + yi$. These numbers, as is easy to see, are given by the formulas

$$-z = -x - yi,$$

$$z^{-1} = \frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2} i.$$

Thus, the quantity $z^{-1}$, the inverse of $z$, exists whenever $z \neq 0$.

Geometric representation of complex numbers

Let us denote the plane of our drawing by $P$ and select a rectangular coordinate system on it (Fig. 1). We will place the complex number $z = x + yi$ at the point $z = (x; y)$ with coordinates $x, y$. Let us also denote by $z$ the vector from the origin $O$ to the point $z$. Thus, the letter $z$ simultaneously denotes a complex number, the point $z$, representing this complex number, and the vector $z$, corresponding to this complex number. In this case, the images of real numbers fall on the abscissa axis - therefore the abscissa axis is called the real axis of the $P$ plane of the complex variable, and the number of numbers fall on the ordinate axis - therefore the ordinate axis is called the minimal axis of the $P$ plane of the complex variable. Zero falls at the origin.

Fig. 1.

⟦folio 18⟧

The length of the vector $z$ is called the modulus of the complex number $z = x + yi$ and is denoted $|z|$:

$$|z| = \sqrt{x^2 + y^2}.$$

Complex numbers $z$ satisfying the condition $|z| = 1$ form a circle of radius 1 centered at the origin. The number 1 lies on this circle. From point 1, we cut off arcs of a given length $\varphi$ along the circle in a counterclockwise direction. We denote the end of this arc by $(\varphi)$. If $\varphi$ is a negative number, then to obtain $(\varphi)$ you need to subtract the arc length $|\varphi|$ from point 1 clockwise. As is known, the abscissa of the point $(\varphi)$ is called cos $\varphi$, and its ordinate sin $\varphi$. Thus, the complex number $(\varphi)$ is given by

$$(\varphi) = \cos \varphi + i \sin \varphi.$$

So, any complex number $z$, equal to 1 according to the model, is written in the form (6). If $z$ is an arbitrary complex number whose model $|z| = \varphi$ is different from 0, then the number $z/\varphi$ is a complex number, according to the model, equal to 1, and therefore is written in the form (6). From equality

$$\frac{z}{\varphi} = \cos \varphi + i \sin \varphi$$

we get

$$z = \varphi(\cos \varphi + i \sin \varphi).$$

Recording (7) is called the trionometric formula of a complex number. The number $\varphi$ is called the argument of a complex number. If the model $\varphi$ of a complex number $z$ is nonzero, then the argument $\varphi$ is defined up to the term $2\pi k$, where $k$ is an integer. If the model $\varphi$ of a complex number is equal to 0, then formula (7) also holds, but in this case the argument of the complex number is not defined at all.

The numbers $\varphi$ and $\varphi$ are called the polar coordinates of the point $z$.

Let us now give a geometric source of action on complex numbers.

From formulas (3) and (5) it follows that complex numbers are added and multiplied by real numbers, like vectors.

The geometric meaning of adding complex numbers is very clear: the vector $z_1 + z_2$ is the diagonal of a parallelogram built on the vectors $z_1$ and $z_2$. This leads to an important inequality:

$$|z_1 + z_2| \leq |z_1| + |z_2|.$$

In order to give a geometric source multiplication of complex numbers, you need to use the operation of rotating a vector or, which is the same thing, a complex number. Rotate the vector $z$ counterclockwise by the angle $\alpha$, we get some new vector, which we denote by $R_\alpha(z)$. It is geometrically clear that the rotation operation $R_\alpha$ has the following property: if $\alpha$ is a real number, then

$$R_\alpha(az) = aR_\alpha(z),$$

$$R_\alpha(z_1 + z_2) = R_\alpha(z_1) + R_\alpha(z_2).$$

From these two formulas it follows that if $a_1$ and $a_2$ are two real numbers, then there is a correspondence

$$R_\alpha(a_1z_1 + a_2z_2) = a_1R_\alpha(z_1) + a_2R_\alpha(z_2).$$

It is also immediately clear that

$$R_\alpha(1) = \cos \alpha + i \sin \alpha.$$

Let us now prove that rotating the complex number $z = x + yi$ by the angle $\alpha$ is equivalent to multiplying it by the complex number $\cos \alpha + i \sin \alpha$, that is, that

$$R_\alpha(z) = (\cos \alpha + i \sin \alpha)z.$$

To do this, we first consider separately the rotation through the angle $d = \frac{\pi}{2}$. In this case, $\cos d + i \sin d = i$, and equality (11) takes the form $R_d(z) = iz$. On the one hand, there are geometric estimates that $R_d(1) = i$, $R_d(i) = -1$. On the other hand, $i \cdot 1 = i$, $i \cdot i = -1$. Thus,

$$R_d(1) = i \cdot 1, R_d(i) = i \cdot i.$$

It follows directly from formula (9)
