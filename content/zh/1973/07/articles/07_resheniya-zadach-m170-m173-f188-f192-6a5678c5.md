---
id: 1973-7-resheniya-zadach-m170-m173-f188-f192-6a5678c5
issue: kvant_1973_7
year: 1973
number: "7"
title: 问题解决方案M170—M173； F188—F192
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 30
page_labels: 26-28
tag: PT4C
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f9b7ca6040e5718337c36b9734058fb5db72b900b3b7a1ce1e0e576a9c2c1ffb
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/07_resheniya-zadach-m170-m173-f188-f192-6a5678c5.md
source_content_sha256: 8f074fe59e394b1271d75a1ba0d97a0c3be5e8c75d0b034c3985d4811ab08699
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

问题解决方案

M170—M173; F188—F192

M170。 a) 设$M$和$N$为三角形ABC内接于AB和AC边的圆的切点，P为直线MN与角B平分线的交点。证明角BPC是直角。

b).证明一个更普遍的事实：如果点O位于三角形内部，则$BOC - BAO = 90^\circ$、M和N是从O点到边AB和AC的垂线的底极大值，P是直线BO和MN的交点，则$BPC = 90^\circ$（图1）。

问题a)实际上是6)的特例：如果O是内切圆的圆心，则OCB和OBC角之和中的BOC等于180°，并且相同角之和中的BAO等于三角形内角和的一半，即90°。

让我们立即解决问题6)。为了确定该点，让 P 位于点 N 之外的线段 MN 的延续上，就像我们的 图 上一样。 （其他情况也类似分解，大家可以自己轻松处理。）因此，根据条件$OMA = ONA = 90^\circ$，四边形OMNA的向量可以用圆来描述，因此，

$$OMM = OAM = BAO.$$

现在让我们证明点 O、N、P 和 C 位于同一个圆上。确实，$CNP = MNA = 90^\circ - MNO = 90^\circ - BAO = 180^\circ - BAO$。

使用问题的条件：$BOC - BAO = 90^\circ$，我们得到$CNP = CPO$。

最后，由于四边形 CONP 是循环的，因此我们需要的等式 $CPO = CNO = 90^\circ$ 如下。

I.F.沙里钦

M171。在平面上画一条规则的六维木板，其边长等于 1。用尺子构造出长度为 $\sqrt{7}$ 的线段。

您可以轻松证明图 2 上红色线段的长度等于$\sqrt{7}$。

图 2.

M172。证明对于任何素数 p $\underline{11\dots1}$ $\underline{22\dots2}$ $\underline{33\dots3}$ $\dots$ $\underline{99\dots9}$ $= \underline{10\dots02}$ $\underline{0\dots03}$ $\dots$ $\underline{0\dots08}$ $\underline{0\dots09}$ $= 10^8p + 2 \cdot 10^7p + 3 \cdot 10^6p + \dots + 8 \cdot 10^p + 9 = C$, $\underline{11\dots1} = E$。

显然$B = E \cdot C$，$C - A = (10^8p - 10^8) + 2 (10^7p - 10^7) + 3 (10^6p - 10^6) + \dots + 8 (10^p - 10)$，$10^p - 10 = (9 \cdot E + 1) - 10 = 9 (E - 1)$。

根据费马小定理（参见 «Kvant» No. 10 (1972)），对于任何素数 $p$ 和任何自然数 $n^p$ - n 都可以被 $p$整除

⟦folio 27⟧

特别是，$10^p - 10, 10^2p - 10^2, \dots, 10^8p - 10^8$可以被$p$整除。所以$C - A$可以被$p$整除，$9(E - 1)$可以被$p$整除。

由于数字$A$的各位数字之和为45，因此$A$能被9整除，因此$A(E - 1)$能被9$(E - 1)$整除。因此，$A(E - 1)$可以被$p$整除。

因此，$B - A = EC - AE + AE - A = E(C - A) + A(E - 1)$能被$p$整除，这就是需要证明的。

M·L·格弗

M173。在距离方表$4 \times 4$中，数字为1、2、3、...、最多16，即每行、每列、两条对角线上的所有行中的数字之和等于相同的数字，1和16站在表格的相对角上。让我们证明，在这个二次方程中，关于中心对称的任何两个数字的总和等于 17。对于数字 1 和 16，这在条件上是成立的。假设 1 在左上角，16 在右下角，那么同一对角线上的其他两个数字 - 让我们用 $a$ 和 $a'$ 表示它们 - 满足等式 $a + a' = 17$。让我们始终同意用 $x' : x' = 17 - x$ 来表示 $x$ 至 17 的附加数字。

现在让我们使用 图 3 上给出的符号（$S_i$ 表示相应单元格中的数字之和）。

以下等式成立：
$$S_1 + c + d + a + a' + S_2 + S_3 + c + d + a + a' + S_4 + 2(b + c + d + e) = 34 \cdot 6$$

图 3.

图 4.

图 5.

⟦folio 28⟧

图 6.

F188。容量为$P$的冰箱在$t$的时间内将$n$升的水变成了冰，最初的温度为$t^\circ$℃。这段时间房间里释放了多少水？

从任何制冷机组的运行原理来看，冰箱从网络消耗的所有能量以及从冷却产品（在本例中为水）中分离出来的能量都转化为热量。这意味着在$t$、$Q = P\tau + c_B m_B t^\circ + \lambda m_B$时间内房间释放的热量，

其中$m_B = n$是以千卡表示的水质量，$c_B$是水的比热容，$\lambda$是冰融化的比热。

I.Sh.斯洛博杰茨基

F189。电荷 $q = 10^{-8}$ 均匀分布在半径为 $R = 1$ cm、距离角为水、$\lambda = 2/3$ π 弧度的圆的灵魂上。确定圆中心的电场强度。

a) 电弧的体积被分成$n$等份，每份的电荷为$q/n$。当达到较大的$n$（$\pi R/n \ll R$）时，这些费用可以被认为是准确的。每个电荷都会在圆中心产生一个强度 $\Delta E_i$ 大小相等的场

$$\Delta E_i = k \frac{q}{nR^2},$$

其中$k = \frac{1}{4\pi\epsilon_0} = 9.10^9 \text{ nm}^2/\text{k}^2$。向量$\Delta E_i$的方向如图6,a所示。

为了找到总场强 $E = \sum_{i=1}^{n} \Delta E_i$，我们只需将这些向量相加，将每个向量的开头放在前一个向量的末尾 (图 6.6)。 $E$的值越大，$n$的测定精度越高。

很容易注意到，当$n$到达由向量$\Delta E_i$相加形成的一条大折线时，我们可以注意到一个半圆，并且向量$E$的大小在数值上等于其直径。对于半圆，$l$ 等于

$$l = n \Delta E_i = n \frac{kq}{nR^2} = \frac{kq}{R^2}.$$

另一方面，$l = \pi E/2$。

从这里

$$E = \frac{2l}{\pi} = \frac{2kq}{\pi R^2} = 5.7 \cdot 10^5 \text{ σ/m}.$$

6) 对于具有任意张角$\varphi$的圆弧问题也可以类似地解决。在这种情况下，矢量 $E$ 是圆弧的弦 (图 7.6)。弧长为$l = n \Delta E_i$，圆心角为$\varphi$（pad）（$\varphi$是向量$\Delta E_i$之间的最大角度）。

让我们表示圆 $r$ 的半径，并通过它表达弧 $l$ 和弦 $E$ 的长度：

$$l = r \varphi, \quad E = 2r \sin \frac{\varphi}{2}.$$

但$l = n \Delta E_i = kq/R^2$因此

$$E = 2 \frac{kq}{\varphi R^2} \sin \frac{\varphi}{2}.$$

对于 $\varphi = 2/3$ π 我们得到

$$E = 7.4 \cdot 10^5 \text{ σ/m}.$$

V·G·斯韦特莫扎罗夫

F190。负载通过边缘 $a$ (图 8) 用绳子绑在方形梁 $c$ 上。绳子长度$l = na$（$n$为整数）。负载在垂直于绳索的方向上的速度为 $V$。整根绳子绕在横梁上需要多长时间？

让我们考虑初始时刻绳索平行于梁的一个侧面 ($\alpha = 0$) 的情况。负载开始围绕边缘 $A$ 沿半径为 $l$ 的圆以线速度 $V$ 移动。四分之一圈后，绳索接触梁的边缘，负载沿半径$l - a$的圆以相同的线速度移动。再转四分之一圈后，圆的半径将变为$l - 2a$，依此类推。
