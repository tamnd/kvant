---
id: 1972-5-rabbot-trigonometricheskie-funktsii-784fa2df
issue: kvant_1972_5
year: 1972
number: "5"
title: Trigonometric functions
authors:
  - Раббот Ж. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 44
page_labels: 36-42
tag: 3T64
lang: en
source: kvant_digital
extraction: vision
content_sha256: 859cfc20868e50fa3209892c72a5667b9f1a1c907da7c2414545452803da5035
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/10_rabbot-trigonometricheskie-funktsii-784fa2df.md
source_content_sha256: 03dfbcd899b8451daac0529c7b88193be1e8f98d27d6b78ff9c91068d3d45ffe
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

APPLICANT PRACTICUM

Trionometric function, encryption for applicants to universities on entrance copies.

1. Trinometric number function

What is sin 1? What sign does ctg 21 have? Such questions often perplex many applicants.

We want to define a trionometric function on the set of all real numbers. To do this, consider a circle of unit radius on the coordinate plane with a center at the origin of coordinates (“trionometric circle”).

Let us be given an arbitrary number $t_0$. Let us plot on the circumference of the trionometric circle from the point $E(1; 0)$ (Fig. 1) an arc of length $|t_0|$ in the positive direction (counterclockwise) if $t_0 \geq 0$, and in the negative direction (clockwise) if $t_0 < 0$ (unit of length of the service trionometric circle). In this case, we will obtain a point $P_{t_0}$ on the circle with coordinates $(x_{t_0}, y_{t_0})$. The abscissa $x_{t_0}$ of the point $P_{t_0}$ is called the cosine of the number $t_0$, and the ordinate $y_{t_0}$ of this point is the sine of the number $t_0$:

$$\cos t_0 = x_{t_0}; \sin t_0 = y_{t_0}.$$

The most subtle point in our definition is the process of opening on a circle of given length. It can be visualized as winding (without stretching) a segment around a circle.

So, to get, say, the sin of the number $t_0$, we first matched (by winding) the number $t_0$ to the definition of the point $P_{t_0}$ on the circle, and then took the ordinate of this point:

$$t_0 \rightarrow P_{t_0}(x_{t_0}; y_{t_0}) \rightarrow y_{t_0} = \sin t_0.$$

Using our definition, we can study the properties of the function $y = \sin t$. Let's show you how it's done.

⟦folio 37⟧

a) Find the roots of the equation sin t=0. Let the number $t$ be such that sin t=0. This means that the ordinata of the point $P_t$ corresponding to the number $t$ is equal to zero. There are two such points on the unit circle: $E$ and $E'$ (see Fig. 1). They will be obtained by laying aside each other, the lengths of which are multiples of the length of the semicircle.

Noticing now that half the length of the unit circle is $\pi$, we obtain that the equality sin t=0 is equivalent to the equality $t=\pi k$, where $k=0, \pm 1, \pm 2, \dots$.

6) If the numbers $t_1$ and $t_2$ differ from each other by a multiple of 2π (that is, by an integer number of circumference lengths), then the points of the unit circle corresponding to the numbers $t_1$ and $t_2$ coincide. This means that the equality $t_1-t_2=2\pi k$ ($k=0, \pm 1, \pm 2, \dots$) implies the equality sin $t_1=\sin t_2$, that is, the number 2π is the period of the function $y=\sin t$.

Let us prove that the number 2π is the smallest positive period of the function $y=\sin t$. Let us assume the opposite: let $0<a<2\pi$ and

$$\sin (t+a)=\sin t$$

(1)

for any $t$ (that is, there was a positive number $a$, less than 2π, which is also a period).

Let $t=0$. Then from (1) we obtain that sin a=0. But in the interval $0<a<2\pi$ there is only the number $\pi$, the sine of which is zero, therefore $a=\pi$. Now substituting $t=\frac{\pi}{2}$ into (1), we get that $1=-1\left(\sin \frac{\pi}{2}=1-\text{это ordinata точки } A\text{ на рисунке 1}, a \sin \left(\pi+\frac{\pi}{2}\right)=-1-\text{это ordinata точки } A'\right)$. We have come to disagreement. So, 2π is the smallest positive period of the function $y=\sin t$.

The periodicity property we have established allows us to further study the properties of the sine only within one period, for example, at $0\leq t\leq 2\pi$.

Due to the proven periodicity of the sinus, replacement follows. In the Kochetkovs’ textbook “Algebra and Elementary Functions” (§ 207), it is implied, but not explicitly stated, that for a periodic function, along with the number $x$, all numbers $x+nT$ ($n$-any integer, $T$-period) must also be included in the domain of definition. Meanwhile, this is very important: sometimes it is possible to prove the periodicity of functions by obtaining precisely this property. Let us show, for example, that the function $y=\cos \frac{1}{x}$ is non-periodic. Let us assume that the $T$-period of this function. At $x=-T$ our function is defined, which means it must be defined at $x=-T+T=0$, but at $x=0$ the referenced $\frac{1}{x}$ does not exist: we come to a contradiction.

In a completely similar way, we can study the properties of the function $y=\cos t$. It seems quite clear to you how to define the function $y=\tg t$, $y=\ctg t$ (numeric argument) and explore their properties.

Battles

1. Find the smallest positive periods of the functions:

a) $y=\sin 3x$; 6) $y=\tg 2x-\sin 3x$; c) $y=2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right)$; d) $y=\sin^2 x$; e) $y=\sin(\cos x)$; e) $y=\cos(\sin x)$.

Example 1. Prove that the function $y=\sin x^2$ is non-periodic.

Solved and e. Assume that this function is periodic. Let us find the zero of this function (that is, the values ​​of $x$ at which it becomes zero): sin $x^2=0$, whence $x^2=\pi k$ ($k=0, 1, 2, \dots$), $x=\pm \sqrt{\pi k}$. If $k=0$, then $x_0=0$; if $k=1$, then $x_1=\sqrt{\pi}$. From the assumption made about

⟦folio 38⟧

The periodicity of the function $y=\sin x^2$ implies that there are also infinite pairs of its neighboring zeros (obtained from $x_0$ and $x_1$ with dws to the right by an integer number of periods), the difference between which is equal to $x_1-x_0=\sqrt{\pi}$. But for any $k>1$ we have

$$|x_{k+1}-x_k|=|V(k+1)\pi-Vk\pi|=\frac{\pi}{\sqrt{(k+1)\pi}+\sqrt{k\pi}}<\sqrt{\pi}.$$

since $V(k+1)\pi+Vk\pi>\sqrt{\pi}$. The resulting contradiction proves that the functions $y=\sin x^2$ are non-periodic.

Exercises

2. Prove that the functions are nonperiodic: a) $y=\sin \sqrt{x}$; b) $y=\cos x\cos \sqrt{2}x$.
3. Specify the signs of the following numbers:
a) $\sin 2$; 6) $\cos 3,1$; b) $tg 10$; r) $\sin \pi^2$; d) $tg(\cos 2)$.
4. It is given that $\cos^2 t+p\cos t+q>0$ for all real values ​​of $t$. Does it follow that $x^2+px+q>0$ for all real values ​​of $x$?

It is not difficult to establish a simple one between the definitions of the trionometric functions of the (generalized) angle and the numerical argument. Let's position the angle so that its initial side goes along the $Ox$ (Fig. 2) axis. Then the sine of an angle is by definition equal to the ordinate of the point at which the end side of the angle intersects the unit circle.

If an angle contains $\alpha$ radians, then the end side of the angle will intersect the unit circle at the end of the arc corresponding to the number $\alpha$ when wound. Therefore (compare figure 1 and 2)

Fig. 2.

It is this property that is accepted in the school textbook as the definition of the sine of a number (and similarly for other functions: cosine, tangent, cotangent).

2. Converting Trionometric Expressions

When solving various problems, it is often necessary to carry out similar transformations and use trionometric formulas. It must be remembered that some formulas change the scope of definition; in addition, it is necessary to clarify the reversibility of all transitions.

Example 2. (MAI, 1970). Prove Christmas:

$$\frac{\left(\cos \alpha+\cos \frac{\alpha}{2}\right)^2-\left(\sin \alpha+\sin \frac{\alpha}{2}\right)^2}{\sin 2\alpha-\sin \alpha}=\mathrm{ctg} \frac{\alpha}{4}.$$

Solution e. First of all, let’s find the ODZ. The left side of (2) is defined when $\sin 2\alpha-\sin \alpha\neq 0$, that is, when $2\sin \alpha\cos \alpha-\sin \alpha\neq 0$, whence $\sin \alpha\neq 0$, $\cos \alpha\neq \frac{1}{2}$; finally $\alpha\neq \pi n$, $\alpha\neq \pm \frac{\pi}{3}+2\pi k^*)$. Right

*) Here and further, unless otherwise stated, it follows that the parameters $n, k, l$, etc. accept all integer values.

⟦folio 39⟧

part (2) exists for $\sin \frac{\alpha}{4} \neq 0$, that is, for $\alpha \neq 4\pi l$. So, the ODZ was found: $\alpha \neq n\pi, \alpha \neq \pm \frac{\pi}{3} + 2\pi k$.

Let us denote the left side of the identity by $M$. Then

$$M = \frac{\cos^2\alpha + 2\cos\alpha \cos \frac{\alpha}{2} + \cos^2 \frac{\alpha}{2} - \sin^2\alpha - 2\sin\alpha \sin \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{(\cos^2\alpha - \sin^2\alpha) + \left(\cos^2 \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}\right) + 2\left(\cos\alpha \cos \frac{\alpha}{2} - \sin\alpha \sin \frac{\alpha}{2}\right)}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{\cos 2\alpha + \cos\alpha + 2\cos \frac{3\alpha}{2}}{\sin 2\alpha - \sin\alpha} = \frac{2\cos \frac{\alpha}{2} \cos \frac{3\alpha}{2} + 2\cos \frac{3\alpha}{2}}{2\sin \frac{\alpha}{2} \cos \frac{3\alpha}{2}} =$$

$$= \frac{\cos \frac{\alpha}{2} + 1}{\sin \frac{\alpha}{2}} = \frac{2\cos^2 \frac{\alpha}{4}}{2\sin \frac{\alpha}{4} \cos \frac{\alpha}{4}} = \text{ctg} \frac{\alpha}{4}.$$

So, in ODZ $M = \text{ctg} \frac{\alpha}{4}$.

Example 3. Prove that if $\text{ctg}(\alpha + \beta) = 0$, then

$$\sin(\alpha + 2\beta) = \sin\alpha.$$

(3)

Solution. Note that the condition $\text{ctg}(\alpha + \beta) = 0$ is equivalent to the condition

$$\cos(\alpha + \beta) = 0.$$

(4)

Let us now consider the difference between the right and left sides of (3): $\sin(\alpha + 2\beta) - \sin\alpha = 2\sin\beta \cos(\alpha + \beta)$, from where, using (4), we obtain the required.

Exercises

5. (MAI, 1970). Prove the identities:
a) $(\sin\alpha - \cos\alpha)^2 + (\cos\alpha - \sec\alpha)^2 = 4\text{ctg}^2 2\alpha + 1$;
b) $\sin\alpha + \text{ctg}\alpha - \text{ctg}\alpha \cos\alpha - 1 = \frac{2\cos\left(\frac{\pi}{4} + \alpha\right)\sin\left(\frac{\alpha}{2} - \frac{\pi}{4}\right)}{\cos \frac{\alpha}{4}}.$

6. Prove the identities:
a) (MISP, 1969). $\frac{1}{1 + \text{tg}\alpha \text{tg}2\alpha} = \sin\left(\frac{\pi}{2} + 2\alpha\right)$; b) (MEPhI). $\cos^2\varphi + \cos^2(\alpha + \varphi) - 2\cos\alpha \cos\varphi \cos(\alpha + \varphi) = \sin^2\alpha$.
7. (Faculty of Physics, Moscow State University).
a) Prove that if $5\sin\beta = \sin(2\alpha + \beta)$ then $\frac{\text{ctg}(\alpha + \beta)}{\text{tg}\alpha} = \frac{3}{2}$;
b) Prove that if $\cos x = \cos a \cos b$, $x \pm a \neq \pi(2k + 1)$, $b \neq \pi(2k + 1)$, then $1 + \text{tg}\frac{x + a}{2} \text{tg}\frac{x - a}{2} = \frac{1}{\cos^2 \frac{b}{2}}$.

Example 4. Simplify the expression

$$M = \sin\alpha + \sin(\alpha + \delta) + \dots + \sin(\alpha + n\delta).$$

⟦folio 40⟧

Solution. Noticing that the arguments of the sines form an argument progression with the difference $\delta$, we multiply both sides of the equality by $2 \sin \frac{\delta}{2}$:

$$2 \sin \frac{\delta}{2} \cdot M = 2 \sin \frac{\delta}{2} \sin \alpha + 2 \sin \frac{\delta}{2} \sin (\alpha + \delta) + \dots + 2 \sin \frac{\delta}{2} \times$$

$$\times \sin (\alpha + n\delta) = \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left( \alpha + \frac{\delta}{2} \right) + \cos \left( \alpha + \frac{\delta}{2} \right) -$$

$$- \cos \left( \alpha + \frac{3\delta}{2} \right) + \dots + \cos \left[ \alpha + \left( n - \frac{1}{2} \right) \delta \right] - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] =$$

$$= \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] = 2 \sin \left( \alpha + \frac{n\delta}{2} \right) \sin \frac{n+1}{2} \delta.$$

So, if $\sin \frac{\delta}{2} \neq 0$, that is $\delta \neq 2\pi k$, then

$$M = \frac{\sin \left( \alpha + \frac{n\delta}{2} \right) \sin \left( \frac{(n+1)\delta}{2} \right)}{\sin \frac{\delta}{2}}.$$

If $\delta = 2\pi k$, then

$$M = \sin \alpha + \sin (\alpha + 2\pi k) + \dots + \sin (\alpha + 2\pi nk) = (n+1) \sin \alpha.$$

Exercises

8. Prove the following:

$$= \frac{\sin \frac{n\alpha}{2} \cos \frac{(n+1)\alpha}{2}}{\sin \frac{\alpha}{2}};$$

a) (MEPhI). $\cos \alpha + \cos 2\alpha + \cos 3\alpha + \dots + \cos n\alpha =$

b) (MSU). $\cos \frac{\pi}{5} + \cos \frac{3\pi}{2} = \frac{1}{2}$.

9. (MEPhI). Simplify your expressions. a) $\cos \alpha \cdot \cos 2\alpha \cdot \cos 4\alpha \dots \cos 2^{n}\alpha$;

b) $\cos \alpha - \cos 2\alpha + \cos 3\alpha - \cos 4\alpha + \dots + (-1)^{n+1} \cos n\alpha$;

b) $\sin \alpha + 2 \sin 2\alpha + 3 \sin 3\alpha + \dots + n \sin n\alpha$;

r) $\sin^3 \frac{\alpha}{3} + 3 \sin^3 \frac{\alpha}{3^2} + 9 \sin^3 \frac{\alpha}{3^3} + \dots + 3^{n-1} \sin^3 \frac{\alpha}{3^n}$.

Example 5. Prove Christmas:

$$\mathrm{tg} \alpha + \frac{1}{2} \mathrm{tg} \frac{\alpha}{2} + \frac{1}{4} \mathrm{tg} \frac{\alpha}{4} + \dots + \frac{1}{2^n} \mathrm{tg} \frac{\alpha}{2^n} = \frac{1}{2^n} \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} 2\alpha.$$

Solution. Noticing that the right side of the identity contains cotan-gens, we express $\mathrm{tg} \alpha$ in terms of $\mathrm{ctg} 2\alpha$ and $\mathrm{ctg} \alpha$: $\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha$.

Then

$$\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha,$$

$$\mathrm{tg} \frac{\alpha}{2} = \mathrm{ctg} \frac{\alpha}{2} - 2 \mathrm{ctg} \alpha,$$

$$\mathrm{tg} \frac{\alpha}{4} = \mathrm{ctg} \frac{\alpha}{4} - 2 \mathrm{ctg} \frac{\alpha}{2},$$

$$\dots$$

$$\mathrm{tg} \frac{\alpha}{2^n} = \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} \frac{\alpha}{2^{n-1}}.$$

⟦folio 41⟧

Multiplying the written identities by 1, $\frac{1}{2}$, ..., $\frac{1}{2^n}$, respectively, and adding them together, we obtain the desired result. Our transformations only make sense for $\alpha \neq \frac{\pi k}{2}$ (check!).

Exercises

10. Prove the identities: a) (UGPI). $\sin^2 \alpha + \sin^2 (120^\circ + \alpha) + \sin^2 (120^\circ - \alpha) = \frac{3}{2}$;
6) (MAI). $tg 3\alpha = tg \alpha tg \left(\frac{\pi}{3} + \alpha\right) tg \left(\frac{\pi}{3} - \alpha\right)$; b) (MagGPI). $4 \cos^2 \alpha + \sin^2 2\alpha + 4 \sin^4 \alpha = 4$.

11. Convert into a product: a) (MagGPI). $\cos^2 (x + y) + \sin (x + y) + \cos (x + y) + \sin^2 (x + y)$;
6) (MAI). $tg^3\alpha + \frac{1}{\cos^2 \alpha} + 3 \text{ctg} \left(\frac{3\pi}{2} + \alpha\right) - 4$;
b) (MISP, 1969). $\sin 5\alpha \sin 4\alpha + \sin 4\alpha \sin 3\alpha - \sin 2\alpha \sin \alpha$; r) (MTI, 1970).

$\sec^2 \alpha - tg^2 \alpha + tg \left(\frac{\pi}{2} - \frac{\alpha}{2}\right) + \text{ctg} \left(\frac{\pi}{4} - \frac{\alpha}{2}\right)$.

Example 6. Calculate sin 18° without tables.
Solution e. We will use the fact that $18^\circ \cdot 5 = 90^\circ$, that is, that $2 \cdot 18^\circ + 3 \cdot 18^\circ = 90^\circ$, whence

$$\cos (2 \cdot 18^\circ) = \sin (3 \cdot 18^\circ)$$

and the fact that cos 2α and sin 3α are rationally expressed through sin α. Applying the formulas cos 2α = 1 - 2 sin²α and sin 3α = 3 sin α - 4 sin³α, from (5) we obtain: $4 \sin^3 18^\circ - 2 \sin^2 18^\circ - 3 \sin 18^\circ + 1 = 0$.

Denoting sin 18° by y, we arrive at the equation

$$4y^3 - 2y^2 - 3y + 1 = 0,$$

which is easy to solve by noting that $y = 1$ is its root (it immediately follows that the left-hand side of (6) is divisible by $y - 1$): $(y - 1) (4y^2 + 2y - 1) = 0$, whence $y_1 = 1, y_2, 3 = \frac{-1 \pm \sqrt{5}}{4}$. Considering that sin 18° ≠ 1, sin 18° > 0, we find that sin 18° = $\frac{\sqrt{5} - 1}{4}$.

Example 7. Let's simplify the expressions: a) $S_1 = \cos^2 \alpha + \cos^2 2\alpha + \dots + \cos^2 n\alpha$; b) $S_2 = \sin^2 \alpha + \sin^2 2\alpha + \dots + \sin^2 n\alpha$.
Solution e. Since sin²x + cos²x = 1, then

$$S_1 + S_2 = n.$$

Now applying the result of Exercise 8a) (for what α can this be done?), we get:

$$S_1 - S_2 = (\cos^2 \alpha - \sin^2 \alpha) + (\cos^2 2\alpha - \sin^2 2\alpha) + \dots + (\cos^2 n\alpha - \sin^2 n\alpha) = \cos 2\alpha + \cos 4\alpha + \dots + \cos 2n\alpha = \frac{\sin n\alpha \cos (n + 1)\alpha}{\sin \alpha}$$

Now from (7) and (8) it is easy to obtain: $S_1 = \frac{n}{2} + \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$; $S_2 = \frac{n}{2} - \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$. What is the answer for α = πk?

Exercises

12. Calculate without tables: a) cos 15°; b) tg 7.5°; c) tg 18°; r) (MAI, 1970). cos 55° cos 65° cos 175°; d) (MISP, 1969). tg 9° - tg 27° - tg 63° + tg 81°.

⟦folio 42⟧

Example 8. Find $\cos \alpha + \sin \alpha$ if $\sin \alpha \cos \alpha = 0,48$.

Solution. Taking the square root (as always, arithmetic!) from both sides of the identity $(\cos \alpha + \sin \alpha)^2 = 1 + 2 \sin \alpha \cos \alpha$, we obtain: $|\cos \alpha + \sin \alpha| = \sqrt{1 + 2 \sin \alpha \cos \alpha} = 1,4$ (the radical expression is non-negative: $1 + 2 \sin \alpha \cos \alpha = 1 + \sin 2\alpha \geq 0$, since $\sin 2\alpha \geq -1$). Since by condition $\sin \alpha \cos \alpha > 0$, then $\sin \alpha$ and $\cos \alpha$ have the same signs, that is, $\alpha$ is either in the I or III quarter. If $2\pi n < \alpha < \frac{\pi}{2} + 2\pi n$, then $\sin \alpha + \cos \alpha = 1,4$;

if $\pi + 2\pi n < \alpha < \frac{3\pi}{2} + 2\pi n$, then $\sin \alpha + \cos \alpha = -1,4$.

Exercises

13. a) (MAI). Find $\frac{1 - 2 \sin^2 \frac{\alpha}{2}}{1 + \sin \alpha}$ if $tg \frac{\alpha}{2} = m - 1$; 6) (MSU). Prove that if $tg \alpha = \frac{1}{7}$, $\sin \beta = \frac{1}{\sqrt{10}}$, then $\alpha + 2\beta = \frac{\pi}{4}$ ($\alpha$ and $\beta$ are the angles of the first quarter); 7) (MISP). Find $18 \sin \frac{3\alpha}{2} \sin \frac{\alpha}{2}$ if $\cos \alpha = \frac{2}{3}$. 8) (MTI). Find $tg \frac{\alpha}{2}$ if $tg \alpha = \frac{4}{3}$, $\pi < \alpha < \frac{3\pi}{2}$.

14. (MSU). It is known that $\alpha + \beta + \gamma = \frac{\pi}{2}$, $\alpha > 0$, $\beta > 0$, $\gamma > 0$ and that $ctg \alpha, ctg \beta, ctg \gamma$ form an arithmetic progression. Find $ctg \alpha$ $ctg \gamma$.

15. (MEPhI). Prove that if $\alpha, \beta, \gamma$ are the angles of a triangle, then

a) $\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$;

b) $tg \alpha + tg \beta + tg \gamma = tg \alpha tg \beta tg \gamma$;

r) $\sin 2\alpha + \sin 2\beta + \sin 2\gamma = 4 \sin \alpha \sin \beta \sin \gamma$;

d) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma = 2 \cos \alpha \cos \beta \cos \gamma + 2$;

e) $tg \frac{\alpha}{2} tg \frac{\beta}{2} + tg \frac{\alpha}{2} tg \frac{\gamma}{2} + tg \frac{\beta}{2} tg \frac{\gamma}{2} = 1$;

g) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$;

3) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma > 2$ (acute triangle).

16. Prove the inequalities:

a) (MIPT).

$ctg \frac{\alpha}{2} > 1 + ctg \alpha \left(0 < \alpha < \frac{\pi}{2}\right)$;

6) (VSU). $\cos \alpha + 3 \cos 3\alpha + 6 \cos 6\alpha \geq -7,2$;

b) (MIPT). $(1 - tg^2\alpha) (1 - 3tg^2\alpha) (1 + tg2\alpha tg3\alpha) > 0$; r) (MIPT).

$(ctg^2\alpha - 1) (3ctg^2\alpha - 1) \times (ctg3\alpha tg2\alpha - 1) \leq -1$; d) (MSU). $4 \sin 3\alpha + 5 \geq 4 \cos 2\alpha + 5 \sin \alpha$.

Moreover. The following abbreviations are used in the article:

MAI - Moscow Aviation Institute, MSU - Moscow State University, MGPI - Moscow State Pedagogical Institute, MagGPI - Magadan State Pedagogical Institute, MTI - Moscow Textile Institute, MISP - Moscow Institute of Steel and Slavs, MEPhI - Moscow Engineering Physics Institute, USPI - Ulyanovsk State Pedagogical Institute, VSU - Voronezh State University, MIPT - Moscow Institute of Physics and Technology.
