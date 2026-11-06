---
id: 1990-12-bendukidze-nachinaem-s-neravenstva-evklida-35625d2f
issue: kvant_1990_12
year: 1990
number: "12"
title: 让我们从欧几里得不等式开始......
authors:
  - Бендукидзе А. Д.
rubric: shkola-v-kvante
page_first: 36
page_last: 37
page_labels: 34-35
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 55969820f9e16a0c39ac0600e33a1c625000a39a34f550ad0cc41cdf209e6c87
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/11_bendukidze-nachinaem-s-neravenstva-evklida-35625d2f.md
source_content_sha256: d4cd6abcdfeebd6eb78bfb855e052534ec86269d1b75c8f27cec615683055a16
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 34⟧

---
running_head:
folio:
---

数学9-11
发表的文章适用于儿童
Nyatiklassiki。

让我们开始吧
与不平等
欧几里得...

第五条二十五声明
著名的欧几里得“原理”*）的 kigi 说：如果有四个量
成正比，那么最
最小的大于其余两个
（即最大和最小的总和
颈部大于其余两个的总和）。
对于现代读者来说，这是一个声明
情况看起来不会特别困难
nom，但它包含预
*）欧几里得——古希腊伟大的数学家，
谁生活在公元前3世纪。他的主要角色是
Bota - 六卷本《原理》 - 产生了影响
对整个数学的发展产生了重大影响。

发送许多结果
算术和分析。所以，从他的角度来看
功率可以很容易地证明一
级数的简洁定理，从
这意味着众所周知的不平等
雅各布·伯努利的艺术*）。但我们正在谈论
这是前面的。

那么让我们看看不平等
欧几里得。应该说，ενkli-
这个不等式的证明纯粹是几何的。然而，
这并不奇怪——毕竟作者
《Nachal》只用几何语言与读者对话！不仅几何，而且纯算术陈述（以下简称素数集无穷大的陈述——第九卷第 20 条陈述）在《几何原本》中都得到了几何证明。

然而，这些陈述的证据背后的想法

*）雅各布·伯努利——预兆的创始人
居住在第二个瑞士数学家家庭
17世纪下半叶。

⟦folio 35⟧

---
running_head:
folio:
---

类型，由现在的欧几里得清楚地呈现出来，并且将它们从几何语言“翻译”为算术或代数语言并不困难。

我们必须证明如果$a, b, c, d$是正数$u$

$$\frac{a}{b} = \frac{c}{d},$$

那么这些数字中最大和最小的和大于其他两个的和。

事实上，不失一般性，我们可以假设最大的是$a$。从这个比例来看

$$d = b \frac{c}{a} = c \frac{b}{a},$$

由于分数 $c/a$ 和 $b/a$ 都小于 1，因此 $d < b, d < c$。因此，$d$是最小的数，因此我们需要证明不等式

$$a + d > b + c.$$

我们有

$$\frac{a}{b} = \frac{c}{d} \Leftrightarrow \frac{a}{b} - 1 = \frac{c}{d} - 1 \Leftrightarrow$$

$$\Leftrightarrow \frac{a - b}{b} = \frac{c - d}{d} \Leftrightarrow \frac{a - b}{c - d} = \frac{b}{d} \Leftrightarrow a - b =$$

$$= \frac{b}{d}(c - d).$$

由于$c - d > 0$和$b/d > 1$，那么

$$a - b > c - d,$$

或者，这是同样的事情，$a + d > b + c$。这就是我们想要证明的。

现在我们制定并证明伯努利级数定理。

定理。如果$(a_n)$是等差数列，$(b_n)$是正数$u$$a_1 = b_1, a_2 = b_2, a_1 \neq a_2$的等比级数，则从第三个开始的等比级数的项大于等差数列的相应项。

证明。让$m > 2$。我们有

$$\frac{b_m}{b_{m-1}} = \frac{b_2}{b_1}.$$

如果$(b_n)$是递增级数，那么写下的四个数字中，最大的是$b_m$，最小的是$b_1$。如果级数$(b_n)$杀死了，那么，相反，$b_m$是最小的，而$b_1$是这些数字中最大的。因此，在第一种和第二种情况下，根据欧几里得不等式，

$$b_m + b_1 > b_{m-1} + b_2.$$

回想一下 $b_1 = a_1, b_2 = a_2$，并用 $d$ 表示级数 $(a_n)$ 的差，我们得到不等式

$$b_m > b_{m-1} + d,$$

对于任何自然$m > 2$都有效。

依次给 $m$ 值 3, 4, 5, ..., $n$，我们看到

$$b_3 > b_2 + d,$$

$$b_4 > b_3 + d,$$

$$b_n > b_{n-1} + d.$$

添加不等式，我们得到

$$b_n > b_2 + (n - 2)d = a_2 + (n - 2)d = a_1 + (n - 1)d = a_n.$$

所以，对于任意 $n > 2$

$$b_n > a_n,$$

这就是所需要的。

推论（伯努利不等式）。如果$h > -1, h \neq 0$，则对于任何自然$n > 1$

$$(1 + h)^n > 1 + nh.$$

事实上，考虑两个序列

$$1, 1 + h, (1 + h)^2, ..., (1 + h)^n, ...,$$

$$1, 1 + h, 1 + 2h, ..., 1 + nh, ...$$

第一个是算术级数，第二个是几何级数，它们满足伯努利定理的条件。波佐托穆

$$(1 + h)^n > 1 + nh (n = 2, 3, 4, ...),$$

这是需要证明的。

请注意，对于$h > 0$，这种不等式源自牛顿生物群落的公式，但对于$-1 < h < 0$，即使对于熟悉牛顿生物群落的人来说，它也不完全明显。

A·文杜基泽
