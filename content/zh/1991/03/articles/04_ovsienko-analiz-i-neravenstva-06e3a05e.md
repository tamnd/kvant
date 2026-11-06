---
id: 1991-3-ovsienko-analiz-i-neravenstva-06e3a05e
issue: kvant_1991_3
year: 1991
number: "3"
title: 分析和不平等
authors:
  - Овсиенко В. Ю.
rubric: osnovnye-stati
page_first: 17
page_last: 20
page_labels: 15-18
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1ca877c0b51a097d5b2194ccc2f6214ce447d85a723b011d3d2089a82bd41886
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/04_ovsienko-analiz-i-neravenstva-06e3a05e.md
source_content_sha256: 2f35a29dd075e24fb8d1a98b1ec75356db3dd214be9edd3c298577401661398b
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 15⟧

---
running_head:
folio:
---

分析与
不平等现象

物理和数学科学候选人
V·奥夫辛科

亨利·庞加莱（Henri Poincaré）说，数学是用做不同的事情来表达同样的事情的一种方式。这尤其适用于数学分析，就像经验丰富的窃贼手中的万能钥匙一样，它提供了“打开所有门的通用钥匙”......

我们将讨论以相同方式解决的三个不同任务。解决方案将基于学校课程中众所周知的陈述：如果某个函数的导数大于零，则该函数正在增加（反之亦然，如果导数小于零，则该函数正在减少）。

正弦和余弦的不等式

不平等现象

$$\sin x < x,$$
$$\cos x > 1 - \frac{x^2}{2},$$

对于 $x > 0$ (图 1) 有效，几何数通常已被证明（在学校）。然而，分析证明要简单得多，不需要太多的独创性。

让我们从第一个不等式开始。 nULE 中的函数 $y_1(x) = \sin x$ 和 $y_2(x) = x$ 相同。因此，只要证明在 $x > 0$ 处第二个函数比第一个函数增长得更快（即 $y(x) = x - \sin x$ 是$x > 0$ 处的递增函数）。但$y'(x) = 1 - \cos x$在$x > 0$处的导数大于零。不等式已被证明。

为了证明第二个不等式，我们将做同样的事情。

函数 $y(x) = \cos x - 1 + \frac{x^2}{2}$ 在 $x = 0$ 处等于 0。它的导数是$y'(x) = -\sin x + x$。因此，$y'(x) > 0$ 和 $x > 0$（由于第一个

⟦folio 16⟧

---
running_head:
folio:
---

不等式！），即函数正在增加，因此为正值。

练习
1. 证明对于 $x > 0$
a) $\sin x > x - \frac{x^3}{6}$,
b) $\cos x < 1 - \frac{x^2}{2} + \frac{x^4}{24}$.

笔记。像以前一样做。微分后，使用前面的不等式。
2. 继续得到 sin $x$ 和 cos $x$ 的不等式链。

三角形中的不等式

对于角为 $\alpha, \beta, \gamma$ (图 2) 的三角形，以下不等式成立：
$$\sin \alpha + \sin \beta + \sin \gamma \leq \frac{3\sqrt{3}}{2}.$$

让我们证明一下。首先，请注意，如果三角形是正三角形 ($\alpha = \beta = \gamma = 60^\circ$)，则等式成立。

令三角形为等边三角形，其角度等于 $\alpha = 60^\circ + x, \beta = \gamma = 60^\circ - \frac{x}{2}$，其中 $x$ 是$-60^\circ < x < 120^\circ$ 的某个数字。那么表达式 $\sin \alpha + \sin \beta + \sin \gamma$ 是 $x$ 的函数：
$$f(x) = \sin (60^\circ + x) + 2\sin \left(60^\circ - \frac{x}{2}\right).$$
她的产品是$f'(x) = \cos (60^\circ + x) - \cos \left(60^\circ - \frac{x}{2}\right)$。很明显，$f'(x) > 0$位于$-60^\circ < x < 0$，$f'(x) < 0$位于$0 < x < 120^\circ$。因此，函数 $f(x)$ 在点 $x = 0$ 处具有最大值，并且 $x$ 距离零越远，函数越小。

现在让函数$\alpha$改变角度$\beta$和$\gamma$：$\beta = \delta - x$，$\gamma = \delta + x$。那么原始表达式将再次成为 $x$ 的函数：
$$f(x) = \sin (\delta - x) + \sin (\delta + x) + \sin \alpha.$$
她的作品 $f'(x) = \cos (\delta + x) - \cos (\delta - x)$。再次 $f'(x)$ 大于零表示负数 $x$ 小于零为正 $x$。换句话说，表达式 $\sin \alpha + \sin \beta + \sin \gamma$ 越小，三角形与等边三角形的差异就越大。

不等式被证明是因为通过先改变角$\alpha$，然​​后改变$\beta$和$\gamma$，可以从等边三角形得到三角形。我们相信，通过这样的改变，表达式$\sin \alpha + \sin \beta + \sin \gamma$将一直减少。

练习 3. 证明不等式
a) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$,
b) $\sin \alpha \cdot \sin \beta \cdot \sin \gamma \leq \frac{3\sqrt{3}}{8}$,
b) $\cos \alpha \cdot \cos \beta \cdot \cos \gamma \leq \frac{1}{8}$,
如果 $\alpha, \beta, \gamma$ 是某个三角形。

柯西不等式

对于任何非负数 $a_1, ..., a_n$，以下不等式成立：
$$\frac{a_1 + ... + a_n}{n} \geq \sqrt[n]{a_1 \cdot ... \cdot a_n}$$

介于算术平均数和几何平均数之间。它被称为柯西不等式。我们将使用相同的方法来证明它，即通过计算某个函数的任意函数。

作为热身，让我们从一个非常简单的案例$n = 2$的证明开始。

⟦folio 17⟧

---
running_head:
folio:
---

$\frac{a+b}{2} \geqslant \sqrt{ab}$
以各种几何方式证明（包括非常漂亮的方式）。我们将在其上制定我们的方法。让我们定义$a \leqslant b$。然后是$b=a+x$，其中$x$是某个非负数。表达式 $\frac{a+b}{2} - \sqrt{ab}$ 成为 $x$ 的函数，具有 $f(x) = \frac{2a+x}{2} - \sqrt{a(a+x)}$ 的形式。
对于$x=0$，函数为$f(x)=0$，其乘积为$f'(x) = \frac{1}{2} - \frac{1}{2} \sqrt{\frac{a}{a+x}} > 0$。
因此，函数$f(x)$是递增的，即算术平均值大于几何平均值，差值$b-a=x$越大。
现在让我们在一般情况下证明柯西不等式。事实上，这个证明是前一个证明的重复。我们只需要函数$\sqrt[n]{x^k} = x^{\frac{k}{n}}$的导数值。课本上计算的是：$\left( x^{\frac{k}{n}} \right)' = \frac{k}{n} x^{\frac{k}{n}-1}$。
让我们定义$a_1 \leqslant a_2 \leqslant \dots \leqslant a_n$。很明显，对于$a_1 = \dots = a_n$，我们的不平等变成了平等。我们将取$n$相同的数字$a_1, a_1, \dots, a_1$并增加它们（从第二个开始），但不是一步一步，而是分$(n-1)$步。第一步——
$$a_1, a_1+z, \dots, a_1+z$$
（其中$a_1+z=a_2$），
在第二步中 -
$$a_1, a_2, a_2+y, \dots, a_2+y$$
（其中$a_2+y=a_3$）。
我们最终会得到一组数字$a_1, a_2, \dots, a_n$。
我们将证明，在任何一步，算术平均值和几何平均值之间的差异都会增加

⟦folio 18⟧

---
running_head:
folio:
---

自杂志创刊以来，我们一直在逐期运行此版块。其中发布的问题是非标准的，但它们的解决方案不需要超出学校课程范围的知识。最困难的任务标有星号。创建任务后，我们通常会指出谁向我们提出了该任务。当然，并非所有这些问题都是第一次发表。
本期问题的解决方案应在 1991 年 5 月 15 日之前发送至地址：103006，Moscow K-6，st.高尔基，32/1，«Kvant»。
将不同期刊或不同学科（数学和物理）问题的解决方案放在不同的信封中发送。在信封的“收件人”栏中写下：“问题 «Kvant» No. 3 - 91”以及您要发送其解决方案的问题编号，例如“M1271”或“F1278”。
在“...发件人地址”栏中，请分别填写您的名字和姓氏。附上一个写有您地址的信封（您将在这个信封中收到决定审核的结果）。
请将拟发表的每个原始问题的条件连同您对该问题的解决方案一式两份装在一个单独的信封中发送（在信封上标记：“问题«Kvant»，物理新问题”或“...数学新问题”）。
请在每封信的开头注明您将就读的学校编号和班级。
