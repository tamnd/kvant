---
id: 1987-10-mozhaev-kondensatoryi-s-izbyitochnyim-zaryadom-plastin-1495c99e
issue: kvant_1987_10
year: 1987
number: "10"
title: Capacitors with “excessive” plate charge
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 59
page_labels: 53-57
tag: GE4R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5ed3e67c7afaf328cc78039ae6668d551afb10148d34ee613d92798f8407eb2e
prompt_sha256: draft-1
translated_from: content/ru/1987/10/articles/19_mozhaev-kondensatoryi-s-izbyitochnyim-zaryadom-plastin-1495c99e.md
source_content_sha256: 4163259cb0278c8b29c053845ad7b05c086c36b22a61cbbe86cbd55a34336165
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

Capacitors with “excessive” plate charge

Candidate of Physical and Mathematical Sciences
V. V. MOZHAEV

Many characteristics of applicants' errors when solving electrostatic problems are due to a formal understanding of the relationship between potentials and charges of conductors. And these connections are varied. For example, there may be a potential difference between the conductors in the absence of charges on them or, conversely, with a zero potential difference, the conductors can be charged. A gap option is also possible - there are charges on the conductors and there is a potential difference between them.

The latter case refers to widespread combustion when two isolated conductors (there are no other conductors) are charged

We have charges of the same magnitude, but opposite in sign. In such a system, the potential difference $U$ that arises between the conductors is proportional to the charge $q$ on them:

$$U \sim q, \text{ или } q = CU,$$

(*)

where $C$ is a proportionality coefficient called the electrical capacitance of two conductors. As is known, $C$ depends only on the size and shape of the conductors, their relative position and dielectric permeability of the environment.

Once again emphasizing that the linear relationship between the potential difference and the charge on conductors is not universal. It is preserved only when there is no influence of other conductors and the charges on two given conductors are equal in magnitude and opposite in sign. In other words, when the forces of the electric field lines, leaving one conductor, are closed on another. A typical example of such a system is a capacitor. It appears to be two conductors,

⟦folio 54⟧

Fig. 1.

separated by a layer of dielectric, the thickness of which is small compared to the size of the conductors (capacitor plates).

Now let's place several specific tasks. All of them were offered at various times during the entrance exams to the Moscow Institute of Physics and Technology.

Problem 1. Two uncharged metal plates 2 and 3 are located inside a flat charged capacitor (Fig. 1, a). In the capacitor there is a uniform electric field with a strain $\vec{E}_0$. What is the potential difference between plates 2 and 3 if the distance between them is $d_2$?

In this problem, the first partial case is implemented, when the conductors are not charged, but a potential difference exists between them.

Plates 2 and 3 formally form a flat capacitor, but they are not insulated - next to them there are other plates, and even charged ones. Therefore, the correspondence, if the coefficient $C$ is understood between plates 2 and 3: there are no charges on these plates, and the potential difference between them is not zero.

Let's find this potential difference in two ways. First, we will not resort to the concept of capacitance, but will use only the definition of potential difference. By definition, the potential difference between plates 2 and 3 is numerically equal to the work of moving a unit pole charge from plate 2 to plate 3. In an external field $\vec{E}_0$, a redistribution of charges will occur on plates 2 and 3: the left surfaces of these plates are charged negatively, and the right ones are charged positively (as shown in figure 1, a). Obviously, the field between the plates remains equal to $\vec{E}_0$, and the surface charge density on them will be equal to $\sigma = \varepsilon_0 E_0$ (try to show this yourself using the principle of superposition and electric fields). Then the potential difference between the plates

$$\Delta \varphi_{23} = E_0 d_2,$$

where $d_2$ is the distance between the internal surfaces of the plates.

Now find this potential difference using the concept of capacitance. Our system of four plates will be equivalent to the system of three series-connected flat capacitors shown in figure 1, 6. Indeed, each of the plates 2 and 3 can be split into two parts, retaining its own charge on each of them, and since they (the two parts) are at the same potential, they can be short-circuited. Total system capacity

$$C_{14} = \frac{\varepsilon_0 S}{d_1 + d_2 + d_3},$$

where $S$ is the area of ​​each plate, and the total potential difference

$$U_{14} = E_0 (d_1 + d_2 + d_3).$$

Then charge

$$q = C_{14} U_{14} = E_0 \varepsilon_0 S.$$

In a series connection, the charges on the capacitors are equal, so the potential difference across capacitor 2-3 will be equal to

$$U_{23} = \frac{q}{C_{23}} = \frac{E_0 \varepsilon_0 S}{\varepsilon_0 S/d_2} = E_0 d_2.$$

Problem 2. Let us short-circuit plates 2 and 3 with a conductor, discussed in the previous problem, and find the appearance of charges on them.

It is obvious that if plates 2 and 3 are connected briefly, then the potential difference between them will become equal to zero, and charges of equal magnitude but opposite in sign will appear on the plates (Fig. 2, a). Thus, in this problem we consider the second partial case, when there are charges on the conductor, but there is no potential difference.

⟦folio 55⟧

Let's find the charge on plates 2 and 3 using the same two methods. Since the potential difference between the plates is zero, the electric field voltage in the gap 2-3 is also zero. And this field is the resulting field created by the capacitor and the charges on plates 2 and 3. Let there be charge - $q$ on plate 2, charge + $q$ on plate 3, and the field of the capacitor is $\vec{E}_0$, then the resulting field between plates 2 and 3 will be equal to $E_0 - q / (\varepsilon_0 S) = 0$. From this condition we find

$$q = \varepsilon_0 SE_0.$$

The equivalent circuit for this case is shown in Fig. 2, b. This is a system of two series connected capacitors. We find the charge on plate 2 by considering the capacitor formed by plates 1 and 2:

$$q = C_{12} U_{12} = \frac{\varepsilon_0 S}{d_1} E_0 d_1 = \varepsilon_0 SE_0.$$

In exactly the same way, you can get a charge on plate 3.

Task 3. On plate 1 there is a charge $q$, plate 2, located at a distance $d$ from plate 1, is not charged. What is the potential difference between these plates?

As you can see, in this case there are arbitrary charges on the conductors, and there is a potential difference between the conductors.

Again we will solve the problem in two ways. Under the influence of the field created by the charges of plate 1, a negative charge will be induced on the left side of plate 2, and on the right

⟦folio 56⟧

Then the potential difference between points $A$ and $B$

$$U_{AB} = \frac{q}{C_{06}} = \frac{q(C + C_0)}{C_0(2C + C_0)},$$

and the desired potential difference between plates 1 and 2 (in the equivalent circuit this is the direction between plates $1'$ and $2'$) will be equal to

$$U_{12} = \frac{q}{2C + C_0} \approx \frac{q}{2C} = \frac{qd}{2\varepsilon_0S}$$

(here we have neglected the magnitude of capacitance $C_0$ compared to capacitance $C$).

Task 4. In the circuit shown in figure 4 (the values ​​$C$, $R$, $\varepsilon$ are known), with the switch $K$ open, the charge of the left plate of the flat capacitor is zero. Determine the initial charge of the right plate of the capacitor if, after closing the switch on resistor $R$, the same amount of heat is released as in the case when the capacitor is initially not charged.

Unlike the previous problem, here a potential difference equal to $\varepsilon$ is additionally maintained between the plates.

Let us denote the initial charge on the right plate of the capacitor by $q_0$. We will assume that it is evenly distributed over the surfaces (both internal and external) of the plate. On the face of the charge $q_0$ leads to the fact that in the space between the plates there is a uniform electric field with the direction of the potential difference

$$E_0 = \frac{q_0}{2\varepsilon_0S},$$

where $S$ is the area of ​​the plate, and there is a potential difference between the plates

$$U_0 = E_0d = \frac{q_0d}{2\varepsilon_0S},$$

where $d$ is the distance between the plates.

Let $U_0 < \varepsilon$, then after closing the key the capacitor begins to recharge. On its right plate the charge will increase, and on the left plate a charge will appear in the opposite direction.
false sign, equal in magnitude to the additional charge on the right plate (but not the full charge on it!). In this case, the source will perform positive work, charging the capacitor plates. The plates will be recharged until the potential difference across the capacitor $U$ becomes equal to the emf of the source $\varepsilon$. Let a charge $q$ flow through the source during charging, then the conditions for equal voltage on the capacitor EMF of the batteries will have the form

$$\frac{q_0d}{2\varepsilon_0S} + \frac{q}{C} = \varepsilon.$$

Considering that $C = \varepsilon_0S/d$, we get

$$q = \varepsilon C + \frac{q_0}{2}.$$

Let us now find the amount of heat that will be released on the resistor $R$ during charging. The work done by the source was partly used to increase the energy of the electric field in the space between the capacitor plates, and partly to heat the resistor:

$$\varepsilon q = \Delta W + Q.$$

We will calculate the electric field energy through the volumetric electric field energy density equal to $\varepsilon_0E^2/2$. With the key $K$ open, this energy is equal to

$$W_0 = \frac{q_0^2}{8\varepsilon_0S^2} Sd = \frac{q_0^2d}{8\varepsilon_0S} = \frac{q_0^2}{8C}.$$

After charging the capacitor, the energy of the electric field between the plates will increase and become equal to

$$W = \frac{\varepsilon_0}{2} \left( \frac{q_0}{2\varepsilon_0S} + \frac{q}{Cd} \right)^2 Sd = \frac{q_0^2}{8C} + \frac{q_0q}{2C} + \frac{q^2}{2C}.$$

Increase in electric field energy

$$\Delta W = W - W_0 = \frac{q(q_0 + q)}{2C}.$$

Then the complete energy balance can be written as

$$\varepsilon q = \Delta W + Q = \frac{q(q_0 + q)}{2C} + Q,$$

from where we find the amount of heat released by the resistor:

$$Q = \varepsilon q - \frac{q(q_0 + q)}{2C}.$$

Substituting the expression for charge $q$ into this equation (from the condition of equality of the potential difference between

⟦folio 57⟧

plates of the emf source), we finally obtain

$$Q = \mathcal{E} \left( \mathcal{E} C - \frac{q_0}{2} \right) - \frac{(\mathcal{E} C - q_0/2)(\mathcal{E} C + q_0/2)}{2C} = \frac{C \mathcal{E}^2}{2} + q_0 \left( \frac{q_0}{8C} - \frac{\mathcal{E}}{2} \right).$$

As can be seen, the released amount of heat $Q$ will not depend on the initial charge $q_0$ on the right plate for two values ​​of $q_0$:

$$q_1 = 0 \text{ и } q_2 = 4C\mathcal{E}.$$

It should be emphasized that to calculate the energy of the electric field between the plates of the capacitor both before closing the switch $K$ and after closing, we could not use formulas for the energy of a charged capacitor, since in both cases there is an “excess” charge $q_0$ on the right plate.

The question arises: is it possible in this case to “construct” the electric field between the plates of the capacitor both before the closure of the switch $K$ and after the closure? We could not use formulas for the energy of a charged capacitor, since in both cases there is an “excess” charge $q_0$ on the right 塑性.

In the system depicted at figure 4 ($C, R, \mathcal{E} - \text{заданы}$), with the switch $K$ open, the plates of a flat capacitor are charged with one-dimensional charges, the sum of which is equal to $q_0$. Determine the initial charges of each plate if, after closing the switch, the same amount of heat is released on resistor $R$ as in the case when the capacitor is not charged at first.

4. Two capacitor plates $S$ connected by a conductor are located at a distance $d$ from each other (Fig. 6) in an external uniform electric field, the direction of which is $\vec{E}_0$. How much work must be done to slowly lick the plates to a distance $d/2$?

5. In the system depicted on figure 7, the radius of the internal conducting sphere is $R$, the external (also conducting) is 3$R$. The distance from the center of the system to the charge - $q$ is equal to 2$R$. Using the value $q, \mathcal{E}, R$, determine the charge on the inner sphere. The earth's potential is assumed to be zero.

Dear readers!

In the future, 1988, the magazine «Kvant», as before, will be distributed only by subscription. If you miss your annual subscription (deadline October 31, 1987), don't worry. You can subscribe to any issue starting from February no later than the first day of the pre-subscription month. Subscriptions are accepted at Soyuznechat agencies, post offices and post offices. The magazine index «Kvant» in the Soyuznechat catalog is 70465, one-zone number 40 kopecks.
