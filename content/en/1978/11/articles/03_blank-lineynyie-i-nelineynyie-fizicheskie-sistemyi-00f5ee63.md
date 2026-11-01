---
id: 1978-11-blank-lineynyie-i-nelineynyie-fizicheskie-sistemyi-00f5ee63
issue: kvant_1978_11
year: 1978
number: "11"
title: Linear and nonlinear physical systems
authors:
  - Бланк Е. И.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: SF2P
lang: en
source: kvant_digital
extraction: vision
content_sha256: fd18017e2f4456e05401a39742bc9d2a4d8b1b7a61c9f191fb5c7b8884a172be
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/03_blank-lineynyie-i-nelineynyie-fizicheskie-sistemyi-00f5ee63.md
source_content_sha256: 88386279a8a8ae5fdd1cda425cca21f0090e281509e18cef38cfaa03ae702cde
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Linear and nonlinear physical systems

Phenomena occurring in physical systems are quantitatively described by equations, and functional dependencies between various physical quantities are expressed. The nature of these dependencies can be very diverse. A significant group among them consists of linear dependencies of type $y=f(x)=ax+b$, where $a$ and $b$ are considered constant. Very often, by appropriate selection of the reporting system, coordinate system or initial conditions, a dependence of this type can be reduced to direct proportionality.

There are a lot of believers in the direct proportional dependence of physical quantities. This is how the model of elastic force and the magnitude of deformation are related: $|\vec{F}|=kx$; capacitor charge and voltage across it: $q=CU$; voltage at the ends of the conductor and current strength along the conductor: $U=RI$; the flux of magnetic induction producing the circuit, and the current strength in the circuit $\Phi=LI$, etc. The proportionality coefficients in these formulas - rigidity $k$, capacitance $C$, resistance $R$, inductance $L$ - are constant values ​​that characterize the properties of a given system.

When the properties of a physical system (for example, the resistance of a circuit) do not depend on its state (on the current flowing through the circuit), the system is said to be linear. In linear systems, the principle of superpoly is observed: as a result of several simultaneous impacts, the system comes to the same state as if these impacts followed separately one after the other. In other words, the result of any one influence in the presence of another (or others) turns out to be the same as if this other influence was absent. So, for example, if as a result of the action of a mass load $m_1$ the elongation of the spring is equal to $x_1$, and as a result of the action of a mass load $m_2$ the elongation is equal to $x_2$, then both loads $(m_1+m_2)$ suspended from the spring will cause an elongation $x_1+x_2$.

figure 1 shows graphs of the dependence of the voltage drop on a resistor with a constant resistance on the current (voltmeter characteristic of the resistor, Fig. 1, a), the charge of a capacitor with a constant capacitance on the voltage on its plates (coulomb wave characteristic of the capacitor, Fig. 1, ​​b), the flux of magnetic induction through the circuit with

⟦folio 3⟧

constant inductance from current (vber-amp characteristic of the coil, Fig. 1, $\theta$). These are straight lines; the angle of inclination of each of them to the abscissa axis is determined, respectively, by the values ​​$R$, $C$ or $L$.

It is not difficult to find that $R=U_I/I=tg\alpha$, $C=q_U/U=tg\beta$, $L=\Phi_I/I=tg\gamma$. Elements of physical systems whose characteristics are specified by graphical straight lines are often called linear.

However, we know that many permanent characteristics of physical systems remain truly constant only under certain conditions - under certain restrictions on the magnitude of the impact. Thus, the spring stiffness coefficient $k$ is constant only if the electric field created by the charges of the plates is necessary, then the capacitance of such a capacitor is no longer a constant value. And the inductance of the coil may depend on the current flowing through the winding, if the core is made of a ferromagnet - a material whose magnetic properties depend on the inductance of the magnetic field created by the current flowing through the winding.

The characteristics of such elements are no longer linear; therefore, such elements are called *nonlinear*, and systems containing them are called *nonlinear* systems. Thus, nonlinear systems are systems whose properties (for example, circuit resistance) depend on the state of the system (on the current flowing through the circuit).

How this nonlinearity “appears” can most easily be understood from this example. With significant deformations, Hooke's law is known to be violated; the values ​​of rigidity $k$ begin to depend on the amount of mixing. To the extent that the mixing is not much greater than “elastic”

(that maximum mixing that also leads to elastic deformations), this dependence can be written with a good approximation in the form $k=ax+b$. then the elasticity force turns out to be related to the magnitude of the displacement by the correspondence $|\vec{F}|=(ax+b)x=ax^2+bx$, that is, a clearly nonlinear relationship.

Calculation of electrical circuits containing nonlinear elements is most often done graphically. Let's look at this simple problem as an example. At figure 2 there is a diagram of a nonlinear system containing a diode and an incandescent lamp, the current-voltage characteristics of which are specified at figure 3. The circuit is connected to a constant voltage source $U=2B$. What is the current in the circuit?

Since the lamp and diode are connected in series, for a given value of current in the circuit, the padre voltage at its ends is equal to the sum of the padre voltages on the diode and on the lamp. Taking advantage of this, we will construct the current-voltage characteristic of the entire circuit (black line at figure 3). Now it is easy to find that at $U=2$ V the current is 0.13 A.

⟦folio 4⟧

Nonlinear electrical and magnetic systems are widely used in technology. Generators of independent oscillations, modulators and detectors of oscillations, frequency converters, etc. are devices that are primarily implemented only on nonlinear elements.

Let us explain, for example, the need for nonlinear elements to implement amplitude modulation of oscillations. As is known, with amplitude modulation, the amplitude of high-frequency oscillations must change in accordance with the change in the voltage of the useful signal, for example, an audio frequency signal. Regardless of the specific circuit, the parts of which it consists, the modulator can be represented as a kind of nonlinear resistor - a resistor whose resistance depends on the control voltage of the (useful) signal: as this voltage decreases, the resistance increases. If the resistor is connected to a high (carrier) frequency alternating voltage source, then the current oscillations in the resistor repeat the oscillations of the “signal” from the source (Fig. 4, a). If now an additional low-frequency alternating voltage (useful signal) is applied to the resistor, then the resistance of the resistor begins to “oscillate” with the same low frequency (Fig. 4, b), and as a result, the amplitude of current oscillations in the resistor will increase as the resistance decreases and decrease as it increases. In other words, the amplitude of the carrier frequency oscillations will, in turn, “oscillate”, following the change in the magnitude of the useful signal (Fig. 4, s).

It is clear that a linear resistor would not provide modulation of high-frequency oscillations: in the same mode that we have described, the resulting current oscillations in the resistor would be a superposition of high-frequency and low-frequency oscillations, and the amplitude of the high-frequency oscillations would remain unchanged (Fig. 5).

In the Problem Book «Kvant» in this issue of the magazine there is problem F546. The diagram shown in this book is

⟦folio 5⟧

Next, this is a schematic diagram of the magnetic amplifier device. Magnetic amplifiers are another example of the use of nonlinear elements in technology. Problem F546 is quite difficult. We will make it easier for the reader to solve it with the following hint: in magnetic amplifiers, the nonlinear dependence of the inductance of a coil with a ferromagnetic core on current “works.”

In conclusion, it should be noted that, strictly speaking, all physical systems are nonlinear if the limit of change in their state is not limited. We saw this in mechanical systems - at large deformations, in electromagnetic systems - at high currents (voltages). However, often even in the area of ​​small changes in the state of the system it must be considered as nonlinear. Thus, the force of dry friction changes abruptly when the sign of the speed changes, the current strength in conductors with one-way conductivity changes nonlinearly when the sign of the voltage changes.

Exercises

1. There is a box with mass $m=10$ kg on a horizontal plane. The maximum static friction force is $|\vec{f}|=35$ N. The box can be subject to two mutually perpendicular forces $|\vec{F}_1|=30$ N and $|\vec{F}_2|=40$ N, lying in the horizontal plane. Describe the movement of the box in the case when it is acted upon by: a) only force $\vec{F}_1$; b) only strength $\vec{F}_2$; c) both forces at the same time.

2. The lamp and diode, the current-voltage characteristics of which are shown in figure 3, are connected in parallel. Current in the unbranched part of the circuit $I=0,15$ A. Determine the graphic points in the lamp $I_\pi$ and in the diode $I_\pi$.

3. A resistor with a resistance of 6 Ohms and a nonlinear resistance, the current-voltage characteristic of which is described by the dependence $U=2\sqrt{I}$, are connected in series and connected to a voltage source $U=4$ V. Calculate without plotting the current strength in the circuit.

Fig. 5.
