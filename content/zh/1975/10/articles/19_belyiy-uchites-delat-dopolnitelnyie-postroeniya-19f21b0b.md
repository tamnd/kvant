---
id: 1975-10-belyiy-uchites-delat-dopolnitelnyie-postroeniya-19f21b0b
issue: kvant_1975_10
year: 1975
number: "10"
title: 学习制作额外的结构
authors:
  - Белый С. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: NEMY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2ee7f32885a234b31ae064ef7a92f3cee4dfc1d8f2a8ec30ba88d920f7d43b1c
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/19_belyiy-uchites-delat-dopolnitelnyie-postroeniya-19f21b0b.md
source_content_sha256: b17642aa7c40d9c981b6e666e7936f344bb0f4448ddc700549b465fa559735e4
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

学习制作额外的结构
S·B·贝利

几乎每个几何问题都可以通过多种方式解决。尝试找到最简单、“漂亮”的解决方案总是很有趣 - 特别是因为此类解决方案受到审查员的高度评价。额外的结构通常有助于此。在一种情况下，这些构造是由它们自己指导的，而在另一些情况下，梦想并不那么明显，需要决策者的大量经验、独创性和几何直觉。

让我们继续考虑具体任务。

问题1. 在直角三角形的AC、BC 边上，在其构造之外是正方形ACDE 和BCKF。从点 E 和 F 开始，重新分布 EM 和 FN 落在斜边的延长线上。证明 EM + FN = AB。

在直角三角形 ACB 中，我们画出高度 CL（参见 图 1）。

显然，ΔACL=ΔEAM，ΔBCL=ΔFBN。因此 EM = AL，FN = LB，EM + FN = AL + LB = AB。

问题 2。（MIPT，1970）。如果等边边界的对角线相互重新分布并且边界的面积等于S，则等边边界的高度最大。

让我们通过顶点 C 平行于对角线 BD 画一条线，直到它与梯形 AD 的底延长线在点 E 相交（参见 图 2）。由于梯形是等边的，并且它的对角线相互重新分布；那么三角形 ACE 是等边直角的（证明一下！）。在三角形 ACE 中，我们画出高度 CF 并用 h 表示其长度。显然 AF = CF，但 AF 等于梯形的中线，因此 S = h²。因此，h = √S。

正如你所看到的，这个任务很简单，主要的难点是

图 1.
图 2.

⟦folio 49⟧

我们决定进行适当的额外建设。

问题3. 在三角形ABC 的边AB 和BC 上，在其外侧构造正方形ABDE 和BCKF。证明线段 DF 是三角形中位 BP 的两倍。

我们将三角形 ABC 延伸为平行四边形，并将中值 BP 延伸至其对角线（参见 图 3）。让$ABC = \alpha$，然后$DBF = 180^\circ - \alpha$。但也有$BCQ = 180^\circ - \alpha$，并且这些角围成的边也彼此相等，因此$\Delta DBF = \Delta QCB$。因此，$BQ = 2BP = DF$。

问题4. 在三角形内部，找到一个点，如果将线段与三角形的顶点连接起来，则三角形将被分成三部分，其面积之比为$m:n:q$。

我们将三角形 ABC 的底 AC 按 D 点和 E 点分成三部分，比例为 $m:n:q$ (图 4)。通过D点画一条与AB平行的线，通过E点画一条与BC平行的线。让我们证明这些线的交点 O 就是所需的点。证明顶点 B 与点 D 和 E 的连接。$S_{\Delta AOB} = S_{\Delta ABD}$，因为这些三角形有公共底 AB 和相等的高度。与$S_{\Delta BOC} = S_{\Delta BEC}$类似，下一个与$S_{\Delta AOC} = S_{\Delta DBE}$类似。但三角形 ABD、DBE、EBC 的面积比率为 $m:n:q$，因为它们的高度相同。因此，$S_{\Delta AOB} : S_{\Delta BOC} = m:n:q$。

问题5 通过三角形ABC 中线的交点，画一条与AB 和AC 边相交的线l。证明直线l到顶点B和C的距离之和等于它到顶点A的距离。

设 O 为三角形中线的交点，AD 为中线 (图 5)。让我们将垂线 BM、DL、CN、AK 放到直线 l 上。容易看出DL是梯形BMNC的中线，$DL = \frac{BM + CN}{2}$和$\Delta AKO \sim \Delta DLO$，所以$\frac{DL}{AK} = \frac{DO}{OA} = \frac{1}{2}$和$AK = 2DL = BM + CN$。

⟦figure⟧
图 6.

⟦figure⟧
图 7.

问题 6。（密歇根州立大学，力学和数学，1973 年）。 *在梯形中，对角线为3和5，连接底边中点的线段为2。求梯形的面积。*

首先，请注意点$E$和$F$——梯形$ABCD$的底$BC$和$AD$的中点（参见图6）——以及对角线交点$O$位于同一条直线上（证明一下！）。通过点$C$，我们画两条直线：一条平行于对角线$BD$，直到它与底线$AD$的延长线相交于点$L$，另一条平行于$EF$。由于$OF$是三角形$AOD$的中线，因此$CK$是三角形$ACL$的中线。现在我们将三角形 $ACL$ 补充为平行四边形，并将中线 $CK$ 补充为它的对角线。 $S_{\square ABCD} = S_{\Delta ACL} = S_{\Delta ACQ}$（为什么？）。需要注意的是，$\Delta ACQ$是矩形，$S_{\Delta ACQ} = 6$。

问题 7（MIPT，1970）。 *两个相等的圆相交于点$C$。通过点 $C$ 绘制两条线，分别与这些圆相交于点 $A$、$B$ 和 $M$、$N$。线$AB$与中心线平行，线$MN$与中心线形成角度$\alpha$。 $AB$的长度等于$a$。求线段 $MN$ 的长度。*

从点 $A$ 和 $B$，我们将垂线 $AE$ 和 $BF$ 垂到直线 $MN$（参见 图 7）。让$\sphericalangle AMC = \beta$，然后$\sphericalangle CNB = 180^\circ - \beta$（为什么？），然后$\sphericalangle FNB = \beta$。从等式三

⟦column⟧

三角形 $AEC$ 和 $BFC$（由斜边和角度）可以得出 $AE = BF$。从$\sphericalangle AMC = \sphericalangle FNB$开始，然后是$\Delta AEM = \Delta BFN$和$ME = NF$。因此$MN = EF = EC + CF =$

$$= \frac{a}{2}\cos\alpha + \frac{a}{2}\cos\alpha = a\cos\alpha.$$

问题 8（MIPT，1973）。 *半径为 $R$ 和 $r$ $(R > r)$ 的两个圆在点 $A$ 处有外切线。通过在大圆上取的点 $B$，绘制一条直线，在点 $C$ 处与小圆相交。如果弦 $AB$ 等于 $a$，求线段 $BC$ 的长度。*

通过小圆的中心$O$和点$B$，我们画一条直线（参见图8）。然后$BC^2 = OB^2 - r^2$。由余弦定理

$$OB^2 = (R + r)^2 + R^2 -$$
$$-2R\,(R + r)\cos\sphericalangle AO_1B,$$

在哪里

$$\cos\sphericalangle AO_1B = \frac{2R^2 - a^2}{2R^2}.$$

因此，
$$BC^2 = (R+r)^2 + R^2 - 2R\,(R+r)\times$$
$$\times\ \frac{2R^2 - a^2}{2R^2} - r^2 = a^2\left(\frac{R+r}{R}\right),$$

$$BC = a\sqrt{1 + \frac{r}{R}}.$$

问题 9（密歇根州立大学生物学院，1973 年）。 *过面积为1的平行四边形ABCD的边BC的中点M与顶点A作与对角线相交的直线*

⟦folio 50⟧

⟦folio 51⟧

尿O中的最终BD。求四边形OMCD的面积。

通过B点我们画一条与AM平行的直线，直到它与边AD的延续相交于E点，通过A点我们画一条与BD平行的直线AF（见图9），$S_{\triangle EBD} = \frac{3}{4}$（为什么？）。现在，由于三角形 EFA 和 EBD 的相似性，我们可以写：$\frac{S_{\triangle EFA}}{S_{\triangle EBD}} = \frac{EA^2}{ED^2}$。

但是$\frac{EA^2}{ED^2} = \frac{1}{9}$，从这里我们找到$S_{\triangle EFA} = \frac{1}{12}$。但是$S_{\triangle EFA} = S_{\Delta BOM}$，现在我们可以求出OMCD四边形的面积：

$S_{OMCD} = S_{\triangle BDC} - S_{\triangle BOM} = \frac{5}{12}$.

让我们得出一些结论。当开始解决几何问题时，您需要记住，一般的几何问题可以通过多种方式解决。因此，如果你有解决问题的想法，但你发现解决问题的路径很长，那么就尝试寻找不同的解决方法。应该记住，额外的结构可以提供重要的帮助。

乌拉真亚

1（MIPT，1963）。求中线分别为 12、15 和 21 厘米的三角形的面积。

2（MIPT，1967）。基本等边梯形比例为3：2。在较大的底座上，就像在直径上一样，建立一个圆，在较小的底座上切出等于该底座一半的一段。圆与梯形各边的比例是多少？

3（MIPT，1969）。在矩形梯形中，对角线相互垂直，底边的关系为 m:n。求梯形对角线的比率。

4（MIPT，1970）。梯形ABCD中，大底AD的长度等于a，BC⊥CD，AB=BC，BD⊥AB。找出梯形的边。

5. （MIPT，1970）。在底角为锐角α的等边梯形中，以一侧为直径所画的圆与另一侧相切。梯形的底边与梯形的底边的比例是多少？

6（密歇根州立大学经济学院，1964 年）。在底边为 a 和 b 的梯形中，通过对角线的交点画一条与底边平行的线。找到这条线包围在两侧之间的线段。

7（密歇根州立大学化学系，1967 年）。在三角形 ABC 中，从顶点 A 绘制一条直线，与 BC 边相交于位于 B 点和 C 点之间的 D 点，且 CD : BC = α（其中 α < $\frac{1}{2}$）。在 B 点和 D 点之间的 BC 边上，取点 E，并通过它画一条直线，平行于边 AC，并与边 AB 相交于点 F。如果已知 CD = DE，则求梯形 ACEF 和三角形 ADC 的面积比。

8（密歇根州立大学，力学，1973 年）。在梯形ABCD中，点K和M分别是对应的底AB=5和CD=3。如果三角形AMB是直角三角形，DK是梯形的高，求梯形的面积。
