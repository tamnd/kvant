---
id: 1976-7-dozorov-zachem-transformatoru-serdechnik-adbfd834
issue: kvant_1976_7
year: 1976
number: "7"
title: 变压器为什么需要铁芯？
authors:
  - Дозоров А. А.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14-17
tag: 9FIE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9eccf52aaed67ec5757634f57e59b83a407dab54243b4bd58bba8667c1d1af49
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/05_dozorov-zachem-transformatoru-serdechnik-adbfd834.md
source_content_sha256: b17570371dc02d0303f682125af7fac7f23c41d00d30cd7a1bff5fc634dae84d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

让我们记住如何构建变压器及其工作原理。

最简单的变压器（参见图）由缠绕在普通钢芯上的两个线圈（绕组）组成。一个绕组（初级）连接到交流电源。消耗电力的设备（所谓的负载）连接到第二绕组（次级）。第一和第二绕组都被源的交变电流产生的相同的交变磁通量刺穿。在第一个绕组中，匝数为 $n_1$ E.D.出现。和。感应 $e_1 = -n_1 \frac{\Delta \Phi}{\Delta t}$（ΔΦ 是通过一圈时间 $\Delta t$ 的磁通量变化），以及次级 - E.D.和。感应$e_2 = -n_2 \frac{\Delta \Phi}{\Delta t}$。

我们假设次级绕组开路，即考虑变压器的冷运行模式。我们还假设初级线圈的有源电阻与其感应电阻相比非常小。根据欧姆定律，所有 E.D. 的总和。和。闭合电路中的电压降等于该电路中的电压降之和（通常以这种形式编写的欧姆定律称为基尔霍夫定律）：

$$u_1 + e_1 = i_1 R_1.$$

这里$u_1$是电流源的电压，$i_1$是电流，$R_1$是初级绕组的有功电阻。因为$R_1$很少（$R_1 \rightarrow 0$），$u_1 + e_1 = 0$，或者

$$u_1 = -e_1.$$

当次级绕组开路（$i_2 = 0$）时，其两端电压

$$u_2 = -e_2.$$

因此，电压比$\frac{u_2}{u_1} = \frac{e_2}{e_1}$，或者对于抢夺动作

$$\frac{U_2}{U_1} = \frac{\mathcal{E}_2}{\mathcal{E}_1} = \frac{n_2}{n_1}.$$

这封信引起了标题中提出的问题。事实上，电压比仅取决于绕组的匝数比，并且不存在根据（1）的磁芯参数。这些参数可以是任意的吗？是否可以在没有铁芯的情况下运行变压器？如果是，在什么条件下？

在推导对应关系（1）时，假设通过初级线圈和次级线圈的磁通量相等。然而，这个条件可能无法满足：初级线圈产生的部分磁通量可能会消散而不会穿透变压器的次级绕组，这不可避免地会导致技术成本。

⟦folio 15⟧

变压器的容量。那么，也许磁芯的主要目的是减少磁通量耗散？但可以通过其他方式避免移民！例如，将次级绕组直接缠绕在初级绕组上，或者将绕组缠绕在环面（方向盘）上。问题再次出现，标题中的结构：为什么变压器需要一个重铁芯，其中除其他外，会产生能量损失 - 傅科电流、磁滞？总的来说，核心有很多缺点。那么为什么需要它呢？

于是，问题就形成了，并受到谴责；是时候继续回答这个问题了。

通常，与理论描述的理想模型（尤其是最简单的模型）相比，真实设备的性能较差。这适用于变压器。什么样的变压器可以合理地称为理想的？让我们尝试定性地理解这一点。在变压器中，电磁能从初级线圈传输到次级线圈。在最好的情况下，次级绕组电路中释放的能量将等于初级绕组从源消耗的能量。我们不能谈论能源，而是谈论权力。还希望功率最大，即功率因数 f≈1。从数学上讲，这些要求记录在系数系统中。

考虑一个具有大量匝数的长线圈（底部）。载流导体产生的磁场感应始终与电流强度成正比，并且还取决于导体的配置、磁场感兴趣点的位置以及介质的磁特性。螺极内部的磁场是均匀的。可以证明该场的归纳为$B = \mu_0 \mu I n/l$。这里$\mu_0$是磁常数，$\mu$是介质的相对磁导率，$n$是螺线节点的匝数，$l$是其长度。那么从等式(3)
$$\Phi = B S n = \mu_0 \mu I n^2 S/l.$$

将该表达式与式（4）进行比较，我们发现

⟦folio 16⟧

电磁螺线管电感：
$$L = \mu_0 \mu n^2 S/l. \quad (5)$$

类似地，引入了两个电路的互感系数（互感）$M$的概念。在我们的例子中，变压器的初级和次级绕组的互感概念。当次级绕组与负载短路时，次级电路中就会出现电流。我们将其有效值表示为$I_2$。同时，初级绕组中的电流发生变化。现在其有效值$I_1$不再与变压器冷运行时相同。由初级绕组的电流 $I_1$ 产生的通过次级绕组的磁通量 $\Phi_2$ 与该电流成正比：
$$\Phi_2 \sim I_1, \text{ или } \Phi_2 = MI_1.$$
同样，由次级绕组的电流 $I_2$ 产生的通过初级绕组的磁通量 $\Phi_1$，
$$\Phi_1 \sim I_2, \text{ или } \Phi_1 = MI_2.$$
比例系数$M$是互感系数，即变压器绕组的互感。与螺振管电感值的推导类似，可以得到$M$的表达式：
$$M = \mu_0 \mu n_1 n_2 S/l. \quad (6)$$
由表达式(5)和(6)可知
$$M = \frac{n_2}{n_1} L_1 = \frac{n_1}{n_2} L_2. \quad (7)$$

请注意，事实上，变压器铁芯中当然只有一个磁通量。实际上，它完全由连接到初级绕组电路的电流源的电压决定。然而，为了清楚起见，我们可以分别考虑电流$I_1$和$I_2$产生的磁通量。

现在让我们再次回到变压器并继续讨论其在运行模式下的运行。我们首先为初级绕组的闭合电路写出欧姆定律（基尔霍夫定律），然后为次级绕组写出欧姆定律（基尔霍夫定律）。在每

⟦folio 17⟧

这里$A, B, \alpha$和$\beta$是常数。
第一电流变化率

$$\frac{\Delta i_1}{\Delta t} = \frac{i_1(t + \Delta t) - i_1(t)}{\Delta t} =$$

$$= A \frac{\sin [\omega(t + \Delta t) - \alpha] - \sin (\omega t - \alpha)}{\Delta t} =$$

$$= 2 \frac{A}{\Delta t} \sin \frac{\omega \Delta t}{2} \cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right).$$

将$\Delta t$指向零$\left(\sin \frac{\omega \Delta t}{2} \approx \frac{\omega \Delta t}{2}\right)$，

$$\cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right) \approx \cos (\omega t - \alpha)),$$

我们得到

$$\lim_{\Delta t \to 0} \frac{\Delta i_1}{\Delta t} = A \omega \cos (\omega t - \alpha).$$

同样地

$$\lim_{\Delta t \to 0} \frac{\Delta i_2}{\Delta t} = B \omega \cos (\omega t - \beta).$$

将式（8）、式（9）转化为三角方程：

$$U_0 \sin \omega t - p MA \omega \cos (\omega t - \alpha) - MB \omega \cos (\omega t - \beta) = 0,$$

(8a)

$$- \frac{1}{p} MB \omega \cos (\omega t - \beta) -$$

$$- MA \omega \cos (\omega t - \alpha) = RB \sin (\omega t - \beta).$$

(9a)

变换元素（打开括号）之后的每个方程都可以写成以下形式

$$a \sin \omega t + b \cos \omega t = 0,$$

(10)

其中系数 $a$ 和 $b$ 不依赖于时间。

仅当$a=0$和$b=0$同时存在时，方程(10)在任何时间$t$都有效。因此，两个方程被转换为四个方程：

$$\begin{cases}
U_0 - p MA \omega \sin \alpha - MB \omega \sin \beta = 0, \\
p A \cos \alpha + B \cos \beta = 0, \\
- \frac{1}{p} MB \omega \sin \beta - MA \omega \sin \alpha = RB \cos \beta, \\
\frac{1}{p} MB \omega \cos \beta + MA \omega \cos \alpha = RB \sin \beta.
\end{cases}$$

求解该系统后，我们将找到初级和次级电路中电流的幅值以及电流相对于外部电压同相的 dwgi。

最后我们得到

$$I_{0_1} = A = \frac{U_0}{p^2 R} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2},$$

$$I_{0_2} = B = \frac{U_0}{p R},$$

$\alpha = \arctg \frac{p R}{M \omega}, \beta = \pi$.

我们找到的解决方案是否满足理想变压器的要求（分别为（2））？让我们检查一下。让我们求出电流幅值之比：

$$\frac{I_{0_1}}{I_{0_2}} = \frac{A}{B} = \frac{1}{p} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2}.$$

最后一个表达式与对应关系 (2) 一致，如果在根下第二项趋于零：

$$\frac{R}{M \omega} = \frac{R l}{\mu_0 \mu S n_1 n_2 \omega} \rightarrow 0$$

（匝数比$p$必须保持恒定）。因此，变压器可以被认为是理想的，如果

a) 介质的磁导率$\mu$足够大，

b) 交流电压$\omega$的频率足够高，

b)初级和次级绕组的匝数较大，

d) 次级绕组有功电阻小，

d) 线圈的长度最短，即绕组缠绕紧密。

要创建一个接近理想的变压器，您需要选择实际意义上最方便的变换。这首先是介质高磁导率的转变。对于真空 $\mu=1$，对于铁磁体 $\mu \approx 10000$。增加匝数实际上是无利可图的（变压器的尺寸和成本急剧增加），并且将电流频率增加数千倍会带来重大的技术问题。现有的高频变压器实际上是无铁芯使用的，其性能接近理想变压器。
