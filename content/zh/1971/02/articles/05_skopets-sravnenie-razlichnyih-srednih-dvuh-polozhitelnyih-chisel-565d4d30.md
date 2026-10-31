---
id: 1971-2-skopets-sravnenie-razlichnyih-srednih-dvuh-polozhitelnyih-chisel-565d4d30
issue: kvant_1971_2
year: 1971
number: "2"
title: 比较两个正数的不同平均值
authors:
  - Скопец З. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 25
page_labels: 20-23
tag: F205
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 063d6a5827c7a083ebc70297f31fc69b5fffe072052fde32aac39fc7e49e087b
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/05_skopets-sravnenie-razlichnyih-srednih-dvuh-polozhitelnyih-chisel-565d4d30.md
source_content_sha256: b58de987b7777e6156724bf8e4094c9b891053c126ce80a58690175aa28eddc0
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

比较
不同的媒介
两个积极
数字

3. A·斯科佩茨

众所周知，两个正数$a$和$b$或两个长度为$a$和$b$的线段与其算术平均值$\frac{a+b}{2}$和几何平均值$\sqrt{ab}$以及$\sqrt{ab} \leq \frac{a+b}{2}$相关（该等式仅适用于$a=b$）。这个不等式的代数证明非常简单：

$$(a-b)^2 \geq 0, (a+b)^2 \geq 4ab,$$
$$ab \leq \left(\frac{a+b}{2}\right)^2 \text{ и } \sqrt{ab} \leq \frac{a+b}{2}.$$

几何证明基于直角三角形元素之间的一种度量关系：直角三角形的高度，降低到斜边，是直角三角形腿在斜边上的投影的几何平均值。该高度不超过三角形外接圆的半径，而斜边线段的算术平均值恰好等于该圆的半径。

除了所示的两个间均值之外，还考虑了两个更频繁出现的均值：二次均值 $\sqrt{\frac{a^2+b^2}{2}}$ 和调和均值 $\frac{2}{\frac{1}{a}+\frac{1}{b}} = \frac{2ab}{a+b}$。

让我们先给出代数证明，然后再给出几何证明

$$\frac{2ab}{a+b} \leq \sqrt{ab} \leq \frac{a+b}{2} \leq \sqrt{\frac{a^2+b^2}{2}},$$

并且在所有情况下等号成立当且仅当$a=b$。让我们用字母 $M, N, K, L$ 交替表示 (1) 中写出的平均值。我们已经检查了不等式$N \leq K$。尚需证明 1) $K \leq L$; 2）$M \leq N$。

1) $K^2 - L^2 = \left(\frac{a+b}{2}\right)^2 - \frac{a^2+b^2}{2} = -\frac{1}{4} (a-b)^2 \leq 0,$

即，$K \leq L$，$K=L$仅适用于$a=b$；

2) $M^2 - N^2 = \frac{4a^2b^2}{(a+b)^2} - ab = -\frac{ab (a-b)^2}{(a+b)^2} \leq 0,$

即，$M \leq N$ 和$M=N$ 位于$a=b$。

不等式(1)的有效性已被证明*)。

我们现在来看看这些不等式的几何证明，结果可能是

*) 这些不等式已经在 A. P. Savin 的文章“最大值、最小值和平均定理”（«Kvant» No. 11, 1970）中讨论过。

⟦folio 21⟧

在解决几何问题时很有用。

令给定的两个线段为$a$和$b$。如果$a=b$，那么通过检查我们确信不等式（1）的有效性。假设$a>b$并构造一个梯形$ABCD$，底边$AB$和$CD$等于$a$和$b$（图1）的对应关系。让我们画一条割线$l$，使它与梯形的底平行，并将其切成两个相等的梯形$T_1(ABL_2L_1)$和$T_2(L_1L_2CD)$。让我们计算线段$L_1L_2$的长度，用$x$表示。根据梯形 $T_1$ 和 $T_2$ 的等价性，可以得出 $(a+x)h_1=(x+b)h_2$，或者

$$h_1:h_2=(x+b):(a+x),$$

(2) 其中$h_1$是梯形$T_1$的高度，$h_2$是梯形$T_2$的高度。从三角形$AL_1U$和$DL_1V$的相似性可以得出：

$$h_1:h_2=(a-x):(x-b).$$

(3) 比较(2)和(3)，我们得到

$$\frac{x+b}{a+x}=\frac{a-x}{x-b},$$

$x^2-b^2=a^2-x^2$从哪里来，最后

$$x=\sqrt{\frac{a^2+b^2}{2}}.$$

所以，已经证明$L_1L_2=\sqrt{\frac{a^2+b^2}{2}}.$

考虑到（2），我们有 $h_1<h_2$，所以该段 $L_1L_2$ 靠近更大的基地 $AB$ 梯形大于其中线 $K_1K_2$， 平等的 $\frac{a+b}{2}$。诺利纳段 $x$平行于梯形的底边，其端部位于梯形的侧面，被包围在其底边的长度之间（这是从相似性得出的）。所以，当 $a>b$ 我们有 $\frac{a+b}{2}<\sqrt{\frac{a^2+b^2}{2}}$。即使当 $a<b$ （只需更改符号： $a$ 在 $b$ 和 $b$ 在 $a$）。因此，对于任何 $a$ 和 $b$ 我们有 $\frac{a+b}{2}\leq\sqrt{\frac{a^2+b^2}{2}}.$

让我们继续比较$N$和$K$。为此，我们绘制一条割线 $n$，以便将给定的梯形切割成两个相似（相似）梯形 $T_1'(ABN_2N_1)$ 和 $T_2'(N_1N_2CD)$ (图 2)。让我们用 $y$ 表示线段 $N_1N_2$ 的长度。根据梯形 $T_1'$ 和 $T_2'$ 的相似性，可以得出 $a:y=y:b$，或者

$$y=\sqrt{ab}.$$

因此，$N_1N_2=\sqrt{ab}$。根据梯形的相似性（考虑到（4））还可以得出：

$$AN_1:N_1D=a:y=\sqrt{\frac{a}{b}}>1.$$

这意味着线 $n$ 距离梯形的底$AB$ 更远，

⟦folio 22⟧

中间线是$K_1K_2$，因此是$N_1N_2 < K_1K_2$。因此，对于任意 $a$ 和 $b$ 我们有

$$\sqrt{ab} \leq \frac{a+b}{2}.$$

最后，让我们通过该梯形对角线的交点 $O$ 画一条线 $m$，平行于其底边，并在点 $M_1$ 和 $M_2$ (图 3) 处与侧边相交。显然$AM_1:M_1D = AO:OC = a:b$。

但是$\frac{a}{b} > \sqrt{\frac{a}{b}}$，因为$a > b$。因此，考虑到（5），我们得出结论，线段$M_1M_2$比线段$N_1N_2$更接近梯形的较小底，因此$M_1M_2 < N_1N_2$。另一边，

$$M_1O:a = DO:DB = CO:CA = OM_2:a.$$

这意味着$M_1O = OM_2$。下一个，

$$\frac{M_1O}{a} + \frac{OM_2}{b} = \frac{DO}{DB} + \frac{BO}{DB} = 1.$$

由此得出$M_1M_2 = 2M_1O = 2\frac{1}{a} + \frac{1}{b}$，因此$M_1M_2 = \frac{2ab}{a+b}$。所以，如果$a > b$，则$M < N$。同理，证明$M < N$如果$a < b$。因此，对于任何$a$和$b$，我们有

$$\frac{2ab}{a+b} \leq \sqrt{ab}.$$

这正确地证明了不等式（1）。

所以四个都是平均水平

$$M_1M_2 = M = \frac{2ab}{a+b}; \quad N_1N_2 = N = \sqrt{ab};$$

$$K_1K_2 = K = \frac{a+b}{2}; \quad L_1L_2 = L = \sqrt{\frac{a^2+b^2}{2}}.$$

$a$和$b$这两个线段下面得到了一个几何原点：如果这两个线段作为梯形的底，那么靠近梯形较大底边的是二次均值，接下来是算术平均，然后是几何平均，最后是调和平均（图4）。显然，这些线段的长度并不取决于梯形的形状 - 对于具有给定长度 $a$ 和 $b$ 底边的所有梯形，相应梯形的指示平均值相等。当$a = b$时，梯形变成平行四边形，中间的四个四边形全部重合，等于$a$。

仍然需要在给定的段 $a$ 和 $b$ 上构造这四个平均值。我们给出这样的构造，以便人们能够以另一种方式确信不等式（1）的真实性。

让我们在点 $O$ 一侧的直线上绘制线段 $OA = a$、$OB = b$，其中 $a < b$。令 $S$ 为线段 $AB$ (图 5) 的中点。然后

$$OS = a + \frac{b-a}{2} \text{ или } OS = \frac{a+b}{2} = K.$$

⟦folio 23⟧

图 5.

$$OC = M = \frac{2ab}{a+b};$$
$$OP = N = \sqrt{ab};$$
$$OS = K = \frac{a+b}{2};$$
$$OE = L = \sqrt{\frac{a^2+b^2}{2}};$$
$$M < N < K < L.$$

让我们在线段 $AB$ 上构造一个圆，就像在直径上一样，并从点 $O$ 向其绘制切线 $OP$ 和 $OQ$（$P, Q$ 是切点）。让我们使用从点 $O$ 到圆绘制的割线和切线段之间的关系：
$$OP^2 = ab.$$ 因此，$OP = \sqrt{ab} = N$，$N < K$。接下来，让$PQ$与$OS$相交于$C$。然后 $OP^2 = OS \cdot OC$ 和
$$OC = ab: \frac{a+b}{2} = \frac{2ab}{a+b} = M,$$
和$M < N$。

最后，我们构造垂直于$AB$的半径$SE$。我们有
$$OE^2 = \left(\frac{a+b}{2}\right)^2 + \left(\frac{a-b}{2}\right)^2,$$
$$OE = \sqrt{\frac{a^2+b^2}{2}} = L,$$
和$K < L$。所以，如果$a \neq b$，那么$M < N < K < L$。

练习
1. 在点 $O$ 一侧的直线上，布置线段 $OA = a, OB = b, a < b,$，并构造一个直径为 $AB$、中心为 $S$ 的圆 $k$。接下来，构造以 $O$ 为中心、半径为 $OP$ 的$k_1$ 和直径为 $OS$ 的$k_2$。

证明如果穿过$O$的直线与位于$k$内部的直线$g, k_1$和$k_2$的部分相交于点$C_1, P_1, S_1$，并且与圆$k$相交于点$A_1$和$B_1$，则
$$OC_1 = \frac{2a_1b_1}{a_1+b_1},$$
$$OP_1 = \sqrt{a_1b_1},$$
$$OS_1 = \frac{a_1+b_1}{2} \quad (a_1 = OA_1, b_1 = OB_1).$$

2. 求连接两个数字 $a$ 和 $b$ 的每三个平均值的偶数比率：
$$M = \frac{2ab}{a+b},$$
$$N = \sqrt{ab},$$
$$K = \frac{a+b}{2},$$
$$L = \sqrt{\frac{a^2+b^2}{2}}.$$

3. 证明下列不等式的正确性：
a) $N - M \leqslant K - N,$
b) $K - M \leqslant L - N,$
b) $L - K \leqslant K - N.$

4. 圆心 $S$ 在直角坐标系 x 轴上的圆与该轴相交于点 $A(a, 0)$ 和 $B(b, 0), a > 0, b > 0, a < b$。通过原点 $O$ 的割线与圆相交于点 $A_1$ 和 $B_1$。写出割线上那些点 $C_1(x, y)$ 所属直线的方程，其中
$$(OC_1)^2 = \frac{1}{2} \left[ (OA_1)^2 + (OB_1)^2 \right].$$

5. 在三角形$ABS$的边$AB$在点$A$之外的延续上，有一个底点$O$，通过该点画一条线与对应于点$B_1$和$A_1$的$AS$和$BS$相交。通过线 $AA_1$ 和 $BB_1$ 的交点 $P$，绘制一条线 $SP$，与 $AB$ 相交于点 $C$。证明$c = \frac{2ab}{a+b}$，其中$OA = a, OB = b, OC = c$。

6. 给定一个平行四边形 $OABC$ 和与 $AC$ 平行的三角形 $ABC$ 的中线 $MN$。通过顶点$O$画一条直线；与相应线的线 $BC, CA, AB, MN$ 相交于点 $A_0, B_0, C_0, D_0$。证明$\frac{1}{a} + \frac{1}{b} + \frac{1}{c} = \frac{3}{d}$，其中$OA_0 = a, OB_0 = b, OC_0 = c, OD_0 = d$；点$A_0, B_0, C_0, D_0$位于$O$的一侧（$d$是线段$a, b, c, d$的调和平均值）。

如果点 $A_0, B_0, C_0, D_0$ 不位于 $O$ 的同一侧，那么规定的等式会如何变化？
