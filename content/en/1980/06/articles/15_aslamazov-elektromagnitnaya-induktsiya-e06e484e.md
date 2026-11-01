---
id: 1980-6-aslamazov-elektromagnitnaya-induktsiya-e06e484e
issue: kvant_1980_6
year: 1980
number: "6"
title: Electromagnetic induction
authors:
  - Асламазов Л. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 43
page_labels: 36-41
tag: MLXS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1be72f58f9c942984daaba9a47d6f6b47b7c84cd40cb0c592bab34cf637c0480
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/15_aslamazov-elektromagnitnaya-induktsiya-e06e484e.md
source_content_sha256: 1fb392abfb457ca70b25c37b5557be7e9918015909c25b4a5a5d2c15cda6e169
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

L. Aslamazov

Electromagnetic induction

Induction EMF in moving conductors

When a conductor moves in a magnetic field, an electromotive force of induction arises in it

$$\mathcal{E}_i = |\vec{B}|l|\vec{v}| \sin \alpha,$$

(1)

where $\vec{B}$ is the magnetic field induction, $l$ is the length of the conductor, $\vec{v}$ is its speed, $\alpha$ is the angle between the direction of movement of the conductor and the magnetic field*). In the case of an open conductor, a potential difference appears at its ends equal to the induced emf. When the conductor is shorted to an external circuit, an induction current will occur.

Task 1. A metal rod scolcite with a constant speed $\vec{v}$ along conducting rails in a magnetic field with induction $\vec{B}$ perpendicular to the plane of the rails (Fig. 1). The ends of the rails are connected to a conductor with resistance $R$ and a capacitor $C$. Assuming that the resistance of the rails and the rod is negligible, find the current in the conductor and the charge on the capacitor. Distance between rails $l$.

Since the moving rod, conductor and capacitor are connected in parallel, the EMF induction is large

$$\mathcal{E}_i = |\vec{B}| \Delta r |\vec{v}_r| = |\vec{B}| \Delta r \omega r.$$

The total induced emf induced in the rod is

$$\mathcal{E}_i = \int_0^l |\vec{B}| \omega r \, dr = \frac{|\vec{B}| \omega l^2}{2}.$$

Since the resistance of the bulb can be ignored, the electric

⟦folio 37⟧

Fig. 2.

Fig. 3.

Fig. 4.

The scheme of the problem under consideration is reduced to two sources with electromotive forces $\mathcal{E}_1 = |\vec{B}| \omega_1 l^2/2$ and $\mathcal{E}_2 = |\vec{B}| \omega_2 l^2/2$ and identical internal resistances $R$. The sources are connected in parallel when the rods rotate in one direction (Fig. 4, a) and in series when rotating in different directions (Fig. 4, b). Therefore, in the first case, the current in the rods is equal to

$$I_a = \frac{\mathcal{E}_1 - \mathcal{E}_2}{2R} = \frac{|\vec{B}| l^2}{4R} (\omega_1 - \omega_2),$$

and in the second -

$$I_6 = \frac{\mathcal{E}_1 + \mathcal{E}_2}{2R} = \frac{|\vec{B}| l^2}{4R} (\omega_1 + \omega_2).$$

The potential differences at the ends of both rods are the same. For the first rod, for example, the potential difference at its ends is equal to the difference between the induced emf and the voltage drop across the resistance $R$:

$$U_a = \mathcal{E}_1 - I_a R = |\vec{B}| l^2 (\omega_1 + \omega_2)/4,$$

$$U_6 = \mathcal{E}_1 - I_6 R = |\vec{B}| l^2 (\omega_1 - \omega_2)/4.$$

Note that when the rods rotate with the same angular velocities in one direction, the current in the rods is zero (as with a parallel connection of identical sources), and when rotating in different directions, the potential difference at the ends of the rods is zero (as with a series connection of identical sources).

Change in magnetic flux and induced emf

An induced emf occurs not only when a conductor moves in a magnetic field, but also when the magnitude of the magnetic flux through a surface bounded by a conducting circuit changes. In this case, according to Farad’s law, an induced emf is induced in the circuit

$$\mathcal{E}_i = -\frac{d\Phi}{dt}.$$

Here $\Phi = |\vec{B}| S \cos \alpha$ is the magnetic flux ($\vec{B}$ is the magnetic field induction, $S$ is the surface area covered by the circuit, $\alpha$ is the angle between the induction and the normal to the surface), $\frac{d\Phi}{dt}$ is the rate of change of the magnetic flux. The “minus” sign indicates that the induced current arising in the circuit changes the magnetic flux.

The physical reasons for the occurrence of induced emf when a conductor moves and when a magnetic flux changes are different. However, formula (2) can also be used to find the EMF generated in the circuit due to the movement of the conductor in a magnetic field. (You can verify this, for example, by returning to task 1. Do it yourself.)

Problem 3. A wire coil is in a magnetic field parallel to the axis of the coil. When a magnetic field is turned on during time $\Delta t_1$, an induced emf appears in the coil

⟦folio 38⟧

tsits $\mathcal{E}_1$. What induced emf will be induced in the coil when its axis is rotated through an angle $\alpha$ in time $\Delta t_2$?

When the magnetic field is turned off, the change in magnetic flux through each turn of the coil, taken with the opposite sign, is equal to

$$-\Delta \Phi_1 = |\vec{B}| S,$$

where $|\vec{B}|$ is the absolute value of the initial magnetic field induction, and $S$ is the cross-sectional area of ​​the coil (the final value of induction is zero). In accordance with Faraday's law (2), an induced emf will arise in the coil

$$\mathcal{E}_1 = n \frac{|\vec{B}| S}{\Delta t_1},$$

where $n$ is the number of turns in the coil. From here

$$n |\vec{B}| S = \mathcal{E}_1 \Delta t_1.$$

When the coil is rotated, the magnetic flux changes due to a change in the angle between the normal to the planes of the turns, directed along the axis of the coil, and the magnetic field induction vector (Fig. 5). The initial flow is $\Phi_{\text{нач}} = |\vec{B}| S$, and after turning by an angle $\alpha$ $\Phi_{\text{кон}} = |\vec{B}| S \cos \alpha$. That's why

$$-\Delta \Phi_2 = |\vec{B}| S (1 - \cos \alpha)$$

and the induced emf arising in the coil is equal to

$$\mathcal{E}_2 = n |\vec{B}| S (1 - \cos \alpha).$$

Substituting the value of $n |\vec{B}| S$ into the last formula, we obtain

$$\mathcal{E}_2 = \mathcal{E}_1 \frac{\Delta t_1}{\Delta t_2} (1 - \cos \alpha).$$

Problem 4. A flat conducting frame is in a magnetic field with induction $\vec{B}$ perpendicular to its plane. The frame is a square on the $a$ side. Then it is: a) laid out in a rectangle with an aspect ratio of 1:2; b) calve in one line; c) there will be an excess of two squares with an area ratio of 1:4 (Fig. 6). Find the breasts flowing through the frame with each change in its shape. Frame resistance $R$.

⟦folio 39⟧

and a charge flows through the frame
$$Q_a = \frac{|\vec{B}| |\Delta S_a|}{R} = \frac{|\vec{B}| a^2}{9 R}.$$

In case b) the final area is zero, so
$$\Delta S_6 = -a^2$$

And
$$Q_6 = \frac{|\vec{B}| |\Delta S_6|}{R} = \frac{|\vec{B}| a^2}{R}.$$

In case c), the frames are bent so that the direction of the normal of one of the squares turns out to be opposite to the initial direction. Consequently, the total flux of magnetic induction in this case is equal to the difference in magnetic fluxes through the individual squares:
$$\Phi_{\text{КОН}} = |\vec{B}| (S_1 - S_2),$$
where $S_1 = (2/3a)^2 = 4/9a^2$ and $S_2 = S_1/4 = a^2/9$ are the areas of the larger and smaller squares. Then
$$\Delta S_B = \left( \frac{4}{9} a^2 - \frac{a^2}{9} \right) - a^2 = -\frac{2}{3} a^2$$

and a charge flows through the frame
$$Q_B = \frac{|\vec{B}| |\Delta S_B|}{R} = \frac{2 |\vec{B}| a^2}{3 R}.$$

Vortex electric field and its work

The reason for the appearance of an induction current in a circuit placed in an alternating magnetic field is the vortex electric field that arises in space when the magnetic field changes. This field sets electrons in motion in a conducting circuit. Unlike the electrostatic field, the work done when moving a charge along a closed circuit is not zero here: it is equal to $\beta_i$ multiplied by the magnitude of the moved charge.

Task 5. In the accelerator chamber, a thin beam of electrons uniformly distributed along the orbit moves along a circle of constant radius $R$. The magnetic flux through the plane covered by the beam increases linearly with time: $\Phi = \alpha t$. At some point in time, the magnitude of the current in the chamber accelerates and is equal to $I_0$. What will be the current $I$ after the particles make one revolution?

The magnitude of the current $I$ in the chamber is determined by the charge passing through the cross section per unit time. If the linear speed of electrons is $v$, then in time $t = 2\pi R/v$ all $n$ electrons pass through the selected cross section. Therefore the current
$$I = \frac{ne}{t} = \frac{nev}{2\pi R}.$$

The initial value of the current allows us to find the initial speed of the electrons:
$$v_0 = \frac{2\pi R I_0}{ne}.$$

An alternating magnetic field generates a vortex electric field, which accelerates electrons. During one revolution of the electron, the electric field does work
$$A = e |\beta_i| = e \left| \frac{d\Phi}{dt} \right| = e\alpha.$$
This work goes to change the kinetic energy of the electron:
$$\frac{mv^2}{2} - \frac{mv_0^2}{2} = e\alpha.$$
From here we find the final speed of electrons:
$$v = \sqrt{\frac{2e\alpha}{m} + v_0^2} = \sqrt{\frac{2e\alpha}{m} + \frac{4\pi^2 R^2 I_0^2}{n^2 e^2}}$$

EDS samonidukini

A change in the magnetic flux through a plane covered by a loop can occur due to a change in the current in the loop itself. In this case, the circuit also contains an electromotive force, which is called the EMF of samonidukini, and the phenomenon itself is called samonidukiya. The relationship between the magnetic flux $\Phi$ and the current value $I$ is determined by the formula
$$\Phi = LI,$$
where $L$ is the inductance of the circuit. Then

⟦folio 40⟧

yes, in accordance with Faraday's law (2), the self-induction emf is equal to

$$\mathcal{E}_{is} = -L \frac{dI}{dt}.$$

Problem 6. The rod slides at a constant speed $\vec{v}$ along rails located in a magnetic field with induction $\vec{B}$, peredicular to the plane of the rails (Fig. 7). The ends of the rails are closed to a solenode with inductance $L$. How much current flows through the solenoid? The resistance of the solenoid, rails and rod is negligible. Distance between rails $l$.

Since there is no voltage drop on the solenode, rails and rod, the sum of the induced emf induced in the moving rod and the self-induction emf arising in the solenode due to a change in the current in it is equal to zero:

$$\mathcal{E}_i + \mathcal{E}_{is} = 0.$$

Here $\mathcal{E}_i = |\vec{B}|l|\vec{v}|$ and $\mathcal{E}_{is} = -L \frac{dI}{dt}$.

Since the induced emf does not depend on time (the rod moves uniformly), the self-induction emf must also be constant. Therefore, the rate of change of current in the solenode is constant and equal to

$$\frac{dI}{dt} = \frac{|\vec{B}|l|\vec{v}|}{L},$$

and the current in the solenode changes linearly with time

$$I = \frac{|\vec{B}|l|\vec{v}|}{L} t.$$

Problem 7. A solenode with inductance $L$ is connected through switches $K$ to a source with constant EMF ($\text{рис. 8}$). What power does the solenoid consume from the source at the switch switching frequency $v$?

Neglect the resistance of the solenoid, source and supply wires. Consider that the key is turned off for a very short time.

When the switch is closed, a current appears in the solenode, which grows linearly with time: $I = \mathcal{E}_t/t/L$ (see solution to the previous problem). During time $T = 1/v$ the current increases to $I_{\max} = \mathcal{E}_T/L$. When the switch is opened, the current decreases to zero in a very short time (much less than $T$). The graph of current versus time is as shown in figure 9.

When the current $I$ increases, during the time $\Delta t$ the charge $\Delta Q = I \Delta t$ passes through the circuit, and during the period $T$ the charge moves

$$Q = \int_0^T I dt = \int_0^T \frac{\mathcal{E}_t}{L} dt = \frac{\mathcal{E}_T^2}{2L} = \frac{\mathcal{E}_2}{2Lv^2}$$

(this charge is numerically equal to the area of ​​the figure protected by figure 9). In this case, the source does work

$$A = Q \mathcal{E} = \frac{\mathcal{E}_2}{2Lv^2}.$$

Therefore, power consumption

⟦folio 41⟧

nct is equal
$$P = \frac{A}{T} = Av = \frac{\varepsilon^2}{2Lv}.$$
Exercises
1. The metal rod moves at a constant speed $\vec{v}$ along rails, the ends of which are closed to conductors by resistances $R_1$ and $R_2$ (Fig. 10). The rails are in a magnetic field with induction $B$, perpendicular to the plane of the rails. Distance between rails $l$. What current does the rod flow if its resistance and the resistance of the rails are negligible? How much power must be developed to move the rod at a constant speed?
2. How will the current change in a metal frame rotating in a constant magnetic field with induction directed perpendicular to the axis of rotation when the rotation speed doubles?
3. The wire square from the side $a$ moves at a speed $\vec{v}$ into the field of a permanent magnet with induction $B$, perpendicular to the plane of the square (Fig. 11). What current flows through the wiring if the resistance of the square is $R$? According to what law will the current change with time if the square is moved with constant acceleration? Neglect the inductance of the wire square.
4. The ring of superconductor, through which the current flows, is bent in the form of a figure eight, and then bent in half. How will the current in the ring change?
5. A permanent magnet is inserted into a short-circuited coil: once quickly and once slowly. Will the same charge be read across the coil in each case? Will the amount of heat generated in the coil be the same?
6. Show that the inductance of a single-layer coil is proportional to time. What is the nature of the dependence of current on time in another coil, inductively connected to the first and closed to a constant resistance?
8. At what minimum frequency can the switch be switched in problem 7 in the article if it is known that the solenoid can withstand the maximum current $I_0$?

(For the beginning, see p. 28)

82; B. Goldfarb (Moscow) 74; V. Gorbunov (Kommunarsk) 79, 80, 82-84, 86, 87; S. Gorodko (Dnepropetrovsk) 74, 76, 78, 79; A. Grizoreko (Makeeva, Donetsk region) 79, 80, 82—84, 87; I. Gruzbere (Perm) 74, 76, 78-80, 84; I. Gubin (Yerevan) 75, 76, 80, 82; A. Gullev (Moscow) 78, 80, 82, 84; M. Gundilovich (Gorodeya) 82; L. Guralnik (Zhitomir) 76, 82; A. Davoyan (Leninakan) 78, 82; M. Danilin (Novoanninsky) 75, 76, 78; I. Danilovsky (Gorky) 78-80, 82, 84; V. Dvortsova (Lipetsk) 84; I. Derebas (Magnitogorsk) 74; S. Dovbysh (Moscow) 74, 76; A. Dolinin (Vladimir) 76; A. Dremin (Chernogolovka village, Moscow region) 78, 80, 82; Yu. Eliseev (Velikie Luki) 80, 82; I. Elishevich (Chernigov) 75, 76, 79, 80, 82; E. Zheltsovskaya (Moscow) 74—76, 83, 84, 87; I. Zhitenev (Chernogolovka village, Moscow region) 74, 76, 78-80, 82-84; V. Zhordichkin (Orsk) 80, 82, 84; A. Zanevsky (Lenin-grad) 78-80, 82; A. Zakharyan (Chernigov) 75, 76; M. Zeifman (Vologda) 74, 76, 78-80, 82-84; I. Zilberbere (Alma-Ata) 80, 82-84; S. Zinevsky (village of Khoroshoe, Ocherigov region) 84; A. Zolotykh (Kursk) 82; V. Zubko (Ivano-Frankivsk) 79, 80, 82; I. Ivanov (Saratov) 75, 76, 78-80, 82-84, 87; V. Ivakhenenko (Kyiv) 83; V. Izerenin (Novosibirsk) 78, 84; V. Izrailit (Dnepropetrovsk) 75, 80, 82, 84; A. Izralits (Tbilisi) 75; O. Isupova (Orenburg) 76; A. Kanel (Moscow) 74-76; V. Katin (Zhitomir) 75, 76, 78, 79, 82-84, 86, 87; E. Kafarov (Baku) 80; A. Klink (Kovrov) 76, 82; E. Kozan (Dnepropetrovsk) 75, 76, 78-80, 82-84, 86; A. Kozhevnikov (Dnepropetrovsk) 76, 78—80, 82; G. Kozhoridze (Telvi) 82-84, 86; V. Kozlovsky (Novolukoml) 75, 76, 78-80, 82, 84, 86, 87; A. Koldorkin (Kuibyev) 74-76; G. Kolomotsez (Sumgant) 74-76, 78-80, 82-84, 87; V. Komov (Alexandrov) 74-76, 78-80, 82-84, 87; V. Konshin (Rostov-on-Don) 84; V. Korobov (Kirovograd) 74, 76, 80, 83, 84; G. Korotkov

(For the end see p. 56)
