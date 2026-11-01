---
id: 1982-6-otvet-na-vopros-chitatelya-n-p-ratnikova-o-reshenii-neravenstva-s-integralom-0ac063de
issue: kvant_1982_6
year: 1982
number: "6"
title: '[回答读者 N.P. 的问题Ratnikov 关于用积分求解不等式]'
rubric: raznoe
page_first: 16
page_last: 16
page_labels: "14"
tag: WAC8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 59621eba41b33ec6d166d88410939e749c4e6efc04fedb3b045e6de85be78c3a
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/03_otvet-na-vopros-chitatelya-n-p-ratnikova-o-reshenii-neravenstva-s-integralom-0ac063de.md
source_content_sha256: 72903e98843be94909be87ce61919d804765906f63ad2bc318d92c5d7bd1d93b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

提问 - 我们回答

你是对的：根据学校课本中给出的积分定义（《代数与分析入门》第 9-10 章第 60 段），对于积分$\int_a^b f(x) dx$ 的存在性，要求子内函数$f$ 在端点为$a, b$ 的线段上连续（即对于 $a < b$ 在$[a; b]$ 上连续） $[b; a]$ 为 $a \geq b$）。

«Kvant»中所示的答案是通过过度格式化的插值获得的，该插值没有考虑牛顿-莱布尼兹公式成立的条件

$$\int_a^b f(x) dx = F(x) \bigg|_a^b.$$

如果函数 $f$ 在 $[a; b]$ 上连续且 $F'(x) = f(x)$ 在 $[a; b]$ 上处处连续，则此公式成立。

波兹尼

$$\int_0^x \frac{dy}{(y+1)^2} = -\frac{1}{y+1} \bigg|_0^x$$

仅对于 $x > -1$ 并且这个不等式等价于系统

$$\left\{ \begin{array}{l} \frac{9x-15}{19} < -\frac{1}{y+1} \bigg|_0^x -1 \\ x > -1. \end{array} \right.$$

问题的正确答案是：$\emptyset$。

顺便说一下，从 (*) 可以看出

$$\int_0^x \frac{dy}{(y+1)^2} = \frac{1}{x+1} -1.$$

对于$x < -1$，我们得到一个矛盾的结果：正函数的积分，即面积，是负的（回想一下，$\int_a^b f(x) dx$是$a < b$和$f(x) \geq 0$在$[a; b]$上的面积）。

对于熟悉不正确积分概念的人，请注意，对于 $x_0 < -1$，积分 $\int_0^x \frac{dy}{(y+1)^2}$ 不存在。
