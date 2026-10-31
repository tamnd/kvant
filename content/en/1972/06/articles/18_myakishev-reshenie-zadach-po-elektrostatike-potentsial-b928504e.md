---
id: 1972-6-myakishev-reshenie-zadach-po-elektrostatike-potentsial-b928504e
issue: kvant_1972_6
year: 1972
number: "6"
title: Solving problems in electrostatics. (Potential)
authors:
  - Мякишев Г. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 57
page_last: 59
page_labels: 55-57
tag: DBW8
lang: en
source: kvant_digital
extraction: vision
content_sha256: f22fd41b0df5377e58c14808f80073b972ee3fce5b6466677b1c1add1101e474
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/18_myakishev-reshenie-zadach-po-elektrostatike-potentsial-b928504e.md
source_content_sha256: 3148530fee6474bdb72c85a97555120d820304e85c095acad00325467651330f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Solving problems in electrostatics (Potential)

G. Ya. Myakishev

The concept of potential or potential difference causes major difficulties in the course of electrostatics.

The work of electrostatic forces is equal to the change in potential energy, taken with the opposite sign:

$$\Delta A = -(\Pi_2 - \Pi_1) = -\Delta \Pi,$$

where $\Pi_1$ and $\Pi_2$ are the initial and final energy values. Since the work is proportional to the force, and the force, in turn, is proportional to the charge $q$ on which the field acts, then the energy of the charges in the field is $\Pi \sim q$. Consequently, the ratio $\frac{\Pi}{q}$ does not depend on the charge and can be taken as a characteristic of the field. This characteristic is called potential:

$$\varphi = \frac{\Pi}{q}.$$

It follows that

$$\Delta A = -q(\varphi_2 - \varphi_1).$$

The projection of the intense field onto an arbitrary voltage specified by a small segment $\Delta l$ is related to the potential difference at the ends of this segment by the formula

$$E_l = -\frac{\Delta \varphi}{\Delta l}.$$

The concept of potential difference turns out to be quite complex due to the fact that work is expressed not through the potential itself, but through the potential difference (formula (2)). Therefore, adding any constant to the potential will not change the amount of work, and therefore will not change anything that would have physical meaning. The potential is determined up to an arbitrary constant, just like potential energy *).

Like field strength, the magnitude of the potential depends on the distribution of electrostatic charges in space. In particular, the potential of a uniformly charged infinite plane in the SI system is determined by the formula

$$\varphi = \frac{\sigma}{\varepsilon_0}x + c,$$

where $\sigma$ is the surface charge density, $x$ is the distance to the plane, $c$ is an arbitrary constant. Since the field voltage of the plane is $E = \frac{\sigma}{\varepsilon_0}$, formula (4) can be rewritten in the form

$$\varphi = Ex + c.$$

The potential of a point charge can be found using Coulomb's law and formula (2) for the potential difference. But this is quite a difficult task. It is much easier to prove that, taking the potential of a point charge in

*) It's hard to imagine. After all, if we know the potential at each point, then the voltage of the electrostatic field is also determined at each point. But at the same time, the potential at a given point can be anything, since it is determined to within a constant.

The point here is this. The potential at a point can be considered equal to any value, but the change in potential when moving from a given point to another, no matter how close, will be certain, since the dependence of the potential on the coordinates $\varphi(x, y, z)$ is known. If the potential does not change at all with such a bias, then at this point it is equal to zero. Knowing the nature of the potential change at an arbitrary point, you can always find the magnitude and voltage of the field voltage at this point using formula (3).

⟦folio 56⟧

form

$$\varphi = \frac{q}{r} + c,$$

where $c$ is an arbitrary constant, we can use (2) to obtain Coulomb’s law. This will mean that formula (6), which is given without proof in a school physics course, actually determines the potential of the exact charge in the SGSE system.

In fact, let the exact charge $q_2$ be mixed in the field of another exact charge $q_1$ for a very small segment $\Delta r$. Then, according to formulas (2) and (6),

$$\Delta A = -q_2 \left( \varphi_2 - \varphi_1 \right) = -q_2 q_1 \times \left( \frac{1}{r + \Delta r} - \frac{1}{r} \right) = \frac{q_1 q_2 \Delta r}{r^2 + r \Delta r}.$$

Since $\Delta r$ is small, then $r^2 \gg r \Delta r$ and

$$\Delta A = F \Delta r = \frac{q_1 q_2}{r^2} \Delta r.$$

Therefore, the force $F$ is equal to $\frac{q_1 q_2}{r^2}$, and this is Coulomb’s law. This means that formula (6) is valid.

Just as the directional field of the spherical symmetrically charged ball coincides with the directionally accurate charge, the potential of the charged ball (outside the ball) is also determined by formula (6). In the SI system

$$\varphi = \frac{q}{4 \pi \varepsilon_0 \varepsilon r} + c,$$

if the ball is in a homogeneous dielectric with dielectric constant $\varepsilon$.

To solve problems, it is enough to have a good understanding of the physical meaning of the basic formulas. In addition, it is often necessary to use simple but very important provisions: the work of the power plant field on a closed path is zero and all conductor points in the power plant have the same potential.

Task 1. Is it possible to exist an electric field whose direction does not change in the direction $x$ and increases in the direction $y$ (Fig. 1)?

Solution e. It cannot, because in such a field of work when moving a charge along a closed circuit

**Fig. 1.**

(for example, a rectangular one with sides parallel to $x$ and $y$) is non-zero.

Task 2. A metal leaf (Fig. 2) is attached to the inner wall of an electrical grid isolated from the ground. The rod and the body of the electric generator were connected with a wire and after that a certain charge was given to the body of the electric generator. Do the leaves of the electric meter deflect at the same time? What happens to the leaves if the wire is removed and the rod is then connected to the ground?

Solution f: The body and the rod connected by a wire will have

**Fig. 2.**

right potentials. The field of the internal electric grid is zero and the leaves will not deviate. After removing the connected wire and replacing the rod, both leaves are deflected, since a potential difference and, accordingly, an electrical grid field will arise between the rod and the body. The appearance of a very low potential difference equals zero work of the electrical field when moving a charge along a closed path $ABCDEFA$,

⟦folio 57⟧

shown in figure 3. The work on the AC section should be zero, since the CDEFA path is penetrated inside the conductor. Consequently, the potential difference between the body and the rod is equal in magnitude to the potential difference between the body and the ground, which (since the electrometer body is charged) is not zero.

Task 3. What is the potential energy Π of the interaction of two exact charges $q_1$ and $q_2$, located at a distance $r$ from each other?

Solution e. According to the definition of potential (1) and the formula for the potential exact charge (6),

$$\Pi = \varphi_1 q_2 = \varphi_2 q_1 = \frac{q_1 q_2}{r} + c. \tag{8}$$

Task 4. A solitary conducting ball of radius $R$ carries a charge $q$. What is the energy of the ball?

Solution e. If an arbitrary constant in formula (7) is set equal to zero, then the potential of the ball in emptiness

$$\varphi = \frac{q}{4\pi\varepsilon_0 R}.$$

The self-energy of the ball is not equal to $\frac{q^2}{4\pi\varepsilon_0 R}$, as it may seem at first.

The energy of the ball can be found by calculating the work that needs to be done to give the ball a charge $q$. We will charge the ball by moving a charge towards it from infinity in equal small portions. In this case, the potential of the ball will increase linearly from zero to $\frac{q}{4\pi\varepsilon_0 R}$. Average potential value $\frac{1}{2} \frac{q}{4\pi\varepsilon_0 R}$. Therefore, the energy of the ball turns out to be equal

$$\Pi = \frac{q^2}{8\pi\varepsilon_0 R}. \tag{9}$$

Task 5. At a distance $d$ from the exact charge $q$ there is an independent ball of radius $R$. What is the potential of the $\varphi$ ball?

Solution e. The potential of all points on the ball is the same. Therefore, to solve the problem it is enough to find the potential of one point on the ball. The easiest way is to find the potential of the center of the ball. It is equal to the potential created at the center of the ball by the exact charge $q$:

$$\varphi = \frac{q}{d} + \sum_i \frac{\Delta q_1}{r} = \frac{q}{d} + \frac{1}{r} \sum_i \Delta q_1 = \frac{q}{d}.$$

Task 6. Inside a hollow conducting sphere of radius $r$, carrying a charge $+Q$, a body with a charge $-q$ was introduced through a small hole. What is the potential of a point located at a distance of $R > r$ from the center of the sphere.

Solution e. First we place the charge $-q$ at the center of the sphere. On the outer surface this charge inducts a charge $-q$, and on the inner surface $+q$, and the charges are distributed evenly. The potential at a point located at a distance of $R$ is equal to $\varphi_R = \frac{Q - q}{R}$ (since the total potential is called potential equal to zero).

When a charged body moves inside a sphere, the confluent lines of the electric field are deformed, but do not penetrate through the conducting sphere. Therefore, the found value of the potential remains valid for any position of the charge $-q$ inside the sphere.

Task 7. In the center of a wire ring of radius $R$ there is a charged particle with a speed of $v_0$ (Fig. 4). Ring charge $+Q$, particle charge $-q$. What speed $v$ will the particle be away from the ring?
