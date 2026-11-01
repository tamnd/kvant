---
id: 1978-12-skvortsov-xx-mezhdunarodnaya-matematicheskaya-olimpiada-shkolnikov-83039dbb
issue: kvant_1978_12
year: 1978
number: "12"
title: XX年国际中小学生数学奥林匹克竞赛
authors:
  - Скворцов В. А.
rubric: informatsiya
rubric_sub: Информация
page_first: 57
page_last: 57
page_labels: "55"
tag: NBFC
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 354c3e6d2b85fee0912bebb3f0287d015135dfab9cc2fecd33dd763007146c9f
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/16_skvortsov-xx-mezhdunarodnaya-matematicheskaya-olimpiada-shkolnikov-83039dbb.md
source_content_sha256: 60404cf3a47f502d4b9565eb4924172b2d07184af4642799613f953116bd5cff
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

XX年国际中小学生数学奥林匹克竞赛

第二十届奥林匹克运动会于 1978 年 7 月在布加勒斯特举行。来自17个国家的代表队参加了比赛。和往常一样，每个国家队由 8 名小学生组成。参与者被分配了 6 项任务——在北方的两天里每天都有 3 项任务。解决每个棘手问题都会获得一定数量的分数。单个参与者解决所有问题的最大可能得分为 40 分，因此整个团队的得分为 320 分。非官方夏季赛，罗马尼亚队领先（237分）。接下来是美国队（225分）、英国队（201分）、越南队（200分）、捷克斯洛伐克队（195分）。 （苏联代表队没有参加本届奥林匹克竞赛。）XX奥林匹克竞赛的四道题放在本期习题册«Kvant»中。下面给出本问题中未包含的所有问题的条件和解决方案。

第一天

1. 令$m$和$n$为自然数，使得$n > m \geqslant 1$。用十进制表示，1978$^m$的后三位数字的组与1978$^n$的后三位数字的组相同。找到$m$和$n$，使得$m+n$之和最小。

2. 令 $P$ 为给定球体内的给定点，$A, B, C$ 为该球体的任意三个点，使得线段 $PA, PB, PC$ 相互垂直。令 $Q$ 为由与 $P$ 对角线相对的线段 $PA, PB$ 和 $PC$ 定义的平行六面体的顶点。确定点$Q$的几何位置。

3. 所有自然数的集合是两个不相交子集$\{f(1), f(2), \dots, f(n), \dots\}$、$\{g(1), g(2), \dots, g(n), \dots\}$的并集，其中$f(1) < f(2) < \dots < f(n) < \dots$、$g(1) < g(2) < \dots < g(n) < \dots$和$g(n) = f(f(n)) + 1$代表所有$n \geqslant 1$。定义$f(240)$。

第二天

4. 该圆在内部与右股骨三角形 $ABC$ 外接圆以及该三角形的等边 $AB, AC$ 在点 $P, Q$ 处相切，对应。证明线段$PQ$的中点是三角形$ABC$外接圆的圆心。

5. 令 $\{a_k\} (k=1, 2, \dots, n)$ 为不同自然数的序列。证明对于每个自然数 $n$ 不等式

$$\sum_{k=1}^{n} \frac{a_k}{k^2} \geqslant \sum_{k=1}^{n} \frac{1}{k}.$$

6. 国际协会由来自6个不同国家的代表组成。该协会的成员名单由 1978 个名字组成，并标有数字 1、2、...、1978。

证明该社团中至少有一名会员的人数等于其所在国家两名会员人数的总和，或者是其所在国家某会员人数的两倍。

解决方案

问题1. 根据条件得出$1978^n - 1978^m = 1978^m (1978^n - m - 1) = 1000 a$，其中$a$是某个自然数。由此可见，$m \geqslant 3: 1978^m$ 必须能被 8 整除。仍然需要找到 $n-m$，其中 $A = 1978^n - m - 1$ 能被 5$^3$ 整除。很容易证明，只有当 $n-m=4k$ 时，$A$ 才能被 5 整除。由于我们感兴趣的是数字$A$除以125时的余数，因此我们可以将1978替换为103，将103$^4$替换为6。然后是$6^k - 1 = (1 + 5)^k - 1 = k \cdot 5 + \frac{k(k-1)}{2} - 5^2 + \dots$，其中省略的项可被125整除。因此，$2k + 5(k-1)k = k(5k-3)$可被25整除，因此$k$可被25. 因此$n-m=100k$，和$n+m=100k+2m$。答案：106。

问题5. 很容易检查，从$x_1 > x_2$、$y_1 > y_2$ 开始，它紧随$x_1y_1 + x_2y_2 > x_1y_2 + x_2y_1$。因此，对于$k_1 < k_2$和$a_{k_1} > a_{k_2}$我们得到

$$\frac{a_{k_1}}{k_1^2} + \frac{a_{k_2}}{k_2^2} \geqslant \frac{a_{k_2}}{k_1^2} + \frac{a_{k_1}}{k_2^2}.$$

让我们按照年龄的顺序重新排列所有 $a_k$ 和 $k=1, \dots, n$：$a_{k_1} < a_{k_2} < \dots < a_{k_n}$。然后通过(*)

$$\sum_{k=1}^{n} \frac{a_k}{k^2} \geqslant \sum_{k=1}^{n} \frac{a_k}{i^2}.$$

考虑到$a_{k_i} \geqslant i$，我们得到了一个异常不等式。

V·斯科沃佐夫
