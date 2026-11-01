---
id: 1983-7-meledin-zadachi-otsenki-2d361f29
issue: kvant_1983_7
year: 1983
number: "7"
title: Assessment tasks
authors:
  - Меледин Г. В.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 28
page_last: 33
page_labels: 26, 27, 28, 29, 31
tag: DP6C
lang: en
source: kvant_digital
extraction: vision
content_sha256: c1445c682f738c1635176bfe0e406a0381deaefa47ba6a1755884ac8d55f326d
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/04_meledin-zadachi-otsenki-2d361f29.md
source_content_sha256: e6bb31bd1ef48dec42ec6bd9213345f2ce32fc388b1c5566c07adf6e0d57221c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Assessment tasks

Candidate of Physical and Mathematical Sciences
G. V. MELEDIN

In everyone’s life, there are evaluations: will I be able to get there in time, will I have enough money, how long will it take to adjust the clock regulator, how much will it take to hold the load, etc.

In the activities of a researcher, assessments are necessary professionally. Rough application, estimation by order of magnitude is an almost obligatory stage in preparing an experiment, designing an installation, and theoretical development. They are indispensable in the process of discussing new ideas and projects. Sometimes estimates suggest the path to an exact solution of a problem, make it possible to establish the boundaries of the scope of application of an exact solution and understand what changes will be required when formulating and solving a problem outside this scope.

The ability to make adjustments, along with intuition, is very important in creative work. It is no coincidence, therefore, that recently assessment tasks have begun to appear in university entrance exams. For example, for several years now, every version of the written exam in physics for applicants to the Physics Faculty of Novosibirsk State University has an assessment task. In the formulation of such a problem there are no or almost no physical quantities necessary for solving the numerical values; It is assumed that everyone can choose and set them themselves.

The physical formulation of the problem, the selection and construction of the simplest physical model of the phenomenon is the most important and at the same time difficult stage in solving assessment problems. It is necessary to correctly select the physical parameters that are most significant for the problem, determining its physics, and neglect the parameters that have little effect on the interdrying phenomenon. To establish the relationship between various parameters, the correct use of basic physical laws and definitions is essential. Sometimes you can limit yourself to not very strict definitions or a qualitative interpretation of physical laws.

Before moving on to specific tasks, we will make two small remarks. First, let’s agree on what exactly we mean by the words “order of magnitude estimate.” Two numerical values ​​of any physical quantity are considered to differ by an order of magnitude if their ratio is approximately equal to 10, by two orders of magnitude if it is equal to 10², etc. From this point of view, the number 89 should be considered a number of the order of 10², and the number 15 - of the order of 10. If two values ​​differ, for example, by 1.3 times, they should be considered quantities of the same order. The same applies to the case when there is a difference of 2.3 or even 5 times. With rough estimates there is also no difference from the exact result.

Secondly, conditions about notation. Along with the equal sign “=” or the approximate equal sign “≈” we will use the sign “~”. Obviously it is used to record the fact of proportionality of two quantities. We will use this symbol to denote equality in order of magnitude, thereby emphasizing that the dimensionless proportionality coefficients in our formulas are numbers of the order of unity. Once again, we emphasize that the difference between the “true” and “estimated” coefficients is several times insignificant for ours.

⟦folio 27⟧

Now let's look at several relatively simple estimation problems. Almost all of them are taken from the entrance exams for the Faculty of Physics of NSU.

Let's start with problems in which physics is a clear subject and you just need to wisely choose specific values ​​of the corresponding physical quantities.

Task 1. Estimate the pressure of a ballpoint pen on paper when writing.

To make such an estimate, use the undefined pressure: $p = F/S$. Now we need to think about what the numerical values ​​of the force and area included in this definition are. Each line that we draw on paper while writing consists of individual points. The point can be considered a circle whose diameter is equal to the width on the left $d$ left on the paper: $S = \pi d^2/4$. Moreover, $d \sim 0,2$ mm (which is quite plausible). We will also evaluate the gain $F$ applied to the handle “by eye”: it does not exceed the weight of the hand, but is certainly greater than the weight of the handle. Let's take $F \sim 1$ N. Then

$$p = \frac{F}{S} \sim \frac{4F}{\pi d^2} \sim 3 \cdot 10^7 \text{ Pa}.$$

In order to feel whether it is a lot or a little, it is useful to compare the resulting value with some other value. Imagine that there is a weight of 1 kg on the table. Its diameter at the bottom is about 4 cm, so the weight exerts a pressure of about $8 \cdot 10^3$ Pa on the table. This means that when writing with a ballpoint hand, the pressure on the paper is several thousand times greater than the pressure of kilograms of weights standing on the table.

Task 2. Estimate the speed of the steam jet coming out of the spout of a boiling kettle.

Let the heater power be $W$, and the specific heat of water vaporization be $L$. Let us introduce one more parameter—the fraction of power $\eta$ that contributes to the formation of steam. Then $\eta W/L$ is the mass of steam that forms in each unit of time. Obviously, as much steam is formed, the same amount comes out of the kettle:

$$\frac{\eta W}{L} = \varrho v S.$$

Here $\varrho$ is the steam density during boiling, $v$ is the speed of steam flow, $S$ is the cross-sectional area of ​​the kettle spout. According to the Mendeleev-Clapeyron law, the vapor density is $\varrho = p\mu/(RT)$, where $p$ is the pressure, $\mu$ is the molar mass of water, $R$ is the universal gas constant, $T$ is the steam temperature. Finally we get

$$v = \frac{\eta W}{L\varrho S} = \frac{\eta WRT}{Lp\mu S}.$$

If the heater power is $W \sim 1$ kW, $\eta \sim 0,5$, $S \sim 1$ cm$^2$, $T \sim 373$ K, $p \sim 10^5$ Pa (since the saturated vapor pressure at the boiling point is equal to atmospheric pressure), and the constant values are equal, corresponding to $R = 8,3$ J/(kg K), $L = 4,2$ kJ/kg and $\mu = 18 \cdot 10^{-3}$ kg/mol, then

$$v \sim 2 \text{ м/с}.$$

Task 3. Estimate how many times it is brighter on a good sunny day than a night with a full moon.

First of all, we note that the Moon only reflects the light falling on it from the Sun. Let's assume

⟦folio 28⟧

Basically, the illumination created by the Sun on the Earth and on the Moon is approximately the same and equal to $E_C$. The light power $E_C \pi R^2$ hits the Moon (here $R$ is the radius of the Moon). The Moon creates illumination on Earth $E_\pi = E_C \pi R^2 k / (2\pi l^2)$, where $k$ is the coefficient of light reflection from the surface of the Moon, $l$ is the distance from the Moon to the Earth (we assume that the Moon uniformly “casts” the reflected light within a solid angle equal to half the maximum). Now let's find the illumination ratio:

$$\frac{E_C}{E_\pi} = \frac{2}{k} \left( \frac{l}{R} \right)^2 = \frac{8}{k} \left( \frac{2R}{l} \right)^{-2},$$

where $2R/l$ is the angular size of the Moon, equal in order of magnitude to 0.01 radians.

Let's take $k \sim 0,2$, then final

$$E_C/E_\pi \sim 4 \cdot 10^5.$$

Task 4. Estimate how far further the grenade will go if the athlete throws it from the sky.

Let's assume that when a grenade flies, it rises to a maximum height $H$. Then the grenade's flight time is $2\sqrt{2H/g}$. If at the initial moment the horizontal projection of the grenade speed increases by $v$, and the vertical projection remains practically unchanged, then the flight time will not change, and the flight range will increase by $l = 2v\sqrt{2H/g}$.

It is reasonable to consider $H \sim 5$ m, and $v \sim 8$ m/s (remember, for example, that sprinters run a hundred-meter dash in a time of about 10-12 s); hence $l \sim 20$ m.

The resulting estimate is quite reasonable.

Problem 5. Estimate the discharge time of a charged metal ball connected to the Earth through a resistor with a known resistance.

Let the potential of the charged ball be $\varphi$ and the charge $Q = C\varphi$, where $C = 4\pi\varepsilon_0a$ is the capacity of the ball ($a$ is the radius of the ball). After connecting with the Earth, both the potential of the ball and its charge will become zero. During discharge, a current $I$ is picked up in the circuit, which will, of course, change over time, but for the purpose of evaluation we will neglect this factor. Then we get

$$I \sim \frac{Q}{t} \sim \frac{\varphi}{R},$$

where $R$ is the resistor resistance, $t$ is the discharge time. From here

$$t \sim \frac{QR}{\varphi} = CR = 4\pi\varepsilon_0aR.$$

At $a \sim 1$ m, $R \sim 1$ MΩ and $\varepsilon_0 = 8,85 \cdot 10^{-12} \Phi/\text{м}$

$$t \sim 10^{-4} \text{ с.}$$

In Ya. I. Perelman’s “Entertaining Physics” there is a story called “Dry Out of the Water.” It begins like this: “Place the coin on a large flat plate, pour in enough water to

⟦folio 29⟧

coat the coin, and invite guests to take it directly with their hands, without getting their fingers wet.

This seemingly impossible task can be solved quite simply with the help of a glass and a burning piece of paper. Light the piece of paper, place it hot inside the glass and quickly place the glass on a plate near the coin upside down. The paper will go out, the glass will fill with white smoke, and then all the water from the plate will gather under it by itself. The coin, of course, will remain in place, and in a minute, when it has dried, you will be able to pick it up without getting your fingers wet.”

Let's solve this problem in connection with this story.

Problem 6. Estimate the minimum temperature to which the glass must be heated so that after cooling, all the water from the plate will be withered.

First, let’s solve the problem exactly (bumpwise, within the framework of some assumptions, which we’ll talk about later). When the glass is brought to the surface of the water, the air pressure in it is equal to atmospheric pressure $p_a$, and its temperature $T_x$ is unknown. When the glass cools down and a mass of water $m$ falls into it, the air pressure in it will be $p$, the temperature of the glass will be equal to the temperature $T$ of the surrounding air, and the volume will decrease by the amount of air in the water, that is, the glass will be equal to $(S_l - m/Q)$, where $S$ and $l$ are the cross-sectional area of the glass and its height, $Q$ is the density of water. According to the Mendeleev-Clapeyron law,

$$\frac{p_a S_l}{T_x} = \frac{p S (l - m/(\varrho S))}{T}.$$

From the condition of equilibrium of a column of water it follows that $pS + mg = p_aS$, then

$$T_x = T \frac{1}{1 - \frac{mg}{p_a S}} \frac{1}{1 - \frac{m}{\varrho l S}}.$$

Let us now indicate the implicit assumptions that we made in the solution. We assumed that the temperature of the air in the glass coincides with the temperature of its walls; that the glass is placed on the water slowly, so that the initial pressure in it coincides with the atmospheric pressure; that the pressure of water vapor in the glass can be neglected; that capitular effects are negligible.

It is interesting that the resulting formula for $T_x$ takes into account the change in pressure (caused by the column of water entering the glass) and takes into account the change in the volume of air in the glass of water in the form of independent components. Therefore, their influence can be studied separately.

Let's transform the first cohabitant from the right side of the indicated formula:

$$\frac{1}{1 - \frac{mg}{p_a S}} = \frac{1}{1 - \frac{p_{BO}}{p_a}} \approx 1 + \frac{p_{BO}}{p_a}.$$

Atmospheric pressure corresponds to the pressure of a water column 10 m high, and in our case it is clear that the height of a column of water poured into a glass cannot exceed the height of the glass, that is, approximately 10 cm, so it is reasonable to neglect the pressure of the water column and consider this factor approximately equal to unity:

$$\frac{1}{1 - \frac{mg}{p_a S}} \approx 1.$$

The second cohabitant is associated with a change in the volume of water in the glass. The volume of water and the volume of the glass no longer differ as much as pressure, so the volume of water cannot be neglected.

Thus,

$$T_x \approx \frac{T}{1 - \frac{m}{\varrho l S}}.$$

⟦folio 31⟧

Task 8. Estimate the time after which you will hear this after a flash of lightning, if you know that lightning struck a tree located at a distance of about 3 km from you.

Since light travels at a speed of $\approx 3 \cdot 10^5$ km/s, a lightning flash will be visible after a time of $\sim 10^{-5}$ s. The sound travels much longer. Let's try to estimate the speed of propagation of sound vibrations in the air. Let's use the dimensional method for this.

It is obvious that the speed $v$ of sound depends on the parameters characterizing this medium. Let this be pressure $p$ and density $\rho$ for air. Suppose now that $v \sim p^x \rho^y$,

where $x$ and $y$ are unknown impressions. If such a formula really exists, then the dimensions of its left and right sides must, of course, be the same.

Conditions for the dimension of a physical quantity $A$ are denoted by [A].

Then

$$v = m \cdot c^{-1},$$

$$p = \Pi a = \kappa \Gamma \cdot m^{-1} \cdot c^{-2},$$

$$\rho = \kappa \Gamma \cdot m^{-3},$$

and you can write

$$m \cdot c^{-1} = (\kappa \Gamma \cdot m^{-1} \cdot c^{-2})^x (\kappa \Gamma \cdot m^{-3})^y.$$

This equality holds provided that

$$x + y = 0,$$

$$-x - 3y = 1,$$

$$-2x = -1.$$

From here

$$x = \frac{1}{2} \text{ и } y = -\frac{1}{2},$$

by pose we get

$$v \sim \sqrt{\frac{p}{\rho}}.$$

The numerical coefficient in this formula cannot be determined from dimension messages. Let's assume that it is of order one (in general, this would need to be checked somehow).

To estimate the speed of sound, air pressure is applied to normal atmospheric pressure: $p \sim 1$ atm $\sim 10^5$ Pa, and the air density will be considered equal to the density under normal conditions: $\rho \sim 1,3$ kg/m³. Then the speed of sound

$$v \sim \sqrt{\frac{p}{\rho}} \sim 300 \text{ м/c},$$

and the time after which thunder conditions are observed,

$$t \sim \frac{3 \cdot 10^3 \text{ м}}{300 \text{ м/c}} \sim 10 \text{ с}.$$

This time is six orders of magnitude longer than the time of light propagation, which is completely reasonable from the point of view of our life experience.

In conclusion, several more assessment tasks are proposed. Previous, without looking at the answer, get the necessary assessments yourself.

Reflection Challenge

1. Estimate how atmospheric pressure will change if the water in the oceans evaporates.
2. Estimate the speed at which the parachute descends with the parachute open.
3. Estimate the average density of the Sun.
4. Estimate how many revolutions (somersaults) it will make automatically, freely falling into a kilometre-long abyss at full speed.
5. Evaluate the success of an athlete in the shot put.
6. Estimate the tension of the bike chain when riding uphill.
7. Estimate the speed with which a drop of water was traveling if, when it hits a stationary wall, it exerts an average pressure of the order of $10^6$ Pa.
8. Estimate the tension force of the seat belts holding a person in an automatic vehicle if the automatic vehicle, moving at a speed of about 30 km/h, collided with a pole, as a result of which the automatic vehicle received a dent about 30 cm deep.
9. Estimate how far the distances between the world ocean levels and the center of the Earth at the pole and equator will be.
10. Estimate at what distance a person in bright clothes, going into a pine forest, will be lost from sight. (No undergrowth.)
