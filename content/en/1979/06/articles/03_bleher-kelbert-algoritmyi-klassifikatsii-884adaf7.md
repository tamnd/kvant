---
id: 1979-6-bleher-kelbert-algoritmyi-klassifikatsii-884adaf7
issue: kvant_1979_6
year: 1979
number: "6"
title: Classification algorithms
authors:
  - Блехер П. М.
  - Кельберт М. Я.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
tag: 79U4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5024437ba7164d159f1e35d4127ca953f1ed3a070a9c125174ca0890a0fb9b6c
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/03_bleher-kelbert-algoritmyi-klassifikatsii-884adaf7.md
source_content_sha256: 254160ba9dc8bd14f5ef6259b22eb3e04f5cad349ba569850809f384a4e62563
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

P. Blecher, M. Kelbert

Classification algorithms

In this article we will talk about one of the sections of a science that emerged not so long ago - the theory of pattern recognition *). Namely: we will talk about classification methods. Classification is the division of a certain set of objects into groups of objects that are close in some sense. You can classify, for example, factories in a given industry that were observed in some regional earthquake, September weather for many years, extinct lizards, etc. It is only important that the objects being classified are characterized by a certain set of numbers and characteristics. For simplicity, we will consider the case when each object is described only by a set of numbers.

*) For those who want to get acquainted with it in use, we advise you to read the fascinating, although not very simple book by M. M. Bongard “The Problem of Recognition” (M., “Hayka”, 1967).

How to classify schoolchildren?

Suppose we want to divide all ninth-grade students of a given school according to how they use their out-of-school time. We ask each student to write down what part of this time he spends on lessons and what part on entertainment. The remaining time (for food, sleep, transport, etc.) is not of interest to us now. As a result, each student will be characterized by two numbers: time for lessons and time for entertainment. Therefore, it can be represented by a point on the coordinate plane. Thus, we come to a purely mathematical question: how to divide a given set of sets into groups of similar numbers?

Many gray applied problems lead to the same question, only in them the number of city coordinates is larger (on the order of several tens).

For example, there are a huge number of enterprises in the textile industry. Among them there are

⟦folio 3⟧

and specialized factories with a small range of products, and plants producing a variety of products. There are giant factories, there are medium-sized factories, and there are also small local productions. In order to compare the detail of individual objects and plan their work, it is necessary to classify all these objects - dividing them into groups of similar objects. Enterprises are differentiated by their economic indicators. We will select among them several of the most important ones (for example, the cost of constructing individual items and the wage fund) and will classify them according to them. The number of selected indicators will be denoted by $n$.

Let us associate each object with a set of numbers $(x_1; \dots; x_n)$, where $x_1$ is the value of its first indicator, $x_2$ is the value of its second indicator, etc.

A pair of numbers $(x_1; x_2)$ defines a point on the plane, a triple of numbers $(x_1; x_2; x_3)$ defines a point in space, and a sequence of $n$ numbers $(x_1; x_2; \dots; x_n)$ is by definition considered a powerful $n$-dimensional space.

Thus, this time we come to the problem of classifying points in $n$-dimensional space.

It's difficult without cars

To solve classification problems, various algorithms have been developed that allow the use of computers. The need to use computers is caused by two reasons. Firstly, as a rule, there are a lot of objects, and processing all the data manually is simply impossible. Secondly, the classified objects are most often multidimensional.

If, as in the example with schoolchildren, there are only two coordinates and the number of objects is small, then a person can cope with the classification task no worse than a computer. Namely: he will look at a picture where points representing objects are depicted, and he will see clouds corresponding to the condensation of the point. Experiments show that all people do this in approximately the same way. This is due to the fact that they (people) involuntarily tend to ensure that points in one group are close to each other, and different groups are distant enough. If the number of parameters is equal to or greater, then the visualization messages are practically useless and the classification task becomes difficult for humans to understand.

Psychologists conducted the following experiment *. The subjects were given a set of cards with those numbers corresponding to the coordinates of points in space. Requirements to divide the points into two natural groups. In fact, there was a plane, looking at an angle to the coordinate osm, which divided all the points into two groups so that the distance from any point to this plane was quite large compared to the distances between points within each group. Most people by the value of one of the coordinates, which led to unnatural partitions; Almost no one could construct a correct partition.

Classification algorithms have been developed for points in multi-dimensional space. However, one of the criteria for the correct operation of these algorithms is the requirement that when classifying points on a plane, they give natural partitions - the same ones that people find.

Minimum length tree

We will now describe an algorithm for constructing a connection between a new system of segments connecting these points with a minimum sum of length (a system of segments is called connected if

*) This and some other similar experiments are described in the book by N. G. Zagoruko “Methods of recognition and their application” (M., “Soviet Radio”, 1972). In this book you can read in more detail about many questions, which we will only mention in passing.

⟦folio 4⟧

from any given point along segments of this system you can add to any other given point). For clarity, we will consider construction on a plane. In a multidimensional space, the algorithm is the same, but you can’t paint a picture.

So, the path on the data plane is $N$ points $A_1, \dots, A_N$. For simplicity, we will assume that all pairwise distances between points are different. Let's write down all the pairs of points $(A_1, A_2), (A_1, A_3), \dots, (A_{N-1}, A_N)$ and arrange them so that first comes the pair with the minimum distance between the points, followed by the pair with the second largest distance, etc. Now connect the first pair of points, then the second pair, etc. If, when drawing the next segment, a cycle appears (that is, from the system of already drawn segments, you can select several segments that form a closed broken line), then we will skip this segment and move on to the next one and etc. - until we go through all the segments. By construction, the resulting system of segments does not contain cycles. (A connected system of segments without cycles is called a *tree.*)

Problem 1. Prove that the constructed system of segments has the minimum length of all connected systems of segments connecting these points.

Problem 2. Prove that the same system of segments can be obtained by the following, as mathematicians say, pre-weined construction: we connect all pairs of points with segments and arrange these segments in decreasing order of their length; discard the longest segment, then the second longest segment, etc.; if, when discarding the next segment, the remaining segments do not form a connected set, then we will skip this segment and move on to the next one, etc. - until we have enumerated all the segments.

Problem 3*. Let there be a coincidence among the pairwise distances between points $A_1, \dots, A_N$. Let us arrange segments of equal length in an arbitrary manner and carry out the procedure described in the text or in task 2. Prove that the constructed system of segments has a minimum length independent of how the equal segments were ordered. Of course, in this case the system of segments of minimum length may not be unique.

The algorithm we described for constructing a tree of minimum length

relatively simple, but requires a lot of searching and, therefore, must be run by a computer. There are faster (but also more complex!) algorithms.

Grouping

After a tree Г of minimum length has been constructed, the partition of the set of points $A_1, \dots, A_N$ into groups is carried out by drawing out some segments included in this tree. Naturally, fairly long segments are drawn, but so that the points that fall into one group are located as closely as possible. This visual message can be formalized by entering the following quantities. Let us want to split the set of points $A_1, \dots, A_N$ into $k + 1$ groups. Let us choose arbitrary $k$ segments of the tree Г and discard them (Fig. 1). We get $k + 1$ connected groups of points: $\Gamma_1, \dots, \Gamma_{k+1}$. For each group $\Gamma_i$ we divide the sum of the lengths of segments of the tree Г, connecting points included in it, by the number of segments. We obtained the average length of the segments in each group $\Gamma_i$. If some group consists of one point, then by definition this average length is zero. Let us denote the calculated average lengths by $l_1, l_2, \dots, l_k, l_{k+1}$. Let, in addition, the lengths of the regrown segments be $b_1, b_2, \dots, b_k$. Let's form the quantities

$$F = l_1 + l_2 + \dots + l_{k+1} - b_1 - \dots - b_k.$$

It is clear that the smaller the value $F$, the more closely spaced the points of each group are and the farther the different groups are from each other.

⟦folio 5⟧

Therefore, it is natural to propose the following algorithm: from a tree of minimal length, we discard $k$ segments in all possible ways and calculate the values ​​$F$; Among all the obtained partitions, we choose the one for which the value $F$ is minimal; if there are several “minimal” partitions, we take any of them.

As a result of the algorithms used, the value $F$ is determined, as a rule, in a more complex way.

Computational practice has shown that algorithms of the described type lead to fairly reasonable partitions. The main disadvantage of these algorithms is that they require too much brute force. As the number of points increases, the task becomes inaccessible even for modern computers.

To cope with this difficulty, the following ideas are used. Points, the distance between which is less than a certain value $a$, tend to belong relatively to the same group. All construction is carried out in two stages. At the first stage, the set of points $A_1, \dots, A_N$ is divided into smaller groups $G_1, \dots, G_m$ so that for each group $G_i$ there is a circle $S_i$ of radius $R = a/2$ containing all the points of the group $G_i$ and only them. We will discuss how to do this below. At the second stage, only the centers $O_1, \dots, O_m$ of circles $S_1, \dots, S_m$ are considered and a tree of minimum length is built for the set $O_1, \dots, O_m$. By minimizing the value $F$ corresponding to this tree, a partition of the set of points $O_1, \dots, O_m$ into groups is constructed as described above. Thus, we also obtain a partition of the set of points $A_1, \dots, A_N$. Namely, two points $A_i, A_j$ belong to the same group if they lie in the same small group $G_i$ or if the centers of the circles correspond to the small group and fell into one group when dividing the points $O_1, \dots, O_m$. The meaning of this two-stage procedure is to reduce the number of starting points: the number $m$ turns out to be much less than $N$, and also the processors can already be implemented on a computer.

Moving circle problem

It remains for us to discuss how the set of points $A_1, \dots, A_N$ is divided into small groups. To solve this problem, the “Trout” algorithm is used (it is somewhat reminiscent of one of the methods of trout fishing). We will describe this algorithm for points on the plane, although it works in exactly the same way in multidimensional spaces.

So, let $N$ points $A_1, \dots, A_N$ be given on the plane. Let us place balls of unit mass at these points and draw some circle $S_0$ of radius $R$, in which at least one of the balls lies. Let $O_1$ be the center of gravity of the balls falling into the circle $S_0$, and $S_1$ be a circle of radius $R$ centered at point $O_1$. Let $O_2$ be the center of gravity of the balls falling into circle $S_1$, and $S_2$ be a circle of radius $R$ with center at point $O_2$, etc. For example, at Fig. 2.

⟦folio 6⟧

The circle along route $S_0 \rightarrow S_1 \rightarrow S_2 \rightarrow \dots$ cannot go on forever. We will assign the points that fall into the last circle to the first group. The same procedure is applied to the remaining points, that is, a new circle is “released”, the final position of which determines the second group. This process continues until all points are assigned to a group.

Why does the circle stop?

The rest of the stat is devoted to proving that the circle actually "stops". Looking at figure 2, we notice that the circles $S_0, S_1, S_2$, ... capture an increasingly large number of points and their final position corresponds to the group. It is natural to assume that for any location of the point $A_1, \dots, A_N$ and the circle $S_0$, the number of points falling into the circles $S_0, S_1, S_2$, ..., at least, does not decrease. Figure 3 shows that this is incorrect; however, in some cases it is possible to increase, only in addition to the number of points falling in the circle, one must take into account how close to the center of the circle they lie.

Namely, the path to some circle $S$ with center $O$ included points $A_{i_1}, \dots, A_{i_h}$; let's determine the values

$$F(S) = \left(R^2 - |OA_{i_1}|^2\right) + \dots + \left(R^2 - |OA_{i_h}|^2\right).$$

The closer a point is to the center of the circle $S$, the greater its contribution to the values ​​$F(S)$. Let us prove that the sequence of the quantity $F(S_0), F(S_1)$,

$$F(S_2), \dots$$ increases until the circle stops.

To prove it, we will need the moment of hierarchia and the system of materials of points $A_1, \dots, A_m$ relative to some $A$ and Steiner’s theorem, which is very useful in solving many problems not only from geometry, but also from mechanics *).

The moment of inertia of the material system of points $A_1, \dots, A_m$ relative to point $A$ is the quantity

$$I(A) = |AA_1|^2 + \dots + |AA_m|^2.$$

Steiner's theorem allows one to calculate $I(A)$ if the moment of inertia $I(C)$ is known. of this system of points relative to their center of gravity $C$. This theorem states that

$$I(A) = I(C) + m|CA|^2.$$

Let us prove Steiner's theorem. Let us introduce a rectangular coordinate system, placing its origin at the center of gravity of the point $A_1, \dots, A_m$ - point $C$. Let us denote the coordinates of the point $A_1, \dots, A_m$ by $(x_1; y_1), \dots, (x_m; y_m)$. Then the center of gravity $C$ has coordinates $(x_1 + \dots + x_m)/m; (y_1 + \dots + y_m)/m)$, and since $C$ coincides with the origin of coordinates, then $x_1 + \dots + x_m = y_1 + \dots + y_m = 0$. Let the point $A$ have coordinates $(x; y)$. Then

$$I(A) = \left[ (x_1 - x)^2 + (y_1 - y)^2 \right] + \dots + \left[ (x_m - x)^2 + (y_m - y)^2 \right] = \left( x_1^2 + y_1^2 \right) + \dots + \left( x_m^2 + y_m^2 \right) + m \left( x^2 + y^2 \right) - 2x \left( x_1 + \dots + x_m \right) - 2y \left( y_1 + \dots + y_m \right) = I(C) + m|CA|^2,$$

since $2x(x_1 + \dots + x_m) = 2y(y_1 + \dots + y_m) = 0$. Steiner's theorem has been proven.

Let us prove that if the circle $S_1$ does not coincide with the circle $S_0$, then $F(S_1) > F(S_0)$. Let us renumber the points $A_1, \dots, A_m$ so that the points that fall into the circle $S_0$, but do not fall into the circle $S_1$, have numbers from 1 to $p$, the points that fall into the intersection of the circles $S_0$ and $S_1$ have numbers from $p + 1$ to $q$, and the points

*) See the book by M. B. Balk “Geometric applications of the concept of the center of softness” (M., Fizmatiz, 1959).

⟦folio 7⟧

ki that fell into $S_1$, but did not fall into $S_0$, are numbers from $q + 1$ to $r$. Thus, in the circle $S_0$ there are points $A_1, \dots, A_q$, and in the circle $S_1$ there are points $A_{p+1}, \dots, A_r$. It is clear that the quantities $F(S_0)$ can be expressed through the moment of inertia $I(O)$ of the point $A_1, \dots, A_q$ relative to the point $O$—the center of the circle $S_0$, namely,

$$F(S_0) = (R^2 - |OA_1|^2) + \dots + (R^2 - |OA_q|^2) = qR^2 - I(O).$$

The point $O_1$ — the center of the circle $S_1$ — is the center of gravity of the points $A_1, \dots, A_q$, therefore, according to Steiner’s theorem

$$I(O) = I(O_1) + q |OO_1|^2,$$

that is

$$F(S_0) = qR^2 - I(O_1) - q |OO_1|^2 = (R^2 - |O_1A_1|^2) + \dots + (R^2 - |O_1A_q|^2) - q |OO_1|^2.$$

Let's compare this expression with

$$F(S_1) = (R^2 - |O_1A_{p+1}|^2) + \dots + (R^2 - |O_1A_r|^2).$$

The expression $F(S_1)$ is missing terms

$$(R^2 - |O_1A_1|^2), \dots, (R^2 - |O_1A_p|^2),$$

but terms appeared

$$(R^2 - |O_1A_{q+1}|^2), \dots, (R^2 - |O_1A_r|^2).$$

Pozny

$$F(S_1) - F(S_0) = -(R^2 - |O_1A_1|^2) - \dots - (R^2 - |O_1A_p|^2) + (R^2 - |O_1A_{q+1}|^2) + \dots + (R^2 - |O_1A_r|^2) + q |OO_1|^2.$$

Let us now note—and this is a decisive circumstance—that the points $A_1, \dots, A_q$, by construction, lie in the nekurata $S_1$. Therefore, the quantities $R^2 - |O_1A_1|^2, \dots, R^2 - |O_1A_p|^2$ are relative. For example, the points $A_{q+1}, \dots, A_r$ lie inside the circle $S_1$; therefore the quantities $R^2 - |O_1A_{q+1}|^2, \dots, R^2 - |O_1A_r|^2$ are relative. Thus,

$$F(S_1) - F(S_0) \geq q |OO_1|^2,$$

that is, $F(S_1) > F(S_0)$ if the points $O_1$ and $O$ do not coincide.

In the same way, it is proved that $F(S_{k+1}) > F(S_k)$ if the points $O_{k+1}$ and $O_k$ do not coincide. Using this fact, it is now easy to show that, starting from some number $n$, all circles $S_n, S_{n+1}, \dots$ coincide. By construction, the point $O_{m+1}$ is the center of gravity of the points falling within the circle $S_m$. If we consider all subsets of the set of point $A_1, \dots, A_N$ and the centers of gravity of the point of these subsets, then point $O_{m+1}$ will be one of these centers of gravity. Since the set of centers of gravity is finite, in the sequence of centers $O, O_1, O_2, \dots$ there must be coinciding, say, $O_i$ and $O_j$. However, we have proven that

$$F(S_i) \leq F(S_{i+1}) \leq \dots \leq F(S_j),$$

and since $S_i = S_j$, $F(S_i) = F(S_j)$, therefore $F(S_i) = F(S_{i+1}) = \dots = F(S_j)$.

Let us now remember that the equality $F(S_i) = F(S_{i+1})$ is possible if the circles $S_i$ and $S_{i+1}$ coincide. It remains to note that if two successive circles coincide, then all subsequent circles coincide with it in construction. Thus, we have proven that the movement of the circle $S_0 \rightarrow S_1 \rightarrow S_2 \rightarrow \dots$ cannot be infinite, or, as mathematically speaking, we have proven the convergence of the Trout algorithm. Along the way, we analyzed the solution to the problem that was proposed at the last Moscow mathematical optimization and in the problem «Kvant» (see problem M505 in «Kvant», 1978, No. 5).

Two new tasks

In conclusion, we formulate two more tasks. The procedures that are described in these problems are also used to classify a point in multidimensional spaces. As before, we restrict ourselves to the case of a plane.

Problem 4. Let $N$ stones $A_1, \dots, A_N$ be divided into $l$ (non-empty) groups $G_1, \dots, G_l$. Let $O_1, \dots, O_l$ be the centers of gravity of each of these groups. Let's construct a new partition of stones $A_1, \dots, A_N$ according to the following rule: we assign each point to the $i$th group ($i \leq l$), if close to it
