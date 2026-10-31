---
id: 1972-7-myakishev-reshenie-zadach-po-elektrostatike-elektroemkost-06d3934d
issue: kvant_1972_7
year: 1972
number: "7"
title: 解决静电问题。 (电量)
authors:
  - Мякишев Г. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 52
page_labels: 48, 50
tag: WLAI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: dafd44701b033073b797a4d7efe02f32504b0cefee95af3fa7e5f4fc9ae4c075
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/14_myakishev-reshenie-zadach-po-elektrostatike-elektroemkost-06d3934d.md
source_content_sha256: 74b934ab6d4052c760ebb3e513e27a781592ab0802d2199e570e60b9bbc02200
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

解决静电问题
（电容）

G.雅.米亚基舍夫

电容是静电部分的最后一个主题。在解决该主题的问题时，可能需要从静电学研究中获得的所有信息：电荷守恒、场强和电势的概念、静电场中导体的行为、电介质场强的变化、能量守恒定律。因此，这些任务显然是象征性的。但是，如果前面的概念很好理解，那么在解决电容问题时应该不会遇到任何特殊困难。

电容概念的引入是基于这样一个事实：当向导体施加电荷 Q 时，导体的所有点都获得相同的电势 φ。电荷与电势的比率不取决于电荷量，称为单个导体的电容：

$$C = \frac{Q}{\varphi}.$$

SGSE 系统中单个导电球（真空中）的容量等于其半径：

$$C = R.$$

SI 系统中电介质中球体的电容等于：

$$C = 4 \pi \varepsilon_0 R.$$

最有趣的是两个导体系统的电容，其电荷大小相等且符号相反。这样的系统称为冷凝器

sator，其容量等于：

$$C = \frac{Q}{\Delta \varphi},$$

其中 Q 是电容器极板之一的电荷，Δφ 是极板之间的电势差。电容器的电容实际上与周围物体无关。

对于平行板电容器

$$C = \frac{\varepsilon S}{4\pi d} \left( \Gamma C \partial\right); \quad C = \frac{\varepsilon \varepsilon_0 S}{d} \left( \mathrm{C I}\right).$$

这里S是板的面积，d是板之间的距离。

电容器的能量可以使用以下三个公式之一计算：

$$\Pi = \frac{Q \Delta \varphi}{2} = \frac{Q^2}{2C} = \frac{C (\Delta \varphi)^2}{2},$$

也就是说，对于三个值中的任何一对，值都是 Q、C、Δφ。并联电容器时，它们的电容相加：

$$C = \sum_i C_i.$$

串联时，电池电容的倒数等于各个电容器电容倒数的总和：

$$\frac{1}{C} = \sum_i \frac{1}{C_i}.$$

让我们回顾一下基本概念和公式，现在继续解决具体问题。

问题1. 已充电的平行板电容器的极板交替接地。这会导致电容器放电吗？

解决方案和解答已确定，

⟦folio 50⟧

$C_4$不带电，其容量可以忽略不计。简化的等效电路如图 5 所示。结果是一个由三个并联支路组成的电路，其中两个支路包含两个串联的电容器。系统总容量

$$C = C_1 + \frac{C_2 C_3}{C_2 + C_3} + \frac{C_5 C_6}{C_5 + C_6} = 2C.$$

问题 4. 两个容量为 $C_1$ 和 $C_2$ 的电容器被充电至电势差 $\Delta \varphi_1$ 和 $\Delta \varphi_2$ ($\Delta \varphi_1 \neq \Delta \varphi_2$)。证明当这些电容器并联时，它们的总静电能量减少。解释为什么能量会减少。

解决方案。连接前电容器的能量等于$\Pi_0 = \frac{1}{2} \left( C_1 \Delta \varphi_1^2 + C_2 \Delta \varphi_2^2 \right)$。连接后，电容器组的电量为$Q = Q_1 + Q_2$，电池中存储的能量为$\Pi = \frac{1}{2} \frac{Q^2}{C_1 + C_2} = \frac{1}{2} \frac{(C_1 \Delta \varphi_1 + C_2 \Delta \varphi_2)^2}{C_1 + C_2}$。能量差$\Pi_0 - \Pi = \frac{C_1 C_2}{2 (C_1 + C_2)} \times \left( \Delta \varphi_1^2 + \Delta \varphi_2^2 - 2 \Delta \varphi_1 \Delta \varphi_2 \right) > 0$。

由于将电容器与导体连接时，电荷从一个电容器流到另一个电容器，因此静电能量减少。这会在连接电容器的导体中产生热量。

对于逻辑问题

（见第28页）

1. 例如，你可以问：“你是骗子吗？”，他们也会以同样的方式回答。你也可以问：“你说的是真的吗？”，他们也会回答同样的问题。

2. 对于“我今天问你什么了吗？”这个问题第一次正确答案是“否”，第二次正确答案是“是”。还有其他问题。

3. 如果游客靠近一岸，他们会以偶数次换乘到对岸，非常低。这意味着游客会接近相对的板条：两个板条接近一个银行，第三个板条接近另一个银行。在这种情况下，穿越可以分两次飞行完成。

4. 由于五位数的各位数字之和不超过45，那么我的邻居不超过45岁。但他不能低于45岁，否则他就得说出几个五位数字，其中数字之和等于邻居的年龄。那么他今年45岁，我的彩票号码是99999。
