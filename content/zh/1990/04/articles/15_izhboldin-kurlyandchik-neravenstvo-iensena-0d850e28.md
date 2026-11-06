---
id: 1990-4-izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28
issue: kvant_1990_4
year: 1990
number: "4"
title: 詹森不等式
authors:
  - Ижболдин О. Т.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 59
page_last: 63
page_labels: 57, 58, 59, 61
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1231ab19a858e8a58d7e3d5ea7dbc72c36f71f96ff67a4f064d2f3f6b8803bb1
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/15_izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28.md
source_content_sha256: 2eff30638d5aae031b3e1d22a6ed15aa28be10dcd634d546ce57c674fa9c9b0e
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 57⟧

---
running_head:
folio:
---

不等式
詹森
O. 伊日沃尔丁、L. 库尔良奇克

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$
$$\prod_{k=1}^{n} a_k = a_1 \cdot a_2 \cdot \dots \cdot a_n.$$

我们建议那些还没有学过的人
使用它们，描述你——
砌体更详细。

证明不平等的艺术
掌握绝非易事。这需要大量的经验、直觉和
与每门艺术一样，自由应用各种“技术”技巧的能力。我们将使用许多示例来演示一种此类技术。本文将证明经典不等式（柯西、柯西-布尼亚科夫斯基、霍尔德和闵可夫斯基），以及不太出名但也非常有趣的。

我们将使用符号编写公式，通常是简短的

将要讨论的不等式的证明基于凸性的概念。这是一个非常重要的数学概念，你在学校几何课程中学习多边形时已经遇到过它。然而，在数学中，凸性的概念不仅仅与多边形有关。如果一个图形具有点的任意两个属性，并且包含端点位于这些点的整个线段，则该图形称为凸图形。图 1、a-2 显示了凸形和非凸形的示例。你-

57

⟦folio 58⟧

---
running_head:
folio:
---

凸图形有许多显着的性质，但我们只对其中之一感兴趣。让我们形成它。
令质量$m_1, m_2, \dots, m_n$分别集中在凸图形Ф的点$A_1, A_2, \dots, A_n$上。那么这些点的质心也属于图形F。
由物理学可知，质心是一个有坐标的点
$$\left( \frac{\sum_{i=1}^{n} m_i x_i}{\sum_{i=1}^{n} m_i}; \frac{\sum_{i=1}^{n} m_i y_i}{\sum_{i=1}^{n} m_i} \right),$$
其中$x_i, y_i$是点$A_i$的坐标。

乌拉真尼亚
1. 证明两点的质心位于连接它们的线段上。
2. 证明 $n$ 点的质心位于连接它们中的任何一个与其他点的质心的线段上。

凸图形
让我们画一个函数 $y = x^2$ (图 2, a) 的图形。

图 1.
图 2.

我们看到这个图形的铭文（在图处是红色的）是一个凸图形。如果我们考虑图形$y = \sin x$（$x \in [0; \pi]$），那么它的铭文（在图2上，b它是红色的）不是凸的。然而，该图的子图是凸的（在相同的图上它用相同的颜色着色）。

这些观察结果得出了一个重要的定义。

如果figuntia的题词是凸图形，那么他们说这个figuntia是凸的，如果子图是凸的，那么他们说这个figuntia是voguntai *)。

因此，figuncia $y = x^2$ 是凸的，figuncia $y = \sin x$ ($x \in [0; \pi]$) 是 vogunt。

基本不平等
在众所周知的经典不等式的平均值中，詹森不等式**占有特殊的地位。文章开头提到的所有经典不平等都是其后果。

定理（詹森不等式）。令$y = f(x)$为某个区间上的凸图，$x_1, x_2, \dots, x_n$为该区间内的任意数，$a, \alpha_1, \alpha_2, \dots, \alpha_n$为任意总和等于1的正数。然后

$$f(\alpha_1 x_1 + \dots + \alpha_n x_n) \leqslant \alpha_1 f(x_1) + \dots + \alpha_n f(x_n).$$

证明。让我们在图 $y = f(x)$ 的图表上考虑横坐标为 $x_1, x_2, \dots, x_n$ 的点 $A_1, A_2, \dots, A_n$。让我们在这些点上放置质量为 $m_1, m_2, \dots, m_n$ 的重物。这些点的质心有坐标

$$\left( \frac{m_1 x_1 + \dots + m_n x_n}{m_1 + \dots + m_n}; \frac{m_1 f(x_1) + \dots + m_n f(x_n)}{m_1 + \dots + m_n} \right).$$

*) 一些教科书使用不同的术语。
**) Jensen Johann Ludwig (1859-1925) - 丹麦数学家。

⟦folio 59⟧

---
running_head:
folio:
---

由于点$A_1, A_2, \dots, A_n$属于凸函数的铭文，那么它们的质心也属于凸函数（因为铭文是凸函数）。这意味着质心的纵坐标不小于图上同横坐标点的纵坐标（图3），即

$$f\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right) \leqslant \frac{m_1f(x_1) + \dots + m_nf(x_n)}{m_1 + \dots + m_n}.$$ (3)

要完成证明，剩下的就是输入$m_1 = \alpha_1, \dots, m_n = \alpha_n$。

我们想用两点重要的话来结束本文的这一点。首先，在证明Jensen不等式（2）的过程中，我们证明了不等式（3）。事实上，这些不等式是等价的。将$\alpha_i = \frac{m_i}{m_1 + \dots + m_n} (i = 1, 2, \dots, n)$代入不等式(2)，可得不等式(3)。因此，这两个不等式自然被称为 Jensen 不等式。不等式（2）看起来更紧凑，但对于应用来说使用不等式（3）更方便。其次，如果函数 $f(x)$ 是凹函数，那么 Jensen 不等式 (2) 和 (3) 就相反。为了证明这一点，只需考虑凸函数$f(x)$即可。

柯西-布尼亚科夫斯基不等式

乍一看，詹森不等式并没有给人留下太多印象：其表述过于笼统。读完本文后，您就会发现这种印象是具有欺骗性的。

让我们用一个具体的例子来证明詹森不等式的威力。也就是说，我们将证明著名的柯西-布尼亚科夫斯基不等式：

$$(a_1^2 + \dots + a_n^2)(b_1^2 + \dots + b_n^2) \geqslant (a_1b_1 + \dots + a_nb_n)^2,$$

其中$a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$是任意正数。

证明。众所周知，函数 $y = x^2$ 是凸函数。让我们为这个函数写出 Jensen 不等式 (3)

$$\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right)^2 \leqslant \frac{m_1x_1^2 + \dots + m_nx_n^2}{m_1 + \dots + m_n} (m_i > 0).$$

因此，$(m_1x_1^2 + \dots + m_nx_n^2) \times (m_1 + \dots + m_n) \geqslant (m_1x_1 + \dots + m_nx_n)^2$。

代入$m_i = b_i^2$，$x_i = \frac{a_i}{b_i}$，我们得到所需的不等式。

练习 3. 证明任意实数 $a_i, b_i$ 的柯西-布尼亚科夫斯基不等式。

凸函数的例子

要成功应用 Jensen 不等式，您需要一个简单的 cri

⟦folio 61⟧

---
running_head:
folio:
---

$$\left( \frac{\sum m_i x_i}{\sum m_i} \right)^p \leqslant \frac{\sum m_i x_i^p}{\sum m_i}.$$

从这里
$$\sum m_i x_i \leqslant \left( \sum m_i \right)^{\frac{p-1}{p}} \left( \sum m_i x_i^p \right)^{\frac{1}{p}}.$$

既然$\frac{1}{p} + \frac{1}{q} = 1$，那么$\frac{p-1}{p} = \frac{1}{q}$，因此
$$\sum m_i x_i \leqslant \left( \sum m_i x_i^p \right)^{\frac{1}{p}} \left( \sum m_i \right)^{\frac{1}{q}}.$$

现在放入$m_i = b_i^q$，$x_i = a_i b_i^{1-q}$，我们得到所需的不等式。

闵可夫斯基不等式
$$\sqrt[n]{a_1 \cdots a_n} + \sqrt[n]{b_1 \cdots b_n} \leqslant$$
$$\leqslant \sqrt[n]{(a_1 + b_1) \cdots (a_n + b_n)} (a_i, b_i > 0).$$

证明。将不等式两边同时除以$\sqrt[n]{a_1 \cdots a_n}$，我们得到
$$1 + \left( \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( \frac{b_n}{a_n} \right)^{\frac{1}{n}} \leqslant$$
$$\leqslant \left( 1 + \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( 1 + \frac{b_n}{a_n} \right)^{\frac{1}{n}}.$$

很明显，以某种方式指定分数 $\frac{b_i}{a_i}$ 是有意义的。但事实上，引入一个符号不是针对分数 $\frac{b_i}{a_i}$ 本身，而是针对它的对数更方便：
$$x_i = \ln \frac{b_i}{a_i}$$。因此，用 $e^{x_i}$ 替换 $\frac{b_i}{a_i}$，我们将不等式写成以下形式
$$1 + e^{\sum \frac{1}{n} x_i} \leqslant \Pi \left( 1 + e^{x_i} \right)^{\frac{1}{n}}.$$

让我们对所得不等式两边取对数：
$$\ln \left( 1 + e^{\sum \frac{1}{n} x_i} \right) \leqslant \sum \frac{1}{n} \ln \left( 1 + e^{x_i} \right).$$

在最后一个不等式中，我们学习了凸函数 $y = \ln \left( 1 + e^{x_i} \right)$ 的 Jensen 不等式（示例 4）。

使用詹森不等式的一些例子
问题1.证明不等式
$$\Pi a_i^a \geqslant \left( \sum \frac{1}{n} a_i \right)^{\sum a_i} (a_i > 0).$$

解决方案。计算不等式两边并除以 $n$，我们得到
$$\sum \frac{1}{n} a_i \ln a_i \geqslant \left( \sum \frac{1}{n} a_i \ln \sum \frac{1}{n} a_i \right).$$

这就是凸函数 $y = x \ln x$ 的 Jensen 不等式（示例 5）。

任务 2. 证明不等式：
$$\sqrt{\left( \sum a_i \right)^2 + \left( \sum b_i \right)^2} \leqslant \sum \sqrt{a_i^2 + b_i^2} (a_i, b_i > 0).$$

解决方案。让我们为凸函数 $y = \sqrt{1 + x^2}$ 写出 Jensen 不等式 (3)（例 6）：
$$\sqrt{1 + \left( \frac{\sum m_i x_i}{\sum m_i} \right)^2} \leqslant \sum \frac{\sum m_i \sqrt{1 + x_i^2}}{\sum m_i}.$$

将不等式两边同时乘以$\sum m_i$，我们得到
$$\sqrt{\left( \sum m_i \right)^2 + \left( \sum m_i x_i \right)^2} \leqslant$$
$$\leqslant \sum m_i \sqrt{1 + x_i^2} = \sum \sqrt{m_i^2 + (m_i x_i)^2}.$$

剩下的就是放入$m_i = a_i$，$x_i = \frac{b_i}{a_i}$。

总之，我们考虑一个相当困难的问题，也可以使用 Jensen 不等式来解决。

问题 3. 证明不等式
$$\frac{p_1}{p_2 + p_3} + \frac{p_2}{p_3 + p_4} + \frac{p_3}{p_4 + p_5} +$$
$$+ \frac{p_4}{p_5 + p_1} + \frac{p_5}{p_1 + p_2} \geqslant \frac{5}{2} (p_i > 0).$$

解决方案。为了方便起见，我们引入了额外的变量$p_6$和$p_7$，分别等于$p_1$和$p_2$。 Teler，这个不等式可以简单地写成：
$$\sum_{i=1}^{5} \frac{p_i}{p_i+1+p_i+2} \geqslant \frac{5}{2}.$$

让我们表达凸函数 $y = \frac{1}{x}$ 的 Jensen 不等式 (3)（示例 1）：
