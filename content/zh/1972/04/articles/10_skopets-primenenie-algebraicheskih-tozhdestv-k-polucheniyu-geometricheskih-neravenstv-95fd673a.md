---
id: 1972-4-skopets-primenenie-algebraicheskih-tozhdestv-k-polucheniyu-geometricheskih-neravenstv-95fd673a
issue: kvant_1972_4
year: 1972
number: "4"
title: 应用代数恒等式获得几何不等式
authors:
  - Скопец З. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 41
page_labels: 36-38
tag: 52NA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 40649958f85897a29b9314ad509091b28b6f71ed834d938e2089322a351fd834
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/10_skopets-primenenie-algebraicheskih-tozhdestv-k-polucheniyu-geometricheskih-neravenstv-95fd673a.md
source_content_sha256: c85c9baf41a8064edec57255887c04a8335818eb3188fb478db6c536ecd98ad4
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

代数点的应用就是求得几何不等式

Z·A·斯科佩茨

代数点对复数集有效，但有某些例外，可以成功地应用来获得连接平面图形的线性和角度元素的有趣的几何不等式。下面通过这种方式得到几个几何不等式。请注意，找到这些不等式的几何证明的数量是相当困难的。我们将用拉丁字母的小写字母$a, b, c, \dots$来表示复数。回想一下，复数是表达式 $x+iy$，其中 $x$ 和 $y$ 是实数，$i$ 是最小单位 ($i^2=-1$)。如果在平面上给出直角（笛卡尔）坐标系$Oxy$，则每个复数$a=x+iy$都可以与平面上横坐标为$x$、纵坐标为$y$的点$A$相关联。让我们给出一些与复数相关的定义。

一、复数$a=x+iy$的模型是等于距离的非负数$\sqrt{x^2+y^2}$

图 1.

图 2. $OM=MA$; $A_1M=MA_2$

图 3. $OM=MA_1$; $A_2M=MA$

⟦folio 37⟧

图 4. 图 5.

我们有

$$|a_1+a_2| \leq |a_1|+|a_2|.$$ (2)

(2)中的等号表示点$O, A_1$和$A_2$位于同一条直线上，且点$O$不属于线段$A_1A_2$。

因此，两个完整数之和的模型不大于各项模型之和。

两个完整数$a_1$和$a_2$的差$a_1-a_2$是一个数$a$，使得$a+a_2=a_1$（几何构造在图3中给出）。从$OA=A_1A_2$开始，那么

$$|a_1-a_2|=A_1A_2.$$ (3)

因此，两个完全数之差的模型就等于考虑它们的对应点之间的关系。

接下来，$OA_1-OA_2 \leq A_1A_2 \leq OA_1+OA_2$。这就是为什么

$$|a_1|-|a_2| \leq |a_1-a_2| \leq |a_1|+|a_2|.$$ (4)

如果点$O, A_1$和$A_2$属于同一条直线，则(4)中的不等号之一变为相等。

因此，两个完全数之差的模型不大于它们模型的和，也不小于它们的差。

很容易检查 (图4) 是否为真，例如，以下不等式：

$$|a+b+c| \leq |a|+|b|+|c|.$$ (5)

请注意，如果数字 $a$ 对应于坐标为 $x, y$ 的点 $A$，则数字 - $a$ 对应于坐标为 - $x$、- $y$ 的点。这两点关于原点 $O$ (图 5) 对称。斯莱多瓦-

⟦folio 38⟧

图 7.

2. 很容易检查以下几点：
$$a^2(b-c) + b^2(c-a) + c^2(a-b) = -(b-c)(c-a)(a-b).$$
由此可知 $|b-c| |c-a| |a-b| \leqslant |a^2| |b-c| + |b^2| |c-a| + |c^2| |a-b|$ 或 (图 7)
$$BC \cdot CA \cdot AB \leqslant OA^2 \cdot BC + OB^2 \cdot CA + OC^2 \cdot AB.$$ (8)
推论 1. 如果 $ABC$ 是等边三角形，则 $OA^2 + OB^2 + OC^2 \geqslant d^2,$ (8')
rede $d$ 是三角形的边长。
因此，平面上任意点到等边三角形各顶点的距离的平方和不小于其边长的平方。
推论 2. 如果 $O$ 是任意三角形的外接圆的圆心，则从 (8) 可以得出
$$AB \cdot BC \cdot CA \leqslant R^2(AB + BC + CA)$$
或者
$$\frac{AB \cdot BC \cdot CA}{AB + BC + CA} \leqslant R^2.$$ (8'')
因此，三角形三边的任意度与其总和之比不超过三角形外接圆半径的平方。
3. 通过检查我们确信这一点的真实性：
$$(b-c)(b+c)^2 + (c-a)(c+a)^2 + (a-b)(a+b)^2 = (a-b)(a-c)(b-c).$$
让我们分别用 $k_1, k_2, k_3$ 表示从围绕三角形 $ABC$ 描述的圆心到边 $BC, CA, AB$ (图 8) 的距离。这个圆的中心是

图 8.
模因的起源。然后
$$|b+c| = 2k_1, |c+a| = 2k_2, |a+b| = 2k_3.$$
从这一点可以看出
$$AB \cdot BC \cdot CA \leqslant 4(k_1^2 \cdot BC + k_2^2 \cdot CA + k_3^2 \cdot AB).$$
但是$S_{OBC} = \frac{1}{2} k_1 \cdot BC = \frac{1}{2} R^2 \sin 2A,$如果$A \leqslant 90^\circ$。因此，
$$k_1 \cdot BC = R^2 \cdot \sin 2A.$$
类似地，如果角 $B$ 和 $C$ 不是钝角，则
$$k_2CA = R^2 \sin 2B, k_3AB = R^2 \sin 2C.$$
波兹尼
$$AB \cdot BC \cdot CA \leqslant 4R^2(k_1 \sin 2A + k_2 \sin 2B + k_3 \sin 2C).$$
考虑到
$$k_1 = R \cos A, k_2 = R \cos B, k_3 = R \cos C, AB \cdot BC \cdot CA = 4RS_{ABC},$$
我们有
$$4RS_{ABC} \leqslant 4R^3 (\cos A \sin 2A + \cos B \sin 2B + \cos C \sin 2C).$$
从这里
$$\frac{S_{ABC}}{R^2} \leqslant \cos A \sin 2A + \cos B \sin 2B + \cos C \sin 2C.$$ (9)
因此，对于任何非钝角三角形，不等式（9）成立。
四．独立解决的问题。
任务1. 从点$a^2 - b^2 = (a+b)(a-b)$导出不等式$2OM \cdot AB \geqslant OA^2 - OB^2,$，其中$M$是中点，$AB, O$是坐标原点，$a, b$是点$A, B$对应的数字。找出什么时候它变成平等。
任务 2. 从点 $a^3(b-c) + b^3(c-a) + c^3(a-b) = -(a+b)(a-b)(b-c)(c-a)$ 不均匀导出

⟦folio none⟧

等式$OH \leq \frac{R^2}{2r}$，其中$O$是三角形的外接圆的圆心，$R$是该圆的半径，$H$是三角形的垂心，$r$是内接圆的半径。 （三角形的重心是其高或其延伸线的交点。）

任务 3. 证明 $AB \cdot CD + BC \cdot DA \geq CA \cdot BD$，其中 $A, B, C, D$ 是平面上的任意点。

任务 4. 证明 $AB \cdot AM \cdot BM + BC \cdot BM \cdot CM + CA \cdot CM \cdot MA \geq AB \cdot BC \cdot CA$。

任务 5. 从目标点 $\frac{a}{(a-b)(a-c)(a-d)} + \frac{b}{(b-c)(b-d)(b-a)} + \frac{c}{(c-d)(c-a)(c-b)} + \frac{d}{(d-a)(d-b)(d-c)} = 0$ 导出不等式 $OA \cdot BC \cdot BD \cdot CD + OB \cdot CA \cdot CD \cdot AD + OC \cdot AB \cdot AD \cdot BD \geq OD \cdot AB \cdot BC \cdot CA$，其中 $O, A, B, C, D$ 是平面上的任意（不同）点。

路线

1) 等式对于位于同一直线上的点 $O, A, B$ 成立。

2) 利用这样的事实：如果$H$是三角形$ABC$的重心，并且三角形的外接圆的中心与坐标原点重合，则$h = a + b + c$（$a, b, c, h$是对应于点$A, B, C, H$的复数）。请注意，$h - a = k_1(b + c)$、$h - b = k_2(c + a)$、$h - a = k_3(a + b)$，其中 $k_1, k_2, k_3$ 是实数。从这个系统可以得出$k_1 = k_2 = k_3 = 1$。

3) 考虑身份$(m - a)(b - c) + (m - b)(c - a) + (m - c)(a - b) = 0$。

4) 考虑身份$(m - a)(m - b)(a - b) + (m - b)(m - c) \times (b - c) + (m - c)(m - a)(c - a) = (a - b)(b - c)(c - a)$。
