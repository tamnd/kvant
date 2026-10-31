---
id: 1971-5-alimov-vasilev-modenov-vstupitelnyiy-pismennyiy-ekzamen-po-matematike-na-fakultete-vyichislitelnoy-matematiki-i-kibernetiki-mgu-v-1970-godu-0795de16
issue: kvant_1971_5
year: 1971
number: "5"
title: Entrance written exam in mathematics at the Faculty of Computational Mathematics and Cybernetics of Moscow State University in 1970
authors:
  - Алимов Ш. А.
  - Васильев Ф. П.
  - Моденов В. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 47
page_labels: 42-45
tag: JUJ4
lang: en
source: kvant_digital
extraction: vision
content_sha256: b327dae191d8a9e47f63144cd79f796d394c350ae1c5526231692e98bf5fe830
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/11_alimov-vasilev-modenov-vstupitelnyiy-pismennyiy-ekzamen-po-matematike-na-fakultete-vyichislitelnoy-matematiki-i-kibernetiki-mgu-v-1970-godu-0795de16.md
source_content_sha256: b45821f77d0742a3789fc8ee2d1f5539cd1795171fda37cbe318767cfc40bfb9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Entrance written exam in mathematics at the Faculty of Computational Mathematics and Cybernetics of Moscow State University in 1970

Sh. A. Alimov, F. P. Vasiliev, V. P. Modenov

In the last two decades, the importance of mathematical sciences in the general system of human knowledge has increased immeasurably. The main reason for this is the development of computational mathematics. The creation of electronic computers resulted in a real revolution not only in computing capabilities and methods, but also in the very nature of the application of mathematics. It became clear that the quality and quantity of mathematical machines, their application and management systems are an integral part that determines the scientific and technical level of the country.

In this regard, the need arose to train mathematicians of a new specialization. In 1970, a new faculty was opened at the M.V. Lomonosov Moscow State University - the Faculty of Computational Mathematics and Cybernetics. In the same year, the first admission to this faculty was made.

At the written exam in mathematics, each applicant was given a variant of five problems, the solution of which was given 4 hours. To obtain a satisfactory grade, more than two problems had to be solved. An excellent mark was given for correctly solving all five problems.

As an example, let’s look at a typical version made up of tasks offered in a written exam.

Option 0
1. Determine all real values ​​of $a$, for each of which the equation $\cos^4 x - (a-2)\cos^2 x - 3(a+1) = 0$
have a solution, and find all these solutions.
2. Solve the equation
$$\left| 1 + \log \frac{1}{3} x \right| = 3 + \left| 2 - \log \frac{1}{3} x \right|.$$

3. From the city $A$ to the city $B$, located at a distance of 240 km from $A$, an autorus leaves at a speed of 40 km/h. At the same time, from $B$ to $A$ at a constant speed of $v$ km/h, the automaton exits. Half an hour after the car meets, before reaching the city $A$, it turns back and at the same speed towards $B$. Determine all the values ​​of $v$ at which autoroms come to $B$ more equally than autorus.
4. In triangle $ABC$, the length of side $BC$ is equal to the arithmetic mean of the lengths of sides $AB$ and $AC$. Angle $A$ is equal to $\alpha$. Find the angles $B$ and $C$, assuming that $B \geq C$. Investigate at what values ​​of the angle $\alpha$ the problem has a solution.
5. In a right circular cone with vertex $S$, the angle between the height $SO$ and the generator is equal to φ. On the base plane outside the cone, two points $A$ and $B$ are chosen so that the lines $SA$ and $SB$ are mutually perpendicular and form angles with a height $SO$ corresponding to $\alpha$ and $\beta$. Calculate the angle between the generators along which the lateral surface of the cone intersects the triangles $OSA$ and $OSB$.

⟦folio 43⟧

Analysis of problems

1. Note that $0 \leq \cos^2 x \leq 1$ for all $x$. Then, using the substitution $\cos^2 x = t$, the equation is reduced to the system:

$$\begin{cases} t^2 - (a - 2)t - 3(a + 1) = 0, \\ 0 \leq t \leq 1, \end{cases}$$

which has the solution $t = a + 1$ at $-1 \leq a \leq 0$. Hence,

$$\cos^2 x = a + 1,$$

where $-1 \leq a \leq 0$. From here

$$x = \pm \arccos \sqrt{a + 1} + \pi n$$

($n = 0, \pm 1, \pm 2, \dots; -1 \leq a \leq 0$).

Most of those who applied coped with this task. Some of the applicants incorrectly solved equation (1), mistakenly believing that $\arccos (-\sqrt{a + 1}) = \arccos \sqrt{a + 1}$, and lost the solution corresponding to equation $\cos x = -\sqrt{a + 1}$. Some applicants did not indicate all values ​​of $a$ for which a solution to the problem exists.

2. Range of acceptable values ​​of the unknown: $x > 0$. Let's rewrite the equation in the form

$$|1 + t| = 3 + |2 - t|,$$

where $t = \log \frac{1}{3} x$. Sequentially spaced intervals $t \leq -1, -1 < t < 2, t \geq 2$. For $t \geq 2$ we have $1 + t = 3 + t - 2,$

that is, equation (1) is then satisfied effectively for all $t \geq 2$. Next, we verify that equation (1) for $t \leq -1$ and $-1 < t < 2$ has no solution. Thus, equation (1) is all $t \geq 2$. Hence $\log \frac{1}{3} x \geq 2$, and taking into account the domain of definition of finding

$$0 < x \leq 1/9.$$

Some applicants, noticing the same equation (2), wrote that the equation is then validly satisfied for all $t$, without taking into account the constraint $t \geq 2$.

3. Let $t(u)$ be the time of movement of the automaton before the first meeting with the automaton. Since the automaton and the automaton left at the same time, the equality is true

$$40t + vt = 240.$$

(1)

The car surfaces through $t + \frac{1}{2}(u)$ after leaving the city $B$ and therefore returned to $B$ through $2t + 1(u)$. After the first meeting, the bus traveled $vt(\kappa m)$, spending $\frac{vt}{40}(u)$ on this journey. Thus, the Bus needed $t + \frac{vt}{40}(u)$ for the entire journey from $A$ to $B$. In order for the car to arrive at $B$ earlier than the bus, the inequality

$$2t + 1 < t + \frac{vt}{40}.$$

(2)

According to the conditions of the surface automaton, before reaching the city $A$. Since at the moment of the first meeting he is at a distance of $40t(\kappa m)$ from $A$ and during the receiving path $\frac{v}{2}$, then this condition comes to the inequality

$$\frac{v}{2} < 40t.$$

(3)

Combining (1), (2) and (3), we arrive at the system:

$$\begin{cases} 40t + vt = 240, \\ 2t + 1 < t + \frac{vt}{40}, \\ \frac{v}{2} < 40t. \end{cases}$$

From equation (1) we find $t = \frac{240}{v + 40}$ and substitute it into inequalities (2) and (3). By jointly solving the resulting inequalities for $v$, we find $56 < v < 120$.

Most applicants were able to complete equation (1) and inequality (2), although some of them replaced the < sign in (2)

⟦folio 44⟧

to the ≤ sign. The main share of errors was caused by conditions (3), since many applicants did not understand the need for this requirement and limited themselves to only solving the system obtained from (1) and (2).

4. According to the condition

$$BC = \frac{AB + AC}{2}.$$

(1)

Using the sine theorem we find

$$AB = BC \frac{\sin C}{\sin \alpha}, \quad AC = BC \frac{\sin B}{\sin \alpha}$$

and substitute it into (1). We get

$$\sin B + \sin C = 2 \sin \alpha,$$

$$\sin \frac{B + C}{2} \cos \frac{B - C}{2} = \sin \alpha.$$

Because

$$B + C = \pi - \alpha,$$

(2)

then $$\sin \frac{B + C}{2} = \cos \frac{\alpha}{2},$$ and

$$\cos \frac{B - C}{2} = 2 \sin \frac{\alpha}{2}.$$

(3)

Since by condition $B \geq C$ and, in addition, $0 < C < \pi, 0 < B < \pi$, then

$$0 \leq B - C < \pi.$$

(4)

Noting that $$\sin \frac{\alpha}{2} > 0$$, from conditions (2), (3), (4) for determining $B$ and $C$ we have the system:

$$\begin{cases} B - C = 2 \arccos \left(2 \sin \frac{\alpha}{2}\right), \\ B + C = \pi - \alpha. \end{cases}$$

(5)

From (5) there is

$$\begin{cases} B = \frac{\pi - \alpha}{2} + \arccos \left(2 \sin \frac{\alpha}{2}\right), \\ C = \frac{\pi - \alpha}{2} - \arccos \left(2 \sin \frac{\alpha}{2}\right). \end{cases}$$

Thus, for all values ​​of $\alpha$ for which there is a triangle $ABC$ that satisfies all the conditions of the problem, the values ​​of the angles $B$ and $C$ are obtained from formulas (6).

Let us investigate at what values ​​of $\alpha$ the problem has a solution. From (6) it necessarily follows

$$\left| 2 \sin \frac{\alpha}{2} \right| \leq 1.$$

Since $0 < \alpha < \pi$, then hence $0 < \sin \frac{\alpha}{2} \leq \frac{1}{2}$ and, therefore, $0 < \alpha \leq \frac{\pi}{3}$.

For the found values ​​of $\alpha$, the values ​​$A = \alpha, B$ and $C$, determined by formulas (6), are positive and in total equal to $\pi$. To prove this, it is enough to check conditions $C > 0$ or $0 < \alpha \leq \frac{\pi}{3}$ and, as follows from (6), $B \geq C, \alpha + B + C = \pi$.

Let us show that $C > 0$ or, according to (5),

$$\frac{\pi - \alpha}{2} > \arccos \left(2 \sin \frac{\alpha}{2}\right).$$

(7)

Since cos $x$ monotonically kills on the segment $0 \leq x \leq \pi$, and the quantities $\frac{\pi - \alpha}{2}$ and arccos $\left(2 \sin \frac{\alpha}{2}\right)$ belong to this segment, then, calculating the cosine of both sides of inequality (7), we have $$\cos \frac{\pi - \alpha}{2} = \sin \frac{\alpha}{2} < 2 \sin \frac{\alpha}{2}.$$

For $0 < \alpha < \frac{\pi}{3}$ this inequality is true.

Repeating our reasoning in reverse order, we are convinced of the validity of the inequality $C > 0$.

Thus, a triangle $ABC$ with angles $A = \alpha, B \geq C$ and satisfying the conditions of the problem, the values ​​of angles $B$ and $C$ are given by formulas (6), $0 < \alpha \leq \frac{\pi}{3}$.

Many applicants, having received a system for determining $B$ and $C$, were unable to solve it, and some wrote the answer in the form (6), but did not investigate at what values ​​of $\alpha$ the problem has a solution. Some applicants indicated only the case of an equilateral triangle

$$\alpha = B = C = \frac{\pi}{3}.$$

5. Let $x$ be the exclusive angle between the generators $SA_1$ and $SB_1$ along which the lateral surface of the cone intersects the triangles $OSA$ and $OSB$ (see Fig.ok): $\Rightarrow ASB = \frac{\pi}{2}, \Rightarrow OSA = \alpha,$

⟦folio 45⟧

Few applicants managed this task.

Note that formulas (1) and (2) express the relationships between the internal two-faceted angle and the flat angles at the vertex of the trihedral angle. In the general case, if $A, B$ and $C$ are interior two angles, the opposite of the corresponding plane angles $\alpha$, $\beta$ and $\gamma$ of a trihedral angle, then the valid formulas are:

$$\cos A = \frac{\cos \alpha - \cos \beta \cos \gamma}{\sin \beta \sin \gamma},$$

$$\cos B = \frac{\cos \beta - \cos \alpha \cos \gamma}{\sin \alpha \sin \gamma},$$

$$\cos C = \frac{\cos \gamma - \cos \alpha \cos \beta}{\sin \alpha \sin \beta},$$

which are derived in the same way as formula (1). These formulas can be useful in solving many stereometric problems.

In conclusion, we suggest that you independently solve the following option offered in the written exam.

Option 1

1. Determine all real values ​​of $a$ for each of which the equation $\cos^4 x - (a+2)\cos^2 x - (a+3)=0$ has a solution, and find all these solutions.

2. Solve the equation

$$|1 - \log_1 x| + 2 = |3 - \log_1 x|.$$

3. From the city $A$ to the city $B$, located at a distance of 105 km from $A$, an autorus leaves at a constant speed $v$ km/h. 30 minutes later, following him out of $A$ at a speed of 40 km/h, a car leaves, which, having caught up with the bus on the way, turns back and moves at the same speed. Determine all values ​​of $v$ at which the car returns to $A$ later than the car arrives to $B$.

4. In triangle $ABC$, side $BC$ serves as the base of a semicircle whose area is equal to the area of ​​triangle $ABC$. Angle $A$ is equal to $\alpha$. Find the angles $B$ and $C$, assuming that $B \geq C$. Investigate at what values ​​of the angle $\alpha$ the problem has a solution.

5. In a right circular cone with vertex $S$, the angle between generators $SA$ and $SB$ is equal to $\alpha$, and the angle between their projections onto the plane of the base is equal to $\beta$. Calculate the angle between the bissertrices of angles $OSA$ and $OSB$, where point $O$ is the center of the circle that served as the base of the cone.
