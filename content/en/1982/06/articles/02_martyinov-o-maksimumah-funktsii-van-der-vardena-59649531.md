---
id: 1982-6-martyinov-o-maksimumah-funktsii-van-der-vardena-59649531
issue: kvant_1982_6
year: 1982
number: "6"
title: On the maxima of the van der Waerden function
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 9, 10, 12, 13
tag: O53W
lang: en
source: kvant_digital
extraction: vision
content_sha256: ee42172ddd2d949aaf086c9be15532bc99ada0ceaa07a0d09aad56ac4a0e8b76
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/02_martyinov-o-maksimumah-funktsii-van-der-vardena-59649531.md
source_content_sha256: 369c2e8a600d3647673a773c087b382f6f316efa3f33bf568d56fa32b3a78114
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

B. Martynov

On the maxima of van der Waerden functions

The function we are familiar with

Schoolchildren in the ninth and tenth grades know that a function that is differentiable at some point is continuous at that point (“Algebra and principles of analysis 9-10,” paragraph 19). They also know that the converse is not true: for example, the function $y = |x|$ is continuous at $x = 0$ (and at any other point), but is not arbitrary at $x = 0$. In general, any function whose graph has a “corner” at some point is not differentiable at that point. It is clear that it is easy to construct a function that on the interval, say, [0; 1] has an infinite number of “angles” (figure 1 shows a piece of the graph of such a function; it is, of course, impossible to draw it completely).

However, all such functions, as well as other continuous functions known to you, are still differentiable at “most” points.

For a long time after the invention of differential calculus, mathematicians thought that continuous functions were, as a rule, differentiable. Therefore, when, in the sixties, centuries passed, the German mathematician Karl Weierstrass published an example of a function that is continuous at every point on a line and not arbitrary at any point *), a Strassian evening will arise in the mathematical world.

*) The first example of this kind was built forty years before Weierstrass by the Czech mathematician and philosopher Bernhard Bolzano, but his example became known later than Vecherstrass’s.

Fig. 1.

⟦folio 9⟧

What if all the functions $\varphi_n$ are added? There is reason to hope that the “sum” will, in any case, be continuous at each point and not differentiable at points of the form $x = \frac{k}{2^n} (k \in \mathbb{Z}, n \in \mathbb{N})$. Unfortunately, we do not know what the sum of an infinite number of terms is.

Therefore, we will do this: we form a sequence of the function $\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x)$ (thus, $\Phi_{n+1}(x) = \Phi_n(x) + \varphi_{n+1}(x)$; see Fig. 3-5) and prove that for any $x$ there exists $\lim_{n \to \infty} \Phi_n(x)$.

To prove it, we need Weierstrass's theorem, which states that a monotonic bounded sequence has a limit (Algebra and Analysis 9, paragraph 32).

From $\varphi_{n+1}(x) \geq 0$ it follows $\Phi_{n+1}(x) \geq \Phi_n(x)$—the sequence ($\Phi_n(x)$) is monotonic. Since $\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x) \leq \frac{1}{2} + \frac{1}{4} + \dots + \frac{1}{2^{n+1}} = 1 - \frac{1}{2^{n+1}} < 1$, the sequence ($\Phi_n(x)$) is bounded. Therefore, $\lim_{n \to \infty} \Phi_n(x)$ exists. Let us denote this limit by $\Phi(x)$. Thus, the function $\Phi$ is defined on the entire number line. It is periodic (with period 1), $0 \leq \Phi(x) \leq 1$ for all $x \in \mathbb{R}$, the graph of the function $\Phi$ is symmetrical with respect to any straight line $x = \frac{k}{2} (k \in \mathbb{Z})$ - all this easily follows from the properties of the function $\varphi_0$ and the properties of the limit. Therefore, the graph of function $\Phi$ is impossible: in Figures 3-5 you can see how the points “heat up” at which the graph of function $\Phi_n$ has a “corner”, that is, points where these functions do not have an arbitrary function.

The continuity of the constructed function $\Phi_n$ is continuous at each point of the line.

Intuitively, this is quite clear: if $\Phi$ had a discontinuity at some point $x_0$, then for a sufficiently large

⟦folio 10⟧

$n \in \mathbb{N}$ would have approximately the same discontinuity at point $x_0$ at $\Phi_n$, and $\Phi_n$ is continuous along the entire line. The evidence below clarifies these reports.

Let us first study the difference $r_n(x) = \Phi(x) - \Phi_n(x)$ (here $x$ is fixed, $n$ is variable).

$$\Phi_{n+m}(x) - \Phi_n(x) = \varphi_{n+1}(x) + \varphi_{n+2}(x) + \dots + \varphi_{n+m}(x).$$

It's clear that

$$0 \leqslant \Phi_{n+m}(x) - \Phi_n(x) \leqslant \frac{1}{2^{n+2}} + \frac{1}{2^{n+3}} + \dots +$$

$$+ \frac{1}{2^{n+m+1}} = \frac{1}{2^{n+2}} \cdot \frac{1 - \frac{1}{2^m}}{1 - \frac{1}{2}} < \frac{1}{2^{n+1}}.$$

Since $\lim_{m \to \infty} \Phi_{n+m}(x) = \Phi(x)$ and $\lim_{m \to \infty} \Phi_n(x) = \Phi_n(x)$,

$$0 \leqslant r_n(x) \leqslant \frac{1}{2^{n+1}}.$$

Now we can move on to proving the continuity of the functions $\Phi$ at an arbitrary point $x_0 \in \mathbb{R}$. Let's take $\varepsilon > 0$ and consider the difference model

$$|\Phi(x_0 + h) - \Phi(x_0)| = |\Phi_n(x_0 + h) + r_n(x_0 + h) - \Phi_n(x_0) - r_n(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + |r_n(x_0 + h)| + |r_n(x_0)|.$$

But $|r_n(x_0)| \leqslant \frac{1}{2^{n+1}}$ and $|r_n(x_0 + h)| \leqslant \frac{1}{2^{n+1}}$; That's why

$$|\Phi(x_0 + h) - \Phi(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + \frac{1}{2^n}.$$

When $n$ is large enough

$$\frac{1}{2^n} < \frac{\varepsilon}{2}.$$

The function $\Phi_n$, as the sum of a finite number of continuous functions, is continuous at the point $x_0$. Therefore, by choosing $\delta > 0$ it is possible to achieve that for $|h| < \delta$

$$|\Phi_n(x_0 + h) - \Phi_n(x_0)| < \frac{\varepsilon}{2}.$$

When $\delta$ is selected

$$|\Phi(x_0 + h) - \Phi(x_0)| < \varepsilon,$$

and this proves the continuity of the functions $\Phi$ at the point $x_0$.

Non-differentiability of the constructed function

The function $\Phi$ is not differentiable at any point on the line.

At first glance, this may seem very surprising: as $n$ grows, the set of points of non-differentiability of functions $\Phi_n$ becomes denser and deeper, so it is natural to expect that “in the limit”, that is, for functions $\Phi$, it will fill the entire straight line. However, this naive reasoning is incorrect, as the example function shows

$$G(x) = \lim_{n \to \infty} G_n(x),$$

where the functions $G_1, G_2, G_3$ are shown on figure 6. Obviously, $G(x) = 1 - x^2$ is a function that is differentiable at any point.

Proving by contradiction, let us assume that for some $x_0 \in \mathbb{R}$ there is $\Phi'(x_0)$.

“Lock” $x_0$ in a sequence of double approximations by flaw and by image:

$$\frac{s_k}{2^{k+1}} \leqslant x_0 < \frac{s_k + 1}{2^{k+1}} \quad (k = 0, 1, 2, \dots; \ s_k \in \mathbb{Z}).$$

Let's put $\alpha_k = \frac{s_k}{2^{k+1}}, \beta_k = \frac{s_k + 1}{2^{k+1}}$. Then

$$\alpha_k \leqslant x_0 < \beta_k \quad (k = 0, 1, 2, \dots)$$

And

$$\lim_{k \to \infty} \alpha_k = \lim_{k \to \infty} \beta_k = x_0.$$

From (1)

$$0 < \frac{\beta_k - x_0}{\beta_k - \alpha_k} \leqslant 1$$

$$0 \leqslant \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \leqslant 1.$$

From here, from (2) and from the easily verifiable identity

$$\frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} - \Phi'(x_0) =$$

$$= \frac{\beta_k - x_0}{\beta_k - \alpha_k} \left[ \frac{\Phi(\beta_k) - \Phi(x_0)}{\beta_k - x_0} - \Phi'(x_0) \right] +$$

$$+ \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \left[ \frac{\Phi(x_0) - \Phi(\alpha_k)}{\beta_k - x_0} - \Phi'(x_0) \right]$$

should

$$\lim_{k \to \infty} \frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} = \Phi'(x_0).$$

⟦folio 12⟧

$$\Phi(2\bar{x}) = 2\Phi(\bar{x}) - 2\varphi_0(\bar{x}) = 2\Phi(\bar{x}) - 2\bar{x} = 2M - 2\bar{x} \leqslant M$$
$$\bar{x} \geqslant \frac{M}{2} \geqslant \frac{1}{3}.$$

From the symmetry of the graph of the function Ф relative to the straight line $x = \frac{1}{2}$ it follows that there are no maximum points on the interval $] \frac{2}{3}; 1]$.

Let us now prove that $M = \frac{2}{3}$. We apply equality (3) again:

$$\Phi(4x) = 2\Phi(2x) - 2\varphi_0(2x) = 2[2\Phi(x) - 2\varphi_0(x)] - 2\varphi_0(2x) = 4\Phi(x) - 4\varphi_0(x) - 2\varphi_0(2x)$$
$$\Phi(x) = \varphi_0(x) + \frac{1}{2}\varphi_0(2x) + \frac{1}{4}\Phi(4x) = \Phi_1(x) + \frac{1}{4}\Phi(4x).$$

The function $\Phi_1$ on the segment $[\frac{1}{4}; \frac{3}{4}]$ is constructed and equal to $\frac{1}{2}$ (Fig. 3), therefore on this segment

$$\Phi(x) = \frac{1}{2} + \frac{1}{4}\Phi(4x).$$

Since $\bar{x} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$, equality (4) can be applied to $\bar{x}$:

$$M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) \leqslant \frac{1}{2} + \frac{1}{4}M$$
$$M \leqslant \frac{2}{3}.$$

Let us remember that $M \geqslant \Phi(\frac{1}{3}) = \frac{2}{3}$, and finally find $M = \frac{2}{3}$. Also, $\Phi(\frac{1}{3}) = \Phi(\frac{2}{3}) = \frac{2}{3}$.

To further prove that if $\bar{x} - \text{точка максимума},$ then $4\bar{x} - \text{точка максимума};$ if $4\bar{x} - \text{точка максимума}$ and $\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$ then $\bar{x} - \text{точка максимума}$. To prove it, note that equality (4) is true for all $x$ for which $\{x\} \in [\frac{1}{4}; \frac{3}{4}]$ (check!). Let $\bar{x} - \text{точка максимума}$. Then $\{\bar{x}\} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$.

$$\frac{2}{3} = M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x})$$
$$\Phi(4\bar{x}) = \frac{2}{3} = M.$$

Let now $4\bar{x} - \text{точка максимума}$ and $\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$. Then $\Phi(4\bar{x}) = M = \frac{2}{3}$ and $\Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) = \frac{2}{3} = M.$

Many maximum points

Let us find out the structure of the set $E$.

Probably, if Hermite had known how complex it is, he would have responded to Van der Waerden’s functions with even greater disgust. On the other hand, who knows - perhaps the beautiful and subtle structure of this set would have attracted Hermite to the study of non-differentiable functions.

We know two points of the set $E$:

$$\frac{1}{3} \text{ и } \frac{2}{3};$$ we also know that $E \subset [\frac{1}{3}; \frac{2}{3}]$.

Further, the set $E$ is closed. This means the following: if there is a convergent sequence of points in the set $E$, then the limit of this sequence also belongs to $E$. Let's prove it. Let $x_n \in E$ ($n=1, 2, 3, \dots$), that is, $\lim_{n \to \infty} x_n = \bar{x}$; then from the continuity of the functions $E$ at the point $\bar{x}$ it follows that $\Phi(\bar{x}) = \Phi(\lim_{n \to \infty} x_n) = \lim_{n \to \infty} \Phi(x_n) = M$, that is, $\bar{x} \in E$.

From what was proved at the end of the previous paragraph and the fact that $1$ is the period of the function $E$, it follows that if $x - \text{точка максимума} E$, then the points $\frac{1}{4} + \frac{x}{4} = \frac{x+1}{4}, \frac{2}{4} + \frac{x}{4} = \frac{x+2}{4}$ also belong to $E$. Thus, starting from the points $\frac{1}{3}, \frac{2}{3}$, one can construct many points of the set $E: \frac{1}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{2}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{1}{4} + \frac{1}{4} \cdot \frac{2}{3}$, etc.

It is easy to see that all numbers are of the form

$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{a_{n+1}}{3},$$

⟦folio 13⟧

where $a_1, a_2, \dots, a_n, a_{n+1}$ are either ones or twos, and are elements of the set $E$. Since
$$\frac{1}{3} = \frac{1}{4} + \frac{1}{4^2} + \frac{1}{4^3} + \dots,$$
such a $x$ can be represented as
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+1}}{4^{n+2}} + \dots$$
or, by analogy with decimal fractions, in the form of an infinite periodic quadruple fraction with a period of length 1:
$$x = 0, a_1 a_2 \dots a_n a_{n+1} a_{n+1} = 0, a_1 a_2 \dots a_n (a_{n+1}).$$
Since the set $E$ is closed, any number
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+2}}{4^{n+2}} + \dots$$
where $a_i$ are either ones or twos, the set $E$ belongs. Indeed, for each such $x$ one can find a sequence of $(x_n)$ elements from $E$ converging to $x$; for example if
$$x_n = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{1}{3},$$
then $\lim_{n \to \infty} x_n = x \left(0 \leqslant x - x_n \leqslant \frac{1}{4^{n+1}}\right)$.

Thus, the set $E$ contains all numbers, in the representation of which $0, a_1 a_2 a_3 \dots$ as an infinite quadruple fraction, all digits $a_i$ are either ones or twos (on figure 8 the quaternary expansions of the numbers $\frac{1}{12}, \frac{2}{12}, \dots, \frac{11}{12}$ are depicted).

Let us now prove that $E$ does not contain any other numbers. Let in the quadruple notation of the number $x \in E$ there be a digit 0 at some place after the decimal point, that is, $x = 0, a_1 a_2 \dots a_n 0 a_{n+2} \dots$; then $\{4^n x\} = 0, 0 a_{n+2} \dots \in E$.

But $0, 0 a_{n+2} a_{n+3} \dots < 0, 033 \dots = 3 \left(\frac{1}{4^2} + \frac{1}{4^3} + \dots\right) = \frac{1}{4}$ and, therefore, the point $\{4^n x\}$ does not belong to the segment $\left[\frac{1}{3}; \frac{2}{3}\right]$ containing $E$.

If the quadruple notation of the number $x \in E$ contains the digit 3, that is, $x = 0, a_1 a_2 \dots a_n 3 a_{n+2} \dots$, then
