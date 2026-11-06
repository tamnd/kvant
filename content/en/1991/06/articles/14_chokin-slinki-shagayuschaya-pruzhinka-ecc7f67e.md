---
id: 1991-6-chokin-slinki-shagayuschaya-pruzhinka-ecc7f67e
issue: kvant_1991_6
year: 1991
number: "6"
title: Slinky - walking spring
authors:
  - Чокин Д.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 44
page_last: 46
page_labels: 42-44
lang: en
source: kvant_digital
extraction: vision
content_sha256: 81f32583c59a159778e5b511277b9da8a9b8ffe4f054986fd0c1251d52910374
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/14_chokin-slinki-shagayuschaya-pruzhinka-ecc7f67e.md
source_content_sha256: a759a078355d9fce0082d4b1f74898aa719b1c67114c3fcef977d1772a7790d6
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

Slinky - walking spring

D. Chokin

This article will tell you about one amazing toy, which in America is called a slinky. This is a spring with a very low coefficient of elasticity, the diameter of its coils is from 5 to 10 cm, the number of coils is from 50 to 100. Despite its apparent simplicity, such a spring is difficult to make yourself. You need a special steel that has undergone special heat treatment, only then can you achieve low elasticity of the spring. Namely, this property allows us to carry out

Diar Chokin wrote this article while still a schoolboy (RFS, Alma-Ata). Now he is a student at the Faculty of Physics of Moscow State University.

Fig. 1.

⟦folio 43⟧

---
running_head:
folio:
---

bridges have a linear spring density, which is proportional to the number of turns per unit length, from the distance to the lower end. Let's look at some sections of the spring. Let it fall on the $n$th turn, counting from the lower end of the spring. If the length of this turn is $\Delta x_n$, then

$$\Delta k \Delta x_n = \Delta mng,$$

where $\Delta k$ is the stiffness of one turn, and $\Delta m$ is its mass. Then we find that the average linear density of the $n$-th turn is equal to

$$\lambda_n = \frac{\Delta m}{\Delta x_n} = \frac{\Delta k}{ng},$$

or, considering that there are $N$ turns in the spring and its overall stiffness is $k$, -

$$\lambda_n = \frac{Nk}{ng}.$$

Now let's find the distance from this coil to the lower end of the spring. Since $\Delta x_n = \Delta mng/\Delta k$, the comme distance is equal to

$$x_n = \sum_{i=1}^{n} \frac{\Delta mg}{\Delta k} i = \frac{\Delta mg}{\Delta k} \frac{n(n+1)}{2} \approx \frac{\Delta mgn^2}{2\Delta k} = \frac{Mg}{2k} \frac{n^2}{N^2},$$

where $M$ is the mass of the entire spring. (It is interesting that the total length of the suspended spring $L_0 = Mg/(2k)$ turns out to be half the length that it has

$$x_n$$

Fig. 2.

would be the same weightless spring with a load of mass $M$ suspended at the end.

Compare the obtained expressions for linear density $\lambda_n$ and distance $x_n$, find the relationship between them:

$$\lambda_n = \frac{k}{g} \frac{N}{n} = \sqrt{\frac{Mk}{2gx_n}}.$$

For convenience (we will need this later), we move from a discrete representation of the linear density distribution to a continuous one, taking the limiting case of an infinite number of turns (see Fig. 3):

$$\lambda(x) = \sqrt{\frac{Mk}{2gx}}.$$

Now it’s time to estimate the mass of the spring involved in the movement. We will assume that the required part is equivalent to a freely suspended spring, the length of which is $h$ ($h$ is the height of the step). Then, using the last formula, we estimate the unknown mass:

$$m_0 = \int_0^h \lambda(x) dx = \int_0^h \sqrt{\frac{Mk}{2gx}} dx = \sqrt{\frac{2Mkh}{g}}$$

and the ratio of this mass to the total:

$$\frac{m_0}{M} = \sqrt{\frac{2kh}{Mg}} = \sqrt{\frac{h}{L_0}}.$$

The less part of the spring's mass is involved in movement, the more stable it will move. Therefore, to improve the walking of the spring, it is necessary, as can be seen from the obtained ratio, to reduce the elasticity coefficient, increase the mass of the spring,

⟦folio 44⟧

---
running_head:
folio:
---

launch a bait from not very high steps. And in general, it is better to do this, say, on Jupiter - in order to increase the free fall velocity $g$. To implement the compression, taking $h=10$ cm and $L_0=1$ m, we obtain $m_0/M \approx 0,3$.

To determine the time of one step of a slinky, use Newton's second law. Let the initial speed of the upper turn be $v$. Then
$$v\Delta m = F\Delta t,$$

where $F$ is the tension force of the attachment at the top point, $\Delta m$ is the mass of the attachment, which began to move in time $\Delta t$. If $\lambda_0$ is the linear density of the landing at the place of the beginning of the movement, then $\Delta m = \lambda_0 v\Delta t$, and
$$\lambda_0 v^2 = F.$$

It's obvious that
$$\lambda_0 = \sqrt{\frac{Mk}{2gh}}, \quad a = F = m_0 g = \sqrt{2Mgkh}.$$

For the speed of “unwinding” we obtain
$$v = \sqrt{\frac{F}{\lambda_0}} = \sqrt{2gh}.$$

Let a part of the attachment with mass $\Delta m = \lambda_0 v\Delta t$ be “unwound” during time $\Delta t$. Substituting the values ​​$\lambda_0$ and $v$, we have
$$\Delta t = \frac{\Delta m}{\sqrt{Mk}}.$$

Where do we get the time of one slinky step:

$$T = \sum \Delta t_i = \frac{1}{\sqrt{Mk}} \sum \Delta m_i = \sqrt{\frac{M}{k}} = \sqrt{\frac{2L_0}{g}}.$$

It is interesting that the time of one step does not depend on the height of the step and that this time is of the same order as the period of free oscillations of the step and the time of the body falling from a height of $L_0$. Taking the value of $L_0$ equal to, for example, 1 m, we obtain $T \sim 0,5$ s, which is well confirmed by experiment.

Another, no less important experience with prizing is the modeling of longitudinal mechanical waves. To carry out this experiment, it is necessary to stretch the clamp and compress one of its turns along the axis, thereby making it the beginning of wave propagation. A wave of rolling and stretching will run along the pinch, reflecting from its ends. Interesting and useful experience. It can be shown in school to visualize longitudinal waves and study their properties. For example, it is known that a decrease in the density of the medium leads to an increase in the speed of longitudinal waves. This can be easily verified by experiments with a slinky—it is enough to stretch it a little for the speed of the waves to noticeably increase.

Probably, many more interesting experiments can be carried out with a zipper that has very low rigidity, i.e. with a slinky.
