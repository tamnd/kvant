---
id: 1989-3-geyn-kovaldzhi-sapir-zadachi-modeli-i-evm-7e23779a
issue: kvant_1989_3
year: 1989
number: "3"
title: Tasks of the model and computer
authors:
  - Гейн А. Г.
  - Ковальджи А. К.
  - Сапир М. В.
rubric: raznoe
rubric_sub: Разное
page_first: 61
page_last: 66
page_labels: 59-64
tag: RMQH
lang: en
source: kvant_digital
extraction: vision
content_sha256: b3bea7c62c6c556178b81023e7496e5fb1c67ccddd448e8b9b3ef0750ca9f0d5
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/18_geyn-kovaldzhi-sapir-zadachi-modeli-i-evm-7e23779a.md
source_content_sha256: 3a2a0542171a9703e8ca3d6a145cbcabade652f479cb64ada31e2f766aac173d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Tasks, models and computers

Candidate of Physical and Mathematical Sciences
A. G. GEIN,
A. K. KOVALDZHI,
Candidate of Physical and Mathematical Sciences
M. V. SAPIR

Surely all readers «Kvant» know that the computer has a fantastic counting speed, freeing us from cumbersome and tedious calculations. At the same time, you constantly hear about how computers are used to create decisions and manage production, to draw cartoons and search for representatives, that is, to solve problems that seem to have nothing to do with calculations. How does this work? After all, there is an obvious contradiction here! And indeed it is a contradiction. Libra is not easy to overcome. How to use computers to solve non-computational problems will be discussed in a series of articles, which begins in this issue «Kvant».

Remember, in N.A. Nekrasov’s poem it is described how to gather the men of the surrounding villages to discuss who should live well in Rus'? In those free times, they could not do anything to make their life easier: all social issues were decided for them by the household. Now not a single social issue can be resolved without broad discussion. This is one of the tasks that often comes with being a planning authority.

Problem. Several settlements are located in one diet. A railroad runs through the area. When the area gets excited, it is planned to build a railway station and extend roads from it to each settlement. It is required to determine the most convenient location of the railway station.

figure 1 shows a map of the area (we retained the Nekrasov village names). So imagine that you are working as a program

⟦folio 60⟧

in the district executive committee and you are instructed to solve this problem using the services of a computer. What is needed for this? First of all, you need to remember: a computer can’t do anything else but carry out your instructions and algorithms, and then only if they are formulated in a language it understands. And to compose an algorithm, you need to know what is given, what needs to be obtained, how the initial data and results are related, as well as what commands can be used. In other words, the task must be clearly formulated.

Let's put aside our railway problem for a moment and talk about the formulation of the problem.

Statements of objectives

It is only in school tasks that it is immediately clear what is given and what is required to be received. Everything in life is more complicated. Experience literally screams about how difficult it is to correctly set the task: not to over-forgive and not to re-add, not to miss important initial data and not to include unnecessary ones, to balance what is possible with what is possible.

Let's say that you decided, as an individual labor activity, to organize an apartment exchange office. Your task is to select an exchange option for each received application that satisfies all interested parties. Try to formulate this task clearly. Many questions immediately arise: what parameters of the available and required living space should be taken into account in the application (number and area of ​​the room, their relative location, area of ​​the kitchen and other utility rooms, year of construction of the house, floor, availability of an elevator, distance from the city center, etc.)? Do you accept requests for lunch and exchange of apartments? Should the cost of a cooperative apartment be taken into account?

Or another task: create a lesson schedule at school. What are the input data for this task? This depends, of course, on the scheduling requirements. Require that two different lessons not occur at the same time in the same class? Then there will be little initial data: a list of educational subjects for grade levels in each parallel. At the same time, however, it may be that one class of a subject is taught only mathematics, another only geography, and a literature teacher is unlikely to be happy if he is assigned to teach physics lessons. Try to clearly formulate the task of creating a school schedule yourself. We think that after this you will sympathize with the difficult work of the head teacher, who solves this problem every six months.

These two examples are probably enough to understand: setting a problem is an important part (sometimes they say half) of its solution. When setting a problem, it is necessary to formulate those assumptions that will allow us to extract the initial data from the sea of ​​​​information about the object under study, determine what the result will serve and what is the connection between the initial data and the result. All this - assumptions, input data, results and connections between them - is called a problem model.

It is not always clear in advance which properties of an object are essential for solving a problem. Let's say this is an old problem.

With two blows of the axe, cut the horseshoe into as many pieces as possible, without rearranging the piece after the blow.

Let's formalize the problem. We can immediately formulate the following assumptions: the blow of the ax is a straight cut, the horseshoe is some kind of arc, the parts of the horseshoe after the blow remain

⟦folio 61⟧

are in place and do not deform. This means that you need to draw an arc and cut it with two straight lines. We have clearly set the task, and it is not difficult to make sure that more than a fifth of the part will not work out (Fig. 2).

However, in the book by E. I. Ignatev “In the Kingdom of Ingenuity” (M., Nauka, 1982), in a similar problem it is necessary to cut a horseshoe into six parts and another figure (Fig. 3; good when there is an answer!) is given. It turns out that we were too abstract and did not teach that a horseshoe also has width. So, in our model we need to replace the assumption that a horseshoe is an arc with this: a horseshoe is half a ring.

However, continuing in the same vein, we can say that the horseshoe also has a thickness (Fig. 4), and then the dar toropa has a flat cut. How many pieces can a horseshoe be divided into, taking into account the thickness? We got 7 parts.

Exercise 1. Using two udarami toropa, cut the horseshoe into 7 pieces.

Or maybe the answer is actually even greater? WHAT else should I take into account? Of course, holes! After all, the horseshoe has holes for nails (Fig. 5). It’s hard to believe the success, but it turns out to be 11 parts!

Exercise 2. Using two udarami toropa, cut the horseshoe into 11 pieces.

So, due to a more complete description of the object, it is possible to more than double the initial result! It is interesting that each new approach of the model to reality led to a clearly defined problem with an unambiguous answer.

As you can see, the problem significantly depends on the initial assumptions, and the more properties of an object we learn in the model, the more complex the solution. However, not always, having folded the model, we will get a new result. Let's add up, those who have seen a horseshoe know that the horseshoe does not have two holes, but more (see Fig. 6). However, increasing the number of holes in a real horseshoe may not affect the answer to the problem.

Exercise 3. Prove that the horseshoe chosen at figure 6 cannot be cut by two blows toropa into more pieces than the horseshoe at figure 5.

The art of drawing up a model lies precisely in taking into account all existence in it without overcomplicating the model and discarding what is unimportant.

Fig. 2.
Fig. 3.
Fig. 4.
Fig. 5.
Fig. 6.

⟦folio 62⟧

Isn’t this what any art consists of, be it painting or sculpture? And in general, please, every form of art is engaged in creating a model of life that uses expressive means.

And one more conclusion can be drawn: if we replace a life task with its model, then the answer relates to the model, and only indirectly to the original task.

So, creating a good model of a problem is not an easy task. Next, solve this problem by presenting it to you yourself. What if the problem needs to be explained to the computer? In this case, you will have to take into account the “abilities” of the computer, or more precisely, the capabilities of the language in which you will explain to it. If your computer only has to calculate, then when expressing ideas about an object, you need to make sure that the initial data and results are numbers, and the connections between them are mathematical correspondences. Perform such a “translation” of the problem into the language of mathematics, you will receive a model that is promised to be called a mathematical model.

Mathematical models

Now we can return to our station problem. Let's start, naturally, with building a mathematical model. First of all, we express our ideas. We will assume that the section of the road passing through the territory of the district is straight; a station can be built anywhere on the section and connected by straight roads to each settlement $A_1$, $A_2$, ..., $A_n$.

Now we need to understand the words “the most convenient location of the station.” How to understand this? If you strive to save money on road construction, then the station must be located so that the total length of roads connecting the station with populated areas is the smallest. If we strive for maximum fairness, then choose the location for the natural station so that the distance from it to populated areas is as short as possible. For example, if a person falls ill in the settlement farthest from the station, then he must be transported to the station in the shortest possible time.

We are for justice, and therefore we will avoid the second principle.

Exercise 4. a) Show that these two causes lead to different results.

6) How should two settlements be located so that these causes produce the same results?

Research task. Solve exercise 4 b in the case of an arbitrary number of settlements.

Assumptions have been made, we will determine what will be the initial data and what will be the result in our mathematical model. Fortunately (or rather, intentionally), the assumptions are such that we can easily translate our problem into the language of numbers. To do this, draw the coordinate axes on the map of the area so that the abscissa axis passes along the railway node of interest, and the origin of coordinates coincides with its left end. The data we use, of course, is the number $n$ of settlements, their coordinates $(a_1; b_1), (a_2; b_2), ..., (a_n; b_n)$ or $S$ of the railway that ran through the area. The result is the abscissa of the point where the station should be built (Fig. 7).

It remains to find correspondences between the populated data and the result.

⟦folio 63⟧

Let's take any point on the segment and depict a railroad. Let $t$ be its abscissa. Let $Z$ denote the maximum distance between this point and each of the settlements:

$$Z = \max \left\{ \sqrt{(t-a_1)^2 + b_1^2}, \right. \\
\sqrt{(t-a_2)^2 + b_2^2} ; \dots ; \sqrt{(t-a_n)^2 + b_n^2} \}.$$

It is clear that $Z$ is a function of $t$. To determine where to build a station, you need to find out at which $t$ from the segment [0; $S$] function $Z(t)$ takes the smallest value.

As you can see, we replaced the original station problem with a mathematical problem: find the minimum point of a certain function. This problem is a mathematical model.

How to find the minimum point? It would be desirable, of course, to try to take an arbitrary function $Z(t)$ and equate it to zero. They face many difficulties: the function $Z(t)$ cannot be given by a simple formula, and an arbitrary function of it most likely does not exist at all points. Let's try to imagine the graph of the function $Z(t)$.

Difference 5. Select arbitrary coordinates of several trees, as well as the length of the railway segment, and using a computer or microcalculator, construct (point by point) a graph of the function $Z(t)$.

It is easy to verify that the function $Z(t)$ first kills and then increases. We are lucky: our function has only one minimum point. It can be found with any accuracy using the following method. Let's split the segment [0; $S$] into equal parts, the length of each of them is denoted by the letter $r$. Then we find the values ​​of $Z$ at $t=0, r, 2r, \dots$ and so on until $t=S$. Let us choose the smallest of these values ​​and replace the result $t$ at which it is achieved. This value $t$ will differ from the “true” result by no more than $r$.

So, we replaced the complex task of finding the minimum point of a low-spicy function with the simple task of finding the minimum of several numbers.

The following is simplicity of precision. The result is obtained only by approximation: the smaller $r$, the more accurate. However, there is no point in pursuing particular accuracy - after all, in reality, the railway is not straight, and the coordinates of the trees are known only approximately, and the Earth, as we know, is not flat, and most importantly, both the station and the villages are not points.

True, using geometric constructions, it is possible to find an “exact” solution.

Exercise 6. $n$ points and a segment are given on the plane. Using only a compass and a ruler, find a point on the segment such that the distance from it to the given points is the smallest.

The choice of initial proposals for the mathematical model of the station problem may be influenced not only by the desire for justice, but also by some economic factors, for example, a lack of funds for road construction. Then the principles for finding a location for a station will be as follows: the sum of the distances from the station to populated areas should be minimal.

Exercise 7. Create a mathematical model of the station problem based on this principle.

Research task. $n$ points and a segment are given on the plane. Construct a point on a segment such that the sum of the distances from it to the given points is minimal.

So, when creating a mathematical model to solve a problem, you need to:

1) highlight the proposals on which the mathematical model will be based;
2) determine what is considered input data and results;
3) write down mathematical correspondences (formulas, equations, inequalities, etc.) connecting the results with the original data.

As you can see, a mathematical model is always based on some principles. However, thanks to the replacement

⟦folio 64⟧

of a given object with its corresponding model, it becomes possible to formulate the problem of its study as a mathematical one and use the means of mathematics to solve it.

The model is built. What's next?

The creation of a mathematical model completes the first stage of solving a problem using a computer. Next you need to write the appropriate program. We will not tell you how this is done - it depends on the capabilities of a particular computer and the languages ​​​​implemented on it. But then you need to make sure that the model matches the real object. Such confidence can only be achieved through experimentation. When performing calculations on a computer, it is necessary to analyze the results. In this case, it may be necessary to clarify the mathematical model, because it becomes clear that during its development any essential properties of the object were not taken into account. Refine the model, compose the program again, continue calculations on the computer and analyze the results. And again it may require taking into account the model. This will continue until the analysis of the results shows their correspondence to the object being studied.

After you have ensured that the mathematical model corresponds to reality, you can conduct computational experiments using a computer. In this case, you can cook the values ​​of the initial data, study extreme situations, determine the limits of applicability of the model, etc. The computer, thus, allows you to replace a natural experiment, often expensive and dangerous, with a safe and relatively cheap computational experiment. This, perhaps, is the main advantage of a computer.

Exercise

1. Compose a mathematical model of the problem of a railway station, guided by the compromise principle: if $Z$ is the distance from the station to the most distant point, and $W$ is the sum of the distances to all points, then you need to make the sum $kZ+(1-k)W$ as small as possible, where $k$ is a number from the segment [0; 1] (degree of compromise).

2. Study the problem of a railway station for two settlements, one of which has 1000 people, the other 2000, guided by the following principle: the total number of “person-kilometers” spent by the population on the way to the station should be the smallest.

3. A schoolboy who does not know integral calculus compiled the following mathematical model for finding the perimeter of an arbitrary climb.

Assumptions: we consider the climb to be a flat figure; if you divide the boundary of the climb into a large number of small sections and connect the splitting points sequentially, then the perimeter of the resulting polygon differs little from the perimeter of the climb, and the smaller the split, the more accurate the result.

Complete the construction of the mathematical model.

4. A schoolboy who does not know the Pythagorean theorem compiled the following mathematical model to determine the length of the diagonal of an arbitrary rectangular table.

Assumptions: consider the table surface to be a rectangle from sides $a$ and $b$; the length of the diagonal $d$ is approximately equal to the length of the broken line shown in figure 8, if, of course, the steps of this broken line are small enough; with an unlimited increase in the number of steps, the diagonal value is obtained with any accuracy. Then $d=a+b$ (indeed, the length of the broken line is exactly equal to $a+b$, regardless of how many steps it has).

Why was the result incorrect: the diagonal of a rectangle is equal to the sum of its adjacent sides?

Topics of computational experiments (for the program)

Compose programs that correspond to the distances in the stat model of the railway station problem. See how the location of the station changes when the number $k$ in Problem 1 changes and when the number of partition segments increases.
