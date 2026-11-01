---
id: 1980-8-sosinskiy-peremescheniya-prostranstva-f3bae3bb
issue: kvant_1980_8
year: 1980
number: "8"
title: 移动空间
authors:
  - Сосинский А. Б.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: UPMN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5cd4246d75f7ef19f8abef0bbafa41b01172ccb002b7480fdc8712271dc43f1e
prompt_sha256: draft-1
translated_from: content/ru/1980/08/articles/04_sosinskiy-peremescheniya-prostranstva-f3bae3bb.md
source_content_sha256: 63964931eef9fbb88fbaa6600d77dbf79b8c53b1ce671a125548b833c3aca986
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A·索辛斯基

移动空间

在这篇文章中，我想告诉你太空运动是什么样的。首先写道：空间的位移是空间到自身的映射$f$，保留点之间的距离。这意味着对于任意点 $A, B$

$$|AB| = |A'B'|,$$

(1)

其中$A' = f(A), B' = f(B)$。

您当然知道这些例子 - 这些是对称性（中心、osvaya、相对于平面）和平行平移 $\vec{a}$；很容易说，这场运动也将

门 $R_l^\phi$ 绕线 $l$ 以给定角度 φ (图 1) 运行。我们的任务是列出空间的所有运动，就像 V. Boltyansky 的文章“飞机的运动”（«Kvant»，1980，第 3 期）中对飞机所做的那样。

从定义很容易推导出位移将直线变换为直线、平面变换为平面、圆变换为同心圆、角度变换为同心角等。

动作和方向

在平面上，通过指定两个可能的旋转方向之一（“顺时针”或“逆时针”）来指定方向。显然，“逆时针”方向称为正方向，“顺时针”方向称为负方向。

空间中也有两种方向：一种由左手钻给出（例如，一般的开瓶器），另一种由左手给出（图2）。

数学家并不真正喜欢谈论小工具 - 他们更喜欢通过指示向量的非平面三元组 $(\vec{a}; \vec{b}; \vec{c})$ 来指定空间的方向。

图 1.

⟦folio 3⟧

事实是，所有这样的三元组自然地分为两类：从第一个向量到位于第三个向量末尾的第二个观测值的最短时间为正的三元组（参见 图 3；我们称此类三元组为正），以及为负的三元组（负三元组）。

检查一下自己：你走那条路吗？
a) 三元组 ($\vec{a}; \vec{b}; \vec{c}$) 和 ($\vec{c}; \vec{a}; \vec{b}$) 的符号相同吗？
b) 三元组 ($\vec{a}; \vec{b}; \vec{c}$) 和 ($\vec{a}; \vec{c}; \vec{b}$) 是否有不同的符号？
b) 三元组 ($\vec{a}; \vec{b}; \vec{c}$) 和 ($\vec{a}; \vec{b}; -\vec{c}$) 是否有不同的符号？

物理学家更喜欢手而不是三重向量：右手设置正方向，左手设置负方向（图 4）；记住电发生论中的左手定则。

因此，指定非平面向量三元组指定了两个可能的空间方向之一。

如果平移$f$将选定的向量三元组转换为具有相同符号的三元组（可以证明它随后保留了任一三元组的符号！），我们会说它保留了方向；否则我们自然会

图 2.
图 3.
图 4.

图 5.

⟦folio 4⟧

图 6.

假设移动 $f$ 会改变方向。

例如，平行平移和绕线旋转（特别是轴对称）会保留方向，而中心对称和相对于平面的对称会改变方向（图 5）。

我不想误导你：这里的一切并不那么简单。例如，复杂的顺序“逆时针”和“最短旋转......对于观察者发现......”（见上文）严格来说没有任何数学意义 - 它们不能在几何学运动学的框架内定义（以及作者已知的其他运动学）。

事实上，可以严格定义相等和相反方向的“带箭头的圆”或向量三元组，但形式上不能优先选择圆或三元组类型中的一种。此外，在没有证据的情况下，我们驳斥了一个重要的事实：保留一个三元组方向的举动不能放置另一个三元组的方向。对这些问题的详细讨论会让我们走得太远：视觉清晰度足以让我们继续前进。

动作的组成

映射$f$、$g$（特别是位移）的组合称为映射$h = g \circ f$，依次执行$f$、$g$得到；这意味着对于任何点 $A$

$$h(A) = g(f(A)).$$

请注意$g \circ f$条目中的顺序：首先执行$f$，然后$g$。这个条目是完全自然的，因为根据公式（2）

$$(g \circ f)(A) = g(f(A)).$$

很容易看出，位移的合成就是位移（如果您应用（1）两次，则立即获得）。让我们看看如果我们将已知的位移组合起来，会得到什么位移。我将从非常简单的示例开始，您可以通过查看相应的附图轻松理解这些示例。但这里几乎没有视觉理解——你需要检查证据（但是，有很多过程）。

1°。两个对称相对平行平面的合成是平行平移（图6a）。

2°。两个对称的相对相交平面的组合 - 绕其相交线的圆旋转 (图 6 b)。

3°。相对于三个相互垂直的平面的三个对称的组成相对于它们的公共点（图6英寸）对称。

4°。相对于一个平面对称和垂直于该平面的传递的组合是相对于（另一个）平面对称的。

⟦folio 5⟧

图 7.

在这些例子中，组合物导致了我们之前已知的位移。但当然，情况并非总是如此 - 例如，移动

$$W_{l,\vec{a}}^{\varphi} = \vec{a} \circ R_{l,\varphi},$$

其中向量$\vec{a}$与线$l$平行，我们还没有遇到过； $W_{l,\vec{a}}^{\varphi}$称为螺旋运动（轴$l$、角度$\varphi$、矢量$\vec{a}$）；它将在进一步的故事ZE（图7）中发挥重要作用。

显然对于 $\vec{a} \parallel l$

$$\vec{a} \circ R_{l,\varphi} = R_{l,\varphi} \circ a.$$ (3)

同样明显的是，螺杆运动和平行于旋转轴的矢量上的位移的组合将再次是具有相同旋转轴但具有不同位移矢量（等于旧位移和新位移之和）的螺杆运动。但以下事实一点也不有趣：

$$5^\circ. \text{Композиция поворота } R_{l,\varphi} \text{ и произвольного перемещения } c \text{ является винтовым перемещением } c \text{ осью } l' \parallel l \text{ на угол } \varphi.$$

我们很快就会需要这份声明；让我们证明一下。为此，我们将向量 $c$ 分解为和 $\vec{c} = \vec{c}_1 + \vec{c}_2$，其中向量 $\vec{c}_1$ 沿着 $l$ 轴，而 $\vec{c}_2$ 垂直于该轴。平行平移的组合对应于向量之和，因此 $\vec{c} = \vec{c}_2 \circ \vec{c}_1$，因此根据 (3)

图 8.

$$\vec{c} \circ R_{l,\varphi} = (\vec{c}_2 \circ \vec{c}_1) \circ R_{l,\varphi} = \vec{c}_2 \circ (\vec{c}_1 \circ R_{l,\varphi}) = \vec{c}_2 \circ (R_{l,\varphi} \circ \vec{c}_1) = (\vec{c}_2 \circ R_{l,\varphi}) \circ \vec{c}_1.$$ (4)

会移动$\vec{c}_2 \circ R_{l,\varphi}$，记住$\vec{c}_2 \perp l$。考虑任意平面 $l$ (图 8)。在这个平面上，位移$\vec{c}_2 \circ R_{l,\varphi}$是平面$R_{0}^{\varphi}$（其中$O = l \cap \pi$）的旋转和平面到向量$\vec{c}_2$（毕竟，$\vec{c}_2 \perp l \Rightarrow \vec{c}_2 \parallel \pi$）的传递的组合。这样的组合将是（«Kvant»，1980，第 3 期，第 6 页）围绕新中心 $O'$ 旋转相同角度 $\varphi$，这很容易构造（参见图 8，其中$[OA] \rightarrow [AA']$）。在垂直于 $l$ 的所有平面上观察到相同的图像，因此

$$\vec{c}_2 \circ R_{l,\varphi} = R_{l,\varphi},$$

其中$l'$是穿过$O'$平行于$l$的线。根据 (4)，考虑$\vec{c}_1 \parallel l$，我们得到

$$\vec{c} \circ R_{l,\varphi} = (\vec{c}_2 \circ R_{l,\varphi}) \circ \vec{c}_1 = R_{l,\varphi} \circ \vec{c}_1 = \vec{c}_1 \cdot R_{l,\varphi} = W_{l,\varphi} \cdot \vec{c}_1.$$

从几何角度来看，这样的说法更不明显：

$$6^\circ. \text{Композиция винтового перемещения } W_{l,\varphi} \text{ и произвольного перемещения } c \text{ осью, параллельной прямой } l, \text{ на угол } \varphi.$$

然而，这个事实可以通过两种方式证明：

$$\vec{c} \circ W_{l,\varphi} = \vec{c} \circ (\vec{a} \circ R_{l,\varphi}) = (\vec{c} \circ \vec{a}) \circ R_{l,\varphi} = W_{l,\varphi} \cdot \vec{c}_1,$$
