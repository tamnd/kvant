---
id: 1973-1-lopovok-vpisannyiy-shestiugolnik-2933f136
issue: kvant_1973_1
year: 1973
number: "1"
title: 内接六边形
authors:
  - Лоповок Л. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 24
page_labels: 18, 20, 21, 22
tag: J81S
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b25a383d2cae64f5c521caecbe47ef06f4b16098b059a469da912783caeb1488
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/07_lopovok-vpisannyiy-shestiugolnik-2933f136.md
source_content_sha256: 3c034f901ccd5d3c983d5aac3a8d9824b6d53f2892a1a365b3a2669cea324c17
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

在“数学圈”部分中，我们发布了一些笔记，其中讨论了与数学中的循环程序相近的任务。一般来说，这些注释的结构是数学循环的含义：循环提供了与药物相关的任务的多个位置。其中一些问题在课文中得到了解决，而另一些问题（包括讲座和更困难的问题）则留给独立解决方案。

一般来说，我们的“数学圈”是有循环的，我们谈论的是正六边形。同时，圆中的任意凸六边形值得特别关注，因为它具有许多有趣的属性。

330多年前，法国著名数学家布莱斯·帕斯卡（当时还是个16岁的男孩）研究了有限截面（即圆、椭圆、双曲线或抛物线）内接六边形的某些性质。同时，他发现了现在以他的名字命名的定理：如果六边形内接于有限截面，则其相对边（或其延伸）的交点位于同一条直线上。帕斯卡使用所谓的射影几何的方法进行了他的研究。我们将考虑内切于圆的凸六边形的性质。问题的这种简化使我们能够保持在初等几何的范围内。

角度

通过内接凸六边形的一个角所得到的和彼此相等。

令 (图 1) 为内接于圆的凸六边形$A_1A_2A_3A_4A_5A_6$。让我们用$2x_1$，$2x_2$，...，$2x_6$来表示相应弧的弧$A_1A_2$，$A_2A_3$，...，$A_6A_1$。再根据内切角$\Rightarrow A_1=x_2+x_3+x_4+x_5$、$\Rightarrow A_3=x_1+x_4+x_5+x_6$、$\Rightarrow A_5=x_1+x_2+x_3+x_6$的性质。

因为$\Rightarrow A_1+\Rightarrow A_3+\Rightarrow A_5=2x_1+2x_2+2x_3+2x_4+2x_5+2x_6=360^\circ$。

由于凸六边形的内角和为$720^\circ$，则$\Rightarrow A_2+\Rightarrow A_4+\Rightarrow A_6=360^\circ$。

⟦folio 20⟧

（显然这总是可以做到的）。

设 $A_1A_2 \cdot A_3A_4 \cdot A_5A_6 = A_2A_3 \cdot A_4A_5 \cdot A_6A_1$；对角线 $A_1A_4$ 和 $A_2A_5$ 相交于点 $M$，对角线 $A_3A_6$ 不经过该点 (图 3)。考虑一个六边形$A_1A_2A_3A_4A_5B$内接于同一个圆，点$B$位于圆与线$A_3M$的交点；这个六边形有越来越多的对角线穿过点$M$。

那么，由已证明的定理
$$A_1A_2 \cdot A_3A_4 \cdot A_5B = A_2A_3 \times A_4A_5 \cdot BA_1.$$
将这个等式与条件进行比较，我们看到
$$\frac{A_5A_6}{A_5B} = \frac{A_6A_1}{BA_1}.$$
但如果点$B$（位于$A_5$和$A_1$之间）位于$A_5$和$A_6$之间，那么从条件$\bigcup A_1A_5 < 180^\circ$我们得到：
$$A_5B < A_5A_6, BA_1 > A_6A_1,$$
在哪里
$$\frac{A_5A_6}{A_5B} > 1 > \frac{A_6A_1}{BA_1}$$

- 严格的不平等而不是平等。类似地考虑点$B$位于$A_1$和$A_6$之间的情况。因此，原六边形的第三条较大对角线未经过点 $M$ 的假设是不正确的。

因此，乘积相等就是凸的一边

图 4.

穿过一的六边形是六边形的大对角线交于一点的充要条件。

内接凸六边形的边和主对角线之间的公制对应关系

内接凸六边形的主对角线的乘积等于其穿过一条边的乘积之和，以及其对边与分隔它们的主对角线的乘积之和（在 图 4 $xyz = abc + a_1b_1c_1 + aa_1x + bb_1y + cc_1z$）。

众所周知，内接四边形的对角线的乘积等于四边形对边的乘积之和（托勒密定理）。

六边形所有元素的名称都在 图 4 上给出。根据托勒密定理，从四边形 $A_2A_3A_5A_6$ 可以发现
$$xy = cc_1 + de$$
和
$$xyz = cc_1z + dez.$$
但$e$和$z$是循环四边形$A_1A_3A_4A_5$的对角线。因此$ez = fa_1 + gb$。因此，
$$xyz = cc_1z + dfa_1 + dgb.$$

从循环四边形 $A_1A_2A_3A_6$ 可以找到 $df = ax + b_1c_1$，从四边形 $A_1A_2A_5A_6$:$dg = ac + b_1y$ 可以找到。替换这些值，我们获得所需的等式。

计算内切凸六边形沿其边的对角线是一项非常困难的任务。只有当循环六边形是半右（$a = b = c, a_1 = b_1 = c_1$）的情况下，解法才简单。由于此类六边形的所有角度都等于 $120^\circ$，因此次对角线定义为三角形的第三条边，其两条边等于 $a$

⟦folio 21⟧

图 5.
和$a_1$，它们之间的角度为$120^\circ$。因此，$\alpha = \sqrt{a^2 + aa_1 + a_1^2}$。主对角线是梯形的底边，梯形的边相等，与底边形成$60^\circ$角。这样的梯形有一个较大的底等于第二个底与边的和，即
$$x = a + a_1.$$

几点

我们需要三角形的一个性质——墨涅劳斯定理。

设一条不通过三角形ABC顶点的直线与其边AB、BC、CA或其对应点C$_1$、A$_1$和B$_1$的延长线相交（图5中给出了这种配置的示例）；莫埃达

$$\frac{AC_1}{BC_1} \cdot \frac{BA_1}{CA_1} \cdot \frac{CB_1}{AB_1} = 1.$$

当直线仅与三角形的续边相交时，证明墨涅拉俄斯定理的有效性也很容易 - 自己动手吧。

让一个凸六边形挂在一个圆上，并在点K、L和M处延伸其相应的延伸（图6）。那么点 K、L 和 M 位于同一条直线上。

边$A_1A_2$、$A_3A_4$和$A_5A_6$的延长线相交于点B、C和D。三角形BCD与线$KA_2A_3$、$LA_5A_4$、$MA_6A_1$相交的距离（技术不是像平常那样用两点来书写，而是用托盘来显示线与延续的相交点

⟦folio 22⟧

图 7.

位于三角形 BCD 对应边的下方）。根据这些线的墨涅拉俄斯定理，我们有：

$$\frac{BA_2}{A_2D} \cdot \frac{DK}{KC} \cdot \frac{CA_3}{A_3B} = -1;$$

$$\frac{BL}{LD} \cdot \frac{DA_5}{A_5C} \cdot \frac{CA_4}{A_4B} = -1;$$

$$\frac{CM}{MB} \cdot \frac{BA_1}{A_1D} \cdot \frac{DA_6}{A_6C} = -1.$$

改变这些等式，我们得到：

$$\frac{BL \cdot DK \cdot CM}{LD \cdot KC \cdot MB} \times$$

$$\times \frac{BA_2 \cdot CA_3 \cdot DA_5 \cdot CA_4 \cdot BA_1 \cdot DA_6}{A_2D \cdot A_3B \cdot A_5C \cdot A_4B \cdot A_1D \cdot A_6C} = -1.$$

(*)

根据从一点画圆的割线的性质，$BA_1 \cdot BA_2 = BA_3 \cdot BA_4; CA_3 \cdot CA_4 = CA_5 \cdot CA_6; DA_5 \cdot DA_6 = DA_1 \cdot DA_2$。

因此 (*) 中的第二个分数等于 1。因此，

$$\frac{BL}{LD} \cdot \frac{DK}{KC} \cdot \frac{CM}{MB} = -1.$$

正如我们所知，这证明了点 K、L 和 M 位于同一条直线上。

对角线$A_1A_3$和$A_2A_4$、$A_2A_5$和$A_3A_6$、$A_1A_5$和$A_4A_6$（图7）的交点也位于同一条直线上。

为了证明这一点，他使用了正弦定理（三角形的边与对角的正弦成正比）以及三角形 $A_1A_3E$ 和点 B、C、D 的墨涅拉俄斯定理的逆定理：

$$\frac{A_1B}{BA_3} = \frac{A_1B}{A_2B} \cdot \frac{A_2B}{BA_3} =$$

$$= \frac{\sin(x_4 + x_5 + x_6)}{\sin x_2} \cdot \frac{\sin x_1}{\sin x_3};$$

$$\frac{A_3C}{CE} = \frac{A_3C}{CA_5} \cdot \frac{CA_5}{CE} =$$

$$= \frac{\sin x_2}{\sin x_5} \cdot \frac{\sin(x_3 + x_4 + x_6)}{\sin x_1};$$

$$\frac{ED}{DA_1} = -\frac{ED}{A_1D} =$$

$$= -\frac{ED}{DA_6} \cdot \frac{DA_6}{A_1D} = -\frac{\sin x_3}{\sin(x_1 + x_2 + x_5)} \times \frac{\sin x_5}{\sin(x_1 + x_2 + x_3)}.$$

改变这些等式，我们得到：

$$\frac{A_1B}{BA_3} \cdot \frac{A_3C}{CE} \cdot \frac{ED}{DA_1} =$$

$$= -\frac{\sin(x_3 + x_4 + x_6)}{\sin(x_1 + x_2 + x_3)} \cdot \frac{\sin(x_4 + x_5 + x_6)}{\sin(x_1 + x_2 + x_5)}.$$

由于$x_1 + x_2 + x_3 + x_4 + x_5 + x_6 = 180^\circ$，那么

$$\sin(x_1 + x_2 + x_3) = \sin(x_4 + x_5 + x_6)$$

和

$$\sin(x_1 + x_2 + x_5) = \sin(x_3 + x_4 + x_6)$$

因此，

$$\frac{A_1B}{BA_3} \cdot \frac{A_3C}{CE} \cdot \frac{ED}{DA_1} = -1.$$

这就证明B、C、D点在同一条直线上。

类似地，可以证明对角线$A_1A_3$和$A_2A_6$、$A_3A_5$和$A_4A_6$、$A_1A_4$和$A_2A_5$的交点以及对角线$A_1A_5$的交点位于同一条直线上
