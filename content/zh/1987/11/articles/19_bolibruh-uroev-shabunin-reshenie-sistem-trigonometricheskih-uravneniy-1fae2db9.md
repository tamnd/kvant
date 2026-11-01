---
id: 1987-11-bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9
issue: kvant_1987_11
year: 1987
number: "11"
title: 求解三角方程组
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: XXRY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2b3a1f068b7aa04c6d02a29d8d048568aa74acd9499d86b87a2b7e523a2723c1
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/19_bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9.md
source_content_sha256: e91de4415ab15b8e3c218a33b9c2ab8949e4c282e7d086e5d075058bddb6fa34
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

求解三角方程组

物理和数学科学候选人
A.A.博利布鲁克，
物理和数学科学候选人
V.M.乌罗耶夫，
M.I.沙布宁教授

在本文中，以 MIPT 不同年份的入学考试（笔试和口试）中提出的问题为例，给出了一些求解三角方程组的方法。

让我们回顾一下适用于任何系统（不一定是三角系统）的定义。如果一个系统的每个解决方案都是另一个系统的解决方案，那么第二个系统被称为第一个系统的“后果”。如果第一个系统是第二个系统的结果，而第二个系统是第一个系统的结果，那么这样的系统被称为等效系统。

让我们指出系统的一些变换，由此我们获得与原始系统等效的系统。

1. 系统的任何方程都可以用等效方程代替。

2. 系统的任何方程都可以用通过将给定方程添加到系统的另一个方程而获得的方程来代替。

3. 从系统的某个方程中找到的未知值可以代入同一系统的任何其他方程。

4. 您可以向系统中添加一个方程，该方程是该系统的结果。

5. 如果一个系统包含方程$f \cdot g = 0$，其中函数$f$和$g$定义在同一集合上，那么它相当于两个系统的集合，其中一个系统中的方程$f \cdot g = 0$被方程$f = 0$代替，另一个系统中的方程被$g = 0$代替。

当开始求解三角方程组时，建议首先检查是否可以从系统的任何方程中用其他未知数模糊地表达其中一个未知数。

问题 1（MIPT，1983）。求解方程组
$$\begin{cases} tg x + tg y = 1 - tg x \cdot tg y, \\ \sin 2y - \sqrt{2} \sin x = 1. \end{cases}$$

解决方案e.仅当定义了函数 $tg x$ 和 $tg y$ 时，底层系统才有意义，即

⟦folio 47⟧

有条件
$$\cos x \neq 0, \cos y \neq 0.$$ (3)

让我们看一下第一个方程。将两个部分除以 1 - tg x · tg y 并使用总和的正切公式是很自然的。那么方程(1)可以改写为
$$\text{tg}(x + y) = 1;$$ (4)
但同时我们可能会失去系统（1）、（2）的那些解，其中
$$1 - \text{tg} x \cdot \text{tg} y = 0.$$ (5)
然而，很容易验证系统(1)、(2)、(5)无解。事实上，如果该系统有解，那么从方程 (1) 可以得出 tan x + tan y = 0。但是方程 (5) 将采用 1 + tan² y = 0 的形式，因此它没有解。

因此，条件(3)下的原系统等价于系统(2)、(4)。

从方程（4）我们发现x + y = π/4 + πn，即
$$y = \pi/4 + \pi n - x, \ n \in \mathbb{Z}.$$ (6)
现在我们将找到的 y 表达式代入原系统的方程（2）：
$$\sin(\pi/2 - 2x + 2\pi n) - \sqrt{2} \sin x = 1.$$
所得方程简化为 sin x (2 sin x + √2) = 0 的形式，由此
a) sin x = 0, x = πm, m ∈ Z,
6) sin x = -√2/2,
x = (-1)^{k+1}π/4 + πk, k ∈ Z.
利用公式（6）我们确定y的对应值。对于系列 a)
$$y = \pi/4 + \pi(n - m), \ n, m \in \mathbb{Z};$$ (7)
适用于系列 6)
$$y = \pi/4 - (-1)^{k+1}π/4 + π(n - k), \ n, k \in \mathbb{Z}.$$ (8)
式(7)中的值(x,y)满足条件(3)。系列 (8) 需要额外的研究。如果sin x = -√2/2，则cos x ≠ 0，因此方程(3)的第一个不等式完全依赖。第二个不等式 cos y ≠ 0 并不总是满足。

如果k是偶数，即k = 2p，其中p ∈ Z，则公式(8)给出y = π/2 + π(n - 2p)。对于y的这些值，条件(3)不满足。如果 k 是奇数，即 k = 2p - 1，其中 p ∈ Z，则 y = π(n - 2p + 1) 且条件 (3)
日志。使用公式6）找到x对应的值：x = -3π/4 + 2πp。
答案：(πm; π/4 + π(n - m)), (-3π/4 + 2πp; π(n - 2p + 1)), m, n, p ∈ Z。

系统解记录中包含的整数参数不能用一个字母表示。这意味着它们被指定为具有相同的值，而实际上它们具有所有相同的值 - 相同或不同。

下文中，k、l、m、n、p、r、s、t，除非另有说明，均取整数值。

问题 2. 求解方程组
$$\begin{cases} \sin x \cdot \cos y = -1/2, \\ \cos x \cdot \sin y = 1/2. \end{cases}$$ (9)

解决方案。将系统（9）的方程相加，然后从第二个方程中减去第一个方程，我们得到与系统（9）等效的系统：
$$\begin{cases} \sin(x + y) = 0, \\ \sin(y - x) = 1, \end{cases}$$

依次位于哪里
x + y = πn, y - x = π/2 + 2πk,
x = π(n/2 - k - 1/4),
y = π(n/2 + k + 1/4).

答案：(π(n/2 - k - 1/4)；π(n/2 + k + 1/4))。

就像系统（9）一样，您可以解决以下形式的任何系统
$$\begin{cases} \sin x \cdot \sin y = a, \\ \cos x \cdot \cos y = b. \end{cases}$$

此类系统包括例如系统
$$\begin{cases} \sin x \cdot \sin y = a, \\ \text{tg} x \cdot \text{tg} y = b, \\ \sin x \cdot \cos y = a, \\ \text{tg} x \cdot \text{ctg} y = b. \end{cases}$$

如果一个系统仅包含两种三角函数的组合或者可以简化为一种，那么通过将这些函数的组合指定为新的未知数，我们可以将原始系统简化为代数系统。

问题 3. 求解方程组
$$\begin{cases} \cos x - \sin x = 1 + \cos y - \sin y, \\ 3 \sin 2x - 2 \sin 2y = 3/4. \end{cases}$$ (10)

解决方案。让我们使用身份
$$(\sin x - \cos x)^2 = 1 - \sin 2x$$ 并表示

⟦folio 48⟧

cos x - sin x = u, cos y - sin y = v;
(11)

然后
sin 2x = 1 - u², sin 2y = 1 - v²,
系统(10)将被简化为代数系统
$$\begin{cases} u = 1 + v, \\ 3u^2 - 2v^2 = 1/4. \end{cases}$$

系统(12)有两个解：
$$u_1 = -9/2, v_1 = -11/2 \text{ и } u_2 = 1/2, v_2 = -1/2.$$
我们首先考虑$u_1, v_1$的值。回到原来的变量，利用式(11)可得：
$$\begin{cases} \cos x - \sin x = -9/2, \\ \cos y - \sin y = -11/2. \end{cases}$$

但系统 (13) 的第一个方程无解，因为 cos x - sin x = $\sqrt{2}$ cos $(x + \pi/4)$ $\geqslant -\sqrt{2} > -9/2$。

因此，系统(13)无解。

现在让我们考虑$u_2$和$v_2$的值。再次利用公式(11)，我们得到
$$\begin{cases} \cos x - \sin x = 1/2, \\ \cos y - \sin y = -1/2. \end{cases}$$

对于第一个方程，我们发现
$$\cos x \cdot 1/\sqrt{2} - \sin x \cdot 1/\sqrt{2} = 1/2\sqrt{2}, \cos(x + \pi/4) = 1/2\sqrt{2}, x + \pi/4 = \pm \arccos(1/2\sqrt{2}) + 2\pi n, x = -\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n.$$
以完全相同的方式我们得到
$$y = -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n.$$
于是，我们对原系统找到如下解决方案：
$$(-\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n; -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n)$$
（符号的选择是相互独立的）。

在某些情况下，系统可以采用以下形式
$$\begin{cases} \sin x = f(y), \\ \cos x = g(y), \end{cases}$$

由此，由于主要三角点$\sin^2 x + \cos^2 x = 1$，我们得到方程$f^2(y) + g^2(y) = 1$，其中仅包含一个未知数。

如果系统简化为以下形式
$$\begin{cases} \text{tg} x = f(y), \\ \text{ctg} x = g(y), \end{cases}$$

那么未知的 $x$ 就被方程的变量排除：tg $x \cdot \text{ctg} x = 1$，因此$f(y) \cdot g(y) = 1$。

使用这种解决方法，必须仔细监控，以免丢失解决方案，也不会获得无关的解决方案。

问题 4（MIPT，1978）。求解方程组
$$\begin{cases} 4 \sin x - 2 \sin y = 3, \\ 2 \cos x - \cos y = 0. \end{cases}$$

解决方案。系统(15)可以简化为形式(14)。因此，我们得到了一个等价系统
$$\begin{cases} \sin x = 3/4 + 1/2 \cdot \sin y, \\ \cos x = 1/2 \cdot \cos y. \end{cases}$$

通过将系统（16）的方程逐项平方并相加，我们得到系统（16）的结果方程：
$$1 = \frac{9}{16} + \frac{3}{4} \sin y + \frac{1}{4} \cos^2 y,$$
或者
$$\sin y = 1/4,$$

在哪里
$$y = (-1)^n \arcsin 1/4 + \pi n.$$
从系统 (16) 的第一个方程考虑 (17)，我们发现 $x = 7/8$, $x = (-1)^m \arcsin 7/8 + \pi m.$

由于求解方程组(15)时可能会出现解的构造(使用了平方运算)，因此需要将求得的值(18)、(19)代入该方程组的第二个方程中进行选择。

容易看出，对于式（18）、（19）中的偶数$m$和$n$，cos$x$和cos$y$对应的值为正，对于奇数$m$和$n$对应的值为负。于是|cos$x| = \sqrt{1 - \sin^2 x} = \sqrt{15}/8, |\cos y| = \sqrt{15}/4$，这样满足系统(16)的第二个方程只需要cos$x$和cos$y$的值一致即可。从这里我们得到
$$\begin{cases} x = \arcsin \frac{7}{8} + 2\pi k, \\ y = \arcsin \frac{1}{4} + 2\pi l, \end{cases}$$

$$x = -\arcsin \frac{7}{8} + (2k + 1)\pi,$$
$$y = -\arcsin \frac{1}{4} + (2l + 1)\pi.$$

可以将得到的两个级数(20)组合起来，并将答案写成以下形式。

⟦folio 49⟧

回答：

$$((-1)^p \arcsin \frac{7}{8} + \pi p),$$
$$((-1)^p \arcsin \frac{1}{4} + \pi (p + 2r)).$$

在求解三角系统时，往往很难迈出第一步，找到解决问题的“钥匙”。这里不能给出一般性建议。我们只能建议尝试应用系统方程的此类变换，从而导致出现一个参数的三角函数，或者至少不会增加具有不同参数的函数的数量。

问题 5（MIPT，1982）。求解方程组

$$\begin{cases}
3 \cos 3x = \sin (x + 2y), & (21) \\
3 \sin (2x + y) = -\cos 3y.
\end{cases}$$

解决方案。如果我们用参数 $x$ 和 $y$ 的正弦和余弦来表达方程的项，我们会得到一个相当复杂的系统。因此，应选择另一种解决方案。

请注意，系统方程中余弦参数的总和等于 $3x + 3y$，与正弦参数的总和一致。考虑到这一点，让我们“交叉”重新排列系统（21）的方程，即将一个方程的左侧乘以另一个方程的右侧。我们得到方程 $-\cos 3x \cos 3y = \sin (x + 2y) \sin (2x + y)$, (22)，它是系统 (21) 的结果。

让我们在方程（22）中注意三角函数与相应的和（差）的乘积；我们在应用类似的 cos $(x - y)$ + cos $(3x - 3y) = 0$ 后得到，因此 2 cos $(x - y) \cdot \cos (2x - 2y) = 0$。这个方程分解为两个方程：

$$\cos (x - y) = 0, \quad (23)$$
$$\cos (2x - 2y) = 0. \quad (24)$$

因此，系统(21)等于系统(21)、(23)和(21)、(24)的总和。

a) 从方程（23）得出$x = y + \pi/2 + \pi n$。 (25)

将式(25)中的$x$代入系统(21)，可得：

$$3 \cos (3y + 3\pi/2 + 3\pi n) = \sin (3y + \pi/2 + \pi n), \quad 3 \sin (3y + \pi + 2\pi n) = -\cos 3y.$$

该系统的两个方程都简化为 3 sin $3y = \cos 3y$ 的形式，由此得到 $y = \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3}$。从(25)中找到$x$的对应值。

6) 现在让我们考虑系统(21)、(24)。从方程（24）我们找到$x = y + \pi/4 + \pi k/2$。将这个值代入系统(21)，我们得到：

$$3 \cos (3y + 3\pi/4 + 3\pi k/2) = \sin (3y + \pi/4 + \pi k/2), \quad 3 \sin (3y + \pi/2 + \pi k) = -\cos 3y.$$

接下来，我们将使用归约公式。从系统（26）的第二个方程可以得出$\cos 3y = 0$，即$y = \pi/6 + \pi p/3$。将该值代入第一个方程，我们得到

$$3 \cos (\pi p + \pi/2 + 3\pi/4 + 3\pi k/2) = \sin (\pi p + 3\pi/4 + \pi k/2), \quad \text{откуда } (3(-1)^k + 1) \sin (3\pi/4 + \pi k/2) = 0.$$

最后一个等式对于任何目的$k$都不满足，因此系统（26）是不一致的，并且在情况6）中没有解。

回答：

$$\left( \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi}{2} + \frac{\pi m}{3} + \pi n; \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3} \right).$$

战斗

求解方程组：

1（MIPT，1982）。

$$\begin{cases}
tg y - tg x = 1 + tg x \cdot tg y, \\
\cos 2 y + \sqrt{3} \cos 2x = -1.
\end{cases}$$

2（MIPT，1978）。

$$\begin{cases}
6 \cos x + 4 \cos y = 5, \\
3 \sin x + 2 \sin y = 0.
\end{cases}$$

3（MIPT，1982）。

$$\begin{cases}
2 \cos (3x + y) = \sin (x - y), \\
2 \sin (x + y) = \cos (3x - y).
\end{cases}$$

4（MIPT，1982）。

$$\begin{cases}
\sin (2x + y) + \sin (2x - y) = \sqrt{2} \cos y, \\
tg (x + \pi/8) + \cos y = tg^2 y.
\end{cases}$$

5（MIPT，1981）。

$$\begin{cases}
\cos 2y + 1/2 = (\cos y - 1/2) (1 + 2 \sin 2x), \\
\sin y (tg^3 x + ctg^3 x) = 3 ctg y.
\end{cases}$$

6（MIPT，1976）。

$$\begin{cases}
\sin^2 x + \cos y \cdot \sin x = \cos 2y, \\
\cos 2x + \sin 2y = \sin^2 y + 3 \cos y \cdot \sin x.
\end{cases}$$

7（MIPT，1978）。

$$\begin{cases}
\sqrt{1 + \sin x \cdot \sin y} = \cos x, \\
2 \sin x \cdot ctg y + 1 = 0.
\end{cases}$$

8（MIPT，1986）。

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$

9 (MIPT, 1982)，找到方程组的所有解

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cdot \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$
