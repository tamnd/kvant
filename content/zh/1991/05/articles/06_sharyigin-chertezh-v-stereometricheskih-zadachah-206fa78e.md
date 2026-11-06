---
id: 1991-5-sharyigin-chertezh-v-stereometricheskih-zadachah-206fa78e
issue: kvant_1991_5
year: 1991
number: "5"
title: 绘制立体问题
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 49
page_last: 52
page_labels: 47, 50
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9ebaf0d02c44c3b77ee8b38c8ca975b5198583be535ceea555bde5571f3ac498
prompt_sha256: draft-1
translated_from: content/ru/1991/05/articles/06_sharyigin-chertezh-v-stereometricheskih-zadachah-206fa78e.md
source_content_sha256: 95256abf278c42c3773184ff1162f76044bb741f6fb72c43262ed0c7b3cd8431
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

画入
立体测量
任务

I.沙里金

在解决立体问题时，绘图的作用显着增加。绘图不仅作为解题的有效要素，而且很大一部分包含在解题方法中，提供了解决问题的关键。本文将讨论某些类型的此类任务。

首先，我们注意到空间体可以分为两类：“好”，方便描绘，和“坏”。第一组包括三角形（主要是规则的）、平行六面体、三角形和四边形参数。 Ko 第二个 - $n$-gonal ($n > 4$) 和参数、截断参数和圆形物体，尤其是球体，都被识别。

最令人沮丧的技术之一是，在给定的“不方便”的构造中，“好的”多面体被隔离为关键元素。这个例子给出了

问题 1. 如果顶点处的平面角为 $\alpha$，求直立六边形相邻侧边之间的二维角度。

解决方案。这里可以方便地考虑三角形参数 - 给定参数的 1/6 部分 - 其顶点是原始参数 (图 1) 的高度的两端和底边的一侧。在此参数中，$OB=OA$、$\angle BOA=60^\circ$、$SO$ 垂直于平面$AOB$、$\angle ASB=\alpha$。平面$ASB$和$OBS$（或$OAS$）之间的二面角等于所需角度的一半（所需角度$\varphi$）。让我们从$A$垂直于$AD$和$AK$下降到$BS$和$OB$。然后$\angle KDA=\varphi/2$（证明它）。代入$OA=OB=R$，我们有

$$AK=R\frac{\sqrt{3}}{2}, AB=R, AD=\frac{R}{\cos \alpha/2},$$

$$\sin \frac{\alpha}{2}=\frac{AK}{AD}=\frac{\sqrt{3}}{2}\cos \frac{\alpha}{2},$$

$$\varphi=2\arcsin\left(\frac{\sqrt{3}}{2}\cos \frac{\alpha}{2}\right).$$

这个非常简单的任务纯粹是说明性的。

在有关立体问题或与绘图相关的其他问题的每项有意义的任务中都很实用。可以找出一些典型的公认的，根据相关情况使用。因此，例如，在涉及空间中的直线和平面的问题中，我们必须尝试将给定的配置“绑定”到“好的”多面体。接收器和飞机不应在太空中“悬挂”！它们必须连接

⟦folio 50⟧

---
running_head:
folio:
---

在下一个任务中，主要问题（如任务 4）是找到所需的图形解释。

问题 6. 半径为 1 和 3 的两个球在外部相互接触。通过距离变化球中心 3 处的点 M，绘制两条与公共球相切的直线。如果您知道切线之一与穿过球中心的直线形成 45° 角，请求切线之间的角度。

解决方案。让我们分别用$O_1$和$O_2$表示球的中心，用$A$和$B$表示与直线$O_1O_2$形成45°角的切线的切点。现在这个构造对于三棱柱$O_1ACDBO_2$（图7）来说已经足够了。由于边 $AB$ 垂直于边 $AO_1$ 和 $BO_2$，因此该棱镜是直棱镜。在矩形$O_1CO_2D$中，对角线$O_1O_2$与边$O_1D$形成45°角，因此该矩形是正方形。它的对角线是$O_1O_2=4$，也就是说这个正方形的边长是$2\sqrt{2}$。我们的棱柱的底面是直角三角形，顶点为 $O_1$ 和 $D$ ($O_1C^2=9-1=AC^2-AO_1^2$)。根据条件，点$M$位于直线$AB$上距$O_1$ 3 的位置。但是$O_1B=3$。因此，出现两种情况：1）$M$与$B$重合； 2) $M$ 相对于点 $A$ 对称$B$。

接下来，我们注意到对称线$AB$的第二条切线是相对于平面$MO_1O_2$的。因此，切线之间的角度等于切线之一与平面 $MO_1O_2$ 之间的角度的两倍（或补该角度为 $180^\circ$）。

考虑第一种情况：$M$与$B$重合。我们需要找到直线 $BA$ 和平面 $BO_1O_2$ 之间的角度。该角度等于 $DO_1$ 与平面 $BO_1O_2$ 之间的角度。考虑三角形paramid $BDO_1O_2$。它的体积是$\frac{1}{6}BD \cdot DO_2 \cdot DO_1=\frac{4}{3}$。现在让我们以三角形 $BO_1O_2$ 为底：$BO_2=3$、$BO_1=3$、$O_1O_2=4$。 $BO_1O_2$的面积等于$2\sqrt{5}$。如果$h$是从$D$下降到$BO_1O_2$的高度，则$\frac{2}{3}\sqrt{5}h=\frac{4}{3}$。从这个方程我们找到$h=\frac{2}{\sqrt{5}}$。因此，$DO_1$ 和平面 $BO_1O_2$ 之间的弧线等于 $\frac{1}{\sqrt{10}}$。这意味着 $\frac{\alpha}{2}=\arcsin \frac{1}{\sqrt{10}}$（或 arctg $\frac{1}{3}$），其中 $\alpha$ 是所需的角度。

第二种情况是独立考虑的。然而，我们可以报告，在第二种情况下，答案与第一种情况相同。这是因为$AO_1$是$AB$和$O_1O_2$之间的公垂线，并且每种情况对应的点$M$关于$A$对称。

我想强调的是，绘图的构建不是解决问题之前的单个动作，而是包含在解决方案中的一个过程，并且从头到尾伴随着所有解决方案。
