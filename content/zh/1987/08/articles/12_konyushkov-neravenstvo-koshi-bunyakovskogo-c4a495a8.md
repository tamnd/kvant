---
id: 1987-8-konyushkov-neravenstvo-koshi-bunyakovskogo-c4a495a8
issue: kvant_1987_8
year: 1987
number: "8"
title: 柯西-布尼亚科夫斯基不等式
authors:
  - Конюшков А. А.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
tag: 9S4C
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 898b46192fe586e7eda7a8483b28712dffefa0415d532b4dfdfd0d7c4d6e6a83
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/12_konyushkov-neravenstvo-koshi-bunyakovskogo-c4a495a8.md
source_content_sha256: da1ea376f5fccc06ff2e420b1232a1bb3228632e2c31c8d2ba1c18c647c72829
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

我们的空间图没有明确证明这一点。

问题 3. 将与给定平行四边形相似的平行四边形内接到另一个给定平行四边形中，使得所描述的平行四边形的每一侧都有一个内接平行四边形的顶点。

设 ABCD 为给定的外接平行四边形，KLMN 为所需的内接平行四边形 (图 4)。它们的中心必须重合，因为相对于平行四边形 KLMN 的中心对称，平行四边形 ABCD 必须变换为自身。因此，我们已知所需平行四边形的中心 O； $\angle KOL = \alpha$ 和关系 $LO:KO = k$ 也是已知的，因为给出了平行四边形形状 KLMN。这意味着我们可以将直线AB和BC作为$M_1$和$M_2$，将现成的旋转$H_0^\circ R_0^\alpha$作为F，将所需的点K和L（$L = F(K)$）作为X和Y来应用我们的方案。无需进一步解释。我们只是注意到，在这个问题上进行完整的研究是很有趣的。

问题 4. 如果已知三角形 ABC 的比色线 AD 的长度以及边长 AB 和 AC，则构造三角形 ABC。

让我们构造一条线段AD，并以A (图 5) 为圆心，以AB 和AC 为半径绘制圆β 和γ。这将是集合 M1 和 M2，点 B 和 C 是我们图中的点 X 和 Y。变换F会是什么？根据bissergris定理（例如，参见«Kvant» 1985年第2期，第29页），边CB除以bissergris底边的比率$k = CD:DB$等于三角形各边的比率AC:AB，因此我们知道。而从$C = H_D^{-k}(B)$开始，我们可以将现成的$H_D^{-k}$作为F，即C是圆γ与$H_D^{-k}(\beta)$的交点。

需要独立解决的问题

1. 使用比塞尔格里斯和比塞尔格里斯的底将三角形边划分成的线段构造一个三角形。
2. 构造一个具有给定圆心的圆，使得连接其交点与给定角度的边的线段之一平行于给定的直线。
3. 在已知的两个奶牛时刻，测量了地图上标记的两个灯塔方向之间的角度。奶牛运动的方向和速度也是已知的。如何在这些时刻找到牛在地图上的位置？
4. 使用介质 AA1 和 BB1 以及角 C 构造三角形 ABC。
5（对于熟悉反演的读者）。在给定的平行四边形中内接给定面积的菱形，使得菱形的一个顶点位于平行四边形的每一侧。

V·N·杜布罗夫斯基

柯西-布尼亚科夫斯基不等式

柯西-布尼亚科夫斯基不等式可以被认为是数学中最流行的不等式之一。它不止一次出现在我们杂志的页面上（例如，参见«Kvant»，1986年，第12期，第31页）。柯西-布尼亚科夫斯基不等式如下所示：

$$\begin{align*}
|a_1b_1 + a_2b_2 + \dots + a_nb_n| &\leq \\
\leq \sqrt{a_1^2 + a_2^2 + \dots + a_n^2} \cdot \sqrt{b_1^2 + b_2^2 + \dots + b_n^2}.
\end{align*}$$

然而，几乎没有证据证明这一点。这里我们给出柯西-布尼亚科夫斯基不等式的一个非常简单的证明，讨论它的几何意义，并在它的帮助下再次解决 1984 年提出的一个问题

⟦folio 43⟧

«Kvant»（参见第 5 期，第 37 页，选定的学校问题，任务 15）。在此过程中，我们将讨论不平等的“准确性”问题。

因此，如果至少一个根号（例如 $\sqrt{a_1^2+a_2^2+\dots+a_n^2}$）等于 0，则 (1) 左侧的 $a_1=a_2=\dots=a_n=0$ 也等于 0，并且不等式成立。设两个根为正且为空

$$A = \sqrt{a_1^2+a_2^2+\dots+a_n^2},$$
$$B = \sqrt{b_1^2+b_2^2+\dots+b_n^2}.$$

让我们将不等式（1）重写为以下形式

$$\frac{|a_1b_1+a_2b_2+\dots+a_nb_n|}{AB} \leq 1.$$

利用$|x+y| \leq \leq |x|+|y|$和$|xy| \leq \frac{1}{2}(x^2+y^2)$的事实，我们写出整数不等式：

$$\frac{|a_1b_1+a_2b_2+\dots+a_nb_n|}{AB} \leq \frac{|a_1b_1|}{AB} +$$
$$+ \frac{|a_2b_2|}{AB} +\dots+\frac{|a_nb_n|}{AB} =$$
$$= \frac{|a_1|}{A} \cdot \frac{|b_1|}{B} +\frac{|a_2|}{A} \cdot \frac{|b_2|}{B} +\dots$$
$$\dots \frac{|a_n|}{A} \cdot \frac{|b_n|}{B} \leq \frac{1}{2}\left(\frac{a_1}{A}\right)^2+\left(\frac{b_1}{B}\right)^2)+$$
$$+ \frac{1}{2}\left(\left(\frac{a_2}{A}\right)^2+\left(\frac{b_2}{B}\right)^2\right)+\dots+\frac{1}{2}\left(\left(\frac{a_n}{A}\right)^2+\left(\frac{b_n}{B}\right)^2\right)+$$
$$+ \frac{1}{2}\left(\left(\frac{a_1}{B}\right)^2+\left(\frac{b_2}{B}\right)^2\right)=1$$

——不等式（1）已被证明。请注意，我们已经证明了更强的不等式：$|a_1b_1|+\dots+|a_nb_n| \leq AB$。当以下情况时，就实现了平等：

$$\frac{|a_1|}{A} = \frac{|b_1|}{B}, \frac{|a_2|}{A} = \frac{|b_2|}{B}, \dots, \frac{|a_n|}{A} = \frac{|b_n|}{B},$$

即，对于$\left|\frac{a_1}{b_1}\right| = \left|\frac{a_2}{b_2}\right| = \dots = \left|\frac{a_n}{b_n}\right|$（如果$a_i, b_i$不为零；如果有$b_i=0$，则对应的$a_i=0$）。在 (1) 中，当乘积 $a_1b_1$, ..., $a_nb_n$ 具有相同符号时，即达到相等，即当

$$\frac{a_1}{b_1} = \frac{a_2}{b_2} = \dots = \frac{a_n}{b_n}.$$

对于 $n=3$，柯西-布尼亚科夫斯基不等式的形式为

$$|a_1b_1+a_2b_2+a_3b_3| \leq$$
$$\leq \sqrt{a_1^2+a_2^2+a_3^2} \cdot \sqrt{b_1^2+b_2^2+b_3^2},$$

(1') 其几何意义不难理解。考虑两个向量$\vec{a}(a_1, a_2, a_3)$和$\vec{b}(b_1, b_2, b_3)$。然后在(1')的左边写上绝对值

向量 $\vec{a}$ 和 $\vec{b}$ 的标量积的秩，右侧是它们的长度 $\|\vec{a}\|=\sqrt{a_1^2+a_2^2+a_3^2}, \|\vec{b}\|=\sqrt{b_1^2+b_2^2+b_3^2}$ 的积。但是向量的标量积等于向量的长度和它们之间的角度的余弦的乘积；从 $\|\cos(\vec{a}, \vec{b})\| \leq 1$ 开始，我们得到不等式 (1')。

在任意 $n$ 的情况下，柯西-布尼亚科夫斯基不等式在维度 $n$ 的空间中具有相同的几何意义，其中向量、向量的长度和向量的标量积的定义与在三维空间中的定义类似：

$$\vec{a} = (a_1, a_2, \dots, a_n),$$
$$\vec{a}\vec{b} = a_1b_1+a_2b_2+\dots+a_nb_n,$$
$$|\vec{a}|=\sqrt{a_1^2+a_2^2+a_3^2};$$
$$a\cos(\vec{a}, \vec{b})=\frac{\vec{a}\vec{b}}{|\vec{a}| \cdot |\vec{b}|}.$$

现在我们以«Kvant»，1984年第5期来看《学校问题选》中的第15题：

a) 设 $a+b+c=1$。证明$a^2+b^2+c^2 \geq 1/3$。

b) 还已知$a+b+c=1$和$k$，$a, b, c$是某个三角形的边长。证明$a^2+b^2+c^2 < 1/2$。

解 a) 通过 Cauchy-Bunyakovsky 不等式

$$1=a \cdot 1+b \cdot 1+c \cdot 1 \leq \sqrt{a^2+b^2+c^2} \times \sqrt{1^2 \cdot 1^2 \cdot 1^2}=\sqrt{3} \cdot \sqrt{a^2+b^2+c^2}.$$

因此$a^2+b^2+c^2 \geq 1/3$。

如果$a=b=c=1/3$，则$a+b+c=1$和$a^2+b^2+c^2=1/3$。这意味着我们的不平等是精确的。

不等式的准确性问题非常重要。因此，我们给该阵型下一个定义。

让不平等

$$f(x_1, x_2, \dots, x_n) \geq c$$

满足$x_1, x_2, \dots, x_n$的所有有效值。如果右侧的常数 $c$ 不能增加，则称其为精确常数，即不存在 $k>c$ 使得不等式对于 $x_1, x_2, \dots, x_n$ 的所有允许值都成立。

$$f(x_1, \dots, x_n) \geq k.$$

我们在不等式的右侧投影一个类似的$c$

$$b(x_1, x_2, \dots, x_n) \leq c,$$

对所有允许的$x_1, x_2, \dots, x_n$都有效，如果不能增加则称是精确的。

让我们回到我们的任务。让我们用稍微更一般的公式来证明 6)：令 $a, b, c$ ($a \neq 0, b \neq 0, c \neq 0$) 为向量 $\vec{a}, \vec{b}, \vec{c}$ 的长度，使得 $\vec{a}+\vec{b}+\vec{c}=\vec{0}$ 和 $a+b+c=1$。然后$a^2+b^2+c^2 < 1/2$。
