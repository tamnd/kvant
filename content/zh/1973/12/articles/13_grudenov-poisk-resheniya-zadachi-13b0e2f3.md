---
id: 1973-12-grudenov-poisk-resheniya-zadachi-13b0e2f3
issue: kvant_1973_12
year: 1973
number: "12"
title: 寻找问题的解决方案
authors:
  - Груденов Я. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 46
page_labels: 39-44
tag: 7A3E
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 17b6f5187cceb88314a0d843ae5c5a82f845ee64857acd611d406e9a53bab7c8
prompt_sha256: draft-1
translated_from: content/ru/1973/12/articles/13_grudenov-poisk-resheniya-zadachi-13b0e2f3.md
source_content_sha256: fd128d98918c60416eabd6edecb8b1638aee0db7eff172af7752cbda6ed4eded
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

寻找解决方案
任务
格鲁格霍夫

为了找到多任务的解决方案，采用了两侧交替运动的方法——从给定的任务到所需的任务，然后返回。首先，他们尝试从数据中获得一系列结果，然后是期望结果的陈述，然后再次返回数据，依此类推。

一般来说，从这些任务中你可以得到许多与其解决方案无关的结果。然而，大多数情况下，我们下意识地专注于那些与我们正在寻找的内容相关的内容，因为我们的注意力刚刚集中在它或它所遵循的陈述上。当从搜索到数据时，也会发生同样的事情。

建议在两侧进行交替运动，直到出现解决方案（一个或多个）的想法。有时候，它的出现似乎是出乎意料的。事实上，这是从数据中找出你想要的东西的艰苦工作的结果。这可以在图 (图 1) 中清楚地看到，其中让解通过语句 1、2、3 和 4。

让我们看一个例子。

问题1. 证明在直窗台中，直角的二等分角平分中线与画成相同角度的高度之间的角度。

我们研究条件。我们画一张图（图2），用数字表示一些角度。我们选择数据（$\angle ABC = 90^\circ$，$BO \perp AC$，$AM = MC$，$\angle ABK = \angle KBC$）和所需的数据（证明$\angle 2 = \angle 3$）。我们事先检查 图 2 上的元素排列是唯一可能的（平分线位于中线和高度之间）；使用围绕圆 $\Delta ABC$ 外接的弧 AC 的中点可以轻松证明这一点。

图 1. 图 2.

⟦folio 40⟧

我们去找我们的父亲吧。既然$\overrightarrow{ABK} = \overrightarrow{KBС}$，那么要证明$\overrightarrow{2} = \overrightarrow{3}$相等，证明$\overrightarrow{1} = \overrightarrow{4}$就足够了。为此，您可以将 $\overrightarrow{1}$ 和 $\overrightarrow{4}$ 的大小与其他角度进行比较。让我们看看 $\overrightarrow{A}$ 和 $\overrightarrow{1}$ 是否相等。如果$AM = MB$，这是可能的。

我们从数据中得到一个结果。由于$MB$是直角三角形$ABC$中斜边的中线，因此$MB = \frac{1}{2}AC$，即$MB = AM$，因此$\overrightarrow{A} = \overrightarrow{1}$。

让我们回到证明关系上来。由于$BO \perp AC$和$BC \perp AB$，那么$\overrightarrow{A} = \overrightarrow{4}$就像边相互垂直的锐角。因此$\overrightarrow{1} = \overrightarrow{4}$，这意味着$\overrightarrow{2} = \overrightarrow{3}$。

如果通过两侧交替运动无法解决问题，可以转向其他方法。例如，解决特定情况下的问题。记住是否遇到过类似的问题，这个问题是否可以简化为一个已知的、更简单的问题，如果只考虑部分数据，是否必须采用日本的解决方案。

任务 2. 计算

$$M = \sqrt{\frac{44 \cdot 4}{200} - \frac{88 \cdot 8}{100}}$$

我们研究条件a)。提取两个数之差的平方根很容易； 6）哪一个数字包含相同的数字； b) 八数减去四数的被减数； d) 被减数包含200位，减数包含100位； e) 被减数有两倍的数字。

无法计算此差异。让我们尝试将其纳入因素中。为此，我们首先考虑应用程序的一部分

措施，将其组合为仅执行部分数据：(a)、(6)、(c)、(e)（(d) 除外）。

1) $4444 - 88 = 4 \cdot 1111 - 8 \cdot 11 = 4 \cdot (1111 - 2 \cdot 11) = 4 \cdot (1100 + 11 - 11 - 11) = 4 \cdot (11 \cdot 100 - 11) = 4 \cdot 11 \cdot (100 - 1) = 4 \cdot 11 \cdot 99 = 4 \cdot (11)^2 \cdot 9$.

2) $4444 - 88 = (4400 + 44) - (44 + 44) = 44 \cdot 100 - 44 = 44 (100 - 1) = 44 \cdot 99 = 4 \cdot (11)^2 \cdot 9$.

这些方法中的任何一种都可以用来解决这个问题；选择第二个：

$$M = \sqrt{\frac{44 \cdot 4}{200} - \frac{44 \cdot 4}{100}} = \sqrt{\frac{44 \cdot 4}{100} \cdot (10^100 - 1)} = \sqrt{\frac{44 \cdot 4}{100} \cdot (10^100 - 1)} = \sqrt{\frac{44 \cdot 4}{100} \cdot (10^100 - 1)} = \frac{66 \cdot 6}{100}$$

在解决平面问题时，有时不用手绘制图形，而是使用工具绘制图形，这样会更准确。通过观察它，你可以摆脱一些误解，找到图形元素之间的真正关系。当然，这样得出的结论必须是有道理的。

任务3（诡辩，即故意犯错误的异化，必须被发现）。设四个尾巴分别为$K = 90^\circ$、$C > 90^\circ$、$BC = AK$。通过边$AB$和$CK$的中点，我们绘制它们的垂直线。我们将它们的交点$O$与四尾的所有顶点连接起来。从两两相等的直角三角形$KOM$和$MOC$、$AOP$和$BOP$我们有：

$$OK = OC, OA = OB; \quad OKM = \overrightarrow{OCM}.$$

既然$AK = BC, OA = OB$和$OK = OC$，那么$\Delta AOK = \Delta OBC$。因此$\overrightarrow{AKO} = \overrightarrow{BCO}$。

⟦folio 41⟧

逐元素绣项，由等式（2）等式（1），我们得到$\triangle AKM = \triangle BCM$，即直角等于tun。

这里很明显该论证使用了绘图：假设点 $O$ 位于非四边形中。但它也可以在边$KC$上或在四边形内部。我们检查这些案例并得出同样荒谬的结论。

然后我们使用工具尽可能准确地进行绘图（图4）。从图中可以看出，点$O$和$K$位于直线$BC$的两侧。确保在这种情况下推理不会导致懒惰，并通过反证证明这是与给定任务相对应的元素的唯一可能的推理。

在寻找解决方案时，我们通常首先发现最短路径远非最短。因此，检查是否可以缩短论证、简化或完全省略某些中间转换是有用的。

完成所有这些工作后，建议记下那些最难找到解决方案的点，尝试记住过程中建立的解决方案和以前未知的解决方案，或者忘记定理。

当这些定理在正确的时刻出现在头脑中时，这样的工作就体现在解决以下问题上。

下表收集了所考虑的建议。其中包含的说明不需要记住。在解决几个问题的过程中，有选择地阅读和执行就足够了。

让我们应用这个方法来解决以下问题。

问题4. 在正方形$ABCT$中，从点$T$（如从中心）画一条圆弧$AC$，其半径等于边长。在$AT$上，正如在直径上一样，在正方形内构建一个半圆。 $P$——圆弧点$AC$；直线 $PT$ 与半圆 $AT$ 相交于点 $K$。证明线段$PK$的长度等于点$P$到边$AB$的距离。

说明 1. 我们按照任务条款进行绘图，并进行$PE \perp AB$（图 5）。我们必须证明$PE = PK$。

说明 2. 我们来画线段 $AP$ 和 $AK$。我们必须证明$\Delta APE = \Delta APK$。

提示 2. 内切三角形 $\triangle AKT$ 位于直径和 $PE \perp AB$ 上，因此三角形 $APE$ 和 $APK$ 与公共斜边 $AP$ 成直角。

说明2. 例如，仍需证明等式$\alpha = \beta$。

⟦folio 42⟧

<table><thead><tr><th>说明</th><th>附加说明</th></tr></thead><tbody><tr><td>1.熟悉问题。</td><td>a) 完成绘图，图。分析所有可能的图形排列。
b) 选择数据和您要查找的内容。
c) 回忆概念的符号和属性。</td></tr><tr><td>2。交替地从受欢迎的内容移动到数据，再从数据移动到受欢迎的内容，寻找它们之间的联系。</td><td>a) 将受欢迎的内容替换为它所遵循的陈述。
b) 从数据中得出结果。
c) 使用所有数据。</td></tr><tr><td>3。如果您有任何困难，请参阅附加说明：3a、36、38 等</td><td>a) 回忆一个与此类似的问题。使用方法来解决它。
b) 改变问题的条件（只考虑部分数据的时间、替换所需的数据等）。
c) 解决部分情况下的问题。
d) 使用工具进行更精确的绘图并制作模型。观察揭示了图形的属性。验证所得结论。</td></tr><tr><td>4。陈述找到的解决方案，证明每个步骤的合理性。完成问题。</td><td>a) 尝试缩短推理过程或寻找另一种更简单的方法来解决它。
b) 进行检查。
c) 记住那些以前不知道或忘记的求解时使用的定理。</td></tr></tbody></table>

⟦folio 43⟧

图 6.

准则 26. $KO = \frac{1}{3} KC$，因此 $S_{\Delta KPC} = 9 S_{\Delta KOT}$。

说明 2 $OT = TA = OE$，因此$S_{\Delta KOT} = \frac{1}{2} S_{\Delta AKO}$，$S_{\Delta AKO} = \frac{1}{2} S_{\Delta AOB}$，$CK = 3 \cdot OK$，因此$S_{\Delta AOB} = \frac{1}{3} S$。最后，$S_{\Delta KCP} = 9 S_{\Delta KOT} = \frac{9}{2} S_{\Delta AKO} = \frac{9}{4} S_{\Delta AOB} = \frac{3}{4} S$。

问题 6. 证明 $\frac{R}{r} \geq \sqrt{2} + 1$，其中 $R$ 是围绕正则四重聚酰胺描述的球的半径，$r$ 是在此参数中描述的球的半径。

准则 1. 令 $PABCD$ 为正则 Paramid，$PO$ 其高度 (图 7)。那么在paramid中描述的球的中心$T$位于其高度处，并且在其附近描述的球的中心$M$位于该高度或其延伸上。

说明 2为了在证明不等式$\frac{R}{r} \geq \sqrt{2} + 1$时使用这些问题，我们通过paramida的元素来表达$R$和$r$。如果一个元素是线性的，第二个元素是角度的，那么这就更容易做到。设$BC = a$，$\triangle PKO = \alpha$，其中$K$是$CB$，$\triangle PCO = \beta$的中间。请注意，$R$和$r$比$a$和$\beta$更容易用$a$和$\alpha$来表达。

图 7.

准则 26. $T$ 是正则 Paramid 中描述的球的中心，$\triangle PKO$ 是二面角 $BC$ 的线性角，因此 $TK$ 是角 $OKP$ 和 $r = OT = \frac{a}{2} \cdot tg \frac{\alpha}{2}$ 的平分线。

说明 2要找到$R = MP = MC = MB = \dots$，你可以检查一下。 $ME \perp PC$ 并考虑相似的三角形$PME$ 和$POC$。为此，您需要找到 $PC$、$OP$ 和 $PE = \frac{1}{2} CP$。

准则 26。$OC = \frac{a \sqrt{2}}{2}$，$OP = \frac{a}{2} tg \alpha$。因此，$\Delta OPC$将得到$PC = \frac{a}{2} \sqrt{2 + tg^2 \alpha}$。然后$PE = \frac{a}{4} \sqrt{2 + tg^2 \alpha}$。

根据三角形$OPC$和$MPE$的相似度，我们有：$\frac{PM}{PE} = \frac{PC}{OP}$，$PM = \frac{PE \cdot PC}{PO}$。将值$PE$、$PC$和$PO$代入，我们得到$R = PM = \frac{(2 + tg^2 \alpha) \cdot a}{4 tg \alpha}$。

因此，$\frac{R}{r} = \frac{2 + tg^2 \alpha}{2 \cdot tg \alpha \cdot tg \frac{\alpha}{2}}$。

⟦folio 44⟧

说明 2a.原始不等式包含两个参数：$R$和$r$。利用这些问题，我们将其替换为不等式

$$\frac{2 + \text{tg}^2 \alpha}{2 \text{tg} \alpha \cdot \text{tg} \frac{\alpha}{2}} \geq \sqrt{2} + 1,$$

其中我们可以转到tg$\frac{\alpha}{2}$，即只有一个参数，这意味着会更容易证明。

注 26. 对最后一个不等式的 ley 部分进行变换，我们得到

$$\frac{1 + \text{tg}^4 \frac{\alpha}{2}}{2 \text{tg}^2 \frac{\alpha}{2} \cdot \left(1 - \text{tg}^2 \frac{\alpha}{2}\right)} \geq \sqrt{2} + 1.$$

我们用 $\text{tg}^2 \frac{\alpha}{2} = x$ 表示，要证明的不等式的形式为

$$\frac{1 + x^2}{2x(1-x)} \geq \sqrt{2} + 1.$$

说明 2a.为了证明不等式，只需证明

$$A = \frac{1 + x^2}{2x(1-x)} - \left(\sqrt{2} + 1\right) \geq 0.$$

指令 26.

$$A = \frac{1 + x^2 - 2x\sqrt{2} - 2x^2 + 2\sqrt{2}x^2 + 2x^2}{2(1-x)} = \frac{(3 + 2\sqrt{2})x^2 - 2(1 + \sqrt{2})x + 1}{2x(1-x)}$$

二次三项式的分子判别式为零（检查）和 $3 + 2\sqrt{2} > 0$。因此，三项式是非负的。

说明 2a.如果能证明分数$2x \times (1-x)$的分母为正，那么问题就解决了。

指令26. $x = \text{tg}^2 \frac{\alpha}{2}$，但是$0 < \alpha < \frac{\pi}{2}$，$0 < \frac{\alpha}{2} < \frac{\pi}{4}$，由此而来$0 < \text{tg}^2 \frac{\alpha}{2} < 1$，即$0 < x < 1$，$1 - x > 0$。这意味着$A \geq 0$和不等式$\frac{R}{r} \geq \sqrt{2} + 1$被证明。

练习

1. 在平行四边形$ABCD$中，点$M$是$AD$、$BC = 2AB$、$E$的中点——从顶点$C$到$AB$的垂线的底边。证明$\Rightarrow EMD = 3 \Rightarrow AEM$。

2. 三角形 $ABC$ 外接圆。证明这个圆的直径$CM$和三角形$CK$的高度之间的角度等于$| \Rightarrow A - \Rightarrow B|$。

3. 证明对于任何偶数 $n$，$\frac{n}{12} + \frac{n^2}{8} + \frac{n^3}{24}$ 都是整数。

4. 平行四边形的边是$a$和$b$。计算该平行四边形内角平分线交点形成的四边形的对角线。

5. 沿边 $b$、外接圆半径 $R$、中线 $m_c$ 构造一个三角形 $ABC$。

6. 三角形长方形的两个面都是等边直角三角形，有一条公共斜边$AB$。 $AB$ 处的二面角为 $a$。找到一个二面角，其边有一条腿。

7. 如果底平面与侧面之间的二面角等于 $\alpha$、$\beta$、$\gamma$，求直线的体积，该直线的底边是从边 $a$ 开始的正三角形。

8. 找出 $\frac{34x5y}{34x5y}$ 形式的所有能被 36 整除的五位数字。

9. 证明$(\sqrt{3} - \sqrt{2})^{243}$可以表示为$a\sqrt{3} - b\sqrt{2}$，其中$a$和$b$是整数，$3a^2 - 2b^2 = 1$。
