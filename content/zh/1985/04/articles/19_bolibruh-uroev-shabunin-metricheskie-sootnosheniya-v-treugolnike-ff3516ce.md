---
id: 1985-4-bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce
issue: kvant_1985_4
year: 1985
number: "4"
title: 三角形的公制比率
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 52
page_labels: 48-50
tag: TSKU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9606f923db0d1eb91e370b9648e576710d3dcf636ae536b5eb2d6037981a4a13
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/19_bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce.md
source_content_sha256: 080d977e5b4ed50150a1c47669504e70d0aabd66f5300868419c35d35be82cbf
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

三角形的公制比率

物理和数学科学候选人 A. A. BOLIBRUKH，
物理和数学科学副博士 V. M. UROEV，
M.I.沙布宁教授

大学考试的经验表明，许多申请者在解决几何问题方面没有足够的技能。即使对于那些成功解决代数和三角学问题的申请者来说，最简单的平面问题有时也会成为绊脚石。而且，这不仅适用于需要表现出一定独创性的问题，也适用于使用学校课程的标准定理和公式解决的问题，例如余弦定理、正弦定理、三角形面积公式等。

目前，MIPT不同年份入学考试的主要提案正在考虑问题。作者从大量材料中选择了问题，其解决方案使用了三角形元素之间的基本度量关系。

让我们把这些关系写下来。距离为三角形 ABC，引入以下符号：$a = |BC|$、$b = |AC|$、$c = |AB|$、$R$ - 三角形 ABC 的外接圆的半径，$r$ - 内切圆的半径，$h_a$ - 下降到边 BC 的高度的长度，$S$ - 三角形的面积。然后

$$\frac{a}{\sin \hat{A}} = \frac{b}{\sin \hat{B}} = \frac{c}{\sin \hat{C}} = 2R$$

（正弦定理），（一）

$$a^2 = b^2 + c^2 - 2bc \cos \hat{A}$$

（余弦定理），（二）

$$S = \frac{1}{2} h_a a,$$

(III)

$$S = \frac{1}{2} bc \sin \hat{A},$$

(IV)

$$S = \frac{1}{2} (a + b + c) r.$$

(V)

申请人必须知道这些公式，能够证明它们，并在解决问题时应用它们。还有其他公式，程序员不再提供用于构造它们的知识，但它们在解决问题时通常很有用。例如，Heron 公式

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

(VI)

其中 $p = (a + b + c)/2$ 是三角形的米或公式

$$S = \frac{abc}{4R},$$

(VII)

将由正弦定理(I)求出的sin$\hat{A}$的值代入式(IV)即可容易地得到。

让我们从使用正弦定理的问题开始。

1. 在等边三角形ABC（$|AB| = |BC|$）中，中线AD与平分线CE垂直。确定 ADB 角。

解决方案。令 $\alpha$ 为所需角度，$O$ 为线段 AD 和 CE 的交点 (图 1)。在 $\triangle ADC$ 平分线中，CO 也是一个高度，这意味着 $\triangle ADC$ 是等边，$D\hat{AC} = A\hat{DC} = \pi - \alpha$、$\hat{A} = \hat{C} = 2\alpha - \pi$、$B\hat{AD} = \hat{A} - D\hat{AC} = 3\alpha - 2\pi$。在三角形ABD中，根据条件$|BD| = 1/2 |AB|$。应用正弦定理，我们得到$\frac{|AB|}{\sin \alpha} = \frac{|BD|}{\sin (3\alpha - 2\pi)}$，从中得到$\frac{1}{\sin \alpha} = \frac{1}{2 \sin 3\alpha}$、$2 \sin 3\alpha = \sin \alpha$、$2 \sin \alpha (3 - 4 \sin^2 \alpha) = \sin \alpha$、$\sin^2 \alpha = 5/8$。但从问题的条件来看，$D\hat{CO} = \alpha - \pi/2 > 0$，另一方面，$\alpha < \pi$，即$\pi/2 < \alpha < \pi$，因此$\sin \alpha = \sqrt{10}/4$，$\alpha = \pi - \arcsin \sqrt{10}/4$。

答案：$\pi - \arcsin \sqrt{10}/4$。

2. 在等边三角形ABC中，高BD到底边的长度等于h，外接圆的半径等于r。求该三角形的外接圆的半径。

⟦folio 49⟧

解决方案。令 $O$ 为内切圆的圆心，$E$ 为圆与线段 $AB$、$|AC| = b$ (图 2) 的切点。根据正弦定理，外接圆的半径$R$为$\frac{b}{2 \sin \hat{B}}$。从$\triangle BOE$开始有$\sin \frac{\hat{B}}{2} = \frac{|OE|}{|OB|} = \frac{r}{h-r}$。另一方面，$\tg \frac{\hat{B}}{2} = \frac{|AD|}{|BD|} = \frac{b}{2h}$，从这里开始
$$b = 2h \text{ tg} \frac{\hat{B}}{2} \text{ и } R = \frac{h \text{ tg} \frac{\hat{B}}{2}}{\sin \hat{B}} = \frac{h}{2 \cos^2 \frac{\hat{B}}{2}} = \frac{(h-r)^2}{2(h-2r)}$$
答案：$\frac{(h-r)^2}{2(h-2r)}$。

3. 三角形$ABC$顶点$A$和$C$处的角度分别为$\pi/4$和$\pi/6$。求该三角形的高度 $BD$ 与中线 $BE$ 之间的角度。

解决方案。让我们表示 $|AB| = c$、$|AC| = b$、$DBE = \varphi$ (图 3)。然后$|AD| = c \cos \hat{A} = c \sqrt{2}/2$，$|DE| = |BD| \times \text{tg} \varphi = (c \sqrt{2} \text{ tg} \varphi)/2$。因此，$b/2 = |AE| = |AD| + |DE| = c \sqrt{2} \times (1 + \text{tg} \varphi)/2$。根据 $\triangle ABC$ 的正弦定理，我们得到 $\frac{c}{\sin \hat{C}} = \frac{b}{\sin \hat{B}}$，其中
$$\sin \hat{B} = \sin (\pi - \hat{A} - \hat{C}) = \sin (\hat{A} + \hat{C}) = \sin \frac{\pi}{6} \cos \frac{\pi}{4} + \cos \frac{\pi}{6} \sin \frac{\pi}{4} = \frac{\sqrt{2}}{4} \times (1 + \sqrt{3}).$$
从这里开始是
$$\frac{c}{1/2} = \frac{4c(1 + \text{tg} \varphi)}{1 + \sqrt{3}}, \text{tg} \varphi = \frac{\sqrt{3} - 1}{2}.$$
答案：$\arctg \frac{\sqrt{3} - 1}{2}$。

以下问题使用余弦定理。

4. 三角形$ABC$的平分线$AD$和$CF$分别与边$BC$和$AB$相交于点$D$和$F$。如果$|AC| = 6$、$|AF| = 2$、$|CD| = 3$，求线段$FD$的长度。

解决方案。让我们表示 $|BD| = x$，$|BF| = y$ (图 4)。让我们使用平分线的一个重要属性：平分线将三角形的边分成与相邻边的长度成比例的部分。因此，$|AB|/|AC| = x/3$、$|BC|/|AC| = y/2$或$(2+y)/6 = x/3$、$(x+3)/6 = y/2$，由此而来$x=9/5$、$y=8/5$、$|AB|=18/5$、$|BC|=24/5$。为了计算 $|DF|$，我们使用 $\triangle FBD$ 的余弦定理。

$$|DF|^2 = x^2 + y^2 - 2xy \cos \hat{B},$$
其中$\cos \hat{B}$又可以从对应关系$|AC|^2 = |AB|^2 + |BC|^2 - 2|AB| \cdot |BC| \cos \hat{B}$中找到。替换为

⟦folio 50⟧

给定边长$\triangle ABC$，我们得到$36 = \frac{18^2}{25} + \frac{24^2}{25} - \frac{2 \cdot 18 \cdot 24}{25} \times \cos \hat{B}$，从中得到$\cos \hat{B} = 0$、$\hat{B} = \pi/2$、$|DF| = \sqrt{145}/5$。

答案：$\sqrt{145}/5$。

5. 在三角形$ABC$中：$\hat{B} = \arccos \frac{7}{8}$、$|AC| = b$，从顶点$B$下降的高度等于另外两个高度之和。求三角形$ABC$的面积。

解决方案。令 $|AB| = x, |BC| = y$ (图 5)。然后根据余弦定理$b^2 = x^2 + y^2 - 2xy \cos \hat{B} = x^2 + y^2 - \frac{7}{4}xy$。

(3)

接下来是$h_b = \frac{2S}{b}$、$h_x = \frac{2S}{x}$、$h_y = \frac{2S}{y}$，其中$S$是$\triangle ABC$的面积，$h_b, h_x, h_y$是它的高度。由于根据问题的条件$h_b = h_x + h_y$，则$\frac{1}{b} = \frac{1}{x} + \frac{1}{y}$或$x + y = \frac{xy}{b}$，因此$x^2 + y^2 = \frac{(xy)^2}{b^2} - 2xy$。从这里和方程（3）我们得到$z = xy$的方程：

$$b^2 = \frac{z^2}{b^2} - 2z - \frac{\tau}{4}z,$$

从哪里$z = xy = 4b^2$。因此$S = \frac{xy \sin \hat{B}}{2} = \sqrt{15}/4 b^2$。

答案：$\frac{\sqrt{15}}{4} b^2$。

关于余弦定理的注释。利用余弦定理，很容易得到用三角形边长表示中线长度的公式。让我们用 $m_a$、$BDA = \varphi$ (图 6) 表示$|AB| = c$、$|AC| = b$、$|BC| = a$，中位数$AD$的长度。使用三角形 $ABD$ 和 $ADC$ 的余弦定理，我们得到：

$$a^2/4 + m_a^2 - am_a \cos \varphi = c^2,$$
$$a^2/4 + 2m_a^2 - am_a \cos (\pi - \varphi) = b^2.$$

将这些方程相加并使用 $\cos (\pi - \varphi) = -\cos \varphi$，我们找到 $a^2/2 + 2m_a^2 = c^2 + b^2$，从哪里

$$m_a = \frac{1}{2} \sqrt{2(b^2 + c^2) - a^2}.$$

6. 在三角形$ABC$中，相关关系$|BC|^2 + |AC|^2 = 5|AB|^2$的边很长。求麦地那 $AM$ 和 $BN$ 之间的角度。

解决方案。让我们表示 $|AB| = c$、$|BC| = a$、$|AC| = b$、$NOM = \varphi$、$AM| = m_a$、$BN| = m_b$ (图 7)。由于在交点处，中位数按 2:1 的比例划分，从顶点开始计算，则根据式（4）可得：

$$|OM| = \frac{m_a}{3} = \frac{1}{6} \sqrt{2(b^2 + c^2) - a^2},$$
$$ON = \frac{m_b}{3} = \frac{1}{6} \sqrt{2(a^2 + c^2) - b^2}.$$

图 10. 图 11. 图 12.
