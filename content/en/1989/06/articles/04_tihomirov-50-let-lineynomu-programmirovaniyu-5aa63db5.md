---
id: 1989-6-tihomirov-50-let-lineynomu-programmirovaniyu-5aa63db5
issue: kvant_1989_6
year: 1989
number: "6"
title: 50 years of linear programming
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 9, 10, 12, 13, 14
tag: X33E
lang: en
source: kvant_digital
extraction: vision
content_sha256: f35d3e374003d467e6fb6b055f11b9bb27550dfe8e3301ea7a37ef4761a77557
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/04_tihomirov-50-let-lineynomu-programmirovaniyu-5aa63db5.md
source_content_sha256: 96a8bc57c1d4c96e32ab3a3dd7efca5da57a091acffbba9c1d3e2784ff61d851
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

In 1975, the Soviet mathematician L. V. Kantorovich and the American economist T. Koopmans were awarded the Nobel Prize.

These prizes were named after their founder, the famous chemist and inventor Alfred Nobel. According to Nobel, they were to be awarded for scientific discoveries in the field of physics, chemistry, physiology or medicine, for literary works “reflecting the ideals of humanity”, as well as for those who “would make a significant contribution to the unity of peoples, the destruction of work, the reduction of the number of existing armies and the joint peace agreements.” The prize was not intended for mathematicians. However, in 1969, the Swedish Bank, on the occasion of the 300th anniversary of its formation, established a premio in memory of A. Nobel - in economic sciences. It was awarded in 1975 to L.V. Kantorovich and T. Koopmans for the creation of a new mathematical theory (received the name linear programming) and the application of this theory to economics.

In the autograph submitted to the Nobel Committee, Leonid Vitalievich Kantorovich talks about his experiences in 1939. He, a 26-year-old mathematics professor, was approached for advice by employees of the laboratorium of the plywood trust, which needed to solve the problem of the highest distribution of materials between machines. This problem coincided with finding the maximum of a linear function defined on a polygon. The maximum of such a function is achieved at a vertex, but the number of vertices in this problem reached a billion... Therefore, a simple enumeration of vertices was not suitable.

Leonid Vitalievich wrote:

“It turned out that this task is not accidental. I discovered a large number of problems, varied in content, of a similar mathematical nature: better use of sowing crops, choice of equipment loading, location of material cutting, use of raw materials, distribution of transport cargo flows... This really prompted me to search for an effective method for solving them.”

And already in the summer of 1939, L. V. Kantorovich’s book “Mathematical methods of organizing and planning production” was published, which contained the foundations of what is called mathematical economics.

In order to understand mathematical problems in which mathematics was able to provide significant help, let's start with an example - the same one with which Leonid Vitalievich begins his book.

Let the work require the production of the greatest number of sets of two parts. There are three types of machines I, II and III, the details of which are given in the table.

The “natural distribution” used in practice is that each group of machines produced the largest number of sets. Machines of the first type can produce 20 sets (for example, like this: the first and second machines each produce 10 of the first parts, and the third - 20 of the second) and cannot produce more. The number 36 has a similar meaning for machines of the second type: the first machine produces only

⟦folio 10⟧

to the first parts, the second - only the second, and the third - 4/5 of the time produces the first, and 1/5 of the time - the second part. Likewise for machines of the third type.

As can be seen from the table, the optimal distribution provides a significant benefit - 9 extra sets! - no additional costs required.

In order to find the far from optimal optimal distribution, it is necessary to translate the problem into the language of mathematics. So, we have seven machines at our disposal - the first, second and third machines form the first type, the fourth, fifth and sixth - the second and, finally, the seventh - the third type. It is required to indicate the fraction of time during which each machine must produce the first and second parts. Let $\alpha_i$ be the fraction of time during which the $i$-th machine will produce the first part, and $\alpha'_i$ be the fraction of the time it will work on the second part. Then $\alpha_i \geq 0$, $\alpha'_i \geq 0$, $\alpha_i + \alpha'_i \leq 1$, $i = 1, 2, \dots, 7$. The number of first parts made by machines will be equal to

$$10(\alpha_1 + \alpha_2 + \alpha_3) + 20(\alpha_4 + \alpha_5 + \alpha_6) + 30\alpha_7.$$

Similarly, the number of second parts is equal to

$$20(\alpha'_1 + \alpha'_2 + \alpha'_3) + 30(\alpha'_4 + \alpha'_5 + \alpha'_6) + 80\alpha'_7.$$

The number of first and second parts should be the same and as large as possible. So we come to the problem:

find the maximum number $s$ such that

$$s = 10(\alpha_1 + \alpha_2 + \alpha_3) + 20(\alpha_4 + \alpha_5 + \alpha_6) + 30\alpha_7,$$

and substitute it into the expression for $s$. We get

$$s = \frac{230}{3} + \left(20 - \frac{50}{3}\right)y + \left(30 - \frac{110}{3}\right)z = \frac{230}{3} + \frac{10}{3}y - \frac{20}{3}z.$$

Now it is clear that the greatest value of the sum will be obtained when $y = 3,$

⟦folio 12⟧

kah also looks like this:

$$\begin{cases}
s = 10x + 20y + 30z, \\
10x + 20y + 30z \geq 20(3-x) + 30(3-y) + 80(1-z), \\
20(3-x) + 30(3-y) + 80(1-z) \geq 10x + 20y + 30z, \\
x \geq 0, 3 \geq x, y \geq 0, 3 \geq y, \\
z \geq 0, 1 \geq z.
\end{cases}$$

The “polyhedron” defined by the system of inequalities is depicted in the same color at figure 1 - it coincides with a flat patagon. The vertex at which the function s reaches a maximum is placed in red.

L.V. Kantorovich proposed several approaches to solving the formulated general problem. One of them is based on the idea of ​​duality. To understand it, let's solve the machine tool problem in a different way.

Again we denote $\alpha_1 + \alpha_2 + \alpha_3$ by $x$, $\alpha_4 + \alpha_5 + \alpha_6$ by $y$ and $\alpha_7$ by $z$; Let us introduce new notations: $x' = \alpha'_1 + \alpha'_2 + \alpha'_3$, $y' = \alpha'_4 + \alpha'_5 + \alpha'_6$, $z' = \alpha'_7$. Let us associate each set $(x, y, z, x', y', z')$, where all numbers are non-negative and related by the inequalities

$$x + x' \leq 3, y + y' \leq 3, z + z' \leq 1,$$

(1) a point in the plane $(a; b)$ with coordinates $a = 10x + 20y + 30z$, $b = 20x' + 30y' + 80z'$. (2)

What is the set $C$ of all points given by relations (1) and (2)? This set is the sum of three sets: $C_1$, formed by those points $(a; b)$ for which $a = 10x, b = 20x'$; $C_2$, consisting of points $(a; b)$, for which $a = 20y$, $b = 30y'$; $C_3$, consisting of points $(a; b)$, for which $a = 30z, b = 80z'$. In this case, of course, inequality (1) is satisfied. The sets $C_1, C_2$ and $C_3$ are the triangles shown in figure 2.

To construct the required set $C$, we first find the sum $C_1$ and $C_2$, i.e. the set of points $(a; b)$ with coordinates

$$a = 10x + 20y, b = 20x' + 30y'.$$

To do this, triangle $C_2$ is laid off from the upper vertex of triangle $C_1$, and then $C_2$ “slides down the hill” formed by the hypotenuse $C_1$. The result is a quadrilateral shown in figure 3.

Now we can construct the set $C$. Let's move the triangle $C_3$ from the top vertex to figure 3 and let it “slide down the hill” formed by the two-link broken line. This produces the pentagon $C$ shown in figure 4.

What is required in the task? It is required to find a point $A = (a; b)$ such that, firstly, $a = b$, and secondly, $a$ has the most value. This point lies at the intersection of the bisector and the broken line $KLMN$ (see Fig. 4) and has coordinates $(86^2/3, 86^2/3)$.

How do we add to point $A$? Let's approach it from both sides. Let's take a step along the segment $KL$ from point $K$ to point $L$. At the same time, we will rise by 80 units. This corresponds to the fact that the triangular machine must produce 80 second parts. Next we will take a step from point $N$ to point $M$. At the same time, we will be astonished to the right by 60 units. This

⟦folio 13⟧

corresponds to the fact that machines of the second type should work only on the first parts and make 60 of them.

And now we move from $L$ to $A$ and from $M$ to $A$. This corresponds to the fact that the first machine works $2^2/3$ of the total three units of time on the first part (and we move up to the right by $26^2/3$) and $1/3$ of time on the second part (and we move up by $6^2/3$). As a result, we get to point $A$.

By the way, it becomes clear what to do if we have not three, but $n$ types of machines. Then the set $n$ will be a bounded polygon of $C$ links, the angles of inclination of which will be ordered from the lower point to the upper one in descending order. And again we need to go from the top and bottom points towards each other. All types of machines, except one, will process only one part - “upper” - the first, “lower” - the second. And only in the last section will one type of machine have to “share” - part of the time to process the first part, part of the time to process the second part.

In our second solution, the main role was played by the straight lines on which the link-breaker KLMN lies. In the most general terms, the idea of ​​duality is that a polyhedron can be defined as a set of its vertices, or as the intersection of a set of half-spaces containing it.

Having formalized the derived problem and indicated some solutions, L. V. Kantorovich also saw wonderful prospects in the field of economics. Imagine yourself in the place of a foreman who has seven workers under his command. They work on the very same machines that we have already met with more than once. You must organize production in such a way as to produce as large sets of parts as possible.

One way is directive. The foreman calls a team and orders with his head: “You, Peter, let’s make the second part on a machine of the third type; Ivan, Nikolay and Alexander - make the first part on a machine of the first type” and so on.

But there is another way, more delicate. You can call a team and say: “Guys, you need to make two types of parts on your machines. The first one costs 2 rubles, and the second one costs 1 ruble; for each set of parts of two types - a bonus of 10 kopecks. Think about how you can earn more."

Perhaps the first option that will come to workers’ minds is what is called “natural distribution” in our table. At the same time, they will earn 238 rubles 70 kopecks. But then they

⟦folio 14⟧

probably agreeing that there is a more profitable one - “optimal distribution”.

Question: What is the maximum amount a brigade can earn?

Where did the prices for parts come from? Look at figure 4. The line LM on which the optimal point A lies has the equation 2a+b=260. Its coefficients 2 and 1 are the prices. If it were not for the premium for completeness, then with prices for parts of 2 and 1 rubles, the largest earnings of the crew would have come from any of the points on the segment ML. And a small premium of 10 kopecks makes point A the most profitable. This is the art of choosing the right prices!

But let's go back to 1939. They say that truth is distributed as heresy... Alas, this is also an accident with the ideas of L. V. Kantorovich in the field of economics. They did not meet the concept at the time of their inception, were declared heresy, and his work was converted.

Leonid Vitalievich's concepts were rediscovered in the West shortly after the end of the war. For many years, the American economist T. Koopmans attracted the attention of mathematicians to a number of problems related to military topics. He actively contributed to the formation of a mathematical team to develop these problems. As a result, it was realized that it was necessary to learn how to solve problems of finding extrema of linear functions on polyhedra defined by linear inequalities. At the suggestion of Koopmans, this branch of mathematics was called linear programming.

The American mathematician D. Danzgg in 1947 developed a very effective concrete method for numerically solving linear programming problems (it was called the sumplex method). The ideas of linear programming spread rapidly throughout the world within five to six years, and it was Koopmans and Danzgg who became widely known everywhere.

Around this time, Koopmans learned that even before the war, something different had already been done in distant Russia.

similar to the development of the beginnings of linear programming. How easy it was for Danzgg and Koopmans to ignore this information! A small book, published with an insignificant amount of money, addressed not even to economists, but to production organizers, with a minimum of mathematics, without clearly described algorithms, without demonstrative theorems - in a word, is such a book worth taking into account... But Koopmans insists on the translation and publication of Kantorovich’s book in the West. His name and ideas become known to everyone. Let us pay tribute to the nobility of the American scientist!

And Leonid Vitalievich himself - how natural it would have been for him, having experienced the first crippling blows of the retrogrades, to renounce the “sins” of his youth, to forget about all this economics and return to mathematics. But L. V. Kantorovich continues to write mathematical works, explicitly based on economic ideas, and also participates in specific developments in production. At the same time (simultaneously with Danzgg, but without knowing his work) he developed a method, later called the modified simplex method. As soon as a small gap formed in the 50s and some of the previously forbidden things became possible, he organized a group of students at the Faculty of Economics of Leningrad State University to study the method of optimal planning. And the year 1960 begins, Leonid Vitalievich deals only with economics and related mathematical problems. His inclusion in these areas was awarded the Lenin Prize in 1965 (awarded to him jointly with V.S. Nemchinov and V.V. Novozhilov) and, as already mentioned, the Nobel Prize in 1975.
