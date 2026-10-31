---
id: 1989-4-chernoutsan-zakonyi-sohraneniya-energii-i-impulsa-f5a4eb67
issue: kvant_1989_4
year: 1989
number: "4"
title: Laws of conservation of energy and momentum
authors:
  - Черноуцан А. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 62
page_last: 65
page_labels: 60-63
tag: KNZ3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 04c93a6763bbb39cd4f74d6c63604926a7a7fecb8d5ab1348608e4a964eedcb4
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/15_chernoutsan-zakonyi-sohraneniya-energii-i-impulsa-f5a4eb67.md
source_content_sha256: c3b35ad79a8af9de2d2d29166c285bf1099c75ed8130d9d993f0f64c79e999b5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Laws of conservation of energy and momentum

Candidate of Physical and Mathematical Sciences
A. I. CHERNOUTSAN

This article discusses the joint use of two conservation laws - energy and momentum - to solve various physical problems.

At applied exams in physics, a situation arises when applicants, having a good knowledge of each conservation law separately, experience “psychological” difficulties when it is necessary to combine these laws together within the framework of one task. Moreover, most often, taking away is accelerated by a simpler, in our opinion, law - the law of conservation of momentum. Having written down the corresponding equation for energy, the applicant no longer remembers the implus - and... gets into trouble. However, it happens differently.

Let's look at a few specific examples of how the joint “efforts” of energy and impulse lead to the desired result.

Problem 1. Two balls, made of the same material and having masses $m_1$ and $m_2$, move towards each other at speeds $v_1$ and $v_2$. How much will the temperature of the balls increase after any absolute inelastic impact if the specific heat capacity of the materials of the balls is c?

The initial temperatures of the balls quickly increase their internal energy:

$$\Delta E_{\text{вн}} = c (m_1 + m_2) \Delta t.$$

Many applicants mistakenly believe that as a result of a blow to internal energy

⟦folio 61⟧

The entire initial kinetic energy of the system $m_1 v_1^2/2 + m_2 v_2^2/2$ is transferred to the initial energy. At the same time, they forget that the balls cannot remain after the impact, since this would contradict the law of conservation of momentum - the initial momentum of the system $m_1 \vec{v}_1 + m_2 \vec{v}_2$, generally speaking, is not equal to zero. This means that when calculating energy, it is necessary to take into account the kinetic energy of the balls in the final state.

Let us denote the speed of the balls collapsing after an absolutely inelastic impact by $v$ and write down the laws of conservation of energy and momentum, more precisely, the projection of momentum onto the direction of motion of the first ball:

$$\frac{m_1 v_1^2}{2} + \frac{m_2 v_2^2}{2} = \frac{(m_1 + m_2) v^2}{2} + \Delta E_{\text{вн}},$$

$$m_1 v_1 - m_2 v_2 = (m_1 + m_2) v.$$

Solving the three equations obtained together, we find the desired temperature increase:

$$\Delta t = \frac{m_1 m_2 (v_1 + v_2)^2}{2 c (m_1 + m_2)^2}.$$

Problem 2. The virgin valon, whose masses are $M_1$ and $M_2$, are moving towards each other at speeds $v_1$ and $v_2$. When a collision occurs, four identical buffer springs roll down, after which the valances diverge. Find the maximum deformation of each spring if its spring constant is $k$.

In this problem, unlike the previous one, you can use the law of conservation of mechanical energy (assuming that the friction is small and the springs are ideal), equating the initial energy of the rollers to the energy of the system at the moment when the deformation of the springs $x$ is maximum. In this case, the desired value $x$ will be included in the potential energy of the spring deformation of the springs:

$$E_p = 4 k x^2/2.$$

However, in addition to this energy, it is also necessary to take into account the kinetic energy of the valons.

The fact that at maximum approach the rollers do not stop (which, unfortunately, many applicants forget about), follows, as in the previous problem, from the law of conservation of momentum. The only peculiarity of this moment is that at maximum deformation of the springs, the speeds of the rollers are the same: $v'_1 = v'_2 = v$. Therefore, the laws of conservation of energy and momentum (or rather, its projection) look like this:

$$\frac{M_1 v_1^2}{2} + \frac{M_2 v_2^2}{2} = \frac{(M_1 + M_2) v^2}{2} + 4 \frac{k x^2}{2},$$

$$M_1 v_1 - M_2 v_2 = (M_1 + M_2) v.$$

From here we get

$$x = \frac{1}{2} \sqrt{\frac{M_1 M_2}{k (M_1 + M_2)}} (v_1 + v_2).$$

Problem 3 (ballistic matrix). A block of mass $M$, suspended on parallel threads of length $l$, is hit by a horizontal flying bullet of mass $m$ and gets stuck in it (Fig. 1). As a result of the impact, each thread is deflected by an angle $\alpha$. Find the initial speed of the spring v. The threads are considered ideal (weightless and non-stretchable).

As can be seen from figure, the angle of deflection of the threads $\alpha$ is related to the height $h$ at which the block rises:

$$h = l (1 - \cos \alpha),$$

and the height $h$ can be associated with the potential energy of the block and bullet in the final state:

$$E_p = (M + m) gh.$$

The question arises: is the conservation law satisfied in this situation?

⟦folio 62⟧

mechanical energy? In other words, is the energy of the system in the final state equal to its initial energy, i.e., the kinetic energy of the bullet $mv^2/2$? The answer, of course, is negative. After all, we know that during an inelastic impact, part of the mechanical energy transforms into internal energy.

How can this be? Let's consider another, intermediate state of the system - immediately after the end of the impact, when the bullet is already stuck in the block, but the beggars are still vertical. The energy of the system in this state is simply the kinetic energy of the block and the bullet: $E_k=(m+M)v'^2/2$, where $v'$ is their total speed. After the inelastic impact has already ended, there will be no more energy lost, and we can write

$$E_k=E_p,$$

or

$$\frac{(m+M)v'^2}{2}=(M+m)gh.$$

The speed $v'$ can be related to the initial speed of the bullet using the law of conservation of momentum

$$mv=(m+M)v'.$$

From the last two equations, taking into account the expression for $h$, we have

$$v=2\left(1+\frac{M}{m}\right)\sqrt{gl}\sin \frac{a}{2}.$$

Note that in this problem the laws of conservation of momentum and energy do not work simultaneously, but as if in turn. It turns out that this is not so easy to understand, and many applicants solve problems of this type using only the law of conservation of energy, obtaining, of course, incorrect results.

Problem 4. Three small loaded balls - the mass of each ball is $m$, the charge $q$ - are contained by identical ideal threads of length $l$ and form an equilateral triangle (Fig. 2). One of the threads is cut and the balls begin to move. Find the maximum speed of the middle ball (3) while moving. In fact, the force of gravity can be transformed.

Since the system is closed and only Coulomb interaction forces act in it, the law of conservation of energy can be applied to the system. In this case, we will not take into account the interaction energy of balls 1, 3 and 2, 3, since it is the same in states a) and 6) (see Fig. 2). Then the law of conservation of energy will have the form

$$\frac{kq^2}{l}=\frac{kq^2}{r_{12}}+2\frac{mv^2}{2}+\frac{mV^2}{2}.$$

Based on this equation alone, it is impossible not only to calculate the required speed $V$, but also to understand when it is maximum. However, since the system is closed, we can also apply the law of conservation of momentum - the total momentum of the three balls is always zero. For the projections of impulses we obtain

$$0=2mv-mV.$$

Now it is clear that the speed $V$ will be maximum when balls 1 and 2 are farthest from each other, i.e. when $r_{12}=2l$. Solving the corresponding equations, we find

$$V=q\sqrt{\frac{2}{3}\frac{k}{ml}}.$$

For some reason, many schoolchildren are used to solve this problem of the law of conservation of momentum, which seems unusual or even strange.

Problem 5. On a block of length $l$ and mass $M$, located on the main horizontal surface, lies a small body with mass $m$ (Fig. 3). The friction coefficient between the body and the block is $\mu$. At what speed $v$

⟦folio 63⟧

should the system move so that after controlling the impact of the block against the wall, the body falls from the block?

The impact of the block against the wall will cause its speed to abruptly change to the opposite. The speed of the body will not change during the impact, and it will begin to slide along the block.

Let us find the distance $x$ the body will move relative to the block before the end of sliding. It is clear that conditions $x > l$ will be the condition for a body to fall from the block. The work of the sliding friction force is associated with the distance $x$ -

$$A_{\text{тр}} = -\mu mgx,$$

which, in turn, is equal to the change in the kinetic energy of the system:

$$A_{\text{тр}} = \frac{(m+M)v^2}{2} - \left(\frac{mv^2}{2} + \frac{Mv^2}{2}\right).$$

Here $v'$ is the speed of the block with the body at the moment when the body stops relative to the block. This speed can be found from the law of conservation of momentum

$$Mv - mv = (M+m)v'.$$

Solving all three equations together, we get

$$x = \frac{2Mv^2}{\mu g(M+m)}.$$

Condition $x > l$ allows you to find the initial speed:

$$v > \sqrt{\frac{1}{2}\mu g\left(1 + \frac{m}{M}\right)}.$$

It may seem incomprehensible why the work $A_{\text{тр}}$ is equal to the product of the force times the displacement of the body relative to the block - after all, the block does not stand still, and therefore moves

The motion of a body relative to the ground is not equal to its displacement relative to the block. The fact is that the change in the mechanical energy of the system is equal to the total work $F_{\text{тр}}$ - both on the body and on the block:

$$A_{\text{тр}} = \left(F_{\text{тр}}x\right) + \left(-F_{\text{тр}}x\right) = F_{\text{тр}}x.$$

In conclusion, we will analyze the problem of calculating a nuclear reaction. In this problem, the vector nature of the law of conservation of momentum appears more clearly than in the previous ones.

Problem 6. To carry out the synthesis reaction of heavy and superheavy hydrogen isotopes ($^2H + ^3H = ^4He + n$), the action nuclei accelerated to the energy $E = 2M\theta B$ are directed at a Tritz target. The detector detects neutrons emitted perpendicularly to the direction of the deuteron beam. Determine the energy of resisted neutrons if energy $\Delta E = 14M\theta B$ is released in the reaction.

The law of conservation of energy in this reaction has the form

$$\frac{m_{\text{д}}v_{\text{д}}^2}{2} = E = \frac{m_{\text{r}}v_{\text{r}}^2}{2} + \frac{m_{\text{н}}v_{\text{н}}^2}{2} - \Delta E$$

(hereinafter the index “d” denotes deuterium, “g” - helium, “n” - neutron). The law of conservation of momentum must be written in projections both on the $X$ axis (the direction of the velocity of incident deuterons) and on the $Y$ axis (the direction of escape of resisted neutrons):

$$m_{\text{д}}v_{\text{д}} = m_{\text{r}}v_{\text{rx}},$$

$$0 = m_{\text{н}}v_{\text{н}} - m_{\text{r}}v_{\text{ry}}.$$

Taking into account that $v^2_{\text{r}} = v^2_{\text{rx}} + v^2_{\text{ry}}$, we get

$$\frac{m_{\text{н}}v_{\text{н}}^2}{2} \left(1 + \frac{m_{\text{н}}}{m_{\text{r}}}\right) = \Delta E + \frac{m_{\text{д}}v_{\text{д}}^2}{2} \left(1 - \frac{m_{\text{д}}}{m_{\text{r}}}\right).$$

From here, taking into account that $m_{\text{н}}/m_{\text{r}} = 1/4$ and $m_{\text{д}}/m_{\text{r}} = 1/2$, we find the energy of resisted neutrons:

$$E_{\text{н}} = \frac{4}{5} \left(\Delta E + \frac{1}{2}E\right) = 12M\theta B.$$

Exercises
1. A cart of mass $M$ moves with speed $v$ on a smooth horizontal surface (Fig. 4). On the cart from above
