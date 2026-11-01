---
id: 1980-5-olhov-kak-pridumat-geometricheskoe-neravenstvo-01b1ff97
issue: kvant_1980_5
year: 1980
number: "5"
title: 如何得出几何不等式
authors:
  - Ольхов В. Е.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 35
page_labels: "33"
tag: UD32
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f0ee9e723fbef7371ed7a6c8c869e2ea6c15381d0a6cc27327a7b360562e08c7
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/11_olhov-kak-pridumat-geometricheskoe-neravenstvo-01b1ff97.md
source_content_sha256: dc29ea4db9f6d51ee1e554b5610177c9ac8eb13add776e86b1db4d7cbde42fdf
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

如何得出几何不等式

“提出一个新的、原创的问题——请做出一个小的独立‘发现’，比解决别人现成的问题还要困难。”这些话出现在杂志第一期作业«Kvant»的序言中。很多人会问：你自己怎么能提出问题呢？

我会告诉你我曾经是如何想出几个几何不等式的。

我首先证明了两个众所周知的不等式：

$$a^4 + b^4 + c^4 \geqslant 16S^2,$$
$$a^2 b^2 + a^2 c^2 + b^2 c^2 \geqslant 16S^2,$$

其中$a, b, c$是三角形的边长，$S$是三角形的面积。我这样证明了他们。

通过写出三角形面积的公式

$$S = \frac{1}{2} ab \sin \gamma$$

和余弦定理

$$c^2 = a^2 + b^2 - 2ab \cos \gamma,$$

我发现了正弦和余弦

$$\sin \gamma = \frac{2S}{ab},$$
$$\cos \gamma = \frac{a^2 + b^2 - c^2}{2ab}$$

并将它们的值代入三角恒等式$$\sin^2 \gamma + \cos^2 \gamma = 1.$$ 原来

$$\frac{4S^2}{a^2 b^2} + \frac{a^4 + b^4 + c^4 + 2a^2 b^2 - 2a^2 c^2 - 2b^2 c^2}{4a^2 b^2} = 1,$$

或者

$$16S^2 = 2(a^2 b^2 + a^2 c^2 + b^2 c^2) - a^4 - b^4 - c^4.$$

因此，使用代数不等式（证明它）

$$a^4 + b^4 + c^4 \geqslant a^2 b^2 + a^2 c^2 + b^2 c^2,$$
(5)

我得到了不等式（1）和（2）。

经过一番思考，我决定尝试使用另一个三角恒等式。我写的不是$$\sin^2 \gamma + \cos^2 \gamma = 1$$

$$\sqrt{3} \sin \gamma + \cos \gamma = 2 \sin (\gamma + 30^\circ),$$
$$\sqrt{3} \sin \gamma + \cos \gamma \leqslant 2,$$

将对应关系（3）和（4）代入最后一个不等式，变换后得到

$$c^2 - a^2 - b^2 + 4ab \geqslant 4\sqrt{3} S.$$

注意到长度 $a, b, c$ 包含在 (6) “非等距”中，我又写了这个不等式的两个版本

$$a^2 - b^2 - c^2 + 4bc \geqslant 4\sqrt{3} S,$$
$$b^2 - a^2 - c^2 + 4ac \geqslant 4\sqrt{3} S.$$

把它们加起来我得到

$$(4ab + ac + bc) - (a^2 + b^2 + c^2) \geqslant 12\sqrt{3} S.$$

看看（7），我决定使用不等式

$$a^2 + b^2 + c^2 \geqslant ab + ac + bc$$

并得到，如（1）和（2）的证明，两个红色（但不幸的是，众所周知！）不等式

$$a^2 + b^2 + c^2 \geqslant 4\sqrt{3} S,$$
$$ab + bc + ca \geqslant 4\sqrt{3} S.$$

在此之后，我已经很清楚还能得到多少几何不等式了。

乌拉真亚

1. 证明不等式
$$2ab + 2bc - b^2 \geqslant 4\sqrt{3} S$$
找出什么时候它变成平等。

2. 证明对于等边三角形，不等式 (7) 变为等式。事实恰恰相反吗？

3. 应用三角不等式$$\sin^2 \gamma + \cos^2 \gamma \leqslant \sqrt{2},$$并证明

$$c^2 - a^2 - b^2 + 2\sqrt{2}ab \geqslant 4S,$$
$$\sqrt{2}(ab + bc) - b^2 \geqslant 4S,$$

并检查它们何时变成平等
