---
id: 1985-12-pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317
issue: kvant_1985_12
year: 1985
number: "12"
title: 有序数集和不等式
authors:
  - Пинтер Л.
  - Хегедыш Й.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 17
page_labels: 14-15
tag: MCIF
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ae9d936201055ff5fa8231441438c1834470669375632dbcf2b3f0e47f97c6f0
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/04_pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317.md
source_content_sha256: 8cd9e2e40a3bb466668d4baddc43f09e3485c43ac2595a20f5d86179497baede
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

有序数集和不等式

L.品特、I.赫格迪什

科利亚的父母将纸币放在信封里。有一天，他们拿出三个信封放在他面前。其中一个信封里装着卢布，另一个信封里装着三卢布，第三个信封里装着五卢布。父母让科利亚从一个信封中取出两张纸，从另一个信封中取出三张纸，然后从另一个信封中取出四张纸。

Kolya 应该如何选择信封才能获得尽可能多的金额，以及如何获得尽可能多的金额？求导数选择信封时的累计金额，需要将表 1 中的数字 2、3、4 按适当的顺序与问号一起放在底行中，然后将各列中的数字相乘并相加。

表1

1? 3? 5?

表1

如果科利亚想要收集尽可能多的金额，那么他必须从装有五的信封中取出四张纸，从装有三的信封中取出三张纸，并从装有卢布的信封中取出两张纸：

$$5 \cdot 4 + 3 \cdot 3 + 1 \cdot 2 = 31.$$

如果科利亚想收集尽可能多的钱，那么他就必须从装满五卢布的信封中取出尽可能多的纸片，即从装有五卢布的信封中取出两张纸，从装有三卢布的信封中取出三张纸，从装有卢布的信封中取出四张纸，即

$$5 \cdot 2 + 3 \cdot 3 + 1 \cdot 4 = 23.$$

有序三元组

一般来说，这个问题可以表述如下。让给定的正数三元组

$$a_1, a_2, a_3,$$

$$b_1, b_2, b_3.$$

我们来考虑一下金额

$$S = a_1 b_i + a_2 b_j + a_3 b_k,$$

其中 $i, j, k$ 是数字 1、2、3，按什么顺序书写。如何选择这个顺序，使得总和 $S$ 成为最可能的（分别是最可能的）？

显然，如果最多的数字$a$乘以最多的数字$b$，再将数字的平均值$a$乘以数字的平均值$b$，最后将数字的名称$a$数字的名称$b$相加，然后将得到最大可能的值$S$（如果平均值数$a$的个数或数$b$的平均值相等，则该最大值$S$不是通过唯一的方法获得的）。如果最多的数字$a$乘以最多的数字$b$，平均值乘以平均值，等等，那么我们得到最大可能的值$S$。

使用这种方法，您可以简单地解决问题M762（参见«Kvant»，1982，第9号）*。

证明对于任何正数 $a, b, c$，以下不等式成立：

$$a + b + c \leq \frac{a^2 + b^2}{2c} +$$

$$+ \frac{b^2 + c^2}{2a} + \frac{c^2 + a^2}{2b} \leq \frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}. \quad (1)$$

我们首先证明第一个不等式。让我们写下两个三元组的数字

$$a^2, b^2, c^2,$$

$$\frac{1}{a}, \frac{1}{b}, \frac{1}{c}.$$

由于数字$a, b, c$是正数，因此第一个三元组的大多数数字位于第二个三元组的大多数数字上方，第一个三元组的大多数数字位于大多数数字上方

⟦folio 15⟧

第二个三。因此，对于这些三元组的总和

$$a^2 \cdot \frac{1}{a} + b^2 \cdot \frac{1}{b} + c^2 \cdot \frac{1}{c}$$

是最小的，因此

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a},$$

(2)

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b}.$$

(3)

将不等式(2)和(3)相加，可得：

$$2(a+b+c) \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a} + a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b}.$$

要获得第二个不等式 (1)，请考虑三倍数

$$a^3, b^3, c^3,$$

$$\frac{a}{abc}, \frac{b}{abc}, \frac{c}{abc}.$$

在前三个数中最多（或最多）的下面写着后三个数中最多（最小）的数。这就是为什么

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{b}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(4)

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{c}{abc} + b^3 \frac{a}{abc} + c^3 \frac{b}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(5)

将不等式（4）和（5）相加，我们得到

$$2\left(\frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}\right) \geq \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b} + \frac{b^2}{c} + \frac{c^2}{a},$$

$$+ \frac{c^2}{a} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b},$$

这就是所需要的。

练习
证明不等式：
1. $a^4 + b^4 \geq a^3 b + ab^3$.
2. $a^3 b + b^3 c + c^3 a \geq a^2 bc + b^2 ca + c^2 ab$.
3. $\frac{a^3 b}{c} + \frac{a^3 c}{b} + \frac{b^3 a}{c} + \frac{c^3 b}{a} \geq 6abc$（这里是$a > 0, b > 0, c > 0$）。
4. 如果$a_1 \geq a_2 \geq a_3 \geq a_4, b_1 \geq b_2 \geq b_3$，则$3(a_1 b_1 + a_2 b_2 + a_3 b_3) \geq (a_1 + a_2 + a_3)(b_1 + b_2 + b_3)$。
5. 若$a > 0, b > 0, c > 0$，则

$$\frac{a}{b+c} + \frac{b}{a+c} + \frac{c}{a+b} \geq \frac{3}{2}.$$

一些概括

现在给定一组 $n$ 数字

$$a_1 \geq a_2 \geq a_3 \geq ... \geq a_n,$$

$$b_1 \geq b_2 \geq b_3 \geq ... \geq b_n.$$

让我们考虑 $i$ $\sigma = a_1 b_1 + a_2 b_2 + ... + a_n b_n$ 形式的所有可能的和，其中 $i_1, i_2, ..., i_n$ 是数字 1, 2, ..., $n$ 的某种排列。

这样的和的数量是有限的，因此其中有最多的$S$和最多的$s$。报出$S = a_1 b_1 + a_2 b_2 + ... + a_n b_n$和$s = a_1 b_n + a_2 b_n - 1 + ... + a_n b_1$并不难。

让我们证明一下。首先让我们注意，对于任意四个数字 $a, b, c, d$ 使得 $a \geq b$ 和 $c \geq d$，不等式成立

$$ac + bd \geq ad + bc,$$

(*) 等于明显不等式

$$(a - b)(c - d) \geq 0.$$

此后，替换我们的陈述就被证明是毫无困难的。事实上，如果在某个和$\sigma$中存在以下$a_e b_q$和$a_k b_p$，其中$e < k, q > p$，即$b_p \geq b_q$，那么，通过重新排列数字$b_p$和$b_q$，我们得到一个不小于$\sigma'$的和，其中$a_e b_p$和$a_k b_q$。

不断地进行这样的排列，我们得到总和$S$，因此$S \geq \sigma$。

类似地，如果$b_q \geq b_p$，那么交换这些数字，我们得到一个不大于$\sigma$的和。

由于经过多次排列，我们可以得出总和 $s$，然​​后是 $\sigma \geq s$。

因此，对于任意总和 $\sigma$

$$s \leq \sigma \leq S,$$

(B)

此外，只有当集合$a_1, ..., a_n, \text{ либо } b_1, ..., b_n$之一包含相同的数字时，相等（B）才可能。

总而言之，我们可以制定一个证明不等式的通用方法：如果数字集合$a_1, a_2, ..., a_n$和$b_1, b_2, ..., b_n$是等序的（即从$a_k \geq a_l$得出$b_k \geq b_l$），则$a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n \geq a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n$，（这里$i_1, i_2, ..., i_n$是数字1, 2, ..., $n$的任意排列）。
