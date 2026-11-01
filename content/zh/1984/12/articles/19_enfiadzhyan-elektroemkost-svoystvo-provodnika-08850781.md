---
id: 1984-12-enfiadzhyan-elektroemkost-svoystvo-provodnika-08850781
issue: kvant_1984_12
year: 1984
number: "12"
title: 电容量是导体的一种特性
authors:
  - Энфиаджян Р. Л.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 42
page_labels: "40"
tag: ZDOF
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 61ff8e0cd8734ff6c34414990ab38bc1703e455c242dd03ac2f0eb643b1a6666
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/19_enfiadzhyan-elektroemkost-svoystvo-provodnika-08850781.md
source_content_sha256: 2fcdedb4309d3500c08133052bfee67172467cf1d175e873b9ef3ceee692eaa4
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

电是导体的特性

（解决方案���题 F891）

已知赋予导电体的电荷位于其表面。在这种情况下，表面上的电荷分布使得导体内部任意点的电场方向为零。导体是等电位区域（完全位于导体内部的任何表面都是等电位）。林恩的电场方向性重新分布了导体。

带电荷$q$的导体在空间中任意点产生的电场由导体的各个带电部分产生的场的叠加决定。每个这样的部分都有一个电荷$\Delta q_i = \sigma_i \cdot \Delta s_i$，其中$\Delta s_i$是该部分的面积，$\sigma_i$是该部分导体的表面电荷密度。如果导体施加的电荷大于（或小于）$q$ $n$ 倍，会发生什么？导体电导率中任意一点的电荷密度都会变化$n$倍。这意味着电场对单位正电荷所做的基本功在任何区域都会改变 $n$ 倍。在柱中，当将单个正电荷从导体表面移动到无穷远时，作用在单个正电荷上的电力的功将发生变化——即电势状态保持不变。尺寸

$$C = \frac{q}{\varphi}$$

称为远程导体的电容（或简称电容）。在给定电势下可以传递给导体的电荷越多，导体的电容就越大。我们可以说，电容表征了导体在给定电势下积累电荷的能力。对于给定的导体（电容为$C$的导体），有一个电荷值$q$，必须将其传递给导体才能使其电势等于$q$。

电子由导体的公式、其尺寸和环境的电特性唯一决定。

如果导体尺寸减少$n$倍，则导体电容将减少$n$倍。让我们展示一下这个。

让电容为$C$的远端导体$N$带上电荷$q$；导体的电势显然等于$\varphi = q/C$。我们再给售票员一点小费$\Delta q$，

$$\Delta A = -\varphi \cdot \Delta q = -\frac{q}{C} \cdot \Delta q = -\Delta \left( \frac{q^2}{2C} \right).$$

这项工作改变了导体的势能。因此，随着电荷$\Delta q$的加入，导体的势能变化为

$$\Delta U = -\Delta A = \Delta \left( \frac{q^2}{2C} \right).$$

但这意味着具有电容 $C$ 的导体的势能（赋予电荷 $q$）等于

$$U = \frac{q^2}{2C}.$$

我们可以说，该能量是由于导体的带相似电荷的各个部分之间作用的排斥力造成的，并且代表分布在导体表面上的相同精确电荷相互作用的势能。导体的两个基本电导率部分 $N$ (图 1, a) 贡献总势能

$$\Delta U_{12} = k \frac{\Delta q_1 \cdot \Delta q_2}{R_{12}},$$

其中$\Delta q_1$、$\Delta q_2$是这些路段的费用，$R_{12}$是它们之间的距离。

现在让我们转向孤立导体$N'$，其线性尺寸比导体$N$的$u$小$n$倍。关于该导体的电容 $C'$ 可以说什么呢？

令导体$N'$与导体$N$具有相同的电荷$q$。让我们考虑导体 $N'$ (图 1, b) 的两个基本导电部分，类似于导体 $N$ 的部分 1 和 2。这些部分的电荷相互作用对总势能的贡献等于

$$\Delta U_{12}' = k \frac{\Delta q_1' \cdot \Delta q_2'}{R_{12}'}.$$

根据导体$N'$和$N$的线性尺寸的相似性，可以得出截面$I'$和$I'$与2的面积通过关系$\Delta s_1' = \Delta s_1/n^2$、$\Delta s_2' = \Delta s_2/n^2$连接。根据唯一性定理，我们可以得到这些部分的电荷密度：$\sigma_1' = \sigma_1 n^2$，$\sigma_2' = \sigma_2 n^2$。因此$\Delta q_1' = \sigma_1' \cdot \Delta s_1' = \Delta q_1$和$\Delta q_2' = \sigma_2' \cdot \Delta s_2' = \Delta q_2$。从$R_{12}' = R_{12}/n$开始，$\frac{\Delta U_{12}}{R_{12}} = \frac{1}{n}$，即$\Delta U_{12}' = n \cdot \Delta U_{12}$。因此，导体的总势能$N'$大于导体的势能。
