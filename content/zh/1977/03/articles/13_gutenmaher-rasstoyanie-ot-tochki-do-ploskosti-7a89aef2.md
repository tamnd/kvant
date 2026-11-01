---
id: 1977-3-gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2
issue: kvant_1977_3
year: 1977
number: "3"
title: 点到平面的距离
authors:
  - Гутенмахер В. Л.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 40
page_last: 41
page_labels: 38-39
tag: KY12
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9323e10a00d53de10a5a85e0203c266ef963a15ce0381aa05dc393cca43352b3
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/13_gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2.md
source_content_sha256: fca9d8c596f91f2b96ee674d575ce1fe36d0df7a029d85f3b3a35d4d9cdeed7c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

V·古登马赫

点到平面的距离

《几何10》教科书中有几个问题要求你求给定点到给定平面的距离。奇怪的是，这些问题给学童带来了一些困难（尽管这些问题之一——第 28 号，第 10 页——在文本中得到了解决）。因此，我们将更详细地讨论这个问题。

新配方

令 $A(x_0; y_0; z_0)$ 为坐标空间 $Oxyz$ 中的一个点，$\alpha$ 为由方程 $ax+by+cz+d=0$ 定义的平面。从点$A$到平面$\alpha$的距离$\rho(A, \alpha)$可通过以下公式求出

$$\rho(A, \alpha) = \frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}.$$

该公式可以描述如下：

需要将点$A$的坐标代入表达式$ax+by+cz+d$而不是变量$x, y, z$。取所得数字的模，然后除以数字 $\sqrt{a^2+b^2+c^2}$。

公式推导

公式(*)的推导本质上重复了第28页给出的问题的解决方案。课本《几何10》10-11。

让我们从点 $A(x_0; y_0; z_0)$ 下降到平面 $\alpha$，由方程 $ax+by+cz+d=0$ 给出；设 $B$ 为该溢出与平面 $\alpha$ 的交点；那么$|AB|$是从$A$到$\alpha$的距离（参见图）。让我们用$(x_1; y_1; z_1)$表示点$B$的坐标；然后

$$\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = (x_1-x_0; y_1-y_0; z_1-z_0),$$

在哪里

$$|AB| = |\overrightarrow{AB}| = \sqrt{(x_1-x_0)^2 + (y_1-y_0)^2 + (z_1-z_0)^2}.$$

由于向量 $\overrightarrow{AB}$ 垂直于平面 $\alpha$，因此它与坐标为 $(a; b; c)$ 的向量 $\vec{n}$ 共线。

这意味着存在一个数字 $p$ 使得

$$\overrightarrow{AB} = p \cdot \vec{n}.$$

(1)

从这个等式可以得出

$$x_1-x_0 = p \cdot a, \quad y_1-y_0 = p \cdot b, \quad z_1-z_0 = p \cdot c.$$

(2)

因此，

$$|AB| = \sqrt{p^2a^2 + p^2b^2 + p^2c^2} = |p| \cdot \sqrt{a^2 + b^2 + c^2}.$$

剩下的就是找到数字$|p|$。由于点$B$属于平面$\alpha$，因此$ax_1+by_1+cz_1+d=0$。由于$x_1=x_0+pa, y_1=y_0+pb, z_1=z_0+pc$（参见对应关系（2）），对于$p$，我们得到方程

$$a(x_0+pa) + b(y_0+pb) + c(z_0+pc) + d=0,$$

从中找到$|p|$：

$$|p| = \frac{|ax_0+by_0+cz_0+d|}{a^2+b^2+c^2}.$$

⟦folio 39⟧

将求得的值$|p|$代入对应式(3)，得到所需的公式：

$$\rho(A, \alpha) = |AB| = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}}.$$

公式(*)可以让您轻松解决任何计算点到平面距离的问题。让我们举几个例子。

锻炼
问题 1 (*)。求从点 $A(-1; 3; 0)$ 到由方程 $x - 3y - 2z + 5 = 0$ 给出的平面 $\alpha$ 的距离。

解决方案。使用公式（*）我们得到：

$$\rho(A, \alpha) = \frac{|-1 - 3\cdot3 - 2\cdot0 + 5|}{\sqrt{1 + 3^2 + 2^2}} = \frac{|-5|}{\sqrt{14}} = \frac{5}{\sqrt{14}}.$$

问题 2**)。计算从原点到平面$2x + 3y - 6z + 14 = 0$的距离。

解决方案。我们需要找到距点 $A(0; 0; 0)$ 的距离。使用公式（*）我们得到：

$$\rho(A, \alpha) = \frac{|2\cdot0 + 3\cdot0 - 6\cdot0 + 14|}{\sqrt{2^2 + 3^2 + 6^2}} = \frac{14}{7} = 2.$$

问题 3. 计算平面 $\alpha$ 和 $\beta$ 之间的距离，由相应的方程给出：

$$3x + 2y + 4z + 11 = 0$$

和

$$9x + 6y + 12z - 5 = 0.$$

将第二个方程两边除以 3，我们看到平面 $\alpha$ 和 $\beta$：$3x + 2y + 4z + 11 = 0$ 和 $3x + 2y + 4z - \frac{5}{3} = 0$ 平行。

让我们取属于平面$\beta$的任意点$A(x_0; y_0; z_0)$：例如，先放$x_0 = y_0 = 0$，然后放$z_0 = \frac{5}{12}$。

*) 这是课本《几何 10》中的第 298.1 号问题。教科书上有一个错别字——答案不正确。
**) 这是同一教科书中的第 29.2 号问题。

很容易理解，平面$\alpha$和$\beta$之间的距离等于数字$\rho(A, \alpha)$，其中$A = \left(0; 0; \frac{5}{12}\right)$。应用公式(*)，我们得到

$$\rho(\alpha, \beta) = \rho(A, \alpha) = \frac{|3\cdot0 + 2\cdot0 + 4\cdot\frac{5}{12} + 11|}{\sqrt{3^2 + 2^2 + 4^2}} = \frac{38}{3\sqrt{29}}.$$

扫地。一般情况下，平行平面$\alpha$和$\beta$之间的距离：

$$ax + by + cz + d_1 = 0$$

和

$$ax + by + cz + d_2 = 0$$

由公式找到

$$\rho(\alpha, \beta) = \frac{|d_1 - d_2|}{\sqrt{a^2 + b^2 + c^2}}.$$

重复问题 3 的求解，得出公式 (**)。

总之，我们向您提出了几项任务。

任务 1. 计算点 $A(1; 1; 1)$ 到平面 $x + y + z = 0$ 的距离。

2. 计算点 $A(1; 2; 3)$ 到平面 $x + y + z - 6 = 0$ 的距离。

3. 求点 $A(x_0; y_0; 0)$ 到平面 $ax + by + d = 0$ 的距离。

4. 求距平面 $x + y + z = 0$ 距离 1 的平面的方程。

5. 众所周知，在三角形paramid中，顶点处的所有平面角都是直角。如果其侧边长度为$a, b$和$c$，求其高度的长度。
