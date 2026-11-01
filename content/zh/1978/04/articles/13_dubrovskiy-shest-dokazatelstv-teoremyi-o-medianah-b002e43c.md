---
id: 1978-4-dubrovskiy-shest-dokazatelstv-teoremyi-o-medianah-b002e43c
issue: kvant_1978_4
year: 1978
number: "4"
title: 中位数定理的六个证明
authors:
  - Дубровский В. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 40
page_labels: 36-38
tag: XUOD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c879a3b58dcb22ea6dbc54641f6eef672b16e0b133b046e0a528b8cc45c1a5ba
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/13_dubrovskiy-shest-dokazatelstv-teoremyi-o-medianah-b002e43c.md
source_content_sha256: 6dbf48578075e58cf84add5e674d005ae19bc0d5e3ea5988efa9bb7bf46bc63e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

V·杜布罗夫斯基

中位数定理的六个证明

你不能用油毁掉你的护齿套。

关于三角形中线相交的定理在教科书《几何6、7、8》中并未得到证明，而是以问题的形式进行了假设。该定理随后被用于《几何 9》教科书。这里我们提出它的几个证明。

定理。三角形ABC的中线AA₁、BB₁、CC₁交于某点M，分别除以该点，以2：1的比例除以从顶点算起：
|AM| : |MA₁| = |BM| : |MB₁| =
= |CM| : |MC₁| = 2. (1)

在下面给出的所有证明中，除了第六个之外，我们仅确定中位数 BB₁ 通过点 M，该点将中位数 AA₁ 除以 2:1 的比率。

如果根据相应的推理，我们将[BB₁]替换为[CC₁]，那么我们得到[CC₁]也经过M。这将证明所有三个中线都相交于某个点M，且|AM| :|MA₁| = 2。

由于所有中位数都相等，我们可以将 [AA₁] 替换为 [BB₁] 或 [CC₁]； (1) 从这里开始。

第一个证明（六年级）。令K为线段AM的中点，B'为线BM与边AC的交点。我们只要证明 |AB'| 就足够了= |B'C|。通过与直线 BM 平行的点 K 和 A₁，我们绘制线段 [KL] 和 [A₁N] (图 1)。经过-

⟦folio 37⟧

正方形 $MAC$ 和 $MA_1C$ (图 3)。
它们的高度（从顶点 $C$ 省略）重合，并且与该顶点相对的边的长度比例为 2:1，因此为 $S_{AMC} = 2S_{A1MC}$。
同样，$S_{AMB} = 2S_{A1MB}$。
但是$S_{A1MC} = S_{A1MB}$。因此，$S_{AMC} = S_{AMB} = S_{BMC}$。
因此，三角形 $MAB$、$MBC$ 和 $MCA$ 大小相等。让$B' = (BM) \cap (AC)$。让我们证明$|AB'| = |B'C|$。一方面，$\frac{|AB'|}{|B'C|} = \frac{S_{AB'M}}{S_{CB'M}}$。另一方面，$\frac{|AB'|}{|B'C|} = \frac{S_{AB'B}}{S_{CB'B}}$。所以，$\frac{|AB'|}{|B'C|} = \frac{S_{AB'B}}{S_{CB'B}}$。使用定理$\frac{a}{b} = \frac{c}{d} \Rightarrow \frac{c-a}{d-b} = \frac{a}{b}$。
从这里我们得到
$$\frac{|AB'|}{|B'C|} = \frac{S_{AB'B} - S_{AB'M}}{S_{CB'B} - S_{CB'M}} = \frac{S_{ABM}}{S_{CBM}} = 1.$$

图 3.

图 4.

所以，$|AB'| = |B'C|$。
第四个证明（七年级）。从 图 4
$$\overrightarrow{BM} = \overrightarrow{BC} + \overrightarrow{CA} + \overrightarrow{AM} =$$
$$= \overrightarrow{BC} + \overrightarrow{CA} + \frac{2}{3} \overrightarrow{AA_1} =$$
$$= \overrightarrow{BC} + \overrightarrow{CA} + \frac{2}{3} \left( \overrightarrow{AC} + \overrightarrow{CA_1} \right) =$$
$$= \overrightarrow{BC} + \overrightarrow{CA} + \frac{2}{3} \overrightarrow{AC} + \frac{1}{3} \overrightarrow{CB} =$$
$$= \overrightarrow{BC} - \frac{1}{3} \overrightarrow{BC} + \overrightarrow{CA} - \frac{2}{3} \overrightarrow{CA} =$$
$$= \frac{2}{3} \overrightarrow{BC} + \frac{1}{3} \overrightarrow{CA} =$$
$$= \frac{2}{3} \left( \overrightarrow{BC} + \frac{1}{2} \overrightarrow{CA} \right) =$$
$$= \frac{2}{3} \left( \overrightarrow{BC} + \overrightarrow{CB_1} \right) = \frac{2}{3} \overrightarrow{BB_1}$$.

因此，点$M$位于中线$BB_1$上。
第五个证明（八年级）。再次让 $B' = (BM) \cap (AC)$ (图 3)。首先将正弦定理应用于三角形$AB'B$和$CB'B$，然后应用于三角形$ABM$和$A_1BM$，得知$\sin \overrightarrow{AB'B} = \sin \overrightarrow{CB'B}$，$\sin \overrightarrow{AMB} = \sin \overrightarrow{A_1MB}$，$|BC| = 2|A_1B|$和$|MA| = 2|MA_1|$，我们得到
$$\frac{|AB'|}{|B'C|} =$$
$$= \frac{|AB| \sin \overrightarrow{ABM}}{\sin \overrightarrow{AB'B}}: \frac{|BC| \sin \overrightarrow{A_1BM}}{\sin \overrightarrow{CB'B}} =$$
$$= \frac{|MA| \sin \overrightarrow{AMB}}{2|MA_1| \sin \overrightarrow{A_1BM}} = 1.$$

所以，$|AB'| = |B'C|$。
第六证明（九年级）。让我们通过点$A$和$B$画一个平面$\alpha$，不包含$C$，并在这个平面上构造一个正三角形$ABC'$（图5）。根据平行投影的一般性质（“几何 9”，§ 12），沿直线 $CC'$ 的平行投影需要 $\triangle ABC$

⟦folio 38⟧

图 5.

$\Delta ABC'$，三角形$ABC$的中线投影到三角形$ABC'$的中线。但在正三角形中，中线也是二分线，因此相交于一点。也很容易证明（证明！）对于三角形 $ABC'$ 等式（1）是有效的。

由此可见，我们的定理对于 $\Delta ABC$ 也成立。

总之，我们注意到$\overrightarrow{MA} + \overrightarrow{MB} + \overrightarrow{MC} = \overrightarrow{MA} + 2\overrightarrow{MA}_1 = 0$，如果点$P$不与$M$重合，则$\overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC} = \overrightarrow{PM} + \overrightarrow{MA} + \overrightarrow{PM} + \overrightarrow{MB} + \overrightarrow{PM} + \overrightarrow{MC} = 3\overrightarrow{PM} \neq 0$。一般来说，点$G$称为点$A_1, A_2, \dots$系统的中心（或重心），

$$\frac{|AP|}{|PA_1|} = \frac{|BP|}{|PB_1|} = \frac{|CP|}{|PC_1|}.$$

证明$P$是三角形$ABC$的质心。

6. 证明七个线段：连接四面体顶点与相对面质心的线段，以及连接相对边中点的线段相交于一点。这些片段通过它们的共同点以什么方式划分？

7. 证明三角形的质心是到三角形顶点的距离平方和达到最小值的唯一点。

（关于开头，请参见第 21 页）
N. Kevkhshivili（第比利斯）47、52、54； A. 科罗廖夫（高尔基）57, 60a), 6), d)； S. Korchanov（安加尔斯克）46、47、49a)、50、56、57、60a)； V. Kostmusak（扎波罗热）46、48、50； L. Kostmok（基辅）54； E.库兹明（切尔波韦茨）46、48、54、56、57； A.库季诺夫（沃罗涅日）57； S.库兹涅佐夫（安加尔斯克）53； A. Kulesko（顿涅茨克）47, 50, 53-55, 60a), 6), c)； P.库利尼茨（沃罗涅日）54； A.库尔科夫（尼古拉耶夫）52； E. Lapin（阿拉木图）52； I.洛齐茨基（甘采维奇）46、48、52、53； E. Lumelskaya（彼尔姆）56、57； V.Marzzoy（阿拉木图）54； G. Martirosyan（塔林村，ArmSSR）46； D.马蒂诺夫（切尔克佐沃）57； R. Meshchoir (莫斯科) 51, 56, 57, 60a)； A.米列夫斯基（Mytits）51、52、57； D. 明德林（塔什干）46、48、50、51、54、56； B.Mintsbere（列宁格勒）54； A. Mirlin（列宁格勒）46、47、49a)、50、51、53-58、60a)、6)、c)、d)； A.莫洛托维科夫（Teykov）54； E. Mostshvenko (瑟克特夫卡尔) 51, 54; I.迈舍（切尔诺夫策）57； N.Naumova（Kamyshin）54； A. Nenashev（列宁格勒）46, 48, 50—59, 60a), 6), c), d)； N. Nesterenko（新西伯利亚）47、48、51-54； A.尼基坚科夫（Velikiye Luki）48； G.尼科洛夫（NRB）52、56、57； A.奥纳林（高尔基）47, 48, 53, 60a), 6)； V. Ostmanenko（阿拉木图）54； D. 帕普什（哈尔科夫）46、50-52、54-57； I. Pashin（临时）46； I.波诺马列夫（奔萨）46； A. 波波夫 (Chusovoy) 54, 60a), 6)； V. Pomemkin（顿涅茨克）52； G. Puninsky（博布赖斯克）46, 52, 54, 60a), 6), c), d)； S. Putintsev（涅维诺夫斯基）51-55； H. Rivilis（敖德萨）496），56-58； I. Roizman（文尼察地区 Kalinovka 村）51、54； V. Romanovsky（续，见第 52 页）
