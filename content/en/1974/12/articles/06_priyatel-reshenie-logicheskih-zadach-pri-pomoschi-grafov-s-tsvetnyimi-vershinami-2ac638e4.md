---
id: 1974-12-priyatel-reshenie-logicheskih-zadach-pri-pomoschi-grafov-s-tsvetnyimi-vershinami-2ac638e4
issue: kvant_1974_12
year: 1974
number: "12"
title: Solving logical problems using graphs with colored vertices
authors:
  - Приятель А.
rubric: osnovnye-stati
page_first: 17
page_last: 24
page_labels: 15, 16, 17, 18, 20, 21, 22
tag: HG0I
lang: en
source: kvant_digital
extraction: vision
content_sha256: b87d23f682a10c01bb31abff9d1535e8287a9e3aadf7b4fb3783d07c2d67c6d8
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/06_priyatel-reshenie-logicheskih-zadach-pri-pomoschi-grafov-s-tsvetnyimi-vershinami-2ac638e4.md
source_content_sha256: 7dfe36de8ce73c0523f8e300fcd8832f9fa98f2dc974e19f60eee0f513586071
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

In «Kvant» No. 8 for 1973, an article by L. Yu. Berezina “On graphs with colored edges” was published, devoted to solving logical problems. No less interesting is the method of solving logical problems using graphs with colored vertices, which allows you to find solutions to problems that are often called “logical problems on Johnson and Smith” *). This method consists of depicting the structure of a problem using a graph. The vertices of such a graph will indicate the basic statements of the problem; and the edges of the graph are implications or connections between basic statements. The color of the vertex will indicate the truth or falsity of the statement being depicted. The described method consists of determining the color of the vertices of the graph. Throughout the following, we will call the process of determining the color of vertices graph coloring. The color of the vertex will not always be determined uniquely; perhaps we will call varnatas coloring.

To depict the structure of a problem using a graph, we will agree on a symbol that allows us to change from the language of logic to the language of graphs:

Table 1

Logical concept Graph element

Statement Vertex of the graph
True statement The top is red
False statement Top black
Implication $X \Rightarrow Y$ Oriented edge $\overrightarrow{XY}$ of a graph

Coloring of graphs is carried out according to the rules of logical algebra, which are translated into the language of graphs using the following symbols:

Table 2

Logic algebra rule Graph coloring rule

1. Every statement has one and only one of two truth values: “false”, “true”.
2. If the implication $X \Rightarrow Y$ is true and the premise $X$ is true, then the conclusion $Y$ is true.
3. If the implication $X \Rightarrow Y$ is true and the conclusion $Y$ is false, then the premise $X$ is false.

1. Each vertex of the graph is either black or red.
2. If edge $\overrightarrow{XY}$ is oriented from vertex $X$ to vertex $Y$ and vertex $X$ is red, then vertex $Y$ is red.
3. If edge $\overrightarrow{XY}$ is oriented from vertex $X$ to vertex $Y$ and $Y$ is black, then $X$ is black.

*) You can, of course, talk about “problems about Vorobyov and Grachev” - everyone remembers the parody of them from “The Golden Calf”.

⟦folio 16⟧

In addition to these rules 1-3, additional rules can be introduced for each specific task (depending on the structure of the graph used).

Let us demonstrate the method using examples of solving specific problems.

Problem 1

For a clearing expedition from all pretensions $A, B, C, D, E, F, G$ and $H^*$, six specializations must be displayed: biology, hydroLOGa, cyoptics, doctor, mechanics and radio. The duties of biology can be performed by $E$ and $G$, hydroLOGа - $B$ and $F$, syoptics - $F$ and $G$, doctor - $A$ and $D$, radiotics - $C$ and $D$, mechanics - $C$ and $H$. Although some of the claims are compatible with two specialties, in each expedition only one obligation must be fulfilled.

This is who should be taken on the expedition if we don’t want to take $F$. We don’t want to go without $B$, $D$ without $H$ and without $C$, $C$. We don’t want to go with $G$, and we don’t want to go with $A$. $B$?

The basic set of statements of the problem consists of all statements of the form “$A, B, C, \dots$” is included in the expedition” (we will denote them by the letters $A, B, C, \dots$, respectively).

To make it easier to understand the conditions of the problem, let us depict the specialization of the applicants using the so-called bipartite graph, that is, a graph whose vertices fall into two classes (two “dolly”) so that the vertices from the same class are not interconnected (not connected by edges). It is convenient to draw bipartite graphs by arranging the vertices of one “dolly” in a line, and the vertices of the other in a line parallel to the first (Fig.1).

On figure 1 we depicted applicants as vertices $A, B, \dots, H^*$ of the first part, and specialties as vertices $6, 8, \dots, c$ (“b”) - biologist, “c” doctor, etc.) of the second part. The vertex of the first share is connected with the vertices of the second share, if the corresponding applicant has the corresponding specialty. Using such a graph, it is easy to determine which two applicants own the corresponding one.

Of the two candidates $X$ and $Y$, who have the same specialty, at least one is taken over, that is, a disjunction of the form $X \lor Y$ is true, equivalent to the implication $\bar{X} \Rightarrow Y^{**}$). Based on this we can write

$(\bar{E} \Rightarrow G) \wedge (\bar{B} \Rightarrow F) \wedge (\bar{F} \Rightarrow G) \wedge (\bar{A} \Rightarrow D) \wedge (\bar{C} \Rightarrow D) \wedge (\bar{C} \Rightarrow H)$.

In addition, if $X$ does not want to Exit without $Y$, then the implication $\bar{Y} \Rightarrow \bar{X}$ is true, and if $X$ does not want to Exit together with $Y$, then the implication $Y \Rightarrow \bar{X}$ is true. Based on this we have

$(\bar{B} \Rightarrow \bar{F}) \wedge (\bar{H} \Rightarrow \bar{D}) \wedge (\bar{C} \Rightarrow \bar{D}) \wedge$
$(\bar{G} \Rightarrow \bar{C}) \wedge (\bar{B} \Rightarrow \bar{A})$.

So, the conditions of the problem can be represented in the form of an implication conjunction:

*) Of course, these are just their names: Johnson, Smith, Brown, ... (Vorobiev, Grachev, Drozdov, etc.).
**) Or $\bar{Y} \Rightarrow X$ - it doesn’t matter.

⟦folio 17⟧

Fig. 2.

Let's imagine the structure of the problem in the form of a graph. In this case, we will place the vertices depicted as non-negative statements of the form $X$ on one straight line, and the vertices of the form $\bar{X}$ on a line parallel to it so that $A$ and $\bar{A}$, $B$ and $\bar{B}$, etc. are located in vertical columns. The content of the implication (1) in condition 11 is represented by the oriented edges of the graph (according to the data in Table 1, see Fig. 2).

When coloring a graph, we will always start with an assumption about the color of one of the vertices $X$ of the graph. We will choose this vertex $X$ so that the sum of its connection $r(X)$ with the $r(\bar{X})$ connection of vertex $\bar{X}$ is the same as in this case the color of vertex $X$ gives maximum information about the color of other vertices. In some cases, one assumption allows one to completely and unambiguously color the graph or leads to a contradiction, in others it is necessary to make new assumptions. It is followed when the information provided by the ultimate assumption is exhausted (the chain of alienations is broken).

Complete coloring of the graph gives a solution to the problem; a contradiction indicates that the assumption is incorrect. Two assumptions can be made about the color of vertex $X$: “$X$ is red”, “$X$ is black”. Both assumptions must be used; Only then is it possible to exhaust all coloring options.

Let us now introduce additional coloring rules 4--6:

Rule 4
If the statement is true, then the negation is false, and vice versa.

Rule 5
If six applicants were included in the expedition, the rest were excluded.

Rule 6
If two claimants are truly from the expedition, then the rest were included.

Now, guided by rules 1-6, we can color the graph shown in figure 2:

1. Let's assume that vertex $C$ is red. Then:
1) $\bar{C}$ — black (4) *); 2) $G$ - black (3); 3) $\bar{E}$, $\bar{F}$ - black (3); 4) $\bar{B}$ - black (3); 5) $E$, $F$ and $B$ - red (4); 6) $\bar{G}$ - red (4); 7) $\bar{A}$ - red

*) Here and in what follows, the numbers in brackets indicate the number of the rule on the basis of which the conclusion about the color of the vertex is made.

⟦folio 18⟧

Fig. 3.
naya (2); 8) $A$ - black (4); 9) $D$ - red (2); 10) $\bar{D}$ - black (4);
11) $\bar{H}$ — black (3); 12) $H$ - red (4).

The obtained result is consistent with rules 5 and 6. Therefore, if $C$ is included in the expedition, then we must also include $B, D, E, F$ and $H$ and exclude $A$ and $G$.

II. Let's assume that vertex $C$ is black (Fig. 3):

1) $\bar{C}$ — red (4); 2) $\bar{D}$ - red (2); 3) $D$ - black (4); 4) $D$ - red (2).

Since $D$ cannot be both red and black (1), the assumption “$C$ is black” leads to a contradiction; This means that $C$ is red, and the problem has a unique solution:

$B, C, D, E, F, H (\bar{A}, \bar{G})$.

It remains to be determined what position each of the six included in its composition will occupy in the expedition. To do this, we will have to use a graph with colored edges.

Let us redraw the graph shown in figure 1, excluding the vertices $A$ and $G$ and the edges associated with them (Fig. 4). The edges of the graph are often painted in the same color, so that it is convenient to “point” (paint) them with other colors later. Let us agree that the edge connecting the vertex $X$ of the first part with the vertex $a$ of the second part will be red if $X$ occupies the position $a$, and black if $X$ does not occupy this position (for example, “$Fc$ is red” if $F$ occupies the position of weather forecaster, and “$Dp$ - black" means that $D$ does not hold the position of radio operator).

When determining the color of the ribs, we will be guided by the following rules:

Rule 7
If only one of the values ​​in the expedition can take position $a$, then he will have to take it.

Rule 8
If some $X$, a member of the expedition, comes to occupy the position $a$ due to condition 7, then he cannot occupy any other.

Guided by rules 7-8, color the graph on figure 4:

1) $E\delta$ - red (7); 2) $Fc$ - red (7); 3) $F\epsilon$ - black (8); 4) $B\epsilon$ —

⟦folio 20⟧

We will mainly teach five vertices representing skates: $(D \wedge E), (F \wedge \bar{A}), (\bar{F} \wedge E), (\bar{D} \wedge \bar{H})$ and $(E \wedge \bar{A})$.

We will call the vertices representing conyons of the form $X \wedge Y$ the resulting vertices, and the vertices $X$ and $Y$ their components (say, the vertex $F \wedge \bar{A}$ is the resultant of the components $F$ and $\bar{A}$).

What is the resulting connection with its two constituent unoriented red edges. We depict the implications contained in the conditions of the problem as in problem 1 (Fig. 5).

We will also use coloring rules 1–4 when coloring the graph on figure 5. In addition, we introduce additional rules 9–13:

Rule 9
If $X$ is true and $Y$ is true, then $X \wedge Y$ is true.

Rule 10
If $X \wedge Y$ is true, then $X$ and $Y$ are true.

Rule 11
If $X$ or $Y$ is false, then $X \wedge Y$ is false.

Rule 12
If $X \wedge Y$ is false and $X$ is true, then $Y$ is false.

Rule 13
If some assumption excludes the possibility of inviting several guests, and all the rest can be invited without receiving any opposition, then this should be done (to maximize the number of guests).

Using rules 1-4 and 9-13, let's color the graph by figure 5:
I. Let us assume that $G$ is red:

⟦folio 21⟧

1) $\bar{G}$ — black (4); 2) $B$ - black (3); 3) $C$ - black (3); 4) $E \wedge \bar{A}$ - black (3); 5) $\bar{D} \wedge \bar{H}$ - black (3); 6) $\bar{B}$ and $\bar{C}$ - red (4).
Let us now assume (using Rule 13) that $D$ is red:
7) $E$ — red (2); 8) $D \wedge E$ - red (9); 9) $\bar{A}$ - red (2); 10) $E \wedge \bar{A}$ - red (9).

But according to rules 1, $E \wedge \bar{A}$ cannot be both black (step 4) and red (step 10), which means that if $G$ is red, then $D$ is black.

Let's construct a new graph (Fig. 6) and use the results of the first six steps on it. Color the graph at figure 6, assuming that $D$ is black:
11) $\bar{D}$ — red (4); 12) $D \wedge E$ - black (11); 13) $\bar{H}$ - black (12);
14) $H$ — red (4); 15) $F \wedge \bar{A}$ - black (3); 16) $\bar{F} \wedge E$ - black (3).
Let's assume that $E$ is red (13):
17) $\bar{E}$ — black (4); 18) $\bar{F}$ - black (12); 19) $F$ - red (4); 20) $\bar{A}$ - red (12); 21) $A$ - red (4).

Following rules 13, we made all three remaining vertices red: $E, F$ and $A$. Then from graph figure 6 it follows that if you invite $G$, then, in addition, you can invite $A, E, F$ and $H$ (5 guests in total).

In the considered variant (under the assumption “$G$ is red”) three vertices $B, C$ and $D$ turned out to be black. Let's check whether in the case of “$G$ - black” we can get at least five red vertices, that is, no more than three black ones.

II. Let's assume that $G$ is black (Fig. 7). Then:
1) $\bar{G}$ — red (4); 2) $F$ - black (3); 3) $\bar{F}$ - red (4);
4) $F \wedge \bar{A}$ - black (11).
Let now $D$ be red (13):
5) $E$ - red (12); 6) $\bar{E}$ - black (4); 7) $B$ - black (3);
8) $D \wedge E$ — red (9); 9) $\bar{A}$ - red (2); 10) $A$ - red (4).

Thus, already four vertices turned out to be black ($A, B, F, G$).

Let's redraw the graph figure 7 (Fig. 8) - use the results of the first four steps and assume that $D$ is black. Then there are already three vertices that are black ($D, F$ and $G$), which means that in order to get at least five red vertices, it is necessary to make all other vertices of the type $X$ red.

But this is impossible, because if $A$ is red, then

⟦folio 22⟧

11) $\bar{A}$ — black (4); 12) $B$ - black (3).

Thus, the assumption “$G$ is black” does not produce more than four red vertices of the form $X$. The largest number of such vertices (five) is given by the assumption “$G$ is red”.

The answer follows from graph figure 6:
$N$ could invite a maximum of five guests: $A, E, F, G$ and $H$.

Then e. When considering all four coloring options (Fig. 5–8), it was possible to limit ourselves to only one graph. To do this, its vertices had to be made in the form of circles of sufficiently large diameter, divided into four squares, and when considering each option, one square had to be painted over.

* *

In conclusion, we note that problems 1 (on the presence of a triangle with single-valued sides in a graph with six vertices and edges of two colors) and 5 (on the presence of such a triangle in a graph with seventeen vertices and edges of three colors) from the article by L. Yu. Berezina “On graphs with colored edges” admit the following generalization (proposed at the XIII Ukrainian Republican Olympiad for Young Mathematicians):

Problem 3

The sequence $\{a_n\}$ is given using the recurrent formula: $a_1 = 2; a_n = n a_{n-1} + 1$. Prove that in a graph $c a_n + 1$ with a vertex whose edges are surrounded by $n$ colors, there is a triangle with single-valued sides.

Let's use the method of mathematical induction.

1. At $n = 1$ $a_1 = 2$. Number of vertices $a_1 + 1 = 3$.

The graph is a triangle with edges of the same color (that is, the desired triangle).

2. Let the statement be true for $n = k$, that is, in a graph with the number of colors $k$ and the number of vertices $a_k + 1$ there is a triangle with single-valued sides. Let now $n = k + 1$. Then the number of vertices is

$$a_{k+1} + 1 = [(k + 1) \cdot a_k + 1] + 1.$$

Let's select one of the vertices; Let's call it $A$. It is connected by edges $k + 1$ of color with vertices, the number of which is $(k + 1) \cdot a_k + 1$. Among these edges, at least $a_k + 1$ are of the same color (according to the Dirichlet principle*)) for definiteness - blueERO. If one of the $a_k + 1$ vertices $B$ is connected to another $C$ by an edge, then the triangle $\Delta ABC$ is the desired one. If not, the blue color is not used in the graph consisting of $a_k + 1$ vertices, and then only $k$ colors are used there. According to the proposal, this graph (which is part of the original one) contains the desired triangle, which means it also has it in the original one.

The statement has been proven.

In particular, at $n = 2$ (two colors) $a_2 = 2 \cdot 2 + 1 = 5, a_2 + 1 = 6$ (six vertices); at $n = 3$ (three colors) $a_3 = 3 \cdot 5 + 1 = 16, a_3 + 1 = 17$ (seventeen vertices).

(In all these problems we mean complete graphs in which any pair of vertices is connected by an edge.)
