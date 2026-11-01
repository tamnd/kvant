---
id: 1987-3-yarskiy-neravenstva-s-parametrom-01477d23
issue: kvant_1987_3
year: 1987
number: "3"
title: Inequalities with parameter
authors:
  - Ярский А. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 54
page_labels: 49-52
tag: W50F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 75bef234010a80115f01891b803320761e566917aba3ff7fc3f9c55d1fff9a62
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/14_yarskiy-neravenstva-s-parametrom-01477d23.md
source_content_sha256: 544a43830aefb4fb23110cbc79dc5d505cb19f53b23b9dee09a43a968deab478
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Inequalities with parameter

Candidate of Physical and Mathematical Sciences
A. S. YARSKY

In this article the reader will find a general method for solving the
inequalities with a parameter that appear on entrance exams.

Example 1 (LSU, Mat.-Mex., 1965)
Solve the inequality
$$\log_x (x-a) > 2.$$ (1)

1. Let us find the domain of definition of inequality (1):
$$x > 0, x \neq 1, x-a > 0.$$

2. Let us solve the corresponding inequality
according to (1) equation
$$\log_x (x-a) = 2 \Rightarrow x-a = x^2.$$

Let us depict the region in the Ox plane
definitions and schedule of the latter
functions in one drawing. As for-
functions, it is easier to express a
through x: $a=x-x^2$ is a parabola in the Ox plane. We need to find out how to dis-
this parabola is placed in relation to the straight line $x=a$ - the boundary of the region
definitions. It turns out that these couple
The ball and the straight line have exactly one common point (0; 0) (check). All I say is
what is given is reflected on figure 1. The definition area on figure 1 is shaded. In red (over the entire
in the entire statistic) the lines are depicted at the points of which this inequality is not defined or is not fulfilled.
no. (Note that it was necessary to select only the part of the parabola that fell within the definition area.)

So, the domains of definition are divided
fell into four parts $D_1, ..., D_4$.

It turns out that the following is true:
sche.

Offer. Each of the domains $D_1, ..., D_4$ has the following property: either inequality (1) is satisfied at all points of the domain, or it is unequal at no point.

⟦folio 50⟧

In other words, each of the region $D_1, \dots, D_4$ is either completely included or completely not included in the answer.

Initially, this statement does not raise doubts. Indeed, the reason why the sign of inequality (1) can change as a result of moving from a point in the region $D_1$ to a point in the region $D_2$ is clear - we cross the “red” line, that is, we beat at the point where the functions included in the inequality are not defined.

When moving from $D_1$ to $D_3$ you will also have to cross the “red” line - it breaks at the point where inequality (1) turns into an inequality. And when moving from one point of the region $D_1$ to another point, no “red” lines are visible, which means there is no reason for changing the inequality sign!

All of these essentially true statements require proof. Unfortunately, such a proof requires knowledge, we go beyond the school curriculum...

If we take on faith the validity of the assumption, then the solution to the inequality can be completed by a simple

3. Examination. In each of the region $D_1, \dots, D_4$ we arbitrarily select one point, for example, $A_1\left(\frac{1}{2}; \frac{3}{8}\right) \in D_1$,

$$A_2(2; 0) \in D_2, \quad A_3\left(\frac{1}{2}; -1\right) \in D_3,$$

$$A_4(2; -3) \in D_4$$ (check if these points fall within the corresponding areas). Substituting the selected values ​​$(x; a)$ into inequality (1), we find that the inequality is satisfied only at points $A_1$ and $A_4$. This means, according to the Proposition, that the inequality holds at all points of the region $D_1$ and $D_4$ and only at these points.

4. How to write down the answer. By tradition, $x$ denotes an unknown, $a$ a parameter. Therefore, it is necessary to indicate how $x$ changes depending on the value of the parameter $a$. Let us first choose an arbitrary $a < 0$. The set of points on the plane $Oxa$ with fixed $a$ forms a horizontal line. We need to find out at what values ​​$x$ the point of this line is in the region $D_4$. From figure 2 it is clear that $x \in ]x_1; x_2[$ (“red” boundaries are not included in the answer), where $x_1 = 1$, and the point $(x_2; a)$ lies on the parabola $a = x - x^2$. Hence $x_2^2 - x_2 + a = 0$ and $x_2 = (1 + \sqrt{1 - 4a})/2$ (think about why the “+” sign was chosen for the radial). So, if $a < 0$, then $x \in ]1; (1 + \sqrt{1 - 4a})/2[$.

For $a = 0$, as can be seen from figure 1, the inequality has no solutions. Moving the horizontal line above, we see (see Fig. 3) ​​that if $a \in ]0; 1/4[$, then $x \in ]x_1; x_2[\cup]x_3; 1[$; if $a \in ]1/4; 1[$, then $x \in ]x_4; 1[$; if $a \geq 1$, then the inequality has no solutions. Let's express $x_1, x_2, x_3, x_4$ through $a$: $x_1 = a$, $x_2 = (1 - \sqrt{1 - 4a})/2$, $x_3 = (1 + \sqrt{1 - 4a})/2$, $x_4 = a$. And combining the found formulas, we get

Answer: If $a \in ]-\infty; 0[$, then $x \in ]1; (1 + \sqrt{1 - 4a})/2[$; if $a = 0$, then $x \in \emptyset$; if $a \in ]0; 1/4[$, then $x \in ]a; (1 - \sqrt{1 - 4a})/2[\cup](1 + \sqrt{1 - 4a})/2; 1[$; if $a \in ]1/4; 1[$, then $x \in ]a; 1[$; if $a \in ]1; +\infty[$, then $x \in \emptyset$.

The solution presented contains a serious flaw - a reference to a correct but unproven assumption. Regarding such a decision, the examiner will conclude: “The answer is correct, but not justified!” And the task will not be read to the applicant. Therefore, to completely solve the problem, additional

5. Rationale. Inequality (1) is equally satisfied by one of two systems of inequalities:

$$\begin{cases} 0 < x < 1, \\ x - a < x^2, \end{cases}$$ or $$\begin{cases} 0 < x < 1, \\ a > x - x^2, \end{cases}$$ or $$\begin{cases} x > 1, \\ a < x - x^2. \end{cases}$$

The first of the two systems describes a set on the plane $Oxa$, lying in the strip between the lines $x = 0$ and $x = 1$

⟦folio 51⟧

Fig. 4.

and at the same time - above the parabla $a=x-x^2$, i.e. (taking into account the domain of definition) - exactly the region $D_1$ (see Fig. 1). Similarly, the second system describes the region lying to the right of the line $x=1$ and below the parabla $a=x-x^2$ - the region $D_4$. The answer found earlier is completely justified.

It is easy to notice that clause 5 made the check in clause 3 unnecessary. However, it is unwise to postpone checking: it is simple, allows you to quickly get an answer and, most importantly, makes the method of solving the essential more reliable.

When formulating a solution to a problem, it is best to leave the check that played its role in the draft - it is no longer needed - and write in its place the calculations from point 5.

Example 2 (LSU, Mat.-Mex., 1966). Solve the inequality
$$\sqrt{a+\sqrt{x}}+\sqrt{a-\sqrt{x}}<\sqrt{2}.$$
(2)

1. Let us find and depict the domain of definition on the plane $Oxa$:
$$x \geq 0, a+\sqrt{x} \geq 0, a-\sqrt{x} \geq 0.$$
The result is an area located to the right of the straight line $x=0$ and above the parable $a=\sqrt{x}$, which is shown in figure 4 (the boundaries included in the definition area are depicted in a different color).

2. Let us solve the equation corresponding to inequality (2)
$$\sqrt{a+\sqrt{x}}+\sqrt{a-\sqrt{x}}=\sqrt{2}.$$
Since both sides of the equation are non-negative, then, squaring, we obtain (taking into account the domain of definition) an equivalent equation:
$$2a+2\sqrt{a^2}-x=2 \iff \sqrt{a^2}-x=1-a \iff \left\{ \begin{array}{l} a^2-x=1-2a+a^2, \\ 1-a \geq 0 \end{array} \right. \iff \left\{ \begin{array}{l} x=2a-1, \\ a \leq 1. \end{array} \right.$$
Now you need to combine the domain of definition (Fig. 4) and the found straight line $x=2a-1$ in one drawing. It is easy to check that this line and the parabola $a=\sqrt{x}$ have only one common point (1; 1) (check). By depicting that part of the beam $x=2a-1,$

Fig. 5.

$a \leq 1$, which falls into the domain of definition, we obtain figure 5. So, the domain of definition is divided into two parts $D_1$ and $D_2$. Just like in example 1, each of these areas can only be fully included in the response.

3. Examination. Let's select points $A_1(1/25; 1/4) \in D_1$, $A_2(1; 2) \in D_2$. Substituting the coordinates of these points into inequality (2), we find that the inequality is satisfied only at the point $A_1$, and therefore in the region $D_1$ (and on the “blue” part of its boundaries). Considering the intersection of the region $D_1$ with all possible horizontal lines, we obtain

4. Answer:
if $a \in ]-\infty; 0[\cup[1; +\infty[$, then $x \in \emptyset$; if $a \in [0; 1/2[$, then $x \in [0; a^2]$; if $a \in [1/2; 1[$, then $x \in ]2a-1; a^2]$.

As in example 1, the answer received needs justification.

5. Rationale. Let us transform inequality (2):
$$\sqrt{a+\sqrt{x}}+\sqrt{a-\sqrt{x}}<\sqrt{2} \iff 2a+2\sqrt{a^2}-x<2 \iff \sqrt{a^2}-x<1-a \iff \left\{ \begin{array}{l} a \leq 1, \\ a^2-x<1-2a+a^2, \end{array} \right. \iff \left\{ \begin{array}{l} a \leq 1, \\ x>2a-1. \end{array} \right.$$
The last system of inequalities is described lying below the line $a=1$ and to the right of the line $x=2a-1$, i.e. (taking into account the domain of definition) the region $D_1$. The answer is justified.

Example 3 (MSU, Faculty of Chemistry, 1984). Find all $a$ for which the inequality
$$\frac{1}{2}|a-2||x+a-4|+
+\left(\frac{a^2-4a+3}{|a-2|}-|a-2|\right)|x-2|+
+\frac{1}{2}|a-2||x-a| \leq 1$$ (3)

⟦folio 52⟧

holds exactly for two values ​​of $x$.

We will do more than what is required in the problem - we will solve the inequality. Then, of course, the answer to the question posed will be received.

1. Definition area: $a \neq 2$.
2. Let us transform inequality (3). Multiplying both sides by $2|a-2| > 0$ and taking into account the equality $|a-2|^2 = (a-2)^2$, we get $(a-2)^2|x+a-4| + 2(a^2-4a) + 3-(a-2)^2|x-2| + (a-2)^2|x-a| \leq 2|a-2| \Leftrightarrow (a-2)^2|x-2+a-2| - 2|x-2| + (a-2)^2|x-2-(a-2)| \leq 2|a-2|$.

Now we increase the replacement $x-2=y$, $a-2=b \neq 0$ ($a \neq 2$), bringing the last inequality to the form
$$b^2(|y+b|+|y-b|) \leq 2(|b|+|y|).$$

So, we have to depict the set of points of the plane $Oyb$, the coordinates of which satisfy inequality (4). Note that replacing $(y; b)$ with $(y; -b)$ or $(-y; b)$ does not change anything in inequality (4) (check). This means that the desired set has symmetry with respect to both axes $Oy$ and $Ob$. Therefore, it is enough to draw only the part of the desired set located in the first quarter and then use symmetry. In the first quarter $|y|=y$, $|b|=b$, $|y+b|=y+b$, and inequality (4) takes the form
$$b^2(y+b+|y-b|) \leq 2(b+y).$$

It remains to reveal $|y-b|$. In the region $y \geq b$: $|y-b|=y-b$, and the equation corresponding to inequality (5) takes the form
$$2b^2y=2(b+y) \Leftrightarrow y=b/(b^2-1).$$

Now draw a little part of the graph of this function, located in the region $y \geq b$ (Fig. 6). In the region $y < b$: $|y-b|=b-y$, and the equation corresponding to inequality (5) takes the form
$$b^2 \cdot 2b=2(b+y) \Leftrightarrow y=b^3-b.$$

It remains to draw part of the graph of the last function that falls in the region $y < b$ (see Fig. 6).

3. Checking shows that of the two regions into which the first quarter was divided, inequality (5) is satisfied by the region shaded at figure 6. Using symmetry, we obtain the complete picture (Fig. 7). Now from figure 7 it is clear that only for $b=\pm \sqrt{2}$ inequality (4) is satisfied by exactly two different values ​​of $y$. And we returned to the original variable $a$, we get $a=b+2 \pm \sqrt{2}$.

4. Answer: $a=2 \pm \sqrt{2}$.

5. Rationale. Let us transform inequality (5) (we consider the first quarter $y \geq 0$, $b > 0$):
$$b^2(y+b+|y-b|) \leq 2(b+y) \Leftrightarrow b^2|y-b| \leq (2-b^2)(b+y) \Leftrightarrow -(2-b^2)(b+y) \leq b^2(y-b) \leq (2-b^2)(b+y).$$

This system of inequalities can be easily rewritten in the form
$$\begin{cases} y \geq b^3-b, \\ y(b^2-1) \leq b. \end{cases}$$
