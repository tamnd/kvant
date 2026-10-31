---
id: 1973-1-ryivkin-formalizatsiya-usloviy-zadach-a32e792a
issue: kvant_1973_1
year: 1973
number: "1"
title: Formalization of task conditions
authors:
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 37
page_last: 41
page_labels: 35, 36, 38, 39
tag: BN3N
lang: en
source: kvant_digital
extraction: vision
content_sha256: 282ba7bcdcd0684a7e240b6ffa1ea2a841581058cb27df3291c4ad933cb08a29
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/12_ryivkin-formalizatsiya-usloviy-zadach-a32e792a.md
source_content_sha256: c816f5dd5cb94867e38095187c52008fa24d9a35176b1ad4d1b5f653c88e07de
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

Formalization of the problem conditions

A. A. Ryvkin

When people whose lives revolve around mathematics remember school, they involuntarily think of trains going from point A to point B, and swimming pools into which water is poured through one labor and poured out through another. Although such problems have little in common with the “real” aksiomatic mathematics, the standard of which has remained elementary geometry for many centuries, solving them skillfully is one of the indispensable criteria for assessing the mathematical preparation of most applicants.

Apparently, the vitality of such text problems lies in the role that logic plays in them, inherent in any rigorous applied research.

Today, mathematics is increasingly and increasingly successfully used to solve specific problems (both purely practical and those arising in other sciences) that require an individual, unconventional approach to their formatting.

When faced with such a problem, a mathematician first strives to formulate it in words, that is, to build a verbal model that reflects all the essential aspects of the phenomenon and leaves aside the secondary ones. Then this verbal model will be presented to format, or build a mathematical model of the object being studied. The formal model must, on the one hand, be precisely simple in order to allow further mathematical analysis, and on the other hand, it must be effective - it must meet the purpose for which it was designed.

The model constructed in this way can be studied using a number of mathematical means. Most often it turns out to be a control system, and the goal is achieved as a result of its solution. In other cases, the system consists of controls and constraints. Often, the conditions of the problem contain some quality criterion that allows one to select the “best” from the many possible solutions of the system. It is heard that at the last stage of solving the system, the discrepancy between the model and the research goals is revealed. Then you have to return to the very first stage and start all over again.

The word problem that applicants face on the exam is a verbal model of some criterion problems. Even if this problem is not always quite realistic in its content, even if it is known in advance that it has a more or less simple solution. The logic of formalization and the remaining stages of applied mathematical research are necessarily contained in it.

Now word problems have begun to appear, leading applicants to the problems they will have to face after entering the university. For example, in 1968, applicants to the Department of Economic CyberNETKI of the Faculty of Economics of Moscow State University were offered such a task.

Task 1. The factory must send an order of 1100 parts. Parts for shipment are packed in boxes. Three minute boxes are available. One box of the first type has 70 parts, one box of the second type has 40 parts, and one box of the third type has 25 parts. The cost of sending one box of the first, second and third types is equal to 20, 10 and 7 rubles. Which boxes should you use?

⟦folio 36⟧

factory so that the shipping cost is minimal? Inexpensive boxes are not allowed.

Readers accustomed to solving word problems will easily write down the corresponding matching formulas. If we denote by $x_1, x_2$ and $x_3$ the number of boxes containing 70, 40 and 25 parts, respectively, then

$$70 x_1 + 40 x_2 + 25 x_3 = 1100,$$

since, according to the conditions, under-loading of boxes is not allowed. The values ​​$x_1, x_2$ and $x_3$ must be chosen such that the shipping cost

$$20 \times 70 x_1 + 10 \times 40 x_2 + 7 \times 25 x_3$$

was the smallest.

Unfortunately, the formulaic recording of the conditions of the problem does not help us much in finding its solution. It is more useful for Goraddo to imagine himself in the place of the examination worker who was assigned to carry out this transfer. The first thing he will pay attention to will be the cost of shipping one part for each of the three options.

Comparing the numbers $\frac{20}{70}, \frac{10}{40}$ and $\frac{7}{25}$ or after reducing to a common value $\frac{200}{700}, \frac{175}{700}$ and $\frac{196}{700}$, he will notice that the cheapest shipping is in sets of 40 parts, and the most expensive is in sets of 70 parts. Since 1100 is not divisible by 40, the visitor will take advantage of not only the most profitable sets. In order to lose as little as possible, he will gradually refuse the most favorable conditions, that is, consider the case when the maximum possible number of parts are packed into boxes of 40 parts: 1080, 1040, 1000, 960, etc. In the first case, 20 parts will remain unpacked, and in the second - 60 parts. They cannot load boxes with 25 parts each, much less 70 parts. The third case is quite acceptable: it assumes that 25 boxes of 40 parts each ($25 \times 40 = 1000$) and 4 boxes of 25 parts each will be used for packaging. Any other option will lead to greater expenses, since the number of the most profitable kits will decrease due to an increase in the number of less profitable kits (25 parts per box) or due to the appearance of the most profitable kits (70 parts each), which are not used at all in the option we found.

We see that in solving this problem, common sense turned out to be much more useful than formal mathematics. But for the task from another version of the same year, common sense alone would not be enough.

Task 2. Chemyr groups of musicians went on a Sunday hike through several marirums of different lengths. The sum of surveys eaten by the first and quarters together is 6 km greater than the sum of surveys eaten by the second and third groups. The second group fell 2 km less than the first. The number of musicians of the third group is equal to the distance (in kilometers) covered by the first group, and the number of musicians of the second group is equal to the distance covered by the fourth group, equal to 494 km². How many kilometers did each group travel?

As in the previous task, let's start by formatting the condition. If group number $i$ covered $x_i$ km, then

$$\begin{cases} x_1 + x_4 = x_2 + x_3 + 6, \\ x_1 = x_2 + 2, \\ x_1^2 + x_2^2 + x_3^2 + x_4^2 = 494. \end{cases}$$

We have obtained a system of equations with four unknowns. True, the conditions remained unused, due to which $x_1$ is equal to the number of tourists of the third group, and $x_4$ is equal to the number of tourists of the second group. At first, these problems cause bewilderment, and a childhood joke problem pops up in my memory, ending the questions neither in the village nor in the city.

⟦folio 38⟧

filling the tank with the first and second pipes will it yield a 5% acid calculation? To record the fact that the tank was replenished, we need to know the time that these two pipes worked. It is equal to $\frac{1}{x_1+x_2}$. During this time, $\frac{qx_1}{x_1+x_2}$ of concentrated acid was received, which is 5% of the volume equal to one:

$$\frac{qx_1}{x_1+x_2} = 0,05.$$

In the second case, the reservoir was replenished first when it was full. The amount of concentrated acid turned out to be equal to $\frac{qx_1}{2(x_1+x_2)}$.

Then it was replenished only by the second pipe, through which acid of concentration $q$ flowed. Therefore, there was a total of $\frac{qx_1}{2(x_1+x_2)} + \frac{q}{2}$ concentrated acid in the tank. Thus, we get the second equation:

$$\frac{qx_1}{2(x_1+x_2)} + \frac{q}{2} = 0,1.$$

Solving the resulting system, we find that the pipe through which water flows has twice the throughput capacity compared to the pipe through which acid flows.

Although the solution to the problem is quite quick, the process of composing the equation required more difficult logical calculations than was necessary.

We should immediately draw attention to the fact that the reservoir itself does not play any role in the conditions of the problem, and therefore we chose the “core” of the problem incorrectly. In both the first and second cases, the conditions speak of fluid flows, and not of its reserves. If clean water and acid solutions of constant concentration begin to flow into the tank through two pipes at the same time, then a 5% acid solution will be obtained not only after its replenishment. At each moment of time, as a result of the movement of two liquids entering the reservoir, a mixture of 5% concentration is obtained. We now take the throughput of the pipe through which the acid flows as one, and denote the throughput of the other pipe by $p$ (we must determine $p$ according to the conditions of the problem). Let, as before, the concentration of acid entering through the first pipe be equal to $q$. The mixing process can be described by a simple equation:

$$\frac{q}{p+1} = 0,05$$

(per unit time, an amount of liquid equal to $p+1$ enters the pool, and the concentrated acid in this liquid will be $q$).

The second part of the problem is now reformulated as follows: as a result of mixing two identical volumes of acid, one of which had a concentration of 0.05, and the other $q$, a mixture of concentration 0.1 was obtained:

$$\frac{0,05+q}{2} = 0,1.$$

Solving the resulting equations is not difficult.

In this problem, the choice of a less rational way for its formalization was not a practical condition for the process of solving the resulting system of equations. However, in the same tasks of concentration, serious difficulties may arise only due to the fact that an unsuccessful choice was made by composing the equation. As an example, let us turn to a problem that was repeatedly proposed in exams (mechanics and mathematics, 1962, economic kiberetics, 1965).

Task 4. From a full tank containing 729 liters of pure acid, a liter and a gallon of water were poured. After complete movement (until a homogeneous detuning was obtained), a liter of solution was again poured from the tank, a tank of water was again added and the tank was carefully moved. After the dipping operation has been carried out six times, the liquid in the tank

⟦folio 39⟧

contained 64 liters of pure acid. Determine the values ​​of $a$.

In the conditions, the emphasis is placed on the fact that after repeating the operation six times, 64 liters of pure acid remained in the tank. Typically, these conditions serve as the basis for composing the equation.

However, the problem can be solved more simply if the concentration of solutions, rather than volumes, is chosen as the basis for composing the equation. Such problems are called concentration problems, since it is the appeal to concentration that allows us to obtain the most convenient formulaic representation of the condition. Let us denote by $q_1, q_2, \dots$ the concentration of acid in the bake after the first, second,... operation. It's obvious that

$$q_1 = \frac{729 - a}{729}, \quad q_2 = q_1 \frac{729 - a}{729}, \dots,$$

$$q_6 = q_5 \frac{729 - a}{729}.$$

In fact, if before the $(i + 1)$th operation the acid concentration was $q_i$, then $q_i$ liters of pure acid were removed from the tank, after which $q_i (729 - a)$ liters of pure acid remained in it. Thus,

$$q_{i+1} = q_i \frac{729 - a}{729}.$$

So, the concentration $q_i$ forms a geometric progression with the value $\frac{729 - a}{729}$. Since the concentration $q_6$ is equal to $\frac{64}{729}$ by condition, we obtain the equation

$$\left( \frac{729 - a}{729} \right)^6 = \frac{64}{729},$$

that is, $\frac{729 - a}{729} = \frac{2}{3}$,

whence $a = 243$.

Now move on to the exercise. Take your time to look into the solution, even if the task does not seem difficult to you and you only want to check the correctness of your train of thought. Bring the problem to an answer, and do it externally and carefully, and only after that read the solution. Compare your approach with the one proposed at the end of the issue.

Exercises

1. (Faculty of Economics, Moscow State University, 1968). It is expected to use 2000 rubles. on the way to separate houses. Vouchers are available for 15, 27 and 45 days; their cost is 21, 40 and 60 rubles respectively. How many and what kind of vouchers do you need to buy in order to maximize the total number of vacation days?

2. (Faculty of Chemistry, Moscow State University, 1969). The first vessel with a capacity of 6 liters is filled with 4 liters of 70% sulfuric acid solution; 3 liters of 90% sulfuric acid solution (volume content is meant) is poured into the second vessel of the same container. How many liters of solution must be poured from the second vessel into the first one in order to obtain a $r\%$ solution of sulfuric acid in the first vessel? Find all values ​​of $r$ for which the problem has a solution.

3. (Faculty of Chemistry, Moscow State University, 1970). Two pipes, when in operation, supply 100 liters of liquid per minute to the tank. There are two acid solutions - strong and weak. If you mix 10 liters of each solution and 20 liters of water, you will get 40 liters of a 20% solution. It is also known that if for an hour a weak solution is fed into an initially empty tank through the first pipe, and a strong solution through the second, you will get a 30% acid solution. What concentration (in%) will the acid be obtained if a strong solution is fed into an initially empty tank for an hour through the first pipe, and a weak solution through the second? (It is believed that when water and acid are mixed, the volume does not change.)

4. (Faculty of Philology, Moscow State University, 1970). The reservoir is supplied with water through five pipes. The first pipe fills the tank in 40 minutes, the second and fourth in 10 minutes, the third and fifth in 20 minutes, and finally the fourth and fifth in 30 minutes. How long does it take to fill the tank with all five when working simultaneously?

5. The vessel containing the $p\%$-th acid solution must be topped up with the $q\%$-th acid solution and, after mixing, the same amount is dispensed. Having sold this operation $k$ times, we received the $r\%$ solution. What fraction of the volume of the vessel is occupied by the initial solution?
