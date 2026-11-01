---
id: 1984-7-voinov-o-gidravlicheskom-udare-4fe4babf
issue: kvant_1984_7
year: 1984
number: "7"
title: About water hammer
authors:
  - Воинов Е. М.
rubric: osnovnye-stati
page_first: 28
page_last: 31
page_labels: 26, 27, 29
tag: AE7H
lang: en
source: kvant_digital
extraction: vision
content_sha256: babe5f95eadf52fdd97aef00b5f8c4ace39d9d3309b0ac6059167002bff34d3c
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/09_voinov-o-gidravlicheskom-udare-4fe4babf.md
source_content_sha256: 44957c2970e8287f050044eedc6fe05a8bf2e216e8c7f8763ba0f1f66f650aec
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

About water hammer

Candidate of Technical Sciences
E. M. VOINOV

At the end of the 19th century, cases of rupture of city water supply pipes became more frequent in Moscow, and service accidents at hydraulic stations occurred more than once. There were no apparent causes for the events, and in 1897 the great Russian scientist Nikolai Egorovich Zhukovsky began studying this issue. As a result, the now classic work “On Hydraulic Impact in Water Pipes” appeared, in which Zhukovsky gave an extremely clear solution to the problem, brought to direct practical application. He showed theoretically and then experimentally verified that when the shut-off devices are quickly closed and, consequently, the movement of water through the pipe is quickly stopped, the pressure in the pipeline increases sharply. This phenomenon, called water hammer, causes pipes to burst. Let's get to know him in more detail.

N. E. Zhukovsky proposed that a sharp increase in pressure in the pipe is due to the unsteady movement of the liquid. He came to the conclusion that in the process of increasing pressure in a pipe after a rapid depainting, all the liquid in the pipe participates in the flow, and its kinetic energy is converted into the potential energy of elastic deformation of the liquid itself (that is, leads to a sharp increase in pressure in it), and is also spent on work on elastic deformation of the pipe walls. Let us explain how this process occurs.

Let a liquid flow from a large reservoir (figure 1) through a sufficiently long pipe at a speed of $v_0$. At the end of the pipe there is a valve that can quickly close the pipe (what “quickly” means, we will explain later). When the valve is quickly closed, at the first moment of time a certain layer of liquid located on the front of the valve and up to the reservoir stops. Obviously, the boundary of the high pressure area will move in the same direction. It is important to remember that in this case all layers of liquid remain in their places, mixing only by an insignificant amount, determined by the value of the elastic deformation of each layer. There is a transfer of the state of deformation from the layer to the layer and the associated spread of a region of increased pressure along the pipe. As they say, a pressure wave spreads.

Let us now determine the maximum value of the resulting unsteady fluid motion. To do this, let’s select a small volume of liquid adjacent to the valve (this is the layer discussed above). Let the pipe area be $S$, and the layer thickness $\Delta x$; then the allocated volume of liquid is $S \cdot \Delta x$, and its mass is $m = \rho S \cdot \Delta x$. In the short time $\Delta t$ during which this one stops, it loses momentum $\Delta (mv_0) = \rho S \cdot \Delta x \cdot \Delta v_0$, which leads to an increase in pressure in it by $\Delta p$. According to Newton’s second law, the change in the momentum of this layer is determined by the momentum of the resulting pressure force $F = S \cdot \Delta p$, that is

$$F \cdot \Delta t = \Delta p \cdot S \cdot \Delta t = \rho S \cdot \Delta x \cdot v_0.$$

From here

$$\Delta p = \rho v_0 \left( \frac{\Delta x}{\Delta t} \right).$$

⟦folio 27⟧

The quantity $c = \frac{\Delta x}{\Delta t}$ included in this expression is the speed of propagation of the boundary of the area of ​​​​high pressure (deformation) in the liquid of the water pipe. As N.E. Zhukovsky showed, this value depends on the elastic properties of the liquid itself and the materials of the pipe wall, as well as on the ratio of the thickness of the pipe wall to its diameter. It turned out that for normal use in pipelines of steel and cast iron pipes when water flows through them, this speed is close to the speed of sound in water $c_{3B} = 1450$ m/s and equal to $c = 0,9c_{3B} \approx 1300$ m/s. Thus,

$$\Delta p = \varrho v_0 c.$$

We obtained the well-known formula of N. E. Zhukovsky for excess pressure that arose during the rapid release of liquid flowing through a pipe. The phenomenon of a sharp change in fluid pressure caused by an external change in the speed of its flow is called water hammer.

Now let’s ask what should be understood by quickly closing the valve. To do this, let us consider in more detail the process of propagation of a pressure wave through a pipe. If the pipe has a length of $L$, then the time of propagation of the high-pressure area from the valve to the reservoir is $t_1 = L/c$. When this wave (often called a shock) reaches the reservoir, two layers of liquid with different pressures come into contact at the boundary of the pipe and the reservoir: one, located on the side of the reservoir, with a pressure of $p_0$, and the other, located in the pipe, with a pressure of $p_{yd} = p_0 + \Delta p$. Since under such conditions a state of equilibrium at the boundary of these words is impossible, a small amount of liquid from the pipe will flow into the reservoir, and the pressure in this section of the pipe is understood to be up to pressure $p_0$.

This state of reduced pressure (relative to the pressure $p_{yd}$ in the pipe) begins, in turn, to propagate in the opposite direction - from the tank to the valve, which it reaches after a time $t_2 = 2L/c$ from the moment the valve is closed. At time $t_2$, the initial pressure $p_0$ is established in the entire pipe. However, at the moment when the wave of reduced pressure $p_0$ reaches the valve itself, the layer of liquid adjacent to it tends to tear away from it, which leads to a decrease in pressure in it to a certain value $p_1 < p_0$. It is clear that after this the wave of reduced pressure $p_1$ begins to spread from the valve to the tank. After it reaches the boundary of the pipe and the reservoir, a shock wave will again arise there (but with increased pressure in the pipe), which reaches the valve after a time $t_3 = 4L/c$ from the beginning of the entire process. Now the process, the full cycle of which we have considered, begins to repeat itself, but due to energy losses for work against friction forces (caused by the viscosity of the liquid), the amplitude of pressure oscillations in the shock wave will gradually decrease. figure 2 shows how the pressure at the valve will change throughout the entire distance cycle. As follows from what N. E. Zhukovsky cited, the maximum increase in pressure in a pipe is usually called a direct blow.

If the closing time of the valve is greater than $2L/c$, then the amount of excess pressure turns out to be less than with a direct impact, and as N. E. Zhukovsky showed, it is determined by the expression

$$\Delta p_{\text{непр}} = \varrho v_0 c \left( \frac{L}{ct_{3akp}} - L \right).$$

For example, let’s consider the stop of water pressure in a steel pipe with a length of $L = 500$ m at a water flow speed of $v_0 = 3$ m/s. Having assumed $c \approx 1300$ m/s, we obtain: time for rapid closing of the pipe $t_{3akp} = 2L/c \approx 0,8$ s; the corresponding maximum pressure increase for a direct impact is $\Delta p_{\text{max}} = \varrho v_0 c = 39 \cdot 10^5$ Pa = 39 atm. With such an increase

⟦folio 29⟧

That it allows water to rise by $H_2=20 \div 30$ m at a pressure $H_1$ of only 1-2 m. In this case, no violation of the law of conservation of energy occurs - a significant part of the water flows out from under the clan $E$, releasing its kinetic energy. Developed by N. E. Zhukovsky. Thus, the founders of aeronautics, the Mongolf brothers, and the “father of Russian aviation,” N. E. Zhukovsky, were “strong” to him.

Finally, here is another example of a very useful use of water hammer. Currently, so-called hydraulic stamping is widely used in industry. This is done as follows. A matrix is ​​installed in a fairly strong container, made of durable material, which has a “negative” shape of the stamped product (where there should be a convexity in the product, a concavity in the matrix, and vice versa). The workpiece is placed on it, and the container is filled with liquid. In certain places, two (or more) electrodes are inserted into the container. Carrying out a powerful impulse discharge (or a series of discharges), they create a hydraulic shock, deforming the workpiece according to the shape of the matrix. In this way, steel products of significant sizes with a thickness of up to 10 mm are stamped, automatic body parts are manufactured, etc.

There are also water devices that work on this principle. Due to the energy of the discharge, it is possible to obtain a scab flow rate of up to 1000 m/s. However, the impulse blow is such a scab

“Queen in the corner”, “Izyanshins” and Fibonacci numbers

(For the beginning, see p. 18)

After the substitutions we have made, we can formulate the following theorem, which gives another description of all marked pairs.

Theorem 2. Let $(a_n, b_n)$ be a marked pair. If we imagine the natural number $n-1$ as a sum of non-repeating Fibonacci numbers: $n-1 = f_{k_1} + f_{k_2} + \dots + f_{k_l}$, then $a_n-1 = f_{k_1+1} + f_{k_2+1} + \dots + f_{k_l+1}$ or, in other words, if $n-1$ is the sum of some pairwise distinct Fibonacci numbers, then $a_n-1$ is the same sum of Fibonacci numbers with numbers one greater.
