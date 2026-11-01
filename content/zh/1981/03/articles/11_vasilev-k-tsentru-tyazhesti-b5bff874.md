---
id: 1981-3-vasilev-k-tsentru-tyazhesti-b5bff874
issue: kvant_1981_3
year: 1981
number: "3"
title: 朝向重心
authors:
  - Васильев Н. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 35
page_labels: "33"
tag: 1BIJ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 826fc4692d642bf7dfee5f2b16bb3d57393ed04a653027ebe5a2ec61be66e9d6
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/11_vasilev-k-tsentru-tyazhesti-b5bff874.md
source_content_sha256: 984095cf853260ae74d95c3e4045646c4ebf2a0e174ebaa936dca06edcf5892a
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

朝向重心

在第一种情况下
$$\frac{I_{(1)}}{I_0} = 1 + \frac{L_1}{L_2}.$$
在这种情况下，过程结束时系统的能量等于
$$E_{(1)} = \frac{L_2 I_1^2}{2} = \frac{L_1 + L_2}{2} I_0^2 \left(1 + \frac{L_1}{L_2}\right) = E_0 \left(1 + \frac{L_1}{L_2}\right),$$
在哪里
$$\frac{E_{(1)}}{E_{(0)}} = 1 + \frac{L_1}{L_2}.$$
在第二种情况下
$$\frac{I_{(2)}}{I_0} = 1 - \frac{L_1}{L_2}.$$
$$E_{(2)} = \frac{L_2 I_2^2}{2} = \frac{(L_2 - L_1)^2}{2 L_2} I_0^2,$$
$$\frac{E_{(2)}}{E_0} = \frac{(L_2 - L_1)^2}{L_2 (L_1 + L_2)}.$$
祖布科夫

朝向重心

一个由相同部件组成的系统如何运作，每个部件的运动规则仅取决于少量的车轴？此类问题出现在物理、化学和生物对象的许多数学模型中，并且通常很难获得这些问题的答案。在这篇笔记中，我们将解决一个此类问题（问题书«Kvant»中的M604），其中粒子运动的规则用直线和函数来表达，这使我们能够得到一个简单的答案：粒子向共同的重心合并。

问题表述
a) Andrey、Victor、Sergey，在水下游泳，同时选择$A_0, B_0, C_0$点并立即再次潜水，Andrey决定在一分钟内游到Victor的三分之一路程，Victor - 到Sergey的三分之一路程，Sergey - 到Andrey的三分之一路程。几分钟后，他们再次选择（点$A_1, B_1, C_1$ - 参见图1）并决定重复此操作 - 已经在半分钟内；然后四分之一分钟，等等。

他们将在何时何地见面？
b) 在半径为 1 km 的球体内，有 100 万个点，编号从 1 到 100 万。每个点同时移动到下一个编号为该点距离的 1/3 的时间是多少秒？完全相同的最后一点向第一点移动。证明一段时间后所有点都将位于半径为 1 厘米的某个球体内。

问题a）的解决方案
让我们证明所有点$A_k, B_k$和$C_k$都趋于重心极限。 Q 三角形 - 其中线的交点；从这个意义上说，我们可以说安德烈、维克多和谢尔盖将在$1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \ldots = 2$分钟后的$Q$点相遇（当然，即使是海豚也无法像我们的游泳运动员在第二分钟结束时那样快速转身和翻滚）。

以$Q$为坐标原点，使用变换$(A_k, B_k, C_k) \rightarrow (A_{k+1}, B_{k+1}, C_{k+1})$的向量表示法。

很容易看出 (图 2)，对于每个 $k = 0, 1, 2, \ldots$
$$\vec{Q}A_{k+1} = \frac{2\vec{Q}A_k + \vec{Q}B_k}{3},$$
$$\vec{Q}B_{k+1} = \frac{2\vec{Q}B_k + \vec{Q}C_k}{3},$$
$$\vec{Q}C_{k+1} = \frac{2\vec{Q}C_k + \vec{Q}A_k}{3}.$$
从这些公式可以得出，点 $Q$ 是所有三角形 $A_k B_k C_k$: $\vec{Q}A_k + \vec{Q}B_k + \vec{Q}C_k = \vec{0}$ (图 3) 的公共重心。

而且，变换$L^2 = L \cdot L$，从公式可以看出
$$\vec{Q}A_{k+2} = \frac{4\vec{Q}A_k + 4\vec{Q}B_k + \vec{Q}C_k}{9} = -\frac{\vec{Q}C_k}{3},$$
$$\vec{Q}B_{k+2} = -\frac{\vec{Q}A_k}{3},$$
$$\vec{Q}C_{k+2} = -\frac{\vec{Q}B_k}{3},$$
— 用系数 $(-1/3)$ 和中心 $Q$ 准备（参见 图 1）。因此，如果三角形$A_0 B_0 C_0$位于以点$Q$为中心、半径为$R$的圆中，则三角形$A_{2k} B_{2k} C_{2k}$和所有后续三角形将是
