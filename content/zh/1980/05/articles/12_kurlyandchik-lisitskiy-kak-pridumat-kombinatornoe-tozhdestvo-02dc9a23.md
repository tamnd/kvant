---
id: 1980-5-kurlyandchik-lisitskiy-kak-pridumat-kombinatornoe-tozhdestvo-02dc9a23
issue: kvant_1980_5
year: 1980
number: "5"
title: 如何提出组合恒等式
authors:
  - Курляндчик Л. Д.
  - Лисицкий А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 36
page_labels: "34"
tag: KJUA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: caeb7d46a970d3347aa6d710479f17c7c37450b921f05322a87cff75be2f8d5a
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/12_kurlyandchik-lisitskiy-kak-pridumat-kombinatornoe-tozhdestvo-02dc9a23.md
source_content_sha256: 76165c6f0174b4d1cdd500fdf6a0d52d2e4ce7b81ca0d30a7ed96d66bd32114c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

如何提出组合恒等式

在各种问题中，甚至在问题书«Kvant»中，也经常遇到包含生物系数$C_k^i$的恒等式。很多时候，可以通过数学归纳法来证明它们，有时通过各种巧妙的变换来证明它们，但这些证明通常会留下一种不满意的感觉：他们完全不清楚这个恒等式是如何发明的，新的恒等式一般是如何发现的。

在这里，我们将指出几个可让您提出此类恒等式的原语。特别是，我们将解释我们是如何得出���题 M470的；达吉斯坦男生 A. Gabibov 在给«Kvant»的信中询问了此事。

假设我们需要找到 $\sum_{k=1}^{n} kx^{k-1}$。让我们尝试使用我们遇到表达式 $kx^{k-1}$ 的地方。当然，在公式$(x^k)' = kx^{k-1}$中。我们的合同“杀死”了这项任务；真的吗，

$$\left( \sum_{k=1}^{n} x^k \right)' = \sum_{k=1}^{n} (x^k)' = \sum_{k=1}^{n} kx^{k-1}.$$

另一边，

$$\left( \sum_{k=1}^{n} x^k \right)' = \left( \frac{x^{n+1}-x}{x-1} \right)' =$$

$$= \frac{((n+1)x^n-1)(x-1)-(x^{n+1}-x)}{(x-1)^2} =$$

$$= \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n.$$

（在这个计算中，我们自然地假设$x \neq 1$。）所以，

$$\sum_{k=1}^{n} kx^{k-1} = \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n. \quad (1)$$

现在让我们尝试寻找

$$\sum_{k=1}^{n} k(k-1)x^{k-2}. \quad (\text{Особенности человекого характера побуждают повторить процедуру, которая помогла нам ранее в анализной ситуации...})$$

（D. Poya“数学发现”，M.，“Nauka”，1970 年，第 88 页）。那么让我们重复一遍吧！

$$\sum_{k=1}^{n} k(k-1)x^{k-2} =$$

$$= \sum_{k=1}^{n} (kx^{k-1})' = \left( \sum_{k=1}^{n} kx^{k-1} \right)' =$$

$$= \left( \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n \right)' = \frac{2}{(1-x)^3} +$$

$$+ \frac{n(1-x)^2+2(1-x)(nx-n-1)}{(1-x)^4} x^n +$$

$$+ \frac{n(nx-n-1)}{(1-x)^2} x^{n-1}. \quad (2)$$

等式（1）和（2）很麻烦。基于它们，我们可以得到（在$|x| < 1$）一个更漂亮的公式

$$\sum_{k=0}^{\infty} C_{k+n}^n x^k = \frac{1}{(1-x)^{n+1}},$$

但它的结论超出了学校课程的范围。

现在让我们讨论一种可以让我们从“旧”身份获得“新”身份的技术。良好的提取距离牛顿公式

$$(1+x)^n = \sum_{i=0}^{n} C_i^n x^i.$$

让我们对这个等式进行微分。我们得到

$$n(1+x)^{n-1} = \sum_{i=1}^{n} iC_i^n x^{i-1}. \quad (3)$$

将 $x=1$ 和 $x=-1$ 代入等式 (3)，我们发现。
