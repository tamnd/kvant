---
id: 1978-11-zemlyakov-orlov-trehfaznyiy-tok-913badfa
issue: kvant_1978_11
year: 1978
number: "11"
title: Three-phase current
authors:
  - Земляков А. Н.
  - Орлов В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 35
page_last: 38
page_labels: 33-36
tag: JXFS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 61cba924a57893fae93c0dfa76fe4a3d1728bf6f147d7fca57d580870b67532d
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/15_zemlyakov-orlov-trehfaznyiy-tok-913badfa.md
source_content_sha256: da219adb2950d17715526b80ea1d0952ffff6d46dcaefcb5e4c07ccd31a24ed0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

and the same frequency $\omega$ and amplitude $A$, but differ in phases so much that the ends of their vector diagrams form a regular triangle (see $\triangle P_1P_2P_3$ on Fig. 3).

The voltage between two “phases” (for example, between the first and second) is also a harmonic oscillation. It is equal to the difference between the harmonic oscillations corresponding to these phases. Therefore, its vector diagram is the difference between the vector diagrams $\overrightarrow{OP}_1$ and $\overrightarrow{OP}_2$ (Fig. 3). This means that the amplitude $A_{12}$ of this direction is equal to the length of the side of a regular triangle $P_1P_2P_3$. The amplitude $A_{10}$ of the direction between the “phase” (say, first) and “zero” is the length of the vector $\overrightarrow{OP}_1$, that is, $\frac{2}{3}$ of the height of the regular triangle $P_1P_2P_3$.

Thus, the ratio of the amplitude $A_{12}$ to $A_{10}$ is equal to the ratio

$$\frac{220}{127} \text{ равно } \sqrt{3} \text{ только при } 6 \text{ и жено. Отсюда вытекает, что если первое направление в цепи равно в точности } 220 \text{ В, то второе равно } 127 \text{ В, а } \frac{220}{\sqrt{3}} \text{ В. В результате же сети случайные отклонения направления все равно преосходят } \left| \frac{220}{127} - \sqrt{3} \right|.$$

A. Zemlyakov, B. Orlov

Three phase current

Industrial generators (for example, those installed at hydroelectric power plants) actually provide not just alternating current (i.e., a current varying according to the harmonic law $i(t) = A \cos(\omega t + \varphi)$), but a current with three phases. In the first part of the note, we will discuss how such a “three-phase” current is obtained, and in the second, why it is suitable for use in electric motors. As in the previous note, the same mathematical example plays a decisive role here: the addition of vector diagrams of harmonic oscillations.

1. Alternators

If the wiring frame rotates uniformly in a uniform magnetic field, then the flux of magnetic induction through the frame changes according to a harmonious law:

$$\Phi(t) = (\vec{B} \cdot \vec{n}) \cdot S = BS \cos \omega t,$$

where $\vec{B}$ is the magnetic induction vector, $S$ is the area limited by the frame,

⟦folio 34⟧

Fig. 1.

Fig. 2.

Fig. 3.

$\vec{n}$ is the unit norm to the plane of the frame, which rotates with angular velocity $\omega$ and at time $t$ forms an angle $\omega t$ with the vector $\vec{B}$; we believe that the rotation axis of the frame is perpendicular to the vector $\vec{B}$ (Fig. 1). As a result of the action of the Lorentz force, free charges moving in the field together with the frame begin to move along the conductors of the frame, in which an induced emf will arise equal to

$$e = -\Phi'(t) = \omega BS \sin \omega t.$$

The voltage between the ends of the frame will also change according to the harmonic law, and in accordance with the closed circuit, an alternating electric current arises:

$$i(t) = I \cos(\omega t + \varphi).$$

This is the simplest model of a power generation generator (cf. Physics 10, § 21).

In industrial generators, it is not the frame that rotates, but the magnetic field, and the EMF is created in a stationary winding, and in fact in three identical windings located at an angle $120^\circ$ to one another (Fig. 2). This leads to the fact that the resulting electrical oscillations are out of phase relative to each other by $2\pi/3$ - to the right, for the induced emf we can write:

$$e_1 = \sin \omega t,$$
$$e_2 = \sin \left(\omega t + \frac{2\pi}{3}\right),$$
$$e_3 = \sin \left(\omega t + \frac{4\pi}{3}\right)$$

(explain). The corresponding current system is called *three-phase*; it was proposed in 1888 by the Russian electrical engineer M. O. Dolivo-Dobrovolsky and is now used all over the world. Why is a three-phase current system needed? What are the benefits?

First of all, we will explain how the load is connected to a three-phase generator. If equal loads are connected to all these windings (Fig. 3a), then the current amplitude in all three circuits will be the same

⟦folio 35⟧

and the same:

$$i_1 = I \cos(\omega t + \varphi),$$
$$i_2 = I \cos(\omega t + \varphi + \frac{2\pi}{3}),$$
$$i_3 = I \cos(\omega t + \varphi + \frac{4\pi}{3}).$$

Adding these harmonic oscillations using vector diagrams *) (Fig. 4), we obtain: $i_1 + i_2 + i_3 = 0$. Therefore, if wires $X$, $Y$ and $Z$ are combined into one wire (as on figure 36), then the current in it will be zero! This is exactly how current is transmitted from three-phase generators - along those lines $A$, $B$, $C$ and through the neutral wire 0. With a symmetrical load (as above), a neutral wire is not needed, but if the fragment is not symmetrical, as, for example, in a lighting network in houses (Fig. 5), then a small wire will appear in the neutral wire "compensation" current.

The main advantage that the three-phase current system provides is the simplicity of three-phase electric motors, the operating principles of which we will now consider.

2. AC motors

Let an alternating current of frequency $\omega$ flow through the winding $L$. Then it creates an alternating magnetic field, which causes the axis of the winding $L$ (Fig. 6) to be approximately uniform and directed along $n$, and the field induction also changes according to the harmonic law, so that the induction vector can be written in the form

$$\vec{B} = B \cos \omega t \cdot \vec{n}.$$

If you place a closed metal frame $K$ near the axis $n$ with an axis of rotation perpendicular to $n$ (Fig. 6), then an induction current will arise within the frame, and Ampere forces will act on it (“Physics 9”, paragraph 120),

*) See “Physics 10”, § 26; “Algebra and beginnings of analysis 10”, paragraph 82, ex. 69-70; «Kvant», 1976, No. 11, art. "Addition of harmonic vibrations."

⟦folio 36⟧

directed perpendicular to the directional current and vector $\vec{B}$. These forces create a torque that turns the frame around its axis. However, in a position where the frame is perpendicular to the $n$ axis, this torque is zero; In order for the rotation to begin, it is necessary to remove the frame from this position - use the calculated frame will pass through this position by inertia, although unevenly, it will rotate. These are the operating principles of a single-phase alternating current electric motor.

It turns out that if a three-phase current is connected to those windings located at an angle $120^\circ$ to one another, as shown in figure 7, then the magnetic field licks the 0 intersection of the symmetry axes of the windings of constant magnitude and will rotate uniformly with an angular velocity $\omega$.

To justify this, we find the sum $\vec{B} = \vec{B}_1 + \vec{B}_2 + \vec{B}_3$ of the magnetic induction vectors created by the currents in the windings $AX, BY, CZ$:

$$\vec{B}_1 = B \cos \omega t \cdot \vec{n}_1,$$
$$\vec{B}_2 = B \cos \left( \omega t + \frac{2\pi}{3} \right) \cdot \vec{n}_2,$$
$$\vec{B}_3 = B \cos \left( \omega t + \frac{4\pi}{3} \right) \cdot \vec{n}_3,$$

where $\vec{n}_i$ is the corresponding unit normal. Let us introduce a coordinate system on the plane passing through the axes of the windings, directing the axis $Ox$ along the vector $\vec{n}_1$; the coordinates of the vectors $\vec{n}_2$ in this system will be (see Fig. 8)

$$\vec{n}_1 = (1; 0),$$
$$\vec{n}_2 = \left( -\frac{1}{2}; -\frac{\sqrt{3}}{2} \right),$$
$$\vec{n}_3 = \left( -\frac{1}{2}; \frac{\sqrt{3}}{2} \right).$$

Using the formulas for the vectors $\vec{B}_i$, the sums $\vec{B}_1 + \vec{B}_2 + \vec{B}_3 = \vec{B}$ are found from here:

$$B_x = B \cos \omega t - \frac{1}{2} B \cos \left( \omega t + \frac{2\pi}{3} \right) - \frac{1}{2} B \cos \left( \omega t + \frac{4\pi}{3} \right),$$
