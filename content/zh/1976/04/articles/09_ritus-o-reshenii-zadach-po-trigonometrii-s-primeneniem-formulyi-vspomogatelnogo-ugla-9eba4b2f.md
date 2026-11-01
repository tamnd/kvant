---
id: 1976-4-ritus-o-reshenii-zadach-po-trigonometrii-s-primeneniem-formulyi-vspomogatelnogo-ugla-9eba4b2f
issue: kvant_1976_4
year: 1976
number: "4"
title: 【利用辅助角公式求解三角问题】
authors:
  - Ритус В.
rubric: raznoe
page_first: 43
page_last: 44
page_labels: 41-42
tag: T8SY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: bd3b483aaf566b608304bba36f96d0ec2baaa02bd900256ea3111a0c69e0cbf3
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/09_ritus-o-reshenii-zadach-po-trigonometrii-s-primeneniem-formulyi-vspomogatelnogo-ugla-9eba4b2f.md
source_content_sha256: d0e1b78c8cb15c2839d6cc29e535b5b46c093b36201451431f171d201255ca2e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

质量为 1.31 × (1000+x) e，因此含有 0.5 × 1.31 × (1000 + x) e 的纯酸。我们得到方程

$$1,51x = 0,5 \cdot 1,31(1000+x),$$

其中 $x \approx 766$ 毫升。

人们可以提出不同的观点。 $x$ml纯酸的质量等于1.51×e，1000ml水的质量为998e，50％溶液的质量为1.31(1000+x)e。由于组分的总质量与溶液的质量一致，我们得出方程

$$1,51x + 998 = 1,31(1000+x),$$

其中 $x \approx 1560$ 毫升。

我们看到这两种解决方案会导致不同的结果。事实上，这两种解决方案都是错误的。然而，第二个结果的严重谬误是非常明显的：如果在一升水中加入一升半以上的纯酸，那么所得溶液的浓度将高于50%。

错误的原因是两个解决方案中使用的体积相加性假设都不成立。当酸与水混合时，会形成大量液体；它可以通过分子吸引力之间的力的作用来解释（水分子靠近酸分子，渗透到它们之间的“空隙”）。因此，解决液体混合问题应基于质量守恒定律：溶液各组分的总质量等于溶液本身的质量。

所考虑问题的正确解决方案如下。 $x$ ml 纯酸的质量等于 1.51 x e，1000 ml 水的质量为 0.998 x 1000 = 998 e)，因此溶液各组分的总质量为 (998 + 1.51 x) e（50%酸溶液的实际体积为$\frac{998+1,51x}{1,31}$ ml）。求50%溶液中纯酸的质量与倒入的100%酸的质量一致，我们得到方程1.51x=0.5·(998+1.51x)，由此我们找到$x \approx 661$ml。

你对吧

1. 对于密度为 1.290 e/cm3 的自动溶解电池，需要在 15 °C 下将多少体积的 91% 硫酸加入到 1 升水中才能获得电解液？

91%硫酸在15℃时的密度为1.825e/cm3； 15℃时密度为1.290e/cm3的硫酸浓度为38.03%； 15 °C 时水的密度为 0.999 e/cm3。

2. 需要将多少水倒入 800 毫升 100% 乙酸中才能得到 65% 的溶液？混合将在 20 °C 下进行。

100% 乙酸在 20 °C 时的密度 - 1.0498 e/cm3；水 - 0.998 e/cm3。

A. 亚洲（奥德卡）

Nechen Kong Qui（河内，刚果民主共和国）在给编辑的信中向杂志读者提出了一个相当有趣的几何事实，数学爱好者无疑会欣赏这一事实。给定问题的解决方案可以很好地测试 Planietri 课程中材料的先进程度。

3. 在底平面上有一个直径相互垂直的圆$AB$和$CD$以及一条与直线$AB$平行的直线$m$。通过圆的点 $T$（与点 $C$ 和 $D$ 不同）绘制一条切线，与线 $AB$ 相交于点 $K$ ，线 $m$ 相交于点 $M$ 。设$E$和$F$分别为线$m$与线$KC$和$KD$的交点。证明线段 $ME$ 和 $MF$ 的长度乘积既不依赖于圆的半径，也不依赖于圆上点 $T$ 的选择。

在三角变换中，特别是在求解三角方程时，用以下形式表示表达式 $c \sin x + b \cos x$ 会很有用：

$$a \sin x + b \cos x = \sqrt{a^2 + b^2} \sin(x + \varphi).$$

⟦folio 42⟧

此式中出现的角度 φ 通常称为辅助角。众所周知，是由对应关系决定的

$$\sin \varphi = \frac{b}{\sqrt{a^2 + b^2}}, \quad \cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}$$

直到术语$2n\pi$（其中$n = 0, \pm 1, \pm 2, \ldots$）。因此，只要指示位于某个长度$2\pi$的区间内的一个角 φ 就足以获得辅助角的所有其他值。

让我们注意下面这个简单的辅助角显式公式，它在学校教科书上没有，但是很方便解决问题，特别是带参数的方程。让我们选择区间$-\pi < \varphi \leq \pi$作为长度$2\pi$的区间。则该区间内唯一满足一般关系式（2）的角度 φ 由下式确定

$$\varphi = \begin{cases} \arccos \frac{a}{\sqrt{a^2 + b^2}}, & \text{ если } b \geqslant 0; \\ -\arccos \frac{a}{\sqrt{a^2 + b^2}}, & \text{ если } b < 0. \end{cases}$$

事实上，无论$b$的符号如何，两个角度（3）都满足第二个关系（2），并且对于$b \geqslant 0$来说，区间$-\pi < \varphi \leq \pi$中的第一个关系（2）仅由$\varphi = \arccos \frac{a}{\sqrt{a^2 + b^2}}$满足，而对于$b < 0$仅$\varphi = -\arccos \frac{a}{\sqrt{a^2 + b^2}}$满足。

应该记住，单独采用的关系式 (2)（或者从它们得出的关系式$tg \varphi = b/a$，也单独采用）都不足以找到辅助角：它在长度$2\pi$的区间内定义了两个角度，其中只有一个满足一般关系式（2）。因此，如果$a = -1$，$b = \sqrt{3}$，则方程$tg \varphi = b/a$在区间$-\pi < \varphi \leq \pi$中有两个根：$-\pi/3$和$2\pi/3$，但仅对其中第二个根（1）有效。

从下面的例子中可以很容易地看出公式(3)的优点。

示例 2（MIEM，1972）。解方程

$$\sin^6 x + \cos^6 x = a \sin 4x,$$

埃德$a - \text{параметр}$。

通过降低方程左侧的幂两次，我们将其简化为以下形式

$$a \sin 4x - \frac{3}{8} \cos 4x = \frac{5}{8},$$

由此，利用公式（1）和（3），我们得到：

$$\sqrt{a^2 + \frac{9}{64}} \sin (4x + \varphi) = \frac{5}{8},$$

$$\varphi = -\arccos \frac{a}{\sqrt{a^2 + \frac{9}{64}}}.$$

很明显，该方程存在一个解

$$\frac{5}{8} \leq \sqrt{a^2 + \frac{9}{64}},$$

即在 $|a| \geqslant 1/2$ 处，给出公式

$$x = \frac{(-1)^n}{4} \arcsin \frac{5}{\sqrt{64a^2 + 9}} + \frac{1}{4} \arccos \frac{8a}{\sqrt{64a^2 + 9}} + \frac{\pi n}{4},$$

其中$n$是一个整数。公式（3）的使用导致了结果的非常紧凑的表示（参见 «Kvant», 1973, No. 7, pp. 47, 60-61 中给出的答案）。

V·鲁姆斯（莫斯科）

* *

如您所知，如果找到未知方程的替代项，则可以求解一些“非标准”方程。尝试为八年级学生 S. Akhmedov（阿塞拜疆苏联 Minjevny 站）发送给编辑的方程找到这样的替代。
