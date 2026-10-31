---
id: 1972-10-grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22
issue: kvant_1972_10
year: 1972
number: "10"
title: “从头到尾”解决问题的方法
authors:
  - Груденов Я. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: DPHK
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f3c02361e1cf1e1a90f8512f6e39b6b15e29fe3eff42aed036b2ca228a44ecd4
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/12_grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22.md
source_content_sha256: 531f1bb66fe344036d290266aac5927f3cb137023875c66c02f276300cef435a
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

“从头到尾”解决问题的方法

通常，我们解决问题或证明定理是从已知到未知，从给定到期望。但你可以采取不同的行动。这里我们将考虑“从头开始”解决问题的方法，即从未知到已知、从期望到给定进行推理。

总体方案

有必要证明一些断言$A$。让我们假设这是真的，并且根据问题的数据和已知定理，我们将尝试从$A$获得正确的推论。在这种情况下，有几种情况是可能的。

1. 获得了错误的结果。这意味着我们关于陈述$A$有效性的假设是错误的。用这条定律解决问题——我们发现$A$是不正确的。

2. 获得了错误的结果。在这种情况下，您应该检查参数的可逆性，因为从错误的陈述（例如，$a = -a$，$a \neq 0$）中，您也可以获得正确的结果（$a^2 = a^2$）。

a) 如果所有推理都相反，则 $A$ 为真。

b) 如果争论中存在不可逆转的争论（例如，在某个阶段我们对等式进行了平方），那么就需要使用其他方法来寻找问题的解决方案。

3. 如果无法获得正确的结果，那么也是时候转向其他方法了。

两条指令

1. 在得到的中间表达式中，希望减少参数的数量，然后简化这些表达式。

2. 如果任务不包含不必要的条件*，则必须使用所有任务数据。

示例

示例 1. 在直角三角形 ABC 中，数字 AC 是数字 AB 的三倍。 K点和M点的AC棋子被分成三等份。证明$\triangle AMB + \triangle AKB + \triangle ACB = 90^\circ$。

解决方案e.令 $\triangle AMB = \alpha$、$\triangle AKB = \beta$、$\triangle ACB = \gamma$ (图 1)。假设 $\alpha + \beta + \gamma = 90^\circ$ (1)

或者，从$\alpha = 45^\circ$开始，

$$\beta + \gamma = 45^\circ.$$ (1a)

然后

$$tg(\beta + \gamma) = tg 45^\circ,$$ (2)

$$\frac{tg \beta + tg \gamma}{1 - tg \beta \cdot tg \gamma} = 1.$$ (2a)

*) 找到其条件的线是该解决方案的一大优势，但通常竞争性线问题不包含其条件。

⟦folio 48⟧

等式 (2) 或 (2a) 成立，因为
$$tg \beta = \frac{AB}{AK} = \frac{1}{2}, \quad tg \gamma = \frac{1}{3}$$

和
$$\frac{\frac{1}{2} + \frac{1}{3}}{1 - \frac{1}{2} \cdot \frac{1}{3}} = 1.$$

学生一般都会完成问题的解答，即

**图 1.**

一个错误。开始反转转换，我们注意到从等式（2）的有效性来看，它遵循的不是等式（1a），而是依赖性
$$\beta + \gamma = 45^\circ + 180^\circ \cdot n,$$
其中 $n = 0; \pm 1; \pm 2; \pm 3; \dots$

但从三角形$AKB$和$ACB$我们发现$0 < \beta < 45^\circ; 0 < \gamma < 45^\circ$因此
$$0 < \beta + \gamma < 90^\circ.$$

因此，从对应关系（2）和（3）得出$\beta + \gamma = 45^\circ$，并且，由于$\alpha = 45^\circ$，因此$\alpha + \beta + \gamma = 90^\circ$。

例2.证明在任意三角形$R = \frac{a \cdot b \cdot c}{4S}$中，$a, b, c$是三角形的边，$S$是三角形的面积，$R$是外接圆的半径。

解决方案e.假设等式成立：
$$R = \frac{a \cdot b \cdot c}{4S}.$$

让我们减少参数的数量：
$$R = \frac{a \cdot b \cdot c}{4 \cdot \frac{1}{2} b \cdot c \cdot \sin A}, \quad R = \frac{a}{2 \cdot \sin A},$$

在哪里
$$2R = \frac{a}{\sin A},$$

根据正弦定理，这是正确的。所有变换都很容易处理，因此等式（4）得到证明。

例3. 三角形$a, b, c$($a < b < c$)的边构成一个算术过程。证明$ac = 6Rr$，其中$R$是三角形的外接圆半径，$a$$r$是三角形的外接圆半径。

解决方案e.令等式$ac = 6Rr$为真。让我们通过用三角形的边来表示$R$和$r$来减少参数数量：$R = \frac{abc}{4S}, r = \frac{S}{p}$，其中$S$是三角形的面积，$p$是三角形的半周长。我们得到：
$$ac = 6 \cdot \frac{abc}{4S} \cdot \frac{S}{p}, \quad 1 = \frac{3b}{2p},$$
$$a + b + c = 3b, \frac{a + c}{2} = b,$$

这是正确的，因为 $a, b, c$ 构成了一个算术过程。

所有这些变换都可以以相反的顺序进行检查，因此，所证明的对应关系是正确的。

例 4. 证明悬浮图形的对角线乘积等于对边乘积之和（托勒密定理）。

解决方案e.假设等式 (图 2) 为真：
$$AC \cdot BM = AM \cdot BC + AB \cdot CM.$$

让我们通过用一些其他元素来表达所有段来减少参数的数量。需要使用任务的所有数据（四重 - vissanny）给我们带来了这个想法

⟦folio 50⟧

在哪里
$$\sin(\alpha + \beta) \cdot \cos \alpha = 2 \sin \alpha \times \cos (\alpha + \beta);$$
$$\left( \alpha + \beta \neq \frac{\pi}{2} + \pi k; \quad \alpha \neq \frac{\pi}{2} + \pi n \right);$$
$$\frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin \beta \right] =$$
$$= 2 \cdot \frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin (-\beta) \right);$$
$$3 \sin \beta = \sin (2\alpha + \beta),$$

根据问题的条件，这是正确的。

这些变换可以以相反的顺序证明（对于参数的所有有效值），因此等式（9）为真。

示例 7. 证明对于 $\alpha$ 的所有允许值，我们有不等式
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| > |\sin \alpha + \cos \alpha|.$$ (11)

解决方案e.假设不等式(11)成立。让我们减少函数的数量：
$$\left| \frac{\sin^2 \alpha + \cos^2 \alpha}{\sin \alpha \cos \alpha} \right| > |\sin \alpha + \cos \alpha|;$$ (12)
$$\frac{1}{|\sin \alpha \cdot \cos \alpha|} > |\sin \alpha + \cos \alpha|.$$ (13)

为了比较这些表达式的大小，建议通过一个函数来表达它们，例如通过正弦：
$$\frac{2}{|\sin 2\alpha|} > \sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)|.$$ (14)

但是$|\sin 2\alpha| \leqslant 1$、$|\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant 1$，因此$\frac{2}{|\sin 2\alpha|} \geqslant 2$和$\sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant \sqrt{2}$，并且不等式（14）对于$\alpha$的所有允许值都成立。

从不等式（14）得出（13），因此得出（12），并且从不等式（12）得出（11），因此不等式（11）对于所有$\alpha \neq \frac{\pi k}{2}$都成立。

上述推理表明可以证明更强的不等式
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| \geqslant \sqrt{2} |\sin \alpha + \cos \alpha|.$$ (50)

例 8. 证明在每个三角形中
$$h_a > \sqrt{p(p-a)},$$ (15)

其中$h_a$是$a$边的高度，$p$是三角形的米。

解决方案e.令不等式(15)成立。让我们减少参数的数量：
$$\frac{\sqrt{p(p-a)(p-b)(p-c)}}{1/2 a} > \sqrt{p(p-a)}.$$

我们使用了公式
$$S_\Delta = \frac{1}{2} h_a \cdot a,$$
$$S_\Delta = \sqrt{p(p-a)(p-b)(p-c)},$$
$$\sqrt{(p-b)(p-c)} > \frac{1}{2} a.$$

不等式两边都是正数——可以平方
$$(p-b)(p-c) > \frac{a^2}{4},$$
$$\frac{a+c-b}{2} \cdot \frac{a+b-c}{2} > \frac{a^2}{4},$$
$$a^2 + ab - ac + ac + bc - c^2 - ab - b^2 + bc > a^2,$$
$$2bc - c^2 - b^2 > 0,$$
$$-(b-c)^2 > 0,$$

这是不正确的。因此，我们关于不等式（15）有效性的假设是错误的。

至此，问题的解算是完成了，或者说我们已经证明了式（15）是不正确的。然而，在证明了公式（15）不正确之后，我们从而证明了公式总是正确的
$$h_a \leqslant \sqrt{p(p-a)}.$$

尝试找出最后一个公式中何时出现相等。这里我们“从头到尾”解决问题的方法变成了“矛盾”的方法。

这种解决几何问题的方法与所描述的方法有一定的相似之处，当需要

⟦folio 51⟧

和其他未知元素（线段、角度等）由字母 $x, y, z, \dots$ 指定，并被视为已知元素。

例9. 在包含120°的种子中，刻有一个正方形。如果圆的半径为 $R$，求正方形的边长。

解决方案。令 $ABCK$ 为正方形，$\cup EF = 120^\circ$，$O$ 为圆心 (图 3)。让我们表示

图 3.

$BC$穿过$2x$并绘制$OP \perp EF$。然后$ON = \sqrt{R^2 - x^2}$，$OM = \frac{1}{2}R$，$MN = 2x$，$OM = ON - MN$。

我们有等式
$$\frac{R}{2} = \sqrt{R^2 - x^2} - 2x$$
解决这个问题，我们得到 $x = \frac{R(\sqrt{19} - 2)}{10}$

答案：$\frac{R(\sqrt{19} - 2)}{5}$。

许多学生不仅在解决问题时犯错误，在提出理论问题时也犯错误。例如，他们是如何证明众所周知的身份的：
$$\log_a \left( \frac{x}{y} \right) = \log_a x - \log_a y$$
（在 $x > 0$ 和 $y > 0$）。

“让我们将$\log_a y$移到左侧并使用之前证明的定理：
$$\log_a \left( \frac{x}{y} \right) + \log_a y = \log_a x$$
$$\log_a \left( \frac{x}{y} \cdot y \right) = \log_a x$$
$$\log_a x = \log_a x.$$

我们得到了正确的等式，这意味着原来的公式已经被证明了。”

显然，这些论点尚未证明该公式。学生们通常会咒骂学校教科书，甚至无法理解，他们说，教科书中的公式以完全相同的方式得到了证明。对于他们来说，教科书中提到的公式等价并没有被注意到。

练习

1. 在底边为$a$、边为$b$的等边三角形中，顶点的角度为$20^\circ$。证明$a^3 + b^3 = 3ab^2$。

2. 证明在凸四边形中，与一侧相邻的角的二等腰线所形成的角等于另外两个角之和的一半。

3. 证明不平等
$$\text{ctg} \frac{\varphi}{2} > 1 + \text{ctg} \varphi$$ $0 < \varphi < \frac{\pi}{2}$。

4. 证明不等式$(x + y)(x + y + 2\cos x) + 2 \geq 2\sin^2 x$。 $x$和$y$取什么值才能实现平等？

5. 在三角形$ABC$中，角$A, B$和$C$构成元素值为2的等比级数。证明$\frac{1}{a} = \frac{1}{b} + \frac{1}{c}$。

6. 证明
$$\frac{1}{\log_2 \pi} + \frac{1}{\log_5 \pi} + \frac{1}{\log_{10} \pi} > 4.$$

7. 证明直平行六面体的最大总表面积等于$\frac{M^2}{24}$，其中$M$是平行六面体的边长之和。

8. 梯形对角线的平方和是否等于底边乘积加上侧边的平方和？

9. 检查以下不等式是否成立：
$$\sin^2 \alpha + \sin^2 \beta \geq \sin \alpha \cdot \sin \beta + \sin \alpha \cdot \sin \beta - 1?$$

“让我们重写要证明的不等式
$$2\sin^2 \alpha + 2\sin^2 \beta - 2\sin \alpha \cdot \sin \beta - 2\sin \alpha - 2\sin \beta + 2 \geq 0,$$
或者
$(\sin \alpha - 1)^2 + (\sin \beta - 1)^2 + (\sin \alpha - \sin \beta)^2 \geq 0,$
这非常痛苦。”

10. 真的是$\sin(\cos \varphi) = \cos(\sin \varphi)?$吗
