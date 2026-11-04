---
id: 1971-2-ryizhkov-vstupitelnyie-ekzamenyi-po-matematike-v-universitet-druzhbyi-narodov-da23c8c4
issue: kvant_1971_2
year: 1971
number: "2"
title: Entrance exams in mathematics at Peoples' Friendship University
authors:
  - Рыжков В. В.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 53
page_labels: 47-51
tag: VSVR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 76b272c1e8368a8281629233476b469d12f0449a2a35bb4e7826386868747d58
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/10_ryizhkov-vstupitelnyie-ekzamenyi-po-matematike-v-universitet-druzhbyi-narodov-da23c8c4.md
source_content_sha256: 8aecfe720e2f300e2401bb575991f9160c552f4797483c96b103c4f63b19e0d5
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 47⟧

At the Patrice Lumutba University of Other Nations, along with students from Asian, African and Latin American countries, Soviet citizens are also accepted. Since the University has different faculties, it is natural that the nature of the requirements for mathematics in these faculties is different. It is quite clear that higher demands are placed on future physicists and mathematicians than on engineers, economists or chemists. We will talk here about the 1970 Mathematics Entrance Examination for Physics and Mathematics majors.
Here is a version of a written work in mathematics (a prefabricated version, actually composed of problems of various options).

Option 0
1. Find all complete values ​​of z for which $z^2 + (1 + i)z$ takes purely minimal values. Show the corresponding geometric location of the point, use the image of complete numbers on the plane.
2. It is known that the inequality $\log_a(x^2 - 3x) > \log_a(4x - x^2)$ is satisfied at $x = 3\frac{3}{4}$. Solve inequality.
3. The dihedral angle at the lateral edge of a regular quadrangular rectangle is equal to triple the dihedral angle at its base. Find the volume of the straight line if its height is H.
4. Solve the equation
$$tg px + tg qx = tg (p + q)x$$
($p$ and $q$ are known real numbers).

At what values ​​of $p$ and $q$ does it become an identity?
5. With independent group lifting, they are engaged in soil removal. The soil will be completely removed if they all make 8 trips. The soil will also be removed if the first dump truck makes 4 trips, the second - 2, the third - 16. If the first and third dump trucks make the corresponding 6 and 12 trips, then how many trips will the second dump truck have to make?

At first glance, it is clear that only the third of those given here is a technically cumbersome, “classical” competition-type problem. The first task is very simple, but not standard in content. The rest require very small computational costs with a reasonable approach to solving them. In each of them there is, however, some kind of non-privibuant moment that requires elements of an independent approach.

Let's consider solving these problems.

1. The problem has a simple, fairly natural solution. Let's write the complex number z in algebraic form: $z = x + iy$; Then
$$z^2 + (1 + i)z = (x + iy)^2 + (1 + i)(x + iy) = x^2 + 2 ixy - y^2 + x + iy + ix - y = x^2 - y^2 + x - y + i(2xy + x + y).
$$
In order for this number to be purely minimal, it is necessary and sufficient that its real part is equal to zero (of course, zero also applies to purely minimal numbers). We have:
$$x^2 - y^2 + x - y = 0.$$

⟦folio 48⟧

We rewrite this difference in the form
$(x - y)(x + y + 1) = 0$
and we find that the desired locus consists of two straight lines: $x - y = 0, x + y + 1 = 0$, shown in figure 1. If we want to express the answer algebraically, then we write the equation of these lines in the form $y = x$ and $y = -x - 1$. Then the required values ​​of $z$ will be given by two equalities: $z = (1 + i)x$ or $z = x - (x + 1)i$.

Instead of this logical and almost calculation-free solution, the applicants - among those who are generally trying to solve this example - proposed this way. Let's put $z^2 + (1 + i)z = bi$; here on the right $bi$ is the minimum number. Now we solve the quadratic equation:

$$z = \frac{-(1 + i) \pm \sqrt{2i + 4bi}}{2}.$$

In a sense, the solution to this, but what follows is to transform the right side of the equality, which involves extracting the square root of the minimum number; They failed to cope with this decisively, but, as we have seen, with a more successful approach to the task this was not required.

2. The example is very simple, but you need to read the conditions carefully and think a little. Given the condition: unequal

```markdown
венство выполено при $x = 3\frac{3}{4}$; для чего оно дано? Подставим $x = 3\frac{3}{4}$ в неравенство, получим
$$\log_a \frac{45}{16} > \log_a \frac{15}{16}.$$
Отсюда вывод: $a > 1$. В этом весь смысл данного условия, оно позволяет сразу установить, что $a > 1$. Тепер мы приходим к неравенству $x^2 - 3x > 4x - x^2$; к нему надо присоединить неравенство, характеризующее ОДЗ: $4x - x^2 > 0$. Заметим, что писать еще и неравенство $x^2 - 3x > 0$ незачем, так как оно уже завершено выполняется в силу написанных двух неравенств. Итак, получается система двух неравенств
$$2x^2 - 7x > 0, \quad 4x - x^2 > 0.$$
Первое из них выполняется при $x < 0$ и $x > 3\frac{1}{2}$, второе — при $0 < x < 4$; решением служит инвервал
$$3\frac{1}{2} < x < 4.$$
Эта задача, в общем, совершенное стандартная, дополнительное условие в ней при правильном понимании не условияет, а упрощает задачу. Многие абитриенты решили примерdo конца, но в большинстве случаеев очень его запутали, а некоторые так и уtonули в вычислениях. Именно, игнорируя данное в задаче условия о значении $x = 3\frac{3}{4}$, они рассуждают «по стандарту»: либо $a < 1$, либо $a > 1$. Потом писали полностью условия, определяющие ОДЗ, и получали две системы неравенств:
$$\begin{cases} x^2 - 3x > 0, \\ 4x - x^2 > 0, \\ x^2 - 3x < 4x - x^2 \end{cases}$$
Вместо одной системы из двух неравенств, приходилось решать две системы из трех неравенств каждой и лишь потом учитывать дополнительно-
```

⟦folio 49⟧

telial condition. Here you can already get lost.

3. The problem on stereometry is standard, but quite difficult. The point is not only that problems on dihedral angles are not always solved in a decreasing way, but also that the conditions do not give a single angular value, but only the correspondence between two such values. In general, a regular quadrangular paramida is determined by one linear and one angular dimensions. The linear dimension dan is the height of the paramid, and together the angular dimension indicates the correspondence between the two angles.

Many applicants have solved this problem. In other words, some of them did not understand the essence of the task at all. Having designated one of the dihedral angles as $\alpha$ and the other as $3\alpha$, they were able to express the volume through the angle $\alpha$, without thinking that this angle was determined by the conditions of the problem.

Here is one possible solution to the problem. On figure 2, $\alpha$ denotes the dihedral angle at the edge of the base, and $\beta$ denotes the dihedral angle at the lateral edge of the paramid, so $BK$ and $DK$ are the heights of the lateral faces of the paramid drawn from the vertices of the base. Under condition $\beta = 3\alpha$.

For convenience, we also introduce the notation $\gamma$ for the plane angle at the base of the paramid; by $a$ we denote the side of the base, and by $h$ the height of the side face, that is, the apothem of the paramid.

A correspondence is immediately found between the angles $\alpha$ and $\gamma$: from the triangle $SOL$ we have $\frac{a}{2h} = \cos \alpha$; the same relation in the triangle $SLB$ is expressed as follows: $\frac{a}{2h} = \text{ctg} \gamma$.

Thus, $\text{ctg} \gamma = \cos \alpha$. Since when considering the triangle $ABK$ we need sin $\gamma$, we express this sine through the function of the angle $\alpha$:

$$\sin \gamma = \frac{1}{\sqrt{1 + \text{ctg}^2} \gamma} = \frac{1}{\sqrt{1 + \cos^2 \alpha}}.$$

Now from the triangle $ABK$ we have $BK = a \sin \gamma$ and from the triangle $BKD$ $BK = \frac{a}{\sqrt{2} \sin \frac{\beta}{2}}$, whence $\sqrt{2} \sin \frac{\beta}{2} = \frac{1}{\sin \gamma}$ or $\sqrt{2} \sin \frac{\beta}{2} = \sqrt{1 + \cos^2 \alpha}$.

Hence $2 \sin^2 \frac{\beta}{2} = 1 + \cos^2 \alpha$ or $1 - 2 \sin^2 \frac{\beta}{2} = -\cos^2 \alpha$, that is, definitively

$$\cos \beta = -\cos^2 \alpha.$$

Such an interesting correspondence between the quadrangular paramid. In our problem $\beta = 3\alpha$, and therefore to find the angle $\alpha$ we obtain the equation

$$\cos 3\alpha = -\cos^2 \alpha.$$

It can be solved using the standard method. Expressing cos $3\alpha$ in terms of the angle function $\alpha$

$$\cos 3\alpha = 4 \cos^3 \alpha - 3 \cos \alpha,$$

we get

$$4 \cos^3 \alpha - 3 \cos \alpha = -\cos^2 \alpha.$$

Assuming for brevity cos $\alpha = u$, we arrive at the following equation:

$$4 u^3 + u^2 - 3 u = 0.$$

⟦folio 50⟧

The root $u_1 = 0$ has no meaning in our problem; what remains is a quadratic equation

$$4 u^2 + u - 3 = 0$$

with roots $u_2 = -1$ and $u_3 = \frac{3}{4}$, of which we are only interested in the latter. So, $\cos \alpha = \frac{3}{4}$; it is convenient to find such $\sin \alpha = \frac{\sqrt{7}}{4}$ and $\text{ctg} \alpha = \frac{3}{\sqrt{7}}$.

Now it remains to express the volume of the primid; we find $\frac{a}{2} = H \text{ctg} \alpha$ or $a = \frac{6H}{\sqrt{7}}$. Hence,

$$V = \frac{1}{3} Ha^2 = \frac{12}{7} H^3.$$

4. The solution equation is quite simple:

$$\text{tg}(p + q) x = \frac{\text{tg} px + \text{tg} qx}{1 - \text{tg} px \text{tg} qx}.$$

This shows that either $\text{tg} px + \text{tg} qx = 0$ or $\text{tg} px \cdot \text{tg} qx = 0$. Thus, the equation is satisfied in each of the three cases:

a) $\text{tg} px + \text{tg} qx = 0$, which is equivalent to $\sin (p + q) x = 0$; 6) $\text{tg} px = 0$; 8) $\text{tg} qx = 0$. Therefore it goes to the same place if $p + q = 0$, or $p = 0$, or $q = 0$; if none of these three equalities is satisfied, then the equation satisfies three series of solutions:

$$x = \frac{k\pi}{p + q}, \quad x = \frac{k\pi}{p}, \quad x = \frac{k\pi}{q}$$

($k = 0, \pm 1, \pm 2, \dots$).

When solving the problem in detail, it would be necessary to find out whether some of the indicated solutions could turn out to be in the form of these cases, since only a few of those solving the problem clearly indicated all three cases of addressing the same place.

5. Much of the problem was solved, but often in a cumbersome or illogical way. Let each dump truck remove $\frac{1}{x}, \frac{1}{y}, \frac{1}{z}$ part of the total soil in one trip, respectively. Moreover

$$\text{obщее количество ручента за единицу. Тогда условие задачи перешдает в виде системы}$$

$$\left\{ \frac{8}{x} + \frac{8}{y} + \frac{8}{z} = 1, \quad \frac{4}{x} + \frac{2}{y} + \frac{16}{z} = 1, \quad \frac{6}{x} + \frac{p}{y} + \frac{12}{z} = 1. \right.$$

Here the number of trips of the second dump truck $p$ is unknown; $x, y, z$ is also unknown, which, however, we do not need to determine. With a certain amount of mathematical observation, we can agree to add the first two equalities by division and divide both sides of the resulting equation by 2. We arrive at the equality

$$\frac{6}{x} + \frac{5}{y} + \frac{12}{z} = 1,$$

from comparing which with the third equation of our system we find the number of flights equal to the heels: $p = 5$.

An analysis of the applicants' work shows that the level of technology among different applicants was, of course, different. But this is not only due to the lack of technology among some applicants, but also to the fact that many formally prepared applicants are accustomed to the standard and do not think about the conditions of the task. The slightest deviation of these conditions from the attractive ones, even in the direction of simplification, leads to confusion and, as a consequence, to mistakes and irrational decisions.

We provide options for written work for independent solution (these two options are “real”, not prefabricated).

Option 1

1. It is known that one of the real roots of the equation $x^3 - 5x^2 + px + 8 = 0$ is equal to the equational root of the other one. Find $p$ and all roots of the equation.

2. Find all values ​​of $a$ for which the inequality

$$\log_{2a+1}(2x - 1) + \log_a(x + 3) < 0$$

simultaneously executed for $x = 1$ and $x = 4$.

3. Solve inequality

$$\sin x \cdot \cos 2x \cdot \sin 3x \geq 0.$$

⟦folio 51⟧

---
running_head:
folio:
---

4. The surface of a sphere inscribed in a cone, the lateral surface of the cone, and the complete surface of the cone form a geometric progression. Find the volume of a cone if the radius of the ball inscribed in it is $R$.

5. In a three-room apartment, the length of the first room is equal to the length of the second, the width of the second room is equal to the width of the third, and the diagonal of the floor of the first room is the same as in the third. The areas of the rooms are respectively $a$, $b$, $c$. Find the length and width of each room.

Option 2

1. Solve system of equations
$$\begin{cases} xy^2z^3 = 108. \\ x^2y^3z = 24, \\ x^3yz^2 = 18. \end{cases}$$

2. Solve inequality
$$\log \frac{1}{2}x - 2\log \frac{1}{2}x^2 - \frac{1}{x^3} > 0.$$

3. A hemisphere is inscribed in a truncated cone, the volume of which is $\frac{6}{7}$ of the volume of the truncated cone. Find the ratio of the lateral surface of the cone to the spherical surface of the hemisphere.

4. For what values ​​of $\alpha$ does inequality $x^2(1 + \sin \alpha) - 2x\cos \alpha + 2\sin \alpha \geq 1$ hold for all values ​​of $x$?

5. The volume of a rectangular parallelepiped is $V$. If all its edges are increased by $a$, then the volume will be equal to $V_1$, and if they are shortened by $a$, then the volume will be equal to $V_2$. Find the length of the diagonal of the parallelepiped.

Assignment from other options

1. Solve inequality
$$\log_2\log_8x > \log_8\log_2x.$$
2. Find values ​​of $tg(x + y)$ if $(3\cos x + 4\sin x)(5\sin y + 12\cos y) = 65.$
3. Equation with real coefficients
$$x^3 + px^2 + 2px + q = 0$$
has root $x_1 = 1 + i$. Find all the roots of the equation.
