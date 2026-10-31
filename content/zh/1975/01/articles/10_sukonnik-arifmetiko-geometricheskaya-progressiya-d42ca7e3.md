---
id: 1975-1-sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3
issue: kvant_1975_1
year: 1975
number: "1"
title: 算术几何级数
authors:
  - Суконник Я. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 40
page_labels: 36-38
tag: PPLZ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4070098ed7177b22a19d3712cfad95aa79728205e193c33ff94ed35fa671bd08
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/10_sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3.md
source_content_sha256: 6b0588f272ef65c305545680949173fb6cbee224cc9251557178811ee51f78bc
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦rubric⟧ 数学圈

## 算术几何级数
Y·N·苏康尼克

数学可以通过不同的方式来研究。你可以听讲座，也可以拿一本厚厚的书，连续阅读：定义、定理、证明。或者你可以采取更积极的行动：阅读定理的定义和陈述，把书放在一边，自己想出证明。第一种方法一开始可以移动得更快。但只有第二种方法才能让你深入理解数学理论，长期记住它并学会应用它。因此，数学研讨会、学校和俱乐部经常使用这种方法——独立发现古老的真理。

“数学圈”版块发表的文章正是针对这种读者的积极主动的工作而设计的。通常，这些文章是通过共同主题或解决方法联合起来的一系列问题。其中一些在文本中得到了解决，但大多数（无论简单还是困难）都留给读者自己决定。有时，这些问题的简短解决方案（或说明和答案）会放在同一期中，但更常见的是 - 放在杂志的下一期最后一页上。

通常，我们的“数学俱乐部”面向 8 至 9 年级的学生，有时甚至是 7 年级的学生。请寄出关于本部分的评论和建议的信件，并在信封上注明“数学圈”。

许多全联盟奥林匹克竞赛的参与者与数学界保持着定期的通信。

⟦column⟧

本文研究了一个可以粗略地称为“算术几何级数”的序列；它由以下递推关系给出：

$$u_1 = a_1, \quad u_{n+1} = qu_n + d, \qquad (1)$$

其中 $q$ 和 $d$ 是常量参数。将 $q = 1$ 代入 (1)，我们得到一个*算术*级数

$$u_1 = a_1, \quad u_{n+1} = u_n + d,$$

将 $d = 0$，- *几何*：

$$u_1 = a_1, \quad u_{n+1} = qu_n.$$

（这就解释了为什么我们称数列（1）为算术几何级数。以此类推，$q$是分母，$d$是算术几何级数的差。）

算术几何级数的例子

a) $1, \ \dfrac{3}{2}, \ \dfrac{7}{4}, \ \dfrac{15}{8}, \ \dfrac{31}{16}, \ \cdots$

$$\left(u_1 = 1, \ q = \frac{1}{2}, \ d = 1\right);$$

b) $-1, \ \dfrac{3}{2}, \ \dfrac{1}{4}, \ \dfrac{7}{8}, \ \dfrac{9}{16}, \ \cdots$

$$\left(u_1 = -1, \ q = -\frac{1}{2}, \ d = 1\right).$$

讨论此类序列的想法是由 ���题 M97 引发的，它发表于 1971 年的«Kvant» 第 8 期（在“问题书 «Kvant»”中）。这是她的情况（略有修改）：

⟦folio 36⟧

*在底边为$AB = a$和$A_1B_1 = a_1$$(a < a_1)$的梯形$AA_1B_1B$中，绘制一条线段$A_2B_2$连接对角线的中点。在生成的梯形$AA_2B_2B$中，再次绘制线段$A_3B_3$，连接对角线的中点，依此类推。求线段 $A_{n+1}B_{n+1}$ 的长度。*

在图 1 上描绘了梯形$AA_nB_nB$ - 这里$AB = a$、$CD$ 是梯形的中线，$A_{n+1}$ 和$B_{n+1}$ 是对角线$A_nB$ 和$AB_n$ 的中点。很明显，点$A_{n+1}$和$B_{n+1}$位于$CD$上。用$a_n$和$a_{n+1}$表示线段$A_nB_n$和$A_{n+1}B_{n+1}$的长度，我们得到

$$a_{n+1} = |A_{n+1}B_{n+1}| =$$
$$= |A_{n+1}D| - |B_{n+1}D| = \frac{1}{2}\,a_n - \frac{1}{2}\,a,$$

因此，线段 $A_nB_n$ 的长度精确地形成了一个“算术几何级数”。

算术几何级数兼具算术级数和几何级数的特征。让我们推导其通项的公式。

设关系式 (1) $q \neq 1$（和 $d \neq 0$）。将表达式 $\dfrac{d}{q-1}$ 添加到 (1) 两边，我们得到

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right).$$

考虑到这种关系是循环的，我们为 $k = n+1, n, \ldots, 2$ 写出类似的等式：

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right),$$

$$u_2 + \frac{d}{q-1} = q\left(a_1 + \frac{d}{q-1}\right).$$

通过将书面等式相乘并减少相同的因子，我们得到*算术几何级数的通项公式*

$$\boxed{u_{n+1} = q^n\left(a_1 + \frac{d}{q-1}\right) + \frac{d}{1-q}.}\qquad(2)$$

⟦column⟧

⟦figure⟧
图 1.

在���题 M97$a_{n+1} = \dfrac{1}{2}\,a_n - \dfrac{1}{2}\,a$中，即$q = \dfrac{1}{2}$、$d = -\dfrac{1}{2}\,a$；这就是为什么

$$a_{n+1} = |A_{n+1}B_{n+1}| = \frac{1}{2^n}\,(a_1 + a) - a.$$

现在让我们阐述算术几何级数的一些基本性质（我们将证明留给读者）。

$1^\circ$。算术几何级数 (1) 是一个*二阶循环序列*\*)，由下式给出

$$u_{n+1} = (q+1)\,u_n - qu_{n-1}.\qquad(3)$$

特别是，对于$q = 1$，我们获得了算术级数的特征属性

$$u_n = \frac{u_{n-1} + u_{n+1}}{2}.$$

推论：算术几何级数的分母 $q$ 由以下公式确定

$$q = \frac{u_{n+1} - u_n}{u_n - u_{n-1}}.\qquad(4)$$

$2^\circ$。定义算术几何级数的差 $d$

---

\*) 如果存在自然数$k$和数字$a_1, a_2, \ldots, a_k$，则序列$u_1, u_2, \ldots, u_n, \ldots$称为*$k$阶的返回序列*，使得从某个数字$N$开始并且对于所有后续数字$m \geqslant N$
$$u_{m+k} = a_1u_{m+k-1} + a_2u_{m+k-2} + \ldots + a_ku_m.$$
最后一个关系称为*$k$阶的倒数方程*。

⟦folio 37⟧

根据公式

$$d = \frac{u_n^2 - u_{n-1}\cdot u_{n+1}}{u_n - u_{n-1}}. \qquad (5)$$

特别地，如果$d = 0$（和$q \neq 1$），我们获得等比级数的特征属性

$$u_n = \sqrt{u_{n-1}\cdot u_{n+1}}.$$

$3^\circ$（*算术几何级数的特征*）。数列$\{a_n\}$（其中$a_n = u_{n+1} - u_n$）是具有相同分母$q$的等比级数，即

$$|u_{n+1} - u_n| =$$
$$= \sqrt{|u_n - u_{n-1}|\cdot|u_{n+2} - u_{n+1}|}. \qquad (6)$$

$4^\circ$。子序列

$$S_1 = u_1, \quad S_2 = u_1 + u_2, \quad \ldots,$$
$$S_n = u_1 + \ldots + u_n,$$
$$S_{n+1} = S_n + u_{n+1}, \quad \ldots$$

算术几何级数项的*部分和*是三阶倒数序列，由以下等式给出：

$$S_{n+1} = (q+2)\,S_n -$$
$$- (2q+1)\,S_{n-1} + qS_{n-2}. \qquad (7)$$

$5^\circ$。如果部分和的序列$S_1$、$\ldots$、$S_n$、$\ldots$是算术几何级数，则序列$u_1, \ldots, u_n \ldots$是等比级数。

评论。从算术几何级数的通项公式（见公式（2））可以得出：

a) 对于$|q| < 1$，算术几何级数*收敛*（对于$0 \leqslant q < 1$ - *单调*）到数字

$$A = \lim_{n \to \infty} u_n = \frac{d}{1-q};$$

b) 在 $|q| \geqslant 1$ 处，算术几何级数*发散*。

特别是，通过将���题 M97中的数字$n$指向无穷大，我们在极限中得到

$$b = \lim_{n \to \infty}|A_{n+1}B_{n+1}| = \left|\frac{-\dfrac{1}{2}\,a}{1 - \dfrac{1}{2}}\right| = a.$$

⟦column⟧

（有趣的是，如果在���题 M97而不是条件$a < a_1$我们需要$a > a_1$，那么

$$|A_{n+1}B_{n+1}| = -\frac{1}{2}\,a_n + \frac{1}{2}\,a,$$

那是

$$|A_{n+1}B_{n+1}| = \left(-\frac{1}{2}\right)^n\left(a_1 - \frac{a}{3}\right) + \frac{a}{3},$$

和

$$b = \lim_{n \to \infty} A_{n+1}B_{n+1} = \frac{a}{3}\Bigg).$$

熟悉算术几何级数有时有助于解决一些几何问题。例如，考虑以下问题：

*延长锐角三角形$A_1B_1C_1$的高，直到它们分别与外接圆相交于点$A_2$、$B_2$、$C_2$，这些点分别作为锐角三角形$A_2B_2C_2$的顶点。三角形$A_2B_2C_2$的高分别延伸到与外接圆的交点$A_3$、$B_3$、$C_3$，这些点分别作为锐角三角形$A_3B_3C_3$的顶点，依此类推 - 直到三角形$A_{n+1}B_{n+1}C_{n+1}$（含）。假设三角形 $A_1B_1C_1$ 的角度已知，求三角形 $A_{n+1}B_{n+1}C_{n+1}$ 的角度。*

解决方案。 图 2 显示一个圆以及内接于其中的锐角三角形 $A_nB_nC_n$ 和 $A_{n+1}B_{n+1}C_{n+1}$。让我们通过角度$A_n$来表达角度$A_{n+1}$：

$$\angle A_{n+1} = \angle B_{n+1}A_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}A_{n+1}A_n + \angle A_nA_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}B_nA_n + \angle A_nC_nC_{n+1} =$$
$$= \left(\frac{\pi}{2} - \angle A_n\right) +$$
$$+ \left(\frac{\pi}{2} - \angle A_n\right) = \pi - 2\angle A_n,$$

那是

$$\angle A_{n+1} = -2\angle A_n + \pi$$

角度序列$A_1$、$A_2$、$\ldots$、$A_{n+1}$ 形成算术几何级数。利用公式(2)我们发现

$$\angle A_{n+1} = (-2)^n\cdot\left(\angle A_1 - \frac{\pi}{3}\right) + \frac{\pi}{3}.$$

⟦folio 38⟧
