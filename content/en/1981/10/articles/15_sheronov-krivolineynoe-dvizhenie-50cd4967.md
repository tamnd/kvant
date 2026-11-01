---
id: 1981-10-sheronov-krivolineynoe-dvizhenie-50cd4967
issue: kvant_1981_10
year: 1981
number: "10"
title: Curvilinear movement
authors:
  - Шеронов А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 51
page_labels: 47-49
tag: OPYT
lang: en
source: kvant_digital
extraction: vision
content_sha256: a84c3afaffab969a6a79cf6ceb79b6b2b9582e971e355fe9c111485204b83009
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/15_sheronov-krivolineynoe-dvizhenie-50cd4967.md
source_content_sha256: 06d4b265325d5997cc7a390cbeb8ffe620fd3af22f728d090d44fdaa059d5672
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Curvilinear movement

The movement of a body along curved trajectories is often found in nature and technology. This is, for example, the movement of satellites and meteorites in the gravity field of the Earth or planets and comets in the gravity field of the Sun, the movement of charged parts in accelerators or parts of various mechanisms.

Let us recall the basic laws that are valid for curvilinear motion. As is known, the speed of a body is always directed tangentially to its trajectory and during movement can change both in magnitude and direction. The acceleration vector of a body does not coincide in direction with the speed, but makes a certain angle with it. It is often more convenient to talk not about acceleration itself, but about its two projections. However, of these, the so-called tangential (or tangent) projection $a_T$ is a projection onto the direction of velocity (that is, towards the direction of the tangent to the trajectory). This projection characterizes the change in the velocity model. Another, so-called normal (or centripetal) projection $a_H$ is a projection in the direction perpendicular to the velocity vector. It characterizes the change in direction of speed. In particular, when a body moves uniformly in a circle, the acceleration has only one projection - normal to the speed and changing only its direction. The modulus of this projection is equal to the square of the velocity modulus divided by the radius of the circle: $a_H = v^2/R$.

A small section of any curvilinear trajectory can always be represented as part of a certain circle; the radius of the corresponding circle is called the radius of curvature of the trajectory at a given location. Therefore, the expression $a_H = v^2/R$ can be used to determine the radius of curvature of the trajectory $R$.

Finally, for a body moving along a curvilinear trajectory, as well as for a body moving under lightning, Newton’s second law is valid: the vector sum of all forces acting on the body is equal to the mass of the body multiplied by the vector of its acceleration.

Let's consider several specific problems on the curvilinear motion of a body.

Problem 1. A body is thrown from the surface of the earth with an initial speed $\vec{v}_0$ at an angle $\alpha_0$ to the horizon. Find the dependence of the tangential and normal projection of the acceleration of the body on its subheight. Air resistance can be ignored.

After the throw, only one force acts on the body - the force of gravity towards the Earth, therefore, at any point in the trajectory, the acceleration $\vec{a}$ of the body is equal to the acceleration of free fall $\vec{g}$ (Fig. 1). The tangential and normal acceleration projections are equal, corresponding to

$$a_T = g \sin \alpha \text{ и } a_H = g \cos \alpha.$$

Here $\alpha$ is the angle that makes

⟦folio 48⟧

The speed $\vec{v}$ of the body at height $h$ correlates with the horizon.

Let's write down the law of conservation of energy:

$$\frac{mv_0^2}{2} = \frac{mv^2}{2} + mgh$$

and find an expression for the model $v$ of the body velocity:

$$v = (v_0^2 - 2gh)^{1/2}$$

During movement, the projection of velocity onto the horizontal direction remains constant and equal to $v_0 \cos \alpha_0$. Then (see Fig. 1)

$$a_H = g \cos \alpha = g v_0 \cos \alpha_0 \cdot v^{-1} = g v_0 \cos \alpha_0 \cdot (v_0^2 - 2gh)^{-1/2}$$

And

$$a_T = g \sin \alpha = g (1 - \cos^2 \alpha)^{1/2} = g (v_0^2 \sin^2 \alpha_0 - 2gh)^{1/2} (v_0^2 - 2gh)^{-1/2}$$

The resulting formulas can be used to derive the maximum lifting height of the body $h_{\max} = v_0^2 \sin^2 \alpha_0 / 2g$:

$$a_H = g \cos \alpha_0 \cdot h_{\max}^{1/2} (h_{\max} - h \sin^2 \alpha_0)^{-1/2}$$

$$a_T = g \sin \alpha_0 \cdot (h_{\max} - h)^{1/2} (h_{\max} - h \sin^2 \alpha_0)^{-1/2}$$

Problem 2. The final section BC of the acceleration hill on a ski jump is an arc of a circle with a radius of $R = 15$ m (Fig. 2). The total height of the mountain is $H = 50$ m. Find the model of acceleration of the skier at point C if the angle is $\alpha = 30^\circ$. Consider that a skier is descending a mountain without any initial speed; You will neglect training.

When moving along the acceleration mountain, two forces act on the skier. This is the gravitational force $m\vec{g}$, directed vertically downward, and the reaction force

$$\vec{m}\vec{g}$$

and support $\vec{N}$, directions, in the absence of friction, along the radius of curvature of the trajectory, in our case - along the radius $CO$. The resultant of these forces gives the lieutenant the initial acceleration $\vec{a}$:

$$\vec{m}\vec{a} = m\vec{g} + \vec{N}$$

By the cosine theorem for the triangle of forces we have (see Fig. 2)

$$(ma)^2 = (mg)^2 + N^2 - 2mgN \cos \alpha.$$

Let $\vec{v}$ be the speed of the skier at point C. The normal acceleration projection $a_H = v^2/R$ creates the corresponding projections of forces $m\vec{g}$ and $\vec{N}$:

$$mv^2/R = N - mg \cos \alpha.$$

Eliminating $N$ from the last two equations, we get

$$a^2 = g^2 \sin^2 \alpha + (v^2/R)^2.$$

Let us substitute here the value of the model $v$ speed of the skier from the law of conservation of energy

$$mv^2/2 = mg(H - R(1 - \cos \alpha))$$

and find the model of skier acceleration:

$$a = (g^2 \sin^2 \alpha + (v^2/R)^2)^{1/2} = g(\sin^2 \alpha + 4(H/R - 1 + \cos \alpha)^2)^{1/2} \approx 65 \text{ m/c}^2.$$

The same value can be obtained from several other calculations. When moving along a circular arc, the normal acceleration projection is $a_H = v^2/R$, and the tangential projection, created only by the corresponding gravity projection, is $a_T = g \sin \alpha$. Then the acceleration model is

$$a = (a_H^2 + a_T^2)^{1/2} = (g^2 \sin^2 \alpha + (v^2/R)^2)^{1/2}.$$

Problem 3. A small body located on a hemisphere begins to slide along the hemisphere, and then, breaking away from it, it will move like a body thrown at an angle to the horizon.

Let us introduce the coordinate system $XOY$, as indicated in Fig. 3. First, we find the coordinates $x_0$ and $y_0$ of the point from the hemisphere, as well as the model and direction of the speed $\vec{v}_0$ in the mo-

⟦folio 49⟧

Fig. 3.

ment of separation. The movement of the body along the semi-ferrier occurs under the influence of two forces - the force of gravity $m\vec{g}$ and the force of the normal (since there is no friction) reaction $\vec{N}$. At the moment of separation, the reaction force becomes zero, so that the normal acceleration $a_H = v_0^2/R$ is imparted to the body only by the corresponding projection of gravity:

$$mv_0^2/R = mg \cos \alpha_0.$$

Solving this equation together with the equation expressing the law of conservation of energy:

$$mv_0^2/2 = mgR(1 - \cos \alpha_0),$$

let's find:

$$\cos \alpha_0 = 2/3, \quad v_0 = (2gR/3)^{1/2}.$$

The coordinates of the separation point are equal to the corresponding

$$y_0 = R \cos \alpha_0 = 2R/3,$$
$$x_0 = (R^2 - y_0^2)^{1/2} = R(1 - \cos^2 \alpha_0)^{1/2} = \sqrt{5}R/3.$$

Now let’s write down the equation of motion of the body after separation from the semi-ferry:

$$x = x_0 + v_0 \cos \alpha_0 \cdot t,$$
$$y = y_0 - v_0 \sin \alpha_0 \cdot t - gt^2/2.$$

Obviously, at the moment the horizontal plane is reached, the coordinate $y$ becomes equal to zero: $y = 0$. coordinate $x$ will be found from the corresponding equation of motion, substituting there the values ​​of the initial conditions ($x_0, v_0$ and $\cos \alpha_0$), as well as the flight time before impact, obtained from condition $y = 0$:

$$x \approx 1,12R.$$

Problem 4. A wheel of radius $R$ rolls on a horizontal surface at a constant speed $\vec{v}_0$ without slipping. There is a material point of mass $m$ on the rim of the wheel. Determine the modulus and direction of the reaction force acting on the point, as well as the radius of curvature of its trajectory depending on the position of the point on the rim.

Let the instantaneous position of a material point on the wheel rim be characterized by the angle $\alpha$ (Fig. 4). From the point of view observed in a fixed coordinate system (for example, associated with the earth), the point participates in two movements - in translational movement together with the wheel with a constant horizontal speed $\vec{v}_0$ and in rotational movement around the center of the wheel with an angular speed $v_0/R$.

Let us take advantage of the fact that in different inertial coordinate systems the accelerations of the body are the same. Let us consider a coordinate system moving together with the center of the wheel at a speed $\vec{v}_0$. In this system, a material point moves uniformly around a circle. Normal acceleration $\vec{a}_H(a_H = v_0^2/R)$ is imparted to it by two forces - gravity $m\vec{g}$ and reaction force $\vec{N}$. By the cosine theorem from the triangle of forces we have (see Fig. 4):

$$N^2 = (mg)^2 + (mv_0^2/R)^2 - 2(mg)(mv_0^2/R) \cos \alpha,$$

where

$$N = ((mg)^2 + (mv_0^2/R)^2 - 2(mg)(mv_0^2/R) \cos \alpha)^{1/2}.$$

The direction of the force $\vec{N}$, determined by the angle $\alpha$, can be found from the same triangle using the law of sines:

$$N/\sin \alpha = mg/\sin \varphi,$$

Fig. 4.
