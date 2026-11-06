---
id: 1990-4-izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28
issue: kvant_1990_4
year: 1990
number: "4"
title: Jensen's inequality
authors:
  - Ижболдин О. Т.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 59
page_last: 63
page_labels: 57, 58, 59, 61
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6cfa11fd34e5aedce2835aebf13ca2cecb6fd905260a75d57cdb6c24c9a6b728
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/15_izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28.md
source_content_sha256: 2eff30638d5aae031b3e1d22a6ed15aa28be10dcd634d546ce57c674fa9c9b0e
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 57⟧

---
running_head:
folio:
---

Inequality
Jensen
O. IZHVOLDIN, L. KURLYANDCHIK

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$
$$\prod_{k=1}^{n} a_k = a_1 \cdot a_2 \cdot \dots \cdot a_n.$$

We advise those who have not yet learned
use them, describe you-
masonry in more detail.

The art of proving inequalities
mastering is far from easy. This requires a lot of experience, intuition, and
as in every art, the ability to freely apply various “technical” techniques. We will demonstrate one such technique using a number of examples. This article will prove both classical inequalities (Cauchy, Cauchy-Bunyakovsky, Hölder and Minkowski), as well as less famous, but also very interesting.

We will write formulas, usually briefly, using the notation

The proof of the inequalities that will be discussed is based on the concept of convexity. This is a very important mathematical concept, and you have already encountered it in your school geometry course when studying polygons. However, in mathematics, the concept of convexity is not only associated with polygons. A figure is called convex if, with any two properties of points, it contains the entire segment with endpoints at these points. Figures 1, a-2 show examples of convex and non-convex figures. You-

57

⟦folio 58⟧

---
running_head:
folio:
---

convex figures have many remarkable properties, but we will be interested in only one of them. Let's form it.
Let the masses $m_1, m_2, \dots, m_n$ be concentrated at the points $A_1, A_2, \dots, A_n$ of the convex figure Ф, respectively. Then the center of mass of these points also belongs to the figure F.
It is known from physics that the center of mass is a point with coordinates
$$\left( \frac{\sum_{i=1}^{n} m_i x_i}{\sum_{i=1}^{n} m_i}; \frac{\sum_{i=1}^{n} m_i y_i}{\sum_{i=1}^{n} m_i} \right),$$
where $x_i, y_i$ are the coordinates of point $A_i$.

Urazhennya
1. Prove that the center of mass of two points lies on the segment connecting them.
2. Prove that the center of mass of the $n$ points lies on the segment connecting any of them with the center of mass of the others.

Convex figures
Let's draw a graph of the function $y = x^2$ (Fig. 2, a).

Fig. 1.
Fig. 2.

We see that the epigraph of this figure (at figure it is colored red) is a convex figure. If we consider the figure $y = \sin x$ ($x \in [0; \pi]$), then its epigraph (on figure 2, b it is colored red) is not convex. However, the subgraph of this figure is convex (on the same figure it is shaded with the same color).

These observations lead to an important definition.

If the epigraph of a figuntia is a convex figure, then they say that this figuntia is convex, and if the subgraph is convex, then they say that the figuntia is voguntai *).

Thus, the figuncia $y = x^2$ is convex, and the figuncia $y = \sin x$ ($x \in [0; \pi]$) is a vogunt.

Basic inequality
Among the averages of well-known classical inequalities, Jensen’s inequality** occupies a special place. All the classical inequalities mentioned at the beginning of the article are its consequences.

Theorem (Jensen's inequality). Let $y = f(x)$ be a figure convex on some interval, $x_1, x_2, \dots, x_n$ be arbitrary numbers from this interval, $a, \alpha_1, \alpha_2, \dots, \alpha_n$ be arbitrary positive numbers whose sum is equal to one. Then

$$f(\alpha_1 x_1 + \dots + \alpha_n x_n) \leqslant \alpha_1 f(x_1) + \dots + \alpha_n f(x_n).$$

Proof. Let us consider on the graph of the figure $y = f(x)$ the points $A_1, A_2, \dots, A_n$ with abscissas $x_1, x_2, \dots, x_n$. Let us place weights with masses $m_1, m_2, \dots, m_n$ at these points. The center of mass of these points has coordinates

$$\left( \frac{m_1 x_1 + \dots + m_n x_n}{m_1 + \dots + m_n}; \frac{m_1 f(x_1) + \dots + m_n f(x_n)}{m_1 + \dots + m_n} \right).$$

*) Some textbooks use different terminology.
**) Jensen Johann Ludwig (1859-1925) - Danish mathematician.

⟦folio 59⟧

---
running_head:
folio:
---

Since the points $A_1, A_2, \dots, A_n$ belong to the epigraph of a convex function, then their center of mass also belongs to the epigraph (since the epigraph is a convex function). And this means that the ordinata of the center of mass is not less than the ordinata of the point on the graph with the same abscissa (Fig. 3), i.e.

$$f\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right) \leqslant \frac{m_1f(x_1) + \dots + m_nf(x_n)}{m_1 + \dots + m_n}.$$ (3)

To complete the proof, all that remains is to put $m_1 = \alpha_1, \dots, m_n = \alpha_n$.

We would like to conclude this point of the article with two important remarks. First, in the process of proving Jensen's inequality (2), we proved inequality (3). In fact, these inequalities are equivalent. Putting $\alpha_i = \frac{m_i}{m_1 + \dots + m_n} (i = 1, 2, \dots, n)$ in inequality (2), we obtain inequality (3). Therefore, naturally both of these inequalities are called Jensen’s inequalities. Inequality (2) looks more compact, but for applications it is more convenient to use inequality (3). Secondly, if the function $f(x)$ is concave, then for it Jensen’s inequalities (2) and (3) are reversed. To prove this, it suffices to consider the convex function $f(x)$.

Cauchy–Bunyakovsky inequality

At first glance, Jensen's inequality does not make much of an impression: the formulation is too general. After reading this article to the end, you will see that this impression is deceptive.

Let us demonstrate the power of Jensen's inequality using a specific example. Namely, we will prove the famous Cauchy–Bunyakovsky inequality:

$$(a_1^2 + \dots + a_n^2)(b_1^2 + \dots + b_n^2) \geqslant (a_1b_1 + \dots + a_nb_n)^2,$$

where $a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$ are arbitrary positive numbers.

Proof. As we know, the function $y = x^2$ is convex. Let us write Jensen’s inequality (3) for this function

$$\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right)^2 \leqslant \frac{m_1x_1^2 + \dots + m_nx_n^2}{m_1 + \dots + m_n} (m_i > 0).$$

Therefore, $(m_1x_1^2 + \dots + m_nx_n^2) \times (m_1 + \dots + m_n) \geqslant (m_1x_1 + \dots + m_nx_n)^2$.

Putting $m_i = b_i^2$, $x_i = \frac{a_i}{b_i}$, we obtain the required inequality.

Exercise 3. Prove the Cauchy–Bunyakovsky inequality for arbitrary real numbers $a_i, b_i$.

Examples of convex functions

To successfully apply Jensen's inequality, you need a simple cri

⟦folio 61⟧

---
running_head:
folio:
---

$$\left( \frac{\sum m_i x_i}{\sum m_i} \right)^p \leqslant \frac{\sum m_i x_i^p}{\sum m_i}.$$

From here
$$\sum m_i x_i \leqslant \left( \sum m_i \right)^{\frac{p-1}{p}} \left( \sum m_i x_i^p \right)^{\frac{1}{p}}.$$

Since $\frac{1}{p} + \frac{1}{q} = 1$, then $\frac{p-1}{p} = \frac{1}{q}$, and therefore
$$\sum m_i x_i \leqslant \left( \sum m_i x_i^p \right)^{\frac{1}{p}} \left( \sum m_i \right)^{\frac{1}{q}}.$$

Now putting $m_i = b_i^q$, $x_i = a_i b_i^{1-q}$, we obtain the required inequality.

Minkowski's inequality
$$\sqrt[n]{a_1 \cdots a_n} + \sqrt[n]{b_1 \cdots b_n} \leqslant$$
$$\leqslant \sqrt[n]{(a_1 + b_1) \cdots (a_n + b_n)} (a_i, b_i > 0).$$

Proof. Dividing both sides of the inequality by $\sqrt[n]{a_1 \cdots a_n}$, we get
$$1 + \left( \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( \frac{b_n}{a_n} \right)^{\frac{1}{n}} \leqslant$$
$$\leqslant \left( 1 + \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( 1 + \frac{b_n}{a_n} \right)^{\frac{1}{n}}.$$

It is clear that the fraction $\frac{b_i}{a_i}$ makes sense to be designated somehow. But in fact, it is more convenient to introduce a notation not for the fraction $\frac{b_i}{a_i}$ itself, but for its logarithm:
$$x_i = \ln \frac{b_i}{a_i}$$. So, replacing $\frac{b_i}{a_i}$ with $e^{x_i}$, we write our inequality in the form
$$1 + e^{\sum \frac{1}{n} x_i} \leqslant \Pi \left( 1 + e^{x_i} \right)^{\frac{1}{n}}.$$

Let us take the logarithm of both sides of the resulting inequality:
$$\ln \left( 1 + e^{\sum \frac{1}{n} x_i} \right) \leqslant \sum \frac{1}{n} \ln \left( 1 + e^{x_i} \right).$$

In the last inequality we learned Jensen's inequality for the convex function $y = \ln \left( 1 + e^{x_i} \right)$ (Example 4).

Some examples of using Jensen's inequality
Problem 1. Prove the inequality
$$\Pi a_i^a \geqslant \left( \sum \frac{1}{n} a_i \right)^{\sum a_i} (a_i > 0).$$

Solution. Having calculated both sides of the inequality and divided by $n$, we get
$$\sum \frac{1}{n} a_i \ln a_i \geqslant \left( \sum \frac{1}{n} a_i \ln \sum \frac{1}{n} a_i \right).$$

And this is Jensen’s inequality for the convex function $y = x \ln x$ (example 5).

Task 2. Prove the inequality:
$$\sqrt{\left( \sum a_i \right)^2 + \left( \sum b_i \right)^2} \leqslant \sum \sqrt{a_i^2 + b_i^2} (a_i, b_i > 0).$$

Solution. Let us write Jensen’s inequality (3) for the convex function $y = \sqrt{1 + x^2}$ (example 6):
$$\sqrt{1 + \left( \frac{\sum m_i x_i}{\sum m_i} \right)^2} \leqslant \sum \frac{\sum m_i \sqrt{1 + x_i^2}}{\sum m_i}.$$

Multiplying both sides of the inequality by $\sum m_i$, we get
$$\sqrt{\left( \sum m_i \right)^2 + \left( \sum m_i x_i \right)^2} \leqslant$$
$$\leqslant \sum m_i \sqrt{1 + x_i^2} = \sum \sqrt{m_i^2 + (m_i x_i)^2}.$$

All that remains is to put $m_i = a_i$, $x_i = \frac{b_i}{a_i}$.

In conclusion, let us consider a rather difficult problem, which can also be solved using Jensen’s inequality.

Problem 3. Prove the inequality
$$\frac{p_1}{p_2 + p_3} + \frac{p_2}{p_3 + p_4} + \frac{p_3}{p_4 + p_5} +$$
$$+ \frac{p_4}{p_5 + p_1} + \frac{p_5}{p_1 + p_2} \geqslant \frac{5}{2} (p_i > 0).$$

Solution. For convenience, we introduce additional variables $p_6$ and $p_7$, equal to $p_1$ and $p_2$, respectively. Teler, this inequality can be written briefly:
$$\sum_{i=1}^{5} \frac{p_i}{p_i+1+p_i+2} \geqslant \frac{5}{2}.$$

Let us express Jensen’s inequality (3) for the convex function $y = \frac{1}{x}$ (example 1):
