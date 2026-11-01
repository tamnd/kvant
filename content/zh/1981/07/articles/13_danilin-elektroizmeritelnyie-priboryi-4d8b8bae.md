---
id: 1981-7-danilin-elektroizmeritelnyie-priboryi-4d8b8bae
issue: kvant_1981_7
year: 1981
number: "7"
title: 电气测量仪器
authors:
  - Данилин В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 45
page_labels: 39, 40, 42, 43
tag: I40F
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4219bec12ceb6b14d42c21e6c0190dcb98f060ca6e0c1d1b91d7b199170b2bd9
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/13_danilin-elektroizmeritelnyie-priboryi-4d8b8bae.md
source_content_sha256: d8b263aac26aaeda95daff553f25fc4792ca6e5b3918c34a36c84594221c1037
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

V·达尼林

电子测量仪器

In all electronic measuring instruments, the effect of the electron current is reduced to the movement of the moving part of the measuring mechanism.一般可移动的部分和与其相关的装置的箭头绕其轴线旋转。引起这种旋转的力矩称为转动力矩。 In order for the pointer to not turn off indefinitely, and for the angle of deflection to correspond to the value being changed, it is necessary to counteract the rotation of the pointer.产生这种效果的力矩称为反作用力矩。

在实践中，反作用力矩总是由压力的微小弹性产生。但转折点可以通过不同的方式创造。根据产生扭矩的方法，电气测量仪器被分配给一个或另一个系统。让我们看看其中的一些。

磁电系统装置的工作原理基于导体与电流和磁场的相互作用。 The field is created by a permanent magnet 1 (图 1), the current passes through a coil in the form of a frame 2. The frame is a movable element of the device and is on the same axis with the arrow 3.

由于设计了磁铁，作用在框架上的扭矩不依赖于框架的旋转角度，并且等于

$$M_{\text{вр}} = |\vec{B}| \text{INS},$$

其中$\vec{B}$是磁场感应，$I$是电流，$N$是框架中的匝数，$S$是其面积。在这一刻的影响下，框架开始旋转。在这种情况下，螺旋弹簧 4 扭转并产生反作用力矩，该反作用力矩与框架 $\alpha$ 的旋转角度成正比：

$$M_{\text{пр}} = k\alpha,$$

其中 $k$ 是比例系数，取决于压力的弹性特性。

当反作用力矩等于扭矩时，框架停止。在这种情况下，框架的旋转角度以及箭头的旋转角度等于

$$\alpha = \frac{|\vec{B}| \text{SN}}{k} I,$$

也就是说，primo 与帧中的电流成正比。这样保证了仪器刻度的统一性。

麦克尼特电设备仅设计用于直流电，这当然是它们的缺点。这些设备的优点包括低能耗和高灵敏度。

磁电系统中最敏感的设备是镜面检流计。其中，基于箭头的介入，固定了一个小平面镜。灯泡发出的窄光束

图 1.

⟦folio 40⟧

落在镜子上，镜子反射的兔子落在远处的刻度上。镜面检流计的灵敏度可达$10^{-12}$A/mm。

问题1. 镜面检流计的尺寸为$S = a \times b = 40 \times 30$ mm²，其上缠绕$N = 100$ 匝直径为$d = 0,1$ mm 的铜线。框架悬挂在一根线上，当线扭转$\alpha_0 = 1^\circ$角度时，会产生反作用力矩$M_0$。磁场在所有可能的位置都垂直于框架的旋转轴；磁场感应$|\vec{B}| = 10^{-1}$ T。距检流计$L = 1$ m 处有毫米刻度。 1) 如果 $I = 0,1$ mA 的电流通过其绕组，则框架表面呈什么角度？ 2) 设备消耗的功率 $P$ 对应于秤上兔子的偏差 $l = 1$ 毫米？

1) 当框架处于平衡状态时，扭矩$M_{BP} = |\vec{B}|INS$由反作用力矩$M_{np} = k\alpha = M_0\alpha/\alpha_0$平衡：

$$|\vec{B}|INS = \frac{M_0\alpha}{\alpha_0} \alpha.$$

从这里

$$\alpha = \frac{|\vec{B}|INS\alpha_0}{M_0\alpha} = 12^\circ.$$

2) 检流计消耗的功率取决于流过框架绕组的电流$I$及其电阻$R$：

$$P = I^2R.$$

让我们找出当前 $I$ 对应于秤上兔子的距离 $l$ 的偏差。当框架和镜子旋转角度 $\alpha$ 时，反射光束旋转角度 $2\alpha$（请自行检查），并且兔子沿着刻度移动距离 $l = 2\alpha L$（我们教过$l \ll L$）。因此，

$$I = \frac{k\alpha}{|\vec{B}|NS} = \frac{M_0\alpha}{\alpha_0} \frac{l}{2L} \frac{1}{|\vec{B}|NS} \approx 2,4 \cdot 10^{-7} \text{ A}.$$

图 2.

框架绕组的电阻为

$$R = \varrho \frac{l'}{s} = \varrho \frac{2(a+b)N}{\pi d^2/4} \approx 31 \text{ Om}.$$

最后

$$P = I^2R \approx 1,8 \cdot 10^{-12} \text{ Bt}.$$

在电动系统的设备中，扭矩是由流经两个线圈的电流$i_1$和$i_2$的相互作用产生的：静止线圈1和运动线圈2 (图2)。一般情况下，电流是可变的，并按照规律$i_1 = I_{1M} \cos \omega t$和$i_2 = I_{2M} \cos (\omega t - \varphi)$变化。

扭矩的瞬时值与电流的乘积成正比：$M_{BP} \sim i_1i_2$。由于惯性，动圈没有时间跟随扭矩的瞬时变化，因此其偏差与一段时间内的平均值成正比

$$M_{BPcp} = kI_1I_2 \cos \varphi.$$

这里$k$是常数系数，$I_1$和$I_2$是有效电流值，$\varphi$是它们之间的相移。如果绕组串联，设备的读数将与电流的平方成正比。因此，天平也是一个不平坦的装置。

显然，电动系统的器件可以改变交流电路中的功率（$P_{cp} = IU \cos \varphi$，其中$U$为有效电压值）。为此，只需将一个线圈（固定）与选定的电路部分串联，将第二个线圈（移动）与该部分并联即可。确切地

⟦folio 42⟧

电流表串联到电路中，整个被测电流都通过它。因此，为了不向电路中引入额外的电阻，电流表的阻值应尽可能小。电压表并联到应测量电压的电路部分。因此，它的电阻应该尽可能高，以免在所研究的电路部分上开玩笑。

任务4.估计测量电流和电压时出现的误差，考虑到电流表和电压表的具体电阻值（图4）。

在图4处的电路中，流过电流表A的电流与电压电阻$R_H$相同。因此，电流表读数不存在误差。但电压表测得的负载电压与真实电压不同：

$$U_H = I R_H, \quad U_V = I (R_H + R_A).$$

因此，测量负载电压的绝对误差等于

$$\Delta U = |U_H - U_V| = I R_A,$$

和相对误差

$$\delta = \frac{\Lambda U}{U_H} = \frac{I R_A}{I R_H} = \frac{R_A}{R_H}.$$

在图 4、b处的电路中，电压表读数为真，电流表显示流过负载和流过电压表的电流之和：

$$I_A = I_H + I_V = \frac{U_H}{R_H} + \frac{U_H}{R_V}.$$

电流测量的绝对误差和相对误差等于相应的

$$\Delta I = |I_H - I_A| = I_V = \frac{U_H}{R_V}$$

和

$$\delta = \frac{\Delta I}{I_H} = \frac{U_H}{R_V} : \frac{U_H}{R_H} = \frac{R_H}{R_V}.$$

问题 5. 一个内阻未知的电压表首先连接到阻值为 $R_1$ 的电阻，然后连接到阻值为 $R_2$ 的电阻，最后连接到阻值为 $R$ (图 5) 的电阻。

在这种情况下，电压表读数分别为 $U_1 = 4$ V、$U_2 = 6$ V 和 $U = 12$ V。忽略电源的内阻，在没有电压表的情况下确定第一和第二电阻器上的电压$U_{01}$和$U_{02}$。

当连接到阻值$R$的电阻时，电压表读数等于源的电动势（因为源的内阻可以忽略）。

当电压表连接到第一个电阻时，该部分$R'_1$的电阻为

$$\frac{1}{R'_1} = \frac{1}{R_1} + \frac{1}{R_V},$$

其中$R_V$是电压表的内阻。此部分的电压等于电压表读数$U_1 = 4$V，第二个电阻两端的电压为$U - U_1 = 8$V$= 2 U_1$。由于相同的电流流过电路的两个部分，因此我们有 $R_2 = 2 R'_1$，或者

$$\frac{1}{R_1} + \frac{1}{R_V} = \frac{2}{R_2}.$$

如果电压表连接到第二个电阻，那么，经过类似的计算，我们得到

$$\frac{1}{R_2} + \frac{1}{R_V} = \frac{1}{R_1}.$$

从最后一个方程中减去前一个方程，我们发现

$$\frac{R_1}{R_2} = \frac{U_{01}}{U_{02}} = \frac{2}{3}.$$

除了，

$$U_{01} + U_{02} = U.$$

因此，

$$U_{01} = \frac{2}{5} U = 4,8 \text{ В}, \quad U_{02} = \frac{3}{5} U = 7,2 \text{ В}.$$

在实践中，经常使用具有多个限制的设备

⟦folio 43⟧

电流和电压测量。为此，在测量电压时，将额外的电阻与设备串联，而在测量电流时，将并联电阻（分流器）连接到设备。在某些情况下，可以同时连接附加电阻和分流器。 （请注意，连接额外的电阻和分流器不仅可以使器件具有多量程，而且还可以减少与器件内阻增加或减少相对应的测量误差。）

问题6.内阻为$R_\Gamma = 50$欧姆的检流计，其测量分度电路为$C = 50$μA。该量表分为 $N = 100$ 个分区。如何使用该设备制作电压表来测量高达 $U = 200$ V 的电压或电流表来测量高达 $I = 800$ mA 的电流？

当指针通过检流计偏转至满刻度时，流过最大允许电流
$$I_{\text{пр}} = CN = 5 \text{ мА},$$
在这种情况下，检流计上的电压等于
$$U_{\text{пр}} = I_{\text{пр}} R_\Gamma = 250 \text{ мВ}.$$

为了使用该检流计测量高达$U$值的电压，必须与检流计串联一个附加电阻$R_\Delta$。它两端的电压$U_\Delta$等于电路中和检流计上的电压差，流过检流计和附加电阻的电流相同。这就是为什么
$$\frac{U_\Delta}{U_\Gamma} = \frac{R_\Delta}{R_\Gamma},$$

图 5. 图 6.

图 7.

在哪里
$$R_\Delta = R_\Gamma \frac{U_\Delta}{U_\Gamma} = R_\Gamma \left( \frac{U}{U_\Gamma} - 1 \right) \approx 40 \text{ кОм}.$$

要将检流计用作与检流计并联的电流表，必须连接一个电阻为 $R_\Delta$ 的分流器。电路中流动的电流$I$等于检流计中的电流$I_\Gamma$和分流器中的$I_\Delta$之和，并且检流计和分流器上的电压相同。因此，
$$I_\Gamma R_\Gamma = I_\Delta R_\Delta,$$

在哪里
$$R_\Delta = R_\Gamma \frac{I_\Gamma}{I_\Delta} = R_\Gamma \frac{I_\Gamma}{1 - I_\Delta} = \frac{R_\Gamma}{1 - I_\Delta} \approx 0.31 \text{ Ом}.$$

练习
1. 在图6所示的电路中，所有电压表都是相同的。电池电动势$\mathcal{E} = 5$V，内阻低。第一个电压表显示 $U_1 = 2$ V。其他电压表显示什么？
2. 为了测量电路$CC$中的大电流，使用分流器$Ш$，并通过电阻$R_1 = 2$欧姆和$R_2 = 90$欧姆（图7）与测量装置$\Gamma$并联。在开关$\Pi$的位置$A$，设备的整个刻度对应于电路中的电流$I_1 = 10$A，在位置$B$ - 对应于电流$I_2 = 100$A。找到设备$\Gamma$的内阻$r$。分流电阻远小于$R_1$和$R_2$。
3. 当接通$R_\Delta = 100$欧姆电阻的分流器时，并行测量装置在外电路中的电流为$I_1 = 3$A时使指针偏离满量程。当在非屏蔽检流计上接通$R_\Delta = 300$欧姆的附加电阻时，设备的刻度变得比没有附加电阻和分流器时大四倍。当外电路电流为$I_2 = 7.5$A时，应采取什么分流器才能使表针偏转至满量程？
4. 内阻为$r_\Gamma$的检流计，与电阻$R_\Delta$并联，并与附加电阻$R_\Delta$串联，用作电压表。在$U_1 = 1$ V 电压下，检流计指针会偏离一格。需要多大的附加电阻才能使检流计指针在 $U_2 = 10$ V 电压下偏离一格？
