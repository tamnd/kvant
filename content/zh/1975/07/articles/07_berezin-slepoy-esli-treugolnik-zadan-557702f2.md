---
id: 1975-7-berezin-slepoy-esli-treugolnik-zadan-557702f2
issue: kvant_1975_7
year: 1975
number: "7"
title: 如果给定一个三角形...
authors:
  - Березин В. Н.
  - Слепой В. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 41
page_labels: 36-39
tag: RQ87
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9900bf7994d010c65578617553324e30d0ed024541c14c44c9357492ba632122
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/07_berezin-slepoy-esli-treugolnik-zadan-557702f2.md
source_content_sha256: e4181b68623421e559c340ec0521596e3dcadfc5157041b8b3e3a96210c584c5
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

如果给定一个三角形...

V. N. Berezin、V. I. Slepoy

一般来说，在几何任务中，我们必须处理 30°、45°、60°……的角度；但也存在80°、40°甚至47°角度的问题！我们几乎正在谈论这样的问题。

本文讨论的所有问题都涉及位于同一平面的三角形以及通过线段连接到其顶点的点。已知被认为是直线之间的某些角度，或直线段之间的某些度量关系，或两者。要求确定某个未知的角度（在相应的图上用问号和红色蝴蝶结标记）。

注释中的主要符号是标准的，但有时辅助符号在解决问题时很有用。首先，用相同的（非黑色）颜色“着色”相等的部分，并用颜色突出显示平面上在解决问题时需要注意的那些部分。

让我们从最简单的任务开始。

任务 1. 给定一个等边三角形 ABC 和它外面的一个点 D，线段 BD 的长度等于边 $\Delta ABC$ 和 $\widehat{DBC}=40^\circ$（参见 图 1）。找到$\widehat{ADC}$。

很容易计算（自己计算）$\widehat{ADC}=30^\circ$。有趣的是，$\widehat{DBC}$可以是任何值（并且不一定等于40°）； $\widehat{ADC}$ 仍然等于 30°。

现在解决这个问题。

任务 2. 给定一个等边三角形 ABC（$|BC|=|CA|$，见图 2），其角 BAC 小于 60°，以及点 D，令线段 AD 与三角形的边 AC 所成的角等于 60° 角与角 BAC 之间的差（也许

图 1.
图 2.

⟦folio 37⟧

图 3.

线AC作为角DAE)的平分线，其中$|AD| = |AB|$。求$\widehat{ADC}$（结果又等于30°）。

第十五届莫斯科数学奥林匹克竞赛中提出了以下问题。

问题3. 从顶角为$\widehat{ABC} = 20^\circ$（图3）的等边三角形ABC 的顶点A 和C 出发，画两条直线，直到它们分别与三角形的对边相交于点D 和E，使得角CAD 等于60°，角ACE 等于50°。确定角度 ADE。

解决方案。从与三角形 ABC 全等的等边三角形，让我们形成一个正 18 边形 $ACC_1C_2 \dots C_{15}C_{16}$（参见 图 4），中心位于原始三角形的顶点 B。让我们画出这个 18 边形的对角线 $AC_8, AC_6, CC_9, CC_{12}, C_1C_{12}, C_1C_{16}, C_4C_{16}$。对角线$AC_6$和$C_1C_{12}$相对于对角线$CC_9$对称，并交于点D。同样，证明对角线$CC_{12}, C_4C_{16}$和$AC_8$相交于公共点E。现在注意到$[C_4C_{16}]$和$[BC_1]$是菱形$BC_4C_1C_{16}$的对角线；因此，线段$C_4C_{16}$垂直于线段$BC_1$并通过其中间；但由于 $\Delta BC_1D$ 是等边 ($\triangle DBC_1 \cong \triangle DC_1B$)，则 $C_4C_{16}$ 包含其高度，因此通过点 D。 现在已经清楚 $\widehat{ADE} = 30^\circ$ （它等于我们的正 18 边形内切圆的弧 $AC_{16}$ 和 $C_4C_6$ 的和的一半）。

顺便说一句，请注意角度 ECD 也等于 30°，并且三角形 AEC 是等边三角形 ($|AE| = |AC|$)。

⟦folio 38⟧

图 6.

现在让我们概括一下问题 3 的条件。
问题4. 在三角形ABC 的边AB 和BC 上取点E 和D 对应于马克，即$\widehat{ADE} = \widehat{ECD} = 30^\circ$。已知三角形 AEC 是等边三角形 ($|AE| = |AC|$; 图 5)。假设$\widehat{ABC} = \alpha$，求三角形ABC的剩余角。 $\alpha$ 角可能是多少？

解决方案。 图 5 告诉你如何根据问题的条件，从平面 A、E、D 上的给定点和 $\widehat{ADE} = 30^\circ$ 构造三角形 ABC。让我们继续线段 AC 和 EC，直到它们与三角形 AED 的外接圆相交于点

图 7.

分别为 G 和 F（在 图 5 处是一个以 $O_1$ 为圆心的圆）。

三角形ACF与三角形CEB相似($\widehat{AFC} = \widehat{EDA} = \widehat{ECB} = 30^\circ$;$\widehat{ACF} = 180^\circ - \widehat{GCF} = 180^\circ - \widehat{ACE} = 180^\circ - \widehat{AEC}$)；意思是$\widehat{FAC} = \alpha$。因此$\widehat{ACB} = \widehat{ACE} + 30^\circ = \alpha + 30^\circ + 30^\circ = \alpha + 60^\circ$，$\widehat{CAB} = 120^\circ - 2\alpha$。

现在，应用等式我们得到$\alpha < 60^\circ$。

现在 - 承诺的任务，其中发生 47° 角。

问题5. 在四边形BGEC中（BE和GC是它的对角线，见图6）$\widehat{EBC} = 30^\circ$，$\widehat{BCG} = 26^\circ$，$\widehat{GCE} = 51^\circ$，$\widehat{GEB} = 13^\circ$。该名称将由 BGC 完成。

解决方案。在这个四边形的BC和EC边上，我们将构造一个正三角形：$\triangle BAC$和$\triangle EFC$（在图7上，它们的轮廓由相应的红色和蓝色表示）。从E点在GE边上，我们绘制一条线段DE，使得$|DE| = |EC|$，并将点A与点D和E连接。我们得到一个正三角形ADE，等于三角形EFC（整个fi-

⟦folio 39⟧

群 BAEC 相对于 (BE)) 对称。

让我们将点 F 与点 B、点 D 与点 B 和 C 连接（参见 图 8）。三角形ADB等于三角形AEC（两条边和它们之间的角度）；由于 ΔAEC 是等角的，因此 ΔADB 也是等角的。三角形 ADB 和 BFC 相对于 (BE) 对称，因此也相等； $\widehat{BAD} = \widehat{BCF} = 17^\circ$。这意味着$\widehat{ADB} = 146^\circ$和$BDE = 360^\circ - \widehat{ADB} - 60^\circ = 154^\circ$，即$\widehat{BDC} = 180^\circ - \widehat{BDE} = 180^\circ - 154^\circ = 26^\circ = \widehat{BCG}$，因此可以围绕四边形BGDC画一个圆。该圆中的角BGC和角BDC基于同一圆弧，因此相等。

但$\widehat{BDC} = 154^\circ - \widehat{EDC}$，其中$\widehat{EDC}$是等边三角形DEC的底角，其顶角为86°；因此，$\widehat{EDC} = 47^\circ$和$\widehat{BDC} = \widehat{BGC} = 107^\circ$。

这个问题的情况也可以概括。

问题5'。在四边形BGEC中（BE和GC是它的对角线）

$$\widehat{EBC} = 30^\circ, \widehat{GCB} = \alpha, \widehat{GEB} = \frac{\alpha}{2},$$

$$\widehat{GCE} = 90^\circ - \frac{3}{2}\alpha.$$
