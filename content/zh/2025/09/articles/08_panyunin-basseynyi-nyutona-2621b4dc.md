---
id: 2025-9-panyunin-basseynyi-nyutona-2621b4dc
issue: kvant_2025_9
year: 2025
number: "9"
title: 牛顿池
authors:
  - Панюнин Н. М.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 35
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f2f36fc73af849421cebe95b1b11723d762fdc7590f04ca9c52bb282cfdcff91
prompt_sha256: draft-1
translated_from: content/ru/2025/09/articles/08_panyunin-basseynyi-nyutona-2621b4dc.md
source_content_sha256: b07551880ab4d42d82d853038da6bbbbffa0a105fa583c14547c8e8179dc6543
translation_model: draft
translation_run: zh-draft-2026-11-05
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

$z - \{n + 1\} = Z$
$f(z) = Z^5 - Z^4 - Z - 1$
万花筒“量子”

牛顿池

让我们考虑一下如何“工作-
et”牛顿法在计算机上的应用
lek飞机以及如何
牛顿的事实并不存在。
我们将依靠termi-
Sta-中提出的nology
在此层中“牛顿法”
杂志发行，所以
首先我们建议您熟悉一下
和她一起出去玩。

例如，我们以
方程
$z^5 - \frac{3}{4} z^4 - \left(\frac{1}{2} - \frac{3}{4} i\right) z^3$
$- (1 + i) z - 1 - i = 0$.

该方程的选择基于
的清晰度。它有
5个不同的根：
$w_1 \approx -0,8 + 0,3 i,$
$w_2 \approx -0,7 - 0,4 i,$
$w_3 \approx i,$
$w_4 \approx 0,7 - i,$
$w_5 \approx 1,5$.

图 2

让我们为每个根分配不同的颜色
让我们在复平面 (图 1) 上标记根。

考虑牛顿法的迭代过程：$z_{n+1} = N(z_n)$，其中$N(z)$是牛顿图。让我们在复平面上选择几个初始点，用三角形表示它们，并跟踪这些点的轨迹进行 19 次迭代（参见 图 1）。正如您所看到的，从彼此接近的点开始，您可以到达不同的根。在这种情况下，点的轨迹可能非常复杂。

让我们在复平面上取一个体积
区域$\{z : |Rez| \leq 2,5, |Imz| \leq 2,5\}$，对于该区域的每个点$z_0$，我们将执行牛顿法的 19 个步骤。我们得到一些

⟦folio none⟧

---
running_head:
folio:
---

我指$z_{19}$。让我们用与 $z_{19}$ 最接近的根命名的颜色来绘制起点 $z_0$。结果，接收到下一个分形图片（图2）。

我们再次确信，与牛顿盆地作为由靠近一个或另一个根的点组成的区域的自然假设相反，实际上情况并非如此。值得注意的是，将平面划分为点接近数据的区域称为 Voronoi 图（例如，参见 N. Dolbilin 的文章《Multifaceted Delaunay》，«Kvant» No. 1 和 2，为 2010）。请注意，如果我们不对牛顿法进行 19 次迭代，而是进行 0 次迭代，并根据类似的规则绘制平面，那么我们将得到 Voronoi 图——接近分形结构的零步。

图 3 显示0、1、2、5之后得到的结构

相应迭代。可以看出，图片很快就建立起来了，并且在后续迭代之后，分形结构就被猜测出来了。仅在“无限”步数的情况下才会出现碎片，即在极限情况下，但是在所讨论的尺寸的图中，在 19 步后和 100 步后形成的图片是无法用肉眼区分的。

在计算机上做这些不太复杂的实验。观察引力盆地结构如何根据多项式根的变化而变化。它由牛顿图的临界点决定，即牛顿图的导数为零的点：$N'(z) = 0$。标记关键点并追踪特定区域中关键点的数量与该区域的形状之间的联系。弄清楚如何确定牛顿法循环的起始点。

N. Paponin 准备的材料
