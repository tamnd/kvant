---
id: 1970-8-chimev-o-dvuh-deystviyah-s-deystvitelnyimi-chislami-f30f9016
issue: kvant_1970_8
year: 1970
number: "8"
title: 关于实数的两次运算
authors:
  - Чимев К.
rubric: raznoe
page_first: 58
page_last: 59
page_labels: 56-57
tag: S6ZL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 99167ce9c2c5939e0ca35fe849b599c3d2f4ddd6de1e0879c8e3b1fc1fb4aafc
prompt_sha256: draft-1
translated_from: content/ru/1970/08/articles/13_chimev-o-dvuh-deystviyah-s-deystvitelnyimi-chislami-f30f9016.md
source_content_sha256: f91ff851b3353e3631ea4af12e4b5f94382f92ba3f8c9bffa16f50a8f28dd9d3
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

数量$a \oplus b$、$(a \oplus b) \oplus c$、$b \oplus c$、$a \oplus (b \oplus c)$。从该表可以清楚地看出，等式 (1) 对于任何实数 $a, b, c$ 都有效。

因此，我们可以谈论三个实数$a \oplus b \oplus c$的“和”，定义为$a \oplus (b \oplus c)$或等价地定义为$(a \oplus b) \oplus c$。仔细观察表 1，我们得出结论：$a \oplus b \oplus c = \max(a, b, c)$。

“乘法”的结合性，即对于任何实 $a, b, c$ 等式都有效

$$(a \otimes b) \otimes c = a \otimes (b \otimes c)$$

或者，相同的是，读者将独立检查等式 min $(\min(a, b), c) = \min(a, \min(b, c))$，就像我们确信“加法”的结合律一样。

现在让我们建立“乘法”相对于“加法”的分配律：

$$(a \oplus b) \otimes c = (a \otimes c) \oplus (b \otimes c),$$

(2) 可以写成以下形式

$$\min(\max(a, b), c) = \max(\min(a, c), \min(b, c))$$.

为此，编译表 2 就足够了，从中可以清楚地看出，对于任何三个实数 $a, b, c$，等式 (2) 确实成立。

众所周知，对于普通算术运算，加法相对于乘法的分配律并不适用：等式 $(ab) + c = (a + c) \times (b + c)$ 并不适用于所有实数。但对于我们引入的“加法”和“乘法”运算，这种分配性也是成立的：

$$(a \otimes b) \oplus c = (a \oplus c) \otimes (b \oplus c).$$

通过检查任何实数$a, b, c$的最大值$(\min(a, b), c) = \min(\max(a, c), \max(b, c))$，读者将确信这一点。

有趣的是，“加法”和“乘法”还具有普通实数算术中未观察到的其他属性：

$$a \oplus a = a, a \otimes a = a;$$

$$a \otimes (a \oplus b) = a, a \oplus (a \otimes b) = a.$$

这些关系直接来自操作$\oplus$和$\otimes$的定义。

⟦folio 57⟧

大家都知道，每个实数$a$都可以分配一个相反的数，即数$-a$。我们将$a$相反的数设为符号$a$。例如：$\overline{2,5} = -2,5; \overline{-V^2} = \sqrt{2}; \overline{0} = 0$。

奇怪的是，“加法”和“乘法”的运算竟然与取相反数的运算有关：

$$\overline{a \oplus b} = \overline{a} \otimes \overline{b}; \overline{a \otimes b} = \overline{a} \oplus \overline{b}$$

(6)（在一般算术中，这些公式也是不正确的！）。

自己证明这些公式。

总之，尝试自己解决以下问题：

1. 验证对于 $n \geq 2$ 任意实数 $a_1, \ldots, a_n$
   $a_1 \oplus \ldots \oplus a_n = \max(a_1, \ldots, a_n), a_1 \otimes \ldots \otimes a_n = \min(a_1, \ldots, a_n)$.

2. 匹配正确吗？
   $c \otimes (a \oplus b) = (c \otimes a) \oplus (c \otimes b), c \oplus (a \otimes b) = (c \oplus a) \otimes (c \oplus b)?$

3. 证明对于任意实数 $a, b, c$ 等式
   $\min [\min(a, c), \min(\max(a, b), c)] = \min(a, c)$并使用操作$\oplus$和$\otimes$写入。此后如何才能立即确信其有效性？

4. 令 $a, b, c$ 为任意实数。求一个简单的数量表达式
   $\min[a, -\max(\min(a, b), \max(a, c))]$.

5. 对于任何实数 $a, b, c$ 等式为真
   $(a \oplus b) \otimes (a \oplus b \oplus c) = a \otimes [c \otimes (c \oplus b)]?$

6. 是否有可能找到一个实数$x$使得
   $\max [\min(a, \max(a, b), x)] = b$?

以下是从 Matematika 杂志的竞赛部分摘取的几个问题。

1. 有些王国、有些州有好几个城市，而且它们之间的距离成对都不同。一天早上，每个城市都会起飞一架飞机，飞往最近的邻近城市。

任何一个城市都会有不止一架飞机吗？

2. 证明;如果 $a, b, c$ 是三角形的边长，$l_a, l_b, l_c$ 是内角平分线的长度，那么
   $$\frac{l_a}{a} + \frac{l_b}{b} + \frac{l_c}{c} \leq \frac{p^2}{2S}$$

其中$p$是半周长，$S$是三角形的面积；等号仅适用于等边三角形。

A·马米耶夫

3. 证明如果实数$a$是方程的根
   $2(x^2 + x)\sin 2x + (2x + 2 - x^3)\cos 2x = x^3 + 2x + 2$,
那么这个数满足不等式$|a| < 1$。

B·佩特科夫

4. 设凸多边形平面上有一点，该点具有以下性质：通过该点绘制的任何直线都将该多边形分成相等的两部分。那么证明这个多边形是中心对称的。

P·格罗兹丹诺夫

5. 苍蝇不停地沿着一个圆柱形锡罐上底的圆周，以匀速向一个方向攀爬，其高度为底直径$2r$的4倍。在某个时刻，从罐子表面距离丈夫最远的点开始，面粉开始沿着路径移动，并以与面粉速度相同的恒定速度沿着罐子表面爬升（并且不会停止）。求该路径可以超过面粉的最短路径的长度。

I·迪莫夫斯基
