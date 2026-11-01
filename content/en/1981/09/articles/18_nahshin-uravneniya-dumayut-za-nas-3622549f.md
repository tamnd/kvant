---
id: 1981-9-nahshin-uravneniya-dumayut-za-nas-3622549f
issue: kvant_1981_9
year: 1981
number: "9"
title: Equations think for us
authors:
  - Нахшин В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 47
page_labels: 42, 44, 45
tag: R8SR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6d58be7d9156fd92760dbf7fcfe5d4da87a60711b043f9054fbc39e4790fbc83
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/18_nahshin-uravneniya-dumayut-za-nas-3622549f.md
source_content_sha256: e779f1e3336090a2d036273ae5fd71ef06d582f7093cdaa7a6d726c998ab5976
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

V. Nakhshin

Equation
think for us

The solution to any calculation problem in physics consists of two parts - physical and mathematical.

While we think about the conditions of the problem, analyze in accordance with what physical laws this phenomenon occurs, and compose the corresponding system of equations, we are physicists. After this, physics temporarily fades into the background. Now we are mathematicians, and we are faced with different problems: how to most rationally solve the resulting system of equations and find the answer? Moreover, the answer must be found in a general (literal) form, so that the trace from the equal sign is the desired quantity (in the letter designation), and on the right is a combination of only known quantities (the same in the corresponding letter designation).

But now the answer in general form has been obtained, and we again turn to physics: before substituting numerical data, we need to check the dimension of the desired quantity and analyze the answer from the point of view of its similarity. If the dimension is correct and the answer is plausible, you can substitute the data and count.

The described solution stages are inherent in practically all problems. However, sometimes - and it is precisely such cases that will be discussed in the article - after calculations, the necessary absurd result is obtained, which indicates an incorrect decision. This happens, for example, when neither the condition of the problem, nor intuition, nor common sense can tell in which direction this or that process is proceeding or what the final result is.

When starting to solve such a problem, we are forced to assume some option and, in accordance with it, create a system of equations. If the answer turns out to be absurd, you should not check in. We're just unlucky: our assumption turns out to be wrong. However, we still received information - the process is not moving in the expected direction. Well, let's say another option and so on. The problem turns into a small study, and the equations turn into something like a meditation exercise. In the end, they will not let us down (of course, if we do not let them down, that is, we do not make a mistake in drawing up the decision) and will tell us about the true direction of the process or the final result.

Let's consider several specific tasks.

Problem 1. At the top of a scissor-grabbed inclined plane there is a block through which a thread is thrown (Fig. 1). Two bodies with masses $m_1=3$ kg and $m_2=2$ kg are attached to the end of the path. Find the acceleration of the system and the friction force between the first body and the plane if the friction coefficient is $\mu=0,5$ and the plane is relative to the horizon $\alpha=30^\circ$.

Where is the system accelerating and is it moving at all? It is not clear from the problem statement. Meanwhile, it is very important to know this. So, if the system

⟦folio 44⟧

plane. This is the projection of the force of gravity, equal in modulus to $m_1 g \sin \alpha = 15$ N, and the tension force of the thread, the model of which can be found from the condition of rest of the second body: $T = m_2 g = 20$ N. Consequently, the static friction force is directed along the plane downwards and is equal in modulus

$$F_{\text{тр.п}} = T - m_1 g \sin \alpha = 5 \text{ Н}.$$

By the way, it is not difficult to verify that in this case the friction force $F_{\text{тр.п}} = 5$ N is really less than $\mu N = \mu m_1 g \cos \alpha \approx 13$ N.

Problem 2. In a heater containing $m_1 = 3$ ice at a temperature $t_1 = -10^\circ C$, moisture $m_2 = 2$ and water at a temperature $t_2 = 80^\circ C$. What temperature is established as a result of heat exchange? Ignore the heat capacity of the heater.

It is clear that the final temperature $t$ is in the range from - 10 to +80 ° C:

$$-10^\circ C < t < 80^\circ C.$$

Consequently, it can be greater than 0°C—the gravitational temperature of ice—or less than or equal to this temperature. It is impossible to say in advance what exactly it turns out to be. We will make our way to the goal “by touch”, going through possible options and relying on the will of the equation.

Let's assume that $t > 0^\circ C$, that is, that there will be only water in the heater. Then the ice receives heat in three stages: being ice itself, heating up from -10 to 0°C, turning into water at 0°C and, being already water, heating up from 0°C to $t$. In this case, water gives off heat only when cooled from temperature $t_2$ to $t$. Let us write the corresponding heat balance equation:

$$c_1 m_1 (0 - t_1) + \lambda m_1 + c_2 m_2 (t - 0) + c_2 m_2 (t - t_2) = 0,$$

where $c_1 = 2,1 \cdot 10^3$ J/(kg K) and $c_2 = 4,2 \cdot 10^3$ J/(kg K) are the specific heat capacities of ice and water, and $\lambda = 3,4 \cdot 10^5$ J/kg is the specific heat of melting of ice. From here we will find

$$t = \frac{c_1 m_1 t_1 + c_2 m_2 t_2 - \lambda m_1}{c_2 (m_1 + m_2)}.$$

Substituting the numerical data, we get $t < 0^\circ C$. This means that our assumption is incorrect.

Now let's assume that $t < 0^\circ C$. In this case, water gives off heat in three stages - cooling to 0°C, turning into ice at 0°C and cooling as ice to the desired temperature $t$, and first-year ice receives heat only in one stage - heating from $t_1$ to $t$:

$$c_1 m_1 (t - t_1) + c_2 m_2 (0 - t_2) - \lambda m_2 + c_1 m_2 (t - 0) = 0.$$

Solving this equation, we get

$$t = \frac{c_1 m_1 t_1 + c_2 m_2 t_2 + \lambda m_2}{c_1 (m_1 + m_2)}.$$

Let's substitute the numerical data and make sure that $t > 0^\circ C$. Therefore, the second sentence was also incorrect.

The only option left is $t = 0^\circ C$. This will be the answer to the problem.

Here we foresee some frustration for the reader: why does the author deliberately select examples where all the initial sentences turn out to be incorrect, and both columns of cumbersome solutions lead to relatively simple results ($a = 0, t = 0^\circ C$)? Why not, in fact, offer these simple options in advance?

This path is possible, but it does not promise relief. So, in the first problem, having proposed rest and not having a formula for the static friction force, we must create a system of three equilibrium equations, but having solved it and found the friction force, we must definitely check whether it is actually less than the sliding friction force. If it turns out that it is not, you will have to start all the solutions described above over again.

In the second problem, by proposing $t = 0^\circ C$, we must confirm this heat balance equation, but we do not know how to construct it. We don’t know which is equal to zero: ice “from below” or water “from above”, and as a consequence - has part (and what part) of the ice melted or has part of the water frozen? You can, of course, offer something, but the number of options will be no less, and even more, than in the above solution.

Problem 3. Find threads in all branches of the circuit shown in figure 4. Here $\mathcal{G}_1 = \mathcal{G}_2 = \mathcal{G}_3 = 1$ B,

⟦folio 45⟧

Fig. 4.

$$r_1 = r_2 = r = 1 \text{ Ом} \text{ и } R_1 = R_2 = R_3 = R = 10 \text{ Ом}.$$

Let us assume that the points $I_1, I_2$ and $I_3$ are directed as shown in figure 4, although we do not know this for sure. If we are wrong, the corresponding equations will correct us.

Since electric charge does not accumulate at branching points (nodes), the charge entering a node per unit time is equal to the charge leaving the node during the same time, that is

$$I_1 = I_2 + I_3.$$

Let us select two simple closed contours in this diagram, for example, left and right, and select the traversal directions in them, for example, counterclockwise. According to the law of conservation of energy, the algebraic sum of the emf is equal to the algebraic sum of the divisions of the direction:

$$\mathcal{E} = I_1 R + I_1 r + I_2 r + I_2 R,$$
$$-\mathcal{E} = -I_2 R - I_2 r + I_3 R.$$

Let’s combine the resulting equations into a system and, for simplicity, substitute numerical data:

$$\begin{cases}
I_1 = I_2 + I_3, \\
10 I_1 + I_1 + I_2 + 10 I_2 = 0, \\
10 I_2 + I_2 - 10 I_3 = 1.
\end{cases}$$

Having solved this system, we find

$$I_1 = -\frac{1}{31} \text{ А}, \quad I_2 = \frac{1}{31} \text{ А}, \quad I_3 = -\frac{2}{31} \text{ А}.$$

The first and third points turned out to be negative. This means that our assumptions about their directions were incorrect. We found the numerical values ​​correctly, and the directions of these currents are opposite to those expected.

Problem 4. A body is thrown vertically upward with an initial speed $v_0 = 25 \text{ м/с}$. How long will it take for it to reach height $h = 40 \text{ м}$?

Let us write down the well-known formula for the coordinates of a body thrown vertically upward (we consider the upward direction to be positive):

$$h = v_0 t - \frac{g t^2}{2}.$$

Solving it for $t$, we get

$$t = \frac{v_0 \pm \sqrt{v_0^2 - 2gh}}{g}.$$

However, when substituting numerical data, it turns out that the expression under the root is negative. What does this mean?

It turns out that this equation in its own language tells us that this body does not reach such a height at all. In fact, the maximum rise height is $h_{\text{max}} = v_0^2 / 2g \approx 31,5 \text{ м}$, which is less than $h = 40 \text{ м}$.

So there are times when an equation is “thought” unexpectedly, unplanned.

The English naturalist Thomas Huxley once compared mathematics to millstones that grind only what is poured into them, nothing more. The above examples illustrate this idea - if the wrong idea was put into the equation, the solution will become “husk” and thereby push us to the bottom of the rational “grain”.

Exercises

1. A homogeneous lever with a mass of $m = 10$ kg rests on a support located at a distance of $l_1 = 25$ cm from its left end. The length of the lever is $l = 1$ m. A load weighing $m_1 = 2$ kg is suspended from the left end of the lever. What force must be exerted on the right end downward at an angle $\alpha = 30^\circ$ to the horizontal so that the lever is in equilibrium?

2. In 卡尔iter, where there is $m_1 = 1$ kg of ice at a temperature of $t_1 = 0^\circ \text{C}$, $m_2 = 500$ g of water vapor is admitted at a temperature of $t_2 = 100^\circ \text{C}$. What temperature will be reached after heat transfer occurs? Heat capacity 卡尔itera can be used.

3. A body is thrown vertically upward with an initial speed $v_0 = 15 \text{ м/с}$. How far will it travel in $t = 2$ flight? The free fall acceleration is considered equal to $g = 10 \text{ м/с}^2$.
