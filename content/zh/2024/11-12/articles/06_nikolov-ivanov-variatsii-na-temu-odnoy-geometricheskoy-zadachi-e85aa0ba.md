---
id: 2024-11-12-nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: 几何问题主题的变奏
authors:
  - Николов Н.
  - Иванов А. Д.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28, 31
tag: TPIO
lang: zh
source: kvant_digital
content_sha256: 17d1998813968b06309448a9197393d7a82cf37702851ac082e764308f8dbfe2
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/06_nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba.md
source_content_sha256: f48dfd089e0476af5d204b46105a83c1d5a7e6045e6c45063aaaf515e28e3a06
translation_model: draft
translation_run: zh-draft-2026-11-03
translation_quality: draft
---

⟦folio 28⟧

几何问题主题的变奏

N. 尼科洛夫 (索菲亚), A. 伊万诺夫 (普列文)

在本文中，我们将讨论与第 73 届保加利亚国家奥林匹克竞赛中提供的几何 ���题 M2809 相关的图。

让我们看看这个简单的设计。设点 M 和 N 分别位于三角形 ABC (图 1) 的边 AC 和 BC 上。让线段 AN 和 BM 相交于 O 点。接下来，我们将使用三角形元素的标准符号：BC = a，AC = b，ACB J。此外，我们将 CM = m，CN = n，AOM T。

⟦column⟧

⟦figure⟧

图 3

⟦figure⟧

图 1

让我们从以下任务开始，原则上 7-8 年级的学生可以完成该任务。问题1. 设ACB 90 q，并已知AM = BC，CM = BN。寻找 OM。

练习 1. 找出在极限情况 AC = BC 和 AC = 2BC 下问题 1 的答案是什么。

解决方案。让我们将三角形 AMB 完成为平行四边形 AMBP (图 2)。然后是 BC。

图 2

⟦folio none⟧

---
running_head:
folio:
---

= AM = PB，CM = BN，$\angle BCM = 90^\circ = \angle PBN$，因此三角形 BCM 和 PBN 相等。因此 AP = BM = PN。我们还有 $\angle BNP = \angle CMB = 90^\circ - \angle MBN$，即 NP ⊥ BM，因此 NP ⊥ AP。那么三角形 ANP 是等边直角三角形，因此 $\angle AOM = \angle OAP = 45^\circ$。解决问题。

练习 2. 从以下构造中获得问题 1 的另一个解 (图 3)。设BNAX为平行四边形。

图 3

a) 证明直角三角形BCM 和MAX 相等。
b) 求出三角形XMB的内角，然后求$\angle AOM$。
这种结构可以通过另一种方式获得，即在 AC 侧构建一个正方形，并在 BM 侧构建一个内接正方形。

请注意，在我们的符号中，问题 1 的条件 AM = BC 和 CM = BN 被重写为 $b - m = a$ 和 $m = a - n$。

如果$\angle ACB = 90^\circ$，简单的计算允许我们用$a$、$b$、$m$、$n$ 来表达数量$\theta$。让我们特别声明以下声明。

陈述 1. 如果 $\angle ACB = 90^\circ$，mo $\theta = 45^\circ$ 可以并且悄悄地可以，当
$$ab - mn = bm + an.$$ (1)

证明。让我们放置$\theta_1 = \angle CAN$和$\theta_2 = \angle BMC$，从而得到$tg\theta_1 = \frac{NC}{AC} = \frac{n}{b}$和$tg\theta_2 = \frac{BC}{MC} = \frac{a}{m}$。然后
$$tg\theta = tg(\theta_2 - \theta_1) = \frac{tg\theta_2 - tg\theta_1}{1 + tg\theta_1tg\theta_2} = \frac{ab - mn}{bm + an}.$$

仍然需要使用$\theta = 45^\circ$当且仅当$tg\theta = 1$这一事实。这就是所需要的。

练习
3. 进行代数计算，证明等式 $b - m = a$ 和 $m = a - n$ 蕴含 (1)。
4. 令 $a, b, m, n$ 为正数。证明从 (1) 可以得出 $b > n$ 和 $a > m$。

现在我们固定$a, b, m, n$，角度$\gamma$允许改变——我们可以认为我们有一个ACB铰链，在AC和CB上有固定标记$M$和$N$。那么角度$\theta$取决于$\gamma$，即定义了$\gamma \in (0; \pi)$的函数$\theta = \theta(\gamma)$。您可以观察（例如，在 Geogebra 程序中）$\theta(\gamma)$ 的变化。让我们证明一些关于$\theta(\gamma)$行为的陈述。

陈述2.设$a > m$和$b > n$。然后$\theta(\gamma)$阶数在区间$(0; \pi)$上递减。

在证明这个说法之前，让我们先陈述以下推论。

结果。令(1)成立。那么：$\theta > 45^\circ$当且仅当$\gamma < 90^\circ$，$\theta = 45^\circ$当且仅当$\gamma = 90^\circ$，$\theta < 45^\circ$当且仅当$\gamma > 90^\circ$。

证明。事实上，从练习 4 中我们知道 (1) 将突出显示 $a > m$ 和 $b > n$。那么一切都由陈述 1 和 2 得出：$\theta(\gamma)$ 阶数递减，此外，满足等式 $\theta\left(\frac{\pi}{2}\right) = \frac{\pi}{4}$。调查已证实。

让我们回想一下问题 M2809（我们用符号表示它的表述）并假设它紧随语句 2 得出。

任务 2 (M2809)。已知AM=BC，CM=BN。如果您知道$\gamma = 2\theta$，请找到$\gamma$。

第一个决定。正如我们所看到的结果，对于 $\gamma < 90^\circ$ $2\theta > 2\cdot 45^\circ > \gamma$ 是满足的，并且对于 $\gamma > 90^\circ$ $2\theta < 2\cdot 45^\circ < \gamma$ 是满足的。这意味着 $\gamma = 90^\circ$ 是唯一可能的值。

在本文的最后，我们将提出问题 M2809 的另一个简短、优雅的几何解决方案，该解决方案不依赖于本文中的任何其他陈述。

不，我们现在继续研究吧。

陈述证明2。设置$x = \cos \gamma$，$y = -\cos \theta$。我们只要理解函数$y(x)$在区间$x \in [-1; 1]$上严格递增就足够了。下面我们将显式计算$y(x)$。

让我们完成三角形 AMB 做平行四边形 AMBP (图 4) 使得 BP = AM = $b - m$, $\angle NBP = 180^\circ - \gamma$, $\angle NAP = \theta$。

⟦folio 31⟧

---
running_head:
folio:
---

来自积分$\left[ \theta \left( \gamma_0 \right); 0 \right)$的所有值。还有，$\theta \left( \gamma_0 \right) < \pi/2$。

证明。从$a < m$开始，然后是$p < 1$，从$y(x)$的公式我们可以看到$y(x) \in (-1; 0)$位于$x \in (-1; 1)$，此外还有$y(\pm 1) = -1$。现在需要理解的是，存在$x_0 \in (-1; 1)$使得$y(x)$严格在$x \in [-1; x_0]$返回并严格在$x \in [x_0; 1]$杀死，此外还有$x_0 > 0$。

计算任意一个可得出：

$$y'(x) = \frac{ux + v}{2\left(\sqrt{1 - qx}\sqrt{1 - rx}\right)^3},$$

其中$u = 2qr - pq - pr$，$v = 2p - q - r$。我们看到（因为$y(x)$不是常数函数）任意$y'(x)$只能在一点$\left(x_0 = -\frac{v}{u}\right)$分别变为0，符号$y'(x)$只能改变一次（仅在点$x_0$）。这意味着要么$y(x)$在$[-1; 1]$上严格单调，要么$[-1; 1]$被点$x_0$分为两个严格单调的区间。第一个选项是不可能的，因为 $y(\pm 1) = -1$。这意味着$x_0 \in (-1; 1)$，并且从$x \in (-1; 1)$上的$y(x) > -1$开始，$y(x)$必须严格在$x \in [-1; x_0]$返回并严格在$x \in [x_0; 1]$杀死。

$x_0 = -\frac{v}{u} > 0$还有待观察。我们已经知道$y'(x) > 0$位于$x \in [-1; x_0]$，$y'(x) < 0$位于$x \in (x_0; 1]$。特别是，$y'(-1) > 0$，由此而来$-u + v > 0$和$y'(1) < 0$，因此$u + v < 0$。由此我们得到$u < 0$。让我们通过直接替换来证明$v > 0$：放入$s = \frac{a}{m}$、$t = \frac{n}{b}$（因此$s > t$）并进行变换

$$\frac{v}{2} = p - \frac{q}{2} - \frac{r}{2} = \frac{s + t}{st + 1} - \frac{s}{s^2 + 1} - \frac{t}{t^2 + 1} = \frac{(s - t)^2(s + t)}{(st + 1)(s^2 + 1)(t^2 + 1)} > 0.$$

该说法已被证明。

总之，正如所承诺的那样，我们提出了问题 2 的解决方案，该解决方案不基于统计结果。这一决定是由奥运会参赛者瓦西尔·瓦西列夫做出的。

问题 M2809 的第二个解决方案。所以，$AM = BC, CM = BN, \angle ACB = \gamma, \angle AOM = \frac{\gamma}{2}$。

1) 让我们将三角形 $ABC$ 完成为平行四边形 $ACBQ$ (图 5)。然后$\angle QAM = 180^\circ - \angle ACB = 180^\circ - \gamma$。从$AM = BC = AQ$开始，从等边三角形$AMQ$我们有$\angle AQM = \frac{180^\circ - \angle QAM}{2} = \frac{\gamma}{2}$。我们看到$\angle AQM = \angle AOM$，这意味着点$A, Q, O, M$位于同一个圆上。

2) 现在，在线段 $BQ$ 上，我们取一个点 $R$，使得 $BR : RQ = CM : MA$ （因此 $AMRQ$ 和 $MCBR$ 是平行四边形）。然后$\angle CBR = 180^\circ - \angle ACB = 180^\circ - \gamma$。从$BR = CM = BN$开始，从等边三角形$BRN$我们有$\angle BRN = \frac{\gamma}{2}$。我们看到$\angle BRN = \angle BON$，这意味着$B, R, O, N$点位于同一个圆上。

3) 进一步，从圆（BRON）我们看到$\angle ROB = \angle RNB = \frac{\gamma}{2}$。但从前面的角度算$\angle RQM = \angle RQA - \angle MQA = \gamma - \frac{\gamma}{2} = \frac{\gamma}{2}$。这意味着$\angle ROB = \angle RQN$是开放的；由此可知四边形 $MQRO$ 是内接四边形。

4) 因此，所有五个点 $A, Q, O, M, R$ 都位于同一个圆上。从这里开始，问题的陈述就立即出现了，因为$AQRM$是一个内接平行四边形，这意味着它是一个直角，$\gamma = \angle AQB = 90^\circ$是开放的。

练习 7. 将解的步骤 3) 替换为证明 $AQRO$ 是循环四边形。
