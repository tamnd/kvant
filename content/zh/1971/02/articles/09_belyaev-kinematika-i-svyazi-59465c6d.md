---
id: 1971-2-belyaev-kinematika-i-svyazi-59465c6d
issue: kvant_1971_2
year: 1971
number: "2"
title: 运动学和通信
authors:
  - Беляев С. А.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 48
page_labels: 44-46
tag: X6P0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 57506a3175f28fce2895960c2ed260ea167bf747a5a56c5b12daf3f1b4039280
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/09_belyaev-kinematika-i-svyazi-59465c6d.md
source_content_sha256: ea2685ae56d18911b8f5e6056c2e58c8f1af0c081a8455b7f5cad721f6478607
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

运动学经常考虑绝对刚体的运动，即任何两点之间的距离保持恒定的物体。同时，也有一些方法可以显着地原谅运动学问题的解决。现在我们将熟悉其中之一。

移动时使物体相互接触，相互之间不得滑动。那么两个物体在接触点的速度完全重合（图1）。如果物体之间存在滑动，则只有速度在接触点切线上的投影重合。在这种情况下，至少一个滑动面（图2）存在切线就足够了。

让我们看几个例子。

1. 杆$OA$顺时针旋转

角速度为$\omega$的箭头，从侧面$a$（图3）驱动砖块$ABCD$。求砖块速度 $v$ 与角度 $\alpha$ 的关系。

解决了并且e。棒和砖在$A$点接触。因此，此时砖块和杆在$MN$（$MN \perp \bot OA$）方向上的速度是一致的。因此，

$$v \cos(90^\circ - \alpha) = \omega \cdot OA,$$

或者

$$v = \frac{\omega}{\sin \alpha} \cdot \frac{a}{\mathrm{tg} \alpha} = \frac{\omega a \cos \alpha}{\sin^2 \alpha}.$$

2. 光源 $S$ 距屏幕 $MN$ (图 4) 的距离为 $l$。在初始时刻，高度为$h$的扁平物体开始以$v$的速度从源均匀移动到屏幕。找出屏幕上阴影边缘的运动速度与时间的依赖关系。

⟦folio 45⟧

解决方案。在这个问题中，杆的作用是由射线$SB$扮演的。在点 $A$ 处，光束“触及”极限，在点 $B$ 处 - 与屏幕接触，形成阴影的边界。让我们创建两个方程，连接点 $A$ 和 $B$ 处的速度投影：$\omega \cdot SA = v \cos(\pi - \alpha)$ 是$LK$ 上的投影，$\omega \cdot SB = u \cos \alpha$ 是$MN$ 上的投影。这里$\omega$是光束旋转的角速度。将第二个等式除以第一个等式并考虑到

$$\frac{SB}{SA} = \frac{l}{SL} = \frac{l}{vt} \quad \text{и} \quad tg\alpha = \frac{h}{SC} = \frac{h}{vt},$$

我们得到

$$u = \frac{lh}{vt^2}.$$

现在让给定长度$l$ (图 5) 的杆$AB$任意移动。其两端的速度$\vec{v}_A$和$\vec{v}_B$可以不同，但​​由于杆的长度不变，因此这些速度$v''_A$和$v''_B$的投影必须相等：$v''_A = v''_B$。速度投影 $v'_A$ 和 $v'_B$ 定义了杆的圆周运动，角速度为 $\frac{v'_B - v'_A}{l}$（检查这是最准确的）。

我们来解决两个问题。

3. 杆 $AB$ 将其端部放置在钝角 $\beta$ (图 6) 的两侧。杆的上端以速度 $v$ 沿边 $AO$ 拉动。求点$B$的速度$u$与角度$\alpha$的关系。

解决了并且e。由于杆的长度$AB$不变，因此其两端的速度在杆方向上的投影是相同的：

$$u \cos \alpha = v \cos(\pi - \alpha - \beta),$$

或者

$$u = -\frac{\cos(\alpha + \beta)}{\cos \alpha} v.$$

让我们考虑杆的长度在运动过程中发生变化的情况（例如，“杆”可以用作连接两个给定点的线段，两个给定点之间的距离发生变化）。然后

⟦folio 46⟧

连接杆端部速度过程的对应关系采用以下形式

$$|v_A'' - v_B''| = u,$$

其中$u$是杆长度的变化率。 （这里需要该模块，因为不知道哪个速度更大。）

4. 一艘来自圆形冰山的船被绳索以恒定速度 $v$ 拉动。求船速 $u$ 与角度 $\alpha$ 的关系。

解决方案。在本例中，我们感兴趣的是绳索$AB$的部分。其收缩速度为$v$。绳端$A$和$B$的速度矢量如图7所示。根据上面的说法，我们有

$$v_A \cos \alpha = v_B,$$

或从$v_A = u$、$v_B = v$开始，

$$u = \frac{v}{\cos \alpha}.$$

尝试自己解决类似的问题。

1. 杆$OA$以角速度$\omega$顺时针旋转，驱动半径为$r$（图8）的圆柱体。圆柱体与平面之间没有滑移。求圆柱体速度 $v$ 与角度 $\alpha$ 的关系。

2. 长度为$r$（图 9）的曲柄$AO$以角速度$\omega$旋转，轴$AB$的长度为$l$。如果 $\angle ABO = \alpha$，求该点$B$ 的速度$v$。

3. 先前已绕其轴线解开的球被放置在水平表面上。球在表面上的摩擦系数不为零。在摩擦力的影响下，球改变其初始旋转运动并开始以某种方式沿着表面移动。描述这个运动将如何发生。
