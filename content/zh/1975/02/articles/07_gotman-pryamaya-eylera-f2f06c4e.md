---
id: 1975-2-gotman-pryamaya-eylera-f2f06c4e
issue: kvant_1975_2
year: 1975
number: "2"
title: 欧拉线
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 27
page_labels: 20-24
tag: MFX4
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b32076dea336f6a870ee0b3608242461d187d4e3c7b6f9bba7876700c0c8a665
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/07_gotman-pryamaya-eylera-f2f06c4e.md
source_content_sha256: 3f3cbbb4899e8c4287d4fe9ea8a050319fb0733431448317e8680e62a75e8dfd
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

古希腊人对三角形的性质进行了深入研究。

欧几里得的《几何原本》证明，三角形外接圆的圆心是椎间盘中线与其各边的交点。

阿基米德确定了均匀三角形板的重心位置，发现它位于三个中线的每一个上。三角形中线的交点称为柔软中心或三角形的中心。

后来证明，三角形的三个高也交于一点，该点称为三角形的垂心。

三角形的三个显着点——外接圆圆心O、质心G和原心H——位置的规律性是由著名数学家莱昂哈德·欧拉（Leonhard Euler，1707-1783）首先发现的。让我们首先研究一个特殊情况：直角三角形 ABC (图 1)。

斜边AB的中点O是其外接圆的圆心。从顶点C开始计算，中心G以2:1的比例除中值CO。AC和BC边是三角形的高，因此直角的顶点C与三角形的垂心H重合。因此，点 O、G、H 位于同一条直线上，且$\overrightarrow{OH} = 3\overrightarrow{OG}$。欧拉利用坐标法证明了三个指示点之间或围绕一个三角形存在相同的连接。我们将使用向量证明这一事实，并且要求读者只熟悉最简单的运算：向量相加以及向量乘以数字。

给定关系中的段划分

设A、B、O为平面上的给定点，已知点G以k：$\frac{\overrightarrow{AG}}{\overrightarrow{GB}} = k$(图2)的比例划分线段AB。让我们用向量 $\overrightarrow{OA}$ 和 $\overrightarrow{OB}$ 来表达向量 $\overrightarrow{OG}$。为此，我们将通过 $\overrightarrow{OG}$、$\overrightarrow{OA}$ 和 $\overrightarrow{OB}$ 的所有向量的表达式代入等式 $\overrightarrow{AG} = k \times \overrightarrow{GB}$：$\overrightarrow{OG} - \overrightarrow{OA} = k (\overrightarrow{OB} - \overrightarrow{OG})$。求解 $\overrightarrow{OG}$ 方程，我们得到

$$\overrightarrow{OG} = \frac{\overrightarrow{OA} + k\overrightarrow{OB}}{1 + k}.$$ (1)

例如，如果 G 是线段 $\overrightarrow{AB}$ 的中点，则$k = 1$ 和 $\overrightarrow{OG} = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB})$。

三角形中线交于一点的定理

这里我们获得了一个向量等式，稍后我们将需要它。

⟦folio 21⟧

定理1.瞬态$ABC$的药物相交于一点$G$，从顶点开始按2:1的比例划分，得
$$3\overrightarrow{PG} = \overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC},$$
(2)
food $P$ - 平面或空间的任何点。
证明。在三角形 $ABC$ 的中线 $CD$ 上，我们取点 $G$，由对应关系 $|CG| : |GD| = 2:1$ (图 3) 确定。根据式（1），
$$\overrightarrow{PG} = \frac{\overrightarrow{PC} + 2\overrightarrow{PD}}{3},$$
$$\overrightarrow{PD} = \frac{1}{2} (\overrightarrow{PA} + \overrightarrow{PB}),$$
在哪里
$$\overrightarrow{PG} = \frac{1}{3} (\overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC}).$$
通过计算以点 $G'$ 为终点的向量 $\overrightarrow{PG}$ 按 2:1 的比例除以三角形的另外两个中线（从顶点开始计算），我们得到右侧相同的表达式：
$$\overrightarrow{PG'} = \frac{1}{3} (\overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC}),$$
姿势$\overrightarrow{PG'} = \overrightarrow{PG}$，点$G'$与点$G$重合。因此，三角形的所有三个中线都相交于一点 $G$，由对应关系 (2) 确定。

任意三角形的高度定理
定理2. 三角形$ABC$的高相交于一点$H$，并且
$$\overrightarrow{OH} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC},$$
(3)
food $O$ 是三角形外接圆的圆心。
证明。令 $ABC$ 为非直角三角形 (图 4)。让我们求向量 $\overrightarrow{OA}$ 和 $\overrightarrow{OB}$ 的和。为了这

⟦folio 22⟧

让我们构造一个相对于边 $AB$ 与 $O$ 对称的点 $M$，然​​后是 $\overrightarrow{OM} = \overrightarrow{OA}+\overrightarrow{OB}$。然后我们构造点$H$，其中

$$\overrightarrow{OH} = \overrightarrow{OM}+\overrightarrow{OC} = \overrightarrow{OA}+\overrightarrow{OB}+\overrightarrow{OC},$$

并证明点$H$是三角形$ABC$的重心。

事实上，通过构造，线$CH$和$OM$是平行的，$OM$是线段$AB$的垂直平分线，因此，线$CH$也垂直于线$AB$，点$H$位于从顶点绘制的三角形$ABC$的高处$C$。

如果我们从向量$\overrightarrow{OA}$和$\overrightarrow{OC}$开始重复构建，我们将得到相同的点$H$，但同样的推理表明，现在点$H$位于从顶点$B$绘制的三角形的高度上。类似地，我们发现点$H$位于从顶点$A$绘制的高度上。因此，三角形$ABC$的高交于点$H$，由关系式（3）确定。

很容易验证定理 2 对于直角三角形也成立。

**欧拉直线**

根据已证明的定理 1 和 2，我们感兴趣的三角形显着点的性质如下。

定理3. *任意三角形的外接圆圆心$O$、质心$G$和垂心$H$位于同一直线上，点$G$位于点$O$、$H$和$|OG| : |GH| = 1 : 2$之间。*

证明。由定理1

$$3\overrightarrow{OG} = \overrightarrow{OA}+\overrightarrow{OB}+\overrightarrow{OC}.$$

将这个等式与等式（3）进行比较，我们得到

$$\overrightarrow{OH} = 3\overrightarrow{OG}.$$

因此，具有共同原点 $O$ 的向量 $\overrightarrow{OH}$ 和 $\overrightarrow{OG}$ 位于

⟦column⟧

妻子在同一条直线上并且$|\overrightarrow{OG}| : |\overrightarrow{GH}| = 1 : 2$。

点 $O$、$G$ 和 $H$ 所在的直线称为*欧拉直线*。

$$* \quad * \quad *$$

在立体测量中，最简单的多面体——四面体（三棱锥）在平面测量中起着与三角形相同的作用。三角形和四面体的性质在很大程度上相似。让我们尝试将三角形的显着点的性质扩展到四面体。

**围绕四面体外接的球体**

众所周知，围绕任何四面体都可以描述一个球体，其中心 $O$ 位于四面体面的垂直线上，构建在围绕面描述的圆的中心处。

**四面体的中线**

连接四面体的顶点与相对面的质心的线段称为四面体的“中线”。四面体中线的性质与三角形中线的性质相似。

定理 4. *四面体 $ABCD$ 的四个中线相交于一点 $G$，从四面体的顶点开始计算，将它们按比例 $3:1$ 分开，并且*

$$4\overrightarrow{PG} = \overrightarrow{PA}+\overrightarrow{PB}+\overrightarrow{PC}+\overrightarrow{PD}, \quad (4)$$

*其中$P$是空间中的任意点。*

证明。让我们取四面体$ABCD$的中线$DG_1$上的点$G$，由关系$|DG| : |GG_1| = 3:1$ (图 5) 定义。根据式（1），

$$\overrightarrow{PG} = \frac{\overrightarrow{PD}+3\overrightarrow{PG_1}}{4}.$$

考虑三角形$ABC$的质心$G_1$满足关系式$3\overrightarrow{PG_1} = \overrightarrow{PA}+\overrightarrow{PB}+\overrightarrow{PC}$，可得

⟦folio 23⟧

$$\vec{PG} = \frac{1}{4}\left(\vec{PA} + \vec{PB} + \vec{PC} + \vec{PD}\right).$$

通过计算以点$G'$为终点的向量$\vec{PG'}$除以四面体的其他三个中线中的任意一个，以比率$3:1$（从顶点开始计算），我们得到相同的表达式。这意味着四面体的所有四个中线都相交于一点$G$，满足关系式（4）。点 $G$ 称为四面体的*重心*（或*质心*）。

**四面体高度**

三角形的高总是相交于一点。以此类推，我们可以假设任何四面体的高度也相交于一点。然而，事实并非如此。

例如，考虑在边 $AB$ 处具有直二面角的四面体 $ABCD$，其中 $|AC| = |BC|$ 但 $|AD| \neq |BD|$ (图 6)。四面体的高$CE$和$DF$分别位于面$ABC$和$ABD$，但点$E$是$AB$的中间，$F$不是。如果边$DA$和$DB$的长度相等，则高度的底$E$和$F$将重合，但四面体的其他两个高度不能通过点$E$。

因此，即使四面体的两个高度也可能没有公共点。

然而，也存在四面体，其所有四个高度都相交于一点。例如，这将是在顶点 $D$ 处具有直角的四面体 $ABCD$。边 $DA$、$DB$ 和 $DC$ 是其高度，顶点 $D$ 是*正交中心*（所有四个高度的交点）。

让我们尝试找到所有高度相交于一点的四面体。

让从顶点 $C$ 和 $D$ 绘制的四面体 $ABCD$ 的高度相交于点 $H$ (图 7)。那么$CH_1 \perp AB$和$DH_2 \perp AB$，即直线$AB$垂直于两者

⟦column⟧

⟦figure⟧
图 5.

⟦figure⟧
图 6.

⟦figure⟧
图 7.

⟦figure⟧
图 8.

**23**

⟦folio 24⟧

与 CDH 平面内的直线相交，因此 AB⊥CD。同样证明，如果四面体ABCD的另外两个高经过同一点H，则AC⊥BD和AD⊥BC。因此，如果四面体的所有高度相交于一点，则四面体的相对边缘相互垂直。这样的四面体称为正交中心。

定理5。如果正交中心太面体ABCD的高度相交于一点，则太面体的相对边缘相互垂直。这样的四面体称为正交中心。

定理5。如果正交中心太面体ABCD的高度相交于一点，则太面体的相对边缘相互垂直。这样的四面体称为正交中心。

设 ABCD 为正交中心四面体，DG₁ 为中线，DH₁ 为高度 (图 8)。那么G₁是质心，H₁是三角形ABC的重心（你自己证明一下——这就是使用四面体相对边的垂直度的地方），点O₁（三角形ABC的外接圆的中心），G₁和H₁位于同一条直线上。请注意，围绕太面体 ABCD 外接的球体中心 O 位于三角形 ABC 平面的垂直线上，并在点 O1 处恢复。

我们将以与三角形定理 2 相同的方式证明该定理：以不同方式构造满足（5）的点 H。

首先，将向量 $\overrightarrow{OA}$、$\overrightarrow{OB}$ 和 $\overrightarrow{OC}$ 相加：

$$\overrightarrow{OM} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}.$$

根据定理 1 $\overrightarrow{OG}_1 = \frac{1}{3}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC})$，因此 $\overrightarrow{OM} = 3\overrightarrow{OG}_1$ 或 $\overrightarrow{G}_1\overrightarrow{M} = 2\overrightarrow{OG}_1$。点 O₁、G₁、H₁ 位于三角形 ABC 和 $\overrightarrow{H}_1\overrightarrow{G}_1 = 2\overrightarrow{G}_1\overrightarrow{O}_1$ 的欧拉线上。因此，

$$\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OM} + \overrightarrow{OD}) = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$$

由此可见，直线H 1 M 和OO 1 平行，并且由于直线OO 1 垂直于平面ABC，因此直线H 1 M 垂直于该平面。因此，点 M 位于直线 DH₁ 上（如果点 O 和 O₁ 重合，则点 M 和 H₁ 也重合）。

设理论$\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OM} + \overrightarrow{OD}) = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$ 由左等式可得H点为线段DM的中点，即H点位于四面体的高度DH₁处。

类似地，构造点N：$\overrightarrow{ON} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OD}$，也$\overrightarrow{H}:\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{ON} + \overrightarrow{OC})$，并证明点H位于从顶点C绘制的四面体的高度上，等等。

因此，正交中心四面体的高度相交于一点 H，由相应的 (5) 确定。

四面体欧拉线

定理6 外接球的切尼尔O、切尼罗德G和正交中心四面体ABCD位于同一直线上，且O点和H点相对于G点对称。

证明。根据式（4）和（5）

$$\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD}),$$

$$\overrightarrow{OG} = \frac{1}{4}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD}),$$

从哪里$\overrightarrow{OH} = 2\overrightarrow{OG}$。由此产生的相等意味着点 O、G、H 位于同一条直线上，并且点 O 和 H 相对于点 G 对称。

⟦folio none⟧

点$O$、$G$、$H$所在的直线可称为*正交中心四面体的欧拉直线。*

练习

使用向量的标量积来解决问题 1-4。

1. a) 证明如果$O$是三角形$ABC$和$\overrightarrow{OH} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}$外接圆的圆心，则$H$是三角形高的交点。

b) 证明如果$O$是正交中心四面体$ABCD$和$\overrightarrow{OH} = {}^{1}\!/_{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$外接球的中心，则$H$是四面体四个高的交点。

2. 证明如果$A$、$B$、$C$和$D$是空间中的任意四个点，则

$\overrightarrow{AB} \cdot \overrightarrow{CD} + \overrightarrow{BC} \cdot \overrightarrow{AD} + \overrightarrow{CA} \cdot \overrightarrow{BD} = 0.$

利用这个等式，证明

a) 三角形的三个高相交于一点；

b) 如果四面体$ABCD$的对边$AB$和$CD$、$AD$和$BC$垂直，则边$CA$和$BD$也垂直。

3. 证明如果$A$、$B$、$C$、$D$是空间中的任意四个点，则

$$|AB|^2 + |CD|^2 - |AD|^2 - |BC|^2 = 2\overrightarrow{AC} \cdot \overrightarrow{DB}.$$

利用这个等式，证明

a) 梯形对角线的平方和等于其各边的平方和加上两倍底边乘积；

b) 四边形的对角线垂直当且仅当对边的平方和相等；

⟦column⟧

c) 对于正交中心四面体，其相对边的平方和相等是必要且充分的。

4. 证明正交中心四面体一个顶点处的所有平面角都是锐角、直角或钝角，并且其至少一个面是锐角三角形。

5. a) 证明三角形$ABC$的垂心$H$相对于其边的中点对称的点，以及垂心$H$相对于直线$BC$、$CA$和$AB$对称的点位于该三角形的外接圆上。

b) 设$H$为四面体$ABCD$的重心，$G_1$和$H_1$分别为面$ABC$的质心和重心，$G_2$和$H_2$为$\overrightarrow{HG_2} = 3\overrightarrow{HG_1}$和$\overrightarrow{HH_2} = 3\overrightarrow{HH_1}$的点。证明点 $G_2$ 和 $H_2$ 位于该四面体的外接球面上。

6. a) 证明三角形三边的中点、三个高的底边以及三个顶点与垂心的线段的中点位于同一个圆上，且该圆的圆心（称为“十点圆”）位于欧拉线上。

b) 证明四个面的质心、垂心四面体的四个高的底边以及垂心与顶点相连的各线段的分割点（从垂心开始计算）按 1:2 的比例位于同一球面上，且该球面（称为“十二点球面”）的中心位于欧拉直线上。

7. 证明

a) 如果四面体的一个高的底是相应面的正交中心，则该四面体是正交中心的；

b) 正交中心四面体的任何高的底是相应面的正交中心（这些性质用于证明定理 5）。

---
