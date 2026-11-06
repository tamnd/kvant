---
id: 1991-7-solovev-kompleksnyie-chisla-33027c74
issue: kvant_1991_7
year: 1991
number: "7"
title: 复数
authors:
  - Соловьёв Ю. П.
rubric: shkola-v-kvante
page_first: 49
page_last: 55
page_labels: 47, 49, 50, 51, 52, 53
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d472d1159a3b17dcab9e4457ae3dd1ba340e66dd6a30730a4b8ec396ff807058
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/14_solovev-kompleksnyie-chisla-33027c74.md
source_content_sha256: 78904b3e41ba58650dfdb72a26edd0bdd52696331fc8a8f11f8693baa9d23161
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

Matematika 9 — 11
复数
物理和数学科学博士
Y·索洛维耶夫

早在古代，数学家在解决用现代语言编写的二次方程问题时，就遇到了需要从负数中求根的情况。在这种情况下，问题被认为是无法解决的。然而，伊利安数学家在十六世纪上半叶发现的三次方程根式的解，导致方程的实根用负数的平方根来表达。这迫使数学家使用新的数字进行运算，并应用实数所遵循的相同运算规则。

考虑提取负数$\sqrt{-a}$的平方根的问题。由于实数的平方总是正数，因此在实数领域中这样的问题是不可能的。我们需要一些新数字：

$$\sqrt{-a} = \sqrt{a} \cdot \sqrt{-1} = \sqrt{a} \cdot i,$$

其中$i = \sqrt{-1}$、$i^2 = -1$是一个新的非实数的指定，称为最小单位。

表格编号

$$a + bi,$$

其中$a$和$b$是实数，称为复数；数$a$称为实部，数$b$称为最小部分。在$a = 0$，复数变成最小数$bi$；通过$b = 0$，我们得到数字$a + 0i$，它被视为实数$a$。

$z = a + bi$和$z = a - bi$形式的复数称为共轭，$a + bi$和$-a - bi$形式的复数称为相反数。复数集合通常用$C$表示。

考虑复数$a + bi$和$c + di$相等的条件当且仅当$a = c$和$b = d$。

根据该定义，当且仅当 $a = 0$ 和 $b = 0$ 时，复数 $a + bi$ 等于 0。事实上，实数0可以表示为复数$0 + 0i$。根据定义，仅当满足 $a = 0$ 和 $b = 0$ 时，等式 $a + bi = 0 + 0i$ 才成立。

请注意，对于复数，对于哪一个被认为大于另一个没有达成一致。

发声
1. 找到 $x$ 和 $y$ ，其中

$$(2x + 3y) + (x - y)i = 2 + (2x + y)i.$$

2. 求复数、相反数和共轭数

a) $2 + i$; 6) $1 + i$.

3. 哪些复数与其共轭物的性质一致？对面的？

⟦folio 49⟧

---
running_head:
folio:
---

$$a + bi = (x + yi)^2 = (x^2 - y^2) + 2xyi,$$
IE。
$$x^2 - y^2 = a, 2xy = b.$$

因此，任务归结为找到该系统的真正解决方案。通过对两个方程进行平方然后相加，我们得到$(x^2 + y^2)^2 = a^2 + b^2; x^2 + y^2 = \sqrt{a^2 + b^2},$（因为$x^2 + y^2 > 0$，只取正根）。现在从等式
$$x^2 + y^2 = \sqrt{a^2 + b^2}, x^2 - y^2 = a$$
我们发现
$$x^2 = \frac{\sqrt{a^2 + b^2} + a}{2}, y^2 = \frac{\sqrt{a^2 + b^2} - a}{2}.$$

对于$x$和$y$，我们各有两个值，这给出了四种组合$(x; y)$，但是，根据条件$xy = b/2$，乘积$xy$的符号必须与数字$b$的符号一致；这仅给出两对 $(x; y)$ 的值，即两个根：

$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} + i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b > 0,$$
$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} - i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b < 0.$$

练习 6. 计算
a) $\sqrt{1 + i}$; 6) $\sqrt{3 + 4i}$;
b) $\sqrt{4 - 3i}$;
d) $\sqrt{\cos \alpha + i \sin \alpha}$ ($0 < \alpha < \pi$);
e) $\sqrt{\cos 2\alpha - i \sin 2\alpha}$。

求解二次方程
众所周知，并不是所有的二次方程都可以用实数求解。可解性的条件是其判别式$D = b^2 - 4ac$非负。在复数中，这种例外消失了。如果$D < 0$，则二次方程的解可通过以下公式找到
$$x_{1,2} = \frac{-b \pm \sqrt{|D|} \cdot i}{2a}.$$

换句话说，无论二次方程的系数 $a, b$ 和 $c$ 是多少
$$ax^2 + bx + c = 0,$$
 它的解由公式找到
$$x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}.$$

另请注意，此公式允许您求解具有复系数 $a, b, c$ 的二次方程。毕竟，我们已经知道任何复数的平方根。

练习
7. 求解二次方程
a) $x^2 + 2x + 2 = 0$;
b) $x^2 + (1 + i)x + i = 0$;
b) $ix^2 - 2x + 1 = 0.$

8. 找到（复）方程的所有根
a) $x^3 = 1$;
b) $x^4 = -1$;
b) $x^4 + x^2 + 1 = 0.$

复数的几何解释

“complex”一词由拉丁语翻译而来，意思是“复合的”、“复杂的”。尽管处理复数并不比处理实数更困难，但直到 19 世纪初，复数仍被认为是非常复杂、黑暗、几乎神秘的对象。坚韧值得更好地利用，重量是“最小”数字的各方和反对者之间的长期斗争。反对者的主要反对意见如下：$a + bi$形式的表达式没有意义，因为$i$不是实数，因此根本不是数字；因此$i$不能乘以实数。

⟦folio 50⟧

---
running_head:
folio:
---

为了给复数理论打下坚实的基础，有必要对它们进行明确的构造，最好是几何构造。如果我们记得实数集与一条“实直线”是不可分离的，那么对一组复数进行几何实现的愿望就不是偶然的，该直线上有一个固定点代表零，并且具有由数字 1 的位置确定的固定比例。

儿童测量员 K. Vesel 于 1799 年首次给出了复数作用的几何表示，1806 年，法国数学家 J. Arganov 独立于他给出了复数作用的几何表示。然而，直到三十年代，即德国数学家 F. Gauss 和英国数学家 W. Hamilton 的工作几个世纪之后，它才得到普遍认可。复数的几何解释的思想是，它们不像实数那样由直线上的点表示，而是由平面上的点表示。

因此，让我们构造一个集合，其元素是平面上的点，并且点的加法和乘法将遵守所有实数运算规则。

让我们在平面中选择一个直接坐标系，横坐标轴为$x$，纵坐标轴为$y$。让我们用 $(a; b)$ 表示横坐标 $a$ 和纵坐标 $b$ 的点。对于点$(a; b)$和$(c; d)$，我们根据规则确定和与积：

$$
(a; b) + (c; d) = (a + c; b + d),
$$

$$
(a; b) \cdot (c; d) = (ac - bd; ad + bc).
$$

直接验证很容易确定点的加法和乘法运算具有交换律和结合律：

$$
(a; b) + (c; d) = (c; d) + (a; b),
$$

$$
((a; b) + (c; d)) + (e; f) = (a; b) + ((c; d) + (e; f)),
$$

$$
(a; b) \cdot (c; d) = (c; d) \cdot (a; b),
$$

$$
((a; b) \cdot (c; d)) \cdot (e; f) =
= (a; b) \cdot ((c; d) \cdot (e; f)).
$$

分布式定律也满足：

$$
((a; b) + (c; d)) \cdot (e; f) =
= (a; b) \cdot (e; f) + (c; d) \cdot (e; f).
$$

点 (1; 0) 作为一个单位，即对于任何点 $(a; b)$

$$
(a; b) \cdot (1; 0) = (1; 0) \cdot (a; b) = (a; b).
$$

最后，对于任何点 $(a; b) \neq (0; 0)$ 也有一个独特的点 $(x; y)$ 使得

$$
(a; b) \cdot (x; y) = (1; 0).
$$

我们来证明最后一个性质。让我们取一些非零点$(a; b)$（这尤其意味着$a^2 + b^2 > 0$）。我们需要找到一个点$(x; y)$使得$(a; b) \cdot (x; y) = (1; 0)$。但

$$
(a; b) \cdot (x; y) = (ax - by; ay + bx).
$$

因此，我们得到一个方程组

$$
ax - by = 1, ay + bx = 0.
$$

求解该方程组的 $x$ 和 $y$，我们发现

$$
x = \frac{ac + bd}{a^2 + b^2}, y = \frac{ad - bc}{a^2 + b^2}.
$$

这已经证明了一切。

这样，我们就把平面上的点变成了一个数值集合，即一个具有加法和乘法运算的集合，并且一般实数的加法和乘法的所有性质都成立。该集合中包含的实数是 $(a; 0)$ 形式的点。事实上，这些点的相加和相乘就是简单的实数相加和相乘：

$$
(a; 0) + (c; 0) = (a + c; 0),
$$

$$
(a; 0) \cdot (c; 0) = (ac; 0).
$$

⟦folio 51⟧

---
running_head:
folio:
---

现在我们取点(0; 1)。让我们看看如果我们对它求平方，即将总和乘以我们自己，会发生什么：
$(0; 1)^2 = (0; 1) \cdot (0; 1) = (-1; 0)$.
因此，$(0, 1)^2$是一个实数——1。这意味着点(0, 1)可以解释为最小单位$i$，从而揭开了它神秘的面纱。最后，任意点$(a; b)$都可以表示为
$(a; b) = (a; 0) + (0; b) = (a; 0) + (b; 0) \cdot (0; 1)$.
如果$(a; 0)$和$(b; 0)$用$a$和$b$表示为素数，$(0, 1)$用$i$表示为素数，那么我们得到
$(a; b) = a + bi$.
也就是说，现在公式表达式$a + bi$已经有了坚实的基础——它只是平面上坐标为$(a; b)$的点，经过上述加法（1）和乘法（2）运算。
除了纯粹的理论价值之外，复数的几何实现还具有重要的实际意义——在它的帮助下，复数可以用所谓的三角形式表示，这在众多应用中都很方便。
练习
9. 将复数 $2 + i, 1 + i, -1 - i, -3 - 2i$ 绘制为平面上的点。
10. 证明复数$z_1$和$z_2$的和$z_1 + z_2$由平行四边形的第四个顶点表示，平行四边形的两个相邻边是连接点$z_1$和$z_2$与点$O$的线段。
11. 点 $z_1, z_2, z_3$ 是平面上三角形的顶点。写下代表该三角形重心的数字。

复数的三角形式

让我们考虑直线平面上的坐标系$xOy$。让点$P$代表复数$z = a + bi$（图1）。
让我们用 $r$ 表示从点 $P$ 到坐标原点的距离 $OP$，用 $\varphi$ 表示射线 $OP$ 与轴 $Ox$ 的正方向形成的角度（参见 图 1），并且逆时针不存在 $(0 < \varphi < 2\pi)$。 （在 图 1 处，针对点 $P$ 位置的不同情况显示了角度 $\varphi$。）
根据三角函数的定义可以得出：
$a = r \cos \varphi, b = r \sin \varphi$,

图 1.

⟦folio 52⟧

---
running_head:
folio:
---

$$z = r(\cos \varphi + i \sin \varphi).$$

这是复数的三角形式。量$OP = r$称为复数$z$的模，用$|z|$表示，角度$\varphi$的大小是数$z$的主要参数，用arg$z$表示。

由于 $OP$ 是正三角形 $OAP$ 的斜边，则
$$|z| = r = \sqrt{a^2 + b^2},$$
$$\arg z = \left\{ \begin{array}{l} \arccos \frac{a}{\sqrt{a^2 + b^2}} \text{ при } b \geqslant 0; \\ 2\pi - \arccos \frac{2}{\sqrt{a^2 + b^2}} \text{ при } b < 0. \end{array} \right.$$

从这些公式可以看出，当且仅当 $z = 0$ 时，$|z|$ 是唯一确定的并且等于零。

$z = 0$ 的主要参数未定义。对于 $z \neq 0$，每个与 arg $z$ 相差 $2\pi$ 倍数项的角度称为 $z$ 的参数。

例如，由于 arg $i = \frac{\pi}{2}$，因此数字 $i$ 的所有参数均采用 $\frac{\pi}{2} + 2k\pi$ 形式。同样，arg 是 $(-1) = \pi$，所有其他参数都是数字 $\pi(2k + 1)$。

练习。
12. 查找 $|z|$ 和 arg $z$ if
a) $z = -2$; 6) $z = 1 + i$; b) $z = -1 - i$; c) $z = -i$; d) $z = 1 - i\sqrt{3}$; e) $z = -3 - 4i$.

13. 写出数字的三角形式
a) 1; 6) -1; b) 12 + 5i; c) 12 - 5i; d) -12 - 5i; e) $\sin \alpha + i \cos \alpha$ ($0 < \alpha < \pi$).

14. 证明点$z_1$和$z_2$之间的距离是$|z_1 - z_2|$。用它来在平面上绘制点
a) $|z - i| = 1$; 6) $|z - 1| = |z + 1|$; b) $|z - i| = |iz - 1|$; c) $1 \leqslant |z - i| \leqslant 2$.

15. 画出平面上的点
a) arg $iz = \pi/4$; b) arg $(iz - 1) = \pi/3$.

所有以三角形式给出的复数的代数运算都遵循与以代数形式给出的复数相同的规则。当复数以代数形式给出时，复数的加法和减法以及三角函数形式的乘法和除法更加容易和方便。

定理 1. 当任意有限数量的复数相乘时，它们的 modi 会发生转换，并且参数会相加。

证明。让我们将自己限制在两个因素上：一般情况可以通过归纳法很容易地得到。所以我们必须证明
$$(r_1(\cos \varphi_1 + i \sin \varphi_1)) \cdot (r_2(\cos \varphi_2 + i \sin \varphi_2)) = (r_1 r_2)(\cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2)).$$

但
$$(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 + i \sin \varphi_2) = (\cos \varphi_1 \cos \varphi_2 - \sin \varphi_1 \sin \varphi_2) + i(\cos \varphi_1 \sin \varphi_2 + \sin \varphi_1 \cos \varphi_2) = \cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2),$$
由此产生非主席平等 (3)。由于 $r_1 \geqslant 0, r_2 \geqslant 0$ 蕴含 $r_1 r_2 \geqslant 0$，因此 $r_1 r_2$ 是模数，$\varphi_1 + \varphi_2$ 是两个给定数字的乘积的参数。定理已被证明。

根据该定理，复数 $z$ 与复数 $a$ 的乘积是从点 $z$ 获得的，如下所示：您需要将射线 $Oz$ 逆时针旋转角度 $\alpha = \arg a$，然后将所得射线置于距 $O$ 距离 $|a| \cdot |z|$ (图) 的点上2）。换句话说，以万能点$z$到点$az$的平面变换为

⟦folio 53⟧

---
running_head:
folio:
---

旋转角度$\alpha$与系数$|a|$和中心$O$准备的乘积。

练习 16.证明以下等式

a) $|z|^2 = zz'$; 6) $\frac{z_1}{z_2} = \frac{z_1\bar{z}_2}{|z_2|^2}$;

b) $|z_1 + z_2| \leqslant |z_1| + |z_2|$（找出$z_1$和$z_2$相等）；

d) $|z_1 + z_2|^2 + |z_1 - z_2|^2 = 2(|z_1|^2 + |z_2|^2)$。

这又有什么几何意义呢？

定理 2. 当除复数时，它们的模被除，参数被减去。

更详细地说，

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)} = \frac{r_1}{r_2}(\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2))$$.

证明。转换分数

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)},$$

将其分子和分母乘以 $\cos \varphi_2 - i \sin \varphi_2$。结果我们得到

$$\frac{r_1}{r_2} \cdot \frac{(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 - i \sin \varphi_2)}{(\cos \varphi_2 + i \sin \varphi_2)(\cos \varphi_2 - i \sin \varphi_2)}$$.

由于$i^2 = -1$，第二个分数的分母是$\cos^2 \varphi_2 + \sin^2 \varphi_2 = 1$。分子可以这样写：

$$(\cos \varphi_1 + i \sin \varphi_1)(\cos (-\varphi_2) + i \sin (-\varphi_2))$$.

应用乘法规则，我们得到

$$\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2)$$,

Q.E.D.

当因素一致时，定理 1 得出所谓的 Myabra 公式

$$(r_1(\cos \varphi + i \sin \varphi))^n = r^n(\cos n\varphi + i \sin n\varphi).$$

定理 3. 设 $z$ 为复数，$n$ 为自然数。在复数集合中，$z = 0$ 的表达式 $\sqrt[n]{z}$ 具有单个值 - 0，而对于 $z \neq 0$ - 它具有不同的值。如果

$$z = r(\cos \varphi + i \sin \varphi),$$

然后通过公式找到这些值

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2\pi k}{n} + i \sin \frac{\varphi + 2\pi k}{n} \right),$$

$k = 0, 1, \dots, n - 1$.

证明。从 $0^n = 0$ 和$z^n = 0$ 可以得出$z = 0$。

现在就让它

$$z = r(\cos \varphi + i \sin \varphi) \neq 0.$$

用$\rho$和$\alpha$表示根对应的模型和参数，我们有

$$\sqrt[n]{r(\cos \varphi + i \sin \varphi)} = \rho(\cos \alpha + i \sin \alpha).$$

因此，根据迈布拉公式

$$r(\cos \varphi + i \sin \varphi) = \rho^n(\cos n\alpha + i \sin n\alpha).$$

因此，他们必须遵守

$$\rho^n = r, n\alpha = \varphi + 2k\pi,$$

在哪里

$$\rho = \sqrt[n]{r}, \alpha = \frac{\varphi + 2k\pi}{n},$$

IE。

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2k\pi}{n} + i \sin \frac{\varphi + 2k\pi}{n} \right).$$

我们会得到多少种不同的值？很容易看出，如果我们将值$k = 0, 1, 2, \dots, n - 1$代入最后一个公式，则根的所有结果值都会不同，因为它们的参数会不同。对于 $k = n$ 我们得到

$$\frac{\varphi + 2\pi n}{n} = \frac{\varphi}{n} + 2\pi,$$

并且根将相等

$$\sqrt[n]{r} \left( \cos \left( \frac{\varphi}{n} + 2\pi \right) + i \sin \left( \frac{\varphi}{n} + 2\pi \right) \right) =$$

$$\sqrt[n]{r} \left( \cos \frac{\varphi}{n} + \sin \frac{\varphi}{n} \right),$$
