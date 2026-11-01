---
id: 1985-3-resheniya-zadach-m891-m895-f903-f907-1c0660d5
issue: kvant_1985_3
year: 1985
number: "3"
title: 问题解决方案M891—M895； F903—F907
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28-31
tag: T8MA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c6a26a935cecf017da55b7dd32105a04b38548c9e095d4a26890104e35905a10
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/14_resheniya-zadach-m891-m895-f903-f907-1c0660d5.md
source_content_sha256: 745b7593093f06d36e4cf134ddebb58f92107bd67201a45314dc9004ba934ab1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

—4q, ..., —1984q, 1985q (q>0), respectively.
Prove that one of the balls has an everywhere positive charge density on its surface. The distances between the balls are finite.

V. A. Yasinski

P927. A charged particle flies through a scintillation counter; the scintillating molecules along its trajectory emit light. The light is emitted isotropically (i.e. uniformly in all directions) at each point. What part of the emitted light will leave the scintillator into the air, if the refraction coefficient of the scintillating matter is $n=1.6$? Light absorption in the scintillator may be neglected.

Remark. The solid angle at the vertex of a cone equals $\Omega=2\pi(1-\cos\theta)$, where $\theta$ is the angle between the cone's axis and its generator.

S. A. Khorozov

问题解决方案

M891 — M895; F903 — F907

在这个三角形$ABC$中，我们用$a$和$b$表示边长$BC$和$CA$，用$m_a$和$m_b$表示中线$AA_1$和$BB_1$的长度，用$M$表示中线的交点（参见， 图）。由于从一条边的中点到中线交点的距离等于其三分之一，并且四边形 $MA_1CB_1$ 是围绕圆描述的，因此等式 $m_a/3+b/2=m_b/3+a/2$ 或

$$m_a + \frac{3b}{2} = m_b + \frac{3a}{2}. \tag{1}$$

进一步，三角形$AA_1C$和$BB_1C$面积相等（等于三角形$ABC$的面积）且有共同内切圆，因此它们的周长相等：$m_a+a/2+b=m_b+b/2+a$，即

$$m_a + \frac{b}{2} = m_b + \frac{a}{2}. \tag{2}$$

从(1)减去等式(2)，我们得到$a=b$。

请注意，当圆接触三角形两条边和两条中线的延长线时，问题的陈述也成立。

A·A·穆拉戈夫

M892。 a) 证明数$2^m+2^k$和数$3^m+3^k$之间存在无穷多阶，并且数$4^m+4^k$、$5^m+5^k$和$6^m+6^k$之间不存在单一平方整数（这里$m$和$k$是自然数，$m \neq k$）。
b)* 数字$7^m+7^k$中有正方形吗？

a) 首先让我们注意，如果数字$a^m+a^k$是一个正方形，那么有无限多个这种类型的正方形：$a^{m+2n}+a^{k+2n}=(a^n)^2 \cdot (a^m+a^k)$（这里$m$或$k$也可以等于零）。因此，$a=2$和$a=3$的问题的陈述来自等式$2^3+2^0=8+1=3^2$、$3^1+3^0=2^2$。

案例$a=4$。设$4^m+4^k=b^2$，其中$b$是整数，$m>k$；然后$4^{m-k}+1=(b/2^k)^2$或$4^n+1=c^2 (n=m-k, c=b/2^k)$。由此可见$(c+2^n)(c-2^n)=1$，这是非常不可能的。

⟦folio 29⟧

案例$a=5$。很容易看出，任何$m>1$的数字$5^m$都以数字25结尾，因此$5^m+5^k$只能以30（对于$k=1$）或50（对于$k>1$）结尾，因此不能是平方（以零结尾的平方必须能被100整除）。

案例$a=6$。 6 的幂总是以 6 结尾，这意味着数字 $6^m+6^k$ 总是以 2 结尾。但是整数的平方只能以 0、1、4、6、9 结尾。

6) 答：不。由于 7 除以 3 余数为 1，因此 7 的所有幂也具有相同的余数。因此，数字 $7^m+7^k$ 除以 3 时余数为 2，因此不能是平方 $((3n)^2$ 可以被 3 整除，但$(3n \pm 1)^2 = 3(3n^2 \pm 2n) + 1)$。

A. I. Zaichik、V. N. 杜布罗夫斯基

M893。 n 个计算机块中的每两个都通过电线连接。是否有可能用 n—1 种颜色中的一种覆盖这些电线，以便从每个块中出来 n—1 条不同颜色的电线，如果 a) $n=6$; b) $n=13$？

a) 答案：是的。所需的颜色显示在图处。

6) 答：不。事实上，如果使用任何一种颜色的$m$穿孔，则块的数量为$2m$（所有这些穿孔的末端数量，并且每个末端恰好连接到一个块）。但13是奇数。

这个问题通常被表述为为圆形游览器创建时间表的问题 - 在这种情况下，通过将游览器部分分成相同类型的对来回答相同颜色的电线。我们已经看到，对于奇数$n$，这个问题是无解的。可以证明，即使是 $n$ 也总有解（例如参见 O. Ore 的书《Invitation to Number Theory》（M.: Hayka, 1980, Chapter 8, § 3），以及《Correspondence Mathematical Descriptions》一书中问题 1.16 的解（M.: Hayka, 1981, p. 19））。

V·V·阿列克谢耶夫

M894。 a) 非负数的尾部之和为1。证明它们可以围绕一个圆间隔开，使得相邻数两两乘积的尾部之和不超过1/5。

b)* 圆周围有$n \geqslant 4$个非负数，其和等于1。证明所有n个相邻数的两两乘积之和不超过1/4。

a) 我们用反证法来证明。让我们假设对于任何数字 $a, b, c, d, e$ 的排列，我们都考虑大于 1/5 的总和，特别是（参见 图 1 和 2）：

$$ab+bc+cd+de+ea > 1/5,$$
$$ac+ce+eb+bd+da > 1/5.$$

从这里我们得到一个矛盾：

$$1 = (a+b+c+d+e)^2 = \frac{a^2+b^2}{2} + \frac{b^2+c^2}{2} + \frac{c^2+d^2}{2} +$$
$$+ \frac{d^2+e^2}{2} + \frac{e^2+a^2}{2} + 2[(ab+bc+cd+de+ea) +$$
$$+(ac+ce+eb+bd+da)] \geqslant$$
$$\geqslant 3(ab+bc+cd+de+ea) +$$
$$+ 2(ac+ce+eb+bd+da) > 1$$

（我们使用了不等式$x^2+y^2 \geqslant 2xy$）。

从解中可以清楚地看出，数非负性的条件不存在。任务审批

⟦folio 30⟧

（1/5 替换为 1/n）对于任何 $n$ 数字都有效。

6) 我们必须证明对于任何$n \geqslant 4$非负数$a_1, \dots, a_n$其总和为1，不等式成立
$$a_1a_2 + a_2a_3 + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

即使对于$n (n=2m)$，这种不等式也被无限证明：设$a_1 + a_3 + \dots + a_{2m-1} = a$；那么显然
$$a_1a_2 + \dots + a_na_1 \leqslant (a_1 + a_3 + \dots + a_{2m-1}) \times \times (a_2 + a_4 + \dots + a_{2m}) = a(1-a) \leqslant 1/4.$$

现在令 $n$ 为奇数，并令 $a_k$ 为给定数字中最小的。 （为了方便起见，我们假设$1 < k < n-1$ - 这并不限制$n \geqslant 4$的通用性。）让我们用$b_i = a_i$代表$i=1, \dots, k-1$，$b_k = a_k + a_{k+1}$和$b_i = a_{i+1}$代表$i=k+1, \dots, n-1$。将我们的不等式应用于数字$b_1, \dots, b_{n-1}$，我们得到：
$$a_1a_2 + \dots + a_{k-2}a_{k-1} + (a_{k-1} + a_{k+2})b_k + a_{k+2}a_{k+3} + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

仍然需要利用以下事实：
$$a_{k-1}a_k + a_ka_{k+1} + a_{k+1}a_{k+2} \leqslant a_{k-1}a_k + a_{k-1}a_{k+1} + a_{k+1}a_{k+2} \leqslant (a_{k-1} + a_{k+2})b_k.$$

请注意，一般而言，所示的估计值是准确的（不能减少）； a) 点评估 $1/n$ 当一切都达成时 $n$ 数字相等，并且在第 6) 点中 - 当其中两个等于 1/2，其余均为 0 时。
S.V.加什科夫、A.N.德兰辛科夫

**M895*。证明立方体的内切球面所截面积不超过立方体面面积的一半。当该部分是 a) 三角形、b) 四边形时展开箱子。 b) 证明在a)情况下，三角形正方体的完整曲面的面积小于面的面积。 （这三个面在第一个面的平面上的正交投影完全覆盖了它，并且投影的面积小于面本身的面积。）但是，我们将独立地证明 a），因为这将给出更一般的结果。

让我们用 $A, B, C$（三条边的公共顶点）来表示所考虑的立方体三角形截面的顶点；它们位于其上 - 通过 $V$，内切球与平面 $ABC, VAB, VBC, VCA$ - 到 $T, K, L, M$ 的接触点（最后三个点，非常方便，是立方体面的中心；图 1）。由于从一点 $AT=AK=AM, BT=BK=BL, CT=CL=CM$ 到球体的切线相等，因此三角形 $ABK$ 和 $ABT, BCL$ 和 $BCT, CAM$ 和 $CAT$ (图 1)，以及 $AVK$ 和 $AVM, BVK$ 和 $BVL, CVL$ 和$CVM$ (图 2) 两两相等，而且大小相等。因此，截面$ABC$的面积等于图1上的三角形面积之和$S_1$，三角形$VABC$完整曲面的面积$S_{\text{тетр}}$等于四边形$AKBV, BLCV$和$CMAV$的面积之和，即是总和的两倍

⟦folio 31⟧

图 2 上的$S_2$ 绿色、红色和黄色三角形区域：
$$S_{\text{тетр}} = 2S_2 = 2(S_{AKV} + S_{BKV} + S_{CLV}) = 2(S_{AKBV} + S_{CLV}).$$

令$S_0$为立方体面的面积。让我们证明，对于立方体边缘上从顶点 $V$ 发出的任意三个点 $A, B, C$，
$$S_1 = S_{ABK} + S_{BCL} + S_{CAM} \leq S_0 / 2$$
(1)
（特别是声明 a））。

为此，请注意，如果三个点中的两个（例如 $B$ 和 $C$）闭合，则三角形 $ABK$ 和 $ACM$ 的面积以及总和 $S_1$ 线性依赖于 $x=VA$（有关证明，请参阅图 3）。因此，您始终可以将点 $A$ 移动到边缘的末端，以便值 $S_1$ 增加（或者在任何情况下都不会减少）。同样可以从点$B$、$C$依次进行；因此，对于位于立方体顶点的点$A, B$和$C$，证明不等式（1）就足够了。这样的地点只有 4 个（直至重新指定为止）；它们显示在图 4。在两种情况下为$S_1=0$，在另外两种情况下为$S_1=S_0 / 2$。容易理解，除了后两种情况外，(1)中的不等式始终是严格的，但图 4, in 上的三角形$ABC$可以视为与所写球体相切的截面的极限位置，因此问题a）中的估计是准确的。

现在我们来证明不等式
$$S_2 = S_{AKBV} + S_{CLV} < S_0 / 2$$
（以及随之而来的 - 声明 b））。

让我们定义$KB \geqslant KA$。显然，直线$KB$将立方体的面分成面积为$S_0 / 2$的两个相等的梯形，其中一个-$VBB_1U$（图2）由四个三角形$AKBV$和$AKB_1U$组成。因此，足以证明
$$S_{CLV} < S_{AKB_1U}.$$
让我们在边 $UV$ 上绘制线段 $UC_1=VC$ (图 5)；那么三角形$C_1KU$和$CLV$相等，并且$\angle C_1KU = \angle CLV = \angle AKB_1$。

（事实上​​，根据 图 2 上的单臂三角形相等，可以得出 $2(\angle CLV + \angle AKB) = \angle AKB + \angle BLC + \angle CMA = \angle ATB + \angle BTC + \angle CTA = 360^\circ = 2(\angle AKB_1 + \angle AKB)$。）因此，$\angle B_1KU = \angle C_1KA$ (图 5)，此外还有$KB_1 = KB \geqslant KA$、$KU > KC_1$，因此$S_{AKC_1} < S_{B_1KU}$，即
$$S_{CLV} = S_{C_1KU} = S_{AKC_1} + S_{AKU} < S_{B_1KU} + S_{AKU} = S_{AKB_1U}.$$
与 a) 点相同的消息表明此处的估计是准确的。

6) 让 $ABCD$ - 立方体的四边形部分，将一条边与其分开 $UV$ 并将面与中心相交 $K, L, M, N$ (图 6).如上，很容易看出它的面积等于总和 $S_3$ 三角形的面积 $ABK, BCL, CDM$ 和 $DAN$，这显然小于总和
$$S_4 = S_{ABK} + S_{BLCV} + S_{CDM} + S_{DNAU}.$$

（最后见第34页）
