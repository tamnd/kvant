---
id: 1989-8-sokolov-vechnaya-elektricheskaya-lampochka-767e2958
issue: kvant_1989_8
year: 1989
number: "8"
title: Eternal light bulb?
authors:
  - Соколов И. М.
rubric: osnovnye-stati
page_first: 4
page_last: 18
page_labels: 2, 3, 4, 5, 6, 7, 16
tag: YGDA
lang: en
source: kvant_digital
extraction: vision
content_sha256: a40add2c863d44a0a450ac8164f8371fbbb29c5553e645db39827f1ec15f7c2f
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/03_sokolov-vechnaya-elektricheskaya-lampochka-767e2958.md
source_content_sha256: c0478728570fec3da4ef35d3ce11f9d9ff0362fb9e63121f1c36dffd33fe054e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

ETERNAL ELECTRIC BULB?

Candidate of Physical and Mathematical Sciences
I. M. SOKOLOV

Let's talk about the common light bulb, the physical laws that govern its behavior, and the properties of the light bulb itself as a technical system.

A few years ago, light bulbs appeared in stores that were designed not for 220 V, but for 235 V. These light bulbs last much longer than regular ones. The reason that directly caused their appearance was a shortage of light bulbs in stores. Light bulb manufacturers sensibly (from their point of view) reasoned that the longer light bulbs last, the less often they will be bought and the less they will need to be produced.

The problem of extending the life of the lamp was solved very simply - by slightly lengthening the filament. However, people who know physics said: this is wastefulness, you can’t waste electricity like that. Why they said that, we'll talk about it a little later.

In the summer of 1986, an article appeared in Literaturnaya Gazeta about the inventor who invented the eternal light bulb. It is designed very simply. In series with the common lamp connection there is a diode (Fig. 1), which cuts off, say, negative half-cycles of the current. The light bulb operates at an effective voltage value $\sqrt{2}$ times less than the mains voltage. The idea here is the same: with a lower voltage, the light bulb lasts longer. We will see that such a light bulb is indeed practically eternal. For some formal reasons, the inventor was denied an author's certificate. But even in this case, those who know physics understood that there was no point in getting upset: the introduction of eternal light bulbs would not lead to anything good for him.

And here, finally, is a small note from the Izvestia newspaper dated December 25, 1987. This is a note about a collector who collects light bulbs. His collection also includes an Edison light bulb made in 1881. She is over 100 years old and still works. Eternal light bulb again?

Over these 100 years, television, airplanes, space rockets, ballpoint pens, refrigerators and many other technical systems, simple and complex, large and small, have appeared. I don’t want to believe that during this time mankind not only failed to improve the light bulb, but even moved away from the ideal, losing the secret of its eternity. This rather begs the question: is an eternal light bulb necessary?

To answer this, let’s look at the physical side of the matter. Why is the light on? Why does it burn out? So,

Why is the light on?

The filament of an incandescent light bulb emits light because it is heated.

All heated bodies emit electromagnetic waves. Thermal radiation contains waves of all possible lengths, and for each component (more precisely, for each interval

⟦folio 3⟧

Wavelengths) comes with its share of energy. In 1900, Max Planck derived the law of black body radiation. (We will not find out what an “absolutely black body” is; it is important for us that the filament of an accumulation lamp can be considered just such a body with sufficient accuracy, and therefore we can use Planck’s radiation law.) According to Planck’s formula, the energy emitted per unit time per unit surface area of ​​a body heated to a temperature of $T$ in the wavelength range from $\lambda$ to $\lambda + \Delta \lambda$ is equal

$$u(\lambda, T) d\lambda = \frac{2\pi h c^2}{\lambda^5} \frac{1}{e^{\frac{h c}{\lambda k T}} - 1} d\lambda.$$

In this formula, $c$ is the speed of light, $h$ is Planck’s constant, $k$ is Boltzmann’s constant. Total body emissivity

$$u(T) = \int_0^\infty u(\lambda, T) d\lambda$$

(i.e., the radiation power per unit surface area over the entire range of electromagnetic waves) depends only on temperature and obeys the Stefan-Boltzmann law:

$$u = \sigma T^4,$$

where $\sigma = \frac{2\pi^5 k^4}{15 c^2 h^3} \approx 5,67 \cdot 10^{-8} \text{ Bt}/(\text{m}^2 \cdot \text{K}^4)$ is the Stefan-Boltzmann constant. For orientation, in order of magnitude, thenism, which at the melting temperature of tungsten 3500 K, the value $u$ is $9 \cdot 10^6 \text{ Bt}/\text{m}^2$.

Most of the filament's radiation is useless for illumination because it lies in the invisible infrared region. The eye perceives as light only electromagnetic waves with wavelengths from $\lambda \approx 400$ nm (phylottic light) to $\lambda \approx 760$ nm (red light). The total power emitted per unit surface area of ​​a heated body in the range of wavelengths visible to the eye is equal to

$$u_{\text{cb}}(T) = \int_{\lambda_\phi}^{\lambda_\kappa} u(\lambda, T) d\lambda,$$

and the luminous flux given by the light bulb is

$$\Phi(T) \approx A S u_{\text{cb}}(T),$$

where $S$ is the area of ​​the emitting surface (the surface of the thread), $A$ is the coefficient of conversion of energy quantities into photometric ones associated with the color value of the eye. (We are now leaving aside all the subtleties caused by the different chromaticity of the eye to different colors, but we note that the eye is much less chromatically sensitive to red and violet rays than to yellow-green ones.)

The luminous intensity of a light bulb, measured in candelas (or, in the old way, in candles), is equal to the luminous flux emitted per unit of telephone angle, i.e. approximately equal

$$I(T) \approx \frac{\Phi(T)}{4\pi}.$$

In the range of wavelengths that we are interested in and at temperatures not exceeding the melting point of tungsten,

$$I(T) \approx \text{const} \left( x^3 - 3x^2 + 6x - 6 \right) e^{-x},$$

where $x = \frac{h c}{\lambda_\kappa k} \frac{1}{T}$.

Since the quantity $\frac{h c}{\lambda_\kappa k}$ has the dimension of temperature, we will denote it $T_{\kappa}$. It is approximately 19,000 K. The specific value of CONSTANTES BEFORE THE BRACKET FOR NATIONAL: we will be interested only in the general form of the dependence $I(T)$.

Now we have to ask the following question:

How do $T$ and $I$ depend on $U$?

The dependence of the filament temperature on voltage is the author of the experimental definition. The determination scheme is simple: for different voltage values ​​$U$ on the lamp, change the current $I$ through it and calculate the resistance of the thread $R_U = U/I$; then use the formula expressing the dependence of resistance on temperature -

$$R(T) = R(T_1)(1 + \alpha (T - T_1))$$

⟦folio 4⟧

$(R(T_1) - \frac{R_U(T) - R(T_1)}{\alpha R(T_1)})$

The author continued several changes with a 60-watt bulb rated at $U_0 = 220$ V. The resistance $R(T_1)$ (which can be adjusted with a meter) was found to be 70 ohms. To obtain the voltage values ​​on the light bulb, various resistances were connected in series with it (iron, boiler, TV, other light bulbs). The voltage on the light bulb was changed by a voltmeter, the current through it was changed by an amperator.

The results of the changes are shown in Table 1. (The table also shows the power $P_U = UJ$ consumed by the light bulb at different voltages; this value will be useful to us later.) As can be seen from the table, the operating temperature of the filament $T_0$ at a voltage $U_0 = 220$ V is 2900 K.

Knowing how the temperature of the filament depends on the voltage, we can calculate the light intensity of the light bulb at different voltages.

The luminous intensity $I$ (in some relative units) can be very accurately determined experimentally using an oil slick photometer. This wonderful device is a vertically mounted sheet of paper, in the middle of which there is a translucent spot. On one side, the sheet is illuminated by a “reference” electric lamp. The light bulb under study (Fig. 2) is placed on the other side of the sheet, and observation is carried out from the same side. If the illumination of the sheet from the side is less than from the opposite side, the spot will appear light against the dark background of the sheet; if the opposite is true, the spot will appear darker. With equal illumination, the spot is barely visible.

Surface illumination $E = I/r^2$, where $I$ is the luminous intensity of the source, $r$ is the distance to it. When the voltage $U$ on the bulb under study changes, its luminous intensity $I$ changes. In order for the illumination of the spot created by the lamp at different values ​​of $U$ to be equal to the illumination $I_0/r_0^2$ from the reference lamp, it is necessary to change the distances $r$. Thus, you can find the ratio of the luminous intensity of a light bulb at voltage $U$ to its luminous intensity at equal voltage $U_0$ (on the reference lamp - the same as the one under study - the voltage is always $U_0$):

$$I(U)/I_0 = (r/r_0)^2.$$

The results of such changes are shown in Table 2. In order to correctly process the results of the experiment, it is necessary to construct a graph of the dependence of $I_U/I_0$ on $U$ in such coordinates in which it will have the simplest form. On figure 3

⟦folio 5⟧

Fig. 3.

the dependence of the value $y = \ln \frac{I}{I_0}$ on $z = 1 - \frac{U_0}{U}$ is shown (the necessary data are given in the same table 2). The experimental points lie well on a straight line. The logarithmic scale along the $y$ axis was chosen because if in the formula for $I(T)$ there was no polynomial facing the experiment, then the dependence $y(T)$ would have the form

$$y = \ln \frac{I}{I_0} = \frac{T_{\text{кр}}}{T_0} \left(1 - \frac{T_0}{T}\right),$$

the value $\theta = 1 - \frac{T_0}{T}$, as can be concluded from the data in Table 1, is proportional to $z$ with good accuracy (to figure this out, some observations related to the energy balance in the light bulb were needed): $\theta \approx Kz$, where the coefficient

Table 2

| $U, \text{B}$ | 220 | 120 | 130 | 150 | 180 | 190 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $U_0/U$ | 1 | 1,81 | 1,66 | 1,47 | 1,14 | 1,12 |
| $z$ | 0 | -0,81 | -0,66 | -0,47 | -0,14 | -0,12 |
| $r, \text{см}$ | 27 | 5,5 | 8 | 13 | 21 | 22 |
| $I/I_0$ | 1 | 0,05 | 0,09 | 0,23 | 0,60 | 0,66 |
| $y$ | 0 | -3,0 | -2,4 | -1,5 | -0,5 | -0,4 |

Fig. 4.

the cent of proportionality $K$ is approximately 0.3. The presence of a polynomial before the experiment causes the dependence $y(z)$ to deviate from strict proportionality, but these deviations are small.

Why does the light bulb burn out?

The reason for the light bulb burning out is clear - it is the evaporation of tungsten. In order for not a single tungsten molecule to leave the surface, it is necessary that the kinetic energy of its thermal motion $W \sim kT$ become greater than the binding energy of the molecules with the rest of the crystal $w$. According to the laws of statistical physics, the probability of such an event is proportional to $e^{-w/kT}$. This means that the number of molecules breaking away from the bottom per unit time is

$$n \sim e^{-w/kT}.$$

The value of $w$ can be determined from the value of the heat of evaporation of tungsten at room temperature $Q = 850$ kJ/mol: $w = Q/N_A \approx 1,4 \times 10^{-18}$ kJ ($N_A$ is Avogadro’s number); the quantity $w/k$, which has the dimension of temperature, is about $10^5$ K.

Let us assume that the filament burns out after a certain number of molecules have evaporated. This means that the service life of the light bulb is longer, the

⟦folio 6⟧

less than $n$, i.e.

$$t \sim \frac{1}{n} \sim e^{w/kT}.$$

Let the average life of a 60-watt, 220-volt light bulb (at filament temperature $T_0$) be $t_0$. then the ratio of the service life of the light bulb with a change in voltage $U$ (and filament temperature $T$) to the service life at normal voltage is

$$\frac{t}{t_0} = e^{w/kT - w/kT_0} = e^{-w\theta/kT_0},$$

where $\theta = \left(1 - \frac{T_0}{T}\right)$. We remember that this quantity is proportional to $z = 1 - \frac{U}{U}$ with good accuracy. Therefore, $\ln \frac{t}{t_0}$ is proportional to $z$.

Finding the dependence of $\ln \frac{t}{t_0}$ on $z$ in a “home” experiment is a long and expensive task; you have to burn a lot of light bulbs. Therefore, we had to find ready-made data. These data are shown in Table 3, and figure 4 shows a graph of $\ln \frac{t}{t_0}$ versus $z$. We see that the corresponding points fit well on a straight line. The slope of the line is -14.

Based on the data known to us, we can estimate the theoretical value of this slope:

$$\ln \frac{t}{t_0} = -\frac{w}{kT_0} \theta \approx -\frac{wK}{kT_0} z,$$

so the slope of the line is $(-wK/kT_0)$, which is about -10. Considering the low accuracy with which we know $K$ and $T_0$, the match should be considered incomplete.

If we think more deeply about the process of evaporation, we will see that the situation is to some extent paradoxical.

Let us assume that the thread evaporates completely uniformly and becomes increasingly thinner. At the same time, the compliance of the thread returns, the released thermal power and the temperature of the thread decrease. Thus, with uniform evaporation over time, the light bulb would burn dimmer and dimmer, but would not burn out (or at least would last a very long time).

This means that the reason for the filament burnout is its low-grade evaporation. Indeed, even if, due to some principle, a small overload has formed on the thread. The resistance of the section of thread in the overload region is greater than the resistance of any other section of thread of the same length. In this case, the thermal power $J^2R_\pi$ released in the overload area is greater than in any other section of the thread of the same length. This means that the overload temperature is higher, and evaporation from it occurs more intensely. The thinner the overload, the higher the temperature, the more intense the evaporation, the faster the overload hardens, the faster its resistance increases. This ever-accelerating process ultimately leads to the thread burning out in the place where initially there was even a slight overload. In reality, of course, the whole thread is somewhat thin in thickness, but only the strongest thinning manages to develop into a significant overload: the thread burns out in only one place.

Situations similar to just distance are found in physics to be quite unstable. Suffice it to say that it is the instability of plasma

⟦folio 7⟧

we make it so difficult to control thermonuclear fusion.

So, the reason for the overheating of the light bulb is the instability of the uniform evaporation of the thread. We’ll talk about how to combat this phenomenon a little later, but for now

Let's count the endings

The general lighting bulb has an average lifespan of $t_0=1000$ hours. From our graphs it follows that

$$\ln \frac{t}{t_0} \approx -14 \left(1 - \frac{U_0}{U}\right),$$

$$\ln \frac{I}{I_0} \approx 3,5 \left(1 - \frac{U_0}{U}\right),$$

i.e.

$$t = t_0 e^{-14 \left(1 - \frac{U_0}{U}\right)}, \quad I = I_0 e^{3,5 \left(1 - \frac{U_0}{U}\right)}.$$

The light bulb should give light. The next light bulb will be the one that provides the cheapest light. The cost of lighting over a long period of time consists of the cost of consuming electricity and the cost of a light bulb, which lasts on average for a period of time $t$, and then breaks down. One kilowatt-hour of electricity costs 4 kopecks, a new light bulb costs 25 kopecks.

Let for ours be a zero light bulb with a luminous intensity of $I_0$. If the light intensity is less, we will get tired of damaging our eyes, and we will screw in a more powerful light bulb. Suppose that an “improved” light bulb with a voltage of $U=220$ V is turned on with a voltage of $U_0=235$ V. Its service life is $t = t_0 e^{0,95} \approx 2600$ hours, but the light intensity is $I = I_0 e^{-0,25} \approx 0,78 I_0$, i.e. less than $I_0$, and we will want to change the light bulb to a more powerful one. An “improved” light bulb with zero luminous intensity $I_0$ will consume 1.2 times more power than a conventional light bulb. Over 1000 hours (the service life of a conventional light bulb), an “improved” light bulb with zero luminous intensity, like a regular 60 W light bulb, will consume less than 60 kWh of energy, which in monetary terms is 2 rubles. 40 k., and 72 kWh, i.e. for 2 rubles. 88 k.

This means that during the service life of a regular light bulb, the “improved” one consumes an additional 48 kW of electricity, which is almost equal to the cost of two new light bulbs. Consequently, an increase in service life due to operation at the same voltage is obvious.

If we are talking about an eternal light bulb with a diode for which $U_0 / U \approx 1,43$, then its service life is approximately 350 times longer than that of a regular one, but its strength is $I \approx 0,22 I_0$. An eternal light bulb with a luminous intensity of $I_0$ consumes 2.5 times more power than a regular one: together with a 60 W light bulb, you must turn on a 150 W light bulb in series with the diode. For 1000 hours of operation, the excess energy consumption is 90 kWh, or, in monetary terms, 5 rubles. 60 k. - cost of 22 light bulbs. The game is not worth the candle!

A detailed calculation shows that it is impossible to improve the lamp by increasing $U_0$. This means that over the 100 years of its existence, a conventional storage lamp has practically reached perfection, and in order to improve it, new devices and technical solutions are needed. Now we’ll talk about them, but first we note that using the example of a light bulb, we were faced with a fairly typical technical opposition “cost - reliability”: the more reliable, the more ineffective. If a decrease in reliability is not associated with risk, they choose something cheap and unreliable - empty, even homogeneous. Examples: paper napkins and cups, markers, etc.

So, a light bulb doesn't have to last forever. Still, it would be good to extend its service life or, with the same service life, to increase its efficiency due to reheating. The only way to achieve this is to force the educational “heal” on the overload thread. There are several simple solutions to this problem. However, one of them is filling the lamp bulb with an inert gas with a molecular weight less than that of tungsten - krypton (of course, at a very low level (For the end, see p. 16)

⟦folio 16⟧

If the coefficient $k$ does not depend on time and $k < 0$, then the equation $x'' = k(t)x$ turns into the equation of small oscillations known to you from the school curriculum (the solution in example 1). It describes all fresh vibrations with small amplitudes; $x$ is a (small) deviation from the equilibrium position.

Exercise 6. Calculate the coefficient $k$ in the case shown in figure 3, if $a) x$ is the spring stiffness coefficient, $m$ is the mass of the load; $6) l$ — length of the weightless messy thread; $b) R$ is the radius of the hole, $d$ is the diameter of the ball.

Finally, the Great Denogardus Number, or rather the Great Denogardus Formula (exercise 4) is called the arbitrary Schwartz, or Schwarzan. In fact, this formula was communicated in a letter to G. A. Schwartz by the German mathematician K. F. Gauss. Shvarchan is a popular object of modern mathematics. It has a remarkable property of appearing in a wide variety of mathematical theories.

So, although everything said about Denogarduce is nothing more than a hoax, the mathematical content of his work is quite serious. As they say: “Every joke has a grain of humor in it...”

Eternal light bulb?

(For the beginning, see p. 2)

pressure so that the heat transfer does not increase too much). When the lamp operates in gas, a certain temperature distribution is established inside the cylinder: near the filament, the temperature is much higher than near the walls of the cylinder. The total pressure of krypton and tungsten vapor in the bulb of a working lamp is the same, however, there is more tungsten vapor near the filament, and more krypton near the cold wall. This inhomogeneous distribution of gases is associated with a phenomenon called thermal diffusion. At the same time, a tungsten molecule detached from the filament has a greater chance of returning to the hottest part of the filament and is less likely to settle on the wall.

In halogen lamps of automatic headlights (here the question of the brightness of the source is acute), the gas filling the bulb forms a volatile compound with tungsten, which decomposes and releases metallic tungsten upon contact with a hot filament. Such conditions are justified, since they are not too expensive and almost do not involve an increase in power consumption.

While thinking about the light bulb, we talked about various important things - about the radiation of a heated body, about the temperature dependence of resistance, about evaporation and instability, about technical contradictions and the thermal separation of gases. And each of these topics could be continued. But other objects around us are no less interesting than a light bulb...
