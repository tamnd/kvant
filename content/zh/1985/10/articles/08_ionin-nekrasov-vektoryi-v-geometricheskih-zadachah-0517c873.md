---
id: 1985-10-ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873
issue: kvant_1985_10
year: 1985
number: "10"
title: 几何问题中的向量
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: shkola-v-kvante
page_first: 23
page_last: 25
page_labels: 21-23
tag: K5Y7
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ca3d7cd295c986e592c667df02fe8217c7300115368fd7b7ad99c12ef855bfd4
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/08_ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873.md
source_content_sha256: 00cd43ae4424b31f7f2b16c8d63901ed3e55beb3ee791ff662600841fb8d5a0f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Matematika
8, 9, 10

下面发布的注释适用于十年级学生。然而，它的第一部分对于八年级和九年级的学生可能有用。

几何问题中的向量

1. 段的并行度和比例

问题1. 点K、L、M、N 是五边形ABCDE 的边BC、CD、DE、EA 的中点，点P 和Q 是线段KM 和LN 的中点。证明线段 PQ 和 AB 平行并求出它们的长度比（第 1 页）。

让我们将问题陈述翻译成矢量语言。

段 PQ 和 AB 的并行性由等式 $\overrightarrow{PQ} = k \cdot \overrightarrow{AB}$ 表示，其中 $k$ 是某个实数。计算出$k$后，我们就可以求出线段PQ和AB的长度之比。

解决这个问题的主要公式是$\overrightarrow{OZ} = \frac{1}{2}(\overrightarrow{OX} + \overrightarrow{OY})$，其中$Z$是XY线段的中点，$O$是任意点。

解决方案。 $\overrightarrow{PQ} = \overrightarrow{OQ} - \overrightarrow{OP} = \frac{1}{2}(\overrightarrow{OL} + \overrightarrow{ON}) - \frac{1}{2}(\overrightarrow{OK} + \overrightarrow{OM}) = \frac{1}{2}\left(\frac{1}{2}(\overrightarrow{OC} + \overrightarrow{OD}) + \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OE})\right) = \frac{1}{4}(\overrightarrow{OA} - \overrightarrow{OB}) = -\frac{1}{4}\overrightarrow{AB}$。

由此可见，线段 PQ 和 AB 平行，且它们的比为 $\frac{1}{4}$。

在上面的解决方案中，我们使用了两次“差分公式”

$\overrightarrow{XY} = \overrightarrow{OY} - \overrightarrow{OX}$，它允许您用从同一点绘制的向量来表达任何向量。

以下是用几何​​和矢量语言编写相同语句的一些示例：

1. A、B、C 点位于同一条直线上。
2. M 点相对于 $|AM|:|MB| = l:k$ 划分线段 AB
3. M 是三角形 ABC 中线（质心）的交点。
4. ABCD——平行线。

在后两种情况中，只要 A、B、C 点不在同一条线上，几何和矢量语句是等效的。

问题2.证明梯形底边的中点与对角线的交点位于同一条直线上（图2）。

解决方案。设M、N为梯形ABCD的底BC和AD的中点，O为对角线的交点。根据三角形 AOD 和 BOC 的相似性，可以得出：$\frac{|OA|}{|OC|} = \frac{|OD|}{|OB|}$。指定这些

⟦folio 22⟧

2. 点系的质心

质心的概念可以很容易地从三角形转移到空间中任意有限的点系统：

如果 $\overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \dots + \overrightarrow{MA}_n = \overrightarrow{0}$，点 M 称为 n 点 $A_1, A_2, \dots, A_n$ 系统的质心。

利用差分公式，最后的等式可以重写为：$(\overrightarrow{OA}_1 - \overrightarrow{OM}) + (\overrightarrow{OA}_2 - \overrightarrow{OM}) + \dots + (\overrightarrow{OA}_n - \overrightarrow{OM}) = \overrightarrow{0}$（O为任意点），

$\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n - n \cdot \overrightarrow{OM} = \overrightarrow{0}$,

$\overrightarrow{OM} = \frac{1}{n} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n)$.

从最后一个公式可以看出，任何有限的点系统都有一个质心。此外，由一个点组成的系统的质心是该点本身，一对点的质心是连接它们的线段的中间。寻找大数的质心可以通过以下原则得到原谅：如果$M_1$是k个点$A_1, A_2, \dots, A_k$的系统的质心，$M_2$是l个点$B_1, B_2, \dots, B_l$的系统的质心，并且这些系统没有公共点，那么k + l个点$A_1, A_2, \dots, A_k, B_1, B_2, \dots, Bl$的系统的质心是属于线段$M_1M_2$的点M，并且将其除以关系$|M_1M_2| = l:k$。

确实，让$k \cdot \overrightarrow{M_1M} = l \cdot \overrightarrow{MM_2}$。

利用差分公式，我们得到：

$k (\overrightarrow{OM} - \overrightarrow{OM}_1) = l (\overrightarrow{OM}_2 - \overrightarrow{OM}_1)$,

$k \cdot \overrightarrow{OM} - k \cdot \overrightarrow{OM}_1 = l \cdot \overrightarrow{OM}_2 - l \cdot \overrightarrow{OM}_1$,

$(k + l) \cdot \overrightarrow{OM} = k \cdot \overrightarrow{OM}_1 + l \cdot \overrightarrow{OM}_2$,

$\overrightarrow{OM} = \frac{k}{k + l} \overrightarrow{OM}_1 + \frac{l}{k + l} \overrightarrow{OM}_2$.

根据式(1)

$\overrightarrow{OM}_1 = \frac{1}{k} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

$\overrightarrow{OM}_2 = \frac{1}{l} (\overrightarrow{OB}_1 + \overrightarrow{OB}_2 + \dots + \overrightarrow{OB}_l)$,

所以

$\overrightarrow{OM} = \frac{1}{k + l} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

我们得到了我们需要的东西。

将这个原理应用到三角形的三个顶点上，我们发现三角形的质心位于

⟦folio 23⟧

连接该顶点与另外两个顶点的中心（即与对边的中间）的线段，并从该顶点开始计算，以 2:1 的比例划分该线段。这蕴含着众所周知的平面测量定理：三角形的中线相交于一点，并以 2:1 的比例除以该点（从顶点算起）。

同样可以证明，连接三角形顶点与相对面质心的线段相交于一点（三角形的质心），并在该点以 3:1 的比例进行划分（从顶点算起）。

3. 计算距离和角度

给定空间中的非共平面向量的三元组（基）后，可以以独特的方式将任何向量扩展到该基中。知道基向量的标量积，我们可以轻松计算任何向量的标量积，从而计算它们的长度和它们之间的角度。

任务 4. 给定 $\vec{a}\vec{b} = 1$、$\vec{a}\vec{c} = 2$、$\vec{b}\vec{c} = 0$、$\vec{a}^2 = \vec{b}^2 = 4$、$\vec{c}^2 = 2$。

如果$\vec{p} = 2\vec{a} - \vec{b}$、$\vec{q} = \vec{a} + \vec{b} + \vec{c}$，则求$|\vec{p}|$、$|\vec{q}|$、$(\vec{p}, \vec{q})$。

解决方案：让我们以“乘法表”的形式重写问题的条件（表1）。我们发现：$|\vec{p}| = \sqrt{\vec{p}^2} = \sqrt{(2\vec{a} - \vec{b})^2} = \sqrt{4\vec{a}^2 - 4\vec{a}\vec{b} + \vec{b}^2} = \sqrt{16} = 4$；

$|\vec{q}| = \sqrt{\vec{q}^2} = \sqrt{(\vec{a} + \vec{b} + \vec{c})^2} = \sqrt{\vec{a}^2 + \vec{b}^2 + \vec{c}^2 + 2\vec{a}\vec{b} + 2\vec{a}\vec{c} + 2\vec{b}\vec{c}} = \sqrt{16} = 4$.

从标量积的定义我们得到：

$$\cos(\vec{p}, \vec{q}) = \frac{\vec{p}\vec{q}}{|\vec{p}| \cdot |\vec{q}|} = \frac{2(\vec{a} - \vec{b})(\vec{a} + \vec{b} + \vec{c})}{16} = \frac{2\vec{a}^2 + \vec{a}\vec{b} + 2\vec{a}\vec{c} - \vec{b}^2 - \vec{b}\vec{c}}{16} = \frac{9}{16},$$

从哪里$(\vec{p}, \vec{q}) = \arccos \frac{9}{16}$。

问题 5. 底$ABCA_1B_1C_1$ 是正三角形。侧边$AA_1$是底座边的两倍大，并形成角度$A_1AB = 90^\circ$、$A_1AC = 60^\circ$。 O 是三角形 $ABC$ 的中心。在直线 $CC_1$ 上找到点 $K$，使得直线 $B_1K$ 和 $A_1O$ 垂直。

解决方案。直线$CC_1$上点$K$的位置由等式$\vec{C}_1\vec{K} = x \cdot \vec{C}_1\vec{C}$中系数$x$的值确定。让我们用$a$表示识别底边的长度，选择向量三元组$\vec{m} = \vec{AB}$，$\vec{n} = \vec{AC}$，$\vec{p} = \vec{AA}_1$（图5）作为基础，然后我们编制一个“乘法表”（表2）。

让我们将向量$\vec{A}_1\vec{O}$和$\vec{B}_1\vec{K}$分解为基$(\vec{m}, \vec{n}, \vec{p})$：$\vec{A}_1\vec{O} = \vec{A}_1\vec{A} + \vec{A}O = -\vec{p} + \frac{1}{3}(\vec{m} + \vec{n}) = \frac{1}{3}(\vec{m} + \vec{n} - 3\vec{p})$，$\vec{B}_1\vec{K} = \vec{B}_1\vec{A}_1 + \vec{A}_1\vec{C}_1 + \vec{C}_1\vec{K} = \vec{m} + n - x\vec{p}$。写出垂直于素数$A_1O$和$B_1K$的条件：

$(\vec{m} + \vec{n} - 3\vec{p})(-\vec{m} + \vec{n} - x\vec{p}) = 0$，我们使用表2得到：$11a^2x - 3a^2 = 0$，其中$x = \frac{3}{11}$。

练习

1. 在地形$ABCD$中，点$E$和$F$是边$AB$和$CD$的中点。证明线段$CE, DE, AF$的中点是平行四边形的顶点。

2. 点 $A, B, C, D, E, F$ 不在同一平面上。证明如果直线$AB$和$DE, BC$以及$EF, CD$和$AF$平行，则$|AB| = |DE|, |BC| = |EF|, |CD| = |AF|$。

3. 证明连接平行四边形四边形底中点的线段相交于一点。他们在哪些方面有共同的观点？

4. 证明上一个练习中讨论的四边形的中点是平行四边形的顶点。
