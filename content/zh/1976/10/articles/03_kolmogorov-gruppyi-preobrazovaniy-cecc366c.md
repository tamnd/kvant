---
id: 1976-10-kolmogorov-gruppyi-preobrazovaniy-cecc366c
issue: kvant_1976_10
year: 1976
number: "10"
title: 转化组
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2, 4
tag: SM6R
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 73506c8936e1af3f5c0ab14aa8c377655470e794f3287c0281e0225984f28bb4
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/03_kolmogorov-gruppyi-preobrazovaniy-cecc366c.md
source_content_sha256: 73df56adcea2b2207a24ca33db2414d0a7d9c9a27785de4c7066609423d40cd5
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

转化组

我写这篇短文的目的是让 L. Sadovsky 和 ​​M. Arshinov 发表的文章《团体》的内容更容易理解，并将其与新的学校教科书联系起来。

根据新的学校计划，五年级的学生会学到“将集合映射到集合”的概念。六年级时，他们被引入“可逆映射”的概念（许多读者都熟悉的另一个术语«Kvant»，“一对一映射”）。

每个可逆映射都有一个逆映射。例如，围绕点 $O$ 逆时针旋转 $70^\circ$ (图 1) 的旋转 $R_0^{70^\circ}$ 的逆映射是围绕点 $O$ $70^\circ$ 的旋转，但是是顺时针方向。在新几何教科书中，这种旋转用$R_0^{-70^\circ}$表示（绕点$O$旋转负$70^\circ$）。

在下一堂课和最后一堂课中，学生将了解“展示构图”的概念。例如，让我们考虑平面的两次运动，即平面到其自身的两个保持距离的映射。作为第一个位移，我们采用与轴 $x$ 轴对称 $S_x$，作为第二个位移 - 与轴 $y$ 轴对称 $S_y$，垂直于轴 $x$ (图 2)。如果按顺序执行这两个映射：首先是$S_x$，然后是$S_y$，会发生什么？

具有自身对称性 $S_x$ 的点 $P$ 将进入相对于轴 $x$ 对称的点 $P_1$，并且凭借点 $P_1$ 的对称性 $S_y$，它将进入点 $P_2$。上式可以写成等式的形式

$$P_2 = S_y(S_x(P)).$$

另一方面，可以使用中心对称性$Z_0$直接从点$P$获得点$P_2$，其中中心$O$是线$x$和$y$的交点：

$$P_2 = Z_0(P).$$

自己证明对于平面上的任意点 $P$

$$S_y(S_x(P)) = Z_0(P)$$

（如前所述，假设线 $x$ 和 $y$ 垂直并相交于点 $O$）。

⟦folio 4⟧

解决了问题 2 和问题 3，根据变换群的定义，您将确定集合 $G_1$ 具有性质 (1) 和 (2)，即 $G_1$ 是平面的变换群。

可以证明一个更普遍的事实：平面所有位移的集合$G_\Phi$；将任何给定图形$\Phi$映射到其自身上是一个平面变换群。证明并不困难（去做吧！）。群$G_\Phi$称为对称图形群$\Phi$。

从集合$G_1$的构成表中我们可以看出，动作的构成并不总是可以重新定位的：

$$S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ} \neq R_0^{120^\circ} = S_{(OB)} \circ S_{(OA)}.$$

然而，可以证明变换集合$M$的复合运算总是具有结合性：

$$F_3 \circ (F_2 \circ F_1) = (F_3 \circ F_2) \circ F_1$$

（试试这个）。

表1

| $\circ$ | $E$ | $S_{(OA)}$ | $S_{(OB)}$ | $S_{(OC)}$ | $R_0^{120^\circ}$ | $R_0^{-120^\circ}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $E$ | $E \circ E = E$ | $E \circ S_{(OA)} = S_{(OA)}$ | $E \circ S_{(OB)} = S_{(OB)}$ | $E \circ S_{(OC)} = S_{(OC)}$ | $E \circ R_0^{120^\circ} = R_0^{120^\circ}$ | $E \circ R_0^{-120^\circ} = R_0^{-120^\circ}$ |
| $S_{(OA)}$ | $S_{(OA)} \circ E = S_{(OA)}$ | $S_{(OA)} \circ S_{(OA)} = E$ | $S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ}$ | | | |
| $S_{(OB)}$ | | $S_{(OB)} \circ S_{(OA)} = R_0^{120^\circ}$ | | | | |
| $S_{(OC)}$ | | | | | | |
| $R_0^{120^\circ}$ | | | | | | |
| $R_0^{-120^\circ}$ | | | | | | |
