---
id: 1981-7-danilin-elektroizmeritelnyie-priboryi-4d8b8bae
issue: kvant_1981_7
year: 1981
number: "7"
title: Electrical measuring instruments
authors:
  - Данилин В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 45
page_labels: 39, 40, 42, 43
tag: I40F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3f459cfc77503922dd62557b4400220a7df9773fe446ba6334c342a8191a926d
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/13_danilin-elektroizmeritelnyie-priboryi-4d8b8bae.md
source_content_sha256: d8b263aac26aaeda95daff553f25fc4792ca6e5b3918c34a36c84594221c1037
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

V. Danilin

Electronic measuring instruments

In all electronic measuring instruments, the effect of the electron current is reduced to the movement of the moving part of the measuring mechanism. The generally movable part and the arrow of the device associated with it rotate around its axis. The moment of forces causing this rotation is called the turning moment. In order for the pointer to not turn off indefinitely, and for the angle of deflection to correspond to the value being changed, it is necessary to counteract the rotation of the pointer. The moment of force that produces such an effect is called the counteracting moment.

In practice, a counteracting moment is always created by the slim elasticity of the pressure. But the turning point can be created in different ways. Depending on the method of generating torque, electrical measuring instruments are assigned to one or another system. Let's look at some of them.

The operating principle of magnetoelectric system devices is based on the interaction of a conductor with current and a magnetic field. The field is created by a permanent magnet 1 (Fig. 1), the current passes through a coil in the form of a frame 2. The frame is a movable element of the device and is on the same axis with the arrow 3.

The torque acting on the frame, thanks to the designed magnet, does not depend on the angle of rotation of the frame and is equal to

$$M_{\text{вр}} = |\vec{B}| \text{INS},$$

where $\vec{B}$ is the magnetic field induction, $I$ is the current, $N$ is the number of turns in the frame, $S$ is its area. Under the influence of this moment, the frame begins to rotate. In this case, the spiral spring 4 twists and a counteracting moment arises, proportional to the angle of rotation of the frame $\alpha$:

$$M_{\text{пр}} = k\alpha,$$

where $k$ is the proportionality coefficient, depending on the elastic properties of the pressure.

When the counteracting moment becomes equal to the torque, the frame stops. In this case, the angle of rotation of the frame, and therefore the arrow, is equal to

$$\alpha = \frac{|\vec{B}| \text{SN}}{k} I,$$

that is, primo is proportional to the current in the frame. This ensures the uniformity of the instrument scale.

Macnitoelectric devices are designed only for direct current, which, of course, is their disadvantage. The advantages of these devices include low energy consumption and high sensitivity.

The most sensitive devices of the magnetoelectric system are mirror galvanometers. In them, based on the intervention of the arrow, a small flat mirror is fixed. A narrow beam of light from a light bulb

Fig. 1.

⟦folio 40⟧

falls on the mirror, and the bunny reflected from it falls on the remote scale. The sensitivity of mirror galvanometers can reach $10^{-12}$ A/mm.

Problem 1. A mirror galvanometer has a size of $S = a \times b = 40 \times 30$ mm², on which $N = 100$ turns of copper wire with a diameter of $d = 0,1$ mm are wound. The frame is suspended on a thread in which a counteracting moment $M_0$ occurs when the thread is twisted at an angle $\alpha_0 = 1^\circ$. The magnetic field is perpendicular to the axis of rotation of the frame in all its possible positions; magnetic field induction $|\vec{B}| = 10^{-1}$ T. At a distance of $L = 1$ m from the galvanometer there is a millimeter scale. 1) At what angle is the surface of the frame if a current of $I = 0,1$ mA is passed through its winding? 2) What power $P$, consumed by the device, corresponds to the deviation of the bunny on the scale by $l = 1$ mm?

1) When the frame is in equilibrium, the torque $M_{BP} = |\vec{B}|INS$ is balanced by the counteracting moment $M_{np} = k\alpha = M_0\alpha/\alpha_0$:

$$|\vec{B}|INS = \frac{M_0\alpha}{\alpha_0} \alpha.$$

From here

$$\alpha = \frac{|\vec{B}|INS\alpha_0}{M_0\alpha} = 12^\circ.$$

2) The power consumed by the galvanometer depends on the current $I$ flowing through the frame winding and on its resistance $R$:

$$P = I^2R.$$

Let's find what current $I$ corresponds to the deviation of the bunny on the scale by a distance $l$. When the frame, and therefore the mirror, is rotated by an angle $\alpha$, the reflected beam is rotated by an angle $2\alpha$ (check this yourself), and the bunny moves along the scale by a distance $l = 2\alpha L$ (we taught that $l \ll L$). Thus,

$$I = \frac{k\alpha}{|\vec{B}|NS} = \frac{M_0\alpha}{\alpha_0} \frac{l}{2L} \frac{1}{|\vec{B}|NS} \approx 2,4 \cdot 10^{-7} \text{ A}.$$

Fig. 2.

The resistance of the frame winding is

$$R = \varrho \frac{l'}{s} = \varrho \frac{2(a+b)N}{\pi d^2/4} \approx 31 \text{ Om}.$$

Finally

$$P = I^2R \approx 1,8 \cdot 10^{-12} \text{ Bt}.$$

In devices of an electrodynamic system, torque arises from the interaction of currents $i_1$ and $i_2$ flowing through two coils: stationary coil 1 and moving coil 2 (Fig. 2). In the general case, currents are variable and change according to the laws $i_1 = I_{1M} \cos \omega t$ and $i_2 = I_{2M} \cos (\omega t - \varphi)$.

The instantaneous value of the torque is proportional to the product of the currents: $M_{BP} \sim i_1i_2$. Due to inertia, the moving coil does not have time to follow instantaneous changes in torque, so its deviation is proportional to the average value over the period

$$M_{BPcp} = kI_1I_2 \cos \varphi.$$

Here $k$ is a constant coefficient, $I_1$ and $I_2$ are the effective current values, $\varphi$ is the phase shift between them. If the windings are connected in series, the reading of the device will be proportional to the square of the current. Consequently, the scale is also an uneven device.

It is obvious that the devices of the electrodynamic system can change the power in alternating current circuits ($P_{cp} = IU \cos \varphi$, where $U$ is the effective voltage value). To do this, it is enough to connect one coil (fixed) in series with the selected section of the circuit, and the second coil (moving) in parallel to this section. Exactly

⟦folio 42⟧

The permeter is connected in series to the circuit, and the entire measured current passes through it. Therefore, in order not to introduce additional resistance into the circuit, the resistance of the ammeter should be as small as possible. The voltmeter is connected in parallel to the section of the circuit where the voltage should be measured. Therefore, its resistance should be as high as possible so as not to joke around the section of the circuit under study.

Task 4. Estimate the errors that occur when measuring currents and voltages, taking into account the specific resistance values ​​of the ammeter and voltmeter (Fig. 4).

In the circuit at figure 4, and the current flowing through the ammeter A and the voltage resistance $R_H$ is the same. Therefore, there is no error in the ammeter readings. But the load voltage measured by a voltmeter differs from the true one:

$$U_H = I R_H, \quad U_V = I (R_H + R_A).$$

Thus, the absolute error in measuring the voltage across the load is equal to

$$\Delta U = |U_H - U_V| = I R_A,$$

and the relative error

$$\delta = \frac{\Lambda U}{U_H} = \frac{I R_A}{I R_H} = \frac{R_A}{R_H}.$$

In the circuit at figure 4, b, the voltmeter reading is true, and the ammeter shows the sum of the currents flowing through the load and through the voltmeter:

$$I_A = I_H + I_V = \frac{U_H}{R_H} + \frac{U_H}{R_V}.$$

The absolute and relative errors in current measurement are equal to the corresponding

$$\Delta I = |I_H - I_A| = I_V = \frac{U_H}{R_V}$$

And

$$\delta = \frac{\Delta I}{I_H} = \frac{U_H}{R_V} : \frac{U_H}{R_H} = \frac{R_H}{R_V}.$$

Problem 5. A voltmeter with an unknown internal resistance is connected first to a resistor with resistance $R_1$, then to a resistor with resistance $R_2$, and finally to a resistor with resistance $R$ (Fig. 5).

In this case, the voltmeter readings are $U_1 = 4$ V, $U_2 = 6$ V and $U = 12$ V, respectively. Neglecting the internal resistance of the source, determine the voltage $U_{01}$ and $U_{02}$ across the first and second resistors in the absence of a voltmeter.

When connected to a resistor with resistance $R$, the voltmeter reading is equal to the emf of the source (since the internal resistance of the source can be neglected).

When the voltmeter is connected to the first resistor, the resistance of this section $R'_1$ is such that

$$\frac{1}{R'_1} = \frac{1}{R_1} + \frac{1}{R_V},$$

where $R_V$ is the internal resistance of the voltmeter. The voltage in this section is equal to the voltmeter reading $U_1 = 4$ V, and the voltage across the second resistor is $U - U_1 = 8$ V $= 2 U_1$. Since the same current flows through both sections of the circuit, we have $R_2 = 2 R'_1$, or

$$\frac{1}{R_1} + \frac{1}{R_V} = \frac{2}{R_2}.$$

If the voltmeter is connected to the second resistor, then, after carrying out similar calculations, we get

$$\frac{1}{R_2} + \frac{1}{R_V} = \frac{1}{R_1}.$$

Subtracting the previous one from the last equation, we find

$$\frac{R_1}{R_2} = \frac{U_{01}}{U_{02}} = \frac{2}{3}.$$

Besides,

$$U_{01} + U_{02} = U.$$

Hence,

$$U_{01} = \frac{2}{5} U = 4,8 \text{ В}, \quad U_{02} = \frac{3}{5} U = 7,2 \text{ В}.$$

In practice, devices with several limits are often used

⟦folio 43⟧

current and voltage measurements. To do this, when measuring voltage, additional resistances are connected in series with the device, and when measuring currents, parallel resistances - shunts - are connected to the device. In some cases, it is possible to simultaneously connect additional resistances and shunts. (Note that connecting additional resistances and shunts not only makes it possible to make devices multiscale, but also reduces measurement errors corresponding to an increase or decrease in the internal resistance of the device.)

Problem 6. A galvanometer with an internal resistance of $R_\Gamma = 50$ Ohm has a measuring scale division circuit of $C = 50$ µA. The scale is divided into $N = 100$ divisions. How to make a voltmeter from this device to measure voltages up to $U = 200$ V or an ammeter to measure currents up to $I = 800$ mA?

When the needle deflects to the full scale through the galvanometer, the maximum permissible current flows
$$I_{\text{пр}} = CN = 5 \text{ мА},$$
in this case the voltage on the galvanometer is equal to
$$U_{\text{пр}} = I_{\text{пр}} R_\Gamma = 250 \text{ мВ}.$$

In order to use this galvanometer to measure voltage up to the value $U$, an additional resistance $R_\Delta$ must be connected in series with the galvanometer. The voltage $U_\Delta$ across it is equal to the difference in voltage in the circuit and on the galvanometer, and the current flowing through the galvanometer and the additional resistance is the same. That's why
$$\frac{U_\Delta}{U_\Gamma} = \frac{R_\Delta}{R_\Gamma},$$

Fig. 5. Fig. 6.

Fig. 7.

where
$$R_\Delta = R_\Gamma \frac{U_\Delta}{U_\Gamma} = R_\Gamma \left( \frac{U}{U_\Gamma} - 1 \right) \approx 40 \text{ кОм}.$$

To operate the galvanometer as an ammeter parallel to the galvanometer, you must connect a shunt with resistance $R_\Delta$. The current $I$ flowing in the circuit is equal to the sum of the currents $I_\Gamma$ in the galvanometer and $I_\Delta$ in the shunt, and the voltage on the galvanometer and on the shunt are the same. Hence,
$$I_\Gamma R_\Gamma = I_\Delta R_\Delta,$$

where
$$R_\Delta = R_\Gamma \frac{I_\Gamma}{I_\Delta} = R_\Gamma \frac{I_\Gamma}{1 - I_\Delta} = \frac{R_\Gamma}{1 - I_\Delta} \approx 0.31 \text{ Ом}.$$

Exercises
1. In the circuit shown in figure 6, all voltmeters are the same. The emf of the battery is $\mathcal{E} = 5$ V, its internal resistance is low. The first voltmeter shows $U_1 = 2$ V. What do the other voltmeters show?
2. To measure large currents in circuit $CC$, a shunt $Ш$ is used, parallel to which a measuring device $\Gamma$ is connected through resistances $R_1 = 2$ Ohm and $R_2 = 90$ Ohm (Fig. 7). In position $A$ of switch $\Pi$ the entire scale of the device corresponds to the current in the circuit $I_1 = 10$ A, in position $B$ - to current $I_2 = 100$ A. Find the internal resistance $r$ of device $\Gamma$. The shunt resistance is much less than $R_1$ and $R_2$.
3. When a shunt with a resistance of $R_\Delta = 100$ Ohm is turned on, the parallel measuring device deviates the needle to the full scale at a current in the external circuit of $I_1 = 3$ A. When an additional resistance of $R_\Delta = 300$ Ohm is turned on to an unshielded galvanometer, the scale of the device becomes four times greater than without additional resistance and shunt. What shunt should be taken so that the needle deflects to the full scale when the current in the external circuit is $I_2 = 7.5$ A?
4. A galvanometer with internal resistance $r_\Gamma$, shunted by resistance $R_\Delta$ and connected in series with additional resistance $R_\Delta$, is used as a voltmeter. At a voltage of $U_1 = 1$ V, the galvanometer needle deviates by one division. What additional resistance must be taken so that the galvanometer needle deviates by one division at a voltage of $U_2 = 10$ V?
