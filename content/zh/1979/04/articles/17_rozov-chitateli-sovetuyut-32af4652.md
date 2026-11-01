---
id: 1979-4-rozov-chitateli-sovetuyut-32af4652
issue: kvant_1979_4
year: 1979
number: "4"
title: 读者指教
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48, 49, 51
tag: EWFA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d7ebe84e73b51a589be0e7e736646984a8dfc26315609a85df27d5ee0cb01907
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/17_rozov-chitateli-sovetuyut-32af4652.md
source_content_sha256: 4b41d528d1684c03336edf6a58375374e881a9d633f5fc61a717da360422ed7e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

读者建议

在一般社论邮件«Kvant»中，我们的读者（学生、教师、数学爱好者）来信的很大一部分涉及“申请人实践”部分的主题。其中许多涉及局部问题；编辑会亲自回复作者的此类信件。但在一系列的信件和笔记中，对学校数学课程中的各种理论问题表达了有趣的信息，概述了某些类型考试问题的想法，传达了有用的评论、方法建议以及独立撰写的问题。尽管此类信件中给出的信息和任务并不总是新颖且原创的，但我们认为，建议向所有读者«Kvant»介绍其内容。由于考虑到不可能完整发表这些信件和注释，编辑们根据杂志读者的想法和建议编写了一些材料，并附有必要的补充评论。我们希望该集中包含的问题能够对大学申请者有所帮助。

申请人必须在入学考试中证明学校数学课程的流利程度，特别是指能够正确进行计算和正确转换代数表达式的能力。不幸的是，申请者的成绩往往会因为转换过程中犯的错误而被降低。一般来说，此类错误的发生并不是因为无关紧要，而是由于疏忽和疏忽、无法自我检查、在解决反映技术培训的示例时练习不足的结果（参见«Kvant»，1974年，第3期，第49-50页）。该方法的实质是用某个辅助角的三角函数代替代数表达式中包含的变量之一，并选择它，从而借助众所周知的三角函数公式来简化原始表达式。

当然，三角函数训练不仅对于转换代数表达式有用，而且在许多问题中都很有用——求解方程、证明不等式等。我们的读者 V. Olkhov（高尔基）发送了一大堆此类有趣的例子。

示例 1. 证明圣诞节

$$\sqrt{a + \sqrt{b}} = \sqrt{\frac{a + \sqrt{a^2 - b}}{2}} + \sqrt{\frac{a - \sqrt{a^2 - b}}{2}}.$$ (1)

首先，我们注意到等式 (1) 的两边同时有意义，如果

$$b \geq 0, a \geq 0, a \geq \sqrt{b};$$ (2)

对于这些值$a$和$b$我们将证明我们的身份。平方根下存在表达式 $a^2 - b$ 暗示了将

$$b = a^2\sin^2\varphi, \text{ где } 0 \leq \varphi \leq \pi/2,$$ (3) - 因为那时

$$\sqrt{a^2 - b} = a\cos\varphi.$$

这种三角准备是可以接受的，因为由于不等式 (2)，分数 $b/a^2$（$a \neq 0$）位于 0 和 1 之间，并且可以将其视为第一个四分之一角的正弦平方值

⟦folio 49⟧

（如果$a=0$，则$b=0$和恒等式（1）非常具体）。

将(3)代入定律后，等式(1)的部分将写成以下形式

$$\sqrt{a} \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right).$$

同时

$$\sqrt{a + \sqrt{b}} = \sqrt{a + a \sin \varphi} = \sqrt{a} \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right),$$

从 $1 + \sin \varphi = \cos^2 \frac{\varphi}{2} + 2 \cos \frac{\varphi}{2} \sin \frac{\varphi}{2} + \sin^2 \frac{\varphi}{2} = \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right)^2$ 开始，恒等式 (1) 被证明。

示例 2. 证明对于 $c > 0, a > c, b > c$

$$\sqrt{(a + c)(b + c)} + \sqrt{(a - c)(b - c)} \leq 2 \sqrt{ab}.$$

这个不等式中的等号是如何实现的？

让我们将证明的不等式重写为以下形式

$$\sqrt{\left( 1 + \frac{c}{a} \right)\left( 1 + \frac{c}{b} \right)} + \sqrt{\left( 1 - \frac{c}{a} \right)\left( 1 - \frac{c}{b} \right)} \leq 2.$$ (4)

由于按条件

$$0 < \frac{c}{a} < 1, \quad 0 < \frac{c}{b} < 1,$$

可以放

$$\frac{c}{a} = \cos \alpha, \quad 0 < \alpha < \pi/2,$$

$$\frac{c}{b} = \cos \beta, \quad 0 < \beta < \pi/2.$$

如果我们在不等式（4）的左边进行三角代入，那么我们可以得出：

$$\sqrt{(1 + \cos \alpha)(1 + \cos \beta)} + \sqrt{(1 - \cos \alpha)(1 - \cos \beta)} = 2 \left( \cos \frac{\alpha}{2} \cos \frac{\beta}{2} + \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \right) = 2 \cos \left( \frac{\alpha}{2} - \frac{\beta}{2} \right) \leq 2,$$

这就证明了不等式（4）。

从上面的转换链可以清楚地看出，当

$$\cos \left( \frac{\alpha}{2} - \frac{\beta}{2} \right) = 1,$$

即在$\alpha = \beta$；这只能通过 $a = b$ 实现（请自行检查！）。

以下带参数的无理方程可以通过标准方法 - 求幂轻松求解；你只需要小心不要扎根。我们将展示如何以不同的方式求解该方程 - 使用三角代换。

示例 3：求解方程

$$\sqrt{p + x} + \sqrt{p - x} = x.$$ (5)

首先我们要注意，如果方程（5）对于参数$p$的某个值有一个根，那么这个根是一个非负数（为什么？）。由此可见，对于$p < 0$方程（5）没有根，对于$p = 0$它有一个根$x = 0$，对于$p > 0$，根必须满足不等式$0 < x \leq p$（证明这些陈述）。

让我们进行三角代换

$$x = p \cos \psi, \quad 0 \leq \psi < \frac{\pi}{2};$$

那么方程（5）将采用以下形式

$$\sqrt{1 + \cos \psi} + \sqrt{1 - \cos \psi} = \sqrt{p} \cos \psi,$$

或者

$$\sqrt{2} = \sqrt{p} \left( \cos \frac{\psi}{2} - \sin \frac{\psi}{2} \right)$$

（进行计算）。通过对最后一个方程两边进行平方，我们得到

$$\sin \psi = \frac{p - 2}{p}.$$

从这里我们确定，只有当$p \geq 2$时，才可以在第一季度选择值$\psi$；因此，方程（5）仅对参数$p \geq 2$的值有根。对于满足此条件的任何参数值，

⟦folio 51⟧

穿着

$$\sin \varphi = \frac{b}{\sqrt{a^2 + b^2}}, \cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}$$

（«Kvant»，1976 年，第 4 期，第 41-42 页）。

M. Shkalenyuk（敖德萨）在他的信中指出了公式（7）的一个有趣的概括。让我们通过一个具体问题来证明这一概括。

示例 5（密歇根州立大学，力学和数学，1965 年）。方程有多少个根？

$$\sin x + 2 \sin 2x = 3 + \sin 3x?$$

使用众所周知的三角函数公式，我们将所提出的方程重写为以下形式

$$\sin 2x - \sin x \cos 2x = \frac{3}{2}.$$

(8)

现在我们将左侧部分变换如下：

$$\sin 2x - \sin x \cos 2x =$$

$$= \sqrt{1 + \sin^2 x} \left[ \frac{1}{\sqrt{1 + \sin^2 x}} \sin 2x - \frac{\sin x}{\sqrt{1 + \sin^2 x}} \cos 2x \right].$$

因为对于任意 $x$

$$\left( \frac{1}{\sqrt{1 + \sin^2 x}} \right)^2 + \left( -\frac{\sin x}{\sqrt{1 + \sin^2 x}} \right)^2 = 1,$$

存在一个角度 $\varphi = \varphi(x)$ 取决于 $x$，使得

$$\frac{1}{\sqrt{1 + \sin^2 x}} = \cos \varphi(x),$$

$$- \frac{\sin x}{\sqrt{1 + \sin^2 x}} = \sin \varphi(x).$$

没有然后

$$\sin 2x - \sin x \cos 2x =$$

$$= \sqrt{1 + \sin^2 x} \sin (2x + \varphi(x)),$$

所以方程(8)等价于方程

$$\sqrt{1 + \sin^2 x} \sin (2x + \varphi(x)) = \frac{3}{2}.$$

由于最后一个方程的左边对于$x$的所有值都不超过$\sqrt{2}$，所以这个方程没有根。

* * *

我们的读者 V. Kolmykov（沃罗涅日）建议在以下明显不正确的“定理”的“证明”中找到错误：

10. 定理。如果两个平面平行，则它们重合。

证明。让

$$ax + by + cz + d = 0$$

是平面 $\alpha$ 的方程，并且

$$Ax + By + Cz + D = 0$$

是平面$\beta$的方程，令$\alpha \parallel \beta$。由于这些平面的平行度

$$\frac{A}{a} = \frac{B}{b} = \frac{C}{c},$$

或者，如果他用 $k$、$A = ka$、$B = kb$、$C = kc$ 表示这些关系。

否，那么平面 $\beta$ 的方程可以写为

$$ax + by + cz + d = 0.$$

将式(10)减去式(9)，得到$D = kd$，因此平面$\beta$的式(10)可以改写为

$$ax + by + cz + d = 0.$$

由于该方程与$\alpha$平面的方程(9)一致，因此我们得到$\alpha = \beta$。
