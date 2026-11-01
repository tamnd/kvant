---
id: 1990-2-panov-schitaem-v-dvoichnoy-sisteme-1087a597
issue: kvant_1990_2
year: 1990
number: "2"
title: 我们用二进制数
authors:
  - Панов А.
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 32
page_last: 32
page_labels: "30"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 6e6c603973bea676fcc25ad2fbc241c138d4a847a3d7baca5320634b09c8f1ee
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/08_panov-schitaem-v-dvoichnoy-sisteme-1087a597.md
source_content_sha256: 1c522c1e5d40dd01144d17f11ef69b670040de157a02f360674c9532bb4a74c0
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

我们算双系统
假设我们面前有几个物体，我们需要数它们。 As usual, we do this by sequential recalculation: we take the first item and say “one”, take the next one – “two”, the next one – “tri” and so on until the last one.由于我们是用十进制计数的，所以我们也会得到十进制中对象$N$的数量

$$N = a_k a_{k-1} \dots a_1 a_0.$$
这里每个数字$a_i$是0、1、2、3、4、5、6、7、8或9以及$N = a_k \cdot 10^k + a_{k-1} \cdot 10^{k-1} + \dots + a_1 \cdot 10 + a_0$。

在该系统中，数字$N$表示为

$$N = b_l b_{l-1} \dots b_1 b_0,$$

其中每个数字 $b_i$ 是 0 或 1 并且

$$N = b_l \cdot 2^l + b_{l-1} \cdot 2^{l-1} + \dots + b_1 \cdot 2 + b_0.$$

然而，在双系统中，有一种根本不同的计数方法，我想向您介绍这种方法。让我们转向图：根据参数构建所有项目。在这种情况下，要么什么都不会保留，要么会保留一个未配对的对象。让我们这样加起来：要么剩下 0 件，要么剩下 1 件。在第二阶段，我们将每两对组合成四元组。在这种情况下，仍然会保留 0 对或 1 对。接下来，我们将四人一组，然后八人一组，依此类推。经过最后一次统一，我们得到了所有对象的分组，每组中的元素数量是2的幂。如果分区包含具有 $2^i$ 个元素的组，则我们放置 $b_i = 1$，如果没有这样的组 - $b_i = 0$。进而

$$N = b_l b_{l-1} \dots b_1 b_0$$

— 双系统中对象数量的记录。

这两种方法中哪一种更可取？我建议你自己解决这个问题。

A·帕诺夫
