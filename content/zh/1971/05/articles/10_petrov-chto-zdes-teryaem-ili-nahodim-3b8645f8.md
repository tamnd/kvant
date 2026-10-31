---
id: 1971-5-petrov-chto-zdes-teryaem-ili-nahodim-3b8645f8
issue: kvant_1971_5
year: 1971
number: "5"
title: 我们在这里失去或发现了什么？
authors:
  - Петров В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 43
page_labels: 40-41
tag: 1QIU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2008a53e8d449e8a422acdc7e8a219a2ec6581ff321f1bcde680debf81520ae5
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/10_petrov-chto-zdes-teryaem-ili-nahodim-3b8645f8.md
source_content_sha256: 97fe5dc4ab9a79753b0b4e2ffabccd53b938a2bbe589894eb51d1ab7738b5f5e
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

我们在这里失去或找到了什么？

彼得罗夫

几乎每张数学笔试试卷都包含某种方程。考生在解题时，不仅要准确核对得出答案所需的计算，而且还要求确保这些计算是正确的。您需要能够分析每个提议的转换：它是否会导致等价方程，是否会威胁到解决方案的丢失或获得。

A. G. Mordkovich 的文章“有人失去，有人发现”（«Kvant» No. 5，1970）*）考虑了“战斗”与已建根和失去根的策略问题。现在我们邀请你来测试一下你对这个策略是否有足够的信心。首先，给出方程的解。您需要分析这些决策并回答以下问题。答案正确吗？如果没有，那么这里是什么——是失去了根还是找到了结构？为什么？正确答案是什么？将您的想法与第 62 页上我们的想法进行比较。

1. $2\sin 4x = \sqrt{2(1 - \cos 4x)}$.

解决方案。使用公式
$$2\sin^2\alpha = 1 - \cos 2\alpha,$$
我们得到
$$2\sin 4x = \sqrt{4\sin^2 2x}$$
或者
$$\sin 4x = \sin 2x,$$
这已经很容易解决了。

答案：$x = n\pi$和$x = \frac{\pi}{6} + n\frac{\pi}{3}$，其中$n = 0, \pm 1, \pm 2, \dots$

*) 这种“策略”在 G.V. 的书中有更详细的介绍。多罗费耶夫，M.K. Potanov, N.H. Rozov，对申请人非常有用，“建设大学的数学手册”，M.，“Nauka”，1970 年。

2. $8\cos x\cos 2x\cos 4x = 1$.

解决方案。将等式两边乘以sin$x$，并利用三倍角正弦公式，得到简单的等式
$$\sin 8x = \sin x.$$
答案：$x = (2n + 1)\frac{\pi}{9}$和$x = 2n\frac{\pi}{7}$，其中$n$是任意整数。

3. $\sin \left(\frac{1}{5}\arccos x\right) = 1$.

解决方案。从这个方程我们发现
$$\arccos x = \frac{5\pi}{2} + 10n\pi$$
($n = 0, \pm 1, \pm 2, \dots$).

⟦folio 41⟧

从这里，根据 arccos $x$ 的定义，我们得到$x = \cos \left( \frac{5\pi}{2} + 10n\pi \right) = 0$。

答案：$x = 0$。

4. $\log_{x-1} (x^2 - 5x + 7) = 1$.

解决方案。让我们找到 ODZ：

$$x^2 - 5x + 7 > 0, \quad x - 1 > 0,$$

从哪里$x > 1$。根据对数函数的定义，我们有$x^2 - 5x + 7 = x - 1; \quad x_1 = 2, \quad x_2 = 4$。

由于这两个值都包含在 ODZ 中，因此它们都是原方程的解。

5. $\sqrt[3]{2x - 1} + \sqrt[3]{x - 1} = 1$.

解决方案。让我们对方程两边求三次方：

$$3x - 2 + 3\sqrt[3]{(2x - 1)(x - 1)} \times (\sqrt[3]{2x - 1} + \sqrt[3]{x - 1}) = 1.$$

括号中的表达式代表原始方程的左侧 - 可以用右侧代替。此后，方程简化为形式

$$(2x - 1) (x - 1) = (1 - x)^3.$$

答案：$x_1 = 0, \quad x_2 = 1$。

6. 方程可以吗

$$\sqrt{x + a\sqrt{x + b}} + \sqrt{x} = c$$

有无穷多个解吗？

解决方案。向右移动 $\sqrt{x}$ 并将两边平方：

$$x + a\sqrt{x + b} = c^2 - 2c\sqrt{x} + x.$$

引入类似的项后，我们得到：$(a + 2c)\sqrt{x} = c^2 - b$。对于 $a + 2c = 0$ 和 $c^2 - b = 0$（且仅在这种情况下），方程成为对所有非负 $x$ 有效的恒等式。

答案：方程在$a = -2c$和$b = c^2$处有无穷多个解。这种情况下的解是$x \ge 0$。

7. $$\cos \frac{x}{2} \sqrt{x^2 + (7-\pi)x - 7\pi} = 1.$$

解决方案。如果，当提高到一些积极的力量
