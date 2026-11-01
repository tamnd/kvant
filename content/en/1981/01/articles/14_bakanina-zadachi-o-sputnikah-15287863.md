---
id: 1981-1-bakanina-zadachi-o-sputnikah-15287863
issue: kvant_1981_1
year: 1981
number: "1"
title: Problems about satellites
authors:
  - Баканина Л. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 47
page_labels: 43-45
tag: EKY7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7b4fc1e7ca05edc2e0d4fa16f966b0a93d412ad6754e51d9826af34a1b3374c1
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/14_bakanina-zadachi-o-sputnikah-15287863.md
source_content_sha256: 6dc1f366dfb369440d88b8174540f2769d3dda5e30cbda373ac934c616e362ab
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

L. Bakanina

Problems about satellites

October 4, 1957 is rightfully considered the beginning of a new century in the exploration of the Cosmos. The launch of the first artificial Earth satellite opened up previously unimaginable spaces for scientific research. Research into space exploration has emerged without the possibility of an atmosphere. Man got the opportunity to look at his home planet in a new way, from a different perspective: on its surface, atmosphere and even depths.

Artificial satellites gave rise to many problems associated with their own motion, and caused a new wave of interest in issues that were dealt with by Kepler, Galileo, and Newton.

Accurately calculating the motion of a satellite is an extremely difficult task. However, as a first approximation, it coincides with the problem of interaction of two bodies. These are the tasks that will be considered in this article.

Let us recall the basic physical laws that need to be known when solving problems about the motion of satellites.

First of all, this is the law of universal gravity - any two material points pull each other with a force $\vec{F}$, directed along the line connecting them, and in absolute value directly proportional to their masses $m_1$ and $m_2$ and inversely proportional to the square of the distance $r$ between them:

$$|\vec{F}| = G \frac{m_1 m_2}{r^2}$$

($G = 6,67 \cdot 10^{-11} \text{ m}^3 / (\text{кг} \cdot \text{с}^2)$ is the gravitational constant).

Regarding this law, an article by V. Mozhaev was published in the third issue of «Kvant» for 1980. It was shown, in particular, that the potential energy of the graviton interaction of bodies is equal to

$$E_p = -G \frac{m_1 m_2}{r^2}$$

that is, it is negative and inversely proportional to the distance between the bodies. Knowledge of this expression goes beyond the scope of the school curriculum, but sometimes turns out to be very useful in solving problems. Well known formula for change in potential energy

$$\Delta E_p = mg\Delta h$$

is part of the above general formula. It is valid if we consider the interaction of a body of mass $m$ with the Earth, and the body is located near the Earth’s surface and moves to a height $\Delta h$, small compared to the radius of the Earth. In this case

$$\Delta E_p = \left( -G \frac{m M_3}{R_3 + \Delta h} - \left( -G \frac{m M_3}{R_3} \right) \right) = \frac{G M_3 m \Delta h}{(R_3 + \Delta h) R_3} \approx m \frac{G M_3}{R_3^2} \Delta h.$$

But, as follows from the law of universal gravity, the acceleration of free fall on the surface of the Earth is equal to

$$g = G M_3 / R_3^2.$$

So really

$$\Delta E_p = mg\Delta h.$$

In addition to the law of universal gravitation, one should remember Kepler’s laws -

1) each planet moves along an ellipse, at one of the focuses of which is the Sun;
2) the radius vector of the planet describes equal areas in equal periods of time;
3) The squares of the planets' orbital periods are treated as the cubes of the semimajor axes of their orbits.

⟦folio 44⟧

These laws, obtained by processing the results of many years of observations by the Danish astronomer Tycho Brahe, are also valid for satellites. So, for example, for a satellite moving around the Earth, the Earth acts as the Sun, and the satellite acts as a planet.

Let us now consider several specific problems.

Problem 1. Show that the period of a satellite orbiting a planet in close proximity to its surface depends only on the average density of the planet. Calculate the period of such a satellite for a neutron star, assuming that the density of a neutron star is of the order of the density of atomic nuclei $Q = 10^{17}$ ke/m$^3$.

The force of gravity between the satellite and the planet imparts centripetal acceleration to the satellite:

$$G \frac{mM}{r^2} = m\omega^2 r,$$

where $m$ is the mass of the satellite, $r$ is its distance to the center of the planet, approximately equal to the radius of the planet, $M = 4/3\pi r^3$ is the mass of the planet. From here we can find the angular velocity $\omega$, and therefore the period $T$ of the satellite’s revolution:

$$T = \frac{2\pi}{\omega} = \sqrt{\frac{3\pi}{G\omega}}.$$

For a neutron star companion $T \approx 1,2 \cdot 10^{-3}$ s.

Problem 2. Determine the ratio of the mass of Mars to the mass of the Earth according to the orbital parameters of the Soviet automatic station “Mars-2”: maximum distance from the surface (at the apocenter) $a = 25000$ km, minimum (at the apocenter) $p = 1380$ km, orbital period $T = 18$ and 00 min. The radius of Mars is $r_M = 3400$ km, the radius of Earth is $r_3 = 6400$ km.

From the conditions of the problem, the period $T$ and the length of the semimajor axis $a_M = 2r_M + a + p = 33180$ km of the ellipse along which the automatic station “Mars-2” moves are known. It is easy to calculate the periods $T_3$ and $T_M$ of satellites rotating in circular orbits

near the surface of the Earth and Mars, and compare all three periods.

For the Earth satellite you can write

$$G \frac{m_c M_3}{r_3^2} = m_c \frac{4\pi^2}{T_3^2} r_3,$$

where

$$\frac{T_3^2}{(2r_3)^3} = \frac{\pi^2}{2GM_3}.$$

For a similar satellite of Mars

$$\frac{T_M^2}{(2r_M)^3} = \frac{\pi^2}{2GM_M}.$$

According to Kepler's third law

$$\frac{T_M^2}{T^2} = \frac{(2r_M)^3}{a_M^3}.$$

Thus, from the last three equalities we obtain

$$\frac{4\pi^2}{T_3^2} r_3 = g,$$ and $T_3^2 = \frac{4\pi^2 r_3}{g}$.

So, finally

$$\frac{M_M}{M_3} = \frac{\pi^2 a_M^3}{2r_3^2 g T^2} = 0,11.$$

Task 3. An artificial Earth satellite is launched from the equator and is flying in a circular orbit in the direction of the Earth. Find the ratio of the radius of the satellite's orbit to the radius of the Earth, at which the satellite periodically passes over the launch point exactly every other day.

Since the angular velocity of the satellite $\omega_c$ can be either greater or less than the angular velocity of the Earth $\omega_3$, two solutions to the problem are possible.

1) Let $\omega_c > \omega_3$, then

$$(\omega_c - \omega_3) 2T_3 = 2\pi,$$

$$\omega_3 = \frac{2\pi}{T_3} \text{ и } \omega_c = \frac{3\pi}{T_3}$$

(here $T_3$ - one day - period

⟦folio 45⟧

formation of the Earth around its axis).
According to Newton's second law,
$$G \frac{m_c M_3}{r^2} = m_c \omega_c^2 r.$$

Substituting here the expression for $\omega_c$ and knowing that $GM_3 = gr_3^2$, we find the ratio of the radius of the satellite’s orbit $r$ to the radius of the Earth $r_3$:

$$\left( \frac{r}{r_3} \right)^3 = \frac{g T_3^2}{9 \pi^2 r_3} \approx 130, \frac{r}{r_3} \approx 5.$$

2) Let $\omega_c < \omega_3$, then
$$(\omega_3 - \omega_c) 2T_3 = 2\pi, \omega_c = \frac{\pi}{T_3},$$
$$\left( \frac{r}{r_3} \right)^3 = \frac{g T_3^2}{\pi^2 r_3} \approx 1170, \frac{r}{r_3} \approx 10,5.$$

Problem 4. A satellite launched into a steep orbit at an altitude of $H = 500$ km above the Earth’s surface decelerates in the upper layers of the atmosphere. The angular acceleration of the satellite is $\beta = -3 \cdot 10^{-13}$ rad/s². What altitude is the satellite at after a month?

Let us denote by $T_0$ and $r_0$ the initial periods of revolution and the radius of the satellite’s orbit, and by $T$ and $r$ the period and radius of the satellite’s orbit a month after launch. According to Kepler's third law
$$\frac{T_0^2}{T^2} = \frac{r_0^3}{r^3};$$

therefore, as the orbital period increases (as the frequency decreases), the orbital radius should increase. Let's find out how much.

Let the period increase by $\Delta T$ and the orbital radius by $\Delta r$. Since the catch acceleration $\beta$ is small, we can assume that $\Delta T \ll T$ and $\Delta r \ll r$. From equality
$$T_0^2 (r_0 + \Delta r)^3 = (T_0 + \Delta T)^2 r_0^3,$$
neglecting all powers $\Delta T / T$ and $\Delta r / r$, except the first, we obtain
$$2 \frac{\Delta T}{T_0} = 3 \frac{\Delta r}{r_0}.$$

The rotation period $T$ is associated with the angular velocity $\omega$ by correspondence $T = 2\pi / \omega$. Let's differentiate it: $T'(\omega) = -2\pi / \omega^2$. Due to the smallness of $\Delta T$ and $\Delta \omega$, we will assume that $\frac{\Delta T}{\Delta \omega} = T'(\omega)$. Then
$$\frac{\Delta T}{T_0} = -\frac{\Delta \omega}{\omega_0} = -\frac{\beta t}{\omega_0}.$$

We find the initial angular velocity $\omega_0$ from the condition that at an altitude $H \ll r_3$ the centripetal acceleration of the satellite is approximately equal to $g$:
$$\omega_0^2 r_0 = g, \omega_0 = \sqrt{\frac{g}{r_0}} = \sqrt{\frac{g}{r_3 + H}}.$$
Finally
$$\Delta r = \frac{2}{3} \frac{\Delta T}{T_0} r_0 = -\frac{2}{3} \beta t (r^3 + H) \sqrt{\frac{r_3 + H}{g}} \approx 3 \text{ км}.$$
So, in a month the satellite will be at an altitude of $H' = 503$ km.

Exercises
1. An artificial Earth satellite is launched from the equator and rotates in a circular orbit in the equatorial plane in the direction of the Earth's axial rotation. The radius of the satellite's orbit is $\alpha = 3$ times the radius of the Earth $r_3 = 6400$ km. How long will it take for the satellite to pass over the launch point for the first time?
2. Calculate the first escape velocity when launching from the surface of Jupiter, if it is known that Jupiter’s satellite Ganymede rotates in an almost circular orbit with a radius of $r = 1 \cdot 10^6$ km with a period of $T = 7,15$ Earth days. The radius of Jupiter is $r_0 = 70 \cdot 10^3$ km.
3. It is known that at present the Moon is moving away from the Earth at a speed of $\vec{v} (|\vec{v}| = 3,3$ cm/year). Find the angular acceleration of the Moon. The average distance from the Moon to the Earth is $R = 3,84 \cdot 10^5$ km, the angular velocity of the Moon’s rotation around the Earth is $\omega = 2,56 \cdot 10^{-6}$ rad/s.
