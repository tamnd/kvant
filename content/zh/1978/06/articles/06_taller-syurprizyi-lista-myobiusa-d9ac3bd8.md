---
id: 1978-6-taller-syurprizyi-lista-myobiusa-d9ac3bd8
issue: kvant_1978_6
year: 1978
number: "6"
title: 莫比乌斯带的惊喜
authors:
  - Таллер А.
rubric: osnovnye-stati
page_first: 30
page_last: 33
page_labels: 28-31
tag: 6AR7
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 950a86fe9d7b9756075bfaea0ab5605d57004d3b375f2af8170938d679ca486c
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/06_taller-syurprizyi-lista-myobiusa-d9ac3bd8.md
source_content_sha256: 1334c2851b50ce90ec55f4ec929596e23029a5ae0f5cf8d7e09361e516535451
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

A·塞勒

苏尔皮萨
莫比努斯带

让我们想象一个表面和一只蚂蚁坐在上面。蚂蚁是否到达了表面的边缘（形象地说，到达其底面）而没有溢出边缘？当然不是！直到本世纪中叶，数学家们才确信这一点，当时德国天文学家和几何学家奥古斯特·莫比努斯给出了第一个单面表面的例子，蚂蚁可以爬到任何地方而不会趴在边缘上。我们将讨论这个表面，称为莫比努斯带（或条带）。

在继续阅读之前，先制作一个莫比努斯带的模型：取一条长为窄矩形 ABCD (图 1) 的纸带；将其扭转 180°，粘出一个环 - 莫比努斯带已准备就绪。尝试覆盖它的一侧，使另一侧保持白色。通过判断，您很快就会发现染料是“由内而外”的。因此，莫比努斯带确实是一个单面表面。

即使您尝试切割莫比努斯带，它也会克服不止一种速度：

1) 沿着中心线剪下莫比努斯带。在最后一次切割 (图 2) 时，该部件不会分裂成两块，而是展开成一条长的连接的闭合条带。

2) 将第一次切割后获得的胶带沿其中心线再次切割。在最后一次垮台之前，试着猜猜会发生什么？

3) 取另一条很窄的纸条，这次不是 180°，而是 360°，然后将其粘在一起。

图 1.

⟦folio 29⟧

那些;然后沿着中心线剪开。将结果与上次切割的结果进行比较。

为什么会发生这种情况？不借助纸模型和剪刀，让我们尝试用数学方法来解决它。

莫布努斯曲面方程

让我们在三维笛卡尔坐标系 $Oxyz$ 中构造莫布努斯曲面。考虑在平面 $z = 0$ 上有一个半径为 $R$、中心位于原点 $O\left(x^2 + y^2 = R^2\right)$ 的圆。让$A$点沿着这个圆向正方向匀速移动；那么平面$\alpha$穿过轴$Oz$和点$A$，将随之绕轴$Oz$匀速旋转。让我们考虑在平面 $\alpha$ 中穿过点 $A$ 的线 $l$。让直线$l$绕点$A$逆时针旋转（如果沿着点$A$的运动方向看$\alpha$），任意时刻射线$OA$与直线$l$之间的夹角等于轴之间夹角$\varphi$的一半$Ox$ 和射线$OA$。因此，当点$A$完成一整圈时，相对于初始位置$180^\circ$，直线$l$出现在表面上。

直线 $l$ 通过（参与两个运动）的空间点集是莫布努斯曲面 (图 3)。在-
图 2.

图 3.

⟦folio 30⟧

$$\begin{cases} x = \left( R + \lambda \cos \frac{\varphi}{2} \right) \cos \varphi, \\ y = \left( R + \lambda \cos \frac{\varphi}{2} \right) \sin \varphi, \\ z = \lambda \sin \frac{\varphi}{2}, \end{cases}$$

其中$0 \leq \varphi < 2\pi, \lambda \in \mathbb{R}^*$）。

该杂志的封面描绘了莫比乌斯表面的总体视图。 图4表示$-1 \leq \lambda \leq 1$对应的表面部分；我们用纸模型描绘了这部分表面。

如果绕圈时，我们以两倍的速度旋转直线，那么在 $-1 \leq \lambda \leq 1$ 处，我们将得到一条扭曲 $360^\circ$ 的条带（记住切割 3））。这已经是一个双面曲面 (图 5)。她的方程显然是

$$\begin{cases} x = \left( R + \lambda \cos \varphi \right) \cos \varphi, \\ y = \left( R + \lambda \cos \varphi \right) \sin \varphi, \\ z = \lambda \sin \varphi. \end{cases}$$

现在让我们注意到，在 $\varphi = 0$ 处，生成器 $l$ 也在点 $(-R, 0, 0)$ 处与原始圆相交。因此，它不相交

*) 这种类型的表面定义通常称为参数化；这里参数$\varphi$和$\lambda$仅由表面使用（类似于地球表面的纬度和经度）。

线性自相交

为了找到莫比乌斯面的自交线，我们要找出哪些生成元可以相交。

如果两个生成器位于不同的垂直平面上，则它们的交点（如果存在）必须位于这些平面的交线上，即在 $Oz$ 轴上。

对于每个$\varphi \in [0; 2\pi]$，我们找到母线与轴$Oz$的交点。对于这一点

$$x = \left( R + \lambda \cos \frac{\varphi}{2} \right) \cos \varphi = 0,$$

$$y = \left( R + \lambda \cos \frac{\varphi}{2} \right) \sin \varphi = 0.$$

由于$\sin \varphi$和$\cos \varphi$不能同时为0，$R + \lambda \cos \frac{\varphi}{2} = 0$。 $\varphi \neq \pi$、$\lambda = -\frac{R}{\cos \frac{\varphi}{2}}$。从 (1)$z = -R \mathrm{tg} \frac{\varphi}{2}$。

因此，母线与轴$Oz$交点的坐标：

$$\left( 0, 0, -R \mathrm{tg} \frac{\varphi}{2} \right).$$

对我们来说，存在是这样一个事实：所有位于 $\varphi \neq \pi$ 的生成器

⟦folio 31⟧

在不同点与 $Oz$ 轴相交。在 $\varphi = \pi$ 处，它们平行于 $Oz$ 轴形成。

因此，只有位于同一垂直平面内的母线对才能相交；换句话说，如果相交生成元之一对应于角度$\varphi$，则另一个相交生成元对应于角度$\varphi + \pi$。让这些图像的交点位置由参数$\lambda$的值$\lambda_1, \lambda_2$来确定。那么从(1)

$$\begin{cases}
x = \left(R + \lambda_1 \cos \frac{\varphi}{2}\right) \cos \varphi \\
= -\left(R - \lambda_2 \sin \frac{\varphi}{2}\right) \cos \varphi \\
y' = \left(R + \lambda_1 \cos \frac{\varphi}{2}\right) \sin \varphi \\
= -\left(R - \lambda_2 \sin \frac{\varphi}{2}\right) \sin \varphi \\
z = \lambda_1 \sin \frac{\varphi}{2} = \lambda_2 \cos \frac{\varphi}{2}.
\end{cases}$$

从这些表达式可以看出 $\lambda_1, \lambda_2$ 满足方程组

$$\begin{cases}
R + \lambda_1 \cos \frac{\varphi}{2} = -R + \lambda_2 \sin \frac{\varphi}{2}, \\
\lambda_1 \sin \frac{\varphi}{2} = \lambda_2 \cos \frac{\varphi}{2},
\end{cases}$$

其中 ($\text{при } \varphi \neq \frac{\pi}{2}, \frac{3\pi}{2}$) 是 $\lambda_1 = -2R \frac{\cos \frac{\varphi}{2}}{\cos \varphi}$。将求得的值$\lambda_1$代入式(1)，可得自交点坐标：

$$x = -R, \ y = -R \text{tg} \varphi, \ z = -R \text{tg} \varphi.$$

由此可见，随着$\varphi$的变化，莫比乌斯面的自交点沿位于$x = -R$平面内的直线移动，由方程$z = y$描述。因此，自相交线是直的（但不是生成的！）。封面上描绘了该直线的一段。仔细研究屏幕保护程序，您会发现上面有一条自相交线。

图 6.

为什么莫比乌斯带在切割时不会分解？

现在回答这个问题并不难。在莫比乌斯带边缘的图 4（以及盖子上）展开，即线$\lambda = \pm 1$。仔细观察：这条边并不像未扭曲的平面那样分解成一对闭合曲线，而是代表一条连续曲线。我们的切割没有接触边缘，因此边缘（以及整个条带）在切割后将保持完整。

如何解释其他 sioprizzes？

我们可以假设第二次切割是沿着线 $\lambda = \frac{1}{2}$ (图 6) 进行的。

这条线上的点的坐标（在$\varphi \in [0, 2\pi]$）由方程描述

$$\begin{cases}
x = \left(R + \frac{1}{2} \cos \frac{\varphi}{2}\right) \cos \varphi \\
y = \left(R + \frac{1}{2} \cos \frac{\varphi}{2}\right) \sin \varphi \\
z = \frac{1}{2} \sin \frac{\varphi}{2}.
\end{cases}$$

显然，切割将我们的平面分为两部分，可以有条件地称为外部和内部，内部部分是相同的，只是更窄，是莫比乌斯带的条带。外部部分是什么？

（续第 59 页）
