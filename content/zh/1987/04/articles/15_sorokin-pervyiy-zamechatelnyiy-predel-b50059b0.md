---
id: 1987-4-sorokin-pervyiy-zamechatelnyiy-predel-b50059b0
issue: kvant_1987_4
year: 1987
number: "4"
title: 第一个精彩极限
authors:
  - Сорокин Г. А.
rubric: shkola-v-kvante
page_first: 42
page_last: 42
page_labels: "40"
tag: 58DG
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 175756adffa5e9db22aaa3c0ef0b4b2854658d79eec8059ab516a1c502357942
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/15_sorokin-pervyiy-zamechatelnyiy-predel-b50059b0.md
source_content_sha256: 6f801eea87eef9f6e371820e3144486de0628b10acc6148a7672ce6941968341
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

不；例如，11 934:51=234（证明一下！）。

要获得能被$m=10n-1$整除的符号，需要将B中的减法改为加法，将D和D中的0写成$m$，将10$n+1$写成10$n-1$。

例子

$$N = 9246, m = 69$$

（这里操作B是操作C的修改）。

这意味着 9246 可以被 69 整除。弄清楚如何读取这一行中的商 9246:69。

最后，让我们注意，如果我们在双数系统中写数字，那么我们的任何规则都会给出可被任何奇数整除的符号（在双数系统中可被 2 整除的符号是不言而喻的）。

V·G·斯托利亚尔

第一个精彩极限

在教科书《代数与分析入门 9-10》（莫斯科：Prosveshcheniye，1986）第 20 段（第 94 页）中，证明了关于任意正弦的定理：正弦函数在任何点都是任意的且$(\sin x)'=\cos x$。在这个公式的证明中，利用当$\Delta x$趋于0时，比率$\frac{\sin \frac{\Delta x}{2}}{\Delta x}$趋于1：

$$\frac{\sin \frac{\Delta x}{2}}{\Delta x} \rightarrow 1$$ $\Delta x \rightarrow 0$。

换句话说，使用关于$\frac{\sin x}{x}$在$x \rightarrow 0$处的极限的定理：

$$\lim_{x \rightarrow 0} \frac{\sin x}{x} = 1.$$

数学家将此极限称为第一个显着极限。

在这篇笔记中，我们将证明关于$(\sin x)/x$在$x \rightarrow 0$的极限的定理（在学校教科书中，相应的证明是基于几何清晰度，参见第95页）。在证明中，我们需要比“代数和分析原理 9-10”中给出的极限更正式的定义。 76. 也就是说，如果对于任何正 $\varepsilon$ 存在一个正 $\delta$，使得对于所有 $x$ 使得 $|x-a|<\delta$ 不等式 $|f(x)-L|<\varepsilon$ 成立，则函数 $f(x)$ 趋向于$x \rightarrow a$ ($x \neq a$) 处的极限 $L$。换句话说，如果对于任何 $\varepsilon>0$ 可以指定点 $a$ 的邻域，那么对于来自该邻域的所有 $x$ $x \neq a$，不等式 $|f(x)-L|<\varepsilon$ 将成立，则函数 $f(x)$ 趋向于 $x \rightarrow a$ 处的极限 $L$。 （自己想想极限的所有三个定义的等价性：我们的两个和学校教科书中给出的定义。）

那么，让我们继续证明定理。

我们首先假设$0<x<\frac{\pi}{2}$。让我们考虑具有中心 $O$ 的单个邻域，并将其与具有直线平面 $ABCD$ 的中心 $AFC$ 进行比较（参见 图）。

线段$AFC$的面积等于扇形$OAC$和三角形$OAC$的面积之差，即

$$S_{AFC} = \frac{1}{2} x - \frac{1}{2} \sin x > 0,$$

在哪里

$$\sin x < x.$$

现在我们来估计一下直线$ABCD$的面积。从$AD=\sin x$、$DC=1-\cos x$开始，

$$S_{ABCD} = \sin x (1-\cos x) = 2 \sin^2 \frac{x}{2} \cdot \sin x < 2 \cdot \frac{x^2}{4} \cdot x = \frac{x^3}{2}.$$
