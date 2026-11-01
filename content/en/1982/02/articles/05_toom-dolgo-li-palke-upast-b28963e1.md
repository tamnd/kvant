---
id: 1982-2-toom-dolgo-li-palke-upast-b28963e1
issue: kvant_1982_2
year: 1982
number: "2"
title: How long does it take for the stick to fall?
authors:
  - Тоом А. Л.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10-13
tag: IYSU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 343306e4cd8571f0c61f963bde2af848d3ebe325f51ae13f7ed8def4f954c64b
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/05_toom-dolgo-li-palke-upast-b28963e1.md
source_content_sha256: 95aafb65796ba1689e8eb7c24b0c9d3d598c882d1a420e2fe5bb7814fc331750
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

How long does it take for the stick to fall?

From the editor. When solving a real physical problem, we usually choose its idealized model, which allows us to apply mathematical methods to solve it. Of course, it is important to select the correct device for this choice. Unexpected difficulties that may arise in this case are discussed in the article published below from the point of view of a mathematician.

Do the following physics experiment. Place a vertical stick on the floor (you can use a brush, rolling pin, ruler, etc.) and smoothly, without pushing, remove your hand and release it. The stick will fall. Of course, if the stick is thick (for example, a log) and its lower end is quite robust, then it will remain standing, but we are not considering this case. Thin sticks with a pointed lower end, placed vertically on the floor, always fall if nothing supports them - this is an experimental fact.

Let us now try to compare this fact with a theoretical calculation.

As this is done when solving physical problems, let us idealize the object of consideration: together with a stick, consider a rod that has no thickness, mounted vertically on a horizontal surface; the rod is in a gravity field, and the medium does not resist movement; how long will he continue to nad?

With some appearances, you can notice that the lower end of the stick is motionless only in the initial stage of its fall; later he rides across the floor. Which direction he goes depends on the friction coefficient of the stick on the floor*. To avoid this difficulty, suppose that the lower end of our ideal rod is fixed in a hinge; there is no training.

Let us denote by $l$ the distance from the center of mass of the rod to its lower end, and by $m$ the mass of the rod. The distance is the moment in time when the rod forms a vertical angle $\alpha$, $0 < \alpha \leq \frac{\pi}{2}$ (Fig. 1). At this point, the center of mass will have dropped by $l$ (1—cos $\alpha$). This means that the potential energy decreased by $mgl$ (1—cos $\alpha$). It turned into kinetic energy, which we will write in the form $K = I \frac{\omega^2}{2}$, since it is proportional to the square of the angular velocity $\omega$ (here $I$ is a constant**), and $\omega$ depends on $\alpha$).

Indeed, if the mass of the rod is considered concentrated at its center of mass, then

$$K = \frac{1}{2} m v_0^2 = \frac{1}{2} m (l \omega)^2 = (ml^2) \frac{\omega^2}{2}.$$ (0)

If the rod is considered homogeneous, then

*) See, for example, problems 196, 197 in the assignment by B. B. Bukhovtsev et al. “Collection of problems in elementary physics” (M., “Hayka”, 1974).

**) I is called the moment of inertia; the definition of this concept can be read in the previous issue «Kvant» on p. 6, but we won't need it.

⟦folio 11⟧

Fig. 1.

$$K = \int_{0}^{2l} \frac{m(v(y))^2}{2l \cdot 2} \, dy = \frac{m}{2l} \int_{0}^{2l} \frac{(\omega y)^2}{2} \, dy = \left( \frac{4}{3} m l^2 \right) \frac{\omega^2}{2}.$$ (00)

Equating the lost potential energy and the gained kinetic energy, we get

$$\frac{1}{2} I \omega^2 = m g l (1 - \cos \alpha),$$

where

$$\omega = \sqrt{\frac{2}{l} m g l (1 - \cos \alpha)} = 2 \sqrt{\frac{m g l}{l} \sin \frac{\alpha}{2}}$$

Angular velocity $\omega$ is the rate of change of angle $\alpha$, that is, arbitrary $\alpha$ in time:

$$\omega = \frac{d\alpha}{dt}.$$

Hence (by the theorem on an arbitrary inverse function)

$$\frac{dt}{d\alpha} = \frac{1}{\omega} = \frac{1}{2} \sqrt{\frac{I}{m g l}} \cdot \frac{1}{\sin \frac{\alpha}{2}}.$$ (1)

Does this expression make sense? Integrals of continuous bounded functions are taught at school. Here, under the integral sign there is a function that is undefined at $\alpha = 0$ and tends to infinity at $\alpha \to 0$. A "curved grapeze" between the axis $\alpha$, the lines $\alpha = 0$ and $\alpha = \frac{\pi}{2}$, and the graph of this function

Fig. 2.

tsini, infinite (Fig. 2). How can we talk about the area of ​​an infinite function? It turns out that it is possible, and with a reasonable definition this area is sometimes even finite. The intergal of an unbounded function of such type as (1) is called non-proper and, by definition, is assumed to be equal to the prelude of a regular, “proper” intergal with a suitable change in its boundaries*). In this case

$$\int_{0}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = \lim_{\varepsilon \to 0} \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}}$$

The intergal under the limit sign corresponding to the shaded area on figure 2 can be calculated exactly, but for now we don’t even need it.

Recall that $\sin \alpha < \alpha$ at $0 < \alpha < \frac{\pi}{2}$.

Therefore $\sin \frac{\alpha}{2} < \frac{\alpha}{2}$, from where

$$\int_{0}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} > 2 \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = 2 \left( \ln \frac{\pi}{2} - \ln \varepsilon \right).$$

The last expression tends to infinity as $\varepsilon \to 0$.

Here you go! It turns out that the time the rod falls is infinity! But in an experiment the stick falls - does that mean theory contradicts practice?

Of course, the situation is not so unclear. If at first the rod is vertical, then it

*) See, for example, the definition of an improper integral in problem 12 of paragraph 1 of chapter V of the book by B. M. Ivlev et al. “Collection of problems in algebra and the beginning of analysis for grades 9 and 10.” (M., “Enlightenment”, 1978).

⟦folio 12⟧

will not fall at all, that is, α will always be equal to zero. We actually started our calculation with some positive α.

Since in practice the stick still falls, in theory it must be compared with the rod that falls. From a physical point of view, it would be natural to consider one of the following two cases:

1) at first the rod is vertical and has a small but non-zero angular velocity;
2) At first, the rod is motionless and deflected from the vertical by a small but non-zero angle.

But in these cases the formulas will have to be written again, and they are more complicated than those that have already been written. Therefore, let us consider the case, the simplest from a mathematical point of view: the rod falls over time (see 1))

$$T = \frac{1}{2} \sqrt{\frac{I}{mgl}} \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}}.$$

The physical meaning of this case is that initially the rod is deflected from the vertical by a small angle ε > 0 and has an initial angular velocity equal to

$$2 \sqrt{\frac{mgl}{I}} \sin \frac{\varepsilon}{2}.$$

Now there is no paradox, since the written interval has a complete definition of a finite value.

It can even be calculated exactly. Using the formula for differentiating a complex function, you can verify that

$$\left(2 \ln tg \frac{x}{4}\right)' = \frac{1}{\sin \frac{x}{2}},$$

where

$$\int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = 2 \left(\ln tg \frac{\pi}{8} - \ln tg \frac{\varepsilon}{4}\right).$$

So, the time of fall of the rod is

$$T = Q \left(\ln tg \frac{\pi}{8} - \ln tg \frac{\varepsilon}{4}\right),$$

where $Q = \sqrt{\frac{I}{mgl}}$.

If all the mass of the rod is concentrated at its center of mass, then (see (0))

$$I = ml^2 \text{ и } Q = \sqrt{\frac{l}{g}}.$$

If the rod is homogeneous, then (see (0))

$$I = \frac{4}{3} ml^2 \text{ и } Q = \sqrt{\frac{4}{3} \frac{l}{g}}.$$

In both cases, the fall time $T$ does not depend on the mass $m$ and is proportional to the square root of $l$. This corresponds to the observed fact that long sticks fall faster than short ones.

Note that the paradox stats obtained at the beginning will not always be replaced. For example, problem 195 of the mentioned problem book by B.B. Bukhovtsev et al. is formulated as follows: A massive ball (Fig. 3) is mounted on a light rod. In which case will the rod fall faster: if it is placed vertically at end $A$, or at end $B$? Standing on the ground, the end of the rod does not slip.

As a solution to this problem, the formula for angular velocity is derived

$$\omega = 2 \sin \frac{\alpha}{2} \sqrt{\frac{g}{R}},$$

where $R$ is the distance from the end of the rod to the center of mass of the ball (this formula coincides with ours at $l = R, I = mR^2$), and further: “For a given α, the larger $R$, the smaller it is. Therefore, the rod will fall more quickly if it is placed at the $B$ end” (p. 227). This reasoning is not correct, because, as we have seen, the integral of the formula written above is infinite for any $R > 0$. Does it make any sense to say that one infinity is greater than other infinities? What would in some

Fig. 3.

⟦folio 13⟧

In the sense of solving the cited problem, one can, for example, consider rods that are initially deflected from the vertical by some small angle, or have some small initial angular velocity, or both - as done above.

By the way, in a sense, we also solved problem No. 56 from the excellent problem of I. Sh. Slobodetsky and L. G. Aslamazov “Problems in Physics” (M., “Nuka”, 1980): How much is it much easier to hold a chaff on a finger than a paluta of the same length?

In the solution to this problem, given in the problem (p. 77), the reader is invited to independently consider how the time of fall depends on the length of the rod, and no mention is made of the difficulties that we are trying to overcome here. An accurate solution to this problem indeed requires consideration of the time the stick falls, but in order for this time to be finite (and only finite values ​​can be compared with each other), it is necessary to consider the initial condition, somehow different from the equilibrium condition. This consideration gives a strict meaning to an informal calculation like “the higher the center of mass of the stick, the slower it tilts, and the easier it is to move your finger in the same direction.”

In the process of discussing the original problem, we had to abandon its simplest model (an ideal hinged rod standing vertically) and consider a more complex model, since a vertical ideal rod does not fall. However, the simplest model is completely correct if you reverse time, in other words, it deals not with a falling stick, but with a raised stick. More precisely, let us consider the following problem: one end of a horizontal lying ideal rod of length l is fixed in a hinge, and the other end is given a speed directed upward and equal to $\sqrt{8gl/3}$; how will the rod rise?

The correct answer is given by integral (1): the rod will rise indefinitely, tending to a vertical position, but never reaching it. Thus, a hypnast, turning into the upper stance on the crossbar, in order not to rise to the balance point for an indefinitely long time, must, due to the maximum movement, give himself a speed that ensures movement further than this point, and remain in it due to friction (clamping the crossbar with his hands).

But here is what still remains unclear in the original problem.

Suppose we are doing several experiments with the same stick. Each time we place it on the floor, as it seems to us, vertically and let go. The stick falls, and you can make sure that the periods of time spent falling do not differ much from each other in all cases. And this is strange. After all, each time the stick actually deviates from the vertical by some other non-zero angle and has some other non-zero initial speed. This means that the duration of the fall must be different. In some cases, it would seem that the initial angle and service speed should be very small, and then the fall time should be very large, but this is not observed. What's the matter?

We can only manage to answer this question informally. Let's consider formula (2). It contains a constant term $Q \ln tg \frac{\pi}{8}$ and a variable term $Q \ln tg \frac{\varepsilon}{4}$. For small $\varepsilon$ (which is also what we are interested in), $tg \frac{\varepsilon}{4}$ is close to $\frac{\varepsilon}{4}$, and the variable term is close to

$$-Q \ln \frac{\varepsilon}{4} = Q \ln 4 - Q \ln \varepsilon.$$

So the fact is that the quantity - $\ln \varepsilon$, although it tends to infinity at $\varepsilon \rightarrow 0$, but very slowly.

For example, a decrease in $\varepsilon$ by 10 times corresponds to an increase in - $\ln \varepsilon$ by a constant value $\ln 10 \approx 2,3$.

(For the end see p. 24)
