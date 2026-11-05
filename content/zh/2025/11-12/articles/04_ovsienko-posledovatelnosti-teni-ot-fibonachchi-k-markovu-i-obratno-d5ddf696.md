---
id: 2025-11-12-ovsienko-posledovatelnosti-teni-ot-fibonachchi-k-markovu-i-obratno-d5ddf696
issue: kvant_2025_11-12
year: 2025
number: 11-12
title: 阴影序列：从斐波那契到马尔可夫并返回
authors:
  - Овсиенко В. Ю.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 13-14
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5508d27efbc080343c4f7ae7a607a219eefd79612066e347294061fba3ddd31a
prompt_sha256: draft-1
translated_from: content/ru/2025/11-12/articles/04_ovsienko-posledovatelnosti-teni-ot-fibonachchi-k-markovu-i-obratno-d5ddf696.md
source_content_sha256: f225225f81e9f57c981016301f7777c523463b0d7edbc93e71cc49d7f784e1e2
translation_model: draft
translation_run: zh-draft-2026-11-05
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

序列标签：
从斐波那契到马尔可夫
然后回来

V·奥夫辛科

在本文中我们讨论-
罗马循环整数
序列并设置
没什么问题。如果这样的序列会怎样
实际上还有另一个整数
接下来的顺序
像我这样的？让我们证明在这样的情况下
提出问题，真实情况是
意义。但是，我们不承诺索赔
确实，这样的黑暗绝对是可以找到的
任何顺序都可以，尽管
nam 尚未意识到任何反制措施
皮梅拉

所以，对于每个序列我们
让我们尝试至少再比较一个。
这是否意味着已知的数量
顺序和注册的
在线整数百科全书中的信息
OEIS 序列（子
有关百科全书的更多信息，请参阅文章[1]），
目前已超过 350,000 人，将翻倍
夏？答案是否定的，原因有二：
nam：一方面，众所周知
序列也可能是由于
已知序列，另一方面
手，一个序列可以-
可能有几个阴影。

转到序列-
那么我们需要对偶的概念
数字。关于这些数字有足够的细节
lah 在书中有描述[2]。

Stratia 是修订版
stats “整数的影子序列：从
斐波那契到马尔可夫并返回》，出版者
诺亚在数学智能杂志上
2023 年。

DOI: https://doi.org/10.4213/kvant20251102

双数

考虑一对数字$A = (a, \alpha)$，
$a, \alpha \in \mathbb{R}$，作为以下形式的表达式

$$A = a + \alpha \varepsilon,$$

其中 $\varepsilon$ 是某个符号。如果 $\varepsilon$ 是最小值
单位，即$\varepsilon^2 = -1$，那么$A$是复数
数字。如果$\varepsilon$满足条件
$\varepsilon^2 = 0$，则$A$称为$\delta$实数。
而且，符号$\varepsilon$本身不为零。
在对偶数集上我们可以引入
简单的算术运算：

$$(a + b\varepsilon) + (c + d\varepsilon) = (a + c) + (b + d)\varepsilon,$$

$$(a + b\varepsilon) - (c + d\varepsilon) = (a - c) + (b - d)\varepsilon,$$

$$\cdot (a + b\varepsilon) \cdot (c + d\varepsilon) = ac + (ad + bc)\varepsilon,$$

$$\frac{a + b\varepsilon}{c + d\varepsilon} = \frac{a}{c} + \frac{bc - ad}{c^2}\varepsilon (c \neq 0).$$

正如我们所见，双数运算
lamami 在很多方面都与 lamami 的操作类似
复数。同样你可以
进一步跟进。数字$a - b\varepsilon$可以是
考虑对偶数的共轭
$a + b\varepsilon$。共轭数的乘积
是一个实数：

$$(a - b\varepsilon)(a + b\varepsilon) = a^2.$$

打个比方
对于复数，我们得到 $a$
很自然地要考虑双路模块
数字$a + b\varepsilon$，并将数字本身写成三
角度形式$a + b\varepsilon = a(1 + \varepsilon\varphi)$，
其中 $\varphi$ 是对偶数的参数。
那么当双数相乘时，
写成三角函数形式，
像复数一样，模数

⟦folio 13⟧

---
running_head:
folio:
---

马尔可夫数可以使用无限二叉树进行排序。在平面上画一棵树将其切割成无数个区域，每个区域都有一个相应的马尔可夫数。局部（即每个顶点的邻域）图片看起来如图 1 中所示。变换 (6) 对应于 图 2 中所示的分支。生成的马尔可夫树如 图 3 中所示。

让我们考虑图上的极端分支——那些以数字1和2的区域为界的分支。请注意，马尔可夫数的相应三元组包含奇数斐波那契数$(1, F_{2k-1}, F_{2k+1})$和奇数佩尔数$(2, P_{2k-1}, P_{2k+1})$——序列A001519和A001653。事实上，马尔可夫数的不同子序列和排列构成了OEIS中的十个序列（参见A002559和相关序列）。

马尔可夫序列阴影

我们的目标是除了在马尔可夫数上投射阴影之外做任何事情，但将阴影映射的一般结构应用于它们已经非常诱人了。这样做非常简单。让我们选择对偶数 $(A_1, B_1, C_1)$ 的初始三元组：

$$A_1 = 1 + \alpha_1 \varepsilon,$$
$$B_1 = 1 + \beta_1 \varepsilon,$$
$$C_1 = 1 + \gamma_1 \varepsilon,$$

其中 $\alpha_1, \beta_1, \gamma_1$ 是任意整数。然后应用到$A = a + \alpha \varepsilon, B = b + \beta \varepsilon, C = c + \gamma \varepsilon$所有可能的变换

$(A, B, C) \mapsto (A', B, C)$，其中$A' = \frac{B^2 + C^2}{A}$，以及排列$A, B$和$C$。收集有和没有$\varepsilon$的项，我们得到

$$a' = \frac{b^2 + c^2}{a}, \quad \alpha' = \frac{2b\beta + 2c\gamma - a'\alpha}{a}. \tag{8}$$

这次不是很印度，为什么$\alpha'$整。

命题3.任意选择变换(8)的初始条件(7)，连同排列，生成整数序列$\{\alpha_n\}, \{\beta_n\} u \{\gamma_n\}$。

这种完整性得益于称为洛朗现象（参见[8]）的替换事实，它也保证了科莫萨和盖尔-罗宾逊序列的完整性。 Comosa 序列的整数性质的证明也可以在[5]中阅读。

初始值有一种选择$(\alpha_1, \beta_1, \gamma_1)$，看起来既自然又有趣：

$(\alpha_1, \beta_1, \gamma_1) = (0, 1, 1). \tag{9}$

让我们更详细地看看它。首先，很自然地取第二个和第三个元素对称的初始值，即猜测$\beta_1 = \gamma_1$。再次选择 $(\alpha_1, \beta_1, \gamma_1) = (1, 1, 1)$ 作为马尔可夫数：

$$\alpha_n = a_n, \quad \beta_n = b_n, \quad \gamma_n = c_n,$$

这不是很有趣。选择 $(\alpha_1, \beta_1, \gamma_1) = (1, 0, 0)$ 作为数字的总项。只剩下选项（9）了。 图 4 显示了马尔可夫数树及其主题。

⟦folio 14⟧

---
running_head:
folio:
---

让我们以一些观察作为结束。子序列
1,4,13,40,120,354,1031,2972,8495, ...
它作为奇数斐波那契分支的卫星出现，结果是一个著名的数列。这个非凡的序列 A238846 是斐波那契序列 $\{F_{2n+1}\}$ 和 $\{F_{2n}\}$ 的两个子序列的亮点。通过沿着树的分支从树中获得的其他子序列似乎是新的。
马尔可夫序列影子的作用是什么？它有什么意义呢？这有任何意义吗？我很想解决这个问题，但现阶段我们只能跟小熊维尼说：
– 我的问题简单而简短， –
犀牛说：
哪个更好 - 四十五
还是四十高跟鞋？ –
唉，没有什么可做的
回复
我给不了！

文学
1. A.扎博洛姆斯基。坏箭头。 – «Kvant»，2022 年，第 7 期。
2. I.M.亚格洛姆.复数及其在几何中的应用。 – M.GIFML，1963 年。
3. V. Ovsienko. A step towards cluster superalgebras. – arXiv:1503.01894, 2015.
4. V. Ovsienko and S. Tabachnikov. Dual numbers, weighted quivers, and extended Somos and Gale-Robinson sequences. – Algebras and Representation Theory, 2018, vol. 21, p. 1119–1132.
5. A·乌斯特米诺夫。索莫卡序列。 – «Kvant»，2023 年，第 8 期。
6. A. Markoff. Sur les formes quadratiques binaires indefinies. – Mathematische Annalen, 1879, vol. 15, p. 381–406.
7. M·克莱恩。 A. A. 马尔可夫的丢番图方程。 – «Kvant»，1985 年，第 4 期。
8. S. Fomin and A. Zelevinsky. The Laurent phenomenon. – Advances in Applied Mathematics, 2002, vol. 28, p. 119–144.
