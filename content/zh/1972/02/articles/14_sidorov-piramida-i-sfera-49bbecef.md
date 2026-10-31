---
id: 1972-2-sidorov-piramida-i-sfera-49bbecef
issue: kvant_1972_2
year: 1972
number: "2"
title: 金字塔和球体
authors:
  - Сидоров Ю. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 62
page_last: 66
page_labels: 60, 62, 64
tag: 8Z5A
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 436e0cd2a1ff0b3dda7c521b46d0a0b31399e3c22667fd7b29a6fbd62437789c
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/14_sidorov-piramida-i-sfera-49bbecef.md
source_content_sha256: 0136bd44f262071399e9496b1332bef40845da883cc10b1c7ad4146b1bfecd87
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

在学院的应用考试中，经常会出现这样的问题：必须确定一个球体（或多个球体）相对于参数的某个位置。解决此类问题主要基于以下三个事实：

1) 如果一个平面（或直线）与球体相切，则认为从球心到该平面（或直线）的距离等于球体的半径；
2) 如果球体接触两个相交平面，则球心位于经验平面形成的二维区域的平分平面内；
3) 如果参数是围绕球体描述的，那么

$$V = \frac{1}{3} rS,$$

(1)

food $r$ 是球体的半径，$V$ 和 $S$ 是体积和总表面积参数。

这些事实是学校数学课程中的每个学生都知道的。但在数学中，仅仅知道定理的表述是不够的——理解这些定理并能够应用它们来解决问题很重要。

一般来说，入学考试中提出的问题都很简单，大多数申请者很快就能找到解决办法。但通常所选择的方法非常复杂和繁琐，需要长时间的计算。因此，想要得到完整的最终结果是非常困难的。对于每个问题，你都需要尝试找到最短、最“优雅”的解决方案。

有时，在口试期间，申请人不会被要求解决问题，而只是指出解决问题的路径，从而检查申请人对这部分理论的了解程度。

在本文中，我们将研究使用多个几何消息有助于找到简单而美观的解决方案的问题。

任务 1（MIPT，1966）。在具有 aitripent 边缘的正多面体内部，有四个相等的球体，以便每个球体接触其他三个球体和多面体的三个面。这些球体的名称。

解决方案。令$ABCD$为给定的四面体，$O$为其中球体的中心，$r$为该球体的半径； $M, N, K, L$是球体的数据中心，它们的半径将用$x$表示。

四面体 $MNKL$ 是正确的，因为它的每条边都等于 $2x$。四面体 $MNKL$ 的面与四面体 $ABCD$ 的面平行（证明这一点！），并且点 $O$ 与四面体 $MNKL$ 的每个面相距距离 $r-x$。因此，点$O$是四面体内切球的中心

⟦folio 62⟧

图 3.

解决方案。令 $P$ 和 $P_1$ 为主要给定截断 Paramid 的中心，$DD_1$ 其边心 (图 3)。让我们用 $x$ 和 $y$ 表示主面。由梯形 $AA_1D_1D$ 得

$$DD_1^2 = b^2 - \frac{1}{4}(x - y)^2.$$

参数中描述的球体在点 $P$、$P_1$ 处接触主参数，并接触边心线 $DD_1$（证明这一点！）。因此，

$$DD_1 = PD + P_1D_1 = \frac{x + y}{2\sqrt{3}},$$

在哪里

$$b^2 - \frac{1}{4}(x - y)^2 = \frac{1}{12}(x + y)^2. \quad (2)$$

在接触 paramid 所有边缘的球体截面中，面 $BB_1C_1C$ 是由梯形 $BB_1C_1C$ 外接的圆。所以，$BC + B_1C_1 = BB_1 + CC_1$，

$$x + y = 2b. \quad (3)$$

求解方程组（2）和（3），我们发现

$$x = b\left(1 + \sqrt{\frac{2}{3}}\right),$$

$$y = b\left(1 - \sqrt{\frac{2}{3}}\right).$$

任务 5（MIPT，1968）。欣赏围绕正四边形 paramid 描述的球体，

62

图 4.

我们距侧面 $u$ 的距离为 $a$，距侧边的距离为 $b$。求球体的半径。

解决方案。令 $O$ 为 paramid $SABCD$ (图 4) 附近描述的球体中心，$OS = OA = R$ 该球体的半径，$SK$ paramid 的高度。我们来做$SL \perp BC$、$OM \perp SL$、$ON \perp AS$。根据问题$OM = a$、$ON = b$的条件（证明一下！）。

由于$\triangle SOM \sim \triangle SKL$和$\triangle SON \sim \triangle ASK$，那么

$$\frac{a}{\sqrt{R^2 - a^2}} = \frac{KL}{SK},$$

$$\frac{b}{\sqrt{R^2 - b^2}} = \frac{AK}{SK} = \frac{\sqrt{2}KL}{SK}.$$

从这里我们发现

$$\frac{b}{\sqrt{R^2 - b^2}} = \frac{a\sqrt{2}}{\sqrt{R^2 - a^2}},$$

$$R = \frac{ab}{\sqrt{2a^2 - b^2}}.$$

任务 6（MIPT，1971）。在正三角形 paramid $ABCD$ 中，底边 $ABC$ 的边为 $b$，paramid 的高度为 $b\sqrt{2}$。 paramida 中描述的球体在点 $K$ 处接触面 $ACD$。求通过点 $K$ 和边 $AB$ 的平面的 paramid 横截面积。

解决方案。令 $DO$ 为 paramid 的高度 (图 5)。点$K$位于

⟦folio 64⟧

茶$EL^2 = KL^2 + KE^2 = a^2 + \frac{1}{3} y^2 + z^2 - ay - az$。

现在从直角三角形$EFL$我们找到$EF^2 = FL^2 + EL^2$，即
$$x^2 = a^2 - y(a - y) - z(a - z).$$

最后一个对应关系本身就很有趣，可以用来解决其他问题。

考虑穿过线 $EF$ 和 $CD$ 的平面。该平面与沿圆（以 图 6 表示）外接三角形的球体相交。对于该圆，线段 $MN$ 和 $CD$ 是在点 $F$ 处相交的弦。因此，
$$CF \cdot DF = MF \cdot NF$$
（证明它！），那就是
$$y(a - y) = \frac{5}{12} x^2.$$

同样，从等式
$$AE \cdot BE = ME \cdot NE$$
我们得到
$$z(a - z) = \frac{1}{3} x^2.$$

从对应关系（4）、（5）和（6）我们发现
$$x^2 = a^2 - \frac{5}{12} x^2 - \frac{1}{3} x^2, \quad x = \frac{2a}{\sqrt{7}}.$$

练习

1. （MIPT，1966）。正三角形的边$ABCD$等于$a$。球体是在边 $AB$ 上构建的，就像在直径上构建的一样。求以点 $A$ 为顶点且与所构造的球体相切的三角形的三角角内接的球体的半径。

2. （MIPT，1966）。在正三角形帕酰胺$SABC$内，底边为$a$，帕酰胺的高度为$a\sqrt{3}$。点$M, N$和$K$是相应侧边$AS, BS$和$CS$的中点。求与聚酰胺底部和线 $AK, CN$ 和 $BM$ 相切的球体半径。

3. （MIPT，1967）。在正三角形帕拉米德中，内切球通过外接球的中心。外接球的半径比外接球的半径大多少倍？

4. （MIPT，1968）。内切于正四边形帕酰胺的球的中心距侧边的距离为$\sqrt{2}cm$，距底边的距离为$\sqrt{5}cm$。求球的半径。

5. （MIPT，1968）。内切于正四边形帕酰胺的球的中心距侧边的距离为$\sqrt{2}cm$，距底边的距离为$\sqrt{5}cm$。求球的半径。

6. （MIPT，1969）。正三角形的边$ABCD$等于$a$。求穿过顶点 $A, B$、边 $CD$ 中点和面中心 $ABC$ 的球体半径。

7. （MIPT，1971）。在正四边形帕拉米德$SABC$中，底边$ABCD$的边长为$b$，帕拉米德的高度为$b\sqrt{2}$。在此帕酰胺中内切的球体在点 $K$ 处接触侧面 $SAD$。求通过点 $K$ 和边 $AB$ 的平面的帕酰胺横截面积。

**前往任务M86。**

该声明变为错误。左边图有一个四边形，右边有五个。
