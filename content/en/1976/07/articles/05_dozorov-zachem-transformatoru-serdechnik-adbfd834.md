---
id: 1976-7-dozorov-zachem-transformatoru-serdechnik-adbfd834
issue: kvant_1976_7
year: 1976
number: "7"
title: Why does a transformer need a core?
authors:
  - Дозоров А. А.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14-17
tag: 9FIE
lang: en
source: kvant_digital
extraction: vision
content_sha256: f88f4f45c9ca0a3a95a9d677c55d329f270778ea0286ca763b668be3d7e4d313
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/05_dozorov-zachem-transformatoru-serdechnik-adbfd834.md
source_content_sha256: b17570371dc02d0303f682125af7fac7f23c41d00d30cd7a1bff5fc634dae84d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

Let's remember how to construct a transformer and why it works.

The simplest transformer (see figure) consists of two coils (windings) wound on a common steel core. One winding (primary) is connected to an alternating current source. The device consuming electricity (the so-called load) is connected to the second winding (secondary). Both the first and second windings are pierced by the same alternating magnetic flux created by the alternating current of the source. In the first winding with the number of turns $n_1$ E.D. arises. With. induction $e_1 = -n_1 \frac{\Delta \Phi}{\Delta t}$ (ΔΦ is the change in magnetic flux through one turn in time $\Delta t$), and in the secondary - E.D. With. induction $e_2 = -n_2 \frac{\Delta \Phi}{\Delta t}$.

Let's assume that the secondary winding is open, i.e., let's consider the cold running mode of the transformer. We will also assume that the active resistance of the primary coil is very small compared to its inductive resistance. According to Ohm's law, the sum of all E.D. With. in a closed circuit is equal to the sum of the voltage drops in this circuit (often Ohm’s law, written in this form, is called Kirchhoff’s rule):

$$u_1 + e_1 = i_1 R_1.$$

Here $u_1$ is the voltage of the current source, $i_1$ is the current and $R_1$ is the active resistance of the primary winding. Because $R_1$ is very few ($R_1 \rightarrow 0$), $u_1 + e_1 = 0$, or

$$u_1 = -e_1.$$

With the secondary winding open ($i_2 = 0$), the voltage at its ends

$$u_2 = -e_2.$$

Thus, the voltage ratio $\frac{u_2}{u_1} = \frac{e_2}{e_1}$, or for the action of the snatch

$$\frac{U_2}{U_1} = \frac{\mathcal{E}_2}{\mathcal{E}_1} = \frac{n_2}{n_1}.$$

This correspondence gives rise to the question posed in the title. Indeed, the voltage ratio depends only on the ratio of the number of turns in the windings, and the core parameters in accordance with (1) are absent. Can these parameters be arbitrary? Is it possible to operate a transformer without a core at all? If yes, under what conditions?

When deriving correspondence (1), it is assumed that the magnetic fluxes through the primary and secondary coils are equal. However, this condition may not be met: part of the magnetic flux created by the primary coil may dissipate and not penetrate the secondary winding of the transformer, which inevitably must lead to technical costs.

⟦folio 15⟧

ity of the transformer. So, maybe the main purpose of the core is to reduce magnetic flux dissipation? But resettlement can be avoided in other ways! For example, by winding the secondary winding directly onto the primary or by winding the windings onto a torus (steering wheel). And again the question arises, the formation in the title: why does a transformer need a heavy core, in which, among other things, energy losses arise - Foucault currents, hysteresis? In general, the core has a lot of shortcomings. So why is it needed?

So, the question is formed and condemned; it's time to move on to answering it.

Real devices, as a rule, have worse properties compared to those ideal models that are described by theory, especially the simplest one. This applies to the transformer. What kind of transformer can reasonably be called ideal? Let's try to understand this qualitatively. In a transformer, electromagnetic energy is transferred from the primary coil to the secondary coil. In the best case, the energy released in the secondary winding circuit will be equal to the energy consumed by the primary winding from the source. We can talk not about energy, but about power. It is also desirable that the power be maximum, i.e. power factor with f≈1. Mathematically, these requirements are recorded in a system of coefficients.

Consider a long coil with a large number of turns (soleond). The induction of a magnetic field created by a conductor carrying current is always proportional to the strength of the current and also depends on the configuration of the conductor, on the location of the point at which the magnetic field interests us, and on the magnetic properties of the medium. Inside the solenode the magnetic field is uniform. It can be shown that the induction of this field is $B = \mu_0 \mu I n/l$. Here $\mu_0$ is the magnetic constant, $\mu$ is the relative magnetic permeability of the medium, $n$ is the number of turns of the solenode, $l$ is its length. Then from equality (3)
$$\Phi = B S n = \mu_0 \mu I n^2 S/l.$$

Comparing this expression with (4), we find

⟦folio 16⟧

dem solenon inductance:
$$L = \mu_0 \mu n^2 S/l. \quad (5)$$

In a similar way, the concept of the coefficient of mutual inductance (mutual inductance) $M$ of two circuits is introduced. In our case, the concept of mutual inductance of the primary and secondary windings of a transformer. When the secondary winding is shorted to the load, a current appears in the secondary circuit. Let's denote its effective value $I_2$. At the same time, the current in the primary winding changes. Now its effective value $I_1$ is no longer the same as in the cold running mode of the transformer. The magnetic flux $\Phi_2$ through the secondary winding produced by the current $I_1$ of the primary winding is proportional to this current:
$$\Phi_2 \sim I_1, \text{ или } \Phi_2 = MI_1.$$
Similarly, the magnetic flux $\Phi_1$ through the primary winding caused by the current $I_2$ of the secondary winding,
$$\Phi_1 \sim I_2, \text{ или } \Phi_1 = MI_2.$$
Proportionality coefficient $M$ is the coefficient of mutual inductance, or the mutual inductance of the transformer windings. Similar to the derivation of the solenon inductance value, one can obtain an expression for $M$:
$$M = \mu_0 \mu n_1 n_2 S/l. \quad (6)$$
From expressions (5) and (6)
$$M = \frac{n_2}{n_1} L_1 = \frac{n_1}{n_2} L_2. \quad (7)$$

Note that, in fact, there is, of course, only one magnetic flux in the transformer core. In practice, it is entirely determined by the voltage of the current source connected to the primary winding circuit. However, for clarity, we can consider separately the magnetic fluxes created by the currents $I_1$ and $I_2$.

Let us now return to the transformer again and continue our discussion of its operation in operating mode. Let's write Ohm's law (Kirchhoff's rule) first for the closed circuit of the primary winding, and then for the secondary. In per-

⟦folio 17⟧

Here $A, B, \alpha$ and $\beta$ are constants.
Rate of change of first current

$$\frac{\Delta i_1}{\Delta t} = \frac{i_1(t + \Delta t) - i_1(t)}{\Delta t} =$$

$$= A \frac{\sin [\omega(t + \Delta t) - \alpha] - \sin (\omega t - \alpha)}{\Delta t} =$$

$$= 2 \frac{A}{\Delta t} \sin \frac{\omega \Delta t}{2} \cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right).$$

Directing $\Delta t$ towards zero $\left(\sin \frac{\omega \Delta t}{2} \approx \frac{\omega \Delta t}{2}\right)$,

$$\cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right) \approx \cos (\omega t - \alpha)),$$

we get

$$\lim_{\Delta t \to 0} \frac{\Delta i_1}{\Delta t} = A \omega \cos (\omega t - \alpha).$$

Likewise

$$\lim_{\Delta t \to 0} \frac{\Delta i_2}{\Delta t} = B \omega \cos (\omega t - \beta).$$

After which equations (8) and (9) turn into trigonometric ones:

$$U_0 \sin \omega t - p MA \omega \cos (\omega t - \alpha) - MB \omega \cos (\omega t - \beta) = 0,$$

(8a)

$$- \frac{1}{p} MB \omega \cos (\omega t - \beta) -$$

$$- MA \omega \cos (\omega t - \alpha) = RB \sin (\omega t - \beta).$$

(9a)

Each of these equations after the transformation elements (opening the brackets) can be written in the form

$$a \sin \omega t + b \cos \omega t = 0,$$

(10)

where the coefficients $a$ and $b$ do not depend on time.

Equation (10) is valid at any time $t$ only if $a=0$ and $b=0$ simultaneously. Thus, two equations are converted into four:

$$\begin{cases}
U_0 - p MA \omega \sin \alpha - MB \omega \sin \beta = 0, \\
p A \cos \alpha + B \cos \beta = 0, \\
- \frac{1}{p} MB \omega \sin \beta - MA \omega \sin \alpha = RB \cos \beta, \\
\frac{1}{p} MB \omega \cos \beta + MA \omega \cos \alpha = RB \sin \beta.
\end{cases}$$

Having solved this system, we will find the amplitudes of the currents in the primary and secondary circuits and the dwgi of the currents in phase relative to the external voltage.

Finally we get

$$I_{0_1} = A = \frac{U_0}{p^2 R} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2},$$

$$I_{0_2} = B = \frac{U_0}{p R},$$

$\alpha = \arctg \frac{p R}{M \omega}, \beta = \pi$.

Does the solution we found satisfy the requirement of an ideal transformer (respectively (2))? Let's check. Let us find the ratio of the amplitude values ​​of the currents:

$$\frac{I_{0_1}}{I_{0_2}} = \frac{A}{B} = \frac{1}{p} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2}.$$

The last expression coincides with correspondence (2), if under the root the second term tends to zero:

$$\frac{R}{M \omega} = \frac{R l}{\mu_0 \mu S n_1 n_2 \omega} \rightarrow 0$$

(the ratio of the number of turns $p$ must remain constant). Thus, a transformer can be considered ideal if

a) the magnetic permeability of the medium $\mu$ is sufficiently large,

b) the frequency of the alternating voltage $\omega$ is high enough,

b) the number of turns in the primary and secondary windings is large,

d) the active resistance of the secondary winding is small,

d) the length of the coil is minimal, i.e. the windings are wound tightly.

To create a transformer that is close to ideal, you need to choose the most convenient transformation in a practical sense. This is, first of all, the transformation of the high magnetic permeability of the medium. For vacuum $\mu=1$, and for ferromagnets $\mu \approx 10000$. Increasing the number of turns is practically unprofitable (the size and cost of the transformer increase sharply), and increasing the frequency of current by several thousand times is associated with significant technical problems. Existing high-frequency transformers are actually used without a core, and their properties are close to those of an ideal transformer.
