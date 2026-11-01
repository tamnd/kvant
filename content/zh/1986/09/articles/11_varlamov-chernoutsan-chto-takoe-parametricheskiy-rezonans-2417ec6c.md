---
id: 1986-9-varlamov-chernoutsan-chto-takoe-parametricheskiy-rezonans-2417ec6c
issue: kvant_1986_9
year: 1986
number: "9"
title: 什么是参量共振？
authors:
  - Варламов А. А.
  - Черноуцан А. И.
rubric: shkola-v-kvante
page_first: 31
page_last: 32
page_labels: 29-30
tag: 3Z3J
lang: zh
source: kvant_digital
extraction: vision
content_sha256: fbe5e974548c0a3f56af4b6ffba48bacfabb52ab13b641c5cf43cd543c59851f
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/11_varlamov-chernoutsan-chto-takoe-parametricheskiy-rezonans-2417ec6c.md
source_content_sha256: f748ba44460592aff4ebc84adef2efa4e9b7b0bc1200adf9d6bcb0f3fb546500
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

考虑三个特定过程的传递系数并不代表太大的困难。

事实证明，所有三个系数（电导率、扩散度和粘度）均与分子的自由长度 (l) 及其热运动的平均速度 (v) 成正比：λ~D~η~lv。传递系数对分子运动特征的这种依赖性是非常自然的。毕竟，分子v的平均速度决定了建立平衡过程中一种或另一种特性的传递速度。公式中出现自由碰撞的长度l，因为每次碰撞后，分子运动的参数由发生这些碰撞的地方（即彼此间隔距离l的点）的系统参数决定。因此，在我们的身体电导率示例中，下一次碰撞期间分子传递的能量决定了介质中发生本次碰撞和上一次碰撞的那些点的温差。

E·E·戈罗德茨基

什么是参量共振？

从这个例子可以清楚地看出，振荡幅度的急剧影响不仅可以由周期性外力引起，还可以由振荡系统的参数之一的周期性变化引起，前提是这些变化的频率由与系统自然振荡频率的联系确定。这种共振称为参数共振。

为了阐明该方法的机制，成功的振荡被处理到您熟知的系统 - 外部重量（“物理 10”，§ 2）。然而，为了激发重量振荡的正常特性，我们将执行以下操作。

当质量为 m 的重物以最大速度 v_m 通过平衡位置时，让我们在其上放置一些质量为 Δm 的附加重物，例如板球。为了保证此时重物的速度不会改变，我们首先将球加速到相同的速度v_m。请注意，在加速球的过程中，我们做功，最终将系统的总能量增加到 (m+Δm)v²/m/2 的值。与之前相比，能量的增加导致其他 x'm 的解的最大计算量更大，其大小可以从能量守恒定律中找到。

$$\frac{(m+Δm)v²}{2} = \frac{k(x'm)²}{2}.$$

当枪达到最大距离且重物速度为零的那一刻，我们瞬间对称。由于此时系统的能量仅包含在拉伸的梁中，因此减少配重的质量不会以任何方式改变系统的总能量。因此，我们设法向系统添加额外的能量 Δmv²/m/2。同时

⟦folio 30⟧

系统能量增加
$$n = \frac{(m + \Delta m)v_m^2}{2m v_m^2} = 1 + \frac{\Delta m}{m} \text{ раз.}$$

让我们让我们的系统“休息”一下，当重量再次通过（沿相反方向）平衡位置时，我们用橡皮泥球重复相同的过程。然而，现在，由于之前的干预，重物的最大速度结果等于$v_m' = \sqrt{(m + \Delta m)/m} v_m$，并且，加速球，在将其放在重物上之前，我们将必须比第一次做更多的工作（$\Delta m(v_m')^2/2 > \Delta m v_m^2/2$）。

因此，每个极化我们都会增加系统的能量，并且很明显，这种能量的增加会导致振荡幅度的增加（我们将认为球的质量与重物的质量相比非常小，以至于系统振荡频率的变化可以忽略不计）。

重点在于，与传统共振不同，在传统共振中，外力的频率必须等于系统振荡的固有频率，在参数共振的情况下，当系统的一个或另一个参数的变化频率是振荡的固有频率的两倍时，振荡的放大最有效。

让我们考虑另一个例子，或者构建参量共振发生的一般原理的例子。 Let us imagine an oscillatory circuit consisting of a capacitor and a coil in which free electrical oscillations can occur (“Physics 10”, § 13).我们会定期改变电容器的电容值。 To do this, at the moment when the charge on the capacitor is maximum, its plates quickly develop, and when the charge on the plates is zero, we just as quickly return them to their previous position. Continuing this process, one can be convinced that the amplitude of oscillations in such a system will increase indefinitely, although there is no external EMF in the circuit. The fact is that when developing charged plates, we each time make a positive equality, and when bending uncharged plates, we do not do any work at all. It is easy to see that in this process the frequency of the external influence is twice as high as the natural frequency of the system’s oscillations.

What happens if we take an oscillatory circuit, in which there are initially no obvious oscillations, and begin to change the capacitance of the capacitor purely mechanically (the distance between the plates or their area) with a frequency twice its own?事实证明，在这种情况下，也会发生振荡增加的过程！事实上，电容器板上总是有少量意外形成的电荷。根据上述方案，该电荷为振荡的快速增长提供了“初始动力”。这个王子包含电磁振荡发生器和放大器，称为参数机。 The first parametric machine was designed in 1933 based on the research of Soviet physicists - academicians L. I. Mandelstam and N. D. Papaleksi.

那么，如果系统不理想，即存在能量损失怎么办？

对于普通共振，能量损失决定了振荡的最大幅度。在参数共振的情况下，这些损耗的作用就占据了主导地位。正如我们已经讨论过的，通过参量共振，对于每个极化电极，系统的能量都会增加一定的倍数，但同时，部分能量也无法挽回地损失掉（以热的形式释放）。如果能量的增加超过了损耗，那么振荡虽然比没有损耗时慢，但为了在有摩擦的系统中激发振荡，系统的相应参数应该改变到更大的程度——更大质量的球应该改变为重量，电容器板应该扩展到更大的距离。荡秋千的人必须蹲得更深，但如果你设法开始荡秋千，那么在不改变蹲下深度的情况下，你就可以荡得非常有力。

A.A.瓦尔拉莫夫、A.I.切尔波尚
