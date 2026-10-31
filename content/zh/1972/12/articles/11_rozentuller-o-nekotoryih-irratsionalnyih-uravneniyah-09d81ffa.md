---
id: 1972-12-rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa
issue: kvant_1972_12
year: 1972
number: "12"
title: 关于一些无理方程
authors:
  - Розентуллер В. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 54
page_labels: 51-52
tag: C2O4
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ce0e6260809582aa74ec5c72dd0b243ab1b0d1f1d063280ee7694a3514a863fa
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/11_rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa.md
source_content_sha256: 42fcb89791fdeccc9509e02bee6f43dd8ad4ad46dbef7f5e6db3002dcce41101
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

关于一些无理方程

V·M·罗森图勒

A. M. Grigoriev 的文章“Irrational Equations”（«Kvant» No. 1，1972）详细讨论了求解无理方程的技术。但一般的例子并不总是最好的。本文使用三个示例来演示一种方法，可以让您快速且“漂亮”地求解某些（实际上不仅是无理数）方程。

示例 1. 求解方程：

$$\sqrt{x - 30} + \sqrt{2x + 4} = 8.$$

解决方案。 ODZ 由不等式系统确定

$$\begin{cases} x - 30 \geq 0, \\ 2x + 4 \geq 0, \end{cases}$$

在哪里

$$x \geq 30.$$

然后你就可以这样继续下去。我们将两边平方并得到：

$$x - 30 + 2x + 4 + 2\sqrt{2x^2 - 56x - 120} = 64,$$

$$2\sqrt{2x^2 - 56x - 120} = 90 - 3x.$$

我们必须再次对该方程两边进行平方*）：

$$8x^2 - 224x - 480 = 8100 - 540x + 9x^2,$$

$$x^2 - 316x + 8580 = 0,$$

$$x_{1,2} = 158 \pm \sqrt{158^2 - 8580} = 158 \pm \sqrt{16884} = 158 \pm 128;$$

$$x_1 = 286, x_2 = 30.$$

*) 在这种情况下，从最后一个方程已经可以清楚地看出$x \leq 30$，并且只需要检查$x = 30$，但这是一个意外。

检查发现$x_1 = 286$是构造根，$x_2$满足问题的条件。

答案：$x = 30$。

我们求解了这个方程，需要对其进行两次平方并检查根。难道就没有更简单的解决方案吗？

我们已经定义了 ODZ：$x \geq 30$。解这个方程时是否可以立即使用它？我们来试试吧。

ODZ 允许：$x = 30$ 和$x > 30$。让我们检查一下$x = 30$。让我们将值 $x = 30$ 代入这个方程：

$$\sqrt{30 - 30} + \sqrt{60 + 4} = 8,$$

$$0 + 8 = 8,$$

$$8 = 8.$$

我们获得了这份荣誉。因此，$x = 30$是该方程的根。现在剩下的就是检查$x > 30$。

对于$x > 30$，我们有$\sqrt{x - 30} > 0,$

$$\sqrt{2x + 4} > 8,$$

在哪里

$$\sqrt{x - 30} + \sqrt{2x + 4} > 8.$$

因此，任何$x > 30$都不满足方程。剩下的唯一答案是$x = 30$。

示例 2. 求解方程：

$$5\sqrt{2x - 24} + 3\sqrt{5x - 59} + \sqrt{x - 8} + \sqrt{3x - 20} + \sqrt{x + 13} + 2\sqrt{x + 24} = 26.$$

解决方案。 ADL 已确定

⟦folio 52⟧

不平等制度：

$$\begin{cases} x \geq 12, \\ x \geq 11,8, \\ x \geq 8, \\ x \geq 6\frac{2}{3}, \\ x \geq -13, \\ x \geq -24, \end{cases}$$

从哪里$x \geq 12$。

因此，ODZ 允许：$x=12$ 和$x>12$。

让我们检查一下$x=12$：$5\sqrt{24-24} + 3\sqrt{60-59} + \sqrt{12-8} + \sqrt{36-20} + \sqrt{12+13} + 2\sqrt{12+24} = 0 + 3 + 2 + 4 + 5 + 12 = 26$。

我们获得了这份荣誉。因此，$x=12$是方程的根。

现在让我们检查$x>12$：

$$5\sqrt{2x-24} > 0,$$

$$3\sqrt{5x-59} > 3,$$

$$\sqrt{x-8} > 2,$$

$$\sqrt{3x-20} > 4,$$

$$\sqrt{x+13} > 5,$$

$$2\sqrt{x+24} > 12.$$

因此$5\sqrt{2x-24} + 3\sqrt{5x-59} + \sqrt{x-8} + \sqrt{3x-20} + \sqrt{x+13} + 2\sqrt{x+24} > 26,$

这与问题的条件相矛盾。剩下的唯一答案是$x=12$。

示例 3. 求解方程：

$$\sqrt{x(x+1)} = \sqrt{x+3} - \sqrt{1 + \frac{1}{x^2}}.$$

解决方案。让我们将方程的项分组如下：

$$\sqrt{x^2+x} + \sqrt{1 + \frac{1}{x^2}} = \sqrt{x+3}.$$

让我们将两边都平方：

$$x^2+x+1 + \frac{1}{x^2} +$$

$$+ 2\sqrt{(x^2+x)\left(1 + \frac{1}{x^2}\right)} = x+3,$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = x+3 - x^2 - x - 1 - \frac{1}{x^2},$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = 2 - \left(x^2 + \frac{1}{x^2}\right).$$

已知$x^2 + \frac{1}{x^2} \geq 2$，但是$\sqrt{x^2+x+1 + \frac{1}{x}} \geq 0$，所以$x^2 + \frac{1}{x^2} = 2$和$\sqrt{x^2+x+1 + \frac{1}{x}} = 0$。

当$x^2=1$时，第一个相等是可能的，因此$x_1=1; x_2=-1$，而当$x=-1$时，第二个$\sqrt{x^2+x+1 + \frac{1}{x}} = 0$是可能的。经检验，$x=-1$为方程根。

填字游戏的答案（参见封面第 4 页）

水平的：

8. 法拉。 9.远地点。 10. 转变。 11. 频率。 12.高斯。 15. 惯性。 16. 直径。 18. 硬橡胶，19. 硼。 20.巴德克。 23. 细分。 25. 开尔文。 28. 量子。 29.卡路里。 30. 光子。 33. 工作。 34. 核子。

垂直的：

1. 狄拉克。 2.吊坠。 3. 频谱。 4.卡托。 5、钒。 6.钟摆。 7.笛卡尔。 13.阿基米德。 14.冲动。 17. BSR。 21.托卡马克。 22. 麦地那。 24. 钽。 26. 同位素。 27.洛伦兹。 31. 光子。 32.雅可比。
