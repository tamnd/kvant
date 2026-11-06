---
id: 1991-3-o-itak-zadacha-polnostyu-reshena-eb73030e
issue: kvant_1991_3
year: 1991
number: "3"
title: ……那么，问题就彻底解决了
authors:
  - О. М.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 32
page_labels: 29-30
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4b9b20ebf315ecc4c26fd4e27e493154d1f901d62dca42c29fd93a4910266e3a
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/07_o-itak-zadacha-polnostyu-reshena-eb73030e.md
source_content_sha256: 1e1ebbb14d8ec6cb0049d3c0fcd06ddc6e5e9e4d84e761e39478202e63ea752a
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 29⟧

---
running_head:
folio:
---

其中$k = \alpha/\beta$也是比例系数。让我们针对$v$和$U$的不同值写出这个方程：

$$v_1^2 = kU_1^2(v_0 - v_1),$$
$$v_2^2 = kU_2^2(v_0 - v_2),$$

其中$v_0 = 50$ Hz，$v_1 = 1800/60$ Hz = 30 Hz，$U_1 = 220$ V，$U_2 = 127$ V。代入这些值并排除$k$，我们得到相对所需部分$v_2$的方程：

$$v_2^2 + 15v_2 - 750 = 0,$$

在哪里

$$v_2 = 21$$赫兹。

因此，通过专有格式化程序连接到网络后，风扇叶片将以一定速度旋转

$$n_2 = 21 \cdot 60 \text{ об/min} \approx 1260 \text{ об/min}.$$

奥·法蒂亚诺夫

...所以，问题彻底解决了（没有给读者的信）

M1194问题的解答发表后（«Kvant»第4期，1990年，第34页），编辑收到了几封读者来信，其中假设$E$得到了证明。戈尔伯格（列宁格勒），完善了这个问题的陈述。让我们提醒您我们正在谈论什么。这是问题的第一点（对我们来说至关重要）的表述，由 A. Azamov 编译：

M1194。 a) 从面积$S$直刃$ABCD$内的点$M$画出三角形AMB、BMC、CMD、DMA的MF、MG、MH、ME。证明四边形 EFGH 的面积$S_0$满足以下不等式：

$$\frac{3}{8} S < S_0 \leq \frac{1}{2} S.$$

E. Golberg 证明了 $S_0/S = 1 - A/2$，其中

$$A = \frac{a^2}{(a+b)(d+a)} + \frac{b^2}{(b+c)(a+b)} + \frac{c^2}{(c+d)(b+c)} + \frac{d^2}{(d+a)(c+d)},$$

并且数字 $a, b, c, d$ 等于从 $M$ 到给定直刀片的顶点 $A, B, C, D$ 的距离，并且，使用这种表示法，即 $S_0/S > 0,4$。他的假设是相对 $S_0/S$ 的确切下确界是 $\sqrt{2} - 1 = 0,41$...，当 $ABCD$ 是正方形且 $M$ 是其顶点之一时获得的值。

我们收到了来自 V. Curtoaje（罗马尼亚）的该提案的第一份证明。利用等式$a^2 + c^2 = b^2 + d^2$（$ABCD$是矩形的结果），他推导出优雅的公式$A = 1 + (a - b + c - d)^2 / (ac + bd)$。从这里开始，使用三角代换$a = l \sin \alpha$、$b = l \sin \beta$、$c = l \cos \alpha$、$d = l \cos \beta$（此处为$l = a^2 + c^2 = b^2 + d^2$），他获得了估计值$A \leq (2 + c - 1/c) / (1 + c) \leq 2(2 - \sqrt{2})$，其中$c = ctg(|\alpha - \beta|/2)$，由此得出所需的不等式。请读者还原他的图画点变换的细节。

列宁格勒第 76 学校十年级学生 I. Egorova 选择了分析证明路径。她提出了 $S_0/S$ 的表达式，与上面的类似，作为两个变量的函数：$x = d/c$ 和 $t = b/c$（回想一下 $a^2 = b^2 + d^2 - c^2$），并使用任意变量探索它的最小值。太空不允许在这里重复这项相当艰苦的研究。

让我们更详细地讨论两个几何解决方案。它们都基于等式 $S_0/S = (1 - s/S)/2$，其中 $s$ 是直刀片 $A_1B_1C_1D_1$ (图 1) 的面积，以通过 bissertis $E, F, G, H$ 的底面平行于边 $ABCD$ 绘制的直线为界（该等式在已发布的问题解决方案中给出）。在一般解决方案中，表明可以通过将点$M$放置在直刀片的顶点来增加比率$s/S$，之后不难证明在这种特殊情况下对于正方形来说它将是最大的。

⟦folio 30⟧

---
running_head:
folio:
---

《问题书«Kvant»》的原作者之一 A. Mikhailov（拉脱维亚艾兹克拉克勒）的推理不同：他改变的不是点，而是矩形。即假设$a \leq b \leq c \leq d$，他将原来的矩形ABCD替换为矩形MNCK（见图2），而$M$点不变。然后将区域$S$、$S_0$和$s$分别替换为$S' = S_{MNCK}$、$S_0' = S_{\Delta MPQ}$，其中MP和MQ是角NMC和CMK的黑底，以及$s' = NP \cdot KQ$（在图2处是区域$s'$对应的矩形） $A_1B_1C_1D_1$ 未显示）。我们必须证明$S_0/S > S_0'/S'$，即$s/S < s'/s'$。在已发布的问题解决方案中，发现$AE \leq BG$和$AF \leq DH$。因此，$LF \leq NG$，$IF \leq KH$。因此$NP \geq NG \geq NG - LE = A_1D_1$，$KQ \geq KH \geq KH - IF = A_1B_1$，这意味着

$$\frac{s'}{S'} = \frac{NP \cdot KQ}{S_{MNCK}} \geq \frac{A_1D_1 \cdot A_1B_1}{S_{ABCD}} = \frac{s}{S'}$$

这正是我们所需要的。

因此，当给定点位于矩形的顶点 (图 3) 时，仍然需要考虑这部分问题。这不再困难。让我们介绍一下 A. Mikhailov 的计算

$$\frac{S_0'}{S'} = \frac{S_{\Delta MPQ}}{S_{MNCK}} = \frac{MP \cdot MQ \cdot \sin \angle PMQ}{2 \cdot MN \cdot MK} = \frac{\sin \pi/4}{2 \cos(\pi/4 - \alpha/2)} = \frac{1/\sqrt{2}}{\cos \pi/4 + \cos(\pi/4 - \alpha)} = \frac{1}{1 + \sqrt{2} \cos(\pi/4 - \alpha)} \geq \frac{1}{1 + \sqrt{2}} = \sqrt{2} - 1,$$

其中$\alpha = \angle CMK$。仅当 $\alpha = \pi/4$ 时才实现相等，即当 MNCK 是正方形时。

很容易证明矩形ABCD与点$A$的比率$s/S$大于嵌入的ABCD矩形MNCK与点$M$的类似值。由此可见，对于固定矩形，当点 $M$ 位于其顶点时，即可实现最小 $S_0/S$（顺便说一句，这已由 G. Khotsanyan 证明），并且正如我们所见，等于 $1/(1 + \sqrt{2} \cos(\pi/4 - \alpha))$。

O.M.

修正案
在任务 M1258 的条件下（参见 1990 年«Kvant» No. 12）第 6 段）存在不准确之处。这是正确的措辞。
6) 证明对于圆上任意一组和为正的$n$数，可以得到且仅有一组$n$非负数。
提交此问题解决方案的截止日期已延长至 5 月 15 日。
