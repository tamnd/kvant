---
id: 1982-3-pontryagin-kompleksnyie-chisla-d06fe223
issue: kvant_1982_3
year: 1982
number: "3"
title: Complex numbers
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 6
page_last: 7
page_labels: 4-5
tag: EDGX
lang: en
source: kvant_digital
extraction: vision
content_sha256: d7800ada7780a812221499b4a72570619779d3da60f7dbdae8486292c259aa53
prompt_sha256: draft-1
translated_from: content/ru/1982/03/articles/03_pontryagin-kompleksnyie-chisla-d06fe223.md
source_content_sha256: d2dba5eb43244367b7bb3b2bf361ed9a754d8e64008285cfe3d17f158c173ea8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

Let us now set ourselves the task of expanding the concept of number or, as they say in abstract algebra, expanding the field $R$ to the field $K$ in such a way that in this new field $K$ the equation

$$z^2 + 1 = 0$$

(1)

had a decision. We denote the field element $K$ that satisfies equation (1) by $i$. Thus, for $i$ we have

$$i^2 = -1.$$

(2)

Since the field $K$ contains all real numbers and the element $i$ and since addition and multiplication are possible in it, the field $K$ should contain all possible polynomials with respect to $i$ with real coefficients, in particular - all polynomials of the first degree, that is, expressions of the form

$$z = x + yi = x + iy,$$

where $x$ and $y$ are real numbers. These expressions are called complex numbers. We define actions on them as actions on polynomials, taking into account condition (2). Complex numbers of the form

$$z = x + 0i = x$$

are real numbers. Complex numbers of the form

$$z = 0 + yi = yi$$

The number is called a minimum number.

Let $z_1 = x_1 + y_1 i$, $z_2 = x_2 + y_2 i$ be two complex numbers. According to the stated rule, the sum and product of these complex numbers are determined by the equalities

$$z_1 + z_2 = (x_1 + y_1 i) + (x_2 + y_2 i) > = (x_1 + x_2) + (y_1 + y_2) i;$$

$$z_1 z_2 = (x_1 + y_1 i) (x_2 + y_2 i) = x_1 x_2 + (x_1 y_2 + y_1 x_2) i + y_1 y_2 i^2 = (x_1 x_2 - y_1 y_2) + (x_1 y_2 + y_1 x_2) i.$$

When obtaining the last equality, we use the result

$$x_1 z_2 = x_1 x_2 + x_1 y_2 i.$$

(5)

From formulas (3) and (4) it is clear that the sum and product of two complex

Of all numbers there is also a complex number.

In order to make sure that the action of subtraction, the inverse of the action of addition, exists, it is enough to find the number - $z$, the opposite of the number $z$, and in order to make sure that division is possible, it is enough for $z \neq 0$ to indicate the number $z^{-1}$, the inverse of the number $z = x + yi$. These numbers, as is easy to see, are given by the formulas

$$-z = -x - yi,$$

$$z^{-1} = \frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2} i.$$

Thus, the quantity $z^{-1}$, the inverse of $z$, exists whenever $z \neq 0$.

**Geometric representation of complex numbers**

Let us denote the plane of our drawing by $P$ and select a rectangular coordinate system on it (Fig. 1). We will place the complex number $z = x + yi$ at the point $z = (x; y)$ with coordinates $x, y$. Let us also denote by $z$ the vector going from the origin $O$ to the point $z$. Thus, the letter $z$ simultaneously denotes a complex number, the point $z$, representing this complex number, and the vector $z$, corresponding to this complex number. In this case, the images of the real numbers fall on the abscissa axis - therefore the abscissa axis is called the real plane $P$ of the complex variable, and the number of the number falls on the ordinate axis - therefore the ordinate axis is called the minimum of the $P$ plane of the complex variable. Zero falls at the origin.

The length of the vector $z$ is called the modуlem of the complex number $z =$

Fig. 1.

⟦folio 5⟧

$$= x + yi \text{ и обозначется } |z|:
|z| = \sqrt{x^2 + y^2}.$$

Complex numbers $z$ satisfying the condition $|z| = 1$ form a circle of radius 1 centered at the origin. The number 1 lies on this circle. From point 1, we draw an arc of a given length $\varphi$ along the circle in a counterclockwise direction. We denote the end of this line by $(\varphi)$. If $\varphi$ is a negative number, then to obtain $(\varphi)$ you need to subtract the arc length $|\varphi|$ from point 1 clockwise. As is known, the abscissa of the point $(\varphi)$ is called cos $\varphi$, and its ordinate sin $\varphi$. Thus, the complex number $(\varphi)$ is given by

$$(\varphi) = \cos \varphi + i \sin \varphi.$$

So, any complex number $z$, equal to 1 according to the model, is written in the form (6). If $z$ is an arbitrary complex number whose model $|z| = \varphi$ differs from 0, then the number $z/\varphi$ is a complex number, according to the model, equal to 1, and therefore is written in the form (6). From equality

$$\frac{z}{\varphi} = \cos \varphi + i \sin \varphi$$

we get

$$z = \varphi (\cos \varphi + i \sin \varphi).$$

Recording (7) is called the trionometric formula of a complex number. The number $\varphi$ is called the argument of a complex number. If the model $\varphi$ of a complex number $z$ is distinguished from zero, then the argument $\varphi$ determines up to the term $2\pi k$, where $k$ is an integer. If the model $\varphi$ of a complex number is equal to 0, then formula (7) also holds, but in this case the argument of the complex number is not defined at all.

The numbers $\rho$ and $\varphi$ are called the polar coordinates of the point $z$.

Let us now give a geometric source of action on complex numbers.

From formulas (3) and (5) it follows that complex numbers are added and multiplied by real numbers, like vectors.

The geometric meaning of adding complex numbers is very clear: the vector $z_1 + z_2$ is the diagonal of the parallelogamma built on the vectors $z_1$ and $z_2$. This leads to an important inequality

$$|z_1 + z_2| \leq |z_1| + |z_2|.$$

In order to give geometric sources of multiplication of complex numbers, you need to use the operation of rotating a vector or, which is the same thing, a complex number. Rotate the vector $z$ counterclockwise by the angle $\alpha$, we get some new vector, which we denote by $R_\alpha(\alpha)$. Geometrically it is clear that the rotation operation $R_\alpha$ has the following property: if $a$ is a real number, then

$$R_\alpha(az) = aR_\alpha(z),$$

$$R_\alpha(z_1 + z_2) = R_\alpha(z_1) + R_\alpha(z_2).$$

From these two formulas it follows that if $a_1$ and $a_2$ are two real numbers, then the correspondence $R_\alpha(a_1z_1 + a_2z_2) = a_1R_\alpha(z_1) + a_2R_\alpha(z_2)$ holds.

It is also immediately clear that

$$R_\alpha(1) = \cos \alpha + i \sin \alpha.$$

Let us now prove that rotating the complex number $z = x + yi$ by the angle $\alpha$ is equivalent to multiplying it by the complex number $\cos \alpha + i \sin \alpha$, that is, that

$$R_\alpha(z) = (\cos \alpha + i \sin \alpha)z.$$

To do this, we first consider separately the rotation through the angle $d = \frac{\pi}{2}$. In this case, $\cos d + i \sin d = i$, and equality (11) takes the form $R_dz = iz$. On the one hand, geometric estimates that $R_d(1) = i, R_d(i) = -1$. On the other hand, $i \cdot 1 = i, i \cdot i = -1$. Thus,

$$R_d(1) = i \cdot 1, R_d(i) = i \cdot i.$$

It follows directly from formula (9)

$$iz = i \cdot (x + iy) = x \cdot i + y(-1) = xR_d(1) + yR_d(i) = R_d(x \cdot 1 + y \cdot 1) = R_d(x + iy) = R_d(z).$$

Thus, formula (11) is proven for $\alpha = \frac{\pi}{2}$.
