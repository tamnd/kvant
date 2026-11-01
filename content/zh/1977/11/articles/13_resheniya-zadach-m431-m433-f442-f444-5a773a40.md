---
id: 1977-11-resheniya-zadach-m431-m433-f442-f444-5a773a40
issue: kvant_1977_11
year: 1977
number: "11"
title: 问题解决方案M431—M433； F442—F444
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 51
page_last: 53
page_labels: 49-51
tag: 32ZX
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5db605ec78845f0d98d1c924389ec897dea1079bbd888885c6c84d087fb54341
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/13_resheniya-zadach-m431-m433-f442-f444-5a773a40.md
source_content_sha256: 6544da969551fc965bf41179e9a3871c911adfd75ea89f2c62fee8b55b9c429a
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

问题解决方案
M431—M433; F442—F444

M431。森林里生长着圆柱形的树木。将一根电线从 A 点穿过森林延伸到 B 点需要连通性，它们之间的距离等于 l。证明为此目的，一根 1.6 升长的电线足以进行连接。

让我们连接点 A 和 B。在没有树木的区域，我们将沿着这条线画一条线。在直线 AB 与树干轮廓相交的同一位置，让我们沿着两个圆中较小的一个绕线，通过垂直于树干的平面限制树干的截面（参见 图 1）。让我们证明，在这种情况下，电线的长度不超过 $\frac{\pi l}{2}$。

令 $a_1, \dots, a_n$ 为导线直线段的长度，$b_1, \dots, b_k$ 为位于树干内的直线段 AB 的长度。由于每个$b_i$（$i=1, \dots, k$）不超过相应圆的直径，导线的弯曲部分的总长度不超过$\frac{\pi b_1}{2} + \dots + \frac{\pi b_k}{2}$，并且导线的总长度不超过$\frac{\pi l}{2}$，所以在这个不等式中不可能用less来代替，因为很容易指出需要长度为$\frac{\pi l}{2}$的导线的例子：森林中生长着一棵直径为l的树，并且A 点和 B 点是树干圆周上完全相对的点。

A·阿尔特席勒

图 1.

M432。是否存在一个完全平方数，其数字之和等于
a) 1977;
b) 1978?
c) 找出哪些自然数可以是整数平方的数字之和。

让我们立即解决问题的b)点。首先，我们注意到平方的数字之和不能是任意的。事实上，情人的数字的平方除以 9 时，得到的余数为 1, 4, 7。除以 9，平方的数字之和也是如此，因此对于平方，数字之和可以是 9k、或 9k+1、或 9k+4、或 9k+7 的形式。让我们证明所有这些数字确实可以是和。

事实上，数字 9k 是数字 $10^k-1$ 的平方的数字之和：

$$(10^k-1)^2 = (10^k-2) \cdot 10^k + 1 = \underbrace{99 \dots 98}_{k} \underbrace{00 \dots 01}_{k};$$

⟦folio 50⟧

数字$9k+1$ ($k \neq 0$) - 数字$10^k-2$的平方的数字之和：
$$(10^k-2)^2 = (10^k-4) \cdot 10^k + 4 = \underbrace{99 \ldots 96}_{k} \underbrace{00 \ldots 04}_{k}$$

（情况$k=0$非常识别：$1=1^2$）；数字$9k+4$ ($k \neq 0$) - 数字$10^k-3$的平方的数字之和：
$$(10^k-3)^2 = (10^k-6) \cdot 10^k + 9 = \underbrace{99 \ldots 94}_{k} \underbrace{00 \ldots 09}_{k}$$

（对于$k=0$，我们得到数字4，以及$4=2^2$）。数字$9k+7$是数字$10^k+1-5$的平方的各位数字之和：
$$(10^k+1-5)^2 = (10^k+1-10) \cdot 10^k+1 + 25 = \underbrace{99 \ldots 90}_{k+1} \underbrace{00 \ldots 025}_{k+1}$$

因此，数字 1978 可以是平方数之和，但 1977 不能。

L·利马诺夫

M433。在凸鞋跟处
边 ABCDE 边
BC 平行于对角线
AD、CD面-对角线
BE，边 DE - 对角线
AC 和 AE 侧 -
对角线 BD (图 2)。证明AB边与对角线CE平行。

图 2.

设$F = [AD] \cap [BE]$、$G = [AC] \cap [BE]$和$K = [BD] \cap [AC]$（参见图2）。

从三角形$AEF$和$BCD$的相似性可以得出：
$$\frac{|AF|}{|EF|} = \frac{|BC|}{|CD|}.$$ 因此，$$\frac{|AF| + |BC|}{|EF| + |CD|} = \frac{|BC|}{|CD|}$$

和 $$\frac{|AD|}{|BE|} = \frac{|BC|}{|CD|},$$ 自 $|BC| = |DF|$、$|BF| =$
$= |CD|$，即
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|}.$$ (1)

类似地，根据三角形$BKC$和$AED$的相似度我们得到
$$\frac{|AE|}{|BD|} = \frac{|DE|}{|AC|}.$$ (2)

最后，从三角形$BKG$和$AGE$的相似度来看
$$\frac{|BG|}{|BK|} = \frac{|CD|}{|AE|},$$ 从 $$\frac{|BE|}{|BD|} = \frac{|CD|}{|AE|},$$

或者
$$\frac{|CD|}{|BE|} = \frac{|AE|}{|BD|}.$$ (3)

从对应关系 (1) - (3) 可以得出：
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|} = \frac{|AE|}{|BD|} = \lambda.$$ (4)

下一个：
$$\vec{BC} + \vec{CD} + \vec{DE} + \vec{EA} + \vec{AB} = \vec{0},$$
$$\vec{AD} + \vec{BE} + \vec{DB} + \vec{CA} + \vec{EC} = \vec{0},$$

和$$\vec{BC} = \lambda \vec{AD}, \vec{CD} = \lambda \vec{BE}, \vec{DE} = \lambda \vec{CA}, \vec{EA} = \lambda \vec{DB}.$$

波塞托姆
$$\vec{0} = \lambda (\vec{AD} + \vec{BE} + \vec{CA} + \vec{DB}) + \vec{AB} = -\lambda \vec{EC} + \vec{AB},$$

其中$$\vec{AB} = \lambda \vec{EC},$$表示对角线$EC$的边$AB$平行。

使用共角坐标系可以获得更短的解。令点 $D, C$ 和 $E$ 的坐标为 $D(0; 0), C(1; 0), E(0; 1)$ (图 2)。那么$A$和$B$有坐标$(1; a)$和$(b; 1)$，因为$(CD) \parallel (BE), (DE) \parallel (AC).$

⟦folio 51⟧

并行条件$(AE) \parallel (BD)$和$(BC) \parallel (AD)$写为：

$$\frac{a-1}{1-0} = \frac{1-0}{b-0} \quad \text{и} \quad \frac{1-0}{b-1} = \frac{a-0}{1-0},$$

即$b(a-1)=1$、$a(b-1)=1$，由此产生$a=b$和$\frac{a-1}{1-b} = \frac{1-0}{0-1}$，即$(AB) \parallel (EC)$。

请注意，本问题中讨论的斑点 $ABCDE$ 可以通过仿射变换（或简单的倾斜）变成规则的。

I.克鲁莫娃、E.图尔克维奇

F442。质量为 1、2、3 和 4 ke 的球由光棒连接，每根光棒长 1 m。这些杆紧固在一起，形成十字 (图3)。系统可以绕经过点O且垂直于平面图的轴自由旋转。如果在初始时刻，连接具有质量 $m_2=2$ke 和 $m_4=4$ke 的球的杆是垂直的并且球静止不动，求系统振荡的幅度。

图 3.

F443。如您所知，地球绕地轴转一圈需要 23 小时 56 分 4 秒。因此，在白天，所有表盘分为24小时的手表都必须静置近4分钟。这相当于在 23 小时 56 分 4 秒内几乎绕轴旋转一整圈。因此，在每个地球上仍然可以观察到，天空中的星星在时间$T$中绕其轴旋转一周需要23小时56分4秒，太阳“绕”地球一周需要24小时（与此相关，所有地球时钟的表盘都被划分为24小时）。

发生这种情况的原因是，在绕其轴旋转一周的过程中，地球围绕太阳的轨道运动设法前进了大约 1/365 小时的轨道长度 (图 5)。例如，虽然地球仪绕其轴旋转了一整圈，因此粗略地说，地球上的观察者在同一个地方看到了太阳（例如，在他的手表上注意到正午的开始），地球仪还必须自转一小时的 1/365，这大约需要 4 分钟。

B·布霍夫采夫
