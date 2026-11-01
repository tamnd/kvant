---
id: 1978-3-lopshits-ploschadi-orientirovannyih-figur-975f2900
issue: kvant_1978_3
year: 1978
number: "3"
title: 定向图形的区域
authors:
  - Лопшиц А. М.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 4, 7, 8, 9
tag: 3BBG
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e3ef4098f4cb1c3812f017c08e80203c2dffda44a31cd934ce29f42fff59f2a8
prompt_sha256: draft-1
translated_from: content/ru/1978/03/articles/03_lopshits-ploschadi-orientirovannyih-figur-975f2900.md
source_content_sha256: 5ad201fd211f7148c6c0ee90eb674885e18455bdc1e7cd23294d54f6ad202d83
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A·洛普希茨

定向图形的区域

我们杂志的读者经常遇到讨论领域的各种问题。他们的解决方案也是通过多种方式获得的。在1977年的«Kvant»第3期中，我们谈到了莫比乌斯的想法——不仅可以像学校那样用正数来测量有向多边形的面积，还可以用负数来测量。我们承诺将重新考虑这些问题，并向读者介绍莫比乌斯提出的问题的解决方案以及自然延续它们的问题。目前，我们建议首先测量有向多边形的面积——这是第一部分的重点；其中提供的材料条件将使读者准备好独立解决我们杂志中提出的领域的问题以及许多其他问题。

1. 有向图形区域的基本性质

1. 正如历史学家所认为，测量平面图形面积的需要是几何学出现和发展的基本原理之一：在下一次尼罗河泛滥之后，古埃及人必须恢复被泉水淹没的土地边界，并再次改变其面积。

在乡村课堂上，学生已经学会了求平行四边形、三角形和梯形面积的最简单规则。这些规则的数学推导使用面积等于三角形$A_1A_2A_3$和多边形$A_1A_3A_4 \dots A_n$面积之和的多边形：

$$\text{пл. } A_1A_2 \dots A_n = \text{пл. } A_1A_2A_3 + \text{пл. } A_1A_3A_4 \dots A_n.$$

一看图1，似乎就足以接受这个性质，即根据它所表达的数学句子是真实的这一事实。然而，对于图 1, 6所示的多边形，这个性质不成立；在这种情况下

$$\text{пл. } B_1B_2 \dots B_n = \text{пл. } B_1B_3B_4 \dots B_n - \text{пл. } B_1B_2B_3.$$

因此，我们必须改变公式：多边形$A_1A_2 \dots A_n$的面积等于多边形$A_1A_3A_4 \dots A_n$和三角形$A_1A_2A_3$的面积之和或差。

这个说法对于凸多边形和非凸多边形都适用，但是，唉！ - 一个显着的缺点：要使用它，您每次都需要查看绘图并选择“加号”或“减号”。

2. 符号几何学家莫比乌斯（Möbius）早在 1827 年就指出了摆脱这种情况的出路。他建议仅当满足以下条件时才为三角形$B_1B_2B_3$的面积指定正值

⟦folio 3⟧

顶点$B_1, B_2, B_3$顺时针位于(图 2, a)，否则(图 2, b)，则三角形$B_1B_2B_3$的“面积”被认为是负数，其模数等于该三角形的总面积。

下面的例子清楚地说明了这种新观点的有用性。如果点$P$位于三角形$ABC$内部，则(图3)。 pl。 $ABC =$ pl。 $PAB +$ pl。 $PBC +$
+ pl。 $PCA$。 (*)

然而，如果点$P$位于三角形$ABC$之外，那么这个等式必须用另一个等式代替，例如，在图4中给出的情况，并且等式

pl。 $ABC =$ pl。 $PAB +$
+ pl。 $PBC -$ pl。 $PCA$。

读者可以很容易地看出，根据点$P$的位置，另外五个“相似等式”是有效的（图4，b，b；5，a，b，b）。然而，如果我们使用莫比努斯规则，那么，很容易验证，“所有这”七个等式都可以写成(*)(图6)的形式。

因此，正确的莫比努斯使得可以断言它是公平的。

定理1.无论三角形在平面中的位置如何，

⟦folio 4⟧

中$ABC$点$P$，
pl。 $ABC = \text{пл. } PAB + \text{пл. } PBC + \text{пл. } PCA$。

而不是七个定理——一个！那么是否有可能就莫比努斯规则的权宜之计达成一致呢？

3. 现在让我们使用莫比努斯规则给出面积的严格定义。

首先，让我们澄清一下我们将要讨论的数字领域。让我们将任意闭合折线称为多重顶点，其顶点顺序 $^*$ 已被指示。

符号$\overline{A_1A_2 \dots A_n}$意味着顶点$A_2$跟随顶点$A_1$，$A_3$跟随$A_2$，...，$A_n$跟随$A_{n-1}$，最后，非常重要！ — $A_1$ 紧随$A_n$。这种顺序称为循环（或循环）。从这个定义可以看出，对于合适的$n$-顶点$\overline{A_1A_2 \dots A_n}$也可以表示如下：$\overline{A_2A_3 \dots A_nA_1}$。因此，条目$\overline{ABC}$、$\overline{BCA}$、$\overline{CAB}$表示相同的有序三顶点，条目$\overline{BAC}$、$\overline{ACB}$、$\overline{CBA}$表示不同的有序三顶点。我们会说三个顶点$\overline{ABC}$和$\overline{BAC}$是针对该位置的。

我们要为有向（有序）多顶点结构定义面积的概念。

我们就这样吧。让我们指出它的一些主要属性。这些性质不会被证明，但所有其他关于定向多顶点结构面积的陈述都将从这些性质中推导出来。 （这种定义方法，在数学中被称为公理化。）因此，我们相信每个多重顶点$\overline{A_1A_2 \dots A_n}$都被分配了一个特定的数字 - pl。 $\overline{A_1A_2 \dots A_n}$；既可以为正，也可以为负，甚至可以为零；在这种情况下，满足以下属性：

(I) $\overline{ABC} = -\text{пл. } \overline{BAC}$;

（二）$\overline{A_1A_2A_3 \dots A_n} = \text{пл. } \overline{A_1A_2A_3} + \text{пл. } \overline{A_1A_3A_4 \dots A_n}$。如果我们考虑到多重顶点$\overline{A_1A_2 \dots A_n}$与多重顶点$\overline{A_2A_3 \dots A_nA_1}$重合，那么这个性质可以写成如下：

(II') $\overline{A_2A_3 \dots A_nA_1} = \text{пл. } \overline{A_2A_3A_4} + \text{пл. } \overline{A_2A_4 \dots A_nA_1}$.

现在让我们回到定理1。对应关系(I)和(II)的弱点，它已经可以被构建和证明了！事实上，无论点 $PABC$ 在四平面上的位置如何，根据 (II) 和 (II') ，等式都会发生：pl。 $\overline{PABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC}$； pl。 $\overline{PABC} = \text{пл. } \overline{ABCP} = \text{пл. } \overline{ABC} + \text{пл. } \overline{ACP}$ 因此 pl。 $\overline{PAB} + \text{пл. } \overline{PBC} = \text{пл. } \overline{ABC} + \text{пл. } \overline{ACP}$，即 pl。 $\overline{ABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC} - \text{пл. } \overline{ACP}$。考虑到凭借（I），pl。 $\overline{ACP} = -\text{пл. } \overline{PCA}$，我们得到pl。 $\overline{ABC} = \text{пл. } \overline{PAB} + \text{пл. } \overline{PBC} + \text{пл. } \overline{PCA}$。

现在尝试找出定理 1 的必要符号：

定理2. 无论点$P$位于有序多重顶点$\overline{A_1A_2 \dots A_n}$的平面上，都等式pl。 $\overline{A_1A_2 \dots A_n} = \text{пл. } \overline{PA_1A_2} + \text{пл. } \overline{PA_2A_3} + \dots + \text{пл. } \overline{PA_nA_1}$。

由此得出一个推论

⟦folio 7⟧

图 12，一个。

问题 4. 证明 $(A_3)$ if
a) $\lambda$ 是正整数，
b) $\lambda$ 是有理正数，
c) $\lambda$ 是负有理数。

对应关系$(A'_3)$$S(\lambda AB, MN) = S(AB, MN) \cdot \lambda$也是有效的。 （您应该只使用 $(A_3)$ 和 $(A_2)^*$。））

为了总结这个公式列表，我们将证明它们暗示着整个平面理论的一个非常重要的定理：

如果线段 $AB$ 和 $CD$ 共线（即位于平行线或同一条线上），则

$$S(\overrightarrow{AB}, \overrightarrow{CD}) = 0^*.$$

事实上，由于$(A_2)$，我们有

$$S(\overrightarrow{AB}, \overrightarrow{AB}) = -S(\overrightarrow{AB}, \overrightarrow{AB}),$$

因此

$$S(\overrightarrow{AB}, \overrightarrow{AB}) = 0.$$

如果线段$\overrightarrow{CD}$与线段$\overrightarrow{AB}$共线，则$\overrightarrow{CD} = \lambda \overrightarrow{AB}$；这就是为什么

*) 公式$(A_3)$和$(A'_3)$对于无理数$\lambda$的有效性不能根据公式$(A_1)$建立。为了将这些公式扩展到无理数$\lambda$，有必要对表达式$S(\overrightarrow{AB}, \lambda MN)$作为$\lambda$的函数施加neokotny限制。例如，假设该函数是单调的就足够了。

**）是的，这非常酷！ ——读者会说。

毕竟，建立在共线线段上的平行四边形$PQRS$可以表达如下：它的所有顶点都位于同一条直线上，因此它的面积为零。然而，在这个“de-wonder”中使用“posto”这个词在逻辑上根本不合理——只有在那些情况下，当我们依赖I、II、III的主要规定，或者依赖已经在它们的帮助下证明的定理时，我们才能说“posto”。

⟦folio 8⟧

三．任意有序平面多重顶点的定向平面的计算

7. 令$O$为平面上任意选择的点，并令位于其中的向量$\overrightarrow{OE}_1$和$\overrightarrow{OE}_2$为非圆。

如果$x_1$和$x_2$是两个任意数，则向量$x_1\overrightarrow{OE}_1+x_2\overrightarrow{OE}_2$称为向量$\overrightarrow{OE}_1$和$\overrightarrow{OE}_2$的线性组合。

让

(1) $x_1\overrightarrow{OE}_1+x_2\overrightarrow{OE}_2=\overrightarrow{OP}$.

因此，指定一对有序数字 ($x_1; x_2$) 同时确定点 $P$（对应于该对）。通常说，$x_1$是点$P$的第一个坐标，$x_2$是点$P$相对于由原点$O$和“尺度向量”$\overrightarrow{OE}_1$和$\overrightarrow{OE}_2$定义的坐标系$\langle O; E_1, E_2 \rangle$的第二个坐标。

在下面的演示中，我们将假设点 $O$ 以及向量 $\overrightarrow{OE}_1$ 和 $\overrightarrow{OE}_2$ 是固定的，并且我们将使用符号 (1) 以及简短符号：$P=(x_1, x_2)$。

问题 6. 平面 ($O, E_1, E_2$) 的点在哪里：

a) 第一个坐标（在系统$\langle O; E_1, E_2 \rangle$中）是某个正（负）数，第二个坐标为零，

b) 两个坐标均为正（负）数，

b) 谁的第一个坐标为正（负），第二个坐标为正）？

给定公式（1）中数字$x_1$和$x_2$所有可能的值，我们得到包含点$O$、$E_1$、$E_2$的平面的所有可能的向量$\overrightarrow{OP}$；换句话说，该平面的每个点$P$都有自己的一对坐标：$x_1; x_2$（图13）。很容易看出，它们可以使用以下公式计算：

(2) $x_1 = \frac{\pi l. \overrightarrow{OPE}_2}{\pi l. \overrightarrow{OE}_1 E_2}; \quad x_2 = \frac{\pi l. \overrightarrow{OPE}_1}{\pi l. \overrightarrow{OE}_2 E_1}$.

事实上，乘以（倾斜！）倍

⟦folio 9⟧

四．莫比乌斯问题及其产物

10. 在这个标题的文章中（我们杂志去年的第三期），我们提出要证明，无论五角星A、B、C、D、E在平面中的位置如何，五边形$\overline{ABCDE}$的面积x是二次方程的根

(3) $x^2 - x(a + b + c + d + e) + (ab + bc + cd + de + ea) = 0$,

其中a、b、c、d、e是有向三顶点$\overline{ABC}, \overline{BCD}, \overline{CDE}, \overline{DEA}, \overline{EAB}$的面积。

这个问题之所以引起人们的特别兴趣，是因为五元组$\overline{ABCDE}$可以是非凸的，甚至可以是边相交的五元组（图14）；因此，数字 a、b、c、d 和 e 也可以为负数也就不足为奇了。

莫比乌斯给出的优雅证明使用了他所描绘的特殊数学装置 - 重心微积分（重心 - 重心），这是莫比乌斯在研究固体力学问题时发现的。现代向量代数也是在莫比乌斯这些思想的影响下产生的。我们将向读者介绍莫比乌斯问题的向量证明 - 它使用上面描述的定向区域理论，更准确地说，是第 8 段中证明的“莫比乌斯恒等式” - 我们将写如下：

pl。 $\overline{ABC} \cdot$ pl。 $\overline{ADE}$ +
(4) + pl。 $\overline{ADB} \cdot$ pl。 $\overline{ACE}$ +
+ pl。 $\overline{ABE} \cdot$ pl。 $\overline{ACD} = 0$。

由于定向区域 pl 的特性。 $\overline{ABCDE} = x =$ pl。 $\overline{ABC}$ +
+ pl。 $\overline{ACD} +$ pl。 $\overline{ADE} = a +$ pl。 $\overline{ACD} +$d；

x = 平方 $\overline{CDE} +$ pl。 $\overline{CEA}$ +
+ pl。 $\overline{CAB} = c +$ pl。 $\overline{CEA} + a$,

x = 平方 $\overline{DEA} +$ pl。 $\overline{DAB}$ +
+ pl。 $\overline{DBC} = d +$ pl。 $\overline{DAB} + b$，因此
