---
id: 1973-4-stolyarov-perehod-ot-odnoy-sistemyi-edinits-k-drugoy-76440b07
issue: kvant_1973_4
year: 1973
number: "4"
title: 从一种单位制过渡到另一种单位制
authors:
  - Столяров И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 55
page_labels: 52-53
tag: 7PSP
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c8a92b19476d421b620ed2bd56286bc06dea1c49462561caed9b0277abf97cb8
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/14_stolyarov-perehod-ot-odnoy-sistemyi-edinits-k-drugoy-76440b07.md
source_content_sha256: 69957247cc8c06f6da39e41ff151f3ea62cb421ea6967252d2260ac8479d2d34
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

从一种单位制过渡到另一种单位制
I·A·斯莫利亚罗夫

在解决力学和分子物理问题时，最常使用 SI 和 CGS 单位，而在解决电磁学问题时，则使用 SI 系统和基于 CGS 系统机械单位的所谓高斯单位系统。 （对于电气单位，Gausscova 单位制与 SGSE 单位制一致。）

在力学中，从一种单位制到另一种单位制的转换非常简单。所有力学方程在两种单位制中的写法都完全相同。因此，只要我们不将量的数值代入公式中，就无需考虑在解决问题时我们将使用什么单位制。为了用一种单位制规定的其他量用另一种单位制表示，只需知道表1给出的基本单位之间的对应关系即可。

表1

| 基本单位 | 在国际单位制中 | 在全球统一制度中 | SI 和 GHS 单位之间的关系 |
| :--- | :--- | :--- | :--- |
| 重量 | $k_2$（千克м） | $e$（克） | $1 \ k_2 = 10^3 \ e$ |
| 长度 | $m$（米） | $cm$（厘米） | $1 \ m = 10^2 \ cm$ |
| 时间 | $c$（第二） | $c$（第二） | |

假设力的大小用diah表示，但我们需要用牛顿来表示。如何做到这一点？

SI 系统和 CGS 系统中的单位和基本单位（力的量纲）之间的联系是相同的：$\frac{ML}{T^2}$。这里$M$代表质量单位，$L$代表长度单位，$T$代表时间单位。

$$1 \ \partial h = 1 \ \frac{2 \ \text{cm}}{c^2}, \ a \ 1 \ h = 1 \ \frac{k_2 \ \text{m}}{c^2}.$$

由于$1 \ e = 10^{-3} \ k_2$和$1 \ cm = 10^{-2} \ m$，那么

$$1 \ \partial h = 1 \ \frac{10^{-3} \ k_2 \cdot 10^{-2} \ m}{c^2} = 10^{-5} \ h.$$

另一个例子。让我们找出 Joyle 和 egro 之间的联系。

$$1 \ \partial jx = 1 \ \frac{k_2 \ m^2}{c^2}, \ a \ 1 \ эгром = 1 \ \frac{2 \ \text{cm}^2}{c^2}.$$

由于$1 \ k_2 = 10^3 \ e$和$1 \ m = 10^2 \ cm$，那么

$$1 \ \partial jx = 1 \ \frac{10^3 \ e \cdot (10^2 \ cm)^2}{c^2} = 10^7 \ эгром.$$

SI 系统和 GHS 系统都没有特殊的“热”量，但温度除外，在这两个系统中温度都是用相同的单位来测量的。因此，分子物理学中从一种单位系统到另一种单位系统的转变就像力学中一样简单。然而，有时，热量的计算不是以焦耳或出口为单位，而是以外部单位——卡路里或

⟦folio 53⟧

千卡：
$$1 \text{ кал} = 10^{-3} \text{ ккал} = 4.18 \text{ дж.}$$

当解决物理问题时，根本不会出现任何问题。他们总是使用一种单位制 - SI。其中，发光强度的变化以坎德拉为单位，照明度以阴影为单位，光通量以流明为单位。

在电磁理论中从一个系统到另一个系统的转变要困难得多。这里使用基于 CGS 系统机械单位的 SI 系统和所谓的高斯单位系统。对于电量来说，它与 SGSE 系统一致。在这些系统中，不仅数量的计量单位不同，而且大多数公式看起来也不同。这些公式包括各种数值因子（见表 2）。例如，如果在解决问题时使用高斯单位制，则库仑定律可写如下：
$$F = \frac{q_1 q_2}{\varepsilon r^2},$$
如果你使用 SI 系统，那么像这样：
$$F = \frac{1}{4 \pi \varepsilon_0} \frac{q_1 q_2}{\varepsilon r^2},$$
其中 $\varepsilon_0$ 是电常数。许多其他公式的写法也同样不同。因此，在解决涉及电或磁的问题时，有必要从一开始就确定该问题将在哪种单位制中解决。这是不同的公式在两种单位制中的样子：

| | SI | 高斯 |
| :--- | :--- | :--- |
| 库仑定律 | $F = \frac{q_1 q_2}{4 \pi \varepsilon_0 \varepsilon r^2}$ | $F = \frac{q_1 q_2}{\varepsilon r^2}$ |
| 精确电荷的强烈场 | $E = \frac{q}{4 \pi \varepsilon_0 \varepsilon r^2}$ | $E = \frac{q}{\varepsilon r^2}$ |
| 精确的电荷场电位 | $\varphi = \frac{q}{4 \pi \varepsilon_0 \varepsilon r}$（在$r \to \infty$$\varphi \to 0$） | $\varphi = \frac{q}{\varepsilon r}$ |
| 平行板电容器电容 | $C = \frac{q}{u} = \frac{\varepsilon_0 \varepsilon S}{d}$ | $C = \frac{q}{u} = \frac{\varepsilon S}{4 \pi d}$ |
| 洛伦兹力 | $F = q v B \sin \alpha$ | $F = \frac{1}{c} q v B \sin \alpha$ |
| 磁场中作用在载流导体上的力 | $F = I l B \sin \alpha$ | $F = \frac{1}{c} I l B \sin \alpha$ |
| 环形电流中心的磁场感应 | $B = \mu \mu_0 \frac{I}{2 r}$ | $B = \frac{1}{c} 2 \pi \mu \frac{I}{r}$ |
| 电磁感应定律 | $E_{\text{инд}} = - \frac{\Delta \Phi}{\Delta t}$ | $E_{\text{инд}} = - \frac{1}{c} \frac{\Delta \Phi}{\Delta t}$ |
| 带电流的无限直线导体的磁场感应 | $B = \mu \mu_0 \frac{I}{2 \pi r}$ | $B = \frac{1}{c} 2 \mu \frac{I}{r}$ |
