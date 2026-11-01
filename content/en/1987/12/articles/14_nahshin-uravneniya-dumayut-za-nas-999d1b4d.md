---
id: 1987-12-nahshin-uravneniya-dumayut-za-nas-999d1b4d
issue: kvant_1987_12
year: 1987
number: "12"
title: Equations think for us
authors:
  - Нахшин В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 49
page_labels: 44-47
tag: 5ORN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 90a43e7926da635befee44a46e6bd6d9d7f407d9acebb9f86314aa28fce1788d
prompt_sha256: draft-1
translated_from: content/ru/1987/12/articles/14_nahshin-uravneniya-dumayut-za-nas-999d1b4d.md
source_content_sha256: 41d3d40e78fb7fa539f22384d89e57834f4b52358b0fc4f4560e1356c00cc0c0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

Equations
think for us

V. A. NAKHSHIN

The solution to any calculation problem in physics consists of two parts - physical and mathematical.

While we think about the conditions of the problem, analyze in accordance with what physical laws this phenomenon occurs, and compose the appropriate system of equations, we are physicists. After this, physics temporarily fades into the background. Now we are mathematicians, and we are faced with different problems: how to most rationally solve the resulting system of equations and find the answer? Moreover, the answer must be found in a general (literal) form, so that on the side of the equal sign there is only the desired quantity (in the letter designation), and on the right is a combination of only known quantities (the same in the corresponding letter designation).

This article was first published in the September issue «Kvant» in 1981. (Note ped.)

But now the answer in general form has been obtained, and we again turn to physics: before substituting numerical data, we need to check the dimension of the desired quantity and analyze the answer from the point of view of its plausibility. If the dimension is correct and the answer is plausible, you can substitute the data and count.

The described solution stages are inherent in practically all problems. However, sometimes - and it is precisely such cases that will be discussed in the article - after calculations, an unexpected absurd result is obtained, which indicates an incorrect decision. This happens, for example, when neither the condition of the problem, nor intuition, nor common sense can tell in which direction this or that process is proceeding or what the final result will be.

When starting to solve a problem, we are forced to assume some option and, in accordance with it, create a system of equations. If the answer turns out to be absurd, you should not check in. We were just unlucky: our assumption turns out to be wrong. However, we still received information - the process is not moving in the expected direction.

⟦folio 45⟧

Well, let's say another option and so on. The problem turns into a small study, and the equation turns into something to think about. In the end, they will not let us down (of course, if we do not let them down, that is, if we do not make a mistake in drawing up the decision) and will tell us about the true direction of the process or the final result.

Let's consider several specific tasks.

Problem 1. At the top of a rough inclined plane there is a block, through which a thread is thrown. Two bodies with masses $m_1=3$ kg and $m_2=2$ kg are attached to the end of the thread. Find the acceleration of the system and the friction force between the feather body and the plane if the friction coefficient is $\mu=0,5$ and the angle of inclination of the plane to the horizon is $\alpha=30^\circ$.

Where is the system accelerating and is it moving at all? It is not clear from the problem statement. Meanwhile, it is very important to know this. So, if the system is moving, sliding friction occurs and the model of this force is equal to $F_{\text{rp}}=\mu N$ (N is the model of the normal reaction force). If the system ends, the first body is affected by the static friction force, about which it is only known that it is not greater than the sliding friction force.

Maybe intuition will help? On the one hand, the first body is heavier than the second, but, on the other hand, the second body hangs in the air, and the first lies on an inclined plane, and besides, there is a train. No, intuition will not help us, we need analysis. Let's try to transfer our worries to equations.

Let us assume that the block rotates clockwise, i.e., the second body descends with a slight acceleration, and the first body rises along the plane with the same acceleration. Let us depict the links acting on each body (Fig. 1), and write down the system of equations of the second law. Newton in projections onto the corresponding directions (for the first body these are the directions along the plane and perpendicular to it, and for the second body this is the vertical direction):

$$\begin{align*}
T &= m_1 g \sin \alpha - \mu N = m_1 a, \\
N &= m_1 g \cos \alpha = 0, \\
m_2 g &= T = m_2 a.
\end{align*}$$

Solving this system, we get

$$a = g \frac{m_2 - \mu m_1 \cos \alpha - m_1 \sin \alpha}{m_1 + m_2} \approx -1.6 \text{ m/c}^2$$

— the projection of the projection onto the chosen direction is negative. This means our assumption is incorrect.

What then happens to the system? Moving in the opposite direction? And with what kind of sincerity?

In this place, many people make a mistake, considering that the system is accelerated in the opposite direction with the same acceleration model ($\approx 1.6 \text{ m/c}^2$). Sometimes this can be considered valid. For example, if there were no friction force in this system, when the selected direction of movement changed to the opposite, the projections of all forces would change their sign, and the acceleration would turn out to be the same in modulus, but with the opposite sign. In our case, under the new assumption, the projection of the friction force is still negative, so the corresponding system of equations will be different (Fig.2):

$$\begin{align*}
m_1 g \sin \alpha - T - \mu N = m_1 a, \\
N - m_1 g \cos \alpha = 0, \\
T - m_2 g = m_2 a.
\end{align*}$$

⟦folio 46⟧

From here

$$a = g \frac{m_1 \sin \alpha - \mu m_1 \cos \alpha - m_2}{m_1 + m_2} \approx -3,6 \text{ m/c}^2.$$

And again the acceleration projection turned out to be negative; therefore, the new assumption is also incorrect.

So, the equations, having “thought” for us, lead to the conclusion that the system is not accelerating, that is

$$a = 0.$$

This means that to find the friction force, or more precisely, the static friction force, you cannot use the formula $F_{\tau p} = \mu N$, which is valid for the sliding friction force.

To determine the required force, let's see what other forces (or their projections) act on the first body in the direction along the inclined plane. This is the projection of the string force, equal in modulus to $m_1 g \sin \alpha = 15 \text{ H}$, and the thread tension force, the model of which can be found from the condition of rest of the second body: $T = m_2 g = 20 \text{ H}$. Consequently, the static friction force is directed downward along the plane and is equal in magnitude

$$F_{\tau p, n} = T - m_1 g \sin \alpha = 5 \text{ H}.$$

By the way, it is not difficult to verify that in this case the friction force $F_{\tau p, n} = 5 \text{ H}$ is really less than $\mu N = \mu m_1 g \cos \alpha \approx 13 \text{ H}.$

Problem 2. A calormeter containing $m_1 = 3$ kcal at a temperature $t_1 = -10^\circ \text{C}$ is filled with $m_2 = 2$ kcal at a temperature $t_2 = 80^\circ \text{C}$. What temperature will be established as a result of heat exchange? The heat capacity of the calorimeter is not taken into account.

It is clear that the final temperature $t$ is in the range from $-10$ to $+80^\circ \text{C}$:

$$-10^\circ \text{C} < t < 80^\circ \text{C}.$$

Consequently, it can be greater than $0^\circ \text{C}$, the ice traction temperature, less than this temperature, or equal to it. It is impossible to say in advance what exactly it turns out to be. We will make our way to the goal “by touch,” going through possible options and relying on the will of the equation.

Let's assume that $t > 0^\circ \text{C}$, i.e. there will be only water in the calorimeter. Then the ice receives tello in three stages: being ice itself, heating up from $-10$ to $0^\circ \text{C}$, turning into water at $0^\circ \text{C}$ and, being already water, heating up from $0^\circ \text{C}$ to $t$. In this case, the water will separate the body only when cooled from a temperature of $t_2$ to $t$. Let us write the corresponding heat balance equation:

$$c_1 m_1 (0 - t_1) + \lambda m_1 + c_2 m_1 (t - 0) + c_2 m_2 (t - t_2) = 0,$$

where $c_1 = 2,1 \cdot 10^3$ J/(kg K) and $c_2 = 4,2 \cdot 10^3$ J/(kg K) are the specific heat capacities of ice and water, and $\lambda = 3,4 \cdot 10^5$ J/kg is the specific heat of ice. From here we will find

$$t = \frac{c_1 m_1 t_1 + c_2 m_2 t_2 - \lambda m_1}{c_2 (m_1 + m_2)}.$$

Substituting the numerical data, we get $t < 0^\circ \text{C}$. This means that our assumption is incorrect.

Now let's assume that $t < 0^\circ \text{C}$. Consequently, our second assumption was also incorrect.

The only option left is $t = 0^\circ \text{C}$. This will be the answer to the problem.

Here we foresee some increase in docs for the reader: why does the author choose examples where all the initial assumptions turned out to be incorrect and both such cumbersome solutions lead to relatively simple results ($a = 0, t = 0^\circ \text{C}$)? Why not, in fact, assume these simple options in advance?

This path is possible, but it will not buy relief. So, in the first problem, assuming rest and not having a formula for the static friction force, we will have to create a system of three equilibrium equations, but having solved it and find the friction force, we must check whether the sliding friction force is real or not. If it turns out that it is not, you will have to start all the solutions described above over again.

⟦folio 47⟧

In the second problem, assuming $t = 0^\circ\text{C}$, we must confirm this heat balance equation, but do not know how to construct it. We don’t know which reached zero: the ice “from below” or the water “from above”, and as a result - did some (and what part) of the ice melt or did some of the water freeze? You can, of course, again assume something, but the number of options will be no less, and even more, than in the above solution.

Problem 3. Find points in all branches of the diagram shown in figure 3. Here are $\mathcal{C}_1 = \mathcal{C}_2 = \mathcal{C} = 1\text{ B}$, $r_1 = r_2 = r = 1\text{ Om}$ and $R_1 = R_2 = R_3 = R = 10\text{ Om}$.

Let us assume that the points $I_1, I_2$ and $I_3$ are directed as shown in figure 3, although we do not know this for sure. If we are wrong, the corresponding equations will correct us.*)

Since electric charge does not accumulate at branching points (nodes), the charge entering a node per unit time is equal to the charge leaving the node during the same time, i.e.

$$I_1 = I_2 + I_3.$$

Let us select two simple closed contours in this diagram, for example, left and right, and select the traversal directions in them, for example, counterclockwise. According to the law of conservation of energy, the algebraic sum of the emf is equal to the algebraic sum of the directions:

$$\mathcal{C} - \mathcal{C} = I_1R + I_1r + I_2r + I_2R,$$
$$-\mathcal{C} = -I_2R - I_2r + I_3R.$$

Let’s combine the resulting equations in the system and substitute numerical data for simple ones:

$$I_1 = I_2 + I_3,$$
$$10I_1 + I_1 + I_2 + 10I_2 = 0,$$
$$10I_2 + I_2 - 10I_3 = 1.$$

Having solved this system, we find

$$I_1 = -\frac{1}{31}A,$$
$$I_2 = \frac{1}{31}A,$$
$$I_3 = -\frac{2}{31}A.$$

The first and third currents turned out to be negative. This means that our assumptions about their directions were incorrect. We found the numerical values ​​correctly, and the directions of these currents are opposite to those expected.

Problem 4. A body is thrown vertically upward with an initial speed $v_0 = 25\text{ m/c}$. How long will it take for it to reach height $h = 40\text{ m}$?

Let us write down the well-known formula for the coordinates of a body thrown vertically upward (we consider the upward direction to be positive):

$$h = v_0t - \frac{gt^2}{2}.$$

Solving it for $t$, we get

$$t = \frac{v_0 \pm \sqrt{v_0^2 - 2gh}}{g}.$$

However, when substituting numerical data, it turns out that the expression under the root is negative. What does this mean?

It turns out that this equation, in its own language, tells us that this body does not reach such a height at all. In fact, the maximum height of a subbem is $h_{\max} = v_0^2/2g \approx 31,5\text{ m}$, which is less than $h = 40\text{ m}$.

So there are times when an equation is “thought” unexpectedly, unplanned.

Exercises

1. A homogeneous lever with mass $m = 10\text{ кг}$ is described on a support located at a distance $l_1 = 25\text{ cm}$ from its left end. Lever length $l = 1\text{ м}$. A mass of mass $m_1 = 2\text{ кг}$ is suspended from the left end of the lever. With what force is necessary to act downwards on the right end at an angle $a = 30^\circ$ to the horizontal so that the lever is in equilibrium?

2. In a calorimeter, where there is $m_1 = 1\text{ кг}$ ice at a temperature $t_1 = 0^\circ\text{C}$, there is $m_2 = 500\text{ г}$ water vapor at a temperature $t_2 = 100^\circ\text{C}$. What temperature will be reached after heat transfer occurs? The heat capacity of the calorimeter can be calculated.

3. A body is thrown vertically upward with an initial speed $v_0 = 15\text{ m/c}$. How far will it travel in $t = 2\text{ с}$ flight? The free fall acceleration is considered equal to $g = 10\text{ m/c}^2$.
