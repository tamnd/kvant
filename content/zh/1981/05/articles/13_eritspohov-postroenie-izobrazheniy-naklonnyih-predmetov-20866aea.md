---
id: 1981-5-eritspohov-postroenie-izobrazheniy-naklonnyih-predmetov-20866aea
issue: kvant_1981_5
year: 1981
number: "5"
title: 构建倾斜物体的图像
authors:
  - Ерицпохов Б. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 39
page_last: 42
page_labels: 37-40
tag: O98F
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d9c4e85657060e542d4d3b1eee82e38a6113a91d46302ba11b870f35fc2af346
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/13_eritspohov-postroenie-izobrazheniy-naklonnyih-predmetov-20866aea.md
source_content_sha256: 449b636447ea0781b4fcff68ce134c142b04706949995d3077b6ea355f2173a9
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

构建倾斜物体的图像

为了找到光学系统（例如透镜或镜子）中发光点的图像，构建从该点发出的两条光线的路径就足够了。通常，选择三个特征射线中的两个，其经过系统的路径是已知的。它们是穿过系统光学中心的光线、平行于其光轴入射到系统上的光线以及穿过系统前焦点的光线。

但是如果光源不是精确的而是扩展的怎么办？当然，您可以构建各个点的图像，但有时可以不使用简化。因此，如果物体垂直于主光轴，则图像也垂直于它。如果物体与轴倾斜任意角度怎么办？让我们仔细看看这个案例。

让对象 $AB$ 停留在轴上的点 $A$ 上，并与轴形成角度 $\alpha$。让我们在光学系统中构造该物体的图像 $A'B'$，例如在聚光透镜 (图 1) 中。直观上，可以认为图像将相对于轴与物体对称地定位。然而，事实并非如此。让我们找出角度 $\beta$ 对角度 $\alpha$ 的依赖性。

让我们根据学校教科书中采用的符号规则，在物体空间中指向坐标轴$XOY$，在图像空间中指向$X'OY'$。在这种情况下，坐标$x$对应于从物体到镜头的距离$d$，坐标$x'$对应于从镜头到图像的距离$f$。

角度 $\alpha$ 和 $\beta$ 将由它们的切线 $^*$ 确定）。从 图 1

$$tg\alpha = \frac{y}{d - d_0}, \quad tg\beta = -\frac{y'}{f_0 - f} = \frac{y'}{f - f_0},$$

$$\frac{y'}{y} = \frac{f}{d}.$$

由透镜公式$\frac{1}{d} + \frac{1}{f} = \frac{1}{F}$和$\frac{1}{d_0} + \frac{1}{f_0} = \frac{1}{F}$我们表达$f$和$f_0$：

$$f = \frac{Fd}{d - F}, \quad f_0 = \frac{Fd_0}{d_0 - F}.$$

我们最终会得到它

$$tg\beta = tg\alpha \left(1 - \frac{d_0}{F}\right).$$

* 在这种情况下，在从轴线$OX$到轴线$OY$的旋转方向上不存在角度$\alpha$，并且从轴线$OX'$到轴线$OY'$不存在角度$\beta$。

⟦folio 38⟧

图 2 显示了当物体$AB$ 及其图像$A'B'$ 不接触光轴时的更一般情况。自己考虑这种情况并获得角度 $\beta$ 的正切更通用的公式：

$$\text{tg} \beta = \frac{y_1(d_2 - F) - y_2(d_1 - F)}{F(d_2 - d_1)}$$

假设光源是一条发光线 (图 3)。这条线的方程的形式为 $y = kx + b$，其中 $b = -kd_0$ 和 $x = d$。让我们在图像空间中找到函数$y'$：

$$y' = y \frac{f}{d} = y \frac{f - F}{F} = k \left( \frac{fF}{f - F} - d_0 \right) \frac{f - F}{F} = k \left( 1 - \frac{d_0}{F} \right) f + kd_0,$$

或者

$$y' = k'x' + b'$$

其中$k' = k \left( 1 - \frac{d_0}{F} \right)$和$b' = kd_0$。

显然这是一个直线方程；因此，直线的图像也是直线。系数 $k$ 和 $k'$ 分别是角度 $\alpha$ 和 $\beta$ 的正切：

$$k = \text{tg} \alpha, \ k' = \text{tg} \beta.$$

由此，角度$\alpha$和$\beta$的切线之间的联系再次得到。

请注意，在几何光学中，仅考虑副斯卡光线，即非常接近主光轴的光线。然而，从所有图中（前一张和后一张）的可视化消息来看，角度 $\alpha$ 都显示得相当大。

现在让我们继续看具体的例子。让我们一致认为，在所有图中，发光线的形式为$y = kx + b$，其中$b = -kd_0$和$x = d$。让我们在图像空间中找到函数$y'$：

$$y' = y \frac{f}{d} = y \frac{f - F}{F} = k \left( \frac{fF}{f - F} - d_0 \right) \frac{f - F}{F} = k \left( 1 - \frac{d_0}{F} \right) f + kd_0,$$

或者

$$y' = k'x' + b'$$

其中$k' = k \left( 1 - \frac{d_0}{F} \right)$和$b' = kd_0$。

例1、让发光直线与集光线光轴相交于坐标$d_0 = 2F$（图4）点。然后

$$k' = k \left( 1 - \frac{d_0}{F} \right) = k \left( 1 - \frac{2F}{F} \right) = -k,$$

或者

$$\text{tg} \beta = k' = -k = -\text{tg} \alpha.$$

示例 2. 设 $d_0 = 0$。然后

$$k' = k \left( 1 - \frac{d_0}{F} \right) = k.$$

对应的发光线及其在采集线中的图像如图5所示。

示例 3. 如果 $d_0 = F/2$ (图 6)，则求直线在波状球面镜中的图像。

请注意，在波浪镜的情况下，图像空间中的 $OX'$ 轴与物空间中的 $OX$ 轴的方向相同。

⟦folio 39⟧

图 4.

例 4. 让我们在发散透镜和凸面镜中构造一条直线的图像，前提是 $d_0 = F$。

对于散射系统，透镜公式的形式为

$$\frac{1}{d} + \frac{1}{f} = -\frac{1}{F},$$

这就是为什么

$$k' = k \left( 1 + \frac{d_0}{F} \right).$$

在我们的例子中

$$k' = k \left( 1 + \frac{d_0}{F} \right) = 2k.$$

图 5.

图 6.

由于凹面镜的所有公式与会聚透镜的公式相同，因此我们得到

$$k' = k \left( 1 - \frac{d_0}{F} \right) = \frac{k}{2}.$$

发散透镜和凸面镜结构的对应关系如图7和图8所示。

示例 5. 让一条发光线穿过坐标为 $d_0 = F$ 的点。她的形象会是怎样的呢？

⟦folio 40⟧

在收集系统（收集透镜或波镜）中发酵？
若$d_0 = F$，则
$$k' = k \left( 1 - \frac{d_0}{F} \right) = 0.$$
这意味着斜线的图像将是平行于系统主光轴的直线。在图9时进行会聚透镜的构造。
例 6. 让我们找出散射系统中的图像在直线的什么位置将平行于系统的光轴。
由于对于分散系统
$$k' = k \left( 1 + \frac{d_0}{F} \right),$$
那么 $k'$ 在 $d_0 = -F$ 处将等于 0。凸面镜的相应结构如图10所示。

让我们更详细地看一下最后两个示例。
首先，从 图 9 和 10 可以得出 $y' = F \mathrm{tg} \alpha$。这意味着发光直线与系统光轴的倾斜角度越大，像线离光轴越远。
其次，我们注意到，当物体的 linny 点在 linny 图像上均匀分布时，分布点是不均匀的（例如，参见 图 10）。这是由于所谓的纵向放大率（光轴方向上的放大率）所致，该放大率由以下公式确定
$$\Gamma_{\text{прод}} = \lim_{d_2 \to 0} \frac{f_2 - f_1}{d_2 - d_1}.$$
换句话说，纵向增量等于从 $f$ 到 $d$ 的任意一个：
$$f' = \left( \frac{Fd}{d-F} \right)' = -\left( \frac{F}{d-F} \right)^2 = -\Gamma_{\text{попер}}^2$$
