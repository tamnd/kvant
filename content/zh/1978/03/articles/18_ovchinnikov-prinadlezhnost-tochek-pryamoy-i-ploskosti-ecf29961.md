---
id: 1978-3-ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961
issue: kvant_1978_3
year: 1978
number: "3"
title: 点属于直线和平面
authors:
  - Овчинников С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 55
page_labels: 48, 49, 50, 52, 53
tag: XKRD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 77145f80cace38da30fe9789b5856f40c6e813c85c98d1a4359b0def72e46739
prompt_sha256: draft-1
translated_from: content/ru/1978/03/articles/18_ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961.md
source_content_sha256: 54ea9db5ca115c0ddf6ffd234d0543994b2bd479195c299b96a36a292ccb3beb
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

S·奥夫钦尼科夫

点属于直线和平面

在解决几何问题时，他经常使用点属于直线或平面的条件。向量的使用使我们能够以简单而紧凑的形式编写这些条件。同时，在解决问题时通常不需要相当狡猾的额外构造。

在本文中，我们将推导点属于直线和平面的条件，并考虑它们的应用示例。让我们从解决以下问题开始。

问题 1（莫斯科国立大学经济学院，1975 年）。给定三角形ABC。点M和N分别在AB和BC边上取； $|AB| = 5|AM|$，$|BC| = 3|BN|$。线段 AN 和 CM 相交于点 O。求三角形 AOC 和 ABC 的面积比。

解（图1）。因为

$$\frac{S_{AOC}}{S_{ABC}} = \frac{S_{AMC}}{S_{ABC}} \cdot \frac{S_{AOC}}{S_{AMC}} = \frac{|AM|}{|AB|} \cdot \frac{|OC|}{|MC|} = \frac{1}{5} \cdot \frac{|OC|}{|MC|},$$

我们只要确定 O 点分割线段 MC 的比例就足够了。让我们画出 ME，$E \in [BC]$，与 AN 平行；然后$\frac{|EN|}{|BN|} = \frac{|AM|}{|AB|} = \frac{1}{5}$。

但是$|BN| = \frac{1}{3}|BC|$，$|EN| = \frac{1}{15}|BC|$来自哪里。下一个，

$$\frac{|OC|}{|MC|} = \frac{|NC|}{|EC|} = \frac{2/3|BC|}{2/3|BC| + 1/15|BC|} = \frac{10}{11}.$$

方法，

$$\frac{S_{AOC}}{S_{ABC}} = \frac{1}{5} \cdot \frac{10}{11} = \frac{2}{11}.$$

请注意，大多数申请人无法弄清楚 ME || 的附加结构因此AN并没有解决这个问题。

让我们考虑基于《几何9》教科书第254题结果的另一种解决方案。让我们将这个结果表述如下：

定理 1. 对于 O 点的任意选择，均等式

$$\overrightarrow{OC} = \alpha \overrightarrow{OA} + (1 - \alpha) \overrightarrow{OB}$$

(1)

对于某个数 α，点 A、B 和 C ($A \neq B$) 属于同一条直线是必要且充分的条件。同时$\overrightarrow{BC} = \alpha \overrightarrow{BA}$。

图 1.

图 2.

⟦folio 49⟧

图2说明了定理1。注意，系数$\alpha$的值决定了直线$(AB)$上的点的位置。如果$0 \leqslant \alpha \leqslant 1$，则点$C$在$A$和$B$之间；如果$\alpha > 1$，则点$A$位于$C$和$B$之间，最后，如果$\alpha < 0$，则点$B$位于$A$和$C$之间。系数$\alpha$起到直线$(AB)$上的自由坐标的作用：坐标原点是点$B$，尺度由线段$BA$给出，因此点$A$的坐标为1。

让我们回到问题1，表示$\overrightarrow{BA} = \vec{p}$和$\overrightarrow{BC} = \vec{q}$。然后是$\overrightarrow{BM} = \frac{4}{5} \vec{p}$和$\overrightarrow{BN} = \frac{1}{3} \vec{q}$。由于点 $O$ 属于线 $AN$ 和 $CM$，则
$$\overrightarrow{BO} = \alpha_1 \overrightarrow{BM} + (1 - \alpha_1) \overrightarrow{BC} = \alpha_2 \overrightarrow{BA} + (1 - \alpha_2) \overrightarrow{BN},$$
IE。
$$\frac{4}{5} \alpha_1 \vec{p} + (1 - \alpha_1) \vec{q} = \alpha_2 \vec{p} + \frac{1}{3} (1 - \alpha_2) \vec{q},$$
在哪里
$$\begin{cases} \frac{4}{5} \alpha_1 = \alpha_2, \\ 1 - \alpha_1 = \frac{1}{3} (1 - \alpha_2). \end{cases}$$
求解所得系统，我们找到 $\alpha_1 = \frac{10}{11}, \alpha_2 = \frac{8}{11}$。由定理1
$$\overrightarrow{CO} = \alpha_1 \overrightarrow{CM} = \frac{10}{11} \overrightarrow{CM},$$
在哪里

图 3.

图 4.

⟦folio 50⟧

$$= \frac{10}{3}.$$ 用 φ 表示 $BCD$，利用余弦定理从三角形 $ECF$ 求$\cos \varphi = \frac{1}{10}$。给定 cosф 的值，我们使用余弦定理计算对角线 $|AC| = \sqrt{45}$ 和 $|BD| = \sqrt{37}$。

问题 3*)。给定一个三角形 $ABC$ 和边 $BC$ 上的一个点 $M$。证明$|AM| \cdot |BC| \leq |AB| \cdot |MC| + |AC| \cdot |BM|$。

解（图4）。我们有$\overrightarrow{AM} = \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC}$。

从$\alpha = \frac{|MC|}{|BC|}$开始，然后$1-\alpha = \frac{|BM|}{|BC|}$。接下来是$\left| \overrightarrow{AM} \right| = \left| \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC} \right| \leq \alpha \left| \overrightarrow{AB} \right| + (1-\alpha) \left| \overrightarrow{AC} \right| = \frac{|MC|}{|BC|} \cdot |AB| + \frac{|BM|}{|BC|} \cdot |AC|$，问题的陈述如下。

定理 1 允许对空间情况进行以下推广。

定理 2. 令 $A, B$ 和 $C$ 为不在同一直线上的成对不同点。对于任何点 $O$ 的选择都相等
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1-\alpha-\beta) \overrightarrow{OC} \text{ является необходимым и достаточно условием принадлежности точки } A, B, C \text{ и } D \text{ одной плоскости}.$$
证明1）充分性。令(2)成立。我们从$\overrightarrow{CD} = \alpha \overrightarrow{CA} + \beta \overrightarrow{CB}$找到$\overrightarrow{OD} - \overrightarrow{OC} = \alpha (\overrightarrow{OA}-\overrightarrow{OC}) + \beta (\overrightarrow{OB}-\overrightarrow{OC})$。因此，向量$\overrightarrow{CA}, \overrightarrow{CB}$和$\overrightarrow{CD}$共面，因此点$A, B, C$和$D$属于同一平面。

2) 必要性。如果$A, B, C$和$D$属于同一平面，则向量$\overrightarrow{CA}, \overrightarrow{CB}$和$\overrightarrow{CD}$共面。由于点 $A, B$ 和 $C$ 成对不同且不在同一直线上，因此向量 $\overrightarrow{CA}$ 和 $\overrightarrow{CB}$ 不共线。

*) 这个问题是由 I. Sharygin 提出的。

图 5.

⟦folio 52⟧

减去金字塔的体积 $LAFN$ 和 $DB_1KM$。令 $V$ 为棱柱的体积。通过前面的计算我们知道了金字塔$LA_1EM$、$LAFN$、$DB_1KM$的高度$|LA_1|$、$|DB_1|$、$|LA|$与棱柱高的对应关系，以及底面面积的对应关系。这样就很容易找到$V_{LA_1EM} = \frac{3}{8}V$、$V_{LAFN} = \frac{1}{72}V$和$V_{MKB_1D} = \frac{1}{48}V$，由此多面体$AEKB_1DNAF$的体积等于$\frac{3}{8}V - \frac{1}{72}V - \frac{1}{48}V = \frac{49}{144}V$。因此，切割面以 49:95 的比例划分棱柱的体积。

首先请注意，在我们的解决方案中，任何地方都没有使用棱镜正确的条件。其次，我们的解法也适用于点 $E$ 和 $N$ 不是边 $A_1C_1$ 和 $AB$ 的中点的情况，而具有附加构造的解 *) 充分利用了这种情况（素数 $EP$ 与 $BB_1$ 相交于点 $D$ 因为$|A_1E| = |EC_1|$）。

细心的读者可能已经注意到，通过比较定理1和定理2，定理1中的系数$\alpha$只是dado的几何原点，而定理2中的系数$\alpha$和$\beta$的几何意义尚不清楚。我们在一个重要的特殊案例中利用了这一差距，将概括留给读者。

定理 3. 如果在定理 2 的条件下，点 $D$ 位于三角形 $ABC$ 内，则根据等式
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1 - \alpha - \beta) \overrightarrow{OC} \text{ следует}$$
$$\begin{cases} \alpha = S_{BDC}: S_{ABC}, \\ \beta = S_{ADC}: S_{ABC}, \\ 1 - \alpha - \beta = S_{ADB}: S_{ABC}. \end{cases}$$

*) 将这个问题的解决方案与 G.V. 书中给出的解决方案进行比较多罗费耶夫，M.K.波塔波夫，N.Kh. Rozov“构造问题的数学手册”，莫斯科，1976 年，第 3 节，第 6 节，任务 7（第 514 页）。

⟦folio 53⟧

图 8.

证明（图8）。由定理2$\vec{CD} = \alpha \vec{CA} + \beta \vec{CB}$证明如下。让我们输入$\vec{CK} = \alpha \vec{CA}$，$\vec{CL} = \beta \vec{CB}$。从图 8 可以清楚地看出$S_{ADC} : S_{ABC} = \beta$ 和$S_{BDC} : S_{ABC} = \alpha$。从这些等式很容易得出$S_{ADB} : S_{ABC} = 1 - \alpha - \beta$。

任务和

1. （Geofak，莫斯科国立大学，1966 年）。点$K$以3:1的比例除三角形$ABC$的中线$AD$，从顶点开始计算。直线 $BK$ 与三角形 $ABC$ 的平面的比例是多少？

2. （Geofak，莫斯科国立大学，1974 年）。给定一条正四边形线 $PABCD$，顶点为 $P$。在边$PA$和$PC$上，分别取点$K$和$M$，以及$|AK| : |KP| = 1:3$、$|CM| = |PM|$。求边 $PB$ 除以通过点 $D$、$K$ 和 $M$ 绘制的平面的比率。

3. （莫斯科国立大学化学系，1970）。该平面穿过三角形线 $SABC$ 的底顶点 $A$，平分三角形 $SAB$ 的中线 $SK$，并与三角形 $SAC$ 的中线 $SL$ 相交于点 $D$，使得$|SD| = \frac{1}{2} |DL|$。该平面将直线的体积除以什么比例？

修正案。条件���题 M483有一个拼写错误，它描述了问题«Kvant»（«Kvant»，1978年，第1号）。下面我们给出这个问题的正确条件。发送决定的截止日期延长至 1978 年 5 月 1 日。

4. （Geofak，莫斯科国立大学，1976 年）。在对角线等于$|AC| = 6$和$|BD| = 24$的平行四边形$ABCD$中，绘制一条线段$EF$，连接对角线$AC$的点$E$与边$BC$的点$F$。选择点$E$和$F$使得$\frac{|FC|}{|BF|} = \frac{1}{2}, \frac{|EA|}{|EF|} = \frac{1}{3}$。已知对角线$BD$与线段$EF$的交点$M$将其按比例$\frac{|EM|}{|MF|} = \frac{1}{2}$分开。找出平行四边形的边。

5. 给定一个三角形$ABC$。在边 $AB$ 上取点 $D$，在边 $BC$ 上取点 $E$ 和 $F$，从而得到 $|AD| : |DB| = 3:2, |BE| : |EC| = 1:3$ 和 $|BF| : |FC| = 4:1$。线段 $(AE)$ 分割线段 $DF$ 的比例是多少？

6. （Mekhmat，莫斯科国立大学，1964 年）。给定一个立方体$ABCDA_1B_1C_1D_1$，其中$AA_1, BB_1, CC_1, DD_1$是侧边。正方体的体积除以穿过顶点$A$、边中点$BC$和面中心$DCC_1D_1$的平面的比例是多少？

7. （Mekhmat，莫斯科国立大学，1965 年）。给定一条正四边形线 $SABCD$，顶点为 $S$。通过边 $AB, AD$ 和 $CS$ 的中点绘制一个平面。该平面将直线的体积除以什么比例？

8. 在三角形$ABC$内取点$O$。线 $(AO), (BO)$ 和 $(CO)$ 分别与边 $BC$、$CA$ 和 $AB$ 相交于点 $P$、$Q$ 和 $R$。证明

$$\frac{|AR|}{|RB|} \cdot \frac{|BP|}{|PC|} \cdot \frac{|CQ|}{|QA|} = 1.$$

9. 点 $P$ 和 $Q$ 按给定比率划分三角形 $ABC$ 的边 $BC$ 和 $CA$：

$$\frac{|BP|}{|PC|} = a, \quad \frac{|CQ|}{|QA|} = b.$$

设$O$为线$AP$和$BQ$的交点。求平面四边形 $OPCQ$ 与平面三角形 $ABC$ 的比率。

10. 令$OABC$为一条三角形线，顶点为$O$，$M$为三角形$ABC$内的一个点。然后

$$|OM| \cdot S_{ABC} \leq |OA| \cdot S_{MBC} + |OB| \cdot S_{MAC} + |OC| \cdot S_{MAB}.$$

M483。 a) 证明直角三角形内切圆半径的平方与锐角中线长度的平方和之比不超过1/20。

6) 这种关系最重要的意义是什么？
