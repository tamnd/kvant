---
id: 1976-11-dozorov-elektricheskie-multipoli-ca62541e
issue: kvant_1976_11
year: 1976
number: "11"
title: Electrical multipoles
authors:
  - Дозоров А. А.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: 69PW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 902b37b589af78609c47cdb60feb7f692a38ca6e26f9f416e0095674960837d6
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/02_dozorov-elektricheskie-multipoli-ca62541e.md
source_content_sha256: 65192a929a8efbc64e51a4eb20e2b2b5c5ea167f2eed6ed9b6649a077d729cb2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Electrical multipoles

The potential of the electrostatic field created by a precise charge at some point in the surrounding space is inversely proportional to the distance from the charge to this point (see appendix at the end of the statistic). Each would be that any set of charges concentrated in a certain region, far from this region, will create a potential inversely proportional to the distance. However, this conclusion is not true in the general case. It turns out that by arranging the charges in a certain order, you can get a potential that is inversely proportional to any integer power of the distance.

In order to be convinced of this unusual property, we need only one mathematical statement: if the value $|x|$ is less than one, then the correspondence is true

$$\frac{1}{1-x} = 1 + x + x^2 + x^3 + x^4 + \dots$$

(1)

This is the familiar expression for the sum of an infinite decreasing geometric progression.

Let's move on to consider various systems of electrostatic charges. At a distance $r$ from the exact charge $q$, the magnitude of the potential, φ, created by this charge is inversely proportional to the distance: $\varphi = \frac{kq}{\varepsilon r}$. The proportional coefficient $k$ depends on the choice of system of units. In SI $k = \frac{1}{4\pi\varepsilon_0}$. It will be more convenient for us to choose a system of units in which $k = 1$ (SGSE system). In addition, we will assume that all charges are in vacuum, that is, $\varepsilon = 1$.

Consider, for example, three charges located on the same straight line at a certain distance from each other (Fig. 1). Let $AB = a$, $AC = b$, and the magnitudes of the charges be $q$, $nq$ and $mq$, where $n$ and $m$ are some numbers. Let's find the potential at point $D$, lying on the continuation of the segment $AC$ at a distance $r$ from point $A$ and located sufficiently far from all three charges. Mathematically, the last condition can be written as $r \gg a + b$. According to the principle of superposition of electric fields, the potential $φ$ at point $D$ is equal to the algebraic sum of the field potentials created by each charge:

$$\varphi = \frac{q}{r} + \frac{nq}{r-a} + \frac{mq}{r-b} = \frac{q}{r} \left( 1 + \frac{n}{1-a} + \frac{m}{1-b} \right).$$

Since we are only interested in the case $r \gg a + b$, we can use correspondence (1). In this case we get

$$\varphi = \frac{q}{r} \left[ 1 + n \left( 1 + \frac{a}{r} + \frac{a^2}{r^2} \right) + \frac{a^3}{r^3} + \dots \right] + m \left( 1 + \frac{b}{r} + \frac{b^2}{r^2} + \frac{b^3}{r^3} + \dots \right) = \frac{q + nq + mq}{r} + q \frac{na^2 + mb^2}{r^3} + q \frac{na^3 + mb^3}{r^4} + \dots.$$

From this expression it is clear that for large distances $r$ the absolute value of each subsequent term is significant less than the previous one, unless the numerator of the previous term is equal to zero. For example, if the sum of charges is not

⟦folio 4⟧

to the previous $2^n$-field, add the same $2^n$-field, but only symmetrically shifted to a certain distance and, moreover, with charges of opposite sign. The result is a system consisting, as they say, of two opposite $2^n$-fields. This new system forms a multipole of $(n+1)$ order $(2^{n+1}-поль)$.

Let's look at a few examples.

Point charge - $q$ - zero order multipole. From it we form a first-order multipole $(2$-field), which is usually called a dipole. Let's shift the exact charge - $q$ by a distance $l$ and change the sign of the charge. In this case, we obtain the dipole shown in figure 2. It is usually characterized by the so-called dipole moment $d = ql$; the vector $l$ is directed from the negative charge to the positive charge, and its length is equal to the distance between the charges.

Let us calculate the potential $\varphi_1$ created by the dipole field at a remote point $D$ lying on the continuation of the line connecting the charges $(AD = r \gg l)$:

$$\varphi_1 = \frac{-q}{r} + \frac{q}{r-l} = \frac{q}{r} \left( -1 + \frac{1}{1-l} \right).$$

Accepting correspondence (1), we obtain the main part of the potential created by the dipole:

$$\varphi_{\text{BN}} = \frac{ql}{r^2} = \frac{d}{r^2}.$$

If the observed point does not lie on the line connecting the charges, then its position can be characterized by two coordinates: the distance to one of the charges and, for example, the angle between the dipole moment

$$\text{Рис. 2.}$$

Fig. 3.

volume and radius vector drawn from the positive *) charge to the point is observed.

On figure 2, point $C$ is characterized by coordinates $\rho = BC$ and angle $\theta$. In this case, the calculation of the potential becomes somewhat more complicated. Let's just give the result:

$$\varphi_1 = \frac{d \cos \theta}{\rho^2}.$$

In order to form a second-order multipole ($(2^2$-field, more often called a quadruple) from a dipole - a first-order multipole - it is necessary to add to the previous dipole the same dipole, mixed at some distance, and change the signs of the charges in it to the opposite. Let's do this as shown in figure 3, $a$: we move the dipole to the value of its length $l$. (Mixing can be done at a shorter distance. In this case, the calculations will be slightly longer.)

If the charges are multipole on the same axis, then the multipole is called axial. On figure 3, $b$ the axial quadrature resulting from the system of charges figure 3, $a$ is depicted, and on figure 3, $b$ the general case of quadratures - charges of equal magnitude and opposite signs are symmetrically located at the vertices of the parallelogram. Quadruple potential $\varphi_2$,

*) Due to the fact that $r \gg l$, the result does not change if the radius vector is drawn from a negative charge.

⟦folio 5⟧

Fig. 4.

according to formula (4), must be proportional to $1/r^3$. Consequently, in expansion (1) it is sufficient to take into account the terms of the sum only up to $x^2$.

Let us determine the coefficient of proportionality $C_2$ for the axial quadrapole depicted in figure 3, 6. The calculation will be performed for the remote point $D$ lying on the axis of the quadrapole:

$$\varphi_2 = \frac{q}{r} + \frac{(-2q)}{r-l} + \frac{q}{r-2l} \approx \frac{q}{r} \left[ 1 - 2 \left( 1 + \frac{l}{r} + \frac{l^2}{r^2} \right) + \left( 1 + \frac{2l}{r} + \frac{4l^2}{r^2} \right) \right] = \frac{2ql^2}{r^3}.$$

We now form a third-order multipole, generally called an octupole, since in the general case it includes 8 charges of equal magnitude. For this purpose, an additional quadrapole (Fig. 3, 6) is symmetrical with the axial quadrapole as shown in figure 4, $a$. In this case we obtain an axial octupole (Fig. 4, 6). In the general case, from the quadrapole (Fig. 3, 6) an octupole is obtained, shown in figure 4, $\theta$, the charges of which are located at the vertices of the parallelepiped. The electrostatic field potential of the octupole $\varphi_3$, according to formula (4), should be proportional to $1/r^4$. Let us determine the potential created by the field of the axial octupole at point $D$:

$$\varphi_3 = \frac{q}{r} + \frac{(-3q)}{r-l} + \frac{3q}{r-2l} + \frac{(-q)}{r-3l} \approx \frac{q}{r} \left[ 1 - 3 \left( 1 + \frac{l}{r} + \frac{l^2}{r^2} + \frac{l^3}{r^3} \right) + 3 \left( 1 + \frac{2l}{r} + \frac{4l^2}{r^2} + \frac{8l^3}{r^3} \right) - \left( 1 + \frac{3l}{r} + \frac{9l^2}{r^2} + \frac{27l^3}{r^3} \right) \right] = -\frac{6ql^3}{r^4}.$$

The fields of multipoles of higher orders are calculated in a similar way.

Far from any system of electric charges, the field of this system can be represented as the result of the addition of fields of multipoles of different orders. The higher the order of the multipole corresponding to the system of charges under consideration, the more neutral the system as a whole, and the faster the field decreases with distance from the charges.

We examined the potentials of electrostatic fields created by axial multipoles on their axis. The calculation of the potential at an arbitrary point in space is done in the same way, but the calculations become more cumbersome. If the type of multipole potential $\varphi_n = C_n/r^{n+1}$ is known, then the value of the electric field strength $E$, and therefore the force $F = qE$ acting from the multipole on the charge $q$ is uniquely determined (see § 76 in the textbook “Physics-9”). If $n \geq 0$ (which is true for any multipole), then

$$E \sim \frac{1}{r^{n+2}}.$$

Omitting mathematical details, let us consider the pictures of the force lines of the dipole and the axial quadrapole, presented in Figures 5, $a$ and 5, $\theta$. At figure 5, $a$ the dipole field is depicted. The total electric field strength $E$ at each point is obtained by geometrically adding the field of the positive charge $E_+$ with the field of the negative charge $E_-: E = E_+ + E_-$.

⟦folio 6⟧

Fig. 5.

On figure these vectors are shown at one of the points in space. A similar picture is shown in figure 5, b for the axial quadruple. At each point in space, the total field E is the result of the summation of three vectors: two directional vectors $E_+$ fields created by positive charges, and one directional vector $E_-$ fields created by a negative charge, the magnitude of which is equal to the sum of positive charges. A complete picture of the distribution of electric field lines in space for a dipole and a quadruple will be obtained if figure 5 is expressed around the corresponding symmetry axes.

In addition to electric ones, you can also consider magnetic multimoles - systems consisting of magnets or closed currents. The only difference is that individual magnetic charges have not yet been discovered, so the consideration must begin immediately with the magnetic dipole. At figure 5, in the induction lines of a magnetic dipole formed by a circular current $I$ are shown, the plane of which is perpendlular to the plane figure. At large distances from the dipole figure 5, a and 5, b have the same appearance.

The similarity of a magnetic dipole with an electric one can be illustrated with another example. The magnetic compass needle—a magnetic dipole—is oriented along the magnetic indication lines. An electric dipole behaves similarly in an electric field: it is also installed along the lines of force, that is, it is a kind of “electric compass” (Fig. 6).

Examples of electrical multimoles are atoms and molecules. If, during the formation of molecules as a result of the redistribution of electrons between atoms, the centers of distribution of positive and negative charges in it do not coincide, then the molecules have their own dipole moment and are called polar. The molecules of hydrochloric acid and water are polar (Fig. 7). If in molecules ULE the positive and negative charges are separated by a distance of the order of the radius of a hydrogen atom ($l = 0,5 \times 10^{-8} \text{ cm}$), then the dipole moment of the molecule should be of the order of $d = el^*$), that is, $d \approx 2,4 \cdot 10^{-18} \text{ cm} \times \text{ед. заряд} \text{ СГСЭ.}$. The order of magnitude of this is consistent with the experimental data given in figure 7. If the molecule consists of identical atoms ($O_2, H_2, Cl_2$), then the electrons, figuratively speaking, they “don’t know” which atom to choose and will be located in the ULE molecule more evenly, which leads to a zero value

*) Electron charge $e = 4,8 \cdot 10^{-10} \text{ ed. заряд} \text{ СГСЭ.}$

⟦folio 7⟧

Fig. 6.

changing the dipole moment of the molecule. Such molecules are called non-polar. figure 7 shows a linear carbon dioxide molecule, CO₂, which is nonpolar. Further, the “appearance” of this molecule is called on the object and the redistribution of electrons between atoms should form an axial quadrupole from it (compare with figure 3, 6), and the electric field created by the carbon dioxide molecule should have the form presented in figure 5, 6.

A more complex distribution of atoms and electrons in molecules leads to the formation of multipoles of calculated orders.

Application. Calculation of the electric field potential created by an exact charge

In the Physics-9 textbook, formulas for the field potential created by a precise charge are given without derivation (see formulas (8.28) and (8.29) on page 144). Let us present a simple derivation of these formulas for vykuma.

If the exact charge q is located at point O (Fig. 8), then the potential φ of the field created by it at point N at a distance r from charge q is equal to the work A that would be done by the electric field in moving a single positive charge from point N to an infinite point at which φ=0. Since the work of displacement does not depend on the shape of the trajectory along which the charge moves, we will assume that a single charge moves along the line of force.

Let's calculate how much this work already equals? To do this, we will divide the entire path traveled by a single positive charge into very small parts NN₁, N₁N₂, N₂N₃, etc. (see Fig. 8). In each of these sections, we calculate the work of moving a single charge. The sum of these works is equal to the field potential at point N with respect to infinity.

Let's calculate the work A₁ of moving a single charge from point N to point N₁, which is located at a very small distance from N (r₁−r). As shown in the textbook “Physics-9” (see formula (8.20)), in a uniform electric field, the directed work E to move a unit charge is numerically equal to

$$A = E(r₁−r).$$

The exact charge field is, of course, not uniform. Its directionality at point N is equal to E_N = q/r², and at point N₁E_N = q/r²!.

What value of E should we substitute into formula (1)? Obviously, it is necessary to take a field directionality value that would be the average between these two values. Since r and r₁ differ little from each other, then together r² and r₁² in the expressions for the direction of E_N and E_N₁ we can take the product rr₁, which is slightly greater than r²=rr, and slightly less than r₁²=r₁r₁. Then we can assume that throughout the entire section NN₁ the direction of the field is determined by the formula

$$E_{NN_1} = \frac{q}{rr_1}.$$

In this case, the work A₁ will be numerically equal

$$A_1 = \frac{q}{rr_1}(r_1−r),$$

or

$$A_1 = \frac{q}{r} - \frac{q}{r_1}.$$

In the same way, you can calculate the work of moving a single charge from point N₁ to
