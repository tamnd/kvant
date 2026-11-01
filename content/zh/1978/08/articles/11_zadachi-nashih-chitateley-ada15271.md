---
id: 1978-8-zadachi-nashih-chitateley-ada15271
issue: kvant_1978_8
year: 1978
number: "8"
title: 读者的任务
rubric: smes
page_first: 49
page_last: 49
page_labels: "47"
tag: J2DT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 28a7861ccf8b2a88264250a72e10d77ba2a8ffc5bacaab2e046507295104302f
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/11_zadachi-nashih-chitateley-ada15271.md
source_content_sha256: 343b2e819dec2258aa32dd91f5e925b569c1d17fe62b514b6b4cbf112909d01e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

图 8.

$\Pi_1, \Pi_2, \Pi_3, \dots$ 在每个矩形 $\Pi_i$ 中，正好有 $n_i$ 条线，每条线至少有 $n_i$ 个阴影单元格，因此在 $Q_0$ 中，无论如何都有 $n_0^2 + n_1^2 + \dots + n_k^2 - 3$ 个单元格被阴影化。让我们介绍一下符号：$m_0 = n_0, m_1 = n_0 + n_1, m_2 = n_0 + n_1 + n_2, \dots$（参见图 8）。考虑一张编号为$[0m_0m_1 \dots m_{k-3}xy]$的票，其中$x$和$y$是不少于$m_{k-3}$的两个“数字”（也就是说，编号为$xy$的盒子“位于”$Q_{k-2}$中）。不难看出，这张票只能放在编号为$xy$的盒子里。由于$x$和$y$是在$Q_{k-2}$中任意选择的，我们得到所有方形$Q_{k-2}$单元格都是阴影的（其中有$n_{k-2}^2$）。所以我们至少有 $n_0^2 + n_1^2 + \dots + n_k^2 - 3 + n_{k-2}^2 + n_{k-2}^2$ 个阴影单元格。现在让我们注意$n_0 + n_1 + \dots + n_{k-3} + n_{k-2} = N$，因此阴影单元不少于$F(k-1, N)$。

剩下的就是证明你可以使用恰好 $F(k-1, N)$ 个盒子。让和$F(k-1, N)$对应于集合$\{a_1, a_2, \dots, a_{k-1}\}$。让我们将$N$数字分成$k-1$组：第一组有$a_1$“数字”，第二组有$a_2$“数字”，依此类推。

让我们考虑所有带有数字的方框，其中的两个“数字”都属于同一组。只有$a_1^2 + a_2^2 + \dots + a_{k-1}^2 = F(k-1, N)$，每张票都可以放入其中一个盒子中，因为票的$k$“数字”中有两个来自同一组的“数字”。

对于 $N = 10$，$F(k-1, 10)$ 的相应值在表图 2 处给出。

读者的任务

1. 证明
a) $S_n = \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2} < \frac{2}{3}$;
b) $P_n = \frac{1}{2} \cdot \frac{3}{4} \cdot \frac{5}{6} \times \dots \frac{2n-1}{2n} > \frac{1}{\sqrt{4n+1}}$.

G·皮斯卡列夫
（雅罗斯拉夫尔地区）

2. 设三角形$ABC$的边$AC$是最长或最短的。证明存在实数$x$使得$|AC|^x = |BC|^x + |AB|^x$。
O·莱梅舍夫
（鄂木斯克）

3. 是否存在一个自然数，其平方等于1000个连续自然数的平方和？

4. 证明方程
a) $(m+1)^3 + (m+2)^3 + \dots + (m+n)^3 = 10^k + 2$;
b) $(m+1)^5 + (m+2)^5 + \dots + (m+n)^5 = 10^k + 2$ 无整数解。

I·切列平斯基
（切尔卡瑟）

5. 给定一个线段$AD$和属于该线段的一个点$H$，以及$|AH| : |HD| = 4:1$。构造三角形$ABC$，使线段$AD$为其高，点$H$为其正交点，三角形$ABC$的外接圆的半径等于$\frac{4}{5}|AD|$。

6. 给定一个三角形$ABC$，$[AD]$是它的中线，$M \in [AD]$，$|AM| : |MD| = 2:3$，$N \in [AB]$，$|AN| : |NB| = 5:3$。求三角形 $AMN$ 和 $ABC$ 的面积比。
A·普利亚耶夫
（顿涅茨克）
