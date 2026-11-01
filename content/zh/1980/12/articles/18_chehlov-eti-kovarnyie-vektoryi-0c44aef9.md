---
id: 1980-12-chehlov-eti-kovarnyie-vektoryi-0c44aef9
issue: kvant_1980_12
year: 1980
number: "12"
title: 这些“阴险”的载体
authors:
  - Чехлов В. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 46
page_labels: 40, 42, 43, 44
tag: KANU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 51264b2273dfa6406365e7b94f1d76d0653817039ab498a46c6106c3121026dc
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/18_chehlov-eti-kovarnyie-vektoryi-0c44aef9.md
source_content_sha256: e5111849d0c4099c441094159fd3a9621927bbef7137fa03666b83f0dc17b893
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

这些“阴险”的载体

本笔记主要介绍应用向量解决几何问题的一些特征。

向量的使用基于以下事实：关于点、线和平面的相对位置的各种陈述可以以“向量语言”形成，特别是使用共线和共面的概念。这使我们能够将几何问题简化为向量等式。反过来，向量等式可以（特别是基于分解定理的唯一性）简化为代数等式或代数等式系统。

问题1.平行四边形ABCD的底。该平面与相应平行线的侧边 SA、SB、SC 和 SD 相交于点 M、N、P 和 Q，使得 |SM|:|SA|=a，|SN|:|SB|=b，|SP|:|SC|=c，

图 1.

|SQ|:|SD|=d。证明$\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$。

解决方案e.线段 NM、NP 和 NQ (图 1) 位于同一平面内。根据共面向量的定义，向量NM、NP和NQ是共面的。向量 NM 和 NP 显然不共线，因此，根据共面向量分解定理，存在满足 $NQ = xNM + yNP$ 的数 x 和 y。 (1)

让我们将这些向量分解为三个非共平面向量 SA、​​SB 和 SC。我们有 SM=aSA, SN=bSB, SP=cSC, SQ=dSD，从哪里

$NM = SM - SN = aSA - bSB$, (2)
$NP = SP - SN = cSC - bSB$, (3)
$NQ = SQ - SN = dSD - bSB$. (4)

由于$SD = SA + AD$和$AD = BC = SC - SB$，由(4)得出$NQ = dSA - (d + b)SB + dSC$。 (5)

将(2)、(3)、(5)代入(1)可得

$NQ = dSA - (d + b)SB + dSC = axSA - b(x + y)SB + cySC$. (6)

由于展开式的唯一性，向量等式(6)等价于系统

$$\begin{cases}
d = ax; \\
d + b = b(x + y), \\
d = cy.
\end{cases}$$

因此$x + y = \frac{d}{a} + \frac{d}{c} = \frac{d + b}{b}$，或$\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$。

在所考虑的示例中，矢量等式（6）被简化为系统（7）。应该记住，空间向量的等式等价于三个代数等式的系统。因此，如果这个系统的等式对于任何变量值至少有一个为假，那么向量等式为假，原来的几何问题无解。下面的简单例子证实了这一点。

⟦folio 42⟧

我们压入 OAB 平面。这意味着向量 $\vec{a}, \vec{b}$ 和 $\vec{c}$ 共面。除了上面的例外，证明就更简单了，我们把它留给读者。

问题 3（《几何 9-10》，第 247 期）。 A点是平行四边形ABCD和$AB_1C_1D_1$的公共顶点。证明向量$\vec{BB}_1, \vec{CC}_1, \vec{DD}_1$共面。

解决方案。我们有 $\vec{CC}_1 = \vec{CB} + \vec{BB}_1 + \vec{B}_1\vec{C}_1$ (图 4)，并且从 $\vec{CB} = \vec{DA}$ 和 $B_1\vec{C}_1 = \vec{AD}_1$ 开始，我们得到 $\vec{CC}_1 = \vec{BB}_1 + (\vec{DA} + \vec{AD}_1)$。但是$\vec{DA} + \vec{AD}_1 = \vec{DD}_1$，因此$\vec{CC}_1 = \vec{BB}_1 + \vec{DD}_1$。从 (*) 可知向量 $\vec{CC}_1, \vec{BB}_1$ 和 $\vec{DD}_1$ 共面。

问题 4. 给定三个与 $(\vec{a}, \vec{c}) = (\vec{b}, \vec{c}) = \frac{\pi}{3}, (\vec{a}, \vec{b}) = \frac{\pi}{2}$ 相同的联合向量 $\vec{a}, \vec{b}$ 和 $\vec{c}$。这些向量共面吗？

我们建议首先找出以下推理中的错误：

“让我们证明$\vec{a}, \vec{b}$和$\vec{c}$共面。我们将寻找数字$x$和$y$，其中$\vec{c} = \vec{x}a + \vec{yb}$。

为此，我们将 (11) 两边均乘以向量 $\vec{a}$。我们从$x = \frac{1}{2}$得到$\vec{c} \cdot \vec{a} = \vec{x}a \cdot \vec{a} + \vec{yb} \cdot \vec{a}$。将(11)两边乘以$\vec{b}$，我们得到$\vec{c} \cdot \vec{b} = \vec{x}a \cdot \vec{b} + \vec{yb} \cdot \vec{b}$，即$y = \frac{1}{2}$。方法，

$$\vec{c} = \frac{1}{2} \vec{a} + \frac{1}{2} \vec{b},$$

也就是说，通过 (*) 向量 $\vec{a}, \vec{b}, \vec{c}$ 是共面的。”

很容易证明这种推理是错误的。从某个点开始尝试向量 $\vec{a}, \vec{b}, \vec{c}$ 以及它们之间给定的角度就足够了。立即明确表示这是不可能的。这意味着向量 $\vec{a}, \vec{b}$ 和 $\vec{c}$ 不共面。

为了理解错误出在哪里，让我们回到争论的开始。其中的目标是找到满足等式 (11) 的数字 $x$ 和 $y$。但这种编号并没有进行。事实上，下面的计算仅证明了 (11) 遵循 (12)，仅此而已。数 $x$ 和 $y$（（11）为真）的存在性以及等式（12）都尚未被证明。这意味着“通过 (*) 向量 $\vec{a}, \vec{b}, \vec{c}$ 共面”的结论是不合理的。

这里的错误在于，从进行的推理中得出的结论与已证明的陈述不相符。

现在让我们提出问题 4 的向量解。

让我们通过反证证明向量 $\vec{a}, \vec{b}, \vec{c}$ 不共面。让我们假设存在数字 $x$ 和 $y$ 使得等式 (11) 成立。然后，和之前一样，我们发现 (12) 也成立。将 (12) 标量乘以 $\vec{c}$，我们得到等式 $1 = \frac{1}{4} + \frac{1}{4}$ 成立，即 $1 = \frac{1}{2}$。这个矛盾表明，(11)对于任何$x$和$y$都不成立，即向量$\vec{a}, \vec{b}, \vec{c}$不共面。

让我们考虑另一个例子，说明几何问题的条件不完整地转换为“矢量语言”会如何导致错误。

问题5 四面体ABCD中的边AD在什么长度处满足相应条件：

$$\overrightarrow{ABC} = \frac{\pi}{2}, \overrightarrow{BCD} = (AB, CD) = \frac{5}{7},$$

$$|AB| = |BC| = |CD| = a?$$

⟦folio 43⟧

“解决方案”。从$\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}$开始，我们得到$\vec{AD}^2 = \vec{AB}^2 + \vec{BC}^2 + \vec{CD}^2 + 2\vec{AB} \cdot \vec{BC} + 2\vec{AB} \times \vec{CD} + 2\vec{BC} \cdot \vec{CD}$。这里$\vec{AB}^2 = \vec{BC}^2 = \vec{CD}^2 = a^2$，$\vec{AB} \cdot \vec{BC} = 0$，$\vec{BC} \times \vec{CD} = a^2$ cos $(\pi - \vec{BCD}) = -\frac{5}{7} a^2$，$\vec{AB} \cdot \vec{CD} = a^2$ cos $(\vec{AB}, \vec{CD})$，并且由于可能有两种情况：$(\vec{AB}, \vec{CD}) = \arccos \frac{5}{7}$或$(\vec{AB}, \vec{CD}) = \pi - \arccos \frac{5}{7}$，所以我们得到$\vec{AB} \times \vec{CD} = \frac{5}{7} a^2$或$\vec{AB}, \cdot \vec{CD} = -\frac{5}{7} a^2$。由此可见，要么$\vec{AD}^2 = 3a^2$，要么$\vec{AD}^2 = \frac{a^2}{7}$。所以，$|\vec{AD}| = \sqrt{3} a$，或$|\vec{AD}| = \frac{a}{\sqrt{7}}$。

乍一看，这个决定没有任何错误的余地。然而，其中有一个错误。事实上，所提出的几何问题与求解矢量系统的问题是平衡的：
$$\begin{cases}
|\vec{AB}| = |\vec{BC}| = |\vec{CD}| = a, \\
\vec{AB} \cdot \vec{BC} = 0, \\
\vec{AB} \cdot \vec{CD} = \pm \frac{5}{7} a^2, \\
\vec{BC} \cdot \vec{CD} = -\frac{5}{7} a^2, \\
\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}.
\end{cases}$$

这是一个具有四个未知向量 $\vec{AB}, \vec{BC}, \vec{CD}$ 和 $\vec{AD}$ 的系统，问题 5 的几何公式​​现在可以用代数（向量）公式代替：长度是多少

图 5.

⟦folio 44⟧

将(15) 两边标量乘以$\vec{AB}$，得到$x = \pm \frac{5}{7}$，将(15) 两边乘以$\vec{BC}$，得到$y = -\frac{5}{7}$。然后

$$|\vec{CD}|^2 = (x^2 + y^2 + z^2)a^2 = \left(\frac{50}{49} + z^2\right)a^2 > a^2,$$

这与条件$|\vec{CD}| = a$相矛盾。

这意味着系统（14）无解，我们得到与之前相同的答案。

本笔记所附问题可以使用向量和几何数来解决。

练习
1. 给定不在同一直线上的点$A, B, C$，以及点$D$和$O$、$O \neq D$。证明为了使点$D$属于平面$ABC$，$OD = xOA + yOB + zOC$是充分必要的，其中$x + y + z = 1$。

2. 线 $SABCD$ 的底边是平行四边形 $ABCD$。在边$AB, AS$和$SC$上分别有点$M, N$和$P$，因此$|BM| : |AB| = |AN| : |AS| = |SP| : |SC| = 2:3$。通过边 $BC$ 的中间 $Q$ 画一条直线，平行于平面 $MNP$ 并与线 $SD$ 相交于点 $R$。求比率 $|DR| : |DS|$。

3. 正则直线 $ABCA_1B_1C_1$ 的所有边的长度为 $a$。垂直于平面 $BA_1C_1$ 的直线分别与线 $BC_1$ 和 $AB_1$ 相交于点 $M$ 和 $N$。找到$|MN|$。

4. 给定三条不在同一平面上的直线。有多少条线穿过给定点并与给定线 $^2$ 形成相等的角度。

5. 在四面体$ABCD$$|AB| = |BC| = |CD|$、$ABC = a$、$BCD = (AB, CD) = \beta$。求直线 $AD$ 和 $BC$ 之间的角度。对于a和β问题a)无解； b) 有一个解； c) 有两个解吗？

从 Zadanika «Kvant» 发送问题正确解决方案的读者列表
（开头部分请参见第 34 页）

S.多罗宁（第聂伯罗彼得罗夫斯克）17； A. Dremin（莫斯科地区 Chernogolovka 村）12； A.杜尔巴克（罗哈廷）16； S. Dymshakov（沙德林斯克）16、17；于。 Eliseev (Velikiye Luki) 4; I. 埃利塞耶维奇（切尔尼戈夫）4、6、7； I.埃尔卡诺维奇（巴库）17； T. Enchev（扬博尔，NRB）9, 12； V. Zhordochki (奥尔斯克) 4, 6-8; V. Zavarzin（奇姆肯特）16； A.扎涅夫斯基（列宁格勒）4、6-9、11、16、17； M. Zeifman（沃洛格达）4、6、7、9、11、12、16； I. Zilberberg (阿拉木图) 6; V. Zolotagevsky (p/o Berezovskoye, 哈尔科夫地区) 7; I. Zybtsev（乌祖尔）9、11、12、17； T. Ivanov（白俄罗斯普列文）16、17； A. 伊万诺夫 (沃罗涅日) 8, 12; V.Ivakhenko（基辅）11； V. 伊泽列宁（新西伯利亚）7、9、11、12、16、17； V. Izrailit (第聂伯罗彼得罗夫斯克) 9, 16, 17; V.卡兹洛夫斯基（哈尔科夫）11、12； S.卡尔梅科夫 (Kopeisk) 6, 12; A. 卡普兰 (Sumgant) 8, 17; D.卡普兰（泽列诺格勒）7； A. Karsev (别尔哥罗德) 7, 17; M. Kachkatsivili (Rustavi) 12; E.卡沙诺夫（乌法）4； A. Kechedjyan（埃里温）6、7、9、11、12、16； M. Kibirev（图拉）8、9、12；于。基尔帕奇（基辅）4、6、7、11、17；于。科维尼克（扎波罗热）6； E.《古兰经》（第聂伯罗彼得罗夫斯克）8、9、11、12； A. Kozhevnikov（第聂伯罗彼得罗夫斯克）8、9、12； V.科兹洛夫斯基（Novolukoml）8-12； T. Kozhoridze（特尔维）12； D. Kolomotsev (Sumgant) 4, 6-9, 11； V. 科莫夫 (Aleksadrov) 4, 6-12, 16, 17; T. Kondratskaya（基辅）4, 6-8； S. Konkin（阿尔扎马斯）4、9、11、12； V.科罗博夫（基洛沃格勒）16； K. Korchazin（埃里温）16； M.科斯廷（萨拉托夫）12； I. Kostyuevich（列宁格勒）4、6、9、12、17； D. Kotelnikov（马格尼托哥尔斯克）4、6、7、16、17； M.克拉夫佐夫（科穆纳尔斯克）16； K. Krapivnoy (扎波罗热) 6, 7; I.克拉西科夫（基辅）8、9、11、12； A. Kreines (Kolchugino) 17; L. Kreminskaya（罗夫诺）8； E.克伦泽尔（莫斯科）17； R.克里斯（基辅）4、7、8、11、12； I. Krolivets（克拉马托尔斯克）11、12； E.库兹涅佐夫（基希讷乌）6、8、11、12； P.库兹涅佐夫（基辅）4、6、8-12； A. Kuzmin（阿拉木图）6,7,11； D. Kuksenkov（列宁格勒）16、17； S.库尔恰托夫（萨拉托夫）4、7； B. Lapidus（莫斯科）11、12、17； M. Levenkov (Vereshchino) 17; V. Leites（莫斯科）4、6、7； I.列昂诺夫（沃罗涅日）6、11、12； D. Leshchinsky（马格尼托哥尔斯克）16； F. Lomaya（辛菲罗波尔）9、12； I. Lukuyanchuk（基辅）4、6、17； E.Lyubovitsky（科斯特罗马）16； A. 利亚宾（戈梅利）4、6、16、17； A. Mazurkovich (Lytkarino) 6, 9, 11, 12; Z.马基莫夫（塔什干）16、17； A.马尔钦（高尔基）16； V.马尔采夫（乌法）17； O.Manuilenko（基辅）17； S. Maslennikov（戈门地区 Meshon 村）4； S. Makhortykh（利西昌斯克）9； A.米库拉（日达奇科夫）4、6、12、17； S.米洛瓦诺夫（扎波罗热）17； S. Mikhailovsky（阿尔汉格尔斯克州维诺格拉多夫斯基区）7、11、12、16； G.莫尔查诺夫（萨拉托夫）7-9、11、12； D. Myakshev（安加尔斯克）11； R.纳博科夫（莫斯科）4、7； S. Nadtochiy（莫斯科）4、6-9、11、12； A.纳扎连科（基辅）6-9、11； M. Nylovzen（巴库）16； D. Nishinaidze (库坦西) 8; D. Nozdrin (萨拉托夫) 4, 6; S. Obochevets（列宁格勒）6、7； D. Ovsyannikov（列宁格勒）4、6-9、12； S. Odintsova（基辅）4、6、7、11； A. Orlov（结尾见第 55 页）
