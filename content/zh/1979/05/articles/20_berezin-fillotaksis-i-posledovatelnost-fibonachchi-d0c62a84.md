---
id: 1979-5-berezin-fillotaksis-i-posledovatelnost-fibonachchi-d0c62a84
issue: kvant_1979_5
year: 1979
number: "5"
title: 叶序和斐波那契数列
authors:
  - Березин В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 55
page_labels: "53"
tag: ZFZO
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0dd6f61e7cc4ed614dfe2898bb8653ce49e9f8a3ff5532f9df6af828cbd503b4
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/20_berezin-fillotaksis-i-posledovatelnost-fibonachchi-d0c62a84.md
source_content_sha256: 2046ece6b149fd4da814c8ea9d4493bbb9570e350123356fb64fcb0a666ebacf
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

叶序和斐波那契数列

封面第一页的图可以看作是向日葵花序的简化图像，其种子一个接一个地生长，呈棋盘状。真正的向日葵花序（参见本页的图）还包含两个对数螺线族（关于这些螺旋线请阅读«Kvant»，1977年，第4期，第42页）。一族的螺旋向中心逆时针方向扭转，另一族则沿顺时针方向扭转。在丰富的语言中，两个螺旋家族的组合称为叶序（从希腊语翻译过来，意思是“叶子排列”）。

事实证明，向日葵花序中的螺旋数大约等于所谓斐波那契数列的两个相邻成员：34 和 55 或 89 和 144。

向日葵的叶序是斐波那契数列的许多意外遭遇之一。它是上世纪法国数学家爱德华·卢卡斯首次遇到的。卢卡阅读了文艺复兴时期著名数学家比萨列奥纳多（Leonardo）所著的《算盘的艺术》一书，该书以斐波那契数列的产生而闻名，并解决了列奥纳多的一个问题，卢卡组成了数列 0, 1, 1, 2, 3, 5, 8, ...，其中

$$a_n = a_{n-1} + a_{n-2}.$$

在这个序列中，我们和 seyatsas 意外地相遇了。我们假设$\alpha^2 = 1 - \alpha$。

让我们用$1 = \alpha^0$和$\alpha$来表达度$\alpha^3, \alpha^4, \alpha^5, ...$的值：

$$\alpha^3 = \alpha \cdot \alpha^2 = 2\alpha - 1,$$

$$\alpha^4 = 2 - 3\alpha,$$

$$\alpha^5 = 5\alpha - 3, \dots$$

您是否认识比率中以 $a_1$ 开头的斐波那契数列？显然，对于任何 $n$ 我们可以写出公式

$$\alpha^n = (-1)^n (a_{n-1} - a_n \alpha),$$

其中 $a_{n-1}$ 和 $a_n$ 是斐波那契数列的项。让我们用数学归纳法来证明这一点：

$$\alpha^{n+1} = (-1)^n (a_{n-1} \alpha - a_n \alpha^2) = (-1)^n (-a_n + (a_{n-1} + a_n) \alpha) = (-1)^{n+1}(a_n - a_{n+1} \alpha).$$

方程 $\alpha^2 = 1 - \alpha$ 有两个根：正 $\alpha_1 = \frac{-1 + \sqrt{5}}{2}$ 和负 $\alpha_2 = -\frac{1 + \sqrt{5}}{2}$。正如我们所见，

$$\begin{cases} (-1)^n \alpha_1 = a_{n-1} - a_n \alpha_1 \\ (-1)^n \alpha_2 = a_{n-1} - a_n \alpha_2. \end{cases}$$

求解该系统的 $a_n$，我们得到

$$a_n = \frac{1}{\sqrt{5}} \times \left[ \left( \frac{1 + \sqrt{5}}{2} \right)^n - \left( \frac{1 - \sqrt{5}}{2} \right)^n \right].$$

而且这个结果相当复杂——序列是整数，它的通项是用平方根来表示的。

如果我们计算$\lim_{n \to \infty} \frac{a_n}{a_{n+1}} = \frac{\sqrt{5} - 1}{2}$，我们会得到下一个惊喜。这就是“黄金比例”的含义（关于它，例如参见«Kvant»，1973年，第8期，第22页等）。一个美丽的物体，以这样的观察态度，令人赏心悦目。

有许多公式由斐波那契数列的成员连接起来。以下是其中一些：

$$a_{n+2} = a_0 + a_1 + a_2 + \dots + a_n + 1$$

$$a_{2n+2} = a_1 + a_3 + a_5 + \dots + a_{2n-1}$$

$$a_{2n+1} = 1 + a_2 + a_4 + \dots + a_{2n}$$

$$a_{2n-2} + 1 = a_1 - a_2 + a_3 - a_4 + \dots + a_{2n-1}$$

$$a_{2n}^2 = a_1 a_2 + a_2 a_3 + \dots + a_{2n-1} a_{2n}$$

$$a_{2n-1} = a_n^2 + a_n^2 - 1.$$

尝试证明它们。

您可以在 N. N. Vorobyov 的半部分和间断性著作《斐波那契数列》（M.，“Hayka”，1978）中阅读有关斐波那契数列的内容。关于叶序 - 在另一本有趣的书中：G. S. M. Coxter“几何导论”（M.，“Hayka”，1966）。

V·贝雷津
