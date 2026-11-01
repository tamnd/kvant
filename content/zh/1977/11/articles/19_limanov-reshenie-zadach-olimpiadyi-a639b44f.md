---
id: 1977-11-limanov-reshenie-zadach-olimpiadyi-a639b44f
issue: kvant_1977_11
year: 1977
number: "11"
title: 解决奥林匹克问题
authors:
  - Лиманов Л. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 65
page_last: 66
page_labels: 63-64
tag: YRV0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 40bee2fffbcf06ddebd43abbb78a27e3ad48444f8d484a24677ebba3bf2f7b91
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/19_limanov-reshenie-zadach-olimpiadyi-a639b44f.md
source_content_sha256: 01091850d89ed740f57603287da92b81b3436a468a998c964492597b38eb73f1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 63⟧

定理。 «Kvant»可以为您提供更多这方面的帮助。

奥运会闭幕式于4月19日举行。评审团副代表M.I.巴什马科夫宣读了第十一届全联盟数学奥林匹克竞赛评委会的答案。因此，根据两天的评比结果，决定授予一等奖13名、二等奖24名、三等奖24名，授予一等奖32名，二等奖36名。我们在第 11 页上公布了第十一届全联盟奥林匹克运动会获奖者姓名。 72.

此外，爱沙尼亚的各个组织和企业还设立了特别奖项（最佳结果奖、最原创解决方案奖、最佳资源奖、苏联最偏僻角落的代表奖等），颁发给许多学童。 《Jorral》特别奖«Kvant» - 1976 年《Jorral》活页夹，作者为 I.K. 院士主编。 Kikon - 由来自塔林的八年级学生Mark Levin 接见（他在比赛之外参加了比赛，因此没有获得任何正式名额）。 1978 年还通过订阅«Kvant»杂志发送了八本经典著作：Lyakhovets Andrey（克拉斯诺达尔）、Khlebutin Sergey（彼尔姆）、Bernotas Andrius（维尔纽斯）、Vlasov Vyacheslav（基辅）、Irmatov Andar（Namangan UzSSR）。

根据奥林匹克竞赛的成绩，组建了代表队参加第19届国际中小学生数学奥林匹克竞赛。该团队包括：A. Ambroladze（第比利斯）、A. Auzinsh（里加）、Y. Vinnishin（基辅）、V. Galperin（莫斯科）、A. Kodryan（雷布尼察）、G. Rybnikov（莫斯科）、D. Flaass（新西伯利亚）和 A. Churbanov（莫斯科）。第十九届国际奥林匹克运动会在贝尔格莱德（南斯拉夫）举行。我们将在该杂志的下一期中讨论这次奥林匹克竞赛。

L·利马诺夫

解决方案
任务
奥林匹克运动会

本文研究了第十一届全联盟数学奥林匹克决赛类型的三个问题，这些问题未包含在 Zhvant 问题书中。 Zhvant问题书中发布的问题的解决方案将按照明年的zhorral编号出现。 （有关问题情况，请参阅第 58-61 页。）

八年级。问题4。

Instead of removing chips, we will bet them, starting with one black chip. Let's add white chips to it so that each of them has a black neighbor (one or two).然后我们将放置几个黑色芯片，使每个黑色芯片都有一个白色邻居，并且“旧”黑色芯片没有白色邻居。 On the next move, white chips are placed again, subject to these two conditions, etc.

让我们表示为 $b_i$ 之后放置的黑筹码数量 $i$  $w_i$  $i+1$黑筹码放置在第 - 步棋（$i$  $b_{i+1} = b_i + 2w_i$, $w_{i+1} = w_i$。 If - white chips ($i$  $b_{i+1} = b_i$, $w_{i+1} = w_i + 2b_i$;每一步，我们都会用两个不同颜色的筹码包围所有一种颜色的筹码。显然不可能分配更大的数字。

条件是以向量$\langle b_i; w_i \rangle$的形式记下第$i$次移动后棋子在圆上的位置，并计算几个向量：

$$\langle 1;0 \rangle \rightarrow \langle 1;2 \rangle \rightarrow \langle 5;2 \rangle \rightarrow \langle 5;12 \rangle \rightarrow \langle 29;12 \rangle \rightarrow \langle 29;70 \rangle \rightarrow \langle 169;70 \rangle \rightarrow \langle 169;408 \rangle \rightarrow \langle 985;408 \rangle.$$

Indeed, after the fourth turn, $29+12=41$ chips will be exposed. When moving from $\langle 5;12 \rangle$ to $\langle 29;12 \rangle$, 24 chips are added. Of these, no more than $2 \times 5=10$ are the answer for fulfilling the second condition - they will separate the old black chips from the white ones.我们称这些功能为强制性的。让我们标记它们

⟦folio 64⟧

我们用归纳法证明 $i$

$$\frac{1}{2^i} a_n - 2\varepsilon < a_{n+i} < \frac{1}{2^i} a_n + 2\varepsilon,$$

where $n$ is any number greater than $m$.真的吗，

$$\frac{1}{2^{i+1}} a_n - 2\varepsilon = \frac{1}{2} \left( \frac{1}{2^i} a_n - 2\varepsilon \right) -$$

$$-\varepsilon < \frac{1}{2} a_{n+i} - \varepsilon < a_{n+i+1} <$$

$$< \frac{1}{2} a_{n+i} + \varepsilon < \frac{1}{2} \left( \frac{1}{2^i} a_n + 2\varepsilon \right) + \varepsilon =$$

$$= \frac{1}{2^{i+1}} a_n + 2\varepsilon.$$

但对于任何$\varepsilon > 0$，都可以指定一个$i$，使得$\left| \frac{a_n}{2^i} \right| < \varepsilon$。由此可见，对于任意 $\varepsilon > 0$，可以指定一个 $k$，使得对于所有 $l > k$，不等式 $-3\varepsilon < a_l < 3\varepsilon$ 成立。根据极限的定义，这意味着 $\lim_{n \to \infty} a_n = 0$。

九年级。任务 5。

We will assume that there are no free nodes on the boundary of the square.让我们证明任何满足问题条件的折线系统，并且该条件经过四倍的节点数。

正方形边界上的Zanuterum节点如图2所示。很容易说，连接编号为$i$和$j$的点的折线经过$1+i-j+2l$节点，其中$l$的值取决于折线。现在让我们计算折线所经过的节点的双倍数量。由于正方形的每个点（除了顶点）都有一条折线，因此该数字等于 $4.99 + \sum i - \sum j + 2\sum l (i,j)$，其中 $l(i,j)$ 是从点 $i$ 开始到点 $j$ 结束的折线的 $l$ 的值。很容易看出 $\sum l(i,j)$ 是偶数，因为每个项在其中出现两次：$l(i,j) = l(j,i)$。因此，我们的折线系统穿过节点的数量，并且不在我们的纸张边界上的节点总数是 $99^2$ - 一个奇数。因此，至少有一个节点实际上未被遍历。
