---
id: 1971-5-kogan-fizika-pomogaet-geometrii-364309da
issue: kvant_1971_5
year: 1971
number: "5"
title: 物理帮助几何
authors:
  - Коган Б. Ю.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 26
page_labels: 22-24
tag: 7LN1
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 47fd92d97a2729c409d7a326abd7b58eeb6cc28ac8001828dad776c6e207f689
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/05_kogan-fizika-pomogaet-geometrii-364309da.md
source_content_sha256: 2f8ceaffe024d9fd88e3c6a01f60e2bd0026f118d61a16cd7d362a9d706cfb91
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

物理
帮助
几何学

B、于。科根

学习物理时，当然会用到数学。但事实证明，反过来也是如此：物理有益于数学。以下是如何在几何中使用重心概念的一些示例。

1. 三角形中线定理。让我们将质量相等的质点放置在三角形的顶点 (图 1)。 A 点和 B 点系统的重心位于 K 点——线段 AB 的中间。这意味着 A、B、C 点系统的重心位于 SC 的中线上。以此类推，我们会得出这个重心位于中位 AL 和中位 BM 上。但 A、B、C 点系统只有一个重心。因此，三角形的中线相交于一点。

此外，由于 C 点的质量为 m，K 点“代表”A 点和 B 点的系统，质量为 2m，因此 KS 的大小是 SC 的一半。因此，中位数的交点以 2:1 的比例划分它们。

2. 四边形中线定理。让我们将相同质量 (图 2) 的质点放置在四边形 ABCD 的顶点处。由于系统的重心为 A 点

⟦folio 23⟧

或者对于A点和D点，我们可以得出A、B、C、D点系统的重心位于中线KM和LN的交点上。此外，由于A、B点系统与C、D点系统具有相同的质量，因此KS = SM。以此类推，我们发现LS=SN。因此，相交的四边形的中线被分成两半。

请注意，我们的推理并未使用 A、B、C 和 D 点位于同一平面上的事实。这意味着已证明的定理对于空间四边形也成立。 （由此可见，这样的四边形的中线必然相交。）

3. 先前定理的推广。考虑任意四边形 ABCD (图 3)。让我们将质点放置在其顶点处：顶点 A - 质量 m，顶点 B - 质量 αm，顶点 D - 质量 βm，顶点 C - 质量 αβm，其中 α 和 β 是任意正数。那么A、B、C、D点系统的重心将位于直线KM和LN的交点处，其中K为A、B点系统的重心，M为C、D点系统的重心，L为B、C点系统的重心，N为A、D点系统的重心。进一步，由于纵向任意对应于重量，则

$$\frac{AK}{KB} = \frac{\alpha m}{m} = \alpha, \quad \frac{DM}{MC} = \frac{\alpha \beta m}{\beta m} = \alpha,$$

$$\frac{NS}{SL} = \frac{\alpha m + \alpha \beta m}{m + \beta m} = \alpha, \quad \frac{BL}{LC} = \frac{\alpha \beta m}{\alpha m} = \beta,$$

$$\frac{AN}{ND} = \frac{\beta m}{m} = \beta,$$

$$\frac{KS}{SM} = \frac{\alpha \beta m + \beta m}{\alpha m + m} = \beta.$$

因此，如果这个四边形的边被划分为

$$\frac{AK}{KB} = \frac{DM}{MC} = \alpha, \quad \frac{BL}{LC} = \frac{AN}{ND} = \beta,$$

那么线段 NL 和 KM 将分开

⟦folio 24⟧

例如，在 图 4 上，每个“垂直”段被分为三个相同的部分，每个“水平”段被分为四个相同的部分*)。

4. 寻找匹配项。利用重心的概念，可以轻松解决以下类型的问题。在三角形 $ABC$ 的边上有点 $K$ 和 $L$ (图 5)。给定 $\frac{AK}{KB} = \frac{1}{2}$ 和 $\frac{BL}{LC} = \frac{3}{5}$，求 $\frac{AS}{SL}$ 和 $\frac{CS}{SK}$ 的比率。

解决方案。让我们将质点放置在顶点 $A, B, C$ 处，以使对应关系成立
$$\frac{m_B}{m_A} = \frac{AB}{KB} = \frac{1}{2}, \quad \frac{m_C}{m_B} = \frac{BL}{LC} = \frac{3}{5},
$$
例如，让我们把
$$m_A = 10m, \quad m_B = 5m, \quad m_C = 3m.$$
那么点$A$和$B$的系统的重心将位于点$K$，点$B$和$C$的系统的重心将位于点$L$。因此，$A, B$和$C$点系统的重心位于直线$CK$上，同时位于直线$AL$上，即位于交点$S$上。从这里不难发现
$$\frac{AS}{SL} = \frac{m_B + m_C}{m_A} = \frac{5m + 3m}{10m} = \frac{4}{5},
$$
$$\frac{CS}{SK} = \frac{m_A + m_B}{m_C} = \frac{10m + 5m}{3m} = \frac{5}{1}.$$
锻炼
1. 四面体的每个顶点都连接到相对面的中线的交点。证明所得的四个线段相交于一点。
2. 在三角形 $ABC$ 中绘制中线 $AK$。连接顶点 $C$ 与中线中点的线与边 $AB$ 相交于点 $L$。求出比率 $AL:LB$。
3. 在 图 6 所示的三角形 $ABC$ 中，
$$\frac{AK}{AB} = \frac{BL}{BC} = \frac{CM}{CA} = \frac{1}{3}.$$
三角形$ABC$的面积的哪一部分是受保护三角形的面积之和？
*) 该定理对于非平面四边形也成立。
