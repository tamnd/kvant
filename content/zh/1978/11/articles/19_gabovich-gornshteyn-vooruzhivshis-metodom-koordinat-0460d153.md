---
id: 1978-11-gabovich-gornshteyn-vooruzhivshis-metodom-koordinat-0460d153
issue: kvant_1978_11
year: 1978
number: "11"
title: 用坐标方法武装
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 47
page_labels: 42, 43, 45
tag: G3NY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ed6f00f2cbefb93d3e100d545184b8e8b4ba812d2506bac6ae6cd3aea7a4cea8
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/19_gabovich-gornshteyn-vooruzhivshis-metodom-koordinat-0460d153.md
source_content_sha256: 4cc1b8f9fef2b4054eab1b1d19160f474a049384429dd58e70d81c560c0c8985
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

使用坐标法的问题

坐标法在解决«Kvant»几何问题中的应用已经写过*。现在已经触及这个重要主题的新方面。

问题 1（MIEM，1977）。使用新的坐标平面方法，我们转到以点 M 为中心的节点 α，点 A (1; 2) 到 A₁ (6; 5)，点 B (1; 4) 到 B₁ (4; 5)。求C点(1;3)的图像。找到另一个点的图像（由您自行决定）。求el α的值和M点的坐标。

解决方案。让我们在坐标平面上标记点A； A₁、B、B₁ 和 C (图 1)。为了确定 M 点的坐标 (x; y)，我们利用旋转是位移的事实，因此 |MA|²=|MA₁|² 和 |MB|²=|MB₁|²，即

$$\int (x-1)^2 + (y-2)^2 = (x-6)^2 + (y-5)^2$$
$$\int (x-1)^2 + (y-4)^2 = (x-4)^2 + (y-5)^2.$$

求解该方程组，我们发现 x=2 且 y=6。

让$R_M^\alpha(C) = C_1$。让我们确定点 C₁ 的坐标 $(x_1; y_1)$。很容易看出，C 点是 [AB] 的中点，因此它的图像 - 点 C₁ - 是 [A₁B₁] 的中点。考虑到这一点，我们发现点 C₁ 的坐标为 (5; 5)。

现在让我们确定角度α的大小。注意到A点和B点的横坐标

*) 1977 年第 11 号

图 1.

⟦folio 43⟧

现在我们需要找出得到的解中哪一个是点$D_1$的坐标。看图，读者立即会发现第一个解决方案是正确的，第二个解决方案是构造的。然而，考试需要严格的理由来选择正确的解决方案。在给出这个理由之前，让我们澄清所获得的解的几何意义，并解释为什么有两个解。

方程组(1)的第一个方程是以$M$为圆心，半径为$|MD|$(图2)的圆方程。系统(1)的第二个方程是以$A_1$为圆心、半径为$|AD|$的圆方程。第二个方程与第一个方程在两个点 $-D_1'(7; 7)$ 和 $D_1''(\frac{101}{17}; \frac{47}{17})$ 处相交，其中一个是点 $D$ 的图像。 （如果点$D$属于方向[MA]，那么第二个方程将接触第一个方程，我们将获得系统（1）的一个解，这将是所需的解。）

很明显，$\triangle DMD_1'$和$\triangle DMD_1''$是等边的，并且只有$\overrightarrow{DMD_1'}$、$\overrightarrow{DMD_1''}$之一等于$\alpha$（在我们的问题$\alpha = \frac{\pi}{2}$中）。我们来确定是哪一个。考虑$\triangle DMD_1'$。我们来求 $|DD_1'|$：

$$|DD_1'| = \sqrt{(7-3)^2 + (7-1)^2} = \sqrt{52}.$$
令 $F$ 为 $[DD_1']$ 的中间，然后 $|DF| = \frac{1}{2}\sqrt{52}.$ FROM $\triangle DMF$：

$$\sin \overrightarrow{DMF} = \frac{|DF|}{|DM|} = \frac{\sqrt{52}}{2\sqrt{26}} = \frac{\sqrt{2}}{2},$$

$$\overrightarrow{DMF} = \frac{\pi}{4} \Rightarrow \overrightarrow{DMD_1'} = \frac{\pi}{2}.$$

停电。当找到某个点$N(a; b)$的图像时得到的两个点中，很自然地选择坐标“更简单”的那个点进行验证（这样可以简化计算）。如果您发现选择用于验证的点给出了所需的解决方案，那么它就是点$N$的图像。如果没有，那么，该点的图像自然就是第二个点。

问题 2（MIPT，1977）。正方形$ABCD$位于坐标平面上。正方形的顶点 $A$ 和 $B$ 位于函数 $y=x^2$ 的图上，顶点 $C$ 和 $D$ 位于函数 $y=x-4$ 的图上。让我们确定正方形的范围。

解决方案。坐标平面 (图 3) 显示函数 $y=x^2$、$y=x-4$ 和正方形 $ABCD$ 的图形，其位置如条件所示。由于线$y=x-4$垂直于线$y=-x$，[AC] || （哦）和[BD] || (Oy) 设 $|AC|=l$ 和 $A(x_1; y_1)$，则：

![Рис. 2.](image1.png)
[Рис. 3.](image3.png)

⟦folio 45⟧

最后，从 (3) 中我们找到 $|AP| = \sqrt{\frac{17}{16} - \frac{9}{170}} = \frac{1}{4} \sqrt{\frac{1373}{85}}$。

扫地。没有必要提供该问题解决方案的“完成版本”的图纸。然而，绘制粗图还是很有用的。为了更清楚起见，我们在这里展示了由平面 $\alpha$ (图 4) 构建的立方体截面。我们找到属于$\alpha$的线$OB$与边$KK_1$相交的点$S$。 [SA] 是 $\alpha$ 与面 $KK_1L_1L$ 相交的线段。很明显，$\alpha$ 沿着平行于 [AS] 的线段 $BT$ 与面 $NN_1M_1M$ 相交。 $Q = (BT) \cap (MN)$；显然$Q \in \alpha$和$Q \in (KLM)$，$(AQ) = \alpha \cap (KLM)$；我们找到$U = (AQ) \cap (LM)$。现在构建一个部分不会造成任何困难。

任务 4（密歇根州立大学，机制，1977 年）。 SABC 参数的底是一个边长为 $4\sqrt{2}$ 的等边三角形 $ABC$。侧边SC垂直于底面平面，长度为2。名称为交叉直线之间，其中一条经过点$S$和边$BC$的中间，另一条经过点$C$和边$AB$的中间。

解决方案*）。 SABC (图5)

*) 见“Kvanita”，1978 年，第 2 期，第 14 页。 59-60 提出了该问题的两种解决方案：无限几何和矢量。

这是条件中给出的金字塔。点$E$和$F$分别是边$BC$和$AB$的中点。我们引入一个坐标系，如图*)所示，确定金字塔顶点和点$E$和$F$的坐标：$A (0; 4\sqrt{2}; 0)$； $B (2\sqrt{6}; 2\sqrt{2}; 0)$（点$B$的横坐标是根据$h = \frac{a\sqrt{3}}{2}$的对应关系找到等边三角形的高，其中$h$是高度，$a$是三角形的边）； $C (0; 0; 0)$； $S (0; 0; 2)$； $E (\sqrt{6}; \sqrt{2}; 0)$ 和 $F(\sqrt{6}; 3\sqrt{2}; 0)$。使用向量 $\vec{SE}$ 和 $\vec{CF}$ 的标量乘法求出交叉线之间的角度（参见“Kvanite”，1978 年，第 2 期，第 60 页）；它等于$\frac{\pi}{4}$。

要确定相交线之间的距离，请在 $(ABC)$ 处穿过点 $E$ 画一条平行于 $(CF)$ 的直线； $G$ 是这条线与边 $AB$ 的交点。显然坐标$G$将是$\left(\frac{3\sqrt{6}}{2}; \frac{5\sqrt{2}}{2}; 0\right)$（你自己检查一下）。

相交线 $SE$ 和 $EG$（或者，相同的是，三个点：$S, E, G$）定义了某个平面。

$ax + by + cz + d = 0$, (6) 平行于线$CF$（自$(EG) \parallel (CF)$）并包含$(SE)$。因此，任意点$(CF)$到$(SEG)$的距离等于交叉线$SE$和$CF$之间的距离。

现在让我们确定式（6）中系数$a, b, c$和$d$的值。

*) 这里绘图很简单，建议以解决方案的“干净版本”来呈现。
