---
id: 1975-1-lopshits-funktsionalnyie-uravneniya-1401bd9c
issue: kvant_1975_1
year: 1975
number: "1"
title: Functional equations
authors:
  - Лопшиц А. М.
rubric: osnovnye-stati
page_first: 32
page_last: 37
page_labels: 30-35
tag: YMR9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1b2cf1de1cedb8f5d89d3db45e1ea6121259705c6381cf4cefdcb5f346d6d685
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/09_lopshits-funktsionalnyie-uravneniya-1401bd9c.md
source_content_sha256: 1ff2952722a800f417005a853b241ef3340e5fde6d37c8524023d10f86ff9465
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Functional equations
A. M. Lopshitz

Before you start reading this article, you need to make sure that you have a good grasp of the important mathematical concept of “function”. Therefore, we advise you to read the article by A. N. Kolmogorov \*) and those pages of school textbooks in which this concept is introduced and explained.

Let us recall that to specify a function of a real argument, the values of which are also real numbers (we will only consider such functions in our article), you should: 1) first of all indicate the “domain of its definition”, that is, indicate the set of real numbers from which the values $x$ of the argument will be selected, and 2) clearly formulate the rule according to which for each such value $x$ the corresponding real number will be constructed - it is called: the value of the function corresponding to the selected the value of the argument. If any function is denoted by, say, $Ф$, then the value it takes for the chosen argument value $x$ is denoted $Ф(x)$.

It is useful to give each function (each rule) under consideration a name. So, for example, a function whose domain of definition is the set of all real numbers, and the rule for constructing the value of functions corresponding to the definition

---
\*) «Kvant», 1970, Nos. 1 and 2.

⟦folio 30⟧

⟦column⟧

given the value $x$ of the argument, is that this value is multiplied by some fixed real number $a$, called a *linear homogeneous function*.

It is this function that will be the main character of our article.

**1. Linear homogeneous function is additive**

Among the various functions studied in mathematics, the reader undoubtedly noted one that stands out among the rest for its special simplicity - this function $Л_a$ is defined for all real values ​​of the argument $x$ and its values ​​are determined by the formula

$$Л_a(x) = ax$$

(in which $a$ is some given real number). We called it: *linear homogeneous function*. It is found in all those problems of physics (and not only physics) in which proportional quantities are studied.

Teachers' observations show that schoolchildren feel one of its properties very well, so well that they often (even too often!) attribute it to other, more complex functions. In fact, has the student reader noticed that some of his class friends, having started studying trigonometric functions, believe that the sine of the sum of two angles is equal to the sum

what are the sines of these angles? The essence of this “childish” mistake is that a schoolchild, having become acquainted with some new function—let’s call it $\Phi$—is inclined to believe that it must have the following “simple” property:

$$\Phi(x_1 + x_2) = \Phi(x_1) + \Phi(x_2). \qquad (1)$$

A linear homogeneous function really (check!) has this property, but, alas, other functions studied in school *do not have it*.

Any function that has the property expressed by equality (1) is called an *additive* function. It is easy to check that a *linear inhomogeneous* function, that is, the function $G$, defined for any real value of the argument by the formula

$$G(x) = ax + b \qquad (b \neq 0),$$

is no longer additive; in the same way, functions defined for any value of the argument $x$, the values ​​of which are determined according to the following rules, do not have the property of additivity:

$$x \to ax^2 + bx + c,$$
$$x \to \frac{1}{x^2 + a^2},$$

and many, many other features.

Is there at least one additive function of a real argument that is different from a linear homogeneous one, the reader will ask.

He will get the answer to this question if he is not too lazy to carefully read this short article.

**2. Research of arbitrary additive function**

1. If the function $\Phi$ has property (1), then it is easy to check that it also has the following property:

$$\Phi(x_1 + x_2 + x_3) =$$
$$= \Phi(x_1) + \Phi(x_2) + \Phi(x_3). \quad (1'),$$

Indeed, due to property (1)

⟦column⟧

we have

$$\Phi(x_1 + x_2 + x_3) = \Phi((x_1 + x_2) + x_3) =$$
$$= \Phi(x_1 + x_2) + \Phi(x_3) =$$
$$= \Phi(x_1) + \Phi(x_2) + \Phi(x_3).$$

It will not be difficult for the reader to prove that

$$\Phi(x_1 + x_2 + \ldots + x_n) =$$
$$= \Phi(x_1) + \Phi(x_2) + \ldots + \Phi(x_n) \qquad (1'')$$

(you will, of course, have to use the method of mathematical induction).

The formula $(1'')$ implies the equality

$$\Phi(nx) = n\Phi(x) \qquad (2)$$

($n$ is an arbitrary *integer* positive number).

Since equality (2) is valid for any value of $x$, let us set $x$ equal to $\frac{m}{n} y$ ($m$ and $n$ are positive integers). We get

$$\Phi(my) = n\Phi\left(\frac{m}{n} y\right).$$

Using equality (2) again, we get

$$m\Phi(y) = n\Phi\left(\frac{m}{n} y\right),$$

that is

$$\Phi\left(\frac{m}{n} y\right) = \frac{m}{n} \Phi(y). \qquad (2')$$

So, we are convinced that if the function $\Phi$ is additive, then for any positive rational number $\alpha = \frac{m}{n}$ the equality holds

$$\Phi(\alpha x) = \alpha\Phi(x) \qquad (3)$$

(whatever the real number $x$ is!).

This remarkable relation gives us *the ability to calculate for any additive function $\Phi$ its value for any positive rational value $x$ of the argument, if only one of its values ​​is given - namely, the one it takes when the argument is equal to one.*

In fact, setting $x$ equal to one in (3), we obtain

$$\Phi(\alpha) = \alpha\Phi(1). \qquad (4)$$

⟦folio 31⟧

⟦folio 32⟧

2. No less surprising is that *formula (4) for calculating the values ​​of any additive function Ф is applicable for all rational values ​​of the argument* (and not just for its positive values).

a) First of all, let’s make sure that

$$\Phi(0) = 0\Phi(1),$$

that is, what

$$\Phi(0) = 0.$$

Indeed, due to the additivity of the function $\Phi$, the equality holds

$$\Phi(x + 0) = \Phi(x) + \Phi(0),$$

that is

$$\Phi(x) = \Phi(x) + \Phi(0)$$

and therefore

$$\Phi(0) = 0. \qquad (5)$$

b) Further, due to the additivity of the function $\Phi$, we have

$$\Phi(x) + \Phi(-x) =$$
$$= \Phi(x + (-x)) = \Phi(0)$$

whence (by virtue of (5))

$$\Phi(-x) = -\Phi(x) \qquad (6)$$

(whatever the real value of $x$ may be!).

So, we are convinced that *any additive function is an odd function*.

Now we can already prove that formula (4) is suitable for calculating the values ​​of the additive function and for *negative* rational values ​​of the argument.

Let $\beta$ be some negative rational number; then, by virtue of (6),

$$\Phi(\beta) = -\Phi(-\beta). \qquad (7)$$

Here $(-\beta)$ is already a positive rational number, so we can use formula (4)

$$\Phi(-\beta) = (-\beta)\,\Phi(1).$$

Substituting the last relation into (7), we obtain

$$\Phi(\beta) = \beta\Phi(1),$$

which is what we wanted to prove.

### 3. Functions not limited from above

“This is the answer to the question posed at the end of the first paragraph of this

⟦column⟧

article, the reader will say: there are no additive functions other than homogeneous linear ones!”

No, that's not true!

After all, we proved formula (4) only for rational values ​​of $x$. We have no reason to use it to calculate the values ​​of our additive function $\Phi$ for $x$, say, equal to $\sqrt{2}$.

It is not surprising, therefore, that mathematicians persistently continued to search for an additive function that would differ from a linear homogeneous one.

It's really hard to find such a feature! After all, we have already seen that its values ​​(if it exists!) must coincide with the values ​​of some linear homogeneous function $x \to xa$, roughly speaking, “almost” for all $x$: although rational numbers do not exhaust the set of all real numbers, they are practically sufficient for the approximate solution of problems with any degree of accuracy.

An example of such a function was constructed in 1905 by the German mathematician Hamel \*).

But in this article, unfortunately, we will not be able to introduce the reader to this example - even if we deviate from a strictly mathematical presentation. Hamel's reasoning is so original that it is possible to fully understand it only with mathematical skills and culture acquired as a result of long-term study of mathematics. Therefore, we note here only one important property of the function constructed by Hamel: *among the values ​​it takes on an arbitrarily chosen one*

---

\*) Hamel’s article was published in the journal Matematiche Annalen in volume 60, p. 454-462, 1905

We do not know of any presentation of this result of Hamel in Russian.

*interval* $(p,\ q)$ (*that is, at* $p \leqslant x \leqslant q$), *there is one that is greater than any arbitrary positive number.*

Such a function is said to be *unbounded from above* on the interval $(p,\ q)$.

An example of a function that is not bounded above, for example, on the interval $(-1,\ 1)$, is the function $H$, defined by the formula $H(x) = \dfrac{1}{x}$ for values ​​of the argument that are not equal to zero, and taking the value zero for $x = 0$ (Fig. 1). Another example would be the function defined by the formula

$$P(x) = \frac{1}{(x-p)(x-q)}$$

for $x \neq p$ and $x \neq q$, and taking the value zero for $x = p$ and $x = q$.

This function is not upper bounded on any interval containing either the point $p$ or the point $q$ (see, for example, figure 2).

However, in both of these examples there is an interval in which these functions are still bounded from above (a function is called bounded from above on a given interval if the values ​​it takes on this interval remain less than some predetermined number). But the Hamel function, as we have already said, is not bounded from above on any (however

⟦column⟧

but in a small!) interval. This makes Hamel’s discovery even more interesting: he not only constructed an example of an additive function that is not linear, but also introduced functions into mathematics that have a “strange” (for visual perception) property: they are not bounded above in any interval.

Let us now abandon the consideration of such “*strange*” functions and look for an *additive function*, *bounded from above at least in some one interval*.

**4. Additive function bounded from above on at least one interval**

1. Let the additive function $\Phi$ be bounded from above on the interval $(p,\ p+s)$, where $s$ is some positive number. It is easy to see that then $\Phi$ is bounded above also on the interval $(0,\ s)$.

Indeed, let $x$ be any positive number not greater than $s$, then the number $p + x$ lies in the interval $(p,\ p+s)$ and, therefore, $\Phi(p+x)$ is less than some given number $M$; due to additivity $\Phi$,

$$\Phi(p) + \Phi(x) < M$$

and therefore

$$\Phi(x) < M - \Phi(p)$$

for any value $x$ lying in the interval $(0,\ s)$.

⟦figure⟧
Fig. 1.

⟦figure⟧
Fig. 2.

3 Quantum No. 1

⟦folio 33⟧

⟦folio 34⟧

2. Let us now consider a new function $G$, the value of which for an arbitrary value $x$ of the argument will be calculated using the formula

$$G\,(x) = \Phi\,(x) - \frac{\Phi\,(s)}{s}\,x. \qquad (8)$$

The function $G\,(x)$ is also bounded from above on the interval $(0,\ s)$: its value on this interval is less than $M' = M - \Phi(p) + |\,\Phi\,(s)\,|$.

3. It is obvious (see (8)) that the function $G$ is additive and that $G\,(s) = 0$. That's why

$$G\,(x + s) = G\,(x) + G(s) = G\,(x)$$

and therefore the number $s$ *period* of the function $G$!

Thus, the value that the function $G$ takes for some value of the argument $x$ is equal to the value it takes for some value of the argument from the interval $(0,\ s)$, and therefore it is less than $M'$, that is, $G(x) < M'$ for any value $x$.

4. Now we can already prove the statement - perhaps unexpected for the reader:

*Any value of the function $G$ is equal to zero.*

We will do this “by contradiction.” Let for any positive value $x_0$ of the argument $x$, less than $s$, the corresponding value $G(x_0)$ is different from zero, $G(x_0) \neq 0$.

Then, due to the additivity of the function $G$, we have (see formula (4))

$$G\,(\alpha x_0) = \alpha\,G(x_0).$$

Choosing $\alpha$ so that

$$\alpha G\,(x_0) > M',$$

we will get

$$G\,(\alpha x_0) > M'.$$

And this contradicts the fact that $G(x) < M'$ for all $x$. Therefore, our assumption was incorrect, and $G\,(x_0) = 0$ for any value of $x_0$ lying in the interval $(0,\ s)$. Taking into account that the function $G\,(x)$ has a period $s$, we come to the conclusion that

$$G\,(x) = 0 \qquad (9)$$

for any value of $x$.

⟦column⟧

5. Returning now to definition (8) of the function $G$, we obtain, by virtue of (9), that

$$\Phi\,(x) = ax \quad \left(\text{где } a = \frac{\Phi\,(s)}{s}\right).$$

The reader probably anticipated this result. Here is its verbal formulation: *if an additive function is bounded from above on at least one (even arbitrarily small) interval, then it is a linear homogeneous function!*

**5. Functional equations**

This result can also be formulated as follows:

The task is to *find a function $\Phi$ defined for any real value of the argument and having the property that for any values ​​$x$ and $y$ of the argument the equality holds*

$$\Phi(x + y) = \Phi(x) + \Phi(y) \qquad (10)$$

has many solutions. And even if we look only for those solutions $\Phi$ of this *equation* that are bounded from above - at least on some one interval - then there will still be many solutions. But any such solution is a linear homogeneous function, that is, a function of the form

$$x \to ax$$

($a$ is some real number).

It should be said that this task is usually formulated as follows:

*Find the function $\Phi$ that satisfies the functional equation (10).*

Problems that require finding a function that has some specified property are rarely encountered in school, but are often considered in mathematics and play an important role in it. Here is another such task:

*Find a function $G$ that has the property that for any values ​​$x$ and $y$ of the argument (belonging, of course, to the domain of definition of the sought-for function $G$ holds*

⟦folio 35⟧

*equality*
$$G(x + y) = G(x) + G(y) + p, \qquad (11)$$
*in which* $p$ - *a given number.*

The reader can easily check; what is the function
$$x \to ax - p$$
is her solution. It's tempting to find out if there are any other solutions?

Another interesting task is to solve the functional equation
$$H(x + 2y) + H(x) = 2H(x + y). \qquad (12)$$
It is easy to verify that the function
$$x \to ax + b$$
($a$ and $b$ are arbitrary numbers) is a solution to equation (12). Are there other solutions?

Outstanding mathematicians of the past - and among them such as Euler, Gauss, Cauchy, Abel, Lobachevsky, Weierstrass, Darbou, Gilbert - often turned to functional equations and used them to solve many important problems. The systematic study of functional equations was started by Koshy - in 1821 he published his Course of Analysis \*) (he taught this course at the Paris Polytechnic Institute). In it, he studied in detail (but still not fully enough) the functional equation (10) considered in our article—it is now called the “functional Cauchy equation”; this equation is especially often used in various mathematical theories. Along with it, Cauchy also considers the following functional equations:
$$\Phi(x + y) = \Phi(x)\Phi(y),$$
$$G(xy) = G(x)G(y),$$
$$H(xy) = H(x) + H(y).$$

The reader will undoubtedly be able to find “particular” solutions to these equations. It is much more difficult to find all the solutions for each of them. We hope to talk about this in another article.

---
\*) A. C a u c h y, Cours d'analyse de l'Ecole polytechnique 1. Analyse algebreque, V (Paris, 1821).

3\*

⟦column⟧

## Where does logic begin?

*(End. See p. 24 for the beginning)*

4) The *implication* of the propositions $A$ and $B$ (symbolically $A \supset B$, read as “$A$ implies $B$”, or “From $A$ follows $B$”, or “If $A$ then $B$”) is false if *premise* $A$ is true and *conclusion* $B$ is false, and true in all other cases:

| $A$ | $B$ | $A \supset B$ |
|---|---|---|
| And | And | And |
| And | l | l |
| l | And | And |
| l | l | And |

5) An *equivalence* of the statements $A$ and $B$ ($A \sim B$ reads “$A$ is equivalent to $B$”) is true if $A$ and $B$ have the same truth values, and false if the truth values ​​of $A$ and $B$ are different:

| $A$ | $B$ | $A \sim B$ |
|---|---|---|
| And | And | And |
| And | l | l |
| l | And | l |
| l | l | And |

Of course, these definitions themselves are quite simple and easy to remember. But they raise a number of questions, without answers to which further discussion of the topic would be completely pointless. For example, why did we define and name these operations this way and not otherwise? In other words, what is the connection between all these tables and the “ordinary” meaning of such well-known words as “not”, “and”, “or”, “should”? What are the reasons for considering these operations to be “essential”? What other (non-basic) logical operations are there and can be? And what, strictly speaking, is “logical” in them? For now, we’ll limit ourselves to advice: think about all these questions yourself.
