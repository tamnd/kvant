---
id: 1988-6-schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb
issue: kvant_1988_6
year: 1988
number: "6"
title: 学校电脑画一个圆圈
authors:
  - Щёголев А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 60
page_labels: 56-58
tag: F4A8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b909dc8107deffacb55beee98310f57004ea8c6cf36c84ea7ab3b1ae725fc7eb
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/13_schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb.md
source_content_sha256: 2a4c924644e89440ec978013e6596b361dacc10c50d113f53bd337f975a16520
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

学校电脑画一个圆圈

A·G·舍戈列夫

在上一期«Kvant»中，我们讨论了雅马哈学校计算机的图形功能（以及 MSX 语言 - BASIC），绘制了漂亮的图片 - 或者更确切地说，编译了执行这些图的算法。这次我们将展示机器在解决几何作图问题时的图形能力。我们将限制自己只分析一个问题，但是这个分析会非常详细；它基于系统规划的原则（参见«Kvant»，1987年，第10、11期）。因此，任务：给定坐标属性，通过三个点画一个圆。

你的任务是构造一个由三角形外接的圆。如果这三个点不同并且不在同一条线上，则可以以独特的方式完成此构造。

让我们对算法和程序进行完整系统的构建。

让我们构建一个经过三个点的圆。
第一个点的坐标
第二个点的坐标
第三点的坐标

无法通过这些点画圆（这是唯一的方法！）！

图 1.

⟦folio 57⟧

分期：
给定： $(x_1, y_1)$ — 点 $A, B, C$ 的坐标。
必需：$\sigma$ - 圆形图像（或其位于屏幕内的一部分）。
当：$A, B, C$不在同一条直线上。
联系方式：$A \in \sigma, B \in \sigma, C \in \sigma$。

设想：
在图1处，蓝色圆圈包含未来对话的可变元素——人响应计算机请求报告的特定数字。括号中的数字包含计算机的两个版本：如果具有给定坐标的点位于同一条直线上，则将看到第一个版本；如果点的坐标满足公式，则将看到第二个版本；在后一种情况下，屏幕将显示具有给定坐标的点$A, B, C$，并且一个圆穿过它们。

方法：
三个给定点 $A, B$ 和 $C$ 位于同一条直线上的条件相当于向量 $\overrightarrow{AB}$ 和 $\overrightarrow{BC}$ (图 2) 的共线性，并且具有以下形式
$$(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2).$$
练习 1. 确保此条件也涵盖任意两个（甚至所有三个）点重合的情况。
为了画一个圆，我们必须告诉表演者（学校计算机）它的圆心和半径的坐标。
众所周知，外接圆的圆心$S$可以作为三角形$(AB$和$BC$在图上重新分布的中点的交点找到。 3）。
 向量坐标：
$$\overrightarrow{AB} = (x_2 - x_1, y_2 - y_1),$$
$$\overrightarrow{BC} = (x_3 - x_2, y_3 - y_2);$$
$M$ - 边的中间 $AB$ - 有坐标
$$(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2});$$
 点 $N$ 的坐标 - 中点

边$BC$
$$(\frac{x_2 + x_3}{2}, \frac{y_2 + y_3}{2}).$$

直线$MS$上的任意一点都有坐标$(M_x + \lambda m_x, M_y + \lambda m_y)$，其中$M_x$和$M_y$分别为$M$点对应的横坐标和纵坐标； $m_x = y_2 - y_1$和$m_y = x_2 - x_1$是向量$m$的坐标； $\lambda$ 是某个数字。
练习 2. 证明 $\vec{m} \perp \overrightarrow{AB}$。
 直线$NS$上的点的坐标类似地通过参数$\mu$、点$N$的坐标和垂直于$\overrightarrow{BC}$的向量（例如向量$n = (y_3 - y_2, x_2 - x_3)$）来表示。为了找到线 $MS$ 和 $NS$ 的交点，我们使相应的坐标相等：
$$\begin{cases} M_x + \lambda m_x = N_x + \mu n_x, \\ M_y + \lambda m_y = N_y + \mu n_y. \end{cases}$$

求解该线性方程组的未知数 $\lambda$ 和 $\mu$，我们得到例如 $\lambda$ 的表达式：
$$\lambda = \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}.$$
 圆心坐标
$$S_x = M_x + \lambda m_x = \frac{x_1 + x_2}{2} + \lambda (y_2 - y_1),$$
$$S_y = M_y + \lambda m_y = \frac{y_1 + y_2}{2} + \lambda (x_1 - x_2).$$
钝半径由毕达哥拉斯定理确定为中心与任何给定点之间的距离（例如，

⟦folio 58⟧

米$A$）：

$$r = \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}.$$

现在，有了脚本和计算方法，让我们构建一个算法并将其转换为 MSX - BASIC。我们使用“图像”辅助算法（GOSUB 200是调用相应的子程序）。

算法：

阿尔格圈
开始
输出“作圆”、“经过三点”。
请求“第一个点的坐标”； $x_1, y_1$
请求“第二点的坐标”； $x_2, y_2$
请求“第三点的坐标”； $x_3, y_3$

如果$(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2)$
然后得出结论“不可能”“通过这些点画一个圆”“（也是唯一的一个）！”

英寸图像
全部
骗局

阿尔格图像
开始
图形
点$(x_1, y_1)$，粉红色
点$(x_2, y_2)$，粉红色
点$(x_3, y_3)$，粉红色

$$\lambda := \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}$$

$$S_x := \frac{x_1 + x_2}{2} + \lambda(y_2 - y_1)$$

$$S_y := \frac{y_1 + y_2}{2} + \lambda(x_1 - x_2)$$

$$r := \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}$$

圆圈$(S_x, S_y)$、$r$、粉色
骗局

程序：

10'圆
