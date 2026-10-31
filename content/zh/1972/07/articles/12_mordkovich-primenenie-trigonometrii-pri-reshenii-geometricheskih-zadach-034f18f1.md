---
id: 1972-7-mordkovich-primenenie-trigonometrii-pri-reshenii-geometricheskih-zadach-034f18f1
issue: kvant_1972_7
year: 1972
number: "7"
title: 三角学在解决几何问题中的应用
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 45
page_labels: 40-43
tag: FAMN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 961dda0a93de56e1ba77314ac6c26b37da0ac362d67f747c249ebd137c9d1145
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/12_mordkovich-primenenie-trigonometrii-pri-reshenii-geometricheskih-zadach-034f18f1.md
source_content_sha256: 7b63f9517985ea860b9e25f6c3282421d83ab42cdeae6026a59911c4aadb2cc4
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

三角学在解决几何问题中的应用

A·G·莫德科维奇

在解决几何问题时，您经常需要求助于三角学。有时这种反演是必要的——当给定一个角度并使用该角度的三角函数来计算线性元素时，有时这种反演是可取的——当我们自己看到辅助角度时，按顺序，然后使用三角函数来计算我们需要的线性元素或建立线性元素之间的某种对应关系。如果说三角学在解决几何问题中的应用形式，那么主要包括一般三角变换、余弦定理，更广泛的是三角函数中使用的正弦定理、三角恒等式和三角方程。

现在让我们继续考虑任务。

任务1.正四边形paramid的底边等于a，底边的二维角为a。一个球被放置在paramid中；为球绘制一个切平面，该切平面平行于 paramid 的底部。确定所得截断的帕拉酰胺的侧面。

解决了并且e。无需在图上画内接球。显示球的中心 (图 1) 就足够了 - 这是 paramid 高度与线性角 SDH 平分线的交点 O - 并且考虑到截断 paramid 的高度 HH₁ 等于球的直径。

我们有： OH = r = HD tg ⇐ ODH = a/2 tg α/2，

HH₁ = 2r = a tg α/2,

S_{60k} = 4·(AB + A₁B₁)/2·DD₁ = 2(a + A₁B₁)·DD₁。

⟦folio 41⟧

为了进一步计算，我们需要辅助 图 2：

$$A_1B_1 = 2H_1D_1 = 2HE = 2(HD - DE) = 2\left(\frac{a}{2} - D_1E \cdot \text{ctg} \alpha\right) =$$

$$= a - 2HH_1 \text{ctg} \alpha = a - 2a \text{tg} \frac{\alpha}{2} \text{ctg} \alpha, \quad DD_1 = \frac{D_1E}{\sin \alpha} = \frac{HH_1}{\sin \alpha} = \frac{a \text{tg} \frac{\alpha}{2}}{\sin \alpha},$$

$$S_{60^\circ} = 2\left(a + a - 2a \text{tg} \frac{\alpha}{2} \text{ctg} \alpha\right) \cdot \frac{a \text{tg} \frac{\alpha}{2}}{\sin \alpha} = \frac{4a^2 \text{tg}^2 \frac{\alpha}{2}}{\sin^2 \alpha}.$$

问题 2. 如果边 $a$ 和 $b$ 的内切角落在圆弧 $\alpha$ 上，求圆的半径。

解决方案。内切角为$\frac{\alpha}{2}$。让我们用 $x$ (图 3) 表示连接内切角两端的弦；然后根据余弦定理$x^2 = a^2 + b^2 - 2ab \cos \frac{\alpha}{2}$。接下来，根据正弦定理$\frac{x}{\sin \frac{\alpha}{2}} = 2R$，我们开

$$R = \frac{x}{2 \sin \frac{\alpha}{2}} = \frac{\sqrt{a^2 + b^2 - 2ab \cos \frac{\alpha}{2}}}{2 \sin \frac{\alpha}{2}}.$$

问题3. 三面角的平面角（图 4），$SM$ 是平面角$\alpha$ 和$\beta$ 的公边。让我们找到边 $SM$ 处的二面角值。让我们留出线段$SC = 1$，通过点$C$垂直于线$SM$画一个平面，并用$A$和$B$表示该平面与射线$SN$和$SP$的交点。那么$\triangle ACB$就是我们感兴趣的二面角的线性角。

让$\triangle ACB = x$，然​​后$AC = \text{tg} \alpha$，$BC = \text{tg} \beta$，$AS = \sec \alpha$，$BS = \sec \beta$。从三角形 $ABS$ 通过余弦定理我们有

$$AB^2 = AS^2 + BS^2 - 2AS \cdot BS \cdot \cos \gamma,$$

那是

$$AB^2 = \sec^2 \alpha + \sec^2 \beta - 2 \sec \alpha \cdot \sec \beta \cdot \cos \gamma.$$

另一方面，根据余弦定理，从三角形 $ABC$ 我们有

$$AB^2 = AC^2 + BC^2 - 2AC \cdot BC \cos x,$$

⟦folio 42⟧

那是

$$AB^2 = tg^2\alpha + tg^2\beta - 2tg\alpha tg\beta \cdot \cos x.$$

因此，

$$\sec^2\alpha + \sec^2\beta - 2\sec\alpha\sec\beta\cos\gamma = tg^2\alpha + tg^2\beta - 2tg\alpha tg\beta\cos x,$$

在哪里

$$\cos x = \frac{\cos\gamma - \cos\alpha \cdot \cos\beta}{\sin\alpha \cdot \sin\beta}.$$

这意味着与平面角 $\gamma$ 相反的二面角等于 arccos\left(\frac{\cos\gamma - \cos\alpha \cos\beta}{\sin\alpha \sin\beta}\right)。二面角的发现类似。

如果将三个平面和三个二面角视为三面角的基本要素，那么所考虑的问题使我们可以得出这样的结论：从三面角的任何三个基本要素可以找到其余三个。

问题4. 通过等边三角形底角$\alpha$的顶点画一条直线，与直边相交，并与底角$\beta$（$\beta < \alpha$）。这条线以什么比例划分三角形？

解决了并且e。令 $AB = BC = a, DC = x, BD = a - x$ (图 5)。三角形$ABD$和$ACD$具有共同的高度，因此它们的面积与底边相关，即边长$BD$和$CD$：

$$\frac{S_{ABD}}{S_{ACD}} = \frac{a - x}{x} = \frac{a}{x} - 1.$$

因此，解决这个问题我们只需要找到关系$\frac{a}{x}$。

让我们将正弦定理应用到三角形 $ABD$

$$\frac{a - x}{\sin(\alpha - \beta)} = \frac{a}{\sin(\alpha + \beta)}.$$

从这里

$$\frac{x}{a} = \frac{\sin(\alpha + \beta) - \sin(\alpha - \beta)}{\sin(\alpha + \beta)}.$$

到底

$$\frac{S_{ABD}}{S_{ACD}} = \frac{a}{x} - 1$$

$$= \frac{\sin(\alpha + \beta)}{\sin(\alpha + \beta) - \sin(\alpha - \beta)} - 1 = \frac{\sin(\alpha - \beta)}{2\sin\beta\cos\alpha}.$$

问题5. 正四边形帕拉米德的所有侧面均与底面倾斜角度$\alpha$，且侧面的边心为$a$。通过底座的一侧与底座平面形成角度 $\beta$ ($\beta < \alpha$)。计算横截面积。

解决了并且e。我们先来看看(图6)部分是什么。它平行于线$AB$，并且经过$AB$的侧面与截面相交。沿直线$EF$。但是，如果通过与某个平面平行的线绘制与第一个平面相交的平面，则交线平行于该线，因此平行于线 $CD$。所以，横截面是梯形。

⟦folio 43⟧

现在我们来计算一下。

我们有
$$KH = SK \cdot \cos \alpha = a \cos \alpha,$$
$$KL = CD = 2 a \cos \alpha.$$

让我们将正弦定理应用于三角形 $MKL$：
$$\frac{ML}{\sin \alpha} = \frac{KL}{\sin [180^\circ - (\alpha + \beta)]},$$
在哪里
$$ML = \frac{KL \sin \alpha}{\sin (\alpha + \beta)} = \frac{a \sin 2\alpha}{\sin (\alpha + \beta)}.$$

让我们将正弦定理应用于三角形 $MSL$：
$$\frac{SL}{\sin (\alpha + \beta)} = \frac{MS}{\sin (\alpha - \beta)},$$
$$MS = \frac{a \sin (\alpha - \beta)}{\sin (\alpha + \beta)}.$$

根据三角形$SEF$和$ABS$的相似度我们得到：
$$\frac{MS}{KS} = \frac{EF}{AB}.$$
从这里我们得到
$$EF = \frac{AB \cdot MS}{KS} = \frac{2a \cos \alpha \cdot a \sin (\alpha - \beta)}{a \cdot \sin (\alpha + \beta)} =$$
$$= \frac{2a \cos \alpha \cdot \sin (\alpha - \beta)}{\sin (\alpha + \beta)}.$$

现在我们有了计算横截面积所需的东西。我们有
$$S = \frac{1}{2} (CD + EF) \cdot ML = \frac{1}{2} \left[ 2a \cos \alpha + \frac{2a \cos \alpha \cdot \sin (\alpha - \beta)}{\sin (\alpha + \beta)} \right] \times \frac{a \sin 2\alpha}{\sin (\alpha + \beta)} =$$
$$= \frac{a^2 \sin^2 2\alpha \cdot \cos \beta}{\sin^2 (\alpha + \beta)}.$$

问题6. 在圆的一条弧$AB$上，给出任意点$K$和点$M$——弧的中点。这些点通过点 $A$ 和 $B$ 的弦连接。证明$AK \cdot KB = AM^2 - KM^2$。

解决了并且e。让我们用 $\alpha$ 表示角度 $KBA$，用 $\beta$ (图 7) 表示角度 $KBM$。让我们将正弦定理应用于三角形 $AKB$：
$$\frac{AK}{\sin \alpha} = 2R, AK = 2R \sin \alpha.$$ 同样从三角形 $AMB$ 位于 $AM = 2R \sin (\alpha + \beta)$，并从三角形 $KBM - KM = 2R \sin \beta$.

现在让我们考虑三角形$KMB$。我们有$\Rightarrow KBM = \beta, \Rightarrow MKB = = \Rightarrow MAB = \Rightarrow ABM = \alpha + \beta, \Rightarrow KMB = 180^\circ - \beta - (\alpha + \beta) = 180^\circ - (\alpha + 2\beta), KB = 2R \sin [180^\circ - (\alpha + 2\beta)] = 2R \sin (\alpha + 2\beta)$。我们需要证明$AK \cdot KB = AM^2 - KM^2$，即
$$2R \sin \alpha \cdot 2R \sin (\alpha + 2\beta) = 4R^2 \sin^2 (\alpha + \beta) - 4R^2 \sin^2 \beta$$
或者
$$\sin \alpha \cdot \sin (\alpha + 2\beta) = \sin^2 (\alpha + \beta) - \sin^2 \beta.$$

问题被简化为证明三角点。证明并不困难，留给读者去证明吧。

问题7. 在三角形中，一个角是弧长的两倍，该角的对边与弧长相差2 厘米。如果已知三角形的边长是 5 厘米，请求这些边。
