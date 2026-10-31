---
id: 1974-1-gerver-syurprizyi-e1159ec3
issue: kvant_1974_1
year: 1974
number: "1"
title: 惊喜
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 15
page_last: 23
page_labels: 13-21
tag: 7T9S
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2867020a801e3757554a70fde90b1fe54745a18ea138e76947c8abc84194b07b
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/06_gerver-syurprizyi-e1159ec3.md
source_content_sha256: 619229a4fbdc009ce5b0e0e569e6b5fe8a3aed8a8895f4752cf3416729116248
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

关于名字的几句话。
首先，我们将分析 Kvant Problem Book 中的问题 M195。会发现它与几何圆的一种经典构造密切相关。然后其他意想不到的联系和事实就会出现。
最重要的是抱歉...但是，嘘！不然的话，又会是怎样的遗憾呢？

§1. 三个四边形问题
M195。丹$\Delta ABC$。有多少个点 $D$ 使得四边形 ADBC、ABDC 和 ABCD 的周长相同*)？

解决方案。让我们构建三个圆（$\alpha$、$\beta$ 和 $\gamma$），其中心为 $A$、$B$ 和 $C$，它们在外部成对地相互接触 (图 1)。

*) 仅考虑位于平面 $\Delta ABC$ 中的点 $D$。

这些圆的半径 $a, b$ 和 $c$ 由方程组确定
$$a + b = AB, a + c = AC, b + c = BC.$$
因此，
$$a = p - BC, b = p - AC, c = p - AB,$$
其中$p$是半周长$\Delta ABC$。

令$D$为圆$\delta$的圆心，其外部接触圆$\alpha$、$\beta$和$\gamma$。半径$\delta$用$d$表示。

我们假设已知圆$\delta$存在。这样一个圆的构造就是阿波罗尼乌斯任务*）的意义内容，由佩尔加的阿波罗于公元前3世纪解决。 e.

从 图 1 可以立即看出，三个四边形 ADBC、ABDC 和 ABCD 中的每一个都有一个周长 $2(p+d)=2(a+b+c+d)$。因此，虽然存在一个Izsky点$D$。

这样的点可以有多个吗？继续解决这个问题，首先我们要确保如果参数 ADBC、ABDC 和 ABCD 相等，则点 $D$ 位于圆 $\alpha$、$\beta$ 和 $\gamma$ 之外，从而使它们相等。让我们输入$AD=x, BD=y, CD=z$。那么所考虑的四边形的周长相等将写成如下：
$$2p - AB + x + y = 2p - AC + x + z = 2p - BC + y + z.$$ (2)

从数字$p+x+y+z$逐项减去等式(2)，我们得到
$$z - (p - AB) = y - (p - AC) = x - (p - BC).$$

*) 我已经在 Savin A.P. 的文章 Inversion and the Apollonius Problem 中讨论过这个问题。 «Kvant»，1971 年，第 8 期。

⟦folio 14⟧

利用公式(1)，我们发现
$$z-c=y-b=x-a.$$

根据(3)，数$x-a, y-b$和$z-c$具有相同的符号。此外，如果点 $D$ 位于 $\alpha$ 外部，则$x-a>0$；如果 $D$ 位于$\alpha$ 内部或之上，则$x-a\leq 0$；符号$y-b$和$z-c$具有相似的含义。由于没有点立即属于以圆 $\alpha$、$\beta$ 和 $\gamma$ 为界的所有圆，因此如下
$$x-a=y-b=z-c\leq 0$$
将被排除在外。方法，
$$x-a=y-b=z-c>0,$$
$D$位于$\alpha$、$\beta$和$\gamma$之外并且与它们相等。

对此进行操作，我们将证明唯一的点$D$。

令（为了定义）$\alpha$ 为圆 $\alpha$、$\beta$ 和 $\gamma$ 中最小的一个：
$$a\leq b, a\leq c.$$ 使用半径 $b-a$ 和 $c-a$，我们可以描述圆心 $B$ 和 $C$ 的圆 $\beta'$ 和 $\gamma'$。位于$\alpha$、$\beta$和$\gamma$之外并且与它们相等的点$D$也等于点$A$以及圆$\beta'$和$\gamma'$（图2）。让我们再构造三个圆（$\alpha''$、$\beta''$ 和 $\gamma''$），其圆心为 $A$、$B$ 和 $C$，半径为 $AD$、$BD$ 和 $CD$。令$T$为位于$\alpha''$内部或$\alpha''$上且与$D$不同的任意点。那么 (图 2) $T$ 要么位于 $\beta''$ 之外，要么位于 $\gamma''$ 之外，或者位于这两个圆之外。因此，$T$ 距离$A$ 的距离比距离$\beta'$ 或$\gamma'$ 圆之一的距离更近。

最后的推理表明，两个不同的点$D_1$和$D_2$不能与$A$、$\beta'$和$\gamma'$等距：假设相反（空的$D_1$和$D_2$是这样的点，以及$AD_1\geq AD_2$）并将$D_1$表示为$D$、$a$$D_2$到$T$，我们立即反对。

唯一的点$D$已被证明。

§2. 对偶问题

在第 1 节中，我发现了三个四边形问题和阿波罗问题之间的技术联系。后者的表述（“构造一个与三个给定圆相切的圆”）并没有表明相切应该是外切还是内切。在§ 1中，圆$\delta$外部接触$\alpha$、$\beta$和$\gamma$。让我们用$\epsilon$表示所有三个圆$\alpha$、$\beta$和$\gamma$从内部接触的圆；我们称其中心为 $E$ (图 3)。

他问道：找到$E$点不是可以解决某些问题吗，类似于三个四边形的问题？ （当然，在继续阅读之前，请尝试自己提出这样的问题。）

让我们输入$AE=x, BE=y, CE=z$，并用$e$表示圆$\epsilon$的半径。然后(图3)$x+a=y+b=z+c=e$。因此$x+y+a+b=2e$，即$x+y+AB=2e$。还确定$x+z+AC=y+z+BC=2e$。数量 $x+y+AB, x+z+AC$ 和 $y+z+BC$ 是三角形 $AEB, AEC$ 的周长

图 2.

图 3

⟦folio 15⟧

和重量。由此可见，圆e的圆心$E$就是“三个周长相等的三角形”问题的解，与原来的四边形问题类似。

新问题的表述要点：

“丹$\Delta ABC$。有多少个格言$E$使得三角形$AEB, AEC$和$BEC$的周长相同*）？>

上面我们确定至少存在一个这样的点$E$。

乌帕瓦尼亚
1. 证明不存在其他这样的点。
2. 证明上述命题的逆命题：设点$E$使得三角形$AEB, AEC$和$BEC$的周长等于$2e$，则$\alpha$、$\beta$和$\gamma$从内部与半径为$e$的圆相切$E$。

在三个四边形和三个三角形的问题中，我们不仅证明了点$D$和$E$的存在唯一性，而且还找到了周长公式：$2(p+d)=2(a+b+c+d)$和$2e$。他问：知道边长$\Delta ABC$，是否可以计算这些周长？半径 $a, b$ 和 $c$ 使用简单的公式 (1) 计算。 $d$和$e$是用$a, b$和$c$表示的吗？

第 3 节给出了这个问题的肯定答案。

§ 3. Frederick Soddy 公式

我们已经注意到，阿波罗尼乌斯的问题在公元前 3 世纪就得到了解决。看来这些天她已经容不下任何新鲜的、意想不到的事情了。然而，最近，获得了一个漂亮的公式，显示了阿波罗尼乌斯问题中圆的尺寸如何相互对应。

当您发现这个公式不是由专业人士创建时，它会让打字变得更糟。

*) 仅考虑位于平面 $\Delta ABC$ 上的点 $E$。

数学家、化学家——弗雷德里克·索迪。

让我们用 $k, l, m$ 和 $n$ 表示第 1 段中圆 $\alpha, \beta, \gamma$ 和 $\delta$ 的半径的倒数：

$k=1/a, l=1/b, m=1/c, n=1/d$.

然后

$2(k^2+l^2+m^2+n^2)=(k+l+m+n)^2$.

这种优雅的关系就是索迪的公式。

它可以被视为 $n$ 的二次方程（数字 $k, l$ 和 $m$ 被认为是已知的）。解这个方程，我们得到

$n_{1,2}=k+l+m\pm 2\sqrt{kl+lm+mk}$.

正根$n_1$当然是$1/d$。 $n_2$是什么？

结果是 $n_2=-1/e$，其中 $e$ 是第 2 段中的圆的半径。

加号和减号的含义是什么：为什么$1/d$带有降号，而$1/e$带有减号？

半径的倒数有一个特殊的名字：“曲率”。半径越大，圆的“曲线”越平滑——其曲率越小。

直线（圆的极限情况 - “无限半径的圆”）的曲率为零。使用符号来区分“凸”曲率和“凹”曲率是很自然的。但什么是凸圆和凹圆呢？

当然，所有圈子都是“相同的”。但当它在圆外时，那么自然会认为它是凸的，而如果它在同一个圆内，那么它就显得凹了。因此，“从圆$\alpha, \beta$和$\gamma$的角度来看”，圆和认为“不同”是合理的：第一个是凸的，第二个是凹的。

我们将在第 6 节中介绍索迪公式的推导。

§ 4. 主要研究

我们已经遇到了几个挑战：在第 1 节中，周长相等的四边形问题突然简化为阿波罗尼乌斯问题的特殊情况，在第 2 节中，有必要显示作用顺序 - 我们首先解决并制定了周长相等的三角形问题，在第 3 节中，我们将给出形式 -

⟦folio 16⟧

姆鲁，现代化学家修饰了最古老的几何问题之一。

但现在主要的争议将被提出。

在我们的证明中，我们使用了以下“明显的”几何事实：

I. 让三个圆$\alpha$、$\beta$、$\gamma$成对地从外部接触。那么恰好有一个圆$\delta$在外部接触$\alpha$、$\beta$和$\gamma$，并且恰好有一个圆$\varepsilon$在内部接触$\alpha$、$\beta$和$\gamma$。

二.让三个圆$\alpha''$、$\beta''$和$\gamma''$穿过一个点$D$。那么位于 $\alpha''$ 内部的任何点 $T$ 要么位于 $\beta''$ 外部，要么位于 $\gamma''$ 外部（或位于这两个圆之外）。

这两个事实都是……不正确的。 （Posny 和解决方案 ���题 M195 也是不正确的。）

§ 5. 大修

图 4 显示了圆 $\alpha$、$\beta$ 和 $\gamma$，其中有两个圆（$\delta_1$ 和 $\delta_2$）与 $\alpha$、$\beta$ 和 $\gamma$ 外部接触，并且没有圆 $\varepsilon$ 与$\alpha$、$\beta$ 和 $\gamma$ 内部触摸。

图 5 定义“事实” II。

当然，基于“事实”一、二的结论也是错误的——所有建立在不稳固基础上的数据都会崩溃！

幸运的是，破坏并没有那么灾难性。

定理。让圆$\alpha$、$\beta$和$\gamma$成对地从外部接触。那么三种（也只有三种）情况是可能的：

I. 恰好有一个圆$\delta$与$\alpha$、$\beta$、$\gamma$外部接触，并且恰好有一个圆$\varepsilon$与$\alpha$、$\beta$、$\gamma$内部接触。

二. $\alpha$、$\beta$ 和 $\gamma$ 有一条公切线（并沿着其一条线），而恰好有一个圆 $\delta$ 与 $\alpha$、$\beta$ 和 $\gamma$ 外部接触，并且没有一个圆 $\alpha$、$\beta$ 和 $\gamma$ 不接触从里面。

三．恰好有两个圆$\delta_1$和$\delta_2$，每个圆都在外部接触$\alpha$，$\beta$和$\gamma$，并且不存在$\alpha$，$\beta$和$\gamma$在内部接触的圆。

关于反转的几句话。

为了证明这个定理，我们将使用反演方法*)。

让我们回顾一下反演的定义和一些性质。

关于极限。令 $Q$ 为以 $O$ 为圆心，半径为 $R$ 的圆，位于平面 $P$ 内。相对于圆$Q$的反转称为平面$P$的以下变换：$M$平面的每个点

*) Savin A.P.，反演和阿波罗问题。 «Kvant»，1971 年，第 8 期。

图 4.

图 5.

⟦folio 17⟧

图 6.

$\Pi$，位于距$O$正距离$r$处，到达点$M'$，位于射线$OM$上，距$O$距离$r'$，使得$rr' = R^2$； $O$称为反演中心，$R^2$为反演系数。

性质 1. 若$M$属于$Q$，则$M' = M$；如果$M$位于$Q$内部并且与$O$不同，则$M'$位于$Q$外部；如果$M$位于$Q$之外，则$M'$位于$Q$之内。

2. 直线和圆在反转过程中变换为直线和圆，并且：

a) 位于通过 $O$ 的直线上的点去往同一条直线上的点；

b) 不经过$O$的直线进入经过$O$的圆；

b) 经过$O$的圆进入不经过$O$的直线；

d) 不经过$O$的圆进入不经过$O$的圆；在这种情况下，$O$要么位于这两个圆的外部，要么位于这两个圆的内部。

3. 如果两个圆（或一条线和一个圆）在$M$而非$O$处相接触，则它们的图像$^*$）也会在$M'$点处相接触；如果切点与$O$重合，则这些圆（或直线和圆）变成平行直线。

*) 即反转后变成的样子。

图 7.

对于那些第一次了解反演的人，我们建议要么自己证明列出的性质，要么阅读 A.P. Savin 的上述文章。

作为帮助您了解您对反演方法了解程度的对照，我们建议您在以下问题的“解决方案”中找出错误。

让圆 $\alpha$ 和 $\beta$ 在点 $O$ (图 6) 处外部接触。让我们用 $\Gamma$ 表示点的几何位置。当以反转中心$O$反转时，圆$\alpha$和$\beta$将变成平行线$\alpha'$和$\beta'$（图6）。圆圈$\gamma$接触$\alpha$和$\beta$将变成圆圈$\gamma'$接触$\alpha'$和$\beta'$。 图 6 上的虚线$\Gamma'$ 是圆$\gamma'$ 圆心点的轨迹。所以，曲线$\Gamma$在反演过程中变成了一条直线。这意味着 $\Gamma$ 要么是圆，要么是直线。

如果您在上述“解决方案”中发现错误，那么是时候继续证明第 5 节开头提出的定理了。

定理的证明。根据条件，圆 $\alpha$、$\beta$ 和 $\gamma$ 成对彼此外切 (图 7, a)。 $\alpha$和$\beta$之间的接触点将由$O$表示。

⟦folio 18⟧

让我们取一个以 $O$ 为中心的任意圆 $Q$ 并取相对圆的倒转 (图 6)。

在反转过程中，圆$\alpha$和$\beta$将变成平行线$\alpha'$和$\beta'$，圆$\gamma$将变成与这些线相切的圆$\gamma'$（图7，b）。反转中心 $O$ 位于（检查一下！）位于圆 $\gamma'$ 之外的线 $\alpha'$ 和 $\beta'$ 之间的带中。

显然有两个圆同时接触 $\alpha'$、$\beta'$ 和 $\gamma'$ (图 7, f)。在这种情况下，可能存在三种情况：

I. 点 $O$ 位于其中一个圆的内部（另一个圆的外部）。

二.点 $O$ 位于其中一个上（并且在另一个之外）。

三．点 $O$ 位于这两个圆之外。

在情况 I 和 II 中，我们用 $\delta'$ 和 $\varepsilon'$ 表示所考虑的圆（以及 $\delta'$ - 点 $O$ 所在的圆），在情况 III 中，我们用 $\delta'_1$ 和 $\delta'_2$ 表示它们。

任何与 $\alpha$、$\beta$ 和 $\gamma$ 相切的圆或直线在反转为与 $\alpha'$、$\beta'$ 和 $\gamma'$ 相切的圆时都会被重塑。在情况 I 中，圆 $\delta'$ 和 $\varepsilon'$ 相交，我们称它们为 $\delta$ 和 $\varepsilon$。在情况二中，$\delta'$经过了一个圆（我们称之为$\delta$），$\varepsilon'$经过了一条直线（即，$\alpha$、$\beta$和$\gamma$在这种情况下有公切线，而$\alpha$、$\beta$和$\gamma$显然位于它的一侧）。在情况 III 中，$\delta'_1$ 和 $\delta'_2$ 交叉了圆圈（我们称它们为 $\delta_1$ 和 $\delta_2$）。

因此，接触 $\alpha$、$\beta$ 和 $\gamma$ 的圆要么是两个，要么是一个。对于点 I，$O$ 位于$\delta$ 的外侧且$\varepsilon$ 的内侧，即$\delta$ 与$\alpha$、$\beta$ 和$\gamma$ 具有外切线，$\varepsilon$ 具有内切线。在点 II 的情况下，$O$ 位于 $\delta$ 之外 - $\delta$ 又与 $\alpha$、$\beta$ 和 $\gamma$ 具有外切线。在情况 III 中，这些点既位于 $\delta_1$ 外部又位于 $\delta_2$ 外部，因此它们都在外部接触 $\alpha$、$\beta$ 和 $\gamma$。

定理已被证明。

推论 1. 对于 $I$ 和 $II$ 三个四边形问题，我们有一个唯一解（圆 $\delta$ 的中心 $D$），对于 $III$，我们有两个解（圆 $\delta_1$ 的中心 $D_1$ 和 $D_2$ 和$\delta_2$）。

推论 2. 对于 $I$ 三个四边形问题，我们有唯一解（圆心$E$ $\varepsilon$），对于 $II$ 和 $III$，解是德语。

扫地。在第 3 节中，我们论证（根据第 1 节和第 2 节中提出的不正确理论）$n_1 = 1/d$ 和 $n_2 = -1/e$。在情况 I 中也是如此。在这种情况下$n_2 < 0$。在情况 II $n_2 = 0$ 中（这对应于以下事实：直线 - $\alpha$、$\beta$ 和 $\gamma$ 的公切线 - 曲率为零）。在情况 III 中，$n_1 = 1/d_1$ 和 $n_2 = 1/d_2$，其中 $d_1$ 和 $d_2$ 是圆 $\delta_1$ 和 $\delta_2$ 的半径；在这种情况下$n_2 > 0$。我们将验证第 6 条中刚才所做陈述的有效性。

给定三角形的边$ABC$，我们可以计算$n_{1,2}$并确定发生三种情况中的哪一种。

有时您可以不进行此类计算 - 我们将在第 7 节中讨论这一点。

§ 6.索迪公式的推导

1. 设$U, V$和$W$为三个任意非负数，其总和为$π$。然后
$$\sin^2 U = \sin^2 V + \sin^2 W - 2 \sin V \sin W \cos U.$$
证明。让我们构建一个具有角度 $U, V$ 和 $W$ 的三角形。设对边的长度为$u, v$和$w$。由余弦定理
$$u^2 = v^2 + w^2 - 2 vw \cos U.$$
根据正弦定理
$$u/\sin U = v/\sin V = w/\sin W.$$
从这里可以获得任何非零角度的必要公式。如果角度$U, V$和$W$至少有一个为0，则直接检查公式。

⟦folio 19⟧

2. 令 $A, B, C$ 和 $D$ 为平面上的任意四个点。然后
$$\sin^2 \frac{\angle ADB}{2} + \sin^2 \frac{\angle ADC}{2} - \sin^2 \frac{\angle BDC}{2})^2 = 4\sin^2 \frac{\angle ADB}{2} \times \sin^2 \frac{\angle ADC}{2} \cos^2 \frac{\angle BDC}{2}.$$
证明。点$A, B, C$和$D$的相对位置有(图8)四种情况。在每个中，我们将根据下表选择$U, V$和$W$。无论如何，$U \geq 0$、$V \geq 0$、$W \geq 0$ 和 $U + V + W = \pi$ 因此，根据第 1 点，
$(\sin^2 V + \sin^2 W - \sin^2 U)^2 = 4\sin^2 V \cdot \sin^2 W \cdot \cos^2 U$.
无论如何，仍然要利用这一事实
$$\sin U = \sin \frac{\angle BDC}{2}, \\
\sin V = \sin \frac{\angle ADC}{2}, \\
\sin W = \sin \frac{\angle ADB}{2}, \\
\cos^2 U = \cos^2 \frac{\angle BDC}{2}.$$
3. 设三角形的一个角为$\theta$，对边为$-u$，相邻的$-v$和$w$，我们就得到了三角形$-q$的米。然后
$$\cos^2 \frac{\theta}{2} = \frac{q(q - u)}{v \cdot w}, \quad \sin^2 \frac{\theta}{2} = \frac{(q - v)(q - w)}{v \cdot w}.$$
证明。由余弦定理
$$u^2 = v^2 + w^2 - 2vw \cos \theta, \quad \cos \theta = (v^2 + w^2 - u^2)/2vw.$$
方法，
$$\cos^2 \frac{\theta}{2} = \frac{1 + \cos \theta}{2} = \frac{(v + w)^2 - u^2}{4v \cdot w} = \frac{(v + w + u)(v + w - u)}{4v \cdot w} = \frac{q(q - u)}{v \cdot w},$$

⟦folio 20⟧

$$\sin^2 \frac{\theta}{2} = \frac{1 - \cos \theta}{2} = \frac{u^2 - (v - w)^2}{4v \cdot w} = \frac{(u + v - w)(u + w - v)}{4v \cdot w} = \frac{(q - w)(q - v)}{v \cdot w}.$$

4. 让圆心为$A, B, C$和$D$、半径为$a, b, c$和$d$的圆$\alpha, \beta, \gamma$和$\delta$成对地在外部相互接触。然后
$$\cos^2 \frac{\angle BDC}{2} = \frac{(b + d + c)d}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle BDC}{2} = \frac{bc}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle ADB}{2} = \frac{ab}{(a + d)(d + b)},$$
$$\sin^2 \frac{\angle ADC}{2} = \frac{ac}{(a + d)(d + c)}.$$

证明。在$\triangle BDC$中，我们通过$b, d$和$c$表达边和半周长：
$$BC = b + c, \quad BD = b + d, \quad DC = d + c,$$
$$\frac{1}{2}(BC + BD + DC) = b + d + c$$

并利用第3点的公式，由$\triangle ADB$和$\triangle ADC$类似地得到另外两个公式。
4'。让圆心为$A, B, C$、半径为$a, b, c$的圆$\alpha, \beta, \gamma$成对地从外部相互接触，并让三个圆从内部相互接触，中心为$E$、半径为$e$。然后
$$\cos^2 \frac{\angle BEC}{2} = \frac{(b - e + c)(-e)}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle BEC}{2} = \frac{bc}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle AEB}{2} = \frac{ab}{(a - e)(-e + b)},$$
$$\sin^2 \frac{\angle AEC}{2} = \frac{ac}{(a - e)(-e + c)}.$$

证明与第4点相同。
5. 在第4点的条件下，我们设置$k = 1/a, l = 1/b, m = 1/c, n = 1/d$。

然后
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

证明。根据第2段和第4段
$$\left[ \frac{ab}{(a + d)(d + b)} + \frac{ac}{(a + d)(d + c)} \right]^2 = 4 \frac{ab}{(a + d)(d + b)} \times \frac{ac}{(a + d)(d + c)} \cdot \frac{(b + d + c)d}{(b + d)(d + c)}.$$

将等式两边同时乘以$[(a + d)(b + d)(c + d)/abcd]^2$，我们得到
$$\left[ \frac{c + d}{cd} + \frac{b + d}{bd} - \frac{a + d}{ad} \right]^2 = 4 \frac{b + d + c}{bdc},$$

或者最后
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

扫地。如果我们将 $d$ 替换为 $(-e)$，则可以从第 4 段的公式得到第 4 段的公式。因此，第5段证明的公式在第4段对于$n = -1/e$的条件下也成立。

6. 圆 $\alpha, \beta, \gamma$ 和 $\delta$ 的曲率 $k, l, m$ 和 $n$ 两两外切，由索迪公式关联
$(k + l + m + n)^2 = 2(k^2 + l^2 + m^2 + n^2).$

如果 $n$ 是 $\alpha, \beta$ 和 $\gamma$ 从内部接触的圆 $\varepsilon$ 的曲率，则相同的公式成立。

证明。让我们转变身份
$(k + l + m + n)^2 = (-k + l + m + n)^2 + 4k(l + m + n)$

考虑到第 5 点：
$(k + l + m + n)^2 = 4(kl + km + kn + lm + ln + mn).$

利用身份优势
$(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2) = 2(kl + km + kn + lm + ln + mn),$

我们得到
$(k + l + m + n)^2 = 2[(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2)].$

引入类似的项，我们得到索迪公式。

7. 从第 6 段中证明的陈述可以得出以下结论：

⟦folio 21⟧

推论 1. 让我们假设（如第 3 节）
$$n_{1,2} = k + l + m \pm 2\sqrt{kl + lm + mk}.$$
那么，根据第 5 条，如果情况 I 发生，则$n_2 < 0$，如果情况 III 发生，则$n_2 > 0$。

练习 3. 证明情况 II $n_2 = 0$。

结合推论 1 和练习，我们得到

推论2. 如果$n_2 < 0$，则发生情况I，如果$n_2 = 0$，则发生情况II，如果$n_2 > 0$，则发生情况III。

§7. 另一个必要性

6月，M209题发布在题库«Kvant»中。

对于任何三角形 ABC，您可以计算以下总和：
$$S = \text{tg}^2 \frac{A}{2} + \text{tg}^2 \frac{B}{2} + \text{tg}^2 \frac{C}{2}.$$
证明：
a) $S < 2$ 对于所有锐角三角形和直角三角形；
b) $S > 2$ 对于钝角大于 2 arc tan $^4/3$ 的钝角三角形；
b) 对于任意满足$\frac{\pi}{2} < \varphi < 2\arctg \frac{4}{3}$的Φ，在钝角等于$\varphi$的钝角三角形中，存在满足$S > 2$的钝角三角形和满足$S < 2$的钝角三角形。

乍一看，问题 M195 和 M209 说的是完全不同的事情。但事实证明——又一个惊喜——它们之间存在着深厚的联系。

使用§6（第3点和第4点），很容易证明以下内容：

命题1.设圆心A、B、C，半径a、b、c成对地外接触的圆$\alpha, \beta, \gamma$，设$a + b + c = p$。然后
$$\text{tg}^2 \frac{A}{2} = \frac{bc}{ap}, \text{tg}^2 \frac{B}{2} = \frac{ac}{bp},$$
$$\text{tg}^2 \frac{C}{2} = \frac{ab}{cp}.$$

因此，$(a + b + c)S = \frac{bc}{a} + \frac{ac}{b} + \frac{ab}{c}$。将这个等式两边除以 abc，我们得到
$$S \left( \frac{1}{ab} + \frac{1}{bc} + \frac{1}{ca} \right) = \frac{1}{a^2} + \frac{1}{b^2} + \frac{1}{c^2}$$
或$S(kl + lm + mk) = k^2 + l^2 + m^2$。使用恒等式$k^2 + l^2 + m^2 = (k + l + m)^2 - 2(kl + lm + mk)$，我们发现：$(S + 2)(kl + lm + mk) = (k + l + m)^2$。

因此，以下条件是两两等效的：
$$S < 2 \text{ и } (k + l + m)^2 < 4(kl + lm + mk),$$
$$S = 2 \text{ и } (k + l + m)^2 = 4(kl + lm + mk),$$
$$S > 2 \text{ и } (k + l + m)^2 > 4(kl + lm + mk).$$

让我们记住这个公式
$$n_{1,2} = (k + l + m) \pm 2\sqrt{kl + lm + mk},$$
我们从这里得到它。

陈述 2. 条件 S<2、S=2 和 S>2 表征（对应）情况 I ($n_2 < 0$)、II ($n_2 = 0$) 和 III ($n_2 > 0$)。

因此，问题M209的结果允许相当一部分以△ABC的形式来说明情况I、II、III中的哪一个成立：如果△ABC是锐角或矩形，则情况I（问题M195在这种情况下只有一个解D），如果△ABC是“非常钝角”（$\varphi > 2\arctg^4/3$），则情况III（问题M195有两个解D$_1$和D$_2$）。 “分水岭”（案例二）沿着“不太钝”的三角形（$\pi/2 < \varphi < 2\arctg^4/3$）延伸。通过解决问题 M209 或阅读“问题书«Kvant»”中的解决方案，您将获得有关此“分水岭”的一些附加信息。
