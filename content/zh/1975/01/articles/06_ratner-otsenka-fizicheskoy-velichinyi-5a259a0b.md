---
id: 1975-1-ratner-otsenka-fizicheskoy-velichinyi-5a259a0b
issue: kvant_1975_1
year: 1975
number: "1"
title: 物理量的估算
authors:
  - Ратнер Б. С.
rubric: osnovnye-stati
page_first: 24
page_last: 25
page_labels: 22-23
tag: VM3Z
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0d24c094661b792ff015f5a5c63ac8b45e7075dcd395a2a6c68d0fd5171556dc
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/06_ratner-otsenka-fizicheskoy-velichinyi-5a259a0b.md
source_content_sha256: 910df5be6c9483fae9dd29a7472b792517925992cd234975bfbcb6b5ae9552ce
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

## 物理量的估算
学士学位拉特纳

在物理学以及其他科学中，通过计算或实验获得的各种量的值的确定精度不同。在某些情况下，最准确地了解物理量的值很重要，而在其他情况下，估计其近似值就足够了。这种估计的准确性可能会从一个数量级到几个百分点不等。

作为估计的、不精确计算的一个例子，我们会以一种不寻常的方式找到数学摆的振荡周期 $T$。从学校物理课程中得知，当摆线偏离垂直方向的角度较小时，可以通过公式$T = 2\pi \sqrt{\dfrac{l}{g}}$非常准确地找到$T$值，其中$l$是摆线的长度，$g$是自由落体的加速度。因此我们的例子纯粹是

⟦figure⟧
图 1.

⟦folio 22⟧

⟦column⟧

说明性的——在实际情况下，没有人会粗略地估计一个已经确切知道的值。但我们会立即知道最终的估计与事实有多接近。

初始时刻，让摆锤位于点 $A$ - 距平衡位置 $B$ 距离最大的点，同时螺纹与垂直方向形成小角度 $\alpha$ (图 1)。振荡周期 $T$ 是时间周期 $t$ 的四倍，在此期间，摆锤将描绘弧线 $AB$：

$$T = 4t = 4\,\frac{\smile AB}{v_{\mathrm{ср}}},$$

其中$v_{\mathrm{ср}}$是该路段的平均速度。

由于角度$\alpha$较小，可用弦$AB$代替圆弧$\smile AB$。由直角三角形 $ACO$ 和 $ACB$

$$AC^2 = l^2 - (l-h)^2$$

和

$$AC^2 = AB^2 - h^2,$$

因此，

$$AB = \sqrt{2lh}.$$

我们假设

$$v_{\mathrm{ср}} = \frac{v_0 + v_t}{2} = \frac{0 + \sqrt{2gh}}{2}.$$

这里$v_0$是初始时刻的速度，$v_t$是摆通过平衡位置时的速度。这种假设的不准确性是显而易见的，因为它对应于匀加速运动，即恒定力影响下的运动。在我们的例子中，球受到随时间变化的力的作用——重力的切向分量。不幸的是，使用初等数学不可能获得更接近真实值的值$v_{\mathrm{ор}}$。

将$\smile AB$和$v_{\mathrm{ср}}$的值代入振荡周期$T$的表达式中，得到

$$T = 8 \sqrt{\frac{l}{g}}.$$

⟦figure⟧
图 2.

⟦figure⟧
图 3.

估算得到的振荡周期值比真实值大约大27%。造成这种差异的原因是什么？基本上，根据我们选择的平均速度值，用弦代替圆弧并不重要。 图 2 显示了两种情况下力与位移的关系图：简谐振动，当力 $F_2$ 接近平衡位置时线性减小，并用于估计匀加速运动，当力 $F_1$ 恒定时。图表下方的面积等于运动的能量，自然也必须相等。现在让我们尝试比较一下

⟦column⟧

两种情况下花费的时间间隔。为此，我们使用依赖关系 $v = v(t)$ (图 3)。匀加速运动时，图形$v = v_1(t)$是一条直线。对于谐波振荡，曲线 $v = v_2(t)$ 最初走得更高（$t = 0$ 处曲线的斜率正切是直线正切的两倍），在路径中间，曲线的斜率大致相同，而在末端，曲线 $v_2(t)$ 的斜率正切等于 0。但两条曲线下的面积必须相等，因为它们等于路径。因此，$t_1 > t_2$对应于振荡周期值差异的符号。
