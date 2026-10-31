---
id: 1975-1-kompaneets-razmernost-fizicheskih-velichin-i-podobie-yavleniy-bb7fb941
issue: kvant_1975_1
year: 1975
number: "1"
title: Dimension of physical quantities and similarity of phenomena
authors:
  - Компанеец А. С.
rubric: osnovnye-stati
page_first: 11
page_last: 19
page_labels: 9-17
tag: HXOE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1327dbdb63fc91252f0548db197937cf2c893a49ddade2f5197d829dd42ca209
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/04_kompaneets-razmernost-fizicheskih-velichin-i-podobie-yavleniy-bb7fb941.md
source_content_sha256: d484e8ed0ac2a7fa2576903a4cfa029b74e567a98cd376b30a7bc1b3784b7fd1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

⟦column⟧

## Dimension of physical quantities and similarity of phenomena
A. S. Kompaneets

**The meaning of the dimension of physical quantities**

Everyone knows that there are named and abstract numbers. Named numbers depend on the selected units of measurement, unnamed numbers do not. If, for example, one piece of land has 100 square meters ($м^2$), and another has 200 $м^2$, then 100 and 200 are named numbers, and their ratio $^1/_2$ is an abstract number. It will not change if you move from the metric system of measures to any other, measuring the area in square arshins or square feet \*). Likewise, the ratio of two monetary amounts does not depend on the currency in which these amounts are expressed. It is only important that both amounts are expressed in the same currency.

You can divide named numbers into each other, expressing completely different concepts, for example, rubles per square meters. A plot of land of 100 $м^2$, which costs 100 rubles, is sold at a price of 1 ruble for 1 $м^2$. But the numerical expression of the result depends on the currency in which the amount is expressed and in what units the area was measured. In other words, as a result of such division, a named value is obtained again. Another example is the speed

---
\*) 1 arshin $= 71{,}1$ *cm*; 1 foot $= 30{,}5$ *cm*.

⟦folio 9⟧

⟦folio 10⟧

growth - so many units of length per unit of time. Sometimes the unit of speed is given a special name: one nautical mile (or $1852$ *m*) per hour - one knot.

Every equation in physics expresses a relationship that objectively exists in nature, regardless of the will of the one who writes this equation. And, of course, both sides of the equation must be expressed in quantities measured in the same units.

The units of measurement of each physical quantity are expressed through basic units of measurement, the choice of which is largely arbitrary. A formula expressing the unit of measurement of a given quantity through the basic units of measurement is called the dimension of this quantity. Both sides of every physical equation must have the same dimension.

How many basic units of measurement should you choose? Mechanical motion is described in terms of distance, that is, length, and time. Standards of these two quantities are necessary in any case. But two standards are not enough. Indeed, if, for example, two bodies of the same shape and size interact, then their accelerations can be significantly different. The acceleration of each of them, according to Newton's second law, depends on its mass. Therefore, at least one more standard is needed—mass. At present, no physical laws in mechanics are known, for the description of which new basic standards would be needed, except for length, time and mass. The corresponding symbols $\mathrm{L}$, $\mathrm{T}$ and $\mathrm{M}$ are introduced for the units of measurement of these basic quantities. To denote the dimension of any quantity $A$, use the symbol $[A]$. Thus, the dimension of length is denoted $[l] = \mathrm{L}$, the dimension of time is $[t] = \mathrm{T}$, and the size

⟦column⟧

the dimension of mass is $[m] = \mathrm{M}$. Length, time and mass are called fundamental quantities, and all other physical quantities are called derivatives.

Note that it makes sense to talk about dimension only in relation to a certain system of units. Formulas for the dimension of the same physical quantity in different systems of units can be different. In this article we will mainly use the GHS system. In this system of units, all dimension formulas have the form of power functions of the type

$$[f] = \mathrm{L}^{\alpha}\,\mathrm{M}^{\beta}\,\mathrm{T}^{\gamma}.$$

This type of formula is due to the following physical considerations. Obviously, the ratio of two numerical values ​​of any derived quantity should not depend on the choice of units of measurement of the basic quantities. For example, whether we measure time in seconds or minutes, the ratio of two intervals of time measured in seconds will be the same as the ratio of those intervals measured in minutes. And this requirement is always met provided that the dimension formula has the form of a power monomial.

Let us now consider the dimensions of some derived physical quantities. Let's start with the kinematic quantity - acceleration $a$. By definition, this is the change in speed per unit time. Therefore, the dimension of acceleration is the dimension of speed divided by time, that is

$\dfrac{\mathrm{L}}{\mathrm{T}} : \mathrm{T}$, or

$$[a] = \frac{\mathrm{L}}{\mathrm{T}^2}.$$

According to Newton's second law, force $F$ is equal to mass times acceleration. From here you can get the dimension of force:

$$[F] = [m]\,[a] = \left[\frac{ml}{t^2}\right] = \frac{\mathrm{ML}}{\mathrm{T}^2}.$$

**Heuristic value of dimension**

So, physical equality can only make sense between quantities of the same dimension. If, say, when solving a problem, a check showed that the dimensions of both sides of the resulting equality do not coincide, then an error was made in the solution.

The purpose of this article is to show that the concept of dimension helps not only to find errors, but also to obtain new results.

Even those who have forgotten Archimedes’ law itself, of course, remember the legend that Archimedes, when discovering this law, exclaimed “Eureka,” which translated from Greek into Russian means “found.” Hence the adjective “heuristic”, which in Russian means “helping to find”, or “guiding”, “indicating the truth”. It is this meaning of dimension theory that will be discussed in this article.

Let's consider the connection between Newton's law of gravitation and Kepler's third law. There is no need to formulate Kepler's law in advance: it will emerge from further reasoning. In order not to write only formulas, let’s give free rein to our imagination and try to compose a science fiction story.

So, let a family of astronauts flying to a distant star have a child born on the way. When he grew up, his father wanted to help him get a visual idea of ​​his native Earth and its companion, the Moon. For this purpose, it was decided to launch an artificial satellite of the spacecraft. Is it possible to do this in such a way that the satellite orbits the spacecraft in the same time it takes the Moon to orbit the Earth? What should be the other parameters that describe the motion of such a satellite?

Galileo also established that in vacuum all bodies fall freely with equal accelerations. This law

⟦column⟧

valid if the mass of the attracted body is many times less than the mass of the attracting body. Let the mass of the spacecraft intended for further travel be about 100 *t*. Then Galileo's law can be applied, for example, to a children's ball taken as a satellite of this ship. Usually the mass $m$ of such a ball is no more than 1 *kg*, which, indeed, is much less than the mass of the ship.

The law of universal gravitation in its elementary form $\left(F = \gamma\,\dfrac{m_1 m_2}{r^2}\right)$ is applicable to material points, that is, to bodies whose dimensions are much smaller than the distance between them. Let's assume that the distance from the spaceship to the ball is much greater than the ship in any of its dimensions (this will be confirmed by calculations later). The orbit of the Moon is approximately circular, therefore, the orbit of the ball must also be circular - otherwise there will not be the desired similarity. Such an orbit is characterized by a radius $r$ and an orbital period $\tau$. We will show how to find the period of revolution from the study of the dimensions of physical quantities.

Since the gravitational force $F$ for given material points depends only on the distance between them, and in a circular orbit the distance does not change, the force is also constant in magnitude. It is this force that can impart the necessary centripetal acceleration to the satellite. But instead of writing the corresponding equation of motion and finding the period of revolution from it, we will use only dimensions. We are given the following constant quantities: force $F$ of dimension $\dfrac{\mathrm{ML}}{\mathrm{T}^2}$, orbital radius $r$ of dimension $\mathrm{L}$ and mass $m$ of a moving body of dimension $\mathrm{M}$. We need to find the orbital period $\tau$ of dimension $\mathrm{T}$.

We will look for an expression for the circulation time in the form

$$\tau = A F^x r^y m^z,$$

⟦folio 11⟧

⟦folio 12⟧

where $x$, $y$ and $z$ are unknown exponents, $A$ is some abstract number. Let us rewrite the equation for $\tau$ as an equality of dimensions:

$$[\tau] = |F|^{x}\,[r]^{y}\,[m]^{z} = \left(\frac{\mathrm{ML}}{\mathrm{T}^{2}}\right)^{x}\ \mathrm{L}^{y}\ \mathrm{M}^{z}.$$

We write the left side as $\mathrm{M}^{0}\mathrm{L}^{0}\mathrm{T}^{1}$ and the right side as $\mathrm{M}^{x+z}\mathrm{L}^{x+y}\ \mathrm{T}^{-2x}$ and compare the exponents of $\mathrm{M}$, $\mathrm{L}$ and $\mathrm{T}$. We get three equations with three unknowns:

$$\begin{array}{c} x + z = 0,\\ x + y = 0,\\ -2x = 1. \end{array}$$

Hence $x = -\dfrac{1}{2}$, $y = \dfrac{1}{2}$, $z = \dfrac{1}{2}$.

Therefore, the desired expression for $\tau$ should have the form

$$\tau = Am^{1/2}r^{1/2}F^{-1/2} = A\left(\frac{mr}{F}\right)^{1/2}. \qquad (1)$$

If the astronauts want the ball's orbital period to be equal to the Moon's orbital period around the Earth, they must select the appropriate quantities so that the ratio $\frac{mr}{F}$ is the same as for the Moon. How to do this?

Let us write down the expression for the force of attraction $F$:

$$F = \gamma\,\frac{mM}{r^{2}}. \qquad (2)$$

There are two new quantities here: the mass of the attracting body $M$ and the universal constant of gravity $\gamma$. Let us substitute the expression for the force $F$ into equality (1) and write this equality twice:

for the Earth-Moon system

$$\tau_{1} = A\left(mr_{1}\ \frac{r_{1}^{2}}{mm_{1}\gamma}\right)^{1/2} = A\left(\frac{r_{1}^{3}}{m_{1}\gamma}\right)^{1/2} \qquad (3)$$

($m$ is the mass of the Moon, $m_{1}$ is the mass of the Earth, $r_{1}$ is the distance from the Moon to the Earth);

for the ship-ball system

$$\tau_{2} = A\left(\frac{r_{2}^{3}}{m_{2}\gamma}\right)^{1/2} \qquad (4)$$

($m_{2}$ is the mass of the ship, $r_{2}$ is the distance from the ball to the ship).

⟦column⟧

Then the ratio of the periods of revolution

$$\frac{\tau_{1}}{\tau_{2}} = \left(\frac{m_{2}}{m_{1}}\ \frac{r_{1}^{3}}{r_{2}^{3}}\right)^{1/2}. \qquad (5)$$

Earth mass $m_{1} = 6\cdot10^{27}$ *g*, ship mass $m_{2} = 100\ m = 10^{8}$ *g*, lunar orbit radius $r_{1} = 3{,}84\cdot10^{10}$ *cm*. The astronauts want $\tau_{1} = \tau_{2}$. To do this you need to take $r_{2} \approx 10^{4}\ см = 100\ м$. It is easy to check that under these conditions the ball will go around the ship in the same amount of time as the Moon goes around the Earth, that is, in 29 days.

Let us rewrite equality (5) as follows:

$$\frac{\tau_{1}^{2}}{\tau_{2}^{2}} = \frac{m_{2}}{m_{1}}\ \frac{r_{1}^{3}}{r_{2}^{3}}. \qquad (6)$$

If two different bodies revolve around a common center (that is, $m_{1} = m_{2}$), such as, for example, the planets of the solar system, then equality (6) expresses Kepler’s third law \*): the squares of the revolution times of the planets are related as the cubes of their average distances to the Sun. The word “average” could be omitted, because the ellipses of planetary orbits are slightly elongated and close to circles.

Let us remember that Kepler lived before Newton. In fact, the law of gravity was derived from Kepler's laws, and not vice versa, as was done in our “science fiction” example and as is now done in physics and astronomy textbooks. Let us show that to derive the law of gravitation from Kepler's laws it is enough to use the doctrine of dimensions. Thus, we once again emphasize the heuristic, that is, guiding power of dimensions.

---

\*) Let us give the formulations of Kepler’s first two laws.

I. The planets describe ellipses, at one of the foci of which the Sun is located.

II. The radius vector connecting the Sun with the planet sweeps equal areas at equal intervals of time.

Note that the III law in a more general form is formulated as follows: the squares of the periods of revolution of the planets are related as the cubes of the semi-major axes of the orbits.

Let us assume that the force of attraction of the planets to the Sun has the form

$$F = Bmr^n. \qquad (7)$$

Here $B$ is a value that is the same for all planets, $m$ is the mass of the planet, $r$ is the distance from the planet to the Sun. How can one guess that the force $F$ depends on the mass $m$ exactly linearly? This can be seen from Galileo's law: the accelerations of all bodies under the influence of gravity at the same distance from the attracting body are the same. But the acceleration is equal to the force divided by the mass of the body, so the acceleration during free fall of bodies can be the same only in the case when the force is proportional to the mass. We will consider the exponent $n$ in the law of gravitation to be unknown for now; we have to determine it from Kepler’s law. After all, we seem to have taken the place of Newton and want to come to the law of gravitation, knowing the general law of motion (that is, Newton’s second law) and the results of the previously living Kepler and Galileo.

Reasoning in the same way as when deriving formula (5), using assumption (7), we obtain

$$\frac{\tau_1}{\tau_2} = \left(\frac{r_1}{r_2}\right)^{\frac{1-n}{2}} \qquad (8)$$

For this equality to coincide with Kepler’s law, it is necessary to put $n = -2$, and this leads expression (7) to Newton’s law, according to which the gravitational force is inversely proportional to the square of the distance between bodies.

One may also ask why the law of attraction was chosen in advance in power form (7)? The point is that only the ratio of power functions gives the same power function of the ratio. Equality

$$\frac{f\,(r_1)}{f\,(r_2)} = f\left(\frac{r_1}{r_2}\right)$$

executed only if $f\,(r) = r^n$. Namely, the power function of the ratio is included in Kepler’s third law:

$$\frac{\tau_1}{\tau_2} = \left(\frac{r_1}{r_2}\right)^{3/2}.$$

⟦column⟧

Thus, of necessity, the Newtonian law of gravitation is obtained from the laws of Kepler and Galileo.

**Dimensions of universal constants**

The law of gravitation includes a universal constant $\gamma$, which is the same for all bodies. Physics also knows other universal constants. For example, the speed of light in vacuum $c$, Planck's constant $h$, elementary electric charge $e$, etc.

Let us determine in what units $h$ and $e$ are measured, and find the dimensions of these quantities.

For an electromagnetic wave of frequency $\nu$ the following equality is true:

$$E = h\nu, \qquad (9)$$

where $E$ is the energy transferred by the wave. The quantity $h\nu$ is called a quantum of energy. Since frequency is the number of oscillations per unit time, $\nu$ has the dimension of inverse time:

$$[\nu] = \left[\frac{1}{t}\right] = \frac{1}{\mathrm{T}}\,.$$

The universal coefficient of proportionality between energy and frequency is Planck's constant $h$. The dimension $h$ is thus the dimension of energy times time

$$[h] = [Et].$$

The dimension of energy can be determined in two ways. Either this is the dimension of work - that is, force multiplied by the path -

$$[E] = [Fl] = \left[\frac{ml^2}{t^2}\right] = \frac{\mathrm{ML}^2}{\mathrm{T}^2}\,,$$

or the dimension of kinetic energy $\dfrac{mv^2}{2}$ —

$$[E] = [mv^2] = \left[\frac{ml^2}{t^2}\right] = \frac{\mathrm{ML}^2}{\mathrm{T}^2}\,.$$

In both cases the dimension must be the same. From here

$$[h] = \left[\frac{ml^2}{t}\right] = \frac{\mathrm{ML}^2}{t}\,.$$

⟦folio 13⟧

⟦folio 14⟧

Now, using Coulomb’s law, we will find the dimension of the electric charge $e$ (in the SGSE system of units). Let us assume that two unit charges in a vacuum at a unit distance repel each other with a force equal to one. Since the units of length and force are defined in mechanics, the unit of charge can be found through M, L and T. According to Coulomb's law

$$F_\text{э} = \frac{e^2}{r^2},$$

where $F_\text{э}$ is the electrostatic force. Its dimension, like the dimension of any force, is $\dfrac{\mathrm{ML}}{\mathrm{T}^2}$. Therefore, the dimension of the squared charge is equal to

$$[e^2] = \frac{\mathrm{ML}^3}{\mathrm{T}^2},$$

and the charge dimension is

$$[e] = \frac{\mathrm{M}^{\frac{1}{2}}\,\mathrm{L}^{\frac{3}{2}}}{\mathrm{T}}. \qquad (10)$$

**Natural units of measurement**

All our previous discussions about dimensions were based on an arbitrary choice of basic units of measurement - centimeter, gram, second. For these units (or for multiples of them), corresponding standards of length, mass and time were created.

It is known that storing and reconciling metric standards is very difficult. The famous Parisian meter standard, made of an alloy of platinum and iridium, has somewhat changed its length and continues to change due to recrystallization processes. The earth does not rotate around its axis strictly evenly, so the time standard also has an error. The mass of one cubic decimeter of water at $4^\circ$ C (this was the original mass standard of 1 *kg*) depends on the source of water: ordinary water contains H$_2$O as an impurity.

⟦column⟧

The quality of heavy water in which one of the hydrogen atoms is replaced by deuterium. That's why scientists have to look for more reliable standards.

Fortunately, such more reliable standards exist; nature itself stores them without any effort on our part. Such standards have already been partially listed: the speed of light $c$, the elementary charge $e$ and other universal constant quantities. In other words, instead of standards of length, time and mass, you can choose standards of other quantities, not made artificially, but contained directly in the laws of physics. The number of basic quantities, and therefore the basic units of measurement, can, generally speaking, be chosen arbitrarily. But it turns out that it is most convenient to choose three basic quantities. Which triplets of quantities are suitable for this purpose, and which do not provide a complete description of the dimensions?

For example, we will show that if $e$ and $h$ are chosen as standards, then it is impossible to choose $c$ as the third standard. Let's compose the relation $\dfrac{e^2}{h}$ and find its dimension (for example, in the CGS system):

$$\left[\frac{e^2}{h}\right] = \left[\frac{ml^3}{t^2}\,\frac{t}{ml^2}\right] = \left[\frac{l}{t}\right] = \frac{\mathrm{L}}{\mathrm{T}}.$$

This is the dimension of speed, which means that the value $\dfrac{e^2}{h}$ can well serve as a standard of speed, so the speed of light $c$ is no longer needed as a standard.

Which third standard should we choose?

If we are interested in the behavior of electrons in atoms, then it turns out that to describe it it is reasonable to take the electron mass $m$ as the third fundamental quantity. Let us also add that the equations for electrons actually include not the value $h$ itself, but $h$ divided by $2\pi$. This quotient is usually denoted $\hbar$.

Then it is convenient to choose the following as three independent standards:

common values: $e$, $\hbar$ and $m$. The dimension of none of them can be expressed through a combination of the dimensions of the other two, which is easy to verify with a few attempts.

If we want to find the radius of the electron’s orbit in the system of units we have chosen, a quantity that has the dimension of length, then, using the method of dimensions, we obtain the expression

$$r = \frac{\hbar^2}{me^2}, \qquad (11)$$

that is, the dimension of length in our system

$$[r] = \frac{[\hbar^2]}{[m]\,[e^2]}\;.$$

It is easy to check by substituting the dimensions for $\hbar$, $m$ and $e$, for example, in the CGS system (this is the system of units most often used by physicists), that the quantity $\frac{\hbar^2}{me^2}$ indeed has the dimension of length:

$$\left[\frac{\hbar^2}{me^2}\right] = \left[\frac{m^2l^4}{t^2}\;\frac{1}{m}\;\frac{t^2}{ml^3}\right] = [l] = \mathrm{L}.$$

Similarly, from the quantities $\hbar$, $m$ and $e$ one can uniquely obtain a quantity with the dimension of energy:

$$E = \frac{me^4}{\hbar^2}, \qquad (12)$$

that is

$$[E] = \left[\frac{me^4}{\hbar^2}\right].$$

Let the reader be convinced by the way in which formula (7) was obtained that other quantities with such dimensions cannot be constructed from $e$, $\hbar$ and $m$.

Formulas (11) and (12) contain results of fundamental importance; they make it possible to estimate, at least in order of magnitude, the quantities characterizing an atom: its dimensions, the energy required to remove an electron from it. The exact values ​​of these quantities are obtained by strictly solving the corresponding equations. But no matter how strictly it is decided

⟦column⟧

equation, the answer must always have the same dimension, and it is uniquely determined by formulas (11) and (12). There remains, of course, the question of numerical coefficients for dimensional quantities. These coefficients can only be obtained from rigorous solutions. It turns out that in a number of cases the numerical coefficients differ from unity by no more than 2-3 times. For example, for an electron in a hydrogen atom, the value of the electron orbital radius from formula (11) is obtained absolutely exactly:

$$r = \frac{\hbar^2}{me^2} = 0{,}5\cdot 10^{-8}\ \textit{см},$$

and the ionization energy value

$$E = \frac{me^4}{\hbar^2} = 4{,}3\cdot 10^{-11}\ \textit{эрг}$$

turns out to be 2 times larger than true.

Some natural units of measurement can be obtained from outside the atomic world, for example, by choosing the speed of light $c$ and the gravitational constant $\gamma$ as the basic quantities. They provide standards as reliable as $e$, $\hbar$ and $m$. But from two standards it is impossible to obtain any values. The third standard is taken arbitrarily.

If we leave aside the value $c$, then in addition to $\gamma$ we will need two arbitrary standards. You can take a centimeter and a second as such standards, then you won’t need a gram. After all, instead of it, the gravitational constant was taken, equal in the GHS system $6{,}7\cdot10^{-8}$ *cm³/g s²*. But now it is taken as a unit, so the unit of mass is not one gram, but a new value equal to $1/(6{,}7\cdot10^{-8})$ grams, which, as you can easily see, is approximately 15 tons. Such a unit would be convenient for wholesale trade with representatives of extraterrestrial civilizations if they agree to choose the centimeter and second as the other two units.

⟦folio 15⟧

## Mechanics of liquids and gases and similarity theory

When an airplane or ship is designed, an artist first draws it according to the designer's plans to outline the general proportions. Using this figure more detailed drawings are made and calculations are made. But the most advanced calculations cannot provide for everything - after all, a new design must also have new properties. If you immediately build an airplane or ship according to drawings and calculations, then testing them will be too dangerous and the development of serial production will be very expensive. Therefore, first a scaled-down model similar to the designed product is made and tested in a wind tunnel or in a pool for experiments with ships.

Under what conditions will the flow of air or water around the model be similar to the flow around the original? In other words, when will you get a model, and not just a toy, that looks similar to the object, even if it’s a detailed reduced copy?

Based on the doctrine of dimensions, we can give a general answer to the question posed. True dynamic similarity between an object and a model will be obtained when the ratios of all quantities included in the equations of motion of a gas or liquid are the same for nature and for the model. What are these quantities?

Since the model is geometrically similar to life, all its dimensions are determined by one single size. If, for example, in reality the wingspan of an aircraft is 50 *m*, and the fuselage length is 30 *m*, then a model with a wingspan of 10 *m* should have a fuselage of 6 *m*. Then it is enough to make all comparisons with one selected size $d$.

A flowing liquid or gas is characterized by speed $v$. When modeling, they make sure that the model itself is at rest, and gas or liquid flows onto it. All relative

⟦column⟧

the speeds will not change as a result, but they are the only ones that are important for testing dynamic properties. It is enough to compare with one characteristic speed, which is taken as the speed of the flow or the speed of the object itself (in nature). From a mechanical point of view, it does not matter what exactly to choose. In addition to speed, a moving medium is characterized by density $\rho$, that is, mass per unit volume. Liquids and gases also differ in viscosity: water flows lighter than vegetable or lubricating oil, oil flows lighter than honey, etc. In other words, the flow depends on a special characteristic of the medium, called *viscosity coefficient* $\eta$.

Let's find out what dimension $\eta$ has. Back in the last century, Poiseuille experimentally established that the speed with which a liquid flows through a narrow capillary is directly proportional to the pressure difference $\Delta p$ (at different ends of the capillary), the square of its radius $r$ and inversely proportional to the length of the capillary $l$ and the coefficient $\eta$. Let us write the corresponding equation for dimensions:

$$[v] = \left[\frac{\Delta p r^2}{\eta l}\right].$$

Hence the dimension $\eta$

$$[\eta] = \left[\frac{\Delta p r^2}{v l}\right].$$

But the product $\Delta p r^2$ has the dimension of force (pressure is force per unit area), so

$$[\eta] = \left[\frac{mlt}{t^2 ll}\right] = \left[\frac{m}{lt}\right] = \frac{\mathrm{M}}{\mathrm{LT}}.$$

In the GHS system, the unit of measurement of the viscosity coefficient is called “poise” (named after Poiseuille). One poise - high viscosity; for example, water at room temperature has a viscosity of only $0{,}01$ poise.

So, with uniform motion of an object in a medium, its flow around it is completely determined by four quantities $d$, $v$, $\rho$ and $\eta$. For a given shape of the streamlined bodies, the flow patterns are completely

⟦folio 16⟧

are completely similar if the dimensionless ratios of dimensional quantities are the same. But it turns out that from the four listed dimensional quantities, only one dimensionless combination can be constructed. It is called the Reynolds number and is denoted by the symbol $\mathrm{Re}$:

$$\mathrm{Re} = \frac{dv\rho}{\eta}.$$

(Here you can again use the method of unknown exponents $x$, $y$, $z$, as in deriving formula (1).)

Two flows that have the same numbers $\mathrm{Re}$ are similar in everything. (Strictly speaking, this is true as long as it is not necessary to take into account the compressibility of the medium, which gives an extra constant in the equations of motion. This will happen at speeds close to the speed of sound, but we will leave this question aside). Note that if it is possible to construct several dimensionless relations from quantities characterizing the flow, then dynamic similarity is achieved only if all relations that do not have dimension are equal. Indeed, only in this case can two phenomena be considered similar and from the given characteristics of one phenomenon it is possible to obtain the characteristics of the other by simple recalculation, just as we move from one system of units to another.

For example, let’s say that the model being tested is 5 times smaller than the original. Then you need to either blow it at a speed five times greater, or instead of air take gas, for which the ratio $\frac{\rho}{\eta}$ is 5 times greater than for air, or change both the speed and the gas, but so that $\mathrm{Re}$ does not change. Thus, it is possible, in particular, to measure lift or air resistance for a model aircraft and recalculate them for real life. The forces acting on individual points of the aircraft are also determined, which is important for strength calculations.

2 Quantum No. 1

⟦column⟧

Based on the dimensions of the quantities, it is possible to show how the conversion is made from the model to the object. From $d$, $v$, $\rho$ and $\eta$ a quantity with the dimension of force can be constructed in two ways:

$$F_1 = \rho v^2 d^2$$

And

$$F_2 = d\eta v.$$

Which one should you prefer? Let's take the relation $\frac{F_1}{F_2}$:

$$\frac{F_1}{F_2} = \frac{dv\rho}{\eta} = \mathrm{Re}.$$

It turns out that this ratio is equal to the Reynolds number. Therefore, if the model and the real have the same Reynolds numbers, both expressions for the force are equivalent and you can use either one. Thus, the force acting on the model differs as many times from the force in nature as the products $dv\eta$ (or $\rho v^2 d^2$) for the model and for nature differ.

With this specific example, we wanted to show that dimensional theory underlies modeling.

⟦figure⟧

⟦folio 17⟧
