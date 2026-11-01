---
id: 1980-7-boltyanskiy-tranzitivnyie-mnozhestva-i-pravilnyie-mnogogranniki-9cd73482
issue: kvant_1980_7
year: 1980
number: "7"
title: 传递集和正多面体
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 6
page_last: 10
page_labels: 4-8
tag: KWKE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e4eba28c899f061de59209ac30e836ab50244d76ce8866c766fb3b0e73b10343
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/04_boltyanskiy-tranzitivnyie-mnozhestva-i-pravilnyie-mnogogranniki-9cd73482.md
source_content_sha256: e018f1d3875b833290c3a05c49739ce101663e743c892f296fec73bd429f40eb
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

V·博尔坦斯基

传递集和正多面体

图自对准组

移动 $f$ 称为图形的自对准 $F$，如果将这个数字转化为自身： $f(F) = F$。容易证明一个图形的所有自组合的集合 $F$ 是一个组（对于定义的组，请参见例如 «Kvant»，1976年，第10期）；表示图形的一组自组合的条件 $F$ 通过 $\Gamma(F)$.

任务
1. 指示所有自对准： a) 圆圈； b) 直； c) 段。
2. 找到一个图$F$，其组$\Gamma(F)$恰好包含三个自对准。

图形$F$的自对准组存在与该图形的“几何形状”相关。例如，让 $P$ 是一个既不是矩形也不是菱形的平行四边形。有两种将 $P$ 转化为自身的翻译：恒等映射 $e$ 和关于对角线交点的对称性 $r$。

问题3.证明除了$e$和$r$之外，这样的平行四边形$P$不存在自对齐。

由于$\Gamma(P)$包含中心对称性$r$，平行四边形的所有基本性质都遵循：对边全等和平行、对角全等等。

菱形$Q$的自对准群不是正方形，除了$e$和$r$之外，还包含相对于对角线的两个轴对称$s_1$、$s_2$，即$\Gamma(Q) = \{e, r, s_1, s_2\}$。由于$\Gamma(Q)$组中存在额外的（与所承诺类型的平行四边形相比）自对准，菱形的特定属性如下（除了平行四边形固有的属性之外）：对角线的垂直度、对角线与角平分线的重合等。

任务
4. 列出自对齐组恰好包含两个元素的所有四边形。
5. 证明如果图形$F$是有界的（即包含在某个圆中），则$\Gamma(F)$不能包含与$e$不同的平行平移。

平面上的传递集

许多 $H$ 如果该集合的任何点可以通过集合的某种自组合转换为它的任何其他点，则称为传递性 $H$。在 图 图1示出了一个正方形，从中切出了等腰直角三角形的四边形。结果集所有顶点的集合都在平面上，则存在有界集；根据定义，它恰好包含一些圆圈。那么还存在一个半径最小的圆，

图 1.

⟦folio 5⟧

图 2.
含有$H$。令 $K$ 为最小圆，$O$ 为圆心。

让我们取两个任意点$A, B$集合$H$。让我们证明$|AO| = |BO|$。从这里可以看出，$H$位于某个圆上（很容易看出该圆限制了圆$K$）。

由于集合$H$的传递性，存在自组合$f \in \Gamma(H)$使得$f(A) = B$。从$H \subset K$开始，接着$f(H) \subset f(K)$。但是$f(H) = H$。所以，$H \subset f(K)$。因此，$H \subset K \cap f(K)$。

由于$f$是位移，$f(K)$是圆，对圆$K$承重。如果圆$K, f(K)$不重合，则会存在一个半径较小的圆，其中包含$K \cap f(K)$，然后包含$H$，这与圆$K$的选择相矛盾。所以，$f(K) = K$，因此$f(O) = O$。

从$f(A) = B, f(O) = O$开始，事实上$f$是一个运动，它跟随$|AO| = |BO|$。

显然，空集、任意单元素集、任意二元素集都是传递性的。

任务 6.
证明如果传递集包含 $2k + 1$ 个点 ($k > 0$)，则这些点作为正多边形的顶点。

7. a) 证明如果传递集包含4个点，则这些点是直多边形的顶点。

6) 证明如果传递集包含 2k 个点 ($k > 2$)，则这些点充当内接于一个圆的两个正则 $k$ 边形的顶点。

8. 证明传递集$H$的无限约束总是完全填充包含它的圆（即，该圆中不存在脱离点集$H$的其他圆）。

是否存在无界传递集？

图 3.
当然，还有：例如整个平面以及其上的任意一条直线。尝试再举出至少一个例子。

我们同意将所有顶点的集合具有传递性的多边形称为传递多边形。显然，任何正多边形都是传递的。然而，正多边形$P$还有更深层次的性质，可以称为强传递性：如果$A_1, A_2$是任意两个顶点，$l_1, l_2$是直接到这些顶点的边（图2），则存在满足条件：$f(A_1) = A_2, f(l_1) = l_2$的自对齐$f \in \Gamma(P)$。

如果多边形$P$具有强传递性，则它是正则多边形。

任务 9. 证明对于正则 $n$-边形 $P$，群 $\Gamma(P)$ 包含 $2n$ 变量。确保所有这些变量都是轴对称的。

空间传递集

我们可以考虑空间中的传递集。例如，一条直线的所有顶点的集合，其底是传递多边形（图 3），是传递的。

定理2. 如果$H$是空间中有界传递集，则存在包含$H$的球体。

证明与平面上的证明相同，只是与最小圆一起我们必须考虑包含$H$的最小球。然而，敏锐的读者可能会注意到这些证明是不完整的：仍然有必要确定最小的本质

⟦folio 6⟧

包含给定有界集合 $H$ 的圆（或球）的 shero（例如，可以从 Weierstrass 定理推导出来）。因此，让我们提出其他证明；它不包含空格，但仅适用于有限集$H$。

引理。设 $H = \{A_1, \dots, A_n\}$ 为有限点集。那么存在且只有一个点 $O$ 对于
$$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}.$$

（这样的点称为点$A_1, \dots, A_n$的重心。）

证明。让我们取任意点$Q$，用$\overrightarrow{a}$表示向量$\frac{1}{n} (\overrightarrow{QA}_1 + \dots + \overrightarrow{QA}_n)$，用$O$表示$\overrightarrow{QO} = \overrightarrow{a}$。然后
$$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = (\overrightarrow{OQ} + \overrightarrow{QA}_1) + \dots$$
$$\dots + (\overrightarrow{OQ} + \overrightarrow{QA}_n) = n \overrightarrow{OQ} + (\overrightarrow{QA}_1 + \dots$$
$$\dots + \overrightarrow{QA}_n) = n (-\overrightarrow{a}) + n\overrightarrow{a} = \overrightarrow{0},$$
也就是说，点 $O$ 被排除。

让我们证明唯一的事情。让$\overrightarrow{O'A}_1 + \dots + \overrightarrow{O'A}_n = \overrightarrow{0}$。然后
$$(\overrightarrow{O'O} + \overrightarrow{OA}_1) + \dots + (\overrightarrow{O'O} + \overrightarrow{OA}_n) = \overrightarrow{0},$$
即，$n\overrightarrow{O'O} = \overrightarrow{0}$，因此$\overrightarrow{O'O} = \overrightarrow{0}$，因此点 $O$ 和 $O'$ 重合。

现在让我们证明定理2。设$H = \{A_1, \dots, A_n\}$为传递集，$O$为点$A_1, \dots, A_n$的重心。让我们取一个任意的自对齐$f$集合$H$，并表示当$f$移动$A'_1, \dots, A'_n$，$O'$时点$A_1, \dots, A_n$，$O$的图像。从等式 $\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$ 可以得出 $\overrightarrow{O'A'}_1 + \dots + \overrightarrow{O'A'}_n = \overrightarrow{0}$。但 $A'_1, \dots, A'_n$ 与 $A_1, \dots, A_n$ 相同，只是按其他顺序排列（自 $f(H) = H$ 起）。因此，根据需要重新排列项，对应关系$\overrightarrow{O'A'}_1 + \dots + \overrightarrow{O'A'}_n = \overrightarrow{0}$可以写成$\overrightarrow{O'A}_1 + \dots + \overrightarrow{O'A}_n = \overrightarrow{0}$。根据引理，$O'$与$O$重合，即$f(O) = O$。因此，对于任何自对准，集合 $H$ 点 $O$ 都会进入自身。从这里开始，正如定理 1 的证明一样，集合 $H$ 中的所有点与 $O$ 的距离相同。

从我们的证明可以清楚地看出，如果$H = \{A_1, \dots, A_n\}$是不在同一平面上的传递集，并且$O$是包含集合$H$的球体的中心，则$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$。

所有顶点的集合都是传递的多面体，称为传递多面体。根据定理2，存在一个通过其顶点的球体（外接球体）。从评论中可以看出，如果 $A_1, \dots, A_n$ 是传递多边形的所有顶点，并且 $O$ 是围绕它描述的球体的中心，则$\overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n = \overrightarrow{0}$。

正多边形

对于多边形，强传递性的形成如下：设$A_1, A_2$为多边形$M$的传递顶点，$l_1, l_2$为边，直颊到$A_1, A_2$，$\gamma_1, \gamma_2$为面，直颊到$l_1, l_2$；那么一定存在满足条件$f(A_1) = A_2$、$f(l_1) = l_2$、$f(\gamma_1) = \gamma_2$的自组合$f \in \Gamma(M)$。具有强传递性的多面体称为正多面体$^*$。

任务 10. 证明满足条件 $f(A_1) = A_2$、$f(l_1) = l_2$、$f(\gamma_1) = \gamma_2$（在强及物性定义中讨论）的自组合$f \in \Gamma(M)$是唯一的。

11. 证明群$\Gamma(M)$的元素个数大于正多边形$M$的个数。

令$M$为正多边形，$\gamma$其面，$A_1$和$A_2$其两个顶点，以及$l_1, l_2$多边形的边$\gamma$，直边到顶点$A_1, A_2$。由于强传递性的性质，存在满足条件$f(\gamma_1) = \gamma_2$的$f \in \Gamma(M)$自组合。

*) 正多边形的这一定义与学校定义相同（“几何 9-10”，第 54 节）。 “在一个方向上”这一点现在将得到证明。

⟦folio 7⟧

小偷条件$f(\gamma) = \gamma, f(A_1) = A_2, f(l_1) = l_2$。第一个等式意味着 $f \in \Gamma(\gamma)$。我们看到多边形$\gamma$是强传递性的，即右与。

根据多边形$M$的强传递性性质，还可以得出它的所有面都是全等的。此外，从传递性的性质（下文中广义化，不强）可知，每个顶点与相同数量的面相邻。因此，正多边形的所有面都是全等的正多边形，并且每个顶点都有相同数量的与其相邻的面。

引理。令 $M$ 为正多边形，$A$ 其顶点之一，$AB_1$，...，$AB_k$ 与其相邻的边。那么多边形$B_1...B_k$是正多边形。

证明。让我们用 $\gamma_1$、...、$\gamma_k$ 表示与顶点 $A$ 相邻的面，用 $O$ 表示围绕多边形 $M$ (图 4) 描述的球体的中心。由于$|OB_1| = |OB_2| = R$（其中$R$是外接球的半径），向量$\vec{b}_1 = \vec{OB}_1, \vec{b}_2 = \vec{OB}_2$和$\vec{p} = \vec{B}_1\vec{B}_2$满足条件$\vec{b}_1^2 = \vec{b}_2^2 = (\vec{b}_1 + \vec{p})^2$，即$2\vec{b}_1\vec{p} = -\vec{p}^2$。此外，由于$|AB_1| = |AB_2| = a$，其中$a$是多边形$M$的边长，因此向量$AB_1 = \vec{a}_1, AB_2 = \vec{a}_2$满足条件$\vec{a}_1^2 = \vec{a}_2^2 = (\vec{a}_1 + \vec{p})^2$，即$2\vec{a}_1\vec{p} = -\vec{p}^2$。所以$2\vec{a}_1\vec{p} = 2\vec{b}_1\vec{p}$就是$\vec{p}(\vec{a}_1 - \vec{b}_1) = 0$，也就是$(AO) \perp (B_1B_2)$。同样的计算表明，每条线$(B_1B_3), ..., (B_1B_k)$都垂直于$(AO)$。因此，通过点$B_1$并垂直于线$AO$的平面$\Pi$包含所有点$B_1, B_2, ..., B_k$。进一步，由于强传递性，$f \in \Gamma(M)$存在自组合，将顶点$A$、边$AB_1$和面$\gamma_1$分别映射为顶点$A$、边$AB_2$和面$\gamma_2$。具体来说，$f(B_1) = B_2$。在这种自对准中，脸的两侧$\gamma_1$，直向$A$，将进入脸的两侧$\gamma_2$，直向$A$，即$AB_1$将前往$AB_2$，$AB_2$将前往$AB_3$ （图4）。所以，$f(B_2) = B_3$。以类似的方式推理，我们发现当移动$f$时，点$B_1, ..., B_k$会循环重新排列：$f(B_1) = B_2, f(B_2) = B_3, ..., f(B_{k-1}) = B_k, f(B_k) = B_1$。因此，位于平面 $\Pi$ 中的多边形 $B_1...B_k$ 是规则的。

经过证明的引理可以让人们轻松计算正多边形的基本参数。例如，让我们找到一个围绕正多边形外接的球体的半径，该正多边形的每个顶点都有 $k$ 面，这些面是正则 $n$ 边形（我们用 $a$ 表示边长）。我们有：$AB_1B_2 = \frac{180^\circ}{n}$（面$\gamma_1$是常规的$n$边形）。从三角形$AB_1B_2$有一个$k$边形$B_1B_2...B_k$：

⟦folio 8⟧

$$\left| B_1 B_2 \right| = 2a \cos \frac{180^\circ}{n},$$
然后我们找到它周围的外接圆的 $r = \left| QB_1 \right|$ (图 5)：

$$r = \frac{\left| B_1 B_2 \right|}{2 \sin 180^\circ / k} = a \cdot \frac{\cos 180^\circ / n}{\sin 180^\circ / k}.$$

接下来，从三角形$QAB_1$和$OAB_1$有$\frac{r^2}{a^2} + \frac{|AQ|^2}{a^2} = 1$，$|AQ| = \frac{a^2}{2R}$，即$\frac{r^2}{a^2} + \left(\frac{a}{2R}\right)^2 = 1$。在这里代替 $r$ 的值，我们得到以下结果：

$$R = \frac{a}{2\sqrt{1 - \left(\frac{\cos 180^\circ / n}{\sin 180^\circ / n}\right)^2}}.$$

公式 (*) 不仅给出了围绕给定正多面体描述的球体半径的表达式，还允许您指示 $n$ 和 $k$ 可以取什么值。确实，从$n \geq 3$、$\frac{180^\circ}{n} \leq 60^\circ$、$\cos \frac{180^\circ}{n} \geq \frac{1}{2}$开始；因此，$\sin \frac{180^\circ}{k} > \frac{1}{2}$（其根部表达式不会为正），因此$k < 6$。给定数字$k$可能的值​​$k = 3, 4, 5$，我们发现根式表达式仅在五种情况下为正，这对应于五种可能的正多面体（参见“几何9-10”，第133页）。

任务 12.
使用公式 (*) 求出围绕每个正多面体描述的球体的半径。 （这个问题及后续问题将在下一期«Kvant»给出答案）。

笔记。求 图 6 上三角形的边长，并由此推导出$\cos 36^\circ = \frac{\xi}{2}$、$\sin 36^\circ = \frac{\sqrt{5}}{2\sqrt{\xi}}$、$\sqrt{3 - 4\cos^2 36^\circ} = \frac{1}{\xi}$，其中$\xi = \frac{1 + \sqrt{5}}{2}$。

13. 对于每个正多面体，求其边缘从外接球体中心可见的角度。

14. 计算每个正多面体的表面积，已知 $a$ 其边。

15. 证明对于每个正多面体，都有一个球体接触其所有边缘。

16. 计算正聚酰胺的高度$h$，其底边是正多面体的面，顶点与多面体外接球的中心$O$重合。证明半径为$h$的球体

图 6.
中心为 $O$ 包含在正多面体中，并接触其所有面（内接球面）。

17. 计算每个正多面体的体积，已知 $a$ 其边。

18. 设 $M$ 为正多面体。 $M^*$ 表示多面体，其顶点是多面体 $M$ 面的外接圆的中心。证明多面体$M^*$（称为多面体$M$的对偶）是正则多面体。什么多面体是立方体的对偶？多德卡德鲁？

19. 设$a$为正多面体$M$的对偶角的大小，$\beta^*$为从外接球中心可见对偶多面体$M^*$的边缘的角度。证明$\alpha + \beta^* = 180^\circ$。使用它，计算每个正多面体的对偶角。

20. 证明正多面体的边的中点是花岗质多面体的顶点。

图 7 显示立方八面体 - 顶点为立方体边的中点（或八面体边的中点）的多面体。许多晶体具有立方八面体的形状；例如，在某些条件下 - 食盐结晶。

在我们对正多面体的讨论中，它们的存在问题仍未得到检验。毕竟，所有计算都是在假设存在一个正多面体的情况下进行的，其面是正$n$边形，并且每个顶点有$k$面与其相邻。结尾-

图 7.
