---
id: 1991-6-chokin-slinki-shagayuschaya-pruzhinka-ecc7f67e
issue: kvant_1991_6
year: 1991
number: "6"
title: Slinky - 行走的弹簧
authors:
  - Чокин Д.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 44
page_last: 46
page_labels: 42-44
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2b5c8a8b39cc8c3c1d7eb1cdcfb01b876c661d44c83f7f6be6078b4c5e467de0
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/14_chokin-slinki-shagayuschaya-pruzhinka-ecc7f67e.md
source_content_sha256: a759a078355d9fce0082d4b1f74898aa719b1c67114c3fcef977d1772a7790d6
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

Slinky - 行走的弹簧

D·乔金

这篇文章将向您介绍一种神奇的玩具，在美国被称为“弹力带”。这是一种弹性系数非常低的弹簧，其线圈直径为5至10厘米，线圈数量为50至100个。尽管看起来很简单，但这样的弹簧很难自己制作。您需要经过特殊热处理的特殊钢材，才能实现弹簧的低弹性。也就是说，这个属性允许我们执行

Diar Chokin 在还是一名学生时就写了这篇文章（RFS，阿拉木图）。现在他是莫斯科国立大学物理系的学生。

图 1.

⟦folio 43⟧

---
running_head:
folio:
---

桥具有线性弹簧密度，从到下端的距离，该密度与每单位长度的匝数成正比。让我们看看春天的一些部分。让它落在第$n$圈，从弹簧下端算起。如果这一圈的长度是$\Delta x_n$，那么

$$\Delta k \Delta x_n = \Delta mng,$$

其中$\Delta k$是一圈的刚度，$\Delta m$是它的质量。那么我们发现第$n$匝的平均线密度等于

$$\lambda_n = \frac{\Delta m}{\Delta x_n} = \frac{\Delta k}{ng},$$

或者，考虑到弹簧有 $N$ 圈，其整体刚度为 $k$，-

$$\lambda_n = \frac{Nk}{ng}.$$

现在让我们找到从该线圈到弹簧下端的距离。由于$\Delta x_n = \Delta mng/\Delta k$，通信距离等于

$$x_n = \sum_{i=1}^{n} \frac{\Delta mg}{\Delta k} i = \frac{\Delta mg}{\Delta k} \frac{n(n+1)}{2} \approx \frac{\Delta mgn^2}{2\Delta k} = \frac{Mg}{2k} \frac{n^2}{N^2},$$

其中$M$是整个弹簧的质量。 （有趣的是，悬挂弹簧的总长度$L_0 = Mg/(2k)$原来是其长度的一半

$$x_n$$

图 2.

将是相同的失重弹簧，其末端悬挂有质量$M$的负载。

比较得到的线密度$\lambda_n$和距离$x_n$的表达式，找出它们之间的关系：

$$\lambda_n = \frac{k}{g} \frac{N}{n} = \sqrt{\frac{Mk}{2gx_n}}.$$

为了方便起见（稍后我们将需要它），我们从线性密度分布的离散表示转向连续表示，采用无限匝数的极限情况（参见 图 3）：

$$\lambda(x) = \sqrt{\frac{Mk}{2gx}}.$$

现在是时候估计参与运动的弹簧的质量了。我们假设所需零件相当于一个自由悬挂的弹簧，其长度为$h$（$h$是台阶的高度）。然后，使用最后一个公式，我们估计未知质量：

$$m_0 = \int_0^h \lambda(x) dx = \int_0^h \sqrt{\frac{Mk}{2gx}} dx = \sqrt{\frac{2Mkh}{g}}$$

以及该质量与总质量的比率：

$$\frac{m_0}{M} = \sqrt{\frac{2kh}{Mg}} = \sqrt{\frac{h}{L_0}}.$$

弹簧质量参与运动的部分越少，它的运动就越稳定。因此，要提高弹簧的行走性能，从得到的比值可以看出，需要降低弹性系数，增加弹簧的质量，

⟦folio 44⟧

---
running_head:
folio:
---

从不太高的台阶上发射诱饵。一般来说，最好在木星上这样做，以增加自由落体速度 $g$。为了实现压缩，取$h=10$cm和$L_0=1$m，我们得到$m_0/M \approx 0,3$。

要确定紧身裤一步的时间，请使用牛顿第二定律。设上转弯初速度为$v$。然后
$$v\Delta m = F\Delta t,$$

其中$F$是附件在顶点处的拉力，$\Delta m$是附件在$\Delta t$时间开始移动的质量。如果$\lambda_0$是在运动开始处着陆的线密度，则$\Delta m = \lambda_0 v\Delta t$，并且
$$\lambda_0 v^2 = F.$$

很明显
$$\lambda_0 = \sqrt{\frac{Mk}{2gh}}, \quad a = F = m_0 g = \sqrt{2Mgkh}.$$

对于“展开”的速度，我们得到
$$v = \sqrt{\frac{F}{\lambda_0}} = \sqrt{2gh}.$$

让质量为$\Delta m = \lambda_0 v\Delta t$的附件的一部分在时间$\Delta t$期间“展开”。代入值$\lambda_0$和$v$，我们有
$$\Delta t = \frac{\Delta m}{\sqrt{Mk}}.$$

我们从哪里得到迈出一步的时间：

$$T = \sum \Delta t_i = \frac{1}{\sqrt{Mk}} \sum \Delta m_i = \sqrt{\frac{M}{k}} = \sqrt{\frac{2L_0}{g}}.$$

有趣的是，一步的时间并不取决于台阶的高度，并且该时间与台阶的自由振荡周期和物体从$L_0$高度落下的时间具有相同的数量级。例如，取$L_0$的值等于1 m，我们得到$T \sim 0,5$ s，这通过实验得到了很好的证实。

另一个同样重要的撬样经验是纵向机械波的建模。为了进行这个实验，需要拉伸夹具并沿轴压缩其一圈，从而使其成为波传播的起点。滚动和拉伸的波将沿着夹点传播，并从其末端反射。有趣且有用的经验。它可以在学校展示，以可视化纵波并研究其特性。例如，众所周知，介质密度的降低会导致纵波速度的增加。这可以通过使用紧身衣进行实验来轻松验证——稍微拉伸它就足以使波速显着增加。

也许，可以使用刚性非常低的拉链（即带有紧身拉链）进行更多有趣的实验。
