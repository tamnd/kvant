---
id: 1971-1-skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7
issue: kvant_1971_1
year: 1971
number: "1"
title: 求解方程和方程组的代入法
authors:
  - Сканави М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 46
page_labels: 43-44
tag: BBD2
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 23a578f820ed5dede7d82f7214afdf2519c84b25c19792006dd1f08c61f6f263
prompt_sha256: draft-1
translated_from: content/ru/1971/01/articles/09_skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7.md
source_content_sha256: 96c1e59d5fb3ed66aa52d2ece5c165bfc82e9b02f609aa82ebdb6b09b882574d
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

不包含二次部首！）：我们来补一下左边部首的十进位表达式之间的差，得到$(t+3) - t=3$。

现在让我们对这个差值进行因式分解（使用平方差公式）并找到 $(\sqrt{t+3} + \sqrt{t})(\sqrt{t+3} - \sqrt{t}) = 3$。

从这里开始，除以原始方程（相对于 $t$），我们得到

$$\sqrt{t+3} - \sqrt{t} = \frac{3}{\sqrt{2t+7}}.$$

从原来的方程中减去我们现在得到的，我们发现

$$2\sqrt{t} = \sqrt{2t+7} - \frac{3}{\sqrt{2t+7}},$$

$$2\sqrt{t} = \frac{2t+4}{\sqrt{2t+7}}, \sqrt{t} = \frac{t+2}{\sqrt{2t+7}}.$$

我们刚刚执行的过程允许我们通过简单地对方程各部分进行平方来消除根式。让我们这样做：

$$t = \frac{t^2+4t+4}{2t+7}, t^2+3t-4=0.$$

因此$t_1=1, t_2=-4$。接下来，请注意，我们只对 $t$ 的正值感兴趣，因为 $t = x^2+x+1 > 0$

对于$x$的所有值。因此，我们丢弃不合适的根$t_2$并得到一个用于求$x$的二次方程

$$x^2+x+1=1, \quad x^2+x=0$$

有根 $x_1=-1$ 和 $x_2=0$。很容易验证它们都是这个无理方程的根。

示例 5. 求解方程组

$$\begin{cases} \frac{x^3}{y} + xy = 40, \\ \frac{y^3}{x} + xy = 10. \end{cases}$$

（限制自己寻找真正的解决方案）。

求解方程组学生练习一个重要的解决方案。同时，在这些情况下，它往往非常有效。在解决所提出的系统之前，我将允许自己表达一些有关在求解两个方程组（有两个例外）时的替换方法的一般信息。如果后者由字母 $x$ 和 $y$ 指定，那么根据以下等式转向新数量 $\rho$ 和 $\varphi$ 通常很有用：

$$x = \rho \cos \varphi,$$

$$y = \rho \sin \varphi.$$

对平面坐标法足够熟悉的读者，几乎可以认为，如果$x$和$y$作为某个点的笛卡尔坐标，那么$\rho$和$\varphi$就是同一点的所谓极坐标。极坐标的几何意义及其与笛卡尔坐标的联系从图就会变得清晰起来，建议大家仔细考虑：

⟦folio 44⟧

我们注意到原点$O$有$\rho=0$，而角度$\varphi$没有定义值。如果我们要求有的话，平面上的所有其他点都将服从一对极坐标（$\rho, \varphi$）

$$0 \leqslant \rho < +\infty,$$
$$0 \leqslant \varphi < 2\pi.$$

我们使用等式（！）来求解这个方程组，而不是 $x$ 和 $y$ 在系统方程的域中，我们将它们的表达式替换为 $\rho$ 和 $\varphi$;我们明白了

$$\begin{cases} \frac{\rho^3 \cos^3 \varphi}{\rho \sin \varphi} + \rho \cos \varphi \rho \sin \varphi = 40, \\ \frac{\rho^3 \sin^3 \varphi}{\rho \cos \varphi} + \rho \cos \varphi \rho \sin \varphi = 10. \end{cases}$$

或处理后

$$\begin{cases} \rho^2 \text{ctg} \varphi = 40, \\ \rho^2 \text{tg} \varphi = 10. \end{cases}$$

将第一个方程除以第二个方程我们发现

$$\text{ctg}^2 \varphi = 4.$$

因此$\text{ctg} \varphi = 2$或$\text{ctg} \varphi = -2$。第二个（负）值 $\text{ctg} \varphi$ 立即被丢弃，因为我们有 $\text{ctg} \varphi$ 和 $\rho^2$ 具有相同的符号，并且 $\rho^2$ 不能为负数。现在，使用已知的余切，我们需要找到角度 $\varphi$ 的正弦和余弦。我不言而喻地遵循这一点：

$$\cos^2 \varphi = 1 + \text{ctg}^2 \varphi = 5,$$
$$\cos \varphi = \sqrt{5},$$
$$\cos \varphi = -\sqrt{5},$$

$$\sin \varphi = \frac{1}{\sqrt{5}}, \quad \sin \varphi = -\frac{1}{\sqrt{5}},$$
$$\cos \varphi = \frac{2}{\sqrt{5}}, \quad \cos \varphi = -\frac{2}{\sqrt{5}}.$$

接下来我们找到$\rho$，因为

$$\rho^2 \text{ctg} \varphi = \rho^2 \cdot 2 = 40, \quad \rho^2 = 20.$$

我们得到$\rho = 2\sqrt{5}$。使用等式（！）使用已知的$\rho$和$\varphi$，我们找到以下两对数字作为该方程组的解：

$$x_1 = 2\sqrt{5} \cdot \frac{2}{\sqrt{5}} = 4,$$
$$y_1 = 2\sqrt{5} \cdot \frac{1}{\sqrt{5}} = 2;$$
$$x_2 = 2\sqrt{5} \left(-\frac{2}{\sqrt{5}}\right) = -4,$$
$$y_2 = 2\sqrt{5} \left(-\frac{1}{\sqrt{5}}\right) = -2.$$

假设这个方程组只能通过传递到极坐标来求解是不正确的（例如，也可以这样求解：将$xy$从方程左侧转移到右侧，然后重新组合结果，得到$xy$的二次方程；其余的很明显）。同时，应采用该技术。从某种意义上说，它允许我们调节我们的变换，并使使用整个三角学装置成为可能。在什么情况下使用该技术是有益的，在什么情况下则没有？您的经验有助于回答这个问题，您可以通过自己的工作来丰富这个问题！

趁着距离高考还有一段时间，行动起来吧！
