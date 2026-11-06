---
id: 1991-3-orach-teorema-menelaya-c94304d0
issue: kvant_1991_3
year: 1991
number: "3"
title: 墨涅拉俄斯定理
authors:
  - Орач Б. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 57
page_labels: 52, 53, 55
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0696fbdb4b69c65d535826509a10d5411339a89faffc4d36425d83e53b474ba4
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/17_orach-teorema-menelaya-c94304d0.md
source_content_sha256: 82ec5a6e53dead7e4f0100ae96dea9cfc5307ae6e6b425582757d58b061e6705
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 52⟧

---
running_head:
folio:
---

墨涅拉俄斯定理

五、奥拉奇

墨涅拉俄斯定理美丽而简单。在学校课程中，这个定理在问题中的某个地方丢失了。同时，它被列入古希腊数学的黄金基金。

令$\triangle ABC$与一条不平行于边AB且分别与其两条边AC和BC相交的直线相交于点$B_1$和$A_1$，并与直线AB相交于点$C_1$（图1），则

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$

（为了避免对公式中字母出现的顺序感到困惑，请遵循以下规则：沿着三角形的轮廓从顶点移动到与直线的交点，然后从交点移动到下一个顶点。）

⟦folio 53⟧

---
running_head:
folio:
---

剩下的就是将结果比例相乘：

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = \frac{m \cdot n \cdot l}{n \cdot l \cdot m} = 1.$$

定理已被证明。

这个定理应该为我们翻译亚历山大的墨涅劳斯（Menelaus of Alexandria，公元一世纪）的《Spherics》一书的阿拉伯语版本提供指导。

为了证明其有效性，让我们考虑用两种方式解决一个问题：向量和使用墨涅劳斯定理。

问题1.设AD为$\triangle ABC$(图2)的中位数。在AD上取K点，使得AK:KD=3:1。线 BK 将面积 $\triangle ABC$ 划分为多少比例？

显然，三角形ABP和CBP的面积之比等于线段AP和PC的面积之比。因此，解决问题归根结底就是找到 AP/PC 比率。

矢量解决方案。向量$\overline{AK}$可以通过向量$\overline{AB}$和$\overline{AC}$以两种方式表示。首先，$\overline{AK} = \frac{3}{4} \overline{AD}$。但是$\overline{AD} = \frac{1}{2} (\overline{AB} + \overline{AC})$（线段中间的公式）。方法，

$$\overline{AK} = \frac{3}{4} \cdot \frac{1}{2} (\overline{AB} + \overline{AC}) = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

我们用$\frac{PK}{KB} = \frac{m}{n}, \overline{AP} = x \cdot \overline{AC}$来表示它。

将线段划分定理应用于此关系中的 BP，我们有

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{n}{m+n} \overline{AP}.$$

但$AP = x \cdot \overline{AC}$意味着

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC}.$$

比较(1)和(2)，我们得到

$$\frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC} = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

利用向量 AK 分解为两个非附着向量 AB 和 AC 的唯一性，我们得到系统

$$\begin{cases} \frac{m}{m+n} = \frac{3}{8}, \\ \frac{n}{m+n} = \frac{3}{8x}, \end{cases}$$

从哪里$x = 3/5$，即$AP/AC = 3/5$，和

$$\frac{AP}{PC} = \frac{3}{2}.$$

使用墨涅拉俄斯定理的解决方案。将此定理应用到三角形 ACD 和割线 BP 上，我们有

$$\frac{AP}{PC} \cdot \frac{CB}{BD} \cdot \frac{DK}{AK} = 1,$$

$$\frac{AP}{PC} \cdot 2 \cdot \frac{1}{3} = 1, \quad \frac{AP}{PC} = \frac{3}{2}.$$

使用墨涅劳斯定理的优点是非常大的。

很多时候，解决问题时，需要的不是墨涅劳斯定理本身，而是与之相反的定理。

考虑三角形 ABC。设点 A$_1$、B$_1$、C$_1$ 分别属于直线 BC、AC、AB，即位于三角形或其延长线 (图 3) 的边上。

⟦folio 55⟧

---
running_head:
folio:
---

1. 三角形ABC的边AB和AC上分别有点M和N，使得$\frac{AM}{MB} = \frac{CN}{NA} = \frac{1}{2}$。线段 BN 和 CM 的交点 S 以什么比例划分这些线段？
2. 在△ABC中，二分线AD以2:1的比例除BC。 CE 中位数除以二分线的比例是多少？
3. 在三角形 ABC 中，点 D 在边 AB 上，点 E 和 F 在边 BC 上，因此 AD:DB = 3:2，BE:EC = 1:3，BF:FC = 4:1。线段 AE 与线段 DF 的分割比例是多少？
4. 三角形ABC的重心H平分高。证明$\cos \angle C = \cos \angle A \cdot \cos \angle B$，其中$\angle A, \angle B, \angle C$是顶点的角度。
5. 在边长为 a 的正三角形 ABC 中，E 点为 BC 的中点，D 为 AC 的中点，$F \in DC$、$BF \cap DE = M$、$S_{ABMD} = \frac{5}{8} S_{ABC}$。求 MF (图 6)。
6. 给定一个平行四边形ABCD。 M 点相对于 p 划分线段 AD，点 N 相对于 q 划分线段 DC。线 BM 和 AN 相交于点 S。计算比率 AS:SN (图 7)。
7. 通过面积为1的平行四边形ABCD的边BC的中点M和顶点A，画一条与对角线BD相交于点Q的直线。求四边形QMCD的面积（图8）。
8. 边 △ABC 由点 M、N 和 P 分开，使得 AM:MB = BN:NC = CP:PA = 1:4。求以直线 AN、BP 和 CM 为界的三角形面积与三角形 ABC 面积的比值 (图 9)。

最低金额和最低金额
（开头部分请参见第 49 页）

格尔德的对齐方式。很明显，对于$p = q = 2$，第一个是第二个的特例。因此，如果我们根据规则$|(a; b)|_p = (a^p + b^p)^{\frac{1}{p}}$引入“长”向量$(a; b)$，则结果是两个向量的标量积
$(a; b) \cdot (c; d) \leq |(a; b)|_p \cdot |(c; d)|_q$
不超过它们“长度”的乘积。
在这种状态下，霍尔德不等式的几何解释及其意义。
那么方法就很明确了。我们已经使用一组适度的函数证明了相当多的不等式（包括几个经典的不等式）。读者有可能使用这种方法证明其他解释不等式。

Y展开 4.证明以下不等式$a_1, \dots, a_n, b_1, \dots, b_n$是正数
a) $\sqrt[n]{a_1 \dots a_n} + \sqrt[n]{b_1 \dots b_n} \leq \sqrt[n]{(a_1 + b_1) \dots (a_n + b_n)}$,
b) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} \cdot (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \leq a_1 b_1 + \dots + a_n b_n$ 如果 $q < 0$ 和 $\frac{1}{p} + \frac{1}{q} = 1$
（霍尔德不等式“相反”），
d) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} + (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \geq ((a_1 + b_1)^p + \dots + (a_n + b_n)^p)^{\frac{1}{p}}$，其中$p > 1$（闵可夫斯基不等式）。证明如果$p < 1$，则不等式反转。

方向。 a) 将$n$变量的线性函数$y = a_1 x_1 + \dots + a_n x_n$展开到由集合$(x_1, \dots, x_n)$组成的集合上，使得$x_1 \dots x_n = n$。 6) 将$b_1 = \dots = b_n = 1$置于不等式极限内。 d) 再次考虑条件给定集合上的线性函数 $y = a_1 x_1 + \dots + a_n x_n$：
$x_1^q + \dots + x_n^q = 1$,
其中数字$q$由条件$\frac{1}{p} + \frac{1}{q} = 1$决定。
