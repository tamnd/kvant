---
id: 1979-12-ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1
issue: kvant_1979_12
year: 1979
number: "12"
title: 将解转换为三角方程
authors:
  - Иванов В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 36
page_last: 37
page_labels: 34-35
tag: 5Y6H
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 34f9c3781fc3ae649f344da06a10f5d41322f584ad13b382dbdea7fdf4268de8
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/12_ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1.md
source_content_sha256: 55b68c49d54f2a5e79033a4dc07be45f0fc5956fbdc53b3fb7e60801177fd508
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

变换三角方程的解

显然，任意自然数$n$都可以表示为$n=2t$或$n=2t+1$。此外，任何自然数$n$都可以表示为$n=3t$、$n=3t+1$或$n=3t+2$。此外，数字$n$的所有系数都可以表示为$n=4t$，或$n=4t+1$，或$n=4t+2$，或$n=4t+3$。它。 d.这一系列的陈述是有时伴随三角方程的解而来的变换的理论基础。

示例 1（NSU，力学和数学，1974 年）。解方程

$$\sqrt{\cos 2x - \sin 4x} = \sin x - \cos x.$$ (1)

求解方程（1）的明显方法是对方程两边求平方：

$$\cos 2x - \sin 4x = (\sin x - \cos x)^2.$$ (2)

简单等价 x 变换后我们得到

$$\sin x (\sin x + \cos 3x) = 0.$$

因此，方程（2）的答案为：

$$\begin{cases}
x_1 = \pi k & (k \in \mathbb{Z}), \\
x_2 = \frac{\pi}{4} + \pi l & (l \in \mathbb{Z}), \\
x_3 = -\frac{\pi}{8} + \frac{\pi}{2} m & (m \in \mathbb{Z}).
\end{cases}$$

但式（2）一般来说并不等价于式（1）；它只是（1）的介绍。因此有必要进行检查。

函数$2x$、$\sin 4x$、$\sin x$和$\cos x$的最短公共周期是$2\pi$。这意味着，如果数字$a$是方程（1）的根，则所有数字$a+2\pi t$（$t \in \mathbb{Z}$）都是它的根。因此，我们写下解(3)“周期为$2\pi$”。

将$x_1$中的变量$k$替换为$k=2t$和$k=2t+1$，我们得到

$$\begin{cases}
x_{11} = 2\pi t, \\
x_{12} = \pi + 2\pi t.
\end{cases}$$

类似地，从$x_2$我们得到

$$\begin{cases}
x_{21} = \frac{\pi}{4} + 2\pi t, \\
x_{22} = \frac{5}{4} \pi + 2\pi t.
\end{cases}$$

将$x_3$中的变量$m$替换为$m=4t$、$m=4t+1$、$m=4t+2$和$m=4t+3$，我们得到

$$\begin{cases}
x_{31} = -\frac{\pi}{8} + 2\pi t, \\
x_{32} = \frac{3}{8} \pi + 2\pi t, \\
x_{33} = \frac{7}{8} \pi + 2\pi t, \\
x_{34} = \frac{11}{8} \pi + 2\pi t.
\end{cases}$$

从 ($3_1$), ($3_2$), ($3_3$) 可以清楚地看出，鉴于上述情况，检查数字 0、$\pi$、$\frac{\pi}{4}$、$\frac{5}{4}\pi$、$-\frac{\pi}{8}$、$\frac{3}{8}\pi$、$\frac{7}{8}\pi$、$\frac{11}{8}\pi$ 就足够了。您只需将这 8 个数字代入 (1) 即可。然而，更简单的说法是方程（1）等效于“混合系统”。

图 1.

⟦folio 35⟧

$$\begin{cases} \cos 2x - \sin 4x = (\sin x - \cos x)^2, \\ \sin x - \cos x \geq 0. \end{cases}$$

因此，只需查看 (图 1) 哪个书面数字满足不等式 $\sin x \geq \cos x$ 就足够了。这种不等式由$\pi, \frac{\pi}{4}, \frac{5}{4}\pi, \frac{3}{8}\pi$和$\frac{7}{8}\pi$“承受”。

这意味着方程（1）的答案包括$x_{12}, x_{21}, x_{22}, x_{32}$和$x_{33}$。如果需要，$x_{21}$和$x_{22}$可以“向后”组合。

示例 2：求解方程

$$\sin 7x + \cos 2x = -2. \tag{4}$$

由于$\min \sin 7x = \min \cos 2x = -1$，方程(4)等价于系统

$$\begin{cases} \sin 7x = -1, \\ \cos 2x = -1. \end{cases}$$

求解系统的第一个方程

$$x_1 = \frac{3}{14}\pi + \frac{2\pi}{7}k (k \in \mathbb{Z}), \tag{5}$$

第二个方程的解

$$x_2 = \frac{\pi}{2} + \pi l (l \in \mathbb{Z}). \tag{6}$$

为了找到集合 (5)、(6) 的交集，我们将它们写为“周期为 2n”。将(5)中的变量$k$替换为$7t, 7t+1, 7t+2, 7t+3, 7t+4, 7t+5$和$7t+6$，我们得到

$$\begin{cases} x_{11} = \frac{3}{14}\pi + 2\pi t, \\ x_{12} = \frac{\pi}{2} + 2\pi t, \\ x_{13} = \frac{11}{14}\pi + 2\pi t, \\ x_{14} = \frac{15}{14}\pi + 2\pi t, \\ x_{15} = \frac{19}{14}\pi + 2\pi t, \\ x_{16} = \frac{23}{14}\pi + 2\pi t, \\ x_{17} = \frac{27}{14}\pi + 2\pi t. \end{cases} \tag{7}$$

将(6)中的变量$l$替换为$l=2t$和$l=2t+1$，我们得到

$$\begin{cases} x_{21} = \frac{\pi}{2} + 2\pi t, \\ x_{22} = \frac{3}{2}\pi + 2\pi t. \end{cases} \tag{8}$$

比较(7)和(8)，答案可见：

$$x_{12}.$$

实施例 3（密歇根州立大学化学系，1977 年）。求方程的解

$$2 - \sqrt{3}\cos 2x + \sin 2x = 4\cos^2 3x, \tag{9}$$

满足不平等

$$\cos \left(2x - \frac{\pi}{4}\right) > 0.$$

式(9)等价于式

$$1 - \cos \left(2x + \frac{\pi}{6}\right) = 1 + \cos 6x.$$

他对波兹尼的回答是：

$$\begin{cases} x_1 = \frac{5}{48}\pi + \frac{\pi}{4}k (k \in \mathbb{Z}), \\ x_2 = \frac{7}{24}\pi + \frac{\pi}{2}l (l \in \mathbb{Z}). \end{cases}$$

因此$2x - \frac{\pi}{4}$有一个句点$2\pi$，我们将这个答案写为“有一个句点$l$”。将$x_1$中的变量$k$替换为$k = 4t, k = 4t+1, k = 4t+2$和$k = 4t+3$，我们得到

$$\begin{cases} x_{11} = \frac{5}{48}\pi + \pi t, \\ x_{12} = \frac{17}{48}\pi + \pi t, \\ x_{13} = \frac{29}{48}\pi + \pi t, \\ x_{14} = \frac{41}{48}\pi + \pi t. \end{cases}$$

从这里

$$\begin{cases} 2x_{11} - \frac{\pi}{4} = -\frac{\pi}{24} + 2\pi t, \\ 2x_{12} - \frac{\pi}{4} = \frac{11}{24}\pi + 2\pi t, \\ 2x_{13} - \frac{\pi}{4} = \frac{23}{24}\pi + 2\pi t, \\ 2x_{14} - \frac{\pi}{4} = \frac{35}{24}\pi + 2\pi t. \end{cases}$$

可以看出，所需的不等式满足不等式$x_{11}$和$x_{12}$。

类似地，将$x_2$中的变量$l$替换为$l=2t$和$l=2t+1$，我们得到
