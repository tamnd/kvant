---
id: 1977-8-rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab
issue: kvant_1977_8
year: 1977
number: "8"
title: 仿射问题和定理
authors:
  - Рабинович В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38, 40, 41
tag: F9MH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8b07b89a047fa25981ba822d1baf4d43d188a0ab1a8c5cb6e1de37ad067bbdf1
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/10_rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab.md
source_content_sha256: 58b110e96f77b6692cd0b30b19f2867afcd1f82dba6e87d6e87d2bc9bbce16cc
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

V·拉宾诺维奇

仿射问题和定理

正方形的平行四边形问题可以解决吗？证明等边三角形的三角形定理就足够了吗？事实证明，有时可以，有时就足够了。本文讨论了此类问题和定理。

1. 并行工程

假设有两个平面 $\alpha$ 和 $\beta$ 以及一条与这些平面中的每一个相交的线 $a$ (图 1)。让我们将平面$\alpha$到平面$\beta$的映射$\Pi_a$定义如下：对于任意点$A \in \alpha$，我们分配一个点$A' \in \beta$，在该点，穿过点$A$并平行于线$a$的线与平面$\beta$相交。使用通用函数符号，我们将写成$\Pi_a (A) = A'$。映射$\Pi_a$自然称为平行投影。显然，如果$A \neq B$（$A \in \alpha$和$B \in \alpha$），则$\Pi_a (A) \neq \Pi_a (B)$。因此，平行投影是一种逆映射（“代数 8”，第 20 段）*。因此我们可以讨论逆映射。映射$\Pi_a^{-1}$，与平行投影$\Pi_a$相反，显然是平面$\beta$到平面$\alpha$的平行投影：$\Pi_a^{-1} (A') = A$。

平行投影$\Pi_a$将平面$\alpha$上的任意图形$\Gamma$变换为平面$\beta$（图1）上的某个图形$\Pi_a (\Gamma)$——函数$\Gamma$在映射$\Pi_a$下的图像。

1. 证明直线在平行投影下的像是一条直线，并且，如果点$A$位于$B$和$C$之间，则$\Pi_a (A)$位于$\Pi_a (B)$和$\Pi_a (C)$之间。

从这里显然可以看出，线段的图像是线段，多边形的图像是多边形（边数相同）。

U razzhenne 2. 证明平行投影保持平行性：如果$l \parallel m$，则$\Pi_a (l) \parallel \Pi_a (m)$。

这意味着并行性的形象就是并行性。 3. 证明平行线段的长度比是平行投影的不变量：如果线段$AB$、$CD$位于平面$\alpha$中的一条直线上（或平行线上），则$\frac{|AB|}{|CD|} = \frac{|A'B'|}{|C'D'|}$（此处为$A' = \Pi_a (A)$等）。

因此，如果$AK$是三角形$ABC$（$\triangle ABC \subset \alpha$）的中线，那么$A'K'$就是三角形$A'B'C'$的中线。

U razzhenne 4. 证明图形面积之比是平行投影的不变量：如果$\Gamma \subset \alpha$ 和$\Delta \subset \alpha$，则$\frac{S(\Gamma)}{S(\Delta)} = \frac{S(\Pi_a (\Gamma))}{S(\Pi_a (\Delta))}$。指示。经证明是允许的

*) 本文讨论的并行设计是平面（到平面）的映射。 《几何 9》第 12 节中的平行投影是空间（到平面上）的映射。事实并非相反。

⟦folio 40⟧

从练习 2, 10 可知该定理是仿射定理。根据练习7，给定梯形$ABCD$的仿射图像中有一个等腰梯形。执行相应的平行投影 P 后，我们从梯形$ABCD$移动到等腰梯形$A'B'C'D'$。梯形$ABCD$的对角线$AC$和$BD$将变换为梯形$A'B'C'D'$的对角线$A'C'$和$B'D'$，点$O, K, P, Q$将变换为对应点$O' = [A'C'] \cap [B'D']$、$K' = (A'B') \cap (C'D')$、$P' = (K'O') \cap [B'C']$和 $Q' = (K'O') \cap [A'D']$ (图 3)。

在等边梯形$A'B'C'D'$中，众所周知，$|A'C'| = |B'D'|$和$B' \hat{A}'D' = C' \hat{D}'A'$（《几何7》第50段的问题2）。从这里很容易推断出$|A'K'| = |D'K'|$和$A' \hat{K}'Q' = D' \hat{K}'Q'$。因此，在等边三角形$A'K'D'$中，线段$K'Q'$是二等分线，因此中线也是：$|A'Q'| = |Q'D'|$。同理，证明$|B'P'| = |P'C'|$。

现在让我们执行反向平行投影$\Pi^{-1}$。对于$\Pi^{-1}$，“一切”都会“返回”：$A'$ - 到$A, B'$ - 到$B$，等等。从练习10可以得出$|BP| = |PC|$和$|AQ| = |QD|$。

事实上，如果我们事先检查了我们要证明的定理是仿射定理，并且我们以这种方式证明它（通过传递到仿射图像），那么就不需要进行逆向工程：所证明的定理结论的正确性仅取决于其仿射性。

这样，原则上就可以证明任何亲和定理。

实践 14. 以这种方式证明练习 12、13 中的定理。

4. 从上面看

事实上，情感图像的更自然的定义如下：如果平面图形$\Delta$可以通过有限数量的平行投影的组合从$\Gamma$获得，则称为平面图形$\Gamma$的附属图像。类似地，如果平面图形的性质在有限数量的平行投影的组合下得以保留，那么它的性质自然被称为仿射射影。

因此，情感图像概念的定义（与第2段中定义的概念相反）是传递性的：如果$\Delta$是（平面）图形$\Gamma$的附属图像，并且$\Sigma$是图形$\Delta$的附属图像，那么$\Sigma$是图形$\Gamma$的附属图像。由于这个概念也是对称的（如果$\Delta$是图形$\Gamma$的附属图像，那么$\Gamma$是图形$\Delta$的附属图像）和反射（任何平面图形$\Gamma$是其自身的附属图像），我们可以（=合理地）给出以下定义：两个平面图形$\Gamma$、$\Delta$被称为afficino 等价物，如果其中一个是另一个的 afficino 图像。

我们现在可以制定更多研究定理，而不是练习 5-7 中的定理：所有 afficino 三角形都是等价的，所有 afficino 平行四边形都是等价的，所有 afficino 梯形都是等价的。

在学校几何中，图形实际上被认为是全等的，也就是说，全等图形可以说是被识别并被认为是等价的。因此，这种几何学可以被认为是一门性质的科学

⟦folio 41⟧

不随变化而变化的数字。

平面上的几何，基于有限数量的平行投影*)的组合（这种组合称为平面的仿射变换），即绘制仿射等价图形的几何称为仿射几何。仿射几何是研究在仿射变换下不改变的图形属性的科学。本文向您介绍了该几何的一些概念。

锻炼
1. 通过位于三角形$ABC$内的点$P$，绘制平行直线$l, m, n$，对应于[$AB$，$BC$，$CA$]。令$l \cap [BC] = A_1$，$m \cap [AC] = B_1$，$n \cap [AB] = C_1$。证明$\frac{|PA_1|}{|AB|} + \frac{|PB_1|}{|BC|} + \frac{|PC_1|}{|CA|} = 1$。

2. 证明梅纳莱定理：如果直线$l$与三角形$ABC$的边$AB$在点$R$相交，边$BC$在点$P$相交，以及边$AC$的延长在点$Q$相交，则$\frac{|PB| \cdot |QC| \cdot |RA|}{|PC| \cdot |QA| \cdot |RB|} = 1$。

3. 在三角形$ABC$中，通过点$L \in [AC]$和$K \in [AC]$以及$|AL| = |CK|$，绘制相应的直线$l \parallel AB$和$k \parallel BC$。让$k \cap l = O$。证明直线$BO$穿过线段$AC$的中间。

4. 在与克$ABCD$平行的边$AB, BC, CD, DA$上，取相应的点$P, Q, R$和$S$。若原平行格$ABCD$的平面为$t$、$|AS| = |CQ|$、$|BP| = |DR|$、$\frac{|AS|}{|AD|} = \frac{|DR|}{|CD|}$，求直线$AR, BS, CP$与$DQ$相交而成的四边形$A_1B_1C_1D_1$的平面。

5. 与克$ABCD$平行，点$A_1, B_1, C_1, D_1$相应地位于$[AB], [BC], [CD]$和$[DA]$上。在四边形$A_1B_1C_1D_1$的边$A_1B_1, B_1C_1, C_1D_1$和$D_1A_1$上取相应的点

*) 在本文中，平行投影通常被视为一个平面到另一个平面的映射。但通过这种映射的组合，我们可以实现图像在原始平面中的位置。

$A_2, B_2, C_2$ 和 $D_2$。已知$\frac{|AA_1|}{|BA_1|} = \frac{|BB_1|}{|CB_1|} = \frac{|CC_1|}{|DC_1|} = \frac{|DD_1|}{|AD_1|} = \frac{|A_1D_2|}{|D_1D_2|} = \frac{|D_1C_2|}{|C_1C_2|} = \frac{|C_1B_2|}{|B_1B_2|} = \frac{|B_1A_2|}{|A_1A_2|}$。

证明四边形 $A_2B_2C_2D_2$ 是平行四边形，其边与边 $BC$ 平行 – 分成 $n$ 等份。通过图4所示的分割点画直线。平行四边形$ABCD$的面积是四边形$NFGH$的面积的几部分？

8. 在空中飞人中 $ABCD$ ([AD] || [BC]) 通过点 $B$ 画一条直线，平行 $CD$ 并与相交 $AC$ 在这一点上 $P$，并通过 $C$ – 直线、平行 $AB$ 并与相交 $BD$ 在这一点上 $P$。证明 $[PQ] || [AD]$.

9. 在梯形 $ABCD$ ([AD] || [BC]) 中，通过点 $C$，有一条与 $AB$ 平行并与 $BD$ 相交于点 $P$ 的直线。已知$|BO| = |PD|$，其中$O = [AC] \cap [BD]$。证明$|AD|^2 = |BC|^2 + |AD| \cdot |BC|$。
