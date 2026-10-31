---
id: 1971-5-alimov-vasilev-modenov-vstupitelnyiy-pismennyiy-ekzamen-po-matematike-na-fakultete-vyichislitelnoy-matematiki-i-kibernetiki-mgu-v-1970-godu-0795de16
issue: kvant_1971_5
year: 1971
number: "5"
title: 1970年莫斯科国立大学计算数学与控制论学院数学入学笔试
authors:
  - Алимов Ш. А.
  - Васильев Ф. П.
  - Моденов В. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 47
page_labels: 42-45
tag: JUJ4
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8b4b07a60b468c054bc37985deca18e3f685b64eda4766064028112c2ff71eb8
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/11_alimov-vasilev-modenov-vstupitelnyiy-pismennyiy-ekzamen-po-matematike-na-fakultete-vyichislitelnoy-matematiki-i-kibernetiki-mgu-v-1970-godu-0795de16.md
source_content_sha256: b45821f77d0742a3789fc8ee2d1f5539cd1795171fda37cbe318767cfc40bfb9
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

1970年莫斯科国立大学计算数学与控制论学院数学入学笔试

什。 A. 阿利莫夫、F. P. 瓦西里耶夫、V. P. 莫德诺夫

在过去的二十年里，数学科学在人类知识的一般体系中的重要性已不可估量地增加。其主要原因是计算数学的发展。电子计算机的发明不仅在计算能力和方法上​​带来了真正的革命，而且在数学应用的本质上也带来了真正的革命。可见，数学机器的质量、数量、应用和管理体系是决定国家科学技术水平的重要组成部分。

在这方面，需要培养新专业的数学家。 1970 年，M.V. 开设了一个新的系。莫斯科国立罗蒙诺索夫大学 - 计算数学和控制论学院。同年，该学院首次录取。

在数学笔试中，每位申请者都会收到五个问题的变体，解答时间为 4 个小时。为了获得满意的成绩，必须解决两个以上的问题。正确解决所有五个问题获得了优异的分数。

作为示例，让我们看一下由笔试中提供的任务组成的典型版本。

选项0
1. 确定 $a$ 的所有实数值，对于每个实数值，方程 $\cos^4 x - (a-2)\cos^2 x - 3(a+1) = 0$
有一个解决方案，并找到所有这些解决方案。
2. 解方程
$$\left| 1 + \log \frac{1}{3} x \right| = 3 + \left| 2 - \log \frac{1}{3} x \right|.$$

3. 从城市$A$到城市$B$，距$A$ 240公里，一辆autorus以40公里/小时的速度出发。同时，以$v$公里/小时的匀速从$B$到$A$，自动机退出。车子汇合后半小时，到达市区$A$之前，折返，以同样的速度朝$B$方向行驶。确定 $v$ 的所有值，其中 autoroms 比 autorus 更平等地达到 $B$。
4. 在三角形$ABC$中，$BC$边长等于$AB$和$AC$边长的算术平均值。角度$A$等于$\alpha$。假设 $B \geq C$，求角度 $B$ 和 $C$。研究问题在角度 $\alpha$ 的值是多少时有解。
5. 在顶点为 $S$ 的直圆锥中，高度 $SO$ 与发电机之间的角度等于 φ。在圆锥体外侧的基面上，选择两个点$A$和$B$，使得线$SA$和$SB$相互垂直，并形成高度为$SO$的角度，对应于$\alpha$和$\beta$。计算圆锥体侧面与三角形 $OSA$ 和 $OSB$ 相交的生成元之间的角度。

⟦folio 43⟧

问题分析

1. 请注意，$0 \leq \cos^2 x \leq 1$ 对于所有$x$。然后，使用代入 $\cos^2 x = t$，将方程简化为系统：

$$\begin{cases} t^2 - (a - 2)t - 3(a + 1) = 0, \\ 0 \leq t \leq 1, \end{cases}$$

其在 $-1 \leq a \leq 0$ 处有解 $t = a + 1$。因此，

$$\cos^2 x = a + 1,$$

其中$-1 \leq a \leq 0$。从这里

$$x = \pm \arccos \sqrt{a + 1} + \pi n$$

($n = 0, \pm 1, \pm 2, \dots; -1 \leq a \leq 0$).

大多数申请者都应对了这项任务。部分申请人解错了式（1），错误地认为$\arccos (-\sqrt{a + 1}) = \arccos \sqrt{a + 1}$，而丢失了式$\cos x = -\sqrt{a + 1}$对应的解。一些申请人没有指出存在问题解决方案的$a$的所有值。

2. 未知数可接受的取值范围：$x > 0$。让我们将方程重写为以下形式

$$|1 + t| = 3 + |2 - t|,$$

其中$t = \log \frac{1}{3} x$。连续间隔$t \leq -1, -1 < t < 2, t \geq 2$。对于$t \geq 2$，我们有$1 + t = 3 + t - 2,$

也就是说，对于所有$t \geq 2$，方程（1）都得到有效满足。接下来，我们验证方程（1）对于$t \leq -1$和$-1 < t < 2$无解。因此，方程（1）都是$t \geq 2$。因此$\log \frac{1}{3} x \geq 2$，并考虑查找的定义域

$$0 < x \leq 1/9.$$

一些申请人注意到相同的方程（2），并写道，对于所有$t$，该方程都有效满足，而不考虑约束$t \geq 2$。

3. 令 $t(u)$ 为自动机第一次与自动机相遇之前的运动时间。由于自动机和自动机同时离开，所以等式成立

$$40t + vt = 240.$$

(1)

汽车离开城市$B$后，经过$t + \frac{1}{2}(u)$浮出水面，经$2t + 1(u)$返回$B$。第一次见面后，巴士行程$vt(\kappa m)$，这一趟花费$\frac{vt}{40}(u)$。因此，从$A$到$B$的整个旅程，巴士需要$t + \frac{vt}{40}(u)$。为了让小车比公交车早到达 $B$，不等式

$$2t + 1 < t + \frac{vt}{40}.$$

(2)

根据地表自动机的情况，在到达城市$A$之前。由于在第一次相遇时，他与 $A$ 的距离为$40t(\kappa m)$，并且在接收路径$\frac{v}{2}$期间，因此这个条件得出不等式

$$\frac{v}{2} < 40t.$$

(3)

结合(1)、(2)和(3)，我们得到系统：

$$\begin{cases} 40t + vt = 240, \\ 2t + 1 < t + \frac{vt}{40}, \\ \frac{v}{2} < 40t. \end{cases}$$

从方程（1）中我们找到$t = \frac{240}{v + 40}$并将其代入不等式（2）和（3）中。通过联合求解 $v$ 所产生的不等式，我们找到 $56 < v < 120$。

大多数申请人能够完成方程（1）和不等式（2），尽管其中一些申请人替换了（2）中的<符号

⟦folio 44⟧

到 ≤ 符号。错误的主要部分是由条件（3）引起的，因为许多申请人不理解这一要求的必要性，并且仅限于解决从（1）和（2）获得的系统。

4. 根据条件

$$BC = \frac{AB + AC}{2}.$$

(1)

使用正弦定理我们发现

$$AB = BC \frac{\sin C}{\sin \alpha}, \quad AC = BC \frac{\sin B}{\sin \alpha}$$

并将其代入式(1)中。我们得到

$$\sin B + \sin C = 2 \sin \alpha,$$

$$\sin \frac{B + C}{2} \cos \frac{B - C}{2} = \sin \alpha.$$

因为

$$B + C = \pi - \alpha,$$

(2)

然后 $$\sin \frac{B + C}{2} = \cos \frac{\alpha}{2},$$ 和

$$\cos \frac{B - C}{2} = 2 \sin \frac{\alpha}{2}.$$

(3)

由于根据条件$B \geq C$，此外还有$0 < C < \pi, 0 < B < \pi$，则

$$0 \leq B - C < \pi.$$

(4)

注意到$$\sin \frac{\alpha}{2} > 0$$，根据确定$B$和$C$的条件(2)、(3)、(4)，我们有系统：

$$\begin{cases} B - C = 2 \arccos \left(2 \sin \frac{\alpha}{2}\right), \\ B + C = \pi - \alpha. \end{cases}$$

(5)

由(5)有

$$\begin{cases} B = \frac{\pi - \alpha}{2} + \arccos \left(2 \sin \frac{\alpha}{2}\right), \\ C = \frac{\pi - \alpha}{2} - \arccos \left(2 \sin \frac{\alpha}{2}\right). \end{cases}$$

因此，对于$\alpha$的所有值，如果存在满足问题所有条件的三角形$ABC$，则角度$B$和$C$的值由公式（6）获得。

让我们研究一下问题在 $\alpha$ 的什么值有解。由(6) 必然得出

$$\left| 2 \sin \frac{\alpha}{2} \right| \leq 1.$$

由于$0 < \alpha < \pi$，因此$0 < \sin \frac{\alpha}{2} \leq \frac{1}{2}$，因此，$0 < \alpha \leq \frac{\pi}{3}$。

对于找到的$\alpha$值，由公式（6）确定的$A = \alpha, B$和$C$值为正，总计等于$\pi$。为了证明这一点，只需检查条件$C > 0$或$0 < \alpha \leq \frac{\pi}{3}$，以及（6）中的$B \geq C, \alpha + B + C = \pi$即可。

让我们证明 $C > 0$ 或者根据 (5)，

$$\frac{\pi - \alpha}{2} > \arccos \left(2 \sin \frac{\alpha}{2}\right).$$

(7)

由于 cos $x$ 在线段 $0 \leq x \leq \pi$ 上单调消亡，并且数量 $\frac{\pi - \alpha}{2}$ 和 arccos $\left(2 \sin \frac{\alpha}{2}\right)$ 属于该线段，因此，计算不等式（7）两边的余弦，我们有 $$\cos \frac{\pi - \alpha}{2} = \sin \frac{\alpha}{2} < 2 \sin \frac{\alpha}{2}.$$

对于$0 < \alpha < \frac{\pi}{3}$，这个不等式成立。

以相反的顺序重复我们的推理，我们确信不等式$C > 0$的有效性。

因此，一个具有角度$A = \alpha, B \geq C$且满足问题条件的三角形$ABC$，角度$B$和$C$的值由公式（6）、$0 < \alpha \leq \frac{\pi}{3}$给出。

许多申请人在收到确定$B$和$C$的系统后无法解决该问题，有些人将答案写在表格（6）中，但没有调查问题在$\alpha$的值是多少时有解。一些申请人仅指出了等边三角形的情况

$$\alpha = B = C = \frac{\pi}{3}.$$

5. 令 $x$ 为生成元 $SA_1$ 和 $SB_1$ 之间的互斥角度，圆锥体的侧面沿着该角度与三角形 $OSA$ 和 $OSB$ 相交（参见 图ok）： $\Rightarrow ASB = \frac{\pi}{2}, \Rightarrow OSA = \alpha,$

⟦folio 45⟧

很少有申请人能够完成这项任务。

注意，公式(1)和(2)表示内二面角与三面角的顶点处的平角之间的关系。一般情况下，如果$A, B$和$C$是两个内角，与三面角的相应平面角$\alpha$、$\beta$和$\gamma$相反，则有效公式为：

$$\cos A = \frac{\cos \alpha - \cos \beta \cos \gamma}{\sin \beta \sin \gamma},$$

$$\cos B = \frac{\cos \beta - \cos \alpha \cos \gamma}{\sin \alpha \sin \gamma},$$

$$\cos C = \frac{\cos \gamma - \cos \alpha \cos \beta}{\sin \alpha \sin \beta},$$

与式（1）同理求得。这些公式可用于解决许多立体问题。

总之，我们建议您独立解决笔试中提供的以下选项。

选项1

1. 确定方程 $\cos^4 x - (a+2)\cos^2 x - (a+3)=0$ 有解的每个 $a$ 的所有实数值，并找到所有这些解。

2. 解方程

$$|1 - \log_1 x| + 2 = |3 - \log_1 x|.$$

3. 从城市$A$到城市$B$，距$A$ 105公里，一辆autorus以恒定速度$v$公里/小时出发。 30分钟后，一辆车跟着他以40公里/小时的速度从$A$出来，在途中追上公交车后又折返并以相同的速度行驶。确定汽车到达$B$晚于汽车返回$A$的所有$v$值。

4. 在三角形$ABC$中，边$BC$作为半圆的底，其面积等于三角形$ABC$的面积。角度$A$等于$\alpha$。求角度 $B$ 和 $C$，假设 $B \geq C$。研究问题在角度 $\alpha$ 的值是多少时有解。

5. 在顶点为$S$的直圆锥体中，生成元$SA$和$SB$之间的角度等于$\alpha$，并且它们在底平面上的投影之间的角度等于$\beta$。计算角度 $OSA$ 和 $OSB$ 的三等分线之间的角度，其中点 $O$ 是作为圆锥体底面的圆的中心。
