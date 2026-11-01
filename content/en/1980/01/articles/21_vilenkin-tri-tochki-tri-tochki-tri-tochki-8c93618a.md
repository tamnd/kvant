---
id: 1980-1-vilenkin-tri-tochki-tri-tochki-tri-tochki-8c93618a
issue: kvant_1980_1
year: 1980
number: "1"
title: Three dots, three dots, three dots...
authors:
  - Виленкин Н. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 52
page_labels: 48-50
tag: CMYQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: c84d8943b5dbb3c50848f463caf1334face4cd5239ac164d6cf964fff245552b
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/21_vilenkin-tri-tochki-tri-tochki-tri-tochki-8c93618a.md
source_content_sha256: fef720c42aefc52d51a1088437d3d80f5b0cf0cffcbbbcd25d4e1022b8952637
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

N. Vilenkin

Three dots, three dots, three dots...

Once, during the entrance exams for a university where mathematics is studied in great depth and therefore has high requirements for applicants, one applicant was asked a question that was quite simple at first glance:

How many solutions does the equation $\left(\frac{1}{16}\right)^x = \log_{\frac{1}{16}} x$ have?

Since solving the equation $\varphi(x) = \psi(x)$ is equivalent to finding the abscissa of the point at which the graphs of the functions $y = \varphi(x)$ and $y = \psi(x)$ intersect, the examinee made an eximega of the graphs of the functions $y = \left(\frac{1}{16}\right)^x$ and $y = \log_{\frac{1}{16}} x$ (Fig. 1) and said:

“This equation has one solution. Moreover, since by the definition of a logarithm the functions $y = \left(\frac{1}{16}\right)^x$ and $y = \log_{\frac{1}{16}} x$ are inverse to each other, their graphs are negatively symmetrical.”

Fig. 1.

relative to the line $y = x$, and therefore the point of intersection of the graphs lies on this line. This means that to find it, we need to solve the equation $\left(\frac{1}{16}\right)^x = x$. But I don’t know how to solve it.”

The examiner replied:

“The fact that you do not know how to solve the equation $\left(\frac{1}{16}\right)^x = x$ is not a problem, we do not require this: it cannot be solved by elementary methods. What's worse is that you missed two of his solutions: $x = \frac{1}{2}$ and $x = \frac{1}{4}$. Plug these values ​​into the equation and check!”

And indeed, having written the solution $\left(\frac{1}{16}\right)^{\frac{1}{2}} = \log_{\frac{1}{16}} \frac{1}{2}$ and $\left(\frac{1}{16}\right)^{\frac{1}{4}} = \log_{\frac{1}{16}} \frac{1}{4}$, the applicant was saddened to discover that they were true:

$\left(\frac{1}{16}\right)^{\frac{1}{2}} = \log_{\frac{1}{16}} \frac{1}{2} = \frac{1}{4}$ and $\left(\frac{1}{16}\right)^{\frac{1}{4}} = \log_{\frac{1}{16}} \frac{1}{4} = \frac{1}{2}$. Thus, he was deceived by the “visibility”: the graphs of the functions $y = \left(\frac{1}{16}\right)^x$ and $y = \log_{\frac{1}{16}} x$ intersect not only at the point $P(b; b)$, but at two more points: $M\left(\frac{1}{4}; \frac{1}{2}\right)$ and $N\left(\frac{1}{2}; \frac{1}{4}\right)$, symmetrical to the relative line $y = x$.

The reason for the applicant's error is as follows. He knew that at $0 < a < 1$ the values of the functions $y = \log_a x$ increase indefinitely as $x$ approaches zero, and the function $y = a^x$ at $x = 0$ takes the value 1. From here he made the “conclusion” that on the entire interval $]0; b[$, where $b$ is the abscissa of the point $P$, $a^x < \log_a x$, and therefore the graphs of these functions have no other intersection points except $P$. However, this conclusion should be made in the same way as, looking at the final table of the USSR football championship, one should conclude that the winning team was ahead even after the first round - as is known, they believe it is very autumnal.

It turned out that for $a = \frac{1}{16}$ the graphs of the functions under consideration lead

⟦folio 49⟧

Fig. 2.

yourself much more cunning (Fig. 2): on the interval $0; \frac{1}{4}$ [above is the graph of the function $y = \log_{\frac{1}{16}} x$, on the interval $]\frac{1}{4}$; $b$ [function $y = \left(\frac{1}{16}\right)^x$ “takes the lead”, on the interval $]\beta; \frac{1}{2}$ [the graph of function $y = \log_{\frac{1}{16}} x$ is higher again, and only on ray $[\frac{1}{2}; +\infty[$ function $y = \left(\frac{1}{16}\right)^x$ finally becomes the leader - on this entire ray its graph is higher than the graph of function $y = \log_{\frac{1}{16}} x$.

In this case, we managed to figure out the relative position of the graphs and directly find the roots of the equation $\left(\frac{1}{16}\right)^x = \log_{\frac{1}{16}} x$. For other values ​​of $a$ the situation is worse, and it is difficult to answer without a detailed study how many intersection points the graphs of functions $y = \left(\frac{1}{15,5}\right)^x$ and $y = \log_{\frac{1}{15,5}} x$ or the graphs of functions $y = \left(\frac{1}{10}\right)^x$ and $y = \log_{\frac{1}{10}} x$ have. We will now describe how this study is carried out using arbitrary $^*$). Now we are only interested in case $0<a<1$.

Let us denote $\ln a$ by $-k^{**}$. Then the function $y = a^x$ and $y = \log_a x$ will be written as follows: $y = e^{-kx}$ and $y = -\frac{\ln x}{k}$.

Finding the points of intersection of their graphs is equivalent to finding the points at which the graph of the function $F(x) = e^{-kx} + \frac{\ln x}{k}$ intersects the abscissa axis, and this latter is associated with the study of the intervals of increase and decrease of the function $F$. To do this, we will find an arbitrary one:

$$F'(x) = -ke^{-kx} + \frac{1}{kx} = \frac{1 - k^2xe^{-kx}}{kx}.$$

Let's look at three cases.

First case: $0 < k < e$. Let us show that in this case $F'(x) > 0$ for all $x > 0$. To do this, it is enough to prove that the smallest value of the function $1 - k^2xe^{-kx}$ at $x > 0$ is positive. This smallest value is achieved at the point where $(1 - k^2xe^{-kx})' = 0$, that is, where $-k^2e^{-kx} + k^3xe^{-kx} = 0$. Solving this equation, we find $x = \frac{1}{k}$. In this case, the value of $x$ numeral in (1) is equal to $1 - ke^{-1}$, which is positive for $k < e$. Since this value is the smallest, then $F'(x) > 0$ for all $x > 0$.

From the fact that $F'(x) > 0$ at $x > 0$, it follows that the function $F$ returns on the ray $0; +\infty$ [and its graph will once intersect the x-axis $^*$]. Thus, at $0 < k < e$ the graphs of the functions $y = e^{-kx}$ and $y = -\frac{\ln x}{k}$ intersect only once, namely on the line $y = x$ (same as on figure 1).

Second case: $k > e$. Here it was a matter of circumstance. Let us denote by $b$ the abscissa of the intersection point

$*)$ This follows, for example, from paragraph 84 of the textbook “Algebra and the beginnings of analysis 10”.

**) See also «Kvant», 1977, No. 10, p. 37.
**) Since $0 < a < 1$, $\ln a < 0$.

⟦folio 50⟧

Fig. 4.

graphs $y = e^{-kx}$ and $y = x$. At this point $e^{-kb} = b = -\frac{\ln b}{k}$, and therefore $kb = -\ln b$. At $x = \frac{1}{k}$, the function $e^{-kx}$ is equal to $\frac{1}{e}$, and the function $y = x$ takes the value $\frac{1}{k}$, therefore, due to the condition $k > e$, the abscissa of the intersection point of the graphs of functions $y = e^{-kx}$ and $y = x$ is greater than $\frac{1}{k}$ (Fig. 3), that is $b > \frac{1}{k}$. But then $kb > 1$, and therefore

$$F'(b) = \frac{1 - k^2be^{-kb}}{kb} = \frac{1 - k^2b^2}{kb} < 0.$$

This means that for $k > e$ the derivative function $F$ at the point $x = b$ is different. Since $F(b) = 0$, the trace from $b$ will find points where $F(x) > 0$. Since as $x$ approaches zero, $F(x)$ becomes negative, there is at least one point $c$ lying between 0 and $b$ at which $F(x) = 0^*$. This shows that at $k > e$ the graph of the functions $y = e^{-kx}$ and $y = -\frac{\ln x}{k}$ intersect at least at one point not lying on the line $y = x$. From the fact that these graphs are symmetrical to each other relative to the straight line $y = x$, it follows that there is one more point of intersection. It can be proven that the graphs have no other intersection points besides these three (the proof is related to the study of the second arbitrary function $F$).

*) See previous book.

So, if $k > e$, the graphs in question have three intersection points.

Third case: $k = e$. At the intersection point $(b; b)$ of the graphs of the function $e^{-kx}$ and $-\frac{\ln x}{k}$ we have $e^{-kb} = b$ or, in our case, $e^{-eb} = b$. An immediate substitution verifies that the number $\frac{1}{e}$ is the root of the equation $e^{-ex} = x$. Since the function $e^{-ex}$ kills (on the entire line) and the function $x$ is increasing, the equation $e^{-ex} = x$ has at most one root. So, $b = \frac{1}{e}$. It is easy to check that $F(b) = F'(b) = 0$, so the graph of the function $F$ at $x = b = e^{-1}$ touches the x-axis.

In our case $F(x) = e^{-ex} + \frac{1}{e}\ln x$. Therefore $F'(x) = -e^{1 - ex} + \frac{1}{ex} = \frac{e^{ex} - 2}{xe^{ex} - 1}$.

The derivative function $e^{ex} - 2$ is quotative for $x < b$, equal to 0 for $x = b$, and positive for $x > b$. Therefore, the function $e^{ex} - 2$ is positive for all $x \neq b$. This means that for all positive $x \neq b$ we have $F'(x) > 0$. Consequently, the graph of the function $F$, touching the x-axis at the point $x = b$, changes sign from minus to the plane when passing the point $b$.

In accordance with this, the graphs of functions $y = e^{-ex}$ and $y = \frac{\ln x}{e}$, touching each other at their common point $(e^{-1}; e^{-1})$, “intertwine” with each other (Fig. 4).

To summarize: if $1 > a \geq e^{-e} \approx \frac{1}{15,18}$, then the graphs of the function $y = a^x$ and $y = \log_a x$ have one intersection point; if $e^{-e} > a > 0$, then there are three points of intersection.

Now we can say with confidence that the graphs of the function $y = \left(\frac{1}{15,5}\right)^x$ and $y = \log_{\frac{1}{15,5}} x$ have three points of intersection, and the graphs of the function $y = \left(\frac{1}{10}\right)^x$ and $y = \log_{\frac{1}{10}} x$ have only one common point.
