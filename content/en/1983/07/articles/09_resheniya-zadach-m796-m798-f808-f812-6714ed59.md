---
id: 1983-7-resheniya-zadach-m796-m798-f808-f812-6714ed59
issue: kvant_1983_7
year: 1983
number: "7"
title: Solutions to problems M796—M798; F808—F812
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 52
page_labels: 46-50
tag: 13QT
lang: en
source: kvant_digital
extraction: vision
content_sha256: d0f93ce43c54f6593a4bac7a48c71bca3aef6ce018abacb9eea36a1b31d82818
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/09_resheniya-zadach-m796-m798-f808-f812-6714ed59.md
source_content_sha256: 8a8732c598e42cc819acb01b4dec2c8fcafff62bb74b0d85045b4866921eb65f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

the ammeter then? The battery is assumed ideal, the resistance of the wires is 2 Ohm.

A. R. Zilberman

P826. Far-away objects are viewed through a convergent lens of focal distance $F=9$ cm, the eye being located at the distance $a=36$ cm from the lens. Estimate the minimal size of a screen which, if placed behind the lens, would entirely cover the field of vision. Where should the screen be placed?

D. V. Belov

P827. A cube with side $a$ moves with velocity $v=0.8$ c (where $c$ is the velocity of light) in a direction perpendicular to one of its faces. What will we see on a photograph of the cube taken by a far-away camera with a very short exposure, if the optical axis of the camera is perpendicular to a face of the cube and intersects the trajectory of its centre (figure Pric. 3)?

D. Ju. Grigoriev

Problem solutions

M796—M798; F808—F812

ANSWER: $\widehat{APB}=135^\circ$. Let's rotate $\triangle ABP$ around the point $B$ on $90^\circ$ so that the vertex $A$ is aligned with $C$ (see figure). Let the vertex $P$ go to the point $Q$. Then $|PQ|^2=2|BP|^2=8|AP|^2$ ($\triangle BPQ$ equal headed rectangular), and $|QC|=|PA|$. Therefore, $|PQ|^2+|QC|^2=9|AP|^2=|CP|^2$, that is, $PQC$, is a right triangle with right angle $PQC$. Hence $\widehat{APB}=\widehat{CQB}=\widehat{CQP}+\widehat{PQB}=90^\circ+45^\circ=135^\circ$.

There is also a less artificial (but more cumbersome) solution using the coordinate method. Let us take straight lines $AB$ and $AD$ as coordinate axes; let $(x, y)$ be the coordinates of point $P$. Then, considering the side of the square equal to 1, we get: $|AP|^2=x^2+y^2$, $|BP|^2=x^2+(1-y)^2$, $|CP|^2=(1-x)^2+(1-y)^2$. By condition $|AP|^2:|BP|^2:|CP|^2=1:4:9$, from here it is easy to find $x$ and $y$, and then the desired angle.

L. D. Kurlyandchik

M797*. It is known that the last digits of the squares of integers can only be the numbers 0, 1, 4, 5, 6 and 9. Is it true that before the last digit they can contain any group of digits, that is, that for any set of $n$ digit $a_1, a_2, \dots, a_n$ one can find an integer whose square ends with the digits $a_1a_2\dots a_nb$ (where b is one of the digits listed above)?

ANSWER: No. We will give two proofs of this fact.

First proof. Let $A_n$ be the number of all combinations from $n$ the digit on which the exact square turns. We will show that if $n \geq 4$ then $A_n<10^n$. Our statement will follow from this: even if each combination $a_1, \dots, a_n$ were found in combination with only one $b$, there would already be $A_n=10^n$. To get all the $n$-digit endings of the squares, it is very necessary; it is enough to consider the square of only $n$-digit numbers. Let's divide these $10^n$ numbers (from 0 to $10^n$-1) into classes, collecting into one class all numbers with the same $n$-digit square ending ($p$ and $q$ are included in one class if $p^2-q^2$ is divisible by $10^n$). Then $A_n$ is equal to the number of such classes; Based on this, we will estimate $A_n$.

Let us consider separately three groups of $n$-digit numbers: (1) numbers divisible by $5^n$ (and also $2^n$); (2) odd numbers not divisible by $5^n$ (there are fewer than $0,5 \cdot 10^n$); (3) even numbers not divisible by $5^n$ (there are also fewer of them than $0,5 \cdot 10^n$). The number of numbers in the first group is small compared to $10^n$. What is important for us is that they give pairwise different remainders when divided by $2^n$ (because $k \cdot 5^n-l \cdot 5^n=(k-l) \cdot 5^n$ cannot be divided by

⟦folio 47⟧

2$^n$ at $1 \leqslant l < k \leqslant 2^n$), and therefore, among these residues, all possible residues of the separation at $2^n$ occur once. Let, further, $m$ be a number from the second group. Let us find in the first group the numbers $k_1 \cdot 5^n, k_2 \cdot 5^n, k_3 \cdot 5^n$ and $k_4 \cdot 5^n$, which when divided by $2^n$ give the same remainders as $2m, 2^{n-1}+2m, 2^n-2m$ and $2^{n-1}-2m$. Then the squares of 8 numbers $m, 10^n-m, 0,5 \cdot 10^n \pm m, k_1 \cdot 5^n-m, k_3 \cdot 5^n+m$ and $k_4 \cdot 5^n+m$ (they are written in the margins) have the same $n$-digit endings at $n \geqslant 4$. Indeed, since $0,25 \cdot 10^n$ is an integer ($n \geqslant 4$), $k_i$ are even numbers, and the numbers in the blue box in the margin are divisible by $2^n$, all the numbers in the red box are divisible by $10^n$. Thus, the number classes of the second group contain at least 8 elements, so their number is less than $0,5 \cdot 10^n/8$. Similarly, for $n \geqslant 4$ the classes of numbers of the third group contain at least 16 elements. (Each class, together with the number $m$, contains the numbers $10^n-m, 0,25 \cdot 10^n \pm m, 0,5 \cdot 10^n \pm m, 0,75 \cdot 10^n \pm m, k_1 \cdot 5^n-m, ..., k_4 \cdot 5^n-m, k_5 \cdot 5^n+m, ..., k_8 \cdot 5^n+m$, where $k_1, ..., k_8$ are chosen so that the numbers $k_1 \cdot 5^n, ..., k_8 \cdot 5^n$, when divided by $2^n$, give the same remainders as the numbers $2^n, 2^{n-2}+2m, 2^{n-1}+2m, 3 \cdot 2^{n-2}+2m, 2^n-2m, 2^{n-1}-2m, 3 \cdot 2^{n-2}-2m$.) Thus, the number of classes in group (3) is less than $0,5 \cdot 10^n/16$, and the total number of classes $A_n < 2^n + \frac{0,5 \cdot 10^n}{8} + \frac{0,5 \cdot 10^n}{16} = 10^n \left( \frac{1}{5^n} + \frac{1}{16} + \frac{1}{32} \right) \leqslant 10^n \left( \frac{3}{32} + \frac{1}{5^4} \right) = 0,9535 \cdot 10^{n-1} < 10^{n-1}$.

Try searching for $\lim_{n \to \infty} A_n/10^{n-1}$.

Second proof. It is shorter than the first, but less respectful. The following fact applies:

If the penultimate digit of an exact square is odd, then the last one is 6.

In fact, from the equality $(10a+b)^2 = 100a^2 + 20ab + b^2$ it is clear that the penultimate digit of the square of any number and the penultimate digit of the square of its last digit have the same parity. But of the square of a single-digit number, the penultimate digit is odd only in two cases: $4^2 = 16$ and $6^2 = 36$.

Now we will show that an exact square cannot end in 005$b$. Indeed, according to what has been proven, such a square must have the ending 0056, and then it would give a remainder of 8 when divided by 16, which is obviously impossible (the square of a number divisible by 4 is divisible by 16, and the square of a number not divisible by 4 is not divisible by 8).

We invite the reader to independently study $n=2$ and 3 in more detail. Prove that a) for any number $a_1a_2$ there is an exact square with ending $a_1a_2b$; b) an exact square can end in $a_1a_2a_3b$ (with a neoctor $b$) if and only if the three-digit number $a_1a_2a_3$ gives a remainder not equal to 5 or 7 when divided by 8.

Let us present another problem on this topic, sent to the editor by D. Fedorov: prove that a number of the form $aa...ab$, where $b=a+1$, cannot be an exact square.

D. B. Fuchs

◆ Let us first assume that the red segments do not intersect with each other, and show that then each of them intersects with at least one image, that is, the number of red-blue intersections is not less than $k$. Take any red segment $AB$ and one of the friends subtended by it. The number of red dots on it is even (because

⟦folio 48⟧

mi segments, and 2k blue segments - to blue segments (no three segments intersect at one point). Prove that there are at least k points of intersection of the red segments with the blue ones.

Fig. 1.

Fig. 2.

F808. A motor boat, located at point A at a distance R from the shore of the lake, begins to turn, moving at a speed v=18 km/h along a circle of radius r=R/2; At the initial moment, the speed of the boat is directed towards the shore. Wave from the boat to the shore at time t=3 minutes after the start of the turn. The speed of propagation of a wave from a boat along the surface of the water is u=9 km/h. Find the distance R.

F809. A cylindrical tank is filled to the top with liquid of density q. The tank is tightly closed at the top with a lid of radius R. At the bottom, the tank has a hole of area s, closed with a plug of mass m (see figure).

That any of them must be connected by a segment to a point on the same arc), therefore, the number of blue points on this arc is odd. Therefore, one of the blue segments starting on it must intersect AB.

Telery will show that any system of red and blue segments can be “unraveled” - replaced by a new one in which the red segments do not intersect in pairs, without increasing the number of red-blue intersections. Let AC and BD be intersecting red segments. Let's replace them with red segments AB and CD (Fig. 1). It is clear that any segment (red or blue) intersecting with segment AB or segment CD has the same number of intersection points in common with it as with AC and BD. Therefore, when replacing, the number of red-blue intersections does not increase, but the number of red-blue intersections decreases by at least 1. After several such operations, we obtain a system of segments in which the red segments do not intersect in pairs, and the number of red-blue intersections is no more than the original and at the same time, as was proven at the beginning, not less than k.

It is easy to construct an example of a system of segments having k red-blue intersections (Fig. 2).

S. V. Fomin

◆ Considering the boat as a source of waves, propagating from each point of the boat’s trajectory, we will find that point C from which the wave will reach the shore. The position of point C is determined from the condition of equality of the speed of wave propagation and the projection of the speed of the boat in the direction “towards the shore” (X axis at figure):

$$u = v_x = v \sin \alpha \Rightarrow \sin \alpha = u/v = 1/2,$$

that is, $\alpha = 30^\circ$. Consideration from point C to the shore is

$$l = R - r \cos \alpha = R - \frac{R}{2} \cos \alpha = R \left( 1 - \frac{1}{2} \cos \alpha \right).$$

The time t₁ that it takes for a wave to travel from point C to the shore is

$$t_1 = l/u = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right).$$

The time t₂ it takes the boat from point A to point C is

$$t_2 = \frac{2\pi r}{v} \cdot \frac{60^\circ}{360^\circ} = \frac{\pi R}{6v}.$$

The total time after which, after the start of the turn, the wave reaches the shore is equal to

$$t = t_1 + t_2 = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right) + \frac{\pi R}{6v}.$$

From here we find R from point A to the shore:

$$R = \frac{6tuv}{3v (2 - \cos \alpha) + \pi u} \approx 545 \text{ м.}$$

A. I. Buzdin

◆ The pressure in the liquid in a rotating tank at the same depth will be different in the center of the vessel and at the walls - the pressure increases as it moves away from the center. Let's find how much the pressure at the walls differs from the pressure in the center.

Let us mentally select a thin horizontal column of liquid with a cross-sectional area σ (see figure).

⟦folio 49⟧

To pull the plug out of the tank, you need to apply a force f. At what maximum angular speed can the tank be rotated around a vertical axis without the plug being thrown out?

The center of mass of this table moves along a circle of radius $R/2$. Let's write down the equation of motion of the stool:

$$\varrho R \omega^2 \frac{R}{2} = \Delta p \cdot \sigma$$

($\varrho R \sigma$ is the mass of the stolnik, $\Delta p \cdot \sigma$ is the result of the pressure forces acting on the stolnik on the right and left). Thus, the pressure in the fluid at the wall is greater than the pressure in the center at the top

$$\Delta p = \frac{1}{2} \varrho \omega^2 R^2.$$

To Posny, the force acting on the plug from the side of the liquid is equal to

$$F = s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right),$$

where $p_0$ is atmospheric pressure, $H$ is the height of the tank.

Let us write down the equation of traffic jam:

$$m \omega^2 R = p_0 s + F_{\text{тр}} - s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right).$$

As follows from the condition, the plug flies out of the tank at $F_{\text{тр}} = f + s \varrho g H$. Taking this into account, we find the angular velocity of rotation at which the plug will fly out:

$$\omega = \sqrt{\frac{f}{m R + \frac{1}{2} s \varrho R^2}}.$$

V. I. Komov

F810. There is a cutter with operating temperature $t_H = 700^\circ\text{C}$. Ambient temperature - $t_0 = 20^\circ\text{C}$. What minimum amount of heat must be taken from the cutter to evaporate $m = 3$ kkw. water, cut to boiling point ($t_1 = 100^\circ\text{C}$)? Specific temperature of cutting water $r = 2,26$ MJ/kg.

When directly transferring heat from the heater to water, in order to evaporate a mass of water $m$, it is necessary to receive an amount of heat $Q_0 = mr$ from the heater.

Let's try to reduce this value by taking advantage of the fact that a heat pump (that is, a heat engine operating in a reverse cycle) can pump a large amount of thermal energy from a cold body to a hot one at a low cost of mechanical energy, if the temperature difference is not VELK.

Let's imagine a device for evaporating water, consisting of an ideal heat engine $M$ and an ideal heat pump $H$, turned on as shown in figure 1. The machine takes the amount of heat $Q_1$ from the heater and transfers the amount of heat $Q_2$ to hot water, while doing work $A$. heat pump $H$, uses work $A$, takes the amount of heat $Q_3$ from the environment and transfers the amount of heat $Q_4$ to hot water.

Let's calculate the total amount of heat $Q_2 + Q_4$, we get water. The efficiency coefficient of the machine $M$ is equal to

$$\eta = \frac{A}{Q_1} = \frac{T_H - T_1}{T_H}.$$

From here

$$A = Q_1 \frac{T_H - T_1}{T_H}, \quad Q_2 = Q_1 \frac{T_1}{T_H}.$$

Since the heat pump $H$ is an ideal heat engine operating in a reverse cycle, we can write for it in a similar way

$$\frac{A}{Q_4} = \frac{T_1 - T_0}{T_1} \Rightarrow Q_4 = A \frac{T_1}{T_1 - T_0} = Q_1 \frac{(T_H - T_1) T_1}{T_H (T_1 - T_0)}.$$

Thus,

$$Q_2 + Q_4 = Q_1 \frac{T_1}{T_H} \frac{T_H - T_0}{T_1 - T_0}.$$

⟦folio 50⟧

In order to evaporate water, it is necessary that the total amount of heat transferred to it be equal to $Q_2 + Q_4 = Q_0$. Therefore, machine M must take the amount of heat from the heater

$$Q_1 = Q_0 \frac{T_H(T_1 - T_0)}{T_1(T_H - T_0)} \approx 0.31 \text{ mr.}$$

Thus, when using an ideal heat pump (refrigerator) $Q_1$, the amount of heat required to evaporate water is significantly less.

From the formula for the efficiency of a heat pump it follows that at $\frac{T_1 - T_0}{T_1} \ll 1$ it is possible to use the warm energy of the environment (for evaporation, heating, etc.), while spending a small amount of mechanical, electrical or any other non-corporeal energy. However, in practice, heat pumps (refrigerators) are still far from ideal, and their use as heating elements has not yet become widespread.

It is interesting to note that the result (*) will occur if the machine M operates between heat and the environment (figure 2).

O. S. Rabinovich

F811. In the general circuit of a half-wave rectifier (Fig. 1) $C = 1000$ µF, $R = 500$ Ohm. Network frequency $v = 50$ Hz. Assuming the diode is ideal, find:
1) the magnitude of the voltage ripple coefficient $k = \frac{\Delta U}{U}$ on the resistor $R$;
2) How many times will the coefficient $k$ decrease if an inductor $L = 100$ Hz is connected in series with the resistor?

Fig. 1.

Fig. 2.

1) With the selected parameters $C$ and $R$, the charge of the capacitor changes slightly, so the discharge current of the capacitor can be considered constant. Then

$$\Delta U = \frac{\Delta q}{C} = \frac{I \cdot \Delta t}{C} = \frac{U \cdot \Delta t}{RC}.$$

Means,

$$k = \frac{\Delta U}{U} = \frac{\Delta t}{RC}.$$

If the capacitor is discharged a little, then it is recharged at the moments of maximum positive voltage in the network (Fig. 2), that is

$$\Delta t = T = \frac{1}{v}.$$

Hence,

$$k = \frac{1}{vRC} = 0.04.$$

2) When connecting an inductor, the ripple coefficient becomes even smaller (large inductance: $2\pi vL \gg R$). The load current can all the more be considered constant; This means that the voltage on the capacitor will be less according to the same law as in the first case. In this case, the voltage on the coil will almost compensate for the changes in voltage on the capacitor. The current through the coil during the network period will be less according to the parabolic law (inductive emf according to the linear law), and the maximum current value will be in the middle of the period:

$$\mathcal{E} = \frac{\Delta U}{T} t \quad (\text{при } t \in [nT, (n+1)T])$$

$$I = l_0 - \frac{\Delta U}{T} \frac{1}{L} \frac{1}{2} t^2.$$

Ripple in this case is determined by changes in current: $\Delta U_1 = R \cdot \Delta I$. Since

$$\Delta I = I_{\max} - I_{\min} = \frac{1}{2} \frac{\Delta U}{LT} \frac{T^2}{4} = \frac{1}{8} \frac{UT^2}{LRC}$$

($\Delta U = \frac{UT}{RC}$), we finally get:
