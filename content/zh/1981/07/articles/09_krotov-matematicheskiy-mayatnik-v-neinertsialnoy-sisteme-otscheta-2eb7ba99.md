---
id: 1981-7-krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99
issue: kvant_1981_7
year: 1981
number: "7"
title: 非惯性参考系中的数学摆
authors:
  - Кротов С. С.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 35
page_labels: 32-33
tag: TIZ9
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 29856e0c3fe368757790a26c73d7db7dc25574b0ab34b016cb3d944859c0578b
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/09_krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99.md
source_content_sha256: 3568fd55c17289ba1272bd3a0eb3bd92177ff5c05f08f4de4ee5bf8d8d4ab7f5
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 32⟧

应远小于速度沿切线的变化$\Delta v$，即
$$\Delta v_r \approx a_r \Delta t = \left( \frac{e v_{cp} B}{m} \right) \Delta t = \frac{e \cdot \Delta v \cdot B \cdot \Delta t}{2m} \ll \Delta v.$$
因此$\Delta t$的约束：
$$\Delta t \ll \frac{2m}{eB}.$$
所以，对于 $B = 10^{-4}$ T
$$\Lambda t \ll \frac{2 \cdot 9 \cdot 10^{-31}}{1,6 \cdot 10^{-19} \cdot 10^{-4}} \approx 10^{-7} \text{ с}.$$
$r = 10^{-2}$米处
$$\Delta v = \frac{1,6 \cdot 10^{-19} \cdot 10^{-4} \cdot 10^{-2}}{2 \cdot 9 \cdot 10^{-31}} \approx 10^{5} \text{ м/c} \ll c.$$
A·齐伯曼

非惯性报告系统中的数学数学书

描述数学矩阵的运动（失重尼特上的小负载）的任务是什么？我们必须知道负载的初始位置和初始速度，才能在随后的任何时间确定其位置。换句话说，我们必须确定依赖关系$x = x(t)$和$y = y(t)$的显式形式，其中$x$和$y$是确定重物在其运动平面中的位置的坐标。

让我们考虑描述当其悬挂点相对于地面静止时长度为$l$的数学矩阵的运动的方程。让我们选择坐标轴$OX$和$OY$，如图1所示。让在矩阵运动过程中的某个时间点，螺纹形成一个垂直角度$\varphi$（角度$\varphi$不存在于轴$OY$逆时针方向）。负载运动方程 - 牛顿定律方程 P
$$m \vec{a} = m \vec{g} + \vec{T} \tag{1}$$
（$\vec{T}$ 是螺纹的张力）在轴 $OX$ 和 $OY$ 上的投影具有以下形式
$$m a_x = -T \sin \varphi, \tag{2}$$
$$m a_y = m g - T \cos \varphi. \tag{3}$$
由于运动过程中尼特长度矩阵不变，因此坐标$x$和$y$之间存在对应关系（运动学联系）
$$x^2 + y^2 = l^2,$$
为了描述矩阵的运动，知道任何一个坐标的时间依赖性就足够了。

描述矩阵运动的更自然的坐标是角度$\varphi$。

找到$\varphi(t)$的依赖性，从而确定坐标$x$和$y$的时间依赖性：
$$x(t) = l \sin (\varphi(t)),$$
$$y(t) = l \cos (\varphi(t)).$$
让我们重写方程（2）和（3），代入其中的值
$$a_x = v'_x = x'' = -l(\varphi')^2 \sin \varphi + l\varphi'' \cos \varphi,$$
$$a_y = v'_y = y'' = -l(\varphi')^2 \cos \varphi - l\varphi'' \sin \varphi$$
将 (2) 乘以 $\cos \varphi$，将 (3) 乘以 $\sin \varphi$。我们得到
$$l\varphi'' \cos^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi = 0, \tag{2}$$
$$-l\varphi'' \sin^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi - g \sin \varphi = 0. \tag{3}$$
$(2')$减去$(3')$，得到满足函数$\varphi(t)$的微分方程：
$$\varphi'' + \frac{g}{l} \sin \varphi = 0. \tag{4}$$
在尼特矩阵与垂直sin$\varphi \approx \varphi$偏差较小的情况下，方程（4）变为方程
$$\varphi'' + \frac{g}{l} \varphi = 0,$$
这是频率为$\omega = \sqrt{\frac{g}{l}}$的简谐振动方程。该方程的通解具有以下形式
$$\varphi = \varphi_0 \cos \left( \sqrt{\frac{g}{l}} t + \Phi \right),$$
其中$\varphi_0$是振荡幅度，$\Phi$是初始相位。量 $\varphi_0$ 和 $\alpha_0$ 在初始条件下唯一确定。

现在让数学运动矩阵的悬浮点相对于静止惯性报告系统 (图 2) 加速$\vec{b}$。重物（点$A$）相对于该系统的加速度$\vec{a}$可以为

⟦folio 33⟧

但将其表示为向量和
$$\vec{a} = \vec{a}' + \vec{b},$$
其中$\vec{a}'$是点$A$相对于非惯性报告坐标系的加速度，该点相对于非惯性报告坐标系以加速度$\vec{b}$移动。等式（1）现在将写成如下：
$$m\vec{a}' + m\vec{b} = m\vec{g} + \vec{T}.$$
从这里
$$m\vec{a}' = m\vec{g} + \vec{T} - m\vec{b} = m(\vec{g} - \vec{b}) + \vec{T}.$$
方程（5）在形式上与方程（1）的不同之处在于存在一个常数向量$m(-\vec{b})$，它具有力的量纲。因此，如果我们想在相对于惯性系统以恒定加速度$\vec{b}$运动的非惯性报告系统中使用牛顿PN定律，那么对于作用在重量上的真实力——重力$m\vec{g}$和线的张力$\vec{T}$，我们必须添加一个常数向量$m(-\vec{b})$。这个矢量称为惯性力。在方程（5）中，我们将矢量 $m(-\vec{b})$ 与力矢量 $m\vec{g}$ 组合起来。在这种表示法中，(5) 表示牛顿定律中的 PJ 方程，其中作用有线的张力$T$ 和扮演重力作用的力$m(\vec{g} - \vec{b})$。这样一种新的“重力”$m(\vec{g} - \vec{b})$的引入，给了我们一个新的“水平”方向——垂直于新的垂直。

从方程(1)到方程(4)给出的变换也适用于方程(5)。您只需要记住，非惯性报告框架中矩阵的平衡位置由新垂直方向给出；矩阵偏离平衡位置的角度也是从该垂直线测量的；矩阵（权重）的速度是其相对于以加速度$\vec{b}$移动的报告系统的速度。

图 1.

图 2

在非惯性报告系统中使用能量关系（机械能守恒定律）时，我们可以使用公式符号
$$m\vec{g}'h' + \frac{m(v')^2}{2} = \text{const},$$
其中 $g' = |\vec{g} - \vec{b}|$、$h'$ 是高度，沿新垂直方向没有摆锤，$v'$ 是物体相对于非惯性报告系的速度。垂直于向量 $\vec{g} - \vec{b}$ 的平面现在成为等效曲面。

现在让我们继续讨论问题书«Kvant»中的解决方案���题 F663。让我们回忆一下它的条件。

F663。一辆重型车沿水平面以速度 $v_0$ 移动，并行驶到与水平面成角度 a 的倾斜面上。游泳平面之间的过渡。一个球挂在一根 $l$ 长的线上。当小车被带到斜面上时，摆动球的振幅是多少？

我们必须非常考虑矩阵相对于非惯性报告系统的运动——一辆小车的移动等于
