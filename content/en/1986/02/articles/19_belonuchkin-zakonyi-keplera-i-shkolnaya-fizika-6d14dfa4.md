---
id: 1986-2-belonuchkin-zakonyi-keplera-i-shkolnaya-fizika-6d14dfa4
issue: kvant_1986_2
year: 1986
number: "2"
title: Kepler's laws and school physics
authors:
  - Белонучкин В. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: PFRY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0fe1dd50bc6858cb63400c85e47082360a5350a2748c7f06d5ca39e54ae832e4
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/19_belonuchkin-zakonyi-keplera-i-shkolnaya-fizika-6d14dfa4.md
source_content_sha256: e94f54e0a9a96ba23d93f8a114d4ff5a6fbcfffc4eb65cc5e0d18b71af1b32af
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Kepler's laws and school physics

Candidate of Physical and Mathematical Sciences
V. E. BELONUCHKIN

At the application exams in some challenging areas at the Moscow Institute of Physics and Technology, as well as at school physics Olympiads, there are often problems in which it is necessary to consider the movement of planets (or their satellites) and determine the corresponding parameters of their orbits. Knowledge of Kepler's laws, which is studied in a school astronomy course, can be of great help in solving such problems.

Let's remember Kepler's laws.

First law: each planet revolves around the Column in an ellipse, at one of the foci of which the Column is located.

II law: the radius vector of the planet is described by the area over the same periods of time.

III law: the squares of the periods of revolution of two planets around the Column are related as the cubes of the semimajor axes of their orbits.

If the central “luminary” is not the Column, but, for example, the Earth (or another planet) and we are interested in the movement of its satellites, we can also use Kepler’s laws. Above simple, replace the Column with the Earth, and the planets with their satellites.

In this article we will look at several problems whose solutions require knowledge of Kepler's laws. Along the way, let us recall other, in particular quantitative, information from astronomy; they can also be useful in determining the parameters of the orbits of planets, comets, and satellites.

* * *

Exactly a quarter of a century ago, on April 12, 1961, a man, speaking to you by K. E. Tsiolkovsky, “emerged from the cradle” into Space. Yuri Gagarin, the first cosmonaut on Earth, made one revolution around the globe on the Vostok spacecraft. Do you remember how long this flight was? If not, can you calculate it?

Problem 1. What is the minimum possible duration of a satellite’s flight around the Earth?

By virtue of Kepler's III law, the one that is useful in around the Earth, requiring the least time, must pass along an ellipse with a minimum semi-major axis. Obviously, such an ellipse is a circle (an ellipse with coincident foci) adjacent to the surface of the Earth.

Flight duration can be calculated in various ways. We will choose, perhaps, not the simplest method, but it is one that directly uses Kepler's laws.

Let us remember that the Earth’s natural satellite, the Moon, makes one revolution in a time (sidereal month) $T_{\text{Л}} = 27,3$ day=2.36·10⁶ s. The average radius of the Moon’s orbit is $r_{\text{Л}} = 3,84 \cdot 10^5$ km, the radius of the Earth, and therefore the radius of the “fastest” (in time) satellite trajectory is $R_3 = r_{\text{min}} = 6,38 \times 10^3$ km. It remains to suppress these data into the expression of Kepler's III law

$$\frac{T_{\text{min}}^2}{T_{\text{Л}}^2} = \frac{r_{\text{min}}^3}{r_{\text{Л}}^3},$$

and we will find

$$T_{\text{min}} = T_{\text{Л}} \left( r_{\text{min}} / r_{\text{Л}} \right)^{3/2} \approx 5,06 \cdot 10^3 \text{с} = 84 \text{мин} = 1 \text{ч} 24 \text{мин}.$$

(Note that Yu. A. Gagarin’s flight lasted 1 hour 48 minutes, that is, the Vostok spacecraft made part of more than one revolution.)

Of course, calculating the parameters of circular orbits is a relatively simple matter. We could, for example, use the escape velocity for a satellite launched from Earth and, knowing the radius of its orbit, calculate the period. But when we have to write down truly elliptical orbits that have a noticeable eccentricity, only Kepler’s laws can help us out.

Problem 2. The satellite moves around the Earth in a circular orbit

⟦folio 50⟧

Fig. 1.

dtsus $R + 3R_3$ (Fig. 1). As a result of a short-term braking effect, the speed of the satellite decreased so that it moved into an elliptical orbit touching the surface of the Earth. How long after braking will the satellite land?

Before landing, the satellite must go through an elliptical trajectory, the major half of which, as is easy to see, is equal to $2R_3$. The required braking time $\tau$ can be found not represented from Kepler’s III law, if we use the results of the previous problem:

$$\frac{(2\tau)^2}{T_{\min}^2} = \frac{(2R_3)^3}{R_3^3},$$

$$\tau = \frac{1}{2}T_{\min} \cdot 2^{3/2} = \sqrt{2}T_{\min} \approx 7,1 \cdot 10^3\text{c} \approx 119\text{мин} \approx 2\text{ч}.$$

This year, perhaps the most famous comet of the solar system, Halley’s Comet, visits the vicinity of the Sun. For the first time, scientists will be able to observe it not only with the help of an instrument located on Earth: on a rendezvous with the comet, a Soviet space rocket carries the Vega automatic station created by an international team of scientists (it will visit Venus and Comet HALLEY). Scientists will try to study in as much detail as possible the still mysterious page of space (the research program is very extensive) - after all, the next meeting of the state is only in 76 years!

Let's do a little “study” of the comet.

Problem 3. The minimum distance of Halley's comet from the Sun is $r_{\min} = 0,6$ a. e. (1 astronomical unit = 1 au = 1.5·10^8 km - the radius of the earth’s orbit). Knowing the comet's orbital period is $T=76$ years, find how far it moves from the Sun.

It is not for nothing that we chose the year as the unit of time, and the units of length as the distance from the Earth to the Sun. After all, the easiest way is to compare the parameters of the comet’s orbit with the parameters of the Earth’s orbit.

From Kepler's III law we find the semi-major orbit of Halley's comet $a$:

$$a = a_3 \left( \frac{T}{T_3} \right)^{2/3} = r_0 \left( \frac{T}{T_0} \right)^{2/3} \approx 17,9 \text{ а. е.}$$
($r_0=1$ a.u., $T_0=1$ year). Now it is not difficult to determine the maximum distance of the comet from the Sun:

$$r_{\max} = 2a - r_{\min} \approx 35,2 \text{ а. е.} \approx 5,3 \cdot 10^9 \text{ км}.$$

Problem 4. Using the information from Problem 3, estimate the maximum and minimum speeds of Halley's Comet.

The comet's perihelion orbit is many times closer to the Sun than the aphean one. Consequently, we will not make a big mistake if we assume that at near perihelion the comet moves not in an elliptical, but in a parabolic orbit. This means that at perihelion the speed of the comet is equal to the so-called second cosmic speed (or parabolic speed) relative to the Sun, that is, the minimum speed at which the comet can resist the gravitational attraction of the Sun.

It is known that the second cosmic velocity $v_{\text{II}}$ is $\sqrt{2}$ times greater than the first cosmic velocity $v_1$, calculated for the same distance from the center of attraction.*) This means that we need to know the first cosmic velocity for a distance $r_{\min} = 0,6$ a. e. from the Sun. And you can calculate it using Kepler's laws, using the Earth as a reference and the knowledge that the Earth's speed in orbit is $v_0 = 30$ km/s (if you don't remember this value, it can be calculated by dividing the length of the orbit by the length of the orbital period).

Now let's slightly transform the expression of Kepler's III law - we express the period of revolution in terms of speed and radius:

*) The derivation of this relationship can be found, for example, in the article by V.V. Mozhaev “The Law of Universal Gravitation” («Kvant», 1980, No. 3). There you can also find a method for strictly calculating our intersuccessful velocities and, with its help, make sure that we made a very small mistake.
