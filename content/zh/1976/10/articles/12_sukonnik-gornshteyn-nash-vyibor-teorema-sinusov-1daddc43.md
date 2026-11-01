---
id: 1976-10-sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43
issue: kvant_1976_10
year: 1976
number: "10"
title: 我们的选择是正弦定理！
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: 7Q2O
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1765c630b48e314335c49f913f20fcd5dadc77b28ba958150ca69bf4d061e28c
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/12_sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43.md
source_content_sha256: b0de61526fe5130fa1f947a1f83887daf433f2981ee2244bdf727787e49ad2f1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

我们的选择是正弦定理！

在任何三角形 $ABC$ 中，边 $|BC| = a, |CA| = b, |AB| = c$ 和角 $\widehat{CAB} = \widehat{A}, \widehat{ABC} = \widehat{B}, \widehat{BCA} = \widehat{C}$ 通过以下重要关系相关。

余弦定理*)。任意边的平方等于三角形平面平方的另一边的平方减去这些边与它们之间的角度的余弦的二积，即
$$a^2 = b^2 + c^2 - 2bc \cos \widehat{A},$$
$$b^2 = c^2 + a^2 - 2ca \cos \widehat{B},$$
$$c^2 = a^2 + b^2 - 2ab \cos \widehat{C}.$$
正弦定理。任意一条边等于外接圆直径与邻角正弦的乘积，即
$$a = 2R \sin \widehat{A}, b = 2R \sin \widehat{B},$$
$$c = 2R \sin \widehat{C},$$
或者，以更常见的形式，
$$\frac{a}{\sin \widehat{A}} = \frac{b}{\sin \widehat{B}} = \frac{c}{\sin \widehat{C}} = 2R.$$
但是，如果要求您仅使用这两个定理中的一个并丢弃另一个，您会保留哪一个？从正弦定理可以推导出余弦定理，从余弦定理可以推导出正弦定理（尽管没有比例系数 $2R$ - 正如学校教科书中那样）。但定理

*) 关于余弦定理，请参阅 E. G. Gotman 的文章“余弦定理及其后果”（«Kvant»，1972 年，第 7 期）。

⟦folio 47⟧

因此，

$$|AB| \cdot |CD| + |BC| \cdot |DA| = 4R^2 \left| \sin(\hat{A} + \hat{B} - \alpha) \cdot \sin(\alpha) + \sin(\hat{A} - \alpha) \cdot \sin(\hat{B} - \alpha) \right| = 2R^2 \left| \cos(\hat{A} + \hat{B} - 2\alpha) - \cos(\hat{A} + \hat{B} - 2\alpha) \right| = 4R^2 \sin \hat{A} \sin \hat{B} = (2R \sin \hat{A}) \cdot (2R \sin \hat{B}) = |BD| \cdot |AC|.$$

正弦定理最自然的应用出现在问题涉及三角形的边、对角和外接圆半径的情况下。

问题 2（密歇根州立大学，机制，1961 年）。给定一个三角形，其底角为$\alpha$，顶角为$\alpha$。通过内切三角形的中心和底边的两端构建一个圆。求它的半径。

令 $O$ (图 2) 为内切圆的圆心。然后

$$\widehat{BOC} = 180^\circ - \widehat{OBC} - \widehat{OCB} = 180^\circ - \frac{\hat{B}}{2} - \frac{\hat{C}}{2} = 90^\circ + \frac{\alpha}{2}.$$

由于三角形 $BOC$ 内接于原圆，利用正弦定理我们可以求出这个圆：

$$R = \frac{|BC|}{2 \sin \widehat{BOC}} =$$

图 1.

图 2.

图 3.

问题 3（密歇根州立大学，物理学，1962 年；乌拉尔国立大学，物理学，1973 年）。在等腰三角形中，底角为$\alpha$。降低到底座的高度比悬挂陡坡的半径大$m$。确定三角形的底边和主圆的半径。

再次令 $O$ 为内切圆 (图 3) 的中心。然后

$$|AO| = |AD| - |OD| = h_a - r = m,$$

$$\widehat{AOC} = 90^\circ + \frac{\alpha}{2}, \quad \widehat{ACO} = \frac{\alpha}{2}.$$

因此，应用正弦定理两次（对于三角形$ABC$和$AOC$），我们得到

$$|BC| = |AC| \cdot \frac{\sin \hat{A}}{\sin \hat{B}} =$$

$$= |AO| \frac{\sin \widehat{AOC}}{\sin \widehat{ACO}} \cdot \frac{\sin \hat{A}}{\sin \hat{B}} = 2m \cos \alpha \cdot \text{ctg} \frac{\alpha}{2},$$

$$R = \frac{|AC|}{2 \sin \hat{B}} = \frac{|AO| \sin \widehat{AOC}}{2 \sin \widehat{ACO} \cdot \sin \hat{B}} = \frac{m \sin \left(90^\circ + \frac{\alpha}{2}\right)}{2 \sin \frac{\alpha}{2} \cdot \sin \alpha} = \frac{m}{4 \sin^2 \frac{\alpha}{2}}.$$

问题4. 在陡坡附近描述一个四边形$ABCD$，其对角线

⟦folio 48⟧

圆环相交于点 E。三角形 AEB、BEC 和 CED 外接圆的半径分别等于 $R_1$、$R_2$ 和 $R_3$。
求三角形 AED 的外接圆的半径 R。

四边形 ABCD (图 4) 与圆外接，所以等式成立
$$|AB| + |CD| = |BC| + |AD|.$$
除了，

$$\sin \widehat{AEB} = \sin \widehat{BEC} =$$
$$= \sin \widehat{CED} = \sin \widehat{DEA}.$$
然后
$$\frac{|AB|}{\sin \widehat{AEB}} + \frac{|CD|}{\sin \widehat{CED}} =$$
$$= \frac{|BC|}{\sin \widehat{BEC}} + \frac{|AD|}{\sin \widehat{DEA}}.$$

现在，根据正弦定理，我们得到 $R_1 + R_3 = R_2 + R$，由此而来
$$R = R_1 - R_2 + R_3.$$

有时，在解决问题时，有必要从给定的已知边或线段比率转移到三角形角度之间的相应比率。使用正弦定理可以最方便地实现这一点。

问题 5（列宁格勒国立大学化学系，1973 年）。在等边三角形ABC($|AB| = |BC|$)中，画出中线AD。如果顶点 B 处的角度为 α，则求角 BAD。

从三角形 ABD (图 5)，其中$|AB| = 2|BD|$，可得出正弦定理

$$2 = \frac{|AB|}{|BD|} = \frac{\sin \widehat{ADB}}{\sin \widehat{BAD}} = \frac{\sin(\alpha + \widehat{BAD})}{\sin \widehat{BAD}} = \sin \alpha \cdot \text{ctg} \widehat{BAD} + \cos \alpha.$$

从这里
$$\widehat{BAD} = \arctg \frac{2 - \cos \alpha}{\sin \alpha}.$$

问题6. 给定正三角形内接第二个正三角形，它们的面积之比为3。证明内接三角形的边与给定三角形的对应边垂直。

很容易证明（证明！）$|AF|$等于$|BD|$（图6）。现在根据正弦定理三角形 ABC 和 DEF 的相似性我们有

$$\sqrt{3} = \sqrt{\frac{S_{\triangle ABC}}{S_{\triangle DEF}}} = \frac{|AB|}{|DF|} =$$
$$= \frac{|AF| + |FB|}{|DF|} = \frac{|BD|}{|DF|} + \frac{|FB|}{|DF|} = \frac{\sin \widehat{BFD}}{\sin \widehat{DBF}} + \frac{\sin \widehat{BDF}}{\sin \widehat{DBF}} = \frac{\sin(120^\circ - \widehat{BDF}) + \sin \widehat{BDF}}{\sin 60^\circ} = 2 \cos(60^\circ - \widehat{BDF})$$
$$\cos(60^\circ - \widehat{BDF}) = \frac{\sqrt{3}}{2}, \widehat{BDF} = 90^\circ$$
（然后$|FD| \perp |BC|$）或$\widehat{BDF} = 30^\circ$。 （然后$|FD| \perp |AB|$）。

⟦folio 49⟧

任务 7（密歇根州立大学，力学和数学，1972 年）。在三角形ABC中，uelol C是tunoy； bissertis BE uela B 我们将 AC 边分成长度为 3 m 和 2 m 的段 AE 和 EC。已知点K位于边BC在顶点C之外的延长线上，是经过点C、E以及小点B与小点ACK的交点的圆心。求E点到AB边的距离。

显然，如果已知sin $\hat{A}$，则可以找到所需的距离EH (图 7)。但首先，让我们找出三角形 ABC 的角度之间的关系。令D为二角B和ACK的交点。我们先画弦 EF，然后画 $\hat{EDC} = \hat{EFC}$，但是

$$\hat{EDC} = \hat{DCF} - \hat{DBC} = \frac{1}{2} \hat{ACF} - \frac{\hat{B}}{2} = \frac{(180^\circ - \hat{C}) - \hat{B}}{2} = \frac{\hat{A}}{2},$$

$$\hat{EFC} = 90^\circ - \hat{ECF} = 90^\circ - (180^\circ - \hat{C}) = \hat{C} - 90^\circ,$$

姿势

$$\frac{\hat{A}}{2} = \hat{C} - 90^\circ, \hat{C} = 90^\circ + \frac{\hat{A}}{2}.$$

根据正弦定理和 bissertis 性质，从三角形 ABC 我们有

$$\frac{2}{3} = \frac{|EC|}{|AE|} = \frac{|BC|}{|AB|} = \frac{\sin A}{\sin \hat{C}} = \frac{\sin \hat{A}}{\sin \left(90^\circ + \frac{\hat{A}}{2}\right)} = 2 \sin \frac{\hat{A}}{2},$$

$$\sin \frac{\hat{A}}{2} = \frac{1}{3}, \sin \hat{A} = \frac{4\sqrt{2}}{9},$$

$$|EH| = |AE| \cdot \sin \hat{A} = \frac{4\sqrt{2}}{3}.$$

有时，多个段比率的乘积会出现问题。在这里，正弦定理的应用得出了一个简单的解决方案。

任务 8（密歇根州立大学经济学院，1975 年）。给定一个三角形 ABC，其中 $|AB| = |AC|$ 和 $\hat{A} = 80^\circ$。在三角形ABC内取点M，表示$\hat{MBC} = 30^\circ$和$\hat{MCB} = 10^\circ$。找到 uelol AMC。

让我们用 x (图 8) 表示所需的角度 $\hat{AMC}$。很明显

$$\hat{ABM} = 20^\circ, \hat{ACM} = 40^\circ, \hat{CMB} = 140^\circ,$$

然后$\hat{AMB} = 220^\circ - x$。根据三角形AMB和AMC的正弦条件和定理

图 7. 图 8. 图 9.

⟦folio 50⟧

我们有

$$1 = \frac{|AB|}{|AC|} = \frac{|AB|}{|AM|} \cdot \frac{|AM|}{|AC|} = \frac{\sin(220^\circ - x)}{\sin 20^\circ} \cdot \frac{\sin 40^\circ}{\sin x} = \frac{2 \sin(x - 40^\circ) \cos 20^\circ}{\sin x} = \frac{\sin(x - 20^\circ) + \sin(x - 60^\circ)}{\sin x},$$

$$\sin x - \sin(x - 60^\circ) = \sin(x - 20^\circ),$$
$$2 \sin 30^\circ \cdot \cos(x - 30^\circ) = \sin(x - 20^\circ),$$
$$\cos(x - 30^\circ) = \cos(110^\circ - x),$$
$$x = \widehat{AMC} = 70^\circ.$$

问题 9. 在凸链 ABCD 中，给出以下井：
$$\widehat{BAC} = 15^\circ, \widehat{CBD} = 90^\circ, \widehat{DCA} = 30^\circ,$$
$$\widehat{ADB} = 75^\circ.$$ 说出双重氮之间的井的名称。

让我们用 $x$ (图 9) 表示 $\widehat{AED}$。

然后$\widehat{ABE} = x - 15^\circ, \widehat{BCE} = 90^\circ - x,$
$\widehat{CDE} = x - 30^\circ, \widehat{DAE} = 105^\circ - x,$ 以及三角形 $AEB, BEC, CED$ 和 $DEA$ 由正弦定理我们有
$$\frac{|AE|}{|BE|} = \frac{\sin(x - 15^\circ)}{\sin 15^\circ}, \frac{|BE|}{|CE|} = \frac{\sin(90^\circ - x)}{\sin 90^\circ}, \frac{|CE|}{|DE|} = \frac{\sin(x - 30^\circ)}{\sin 30^\circ},$$
$$\frac{|DE|}{|AE|} = \frac{\sin(105^\circ - x)}{\sin 75^\circ}.$$

将写下的等式逐项相乘，减少相同的因子后，我们得到
$$\sin(x - 15^\circ) \cdot \sin(90^\circ - x) \times \sin(x - 30^\circ) \cdot \sin(105^\circ - x) = \sin 15^\circ \cdot \sin 90^\circ \cdot \sin 30^\circ \cdot \sin 75^\circ,$$
$$[2 \sin(x - 15^\circ) \cdot \sin(105^\circ - x)] \times [2 \sin(x - 30^\circ) \sin(90^\circ - x)] = 2 \sin 15^\circ \cdot \cos 15^\circ,$$
$$[\cos(2x - 120^\circ) - \cos 90^\circ] \times |\cos(2x - 120^\circ) - \cos 60^\circ| = \frac{1}{2},$$
$$2 \cos^2(2x - 120^\circ) - \cos(2x - 120^\circ) - 1 = 0,$$
由此，所需角度等于 $60^\circ$。

在右边
1（密歇根州立大学，VMK，1971 年）。在半径为$R$的圆中，有两个弦：$AB$和$AC$。在弦$AB$或其延长线上，取点$B$为点$M$，该点到直线$AC$的距离等于弦$AC$的长度。同样，在弦$AC$或其延长线上，点$C$取点$N$，该点到直线$AB$的距离等于弦$AB$的长度。求线段 $MN$ 的长度。

2（NSU，mexmat，1969）。证明在给定底角和给定顶角的所有三角形中，等边三角形的周长最大。

3（MIPT，1970）。在三角形中，顶角 $A$ 是角 $B$ 的三倍，边 $AB, BC, AC$（按此顺序）形成等差级数。求三角形 $ABC$ 的内角。

4（工业和信息化部，1972）。在直角三角形中，给定一个锐角$\alpha$，以及另一个锐角的顶点到内切圆圆心的距离$a$。确定三角形的面积。

5（密歇根州立大学地理学院，1969 年）。该线穿过等边三角形 $ABC$ 的顶点 $B$，并与底边 $AC$ 相交于点 $D$。据了解

$$\widehat{ABD} = \frac{1}{3} \widehat{ABC} \text{ и } |AD|:|DC| = 3:4.$$

锐角还是钝角$ABC$？
6（密歇根州立大学，生物学院，1968）。在圆形等边三角形$ABC$中，其中有$|AB| = |BC|$和$\widehat{ABC} = \alpha$。从顶点$A$绘制角$BAC$的平分线，与边$BC$相交于点$D$，与圆相交于点$E$。顶点 $B$ 通过线段连接到点 $E$。求三角形 $ABE$ 和 $BDE$ 的面积比。

7（密歇根州立大学地质学院，1975 年）。在菱形$ABCD$中，从边$(1 + \sqrt{5})$с和锐角$\widehat{BAD} = 60^\circ$有一个圆内切于三角形$ABD$。从点$C$到圆。在点 $E$ 处绘制一条与边 $AB$ 相交的切线。求线段 $AE$ 的长度。

8. 圆角四边形$ABCD$。通过对角线交点$E$，绘制线段$FH$（F 位于$AB$ 上，$H$ 位于$CD$ 上）。证明

$$\frac{|FE|}{|EH|} = \sqrt{\frac{|AF|}{|CH|} \cdot \frac{|BF|}{|DH|}}.$$
