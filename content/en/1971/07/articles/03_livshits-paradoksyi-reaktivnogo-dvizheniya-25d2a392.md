---
id: 1971-7-livshits-paradoksyi-reaktivnogo-dvizheniya-25d2a392
issue: kvant_1971_7
year: 1971
number: "7"
title: Paradoxes of jet propulsion
authors:
  - Лившиц М. С.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11-16
tag: 9LVI
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6b51be5d3313efd4d4a07ea901c1723ad3769b18063a1d01e795b7afeeb0c5be
prompt_sha256: draft-1
translated_from: content/ru/1971/07/articles/03_livshits-paradoksyi-reaktivnogo-dvizheniya-25d2a392.md
source_content_sha256: ae3584af88a799031d58dc318c2a3f2ced347f22242b5a0b339e4bbf1c6b1ec5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Paradoxes of jet propulsion
M.S. Livshits

Rocket propulsion power

During the operation of jet propulsion, the chemical energy of the fuel is converted into kinetic energy with a certain efficiency: part of this chemical energy is spent on various thermal losses (heating the walls of the engine chamber, heat carried away by escaping gases, etc.). The ratio of the resulting kinetic energy to the chemical energy of the burned fuel is called the internal (or effective) efficiency $\eta_{\alpha\phi}$. Obviously they come in the order of $0,3 \div 0,5$.

While it was deliberately not specified - the kinetic energy of what?

Let's consider the coordinate system associated with the rocket. In a very short time $\Delta t$, a mass of gas $\Delta m$ will be ejected from the rocket nozzle. If $\Delta t$ is small enough, then the speed of the rocket practically does not change and the coordinate system associated with it can be considered inertial. In this coordinate system, the rocket is motionless, which means that the chemical energy of the fuel is converted into the kinetic energy of gases.

Let $u$ be the relative velocity of gases flowing out of the rocket nozzle; then the kinetic energy of the gas mass $\Delta m$ escaping from the rocket nozzle is

$$E_{\Delta m} = \frac{\Delta mu^2}{2}.$$

⟦folio 12⟧

Since power is equal to the work done per unit time, we will obtain an expression for power if, instead of the value of the ejected mass of gases, we substitute the second mass consumption μ into our expression.

Therefore, engine power calculations

$$P_{\text{дв}} = \frac{\mu u^2}{2}.$$

The same expression could be obtained in another way, considering the movement of the rocket and gases in a moving coordinate system. In this case, the kinetic energy $E$ obtained during the operation of the rocket engine is spent on changing the kinetic energy of the emitted gases $\Delta E_{\text{газа}}$ and changing the kinetic energy of the rocket:

$$\Delta E = \Delta E_{\text{газа}} + \Delta E_{\text{ракеты}}.$$

Let us find separately each of the terms of this sum.

1. Let the speed of the rocket before the release of fuel $\Delta m$ be equal to $v$. Then

$$\Delta E_{\text{газа}} = \frac{\Delta m (u - v)^2}{2} - \frac{\Delta m v^2}{2},$$

where $\frac{\Delta m v^2}{2}$ is the kinetic energy possessed by the discarded mass of gases before its expiration (when it is in the rocket and moved with it at a speed of $v$), $\frac{\Delta m (u - v)^2}{2}$ is the kinetic energy possessed by the discarded mass of gases after its expiration from the rocket nozzle with a relative speed $u$ (since in a fixed coordinate system its speed will be $u - v$).

2. Now let's deal with the second term - $\Delta E_{\text{ракеты}}$. Since during time $\Delta t$ a mass of gas $\Delta m$ is ejected from the nozzle, carrying away the momentum $\Delta mu$, then this mass of gas, in accordance with Newton’s II law, is acted upon by a force

$$F = \frac{\Delta mu}{\Delta t} = \mu u.$$

According to Newton's III law, forces of the same magnitude, but directed in the opposite direction, act on the rocket - this is the traction force of the engine. If during the time $\Delta t$ the rocket traveled a distance $\Delta S$, then the thrust force of the engine made a perfect movement outside with the coordinate associated with the rocket.

So, the power of the rocket engine $P_{\text{дв}} = \frac{\mu u^2}{2}$ even during stationary operation of the engine remains constant. Let's remember this.

**Net mechanical power of the engine** (power developed by traction forces)

The main task of the engine is to increase the kinetic energy of the rocket. We have seen that the thrust force is equal to $F_{\tau} = \mu u$, and the change in the kinetic energy of the rocket during time $\Delta t$ is equal to $\Delta E_{\text{ракеты}} = \mu u \cdot \Delta S$. Therefore, the useful thrust power of the engine is equal to

$$W_{\pi} = \frac{\Delta E_{\text{ракеты}}}{\Delta t} = \mu u \frac{\Delta S}{\Delta t} = \mu u v.$$

During stationary operation of the engine, that is, with a constant second mass consumption and a constant gas flow rate, the useful power of the engine increases in proportion to the speed of the rocket.

At first glance, this conclusion seems paradoxical. In fact, since the formula that we obtained is valid at any rocket speed, it will be correct

⟦folio 13⟧

vedlin and at such a rocket speed at which the values ​​​​are obtained, the useful power will become greater than the power developed by the rocket engine due to fuel energy!

From a comparison of the expressions for engine power and useful power, it is clear that at $v = \frac{u}{2}$ the useful power becomes equal to the power of the rocket engine. Consequently, with a further increase in the rocket speed, it will be greater than the engine power. This is the quantitative limit where this paradox appears.

In order to understand this paradox, we will have to consider what the external (flight) efficiency is. However, at the same time, we will find out why it is advisable to characterize a rocket engine not by power, as is customary for other engines, but by the thrust force it develops.

The external efficiency cannot fully characterize the efficiency of a rocket engine, since in the general case, as we saw above, the fuel energy is distributed between the rocket and the emitted gases. Therefore, in theory, the so-called external (or flight) efficiency is also introduced, and in the literature one can find two different definitions and corresponding expressions for external efficiency. Each of these definitions of efficiency From different points, energy characterizes the mechanics of rocket flight. Let us consider these definitions, pointing at the same time to their logical basis.

First definition of external efficiency

A flight with a running engine is a flight of a body of variable mass. Therefore, in addition to the power of the rocket engine, the energy

compliance must also take into account the exchange of energy between the rocket and the gases leaving it, that is, all the power that we have. A change in the energy of the rocket can occur both due to the chemical energy of the fuel (the work of the traction force) and due to the energy that the ejected mass of gases possessed before it left the rocket. It can also be transferred to a rocket.

So, external (flight) efficiency can be defined as the ratio of the work done by the thrust force to the sum of the mechanical energy resulting from the combustion of fuel and the energy possessed by the mass of gases before it left the rocket. This relation can be replaced by the relation of the corresponding powers (the result will not change).

$$\eta' = \frac{\mu u v}{\mu^2 / 2 + \mu v^2 / 2} = 2 \frac{v}{u} / 1 + \frac{v^2}{u^2}.$$

Denoting the relation $\frac{v}{u} = R$, we obtain the final

$$\eta' = \frac{2R}{1 + R^2}.$$

Let us now examine the formula. The value of $\eta'$ is maximum when $\frac{1}{\eta'}$ is minimum, that is, when the expression $\frac{1 + R^2}{R} = \frac{1}{R} + R$ is minimum. But $\frac{1}{R} + R \geq 2 \sqrt{\frac{1}{R} \cdot R}$ (the argument mean of two numbers $a$ and $b$ is greater than the geometric mean or equal to it, if $a = b$). This means that $\frac{1}{R} + R$ is minimal for $\frac{1}{R} = R$ (or, what is the same, for $\frac{1}{R} + R = 2$). This means that the maximum $\eta'$ is achieved at $R = 1$ and at the same time $\eta' = 1$.

Physically, this is completely clear: at $v = u$ the expelled mass of gas has a kinetic energy equal to zero, that is, it completely gives up

⟦folio 14⟧

The kinetic energy she had was equal to the package.

The graph of $\eta'$ looks like that shown in Fig. 1.

Reduced flight efficiency at $v > u$ is explained by the fact that the energy carried away by the gas stream appears again and begins to increase.

The second definition of external efficiency is

In the second determination of external efficiency. it is approached in the following way.

The only source of increment in the kinetic energy of the “rocket + discarded gases” system is the operation of the package engine, that is, the energy obtained due to the transition of the chemical energy of the fuel into the mechanical energy of the fuel and packages. And by useful work, you need to remember the work that goes into increasing the kinetic energy of the package itself.

At the same time, the external efficiency is defined as the ratio of useful work to the total mechanical energy obtained in a package engine due to the chemical energy of the fuel.

Let us determine the magnitude of useful work in the understanding accepted here.

The traction force produces over the packet work, which increases the kinetic energy of the packets. But, on the other hand, the mass of gas shown to the package reduces the kinetic energy of the package by the amount that this mass of gas possessed (having, so to speak, its contribution to the total energy of the package) before its expiration. Thus, the net power is $\mu uv - \frac{\mu v^2}{2}$.

Therefore, by the second definition

$$\eta'' = \frac{\mu uv - \frac{\mu v^2}{2}}{\mu u^2} = 2R - R^2$$

Let's draw a graph of the dependence of $\eta'' = 2R - R^2 = R (2 - R)$ on $R$. It is a parabola intersecting the $R$ axis at $R = 0$ and $R = 2$, with a maximum at $R = 1$ (Fig. 2). That is, the maximum $\eta''$ is achieved at the same time as the maximum $\eta'$ - at $R = 1$ (in this case, all the mechanical energy of the package engine is consumed to increase the kinetic energy of the packet moving forward, or the ejected mass of gas has zero speed and does not carry away any energy). The graph shows that at $R > 2 (v > 2u) \eta'' < 0$.

Here, when considering the second definition of efficiency. packet engine, and reveals another important feature of the physics of the packet engine, considered from the point of view of changes in kinetic energy

⟦folio 15⟧

moving packets after reaching the value of the flight speed packets $v=2u$, becomes negative! Another paradox...

What is the solution to these paradoxes?

1. The first “paradox”, that is, the fact that the power developed by the traction force continuously increases with increasing packet speed and at $v > \frac{u}{2}$ becomes greater than the power of packet motion, is explained, as can be seen from the first definition of external efficiency, by the presence of an exchange part, the power of which we will consider. It also increases with increasing packet speed. Thus, with an increase in the speed of the packets, the gases leaving the packet become, so to speak, more and more “rich” and will remove to the packet more and more values ​​(absolute, not relative) of the energy $\frac{\mu v^2}{2}$ that they had before leaving the packet. The packages of gases escaping from the nozzle will give back to the package that part of the energy that was stored earlier. This leads to the fact that the power developed by the traction force continuously grows and at $v > \frac{u}{2}$ becomes greater than the value obtained due to the chemical energy of the fuel.

2. The second “paradox” is also explained quite simply. When the speed of the packet becomes greater than the double speed of gas outflow ($v > 2u$), the energy carried away by the gas increases so much that the flowing stream of gas carries away not only all the energy created at a given moment by the packet motion, but also part of the energy that the “rocket-gas” system possessed up to this moment (accumulated over the previous “history” of the flight). Or, if we approach the appearance of the physical meaning of this “paradox” a little differently: the decrease in the kinetic energy of the package due to a decrease in its mass (due to “losing weight”) is greater than the decrease in kinetic energy due to the decrease in the speed of the package. So, it is advisable to characterize a packet propulsion engine by its traction force. This is sharply different from the usual situation, say, for auto-

⟦folio 16⟧

a mobile or aircraft engine used to provide movement in a resistive environment.

In the latter case, it is the power of the engine that is its most important characteristic, since the more powerful the engine, the higher the speed of movement of a given body it can maintain, predetermining compliance with the increasing resistance of the medium, that is, compensating for energy losses to overcome the resistance of the medium.

During the flight of a rocket with a running engine, the relative kinetic energy (kinetic energy per unit mass) of the remaining part of the rocket continuously increases along with the speed (the effectiveness of this process is characterized by flight efficiency in the first definition), although the kinetic energy of the rocket with the new (remaining) fuel supply at speed $v > 2u$ is less than the kinetic energy of the rocket with fuel before the ejected mass of gas leaves the rocket.
