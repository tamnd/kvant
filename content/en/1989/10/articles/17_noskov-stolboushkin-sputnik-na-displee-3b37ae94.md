---
id: 1989-10-noskov-stolboushkin-sputnik-na-displee-3b37ae94
issue: kvant_1989_10
year: 1989
number: "10"
title: Satellite on display
authors:
  - Носков Н. Н.
  - Столбоушкин С. К.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 66
page_labels: 60-64
tag: 5ZN9
lang: en
source: kvant_digital
extraction: vision
content_sha256: a384e871ff04a4826e500eb276314d7d777b968d7547fee14abd88f416db2d6d
prompt_sha256: draft-1
translated_from: content/ru/1989/10/articles/17_noskov-stolboushkin-sputnik-na-displee-3b37ae94.md
source_content_sha256: f8980b900901d96ef33eb426d8696f5a4d7baa18f064a9f79c7b2fd2f196e457
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Satellite on display

N. N. NOSKOV, S. K. STOLBOUSHKIN

Before Newton, the movement of various bodies, such as planets, seemed a mystery to scientists, but after Newton’s discovery everything suddenly became clear.

R. Feynman

We all once built models of ships or models of houses and cities. Would you like to make a working model of the Universe, or at least the Solar system? It is quite possible to build such a model, and a computer is a very convenient tool for creating it.

We will start with a simple one - with a model of the movement of the Earth's satellite. First, we will deal with the theoretical formulation of the problem, i.e., we will establish the physical laws that determine the motion of the satellite, and then we will compile an algorithm that can be used to write a computer program.

1. Statement of the problem

Simplifications are inevitable when modeling. Therefore, to begin with, we will assume that there are only two bodies in space: the Earth and the satellite. To build a model of their interaction, you need to know the physical laws that determine their movement. These laws are two: Newton’s second law and the law of universal gravitation, discovered by him. In addition, you need to set the initial data. Let's start with this.

The only force acting on the satellite is the Earth's gravitational force. It can be calculated using the formula of the law of universal gravitation

$$F = G \frac{M_1 m_c}{R},$$

where $G$ is the gravitational constant, it is equal to $6,67 \cdot 10^{-11} \text{ m}^3 / (\text{кг} \cdot \text{с}^2)$;

$M_3$ is the mass of the Earth, equal to $5,98 \times 10^{24} \text{ кг}$;

$m_c$ is the mass of the satellite.

According to Newton's second law, the acceleration $\vec{a}$ of the satellite is equal to: $\vec{a} = \vec{F} / m_c$. Further, knowing the coordinates $\vec{S} \vec{\theta} = (x\theta; y\theta)$ and the speed $\vec{v} \vec{\theta}$ of the satellite at some point in time and the applied kinematrix

$$\vec{v} = v\theta + \vec{a} \Delta t, \quad \vec{S} = S\theta + \vec{v} \Delta t,$$

(1)

Kazalova, it is possible to determine the speed and position of the satellite through time $\Delta t$. But that's not true! The force acting on the satellite and the speed $\vec{v}$ will change in time $\Delta t$. What to do?

There is a way out. Let us assume that the time interval $\Delta t$, through which it is necessary to calculate the position and speed of the satellite, is small. Then during this time the distance from the satellite to the Earth will change slightly and by changing the force $\vec{F}$ and speed $\vec{v}$ it will be possible to run during this period of time. You just need to choose the values ​​$\Delta t$ wisely. The result of the calculation will be new values ​​of the satellite’s coordinates and speed. For them, you can repeat the same calculations with the same $\Delta t$ and obtain the next values ​​of coordinates and speed. Consistently applying this calculation scheme, we will obtain the coordinates of the satellite at successive moments of time $T1, T2, T3, ...$, and by connecting these points with straight segments, we will obtain a broken line that approximates

⟦folio 61⟧

but represents the satellite's trajectory (Fig. 1). Such broken lines are called Euler's broken lines, and the calculation method itself also bears the name of Leonhard Euler, the great Russian scientist of the 18th century.

Euler's method is used not only to find the trajectories of celestial bodies. It is used to solve a wide class of equations called differential equations. Our original equation (Newton's second law) is also differential. Moreover, Euler's method is used to solve equations that cannot be solved by exact methods.

Now, knowing Euler's method, we can draw up a detailed scheme for calculating the trajectory of a satellite in low-Earth orbit.

Since the satellite’s orbit is located in the same plane as the center of the Earth, we will establish a coordinate system so that the orbital plane coincides with the $xy$ plane. In this case, the coordinate $z$ is always zero and can be ignored. Let's place the origin of the coordinate system at the center of the Earth (see Fig. 2). Let the distance from the center of the Earth to the satellite be $R$, and its speed relative to the Earth be $\vec{v}$. In order to unambiguously determine the position of the satellite, the value $R$ alone is not enough. It is necessary either to add the angle $\alpha$ to $R$, at which the satellite is visible from the origin, or together with the pairs $R$, $\alpha$, specify a pair of coordinates $x, y$.

If the distance $R$ and angle $\alpha$ are known, then the coordinates $x, y$ can be determined using the formulas $x=R \cos \alpha, y=R \sin \alpha$.

The speed of the satellite and the force of the Earth's tension are vector quantities; let us decompose them into components along the $x, y$ axes. From the similarity of the corresponding triangles on figure 2 it is clear that

$$\frac{F_x}{F} = -\frac{x}{R}, \quad \frac{F_y}{F} = -\frac{y}{R},$$

from here

$$F_x = -|F|x/R, \quad F_y = -|F|y/R.$$

If only the Earth's tension acts on the satellite, then Newton's second law can be written in the form

$$m_c a_x = -G \frac{M_3 \cdot m_c}{R^2} \frac{x}{R}, \quad m_c a_y = -G \frac{M_3 \cdot m_c}{R^2} \frac{y}{R}.$$

Reducing by $m_c$ and substituting the acceleration value into kinematics formulas (1), we obtain formulas for calculating new values ​​of coordinates and velocity components through time $\Delta t$:

$$x^\mathrm{H} = x + v_x \Delta t, \quad y^\mathrm{H} = y + v_y \Delta t, \quad v_x^\mathrm{H} = v_x - G \cdot M_3 x \Delta t/R^3, \quad v_y^\mathrm{H} = v_y - G \cdot M_3 y \Delta t/R^3.$$

Formulas (2) represent a ready-made algorithm diagram for a computer. We will present the implementation of this algorithm. But first, let's figure out how to set the step $\Delta t$. There are special methods for calculating the step so that after a long time the error in calculating coordinates does not exceed a predetermined value. We will do it simpler - we will select the step value using the experimental method. To do this, you need to choose an arbitrary $\Delta t$ and find a solution for this value. Then reduce the step by half and find the trajectory again. If the solution for the new $\Delta t$ is indistinguishable from the previous one, then we will assume that the choice of step is satisfactory.

Now you can start implementing the model on a computer.

2. Programming

We have an algorithm for calculating the satellite’s trajectory, i.e. a set of formulas (2) that allow the location and speed of the satellite at any time. But if you apply

⟦folio 62⟧

these formulas are in SI, then all quantities will have greater values ​​corresponding to cosmic scales. Therefore, it is advantageous to create your own system of units in which the product $GM_3$ is equal to one. This will work out if we take the radius of the Earth as the unit of length, and the first cosmic velocity $v_{1k} = \sqrt{GM_3/R_3}$ as the unit of speed. In this case, the time will change in units of $R_3/v_{1k}$. The relationship between the units of the new measurement system and SI for the Earth will be as follows: unit of length - $6,38 \cdot 10^6$ m, speed - $7,8 \cdot 10^3$ m/s, time - $0,82 \cdot 10^3$ s, and formulas (2) take the form
$$x^H = x + v_x \Delta t,$$
$$y^H = y + v_y \Delta t,$$
$$v_x^H = v_x - x \Delta t/R^3,$$
$$v_y^H = v_y - y \Delta t/R^3.$$
The formulas have become more suitable for calculation and, most importantly, universal. They “work” not only for the Earth, but also for any cosmic body, naturally, in a system of units in which the unit of length is the radius of this body, and the unit of speed is the first escape velocity for this body.

The last thing we need to do before writing the program is to understand what a graphical screen is and how to place our model on it. The display in high-resolution graphics mode is a rectangular field of dots of size $m \times n$. The $x$ axis on it is always located from left to right, and the $y$ axis can be located either from top to bottom or from bottom to top. Let's assume that the axis $y$ goes upward and that $m=n=256$. To display a point on the screen, you need to specify its coordinates and color. To draw a line, you must specify the coordinates of the starting and ending points. To depict a circle, you must specify the coordinates of the center and the radius. We will denote the operators for these actions as follows:
dot(X,Y), color;
line (X1, Y1) - (X2, Y2), color;
circle (X, Y), R, color.

However, you cannot simply take physical coordinates as screen coordinates. As you remember, we took the radius of the Earth as one, and placed the origin of coordinates at the center of the Earth. Now we need to place the center of the Earth in the center of the screen (a point with coordinates ($X_\pi$, $Y_\pi$), for example (128, 128)) and notify everything $k$ times. The following formulas are obtained: if the physical coordinates of the point (satellite) are $x, y$, then the coordinates on the display

$$XD = X_\pi + k*x, \quad YD = Y_\pi + k*y.$$

We will determine the value of $k$ later.

Now you can move directly to drawing up the program. First, we will build a general diagram, and then we will detail it. In the approximation group, the program for the motion of the Earth satellite can be written in the following form:

start
input of initial data;
preparation of graphic display;
draw the Earth and satellite;
repeat
calculate new coordinate values;
draw a trajectory segment and a satellite in a new position;

end repeat end.

The first two instructions do not cause problems. Let the satellite at the initial moment of time TF be located on the axis $x$, then the initial coordinate $y$ must be set equal to zero and the distance $x$ must remain in units of the physical coordinate system, i.e. in units of the earth’s radius.

The initial speed is also simple in the form of a pair of numbers VX, VY. However, it turns out that it is more convenient to enter the value of the velocity model and its direction (angle with the $x$ axis), and then convert it into components of a direct coordinate system using the formulas

$$VX = V*\cos (y\theta*\pi/180),$$
$$VY = V*\sin (y\theta*\pi/180).$$

Expressions in parentheses are needed to convert an angle from degrees to radians,

⟦folio 63⟧

because in all languages ​​trionometric functions are calculated only in radians.

Preparing a graphic display is not difficult, just strictly follow the instructions for the computer. You can draw a border frame for aesthetics. If the graphic display also allows text output, then you can write the name of the task at the top or bottom of the screen. These additions are not necessary, but with them the picture looks much nicer. You can show your imagination and add some other accessories that await the picture.

Now let's depict the Earth and satellite. In order to draw, you need to determine the scale factor $k$. We propose to set it using the formula $k=100/x$. Then the image of the Earth and the satellite (with screens coordinates XD, YD) is realized by operators

circle (X$_\pi$, Y$_\pi$), $k$, blue;
XD←X$_\pi$+$k^*x$; YD←Y$_\pi$;

dot (XD, YD), red.

In this case, scaling is achieved automatically. If you decide to launch a satellite from the surface of the Earth, i.e. $x=1$, then the image of the Earth will take up almost the entire screen, its radius will be one hundred screen units. If the satellite is placed at a distance of $x=10$, then the Earth will occupy a circle with a radius of 10 points.

It remains to determine the time step T$\theta=\Delta t$. It was experimentally determined that a value in the range of 0.1–0.2 performs satisfactorily.

All preparatory actions are legal, let's start modeling the satellite flight based on formulas (3).

Repeat
XS←XD; YS←YD;
X←X+VX*T$\theta$;
Y←Y+VY*T$\theta$;
XD←X$_\pi$+$k^*X$;
YD←Y$_\pi$+$k^*Y$;

Line (XS, YS) - (XD, YD), blue;
Dot (XD, YD), red;

$R\leftarrow\sqrt{X^2+Y^2}$;
VX←VX-X*T$\theta/R^3$;
VY←VY-Y*T$\theta/R^3$;

End repeat.

As you probably agreed, XS and YS are the old satellite coordinate screens. Moreover, we don’t just draw a line or put an end to it, but we do both. As a result, a red dot will move across the screen, leaving a blue trail behind it. When drawing a line, you can only specify the coordinate of the end point if the computer remembers the starting point itself.

The practical program is finite; it remains to decide how the cycle should be repeated. You can set the number of repetitions in advance, but it is possible that we will get tired of working with the model before the cycle ends or, conversely, the cycle ends at the most interesting moment. Therefore, it would be more convenient to repeat the cycle according to our desire. For example, let's press some key. And one more condition for ending the loop must be added. The point is that if R<1, nothing prevents the program from continuing to run. And this means that the satellite of time enters the Earth and continues to move in its depths. Therefore, we maintain the so-called Boolean variable UPAL, which takes only two values: true and false. And we will calculate it like this: FALLED←(R<1). The condition is repeated in this case:

REPEAT UNTIL (FALLED) AND (KEY ≠“S”)

The cycle will continue until at least one of the conditions is violated.

We wrote a program in a hypothetical language. It can be easily translated into the language of any computer.

Now let's talk about what you can change and add to the program yourself. The first part of the changes concerns the natural design. If the satellite fell, then you can depict an explosion at the point of impact. And the satellite itself can be drawn not as a point, but in the form of a figure (for those skilled in the art of sprites, this

⟦folio 64⟧

won't be difficult). You can display the current speed and distance to the Earth after 10 or 20 cycles. This is the first thing that comes to mind. We hope you come up with something else.

In addition to additional artistic features, you can change the model itself. In this case, there is even more room for imagination. If in the formulas for VX and VY we replace the minuses with pluses, then the law of universal gravitation will turn into the law of universal repulsion. Thus, the satellite model will turn into a model of the interaction of one-dimensional charged particles. Or you can contribute to a non-existent Universe. The force in the law of gravity is inversely proportional to the square of the distance. What happens if it is inversely proportional to the cube or the first power of the distance? It is not difficult for us to facilitate this situation as well - it is enough to replace $R^3$ in the formulas with $R^4$ or $R^2$.

But the next change will require more work. We have created a model of the Earth's satellite, but we cannot control it. In addition, there are other bodies in space that can be flown on. It would be interesting to land the “Poprygunchik” on the “Soyuz” from “Phobos” on Phobos. We will deal with this in one of the next issues of the magazine.

Readers list:
who sent the correct solutions
(For the beginning, see p. 38)

48, 55, 58, 59; P. Molodov (Lomonosov) 55; S. Murin (Wrest) 59; V. Mytko (Leningrad) 48, 52, 55, 59, 60; A. Nasibov (Sheki district of the Autonomous Soviet Socialist Republic) 52; A. Nasirov (Sheki district of the Autonomous Soviet Socialist Republic) 52; N. Nemirovskaya (Kyiv) 48, 52, 58; A. Nikolaev (Kyiv) 48, 49; I. Novikov (Kaliningrad) 58; R. Novoselov (Moscow) 55, 58, 59, 61; D. Ometsinsky (Kyiv) 48, 49, 51, 58-61; V. Onishchuk (Minsk) 58, 59; G. Orener (Kyiv) 58; A. Orlovsky (Kyiv) 48, 49, 51, 58-61; D. Ostrovsky (Dnepropetrovsk) 60; A. Pavlotsuk (Kyiv) 49, 52, 58; Y. Paiko (Wrest) 58; P. Penzin (Kuibyshev) 58-60; M. Perepechko (Moscow) 55; S. Petukhov (Gorky) 52; I. Pilosin (Alma-Ata) 52, 58; N. Plakhtiy (Kyiv) 58; T. Podalyako (Leningrad) 58, 61; S. Podryatov (Kyiv) 49, 52; E. Pomarsky (Tashkent) 49, 52; V. Polushuk (Kanev) 51, 61; S. Polyshin (Kharkov) 52, 58-61; S. Ponomarenko (Novosibirsk) 49; S. Pogorochin (Izhevsk) 52, 55, 58, 60; E. Prizant (Odessa) 51, 55, 58, 59, 61; E. Proskurina (Kyiv) 58; V. Puzanov (Donetsk) 51; I. Ptaikin (Moscow) 55; A. Revsky (Moscow) 61; A. Raspereza (Wrest) 48, 49, 52, 55, 58, 61; I. Rassadin (Minsk) 52; R. Rolinsky (Kyiv) 52; A. Ruevsky (Ivano-Frankivsk) 52; R. Ruzev (Khankinsky district, Khorezm region) 52; I. Ryabova (Kharkov) 52, 59; A. Savin (Gorlovka) 58, 59, 61; A. Savchenko (Moshny village

Cherkasy region) 58, 59, 61; N. Samoilova (Kyiv) 58; A. Samuenko (Semipalatinsk) 48, 49, 55; S. Sevchenko (Minsk) 52; A. Skabelin (Baranovich) 48, 51, 55, 58-60; T. Skripnik (Kyiv) 48; V. Soldatov (Krasnorechensky settlement, Primorsky region) 55, 59; Yu. Spektor (Kyiv) 48, 51, 52, 58, 59, 61; Yu. Starostin (Yakutsk) 55; M. Subbotin (Stayy Oskol) 49; A. Suvkhanov (Chardzhou) 59; N. Suleymanov (Sheki district of the Autonomous Soviet Socialist Republic) 52; I. Sysovev (Semipalatinsk) 55, 59, 61; S. Tabaltsev (Moscow) 58; V. Tamoshina (Vilnius) 48, 49, 51, 52, 59; A. Tenekedzhi (Voronezh) 58, 59; S. Timashov (Alma-Ata) 48, 49, 55; M. Titov (Kyiv) 48, 55, 58-60; S. Tikhonov (Voronezh) 48, 51; R. Todorov (Varna, NRV) 52; A. Tutov (Riga) 51; D. Ukrainsky (Moscow) 58; A. Usinsky (village Ptichya, Rivne region) 48, 49, 52, 60, 61; Yu. Fenok (Kyiv) 58; L. Frenklakh (Voronezh) 58, 60; A. Fridlyand (Saratov) 48, 49, 55; G. Khachatran (Artashat district of Armenian SSR) 48; R. Christok (Kyiv) 48, 51; E. Chashechkina (Chernogolovka village, Moscow region) 48, 49, 52, 55, 58-60; I. Chemolosov (Moscow) 60, 61; L. Chernysheev (Moscow) 49, 59, 61; D. Chokin (Alma-Ata) 48, 49, 52, 55, 58, 61; V. Chuev (Stayy Oskol) 52; E. Shaarov (Grozny) 48, 59; A. Shazinyan (Rostov) 59; T. Sharafutdino (Ust-Kamenogorsk) 48, 49; E. Shvets (Chernivtsi) 49, 52, 60; S. Shinkevich (Verezniki) 48, 49, 51, 52, 58-60; S. Shubsky (Rest) 48; I. Shulyak (Kyiv) 52, 55, 58-60; K. Shurunov (Kuibyshev) 58, 59; N. Sherbina (Artemovsk) 52; M. Entit (Tula) 48, 49, 51, 52, 55, 58-61; V. Yurasov (Volgodonsk) 55; I. Yaholtser (Chernivtsi) 52, 55, 58, 59.
