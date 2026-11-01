---
id: 1979-3-ryizhik-gde-oshibka-5b6885f3
issue: kvant_1979_3
year: 1979
number: "3"
title: 错误在哪里？
authors:
  - Рыжик В. И.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 43
page_last: 43
page_labels: "41"
tag: LC39
lang: zh
source: kvant_digital
extraction: vision
content_sha256: cbb9347c37b45ef2393b3014426f1fc45a81e5e5cb007c32d303bab475eefd27
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/12_ryizhik-gde-oshibka-5b6885f3.md
source_content_sha256: 17ca545ef7fbd7290826f80150871129d21a6e1885d91ab91298bf92eed2c191
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

错误在哪里？

在一些学校的一些（九年级），这个问题得到了解决。底面积为1、对角线为2的长方体的侧面的名称。

让我们用$a$和$b$表示底边的长度，用$c$表示侧边的长度。那么侧面面积$Q$将等于$2(a+b)c$。因此，要解决这个问题，您需要找到表达式的横向值

$$Q = 2(a+b)c.$$

(1)

由条件可知，平行六面体$a$、$b$、$c$的变化之间存在等式

$$\begin{cases} ab = 1, \\ a^2 + b^2 + c^2 = 4. \end{cases}$$

(2)

让我们将表达式 (1) 写为一个变量的函数。在那所学校的那个班级里，为此提出了两种方法。

第一种方式。从(2)$b = \frac{1}{a}$。

然后从 (3) $c = \sqrt{4-a^2 - \frac{1}{a^2}}$

这意味着需要找到最大值的函数具有以下形式

$$Q(a) = 2\left(a + \frac{1}{a}\right)\sqrt{4-a^2 - \frac{1}{a^2}}.$$

(4)

正如预期的那样，它可以是任意的。对其进行变换，我们得到

$$Q'(a) = -\frac{4(a-1)(a+1)(a^4-a^2+1)}{a^3\sqrt{-a^4+4a^2-1}}$$

函数$Q(a)$的定义域是一个集合

$$\left[-\sqrt{2+\sqrt{3}}; -\sqrt{2-\sqrt{3}}\right] \cup \left[\sqrt{2-\sqrt{3}}; \sqrt{2+}\sqrt{3}\right].$$

根据符号$a > 0$的含义。因此，我们需要找到函数(4)在线段$\left[\sqrt{2-\sqrt{3}}; \sqrt{2+}\sqrt{3}\right]$上的最大值。使用客观方法（“代数和开始分析 9”，第 59 段）可以发现

$$\max Q(a) = Q(1) = 4\sqrt{2}.$$

第二种方式。由(2)和(3)很容易得出

$$(a+b)^2 + c^2 = 6$$

(5)

或者

$$a+b = \sqrt{6-c^2}.$$

(6)

由(1)和(6)我们得到

$$Q(c) = 2c\sqrt{6-c^2}.$$

(7)

同样，可能是任意的：

$$Q'(c) = \frac{6-2c^2}{\sqrt{6-c^2}}.$$

函数$Q(c)$的定义域是线段$\left[-\sqrt{6}; \sqrt{6}\right]$。根据符号$c > 0$的含义。因此，它将在区间$[0; \sqrt{6}]$上寻找函数(7)的最大值。它是以对象的方式找到的

$$\max Q(c) = Q(\sqrt{3}) = 6.$$

事实证明，通过选择不同的变量来表达目标函数 u (1)，我们得到了结果。

在那所学校，那堂课，他们很快就明白发生了什么事情。你呢？
