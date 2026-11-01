---
id: 1977-6-resheniya-zadach-m403-m405-m409-f413-f415-f417-f422-8bc0aebc
issue: kvant_1977_6
year: 1977
number: "6"
title: Solutions to problems M403, M405—M409; F413—F415, F417—F422
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 58
page_labels: 46, 49, 50, 51, 52, 53, 55, 56
tag: 3WQV
lang: en
source: kvant_digital
extraction: vision
content_sha256: e573df8a2eb71634bd1f3e8a139e9dbe531af5ba61c44d538b56cf1d8952233a
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/13_resheniya-zadach-m403-m405-m409-f413-f415-f417-f422-8bc0aebc.md
source_content_sha256: 002764d9a38eb24beb67e4a51b3fe442197d303f0d3fbea3b191a4b7c36d25f6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

F461. Each square meter of body surface, heated to a temperature of $T$, emits energy of $E = 5,67 \cdot 10^{-8} \cdot T^4$ m per unit time. At what distance from the Sun do iron dusts turn into drops if the flux density of solar radiation (energy passing through a unit area per unit time) in the Earth’s orbit is $W = 1400$ vm/$m^2$? The melting point of iron is taken to be 1535 °K, the distance from the Earth to the Sun is 150·10⁹ m.

A. Stasenko

F462. If the thermostat of an electric iron is set to the “nylon” position, then the iron periodically turns on for 10 seconds and turns off for 40 seconds. The surface of the iron is heated to a temperature of 100°C. If the thermostat is set to the “clap” position, the heater periodically turns on for 20 seconds and turns off for 30 seconds. Determine the established temperature of the iron surface in this position of the thermostat. Find the temperature to which the switched-on stove will heat up if the thermostat fails.

Assume that heat transfer is proportional to the temperature difference between the iron and the surrounding air. The temperature in the room is 20 °C.

V. Skordarov

Problem solutions

M403, M405 — M409; F413 — F415, F417 — F422

M403. Prove that if in a convex manifold a certain number of edges emerge from each vertex, then in any section of it with a plane that does not pass through any of its vertices we obtain a polygon with a certain number of sides.

It is easy to verify that our polyboundary can be colored in two colors—say, white and red—so that any two adjacent (edge-based) faces have different colors. In fact, let's arrange the polyboundary so that all its vertices are at different heights (i.e., so that no edge and no diagonal are parallel to the horizontal - see Fig. 1. Let's draw a plane through the very top of the horizontal plane. Gradually lowering this plane, we color the polygon in the required way: since an even number of faces converge at each vertex, we can choose a color near the vertex faces

Fig. 1.

⟦folio 49⟧

M408. A rectangle similar to the original ones was made from 30 loadable rectangles. What could be the line length ratio of this rectangle?

Fig. 7

Taking the length less than the side of the original (small) rectangle as one, and let its length be greater than the side by $a$ ($a > 1$). Let $A$ be the length of the larger side of the “composite” rectangle, and $B$ the length of its shorter side. Since the larger rectangle is composed of small ones whose long sides are 1 and $a$, he will find the numbers $x, y, z$ and $t$ such that $A = x + ay, B = z + at$. Moreover, the area of ​​the large rectangle is 30 times larger than the area of ​​the small one. This means that the large rectangle $A \times B$ is similar to the small one $a \times 1$ with a coefficient $\sqrt{30}$. That's why

$$\begin{cases} x + ay = \sqrt{30}a, \\ z + at = \sqrt{30}. \end{cases}$$

From here

$$a = \frac{x}{\sqrt{30} - y} = \frac{\sqrt{30} - z}{t},$$

$$yz + 30 - xt = (y + z)\sqrt{30}.$$

(*)

Since $\sqrt{30}$ is an irrational number, the last equality is only possible if $y = -z$. In turn, the equality $y = -z$ is possible only for $y = z = 0$ (after all, $y$ and $z$ are also natural numbers!). Thus, $A = x \cdot 1, B = t \cdot a$.

This means that from thirty small rectangles you can fold a large one similar to them, arranging these rectangles only as shown in figure 7: the original rectangles lie, as it were, across the large one - the larger ones are made from the smaller sides.

Substituting $y = z = 0$ in accordance with (*), we get $xt = 30$, so $x$ and $t$ are some divisors of the number 30. And, finally, the desired ratio $a = \frac{\sqrt{30}}{t}$, where $t$ is some divisor of 30: $t = 1, 2, 3, 5$.

P. Pankov

M409. 1000 numbers are written in a row in a row. Below it is a second line of numbers according to the following rule: under each number $A$ of the first line, a natural number is calculated, indicated by how many times $A$ occurs in the first line. From the second line, the third line is maximized: under each number $B$ of the second line, a natural number is calculated, indicated by how many times $B$ occurs in the second line. Then, from the third line, the fourth is wheated, the fourth is drunk, and so on.

a) Prove that a certain string is the same as the next one.

b) Moreover, prove that the 1st line coincides with the 12th.

c) Give an example of a maximum line for which the 10th line does not coincide with the 11th.

a) It is obvious that, starting from the second line, all the numbers in the table are no more than 1000. In addition, each number is no more than the one written below it. Therefore, the sum of the numbers in the third line is not less than in the second, etc.; and each of these amounts is no more than a million. Consequently, since all sums cannot increase, in every adjacent row the sums coincide, and then the rows themselves coincide.

b) Let us prove that if in the $m$th line, at $m \ge 2$, the number is different from the one written above it, then it is not less than $2^{m-2}$. Indeed, for $m = 2$ this is obvious, since all second lines are natural. Let this already be checked for all lines with numbers less than $m$. Let the number $a$ be written in the $m - 1$th line, and the number $b$, greater than $a$, be written below it. then the $m - 1$th line contains $b$ numbers equal to $a$. It is clear that in the $m - 2$th line there will be several groups of identical numbers, $a$ numbers in each group, and the numbers from different groups are different. It follows that $b$ is divisible by $a$, that is, $b \ge 2a$. In addition, at least one of the numbers in these groups is different from $a$, and hence by the indication assumption $a \ge 2^{(m-1)}-2$. So, $b \ge 2a \ge 2^{m-2}$. Our statement has been proven by indication for all $m \ge 2$. If we assume that the 11th line is different from the 12th, then some number in the 12th line will be greater than $2^{12-2} = 1024 > 1000$, which is impossible.

c) The previous reasoning suggests that:

0, 1, 2, 2, 4, 4, 4, ..., 256, 488, ..., 488;
1, 1, 2, 2, 4, 4, 4, ..., 256, 488, ..., 488;
2, 2, 2, 2, 4, 4, 4, ..., 256, 488, ..., 488;
4, 4, 4, 4, 4, 4, 4, ..., 256, 488, ..., 488;

256, ..., 256, 488, ..., 488;
512, ..., 512, 488, ..., 488

⟦folio 50⟧

(in the first line 0 and 1 appear once each, 2 - twice, 4 - four times, 8 - eight times, ..., 256-256 times, 488 appears 488 times; in the 11th line the number 512 appears 512 times and the number 488 488 times).

An interesting observation is connected with our task. Let's take some meaningful text written in letters of the Russian (or any other) alphabet. Next to each letter we will write how many times it is repeated in this text, and then we will make a table as we did before. In the example given at figure 8, the fifth column already coincides with the previous one: the fourth numeric column turned out to be the last. It turns out that for meaningful texts of different content and length, the number of non-repeating numerical columns is never less than two or more than four - examples with one or a fifth or more columns are unknown. Examples of texts with four non-repeating columns (our example) are very rare. Of course, it is possible to find a set of repeating letters such that the last numerical column in the table is, say, the tenth. From this set of letters you can even form words using all the letters; but it has not yet been possible to compose a meaningful text. Why this is so, we do not know. For now this is just an interesting observation. Try to find or compose a meaningful text such that, according to the table, the last numerical column is the first or fifth. Probably, the first task is easier: after all, the requirement is very simple - different letters must appear in the text a different number of times.

M. Serov

F413. There is an ideal blocking layer with a p-n junction. Emod layer thickness d, dielectric food grade e. Draw a graph of the intensity and placed electric field in the layer, plotting the charge density distribution in the layer maximizing as shown in figure9.

Let's consider the point $A$, located at a distance $x$ from the middle of the blocking layer (Fig. 10), and find the electric field strength at this point. Let us divide the entire layer into very thin sections of thickness $\Delta l$ and take two such sections located symmetrically relative to the middle of the layer. The selected sections form a flat capacitor with charge density $\Delta \sigma = \rho_0 \Delta l$. The voltage of the electric field created by this capacitor between its plates is equal to

$$|\Delta E| = \frac{\Delta \sigma}{\varepsilon_0 \varepsilon} = \frac{\rho_0 \Delta l}{\varepsilon_0 \varepsilon},$$

and outside the capacitor it is zero.

According to the principle of superposition, the field strength $\vec{E}$ at point $A$ is equal to the sum of the strengths of such capacitors. In this case, those capacitors whose plates are at a distance greater than $|x|$ from the middle of the layer are responsible for creating the electric field:

$$|\vec{E}| = \sum \frac{\rho_0 \Delta l}{\varepsilon_0 \varepsilon} = \frac{\rho_0}{\varepsilon_0 \varepsilon} \sum \Delta l = \frac{\rho_0}{\varepsilon_0 \varepsilon} \left(\frac{d}{2} - x\right).$$

Similarly for point $C$ coordinates $0 \geq x \geq -d/2$

$$|\vec{E}| = \frac{\rho_0}{\varepsilon_0 \varepsilon} \left(\frac{d}{2} + x\right).$$

⟦folio 51⟧

The graph of the electric field strength in the barrier layer is shown in figure 11.

Now let's find how the field potential changes. Let us choose as zero the potential of points with coordinate $x = 0$, that is, the middle of the layer. Then the potential of point $A$ is equal to the work of the electric field to move a unit positive charge from this point to the middle of the layer. The force acting on the charge during such a movement is directed opposite to the movement, therefore the work, and therefore the field potential at point $A$ are negative. The absolute values ​​of potential $\varphi_A$ are easiest to find graphically:

$$|\varphi_A| = \frac{\rho_0}{2\varepsilon_0} x^2 - \frac{\rho_0 d}{2\varepsilon_0} x.$$

(Get the expression for the potential point with coordinate $0 \geq x \geq -d/2$ yourself.) The graph of potential changes is shown in figure 12.

F414. The stiffness coefficient of rubber iron of length $l$ and mass $m$ is equal to $k$. The ring, made of emoji iron, is healed with an angular velocity of $\omega$ in the horizontal plane around the ring. Determine the radius $R$ of the healing ring.

Fig. 13.

Let us denote by $L$ the length of the healing ring ($L=2\pi R$). Let's consider a small section of the ring with length $\Delta L$. Its mass

$$\Delta m = \frac{m}{L} \Delta L.$$

The selected section at its ends is subject to two tension forces $\vec{T}$, directed along the tangent ring (Fig. 13).

Their equilibrium $\vec{F}$ is directed radially to the center of the ring and imparts a centripetal acceleration $|\vec{a}| = \omega^2 R$ to the area under consideration. From figure 13

$$|\vec{F}| = 2|\vec{T}| \sin \alpha/2.$$

Let us write down the equation of motion of the selected section:

$$|\vec{F}| = |\vec{a}| \Delta m,$$

or

$$2|\vec{T}| \sin \frac{\alpha}{2} = \omega^2 R \frac{m \Delta L}{L}.$$

Since

$$|\vec{T}| = k(L - l),$$

and at small angles

$$\sin \frac{\alpha}{2} = \frac{\alpha}{2} = \frac{\Delta L}{2R},$$

we get

$$k(2\pi R - l) \frac{\Delta L}{R} = \frac{\omega^2 m}{2\pi} \Delta L.$$

From here

$$R = \frac{l}{2\pi} \frac{1}{1 - \frac{\omega^2 m}{4\pi^2 k}}.$$

I. Slobodetsky

F415. In a simplified manner, energy can be represented as a system in which two electrons form rings around a common center—a stationary nucleus. Using this model, try to estimate the approximate dielectric capacity of a liquid

This task is undoubtedly a difficult task and even somewhat beyond the scope of the school curriculum.

According to the conditions of the Gelyan problem, the force is equal to radiation with a wavelength of $\lambda=0,06$ µm. This means that such radiation causes vibrations of electrons in the gel atom with a large amplitude (this leads to strong absorption), that is, resonance occurs. Any substance is capable of strongly absorbing radiation, the frequency of which coincides with the resonance

⟦folio 52⟧

her parts of its atoms. Hence,

$$v_{\text{pe}_3} = \frac{c}{\lambda} = 5 \cdot 10^{15} \text{ e} \mu.$$

We will assume that the electrons in the gel atom are connected to the nucleus by elastic bonds (“springs”). Knowing the resonant frequency, we can calculate the “stiffness” coefficient $k$ of such a “spring”:

$$2\pi v_{\text{pe}_3} = \sqrt{\frac{k}{m}},$$

And

$$k = 4\pi^2 v_{\text{pe}_3}^2 m \approx 9 \cdot 10^2 \text{ ke} / \text{cek}^2$$

(here $m = 9,1 \cdot 10^{-31} \text{ ke}$ is the electron mass).

If such an atom is placed in a constant electric field with the direction $\vec{E}$, then each electron will be displaced from the equilibrium position to a distance $\Delta x = \frac{e |\vec{E}|}{k}$, where $e = 1,6 \cdot 10^{-19} \text{ k}$ is the charge of the electron. The atom can be detuned like an electric dipole. Its behavior in an electric field can be characterized by a dipole moment

$$p = 2e\Delta x = \frac{2e^2 |\vec{E}|}{k}.$$

A unit volume of matter acquires a dipole moment

$$P = Np = \frac{2e^2 N}{k} |\vec{E}|.$$

Here $N$ is the concentration of atoms, which can be determined by knowing the density $\rho$ of the liquid gel and its molar mass $\mu$:

$$N = N_A \frac{\rho}{\mu} \approx 2 \cdot 10^{28} \text{ m}^{-3},$$

where $N_A = 6,02 \cdot 10^{23} \text{ mol}^{-1}$ is Avogadro’s number.

The phenomenon of the appearance of electric dipoles in a substance in an electric field is called *dielectric polarization*. The ability of a substance to polarize is quantitatively characterized by the polarization coefficient $\alpha$, which in SI units is determined from the correspondence

$$P = \alpha \varepsilon_0 |\vec{E}|,$$

where $\varepsilon_0 = 8,85 \cdot 10^{-12} \kappa^2 / (\mu \cdot m^2)$ is the electrical constant. In our case

$$\alpha = \frac{P}{\varepsilon_0 |\vec{E}|} = \frac{2e^2 N}{\varepsilon_0 k}.$$

The dielectric capacity of a substance $\varepsilon$ is related to the polarization coefficient $\alpha$ by correspondence

$$\varepsilon = 1 + \alpha = 1 + \frac{2e^2 N}{\varepsilon_0 k}.$$

Substituting here the numerical values ​​of the corresponding quantities, we find

$$\varepsilon \approx 1 + \frac{2(1,6 \cdot 10^{-19})^2 \cdot 2 \cdot 10^{28}}{8,85 \cdot 10^{-12} \cdot 9 \cdot 10^2} \approx 1,13.$$

The obtained result agrees quite well with the experimental value of the dielectric capacity of the liquid gel.

C. Goat

⟦folio 53⟧

F416*). A chalk-insulated cylinder contains 5 e of hydrogen and 12 e of oxygen. PodzhizZAIM mixture. Determine the pressure and temperature in the state if it is known that when 1 mole of water is formed, the amount of heat $Q_0=2,4.10^5$ J is released. The volume of the vessel is 100 liters. The initial temperature of the mixture of oxygen and hydrogen is $t_0=20^\circ C$. The specific temperature of water at constant volume is $c_B=14,3$ kJ/(kk.eraD), and that of water vapor is $c_\pi=2,1$ kJ/(kk.eraD).

When the mixture burns, a chemical reaction occurs
$$2H_2 + O_2 = 2H_2O,$$
as a result of which water is formed (more precisely, water vapor). In this case, 2 moles (or 4 e) of hydrogen combine with 1 mole (or 32 e) of oxygen. Since there is only 12 e of oxygen in the vessel, $\frac{4\cdot12}{32}=1,5$ e of hydrogen enters into the reaction, and $m_1=13,5$ e of water vapor is formed. The remaining $m_2=3,5$ e of hydrogen will not react and will be present in the vessel along with water vapor.

Since the molar mass of water is 18 e/mol, 13.5 e of water is $n=\frac{13,5}{18}$ mole and when the mixture is dissolved, the amount of heat released is $Q=nQ_0=1,8\cdot10^5$ J. This energy goes to increase the internal energy of water vapor and hydrogen:

$$Q=(c_\pi m_1+c_B m_2)\Delta T,$$
where $\Delta T=T-T_0$ is the change in gas temperature. From here we find $T$:

$$T=T_0+\Delta T=T_0+\frac{Q}{c_\pi m_1+c_B m_2}\approx2800\text{ ераД}.$$

According to Dalton's law, the pressure in the vessel is equal to the sum of the partial pressures of water and hydrogen:

$$p=p_\pi+p_B.$$
According to the equation of gas state,

$$p_\pi=\frac{m_1}{\mu_\pi}\frac{RT}{V} \text{ и } p_B=\frac{m_2}{\mu_B}\frac{RT}{V}.$$

Hence,

$$p=\left(\frac{m_1}{\mu_\pi}+\frac{m_2}{\mu_B}\right)\frac{RT}{V}\approx5,6\cdot10^5\text{ н/m}^2.$$

I. Slovodechkiy

F418. Adjacent window panes that are stacked together are virtually impossible to separate from each other without trying to tear one pane from the other. Why?

Fig. 14.

*) The solution problem F416 will be published in one of the upcoming issues of the journal.

Let the edges of the plates be straight lines, the thickness of the water layer between the plates be $d$. Since water wets the glass, the free surface of the water at the edges of the plates will be curved. We will assume that the water completely wets the glass. Then its free surface is part of the surface of a cylinder with cross-sectional radius $r=d/2$ (Fig. 14). The curvature of the liquid surface also leads to the fact that the pressure of the internal liquid (in the water between the plates) and the pressure outside are not the same. Let's see what the difference between these pressures is.

A thin layer of liquid applied to its free surface is subject to the force of external pressure, the force of pressure from the water, and the force of surface tension. If the length of the free surface boundary is equal to $l$ (the linear dimension of the plates), then the surface tension force is equal to $2\sigma l$, where $\sigma$ is the surface tension coefficient of the liquid. Let us write down the equilibrium condition for the liquid:

$$pld=2\sigma l+p'ld,$$

where $p$ is the external pressure, $a$ $p'$ is the pressure of the internal fluid. Hence the pressure difference, the bottlenecks. In a state of equilibrium, the plates are contained with each other in the upper butorki (Fig. 15). The resulting reaction forces acting from

⟦folio 55⟧

F420. A load of mass m is suspended on the ACBOE bracket of 6 non-vertical rigid rods of the same length, connected by hinges (Fig. 16), at point C. Is rod AB stretched or sloped? The smallest elastic force is in this rod.

Fig. 16.

Fig. 17.

Fig. 18.

F421. A thin-walled cylinder of radius R was spun to a target speed w and kept constant at an angle (Fig. 19). The coefficient of sliding friction between the walls of the wheel and the cylinder is equal to μ. Determine how many revolutions the cylinder will make before it stops.

The easiest way to find out whether a particular rod in a hinge system grows or slopes is as follows. Let’s mentally remove the inter-us core from the system and see how the rest of the system behaves. If the hinges, which were previously located at the ends of the rod in question, after its (mental) removal begin to move closer together, it means that the rod was sloped and was preventing the approach. Conversely, if these two hinges diverge, it means that we have removed the growing rod.

Using this method, it is easy to establish that in the ACBOE bracket, rods CB, BO and OA grow, and rods AC, AE and the intersex rod AB slope.

Theler let us find the numerical value of the elastic force in rod AB. First of all, we note that any rod can act on the hinge located at its end only with a force directed along the rod itself. Indeed, if this were not so, then, according to Newton’s third law, the hinge would also act on the rod with a force directed not along the rod. Such a force would create a relative axis moment through the hinge at the other end of the rod. As a result, the rod would rotate around the hinge rather than being in equilibrium.

Consider hinge C (Fig. 17). Since the rod AC slopes and BC grows, three forces act on the hinge C, making angles of 120° with each other. Since the hinge ends, all three forces must be equal modulo. However, one of them is the elastic force $F_{yпр}$of the thread on which a load of mass m hangs motionless. That's why

$$|F_{yпр}| = m|g|, \quad |F_{AC}| = |F_{BC}| = m|g|.$$

Hinge B is also acted upon by three forces that make angles of 120° with each other (Fig. 18). However, the strength is known.

This is the elastic force of the stretched rod BC: $|F_{BC}| = m|g|$. Consequently, the remaining forces applied to hinge B, namely the elastic force of the stretched rod BO and the desired elastic force of the rolled rod AB, are equal to the same. In other words,

$$|F_{AB}| = m|g|.$$

This problem can also be solved energetically. Let's assume that we managed to lengthen the rod AB by a negligible amount Δx. To do this, it was necessary to do work against the desired elastic force $F_{AB}$. This work $\Delta A = |F_{AB}| \Delta x$ increases the potential energy of the system, since the load of mass m rises. Moreover, it will rise by the same amount as the hinge C will rise. The amount of movement of the hinge C can be found from such messages. The diagonal (imaginary) OC of the rhombus OACB, passing through the middle of the rod AB, was horizontal before removing the rod AB. After removing the rod by a small amount Δx, the middle of the rod AB rose by Δx/2. Consequently, the middle of the imaginary diagonal of the rhombus also rose by Δx/2. The end of this diagonal (that is, point C) rose by Δh = 2Δx/2 = Δx. Hence $|F_{AB}| \Delta x = m|g| \Delta h$, and therefore,

$$|F_{AB}| = m|g|.$$

B. Bukhovtsev

Since the cylinder and the walls of the corner have friction, the angular speed of rotation of the cylinder decreases over time. According to the kinetic energy theorem, the change in the kinetic energy of the cylinder is equal to the work done by the forces acting on it. It is obvious that in our case the work of the friction forces $F_{тр1}$ and $F_{тр2}$ is limited (see Fig. 19). Therefore, first of all, we will not destroy these forces.

⟦folio 56⟧

The cylinder does not move forward. This means that the equal force of gravity $mg$, the reaction forces of the corner walls $\vec{N}_1$ and $\vec{N}_2$ and the friction forces $\vec{F}_{\text{тр1}}$ and $\vec{F}_{\text{тр2}}$ is zero. Project the force onto the vertical and horizontal axes and write down the corresponding equilibrium conditions:

$$|\vec{N}_1| + |\vec{F}_{\text{тр2}}| - |mg| = 0, \quad |\vec{N}_2| - |\vec{F}_{\text{тр1}}| = 0.$$

Besides,

$$|\vec{F}_{\text{тр1}}| = \mu |\vec{N}_1| \quad \mu |\vec{N}_2|.$$

From here

$$|\vec{F}_{\text{тр1}}| = \frac{\mu m |\vec{g}|}{1 + \mu^2} \quad \mu |\vec{F}_{\text{тр2}}| = \frac{\mu^2 m |\vec{g}|}{1 + \mu^2}.$$

Let the cylinder make $n$ revolutions before stopping. This corresponds to a change in the application of friction forces at a distance $2\pi Rn$. The work done by the friction forces is equal to

$$-(|\vec{F}_{\text{тр1}}| + |\vec{F}_{\text{тр2}}|) 2\pi Rn = -\frac{2\pi Rn \mu (1 + \mu) m |\vec{g}|}{1 + \mu^2}.$$

Equate this work to the change in kinetic energy of the cylinder

$$0 - \frac{m\omega^2 R^2}{2},$$

let's find $n$:

$$n = \frac{\omega^2 R (1 + \mu^2)}{4\pi \mu |\vec{g}| (1 + \mu)}.$$

◆

In a dielectric, the directional electric field is weakened by $\varepsilon$ times. Therefore, at the same charge density, directions, since they are conducting surfaces. Consequently, between any two belonging to different spheres, the potential difference must be the same. For this, obviously, it is necessary that the charge density on the lower half of the capacitor be $\varepsilon$ times greater than on the upper. In this case, the electric field in the entire capacitor will be the same as in a dielectric capacitor, but with the same charge density in the upper and lower halves.

Now let's find the EM value of the capacitor. To do this, you need to know the charge of the capacitor and the potential difference between its plates. Let us denote by $\sigma$ the charge density on the upper half of the capacitor, and by $S$ the surface area of ​​the inner sphere. Then the capacitor charge

$$q = \sigma S/2 - \varepsilon \sigma S/2.$$

As we have already said, the electric field of the internal capacitor is the same as in a dielectric capacitor, but with the same charge density $\sigma$, that is, with a uniformly distributed charge

$$q' = \sigma S.$$

Therefore, the potential difference between the plates

$$\Delta q = \frac{q'}{4\pi \varepsilon_0 r} - \frac{q'}{4\pi \varepsilon_0 R} = \frac{\sigma S}{4\pi \varepsilon_0} \frac{R - r}{rR}.$$

Dividing $q$ by $\Delta q$, we find the EM bone $C$:

$$C = \frac{q}{\Delta q} = \frac{(1 + \varepsilon) \sigma S/2}{\frac{\sigma S}{4\pi \varepsilon_0} \frac{R - r}{rR}} = \frac{2\pi \varepsilon_0 (1 + \varepsilon) rR}{R - r}.$$

I. Slovodechkiy
