---
id: 1991-8-mozhaev-energiya-elektricheskogo-polya-0bf9c1bf
issue: kvant_1991_8
year: 1991
number: "8"
title: Electric field energy
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 60
page_last: 65
page_labels: 58-63
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0940e84e8522d27547d37c4f7df9488c60b09d4024f22a176093e9b170ebf7b6
prompt_sha256: draft-1
translated_from: content/ru/1991/08/articles/17_mozhaev-energiya-elektricheskogo-polya-0bf9c1bf.md
source_content_sha256: 6862f57844323253d362db07600a7481ff810ccda46515acf5bd79aec0001c38
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 58⟧

---
running_head:
folio:
---

Electric field energy
Candidate of Physical and Mathematical Sciences
V. MOZHAEV

When we say that a charged capacitor has energy, a number of questions arise: where does this energy come from? where is it concentrated? in what form? It is very easy to verify that the capacitor actually stores energy. If, for example, it is discharged through a resistor, the resistor will heat up. And, probably, everyone knows what enormous energy is released during a lightning discharge (in a giant cloud-to-ground capacitor).

To answer the questions posed above, let's consider several specific tasks.

Problem 1. There is an insulated spherical air capacitor with plate radii $R_1$ (inner plate) and $R_2$ (outer plate), and charge Q. Find the energy density of the electric field between the plates of the capacitor in the case when $R_2 - R_1 \ll R_1$.

Obviously, the energy stored in the capacitor does not depend on the charging method. Let's carry out charging, for example, in this way. We will transfer the charge from infinity in small portions and place it on the plates. First let's charge the inner sphere. Suppose that at some moment there is already a charge $q$ on it (we have already transferred it), and we will transfer the next portion of the charge $\Delta q$. In this case, we will do the work

$$\Delta A = \frac{1}{4\pi\varepsilon_0} \frac{q\Delta q}{R_1}.$$

This expression can be written immediately, knowing that the potential of a charged sphere is equal to $q/(4\pi\varepsilon_0 R_1)$. Or you can only use Coulomb’s law, write down an expression for work on an elementary section of the path and integrate this expression along the entire path of movement of our charge:

$$\Delta A = - \frac{1}{4\pi\varepsilon_0} \int_0^{R_1} \frac{q\Delta q}{r^2} dr = \frac{1}{4\pi\varepsilon_0} \frac{q\Delta q}{R_1}.$$

It is clear that the total work done to move the charge $Q$ to the inner sphere is equal to

$$A_1 = \int_0^Q \frac{1}{4\pi\varepsilon_0} \frac{q}{R_1} dq = \frac{Q^2}{8\pi\varepsilon_0 R_1}.$$

Now let's start charging the outer sphere. Let, to determine, there is a positive charge on the inner sphere, and a negative charge on the outer_FIELD, which at some moment will be equal to $-q$. In this case, when the next portion of charge is transferred, this charge will be in two fields: in the field, charge $+Q$ (on the inner sphere) and in the field, charge $-q$ (on the outer sphere). Therefore, the elementary work of transferring

⟦folio 59⟧

---
running_head:
folio:
---

$$\Delta A = -\frac{1}{4\pi \varepsilon_0} \frac{Q \Delta q}{R_2} + \frac{1}{4\pi \varepsilon_0} \frac{q \Delta q}{R_2},$$
and full work -
$$A_2 = -\frac{Q^2}{4\pi \varepsilon_0 R_2} + \frac{Q^2}{8\pi \varepsilon_0 R_2} = -\frac{Q^2}{8\pi \varepsilon_0 R_2}.$$

So, our capacitor is fully charged, and the energy stored in it
$$W = A_1 + A_2 = \frac{Q^2}{8\pi \varepsilon_0} \left( \frac{1}{R_1} - \frac{1}{R_2} \right).$$

All this energy is concentrated between the spherical plates of the capacitor in the form of electric field energy. Since $R_2 - R_1 \ll R_1$, the field can be considered homogeneous, and its directionality is equal
$$E = \frac{Q}{4\pi \varepsilon_0 R_1^2} = \frac{Q}{4\pi \varepsilon_0 R_2^2}.$$

Let us express the total energy of the electric field through directivity:
$$W = \frac{Q^2}{8\pi \varepsilon_0} \left( \frac{1}{R_1} - \frac{1}{R_2} \right) = \frac{Q^2}{8\pi \varepsilon_0} \frac{\Delta R}{R_1^2} = 2\pi \varepsilon_0 E^2 R_1^2 \Delta R.$$

To find the volumetric energy density $w$, we divide this expression by the volume $V = 4\pi R_1^2 \Delta R$ occupied by the field and obtain
$$w = \frac{W}{V} = \frac{\varepsilon_0 E^2}{2}.$$

We have considered the effects of a capacitor, and the resulting expression for the volumetric energy density, strictly speaking, corresponds to the case of an electric field in a vacuum. The problem is to correct our expression for a medium with dielectric content $\varepsilon \neq 1$. In this case, if we place the same charge on the spheres, then the work done by us will be $\varepsilon$ times less. The direction of the electric field will also decrease by $\varepsilon$ times, and the expression for the volumetric energy density will have the form
$$w = \frac{\varepsilon_0 E^2}{2}.$$

Note that the obtained result does not mean at all that the energy density after filling the capacitor with a dielectric (while maintaining charges) increased by $\varepsilon$ times. Just the opposite - the energy of the capacitor decreased by $\varepsilon$ times, since the field voltage decreased by $\varepsilon$ times and the product $\varepsilon E^2$ also decreased by $\varepsilon$ times. But if we maintained a constant potential difference between the plates of the capacitor, then after filling the capacitor with a dielectric, the field voltage would remain the same. and the energy of the capacitor would increase $\varepsilon$ times.

Problem 2. What minimum work must be done to place a charge $Q$, initially located at a large distance from it, into the center of an uncharged thin spherical shell (Fig. 1)? The radius of the inner surface of the shell is $R_1$, the outer surface is $R_2$. Consider two cases: the shell is isolated; the shell is grounded.

First of all, we note that the minimum work will be done if the charge is moved so slowly (quasi-static) that the release of heat when moving along the shell of induced charges can be neglected.

Now - the solution itself. From the energy messages it is clear that the work is equal to the energy difference of our system (charge and shell) in the final and initial states:

$$A = W_{\kappa} - W_{\mu}.$$

First, let's consider the case when the shell is not grounded (isolated). The electrical energy of the system is

⟦folio 60⟧

---
running_head:
folio:
---

in the initial state, when the charge $Q$ (to define positive) is located at a large distance from the shell, includes only the energy of the electric field charge $Q$:

$$W_H = W_Q.$$

The configuration of the electric field in the final state is depicted in figure 2. It can be seen that a spherical layer with radii $R_1$ and $R_2$ is cut out of the charge $Q$ field. Therefore, it is clear that the energy of the electric field in the final state will be equal to

$$W_K = W_Q - W_{R_1R_2},$$

where $W_{R_1R_2}$ is the energy of the electric field in the spherical layer with radii

$R_1$ and $R_2$. This energy can be calculated in what is called “any way” - the field energy density is known to us; all that remains is to sum it up (interpret it) over the entire volume of the spherical layer. We will use the expression obtained in Problem 1 for the field energy of a charged spherical capacitor:

$$W_{R_1R_2} = \frac{Q^2}{8\pi\varepsilon_0} \left( \frac{1}{R_1} - \frac{1}{R_2} \right).$$

So, the work done in the first case is equal to

$$A_I = W_K - W_H = \left( W_Q - W_{R_1R_2} \right) - W_Q = - W_{R_1R_2} = - \frac{Q^2}{8\pi\varepsilon_0} \left( \frac{1}{R_1} - \frac{1}{R_2} \right).$$

Let us now consider the case of a substituted shell. The field configuration when the charge $Q$ is in the center is shown in figure 3. In this case, a negative charge equal in magnitude to $Q$ is transferred to the shell. This charge will be located on the inner surface of the shell, and the field will be concentrated only inside a sphere of radius $R_1$. The work in this case will be equal to

$$A_{II} = W_K - W_H = \left( W_Q - W_{R_1} \right) - W_Q = - W_{R_1} = - \frac{Q^2}{8\pi\varepsilon_0 R_1}.$$

Of course, this result could be obtained immediately from the expression for $A_I$ by putting $R_2 \rightarrow \infty$ in it.

Problem 3. How much heat will be released on the resistance resistor?

Fig. 2.

Fig. 3.

Fig. 4.

⟦folio 61⟧

---
running_head:
folio:
---

television $R$ in the diagram shown in figure 4, after closing the key $K$? Before the switch is closed, there is a charge $q_1$ on the capacitor with capacity $C_1$, and a charge $q_2$ on the capacitor with capacity $C_2$.

According to the law of conservation of energy, the amount of heat released will be equal to the difference between the energies of the capacitors before closing the switch $K$ and after closing, i.e., the difference between the initial and final energies:

$$Q = W_{\text{н}} - W_{\text{к}}.$$

Before the key is closed, the total energy concentrated in the capacitors is equal to

$$W_{\text{н}} = \frac{q_1^2}{2C_1} + \frac{q_2^2}{2C_2}.$$

To find the energy of the capacitors after the switch is closed and a new stationary state is established, we must find new charges on the capacitors. Let the charge $q$ leave the capacitor with capacitance $C_1$, and the new charge on it becomes equal to $q_1 - q$. According to the law of conservation of total charge, a charge $q_2 + q$ will be established on the plates of a capacitor with a capacity of $C_2$. The condition for stopping the flow of charges will be the equality of directions on the capacitors:

$$\frac{q_1 - q}{C_1} = \frac{q_2 + q}{C_2}.$$

Solving this equation, we get

$$q = \frac{q_1 C_2 - q_2 C_1}{C_1 + C_2}.$$

Then the new charges on the capacitors will be equal

$$q'_1 = \frac{C_1}{C_1 + C_2} (q_1 + q_2)$$

And

$$q'_2 = \frac{C_2}{C_1 + C_2} (q_1 + q_2),$$

the new energy reserve in the capacitors will be

$$W_{\text{к}} = \frac{q_1^2}{2C_1} + \frac{q'_2^2}{2C_2} = \frac{(q_1 + q_2)^2}{2(C_1 + C_2)},$$

and the amount of heat released is

$$Q = W_{\text{н}} - W_{\text{к}} = \frac{(q_1 C_2 - q_2 C_1)^2}{2C_1 C_2 (C_1 + C_2)}.$$

As can be seen from the resulting expression, $Q$ does not depend on $R$. What is the role of resistance? It turns out that its magnitude affects the rate of energy dissipation (dissipation) - the smaller $R$, the more intense the heat release occurs, and the corresponding discharge time decreases.

Problem 4. What work needs to be done to leave another flat charged capacitor filled with a dielectric with dielectric content $\varepsilon$ (Fig. 5) in the gap of a flat air charged capacitor? Charges on capacitors $Q_1$ and $Q_2$, area of ​​each plate $S$, distance between plates $d_1$ and $d_2$ ($d_1 > d_2$).

To solve the problem, use the energy method. Obviously, the work of introducing a capacitor with charge $Q_2$ into a capacitor with charge $Q_1$ will be equal to the difference in the energies of the electric field of the capacitors in the final and initial positions:

$$A = W_{\text{к}} - W_{\text{н}}.$$

In the initial state, the capacitors are isolated from each other, and their total energy is equal to

$$W_{\text{н}} = \frac{q_1^2}{2C_1} + \frac{q_2^2}{2C_2} = \frac{Q_1^2 d_1}{2 \varepsilon_0 S} + \frac{Q_2^2 d_2}{2 \varepsilon_0 S}.$$

We find the energy of the electric field of the system in the final state using the expression obtained above for the energy density of the electric field. Distance between two volumes of homogeneous electric fields: volume

⟦folio 62⟧

---
running_head:
folio:
---

$V_2 = Sd_2$ capacitor with charge $Q_2$ and the total volume $V_1 = S(d_1 - d_2)$ of air gaps between the plates. The electron field voltage in the volume $V_1$ is determined by the surface charge density on the external plates: $E_1 = Q_1 / (\varepsilon_0 S)$. In the volume $V_2$ the direction of the electron field is determined by the total charge of the plates $Q_1 + Q_2$ and the dielectric constant $\varepsilon$ of the medium filling the internal capacitor: $E_2 = (Q_1 + Q_2) / (\varepsilon_0 S)$. The final energy of the electronic field of the system is

$$W_k = \frac{\varepsilon_0 E_1^2}{2} V_1 + \frac{\varepsilon_0 E_2^2}{2} V_2 = \frac{1}{2\varepsilon_0 S} \left( Q_1^2 (\varepsilon d_1 - \varepsilon d_2) + 2 Q_1 Q_2 d_2 + Q_2^2 d_2 \right).$$

The final work of introducing a capacitor with charge $Q_2$ into a capacitor with charge $Q_1$ is

$$A = W_k - W_h = \frac{Q_1 d_2}{2\varepsilon_0 S} (2Q_2 - (\varepsilon - 1) Q_1).$$

Let's analyze the resulting expression. It contains two terms - the first determines the part of the work that needs to be done to introduce an empty (air) capacitor ($\varepsilon = 1$), the second term characterizes the work of introducing a dielectric plate with a thickness of $d_2$ ($Q_2 = 0$). The sign in front of the first term depends on the product of charges: if $Q_1 Q_2 > 0$, then we do positive work, and, therefore, a pushing force acts on the capacitor with charges $Q_2$ and $\varepsilon = 1$; if $Q_1 Q_2 < 0$, then the capacitor is drawn in, and we do negative work. The sign in front of the second term is always negative—the dielectric plate is always drawn into the region occupied by the electron field. In general, the total work $A$ can be either positive, negative, or equal to zero.

Note that in solving this problem we neglected edge effects, i.e. we assumed that the entire electron field of charges on the capacitor plates was concentrated in a volume limited by the dimensions of the plates and was uniform. This approximation works better the smaller the distance between the plates in relation to the dimensions of the plates. It would seem that everything is normal and natural. However, a paradoxical situation arises: to calculate the quantitative indicator of effectiveness, we relied on the effectiveness itself. Indeed, the work done when one charging capacitor is introduced into another is due to the action of the force from the electronic field of the main (stationary) capacitor on the introduced capacitor. This force arises only due to the inhomogeneity of the field at the edge of a stationary capacitor, i.e., it is determined by the edge effect. And we neglected this effect. How so? In fact, there is no paradox - the forces are determined not by the magnitude of the field at the edge of the capacitor, but by the magnitude of the field as it moves away from the edge of the plates. In the case of a small distance between the plates of the capacitor compared to the size of the plates, the magnitude of the field outside the capacitor drops sharply, and only a small part of the field lines extends beyond the boundaries of the capacitor volume.

Problem 5. A flat air capacitor touches a surface liquid with dielectric constant $\varepsilon$ and density $\rho$. Find the height of the liquid rising in the condenser, using capillary

Fig. 6.

⟦folio 63⟧

---
running_head:
folio:
---

Phenomena, if a constant potential difference $U$ is maintained between its plates, and the distance between the plates $d$ (Fig. 6).

Let the liquid level between the plates of the capacitor after connecting the voltage source be set at a height of $h$. Any closed system strives to occupy a stable position in which it has a minimum of potential energy.

Let's write down the total energy of our system. It includes the energy of the electric field of the capacitor, the energy stored in the source, and the potential energy of the fluid in the gravity field. The energy $W_C$ of a capacitor partially filled with a dielectric liquid in our case is equal to

$$W_C = \frac{CU^2}{2} = \left( \frac{\varepsilon_0 S(L-h)}{dL} + \frac{\varepsilon_0 \varepsilon Sh}{dL} \right) \frac{U^2}{2} = \frac{\varepsilon_0 S(L+(\varepsilon-1)h)}{dL} \frac{U^2}{2}.$$

The energy $W_U$ of the voltage source can be written as the difference between some initial energy reserve $W_0$ (before connecting the capacitor) and the work done by the source to charge the capacitor:

$$W_U = W_0 - qU = W_0 - (CU)U = W_0 - 2W_C.$$

The potential energy of the lifting fluid is equal to

$$W_g = \frac{\rho g dh^2 S}{2L}.$$

Since the total energy $W$ of our system in a state of stable equilibrium is minimal, its derivative is equal to zero:

$$\frac{dW}{dh} = 0, - \frac{\varepsilon_0 S(\varepsilon-1)U^2}{2dL} + \frac{2\rho g dh S}{2L} = 0,$$

whence it follows that the desired height of liquid rise will be equal to

$$h = \frac{\varepsilon_0(\varepsilon-1)U^2}{2\rho g d^2}.$$

In the above solution, we did not take into account the energy losses in our system, and the question may arise: is the effect of these losses on the height of the liquid rising okay? We examined the statistical states of our system and our average states with the lowest energy. This is the state to which our system strives, and if there are losses in the system, then the voltage source will be forced to do additional work. And if the source is able to cover these losses, then the system will sooner or later reach a state of stable equilibrium with a minimum of potential energy.

Exercises

1. Calculate the electrostatic energy of a ball with radius $R$, whose mass $Q$ is uniformly distributed over its volume.
2. Charges $q_1 = q$, $q_2 = 2q$ are placed at the centers of two dielectric spheres distant from each other with radii $R_1 = R$, $R_2 = 12R$ and produced ε. Find the work required to swap these charges.
3. A flat-plate air capacitor is connected through a resistor to a battery with an emf (Fig. 7). A metal plate whose thickness is three times less than the distance between the capacitor plates is quickly placed in the space between the plates. During the introduction of the plate, the charge on the capacitor does not have time to change. How much heat will be released on resistor $R$ after inserting the plate? Capacity of an empty capacitor $C_0$.
