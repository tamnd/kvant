---
id: 1978-10-boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89
issue: kvant_1978_10
year: 1978
number: "10"
title: 三点在一条线上
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18, 19
tag: 9WHD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5d64906cc906b6cc239222ab5c86b10b861011335a0e85de292c9737aee5e801
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/05_boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89.md
source_content_sha256: fd135da9482f19db1fea38c1339363d60507a75044a0b972c16e857d47adf74c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

在本文中，我们将讨论使用向量可以解决的几个问题。基本上，这些问题需要证明某些三个点位于同一条直线上，或者根据某些三个点位于同一条直线上的事实得出某些结果。解决此类问题最主要的是一个众所周知的定理。当向量 $\overrightarrow{AB}$ 和 $\overrightarrow{AC}$ 共线时（即，存在一个数字 $k \in R$ 使得 $\overrightarrow{AC} = k\overrightarrow{AB}$），这两种情况下的点 C 都属于线 AB。

因此，要确定A、B、C三点属于一条直线，只要保证有一个数就足够了 $k$，对于其中 $\overrightarrow{AC} = k\overrightarrow{AB}$。数字 $k$ 根据 $\overrightarrow{AC} = k\overrightarrow{AB}$ 有（与 $A \neq B$）简单的几何意义： $|k| = \frac{|\overrightarrow{AC}|}{|\overrightarrow{AB}|}$， 和 $k > 0$，如果 C 点属于射线 AB，并且 $k < 0$，如果它属于相反的射线。

例如，如果 C 是线段 AB 的中点 (图 1)，则$\overrightarrow{AC} = \frac{1}{2}\overrightarrow{AB}$；从这里开始任意点 Q

$$\overrightarrow{QC} = \frac{1}{2}\overrightarrow{QA} + \frac{1}{2}\overrightarrow{QB}.$$

进一步，若$B$为三角形AMN的边MN的中点，$C$为该三角形的重心（中线的交点），则线段AC的长度为$\frac{2}{3}$线段AB的长度（图2）：$\overrightarrow{AC} = \frac{2}{3}\overrightarrow{AB}$；因为对于任意点 Q 等式 $\overrightarrow{QB} = \frac{1}{2}\overrightarrow{QM} + \frac{1}{2}\overrightarrow{QN}$ 成立，我们可以得出结论：

$$\overrightarrow{QC} = \frac{1}{3}\overrightarrow{QA} + \frac{1}{3}\overrightarrow{QM} + \frac{1}{3}\overrightarrow{QN}.$$

最后，再补充一点：如果向量 $\vec{a}$ 和 $\vec{b}$ 不共线，则根据对应关系

$$\vec{ka} + \vec{lb} = \vec{ma} + \vec{nb}$$

由此可知$k = m$和$l = n$。事实上，这个等式可以重写为以下形式

$$(k - m)\vec{a} = (n - l)\vec{b};$$

如果现在$k \neq m$，则$\vec{a} = \frac{n - l}{k - m}\vec{b}$，这与向量$\vec{a}$和$\vec{b}$的非共线性相矛盾。因此，$k = m$，类似地，$l = n$。

这就是所有“理论”近似值。现在让我们看四个例子。

例1 众所周知，梯形底边的中点和对角线的交点位于同一条直线上。现在让我们在某些情况下证明“逆”定理：如果对角线交点 A

⟦folio 15⟧

图 2.

绰号MNPQ和中B，以其亲
由于对边 MN 和 PQ 位于同一条直线上，因此 MNPQ 是梯形或平行四边形 (图 3)。

证明。让我们输入$\vec{a} = \vec{AM}$，$\vec{b} = \vec{AN}$。然后 $\vec{AP} = k\vec{a}$ （因为点 A、M、P 位于同一条线上），并且以同样的方式，$\vec{AQ} = l\vec{b}$。由于 B 是线段 MN 的中点，

$$\vec{AB} = \frac{1}{2}\vec{AM} + \frac{1}{2}\vec{AN} = \frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}.$$

完全一样

$$\vec{AC} = \frac{1}{2}\vec{AP} + \frac{1}{2}\vec{AQ} = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

根据条件，A、B、C 点在同一条直线上，因此存在一个数 m 使得 $\vec{AC} = m\vec{AB}$，即

$$m\left(\frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}\right) = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

由于向量$\vec{a}$和$\vec{b}$的非线性，可以得出$m = k = l$。

最后，我们有

$$\vec{MN} = \vec{b} - \vec{a}, \vec{PQ} = l\vec{b} - k\vec{a} = k(\vec{b} - \vec{a}),$$

即$\vec{PQ} = k\vec{MN}$。因此，$(PQ) \parallel (MN)$，即$MNPQ$，是梯形或平行四边形。

扫地。在 图 3 个点 A、M、N、P、Q 上，使得数字 k 和 l 为负数。然而，该解决方案没有使用硝基。因此，上述推理对于k和l为正数的情况没有任何改变地适用。这种情况是在图4中选择的。这样，我们就“免费”得到了以下定理的证明：如果陷阱MNQP的边NQ和MP的延长线相交的点A，与边MN和PQ的中点B、C位于同一条直线上，则极点MNQP是梯形。我们还邀请读者看到上述论点以相反的顺序进行（几乎没有变化）。这给出了相应“直接”定理的向量证明：在任何梯形中，底边的中点和对角线的交点位于同一条直线上；任何梯形，底边的中点和侧边延长线的交点都在同一条直线上（即四个指示点都在同一条直线上）。

示例 2. 在平行四边形 AMNO 的 ON 侧及其二边上

⟦folio 16⟧

图 4.

永恒 OM 也取点 B 和 C，即 $\overrightarrow{OB} = \frac{1}{n} \overrightarrow{ON}$ 和 $\overrightarrow{OC} = \frac{1}{n+1} \overrightarrow{OM}$ (图 5)。证明A、B、C点在同一条直线上。

解决方案。让我们输入$\overrightarrow{AB} = \vec{a}$，$\overrightarrow{ON} = \vec{b}$。然后

$$\overrightarrow{AC} = \overrightarrow{AO} + \overrightarrow{OC} = \overrightarrow{AO} + \frac{1}{n+1} \overrightarrow{OM};$$

$$\overrightarrow{AO} = \overrightarrow{AB} - \overrightarrow{OB} = \vec{a} - \frac{1}{n} \vec{b};$$

$$\overrightarrow{OM} = \overrightarrow{ON} - \overrightarrow{AO} = \vec{b} - \left( \vec{a} - \frac{1}{n} \vec{b} \right) = \frac{n+1}{n} \vec{b} - \vec{a},$$

那是

$$\overrightarrow{AC} = \left( \vec{a} - \frac{1}{n} \vec{b} \right) + \frac{1}{n+1} \left( \frac{n+1}{n} \vec{b} - \vec{a} \right) = \frac{n}{n+1} \vec{a},$$

或$\overrightarrow{AC} = \frac{n}{n+1} \overrightarrow{AB}$。由此可见，A、B、C 点位于同一条直线上。

笔记。解决方案中没有任何地方使用数字 $n$ 是自然数。上述推理表明，这里$n$可以是除0和-1之外的任何实数（分数的能指中有表达式$n$和$n+1$）。

图 5 显示情况$n = 4$（B 点切掉边 ON 的四分之一，C 点切掉对角线 OM 的五分之一）。如果我们放入$n = -m-1$，那么我们将有$\frac{1}{n} = -\frac{1}{m+1}, \frac{1}{n+1} = -\frac{1}{m}$，即

$$\overrightarrow{OB} = -\frac{1}{m+1} \overrightarrow{ON}, \overrightarrow{OC} = -\frac{1}{m} \overrightarrow{OM}.$$

图6表示$m = 3$的情况（在ON边的延续上，四分之一边偏离O点，在对角线的延续上，第三个四分之一MNP）。在 MN、NP、PM 线上取点 A、B 和 C：

$$\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP},$$

$$\overrightarrow{PC} = \gamma \overrightarrow{CM}.$$

证明如果 $\alpha \beta \gamma = -1$，则 A、B、C 点位于同一条直线上（墨涅劳斯定理）。

证明。让我们输入$\overrightarrow{AN} = \vec{a}, \overrightarrow{BP} = \vec{b}, \overrightarrow{CM} = \vec{c}$。

然后

$$\overrightarrow{MA} = \alpha \vec{a}, \overrightarrow{NB} = \beta \vec{b}, \overrightarrow{PC} = \gamma \vec{c}.$$

向量$\overrightarrow{AB}$和$\overrightarrow{AC}$很容易表达

⟦folio 18⟧

图 8.

从$\overrightarrow{AB} = \overrightarrow{AO} - \overrightarrow{BO}$和$\overrightarrow{AB} = \overrightarrow{CB} - \overrightarrow{CA}$开始，我们得到
$$\overrightarrow{b} - \overrightarrow{a} = x(\beta \overrightarrow{b} - \overrightarrow{a}) - y(\alpha \overrightarrow{a} - \overrightarrow{b}),$$
那是
$$(x + \alpha y - 1)\overrightarrow{a} - (y + \beta x - 1)\overrightarrow{b} = 0.$$

由于向量$\overrightarrow{a}$和$\overrightarrow{b}$的非共线性，最后一个等式左边的系数必须等于0，即
$$\begin{cases} x + \alpha y = 1, \\ \beta x + y = 1. \end{cases}$$

求解这个方程组，我们找到答案：
$$x = \frac{1 - \alpha}{1 - \alpha\beta}, \quad y = \frac{1 - \beta}{1 - \alpha\beta}.$$

任务和

1. 不在同一直线上的点 $A, B, C, M$ 和 $N$ 的位置使得射线 $AM$ 和 $BN$ 平行且方向相反； $|AC| = p, |BC| = q, |AB| = p + q$。线段$AM$和$BN$的长度之间的对应关系是什么，点$M, N$和$C$位于同一条线上？

2. 线 $a$ 和 $b$ 平行。在直线 $a$ 上我们取任意点 $A_1, A_2, A_3$，在直线 $b$ 上我们取任意点 $B_1, B_2, B_3$。在线段$A_1B_1, A_2B_2, A_3B_3$上，我们还取点$C_1, C_2, C_3$，即$|A_1C_1| = \alpha |A_1B_1|, |A_2C_2| = \alpha |A_2B_2|, |A_3C_3| = \alpha |A_3B_3|$。证明点$C_1, C_2, C_3$位于同一条直线上。

3. 点 $M, N, P$ 相对于三角形 $ABC$ 的边与点 $O$ 对称。证明点 $O$ 与三角形 $ABC$ 和 $MNP$ 的中心位于同一条直线上。

4. 点 $A, B, C$ 是三角形 $OMN, ONP, OMP$ 的中心。证明三角形的中心是$BCD, ACD, ABD, ABC$。证明线段 $AA_1, BB_1, CC_1, DD_1$ 相交于一点 $M$，并且点 $M$ 从这些线段中的每一个中截断第四条线段。按照平面和空间图层的图纸进行操作。

⟦folio 19⟧

10. 图 10.

11. 证明如果四边形ABCD中线的交点属于对角线AC，则对角线BD平分对角线AC。逆定理成立吗？

12. 给定三角形 MNP。点 A、B、C 也在直线 MN、NP、PM 上取，即 $\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP}, \overrightarrow{PC} = \gamma \overrightarrow{CM}$。证明如果 $\alpha \beta \gamma = 1$，则线 MB、NC 和 PA 相交于一点（Ceva 定理）。

13. 线段$A_1A_4$和$D_1D_4$（任意位于空间）被分为每个点$A_2$、$A_3$和$D_2$、$D_3$（图10）的三个拥塞部分。点$B_i$和$C_i$将路段$A_iD_i$分为三个拥堵部分（$i = 1, 2, 3, 4$）。证明点 $B_1, B_2, B_3, B_4$ 位于同一条直线上，点 $C_1, C_2, C_3, C_4$ 位于同一条直线上。

14. 在线段$A_1C_1$和$A_2C_2$（空间中任意位置）上，取点$B_1$和$B_2$，使得$|A_1B_1| = \alpha |A_1C_1|$、$|A_2B_2| = \alpha |A_2C_2|$。在线段 $A_1A_2, B_1B_2, C_1C_2$ 上，我们取点 $M, N, P$ (图 11)，使得 $|A_1M| = \beta |A_1A_2|$、$|B_1N| = \beta |B_1B_2|$、$|C_1P| = \beta |C_1C_2|$。证明点 $M, N, P$ 位于同一条直线上。

15. 两个质点沿两条直线 $a$ 和 $b$ 均匀移动（以非零速度）。连接移动点的直线总是经过固定点$O$。证明$a \parallel b$。

16. 两个质点在空间中以$v_1$和$v_2$的速度作匀速直线运动。 $t$时刻移动点的位置用$A_t$和$B_t$表示，$C_t$也表示线段$A_tB_t$的点，即$|A_tC_t| : |A_tB_t| = \alpha (0 < \alpha < 1)$。证明点$C_t$也匀速直线运动。以什么速度？

17. 一架携带亮点光源的飞机以 $v_1$ 的速度在平坦表面上均匀线性移动，第二架飞机以 $v_2$ 的速度均匀线性移动。在某些时刻，该平面、第二平面和第二平面的阴影分别位于点$A, B, C$（图12）和$|BC| = \alpha |AC| (0 < \alpha < 1)$。在平面速度之间的什么对应关系下，第二个平面的阴影也均匀且直线地移动？

18. 三个质点在空间中均匀直线运动，每个质点都有自己的速度。 $t$ 时刻移动点的位置用$A_t, B_t, C_t$ 表示。证明三角形$A_tB_tC_t$的重心也作匀速直线运动。
