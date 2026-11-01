---
id: 1981-3-mozhaev-kolebaniya-0d2ff4c8
issue: kvant_1981_3
year: 1981
number: "3"
title: Oscillations
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: WV87
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8851065e775c11dbb427d1e63d3fe18dcafcc4e7b223e792120e0a879130b81d
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/15_mozhaev-kolebaniya-0d2ff4c8.md
source_content_sha256: 89640583526683d09f8a74b21818e7f3bbe1a6335d7d5e9a58ac99241a45ff4d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Oscillations

We encounter hesitations everywhere. These are, for example, vibrations of various magnets and scabs of musical instruments, gas molecules in a sound wave and liquid molecules in sea waves. Vibrational movements are performed by atoms in solids and by electrons that are part of the atoms. Fluctuations in electric charge and current occur in the circuits of radios and televisions. According to the same laws, the direction of the electric field and the inductive field in an electromagnetic wave changes.

The most amazing thing is that all these completely different physical phenomena are described by the same mathematical equations, that is, they are subject to a single law. It is with this position that we will consider a number of examples of the simplest oscillatory systems. We will limit ourselves to considering only free oscillations, when there are no external influences on the oscillatory system, the parameters of the system and the conditions under which the oscillations occur do not change over time.

We will neglect energy losses in the oscillatory system, that is, we will assume that the total energy of the system remains constant. This, of course, is an idealization, but if the energy loss is significantly less than the total energy of the system, the oscillations of the system implementation for a sufficiently long time will differ little from the oscillations of the idealized system.

Problem 1. A load of mass m, located on the main horizontal surface, is attached to a fixed wall using a rigid spring k (Fig. 1, a). The load is displaced from the equilibrium position 00′ by amounts A₀ and released without an initial speed. Find:
1) displacement of the load from the equilibrium position depending on time; 2) time dependence of the speed of the load; 3) time dependence of the kinetic energy of the load and the potential energy of the spring; 4) average (per period) kinetic and average potential energy of a given system.

1) Let at some moment of time t the load is at a point with coordinate x (Fig. 1, b). Let us write down the equation of motion of the load along the X axis. In this direction, only one force acts on the load - the elastic force of the spring $\vec{F}$, directed towards the equilibrium position ($x=0$). The projection of this force is $F=-kx$, therefore the equation of motion of the load has the form

Fig. 1.
Fig. 2.

⟦folio 47⟧

$$ma = -kx,$$

(1)

where $a$ is the projection of the acceleration of the load at a given time. Considering that acceleration is the second arbitrary coordinate in time $(a = x'')$, we rewrite equation (1) as follows:

$$x'' + \frac{k}{m} x = 0,$$

or, denoting the constant coefficient $\frac{k}{m}$ by $\omega_0^2$, -

$$x'' + \omega_0^2 x = 0.$$

(2)

The resulting equation describes the harmonic oscillation of the load, that is, oscillations in which the displacement of the load from the equilibrium position changes over time according to the law

$$x = x_m \cos (\omega t + \varphi_0).$$

(3)

Expression (3) is a solution to equation (2). Here $x_m$ is the amplitude, $\omega$ is the circular frequency, $(\omega t + \varphi_0)$ is the phase and $\varphi_0$ is the initial phase of the oscillations.

To find the circular frequency, we substitute solution (3) into equation (2):

$$-x_m \omega^2 \cos (\omega t + \varphi_0) + \omega_0^2 x_m \cos (\omega t + \varphi_0) = 0,$$

or

$$x_m \cos (\omega t + \varphi_0) \cdot (\omega_0^2 - \omega^2) = 0.$$

This equality is valid for any time $t$, if $x_m = 0$ or $\omega_0^2 - \omega^2 = 0$. Since the amplitude of oscillations cannot be equal to zero, it remains

$$\omega_0^2 - \omega^2 = 0,$$ or $\omega = \omega_0 = \sqrt{\frac{k}{m}}$.

We have obtained a very important result: the coefficient for $x$ in equation (2) is nothing more than the square of the circular frequency of oscillations.

Now let's find the amplitude of the oscillations and the initial phase. To do this, we use the initial conditions: at the moment of time $t = 0$ the displacement $x = A_0$ and the speed, which is the first arbitrary coordinate in time, $v = x' = 0$. From the second condition we obtain that $\varphi_0 = 0$, and from the first, that $x_m = A_0$.

Thus, the mixture of cargo changes over time according to the law

$$x = A_0 \cos \sqrt{\frac{k}{m}} t.$$

Fig. 3.

2) Velocity (more precisely, its projection) is the first arbitrary coordinate in time, so it depends on time:

$$v = -A_0 \sqrt{\frac{k}{m}} \sin \sqrt{\frac{k}{m}} t.$$

Graphs $x = x(t)$ and $v = v(t)$ are shown in figure 2.

3) The kinetic energy of the load at an arbitrary moment of time $t$ is equal to

$$E_k = \frac{mv^2}{2} = \frac{A_0^2 k}{2} \sin^2 \sqrt{\frac{k}{m}} t,$$

and the potential energy of the spring is

$$E_\pi = \frac{kx^2}{2} = \frac{A_0^2 k}{2} \cos^2 \sqrt{\frac{k}{m}} t.$$

figure 3 shows the corresponding graphs.

4) The average (per period) values ​​of kinetic and potential energy are equal to the corresponding ones.

$$\overline{E_k} = \frac{A_0^2 k}{2} \sin^2 \sqrt{\frac{k}{m}} t = \frac{A_0^2 k}{4}$$

And

$$\overline{E_\pi} = \frac{A_0^2 k}{2} \cos^2 \sqrt{\frac{k}{m}} t = \frac{A_0^2 k}{4}$$

— the average values ​​of $E_k$ and $E_\pi$ are the same. (Here it was used that the average value of the square of the sine over the period is equal to the average value of the square of the cosine and is equal to 1/2.)

Task 2. A thin hoop with radius $r$ rolls without sliding on the inner surface of a cylinder with radius $R$, making small oscillations around the equilibrium position (Fig. 4). Find the period of these oscillations.

⟦folio 48⟧

Fig. 4.

From the solution to the previous problem it is clear that to find the frequency $\omega$ of the oscillatory system or period $T(T=2\pi/\omega)$ it is enough to draw up an equation of motion and reduce it to the form (2). Then the coefficient of the second term will give the square of the frequency.

It is clear that in equation (2) the role of mixing $x$ can be played by any other physical quantity. Let us choose as such an angle $\varphi$, which the straight line connecting the center of mass of the hoop and the point $O$ forms with the vertical.

To compile the equation of motion for the center of mass of the hoop, we will use energy considerations. In some, an arbitrary moment of time $t$ the hoop has kinetic energy $E_{\kappa1}$ associated with the movement of the center of mass along a circle of radius $R-r$, kinetic energy $E_{\kappa2}$ of rotational motion relative to the center of mass and potential energy $E_{\pi}$ in the gravitational field of the Earth. Let the speed of the hoop's center of mass be $v$; then the kinetic energy is $E_{\kappa1}=mv^2/2$ (m is the mass of the hoop). Since the hoop is thin, that is, all its mass is concentrated in a thin ring, the kinetic energy is $E_{\kappa2}=mV^2/2$, where $V$ is the linear speed of the rotational movement of the hoop. When rolling without piercing $V=v$, therefore

$$E_{\kappa2}=\frac{mv^2}{2}=E_{\kappa1}.$$

For the zero level of potential energy, we choose the level of the center of mass of the hoop in a position of stable equilibrium, then the potential energy of the hoop at a given moment in time will be equal to

$$E_{\pi}=mg((R-r)-(R-r)\cos \varphi)=
=mg(R-r)(1-\cos \varphi)=\frac{mg(R-r)\varphi^2}{2}$$

Fig. 5.

(the last approximate equality is written taking into account the smallness of the angle $\varphi$: $1-\cos \varphi=2\sin^2\varphi/2=\varphi^2/2$).

Total Hoop Energy

$$E_{\kappa1}+E_{\kappa2}+E_{\pi}=\frac{mv^2}{2}+\frac{mv^2}{2}+
\frac{mg(R-r)\varphi^2}{2}=mv^2+\frac{mg(R-r)\varphi^2}{2}$$

remains constant over time. Taking into account the connection between the speed $v$ and the angular velocity of the center of mass in a circle of radius $R-r$, the kinetic energy $E_{\kappa2}$ of rotational motion relative to the center of mass and the potential energy $E_{\pi}$ in the gravitational field of the Earth. Let the speed of the hoop's center of mass be $v$; then the kinetic energy is $E_{\kappa2}=mV^2/2$, where $V$ is the linear speed of the rotational movement of the hoop. When rolling without piercing $V=v$, therefore

$$\varphi'(\varphi''+\frac{g}{2(R-r)}\varphi)=0.$$

Since the angular velocity $\varphi'$ is not equal to zero, the equality

$$\varphi''+\frac{g}{2(R-r)}\varphi=0.$$

This is the equation of motion of the hoop. Therefore, the circular part is $\omega=\sqrt{\frac{g}{2(R-r)}}$, and the period of oscillation

$$T=\frac{2\pi}{\omega}=2\pi\sqrt{\frac{2(R-r)}{g}}.$$

Problem 3. In a vertical cylindrical sauce with a cross-sectional area $S$ a massive piston with mass $M$ (Fig. 5) can move without a tray. The vessel is filled with gas. In the equilibrium position, the mass between the piston and the bottom of the souza is $h$. Determine the period of small oscillations that occur when the piston deflects

⟦folio 49⟧

Fig. 6.
from a position of equilibrium. Atmospheric pressure is $p_0$, the gas is ideal, and the gas temperature is constant.

Let at some instant of time the piston move downward by a small amount $x$. The decrease in gas volume under the piston will be equal to $\Delta V = Sx$, which will cause an increase in gas pressure $\Delta p$. Let's find the connection between $\Delta V$ and $\Delta p$. Because the coil manufacturing process is $pV = \text{const}$, and $\Delta(pV) = 0$. Therefore, $V\Delta p + p\Delta V = 0$, or $\Delta p = -\frac{\Delta V}{V} p = -\frac{Sp}{V} x$.

For small oscillations $\Delta V \ll V$ and $\Delta p \ll p$, therefore

$$\Delta p = -\frac{(p_0 + Mg/S)}{h} x.$$

Let us write down the equation of motion of the piston:

$$Mx'' = \Delta p S,$$

or

$$x'' + \frac{p_0 S + Mg}{Mh} x = 0.$$

From here we find the circular frequency $\omega = \sqrt{\frac{p_0 S + Mg}{Mh}}$ and the oscillation period

$$T = \frac{2\pi}{\omega} = 2\pi \sqrt{\frac{Mh}{p_0 S + Mg}}.$$

Problem 4. An oscillating circuit consisting of a capacitor with a capacitance $C$ and an inductor $L$ is connected through switches $K$ to a source with a constant EMF $\delta$ and internal resistance $r$ (Fig. 6). The key is closed, and after the static mode is established in the circuit, it is closed. Find the dependence of the voltage on the capacitor on time after opening the switch. The ohmic resistance of the coil is considered.

When the switch is closed in a stationary mode through the coils, the flow on the capacitor and, therefore, the charge on it are equal to zero, since the voltage on the capacitor is equal to the voltage across the coils, and it, in the absence of active resistance of the coil, is zero.

After opening the key, free flasks will flow into the circuit. Let at some instant of time the charge on the capacitor be equal to $q$, and the voltage on the capacitor equal to $u$. Obviously, in this case the voltage on the coil is also equal to $u$. We will consider the voltage across the capacitor to be positive when the top plate is positively charged; for the positive direction of the current, we choose the direction indicated by the arrow on figure 6. With this choice of signs, the connection between the charge $q$, voltage $u$ and current $i$ will be as follows: $i = -q'$, $q = Cu$, $u = Li'$.

Hence $i = -Cu'$, $u = -LCu''$, or

$$u'' + \frac{1}{LC} u = 0.$$

We again have an equation that describes the harmonic short circuit with time of the voltage $u$ on the capacitor. It is easy to show that both the current $i$ in the circuit and the charge $q$ on the capacitor changes according to a similar law. See for yourself.

In general, the voltage depends on time looks like this:

$$u = U_M \cos (\omega t + \varphi_0).$$

The frequency of vibrations in this case is equal to

$$\omega = \sqrt{\frac{1}{LC}}.$$

The amplitude and initial phase can be found from the initial conditions: at time $t = 0$ $u = 0$ and $i = \delta/r$. It is easy to show that a solution satisfying such initial conditions will have the form

$$u = \frac{\delta}{r} \sqrt{\frac{L}{C}} \sin \sqrt{\frac{1}{LC}} t.$$

⟦folio 50⟧

Fig. 7.

At the yarn

1. A solid ball suspended on a weightless spring performs harmonic oscillations in the vertical direction with a period of $T_0$ and an amplitude of $A$. What will be the period of oscillation if a force is applied to the ball by a massive solid horizontal plate, with which it will periodically collide elastically? The distance from the equilibrium position of the ball to the plate is $A/2$, the mass of the ball is small compared to the mass of the plate.

2. A thread is thrown through a stationary block in the form of a disk with mass $M$ and radius $R$, at one end of which a load of mass $m$ hangs, and the other end is fixed through a spring with stiffness $k$ (Fig. 7). Find the period of small oscillations of the load relative to the equilibrium position. The thread does not slip relative to the block. Indicated and e. Use the energy method of composing the equation of motion. Kinetic energy of the disk,

$$MR^2\omega^2/4.$$

3. A liquid with density $q$ is poured into communicating vessels with cross sections $S_1$ and $S_2$ (Fig. 8). The mass of the entire liquid is $M$. Neglecting surface tension and viscosity, determine the period of oscillation of the liquid around the equilibrium position.

4. In an oscillatory circuit consisting of an inductor and an air capacitor, the magnitude of the current changes over time according to the harmonic law: $i = I_m \cos \omega t$. When the current in the circuit turns out to be zero, a dielectric plate with a dielectric constant of $e$ is quickly introduced into the space between the capacitor plates. The time of this weighted effect is short compared to the period of oscillations in the circuit. Find the dependence of the current in the circuit on time after hanging the plate.

List of readers who sent correct solutions to problems from the “Kvat” Problem Book

(For the beginning, see p. 35)

A. Sanzhur (Kyiv) 18-31; A. Safonov (Barnaul) 18; S. Svetlchikky (Zaporozhye) 19, 21; Yu. Svistunov (Zaporozhye) 25; V. Semenov (Vladimir) 23; A. Sereda (Donetsk) 25, 27, 31; O. Sereda (Berdyansk) 19; V. Sereda (Lviv) 23, 27; A. Sidorenkov (Smolensk) 19, 21, 27—29, 31; V. Sidorin (Rutov) 19, 31; V. Simonov (Moscow) 18, 25, 27, 28; A. Sokok (Talgar) 19, 21; O. Skoptsov (Angarsk) 18, 19, 21; A. Smirnov (Kurgan) 21, 25, 27, 28, 31; I. Smolyarenko (Minsk) 23, 25, 28, 31; A. Sokol (Chernogolovka village, Moscow region) 18, 25, 28, 29, 31; I. Solovey (Donetsk) 25, 27; V. Solovye (Rybnoe) 23; S. Soloenko (Meluuz) 19; Yu. Spiridonov (Zagorsk) 25, 27, 28, 31; D. Stenanov (Arzamas) 25, 29, 31; A. Strelets (Kyiv) 18, 21; D. Suvorov (Sverdlovsk) 28, 31; T. Surova (Stupino) 25, 27; E. Syrchieva (Vyshny Volochek) 18, 25; I. Tavin (Kovrov) 21, 25, 27; S. Takovychky (Zhukovsky) 18; Yu. Taldenko (Sumy) 18, 19, 23, 25, 27, 31; V. Tanasichuk (Horodenka) 23, 27; A. Tereshchenko (Kyiv) 25, 27-29; S. Timofeev (Noazov district, Donetsk region) 19; Yu. Topchev (Svetly) 21; V. Faber (Baku) 23, 25, 29, 31; N. Fedin (Omsk) 18, 19, 20, 23, 25, 27, 31; V. Fedyukovich (Kyiv) 18, 20, 21, 27-29, 31, 32; S. Fedyakov (Efremov) 28; N. Fesun (Kyiv) 21, 25, 27; A. Flerov (Riga) 18, 19, 27; O. Fonarev (Sumgant) 18, 25, 26; M. Friedman (Lviv) 28, 31; A. Frolov (Tula) 20, 21, 28; S. Frolov (Moscow) 25, 28, 29, 31; I. Kharin (Sukhumi) 23, 25, 27; I. Khasanov (Kokand) 25, 31; S. Khosid (Alma-Ata) 23, 25; A. Tsekhansky (Zaprudnya village, Moscow region) 18, 23, 25, 27-29, 31; Yu. Tsyzdankov (Drozhzhanovsky district of the TASSR) 19-21, 27-29, 31, 32; O. Cheryakov (Arkhangelsk) 27; E. Chulkin (village of Ryabovo, UdASSR) 18, 19, 25, 26, 28; A. Chulkov (Muchkapsky village, Tambov region) 18—21, 27, 28, 31, 32; V. Shapoval (Vinnitsa) 18, 19, 23, 25, 27, 28; Yu. Shapovalov (Serpukhov) 18, 23, 25, 27; A. Shapenko (Orsk) 18, 19; S. Shary (Novosibirsk) 23; A. Shevchenko (Artemovsk, Donetsk region) 19, 28, 29; M. Shevchenko (Artemovsk, Donetsk region) 19, 28, 29; L. Yashchuk (Rivne) 25.
