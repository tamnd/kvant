---
id: 1990-9-shulikovskaya-neravenstvo-koshi-i-obemyi-8bc85430
issue: kvant_1990_9
year: 1990
number: "9"
title: 柯西不等式和体积
authors:
  - Шуликовская В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 67
page_last: 68
page_labels: 65-66
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f6ad4b43b72830a6e6c344aab35efdb25110425674e3b4d75820a5a343b94326
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/21_shulikovskaya-neravenstvo-koshi-i-obemyi-8bc85430.md
source_content_sha256: 6e71452fb6d0639b4b2feb45aa5017ee40e7790243b95bc312e7ad861929cbc5
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 65⟧

柯西不等式和体积

V·舒利科夫斯卡娅

本期杂志发表的文章“数值平均值和几何”提供了不等式$\frac{a+b}{2} \geq \sqrt{ab}(a>0, b>0)$的几个几何证明。

这篇笔记的作者是一名 11 年级的学生，他提供了这种不等式的另一个证明，然后将其推广到空间的情况。

令 $a$ 和 $b$ 为正数，并且（用于定义）$a \geq b$。

考虑一个边长为 $a$ 和 $b$ (图 1) 的矩形。让我们对角度 $A$ 进行除角运算。显然，等边直角三角形$ABL$和$AKD$的面积之和不小于矩形$ABCD$的面积。这就是为什么

$$\frac{a^2+b^2}{2} \geq ab.$$

让我们通过放置$a^2=x$，$b^2=y$来重写不等式。结果我们得到

$$\frac{x+y}{2} \geq \sqrt{xy}.$$

类似的推理可以在三维空间中证明并证明不等式

$$\frac{a^3+b^3+c^3}{3} \geq abc (0 < a \leq b \leq c),$$

由此，通过替换$a^3=x$、$b^3=y$、$c^3=z$，我们得到替代不等式

$$\frac{x+y+z}{3} \geq \sqrt[3]{xyz},$$

意思是三个非负数的算术平均值不小于它们的几何平均值。为了证明 (1)，请考虑一个具有边 $BB'=a$、$AB=b$、$BC=c$ (图 2) 的长方体$ABCDA'B'C'D'$。让我们画出以$B$为顶点的平行六面体的三角形角的平面角的二等分，并构造四边形帕拉米德$BRCQS$、$BAPTK$和$BB'VZU$。

⟦folio 66⟧

---
running_head:
folio:
---

这些primades覆盖了这些平行六面体，并且（如果$a, b, c$中的数字不同）甚至“爬出”平行六面体的边界之外，使得这些平行六面体的体积之和，即$\frac{a^3}{3} + \frac{b^3}{3} + \frac{c^3}{3}$不小于平行六面体的体积。所以，$\frac{a^3 + b^3 + c^3}{3} \geq abc$。

一般柯西不等式
$$\frac{x_1 + x_2 + \ldots + x_n}{n} \geq \sqrt[n]{x_1 x_2 \ldots x_n},$$

其中$x_i \geq 0$，可以在$n$维空间中使用类似的构造来证明。

我们建议熟悉$n$维空间概念的读者进行适当的推理。为此，我们应该考虑一个具有边 $a_1 \leq a_2 \leq \ldots \leq a_n$ 的长方体，并构造具有体积的 $n$ 维 Paramidas
$$\frac{a_1^n}{n}, \frac{a_2^n}{n}, \ldots, \frac{a_n^n}{n},$$
覆盖平行六面体。结果，我们得到了不等式
$$\frac{a_1^n + \ldots + a_n^n}{n} \geq a_1 a_2 \ldots a_n,$$
由此很容易得到不等式(2)。
