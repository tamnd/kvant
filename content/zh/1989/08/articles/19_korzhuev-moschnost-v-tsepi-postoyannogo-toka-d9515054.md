---
id: 1989-8-korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054
issue: kvant_1989_8
year: 1989
number: "8"
title: 直流电源
authors:
  - Коржуев А. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 69
page_last: 71
page_labels: 67-69
tag: HM4O
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b9d6990791f0119bd394be7464a4bc2ca3c1e4b4a2ed769bdea1487aaf92a5d9
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/19_korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054.md
source_content_sha256: e134fd1086fe0cad2201e335dbcf4face093f343aed6216f6ef75df80f690a95
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 67⟧

直流电源

科尔茹耶夫

让我们回顾一下解决涉及直流电路计算的问题时使用的基本原理。

假设有一个简单的（无分支的）闭合电路（图1），包含一个具有电动势和内阻$r$的电流源以及一个具有电阻$R$的电阻器（也称为外部电阻）。根据这种电路的欧姆定律，电流在其中流动

$$I = \frac{\mathcal{E}}{R + r}.$$

在这种情况下，电路外部部分的电压等于

$$U = \mathcal{E} - Ir,$$

电阻上释放的功率等于

$$P_{\text{вн}} = IU,$$

源的总功率为

$$P_{\pi} = I\mathcal{E}.$$

现在我们来看几个具体问题，首先讨论直流电源的问题。

问题 1. 电路包含一个电动势为 $\mathcal{E}$、内阻为 $r$ 的电源，以及变阻器电阻 $R$（参见图 1）。计算电源释放的总功率、提供给其外部电路的功率（净功率）以及电源的效率。验证这些量对外部电阻的依赖性。

根据欧姆定律，电流流过电路

$$I = \frac{\mathcal{E}}{R + r}.$$

电路部分释放的功率为

⟦folio 68⟧

根据定义，电压为 $U$ 的 Pi 等于 $P = IU$。在我们的例子中

$$P_{\text{BH}} = IU = I^2R = \frac{\mathcal{E}^2R}{(R+r)^2}.$$

电源的总功率为

$$P_{\pi} = I\mathcal{E} = \frac{\mathcal{E}^2}{R+r},$$

其效率为

$$\eta = \frac{P_{\text{BH}}}{P_{\pi}} = \frac{R}{R+r} = \frac{1}{1+r/R}.$$

现在让我们分析所有发现的量对外部电阻$R$的依赖性。可以看出，随着$R$的增加，总功率将会下降，相反，效率将会增加 - 随着$R$的增加，越来越多的总功率份额分配给电路的外部部分（与内部源分配的功率相比）。随着能量的释放，情况变得更加复杂。从表达式$P_{\text{BH}} = \mathcal{E}^2R/(R+r)^2$可以得出$P_{\text{BH}} = 0$位于$R = 0$（这是完全自然的）和$R \to \infty$。显然，存在一个值$R$，此时有用功率最大。通过继续 $P_{\text{BH}}$ 通过阻力 $R$ 并将该导数等于零，很容易找到：

$$P'_{\text{BH}} = \frac{\mathcal{E}^2(R+r)^2 - 2\mathcal{E}^2R(R+r)}{(R+r)^4} = 0,$$

我们从哪里得到它

$$R = r$$

— $P_{\text{BH}}$ 最大且等于 $\mathcal{E}^2/(4r)$，前提是外部电阻和内部电阻相等。然而，效率等于

$$\eta = \frac{R}{R+R} = \frac{1}{2},$$

即，总发电功率的一半分配给电源的内阻。反过来，在 $R \to \infty$ 时效率最大且等于 1，但 $P_{\text{BH}}$ 趋于零。因此，在这样的电路中不可能同时实现最大和最有效的能量输出。虽然我们在功率方面有所损失，但我们在效率方面有所提高，反之亦然。

$P_{\text{BH}}$、$P_{\pi}$ 和 $\eta$ 对外部电阻 $R$ 的依赖性如图 图 2 所示。该图清楚地证实，在 $R = 0$ 处，所有功率均在电源的内阻处释放。在$R = r$时，传输到外部电路的功率等于总发电功率的一半，效率为1/2。随着$R$的增加，依赖图$P_{\pi}(R)$和$P_{\text{BH}}(R)$彼此越来越接近，内阻处释放的功率减小。在$R \gg r$时，几乎所有产生的功率都释放到外部电路中，效率趋于1。

问题2.使用图1所示电路，流程1。假设源的$\mathcal{E}$和$r$已知，计算外部电路释放的功率，得到总功率和效率

⟦folio 69⟧

来源。分析这些量对电路中电流的依赖性。

很明显

$$P_{\pi} = I \mathcal{E},$$

$P_{\mathrm{bH}}$ 可以通过从总功率中减去分配给源内阻的功率来找到：

$$P_{\mathrm{bH}} = \mathcal{E} I - I^2 r.$$

然后是效率

$$\eta = \frac{P_{\mathrm{bH}}}{P_{\pi}} = \frac{\mathcal{E} I - I^2 r}{\mathcal{E} I} = 1 - \frac{I r}{\mathcal{E}}.$$

随着电流$I$的增加，总功率线性增加（自$\mathcal{E} = \text{const}$开始），效率下降——电流的增加可以通过减小外部电阻来实现，因此与内部电阻释放的功率相比，减少$P_{\mathrm{bH}}$的份额。 $P_{\mathrm{bH}}$ 对 $I$ 的依赖性是二次的。 $P_{\mathrm{bH}}$在$I = 0$和$I = \mathcal{E}/r$消失。这意味着存在某个电流值，在该值下有用功率最大。对电流进行微分后，我们发现

$$P'_{\mathrm{bH}} = \mathcal{E} - 2 I r = 0, \text{ если } I = \frac{\mathcal{E}}{2 r}.$$

而且，$P_{\mathrm{bH} \max} = \mathcal{E}^2/(4 r)$，与任务1一致。

为了直观地说明所获得的结果，让我们构建所有找到的值对当前 (图 3) 的依赖性的图表。和上一个问题一样，最大功率对应的效率值为1/2；同时$I = \mathcal{E}/r$$P_{\mathrm{bH}} = 0$（这是外部电阻为0时的情况）和$\eta = 0$。

问题 3. 众所周知，随着时间的推移，由气体组成的电池

$$\frac{\mathcal{E}^2}{R + r} \quad \frac{\mathcal{E}^2}{R} \quad \frac{\mathcal{E}}{R + r}$$

Vanich 元素“坐下”（其电动势下降）。外部电路中的总功率和效率如何取决于源$(\text{см. рис. 1})?$的电动势？假设源的内阻$r$不变。

正如问题 1 中已经得到的，

$$P_{\pi} = \frac{\mathcal{E}^2}{R + r}, \quad P_{\mathrm{bH}} = \frac{\mathcal{E}^2 R}{(R + r)^2},$$

$$\eta = \frac{R}{R + r}.$$

从这些表达式可以清楚地看出，当$\mathcal{E}$下降时，总功率和释放到外部电路的功率都减少，两者都遵循二次定律，而效率保持不变，直到源电动势为零，功率释放过程完全停止。

相应的图如图4所示。

问题4、电枢绕组电阻为$R$的电动机，由恒压源$U$供电，流过电流$I$（图5）。计算功耗、由于绕组加热而损失的功率以及电机的效率。分析指示值对电机电流的依赖性。

电机从电源获取动力

$$P_{\mathrm{ot}} = I U.$$

在这种情况下，根据焦耳-楞次定律，消耗热功率来加热绕组

$$P_{\tau} = I^2 R.$$

这些值之间的差异
