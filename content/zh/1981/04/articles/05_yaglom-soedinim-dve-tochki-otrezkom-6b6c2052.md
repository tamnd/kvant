---
id: 1981-4-yaglom-soedinim-dve-tochki-otrezkom-6b6c2052
issue: kvant_1981_4
year: 1981
number: "4"
title: 用线段连接两个点
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 14
page_last: 18
page_labels: 12-16
tag: DRDQ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ef23ac2860db58e900e8be60a31b050666cf236fd820ae42de279e5be7e6e3ef
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/05_yaglom-soedinim-dve-tochki-otrezkom-6b6c2052.md
source_content_sha256: 397e9f2eb69caa7497931f608763f309c556c7c13e885bb864b619b8fb36dc42
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

I·耶洛姆

用线段连接两个点

古希腊人主要将数学理解为几何学。例如，他们使用绘图（图 1）证明了代数等式$(a+b)^2=a^2+2ab+b^2$。例如，今天，数学正迅速变成代数——代数就其与几何的关系而言，正在展开报复。近年来，几何的呈现通常基于一种或另一种微积分（例如，矢量微积分）。本文将讨论其中一个非常简单但出人意料的计算。

点和形状相乘

具有端点 $A$ 和 $B$ 的线段通常用符号 $AB$ (图 2) 表示。该条目提出了意想不到的术语：我们将线段 $AB$ 称为点 $A$ 和 $B$ 的乘积。类似地，图形α和β的乘积αβ是指所有线段$AB$的圆和，其中$A \in \alpha$，$B \in \beta$，即图形α的点与图形β的点的所有可能乘积的圆（图3）。我们确信，这种意想不到的点和数字的乘积与通常的数字乘积是不可能的。

这种点的乘法有什么性质？第一个是显而易见的：

(a) 通勤积分乘法：

$$AB=BA$$

(b) 点关联相乘：

$$(AB)C=A(BC)$$

对于任意点 $A, B$ 和 $C$。

事实上，乘积 $(AB)C$ 是连接线段 $AB$ 的点与点 $C$ (图 4,a) 的所有线段的并集，而乘积 $A(BC)$ 是连接 $A$ 与线段 $BC$ (图 4,b) 的点的线段的并集。因此，$(AB)C=A(BC)=ABC$，其中$ABC$是一个顶点为$A, B, C$的三角形。

在这里，我们可以方便地将数字 α 和 β 的并集称为它们的和；因此，α 和 β 一起写为 α+β。

(c) 点的乘法相对于它们的加法是可分配的：

$$(A+B)C=AC+BC$$

对于任意点 $A, B$ 和 $C$。

这是很清楚的，因为一对点 $A+B$ 和点 $C$ 的乘积是线段 $AC$ 和 $BC$ (图 5) 的并集。

以下乘法点的性质已经不同于我们所学过的乘法的性质：

(d) 点乘法相同：

$$AA=A$$

对于任意点$A$。

事实上，两端合并的线段$AA$就是点$A$。

点乘法的性质 (a) - (c) 延续到任意数字：

(A) 数字的交换乘法：

$$\alpha\beta=\beta\alpha.$$

(B) 数字相乘：

$$(\alpha\beta)\gamma=\alpha(\beta\gamma).$$

数字$(\alpha\beta)\gamma=\alpha(\beta\gamma)$适当地表示为αβγ；它表示所有可能的三角形 $ABC$ 的并集，其中 $A\in \alpha$、$B\in \beta$、$C\in \gamma$。

⟦folio 13⟧

图 1.
图 2.
图 3.
图 4.
图 5.
图 6.
(C) 数字的乘法相对于它们的加法是可分配的：
$(\alpha + \beta)\gamma = \alpha\gamma + \beta\gamma$
(图 6).
然而，数字乘法的幂等性一般来说是没有立足之地的。只能说
(D) 任何图形与其自身的乘积包含该图形：
$\alpha\alpha \supset \alpha$.
图7表明数字$\alpha\alpha$可能与$\alpha$不同。此外，很容易看出对于任何数字$\alpha$
$\alpha^n \subset \alpha^{n+1}$，其中$\alpha^n$照常表示乘积$\underbrace{\alpha\alpha \dots \alpha}_{n\text{ раз}}$。
练习
1. 令$A, B, C$和$D$为任意点（平面或空间）。证明
$(AB)(CD) = (AD)(BC) =$
$= (AC)(BD) = A(BCD) = B(ACD) =$
$= C(ABD) = D(ABC)$.
这个四点的乘积是多少（可以简单地用$ABCD$表示，不带括号）？
2. 证明$(AB)(AC) = ABC$。
3. 数字$a)(A+B)(A+C); 6)(A+B)(C+D);$代表什么？
$b)(A+B+C)D; 7)(A+B+C)(D+E)$?
（在问题 6）-d）中，分别考虑所有点都属于同一平面并且这些点是空间中的任意点的情况。）
4. a) 一个点和一个圆的乘积是多少； 6）点和圆；$
$b) 点和三角形； 7）三角形的点和轮廓； 8）点和方块； e) 两个圆圈； g) 两个三角形； h) 两个正方形； i) 圆形和方形？
5. 如果两条线平行，则两条线的乘积是多少： a) 平行； 6）相交； c) 杂交？

当$\alpha\alpha = \alpha$时
在论证和代数中，$a \cdot a = a$ 的数字扮演着特殊的角色。显然，只有在许多其他方面都很出色的数字 1 和 0 才具有这种性质。

⟦folio 14⟧

在几何中，专门考虑$\alpha$对应$\alpha^2 = \alpha \alpha = \alpha$这样的数字也很有趣。每个这样的图形的特征​​是它属于连接该图形的两个点的任何线段（图8）。如您所知，此类图形称为*凸*。

凸图形的定义也可以给出如下优雅的形式：一组点$\alpha$如果在点乘运算下是封闭的，则称为*凸*，即与任意两个点$A$和$B$一起，图形$\alpha$还包含这些点的乘积$AB$。

很容易想出一个平面图形 $\beta$ ，其中 $\beta^2$ 不是凸的。可以证明，对于任意平面图形$\beta$，图形$\beta^3$都是凸的；它由包含 $\beta$ 的最小凸图表示，称为 $\beta$ 的*凸包*。对于位于三维空间中的图形$\beta$，凸包将为$\beta^4$。

一般来说，对于位于$n$维日氏空间中的任何图形$\beta$，图形$\beta^{n+1}$都是凸的，因此所有图形$\beta^{n+2}, \beta^{n+3}, \dots$都与$\beta^{n+1}$重合。

凸图理论在当今数学中占有重要地位。

练习

6. 证明两个凸图形的乘积是凸的。

7. 如果 $\beta$ 是以下各项的并集，则数字 $\beta^2; \beta^3; \beta^n$ 代表什么： a) 平面上的三个点； b) 空间中的四个点； c) 正五边形的顶点； d) 一个圆和一个不在圆平面内且正交投影到圆心的点。

有乘法就有除法

在数领域，除法被定义为乘法的逆运算：如果$a$，数$q$称为数$a$和$b$的商（表示法：$q=a/b$）

⟦folio 15⟧

有$b$和$q$的乘积。换句话说，条目$q=a/b$和$a=bq$具有相同的含义。类似地，我们将点的除法运算作为其乘法的逆运算：如果$A \neq B$，则用$A/B$表示点集$Q$，其中$A \in BQ$；根据定义，我们还可以输入$A/A=A$。

根据点乘的定义，条件$A \in BQ$意味着$A$属于线段$BQ$（图9）；因此，点$Q \in A/B$位于通过线$A$和$B$上，并且位于$A$与点$B$的另一侧。因此，两点的商$A/B$是一条以$A$为原点的射线，其延续穿过直线$B$。我们也可以说，$A/B$是“环”$A$投射的阴影，被“灯笼”$B$（图10）照亮。

我们将两个图形$a$和$b$的商$\alpha/\beta$定义为所有射线$A/B$的名称，其中$A \in \alpha, B \in \beta$，即图形$a$所有可能的部分点到图形$b$（图11）的点的并集。例如，如果 $A$ 是一个点，那么 $\alpha/A$ 就是由“灯笼”$A$ (图 12) 照亮的图形 $a$ 投射的阴影。

很容易看出（参见图 13-17），对于每三个点$A, B$和$C$，以下关系是有效的（其中前两个基于数字的属性）：

$$(A/B)/C = A/(BC),$$
$$(A+B)/C = (A/C) + (B/C),$$
$$A/(B+C) = (A/B) + (A/C),$$
$$(AB)/C = (A/C)(B/C)$$
$$A/(BC) = (A/B)(A/C).$$

显然，对于任何数字$a$，包含$\alpha/\alpha \supset \alpha$都是有效的。人们普遍感兴趣的是数字$\lambda$，其中$\lambda/\lambda = \lambda$。我们将此类图形称为线性图形（参见 图 18）。

战斗

8. $A)$$(ABC)/D; 6)$$(AB)/(CD); 8)$$A/(BCD)?$代表什么？

9. 数字$\alpha/\alpha; (\alpha/\alpha)/\alpha; [(\alpha/\alpha)/\alpha]/\alpha; ...$代表什么？

如果 $\alpha$ 是不在同一条直线上的三个点的并集？

10. 利用点的乘法和除法运算，写出点$A$和$B$划分直线的区域；

6) 成对连接点$A, B$和$C$的三条直线划分平面；

c) 连接三个给定点$A, B, C$和$D$的四个平面划分空间。

在前。 11-13 采用以下符号： $A$ - 点； $\lambda, \lambda_1, \lambda_2$——直； $\pi, \pi_1, \pi_2$ - 飞机； $\sigma, \sigma_1, \sigma_2$ - 圆圈； $x, x_1, x_2$ - 圆圈； $\tau, \tau_1, \tau_2$ - 三角形。

11. $a)$ $(A/\lambda; 6)$ $\lambda/A; b)$ $A/\pi; \Gamma)$ $A/\sigma; e)$ $\sigma/A; jx)$ $A/x; 3)$ $x/A; i)$ $A/\tau; k)$ $\tau/A; l)$ $\lambda/\pi; m)$ $\pi/\lambda$代表什么？

12. $a)$$\sigma_1/\sigma_2; 6)$$x_1/x_2; b)$$\tau_1/\tau_2; \Gamma)$$\lambda_1/\lambda_2; d)$$\pi_1/\pi_2$代表什么？

在前。 d) 分别考虑$\lambda_1$和$\lambda_2$相交的情况；平行线;杂交。

13. $a)$$\sigma/\sigma; 6)$$x/x; b)$$\tau/\tau; \Gamma)$$\lambda/\lambda; d)$$\pi/\pi$代表什么？

14. 证明对于任意点$A, B, C$，以下关系成立：

a) $A(B/C) \subset (AB)/C; 6)$ $A/(B/C) \subset (AC)/B; b) (A/B)(C/D) \subset (AC)/(BD); g) (A/B)/(C/D) \subset (AD)/(BC).$

（对于任意数字，公平值具有类似的属性。）

15. 证明对于任意数字 $a, b, \gamma$ $(\alpha/\beta)/\gamma \subset (\alpha/\gamma)\cap(\beta/\gamma); 6)$ $(\alpha+\beta)/\gamma = (\alpha/\gamma)+(\beta/\gamma); b) \alpha/(β+\gamma) = (\alpha/\beta)+(\alpha/\gamma); g) (\alpha/\beta)/\gamma = (\alpha/\gamma)(\beta/\gamma); d) \alpha/(β\gamma) = (\alpha/\beta)(\alpha/\gamma).$

17. 证明线性图形必然是凸的。

18. 证明平面上的所有线性图形都可以由点、直线和平面穷举；在空间中，线性图形是点、直线、平面和所有空间。

19. 如果图形$a$和$b$至少有一个公共点，则条件写为$\alpha \approx \beta$（为了比较，请注意，如果$a$和$b$所有点都是公共的，则写为$\alpha = \beta$）。

证明以下优雅的比例规则成立：如果数字$a, b, \gamma, \delta$使得$\alpha/\beta \approx \gamma/\delta$，则$\alpha\delta \approx \beta\gamma$（距离首先是当$a, b, \gamma, \delta$是点时的情况；图18）。还证明$\alpha/\beta \approx \gamma\Leftrightarrow \beta\gamma \approx a$。

点和图形的“非 ενClidean”乘法

本文内容基于美国几何学家沃尔特·彭罗维茨（Walter Penrowitz）最近的研究。彭罗维茨研究的想法（根本不是针对初学者数学家，例如本杂志的读者）是考虑一类广泛的新“几何”，与吸引您的“学校”几何不同。

⟦folio 16⟧

欧几里得度量；这些几何形状可以称为“非ενClidean”几何形状。以下是 Penrowitz 所说的“非 ενClidean 点乘法”的两个例子：

I、坐标平面上A点和B点的乘积AB是由A和B“跨越”（图19）、边与坐标轴平行的矩形；如果通过点 A 和 B 的直线平行于任何坐标轴，则矩形退化为线段，并且根据定义，乘积 AB 与我们之前定义的乘积重合。

二.我们固定图形 P，由从一点 O (图 20) 发出的三条射线形成。这个图形将是我们的“宇宙”：我们将进一步仅考虑属于 P 的点和作为集合 P 的子集的图形。通过点 A ∈ P 和 B ∈ P 的乘积 AB，我们指的是图形 P 内连接 A 和 B 的最短折线。

点积确定后，与之前的字面意思相同，依次确定图形、凸图形、点商、图形商、线性图形的乘积。 图 21 表示例 I 中 A/B 点的商，图 22 表示例 II 中 A/B 的商（A 点和 B 点位置不同）。

事实证明，“彭罗维茨几何”中的凸图理论与一般 ενClidean 几何中的相应理论具有很大的前景。

练习

20. 检查积 AB 和点的商 A/B（例如 I）是否满足文章主要部分和练习中列出的所有属性。在这个“几何图形”中哪些图形是凸的？哪些是线性的？

21. 例子II也一样。

«Kvant»杂志社论集深表遗憾地通知读者，著名苏联数学家、苏联科学院通讯院士阿纳托利·伊拉里奥诺维奇·希尔绍夫的社论集成员于1981年2月28日英年早逝。
