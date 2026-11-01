---
id: 1979-1-gabovich-vektoryi-pomogayut-na-ekzamene-44128586
issue: kvant_1979_1
year: 1979
number: "1"
title: 矢量对考试有帮助
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45, 47, 48, 49
tag: YCER
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a6f1355201a38476f465d0b3e4f9ea102840d6dc9769ff6d74fc5bcf8f745b5d
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/16_gabovich-vektoryi-pomogayut-na-ekzamene-44128586.md
source_content_sha256: 147580f88b1b028ee08593afe0f97d9ebd0151d4d741aa775622025db810f6ac
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

本文介绍了四个重要的向量关系，并以1977-1978年入学考试材料为例，展示了如何应用它们来解决竞争问题。

基本比例。在三角形 ABC 中，点 D 位于 AC 边上，因此 |AD|:|DC| = m:n。然后
$$\overrightarrow{BD} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}^*).$$ (1)

证明。我们有 (图1)
$$\overrightarrow{AC} = \overrightarrow{BC} - \overrightarrow{BA},
\overrightarrow{AD} = \frac{m}{m+n} \overrightarrow{AC} = \frac{m}{m+n} \overrightarrow{BC} - \frac{m}{m+n} \overrightarrow{BA},
\overrightarrow{BD} = \overrightarrow{BA} + \overrightarrow{AD} = \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC} -
\frac{m}{m+n} \overrightarrow{BA} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}.$$
问题 1（密歇根州立大学经济学院，1978 年）。在三角形 KLM 中，点 A 取于边 KL 上，使得 |KA|:|AL| = 1:3； B 点取于 LM 一侧，因此 |LB|:|BM| = 4:1。设 C 为线 KB 和 MA 的交点。已知三角形KLC的面积为2。求三角形KLM的面积。

*) S. Ovchinnikov 的文章 («Kvant», 1978, No. 3, p. 48) 中考虑了该公式的形式略有不同。另请参阅 V. Boltyansky 在 «Kvant» 1978 年的文章，第 10 期，第 17 页。 14.

解决方案。让我们输入$S_{\Delta KLB} = S$。那么(图2)显然是$S_{\Delta KLM} = \frac{4}{5} S$。让我们介绍向量$\overrightarrow{KL}$和$\overrightarrow{KM}$。根据（1）我们有
$$\overrightarrow{KB} = \frac{1}{5} \overrightarrow{KL} + \frac{4}{5} \overrightarrow{KM}.$$
设$\overrightarrow{KC} = x\overrightarrow{KB}$，其中$0 < x < 1$。然后
$$\overrightarrow{KC} = \frac{x}{5} \overrightarrow{KL} + \frac{4x}{5} \overrightarrow{KM}.$$ (2)

让$|AC|:|CM| = m:n$。然后从三角形 AKM 使用相同的公式 (1) 我们有
$$\overrightarrow{KC} = \frac{n}{m+n} \overrightarrow{KA} + \frac{m}{m+n} \overrightarrow{KM} =
\frac{n}{m+n} \frac{1}{4} \overrightarrow{KL} + \frac{m}{m+n} \overrightarrow{KM}.$$ (3)

由于向量在 (2) 和 (3) 中的两个非 collic 向量中的唯一分解，我们得到系统
$$\begin{cases} \frac{x}{5} = \frac{n}{4(m+n)} \\ \frac{4x}{5} = \frac{m}{m+n}, \end{cases}$$ 或
$$\begin{cases} \frac{4x}{5} = \frac{n}{m+n} \\ \frac{4x}{5} = \frac{m}{m+n}. \end{cases}$$

图 1.

图 2.

⟦folio 47⟧

$$\overrightarrow{MN}^2 = \frac{4}{9} a^2 + \frac{a^2}{9} = \frac{5a^2}{9},$$

在哪里

$$|MN| = \frac{a \sqrt{5}}{3}.$$

现在让我们回答问题的第二个问题。让$|D_1M|:|MA| = p$。

然后

$$\overrightarrow{MN} = \frac{1}{p+1} \overrightarrow{D_1D} + \frac{p}{p+1} \overrightarrow{AB_1} =$$

$$= -\frac{a}{p+1} \vec{k} + \frac{2ap}{p+1} \vec{j} + \frac{ap}{p+1} \vec{k} =$$

$$= \frac{2ap}{p+1} \vec{j} + \frac{a(p-1)}{p+1} \vec{k},$$

$$\overrightarrow{MN}^2 = \frac{4a^2p^2}{(p+1)^2} + \frac{a^2(p-1)^2}{(p+1)^2} =$$

$$= \frac{a^2(5p^2-2p+1)}{(p+1)^2}.$$

显然，$|MN|$将在函数达到它的值$p$处具有最小值

$$y = \frac{5p^2-2p+1}{(p+1)^2}.$$

读者可以轻松检查（使用任意一个）$p = \frac{1}{3}$ 是否会发生这种情况。将此值代入 $\overrightarrow{MN}^2$ 的最后一个表达式并求根，我们找到所需的最小距离：

$$\frac{a \sqrt{2}}{2}.$$

三、基本关系。给定一个四面体 ABCD 并在其面 ABC 的平面上有一个点 M。证明对于分解

$$\overrightarrow{DM} = \alpha \overrightarrow{DA} + \beta \overrightarrow{DB} + \gamma \overrightarrow{DC}$$

平等成立

$$\alpha + \beta + \gamma = 1^*).$$

解决方案。假设点 M 位于三角形 ABC (图 5) 内。让我们通过 A 点和 M 点画一条线，BC 边与 E 点相交。让 E 点除以 BC 边的比率

$$*)\text{ В несколько ином виде это соотношение имеется в цитированной статье C. Овчинникова.}$$

图 5.

$m:n$，即$|BE|:|EC| = m:n$。那么根据式(1)

$$\overrightarrow{DE} = \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB}.$$

进一步，让M点相对于$p:q$划分线段AE，即$|AM|:|ME| = p:q$。然后

$$\overrightarrow{DM} = \frac{p}{p+q} \overrightarrow{DE} + \frac{q}{p+q} \overrightarrow{DA} =$$

$$= \frac{p}{p+q} \left( \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB} \right) +$$

$$+ \frac{q}{p+q} \overrightarrow{DA} = \frac{q}{p+q} \overrightarrow{DA} + \frac{p}{p+q} \times$$

$$\times \frac{n}{m+n} \overrightarrow{DB} + \frac{p}{p+q} \frac{m}{m+n} \overrightarrow{DC}.$$

因此，向量$\overrightarrow{DM}$被分解为向量$\overrightarrow{DA}, \overrightarrow{DB}$和$\overrightarrow{DC}$。对该展开式中系数之和的无限计算给出

$$\frac{q}{p+q} + \frac{p}{p+q} \frac{n}{m+n} +$$

$$+ \frac{p}{p+q} \frac{m}{m+n} = \frac{q}{p+q} + \frac{p}{p+q} = 1,$$

这就是所需要的。其余情况（M点位于三角形ABC之外或在其一侧）类似，我们省略它们。

问题 3（MIPT，1978）。正多面体ABCD的边长为$a$。 E点是边CD的中点，F点是面ABD的高度BL的中点。具有线 AD 和 BC 末端的线段 MN 与线​​ EF 相交并落在其上。我们来求一下这段的长度。

解决方案。让我们引入向量 $\overrightarrow{AB} = \vec{b}; \overrightarrow{AC} = \vec{c}; \overrightarrow{AD} = \vec{d}$ (图 6)。请注意 $\|\vec{b}\| = \|\vec{c}\| = \|\vec{d}\| = a$ 和

⟦folio 48⟧

图 6.

$\overrightarrow{b}, \overrightarrow{c} = \overrightarrow{c}, \overrightarrow{d} = \overrightarrow{d}, \overrightarrow{b} = \frac{\pi}{3}$。由于$E$是边$DC$的中点，则$\overrightarrow{AE} = \frac{1}{2}(\overrightarrow{c} + \overrightarrow{d})$。

同样地，
$\overrightarrow{AF} = \frac{1}{2}(\overrightarrow{b} + \overrightarrow{AL})$,
但$\overrightarrow{AL} = \frac{1}{2}\overrightarrow{d}$，因此
$\overrightarrow{AF} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d}$.

达利,
$\overrightarrow{EF} = \overrightarrow{AF} - \overrightarrow{AE} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d} - \frac{1}{2}\overrightarrow{c} - \frac{1}{2}\overrightarrow{d} = \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d}$.

令$\overrightarrow{AM} = m\overrightarrow{d}, \overrightarrow{BN} = n\overrightarrow{BC}$, (9) 其中$0 < m < 1$ 和$0 < n < 1$。从最后一个等式开始，它紧接着$|BN| : |NC| = n : (1 - n)$。

那么，根据式（1），
$\overrightarrow{AN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$.

达利，$\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM}$，来自$\overrightarrow{MN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$。 (11)

由于根据条件，线段 $EF$ 和 $MN$ 是垂直的，则 $\overrightarrow{EF} \cdot \overrightarrow{MN} = 0$，或
$\left( \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d} \right) \times \left( (1 - n)\overrightarrow{b} + n\overrightarrow{c} - m\overrightarrow{d} \right) = 0$.

考虑到上面对向量$\overrightarrow{b}, \overrightarrow{c}$和$\overrightarrow{d}$的模型以及它们之间的角度所做的替换，我们将打开这个等式左侧的括号。

我们得到
$2m - 4n + 1 = 0$. (12)

凭借主关系III，$\overrightarrow{AN} = \alpha\overrightarrow{AF} + \beta\overrightarrow{AE} + \gamma\overrightarrow{AM}$，(13)和$\alpha + \beta + \gamma = 1$。

让我们将(13)中的$\overrightarrow{AF}, \overrightarrow{AE}$和$\overrightarrow{AM}$代入$\overrightarrow{b}, \overrightarrow{c}$和$\overrightarrow{d}$，即(7)、(6)、(9)：

$\overrightarrow{AN} = \frac{\alpha}{2}\left(\overrightarrow{b} + \frac{1}{2}\overrightarrow{d}\right) + \frac{\beta}{2}\left(\overrightarrow{c} + \overrightarrow{d}\right) + \gamma m\overrightarrow{d} = \frac{\alpha}{2}\overrightarrow{b} + \frac{\beta}{2}\overrightarrow{d} + \left(\frac{\alpha}{4} + \frac{\beta}{2} + \gamma m\right)\overrightarrow{d}$.

由于向量独特地分解为三个给定的非平面向量$(\overrightarrow{b}, \overrightarrow{c}, \overrightarrow{d})$，从这里和（10）我们得到系统
$\frac{\alpha}{2} = 1 - n; \frac{\beta}{2} = n; \frac{\alpha}{4} + \frac{\beta}{2} + \gamma m = 0,$
解决我们得到的
$\alpha = 2 - 2n, \beta = 2n, \gamma = -\frac{1 + n}{2m}$.

使用关系$\alpha + \beta + \gamma = 1$，我们从这里得到
$2m - n = 1 = 0$.

与(12)一起求解这个方程，我们得到$n = \frac{2}{3}$和$m = \frac{5}{6}$。剩下的就是将这些值代入表达式(10)中$\overrightarrow{MN}$；我们得到
$\overrightarrow{MN} = \frac{2}{3}\overrightarrow{c} + \frac{1}{3}\overrightarrow{b} - \frac{5}{6}\overrightarrow{d}$;

经过简单的计算我们发现$|MN| = \frac{a\sqrt{23}}{6}$。

四、基本比例。如果 $M$ 是三角形中线 $ABC$ 的交点，$O$ 是空间中的任意点，则等式成立：
$\overrightarrow{OM} = \frac{1}{3}\left(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}\right)$.

这种关系在教科书“几何 9”（§ 22，问题 2）中得到阐述和证明。

问题 4（基辅理工学院，1978 年）。圆的外切于边长为 $a$ 的等边三角形。证明，

⟦folio 49⟧

Chimo 从圆上任意点到该三角形顶点的距离平方和等于 $2a^2$。

解决方案。令 $D$ 为圆上的任意点 (图 7)。让我们输入$|DA| = x; |DB| = y; |DC| = z$。

那么，根据余弦定理，我们有：
从 $\Delta ADB: a^2 = x^2 + y^2 - xy,$
从 $\Delta BDC: a^2 = y^2 + z^2 - yz,$
从$\Delta ADC: a^2 = x^2 + z^2 + xz$开始。

将这些等式逐一相加，我们得到
$3a^2 = 2(x^2 + y^2 + z^2) - xy - yz + zx.$ (14)

凭借 IV 主关系
$\overrightarrow{DO} = \frac{1}{3} (\overrightarrow{DA} + \overrightarrow{DB} + \overrightarrow{DC})$,

其中 $O$ 是圆心。

通过对这个等式两边进行平方，我们得到
$|\overrightarrow{DO}|^2 = \frac{1}{9} (\overrightarrow{DA}^2 + \overrightarrow{DB}^2 + \overrightarrow{DC}^2) + 2\overrightarrow{DA} \cdot \overrightarrow{DB} + 2\overrightarrow{DB} \cdot \overrightarrow{DC} + 2\overrightarrow{DC} \cdot \overrightarrow{DA})$.

由于$|DO|$是边长等于$a$的等边三角形外接圆的半径，因此$|\overrightarrow{DO}|^2 = |DO|^2 = \frac{1}{3} a^2$。

因为
$\frac{a^2}{3} = \frac{1}{9} (x^2 + y^2 + z^2 + xy + yz - zx)$

或者
$3a^2 = x^2 + y^2 + z^2 + xy + yz - zx$.

将这个等式与 (14) 相加，我们得到
$6a^2 = 3(x^2 + y^2 + z^2)$,
在哪里
$x^2 + y^2 + z^2 = 2a^2$.

准备考试的读者«Kvant»可能会问：他在解决考试问题时是否有权使用“基本关系”？当然，是的！然而，对于关系I-III，需要在试卷中输入使用关系。 （对于IV关系，当然参考课本就足够了。）

为了习惯自己使用基本关系，我们建议完成以下练习。其中，1-2借助I解决，3-4借助II解决，5-6借助III解决。

练习

1（MIPT，1970）。在三角形中，$ABC$ 二等分线 $A1$ 按比率 $|BD|: |CD| = 2:1$ 划分边 $BC$。中位数 $CE$ 将此二等分线除以什么比例？

2（密歇根州立大学，生物学院，1973 年）。通过面积为 1 的平行四边形$ABCD$的边$BC$的中点$M$和顶点$A$，画一条直线与对角线$BD$相交于点$Q$。求四边形$QMCD$的面积。

3（MIPT，1977）。规则特征$ABCA_1B_1C_1$的所有边的长度为$a$。考虑末端位于侧面对角线 $BC_1$ 和 $CA_1$ 上且平行于平面 $ABB_1A_1$ 的线段。

1) 这些线段之一是通过对角线 $BC_1$ 的点 $M$ 绘制的，使得$|BM|: |BC_1| = 1:3$。求它的长度。

2) 找到所考虑的所有线段的最短长度。

4（MIPT，1977）。正则直线$SABCD$的底边$ABCD$的长度为$a$，侧边的长度为2a。考虑末端位于底部对角线 $BD$ 和侧边 $SC$ 上的线段，平行 (SAD)。

找到所考虑的所有线段的最短长度。

5（MIPT，1978）。在正确的直接特征$ABCA_1B_1C_1$中，底边的长度为4a，侧边的长度为$a$。点$D$和$E$是边$A_1B_1$和$BC$的中点。端点位于线 $AC$ 和 $BB_1$ 上的线段 $MN$ 与线 $DE$ 相交并垂直于它。求该线段的长度。

6（MIPT，1978）。立方体边长$ABCDA_1B_1C_1D_1$等于$a$。点$P, K, L$分别是边$AA_1, A_1D_1, B_1C_1$的中点，点$Q$是面$CC_1D_1D$的中心。端点位于线 $AD$ 和 $KL$ 上的线段 $MN$ 与线 $PQ$ 相交并垂直于它。求该线段的长度。
