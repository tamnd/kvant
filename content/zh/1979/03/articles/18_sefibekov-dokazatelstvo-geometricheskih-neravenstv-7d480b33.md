---
id: 1979-3-sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33
issue: kvant_1979_3
year: 1979
number: "3"
title: 几何不等式的证明
authors:
  - Сефибеков С. Р.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 55
page_labels: 51, 53
tag: EXHL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 18368710b08cc3156416c37c912b50e8bd09ec00ea0438b137ffd9f705b1eb30
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/18_sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33.md
source_content_sha256: 6b546bab066a8d5115575709b6ad8a6ba1f7238474d34ee2d01e11d776eeea17
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

塞菲别科夫

几何不等式的证明

在数学问题中，以下示例通常很有用：以两种方式找到相同的数量，然后将其获得的表达式相等。例如，让我们用两种方法求某个图形的面积。如果面积表达式之一包括某个角度 $\alpha$ 的正弦，那么使用所得等式中的对应关系 $\sin \alpha \leq 1$，我们可以获得一些有趣的不等式。在 S. Sefibekov 的文章中，整个问题都使用了这个例子。这些问题对于八年级学生来说是容易理解的，但对于大学申请者来说也很有趣——此类问题在口语考试中会遇到。

解决下列问题的关键是三个面积公式。众所周知（《几何8》，第108段），三角形的面积等于它的两条（任意）边与它们之间的角度的正弦乘积的一半：

$$S = \frac{1}{2} ab \sin \alpha$$

由此推论，凸四边形的面积等于其对角线与对角线夹角正弦乘积的一半*)：

$$S = \frac{1}{2} l_1 l_2 \sin \alpha.$$

又证明外接多边形的面积

*) 为什么不需要指定考虑对角线之间的角度？

$$S = \frac{1}{2} Pr.$$

问题1.证明任意两条边三角形的乘积不小于其周长与内切圆半径的乘积：$ab \geq Pr$。

解决方案。使三角形面积的表达式（1）和（3）相等并考虑$\sin \alpha \leq 1$就足够了。

评论。从解中可以清楚地看出，如果长度为 $a$ 和 $b$ 的边之间的角度不是直角，则为 $ab > Pr$。

根据不等式 (4) 和替换，可以得出对于任何三角形

$$ab + bc + ca > 3Pr.$$

问题2.证明任意三角形外接圆的半径$R$、外接圆的半径$r$和周长$P$满足不等式

a) $R > \frac{\sqrt{3}}{3} \sqrt{Pr}$,

如果三角形是锐角三角形还是钝角三角形；

b) $R \geq \frac{\sqrt{2}}{2} \sqrt{Pr}$,

如果三角形是直角。

解决方案。 a) 将外接圆的圆心 $O$ 与三角形的顶点连接起来。

对于锐角三角形 (图 1)

$$S_{ABC} = S_{AOB} + S_{BOC} + S_{COA}.$$

图 1.

⟦folio 53⟧

另一方面，根据式（1）
$$S_{AOB} = \frac{1}{2} |OA| \cdot |OB| \cdot \sin \widehat{AOB}. \quad (18)$$
从 (17) 和 (18)
$$P_1 r_1 \leq |OA| \cdot |OB|. \quad (19)$$
同样地，
$$P_2 r_2 \leq |OB| \cdot |OC|, \quad (20)$$
$$P_3 r_3 \leq |OC| \cdot |OD|, \quad (21)$$
$$P_4 r_4 \leq |OD| \cdot |OA|. \quad (22)$$
从(19) - (22) 很容易得到所需的不等式。
当 $[AC] \perp [BD]$ 时，就实现了平等。由(16)和(13)易得不等式：
$$S_{AOB} \cdot S_{BOC} \cdot S_{COD} \cdot S_{DOA} \leq \frac{1}{16} |OA|^2 \cdot |OB|^2 \cdot |OC|^2 \cdot |OD|^2.$$
问题 5. 证明对于凸四边形 ABCD，以下不等式成立：
$$S_{ABCD} \leq \frac{a^2 + b^2 + c^2 + d^2}{4}, \quad (23)$$
食物$a, b, c, d$——其边长。
解决方案。让我们来分解一下。一条四边形对角线分成两个三角形（图3）。然后
$$S_{ABCD} = S_{ABC} + S_{ADC}.$$
根据式(1)
$$S_{ABC} = \frac{1}{2} ab \sin \widehat{B}.$$

从这里和不等式 $ab \geq \frac{a^2 + b^2}{2}$ 我们得到
$$S_{ABC} \leq \frac{a^2 + b^2}{4}. \quad (24)$$
同样地
$$S_{ADC} \leq \frac{c^2 + d^2}{4}. \quad (25)$$
从（24）和（25）我们得到所需的不等式。
如果$\widehat{B} = \widehat{D} = 90^\circ$和$a = b = c = d$，即四边形ABCD是正方形，则对应关系(23)变为等式。
总之，这里有三个任务需要您自己解决。
问题 6. 证明对于高度为 $h$、对数为 $l_1, l_2$、底为 $a, b$ 的坟墓
$$h \leq \frac{l_1 l_2}{a + b}.$$
问题 7. 证明 ABC 线
$$S_{ABC} < \frac{1}{6} (a^2 + b^2 + c^2),$$
食物$a, b, c$——边长。
问题 8. 证明对于凸四边形 ABCD
$$S_{ABCD} < \frac{1}{6} (a^2 + b^2 + c^2 + d^2 + e^2 + f^2),$$
food $a, b, c, d$——以双数表示的长度。
构建一个多面体！
（从第 50 页开始）
封面第二页上的多面体是从该图中以一种更复杂的方式获得的：其中，顶点 3 和 7 的“周围环境”被使用了五次 - 由此形成了具有顶点 9 的模型的圆顶。侧面也可以从图中获得。
如何构建图表？这是使用同样的半直多面体来完成的。
这种多面体被以下事实所取代：它们的所有面都相等：对于这种多面体的任何两个面，可以指定空间位移，使得多面体将变换为自身，并且第一个面将变换为第二个面。让我们考虑任何这样的多面体并考虑它所有面的平面。让我们修复其中一个平面（我们称之为 $\Pi$）。其中，剩余的平面是由直线系统“雕刻出来”的。其余位面中形成完全相同的系统。现在让我们考虑系统的多面体线$l$。它是平面 $\Pi$ 与另一个面的平面的交线。在将该平面变换为平面 $\Pi$ 的旋转过程中，直线 $l$ 将进入平面 $\Pi$ 的某条直线 $l'$。事实证明，线 $l'$ 是从线 $l$ 通过绕公共点旋转（在平面 $\Pi$ 中）或通过平行平移获得的。保持在转折点线上，并带有相应的运动员和箭头以进行平行转移。
图上的图是从等半直角十六边形得到的（«Kvant»，1976年，第1号）。
建议。当绘制较大比例的图表时，请利用五边形 ABCD 是正确的这一事实。
