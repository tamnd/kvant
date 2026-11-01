---
id: 1979-12-ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1
issue: kvant_1979_12
year: 1979
number: "12"
title: Converting solutions to a trigonometric equation
authors:
  - Иванов В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 36
page_last: 37
page_labels: 34-35
tag: 5Y6H
lang: en
source: kvant_digital
extraction: vision
content_sha256: 078838304ec1ef8eca2b0dfe30cad52e08736227e52b0115a11f67407315ccdd
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/12_ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1.md
source_content_sha256: 55b68c49d54f2a5e79033a4dc07be45f0fc5956fbdc53b3fb7e60801177fd508
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Transforming the solution of a trigonometric equation

Obviously, an arbitrary natural number $n$ can be represented as either $n=2t$ or $n=2t+1$. Moreover, any natural number $n$ can be represented as either $n=3t$, $n=3t+1$, or $n=3t+2$. Further, all coefficients of the number $n$ can be represented as either $n=4t$, or $n=4t+1$, or $n=4t+2$, or $n=4t+3$. It. d. This series of statements is the theoretical basis for the transformation that comes sometimes with solutions to a trigonometric equation.

Example 1 (NSU, Mechanics and Mathematics, 1974). Solve the equation

$$\sqrt{\cos 2x - \sin 4x} = \sin x - \cos x.$$ (1)

The obvious way to solve equation (1) is to square both sides of the equation:

$$\cos 2x - \sin 4x = (\sin x - \cos x)^2.$$ (2)

After easy equivalent x transformed we get

$$\sin x (\sin x + \cos 3x) = 0.$$

Thus, equation (2) has the answer:

$$\begin{cases}
x_1 = \pi k & (k \in \mathbb{Z}), \\
x_2 = \frac{\pi}{4} + \pi l & (l \in \mathbb{Z}), \\
x_3 = -\frac{\pi}{8} + \frac{\pi}{2} m & (m \in \mathbb{Z}).
\end{cases}$$

But equation (2), generally speaking, is not equivalent to equation (1); it is only introductory from (1). Therefore it is necessary to do a check.

The shortest common period of the functions $2x$, $\sin 4x$, $\sin x$ and $\cos x$ is $2\pi$. This means that if the number $a$ is a root of equation (1), then all the numbers $a+2\pi t$ ($t \in \mathbb{Z}$) are its roots. Therefore, we write down solution (3) “with period $2\pi$”.

Replacing the variable $k$ in $x_1$ with $k=2t$ and $k=2t+1$, we get

$$\begin{cases}
x_{11} = 2\pi t, \\
x_{12} = \pi + 2\pi t.
\end{cases}$$

Similarly, from $x_2$ we obtain

$$\begin{cases}
x_{21} = \frac{\pi}{4} + 2\pi t, \\
x_{22} = \frac{5}{4} \pi + 2\pi t.
\end{cases}$$

Replacing the variable $m$ in $x_3$ with $m=4t$, $m=4t+1$, $m=4t+2$ and $m=4t+3$, we get

$$\begin{cases}
x_{31} = -\frac{\pi}{8} + 2\pi t, \\
x_{32} = \frac{3}{8} \pi + 2\pi t, \\
x_{33} = \frac{7}{8} \pi + 2\pi t, \\
x_{34} = \frac{11}{8} \pi + 2\pi t.
\end{cases}$$

From ($3_1$), ($3_2$), ($3_3$) it is clear that, in view of the above, it is enough to check the numbers 0, $\pi$, $\frac{\pi}{4}$, $\frac{5}{4}\pi$, $-\frac{\pi}{8}$, $\frac{3}{8}\pi$, $\frac{7}{8}\pi$, $\frac{11}{8}\pi$. You can simply substitute these 8 numbers into (1). It is simpler, however, to say that equation (1) is equivalent to a “mixed system.”

Fig. 1.

⟦folio 35⟧

$$\begin{cases} \cos 2x - \sin 4x = (\sin x - \cos x)^2, \\ \sin x - \cos x \geq 0. \end{cases}$$

Thus, it is enough to look (Fig. 1) which of the written numbers satisfy the inequality $\sin x \geq \cos x$. This inequality is “withstood” by $\pi, \frac{\pi}{4}, \frac{5}{4}\pi, \frac{3}{8}\pi$ and $\frac{7}{8}\pi$.

This means that the answer to equation (1) includes $x_{12}, x_{21}, x_{22}, x_{32}$ and $x_{33}$. If desired, $x_{21}$ and $x_{22}$ can be combined “backwards”.

Example 2: Solve the equation

$$\sin 7x + \cos 2x = -2. \tag{4}$$

Since $\min \sin 7x = \min \cos 2x = -1$, equation (4) is equivalent to the system

$$\begin{cases} \sin 7x = -1, \\ \cos 2x = -1. \end{cases}$$

Solving the first equation of the system

$$x_1 = \frac{3}{14}\pi + \frac{2\pi}{7}k (k \in \mathbb{Z}), \tag{5}$$

solution to the second equation

$$x_2 = \frac{\pi}{2} + \pi l (l \in \mathbb{Z}). \tag{6}$$

To find the intersection of sets (5), (6), we write them “with a period of 2n”. Replacing the variable $k$ in (5) with $7t, 7t+1, 7t+2, 7t+3, 7t+4, 7t+5$ and $7t+6$, we obtain

$$\begin{cases} x_{11} = \frac{3}{14}\pi + 2\pi t, \\ x_{12} = \frac{\pi}{2} + 2\pi t, \\ x_{13} = \frac{11}{14}\pi + 2\pi t, \\ x_{14} = \frac{15}{14}\pi + 2\pi t, \\ x_{15} = \frac{19}{14}\pi + 2\pi t, \\ x_{16} = \frac{23}{14}\pi + 2\pi t, \\ x_{17} = \frac{27}{14}\pi + 2\pi t. \end{cases} \tag{7}$$

Replacing the variable $l$ in (6) with $l=2t$ and $l=2t+1$, we obtain

$$\begin{cases} x_{21} = \frac{\pi}{2} + 2\pi t, \\ x_{22} = \frac{3}{2}\pi + 2\pi t. \end{cases} \tag{8}$$

From a comparison of (7) and (8) the answer is visible:

$$x_{12}.$$

Example 3 (MSU, Faculty of Chemistry, 1977). Find the solution to the equation

$$2 - \sqrt{3}\cos 2x + \sin 2x = 4\cos^2 3x, \tag{9}$$

satisfying inequality

$$\cos \left(2x - \frac{\pi}{4}\right) > 0.$$

Equation (9) is equivalent to equation

$$1 - \cos \left(2x + \frac{\pi}{6}\right) = 1 + \cos 6x.$$

To Pozny his answer:

$$\begin{cases} x_1 = \frac{5}{48}\pi + \frac{\pi}{4}k (k \in \mathbb{Z}), \\ x_2 = \frac{7}{24}\pi + \frac{\pi}{2}l (l \in \mathbb{Z}). \end{cases}$$

So that $2x - \frac{\pi}{4}$ has a period $2\pi$, we write this answer “with a period $l$”. Replacing the variable $k$ in $x_1$ with $k = 4t, k = 4t+1, k = 4t+2$ and $k = 4t+3$, we get

$$\begin{cases} x_{11} = \frac{5}{48}\pi + \pi t, \\ x_{12} = \frac{17}{48}\pi + \pi t, \\ x_{13} = \frac{29}{48}\pi + \pi t, \\ x_{14} = \frac{41}{48}\pi + \pi t. \end{cases}$$

From here

$$\begin{cases} 2x_{11} - \frac{\pi}{4} = -\frac{\pi}{24} + 2\pi t, \\ 2x_{12} - \frac{\pi}{4} = \frac{11}{24}\pi + 2\pi t, \\ 2x_{13} - \frac{\pi}{4} = \frac{23}{24}\pi + 2\pi t, \\ 2x_{14} - \frac{\pi}{4} = \frac{35}{24}\pi + 2\pi t. \end{cases}$$

It can be seen that the required inequality satisfies the inequality $x_{11}$ and $x_{12}$.

Similarly, replacing the variable $l$ in $x_2$ with $l=2t$ and $l=2t+1$, we obtain
