---
id: 1970-11-kak-nayti-oshibku-65f9e002
issue: kvant_1970_11
year: 1970
number: "11"
title: 如何找到错误
rubric: smes
page_first: 28
page_last: 28
page_labels: "26"
tag: QVQB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: edfdde48d74b57a4f0b7adb7679a4922fe530817d7ebbbec8c6ab6bad054c7f3
prompt_sha256: draft-1
translated_from: content/ru/1970/11/articles/08_kak-nayti-oshibku-65f9e002.md
source_content_sha256: 047f0462fcc9fecaba27dc957dad934bd013ae2c96bb4df8bac4d0aab3cd3180
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

如何查找错误

您已将两个长多项式相乘。如何检查自己的计算是否有错误？

我们提出了两种方法，使我们能够找到一些错误的可能性（但是，当然，不能完全保证已验证计算的正确性）。

方法 1. 将第一个多项式的系数之和乘以第二个多项式的系数之和。应该得到乘积的系数之和。这将是 $x=1$ 处多项式的值。

上述方法可以让您发现算术中的错误（例如，如果使用“等式”$2 \cdot 3=5$），但不能发现代数中的错误。假设，如果在某个阶段您编写了 $2x^2 \cdot 3x^3=6x^4$，那么此方法不会产生错误。

方法2. 与第一种不同的是，偶数次$x$的系数用平面符号表示，奇数次方的系数用负号表示。否则，此方法与第一种方法相同。这里我们得到$x=-1$处多项式的值。

第二种方法比第一种方法更复杂；这也使我们能够识别一些代数错误。当检查“相等”$2x^2 \cdot 3x^3=6x^4$时，结果是$2 \cdot (-3)=6$。这个等式是荒谬的，这意味着计算中有错误。
