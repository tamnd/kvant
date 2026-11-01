---
id: 1986-9-zilberman-tsepi-peremennogo-toka-8b1ebe6e
issue: kvant_1986_9
year: 1986
number: "9"
title: AC circuits
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 57
page_labels: 51-55
tag: 6GOK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 07cd7c985d974783ec9fa261d1cdc6fcb8f66e173e7ca9c045c6868935a59170
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/18_zilberman-tsepi-peremennogo-toka-8b1ebe6e.md
source_content_sha256: e69aa97dcb39fc22e1c8a02046b60b7709115575d7f457bc67c551fdf1d31819
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

AC circuits

A. R. ZILBERMAN

Alternating current (or voltage) represents forced electrical fluctuations. The magnitude of the current changes with time according to the harmonic law

$$i = I_m \cos(\omega t + \varphi_0),$$

where $I_m$ is the amplitude, $\omega$ is the steep (cyclic) frequency (it is measured in radians per second, and is simply written $c^{-1}$), $\varphi_0$ is the initial phase of the vibration. A similar forcing can be written for alternating voltage.

Example. Let's write down the time dependence of the network voltage: 220 V, 50 Hz. In this case, the amplitude $U_m = U \sqrt{2} = 220 \sqrt{2}$ V≈311 V (recall that $U = 220$ V is the effective voltage value), steep frequency $\omega = 2\pi v \approx 6,28 \cdot 50 \text{ c}^{-1} \approx 314 \text{ c}^{-1}$. Let us also know that at the moment the report began ($t=0$) the voltage was equal to $u_0 = 50$ V and was decreasing. Then we can find the initial phase $\varphi_0$:

$$u_0 = U_m \cos \varphi_0,$$

where $\varphi_0 = \arccos \frac{u_0}{U_m} \approx 1,4$ glad

(think for yourself - where did we teach the decrease in tension). So,

$$u = 311 \cos (314t + 1,4).$$

It can be seen that the appropriate choice of the beginning of the time report - and this is in our power - can be made $\varphi_0$ anything, in particular zero. This is often used and written down without special reservations

$$u = U_m \cos \omega t.$$

The calculation of alternating current circuits usually comes down to determining the currents at a given source voltage. It is quite easy to calculate currents in circuits containing only resistors. At any point in such a circuit, the current changes “in time” with

⟦folio 52⟧

Fig. 1.

applied direction, that is, there is no phase shift between current and direction. The situation is more complicated if the circuit contains energy storage devices - coils and capacitors. In this case, the moments of maximum directions and currents may not coincide - corresponding phase shifts appear. It is known, for example, that when a coil is connected to the network, the current maxima lag behind the direction maxima by a quarter of a period (phase shift π/2), and when a capacitor is connected, on the contrary, they are ahead by a quarter of a period.

When calculating in DC circuits, you can simply add the direction values ​​on series-connected elements and the current values ​​on branched sections of the circuit. In the case of alternating current, everything is more complicated - the amplitude of the sum is not always equal to the sum of the amplitudes. For example, the amplitude of the sum of two currents of 1 A each can be anything - from 0 to 2 A, you need to designate it taking into account the phase shifts. To calculate AC circuits, a convenient graphical method is often used - the vector diagram method. It is based on a simple idea.

Let the vector $\vec{A}_0$ (length $A_0$) rotate the entire circle of one of its ends counterclockwise with an angular velocity $\omega$. Then the projection of the second end onto the axis $X$, the beginning of which is at the center of rotation (Fig. 1), is equal to $x = A_0 \cos (\omega t + \varphi_0)$.

That is, we get exactly the function that interests us. (Actually speaking, the circular part is denoted by the same letter as the corner part

Fig. 2.

speed, we have this model in mind.) On the same figure we can depict another vector $\vec{A}_1$, corresponding to another function with amplitude $A_1$ and initial phase $\varphi_1$. At $\varphi_1 > \varphi_0$, the vector $\vec{A}_1$ “leads” the vector $\vec{A}_0$ by an angle $\Delta \varphi = \varphi_1 - \varphi_0$. It is important that $A_0$ and $A_1$ can have different dimensions (for example, $A_0$ can vary in volts, and $A_1$ in amperes).

Now about the method itself. What is a "vector diagram"? This is a drawing that depicts in the form of vectors (on a newly selected scale and taking into account phase shifts) the directions and currents of the circuit under study. In the case of harmonic oscillations we are considering (in other cases this is not true!) all these vectors rotate in one direction with the same angular velocity $\omega$, and the angles between them remain constant, so we don’t have to talk about rotation and paint a “stationary” picture. If a drawing has been constructed, the problem has already been solved, because it contains all the necessary information about the directions and currents of the circuit’s interrelations. The method of constructing vector diagrams is the way to obtain such drawings.

Let's look at a few specific examples.

Task 1. figure 2 shows a simple electrical circuit containing a capacitor and resistor connected in series. The amplitude of the current in the circuit is $I_m = 0,1$ A. Find the amplitudes of the direction of the source and the phases between this direction and the current in the circuit.

Let us choose appropriate scales for depicting currents and directions. Let's draw arbitrarily (in the way that is convenient for us!) the vector $\vec{I}_m$ (Fig. 3). Now we can draw the vector $\vec{U}_{Rm}$, depicted by the direction on the resistor (we will depict it in a different color so as not to confuse the direction vectors and the

⟦folio 53⟧

kov). Its module
$$U_{Rm} = I_m R = 50 \text{ В}.$$
In direction, vector $\vec{U}_{Rm}$ coincides with vector $\vec{I}_m$ (after all, the phase shift between the current and the direction of the resistor is zero). The direction vector on the capacitor $\vec{U}_{Cm}$ is equal in magnitude to $U_{Cm} = I_m X_C = 100 \text{ В}$, where $X_C = 1 / (\omega C) = 1 \text{ кОм} - \text{емкостьное сопротивление},$ and lags $\pi/2$ in phase from the current. Let's draw this vector too. The voltage at source $\vec{U}_m$ corresponds to the sum of vectors $\vec{U}_{Rm}$ and $\vec{U}_{Cm}$:
$$U_m = \sqrt{U_{Rm}^2 + U_{Cm}^2} \approx 112 \text{ В}.$$
Note that we have already found (drawn!) the angle between the current $\vec{I}_m$ and the direction of the entire circuit $\vec{U}_m$. This angle can simply be changed with a transor or calculated trigonometrically:
$$\text{tg} \varphi = \frac{U_{Cm}}{U_{Rm}} = 2,$$
$$\varphi = \arctg 2 \approx 1,1 \text{ рад} \approx 64^\circ.$$
This problem can be formulated a little differently: set the amplitude of the direction of the source, for example $U'_m = 220 \text{ В}$, and find the amplitude of the current in the circuit. This task is more difficult - after all, we must find a diagram to draw without knowing the amplitude of the current $I'_m$. There are two possibilities here. The first is to solve the auxiliary problem of finding the amplitude of the direction $U_m$ for a given current $I_m$ (we just discussed such a problem), and then write down a very similar correspondence
$$\frac{U'_m}{U_m} = \frac{I'_m}{I_m}$$
and find the current amplitude $I'_m$ from it:
$$I'_m = I_m \frac{U'_m}{U_m} \approx 0,18 \text{ А}.$$
The second possibility is to draw the diagram not on a specific numerical scale, but in a general way. In this case, the ratios of the lengths of the residual vectors are the same, which means that the angles between them do not change. The formula obtained from the diagram
$$U'_m = \sqrt{(U'_{Rm})^2 + (U'_{Cm})^2} = \sqrt{(I'_m R)^2 + (I'_m X_C)^2}$$
we use $I'_m$ to find:
$$I'_m = \frac{U'_m}{\sqrt{R^2 + X_C^2}} \approx 0,18 \text{ А}.$$
These methods are approximately equal in complexity.

Fig. 4.
Problem 2. Two directional branches are connected to a source of alternating direction. The current amplitude in the first is $I_{1m} = 1 \text{ А}$, in the second $I_{2m} = 0,3 \text{ А}$. Within what limits can the amplitude of the current flowing through the source be? What can be the maximum phase shift between the current and the current in the first branch?

The solution is clear from figure 4, which shows a vector diagram for this circuit (vector $\vec{I}_{2m}$ is drawn so that it is more convenient to add it with vector $\vec{I}_{1m}$):
$$I_{1m} - I_{2m} \leq I_m \leq I_{1m} + I_{2m},$$
$$0,7 \text{ А} \leq I_m \leq 1,3 \text{ А}.$$
The maximum angle between $\vec{I}_m$ and $\vec{I}_{1m}$ corresponds to:
$$\sin \varphi_{\max} = \frac{I_{2m}}{I_{1m}} = 0,3,$$
$$\varphi_{\max} \approx 0,31 \text{ рад} \approx 18^\circ.$$
At the same time $I_m = \sqrt{I_{1m}^2 - I_{2m}^2} \approx 0,95 \text{ А}$. The angle between $\vec{I}_m$ and $\vec{I}_{2m}$ can be any (from - $\pi$ to +$\pi$).

Problem 3. In the circuit shown in figure 5, find the current flowing through the source and over the phases between this current and the direction of the source.

Let's start drawing a diagram by asking the current to flow through the coil. Let's put, for example, $I_{Lm} = 0,1 \text{ А}$. Then the direction on the coil $\vec{U}_{Lm}$ is equal in magnitude to $U_{Lm} = I_{Lm} X_L = 100 \text{ В}$, where $X_L = \omega L = 1 \text{ кОм} - \text{индуктивное сопротивление},$ determines the current $\vec{I}_{Lm}$ in phase

Fig. 5.

⟦folio 54⟧

by π/2 (Fig. 6). The current through a resistor with resistance $R_2$ is determined by this voltage and is in phase with it:

$$I_{R_2m} = \frac{U_{Lm}}{R_2} = 0,05 \text{ A}.$$

Then the total current

$$I_m = \sqrt{I_{Lm}^2 + I_{R_2m}^2} \approx 0,112 \text{ A}.$$

The voltage $\vec{U}_{R_1m}$ across a resistor with resistance $R_1$ is in phase with this current:

$$U_{R_1m} = I_m R_1 \approx 112 \text{ B}.$$

Then we find the total voltage $\vec{U}_m$ (the sum of the vectors $\vec{U}_{R_1m}$ and $\vec{U}_{Lm}$). After simple calculations (this can also be done graphically, if you carefully build a diagram!) we get

$$U_m \approx 180 \text{ B}, \quad \varphi \approx 0,52 \text{ рад} \approx 30^\circ.$$

Now you can refine the scale and find the total current in the circuit at a given source voltage:

$$I'_m = I_m \frac{U'_m}{U_m} \approx 0,112 \frac{200}{180} \text{ A} \approx 0,124 \text{ A}.$$

All other currents and voltages will also increase by $U'_m / U_m \approx 1,1$ times, while the phase values ​​remain the same.

Reactive elements - coils, capacitors - are often used to obtain a certain phase dwga between voltage and current in a circuit. Let's look at a specific example.

Problem 4. An AC electric motor contains two identical windings (the inductance of each phase between the voltage and current in the circuit. Let's look at a specific example.

Problem 4. An AC electric motor contains two identical windings (the inductance of each phase between the voltage and current in the circuit. Let's look at a specific example.

When switched on ($U = 220 \text{ B}, \nu = 50 \Gamma_u$), one of the windings is connected to the network directly, and the other is connected through a series connection with a capacitor of capacitance $C$ and a resistor of resistance $R$. Calculate the required quantities $C$ and $R$. Pogerami in the windings of claims.

The current in the coil, which is directly connected to the network, lags in phase by π/2 from the network voltage. Its module

$$I_1 = \frac{U}{X_L} = \frac{U}{2\pi vL} \approx 0,7 \text{ A}.$$

Note that we have found the rms value of the current because the set value $U$ is rms. It is clear that vector diagrams can be constructed for both amplitude and effective values ​​- as long as one diagram contains either amplitudes or effective values.

Let's construct a vector diagram for the sequential circuit $RCL$ (Fig. 7). We will draw everything in general form. Let's draw the vector $\vec{I}_2$ corresponding to the current in the circuit. Voltage $\vec{U}_R$ ($U_R = I_2R$) is in phase with the current, $\vec{U}_C$ ($U_C = I_2X_C$) is behind by π/2, $\vec{U}_L$ ($U_L = I_2X_L$) is ahead by π/2. The total voltage $\vec{U}$ must be in phase with the current $\vec{I}_2$, while the currents $\vec{I}_1$ and $\vec{I}_2$ will be out of phase by π/2.

From the diagram it can be seen that this requires that

$$X_C = X_L, \frac{1}{\omega C} = \omega L,$$

$$C = \frac{1}{\omega^2 L} = 10^{-5} \Phi = 10 \text{ мкФ}.$$

At the same time $I_2 = I_1 = U/R$, from where

$$R = \frac{U}{I_1} \approx 314 \text{ Om}.$$

Note that the calculation of such a circuit in a real case is much more complicated, since the phase dws between the voltage and current in the windings of a loaded diggator are not equal to π/2, as in an ideal coil, but depend on the voltage on the diggator shaft.

Energy calculations in AC circuits are complicated by the fact that

⟦folio 55⟧

THAT INSTANTANEOUS POWER CHANGES OVER TIME. We may be interested in both the average power value - to calculate the work of the source or the heat generated in the circuit, and the maximum value of INSTANTANEOUS POWER.

Problem 5. The voltage amplitude of the source $U_m$, the amplitude of the current flowing through it $I_m$, from the phases between the voltage and current f. Determine the work of the source over a long period of time $T$ and the maximum value of INSTANTANEOUS POWER.

Let's write down the expression for INSTANTANEOUS power and bring it to a more convenient form:
$$p = ui = U_m I_m \cos \omega t \cos (\omega t + \varphi) = \frac{1}{2} U_m I_m \cos (2\omega t + \varphi) + \frac{1}{2} U_m I_m \cos \varphi.$$
The average value of the first term over a large (much longer period of oscillation) period of time is zero. Then the average power
$$\bar{P} = \frac{1}{2} U_m I_m \cos \varphi$$
and source work
$$A = \bar{P} T = \frac{1}{2} U_m I_m T \cos \varphi.$$
The maximum value of the first term in absolute value is $1/2 U_m I_m$ and
$$P_m = \frac{1}{2} U_m I_m (1 + |\cos \varphi|).$$
It can be seen that at $|\varphi| \approx \pi/2$ the maximum power can be many times higher than the average. This is due to the fact that the electrical circuit, when it heats up energy, then releases it back to the source. This mode is very bad for powering the network - heat output losses increase. An example of such a circuit is a fluorescent lamp. Its current is limited by a coil with high inductance, and the phases are switched

Fig. 8.

Fig. 9.

close to $\pi/2$. The output is simple - connect a capacitor in parallel to the circuit. If you choose its capacitance correctly (think about it), then the coil and capacitor will exchange energy with each other, and only useful power will be optimal from the network.

Task 6. The effective value of the network voltage in the evening hours can range from 220 to 190 V. To maintain the power of the boiler at the receiver level, it is recommended to turn on the resulting DC voltage source in series with it. What should its voltage $U_n$ be at the minimum network voltage?

The voltage applied to the boiler is
$$u_k = U_{2m} \cos \omega t + U_n,$$
where $U_{2m} = 190 \sqrt{2} \text{ В}$ is the lowest amplitude value of the network voltage. The phase shift between the voltage on the boiler and the current is zero (boiler - resistor). Then the average power
$$\bar{P} = \frac{u_k^2}{R} = \frac{U_{2m}^2}{2R},$$
where $U_{1m} = 220 \sqrt{2} \text{ В}$. But
$$u_k^2 = U_{2m}^2 \cos^2 \omega t + U_n^2 + 2U_n \cdot U_{2m} \cos \omega t = \frac{U_{2m}^2}{2} + U_n^2.$$
From here
$$U_n = \sqrt{\frac{U_{1m}^2}{2} - \frac{U_{2m}^2}{2}} \approx 110 \text{ В}.$$
Exercises
1. The diagram depicted in figure 8 is called the “Win ​​bridge”. At what part of the phase shift between the output and input voltages is zero? How many times is the output voltage on this part less than the input voltage?
2. Prove that in the circuit shown in figure 9, at frequency $\omega = 1/\sqrt{LC}$, the current through the resistor does not depend on its resistance. Find this current.
