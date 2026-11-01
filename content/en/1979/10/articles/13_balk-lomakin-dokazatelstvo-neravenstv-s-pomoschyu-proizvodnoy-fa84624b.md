---
id: 1979-10-balk-lomakin-dokazatelstvo-neravenstv-s-pomoschyu-proizvodnoy-fa84624b
issue: kvant_1979_10
year: 1979
number: "10"
title: Proving inequalities using derivatives
authors:
  - Балк М. Б.
  - Ломакин Ю. В.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 40
page_labels: 36-38
tag: CPOD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a8f6c25bf817ae9a924112c2c8f994b25780b2f721591ad413842c696bfb93c
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/13_balk-lomakin-dokazatelstvo-neravenstv-s-pomoschyu-proizvodnoy-fa84624b.md
source_content_sha256: a062e6d54767d0c633bd1c9a5662cae9e503489fc2fc841f9d249f01164772a0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Proving inequalities using an arbitrary value at the school camp "Matematik-79" (Vologda region), it is shown how the process of information about arbitrary values ​​can be used to verify the truth of inequalities.

To prove inequalities, the following theorem is especially useful (“Algebra and Principles of Analysis 9,” paragraph 54):

Theorem 1. If the function $f$ has a positive arbitrary integral $|a|; b|$, then this function returns to $|a|; b|$. If the function $f$ has a negative arbitrary integral $|a|; b|$, then the function in which urine turns out (or, correspondingly, decreases) takes place throughout this entire result $*$).

Let's start with two examples of the application of this theorem: the first is simple, the second is the last.

Example 1. Prove that for $x > 1$
$$x^2 - 1 > 2 \ln x.$$
Does this inequality hold for $0 < x < 1$?

Solution. Consider the function $f(x) = x^2 - 1 - 2 \ln x$.

*) An analogous statement remains true if instead of getting the merale $|a|; b|$ we get the merale $|a|; b|$ or the segment $|a|; b|$.

We have
$$f'(x) = 2x - \frac{2}{x} = \frac{2}{x}(x^2 - 1) > 0$$
at $x > 1$.

Therefore $f$ returns to $1; +\infty$ [. If we also take into account that the function $f$ is continuous on $1; +\infty$ [ (that is, at any point in this interval), then the return of $f$ takes place on $1; +\infty$ [. Therefore, at $1 < x < +\infty$ there will be $f(x) > f(1)$, i.e. $x^2 - 1 - 2 \ln x > 0$. So, $x^2 - 1 > 2 \ln x$ at $0 < x < 1$.

Example 2. Elevation, which is greater: $79^{3/5} + 1900^{3/5}$ or $1979^{3/5}$?

Solution. Let's solve a more extensive problem: what is greater than $a^p + b^p$ or $(a + b)^p$, if $0 < a < b$ and $0 < p < 1$? Consider on $0; +\infty$ [function $f(x) = (a + x)^p - (a^p + x^p)$].

We have:
$$f'(x) = p(a + x)^{p-1} - px^{p-1} = p\left(\frac{1}{a+x}\right)^{p-1} - \left(\frac{1}{x}\right)^{p-1} < 0$$
at $0 < x < +\infty$. This means $f$ by $0; +\infty$ [decreases. Therefore, from $0 < a < b$ it follows that $f(b) < f(a)$, i.e. $(a + b)^p - (a^p + b^p) < (a + a)^p - (a^p + a^p) = a^p(2^p - 2) < 0, a^p + b^p > (a + b)^p$. Specifically, $79^{3/5} + 1900^{3/5} > 1979^{3/5}$.

To solve further examples we need the following corollary from Theorem 1:

Theorem 2. Let whichever of the functions $f$ and $g$ be continuous in which we obtain the integral $|a|; b|$ and have an arbitrary integral $|a|; b|$ in whichever. To do this, the inequality is true everywhere on the integral $|a|; b|$
$$f(x) < g(x),$$
(1)
It is enough that two conditions are simultaneously satisfied:
I. $f'(x) < g'(x)$ everywhere on $|a|; b|$,
(2)

⟦folio 37⟧

P. $f(a) \leq g(a)$. (3)

Proof. The function $F(x) = g(x) - f(x)$ is continuous on $[a; b]$, and $F(a) \geq 0$ and $F'(x) > 0$ on $[a; b]$. By Theorem 1, the function $F$ increases by $[a; b]$, so that for $a < x < b$ we have $F(x) > F(a) \geq 0$, i.e. $f(x) < g(x)$ everywhere on $[a; b]$.

We will also illustrate the application of Theorem 2 with two examples.

Example 3. Prove that for $x > 0$
$$\ln(1+x) < x.$$ (4)

Solution e. Differentiating (4), we obtain
$$\frac{1}{1+x} < 1,$$
which is obviously true at $[0; +\infty]$. Also, $\ln(1+0) = 0$. Therefore, according to Theorem 2, inequality (4) is true for $0 < x < +\infty$.

Example 4. Check whether the inequality holds for $x_1 > x_2 > 0$
$$\frac{x_1 - x_2}{\ln \frac{x_1}{x_2}} < \frac{1}{2}(x_1 + x_2).$$ (5)

Solution e. We can move from an inequality with two variables to an inequality with one variable if we set $x = \frac{x_1}{x_2}$. Then (5) takes the form
$$\frac{x-1}{\ln x} < \frac{1}{2}(x+1).$$ (6)

$x_1 > x_2 > 0$ implies $x > 1$. Differentiating a fraction with $\ln x$ in the denominator is inconvenient. Let us therefore rewrite inequality (6) in the following equivalent form:
$$\frac{x-1}{x+1} < \frac{1}{2}\ln x.$$ (7)

*) If we additionally require that the functions $f$ and $g$ are not true at the point $b$, then (as is clear from the proof) inequality (1) will be true at the point $b$. It can be proven that Theorem 2 remains true in the case when strict inequality (2) is violated (replaced by the equality $f'(x) = g'(x)$) at a finite number of points (or even at an infinite number of points, unless such points fill some interval of the form $]a; c[$, where $a < c \leq b$).

To decide whether this inequality is true, let us find out whether the inequality that arises when it is differentiated term by term is true. So we must consider the inequality
$$\frac{2}{(x+1)^2} < \frac{1}{2x}$$ (8)

or the equivalent inequality $(x-1)^2 > 0$.

The latter is true for $x > 1$ and, therefore, for these $x$ (8) is true. Further, at $x = 1$ both sides of inequality (7) take equal (zero) values. We see that the conditions of Theorem 2 are met, so inequality (7) is true, and along with it (6) and (5) are true.

Sometimes, when proving an inequality, it is useful to apply term-by-term differentiation not once, but several times. More precisely, it is sometimes useful to use the following corollary from Theorem 2*):

Theorem 3. Let which of the functions $f$ and $g$ be incorrect on the derivation $[a; b]$ and have a derivative of order $n$ at each point of the integral $]a; b[$. In order for the inequality to be true everywhere
$$f(x) < g(x) \text{ на } [a; b],$$ (9)
it is enough that the following conditions are also satisfied:
I. The inequality obtained from inequality [9] by $n$-fold differentiation, $m. k$, holds. everywhere on $[a; b]$
$$f^n(x) < g^n(x);$$ (10)
II. $f(a) \leq g(a)$,
$$f'(a) \leq g'(a),$$ ...
... $f^{(n-2)}(a) \leq g^{(n-2)}(a);$
$$f^{(n-1)}(a) \leq g^{(n-1)}(a).$$

Proof. Since $[f^{(n-1)}(x)]' < [g^{(n-1)}(x)]'$ is on $[a; b]$ and $[f^{(n-2)}(x)]' < [g^{(n-2)}(x)]'$ is everywhere on $[a; b]$. In addition, according to the conditions, $f^{(n-2)}(a) \leq g^{(n-2)}(a)$. Therefore, by theorem

*) The derivative of an arbitrary function $f$ is called its second arbitrary function and is denoted by $f''$; similarly, the definitions of the third, fourth are arbitrary and in general arbitrary of any order $n$ (notation: $f^{(n)}$).

⟦folio 38⟧

reme 2: $f^{(n-2)}(x) < g^{(n-2)}(x)$ always on $|a|; b[$. Repeating similar calculations, after a finite number of steps we obtain that everything on $|a|; b[$ is valid for strict inequalities $f^{(n-3)}(x) < g^{(n-3)}(x), \dots, f''(x) < g''(x), f'(x) < g(x)$ and, finally, $f(x) < g(x)$, which is what we need to prove.

Example 5. Prove that for $x \neq 0$ the inequality $e^x + e^{-x} > 2 + x^2$ is true.

Solution. Let us first consider the case $x > 0$. Let us differentiate (11) term by term several times and see if we get an inequality whose validity is beyond doubt. We get the following:
$e^x - e^{-x} > 2x;$
$e^x + e^{-x} > 2;$
$e^x - e^{-x} > 0$.

The last inequality for $x > 0$ is very true. In addition, for $x = 0$ the equalities $e^0 + e^{-0} = 2 + 0^2, e^0 - e^{-0} = 2 \cdot 0, e^0 + e^{-0} = 2$ are true. By virtue of Theorem 3, inequality (11) is true for $x > 0$. Since replacing $x$ with $-x$ both sides of inequality (11) do not change, this inequality is also true for all $x < 0$.

List of readers who sent corrected solutions to problems from the Problem Book «Kvant»
(End. See beginning on pp. 7, 14, 25)
(Kaynas) 38; G. Irisov (Donetsk) 40;
A. Kapralov (Tbilisn) 38-41; V. Kelman (Moscow) 38, 40; E. Kodan (Dipropetrovsk) 38; A. Kozhevnikov (Dipropetrovsk) 34; G. Kolomitsev (Sumgant) 36; V. Komov (Alexandrov) 33-41, 43-46; K. Kondratye (Moscow) 38, 40, 45, 47; Yu. Kordyukov (Serov) 38; I. Korotkov (Volgograd) 43, 47; A. Kostereyev (Semiluk) 38-41; O. Kravets (Voronezh) 40, 41, 46; A. Kreines (Kolchugino) 35; A. Kruntsov (Kursk) 33; A. Kuprin (Moscow) 38—41; V. Kuryan (Rostov-on-Don) 34, 38—41, 44; A. Kucher (Donetsk) 35; A. Kusherov (Moscow) 38, 44; A. Lazaryan (Lobnya, Moscow region) 35, 37; V. Lashkin (Kyiv) 35-40; A. Lebedev (Gorky) 40; S. Lodunov (Moscow) 40, 47; D. Lodmirsky (Kyiv) 33, 34, 36, 37, 47; S. Mazaryan (Kostroma) 38; S. Malamanov (Leningrad) 35, 38; A. Maslennikov (n. N-Taryal Mar Autonomous Soviet Socialist Republic) 46; A. Minaev (Saratov) 38; A. Mocilier (Sverdlovsk) 35, 38, 40, 41, 44, 46, 47; M. Morozov (Ashgabat) 40; I. Muromtsev (Moscow) 33, 36, 38-41; D. Nadezhdin (Kurgan) 38-41; V. Natalia (Ashgabat) 38, 47; A. Odlovlin* (Irkutsk) 38, 41; I. Omelyan (Lviv) 35, 37—44, 46, 47; O. Orzamedov (regional center Kyzyl-Atrek, TSSR)

Urazhenya

Check the validity of the following inequalities:
1. $e^x > 1 + x$ at $x \neq 0$;
2. $(p + q)^6 < 32(p^6 + q^6)$ at $p > 0, q > 0$;
3. $\sin x > x - \frac{x^3}{6}$ at $x > 0$;
4. $2\sqrt{x} > 3 - \frac{1}{x}$ at $x > 1$;
5. $tg x > x + \frac{x^3}{3}$ at $0 < x < \frac{\pi}{2}$;
6. $\sin x < \frac{1}{2}x(\pi - x)$ at $0 < x < \frac{\pi}{2}$;
7. $2ab \ln \frac{b}{a} < b^2 - a^2$ at $0 < a < b$;
8. $e^x > 1 + x + \frac{1}{2}x^2$ at $x > 0$;
9. $\ln (1 + x) < x - \frac{x^2}{2} + \frac{x^3}{3}$ at $x > 0$.

10. A regular $n$-gon with perimeter $p_n$ is inscribed in a circle of radius $R$, and a regular $n$-gon with perimeter $P_n$ is not inscribed. Prove the following inequality (due to the famous physicist and mathematician Christas Huygens): $2p_n + P_n > 6\pi R$.
