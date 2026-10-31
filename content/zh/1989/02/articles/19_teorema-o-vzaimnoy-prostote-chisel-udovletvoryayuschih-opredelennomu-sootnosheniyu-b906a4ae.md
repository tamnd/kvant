---
id: 1989-2-teorema-o-vzaimnoy-prostote-chisel-udovletvoryayuschih-opredelennomu-sootnosheniyu-b906a4ae
issue: kvant_1989_2
year: 1989
number: "2"
title: 【满足一定关系的数的互质定理】
rubric: nam-pishut
page_first: 74
page_last: 82
page_labels: 72, 74, 76, 77, 78, 80
tag: VEXU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0d3f60ad3cdd78472f93d3f7203fbf1b32f65dc0042a5c4041c17f75e0c2efef
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/19_teorema-o-vzaimnoy-prostote-chisel-udovletvoryayuschih-opredelennomu-sootnosheniyu-b906a4ae.md
source_content_sha256: 665f005baaaa66157e96e542e14d91ff02b7c233407b0200c3dae80b61b356eb
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 72⟧

奈姆普特

来自基辅的 P. Wolfbein 报告了以下定理：

如果自然数$a_1, a_2, \dots, a_n (n \geq 3)$满足对应的$f(x) = x^2 - px + q$，其中$p = na_2a_3\dots a_n$，$q = a_2^2 + a_3^2 + \dots + a_n^2$。根据条件，$f(a_1) = 0$。还有$a_2^2 + q = 2a_2^2 + a_3^2 + \dots + a_n^2 \leq na_2^2$和$pa_2 = na_2^2a_3\dots a_n$。这意味着$f(a_2) = a_2^2 - pa_2 + q \leq 0$，只有在$a_2 = a_3 = \dots = a_n = 1$时才实现平等。

如果不是全部$a_i = 1$，则$f(a_2) < 0$。这意味着$a_1$是较大的根$f(x)$；让我们用 $a'_1$ 表示较小的根。根据维埃塔定理，$a'_1$是自然数，$a'_1, a_2, \dots, a_n$也满足原关系。所以，从这个集合$a_1, a_2, \dots, a_n$我们可以用更小的数量制作一个新的集合$a'_1, a_2, \dots, a_n$。

继续这个过程，我们将得到一组唯一的单元。如果原始集合包含非互质数对，那么这些对将出现在 Vieta 公式中：$a'_1 = na_2\dots a_n - a_1$。但在唯一的集合中不存在这样的对，这证明原始集合中的数字是互质的。

⟦folio 74⟧

$x$的所有值都满足该方程。否则我们得到方程
$$f(x) = (2 \lg a)x^2 + (2 \lg a - 2 \sqrt{22a - 4a^2 - 2a})x - a \sqrt{22a - 4a^2 - 2a} = 0.$$
为了以所需的方式定位其根，满足条件$f(0) \leq 0, f(-1) \leq 0$是必要且充分的。

6. $(42 + 12\sqrt{11})/5$。笔记。设$O_1$和$O_2$为半径为$r_1$的相等球的中心，并令$O_3$为小于半径为$r$、$K, L, M$的球的中心，即球与平面$\pi$、$W$从接触点垂下的垂线的底面的接触点球半径 $r_1$ (图 1) 的$P$。通过$O_3M$，我们绘制一个垂直于$O_1O_2$的平面，并将垂线$O_3Q$降低到$PW$。

然后是$PQ = r_1 - r$、$O_3P = \sqrt{r^2 + 2rr_1}$、$\frac{r_1 - r}{\sqrt{r^2 + 2rr_1}} = \frac{1}{\sqrt{5}}$，然后是$r_1 = 2r$。设 $R$ 为球体的半径。然后$OO_1 = R - 2r$，但是$r = R - 15$。因此$OO_1 = 30 - R$。将余弦定理应用到三角形$O_1OO_3$，我们得到$R = 18$、$r = 3$、$r_1 = 6$。此外，点$O$位于平面$O_3PW$、$O_1P = 6$、$OP = \sqrt{OO_1^2 - PO_1^2} = \sqrt{108}$内。因此$\cos \angle OO_3P = \frac{9}{(5\sqrt{5})}$。点$O$相对于直线$O_3Q$的位置有两种可能的情况（图2和3）。在第一种情况下，点$O$到直线$O_3Q$的距离为
$$OT = OO_3 \sin(\gamma - \delta) = \frac{12\sqrt{11} - 27}{5} < 3,$$
这种情况是不可能的。

在第二种情况下，距离为$OT + 3 = OO_3 \sin(\gamma + \delta) + 3 > 14$。

选项3
1. $(-1)^n \arcsin(2 - \sqrt{3}) + \pi n, n \in Z$.
2. $R \sin 2\alpha$.
3. $\{-1\}$.
4. 2 arctg（5 tg $\alpha$）。笔记。令$DM = 2a$，$MC = a$。根据正弦定理$\frac{AM}{\sin(\frac{A}{2} - \alpha)} = \frac{a}{\sin \alpha}$、$\frac{AM}{\sin(\pi - A)} = \frac{2a}{\sin \frac{A}{2}}$，
从哪里$tg(A/2) = 5 tg \alpha$。
5. 1; $-1/2; (-7 \pm 4\sqrt{2})/2$。笔记。将第二个方程乘以$a$并减去第一个方程，我们得到一个等式系统
$$\begin{cases} x(1 - a) - y(2a + 1) - a + \frac{3}{2} = 0, \\ xy + x + 2y + 1 = 0. \end{cases}$$

对于$a = 1$和$a = -1/2$，该系统有一个独特的解决方案。对于其余$a$，系统是一个二次方程，其唯一性条件是判别函数等于0。

6. 1/3； 2/3。解决方案。由于棱锥的侧面与底面平面的倾斜度相同，因此棱锥的高度是圆柱体的轴线，并穿过棱锥底面内切圆的中心（该圆的半径来自三角形$ABC$，且等于1）。圆柱体的上底内切于三角形 $DEF$ (图 4)，位于从原始金字塔切下类似金字塔 $SDEF$ 的平面上。让我们用 $m$ 表示相似系数。那么圆柱底面的半径就是$r = m$。在三角形$CSO_2:CO_2 = \sqrt{2}, DO_1 = \sqrt{2}m, CG = \sqrt{2}(1 - m), CD = \sqrt{38}(1 - m)$中。接下来，$DG = \sqrt{CD^2 - CG^2} = 6(1 - m)$，因此$S_{60k} = 2\pi r \cdot DG = 2\pi m \times 6(1 - m) = \frac{8\pi}{3}$（按照惯例），由此而来$m_1 = \frac{1}{3}$，$m_2 = \frac{2}{3}$。因此，有 2 个具有给定侧面平面的圆柱体。

选项4
1. 3.
2. $-\pi/3 + 2\pi n, n \in Z$.
3. $(1/2; 1/2)$
4. 9. 笔记。用$x = AC$表示圆的所有切线段，并写出三角形$ABC$的余弦定理。
5. 2； 3.解决方案。在 $a = 3$ 系统不兼容。对于$a \neq 3$，第一个系统有唯一解，但如果第二个系统有唯一解，则$y = 0$（因为$y$以四次幂出现在两个方程中）。姿势系统可以是平等的

⟦folio 76⟧

$$2n\left(\frac{80}{v_1} + \frac{120}{v_2}\right) < 168.$$
从$\frac{80}{v_1} + \frac{120}{v_2} > 2$开始，我们得到$4n < 168$，即$n < 42$。
令$v_1 = 10x$，$v_2 = 10y$。将第一个方程用$x$表示$y$，代入第二个方程，我们得到
$$nx^2 - (105 - 18n)x + 80n - 420 = 0.$$
可解性条件给出
$$n \leq 105\left(\frac{5}{2} - \sqrt{6}\right), \quad n \geq 105\left(\frac{5}{2} + \sqrt{6}\right),$$
从哪里$n = 5$。
6. [1/3； 33/32]。笔记。将$t = \sin x$、$b = 1 - a$代入，我们得到以下问题：对于$b$的什么值，对于任意$p \in [1, 2]$，方程$f(t) = pt^2 - t - b(p+2) = 0$至少有一个满足条件$|t| \leq 1$、$t^2 \neq b$的根？让我们立即将方程 $t^2 = b$ 只能对 $b = 0$ 成立，但方程 (*) 有一个根 $\frac{1}{p}$。方程 (*) 的根位于 $1 + 4pb(p+2) \geq 0$。当且仅当$b \geq -\frac{1}{32}$时，这个不等式对所有$p \in [1; 2]$成立。由于抛物线$y = pt^2 - t - b(p+2)$的顶点$t_0 = \frac{1}{2p}$的横坐标取线段[0; 1]，属于线段[-1;的方程(*)的根存在的充分必要条件； 1]，是至少一个不等式 $f(1) \geq 0; f(-1) \geq 0$ 对于所有 $p \in [1; 2]$ 的有效性。换句话说，对于所有这样的$p$，必须满足不等式$b \leq \frac{p+1}{p+2}; b \leq \frac{p-1}{p+2}$之一，但为此，存在$b \leq \frac{2}{3}$是必要且充分的。
选项9
1. 第一个数字更高。
2.1. $(-\infty; -7) \cup [2; +\infty)$.
2.2. $x_1 = \frac{2\pi}{9}(3n+2), x_2 = \frac{2\pi}{3}(3m+2), m, n \in \mathbb{Z}$.
3.1. $x_1 = \frac{\pi}{8}(4k+1), x_2 = \frac{\pi}{12}(4n+1), k, n \in \mathbb{Z}$.
3.2. $(-\infty; -7) \cup (-5; -3] \cup [2; +\infty)$.
4. 15/2。笔记。将 $y$ 替换为 $-y$ 不会更改匹配。因此，画一张$y \geq 0$的图就足够了。
5.11.笔记。从$\angle DBC = \angle BAC$开始，三角形$BAC$和$DBC$相似。
6.1. $a \in [-12/5; 0]$。笔记。由于$y = 3\sin^2 x + 2a\sin x\cos x + \cos^2 x + a = a\sin 2x - \cos 2x + a + 2 = \sqrt{a^2 + 1}\sin(2x - \varphi) + a + 2$，其中$\varphi = \arccos(a/\sqrt{a^2 + 1})$，必须执行系统
$$\begin{cases} \sqrt{a^2 + 1} + a + 2 \leq 3, \\ -\sqrt{a^2 + 1} + a + 2 \geq -3. \end{cases}$$
6.2. $a = 1$。笔记。第二个方程的根
$$x = \frac{\pi}{4} + \pi n.$$ 将它们代入第一个方程，我们得到$a$的二次方程，由此得出任意$a = 1$、任意$a = -3/2$。剩下的就是将获得的值$a$代入第一个方程并求解，得到对应的$\sin x = \sin x(\sin^2 x + \cos^2 x)$。
选项10
1. $\pi + 2\pi, \pm 4\pi/3 + 4\pi n, n \in \mathbb{Z}$.
2. $\{-2; 4/3; 3\}$.
3. $$\left[ -9; \frac{34 + \sqrt{116}}{5} \right).$$
4. 12点
5. 17/3。解决方案。我们有
$$S_{A_1BC_1} = \frac{1}{2} \cdot \frac{1}{4} S_{ABC} = 4,$$
$$S_{A_1BD} = \frac{1}{6} S_{A_1BC_1} = \frac{4}{3},$$
根据系数为 $ED : BD = 3 : 2$ 的三角形 $A_1BD$ 和 $C_1ED$ 的相似度，我们得到
$$S_{C_1ED} = \frac{9}{4} S_{A_1BD} = 3,$$
最后
$$S_{A_1DC_1} = S_{A_1BC_1} - S_{A_1BD} = \frac{8}{3},$$
$$S_{A_1C_1E} = S_{A_1DC_1} + S_{EDC_1} = \frac{17}{3}.$$
6. 1/9。解决方案。如果不等式有解，则$b \leq 1/9$。事实上，任何$b = 0$，$-\sqrt{b^2} \left(b(x - 4)^2 + \frac{1}{b(x - 4)^2}\right)$左侧的任何最大值，等于$-2\sqrt{b^3}$（对于$y + \frac{1}{y}$，其中$y = b(x - 4)^2$），不小于右侧的最小值，等于$-2b/3$，即$-2\sqrt{b^3} \geq -2b/3$或$9b \leq 1/9$。如果 $b = 1/9$，则不等式有效，例如，对于 $x = 1$。
选项11
1.2.
2. $(3/2; 0), (3/4; -3/2)$。笔记。您将分析揭示模型时出现的四种情况。
3. $\pm \pi/6, \pm \pi/4$.
4. 10. 解决方案。设$A$和$B$为边$KN$和$MN \cdot KN = x$的切点。然后从等式
$$BM^2 = DM \cdot LM = \frac{x}{9} \cdot x = \frac{x^2}{9},$$
$$AK = \sqrt{KC \cdot KL} = \sqrt{\frac{32}{9} \cdot 8} = \frac{16}{3},$$
$$BN = AN = KN - AK = x - \frac{16}{3}$$
我们有$MN = BM + BN = \frac{x}{3} + x - \frac{16}{3} = 8$，揭示$x = 10$。
5. 6.5小时。解决方案。首先，第二个工人在 $t$ 分钟内每分钟生产的零件比第一个工人少 $3/t$ 个零件，然后在

⟦folio 77⟧

x 分钟 - 比第一个每分钟多 5/x 份，随机性的增加为 5/x+3/t=0.2，因此 t=
$$\frac{3x}{0,2x-5}=15+\frac{15\cdot 25}{x-25}\leq 15+15\cdot 25=390$$
（因为$x\in\mathbb{N}$）。另一方面，对于$x=26$，问题的所有条件都已实现，并且$t=390$。

物理
物理学院
1. $v=\sqrt{gl\sin\alpha}$.
2. $F=Mg/\sqrt{3}$.
3. $A=(m/M)(R/T_1)(T_2-T_1)^2$.
4. $\alpha=M_BpV/(mRT)=0,17$.
5. $\varphi_C=\varphi_A-(\varphi_A-\varphi_B)d_1/(d-h)=22,5$V.
6. $\Delta q=C\mathcal{E}r/(r+R)$.
7. $I_2=I_1(\alpha_2/\alpha_1)(\sin\alpha_1/\sin\alpha_2)=0,15$A.
8. 第一种情况 (图 6, a)
$$\varphi_1=(\arcsin 1/n-\arcsin(\sin\alpha/n))/2;$$
第二种情况 (图 6, b)
$$\varphi_2=(\arcsin 1/n+\arcsin(\sin\alpha/n))/2.$$
9. $x=R^2/(\sqrt{R^2-a^2}-\sqrt{R/n^2-a^2})$.
10. $F=6l=6$见

化学学院
1. $\mu=\frac{H-h}{H+h}$ tg $\alpha=\frac{1}{3}\approx0,33$.
2. $F=mg(1-n/k)=0,3$N。
3. $\Delta U=Q-mR(T_2-T_1)/M=4845$ J.
4. $v_{\min}=\sqrt{5gl-Q^2/(4\pi\varepsilon_0ml)}\approx5$ m/c。
5. $I_4=I_1R_1R_5/(R_3R_4+R_3R_5+R_4R_5)=0,2$A.

感官研究学院和地理学院
1. $v_1=l_1\sqrt{\frac{2g(m_2l_2-m_1l_1)}{m_1l_1^2+m_2l_2^2}}\approx2,58$米/秒；
$v_2=v_1l_2/l_1\approx5,16$ m/c。
2. $p=p_0+\mu mg/S=110$千帕。
3. $q=\pm l\sqrt{4\pi\varepsilon_0mg}=3,0\cdot10^{-6}$ 吉隆坡。
4. $\mathcal{E}=U_1U_2/(U_2-U_1)\approx10,3$V.
5. $\beta_{\max}=\arcsin\sqrt{n^2-1}\approx53^\circ$.

地质学院
1. $R=\sqrt{3GM_3T^2/(4\pi^2)}=4,2\cdot10^7$ m（这里$T=24$ h 是地球绕地轴自转的周期）。
2. $l_2=\Delta l/(1-(T_1/T_2)^2)=1$米； $l_1=0,25$米。
3. $A=(p_0+Mg/S)V_0(T_2/T_1-1)=171$ J.
4. $E=\frac{1}{4\pi\varepsilon_0}\sqrt{\frac{q_1^2}{a_1^4}+\frac{q_2^2}{a_2^4}+\frac{q_3^2}{a_3^4}}\approx1,6\cdot10^8$V/m。
5. $\lambda=l/n=0,79$米。

图 6.

力学与数学学院
1. $\tau=\frac{h}{v}-\frac{v}{g}\left(\sqrt{1+\frac{2gh}{v^2}}-1\right)=3,2$ 页。
2. $A=5mgl/4=1,2$ J.
3. $h=\frac{a(h_1+h_2)-2h_1h_2}{2a-(h_1+h_2)}$.
4. $T_2=\sqrt{T_1T_3}=346$K.
5. $\Delta p=\frac{2QvR}{V(3vR+2mc)}=8\cdot10^4$帕。
6. $p=\varrho g(h_1-h)(l-h)/h=9,8\cdot10^4$帕。
7. $I_1=I_2=\frac{\mathcal{E}R_2}{R_1R_2+R_1R_3+R_2R_3}=\frac{1}{11}$A.
8. $t=2RC=20$ 页。
9. $P=\frac{k^2\pi l^4}{16R(\pi+1)^3}$.
10. $l=\sqrt{l_1l_2}=4$见

计算数学与控制论学院
1. $R=\sqrt{\frac{gr^2T^2}{4\pi^2}}$.
2. $k=\varrho_1/\varrho_2=5/4$.
3. $p=p_0\frac{2mcT+3p_0V_0}{2mcT_0+3p_0V_0}\approx1,1\cdot10^5$帕。
4. $Q=11,5$$p_0V_0=115$kJ。
5. $\varphi'=\varphi+\frac{mRT}{Vp_HM_B}\cdot100\%\approx60\%$.
6. $W=\frac{C_1C_2(U_1-U_2)^2}{2(C_1+C_2)}=0,03$ J.
7. $k=\frac{R+r/2}{R+2r}=0,5$.
8. $U=\sqrt{PR/\eta}=12,5$KV。
9. $\delta_{\max}=\pi/2-\arcsin(1/n)=45^\circ$.
10. $\varphi_{\max}=\arctg\left(\frac{a}{2F}\right)=0,1$很高兴。

选定的学校问题
1. {{0, 0}; (1, 2)}。解决方案。由于$1+x+x^2+x^3=(1+x)(1+x^2)$，所以$1+x$和$1+x^2$是2的幂。设 $1+x=2^m$；然后$1+x^2=2^{2m}-2^{m+1}+2$。如果$m>1$，则最后一个表达式除以 4 时余数为 2，并且不是 2 的幂。因此$m=0$或$1$和$x=0$或$1$。
2. $x_1=x_3=\ldots=x_9=-1$，$x_2=x_4=\ldots=x_{10}=1$。解决方案。将每个等式除以以下项（最后一个除以第一个），我们得到：$x_1=-x_4=x_7=-x_{10}=x_3=-x_6=x_9=-x_2=x_5=-x_8$。
3. 1, 0, 1, 1, 0, 1, 1, 0, 1, ..., 1, 1, 0, 1。解决方案。很明显，我们所有的数字都是非负的。让我们逆时针将它们排成一排，从最大的开始（如果有多个相同的）：$a_1, a_2, a_3, ..., a_{30}$。然后$a_1=a_2-a_3$或$a_1=a_3-a_2$，因此$a_2, a_3$中的一个数字是$a_1$，另一个是0。如果$a_2=a_1$，我们重新排列从$a_2$开始的数字。这意味着我们可以假设$a_2=0$。现在找到了数字$a_{30}$：

⟦folio 78⟧

图 7.

$$= |a_1 - a_2| = a_1, \ a_{29} = |a_{30} - a_1| = 0, \ ...$$
事实证明，我们的集合的形式为$a_1, 0, a_1, a_1, 0, a_1$。这些数字的总和是 20 $a_1$，因此 $a_1 = 1$。

4. 如果$A_1, A_2, \ ..., A_n$是这些点，$O$是圆心，则对称半径为$OA_1, OA_2, \ ..., OA_n$的60°扇形除了点$O$外不应有公共点。

5. 如果总共有$x$个男人，那么第一个位置不超过$\frac{2}{3}x$，第二个位置不超过$\frac{1}{3}x$。

6. 5000.解决方案。请注意，对于任何 $x$，$p(1) = \frac{1}{2}$ 和 $p(x) + p\left(\frac{1}{x}\right) = 1$。我们的总和包含一定数量（100）项$p(1)$，其余的可以分为对$p(x) + p\left(\frac{1}{x}\right)$。因此，项数之和乘以$\frac{1}{2}$。

7. 让我们输入$\frac{k(k+1)}{2} = a_k$。如果$a_k$是一个正方形，那么$a_{4k^2+4k} = 4a_k(2k+1)^2$也是一个正方形。因此 $a_1, a_8, a_{288}, \ ...$ 是正方形。 （想想是否还有其他数字 $a_k$ 是正方形。）

8. 5:10:13。解决方案。令 $ABC$ 为给定三角形，$AM$ 为中线 (图 7)。让我们输入$AF = FE = EM = x$，$BM = MC = y$。然后$AP^2 = AF \cdot AE = ME \cdot MF = 2x^2 = MR^2$。因此$AP = AQ = MR = x\sqrt{2}$。所以，$AC = AQ + QC = x\sqrt{2} + y + x\sqrt{2} = y + 2x\sqrt{2}$，$AB = AP + PB = x\sqrt{2} + y - x\sqrt{2} = y, BC = 2y$。从$4AM^2 = 2AB^2 + 2AC^2 - BC^2$开始，然后$36x^2 = 2y^2 + 2(y + 2x\sqrt{2})^2 - 4y^2$。因此$x\sqrt{2} = \frac{4}{5}y$。因此$AB:AC:BC = y:2y: \frac{13}{5}y$。

9. 让线 $AC$ 和 $BC$ 与给定圆相交于对应点 (图 8) 的点 $A_1$ 和 $B_1$，并让$\angle AMB = 2\alpha$。然后$\angle ACB = 180^\circ - \alpha$，因此$\angle AA_1B_1 + \angle BB_1A_1 = \alpha$。

由于$\angle AOB = 180^\circ - 2\alpha$（其中$O$是给定圆的中心），因此$\angle AA_1B_1 = 90^\circ - \alpha$。因此$\angle B_1A_1A + \angle AA_1B_1 + \angle BB_1A_1 = 90^\circ$。因此，$\angle B_1BA_1 = 90^\circ$，这意味着线段$B_1A_1$是一个直径。

10. 圆心为 $B$、半径为 $BA$ 的圆，没有四个点：$A, C$ 及其直径上相对的点，以及另外两个点：三角形的中心和相对于 $AC$ (图 9) 对称的点 $B$。表示：距离9种情况：1.$MA = MB = MC$； 2. $MA = MB = BC$。

图 8.

= BC; 3. $MA = MB, BC = MC$; 4. $MA = AB, MB = MC$; 5. $MA = AB, MB = BC$; 6. $MA = AB, MB = BC$; 7. $AB = BM = BC$; 8. $AB = BM = MC$; 9. $AB = BM, BC = MC$.

11. 显然，对于任何正的$x$和$y$，等式$\left(\frac{x}{y}\right)^{x-y} \geq 1$成立。因此$\left(\frac{a}{b}\right)^{a-b} \left(\frac{b}{c}\right)^{b-c} \left(\frac{c}{a}\right)^{c-a} \geq 1$，这就是$(a^a b^b c^c)^2 \geq a^{b+c} b^{c+a} c^{a+b}$的意思。

12. 让我们以$4(a^2 + b^2 + c^2 + d^2 - 2ab - 2bc - 2cd - 2da) + (a + b + c + d)^2 \geq 0$的形式重写herabenity。左侧表示为平方和：$(a - b + c - d)^2 + 2(a - b)^2 + 2(b - c)^2 + 2(c - d)^2 + 2(d - a)^2$。

13. 令$h_a, h_b, h_c, h_d$为三角形$ABC$的高，并将高$h_d$投影到一点。如果$h_d$与$h_a$和$h_b$相交，则该点位于面的两个高度上，但它也位于第三个高度上；这意味着$h_d$与$h_a$和$h_b$相交，3）如果三个高度成对相交，则它们都经过一个点。确实，否则它们就会位于同一平面上，这显然是没有必要的。我们的声明是显而易见的。例如，如果 $h_d$ 与 $h_a$ 和 $h_b$ 相交，则根据性质 2) $h_d$ 与 $h_c$ 相交，根据性质 1) $h_a, h_b$ 和 $h_c$ 成对相交，

⟦folio 80⟧

$$\frac{(M+2m)u^2}{2} + E_{\text{вн}(Z-2)} + \hbar \omega,$$
$$mv + (M+m)V = (M+2m)u + \hbar \omega/c.$$

内能$E_{\text{вн}(Z-1)}$和$E_{\text{вн}(Z-2)}$的值在以下段落中定义。

3) $E_{\text{вн}(Z-1)} = -\frac{k^2 Z^2 e^4 m}{2 \hbar^2}$.

4) $E_{\text{вн}(Z-2)} = -\frac{k^2 e^4 m (Z-1/4)^2}{\hbar^2}$.

5) $Z=4$；所需的离子是 $\text{Be}^{2+}$。

信息

1989年第一期《科学与生活》杂志刊登了莫斯科国立大学全联盟函授数学学院生物系的入学条件和入学任务。如果您不仅对物理和数学感兴趣，而且对生物学感兴趣，我们邀请您参加比赛。

VZMSH 生物委员会

《«Kvant»》杂志编委会、编集和编委会高度优先通知读者，1988年12月8日，编委会成员安德烈·彼得罗维奇·埃尔绍夫院士去世。

修正案
在«Kvant»第11-12页，一年过去了。图2显示了A. N. Kolmogorov死亡的最新数据。安德烈·尼古拉耶维奇 (Andrei Nikolaevich) 于 1987 年 10 月 20 日去世。编辑们将他们的发现带给读者。

主编——于院士。 A·奥西皮扬

副主编：
V.N.博罗维什基，A.A.瓦尔拉莫夫，
V. A. 列什科夫采夫 (V. A. Leshkovtsev)，Yu. P·索洛维约夫

编辑集：
A.A.阿布里科索夫，M.I.巴什马科夫，
V. E. Belonuchkin、V. G. Boltyansky、
A.A.博罗沃伊，于。 M.布鲁克，V.V.瓦维洛夫，
N.V.瓦西里耶夫、S.M.沃罗宁、V.V.格内登科、
V. L. Gutenkhacher，N. P. Dolbilin，
V.N.杜布罗夫斯基，A.N.泽姆利亚科夫，
A.R.齐伯曼、S.M.科泽尔、
S.S.克罗托夫、L.D.库德里亚夫采夫、A.A.列昂诺维奇、
S.P.诺维科夫、T.S.彼得洛娃、M.K.波塔波夫、
V. G. 拉祖莫夫斯基 (V. G. Razumovsky)、N. A. 罗迪纳 (Rodina)、N. Kh.罗佐夫,
A.P.萨文，Ya。 A·斯莫罗金斯基，
A.V. 索辛斯基、V.M. 乌列夫、V.A. 法布里坎特

编委会：
A. M. Baldin、S. T. Belyaev、E. P. Velikhov、I. Ya。 Verchenko，V.V.沃兹季任斯基，
G.V.Dorofeev，N.A.Ermolaeva，
A. P. Ershov，Yu. V. 伊万诺夫、V. A. 基里林、G. L. 科特金、R. N. 库兹明、A. A. 洛古诺夫、V. V. 莫扎耶夫、V. A. 奥尔洛夫、N. A. 帕特里克耶娃、R. Z. 萨格杰耶夫、S. L. 索博列夫、A. L. 斯塔森科、I. K. 苏林、E. L. 苏尔科夫、L. D. 法德耶夫、V. V.菲尔索夫·G·N·雅科夫列夫

准备编号：
A. N. Vilenkin、A. A. Egorov、L. V. Kardasevich、I. N. Klimova、T. S. Petrova、S. L. Tabachnikov、V. A. Tikhomirova

注册号：
于。 A. Vashchenko、M. V. Dubakh、S. V. 伊万诺夫、T. N. Kolchenko、D. A. Krymov、S. F. Lukhin、I. E. Smirnova、E. K. Tenchurina、L. A. Tishkov、P. I. Chernusky、O. N. Estis、V. V. Yudin

美术编辑
S·V·伊万诺夫
艺术编辑 T. M. Makarova
编辑部主任 L. V. Chernova
校对员 N. D. Dorokhova

交付至 88 年 11 月 23 日。于 2089 年 1 月 4 日签署出版。 T-04004。格式70×100/16。胶版纸1号。胶版印刷。有条件的 kr.-ott。 27.10。有条件的烤箱l。 6.45。学术版。湖8.10。发行量187,365份。订单 2942。价格 45 戈比。

红色替代劳工令
契诃夫印刷厂
VO“联盟测谎仪”
苏联国家委员会
用于出版、印刷和图书贸易
142300 契诃夫, 莫斯科地区

103006 莫斯科 K-6，圣。高尔基，32/1，«Kvant»，电话。 250-33-54
