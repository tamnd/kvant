---
id: 1990-6-tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e
issue: kvant_1990_6
year: 1990
number: "6"
title: Polynomials that deviate least from zero
authors:
  - Табачников С. Л.
rubric: osnovnye-stati
page_first: 25
page_last: 26
page_labels: 23-24
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9b9ef00f75c42a90d2dd0ca1e5f620d4fafa5db0c3ef66ec4c4c47b6efd99a1c
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/04_tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e.md
source_content_sha256: 66530a17b2f0abecdbe2c5cfca401e9fd2fa866d9b9895e016852f4565773ced
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 23⟧

---
running_head:
folio:
---

POLYNOMILES, LEAST
EVADERING FROM ZERO

Candidate of Physical and Mathematical Sciences
S. TAVACHNIKOV

I will talk about one of the most beautiful problems about polynomials - the Chebyshev problem about polynomials that deviate least from zero. Let us fix some segment of the number line, say, the segment [−2; 2] (when I say “let’s say,” I’m lying a little - it is for this segment that the simplest formulas are obtained). Let

$$f(x) = x^n + a_1 x^{n-1} + a_2 x^{n-2} + \dots + a_n$$

is a reduced polynomial of $n$th degree (this means that its leading coefficient is 1). The set of values ​​$f(x)$ on the interval [−2; 2] — segment [m; M], where $m$ is the minimum and $M$ is the maximum of the polynomial. The deviation of a polynomial from zero is called the most calculated |m|, |M|. If the deviation of a polynomial from zero is $c$, then its graph is contained in the field |y| ≤ $c$ and is not contained in any narrower band with the middle line Ox.

The task is to find such a reduced polynomial of the $n$th degree $f_n(x)$, the deviation of which from zero would be minimal (the condition that the leading coefficient is equal to 1 does not allow us to make an arbitrary graph close to the abscissa). At first glance, Chebyshev's problem is of little interest to enthusiasts: in order to look for deviations from zero, you need to calculate arbitrary equations and solve equations of the $n$th degree... It is all the more surprising that this problem is solved geometrically - and almost without calculations!

Let us first, without the wisdom of bows, examine the case of small degrees. At $n=1$ the furnace is simply a linear function of $f(x)=x+a$. Its set of values ​​is the segment [−2+a; 2+a] of length 4. Therefore, the smallest deviation from zero is 2, and $f_1(x)=x$.

For Nenatny, the case $n=2$ (the case of a quadratic trinomial) is more difficult. The graph of a polynomial of the second degree is a segment of a parabola; and it is quite indo that the parabola is most advantageously positioned as shown in figure 1. In this case, $f(x)=x^2-2$, and the deviation from zero again turns out to be equal to 2.

Exercise 1. Check the intuition of calculation: prove that the deviation from zero of a square trinomial is not less than 2.

I could suggest that you examine the case of polynomials of the third degree and make sure that in this case the deviation from zero is equal to 2. This problem still allows for a straightforward solution. But I can't wait to tell you the general solution.

Let us assume that we have managed to discover a reduced polynomial of the $n$th degree $f_n(x)$ such that its graph lies in the strip |y| ≤ $c$ and contains $n+1$ the point of its boundaries: the rightmost one lies on the line $y=c$, the next one on the line $y=-c$, the next one again on the line $y=c$, etc. ($n=5$ on figure 2).

Theorem. The deviation from zero of any reduced polynomial of degree $n$ other than $f_n(x)$ is greater than $c$.

Here is a geometric proof that makes Chebyshev's problem columnar. Let $g(x)$ —

⟦folio 24⟧

---
running_head:
folio:
---

another reduced polynomial of degree $n$, whose deviation from zero does not exceed $c$. Then its graph also lies in the band $|y| \leq c$. Divide this strip of vertical segments into $n$ rectangles as shown in figure 3. The blue curve - graph $f_n(x)$ - diagonally connects the opposite vertices of each rectangle. Therefore, the red curve - graph $g(x)$ - intersects the blue one inside each of them. Therefore, the equation $f_n(x) - g(x) = 0$ has at least $n$ roots. But the degree of the polynomial $f_n(x) - g(x)$ is not greater than $(n-1)$. If such a polynomial still has $n$ roots, then it is also naturally equal to zero, i.e. $g(x) = f_n(x)$. The theorem has been proven.

Consider this proof. Almost for nothing we got quite a lot: although we don’t yet know the value of $c$, we already know that there is only one polynomial of a given degree that least deviates from zero, and we can imagine what its graph looks like.

Exercise 2. The above proof contains a gap (this is the price for beauty). What if the graphs of the polynomials $f_n(x)$ and $g(x)$ touch (Fig. 4)?

Hint: remember the definition of a multiple root of a polynomial.

So, we need to present a polynomial $f_n(x)$ whose graph behaves as shown in figure 2. This figure can't help but remind you of trigonometric functions. And indeed, now they are coming into play!

The easiest thing would be to take as $f_n$ something like the cos functions $n\alpha$. But, alas: cosine is not a polynomial. The following one comes to the rescue.

Lemma. The function 2 cos $n\alpha$ is expressed as a reduced polynomial of degree $n$ in the function 2 cos $\alpha$:

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

For example,

$$2 \cos 2\alpha = 4 \cos^2\alpha - 2 = (2 \cos \alpha)^2 - 2,$$

i.e. $f_2(x) = x^2 - 2$;

$$2 \cos 3\alpha = 8 \cos^3\alpha - 6 \cos \alpha = (2 \cos \alpha)^3 - 3(2 \cos \alpha),$$

i.e. $f_3(x) = x^3 - 3x.$

The proof of the lemma is carried out by induction. Let her statement be proven for the numbers $n-1$ and $n$:

$$2 \cos(n-1)\alpha = f_{n-1}(2 \cos \alpha),$$

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

From the formula

$$\cos(n+1)\alpha + \cos(n-1)\alpha = 2 \cos \alpha \cos n\alpha$$

it follows that

$$2 \cos(n+1)\alpha = (2 \cos \alpha)(2 \cos n\alpha) - 2 \cos(n-1)\alpha = (2 \cos \alpha)f_n(2 \cos \alpha) - f_{n-1}(2 \cos \alpha).$$

Means,

$$f_{n+1}(x) = xf_n(x) - f_{n-1}(x).$$

The lemma is proven, and at the same time a recurrent formula for calculating the polynomials $f_n(x)$ is obtained.

(For the ending, see p. 27).
