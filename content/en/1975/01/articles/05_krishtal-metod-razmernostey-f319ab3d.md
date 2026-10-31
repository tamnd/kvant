---
id: 1975-1-krishtal-metod-razmernostey-f319ab3d
issue: kvant_1975_1
year: 1975
number: "1"
title: Dimensional method
authors:
  - Кришталь Н. Д.
rubric: osnovnye-stati
page_first: 20
page_last: 23
page_labels: 18-21
tag: D1JG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a3e512cd8ad0cba2821a483891af3aebac3b02b307ef7f78b7a0113e5b7f7c0
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/05_krishtal-metod-razmernostey-f319ab3d.md
source_content_sha256: 0c1258ea6dfdfd6e83f03f3d41bd48934db3c1511aa9a154e74c021c010a760d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Dimensional method
N. D. Krishtal

This article discusses several problems that are solved using the dimensional method. This method is described in detail in the article by A. S. Kompaneets “Dimensions of physical quantities and similarity of phenomena” in this issue of the journal.

It is most convenient to demonstrate the main provisions of the dimensional method using specific examples. We will do this by analyzing the deformations and pressures that arise during the elastic interaction of two bodies. The absolute value of the force $F$ with which bodies resist external influences tending to change their shape and size is determined by Hooke’s law:

$$F = kx, \qquad (1)$$

where $x$ is the magnitude of deformation, $k$ is the elasticity coefficient. For tensile (or compressive) deformation, expression (1) can be rewritten in expanded form:

$$F = \frac{ES}{l}\,\Delta l. \qquad (2)$$

⟦figure⟧
Fig. 1

⟦folio 18⟧

⟦column⟧

Here $E$ is the elastic modulus (Young’s modulus) - a quantity characterizing the ability of a material to resist external influences; it does not depend on the shape and size of the sample under study, $S$ is the cross-sectional area perpendicular to the direction of the external force, $l$ is the length and $\Delta l$ is the change in the length of the deformed body.

Let us consider an elastic collision of balls.

Problem 1. *Two balls of radius $R$, made of a material with density $\rho$ and modulus of elasticity $E$, move towards each other along a straight line connecting their centers, with equal speeds $v$ (Fig. 1). An absolutely elastic impact occurs between the balls. Find the maximum amount of deformation $x$ during the impact.*

It is obvious that the value of $x$ can depend on all parameters characterizing the balls during impact, that is, on $v$, $\rho$, $R$ and $E$:

$$x = x(v,\ \rho,\ R,\ E).$$

We will look for this dependence in the form *)

$$x = A v^{p}\, \rho^{b}\, R^{c}\, E^{d}, \qquad (3)$$

where $A$ is the dimensionless proportionality coefficient ($[A] = 1$), $p$, $b$, $c$ and $d$ are currently unknown dimensionless exponents.

According to the doctrine of dimensions, the formulas for the dimensions of the left and right sides of equality (3) should be the same:

$$[x] = [v^{p}]\ [\rho^{b}]\ [R^{c}]\ [E^{d}]. \qquad (4)$$

This imposes certain conditions on the values ​​of indicators $p$, $b$, $c$ and $d$. Let us write down the dimensions of all quantities appearing on both sides of equality (3).

Length is the basic unit of measurement, so immediately write

---

*) Representation of the desired dependence in the form of a power function is an assumption, the validity of which must be proven. When strictly using the dimensional method, such an assumption is not made.

⟦folio 19⟧

we wai
$$[x] = \mathrm{L}, \quad [R] = \mathrm{L}.$$
It follows that volumes and areas have dimensions $\mathrm{L}^3$ and $\mathrm{L}^2$. By definition, speed characterizes the path traveled per unit time, which means
$$[v] = \frac{\mathrm{L}}{\mathrm{T}} = \mathrm{LT}^{-1}.$$

The density of a material is the amount of substance per unit volume, therefore
$$[\rho] = \frac{\mathrm{M}}{\mathrm{L}^3} = \mathrm{ML}^{-3}.$$

The dimension of the elastic modulus can be determined using Hooke's law and Newton's II law. From formula (2) it follows that
$$E = \frac{F}{S}\,\frac{l}{\Delta l}.$$

According to Newton's II law, force is equal to mass times acceleration:
$$F = ma.$$
Means,
$$E = \frac{ma}{S}\,\frac{l}{\Delta l}. \qquad (5)$$

Acceleration is the change in speed per unit time, so
$$[a] = \frac{[v]}{[t]} = \mathrm{LT}^{-2}.$$

The dimensions of the remaining quantities included in equation (5) can be written out immediately:
$$[m] = \mathrm{M}, \quad [S] = \mathrm{L}^2,$$
$$[l] = [\Delta l] = \mathrm{L}.$$
Hence,
$$[E] = \frac{\mathrm{MLT}^{-2}}{\mathrm{L}^2}\,\frac{\mathrm{L}}{\mathrm{L}} = \mathrm{ML}^{-1}\mathrm{T}^{-2}.$$

Let us substitute the dimensions of the corresponding quantities into equality (4):
$$\mathrm{L} = (\mathrm{LT}^{-1})^p\,(\mathrm{ML}^{-3})^b\,(\mathrm{L})^c\,(\mathrm{ML}^{-1}\mathrm{T}^{-2})^d,$$
or
$$\mathrm{L}^1 = \mathrm{L}^{p-3b+c-d}\ \mathrm{M}^{b+d}\ \mathrm{T}^{-(p+2d)}. \qquad (6)$$
The formulas for the dimensions of the left and right sides are the same if the exponents of the same symbols on the left and right sides are equal. Let us rewrite equation (6) in the form
$$\mathrm{L}^1\mathrm{M}^0\mathrm{T}^0 = \mathrm{L}^{p-3b+c-d}\mathrm{M}^{b+d}\mathrm{T}^{-(p+2d)}.$$

2\*

⟦column⟧

Equating the exponents with identical symbols on the left and right sides, we obtain a system of equations
$$\begin{cases} 1 = p - 3b + c - d, \\ 0 = b + d, \\ 0 = p + 2d, \end{cases}$$
from which we find
$$c = 1, \quad b = \frac{p}{2}, \quad d = -\frac{p}{2}.$$

Let's substitute these values ​​into (3):
$$x = Av^p\,\rho^{p/2}E^{-p/2}R,$$
or
$$\frac{x}{R} = A\left(\frac{\rho^{1/2}v}{E^{1/2}}\right)^p = A\left(\frac{\rho v^2}{E}\right)^{p/2}. \qquad (7)$$

The resulting expression determines the form of the equation for the relative deformation $\dfrac{x}{R}$ of the balls. However, $A$ and $p$ are still unknown.

Comparing expressions (3) and (7), it can be noted that consideration of the dimensions of quantities made it possible to replace the relationship between five dimensional quantities ($x$, $v$, $\rho$, $R$, $E$) with the relationship between two dimensionless quantities:
$$\left[\frac{x}{R}\right] = 1, \quad \left[\frac{\rho v^2}{E}\right] = 1.$$

If we were looking for the dependence $x = x(v,\ \rho,\ R,\ E)$ using experiment, then using the dimensional method would allow us to study, instead of the influence of four dimensional quantities on $x$, the influence of only one dimensionless quantity $\dfrac{\rho v^2}{E}$ on $\dfrac{x}{R}$. This gives great convenience to the experimenter, since it allows one to significantly reduce the number of necessary experiments.

It should be noted that the coefficient $A$ cannot be determined by the dimensional method, since it is in no way related to the exponents in the formulas for the dimensions of quantities. The indicator $p$ is related to dimensional formulas, so in some cases it can be

define. Let's try to highlight cases when this can be done.

In our problem there are four unknown exponents $p$, $b$, $c$, $d$ and three equations for their determination. The number of equations that can be constructed to find unknown coefficients is equal to the number of basic units of measurement. To determine the numerical values ​​of all unknown indicators, it is necessary that their number be equal to the number of independent equations in the system. This is possible only in two cases: if you choose a system of measurement units with four basic units or if you reasonably reduce the number of independent variables (and therefore the number of unknown indicators).

We will consider the second way. Let us assume that the deformation that occurs upon impact depends only on the elastic modulus $E$ and on the kinetic energy of the ball $\mathrm{K} = \dfrac{mv^2}{2}$, where $m$ is the mass of the ball. Here we take into account the size of the ball only in the expression for kinetic energy: $\mathrm{K} = \dfrac{1}{2}\ \dfrac{4}{3}\ \pi R^3 \rho v^2$.

(This is a rough assumption, because the magnitude of the deformation depends not only on the kinetic energy, but also on the radius of the ball $R$.) This assumption allows us to approximately write:

$$x = A_1 \mathrm{K}^{p_1} E^{b_1}.$$

Dimension of kinetic energy

$$[\mathrm{K}] = [mv^2] = \mathrm{ML^2T^{-2}}.$$

If we now compose a system of equations and determine the values ​​of $p_1$ and $b_1$ (similar to how it was done above), we obtain

$$\frac{x}{R} = \frac{A_1}{R}\left(\frac{\mathrm{K}}{E}\right)^{1/3} = A_2 \left(\frac{\rho v^2}{E}\right)^{1/3}. \qquad (8)$$

The exponent $^1/_3$ in formula (8) is close to the exponent $^2/_5$ obtained from a rigorous mathematical solution of the problem\*).

---

\*) For another way to obtain formula (8), see, for example, the article by G. L. Kotkin “Collision of balls”, «Kvant», 1973, No. 3.

⟦column⟧

When using the dimensional method, it is very important to correctly formulate the problem, because the formulation of the problem identifies those parameters on which the desired value depends. When solving the problem of elastic collision of balls, we took into account the ability of the balls’ material to resist the spread of deformation inside the ball ($E$), the shape and size of the area under study (balls of radius $R$), the external influence on the area under study (through the speed $v$ and the density of the material of each ball $\rho$).

Problem 2. *Find the deformation that occurs in balls of radius $R$ under the action of two compressive forces $F$ directed along the line connecting the centers of the balls. The material of the balls is the same, and its elastic modulus is $E$.*

Here, as in the first problem, we know the shape and size of the objects (balls of radius $R$), the external influence on the balls (forces $F$) and the properties of the material of the balls (Young’s modulus $E$).

To solve the problem, we need to find the dependence of the magnitude of deformation $x$ on the values ​​$F$, $R$ and $E$. We will again look for this dependence in the form

$$x = A_3 F^n R^s E^t, \qquad (9)$$

or for dimensions

$$[x] = [F^n]\ [R^s]\ [E^t]. \qquad (10)$$

The dimension of force $F$ is equal to

$$[F] = [ma] = \mathrm{MLT^{-2}}.$$

Substituting the dimensions of the quantities $x$, $F$, $R$, $E$ into (10), we obtain

$$\mathrm{L} = (\mathrm{MLT^{-2}})^n \mathrm{L}^s (\mathrm{ML^{-1}T^{-2}})^t,$$

or

$$\mathrm{L^1M^0T^0} = \mathrm{L}^{n+s-t}\mathrm{M}^{n+t}\mathrm{T}^{-2n-2t}.$$

Let us equate the exponents for the same symbols on the left and right sides of this equation:

$$\begin{cases} 1 = n + s - t, \\ 0 = n + t, \\ 0 = -2n - 2t. \end{cases}$$

From here

$$t = -n, \quad s = 1 - 2n.$$

Hence,

$$x = A_3 F^n R^{1-2n} E^{-n} = A_3 R \left(\frac{F}{ER^2}\right)^n,$$

⟦folio 20⟧

⟦figure⟧
Fig. 2.

or
$$\frac{x}{R} = A_3 \left(\frac{F}{ER^2}\right)^n. \qquad (11)$$

In general, external influence on balls changes the state of the material of the balls. This change in the state of the material is characterized by the concept of “stress”. The stress of the material in section $S$ (Fig. 2) under the action of external forces $F$ is called the value $\sigma = F/S$, where $S$ is the cross-sectional area. The stress that occurs under the action of forces directed perpendicular to the section under consideration is called normal stress or pressure. Stress characterizes the specific load on the material (load per unit cross-sectional area of ​​the body). With increasing specific loads, the material first becomes inelastic and then collapses. Therefore, determination of stresses is of practical interest.

Problem 3. *Find the stress $\sigma$ at the point of contact of two balls of radius $R$, arising under the action of compressive forces $F$ (see Fig. 2), if the balls are made of a material with an elastic modulus $E$.*

Obviously, $\sigma$ depends on $F$, $E$ and $R$:
$$\sigma = \sigma(F,\ E,\ R).$$
We will again assume that this dependence has the form
$$\sigma = A_4 F^{n_1}\ R^{s_1}\ E^{t_1}. \qquad (12)$$
From the definition of voltage it follows that the dimension of voltage is

⟦column⟧

the dimension of force divided by the dimension of area:
$$[\sigma] = \frac{[F]}{[S]} = \frac{\mathrm{MLT}^{-2}}{\mathrm{L}^2} = \mathrm{ML}^{-1}\mathrm{T}^{-2}.$$

Therefore, taking into account (12),
$$\mathrm{ML}^{-1}\mathrm{T}^{-2} = (\mathrm{MLT}^{-2})^{n_1}\ \mathrm{L}^{s_1}\ (\mathrm{ML}^{-1}\mathrm{T}^{-2})^{t_1},$$
where
$$\left\{ \begin{array}{l} 1 = n_1 + t_1, \\ -1 = n_1 + s_1 - t_1, \\ -2 = -2n_1 - 2t_1. \end{array} \right.$$

Having made the appropriate calculations, we get
$$\sigma = A_4 F^{n_1} R^{-2n_1}\ E^{1-n_1},$$
or
$$\frac{\sigma}{E} = A_4 \left(\frac{F}{ER^2}\right)^{n_1}. \qquad (13)$$

Let us note once again that the dimensional method is widely used in those problems where, due to the large number of variables and the complexity of the equations describing the phenomenon, an analytical solution is impossible. In this case, an experiment is carried out to find the necessary dependencies. The experimental results are processed using dimensionless combinations of problem parameters, which can be distinguished by the dimensional method. Thus, in the problems considered in this article, the dimensional method allows us to state that relative deformations and stresses are determined not by individual numerical values of the parameters $v$, $\rho$, $E$, $R$ or $F$, $E$, $R$, but by the numerical value of dimensionless combinations of parameters $\dfrac{\rho v^2}{E}$ and $\dfrac{F}{ER^2}$.

Exercises

1. Show that the stress arising in balls moving towards each other with a speed of $v$ at the moment of collision is determined by the expression
$$\frac{\sigma}{E} = A \left(\frac{\rho v^2}{E}\right)^n.$$

2. Show that when two balls with radii $R_1$ and $R_2$ collide, the stress at the point of contact is described by the formula
$$\frac{\sigma}{E} = A \left(\frac{\rho v^2}{E}\right)^n \left(\frac{R_2}{R_1}\right)^r.$$

⟦folio 21⟧
