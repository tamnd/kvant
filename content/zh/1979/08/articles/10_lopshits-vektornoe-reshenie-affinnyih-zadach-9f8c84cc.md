---
id: 1979-8-lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc
issue: kvant_1979_8
year: 1979
number: "8"
title: 仿射问题的向量解
authors:
  - Лопшиц А. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 35
page_labels: 30-33
tag: QZ3X
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 59d02cf11419446b1b2a283688411e296cf7c496e06d9f903ed0d880b152a372
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/10_lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc.md
source_content_sha256: 2d0eb0bcb2d06500dce796a43211d48ee00c4f69edfe38cea6479fc67dd04570
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

仿射问题的向量解

在这节数学课中，我们将学习如何解决某种类型的几何问题 - 所谓的仿射问题。我们不会提前解释这些任务是什么。我们希望您在阅读本文后能够理解这一点。

1. 莫利定理的情感版本

在1978年的«Kvant»第8期（第28页）中，考虑了以下显着的定理：如果在三角形ABC中画出A、B和C的三等分线，那么它们靠近边的交点就是等边三角形的顶点。如果将 trisecgris 替换为 tris，即穿过三角形顶点并将其对边分成三等份的直线，会发生什么？事实证明……然而，真正的读者自己会完成定理的表述，找出三角形$P_{14}P_{36}P_{25}$的性质（符号很容易沟通，说

图 1

在图 1）上，将验证六边形$P_{13}P_{46}P_{15}P_{24}P_{35}P_{26}$的边与原三角形ABC的边平行，并最终证明该六边形边的中点与点$P_{36}, P_{23}, P_{25}, P_{45}, P_{14}, P_{61}$位于三条直线上。如果您还不明白如何解决这个问题，请不要担心。读完本文后，您无疑能够做到这一点。让我们从一个更简单的任务开始。

2. 刘易斯·卡罗尔的亲和力问题

集合中的倒数第二个问题“在不眠之夜发明的三月天问题” *) 要求在给定的三角形中写一个六边形，使其相对边相等且平行，其中三个位于三角形的边上，对角线相交于三角形内的给定点。卡罗尔给出的解决方案使用了古代学童给出的方法（八十年代已经过去了几个世纪）。我们将考虑卡罗尔问题的更一般的表述，并使用七年级学生熟悉的工具来解决它 - 其中。当然，如果没有他们的帮助，卡罗尔的问题并不难解决。但正因为它不难，所以你学得很好！

我们将用以下公式解决卡罗尔问题：在三角形 ABC 的边 BC、CA 和 AB 的线上，我们将相应地放置点 $A_1$ 和 $A_2$、$B_1$ 和 $B_2$、$C_1$ 和 $C_2$，使得六边形 $A_1A_2B_1B_2C_1C_2$ 的相对顶点（即点$A_1$和$B_2$，$A_2$和$C_1$，$B_1$和$C_2$）关于点P对称，在三角形ABC（图2）**）平面上任意定义。 （这样的六边形称为中心六边形。）

*）刘易斯·卡罗尔。结的故事（M.，Mir，1973）。
**) 这是我们的公式的伟大概括 - 卡罗尔认为点 P 位于三角形 ABC 内。

⟦folio 31⟧

3. 矢量分解

我们需要以下事实：如果向量$\vec{a}$和$\vec{b}$不共线，则与向量$\vec{a}$、$\vec{b}$位于同一平面的任何向量$\vec{c}$可以表示为

$$\vec{c} = \alpha \vec{a} + \beta \vec{b}$$

（这里$\alpha$和$\beta$是实数），并且这样的表示是唯一的（参见“几何9”第23节的定理）。

我们将这种表示形式称为向量 $\vec{c}$ 分解为向量 $\vec{a}$ 和 $\vec{b}$ (图 3)。

请注意，如果$O$是平面的固定点，则可以在平面的任意点$M$构造向量$\overrightarrow{OM}$。点$O$称为极点，向量$\overrightarrow{OM}$是点$M$的半径向量。半径向量$\overrightarrow{OM}$唯一确定“自己的”点$M$；为了简洁起见，我们将其表示为$\overrightarrow{M}$。

4. 卡罗尔问题的解决方案

让我们选择这个三角形的顶点 $C$ 作为极点。

让我们将给定点 $P$ 的半径向量展开为向量 $\vec{A}$ 和 $\vec{B}$：

$$\vec{P} = \alpha \vec{A} + \beta \vec{B}.$$

由于所需点 $A_1$ 位于直线 $CB$ (图 2) 上，

$$\vec{A}_1 = x\vec{B},$$

其中$x$是点$A_1$从有向线段$\overrightarrow{CB}$“切断”的分数。我们将“切断”一词放在引号中，因为点$A_1$不一定位于线段$CB$内；它甚至可以“切断”负“份额”（在本例中为$x < 0$）。类似地，对于所需点$B_2$，我们得到

$$\vec{B}_2 = y\vec{A}$$

（这里$y$是期望点从有向线段$\overrightarrow{CA}$“切断”的分数）。由于点 $P$ 是线段 $A_1B_2$ 的中点，因此得出以下结论（§ 22“几何 9”）

$$\vec{P} = \frac{1}{2} (\vec{A}_1 + \vec{B}_2),$$

那是

$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} (x\vec{B} + y\vec{A}),$$

在哪里

$$x = 2\beta, y = 2\alpha$$

因此

$$\vec{A}_1 = 2\beta\vec{B}, \quad \vec{B}_2 = 2\alpha\vec{A}.$$

这些等式使我们能够构造点 $A_1$ 和 $B_2$。

找到点$B_1$和$C_2$有点困难。如果点$B_1$从有向线段$\overrightarrow{CA}$中切掉部分$z$，则

$$\vec{B}_1 = z\vec{A}.$$

现在让我们为点 $C_2$ 的半径向量编写一个表达式，从有向线段 $\overrightarrow{AB}$ 中截去分数 $u$：

$$\vec{AC}_2 = u\vec{AB}.$$

让我们使用 $\vec{AC}_2 = \vec{C}_2 - \vec{A}$; 这个事实$\vec{AB} = \vec{B} - \vec{A}$。因此 $u(\vec{B} - \vec{A}) = \vec{C}_2 - \vec{A}$ 因此 $\vec{C}_2 = \vec{A} + u(\vec{B} - \vec{A}) = (1 - u)\vec{A} +$

⟦folio 32⟧

+ $u\vec{B}$。按条件
$$P = \frac{1}{2} (\vec{B}_1 + \vec{C}_2),$$
那是
$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} [z\vec{A} + (1 - u)\vec{A} + u\vec{B}]$$
因此
$$u = 2\beta, z = 2\alpha + 2\beta - 1$$
$$\vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A},$$
$$\vec{C}_2 = (1 - 2\beta)\vec{A} + 2\beta\vec{B}.$$
独立完成最后阶段，读者将确信
$$\vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B},$$
$$\vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}.$$
由此我们发现卡罗尔问题是有解的（无论点$P!$如何指定）并且这个解是唯一的：
$$\begin{cases} \vec{A}_1 = 2\beta\vec{B}, \vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B} \\ \vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A}, \vec{B}_2 = 2\alpha\vec{A} \\ \vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}, \vec{C}_2 = \\ = (1 - 2\beta)\vec{A} + 2\beta\vec{B} \end{cases}$$

5. 偏离了卡罗尔的问题。
$\vec{C}_2$公式的推导实际上证明了以下一般结果：如果$\vec{A}$和$\vec{B}$是任意点$A$和$B$的半径向量（相对于任意选择的策略$C!$），则属于线$AB$并切断的点的半径向量$\vec{M}$从有向线段$\vec{AB}$“分享”$\lambda$，即点$M$，其中$\vec{AM} = \lambda\vec{AB}$（图 4），由一个简单而优美的公式确定：
$$\vec{M} = (1 - \lambda)\vec{A} + \lambda\vec{B}.$$ (!!)
应该记住这个公式 - 它在解决许多几何问题方面有很好的用户应用*)。

*) 请参阅 V. Boltyansky 的文章“一条直线上的三个点”（«Kvant»，1978 年，第 10 期）和 I. Gabovich 的文章“向量对考试的帮助”（«Kvant»，1979 年，第 1 期）。

图 4.
数字$\lambda$称为点$M$的仿射坐标（相对于初始$A$和尺度向量$\vec{AB}$指定的坐标系）。这个名字是这样定义的：毕竟，如果给定一个坐标系和任意数字$\lambda$，那么$AB$线上的点$M$是唯一确定的：
$$\vec{AM} = \lambda\vec{AB}.$$
我们回到公式
$$\vec{P} = \alpha\vec{A} + \beta\vec{B},$$
借助它，我们写下了位于三角形$ABC$平面上的点$P$的半径向量。它表明，如果给定点 $C$ 以及向量 $\vec{CA}$ 和 $\vec{CB}$ (图 5)，则指定任意有序的数字对 $\alpha$、$\beta$ 定义平面 $ABC$ 中的点 $P$。
这些数字称为点$P$的仿射坐标（在原点为点$C$的坐标系中，尺度向量为$\vec{CA}$和$\vec{CB}$）。容易看出，平面$ABC$第二坐标为零的点位于直线$CA$上；因此称为第一坐标轴。类似地，第一个坐标为零的点位于

⟦folio 33⟧

6. 卡罗尔问题的特殊情况

1) 如果点 $P$ 是三角形 $ABC$ 的质心（即中线的交点），则 (§ 22“几何 9”)
$$\overrightarrow{OP} = \frac{1}{3} (\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC})$$
因此
$$\bar{P} = \frac{1}{3} \bar{A} + \frac{1}{3} \bar{B},$$
那是
$$\alpha = \frac{1}{3}, \quad \beta = \frac{1}{3}.$$
将这些值代入公式（1），我们得到$\bar{A}_1 = \frac{2}{3} \bar{B},$
$$\bar{A}_2 = \frac{1}{3} \bar{B}, \quad \bar{B}_1 = \frac{1}{3} \bar{A}, \quad \bar{B}_2 = \frac{2}{3} \bar{A},$$
$$\bar{C}_1 = \frac{2}{3} \bar{A} + \frac{1}{3} \bar{B}, \quad \bar{C}_2 = \frac{1}{3} \bar{A} + \frac{2}{3} \bar{B}$$
因此（由于上一段所述），找到的六边形的顶点被从三角形$\frac{1}{3}$和$\frac{2}{3}$的边上切掉。

2) 设$P$为连接CA和AB边中点$B'$和$C'$的线段$B'C'$的任意点。由于该点位于线段 $B'C'$ 内部，因此它从其中切掉了部分 $0 < \lambda < 1$，并且凭借公式 (!!)，
$$\bar{P} = (1 - \lambda) \bar{B}' + \lambda \bar{C}'$$
$$\bar{P} = \frac{1 - \lambda}{2} \bar{A} + \frac{\lambda}{2} (\bar{A} + \bar{B})$$

那是
$$\alpha = \frac{1}{2}, \quad \beta = \frac{\lambda}{2}.$$
将这些值代入式（1），我们得到
$$\bar{A}_1 = \lambda \bar{B}, \quad \bar{A}_2 = \lambda \bar{B}, \quad \bar{B}_1 = \lambda \bar{A}, \quad \bar{B}_2 = \bar{A},$$
$$\bar{C}_1 = \bar{A}, \quad \bar{C}_2 = (1 - \lambda) \bar{A} + \lambda \bar{B}.$$
因此，在这种情况下，六边形$A_1A_2B_1B_2C_1C_2$退化为平行四边形$A_1A_1B_1AAC_2 = A_1B_1AC_2$（图6是针对$\lambda = \frac{4}{5}$的情况制作的）。

3) 如果点$P$任意位于非线段$B'C'$中的直线$B'C'$上，则其仿射坐标$\lambda$（在原点为$C'$、尺度向量$\overrightarrow{B'C'}$的坐标系中）要么是大于1的正数，要么是负数。当然，所构造的六边形的顶点的半径矢量是由与一般情况相同的公式确定的，但是，这些顶点（读者将亲眼看到这一点）虽然位于直线 AB、BC 和 CA 上，但将位于线段 AB、BC、CA 之外（位于 图 7 $\lambda = \frac{5}{4}$）。

4) 如果点$P$选在线段BC的中间$A'$，即$\bar{P} = \frac{1}{2} \bar{B}$，因此$\alpha = 0, \quad \beta = \frac{1}{2}$，那么，根据公式
