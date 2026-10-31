---
id: 1974-11-myakishev-vyinuzhdennyie-mehanicheskie-kolebaniya-f7017a9b
issue: kvant_1974_11
year: 1974
number: "11"
title: Forced mechanical vibrations
authors:
  - Мякишев Г. Я.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
tag: M8OL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 640b79612c89eec106448bc0ac2e8b4bc4ae146e98a3db086ce811e966512698
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/03_myakishev-vyinuzhdennyie-mehanicheskie-kolebaniya-f7017a9b.md
source_content_sha256: d3b4699b1a8f198b565211cb5611e8e732b03a85c3e930bb4239ff4ec18fa40f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

The basic equation of motion in mechanics is Newton's second law:

$$m a = F.$$

To find the position of a body and its speed at any moment of time, it is enough to know the force as a function of the body’s coordinates and projections of its velocity, as well as the initial conditions: the coordinates and projections of the body’s velocity at the initial moment of time.

The simplest case is movement under the influence of a constant force $F = const$ (in particular, the force can be zero). Then the acceleration is constant ($a = const$); the coordinates and speed of the body are easily determined using well-known kinematic equations.

In oscillatory motion, which is very common in nature and widely used in technology, acceleration is not constant. This makes solving mechanical problems very difficult. Only free harmonic vibrations of a body under the action of a force proportional to the displacement of the body from the equilibrium position can be studied completely without resorting to higher mathematics. But already taking into account the force in three, proportional to the speed, it is necessary to change the differential equations. Even more difficult (mathematically) is the problem of forced oscillations, when there is an additional external periodic force on the action system. In this case, a curious and practically important phenomenon is observed in the system - resonance. When the frequency of the external force coincides with the natural frequency of the system, the amplitude of the vibrations increases sharply.

It is possible, however, without resorting to solving a complex equation of motion, to analyze the process of forced oscillations using visual physical messages. In particular, we can understand why resonance is observed. This is what this article is about.

But first, let us recall some basic provisions concerning free harmonic oscillations.

Free harmonic oscillations

The simplest oscillatory system is a system in which a force acts proportional to the displacement of the body from the equilibrium position, directed opposite to the displacement. Of course, there is always friction. But if it is small, then over a not too long period of time, by the action of three forces you can cease to exist. Such systems include: an external load, a mathematical mat (at small angles of deflection), a body floating on the surface of the water with a constant cross-section, etc. For the definition, we will only talk about the outward load. There are two forces acting on the load: the gravitational force and the elastic force of the spring. The constant gravitational force $F_T = mg$ does not affect the oscillation process in any way. It will only confuse the equilibrium position of the load. It's easy to exclude

⟦folio 3⟧

from the equation of motion if the origin of the reference system is combined with the end of a spring deformed by a load when the load is at rest (Fig. 1). Let's direct the coordinate axis $OX$ vertically downwards. Then oscillations will occur only under the action of the elastic force $F_y = -kx$, where $k$ is the elasticity coefficient, and $x$ is the displacement of the load from the equilibrium position. The equation of motion will be written as follows:

$$ma_x = -kx. \tag{1}$$

Dividing this equation by $m$ and introducing the notation $\omega_0 = \sqrt{\frac{k}{m}}$, we obtain the generally accepted form of the equation describing a harmonic oscillation with a cyclic frequency $\omega_0$:

$$a_x = -\omega_0^2 x. \tag{2}$$

The solution to this equation, that is, finding the function $x = x(t)$, can be obtained in an elementary, but rather lengthy way. The result is:

$$x = x_0 \cos(\omega_0 t + \varphi_0). \tag{3}$$

Here $x_0$ is the oscillation amplitude, and $\varphi_0$ is the initial phase. These quantities are found from the initial conditions.

Obviously we excite vibrations of a weight on a spring by pulling it down and releasing it. Moreover, at the initial moment (at $t = 0$) $x = x_0$, and $v_x = 0$. This matches that of $\varphi_0 = 0$. Then

$$x = x_0 \cos \omega_0 t. \tag{4}$$

Harmonic oscillations can be described using equality.

Fig. 1.

new trionometric functions cosine and sine. Instead of (3), end, we can write:

$$x = x_0 \sin(\omega_0 t + \varphi_0). \tag{5}$$

But then under the usual initial conditions $\varphi_0 = \frac{\pi}{2}$, and not zero. Therefore, writing through cosine is somewhat preferable, although, of course, you can also use sine.

The speed during harmonic oscillations also changes according to the harmonic law. Its amplitude is equal to $v_0 = \omega_0 x_0$, and the phase shift relative to the coordinate is equal to $\frac{\pi}{2}$:

$$v_x = \omega_0 x_0 \cos\left(\omega_0 t + \frac{\pi}{2}\right) = -\omega_0 x_0 \sin \omega_0 t. \tag{6}$$

The acceleration oscillates out of phase with the coordinate (out of phase by $\pi$) and has an amplitude of $a_0 = \omega_0^2 x_0$, that is

$$a_x = \omega_0^2 x_0 \cos(\omega_0 t + \pi) = -\omega_0^2 x_0 \cos \omega_0 t. \tag{7}$$

That's all you need to know for further relative free harmonic oscillations.

Equation of motion for forced oscillations

Let an external periodic force $F_x = F_0 \cos \omega t$ act on the oscillatory system (a load on a spring in our example). In addition, the body is subject to elastic forces $F_y = -kx$ and a friction force proportional to speed $F_{\tau p} = -\mu v_x^*$), where $\mu$ is the friction coefficient. Then the equation of motion will be written like this:

$$ma_x = -kx - \mu v_x + F_0 \cos \omega t. \tag{8}$$

Crossing the left side of the equation with all forces except the external one, we get:

$$ma_x + \mu v_x + kx = F_0 \cos \omega t.$$

*) At low speeds of body movement, we can indeed assume that the friction force (or, in other words, the resistance force) is directly proportional to the speed.

⟦folio 4⟧

Fig. 2.

It is more convenient to write this equation in a slightly different form, dividing its right and left sides by $m$ and introducing the notation $\omega_0 = \sqrt{\frac{k}{m}}$:

$$a_x + \frac{\mu}{m} v_x + \omega_0 x = \frac{F_0}{m} \cos \omega t.$$ (9)

The movement of a body that obeys this equation is quite complex, especially at the beginning, when it is not harmonic.

Establishing oscillations

The mechanism for establishing forced harmonic oscillations can be done as follows. Under the influence of an external force, the system receives a “push”, as a result of which free oscillations of frequency $\omega_0$ arise in it. Over time, free vibrations will die out the faster, the greater the friction coefficient $\mu$. But at the same time, there is an external periodic force in the action system, which causes oscillations in it with a frequency of $\omega$. Thus, over a certain period of time, both free and forced oscillations occur simultaneously in the system, that is, the principle of superposition applies to oscillatory movements.

The amplitude of forced oscillations increases over time (Fig. 2) until a certain Stationary value is established. This will happen when the work of the external force becomes equal to the work of the friction forces, that is, when the energy entering the system from the outside becomes equal to the loss of mechanical energy within the system.

Thus, only after the time of establishment of oscillations in the system will free oscillations die out and only forced harmonic oscillations with frequency $\omega$ and amplitude $x_0$ remain:

$$x = x_0 \cos (\omega t + \varphi_0).$$ (10)

Externally, the equations for free and forced vibrations coincide. But if during free oscillations $x_0$ and $\varphi_0$ were determined only by the initial conditions, then during forced oscillations they are determined (as we will see later) by the parameters of both the system itself and the external force. First of all, the correspondence between the frequencies of natural and forced oscillations plays a significant role. Note, by the way, that the values ​​of $\varphi_0$ in the case of forced oscillations are called the phase shift between the oscillations of the mixture and the external force.

The speed and acceleration of a body performing forced oscillations are determined by equalities similar to (6) and (7) for free oscillations:

$$v_x = \omega x_0 \cos \left(\omega t + \varphi_0 + \frac{\pi}{2}\right),$$ (11)

$$a_x = -\omega^2 x_0 \cos (\omega t + \varphi_0).$$ (12)

Since speed always characterizes a rapid change in coordinate with time, and acceleration characterizes a rapid change in speed with time, then, knowing the dependence of the coordinate on time $x(t)$, we can uniquely determine the function $v_x(t)$ and $a_x(t)$.

Now let's move on to solving the main problem. Let us find out what and how the amplitude $x_0$ of forced oscillations and the phase shift $\varphi_0$ depend on. To do this, consider three limiting cases.

⟦folio 5⟧

The first case: $\omega \ll \omega_0 = \sqrt{\frac{k}{m}}$, that is, part of the external periodic force is much less than the natural frequency of the system $^*$).

Second case: $\omega \gg \omega_0$; the opposite condition is satisfied.

And finally, the most important case: $\omega \approx \omega_0$. This is a case of resonance.

Forced oscillations of low frequency

Let us rewrite equation (9) again—the equation of motion for forced oscillations:

$$a_x + \frac{\mu}{m} v_x + \omega_0^2 x = \frac{F_0}{m} \cos \omega t.$$

If $\omega \ll \omega_0$, then of the three terms on the left side of this equation the largest will be the last term $\omega_0^2 x$. Indeed, the amplitude of the first term is proportional to $\omega^2 x_0$, the second - to $\omega x_0$, and the last - to $\omega_0^2 x_0$. Therefore the approximation (given that $\omega \rightarrow 0$)

$$\omega_0^2 x = \frac{F_0}{m} \cos \omega t,$$

where

$$x = \frac{F_0}{m \omega_0^2} \cos \omega t = \frac{F_0}{k} \cos \omega t.$$ (13)

The coordinate oscillations are proportional, and the phase of the oscillations coincides with the phase of the external force.

*) One small part is required for accuracy. In the presence of friction, the natural frequency $\omega_c$ of free oscillations is not equal to $\omega_0 = \sqrt{\frac{k}{m}}$. In fact, it is somewhat smaller: $\omega_c = \sqrt{\omega_0^2 - \frac{\mu^2}{4m^2}}$. But with a low friction coefficient ($\mu \rightarrow 0$) $\omega_c \approx \omega_0$. The practical most interesting cases are precisely those of small friction. Therefore, we can rightfully consider the natural frequency of oscillations of the system to be equal to $\omega_0 = \sqrt{\frac{k}{m}}$.

Note that the greater the spring stiffness, the smaller the amplitude of oscillations. Qualitatively, this case can be described as follows. At a low frequency of external force, almost the same thing happens as when a constant force acts on a spring. According to Hooke's law, the displacement increases in proportion to the external force, and at any moment the external force is almost exactly balanced by the elastic force of the spring.

From an energy point of view, the conditions for pumping energy into the oscillatory system from external bodies acting on the system with a periodic force are very unfavorable. In fact: in four periods, when the body is displaced from the equilibrium position, the external force does positive work, since the force and speed of the body, and therefore the displacement, are directed in one direction (Fig. 3). But in the next four periods, when the body returns to the equilibrium position, force and speed (and therefore displacement) are directed in opposite directions (Fig. 4). The work done by the external force will be negative. The same picture will be observed in the second half of the period. In general, during the period of work, the external force is almost exactly zero. Only a small part of the work of the external force goes to compensate for the work of the friction force, since the speed of the body at $\omega \ll \omega_0$ is very small, and therefore the magnitude of the friction force is small.

⟦folio 6⟧

There is some subtlety here that sometimes makes it difficult to understand the essence of the matter. If the change from the equilibrium position is directly proportional to the force at any moment in time, then, at first glance, it would seem that the work should be positive all the time. However, it must be borne in mind that the sign of the work depends on the coincidence of the direction of the force and the direction of displacement, that is, the speed, and not the sign of the coordinate. In order for the work to be positive, it is not necessary that the signs $F_x$ and $x$ match, but that $F_x$ and $\Delta x$ (or $\frac{\Delta x}{\Delta t} = v_x$) have the same signs.

Forced vibrations of a large part

In the case of $\omega \gg \omega_0$ on the left side of equation (9), at any moment of time the largest will be the first term, the amplitude of which is proportional to the square of the frequency. It will play the main role, so you can write:

$$a_x = \frac{F_0}{m} \cos \omega t.$$

Now it is not the coordinate that is in phase with the force, but the acceleration, and the oscillations of the coordinate will occur in antiphase with the oscillations of the external force. The coordinate amplitude is equal to

$$x_0 = \frac{a_0}{\omega^2} = \frac{F_0}{m\omega^2}.$$

Thus, body vibrations are transmitted according to the law

$$x = -\frac{F_0}{m\omega^2} \cos \omega t.$$ (14)

When $\omega \to \infty$ (this is equivalent to the condition $\omega \gg \omega_0$) $x_0 \to 0$, that is, the oscillation amplitude is small. This result is quite natural. The force columns in the direction that the body, which has inertia, does not have time to noticeably shift relative to the equilibrium position.

As in the previous case, when $\omega \ll \omega_0$, half the period the external force does positive work, and the other half - negative work. For half the period, force and displacement are directed in the same direction, and for the other half of the period they are directed in opposite directions. Again, almost no energy enters the system.

Resonance

The most interesting part of the case of forced oscillations is the case when the frequency of an external periodic force coincides with the natural frequency of oscillations of the system ($\omega \approx \omega_0$).

In this case, the first equation is (9), which can be written as follows:

$$a_x = -\omega_0^2 x,$$

mutually cancels out with the third term equal to $\omega_0^2 x$. These two terms at any moment of time are identical in magnitude, but have opposite signs, since the acceleration and coordinate for any harmonic oscillation are out of phase by π.

As a result, equation (9) takes the form:

$$\mu v_x = F_0 \cos \omega_0 t.$$ (15)

This is a simple equation and contains the essence of resonance. At $\omega \approx \omega_0$ at any moment of time (let us emphasize once again that we are talking about steady forced oscillations), the external force seems to turn off the friction servant from the game. As a result, acceleration only comes from elasticity. In essence, a very small situation is realized: harmonic oscillations exist in the system for an arbitrarily long time, despite the effect of friction.

From (15) it is clear that during resonance, the phase of velocity oscillations coincides with the phase of the external force. The work done by the external force under these conditions is positive throughout the entire length of the

⟦folio 7⟧

rioda. Optimal conditions are created for transferring energy from external bodies to the oscillatory system.

The positive work done by the external force is exactly equal in magnitude to the negative work done by the friction force. Because of this, the mechanical energy of the system does not change. The energy coming from outside, due to the work of the friction force, turns into heat (the spring with the load and the surrounding air heat up).

The amplitude of oscillations at resonance is equal to

$$x_0 = \frac{v_0}{\omega_0} = \frac{F_0}{\mu\omega_0}.$$

The lower the friction coefficient, the greater it is. At $\mu \rightarrow 0$ $x_0 \rightarrow \infty$, that is, very/no, that at $\omega \approx \omega_0$ the amplitude is maximum. If $\mu$ has a sufficiently large value, then the resonant oscillation amplitude is not large.

The equation of oscillations at resonance has the form

$$x = \frac{F_0}{\mu\omega_0} \cos \left( \omega t - \frac{\pi}{2} \right),$$

since the mixing lags behind the speed by a quarter of the period. Now it is possible to depict an approximate form of the dependence of the amplitude $x_0$ and сdwа of phases $\varphi_0$ of forced oscillations on frequency. We know that at low frequencies ($\omega = 0$) the amplitude of oscillations is equal to $\frac{F_0}{k}$, and cdwг in phase is equal to zero.

At high frequencies ($\omega \rightarrow \infty$)
