---
id: 2024-11-12-nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: Variations on a theme of a geometric problem
authors:
  - Николов Н.
  - Иванов А. Д.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28, 31
tag: TPIO
lang: en
source: kvant_digital
content_sha256: 7f8ddad7e8d51d445f7a92af24d9da447be4203ce4ef0e9bb1f0e59599c7ed19
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/06_nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba.md
source_content_sha256: f48dfd089e0476af5d204b46105a83c1d5a7e6045e6c45063aaaf515e28e3a06
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 28⟧

Variations on a theme of a geometric problem

N. NIKOLOV (SOFIA), A. IVANOV (PLEVEN)

In this article we will discuss the plot related to the geometric problem M2809 offered at the 73rd Bulgarian National Olympiad.

Let's look at this simple design. Let points M and N be located respectively on sides AC and BC of triangle ABC (Fig. 1). Let the segments AN and BM intersect at point O. In what follows we will use the standard notation for the elements of a triangle: BC = a, AC = b, ACB J. In addition, we put CM = m, CN = n, AOM T.

⟦column⟧

⟦figure⟧

Fig. 3

⟦figure⟧

Fig. 1

Let's start with the following task, which is, in principle, accessible to students in grades 7–8. Problem 1. Let ACB 90 q, and also let it be known that AM = BC and CM = BN. Find A OM.

Exercise 1. Find out what the answer to problem 1 is in the limiting cases AC = BC and AC = 2BC.

Solution. Let's complete the triangle AMB to the parallelogram AMBP (Fig. 2). Then B.C.

Fig. 2

⟦folio none⟧

---
running_head:
folio:
---

= AM = PB, CM = BN, $\angle BCM = 90^\circ = \angle PBN$ and, therefore, triangles BCM and PBN are equal. Therefore AP = BM = PN. We also have $\angle BNP = \angle CMB = 90^\circ - \angle MBN$, i.e. NP ⊥ BM, hence NP ⊥ AP. Then triangle ANP is an equilateral right triangle, hence $\angle AOM = \angle OAP = 45^\circ$. Solution problem.

Exercise 2. Obtain another solution to problem 1 from the following construction (Fig. 3). Let BNAX be a parallelogram.

Fig. 3

a) Prove the equality of right triangles BCM and MAX.
b) Find the angles of triangle XMB and then find $\angle AOM$.
This construction can be obtained in another way by taking a square built on the AC side and an inscribed square built on the BM side.

Note that in our notation the conditions AM = BC and CM = BN of Problem 1 are rewritten as $b - m = a$ and $m = a - n$.

If $\angle ACB = 90^\circ$, simple calculations allow us to express the quantities $\theta$ in terms of $a$, $b$, $m$, $n$. In particular, let us state the following statement.

Statement 1. If $\angle ACB = 90^\circ$, mo $\theta = 45^\circ$ could and quietly could, when
$$ab - mn = bm + an.$$ (1)

Proof. Let's put $\theta_1 = \angle CAN$ and $\theta_2 = \angle BMC$, so that $tg\theta_1 = \frac{NC}{AC} = \frac{n}{b}$ and $tg\theta_2 = \frac{BC}{MC} = \frac{a}{m}$. Then
$$tg\theta = tg(\theta_2 - \theta_1) = \frac{tg\theta_2 - tg\theta_1}{1 + tg\theta_1tg\theta_2} = \frac{ab - mn}{bm + an}.$$

It remains to use the fact that $\theta = 45^\circ$ if and only if $tg\theta = 1$. That's what was required.

Exercises
3. Carry out an algebraic calculation showing that the system of equalities $b - m = a$ and $m = a - n$ implies (1).
4. Let $a, b, m, n$ be positive numbers. Prove that from (1) it follows that $b > n$ and $a > m$.

Now we fix $a, b, m, n$, and the angle $\gamma$ allows changing - we can consider that we have an ACB hinge with fixed marks $M$ and $N$ on AC and CB. Then the angle $\theta$ depends on $\gamma$, i.e. the function $\theta = \theta(\gamma)$ for $\gamma \in (0; \pi)$ is defined. You can observe (for example, in the Geogebra program) the change in $\theta(\gamma)$. Let us prove some statements about the behavior of $\theta(\gamma)$.

Statement 2. Let $a > m$ and $b > n$. Then the $\theta(\gamma)$ order decreases on the interval $(0; \pi)$.

Before proving this statement, let us state the following corollary.

Consequence. Let (1) be fulfilled. Then: $\theta > 45^\circ$ if and only if $\gamma < 90^\circ$, $\theta = 45^\circ$ if and only if $\gamma = 90^\circ$, $\theta < 45^\circ$ if and only if $\gamma > 90^\circ$.

Proof. Indeed, from Exercise 4 we know that (1) will highlight $a > m$ and $b > n$. Then everything follows from statements 1 and 2: $\theta(\gamma)$ order decreases, and in addition, the equality $\theta\left(\frac{\pi}{2}\right) = \frac{\pi}{4}$ is satisfied. The investigation has been proven.

Let us recall problem M2809 (we present its formulation in our notation) and assume that it immediately follows from Statement 2.

Task 2 (M2809). It is known that AM = BC and CM = BN. Find $\gamma$ if you know that $\gamma = 2\theta$.

First decision. As we saw as a consequence, for $\gamma < 90^\circ$ $2\theta > 2\cdot 45^\circ > \gamma$ is satisfied, and for $\gamma > 90^\circ$ $2\theta < 2\cdot 45^\circ < \gamma$ is satisfied. This means that $\gamma = 90^\circ$ is the only possible value.

At the end of this article we will present another short, elegant geometric solution to problem M2809, which does not rely on any other statements from the article.

No, let's continue our research for now.

Proof of Statement 2. Set $x = \cos \gamma$, $y = -\cos \theta$. It is enough for us to understand that the function $y(x)$ is strictly increasing on the interval $x \in [-1; 1]$. Below we will calculate $y(x)$ explicitly.

Let us complete the triangle AMB do parallelogram AMBP (Fig. 4) so ​​that BP = AM = $b - m$, $\angle NBP = 180^\circ - \gamma$, $\angle NAP = \theta$.

⟦folio 31⟧

---
running_head:
folio:
---

all values ​​from the integral $\left[ \theta \left( \gamma_0 \right); 0 \right)$. Also, $\theta \left( \gamma_0 \right) < \pi/2$.

Proof. Since $a < m$, then $p < 1$, and from the formula for $y(x)$ we see that $y(x) \in (-1; 0)$ at $x \in (-1; 1)$, and in addition, $y(\pm 1) = -1$. Now it remains to understand that there is $x_0 \in (-1; 1)$ such that $y(x)$ strictly returns at $x \in [-1; x_0]$ and strictly kills at $x \in [x_0; 1]$, and in addition, $x_0 > 0$.

Calculating the arbitrary one gives:

$$y'(x) = \frac{ux + v}{2\left(\sqrt{1 - qx}\sqrt{1 - rx}\right)^3},$$

where $u = 2qr - pq - pr$, $v = 2p - q - r$. We see that (since $y(x)$ is not a constant function) an arbitrary $y'(x)$ can turn to 0 only at one point $\left(x_0 = -\frac{v}{u}\right)$, respectively, the sign $y'(x)$ can change no more than once (only at the point $x_0$). This means that either $y(x)$ is strictly monotonic on $[-1; 1]$, or $[-1; 1]$ is divided by the point $x_0$ into two intervals of strict monotonicity. The first option is not possible because $y(\pm 1) = -1$. This means that $x_0 \in (-1; 1)$, and since $y(x) > -1$ on the interval $x \in (-1; 1)$, $y(x)$ must strictly return at $x \in [-1; x_0]$ and strictly kill at $x \in [x_0; 1]$.

It remains to be seen that $x_0 = -\frac{v}{u} > 0$. We already know that $y'(x) > 0$ at $x \in [-1; x_0]$ and $y'(x) < 0$ at $x \in (x_0; 1]$. In particular, $y'(-1) > 0$, whence $-u + v > 0$ and $y'(1) < 0$, hence $u + v < 0$. From this we get that $u < 0$. Let us show that $v > 0$ by direct substitution: put $s = \frac{a}{m}$, $t = \frac{n}{b}$ (so $s > t$) and transform

$$\frac{v}{2} = p - \frac{q}{2} - \frac{r}{2} = \frac{s + t}{st + 1} - \frac{s}{s^2 + 1} - \frac{t}{t^2 + 1} = \frac{(s - t)^2(s + t)}{(st + 1)(s^2 + 1)(t^2 + 1)} > 0.$$

The statement has been proven.

In conclusion, as promised, we present a solution to problem 2, which is not based on statistical results. This decision was made by Olympic participant Vasil Vasilev.

Second solution to problem M2809. So, $AM = BC, CM = BN, \angle ACB = \gamma, \angle AOM = \frac{\gamma}{2}$.

1) Let's complete the triangle $ABC$ to the parallelogram $ACBQ$ (Fig. 5). Then $\angle QAM = 180^\circ - \angle ACB = 180^\circ - \gamma$. And since $AM = BC = AQ$, from the equilateral triangle $AMQ$ we have $\angle AQM = \frac{180^\circ - \angle QAM}{2} = \frac{\gamma}{2}$. We see that $\angle AQM = \angle AOM$, which means that the points $A, Q, O, M$ lie on the same circle.

2) Now on the segment $BQ$ we take a point $R$ such that $BR : RQ = CM : MA$ (so that $AMRQ$ and $MCBR$ are parallelograms). Then $\angle CBR = 180^\circ - \angle ACB = 180^\circ - \gamma$. And since $BR = CM = BN$, from the equilateral triangle $BRN$ we have $\angle BRN = \frac{\gamma}{2}$. We see that $\angle BRN = \angle BON$, which means that the points $B, R, O, N$ lie on the same circle.

3) Further, from the circle (BRON) we see that $\angle ROB = \angle RNB = \frac{\gamma}{2}$. But from the previous angle count $\angle RQM = \angle RQA - \angle MQA = \gamma - \frac{\gamma}{2} = \frac{\gamma}{2}$. This means that $\angle ROB = \angle RQN$ is open; it follows that the quadrilateral $MQRO$ is inscribed.

4) So, all five points $A, Q, O, M, R$ lie on the same circle. From here the statement of the problem immediately follows, since then $AQRM$ is an inscribed parallelogram, which means that it is a right angle, $\gamma = \angle AQB = 90^\circ$ is open.

Exercise 7. Replace step 3) of the solution with a proof that $AQRO$ is an cyclic quadrilateral.
