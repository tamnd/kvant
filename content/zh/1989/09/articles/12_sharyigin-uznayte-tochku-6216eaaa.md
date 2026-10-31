---
id: 1989-9-sharyigin-uznayte-tochku-6216eaaa
issue: kvant_1989_9
year: 1989
number: "9"
title: 找出要点
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 58
page_labels: 52, 53, 54, 56
tag: 1WXZ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 28935d2a626fb9387cdeae33c21f83bde5e41120110f68b675c7d0b2eebc4de4
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/12_sharyigin-uznayte-tochku-6216eaaa.md
source_content_sha256: e3658872218046810b99ed6c502ae78aaf8436bc1a9a7db0ef72b73dfa190c02
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

找出要点

I.F.沙里金

在几何中，明确描述它们或与完全定义的图形类别相关的图形属性非常重要 - 所谓的“特征”。例如，您熟悉平行四边形的许多符号，并且可以在对边相等或对角线被交点平分的四边形中轻松识别它。平行四边形还有其他更“狡猾”的符号。例如，众所周知，在平行四边形中，对角线的平方和等于边的平方和。事实证明，相反的说法也是成立的：如果在一个四边形中，边的平方和等于对角线的平方和，那么这个四边形是平行四边形。

练习 1. 自己证明一下。 （说明：从直接定理，得到一个用其边的平方表示三角形中线的平方的公式。利用该公式，用其边和对角线的平方表示四边形对角线中点之间距离的平方。）

在这篇文章中，我们将讨论一些“点的迹象”。在学校课程中，研究了三角形的几个“值得注意”的点。这些点有许多有趣的属性，其中大多数独特地定义了这一点。然而，我们常常很难“识别”一个点，即使它的众所周知的属性已经被指出。

中线的交点（中心）

“显着”点的属性的一些特征可能是

⟦folio 53⟧

不仅用来“认识”它，还用来证明它的存在。

许多小学生都知道三角形的中线相交于一点，尽管并不是每个人都知道如何证明这一点。另一方面，不难证明，任意三角形ABC内部都有一个点M，使得三角形ABM、BCM和CAM大小相等（图1）。

最好的办法就是简单地建立这一点。由于三角形ABM的面积是三角形ABC面积的1/3，所以点M位于与AB平行且距AB的距离等于对应高度的1/3的直线上。类似地，M必须位于与BC平行的相似直线上，即M是这两条线的交点。由于三角形ABM和BCM的面积是三角形ABC面积的1/3，所以三角形CAM的面积也是ABC面积的1/3。

现在我们将证明给定三角形的所有中线都经过 M 点，并从三角形的顶点开始按 2:1 的比例划分。事实上，根据三角形ABM和BCM的点大小相等，可以得出A点和C点等于线BM，这意味着这条线必须经过线段BC的中间（这条线不能与BC平行）。并且根据三角形CAM的面积是面积ABC的1/3，可以得出M到CA的距离第二小于B到CA的距离，这意味着M以BM:B₁M=2的比例划分麦地那BB₁。因此，三角形的中线相交于一点，并将其按指定的比例分开。所以，我们得到了 Centrador 标志：

标记 M₁。当且仅当三角形 ABM、BCM 和 CAM 大小相等时，三角形 ABC 的内点 M 才是圆心。

让我们证明 Centrador 的另外两个标准。

为了使 M 点成为三角形 ABC 的中心，下列条件是充分必要的：

M2 标志。 MA+MB+MC=0。
标志M₃。 MA²+MB²+MC²=1/3 (AB²+BC²+CA²)。

证明。让我们从 M2 开始。设 M 为三角形 ABC (图 2) 中线的交点。

我们有 MA+MB+MC=MA+(MA₁+A₁B)+(MA₁+A₁C)=(MA+2MA₁)+(A₁B+A₁C)=0。反之，令M点满足M2准则，A1为MA与BC的交点。 （证明直线MA不能与BC平行）。那么，如上所述，我们将有 MA+MB+MC=(MA+2MA₁)+(A₁B+A₁C)=0。但是，如果每个向量都等于零，则写在括号中的两个非剪贴向量的总和只能等于零。因此，A₁是BC的中点。

图 1.

图 2.

⟦folio 54⟧

现在让我们证明特征$M_3$等价于特征$M_2$。令 $M$ 为平面上的任意点。首先，我们注意到，根据等式$\overrightarrow{MA} - \overrightarrow{MB} = \overrightarrow{BA}$，对其进行平方后，我们得到$2\overrightarrow{MA} \cdot \overrightarrow{MB} = MA^2 + MB^2 - AB^2$。

类似的等式也适用于 $2\overrightarrow{MB} \cdot \overrightarrow{MC}$ 和 $2\overrightarrow{MC} \cdot \overrightarrow{MA}$。接下来，$0 \leqslant (\overrightarrow{MA} + \overrightarrow{MB} + \overrightarrow{MC})^2 = MA^2 + MB^2 + MC^2 + 2\overrightarrow{MA} \cdot \overrightarrow{MB} + 2\overrightarrow{MB} \cdot \overrightarrow{MC} + 2\overrightarrow{MC} \cdot \overrightarrow{MA} = 3(MA^2 + MB^2 + MC^2) - (AB^2 + BC^2 + CA^2)$。因此，等式 2 意味着等式 3，反之亦然。一路上，我们证明了如果$M$是质心（这也是质心的标志），则$MA^2 + MB^2 + MC^2$达到最小值。

作为说明，让我们解决以下问题。

问题 1. 在三角形外侧的边上构建正方形。证明三角形中线与正方形中心顶点的交点与给定三角形中线的交点重合。

解决方案。令$M$为三角形$ABC$中线的交点，$A_1$为$BC$的中点，$A_2$为$BC$（图3）上构建的正方形的中心。

然后$\overrightarrow{MA} = \overrightarrow{MA_1} + \overrightarrow{A_1A_2}$。我们有$\overrightarrow{MA_2} + \overrightarrow{MB_2} + \overrightarrow{MC_2} = (\overrightarrow{MA_1} + \overrightarrow{MB_1} + \overrightarrow{MC_1}) + (A_1A_2 + B_1B_2 + C_1C_2)$。但每个括号中的向量之和为零。在第一个 - 根据符号 $M_2$。在第二个中，因为这个和的每个向量都是分别从$\frac{1}{2}\overrightarrow{BC}$，$\frac{1}{2}\overrightarrow{CA}$和$\frac{1}{2}\overrightarrow{AB}$通过顺时针旋转$90^\circ$得到的。这意味着$M$是三角形$A_2B_2C_2$的质心。

圆心

这次我们不会扩展学派理论，而是看两个例子。

问题 2. 在三角形 $ABC$ 中，已知以下角度：$\angle A = 30^\circ$、$\angle B = 80^\circ$。

在三角形内部，取一点$K$，使得$BCK$是正三角形。找到$\angle KAC$。

解决方案。这项任务是在 1989 年莫斯科奥林匹克运动会上 10 年级提出的。奥林匹克竞赛中的大多数参赛者试图通过使用正弦定理“计数”来解决这个问题，却没有看到点$K$是$ABC$外接圆的圆心。事实上，从围绕 $ABC$ 外接的圆的中心，可以以$2\cdot 30^\circ = 60^\circ$ 角度看到边 $BC$，该圆心位于三角形内部（该三角形是锐角），并且位于$BC$ 的垂直平分线上。所以，$K$是外接圆（图4）、$\angle CKA = 2\cdot 80^\circ = 160^\circ$、$\angle KAC = \angle KCA = 10^\circ$的圆心。

问题 3. 在凸四边形 $ABCD$ 中，已知以下角度：$\angle BAC = 25^\circ$、$\angle BCA = 20^\circ$、$\angle BDC = 50^\circ$、$\angle BDA = 40^\circ$。求这个四边形对角线之间的角度。

解决方案。可以间接证明点$D$是$ABC$的外接圆的圆心。由于三角形 $ABC$ 是钝角三角形，因此外接圆的中心位于 $AC$ 顶点 $A$ 的另一侧，从该中心开始，分别以角度 $50^\circ$ 和 $40^\circ$ 可见边 $BC$ 和 $BA$。另外，这样的点只有一个（请确保这一点）。

⟦folio 56⟧

交芽高度（重心）

三角形的高相交于一点的定理有许多不同的证明。我们将根据一个一般概念给出证明，您已经从三角形的二等分线及其垂线的中点相交于一点的定理证明中熟悉了这一概念。

为方便起见，请考虑锐角三角形 ABC。请注意，对于高度 AA1 的所有点，构造到边 AB 和 AC 的距离之比等于 $\frac{\cos B}{\cos C}$。 （直线AA1为点的轨迹，其与直线AB、AC的距离之比等于$\frac{\cos B}{\cos C}$。）其他两个高度也是如此。让我们用 $H$ 表示 AA1 和 BB1 高度的交点 (图 7)。知道$H$到AB和$AC$（$\frac{\cos B}{\cos C}$）的距离比以及$H$到BA和$BC$（$\frac{\cos A}{\cos C}$）的距离比，我们发现$H$到CA和CB的距离比为$\frac{\cos A}{\cos B}$，因此$H$属于第三个高度。

钝角三角形的情况与距离有关，因为（参见图7）对于三角形ABH，点C是顶点A和B省略的高度的交点。

在解决问题时，经常使用以下内容。

属性$H_1$。通过三角形两个顶点及其高交点的圆的半径等于三角形外接圆的半径。

有时，稍微不同地表述属性 $H_1$ 会更方便。

属性$H'_1$。通过三角形两个顶点和高交点的圆相对于三角形的对应边与三角形的外接圆对称。

练习 4. 证明命题 $H_1$ 和 $H'_1$。

结论是——一个简单的定理。

问题 4. 平面上有三个相等的圆，
