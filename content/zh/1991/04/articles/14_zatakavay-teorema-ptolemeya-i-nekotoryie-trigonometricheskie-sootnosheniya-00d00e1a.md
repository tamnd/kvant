---
id: 1991-4-zatakavay-teorema-ptolemeya-i-nekotoryie-trigonometricheskie-sootnosheniya-00d00e1a
issue: kvant_1991_4
year: 1991
number: "4"
title: 托勒密定理和一些三角关系
authors:
  - Затакавай В. В.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 11798b7e063f9841dd49e644de8f05ad82d88adaae6aeed50f94f50d68630eee
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/14_zatakavay-teorema-ptolemeya-i-nekotoryie-trigonometricheskie-sootnosheniya-00d00e1a.md
source_content_sha256: 7f8a1c4843652889520dc770ab5a40bae74e2b8328b730332ea316977de426e1
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

数学9-11
发表的笔记是写给九年级学生的。

托勒密定理
还有一些
三角函数
遵守

大约2000年前，当
进行天文观测
古希腊人德尼亚注意到
弦的长度取决于尺寸
对应的弧。生产
测量不同的弦长
中心角并计算相对值
古代的长度与半径之比
河流科学家托勒密编制
这些关系的表。原来是
第一个三角函数之一
0° 到 90° 角度的满足正弦表。

托勒密计算了沿着弦的附加弧（最多 180°）的弦
给定弧 (图 1)，应用理论-
毕达哥拉斯的述说。从现代的角度来看
的观点，就好像
他使用了公式$\sin^2\alpha + \cos^2\alpha = 1$，因为$AC = 2R \sin \alpha$、$BC = 2R \sin \beta = 2R \sin \left(\frac{\pi}{2} - \alpha\right) = 2R \cos \alpha$和$AB = 2R$。于是他整理了表格
0° 到 90° 角度的双余弦。

托勒密还能够从附加弧的弦（即从 2 cos $\alpha$）找到半弧的弦 ($t. e. 2 \sin \frac{\alpha}{2}$)。他的推理构建——
得出结论 $OD = \frac{1}{2} BC$ (OD -
中线$\triangle ABC$），然后$OD = R \cos \alpha$，因此$MD = R - R \cos \alpha$。反过来，$AM =$

⟦folio 43⟧

---
running_head:
folio:
---

$= 2R \sin \frac{\alpha}{2}$。利用直角三角形中的度量关系，我们得到$AM^2 = MD \cdot MK$。考虑到$MK = 2R$，我们得到$4R^2 \sin^2 \frac{\alpha}{2} = (R - R \cos \alpha) \cdot 2R$，或者
$$\sin^2 \frac{\alpha}{2} = \frac{1 - \cos \alpha}{2}.$$
现在我们把这个公式称为多边形度公式。
波托勒毛的另一伟大成就是他证明了一个几何定理，现在称为波托勒毛定理。
定理。内接四边形的对角线乘积等于其对边乘积之和 (图 2)。
证明。让我们在对角线 $AC$ 上取一点 $M$ 使得$\angle ABM = \angle CBD$。由于$\angle CDB = \angle MAB$是内接三角形，因此$BCD$和$ABM$相似。因此$\frac{BD}{AB} = \frac{CD}{AM}$，即
$$AB \cdot CD = AM \cdot BD.$$ (*)
根据构造 $\angle ABD = \angle MBC$ 以及内接 $\angle BCM = \angle ADB$ 的事实，可以得出 $\triangle ABD \sim \triangle MBC$。所以，$\frac{AD}{CM} = \frac{BD}{BC}$ 或
$$AD \cdot BC = BD \cdot CM.$$ (**)
逐项添加等式 (*) 和 (**)，我们得到
$$AB \cdot CD + AD \cdot BC = BD(AM + CM) = BD \cdot AC,$$
Q.E.D.

利用波托勒毛定理，我们可以推导出一些三角公式。
让我们将四边形 $ABCD$ 内接于一个圆，使其其中一条边就是该圆的直径 (图 3)。
让$\angle AOC = 2\alpha$，$\angle AOD = 2\beta$，然后$AC = 2R \sin \alpha$，$AD = 2R \sin \beta$，$BC = 2R \cos \alpha$，$BD = 2R \cos \beta$，$CD = 2R \sin (\alpha - \beta)$。
使用波托勒毛定理并学习 $AB = 2R$，我们得到
$$2R \cdot 2R \sin (\alpha - \beta) + 2R \cos \alpha \cdot 2R \sin \beta = 2R \sin \alpha \cdot 2R \cos \beta,$$
或者
$$\sin (\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta.$$
自己推导出$\sin (\alpha + \beta)$的计算公式。 （提示：在圆内接一个四边形，使其对角线为直径。）
所以，我们有两个重要的三角公式：
$$\sin (\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta,$$
$$\sin (\alpha + \beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta.$$
让我们把它们叠起来。我们得到
$$\sin (\alpha - \beta) + \sin (\alpha + \beta) = 2 \sin \alpha \cos \beta,$$
或者
$$\sin \alpha \cos \beta = \frac{1}{2} (\sin (\alpha - \beta) + \sin (\alpha + \beta)).$$ (1)
通过两个角度的和（或差）的余弦公式的加减，我们可以得到另外两个公式：
