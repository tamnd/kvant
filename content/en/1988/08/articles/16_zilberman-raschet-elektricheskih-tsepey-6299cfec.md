---
id: 1988-8-zilberman-raschet-elektricheskih-tsepey-6299cfec
issue: kvant_1988_8
year: 1988
number: "8"
title: Calculation of electrical circuits
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 60
page_last: 62
page_labels: 58-60
tag: 7XZX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 484775dc47c312539df3fbc5cc39ecc3a0614bf81acfa48101dd772b761733f2
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/16_zilberman-raschet-elektricheskih-tsepey-6299cfec.md
source_content_sha256: 2fe1f02fb1079800ad1d2b1f17e48b204ddb2cbf9041a510badfc81b2a87475d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 58⟧

Calculation of electrical circuits

A. R. ZILBERMAN

There are many ways to calculate electrical circuits consisting of batteries and resistors. Almost any of them (with a simple variable notation) is also suitable for circuits of batteries and capacitors. (And if you are confident with complete numbers, then you can also calculate any circuits for alternating current.) This article will examine two simple ways to calculate direct current circuits with resistors and capacitors.

The first method is suitable for relatively simple circuits. Let us be given a circuit consisting of a battery and several resistors. For calculations in the circuit branches, we first systematically simplify the circuit, then parallel or series connected resistors with their equivalents. After simplifying the circuit to such an extent that the currents in it are easy to find, we carry out the reverse process, finding the currents of the original elements. This method is well known to you since the gray-haired grade.

Let's look at a few examples.

Problem 1. In the circuit shown in figure 1, find the current flowing through the jumper AB.

Let's simplify the circuit by replacing parallel connecting resistors 1 and 3, as well as 2 and 4 with their equivalents. The result is a simple circuit with a common resistance

$$R = \frac{R_1 R_3}{R_1 + R_3} + \frac{R_2 R_4}{R_2 + R_4}$$

and total current

$$I = \frac{U}{R} = \frac{U}{R_1 R_3 + R_2 R_4}.$$

The voltage across resistors 1 and 3 are equal, which means $I_1:I_3 = R_3:R_1$. But $I_1 + I_3 = I$. Then

⟦folio 59⟧

$$I_1 = I \frac{R_3}{R_1 + R_3}, \quad I_3 = I \frac{R_1}{R_1 + R_3}.$$
Likewise
$$I_2 = I \frac{R_4}{R_2 + R_4}, \quad I_4 = I \frac{R_2}{R_2 + R_4}.$$
Now let’s find the current through the jumper $AB$:
$$I_{AB} = I_1 - I_2 = \frac{U(R_2R_3 - R_1R_4)}{R_1R_3(R_2 + R_4) + R_2R_4(R_1 + R_3)}.$$
From the resulting expression it is clear that under the condition $R_1:R_2=R_3:R_4$ the current through the jumper is zero. This is often used to accurately measure unknown resistance.
The considered method, although simple, is very cumbersome. In addition, it is not universal - not every scheme can be simplified this way. For example, if you replace the jumper on figure 1 with a resistor, the resulting circuit contains neither parallel nor series connecting resistors.
The second, more convenient, method of calculation is based on a reasonable choice of unknowns for the equations subsequently compiled.
Consider an unbranched section of the circuit containing a resistor and a current source (Fig. 2). According to the law of conservation of energy, the current in this section is equal to
$$I = \frac{\varphi_A - \varphi_B - \mathcal{E}}{R + r},$$
from which it is clear that to find the currents in each of the branches it is enough to know the potentials at its ends (more precisely, the potential differences). The connection points of unbranched sections of a chain are called nodes, hence the name of the method - the method of nodal potentials.
So, as unknown quantities we choose the potentials of the circuit nodes. It is convenient to set the potential of one of them - any - equal

![Puc. 1.](Puc. 1.)

![Puc. 2.](Puc. 2.)

![Puc. 3.](Puc. 3.)

![Puc. 4.](Puc. 4.)

Zero (then the potentials of the remaining nodes are the voltages changed relative to the node we selected). The equations for determining nodal potentials are written for currents that are in the current and flowing from them: the sum of currents flowing into a node is equal to the sum of currents flowing out. If there are $N$ nodes in the circuit, then there are one less unknown potentials (recall that we set the potential of one of the nodes ourselves). This means that we need to write equations for the currents of all nodes except one. (If we nevertheless write equations for all nodes, we will quickly see that one of them - any one! - is superfluous; it can be obtained by combining the remaining equations.)

Let's look at this problem as an example.
Task 2. Find the current through voltage $R$ connected to a parallel connecting battery with emf $\mathcal{E}_1$ and $\mathcal{E}_2$ and internal resistances $r_1$ and $r_2$ (Fig. 3).
Let's redraw the diagram as shown in figure 4, and set $\varphi_A = 0$. Now it is enough to set the potential of point $B$ to express all the currents in the circuit. For node $B$:
$$\frac{\mathcal{E}_1 - \varphi_B}{r_1} + \frac{\mathcal{E}_2 - \varphi_B}{r_2} = \frac{\varphi_B}{R},$$
where does the potential of point $B$ come from?
$$\varphi_B = \frac{\mathcal{E}_1/r_1 + \mathcal{E}_2/r_2}{1/r_1 + 1/r_2 + 1/R},$$
and voltage current
$$I = \frac{\varphi_B}{R} = \frac{\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1}{R(r_1 + r_2) + r_1 r_2}.$$

Sometimes the question in the problem is formulated differently: is it possible to replace parallel connecting batteries ($\mathcal{E}_1$, $r_1$ and $\mathcal{E}_2$, $r_2$) with an equivalent battery and what should they be (if

⟦folio 60⟧

can it be replaced!) its EMF and internal resistance? To answer these questions, you need to try the expression obtained for the voltage current, bring it to the form

$$I = \frac{\mathcal{E}_{\text{экв}}}{R + r_{\text{экв}}}.$$

If it works, then this will be the answer to both questions. In our case, everything is simple:

$$I = \frac{(\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1) / (r_1 + r_2)}{R + r_1 r_2 / (r_1 + r_2)},$$

$$\mathcal{E}_{\text{экв}} = \frac{\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1}{r_1 + r_2}, \quad r_{\text{экв}} = \frac{r_1 r_2}{r_1 + r_2}.$$

(Note that any system of batteries and resistors connected to an external circuit by two wires can be replaced by an equivalent battery. Proof of this point is beyond the scope of the school curriculum.)

Let us now solve a more complex problem.

Problem 3. In the circuit shown in figure 5, find the resistance between points A and B.

The easiest way to think is this: connect a battery with a given voltage U to these points, find the current through the battery and calculate the total resistance using the formula $R = U/I$. Let's draw the resulting diagram (Fig. 6) and put $\varphi_A = 0$. Then the potential of point B is known: $\varphi_B = U$. Let us denote the potential of point C by $\varphi_1$, of point D by $\varphi_2$. Let's write two equations for node C:

$$-(U - \varphi) C_1 + \varphi C_2 + \varphi C_3 = 0,$$

from where $\varphi = \frac{C_1 U}{C_1 + C_2 + C_3}.$
