---
id: 1982-7-bakanina-zakonyi-sohraneniya-pri-yadernyih-prevrascheniyah-629559b7
issue: kvant_1982_7
year: 1982
number: "7"
title: 核转变过程中的守恒定律
authors:
  - Баканина Л. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 60
page_last: 61
page_labels: 58-59
tag: OTTX
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 458a949a8a61c2f498043d9c31279efdcb2e22f5da7729b17543b9798d32195a
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/14_bakanina-zakonyi-sohraneniya-pri-yadernyih-prevrascheniyah-629559b7.md
source_content_sha256: 64d9e91d39133c2e94683e3d959f12061ce7763440d10a4b993c999ee48f0aa3
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 58⟧

核转变过程中的守恒定律

原子核相互作用过程中发生的过程总是很复杂，而且还远未得到充分研究。然而，如果根据经验知道核反应会产生什么产物，那么它们的速度（以及动能）就可以使用能量和动量守恒定律来计算。

所有核反应都满足动量守恒定律：产生的粒子的总动量始终等于系统的初始动量。

使用能量守恒定律时，必须记住一些核反应涉及能量的释放，而另一些则涉及能量的吸收。这是因为相互作用之前系统的总质量可以大于或小于所形成的产物的总质量。正如他们所说，存在质量缺陷$\Delta m$，它决定了反应过程中释放或吸收的能量$\Delta E$。根据爱因斯坦的公式，

$$\Delta E = \Delta mc^2,$$

其中$c$是光速。

应该记住，在反应之前和之后，质量缺陷总是远小于原子核的质量。因此，只有在需要确定反应能$\Delta E$的情况下才需要考虑。如果给定了它或者在给定问题中不需要确定它，则可以（并且应该）使用核质量的舍入值。

让我们考虑几个具体任务。

问题1.氡是一种α放射性气体，原子质量为$A = 222$。氡衰变过程中释放的总能量中，有多少部分被 α 粒子 (图 1) 带走？

图 1.

衰变过程中释放的能量$\Delta E$（由于质量缺陷）以反应产物动能的形式释放：α粒子（$A_a = 4$）和残余核（$A_a = 218$）。由于质量缺陷的存在小于原始原子核的质量，因此释放的能量与原子核的其余能量相比较小，并且可以使用非相对论（经典）公式来计算动能。因此，

$$\Delta E = \frac{m_a v_a^2}{2} + \frac{m_a v_a^2}{2}.$$

此外，还必须满足动量守恒定律：

$$m_a v_a - m_a v_a = 0.$$

我们认为，在衰变之前，氡核积累，或者无论如何，它的动能远小于反应能量$\Delta E$，因此我们假设总动量等于0。

α粒子带走的总能量的分数等于

$$\frac{E_a}{\Delta E} = \frac{E_a}{E_a + E_a} = \frac{m_a v_a^2}{m_a (m_a / m_a)^2 v_a^2 + m_a v_a^2} = \frac{m_a}{m_a + m_a} = \frac{A_a}{A} \approx 0,98.$$

因此，α粒子带走了衰变过程中释放的 98% 的能量。

问题2. 当中子被$^6$Li核俘获时，发生核反应$^6$Li + $^1$n $\rightarrow^3$T + $^4$He (图 2)，

⟦folio 59⟧

图 2
其中释放出能量$\Delta E = 4,8$ MeV。考虑初始粒子的最终能量可以忽略不计，求反应产物（氚核和 α 粒子）之间的能量分布。

该任务与上一个任务基本相似。让我们写下能量和动量守恒定律：

$$\frac{m_T v_T^2}{2} + \frac{m_a v_a^2}{2} = \Delta E,$$
$$m_T v_T - m_a v_a = 0.$$

从这里，考虑到氚和α粒子的原子质量分别等于$A_T = 3$和$A_a = 4$，我们发现

$$E_T = \frac{m_T v_T^2}{2} = \frac{m_a}{m_T + m_a} \Delta E = \frac{4}{7} \Delta E \approx 2,74 \text{ МэВ},$$
$$E_a = \Delta E - E_T = \frac{3}{7} \Delta E \approx 2,06 \text{ МэВ}.$$

问题3. 通过将加速至$E_D = 2$ MeV能量的氘离子引导到氚靶上，研究氘和氚$^2\text{D} + ^3\text{T} \rightarrow^1\text{n} + ^4\text{He}$（图 3）的合成反应。德-

图 3.
探测器抵抗垂直于氘核束方向发射的中子。如果反应释放能量 $\Delta E = 17,6$ MeV，请确定抵抗中子的能量。

在这种情况下，系统的初始动量不为零，此外，中子和α粒子沿不同方向飞行。

这意味着粒子动量必须作为向量相加，动量守恒定律必须写成向量形式：

$$\vec{P}_D = \vec{P}_n + \vec{P}_a.$$
由于 $\vec{P}_n \perp \vec{P}_D$ (图 4)，根据定理

图 4.
毕达哥拉斯
$$P_a^2 = P_D^2 + P_n^2.$$
根据能量守恒定律
$$E_n + E_a = E_D + \Delta E,$$

或者
$$\frac{P_n^2}{2m_n} + \frac{P_a^2}{2m_a} = E_D + \Delta E.$$
从这些方程中可以发现
$$E_n = \frac{P_n^2}{2m_n} =$$
$$= \frac{m_a}{m_n + m_a} \left( \Delta E + \frac{m_a - m_D}{m_a} E_D \right) \approx 14,9 \text{ МэВ}.$$

图 5.
问题 4. 如果入射到静止氮原子核上的 α 粒子的能量超过阈值能量 $E_n = 14,5$ MeV，则可能发生核反应 $^{14}\text{N} +^{4}\text{He} \rightarrow^{17}\text{O} +^{1}\text{p}$ (图 5)。 α粒子的能量应该比阈值大多少，才能使质子反应过程中形成的动能为零？
