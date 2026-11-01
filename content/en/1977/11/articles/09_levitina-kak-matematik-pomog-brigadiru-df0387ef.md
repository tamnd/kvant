---
id: 1977-11-levitina-kak-matematik-pomog-brigadiru-df0387ef
issue: kvant_1977_11
year: 1977
number: "11"
title: How the Mathematician helped the Brigadier
authors:
  - Левитина В.
rubric: raznoe
page_first: 42
page_last: 45
page_labels: 40-43
tag: RPLO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5b1026087273c90016360a6693438c2ea2da4e605f709e2226eb2220b35ecbe1
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/09_levitina-kak-matematik-pomog-brigadiru-df0387ef.md
source_content_sha256: 703fc8a9eb652169e2390217c796f98ea652bdc624fd3067784c51c4342b2096
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

V. Levitina

How the Mathematician helped the Brigadier

The main goal of the article is to show that the simplest problems that arise in practice naturally lead to fundamental concepts of mathematics.

1. The foreman receives a task

Our Foreman leads a team of 10 people who must load bricks located in two warehouses. The first warehouse has 4 thousand bricks, the second warehouse has 8 thousand. Warehouses are arranged in such a way that at least six workers must simultaneously load in the first warehouse, and from three to six workers can work in the second. The foreman needs to distribute workers so that all the work is completed in the minimum time.

What can the Brigadier do? For example, like this: first send all the workers to the first warehouse, and after loading it, six workers - the maximum allowable number - are transferred to the second warehouse. For simplicity, let’s assume that each worker takes one hour to cut some bricks. Then the time during which the team will complete all the work according to this schedule is very high, equal to $\frac{4}{10} + \frac{8}{6} = 1\frac{11}{15}$ (hours).

Would such an organization of work be the best? If so, why? And if not, how far is it from optimal? The Brigadier himself cannot answer these questions. What about you? Try it - then it will be much more interesting for you to read in the following paragraphs about the meeting of the Brigadier with the Mathematician, to which the Brigadier turned with his task.

2. Mathematician creates a model of a problem

Before taking on the solution of a problem, a Mathematician must create its mathematical model.

If we denote by $u$ and $v$ the quantity in the first and second warehouses, then for each moment in time the numbers $u$ and $v$ satisfy the following conditions:

1) $u \in \mathbb{Z}$ and $v \in \mathbb{Z}$,
2) $6 \leq u \leq 10$ or $u=0$,
3) $3 \leq v \leq 6$ or $v=0$,
4) $u + v \leq 10$.

These conditions are satisfied by the following thirteen operating modes: $\langle 6,4 \rangle$ (6 people work in the first warehouse, 4 in the second), $\langle 7,3 \rangle$, $\langle 6,3 \rangle$, $\langle 10,0 \rangle$, $\langle 9,0 \rangle$, $\langle 8,0 \rangle$, $\langle 7,0 \rangle$, $\langle 6,0 \rangle$, $\langle 0,0 \rangle$, $\langle 0,3 \rangle$, $\langle 0,4 \rangle$, $\langle 0,5 \rangle$ and $\langle 0,6 \rangle$. Let us represent them as points of the coordinate plane (Fig. 1).

The order in which the various operating modes are applied does not matter. For example, if the Foreman had first sent six workers to unload the second warehouse, and then sent the entire team to the first, the work would have been completed in the same $1\frac{11}{15}$ hours. Therefore, we can assume that loading is organized as follows: first $t_1$ hours, mode $\alpha_1$ is applied, then $t_2$ hours - mode $\alpha_2$, etc. In this case, $t_i$ may be equal to zero, i.e. mode $\alpha_i$ may not be used. For example, when loading at a distance in step 1, only $t_4 = \frac{4}{10}$ and $t_{13} = \frac{8}{6}$ are not equal to zero.

We neglect the time of transitions from warehouse to warehouse. Then the total loading time $t$ will be equal to

$$t = t_1 + t_2 + \dots + t_{12} + t_{13}. \tag{1}$$

Since each worker loads an hour of bricks, the number of workers loaded from the first warehouse ($x$ thousand pieces) and from the second warehouse

⟦folio 41⟧

Fig. 1.

(for thousands of pieces), will be expressed by equalities
$$x = 6t_1 + 7t_2 + \ldots + 0t_{12} + 0t_{13},$$
$$y = 4t_1 + 3t_2 + \ldots + 5t_{12} + 6t_{13}.$$
We fix $t$. Substituting into (2) and (3) various non-negative numbers $t_1, t_2, \ldots, t_{13}$ that satisfy conditions (1), we will obtain different points of the plane $\langle x, y \rangle$. We denote the set of all such points by $A_t$; Let's call it the time accessibility set $t$. This name is natural: $A_t$ consists of points on the plane with coordinates equal to the number of bricks (in thousands of pieces) that the team can load - respectively, from the first and second warehouses - in time $t$.

Now the Foreman’s task can be formed as follows: create a loading schedule such that the point with coordinates $\langle 4, 8 \rangle$ (this point corresponds to the given number of bricks in the warehouses) belongs to the set $A_t$ and $t$ minimally.

3. Mathematician solves a problem

First of all, the Mathematician asks for a task: he will limit himself to finding the set $A_1$, since any set $A_t$ prepares a set $A_1$ with a readiness coefficient $t$ and the center of readiness - the origin of coordinates.

Let us show that the set $A_1$ is the convex hull of some points $\alpha_1, \alpha_2, \ldots, \alpha_{13}$.

Recall that a set $M$ of points on a plane is called convex if, together with any pair of its points, it contains the entire segment with endpoints at these points (“Geometry 6”, paragraph 39). Examples of convex sets are given on figure 2; sets on figure 3 are not convex.

The convex hull of the set $M$ is the smallest convex set containing $M$ (Fig. 4). Since the intersection of any number of convex sets is convex (prove it!), the convex hull of an arbitrary set $M$ coincides with the intersection of all convex sets containing $M$ (such sets always - whatever $M$ - exist; why?). The convex hull of the set $M$ is usually denoted by the convex hull $M^*$).

To prove that the reachable set $A_1$ is the convex hull of the set $\{\alpha_1, \alpha_2, \ldots, \alpha_{13}\}$, we give the concept of a convex hull another definition.

Fig. 2.

Fig. 3.

Fig. 4. In both pairs, the right set is the convex hull of the left set.

*) From Latin conprhius (“convex”).

⟦folio 42⟧

To do this, we introduce two operations with points of the coordinate plane. We will call the sum of the points $\langle x_1, y_1 \rangle$ and $\langle x_2, y_2 \rangle$ the point $\langle x_1 + x_2, y_1 + y_2 \rangle$. The product of the point $\langle x, y \rangle$ and the number $t$ is the point $\langle tx, ty \rangle$. If each point $\alpha$ is associated with a vector defined by a pair of points $O$, $\alpha$ ($O$ is the origin), then the introduced operations with points will coincide with ordinary operations on vectors.

Prove that if the set $M$ is convex, then the set $tM$ (that is, the set of points $t\beta$, where $\beta \in M$) is also convex.

Definition. A point $\beta$ is called a convex combination of points $\beta_1, \beta_2, \dots, \beta_n$ if there are also non-negative numbers $t_1, t_2, \dots, t_n$, such as $t_1 + t_2 + \dots + t_n = 1$ and $\beta = t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n$.

Theorem. The convex hull set $M$ consists of all possible convex combinations of points from $M$.

Proof. Let us denote the set of convex combinations of points from $M$ by $Q$. If $\gamma$ and $\delta$ are arbitrary points, then the set of points of the form $t\gamma + (1-t)\delta$, where $0 \leq t \leq 1$, coincides with the segment with endpoints $\gamma$, $\delta$. From here it is easy to deduce that $Q$ is a convex set (do this!). Also, very/no, $M \subset Q$. Therefore, coincidence $M \subset Q$. Let us now prove by induction on $n$ that any convex combination $t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n(t_1 + t_2 + \dots + t_n = 1)$ of points from $M$ accepts the coincidence $M$. This will mean $Q \subset \text{conv } M$. For $n = 1$, the corresponding statement takes the form: if $\beta \in M$, then $\beta \in \text{conv } M$. This is true by the definition of a convex hull. Let now all convex combinations $n$ of points from $M$ accept the coincidence $M$. Let us prove that then the convex combination $\delta = t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n + t_{n+1}\beta_{n+1}$ (where $\beta_1, \beta_2, \dots, \beta_n, \beta_{n+1}$ are points from $M$) also takes $M$:

$$\delta = (1 - t_{n+1}) \left[ \frac{t_1}{1 - t_{n+1}}\beta_1 + \frac{t_2}{1 - t_{n+1}}\beta_2 + \dots + \frac{t_n}{1 - t_{n+1}}\beta_n \right] + t_{n+1}\beta_{n+1}.$$

From $t_1 + t_2 + \dots + t_n + t_{n+1} = 1$ it follows that

$$\frac{t_1}{1 - t_{n+1}} + \frac{t_2}{1 - t_{n+1}} + \dots + \frac{t_n}{1 - t_{n+1}} = 1.$$

By the induction hypothesis

$$\eta = \frac{t_1}{1 - t_{n+1}}\beta_1 + \frac{t_2}{1 - t_{n+1}}\beta_2 + \dots + \frac{t_n}{1 - t_{n+1}}\beta_n \in \text{conv } M.$$

From (4) it follows that the point $\delta$ lies on the segment with endpoints $\eta$ and $\beta_{n+1}$. Since $\beta_{n+1} \in M \subset \text{conv } M$ and conv $M$ is a convex set, we obtain $\delta \in \text{conv } M$. The theorem has been proven.

Thus, each point in conv $M$ is a convex combination of some endpoint in $M$. If the set $M$ is finite, then we can assume that each point from conv $M$ is a convex combination of all points from $M$.

It turns out that for an arbitrary set $M$ on the plane of each point $\beta$ the coincidence set $M$ can be obtained as a convex combination of three points $\beta_1, \beta_2, \beta_3$ from $M$ (of course, for different $\beta$ the points $\beta_1, \beta_2, \beta_3$ are, generally speaking, different). This theorem, or rather its $n$-dimensional analogue, is called *Carmedori's meorem*. Try to prove it!

By definition, the reachability set $A_1$ consists of all possible points $t_1\alpha_1 + t_2\alpha_2 + \dots + t_{13}\alpha_{13}$ for which $t_1 + t_2 + \dots + t_{13} = 1$ (item 2). In other words, $A_1$ consists of all possible convex combinations of points $\alpha_1, \alpha_2, \dots, \alpha_{13}$. According to the proven theorem

$$A_1 = \text{conv} \{ \alpha_1, \alpha_2, \dots, \alpha_{13} \}.$$

From figure 1 it is clear that $A_1$ is the set of points of the quadrilateral $\alpha_1\alpha_2\alpha_3\alpha_{13}$ (the point $\alpha_2$ lies on the line $\alpha_1\alpha_4$).

To find the minimum $t$ for which the set $A_t = t \cdot A_1$ contains the point $\beta$ ($\langle 4, 8 \rangle$ (Fig. 5), we calculate the coordinates of the point $\gamma$ of the intersection of the lines $\alpha_9$ $\beta$ and $\alpha_1\alpha_{13}$. The equation of the line passing through

⟦folio 43⟧

Work press $\alpha_1$ for $t \cdot t_1 = \frac{8}{9}$ (hour) and work mode $\alpha_{13}$ for $t \cdot t_{13} = \frac{2}{3}$ (hour). The time that all the work would have taken according to the schedule drawn up by the Foreman in paragraph 1 was equal to $1 \frac{11}{15}$ hours, which is $1 \frac{4}{35}$ times more than the found minimum time.

Let's summarize. We see that the Brigadier's problem, which is not at all geometric, naturally led us to convex figures on the plane. It turns out that the concept of convexity can be defined not only for geometric - flat or spatial - objects, but also in a much more general situation (for example, in the so-called vector spaces - see «Kvant», 1976, No. 4, p. 2). In this generalized form, it “works” in many areas of mathematics (functional analysis, mathematical programming, game theory).

You can get acquainted with interesting problems solved using the concept of convexity in the book by I. M. Yaglom and V. G. Boltyansky “Convex Figures” (M. - Leningrad, Gostekhidat, 1951).

The Brigadier's problem can also be solved purely algebraically - using linear programming methods. How this is done was described in «Kvant», 1976, No. 7, p. 2. With this approach, it is useful to note that it is possible (see Fig. 1) to consider only those schedules for which

$$t_3 = t_5 = t_6 = t_7 = t_8 = t_9 = t_{10} = t_{11} = t_{12} = 0.$$

Exercises

1. Make a schedule for the Foreman if
a) in the first warehouse - 16 thousand bricks, in the second - 4 thousand;
b) at least 7 people must work in the first warehouse at the same time.
2. There is a frying pan in which you can fry two cutlets at the same time. Each cutlet is fried on one side for one minute. How long does it take to fry three cutlets?
