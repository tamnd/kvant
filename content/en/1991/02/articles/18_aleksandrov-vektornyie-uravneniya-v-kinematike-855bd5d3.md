---
id: 1991-2-aleksandrov-vektornyie-uravneniya-v-kinematike-855bd5d3
issue: kvant_1991_2
year: 1991
number: "2"
title: Vector equations in kinematics
authors:
  - Александров Д. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 61
page_last: 66
page_labels: 59-64
lang: en
source: kvant_digital
extraction: vision
content_sha256: 57c5e7cd41a22efaa8d1f643c9e25cb7133a7e4743090e8ff5cc1880c5f3ea41
prompt_sha256: draft-1
translated_from: content/ru/1991/02/articles/18_aleksandrov-vektornyie-uravneniya-v-kinematike-855bd5d3.md
source_content_sha256: 20e77b23eb8165bf5c3691c6daf842ed6ba322bd6fd70121201a6ca5d031f98b
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

Vector
equations
in kinematics

D. ALEXANDROV

As is known, at uniformly accelerated
speed dependence $\vec{v}$
and displacements $\vec{s}$ of the body over time are given by the formulas

$$\vec{v} = \vec{v}_0 + \vec{a} t,$$
$$\vec{s} = \vec{v}_0 t + \frac{\vec{a} t^2}{2},$$

where the initial velocity $\vec{v}_0$ and the rooting of the body $\vec{a}$ are time-independent vectors.

Exercise 1. From formulas (1) and (2) obtain the following expressions:

$$\vec{s} = \frac{\vec{v}_0 + \vec{v}}{2} t,$$
$$v^2 - v_0^2 = 2\vec{a} \cdot \vec{s}$$

(where $\vec{a} \cdot \vec{s}$ is the scalar product).

Exercise 2. Make sure that from formula (2) after differentiation with respect to time, expression (1) is obtained.

Among all possible cases of uniformly accelerated motion, a special place is occupied by the free fall of a body in a gravity field. The solution to most problems on this topic is usually the application of formulas (1), (2) and (3). Using this example, we will look at the basic methods of working with vector equations.

Problem 1. A body thrown from the surface of the earth at an angle α to the horizontal is compacted at a distance L from the point of throw. Determine the time of flight of the body.

Solution 1. Select the coordinate axes X and Y as shown in figure 1, and write the vector

⟦folio 60⟧

---
running_head:
folio:
---

equation (2) in projections onto these axes:
$$x = v_0 \cos \alpha \cdot t,$$
$$y = v_0 \sin \alpha \cdot t - \frac{g t^2}{2}.$$
Let $\tau$ be the required flight time. From the conditions of the problem it follows that for $t = \tau$ the body has coordinates $x = L$ and $y = 0$. Equations (4), written for the moment the body falls, give a system of two equations with two unknowns
$$L = v_0 \cos \alpha \cdot \tau,$$
$$0 = v_0 \sin \alpha \cdot \tau - \frac{g t^2}{2}.$$
From here, eliminating $v_0$, we find
$$\tau = \sqrt{\frac{2 L t g \alpha}{g}}.$$
We solved the problem using a standard method, which can be called “design on the axis”. With its help, a vector equation is a property of a scalar system, which is then solved in an oblique manner. This is exactly how applicants obliquo solve such problems, but when answering even simple questions they are often perplexed. For example, these:
1) What is the difference between systems of equation (4) and (5)?
2) Why, of the three equations (1) - (3), describing uniformly accelerated motion, was the second one chosen for design?
3) Why are the coordinate axes directed this way?
Exercise 3: Before reading the answers, think about how you would answer these questions.

You, of course, have solved problems with numerical data and know that in general you first need to get a letter answer, or, as they say, the answer in general form, and then substitute numbers into it. It is clear that the letter answer contains disproportionately more information than the numerical answer. So, system (4) is in approximately the same relationship to system (5) as the letter answer is to the numerical answer. So, if the first system is always correct, i.e. from it you can find the coordinates of the body at any time, then the second is correct only for the moment the body falls.

Regarding the second question, we note that three quantities $\vec{v}, \vec{s}$ and $t$ that change over time are included in equations (1) - (3). In our problem, the range ($\vec{s}$) is known, and the required time ($t$) is to be found, which is why we chose the equation with the pair $\vec{s}, t$, i.e. the second one.

Exercise 4. How should the conditions of the problem be conveyed so that it can be solved using equation (1) or (3)?

Note that these messages can easily be transferred to problems from any branch of physics. After all, all quantities encountered in the problem can be divided into three groups: known

⟦folio 61⟧

---
running_head:
folio:
---

quantities; unknown quantities that need to be found; unknown quantities that do not need to be found. It is clear that if the formulas do not include the first two types, then the problem cannot be solved, but it is advisable to get rid of the third ones if possible.

As for the third question, you will probably consider it a ghoul and say that, of course, these coordinate axes are the most convenient. In general, in such a problem, thinking about directing the axes somewhere else looks seditious. And this is easy to justify. Indeed, it is natural to consider a method more convenient if it allows one to obtain an answer with fewer calculations. In this sense, the term $\vec{g}t^2/2$ promises the most trouble in control (2) - because of it, the controls turn out to be square. If we do not want to solve two square controls, one axis of the desired one should be directed horizontally. The second one can be directed anywhere, but in order not to introduce new angles when designing, we will direct it vertically. In addition, the flight range and altitude, which generally appear in such problems, are coordinates precisely with this choice of axes. Make sure, don't you? And yet...

Solution 2. Let's direct the $Z$ axis perpendicular to the initial speed $\vec{v}_0$ (Fig. 2). In projections onto this axis, together with control (2), we obtain

$$z = \frac{g \cos \alpha \cdot t^2}{2}.$$

At $t=\tau$ $z=L \sin \alpha$. From here we get the answer:

$$\tau = \sqrt{\frac{2Ltg\alpha}{g}}.$$

This solution became possible because quantities of the third type (according to our classification) $\vec{v}_0$ are vector, and you can get rid of it by remotely selecting the coordinate axis, thereby obtaining one control with one unknown.

However, you can get around without any axes at all...

Solution 3. Formula (2) states that with uniformly accelerated motion, the displacement vector of the body at any time is equal to the sum of the vectors $\vec{v}_0 t$ and $\vec{g}t^2/2$ (Fig. 3). This, by the way, means that the motion of a body thrown at an angle to the horizon consists of uniform and rectilinear motion with a speed of $\vec{v}_0$ and free fall without an initial speed.

Let us “draw” formula (2) for the moment of falling of the body $\tau$ (Fig. 4). From the resulting right triangle we can easily find

$$Ltg\alpha = \frac{g\tau^2}{2},$$

Exercise 5. A body is thrown at an angle $\beta$ to the horizon from the slope of a mountain inclined at an angle $\alpha$ to the horizon. The body is compacted at a distance of $L$ from the point of throw. 1) Our control of body motion (control (2)) in projections on axes 1—5 (Fig. 5) for the moment the body falls onto the mountainside. 2) Choose any two of these controls and show that the remaining ones can be obtained from these two. 3) For each of the received controls, come up with a task in which this control immediately leads to the goal.

Problem 2. On the main fixed inclined plane with an angle

⟦folio 62⟧

---
running_head:
folio:
---

tilt α, the steel ball hits at an angle β to the plane (Fig. 6). At what values ​​of β can the ball return to the point of its first impact on the plane? All collisions are considered elastic.

Let us limit ourselves to one solution—the most reasonable, from our point of view, to this problem.

Solution. The movement of the ball as a whole in this case is not uniformly accelerated due to impacts on the plane. However, in the intervals between impacts, the ball moves under the influence of gravity only and, therefore, at uniform speed. Therefore, for each interval we can use formulas (1) - (3), although for this each time we will have to look for the initial speed.

As is known, during an elastic impact, the component of the ball’s velocity parallel to the plane does not change, and the component perpendicular to the plane only changes sign, also without changing in magnitude. Then, knowing the speed of the ball $\vec{v}_0$ before the first impact, we will find the speed after this impact and substitute it into formula (2) for the first part of uniformly accelerated motion. Then, using formula (1), we find the speed of the ball before the second impact, etc. In other words, formulas (1) - (3) the plane conditions of the next impact completely determine the movement of the ball.

All that remains is to determine the choice of axes. If, according to tradition, we direct the horizontal and vertical axes, then we, of course, will benefit from writing the equation of motion for individual sections (since the projection of the ball on the horizontal axis moves uniformly), but the conditions for the ball’s rebound will become much more complicated. Therefore, we direct the X and Y axes as shown in figure 7, and write equation (2) in projections onto these axes:

$$x = v_{0x}t + \frac{g_x t^2}{2},$$
$$y = v_{0y}t + \frac{g_y t^2}{2},$$

Where
$$v_{0x} = v_0 \cos \beta, \quad v_{0y} = v_0 \sin \beta,$$
$$g_x = -g \sin \alpha, \quad g_y = -g \cos \alpha.$$

The ball will hit the plane a second time when the y coordinate becomes zero (another advantage of the axes we have chosen). Having solved the equation

$$0 = v_{0y} \tau + \frac{g_y \tau^2}{2},$$

we will find that the second escape will happen after a while

$$\tau = \frac{2v_{0y}}{-g_y} = \frac{2v_0 \sin \beta}{g \cos \alpha}.$$

⟦folio 63⟧

---
running_head:
folio:
---

To find the speed of the ball before the second impact (i.e. after time $\tau$), we write equation (1) in projections onto our axes:

$$v_x = v_{0x} + g_x t,$$
$$v_y = v_{0y} + g_y t.$$

Substituting $t = \tau = 2v_{0y} / (-g_y)$, we find that before the second blow there is $v_y = -v_{0y}$ and, therefore, immediately after the blow there is $v_y = v_{0y}$. This result allows you to breathe a sigh of relief - you don’t have to count any further. Since the time between hits depends only on $v_{0y}$, all hits will occur after the same amount of time.

It is now most convenient to answer the question of the problem by drawing graphs of the dependence of the ball’s coordinates on time one below the other (Fig. 8). The ball will return to the same point if at some moments $x = y = 0$, which can only happen if $T = n\tau$, where $n$ is an integer. So,

$$\frac{2v_0 \cos \beta}{g \sin \alpha} = n \frac{2v_0 \sin \beta}{g \cos \alpha},$$

where

$$\text{ctg} \beta = n \text{tg} \alpha.$$

It is interesting that for even and odd $n$ the ball behaves somewhat differently. For even $n$, the average impact of the ball (all impacts $n+1$) will occur perpendicular to the plane, and the ball will return back along the same trajectory. If $n$ is odd, then after half the blow the ball flies vertically upward, falls back and also returns, repeating the entire path taken.

Problem 3. In a region of space where a horizontal electric field with an intense $\vec{E}$ is created, a ball is launched, the mass of which is $m$, and the charge $q$, with a speed $\vec{v}_0$, directed vertically upward. What is the minimum speed of the ball while moving?

Were you surprised by the presence of an “electrical” problem here? No? And rightly so, this task, of course, is directly related to kinematics.

Let's discuss two solutions.

Solution 1. Two constant forces act on a ball in flight: the gravity force $m\vec{g}$ and the electric force $\vec{E}q$ (Fig. 9). According to Newton's second law, the acceleration of the ball is constant and equal to

$$\vec{a} = \frac{\vec{E}q + m\vec{g}}{m}.$$

At the same time

$$a = |\vec{a}| = \frac{\sqrt{(Eq)^2 + (mg)^2}}{m}.$$

figure 10 shows how the ball’s velocity vector changes with time (“formula (1) is drawn”). It is clear that the minimum speed will occur over time

$$t = \frac{v_0 \sin \alpha}{\alpha},$$

and its magnitude will be equal

$$v_{\min} = v_0 \cos \alpha = v_0 \frac{Eq}{\sqrt{(Eq)^2 + (mg)^2}}.$$

If you want similar formulas, you can do it differently.

Solution 2. Let's direct the coordinate axes perpendicular and parallel to the acceleration (Fig. 11) and write equation (1) in projections onto these axes:

⟦folio 64⟧

---
running_head:
folio:
---

If you have a lot of free time and blank paper, make sure that with a different choice of axes the solutions, to put it mildly, do not become easier.

Exercise
for independent work

1. The ball falls freely from a height $H$ onto an inclined plane making an angle $\alpha$ with the horizon (Fig. 12). Find the ratio of the distances between the points at which the bouncing ball touches the inclined plane. Collisions of a ball with a plane are considered to be absolutely elastic.

2. A mortar is fired at objects located on the mountainside. At what distance from the mortar will the mines fall if their flight time is $t$? The angle of inclination of the mountain to the horizon is $\beta$,.minthe shooter is at an angle $\alpha$ to the horizon.

3. An elastic ball is removed from a table of height $H$, imparting a certain horizontal speed to it. At the moment when the ball experiences one of the free elastic collisions with the floor, another ball is horizontally pulled down from the same table, giving it such a speed that it collides with the first ball. At what altitude will the meeting take place?

4. An electron flows into a flat capacitor, parallel to its plates, with a speed of $v_0=2 \cdot 10^6$ m/s. Find the model of the speed of the electron at the moment it leaves the capacitor. The field strength in the capacitor is $E=100$ V/m, the length of the plates is $L=8$ cm, the electron charge is $e=1,6 \cdot 10^{-19}$ C, its mass is $m=9,1 \cdot 10^{-34}$ kg.
