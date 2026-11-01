---
id: 1987-1-gutenmaher-rabbot-vyibor-nailuchshego-varianta-9ebd607d
issue: kvant_1987_1
year: 1987
number: "1"
title: Choosing the best option
authors:
  - Гутенмахер В. Л.
  - Раббот Ж. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 44
page_labels: 37, 38, 39, 41, 42
tag: 5VXI
lang: en
source: kvant_digital
extraction: vision
content_sha256: 84a50aac49f0434d5a5b63050cb581cf12901b5ba29137f17f1f49fe6fb523f1
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/12_gutenmaher-rabbot-vyibor-nailuchshego-varianta-9ebd607d.md
source_content_sha256: 788545c4a791bd53ebfea79050aa5bec984ddb80e74e7f3e8c6ae83dbcb04181
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

Choosing the best option

Candidate of Physical and Mathematical Sciences
V. L. GUTENMACHER,
.J.K. M. RABBOT

In junior classes, as well as in university entrance exams, they often offer problems on composing equations. In this case, it is necessary, firstly, to translate conditions from a common language into mathematical ones, and secondly, to solve the resulting equations and inequalities.
The text of the problem describes some situation and requires one specified data to determine others. Here, for example, are the first and last phrases of the conditions of the problem from an algebra textbook for grade 7:
“Two typists received a manuscript to retype... In how many hours could each typist retype the manuscript?”
“The boat set off from the river station downstream... How much time did the cyclist spend on the way from the city to the camp site?”
“A copper-zinc alloy containing 5 kg of zinc is alloyed with 15 kg of zinc... What was the original mass of the alloy?”
It is important to be able to solve such problems, since in arbitrary and economic practice it is often necessary to summarize, re-read and summarize various indicators, analyze the work of an enterprise.

tiy, etc. The result of this activity is an understanding of the current situation. After this, it is natural to take the next step - to draw up a plan-program for further actions. Here, of course, there are many options possible and you want to choose the most convenient one.

The formulation and solution of such problems is the subject of mathematical programming. However, one of the first to use mathematics in such matters was the Soviet mathematician, academician L. V. Kantorovich (1912-1986). In 1939, his book “Mathematical methods of organizing and planning arbitrariness” was published. In the introduction to this book he wrote:

“There are two ways to increase the efficiency of a workshop, an enterprise and an entire industry. However, the path is various improvements in technology, that is, new devices in a separate machine, changing the technological process, finding new, better types of raw materials. Another way, to use much less for now, is to improve the organization of arbitrariness and planning. This includes, for example, such issues as the distribution of work between individual machines of an enterprise or mechanisms, the correct distribution of orders among enterprises, the correct distribution of various types of raw materials, fuel, etc.”

Many years have passed since then, and mathematical programming has become a whole science based on eco-

⟦folio 38⟧

nomic-mathematical methods and the widespread use of computers.

As a result, planning and control tasks have to deal with a very large number of variables simultaneously. We will develop several simple educational examples with a small number of variables in which you can obtain solutions using mathematics known to students in grades 6-7 - proportions, properties of a linear function of one variable, a small search of options and, of course, ingenuity.

Where to build a bathhouse? The village of Mochalkino has 100 inhabitants, and the village of Veniki has 50 inhabitants. At what point on the highway connecting these villages should a bathhouse be built so that the total distance that all 150 residents will have to travel along the highway to the bathhouse is the smallest?

Let us translate the condition of the problem into mathematical language. Let the distance along the highway between the villages be a km and the bathhouse is located between the villages x km from Mochalkino, thereby 0≤x≤a. Then all 100 residents of this village will travel 100x km to the bathhouse, and all 50 residents of the village of Veniki will travel 50(a-x) km. In total, S=100x+50(a-x) km will be read.

So, we received the following mathematical problem: find the smallest value of the quantity S=50x+50a, provided that 0≤x≤a, where a is a fixed number.

It is very easy to solve the problem: it is enough to replace that the value of S decreases with decreasing x, therefore the smallest value of S will be at the smallest possible value of x, that is, at x = 0, and thus it is necessary to build a bathhouse in the village of Mochalkino.

Let's discuss the result obtained. Almost everyone to whom we asked the question of where to build a bathhouse immediately answered that it should be built in a place from which the distance to the village of Mochalkino is half the distance to the village of Veniki. They probably came up with the following physical model: they imagine a swing, with a person sitting at one end of the board, twice as heavy as the one sitting at the other end.

If the bathhouse is located at a distance of a/3 from Mochalkino, then all the residents together will follow the same path to the bathhouse as the residents of Venikov:

100·a/3=50·2a/3. Probably, it is more fair if it does not mean all the inhabitants, but contrasts one village with another and looks for a “balance point.” But this will be the solution to a completely different mathematical problem: at what value of x, where 0≤x≤a, the value f=|100x-50(a-x)| will be the smallest?

Of course, the words “best option” can be understood in completely different ways. To make precise sense of them, we compose an objective function. In our problem it was the function S=50x+50a, and in another version it was the function f=|150x-50a|. Having found x at which the objective function takes the smallest value, we have obtained the best (from a certain point of view) option.

It is clear that the residents of the village of Veniki may not be happy with either of these options and may perhaps raise arguments against them quite soon. Let’s add up that they have more old people and children, but fewer cars than in Mochalkino, that they have running water, but in Mochalkino they don’t, etc. But if we take all this into account, we get a completely different mathematical problem - a different mathematical model.

We hope that the somewhat light construction of the banya will not give readers the wrong impression. Now it’s a little worse, but the server tasks have already been completed: where on the territory of a large plant with several workshops to place a canteen? What is the best way to plan maintenance work in it?

Here, the choice of the objective function is clear in principle (least time consumption), but the optimal solution depends not only on the number of workers in different workshops, but also on the special

⟦folio 39⟧

production efficiency and other factors.

The best way to get to the station. Petra Petrovich urgently needs to get to the station. He can call a taxi, which will take 24 minutes, and drive at a speed of 30 km/h, or he can walk at a speed of 6 km/h. What is the best thing for him to do if the distance from home to the station is: a) 2 km; b) 3 km; c) 5 km?

In order to more clearly compare the movement of pedestrians and automatic vehicles, we are recruiting one more staff - the wife of Peter Petrovich.

Let's imagine that Pyotr Petrovich went to the station on foot, but as soon as he left the house, his wife noticed that he had stuffed his train ticket at home, immediately called a taxi, got it and went to pay her husband's price.

Let's calculate the time it will take for her to finish him off. After time $t$ after leaving the house, Pyotr Petrovich will be at a distance of 6t km from the house, and at $t > 24$ min=2/5 hours the taxi will travel 30(t—2/5) km.

The taxi can catch up with Pyotr Petrovich at the moment when

$$6t = 30(t - 2/5),$$

that is, at $t = 1/2$ hours. If the journey to the station is less than 1/2 hour, the wife will not have time to catch up with her husband, but if it is more than 1/2 hour, then she will catch him and give him a ride to the station. In $t = 1/2$ hours Pyotr Petrovich can move 3 km from his house. As a result of these discrepancies, we come to the following conclusion.

If the distance to the station is less than 3 km, as in the case of $a$), Petro Petrovich is better off walking; if it is 3 km, then it doesn’t matter - on foot or by taxi; and if it’s more than 3 km, as in case $b$) - it’s best to call a taxi.

For a better understanding of the solution, it is useful to present a graphical representation; a number of assumptions are silently made: the pedestrian and the taxi move uniformly, the taxi is called and departed instantly (in practice this is far from the case), etc. In addition, according to our conditions, time was the most valuable thing for Pyotr Petrovich. But in the case of $b$) we were faced with the fact that there were two options that were equivalent from this point of view. To choose one of them, you need another message: either the cost of the trip (then he will most likely walk), or the convenience (then he will take a taxi).

One bike for two. Two brothers, Kolya and Seryozha, are trying to get to their grandmother, who lives 40 km away from them. They have one bike that they've added some stuff to. Kolya walks at a speed of 6 km/h and rides a bicycle at a speed of 20 km/h; Serezha’s speed is 4 km/h and 30 km/h, respectively. The bicycle can be left on the road without any brakes. What is the fastest way for them to get to grandma together?

Let's assume that the brother arrives at the grandmother's at the same time, and we will find a time during which they can do this. Then we will show that in less time one of them will not be able to reach the grandmother.

Let Kolya ride a bike $x$ km and walk $(40-x)$ km, and Seryozha, on the contrary, ride $x$ km and drive $(40-x)$ km.

Then Kolya spent $(x/20+(40-x)/6)$ hours on the road, and Seryozha - $(x/4+(40-x)/30)$ hours.

If they are approaching at the same time,

$$\frac{x}{20} + \frac{40-x}{6} = \frac{x}{4} + \frac{40-x}{30}.$$

⟦folio 41⟧

$$m = \frac{2}{15} + \frac{7}{15} y,$$

which takes the smallest value at the smallest possible value of $y = 0$. If we expressed $m$ not through $y$, but through $x$ or through $z$, then it would be more difficult to figure out on what interval we should look for its smallest value. How best to choose which variable to assign a function to is also an important task.

It would be possible to do without these calculations if we note the following circumstances. In order for the new alloy to contain 40% cobalt and as little copper as possible, it must contain as much nickel as possible. Therefore, the second alloy, which seems to be good because it already contains 40% cobalt, is better not to touch it at all, since it contains no nickel at all - see the table. This means that we need to mix the first and third alloys. Let us take $a$ kg of the first alloy, then we need to take $(1-a)$ kg of the third. The new alloy will contain 0.6(1-a) kg of cobalt. By condition, 0.6(1-a)=0.4, so $a=1/3$, which leads to the answer.

New Year's task*). For 100 rubles. decision to buy.elochny cerrushek. Christmas tree cerrushkas are sold the other way around. A set of 20 cerrushes costs 4 rubles, a set of 35 cerrushes costs 6 rubles, a set of 50 cerrushes costs 9 rubles. How many and what sets should you buy in order to buy the least number of cerrushes?

One cerrushka in the first set costs 1/5 rub., in the second set - 6/35 rub., in the third set - 9/50 rub. Let's order these numbers: 6/35<9/50<1/5. So, the cheapest toys are in the second set, and the most expensive ones are in the first.

To buy for 100 rubles. as many cerrushes as possible, you need, of course, to buy large virgin cerrushes. At most, we can buy 16 sets for 6 rubles. and spend 96 rubles on it.

There are 4 rubles left, which you can use to buy the first set. We will all buy 16·35+20=580 zerrushki in this way.

This is most likely the best option. Still, let’s check this: if you buy 15 six-grub sets, then you have 10 rubles left. We can then buy another ninth guble set or two four guble sets. In both cases, the number of cerrushes turns out to be less than in the first option.

So, you need to buy 16 sets for 6 rubles. and 1 set for 4 rubles. In this case, 580 cerrushes will be purchased.

We came to this answer with the help of such a natural message: you can buy larger cerrushes the cheaper they are.

Our reasoning is plausible, but, generally speaking, we have not considered all possible options. Therefore, we present a more rigorous solution.

Let $x$ be the number of sets of type I, $y$ - type II, $z$ - type III. We need to find such non-negative

⟦folio 42⟧

numbers $x$, $y$ and $z$ so that the conditions $4x+6y+9z \leq 100$ are satisfied and the values ​​$S=20x+35y+50z$ are the most.

Since

$$4x+6y+9z = \frac{6}{35}S + \frac{4}{7}x + \frac{3}{7}z \geq \frac{6}{35}S,$$

it turns out that $\frac{6}{35}S \leq 100$, hence $S \leq 583\frac{1}{3}$.

Since $S=20x+35y+50z$ is an integer divisible by 5, we have $S \leq 580$. At $x=1$, $y=16$, $z=0$ all conditions are satisfied and $S=580$.

This problem relates to integer programming, which is one of the most complex branches of mathematical programming.

Quests

1. Three young salespeople - Yuri, Yakov and Lev - were assigned to work in a department store. The director of a department store needs to assign one of them to the radio goods department, another to the musical instruments department, and a third to the photographic goods department. The director asked the psychologist to help him verify this appointment. The psychologist had a conversation with them and assessed everyone’s knowledge

| RADIO | PHOTO | MUSIC |
| :--- | :--- | :--- |
| Yuri | 5 | 4 | 7 |
| Yakov | 6 | 7 | 3 |
| Loeb | 8 | 11 | 2 |

in all three areas in points. He then compiled a table and presented it to the director of the department store. How can the director distribute newcomers so that the sum of the corresponding points is the most? (For example, if Yuri is assigned to the radio department, Yakov to the music department, and Lev to the photography department, then the sum of points will be equal to $5+3+11=19$).

2. In a frying pan, put two cutlets together, you can fry them on both sides in 10 minutes. What is the fastest way to fry 3 cutlets in this frying pan?

3. Given two points, $A$ and $B$, located on one side of a given line. How to place a segment MK of given length $a$ on this straight line so that the broken line AMKB has the shortest length?

4. Three brothers have invested one, and they need to add to the house, located 30 km from the store. Each of the brothers walks at a speed of 4 km/h and rides on an investment at a speed of 20 km/h. In what shortest time can they be added to the house? (The attachment can be left on the road without a prism.)

5*) A baby can eat a cake in 10 minutes, a jar of jam in 8 minutes and drink a carton of milk in 4 minutes. Carlson can do this 2 times faster. In what shortest time can they together finish a breakfast consisting of a cake, a jar of jam and a carton of milk?

6. Each of the four contains 1 liter of a mixture of acid and water. The percentage of acid in them is 10%, 30%, 60%, 80% corresponds. The laboratory needs to obtain a 50% mixture of acid and water. What is the smallest quantity of such a mixture that he can obtain by pouring the mixtures from these vessels?

7. It is necessary to make an alloy containing 40% tin. There are 3 alloys in stock with 60%, 10% and 40% tin content. The price of 1 kg of each of the alloys is 4.3 rubles, 5.8 rubles. and 5.5 rub. corresponds. What alloys and in what proportions should be taken from the warehouse so that 1 kg of new alloy is as cheap as possible?

8. (Task of the entrance exam for the departments of economic planning and economics, library of the Faculty of Economics of Moscow State University, 1984). Three types of houses can be assembled from two types of building parts. To assemble a 12-apartment building, you need 70 parts of the first type and 100 parts of the second type. To assemble a 16-apartment building, 110 and 150 are required, and for a house with 21 apartments, 150 and 200 parts of the first and second types of the corresponding ones are needed. There are 900 parts of the first type and 1300 parts of the second type. How many and what kind of houses need to be assembled so that the total number of apartments in them is the largest?

9. On the highway rings there are three warehouses and three shops; the distance between each two neighboring points is 1 km. figure shows the availability of goods in warehouses (in tons) with a “+” sign and the store’s demand for goods (in tons) with a “-” sign. It is required to draw up the least economical transportation plan in order to transfer all the cargo from the warehouse to the store and so that the amount of transported ton-kilometers is the smallest. (Cite the transportation option available, from your point of view, and state the messages that led you to this answer.)
