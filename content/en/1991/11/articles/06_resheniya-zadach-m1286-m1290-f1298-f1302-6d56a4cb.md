---
id: 1991-11-resheniya-zadach-m1286-m1290-f1298-f1302-6d56a4cb
issue: kvant_1991_11
year: 1991
number: "11"
title: Solutions to problems M1286—M1290; F1298—F1302
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 28
page_labels: 20-26
lang: en
source: kvant_digital
extraction: vision
content_sha256: 261a9ccb1917164d1149f757ea88fa868ad6e3187978a58892d2f71143be351c
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/06_resheniya-zadach-m1286-m1290-f1298-f1302-6d56a4cb.md
source_content_sha256: 88c2a046f870b14712689bd5f6f2b8538f9d40912201df40678c34652032c93c
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 20⟧

---
running_head:
folio:
---

Problem solutions

M1286. The congress will be attended by 100 delegates, each of whom knows several foreign languages. It is known that any three people can talk to each other without the help of others. Prove that delegates can be accommodated in 50 double rooms so that those living in the same room can talk to each other.

1
2
4
3

M1287. In parallelogram ABCD, the diagonal AC is greater than the diagonal BD. Point M on the diagonal AC also means that a circle can be circumscribed around the quadrilateral BCMD. Prove that BD is the common tangent of the circumcircles of the triangles ABM and ADM.

M1288. Prove that the number $235^2 + 972^2$ is composite.

Let us prove by induction a more general statement about 2n delegates and n double rooms, n ≥ 2.

It is natural to depict the situation in the form of a graph - a system of points (representing delegates), some pairs of which are connected by an edge (namely, those pairs of delegates that can talk to each other).

For 4 delegates (n=2), the statement is verified by some brute force. If 1, 2, 3, 4 are delegates (vertices of the graph), each of which can talk to at least one of the others, but at the same time they cannot be accommodated in two double rooms with the conditions met (i.e., the graph is missing one of the edges 12 or 34, as well as one of the edges 13 or 24 and edge 14 or 23), then the only possibility remains is the case corresponding to a graph consisting of three edges emerging from one vertex (see figure), which contradicts the conditions.

The transition from n to n+1 is very clear. Let's assume that the statement is proven for 2n delegates, and prove it for 2n+2. You can choose any pair of them who know a common language and place them in the same room. And the remaining 2n delegates, by induction assumption, can be accommodated in n rooms in accordance with the conditions of the problem.

D. Fomin

To prove this statement for the circumcircle of triangle ABM, it is enough to check the equality of the angles MBD and BAM. But since the quadrilateral BCMD hangs in a circle, $\angle BAM = \angle MOD = \angle MBD$. For the other circle the proof is similar.

D. Fomin

This amount is equal to $1000009 = 3^2 + 1000^2$. Let us prove this general fact. If a number m of the form 4k+1 (k is a natural number) can be represented as a sum of two squares in at least two different ways, then m is composite.

Let

$$m = x^2 + y^2 = u^2 + v^2,$$

where we can consider the numbers x>u odd, and y<v even. Then the most common divisor of the number

⟦folio 21⟧

---
running_head:
folio:
---

$x - u$ and $v - y$ are even numbers; let's denote it $2d$. Let
$x = u - 2da$, $v = y - 2db$, (2)

where $a$ and $b$ are coprime. Substituting expressions (2) into
(1), we obtain after reductions
$au + da^2 = by + db^2 = abc$. (3)

This number is divisible by $a$ and $b$, and therefore also by their products.
conducting; We denoted the quotient by $c$. Thus, as follows from (3), $u = bc - ad$, $y = ac - bd$, whence
$x = u + 2ad = bc + ad$ (here $a$, $b$, $c$, $d$ are some natural numbers) and
$m = x^2 + y^2 = (bc + ad)^2 + (ac - bd)^2 = (a^2 + b^2)(c^2 + d^2)$.

Having done these calculations for these numbers, it is not difficult to find the corresponding expansion for the number $10^6 + 9$.

A stronger statement can be proven: the number $m = 4k + 1$ is prime if and only if it can be represented in a unique way as the sum of two squares. Euler noted that this criterion is convenient for checking the primality of large numbers (the search for essentials is reduced if you use information about what remainders squares can produce when divided by small numbers*).

N. Vasiliev, D. Fomin

M1289. The sum of the integers $a_1, a_2, ..., a_n$ (written along a circle) is equal to 1. For each $k$ from 1 to $n$, we use $N_k$ to denote the number of positive sums among the $n$ sums (starting with $a_k$):

$a_k, a_k + a_{k+1}, ..., a_k + a_{k+1} + ... + a_n + a_1 + ... + a_{k-1}$.

Prove that all $N_k$ are different.

We will assume that the numbers $a_1, a_2, ..., a_n$ are written in the form of points $A_1, A_2, ..., A_n$ located clockwise on the circle. The conditions are to say that point $A_k$ maximizes point $A_j$, and write it as $A_k > A_j$, if the sum of all numbers from $a_k$ to $a_{j-1}$ clockwise is positive. (Of course, under $a_0$ is the concept $a_n$.) Then from the condition that the sum of all numbers $a_1, a_2, ..., a_n$ is equal to 1, the following two properties follow:

1) If $A_k > A_j$ and $A_j > A_i$ then $A_k > A_i$. (Here only the case depicted in figure needs explanation, when the other $A_k A_j$ and $A_j A_i$ overlap each other. In this case, the sum of the numbers on one and the other arc is not less than $1 + 1 = 2$, on the entire circle the sum is equal to -1, therefore, the sum of the numbers on the arc $A_k A_i$ is not less than 1.)
2) For any two points $A_k$ and $A_j$ either $A_k > A_j$ or $A_j > A_k$.

It remains to note that $N_k$ is the number of points that point $A_k$ maximizes. It follows that all these numbers are different. In fact, if $A_k > A_j$ and $A_j$ maximize $N_j$ of some points, then $A_k$, according to property 2), maximizes all these points and at least one more - $A_j$, therefore $N_k > N_j$.

D. Fomin

* More details about this are written, for example, in the wonderful book “Encyclopedia of Elementary Algebra and Analysis” by G. Weber, Mathesis Publishing House, Odessa, 1906.

⟦folio 22⟧

---
running_head:
folio:
---

M1290. A square sheet of erased paper with 8x8 layouts is lined with 14 straight lines into 64 1x1 cells and randomly folded along these lines into a booklet with 1x1 layout (out of 64 sheets). The pages of the book are numbered in order of numbers 1, 2, ..., 64, and then it unfolds again. Let p be the largest difference in the numbers of neighboring (bordering on the side) cells. What is the smallest possible value of p at what fold is it achieved?

F1298. A heavy ball is thrown upward with speed $v_0$. Considering the drag force to be proportional to the speed of the ball, find the length of time after which the ball will fall to the point from where it was thrown. At speed $v_0$ the resistance force is $F = \alpha v_0 \gg mg$ (here $\alpha$ is the proportionality coefficient, $m$ is the mass of the ball).

Answer: the smallest possible value of $p$ is 15 and is achieved by folding the accordion first in one direction and then in the other.

Let us prove that for any fold, he will find two adjacent cells with a difference in numbers of at least 15.

Each of the 14 segments of length 8, which the square is divided into cells, when folded turns into a segment (of the same or shorter length); Some segments may completely coincide and will later be folded together.

Let us consider a neoctor segment of length 8, which, when folded, turns into a segment of length 1, along which the last folding is carried out - when the booklet 2x1 is folded into one cell 1x1; Moreover, we choose this “red” segment so that on one side and the other there are points on the square that are located before the last fold in two different cells of the 2x1 book. Consider 8 pairs of square cells separated by a red segment (at figure they are connected by their heads). At the last fold, each of these pairs turns out to be a violation: between the corresponding pages there will be at least 14 others, so the difference in their numbers is at least 15.

N. Vasiliev

Let us denote the maximum lifting height of the ball by $h$. According to the conditions of the problem, the friction is high, so we will assume that the fall will occur at a steady speed

$$v_{yct} = mg/\alpha$$

and fall time

$$\tau_{пад} = \frac{h}{v_{yct}} = \frac{h\alpha}{mg}.$$

When moving upward, the ball is subject to a constant gravitational force and a changing resistance force. Therefore, the acceleration of the ball is equal to $a = g + \alpha v/m$ and is directed downward. Let at some moment the speed of the ball be equal to $v_i$. Then small increments of speed and displacement will correspond

$$\Delta v_i = a_i \Delta t_i = g \Delta t_i + \frac{\alpha v_i}{m} \Delta t_i,$$

$$\Delta h_i = v_i \Delta t_i.$$

⟦folio 23⟧

---
running_head:
folio:
---

Summing each of the correspondences, we get

$$\sum \Delta v_i = v_0 = g \sum \Delta t_i + \frac{\alpha}{m} \sum v_i \Delta t_i,$$

$$\sum \Delta h_i = h = \sum v_i \Delta t_i,$$

or

$$v_0 = g \sum \Delta t_i + \frac{\alpha}{m} h,$$

where is the rise time?

$$\tau_{\text{подд}} = \sum \Delta t_i = \frac{v_0}{g} - \frac{\alpha h}{mg}.$$

Then we will finally find

$$\tau_{\text{обшт}} = \tau_{\text{подд}} + \tau_{\text{падд}} = \frac{v_0}{g}.$$

An interesting answer was obtained: if the viscosity is high enough, then the rise and fall time no longer depends on the viscosity and is exactly half the rise and fall time in the absence of resistance. In fact, there is nothing surprising here - as the viscosity increases, the lift height decreases.

A. Andrianov

F1299. A black ball with a radius of $r=1$ m is suspended on a thin thread $l=1$ m long. The entire system is placed in an evacuated glass tube with argon at a pressure of $p_0=0,1$ Pa. The ball is illuminated with a horizontal beam of light, the energy flux density in which is equal to $w_0 = 100$ J/(m$^2$·s). Estimate the deviation of the ball from its equilibrium position under the influence of light. Neglect the conductivity of the ball. Take into account that an absolute black body, heated to an absolute temperature of $T$, emits surface units per unit of time of energy equal to $\sigma T^4$, where $\sigma=5,67 \cdot 10^{-8}$ W/(m$^2$·K$^4$). The gas temperature in the tube is constant and equal to $T_0=293$ K. The molar mass of argon is $M=0,04$ kg/mol, the density of the ball is $\rho=1$ g/cm$^3$.

Light falling on the ball from one side heats it by a certain amount $\Delta T$ ($\Delta T \ll T_0$). The ball does not conduct heat, so the incoming energy goes, firstly, to radiation, and secondly, to exchange heat with the surrounding gas.

The power dissipated by radiation per unit surface area is

$$W_1 = \sigma (T_0 + \Delta T)^4 - \sigma T_0^4 \approx 4 \sigma T_0^3 \Delta T.$$

If $N$ gas molecules collide with a unit surface of the ball in one second and $\Delta W$ energy is given off at each impact, then a total of power is given into the environment

$$W_2 = N \Delta W.$$

Let 1/6 of all molecules moving to the surface of the ball have the same speed $v = \sqrt{3RT_0/M}$, and the concentration of molecules in the vessel is $n = p_0/(kT_0)$. Then (let’s make an upper bound)

$$\Delta W = \frac{3}{2} k (T_0 + \Delta T) - \frac{3}{2} k T_0 = \frac{3}{2} k \Delta T,$$

$$W_2 = \frac{1}{6} nv \Delta W = \frac{1}{4} \frac{p_0 v \Delta T}{T_0}$$

And

$$\frac{W_2}{W_1} = \frac{1/4 p_0 \Delta T \sqrt{3RT_0/M/T_0}}{4 \sigma T_0^3 \Delta T} \approx 0,01.$$

⟦folio 24⟧

---
running_head:
folio:
---

Thus, we find that we can neglect heat exchange with the gas and assume that all incoming energy is used only for re-radiation. That's why

$$\Delta T = \frac{W_{\text{пост}}}{4\sigma T_0^3} = \frac{w_0 \pi r^2}{4\sigma T_0^3} = 17,5 \text{ К}.$$

The gas pressure on the illuminated part of the ball is greater than on the unilluminated part, since atoms during a collision acquire on average a greater speed, and therefore carry away a greater impulse:

$$p = nkT_{\text{эфф}} = nk(T_0 + (\Delta T))/2,$$

$$\Delta p = p - p_0 = nk \frac{\Delta T}{2} = \frac{p_0 \Delta T}{2T_0}.$$

The pressure force acting on the ball is equal to

$$F = \Delta p \pi r^2,$$

force of gravity -

$$mg = \frac{4}{3}\rho r^3,$$

deviation of the ball from its equilibrium position -

$$x = l \frac{F}{\sqrt{m^2 g^2 + F^2}} \approx 0,2 \text{ мм.}$$

A. Semenov

F1300. It is known that when an uncharged conducting sphere is introduced into a single-wire electric field, the directional field $E_0$ of the directional field greater than point A (Fig. 1) turns out to be equal to $3E_0$, and that greater than point B is zero. Determine the direction of the field of large points B. Find the total charge induced on the BAB hemisphere. Radius of the sphere R.

There are several ways to solve this problem. We will look at one of them here.

First, let's find the distribution of charges on the sphere. Let us denote the surface charge density near point A by $\sigma_0$ and look for the angular dependence of $\sigma(\alpha)$ in the form $\sigma(\alpha) = \sigma_0 f(\alpha)$ (Fig. 2). Due to symmetry, the function $f(\alpha)$ is even, i.e. $f(\alpha) = f(-\alpha)$. Let's use the principle of superposition - imagine the field $\vec{E}_0$ (Fig. 3) as the sum of two single-line fields $\vec{E}_1$ and $\vec{E}_2 (E_1 = E_2)$. Let us express the charge density near point A in terms of the charges induced by the fields $\vec{E}_1$ and $\vec{E}_2$:

$$\sigma_A = \sigma_0 = \sigma(\vec{E}_1) + \sigma(\vec{E}_2) = \sigma_0 \frac{E_1}{E_0} f(\alpha) + \sigma_0 \frac{E_2}{E_0} f(\alpha).$$

Here we took advantage of the fact that the constant $\sigma_0$ in the distribution $\sigma(\alpha)$ is proportional to the external field:

$$\frac{\sigma_0(E_0)}{E_0} = \frac{\sigma_0(E_1)}{E_1} = \frac{\sigma_0(E_2)}{E_2}.$$

⟦folio 25⟧

---
running_head:
folio:
---

$$E_1 = E_2 = E_0 / (2 \cos \alpha),$$
Means,
$$f(\alpha) = \cos \alpha.$$

Now let's find the value of $\sigma_0$. To do this, consider a small loaded area on the sphere, including point $A$. If you get very close to it, it will turn into a familiar object - an infinite loaded plane, which creates a single-wire field directed $\sigma_0 / (2\varepsilon_0)$, directed in both directions from the plane. Inside the sphere the field is zero, outside in the immediate vicinity of the point $A$ it is equal to $3E_0$. Passing through the section we have selected gives a field jump $3E_0$, which means
$$\frac{\sigma_0}{2\varepsilon_0} - \left( -\frac{\sigma_0}{2\varepsilon_0} \right) = 3E_0 \Rightarrow \sigma_0 = 3\varepsilon_0 E_0.$$

Note that the density of loads at point $B$ is equal to - $\sigma_0$ (this can be seen from the symmetry: however, this also follows from the formula we obtained for the function $f(\alpha)$). Consequently, the field near this point is the same as near point $A$, only it is directed not from the sphere, but towards it. So, the desired direction of the field

$$\vec{E}_B = \vec{E}_A = 3\vec{E}_0.$$

All that remains is to find the full load $BAB$. Divide it into thin rings - one of them is seen on figure 4. The charge of this ring is equal to
$$\Delta Q = \sigma_0 \cos \alpha \cdot \Delta S = \sigma_0 \cos \alpha \cdot 2\pi R \sin \alpha \cdot R\Delta \alpha.$$

Substituting here the value $\sigma_0$ and summing up the loads (the intergal turns out to be quite simple, but if you don’t want to count it, try expressing the area of ​​​​the projection of this peg onto the plane passing through the center of the sphere and perpendicular to $\vec{E}_0$), we get
$$Q = 3\pi \varepsilon_0 R^2 E_0.$$

V. Mozhaev

It is clear from the condition that in the first case the field is created only by the coil connected to the network. The magnetic flux in this coil is equal to
$$\Phi_1 = LI_1,$$

where $L$ is the inductance of the coil, $I_1$ is the current in it. Obviously, the flux in the third coil is also proportional to the current $I_1$, i.e.
$$\Phi_3 \sim I_1,$$ or $$\Phi_3 = MI_1,$$

where $M$ is the coefficient, which is usually called the interaction of the coils. Then for the ratio of directions on the coils we obtain
$$\frac{U_3}{U_1} = \frac{\Phi'_3}{\Phi'_1} = \frac{\Phi_3}{\Phi_1} = \frac{M}{L} = \frac{1}{2}.$$

In the second case, there are currents in two coils - one connected to the network and one short-circuited. That's why

⟦folio 26⟧

---
running_head:
folio:
---

nick is ideal, the magnetic permeability of the core does not change at different values ​​of magnetic induction.

let's write down

$$\Phi_1^* = LI_1^* + MI_2^*,
\Phi_3^* = MI_1^* + MI_2^*,
\Phi_2^* = MI_1^* + LI_2^* = 0$$

(since the circuit resistance is low).
From here we get

$$I_2^* = -I_1^* \frac{M}{L}$$

And

$$\frac{U_3^*}{U_1^*} = \frac{\Phi_3^*}{\Phi_1^*} = \frac{MI_1^* + MI_2^*}{LI_1^* + MI_2^*} = \frac{M - M^2/L}{L - M^2/L} = \frac{M}{L} \frac{1 - M/L}{1 - M^2/L^2} = \frac{M}{L} \frac{1}{1 + M/L} = \frac{1}{3}.$$

Therefore, the voltmeter will now show the source voltage.

A. Andrianov

F1302. A body of mass M leaning against the wall, perpendicular to the wall, is subject to a force that changes according to the harmonic law $F = F_0 \cos \omega t$. A non-spring spring is placed between the body and the wall. What should its rigidity be so that the amplitude of the force acting on the wall differs from $F_0$ by a factor of 3?

This is a general problem for calculating forced oscillations. The solution is the equation of oscillations of the load with the frequency of the forced force (see figure):

$$x = A \cos (\omega t + \varphi),$$

where $A$ is the amplitude, $\varphi$ is the phase shift of forced oscillations.

According to Newton's second law,

$$F_0 \cos \omega t - kx = Ma,$$

or

$$F_0 \cos \omega t - kA \cos (\omega t + \varphi) = -M \omega^2 A \cos (\omega t + \varphi).$$

It can be seen that the phase shift $\varphi$ is equal to either 0 or $\pi$. In both cases, the amplitude of the slya $T = kx$ can be written in the form

$$T_{\max} = kx_{\max} = \frac{F_0}{|1 - M \omega^2 / k|}.$$

We are interested in the values ​​$k$ for which $T_{\max} = 3F_0$ and $T_{\max} = 1/3F_0$, so we write

$$1 - \frac{M \omega^2}{k_1} = \frac{1}{3} \Rightarrow k_1 = 3/2 M \omega^2,$$

$$\frac{M \omega^2}{k_2} - 1 = \frac{1}{3} \Rightarrow k_2 = 3/4 M \omega^2,$$

$$\frac{M \omega^2}{k_3} - 1 = 3 \Rightarrow k_3 = 1/4 M \omega^2.$$

I. Vorobiev
