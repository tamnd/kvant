---
id: 1991-7-o-sootnoshenii-mezhdu-chislami-e-i-p-98c7f95e
issue: kvant_1991_7
year: 1991
number: "7"
title: 【论数与π的关系】
authors:
  - e
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 56
page_last: 56
page_labels: "54"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1dc519d5e04d74ca135e693560f04477487e9cce1b7eb53cd4cf32c04f3997c5
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/15_o-sootnoshenii-mezhdu-chislami-e-i-p-98c7f95e.md
source_content_sha256: beb985b246bbe95c29631e2605b8cbbe5bc20b17ed09fd36a11088897ec70499
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 54⟧

---
running_head:
folio:
---

即我们得到与 $k=0$ 相同的根。类似地，对于$k=n+1$、$n+2$等，我们将得到与$k=1, 2, \dots$相同的根。因此，式(4)中的整数$k$在0至$n-1$之间变化。定理已被证明。

结果。 $n$次单位根由以下公式表示

$$\sqrt[n]{1} = \cos \frac{2k\pi}{n} + i \sin \frac{2k\pi}{n},$$

$$k = 0, 1, 2, \dots, n-1.$$

它们位于正边形 $n$ 边形的顶点，该边形内切于以原点为中心、半径为 1 的圆中。

锻炼
17. 计算根并将其画在平面上
a) $\sqrt[3]{1};$ 6) $\sqrt[3]{-1};$ c) $\sqrt[4]{i};$
d) $\sqrt[6]{-i};$ e) $\sqrt[3]{3+4i}$。
18. 解方程
a) $z^4 = z;$
b) $(x+i)^4 + (x-i)^4 = 0;$
c) $z^3 = -z.$
19. 证明所有$n$单位根都是$\varepsilon = \cos \frac{2\pi}{n} + i \sin \frac{2\pi}{n}$的幂。然后计算所有$n$单位根的$k$幂之和。

复数集合的代数封闭性
我们构造了复数集合$C$作为实数集合的分布，其中任何二次方程都是可解的。乍一看，似乎要使更高次的方程可解，需要一次又一次地扩展集合 $C$。事实证明，不需要更多的扩展。如果我们采用等式

$$a_0 x^n + a_1 x^{n-1} + a_2 x^{n-2} + \dots + a_{n-1} x + a_n = 0$$

所有系数$a_0, a_1, a_2, \dots, a_n$对任意复数进行任意程度的计数，则其所有根都属于集合$C$，因此，要求解方程（5），不需要未包含在$C$中的新数字。

该性质称为复数集合的代数封闭性。它最早由荷兰数学家阿尔伯特·吉拉德 (Albert Girard) 于 1629 年提出，直到 1799 年卡尔·弗里德里希·高斯 (Carl Friedrich Gauss) 才获得严格的证明。

练习 20*。证明如果点$z_1, z_2, \dots, z_n$是$n$边形的顶点，则方程的所有根

$$\frac{1}{z-z_1} + \frac{1}{z-z_2} + \dots + \frac{1}{z-z_n} = 0$$

位于该多边形的内部或边界上。

你好，安静！
有一天，在摆弄我的 Elektronka MK-60 微型计算器时，我成功地创建了令人惊叹的数字 $π$ 和 $e$ 的红色组合：

$$e^6 = \pi^5 + \pi^4.$$

我希望你能回应我的公式。
Alexey Rybak，十年级，VAKO“联盟”成员，Dyurtyush，巴什基尔苏维埃社会主义自治共和国。

来自编辑。
首先，我们在微型计算器上计算了方程的左侧和右侧，得到了 403.428775 和 403.428793。然后我们在 IBM/AT 计算机上计算同样的结果，得到 403.42897 和 403.42893。
