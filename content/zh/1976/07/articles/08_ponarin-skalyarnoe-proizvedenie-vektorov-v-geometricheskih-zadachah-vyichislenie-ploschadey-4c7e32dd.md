---
id: 1976-7-ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd
issue: kvant_1976_7
year: 1976
number: "7"
title: 几何问题中向量的点积。面积计算
authors:
  - Понарин Я. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 27
page_last: 29
page_labels: 25, 27
tag: L0J1
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 47347ac261c018d115a6ebd36dbd8f073c50fc29eba5e49178b3e95e589332cb
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/08_ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd.md
source_content_sha256: 5f1fc9d5d3e34cb13f3e9f70fcea2824acc72fc1e02c44b242ffcdcb29fc79e6
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

是啊。波纳林

饲养区

三角形的面积
已知三角形ABC的面积可以用公式计算
$$S = \frac{1}{2} ab \sin \hat{C},$$
(1)

其中 a、b 和 c 分别是与角 $\hat{A}, \hat{B}$ 和 $\hat{C}$ 相对的三角形的边长。

让我们用 $\vec{a}$ 和 $\vec{b}$ 表示三角形边的向量 $\vec{CB}$ 和 $\vec{CA}$。根据向量标量积的定义可以得出 $\cos \hat{C} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}$，因此 $\sin^2 \hat{C} = \frac{a^2 b^2 - (\vec{a} \cdot \vec{b})^2}{a^2 b^2}$
（向量的标量平方等于其长度的平方）。

让我们对公式（1）两边进行平方，并将找到的表达式代入$\sin^2 \hat{C}$；我们得到
$$4S^2 = a^2 b^2 - (\vec{a} \cdot \vec{b})^2.$$
(2)

公式（2）对我们后面会有用（特别是，从中很容易得到三角形面积的Heron公式）。

四边形的面积
如果 p 和 q 是任意平面四边形（其对边不相交于内点）的对角线长度，则可以使用以下公式求出其面积
$$S = \frac{1}{2} pq \sin (\vec{p}, \vec{q}).$$
(3)

与三角形的情况一样，我们将这个公式重写为类似于（2）的形式：
$$4S^2 = p^2 q^2 - (\vec{p} \cdot \vec{q})^2.$$
(4)

为了评估得到的公式（2）和（4），让我们解决几个问题（如果您尝试以不同的方式解决它们，而不使用标量积，您将看到解决方案有多么复杂）。

问题1.计算多面体ABCD的面ABC的面积，如果a、b、c是其边DA、DB和DC的长度，α、β、γ是与相邻边BC、AC和AB对应的顶点D处的平面角。

解决方案e.让我们引入以下符号：$\vec{DA} = \vec{a}, \vec{DB} = \vec{b}, \vec{DC} = \vec{c}$。那么对于面 ABC 的面积 S 我们有
$$4S^2 = |\vec{CA}|^2 \cdot |\vec{CB}|^2 - (\vec{CA} \cdot \vec{CB})^2 = (\vec{a} - \vec{c})^2 \cdot (\vec{b} - \vec{c})^2 - ((\vec{a} - \vec{c}) \cdot (\vec{b} - \vec{c}))^2 = (a^2 + c^2 - 2ac \cos \beta)(b^2 + c^2 - 2bc \cos \alpha) - (ab \cos \gamma - ac \cos \beta - bc \cos \alpha + c^2)^2.$$

事实上，问题已经解决了，但是得到的表达式不对称地包括长度a、b、c和角度α、β、γ，尽管根据问题的条件a、b、c以及α、β、γ的值应该是

⟦folio 27⟧

任务 4. 通过边为 a 的正多面体的顶点绘制一个平面，使其与底面平面的交线与边平行，并将底面分成相等的两部分。求指定平面 (图 3) 的多面体横截面积。

解决方案。在这个正四面体中，我们表示 $ABCD$ $\vec{DA} = \vec{a}$、$\vec{DB} = \vec{b}$、$\vec{DC} = \vec{c}$ 和 $|\vec{a}| = |\vec{b}| = |\vec{c}| = a$。让切割平面沿直线$MN$、$M \in (AB)$、$N \in (AC)$、$(MN) \parallel (BC)$ 与平面$ABC$ 相交。所需的横截面积可以使用以下公式计算

$$4S^2 = |\vec{DM}|^2 \cdot |\vec{DN}|^2 - (\vec{DM} \cdot \vec{DN})^2.$$

这个公式告诉你如何解决这个问题。

我们有$\vec{DM} = \vec{DA} + \vec{AM}$，其中$\vec{AM} = k \cdot \vec{AB}$。

数$k$是由直线$MN$将底$ABC$等分为两部分，且使得三角形$AMN$与$ABC$相似而得；这就是为什么

$$S_{AMN} : S_{ABC} = |\vec{AM}|^2 : |\vec{AB}|^2 = k^2 = \frac{1}{2},$$

从哪里$k = \frac{1}{\sqrt{2}}$。这就是为什么

$$\vec{DM} = \vec{DA} + k \cdot \vec{AB} = a + \frac{1}{\sqrt{2}} (\vec{b} - \vec{a}) = \frac{(\sqrt{2} - 1) \vec{a} + \vec{b}}{\sqrt{2}}.$$

与$\vec{DN} = \frac{(\sqrt{2} - 1) \vec{a} + \vec{c}}{\sqrt{2}}$相同。

将$\vec{DM}$和$\vec{DN}$的表达式代入$S$的公式，我们得到

$$16S^2 = ((\sqrt{2} - 1) \vec{a} + \vec{b})^2 \cdot ((\sqrt{2} - 1) \vec{a} + \vec{b}) \times ((\sqrt{2} - 1) \vec{a} + \vec{c})^2.$$

因为对于边长为 $a$ 的正四面体

$$\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{c} = \vec{a} \cdot \vec{c} = \frac{1}{2} a^2,$$

经过所有询问后我们得到

$$S = \frac{1}{8} a^2 \sqrt{11 - 4\sqrt{2}}.$$

自行解决以下问题：

1. 给定一个任意四边形$ABCD$。点 $A_1$ 和 $C_1$ 是顶点 $A$ 和 $C$ 当视点平行于它们的交点时的图像。证明四边形 $A_1BC_1D$ 的大小等于给定的四边形 $ABCD$。

2. 在四面体$ABCD$中，所有六个边的长度都是已知的：$|DA| = a$、$|DB| = b$、$|DC| = c$、$|BC| = a_1$、$|AC| = b_1$、$|AB| = c_1$。通过边 $DB$ 的中间绘制一个与边 $AD$ 和 $BC$ 平行的平面。求该平面的四面体的横截面积。

3. 在正三角形中，取顶点处的平面角为$\alpha$，边长为$a$。求穿过底座一侧和对侧肋中部的平面的横截面积。
