---
id: 1978-5-vilenkin-proizvodnaya-i-kasatelnyie-70711ecf
issue: kvant_1978_5
year: 1978
number: "5"
title: 导数和切线
authors:
  - Виленкин А. Н.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 48
page_labels: 44-46
tag: JL9J
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 01a5e69c052f0c9e03bc5ad5faff33f1e1f20c674c5c35286b312677fd363533
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/14_vilenkin-proizvodnaya-i-kasatelnyie-70711ecf.md
source_content_sha256: bff1bc0d014a4dbb62f6296d709e44730740714a576066762f93470ea64e966a
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

A·维伦金

导数和切线

尽管在学校数学课程中，只有一段专门讨论函数图的切线（参见“代数与分析的开端”，九年级，第 52 段），但在 1977 年的大学入学考试（“A”计划）中，提出了许多与该主题相关的问题。大多数问题的解决方案基于使用方程
$$y = f'(x_0) \cdot x + (f(x_0) - f'(x_0)) \cdot x_0$$
 与函数 $y = f(x)$ 的图像在横坐标 $x_0$ (图 1) 处相切。更有趣的问题基于以下事实：切线的角度系数$k$一方面等于切线与横坐标轴之间的角度$\varphi$的正切，另一方面等于任意$f'(x_0)$的值。让我们考虑一些类型的此类问题*)。

求正切方程

示例 1（MEIS，1977）。函数$f(x) = 4 - x^2$图在$f = 0$交点处的国家方程，因此要找到$x_0$，必须求解方程$4 - x_0^2 = 0$。然后，对于$x_0$的每个值，都可以用标准方式写出正切方程。让我们这样做，考虑到$f'(x) = -2x$。

a）$x_0 = 2$； $f(2) = 0$、$f'(2) = -4$、正切方程$y = -4x + 8$；
b）$x_0 = -2$； $f(-2) = 0$，$f'(-2) = 4$，正切方程$y = 4x + 8$。

求 k 和角点

示例 2（MISI，1977）。每个样本的 x 轴与抛物线 $y = x^2 - 4x - 17$ 相切，在尿液中进行测试，x 轴$x_0 = 2,5$？

这里，直线与$Ox$轴的夹角是指$Ox$轴逆时针方向与该直线不存在的角度值（参见《代数6》第52段、《几何8》第98段和《代数与分析入门》10年级复习材料第8段）。由于给定了$f$和$x_0$，我们可以找到$k = f'(x_0)$，并从中得到所需的角度$\varphi$，因为直线与轴$Ox$形成的角度的正切等于该直线的角度系数：$tg\varphi = k$，以及在$k \geq 0$处的$\varphi = \arctg k$和$\varphi = \pi + \arctg k$ $k < 0$ (图 2)。

在此示例中，$f'(x) = 2x - 4$、$k = f'(2,5) = 1$、$tg\varphi = 1$、$\varphi = \pi/4$。

例 3. 方程的名称与函数 $f(x) = x^3 - 4x^2 + 3x + 1$ 的图形相切，在尿液中测试，横坐标为 $0$ 和 $1$。

这里筛子不是关于一条直线与轴$Ox$的夹角，而是关于两条直线的夹角。因此，我们回想一下，两条相交线的方程称为该线所确定的角度中较小者的值（参见“几何9”，第24节），即两条线之间的角度$\alpha$总是在$0 \leq \alpha \leq \pi/2$之内。

在此示例中，$f'(x) = 3x^2 - 8x + 3$，对于第一个切线，我们有 $x_0 = 0$、$f(0) = 1$、$f'(0) = 3$、$k_1 = tg\varphi_1 = 3$、$\varphi_1 = \arctg 3$，正切方程为 $y = 3x + 1$，对于第二个$x_0 = 1$、$f(1) = 1$、$f'(1) = -2$， $k_2 = tg\varphi_2 = -2$、$\varphi_2 = \pi - \arctg 2$、正切方程$y = -2x + 3$。然后，通过近似图（图3），很容易找到角度$\alpha = \pi - \arctg 2 - \arctg 3$。

⟦folio 45⟧

No, it's not clear what you're asking for. It looks like a list of equations or formulas.
让我们重读第一行：“但是这个角度是所需的角度吗？也就是说，$\alpha \leq \pi/2$是真的，还是应该有一个$\pi - \alpha$？看起来角度$\alpha$是所需的角度（因为arctg $2 > \pi/4$和arctg $3 > \pi/4$），但我们现在会采取不同的行动。”
第二行：“让我们推导出直线之间角度的一般公式 $y = k_1x + b_1$ 和 $y = k_2x + b_2$。首先，我们注意到，在平行平移过程中，角度不会改变，因此所需的角度 $\alpha$ 等于线之间的角度 $y = k_1x$ 和 $y = k_2x$ （它们是通过传输从数据中获得的 $\overrightarrow{CO}$）。让这些线和轴之间的角度 $Ox$ 平等的 $\varphi_1$ 和 $\varphi_2$ (图 4).然后很容易找到给定直线上的一个侧角的大小： $|\varphi_2 - \varphi_1|$ （必须放置模型标志，因为我们不知道哪个角落 $\varphi_2$, $\varphi_1$ 更多的）。所需的角度是其中一个角度 $|\varphi_2 - \varphi_1|$, $\pi - |\varphi_2 - \varphi_1|$，不超过 $\pi/2$."
第三行：“事实证明，取这些角度的正切是很方便的，因为根据简化公式”
第四行：“tg ($\pi - |\varphi_2 - \varphi_1|$) = -tg|$\varphi_2 - \varphi_1$| (if $|\varphi_2 - \varphi_1| \neq \pi/2$) and if $|\varphi_2 - \varphi_1| > \pi/2$, then”
The fifth line: "tg $\alpha =$ tg ($\pi - |\varphi_2 - \varphi_1|$) ="
The sixth line: "= -tg|$\varphi_2 - \varphi_1$| = |tg|$\varphi_2 - \varphi_1$| |="
The seventh line: "= |tg($\varphi_2 - \varphi_1$)|"
第八行：“（因为 tg 是奇函数）；如果 $|\varphi_2 - \varphi_1| < \pi/2$，则”
第九行：“tg $\alpha =$ tg|$\varphi_2 - \varphi_1$|，也等于|tg($\varphi_2 - \varphi_1$)|。”
第十行：“因此，公式 tg $\alpha$ = |tg($\varphi_2 - \varphi_1$)| 在所有情况下都是正确的。回想一下两个角度差的正切公式，我们得到：”
The eleventh line: "tg $\alpha$ = |$\frac{k_2 - k_1}{1 + k_2k_1}$|."
第十二行：“请注意，两条直线的过度分布也很容易通过其角度系数来检测：如果 $|\varphi_2 - \varphi_1| = \pi/2$，则 $\varphi_2 = \varphi_1 + \pi/2$ 或 $\varphi_2 = \varphi_1 - \pi/2$，并且在这两种情况下 tg $\varphi_2 = -$ tg $\varphi_1 = -\frac{1}{tg\varphi_1}$”
第十三行：“（如果定义了这些表达式），即 tg $\varphi_2 \cdot$ tg $\varphi_1 = -1$，且以斜率表示”
The fourteenth line: "$k_2k_1 = -1$."
第十五行：“这与公式中的内容一致”
第十六行：“方程与公式中的内容”

Picture 1:
$$\begin{align*}
y &= f(x) \\
M_0(x_0, f(x_0))
\end{align*}$$

Picture 2:
$$k > 0, \varphi = \arctg k; k < 0, \varphi = \pi + \arctg k.$$

Picture 3:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

Picture 4:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

⟦folio 46⟧

tg α 如果 $k_1 k_2 + 1 = 0$，则右侧部分未定义。

还有另一种情况是两条直线垂直 - 如果这些直线的方程具有 $y = b$, $x = a$ 的形式。在这种情况下，$k_1 = 0$和$k_2$不存在，因为直线$x = a$平行于纵轴。

在示例 3 中我们得到：

$$\text{tg} \alpha = \left| \frac{-2 - 3}{1 - 6} \right| = 1, \quad \alpha = \frac{\pi}{4}.$$

将此答案与上面的答案进行比较！

沿切线确定图点

在某些问题中，切线的某些条件以一种或另一种形式给出，并要求找到切点。

例4.函数$f(x) = 3x^3 - 4x^2 + 1$在图上的名称是幂，其中的切线由轴Ox以及$\pi/4$形成。

要使切线与Ox轴的夹角等于$\pi/4$，则切线的角度系数等于1是充分必要的。但是$k = f'(x_0)$，这意味着我们需要求解方程$f'(x_0) = 1$，即$9x_0^2 - 8x_0 = 1$。由此，使用二次方程 $x_0 = 1$ 或 $x_0 = -1/9$ 的根公式。在这些点$f(1) = 0$，$f(-1/9) = 230/243$。这意味着有两个必需点：$M_1(-1/9; 230/243)$和$M_2(1; 0)$，这在该函数的图形上很好（图 5）。

示例 5. 函数 $f(x) = x^2$ 的图像在什么点处相切

a) 平行于直线$2x - y + 1 = 0$；

b) 垂直于同一条线？

a) 众所周知（参见“代数 6”，第 52 段），如果角度系数相等，则两条线平行。这条线的方程可以写成$y = 2x + 1$的形式，这表明$k = 2$。对于切线$k = f'(x_0)$，所以我们需要解方程$f'(x_0) = 2$，即$2x_0 = 2$，因此$x_0 = 1$。这意味着必须在点 $M_1(1; 1)$ (图 6) 处绘制切线。经检验，该切线方程为$y = 2x - 1$。

6) 让我们使用这样的事实：如果 $k_1 k_2 = -1$，线 $y = k_1 x + b_1$ 和 $y = k_2 x + b_2$ 是垂直的。在这个例子中，$k_1 = 2$，因此$k_2 = -1/k_1 = -1/2$，并且从方程$2x_0 = -1/2$我们找到$x_0 = -1/4$。这对应于点$M_2(-1/4; 1/16)$，切线方程为$y = -1/2 x - 1/16$。这个例子的“几何”在 图 6 中清晰可见。

示例 6（密歇根州立大学心理学系，1977 年）。在函数 $\frac{1}{3} x^3 - 2x^2 - 22x - 28$ 的图形上，找到所有点，使得图形在这些点处的切线与正半轴相交，并从它们中切掉相等长度的线段。

让切线在点 $M_0(x_0; f(x_0))$ 处绘制。那么它的方程的形式为

$$y = \left(x_0^2 - 4x_0 - 22\right) \cdot x - \frac{2}{3} x_0^3 + 2x_0^2 - 28.$$

没有直线 $y = kx + b$ 与正半轴相交，仅在 $k = -1$ 和 $b > 0$ 处截断相等长度的线段（b≠ 0，因为
