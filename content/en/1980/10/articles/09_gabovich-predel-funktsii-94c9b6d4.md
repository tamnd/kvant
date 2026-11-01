---
id: 1980-10-gabovich-predel-funktsii-94c9b6d4
issue: kvant_1980_10
year: 1980
number: "10"
title: Function limit
authors:
  - Габович И. Г.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40-42
tag: J474
lang: en
source: kvant_digital
extraction: vision
content_sha256: c879eefcb3375c3bd06fb0a88cfa319867139c0030d6383553cf45d1edcdc1d3
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/09_gabovich-predel-funktsii-94c9b6d4.md
source_content_sha256: f3800ae08a98529689b21112f34ea6fc744ef252449c9beaae6a865811267511
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

I. Gabovich

Function limit

The concept of “limit of a function” is one of the most important in the school mathematics course. Through it, “continuity” and “derivative” are defined.

We formulate the main definition (§ 38 of the manual “Algebra and Principles of Analysis 9”) in two ways.

First in “arithmetic” language: the number $b$ is called the limit of the function $f$ with $x$ tending to $a$ if for any $\varepsilon > 0$ there is a $\delta > 0$ such that for all $x$ satisfying the double inequality*)

$$0 < |x - a| < \delta,$$

inequality holds

$$|f(x) - b| < \varepsilon.$$

To formulate a definition of the limit of a function in “geometric” language, we introduce a term that is not in the school textbook. As is known, a neighborhood of the point $a \in R$ is called an interval of the form $]a - \delta; a + \delta[$, where $\delta$ is an arbitrary positive number. Let us take the punctured neighborhood of the point $a \in R$ as its neighborhood, from which the point $a$ itself is thrown out (“punctured”), that is, a “broken” set of the form $]a - \delta; a[U]a; a + \delta[$. Now the definition of the limit of a function can be formed as follows: the number $b$ is called the limit of the function $f$ with $x$ tending to $a$ if for any

$$*) |x - a| > 0 \iff x \neq a.$$

neighborhood $B$ of point $b$ there is a punctured neighborhood $A$ of point $a$ such that $f(A) \subset B$ (Fig. 1).

Thus, it is not required that inequality (2) also hold for $x = a$. The function $f$ at point $a$ may not even be defined - this does not in any way affect its limit as $x$ tends to $a$. For example, the function $\frac{x^2 - 9}{x - 3}$ is not defined at $x = +3$, but its limit at $x \rightarrow +3$ exists.

A more general example: the function $\frac{\Delta f(x_0)}{\Delta x}$ is always undefined at $\Delta x = 0$, but its limit at $\Delta x \rightarrow 0$ “often” exists (it is called the arbitrary function $f$ at the point $x_0$).

However, “very often” inequality (2) is also satisfied for $x = a$; if at the same time $b = f(a)$, the function $f$ is called continuous at the point $a$.

If a statement of the form

$$\lim_{x \rightarrow 1} f(x) = b$$

proves the outcome indefinitely from the definition, it is necessary for any $\varepsilon > 0$ to find the corresponding $\delta > 0$ or, at least, to prove that such a $\delta > 0$ exists.

Example 1. Let us prove that

$$\lim_{x \rightarrow \frac{1}{7}} (3 - 2x) = \frac{19}{7}.$$

For these “actors” $(f(x) = 3 - 2x, a = \frac{1}{7}, b = \frac{19}{7})$ inequality (2) takes the form

$$|3 - 2x - \frac{19}{7}| < \varepsilon.$$

To find the required $\delta$, let’s “reveal” inequality (4) and construct

⟦folio 41⟧

xia “to bare” $x$. Inequality (4) is equivalent to inequality

$$\left| -2x + \frac{2}{7} \right| < \varepsilon,$$
$$-\varepsilon < -2x + \frac{2}{7} < \varepsilon,$$
$$-\frac{2}{7} - \varepsilon < -2x < -\frac{2}{7} + \varepsilon,$$
$$\frac{1}{7} + \frac{\varepsilon}{2} > x > \frac{1}{7} - \frac{\varepsilon}{2},$$
$$\frac{1}{7} - \frac{\varepsilon}{2} < x < \frac{1}{7} + \frac{\varepsilon}{2}.$$

Now we “collapse” inequality (5) and get an inequality of the form (1):

$$-\frac{\varepsilon}{2} < x - \frac{1}{7} < \frac{\varepsilon}{2},$$
$$|x - \frac{1}{7}| < \frac{\varepsilon}{2}.$$

We're aiming enough. Thus, for $\delta = \frac{\varepsilon}{2}$, (4) follows from $0 < |x - \frac{1}{7}| < \delta$. In this example, inequality (2) = (4) is also true for $x = a$; as $\delta$ one can obviously take any number from $] 0; \frac{\varepsilon}{2}]$.

However, the second remark is correct and of a general nature: if for some $\varepsilon_0 > 0$ some $\delta_0 > 0$ is suitable, that is, from $0 < |x - a| < \delta_0$ (6)

flows out

$$|f(x) - b| < \varepsilon_0,$$

then, of course, any $\delta \in ]0; \delta_0[$ is also suitable for this $\varepsilon_0 > 0$: if $0 < |x - a| < \delta$, then from $\delta < \delta_0$ follows (6), and hence (7).

Example 2. Let us prove that $\lim_{x \to -2} \frac{5}{x} = -\frac{5}{2}$.

Inequality (2) in this case has the form

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon.$$

Let's go down the same path again. Inequality (8) is equivalent to inequality

$$\left| \frac{5}{x} + \frac{5}{2} \right| < \varepsilon,$$
$$-\varepsilon < \frac{5}{x} + \frac{5}{2} < \varepsilon,$$
$$-\frac{5}{2} - \varepsilon < \frac{5}{x} < -\frac{5}{2} + \varepsilon.$$

To achieve the goal of “exposing” $x$, we need to divide 1 term by term into each part of the double inequality (9); but this can only be done if all parts of the inequality have the same sign, since the corresponding property of word inequalities says: if $a < b$ and the numbers $a, b$ have the same sign (in short: $ab > 0$), then $\frac{1}{a} > \frac{1}{b}$ (prove this statement!). $-\frac{5}{2} - \varepsilon < 0$. Therefore, we need the remaining two parts of inequality (9) to be negative. It is enough to require $-\frac{5}{2} + \varepsilon < 0$ or $\varepsilon < \frac{5}{2}$.

So, let's start with $\varepsilon < \frac{5}{2}$ (note this place - we'll come back to this in a bit). Then all parts of inequality (9) are negative. That's why

$$\frac{1}{-\frac{5}{2} - \varepsilon} > \frac{x}{5} > \frac{1}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} - \varepsilon} > x > \frac{5}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} + \varepsilon} < x < \frac{5}{-\frac{5}{2} - \varepsilon},$$
$$\frac{10}{-5 + 2\varepsilon} < x < \frac{10}{-5 - 2\varepsilon}.$$

$x$ “exposed.” Now we need to obtain from (10) an inequality of the form (1):

$$|x - (-2)| < \delta,$$
$$-\delta < x - (-2) < \delta,$$
$$-2 - \delta < x < -2 + \delta.$$

From (10):

$$-2 + \frac{10}{-5 + 2\varepsilon} + 2 < x < -2 +$$
$$+ \frac{10}{-5 - 2\varepsilon} + 2,$$
$$-2 - \frac{4\varepsilon}{5 - 2\varepsilon} < x < -2 + \frac{4\varepsilon}{5 + 2\varepsilon}.$$

So far, inequality (12) does not quite have the form (11). At $\varepsilon < \frac{5}{2}$

$$\frac{4\varepsilon}{5 - 2\varepsilon} > \frac{4\varepsilon}{5 + 2\varepsilon}.$$

⟦folio 42⟧

Means,

$$-2 - \frac{4\varepsilon}{5-2\varepsilon} < -2 - \frac{4\varepsilon}{5+2\varepsilon}. \tag{13}$$

Let's roughen up inequality (12):

$$-2 - \frac{4\varepsilon}{5+2\varepsilon} < x < -2 + \frac{4\varepsilon}{5+2\varepsilon}. \tag{14}$$

It follows from (13) that if $x$ satisfies inequality (14), then it also satisfies inequality (12) (see Fig. 2). But (14) already has the form (11). IZ (14)

$$|x - (-2)| < \frac{4\varepsilon}{5+2\varepsilon}.$$

Thus, if $\varepsilon < \frac{5}{2}$, then for $\delta = \frac{4\varepsilon}{5+2\varepsilon}$ (8) follows from $0 < |x - (-2)| < \delta$.

But we need to prove that for any $\varepsilon > 0$ there is such a $\delta > 0$, and we have shown this only for $\varepsilon < \frac{5}{2}$. However, in essence, this is enough, because for $\varepsilon \geq \frac{5}{2}$ the same $\delta$ will do!

Indeed, let $\varepsilon_1 \geq \frac{5}{2}$; arbitrary $\varepsilon_2 < \frac{5}{2}$ and $\delta_2 = \frac{4\varepsilon_2}{5+2\varepsilon_2}$ are possible; according to proven from

$$0 < |x - (-2)| < \delta_2$$

flows out $$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_2;$$

but $\varepsilon_2 < \frac{5}{2} \leq \varepsilon_1$; Means,

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_1.$$

This remark is of a general nature: it turns out that we can always look for $\delta$ not for all $\varepsilon > 0$, but for all positive $\varepsilon$ less than any positive number we choose.

Of course, in this example, inequality (2) = (8) is true for $x = a$.

Example 3. Let's prove that

$$\lim_{x \to 0} \left( x \cdot \sin \frac{1}{x} \right) = 0.$$

Fig. 2.

Inequality (2) in this case has the form

$$|x \cdot \sin \frac{1}{x} - 0| < \varepsilon,$$

$$|x \cdot \sin \frac{1}{x}| < \varepsilon. \tag{15}$$

If in this example we immediately followed the same path as in the previous ones, we would not have reached the goal: $x$ we would not have been able to “expose”. Therefore, let’s start by “coarsening” inequality (15): since $$\left| \sin \frac{1}{x} \right| \leq 1,$$

$$|x \sin \frac{1}{x}| \leq |x|. \tag{16}$$

It follows from (16) that together with (15) it is sufficient to search for $\delta$ for the inequality $$|x| < \varepsilon.$$ Since in our case inequality (1) has the form $0 < |x| < \delta$, it is clear that we can take $\varepsilon$ as the sought $\delta$.

In this example, inequality (2) = (15) for $x = a = 0$ is, of course, not true: the function $x \sin \frac{1}{x}$ for $x = 0$ is not defined.

Remember the example of “coarsening” we used twice - it is often useful.

In the examples we considered, finding $\delta$ did not cause large functions; proving statement (3) directly by directly finding $\delta$ is certainly not possible. In such cases, theory can help.

Let us give an example from “non-school” theory. The theorem is also true: if $$\lim_{x \to a} f(x) = 0, \lim_{x \to a} g(x) = 0$$ exists and $$\lim_{x \to a} \frac{f'(x)}{g'(x)},$$ exists then $u$ $$\lim_{x \to a} \frac{f(x)}{g(x)} u$$ exists

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}.$$

This theorem is called *Lopitania's rule*. According to this rule:

$$\lim_{x \to 0} \frac{e^x - e^{-x}}{\ln(e - x) + x - 1} =$$

$$= \lim_{x \to 0} \frac{e^x + e^{-x}}{-1 - \frac{1}{e} + 1} = \frac{2}{1 - \frac{1}{e}} = \frac{2e}{e - 1}.$$
