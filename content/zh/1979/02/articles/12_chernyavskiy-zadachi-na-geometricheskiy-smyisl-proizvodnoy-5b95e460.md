---
id: 1979-2-chernyavskiy-zadachi-na-geometricheskiy-smyisl-proizvodnoy-5b95e460
issue: kvant_1979_2
year: 1979
number: "2"
title: 导数的几何意义问题
authors:
  - Чернявский М.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 45
page_labels: 40, 41, 43
tag: Z4Y5
lang: zh
source: kvant_digital
extraction: vision
content_sha256: fed87ebf23d88049d7f97b765d22cd661177bdb4df3c6caacc5e163bd9fe35ac
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/12_chernyavskiy-zadachi-na-geometricheskiy-smyisl-proizvodnoy-5b95e460.md
source_content_sha256: 26ac8a720136214cbd2101bc7daf2de462a03fdee70d3e195d49db455ef3f189
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

M·切尔尼亚夫斯基

锻炼
关于导数的几何意义

在教科书“代数和分析的开始”的第 10 节中，给出了可微函数图的切线方程，并解释了导数的几何意义 *)。本说明中讨论的任务利用了研究分析方法的几何事实的机会。

从物理课程中我们知道，投影仪反射镜的形状通常是旋转抛物线形状。这可以通过以下问题中考虑的抛物线的性质来解释：

任务1.证明从抛物线$y=ax^2$的焦点$F(0, 1/4a)$发出的光线在平行于其对称轴**）的任意点处发生反射。

解决方案。令 $M(x_0; ax^2)$ 为抛物线 (图 1) 的任意点。根据光反射定律，入射光线FM和反射光线MA与切线MP所成的角度彼此相等。 （在 图 1：$\hat{1}=\hat{2}$）。我们需要证明 MA | Oy，它等于等式 $\hat{2}=\hat{3}$，或者考虑到前一个等式，等于等式 $\hat{1}=\hat{3}$。后者由三角形 PFM 的等边性得出。所以，只要证明$FM|=|FP|$就足够了。

$$|FM| = \sqrt{x_0^2 + \left(ax_0^2 - \frac{1}{4a}\right)^2} = \sqrt{a^2x_0^2 + \frac{1}{2}x_0^2 + \frac{1}{16a^2}} = \left|ax_0^2 + \frac{1}{4a}\right|.$$

为了计算 $|FP|$，我们写出正切 MP 的方程。由于$y'=2ax$，该方程为$y - ax_0^2 = 2ax_0(x - x_0)$。其中的字段是$x=0$，我们来求点$P$的纵坐标：$y = -ax_0^2$。因此，$|FP| = \left| \frac{1}{4a} - (-ax_0^2) \right| = \left| ax_0^2 + \frac{1}{4a} \right| = |FM|$。

如果已知切点，则它们可以轻松解决需要找到给定函数图形的切线角度系数或切线方程的问题。然而，在应用问题中，有时需要从一些附加条件中找到该函数。我们在下一个问题中会遇到这样的情况：

任务2.自动机场地轮廓为抛物线形状（图2），轴线垂直穿过场地中部，中心部分高​​度为10 m，底边长度为120 m。场地公共端的饱和斜率应该是多少？

解决方案。请注意，饱和度斜率是切线段的斜率

图 1.

⟦folio 41⟧

图 2.

与点 $A$ 和 $B$ 处的抛物线相关。让我们选择一个如 图 2 所示的坐标系。然后该系统中的抛物线由$y = ax^2 + 10$ 形式的方程给出。由于点 $A(60; 0)$ 位于抛物线上，$a = -\frac{1}{360}$。

因此，抛物线方程为$y = -\frac{x^2}{360} + 10$。因此$y' = -\frac{x}{180}$。

在点$A$：$tg\alpha = y'(-60) = \frac{1}{3}$，$\alpha = \arctg\frac{1}{3}$。

在点$B$：$tg\beta = y'(60) = -\frac{1}{3}$，$\beta = \pi - \arctg\frac{1}{3}$。

有时您需要检查给定的直图是否涉及给定的函数。为此，检查以下两个必要条件就足够了：

图 3.

聚合并足以触摸：

1. 函数的直线和图形有一个共同点。
2. 一般来说，任意给定函数的值等于给定直线的斜率。

问题3.直线$x + 4y - 4 = 0$是否与双曲线$y = \frac{1}{x}$相交？

解决方案。系统解决了
$$\begin{cases} x + 4y - 4 = 0, \\ xy = 1, \end{cases}$$

我们找到直线和双曲线的公共点 (2; 1/2)。任意函数$y = \frac{1}{x}$等于$y' = -\frac{1}{x^2}$，其交点处的值为$-y'(2) = -\frac{1}{4}$。但直线的斜率是相同的。这意味着这条线在点 (2; 1/2) 处接触双曲线。

问题 4. 求从点 $A$ 可以看到抛物线 $y = x^2$ 的角度。 (2;-1)。

解决方案。显然，这个角度是由穿过点$A$（图3）的抛物线的两条切线形成的。让我们用 $\alpha$ 表示所需的角度，用 $\alpha_1$ 和 $\alpha_2$ 表示切线与轴 $Ox$ 的倾斜角度。然后
$$tg\alpha = tg(\alpha_2 - \alpha_1) = \frac{tg\alpha_2 - tg\alpha_1}{1 + tg\alpha_1 \cdot tg\alpha_2} = \frac{k_2 - k_1}{1 + k_1 \cdot k_2},$$
其中 $k_1$ 和 $k_2$ 表示角度系数

⟦folio 43⟧

小便。 5.

小便。 6.

小便。 7.

以横坐标$x_0$为点，满足以下两个条件是充分必要的（对比问题3之前制定的条件）：

1) $f(x_0) = \varphi(x_0)$;
2) $f'(x_0) = \varphi'(x_0)$.

任务 6. 中心位于正带 Oy 上、半径为 1 的圆与抛物线 $y = x^2$ 相切。找到切点 $M$ 和圆心 $C$ 的位置。

解决方案。让我们用 $C(0; a)$ 表示圆心。那么圆的方程就是$x^2 + (y-a)^2 = 1$。

我们感兴趣的是抛物线与下半圆 (图 5, 6) 的切线，其方程的形式为 $y = a - \sqrt{1-x^2}$。让我们用$x_0$表示切点的横坐标。使用条件 1)、2)，我们得到

$$\begin{cases} a - \sqrt{1-x_0^2} = x_0^2, \\ \frac{x_0}{\sqrt{1-x_0^2}} = 2x_0, \end{cases}$$

那是

$$\begin{cases} \sqrt{1-x_0^2} = a - x_0^2, \\ x_0 \left(1 - 2\sqrt{1-x_0^2}\right) = 0. \end{cases}$$

一种解显然是$x_0 = 0$，$a = 1$ (图 6)。第二个方程还有两个根$x_0 = \pm \frac{\sqrt{3}}{2}$。它们对应于相同的值$a = \frac{5}{4}$。

因此，我们得到了一个更有趣的情况：以 $C\left(0; \frac{5}{4}\right)$ 为中心的圆，在点 $M_1\left(\frac{\sqrt{3}}{2}; \frac{3}{4}\right)$ 和 $M_2\left(-\frac{\sqrt{3}}{2}; \frac{3}{4}\right)$ (图 5) 处与抛物线相切。

任务 7. 在恒定力作用下，加速度为 $2 m/c^2$、初速度为零的直线运动点。开始移动3秒后，力停止作用，点开始以相同速度匀速移动。求点的运动规律并画出运动图。

解决方案。让我们选择一个坐标系，以便在初始时刻该点位于坐标原点：$s = 0$ at $t = 0$。那么对于$0 \leq t \leq 3$，我们有$s = t^2$。对于$t \geq 3$，运动图是抛物线$s = t^2$的切线的一部分，在点(3, 9)处沿$t$(图7)增加的方向绘制。因此他的方程的形式为

$$s - 9 = 6(t - 3)$$

或者

$$s = 6t - 9.$$

因此，运动定律op-
