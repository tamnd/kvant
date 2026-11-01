---
id: 1981-9-gabovich-vspomogatelnyie-otrezki-i-uglyi-da27013d
issue: kvant_1981_9
year: 1981
number: "9"
title: 辅助线段和角度
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 50
page_labels: 46, 48
tag: EFVJ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f65bca842225f61c1f3160ef4de5650aedf4c08077b915d40152ad0010649b3a
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/19_gabovich-vspomogatelnyie-otrezki-i-uglyi-da27013d.md
source_content_sha256: 99c32b4d090f363eb3a2891c2e03c032790c5dc343135a8ed4fdff9b8974edf3
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

I·加博维奇

辅助线段和角度

在解决几何问题时，除了条件中给出的量之外，还可以使用辅助量（线段的长度、角度等）并通过它们表达所需的量。此外，在某些情况下，辅助量在求解过程中“消失”（例如，它们减少），而在其他情况下，它们是通过数据确定的。

问题 1（MIPT，1979）。三角形 ABC 的内切圆分别在 M 和 N 点与它的边 AC 和 BC 相切，并在 P 和 Q 点与平分线 BD 相交。如果 $\widehat{A} = \frac{\pi}{4}, \widehat{B} = \frac{\pi}{3}$ (图 1)，求三角形 PQM 和 PQN 的面积比。

解决方案。让我们在三角形 PQM 和 PQN 中画出高度 $[MM_1] \perp [PQ]$ 和 $[NN_1] \perp [PQ]$。由于三角形 PQM 和 PQN 有公共底，

$$\frac{S_{\triangle PQM}}{S_{\triangle PQN}} = \frac{|MM_1|}{|NN_1|}.$$

令 $O$ 为内切圆的圆心，$|OM| = |ON| = x$。由于$\widehat{BON} = \frac{\pi}{3}$和$\triangle ONN_1$是直头的，$|NN_1| = \frac{x\sqrt{3}}{2}$。从$\widehat{C} = \frac{5}{12}\pi$开始，从四边形NOMC我们得到$M\widehat{ON} = \frac{7\pi}{12}$。因此$M\widehat{OM}_1 = \frac{\pi}{12}$。从$\triangle MOM_1$我们得到$|MM_1| = x\sin \frac{\pi}{12} = x\sin \left(\frac{\pi}{3} - \frac{\pi}{4}\right) = x\frac{\sqrt{6} - \sqrt{2}}{4}$。

答案：$\frac{\sqrt{3} - 1}{\sqrt{6}}$。

问题 2（MOPI，1978）。正四边形帕拉米德的高度为30°。通过 paramida 基部的侧面绘制一个平面，垂直于相对的面。求当 paramid 与该平面相交时获得的流形的体积之比。

解决方案。容易看出截面得到的四边形CDMN(图2)是一个梯形。我们通过高度 SO 和边心线 SE 绘制一个平面。该平面垂直于侧面 SAB 和 SCD（垂直于多少？）。因此$F\widehat{SO} = 30^\circ$。由于 $|SF| = |SE|$ 和 $F\widehat{SE} = 60^\circ$，三角形是 FSE 正则三角形。让$|AB| = |AD| = |EF| = x$。然后$|MN| = \frac{x}{2}, |EP| = \frac{x\sqrt{3}}{2}$。我们来求四边形参数 SCDMN 的体积。线段SP是这个paramid的高度（多少？），梯形CDMN是它的底。因此$V_{SCDMN} = \frac{1}{3}|SP| \cdot S_{CDMN}$。

从$|SP| = \frac{x}{2}$和$S_{CDMN} = \frac{(x + \frac{x}{2})}{2} \cdot \frac{x\sqrt{3}}{2} = \frac{3x^2\sqrt{3}}{8}$开始，我们得到

⟦folio 48⟧

$\triangle SDE$我们找到$|DE| = x \sin \frac{\alpha}{2}$。
$|CD| = 2x \cdot \sin \frac{\alpha}{2}$。因此，
$V = \frac{4}{3} x^2 h \sin^2 \frac{\alpha}{2}$。现在让我们用$h$和$\alpha$来表达$x^2$。为此，请考虑三角形 $SOD$。我们有$|SD|^2 = |SO|^2 + |OD|^2$，但是$|OD| = |CD| \times \frac{\sqrt{2}}{2} = x\sqrt{2} \sin \frac{\alpha}{2}$。因此$x^2 = h^2 + 2x^2 \sin^2 \frac{\alpha}{2}$，因此$x^2 = \frac{h^2}{\cos \alpha}$。因此，$V = \frac{4}{3} h^3 \frac{\sin^2 \frac{\alpha}{2}}{\cos \alpha}$。

让我们通过引入辅助角来解决这个问题。让$SDO = \varphi$。从$\triangle SDO$我们得到$|DO| = h \text{ ctg } \varphi$，$|CD| = h\sqrt{2} \text{ ctg } \varphi$。因此，$V = \frac{2}{3} h^3 \text{ ctg}^2 \varphi$。仍然需要用角度函数$\alpha$来表达$\text{ctg}^2 \varphi$。为此，我们引入了辅助段$SD$。让$|SD| = x$。然后$|DE| = x \sin \frac{\alpha}{2}$，$|OD| = x\sqrt{2} \sin \frac{\alpha}{2}$，$\cos \varphi = \frac{|OD|}{|SD|} = \sqrt{2} \sin \frac{\alpha}{2}$。因此$\text{ctg}^2 \varphi = \frac{\cos^2 \varphi}{1 - \cos^2 \varphi} = \frac{2 \sin^2 \frac{\alpha}{2}}{\cos \alpha}$，这会导致收到较早的答案。

在这种情况下，问题的第二个解决方案比第一个解决方案稍长。

引入辅助线段通常有助于解决给定角度和一些非线性元素（例如体积）的问题，并且您需要找到另一个非线性元素（原始或某种相关图形的表面、横截面积、体积）。

问题 5（KSU，物理学家，1978）。表面积为 $S$ 的球体有一个维桑锥体。圆锥体的母线与底面的夹角等于$\alpha$。确定圆锥体的总表面积。

解决方案。如果圆锥体是球的内切面，则球的中心位于圆锥体的高度或其延伸超出底座平面的位置（“几何 9-10”，第 108 页）。所考虑的图形组合的主要横截面

图 5.

一个等边三角形内接于一个大圆。

如果 $\alpha \geq 45^\circ$，则球的中心$O$ 位于圆锥体的高度 (图 5)。设 $|DB| = x$；然后从$\triangle DBO_1$我们找到$|O_1B| = x \cdot \cos \alpha$。
$S_n = \pi |O_1B| \cdot (|DB| + |O_1B|) = \pi x \cos \alpha (x + x \cdot \cos \alpha) = 2\pi x^2 \cos \alpha \cdot \cos^2 \frac{\alpha}{2}$.

显然$\hat{DOE} = \hat{DBO}_1 = \alpha$和$|DE| = \frac{x}{2}$。从$\triangle DOE$我们得到$|DO| = \frac{x}{2} \sin \alpha$和$S = 4\pi \cdot \frac{x^2}{4 \sin^2 \alpha} = \frac{\pi x^2}{\sin^2 \alpha}$，由此得到$x^2 = S \sin^2 \alpha$。因此，
$S_n = 2S \sin^2 \alpha \cdot \cos \alpha \cdot \cos^2 \frac{\alpha}{2} = S \sin \alpha \cdot \sin 2\alpha \cdot \cos^2 \frac{\alpha}{2}$.

很容易看出，上述论点对于$\alpha < 45^\circ$仍然有效。

练习

1（MIPT，1979）。在$\triangle ABC$中给定$\hat{A} = \frac{\pi}{3}$，$\hat{B} = \frac{\pi}{4}$。三角形$ABC$的延长线与它的外接圆相交于点$M, N$和$P$。已知绕直线底面和侧面描述的圆是矛盾的，求 $n$ 角直线的面积与维桑球的体积之比。

2（关键绩效指标，1978 年）。已知面积 $n$ 角直线的体积与威桑球的体积之比，已知围绕直线的底边和侧边描述的圆是矛盾的。

3（KSU，mekhahanite，1978）。面积三角形直线的顶点是球心，与直线底面相切。直线侧面积与球体面积之比等于$\alpha$。确定侧直线与底座平面的倾斜角度。
