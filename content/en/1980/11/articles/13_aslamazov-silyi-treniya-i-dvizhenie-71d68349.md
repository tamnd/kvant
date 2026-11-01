---
id: 1980-11-aslamazov-silyi-treniya-i-dvizhenie-71d68349
issue: kvant_1980_11
year: 1980
number: "11"
title: Friction forces and movement
authors:
  - Асламазов Л. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 43
page_labels: 38-41
tag: YKB5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 43df07b0a19869c51f391d82333a440fb1658ff1443bc5b49e181b71ef935fbd
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/13_aslamazov-silyi-treniya-i-dvizhenie-71d68349.md
source_content_sha256: 096b5d39712d1f377c620956f12f14f0bae9ae03341a9525c51261762e652fcf
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Friction forces and movement

Body movement is usually caused by friction forces. If the surfaces of solid bodies collide, their relative motion is hampered by the forces of dry friction. A characteristic feature of dry training is the existence of a stagnation zone. The body cannot be moved from its place until the absolute value of the external force exceeds a certain value. Until this moment, a static friction force acts between the surfaces of the colliding bodies, which balances the external force and grows with it (Fig. 1). The maximum value of the static friction force is determined by the formula

$$|\vec{F}_{\text{trp max}}| = \mu |\vec{N}|,$$

where $\mu$ is the friction coefficient, depending on the properties of the contacting surfaces; $\vec{N}$ — normal pressure force.

When the absolute value of an external force changes the value

$$|\vec{F}_{\text{trp max}}| = \mu |\vec{N}|,$$

There is a relative movement - piercing. The sliding friction force usually weakly depends on the speed of relative motion, and at low speeds it can be considered equal to $|\vec{F}_{\text{trp max}}|$.

The movement of a body in liquid and gas is caused by friction forces. The main difference between dry and dry training is the absence of a stagnation zone. In a liquid or gas, static friction forces do not arise, and therefore even a small external force can cause the body to move. The friction force at low speeds is proportional to the speed, and at high speeds it is proportional to the square of the speed of movement.

Problem 1. During an emergency stop of a train, moving at a speed of $|\vec{v}| = 70$ km/h, the braking distance is $s = 100$ m. What is the friction coefficient between the train wheels and the ribs? What is the braking distance if the brakes fail in one of the $n = 10$ options? Make the mass of the locomotive equal to the mass of the car; It's difficult to resist air resistance.

When braking, acceleration $\vec{a}$ of the train imparts friction forces $\vec{F}_{\text{trp}}$:

$$M \vec{a} = \vec{F}_{\text{trp}},$$

where $M$ is the mass of the entire composition. The friction force $\vec{F}_{\text{trp}}$ represents the equilibrium of all friction forces acting on the composition (Fig. 2), and is equal according to the model $|\vec{F}_{\text{trp}}| = \mu |\vec{N}| = \mu Mg$. Hence,

$$|\vec{a}| = \frac{|\vec{F}_{\text{trp}}|}{M} = \mu g$$ and $\mu = \frac{|\vec{a}|}{g}$.

On the other hand, $|\vec{a}| = |\vec{v}|^2/2s$. Substituting this value into the expression

⟦folio 39⟧

for μ, we get

$$\mu = \frac{|\vec{v}|^2}{2gs} \approx 0,2.$$

In the case when the brakes of one of the options do not work, the total friction force acting on the shafts and the locomotive is equal to

$$|\vec{F}'_{\tau p}| = \mu nmg,$$

where $m$ is the mass of one cylinder. The mass of the entire composition is $M = (n+1)m$, so $m = M/(n+1)$. The acceleration of the train in this case is equal to

$$|\vec{a}'| = \frac{|\vec{F}'_{\tau p}|}{M} = \frac{n}{n+1} \mu g,$$

and the braking distance is

$$s' = \frac{|\vec{v}|^2}{2|\vec{a}'|} = \frac{n+1}{n} \frac{|\vec{v}|^2}{2\mu g} = \left(1 + \frac{1}{n}\right) s = 110 \text{ m.}$$

***

It is important to remember that the friction force does not always slow down movement. In many cases, movement becomes possible precisely because of it.

Could you run on slippery ice? Obviously not; at best, you would be able to freeze in place. The frictional force between the soles and the ground, which prevents slipping, creates the acceleration necessary for acceleration.

Problem 2. At what friction coefficient can a person climb a slide with a height of $h = 10$ m with an inclination angle of $\alpha = 0,1$ pad in a time of $t = 10$ s without prior acceleration? Assume that human power does not limit the time of movement, and air resistance is small.

The friction force acting on a person prevents slippage and is therefore directed onto a slide with a height of $h = 10$ m from a slope of $\alpha = 0,1$ pad with a friction coefficient of $\mu = 0,05$?

⟦folio 40⟧

Projection of the forces acting on a person in the direction of the slide plane (Fig. 4), for the acceleration model we obtain

$$|\vec{a}| = g \sin \alpha - \mu g \cos \alpha.$$

Human terminal speed

$$\vec{v} = \sqrt{2|\vec{a}|l} = \sqrt{2|\vec{a}|h/\sin \alpha} = \sqrt{2gh(1 - \mu \text{ctg} \alpha)} \approx 10 \text{ m/c}.$$

At $\mu \geqslant tg \alpha$ a person can stand on a hill and, therefore, can go down it as slowly as a corner.

Of course, everything said applies not only to humans, but also to automation. The frictional force between the tires and the road, preventing skidding, accelerates the car when the wheels are connected to the engine. The same force, which also prevents slipping, slows down the movement of the car when the brake pads are pressed to the wheels.

***

Let us now consider the role of the friction force when moving in a circle.

Problem 4. A coin (Fig. 5) lies at the edge of a disk with radius $R$. The disk spins up so that its catching speed increases linearly with time: $\omega = \varepsilon t$. At what point in time does the coin leave the disk if the coefficient of friction between the disk and the coin is $\mu$? What wall is formed by the friction force directed towards the center of the disk at this moment?

As long as the coin lies on the disk, its linear speed $v$ is equal to the linear speed of the disk:

$$v = \omega R = \varepsilon Rt.$$

As you can see, this speed is not constant, but increases linearly with time. Consequently, the coin moves with acceleration, the projection of which on the direction of the tangent to the circle is equal to $a_1 = \varepsilon R$. In addition, since the coin moves in a circle, it also has a centripetal acceleration (that is, a projection of the acceleration in the direction towards the center of the circle) $a_2 = v^2/R = \varepsilon^2 Rt^2$. Thus, the acceleration of the coin is equal in magnitude (see Fig. 5)

$$|\vec{a}| = \sqrt{a_1^2 + a_2^2} = \varepsilon R \sqrt{1 + \varepsilon^2 t^4}.$$

The only force acting on the coin in the plane of the disk is the force $\vec{F}_{\tau p}$. According to Newton’s second law, it creates acceleration $\vec{a}$:

$$m\vec{a} = \vec{F}_{\tau p} \text{ и } m|\vec{a}| = |\vec{F}_{\tau p}|.$$

Substituting expressions for $\vec{a}$ and for the maximum value of the friction force $|\vec{F}_{\tau p}| = \mu mg$ into the last formula, we obtain that the coin can lie on the plane until the moment

$$t = \frac{1}{\sqrt{\varepsilon}} \left( \frac{\mu^2 g^2}{\varepsilon^2 R^2} - 1 \right)^{1/4}.$$

At $\varepsilon > \mu g/R$ the coin follows immediately, since the friction force will not be able to provide the columnar acceleration of the coin.

The direction of the friction force coincides with the direction of acceleration, therefore

$$tg \alpha = \frac{a_1}{a_2} = \frac{\varepsilon R}{\varepsilon^2 Rt^2} = \left( \frac{\mu^2 g^2}{\varepsilon^2 R^2} - 1 \right)^{1/4}.$$

It is convenient to solve many problems on friction forces by applying the law of conservation of energy.

Problem 5. A body sliding with a speed $\vec{v}$ along the main surface flies onto a rough surface with a friction coefficient $\mu$ (Fig. 6). At what minimum length of the body $l$ will it remain so that part of it will still be on the main surface?

From the law of conservation of energy it follows that the initial kinetic energy of the body is equal to the work done against the friction forces:

$$\frac{mv^2}{2} = A_{\tau p}.$$

When doing work, it is necessary to take into account that the friction force changes as the body moves from the head surface to the rough one. If there is a body of length $x$ on a rough surface,

$$|\vec{F}_{\tau p}| = \frac{\mu mg}{l} x,$$

that is, the friction force is proportional to the distance traveled. Therefore, when

⟦folio 41⟧

moving the whole body work

$$A_{\text{тр}} = \int_0^l |\vec{F}_{\text{тр}}| \, dx = \frac{\mu m g}{l} \int_0^l x \, dx = \frac{\mu m g l}{2}.$$

Substituting this expression into the equation expressing the law of conservation of energy, for the minimum body length we obtain

$$l = |\vec{v}|^2 / \mu g.$$

***

In conclusion, we will consider a fairly common phenomenon - jamming: in some cases it is impossible to overcome the friction force, even by applying a very large external force.

Problem 6. A rod is pulled out of a pipe having a diameter slightly larger than the diameter of the rod (Fig. 7, a). A grain of sand in the shape of a parallel (relation $a/b = 0,1$) falls into the gap between the rod and the pipe. Estimate at what value of the friction coefficient between the grain of sand and the surfaces of the rod and pipe, the rod cannot be pulled out of the pipe. Assume that the friction coefficient between the pipe and the rod is negligible.

When the rod moves, a friction force $\vec{F}_{\text{тр}}$ arises between it and the grain of sand. This force, acting on the sand, creates a moment that rotates it around the point $O$ (Fig. 7, b). If this moment is greater than the moment of reaction force $\vec{R}$, rotating the grain of sand in the opposite direction, it will not be possible to pull out the rod, since the grain of sand will be pressed into the rod. In other words, if

$$|\vec{F}_{\text{тр}}| l \sin \alpha > |\vec{R}| l \cos \alpha,$$

the rod will jam.
