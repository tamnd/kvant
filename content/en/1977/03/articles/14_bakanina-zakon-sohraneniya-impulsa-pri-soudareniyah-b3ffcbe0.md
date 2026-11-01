---
id: 1977-3-bakanina-zakon-sohraneniya-impulsa-pri-soudareniyah-b3ffcbe0
issue: kvant_1977_3
year: 1977
number: "3"
title: Law of conservation of momentum during collisions
authors:
  - Баканина Л. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46, 47, 49, 50
tag: 0B0R
lang: en
source: kvant_digital
extraction: vision
content_sha256: ed4d4d60f5adbbcf79ad5b8921de510d99ccf2192709f449f4da1f38e6d86f73
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/14_bakanina-zakon-sohraneniya-impulsa-pri-soudareniyah-b3ffcbe0.md
source_content_sha256: 5d5e2b9f344d293cb482284ab3a092f280f8199af295c666310dfc9d4f36ab6e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

L. Bakanina

Law of conservation of momentum during collision

The law of conservation of momentum (quantitative motion) is satisfied for closed systems, that is, those that include interacting bodies, so that no external forces act on any of the bodies of the system. However, when solving many physical problems, it turns out that the momentum can remain constant for independent systems. True, in this case the amount of motion is conserved only approximately. Let's try to figure out what's going on here.

The change in momentum $\Delta p$ regardless of the system is equal to the total momentum of external forces. Let us denote by $\vec{F}_{cp}$ the average value of the resulting external force acting on the system during the time interval $\Delta t$. Then

$$\Delta p = \vec{F}_{cp} \Delta t.$$

If the abscile value of this force is not too large and the time during which the force acts is short, then the product $|\vec{F}_{cp}| \Delta t$ will also be small. In this case, there will be a need to estimate with what accuracy the momentum of the system can be considered unchanged.

In addition, we should not forget that impulse is a vector, and, therefore, we can talk about preserving the projection of this vector in any direction. Indeed, if the system is not closed, but the external forces are such that the sum of the projections of all forces onto a certain direction is zero, then the projection of the system’s momentum onto this direction remains a constant value. An open-loop system in this direction is similar to a closed one.

Short-term interactions arose, for example, during explosions, shots, collisions. This is the type of problem we are discussing. Let's try to find out in each specific case whether the law of conservation of momentum is satisfied or not and what it depends on.

Task 1. From a cannon that moves without pretense along an inclined plane and has already covered the path $l$, a shot is fired in the horizon direction (Fig. 1). At what projectile speed will the gun remain after the shot? The mass of the projectile $m$ is much less than the mass of the cannon $M$, the inclined plane $\alpha$ is suitable.

Before firing, the cannon (together with the projectile), having traveled the path $l$, has an impulse $(M+m)\vec{v}_0$, directed along the inclined plane. The modulus of this impulse can be found from the law of conservation of energy:

$$\frac{(M+m)|\vec{v}_0|^2}{2} = (M+m)|\vec{g}|l\sin\alpha,$$

And

$$(M+m)|\vec{v}_0| = (M+m)\sqrt{2|\vec{g}|l\sin\alpha}.$$

Immediately after the shot, the gun remained, and the projectile fluttered in the direction of the horizon. Thus, despite the short duration of the interaction between the cannon and the projectile, they

⟦folio 47⟧

The pulse of this system is not stored. Why?

During a shot, the pressure force of the gun on the inclined plane increases sharply, which means that the reaction force on the side of the plane also increases, so that the impulse of this force turns out to be quite large. It is this that changes the total impulse of the gun and the projectile.

However, in the direction along the inclined plane, the projection of the reaction force is zero, and the projection of the gravity impulse $((M+m)|\vec{g}| \times \sin \alpha \cdot \Delta t)$ for a short shot time $\Delta t$ is small and does not increase during the shot. Therefore, we can, with some degree of accuracy, assume that in the direction along the inclined plane the projection of the momentum of the gun system - the projectile is conserved. Consequently, the projection of the total impulse of the gun and the projectile before the shot is equal to the projection of the projectile after the shot (the gun ends):

$$
(M+m)\sqrt{2|\vec{g}|l\sin \alpha}=m|\vec{v}| \cos \alpha.
$$

Hence the model of projectile speed immediately after the shot

$$
|\vec{v}|=\frac{(M+m)\sqrt{2|\vec{g}|l\sin \alpha}}{m\cos \alpha} \approx \frac{M\sqrt{2|\vec{g}|l\sin \alpha}}{m\cos \alpha}.
$$

When solving this problem, we assumed that in the direction along the inclined plane the gun-projectile system behaves as a closed system. However, we cannot assess to what degree of accuracy this is true, since the system of interacting bodies is complex and there is no need for data for such an assessment.

Let us now analyze two problems with simpler interaction, where an estimate can also be made.

Problem 2. A force is fired from a gun into a wooden ball of mass $M=1$ kg, applied downward at a speed of $|\vec{V}_0|=1$ m/sec and pierced through it. What speed will we impulse the ball immediately after emosion? The speed of the gun when approaching the ball is $|\vec{v}_0|=300$ m/sec,

after firing the ball $|\vec{v}|=100$ m/sec, the mass of the gun $m=10$ e.

Let us estimate with what accuracy the ball-bullet system can be considered closed during their interaction. In other words, let's find out whether the impulse of gravity can be neglected during this time.

The interaction time is $\Delta t \approx \frac{d}{|\vec{v}_{\text{cp}}|}$, where $d$ is the diameter of the ball and $\vec{v}_{\text{cp}}$ is the average speed of the bullet inside the ball. The diameter of the ball can be estimated by knowing that the density of wood $\rho$ is approximately equal to the density of water $\rho_B=10^3$ kg/m³:

$$
\frac{4}{3}\pi\left(\frac{d}{2}\right)^3\rho=M, \text{ и}
$$

$$
d=\sqrt[3]{\frac{6M}{\pi\rho}}\approx 0,1 \text{ м},
$$

$$
|\vec{v}_{\text{cp}}| \approx \frac{|\vec{v}_0|+|\vec{v}|}{2}=200 \text{ м/сек}.
$$

Thus, $\Delta t \approx 5 \cdot 10^{-4}$ sec. The gravitational impulse of the system during this time (and therefore the change in the total impulse of the ball and bullet)

$$
|\vec{p}|=(M+m)|\vec{g}| \Delta t \approx 5 \cdot 10^{-3} \text{ м} \cdot \text{сек}.
$$

Number of system movements before interaction

$$
|\vec{p}_0|=m|\vec{v}_0|-M|\vec{V}_0|=2 \text{ м} \cdot \text{сек}.
$$

Then the relation

$$
\frac{|\vec{p}|}{|\vec{p}_0|}=\frac{|\Delta\vec{p}_0|}{|\vec{p}_0|}=2 \cdot 10^{-3}=0,2\%,
$$

and, therefore, with an accuracy of 0.2%, we can assume that the momentum of the system does not change during interaction.

Let us write down the conservation law for the projection of momentum onto an axis directed vertically upward:

$$
mv_0+MV_0=mv+MV,
$$

or

$$
m|\vec{v}_0|-M|\vec{V}_0|=m|\vec{v}|+MV.
$$

Hence the projection of the speed of the ball after interaction

$$
V=\frac{m|\vec{v}_0|-M|\vec{V}_0|-m|\vec{v}|}{M}=1 \text{ м/сек},
$$

that is, the ball begins to move at a speed of 1 m/sec.

⟦folio 49⟧

Fig. 3.

Substituting here the corresponding value for $v_1$ and $v_2$:

$$v_1 = -|\vec{v}_1| = -\frac{|\vec{v}_0|}{4},$$
$$v_2 = |\vec{v}_2| = \frac{7|\vec{v}_0|}{4},$$

we'll find

$$v'_1 = v_2 = \frac{7|\vec{v}_0|}{4} \text{ и } v'_2 = v_1 = -\frac{|\vec{v}_0|}{4}$$

— during an elastic collision, balls of equal masses exchange velocities.

However, one should not think that during collisions one can always neglect the action of external forces and consider the system closed. For example, consider the following problem.

Problem 4. A bag of slozem flour without initial speed from a height $H$ on the main board inclined at an angle $\alpha = 60^\circ$ to the horizontal. After lowering the bag, we find ourselves on a horizontal rough floor. Coefficient of bag tray on the floor $\mu = 0,7$. Where will the bag stop?

After descending from the board, the bag has a speed $\vec{v}$, directed along the board (Fig. 3). Its absolute value can be found from the law of conservation of mechanical energy, since the board is smooth and there is no energy loss:

$$|\vec{v}| = \sqrt{2|\vec{g}|H}$$

Let's see how the projections of the bag's momentum on the horizontal and vertical axes change upon impact with the floor. The vertical projection after the impact becomes zero - the bag is inelastic and does not bounce after the impact. This means that during the collision it is acted in a direction of zero, the momentum of which is exactly equal to the vertical projection of the momentum of the bag immediately before the collision. This force can only be a reaction force $\vec{N}_{cp}$ from the floor, therefore,

$$|\vec{N}_{cp}| \Delta t = m|\vec{v}| \sin \alpha.$$

In the horizontal direction, the bag is subject to a sliding force, the model of which is $|\vec{F}_{tp}| = \mu |\vec{N}_{cp}|$. The impulse of this force during the impact is equal to

$$|\vec{F}_{tp}| \Delta t = \mu m|\vec{v}| \sin \alpha,$$

that is, it does not depend on the law by which the support reaction force changes (and therefore the force of pressure of the bag on the floor), nor on the time of impact. Let's find the change in the horizontal projection of the bag's momentum. Let’s move the $X$ axis horizontally to the right, then, according to Newton’s second law,

$$mv'_x - mv_x = -|\vec{F}_{tp}| \Delta t,$$

or

$$v'_x - |\vec{v}| \cos \alpha = -\mu |\vec{v}| \sin \alpha.$$

Hence the projection of the speed with which the bag begins to move along the floor,

$$v'_x = |\vec{v}|(\cos \alpha - \mu \sin \alpha) = -0,1 |\vec{v}|.$$

What does the minus sign mean? Formally, the minus sign indicates that after the impact the bag should move to the left, or, in other words, that the impulse of the trey’s force turns out to be greater than the initial horizontal projection of the bag’s momentum. This means that at some point during the collision the projection of the bag’s velocity onto the $X$ axis turned to zero. From this moment on, our decision becomes wrong. Indeed, the model of the trey force is equal to $\mu |\vec{N}_{cp}|$ only when sliding, and in the state of rest the trey can take any values ​​from 0 to $\mu |\vec{N}_{cp}|$ depending on what forces (except the trey force) act on the body. In our case, no other forces have projections in the horizontal direction, therefore, at the moment when the horizontal projection of the bag’s velocity becomes zero, the force

⟦folio 50⟧

friction also goes to zero. Thus, the bag will not move on the floor at all!

Finally, let us discuss another well-known problem involving the collision of bodies. When solving this problem, they usually use rather rough approximations, without stipulating in any way that this is an approximation or under any conditions that it can be used.

Task 5. By adjusting the horizontal surface, we press a wedge of mass $M$ from a height $h$ onto a ball of mass $m$ and bounce in the horizontal direction (Fig. 4). Name of wedge velocity projection

$\vec{V}$ after impact. Trenetz pretenbrets, udar consider the absolute elastic.

Unlike all previous problems, here we need to consider the collision of not two, but three bodies - a ball, a wedge and a horizontal plane.

In the general case, without making any additional assumptions about the impact mechanism, this problem cannot be solved. In the most common solution to this problem, it is implicitly (without any reservations) assumed that the collision of the ball with the wedge and the wedge with the horizontal plane occurs simultaneously, and the wedge after the collision has only a horizontal velocity projection. Then write down the equation of the laws of collision of mechanical energy and momentum:

$$m|\vec{g}|h = \frac{MV_x^2}{2} + \frac{mv_x^2}{2},$$

$$MV_x + mv_x = 0,$$

where $V_x$ and $v_x$ are the corresponding projection of the velocities of the wedge and the ball on the horizontal axis directed to the right. From here

$$V_x = \sqrt{2|\vec{g}|h \frac{m^2}{M(M+m)}}.$$

However, in such a solution it is not at all clear where to place the vertical projection of the ball's momentum. After all, if the collision is absolutely elastic, the vertical projection of the system’s momentum does not disappear, but only changes sign! After the impact, the ball rebounds in the horizontal direction, the plane is generally motionless. This means that the wedge must bounce after impact. And the energy associated with this movement is not taken into account in the above solution.

The physical picture of the impact is more consistent with the assumption that at first the ball collides only with the wedge, and then the wedge, which has received some speed as a result of this collision, interacts with the horizontal plane. After the first impact, the vertical projection of the wedge velocity

$$V_y = \frac{m}{M} \sqrt{2|\vec{g}|h},$$

and the horizontal projections of the velocities of the wedge and the ball, as in the first solution, are related by the relation

$$MV_x + mv_x = 0,$$

or $v_x = -\frac{M}{m} V_x$.

Then the law of conservation of energy can be written as

$$m|\vec{g}|h = \frac{mv_x^2}{2} + \frac{MV_x^2}{2} + \frac{MV_y^2}{2}.$$

Substituting here the corresponding expressions for $v_x$ and $V_y$, we find the horizontal projection of the wedge speed:

$$V_x = \sqrt{2|\vec{g}|h \frac{m^2(M-m)}{M^2(M+m)}}$$

Thus, we reduced the problem of the collision of three bodies to the problem of two successive pairwise collisions (we did not need the second collision to solve the problem). At the same time, we assumed that the wedge, after colliding with the ball, moves purely translationally. This can only happen if the pressure force of the ball $\vec{N}$ during the impact passes
