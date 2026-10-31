---
id: 1970-9-resheniya-8a9c9911
issue: kvant_1970_9
year: 1970
number: "9"
title: '[Solutions to problems M6—M7; F8—F11]'
rubric: zadachnik-kvanta
page_first: 52
page_last: 59
page_labels: 50-57
tag: 0QT0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3f1939b5cc33f8d7a290cf4dad14d2df5478bd420529260efe64ae4ec15343a2
prompt_sha256: draft-1
translated_from: content/ru/1970/09/articles/10_resheniya-8a9c9911.md
source_content_sha256: 50c31dc3606f9a3fed8eb6a238171e95328156b388a567fc6e0e58166b98ebd3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

M6. There is a clock in front of you. How many hand positions are there that cannot be used to determine the time unless you know which hand is the hour hand and which hand is the minute hand?
(It is believed that the position of each of the arrows can be determined accurately, but following how the arrows move cannot.)

Answer. There are 132 such positions. In other words, there are 66 pairs of hand arrangements such that in each of these pairs one arrangement is obtained from the other by replacing the hour hand with the minute hand and the minute hand with the hour hand (as with Fig. 1); Of course, such positions are not considered when the directions of the hour and minute hands coincide: in these cases, the time is determined unambiguously.

Solution and e. We got many different solutions to this problem. Let's list some of them. Here's the most common one.

Let's assume that the dial is divided into 12 parts. Let's consider one of the positions of the arrows that are discussed in the conditions. Let one arrow occupy the position $x$, the other - $y$; here $0 \leq x < 12$, $0 \leq y < 12$. If the first hand is considered to be the hour hand, and the second hand is considered to be the minute hand, then the equality must be fulfilled

$$x = a + \frac{5y}{60},$$

(1)

Fig. 1.

⟦folio 51⟧

Fig. 2.

where $a$ is an integer number of hours, $0 \leqslant a \leqslant 11$.
Similarly, if the first hand is the minute hand and the second hand is the hour hand, then
$$y = b + \frac{5x}{60},$$

where $b$ is an integer, $0 \leqslant b \leqslant 11$.
The system of two equalities (1) and (2) can be replaced by equivalent ones:

$$\begin{cases}
12x = 12a + y, \\
12y = 12b + x, \\
143x = 12(b + 12a),
\end{cases}$$

$$\begin{cases}
x = 12 \cdot \frac{b + 12a}{143}, \\
y = 12 \cdot \frac{a + 12b}{143}.
\end{cases}$$

Here $0 \leqslant a \leqslant 11, 0 \leqslant b \leqslant 11$ are integers. Every pair $(x, y)$ satisfying this system is a solution to it. There are only $12^2 = 144$. It is clear that the case when $x = y$, that is, when $a = b$, must be excluded. 132 remain.

Two of them - the corresponding $a = 2, b = 5$ and $a = 5, b = 2$ - are depicted on figure 1 (it is clear that the replacement of $a$ by $b$ and $b$ by $a$ corresponds to the replacement of arrows).

A very clear solution was sent by 10th grade student S. Pozdnyakov (e. Vilnius). Here's his reasoning.

Let us set the position of the minute hand $y$ as a function of the position of the hour hand $x$. The graph of this function $x \rightarrow y$ is shown in figure 2 in blue. This graph is the set of all positions of the hands $(x, y)$ that can be found on the dial of a watch. On the area of ​​interest there are pairs $(x, y)$ for which the pair $(y, x)$ also belongs to this set. But the point $(y, x)$ is a point symmetrical to $(x, y)$ with respect to the bisector of the angle $xOy$. On figure 2 the set of points symmetrical to the systems of points is marked in red *).

It remains to find the number of intersections of the blue and red segments (not counting the points lying on the bisector $x = y$). It is easy to see that there are 132 of them, i.e. 66 pairs of points, symmetrical with respect to the bisector.

And finally, one more thing, no mathematical apparatus is required.

Let's put next to our clock (on the right) another, imaginary one, which runs exactly 12 times faster. Let both clocks be at the same time when they show 12 o'clock; then the hour hand of the right clock always coincides with the minute hand of the left one. It is clear that the “indistinguishable” positions of the hands that interest us are exactly those when the hour hand of the left coincides with the minute hand of the right, fast (think why!). How many times will this happen? Of the 144 revolutions that the minute hand of the right watch will make during the time that the hour hand of the “normal” watch makes one revolution,

*) The author writes that the “red” set is “the graph of the function inverse to our function $x \rightarrow y$”. This is not entirely true: it is clear that our function does not have an inverse on the entire segment $0 \leqslant x \leqslant 12$, since here each $y$ corresponds to many (namely twelve) different $x$. One could say this: we will consider the function $x \rightarrow y$ on each segment $0 \leqslant x < 1, 1 \leqslant x < 2, \dots, 11 \leqslant x < 12$, take the inverse of each of these functions and construct a graph for each of them. Then we will really get a “red” set consisting of `devenaudami` graphs! (For the definition of the inverse function, see «Kvant» No. 1, pp. 32-33.)

⟦folio 52⟧

Each rotation there will be one match (including the starting point of the first rotation); Of these, we need to exclude 12 cases when all four arrows coincide, leaving 132.

**M7.** a, b, c are the sides of the triangle.

Prove that $\frac{a}{b+c-a} + \frac{b}{c+a-b} + \frac{c}{a+b-c} \geq 3$.

Solution. This problem has quite a few solutions. We will give one of the shortest ones. We only need the inequality well known from the school course
$$\frac{m}{n} + \frac{n}{m} \geq 2,$$
(1)

where $m > 0, n > 0$.

Let us introduce the following notation:
$$b + c - a = x,$$
$$c + a - b = y,$$
$$a + b - c = z.$$

Note that
$$x > 0, y > 0, z > 0;$$
(3)
this follows from the fact that $a, b, c$ are the sides of the triangle, and each side is less than the sum of the other two (unfortunately, from the letters sent to the editor, it is clear that most of those who solved the problem did not even think about where they use the fact that $a, b, c$ are the sides of the triangle).

From (2) it follows that
$$a = \frac{y+z}{2}, \quad b = \frac{x+z}{2}, \quad c = \frac{x+y}{2};$$

Posibly, the original inequality can be rewritten as follows:
$$\frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} \geq 3.$$

Transforming the left-hand side of (4) and using (1) and (3), we obtain
$$\frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} =
= \frac{1}{2} \left[ \left( \frac{y}{x} + \frac{x}{y} \right) + \left( \frac{z}{x} + \frac{x}{z} \right) +
\left( \frac{z}{y} + \frac{y}{z} \right) \right] \geq \frac{1}{2} (2 + 2 + 2) = 3,
$$
which is what was required.

Note that a more general inequality can be proven similarly:
$$\frac{x_1}{x_2 + x_3 + \dots + x_n - x_1} +
\frac{x_2}{x_3 + x_4 + \dots + x_n + x_1 - x_2} + \dots +
\frac{x_{n-1}}{x_n + x_1 + x_2 + \dots + x_{n-2} - x_{n-1}} +
\frac{x_n}{x_1 + x_2 + \dots + x_{n-1} - x_n} \geq \frac{n}{n-2},$$

where all the denominators are positive.

In conclusion, we note that one geometric fact directly follows from the proven inequality. Let $R$ be the radius of the circumscribed circle of the triangle, and $r$ the radius of the circle inscribed in it. It's good to know that
$$R = \frac{abc}{4S}, \quad r = \frac{S}{p},$$
(5)

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

where $S$ is the area of ​​the triangle, and $p$ is its half-perimeter. From (2) it follows that
$$p - a = \frac{x}{2},$$
$$p - b = \frac{y}{2},$$
$$p - c = \frac{z}{2}.$$

Now, using (5) and (6), we get
$$\frac{R}{2r} = \frac{abcp}{8S^2} = \frac{abcp}{8p(p-a)(p-b)(p-c)} =
= \frac{abc}{(a+b-c)(b+c-a)(c+a-b)} =
= \frac{(x+y)(y+z)(z+x)}{8xyz} =
= \frac{1}{4} \left[ 1 + \left( \frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} \right) \right].$$

Note that the left side of inequality (4) is in parentheses on the right side of the last equality. Using it, we get
$$\frac{R}{2r} \geq 1,$$
that is, $R \geq 2r$.

So, the radius of the circle circumscribed about the triangle is not less than the diameter of the circle inscribed in it. Try to prove this geometric number (which is much more difficult).

⟦folio 53⟧

Fig. 3

F7. A horizontal rod $O_1A$ of length $l$ rotates around a vertical axis $O_1$ (Fig. 3). A wheel of radius $r$ is mounted on the axis attached to the end of the rod $A$. The wheel axis is horizontal and makes an angle $\alpha$ with the rod $O_1A$. The wheel rotates on its axle without friction and rolls along the ground. There is more trenne between the wheel and the soil. How many revolutions will the wheel make when the rod $O_1A$ makes one revolution around the vertical axis?

Solution. The solution problem is easiest if you reason as an observable sitting at the end $A$ of the rod $O_1A$ would reason. If the angular velocity of rotation of the rod $O_1A$ relative to the ground is equal to $\Omega$, then the observer will say that in his coordinate system the rod is stationary, and the earth rotates around the axis $O_1$ with an angular velocity equal to $\Omega$, in the direction opposite to the direction of rotation of the rod relative to the earth. The speed of the point of the earth at which the wheel touches it is equal in magnitude to $v = \Omega l$ and is directed perpendicular to the rod $O_1A$. Let us decompose this speed into two components: $v_1 = v \cos \alpha$ and $v_2 = v \sin \alpha$, corresponding to the parallel and perpendicular planes of the wheel. It is clear that since the friction of the wheel on the soil is high, the point of the wheel at which it touches the ground moves relative to the point $A$, and therefore the axis of the wheel, at a speed $v_1$. This means that the wheel rotates around its axis with an angular velocity of $\omega = \frac{v_1}{r} = \Omega \frac{l}{r} \cos \alpha$.

Fig. 4.

The ratio of the rotation angles of the rod and the wheel around their axes is equal to the relative angular velocities of rotation of the rod and the wheel. Therefore, when the rod $O_1A$ makes one revolution around the axis $O_1$, the wheel will make $n = \frac{\omega}{\Omega} = \frac{l}{r} \cos \alpha$ revolutions around its axis.

F8. A long rod $AB$ with a threaded hole at the end is screwed onto a vertical screw (Fig. 4). The rod is released. The trenne between the screw and the rod is negligible. How will the rod move after it comes off the screw?

Solution. At the moment when the rod flies off the screw, the speed of its center of mass (center of gravity) will have both vertical and horizontal components. Since the only force acting on the rod from this moment will be the merging of gravity, the center of mass of the rod will move along a parabola - the trajectory of a body thrown at an angle to the horizon with an initial speed equal to the speed of movement of the center of mass of the rod at the moment when it flew off the propeller. But at the moment when the rod flew off the screw, different points of the rod had different horizontal velocities. Therefore, the rod will also rotate in a horizontal plane around the center of mass.

⟦folio 54⟧

---
running_head:
folio:
---

F9. On the horizontal table there is a weight attached to the table using a long spring. At first the spring was not stretched. Then the weight was moved 20 cm from the equilibrium position and released. The weight began to oscillate along the spring. Due to friction, the amplitude of its oscillations over the period decreased by 7%. How many oscillations will the weight make before stopping? At what distance from the equilibrium position will it stop?

Solution. If a constant external force acts on the oscillating mat, then it will change the equilibrium position of the mat. For example, if we compare the oscillations of a load attached to a spring and moving without friction in a horizontal plane with the oscillations of the same system in a vertical plane, when the load along the line of its motion is acted upon by gravity, then we will see that in the second case the equilibrium position of the load will be further from the fixed end of the spring by a distance of $x = \frac{mg}{k}$, where $k$ is the spring stiffness coefficient, and $m$ is the mass cargo In this case, the period of oscillation of the load will be the same in both cases.

The action of a constant external force on the matnik does not change the period of oscillation of the matnik and does not cause damping of its oscillations, since the position of the action of the external force reduces the energy of the matnik, and the second positive period increases the energy of the matnik by the same amount. It’s another matter when, as in our case, the force acting on the mat is constant only during each period, and through the polariod in the opposite direction. In this case, the oscillations of the mat are damped, since when the load moves, the force acting on it is always directed in the direction opposite to the direction of its movement. Moreover, every polariod of oscillation of the load occurs around different equilibrium positions. When the load moves, the equilibrium position is expressed - this is the point $A$ (Fig. 5), since the friction force acting on the load is directed

Fig. 5.

to the left (compare with the oscillations of a load suspended on a spring), and when moving to the left - point $B$.

It is clear that points $A$ and $B$ are at the same distance from point $O$—the position of the load with an undeformed spring. This distance is found from the condition that the spring tension force $F = k \Delta x$ ($\Delta x$ is the spring deformation) and the friction force acting on the load are equal: $k \Delta x = F_{\text{тр}}$. From here

$$a = AO = OB = \Delta x = \frac{F_{\text{тр}}}{k}.$$

The oscillations of the load cannot be limited to the area between points $A$ and $B$, since in this area the spring tension force does not exceed the maximum possible friction force. Therefore, if the speed of the load at every point in this area turns out to be zero, then the load will remain: the tension force of the spring will be balanced by the friction force.

Let us denote the amplitude of the $n$-th oscillation of the load (the deviation of the load from the point $O$) by the letter $y_n$, if the load is deflected to the right from the point $O$, and $x_n$, if the load is deflected to the left from the point $O$. $y_0 = 20$ cm is the initial deflection of the load. According to conditions

$$\frac{y_0 - y_1}{y_0} = 0.07.$$

⟦folio 55⟧

Let us find the law of change in the amplitude of oscillations of the load. The change in the energy of the system when the load moves is equal to the work done by the friction force, therefore, using the formula for the energy of the deformation spring $W = \frac{k(\Delta x)^2}{2}$, we can write that

$$\frac{k y_n^2}{2} - \frac{k x_n^2}{2} = F_{\text{тр}}(y_n + x_n)$$

And

$$\frac{k x_n^2}{2} - \frac{k y_n^2}{2} = F_{\text{тр}}(x_n + y_n+1).$$

Dividing both sides of the first equation by $y_n + x_n$, we find that $y_n - x_n = 2 \frac{F_{\text{тр}}}{k}$. Similarly, from the second equation we obtain that $x_n - y_n+1 = 2 \frac{F_{\text{тр}}}{k}$. Adding the resulting equations, we find that

$$y_n - y_n+1 = 4 \frac{F_{\text{тр}}}{k}$$

(9)

But $\frac{F_{\text{тр}}}{k} = a$, therefore $y_0 - y_1 = y_1 - y_2 = \dots = y_n - y_{n+1} = 4 a$. (10)

The amplitude of the load oscillations during the period decreases by the same amount, equal to 4a. Substituting into formula (7) instead of the difference $y_0 - y_1$ the equal difference $y_n - y_{n+1}$, we obtain that $\frac{y_n - y_{n+1}}{y_0} = 0,07$, or that over the period the amplitude of the load’s oscillations decreases by $0,07 y_0 = 1,4$ cm. After $n$ vibrations it becomes equal to $y_n = y_0 - n \cdot 0,07 y_0$. In this case, the amplitude of oscillations of the load, as we have already said, cannot be less than $a$. Since, according to formulas (7) and (10), $4a = y_0 - y_1 = 0,07 y_0 = 1,4$ cm, then $a = 0,35$ cm.

From the condition $y_n \geq a$ or $20(1 - 0,07n) \geq 0,35$ we obtain that $n \leq 14,04$. $n$ is an integer. Therefore, the load will make 14 complete oscillations.

Since, $y_{14} = 20(1 - 0,07 \cdot 14) = 0,4$ cm, that is, $y_{14} > a$, and the load is outside the area between points $A$ and $B$. Therefore, the tension force acting on the load is greater than the friction force, and the load will perform another part of the oscillation, stopping at a distance $y$ from the point $O$. Moreover, the load cannot reach point $O$. When moving to the left, its equilibrium position is point $B$, and the load cannot deviate to point $B$ by a distance greater than $y_{14} - a \approx 0,5$ cm.

Let the distance traveled by the load before stopping be equal to $y_{14} - y$. The energy of the system at the point where the load stops is $\frac{k y_n^2}{2}$. Equating the energy difference between the system of work done by the friction force, we obtain equation $\frac{k y_{14}^2}{2} - \frac{k y_n^2}{2} = F_{\text{тр}}(y_{14} - y)$. Dividing this equation by the non-zero difference $y_{14} - y$, we obtain that $ky_{14} + ky = 2F_{\text{тр}}$. Hence $y = 2 \frac{F_{\text{тр}}}{k} - y_{14} = 2a - y_{14} = 0,3$ cm.

F10. How to construct a heater of the highest possible power from four thin wire spirals with resistances $10 \text{ om}$, $20 \text{ om}$, $30 \text{ om}$ and $40 \text{ om}$, designed to release a power of no more than $2 \text{ om}$ on each, if there is a current source with e. d.s. $20 \text{ b}$ and internal resistance $20 \text{ om}$?

Solved.e. Let us first prove that the greater the power released in the external circuit, the closer the load resistance is to the internal resistance of the source.

Current in a circuit consisting of a source connected in series with e. d.s. $\varepsilon$ and internal resistance $r$ and load with resistance $R$, is equal to $\frac{\varepsilon}{R + r}$. Therefore, the power allocated to the load is $W = \frac{\varepsilon^2}{(R + r)^2} R$.

Let's draw a graph of the dependence of $W$ on the load resistance $R$. At $R = 0$, $W = 0$; with $R \rightarrow \infty$ you can beat $r$ compared to $R$ in a significant matter. Then $W \approx \frac{\varepsilon^2 R}{R^2} = \frac{\varepsilon^2}{R}$.

That is, for large $R$ ($R \gg r$), the graph of the dependence of $W$ on $R$ is a hyperbola, and the symptoms are approaching the $R$ axis. Since the function $W(R)$ is continuous, equal to zero at $R = 0$ and decreasing at $R \rightarrow \infty$, it must have a maximum. Let's find him.

⟦folio 56⟧

The expression $\frac{\varepsilon^2 R}{(R + r)^2}$ is maximum when the inverse expression $\frac{(R + r)^2}{\varepsilon^2 R}$ is minimum. But $\frac{(R + r)^2}{\varepsilon^2 R} = \frac{1}{\varepsilon^2} \times \frac{R^2 + 2Rr + r^2}{R} = \frac{2}{\varepsilon^2} r + \frac{1}{\varepsilon^2} \left( R + \frac{r^2}{R} \right)$.

This expression is minimal when the expression $R + \frac{r^2}{R}$ is minimal.

Since $R + \frac{r^2}{R} \geq 2\sqrt{R \cdot \frac{r^2}{R}}$ (the correspondence between the argumentative mean and the geometric mean of two numbers $R$ and $\frac{r^2}{R}$), then $R + \frac{r^2}{R} \geq 2r$. Therefore, the minimum of the sum $R + \frac{r^2}{R}$ is 2r and is reached at $r = R$.

So, the power released at the load is maximum at $R = r$. The graph of $W(R)$ is shown in figure 6. From the graph it can be seen that $W(R)$ is greater as $R$ increases to $r$. This means that the coils need to be constructed into a heater with a resistance as close to 20 ohms as possible. It is impossible to use only a spiral with a resistance of 20 ohms, since it will release a power of $W = \left( \frac{\varepsilon}{R + r} \right)^2 R = 5 \text{ ом}$, and each of the spirals is designed to release a power of no more than 2 ohms.

Of all the possible schemes for connecting spirals, the best one is figure 7. The resistance of such a heater is 20 ohms, releasing $W = \left( \frac{20}{20 + 20} \right)^2 20 = 5 \text{ ом}$ power in the heater. It is easy to calculate that the most power is released on a spiral with a resistance of 20 ohms and is equal to 1.8 ohms.

A very good solution to this problem was sent by L. Voronov from Yaroslavl. In the application to the solution of the problem, he examined the question of how efficiency depends. electrical installations from load resistance.

Since the power supplied by the source is equal to $\varepsilon I = \frac{\varepsilon^2}{R + r}$, and the useful power, as we obtained, is equal to $\frac{\varepsilon^2 R}{(R + r)^2}$, then, denoting the ratio $\frac{R}{r}$ by $\alpha$, we obtain for the efficiency $\eta$ the following expression:

$$\eta = \frac{R}{R + r} = \frac{\alpha}{1 + \alpha}.$$

Efficiency are large at high load resistances when a small current flows in the circuit. At $\alpha = 0, \eta = 0$; at $\alpha \rightarrow \infty, \eta \rightarrow 1$. At $\alpha = 1$, when maximum power is released into heating, $\eta = 0,5$ (50%). In this case, of course, the same power is released in the source itself as in the heating. The source becomes a stove.

⟦folio 57⟧

Fig. 8.

By increasing the efficiency of the installation, we simultaneously reduce the useful power released in the load.

F11. When opened, the barrels are filled with water and set at different heights (Fig. 8). Tubes are drawn upward from each barrel and connected together. The tubes are also filled with water. Where will the water flow through the pipes if taps $K_1$, $K_2$ and $K_3$ are opened at the same time?

Solved and e. The system of tubes will work like a siphon. Water will flow from the top barrel to the middle and bottom. In addition, water will flow from the middle barrel to the bottom one. Since the speed of water flow through the siphon is proportional to the difference in water levels in the vessels, then in the case when the water level in the middle barrel is closer to the water level in the lower barrel than to the water level in the upper barrel, more water flows into the middle barrel from the upper barrel than from the middle barrel to the lower one. In this case, both the lower and middle barrels are leveled. If the water level in the middle barrel is closer to the water level in the top than to the bottom, then only the bottom barrel will be filled due to the flow of water from the top and middle barrels.

The subscription to the popular physico-mathematical journal «Kvant» continues. Designed primarily for students in grades 7-10, it will be of interest to teachers, especially those who teach extracurricular or elective classes in physics or mathematics, as well as to all lovers of mathematics and physics.

The main content of the magazine is a “physico-mathematical school,” i.e., materials that help to better understand physics and mathematics, learn to apply these sciences to teach various phenomena and processes that we encounter in practice, and learn to solve problems.

The reader will find many problems in the magazine. Among them are problems proposed for exams in various fields, problems proposed for optimization, and simply interesting problems.

Notes describing the physical apparatus and experiments will help the reader set up and test a physical experiment.

The magazine will publish on its pages a review article telling about the achievements of science and problems that are still waiting to be solved, stories about scientists and stories from scientists themselves about how “science is done”, how scientific discoveries appear.

The magazine will constantly report scientific news, place reviews on books already published and those still being prepared for publication.

Important sections in the magazine are Problem «Kvant», Laboratory «Kvant», “Practicum for applicants”, “Mathematical journal”.

The main authors of the journal are famous Soviet and foreign scientists, young scientists and teachers. The magazine will also provide its pages to schoolchildren to describe the device and experiments, explain interesting issues and tasks.

Many materials are told on the server side of the reader with a pencil in his hands.

The signature begins on September 1. The price of the room is 30 kopecks. The cost of an annual subscription is 3 rubles 60 kopecks. When subscribing, refer to our index 70465.
