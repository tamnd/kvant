---
id: 1990-11-girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625
issue: kvant_1990_11
year: 1990
number: "11"
title: 关于三角形和圆形的几个问题
authors:
  - Гирич А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 50
page_labels: 46-48
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 38f0afd1bd1800a694f42d71fb50834319d4626c5e59bea90ea6de981fca1108
prompt_sha256: draft-1
translated_from: content/ru/1990/11/articles/19_girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625.md
source_content_sha256: 509fc0644c2cc0ba3f045a7205984706d65bf443ee9820e8db0e22a46f00eb73
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 46⟧

---
running_head:
folio:
---

关于三角形和圆形的几个问题

A·吉里奇

在本文中，我们将讨论与三角形两侧相切的圆以及围绕该三角形的外接圆。我们将这样的圆圈称为半写圆圈。我们将发现半写圆的许多有趣的属性。

像往常一样，我们将三角形$ABC$与顶点$A, B$和$C$相对的长边分别表示为$a, b$和$c$，这些顶点的角度为$\alpha, \beta$和$\gamma$，内切圆和外接圆的半径分别为$r$和$R$，三角形面积 - $S$，其半周长 - $p$。

在开始研究半写圆之前，我们先解决一下下面的辅助问题。

问题1. 用外接圆半径$r$和角度$\alpha, \beta, \gamma$来表示外接圆半径$R$。

解决方案。三角形面积有两个已知公式

$$S = \frac{abc}{4R} = rp. \tag{1}$$

由正弦定理$a = 2R \sin \alpha, b = 2R \sin \beta, c = 2R \sin \gamma$。将这些表达式代入(1)，我们得到

$$2R^2 \sin \alpha \sin \beta \sin \gamma = Rr(\sin \alpha + \sin \beta + \sin \gamma),$$

但是$\alpha + \beta + \gamma = \pi$和$\sin \gamma = \sin(\alpha + \beta)$。波佐托穆

$$\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}.$$

所以，$2R \sin \alpha \sin \beta \sin \gamma = 4r \cos \frac{\alpha}{2} \times \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$，从这里我们很容易得到

$$r = 4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}.$$

问题2.证明三角形$ABC$的边$AB$和$AC$相切的半圆半径等于$r/\cos^2 \frac{\alpha}{2}$。

证明。设$r_1$为半径，$I_1$为半圆圆心，$O$为三角形$ABC$（图1）的外接圆中心。然后$OI_1 = R - r_1$、$AI_1 = r_1/\sin \frac{\alpha}{2}$、$OA = R$、$\cos \angle OAI_1 = \cos \frac{(\beta - \gamma)}{2}$（确保这一点）。

对三角形$OAI_1$应用余弦定理，变换后得到

$$r_1 \cos^2 \frac{\alpha}{2} = 2R(\cos \frac{\beta - \gamma}{2} - \sin \frac{\alpha}{2}) \sin \frac{\alpha}{2}. \tag{2}$$

⟦folio 47⟧

---
running_head:
folio:
---

$$\cos \left( \frac{\beta - \gamma}{2} \right) - \sin \frac{\alpha}{2} = \cos \frac{\beta - \gamma}{2} - \cos \frac{\beta + \gamma}{2} = 2 \sin \frac{\beta}{2} \sin \frac{\gamma}{2},$$
等式(2)的右边等于$4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2} = r$。

所以，$r_1 = r / \cos^2 \frac{\alpha}{2}$。

问题3.证明线段$B_1C_1$的中点$I$，其中$B_1$和$C_1$是边为$AB$和$AC$的半圆的切点（见图1），是三角形$ABC$的内切圆的圆心。

证明。显然，三角形$AB_1C_1$是等边三角形，三角形$AIC_1$是矩形。波佐托穆
$$AI = AC_1 \cos \frac{\alpha}{2} = r_1 \text{ ctg} \frac{\alpha}{2} \cos \frac{\alpha}{2} = r / \sin \frac{\alpha}{2}.$$
但这意味着点$I$是内切圆的圆心。

问题 4. 直线 $B_1C_1$ 与三角形 $BIC$ 的外接圆相切。

证明。设$W$为角$A$的平分线与三角形$ABC$的外接圆的交点（图2。）然后$CW = WB$，$\angle CBW = \alpha/2$，所以$\angle IBW = (\alpha + \beta)/2$。另外，$\angle WIB = (\alpha + \beta)/2$（作为三角形$AIB$的外角）。因此，三角形$WIB$是等边三角形。因此，$CW = WI = WB$，即$W$，是三角形$CIB$的外接圆的圆心。问题的陈述源自先前证明的$AI$和$B_1C_1$的特殊性。

现在让我们通过顶点 $B$ 和 $C$ 绘制半圆的切线。令 $K$ 为它们的交点，$M$ 和 $N$ 为对应的切点 (图 3)。

问题 5. 证明直线 $B_1M, C_1N, BC$ 和 $AK$ 相交于一点。

证明。令 $T$ 为线段 $B_1M$ 和 $BC$ 的交点（参见 图 3）。从三角形 $B_1TC$ 和 $BMT$ 我们得到（通过正弦定理）
$$\frac{CT}{\sin \angle CB_1T} = \frac{CB_1}{\sin \angle B_1TC},$$
$$\frac{BT}{\sin \angle BMT} = \frac{BM}{\sin \angle BTM},$$
但是$\angle B_1TC = \angle BTM$和$\angle BMT + \angle CB_1T = \pi$（$\angle CB_1M = \angle B_1MK$，因为$AC$和$KB$与同一个圆相切）。波佐托穆
$$\frac{CT}{BT} = \frac{CB_1}{BM} = \frac{CB_1}{C_1B}.$$

⟦folio 48⟧

---
running_head:
folio:
---

$\angle BC_1V_1 + \angle CB_1V_1 = 180^\circ$。因此，$\frac{BV_1}{CV_1} = \frac{BC_1}{CB_1}$。同样，我们得到（假设$V_2$是$MN$与$BC$的交点）：$\frac{BV_2}{CV_2} = \frac{BM}{CN}$，但$BM = BC_1$、$CN = CB_1$。所以，$\frac{BV_1}{CV_1} = \frac{BV_2}{CV_2}$，因此$V_1 = V_2$。

问题7. 证明直线$BB_1$、$CC_1$ 和$AK$ 相交于一点（参见图 3）。

证明。自 $B_1A = AC_1$ 以及之前建立的$\frac{BT}{CT} = \frac{BC_1}{CB_1}$ 开始，我们得到

$$\frac{BT}{CT} \cdot \frac{CB_1}{B_1A} \cdot \frac{AC_1}{C_1B} = 1.$$

剩下的还是用Ceva定理（关于Ceva定理，参见B. Erdriev和N. Matsaev 1990年«Kvant»第3期的文章）。

总之，我们提供了一系列独立解决方案的任务。

练习

1. 现在让 $A_1, A_2, B_2, C_2$ 为三角形边上另外两个（与距离不同）半圆的切点。证明直线$B_1C_1$和$BC, B_2A_2$以及$AB, A_1C_2$和$AC$的交点位于同一条直线上。

2. 令 $K_1, K_2, K_3$ 为通过三角形顶点绘制到三个半圆中每一个的切线的交点。证明直线 $AK_1, BK_2$ 和 $CK_3$ 相交于一点。

3. 设$D$为线$BB_2$和$CC_2$的交点。证明$D$属于通过顶点$A$绘制的三角形$ABC$的中线。

4. 令$P_1, P_2, P_3$为半圆与外接圆的切点。证明直线 $AP_1, BP_2$ 和 $CP_3$ 相交于一点。
