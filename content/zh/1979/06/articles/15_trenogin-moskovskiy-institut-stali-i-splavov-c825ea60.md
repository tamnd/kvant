---
id: 1979-6-trenogin-moskovskiy-institut-stali-i-splavov-c825ea60
issue: kvant_1979_6
year: 1979
number: "6"
title: 莫斯科钢铁及合金研究所
authors:
  - Треногин В. А.
rubric: ekzamenatsionnye-materialy
page_first: 41
page_last: 42
page_labels: 39-40
tag: ZL05
lang: zh
source: kvant_digital
extraction: vision
content_sha256: fe2ba2d7a91dbd5e86e945f535fdddb2ea39184d3f0ee0060efafc2d09cc91c7
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/15_trenogin-moskovskiy-institut-stali-i-splavov-c825ea60.md
source_content_sha256: e3e5424055d3575a4517a026bbcbcdaeccad713737b2da170077649f324e18e1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

选项
入学考试
1978年挑战

莫斯科学院
钢和合金

1979年«Kvant»，第5期，物理入学考试版本出版。下面我们公布了1978年数学入学考试（笔试）选项。除了选项、解决方案和答案外，这里还对其中一个选项进行了详细分析，指出了小学生的典型错误。

数学

1978年，MISIS在新课程下第二年进行了数学入学考试。我们今年的申请者价值观并没有像我们预期的那样稳定，而是被迫注意到他们的准备程度没有明显改善，甚至略有下降。这尤其适用于学校课程中专门讨论微分和整合的部分。几何问题尤其严重：几乎没有人有能力应用矢量代数来解决几何问题。

按照选择难度由大到小的顺序，MISIS的院系大致可以排列如下：工程学院、黑色金属及合金冶金学院、有色及稀有金属及合金冶金学院、半导体材料与器件学院、物理与化学学院。

半导体材料学院

1. 求函数的定义域

$$y = \sqrt{\log_{0.5}(3x - 8) - \log_{0.5}(x^2 + 4)}$$

该任务包括解决不平等系统。许多申请人无法正确获得这个不等式系统，因为 Plyugo 缺乏线性和对数函数的知识。不平等系统的形式为

$$\begin{cases} 3x - 8 > 0 \\ \frac{3x - 8}{x^2 + 4} \leq 1 \end{cases} \Rightarrow \begin{cases} 3x - 8 > 0 \\ x^2 - 3x + 12 \geq 0. \end{cases}$$

一些申请者无法正确地解决这个系统，尽管第二个不等式对于所有$x \in \mathbb{R}$都满足，这一事实立即得出答案：$x > \frac{8}{3}$。

2. 求解三角方程

$$\frac{1}{1 + \text{ctg}x} + \frac{1}{\sqrt{2}} \cos \left(x - \frac{\pi}{4}\right) = \frac{1 - \text{ctg}x}{2(1 + \text{ctg}x)}$$

这里的典型错误如下： 例如，三角测量学的基本公式毫无意义

$$\cos \left(x - \frac{\pi}{4}\right) = \cos x \cdot \cos \frac{\pi}{4} + \sin x \cdot \sin \frac{\pi}{4},$$

$$\text{ctg}x = \frac{\cos x}{\sin x};$$

获得已建立的根基。

该方程例如可以如下求解。

$$\sin x \neq 0, 1 + \text{ctg}x \neq 0 \Rightarrow x \neq -\frac{\pi}{4} + k\pi.$$

$k \in \mathbb{Z}$, $x \neq m\pi$, $m \in \mathbb{Z}$.

我们来变换一下方程

$$1 + \frac{1}{\sqrt{2}} \left(\cos x \cdot \frac{1}{\sqrt{2}} + \sin x \cdot \frac{1}{\sqrt{2}}\right) \times \left(1 + \frac{\cos x}{\sin x}\right) = \frac{1}{2} \left(1 - \frac{\cos x}{\sin x}\right) \Rightarrow (1 + \text{ctg}x) \left(\cos x + \sin x + 1\right) = 0.$$

1) $1 + \text{ctg}x = 0 \Rightarrow x = -\frac{\pi}{4} + k\pi$

不属于定义范围。

2) $\cos x + \sin x + 1 = 0 \Rightarrow \sin \left(x + \frac{\pi}{4}\right) = -\frac{\sqrt{2}}{2} \Rightarrow x + \frac{\pi}{4} = (-1)^{k+1} \frac{\pi}{4} + k\pi \Rightarrow x = \left[(-1)^{k+1} - 1\right] \frac{\pi}{4} + k\pi = \left(2\pi + 1\right) \pi, k = 2n + 1$

$-\frac{\pi}{2} + 2n\pi, k = 2n$

⟦folio 40⟧

$x = (2n + 1)\pi$ 超出范围。答案是$x = -\frac{\pi}{2} + 2n\pi, n \in \mathbb{Z}$。

3. 求曲线公切线的方程

$y = x^2 + 4x + 8$ 和 $y = x^2 + 8x + 4$。大多数没有解决这个问题的申请人都无法正确写出曲线的切线方程。解决以下问题：第一条和第二条曲线的切线方程

$$\begin{cases} y = f'(x_1)(x - x_1) + f(x_1), \\ y = g'(x_2)(x - x_2) + g(x_2). \end{cases}$$

公切线的条件是

$$\begin{cases} f'(x_1) = g'(x_2) \\ f(x_1) - f'(x_1) \cdot x_1 = g(x_2) - g'(x_2) \cdot x_2 \end{cases} \Rightarrow \begin{cases} 2x_1 + 4 = 2x_2 + 8 \\ -x_1^2 + 8 = -x_2^2 + 4 \end{cases} \Rightarrow \begin{cases} x_1 = 2 \\ x_2 = 0. \end{cases}$$

我们得到公切线方程

$y = 8x + 4$.

4. 求数列的极限

$x_n = \frac{1}{2 \cdot 3 \cdot 4 \cdot 5} + \frac{1}{3 \cdot 4 \cdot 5 \cdot 6} + \dots + \frac{1}{n(n+1)(n+2)(n+3)}$

$= \sum_{k=2}^{n} \frac{1}{k(k+1)(k+2)(k+3)}$.

一个典型的错误是：人们得出总和的最后一项趋于零的结论，并在此基础上决定极限等于第一项，或者前几项的总和，这取决于个人喜好。同时，他们忘记了总和中的项数随着$n$的增加而增加。您可以正确地解决问题，例如像这样。让我们将常用项 $\frac{1}{k(k+1)(k+2)(k+3)}$ 展开为简单分数之和，并将这些分数相加，如下所示：

$$x_n = \sum_{k=2}^{n} \left[ \frac{1}{6} \left( \frac{1}{k} - \frac{1}{k+3} \right) + \frac{1}{2} \left( \frac{1}{k+2} - \frac{1}{k+1} \right) \right] = \frac{1}{6} \left[ \left( \frac{1}{2} - \frac{1}{5} \right) + \left( \frac{1}{3} - \frac{1}{6} \right) + \left( \frac{1}{4} - \frac{1}{7} \right) + \left( \frac{1}{5} - \frac{1}{8} \right) + \dots + \left( \frac{1}{n} - \frac{1}{n+3} \right) \right] + \frac{1}{2} \left[ \left( \frac{1}{4} - \frac{1}{3} \right) + \left( \frac{1}{5} - \frac{1}{4} \right) + \dots + \left( \frac{1}{6} - \frac{1}{5} \right) \right] + \dots +$$

$$+ \left( \frac{1}{n+2} - \frac{1}{n+1} \right) = \frac{1}{6} \left( \frac{1}{2} + \frac{1}{3} + \frac{1}{4} \right) - \frac{1}{6} + \frac{1}{4} - \frac{1}{n+1} - \frac{1}{n+2} - \frac{1}{n+3} + \frac{1}{2} - \frac{1}{3} + \frac{1}{n+2} + \frac{1}{n+3}$$

从这里

$$\lim_{n \to \infty} x_n = \frac{1}{6} \left( \frac{1}{2} + \frac{1}{3} + \frac{1}{4} \right) - \frac{1}{6} + \lim_{n \to \infty} \left[ \frac{1}{2(n+2)} - \frac{1}{6} \left( \frac{1}{n+1} + \frac{1}{n+2} + \frac{1}{n+3} \right) \right] = \frac{1}{6} \left( \frac{1}{2} + \frac{1}{3} + \frac{1}{4} \right) + \frac{1}{4} - 1 + 0 = \frac{1}{72}$$

5. 点$A(1; 2; 3), B(1; 5; 3), C(3; 3; 3)$位于圆柱体下底圆上，点$D(2; 3; 7)$位于圆柱体上底圆上。求出底面中心的坐标和圆柱体的体积。

以立体测量法为例，大多数申请人都未能完成这项任务。例如，您可以提出以下解决方案：

1) 让我们求通过点$A, B$和$C$的平面方程（显然是通过下底的中心$O$）

$$ax + by + cz + d = 0.$$

为了确定$a, b, c$和$d$，我们得到一个系统（点$A, B, C$的坐标满足平面方程）。

2) 让$O(x; y; z)$。然后为了确定 $(x; y; z)$，我们有方程组

$$\begin{cases} z = 3 \\ (x - 1)^2 + (y - 2)^2 + (z - 3)^2 = \\ = (x - 1)^2 + (y - 5)^2 + (z - 3)^2 = \\ = (x - 3)^2 + (y - 3)^2 + (z - 3)^2 \end{cases}$$

$$\Rightarrow \begin{cases} z = 3 \\ y^2 - 4y + 4 = y^2 - 10y + 25 \\ x^2 - 2x + 1 + y^2 - 4y + 4 = \\ = x^2 - 6x + 9 + y^2 - 6y + 9 \end{cases}$$
