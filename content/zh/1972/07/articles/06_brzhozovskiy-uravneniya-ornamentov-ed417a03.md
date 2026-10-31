---
id: 1972-7-brzhozovskiy-uravneniya-ornamentov-ed417a03
issue: kvant_1972_7
year: 1972
number: "7"
title: 装饰方程
authors:
  - Бржозовский М. И.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 16, 18
tag: 6QCT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c3d5a7256db63a79914c61e78fb012307231ae3e8ff41071e1ecbe9bcabf04f7
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/06_brzhozovskiy-uravneniya-ornamentov-ed417a03.md
source_content_sha256: dc0048aed7d81355b9d8b00a490b83d86e40b70d221a1f567da671b62d58bab2
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

装饰方程
布若佐夫斯基

通过正确选择方程，您可以获得各种各样的、有时甚至非常奇怪的图片。例如，您可以得到图 A处显示的“rozicia”。如何做到这一点？首先，我们必须记住，数平面被称为所有实数对的集合（参见 A. N. Kolmogorov 的文章“What is the graph of a function”，«Kvant» No. 2，1970）。条件数平面上的任何点集都称为由方程 $f(x, y)=0$ 描述的几何图形。

特别是，我们可以考虑所有实数对$(x, y)$的集合，其中$f(x, y)=0$，其中$f(x, y)$是给定的表达式。在这种情况下，所得到的几何图形可以用方程 $f(x, y)=0$ 来描述。

因此，方程 $x^2-y=0$ 描述的是抛物线；方程 $x^2-y^2=0$ - 两条直线（$y=x$ 和 $y=-x$）相交于点 $(0, 0)$；方程$x^2+y^2=2$是以点$(0, 0)$为圆心，半径为$\sqrt{2}$的圆；方程 $|x|+|y|=1$ 是一个以点 $(0, 0)$ 为中心、顶点位于坐标轴上的正方形。

现在考虑以下方程：

$$\left(x+y\mathrm{ctg}\frac{\pi n}{32}\right)\sqrt{\frac{x^2}{25}+\frac{y^2}{49}-1} = 0$$

(1)

图A.
图 B.
图V.

⟦folio 16⟧

图1）。同一坐标系中圆$F_1$的方程写成以下形式

$$ (x - 2)^2 + y^2 = 1. $$

同理，我们可以得到圆整数$F_{-1}, F_2, F_{-2}, \dots, F_k, F_{-k}, \dots$。它们形成线性装饰。

如果函数$[x]$的距离是整数部分$x^*$，则整个整数圆可以用一个方程来描述。

这是等式：

$$ (x - 2 \left[ \frac{x + 1}{2} \right])^2 + y^2 = 1. $$

如果 $x$ 在区间 $[2k - 1, 2k + 1)$ 内，那么这个方程（可以很容易地验证）定义了其中一个圆：

$$ (x - 2k)^2 + y^2 = 1. $$

一般来说，如果$f(x, y) = 0$（在$a \leqslant x < a + T$）是某个几何函数的方程，我们将其称为主函数$F_0$，则通过沿$Ox$轴（其中$T > 0$，$k = 0, \pm 1, \pm 2, \dots$）平移$kT$单位从$F_0$获得的线性修饰由以下方程描述

$$ f \left( x - T \left[ \frac{x - a}{T} \right], y \right) = 0. $$

现在让$(b \leqslant y < b + S)$中定义的主函数$F_0$沿$Ox$轴（对角线）转移到$kT$单位，并沿$Oy$轴转移到$kS$单位。然后我们获得一个带有来自函数$F_i$的链接的线性装饰，位于沿着连接坐标原点$(0, 0)$与点$(T, S)$的线段，以及方程

$$ * ) \text{ Функция } [x], \text{ называемая «целой часть } x», \text{ определяется равенством } [x] = k, \text{ если } k \leqslant x < k + 1, \text{ где } k - \text{ целое число (наибольшее целое число, не превысходящое } x). $$

图 2.

这个装饰品将是

$$ f \left( x - T \left[ \frac{y - b}{S} \right], y - S \left[ \frac{y - b}{S} \right] \right) = 0 \quad (7) $$

（在$S \neq 0$）。使用$T = 0$，获得沿轴$Oy$定位的线性装饰。转换 (6) 和 (7) 的组合产生二维装饰的方程。

有趣的是，如果函数 $y = f(x)$ 定义在区间 $a \leqslant x < a + T$ 中，则函数

$$ y = f \left( x - T \left[ \frac{x - a}{T} \right] \right) $$

定义在整个实轴 $-\infty < x < \infty$ 上，具有周期 $T$ 的周期性，并在区间 $a \leqslant x < a + T$ 中与 $f(x)$ 重合。

函数$f \left( x - T \left[ \frac{x - a}{T} \right] \right)$称为函数$f(x)$的周期延拓。例如，如果$y = |x|$在区间$(-1, 1)$内，则

$$ y = |x - 2 \left[ \frac{x + 1}{2} \right] | $$

是周期函数$T = 2$，其图形如图2所示。

图 3 描绘了由半径为 $R = 1$ 的圆弧组成的线性装饰。这个装饰的基础是函数$F_0$（红色部分图3），由等式给出

$$ \left( x - \left[ \frac{x + 1}{2} \right] \right)^2 + \left( y - \left[ \frac{y + 1}{2} \right] \right)^2 = 1. $$

⟦folio 18⟧

图 7. 图 8. 图 9.

$F_0$ 是以原点为中心的六边形所有内点的集合，内切于半径为 $R = \frac{2}{\sqrt{3}}$ (图 7) 的圆。

该六边形的方程可以写为

$$\left| y \right| + \left| \frac{x \sqrt{3} - 1}{2} \right| + \left| \frac{x \sqrt{3} + 1}{2} \right| = 1,$$

因为对于这些且仅这些点，不等式得到满足

$$1 \leqslant | y | + \left| \frac{x \sqrt{3} - 1}{2} \right| + \left| \frac{x \sqrt{3} + 1}{2} \right| < 2.$$

要获得拼花地板的蓝色部分，您可以首先沿 $Ox$ 轴（在 $T_1 = 2\sqrt{3}, a = -\frac{2}{\sqrt{3}}$ 处）对 $F_0$ 进行一系列平移，然后对角线（在 $T_2 = \sqrt{3}, S = 3, b = -1$ 处）移动一条图形 $F_i$（在 $Ox$ 轴上）。拼花地板红色部分的方程是通过将$y$替换为$y - 2$而从构造的方程中获得的，而黄色部分则是将$y$替换为$y + 2$而获得。

如果使用极坐标，则会获得有趣的圆形图案。

在极坐标系中，每个点$A$有两个坐标（图8）：从该点到原点$O$的距离$\rho$和角度$\varphi$，形成具有固定轴的射线$OA$（在图8 - 与

轴$Ox$);该角度是从 $Ox$ 轴正方向（逆时针）测量的。 “原点”（点$O$）具有坐标$\rho = 0$和任意角度$\varphi$；任何其他点都有一个唯一定义的正坐标$\rho$和一个从该点到$2\pi$倍数定义的坐标$\varphi$。

在极坐标系中，与笛卡尔坐标系一样，图形可以用方程来描述。例如，圆 $F_0$ 在 图 1 上的方程将是 $\rho = 1$（正如我们所见，它比笛卡尔坐标系中的方程简单得多）。

若$f(\rho, \varphi) = 0$是扇区$0 \leqslant \varphi < \frac{2\pi}{n}$所包含的主要图形的方程，则类推式（6）有

$$f(\rho, \varphi - \frac{2\pi}{n} \cdot \left[ \frac{n\varphi}{2\pi} \right]) = 0$$

指定由数字$F_i$组成的圆形图案。

例如，可以写出内接于半径为 $R$ 的圆的正则 $n$ 边形的方程。扇形$0 \leqslant \varphi \leqslant \frac{2\pi}{n}$内的方程$\rho \cdot \cos \left( \varphi - \frac{\pi}{n} \right) = R \cos \frac{\pi}{n}$定义了边$AB$（图9），并且在对线段$AB$进行一系列可被$\frac{2\pi}{n}$整除的角度旋转之后，获得权重$n$-gon。

其根据式(8)的方程可写为

$$\rho \cdot \cos \left( \varphi - \frac{\pi}{n} - \frac{2\pi}{n} \cdot \left[ \frac{n\varphi}{2\pi} \right] \right) = R \cos \frac{\pi}{n}.$$
