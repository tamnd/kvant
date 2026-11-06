---
id: 1991-12-mader-diagrammyi-eylera-venna-d912ecf4
issue: kvant_1991_12
year: 1991
number: "12"
title: Euler-Venn diagrams
authors:
  - Мадер В. В.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 37
page_last: 40
page_labels: 35-38
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5af7d847252f2b890b552763100e628bba9bb870e6bcd834a775b4aa70684456
prompt_sha256: draft-1
translated_from: content/ru/1991/12/articles/10_mader-diagrammyi-eylera-venna-d912ecf4.md
source_content_sha256: 1d16b180e7a324870ef636c42f2963c9f71119297d838a2b7b28e86e9ff76b9d
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 35⟧

---
running_head:
folio:
---

Candidate of Pedagogical Sciences
V. MADER

I will start my story with a specific task.

Task. The youth camp was supposed to have track and field events on Sunday. On the eve of this event, a letter arrived from another camp:

“Hello, dear guys! We want to take part in your competitions. Our team consists of volleyball players, runners, jumpers and throwers. All volleyball players are jumpers, and all jumpers are either throwers or runners. But among those throwers who are also jumpers, there are no runners. We have half as many throwers as jumpers, and two less than runners. Runners make up a third of the entire team, and there are twice as many volleyball players as there are guys who are both jumpers and throwers.

We will arrive on Saturday evening. Please prepare bed for our entire team. - Your friends.”

The known approach of the guests was greeted with delight. The only difficulty that arose was with placing them on the stuffed animals. It was necessary to know the number of expected guests, but this is precisely what the letter said nothing about. Nevertheless, we still managed to find out. How many guests were expected to arrive?

Solution. Let's look at figure 1. In it, a larger circle represents the set of all guests. Circles B, P, M represent, respectively, a set of runners, jumpers and throwers. It is not difficult to understand the meaning of individual parts of these circles. So, for example, the common part of two circles B and P represents the set of those guys who are both runners and jumpers. There were also volleyball players among the guests, but (as follows from the letter) none of the volleyball players were either runners, jumpers, or throwers. This means that the entire area outside circles B, P, M falls to the share of volleyball players. Therefore, this area is designated by the letter B.

It is known that all runners were jumpers. This means that the entire region B must be inside P. In order for this condition to be met, it is necessary to protect that part of B that extends beyond P, noting by this that the protected part is the empty set (that this part does not exist).

It is also known that all jumpers are either throwers or runners. This means that the circle P must be located entirely within the region consisting of B and M. Therefore, that part of P that extends beyond this region should be protected.

It is also known that among those throwers who were also jumpers, there are no runners. This means that from the common part of the circles M and P it is necessary to exclude the part that is inside B - it must also be protected.

In the unshaded cells there are seven letters x, y, z, t, which will indicate the number of children involved in the corresponding sports.

Fig. 1.

⟦folio 36⟧

---
running_head:
folio:
---

The number of throwers is half the number of jumpers. So 2(x+y)=y+z. The number of throwers is two less than the number of runners. So x+y+2=z. The runners make up the $1/3$ of the team. Therefore 3z=x+y+z+t. The number of volleyball players is twice as large as the number of guys who are both jumpers and throwers. So t=2y.

The result is a system of four equations with four unknowns. Having solved this system, we find: x=2, y=6, z=10, t=12. So, the number of all guests is 2+6+10+12=30.

Answer: a team of 30 people was supposed to come to the competition.

When solving the above problem, figure 1 played a significant role. It successfully used the idea of ​​depicting sets using circles. This idea is also useful in solving a number of other problems. Leonhard Euler, for example, made extensive use of such drawings, and in his honor the method was called the “Euler circle method.” This method was used by mathematicians before Euler. It was used, for example, by the outstanding German mathematician and philosopher Gottfried Wilhelm Leibnitz (1646-1716). figure with such circles were found in his rough sketches. But, as already mentioned, only the Swiss mathematician Leonhard Euler (1707-1783) developed this method quite thoroughly. He worked for many years at the St. Petersburg Academy of Sciences. His famous “Letters to a German Princess,” written from 1761 to 1768, date back to this time. In some of these letters, Euler talks about his method. After Euler, the same method was developed by the quadricular mathematician Bernard Bolzano (1781-1848), only, unlike Euler, he drew rectangular rather than circular diagrams. Euler's circle method was also used by the German mathematician Ernst Schröder (1841-1902) in his book “Algebra of Logic”. But graphic methods reached a special flowering in the works of English

the famous logician John Venn (1843-1923), who outlined them in detail in the book “Symbolic Logic”, published in London in 1881. This is why the diagrams are sometimes called “Venn diagrams”.

Diagrams can be constructed in different ways. So, for example, when solving the problem considered, one could together draw 1 to illustrate the conditions of the same problem using figure 2. Here the area $B$ (located to the left of the vertical line) denotes the runners; and the area $B$ (to the right of the vertical bar) denotes the set of non-runners. In the same way, above the horizontal line there is a set of $\Pi$ jumpers, and below the line there is a set of $\bar{\Pi}$ non-jumpers. The small circle $M$ denotes the set of non-throwers, and the ring-shaped area $M$ denotes the throwers. Cell $B$ is the intersection (common part) of set $\bar{B}, \bar{\Pi}, \bar{M}$. According to the conditions, it is known that those guys who were neither runners, nor jumpers, nor throwers, were volleyball players. That is why we designated this cell with the letter $B$.

Exercise. Try solving the problem we considered using figure 2.

The considered problem consists of solving four equations with four unknowns. But sometimes there were also problems when the number of equations was less than the number of unknowns.

⟦folio 37⟧

---
running_head:
folio:
---

The result is an indefinite control system, which, generally speaking, has countless sets of solutions. However, if we take into account some additional conditions, it turns out that in this case the problem can have only one solution. We will now consider this type of problem.

Task. The school had a plot of land with a greenhouse. On Saturday, a group of guys worked in this area. They repaired the greenhouse and used cucumbers, tomatoes and cabbage. At the end of the work, information was required about the number of workers, but the changing guys dispersed and it was not possible to find out anything.

Only the following were installed. The guys who repaired the greenhouse were not involved in the use, and the guys who used the vegetables did not participate in the repair of the greenhouse. None of the guys used cucumbers and cabbage at the same time. Some guys used tomatoes and cucumbers, others used tomatoes and cabbage, but there were no guys who used only tomatoes. 7 people used cucumbers, and 4 people used tomatoes. The number of guys who repaired the greenhouse was 2 less than the number of guys who used only cucumbers. The doubled number of children who used only cabbage was 1 more than triple the number of those children who used only cucumbers.

This information was sufficient to establish the number of workers. How many guys were there on the plot of land on Saturday?

Fig. 3.

Solution. Let us draw the corresponding Euler-Venn diagram (Fig. 3). Circles $O, \Pi, K$ represent many children who have eaten the corresponding cucumbers, tomatoes and cabbage. The greenhouse was repaired by those and only those guys who were not busy using vegetables. This means that the area located outside the circles $O, \Pi, K$ depicts many guys repairing the greenhouse. This area is indicated by the letter $T$.

None of the guys used cucumbers and cabbage at the same time. Therefore, the common part of circles $O$ and $K$ must be protected. None of the guys used only tomatoes. This means that that part of the circle $P$, which is outside the circles $O$ and $K$, also needs to be protected. We denote the numerical values ​​of unshaded cells by the letters $a, b, c, d, t$. The letter $a$, for example, indicates the number of children who used warm cucumbers; the letter $b$ indicates the number of children who used both cucumbers and tomatoes. The meaning of the remaining letters is also clear from figure. Now, according to the known data, we can write the equations:

$$\begin{cases} a + b = 7, \\ b + c = 4, \\ a = t + 2, \\ 2d = 3a + 1. \end{cases}$$

The result was an indeterminate system of four controls with five unknowns. To solve this system, we use $a$ for a parameter that we ourselves can assign some specific value to. Then there are four unknowns left. Having solved the system for these unknowns, we obtain the following correspondences:

$$b = 7 - a, c = a - 3, d = (3a + 1)/2, t = a - 2.$$

Now, it would seem, having given the parameter $a$ some arbitrary value, we will be able to calculate the corresponding values ​​of the unknowns $b, c, d, t$. And since the choice of the value of the parameter $a$ seems to be completely arbitrary, we will get an infinite number of solutions. In fact, this is not so. The point is that the unknown

⟦folio 38⟧

---
running_head:
folio:
---

numbers must be non-negative integers. This means that the following additional conditions must be met: 7—a≥0, a—3≥0, 3a+1≥0, a—2≥0, (3a+1)/2 is an integer. The last condition means that 3a+1 must be an even number, which is only possible when a is an odd number.

Having solved the system of inequalities given above, we obtain
3≤a≤7; a is an odd number.

This means that for parameter a we got three values: 3, 5, 7. But with a=3 we get c=0, and with a=7 we get b=0, which is impossible, since c and b indicate the number of guys who watered cabbage or cucumbers in addition to tomatoes, and according to the condition, these sets cannot be empty. Therefore, for parameter a there is only one value left: a=5. The remaining unknowns will then take the following value:

b=2, c=2, d=8, t=3.

Thus, the total number of guys working on the site is equal to
5+2+2+8+3=20.

Answer: 20 guys worked at the site on Saturday.

The law has no less. Construct an Euler-Venn diagram for this problem, similar to the one shown in figure 2.

Now try to solve the following problems yourself.

1. The boy told his friends that his grandmother had sent him a parcel with apples and pears. Some of these fruits were large, others were small. The fruits also varied in color: some of the fruits were yellow, the rest were green. Among the fruits there were neither small pears nor small green apples. There were 25 apples, and 17 pears. There were 32 large fruits. There were 28 yellow fruits. There were 2 more green apples than green pears. The most delicious were the large yellow apples. The guys became interested: how many such apples were there? But the boy did not tell them this. And then they themselves figured out these apples. What was their answer?

2. A complete team builds a fortune from masons, stove-makers, plasterers and general workers (i.e., auxiliary workers without qualifications). All stove-makers were stone-makers, and among those stone-makers who were also stove-makers, there was not a single one who was not also a plasterer. All the stones, who were also plasterers, were also owners of special stove makers. There were also plasterers who did not possess any other specialties. Moreover, it turned out that

1) there were as many workers who had only one specialty as there were general workers;
2) the sum of twice the number of those workers who were only plasterers, and three times the number of those workers who were only masons, is 15;
3) the number of workers who owned only the mason specialty was 5 times less than the sum of the number 9 and triple the number of those workers who owned all third specialties.

How many workers were in this brigade?

3. Each member of the tourist section took part in at least one of the planned pocodes, and there were three such pocodes: to the lake, to the waterfall and to the mountains. Of the guys who hung out at the lake, none of them went to the waterfall. Therefore, only 8 people went to the waterfall. All the guys who went to the mountains took part in at least one more pokoda. The number of guys who beat both on the lake and in the mountains, added to the number of guys who beat only on the waterfall, was 1 greater than the number of guys who were only on the lake. The sum of triple the number of guys who beat only on the lake, and double the number of guys who beat both on the lake and in the mountains, turned out to be equal to 19.

How many guys were in this tourist section?

4. Two girls - Lena and Valya - each brought a bouquet of flowers of carnations and roses. Some flowers were white, others were bright red. Among the flowers Lena brought, there were no white roses, and among the flowers Valya brought, there were no red roses. Neither Lena nor Valya brought white carnations. In addition, we found out the following:

1) Valya arrived with as many flowers as Lena;
2) the sum of twice the number of all white roses and three times the number of all red roses is 18;
3) the five times the number of roses brought by Lena was exactly 10 more than the double number of carnations brought by him.

How many and what flowers did each of the girls bring?

5. During the rain, the guys took a break on the river bank. Some of them immediately went into the forest to pick mushrooms and berries. The rest sunbathed in the clearing, swam in the river or went fishing. All the guys who swam in the river were sunbathing in the clearing, but those who didn’t get into the water would also be sunbathing among them. The fishermen settled in the shade and did not sunbathe. All 7 people were sunbathing. The sum of twice the number of fishermen and five times the number of children who were sunbathing but not swimming was equal to 18. There are as many children in the forest as there were fishermen.

How many guys have participated in this since?
