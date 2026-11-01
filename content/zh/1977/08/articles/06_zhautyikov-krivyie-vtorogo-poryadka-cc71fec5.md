---
id: 1977-8-zhautyikov-krivyie-vtorogo-poryadka-cc71fec5
issue: kvant_1977_8
year: 1977
number: "8"
title: 二阶曲线
authors:
  - Жаутыков О. А.
rubric: osnovnye-stati
page_first: 24
page_last: 27
page_labels: 22-25
tag: LFF3
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ea44034831ebb38446dd8f75058db5c5ed01284d7d30426c57f0976719a49394
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/06_zhautyikov-krivyie-vtorogo-poryadka-cc71fec5.md
source_content_sha256: 53aafb2f4beceb95f7959f491f69f42f1c7f2a697c5beb12e999f0aa3712831d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

二阶曲线

二阶曲线是具有两个未知数的二次方程的图。

$$Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0,$$

(1)

其中$A, B, C, D, E, F \in \mathbb{R}$。让我们用 $f(x, y)$ 表示等式（1）左边的多项式。如果$f(x_0, y_0) = 0$，则点$M(x_0; y_0)$属于方程（1）的图（参见“代数6”，第54段）。

我们的主要任务是学习根据系数$A, B, C, D, E, F$来确定该图的类型。

我们假设$A, B, C$不会同时消失（如果$A = B = C = 0$，则获得一阶曲线 - 线性方程$Dx + Ey + F = 0$的图）。

我们将选择以下计划：首先我们将研究几种简单的特殊情况——当方程（1）的某些系数变为零时，然后我们将学习通过平行平移和旋转从这些特殊情况中获得方程（1）的图形。

特殊情况

这些情况如下（计算项的所有系数，除了 $F$ 之外，均非零）：

$$Ax^2 + Ey = 0,$$

(2a)

$$Cy^2 + Dx = 0,$$

(26)

$$Ax^2 + Cy^2 + F = 0,$$

(3)

方程（5a）的图形是抛物线（参见《代数 6》第 24 段和 I. N. Bronstein 的文章《抛物线》«Kvant»，1975 年第 4 期）。很容易理解，式（56）也定义了一条抛物线——它是由抛物线$y = -\frac{C}{D}x^2$相对于第一坐标角的二边值反射得到的（见图1）。

圆周、椭圆、双曲线、原点、一对直线或空集。这一切都可以用方程（3）来表示。

事实上，如果 $A = C$ ($\neq 0$)，则方程（3）可以重写为

$$x^2 + y^2 = \frac{-F}{A}.$$

(6a)

如果$-F/A > 0$，则等式(6a)定义半径为$\sqrt{-F/A}$(图2)的圆。如果$-F/A = 0$，则只有$x = 0, y = 0$对满足方程（6a），并且原点由图控制。若$-F/A < 0$，则方程(6a)无解，其图为空集。

现在让$A \neq C$。那么如果$A$和$C$同号（即$C/A > 0$），则式（3）的图可以改写为

$$x^2 + \frac{C}{A}y^2 = \frac{-F}{A},$$

(66)

如果 $-F/A > 0$ 则为椭圆（参见 图 3 和 I. N. Bronshtein 在 «Kvant» 中的文章“椭圆”，1975 年第 1 期），如果 $-F/A = 0$ 则为原点，如果 $-F/A < 0$ 则为空集。

⟦folio 23⟧

图 1.

如果$A$和$C$具有不同的符号（即，如果$C/A < 0$），则$F \neq 0$的方程（66）定义了一条双曲线（参见I.N.Bronstein在«Kvant»，1975年，第3期中的文章“双曲线”），而对于$F=0$ - 一对直线(图4)

$$x + \sqrt{\frac{-C}{A}} y = 0,$$
$$x - \sqrt{\frac{-C}{A}} y = 0$$

（参见“代数 6”，第 21 段；这些方程可以很容易地简化为 $y=kx$ 的形式）。

该集合是直接集合还是空集合。在方程（4a）和（46）中，需要考虑三种情况：$F=0, F/A > 0$（或$F/C > 0$）和$F/A < 0$（或$F/C < 0$）。

图 2.

图 3.

图 4.

如果$F=0$，则(4a)变为方程$x=0$，其图形为$Oy$轴，(46)给出$y=0$，即$Ox$轴。

如果数字$F$和$A$（或$F$和$C$）具有不同的符号，则方程（4）各给出一对平行于$Oy$轴的直线：

$$x = \pm \sqrt{\frac{-F}{A}}$$

或轴$Ox$

$$y = \pm \sqrt{\frac{-F}{C}}.$$

如果数$F$和$A$（或$F$和$C$）具有相同的符号，则等式（4a）（和（46））的图是空集。

⟦folio 24⟧

变化

这些是将一个图形转换为与其一致的图形的转换。因此，由于变化，直线将保持直线，抛物线将保持抛物线，双曲线将保持双曲线。但是这些线的方程发生了变化（但仍然是二阶方程），这可以用来简化方程 - 例如，选择一个平移，之后项 $Dx$ 将消失在方程中，或者选择一个旋转来取消 $Bxy$。我们将限制自己的平移和旋转。

并行传输。让并行传输$\vec{r}(a; b)$将点$M(x; y)$移动到点$M'(u; v)$。那么 $x+a=u, y+b=v$ (图 5)，所以

$$x = u - a,$$
$$y = v - b.$$

如果点$M$的坐标满足方程$f(x, y)=0$，则点$M'(u; v)$的坐标满足方程

$$g(u, v) = f(u - a, v - b) = 0,$$

也就是说，传递$\vec{r}(a; b)$时，方程的图形$f(x, y)=0$显示在方程的图形中（在变量$x, y$中）

$$g(x, y) = f(x - a, y - b) = 0.$$

反向平移$\vec{r}'(-a; -b)$将方程$g(x, y)=0$的图映射到方程$f(x, y)=0$的图。

在教科书《代数与入门分析10》（第9*节）中证明，当传递$\vec{r}(a; b)$时，函数$y=f(x)$的图映射到函数$y=f(x-a)+b$的图。这个事实很容易从我们已经证明的转移性质中得到（很清楚为什么$a$包含在最后一个带有减号的公式中，而$b$带有加号）。函数$y=f(x)$的图形与方程$g(x, y) = y-f(x) = 0$的图形重合。

从方程$g(x, y)=0$的图转移$\vec{r}(a; b)$，得到方程$g(x-a, y-b)=0$的图，即方程$(y-b)-f(x-a)=0$，或函数$y = f(x-a)+b$。

轮流。考虑以 $O(0; 0)$ 为中心沿正方向（逆时针）旋转角度 $\beta$。通过此旋转，$R_0^\beta$ 将点 $M(x; y)$ 映射到点 $M'(u; v)$。让我们尝试连接 $u, v$ 和 $x, y$。令$|OM|=r$和点$M(x; y)$由点$K(r; 0)$在轴$Ox$上旋转角度$\alpha$（图6）得到。然后（参见“代数和分析开始 9”，§.14，第 70、71 段）$x=r\cos \alpha, y=r\sin \alpha$。但点$M'(u; v)$是由点$K(r; 0)$转过角度$\alpha+\beta$得到的，因此$u=r\cos (\alpha+\beta), v=r\sin (\alpha+\beta)$。自从

$$\cos (\alpha+\beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta,$$
$$\sin (\alpha+\beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta,$$

⟦folio 25⟧

我们得到：

$$u = r \cos(\alpha + \beta) = x \cos \beta - y \sin \beta,$$
$$v = r \sin(\alpha + \beta) = x \sin \beta + y \cos \beta.$$

当返回$R_0^{-\beta}$时，点$M'(u; v)$映射到点$M(x; y)$，所以
$$x = u \cos(-\beta) - v \sin(-\beta) = u \cos \beta + v \sin \beta,$$
$$y = u \sin(-\beta) + v \cos(-\beta) = -u \sin \beta + v \cos \beta.$$

如果点$M(x; y)$的坐标满足方程$f(x, y)=0$，则点$M'(u; v)$的坐标必须满足方程

$$g(u, v) = f(u \cos \beta + v \sin \beta, -u \sin \beta + v \cos \beta) = 0,$$

也就是说，旋转$R_0^{\beta}$后，方程$f(x, y)=0$的图形被映射到方程的图形（在变量$x, y$中）

$$g(x, y) = f(x \cos \beta + y \sin \beta, -x \sin \beta + y \cos \beta) = 0.$$

简化方程 $f(x, y)=0$

我们回到二阶曲线的一般方程（1）

$$Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0.$$

让我们尝试旋转成员$Bxy$的图像。将表达式$x, y$至$u, v$（式（8））代入方程$f(x, y)=0$，可得二阶方程$g(u, v)=0$。我们写出仅包含$uv$的项并找到$B'$——乘积$uv$的系数的新值：

$$B' = (A - C) 2\sin \beta \cos \beta + B (\cos^2 \beta - \sin^2 \beta).$$

让我们将其等同于零：

$$(A - C) \sin 2\beta + B \cos 2\beta = 0$$

并找到 $\beta$：

$$\mathrm{tg} 2\beta = \frac{B}{C - A}$$

$$\cos 2\beta = 0 (\beta = 45^\circ)$$ $A = C$。

因此，您始终可以旋转图像 (1) 来查看

$$Ax^2 + Cy^2 + Dx + Ey + F = 0.$$

示例 给出方程

$$7x^2 + 6\sqrt{3}xy + 13y^2 + 4(\sqrt{3} - 8)x - 4(8\sqrt{3} + 1)y + 4 = 0.$$

这里$A = 7, B = 6\sqrt{3}, C = 13$，因此$tg 2\beta = \sqrt{3}, \beta = 30^\circ$。将（使用式（8））代入式（10）

$$x = \frac{\sqrt{3}}{2} u + \frac{1}{2} v,$$

$$y = -\frac{1}{2} u + \frac{\sqrt{3}}{2} v,$$

我们得到（检查！）方程

$$4u^2 + 16v^2 + 8u - 64v + 4 = 0.$$

这意味着方程（10）的图形是由方程的图形得到的

$$4x^2 + 16y^2 + 8x - 64y + 4 = 0$$

转$R_0^{-30^\circ}$。

现在让我们使用平移并尝试将方程 (9) 简化为一个更简单的方程 - 没有术语 $Dx$ 和 $Ey$。当传递$r(a; b)$时，等式$f(x, y)=0$的图进入等式$g(x, y)=0$的图，其中$g(x, y)=f(x-a, y-b)$，即等式（9）进入：

$$A(x-a)^2 + C(y-b)^2 + D(x-a) + E(y-b) + F = 0.$$

展开括号并化简，我们得到：

$$Ax^2 + Cy^2 + (D - 2aA)x + (E - 2bC)y + Aa^2 + Cb^2 - aD - bE + F = 0.$$

让我们将 $x, y$ 的系数等于零，并得出 $a$ 和 $b$ 的方程：

$$D - 2aA = 0, E - 2bC = 0,$$

从那里$a = \frac{D}{2A}$（在$A \neq 0$），$b = \frac{E}{2C}$（在$C \neq 0$）。

示例（续）。在方程（11）中$A = 4, C = 16, D = 8, E = -64, F = 4$，因此$a = 1, b = -2$，并且平移$r(1; -2)$将方程（11）的图变换为方程的图

$$4x^2 + 16y^2 - 64 = 0,$$

或者

$$x^2 + 4y^2 - 16 = 0.$$

这是式（3）的方程，它定义了一个椭圆

$$\left(\frac{x}{4}\right)^2 + \left(\frac{y}{2}\right)^2 = 1.$$
