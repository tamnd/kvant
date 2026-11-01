---
id: 1977-3-rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b
issue: kvant_1977_3
year: 1977
number: "3"
title: '[回答读者S. Kirzhalov关于求解无理方程的问题]'
authors:
  - Розов Н. Х.
rubric: raznoe
page_first: 58
page_last: 59
page_labels: 56-57
tag: H0M1
lang: zh
source: kvant_digital
extraction: vision
content_sha256: cc087b2e6f63f29660ce64847fc69de3bc40ea667bdc082aa6febb25a14f4164
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/19_rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b.md
source_content_sha256: de5302fa57fda7c02ca1f98b1d30e661f3138133afbf629ddfccd55a041ac217
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

提问 - 我们回答

编辑收到了一封来自哈尔科夫市的九年级学生斯捷潘·基尔扎洛夫(Stepan Kirzhalov)的来信。这是他写的。

“在《初等数学手册》（基辅，1973 年）中，我遇到了解决无理方程的任何方法
$$\sqrt[3]{8x+4} - \sqrt[3]{8x-4} = 2.$$ (*)

每当我们将这个方程的各个部分放入一个立方体时，我们就会得到 $(8x+4)$ -
$$-3\sqrt[3]{8x+4}\sqrt[3]{8x-4} \times (\sqrt[3]{8x+4} - \sqrt[3]{8x-4}) - (8x-4) = 8.$$

考虑到根据条件方括号中的表达式必须等于2，我们可以写
$$-6\sqrt[3]{64x^2-16} = 0,$$
从那里$x_1=1/2$，$x_2=-1/2$。我还尝试解其他方程
$$\sqrt[3]{2x-1} + \sqrt[3]{x-1} = 1,$$ (**)

但事实证明，在两个结果值$x_1=1$、$x_2=0$中，只有第一个满足方程。怎么了？

由于许多其他读者可能会对 Stepan Kirzhalov 的信的回复感兴趣«Kvant»，因此我们在杂志页面上发布了此回复。

首先，我们提醒读者，在数学文献中，符号 $\sqrt[3]{a}$ 有两种含义（参见“代数 8”，M.，“Prosveshchenie”，1975 年，第 95 页）。

首先，符号$\sqrt[3]{a}$表示一个非负数，其立方为$a$；那么这个符号定义为任何$a$。在 S. Kirzhalov 的 G. P. Bevz、P. F. Filchakov、K. I. Shvetsov、F. P. Yaremchuk 的信中提到的书《建设大学的基础数学手册》（基辅，“Naukova Dumka”，1973 年，第 152-153 页）中，符号 $\sqrt[3]{a}$ 就是在这个意义上使用的，因此，例如， $x=-1/2$ 处的表达式 $\sqrt[3]{8x-4}$ 存在并且等于 -2。

这封信的作者所写的求解三次根式无理方程的方法是经常使用的。前面提到的《参考书》中也提到了这一点，但不幸的是，那里并没有指出，用极大法求解方程时，我们可能会得到外根，因此我们总是需要检查。

验证这一点并不难。我们现在正在进行相应的推理，特别是因为它们非常令人尊敬，并且展示了如何具体研究方程等价性问题并阐明其违反的原因。让我们首先介绍一种代数方法：

$$a^3+b^3+c^3-3abc = \frac{1}{2}(a+b+c)[(a-b)^2+(b-c)^2+(c-a)^2];$$

为了证明这一点，只需打开右侧的括号即可。

考虑方程

$$\sqrt[3]{f(x)} + \sqrt[3]{g(x)} = \varphi(x)$$

我们假设 $x_0$ 是它的根，所以

⟦folio 57⟧

$$\sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0).$$

将正确的数值等式（3）两边都化为立方体并继续变换，可得：

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \left[ \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} \right] + g(x_0) = \varphi^3(x_0).$$

如果我们再次使用正确的数值等式 (3)，我们得到等式

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \varphi(x_0) + g(x_0) = \varphi^3(x_0),$$

这表明 $x_0$ 是方程的根

$$f(x) + 3\sqrt[3]{f(x)} \sqrt[3]{g(x)} \varphi(x) + g(x) = \varphi^3(x).$$

因此，方程(2)的每个根都是方程(5)的根。

现在让我们考虑方程（5）并假设$x_0$是它的根，因此数值等式（4）成立。应用恒等式 (1) 与

$$a = \sqrt[3]{f(x_0)}, b = \sqrt[3]{g(x_0)}, c = -\varphi(x_0),$$

我们将等式（4）重写为以下形式

$$\frac{1}{2} \left( \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0) \right) \times \left| \left( \sqrt[3]{f(x_0)} - \sqrt[3]{g(x_0)} \right)^2 + \left( \sqrt[3]{f(x_0)} + \varphi(x_0) \right)^2 + \left( \sqrt[3]{g(x_0)} + \varphi(x_0) \right)^2 \right| = 0.$$

由等式(6)可知，数$x_0$要么满足等式(3)，即是等式(2)的根，要么满足等式

$$\sqrt[3]{f(x_0)} = \sqrt[3]{g(x_0)} = -\varphi(x_0),$$

也就是说，它是方程组的一个解

$$\begin{cases} f(x) = -\varphi^3(x), \\ g(x) = -\varphi^3(x). \end{cases}$$

因此，方程(5)的根可能不是方程(2)的根。容易验证式(5)的根$x_0$是为式(2)构造的当且仅当条件

$$\begin{cases} \varphi(x_0) \neq 0, \\ f(x_0) = g(x_0) = -\varphi^3(x_0). \end{cases}$$

信件作者找到的值$x = 0$满足这些条件，因此将成为方程（**）的构造根。

总之，我们再次注意到，从新学校课程的角度来看，值$x = -1/2$不是等式（*）的根，因为在这种情况下，等式（*）左边的值没有定义。

H·罗佐夫
