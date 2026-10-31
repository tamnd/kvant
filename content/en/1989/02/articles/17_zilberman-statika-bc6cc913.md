---
id: 1989-2-zilberman-statika-bc6cc913
issue: kvant_1989_2
year: 1989
number: "2"
title: Statics
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 67
page_labels: 62, 63, 65
tag: WM53
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6d8bcc919b6476978f11398e1d26ff04ce50231b60b920902617b20f0a1808ad
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/17_zilberman-statika-bc6cc913.md
source_content_sha256: d9a1de04010ffa06a935c5ec24551b00092d6b33719f7001f71cfed8c0a882c5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

Stapika

A. R. ZILBERMAN

In the problems of this section, the conditions of equilibrium of bodies are studied. Typically, these conditions are used to find forces in the system under study.

Let us recall the conditions for equilibrium of a body: the sum of the forces acting on the body from other bodies must be equal to zero and the sum of the moments of these forces relative to any point must also be zero.

Here the question may immediately arise: won’t we get as many equilibria as we want by equating the sum of moments of forces relative to different points to zero, i.e. won’t we get more equalities than unknowns? It turns out that there is no basis for infinity - for a system 丝, the sum of which is equal to zero (and we are dealing with this once again), the total moment is the same relative to any point, so there will be no “extra” equations.*)

First, let's look at a very simple problem.

Problem 1. A straight beam with a length of $L=1$ m and a mass of $M=200$ kg is suspended by its ends on a vertical tension three (Fig. 1). Find their tension if the center of gravity of the beam is at a distance of $L_1=0,3$ m from one of its ends.

It is clear that if the cables are intact, then the beam is in equilibrium. Let's write the equation for the force:

$$T_1 + T_2 - Mg = 0.$$ (1)

There are two unknown quantities - $T_1$ and $T_2$. This means we need one more equation. We get it by writing the equation for moments丝. Moments can be relative to any point - we choose this point so that the equation of the system of equations.

*) You can read more about this in the article “Equal acting force - how to find it?”, published in the 11-12 issue of the magazine last year.

⟦folio 63⟧

It is convenient to take it as a continuation of the line of action of one (and if possible, then several) of the unknown forces. In our case, you can take one of the ends of the beam - to the right, left:
$$MgL_1 - T_1L = 0.$$

Solving the system of equations (1) and (2), we obtain
$$T_1 = Mg(L - L_1)/L = 1,4 \cdot 10^3\text{H},$$
$$T_2 = MgL_1/L = 0,6 \cdot 10^3\text{H}.$$

Please note: instead of equation (1), one could take the equation of moments about the other end of the beam, then the answers could be written down immediately. Try to justify the possibility of such a choice of equation yourself.

And one more note: if the cables are stretched quite a bit, then the beam will practically remain horizontal, and, therefore, our solution remains valid. If so, then we generally have the right to avoid stretching the cables (that is, we can consider them inextensible). However, it happens that even very small deformations can lead to a significant redistribution of forces in the system, then the deformations can no longer be avoided. Such cases are not difficult to recognize; we will look at an example of such a system later.

Problem 2. The tilting part of the window (fragment) can be rotated around the horizontal axis O (Fig. 2). The fragma is covered and held horizontally by a tension rope, making an angle a with the vertical. The point of attachment of the rope is at a distance L from the axis, the center of gravity of the phragm is at a distance L₁. The mass of the phragm is M. Find the magnitude and direction of the reaction force in the axis.

The easiest way is to find the projections of the reaction forces Q₁ and Q₂. The following equalities hold for them:
$$Q_1 - Mg = 0, \quad Q_2 - T = 0.$$
It remains to find the cable T. Let us write the equation of moments about the O axis:
$$TL\cos\alpha - MgL_1\sin\alpha = 0,$$
where
$$T = Mg \frac{L_1tg\alpha}{L}.$$
Then
$$Q_1 = Mg, \quad Q_2 = Mg \frac{L_1tg\alpha}{L}.$$
Actually, we solved the problem - we found the project of the desired force Q. But its direction could be indicated from the very beginning: it should “look” at the point of intersection of the line of action of the forces $\vec{T}$ and $\vec{Mg}$ (Fig. 3). In fact, relative to this point, neither the force $\vec{T}$ nor the force $\vec{Mg}$ creates moments, which means that the remaining force $\vec{Q}$, if equal, should be directed there.

Please note that the reaction force in the axis is not directed along the phragm. This is due to the fact that the phragm has weight. For a weightless rod hinged at the ends, the forces in the axes will be directed along the rod (if no additional forces are applied to the rod, except for the forces in the axes).

Problem 3. A triangle with angles of 30° and 60° is made of light rigid rods fastened at the ends with hinges. A load of mass M=2 kg is suspended as shown in figure 4. Find the deformations of the rods. Cross-sectional area of ​​the rods S=0.5 cm², modulus of elasticity E=5 \cdot 10^6 \text{H/m}^2. Length of the large rod L=0.2 m. Avoid bending the rods.

⟦folio 65⟧

Equation of forces and moments:
$$T_1 + T_2 + T_3 = Mg,$$
$$Mg L_1 - T_2 \frac{L}{2} - T_3 L = 0.$$

Assuming the deformations to be elastic, we write:
$$T_1: T_2: T_3 = \Delta l_1: \Delta l_2: \Delta l_3.$$

The following equation complements the equilibrium conditions, which are clearly not sufficient to solve this problem (such systems are called static indefinite, meaning the need for additional equations). Now we have a system:
$$\begin{cases}
T_1 + T_2 + T_3 = Mg, \\
T_2 + 2T_3 = 2Mg \frac{L}{L}, \\
2T_2 = T_1 + T_3.
\end{cases}$$

From here is
$$T_1 = Mg \left( \frac{5}{6} - \frac{L_1}{L} \right) = \frac{8}{15} Mg,$$
$$T_2 = \frac{1}{3} Mg,$$
$$T_3 = Mg \left( \frac{L_1}{L} - \frac{1}{6} \right) = \frac{2}{15} Mg.$$

This is the example discussed above: if the cables are not stretchable, then it is enough to take the middle one a little longer - and the entire load will fall on the outer ones, and if it is a little shorter, the load on the right cable will disappear. It is clear that in this problem the tensile strength of the cables cannot be neglected. But even if we forgot about it, the task itself would fill us with a lack of equation.

The equations of statics are very convenient; maybe that is why their leeks will be used even where there is no balance (which means they cannot be used). For example, the problem of a magnitude that is traveling in a circle is widely known, and it is required to find the angle at which the magnitude must

wives to bend down so as not to fall (this problem is in many problems, including in the school problem - in the 1983 edition it is number 279). The answer given there is, of course, correct, but how to solve it correctly?

The following reasoning is usually given as a solution. The reaction force, the components of which are the normal reaction $N$ and the friction force $F_{tr}$, must be directed along the body so as to pass through the center of the gravity, otherwise the magnitude will be lost. It is clear that this reasoning is simply a restatement of the equation of moments about the center of mass. But there is no equilibrium, the sum of forces is not equal to zero, why do we end up with an equation of moments?

It turns out that in those cases when the body is at rest relative to a reference frame moving with acceleration (as in this case), the equation of moments can be written, but only relative to a single point - the center of mass. The rationale for this “recipe for preparing a solution” goes beyond the scope of the school curriculum (but is relevant to the section “Non-inertial reference systems”). Let us forgive the authors of the puzzles where this and similar problems are placed for an innocent desire - now we know how to act in such cases.

Exercises
1. The rigid system consists of identical light rods fastened with a hinge (Fig. 9). Find the tension in rods 1, 2, 3 and 4. Do these rods shrink or grow?
2. The stepladder consists of two halves, fastened at the top with a hinge (Fig. 10). The mass of one half is $M_1$, the other is $M_2$. The stepladder is opened to an angle $\alpha$ and placed on the floor, and to prevent it from “spreading around”, the lower ends of the half-ladders are tied together with a screw. Find the tension in the rope. The floor is smooth.
