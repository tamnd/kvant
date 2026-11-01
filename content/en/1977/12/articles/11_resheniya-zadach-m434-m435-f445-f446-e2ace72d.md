---
id: 1977-12-resheniya-zadach-m434-m435-f445-f446-e2ace72d
issue: kvant_1977_12
year: 1977
number: "12"
title: Solutions to problems M434, M435; F445, F446
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 41
page_labels: 36-39
tag: M28Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8d34d03cf2e04b452f8fa06175d5f5959397aa8d3819f5e1282a39378a077007
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/11_resheniya-zadach-m434-m435-f445-f446-e2ace72d.md
source_content_sha256: d9df1c3ca53b0b8d0a8a16366b92543a5f31096463156abbd9240861d05fd5cb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Problem solutions

M434, M435; F445, F446

M434. Number $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \dots + \frac{2^n}{n}$
represented as a non-Socratic fraction $\frac{p_n}{q_n}$.

a) Prove that $p_n$ is a greater number.
b) Prove that if $n > 3$ then $p_n$ is divisible by 8.
c) Prove that for any natural number $k$ one can indicate which $n$, that the numbers $p_n, p_{n+1}, \dots, p_{n+2}, \dots$ are divisible by $2^k$.

a), b) If the non-Socratic fraction $\frac{p}{q}$ is the sum of several non-Socratic fractions, the numerator of each of which is divisible by $2^k$, then $p$ is also divisible by $2^k$. To solve problem a) it remains to note that the numerators of the fractions $\frac{2}{1}, \frac{2^2}{2}, \frac{2^3}{3}, \dots$ remain even after reduction (since for any natural number $m$ the inequality $2^{m-1} \geq m$ is valid). To solve problem b) it would be enough to have inequality $2^{m-3} \geq m$. This inequality, however, is only valid starting from $m = 6$. Therefore, let us check that the numerators of the sums $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \frac{2^4}{4}$ and $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \frac{2^4}{4} + \frac{2^5}{5}$ after reduction will be divisible by 8. These sums are equal to $\frac{32}{3}$ and $\frac{256}{15}$, respectively.

c) Consider the function $L_n(x) = \frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n}$. Let us show that the polynomial $L_n(2x - x^2) - 2L_n(x) = f(x)$ has the form:

$$f(x) = x^{n+1} \cdot \left( \frac{a_0}{n+1} + \frac{a_1}{n+2} x + \dots + \frac{a_{n-1}}{2n} x^{n-1} \right),$$

where $a_0, a_1, \dots, a_{n-1}$ are integers. To do this, it is enough to show that the polynomial $f'(x)$ has the form:

$$f'(x) = x^n \left( a_0 + a_1 x + \dots + a_{n-1} x^{n-1} \right).$$

Note that $L_n'(x) = 1 + x + x^2 + \dots + x^{n-1} = \frac{1-x^n}{1-x}$. That's why,

$$f'(x) = L_n'(2x - x^2) \cdot (2 - 2x) - 2L_n'(x) =$$

$$= \frac{1 - (2x - x^2)^n}{1 - 2x + x^2} \cdot (2 - 2x) - \frac{2(1 - x^n)}{1 - x} =$$

$$= 2 \cdot \frac{x^n - x^n(2 - x)^n}{1 - x} = x^n \cdot \frac{2(1 - (2 - x)^n)}{1 - x}$$

And

$$1 - (2 - x)^n = (1 - (2 - x))(1 + (2 - x) + (2 - x)^2 + \dots +$$

$$+ (2 - x)^{n-1}) = (x - 1)(1 + (2 - x) + (2 - x)^2 + \dots +$$

$$+ (2 - x)^{n-1}).$$

Since $f(2) = L_n(0) - 2L_n(2) = -2L_n(2)$, then, putting $x = 2$ in equality (*), we get

$$L_n(2) = -2^n \left( \frac{a_0}{n+1} + \frac{2a_1}{n+2} + \dots + \frac{2^{n-1}a_{n-1}}{2n} \right).$$

From the inequality $n < 2^{\frac{n+1}{2}}$, valid for any number $n$, it follows that all denominators in the right

⟦folio 37⟧

M435. In the table of sizes $m \times n$ real numbers are written, in each cell there is a number. Each column underlines the $k$ largest numbers ($k \leq m$), and each row underlines the $l$ largest numbers ($l \leq n$). Let us prove that at least $kl$ numbers are underlined twice.

$$k = 1; \quad l = 2.$$

Fig. 1.

F445. A capacitor with a capacitance of $C = 0,04$ uF using a key $K$ is periodically charged with a frequency of $v = 50$ times per second from a source with e. d.s. % = 100 V and internal resistance $r = 5$ Ohm and discharges through resistance $R = 1$ kOhm (Fig. 2). Determine the power released in the outdoor area $R$, and k. n. any device. Assume that the closing time of the key capacitor is sufficient for the capacitor to be fully charged (position $I$) and completely discharged (position $II$).

We will solve the induction problem in a slightly more general formulation, assuming that each column emphasizes at least $k$ largest numbers, and each row emphasizes at least $l$ largest numbers. We carry out induction on $m+n$.

For $m=n=k=l=1$ the statement is obvious. Let us have a table with dimensions $m \times n$. Reduce the problem to table $m \times (n-1)$ or $(m-1) \times n$. If in the table all underlined numbers are underlined twice, then their number is at least $kn$. Otherwise, the numbers are underlined once, we choose the largest number $A$. The number $A$ is either one of the largest in its number, or one of the largest in its number. Let's assume that $A$ is one of the largest in its size. Then, since $A$ is not one of the largest in its number and $A$ is the largest average of once underlined numbers, all the largest numbers in one line $A$ are underlined (by line!), underlined twice (see Fig. 1). By removing this line from our table, we get a table $(m-1) \times n$, in which at least $l$ of the largest numbers in each number are underlined. And at least $k-1$ numbers in each column. The assumption of induction is that in this smaller table at least $(k-1) l$ numbers are underlined twice. These same numbers are underlined twice in the large table $m \times n$, in which, in addition, at least $l$ numbers in the discarded line are double underlined. So in total, at least $(k-1) l+l=kl$ numbers are underlined twice in the original table, which is what was stated in the problem.

S. Konyazin

During the discharge of a capacitor, all the energy contained in the capacitor is released at resistance $R$. This energy

$$W = \frac{C \mathcal{E}^2}{2}.$$

In one second, the capacitor discharges 50 times (key switch particle $v=50$ 1/c). Therefore, the average power $P_{cp}$ allocated in the load $R$ is equal to

$$P_{cp} = W v = \frac{C \mathcal{E}^2}{2} v = 10^{-2} B T.$$

In order for the efficiency coefficient $\eta$ of this device, it is necessary to divide the energy $W$ released at the resistance $R$ during the discharge of the capacitor by the work $A$ performed by the current source during the charging of the capacitor. Because

$$A = q \mathcal{E} = C \mathcal{E} \mathcal{E} = C \mathcal{E}^2,$$

⟦folio 38⟧

$$\eta = \frac{W}{A} = \frac{C \mathcal{E}^2}{C \mathcal{E}^2} = \frac{1}{2},$$

that is, the efficiency does not depend on the resistance values ​​$R$ and $r$.

If there were no capacitor, and a source with e. d.s. $\mathcal{E}$ and internal resistance $r$ would be non-presidentially connected to load $R$, then the efficiency of the circuit would be equal

$$\eta' = \frac{I^2 R}{I^2 (R + r)} = \frac{R}{R + r} = 0,995,$$

which is significantly more than in our case.

◆

Let's direct the coordinate axis $X$ to the right, and the origin of coordinates is connected with the position of the body at the initial moment (Fig. 4). Two forces act on the body as the relative conveyor belt passes through it. One of them - the elastic force of the spring - is proportional to the coordinate $x$ of the body and is directed in the direction opposite to its displacement:

$$F_{\text{упр}} = -kx,$$

and the other - the power of transorganization - is constant:

$$F_{\text{тр}} = \mu M |\vec{g}|,$$

where $\mu$ is the friction coefficient of the body on the belt. This means that, like a conventional horizontal spring magnet, the body should perform free harmonious vibrations. True, these oscillations occur relative to the equilibrium position - point $O'$ with coordinate $x_0$, where the sum of the projections of all forces is equal to zero:

$$F_{\text{упр}} + F_{\text{тр}} = 0,$$ or $-kx_0 + \mu M |\vec{g}| = 0,$

where

$$x_0 = \frac{\mu M |\vec{g}|}{k};$$

Let us show that this is indeed the case. To do this, it is convenient to switch to another coordinate system, the origin of which is at point $O'$, and the axis $X'$ is directed to the right (see Fig. 4). Let us write down the equation of body motion in projections onto the chosen direction:

$$Ma = F_{\text{упр}} + F_{\text{тр}}.$$

Here $F_{\text{упр}} = -k(x_0 + x') = -k \left( \frac{\mu M |\vec{g}|}{k} + x' \right)$ and $F_{\text{тр}} = \mu M |\vec{g}|.$

Posetom

$$Ma = -k \left( \frac{\mu M |\vec{g}|}{k} + x' \right) + \mu M |\vec{g}|,$$

or

$$Ma = -kx'.$$

(Note that we encounter the same case when solving problems on oscillations of a vertical spring magnet (Fig. 5). Here the role of the constant friction force is also played by the constant force of gravity.) We have obtained the equation of motion of a body performing free harmonic oscillations. These vibrations occur according to the law

$$x' = x_m' \cos(\omega_0 t + \varphi_0).$$

Cyclic oscillation frequency

$$\omega_0 = \sqrt{\frac{k}{M}}.$$

The amplitude $x_m'$ can be found from energy considerations:

⟦folio 39⟧

at the initial moment, when the speed of the body is zero, its displacement is $x' = -x_0$. Therefore, the amplitude of oscillations

$$x'_m = x_0 = \frac{\mu M |\vec{g}|}{k}.$$

The initial phase $\varphi_0$ is determined by the initial conditions: at $t=0$ $x' = -x_0$, whence $\varphi_0 = \pi$.

So,

$$x' = x_0 \cos(\omega_0 t + \varphi_0) = -\frac{\mu M |\vec{g}|}{k} \cos \sqrt{\frac{k}{M}} t.$$

In the coordinate system $OX$, the coordinates of the body depending on time will be as follows:

$$x = x_0 + x' = x_0 (1 - \cos \omega_0 t) =$$

$$= \frac{\mu M |\vec{g}|}{k} \left( 1 - \cos \sqrt{\frac{k}{M}} t \right),$$

and the projections of velocity and acceleration, respectively, are

$$v = x_0 \omega_0 \sin \omega_0 t = v_m \sin \omega_0 t = \mu |\vec{g}| \sqrt{\frac{M}{k}} \sin \sqrt{\frac{k}{M}} t$$

And

$$a = x_0 \omega_0^2 \cos \omega_0 t = a_m \cos \omega_0 t = \mu |\vec{g}| \cos \sqrt{\frac{k}{M}} t.$$

However, all our reasoning is valid only if the amplitude $v_m$ of the body velocity does not exceed the speed $v_0$ of the movement of the conveyor belt. Therefore, only on condition

$$v_m \leq v_0,$$ or $\mu |\vec{g}| \sqrt{\frac{M}{k}} \leq v_0$

the friction force acting on the body is constant. The dependence graphs $x(t), v(t)$ and $a(t)$ for this case are shown in figure 6.

And what will happen to the body if, even before passing through the mixed equilibrium position (point $O'$), the abscylotic value of its velocity becomes equal to $v_0$? Obviously, at this moment the body is “grabbed” by the tape, and the friction force decreases to a value of $|\vec{F}_{\text{Tp}}| = |kx| < \mu M |\vec{g}|$. Due to this, the body moves uniformly for some time at the speed of the belt until it reaches point $O'$ with coordinate $x_0 = \frac{\mu M |\vec{g}|}{k}$. At this moment, the friction force becomes equal to the maximum value $\mu M |\vec{g}|$ and with further movement of the body it will remain constant.

Consequently, starting from this moment, the body, as in the first case, will perform harmonic oscillations with the same frequency $\omega_0 = \sqrt{\frac{k}{M}}$, but with a different amplitude $x_m$.

Since the amplitude of velocity oscillations is equal to $v_0$ (with such a speed the body passes the equilibrium position), the amplitude of coordinate oscillations

$$x_m = \frac{v_0}{\omega_0} = v_0 \sqrt{\frac{M}{k}}.$$

Similarly, the amplitude of acceleration oscillations

$$a_m = v_0 \omega_0 = v_0 \sqrt{\frac{k}{M}}.$$

Correspondence plots of $x(t), v(t)$ and $a(t)$ are shown in figure 7.

I. Slobodetsky
