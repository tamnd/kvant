---
id: 1979-9-sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c
issue: kvant_1979_9
year: 1979
number: "9"
title: 几何问题的几何解
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 44
page_labels: 38-42
tag: 4S9C
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b05b70a88eaf4aa5c1acb8f71ae5e6b216f4a7bae363bd72240d4b50246d2493
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/15_sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c.md
source_content_sha256: 2b4384ab2947b17b794fa3a6ab14ca91fe91065d99f5af34d74dd1416d84a6d8
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

几何问题的几何解

谨以此纪念基辅市的数学老师 Vainman V. Sh.。

在解决几何问题时，他们首先求助于各种分析方法。目前，本文讨论了几种使解决方案简单合理的几何方法。所提出的方法几乎是相同的，毫无疑问，对读者来说并不陌生，但是，尽管如此，有关它们的信息似乎对每个想要学习如何很好地解决几何问题的人都有用。

1. 让我们确定图形的类型。

在某些情况下，如果您首先确定原始图形可能（或可能不）具有的类型，那么解决问题的速度将会显着加快。

问题 1（密歇根州立大学，VMK，1978 年）。三角形 AMB 外接一个圆，其圆心距边 AM 的距离为 10。边AM超出顶点M的延伸，从通过顶点B画的圆的切线上切出一条等于29的线段BC。如果已知角ACB等于arctan$\frac{20}{21}$，求三角形BMC的面积。

让我们确定三角形 BMC 的类型，为此我们绘制其高度 $BM_1$，继续它与圆在点 $M_2$ 的交点，并将圆 O 的中心投影到边 AM 和弦 $BM_2$ (图 1) 上。那么根据条件，

$$|OK| = 10, |BM_1| = |BC| \sin \widehat{ACB} = 29 \sin \left( \arctg \frac{20}{21} \right) = 29 \cdot \frac{20}{29} = 20 = 2 |OK|, |BM_2| = 2 |BL| = 2 (|BM_1| - |LM_1|) = 2 (|BM_1| - |OK|) = 2 |BM_1| - |BM_2| = |BM_1|.$$

由此可见，点 M、$M_1$ 和$M_2$ 重合（图 2），因此点 O 位于 [AB] 上，三角形 BMC 是直角三角形。其余的都清楚了。 （答案210。）

问题 2（密歇根州立大学，地质学。教员，1978 年）。三角形ABC中，边长为$|AC| = 3, \widehat{BAC} = \frac{\pi}{6}$，外接圆半径为2。证明三角形ABC的面积有一条边小于3。

让我们证明 $\triangle ABC$ 不可能是直角。事实上，让我们从 A 点画一个半径为 2 的圆，弦 AC、AB$_1$、AB$_2$ 和直径 AD (图 3)，这样$|AC| = 3, \widehat{B_1AC} = \widehat{B_2AC} = \frac{\pi}{6}$。线段 AB$_1$ 与线段 AD 不重合，因为$\widehat{CAB}_1 = \frac{\pi}{6} \neq \arccos \frac{3}{4} = \arccos \frac{|AC|}{|AD|} = \widehat{CAD}$。因此$\widehat{ACB}_1 \neq \frac{\pi}{2}$和$|AB_1| < |AD|$。因此$S_{\Delta AB_1} = \frac{1}{2} |AC| \cdot |AB_1| \sin \widehat{B_1AC} < \frac{1}{2} |AC| \cdot |AD| \sin \widehat{B_1AC} = \frac{1}{2} \cdot 3 \cdot 4 \times \sin \frac{\pi}{6} = 3$。从 $|AB_2| < |AC| = 3$ 很容易得出不等式 $S_{\Delta AB_2} < 3$。

2. 让我们“完成”这个图。

几何问题的每个几何解决方案都从绘制绘图开始。

⟦folio 39⟧

同时，有时在“自然”绘图中（即在仅“描绘”条件的绘图中）很难注意到数据与原始值之间的联系，而如果图形“完成”，这些联系就会变得明显。

问题 3（密歇根州立大学土壤科学学院，1977 年）。梯形ABCD的底边CD、对角线BD和边AD的长度彼此相等并且等于p。边 BC 的长度等于 q。求对角线 AC 的长度。

在这个梯形ABCD（图4）中，不可能看出原来的对角线AC与其他线段之间的联系。如果考虑到D点与A、B、C点等距，画一个圆O(D, p)，并将这个梯形“补全”为等腰梯形ABCE，那么很容易从直角三角形ACE中找到$|AC| = \sqrt{4p^2 - q^2}$。

问题 4（NSU，1976）。在以 AB 和 CD 为底的梯形 ABCD 中，B 的二等分线垂直于 AD 的外边，与点 E 相交。比例是多少

如果已知线段AE的长度是线段DE的两倍，则直线BE除以梯形的面积？

如果我们把这个梯形ABCD“补全”为三角形AFB（图5），我们就得到一个等边三角形，其中线段DC与相似系数$\frac{1}{4}$的相似三角形DFC相切。因此，所需比例为$\frac{S_{EDCB}}{S_{\Delta AEB}} = \frac{S_{\Delta EFB} - S_{\Delta DFC}}{S_{\Delta AEB}} = \frac{\frac{1}{2} S_{\Delta AFB} - \left(\frac{1}{4}\right)^2 S_{\Delta AFB}}{\frac{1}{2} S_{\Delta AFB}} = \frac{7}{8}$。

3. 我们来描述一个圆。

在某些情况下，问题的几何求解中的一个重要点是建立某些角度的一致性。大多数情况下，这些角度在相似的三角形中是对应的

⟦folio 40⟧

或多边形。然而，当一对角度的同余被认为是从另一对角度的同余推导出来时，这种情况是可能的，而另一对角度的同余的值是已知的。例如，在四边形 $ABCD$ 附近当且仅当当 $\widehat{ABC} + \widehat{ADC} = 180^\circ$ 时可以描述圆（“几何 8”，第 113 页）。很容易证明这个条件与条件$\widehat{ABD} = \widehat{ACD}$等价。因此，等式 $\widehat{ABD} = \widehat{ACD}$、$\widehat{ACB} = \widehat{ADB}$、$\widehat{BAC} = \widehat{BDC}$、$\widehat{CAD} = \widehat{CBD}$ 等价于 (图 6)。

问题 5（MIPT，1976）。点$E$位于正确三角形$ABC$的边$AC$上；点$K$是线段$AE$的中间。垂直通过点$E$的线（$AB$）和垂直通过点$C$的线（$BC$）相交于点$D$。找到三角形 $BKD$ 的角。

让线 $ED$ 与线 $AB$ 相交于点 $F$ (图 7)。那么三角形$AFE$是矩形，$[FK]$是中线。这意味着三角形 $AFK$ 是正三角形，类似于给定的三角形 $ABC$。波斯尼$[FK] \parallel [BC]$和四边形$BFKC$是等边梯形。因此，围绕它画一个圆圈。从$\widehat{BFD} + \widehat{BCD} = 90^\circ + 90^\circ = 180^\circ$可知点$D$属于同一个圆。

波兹尼 $\widehat{BKD} = \widehat{BFD} = 90^\circ$、$\widehat{KDB} = \widehat{KCB} = 60^\circ$ 和 $\widehat{DBK} = 30^\circ$。

问题 6（密歇根州立大学，物理学，1974 年）。点 $A$ 取于顶点 $L$ 的角的二等分线上。点 $K$ 和 $M$ 是从 $A$ 垂到角两侧的垂线的底边。在线段$KM$上，取点$P$（|$KP$| < |$PM$|），并通过点$P$，垂直于线段$AP$，绘制一条直线，与线$KL$相交于点$Q$（在$Q$之间）和$L$），以及点$S$处的直线$ML$。已知$\widehat{KLM} = \alpha$、|$KM$| = $a$, |$QS$| = $b$。求线段 $KQ$ 的长度。

如您所知，$|AK| = |AM|$。很容易报告$\widehat{AKM} = \widehat{ALK} = \frac{\alpha}{2}$。

波兹尼$|AK| = \frac{a}{2\cos \frac{\alpha}{2}}$。

围绕四边形$APKQ$（$\widehat{APQ} = \widehat{AKQ} = 90^\circ$）和$APSM$（$\widehat{APS} + \widehat{AMS} = 90^\circ + 90^\circ = 180^\circ$），可以描述圆（图8）。搜索 $AQS = AQP = AKP = AKM = AMK = AMP = ASP = ASQ = \frac{\alpha}{2}$，三角形 $AQS$ - 等边。从$\triangle AQS$有$|AQ|$，然后从直角三角形$AKQ$ - $|KQ| = \frac{\sqrt{b^2 - a^2}}{2\cos \frac{\alpha}{2}}$。

⟦folio 41⟧

4. “这个引导三角”

该问题的庞斯克几何解可以在图形距离方向上进行，其性质得到了很好的研究。然而，这些图形之一无疑是三角形。忠实和友善的帮助 - 三角 - 对未知的探索，有时在我们的分歧中、在寻找简单而明确的解决方案中是不可或缺的。让我们给出以下建议：如果您难以选择正确的几何路径来解决问题，请寻找三角形！

问题 7（密歇根州立大学，VMK，1975 年）。给定一个矩形梯形，其底等于 a 和 b (a<b)。我们知道，一条平行于某片海底的直线将其切成两个梯形，每个梯形中都可以内接一个圆。确定这些圆的半径。

让我们把这个梯形ABCD延伸成一个三角形(图9)。让梯形AEFD和EBCF的内接圆在M和N点与[EF]相切，它们的半径分别为R和r。由于该梯形是矩形，|EM|=R，|EN|=r。由等式 |KP|=|KQ|很容易推导出|EN|=|MF|。 （这个说法具有一般性：在任何三角形中，内切圆和外圆的切点到它们所切边的端点的距离是等距的。内切圆是与三角形的一条边和另外两条边的延长线相切的圆。）所以|EF|=R+r。根据三角形 BKC、EKF 和 AKD 的相似性，我们得到系统

$$\begin{cases} \frac{a}{R+r} = \frac{r}{R}, \\ \frac{R+r}{b} = \frac{r}{R} \end{cases}$$

（相似三角形中，内切圆半径和外圆半径均视为对应边），其中$R = \frac{bV_a}{V_a + V_b}$，$r = \frac{aV_b}{V_a + V_b}$。

图 9.

图 10.

问题 8（密歇根州立大学物理系，1975 年）。在矩形 ABCD (|BC|>|CD|) 中，对角线 AC 和 BD 相交于 O 点。角 CAD 的平分线与 [BD] 相交于 E 点。设 F 为从 E 点到 AD 边的垂线的底； K点是中间[AD]。通过 E 点，也向 [AE] 画垂线，直到与对角线 AC 相交于 H 点。如果 |OH|=b，|KF|=\frac{4}{3}b，则求面积 ABCD。

让我们做[EL] || [AD]，其中 L∈[AO] (图 10)。由于 $\hat{AEL} = \hat{EAD} = \hat{EAC}$，|AL|=|LE|=2|ME|=2|KF|=\frac{8}{3}b.

让我们继续垂直 HE，直到它与 [AD] 相交于点 G。三角形 AHG 是等边三角形（[AE] 是平分线和高度）。由于[LE]是其中的中间线，

⟦folio 42⟧

图 11.

三角形 LHE 也将是等边的。波兹尼

$$|OM| = \sqrt{|OL|^2 - |LM|^2} = \sqrt{(|LH| - |OH|)^2 - |ME|^2} = \sqrt{(|LE| - |OH|)^2 - |KF|^2} = \sqrt{\left(\frac{8}{3}b - b\right)^2 - \left(\frac{4}{3}b\right)^2} = b.$$

使用具有相似系数的相似三角形ACD和LOM

$$\kappa = \frac{|AC|}{|LO|} = \frac{2|AO|}{|LH| - |OH|} = \frac{2(|AL| + |LH| - |OH|)}{|LE| - |OH|} = \frac{2\left(\frac{8}{3}b + \frac{8}{3}b - b\right)}{\frac{8}{3}b - b} = 5,2,$$

找到需要的区域

$$S_{ABCD} = 2S_{\Delta ACD} = 2k^2 S_{\Delta LOM} = k^2 \cdot |LM| \cdot |OM| = (5,2)^2 \cdot \frac{4}{3}b \cdot b = \left(36 \cdot \frac{4}{75}\right)b^2.$$

问题 9（MIPT，1974）。圆周围描述了以 AD 和 BC 为底的等边边界 (|AD| > |BC|)。与对角线 AC 平行的直线与相应边 AD 和 CD 相交于点 M 和 N，并与圆相交于点 P。如果 $\frac{|MP|}{|PN|} = k$，请确定边界的角度。

考虑相似三角形 ACD 和 MND (图 11) 可得出简单的几何解。让我们用 E、F 和 G 分别表示圆在 AD、CD 和 BC 边上的切点，用 H 和 Q 表示 C 和 N 点在 AD 边上的投影。让|PN| = 1. 那么|MP| = k, |AH| = |AE| + |EH| =|ED| + |气相色谱| =|DF| + |FC| = |DC|。根据相似性的性质，在三角形 MND 中，将有 |MQ| = |DN|。波兹尼

$$|MN| = |MP| + |PN| = k + 1, |DQ| = |DE| - |QM| - |ME| = |DF| - |DN| - |MP| = |NF| - |MP| = |NP| - |MP| = 1 - k, 2 |NQ|^2 = (|MQ|^2 + |NQ|^2) - (|DN|^2 - |NQ|^2) = |MN|^2 - |DQ|^2 = (k + 1)^2 - (1 - k)^2 = 4k, |NQ| = \sqrt{2k}.$$

因此，tan$\hat{D} = \frac{|NQ|}{|DQ|} = \frac{\sqrt{2k}}{1 - k}, \hat{A} = \hat{D} = \arctg \frac{\sqrt{2k}}{1 - k}, \hat{B} = \hat{C} = \pi - \arctg \frac{\sqrt{2k}}{1 - k}.$

练习

1（密歇根州立大学，语言学院，结构和应用语言学系，1978 年）。五边形ABCDE内接于单位半径的圆。众所周知|AB| = $\sqrt{2}$、$ABE = 45^\circ$、$EBD = 30^\circ$ 和 |BC| =|CD|。五边形的面积是多少？

2（密歇根州立大学，地质系，1978 年）。在三角形ABC中，边AB的长度是4。 $\widehat{CAB} = \frac{\pi}{3}$，外接圆R的半径等于2.2。证明从顶点C到边AB下降的高度的长度严格小于 $\frac{11\sqrt{3}}{5}$.

3（新西伯利亚州立大学，1976）。在平行四边形ABCD中，角BAD为60°。经过 A、B、D 点的圆与边 CD 相交于中点。如果圆的半径为R，求平行四边形的面积。

4（密歇根州立大学，感官科学学院，1977 年）。梯形ABCCD的底边AB是底边CD长度的两倍，也是边AD长度的两倍。对角线AC的长度等于a，侧边BC的长度等于b。求梯形的面积。

5（造币厂，1977 年）。半圆的圆心位于梯形ABCCD的大底AD上；所有其他边都接触半圆。证明|AD| =|AB| + |CD|。
