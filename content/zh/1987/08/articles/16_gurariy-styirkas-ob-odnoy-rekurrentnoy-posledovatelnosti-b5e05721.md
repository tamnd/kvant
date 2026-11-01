---
id: 1987-8-gurariy-styirkas-ob-odnoy-rekurrentnoy-posledovatelnosti-b5e05721
issue: kvant_1987_8
year: 1987
number: "8"
title: 关于一个循环序列
authors:
  - Гурарий В. В.
  - Стыркас К. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 50
page_labels: "48"
tag: 20TL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c86c3f8c01dbef70cce1efef65b800c94c7cd659fa528066df3d3700504145ba
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/16_gurariy-styirkas-ob-odnoy-rekurrentnoy-posledovatelnosti-b5e05721.md
source_content_sha256: fa5f1189999fcef1092bdf833340d4fdd4972aa3afdb126b51dcf2d8dd546818
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

关于一个循环序列

V.V.古拉里，K.A.斯蒂卡斯
（10年级学生）

1984年《科学世界》第3期杂志上发表了布莱恩·海耶斯的文章《梯度数的兴衰》。本文讨论了一个关于数列的交互问题。我们想谈谈它以及与解决它的尝试相关的一些有趣的结果。

这个问题的表述非常简单。让我们取一些自然数。如果是偶数，则除以 2，否则乘以 3 加 1。对结果重复相同的操作。问题如下：根据初始数字，结果序列看起来如何？

一般来说，我们可以预期两种可能性：要么这个序列是发散的，也就是说，结果数字将无限增加，或者在每次操作之后，我们将收到一个已经等于序列中已经遇到的数字。在这种情况下，其中的数字将开始周期性地重复，并且这个序列将变得“循环”。

让我们考虑第一个自然数——一。我们的序列将是这样的：1→4→2→1。然后一切都从头开始重复。数字 2 和 4 被认为是无意义的，因为它们已经被遇到过，并且我们不会收到新的数字序列。

让我们继续看数字 3。正如你所看到的，它后面跟着数字 10, 5,16,8,4,2,1,... 我们再次来到一个闭环 1,4,2,1,...
