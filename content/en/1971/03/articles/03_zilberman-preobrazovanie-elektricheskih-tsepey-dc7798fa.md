---
id: 1971-3-zilberman-preobrazovanie-elektricheskih-tsepey-dc7798fa
issue: kvant_1971_3
year: 1971
number: "3"
title: Conversion of electrical circuits
authors:
  - Зильберман А. Р.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10, 12, 13, 14
tag: K0OM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 627b063829c40b1ad75f01f74b222ddbc4b7084fe52792f0f6438d45206ac809
prompt_sha256: draft-1
translated_from: content/ru/1971/03/articles/03_zilberman-preobrazovanie-elektricheskih-tsepey-dc7798fa.md
source_content_sha256: 01dd688f3b4cbb2dfd583e5ea40e2e64724b417dc5de9699fb38bc71c261e9a0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

This article describes a method that allows you to simplify complex problems in calculating electrical circuits.

What do we mean by “chain conversion”? Let's assume that we have a complex circuit of resistances that has many pins and connections to sources. Let's replace this circuit with another one, with the same number of terminals, and so that the resistance between any two terminals of the new circuit is the same as that of the old one. It is clear that the sources "will not know anything" about this replacement, and the points consumed by the circuit will remain the same. But finding these points may be easier.

Therefore, if we want to count currents in a complex circuit, it can be replaced by a simpler equivalent circuit. In this case, the currents inside the replaced part change. Therefore, we can do this only with that part of the scheme that does not directly interest us.

You have already encountered similar substitutions.

Let, for example, in the circuit two resistances $r_1$ and $r_2$ are connected in series, we can replace them with one, equal in value to the sum $r_1 + r_2$. If two resistances are connected in parallel, then they can also be replaced with one, the value of which is $R = \frac{r_1 r_2}{r_1 + r_2}$

These are the simplest examples of circuit conversion. We will focus on more complex schemes.

Let's see how circuits that have three terminals each are converted into each other - “star” (Fig. 1, a) and “triangle” (Fig. 1, b).

The slightly unusual designations (Fig. 1, b) are very convenient, the index showed between which points the resistance is connected. For example, resistance $R_{13}$ is connected between points 1 and 3, etc.

If we want to replace one of these circuits with another, we need to obtain such correspondences between $r$ and $R$ that the resistances between any points are the same for both circuits.

In the “star” circuit (Fig. 1, a) the resistor

⟦folio 12⟧

Fig. 4.

"triangle" ACD "star" as shown in Fig. 4.

Now it is clear that the resistance between points A and B will be equal to
$$\frac{1}{3} + \frac{28}{33} = \frac{13}{11} \text{ ома}.$$

We replaced the “triangle” ACD with a “star”, but it was possible to solve the problem differently - replacing the “star” ADB with a “triangle”.

Let now a battery with negligible small internal resistance and e.m. be connected to points A and B. With. E=1 in. We need to find the current through section CB.

The circuit must be transformed so that the resistance CB of interest to us is not affected. The transformation we did earlier (Fig. 4) will do.

Using that $R_{AB} = \frac{13}{11} \text{ ома}$ we get $I = \frac{E}{R_{AB}} = \frac{11}{13} a$. After branching, the points are added in the ratio inverse to the resistances of the branches:

$$\frac{I_1}{I_2} = \frac{7}{4}.$$

At the same time $I_1 + I_2 = I$. (I is the current before the branching, $I_1$ is the current in the upper branch, $I_2$ is the current in the lower branch).

From here

$$I_1 = \frac{7}{13} a$$

It would be a little more difficult to find the current flowing through the CD section. To do this we would still have to find a current,

⟦folio 13⟧

Fig. 6.

potentiometer. Moreover, the sum of resistance $5r+R_1$ and $7r+R_2$ remains constant. Let's see what they should be so that the total resistance is maximum. We denote $5r+R_1$ by $r_1$ and $7r+R_2$ by $r_2$. Then the total resistance of the parts of the circuit connected in parallel is $r_0 = \frac{r_1 r_2}{r_1 + r_2}$. If we take into account that $r_1+r_2 = const = c$, then the resistance $r_0$ will be expressed as follows: $\frac{r_1 (c-r_1)}{c}$. This expression is maximum when the number of slipels is maximum. But $y = (cr_1-r_1^2)$ is the equation of a parabola (Fig. 7), the branches of which intersect the x-axis at points $O$ and $c$. Therefore, the numerical fraction is greatest at $r_1 = \frac{c}{2}$. Since $r_1+r_2 = c$, this means that the resistance between points $A$ and $B$ is maximum if $r_1=r_2$, that is $5r+R_1=7r+R_2$, or $R_1-R_2=2r$.

It is clear that this is only possible if the resistance of the entire potentiometer $R=R_1+R_2$ is not less than $2r$. Otherwise, the maximum resistance between points $A$ and $B$ is achieved when the potentiometer slider is in its extreme position.

So the answer is: $R \leq 2r$.

The method we have described is very convenient for sequentially transforming a complex diagram into a simple form. It allows you to calculate practically any complex target consisting of resistances.

This method can be applied to circuits containing more than just resistances.

Please note that we did not talk anywhere about physical processes in the circuit, but only used the formal expression for Ohm’s law: $U=r \cdot I$. It follows from it that when connected in series, their values ​​are added, and when connected in parallel, the values ​​reciprocal to resistance $\left(\frac{1}{r_{06\pi}} = \frac{1}{r_1} + \frac{1}{r_2}\right)$ are added. It is clear that if any other physical quantities are related by a law similar to Ohm’s law, then all our conclusions are valid for them.

As an example, consider a circuit with a capacitor (Fig. 8). We know that $Q=C \cdot U$, or $U = \frac{1}{C} Q$.

⟦folio 14⟧

Fig. 9.

Let's compare this with the expression for Ohm's law $U=r \cdot I$.

It can be seen that the laws of positivity, only then together there is a charge, and together with resistance there are quantities, the inverse capacitance. This means that in order to find, say, charges on capacitors, you can do this. Instead of a circuit containing capacitors, draw a target containing resistances, and replace the capacitor with a capacitance of $x$ farads with a resistance $r = \frac{1}{x} \text{ om}$. After we calculate the current in a circuit of resistances, we can immediately write what the charges are on the capacitors: if a current of $I=y$ amers flows through the resistance, then the corresponding capacitor will have a charge of $Q=y$ coulombs.

E.m.f. The batteries remain unchanged during this transformation. But, of course, in a circuit with capacitors, the internal resistance of the batteries does not affect the result. Therefore, the goal changes, we will have to deprive the batteries of their internal resistances.

Let, for example, you need to find the charge on a capacitor with capacity $10 \text{ мкф}$ (Fig. 9). To the capacitor
