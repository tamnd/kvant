---
id: 1991-10-ponarin-garmonicheskiy-chetyirehugolnik-ea9f279f
issue: kvant_1991_10
year: 1991
number: "10"
title: 调和四边形
authors:
  - Понарин Я. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 50
page_last: 54
page_labels: 48-52
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 735c9a6b5d981a83b87e528a07f41dc2aca0e579ad9eae6aae39671d70be76c2
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/15_ponarin-garmonicheskiy-chetyirehugolnik-ea9f279f.md
source_content_sha256: a8db9df0b6a7c3d331af97a6fe4e6917516c9e5c1e78ce8367281b69cabd83e2
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

---
running_head:
folio:
---

= $\frac{AM}{MB}$， 和 $\lambda > 0$，如果向量 $\vec{AM}$ 和 $\vec{MB}$ 匹配，并且 $\lambda < 0$，如果它们的方向相反（您可以很容易地看到这个比率可以像普通分数一样对待）。*）

如果给定点是$A$、$B$和$\lambda = \frac{AM}{MB} \neq -1$，则点$M$是唯一定义的。事实上，让我们假设我们找到两个点 $M$ 和 $N$ 使得

$$\frac{AM}{MB} = \frac{AN}{NB}.$$

让我们在这个等式两边都加 1：

$$\frac{AM}{MB} + \frac{MB}{MB} = \frac{AN}{NB} + \frac{NB}{NB}.$$

然后

$$\frac{AM}{MB} + \frac{MB}{MB} = \frac{AN}{NB} + \frac{NB}{NB},$$

IE。

$$\frac{AB}{MB} = \frac{AB}{NB},$$

方法，

$$\overrightarrow{MB} = \overrightarrow{NB} \text{ и } M = N.$$

通常认为点 $M$ 相对于 $\lambda$ 划分线段 $AB$。请注意，一个点可以在线段之外分割线段！

对于$\lambda > 0$，点$M$属于线段$AB$，对于$\lambda < 0$，它位于线段$AB$上。特别地，如果$\lambda = 1$，则$M$是$AB$的中间；如果$\lambda = -1$，这意味着$\overrightarrow{AM} = -\overrightarrow{MB}$，即点$A$和$B$重合。因此，$\lambda = -1$应该被我们排除（如果$A$和$B$重合，则$M$点给出的不完整）。

关于极限。直线 ($A, B; C, D$) 上的有序四元组称为调和，如果该点

*) 为了区分有向线段的比率与其长度的比率，我们将在线段名称上方放置一条线，作为在其上给出方向的标志。

⟦folio 49⟧

---
running_head:
folio:
---

书 C 和 D 将线段 AB 划分为仅符号不同的关系：

$$\frac{AC}{CB} = -\frac{AD}{DB}.$$ 在这种情况下，A、B 点对称为基本点，C、D 点对称为除法。

然而，基和除法对可以颠倒，因为如果 $$\frac{AC}{CB} = -\frac{AD}{DB},$$ 那么也$$\frac{CA}{AD} = -\frac{CB}{BD}.$$ 换句话说，如果有序四（A，B；C，D）是调和的，那么有序四（C，D；A，B）也将是调和的。

亲自检查一下，如果更改基本对或分隔对中的点的顺序，是否会保留四个点的和谐。

谐波四元点很常见，尽管您可能没有替换它们。这是一个例子。给定一个三角形ABC，其内角和外角的二等分线在顶点C处与直线AB相交于点M和N（图2）。那么有序四元组 (A, B; M, N) 是调和的，因为众所周知，

$$\frac{AM}{MB} = \frac{AC}{BC} \text{ и } \frac{AN}{NB} = -\frac{AC}{BC}.$$

锻炼。证明调和四元组 (A, B; C, D) 完全由其第三点决定。

图 3 展示了如何根据其他点构建第四个点 D。这里，通过点A和B，任意绘制两条彼此平行的直线，并且通过点C，绘制一条直线，分别与它们相交于点P和Q。直线 BQ 上的点 S 使得 QB=BS。那么直线 PS 和 AB 的交点就是所要求的点。

锻炼。证明这样构造的点确实是调和四元组的缺失点。

当点 C 位于线段 AB (图 4) 之外时，相同的构造允许我们找到丢失的点 D。

锻炼。找出上述构造方法中的差距（提示：记住缺少值$\lambda = -1$）。

现在一切都已准备好呈现给您

谐波四边形

决定。如果圆内切四边形的对边长度的乘积相等，则该四边形称为调和四边形。

⟦folio 50⟧

---
running_head:
folio:
---

从这个定义来看，调和四边形与点的调和四边形之间的联系尚不清楚。下面就会清楚了。

调和四边形的一个明显例子是内切三角线 (图 5)，这是一种具有垂直对角线的四边形，其中一个对角线平分另一个。特别地，它可以是正方形。

另一种特殊类型的和谐四边形是调和梯形 (图 6)。很明显，它是等边的。设 $AB$ 和 $CD$ 为调和梯形 $ABCD$ 的底。让我们表示 $AB=a$、$CD=b$、$AD=BC=c$、$AC=BD=d$。根据调和四边形$ab=c^2$的定义，调和梯形的边长为其底边的几何平均数。此外，在任何循环四边形中，对角线长度的乘积等于其对边的乘积之和（托勒密定理*））。因此，$d^2=ab+c^2$，因此，$d^2=2c^2$，因此$d=c\sqrt{2}$，即边长为$c$的调和梯形的对角线等于边长为$c$的正方形的对角线。如果外接圆的半径为 $R$，则为 $d<2R$，因此为 $c<R\sqrt{2}$（在相等 $c=R\sqrt{2}$ 的情况下，梯形变为内接正方形）。

因此，调和梯形可以由两个底$a$和$b$定义，并简单地构造其侧边和对角线。它还可以通过外接圆和侧边的半径来指定，借助它可以轻松找到所有其他元素。

现在让我们考虑一下

调和四边形的一般性质

让我们一致认为，在四边形 $ABCD$ 中，边 $AB$ 和 $BC$

*) 例如，参见 «Kvant»，1991 年，第 4 期，第 4 页。 42.

与对角线 $AC$ 相邻。边 $AD$ 和 $DC$ 也与其相邻。

定理 1. 在调和四边形中，每条对角线都除以它们相对于相邻边的平方的交点。

事实上，考虑和谐四边形$ABCD$。令 $M$ 为其对角线的交点 (图 7)。三角形

⟦folio 51⟧

---
running_head:
folio:
---

$$AM \cdot MC = BM \cdot MD$$ 和 $$\frac{BM}{MC} = \frac{AB}{CD}.$$

根据三角形 AMD 和 BCM 的相似性，我们也有
$$\frac{MD}{MC} = \frac{AD}{BC}.$$

逐项获得的变量比例：
$$\frac{BM \cdot MD}{MC^2} = \frac{AD \cdot AB}{BC \cdot CD}.$$

但$AM \cdot MC = BM \cdot MD$因此
$$\frac{AM \cdot MC}{MC^2} = \frac{AD \cdot AB}{BC \cdot CD},$$
或者
$$\frac{AM}{MC} = \frac{AD \cdot AB}{BC \cdot CD}.$$ (*)

由于四边形 ABCD 是调和的，则 $AD \cdot BC = AB \cdot CD$，因此
$$CD = \frac{AD \cdot BC}{AB}.$$

将这个表达式代入(*)，我们得到
$$\frac{AM}{MC} = \frac{AD \cdot AB}{BC} \cdot \frac{AB}{AD \cdot BC} = \frac{AB^2}{BC^2}.$$

同样地
$$\frac{AM}{MC} = \frac{AD^2}{DC^2}$$ 和 $$\frac{BM}{MD} = \frac{BC^2}{CD^2} = \frac{AB^2}{AD^2}.$$

评论。我们知道，穿过三角形的顶点并将其对边与相邻边的平方分开的直线相对于该顶点处的角度平分线关于中线对称。它被称为三角形的西中线*)。

定理2.和谐四边形的两个对角顶点，其对角线的交点和直线的交点。
*) 您可以在 S.I. Zetel 所著的《New Geometry of the Triangle》（Uchredgiz，1962 年，第 100-103 页）一书中阅读更多相关内容。

我的包含这些顶点，在第三个顶点处与外接圆相切，形成一个和谐的四边形四鸭点。

事实上，顶点 B 处的空切线与直线 AC 相交于点 P (图 8)。然后$\angle BAC = \angle CBD$（要确信这一点，记住垂直角等于中心角的一半就足够了，基于相同的弧）；因此，三角形 BCP 和 BAP 相似。波佐托穆
$$AP \cdot PC = BP^2$$
和
$$\frac{BP}{PC} = \frac{AB}{BC}.$$

将第一个等式两边除以 $PC^2$，我们得到
$$\frac{AP}{PC} = \frac{BP^2}{PC^2}$$

因此
$$\frac{AP}{PC} = \frac{AB^2}{BC^2}.$$

如果我们现在将定理 1 应用到和谐四边形并考虑向量的方向，我们最终得到：$$\frac{AM}{MC} = -\frac{AP}{PC}$$。点 M 和 P 将线段 AC 分为

⟦folio 52⟧

---
running_head:
folio:
---

和外部具有相等的轴幅关系。

结果。调和四边形的外接圆在其相对顶点处的切圆相交于包含其对角线或平行于该对角线的直线上。

事实上，如果在顶点$D$处画一条切线，那么根据定理2，它将与线$AC$相交于一点，该点与相同的点$A, C, M$一起构成四单位谐波。当然，这个性质也适用于顶点 $A$ 和 $C$ 处的切线。切线和对角线的平行发生在除数的情况下。

定理3。如果内接四边形的一条对角线两端的切线与包含第二条对角线的直线相交或平行，则该四边形是调和四边形。

事实上，定理 2 的证明得出了等式 $\frac{AP}{PC} = \frac{AB^2}{BC^2}$，这对于任何循环四边形 $ABCD$ 都是成立的。根据条件，点 $D$ 处的切线与 $AC$ 相交于同一点 $P$，因此也有 $\frac{AP}{PC} = \frac{AD^2}{DC^2}$。因此，$\frac{AB}{BC} = \frac{AD}{DC}$，即四边形$ABCD$是调和的。

该定理是给定顶点 $A, B$ 和 $C$ 构造和谐四边形 $ABCD$ 的方法的基础。

我们围绕三角形$ABC$画一个圆，并通过顶点$B$画一条切线。如果线段 $AB$ 和 $BC$ 不相等，则它将与线 $AC$ 相交于某个点 $P$。现在只需通过 $P$ 画圆的第二条切线，我们就会得到和谐四边形的缺失顶点。如果$AB=BC$且$B$点的切线与$AC$平行，这意味着所需的四边形是约数，因此ver-
总线$D$是垂直于$AC$的中线与圆的交点。在一般情况下，您可以采取稍微不同的做法：如果 $K$ 是给定顶点 $A$ 和 $C$ 处切线的交点，则顶点 $D$ 是线 $BK$ 与圆的第二个交点。

定理4. 在调和四边形中，距各边对角线do 交点的距离与这些边的长度成正比。

看一下图 9。让我们表示点$M$到相应$h_1, h_2, h_3, h_4$的线$AB, BC, CD, DA$的距离。三角形$AMB$和$BMC$的面积之比为$AM:MC$。另一方面，这些相同面积的比率是$\frac{AB \cdot h_1}{BC \cdot h_2}$。根据定理 1 $\frac{AM}{MC} = \frac{AB^2}{BC^2}$，因此$h_1:h_2 = AB:BC$。与$h_2:h_3 = BC:CD$和$h_3:h_4 = CD:DA$类似。

最后，还有一点要注意。四个完整的数 $a, b, c, d$ 形成一个和谐的四边形，如果

$$\frac{a-b}{b-c} = -\frac{a-d}{d-c}.$$

我们今年的下一期杂志介绍了 Yu 的一篇文章。索洛维约夫论完全数，其中特别描述了它们的几何表示。每个数字$a, b, c, d$对应于平面$A, B, C, D$上的一个点。如果所有数构成和谐四边形，则$ABCD$是和谐四边形，反之亦然。
