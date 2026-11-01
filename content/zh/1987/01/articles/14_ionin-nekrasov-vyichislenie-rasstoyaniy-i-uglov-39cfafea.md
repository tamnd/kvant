---
id: 1987-1-ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea
issue: kvant_1987_1
year: 1987
number: "1"
title: 计算距离和角度
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: ROC0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7d74f6129138b8e0cb75c9d640ed49ce7d469819539b86187941fbaf5aa9260b
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/14_ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea.md
source_content_sha256: bd92730ddf940480deef215de2d84af829a826b5218ca8ee01440a0a1de60d71
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

提升距离和角度

教育科学候选人
于。 I. 爱奥宁，
V·V·涅克拉索夫

本文讨论了几个几何问题，为了解决这些问题，需要计算空间中的某些距离或角度（这些问题在大学发展的入学考试中提出）。使用向量的标量积可以方便地解决此类问题。主要的解决方法是在空间中选择一个合适的基并编制一个乘法表——该基的向量的标量乘积表。有了这样一个表并知道向量在所选基础上的分解，就可以很容易地计算这些向量的长度以及它们之间的角度。我们将从一个简单的问题开始，该方法自行指导，然后转向更复杂的问题，演示所有基本情况。

任务 1（MAI，1981）。在三角形paramid ABCD 中，所有边都具有相同的长度。 M点是边AD的中点，O点是三角形ABC的中心，点N是边AB的中点，点K是边CD的中点。求直线 MO 和 KN 之间的角度。

解决方案e.让我们将四面体的边长设为 1，并选择向量 $\overrightarrow{DA} = \vec{a}, \overrightarrow{DB} = \vec{b}, \overrightarrow{DC} = \vec{c}$ 作为基础。让我们为此基础创建一个乘法表（表 1，第 48 页）。让我们将向量 $\overrightarrow{MO}$ 和 $\overrightarrow{KN}$ 展开为向量 $\vec{a}, \vec{b}, \vec{c}$：

$$\overrightarrow{MO} = \overrightarrow{DO} - \overrightarrow{DM} = \frac{1}{3} (\vec{a} + \vec{b} + \vec{c}) - \frac{1}{2} \vec{a} = \frac{1}{6} (-\vec{a} + 2\vec{b} + 2\vec{c}),$$

$$\overrightarrow{KN} = \overrightarrow{DN} - \overrightarrow{DK} = \frac{1}{2} (\vec{a} + \vec{b}) - \frac{1}{2} \vec{c} = \frac{1}{2} (\vec{a} + \vec{b} - \vec{c}).$$

直线MO与KN之间的夹角$\varphi$由以下公式计算

$$\cos \varphi = \frac{|\overrightarrow{MO} \cdot \overrightarrow{KN}|}{|\overrightarrow{MO}| \cdot |\overrightarrow{KN}|}.$$

我们求$\overrightarrow{MO} \cdot \overrightarrow{KN}$、$|\overrightarrow{MO}|$和$|\overrightarrow{KN}|$，得到表1：

⟦folio 48⟧

$$\overrightarrow{MO} \cdot \overrightarrow{KN} = \frac{1}{12} (-\vec{a} + 2\vec{b} + 2\vec{c}) (\vec{a} + \vec{b} - \vec{c}) = \frac{1}{12};$$
$$|\overrightarrow{MO}| = \frac{1}{6} \sqrt{(-\vec{a} + 2\vec{b} + 2\vec{c})^2} = \frac{1}{2};$$
$$|\overrightarrow{KN}| = \frac{1}{2} \sqrt{(\vec{a} + \vec{b} - \vec{c})^2} = \frac{\sqrt{2}}{2}.$$
因此$\cos \varphi = \frac{\sqrt{2}}{6}$，$\varphi = \arccos \frac{\sqrt{2}}{6}$。

然而，问题的条件并不总是允许选择具有完全定义的乘法表的基础。在这种情况下，您需要尝试为不足的元素创建一个方程。

问题 2（MIPT，1974）。直角三棱柱$ABCA_1B_1C_1$的底边等于$a$，$O$和$O_1$分别是底$ABC$和$A_1B_1C_1$的中心。线段$AO_1$到直线$B_1O$的正交投影的长度等于$\frac{5a}{6}$。确定棱镜的高度。

解决了并且e。让我们选择向量 $\overrightarrow{AA_1} = \vec{m}, \overrightarrow{AB} = \vec{n}, \overrightarrow{AC} = \vec{p}$ (图 1) 作为基础。让$h = |\vec{m}|$。表2是基$(\vec{m}, \vec{n}, \vec{p})$的乘法表。

线段 $AO_1$ 到直线 $B_1O$ 的正交投影等于该线段的长度乘以角度的余弦

图 1.

f 位于行 $AO_1$ 和 $B_1O$ 之间。为了计算 $|\overrightarrow{AO_1}|$ 和 cos $\varphi$，我们将向量 $\overrightarrow{AO_1}$ 和 $\overrightarrow{B_1O}$ 展开为基$(\vec{m}, \vec{n}, \vec{p})$：

$$\overrightarrow{AO_1} = \frac{1}{3} (\overrightarrow{AA_1} + \overrightarrow{AB_1} + \overrightarrow{AC_1}) =$$
$$= \frac{1}{3} (\vec{m} + \vec{m} + \vec{n} + \vec{p}) =$$
$$= \frac{1}{3} (3\vec{m} + \vec{n} + \vec{p});$$
$$\overrightarrow{B_1O} = \overrightarrow{AO} - \overrightarrow{AB_1} = \frac{1}{3} (\vec{n} + \vec{p}) - (\vec{m} + \vec{n}) =$$
$$= \frac{1}{3} (-3\vec{m} - 2\vec{n} + \vec{p}).$$

使用表2，我们发现：

$$|\overrightarrow{AO_1}| = |\overrightarrow{B_1O}| = \frac{1}{3} \sqrt{9h^2 + 3a^2},$$
$$\overrightarrow{AO_1} \cdot \overrightarrow{B_1O} = -\frac{1}{6} (6h^2 + a^2),$$
$$\cos \varphi = \frac{6h^2 + a^2}{2(3h^2 + a^2)}.$$

从 $|\overrightarrow{AO_1}| \cdot \cos \varphi = \frac{5a}{6}$ 开始，我们得到方程
$$\frac{\sqrt{9h^2 + 3a^2}(6h^2 + a^2)}{6(3h^2 + a^2)} = \frac{5a}{6}.$$
因此$h = \frac{a \sqrt{6}}{3}$。

计算距离和角度的问题主要有四种类型：

1. 点到直线的距离

给定：点$M$；线$l$，方向向量$\vec{a}$，点$A$属于线$l$； $\overrightarrow{AM} = \vec{m}$。

求：点$M$到直线$l$的距离。

（向量$\vec{a}$和$\vec{m}$在给定乘法表的一定基础上展开的条件下。）

让我们展示一个解决这个问题的图表。

设 $N$ 为点 $M$ 到直线 $l$ (图 2) 的正交投影。然后$\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM} = x\vec{a} - \vec{m}$。内兹维斯特-

⟦folio 50⟧

$\vec{A} = 60^\circ$。棱柱的所有边的长度均为 $a$。点$K$是点$B_1$在平面$DA_1C_1$上的正交投影，点$L$是点$K$在平面$DD_1C_1C$上的正交投影。求金字塔的体积$DCLK$。

解决方案。将原$DCLK$的底边视为三角形$CDL$，位于平面$DD_1C_1C$内。那么线段 $KL$ 就是 prim 的高度 (图 5)。因此，$V_{KCDL} = \frac{1}{3} S_{CDL} \cdot KL = \frac{1}{6} DC \cdot LM \cdot KL$，其中$M$是点$L$到直线$DC$的正交投影。

让我们选择向量 $\vec{C}_1\vec{B}_1 = \vec{m}, \vec{C}_1\vec{D}_1 = \vec{n}, \vec{C}_1\vec{C} = \vec{p}$ 作为基并填写表 4 - 该基的乘法表。

下一个，
$$\vec{B}_1\vec{K} = \vec{C}_1\vec{K} - \vec{C}_1\vec{B}_1 = x\vec{C}_1\vec{A}_1 + y\vec{C}_1\vec{D} - \vec{C}_1\vec{B}_1 = x(\vec{m} + \vec{n}) + y(\vec{n} + \vec{p}) - \vec{m} = (x - 1)\vec{m} + (x + y)\vec{n} + y\vec{p}.$$

由于向量$\vec{B}_1\vec{K}$垂直于向量$\vec{C}_1\vec{A}_1$和$\vec{C}_1\vec{D}$，我们得到系统
$$\vec{B}_1\vec{K} \cdot (\vec{m} + \vec{n}) = 0, \quad \vec{B}_1\vec{K} \cdot (\vec{n} + \vec{p}) = 0.$$

将向量$\vec{B}_1\vec{K}$替换为分解为基$(\vec{m}, \vec{n}, \vec{p})$，并使用表4，将过程简化为控制系统$2x + y = 1$、$3x + 4y = 1$，我们打开$\vec{KL} = \frac{3}{5}(\vec{m} + \vec{n}) - \frac{1}{5}(\vec{n} + \vec{p}) = \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p})$。与$\vec{KL} = \vec{C}_1\vec{L} - \vec{C}_1\vec{K} = z\vec{C}_1\vec{D}_1 + t\vec{C}_1\vec{C} - \vec{C}_1\vec{K} = z\vec{n} + t\vec{p} - \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p}) = \frac{1}{5}(-3\vec{m} + (5z - 2)\vec{n} + (5t + 1)\vec{p})$相同。从$\vec{KL} \cdot \vec{n} = 0$开始，然后$-\frac{3}{2} + 5z - 2 = 0$，打开$z = \frac{7}{10}$，$5t + 1 = 0$，打开$t = -\frac{1}{5}$。因此，
$$\vec{KL} = \frac{1}{5}(-3\vec{m} + \frac{3}{2}\vec{n}) = \frac{3}{10}(-2\vec{m} + \vec{n}).$$

现在您可以找到 prima $KCDL$ 的高度：
$$KL = \frac{3}{10}\sqrt{(-2\vec{m} + \vec{n})^2} = \frac{3a\sqrt{3}}{10}.$$

剩下的就是找到 $\vec{LM}$：
$$\vec{LM} = \vec{CM} - \vec{CL} = u\vec{CD} - (\vec{C}_1\vec{L} - \vec{C}_1\vec{C}) = u\vec{n} - z\vec{n} - t\vec{p} + \vec{p} = (u - \frac{7}{10})\vec{n} + \frac{6}{5}\vec{p}.$$

从$\vec{LM} \cdot \vec{n} = 0$开始，然后$u = \frac{7}{10}$，打开$\vec{LM} = \frac{6}{5}\vec{p}$，$|\vec{LM}| = \frac{6a}{5}$。因此，
$$V_{KCDL} = \frac{1}{6} \cdot a \cdot \frac{6a}{5} \cdot \frac{3a\sqrt{3}}{10} = \frac{3a^3\sqrt{3}}{50}.$$

3. 相交线之间的距离和角度

给定：线$l_1$，方向向量$\vec{a}_1$，点$A_1$属于线$l_1$；线$l_2$，方向向量$\vec{a}_2$，点$A_2$属于线$l_2$； $\vec{A}_1\vec{A}_2 = \vec{m}$。

求：线 $l_1$ 和 $l_2$ 之间的距离 $u$ 角度。

⟦folio 51⟧

根据以下方案指定此类解决方案。

$l_1$ 和 $l_2$ 之间的夹角 φ 的余弦可通过以下公式求出

$$\cos \varphi = \frac{|\vec{a}_1 \cdot \vec{a}_2|}{|\vec{a}_1| \cdot |\vec{a}_2|}.$$

为了确定直线$l_1$和$l_2$之间的距离，即它们共同重分布$P_1P_2$（$P_1 \in l_1$，$P_2 \in l_2$，图6）的长度，我们将向量$\vec{P}_1\vec{P}_2$表示为$\vec{P}_1\vec{P}_2 = \vec{P}_1\vec{A}_1 + \vec{A}_1\vec{A}_2 + \vec{A}_2\vec{P}_2 = x\vec{a}_1 + \vec{m} + y\vec{a}_2$。将向量$\vec{P}_1\vec{P}_2$重新分配给向量$\vec{a}_1$和$\vec{a}_2$，求得未加权系数$x, y$：

$$\begin{cases}
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_1 = 0, \\
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_2 = 0.
\end{cases}$$

所需距离为向量$\vec{P}_1\vec{P}_2$的长度，即$\sqrt{(x\vec{a}_1 + y\vec{a}_2 + \vec{m})^2}$。

任务 5（密歇根州立大学，Mek.-Mat.，1977 年）。参数SABC的底是一个边长为$4\sqrt{2}$的等边三角形ABC。侧边 SC 重新分布到基面，长度为 2。求交叉线之间的角度和距离，其中一条穿过点 S 和边 BC 的中点，另一条穿过点 C 和边 AB 的中点。

解决方案。令 $M$ 和 $N$ 为边 BC 和 AB 的中点 (图 7)。让我们选择向量 $\vec{CA} = \vec{a}$、$\vec{CB} = \vec{b}$、$\vec{CS} = \vec{c}$ 作为基础。该基础的乘法表为表 5。我们来求直线 SM 和 CN 之间的角度 φ：

$$\vec{SM} = \vec{CM} - \vec{CS} = \frac{1}{2} \vec{b} - \vec{c} = \frac{1}{2} (\vec{b} - 2\vec{c}); \quad \vec{CN} = \frac{1}{2} (\vec{a} + \vec{b}).$$

我们来计算$\vec{SM} \cdot \vec{CN}$、$|\vec{SM}|$、$|\vec{CN}|$：

$$\vec{SM} \cdot \vec{CN} = 12, \quad |\vec{SM}| = 2\sqrt{3}, \quad |\vec{CN}| = 2\sqrt{6}.$$

因此，$\cos \varphi = \frac{12}{2\sqrt{3} \cdot 2\sqrt{6}} = \frac{\sqrt{2}}{2}, \quad \varphi = 45^\circ$。

现在我们来计算直线 SM 和 CN 之间的距离，即它们共同重分布 PQ ($P \in SM, Q \in CN$) 的长度：

$$\vec{PQ} = x\vec{SM} + y\vec{CN} + \vec{SC} = \frac{x}{2} (\vec{b} - 2\vec{c}) + \frac{y}{2} (\vec{a} + \vec{b}) - \vec{c} = \frac{1}{2} (y\vec{a} + (x + y)\vec{b} - (2x + 2)\vec{c}).$$

根据向量$\vec{b} - 2\vec{c}$和$\vec{a} + \vec{b}$的向量$\vec{PQ}$的重分布条件，我们得到一个方程组

$$3x + 3y = -1, \quad x + 2y = 0,$$

从哪里$x = -\frac{2}{3}, \quad y = \frac{1}{3}$。

因此，$\vec{PQ} = \frac{1}{6} (\vec{a} - \vec{b} - 2\vec{c}), \quad PQ = \frac{1}{6} \sqrt{(\vec{a} - \vec{b} - 2\vec{c})^2} = \frac{2\sqrt{3}}{3}$。

4. 平面之间的角度

两个平面之间的角度等于它们的直线之间的角度。事实上，空平面 $a$ 和 $b$ 沿着直线 $c$ (图 8) 相交。通过某条线$c$，我们绘制线$a$和$b$，沿着线$a_1$和$b_1$与平面$a$和$b$相交，并由线$c$重新分布（参见图8）。平面 $a$ 和 $b$ 之间的角度等于直线 $a_1$ 和 $b_1$ 之间的角度，而后者又等于直线 $a$ 和 $b$ 之间的角度（因为直线 $a, b, a_1, b_1$ 与 $a \perp a_1, b \perp b_1$ 位于同一平面内）。
