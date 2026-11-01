---
id: 1980-6-byistryiy-ploschad-segmenta-parabolyi-neylya-9d6d3581
issue: kvant_1980_6
year: 1980
number: "6"
title: 尼尔抛物线一段的面积
authors:
  - Быстрый И. М.
rubric: osnovnye-stati
page_first: 16
page_last: 16
page_labels: "14"
tag: V8LA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a220e59b09bec66b827225a7c5437e893b1b4f0b4e751e808c965b91dcee7a4e
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/06_byistryiy-ploschad-segmenta-parabolyi-neylya-9d6d3581.md
source_content_sha256: d7766c52de411272b9a32de330b210da952b0d2cf323b56066e07a255e035116
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

I·比斯特里

尼尔抛物线一段的面积

1657年，牛津大学二十岁的学生威廉·尼尔（William Neil，1637-1670）发现了“半三次抛物线”$y = a^3\sqrt{x^2}$的弧长。这一发现让同时代的人，为了纪念这位英年早逝的天才数学家，将半三次抛物线称为尼尔抛物线。

如今，尼尔抛物线不仅可以在大学分析课程中找到，而且可以在学校教科书中找到*)。最近，在一次针对申请人的讲座上，我收到了以下说明：

如何求由曲线$y = 3\sqrt{x^2}$组成并在点$x = -8$相切的图形的面积？

这就是我当时的回答。

尽管这项任务很简单，但它与识别困难相关。

第一个困难是找到尼尔抛物线的切线

$$f_1(x) = 3\sqrt{x^2}$$

在点$x = -8$。众所周知，正切方程由以下公式确定

$$y - f_1(-8) = f'_1(-8)(x + 8).$$

这里

$$f_1(-8) = 12,$$

*) “代数和分析原理 9”，问题 438、4746，“代数和分析原理 10”，问题 393a。

$$f'_1(-8) = 3\left(\frac{2}{3}\right)' \mid_{x = -8} = -3 \cdot \frac{2}{3}x^{-1} \mid_{x = -8} = 2 \cdot (-8)^{-1/3}.$$

这意味着导数不存在（因为表达式$(-8)^{-1/3}$没有意义），因此曲线（1）的切线也不存在。

同时，从图中可以明显看出，选择是错误的：直线$(AB)$是切线！怎么了？如何求切线的斜率？重点是这个公式

$$(\sqrt[n]{x^m})' = \left(x^{\frac{m}{n}}\right)' = \frac{m}{n}x^{\frac{m}{n}-1},$$

对于 $x \geq 0$ 为真，但不适用于此处。要计算导数（$x < 0$），您应该使用以下公式

$$(\sqrt[n]{x^m})' = \frac{m}{n}\frac{\sqrt[n]{x^m}}{x},$$

$x \neq 0, n \in \mathbb{N}, m \in \mathbb{Z},$

（当然，这也适用于正$x$）。根据它我们有

$$f'_1(-8) = (3\sqrt{x^2})' \mid_{x = -8} = -3 \cdot \frac{2}{3}\frac{\sqrt[n]{(-8)^2}}{(-8)} = -1.$$

将$f_1(-8) = 12$和$f'_1(-8) = -1$代入等式(2)，得到所需的正切方程：

$$y = 4 - x.$$

练习 1. 找到直线 $f_1(x) = 3\sqrt{x^2}$ 和 $f_2(x) = 4 - x$ 的交点。

既然知道了点$B$的横坐标，就很容易求出线性三角形AOB的曲线面积了。如何
