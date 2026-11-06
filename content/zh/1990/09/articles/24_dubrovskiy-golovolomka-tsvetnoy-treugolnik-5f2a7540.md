---
id: 1990-9-dubrovskiy-golovolomka-tsvetnoy-treugolnik-5f2a7540
issue: kvant_1990_9
year: 1990
number: "9"
title: 彩色三角拼图
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 71
page_last: 71
page_labels: "69"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 71e4a130a99cc3c7221f0212d61d87acbe59f9e4dd5604cf53cb1de18f204d61
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/24_dubrovskiy-golovolomka-tsvetnoy-treugolnik-5f2a7540.md
source_content_sha256: ddf071034688843cb3752183a95a92c1a0f4b921f87a501df9c469aa2e419064
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 69⟧

拼图“彩色三角形”
（研究问题）

4 号。上一期封面«Kvant»我们提出了如下谜题：在三角形中的正三角形网格的节点上（一边有$n$节点），放置$n$颜色的图块，使得与边平行的网格线上没有明确的图块。

图 1 和图 2 显示了 $n=5$ 这个难题的两种解决方案。有趣的是，在这两种情况下，将 15 个网格节点划分为一组明确的节点是相对于三角形的垂直高度对称的，并且在 图 2 处 - 也相对于其他两个高度，以及相对于围绕三角形中心旋转 $120^\circ$ 对称。

你可以像这样得到图1的颜色。考虑一个（倾斜）坐标系，原点位于三角形的绿色顶点，轴沿边延伸，其中红色顶点的坐标为 (4; 0)，紫色顶点的坐标为 (0; 4)。然后发现绿色有节点 $(x; y)$，$x=y$，红色 - $y=x$ 除以 5 余数为 1 的点，蓝色 - 余数为 2 的点，等等。您可以检查相同的着色方法是否适用于任何奇数 $n$。然而，如果 $n$ 是偶数，则不起作用：相同的颜色落在同一水平线上。

问题 1. 采用某个整数函数 $f(x)$ 并将网格节点划分为多个集合，每个集合中的差值 $f(x)$ 除以 $n$ 时将得到相同的余数。在收到的每组芯片上，我们都会放置不同颜色的芯片。证明如果 $n$ 是偶数，则“条件性”无论出于何种原因都不会满足函数 $f(x)$。

此外，对于$n=4$（以及$n=2$），我们的难题根本没有被解决。事实上，如果三角形底部的节点的颜色如 图 3 所示，那么中心节点只能是红色或蓝色。在第一种情况下，查看箭头，我们将明确确定另外三个节点的颜色，然后被迫打破规则：三角形的两个顶点变成红色。头部中央节点的情况也以类似方式处理。

问题 2. 解决 $n=6$ 和 $n=8$ 的难题。

问题3*。彩色三角形拼图在哪四个 $n \geq 10$ 处有解？

另一个显然非常困难的问题：根据$n$，谜题有多少种解决方案？ V. Shevelev 的文章“拉丁直头网格”（今年«Kvant»第 5 期）中提出了类似的关于在水平和垂直间距条件下在直头网格上放置芯片的问题。然而，即使是主要问题，尽管历史悠久，但也远未得到彻底解决。

V·杜布罗夫斯基
