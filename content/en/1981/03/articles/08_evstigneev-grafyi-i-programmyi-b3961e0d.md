---
id: 1981-3-evstigneev-grafyi-i-programmyi-b3961e0d
issue: kvant_1981_3
year: 1981
number: "3"
title: Graphs and programs
authors:
  - Евстигнеев В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 24
page_labels: 18-22
tag: 7P1K
lang: en
source: kvant_digital
extraction: vision
content_sha256: c144bd00743eee2ef4e442b1018f762a4f39b3607df37abeb9d8a9940fea90b8
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/08_evstigneev-grafyi-i-programmyi-b3961e0d.md
source_content_sha256: c1367c57fdb488e3e573f2a51bb9ca43690887b6d8361812a5fe64f468bab2f7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

V. Evstgenev

Graphs and programs

Graph theory took shape as an independent branch of mathematics in the mid-thirties and continues to develop intensively to this day. Great interest in graph theory today is based primarily on its broad and fruitful applications to the design and analysis of complex systems of various natures: transport networks, electrical circuits, electronic circuits, mechanical systems, chemical reactions, control systems, social groups and collectives, etc.

In this math club lesson, we will look at several programming problems that use graphs.

Graphs and directed graphs

A graph is a set of elements, some pairs of which are selected. The graph $G$ is thus defined by two sets:

$$G = (X, U);$$

the first state is from elements of arbitrary nature (they are called vertices), and the second is from all selected pairs of vertices. If each distinguished pair is ordered, the graph $G$ is called a directed graph or oreraf, the pairs are called duems; they say that the arc $(x, y)$ is directed from its beginning $x$ to its end $y$ and write

$$U \ni u = (x, y).$$

In this case, they also say that the arc both originates (leaves) from $x$ and enters (enters) $y$. Draw a digraph on a plane in the form of points connected by arcs with arrows (Fig. 1). Notice on this figure that the arc coming out of the vertex $x_3$ enters it; such an arc is called a netley.

If the pairs $(x, y)$ are not ordered, then they are called edges, the vertices of the edge $u = \{x, y\}$ are called ends, and the graph $G = (X, U)$ itself is called an undirected graph or protego graph. An example of such a graph—the so-called Peterson graph—is shown in figure2.

Graph of this program

Let the bottom of the program $P$, for example, be in the form of a block diagram (“Algebra 8”, paragraph 50). Let's associate each block with a graph vertex and connect the vertices in accordance with the sequence of actions (indicated by arrows) in the block diagram. The resulting digraph is called a projection operaf $P$ or a $p$-graph.

Exercise 1. Draw a $p$-graph corresponding to the block diagram of the software ball sorting shown in figure 3.

If the program $P$ is written in any algorithmic language,

Fig. 1.

Fig. 2.

⟦folio 19⟧

then it can also be associated with some $p$-graph: each operator is associated with a vertex, two vertices $a$ and $b$ are connected by another $(a, b)$, if control is transferred from the operator represented by the vertex $a$ to the operator represented by the vertex $b$.

Another example of a $p$-graph is shown in figure 4. Note two special vertices: $x_{0d}$ ($s$) (corresponding to the program input), from which no arc enters, and $b_{1x0d}$ ($t$) (corresponding to the program output), from which no arc emanates.

On a given $p$-graph $G = (X, U)$ (and in general on any digraph) is often considered a path if its vertices are not repeated, a contour if $a = b$, and a simple path if $a = b$, but there are no other repetitions of vertices. So, on figure 4, path $(x_1, x_3, x_6, t)$ is a simple path, $(x_1, x_4, x_6, x_3, x_6, t)$ is not a simple path, $(x_3, x_6, x_3)$ is a simple path, $(x_3, x_6, x_3, x_6, x_3)$ is a path, but not simple, $(x_2, x_7, x_6)$ is not even a path.

Fig. 3.

Fig. 4.

Exercise 2. List all simple paths and all simple contours of the $p$-graph constructed by solving Exercise 1.

Do all roads lead to Rome?

In the $p$-graph corresponding to a well-written program, “all paths lead to Rome,” that is, any path starting at $s$ can be continued until the exit $t$, which marks the end of the program. Therefore, a $p$-graph is naturally called *regular* if any vertex lies on a path (not necessarily a simple one) leading from $s$ to $t$.

Of course, the correctness of the $p$-graph does not yet guarantee the successful operation of the program: if it has at least one contour from which no arc emerges, the program can go into a loop, that is, it spins along this contour. But since there is no general algorithm that checks the correctness of the program (we will talk about this in «Kvant» another time), it is important to check at least the correctness of the $p$-graph.

How to check the validity of a $p$-graph? In simple cases this can easily be done manually.

Exercise 3. Check the correctness of the $p$-graph of the ball sorting program (see Exercise 1). Make sure that the $p$-graph on figure 5 is incorrect, find “dead ends”, “dead-end contours” and “inaccessible contours”.

In complex cases, for example, in modern large programs, manual checking is too laborious and unreliable - it comes to resorting to the help of a computer. Therefore, it is necessary to have algorithms suitable for this purpose. We will formulate the problem of constructing such algorithms in the form of three exercises (4-6) and for the first of them we will suggest a solution.

⟦folio 20⟧

Fig. 5.

Exercise 4. Find all simple paths connecting the input of the $p$-graph to its output.

One of the most beautiful algorithms for solving this problem is based on the sequential arrangement of vertices of a $p$-graph. figure 6 shows its application to the $p$-graph from figure 4. At each step, one of the vertices $x \in X$ (different from $s$ and $t$) is STRAYED; Together with simple paths connecting the vertices adjacent to $x$ and passing through $x$, a new arc is constructed (next to which the name of the removed vertex is written). The loops that arise in this process are discarded. The result is a set of arcs connecting $s$ with $t$, moreover, on each of these arcs vertices are successively written, through which it is possible to find algorithms that solve controls 5, 6. They can be written in the form of a flow chart, in tabular form (“Algebra 8”, p. 49) or, for students of ZShP, in the Rapier language.

Exercise 5*. Find all simple contours of the $p$-graph.

Exercise 6*. Construct a system of paths (not necessarily simple) connecting the input of the $p$-graph with its output, covering all the vertices of the $p$-graph. Construct such a system with the minimum number of paths.

Orgraph of an arithmetic expression

When calculating arithmetic expressions on a computer in random order, when there are many of these expressions and they are quite cumbersome, the initial data and intermediate results of calculations can take up an unacceptably large amount of computer memory; as programmers say, “the program clogs up the machine’s RAM.” How to deal with this? This is where graph theory comes to the rescue.

It turns out that with each arithmetic expression one can associate

SIMPLE WAYS:

$s x_1 x_3 x_6 t$
$s x_1 x_4 x_6 t$
$s x_2 x_7 t$
$s x_2 x_5 x_7 t$

Fig. 6.

⟦folio 21⟧

create a digraph of a special type. For example, with the expression
$$((a+b) \cdot (c-d)) / (g+f) + h = L$$
you can connect the graph shown in figure 7. If the letters are not repeated in the formula, such graphs have a special name. An order tree (directed tree) is a graph in which one vertex is selected - the root of the order tree, and from any other vertex of the order tree there is only one path to the root. There is no path from the root to any vertex.

So, in our example (see Fig. 7) an order with the root $L$ is shown. The vertices $a, b, c, d, f, g, h$ are called calculable.

Exercise 7. Construct an order expression
$$\frac{\sqrt{x+y}}{z^2+5at+7k} + \frac{b+c}{r} = L.$$

Returning to figure 7, imagine that individual operations are performed at the time instant shown by the red vertical lines. Then the memory comes to keep up to 6 numbers at a time. True, this number can be reduced to 4 if the number $g, f$ is in memory at the time $t=2$ (instead of $t=1$).

Is it possible to depict our expression in an even more economical (in this sense) order?

Let's drag a camel through the eye of a needle

Consider the discrete time scale $t=1, 2, 3, \dots$. Let the computational process be organized in such a way that memory cells are filled (initial data is entered, the calculated intermediate result is written, etc.) at integer times and remain occupied for several time intervals of the selected scale. When the contents of a cell are used, it is freed. Let us also assume that at each moment of time only one memory cell is sent. The last condition allows you to number the vertices of the corresponding order,

The idea of ​​constructing order stacks, the wedge of which is small, was expressed by A.P. Ershov in 1958 and turned out to be extremely useful. For complex tasks, narrow placements are also possible, which is just right for putting a camel through the eye of a needle!

⟦folio 22⟧

hanging, go to step 4, otherwise go to step 5.

Step 4. In the second column there is 0, in the third - x. (So ​​we put $p(x) = 0, q(x) = x$.) Go to step 3.

Step 5. Let $y_1, y_2, \dots, y_k$ be the order vertices immediately preceding x, ordered so that $p(y_1) \geq p(y_2) \geq \dots \geq p(y_k)$. We'll find
$$p(x) = \max_{1 \leq s \leq k} \{p(y_s) + s - 1\}$$
$$q(x) = q(y_1)q(y_2) \dots q(y_k)x,$$
and enter the found values ​​into the second and third columns of the row in question. Let's move on to step 3.

Fig. 8.

Fig. 9.

We will now describe one of the algorithms for constructing such structures, known as the *Redrzejewski algorithm*.

Step 1. Let's build a table with n rows and three columns, where n is the number of order vertices.

Step 2. Let's fill the first column of the table from bottom to top, placing the root $x_0$ of the order in the lowest row, then in an arbitrary order of its predecessors, as long as the order of calculations is not violated anywhere (that is, any data needed for the next operation must be obtained before its execution).

In what follows, we will use $p(x)$ and $q(x)$ to denote entries in the second and third columns of the line starting with the letter x. The values ​​of the function $p$ will be numbers, the function $q$ will be sequences of letters. Let the first r lines already be filled in.

Step 3. We start filling out the next line (the previous ones are already filled); let us denote its first letter by x. If vertex x is

Repeat steps 3-5 until the entire table is filled. Then in the last line in the second column we get the width of the stacking, that is, $p(x_0) = W(Y, T)$, and in the third - the stacking of the order T, if the vertices in the sequence $q(x_0)$ are lined from left to right.

The table obtained by applying the Redrzejewski algorithm to the order at figure 7 is shown at figure 8, and the “stacked” order at figure 9.

Exercise 9. Apply the Regjewski algorithm to the order obtained in Exercise 7.
