---
id: 1989-9-gabovich-teorema-o-treh-sinusah-ed507aa8
issue: kvant_1989_9
year: 1989
number: "9"
title: 三正弦定理
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 73
page_last: 74
page_labels: 71-72
tag: WNEE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: dae2539fcbaa832b543fda5df34d75adf2fbe0c6032f11fc10f0ebc0ae8e2c8a
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/17_gabovich-teorema-o-treh-sinusah-ed507aa8.md
source_content_sha256: a787a203ee6bca2086051951676918cf89109546254c61b230eb9532b352a92b
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 71⟧

Teorema
关于三罪

加博维奇

在许多立体测量问题中，常常需要确定直线和平面之间的角度。使用三正弦定理可以方便地完成此操作，如果您解决以下问题，您将学到该定理。

1. 在大小为 α 的二面角的一个面上，画一条直线，与该角的边缘形成角度 β。确定该直线与另一条边所成的角度。

解决方案。令 ∠ABC 为给定二面角等于 α (图 1) 的线性角，并令 ∠ADB=β。让我们将吊挂式空调降低到角落的另一侧；那么∠ADC就是原来的。让我们用 γ 表示 ∠ADC 并设置 AD=x。三角形ABD是直角三角形，所以AB=x sin β。三角形ABC也是直角三角形，所以AC=AB sin α = x sin α sin β。最后，由三角ADC可知AC=x sin γ。所以，

sin γ = sin α sin β.

这就是三窦定理，在解决问题时是相互联系的。

图 1.

⟦folio 72⟧

2. 在正三棱柱$ABCA_1B_1C_1$中，底等于高。求对角线 $AB_1$ 和平面 $AA_1C_1C$ 之间的角度。

解决方案。边 $AA_1$ 处的二面角为 $\frac{\pi}{3}$ (图 2)。对角线 $AB_1$ 与边 $AA_1$ 所成的角等于 $\frac{\pi}{4}$。令 $\gamma$ 为所需角度的大小。那么根据三正弦定理

$$\sin \gamma = \sin \frac{\pi}{3} \sin \frac{\pi}{4} = \frac{\sqrt{3}}{2} \cdot \frac{\sqrt{2}}{2} = \frac{\sqrt{6}}{4}.$$

所以，$\gamma = \arcsin \frac{\sqrt{6}}{4}$。

这是最后一个任务。

3. 正方形$ABCD$的平面与某个平面m之间的角度等于$\alpha$，边$AB$与同一平面之间的角度为$\beta$。求边 $AD$ 与平面 $\tau$ 之间的角度。

解决方案。我们假设正方形的顶点 $A$ 位于所考虑的二面角的边缘上 - 参见 图 3。角度 $BFB_1$ 和 $DED_1$ 是该二面角的线性角：$\angle BFB_1 = \angle DED_1 = \alpha$。线段$AB_1$和$AD_1$是边$AB$和$AD$在平面$\tau$上的投影。根据条件，$\angle BAB_1 = \beta$。

设$\angle BAF = \varphi$和$\angle DAD_1 = \gamma$。根据三个正弦$\sin \beta = \sin \alpha \sin \varphi$定理，我们开$\sin \varphi = \frac{\sin \beta}{\sin \alpha}$。因此，

$$\cos \varphi = \sqrt{1 - \frac{\sin^2 \beta}{\sin^2 \alpha}} = \frac{1}{\sin \alpha} \sqrt{\sin^2 \alpha - \sin^2 \beta} =$$

显然$\angle DAE = 90^\circ - \varphi$。因此，根据三正弦定理可得出

$$\sin \gamma = \sin \alpha \sin (90^\circ - \varphi) = \sin \alpha \cos \varphi = \sqrt{\sin(\alpha + \beta) \sin(\alpha - \beta)}.$$

所以，

$$\gamma = \arcsin \sqrt{\sin(\alpha + \beta) \sin(\alpha - \beta)}.$$

针对 MIPT 入学考试提出了以​​下问题。

5. 等边三角形的边$AB$和$AC$分别位于二面锐角$\varphi$的面$P$和$Q$。边$AB$与二面角的边缘形成锐角$\alpha$。求平面 $ABC$ 和面 $Q$ 之间的角度。

解决方案。我们画个图吧 - 图 4.等边三角形的顶点$A$与边$MN$相邻，边$AB$和$AC$位于面$P$和$Q$；根据条件，$\angle BAM = \alpha$。让我们画出 $BO \perp Q$ 并连接点 $O$ 和 $A$。让我们用$\varphi$表示$\angle BAO$，用$\omega$表示平面$ABC$与$Q$形成的所需角度。

两次应用三正弦定理，我们得到

$$\sin \gamma = \sin \varphi \sin \alpha$$

和

$$\sin \gamma = \sin \omega \sin \frac{\pi}{3}.$$

所以，

$$\sin \omega = \frac{2}{\sqrt{3}} \sin \varphi \sin \alpha$$
