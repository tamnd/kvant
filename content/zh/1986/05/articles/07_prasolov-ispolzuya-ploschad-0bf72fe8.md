---
id: 1986-5-prasolov-ispolzuya-ploschad-0bf72fe8
issue: kvant_1986_5
year: 1986
number: "5"
title: 使用该区域...
authors:
  - Прасолов В. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 21
page_labels: 16-19
tag: BRO4
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4be6af410b575fcc93549128ae08848b68d2110d15f086ba868451608042ea40
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/07_prasolov-ispolzuya-ploschad-0bf72fe8.md
source_content_sha256: cf322fa8f4cfe551fd2d2aa6a80469b8c1b94258f887545a763994fdc9910087
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

使用面积...

V·V·普拉索洛夫

在解决各种数学问题时，考虑问题陈述中未出现的一些辅助元素通常很有用。我们将了解使用原始多边形的面积解决几何问题的基本技术。

技巧1.如果一个多边形被切割成多个多边形，那么它们的面积之和等于原多边形的面积。

使用此技术的最佳替代方法是毕达哥拉斯定理的众多证明之一。

示例 1（毕达哥拉斯定理）。证明长度的平方和是斜边长度的平方。

解决方案。令 $a, b$ 为正方形的长度，$c$ 为斜边的长度。让我们证明作用在边$a$和$b$上的面积之和等于边上$a$和$b$上的正方形的面积（这是相当明显的），并且在第二个中 - 作用在边上有正方形$a$和$b$的4个直角三角形以及边上$c$上的正方形上（这需要一些理由，例如，这样：很明显，所得四边形的所有边都等于$c$，并且角度很容易计算）。

示例 2. 从正三角形 $ABC$ 内部的点 $O$ 开始，垂线 $OA_1, OB_1, OC_1$ 分别垂向边 $BC, AC, AB$。证明$OA_1 + OB_1 + OC_1$之和不依赖于点$O$的位置并且等于三角形的高度。

解决方案。设三角形边长$ABC$为$a$，高为$h$。显然$S_{ABC} = S_{BCO} + S_{ACO} + S_{ABO}$，即$\frac{1}{2}ah =$

⟦folio 17⟧

$$\frac{1}{2} aOA_1 + \frac{1}{2} aOB_1 + \frac{1}{2} aOC_1.$$
波兹图穆$h = OA_1 + OB_1 + OC_1$。

示例 3. 将一个半径为 $r$ 的圆外接的多边形任意切成三角形。证明这些三角形的内切圆半径之和大于$r$。

解决方案。让我们用$r_1, ..., r_n$表示所得三角形的内切圆的半径，用$P_1, ..., P_n$表示它们的周长，用$S_1, ..., S_n$表示它们的面积。我们用$S$和$P$表示原始多边形的面积和周长。从$P_i < P$开始，

$$r_1 + ... + r_n = \frac{2S_1}{P_1} + ... + \frac{2S_n}{P_n} > \frac{2S_1}{P} + ... + \frac{2S_n}{P} = r.$$

技巧2. 线段的长度之比可以用三角形的面积之比来代替。

例4. 在三角形$ABC$的边$AB$和$AC$上分别取点$C_1$和$B_1$。令 $O$ 为线段 $BB_1$ 和 $CC_1$ (图 2) 的交点。如果 $\frac{BC_1}{AC_1} = \alpha$ 和 $\frac{CB_1}{AB_1} = \beta$ 则计算 $\frac{BO}{B_1O}$。

解决方案。在我们开始解决应用问题的这一重要部分之前，让我们注意到它有些复杂。事实上，对于任何三角形$ABC$，都可以用点$B_1$和$C_1$按给定的比率除以其边$AC$和$AB$。为什么条件中没有指定三角形$ABC$的类型，而只指定了$\frac{BC_1}{AC_1}$和$\frac{CB_1}{AB_1}$？

图 1.

图 2.

让我们继续讨论解决方案。显然$\frac{BO}{B_1O} = \frac{S_{BOC}}{S_{B1OC}}$。现在让我们计算$\frac{S_{AOC}}{S_{B1OC}}$和$\frac{S_{BOC}}{S_{AOC}}$。显然$\frac{S_{AOC}}{S_{B1OC}} = \frac{AC}{B_1C} = \frac{AB_1 + B_1C}{B_1C} = 1 + \frac{AB_1}{B_1C}$。由于三角形$BOC$和$AOC$有公共边$OC$，因此它们的面积之比等于高度减去$OC$的长度之比。高度比依次为$\frac{BC_1}{AC_1}$。因此$\frac{S_{BOC}}{S_{AOC}} = \frac{BC_1}{AC_1}$。结果，我们得到$\frac{BO}{B_1O} = \frac{S_{BOC}}{S_{B1OC}} = \frac{S_{BOC}}{S_{AOC}} \cdot \frac{S_{AOC}}{S_{B1OC}} = \alpha(1 + \frac{1}{\beta})$。

示例 5（Ceva 定理）。在三角形$ABC$的边$AB$、$BC$、$CA$上分别取点$C_1$、$A_1$、$B_1$。证明直线 $AA_1$、$BB_1$、$CC_1$ 相交于一点当且仅当 $\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$。

解决方案。首先让直线 $AA_1$、$BB_1$ 和 $CC_1$ 相交于点 $O$。和上一个问题一样，我们得到$\frac{CA_1}{A_1B} = \frac{S_{ACO}}{S_{ABO}}$、$\frac{BC_1}{C_1A} = \frac{S_{BCO}}{S_{ACO}}$和$\frac{AB_1}{B_1C} = \frac{S_{ABO}}{S_{BCO}}$。将这些等式相乘，我们得到 $\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$。

现在假设$\frac{AB_1}{B_1C} \times \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1$，路径$O$是一个点

⟦folio 18⟧

线段 $AA_1$ 和 $BB_1$ 的交集。让我们用 $C'_1$ 表示直线 $OC$ 与线段 $AB$ (图 3) 的交点。那么，正如我们刚刚证明的那样，

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC'_1}{C'_1A} = 1 = \frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A}.$$

因此，$$\frac{BC'_1}{C'_1A} = \frac{BC_1}{C_1A}.$$需要注意的是，如果点$X$沿线段$AB$移动（不超出其限制），则$\frac{BX}{XA}$的值单调变化，因此$C'_1 = C_1$，即线段$AA_1$、$BB_1$和$CC_1$相交于一点。

这个替代定理值得一些评论。知道三角形的所有中线以及所有三边线和所有高都相交于一点的读者可以理解所有这些事实都是一些更一般定理的结果。这是真的：它们是塞瓦定理的结果，可以通过相当简单的计算从中获得。也容易证明，连接三角形顶点和内切圆与边的切点的线段相交于一点。

然而，高度有一个困难：如果三角形$ABC$的角度$C$是类型，那么从$C$省略的高度不会落在边$AB$上，而是落在它的延续上。事实证明，Ceva 定理可以重新表述（当然，也可以证明），以便当点 $A_1$、$B_1$、$C_1$ 不是在边 $BC$、$CA$、$AB$ 上取，而是在线 $BC$、$CA$ 上取时，该定理仍然成立， $AB$。为此，您需要为线段分配 ± 符号，具体取决于相应的向量是指向相同方向还是不同方向（在 Cheva 定理的公式中，仅涉及位于同一直线上的线段长度的比率）。我们建议读者自己想出所需的措辞。

示例 6. 给定一个凸多边形 $A_1A_2...A_n$。在$A_1A_2$边上取点$B_1$和$D_2$，在$A_2A_3$边上取点$B_2$和$D_3$等。因此，如果我们构造平行四边形$A_1B_1C_1D_1$，...，$A_nB_nC_nD_n$，则直线$A_1C_1$，...，$A_nC_n$相交在某一时刻$O$。证明$A_1B_1 \cdot A_2B_2 \cdot ... \cdot A_nB_n = A_1D_1 \cdot A_2D_2 \cdot ... \cdot A_nD_n$。

解决方案。由于$A_iB_iC_iD_i$是平行四边形，并且点$O$位于其对角线$A_iC_i$的延长线上，根据三角形$A_iB_iC_i$和$A_iC_iD_i$的面积相等以及相似性消息，可以得出$$\frac{A_iB_i}{A_iD_i} = \frac{h_i}{h_{i-1}},$$，其中$h_i$是从点$O$到边$A_iA_{i+1}$的距离。我们留下了 $i=1$、...、$n$ 等式的可变性。

技巧3. 各种面积公式可以让您获得边长、高度、周长等之间的对应关系。

例 7. 三角形的边长构成等差数列。证明这个三角形的内切圆半径等于其中一个高的1/3。

解决方案。令边长$a$、$b$、$c$构成等差数列。然后我们得到$p$的米数等于$$\frac{3}{2}b.$$，从$$\frac{1}{2}h_b \cdot b = S = r \cdot p = \frac{3}{2}r \cdot b,$$我们得到$r = b/3$。

示例 8. 在三角形 $ABC$ 内取点 $M$。让我们用$R_a$，$R_b$，$R_c$表示从点$M$到顶点$A$，$B$，$C$的距离，以及从点$M$到边$BC$，$CA$的距离， $AB$分别乘$d_a$、$d_b$、$d_c$。

a) 证明$a \cdot R_a \geq c \cdot d_c + b \cdot d_b$。

b) （Erdős-Mordell 不等式。）证明

$$R_a + R_b + R_c \geq 2(d_a + d_b + d_c).$$

解决方案。 a) 让我们从垂直于$BK$和$CL$的点$B$和$C$下降到直线

⟦folio 19⟧

木鱼马（图4）。令$a_1=BK$，$a_2=CL$。显然$a_1+a_2 \leq a$。这就是为什么
$$\frac{1}{2} a R_a \geq \frac{1}{2} a_1 R_a + \frac{1}{2} a_2 R_a = S_{ABM} + S_{ACM} = \frac{1}{2} b d_b + \frac{1}{2} cd_c.$$
请注意，在证明中我们仅使用点 M 位于角 BAC 内的事实，而不是点 M 位于三角形内的事实。
6) 将不等式应用到关于角 A 的平分线与 M 对称的点 a) 上（这与 a) 点的注释一致），我们得到不等式
$$R_a \geq \frac{c}{a} d_b + \frac{b}{a} d_c.$$
同样地，
$$R_b \geq \frac{c}{b} d_a + \frac{a}{b} d_c$$ 和
$$R_c \geq \frac{a}{c} R_b + \frac{b}{c} R_a.$$
添加这些不等式，我们得到
$$R_a + R_b + R_c \geq \left( \frac{b}{c} + \frac{c}{b} \right) d_a + \left( \frac{c}{a} + \frac{a}{c} \right) d_b + \left( \frac{b}{a} + \frac{a}{b} \right) d_c \geq 2(d_a + d_b + d_c),$$
从$\frac{x}{y} + \frac{y}{x} \geq 2$开始。
埃尔多斯-莫德尔不等式有着相当长的历史。 1935年，匈牙利著名数学家P. Erdős提出不等式
$$R_a + R_b + R_c \geq 2(d_a + d_b + d_c),$$
然而，他无法证明这一点。第一个证明这个不等式的是英国人L. J. Mordell，同年1935年，但他的证明相当复杂，只有多次数学化简的成功才将Erdős-Mordell不等式证明为如此简单的形式。
接待 4. 如果通过位于平行四边形 ABCD 内的点 E 画出平行直边，并将其分成四个平行四边形，则与顶点 B 和 D 相邻的平行四边形大小相等当且仅当点 E 位于对角线 AC 上。
我们邀请读者独立证明这个简单的陈述。
例9 通过位于平行四边形ABCD内的点M，绘制直线PR和QS，平行边BC和AB（点P、Q、R、S分别位于边AB、BC、CD、DA上）。证明直线 BS、PD 和 MC 相交于一点 (图 5)。
解决方案。通过线BS和CM的交点N，我们画线Q$_1$S$_1$和P$_1$R$_1$，平行线QS和PR（点P$_1$，Q$_1$，R$_1$，S$_1$分别位于边AB，BC，CD，DA上）。让我们用 F 和 G 表示直线 PR 与 Q$_1$S$_1$、P$_1$R$_1$ 和 QS 的交点。由于点 M 位于平行四边形 NQ$_1$CR$_1$、S$_{FQ_1QM} = S_{MRR_1G}$，即 S$_{NQ_1QG} = S_{NFRR_1}$ 的对角线 NC 上。点 N 位于平行四边形 ABQS 的对角 BS 上，因此 S$_{AP_1NS_1} = S_{NQ_1QG} = S_{NFRR_1}$。因此，点N位于平行四边形APRD的对角线PD上。

（最后见第43页）
