---
id: 1983-3-bashmakov-ravnomernoe-dvizhenie-f50c93c8
issue: kvant_1983_3
year: 1983
number: "3"
title: Uniform movement
authors:
  - Башмаков М. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 32
page_labels: 26, 28, 29, 30
tag: CRQ9
lang: en
source: kvant_digital
extraction: vision
content_sha256: fd783cfdea0f24113883c5c19470eecfb0cd320e8e11213bce9251a63b2ecf05
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/09_bashmakov-ravnomernoe-dvizhenie-f50c93c8.md
source_content_sha256: bd779dd65cf82f0e5f7e76e15bd51a68985fc089bccf9c33e7165521b15cb58f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Uniform movement

M. I. BASHMAKOV

Here we will consider a straight line, a non-uniform movement, that is, movement along a fixed straight line with a constant speed. Having chosen the direction on this straight line, we can write the equation of motion in the form

$$s = vt,$$

(1)

where $t$ is the time of movement, $s$ and $v$ are the projections of the displacement and velocity vectors onto the selected axis. Then $s$ and $v$ can belong to both positive and negative values.

Average speed

Formula (1) is often written in the form $v = s/t$. The relation $v = s/t$ also makes sense for uneven movement (movement with variable speed), but in this case $v$ is, by definition, the average speed of movement.

As a warm-up, without making up an equation, answer the following questions:

1. One car walked the first half of the journey at a speed of 30 km/h, and the second at a speed of 50 km/h. The second car walked the whole way at a speed of 40 km/h. Which car took the least time for the entire journey?

2. One car went at a speed of 30 km/h for the first half of the time, and the second at a speed of 50 km/h. The second car moved for the same amount of time as its speed was always 40 km/h. Which car drove a long distance?

(Answers are indicated in the caption to figure 1).

Possible errors when answering questions about uniform motion are associated with the fact that we sometimes bypass the nature of the relationship between two of the quantities $s$, $v$ and $t$ with a fixed third.

For a fixed displacement, the relationship between time and speed is inversely proportional. Moreover, if the movement $2s > 0$ consists of two identical parts $s$, which are traversed at constant (but different) speeds, the first in time $t_1$, the second in time $t_2$, then the average speed $v = 2s/(t_1 + t_2)$ is less than the arithmetic average of the speed on each of the parts, equal to

$$\frac{v_1 + v_2}{2} = \frac{1}{2} \left( \frac{s}{t_1} + \frac{s}{t_2} \right) = \frac{s(t_1 + t_2)}{2t_1t_2}.$$

(Indeed, the difference

$$\frac{s(t_1 + t_2)}{2t_1t_2} - \frac{2s}{t_1 + t_2} = \frac{s(t_1 - t_2)^2}{2t_1t_2(t_1 + t_2)}$$

obviously positive, that is, $v < \frac{v_1 + v_2}{2}$).

So, in problem 1, the average speed of the first car is less than $(30 + +50)/2$ km/h = 40 km/h, which means the second car (travelling at a speed of 40 km/h) will arrive faster.

For a fixed time of movement, the relationship between movement and speed is directly proportional. Therefore, if during two identical periods of time $t$ there is uniform movement with different speeds $v_1$ and $v_2$, then the average speed $v$ along the entire path will be equal to the arithmetic average of the speed in individual sections. (Really,

$$v = \frac{s_1 + s_2}{2t} = \frac{1}{2} \left( \frac{s_1}{t} + \frac{s_2}{t} \right) = \frac{v_1 + v_2}{2}).$$

So, in problem 2, the average speed of the first car is equal to the speed of the second $(50 + 30)/2 = 40)$ and therefore they make the same movement in the same time.

⟦folio 28⟧

him again; In addition to formula (1), you will need a general formula for adding speed:

$$v_k = v_{k\theta} + v_p,$$

asserting that the speed $v_k$ of the catarr in the river is equal to the sum of its speed in standing water $v_{k\theta}$ and the speed of the river $v_p$.

In the problem with the category, we were faced with the superposition of two uniform movements - the movement of the catar and the movement of water in the river. There are many interesting and unexpected challenges associated with this situation. Try solving this problem without calculations:

5. A person walks along an upward escalator in the direction of movement and counts the steps he has climbed. The speed of a person relative to a stationary escalator is $v$. What does the graph of the number $s$ of steps he climbed depend on the speed $v$?

Before drawing a graph, answer the question for yourself: does the function return or kill as the speed increases $v$? A rough sketch of the graph is shown at figure 3.

Let's study the situation in more detail. Let us denote the total number of steps of a (stationary) escalator by $s_0$, the speed of the escalator by $v_3$, the speed of a person ascending by $v$, and the number of steps climbed by a person by $s$. These quantities are related by the relation

$$\frac{s}{v} = \frac{s_0 - s}{v_3}$$

(we equated the time for a person to rise and the time for an escalator to rise).

From here is

$$s = \frac{s_0 v}{v + v_3} = \frac{s_0 + s_0 v_3 - s_0 v_3}{v + v_3} = s_0 - \frac{s_0 v_3}{v + v_3}.$$

Let's draw a graph of the function

$$s = s_0 - \frac{s_0 v_3}{v + v_3},$$

assuming that $v$ can take any (including negative) values. The graph is shown on figure 4.

Looking at the graph (and remembering the conditions of the problem), answer the following questions:

a) What happens to $s$ as $v$ increases without limit?

b) How can we explain that $s$ increases without limit as $v$ approaches $(-v_3)$? Imagine that you stood on the first step of an upward escalator and began to go down at the same speed as the escalator itself. How far will you go? How many steps can you go through?

d) How will the graph of function (2) change if we simultaneously replace $v$ with $kv$ and $v_3$ with $kv_3$?

The answer to the last question - the graph does not change - means that the number of steps climbed depends only on the relative speed of the person and the escalator.

To conclude this section, we propose two more tasks.

6. A man, going up an escalator, counted 100 steps, and moving at twice the speed,

⟦folio 29⟧

counted 120 steps. How many steps are there on a fixed ecalator?

7. A person walking along the tram tracks has to go around a tram every 7 minutes, and every 5 minutes a tram passes towards him. How often do the trams run?

Cusno-linear motion

The simplicity of the formula $s=vt$ is due to the fact that the point on the line in which the moving body is located at the moment of time $t=0$ is chosen as the origin. If we shift the origin by $s_0$ (to the left or right, depending on the sign), the equation of uniform motion will take the form $s=s_0+vt$. (3)

On the graph (Fig. 5), the movement is depicted by a straight line (intersecting the axis $s$ at point $s_0$), the slope of which depends on the speed $v$. A positive slope (acute angle) corresponds to positive velocities (that is, movement in the positive direction of the $s$ axis), negative - movement in the opposite direction.

Formula (3) is useful in cases where we depict coarse-linear motion on a single graph, that is, motion that is uniform (but at different speeds) in adjacent time intervals. On the graph, such a movement is depicted as a broken line, each link of which is specified by a function of type (3) on the corresponding time interval (Fig. 6, $a$). If we depict the speed of such movement as a function of time $v=v(t)$, then we obtain a cousnon-constant (step) function (Fig. 6, $b$). The connection between the graphs of the cousnon-constant velocity function and the cousnon-linear path function is clearly visible in figure 6.

We will now use these messages to solve a more difficult (Olympic) problem, which at first glance has nothing to do with uniform motion.

8. There are 10 numbers written in a circle, the sum of which is zero. We start with one of them, for example $a_1$, and sequentially add them in a circle (say, clockwise).

We get the sums $a_1, a_1+a_2, a_1+a_2+a_3, \dots, a_1+a_2+\dots+a_{10}=0$. Prove that you can choose the starting number in such a way that all these sums are non-negative.

To solve, let’s imagine that $a_1, a_2, \dots, a_{10}$ is the speed of movement over ten equal time intervals, which we take as unity.

Assuming that at the initial moment the path is equal to zero, we obtain that the path $s$ after a unit of time will be equal to $a_1$, after two units - $a_1+a_2$, etc. The graph of such a function is depicted as a broken line, starting and ending on the axis $t$, since by condition $a_1+a_2+\dots+a_{10}=0$ (Fig. 7, $a$). We can assume that the movement repeats periodically - after ten units of time, the speed is again equal to $a_1$, etc. The motion graph will be presented in the form of periodically repeating 10-unit broken lines (Fig. 7, $a$). Starting at a different point means

⟦folio 30⟧

Transfer of the origin of coordinates at one of the vertices of the polyline. What does non-negative sum mean? It means that all the vertices of the broken line lie above the time axis (or on it). First, we chose the starting point arbitrarily (Fig. 7, a). It is now clear that if we move the origin of coordinates to the vertex of the broken line for which the value is the smallest, and start

Mössbauer effect

(For the beginning, see p. 7)

magnetic and electric fields in many connections. This allows us to better understand the mechanism of such interactions and take another step in understanding the internal structure of a solid.

In conclusion, let's look at another interesting application of the Mössbauer effect. It turns out that when photons move against the forces of gravity, their energy decreases, and therefore the frequency of light (wavelength increases), that is, the so-called “red” shift of the spectrum occurs. When photons move “across the field,” “phylote” mixing should occur. Using the Mössbauer effect allows us to carry out an extremely subtle red experiment to determine the change in the energy of γ-photons as they move in a gravitational field.

In the experiment of R. Pound and G. Rebka, the source and absorber - iron $^{57}$Fe - were located in a tower at a height of $H=22,6$ m from each other: the source is at the top, and the absorber with the detector is at the base of the tower. Then they were swapped. As the calculation we describe here shows, in this case the relative change in the frequency of the quanta is $\approx 2,5 \times 10^{-15}$. The Mössbauer effect allows even such a small change in frequency.

It can be said with certainty that among recent scientific discoveries, the Mössbauer effect is one of the most fruitful.
