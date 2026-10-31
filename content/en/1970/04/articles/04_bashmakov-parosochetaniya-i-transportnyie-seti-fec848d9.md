---
id: 1970-4-bashmakov-parosochetaniya-i-transportnyie-seti-fec848d9
issue: kvant_1970_4
year: 1970
number: "4"
title: Matchings and transport networks
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 18
page_last: 25
page_labels: 16, 17, 18, 19, 21, 22, 23
lang: en
source: kvant_digital
extraction: vision
content_sha256: d304326f9994728e54495931d0be0ef054b716803e957ffe156f56bd8ad2d5a9
prompt_sha256: draft-1
translated_from: content/ru/1970/04/articles/04_bashmakov-parosochetaniya-i-transportnyie-seti-fec848d9.md
source_content_sha256: a95995f5dfbf55f88111a3ff194dbf54e2d1fdc28ddd22f2b1b06b509f8a3002
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

1. THEOREM ABOUT MATCHmaking

Let's think about the formulation of the theorem. There is a company consisting of $n$ young men, each of whom is friends with one or several two-room apartments. The question that interests us is the following: under what conditions can each of the $n$ young men choose a bride from among his girlfriends (so, of course, that not a single two-room girl is chosen by two young men at once).

Try to find out whether it is possible to arrange such matchmaking in two examples $a$ and $b$) given in Fig. 1. Here $n=6$; kopeck piece and young men are depicted as dots, and from each kopeck piece arrows are drawn to those young men who are friends with it. To arrange matchmaking means to select (for example, circle with a pencil) six arrows, looking from six different two-room apartments to all six different young men.

It turns out that for example $a$ this can be done *). And in example $b$), no matter how hard we try, we cannot get all the young men married. It's not hard to explain why. The fact is that four young men - Ilya, Kolya, Mark and Nikita - have only been friends since the third kopeck piece - Belaya, Ve*

*) One of the solutions to the problem is indicated on page 18 (Fig. 2). There are other solutions.

Fig. 1

16

⟦folio 17⟧

There can only be two cases:
Case 1. For some $k$ ($1 \leq k < n$) there is a group of $k$ boys who are friends (all together) with exactly $k$ girls.

Let us denote the set of these young men by $IO_k$, and the set of their girlfriends by $Д_k$. For the group of boys $IO_k$ the induction sentence was completed. At the same time, their brides exhaust the entire set of $Д_k$ (unevenly $k$ girls). Let's throw these boys and girls out of consideration and prove by contradiction that the condition of the theorem is satisfied for the remaining $n - k$ boys.

Let us select from these $n - k$ young men a company containing $r$ young men. Let's assume that the number of their friends $s$ turned out to be less than $r$. Let's get back on track and unite these $r$ young men with the $IO_k$ group. There are $r + k$ young men in the new group. Since the set $D_k$ contains all the girlfriends of the boys from $IO_k$ (and, possibly, some other girlfriends of the $r$ boys from the displayed company), then these $k + r$ boys had $k + s$ girlfriends at the very beginning. According to the initial condition $k + r \leq k + s$. Therefore, $r \leq s$. The result is a contradiction with proposal $s < r$. This means that in this case the theorem is true.

Case 2. Any group of $k$ boys ($1 \leq k < n$) is friends with at least $k + 1$ girls.

In this case everything is simple. We marry any young man to any of his girlfriends. Let's exclude this pair from consideration. Let us prove that the conditions of the theorem are satisfied for the remaining $n - 1$ boys. Let's take any group of $k$ young men ($k \leq n - 1$). At the very beginning they had at least $k + 1$ girlfriends. Then the bride of the chosen young man gets here, then there are still $k$ girls left. This completely proves the theorem.

Belief, you had to spend some conditions to understand this proof. But, in addition to the fact that the proof is not simple, it suffers from an important drawback - it does not show a simple way to find out whether the condition of the matchmaking theorem is satisfied for each specific case, and if it is, then how to choose a bride, you need to go through all the non-fair subsets (and there are $2^6 - 1 = 63$) sets of young men and for each of these subsets of young men check that they have enough girlfriends. But even if we do this and make sure that, in principle, all weddings can be arranged, we will not receive any instructions from here about who to marry whom. True, in this example $a$ you undoubtedly easily managed to select the required six pairs (there are even several possible options), but when the sets are very large, then random selection only takes a lot of time. It is especially important to have a clear and economical selection rule in order to entrust the solution of problems of this type to a computer.

We will build some algorithm *), which will not only re-prove the matchmaking theorem, but also provide a quick way to arrange the necessary matchmaking, and if this is impossible, then indicate the option for the maximum number of weddings.

3. WEDDINGS AND COURTS

A system of points that are somehow connected by arrows is called a directed graph*). In this case, the points are called the vertices of the graph, and the segments are called its lines or edges. Examples of directed graphs are shown in the discussion already figure 1, as well as in Figures 3 and 5. In the case of Figure 1, the set of all vertices of the graph was divided into two sets - girls and boys - so that the edges go from the points of one set to the points of the other. In such a situation

*) Sequence of actions to solve a certain type of problem. Muscovites were promised an algorithm, Leningraders - an algorithm. Currently the second page of pages.

⟦folio 18⟧

the graph is called simple or bipartite, and the problem that has occupied us so far - to safely arrange the personal lives of the maximum number of girls and boys - is the maximum matching problem.

The matchmaking problem can be formulated using a graph as follows. Choosing each girl-boy pair means choosing an edge of the graph. We assign the number 1 to each pair in the brane edge of the graph, and the number 0 to each of the others. Having arranged all the weddings, we obtain a function whose domain is all the edges of the graph, and the set of values ​​is two numbers 0 and 1*). How can we state all the other conditions of the problem in terms of this function? We need every boy to choose a girl, and every girl to be chosen by no more than one boy. In other words, for each vertex of the graph, a girl is depicted, the sum of the function values ​​along all edges leaving it must be no more than one, and for each vertex, a boy is depicted, the sum of the function values ​​for all edges entering it must be exactly equal to one.

Thus, our problem is formulated as the problem of finding some function defined on the edges of the graph and satisfying some inequalities**).

One solution to this problem (in the case of example a)) is depicted in figure 2, where the selected edges are heads. The required function has the following form:

Anya - Kolya, Bela - Ilya, Vera - Leva, Dasha - Osya, Zhanna - Mark, Zina - Nikita, Anya - Nikita, Vera - Ilya, Galya - Kolya, Dasha - Leva, Dasha - Mark, Dasha - Nikita, Eva - Leva, Zhanna - Leva

*) See the article by A. N. Kolmogorov “What is a function” in No. 1 «Kvant».
**) Note that the equality f=1 can be written as a system of two inequalities: f≥1 and f≤1.

⟦folio 19⟧

Naimporta from the rest of the matrimonial theme. Communication systems themselves are represented using graphs. For example, when monitoring the implementation of a complex set of work, individual intermediate stages are designated by the vertices of the graph, and arrows connect those of them that depend on each other (Fig. 3). The graph placed on page 14 (the splash screen for this status) shows how its parts are connected; from it it is immediately clear, for example, that clause 3 can be read regardless of whether clause 2 is clear. When a graph is given, problems are often posed for it that are mathematically related to finding functions that satisfy certain inequalities. One of them, we have considered the problem of equality. Let us pose another similar problem (without solving it).

Task. Move the knight around the chessboard $8 \times 8$, starting and ending in the given squares.

We draw a graph (Fig. 4) with 64 vertices (fields of the chessboard) and connect the edges (in this case, straight segments) of each vertex with those that can be reached by moving the knight. Until we start solving the problem, the direction of movement does not matter to us, and we can draw the edges of the graph without arrows (undirected graph); Or you can draw a pair of arrows in two opposite directions on each edge.

The required function should give the number 2 for each intermediate vertex, and one for the initial and final vertices.

4. NETWORKS AND STREAMINGS

Now we will look at some special types of graphs - networks and a special type of function on such a graph - flows. Let's look again at the graph (see page 14). It has two extreme vertices - “input” (1. Matchmaking Theorem) and “output” (Problems). A directed graph with an input and an output is called a *transport family* or simply *family*. An example of such a network is shown in figure 5, a.

*A help* on a given network is a function on the edges of a graph that takes (in the simplest case) the values ​​0 and 1 and satisfies the following condition: for each intermediate vertex (i.e., different from the input and output), the sum of the flow values ​​along all edges entering this vertex is equal to the sum of the values ​​over all edges leaving it.

The name “transport seven” and “flow” can be calculated as follows.

Let's imagine a city with the development of a system of streets (edges) and intersections (vertices), and on each street there is one-way traffic and there is only one everywhere into the city and one everywhere from the city.

A continuous flow of cars passes through the city, and the traffic is organized in such a way that there is no traffic jam at any intersection. In the simplest case under consideration, we assume that all streets through which the flow flows are equally loaded (have the same capacity, which is conventionally taken as one).

In a more general case, each edge is assigned a positive integer - weight or capacity. (In our example

⟦folio 21⟧

Street capacity is the number of cars that can pass through a “cross section” of the street per unit of time.)

Instead of saying “a stream is defined on the network,” it is customary to say “a stream is passed through the network.” Obviously, the flow leaves nothing at the intermediate vertices, and therefore brings to the exit the same number of collisions that went through the entrance. This sum of flux values ​​along all edges leaving the input, equal to the sum of values ​​along all edges going to the output, is called the flux value.

figure 5,6 shows the flow on network figure 5,a. The network edges on which the values ​​of this flow are equal to 1 are depicted as heads. The flow value is 3.

It is easy to say that in order for a flow of size n to pass through the network, the following necessary conditions must be met: if any k edges are disconnected from the network, where k<n, then it is possible to pass from the input to the output along the remaining edges.

It is remarkable that (just as in the matchmaking theorem) this necessary condition turns out to be sufficient.

A number of real economic problems lead to finding the maximum flow, i.e., the flow of the highest possible value that can be passed through a given network.

We will now deal with the description of the algorithm that makes it possible to construct the maximum flow.

5. ALGORITHM
FORD-FALKERSON

Let us have a transport network (Fig. 5,a). Our task is to build the maximum flow for it.

Let there be some initial flow along this network (in the extreme case, zero, that is, one whose values ​​on each edge are equal to zero).

We will start with a non-zero flux (Fig. 5,6). The edges along which this flow went (they are made by heads) will be called saturated, and the rest (yellow) - free. Check that our flow cannot be increased without touching the already occupied ones (you cannot connect the input to the output by moving only along the free arrows).

We will now perform some operation that will lead to two possible outcomes: either it will be shown how to increase this flow, or it will be found that the existing flow is maximum.

Let's start putting "plus" and "minus" boxes on the tops. Let us mark with a flat buckle all the vertices that can be reached from the entrance along the free edges. The further process of placing will be arbitrary: from the already placed vertex we will place flat those vertices to which one can get from it along free edges, and in a minute - all those vertices to which one can return from it (in the direction opposite to the arrow) along saturated arcs. Don't be confused by the fact that the process of placing is insignificant - often the same vertex can be placed with both a plus and a minute.

Let us mark all possible vertices in this way (there are no unplaced vertices on Fig. 5,6; but in other cases they may appear!).

Two cases are possible: 1) we managed to place the output (of course, with a plus); 2) it is impossible to make more premises, but the exit remains unfinished.

1) It turned out that m was placed in the output. (This occurs at Fig. 5,6.) Let us restore the order in which we managed to place the output*), that is, we connect the output with the input by a path passing along the intended vertices (this path can in some cases go

*) Practical (in graphs with a large number of vertices) placements make the part more complex in order to store information about the order in which the vertices were placed.

⟦folio 22⟧

in the direction opposite to the direction of the arrows).

This path at figure 5.6 is highlighted with a red line.

Now we will do the following: in the selected red path we will make the free arrows saturated and vice versa (Fig. 5,8), i.e. we will change the flow on the red line so that it takes on each of its edges the value 1 together with 0 and 0 together with 1*). It is easy to see that the new function is again a flow, i.e. at intermediate vertices the number of incoming and outgoing saturated arrows is again the same - the balance is not violated. At the same time, the face of the flow increased by one unit.

So in the first case we could increase the flow. If this operation can be done again, we will repeat it as long as possible.

2) THE OUTPUT IS NOT MARKED (Fig. 5,2). Our method cannot increase the flow. But it does not yet follow from this that it is maximum. It is possible that our method of increasing is bad, and we can increase the flow in another way. Let us prove that this is not the case, i.e. we will prove that the existing flow is maximum. Let's consider the set of all unplaced vertices. By condition, this set includes the output. Let's count the number of arrows leading to this set, i.e., those whose left end is placed, but the right end is not. It is clear that the magnitude of any flow is not greater than this number. At the same time, for our flow all these arrows are saturated, since otherwise the right end could be placed flat. In addition, all arrows coming from the set of unplaced vertices (that is, those whose left end is not placed and the right end is placed) are free, otherwise the left end could be placed in a minute. This means that the size of the original flow is equal to the number of arrows leaving in

6. GAYLE'S THEOREM
ABOUT SATURATION

Using the Ford-Falkerson algorithm, we will now formulate and prove the central theorem of the theory of transport networks. The formulation will use some natural economic terms, but you will feel how close it is to the matchmaking theorem.

Let us be given a transport network. Consider an arbitrary set of arbitrary vertices $A$ (i.e., containing neither input nor output). Let us define the capacity of this set $A$ as the number of arrows going to $A$. Let's denote this number

⟦folio 23⟧

via $c(A)$. Let us define by the total requirement of the set $A$ the number of edges leading from $A$ directly to the exit. Let's denote this number by $d(A)$.

Let us study the following question: under what conditions does there exist a flow that saturates all output edges, i.e., one whose values ​​on all edges leading to the output are equal to one. It is clear that such a flow should be maximum.

Gale's theorem. For any number, there is a flow that saturates all output arcs; it is necessary and sufficient that for any set $A$ its total demand does not exceed the capacity:

$$d(A) \leq c(A).$$

Proof. As with the matchmaking theorem, the necessity is almost a turn. Indeed, if we can construct a flow passing along all edges leading to the exit, then for any set $A$ it also passes along the edges leading to the exit only from $A$. At the same time, the number of flows leading to the sets $A$ cannot be greater than the number of edges leading to $A$, i.e. the numbers $c(A)$. But this amount of flow must completely leave $A$ along all the edges leading primo to the exit, and maybe along some others. From this it is clear that $d(A) \leq c(A)$.

Adequacy. Let there be maximum flow through our network. Let us prove that it passes along all output arcs. Let's label the vertices using the Ford-Folkerson method and consider the set of unlabeled vertices. Let's remove the output from this set. We denote the resulting set by $A^*$. The ribs leading to the exit can be of two types.

Firstly, these are also edges whose end lies in $A$, i.e., is a labeled vertex. They will be saturated, since according to the method of constructing the flow, all edges whose left end is placed, but the right end is not, are saturated.

Secondly, these are the edges leading to the exit from the set. Since $A$ together with the exit forms the set of all unlabeled vertices, then all $c(A)$ edges leading to $A$ will be saturated, and all edges leading from $A$ not directly to the exit will be free.

*) The set $A$ may turn out to be empty - our reasoning will still be correct. But in this case the validity of Gale's theorem is immediately visible. Why?

This means that the entire flow of value $c(A)$ that entered $A$ must exit $A$ directly to the exit. But from $A$ only $d(A)$ each lead to the exit, and we know that $d(A) \leq c(A)$. Therefore, all these edges are saturated and $d(A) = c(A)$.

You probably noticed that the conditions of Gale's theorem correspond to the conditions of the wedding theorem. Try to deduce this theorem yourself as a consequence of Gale's theorem. To do this, you need to make a transortunal network from the bipartite graph of acquaintances between boys and girls, connecting the input with all the girls, and the output with all the boys (it is then convenient to assign a weight $N$ to each arrow connecting the girl with the boy, where $N$ is greater than the number of boys).

What is much more important for us now is not that we have obtained yet another proof of the matchmaking theorem, but that we have a simple algorithm for constructing maximum flows.

For the matchmaking problem, the algorithm naturally formulates the flow as follows: for each girl who is not a bride, all her friends are placed flat, then in a minute - the brides of these friends, then the rest of the friends of these brides are placed on the flat, etc.; if an unoccupied young man turns out to be placed, then the number of weddings can be increased by making replacements along the chain drawn (like the red line at Fig. 5.6) along the marks from the unoccupied girl to the unoccupied young man.

The arrangement of weddings for all young men is nothing more than the construction of a flow that saturates all the exit arcs; if this is not the case, then the Ford-Folkerson algorithm provides the maximum possible new interesting algorithm for solving a number of difficult problems in finite mathematics.
