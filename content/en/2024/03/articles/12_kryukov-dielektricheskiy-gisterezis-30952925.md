---
id: 2024-3-kryukov-dielektricheskiy-gisterezis-30952925
issue: kvant_2024_3
year: 2024
number: "3"
title: Dielectric hysteresis
authors:
  - Крюков П. А.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 55
page_last: 57
page_labels: 53, 55
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2e5c8208becf6c54cf4e606c51e6f29b3e647b5045c0af1093a6dcdd70d3f383
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/12_kryukov-dielektricheskiy-gisterezis-30952925.md
source_content_sha256: 6cf59cb1775f9cf4aaabf25c2103be4cf72df4841d4e3133d8b218a9313e6b34
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 53⟧

Dielectric hysteresis

Below are the conditions and solutions to problem 5 for grade 11 (round I) of the 84th Moscow Olympiad for schoolchildren in physics (see «Kvant» No. 5 for 2023).

Condition

In a flat nonlinear capacitor, the space between the plates is filled with a nonlinear dielectric, so the dependence of the capacitor charge on the voltage between the plates can be more complex than in the linear case, for which $q = CU$. When the voltage changes cyclically, the dependence $q(U)$ for a nonlinear capacitor has the form of a hysteresis loop.

a. To study the properties of the nonlinear capacitor $C$, we assembled the circuit shown in figure 1. The capacitance of the typical (linear) reference capacitor $C_0$ satisfies

Fig. 1

8. In space there are segments $AA_1$, $BB_1$ and $CC_1$ with a common middle $M$. It turned out that the sphere $\omega$, described near the tetradra $MA_1B_1C_1$, touches the plane $ABC$ at the point $D$. Point $O$ is the center of the circle circumscribed about triangle $ABC$. Prove that $MO = MD$.

A. Kuznetsov

9. See problem M2788 “Problem book «Kvant»”.
10. See problem M2789 “Problem book «Kvant»”.
The publication was prepared by N. Agakhanov, I. Bogdanov, P. Kozhevnikov, A. Kuznetsov, O. Podlinsky, K. Sukhov

Dielectric hysteresis

Below are the conditions and solutions to problem 5 for grade 11 (round I) of the 84th Moscow Olympiad for schoolchildren in physics (see «Kvant» No. 5 for 2023).

Condition

In a flat nonlinear capacitor, the space between the plates is filled with a nonlinear dielectric, so the dependence of the capacitor charge on the voltage between the plates can be more complex than in the linear case, for which $q = CU$. When the voltage changes cyclically, the dependence $q(U)$ for a nonlinear capacitor has the form of a hysteresis loop.

a. To study the properties of the nonlinear capacitor $C$, we assembled the circuit shown in figure 1. The capacitance of the typical (linear) reference capacitor $C_0$ satisfies

Fig. 2

⟦folio none⟧

---
running_head:
folio:
---

states corresponding to points α, β, γ
on the chart. Find the direction of the field in the dielectric in the α and γ states. Options
nonlinear capacitor $S$ and $d$, capacitance $C_0$
reference capacitor, as well as the parameters of the loop $a, b, u$ indicated on the graph
are considered famous. The electric constant is $\varepsilon_0$.

b. Another nonlinear capacitor will be connected in series with a resistor of resistance $R$ to a rectangular pulse generator with a frequency $n$, the direction between the terminals of which during the polyvin period periode is equal to $U_0$, and during the second polyvin periode is equal to $-U_0$. In the established mode, the charge of one of the plates of the capacitor $q$, depending on the direction between the plates $U$, changes as shown in the graph at figure 3. The parameters of the hysteresis loop, designated

Fig. 3

shown on the graph are equal to $U_1 = 0,1U_0$, $U_2 = 0,25U_0$, $q_1 = 2CU_1$, $q_2 = q_1 + 0,1CU_0$. The values ​​of $U_0$ and $C$ are known, with $nRC \ll 1$. Find the average power consumed by the circuit from the generator over the period and the average power released by the resistor. Express your answers using parameters $C, U_0, n$.

Solution

a. First, consider point $\gamma$ of the graph of dependence $U_y(U_x)$. Fair ratios are:

$$100u = \frac{q^{(\gamma)}}{C_0}, u = \frac{R_2}{R_1 + R_2}\left(E^{(\gamma)}d + 100u\right),$$

where $q^{(\gamma)} - заряд эталонного конденсатора, $E^{(\gamma)} is the direction of the field in the dielectric plate at a given moment. The following inequality follows from the condition:

$$\frac{100R_2}{R_1 + R_2} \ll 1,$$

The postural ratio for $u$ can be written as follows:

$$u = \frac{R_2}{R_1 + R_2}E^{(\gamma)}d.$$

Thus, the direction $U_x = 100u$ at point $\gamma$ is proportional to the charge $q^{(\gamma)}$ of the reference capacitor, and therefore (since the charges of the capacitors are equal), and to the charge of the nonlinear capacitor. the direction of $U_y = u$ at point $\gamma$ is proportional to the direction on the nonlinear capacitor. From here we get the exclusive directionality:

$$E^{(\gamma)} = \frac{C_0u}{S\varepsilon_0}.$$

The surface density of fielding charges can be found from the relation

$$\frac{q^{(\gamma)}}{S\varepsilon_0} - \frac{\left|\sigma_{\pi}^{(\gamma)}\right|}{\varepsilon_0} = E^{(\gamma)}.$$

Let us substitute expressions for charge and field direction into this relationship, and after several transformations we obtain the exclusive surface density:

$$\left|\sigma_{\pi}^{(\gamma)}\right| = \frac{100C_0u}{S} - \frac{C_0u}{S} = \frac{99C_0u}{S}.$$

Now consider the point $\beta$. It is easy to see that the sum of the directions on the nonlinear and common capacitors in the state corresponding to this point on the graph is equal to zero. This fact is reflected by the equation

$$\left(\frac{C_0b}{S\varepsilon_0} - \frac{\left|\sigma_{\pi}^{(\beta)}\right|}{\varepsilon_0}\right)d - b = 0,$$

since the charge of the nonlinear capacitor in this case is equal to $C_0b$ (up to sign). The following inequality follows from the condition:

$$\frac{C_0d}{S\varepsilon_0} \gg 1,$$

Therefore, neglecting the last term in the equations, we obtain the elimination of the surface.

⟦folio 55⟧

---
running_head:
folio:
---

new density:
$$\left| \sigma_{\pi}^{(\beta)} \right| = \frac{C_0 b}{S}.$$
Finally, consider the state of the dielectric corresponding to the point $\alpha$. The charges of the capacitors in this state are obviously zero, therefore the field strength in the dielectric is created only by polarization charges, therefore, the equality is true
$$\frac{\left| \sigma_{\pi}^{(\alpha)} \right|}{\varepsilon_0} d \frac{R_2}{R_1 + R_2} = a.$$
Using the correspondence for resistance given in the conditions, we get the answers:
$$\left| \sigma_{\pi}^{(\alpha)} \right| = \frac{C_0 a}{S}, \quad E^{(\alpha)} = \frac{C_0 a}{S \varepsilon_0}.$$
b. The strong inequality $nRC \ll 1$, given in the conditions, indicates that the time during which the charges are established on the capacitor plates is significantly less than the period of voltage oscillations.
Let at some instant of time the voltage at the terminals of the generator and at the capacitor be equal to $-U_0$. When the polarity of the voltage at the terminals of the generator changes, the latter moves the charge $Q = 2CU_0$, performing work $A^{(1/2)} = 2CU_0^2$. When the polarity is reversed at the terminals of the generator, it does the same work to move the charge. Thus, during the period the generator does work
$$A = 2A^{(1/2)} = 4CU_0^2,$$
therefore, the average power consumed by the target from the generator is
$$P = 4CU_0^2 n.$$
Note that if the dependence of the capacitor charge on the voltage across it was linear ($q = CU$), then all the power consumed by the target from the generator would be released in the form of heat on the resistor. In the case of a nonlinear capacitor, part of the work performed by the generator is spent on “repolarization of the dielectric.” When the charge of a nonlinear capacitor increases from the value $-CU_0$ to the value $CU_0$, the electric forces perform work
$$A_{\text{эл}}^{(1/2)} = \int U dq.$$
Numerically, this work is equal to the area of ​​half of the loop located to the right of the ordinat axis. Obviously, the work of electrical forces to recharge the capacitor over a period is equal to the area of ​​the loop:
$$A_{\text{эл}} = 2A_{\text{эл}}^{(1/2)}$$
This is the energy loss due to repolarization of the dielectric. From the law of conservation of energy it follows that the amount of heat released on the resistor per period
$$Q = A - A_{\text{эл}}.$$
The definition of $A_{\text{эл}}$, as already mentioned, is evidence for calculating the area of ​​the loop of the steresis, which can be found in different ways. Here's the final answer:
$$A_{\text{эл}} = 0,2CU_0^2.$$
Therefore, the power released by the resistor is equal to
$$P_R = 3,8CU_0^2 n.$$
P. Kryukov
