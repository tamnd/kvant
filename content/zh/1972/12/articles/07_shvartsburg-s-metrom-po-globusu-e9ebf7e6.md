---
id: 1972-12-shvartsburg-s-metrom-po-globusu-e9ebf7e6
issue: kvant_1972_12
year: 1972
number: "12"
title: 一米绕地球一圈
authors:
  - Шварцбург А. Б.
rubric: raznoe
page_first: 28
page_last: 34
page_labels: 26-32
tag: CAMU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 871c85891f198e9745da8223856c08e7c3ea0db5de94096393468f2e435d44f3
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/07_shvartsburg-s-metrom-po-globusu-e9ebf7e6.md
source_content_sha256: 1a27f2ebc69cc35e6bf50d7240fbbc1456929628a3dd62edc00ce9933d03faff
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

全球有仪表

A·B·施瓦茨堡

让我们尝试在地球表面绘制一艘离开港口 $A$ 且必须前往港口 $B$ 的船舶的路径。这条路径可以通过不同的方式完成，每种方式都有自己的优点和缺点。如果船舶赶时间，那么了解港口之间的最短路线就很重要。众所周知，在平面上，两点之间的最短距离是直线。然而，在球体上，这幅图景是有条件的。 By stretching a thread flexible and inextensible on a globe between points $A$ and $B$ (the beginning and end of the path), one can find a position of the thread at which the length $AB$ will be the smallest. However, the orientation of the thread relative to the grid of meridians and parallels marked on the globe will be different at each point along the length $AB$.这意味着在公海上铺设这样的道路并不容易。

您可以选择另一种方法 - 例如，始终朝一个方向移动，以相同的角度穿过所有经脉。那么在海上航行就会更加容易。然而，在地球上使用相同的线程，很容易验证这样的路径将比第一个路径更长。为了更好地想象每条路径，请考虑一个辅助问题。

靠近极点的运动

在学校地图上，经线和纬线通常以矩形网格的形式描绘。 However, to depict areas adjacent to the pole, another coordinate grid is used, in which meridians are represented by rays emanating from the pole $O$, and parallels are represented by circles centered at the pole.让我们假设在这样的地图上标记了点 $A$ 和 $B$。让我们尝试绘制轨迹$AB$，不关心路径的长度，但要求运动方向恒定。 In other words, it is required to measure a flat curve that would pass through points $A$ and $B$, intersecting all rays emerging from the pole at some constant angle $\alpha$ (图 1, a).

点 $A$ 和 $B$ 的坐标被视为已知（即，它们到极点 $\rho_A$ 和 $\rho_B$ 的距离以及它们的经度差已知）。很容易指出对应于 $\rho_A = \rho_B$ 的轨迹的特殊情况。垂直于从一点发出的所有光线的线是圆。要找到任意角度 $\alpha$ 的轨迹，请考虑形成小角度 $\theta$ 的两条射线。让其中之一$OA = \rho_0$对应于值$\theta = 0$。抛开第二条射线上的$ON = \rho_0 = OA$ (图 1, b)，我们注意到$\rightarrow ANO \approx \frac{\pi}{2}$（因为角度$\theta$很小）。

⟦folio 27⟧

让轨迹与射线 $ON$ 相交于点 $K$。然后从三角形$ANK$，其中$AN = \rho_0 \theta^*$)：我们找到$NK = AN \cdot \text{ctg} \alpha = \rho_0 \theta \text{ctg} \alpha$。由此可知，轨迹$OK$的半径向量长度为

$$\rho_1 = \rho_0 - \rho_0 \theta \text{ctg} \alpha = \rho_0 (1 - \theta \text{ctg} \alpha).$$

再次从$ON$顺时针延迟角度$\theta$，我们得到半径向量

$$\rho_2 = \rho_1 (1 - \theta \text{ctg} \alpha) = \rho_0 (1 - \theta \text{ctg} \alpha)^2.$$

重复这些计算$n$次，我们发现

$$\rho_n = \rho_0 (1 - \theta \text{ctg} \alpha)^n.$$

假设半径向量$\rho_0$在$n$圈中旋转了$\lambda$角度，则$\theta = \frac{\lambda}{n}$和

$$\rho_n = \rho_0 \left(1 - \frac{\lambda}{n} \text{ctg} \alpha\right)^n.$$

假设我们考虑角度$\lambda$常数，增加“步长”的数量，从而使一个“步长”$\theta = \frac{\lambda}{n}$的大小减小。如果$n$无限增加，那么这将对应于点沿着轨迹的连续移动。将式（4）代入$n \to \infty$处的前奏，我们发现（参见L. G. Limanov“论数$e$和$n!$”«Kvant»No.5，1972）：

$$\rho = \lim_{n \to \infty} \rho_n = \rho_0 e^{-\lambda \text{ctg} \alpha},$$

其中$e = 2,73$是数学中已知的常数，即著名的“数$e$”，它是自然对数的底数。

我们已经得到了与从中心发出的所有光线以角度 $\alpha$ 相交的曲线方程。通过知道点$A$和$B$的坐标以及它们的经度差$\lambda$就可以找到这个角度的值。由(5)我们发现

$$\text{ctg} \alpha = -\frac{1}{\lambda} \ln \frac{\rho}{\rho_0}.$$

鲫鱼以$\alpha$角度穿过每条子午线，将从端口$A$到达端口$B$。

从公式（6）可以看出所得曲线的其他重要属性：半径向量之间的角度与其对数成正比

*) 这样的替换相当于对角度$x \left(x \ll \frac{\pi}{2}\right)$: $\sin x \approx x$的小值进行近似等式。这个等式以及由此得出的等式 $\text{ctg} x \approx x$ 在本文中被多次使用。

⟦folio 28⟧

$$\lambda = - \frac{\ln \frac{\rho}{\rho_0}}{\text{ctg} \alpha}.$$

曲线（5）有一个特殊的名字“对数螺线”，数学家雅各布·伯努利甚至称其为“spira mirabilis”，在拉丁语中意为“奇妙的螺线”。

在这个辅助问题中，地球表面发生运动的部分被认为是一个平面。让我们尝试将所得解 (6) 推广到球面的情况。换句话说，我们尝试在地球上画一条连接点 A 和 B 并以恒定角度 α 与所有经线相交的曲线。在这种情况下，我们将需要与辅助问题中使用的相同的数学入门知识。

斯涅尔曲线

我们假设 A 点和 B 点至少有一点与球体的极点不重合。 （如果 A 和 B 是极点，则任何经线都是曲线的例外）。我们将通过纬度 φ、远离赤道和经度 λ 来表征每个点的位置。要求检查球体上从 A 点出发，坐标为 φ_A、λ_A，到达 B 点，坐标为 φ_B、λ_B（参见图 2）的一条曲线，使得所有经线都以相同的角度 α 相交。在一个辅助问题中，我们证明具有此属性的平面曲线是对数螺线。

考虑球体上两个接近的点（A 和 N）（图 3），纬度差（弧 AO）为 Δφ，经度差（弧 ON）为 θ，其中 θ 是一个小角度，(θ << λ)。如果两个点都位于我们感兴趣的曲线上，则该曲线与经过这些点的经线形成相等的角度 α。考虑弯曲三角形 AON，其中弧 AO 与子午线的部分重合，弧 ON 与纬度圆的部分 φ₁ 重合，并且 ⇄ OAN = α。让我们将 A 点的坐标 φ 的值表示为 φ_A = φ_0。因此， φ₁ = φ_0 + Δφ。

图 2.
图 3.

⟦folio 29⟧

可以严格证明坐标值$\varphi_0$和$\varphi_1$之间的关系如下：

$$\text{tg} \left( 45^\circ + \frac{\varphi_1}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) [1 + \theta \text{ctg} \alpha].$$

（附录一给出了这个等式的详细推导。）

此外，您可以用与解决辅助问题时相同的方式进行推理。函数$\text{tg} \left( 45^\circ + \frac{\varphi}{2} \right)$在坐标$\varphi_2$、$2\theta$处的值将是

$$\text{tg} \left( 45^\circ + \frac{\varphi_2}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_1}{2} \right) [1 + \theta \text{ctg} \alpha] =$$

$$= \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) [1 + \theta \text{ctg} \alpha]^2.$$

经过$n$“步数”后，我们得到$\varphi_n$

$$\text{tg} \left( 45^\circ + \frac{\varphi_n}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) \left[ 1 + \frac{\lambda}{n} \text{ctg} \alpha \right]^n.$$

现在让我们假设我们通知“步数”$n$到无穷大，接近点$B$。同时$\varphi_n \rightarrow \varphi_B$。那么每一步$\theta = \frac{\lambda}{n}$的值都趋于0，式(9)右边的因子数量无限增长。传至式（9）中$n \rightarrow \infty$处的极限，可得（类推式（5））：

$$\text{tg} \left( 45^\circ + \frac{\varphi_B}{2} \right) = \lim_{n \rightarrow \infty} \left\{ \text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right) \left[ 1 + \frac{\lambda}{n} \text{ctg} \alpha \right]^n \right\} =$$

$$= \text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right) e^{\lambda \text{ctg} \alpha}.$$

生成的曲线以恒定角度 $\alpha$ 与球体上的所有经线相交。知道每个端口的纬度（$\varphi_A$和$\varphi_B$）以及它们之间的经度差（$\lambda_B - \lambda_A) = \lambda$），可以很容易地从（10）找到这个角度的值：

$$\text{ctg} \alpha = \frac{1}{\lambda} \ln \frac{\text{tg} \left( 45^\circ + \frac{\varphi_B}{2} \right)}{\text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right)}.$$

式(10)所表示的曲线有一个专门的名字“loxodrome”，可以从拉丁文翻译为“oblique”。数学家斯内尔在 18 世纪研究了这条曲线，他也因提出光线在两种介质边界处的折射定律而闻名，被称为“在家上学”。

斜线“倾斜”穿过球的子午线并接近极点，像螺旋一样“缠绕”在极点上。不难证明斜极点的排列接近我们在辅助问题中讨论的对数螺线。事实上，在极点$\varphi = 90^\circ - \delta$附近，$\delta \ll 90^\circ$所在。然后

$$\frac{\text{tg} \left( 45^\circ + \frac{\varphi}{2} \right)}{\text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right)} \approx \frac{\text{tg} \left( \frac{\delta_0}{2} \right)}{\text{tg} \left( \frac{\delta}{2} \right)} \approx \frac{\delta_0}{2} \frac{\delta}{2}.$$

⟦folio 30⟧

比较公式(10a)和(10)，我们得到

$$\delta = \delta_0 e^{-\lambda \text{ctg} \alpha}.$$

(106)

另一方面，从极点到纬度为$\delta_A$和$\delta_B$的点$A$和$B$的距离等于对应的$\rho_A = R \delta_A$、$\rho_B = R \delta_B$（R是地球半径）。 （在写这些等式时，我们用连接弧两端的弦代替部分子午弧。）然后从（106）我们得到：

$$\rho_B = \rho_A e^{-\lambda \text{ctg} \alpha}.$$

(10v)

我们已经在一个辅助问题中获得了这个等式。

Loxodrome (10) 描述了一艘船在公海上的航线，其中运动方向保持不变，因此沿途很容易导航。然而，正如我们上面所说，沿着菱形的路径并不是球面上两点之间的最短路径。

大地线

现在让我们尝试找到一条曲线，它是球上两点之间的最短路径。这样的曲线称为测地线，但它不仅适用于测量员。这条曲线对于水手、飞行员和旅行者也很重要。如果我们简化问题并选择位于同一纬度圆$\varphi$上的点$A$和$B$，那么这些点之间的最短路径可能看起来是纬度圆的一段弧。然而，这个答案是不正确的。要验证这一点，请比较点 $A$ 和 $B$ 之间的距离 $S_1$ 和 $S_2$，并沿纬度圆 ($S_1$) 和沿大圆弧 ($S_2$) (图 4) 进行修改。如果点$A$和$B$的经度差为$\lambda$，则

$$S_1 = R \lambda \cos \varphi,$$

$$S_2 = RC,$$

其中 $C$ 是弧$S_2$ 的弧度度量。

可以证明弧$C$的大小（以弧度为单位）等于

$$C = \arccos \left[ \cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \right],$$

其中$\varphi' = \frac{\pi}{2} - \varphi$。 （这在附录二中得到了证明。）

我们来证明大圆$S_2$的弧长不大于纬度圆$S_1$($S_2 \leq S_1$)的弧长，即证明不等式：

$$R \arccos \left[ \cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \right] \leq R \lambda \sin \varphi'.$$

(14)

等式 (14) 仅在 $\varphi' = 90^\circ$ 或 $\varphi = 0$ 时返回，即当纬度圆与大圆重合时。

不等式(14)两边都是正数。我们假设点 $A$ 和 $B$ 之间的经度差位于区间 $0 \leq \lambda \leq \pi$ 内。对于 $0 \leq \lambda \leq \pi$ cos $\lambda$ 是递减函数。

⟦folio 31⟧

根据不等式(14)可得出以下不等式：

$$\cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \geq \cos (\lambda \sin \varphi').$$

使用恒等式 $\cos \lambda = 1 - 2 \sin^2 \frac{\lambda}{2}$，我们将不等式 (15) 简化为以下形式

$$\sin^2 \varphi' \sin^2 \frac{\lambda}{2} \leq \sin^2 \left( \frac{\lambda}{2} \sin \varphi' \right).$$

将这个不等式乘以正值$\left( \frac{\lambda}{2} \sin \varphi' \right)^2$，我们得到：

$$\left( \frac{\sin \frac{\lambda}{2}}{\frac{\lambda}{2}} \right)^2 \leq \left( \frac{\sin \left( \frac{\lambda}{2} \sin \varphi' \right)}{\frac{\lambda}{2} \sin \varphi'} \right)^2.$$

如果我们现在使用三角表构造函数 $y = \left( \frac{\sin x}{x} \right)^2$ 的图，我们将看到该函数从 $y = \left( \frac{2}{\pi} \right)^2 < 1$ 单调增加到 1，而 $x$ 从 $\frac{\pi}{2}$ 减少到 0。从 $\frac{\lambda}{2} \sin \varphi' \leq \frac{\lambda}{2}$ 开始，则始终满足不等式 (17)，这意味着原始不等式 (14) 也满足。因此，大圆的弧比连接相同两点的其他纬度圆短。

可以证明，即使在沙拉上的任意位置有两个点，它们之间的最短距离也是由穿过这些点的大圆弧确定的。换句话说，球上的测地线是大圆的弧。

然而，当沿着大圆弧移动时，导航是很困难的——移动方向与子午线之间的角度$\alpha$一直在变化。

因此，菱形路径和大圆路径各有其优点和缺点。在这些路径之间进行选择时，它们的行为方式通常与沿着平面移动时相同，即沿着复杂平面曲线一起移动时，会沿着虚线勾勒出路径，该虚线的所有顶点都位于所需的曲线上。

类似地，在球体上移动时，在连接出发点和目的地的大圆弧上标记几个点，并沿着菱形从一个点移动到另一个点。

**附录一**

不通过纬度 $\varphi$ 而是通过附加角度 $\varphi'$ 来表征球体上的点是很方便的

$$\varphi' = 90^\circ - \varphi.$$

这种描述的便利性是由于函数$ctg \left( \frac{90^\circ - \varphi}{2} \right)$有一个重要的性质。我们用两个角度之和的正切公式计算一下，改变$\varphi$时该函数的增量：

$$ctg \left( \frac{90^\circ - \varphi}{2} \right) = tg \left( \frac{90^\circ + \varphi}{2} \right) = tg \left( 45^\circ + \frac{\varphi}{2} \right);$$

⟦folio 32⟧

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = tg \left( 45^\circ + \frac{\varphi}{2} \right) - tg \left( 45^\circ + \frac{\varphi}{2} \right) =$$

$$= \frac{tg \left( 45^\circ + \frac{\varphi}{2} \right) + tg \frac{\Delta \varphi}{2}}{1 - tg \left( 45^\circ + \frac{\varphi}{2} \right) tg \frac{\Delta \varphi}{2}} - tg \left( 45^\circ + \frac{\varphi}{2} \right) =$$

$$= \frac{tg \frac{\Delta \varphi}{2}}{\cos^2 \left( 45^\circ + \frac{\varphi}{2} \right)} \cdot (I-3)$$

使用相同的恒等式$\frac{1}{\cos \left( 45^\circ + \frac{\varphi}{2} \right)} = 2 \sin \left( 45^\circ + \frac{\varphi}{2} \right) \cos^{-1} \varphi$，我们从公式中得到

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = \frac{2 tg \frac{\Delta \varphi}{2} tg \left( 45^\circ + \frac{\varphi}{2} \right)}{\left[ 1 - tg \frac{\Delta \varphi}{2} tg \left( 45^\circ + \frac{\varphi}{2} \right) \right] \cos \varphi}.$$

(I-4)

考虑增量$\Delta \varphi$很小的情况，因此$|tg \frac{\Delta \varphi}{2}| \cdot |tg \left( 45^\circ + \frac{\varphi}{2} \right)| \ll 1$。那么式(I-4)中的值可以认为近似等于1，并且可以将$tg \frac{\Delta \varphi}{2}$替换为$\frac{\Delta \varphi}{2}$。然后从(I-3)和(I-4)我们发现：

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = \frac{\Delta \varphi}{\cos \varphi} \cdot tg \left( 45^\circ + \frac{\varphi}{2} \right).$$

(I-5)

公式（I-5）表明函数$tg \left( 45^\circ + \frac{\varphi}{2} \right)$实际上具有重要的性质：该函数的小增量与函数本身的值成正比。

求式（I-5）中的比例系数。由于自转圆的半径等于

$$r = R \cos \varphi,$$

那么弧$ON$的长度是（参见图3）

$$ON = R \theta \cos \varphi.$$

这里$R$是球体的半径。同理，弧$OA$的长度为

$$OA = R \Delta \varphi.$$

由于角度$\angle AON = \frac{\pi}{2}$是三角形，因此对于角度$\alpha$的正切我们可以写成

$$tg \alpha = \frac{R \theta \cos \varphi}{R \Delta \varphi}.$$

由该关系式，可得式（I-5）中$\frac{\Delta \varphi}{\cos \varphi}$：

$$\frac{\Delta \varphi}{\cos \varphi} = \theta \text{ ctg } \alpha.$$
