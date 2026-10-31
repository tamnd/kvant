---
id: 1989-8-korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054
issue: kvant_1989_8
year: 1989
number: "8"
title: DC power
authors:
  - Коржуев А. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 69
page_last: 71
page_labels: 67-69
tag: HM4O
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8896905e3d2e8b8f6d7eb69ca7a5919a9cda6af3e0cf071eeeb1b5974e347f81
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/19_korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054.md
source_content_sha256: e134fd1086fe0cad2201e335dbcf4face093f343aed6216f6ef75df80f690a95
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 67⟧

DC power

A. V. KORZHUEV

Let us recall the basic principles that are used when solving problems involving the calculation of direct current circuits.

Let there be a simple (unbranched) closed circuit (Fig. 1), containing a current source with EMF and internal resistance $r$ and a resistor with resistance $R$ (it is also called external resistance). According to Ohm's law for such a circuit, current flows in it

$$I = \frac{\mathcal{E}}{R + r}.$$

In this case, the voltage on the external section of the circuit is equal to

$$U = \mathcal{E} - Ir,$$

the power released on the resistor is equal to

$$P_{\text{вн}} = IU,$$

and the total power of the source is

$$P_{\pi} = I\mathcal{E}.$$

Now let's look at a few specific problems that discuss, first of all, the issue of DC power.

Problem 1. An electric circuit contains a source with emf $\mathcal{E}$ and internal resistance $r$, and rheostat resistance $R$ (see Fig. 1). Calculate the total power released by the source, the power supplied to its external circuit (net power), and the efficiency of the source. Validate the dependence of these quantities on external resistance.

According to Ohm's law, current flows through the circuit

$$I = \frac{\mathcal{E}}{R + r}.$$

The power released in the circuit section is

⟦folio 68⟧

Pi with voltage $U$ is equal to $P = IU$ by definition. In our case

$$P_{\text{BH}} = IU = I^2R = \frac{\mathcal{E}^2R}{(R+r)^2}.$$

The total power of the source is

$$P_{\pi} = I\mathcal{E} = \frac{\mathcal{E}^2}{R+r},$$

and its efficiency is

$$\eta = \frac{P_{\text{BH}}}{P_{\pi}} = \frac{R}{R+r} = \frac{1}{1+r/R}.$$

Let us now analyze the dependence of all found quantities on the external resistance $R$. It can be seen that with an increase in $R$ the total power will decrease, and the efficiency, on the contrary, will increase - with an increase in $R$ an increasingly larger share of the total power is allocated to the external section of the circuit (compared to the power allocated by the internal source). The situation is more complicated with the power released as a result. From the expression $P_{\text{BH}} = \mathcal{E}^2R/(R+r)^2$ it follows that $P_{\text{BH}} = 0$ at $R = 0$ (which is completely natural) and at $R \to \infty$. Obviously, there is a value $R$ at which the useful power is maximum. It is easy to find by continuing $P_{\text{BH}}$ through resistance $R$ and equating this derivative to zero:

$$P'_{\text{BH}} = \frac{\mathcal{E}^2(R+r)^2 - 2\mathcal{E}^2R(R+r)}{(R+r)^4} = 0,$$

where do we get it from

$$R = r$$

— $P_{\text{BH}}$ is maximum and equal to $\mathcal{E}^2/(4r)$, provided that external and internal resistance are equal. However, the efficiency is equal to

$$\eta = \frac{R}{R+R} = \frac{1}{2},$$

i.e., half of the total generated power is allocated to the internal resistance of the source. In turn, the efficiency is maximum and equal to 1 at $R \to \infty$, but $P_{\text{BH}}$ tends to zero. Thus, it was not possible to achieve simultaneous maximum and most efficient energy output in such a circuit. While we lose in terms of power, we gain in efficiency, and vice versa.

Graphs of the dependence of $P_{\text{BH}}$, $P_{\pi}$ and $\eta$ on external resistance $R$ are shown in figure 2. The graphs clearly confirm that at $R = 0$ all the power is released at the internal resistance of the source. At $R = r$ the power transferred to the external circuit is equal to half of the total generated power, and the efficiency is 1/2. As $R$ increases, the dependence graphs $P_{\pi}(R)$ and $P_{\text{BH}}(R)$ get closer and closer to each other, the power released at the internal resistance decreases. At $R \gg r$ almost all the generated power is released in the external circuit and the efficiency tends to 1.

Problem 2. Using the circuit shown in figure 1, flow 1. Assuming $\mathcal{E}$ and $r$ of the source are known, calculate the power released in the external circuit, the resulting total power and efficiency

⟦folio 69⟧

source. Analyze the dependence of these quantities on the current in the circuit.

It's obvious that

$$P_{\pi} = I \mathcal{E},$$

and $P_{\mathrm{bH}}$ will be found by subtracting from the total power the power allocated to the internal resistance of the source:

$$P_{\mathrm{bH}} = \mathcal{E} I - I^2 r.$$

Then the efficiency

$$\eta = \frac{P_{\mathrm{bH}}}{P_{\pi}} = \frac{\mathcal{E} I - I^2 r}{\mathcal{E} I} = 1 - \frac{I r}{\mathcal{E}}.$$

With increasing current $I$, the total power increases linearly (since $\mathcal{E} = \text{const}$), and the efficiency decreases - an increase in current can be achieved by reducing the external resistance, and therefore reducing the share of $P_{\mathrm{bH}}$ compared to the power released at the internal resistance. The dependence of $P_{\mathrm{bH}}$ on $I$ is quadratic. $P_{\mathrm{bH}}$ vanishes at $I = 0$ and at $I = \mathcal{E}/r$. This means that there is a certain current value at which the useful power is maximum. Having differentiated with respect to the current, we find

$$P'_{\mathrm{bH}} = \mathcal{E} - 2 I r = 0, \text{ если } I = \frac{\mathcal{E}}{2 r}.$$

Moreover, $P_{\mathrm{bH} \max} = \mathcal{E}^2/(4 r)$, which is consistent with task 1.

To visually illustrate the results obtained, let us construct graphs of the dependence of all found values ​​on the current (Fig. 3). As in the previous problem, maximum power corresponds to an efficiency value of 1/2; at the same $I = \mathcal{E}/r$ $P_{\mathrm{bH}} = 0$ (this is the case when the external resistance is 0) and $\eta = 0$.

Problem 3. It is known that over time a battery composed of gases

$$\frac{\mathcal{E}^2}{R + r} \quad \frac{\mathcal{E}^2}{R} \quad \frac{\mathcal{E}}{R + r}$$

Vanich elements, “sits down” (its emf drops). How does the total power and efficiency depend in the external circuit on the emf of the source $(\text{см. рис. 1})?$ Assume that the internal resistance $r$ of the source does not change.

As was already obtained in problem 1,

$$P_{\pi} = \frac{\mathcal{E}^2}{R + r}, \quad P_{\mathrm{bH}} = \frac{\mathcal{E}^2 R}{(R + r)^2},$$

$$\eta = \frac{R}{R + r}.$$

From these expressions it is clear that when $\mathcal{E}$ falls, both the total power and the power released into the external circuit decrease, both of them according to a quadratic law, and the efficiency remains unchanged until the source emf becomes equal to zero and the process of power release stops completely.

The corresponding graphs are shown in figure 4.

Problem 4. An electric motor, the armature winding resistance of which is equal to $R$, is powered by a constant voltage source $U$, while current $I$ (Fig. 5) flows through it. Calculate the power consumption, the power lost due to heating of the winding, and the efficiency of the motor. Analyze the dependence of the indicated values ​​on the current in the motor.

The motor takes power from the source

$$P_{\mathrm{ot}} = I U.$$

In this case, in accordance with the Joule-Lenz law, thermal power is expended to heat the winding

$$P_{\tau} = I^2 R.$$

The difference between these values
