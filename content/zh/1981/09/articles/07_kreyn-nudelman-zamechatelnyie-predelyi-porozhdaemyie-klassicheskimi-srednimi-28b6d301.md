---
id: 1981-9-kreyn-nudelman-zamechatelnyie-predelyi-porozhdaemyie-klassicheskimi-srednimi-28b6d301
issue: kvant_1981_9
year: 1981
number: "9"
title: 经典平均值产生的显着限制
authors:
  - Крейн М. Г.
  - Нудельман А. А.
rubric: osnovnye-stati
page_first: 15
page_last: 16
page_labels: 13-14
tag: UQWU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2206a578cb99b2d683a4f433d1397419feca3898ec79c59c34290119d621a817
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/07_kreyn-nudelman-zamechatelnyie-predelyi-porozhdaemyie-klassicheskimi-srednimi-28b6d301.md
source_content_sha256: ec705c66a1716c888516b689b15b093d9c259f8e7f7158bc89e756876cd0a9d2
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

由经典平均值生成的精彩背景

对于两个正数$a$和$b$，众所周知，$\frac{a+b}{2}$称为算术平均，$\sqrt{ab}$称为几何平均。比这些平均值更不常见的是调和平均值 $\frac{2ab}{a+b}$（例如，它等于机枪手以 $a$ 速度完成前半程行程、后半段行程为 $b$ 速度的平均速度）。每个平均值都位于数字 $a$ 和 $b$ 之间（请确保这一点）。

她的等式的有效性很容易验证

$$\frac{2ab}{a+b} < \sqrt{ab} < \frac{a+b}{2}$$

对于任何正 $a \neq b^*$。

我们将在这里处理下一个问题。设给定的两个正数$a$和$b$、$a < b$。计算这些数字的一对平均值后，我们得到数字 $a_1$ 和 $b_1$。然后，对于数字 $a_1$ 和 $b_1$，我们计算相同的平均值 - 我们得到数字 $a_2$ 和 $b_2$。我们将与他们重复相同的程序等等。结果，我们得到序列$(a_n)$和$(b_n)$。

例如，取几何平均值和算术平均值，从数字 1 和 3 开始，我们得到

$$a_1 = \sqrt{3} \approx 1.732050808, \quad b_1 = 2;$$
$$a_2 \approx 1.861209718, \quad b_2 \approx 1.866025404;$$
$$a_3 \approx 1.863616006, \quad b_3 \approx 1.863617561;$$
$$a_4 \approx 1.863616784, \quad b_4 \approx 1.863616784;$$
ETC。

我们看到，在我们的示例中，序列 $(a_n)$ 和 $(b_n)$ 收敛得非常快。会一直这样吗？事实证明，这样的序列总是有一个共同的极限——这相对容易证明。但如何找到这个极限值呢？

算术调和平均值

我们将从所选择的均值对是调和平均数和算术平均数的情况开始；因此，序列 $(a_n)$ 和 $(b_n)$ 的项由以下公式定义

$$a_{n+1} = \frac{2a_nb_n}{a_n+b_n}, \quad b_{n+1} = \frac{a_n+b_n}{2}$$

($n=0, 1, 2, \dots; a_0=a, b_0=b$).

鄂木斯克学校在第二届奥林匹克团体赛上提出了寻找它们共同极限的问题（«Kvant»，1979年，第12号）。

由不等式(1)可得

$$a < a_n < a_{n+1} < b_{n+1} < b_n$$

也就是说，序列$(a_n)$返回“朝向”杀死序列$(b_n)$。

因此，两个序列都是单调且有界的；因此，根据 Weierstrass 定理（代数和分析原理 9，第 32 段），它们有一个极限 $\alpha = \lim_{n \to \infty} a_n, \beta = \lim_{n \to \infty} b_n$。传递到等式 (2) 之一的极限，我们得到

$$\beta = \lim_{n \to \infty} b_{n+1} = \lim_{n \to \infty} \frac{a_n+b_n}{2} =$$
$$= \frac{1}{2} \left( \lim_{n \to \infty} a_n + \lim_{n \to \infty} b_n \right) = \frac{1}{2} (\alpha + \beta),$$

由此$\alpha = \beta$：序列$(a_n)$、$(b_n)$有一个共同的极限。该极限称为数字 $a$ 和 $b$ 的算术调和平均值。我们去找他吧。来自 (2)

⟦folio 14⟧

$$a_{n+1} \cdot b_{n+1} = a_n \cdot b_n = \ldots = a_1 b_1 = ab,$$
因为
$$a^2 = \left( \lim_{n \to \infty} a_n \right)^2 = \lim_{n \to \infty} a_n \times \lim_{n \to \infty} a_n = \lim_{n \to \infty} a_n \times b_n = ab,$$
在哪里
$$\alpha = \sqrt{ab} = \beta,$$
（算术加里昂平均值与几何平均值一致）。

练习 1. 证明 $b_n - a_n < \frac{b-a}{2^n}$。

因此，序列$(a_n)$和$(b_n)$足够快地收敛到$\sqrt{ab}$。因此，它们可用于平方根的近似计算。要计算$\sqrt{c}$，您需要从数字$a$和$b$开始序列$(a_n)$，$(b_n)$，使得$c = ab$（例如，$a = 1, b = c$），并且这些因素之间的差异越小，过程收敛得越快（例如，计算$\sqrt{56}$最好不要$a = 1$、$b = 56$、$a = 7$、$b = 8$）。很容易验证序列$(a_n)$和$(b_n)$是由公式得到的
$$b_{n+1} = \frac{1}{2} \left( b_n + \frac{c}{b_n} \right), a_{n+1} = \frac{c}{b_n}.$$
为了说明$\sqrt{12}$的计算，放入$b = 4$。我们得到$b_1 = \frac{1}{2} \left( 4 + \frac{12}{4} \right) = 3,5$，$b_2 \approx 3,464285715$，$b_3 \approx 3,464101620$，$b_4 \approx 3,464101615$，然后所有符号都稳定了：
$$\sqrt{12} \approx 3,464101615.$$

算术-几何平均 十四岁的 Carl Friedrich Gauss*) 从数值例子中发现，当使用几何平均和算术平均计算序列 $(a_n)$ 和 $(b_n)$ 时：
$$a_{n+1} = \sqrt{a_n b_n}, b_{n+1} = \frac{a_n + b_n}{2}$$

($n = 0, 1, 2, \ldots; a_0 = a, b_0 = b$) 这些序列与最近的序列很快收敛。

*) 读者可以在 S. Gindikn“Carl Friedrich Gauss”（«Kvant»，1977 年，第 8 期）的文章中找到“数学家之王”的传记以及有关他的科学活动的有趣信息。

练习2.证明序列(3)的极限的存在性和重合性。

这个一般极限称为数字 $a$ 和 $b$ 的算术几何平均值，并用 $\mu(a, b)$ 表示。通过 $a$ 和 $b$ 找到 $\mu(a, b)$ 的显式表达式并不容易。它首先是由高斯通过使用所谓的椭圆间目标的性质进行令人难以置信的敏锐和熟练的解剖和变换而获得的。让我们在没有证明的情况下呈现这个表达式*)：

$$\mu(a, b) = \frac{\pi}{2} \int_0^{\pi/2} \frac{dx}{\sqrt{a^2 \sin^2 x + b^2 \cos^2 x}}.$$

几何-Gharionch 平均值

如果我们使用语法和几何平均值构造序列 $(a_n)$ 和 $(b_n)$：
$$a_{n+1} = \frac{2a_n b_n}{a_n + b_n}, b_{n+1} = \sqrt{a_n b_n}$$

($n = 0, 1, 2, \ldots; a_0 = a, b_0 = b$),

那么在这种情况下很容易证明它们收敛到一个共同极限。我们将其称为 $a$ 和 $b$ 的几何加利奥数，并用 $\nu(a, b)$ 表示。然而，与序列（3）相比，这里没有什么重要的，因为从（4）我们看到
$$\frac{1}{a_{n+1}} = \frac{1}{a_n} + \frac{1}{b_n}, \frac{1}{b_{n+1}} = \sqrt{\frac{1}{a_n} \cdot \frac{1}{b_n}}.$$
因为
$$\frac{1}{\nu(a, b)} = \mu\left(\frac{1}{b}, \frac{1}{a}\right),$$
或者，根据高斯公式。

*) 如果“反方向”使用此表达式，我们可以快速近似计算分母中的积分：它等于 $\frac{\pi}{2\mu(a, b)}$，并且使用序列 $(a_n)$ 和 $(b_n)$ 近似计算平均值 $\mu(a, b)$。在我们的计算机时代，这些计算可以以极高的速度和准确性进行。
