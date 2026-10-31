---
id: 1975-3-resheniya-zadach-m273-m279-f285-f290-e3d146e5
issue: kvant_1975_3
year: 1975
number: "3"
title: Solutions to problems M273—M279; F285—F290
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 50
page_last: 60
page_labels: 48-58
tag: 74GG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 21219ad4b213e4f17b69acc9bdf9d80767022a43c56eeaa46c95c13cec0141f6
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/13_resheniya-zadach-m273-m279-f285-f290-e3d146e5.md
source_content_sha256: 9f857def718b22d059e026d49054091b997dfe800d0307e5c575a7c41e3c2d7b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

M273. On the segment $0 \leq x \leq 1$ the function $f$ is given. It is known that this function is non-negative and $f(1) = 1$. Moreover, for any two numbers $x_1$ and $x_2$ the maximum that $x_1 \geq 0$, $x_2 \geq 0$ and $x_1 + x_2 \leq 1$ satisfies the inequality
$$f(x_1 + x_2) \geq f(x_1) + f(x_2).$$
a) Prove that whatever function $f$ is that satisfies the above conditions, for all $x$ the inequality $f(x) \leq 2x$ will be satisfied.
6) Is it true that for all $x$ $f(x) \leq 1,9x$?

M274. Find the smallest number of the form
a) $|11^k - 5^l|$;
b) $|36^k - 5^l|$;
c) $|53^k - 37^l|$,
where $k$ and $l$ are natural numbers.

a) A function that satisfies the conditions of the problem returns multitone. Indeed, if $x_2 \geq x_1$ and $x_2 \leq 1$, then $f(x_2) \geq f(x_1) + f(x_2 - x_1)$ and $f(x_2 - x_1) \geq 0$; hence $f(x_2) \geq f(x_1)$. Therefore, if $\frac{1}{2} < x \leq 1$, since $f(1) = 1$, we have
$$f(x) \leq 1 \leq 2x.$$
Let now $0 < x \leq \frac{1}{2}$. Let's take a natural $n$ such that $\frac{1}{2} < nx \leq 1$ (it is clear that this can always be done). It is easy to prove (by induction) that if $x \geq 0$ and $nx \leq 1$, then $f(nx) \geq nf(x)$. For $\frac{1}{2} < nx \leq 1$ it has already been proven that $f(nx) \leq 2 \cdot nx$.
Posny $nf(x) \leq f(nx) \leq 2 \cdot nx$, opening $f(x) \leq 2x$ and for $0 < x \leq \frac{1}{2}$.
All that remains is to find out what will happen at zero. Let's take $0 < x_1 \leq 1$; Then
$$f(x_1) = f(0 + x_1) \geq f(0) + f(x_1).$$
But by definition, $f(0) \geq 0$ means $f(0) = 0$.
6) Answer: no, that's not true.
Let's give an example. Let's define the function as follows:
$$f(x) = \begin{cases} 1, & \frac{1}{2} < x \leq 1, \\ 0, & 0 \leq x \leq \frac{1}{2}. \end{cases}$$
If $1 \geq x_1 \geq x_2 \geq 0$ and $x_1 + x_2 \leq 1$, then $x_2 \leq \frac{1}{2}$ and $f(x_2) = 0$.
Consequently, $f(x_1 + x_2) \geq f(x_1) + f(x_2)$ and we consider the function satisfies the requirements of the problem.
At the same time
$$f\left(\frac{51}{100}\right) = 1 > 1,9 \cdot \frac{51}{100}.$$

◆
a) If $11^k > 5^l$, then the number $|11^k - 5^l|$ is 6; if $11^k < 5^l$, then by 4.
It is easy to see that $|11^k - 5^l| = 4$ for $l = 3$, $k = 2$, that is, 4 is the smallest number of the form $|11^k - 5^l|$.
6) If $36^k > 5^l$, then the number $|36^k - 5^l|$ is 1; if $36^k < 5^l$, then by 9.
For $k = 1$, $l = 2$ we have $|36^k - 5^l| = 11$.
Let us prove that 11 is the smallest number of this type. To do this, we need to show that $|36^k - 5^l|$ cannot equal either 1 or 9.

⟦folio 49⟧

1) If $36^k - 5^l = 1$, then $(6^k - 1)(6^k + 1) = 5^l$.
No number $6^k + 1$ cannot be a power of 5, since it ends in 7 (at $k > 0$).

2) If $5^l - 36^k = 9$, then $5^l = 9 + 36^k$, which also cannot happen, since the right side of $k > 0$ is divisible by 9, but the left is not. This means that 11 is the smallest number of the form $|36^k - 5^l|$.

c) The number $N = |53^k - 37^l|$ can end with any even digit. In addition, since $|53^k - 37^l| = |(52 + 1)^k - (36 + 1)^l| = |(4.13 + 1)^k - (4.9 + 1)^l|$, then $N$ is divisible by 4. For $k = l = 1$ $N = 53 - 37 = 16$. Let us prove that 16 is the smallest number of the form $|53^k - 37^l|$. To do this, it is enough to show that $N$ cannot equal 4, 8 and 12 ($N$, very clearly, does not equal 0, since 53 and 37 are coprime).

We have $N = |53^k - 37^l| = |(54 - 1)^k - (36 + 1)^l| = |(6.9 - 1)^k - (4.9 + 1)^l|$.

Pozny, when dividing $N$ by 9, the remainder can only be 0.2 and - 2 (that is, 7). But neither 4, nor 8, nor 12 give these remainders when divided by 9.

I. N. Klimova

M275. a) On the data plane of $n$ vectors, the length of each comorbix is ​​1. The sum of all $n$ vectors is equal to the zero vector. Prove that the vectors can be measured so that for all $k = 1, 2, \dots, n$ the following conditions are satisfied: the sum of the first $k$ vectors has a length of no more than 3.
b) Prove a similar statement for $n$ vectors with sum 0, the length of each comorbix is ​​1. b) Can the number 3 in problem a) be replaced by less? Construct an incriminating assessment also in task 6).

Let us first consider the “one-dimensional” problem.
Lemma 1. Let there be given $n$ numbers such that each modulus does not exceed 1, and the sum of all is equal to 0. Then they can be measured so that for any $i \leq n$ the sum of the first $i$ of them is at most 1 in modulus.

Let us indicate one of the filling methods: $a_1, \dots, a_k$ and non-positive: $b_1, \dots, b_{n-k}$. Let's put $c_1 = a_1, c_2 = b_1$. If $c_1 + c_2 < 0$, put $c_3 = a_2$; if $c_1 + c_2 \geq 0$, put $c_3 = b_2$. And in general, if $c_1, \dots, c_l$ have already been selected, then for $c_1 + \dots + c_l < 0$ use the next positive number for $c_{l+1}$, and for $c_1 + \dots + c_l \geq 0$ for the next positive number.

Based on Lemma 1, we solve problem M275 6). Let us apply all these vectors to some point $O$ and choose a direct coordinate system $Oxy$ so that the sum $s$ of all vectors looking up ($v > 0$) is directed exactly along the axis $y$. (We will discuss the question of how to construct such a coordinate system later.) The remaining vectors (smogrizia down) then give a total of $s$.

First, let's measure the vectors looking up. We denote their components along the $x$ axis by $p_1, \dots, p_k$. Since the component $s$ along the axis $x$ is equal to 0, then $p_1 + \dots + p_k = 0$. In modulus, each of the numbers $p_1, \dots, p_k$ does not exceed 1. By Lemma 1, we measure the numbers $p_1, \dots, p_k$ so that for any $i \leq k$ the sum of the first $i$ of them is at most 1 in absolute value. Thus, we measure the upward-looking vectors, so that for any $i \leq k$ the sum of the first $i$ of them will lie in the strip $|x| \leq 1$ (Fig. 1). The components of these vectors along the $y$ axis (in the chosen order) will be denoted by $a_1, \dots, a_k$.

We also measure the vectors looking up, and call their components along the $y$ axis $b_1, \dots, b_{n-k}$.

Now let's move on to the continuous numbering of all these vectors. Each of the numbers $a_1, \dots, a_k$ is contained between 0 and 1, each of the numbers $b_1, \dots, b_{n-k}$ is between 0 and - 1, and their sum is 0. Without changing the relative order of the numbers $a_1, \dots, a_k$ and the relative order of the numbers $b_1, \dots, b_{n-k}$, we write them according to Lemma 1 as a set $c_1, \dots, c_n$ so that for any $i \leq n$ we obtain the inequality $|c_1 + \dots + c_i| \leq 1$. Thus, we measure all these vectors so that for any $i \leq n$ the sum of the first $i$ of them will be located

⟦folio 50⟧

lies in the strip $|y| \leq 1$. Moreover (due to the preliminary numbering of the numbers $a_1, \dots, a_k$ and $b_1, \dots, b_{n-k}$) any such sum lies in the strip $|x| \leq 2$.

So, we have proven that $n$ of given vectors can be created through $v_1, \dots, v_n$ so that for any $i \leq n$ the sum $v_1 + \dots + v_i$ lies in the rectangle $|x| \leq 2$, $|y| \leq 1$, and therefore $|v_1 + \dots + v_i| \leq \sqrt{5}$.

Let us also note 1. It remains to justify the construction of the system $Oxy$.

Let us divide all these vectors into two classes; the sum of vectors of the first class will be denoted by $s$ (then the sum of vectors of the second class will be $s$). There are only $2^n$ all possible partitions into two classes (the important thing is that there is a finite number of them). Let us choose from them the one for which $|s|$ takes the most value, and the direction of this particular vector $s$ will be taken as the direction of the $y$ axis.

(Make sure that the constructed system $Oxy$ has the property we need.)

Note that it is not e2. From the above construction of the $y$ axis it is clear that none of these vectors are perpendicular to it, therefore, we correctly spoke about vectors “looking down” (instead of the more careful “not up”).

In the space of a given $n$ vectors, such that each modulo does not exceed 1, and the sum of all is equal to 0. Prove that they can be numbered so that for any $i \leq n$ the sum of the first $i$ of them has a length less than $C$, where: a) $C = \sqrt{21}, 6)$* $C = \sqrt{20,5}$.

Let's move on to problem $M275$ a).

Lemma 2. Let each of the vectors $e_1, \dots, e_r$ have length 1, length $e_0$ at most 1, and $e_0 + e_1 + \dots + e_r = 0$. Then among the vectors $e_1, \dots, e_r$ there is either one vector $e_i$, or a pair of vectors $e_j$ and $e_k$, which in sum with $e_0$ give a vector $e$ of length no more than 1 (either $|e_0 + e_i| \leq 1$ or $|e_0 + e_j + e_k| \leq 1$). In the second case $|e_0 + e_j| < \sqrt{2}$.

Proof. Let us draw two rays, $OA$ and $OB$, forming angles with $e_0$ in $120^\circ$ (Fig. 2). If among $e_1, \dots, e_r$ there is a vector lying inside (or on the sides) $AOB$, then we will take it as $e_i$.

Let there be no such vector among $e_1, \dots, e_r$. Let us then draw a straight line $CD \perp e_0$ through the point $O$. Among the vectors $e_1, \dots, e_r$ there turns out to be a vector lying inside $AOC$ or inside $BOD$ (otherwise condition $e_0 + e_1 + \dots + e_r = 0$ is not satisfied). For the sake of definition, let at least one of the vectors $e_1, \dots, e_r$ lie inside $BOD$. The closest of these vectors to $OB$ is called $e_j$, and the ray directed opposite to it is denoted by $OE$. At least one of the vectors $e_1, \dots, e_r$ lies inside $AOE$ (otherwise condition $e_0 + e_1 + \dots + e_r = 0$ is not satisfied again). The closest to $OA$ of these vectors is called $e_k$, the angles $e_j$ and $e_k$ denote both the $e_j$ and $e_k$ angles, greater than 60°. This means that the vector $e_j + e_k$ lies inside $AOB$, and therefore $|e_0 + e_j + e_k| \leq 1$. At the same time $|e_0 + e_j| < \sqrt{2}$.

It immediately follows from Lemma 2 that in problem $M275$ a) the vectors can be numbered so that for any $k \leq n$ the sum of the first $k$ vectors has length $\sqrt{2}$ (proof by induction on $n$).

Complicating the proof, we can further improve the estimate in problem $M275$ a), namely, replace $\sqrt{2}$ with $\frac{\sqrt{5}}{2}$.

In the puzzle 2. Obtain in the problem $M275$ a) a score of $\frac{\sqrt{5}}{2}$. Prove that it is no longer possible to improve this estimate, that is,

⟦folio 51⟧

Fig. 3.

**M276.** Given a square ABCD. Points P and Q lie on sides AB and BC, respectively, with $|BP| = |BQ|$. The points H are the base of the perpendicular dropped from point B onto the segment PC. Prove that the huelol DHQ is direct.

Fig. 4.

**M277.** Several red and several synchro lights are specified. Some of them are connected by segments. A lobe soil is “special” if the most watered of the lobes connected to it have a color different from its color. If there is at least one special mocka, then any special mocka is selected and repainted in a different color. Prove that after a finite number of shads there will not be a single special lobe left.

**M278. a) Each of the sides of the convex hexacell has a length greater than 1. Is it always found in it? Show that for any positive $C < \frac{\sqrt{5}}{2}$ it is possible to indicate on the plane $n$ unit vectors with sum 0, such that, as if denoted by $v_1, \dots, v_n$, for some $k$ the inequality $|v_1 + \dots + v_k| > C$ turns out to be valid.

It would be interesting to obtain an unimprovable estimate for Problem M275 6) (it is unknown to the author). However, for the purposes for which the M275 task was proposed, an accurate assessment is not needed. The goal is mentioned - the proof of Riemann's complex theorem (see «Kvant», 1973, No. 9, “From the reversal of terms,” exercises 22 and 23).

In yarn and 3. Based on M275 6), complete exercise 22 from the article “From changing the places of terms.”

**M. L. Gerver**

Consider a similar plane transformation that transforms triangle BHC into triangle PHB; this is a center-like rotation through an angle of 90° centered at point H and a similarity coefficient of $k = \frac{|BH|}{|HC|} = \frac{|PH|}{|HB|}$ (Fig. 4). With this similar transformation, three vertices B, C, D of the square ABCD must, of course, go into three vertices of the square: B - to P, C - to B, therefore, D - to Q (enter $|PB| \perp |BQ|$ and $|PB| = |BQ|$ by condition). It follows that Q is obtained from D by a similar transformation consisting of a preparation with a coefficient of $k$ and a rotation of 90° around the point H.

Therefore, $DHQ = 90^\circ$ (at the same time we proved that $\frac{|QH|}{|HD|} = \frac{|BH|}{|HC|}$).

Readers and participants of the World Olympiad last year, in which this problem was proposed, indicated many different solutions that did not use “geometric transformations.” For example, $\triangle BHQ \sim \triangle CHD$, since $\frac{|HB|}{|HC|} = \frac{|PB|}{|BC|} = \frac{|BQ|}{|CD|}$ and $HBQ \cong HCD$ (the sides of these angles have been redistributed); hence $BHQ \cong CHD$, hence $QHD = BHC = 90^\circ$.

**H. B. Vasiliev**

A segment is considered “special” if its ends have different colors. Note that a point is “special” if the segments coming out of it are more irrigated—“special.” Therefore, when recoloring any “special” point, the total number of “special” segments decreases. Since all “special” segments are at least zero, and at each step their number decreases by at least one, after a finite number of steps we obtain a system in which none of the points can be recolored and, therefore, there are no special points.

**AND. N. Klumova**

Answer. a) Not always; 6) always.

a) Take a regular triangle with sides 2 (at Fig. 5 it is dotted). From the middle of its side we restore its side of the redistribution, put it on them

⟦folio 52⟧

Is the length diagonal greater than 2?
6) In a convex hexagon ABCDEF, the diagonal lengths AD, BE and CF are greater than 2. Does it always have a side of length greater than 1?

Fig. 5.

M279. Numbers are written on n cards laid out in a circle, each of which is equal to +1 or -1. In what is the smallest number of questions you can definitely determine the product of all n numbers, if in one question you can find out:
a) product of numbers on any three cards?
b) the product of numbers on any three cards lying in a row? (n is a natural number greater than 3.)

Fig. 6.

Let us denote the numbers written on the cards by $a_1, a_2, \dots, a_n$, and eliminate the number of questions by $p$.

a) First of all, we note that each of these numbers must be included in at least one of the products, the meanings of which we will find out by asking our question, or otherwise, by changing the sign of the number written on an unused card, we will change the sign of the product of all numbers, while keeping the same answers to all the questions asked. (This shows that based on the answers received, it is impossible to determine the product of all numbers.) Since with one question we learned the product of three numbers, then $p \geq \frac{n}{3}$.

If $n=3k$, then k questions are sufficient. Having found out what the k products $a_1a_2a_3, a_4a_5a_6, a_7a_8a_9, \dots, a_{3k-2}a_{3k-1}a_{3k}$ and the resulting variables are equal to, we will find the product of all numbers.

If $n=3k+1$, then $p \geq k+1$. Let us show that with $k>1$ in $(k+1)$ questions you can find out the product of all numbers.

Let's find out what $(k+1)$ products $a_1a_2a_3, a_1a_2a_4, a_1a_2a_5, a_6a_7a_8, a_9a_10a_11, \dots, a_{3k}a_{3k+1}a_{3k+2}$ are equal to, and ask $k+2$ questions (the products involve the 3k factor once, and the factors $a_1$ and $a_2$ three times each, that is, the $3k+6$ factor). We will show that $k+1$ questions are not enough.

The $k+1$ products include a $3k+3=n+1$ factor; but since each of the $n$ numbers written on the cards must go into at least one of these products, then one number (let’s call it a) is included in two products: $abc$ and $ade$, and each of the other numbers is included in one product. But by replacing the numbers a, b and d, we will not change any of the answers received, while changing the product of all of them by number cards; This means that based on the $k+1$ answers received, this work cannot be completed.

⟦folio 53⟧

So, the answer to problem a) is:
if $n=3k$ then $p=k$,
if $n=3k+1$, then $p=k+1$ (except in the case of $n=4$),
if $n=3k+2$, then $p=k+2$.

b) If $n=3k$, then as in problem a), $p=k$. Let $n$ not be divisible by 3.

Note that in the conditions of problem b) questions can be asked about the values ​​of only such $n$ products:
$a_1a_2a_3,\ a_2a_3a_4,\ \dots,\ a_{n-2}a_{n-1}a_n,\ a_{n-1}a_na_1,\ a_na_1a_2.$ (*)

Having asked all $n$ questions, we find out the cube of the product $a_1a_2\dots a_n$, and therefore the product itself - after all, it is equal to 1 or $-1$. Let us show that $n-1$ questions are not enough to find the product $a_1a_2\dots a_n$.

By asking $n-1$ questions, we will know all the works (*), except one. Since we could start numbering the cards with any of them, we can assume that the question about the meaning of the product $a_1a_2a_3$ was not asked.

Let $n=3k+1$. By replacing $a_2$ and $a_3$, $a_5$ and $a_6$, $a_8$ and $a_9$, ..., $a_{3k-1}$ and $a_{3k}$ with opposite numbers, as well as the number $a_1$, we change the sign of the entire product $a_1a_2\dots a_n$ (since they are replaced $2k+1$ numbers). But since in each of the products (*), except for the product $a_1a_2a_3$, about which we do not ask anything, two factors change, then we will not learn anything about this change of sign of the entire product by asking $n-1$ questions.

Let $n=3k+2$. Again, by replacing $a_4$ and $a_5$, $a_7$ and $a_8$, $a_{10}$ and $a_{11}$, ..., $a_{3k+1}$ and $a_{3k+2}$ and $a_2$ by opposite numbers, we change the sign of the entire product $a_1a_2\dots a_n$ (since again it is replaced an odd number of numbers) and again we do not recognize this change, since again in all products (*), except for the product $a_1a_2a_3$, two factors change.

So, the answer to problem b) is:
if $n$ is not divisible by 3, then $p=n$;
if $n$ is divisible by 3, then $p=\dfrac{n}{3}$.

Now we see that in problem a) for $n=4$ $p=4$.

Yu. I. Ionin

⟦figure⟧
Fig. 7.

⟦column⟧

F285. A refrigerator with a thermostat operates in an unheated room. When the refrigerator was connected to the network, the temperature outside, indoors and in the refrigerator was the same. Assuming the temperature outside is constant, roughly depict on graphs how the temperature in the room changed after connecting the refrigerator.
Consider three cases:
1) the refrigerator is empty;
2) filled with products;
3) The refrigerator door is open.
Draw all three graphs of temperature versus time on one figure.

◆

A refrigeration machine operates on the reverse principle of a heat engine: a certain amount of work is done on the working fluid—the agent gas—and heat is transferred from the cold body to the hot body. In this case, not only the heat that is taken from the cold body is transferred to the hot body, but also heat equivalent to the work done. In a home refrigerator (see Fig. 7), the liquefied gas agent, evaporating, takes away heat from the walls of the evaporation chamber. This gas is then liquefied again in a condenser, transferring heat to the surrounding air.

If the refrigerator door is open, heat is removed by the evaporator from the surrounding air and transferred by the condenser to the same air in the room. The air also receives heat equivalent to the work done and heat generated in the supply wires and in the compressor motor winding. Therefore, when the refrigerator door is open, the temperature in the room will continuously increase until the amount of heat entering the room becomes equal to the amount of heat leaving the room outside. The thermostat will not work in this case. The temperature change graph in the room is shown at figure 8 with a black line.

Now consider a closed refrigerator. Initially, the temperature inside the refrigerator (in the refrigerator compartment) will decrease, and in the room it will rise, and slightly

⟦folio 54⟧

faster than in the case of an open refrigerator, since now heat is taken not from the air in the room, but from the air, which is located in a limited volume of the cabinet, and is separated from the air in the room. The temperature in the room can become either higher $T_1$ or lower. This depends on the intensity of heat exchange between the room and the street and on the temperature inside the refrigerator at which the thermostat becomes equal (i.e., from the time the refrigerator is running until it is turned off). When the temperature in the refrigerator reaches the set temperature, the thermostat will disconnect the refrigerator from the network, and the temperature inside the refrigerator will gradually increase due to heat exchange through the walls of the refrigerator. Then the refrigerator turns on again, the temperature in the room will change, etc. The graph of the temperature inside the refrigerator versus time is the blue line at figure 8.

In accordance with the temperature fluctuations in the refrigerator compartment, the temperature in the room also changes. But just as when the refrigerator is disconnected from the network, the temperature of the condenser is higher than the temperature in the room, the temperature in the room continues to rise for some time, despite the fact that the refrigerator is not working. Then the temperature in the room decreases until the refrigerator turns on again, etc. If the thermostat is good, that is, it turns on the refrigerator when it is necessary to increase the temperature inside the cabinet, then the refrigerator operates almost continuously.

Since a relatively small amount of heat is transferred from the refrigerator to the room through the walls of the refrigerator, the refrigerator does little work. The temperature in the room gradually decreases, tending to some constant temperature (below $T_1$). If the thermostat is bad, then the refrigerator will turn off for a long time if its heat exchange with the room is poor, and for a relatively short time if this heat exchange is good. This determines the temperature fluctuations and the average value to which the temperature in the room tends. One of the curves of the temperature in the room versus time is shown in figure 8 red line.

When the refrigerator is full of food, both the time the refrigerator is on and the time it is off increases. In accordance with this, the period (temperature fluctuations in the room) also changes.

Consider one of the turns of the coil, for example, turn ABC (Fig. 9). When the spring is deformed, half of this turn rotates, deviating from the horizontal plane.

⟦folio 55⟧

Is it possible that if one end is fixed and the other is rotated by an angle φ around the axis, then a moment of elastic forces $M=k\varphi$ arises. After this, a spring of radius $R$ was wound from the wire with a step much smaller than $R$. Calculate the elasticity coefficient of the spring (assume that the elastic properties of steel are completely restored after coiling the spring).

⟦figure⟧
A)

⟦figure⟧
b)

⟦figure⟧
V)

⟦figure⟧
G)

Fig. 10.

F287. *The canal passes over a bridge over the highway. Will the pressure on the bridge change if an empty barge moves along the canal one time and a loaded barge another time?*

F288. *Vessel C (Fig. 11) communicates with the surrounding space through a small opening. Temperature of the gas in the surrounding space T, pressure p. The gas is so rarefied that the molecules do not collide with each other when flying into and out of the vessel over the size of the hole. The temperature in the vessel is maintained at 4T. What will be the pressure in the vessel?*

⟦column⟧

speed at equal angles α. If the spring deformation is small, then this angle α is also small. In section B, a force F and a moment of force F equal to $M=FR$ act on the wire from the side of the lower part of the spring, where R is the radius of the coils of the spring. The stresses that balance the force F are R/r times less than the stresses that balance the moment M (prove this; r is the cross-sectional radius of the wire), and they can be neglected. This means that when considering the deformation of a spring, we can assume that it is associated with the net twisting of the wire around its axis. Let us find how the tension of the spring is related to the angle φ through which the wire is twisted. It is clear that section C does not rotate when the spring is stretched. Indeed, when the spring is stretched, the upper AC and lower NE parts of the coil rotate at the same angles in different directions. It is obvious that sections A and B do not rotate either. (They only slightly deviate in the plane perpendicular to figure, in accordance with the change in the inclination of the coil.)

A simple tilt of half of the turn BC by an angle α will cause a rotation of sections B and C by an angle α (Fig. 10, a, b). But sections B and C must remain oriented as in an undeformed spring. Let's rotate them sequentially by angle α. Rotating section C will cause half of the turn to twist at angle α clockwise (Fig. 10, c). The wire is twisted at the same angle when turning section B through an angle α (Fig. 10, g). Consequently, half of the turn rotates through an angle of 2α. The entire coil is twisted at an angle of 4α, the entire wire is twisted at an angle φ=4nα, where n is the number of turns of the spring.

Since the length of one turn is $2\pi R$, and the length of the wire is $l$, then $n=\dfrac{l}{2\pi R}$ and $\varphi=\dfrac{2l\alpha}{\pi R}$.

It is obvious that the elongation of the spring on one turn (see Fig. 9) is equal to $2\Delta h=4R\sin\alpha$, or, since the angle α is small and $\sin\alpha\approx\alpha$, $2\Delta h\approx4R\alpha$. The elongation of the entire spring (over n turns) is $\Delta H=4nR\alpha$. Let us denote the elasticity coefficient of the spring by μ. Then $F=\mu\Delta H$. On the other hand, $M=FR$, that is, $F=\dfrac{M}{R}$. Therefore, $\mu\Delta H=\dfrac{M}{R}=\dfrac{k\varphi}{R}$. From here

$$\mu=\dfrac{k\varphi}{R\Delta H}=\dfrac{k4n\alpha}{R4nR\alpha}=\dfrac{k}{R^2}.$$

◆

The pressure on the bridge is determined by the water level in the channel. If a barge moves along a canal, then, strictly speaking, the water level rises the more, the heavier the barge. However, practically the water level in the entire canal, of course, remains the same, since the volume of water displaced by the barge is very small compared to the total volume of water in the canal.

◆

The gas pressure in the vessel is equal to $p_1=n_1kT_1=4n_1kT$, where $n_1$ is the concentration of molecules in the vessel (the number of molecules per unit volume) and k is Boltzmann’s constant. Outside the vessel, the pressure is $p=n_2kT$ ($n_2$ is the concentration of molecules in the surrounding space). Hence,

$$p_1=4p\dfrac{n_1}{n_2}.$$

Thus, in order to find the pressure in a vessel, it is enough to determine the ratio of the concentrations of gas molecules in the vessel and in the surrounding space. To find this ratio, we take advantage of the fact that the gas in the vessel is in equilibrium.

At equilibrium, the number of gas molecules escaping from

⟦folio 56⟧

⟦figure⟧
Fig. 11.

vessel is equal to the number of gas molecules flying into the vessel during the same time. For simplicity of reasoning, we will assume that the speeds of all gas molecules at a steady temperature are the same and equal to the root mean square speed corresponding to this temperature. In addition, we will assume that the molecules move along three mutually perpendicular directions, one of which is perpendicular to the cross-sectional plane of the hole, and all directions are equally probable. Then $1/6$ part of all molecules present in the vessel moves towards the hole. During time $\Delta t$, those molecules that are located from the hole at a distance equal to $v_1\Delta t$ fly out of the vessel, where $v_1$ is the speed of the molecules in the vessel. Since the concentration of molecules in the vessel is $n_1$, then in time $\Delta t$ $1/6\, n_1 v_1 \Delta t \Delta S$ molecules fly out of the vessel ($\Delta S$ is the area of ​​the hole). Similarly, we find that $1/6\, n_2 v_2 \Delta t \Delta S$ molecules fly into the vessel from the outside, where $v_2$ is the speed of gas molecules in the surrounding space. Under equilibrium conditions $n_1 v_1 = n_2 v_2$. From this we find that the ratio of the concentrations of molecules is equal to

$$\frac{n_1}{n_2} = \frac{v_2}{v_1}.$$

But, as is known, the root mean square speed of molecules is related to the gas temperature by the formula $\dfrac{m\overline{v^2}}{2} = \dfrac{3kT}{2}$

($m$ is the mass of the molecule). Hence,

$$v_1 = \sqrt{\frac{12kT}{m}}, \quad v_2 = \sqrt{\frac{3kT}{m}} \quad \text{и} \quad \frac{n_1}{n_2} = \frac{1}{2}.$$

Using this relationship, we find the gas pressure in the vessel:
$$p_1 = 2p.$$

◆

⟦figure⟧
Fig. 12, a.

**F289.** A rigid stick of length $2l$ slides along the sides of the right angle, in the center of which a bead of mass $m$ is fixed. The speed of point $B$ is constant and equal to $v$ (Fig. 12, a). Determine the force with which the bead acts on the stick at the moment when $\alpha=45°$.

⟦figure⟧
Fig. 12, b.

⟦column⟧

Let's consider a bead. Two forces act on it - the force of gravity $m\mathbf{g}$ and the force $\mathbf{Q}$ of the reaction of the stick. According to Newton's second law

$$m\mathbf{g}+\mathbf{Q}=m\mathbf{a}.$$

Therefore, if we find the acceleration of the bead, we will thereby determine the force $\mathbf{Q}$. And according to Newton’s third law, the force $\mathbf{N}$ with which the bead acts on the stick is equal in absolute value to the force $\mathbf{Q}$.

Let's draw several positions of the stick (Fig. 12, b). From figure it is clear that the bead (point $C$) is always at the same distance from the vertex of the right angle. This follows from the fact that in a right triangle, the median connecting the vertex of the right angle to the middle of the hypotenuse is equal to half the hypotenuse.

So, the bead moves along a circle of radius $l$, the speed $v_c$ of the bead is always directed tangent to this circle, and the centripetal acceleration is equal to

$$a_\mathrm{ц} = \frac{v_c^2}{l}.$$

At any moment of time, the total speed of the bead is the sum of the horizontal and vertical components. According to the conditions of the problem, the speed of the point $B$ is constant and equal to $v$. For reasons of similarity, the horizontal velocities of all other points are also constant, and the horizontal velocity of the bead is equal to $\dfrac{v}{2}$. This means that the bead's acceleration and force $\mathbf{Q}$ are directed vertically!

At the moment when $\alpha=45°$, the speed $v_c$ of the bead is directed along the stick, and its vertical and horizontal co-

⟦folio 57⟧

⟦figure⟧
Fig. 12. c.

the components are identical in magnitude and equal to $\dfrac{v}{2}$ (Fig. 12, c).

Therefore, the total speed of the bead at this moment is equal to

$$\sqrt{2}\,\dfrac{v}{2}\ .\ \text{Поэтому}\ a_{\text{ц}} = \dfrac{v_c^2}{l} = \dfrac{v^2}{2l}\ \text{и}$$

$$a = \sqrt{2}a_{\text{ц}} = \dfrac{v^2}{\sqrt{2}\,l}\ .$$

Then from Newton's second law

$$Q = mg - ma = m\left(g - \dfrac{v^2}{\sqrt{2}\,l}\right),$$

And

$$|\mathbf{N}| = |\mathbf{Q}| = m\left(g - \dfrac{v^2}{\sqrt{2}\,l}\right).$$

◆

F290. The tube, which contains a spring with a ball attached to it, can rotate around a vertical axis passing through the end of the tube. The free end of the spring is attached to the tube (Fig. 13). A graph of the elastic force of spring $F$ versus deformation is presented in figure 14.

Draw an approximate graph of the dependence of the displacement of the ball along the tube on the angular velocity as it increases from zero to a value such that $F=5\text{н}$. How will this relationship change as the angular velocity decreases? $l_0 = 2$ see

⟦figure⟧
Fig. 13.

⟦figure⟧
Fig. 14.

⟦column⟧

We will assume that the angular velocity $\omega$ of rotation of the tube changes slowly, so that at each value $\omega$ the ball is in an equilibrium state relative to the tube, and in a stationary frame of reference the ball moves along a circle of radius $l_0+\Delta l$ ($\Delta l$ is the change in the length of the spring). Since the centripetal acceleration $a=\omega^2(l_0+\Delta l)$ is imparted to the ball by the elastic force of the spring, then according to Newton’s law

$$m\omega^2(l_0+\Delta l)=F_{\text{упр}}. \qquad (*)$$

In order to solve the problem, it is necessary to find from equation (*) the dependence of $\Delta l$ on $\omega$ or, more conveniently, $l=l_0+\Delta l$ on $m\omega^2$.

The dependence of the elastic force of the spring on the elongation of the spring is given graphically, so we will also solve equation (*) graphically. Let's redraw the graph, shifting the origin to the point with coordinate $-l_0$ (Fig. 15). Now along the abscissa axis we have the total length $l$ of the spring. If we draw a straight line from the origin of coordinates, then the coordinates of the point of intersection of this line with the graph will be the values ​​$F_{\text{упр}}$ and the corresponding length of the spring $l$, and the tangent of the angle of inclination of the straight line to the abscissa axis will be equal to $F_{\text{упр}}/l$, that is, $m\omega^2$.

To construct a graph of the dependence of $l$ on $m\omega^2$, we draw a bunch of straight lines from the origin and mark all the points of intersection of the lines with the graph. Then, knowing the values ​​of $l$ and the corresponding values ​​of $m\omega^2=\mathrm{tg}\alpha$, we will mark them on the graph of the dependence of $l$ on $m\omega^2$. From figure 15 it is clear that at angles $\alpha<\alpha_1$, that is, at $m\omega^2<\mathrm{tg}\alpha_1$, each of the drawn straight lines intersects with the graph $F_{\text{упр}}(l)$ only at one point, and each value $m\omega^2$ corresponds to one value $l$. At $\alpha_1<\alpha<\alpha_2$ the straight line intersects the graph at three points (at $\alpha=\alpha_1$ and $\alpha=\alpha_2$ - at two), that is, the same value $m\omega^2$ corresponds to three values ​​$l$. Let us mark them all on the graph, leaving aside for now the question of what such polysemy means. At $\alpha>\alpha_2$, that is, at $m\omega^2>\mathrm{tg}\alpha_2$, each of the lines again intersects with the graph at only one point and each value $m\omega^2$ corresponds to one value $l$. By connecting all the plotted points with a smooth curve, we get the graph shown in figure 16 with a black line. Let's look at this chart in more detail.

At $m\omega^2<\mathrm{tg}\alpha_1$ and at $m\omega^2>\mathrm{tg}\alpha_2$ each value of angular velocity corresponds to one value $l$. Everything is clear here. But with $\mathrm{tg}\alpha_1<m\omega^2<\mathrm{tg}\alpha_2$ there are three different values ​​of $l$ for each value of $m\omega^2$. At what distance from the axis of rotation is the ball? First of all, it is clear that the ball is not

⟦folio 58⟧

can be at a distance that corresponds to point $B_2$ of the graph (see Fig. 15). Indeed, suppose that due to some random causes the ball should deviate from this equilibrium position, so that $l$ increases by $\Delta x$. In order for the ball to rotate while being at a distance $l + \Delta x$ from the axis, the compression force must increase. In our case, the compression force, as can be seen from figure, decreased. Consequently, this force cannot impart to the ball the centripetal acceleration necessary for its movement, and the ball will continue to move along the tube to position $B_3$. Thus, point $B_2$ corresponds to the position of the unstable equilibrium of the ball. Similarly, it can be shown that points $B_1$ and $B_3$ correspond to the stable equilibrium position of the ball.

Posny at $tg\alpha_1 < m\omega^2 < tg\alpha_2$ the ball can be in positions corresponding to sections of the graph $A_1C_1$ and $A_2C_2$.

Fig. 15

Fig. 16.

In which of its stable positions will the ball be? The answer to this question depends on how the angular velocity of rotation of the tube changes. If $\omega$ increases, then the ball cannot get to the positions corresponding to section $A_2C_2$ of the graph without reaching the positions corresponding to section $A_1C_1$, which of which is stable. Consequently, with increasing angular velocity $l$ will be less according to the graph shown on figure 16 red line (at point $m\omega^2 = tg\alpha_2$ the value $l$ changes abruptly from the value corresponding to point $C_1$ to the value corresponding to point $C_2$). As the angular velocity increases, the graph of $l$ versus $m\omega^2$ will be as shown in figure blue line. It should be borne in mind that if the tube rotates with an angular velocity such that $tg\alpha_1 < m\omega^2 < tg\alpha_2$, then, if only the ball is zero, it can be moved to a position corresponding to the “alien” section of the graph, according to which $l$ will further change as $\omega$ changes.

I. Sh. Slovodetsky
