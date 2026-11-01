---
id: 1979-5-krayzman-zamenim-figuru-7c8c1738
issue: kvant_1979_5
year: 1979
number: "5"
title: 我们来替换一下图
authors:
  - Крайзман М. Л.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 36
page_last: 39
page_labels: 34-37
tag: INAT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ddc51a33fb19586d9af67b83e62c8546a22d2e9a04ddbe4b82a78635a3d6df30
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/13_krayzman-zamenim-figuru-7c8c1738.md
source_content_sha256: 47a69af924e55223d88a5dc5ebd3a492ff000959a47d8afd66ddadb6015bfff3
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

M·克赖兹曼

我们来替换一下图

众所周知，变量变换法在代数中应用广泛。同样有效的是，“替换”可以应用于几何学。这种解决几何问题的技术如下：将问题条件下的所讨论的图形替换为具有相同期望值的图形，以便更容易找到该值。

在前两个问题中，解决最简单的替换问题——用一个段替换另一个段。

任务 1. 从节点 AOB 外部取的点 C（等于 60°），省略对应于该节点的边 OA、OB 和平分线 ON 的变量 CD、CM 和 CN。确定 |ON|如果 |CM|=d₁ 且 |CD|=d2。

解决方案。令E和P为(CN)与(OB)和(OA)的交点(图1)。由此产生的三角形 OEP 非常坚忍。对图的分析导致了用全等线段EF替换线段ON的想法，其中(EF)⊥(OP)：线段EF的长度很容易与线段CD和CM的给定长度相关。

让我们做[EK]⊥[CD]（参见图1）；

然后
|EF| = |KD| = |CD| — |CK| = = |CD| — |CM| = d₂ — d₁.
我们在这里假设 d2>d1。 d 1 >d 2 的情况如图 2 所示，与d 2 >d 1 的情况类似。最终答案：|开| = |d₁—d2|。

任务2. 在等边三角形ABC (|AB|=|BC|) 中，从顶点A 到边BC 绘制垂线AD。半圆内切于三角形ABD和ACD，因此它们的直径对应于[BD]和[AD]。如果节点 B 的大小等于 π/4，求这些半圆的面积之比。

解决方案。如果考虑到$\frac{S_1}{S_2} = \left( \frac{r_1}{r_2} \right)^2$，那么只要确定其上的半圆半径之比就可以找到所需的值；为此，我们将半径 O₁M (图 3) 替换为与之相等的线段，该线段是具有已知锐角的直角三角形的斜边。由于$\widehat{B} = \frac{\pi}{4}$，有|AD|=|BD|，|MB|=|MO₁|=r₁。考虑到 |AD|=|AM|和|BA|=|BC|，我们得到|MB|=|CD| — 段 MB 可以用段 CD 代替。在直角三角形 O2CD 中

⟦folio 35⟧

图 4. 图 5. 图 6.

$$\widehat{O_2CD} = \frac{1}{2} \widehat{ACD} = \frac{3\pi}{16};$$
因此$$\frac{S_1}{S_2} = \text{ctg}^2 \frac{3\pi}{16}.$$

在接下来的三个任务中，我们将替换更复杂的形状（三角形、paramid）。

问题3 在这个三角形中，用长度最短的对角线内切一个矩形，使得三角形（或其延长线）的一条边包含两个顶点，另外两条边包含该矩形的一个顶点。

解决方案e.如果这个问题不是关于任意三角形，而是关于与给定矩形有公共直角的矩形，那么解决方案不会造成任何困难：所需的矩形将是对角线垂直于三角形斜边的矩形（图4）。让我们尝试用直角三角形替换该三角形，该直角三角形具有与所需三角形全等的内切矩形。

令 $B_1AC$ 为直角三角形 ($\hat{A} = 90^\circ$)，其底边 $AC$ 和 $(B_1B) \parallel (AC)$ (图 5)。然后$|M_1N_1| = |MN|$（证明）。在三角形 $B_1AC$ 中，我们用最小对角线 (图 5) 内接一个矩形 $AM_1N_1K_1$。线 $M_1N_1$ 将分别与边 $BA$ 和 $BC$ 相交于点 $M$ 和 $N$。我们来做$[MF] \perp [AC]$和$[NK] \perp [AC]$。直角三角形$FMNK$就是我们要找的三角形。

问题 4. 证明圆角器 $AHB, BHC$ 和 $AHC$ 所描述的圆的半径，

另一个$H$是锐角三角形$ABC$高的交点，彼此相等。

解决方案e.让我们将这些三角形之一（例如，$\Delta BHC$）标记为构造三角形，并找到该三角形的外接圆的半径。

1 种方式。通过顶点$B$，我们画一条平行于高度$CK$的线，通过$C$画一条平行于高度$BM$的线；设 $F$ 为这些线的交点 (图 6)。

四边形$BHCF$是平行四边形，因此$\Delta BFC \cong \Delta BHC$。考虑四边形 $ABFC$：

$$\begin{pmatrix} [FB] \\ [CK] \\ [FC] \\ [BM] \end{pmatrix} \Rightarrow \begin{pmatrix} \widehat{ABF} \\ \widehat{ACF} \\ 90^\circ \end{pmatrix}.$$

因此，点$A, B, F$和$C$位于同一个圆上，因此$R_{\triangle ABC} = R_{\triangle BFC}$（$R_{\triangle ABC}$表示圆角$\Delta ABC$外接圆的半径）。

($\Delta BFC \cong \Delta BHC$) $\Rightarrow (R_{\triangle BFC} = R_{\triangle BHC})$.

接下来$$\begin{pmatrix} R_{\triangle ABC} = R_{\triangle BFC} \\ R_{\triangle BFC} = R_{\triangle BHC} \end{pmatrix} \Rightarrow (R_{\triangle ABC} = R_{\triangle BHC}).$$

类似地可以证明$R_{\triangle AHB} = R_{\triangle AHC} = R_{\triangle ABC}$。

方法二：将圆三角形$ABC$描述为圆，并延伸其高度$AP$，直到与所画圆相交于点$E$（图7）。请注意 $\widehat{CBM} = \widehat{PAC}$（这些角度中的每一个都由角度 $ACB$ 到 $90^\circ$ 补足）和 $\widehat{PAC} = \widehat{CBE}$

⟦folio 36⟧

（它们中的每一个都以它们所在的圆弧 EC 的角度大小的一半来测量）；因此$\angle CBE \cong \angle CBH$。我们同样证明$\angle BCE \cong \angle BCH$。因此，$\triangle BEC \cong \triangle BHC$，因此，$R_{\triangle BEC} = R_{\triangle BHC}$。

A、B、C、E 点在同一个圆上，所以$R_{\triangle BEC} = R_{\triangle ABC}$。最后我们得到$R_{\triangle BHC} = R_{\triangle ABC}$。

类似地证明三角形AHB和AHC外接圆的半径等于三角形ABC外接圆的半径。

任务 5*)。给定一个以 ABCD 和 $A_1B_1C_1D_1$ 为底的立方体。如果立方体的边为 1，则求多面体 AD$_1$EF 的体积，其中 E 是边 DC 的中点，F 是边 BB 的中点。

解决了并且e。让我们通过点 D$_1$ 画一条平行于 [AF] (图 8) 的线 l。

$$\begin{pmatrix} l & \| [AF] \\ [AF] \subset (AA_1B_1) \end{pmatrix} \Rightarrow (l \| (AA_1B_1)).$$

由于$D_1 \in (DD_1C_1)$和$(DD_1C_1) \parallel (AA_1B_1)$，通过点D$_1$平行于$(AA_1B_1)$绘制的任何线（部分为线l）都将位于面DD$_1C_1C$的平面内。让$l \cap (DC) = K$。从 $(D_1K) \parallel [AF]$ 和 $[AF] \subset (AFE)$ 的事实，我们得到 $(D_1K) \parallel (AFE)$，因此 rectida D$_1$AFE 的大小与 paramida KAFE 相等（它们有一个共同的基 -

*) 这个问题是在 1969 年莫斯科国立大学物理学院入学考试中提出的。

图 7.

图 8.

图 9.

⟦folio 37⟧

考虑到$\overrightarrow{AD}_1C + \overrightarrow{CAD}_1 + \overrightarrow{ACD}_1 = 180^\circ$（三角形内角之和），我们得到$\overrightarrow{AB}_1D_1 + \overrightarrow{AB}_1C + \overrightarrow{CB}_1D_1 = 180^\circ$。

问题7. 证明连接顶点为直三面角的四面体相交边的中点的线段长度等于给定四面体外接球的半径。

解决方案。互补四面体 $ABCD$，顶点 $A$ 与直角平行六面体 $ABKCDLMN$ (图 10) 具有直角平面。围绕给定平行六面体描述的球体也将围绕四面体 $ABCD$ 描述。从三角形$AKD$可以得出$|PQ| = \frac{1}{2}|DK|$。由于平行六面体的对角线 $DK$ 是外接球体的直径，因此线段 $PQ$ 的长度等于该球体的半径。

问题 8. 直立平行六面体的边长为 1、2 和 3。确定该四面体相邻侧面的交叉对角线之间的距离。

解决方案。考虑四面体 $DB_1C_1C$ (图 11)，而不是平行六面体 $ABCDA_1B_1C_1D_1$。这个四面体的体积是

$$V = \frac{1}{3} S_{\triangle B_1C_1C} \cdot |DC| = \frac{1}{3} \left( \frac{1}{2} \cdot 1 \cdot 3 \right) \cdot 2 = 1.$$

现在让我们找到它的体积，使用对应关系$V = \frac{1}{6} \times l_1 \cdot l_2 \cdot d \cdot \sin \varphi^*$，其中$l_1$和$l_2$是这个四面体交叉边的长度，$d$和$\varphi$是它们之间的距离和角度。我们得到

$$V = \frac{1}{6} |B_1C| \cdot |DC_1| \cdot d \cdot \sin \overrightarrow{AB}_1C = \frac{1}{6} \sqrt{50} \cdot d \cdot \sin \varphi.$$

在三面角$BACB_1$中，与直二面角的边$B_1B$相对的平面角$\varphi$的余弦等于限制该直二面角的平面角的余弦的乘积，即

$$\cos \overrightarrow{AB}_1C = \cos \overrightarrow{AB}_1B \cdot \cos \overrightarrow{BB}_1C;$$

从这个等式我们得到

$$\cos \overrightarrow{AB}_1C = \frac{1}{\sqrt{5}} \cdot \frac{1}{\sqrt{10}} = \frac{1}{\sqrt{50}};$$

$$\sin \overrightarrow{AB}_1C = \sin \varphi = \frac{7}{\sqrt{50}}.$$

因此，

$$V = \frac{1}{6} \sqrt{50} \cdot d \cdot \frac{7}{\sqrt{50}} = \frac{7}{6} d.$$

从等式（1）和（2）得出$1 = \frac{6}{7} d$。

因此$d = \frac{6}{7}$。

让我们提出一种替换，其中替换四面体的三个侧边是替换四面体的侧面的中线。

*) 这个公式也可以用替换法来证明！
