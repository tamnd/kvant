---
id: 1979-2-kotkin-pochemu-ploho-krichat-protiv-vetra-359bc97a
issue: kvant_1979_2
year: 1979
number: "2"
title: 为什么对着风大喊不好？
authors:
  - Коткин Г. Л.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 5-7
tag: 21PS
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 384f2ec7064be5ecd686c11c3ea0938e2485e86adb1f0a5121a033885d1c8d7e
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/04_kotkin-pochemu-ploho-krichat-protiv-vetra-359bc97a.md
source_content_sha256: 7a79c80d96003e69d879765a3771d2d39b4a5cccf274159df6a803218a3130b9
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

G·科姆金

为什么逆风喊叫不好？

如果风从我们这里吹向它的源头，为什么我们听到的声音很差？
乍一看，这一点很清楚。扔出的石头逆风落下，鸟儿飞得更慢……不过，让我们尝试检查一下定量评估。

设声速相对于空气的速度为$c$，风速为$u$。那么声音信号相对于地面的速度为$|c| - |u|$，其传播距离$l$的时间为$t = \frac{l}{|c| - |u|}$。在此期间，信号相对于空气传播一段距离

$$l' = |c| t = \frac{l |c|}{|c| - |u|}.$$

标称值$l'$决定了声音的衰减：距声源距离$l$（逆风），我们听到的声音就像没有风且距离$l'$一样。

接收$|u| = 15$米/秒（强风），$|c| = 330$米/秒，$l = 50$米。然后$l' \approx 52$米。风将我们“推”了大约 2 m。拜托，我们不会注意到这一点。事实上，城市风的影响更大。因此，我们必须寻找另一种解释。

让我们注意这样一个事实：不同高度的风速并不相同——它随着距地面高度的增加而增加。大家，当声源和接收器位于同一高度时，这不应该以任何方式影响声音的传播。如果声音接收器（或源）下降，声音信号的部分路径将穿过以较低速度移动的空气层，并且到达时衰减较小。事实上，如果一个随机（或大喊大叫）的人蹲下，听力只会变得更差。然而重点恰恰在于风速对高度的依赖性。

为了更容易理解声音传播的图景，我们首先按距离举一个例子。让我们想象一艘摩托艇 $J$ 以相对于水的速度 $c$ 移动，与水流成一定角度 (图 1)。让中间的人（我们称他为队长）“瞄准”远处可见的工厂烟囱$T$。如果没有电流，

⟦folio 6⟧

ka 将在$A$点降落在海岸上。实际上，船相对于岸的速度是$\vec{v} = \vec{c} + \vec{u}$。如果水流$\vec{u}$的速度一直恒定到岸边，那么船将在点$B$着陆。但当接近海岸时，水流的速度会致命，因此船$\vec{v}$的速度大小和方向发生变化，使其沿着曲线$JD$移动。

我们假设机长短暂打瞌睡，但继续将方向盘保持在同一位置。趁他睡觉的时候，让我们看看随着水流漂浮的浮冰$C\Pi$。该浮冰漂浮旋转：它被水驱动旋转，水在浮冰的一个边缘 ($C$) 落后于它，而在另一边缘 ($\Pi$) 则超过它。同样的情况也发生在船上。它会转动，并且速度$\vec{c}$的方向会改变（尽管方向盘保持不动）。醒来后，船长会看到描绘$JE$弧线的船正在远离海岸。

现在我们不难描绘出声音信号传播的图景了。它们的轨迹（“射线”）是弯曲的，就像一艘沉睡的船长的船的轨迹（图2；风从右向左吹）。在这种情况下，区域$MLN$实际上是一个“死区”：声音“射线”不会进入其中。在此区域中的人几乎听不到来自$S$的声音。 （“死区”中的一些可听度是由于声音被地面反射而散射以及声音的衍射造成的。）

然而，让我们记住，当我们试图量化这一现象时，我们发现了对该现象的第一个解释的不一致。让我们尝试检查第二种解释的定量评估。我们来估计一下到“死区”的距离。距离“射线”$SLM$（参见图2），我们将认为其方向接近水平。让我们选择波浪表面的最小部分 $AB$ 并认为它是平坦且垂直的 (图 3)。过了一会儿$\Delta t$这一段

图 2.

将占据位置$A'B'$，并且

$$|AA'| = (|\vec{c}| - |\vec{u}_A|) \Delta t,$$

$$|BB'| = (|\vec{c}| - |\vec{u}_B|) \Delta t$$

（$\vec{u}_A$和$\vec{u}_B$是点$A$和$B$高度处的风速）。在这种情况下，该截面被认为旋转了一个小角度 $\alpha$：

$$\alpha \approx tg\alpha \approx \frac{|B'B''|}{|A'B''|} =$$

$$= \frac{(|\vec{c}| - |\vec{u}_A|) - (|\vec{c}| - |\vec{u}_B|)}{\Delta h} = \frac{|\Delta u| \Delta t}{\Delta h},$$

其中$|A'B''| = |AB| = \Delta h$和$\Delta u = \vec{u}_B - \vec{u}_A$。

因此，波面的一部分将以角速度旋转

$$\omega = \frac{\alpha}{\Delta t} \approx \frac{|\Delta u|}{\Delta h}.$$

速度矢量$\vec{c}$，即声速相对于空气的速度，也以相同的角速度旋转。

我们假设$\omega$的值是沿着整个“射线”构建的，那么$SLM$（参见图2）部分可以被认为是一段圆弧。蜂鸣速度

⟦folio 7⟧

结果，风中附着力变差的原因有很多，但上面的计算给出了增加，我们正确地指出了主要原因。

在实践中
1. 在一个夏日的午后，甲虫决定飞向太阳，并以$|\vec{v}| = |\vec{c}| - |\vec{u}| \approx |\vec{c}|$的速度飞行，这个速度可以与这个圆的半径$r$相关联：$|\vec{v}| = \omega r$。从这里开始 (图4)
$$|SO| = |OL| = r = \frac{|\vec{v}|}{\omega} \approx \frac{|\vec{c}| \Delta h}{|\Delta u|}.$$
从三角形OSF
$$|SF| = \sqrt{|OS|^2 - |OF|^2} = \sqrt{r^2 - (r - h)^2} \approx \sqrt{2rh} \approx \sqrt{2|\vec{c}|h \Delta h}.$$
因此，听者与声源位于同一高度$h$，在一定距离处落入“死区”
$$|SS'| = 2|SF| \approx 2\sqrt{2|\vec{c}|h \Delta h}.$$
接待处$\frac{|\Delta u|}{\Delta h} \approx \frac{|\vec{u}|}{h}$。然后最后
$$|SS'| \approx 2h \sqrt{\frac{2|\vec{c}|}{|\vec{u}|}} \approx 3h \sqrt{\frac{|\vec{c}|}{|\vec{u}|}}.$$
对于 $h=1,5$ m、$|\vec{c}| = 330$ m/s 和 $|\vec{u}| = 15$ m/s，我们得到
$$|SS'| \approx 20$$

相当合理的结果。对“声线”形状的精确计算会得出相同的结果。
