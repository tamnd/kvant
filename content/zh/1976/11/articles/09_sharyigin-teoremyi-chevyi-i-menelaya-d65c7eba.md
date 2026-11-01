---
id: 1976-11-sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba
issue: kvant_1976_11
year: 1976
number: "11"
title: Ceva 和 Menelaus 定理
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 31
page_labels: 22, 24, 25, 26, 27, 28, 29
tag: 7DBD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f6dc4b327ce16fab2e27fd39b0774f8ba707f5182c7e41d827bbb0d29814cdaf
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/09_sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba.md
source_content_sha256: 248dcaa44178532f04d32ae4e049eb2dd0a2f95d1f9291419f2508f358d94c6d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

几何学从三角形开始。翻阅几何学校教科书，我们会发现第一个有意义的定理与三角形特别相关。前面所有的只是公理、定义或者它们的最简单的推论。在其出现之初，该计划本质上是“三角形的几何形状”。

《三角形的几何》可以为以欧拉、托里拆利和莱布尼茨的名字命名的定理感到自豪。十九世纪和二十世纪之交，由于大量研究三角形的著作，甚至形成了整个平面测量学的一部分，称为“三角形的新几何”。这些作品中的许多现在看起来都没有被列出并且不完美。其中使用的术语是半写的，只能在百科全书中找到。然而，“新几何”的一些定理至今仍然存在。本文讨论了两个这样的定理 - Cheva 定理和 Menelaus 定理 *)。

切瓦定理和墨涅劳斯定理可以称为“对偶”定理：它们的表述相似（每个定理出现在两个领域）并被证明，在解决问题时它们是可以互换的。事实证明，切瓦和墨涅拉俄斯定理在需要“澄清点和线之间的关系”的情况下特别有用——例如，证明三条线相交于一点、三点位于同一条线上等。

*) 任何希望更详细地了解三角形几何的人可以参考 S. I. Zetel 的书“New Geometry of a Triangle”（M., Uchpedgiz, 1962）。

⟦folio 24⟧

图 2.

证明。首先，我们检查 $R$ 和 $R^*$ 是否具有相同的符号。很容易验证，改变其中一个向量$a, b, c, a_1, b_1, c_1$的方向不会改变值$R^*$（$\omega, \omega_1$），因此可以通过某种方式选择它们每个的方向；例如，向量 $a, b, c, a_1, b_1, c_1$ 可以被认为与向量 $\overrightarrow{BC}, \overrightarrow{CA}, \overrightarrow{AB}, \overrightarrow{AA_1}, \overrightarrow{BB_1}$ 和 $\overrightarrow{CC_1}$ (图 2) 方向一致。在这种情况下，表达式$R(\Delta, \Delta_1)$中包括的三个分数中的每一个都具有与表达式$R^*$($\omega, \omega_1$)中包括的对应分数相同的符号。例如，分数

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} \text{ и } \frac{\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})}{\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})}$$

如果点 $C_1$ 位于点 $A$ 和 $B$ 之间，则为正，并且在相反的情况下（图 3 和 2）进行印记。

仍有待证明$|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$。我们有

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} = \frac{S_{\Delta ACC_1}}{S_{\Delta BCC_1}} = \frac{1/2 |AC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{1/2 |BC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|} = \times \frac{|AC|}{|BC|} \cdot \frac{|\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{|\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|},$$

$$\left\{ \frac{\overrightarrow{BA_1}}{\overrightarrow{A_1C}} \right\} = \frac{|AB|}{|AC|} \cdot \frac{\sin \theta (\overrightarrow{c}, \overrightarrow{a_1})|}{|\sin \theta (\overrightarrow{b}, \overrightarrow{a_1})|},$$

$$\left\{ \frac{\overrightarrow{CB_1}}{\overrightarrow{B_1A}} \right\} = \frac{|BC|}{|AB|} \cdot \frac{\sin \theta (\overrightarrow{a}, \overrightarrow{b_1})|}{|\sin \theta (\overrightarrow{c}, \overrightarrow{b_1})|}.$$

图 3.

Variable these three equalities, we get that $|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$.引理已得证。

接下来我们需要一个直接从定义得出的等式 $R^*(\omega, \omega_1)$:

$$R^*(\omega, \omega_1) = \frac{1}{R^*(\omega_1, \omega)}. \tag{4}$$

塞瓦定理。 In order for the lines $AA_1, BB_1$ and $CC_1$ to intersect at one point, it is necessary and sufficient that the equality

$$R(\Delta, \Delta_1) = 1, \tag{5}$$

或同等的平等

$$R^*(\omega, \omega_1) = 1. \tag{5'}$$

墨涅劳斯定理。 In order for the points $A_1, B_1, C_1$ to lie on the same line, it is necessary and sufficient that the equality

$$R(\Delta, \Delta_1) = -1, \tag{6}$$

或同等的平等

$$R^*(\omega, \omega_1) = -1. \tag{6'}$$

Ceva定理的证明

必要性。让线 $AA_1, BB_1, CC_1$ 相交于一点。 Let us prove that conditions (5) and (5') are satisfied.

*) 表达式$R^*(\omega_1, \omega)$是从互向量$a$和$a_1$、$b$和$b_1$、$c$和$c_1$的表达式$R^*(\omega, \omega_1)$获得的。

⟦folio 25⟧

图 4a.

请注意，如果直线 $AA_1$、$BB_1$ 和 $CC_1$ 相交于一点，则所有三个点 $A_1$、$B_1$ 和 $C_1$ 都位于三角形 $ABC$ 的边上，或者其中一个点位于三角形的边上，另外两个点位于相应边的延长线上。在第一种情况下，表达式$R(\Delta, \Delta_1)$中包含的所有其他分数都是正数，在第二种情况下，$R(\Delta, \Delta_1)$中包含的三个分数之一是正数，另外两个是负数，因此表达式$R(\Delta, \Delta_1)$（因此$R^*(\omega, \omega_1)$ - 请参阅引理）再次大于零。 Let us now prove that $|R^*(\omega, \omega_1)| = 1$ (since $R^*(\omega, \omega_1) > 0$, it will follow that $R^*(\omega, \omega_1)$ is equal to one). Let us denote the intersection point of lines $AA_1$, $BB_1$ and $CC_1$ by $D$ (图 4a).应用正弦定理，我们得到

$$\frac{\sin \theta \vec{b}, \vec{c}_1}{\sin \theta \vec{b}, \vec{a}_1} = \frac{|DA|}{|DC|},$$

$$\frac{\sin \theta \vec{c}, \vec{a}_1}{\sin \theta \vec{c}, \vec{b}_1} = \frac{|DB|}{|DA|},$$

$$\frac{\sin \theta \vec{a}, \vec{b}_1}{\sin \theta \vec{a}, \vec{c}_1} = \frac{|DC|}{|DB|}.$$

改变这些等式，我们看到 $|R^*(\omega, \omega_1)| = 1$。从而证明了必要性。

图 46.

“通过矛盾。” Let us assume that $R(\Delta, \Delta_1) (= R(\omega, \omega_1)) = 1$, but the lines $AA_1$, $BB_1$ and $CC_1$ do not pass through the same point (图 46).让我们用$D_1$表示线$AA_1$和$BB_1$的交点，用$C'_1$表示线$AB$和$CD_1$的交点。 Since lines $AA_1$, $BB_1$ and $CC_1$ intersect at one point,

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{C'_1}B} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1.$$

但根据条件

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1,$$

在哪里

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} = \left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\}.$$

Since both the point $C_1$ and the point $C'_1$ lie on the line $AB$, it follows that the points $C_1$ and $C'_1$ coincide. Ceva 定理得到证明。

墨涅拉俄斯定理的证明

必要性。 It is known that the points $A_1$, $B_1$ and $C_1$ lie on the same line. It is necessary to prove equalities (6) and (6′).

再次注意，如果点 $A_1$、$B_1$ 和 $C_1$ 位于同一条线上，那么它们要么都在三角形的延长线 $BC$、$AC$ 和 $AB$ 边上。

⟦folio 26⟧

图 5.

缺口 $ABC$，或其中两个点 $A_1, B_1, C_1$ 位于对应边，第三个位于延续。在这两种情况下，表达式 $R(\Delta, \Delta_1)$ 将为负数（请确保这一点）。现在让我们证明如果点 $A_1, B_1, C_1$ - 在一条直线上，然后 $|R(\Delta, \Delta_1)| = 1$ （自从 $R(\Delta, \Delta_1) < 0$，由此可知 $R(\Delta, \Delta_1) = -1$).

让我们通过点$B$画一条与$AC$平行的线，并用$D$（图5）表示它与线$B_1A_1C_1$的交点。

利用相似度，很容易得到

$$\left\{ \frac{\overrightarrow{CA_1}}{\overrightarrow{A_1B}} \right\} = \frac{|B_1C|}{|BD|}, \quad \left\{ \frac{\overrightarrow{BC_1}}{\overrightarrow{C_1A}} \right\} = \frac{|BD|}{|AB_1|}.$$

通过添加下一个等式 $$\frac{\overrightarrow{AB_1}}{\overrightarrow{B_1C}} = \frac{|AB_1|}{|B_1C|}$$ 并改变所有三个等式，我们得到$|R(\Delta, \Delta_1)| = 1$。证明了墨涅拉俄斯定理条件的必要性。

Menelaus定理的条件(6)和(6')的充分性的证明与Ceva定理的条件(5)和(5')的充分性的证明类似。

有点如下

在 Ceva 和 Menelaus 定理的表述中引入两个等价条件 (5) 和 (5')、(6) 和 (6') 不仅是为了便于证明 -

这些定理的证明。 In some problems it turns out to be convenient to use one of the conditions, in others - another.通过尝试自己证明以下陈述来确保这一点。

命题1.如果穿过三角形顶点的三条直线相交于一点，则相对于三角形相应的二等分线与它们对称的直线也相交于一点。如果三条直线在位于同一直线上的三个点处与三角形的对边相交，则相对于相应的二等直角对称于它们的直线也在位于同一直线上的三个点处与三角形的对边相交。

如果我们记住等式（4），我们就可以很容易地证明它。

命题2. 如果穿过三角形ABC 的顶点A、B、C 且平行于三角形$A_1B_1C_1$ 的边$B_1C_1, A_1C_1$ 和$A_1B_1$ 的三条直线相交于一点，则穿过三角形$A_1B_1C_1$ 的顶点A、$B_1$ 和$C_1$ 平行于三角形ABC 的边BC、AC 和AB 的直线也相交于一点。如果这些线与三角形 ABC 的对应边相交于同一条线上的三个点，那么穿过与 BC、AC 和 AB 平行的三角形 $A_1B_1C_1$ 顶点的线也是如此（图 6, 7）。

你也证明一下

命题3.如果通过三角形ABC的顶点A、B、C垂直于三角形$A_1B_1C_1$的边$B_1C_1, A_1C_1$和$A_1B_1$的直线相交于一点，则从三角形$A_1B_1C_1$的顶点A、$B_1$和$C_1$引出的直线BC、AC和AB也垂直

⟦folio 27⟧

相交于一点。如果直线的第一点与三角形 ABC 的对应边相交于同一条直线上的三个点，则穿过三角形 $A_1B_1C_1$ 垂直于三角形 ABC 边的顶点的直线与三角形 $A_1B_1C_1$ 的对应边相交于位于同一条直线上的三个点（图 8, 9）。

让我们再举两个例子，使用三角形 $A_1B_1C_1$ 的边垂直于三角形 ABC 的边，并与三角形 $A_1B_1C_1$ 的对应边相交于位于同一直线上的三个点。

证明。让我们分别用字母 K、L 和 M 表示条件中提到的线的交点。我们假设线 $A_1A_2$ 和 $A_4A_5$ $A_2A_3$ 和 $A_5A_6$ $A_3A_4$ 和 $A_6A_1$ 位于同一条线上。

证明。让我们分别用字母 K、L 和 M 表示条件中提到的线的交点。我们假设线 $A_1A_2$ 和 $A_4A_5$ $A_2A_3$ 和 $A_5A_6$ $A_3A_4$ 和 $A_6A_1$ 位于同一条线上。

让我们创建下表：

| A | K | $A_1$ | $A_2$ | B |
| :--- | :--- | :--- | :--- | :--- |
| B | $A_4$ | M | $A_3$ | C |
| C | $A_5$ | $A_6$ | L | A |

该表中每一行和每一列中的字母对应位于同一直线上的点。

由于点 K、$A_4$、$A_5$ 位于同一条直线上且在三角形 ABC 的边 AB、BC、CA 上，因此必须满足条件（6），即：

$$\begin{align*}
\frac{\overrightarrow{AK}}{\overrightarrow{KB}} &\cdot \frac{\overrightarrow{BA}_4}{\overrightarrow{A}_4C} \cdot \frac{\overrightarrow{CA}_5}{\overrightarrow{A}_5A} = -1.
\end{align*}$$

同样地

$$\begin{align*}
\frac{\overrightarrow{AA}_1}{\overrightarrow{A}_1B} &\cdot \frac{\overrightarrow{BM}}{\overrightarrow{MC}} \cdot \frac{\overrightarrow{CA}_6}{\overrightarrow{A}_6A} = 1,
\end{align*}$$

⟦folio 28⟧

由于点$A_1, A_2, A_5$和$A_6$位于同一个圆上，并且点$A$是直线$A_1A_2$和$A_5A_6$的交点，因此$|AA_1| \cdot |AA_2| = |AA_5| \cdot |AA_6|$。让我们为共线向量$\overrightarrow{AA_i}$和$\overrightarrow{AA_j}$定义值$\{\overrightarrow{AA_i} \cdot \overrightarrow{AA_j}\}$，等于向量$\overrightarrow{AA_i}$和$\overrightarrow{AA_j}$长度的乘积，如果向量$\overrightarrow{AA_i}$和$\overrightarrow{AA_j}$相连，则使用“+”号，如果它们方向相反，则使用“-”号。然后我们可以用新的符号重写最后一个等式，如下所示：
$$\{\overrightarrow{AA_1} \cdot \overrightarrow{AA_2}\} = \{\overrightarrow{AA_5} \cdot \overrightarrow{AA_6}\} =
\{A_5A \cdot A_6A\}.$$ (10)

同样地
$$\{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}\} = \{\overrightarrow{A_1B} \cdot \overrightarrow{A_2B}\},$$ (11)
$$\{\overrightarrow{CA_5} \cdot \overrightarrow{CA_6}\} = \{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}\}.$$ (12)

变量等式 (7) - (9) 考虑等式 (10 - (12)) 以及根据定义，例如 $$\frac{\overrightarrow{BA_4}}{\overrightarrow{A_4C}} \cdot \frac{\overrightarrow{BA_3}}{\overrightarrow{A_3C}} =
\frac{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}}{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}}$$，我们得到$$\frac{\overrightarrow{AK}}{\overrightarrow{KB}} \times
\times \left\{\frac{\overrightarrow{BM}}{\overrightarrow{MC}}\right\} \cdot \frac{\overrightarrow{CL}}{\overrightarrow{LA}} = -1$$，根据定理

墨涅拉俄斯意味着点$K, L$和$M$属于同一条直线。

直线$A_1A_2, A_3A_4$和$A_5A_6$相交于一点（因此不形成三角形$ABC$）的情况，您可以自行分析。

图 10-12 显示了点$A_1, ..., A_6$ 位置的三种不同情况。当然，他们并没有穷尽所有的可能性。

总而言之——还有一个后果。

命题5. 设圆的两条切线$AM$和$AN$，从圆外的点$A$引出两条截面，并令$P$和$Q$为圆与第一截面的交点，点$K$

⟦folio 29⟧

u L——从第二个开始。那么线 PK、QL 和 MN 相交于一点。

证明（图13）。
让我们将 Ceva 定理应用于 KLM 三角形。请注意，如果满足等式，则直线 PK、QL 和 MN 相交于一点

$$\frac{\sin \widehat{LMN}}{\sin \widehat{NMK}} \cdot \frac{\sin \widehat{KLQ}}{\sin \widehat{QLM}} \cdot \frac{\sin \widehat{MKP}}{\sin \widehat{PKL}} = 1. \quad (13)$$

最后一个表达式中出现的所有角度都内接于给定的圆；这些角度的正弦与它们所对的弦的长度成正比（例如，sin $\widehat{LMN} = \frac{|LN|}{2R}$，其中 R 是圆的半径）。因此，等式(13)等价于以下等式：

$$\frac{|LN|}{|NK|} \cdot \frac{|KQ|}{|QM|} \cdot \frac{|MP|}{|PL|} = 1. \quad (13')$$

让我们证明 (13') 确实满足。根据三角形 AMP 和 AMQ 的相似度，我们得到 $\frac{|PM|}{|MQ|} = \frac{|AM|}{|AQ|}$。

根据三角形 APL 和 AQK $$\frac{|KQ|}{|PL|} = \frac{|AQ|}{|AL|},$$ 的相似度，最后根据三角形 ALN 和 ANK $$\frac{|LN|}{|NK|} = \frac{|AL|}{|AM|}.$$ 的相似度，将最后三个等式相乘，得到 (13)。

注意：从陈述 5 可以看出，在一把尺子的帮助下，可以通过圆外的给定点绘制切线。施工方法如图14所示。

锻炼
1. 证明： a) 三角形外角的二等分线与直线相交，

图 10.

图 11.

图 12.

图 13.

图 14.
