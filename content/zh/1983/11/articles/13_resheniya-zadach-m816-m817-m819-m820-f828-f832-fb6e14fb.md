---
id: 1983-11-resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb
issue: kvant_1983_11
year: 1983
number: "11"
title: 问题M816、M817、M819、M820的解决方案； F828—F832
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 45
page_labels: 39, 40, 43
tag: IIDV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b04e8c473499660fddc889d5d04dd4ad7ff185e1b65120874378478eaade4408
prompt_sha256: draft-1
translated_from: content/ru/1983/11/articles/13_resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb.md
source_content_sha256: 6502541d952a232a58231441eb6e423fea6100b4a3ac1d8110ff7a1e83155781
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

问题解决方案
M816, M817, M819, M820*); F828—F832

M816。自然数a和b是通过重新排列数字而获得的。证明
a) 数字2a和2b的各位数字之和相等；
b) 数字a/2和b/2的各位数字之和相等（如果a和b是偶数）；
c) 数字5a和5b的数字之和相等。

首先我们证明一个辅助命题。
令$S(x)$为自然数$x$的各位数字之和，$N(x)$为大于4的自然数的位数。则
$$S(2x) = 2S(x) - 9N(x).$$

假设我们将数字 $x$ 添加到一列中，从最低数字开始。当且仅当数字 $x$ 的第 $k$ 位数包含数字 5、6、7、8 或 9 之一时，才会发生总和中第 $(k+1)$ 位的从一位到下一位的转移（在页边距的示例中，这种情况发生在从数字末尾算起的第 2 位、第 3 位和第 5 位），即转移次数为 $N(x)$。每传输 10，即包含在总和$S(x) + S(x)$中，就会出现一个单位，该单位包含在总和$S(2x)$中，即$S(2x)$与$2S(x)$相比减少了9。从这里我们得到（*）。

现在很容易证明问题​​的陈述。
a) 一起代入(*) $x$ 交替 $a$ 和 $b$ 并考虑以下等式 $S(a) = S(b)$ 和 $N(a) = N(b)$，我们得到了 $S(2a) = S(2b)$.
b) 请注意，当且仅当数字 $2x$ 的数字 $(i+1)$ 为奇数时，数字 $x$ 的数字 $i$ 大于 4。因此，$N(x)$等于$2x$中的奇数位数。因此，对于由相同数字组成的数字 $a$ 和 $b$，$N(a/2) = N(b/2)$ 并凭借 (*)
$$S\left(\frac{a}{2}\right) = \frac{1}{2}\left(S(a) + 9N\left(\frac{a}{2}\right)\right) = \frac{1}{2}\left(S(b) + 9N\left(\frac{b}{2}\right)\right) = S\left(\frac{b}{2}\right).$$
c) 显然，数字10a和10b满足第6)点的条件，因此
$$S(5a) = S\left(\frac{10a}{2}\right) = S\left(\frac{10b}{2}\right) = S(5b).$$
A·D·李西茨基

M817。点 $K$ 位于三角形 $ABC$ 的边 $BC$ 上。证明对应关系 $|AK|^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC|$ 当且仅当 $|AB| = |AC|$ 或 $BAK = CAK$ 成立。

图 1.
$$|AK|^2 = q|AB|^2 + p|AC|^2 - |BK| \cdot |KC|$$
其中$p = |BK| : |BC|$，$q = |CK| : |BC|$。

第一个解决方案（图1）。设 $p = |BK| : |BC|$，$q = 1 - p = |CK| : |BC|$，则
$$\overrightarrow{AK} = \overrightarrow{AB} + \overrightarrow{BK} = \overrightarrow{AB} + p\overrightarrow{BC} = \overrightarrow{AB} + p(\overrightarrow{AC} - \overrightarrow{AB}) = q\overrightarrow{AB} + p\overrightarrow{AC}.$$
(*)

在$|AK|^2 = (q\overrightarrow{AB} + p\overrightarrow{AC})^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC| = |AB| \cdot |AC| - pq(\overrightarrow{AC} - \overrightarrow{AB})^2$ 的条件下。

展开括号并考虑$p + q = 1$，我们得到：
$$q|AB|^2 + p|AC|^2 - |AB| \cdot |AC| = 0.$$

因此，三角形边长比$\lambda = |AB| : |AC|$满足二次方程$q\lambda^2 - \lambda + p = 0$，即$\lambda = 1$或$\lambda = p/q$。在第一种情况下为$|AB| = |AC|$，在第二种情况下为$|AB| : |AC| = p/q = |BK| : |KC|$，根据众所周知的定理***），可以得出$AK$是bisserris或$BAK = CAK$。

使用等式（*），很容易导出线段$AK$长度的通用公式，称为斯图尔特公式。它在页边给出。

*) 问题M818将在以下数字«Kvant»之一中得到解决。
***) 例如，参见 S. R. Sefi Bekov“比塞里斯定理的四个证明”（«Kvant»，1983 年，第 8 期）。

⟦folio 40⟧

第二个解决方案。让我们在线段 BC 上取一点 L，使得 $\widehat{CAL} = \widehat{KAB}$ (图 2)。让我们证明$|AL| = |AK|$。由此可知，要么 L 点与 K 点重合，即 AK 是角 A 的二等角，要么 $\Delta ALK$ 是等边，然后由三角形外角定理

$$\widehat{ABC} = \widehat{AKC} - \widehat{BAK} = \widehat{ALB} - \widehat{LAC} = \widehat{ACB},$$

即三角形ABC是等边三角形。

让我们用 D 表示直线 AK 和三角形 ABC 的外接圆的交点。由于$ACB = ADB$，三角形ACL与三角形ADB相似，因此$|AL| \cdot |AD| = |AB| \cdot |AC|$。三角形ACK和BDK也相似($\widehat{ACB} = \widehat{ADB}, \widehat{AKC} = \widehat{BKD}$)，所以$|BK| \cdot |KC| = |AK| \cdot |KD|$。因此，条件中给出的等式等价于以下

$$|AK|^2 = |AL| \cdot |AD| - |AK| \cdot |KD|$$

或者

$$|AK|(|AK| + |KD|) = |AL| \cdot |AD|.$$

因此，$|AK| = |AL|$。

A. L. 图姆、N. B. 瓦西里耶夫

**M819。施万布拉尼亚有 n 个城市，每两个城市有一条道路连接。 （道路仅在城市中交汇，所有交叉路口都限制在不同的拐角处。）邪恶巫师打算在每条道路上建立单向交通，这样，一旦离开任何城市，就不再可能返回该城市。证明 a) 巫师可以做到这一点；
b) 在这种情况下，将会有一个城市你可以到达所有其他城市，并且会有一个城市你不能离开；
c) 有 $n! = 1 \times 2 \times \dots \times n$ 种方法可以实现此向导的意图。**

a) 向导可以将 Schwambrania 的所有城市编号为 1 到 n，并在每条道路上设置从编号较小的城市到编号较大的城市的移动。通过这样做，他将达到他的目的，因为沿着任何有这种限制的路线移动时遇到的城市数量总是会被返回。

b) 从任意城市出发，我们将沿着施瓦姆布拉尼亚的道路行驶，遵守该向导的规则。只要这是可能的，就让我们惊叹吧。我们的路线上找不到任何城市，而且由于城市数量有限，我们迟早要停下来。但这意味着我们最终到达了Z市，我们无法离开。

现在让我们反转所有道路上的移动方向。显然，根据新规定，我们将再次无法访问同一座城市。因此，如上所述，根据新的（！）规则，有一个城市A您不能离开。因此，最初在连接 A 和任意其他城市 B 的道路上，建立了从 A 到 B 的交通，即从 A 可以到达任意城市（只经过一条道路）。

请注意，您可以从除 Z 之外的任何城市出发（例如，前往 Z），也可以前往除 A 之外的任何城市。

c) 让我们对城市数量n进行归纳。当 n = 1 时，陈述 c) 是显而易见的。让我们在 n 个城市证明它，假设它对 n - 1 个城市有效。根据第6点），对于任何满足该向导条件的交通规则，只有一个且唯一一个无法离开的城市Z。它可以是n个城市中的任何一个。

在所有通往城市Z的道路上。因此，连接另外两个城市的路线不再经过Z，只需在剩余的n-1个城市之间的道路上设置方向，使得沿这些方向行驶时不可能到达其中任何一个。通过归纳假设，这可以完成 (n - 1)！方式。因此，总的路数是n·(n - 1)！ = n!.

另一种解决方案基于以下事实：存在一条最长（就道路数量而言）的路线

⟦folio 43⟧

光栅表面上方的蒸气仅包含水分子。通用值常数为 $R = 8,3$ J/(mol K)。

我们根据气态方程求出温度 $T = 293$ K 时蒸汽的密度 $\rho_{\pi}$：

$$\rho_{\pi} = p_{\text{mac}} \frac{\mu}{RT}.$$

因此，

$$h = \frac{0,05c_2RT}{\mu g} (2 \frac{h_0}{h} - 1).$$

代入条件中给出的数值数据，我们发现

$$h \approx 16,4 \text{ см.}$$

有趣的是，从所考虑的问题可以看出，如果引擎盖下有两个相同的容器，其中装有不同浓度的溶液，那么浓度较低的溶液将会发生蒸发。反之，水蒸气会凝结成浓度较高的溶液。因此，浓度将趋于均衡。这种物理现象与糖、盐等在潮湿空气中的润湿有关。

A.I.布兹丁

F831。将不带电的导电薄壁球壳置于均匀电场中。当场方向为$E_0$时，壳破裂。两倍半径且壁厚相同的壳在什么最小场方向上会破裂？

◆ 导电外壳置于电场中会产生感应电荷。这些电荷的表面密度与场$E$的方向成正比。当壳的尺寸改变 $n$ 倍，场的方向改变 $k$ 倍时，作用在半个球体上的力（在其上感应出相反符号的电荷）改变 $k^2n^2$ 倍。

由于壁厚保持恒定，因此壳体每单位长度的力应该相同。如果在第一种情况下，不连续性与场方向 $k$ 倍成比例，与场方向 $n$ 倍成比例，并且与场方向 $k$ 倍成比例，则不连续性与条件 $f = (k^2n^2/n)f_0$ 成比例。由条件$f = f_0$得出：

$$\frac{k^2n^2}{n} = 1 \Rightarrow k = \frac{1}{\sqrt{n}}.$$

当壳半径加倍时，不连续性与场成正比

$$E = E_0 / \sqrt{2}.$$

S·K·斯特罗科夫

F832*。 a面的方形不变形超导框架水平放置，处于低级磁场中，其感应强度在空间中按规律变化

$$B_x = -kx,$$

$$B_y = 0,$$

$$B_z = kz + B_0.$$

框架质量$m$，电感$L$。初始时刻，框架中心与坐标原点重合，边平行于$X$和$Y$轴。框架已失去光泽。 $t$时间后它会如何移动以及最终会到达哪里？

产生受超导电路限制的区域的磁通量是恒定的。事实上，$\Delta \Phi / \Delta t = \delta_i$，但$\delta_i = iR = 0$（自$R = 0$），因此$\Phi = B_0 a^2 + kz^2 + Li$。

由于在初始时刻$(z = 0, i = 0)$$\Phi = B_0 a^2$，在任何其他时刻，点$i$的值将由以下关系确定

$$Li = -kz^2 \Rightarrow i = -\frac{kz^2}{L}.$$

磁场作用在具有电流 $i$ 的框架上的合力等于作用在框架平行于轴 $Y$ 的那些侧面上的力的总和，
