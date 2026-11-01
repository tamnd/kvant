---
id: 1987-7-hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0
issue: kvant_1987_7
year: 1987
number: "7"
title: Как построить траекторию?
authors:
  - Хилькевич С. С.
  - Зайцева О. А.
rubric: raznoe
page_first: 28
page_last: 32
page_labels: 26, 28, 29, 30
tag: DGVW
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f07d026081e39e91b427fbb9a6250327ccddbeb50164bb1171f6ea51add20d0b
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/07_hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0.md
source_content_sha256: 6abe958734e9192f4001adcf90e72d762fc3d895ad872f9e453f928e5148c886
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

经常会遇到计算特定人体运动轨迹的需要。 This problem arises both before an Australian aborigine sneaking up on a flock of birds with a boomerang, and before a mathematician calculating the location of a spaceship.

在读完童话故事之前，不要指指点点。

该方法的主要思想非常简单，基于众所周知的连接材料点的位移矢量与其平均速度矢量的关系。回想一下平均速度 $\vec{v}_{\text{cp}}$ 不均匀运动称为等于位移比的物理量 $\vec{s}$ 一段时间内的身体 $\Delta t$ 至此间隔的持续时间：

$$\vec{v}_{\text{cp}} = \frac{\vec{s}}{\Delta t}.$$

从这里

$$\vec{s} = \vec{v}_{\text{cp}} \Delta t.$$

平均速度和位移都是矢量，因此在图中它们被描绘为有向线段。在这种情况下，两个向量的方向相同，但长度相差 $\Delta t$ 倍。 Obviously, with an appropriate choice of scale, it is possible to make the directed segments depicting the average speed and displacement coincide

$$\vec{v}_0$$

图 1.

completely - both in direction and in length.正是这种情况使得快速且某种程度上构建各种轨迹成为可能，当然是近似的。

我们首先考虑最简单的情况——匀速直线运动。假设在初始时刻，物体位于点 $A_0$ 且速度为 $\vec{v}_0$ (图 1)。 Since (as we agreed) the displacement vector over the time interval $\Delta t$ coincides with the velocity vector, then after this interval the body finds itself at point $A_1$, at which the initial velocity vector $\vec{v}_0$, delayed from $A_0$, appears.从点 $A_1$ 存入另一个向量 $\vec{v}_0$，我们得到点 $A_2$，在两个间隔 $\Delta t$ 后，物体结束于该点。 Continuing this procedure, we obtain a sequence of points $A_n$ at which the body will be located after $n$ selected time intervals from the beginning of the movement.走、经过这些点就是匀速直线运动的轨迹。

他们是第一个考虑将 CRA 推广到“多手玩家”（即拥有两只以上手牌的玩家）的情况的人。

选自《数学花园》系列

为了近似构建轨迹，我们将身体的整个运动时间划分为小间隔*)，

*) 根据运动条件的不同，“小”间隔的持续时间可以从几分之一微秒到数十亿年不等。唯一重要的是它远小于所讨论过程的持续时间。

⟦folio 28⟧

点$A_3$。 The body will end up in it after the interval $\Delta t$ after passing the point $A_2$, etc. The construction gives an approximate trajectory - a broken line, which is similar to the well-known parabola, which is the true trajectory.

这个问题的解决方案似乎并不特别，因为答案是从学校物理课程中提前知道的。此外，将获得的结果与已知结果进行比较可以让您检查该方法，并且验证总是有用的。

现在我们准备考虑一个在学校没有研究过的更复杂的问题，即物体在存在空气阻力的情况下在重力场中的运动。设初始时刻物体位于$A_0$点，速度$\vec{v}_0$（图4），空气阻力$\vec{F}_c$与物体速度矢量$v$对应$\vec{F}_c = -\alpha \vec{v}$（α为常数系数）。有必要确定在这种情况下身体的轨迹是什么。

由重力和阻力两种融合引起的加速度 $\vec{a}$ 可以根据牛顿第二定律确定。然而，对于构造而言，将加速度 $\vec{a}$ 表示为两个分量的总和更为方便：由重力产生的加速度 $a_t = g$ 和加速度 $\vec{a}_c = \vec{F}_c / m = -(\alpha / m)\vec{v}$。如果以图表的形式描述$a_c$对$v$的依赖关系，那么从中很容易确定对于任何身体速度值，加速度$\vec{a}_c$的大小。例如，该加速度始终与速度矢量 $\vec{v}$ 的方向相反。

Let's start building the trajectory.物体从点$A_0$开始移动后，经过一小段时间$\Delta t$（参见图4），最终到达点$A_1$。为了构建下一步的速度向量，需要关闭从点$A_1$开始的初始速度向量$\vec{v}_0$，并添加加速度向量$\vec{a} = \vec{g} + \vec{a}_c$（我们已经知道如何分别构建向量$\vec{g}$和$\vec{a}_c$）。作为构造的结果，我们获得点 $A_2$ - 新的速度矢量将指向它。这样，身体开始运动后，经过两段时间，就会到达$A_2$点。

重复这个过程，我们得到点$A_3$，在另一个时间间隔后，物体将在该点结束，然后是点$A_4$，$A_5$等。请注意，每个时间段后的加速度$\vec{a} = \vec{g} + \vec{a}_c$必须再次确定，因为分量$\vec{a}_c$取决于速度，因此在运动过程中不会保持恒定。

通过点$A_0$、$A_1$、$A_2$、...的虚线表示物体在存在空气阻力的情况下的近似飞行轨迹。该曲线的特殊之处在于，与抛物线（参见 图 3）不同，它相对于穿过飞行点的垂直线不对称：轨迹的传出分支比上升分支更圆。现在看一下我们根据羽毛球教科书制作的模型*) 图 5，它显示了各种发球时波浪的飞行路径。你看到了吗？

几乎所有的轨迹都有一个显着的特征——它们是不对称的。这在体育基础上应用非常广泛。例如，高发球通常会在天花板高度和球员力量允许的范围内发球——同时，在对手场地的后线上，羽毛球几乎垂直落下，回球的羽毛球由于羽毛的阻碍而无法强力反击。

现在凝结的条件是自然的，例如，添加了作用在身体上的另一种力。提供

*) Rybakov D. P., Shtilman M. I. 运动基础基础。 （硕士，体育文化与体育，1978年。）

⟦folio 29⟧

事实证明，这让我们可以考虑一个非常美丽的问题……

在这里，我们建议读者停止阅读几分钟，将一张纸折叠成一架“飞机”，并展示它以不同速度和与地平线不同角度发射时在空中的特技。首先，这让你有机会放松一下，其次，经过这样的实验，你会对阅读接下来写的内容更有兴趣。

纸飞机是怎样飞起来的？

这里不能提前说什么。当然，这是最有趣的！

A.A.米尔. Vinits-Pooh 和所有所有所有

所进行的实验可能会让您相信，纸飞机在飞行中的行为方式比投掷的石头或羽毛球要复杂得多、有趣得多。然后始终严格水平地扔它，然后，根据初始速度，它要么几乎垂直地俯冲到地板上，要么飙升到天花板上。提前猜测其飞行轨迹几乎是不可能的，但这并不意味着钱包在空中翻滚的行为无法分析。

纸飞机的飞行问题是非机动飞机失控飞行这一更普遍问题的一部分。这个问题最先提出并决定由俄罗斯科学家、空气动力学创始人N. E. Zhukovsky (1847-1921) 提出并决定取代。在这里，我们将只分析该问题的那个版本，朱可夫斯基本人将其称为“滑翔机问题”。

让一个对称的滑翔机（图6）在空中飞行。三个力作用在其上：重力

$$\vec{F}_T$$，阻力$$\vec{F}_c$$，升力$$\vec{F}_n$$。重力$$\vec{F}_T = m\vec{g}$$的大小是可变的，并且始终垂直向下。速度为$$\vec{v}$$的连接的阻力对应于$$\vec{F}_c = -\alpha \vec{v}$$，即与前一种情况完全相同。根据所谓的，升力位于垂直平面内，并且垂直于速度矢量及其大小。朱可夫斯基定理与速度的对应关系为$$\vec{F}_n = \beta v^2$$。所有三个力都施加在质心处，该质心位于对称机身的垂直平面内。问题是，如果滑翔机从 A₀ 点以初速度 $$\vec{v}_0$$ 与地平线成 φ 角（图 7）发射，飞行轨迹会是什么呢？

轨迹的构建方式与之前完全相同，只是现在要找到总加速度，您将不必添加两个向量，而是三个向量：$$\vec{g}, \vec{a}_c$$和$$\vec{a}_n$$，其中升力引起的加速度$$\vec{a}_c = \vec{F}_n/m$$垂直于速度向量$$\vec{v}$$，并且大小等于($\beta/m)v^2$。为了简化构造，使用图中给出的那些很有用7张$$a_c$$和$$a_n$$对$$\vec{v}$$的依赖关系图。

正如您所看到的，构建滑翔机轨迹虽然很麻烦，但并不复杂。看看我们得到了多么惊人的曲线！我们的滑翔机描述了真正的“死循环”！在这种情况下，只有一个循环，但原则上滑翔机可以描述几个这样的循环，之后它进入特有的“扑动”循环模式：它要么坠落，然后再次获得高度，并逐渐减小这种“下降”的幅度，使其飞行水平并沿着某个倾斜的直线均匀移动。

⟦folio 30⟧

因此，我们构建了一条轨迹并获得了对称滑翔机飞行的最典型特征的描述，尽管事实上不可能将滑翔机问题的精确解（复杂的微分方程组的解）翻译成小学生可以理解的语言。

细心的读者可能会注意到，纸飞机在某些方面与我们考虑的理想滑翔机有所不同。例如，飞机可能不是完全对称的：它的左右机翼上可能有不同的重力、升力和空气阻力。这导致这样的事实：在飞行中，飞机的一个机翼将高于另一个机翼，并且飞机开始向降低的机翼“滑动”，就像在倾斜的平面上一样。

有了这样的横向“滑移”，飞机的机头和机尾就会受到不均等的空气阻力，于是飞机开始绕垂直轴转动，即不会直线向前飞行，而是向右或向左转向。简而言之，除了考虑滑翔机在垂直面的“翻滚”和“扑动”之外，我们还增加了向右或向左的转弯。

由于作用在飞机上的不同类型的力对速度的影响不同，因此转弯半径甚至其方向也将取决于速度。飞机在高速时向右转向和在低速时向左转向的行为特别有趣。发射几架不同类型的飞机，习惯它们的飞行 - 您会发现它们的大部分行为现在对您来说更容易理解。

原则上，使用所描述的方法，可以考虑与飞机改进相关的甚至更复杂的问题。例如，飞机飞行。为此，请记住飞机与滑翔机相同，只是带有发动机。因此，加上滑翔机问题中考虑的力trem，即沿速度矢量方向移动的推力大小为$\vec{F}$的常数，我们将能够构建飞机的飞行路径。如果我们想象一个飞行员坐在这架飞机的驾驶舱里，控制发动机和升降舵（即改变值$\vec{F}$和参数$\beta$），那么我们甚至可以模拟飞机在受控飞行中的上升。通过定期打开和关闭这种飞机的发动机，耐心的读者可以相对容易地确保飞机进入波浪式飞行模式，让人想起山雀、雨燕和其他小鸟的飞行。通过改变该模式下的质量 $m$ 并增加参数 $\alpha$ 和 $\beta$，您可以获得能够非常准确地再现混乱可能性的轨迹。
