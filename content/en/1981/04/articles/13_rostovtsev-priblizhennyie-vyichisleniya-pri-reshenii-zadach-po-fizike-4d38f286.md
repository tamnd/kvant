---
id: 1981-4-rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286
issue: kvant_1981_4
year: 1981
number: "4"
title: Approximate calculations when solving physics problems
authors:
  - Ростовцев Н. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: U2PI
lang: en
source: kvant_digital
extraction: vision
content_sha256: b07e9eadf16652bdeee1dcf4a0e69c035dea34faed0c16c7043b7570c2b604bf
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/13_rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286.md
source_content_sha256: f26f600a2c36c4c33a2757acd962c21d7678de490c9ed0816d01b35314d031fa
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Approximate calculations when solving problems in physics

When starting to solve any physical problem, first of all it is necessary to find out which phenomena or processes play a significant role, and which ones play a non-existent role. Neglect of non-essential phenomena inevitably leads to neglect of relatively small quantities, that is, to approximate calculations. Knowledge of formulas for approximate calculations and the ability to use them often greatly simplifies calculations.

From the course of mathematics it is known that the expression $(1+x)^n$ at $|x|<1$ can be represented in the form

$$(1+x)^n = 1 + nx + \frac{n(n-1)}{1 \cdot 2} x^2 + \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} x^3 + \dots$$

Here $n$ is any real number. With natural $n$ this sum is converted to a term of the $n$th degree; the resulting formula is called Newton's formula.

Let there be an expression $(a+b)^n$, then from (1)

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n = a^n \left(1 + n \frac{b}{a} + \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2 + \dots\right).$$

If $|b| \ll |a|$, terms containing the relation $b/a$ to the second power and higher, we can neglect and limit ourselves to only the first two terms:

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n \approx a^n \left(1 + n \frac{b}{a}\right).$$

What error will occur when using this approximate formula? To estimate the wave, we can assume that the error is equal to the third term in the expansion:

$$\Delta y = a^n \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2.$$

When solving physical problems, calculations with an accuracy of up to one percent are often permissible. From expression (3) one can find the maximum value of $b/a$, at which the calculation accuracy does not exceed the permissible dimensions.

Formulas for approximate calculation of the values ​​of trigonometric functions are very simple and convenient. If the angle $α$, expressed in radii, is small enough, one can take

$$\sin α \approx α,$$

$$tg α \approx α,$$

$$\cos α \approx 1.$$

Calculations show that the error does not exceed one percent if the angle $α$ satisfies the conditions

$$α \leq 23° \approx 4.0 \cdot 10^{-1}$$

glad for sin $α$,

$$α \leq 18° \approx 3.1 \cdot 10^{-1}$$

glad for tg $α$,

$$α \leq 8° \approx 1.4 \cdot 10^{-1}$$

glad for cos $α$.

(This can be checked using, for example, Bradis tables.)

In physics, the exponential function $y=a^x$ is quite common. For small values ​​of $x$ the approximate equality is satisfied

$$a^x \approx 1 + \frac{\lg a}{0.43} x.$$

Let us now consider several specific problems.

Task 1. The resistance $R$ of the conductor is changed using an ammeter and a voltmeter according to the diagram shown in figure 1. The resistance of the voltmeter $R_V \gg R$. Identify the mistake that is being made

⟦folio 41⟧

calculating the resistance of a conductor without taking into account the current flowing through the voltmeter.

The resistance of the conductor, calculated from the readings of the amperator and voltmeter, without taking into account the resistance of the voltmeter, is equal to

$$R' = \frac{U}{I},$$

where $U$ is the voltage on the voltmeter, $I$ is the current flowing through the amperor.

True resistance is

$$R = \frac{U}{I - I_V} = \frac{U}{I - U/R_V}.$$

The error you are looking for

$$\Delta R = R - R' = \frac{U}{I - U/R_V} - \frac{U}{I} = \frac{U}{I} \left( \left( 1 - \frac{U/R_V}{I} \right)^{-1} - 1 \right).$$

Since $R_V \gg R$, then $U/R_V \ll I$. Applying formula (2), we obtain

$$\Delta R = R - R' \approx \frac{U}{I} \left( 1 + \frac{U/R_V}{I} - 1 \right) \approx \frac{U^2}{I^2 R_V}.$$

Task 2. By what fraction will the force of gravity change when rising to a height of $h = 1$ km above the Earth’s surface? The radius of the Earth is considered equal to $R = 6400$ km.

The gravitational force of a body of mass $m$ at the surface of the Earth is equal to

$$F_0 = G \frac{mM}{R^2},$$

where $G$ is the gravitational constant, $M$ is the mass of the Earth.

As we move away from the Earth's surface, the gravitational force decreases, and at a height $h$ it is equal to

$$F_1 = G \frac{mM}{(R+h)^2}.$$

From the expressions for $F_0$ and $F_1$ we find

$$\frac{F_0 - F_1}{F_0} = 1 - \frac{F_1}{F_0} = 1 - \frac{R^2}{(R+h)^2} = 1 - \frac{1}{(1+h/R)^2} = 1 - \left( 1 + \frac{h}{R} \right)^{-2}.$$

Since $h \ll R$, that is, $h/R \ll 1$, using formula (2), we obtain

$$\frac{F_0 - F_1}{F_0} \approx 1 - \left( 1 - 2 \frac{h}{R} \right) = 2 \frac{h}{R} \approx 3 \cdot 10^{-4}.$$

Task 3. In the theory of relative energy, ana-

The particles $E_k$ are calculated using the formula $E_k = E - E_0$, where $E$ is the energy of a moving particle, and $E_0$ is the energy of a particle at rest. Show that when the particle speed is $v \ll c$ (with the speed of light), the kinetic energy of the approximate is $m_0 v^2/2$, where $m_0$ is the mass of the particle at rest.

According to the theory of relative energy

$$E = \frac{m_0 c^2}{\sqrt{1 - (v/c)^2}}$$ and $E_0 = m_0 c^2.$

From here

$$E_k = E - E_0 = m_0 c^2 \left( \frac{1}{\sqrt{1 - (v/c)^2}} - 1 \right) = m_0 c^2 \left( \left( 1 - \frac{v^2}{c^2} \right)^{-1/2} - 1 \right).$$

Since $v \ll c$, that is, $v/c \ll 1$, and therefore $v^2/c^2 \ll 1$, applying formula (2), we find

$$E_k \approx m_0 c^2 \left( 1 + \frac{1}{2} \frac{v^2}{c^2} - 1 \right) = \frac{m_0 v^2}{2}.$$

Task 4. A body slides from an inclined plane making an angle $\alpha = 7^\circ$ with the horizon. Find the acceleration of the body if the coefficient of friction of the body on the plane is $\mu = 3 \cdot 10^{-2}$.

Three forces act on a body moving along an inclined plane: the gravitational force $m\vec{g}$, directed vertically downwards, the gravitational force $\vec{F}_{\text{тр}}$, directed upward along the inclined plane, and the normal reaction force $\vec{R}$, perpendicular to the inclined plane. Let's project the forces on the coordinate axes $OX$ and $OY$, as shown in figure 2, and write the equation of motion:

$$mg \sin \alpha - F_{\text{тр}} = ma,$$

$$R - mg \cos \alpha = 0.$$

Considering that

$$F_{\text{тр}} = \mu R,$$

⟦folio 42⟧

from the equation of motion we find the acceleration module of the body:
$$a = g(\sin \alpha - \mu \cos \alpha).$$

Since the angle is $\alpha < 8^\circ$, we can use formulas (4) and (6) and assume that $\cos \alpha \approx 1$ and $\sin \alpha \approx \alpha$ (the angle $\alpha$ must be expressed in radians). Substituting the values ​​$\cos \alpha \approx 1$ and $\sin \alpha \approx 1,2 \cdot 10^{-1}$, we get $a \approx g(1,2 \cdot 10^{-1} - 3 \cdot 10^{-2}) = 8,8 \cdot 10^{-1}$ m/s$^2$.

Problem 5. How many atoms decay in time $t = 1$ from one gram of radium? The half-life of radium is $T = 1600$ years. There are $N_0 = 2,6 \cdot 10^{21}$ atoms in a gram of radium.

If the number of radioactive atoms at the initial moment of time is $N_0$, then, according to the law of radioactive decay, after time $t$ the number $N$ of unmelted atoms is

$$N = N_0 2^{-t}.$$

From here we can find the exception number $n$ of decayed atoms:

$$n = N_0 - N = N_0 (1 - 2^{-t}).$$

Since $t/T \ll 1$, applying formula (7), we obtain

$$n \approx N_0 \left(1 - 1 + \frac{\lg 2}{0,43} \frac{t}{T}\right) \approx 3,7 \cdot 10^{10}.$$

Note that the activity of a radioactive converter, in which $3,7 \cdot 10^{10}$ atoms decay in 1 s, is taken as a unit of activity and is called 1 curie.

In conclusion, a few words about numerical calculations when solving the problem. Recording a brief condition of the problem, it is reasonable to represent all numerical values ​​in the form $a \cdot 10^n$ (where $1 \leq a < 10$), and with the same degree of accuracy. In the vast majority of cases, deve has significant numbers. Then the resulting result should also be rounded to two significant figures (see, for example, the solution to problem 4).

Exercises

1. Calculate the maximum values ​​of $a$ at which the errors of formulas $(1+a)^3 \approx 1+3a$ and $\sqrt{1-a} \approx 1 - \frac{1}{2}a$ do not exceed 0.01.

2. Coefficient of linear distribution of brass $a = 2 \cdot 10^{-5} \text{K}^{-1}$. How far behind will the Chistsy with a brass magnet be in 24 hours due to the temperature increase of $\Delta T = 10$ K?

3. Determine the acceleration of gravity at an altitude of 10 km from the Earth, if at the surface it is equal to 981 cm/$^2$. The radius of the Earth is $R = 6400$ km.

4. Determine the direction of the field of the system of exact charges $+q$ and $-q$ at point $B$ (Fig. 3), if $l \ll L$.

5. A car weighing $m = 2 \cdot 10^3$ kg starts from rest and goes uphill, the slope of the mines is $a = 0,02$. Having covered a distance of $s = 100$ m, it develops a speed of $v = 32,4$ km/h. Motion resistance coefficient $k = 0,05$. Determine the average power developed by the automaton during this movement.

Small intercosmos

(For the beginning, see p. 8)

Teams of schools, non-school institutions, scientific and technical associations of institutions, who took the most active and dense participation in the competition, as well as sub-departments and teams of enterprises, institutions, universities, who provided effective assistance in the work of young technical and researchers, will be awarded honorary diplomas, and teachers, heads of circles, consultants from among the scientists and specialists under whose guidance the work was carried out, the winners at the competition - diplomas and badges.

For all questions regarding the organization and conduct of the competition, please contact the Komsomol Central Committee (Moscow, New Square 6/8, tel. 206-84-70, 206-89-92), the Central Station for Young Technical Education of the RSFSR (tel. 289-75-44), the Moscow City Palace of Pinoyers (tel. 139-89-54, 139-84-88).
