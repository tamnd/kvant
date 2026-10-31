---
id: 1971-3-resheniya-8f59aa9a
issue: kvant_1971_3
year: 1971
number: "3"
title: Solutions to problems M26—M28; F35—F40
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32, 33, 34, 35, 37, 38, 39
tag: 2KIG
lang: en
source: kvant_digital
extraction: vision
content_sha256: ec5137c35c76f9a8f255e847663f347355fd24604f62eb5a364d1508fe5ec306
prompt_sha256: draft-1
translated_from: content/ru/1971/03/articles/09_resheniya-8f59aa9a.md
source_content_sha256: bd64d325a2302e14f6c4b01d1587b5aa0bdd559fe3c204d3dfb12307184aaecf
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

SOLUTIONS

M26

Let's assume that in each issue of our magazine there will be five mathematics problems in the "Kvata" task. Let us denote by $f(x, y)$ the number of the first of the tasks of the $x$-th issue of the journal for the $y$ year (for example, $f(6, 1970) = 26$). Write the general formula for $f(x, y)$ for all $x, y$ ($1 \leq x \leq 12, y \geq 1970$). Solve equation $f(x, y) = y$.

The function $f$ satisfies the following conditions:

1) $f(1, 1970) = 1$;
2) $f(x + 1, y) = f(x, y) + 5$ ($1 \leq x < 12$) - for each month $f(x, y)$ increases by 5;
3) $f(1, y + 1) = f(1, y) + 60$ - for each year $f(x, y)$ increases by 60.

It is clear that the function is uniquely determined by these conditions; it can be specified, for example, with the following formula:

$$f(x, y) = 5x + 60(y - 1970) - 4.$$

It is easy to verify that $f(5, 2003) = 2001$; $f(6, 2003) = 2006$. Therefore, equation $f(x, y) = y$ has no solutions.

The correct solutions were sent by E. Orlok from Zhitomir, N. Ilyin from the village of Zakhar, Irkutsk region, M. Perelmuter from Kyiv and other readers.

From the above, it is clear that if we also introduced the following function: $f(k, x, y)$ is the number of the $k$th problem of the $x$th issue of the journal for the $y$th year ($1 \leq k \leq 5, 1 \leq x \leq 12, y \geq 1970$), then the equation $f(k, x, y) = y$ would be the only solution $k = 3, x = 5, y = 2003$ - in other words, if our system remains unchanged until then (still in each issue there will be five problems in mathematics), then the third problem in the “Kvata” task No. 5 for 2003 will have the number M2003. The general formula for $f(k, x, y)$ is also:

$$f(k, x, y) = k + 5x + 60(y - 1970) - 5.$$

For readers, please, more useful are the formulas given by the inverse function, which by the given number $n$ allows you to find the year $y$ and the journal number $x$ in which this problem was proposed.

To do this, it is convenient to use the following notations: $[a]$ is the integer part of the number $a$ (the largest integer not exceeding $a$) and $\{a\} = a - [a]$ is the fractional part of the number $a$.

Check that

$$x = \left[ 12 \left\{ \frac{n - 1}{60} \right\} \right] + 1, y = \left[ \frac{n - 1}{60} \right] + 1970.$$

M27

Prove that if $\frac{a}{b - c} + \frac{b}{c - a} + \frac{c}{a - b} = 0$ then $\frac{a}{(b - c)^2} + \frac{b}{(c - a)^2} + \frac{c}{(a - b)^2} = 0$.

This statement follows from this lie:

$$\left( \frac{a}{b - c} + \frac{b}{c - a} + \frac{c}{a - b} \right)\left( \frac{1}{b - c} + \frac{1}{c - a} + \frac{1}{a - b} \right) = \frac{a}{(b - c)^2} + \frac{b}{(c - a)^2} + \frac{c}{(a - b)^2}.$$

To prove it, it is enough to multiply the two sums on the left side of the lie, term by term, and take into account that the sum of three fractions

$$\frac{a}{b - c}\left( \frac{1}{c - a} + \frac{1}{a - b} \right) = \frac{ca - ab}{(a - b)(b - c)(c - a)},$$

$$\frac{b}{c - a}\left( \frac{1}{b - c} + \frac{1}{a - b} \right) = \frac{ab - bc}{(a - b)(b - c)(c - a)},$$

$$\frac{c}{a - b}\left( \frac{1}{b - c} + \frac{1}{c - a} \right) = \frac{bc - ca}{(a - b)(b - c)(c - a)}$$

equal to zero.

⟦folio 33⟧

This decision was sent by A. Shilitum from Tashkent. Less clear, but also correct solutions were sent by B. Paiss from Novomoskovsk, Tula region, and A. Izbitsky from Malorita, Brest region.

After reading such an artificial solution, of course, a reasonable question may arise: what is the agreement that the given expression must be multiplied by $\frac{1}{b-c} + \frac{1}{c-a} + \frac{1}{a-b}$? Is it possible to come up with a general method of calculation that allows solving such problems?

It would be more natural to solve this problem this way. Let's write these expressions as a ratio of two polynomials:

$$\frac{a}{b-c} + \frac{b}{c-a} + \frac{c}{a-b} = \frac{p(a,b,c)}{(a-b)(b-c)(c-a)},$$

$$\frac{a}{(b-c)^2} + \frac{b}{(c-a)^2} + \frac{c}{(a-b)^2} = \frac{q(a,b,c)}{(a-b)^2(b-c)^2(c-a)^2}$$

($p$ will be a third-degree polynomial, and $q$ will be a fifth-degree polynomial). We must prove that if $p(a,b,c) = 0$ then also $q(a,b,c) = 0$. It is natural to try to prove that the polynomial $q$ is divisible by the polynomial $p$, that is, to find a polynomial $r=r(a,b,c)$ such that $q=pr$ (you can prove a general theorem for polynomials in any number of variables: if $q$ is equal to zero for all those values of the variables for which $p$ is equal to zero, and at the same time the polynomial $p$ is continuous, that is, it cannot be factorized—and in this case it is—then $q$ must be divisible by $p$). You can divide polynomials in the usual way - with a “corner”, considering them polynomials in one variable $a$ (the coefficients of which include the letters $b$ and $c$); for example, $p$ would be written like this:

$$p(a,b,c) = -a^3 + p_1(b,c)a^2 + p_2(b,c)a + p_3(b,c).$$

As a result, we would, of course, get $q=pr$, where

$$r(a,b,c) = (a-b)(b-c)(c-a)\left(\frac{1}{a-b} + \frac{1}{b-c} + \frac{1}{c-a}\right) = -a^2 + ab + ac + bc - b^2 - c^2.$$

In this example, the implementation of this solution plan involves very difficult calculations (in the polynomial $q(a,b,c)$ even after reducing similar terms to the remaining 21 terms!), but we strongly advise readers to consider all the details of this solution, which applies to many others.

N. B. Vasiliev

M28

a) Of the 19 balls, 2 are radioactive. For any pile of balls, in one check you can find out whether it contains at least one radioactive ball or not (but you cannot find out how many such balls are in the pile). Prove that in 8 tests it is possible to isolate both radioactive balls.

b) Of the 11 balls, 2 are radioactive. Prove that in less than 7 checks it is impossible to guarantee the release of both radioactive balls.

Let's start with a similar, but simpler task. Let $n$ balls be given, one of which is radioactive; How many checks can it take to identify it? It is easy to indicate a method that allows you to select one of the $n=2^k$ balls in $k$ checks: first, we divide all the balls into two equal piles of $2^{k-1}$ balls in each, we check one of them and thereby determine which of them contains the radioactive ball, then we divide this pile of $2^{k-1}$ balls into halves again, etc. - with each check the number the balls are halved, and after $k$ checks we will find the radioactive ball. It is clear that if $n<2^k$, then $k$ checks are also sufficient. So, in order to isolate one radioactive ball from $n$, it is enough to perform $f_1(n)$ tests, where $f_1(n)$ is the smallest integer $k$ for which $n\leq 2^k$ (in other words, $f_1(n)$ is the smallest integer greater than or equal to $\log_2 n$). Below we will see that less than the number of checks completed is not enough.

Now let's move directly to solving our problem. Here it was no longer possible to obtain an exact result immediately for any member of the remaining 21 members!, but we strongly advise readers to consider all the details of this solution, which applies to many others.

N. B. Vasiliev

⟦folio 34⟧

Fig. 1. This figure presents a method that allows you to select 2 radioactive balls from 7 in 5 checks. We consider that the balls are numbered 1, 2, ..., 7, and in each cell we write a bunch of balls that are subject to verification (sometimes the pile consists of one ball). For example, the first one to check is a pile of three balls {1, 2, 3}.
Each check has two possible outcomes: “there is radioactivity” - then you need to follow the red arrow, and “there is no radioactivity” - then you need to follow the black arrow. If the cell is shaded, then no further checks are needed. For each path descending along the arrows from top to bottom, as a result of all the checks performed along this path, it is possible to determine which pair of balls is radioactive (it is indicated under the lowest arrow). Make sure of it!

but we are interested in how many checks can be used to identify radioactive balls for sure, regardless of any option for their location, even the most unfavorable one for us. In the same way, checking the balls one after another, you can select two balls from 4 in 3 checks, from 5 - in 4, from 6 - in 5, from 7 - in 6, etc. However, for $n=7$ you can bypass the fifth one with checks. Before reading the solution further, try to prove this, that is, find an appropriate way to lower radioactive balls. However, this method (there are several of them) is indicated in figure 1.

This figure helps us understand what we mean by the words “method of dropping balls”: to specify a method, you need to indicate the pile of balls that is checked first, and also indicate which pile to check after each of the possible outcomes of the next test for radioactivity; in other words, you need to measure a diagram from straight

mogol cells and arrows - the same as on figure 1, only, if necessary, with a different number of $k$ checks - and write some numbers of balls in each cell.

Now we will try to answer two related questions: how to find a way to find two balls among $n$, consisting of $k$ checks, if such a method exists; if it does not exist, then how to prove it?

In principle, for any specific $n$ and $k$ these questions can be solved by “exhaustive search”: try one after another all possible ways to fill the cells of the diagram corresponding to $k$ checks with subsets of $n$ balls (after all, there are a finite number of such methods!) and for each of these methods check whether it allows you to isolate radioactive balls or not (that is, whether there will be a different assumption: which pair balls are radioactive - match different paths using the arrows from top to bottom). But the number of such methods, even with small $n$ and $k$, is so great that it is practically impossible to do a “full search” even with the help of a computer (for example, with $n=11$ and $k=7$ you can fill the cells of the diagram with piles

⟦folio 35⟧

more than $10^{400}$ different ways!). We will now show how this search can be greatly reduced.

Let's return again to figure 1. From the lowest row of cells, corresponding to the last, fifth check, $2^5=32$ arrows extend. In general, for $k$ checks, there will be $2^k$. If the ponska method, written on the diagram, guarantees the isolation of radioactive balls, then each of these arrows corresponds to only one of the possible answer options: which two balls are radioactive (but, perhaps, different arrows correspond to the same option). Therefore, the number of different possible answer options depends on no more than the number of the arrow, that is, no more than $2^k$.

Let's formulate this main message like this:

If the number of possible options is greater than $2^k$, then there is no way to select one of these options in $k$ checks.

The same can be said like this:

If there is a way that allows you to select one option from $N$ possible in $k$ checks, then $N \leq 2^k$.

(The last inequality can also be written as follows: $k \geq f_1(N)$.)

Of course, this rule applies to any problem where you need to select one option from $N$ based on the results of several checks; the only important thing is that each check has two possible initial ones: “there is radioactivity” and “there is no radioactivity”).

In particular, it follows from this rule that it is impossible to select one and 同一 radioactive ball from $n$ in less than $f_1(n)$ checks: if $f_1(n) = k$, then $2^{k-1} < n$, and there are $n$ different options in this problem (the 1st ball is radioactive, the 2nd ball is radioactive, ..., the $n$th is radioactive ball).

Let's return again to the problem where there are two radioactive balls. How many different options are there? At figure 1, where we choose 2 balls from 7, the number of options is 21. In general, there are $C_n^2 = \frac{n(n-1)}{2}$ options to choose 2 balls from $n$. From our basic rule, printed above on a pink background, it follows that if in $k$ checks it is possible to select 2 balls from $n$, then $\frac{n(n-1)}{2} \leq 2^k$.

Conditions denote the smallest number of checks required to select 2 balls from $n$, through $f_2(n)$. Then the last inequality can be written as follows:

$$f_2(n) \geq f_1\left(\frac{n(n-1)}{2}\right).$$

It is clear from the table that for some $n$ (for example, for $n=6$, $n=8$) a strict inequality is possible here. Indeed, in order for $k$ checks to be able to find 2 radioactive balls among $n$, it is not enough that inequality $\frac{n(n-1)}{2} \leq 2^k$ be satisfied. It is also necessary that such options for which the first check should result in “+” (natural radioactivity) should be no more than $2^{k-1}$ and those for which the result should be “-” (no radioactivity) should also be no more than $2^{k-1}$ - because otherwise, according to the basic rule, we will not be able to choose one of these options during the $k-1$ check! In the same way, each of the outcomes “++” (1st check “+”, 2nd check “+”), “+—”, “+—”, “—” should correspond to no more than $2^{k-2}$ options, etc.

We will return to solving this problem in the next issue of the journal.

A. N. Vilenkin

⟦folio 37⟧

Fig. 3.

where $n_{жс}$ is the refractive index of a light ray when passing from liquid to glass.

With total internal reflection of light at the glass-liquid interface $\alpha = 90^\circ$, and therefore $\sin \beta_0 = n_{жс}$, where $\beta_0$ is the angle of incidence of the beam at which total internal reflection is observed. Similarly, for the total internal reflection of light at the glass-air interface, we can write $\sin \delta_0 = \frac{1}{n_c}$, where $n_c$ is the refractive index of glass. From these two formulas, taking into account that $n_{жс} = \frac{n_{жс}}{n_c}$, we find

$$n_{жc} = \frac{\sin \beta_0}{\sin \delta_0}.$$

Fig. 4.

Now we need to determine the refractive index of a light beam so that it can only be observed by correcting the total internal reflection at the glass-liquid interface. This we will define the angle $\beta_0$. Then we define the angle $\delta_0$ in exactly the same way. After this, calculating the refractive index of a light beam is not difficult. The fact that the beam does not undergo refraction at the spherical boundary of glass and air will help to carry out the experiments, since it falls perpendicular to the surface of the glass. This makes it easy to determine the direction of the beam incident on the flat boundary of the plate.

F37

In two vertical cylinders with cross-sectional areas $S_1$ and $S_2$ there are two irreversible pistons connected by a thin irreversible thread of length $l$ (Fig. 4). The space between the pistons is filled with water. Find the tension in the thread if the ends of the vessels are open to the atmosphere. Density of water $ρ$.

If the fluid pressure on a large piston (with an area $S_1$) is $p$, and the atmospheric pressure is $p_0$, then the pressure force $F_1 = S_1p$ acts upward on the piston, and the tension force $T$ of the thread and the atmospheric pressure force $F'_1 = p_0 \cdot S_1$ acts downward on the piston. Since the piston is in equilibrium, then

$$S_1p = S_1p_0 + T.$$

A similar equation can be drawn up for the lower piston: the thread tension force $T$ and the atmospheric pressure force $F'_2 = p_0S_2$ act upward on it, and the water pressure force $F_1 = p'S_2$ acts downwards on it. Moreover, the pressure $p'$ of water on the lower piston is $\rho gl$ greater than on the upper one. Since the piston is in equilibrium, then

$$T + p_0S_2 = (p + \rho gl)S_2.$$

Solving both equations together, we find

$$T = \rho gl \frac{S_1S_2}{S_1 - S_2}.$$

⟦folio 38⟧

We usually check the answer by using it at the extreme values ​​of the parameters. We will assume that $S_2 \rightarrow S_1$. In this case $T \rightarrow \infty$. This is understandable. The entire system maintains balance thanks to the water pressure on the stake with an area of ​​$S_1 - S_2$ on the upper piston. If $S_1 \rightarrow S_2$, then the pressure on this stake should tend to infinity. In this case, the tension force of the thread should also tend to infinity.

For $S_1 = S_2$ we get that $T$ is infinite. However, this is no longer true. Such a limiting transition is impossible. When solving the problem, we assumed that the system is in equilibrium. However, at $S_1 = S_2$ equilibrium is impossible and the system of pistons will fall equal to the acceleration of free fall $g$. The thread tension in this case should be zero. This example shows how carefully one must approach passages to the limit in physics. It is necessary to ensure that this phenomenon does not become completely different.

This solution was sent by N. Fedin from Omsk, tenth-class student M. Fedorov from Moscow, A. Ratzozin from Izhevsk.

An interesting solution was proposed by A. Zhukov from Kirovsk, Donetsk region. He used the method of virtual change. Although such a discussion about this method requires a special long article, the solution will be clear anyway.

Let the thread decrease by $\Delta l$, and the upper piston moves to $\Delta l_1$, and the lower one to $\Delta l_2$. Since the volume of water between the pistons has not changed, both pistons should move in the same direction (lower), and in such a way that

$$\Delta l_1 S_1 = \Delta l_2 S_2 \text{ и } \Delta l_2 - \Delta l_1 = \Delta l$$
($\Delta l_2 > \Delta l_1$).

Solving these equations together, we find

$$\Delta l_1 = \Delta l \frac{S_2}{S_1 - S_2} \text{ и } \Delta l_2 = \Delta l \frac{S_1}{S_1 - S_2}.$$

The change in the potential energy of the system when moving the volume of water $\rho S_1 \Delta l_1$ (or $\rho S_2 \Delta l_2$) by $l$ must be equal to the work done by the tension force of the thread. Therefore we can write,

$$p + \Delta p = p + \rho gh,$$

⟦folio 39⟧

where $h$ is the difference in fluid levels in the elbows (Fig. 5). From this equation we find that $h = \frac{\Delta p}{\rho g}$. We see that $h$ does not depend on the areas of the pressure gauge elbows. This means that the accuracy of measurements when connecting a vessel to both a wide and a narrow elbow is the same.

The correct solution was sent by A. Zhukov and the memoirs of S. Pastmukhov from Sverdlovsk.

F39

A planet of radius $r$ and mass $M$ is surrounded by an equally dense atmosphere consisting of gas with molecular weight $\mu$. What is the temperature of the atmosphere on the surface of the planet if the height of the atmosphere is $h$?

Let us write the equation of the gas state for the volume of gas $V$ with mass $m$ (Mendeleev-Clapeyron equation):

$$PV = \frac{m}{\mu} RT;$$

$P$ is pressure, $V$ is gas volume, $R$ is gas constant and $T$ is temperature. Since $\frac{m}{V} = \rho$, where $\rho$ is the gas density, we can rewrite this equation in the form $P = \frac{\rho}{\mu} RT$.

Hence $T = \frac{P\mu}{\rho R}$.

It is clear that in order to find the temperature on the surface of a planet, we need to find the pressure on its surface. If $\rho = \text{const}$, then $P = \rho gh$, where $g$ is the acceleration of free pressure on a given planet. Let's find him.

For a body of mass $m$ located on the surface of the planet, the force of attraction is equal to $mg$. On the other hand, according to the law of universal gravitation, it is equal to $\gamma \frac{mM}{r^2}$. Therefore we can write that $mg = \gamma \frac{mM}{r^2}$.

Hence $g = \gamma \frac{M}{r^2}$ and $P = \rho \gamma \frac{M}{r^2} h$.

Substituting this expression for $P$ into the equation for temperature, we obtain

$$T = \frac{\gamma M\mu h}{r^2 R}.$$

 The correct solution to the problem was sent by V. Malkov from Orsha and A. Proskuryakov from Moscow.

F40

At what potential difference between the electrodes does a neon lamp light up if the energy of neon is $I = 21,5$ eV, and the average distance between two successive collisions of the electrode with gas atoms is $l = 0,4$ mm? The electrodes are in the form of large flat plates located at a distance of $d = 3$ mm from each other.

If the potential difference between the electrodes is $U$, then the direction of the electric field between them is $E = \frac{U}{d}$. In this field, the electron is acted upon by a force $F = E \cdot e$ (e is the charge of the electron), imparting to it an acceleration $a = \frac{F}{m} = \frac{Ee}{m} = \frac{Ue}{dm}$, where $m$ is the mass of the electrode.

When an electron collides with an atom of a gas, it transfers its energy to it and is abandoned (we assume that the collision is inelastic). The mass of the atom is greater than the mass of the electrode. Therefore, during a collision, an atom of a gas is transferred energy $\frac{mv^2}{2}$, acquired by an electron between its successive stolnovs. This energy must be equal to the gas nomization energy $I$:

$$\frac{mv^2}{2} = I.$$

Let us now find the speed acquired by the electron. If the flare time is $t$, then we can write that $v = a\tau = \frac{Ue}{md} t$ and $l = \frac{a\tau^2}{2} = \frac{Ue\tau^2}{2md}$. From these equations we find that

$$v = \sqrt{\frac{2Uel}{md}}.$$

Substituting this expression for $v$ equation (*), we obtain

$$\frac{Uel}{d} = I.$$

Hence $U = \frac{Id}{el} \approx 160\theta$.
