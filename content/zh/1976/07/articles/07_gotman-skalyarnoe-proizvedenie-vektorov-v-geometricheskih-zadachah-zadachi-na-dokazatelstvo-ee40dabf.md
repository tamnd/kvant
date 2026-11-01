---
id: 1976-7-gotman-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-zadachi-na-dokazatelstvo-ee40dabf
issue: kvant_1976_7
year: 1976
number: "7"
title: 几何问题中向量的点积。证明问题
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 26
page_labels: 21, 23, 24
tag: JINI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d4105e25afc33948cc221809645e9d7a630322bc786b516ab8113eee44ef77d3
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/07_gotman-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-zadachi-na-dokazatelstvo-ee40dabf.md
source_content_sha256: fc8ca149abad960f8662319942e862a3178ce33579f59a41b987daacf8f3c270
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

新的几何课程（九年级）包括向量标量积的概念。向量的标量积广泛应用于解决各种几何问题和证明定理。下面我们放置了 E. Gotman 和 Y. Ponarin 的两个注释，并通过几个示例演示了向量方法的使用。读者需要熟悉最简单的运算——向量加法和向量与数字的乘法，以及向量标量积的概念。让我们回顾一下向量标量乘法的定义和一些性质。

两个非零向量的标量积是一个数字，等于这些向量的长度数值与向量之间角度的余弦的乘积。

向量a和b的标量积表示为a·b；根据定义 a·b = |a|·|b|·cos a, b)。标量向量乘法的性质与数字运算法则类似：

1) a·b = b·a;
2) (λa) b = λ(a b)，其中λ是某个数字；
3) a·(b+c) = a·b+a·c

（其证明参见九年级几何教科书，第 59 页）。

E·戈特曼

任务

为了证明

您应该从获得的结果中挤出它可以提供的所有内容。

D. 唱 a.如何解决问题。

平四边形

容易看出，如果四边形ABCD的对角线AC和BD互相垂直（图1），则

其边长满足关系

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

反之亦然：是否可以说四边形的对角线

⟦folio 23⟧

而不是在上一段中陈述（使用余弦定理），但它的应用非常严格：毕竟，现在我们知道等式（2）对于四个点$A, B, C$和$D$的任何位置都有效，而不仅仅是当这些点是平坦四边形的顶点时。

应用等式（3），我们现在将获得许多新的有趣结果。

结果

1. 当其他工业边$AB$和$CD$、$BC$和$AD$的长度平方和彼此相等时，米面体$ABCD$的工业边$AC$和$BD$重新分配moed和molkomoed。

事实上，边$AC$和$BD$之间的角度可以通过公式求出

$$\cos(\overrightarrow{AC}, \overrightarrow{DB}) = \frac{|AB|^2 + |CD|^2 - |BC|^2 - |AD|^2}{2|AC| \cdot |BD|}.$$

但 $\cos(\overrightarrow{AC}, \overrightarrow{DB}) = 0$ 当且仅当

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

2. 平面上的点集$D$，每个点到给定的两个点$A$和$C$的距离的平方之差是一个常数值，是一条直线，重新定义直线$AC$。

证明。令该差值等于$k^2$。让我们以 图 3 为基础。

直$AC$点$B$，使得$|AB|^2 - |BC|^2 = k^2$。为此，我们通过点 $C$ 绘制线 $AC$ 的重新分布，并在其上绘制长度为 $k$ (图 2) 的线段 $CM$。线段$AM$的中间重新分布将与直线$AC$与太阳穴点$B$相交。

事实上，从直角三角形$BCM$，$|BM|^2 - |BC|^2 = |CM|^2$。但根据中点重分布的性质$|BM| = |AB|$，还有$|CM| = k$。因此，$|AB|^2 - |BC|^2 = k^2$。

显然，点$B$总是存在的，并且是唯一的。现在让 $D$ 成为所需集合的一个点。将公式（3）应用于平面上的点$A, B, C$和$D$，当且仅当直线$BD$是直线$AC$的重分布时，我们得到$|AD|^2 - |CD|^2 = |AB|^2 - |BC|^2$。

扫地。空间中具有指定属性的点集是一个平面，重新分布到直线 $AC$。

3. 如果$ACBD$是凸四边形，其工业边$AC$和$BD$重新分布（图3），则其对角线长度的平方和等于其另外两个工业边的长度的平方和。

证明。 Pokolku $(AC) \perp (DB)$, $\overrightarrow{AC} \cdot \overrightarrow{DB} = 0$，即等式 (3) 的右边变为零。因此，

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

⟦folio 24⟧

图 5.

4. 翼片对角线长度的平方和等于其侧边长度的平方和与底边长度的二倍积。

证明。设 AC 和 DB 为梯形 ACBD (图 4) 的底。由于向量 $\vec{AC}$ 和 $\vec{DB}$ 是共同校正的，$\vec{AC} \cdot \vec{DB} = |AC| \cdot |DB|$，并且等式 (3) 采用 $|AB|^2 + |CD|^2 - |BC|^2 - |AD|^2 = 2|AC| \cdot |BD|$ 的形式，即

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2 + 2|AC| \cdot |DB|$$

Q.E.D.

5. （众所周知的定理。）平行四边形对角线长度的平方和等于其所有边长的平方和。

证明。向量 AC 和 DB 共同校正 (图 5)，因此自 $|AC| = |DB|$ 以来为 $\vec{AC} \cdot \vec{DB} = |AC| \cdot |DB| = |AC|^2$。

将求得的值$\vec{AC} \cdot \vec{DB}$代入式(3)，可得

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2 + 2|AC|^2 = |BC|^2 + |AD|^2 + |AC|^2 + |BD|^2$$

并且定理被证明。

回想一下，两点之间距离的平方等于这些点定义的向量的标量平方。解决一个问题后，慢慢来：考虑一下结果是否可以用来解决其他问题。

3. a) 围绕三角形 $ABC$ 画一个外接圆，并构造一个点 D，该点相对于边 AB 与中心 O 对称。用向量 $\vec{OA}$、$\vec{OB}$ 和 $\vec{OC}$ 表达向量 $\vec{CD}$。证明

$$|CD|^2 = R^2 + a^2 + b^2 - c^2,$$

其中a = |BC|，b = |AC|，c = |AB|，R = |OA|。

6) 证明对于每个三角形 $ABC$ 不等式

$$\cos 2\hat{A} + \cos 2\hat{B} - \cos 2\hat{C} \leq \frac{3}{2}.$$

找出何时发生平等。

2. a) 证明三角形$ABC$的外接圆圆心O到其质心面ABC的距离M是满足条件$|OM| = 3 |OG|$的点。用三角形边的长度和三角形外接球的半径来表示从顶点 D 到点 M 的距离。

6) 证明如果a、b、c是具有公共顶点的三角形的边的长度，a1、b1、c1是其他三条边的长度，R是其外接球体的半径，则

$$a_1^2 + b_1^2 + c_1^2 \leq 4R^2 + a^2 + b^2 + c^2.$$

4. 证明三角形$ABC$外接球心O到其质心面ABC的距离M是满足条件$|OM| = 3 |OG|$的点。用具有公共顶点的三角形边的长度表示从顶点 D 到点 M 的距离，a1、b1、c1 - 其余三个边的长度以及 R - 围绕它的外接球体的半径，则等式成立

$$|OG|^2 = R^2 - \frac{1}{16} (a^2 + b^2 + c^2 + a_1^2 + b_1^2 + c_1^2),$$

其中a、b、c、a1、b1、c1是三角形的边长，R是外接球的半径。

5. 证明如果A、B、C、D是空间中的四场点，M和N分别是线段AC和BD的中点，则等式成立

$$|AC|^2 + |BD|^2 = |AB|^2 + |BC|^2 + |CD|^2 + |DA|^2 - 4 |MN|^2.$$

从这个定理可以推出什么结果？

*) 请参阅 E. Gottman 的文章“Euler's Direct”（Quant，1975 年，第 2 期，第 32 页）。
