---
id: 1975-8-byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98
issue: kvant_1975_8
year: 1975
number: "8"
title: 从函数图构造方程
authors:
  - Быстрый И. М.
rubric: raznoe
page_first: 56
page_last: 59
page_labels: 54, 56, 57
tag: 90VB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7f0ef58216eb8bb236b6ae0206ce706c132f6392e81bd913e14a6b3264a6f714
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/13_byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98.md
source_content_sha256: 8a783133ed3111199adc014dc698a727129559f41dde686aca4cc95fbedf2953
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

从函数图构造方程

解决各种问题时需要构造函数方程。这些问题出现在数学、物理学，最重要的是现代技术中。本文展示了如何使用榄香碱函数方程 [直线、抛物线、正弦曲线方程] 来描述学校物理课程中发现的更复杂的依赖关系图。更准确地说，在讨论周期性过程的那些部分中。

让我们首先回顾一下函数图的几个重要属性。

1. 如果函数 $F_1(x)$ 的图形沿函数 $f(x)$、$x \in [a, b]$ 的图形纵轴向上或向下移动 $|c|$ 个单位，则函数 $F_1(x)$ 的方程为以下形式

$$F_1(x) \quad f(x) \pm |c|, \quad x \in [a, b]$$

此外，如果图形向上移动，则应取“+”号，如果向下移动，则应取“-”号。

2. 如果函数 $F_2(x)$ 的图形是函数 $f(x)$、$x \in [a, b]$ 沿横坐标向左或向右移动 $|c|$ 个单位，则函数 $F_2(x)$ 的方程具有以下形式

$$F_2(x) - f(x \pm |c|), \quad x \in [a \mp |c|, b \mp |c|]$$

此外，当图形向左移动时，取上方的符号，当图形向右移动时，取下方的符号。

3. 如果函数 $F(x)$ 的图像相对于函数 $f(x)$、$x \in [a, b]$ 的图像的横坐标轴对称，则方程 $F(x)$ 具有以下形式

$$F(x) - f(x), \quad x \in [a, b]$$

现在让我们看一些例子。

图 1.

图 2.

⟦folio none⟧

“药丸状”方向

我们尝试用函数图的上述性质来描述“药丸状”方向（图1）。这种类型的方向例如被提供给示波器电子管的偏转板。 “药丸”方向的特点是上升时间$T$比下降时间$t$长。因此，从图形上看，时间过程中方向的变化可以表示为 图 2 中所示的线。但是，在这种情况下需要点

$$t = \frac{T}{2} (2n + 1),$$

$n$是一个整数。为了避免歧义，让我们用在点上根本没有定义的函数图来替换“药丸形”线

$$t = \frac{T}{2} (2n + 1),$$

或在左侧或右侧这些点定义的函数图（图 3、$a$、$b$、$\theta$）。

为了获得对周期函数$u(t)$变为图3、$a$的控制，我们研究一个周期内自变量变化时的情况，例如$\left(-\frac{T}{2}, \frac{T}{2}\right)$。

在这个区间内，周期函数$u(t)$的图形与函数$u_0 = f(t) = t^*$的图形重合）。现在让我们将图形 $u_0$ 沿着 x 轴向右移动一个周期（图 处的红线）。然后我们得到一个新函数$u_1 = f(t - T) = t - T$，区间$\left(-\frac{T}{2}, \frac{T}{2}\right)$将进入区间$\left(\frac{T}{2}, \frac{3}{2} T\right)$。通过将函数 $u_0$ 的图形沿 x 轴移动整数 $n$ 周期，每个

$$*) \text{Точнее, } f(t) = At, \text{ где } A = 1 \ \theta/c \text{-размерный коэффициент.}$$

对于固定的 $n$ 次，我们得到一个新函数

$$u_n = f(t - nT) = t - nT,$$

$$t \in \left(\frac{T}{2} (2n - 1), \frac{T}{2} (2n + 1)\right).$$

这些函数在$n = 0, \pm 1, \pm 2, \dots$处的集合构成了互斥函数$u(t)$的方程。

如果函数的周期为 $T = \pi$ 秒，则其方程可以写成不同的形式：

⟦folio 56⟧

与纵轴平行的线段。他们的方程是：

$$t(u) = \frac{T}{2}(2n+1),$$
$$u \in \left[-\frac{T}{2}, \frac{T}{2}\right], \quad n = 0, \pm 1, \pm 2, \ldots$$

路径方程

图 4 显示了直线移动的点所经过的路径的图。
让我们构建路径方程*)。

显然，图$S(t)$是由抛物线$S_\alpha = at^2$、$t \in \left[0, \frac{T}{2}\right]^{**}$的一段组成的。让我们进行以下转换：

1) 分支（$\alpha$）相对于纵轴对称切割 - 我们得到分支（$\beta$）：$S_\beta = at^2$，$t \in \left[-\frac{T}{2}, 0\right]$；

2) 分支($\beta$)相对于横坐标轴对称切割——我们得到分支($\gamma$)：$S_\gamma = at^2$，$t \in \left[-\frac{T}{2}, 0\right]$；

3) 将分支 ($\gamma$) $T$ 向右移动，并向上移动 $\frac{aT^2}{2}$ - 我们得到分支 ($\delta$)：$S_\delta = -a(t-T)^2 + \frac{aT^2}{2}$，$t \in \left[\frac{T}{2}, T\right]$。

将分支 ($\alpha$) 和 ($\delta$) 向右移动 $nT$，向上移动 $\frac{aT^2}{2}$，使用变量 $n = 0, 1, 2, \ldots$，我们将得到

$$S(t) = \begin{cases} a(t-nT)^2 + n\frac{aT^2}{2}, \\ t \in [nT, \frac{T}{2} + nT]; \\ -a[t-(n+1)T]^2 + (n+1)\frac{aT^2}{2}, \\ t \in \left[\frac{T}{2} + nT, (n+1)T\right]. \end{cases}$$

*) 参见 «Kvant»，1973 年，第 11 期，第 11 页。 60.
**) 这里$a$是比例系数。如果一个点以加速度$b$移动，则$a = b/2$

⟦folio 57⟧

⟦figure⟧
图 5.

⟦figure⟧
图 6.

⟦figure⟧
图 7.

⟦figure⟧
图 8.

⟦figure⟧
图 9.

⟦column⟧
如果我们像这样转换第二部分：

$$--a\left[\left(t-nT-\frac{T}{2}\right)-\frac{T}{2}\right]^2+\frac{aT^2}{2}+$$

$$+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t--(2n+1)\frac{T}{2}\right]-\frac{aT^2}{4}+$$

$$+\frac{aT^2}{2}+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t-(2n+1)\frac{T}{2}\right]+\frac{aT^2}{4}(2n+1),$$

那么路径方程可以写成如下：

$$S(t)=(-1)^m a\left(t-m\frac{T}{2}\right)^2+$$

$$+\frac{1-(-1)^m}{2}aT\left(t-m\frac{T}{2}\right)+m\frac{aT^2}{4},$$

$$t\in\left[m\frac{T}{2},(m+1)\frac{T}{2}\right], m=0,1,2,\dots$$

练习

1. 写出图 5、6 和 7 所示直线的方程。对于 图 5 所示的直线，写出在左右点 $t=n\pi$ 处定义的函数方程。
2. 使用具有两个电子管二极管的电路对交流电进行“推挽”（全波）整流。如果电流的正半周通过一个二极管，负半周通过另一个二极管，则电压波形将如图 8 所示的线所示。找出该线的方程。
3. 使用单个二极管电路可以实现半波交流整流。然后一个符号的半周期通过二极管，但另一个符号的半周期不通过。电压波形如图图 9 所示。求该函数的方程。
4. 构造函数的方程，其在 $[nT,(n+1)T]$、$n=0,1,2,\dots$ 部分上的图（参见 图 4）与函数的图全等

$$y=A\sin x,\ x\in\left[-\frac{\pi}{2},\frac{\pi}{2}\right].$$
