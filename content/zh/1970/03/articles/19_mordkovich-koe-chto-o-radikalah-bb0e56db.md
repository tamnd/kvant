---
id: 1970-3-mordkovich-koe-chto-o-radikalah-bb0e56db
issue: kvant_1970_3
year: 1970
number: "3"
title: 关于部首的一些事
authors:
  - Мордкович А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 59
page_labels: 53-57
tag: Q3LL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4c2ddcc1edc5617d45ba16c8def5bb9ff2c4caf8c32652d65e5c0a6488fa2611
prompt_sha256: draft-1
translated_from: content/ru/1970/03/articles/19_mordkovich-koe-chto-o-radikalah-bb0e56db.md
source_content_sha256: c5413f2dd1175d2141e3351e3944ba75a8dc49cde0d4c495e50ccbfcbff17c45
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

关于 RADICALAX 的一些事情

A·G·莫德科维奇

“现在，”考官说，“我想再给你一项任务，一项非常简单的任务。”这里是：

已知一个卡梅特在青门线上的投影是 6 厘米，另一个卡梅特的投影比这个卡梅特的长度小 1.5 厘米，求直角三角形的边。

...几分钟后，申请人一起去见审查员。
- 嗯，你是怎么解决这个问题的？ - 考官问道。
- 是的！ - 参赛者回答。
- 发生了什么事？
——问题没有解决办法。
- 你能证明这一点吗？

- 当然！考虑三角形 ABC（参见 图）； C是直角的顶角，CH是高度。令AC = x，则由条件AH == x—1.5，且BH = 6。

⟦folio 54⟧

我们使用已知的关系
$$CH^2 = BH \cdot AH$$ 或 $$CH^2 = 6(x - 1,5).$$

将勾股定理应用到直角三角形$ACH$，我们得到

$$\sqrt{AC^2 - CH^2} = AH,$$

那是

$$\sqrt{x^2 - 6(x - 1,5)} = x - 1,5.$$

“嗯，到目前为止一切都是正确的，”审查员指出，“尽管我们必须说所选择的解决方案路径并不是最合理的。”

“然后，”参赛者继续说道，“剩下简单的计算：

$$\sqrt{x^2 - 6x + 9} = x - 1,5; \quad \sqrt{(x - 3)^2} = x - 1,5;$$

$$x - 3 = x - 1,5; \quad -3 = -1,5.$$

由于最后一个等式是假的，所以问题无解。

“不幸的是，我一定让你失望了，”主考官说道，“这个问题是有解决办法的。”例如，可以这样解决：从已知关系$AC^2 = AB \cdot AH$我们有$x^2 = (x + 4,5) (x - 1,5), 3x = 4,5 \cdot 1,5$和$x = 2,25$，即$AC = 2,25$cm。然后是$AB = 6,75$厘米，然后是$BC = 4\sqrt{2}$厘米。

并且，注意到申请人困惑的表情，审查员补充道：

- 你显然对你的推理中的错误所在感兴趣。好吧，让我们弄清楚一下。

错误在哪里？

“你记得，”考官开始说道，“我虽然有所保留，但还是认可了你的几何推理。”所以错误只可能发生在你所谓的“简单计算”中。更准确地说，在提取平方根时出现了错误。你没有教说，根据问题的意思，数量$\sqrt{(x - 3)^2}$必须是正数。一般来说，在实数领域，符号 $\sqrt{}$ 表示算术的、非负的根值。所以，$\sqrt{16} = 4$，你不能写$\sqrt{16} = -4$或$\sqrt{16} = \pm 4$。因此，不能说$\sqrt{a^2} = a$总是：对于$a \geq 0$来说这个等式是正确的，但是数字$a$也可以是负数！化简，例如 $\sqrt{(-3)^2}$：

申请人写道：

$$\sqrt{(-3)^2} = \sqrt{9} = 3.$$

- 正确的。换句话说，

$$\sqrt{(-3)^2} = -(-3).$$

一般来说，如果$a < 0$，则$\sqrt{a^2} = -a$。

因此，

$$\sqrt{a^2} = \begin{cases} a, если a \geq 0, \\ -a, если a < 0. \end{cases}$$

“我明白了，”申请人感叹道，“这可以简单地写成：$\sqrt{a^2} = |a|$，因为模型$a$的定义方式完全相同：

$$|a| = \begin{cases} a, если a \geq 0, \\ -a, если a < 0. \end{cases}$$

- 完全正确。这与你的问题完全相同：你不能写

⟦folio 55⟧

$$\sqrt{(x-3)^2} = (x-3), \text{ потому что } (x-3) \text{ может быть и отрицательным числом.}
\text{Если воспользоваться тем, что } \sqrt{(x-3)^2} = |x-3|, \text{ то приdem к управлению } |x-3| = x-1, 5.$$

接下来我们应该考虑两种情况：1）$x-3 \geq 0$； 2）$x-3 < 0$。你只考虑了第一种情况，所以过早地得出了问题无解的结论。在第二种情况下$|x-3| = -(x-3)$。然后从方程$-(x-3) = x-1, 5$我们得到$x = 2, 25$，即$AC = 2, 25$厘米。

“一切都清楚了，”参赛者说。
在这种情况下，我们将认为我们的谈话结束了。恳请您原谅，我给您以下建议：

别忘了$\sqrt{a^2} = |a|!$

我们将与申请人和审查员讨论这个问题，但我们会考虑审查员的建议。特别是，我们将在解决以下示例时使用它。

示例 1：简化表达式

$$\sqrt{\frac{a+x^2}{x} - 2\sqrt{a}} + \sqrt{\frac{a+x^2}{x} + 2\sqrt{a}}, \text{ если } x > \sqrt{a}.$$

解决方案。我们有

$$\sqrt{\frac{a+x^2-2x\sqrt{a}}{x}} + \sqrt{\frac{a+x^2+2x\sqrt{a}}{x}} =$$

$$\frac{\sqrt{(V\bar{a}-x)^2}}{\sqrt{x}} + \frac{\sqrt{(V\bar{a}+x)^2}}{\sqrt{x}} = \frac{|V\bar{a}-x|}{V\bar{x}} + \frac{|V\bar{a}+x|}{V\bar{x}}.$$

因为根据条件$x > \sqrt{a} \geq 0$，则$|V\bar{a}-x| = -V\bar{a} + x$，$|V\bar{a}+\bar{x}| = \sqrt{a} + x$，这个表达式变换如下：

$$\frac{-V\bar{a} + x + \sqrt{a} + x}{\sqrt{x}} = 2\sqrt{x}.$$

关于自由基性质的几句话

在解决带有部首的动作示例时，必须使用部首的各种性质。因此，在示例 1 中，我们相当随意地使用了众所周知的属性：

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{b}.$$

然而，应该考虑到这种相等仅发生在$a \geq 0$和$b > 0$的情况下。如果$a$和$b$是负数，那么符号$\frac{\sqrt{a}}{b}$在实数领域没有意义。在示例 1 中，就我们而言，由于 $(V\bar{a}-x)^2 > 0$、$(V\bar{a}+x)^2 > 0$ 以及条件 $x > 0$，因此没有发生错误。但是，无论如何，从上面我们可以得出以下结论：在揭示乘积或分数的（次数）根时必须非常小心。一般情况下，当$a$和$b$的符号未知时，建议进行如下推理：

$$\sqrt{\frac{a}{b}} = \sqrt{\frac{|a|}{|b|}} = \sqrt{\frac{|a|}{|b|}}.$$

⟦folio 56⟧

因此，如果数字 $a$ 和 $b$ 具有相同的符号，则

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{|a|}}{\sqrt{|b|}}$$

和类似地

$$\sqrt{ab} = \sqrt{|a|} \cdot \sqrt{|b|}.$$

示例 2：简化

$$\sqrt{\frac{a-\sqrt{x}}{a+\sqrt{x}}} + \sqrt{\frac{a+\sqrt{x}}{a-\sqrt{x}}} - \sqrt{\frac{16}{a^2-x}},$$如果$x = 4(a-1)$。

解决方案。相反，让我们表达$a$到$x$：$a = \frac{x+4}{4}$，并将其代入这个表达式。它是这样转换的：

$$\sqrt{\frac{x-4\sqrt{x}+4}{x+4\sqrt{x}+4}} + \sqrt{\frac{x+4\sqrt{x}+4}{x-4\sqrt{x}+4}} - \sqrt{\frac{16^2}{(x+4)^2-16x}}$$

$$= \frac{|\sqrt{x}-2|}{|\sqrt{x}+2|} + \frac{|\sqrt{x}+2|}{|\sqrt{x}-2|} - \frac{16}{\sqrt{x^2}-8x+16}$$

$$= \frac{(x-4\sqrt{x}+4) + (x+4\sqrt{x}+4)}{|(\sqrt{x})^2-4|} - \frac{16}{|x-4|} = \frac{2x+8}{|x-4|} - \frac{16}{|x-4|} = 2\frac{x-4}{|x-4|}.$$

另请注意，如果$a > 2$则为$x > 4$，如果$1 \leqslant a < 2$则为$x < 4$。

最终答案：

2 如果$a > 2$，
- 2 如果$1 \leqslant a < 2$。

我们使用了 - 这通常很有用 - 模块的以下属性：对于所有 $a$ 和 $b$

$$|a| \cdot |b| = |ab|, \quad |a|^2 = a^2.$$

现在我们将详细讨论根的一个更重要的属性。

示例 3：简化

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}.$$

解决方案。人们常常这样想。 Using the well-known property of the root, you can show the root of the second factor by multiplying by 2 and at the same time squaring the subordinate expression;我们得到

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{19^2-(6\sqrt{10})^2} = \sqrt[10]{1} = 1.$$

但这里有一个错误！正确答案是负一。重点是$3\sqrt{2}-2\sqrt{5} < 0$因为$(3\sqrt{2})^2 = 18 < (2\sqrt{5})^2 = 20$。

因此，事实并非如此 $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$，但确实如此 $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = -\sqrt[5]{2\sqrt{5}-3\sqrt{2}} = -\sqrt[10]{(2\sqrt{5}-3\sqrt{2})^2}$.

示例 4：化简 $\sqrt[8]{(\pi^2-10)^4}$。

⟦folio 57⟧

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{\pi^2 - 10}$$

(the result does not make sense because $\pi^2 < 10$).以下等式成立：

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{10 - \pi^2}.$$

结果，我们得出以下结论：

任务

1. 列出下列等式成立的条件（$k$ 和 $n$ - 自然数）：

a) $$\sqrt[n]{-a} = -\sqrt[n]{a};$$
e) $$a \cdot \sqrt[n]{b} = \sqrt[n]{a^n b};$$
6) $$\sqrt[n]{a^n} = a;$$
g) $$\sqrt[n]{a} = \sqrt[n]{a^k};$$
b) $$(\sqrt[n]{a})^n = a;$$
h) $$\sqrt[k]{\sqrt[n]{a}} = \sqrt[k]{a};$$
d) $$\sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b};$$
我）$$(\sqrt[n]{a})^k = \sqrt[n]{a^k};$$
e) $$\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{n \sqrt[n]{b}};$$
j) 如果$a < b$，则$$\sqrt[n]{a} < \sqrt[n]{b}$$。

2. 化简下列表达式：

a) $$(\sqrt{\frac{a+1}{a-1}} + \sqrt{\frac{a-1}{a+1}}) \cdot (\sqrt{\frac{a+1}{a-1}} - \sqrt{\frac{a-1}{a+1}});$$
6) $$\sqrt{\frac{3y+x^3}{2x}} + \sqrt{3xy} - \sqrt{\frac{3y+x^3}{2x}} - \sqrt{3xy};$$
b) $$\frac{(4a^2m^{-2} + a^{-2}m^2 - 4)^{-1/2}}{2ma (m^2 - a^2)^{-1/2}} \cdot \left(2 \sqrt{m^4 - \frac{a^2}{m^{-2}}} - \frac{2a^2}{\sqrt{1 - a^2}m^{-2}}\right);$$
d) $$\frac{a + \sqrt{2 + \sqrt{5}} \cdot \sqrt[12]{(9 - 4\sqrt{5})^3}}{\sqrt[3]{2 - \sqrt{5}} \cdot \sqrt[6]{9 + 4\sqrt{5}} - \sqrt[3]{a^2} + \sqrt[3]{a}}.$$
