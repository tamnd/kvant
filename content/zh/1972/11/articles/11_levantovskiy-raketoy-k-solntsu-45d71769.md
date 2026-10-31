---
id: 1972-11-levantovskiy-raketoy-k-solntsu-45d71769
issue: kvant_1972_11
year: 1972
number: "11"
title: 火箭飞向太阳
authors:
  - Левантовский В. И.
rubric: osnovnye-stati
page_first: 31
page_last: 31
page_labels: "29"
tag: U7AT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b475686a826305a83f9d81c017cf9d944bf247002c383ba6b23c4993fc8fcdf8
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/11_levantovskiy-raketoy-k-solntsu-45d71769.md
source_content_sha256: 05f1bb51cf56a1a11d7388a0aacea09f044d58ee694350ed66acf1edd17cc7e1
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

乍一看，用火箭撞击太阳就像苹果落到地球一样容易。

在许多致力于太空飞行的科幻故事中，宇宙飞船坠向太阳被描述为太阳系探险家可能遭遇的最可怕的灾难。有时坠落是由于技术故障，有时是由于飞行员在控制船只时出现失误......

与此同时，由于意外原因坠落到太阳上就像一架进行特技飞行的飞机意外坠落到月球上一样是不可能的。事实是，只有消耗更多的能量才能将航天器转移到朝向太阳的下落轨道，这需要太多的燃料。

让我们计算一下运载火箭必须传递给航天器才能到达太阳的速度。如果从无引力的地球发射，火箭只需产生与地球轨道速度相反且大小相等的速度，即 29.77 公里/秒。因此，航天器的以凝胶为中心的速度（相对于太阳的速度）将等于零，并且它将开始沿着直线轨迹落向太阳。

现在考虑重力的影响。令航天器下落时的地心速度（相对于地球的速度）远离地球（“无穷远”），此时地球的吸引力不再错误，等于$v_\infty=29,77$ km/s。让我们写出这种情况的机械能守恒定律：

$$\frac{mv_H^2}{2} - \frac{\gamma Mm}{r_H} = \frac{mv_\infty^2}{2}$$

(1)

（$m$和$M$为航天器与地球对应的质量，$v_H$和$r_H$为被动飞行开始时（加速结束时）距地心的速度和距离，$\gamma$为万有引力常数）。右侧火箭在重力场中没有势能，在无穷远处为零。从这里我们得到

$$v_H^2 = v_\infty^2 + \frac{2\gamma M}{r_H}$$

(2)

但公式右边第二项等于释放速度$v_{\text{OCB}}$（第二逃逸速度）的平方。这可以通过将$v_H=v_{\text{OCB}}$、$v_\infty=0$放入最后一个方程中来验证（根据释放率的定义）。

所以，

$$v_H = \sqrt{v_\infty^2 + v_{\text{OCB}}^2}$$

(3)

取$v_{\text{OCB}}=11,19$ km/s（地球表面的约定值）和$v_\infty=29,77$ km/s，我们发现：$v_H=31,8$ km/s。必须将这个速度传递给火箭，以便它能够到达太阳。该速度有时称为逃逸速度。它几乎是第三逃逸速度（16.67公里/秒）的两倍，这确保了离开太阳系。
