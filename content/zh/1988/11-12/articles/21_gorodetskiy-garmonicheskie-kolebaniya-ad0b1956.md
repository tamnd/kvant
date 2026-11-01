---
id: 1988-11-12-gorodetskiy-garmonicheskie-kolebaniya-ad0b1956
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: 简谐振动
authors:
  - Городецкий Е. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 69
page_labels: 64, 65, 67
tag: CGCS
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8bb96c890985452fb474baf5f3fc3750a1f50d70a40d554804088f7013f78b85
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/21_gorodetskiy-garmonicheskie-kolebaniya-ad0b1956.md
source_content_sha256: 8dac022000be44baddba29443b853d8519904fe7a3e140f93170d1b4279e82e7
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 64⟧

简谐振动

物理和数学科学候选人
E·E·戈罗德茨基

任何机械系统中发生自由简谐振动的机制始终是相同的。这种出现的目的是使系统远离稳定的平衡位置。本文将仅关注谐波振荡。尽管针对每种具体情况产生的自然现象可能不同，但描述振动的运动方程是相同的。

大多数振荡问题看起来都是这样的。给定的某个系统可以围绕其位置振荡。

纳亚平衡。产生振荡的方法是已知的，即初始条件是指定的。问题一：求振荡的频率（或周期）。问题二：求出它们的振幅和初始相位，并写出振荡值对时间的依赖性。问题三：找出振荡量在什么时间（或周期的几分之一）后呈现给定值。我们将通过找到所附矩阵的一个众所周知的例子来说明这些问题的答案。我们制定了解决此类问题的通用算法。

问题 1. 给定图 1 所示的系统。体重 m，弹簧刚度 k。物体从右侧的平衡位置位移 x0 并被推向左侧，速度为 v0。找出振荡的频率、振幅和初始相位。没有摩擦。

让我们将物体的牛顿第二定律写成 X 轴的投影：

⟦folio 65⟧

$$F_{\text{упр}} = ma,$$
其中$F_{\text{упр}}$是弹簧作用在物体上的弹力，$a$是物体的加速度。如果物体在任意时刻$t$与平衡位置的偏差等于$x$，则根据胡克定律$F_{\text{упр}} = -kx$。物体沿某个第二任意坐标及时的加速度：$a = x''$。现在物体运动方程可以写成$mx'' + kx = 0$的形式。

该方程与任何其他振荡方程一样，是两项之和：其中一项包括未知的时间函数（在本例中为 $x$），另一项为该时间的第二个任意函数（$x''$）。

众所周知，该方程的解是调和函数

$$x = x_m \sin(\omega t + \varphi_0).$$

这里 $x_m$ 是振幅，$\omega$ 是频率（更准确地说，是循环频率），$\varphi_0$ 是振荡的初始相位。通过直接将解代入方程，很容易找到振荡频率：

$$\omega = \sqrt{\frac{k}{m}}.$$

请注意（这一点非常重要），收到的答案是一般规则的特例。如下。如果获得振荡方程，则振荡频率的平方等于未知函数的系数（在本例中为$x(t))$）与时间上的第二个任意函数的系数（$x''(t))$.

那么振幅$x_m$和初始相位$\varphi_0$呢？为了确定这些量，让我们再次回到条件：身体向右移动 $x_0$，并以 $v_0$ 的速度向左推动。这里

$$\text{Puc. 1.}$$

我们正在讨论振荡是如何被激发的，即初始条件。在不同的任务中，它们可以以不同的方式指定，但它们的含义始终相同：在初始时刻，指定某些量的具体值。在我们的例子中，给出了混合物体及其速度（更准确地说，速度在 $X$ 轴上的投影）的值：

在 $t = 0$ $x = x_0$ 和 $v = -v_0$。

因为我们已经知道混合对时间的依赖性：

$$x = x_m \sin(\omega t + \varphi_0),$$

不难发现速度：

$$v = x' = x_m \omega \cos(\omega t + \varphi_0).$$

让我们将 $t = 0$ 放入这些表达式中：

$$x_0 = x_m \sin \varphi_0,$$

$$-\frac{v_0}{\omega} = x_m \cos \varphi_0.$$

这是两个带有两个未知数的方程：$x_m$ 和 $\varphi_0$。将一个方程除以另一个方程，我们得到

$$tg \varphi_0 = -\frac{x_0 \omega}{v_0},$$

或者

$$\varphi_0 = \arctg \left(-\frac{x_0}{v_0} \sqrt{\frac{k}{m}}\right).$$

通过对两个方程进行平方并相加，我们发现

$$x_m^2 = x_0^2 + \frac{v_0^2}{\omega^2},$$

或者

$$x_m = \sqrt{x_0^2 + \frac{mv_0^2}{k}}.$$

问题 2. 位于平衡位置的物体（参见问题 1）被赋予向右的速度 $v_0$。找出：a）在什么时间段之后系统的势能首先变得比动能大三倍，b）在什么时间之后物体的速度首先变成场。

a) 当物体外部振荡时，系统有储备的势能方程

$$W_p = \frac{kx^2}{2} = \frac{kx_m^2 \sin^2(\omega t + \varphi_0)}{2}$$

和动能

$$W_k = \frac{mv^2}{2} = \frac{mx_m^2 \omega^2 \cos^2(\omega t + \varphi_0)}{2}.$$

在想要的时刻$t$

⟦folio 67⟧

在平衡位置，身体浸入水中的深度$l_0$由重力$mg$和浮力$F = \rho_B Sl_0 g$的大小决定（这里$\rho_B$是水的密度）：

$$mg = \rho_B Sl_0 g.$$

在振荡过程中，例如当物体深度等于$l_0 + y$时，牛顿第二定律可写为：

$$mg - \rho_B S(l_0 + y)g = ma,$$

其中$a = y''$。从第二个方程中减去第一个方程，我们得到

$$- \rho_B Sgy = my''.$$

或者

$$y'' + \frac{\rho_B Sg}{m} y = 0.$$

这是您已经熟悉的振荡方程。他的解决方案如下所示：

$$y = y_m \sin(\omega t + \varphi_0),$$

其中$\omega = \sqrt{\frac{\rho_B Sg}{m}}$。

为了确定幅度和初始相位，我们转向初始条件：

在 $t = 0$ $y = 0$ 和 $v = v_0$。

从 $v = y' = y_m \omega \cos(\omega t + \varphi_0)$ 开始，我们得到

$$y_m \sin \varphi_0 = 0$$ 和 $y_m \omega \cos \varphi_0 = v_0$。

从这里

$$\varphi_0 = 0$$ 和 $y_m = \frac{v_0}{\omega} = v_0 \sqrt{\frac{m}{\rho_B Sg}}$。

问题 5. 气体圆柱法由质量 $m$ 和横截面积 $S$ (图 4) 的活塞封闭。平衡时，活塞距容器底部 $l$ 的高度。在某个时刻，活塞从平衡位置向下移动 $h_0$ 并释放。确定振荡的频率、初始相位和振幅：

$$\omega = \sqrt{\frac{mg + p_a S}{ml}},$$

$\varphi_0 = \frac{\pi}{2},$ $y_m = h_0$.

问题6. 求倒入U 形管中的液体的振动频率（图 5）。液体质量$m$，密度$\rho$，管横截面积$S$。

这里最容易使用能源方面的考虑。
