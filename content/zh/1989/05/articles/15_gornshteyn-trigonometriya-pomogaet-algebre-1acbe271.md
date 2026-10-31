---
id: 1989-5-gornshteyn-trigonometriya-pomogaet-algebre-1acbe271
issue: kvant_1989_5
year: 1989
number: "5"
title: 三角学有助于代数
authors:
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 70
page_last: 72
page_labels: 68-70
tag: 3LYN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: fe8af366b77ebe526673f0a6fac8c511318342e32eba44018f92fdcb557d5498
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/15_gornshteyn-trigonometriya-pomogaet-algebre-1acbe271.md
source_content_sha256: 04bb695f633d7528b2f9d576aa9f87905c02ccc4522cccdc152ebd9d97cd9c77
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 68⟧

三角学
帮助代数

P·I·戈恩斯坦

通常，在解决代数问题时，可以方便地将一个变量（或多个变量，如果有多个）替换为三角函数，从而将代数问题简化为三角函数。这种替代（三角替代）有时会显着简化解决方案。一个或另一个函数的选择取决于需要简化的方程、方程组或代数表达式的类型。例如，如果由变量$x$的允许值由不等式$|x| \leq 1$决定，那么用$x=\sin \alpha$、$\alpha \in \left[-\frac{\pi}{2}; \frac{\pi}{2}\right]$或者$x=\cos \alpha$、$\alpha \in [0; \pi]$替换都很方便，具体选择哪一个取决于具体问题。

如果变量可以取任何值，则使用替换 $x=\mathrm{tg} \alpha$、$\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$ 和 $x=\mathrm{ctg} \alpha$、$\alpha \in (0; \pi)$。

让我们看几个例子。

任务 1（LPI，1976）。解方程

$$\sqrt{1-x^2}=4x^3-3x.$$

解决方案。在这种情况下$|x| \leq 1$。将$x=\cos \alpha$，$\alpha \in [0; \pi]$，我们得到等式$$\sqrt{1-\cos^2 \alpha}=4\cos^3 \alpha-3\cos \alpha$$或$|\sin \alpha|=\cos 3\alpha$，但在我们的例子中是$\sin \alpha \geq 0$，所以$\sin \alpha=\cos 3\alpha$，或

$$\cos 3\alpha-\cos\left(\frac{\pi}{2}-\alpha\right)=0.$$

求解最后一个方程，我们得到

$$\alpha=\frac{\pi}{8}+\frac{\pi k}{2}, k \in Z$$

⟦folio 69⟧

或者

$$\alpha = \frac{3}{4} \pi + \pi n, \ n \in \mathbb{Z}.$$

条件$0 \leqslant \alpha \leqslant \pi$由三个值满足

$$\alpha_1 = \frac{\pi}{8}, \ \alpha_2 = \frac{5\pi}{8} \text{ и } \alpha_3 = \frac{3\pi}{4},$$

所以

$$x_1 = \cos \frac{\pi}{8} = \sqrt{\frac{1 + \cos \frac{\pi}{4}}{2}} =$$

$$= \sqrt{\frac{1 + \frac{\sqrt{2}}{2}}{2}} = \frac{1}{2} \sqrt{2 + \sqrt{2}};$$

$$x_2 = \cos \frac{5\pi}{8} = -\sqrt{\frac{1 + \cos \frac{5\pi}{4}}{2}} =$$

$$= -\sqrt{\frac{1 - \cos \frac{\pi}{4}}{2}} = -\frac{1}{2} \sqrt{2 - \sqrt{2}};$$

$$x_3 = \cos \frac{3\pi}{4} = -\cos \frac{\pi}{4} = -\frac{\sqrt{2}}{2}.$$

答案：$\left\{ -\frac{\sqrt{2}}{2}; -\frac{1}{2} \sqrt{2 - \sqrt{2}}; \right.$

$\frac{1}{2} \sqrt{2 + \sqrt{2}}$.

让我们考虑一个稍微复杂的问题。

任务 2（LPI，1976）。解方程

$$\sqrt{1 - x} = 2x^2 - 1 + 2x\sqrt{1 - x^2}.$$

解决方案。这就是方程$|x| \leqslant 1$。如前面的示例所示，设 $x = \cos \alpha$，其中 $\alpha \in [0; \pi]$。代入并给定$\sin \frac{\alpha}{2} \geqslant 0$，$\sin \alpha \geqslant 0$，我们得到方程

$$\sqrt{2} \sin \frac{\alpha}{2} = \cos 2\alpha + \sin 2\alpha,$$

其转换为以下形式

$$\sin \left( \frac{3\alpha}{4} + \frac{\pi}{8} \right) \cos \left( \frac{5\alpha}{4} + \frac{\pi}{8} \right) = 0,$$

从 $\alpha = -\frac{\pi}{6} + \frac{4\pi k}{3}$、$k \in \mathbb{Z}$ 或 $\alpha = \frac{3\pi}{10} + \frac{4\pi n}{5}$、$n \in \mathbb{Z}$ 开始。

获得的值$\alpha$中，只有一个$\alpha = \frac{3\pi}{10}$位于区间(0;$\pi$)内。所以，$x = \cos \frac{3\pi}{10}$。

答案可以保留为三角函数形式，但也可以使用公式$\sin 18^\circ = \frac{\sqrt{5} - 1}{4}$以根式表示，该公式源自下一个等式：$\sin 36^\circ = \cos 54^\circ$。

答案：$\left\{ \cos \frac{3\pi}{10} = \frac{1}{4} \sqrt{10 - 2\sqrt{5}} \right\}$。

下一个问题会出现更复杂的情况。

问题 3（密歇根州立大学生物学院，1985 年）。线段 [0; 上有多少个根1] 有方程

$$8x(1 - 2x^2)(8x^4 - 8x^2 + 1) = 1?$$

解决方案。这是一个七次方程，因此尝试用代数方法求解它是没有希望的。然而，因子$1 - 2x^2$的存在表明了进行三角计量替代$x = \cos \varphi$，$\varphi \in (0; \pi/2)$（显然是$x \neq 0$，$x \neq 1$）的想法。

将等式左边的 $x$ 替换为 $\cos \varphi$，我们得到

$$8 \cos \varphi(1 - 2 \cos^2 \varphi) \times$$

$$\times (8 \cos^4 \varphi - 8 \cos^2 \varphi + 1) =$$

$$= 8 \cos \varphi(-\cos 2\varphi) \times$$

$$\times (8 \cos^2 \varphi(\cos^2 \varphi - 1) + 1) =$$

$$= -8 \cos \varphi \cos 2\varphi(-2 \sin^2 2\varphi + 1),$$

在哪里

$$-8 \cos \varphi \cos 2\varphi \cos 4\varphi = 1.$$

现在将两边 (*) 乘以 $\sin \varphi(\varphi \neq 0!)$：

$$-8 \sin \varphi \cos \varphi \cos 2\varphi \cos 4\varphi = \sin \varphi,$$

或者

$$-\sin 8\varphi = \sin \varphi,$$

$$\sin 8\varphi + \sin \varphi = 0,$$

$$2 \sin \frac{9}{2} \varphi \cdot \cos \frac{7}{2} \varphi = 0,$$

从 $\varphi = \frac{2}{9} \pi k$、$k \in \mathbb{Z}$ 或 $\varphi = \frac{\pi}{7} + \frac{2\pi n}{7}$、$n \in \mathbb{Z}$ 开始。从第一个系列开始，区间 $(0; \frac{\pi}{2})$ 包含两个

⟦folio 70⟧

值：$\varphi_1 = \frac{2\pi}{9}, \varphi_2 = \frac{4\pi}{9}$，第二个系列中还有两个这样的值：$\varphi_3 = \frac{\pi}{7}, \varphi_4 = \frac{3\pi}{7}$。

答案：原方程在区间[0; 1]正好有四个根。

让我们举另一个例子，其中变量的变化相当意外，其形式为 $x = \text{tg} \alpha, \alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$。

问题 4（东德奥运会，1980 年）。确定满足系统的所有实数$(x, y, z)$
$$\begin{cases} 2x + x^2y = y, \\ 2y + y^2z = z, \\ 2z + z^2x = x. \end{cases}$$
解决方案。很容易验证系统
$$\begin{cases} y = \frac{2x}{1-x^2}, \\ z = \frac{2y}{1-y^2}, \\ x = \frac{2z}{1-z^2} \end{cases}$$ (*)
相当于使用原来的。

我们知道公式$tg 2\alpha = \frac{2tg \alpha}{1-tg^2 \alpha}$。这建议执行三角计量替换$x = \text{tg} \alpha$，其中$\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$、$\alpha \neq -\frac{\pi}{4}$、$\alpha \neq \frac{\pi}{4}$。

从系统（*）我们得到$x = \text{tg} \alpha$，$y = \text{tg} 2\alpha$，$z = \text{tg} 4\alpha$，$x = \text{tg} 8\alpha$。

所以，$tg 8\alpha = \text{tg} \alpha$，$tg 8\alpha - \text{tg} \alpha = 0$，$\frac{\sin 7\alpha}{\cos 8\alpha \cos \alpha} = 0$，$\sin 7\alpha = 0$，$\alpha = \frac{\pi n}{7}$，$n \in \mathbb{Z}$。

在计算机上确定数字的数字之和
（开头部分请参见第 66 页）

计算实验主题

在计算机上安装上述算法，用于计算数字$n$的数字之和、通过加法法计算从1到$n$的所有数字的数字之和以及使用公式$fk(n)$的计算方法。测试它们的学校教科书页码。在每种情况下确定 $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$。

检验发现，对于$n \in \{-3; -2; -1; 0; 1; 2; 3\}$，得到的7组数字是不同的，确实满足原系统。

当然，前面讨论的所有例子都是人为的，可以说是专门为竞赛的申请人和参与者选择的。

总之，我们建议您自行解决以下练习。

锻炼
1. （POI，1976）。解方程
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. 解方程
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. （密歇根州立大学，经济学院，1981）。找到方程的所有解
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. （列宁格勒奥运会，1985 年）。求解方程组
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. （密歇根州立大学，生物学院，1985）。线段 [0; 上有多少个根1] 有方程
$$8x(2x^2 - 1)(8x^4 - 8x^2 + 1) = 1?$$
6. （密歇根州立大学，经济学院，1985）。所有解决方案中$(x, y, z, v)$系统
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
找出那些表达式 $x + z$ 最具意义的内容。

在计算机上确定数字的数字之和
（开头部分请参见第 66 页）

计算实验主题

在计算机上安装上述算法，用于计算数字$n$的数字之和、通过加法法计算从1到$n$的所有数字的数字之和以及使用公式$fk(n)$的计算方法。测试它们的学校教科书页码。在每种情况下确定 $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$。

检验发现，对于$n \in \{-3; -2; -1; 0; 1; 2; 3\}$，得到的7组数字是不同的，确实满足原系统。

当然，前面讨论的所有例子都是人为的，可以说是专门为竞赛的申请人和参与者选择的。

总之，我们建议您自行解决以下练习。

锻炼
1. （POI，1976）。解方程
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. 解方程
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. （密歇根州立大学，经济学院，1981）。找到方程的所有解
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. （列宁格勒奥运会，1985 年）。求解方程组
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. （密歇根州立大学，经济学院，1985）。所有解决方案中$(x, y, z, v)$系统
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
找出那些表达式 $x + z$ 最具意义的内容。

在计算机上确定数字的数字之和
（开头部分请参见第 66 页）

计算实验主题

在计算机上安装上述算法，通过加法计算数字$n$的各位数字之和，从1到$n$所有数字的数字之和以及公式$fk(n)$的计算方法。测试它们的学校教科书页码。在每种情况下确定 $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$。

检验发现，对于$n \in \{-3; -2; -1; 0; 1; 2; 3\}$，得到的7组数字是不同的，确实满足原系统。

当然，前面讨论的所有例子都是人为的，可以说是专门为竞赛的申请人和参与者选择的。

总之，我们建议您自行解决以下练习。

锻炼
1. （POI，1976）。解方程
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. 解方程
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. （密歇根州立大学，经济学院，1981）。找到方程的所有解
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. （列宁格勒奥运会，1985 年）。求解方程组
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. （密歇根州立大学，经济学院，1985）。所有解决方案中$(x, y, z, v)$系统
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
找出那些表达式 $x + z$ 最具意义的内容。
