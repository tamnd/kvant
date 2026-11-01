---
id: 1990-3-erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138
issue: kvant_1990_3
year: 1990
number: "3"
title: Ceva 和 Menelaus 定理
authors:
  - Эрдниев Б. П.
  - Манцаев Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 58
page_last: 61
page_labels: 56-59
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 397acd6c29eaba1d61007be40b701b076f84e32b30c4241a222e319f001468b9
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/13_erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138.md
source_content_sha256: b8b94f135b8b7badcc1379eb1d4cb895454e08edc28e4e01fdbf4a4a36d29f8b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

---
running_head:
folio:
---

塞瓦定理
和墨涅拉俄斯

V·埃尔德涅夫，
曼萨耶夫

从你的学校课程中，你知道了关于三角形中显着点的定理：三个bissertrices（中线，高度）相交于一点。这些性质是本文所讨论的定理的结果。因此，我们将讨论 Ceva 和 Menelaus 定理，以及它们对三维空间的一些推广。

墨涅拉俄斯定理

该定理由古希腊数学家墨涅拉俄斯证明

公元一世纪的亚历山大。

定理1. 设点$A_1$和$C_1$位于三角形ABC（图1）的边BC和AB上，点$B_1$位于该三角形的边AC的延长线上。为了使点 $A_1$、$B_1$、$C_1$ 位于同一条直线上，满足以下条件是充分必要的：

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$

证明。首先我们证明必要性。让点$A_1$，$B_1$，$C_1$位于线$l$和$AA_0 = h_1$，$BB_0 = h_2$，$CC_0 = h_3$上 - 分别从点$A$，$B$，$C$到线$l$的垂线（参见图1)。根据三角形$AA_0C_1$和$BB_0C_1$的相似度，我们得到

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2}.$$

类似地，考虑其他成对的相似三角形，我们得到

⟦folio 57⟧

---
running_head:
folio:
---

$$\frac{BA_1}{A_1C} = \frac{h_2}{h_3}, \frac{CB_1}{B_1A} = \frac{h_3}{h_1}.$$

获得可变比例，我们达到所需的平等。

充分性。设直线 $BC, AC, AB$ 上的点 $A_1, B_1, C_1$ (图 2) 为
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$
让我们证明点 $A_1, B_1, C_1$ 位于同一条直线上。
让我们画一条线 $A_1B_1$ 并证明点 $C_1$ 属于它。
我们假设情况并非如此。首先，请注意线 $A_1B_1$ 与线 $AB$ 不平行（为什么？）。令 $T$ 为线 $A_1B_1$ 和 $AB$ 的交点（参见 图 2）。然后
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BT}{TA} = 1.$$ (1)

根据条件和等式 (1) 可以得出
$$\frac{BT}{TA} = \frac{BC_1}{C_1A}.$$

由于点 $T$ 和 $C_1$ 位于线段 $AB$ 之外，因此它们的重合很容易从以下引理得出。

引理。令 $A$ 和 $B$ 为两个不同的点。那么对于直线$AB$上的任意$k > 0, k \neq 1$，有两个且只有两个点$U$和$V$以及$\frac{AU}{UB} = \frac{AV}{VB} = k$，其中一个点属于线段$AB$，另一个点位于线段$AB$之外。

证明。我们引入直线$AB$上的坐标，以点$A$为坐标原点（图3）。让 $k > 1$ 来确定。位于线段$AB$内的所需点$U$的坐标满足方程$\frac{u}{b - u} = k$，因此$u = \frac{k}{k + 1} b$。

线段$AB$之外的点$V$是从方程$\frac{v}{v - b} = k$中唯一找到的，因此$v = \frac{kb}{k - 1}$。

情况 $0 < k < 1$ 与距离的不同之处仅在于，应该在点 $A$ 的左侧寻找点 $V$。

墨涅拉俄斯定理经常以不同的方式表述，使用有向关系的概念

⟦folio 58⟧

---
running_head:
folio:
---

我们假设如果$\vec{AU} = k\vec{UB}$则$\frac{AU}{UB} = k$。很明显，如果向量 $\vec{AU}$ 和 $\vec{UB}$ 同向，则$k > 0$。如果这些向量方向相反，则$k < 0$，当然，数字$|k|$等于线段$AU$和$UB$的长度之比。

有了对线段之间关系的理解，墨涅劳斯定理表述如下。设三个点 $A_1, B_1, C_1$ 分别位于直线 BC、AC 和 AB 上。为了使这些点属于同一条直线，满足以下条件是必要且充分的：

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = -1.$$

我们鼓励读者证明这个定理作为练习。

墨涅拉俄斯定理允许进行有趣的立体概括。

定理2. 若平面$\mu$与四面体ABCD的边AB、BC、CD、DA相交于点$A_1, B_1, C_1, D_1$，则

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (2)

反之，如果分别位于四面体的边AB、BC、CD、DA上的四个点$A_1, B_1, C_1, D_1$满足等式（2），则这四个点位于同一平面内。

证明。设 $h_1, h_2, h_3, h_4$ 分别为点 A、B、C、D 到平面 $\mu$ (图 4) 的距离。然后

$$\frac{AA_1}{A_1B} = \frac{h_1}{h_2}, \frac{BB_1}{B_1C} = \frac{h_2}{h_3}, \frac{CC_1}{C_1D} = \frac{h_3}{h_4},$$

$$\frac{DD_1}{D_1A} = \frac{h_4}{h_1}.$$

剩下的就是将所得的比率相乘。

为了证明逆定理，我们画平面$A_1B_1C_1$。令该平面与边 DA 相交于点 T (图 5)。据证明

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1,$$

并根据条件

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$

波佐托穆

$$\frac{DT}{TA} = \frac{DD_1}{D_1A},$$

并且，根据引理，点 T 和 D$_1$ 重合。该说法已被证明。

⟦folio 59⟧

---
running_head:
folio:
---

1. 证明如果空间四边形的所有边都接触某个球体，则四个接触点位于同一平面上。
2. 证明连接四面体相对边中点的线段相交于一点。

**塞瓦定理**

这个非凡的定理在 17 世纪由成分和数学家 Cheva 证明。

定理3. 设点$A_1, B_1, C_1$ 分别位于三角形ABC (图 6) 的边BC、AC 和BA 上。为了使线段$AA_1, BB_1$和$CC_1$相交于一点，满足以下条件是必要且充分的：

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$ (3)

（有时也称为线段 $AA_1, BB_1$ 和 $CC_1$。）
证明。必要性。让线段 $AA_1, BB_1$ 和 $CC_1$ 相交于三角形 ABC (图 7) 内的点 M。让我们用$S_1, S_2, S_3$表示三角形AMC、CMB和AMB的面积，用$h_1, h_2$分别表示从点A和B到直线MC的距离。

然后

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2} = \frac{S_1}{S_2},$$

类比的

$$\frac{BA_1}{A_1C} = \frac{S_3}{S_1}, \frac{CB_1}{B_1A} = \frac{S_2}{S_3}.$$

测试了所获得的比例后，我们确信该定理的有效性。

充分性。设点$A_1, B_1, C_1$位于三角形的BC、CA、AB上，且满足(3)，M为线段$AA_1$与$BB_1$的交点，线段CM与AB相交于点Q。则根据已证明，

$$\frac{AQ}{QB} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1,$$

所以

$$\frac{AQ}{QB} = \frac{AC_1}{C_1B}.$$

引理一词意味着点的重合：$Q=C_1$。充分性已被证明。

锻炼

3. 证明三角形中的以下线段相交于一点： a) 中线； b) 平分线； b) 高度； d) 从对边与内圆的接触点（格尔贡点）连接三角形顶点的线段； d) 穿过顶点并将周长一分为二的线段； e) 从相对边与内切圆的接触点连接三角形顶点的线段。

现在让我们转向 Ceva 定理的空间推广。

定理4.设M为三角形ABCD内的一点，$A_1, B_1, C_1$和$D_1$分别为平面CMD、AMD、AMB和CMB与边(图8)AB、BC、CD和DA的交点。然后

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (4)

反之，如果位于相应边上的点$A_1, B_1, C_1, D_1$满足对应关系(4)，则平面ABC、BCD、CDA和DAB通过一个点。

通过注意到点$A_1, B_1, C_1$和$D_1$（参见图8）位于同一平面（这是穿过线$A_1C_1$和$B_1D_1$并在点M相交的平面），并应用墨涅劳斯定理，很容易获得必要性的证明。

逆定理的证明方式与空间中的墨涅拉俄斯逆定理相同：需要通过点$A_1, B_1, C_1$画一个平面，并借助引理证明该平面与边DA在点$D_1$相交。

锻炼

4. 设三角形ABC有三条链$AA_1, BB_1$和$CC_1$相交于O点。那么

$$\frac{OA_1}{A_1A} + \frac{OB_1}{B_1B} + \frac{OC_1}{C_1C} = 1.$$

5. 证明三角形的中线在一点（三角形的中线是连接其顶点与对边中心的线段）。

6. 在三角形ABCD中，对边之和相等。证明存在一个与该三角形所有边相切的球体。
