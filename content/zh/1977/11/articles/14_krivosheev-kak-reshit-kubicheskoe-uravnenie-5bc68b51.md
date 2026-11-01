---
id: 1977-11-krivosheev-kak-reshit-kubicheskoe-uravnenie-5bc68b51
issue: kvant_1977_11
year: 1977
number: "11"
title: 如何解三次方程？
authors:
  - Кривошеев В.
rubric: smes
page_first: 54
page_last: 54
page_labels: "52"
tag: LIYK
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 59ed5fb08ae278d15c79f0f303864d448aaa5189a4489a1446f1e9f40cb2f654
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/14_krivosheev-kak-reshit-kubicheskoe-uravnenie-5bc68b51.md
source_content_sha256: 8bf4a37c530b83e7c10614a9ed51941b74b7f9d38e23584c49fea5bdca118156
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

F444。质量为 M 的重箱滚下滚轮，形成斜面 (图 6)。滚子之间的距离为 l，半径为 r，质量为 m。平面与地平线的夹角等于α。如果已知盒子已建成，请求其移动速度。假设滚轮是空心的，其壁厚为 d << r。

图 6.

当威兹箱沿着其下方的斜面移动时，滚筒开始移动并开始展开。盒子以恒定速度移动的事实意味着滚轮作用在其上的阻力$\vec{F} = -M\vec{g} \sin \alpha$。

假设盒子以速度 $\vec{v}$ 移动，并且其长度足够大，以便它有时间将滚轮旋转到线速度 $u = |\vec{v}|$。由于箱体侧面作用于其上的盲摩擦$\vec{f}$，滚轮展开，直到其线速度等于$|\vec{v}|$。此后，该滚轮和盒子之间的摩擦力消失。

从对称信息可以清楚地看出，滚子上摩擦力的作用等于在与滚子边缘相切的任意点处施加到滚子上并与滚子一起“旋转”的力$|\vec{f}|$的相同绝对值的作用。由于作用在滚轮上的力绝对值恒定，因此力$|\vec{f}|$作用下滚轮的旋转线速度随时间按线性规律变化。让 Roll 在时间 $\tau$ 内旋转至线速度 $u = |\vec{v}|$。力$\vec{f}$做功$|\vec{f}||\vec{v}| \tau/2$（罗利卡的平均速度为$|\vec{v}|/2$，设力作用点经过的距离为$|\vec{v}| \tau/2$）。这个功等于罗利卡的动能：

$$\frac{|\vec{f}| |\vec{v}| \tau}{2} = \frac{m |\vec{v}|^2}{2}.$$

由于滚筒在$\tau$时间内放卷至线速度$|\vec{v}|$，因此箱体下方始终有$N = |\vec{v}| \tau/l$个滚筒，其线速度小于$|\vec{v}|$。这些滚子作用在盒子上的摩擦力等于

$$|\vec{F}| = N |\vec{f}| = \frac{|\vec{v}| \tau}{l} |\vec{f}| = M |\vec{g}| \sin \alpha.$$

从（1）我们有：$|\vec{v}| \tau |\vec{f}| = m |\vec{v}|^2$。将这个式子代入式(2)，可得：

$$\frac{m |\vec{v}|^2}{l} = M |\vec{g}| \sin \alpha.$$

从这里

$$|\vec{v}| = \sqrt{\frac{M}{m} |\vec{g}| l \sin \alpha}$$

T·佩特洛娃

如何解三次方程？

你们中的许多人都读过有关三次方程解的戏剧性故事（参见«Kvant»，1976 年，第 9 期）。现代代数符号现在甚至可以让小学生完成这项任务，但在 17 世纪，即使是顶尖的数学家也无法做到这一点。这是我们的读者 V. Krivo Sheev (Cherkassy) 提供的一种优雅的方法。

众所周知，任何三次方程都可以简化为以下形式

$$y^3 + by + c = 0.$$

偶然我发现了以下替代方法来解决这个问题。

a) 设 $b > 0$。让我们把

$$y = \sqrt{\frac{b}{3}} \left( z - \frac{1}{z} \right),$$

我们得到（容易检查）方程

$$\frac{b}{3} \sqrt{\frac{b}{3}} \left( z^3 - \frac{1}{z^3} \right) + c = 0.$$

接下来我们输入$z^3 = t$，化简到公分母后我们得到一个二次相对$t$方程。

6) 让$b < 0$。让我们把

$$y = \sqrt{\frac{b}{3}} \left( z + \frac{1}{z} \right)$$

并且进一步类似于a)点。
