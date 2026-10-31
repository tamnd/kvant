---
id: 1976-6-resheniya-zadach-m343-m350-f353-f357-c353fe7f
issue: kvant_1976_6
year: 1976
number: "6"
title: Solutions to problems M343—M350; F353—F357
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 41
page_labels: 29, 30, 31, 32, 34, 36, 38, 39
tag: 2A21
lang: en
source: kvant_digital
extraction: vision
content_sha256: 100c22f1162227a1d299615e9bdc26430c213446e106c73292fbb56fe4dd8456
prompt_sha256: draft-1
translated_from: content/ru/1976/06/articles/09_resheniya-zadach-m343-m350-f353-f357-c353fe7f.md
source_content_sha256: 86332fae4bb9f566b4bbe4f1f9443083ee6efac1d8cb0b0dca04d1b57b397877
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

were burning. Draw a diagram of the completed installation and explain the observed effects. (8th grade)

F399. Three small identical metal balls in a vacuum are placed at the vertices of an equilateral triangle. The balls are connected one at a time to a remote conductor, the potential is maintained constant. As a result, the first ball has a charge $Q_1$, and the second one has a charge $Q_2$. Determine the charge of the third ball. (9th grade)

F400. The two charged particles were initially identical in size and direction. After a uniform electrostatic field was turned on for some time, the velocity vector of one of the particles turned by $60^\circ$, and the numerical value of the velocity decreased by half. the velocity vector of the other particle has rotated by $90^\circ$. How many times did the numerical value of the speed of the second particle change? Determine the charge-to-mass ratio for the second particle if it is $k_1$ for the first particle. (9th grade)

F401. The circuit shown in figure 1 (Wheatstone bridge) is usually used to measure the unknown resistance $x$. How, using a similar circuit, can you measure the resistance $R_G$ of the galvanometer $G$ itself, if there is no second galvanometer? (10th grade)

F402. A diverging lens with a focal length $F = -0,6$ m is located so that one of its foci coincides with the pole of a concave mirror. What is the focal length $F_1$ of the mirror if the system is known to produce a real image of an object placed at any distance in front of the lens? The image is created by rays that pass through the lens for the second time after reflection from the mirror. (10th grade)

Problem solutions

M343—M350; F353—F357

M343. In some states, cities are connected by roads. For any road less than 500 km and from any city to any by road

We will denote cities with the letters $A, B, C, D, \dots$. First of all, we note that: 1) if some path $A$ - ... - $B$ - ... - $C$ - ... is the shortest between cities $A$ and $C$, then part of it, for example, from $A$ to $B$ is the shortest path between the corresponding cities; 2) the shortest path does not pass along the same road twice.

⟦folio 30⟧

less than 500 km. When one road was closed for repairs, they found out that you can drive from any city to any other along the remaining roads. Let us prove that this can be done by driving no more than 1500 km.

Fig. 1.

Fig. 2.

Fig. 3.

M344. The chains of all 64 squares are laid out on the chessboard. Is it possible to check 13 lines on the board so that in each of the parts in which these lines divide the board there is no more than one offset point? (Straight lines must not pass through field chains.)

M345. In the sequence 1 9 7 5 2 3 ... each digit, starting from the square, is equal to the last digit of the sum of the previous chain. Does it occur in a row in this sequence?

Let us now assume that the road connecting cities A and B is closed; let's denote it by AB. Let's divide all cities into two groups: the first group includes city A and those cities whose shortest path to city A did not go along the road AB, and the second group includes all the rest. We must assume that city B is in the second group - otherwise there will be no city at all in the second group; because if AB is not the shortest path from A and B, then none of the shortest paths can travel along the road AB, that is, the road AB is then useless.

Let M and N be cities, the shortest path between them is now more than 500 km. This means that the equal shortest path between M and N was along the road AB. But then the shortest route to city A from one of these cities was along road AB, but from the other - not (see the remark at the beginning of the solution); therefore, cities M and N belong to different groups. By contradiction, we find that any two cities belonging to the same group can be connected by a path less than 500 km long.

Since it is still possible to travel from city A to city B, there are two cities C and D such that C belongs to the first group, and D to the second, and city C is connected by a road to D. Now it is clear how from any city M of the first group to get to any city N of the second group, traveling less than 1500 km: you need to go from M first to city C (this is a journey of less than 500 km, since M and C belong to the same group), then from C to D (the length of the road CD is less 500 km according to the condition), and, finally, from city D to city N (cities D and N are from the same group, so the path from D to N is again less than 500 km) - see figure 1.

The estimate of 1500 km cannot be improved. Indeed, if four cities A, B, C and D are located as shown in figure 2 (ABCD is a trapezoid such that when extending its lateral sides, an equilateral triangle is obtained), then by closing the road AB, we obtain that the length of the shortest path between A and B is equal to (500+2a) km, where a can be made angularly close to 500.

S. Eliseev

At figure 3 it is shown how lines 14 are straight (at figure these lines are red) separating all the centers of the squares of the chessboard.

However, 13 straight is not enough for this.

Indeed, consider a square passing through the chains of all 28 border cells (at figure 4 it is a square of black dots). It is clear that 13 straight lines intersect it in no more than 26 points, and therefore are cut into no more than 26 parts, that is, two “border” centers will end up in one part. This means that to separate 28 boundary, and therefore all centers, at least 14 hits are direct.

Yu. Lysov

To solve the problem in point a) it is enough to note that in the sequence 1975... after each quadruple digit there are four digits in a row. Therefore, the four 1 2 3 4 cannot occur in this sequence.

We will analyze points 6) and c) in more detail.

Under the conditions of this rule, how to determine the next number based on four adjacent numbers. Let's try

⟦folio 31⟧

a) four numbers 1 2 3 4?
b) secondary numbers 1 9
7 5?
e) numbers 8 1 9 7?

do the opposite: using four adjacent numbers $a b c d$, determine the number $x$ that precedes them. Since the digit $d$ follows the quadruple digit $x a b c$, then the digit $d$ is equal to the last digit of the sum $x + a + b + c$, which means $x + a + b + c = 10k + d$ for some integer $k$. Hence, $x = 10k + (d - a - b - c)$. Since $x$ is a digit, it follows from the last expression that $x$ is equal to the remainder of the number $(d - a - b - c)$ when divided by 10. Dividing the number $p$ by the number $q$ with a remainder means finding the numbers $s$ and $r$ as well as $p = sq + r$ and $0 \leqslant r < q$. (Please note that the remainder when dividing the number - 13 by 10 is 7, not - 3!) The remainder when dividing one number by another is determined uniquely; This means that the number $x$ is also uniquely determined.

For example, to determine the number preceding the four 1 9 7 5, you need to subtract 1, 9, 7 from 5 and divide the resulting number (-12) with the remainder by 10. The remainder is 8; This means that the number 8 precedes the four 1 9 7 5.

Fig. 4.

1 9 7 5 2 3 ... x a b c d ... y a b c d ... (*)

Fig. 5.

Because under the sequence (*) is the same sequence again, but “shifted”, so that under the first quadruple $a b c d$ there is a second one (see Fig. 5). According to the statement proven above, the numbers in the first column located to the left of the red line coincide, i.e. $x = y$. Likewise, the numbers in the previous $x$ and $y$ columns coincide, and so on. Thus, in each of the columns located to the left of the red line, the numbers match. Therefore, under the four 1 9 7 5 in the “upper” sequence there is the four 1 9 7 5 in the “lower” sequence. And this means that the four 1 9 7 5 meets in the sequence 1 9 7 5 2 3... secondary.

As was shown above, the number 1 9 7 5 is preceded by the number 1 9 7 5 in the sequence 1 9 7 5 2 3... the second time, the number 8 will appear. This means that the number 8 1 9 7 will also appear in the sequence under consideration.

G. Gurevich

♦

Let's put the square on the checkered paper from the side of the cell equal to the $1/4$ side of the square, as shown in figure 6 (the points $K$ and $L$ will fall into the lattice nodes!). Obviously, the triangles $KNL$ and $MLD$ are congruent to $\Rightarrow LDM \cong KLN$, and therefore $DLM + KLN = 90^\circ$. Therefore $DLK = 180^\circ - (DLM + KLN) = 180^\circ - 90^\circ = 90^\circ$, which is what needed to be proven.

L. Limanov

⟦folio 32⟧

M347. Two cerams in a dipping cerra. The first one is given two numbers from 1 to 25, and the second one must eat them up. He can name any two numbers from 1 to 25 and find out from the first how many of the numbers he named - 0.1 or 2 - coincide with the given ones. In what minimum number of questions can he definitely determine the given numbers?

| Answer | Given numbers |
| :--- | :--- |
| 1,1 | 2i,25 |
| 1,0 | 2i-1,23 |
| 0,1 | 2i-1,24 |
| 0,0 | 2i-1,25 |

Fig. 7.

M348. A 10x10 table contains numbers from 1 to 100 in order. Then in each row and in each column, exactly half of the numbers are given a minus sign. Prove that in the resulting table the sum of all numbers is equal to zero.

M349. What condition must the line lengths of a triangle satisfy in order for the triangle to be co-

Many readers have successfully solved the given numbers in 14 questions. Let us show that it is always possible to determine given numbers in no more than 13 questions.

When naming the pairs (1,2), (3,4),...,(21,22), we use 11 questions; In this case, the following 4 cases are possible:

a) after some question the answer “2” is received;
b) all questions received answers “0”;
b) for some two questions - i-th and j-th - the answers “1” were received;
d) only one i-th question received the answer “1”, the remaining questions received a “0” (inattentive consideration of this case led many to believe that it was impossible to guarantee the determination of the given numbers in 13 questions).

We indicate the further actions of the guesser in each of these cases.

a) After the answer “2” the given numbers are determined.
b) Two numbers from the numbers 23,24,25 are guessed. We ask the question (23,24). If the answer is “2”, then these numbers are given, if the answer is “1”, then with the question (23,22) we determine which of the numbers - 23 or 24 - is given along with the number 25.

b) The numbers in the i-th pair are (2i-1) and 2i, in the j-th pair - (2j-1) and 2j. We ask questions (25.2i), (25.2j). The answer “1” to the first (twelfth) question means that the i-th pair contains the number 2i; the answer "0" indicates the number (2i-1). Same with the second (thirteenth) question.

d) Questions (2i,23), (2i,24) with all possible answers determine the given numbers. In fact, the answer “2” to the first or second question does not require dedication. For other combinations of answers to these two questions, we report the given numbers (it is easy to verify that there cannot be a different opinion about what numbers are given)—see. table at figure 7.

So, we have shown that in 13 questions you can always determine the given numbers; Naturally, as follows from the solution, sometimes fewer questions are enough.

To complete the solution, we will prove that it is impossible to guarantee the determination of the given numbers in 12 questions. After 11 questions, all answers can be “0”; however, there are always three numbers not included in the questions. If the twelfth question does not contain any of these three numbers, then the answer "0" allows any two of them to be asked. If the twelfth question includes one or two of these three numbers, then after the answer “1” it is also impossible to unambiguously indicate the given numbers.

Yu. Lisov

◆ Let us present this table A as the sum of two tables B and C (Fig. 8). Let's arrange the signs in each of the tables A, B and C in the same way - so that in each row and in each column there will be minus minutes in half the numbers. Then in the resulting table B the sum of the numbers will be equal to zero in each column, and in the resulting table C the sum of the numbers will be equal to zero in each column. Consequently, the sum of the numbers in tables B, C, and therefore in A=B+C will be equal to zero.

N. Vasiliev

◆ Let us denote this triangle by ABC, the lengths of its sides BC, AC and AB by a, b and c, the resistance values ​​of these sides of the angles by A, B and C of the corresponding one. Let's assume that a≤b≤c (then A≤B≤C). Let h_a, h_b, h_c—

⟦folio 34⟧

If $a=c$, then the triangle $ABC$ is equilateral: $a=b=c$ (since $a \leq b \leq c$), and we obtain this condition as a special case of the condition $2b^2=a^2+c^2$.

It is easy to see that if $2b^2=a^2+c^2$, then condition (2) is also true. Therefore, if the lengths $a, b$ and $c$ ($a \leq b \leq c$) side of the triangle $ABC$ are related by the relations $2b^2=a^2+c^2$, then this triangle is similar to a triangle composed of its medians.

c) Again we need to find out which sides of the triangle $ABC$ and the triangle from its bissertrices can be similar (assuming that these triangles are similar). For example, what do we have $a \leq b \leq c$. Let us prove that then $l_a \geq l_b \geq l_c$.

Let us express $l_a, l_b$ and $l_c$ in terms of $a, b$ and $c$. By the cosine theorem and the bissertrix theorem inside it of the angle of a triangle we have (Fig. 10):

$$l_a^2 = c^2 + \left( \frac{ac}{b+c} \right)^2 - 2c \frac{ac}{b+c} \cos B = c^2 + \left( \frac{ac}{b+c} \right)^2 - \frac{2ac^2}{b+c} \cdot \frac{a^2+c^2-b^2}{2ac} = bc \left[ 1 - \frac{a^2}{(b+c)^2} \right].$$

Likewise

$$l_b^2 = ac \left[ 1 - \frac{b^2}{(a+c)^2} \right] и l_c^2 = ab \left[ 1 - \frac{c^2}{(a+b)^2} \right].$$

Since $a \leq b$, we get $b+c \geq a+c$, that is, $\frac{a}{(b+c)^2} \leq \frac{b}{(a+c)^2}$, and $\frac{a^2b}{(b+c)^2} \leq \frac{ab^2}{(a+c)^2}$; therefore, $c \left[ b - \frac{a^2b}{(b+c)^2} \right] \geq c \left[ a - \frac{ab^2}{(a+c)^2} \right],$ i.e. $l_a \geq l_b$. Inequality $l_b \geq l_c$ is proved in a similar way.

So, if the triangle $ABC$ ($a \leq b \leq c$) is similar to the triangle from the bissertrix, then the equalities $l_c:l_b:l_a = a:b:c$ must hold, that is, $\frac{l_c}{l_a} = \frac{a}{c}$ and $\frac{l_b}{l_a} = \frac{b}{c}$.

Let's see when these conditions are met.

If $\frac{l_c}{l_a} = \frac{a}{c}$, then $al_a = cl_c$. But a similar relationship always holds for heights: $ah_a = ch_c$ (see point a). This means (Fig. 11), right triangles $AH_aL_a$ and $CH_cL_c$, where $|AH_a| = h_a$, $|AL_a| = l_a$, $|CH_c| = h_c$, $|CL_c| = l_c$, are similar, and their sides of length $h_a, h_c$ and $i_a, l_c$ are similar. Therefore, the angles formed by the sides $AH_a$, $AL_a$ and $CH_c$, $CL_c$ will be equal: $H_a\widehat{AL_a} = H_c\widehat{CL_c}$. Let's calculate these angles.

Recall that we have $a \leq b \leq c$, that is, $A \leq B \leq C$. From this condition it follows that $L_c \in [AH_c]$, and $L_a \in [BH_a]$.

Posmotu $H_a\widehat{AL_a} = \frac{\pi}{2} - \frac{A}{2} - B$, $H_c\widehat{CL_c} = \frac{\pi}{2} - \frac{C}{2} - A$,

and since $H_a\widehat{AL_a} = H_c\widehat{CL_c}$, then $\frac{A}{2} + B = \frac{C}{2} + A$, that is

⟦folio 36⟧

M350. The bishop begins to move from the white corner square of the chessboard with dimensions $n \times m$ ($n$ and $m$ greater than 1). Having reached the edge of the board, we turn the bishop at a right angle. Once in the corner, he stops.

a) For what $n$ and $m$ will the bishop go around all the white squares of the board?
b) How many fields will he cover on the board $n \times m$?
Let us consider boards of size $10 \times 15, 10 \times 25, 15 \times 25$ as examples.

Fig. 13.

Fig. 14.

Fig. 15.

a) Consider the right angle to $A_{00}A_{01}A_{11}A_{10}$ with vertices at the centers of the angular fields (Fig. 13) $|A_{00}A_{10}| = n - 1, |A_{00}A_{01}| = m - 1$. Let's take a lattice and generate it by a straight line (Fig. 14). Let us denote the nodes of such a lattice by $A_{ij}$, $i,j = 0,1,2,...$ (Node $A_{ij}$ is the point of intersection of the line passing through $A_{i0}$ parallel ($A_{00}A_{01}$) with the line passing through $A_{0j}$ parallel ($A_{00}A_{10}$); points $A_{i0}(i = 1,2,...)$ lie on the line $A_{00}A_{10}$, points $A_{0j}(j = 1,2,...)$ - on straight line $A_{00}A_{01}$, and $|A_{(i-1)}A_{i0}| = |A_{i0}A_{(i+1)}| = |A_{00}A_{10}|$, $|A_{(j-1)}A_{0j}| = |A_{0j}A_{(j+1)}| = |A_{00}A_{01}|$.

Let us draw a ray $d$ from the point $A_{00}$ at an angle $45^\circ$ to the straight line $A_{00}A_{01}$ (the bisector of the right angle of the lattice). Then the path of the bishop $A_{00}B_1B_2B_3...$ along the board will correspond to the sequence of points $A_{00}, B_1, B_2', B_3',...$, at which the ray $d$ intersects from the side of the lattice. The bishop stops on the $l$ move (hitting the corner) if and only if the $B'_l$ point hits a lattice node.

Let $A_{pq}$ be the first (not counting $A_{00}$) lattice node lying on the ray $d$ (it corresponds to the corner square of the board reached by the bishop). Since $A_{00}A_{0q}A_{pq}A_{p0}$ is a square, $p(n-1) = q(m-1) = a$; (1) and the number $a$ is the least common multiple of $m-1$ and $n-1$ (recall that node $A_{pq}$ is the first).

Between nodes $A_{00}$ and $A_{pq}$ the ray $d$ intersects the sides of the lattice $p+q$ times, and corresponds to $p+q$ times the bishop hits the edge of the board. At the board boundary there are $2m+2n-4$ squares - equally white and black. The bishop captures on all white squares of the board in this and only that case if he captures on all bordering white squares, i.e. if $p+q = m+n-2$.

(2)

From (1) and (2) it follows that $\frac{a}{m-1} + \frac{a}{n-1} = (m-1)+(n-1)$, whence $a = (m-1)(n-1)$. But the least common multiple of two numbers is equal to their product if and only if they are relatively prime; and we get the answer to point a) of the problem: the bishop will go around all the white squares of the board if and only if the numbers $m-1$ and $n-1$ are coprime.

6) If each “inner” white square of the board through which the bishop passes twice were counted twice, then the number of white squares traversed by the bishop would be equal to $a+1$ (since for the side of the square $|A_{00}A_{0q}| = a$, $a$ is an integer, on the diagonal $A_{00}A_{pq}$ lie the centers $a+1$ of the square side one). To find how many white squares the bishop will actually go around, you need to subtract from $a+1$ the number of internal white squares the bishop will go through twice. Let's count how many such fields there are.

Let us denote by $b$ the greatest common divisor of the numbers $m-1$ and $n-1$ (now we already assume that the numbers $m-1$ and $n-1$ are not coprime; then $b > 1$ and $(m-1) \times (n-1) = ab$). Let's put $M = \frac{m-1}{b} + 1$, $N = \frac{n-1}{b} + 1$. The numbers $M-1$ and $N-1$ are coprime, therefore, if we take a board of size $N \times M$, then the bishop, starting from the white corner square, will go around all its white squares. Primogutyns $A_{00}A_{10}A_{11}A_{01}$ and $A_{00}A_{10}'A_{11}'A_{01}'$ (Fig. 15) are similar, therefore the numbers of self-intersections of the bishop’s path on both boards (dimensions $n \times m$ and $N \times M$) are the same. But since the bishop lands on all the boundary white squares of the board $N \times M$ and passes along all its diagonals, then

⟦folio 38⟧

2.1 kW The voltage of the seven is 220 V, the resistance of the supply wires is 1 ohm. What is the resistance of the heating element of the furnace?

F355. The pV diagram (Fig. 17) shows a closed process carried out with one mole of saza. Sections 1→2 and 3→4 of the graph are straight lines passing through the origin of coordinates, and sections 2→3 and 4→1 are isotherms. Draw a graph of this process on a TV diagram. Find the volume $V_3$ if the volumes $V_1$ and $V_2 = V_4 = V$ are known.

Fig. 17.

Fig. 18.

Here $U = 220$v is the network voltage, $I$ is the current in the circuit.

The thermal power released at the load is $P = I^2R$. (2)

Eliminating the current $I$ from equations (1) and (2), we obtain a quadratic equation for $R$:

$$PR^2 + R(2rP - U^2) + Pr^2 = 0.$$

From this equation one can directly find $R_1 \approx 21$ ohm, $R_2 \approx 0,05$ ohm.

At either value $R$ the power will be released at the load of 2.1 kW, but at $R=0,05$ ohm the power at the supply wires will be $\frac{I^2r}{I^2R} = \frac{1}{0,05} = 20$ times greater than at the load! Clearly this is unacceptable. Therefore, you need to select the resistance of the heating element $R=21$ ohm.

N. Slobodetsky

In order to plot a graph of this process on a diagram of the dependence of absolute temperature on volume, we first find the dependences between $T$ and $V$ for processes 1→2 and 3→4. On the pV diagram, the graphs of these processes are straight lines passing through the origin of coordinates, so we can write:

for process 1→2 $p=\alpha V$, where $\alpha =$ const;
for process 3→4 $p=\beta V$, where $\beta =$ const ($\beta<\alpha$).

Comparing these equations of processes with the equation of state of an ideal gas $pV = vRT$ ($v = 1$ mol), we obtain that in the process 1→2 $T = \frac{\alpha}{vR} V^2$,

and in the process 3→4 $T = \frac{\beta}{vR} V^2$.

Thus, both processes on the TV diagram are depicted by parabolas (Fig. 18), and the parabola for process 1→2 is larger, since $\alpha > \beta$. States 2 and 4 are characterized by the same volumes $V_2=V_4=V$ (by condition), therefore, on the TV diagram they lie on the same vertical line $V =$ const, intersecting both parabolas. Isotherms 2→3 and 4→1 on the TV diagram are depicted as horizontal segments, starting in width at points 2 and 4 and in width until they intersect with the adjacent parabola at points 3 and 1.

Now let's find the volume $V_3$. Since sections 2→3 and 4→1 are isotherms,

$$T_2 = T_3 \text{ и } T_1 = T_4.$$

Let us rewrite these equalities using the expressions for temperatures already known to us through the corresponding volumes:

$$\frac{\alpha}{vR} V^2 = \frac{\beta}{vR} V_3^2$$

And

$$\frac{\alpha}{vR} V_1^2 = \frac{\beta}{vR} V_2^2.$$

Dividing the first equality by the second, we find

$$V_3 = \frac{V^2}{V_1}.$$

⟦folio 39⟧

F356. At what speed does the moon move across the earth's surface during a total solar eclipse? The eclipse is observed at the equator. For simplicity, assume that the distance of the Moon to the Earth is $R_1 = 384\ 000$ km, and the period of revolution around the Earth is $T_1 = 28$ days. $cym = 2\ 419\ 200$ sec. Similarly, we apply that the radius of the Earth is $R_2 = 6\ 400$ km and the Earth makes a complete revolution around its axis in a time of $T_2 = 1$ days. $cym = 86\ 400$ sec. Then the speed of the Moon in its circular orbit is

$$v_1 = \frac{2\pi R_1}{T_1} \approx 995\ m/sec,$$

Light from the Sun

Fig. 19.

and the linear speed of points on the earth's surface

$$v_2 = \frac{2\pi R_2}{T_2} \approx 465\ m/sec,$$

Moreover, for that region of the Earth’s surface where the shadow of the Moon is observed, both velocities are directed in the same direction (Fig. 19).

Since the sun's rays can be considered parallel and the size of the Moon is small, the shadow of the Moon moves relative to the earth's surface at noon at the speed

$$v = v_1 - v_2 = 2\pi \left( \frac{R_1}{T_1} - \frac{R_2}{T_2} \right) \approx 530\ m/sec.$$

F357. A cube of mass m is attached to two springs with stiffnesses $k_1$ and $k_2$ and unstrained lengths $l_1$ and $l_2$ corresponding. Attached other ends (Fig.20), so the cube

Let us introduce a coordinate system with the origin at point $O$ (on the left wall) and with the positive direction of the axis $OX$ to the right. Let the coordinate of the cube be $x$ ($0 < x < L$); therefore, it is at a distance of $x$ from the left wall and at a distance of $L - x$ from the right wall (see Fig. 20).

Let us denote by $F_1$ the projection of the force acting on the cube from the left spring. According to Hooke's law

$$F_1 = k_1(l_1 - x).$$

Fig. 20.
