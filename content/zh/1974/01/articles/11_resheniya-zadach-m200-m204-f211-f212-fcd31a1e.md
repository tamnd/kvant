---
id: 1974-1-resheniya-zadach-m200-m204-f211-f212-fcd31a1e
issue: kvant_1974_1
year: 1974
number: "1"
title: 问题解决方案M200—M204； F211、F212
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 49
page_labels: 44-47
tag: 97KB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c7df6a036c771c278aea5bc902e445538cf9fb748335abe943a0bd16a4883ad7
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/11_resheniya-zadach-m200-m204-f211-f212-fcd31a1e.md
source_content_sha256: be87316085b7355e243744616885a2c5efc152bde7055219a60f4cef2e9e8af2
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

问题解决方案

M200—M204; F211, F212

M200。 a) 在 图 1 上有六个裂片，三个裂片位于四个直线上。证明有 24 种方法将这组六个波瓣映射到自身上，以便位于同一直线上的每三个波瓣映射到也位于同一直线上的三个波瓣。

b) 在 图 2. 九个瓣上，三个位于九条直线上，并且通过每个摩卡，有三个具有“帕斯卡配置”的最大值。我们的九个瓣的集合可以通过多少种方式映射到自身上，以便位于九个瓣中的一个上的每个三瓣瓣被映射到位于我们的配置的某条直线上的三瓣瓣上？

b) 对于 图 3 中所示的 Desarada 配置（十个波瓣和十个直管）有同样的问题。

a) 一切都可用 6！ = 720 种方法将一组六个点映射到自身上。但并非所有这些映射都满足问题的条件。找到我们配置的直接映射会更方便。如果对于我们的四条直线中的每一条都指示了它映射到哪条直线，则将由此确定每个点的图像（我们的配置的哪个点是配置中包括的某些两条直线的交点）。一组四条直线可以映射到自身上 4！ = 24 种方式。

b) 注意其中一种辣味配置 l。让我们表示位于其上的三个配置点 A、B 和 C。还有 6 条配置线穿过这些点。其余的 9 - 1 - 6 = 2 是不经过任何点 A、B 和 C 的直线。让我们将它们表示为 p 和 q (图 4)。

将直线 l 映射到九个直线配置中的任何一个上 - 映射到直线 l1 上。这可以通过九种不同的方式来完成。点 A、B 和 C 将被映射到位于线 l1 上的点 A1、B1、C1。这个可以做到3！ =

⟦folio 45⟧

$Y_1$点$X$和$Y$，它们必须是不同于$l_1$穿过点$A_1$和$B_1$的配置线的成对交点（证明它！）。总共有 $10 \cdot 6 \cdot 2 = 120$ 映射与我们相交。

笔记。请注意，“证明”这个词的背后仍然隐藏着相当大的一部分解决方案。在以后的问题中，我们将讨论解决���题 M200的其他方法。

A·N·科尔莫多罗夫

**M201。直线 $l_1$ 与边 $a$、$b$ 相交，并且从三角形或其延续点到对应直接相交的点 $A_1$、$B_1$ 和 $C_1$ 仍然是解的很大一部分。在以后的期刊中，我们将讨论解决���题 M200的其他方法。

我们将使用向量来解决这个问题。这种方式（以及坐标法的解决方案）的好处在于，它允许您用一个推理涵盖所有情况，而不必担心线 $l_1$ 和 $l_2$ 相对于给定三角形的位置。

⟦folio 46⟧

图 7.

我的是$AB$（图7）。我们必须找到一个条件，使$B'_1$与$C_1$重合，即$\overrightarrow{AB'_1} = \overrightarrow{AC'_1}$，或者等价地，

$$\frac{\overrightarrow{AB'_1}}{\overrightarrow{C'_1B'_1}} = \frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}}$$

（关系$\frac{\overrightarrow{AM}}{\overrightarrow{C'_1M}} = k$由点$M \in (AB)$的位置唯一确定，因为从$\frac{\overrightarrow{AM}}{\overrightarrow{C'_1A} + \overrightarrow{AM}} = k$可以得出$\overrightarrow{AM} = \frac{k}{1-k} \cdot \overrightarrow{C'_1A}$）。

等式（3）等价于：

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{BC'_1}} \cdot \frac{\overrightarrow{BC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

这相当于(1)。

**M202.** 证明，当关系$a/d$是有理数时，可以从无限等差数列($d \neq 0$)的序列$a, a+d, a+2d, \dots, a+nd, \dots$中选择一个无限等比级数的序列。

让$a/d$是有理数：非常印度，我们可以假设$a$和$d$具有相同的符号。然后

$$\frac{a}{d} = \frac{s}{r},$$

其中$s$和$r$是自然数。那么对于任何非负整数 $m$ ，数字 $(1+r)^m-1$ 都可以被 $(1+r)-1=r$整除，所以这个数字

$$n_m = \frac{a(1+r)^m-a}{d} =$$

$$= s \frac{a(1+r)^m-a}{sd} = s \frac{(1+r)^m-1}{r}$$

——整数且非负；因此，几何级数$a(1+r)^m$、$(m=0,1,2,\dots)$的每一项都具有以下形式

$$a(1+r)^m = a + n_m d,$$

也就是说，它属于算术级数。

示例 算术级数 $\frac{1}{5} + \frac{3}{7}n(n=0,1,2,\dots)$，其中 $\frac{a}{d} = \frac{1.7}{5.3} = \frac{7}{15}$，包含子序列 $\frac{1}{5} \cdot (15+1)^m = \frac{16}{5}m$（$m$ 是任何非负整数）。

反之，令算术级数$a+nd$($d \neq 0$)包含至少三个连续的等比级数项。就当是她的成员吧

$$a+kd, a+ld, a+md \ (k < l < m).$$

那么$(a+ld)^2 = (a+kd)(a+md)$，从哪里

$$a(2l-k-m) = d(km-l^2).$$

这里$2l-k-m \neq 0$。事实上，如果$2l-k-m = 0$，则$km-l^2 = 0$。但是$(k-m)^2 = (k+m)^2 - 4km = 4l^2 - 4l^2 = 0$，因此$k = m$，这与假设$k < l < m$相矛盾。

因此关系$\frac{a}{d} = \frac{km-l^2}{2l-k-m}$是有理数。

**M203.** a) 证明如果满足对角线$AC$和$BD$交点的投影，则ABCD在直线上的交点

⟦folio 47⟧

图 9.

将AB、BC、CD、DA与四条直线（图8）串联起来，则这几条直线都相交于同一个圆。

6) 形成并证明逆定理。

解题a)，得四边形KLMN（OK、OL、OM、ON为对角线AC、BD交点O到边AB、BC、CD、DA的垂线）内接的中心圆为O点。

为了证明这一点，只要证明四边形KLMN的四个角的光谱都经过O就足够了。让我们针对K点来证明这一点（由于所有四个顶点都包含在完全对称的条件下，所以这已经被证明了）。

由于四边形 AKON 和 BLOK 内接于圆（直径 AO 和 BO 对应）且 ABCD 也内接（根据条件），则
$$NKO = NAO = DAC = DBC = OBL = OKL.$$
至此，我们证明了OK是角K的右余角。

当投影落在边的延长线上，但圆可以接触四边形 KLMN 的延长边时，以类似的方式证明问题的陈述。

至于问题b)，其解决方案是不明确的。这就是这一切的意义所在。

我们认为定理“如果 Q，则 P”是定理“如果 P，则 Q”的逆命题（这里 P 和 Q 在某种程度上是一个陈述）。但大多数有意义的定理都有更复杂的结构，包括“条件”和“结论”中的许多单独要求；例如，“如果 P1、P2 和 P3，则 Q1 和 Q2。”在这种情况下，它们通常不仅会反转定理 - 例如，“如果 Q₁ 和 Q2，则 P₁，P2 和 P₃”，而且还会组合其他组件：

“如果 P1、P2、Q1 和 Q2，则 P3”，

如果凸四边形 ABCD 的对角线交点到连接其投影到四边形相邻边的四条直线的距离相等，则四边形 ABCD 是循环四边形。

2. 如果通过以 O 为圆心的外接四边形的顶点 K、L、M、N，分别作相应线段 OK、OL、OM、ON 的垂线，则四边形 KLMN 为以 O 为圆心的外接四边形，则可内接于该圆，且圆心与 P 重合。

3. 设K、L、M和N为凸四边形ABCD的对角线AC和BD的交点P在其边AB、BC、CD、DA上的投影。如果四边形 KLMN 外接于一个以 O 为圆心的圆，则 ABCD 可以内接于该圆，且圆心与 P 重合。

有些读者提出了一个更强的定理——2或3，并证明了一个更弱的定理——1（也就是说，他们默默地假设中心O和对角线AC和BD的交点必须重合）。我们将证明2和3。

2. 让我们用 A、B、C、D 表示比塞三边 OK、OL、OM、ON (图 9) 的相邻垂线的交点，并将这些点与 O 连接。利用四边形 AKON、BLOK、CMOL、DNOM 内接的事实，很容易证明具有相同字母 α、β、γ、δ 的每个四边形相等。这样就可以清楚地看到 α + β + γ + δ = BAD + BCD = ABC + ADC。

ABCD 姿势 - 铭文。下一个，
$$AOC = \left(\frac{\pi}{2} - \beta\right) + \left(\frac{\pi}{2} - \delta\right) + \left(\frac{\pi}{2} - \alpha\right) + \left(\frac{\pi}{2} - \gamma\right) = \pi,$$
构成直线 A + C > D + B。然后我们证明 KLMN 是不可描述的，即 Bissertis 角 K、L、M、N 不相交于一点。即，我们将证明角 K 和 N 的二等分在 AKPN 内相交（同样，角 L 和 M 的二等分在 CMPL 内相交）。
