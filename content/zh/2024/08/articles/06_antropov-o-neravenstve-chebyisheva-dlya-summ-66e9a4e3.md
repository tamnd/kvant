---
id: 2024-8-antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3
issue: kvant_2024_8
year: 2024
number: "8"
title: 关于切比雪夫的和不等式
authors:
  - Антропов А. В.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 34
page_labels: "29"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 84a55fc1fa749bee4a18895d3f5eb519b8b66d92147bc815c82d11ae4eac7825
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/06_antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3.md
source_content_sha256: cba10298d060b51d77d8db37eda3842c379cca16dfc4cd69e02d17d440c497ef
translation_model: draft
translation_run: zh-draft-2026-11-03
translation_quality: draft
---

⟦folio 29⟧

---
running_head:
folio:
---

关于不平等
切比雪夫
对于金额
安特罗波夫

在这篇文章中我们会记住
关于显着的切比雪夫不等式，我们来谈谈它的不同变化和解释，并给出解决方案���题 M2797“量子问题”（更准确地说，让我们注意到，本质上，问题中给出的不等式是切比雪夫不等式的一个特例）。

第一个切比雪夫求和不等式。
令给定的非负数$p_1, p_2, \dots, p_n$使得$p_1 + p_2 + \dots + p_n = 1$，以及两个有序实数集$a_1 \leq a_2 \leq \dots \leq a_n$、$b_1 \leq b_2 \leq \dots \leq b_n$。然后
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n. \tag{1}$$

“什么？！这不是切比雪夫不等式！” – 读者可以利用该例外。事实上，在最佳民间传说中，以下不等式通常称为切比雪夫求和不等式。

第二个切比雪夫求和不等式。
对于有序集 $a_1 \leq a_2 \leq \dots \leq a_n$、$b_1 \leq b_2 \leq \dots \leq b_n$ 满足
$$\frac{a_1 + a_2 + \dots + a_n}{n} \cdot \frac{b_1 + b_2 + \dots + b_n}{n} \leq
\leq \frac{a_1 b_1 + a_2 b_2 + \dots a_n b_n}{n}. \tag{2}$$

容易看出，权重不等式（1）是不等式（2）的推广：只要设置$p_1 = p_2 = p_3 = \dots = p_n = \frac{1}{n}$即可。

另一方面，以下练习表明，在某种意义上，不等式（1）可以简化为不等式（2）。

练习 1. 如果 $p_1, p_2, \dots, p_n$ 是有理数，则从不等式 (2) 导出不等式 (1)。

笔记。令$p_i = m_i / m$，$i = 1, 2, \dots, n$。放松不平等（2）集
$$a_1 = a_1 = \dots = a_1 \leq a_2 = a_2 \leq \dots \leq a_n = a_n,$$
其中有$a_1$的$m_1$副本，$m_2$$a_2$的副本，依此类推。

在证明不等式（1）之前，我们将展示如何使用它来解决问题 M2797。

首先，让我们进行一般性评论。

评论。设不等式(1)均为$a_i \geq 0$和$b_i \geq 0$。那么如果在条件下我们用不等式$p_1 + p_2 + \dots + p_n \leq 1$替换等式$p_1 + p_2 + \dots + p_n = 1$，它仍然成立。

事实上，让$p = p_1 + p_2 + \dots + p_n \geq 0$（在$p_1 + p_2 + \dots + p_n = 0$的情况下，所有$p_i$都等于0，不等式很明显）。我们放入$q_i = \frac{p_i}{p}$，使得$p_1 + p_2 + \dots + p_n = 1$，写出不等式(1)，权重为$q_i$，得到
$$\frac{p_1 a_1 + p_2 a_2 + \dots + p_n a_n}{p} \cdot \frac{p_1 b_1 + p_2 b_2 + \dots + p_n b_n}{p} \leq
\leq \frac{p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n}{p}.$$

由于总和 $p_i a_i b_i$ 是非负数，并且 $p \leq 1$，乘以 $p^2$ 得出所需的：
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p \left( p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

情况$p \leq 1$也可以通过细化的方式减少到$p = 1$——通过引入附加变量$a_0 = b_0 = 0$和附加权重$p_0 = 1 - \left( p_1 + \dots + p_n \right)$。

现在让我们输入$p_i = \frac{1}{i(i+1)}$。正如提取的那样，$p_1 + p_2 + \dots + p_n < 1$对于任何$n$（实际上，$p_i = \frac{1}{i} - \frac{1}{i+1}$，因此，
$$p_1 + p_2 + \dots + p_n = \left( 1 - \frac{1}{2} \right) + \left( \frac{1}{2} - \frac{1}{3} \right) + \dots + \left( \frac{1}{n} - \frac{1}{n+1} \right) = 1 - \frac{1}{n+1}).$$

那么，通过上面的替换，
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

这就是我们需要的不平等。问题M2797解决了。

⟦folio none⟧

---
running_head:
folio:
---

大于或等于他们的数学期望的乘积：
$$\mathbb{E}f \cdot \mathbb{E}g \leq \mathbb{E}(fg).$$
(1")

如果您知道两个随机变量的相关性是什么，那么这种不等式的本质就更容易理解。相关性从 $[-1; 1]$ 获取值并测量数量的相关程度，特别是，如果数量是独立的，则它们的相关性为零，而对于高度相关的数量，相关性接近 1。

形式相关性定义如下。对于值$f$和$g$，引入系数cov($f,g$) - 这是值$f$和$g$与其平均值的偏差乘积的数学期望。并且假设值$f$和$g$之间的相关性相等
$$\frac{\text{cov}(f,g)}{\sqrt{\text{cov}(f,f)} \cdot \sqrt{\text{cov}(g,g)}}.$$
暂时引入记号$M_f = \mathbb{E}f$和$M_g = \mathbb{E}g$，我们可以写成
$$\text{cov}(f,g) = \mathbb{E}\left((f - M_f)(g - M_g)\right).$$
让我们问自己：什么时候表达式$(f - M_f)(g - M_g)$是正数？答案很明确：要么当函数$f$和$g$同时大于它们的平均值，要么当两个函数同时小于它们的平均值。通俗地说，cov($f,g$) 衡量函数的相似程度。

让我们回到不等式 (1")。事实证明，右侧和左侧之间的差等于

cov($f,g$)。真的吗，
cov($f,g$) = $\mathbb{E}\left((f - M_f)(g - M_g)\right) =
= \mathbb{E}\left(fg - M_fg - M_gf + M_fM_g\right) =
= \mathbb{E}(fg) - M_f\mathbb{E}g - M_g\mathbb{E}f + M_fM_g =
= \mathbb{E}(fg) - \mathbb{E}f \cdot \mathbb{E}g$,

其中倒数第二个等式来自数学期望的线性，最后一个等式来自$M_f$和$M_g$的定义。

事实证明，切比雪夫不等式 (1') 通常反映了有关单调函数相似性的逻辑信息。

总之，对于熟悉整数的读者，我们提出了切比雪夫不等式的连续版本。在这种情况下，不等式具有相同的概率论含义，并反映了有关单调函数相似性的相同非正式论文。

切比雪夫第三不等式（对于单调函数）。令 $f(x)u g(x)$ 为定义在区间 $[a; b]$ 上的两个非减（或两个非增）函数。然后
$$\int_a^b f(x)dx \cdot \int_a^b g(x)dx \leq \frac{1}{b-a} \int_a^b f(x)g(x)dx.$$
练习 3*。
a) 从切比雪夫积分不等式推导出切比雪夫和的不等式。
b) 从切比雪夫的和不等式导出（通过从积分和到积分的极限）积分不等式。

（关于开头，请参见第 13 页）

声称这就是黄色的结果。那为什么要和他争论呢？>

我很困惑。我不知道该说什么。最后，我回答道：“我一生都在研究光。我相信，通过混合红色和白色，不可能得到黄色——只能得到粉红色。”

所以，我去了五金店，买了一些油漆，然后带回餐厅。油漆工从二楼下来，业主也来看了。我把红色罐子放在一张旧椅子上，画家开始混合颜料。他拿了红色油漆，添加了白色——在我看来，颜色仍然是粉红色的——他又混合了一点油漆。随后，他在输入中嘟哝了一句：“我通常会用一小管红色颜料来增强效果，然后就会变成黄色。”

- 啊！ - 我说。 - 当然！如果你添加黄色，你就会得到黄色，但如果没有它，什么都不会起作用。

油漆工回去粉刷房间。

餐馆老板说：“这家伙居然敢和一个研究光一辈子的人争论！”

摘自《费曼大师，你真是个笑话！》

⟦folio none⟧

---
running_head:
folio:
---

求流数 [即导数]和半
活它等于零。
艾萨克·牛顿
...[导数] 表示否定
身体移动路径上的点
超出了他们将要旅行的距离
因为他之前的动作。
伦纳德·欧拉
所有热爱分析[数学]的人
会很高兴看到机械师
正在成为一个新的分析分支......
约瑟夫·路易斯·拉格朗日
别用你的数学来烦我
腼腆：导数就是速度！
威廉·汤姆森（开尔文）

牛顿提出了一个一般性问题：在任意给定力的作用下，自由体的速度如何变化？......这个问题......需要一个新的数学应用程序 -
专门为此目的而创建的paratha
牛顿...

阿尔伯特·爱因斯坦
...找到任意一个的复杂过程也称为微分。 ...当你越来越习惯新单词时，这个想法本身就会变得更加清晰。

理查德·费曼
