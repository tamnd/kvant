---
id: 1990-3-abakumov-kratchayshie-seti-8afeea5c
issue: kvant_1990_3
year: 1990
number: "3"
title: Shortest networks
authors:
  - Абакумов Е. В. и др.
rubric: osnovnye-stati
page_first: 19
page_last: 26
page_labels: 17-24
lang: en
source: kvant_digital
extraction: vision
content_sha256: ea14e7e9afe1205d48ba22d37930c21d0939ed61f364aa6abad59f22859ae639
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/03_abakumov-kratchayshie-seti-8afeea5c.md
source_content_sha256: f477ee50d80932fefa5aca5026024918e6372d5546d9476683ac472a6b189919
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

---
running_head:
folio:
---

SHORTEST NETWORKS
E. ABAKUMOV, O. IZHBOLDIN,
L. KURLYANDCHIK, N. NETSVETAEV

In this article we talk about one problem (the Steiner problem):
Residents of several villages want to build roads so that it is possible to drive from each village to any other, and the total length of the road would be the shortest possible.

Three villages
Connecting three villages in the shortest possible way is quite simple: if in the triangle formed by these villages all angles are less than 120°, then you should connect the vertices of the triangle

ka with a point from which all sides are visible at an angle of 120° (Fig. 1).
To prove this, let's build it like this: put a plan of the area on the table and then drill holes into the table at the locations of the villages. Let's pass three trees through these branches, tie the upper ends of them into one knot, and hang weights weighing 1 kg from the lower ones.

⟦folio 18⟧

---
running_head:
folio:
---

(Fig. 2). The ropes on the table will take the position with the minimum total potential energy of the weights. This means that the total length of the ropes under the table turns out to be the maximum possible, and the ropes on the surface of the table indicate the desired shortest connection of these three points. It remains only to understand why the knot will end up at a point from which all sides are visible at an angle of 120°. To do this, it is enough to note that three forces of equal magnitude act on the node (Fig. 3), and they can balance each other only if all three angles formed by it are equal.

Exercise 1. Prove it.
And at this point we could have finished the proof if we were sure that the node would not be responsible. But what does this mean - the node is responsible? This means that the sum of two tension forces directed along the sides of the triangle (Fig. 4) does not exceed 10 N. And this is only possible if the angle formed by these forces is at least 120°.

Let us summarize the discussion of the problem of connecting three points $A, B, C$ by the shortest road network.

If all the angles of the triangle $ABC$ are less than 120°, then you need to connect all the vertices to a point from which all sides are visible at an angle of 120°. If one of the angles of the triangle is at least 120°, then the vertex of this angle should be connected to two other vertices.

The solution is complete, but let us make three comments to it.

First note. One day later, we replaced the original problem of the shortest network connecting three given points with the problem of finding a point for which the sum of the distances to these three is the smallest possibility. (By the way, such a point is called the Fermat point.)

Exercises
2. Justify the correctness of this reformulation.
3. Find out whether a similar reformulation is possible in the case of four points.

Second remark. Another way to construct the shortest road network can be proposed. Let's put a plan of the area on the table and then drive three nails in the locations of the villages. After this, a small ring is used to stretch, as shown in figure 5. In the absence of forces, the elastic band in a tense state will take a position in which its length will be minimal, and this gives us the shortest network of roads.

Remark three. Yes, we have learned how to find the shortest triangle using a network. But solving the problem was not cheap: we had to ruin the table. It would be nice to find a purely geometric construction of the point we need (from which all sides are visible at an angle of 120°). Let's construct equilateral triangles on the sides of triangle $ABC$ to the outside (Fig. 6). Then the required point will be the point of intersection of the segments $AA_1, BB_1, CC_1$. (Naturally, we are now talking about

⟦folio 19⟧

---
running_head:
folio:
---

case when the angles of the triangle $ABC$ are less than $120^\circ$.

Exercises
4. Prove that the segments $AA_1, BB_1, CC_1$ intersect at one point.
5. Prove that the intersection point of the segments $AA_1, BB_1, CC_1$ is the desired one.
6. Let $M$ be the intersection point of the segments $AA_1, BB_1, CC_1$. Prove that $AM+BM+CM=AA_1=BB_1=CC_1$.
7. Prove that for any point $X$ of triangle $ABC$ the inequality $AX+BX+CX \ge AM+BM+CM$ holds.
8. Using the results of the previous exercise, give a purely geometric solution to the problem of the shortest connection of three points.

Properties of the shortest network

So, we have solved the problem of connecting three trees with the shortest network of roads. Moving on to the general case, we formulate the problem facing us.

Given $n$ points on the plane. It is required to connect them with a network of segments having the shortest total length.

Such a network is called shortest. To avoid misunderstandings, let us clarify the concept of a network. A network connecting

given $n$ points, we will call a set of finitely many segments such that any two initial points are the ends of a polyline consisting of segments of this set. We will call the original $n$ points trees. We will call all other ends of the network segments forks. Figures 7, a, b show examples of networks, but what is shown in Figures 7, c, 2 are not networks.

On figure 7, and the fork $\alpha$ was essentially redundant and would not at all agree with the intuitive idea of ​​forks. It is also very interesting that you can do without the fork $\beta$ (which is rather a dead end). These observations suggest that when talking about shortest networks, we can limit ourselves to the case where at least three segments converge at each fork. This can be proven by construction like this. If there were exactly two segments coming out of any fork, then they could be replaced by one segment connecting their ends (in this case, the total length of the network would not increase). Well, what if there was a fork

⟦folio 20⟧

---
running_head:
folio:
---

If it was the end of only one segment, then by throwing out this segment, we would also reduce the length of the network.

Let's find out what angle two segments of the shortest network can form, starting from the same point. This angle cannot be less than 120°. Indeed, if segments AB and AC formed an angle less than 120°, then by replacing the section of the network formed by these segments with the shortest network of triangle ABC (Fig. 8), we would reduce the total length of the network. From here, in particular, it follows that from each village and from each fork there are no more than three segments.

Summarizing all that has been said, we obtain two main properties of the shortest network.

Property 1. Every fork has exactly three segments. Each two of them form an angle of 120°.

Property 2. One, two or three segments go out from each village, and if two segments go out from the village, then the angle between them is at least 120°, and if three segments come out, then the angles between them are equal to 120°.

We will also need some other properties of shortest networks. Let us formulate one more thing - simple, but important.

Property 3. No segments of the network form a closed polyline.

It's almost obvious. Indeed, if there is a closed broken line in the network, then by eliminating an arbitrary link of this broken line, we will reduce the length of the network. In this case, any two villages will remain connected.

How many forks can there be in a network?

So, we have proven three main properties of the shortest network. For those of you who are familiar with a clear graph, it is of course clear that the shortest network is a tree. And for those who have not yet encountered this concept, let’s say that by tree we understand such a set of segments on a plane that there are no closed broken lines in it, and the whole picture is “connected,” i.e., any two ends of these segments are connected by a broken line.

Examples of trees are shown in Figures 9, a - c. The segments that make up a tree are called edges, and the ends of the segments are called vertices.

Look at figure 9: each of the trees has one more vertex than the number of edges. This property applies to any tree. This can be proven by induction on the number of vertices: take some vertex from which only one edge emerges (why is there always such a vertex?), and discard this vertex along with the edge. We are again

⟦folio 21⟧

---
running_head:
folio:
---

we get a tree, but with fewer vertices. By the induction assumption, the number of vertices of the new tree is equal to the number of its edges that are flat for the original tree.

Summarizing what has been said, we get: the number of trees is the number of forks per unit, the greater the number of network segments. Let's calculate the number of network segments in a different way. Since there are three segments coming from each fork, and at least one segment from each village, the number of segments depends on no less than $\frac{3P + \Delta}{2}$ ($P - \Delta$ the number of forks, $\Delta$ the number of the tree; we divide in half because the segment has two ends!). That is, $\Delta + P - 1 \geq \frac{3P + \Delta}{2}$.

So, $P \leq \Delta - 2$.

Thus, we have obtained another property of the shortest network.

Property 4. The number of forks is at least two smaller numbers in the tree.

Control 9. Prove that the number of forks in the shortest network is equal to $\Delta_1 - \Delta_3 - 2$, where $\Delta_1$ is the number of trees from which one segment emerges, and $\Delta_3$ is the number of trees from which three segments emerge.

Four villages at the tops of a square

We already have sufficient knowledge about shortest networks. Let's try to apply them in a specific situation. Consider four villages located at the vertices of a square. How to connect them in the shortest possible way?

It is clear that the shortest network does not extend beyond the square. It follows that from each village there is exactly one road. Indeed, if there were less than two coming out of any village, then the angle formed by it would be no more than $90^\circ$. And this contradicts the second property of the shortest network.

Using the notation from Exercise 9, we find that $\Delta_1 = 4$, $\Delta_3 = 0$, and therefore the number of forks is $\Delta_1 - \Delta_3 - 2 = 2$. It is clear that these two forks are connected by a segment, and each of them is connected to two trees (Fig. 10). At this figure we do not know the exact location of the forks $\alpha$ and $\beta$. How to determine their true location in the square?

Let us again use the second property of the shortest network: all six angles on figure 10 must be equal to $120^\circ$. An example of a network with such a condition is easy to draw (Fig. 11).

Four villages

Let us now solve a more complex problem: four villages are located at the vertices of a convex quadrilateral, all angles of which are less than $120^\circ$. How to connect them in the shortest possible way?

Repeating the reasoning given when solving the problem of the shortest network in a square, we find that in this case the shortest network must have exactly two forks, and there must be one road from each village. Possibly exactly

⟦folio 22⟧

---
running_head:
folio:
---

two ways to connect $A, B, C, D$ with this condition (Fig. 12, $a, \delta$). (In the case of a square, we made do with the distance of one connection method, or the second method is simply obtained by turning by $90^\circ$.)

Naturally, the question arises: what type exactly - $12, a$ or $12, \delta$ - does the shortest network have? The answer to this question can only be obtained by finding the shortest network of each of the two types and comparing them in length. So, we need to build the shortest network of a given type (say, $12, a$), i.e., find the true position of the forks $\alpha$ and $\beta$.

We begin the construction of forks (Fig. 13) by noting that the segments $A\alpha, B\alpha, \alpha\beta$ form the shortest network in the triangle $AB\beta$. This means that developed $\alpha$ is a Fermat point in this triangle. Likewise, point $\beta$ is a Fermat point in triangle $CD\alpha$.

Let us construct equilateral triangles $ABO_1$ and $CDO_2$ on the segments $AB$ and $CD$ to the side external to the quadrilateral. Points $O_1, \alpha, \beta$ - lie on the same straight line (see exercise 5). For the same reasons, points $O_2, \beta, \alpha$ lie on the same line. This means that all four points $O_1, \alpha, \beta, O_2$ lie on the same straight line. Now it is easy to construct points $\alpha$ and $\beta$: these are the intersection points of the circles circumscribed around the equilateral triangles $ABO_1$ and $CDO_2$ with the segment $O_1O_2$ (Fig. 13).

So, we have built the shortest network of the form $12, a$. The shortest network of the form $12, \delta$ can be constructed in a similar way. Of the two connections constructed, the shorter one is the answer to the problem.

Exercises

10. Where in the proof is the condition used that all angles of a quadrilateral are less than $120^\circ$?

11. Prove that the length of the shortest network constructed from figure $13$ is equal to the length of the segment $O_1O_2$.

12. Find a mechanical solution to this problem using two rings, an elastic band and four nails.

13. Find the length of the shortest network in the rectangle $3 \times 4$.

Correct pentagon

Let us now solve the problem of finding the shortest network for five trees located at the vertices of a regular pentagon. When solving this problem, we will proceed in the same way as in the case of four trees. Since all angles in a regular pentagon are less than $120^\circ$, then exactly one segment comes out of each vertex of the pentagon. Therefore, the number of forks in the network, equal to $D_1 - D_3 - 2$ (see Exercise 9), in this case is equal to three, since $D_1 = 5, D_3 = 0$. Essentially, it is enough to consider one option for connecting to the tray. Developments are obtained from it by turning it. Now all that remains is to find the true location of the forks $\alpha, \beta, \gamma$. To construct these forks, we will use the idea that has already been applied: we will construct regular triangles $ABO_1$ and $CDO_2$ on the segments $AB$ and $DC$ in the direction external to the pentagon. Since the developments $\alpha$ and $\gamma$ must lie on the segments $O_1\beta$ and $O_2\beta$, then the segments $\beta O_1, \beta O_2$ and $\beta E$ must form angles $120^\circ$, and, consequently,

⟦folio 23⟧

---
running_head:
folio:
---

Therefore, β is a Fermat point in the triangle $O_1O_2C$. We already know how to build a Fermat point in a triangle.

Now it is easy to construct the forks α and γ - these are the Fermat points in the triangle $AB\beta$ and $CD\beta$. The resulting network is the shortest for the vertices of the regular pentagon $ABCDE$ (see Fig. 15).

Construction of the shortest network

But how to solve the problem in the general case, i.e., connect $n$ villages with the shortest network of roads? The attentive reader, of course, noticed that the solution to the problem in the case of four and five villages was divided into two stages. First, we found out what a connection graph could be, i.e., we determined how many forks there could be and which of the forks and villages were connected by segments. At the second stage, using this information (about the connection graph), we find the true position of the forks. This is exactly what we will do in the general case.

Let's start with the first stage. As we know, the number of forks is no more than $n-2$, and therefore there are only a finite number of possible schemes (more precisely, graphs) for connecting data $n$ points. Consequently, the first stage consists of a final enumeration of all possible connection graphs. Examples of some possible graphs for connecting the heel of villages are shown in Figures 16, a - ε.

Now let's move on to the second stage: constructing the shortest network using its given graph. It is enough to learn how to adapt the problem of constructing a network for $n$ villages to constructing a network for a smaller number of villages.

So, let us have a graph connecting $n$ villages. If some villages in this graph are connected by a segment, then by discarding it, we will split our graph into two with fewer villages. For each of these graphs, the shortest network problem must be solved separately. Let us now assume that every segment leaving the village leads to a fork. Since the number of forks is less than the number of villages, then from some two villages the segments lead to one fork. Let us denote these villages and the fork with the letters $A$, $B$ and $\alpha$.

It is clear that the fork $\alpha$ is the Truss point of triangle $AB\beta$ (Fig. 13). Let's use an idea that we have already used many times: construct an equilateral triangle $ABO_1$. As is known, in the shortest network the fork $\alpha$ must lie on the segment $O_1\beta$. Now the problem is applied to a smaller number of villages by replacing two villages $A$ and $B$ with one located at point $O_1$, and replacing the segments $A\alpha$, $B\alpha$, $\alpha\beta$ with the segment $O_1\beta$. By constructing a network for the new system of villages (instead of $A$ and $B$ - point $O_1$), we will find the exact location of all forks except one - fork $\alpha$. Well, this fork is the intersection point of the circle described around the triangle $ABO_1$ and the segment $O_1\beta$. Since now all the forks have been built, the problem is solved.

And now we turn to the casual reader, who, of course,

⟦folio 24⟧

---
running_head:
folio:
---

The smaller the $a$, the shorter you are!

Fig. 17.
However, I discovered a number of inaccuracies in the proof. To remedy the situation, we offer a number of controls, by solving which you can eliminate the gap in the proof.

Administration
14. What to do in the case when not one, but at least two roads lead from one of the trees $A$ or $B$?
15. On side $AB$ two equilateral triangles can be constructed. Which one should you choose?
16. The second stage of the proof consists of describing the method for constructing a network using a given graph. Does this construction always lead to some network?
17. What to do if point $O_1$ coincides with one of the trees? What to do if any of the segments $Aa$ or $Ba$ intersects any of the constructed segments?

Why are existence theorems needed?

Can we consider that we have completely solved the problem we posed about the shortest connection of $n$ points on the plane? It turns out not!

Our solution is missing a very existence detail: there is no proof that the shortest network exists. But is this question really fundamental? Definitely, yes. After all, the algorithm for constructing the shortest network is based on the fact of its existence. It may, however, appear in print that the very fact of existence is very clear, and proof is needed only later, that it is customary for mathematicians to prove everything. But such things in print are deceptive. To illustrate what has been said, consider the problem.

It is required to connect two villages in the shortest possible way with a network of roads so that when traffic is closed on any section of the network, the villages remain connected.

The formulation of this problem is similar to the original one, and the task is undoubtedly simpler - after all, there are only two villages. However, the similarity is purely external - in this case there is simply no shortest network (Fig. 17).

Now we hope that we have convinced you not only of the need to prove the existence of the shortest network, but also that the fact of its existence is not at all obvious.

However, we must disappoint you. We will not hesitate to present this proof - it goes beyond the scope of the school curriculum. We just wanted to demonstrate the fundamental importance of existence theorems. In conclusion, we suggest several topics for research.

1. Solve the problem of the shortest connection of the vertices of a regular $n$-gon.
2. Consider the problem of finding the shortest connection between several trees in the presence of obstacles (for example, a round lake).
3. Consider the shortest connection problem for a point in space.

And a few more words about algorithms. In mathematics, it often happens that an algorithm for solving a problem exists, but its practical implementation takes too much time. In this case, Japanese algorithms become a meaningful task (this became especially important with the development of computer technology). A typical example of such a situation is the familiar algorithm for multiplying numbers “in a column”. Now cities have discovered faster multiplication algorithms based on deep mathematical ideas (for example, the Fourier transform). Another example is the multiplication of numbers by factors, which is of great practical importance (some commercial codes are based on this). If you are interested in convenient algorithms for constructing shortest networks, we advise you to read an article on this subject in the journal “In the World of Science” No. 3, 1989.
