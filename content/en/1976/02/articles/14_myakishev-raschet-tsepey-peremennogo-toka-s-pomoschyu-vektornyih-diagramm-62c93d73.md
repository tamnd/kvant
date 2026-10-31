---
id: 1976-2-myakishev-raschet-tsepey-peremennogo-toka-s-pomoschyu-vektornyih-diagramm-62c93d73
issue: kvant_1976_2
year: 1976
number: "2"
title: Calculation of AC circuits using vector diagrams
authors:
  - Мякишев Г. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 59
page_labels: 51-57
tag: RTRZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 934f6151b14456ef4dbd003f7880cce9aef2d5d9feccf80a29c8207767acbc19
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/14_myakishev-raschet-tsepey-peremennogo-toka-s-pomoschyu-vektornyih-diagramm-62c93d73.md
source_content_sha256: ff831a5601b2086788ce7356b79dadf27b93a119884b30fe609019f9194c7b24
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

G. Myakishchev

Calculation of AC circuits is much more complex than that of DC circuits. However, if the direction and strength of the current changes according to a harmonic law, there is a fairly simple and visual method for calculating circuits - the vector diagram method. We want to introduce the reader to him in this article.

Equation describing forced oscillations in an oscillatory circuit

Industrial alternating current is forced electromagnetic oscillations. If the direction $u = u(t)$ at the ends of the chain changes according to the harmonic law
$$u = U_0 \cos \omega t,$$
(1)
then the current strength $i$ also changes harmonically with the same frequency $\omega$, but in the general case the current is out of phase with respect to the direction by a constant value $\varphi$:
$$i = I_0 \cos (\omega t + \varphi).$$
(2)

However, at the first moment after the circuit is closed, the current oscillations have a much more complex shape. When closed, the electrical circuit seems to receive a “push”, and if it has its own oscillation frequency $\omega_0$, then free electromagnetic oscillations arise in it. These oscillations are superimposed on forced oscillations of frequency $\omega$, but gradually attenuate due to the presence of active resistance $R$ in the circuit (at which energy is released in the form of heat). Only after free oscillations have died out can forced oscillations be considered established. The current amplitude $I_0$ in formula (2) is the amplitude of the established mechanical oscillations (for more details on this, see, for example, the article by G. Ya. Myakishchev “Forced mechanical oscillations”, «Kvant», 1974, No. 11).

A rather simple, but very important special case is forced oscillations in a circuit consisting of a series-connected conductor with active resistance $R$, an inductor $L$ and a capacitor $C$ (Fig. 1). Such a circuit is called a series oscillatory circuit. Let the direction $u$ at the ends of the chain change according to the law described by equation (1); then the current strength $i$ in the circuit changes in accordance with expression (2). What is the current amplitude $I_0$ and the phase shift $\varphi$?

As is known, the equation describing forced current oscillations in this circuit has the following form:
$$L \frac{\Delta i}{\Delta t} + Ri + \frac{q}{C} = U_0 \cos \omega t.$$ (3)
Here $q$ is the charge of the capacitor. (This

⟦folio 52⟧

The equation is similar to the equation describing forced mechanical vibrations, for example, external vibration of a load.)

Equation (3) can be used as follows. At any moment in time, the total voltage ($u = U_0 \cos \omega t$) at the ends of the circuit is equal to the sum of the voltages across the active resistance ($u_R = Ri$), across the inductor ($u_L = L \frac{\Delta i}{\Delta t}$) and across the capacitor ($u_C = \frac{q}{C}$):

$$u_L + u_R + u_C = u.$$ (4)

All three voltages oscillate at the same frequency, but have different amplitudes and are out of phase with each other.

To find the amplitude of the oscillations in current strength and the phase shift between current and voltage, you need to be able to add harmonic oscillations that are out of phase. To do this, you need to know the voltage amplitudes $u_R$, $u_L$ and $u_C$, as well as the phase shift of these voltages relative to the current strength. This will be discussed in the next three paragraphs.

Voltage across active resistance

The simplest case of an electrical circuit is one containing only active resistance $R$. For such a chain, the basic equation (3) will have the following form:

$$Ri = U_0 \cos \omega t.$$ (5)

From here

$$i = \frac{U_0}{R} \cos \omega t = I_0 \cos \omega t.$$ (6)

The voltage amplitude is related to the current amplitude by correspondence

$$U_0 = I_0 R.$$ (7)

Fluctuations in current and voltage across active resistance are in phase. Note that equality (7) is no different from Ohm’s law for direct current.

Voltage across inductive reactance

Let the target consist of a coil with inductance $L$. We neglect the active resistance of the coil. Instead of equation (3), in this case we will have a simpler equation

$$L \frac{\Delta i}{\Delta t} = U_0 \cos \omega t,$$

or

$$\frac{\Delta i}{\Delta t} = \frac{U_0}{L} \cos \omega t.$$ (8)

Now the rate of change of current ($\frac{\Delta i}{\Delta t}$) performs harmonic oscillations, coinciding in phase with voltage oscillations. The amplitude of these oscillations is $\frac{U_0}{L}$.

In order to express the current strength, use the analogy between electromagnetic oscillations in the circuit and mechanical oscillations of the load externally. As is known, the current strength $i$ corresponds to the speed of oscillations of the load $v$, and the rate of change of the current strength $\frac{\Delta i}{\Delta t}$ corresponds to the acceleration of the load $a$. But the velocity fluctuations lag behind the acceleration fluctuations by $\pi/2$, and the velocity amplitude $v_0$ is related to the acceleration amplitude $a_0$ by the correspondence $v_0 = a_0/\omega$. This is true for harmonic vibrations of any nature. Therefore, if the rate of change of current satisfies equation (8), then the current changes with time according to the law

$$i = \frac{U_0}{L \omega} \cos \left(\omega t - \frac{\pi}{2}\right) = I_0 \cos \left(\omega t - \frac{\pi}{2}\right).$$ (9)

The voltage amplitude is related to the current amplitude by correspondence

$$U_0 = I_0 L \omega = I_0 R_L.$$ (10)

The quantity $R_L = L \omega$ is called inductive reactance.

⟦folio 53⟧

So, in accordance with expressions (1) and (9), the power of the current on the inductive reactance lags behind the voltage in phase by π/2.

Capacitor voltage

Let's consider a circuit consisting of a capacitor em bone C. We claim the active resistance and inductance of the circuit. Forced oscillations in this circuit will be described by the equation

$$\frac{q}{C} = U_0 \cos \omega t. \tag{11}$$

The capacitor charge oscillates in phase with the voltage, and the amplitude of these oscillations is $U_0 C$:

$$q = U_0 C \cos \omega t. \tag{12}$$

In the case of electromagnetic oscillations, the charge corresponds to the coordinate of the body performing mechanical oscillations, and the current strength, which is the rate of change of charge ($i = \frac{\Delta q}{\Delta t}$), is similar to the speed of this body. Since for any harmonic oscillations the amplitude of the velocity of the quantity is $\omega$ times greater than the amplitude of the quantity itself and the speed is out of phase with the quantities by π/2, then in our case

$$i = \frac{\Delta q}{\Delta t} = U_0 C \cos \left( \omega t + \frac{\pi}{2} \right) = I_0 \cos \left( \omega t + \frac{\pi}{2} \right). \tag{13}$$

Therefore, the power of the circuit is determined by the voltage on the capacitor by π/2, or, what is the same, the voltage from the circuit breaker by π/2.

The voltage amplitude is

$$U_0 = \frac{I_0}{C \omega} = I_0 R_C, \tag{14}$$

where $R_C = \frac{1}{C \omega}$ is the resistance of the capacitor, called capacitance.

Addition of harmonic oscillations using vector diagrams

Harmonic oscillations can be added in different ways (analytical, graphic, etc.). However, in the partial case when the oscillation frequencies are the same, it is most convenient to use the vector diagram method. What does this method consist of?

From the 10th grade physics course it is known that the projection onto any direction of a vector rotating with a constant angular velocity $\omega$ performs a harmonic oscillation. If the model of the vector $x_0$ is equal to $x_0$, then its projection onto the axis $OX$ is equal to $x = x_0 \cos \varphi$ (Fig. 2). With uniform rotation of the vector $x_0$, the angle $\varphi$ changes with time according to the law

$$\varphi = \omega t + \varphi_0,$$

where $\varphi_0$ is the value of angle $\varphi$ at the initial time $t=0$. Consequently, the projection of the rotating vector oscillates according to the law

$$x = x_0 \cos \left( \omega t + \varphi_0 \right). \tag{15}$$

Fig. 2.

Fig. 3.

⟦folio 54⟧

Let us now consider the addition of two harmonic oscillations occurring with the same frequencies $\omega$, but with different amplitudes $x_{0_1}$ and $x_{0_2}$ and different initial phases $\varphi_{0_1}$ and $\varphi_{0_2}$:

$$x_1 = x_{0_1} \cos(\omega t + \varphi_{0_1}),$$
$$x_2 = x_{0_2} \cos(\omega t + \varphi_{0_2}).$$

The added oscillations at any moment of time have a phase difference $\varphi = \varphi_{0_1} - \varphi_{0_2}$. These oscillations can be represented as oscillations of the projections of the vectors $x_{0_1}$ and $x_{0_2}$, rotated relative to each other by an angle $\varphi$ and rotating with an angular velocity $\omega$ (Fig. 3).

Adding the vectors $x_{0_1}$ and $x_{0_2}$, we obtain the total vector $x_0 = x_{0_1} + x_{0_2}$. The projection $x$ of this vector onto the direction $OX$ also performs a harmonic oscillation. But the projection of the total vector is equal to the sum of the projections of the added vectors. Hence,

$$x = x_1 + x_2 = x_0 \cos(\omega t + \varphi_0),$$

(16) where $x_0$ is the amplitude, and $\varphi_0$ is the initial phase of the resulting oscillation. The quantities $x_0$ and $\varphi_0$ can be found by knowing $x_{0_1}, x_{0_2}, \varphi_{0_1}$ and $\varphi_{0_2}$. It is easy to show (see Fig. 3) that

$$x_0^2 = x_{0_1}^2 + x_{0_2}^2 + 2x_{0_1}x_{0_2} \cos(\varphi_{0_1} - \varphi_{0_2}),$$
$$tg \varphi_0 = \frac{x_{0_1} \sin \varphi_{0_1} + x_{0_2} \sin \varphi_{0_2}}{x_{0_1} \cos \varphi_{0_1} + x_{0_2} \cos \varphi_{0_2}}.$$

So, each harmonic oscillation can be represented using a vector rotating at a constant angular velocity, and the sum of the harmonic

Fig. 4.

ical oscillations - using the resulting (total) vector rotating at the same speed. A graphical representation using the values ​​of harmonic changing quantities and the correspondences between them is called a vector diagram.

Vector diagram of a series oscillatory circuit

Let's return again to the circuit shown in figure 1 and construct a vector diagram of currents and voltages for it. This allows us to determine the amplitude of the current in the circuit and cdwg phases between the current strength and the applied voltage.

The current strength at a given time is the same in all parts of the circuit*). Therefore, it is convenient to construct a vector diagram on a basis with the vector $I_0$ corresponding to the current strength. It can be oriented arbitrarily. For orientation, we depict the vector $I_0$ with a vertical arrow (Fig. 4).

The voltage across the active resistance is in phase with the current. Therefore, the vector $U_{0R}$, represented by this voltage, coincides in direction with the vector $I_0$. Its module is $U_{0R} = I_0R$. The voltage fluctuations across the inductive reactance determine the current fluctuations at $\pi/2$, and the corresponding vector $U_{0L}$ must be the surface of the vector $I_0$ at $\pi/2**$. Its module is $U_{0L} = I_0L\omega$. And finally, the vector $U_{0C}$, corresponding to the voltage on the capacitor,

*) The current that satisfies this condition is called quasi-stationary. At an industrial current frequency of 50 $2\pi$, it can practically always be considered quasi-stationary.
**) A positive phase cdwg at Fig. 4 corresponds to a rotation of the vector against the parts of the arrow. It was, of course, possible to measure the angle $\varphi$ in the opposite direction.

⟦folio 55⟧

lags in phase from the vector $I_0$ by $\pi/2$ (see Fig. 4). Its module is $U_{0C} = I_0/C\omega$.

In order to find the total voltage (see equation (4)), you need to add three vectors: $U_{0R}$, $U_{0L}$ and $U_{0C}$. First, it is convenient to add the vectors $U_{0L}$ and $U_{0C}$ (Fig. 5). The modulus of this sum is $|U_{0L} + U_{0C}| = I_0\left(L\omega - \frac{1}{C\omega}\right)$,

if $L\omega > \frac{1}{C\omega}$. It is precisely this case that is depicted in Fig. 5. After this, adding the vector $U_{0L} + U_{0C}$ with the vector $U_{0R}$, we obtain the vector $U_0$, depicting voltage fluctuations at the ends of the circuit.

Triangle ABD is right-angled. According to the Pythagorean theorem

$$U_0^2 = U_{0R}^2 + \left(U_{0L} - U_{0C}\right)^2 = I_0^2 R^2 + I_0^2 \left(L\omega - \frac{1}{C\omega}\right)^2.$$

Hence the current amplitude

$$I_0 = \frac{U_0}{\sqrt{R^2 + \left(L\omega - \frac{1}{C\omega}\right)^2}} = \frac{U_0}{Z},$$

where $Z = \sqrt{R^2 + \left(L\omega - \frac{1}{C\omega}\right)^2}$ is the total resistance of the circuit. The phase shift between current and voltage is equal to the angle $\varphi$ between vectors $U_0$ and $I_0$. From triangle ABD

$$tg\varphi = \frac{L\omega - \frac{1}{C\omega}}{R}.$$

figure 5 depicts the case when the current strength lags in phase with the voltage (at $L\omega < \frac{1}{C\omega}$ the current strength would lead the voltage in phase).

Formulas (17) and (18) completely describe forced oscillations in a series oscillatory circuit. Let's look at one special case as an example.

The current strength in the oscillatory circuit reaches its maximum value $I_0 = \frac{U_0}{R}$ at $L\omega = \frac{1}{C\omega}$, i.e., when the frequency of the voltage applied to the circuit is equal to the natural frequency of oscillations of the circuit $\omega_0 = \frac{1}{\sqrt{LC}}$. There comes, as they say, a resonance. At resonance, voltages $u_L$ and $u_C$ are identical in amplitude, but oscillate in antiphase, so at any time they cancel each other out. The phasor diagram for the resonance case is shown in figure 6. The phase shift between the current and the applied voltage becomes zero. The cauterization at the active resistance turns out to be equal to the voltage at the ends of the circuit: $u_R = iR = U_0\cos\omega t$. Resonance in a series oscillating circuit is usually called voltage resonance. The fact is that in a real circuit, the inductive and capacitance resistance are always larger than the active resistance, and at resonance, the voltage amplitudes $U_{0L}$ and $U_{0C}$ turn out to be large amplitudes of the applied voltage $U_0$.

⟦folio 56⟧

Energy consumed
oscillatory circuit

Using a phasor diagram, it can be easily shown that the consumed circuit energy is released only at the active resistance $R$.

The power in an alternating current circuit is determined by the formula

$$P = \frac{I_0 U_0}{2} \cos \varphi.$$ (19)

From triangle $ABD$ to Fig. 5

$$U_{0R} = I_0 R = U_0 \cos \varphi.$$ (20)

Substituting into expression (19) instead of $U_0 \cos \varphi$ its value from equality (20), we obtain

$$P = \frac{I_0^2 R}{2} = I^2 R,$$ (21)

where $I$ is the effective value of the current.

Note that at resonance, when the amplitude of the current reaches its maximum, the oscillatory circuit consumes the greatest amount of energy from the outside. Optimal conditions are created for the transfer of energy from the source to the oscillatory system.

Calculation examples
AC purposes
using vector diagrams

Let's look at two specific problems.

Task 1. A lighting unit of seven apartments (Fig. 7) is connected to an alternating current main with voltage $U = 120$ V (U is the effective voltage value) through a choke with inductance $L = 0,05$ g and active resistance $R = 1$ from.

What is the voltage $U_1$ at the entrance to the apartment if the current consumed is $I = 2a$? The voltage changes with a frequency of $v = 50$ Hz. The inductance and capacitance of the electrical circuit of the apartment can be preserved.

The choke and the apartment's lighting network are connected to the main line in series, so the current is the same

⟦folio 57⟧

on all parts of the chain. Voltage $U_1$ and voltage $U_R$ at the active resistance of the inductor are in phase with current $I$. The voltage $U_L$ across the inductive reactance of the inductor determines the current at $\pi/2$. Consequently, the vector diagram of the circuit has the form shown in figure 8. By the Pythagorean theorem
$$U^2 = U_L^2 + (U_R + U_1)^2 = I^2 \omega^2 L^2 + (IR + U_1)^2.$$
From here
$$U_1 = -IR \pm \sqrt{U^2 - I^2 L^2 \omega^2},$$
where $\omega = 2\pi v$. Since the effective voltage value is always positive, i.e. $U_1 > 0$, then
$$U_1 = -IR + \sqrt{U^2 - I^2 L^2 4\pi^2 v^2} \approx 114\theta.$$
Task 2. At what frequency $\omega$ there is no moka salt $i$ and voltage $u$ of the circuit shown in figure 9?
This problem considers an electrical circuit consisting of two branches connected in parallel. One branch contains active and inductive resistance, the other contains capacitance resistance. This circuit is called a parallel oscillating circuit.
We begin constructing a vector diagram with the vector corresponding to the application of voltage, since the voltage is the same for both branches of the circuit. Let's direct the vector $U_0$ vertically upward (Fig. 10). Current $i$ is the sum of currents $i_1$ and $i_2$ (see Fig. 9). Current oscillations $i_1$ are out of phase with voltage oscillations, since the upper section of the circuit contains inductive reactance. Rotate vector $I_{01}$ relative to vector $U_0$ by angle $\varphi$ in the negative direction. According to formulas (17) and (18)
$$I_{01} = \frac{U_0}{\sqrt{R^2 + L^2 \omega^2}}$$ and $tg\varphi = \frac{L\omega}{R}$.
So $i_2$ flowing through the capacitor determines the phase voltage at $\pi/2$. Rotate the corresponding vector $I_{02}$ by angle $\pi/2$ in the positive direction. Its model is $I_{02} = U_0 C\omega$. According to the conditions of the problem, the current $i$ is in phase with the applied voltage, therefore, the vector $I_0$ is directed in the same way as the vector $U_0$. The final vector diagram is presented at figure 10. From this diagram it follows that the amplitudes of the currents in the communication branches correspond.
$$I_{02} = I_{01} \sin \varphi.$$ (22)
Substituting the values ​​$I_{01}$, $I_{02}$ and $\sin\varphi = \frac{tg\varphi}{\sqrt{1 + tg^2\varphi}} = \frac{L\omega}{\sqrt{R^2 + L^2 \omega^2}}$ into equality (22), we obtain
$$U_0 C\omega = \frac{U_0}{\sqrt{R^2 + L^2 \omega^2}} \frac{L\omega}{\sqrt{R^2 + L^2 \omega^2}}.$$
From here
$$\omega = \sqrt{\frac{1}{LC} - \frac{R^2}{L^2}}.$$
At this frequency, current $i$ and voltage $u$ oscillate in phase.
If the active resistance $R$ is small, so
$$\frac{R^2}{L^2} \ll \frac{1}{LC}$$
(in a real oscillatory controller this is practically true), then
$$\omega = \frac{1}{\sqrt{LC}}$$
- this part of the alternating voltage coincides with the frequency of the circuit’s natural oscillations.
