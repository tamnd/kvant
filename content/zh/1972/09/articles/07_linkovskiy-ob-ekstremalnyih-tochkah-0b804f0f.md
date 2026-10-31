---
id: 1972-9-linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f
issue: kvant_1972_9
year: 1972
number: "9"
title: 关于极值点
authors:
  - Линковский Ж. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 37
page_labels: "35"
tag: Y98L
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7f6082241cecc83d8979c2c74c94f8d4ba92fb4521cc15615427a509e5efd1d4
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/07_linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f.md
source_content_sha256: 253d1dc7683051616e20e805c5ab97cc75f6e29c5ad734a68ceaea128eca3d7d
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

关于极端瓣
平科夫斯基

极值点是某个函数达到其最大值或最大值的点。容易证明，三角形中线的交点具有如下性质：到三角形顶点的距离的平方和最小。在本文中，我们将提出一个完全基本的证明来概括这一事实。

假设数据平面上有 $n$ 个点。让我们在平面上引入一个具有轴 $Ox$、$Oy$ 的笛卡尔坐标系，并将这些点表示如下：$A_1(x_1, y_1)$、$A_2(x_2, y_2)$、...、$A_n(x_n, y_n)$ (图 1)。让我们取平面上的任意一点$M(x, y)$。使用毕达哥拉斯定理（图 2）很容易找到从点$M$到点$A_i$的距离的平方：$d_i^2 = (x - x_i)^2 + (y - y_i)^2$。从 $M$ 到点 $A_1$、$A_2$、...、$A_n$ 的距离平方和如下所示：

$$D = d_1^2 + d_2^2 + \dots + d_n^2 = (x - x_1)^2 + (y - y_1)^2 + (x - x_2)^2 + (y - y_2)^2 + \dots + (x - x_n)^2 + (y - y_n)^2.$$

让我们打开括号并将 $D$ 表示为 $x$ 和 $y$ 的多项式之和：

$$D = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2) + ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2).$$

结果是两个多项式的总和，其中一个仅取决于 $x$：

$$P(x) = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2),$$

第二个仅取决于 $y$：

$$Q(y) = ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2)$$

和$D = P(x) + Q(y)$。我们注意到$x$和$y$是独立的，因此对于$x$来说$D$达到最大值，$P(x)$是最小的，对于$y$来说$Q(y)$是最小的。但$P(x)$和$Q(y)$是二阶多项式（系数有点长）。函数$P(x)$的图形将是一条抛物线（图3），其分支向上（$n > 0$），在$x$处达到最小值$u = P(x)$，等于抛物线顶点的横坐标。从这里很容易找到 $x$ 的值，其中 $P(x)$ 最小：$x = \frac{x_1 + x_2 + \dots + x_n}{n}$。

坐标 $y$（从 $Q(y)$）可以类似地找到：$y = \frac{y_1 + y_2 + \dots + y_n}{n}$。

我们向读者提出解决以下问题。

1. 证明三角形中线与顶点$A_1(x_1, y_1), A_2(x_2, y_2), A_3(x_3, y_3)$的交点坐标如下：

$$x = \frac{x_1 + x_2 + x_3}{3}, \quad y = \frac{y_1 + y_2 + y_3}{3}.$$

2. 托里切利点是三角形中到三角形顶点的距离之和最小的点。证明从托里拆利点看，三角形的边在角度 $120^\circ$ 处可见。
