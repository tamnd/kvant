---
id: 1990-4-mozhaev-perehodnyie-protsessyi-v-elektricheskih-tsepyah-002e21f7
issue: kvant_1990_4
year: 1990
number: "4"
title: Transient processes in electrical circuits
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 72
page_labels: 64-70
lang: en
source: kvant_digital
extraction: vision
content_sha256: 73ba830b355c88c11ce73b2471fdde41fa4bfcd64f408aeaf1d59444113a3671
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/16_mozhaev-perehodnyie-protsessyi-v-elektricheskih-tsepyah-002e21f7.md
source_content_sha256: 17dec3e05e9a4c5539b794e202a235b24ac17e4903bac259c34c53e95095b485
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

---
running_head:
folio:
---

Transitional
processes
in electrical
chains
Candidate of Physical and Mathematical Sciences
V. MOZHAEV

When an electrical circuit is closed or opened or its parameters change, the system moves from one set state to another. We will call what happens in a given circuit during this transition the transition process.

We will consider electrical circuits in which constant sources of EMF operate.

The steady state can be either Stationary or non-Stationary. In the first case, the current, charges and voltages in all elements of the circuit remain constant over time. In the case of a stationary mode, the current in the circuit or, for example, the charge on a periodic capacitor changes with time, i.e., the system is in an oscillatory mode. Obviously, this is only possible when there is no energy dissipation in the system (i.e., dissipation of part of the energy in the form of heat). In the presence of losses, the system will always come to the Stationary established established state

In most tasks offered to applicants, as a rule, we are talking about established states

⟦folio 65⟧

---
running_head:
folio:
---

Let us now move on to consider specific examples.

Problem 1. There is the simplest circuit: a source of constant EMF $E_0$ and a voltage in the form of a resistor with resistance $R$ (Fig. 1). Find the dependence of the current in the circuit on time after closing the switch $K$.

Let's write Ohm's law for this circuit at an arbitrary point in time after closing the key:

$$E_0 = I(t)R.$$

The solution to this equation has the form

$$I(t) = E_0/R = \text{const.}$$

So in the circuit at any time after the key is closed it remains constant and equal to $E_0/R$, i.e. in the instantaneous system the Stationary mode is established. In reality, even in such an idealized system (in the complete absence of inductance and resistance in the circuit), the time it takes to reach the stationary mode will be, although very small, but not zero, which is associated with the finite speed of decay of the electromagnetic wave. But Ohm’s law for a closed circuit “does not know” about this and cannot describe speed regimes in which this must be taken into account. And we, naturally, will not consider them.

Problem 2. An electric circuit contains a resistor with resistance $R$ and a capacitor with resistance $C$ (Fig. 2). How does the voltage across a capacitor change over time?

Let's apply Ohm's law for this case:

$$E_0 = U(t) + I(t)R,$$

where $U(t)$ is the voltage across the capacitor at an arbitrary moment in time (after closing the switch $K$), and $I(t)$ is the current in the circuit. Using connections $I(t) = \Delta(CU)/\Delta t$, we write Ohm’s law in the form

$$RC \frac{\Delta U(t)}{\Delta t} + U(t) = E_0.$$

This equation describes the dependence of the voltage on the capacitor on time at any time after the switch $K$ is closed. Let's introduce a new variable $U^*(t) = U(t) - E_0$, then Ohm's law will look like this:

$$\frac{\Delta U^*(t)}{\Delta t} = -\frac{1}{RC} U^*(t).$$

This type of equation describes many well-known processes, for example, the radioactive decay of nuclei, the dependence of the speed of a body on time when a resistance force is applied to the body, proportional to the speed of the body, i.e. those processes in which the rate of change over time of a certain value is proportional to this value at a given moment in time. In our case, the rate of change $U^*(t)$ is proportional to this value itself with a coefficient of proportionality - $1/(RC)$. The minus sign means that $U^*(t)$ kills over time. We will present here a solution to such an equation, but only for educational purposes:

$$U^*(t) = Ae^{-t/(RC)},$$

where $A$ is some constant that is found from the initial conditions. At the moment of closing the key $K$ the voltage on the capacitor was equal to:

$$U(0) = 0, \text{ следовательно, } U^*(0) = U(0) - E_0 = -E_0 \text{ и } A = -E_0.$$

The final dependence of the voltage on the capacitor on time will be:

$$U(t) = E_0(1 - e^{-t/(RC)}).$$

⟦folio 66⟧

---
running_head:
folio:
---

figure 3 shows the corresponding graph.

As follows from the obtained dependence, the capacitor charge will last indefinitely and the direction to the capacitor can become equal to the source emf $E_0$ only in the foreseeable future. But all this applies to an idealized scheme in which its parameters ($E_0$, $R$ and $C$) are strictly constant values ​​and do not depend on time. In reality, they all “breathe”, that is, they change over time, for example due to instability of the ambient temperature. This leads to a sharp distortion of the obtained dependence $U(t)$ in the region of large values ​​of $t(t \gg RC)$, i.e., when the direction to the capacitor no longer differs much from $E_0$. Therefore, for all finite values ​​of $R$ and $C$, the charge time is always finite and completely determined by the value $RC$, called the time constant. The lower the value of this constant, the faster the charge will occur, and vice versa.

Problem 3. Distance generators containing a resistor with resistance $R$ and an inductor $L$ (Fig. 4). Find the dependence of the current in the circuit on time after closing the switch $K$.

Ohm's law for a given circuit has the form

$$E_0 - L \frac{\Delta I(t)}{\Delta t} = I(t)R.$$

Let's introduce a new variable $I^*(t) = I(t) - E_0/R$ and get

$$\frac{\Delta I^*(t)}{\Delta t} = -\frac{R}{L} I^*(t).$$

This is an equation already familiar to us; we look for its solution in the form

$$I^*(t) = Ae^{-Rt/L},$$

where $A$ is some constant that is found from the initial conditions. At the moment of closing the key $K$, the current in the circuit was equal to zero: $I(0) = 0$; hence $I^*(0) = I(0) - E_0/R = -E_0/R$ and $A = -E_0/R$. Then

$$I(t) = \frac{E_0}{R}(1 - e^{-Rt/L}).$$

We obtained dependence $I(t)$, which is completely similar to dependence $U(t)$ in the previous case. The constant time to reach the Stationary mode in this case is equal to $\tau = L/R$ - the smaller $R$, the more the system reaches a stable state, and as $R$ tends to zero, $\tau$ tends to infinity. At $R = 0$ Ohm's law has the form

$$E_0 - L \frac{\Delta I(t)}{\Delta t} = 0,$$

and the solution to this equation is

$$I(t) = \frac{E_0}{L} t,$$

that is, the current in the circuit will increase linearly with time and will not be able to reach the Stationary mode. In reality, the increase in current will be limited by the finite energy reserve of the source. figure 5 shows a graph of $I(t)$ for some final value $L/R$.

Problem 4. Parallel connection of an inductor $L$ and a resistor $R$ are connected through a switch $K$ to a battery with an emf $E$ and an internal resistance $r$ (Fig. 6). At the initial moment of time, the key $K$ is open and there is no current in the circuit. What charge will flow through the resistor after the switch is closed? Neglect the coil resistance. Draw

⟦folio 67⟧

---
running_head:
folio:
---

graph of the current through the resistor and the current through the coil versus time.
Let at an arbitrary moment in time after the switch $K$ is closed, a current $I_R(t)$ flows through the resistor $R$, and a current $I_L(t)$ flows through the inductor $L$ (see Fig. 6). Obviously, the battery current is equal to the total current $I_R(t) + I_L(t)$. Let's choose two closed contraries and write Ohm's law for each of them. For a circuit enclosing a battery and a resistor, we can write
$$\mathcal{E} = I_R(t)R + (I_R(t) + I_L(t))r. \tag{1}$$

A similar equation for a counter containing a coil and a resistor will have the form
$$L \frac{\Delta I_L(t)}{\Delta t} = I_R(t)R. \tag{2}$$

At the initial moment of time, immediately after closing the key $K(t=0)$, the current is $I_L(0)=0$. From the first equation (this equation is also valid for $t=0$) it follows that the current through the resistor immediately after closing the switch is equal to $I_R(0) = \mathcal{E}/(R+r)$. Know the points themselves, we can find the rates of their change at the initial moment of time
$$\frac{\Delta I_L}{\Delta t} \bigg|_{t=0} \neq \frac{\Delta I_R}{\Delta t} \bigg|_{t=0}.$$

From equation (2) it follows that
$$L \frac{\Delta I_L}{\Delta t} \bigg|_{t=0} = I_R(0)R = \frac{\mathcal{E}}{R+r} > 0,$$
that is, the current through the coil increases over time. Since $\mathcal{E}$ does not depend on times, it follows from equation (1) that
$$\frac{\Delta I_R(t)}{\Delta t} (R+r) + \frac{\Delta I_L(t)}{\Delta t} r=0,$$
and at moment $t=0$

$$\frac{\Delta I_R}{\Delta t} \bigg|_{t=0} = -\frac{\Delta I_L}{\Delta t} \frac{r}{R+r} = -\frac{\mathcal{E}R}{(R+r)^2L} < 0$$

- the current through the resistor decreases at a certain finite rate.

The system is dysregulated, so it tends to some stationary state. Both equations are satisfied by a stationary solution
$$I_R=0, I_L=\mathcal{E}/r.$$

Consequently, the current through the resistor decreases and asymptotically tends to zero, and the current through the coil increases and tends to the value $\mathcal{E}/r$. Dependencies $I_R(t)$ and $I_L(t)$ are shown in figure 7.

To find the total charge $Q_R$ flowing through the resistor, we rewrite equation (2) in the form
$$L \Delta I_L(t)=RI_R(t)\Delta t.$$

Here $I_R(t)\Delta t$ is the charge $\Delta Q_R$ flowing through the resistor in a short period of time $\Delta t$; hence,
$$L \Delta I_L(t)=R\Delta Q_R.$$

As can be seen from this equation, the relationship between the change in current through the coil and the charge flowing through the resistor does not depend on time, i.e., it remains the same for any time interval. During the entire process of establishing a steady state
$$L(I_L(\infty)-I_L(0))=RQ_R.$$

Taking into account the fact that $I_L(\infty)=\mathcal{E}/r$, the total charge flowing through the resistor will be equal to
$$Q_R = \frac{\mathcal{E}L}{Rr}.$$

Task 5. An oscillating circuit consisting of an inductor $L$, a capacitor $C$ and an ideal diode $D$ (Fig. 8) is connected through switches $K$ for a time $t$ to a source of constant EMF $\mathcal{E}$, and then disconnected. Find the dependence of the capacitor on the time after the switch is closed. Present this dependence graphically. Neglect the internal resistance of the source and the resistance of the coil.

⟦folio 68⟧

---
running_head:
folio:
---

After closing the key $K$ in the process, the moment of time $t$ for a circuit containing a source and a coil, according to Ohm’s law, can be written

$$E - L \frac{\Delta I_L(t)}{\Delta t} = 0.$$

Since the initial current is $I_L(0) = 0$, then the dependence of the current $I_L(t)$ through the inductor will have the form

$$I_L(t) = \frac{E}{L} t,$$

i.e. the current is linearly directed with time and after time $\tau$ will be equal

$$I_L(\tau) = \frac{E}{L} \tau.$$

So through the diode, obviously, all this time it will be equal to zero.

Consider a circuit containing a coil, a diode and a capacitor after the switch $K$ is closed (after a time $\tau$). Ohm's law for this counter looks like this:

$$-L \frac{\Delta I_K}{\Delta t} = U(t),$$

where $I_K$ is the current in the circuit (see Fig. 8), and $U(t)$ is the voltage across the capacitor. Taking into account the connection $I_K = \Delta(CU)/\Delta t = CU'$ the equation for this contrar is reduced to the form

$$U'' + \frac{1}{LC} U = 0.$$

This equation describes harmonic oscillations in the circuit, so we look for a solution to this equation in the form

$$U(t) = A \cos \omega_0 t + B \sin \omega_0 t,$$

where $A$ and $B$ are constants, and $\omega_0 = 1/\sqrt{LC}$. We will count the time from the moment the key $K$ is closed. At $t = 0$ voltage across capacitor $U(0) = 0,$

whence it follows that $A = 0$. From the initial condition $I_K(0) = I_L(\tau) = \mathcal{E} \tau/L$, on the other hand, $I_K(0) = C \frac{\Delta U}{\Delta t} \bigg|_{t=0} = B \omega_0 C$; hence $B = \mathcal{E} \tau/(\mathcal{LC} \omega_0) = \mathcal{E} \tau \omega_0$. We get the final result

$$U(t) = \mathcal{E} \tau \omega_0 \sin \left( \frac{1}{\sqrt{LC}} t \right).$$

But this is not true for any moment in time, but only in the interval $0 \leq t \leq T/4$, where $T = 2\pi \sqrt{LC}$. At $t > T/4$ the voltage across the capacitor will remain constant and equal to $\mathcal{E} \tau \omega_0$. The graph of $U(t)$ is shown in figure 9.

Problem 6. In the circuit shown in figure 10, at the initial moment of time, the switches $K_1$ and $K_2$ are open, and the capacitor is not charged. First, the key $K_1$ is closed. At the moment when the voltage on the capacitor turns out to be equal to the sum of the emf of batteries $E_1$ and $E_2$, the switch $K_2$ is closed. How long after closing the key $K_2$ will the current through the coil increase 3 times? Read the given coil inductance $L$, capacitor capacity $C$ and ratio $E_2/E_1 = 0,8$. Claim all ohmic losses.

After closing the switch $K_1$ we have a closed circuit containing the first source, coil and capacitor. Ohm's law for a given circuit at an arbitrary point in time has the form

$$E_1 - LC U_C'' = U_C,$$

where $U_C$ is the voltage across the capacitor. Let us introduce a new variable $U_C^* = U_C - E_1$, then the original equation can be written in the form

⟦folio 69⟧

---
running_head:
folio:
---

As already mentioned, an equation of this type describes harmonic vibrations:
$$U_c^* + \frac{1}{LC} U_c^* = 0.$$

Where $A$ and $B$ are constants that are found from the initial conditions, and $\omega_0 = 1/\sqrt{LC}$. Immediately after closing the key $K_1$ $U_c(0) = 0$, $U_c^*(0) = -E_1$. In addition, $U_c'(0) = U_c^*'(0) = 0$ from the condition that the current is equal to zero at the initial time. From here you can find the constants $A$ and $B$: $A = 0$, $B = -E_1$. The dependence of the voltage on the capacitor on time will have the form
$$U_c(t) = E_1(1 - \cos \omega_0 t).$$

This dependence and the time dependence of the current $(I(t))$ in the circuit are shown in figure 11.

There are two times during each oscillation period when $U_c(\tau_1) = U_c(\tau_2) = E_1 + E_2 = 1,8E_1$. It is easy to find the current strength at these moments in time - either from the dependence
$$I(t) = CU_c' = C E_1 \omega_0 \sin \omega_0 t = E_1 \sqrt{C/L} \sin \omega_0 t,$$
or from the law of conservation of energy: the work of the source with EMF $E_1 \cdot 1,8E_1$ went to increase the energy of the capacitor $C(1,8E_1)^2/2$ and the energy of the magnetic field of the coil $LI_L^2(t)/2$. In both cases
$$I(\tau_1) = 0,6E_1 \sqrt{\frac{C}{L}}, a I(\tau_2) = -0,6E_1 \sqrt{\frac{C}{L}}.$$

After closing the key $K_2$, Ohm's law for a closed loop containing a second source and coils has the form

$$U_c, I$$

Solution to this equation:
$$I_L(t) = I_L(0) + \frac{E_2 t}{L},$$

where time $t$ is absent from the moment of closing the key $K_2$. For the first case, when the key $K_2$ is closed after a time $\tau_1$ after the closure of the key $K_1$,
$$I_L(\tau_1) = I_L(0) = -0,6E_1 \sqrt{\frac{C}{L}}.$$

The minus sign reflects the fact that the same current $I_L(\tau_1)$ flowing through the coils, for a circuit containing the first source and capacitor, flows in the direction of the “action” of the EMF $E_1$ (from “+” to “-”), and for a circuit containing the second source and coils, it flows against the EMF $E_2$. Some time $t_1$ after closure $K_2$
$$I_L(t_1) = 3 \cdot 0,6E_1 \sqrt{\frac{C}{L}} = -0,6E_1 \sqrt{\frac{C}{L}} + 0,8E_1 t_1,$$
where
$$t_1 = 3 \sqrt{LC}.$$

In the second case, when the key $K_2$ closes after the time $\tau_2$ after the closure of the key $K_1$,
$$I_L(0) = I_L(\tau_2) = 0,6E_1 \sqrt{\frac{C}{L}}.$$

Then after time $t_2$ after closure $K_2$
$$I_L(t_2) = 3 \cdot 0,6E_1 \sqrt{\frac{C}{L}} = 0,6E_1 \sqrt{\frac{C}{L}} + 0,8E_1 t_2.$$

⟦folio 70⟧

---
running_head:
folio:
---

Consequently, for the second case, an increase in the current strength by 3 times occurs over time
$$t_2 = \frac{3}{2} \sqrt{LC}.$$

Exercises
1. In the circuit shown in figure 12, at the initial moment of time, the key K opens

List of readers who sent correct solutions

(For the beginning, see p. 39)

Novets) 78, 80, 82, 85-89, 91; P. Bolotskikh (Gubkin) 88-90, 92; R. Butchko (Chernivtsi) 78—82, 85, 86, 88, 89, 92; V. Bykov (Kolomna) 81, 82; G. Vazhenin (Sverdlovsk) 78-80, 85-87; G. Veigas (Vilnius) 78, 80, 81, 88, 89; A. Vikol (Nerongri) 80, 82, 85-90; A. Vlasov (Leningrad) 88, 89; A. Voronin (Stary Oskol) 88, 89; O. Vorotnikova (Krasnoisk) 79, 86, 89; G. Vyzon (Moscow) 78, 79, 81, 85, 86, 89, 92; V. Vysotsky (Kyiv) 79, 81, 82, 85-87, 89-91; K. Galichesky (Severodvinsk) 78-82, 85-92; A. Gvozdev (Riga) 89; E. Gendin (Kyiv) 78—82, 85; M. Grekhova (Yaroslavl) 81; A. Grichuk (village of Mokhro, Brest region) 78—80, 82, 85, 86, 89, 91; A. Gritsan (Novosibirsk) 91; D. Graznykh (Chelyabinsk) 78, 81, 85-92; V. Gubin (Tashkent) 81, 82; O. Gusar (Kanev) 80, 82, 85, 89, 92; R. Guskov (Mines of the Rostov region) 86; Yu. Guts (Rivne) 78—80, 82, 85, 88—90, 92; A. Davletov (Alma-Ata) 79, 80, 82, 89; A. Danilenko (Kyiv) 82; S. Demba (Stary Oskol) 87, 89; N. Demchik (Zdolbunov) 78, 80, 86, 88, 91, 92; S. Dergachi (village Malinovka BashASSR) 81; O. Dzyubenko (Kyiv) 85; S. Dobrovolsky (Dnepropetrovsk) 78—80, 82, 85, 87, 88; A. Dovank (Kyiv) 80; M. Dorokhov (Chernogolovka village, Moscow region) 79, 80, 82; 85-87, 89, 91; M. Drukhinin (Moscow) 78-82; 85, 87; A. Dubovik (Wrest) 78; D. Dushamov (Shavat) 88; D. Egorov (Pavlovo, Gorky region) 80; Yu. Eroshenko (Priyutovo settlement, BashASSR) 82; P. Zhavrid (Minsk) 79-81; A. Zhuk (Rivne) 78—80, 82, 85—90, 92; O. Zhumantsev (Shavat) 89; I. Zhuravleev (Stary Oskol) 89; A. Zborovsky (Stolin) 79; V. Zelevinsky (Novosibirsk) 88, 89; M. Zelenfroid (Bobruisk) 78, 80-82, 85-87, 89, 92; V. Zlobov (Stary Oskol) 88, 89; F. Ibraimov (Baku) 78, 81, 82, 88-92; D. Ivanov (Smolensk) 79, 82; N. Ichchenko (Kyiv) 87;

N. Ilet (Chernivtsi) 79; A. Kalashnikov (Kyiv) 78—80, 82; M. Kalinovsky (Trudovoye settlement, Primorsky region) 79, 80, 82, 85, 88, 89; T. Kalita (Kyiv) 78—80, 82, 85, 89; K. Kalozhny (Odeska) 80; A. Karpenko (Brest) 78, 81, 82, 85; A. Karpenko (Brest) 78, 81, 82, 85, 87; I. Katsman (Kyiv) 79, 82, 89; S. Kelman (Alma-Ata) 78-80, 82, 85, 87-90; Zh. Kitaeva (Chernigov) 79; K. Kladko (Kharkov) 79—82, 88; E. Klimchuk (Kuznetsovsk) 78, 79, 81, 82, 85, 86, 89, 92; M. Kovalev (Gubkin) 82, 88-92; I. Kovalets (Rivne) 85, 90, 92; S. Koval (Gomel) 78-81, 85, 88-90, 92; V. Kovalsky (Kyiv) 79, 81, 82, 85; T. Kovaluchk (Kyiv) 79, 81; M. Kolpakov (village of Pochet, Krasnoyarsk region) 78-82, 85, 87-90; D. Kolvakh (Ordzhonikidze) 87; D. Komisarenko (Vinnitsa) 78—82, 86; E. Konovalov (Kyiv) 78, 80-82; Y. Konteevsky (Kaushany) 78, 79; V. Konyshin (Rostov) 78; I. Korel (Novosibirsk) 89; V. Korolev (Moscow) 79; A. Koronovsky (Saratov) 80; V. Korchazin (Krasnoarmeysk, Moscow region) 88, 89, 91; S. Kostyuk (Kolomna) 85, 86; S. Kotkovsky (Chernivtsi) 80; Yu. Kravachts (village of Knyazhpol, Levovo region) 85, 86; N. Kronsky (Gorky) 78, 79; V. Kutuzov (Riga) 78—81, 85, 87, 89, 90, 92; A. Labunets (Odeska) 85; A. Lempert (Chernogolovka village, Moscow region) 78, 79, 81, 82, 85-87, 89-92; A. Lyanin (Moscow) 78, 85, 88, 89; V. Makarov (Kirovskoe) 89; I. Markaren (Baku) 81; D. Massino (Tashkent) 78-82; Yu. Matonin (Volsk) 80-82, 85, 87-92; I. Matsko (Kyiv) 79—82, 88, 89, 92; V. Merker (Stary Oskol) 89; R. Mizok (Rivne) 78—80, 82, 85—92; O. Miroshinchenko (Lutsk) 78-82; A. Mikhovich (Mogilev) 85, 87; A. Mshchenin (Kropotkin) 82; E. Mitsenko (Chernivtsi) 78-82, 85-92; A. Mukhin (Severodvinsk) 89, 90; V. Mytko (Leningrad) 85, 86, 89, 90, 92; T. Nasardikov (Grozny) 80; I. Nemirovskaya (Kyiv) 79, 80, 85, 89; D. Ometsinsky (Kyiv) 78-82, 85-87; A. Orlovsky (Kramatorsk) 78, 79; K. Palamaruk (For the ending see p. 75)
