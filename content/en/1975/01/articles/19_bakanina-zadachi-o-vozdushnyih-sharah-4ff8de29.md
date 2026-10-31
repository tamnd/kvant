---
id: 1975-1-bakanina-zadachi-o-vozdushnyih-sharah-4ff8de29
issue: kvant_1975_1
year: 1975
number: "1"
title: Balloon problems
authors:
  - Баканина Л. П.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 65
page_labels: 60-63
tag: PR2S
lang: en
source: kvant_digital
extraction: vision
content_sha256: a28105f2498ef39829ea1aea23d6f212ea79b340499b7b144522dc6170a1ab3f
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/19_bakanina-zadachi-o-vozdushnyih-sharah-4ff8de29.md
source_content_sha256: be3bdb7fb2c9e17d37b6cf54e7c4db9d7de9cdc8ad39eeeb178dc17b4a74f247
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

## Tasks
about balloons

L. P. Bakanina

In our age of airplanes and rockets, for which any height above the surface of the Earth is accessible, balloons, bulky, unreliable and uncontrollable, have already become a thing of the past, although once upon a time they gave a person the opportunity to take to the air. However, in some cases, balloons are very convenient, and they are still used today. For example, it is convenient to teach parachute jumping from a balloon, and meteorologists study pressure, temperature and air flows in the atmosphere using balloons.

Problems about balloons are sometimes given in entrance exams. Typically they can be divided into two types:

1) problems in which it is necessary to find the connection between the dimensions and filling of the ball and the lifting force acting on the ball at the surface of the Earth;

2) problems in which you need to determine the maximum height of the ball; in this case, some model of the atmosphere is specified, that is, the law of pressure and temperature changes with height.

Essentially, both types of problems are statics problems. To solve them, you need to be able to apply the equation of state of gases and find the equilibrium condition of a ball, which is subject to the gravitational force of the Earth and the buoyant force from the air surrounding the ball. If the buoyant force is greater than the force

⟦column⟧

gravity (the difference between these forces is called lift), the ball rises up. But as you rise, the density of the surrounding air decreases, and therefore the buoyancy force decreases, which, according to Archimedes’ law, is equal to

$$F = \rho g V,$$

where $\rho$ is the air density, and $V$ is the volume of the ball. At a certain height, the buoyant force will be equal to the attractive force - this will be the maximum height of the ball.

Let us now examine several specific problems that were proposed in different years at the entrance exams to the Moscow Institute of Physics and Technology.

Problem 1. *The spherical shell of a balloon is made of a material, the square meter of which has a mass* $b = 1$ *kg/m²*. *The balloon is filled with helium at normal atmospheric pressure. At what minimum radius does the ball lift itself? The helium temperature and the ambient air temperature are the same and equal* $0\ ^\circ\mathrm{C}$. *Molecular mass of air* $29$ *kg/kmol, molecular mass of helium* $4$ *kg/kmol*.

As the radius of the ball increases, the buoyant force increases in proportion to the cube of the radius, and the weight of the shell increases in proportion to the square of the radius. Consequently, the buoyancy force grows faster and, starting from a certain radius value, will become greater than the weight of the shell. Then the ball will begin to rise. Let us denote this shell radius by $r$. At the same time

$$\rho_\text{в} \cdot g\ \frac{4}{3}\ \pi r^3 = bg \cdot 4\pi r^2 + \rho_\text{Не} \cdot g\ \frac{4}{3}\ \pi r^3,$$

where

$$r = 3\ \frac{b}{\rho_\text{в} - \rho_\text{Не}}\,.$$

The densities of air $\rho_\text{в}$ and helium $\rho_\text{Не}$ under given conditions will be found using the Mendeleev-Clapey law

rona $pV = \frac{m}{\mu} RT$:

$$\rho_\text{в} = \frac{m}{V} = \frac{p\mu_\text{в}}{RT},$$

$$\rho_{\mathrm{He}} = \frac{p\mu_{\mathrm{He}}}{RT}; \quad \rho_\text{в} - \rho_{\mathrm{He}} = \frac{p}{RT}(\mu_\text{в} - \mu_{\mathrm{He}}).$$

Finally we get

$$r = \frac{3b \cdot RT}{p\,(\mu_\text{в} - \mu_{\mathrm{He}})} \approx 2{,}8\ \textit{м}.$$

Problem 2. *The volume of the balloon is $V = 230$ m³, the mass of the shell is $M = 145$ kg. The balloon is filled with hot air at normal atmospheric pressure. What temperature must the air inside the shell be for the ball to begin to rise? Outdoor temperature $t_0 = 0\ ^\circ\mathrm{C}$.*

When air is heated, its density decreases, since $\rho = \frac{p\mu}{RT}$ (see problem 1). The ball will begin to rise if $\rho_0 gV \geqslant Mg + \rho gV$ ($\rho_0$ is the density of the outside air). Substituting expressions for the density of external air and air inside the ball $\rho$, we obtain

$$\frac{pV\mu}{R}\left(\frac{1}{T_0} - \frac{1}{T}\right) \geqslant M.$$

From here

$$1 - \frac{T_0}{T_{\min}} = \frac{MRT_0}{\mu pV} \approx 0{,}5,$$

Means,

$$T_{\min} \approx 2T_0 = 546\ ^\circ\mathrm{K} = 273\ ^\circ\mathrm{C}.$$

Problem 3. *To hold a meteorological balloon with a mass of $M = 20$ kg on the surface of the Earth, it is necessary to apply a force of $F = 1000$ N. The ball rises to a height where its volume doubles. The air temperature measured at this altitude using a probe turned out to be $t = -43\ ^\circ\mathrm{C}$. Calculate the air pressure at this altitude if the pressure on the Earth's surface is $p_0 = 754$ mmHg. Art., and temperature $t_0 = +17\ ^\circ\mathrm{C}$.*

⟦column⟧

The equilibrium condition of a ball at the Earth's surface is written as follows:

$$F = \rho_0 gV - Mg, \qquad (1)$$

where $V$ is the volume of the ball at the surface of the Earth, and $\rho_0 = \frac{\mu p_0}{RT}$ is the air density. In this case, the mass of the ball $M$ includes the mass of the shell, instruments and gas enclosed inside the shell. From the condition it is known that the volume of the ball increases as it rises. Consequently, the shell of the ball is soft and airtight. The volume increases because, with a soft shell, the gas pressure inside must be the same as the pressure of the surrounding air, which decreases with altitude. If the shell is sealed, the mass of the ball does not change as it rises and the maximum height of its rise is determined by the condition

$$\rho g \cdot 2V = M\mathbf{g}, \qquad (2)$$

where $\rho = \frac{\mu p}{RT}$. Solving equations (1) and (2) together, we find

$$p = p_0\,\frac{T}{2T_0\,(1 + F/Mg)} \approx 79\ \textit{мм рт. ст.}$$

Problem 4. *A probe ball filled with hydrogen has a sealed shell of constant volume $V = 50$ m³. The mass of the ball including hydrogen is $M = 5$ kg. Determine to what maximum height he can rise if it is known that atmospheric pressure decreases by half every $h = 5$ km of altitude. Temperature in the stratosphere $t = -60\ ^\circ\mathrm{C}$. The molecular weight of air is 29 kg/kmol. Pressure at the Earth's surface $p_0 = 1$ atm.*

At maximum height, the buoyancy force is equal to the weight of the balloon:

$$Mg = \rho gV.$$

Expressing the density of the surrounding air in terms of pressure and temperature, we obtain

$$M = \frac{\mu p}{RT}\,V.$$

Thus, the air pressure is

⟦folio 61⟧

this height is equal to

$$p = \frac{M}{\mu}\,\frac{RT}{V} \approx 6{,}12\cdot10^3\ н/м^2.$$

Now let's see how many times the pressure $p$ is less than the pressure at the Earth's surface $p_0$: $\frac{p_0}{p} \approx 16$.

From the condition it is known that the pressure drops by half every $5\ км$ rise, that is $p_0/p = 2^{H/h}$, where $H$ is the height of rise, and $h = 5\ км$. In our case

$$2^{H/h} = 16 = 2^4.$$

From here

$$H = 4h = 20\ км.$$

Problem 5. *The inextensible shell of a probe ball of volume $V = 75\ м^3$ has a small hole in the lower part. Shell mass $m = 7\ кг$. The ball is filled with hydrogen. Determine to what maximum height this balloon can rise if it is known that atmospheric pressure decreases by half every $h = 5\ км$ altitude. The air temperature in the stratosphere is $t = -60\ °C$, the temperature of hydrogen is equal to the temperature of the surrounding air. Pressure at the Earth's surface $p_0 = 1\ атм$.*

This problem differs from the previous one in that the shell of the ball is not sealed, but has a hole. Consequently, the pressure inside the ball is always equal to the pressure in the atmosphere, and as the height of the ball increases, hydrogen flows out of the hole. We assume that the rise occurs quickly enough and we can neglect the diffusion of air into the shell, then the condition for the equilibrium of the ball at the maximum height

$$mg + \rho_{\mathrm{H}_2}gV = \rho_{\mathrm{в}}gV.$$

The densities of hydrogen and air can be found from the Mendeleev-Clapeyron equation:

$$\rho_{\mathrm{H}_2} = \frac{\mu_{\mathrm{H}_2}\,p}{RT}, \qquad \rho_{\mathrm{в}} = \frac{\mu_{\mathrm{в}}p}{RT}.$$

Thus, the pressure at maximum

⟦column⟧

low altitude

$$p = \frac{mRT}{(\mu_{\mathrm{в}} - \mu_{\mathrm{H}_2})\,V} \approx 6{,}12\cdot10^3\ н/м^2.$$

The ratio is $\frac{p_0}{p} = 16$, and therefore the lifting height is $H = 20\ км$ (see the solution to the previous problem).

The lifting height in problem 5 turned out to be the same as for the sealed ball in problem 4, but we should not forget that we considered different balls, with different volumes and masses. And if both balls are exactly the same and differ only in that one has a sealed shell, and the other has a hole, which of the balls will rise higher in this case?

The buoyant force will be the same for both balls since their volumes are equal. If the initial masses of the balls were the same, then after the rise the ball with the hole will be lighter, since part of the gas filling it will flow out during the rise. Consequently, a ball with a hole will be able to rise to a greater height.

Usually, to a person thinking about this question for the first time, this result seems strange. The question is often asked: “How does lifting force arise in a ball with a hole? After all, from below, where the hole is, the air and gas inside the ball are in equilibrium.”

Let's look at the top point of the ball. If at the bottom point of the ball the pressure of air and gas is $p_0$, at the top point the air pressure is $p_1 = p_0 - \rho_{\mathrm{в}}gh$, and the gas pressure is $p_2 = p_0 - \rho_{\mathrm{г}}gh$ ($h$ is the height of the ball). If $\rho_{\mathrm{г}} < \rho_{\mathrm{в}}$, then $p_2 > p_1$ and, therefore, a greater force acts on the shell from below than from above - a lifting force arises. It is easy to verify (you can do this yourself for a body of a fairly simple shape) that it is this pressure difference that gives the resulting buoyancy force, determined by Archimedes’ law. Confusion often arises because when calculating gas density

⟦folio 62⟧

inside the ball, the pressure in the ball is usually considered to be the same everywhere. We must not forget that this is just an approximation. If we define the quantity itself

$$p_2 = p_0 - \rho_\mathrm{г}gh,$$

then, since $h$ is small - only a few meters, $\rho_\mathrm{г}gh \ll p_0$, and we can count $p_2 \approx p_0$. If we are interested in the difference

$$p_2 - p_1 = \rho_\mathrm{г}gh - \rho_\mathrm{в}gh,$$

then here both terms are the same in order of magnitude, and both of them must be taken into account. By the way, the fact that we consider $\rho_\mathrm{в}$ and $\rho_\mathrm{г}$ constant is also an approximation; in fact, they decrease with height as the pressure decreases. But taking this circumstance into account would give a much smaller correction to the buoyancy force; this correction can be neglected.

Exercises

1. Determine the lifting force of a balloon containing $m$ g of hydrogen. The shell of the ball is sealed and made of lightweight, inelastic material that can stretch freely.

2. By how many degrees must the air inside a balloon communicating with the atmosphere, whose spherical shell has a diameter of 10 *m* and weighs 10 *kg*, be heated in order for the balloon to take off? Atmospheric pressure 735 * mm. Hg st.*, ambient temperature $+27\ ^\circ\mathrm{C}$.

3. A balloon is a constant-volume balloon filled with helium. Through a hole in the lower part the ball communicates with the atmosphere. How will the maximum height of the balloon change if helium is heated to a temperature of $T_1$? The temperature of the atmosphere is considered constant and equal to $T_0$, and the pressure varies according to the law $p = p_0\,(1 - ah)$, where $a$ is a constant, $h$ is the height of rise, $p_0$ is the pressure at the Earth’s surface.

⟦column⟧
