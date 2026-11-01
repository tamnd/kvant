---
id: 1978-6-gabovich-zadacha-kommivoyazhera-10e07fa2
issue: kvant_1978_6
year: 1978
number: "6"
title: Traveling salesman problem
authors:
  - Габович Е. Я.
rubric: osnovnye-stati
page_first: 13
page_last: 22
page_labels: 11, 12, 13, 15, 16, 17, 18, 19, 20
tag: FRSF
lang: en
source: kvant_digital
extraction: vision
content_sha256: b9915931619cda5ad634d931538a5cbf3c2013377921a0f169861552afaf942c
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/03_gabovich-zadacha-kommivoyazhera-10e07fa2.md
source_content_sha256: 2b1e15e33b5a24ce2b54c92f93b63c7591c40f2ae90784a032fa734b814bdfc5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

E. Gabovich

Task
traveling salesman

“Use the services of Aeroflot!”
Two cars, engineer A. Nevsky and economist B. Liteiny, decided to go to Transcaucasia, visit Baku and Tbilisi, stop by Moscow, Kyiv and Gorky, and then return to their native Leningrad. We started discussing the travel route. Nevsky looked at the map and suggested the following sequence of visiting cities:
L → M → G → B → T → K → L
Liteiny, having taken out a road atlas, wrote down the distances between the cities they needed in a table (see Table 1) and calculated the length of the proposed route:
696 + 410 + 2937 + 579 + 1863 + 1207 = 7692 km. “Too long! - he said. — Aeroflot distance! Is it possible to make it shorter? Are you sure this route is the shortest?
Nevsky did not have such confidence. Moreover, Nevsky could not explain why he decided to go this way. Simple intuition told him what such a route would be, if, etc.

Table 1

| City | L | M | TO | B | T | G |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Leningrad | — | 696 | 1207 | 3223 | 2797 | 1106 |
| Moscow | 696 | — | 858 | 2527 | 2101 | 410 |
| Kyiv | 1207 | 858 | — | 2283 | 1863 | 1268 |
| Baku | 3223 | 2527 | 2283 | — | 579 | 2937 |
| Tbilisi | 2797 | 2101 | 1863 | 579 | — | 2511 |
| Bitter | 1106 | 410 | 1286 | 2937 | 2511 | — |

⟦folio 12⟧

not shorter than all the others, then it is close to the shortest.

“Shouldn’t we look at all the routes? - suggested Liteiny. “Are there many of them?” He began to count. “From Leningrad you can go to any of five cities. If we go, say, to Moscow, then from there we can go to any of the cities other than Leningrad and Moscow. So, there are 20 trips of the form $Л \rightarrow X \rightarrow Y$, where $Л \neq X \neq Y \neq Л$. There are already 60 trips of type $Л \rightarrow X \rightarrow Y \rightarrow Z$, but from $Y$ you can go to any of the remaining three cities. If we choose $Z$, we can consider the next city after $Z$ to be either of the next two cities. So, 120 routes, or the journey ends unambiguously: on the way home the last of the six cities is visited. Lots of things! So this is not a method to try all the routes! After all, if we wanted to visit six cities, we would have 720, and if we wanted to visit seven, then we would have 5040 routes!”

“Then let’s do this,” Nevsky suggested, “let’s go from Leningrad to the nearest city, from there to the nearest one that has not yet been visited, etc. This gives us route $Л \rightarrow M \rightarrow Γ \rightarrow K \rightarrow T \rightarrow Б \rightarrow Л$. Its length, now calculated, is 8057 km. 365 km longer!”

Traveling salesman problem

The problem that Nevsky and Liteiny solve is known in mathematics as the traveling salesman problem *) (itinerant merchant).

Let's formulate it in general form: there are $k$ cities, the distances between which are known; the traveling salesman needs to leave one of these cities, visit the remaining $k-1$ cities, hitting each of them exactly once, and return to

*) Probably the first person to formulate the traveling salesman problem was the famous mathematician Carl Menger. This happened on February 5, 1930 at the mathematical coloquinum in Vienna. Menger used the famous "Messenger Problem".

Fig. 1.

source city; how to find the shortest route?

Obviously, the choice of the starting point of the route is unimportant - the traveling salesman’s problem can be formulated as follows: find the shortest closed route, passing through each of the $k$ cities once.

Exercise 1. Prove that the total number of traveling salesman routes is $(k-1)! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot (k-1)$.

Note that the table of distances compiled by B. Liteiny (mathematicians call such tables of matrices) turns out to be symmetrical with respect to the diagonal on which the line is drawn. The traveling salesman problem also allows for asymmetric tables. An asymmetric table of distances may arise, for example, in the following problem (about a circular bus route). In the city, on some city streets only one-way traffic is allowed, $k$ points (locations of future stops) are fixed. A closed bus line should pass through them. It is also required to find a cyclic sequence of passing the stopping point, in which each sequence occurs once and only once, and the entire route has a minimum length.

Exercise 2. In a plate of size $7 \times 9$, the laser beam must eat through slits in the directions indicated by figure 1 by arrows and return it to its original position. The task of minimizing the cold run of a laser head is a traveling salesman's task. Write down the distance matrix for it. (Note that it is not symmetrical.)

⟦folio 13⟧

From Exercise 2 we see that the “cities” in the commuting agent problem may not be cities at all, and the “distances” may not be settlements at all. For example, under “distance” between two cities you can try or continue traveling between them. In this case, the total cost of the trip or its duration is minimized, respectively.

Let's take another example of the camp problem. During processing on the mill, the part undergoes $k$ operation. When moving from one operation to another, the machine must be set up again, which leads to loss of time. It is required to find such an order for carrying out all operations (with the return of the machine to its original state) in which the total losses would be minimal. It is clear that here we are dealing with the commutator's problem - with a table of time lost for rebuilding the machine as a distance matrix. “Cities” are the state of the machine after various operations.

The problems of production planning and design of linear communication (say, a telephone network), the problem of drawing up a route for a postal worker (doctor, pay phone controller, etc.) and even some computer design problems lead to the problem of a commuting driver.

Complete search

So, in each specific traveler problem, it is required to find the shortest tour for a given distance matrix. It's possible that by chance

| Transaction number | I | II | III | IV | V |
| :--- | :--- | :--- | :--- | :--- | :--- |
| I | — | 0 | 11 | 5 | 20 |
| II | 31 | — | 0 | 52 | 8 |
| III | 9 | 16 | — | 0 | 41 |
| IV | 64 | 31 | 61 | — | 0 |
| V | 0 | 93 | 19 | 7 | — |

this will be extremely easy to do. For example, if transfer losses in the mill problem are given by Table 2, then it is very likely that the optimal sequence of operations is: $I \rightarrow II \rightarrow III \rightarrow IV \rightarrow V \rightarrow I$ (with zero total transfer time).

Exercise 3. Solve the commuter problem from Exercise 2 if you know that during the troublesome stroke the laser head can only move parallel to the edges of the plate.

However, most of the time there are no obvious solutions for specific distance tables. And even if someone tells us which route is the shortest, it may be more difficult when we want to check whether this is actually the case.

Mathematicians are interested not so much in solutions to specific commu-voger problems, but rather in general solutions to all such problems (or at least all commu-voger problems for $k \leq m$, where $m$ is some fixed number).

Note that in each specific commutator problem it is possible to carry out all the routes, of course. Therefore, you can organize a complete search of all routes, calculate their lengths and select the shortest route. This kind of exhaustive search is, in principle, a general method for solving the commu-voger problem.

However, let us remember Nevsky and Liteiny. Although they had to draw a closed route through only six cities, they did not want to go through all 120 turii (however, they did not automatically notice that, due to the symmetry of Table 1, only 60 turii have different lengths). In the general case, the commutator has to choose the shortest of $(k-1)$! possibility of routes. This number grows very quickly as $k$ increases, and therefore the indicating method of solution for large values ​​of $k$ is practically not applicable. Thus, the author knows of an example where 4 hours and 45 minutes were spent on the M-220A computer to carry out an exhaustive search in the problem of a commuter with ten cities $(k=10)$! Fast

⟦folio 15⟧

Experiments have shown that without using the specific properties of each specific communicator task, there is a computer and methods for solving integer linear programming problems make it possible to cope with the communicator task only if necessary in the number of cities (not exceeding ten). At the same time, the most recent work in this area shows that reduction to an integer linear programming problem can be effectively used in combination with another method for solving the communicator problem - the branch and bound method.

Branch and bound method

Currently, the best method for solving the communicator problem is the limited enumeration method, or the branch and bound method. It is used in several modifications with varying effectiveness.

Carrying out a complete search, we can, of course, write out all the tours one after another. You can do it differently: draw a tree of possible trips. For the case of four cities, it is shown at figure 2. In circles are the city numbers; The arrows indicate trips. It is clear that when moving to the trip tree, the number of arrows decreases compared to their number in the record of all routes (at $k > 3$). For example, when writing out all the routes in a row, the arrow I → II would have to be drawn twice. But we will achieve even greater savings if we build not the entire trip tree, but only some of it. Such a truncated tree is named, which differs from the tree of all trips by the absence of those branches that cannot give the shortest route, and is constructed in the version of the branch and bound method presented below.

Let us describe the sequence of stages of such a method for solving the communicator problem (the flow diagram of the described algorithm is shown in figure 3). Complete the stage, move on to the next one, unless otherwise instructed.

1. We draw the root vertex of the tree (for definition, we will assume that it corresponds to city I). We assign it a rating of 0.

2. We branch from any vertex with a minimum score (initially from the root). This means that we draw from the selected vertex all those arrows that would emanate from it in the tree of possible trips, and draw the corresponding vertices of the tree.

3. We assign each new vertex a score equal to the length of that part of the route that is described by arrows leading from the root vertex to this one.

⟦folio 16⟧

Fig. 3.

4. If a vertex corresponding to city I is obtained, then we find
Dim the length G of the shortest obtained
tours available to this point. If not,
go to stage 2.

5. We cut off all the vertices from which branching has not yet been carried out (end vertices) and estimate the co-
of which no less than G. This means that branching from such vertices will not be carried out in the future. If not everything is over -
the last vertices are cut off, go to stage 2. If everything is done, then the solution problem: the optimal tour has length Г and is restored from the end vertex with which the last value of Г was obtained (see stage 4).

Stage 2 describes the branching rule, stage 3 describes the evaluation procedures, stage 4 describes the bounds, and stage 5 describes the pruning procedures.

Let us solve the traveling salesman problem using the branch and bound method with the distances given in Table 3.

The solution is given at figure 4. Per-
The last four branches are shown with green arrows. We assign G a value

Г=8 and cut off two vertices. The fifth branch corresponds to the blue arrow. Of the two end vertices with a minimum score of 4, we chose the one that is farther from the root (in the hope of getting another round faster and reducing the value of G). The following branches are marked with red arrows. Teleri G=5, and we cut off all other end vertices. The solution is round I→II→III→IV→I of length 5.

The described version of the branch and bound method allows you to solve the traveling salesman problem with k≤20 on a computer. It is clear that it always leads to the shortest tour, or it uses a tree of possible

Table 3

N I II III IV

I — 4 0 9

II 5 — 0 3

III 6 4 — 1

IV 0 2 6 —

⟦folio 17⟧

trips, and only those branches are discarded that obviously cannot give shorter tours than those already found.

You can cope with a hundred cities!

In 1963, a very successful version of the branch and bound method was published, in which, when calculating estimates, a number was added to the length of the already completed part of the route, estimating the length of the rest of it. The branching rule in this method (its author is Katta Murthy, an American mathematician of Indian origin) is such that with each branching, two new branches are formed *). Murthy's method made it possible to solve the traveling salesman problem for $k \leq 40$ on a computer in a relatively short time.

Later, another version of the branch and bound method was developed (the Eastman-Shapiro method). Using this method, it was possible to solve several traveling salesman problems for $k \leq 70$. Further development of the Eastman-Shapiro method made it possible to increase the size of the problem solved on a computer to 100-120 cities.

The Eastman-Shapiro method for calculating estimates uses the fact that there are efficient machine methods for solving the so-called assignment problem *), closely related to the traveling salesman problem. In essence, the assignment problem is formulated as follows: there are $k$ people and $k$ positions, and the matrix of points of mismatch between people and positions is known. It is required to find an assignment of workers to positions that minimizes the sum of inconsistency points. Here the point matrix plays the same role as the distance matrix in the traveling salesman problem. And appointments, like pozedki, can be written in the form $x \rightarrow y$. The only difference is that the destinations do not necessarily form a closed route (tour). It is possible, for example, such an appointment $I \rightarrow V \rightarrow I$, $II \rightarrow II$, $III \rightarrow IV \rightarrow VI \rightarrow III$ (this means that the first person will be appointed to the fifth position, the fifth to the first, the second to the second, the third to the fourth, etc.).

So, each round can be considered an appointment (but the appointment of $k$ persons

*) For a description of the Murthy method, see, for example, in the brochure by V. I. Mudrov “The Traveling Salesman’s Problem”, M., “Knowledge”, 1969.

*) The assignment problem was described in the article by M. I. Reitman “Transport Problem” («Kvant», 1974, No. 7).

Fig. 4.

⟦folio 18⟧

It turns out to be a tour on average only in one of the $k$ cases: after all, there are ($k-1$!) tours, and the total number of $k$-assignments is equal to $k!$. Therefore, the sum of points for the optimal $k$-assignment does not exceed the length of the optimal type. And, as we have already noted, the computer finds this amount of points relatively quickly. This is what he uses as an estimate in the Eastman-Shapiro method, in which not a tree of actions is built, but a completely different tree, the vertices of which are auxiliary assignment problems (an example of such a tree is shown in figure 5).

In this method, the assignment problem is first solved with the distance matrix of the communicator problem as the scoring matrix. It corresponds to the root vertex of the tree. The sum of the points for the optimal assignment is considered to be the score of the root node (and the original communicator task). If the solution is a tour, then the communicator's problem is solved: the found tour is optimal. If the $k$-assignment consists of several cyclic sequences, for example, $I \rightarrow III \rightarrow VII \rightarrow V \rightarrow I$, $IV \rightarrow VI \rightarrow II \rightarrow IV$, then since the optimal type cannot have “subtours”, all these cyclic sequences must be broken. In the Eastman-Shapiro method, this is done during input, and one, the shortest, sequence of assignments always works, so that in the future a smaller number of new assignment problems can be solved.

In our example, it is the second; it includes three cities: $II$, $IV$ and $VI$. We impose bans on the positions $IV \rightarrow VI$, $VI \rightarrow II$ and $II \rightarrow IV$, after which we solve three new assignment problems with trays of new score matrices obtained from the matrix corresponding to the root vertex: in the first of them the element $c_{46}$, in the second - the element $c_{62}$, and in the third - the element $c_{24}$ is replaced by the symbol $\infty$, we will inform you in detail about the prohibition of the corresponding pose (via $c_{ab}$ we again indicated the distance between the cities $a$ and $b$). If there are tours among the solutions, then $\Gamma$ is assumed to be equal to the length of the shortest of them. Problems with a score less than $\Gamma$ are “cut off”. The next introduction is carried out for that one of these problems for which the $k$-assignment is not a round, and the score (the sum of the discrepancy points) turns out to be the smallest.

Let us comment on the solution process, the diagram of which is shown in figure 5.

Two introductions were made and six assignment problems were solved. The solution to problem 4 turned out to be a cycle. From this moment on, $\Gamma = 44$, and tasks with a score of 45 and 44 are cut off.

The solution to Problem 3 involved assigning $IV \rightarrow V \rightarrow IV$. The second introduction led to two new problems: 5 and 6. The solution to problem 5 is a cycle of length 42. This new value of $\Gamma$ allows cutting.

Heuristic methods

If the communicator problem could not be solved exactly, they would try to solve it approximately. In this case, a route is sought that is relatively slightly different from the shortest one. Methods for finding such routes are usually approximate, suboptimal or heuristic.

Suboptimal is, for example, the “go to the nearest” method, i.e. to the closest of the untraveled

⟦folio 19⟧

childbirth It is easy to see that this method is not accurate using the following simple distance matrix (see Table 4).

For her, the “go to the near” procedure gives a route I→III→II→I of length 10, while the nonlenian procedure “go to the far” results in a tour I→II→III→I of length 8. Since the communication currently has no other routes, this example means that our heuristic method can sometimes give even the flattest of tours.

However, the “go to the nearest” aim (and other heuristic methods) is often used in practice - especially when solving the problem of communication with a very large number of cities. This is done according to several principles. Firstly, this method works quite quickly. Secondly, practice shows that as $k$ increases, the “go to the closest” method increasingly produces tours whose length differs slightly from the length of the shortest tour (and, sometimes, coincides with it). And, finally, a circumstance common to all heuristic methods: in many practical problems we are not interested in the best solution, but only in a fairly good approximation to it (after all, sometimes the distances between cities are not determined quite accurately). In addition, the accuracy of the “go to your neighbor” algorithm increases (but the labor intensity also increases) if in the course of its work $k$ rounds are built, the first of which begins to be constructed from the first city, the second from the second, etc.; Some of these tours may be different, and in the end the shortest one is selected.

For the task of the traveling salesman, many effective heuristic methods have been created. In particular, branch and bound methods have proven themselves to be quite good; their work stops at one of the found types (not necessarily the optimal one). Thus, in 1976, two Japanese mathematicians solved the problem of a traveling salesman for 300 cities on the HITAC-8800 computer. At the same time, a solution was found in 2 minutes, differing from the optimal one by 0.2 percent.

Amazing country

Let's imagine that A. Nevsky and B. Liteiny, already familiar to us, decided to travel around a small country (let's call it Constantius). Having arrived in its capital and having found the seven most interesting cities of Constantia on their journey, they plan the route of their train. This time, the distances between cities were not only large (see Table 5). Therefore, the friends decided not to chase the minimum, but to calculate the lengths of several randomly taken tours and choose the shortest of them (this procedure is also a suboptimal method, known as the *Monme-Karlo method*). The choice fell on the following tours:

I→II→III→IV→V→VI→VII→VIII→I;
I→III→VII→II→IV→VI→VIII→I;
I→IV→VII→II→V→VIII→I.

We calculated their length; It turned out that all three tours are 794 km long! Having become interested, our

⟦folio 20⟧

the heroes analyzed ten more routes. Each of them was 794 km long! You can imagine how embarrassed our heroes were. But their surprise would be even greater if they knew that for a given distance matrix, all tours in general have the same length.

Why? The opening of the casket is simple: all the numbers 5 are obtained by adding together the numbers 48, 55, 66, 38, 61, 42, 50 and 37. For example, in the third line the sums are 66+48=114, 66+55=121, 0, 66+38=104, etc. And since when calculating the length of the route we take one at a time and only one number from each row and from each column of Table 5, then as a result the length of any type turns out to be equal to twice the sum of the intended numbers (the sum of the eight intended numbers is 397, and 794 = 397 × 2).

The question arises: is it not possible to describe all distance matrices in which any two rounds have the same length? It turns out that it is possible: for any such matrix it is necessary to find the numbers $a_1, a_2, \dots, a_k$ and the numbers $b_1, b_2, \dots, b_k$ such that the distance $c_{xy}$ from the city $x$ to the city $y$ ($x \neq y$) will be equal to the sum $a_x + b_y$.

Let us prove this theorem for the case of three cities.

Let $c$ be the length of each of the two rounds:
$$c = c_{12} + c_{23} + c_{31} = c_{13} + c_{21} + c_{32}.$$
Let us express $c_{31}$ and $c_{32}$ from these relations:
$$c_{31} = c - c_{12} - c_{23},$$
$$c_{32} = c - c_{13} - c_{21}.$$
We need to solve the system of equations
$$x_1 + y_2 = c_{12}, x_1 + y_3 = c_{13},$$
$$x_2 + y_1 = c_{21}, x_2 + y_3 = c_{23},$$
$$x_3 + y_1 = c - c_{12} - c_{23},$$
$$x_3 + y_2 = c - c_{13} - c_{21}.$$
We give the unknown $y_3$ an arbitrary value $d$. Then from the first five equations it is found that $x_1 = c_{13} - d, x_2 = c_{23} - d, y_2 = c_{12} - c_{13} + d, y_1 = c_{21} - c_{23} + d,$
$$x_3 = c - c_{12} - c_{23} - c_{21} + c_{23} - d = c - d - c_{12} - c_{21}.$$
In this case, the sixth equation is also satisfied. Putting $d = 0$, we get a set of $a_1 = c_{13}, a_2 = c_{23}, a_3 = c - c_{12} - c_{21}, b_1 = c_{21} - c_{23}, b_2 = c_{12} - c_{13}, b_3 = 0$ numbers with the property we need.

The theorem formulated above is quite typical for theoretical studies on the assignment of a traveling salesman. Various special cases play an important role in them. (The coincidence of the lengths of all tours is also a special case. However, the weights are narrow.) For special cases, it is sometimes difficult not only to construct a fast-working method (in this case we speak of a solvable case), but also to find out what lengths an optimal tour can have.

The reader can continue to explore solvable cases of the traveling salesman problem by solving the problems below. In some of them, decide to travel on a chessboard, where chess pieces act as a traveling salesman. In this case, we will not talk about the type of traveling salesman, but about the type of knight, rook, etc. The tour of the chess piece continues once along all the squares of the chessboard and ends with a return to the initial square.

Exercise
1. Cities are located at the vertices of a convex polygon. Prove that the length of the optimal type is equal to the perimeter of the polygon.
2. Does the task of a traveling salesman reduce to the task of finding the shortest route for a tourist who leaves from point 1, follows points 2, 3, ..., $k-1$ and leaves the country from point $k$? The same question for the problem of minimizing the path of the messenger, which is sent from point 1 to points 2, 3, ..., $k$. Is this reduction possible for the problem of saboteurs who, in order to blow up objects located at points 1, 2, ..., $k$, plan a decanting location and the shortest route through all points?
3. There are 30 cities on the plane. Their coordinates: $y = 0, 1, 2$ at $x = 0; y = 0, 1, 2, 4, 5, 6$ at $x = 1; y = 1, 2, 3, 4, 6, 7, 8$ at $x = 2; y = 0, 1, 3, 4, 6, 7, 8$ at $x = 3; y = 0, 1, 2, 3, 4, 5, 6$ at $x = 4$. Solve the traveling salesman problem. Prove that the resulting tour is optimal.
4. At what size of the chessboard is there a rook turn on it? Tour of a weakened rook that only moves to neighboring squares?
5. On a chessboard with an odd number of squares, one square is cut out. For what decompositions of a cut square is there a tour of a weakened rook?
6. Find the knight's turn on a spatial "board" in the shape of a rectangular parallelepiped of size $3 \times 4 \times 6$. “Fields” are now considered to be 72 cubes of a unit volume, on which our “board” is naturally divided.
7. Given numbers $k$ and $m$. How to construct a distance matrix for the traveling salesman problem with $k$ cities whose solution was a tour of length $km?$
