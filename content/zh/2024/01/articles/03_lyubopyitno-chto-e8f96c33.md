---
id: 2024-1-lyubopyitno-chto-e8f96c33
issue: kvant_2024_1
year: 2024
number: "1"
title: 有趣的是...
rubric: smes
page_first: 12
page_last: 13
page_labels: "10"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7edf72da557262de0e33d9545d138bc5f49462ebcb581bbc2fc9d3fc76b28798
prompt_sha256: draft-1
translated_from: content/ru/2024/01/articles/03_lyubopyitno-chto-e8f96c33.md
source_content_sha256: 0e5e072fd89fa439f0c6e31469aba37cc9c19c23f0b794d8fa6d9b5e7372e54d
translation_model: draft
translation_run: zh-draft-2026-11-03
translation_quality: draft
---

⟦folio 10⟧

奇怪的是...

要找到多项式$P(x)$在某个点$x_0$的切线方程，您可以走直接的路线：在$x_0$处找到任意一个，它将给出斜率。然后写出通过点 $(x_0,P(x_0))$ 的直线方程以及所得的斜率。

但它可以以不同的方式构建。将 $P(x)$ 除以 $(x-x_0)^2$ 余数：

$$P(x) = (x-x_0)^2Q(x)+R(x).$$

那么$y = R(x)$就是正切方程！

让我们来证明这个简单而又意想不到的事实。

请注意，直线 $y = R(x)$ 经过所需点。除了，

$$P'(x) = 2(x-x_0)Q(x)+(x-x_0)^2Q'(x)+R'(x),$$

方法，

$$P'(x_0) = R'(x_0).$$

但$R(x)$是一次多项式，它的任意值就是$x$的系数。这意味着直线$y = R(x)$在点$x_0$处与任意$P(x)$重合，因此它是一条切线。

⟦folio none⟧

---
running_head:
folio:
---

“量子”问题
任务
在数学和物理方面
自杂志创刊以来，我们一直在逐期运行此版块。其中发布的问题是非标准的，但它们的解决方案不需要超出学校课程范围的知识。最困难的任务标有星号。创建任务后，我们通常会指出谁向我们提出了该任务。当然，并非所有这些问题都是第一次发表。
本期数学和物理问题的解答应分别发送至电子邮件地址：math@kvant.ras.ru 和 phys@kvant.ras.ru，或邮寄地址：119296 Russia, Leninsky Prospekt, 64-A, «Kvant»。
将提议发布的每个原始问题的条件以及该问题的解决方案发送到同一地址。
M2780、M2781 题是在第十七届南方数学锦标赛上提出的。
