---
id: 2025-1-kozhevnikov-ob-invariantah-ponsele-i-puchkah-okruzhnostey-d6158c1e
issue: kvant_2025_1
year: 2025
number: "1"
title: 关于 Poncelet 不变量和圆铅笔
authors:
  - Кожевников П. А.
rubric: osnovnye-stati
page_first: 13
page_last: 20
page_labels: 15-18
tag: D87T
lang: zh
source: kvant_digital
content_sha256: 23dc98b12216d367666220e05c862b968a36d8284980d1521e1e7d632ba1442a
prompt_sha256: draft-1
translated_from: content/ru/2025/01/articles/04_kozhevnikov-ob-invariantah-ponsele-i-puchkah-okruzhnostey-d6158c1e.md
source_content_sha256: ca9aa5b6d66431f19c9463676ac740882d6a5e503ef291c53b7e8e89b4b6fdef
translation_model: draft
translation_run: zh-draft-2026-11-05
translation_quality: draft
---

⟦folio none⟧

关于 Poncelet 不变量和圆铅笔

科热夫尼科夫

围绕庞塞莱定理

庞斯莱定理是您可以欣赏不已的几何定理之一！让我们介绍其表述的“经典”版本之一（当然，变化和概括是已知的）。庞斯莱定理。设平面上有两个圆，第二个圆位于第一个圆内 (图 1)。

⟦figure⟧

图 1

假设有一条闭合的 n 链接折线，其所有顶点都位于第一个圆上，并且所有链接都与第二个圆相接触。那么，这样的闭合n环折线有无穷多条，第一个圆上的任意点都可以是这样的折线的顶点。因此，可以从第一个圆的任意点开始构建折线，绘制第二个圆的切线并获得第一个圆上的新交点。对于一对给定圆，逐步构建这样的折线称为 Poncelet 过程，折线本身（内接于第一个圆并外接于第二个圆）称为 Poncelet 折线或 Poncelet 轨迹。本质上，Poncelet 定理

DOI: https: doi.org 10.4213 kvant20250102

⟦column⟧

指出，如果 Poncelet 轨迹从第一个圆上的某个点开始，结果是周期性的，即在某个步骤后闭合，那么这个闭合轨迹可以在圆之间“旋转”。让我们问自己：Poncelet 轨迹有哪些有趣的特性？有趣的属性可能是不变量，即不依赖于轨迹选择的数量或特征。 “问题书 «Kvant»”中的问题 M2817 给出了度量不变量的示例（有关其解决方案，请参阅本期期刊）。该问题考虑一对圆，其中有一系列 Poncelet 内接 (2n)-边形，并指出面积与主对角线长度之和的比率是不变的，即任何 (2n)-Poncelet 三角形的值相同。解决方案 ���题 M2817 使用 (2n) 边形 Poncelet 系列的一个显着的几何不变量：它们的主对角线相交于一个固定点（与 (2n) 边形的选择无关）。我们将在本文末尾的问题 10 中解决这一事实。让我们考虑关于周期性 Poncelet 轨迹的另一个几何不变量的陈述。陈述。设一对圆：Z 为闭合 n 链接 Poncelet 轨迹。让我们考虑连杆与 Z 的 n 个接触点。那么这 n 个点的系统质心是一个固定点。因此，切点的质心，或更准确地说，n 个相等质量的系统的质心，

⟦folio 15⟧

---
running_head:
folio:
---

以 $S$ 为圆心，半径为 $t$ 的圆）。此条件将铅笔 $\Pi$ 的圆与以 $O_1O_2$ 为中心的所有圆区分开来。现在很容易检测光束中半径为零的圆 - 这些是线 $O_1O_2$ 上的点 $L_1$ 和 $L_2$，距离 $l$ 的距离为 $t$。这些点$L_1$和$L_2$称为束$\Pi$的对象点。

练习 8. 证明在 图 2 上，通过点 $L_1$ 和 $L_2$ 的圆铅笔中的任何圆都与铅笔 $\Pi$ 中的任何圆正交。

最后，如果$\omega_1$和$\omega_2$同心，则得到第四种类型，它们生成同心圆铅笔(图2,e)。

关键引理
关于蓬斯莱审判

从圆 $\omega$ 外的给定点 $A$ 可以检查到它的两条切线。为了准确理解我们正在谈论的是什么样的切线，让我们确定一些协议。此外，通过圆$\omega$，我们将了解圆及其遍历方向的选择（顺时针或逆时针）。我们假设仅当在接触点方向 $\overrightarrow{AX}$ 与圆 $\omega$ 的方向一致时，射线 $AX$ 才会接触 $\omega$。

令$\Omega$和$\omega$为一对圆，$\omega$位于$\Omega$内。让我们制定关键引理。

引理。令圆$\Omega$上的点$A_0, A_1, B_0, B_1$呈罂粟状，使得射线$A_0A_1$和射线$B_0B_1$在相应的（图3）的某些点$X_1$和$Y_1$处接触$\omega$。让线$X_1Y_1$与线$A_0B_0$相交于点$P_0$，并与线$A_1B_1$相交于点$P_1$。然后有一个圆$\gamma$与射线$A_0B_0$和$A_1B_1$相切于相应圆的$P_0$和$P_1$；与圆$\Omega$、$\omega$和$\gamma$对应。

证明。我们假设$B_0$和$\omega$位于$A_0A_1$的相对两侧；类似地考虑其他相互位置的情况。

直线$A_0A_1$和$B_0B_1$与圆$\omega$相切，这意味着角度$B_0Y_1X_1$和$Y_1X_1A_1$相等；我们用$t$表示它们的值。由于点 $A_0, A_1, B_0, B_1$ 位于同一圆上，因此角度 $P_1B_1Y_1$ 和 $X_1A_0P_0$ 相等。下一个，

$$\angle A_1P_1Y_1 = \angle P_1B_1Y_1 + \angle B_0Y_1X_1 =$$

$$= \angle X_1A_0P_0 + \angle Y_1X_1A_1 = \angle X_1P_0B_0.$$

我们看到$P_0P_1$和$A_0B_0$之间的角度等于$A_1B_1$和$P_0P_1$之间的角度，让我们用$s$表示这个角度的大小。根据这些角度的相等性，可以得出，有一个圆 $\gamma$ 与射线 $A_0B_0$ 和 $A_1B_1$ 在相应的点 $P_0$ 和 $P_1$ 处相切（$\gamma$ 内接于线 $A_0B_0$ 和 $A_1B_1$ 之间的角度）。

现在，考虑关系$\frac{pow(A_1,\omega)}{pow(A_1,\gamma)}$。它等于切线 $\frac{A_1X_1^2}{A_1P_1^2}$ 的平方之比，而根据三角形 $A_1X_1P_1$ 的正弦定理，它又等于 $\frac{\sin^2 s}{\sin^2 t}$。让我们输入$\lambda = \frac{\sin^2 s}{\sin^2 t}$。使用三角形$A_0X_1P_0, B_0Y_1P_0, B_1Y_1P_1$的正弦定理重复上述推理，我们发现每个比率$\frac{pow(A_0,\omega)}{pow(B_0,\omega)}, \frac{pow(B_1,\omega)}{pow(B_1,\gamma)}$也等于$\lambda$。这意味着点 $A_0, A_1, B_0, B_1$ 位于圆 $\omega$ 和 $\gamma$ 的阿波罗尼乌斯圆 $\lambda$ 上。因此，$\Omega$就是这个$\lambda$-阿波罗尼乌斯圆，因此$\Omega$、$\omega$和$\gamma$对应。引理已得证。

⟦folio 16⟧

---
running_head:
folio:
---

Poncelet 轨迹的推论。令$A_0A_1A_2 \dots$为Poncelet轨迹，即圆$\Omega$的点$A_0,A_1,A_2 \dots$是罂粟，光线$A_0A_1,A_1A_2 \dots$在某些点$X_1,X_2 \dots,X_n$对应处接触$\omega$。类似地，令 $B_0B_1B_2 \dots$ 为另一条 Poncelet 轨迹，$Y_1,Y_2 \dots$ 为相应的切点。然后
1) 射线$A_0B_0,A_1B_1 \dots$接触某个固定圆$\gamma$；
2) 圆 $\gamma$ 与 $A_iB_i$ 和 $A_{i-1}B_{i-1}$ 的切点位于直线 $X_iY_i$ 上（对于所有 $i=1,2,\dots$）；
3) 圆$\Omega$、$\omega$和$\gamma$对应。
证明。令 $\gamma_1$ 为来自关键引理的圆，与圆 $\Omega$ 和 $\omega$ 共同创建，并接触射线 $A_0B_0$ 和 $A_1B_1$。类似地，令 $\gamma_2$ 为关键引理的圆，射线 $A_1B_1$ 和 $A_2B_2$ 相切。圆$\gamma_1$和$\gamma_2$都属于由圆$\Omega$和$\omega$生成的光束$\Pi$。但在铅笔$\Pi$位于$\Omega$内部的圆圈中，至多有一个圆圈接触射线$A_1B_1$（例如，从铅笔的明确描述中可以看出 - 参见图2,b）。这意味着$\gamma_1$和$\gamma_2$是相同的，即这是同一个圆，我们称之为$\gamma$。继续用切线参数 $A_{i-1}A_i$ 和 $B_{i-1}B_i$ 进一步推理，我们得出结论 $\gamma$ 是所需的圆。
由此可见，根据关键引理，推论中的所有三个陈述都是正确的。
庞斯莱定理现已得到非常简单的证明。

庞斯莱定理的证明。令$A_0A_1A_2 \dots A_n$和$B_0B_1B_2 \dots B_n$为两条Poncelet轨迹（对于圆$\Omega$和$\omega$），已知第一条轨迹是闭合的，即$A_n = A_0$。根据已证明的推论，存在一个固定圆$\gamma$，使得所有光线$A_iB_i$、$i=1,2,\dots$都接触$\gamma$。特别是，射线$A_0B_0$和射线$A_nB_n$，与射线$A_0B_n$重合，接触$\gamma$。但是，根据我们的协议，有一条光线从 $A_0$ 开始接触 $\gamma$。这意味着光线$A_0B_0$和$A_0B_n$重合，从而$B_n = B_0$。 Q.E.D.

关键引理的一些其他推论收集在文章末尾的问题 8-11 中。

切点的质心
现在让我们稍微重新表述一下关于质心的陈述并证明它。
陈述'。设 $A_0A_1 \dots A_n$ 为圆 $\Omega$ 和 $\omega$ 的 Poncelet ($A_n = A_0$) 闭合轨迹，射线 $X_1,X_2 \dots,X_n$ 为与 $\omega$ 连线的切点。类似地，令 $B_0B_1 \dots B_n$ 为另一条（闭合）Poncelet 轨迹，$Y_1,Y_2 \dots,Y_n$ 为与 $\omega$ 的连线的相应切点。那么点$X_1,X_2 \dots,X_n$的质心与点$Y_1,Y_2 \dots,Y_n$的质心重合。

证明。检查向量 $S = \overrightarrow{X_1Y_1} + \overrightarrow{X_2Y_2} + \dots + \overrightarrow{X_nY_n}$ 之和是否为零就足够了。

众所周知，所有光线$A_iB_i$都接触一个固定的圆$\gamma$，与圆$\Omega$和$\omega$共同创建。设$r$和$\rho$分别为圆$\omega$和$\gamma$的半径。使用与图 3 类似的表示法，令$P_i$ 为$A_iB_i$ 与圆$\gamma$ 的切点。我们知道点 $P_{i-1},X_i,Y_i,P_i$ 位于同一条直线上。让我们证明 $\overrightarrow{X_iY_i}$ 与 $\overrightarrow{P_{i-1}P_i}$ 成比例，具有相同的比例系数。从这里开始，立即得出等式 $S = \vec{0}$，因为向量 $\overrightarrow{P_0P_1} + \overrightarrow{P_1P_2} + \dots + \overrightarrow{P_{n-1}P_n}$ 的总和非常为零（因为 $P_n = P_0$）。

我们有$X_1Y_1 = 2r\sin t, P_0P_1 = 2\rho\sin s$。正如我们所见，

$$\lambda = \frac{\sin^2 s}{\sin^2 t} = \frac{pow(M,\omega)}{pow(M,\gamma)}$$

不依赖于点的选择 $M$ 圆圈 $\Omega$。我们得到 $\overrightarrow{X_1Y_1} = \mu \overrightarrow{P_0P_1}$， 在哪里 $\mu = \frac{r}{\sqrt{\lambda} \cdot \rho}$。系数 $\mu$ – 常数，仅取决于圆 $\Omega$, $\omega$, $\gamma$，所以我们类似地得到 $\overrightarrow{X_iY_i} = \mu \overrightarrow{P_{i-1}P_i}$ 对于每个人 $i$。这衡量了证明。

最后，我们提出了有关正在讨论的主题的一系列问题。

⟦folio 17⟧

---
running_head:
folio:
---

关于同轴圆的各种问题

1. 两只甲虫$A$和$B$沿着相交于点$S$的直线以恒定速度爬行。证明所有圆 ($ASB$) 同轴。

2. 两个圆 $\omega_1$ 和 $\omega_2$ 相交于点 $P$ 和 $Q$。考虑点对 $A_1 \in \omega_1$、$A_2 \in \omega_2$ 以及$A_1A_2$ 通过$P$。证明线段$A_1A_2$的中点$M$总是可以位于与$\omega_1$和$\omega_2$同轴的圆上。如果$x^2 + y^2 + a_i x + b_i y + c_i = 0$是圆$\omega_i$的标准方程，那么这个圆的方程是什么？

将此结果推广到点 $M$ 按固定比率除以 $A_1A_2$（即 $\overline{A_1M} = \lambda \overline{MA_2}$）。

3. 给定圆 $\Omega$ 和 $\omega$，并且 $\omega$ 位于 $\Omega$ 内部。令$L$为$\Omega$和$\omega$生成的铅笔的极限点，位于$\omega$内部。让线 $l$ 与 $\Omega$ 相交于点 $A$ 和 $B$。

a) 让$l$接触$\omega$点$N$。证明$\angle ALN = \angle BLN$。

b) 让$l$与$\omega$相交于点$C$和$D$。证明$\angle ALC = \angle BLD$。

4（关于同轴圆的“Ceva 定理”）。设给定的三个不同的圆为$\omega_i$，$i = 1, 2, 3$。令$\gamma_1 - \lambda_1$为$\omega_2$和$\omega_3$的阿波罗圆（即$\gamma_1$是$pow(M, \omega_2) = \lambda_1pow(M, \omega_3)$的点集）。同样，$\gamma_2 - \lambda_2$是$\omega_3$和$\omega_1$的阿波罗圆，$\gamma_3 - \lambda_3$是$\omega_1$和$\omega_2$的阿波罗圆。证明若$\lambda_1\lambda_2\lambda_3 = 1$，则$\gamma_1$、$\gamma_2$、$\gamma_3$同轴。

5. 四条直线构成一个四边形：设$ABC$为由支流构成的三角形，四条直线分别与直线$BC$、$CA$、$AB$相交于点$A'$、$B'$、$C'$。证明在对角线$AA'$、$BB'$、$CC'$和直径上构造的圆同轴，且这些圆的根轴是包含三角形$ABC$、$A'B'C$、$B'C'A$、$C'A'B$的重心的奥伯直线。

6（L. Shatunov、V. Shelomovsky，以 I.F. Sharygin 命名的奥林匹克运动会，2024 年，重新制定）。设给定的两条相交线$x$、$y$和四边形$AA'BB'CC'$（点的指定方式与上一问题相同）。接下来，用$K_x$、$K_y$表示点$K$到线$x$和$y$的投影。已知 $A_x$、$A_x'$、$A_y$、$A_y'$ 位于同一个（踏板）圆 $\alpha$ 上，$B_x$、$B_x'$、$B_y$、$B_y'$ 位于同一个圆 $\beta$ 上。证明$C_x$、$C_x'$、$C_y$、$C_y'$位于同一个圆$\gamma$上，同时$\alpha$、$\beta$、$\gamma$同轴。

评论。已知教师圈存在的条件（$A_xA_x'A_yA_y'$) 等价于点的等角性 $A$ 和 $A'$ 相对于之间的角度 $x$ 和 $y$。正如我们所看到的，这个问题立即暗示了等角定理。此外，如果作为 $x$ 和 $y$ 取四边形的两条边（例如， $ABC'$ 和 $ACB'$），然后我们得到了上一个关于圆的同轴度问题的陈述 $AA'$, $BB'$, $CC'$ 如直径。

7. 给出了同轴圆$\Omega$、$\omega_1$、$\omega_2$、$\omega_3$。三角形$A_1A_2A_3$内接于圆$\Omega$，而$A_1A_2$在点$T_3$处接触$\omega_3$，$A_2A_3$在点$T_1$处接触$\omega_1$，$A_3A_1$在点$T_2$处接触$\omega_2$。证明 $T_1$、$T_2$、$T_3$ 位于同一条直线上，或 $A_1T_1$、$A_2T_2$、$A_3T_3$ 相交于一点。

关键引理的推论

8. 内接四边形$ABCD$的对角线相交于点$E$。让圆$\omega$接触线段$AE$和$BE$，并在点$T$处接触圆($ABCD$)。证明有一个圆在点 $T$ 处与 ($ABCD$) 相切，并且也与直线 $AD$ 和 $BC$（或 $AB$ 和 $CD$）相切。

9（圆铅笔的庞斯莱定理）。圆 $\Omega$、$\omega_1$、$\omega_2$、... 的广义 Poncelet 过程定义如下：从点 $A_0 \in \Omega$ 构造一个序列 $A_0$、$A_1$、$A_2$、... 圆 $\Omega$ 的点，使得射线 $A_{i-1}A_i$ 接触 $\omega_i$ for $i = 1, 2, \dots$。

圆铅笔的 Poncelet 定理指出，如果圆 $\Omega$、$\omega_1$、$\omega_2$、... 是同轴的，并且初始点为 $A_0$ 的广义 Poncelet 过程在第 $n$ 步闭合，那么对于任何初始点，它将在第 $n$ 步闭合。

证明这个定理（在所有 $\omega_i$ 都位于 $\Omega$ 之内的情况下）。

10. a) 令$\Omega, \omega_1, \omega_2$为属于同一束$\Pi$的圆，使得$\omega_1$、$\omega_2$位于$\Omega$内部。令$A_0$、$A_1$、$A_2$ 为$\Omega$ 上的点，使得光线$A_0A_1$ 接触$\omega_1$，并且光线$A_1A_2$ 接触$\omega_2$。证明所有可能的射线$A_0A_2$都与铅笔$\Pi$的固定圆相切。

11. 证明在Poncelet过程中$A_0$、$A_1$、$A_2$...对于圆$\Omega$和$\omega$，对于任何自然数$k$，所有$A_iA_{i+k}$形式的“对角线”都与与$\Omega$和$\omega$同轴的固定圆相切。

检查广义 Poncelet 过程（对于铅笔圆圈）是否也是如此。

（Poncelet 定理本质上是该陈述的部分情况：在闭包 $A_n = A_0$ 的情况下，“对角线”$A_0A_n$“接触”$\Omega$。）

b) 令 $A_0A_1...A_{2n}$ 为圆 $\Omega$ 和 $\omega$ 的闭合 Poncelet 轨迹（使得 $\omega$

⟦folio 18⟧

---
running_head:
folio:
---

内Ω）。证明“对角线”$A_0 A_n$、$A_1 A_{n+1}$、...、$A_{n-1} A_{2n-1}$穿过由Ω和ω生成的铅笔的极限点。

11（梁上的加法运算）。考虑一支不与圆相交的铅笔 Π，以及一支与 Π 相交的铅笔 Ω。令 $\Pi'$ 为 Π 的圆的子集，包括 Ω 和位于 Ω 内部的 Π 的所有圆。对于每个圆$\omega \in \Pi'$，如果射线$AB$接触ω，我们通过条件$g_\omega(A) = B$定义（一对一）映射$g_\omega : \Omega \rightarrow \Omega$。

a) $g_\omega g_\bar{\omega}$ 的组合是什么，其中 $\bar{\omega}$ 表示与 ω 相同的圆，但遍历方向不同？对于每个圆$\omega$，变换$g_\omega$是恒等变换吗？

6) 证明对于某个圆 $\omega_3 \in \Pi'$，合成 $g_\omega_1 g_\omega_2$ 等于 $g_\omega_3$。

b) 证明对于任意 $\omega_1$，$\omega_2 \in \Pi'$ $g_\omega_1 g_\omega_2 = g_\omega_2 g_\omega_1$ 为真。

d) 在集合$\Pi'$的元素上，我们定义加法运算：我们将$\omega_3 = \omega_1 + \omega_2$放在$g_\omega_3 = g_\omega_1 g_\omega_2$的情况下。这个操作有什么属性呢？如何根据此加法来指定 Poncelet 轨迹的周期性条件？

问题 12 – 15 考虑圆 Ω 和 ω 的闭合 Poncelet 轨迹 $A_0 A_1 \dots A_n$，圆心分别为 $O$ 和 $I$，半径分别为 $R$ 和 $r$（圆 $\omega$ 位于圆 Ω 内）； $X_i$ – $A_{i-1} A_i$ 与 ω 的切点，$G$ – （相等）质量$X_1, X_2, \dots, X_n$ 的中心。

12. 证明$G$位于直线$OI$上。

13. 考虑从 $A_{i-1}$ 逆时针穿过 $A_i$ 的弧 $A_{i-1} A_i$ 的中点的质心，$i = 1, \dots, n$。证明该质心恒定且位于直线 $OI$ 上。

14（关于距离总和的函数）。令$\vec{e}_i$为与$\overrightarrow{A_{i-1} A_i}$同位的单位向量，$\vec{n}_i$为$\vec{e}_i$逆时针旋转$90^\circ$的结果（因此$\vec{n}_i$为线$A_{i-1} A_i$的单位法线向量）。考虑从平面上的点 $M$ 到线 $A_{i-1} A_i$ 的定向距离的（线性）函数 $\rho(M, A_{i-1} A_i)$（可以用向量的标量积表示为 $\rho(M, A_{i-1} A_i) = \overrightarrow{A_i M} \cdot \vec{n}_i$）。对于闭合 Poncelet 轨迹 $A_0 A_1 A_2 \dots A_n$，我们定义（线性）函数

$$f(M) = \sum_{i=1}^{n} \rho(M, A_{i-1} A_i).$$

a) 证明向量 $\vec{n} = \sum_{i=1}^{n} \vec{n}_i$ 是 Poncelet 不变量（即不依赖于轨迹的选择）。

6) 证明函数 $f$ 是 Poncelet 不变量。

b) 证明和 $\sum_{i=1}^{n} \cos \angle A_{i-1} A_{i+1} A_i$, $\sum_{i=1}^{n} \cos \angle A_{i-1} A_i A_{i+1}$ 是 Poncelet 不变量。

d) 让 $n = 3$，即考虑 Poncelet 三角形族。

证明则$f(O) = r + R$（卡诺公式）；直线（水平线）$f(M) = 0$ 与直线 $A_{i-1} A_i$ 相交于三角形 $A_0 A_1 A_2$ 的外二等分线的底边。

对于 Poncelet 三角形的 $\omega - A_0$ 扩张圆$A_0 A_1 A_2$ 的情况证明类似的事实（当然，在这种情况下，$\omega$ 不会位于 Ω 内部）。证明（通过考虑 Poncelet 三角形的极限情况）线 $f(M) = 0$ 与 Ω 的交点位于圆 Ω 和 ω 的公切线上。

15（F. Nilov；围绕到接触点的距离平方和）。考虑（二次）函数 $q(M) = \sum_{i=1}^{n} M X_i^2$。可以很容易地看出（例如，使用标量积），$q(M) = n M G^2 + q(G)$（对于具有质心$G$的任意点$X_1, \dots, X_n$都是如此）。

a) 证明$q$是Poncelet不变量。

6) 解决问题 M2668“问题书 «Kvant»”（作者 – I. Vainshtein）的以下泛化：

让$n = 2m$，让我们考虑$(2m)$-Poncelet-gons。证明 $\sum_{i=1}^{2m} \frac{A_i A_{i+1}}{A_{i+m} A_{i+m+1}} - \infty$ 是 Poncelet 不变量（索引被视为模 $2m$）。

16（P. Kozhevnikov；围绕广义 Poncelet 过程的切点质心）。考虑圆 Ω、$\omega_i$ 的闭合 Poncelet 轨迹 $A_0 A_1 \dots A_n$，其中心分别为 $O$ 和 $I_i$，半径分别为 $R$ 和 $r_i$（$\omega_i$ 在 Ω 内）、$i = 1, \dots, n$； $X_i - точки касания $A_{i-1} A_i$ с ω$_i$. (Будем полагать $r_i > 0$, если выбранное на ω$_i$ направление обхода совпадает с направлением обхода Ω, и $r_i < 0$ в противном случае.)

Пусть $d_i - 从$M \in \Omega$到ω$_i$绘制的切线段（即该点的次数的根）的长度；由于共同基础，关系$d_1 : d_2 : \dots : d_n$不依赖于点$M \in \Omega$的选择。让我们输入$m_i = \frac{d_i}{r_i}$。

a) 证明广义陈述：位于点 $X_1, X_2, \dots, X_n$ 的质心 $m_1, m_2, \dots, m_n$ 是 Poncelet 不变量。
