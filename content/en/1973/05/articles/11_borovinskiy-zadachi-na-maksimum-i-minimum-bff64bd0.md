---
id: 1973-5-borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0
issue: kvant_1973_5
year: 1973
number: "5"
title: Maximum and minimum tasks
authors:
  - Боровинский Л. А.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 48
page_labels: 43-46
tag: FJJE
lang: en
source: kvant_digital
extraction: vision
content_sha256: b2e3389a64d5c5e47e825e64f74016022fee6bd4675efee805c3956580fc8946
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/11_borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0.md
source_content_sha256: 4dd016b9b5620eca9e1a00d477111249e11e80368e47b408361ad4ce1132b45f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Tasks
to the maximum
and minimum

In everyday life, in practical and scientific problems, the need often arises to determine the conditions under which we will obtain the most results when determining the conditions. In other cases, on the contrary, it is necessary to know under what conditions goals can be achieved with minimal effort or time. Such conditions are called optimal.

Often, without even noticing it, we solve problems to determine optimal conditions, use life experience and ingenuity. However, interests and life experiences can be misleading or inaccurate. At best, they will tell us the conditions that provide a good, but not the best, result. To effectively find optimal conditions, it is necessary to resort to the use of weapons - mathematics.

Many laws of physics can be formed as some extreme principles, that is, requirements for an extremum (maximum or minimum) of certain physical quantities. We know, for example, that the equilibrium state of a mechanical system can be found from the extremum of the potential energy of the system, and in a state of stable equilibrium the potential energy is minimal, and in a state of unstable equilibrium it is maximum. Anyone who is familiar with Fermat's principle, according to which he always follows two points along a path that requires minimal time, all the laws of geometric optics can emerge from this principle.

There is a significant difference between the optimal conditions for processes controlled by humans and for processes producing in nature with self-production. In the first case, optimal conditions determine the most profitable, but not the only possible, course of the process. And in the second, the conditions of the extremum within the limits of applicability of the laws of nature determine either the only possible or the most probable course of the process.

Complex problems involving the determination of optimal or extreme conditions are solved using the theory of differential calculus, expressed calculus, or linear programming.

However, there are many simple problems for determining the extrema of functions that can be solved without using complex mathematical theories. To solve them, you only need to know the properties of the elements of the functions (for example, the quadratic trinomial or trionometric functions). You can also use the well-known theory:

The geometric mean of n positive numbers is not greater than their arithmetic mean, that is

$$\sqrt[n]{x_1 \cdot x_2 \cdot \cdots \cdot x_n} \leq \frac{x_1 + x_2 + \cdots + x_n}{n},$$

and the equal sign takes place moeda and molko moeda, koeda

$$x_1 = x_2 = \cdots = x_n.$$

Let's consider several specific tasks.

Problem 1. Electronic regressive device of cross-breeding power from a moka source, e. d. c. which is equal to E, and the internal resistance and the resistance of the supply wires add up to r. What resistance R should the device have in order for it to produce maximum power?

⟦folio 44⟧

According to Ohm's law, for a complete circuit the current is equal to

$$I = \frac{E}{R + r},$$

and according to the Joule-Lenz law, the power allocated to the resistance $R$ is equal to

$$P = I^2R = \frac{E^2R}{(R + r)^2} = \frac{E^2}{R + 2r + \frac{r^2}{R}}.$$

When $R (R \ll r)$ is small, the useful power is small, since almost all the power taken from the source is released in the supply wires and in the source. If $R$ is large ($R \gg r$), the useful power is again small, since the current in the circuit is small. Therefore, there is a certain value $R$ at which the useful power will be maximum.

Consider the expression

$$R + 2r + \frac{r^2}{R} = 2r + \left(R + \frac{r^2}{R}\right).$$

It is clear that the useful power reaches its greatest value when this expression is minimal. The value $2r$ is given, and the product of the terms $R$ and $\frac{r^2}{R}$ in parentheses does not depend on $R$ and the constant, therefore, according to the theorem stated above, the minimum value of the value will be reached when $R = \frac{r^2}{R}$, that is, $R = r$.

The smallest value of useful power is equal to

$$P_{\max} = \frac{E^2r}{4r^2} = \frac{E^2}{4r}.$$

Note that in this case the c.p. d. source is only 50%. Therefore, it is advisable to obtain maximum power from the source only for short periods of time, for example, when the starter is operating automatically. In order to make more efficient use of the energy reserve of the current source, the resistance $R$ must be significantly greater than $r$. In this case, the useful power will be less than the maximum.

Simultaneously, but for what purpose? d. will be greater than 100%. Check it out.

Problem 2. A loaded sled moves along the horizon of the surface under the influence of force $F$ applied to the center of the softness. What is the length of the line of action of the force $F$ with the horizon so that the uniform motion of the sleigh occurs under the action of the least force? The coefficient of friction between the sled and the snow is $k$.

Let us decompose the force $F$ into horizontal and vertical components $F_x$ and $F_y$ (Fig. 1). The force of normal pressure of the sled on the snow is equal to the difference between the weight of the sled and the vertical component of the force $F$:

$$N = P - F \sin \alpha. \tag{1}$$

Therefore the friction force

$$F_{\tau p} = kN = k(P - F \sin \alpha). \tag{2}$$

The sled will move uniformly subject to compensation of horizontal forces: $F_x = F_{\tau p}$, that is

$$F \cos \alpha = k(P - F \sin \alpha). \tag{3}$$

From here we find the force $F$ as a function of the angle $\alpha$:

$$F = \frac{kP}{k \sin \alpha + \cos \alpha}. \tag{4}$$

It is obvious that the force $F$ will be minimal at the value of the angle $\alpha$ at which the value in formula (4) is maximum. To determine this angle, we transform the value of expression (4) so ​​that

⟦folio 45⟧

it included only one trigonometric function of the angle $\alpha$. To do this, let’s imagine the friction coefficient $k$ as the tangent of a certain angle $\varphi$:

$$\text{tg} \varphi = k; \quad \varphi = \arctg k;$$

$$\sin \varphi = \frac{k}{\sqrt{1+k^2}}; \quad \cos \varphi = \frac{1}{\sqrt{1+k^2}}.$$

Since $k$ is given, angle $\varphi$ can be considered known. Substituting in (4) tg $\varphi$ instead of $k$ and multiplying the numerator and denominator by cos $\varphi$, we obtain

$$F = \frac{P \text{tg} \varphi}{\text{tg} \varphi \sin \alpha + \cos \alpha} =$$

$$= \frac{P \sin \varphi}{\sin \varphi \sin \alpha + \cos \alpha \cos \alpha} = \frac{P \sin \varphi}{\cos (\alpha - \varphi)} =$$

$$= \frac{P k}{\sqrt{1+k^2} \cos (\alpha - \varphi)}.$$

Now it is clear that the force $F$ will be minimal when $\cos (\alpha - \varphi) = 1$, that is

$$\alpha_{\min} = \varphi = \arctg k.$$

In this case, the minimum value of force $F$ is equal to

$$F_{\min} = \frac{k P}{\sqrt{1+k^2}}.$$

From the solution to this problem we can draw a practical conclusion: when it is necessary to lift a load on a sled along a road with a high coefficient of friction (for example, if the road is sandy), you need to pull the sled as short as possible. If the friction coefficient is small, the screw should be long. Explain this. Problem 3. Points 1 and 2 move along the axes $x$ and $y$ to the origin of coordinates (Fig. 2). At moment $t_0 = 0$ power 1 is at a distance $s_1 = 10$ cm,

![Рис. 2.](image)

Fig. 3.

⟦folio 46⟧

towards the base of perendicular BC and then swim towards the buoy. The winner is the one who reaches buoy B the fastest. From what point of the shore is it most convenient to start swimming to the buoy for a sortman who knows that when swimming along a sandy bank his speed is 13 km/h, and his swimming speed is 5 km/h.

Let $x$ be the distance from point C to the place from where the athlete begins to swim towards the buoy. then the athlete runs a distance $L - x$, and spills a distance $\sqrt{l^2 + x^2}$. The total travel time from start A to buoy B is

$$t = \frac{L - x}{v_1} + \frac{\sqrt{l^2 + x^2}}{v_2}.$$

Let the length of the segment $x$ increase by a small amount $\Delta x$. then the time of movement becomes equal

$$t' = \frac{L - (x + \Delta x)}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2}}{v_2}.$$

The change in time is

$$\Delta t = t' - t = -\frac{\Delta x}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2} - \sqrt{l^2 + x^2}}{v_2} = -\frac{\Delta x}{v_1} + \frac{l^2 + (x + \Delta x)^2 - l^2 - x^2}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} = \left\{ \frac{2x + \Delta x}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} - \frac{1}{v_1} \right\} \Delta x.$$

Fig. 4.

Since $\Delta x \ll x$, the expression for $\Delta t$ can be overslept. Then

$$\Delta t \approx \left\{ \frac{x}{v_2 \sqrt{l^2 + x^2}} - \frac{1}{v_1} \right\} \Delta x.$$

Because $\Delta x > 0$, the sign of $\Delta t$ matches the sign of the expression in the curly braces.

For small $x$ ($x \to 0$), the expression in curly brackets is negative, which means $t$ kills as $x$ increases. When $x \gg l$ the expression in the curly brackets is positive, and the time increases as $x$ increases. Since the function $\Delta t$ changes continuously with an increase in $x$, there is a value $x_m$ at which $\Delta t$ becomes zero, that is, the decrease in $t$ with an increase in $x$ is replaced by an increase in $t$. This value is $x_m$ and will correspond to the minimum time $t$.

So,

$$\frac{x_m}{v_2 \sqrt{x_m^2 + l^2}} - \frac{1}{v_1} = 0,$$

where

$$x_m = l \frac{v_2}{\sqrt{v_1^2 - v_2^2}}.$$

Substituting the numerical values ​​of all quantities, we obtain $x_m = 50$ m.

The length $L$ was not used in the solution. However, it is necessary to know it. Think why?

Battles

1. There are many inclined planes with the same bases equal to $b$, but with different heights. At what height $h$ will the time for a body to slide down an inclined plane without friction be minimal?

2. The top point of the springboard is at height $H$ above the ground, and at height $h$ the springboard is formed (Fig. 4). What should the height $h$ be at a given height $H$ so that the skier, having left the springboard, can fly the greatest distance $S$ (counting horizontally)?

Neglect air and air resistance.
