---
id: 1971-10-shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b
issue: kvant_1971_10
year: 1971
number: "10"
title: 关于二项式系数的一个性质
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 18
page_last: 22
page_labels: 16, 20
tag: 0H1J
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 84affc36b72504985e7ff01ccd14deac98d1669c155e840255d8f3b622f05bd9
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/06_shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b.md
source_content_sha256: b30baeeb85f07444e3de8a0555091d2115bfc2d487f20eab9371136a9ba1b59f
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

A·I·希尔绍夫

1970年«Kvant»第6期，发表了D. B. Fuks和M. B. Fuks的文章《生物系数的算术》。在这篇论文中，作者提出了以下问题：设$p$为素数；找出 $p$ 的幂可以整除数字 $C_{p^{n+1}}^{p^n} - C_{p^n}^{p^{n-1}}$

这个问题引起了很多读者的关注。编辑们收到了来自V. G. Gaidalovich（塔什干）、S. P. Krutik（克拉斯诺达尔边疆区斯塔尼察斯塔罗-谢尔宾斯卡亚）、九年级学生A. Merkuverev（列宁格勒）、V. V. Prlensky（莫斯科）和其他人士的来信，他们将为这个问题提供不同程度的解决方案。

我们请著名的苏联代数学家、苏联科学院通讯院士 A. I. Shirshov 详细介绍了该问题的解决方案。

小学生熟悉许多有关数学的科普书籍和文章。它们的写作尽可能简单、详细、通俗易懂，语言明亮活泼，配有引人入胜的例子和丰富多彩的图片——以引起读者的兴趣，让他们有机会轻松理解材料。

著名科学期刊上的服务器端数学文章是如何撰写的？ A. I. Shirshov 的文章引起了读者的注意，给出了科学数学表达风格的想法。就其内容而言，它是高中生可以理解的，但其编写方式与笔记（例如“苏联科学院报告”）中的笔记相同。

科学和数学风格的特点是坡度和简洁。通常，演示分为单独的步骤 - 引理，沿着这些步骤我们得出最终结果 - 定理。最初的文章总是包含问题的陈述、对引入的概念和使用的符号的解释以及对文献的引用。证明没有详细复制 - 仅概述了它们的想法和推理的一般过程。所以，你只需要手里有笔和纸就可以阅读这样的文章，还原中间的计算；理解其内容需要一定的努力和独立的反思。

数学爱好者无疑会对学习科学数学的表达方式感兴趣。

在文章[1]中，提出了$C_{p^{k+1}}^{p^k} - C_{p^{k-1}}^{p^{k-2}}$形式的数（其中$p$是素数）可以被足够大的数$p$整除。然而，这个陈述仅在情况$p=2$（来自[1]的定理5）中得到证明。

这篇笔记致力于证明一个更一般的定理。

下面考虑的所有数字$m, k, t, s$等都是自然数，$p$是素数。像往常一样，符号$(m, n)$表示数字$m$和$n$的最大公约数。我们将使用符号$[k, s]_n$来表示所有自然数$t$的乘积，使得$k \leq t \leq s$和$(t, n)=1$；在-

⟦folio 20⟧

注意到
$$1(p^{k-1}-1) \cdot 2(p^{k-1}-2) \dots \frac{1}{2}(p^{k-1}-1) \frac{1}{2}(p^{k-1}+1) = [1, p^{k-1}]_p,$$

我们可以写：
$$[p^k - p^{k-1}, p^k]_p = [1, p^{k-1}]_p + p^{2k-1}(p-1)[1, p^{k-1}]_p \cdot \frac{1}{2} \left\{ \frac{2}{1(p^{k-1}-1)} + \dots \right\} + p^{4k-2}Q =$$
$$= [1, p^{k-1}]_p + \frac{1}{2} p^{2k-1}(p-1)[1, p^{k-1}]_p \times$$
$$\times \left\{ \frac{1}{1(p^{k-1}-1)} + \dots + \frac{1}{(p^{k-1}-1)1} \right\} + p^{4k-2}Q,$$

这就是 lemmy 在 $p > 2$ 处证明的。
根据相同的方案考虑情况$p = 2$。
引理 12.

$$1^2 + 2^2 + \dots + (p-1)^2 + (p+1)^2 + \dots + (p^{k-1}-1)^2 =$$
$$= \frac{1}{6} p^{k-1}(p^{k-1}+1)(2p^{k-1}+1) - p^k L, \quad p > 2$$
（所有与 $p$ 互质的数字都写在左侧）。
证明。在表格中表示左侧就足够了
$$\sum_{i=1}^{p^{k-1}} i^2 - p^2 \sum_{i=1}^{p^{k-2}} i^2$$

并根据引理 1 计算两个总和。
定理。下面的等式是公平的：
$$C_{p^k}^{p^{k-1}} - C_{p^{k-1}}^{p^{k-2}} = p^{3k-1} R, \quad p > 3;$$
$$C_{3k}^{3k-1} - C_{3k-1}^{3k-2} = 3^{3k-2} S;$$
$$C_{2k}^{2k-1} - C_{2k-1}^{2k-2} = 2^{3k-3} T,$$

其中 $k \geqslant 3$ 和 $R, S, T$ 是整数。
该定理的证明是通过顺序使用引理9、11、6、12、2来进行的。

评论。从定理的证明中还可以看出，定理中表示的数字$S$和$T$分别不能被3和2整除。作者不知道一般情况下情况如何——数字$R$是否能被$p$整除。

引用文献

1. Fuchs D. B.，Fuchs M. B.，biomp 系数算术。 «Kvant»第6期，1970年，第17-25页。
2. Sominsky I.S.，数学归纳法。 M.，Fizmatgiz，1961。
3. Egorov A.A.，模数比较和余数算术。 «Kvant»第5期，1970年，第27-33页。

编者注。作为读者于。 Trakhtman（第聂伯罗彼得罗夫斯克）告诉我们，他设法获得了某些数字，其中定理中出现的数字$R, S, T$分别不能被$p, 3, 2$整除。然而，这个结果是用小学生不熟悉的术语表述的，并且是通过不平凡的手段证明的。
