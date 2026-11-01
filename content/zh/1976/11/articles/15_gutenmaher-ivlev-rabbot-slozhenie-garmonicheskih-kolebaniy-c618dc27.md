---
id: 1976-11-gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27
issue: kvant_1976_11
year: 1976
number: "11"
title: 添加简谐振动
authors:
  - Гутенмахер В. Л.
  - Ивлев Б. М.
  - Раббот Ж. М.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 46
page_last: 48
page_labels: 44-46
tag: LOL2
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 460e900f4d475596c89aae5afcd1a67f96ba8b9ecfee6aae567cf0c32b539d09
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/15_gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27.md
source_content_sha256: 7882e6961e1e51619536163b024a756f6eee190fc988bb29795da4711f0ae1e1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

添加简谐振动

在教科书“代数与分析原理 10”第 16 节第 80 段中，使用连接到两个水平弹簧 (图 1) 的球的运动示例介绍了简谐振动的概念。我们不会在这里讨论自然产生和谐振动的物理过程。我们的目标是了解相同频率的谐波振荡的加法。

正如我们已经注意到的 (图 1)，简谐振动可以表示为原点 O 沿 Ox 轴的振动。这个运动的图形与函数的图形相同

$$x(t) = A \cos(\omega t + \varphi).$$

振荡过程中x(t)点与O点的最大偏差当然等于|A|个数。称为振荡幅度。振荡周期等于$$\frac{2\pi}{|\omega|}.$$值|ω|称为振荡频率。点 x(t)（时间 t=0 时）的初始位置由值 A cos φ 指定。

当然，相同的简谐振动可以由不同的公式给出。

以振荡点运动为例，我们应用它们，这意味着两个简谐振动相加。如果 Ox 轴上的一个初始位置为 A₁cos φ₁ 的点 x₁ 根据定律 x₁(t) = A₁cos(ω₁t + φ₁) 振动，而另一个初始位置为 A2cos φ2 的点 x2 根据定律 x2(t) = A2(cos ω2t + φ2) 振动，那么这些振动之和将是某一点的振动x 的初始位置为 A₁cos φ₁ + A2cos φ2，根据定律 x(t) = A₁cos(ω₁t + φ₁) + A2cos(ω2t + φ2)。事实证明，如果点 x₁ 和 x2 以相同频率 ω₁ = ω2 = ω 振荡，那么它们的和也将是相同频率 ω 的简谐振动。教科书第 82 § 16 段中的这一事实源于以下事实：微分方程 y'' = -ω²y 的两个解的和又是该方程的解（并且其所有解的形式为 y = A cos(ωt + φ)。是否可以在不了解微分方程的情况下以更简单的方式获得此结果？

您可以尝试以图形方式添加和谐振动。 图 2 显示具有相同周期的两个函数的图像：y = 2cos(2t + π/3) 和 y = cos(2t + π/6)。从这两张图来看，根本不清楚它们的和 y = 2cos(2t + π/3) + cos(2t + π/6) 是否会是简谐振动。所以，正如我们所看到的，这不是很方便。

图 1.

⟦folio 45⟧

在 $\omega_1 = \omega_2 = \omega$ 的情况下，使用矢量图来说明简谐振动的相加要容易得多。让我们解释一下它是什么。

首先，简谐振动的条件写为$A \cos(\omega t + \varphi)$，其中$A > 0$、$\omega > 0$、$\varphi \in [0, 2\pi]$。我们可以为这种形式带来任何和谐的振动。现在让我们考虑一些坐标系 $XOY$ 并取一个半径为 $A$、中心为 $O$ 位于原点的圆（回想一下，$A$ 被选为正值）。假设某个点$P(t)$沿着这个圆逆时针移动——它的位置取决于时间$t$——使得向量$\vec{OP}(t)$匀速旋转，每单位时间经过$\omega$弧度（$\omega$选正值）。假设在初始时刻$(t = 0)$，向量$\vec{OP}(0)$与$OX$轴正方向形成$\varphi$（$\varphi \in [0, 2\pi]$）角度，即$P(0)$点的坐标为$(A\cos\varphi; A\sin\varphi)$。那么在$t$时刻向量$\vec{OP}(t)$与$OX$轴正方向的夹角等于$\omega t + \varphi$，因此向量$\vec{OP}(t)$的坐标为$(A\cos(\omega t + \varphi); A\sin(\omega t + \varphi))$，可得点$P(t)$在$OX$轴上的投影和轴$OY$上的点$P(t)$进行具有相同振幅和频率的简谐振动！因此，例如 $OX$ 轴上的点的简谐振动，可以解释为围绕 $O$ 点均匀旋转的某个矢量 $\vec{OP}(t)$ 投影在 $OX$ 轴上的振动。矢量$\vec{OP}(t)$的初始位置，即$\vec{OP}(0)$，决定了振荡的幅度（等于矢量$\vec{OP}(0)$的长度）和初始相位$\varphi = (\vec{OP}(0), \vec{OX})$； - 仅缺少频率。矢量$\vec{OP}(0)$称为振幅$A$、初始相位$\varphi$的简谐振动矢量图。

任务 1. 绘制以下简谐振动的矢量图：

a) $-3\cos\left(2t + \frac{\pi}{3}\right)$; b) $3\cos\left(2t + \frac{4\pi}{3}\right)$; c) $3\cos\left(-2t + \frac{2\pi}{3}\right)$; d) $3\sin\left(2t + \frac{\pi}{3}\right)$; e) $3\sin\left(-2t + \frac{\pi}{3}\right)$.

借助矢量图，已经很容易理解谐波振荡的加法。让我们绘制两个简谐振动（频率相同！）的矢量图：矢量 $\vec{OP}_1$ 和 $\vec{OP}_2$ (图 3)。那么这些振荡之和的矢量图将是矢量$\vec{OP} = \vec{OP}_1 + \vec{OP}_2$。实际上，

⟦folio 46⟧

图 3.

向量$\vec{OP}_1(t)$和$\vec{OP}_2(t)$在轴$OX$上的投影写如下：
$$x_1 = A_1 \cos(\omega t + \varphi_1),$$
其中$A_1 = |\vec{OP}_1|$，$\varphi_1 = (\vec{OP}_1, \vec{OX})$；
$$x_2 = A_2 \cos(\omega t + \varphi_2),$$
其中$A_2 = |\vec{OP}_2|$，$\varphi_2 = (\vec{OP}_2, \vec{OX})$。
它们的总和$\vec{OP}(t) = \vec{OP}_1(t) + \vec{OP}_2(t)$在$OX$轴上的投影等于$x_1 + x_2$，即$A_1 \cos(\omega t + \varphi_1) + A_2 \cos(\omega t + \varphi_2)$，因此矢量$\vec{OP}$实际上是最低简谐振动之和的矢量图。

现在请注意，向量 $\vec{OP}(t)$ 是从边 $OP_1(t)$ 和 $OP_2(t)$ 开始的平行四边形的对角线（参见 图 3）。由于向量 $\vec{OP}_1(t)$ 和 $\vec{OP}_2(t)$ 以相同的角速度旋转，因此整个平行四边形作为刚性图形旋转。因此，它的对角线以相同的角速度$\omega$旋转，使得矢量$\vec{OP}(t)$在轴$OX$（点$P(t)$的横坐标）上的投影与矢量$\vec{OP}_1(t)$和$\vec{OP}_2(t)$在轴上的投影产生相同频率$\omega$的简谐振动$OX$（点$P_1(t)$和$P_2(t)$的横坐标）。

很清楚如何计算这个和的幅度和初始相位（幅度是平行四边形的对角线，初始相位是这条对角线与$OX$轴的角度 - 参见教科书第59页第260号问题）。

任务 2. 绘制任务 1 中振荡 $a$ 和 $b$、d) 和 e) 之和的矢量图，并找出它们的振幅和初始相位。

利用矢量图，可以证明一个更重要的命题，即任何简谐振动都可以用公式$f(t) = a \cos \omega t - b \sin \omega t$来表示。让我们更详细地看看这个。

让我们有一个频率为$\omega$的简谐振动$A$ cos $(\omega t + \varphi)$，并令$\vec{OP}(0) = (A \cos \varphi; A \sin \varphi)$为其在坐标系$XOY$中的矢量图。给定坐标系 $XOY$，令 $\vec{i}$ 和 $\vec{j}$ 为相互垂直的单位向量（参见教科书“代数与分析原理，9”第 70 § 14 段）。然后$\vec{OP}(0) = A \cos \varphi \cdot \vec{i} + A \sin \varphi \cdot \vec{j}$。现在假设向量$\vec{i}$和$\vec{j}$与向量$\vec{OP}(t)$绕点$O$均匀且同时旋转，且角速度$\omega$与向量$\vec{OP}(t)$相同。然后$\vec{i}(t) = (\cos \omega t; \sin \omega t), \vec{j}(t) = (-\sin \omega t; \cos \omega t)$。由于向量$\vec{OP}(t)$，$\vec{i}(t)$和$\vec{j}(t)$像刚性图形一样旋转，并且在初始时刻$\vec{OP}(0) = a \cdot \vec{i} + b \cdot \vec{j}$（$a = A \cos \varphi, b = A \sin \varphi$），那么在$t$时刻，向量$\vec{OP}(t)$的第x坐标，即数字$A \cos (\omega t + \varphi)$将等于向量$a \cdot \vec{i}(t)$和$b \cdot \vec{j}(t)$的$x-x$坐标之和，即$A \cos (\omega t + \varphi) = a \cos \omega t - b \sin \omega t$。

因此，我们将简谐振动 $A$ cos $(\omega t + \varphi)$ 表示为相同频率 $\omega : a \cos \omega t - b \sin \omega t$ 的两个简谐振动之和（毕竟，正弦图是相位偏移四分之一周期的余弦图。
