---
id: 1975-8-byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98
issue: kvant_1975_8
year: 1975
number: "8"
title: Constructing equations from function graphs
authors:
  - Быстрый И. М.
rubric: raznoe
page_first: 56
page_last: 59
page_labels: 54, 56, 57
tag: 90VB
lang: en
source: kvant_digital
extraction: vision
content_sha256: a890127f1fe89eba54c0fcc834c1daf3ee96227982bf5b6fe3e447844883d863
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/13_byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98.md
source_content_sha256: 8a783133ed3111199adc014dc698a727129559f41dde686aca4cc95fbedf2953
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Constructing equations from function graphs

The need to construct equations of functions arises when solving various problems. Such problems occur in mathematics, physics, and, most importantly, in modern technology. This article shows how, using the equation of elematrine functions [equation of a straight line, parabola, sinusoid], you can describe graphs of more complex dependencies found in a school physics course. More precisely, in those sections where periodic processes are discussed.

Let us first recall several important properties of function graphs.

1. If the graph of the function $F_1(x)$ is shifted by $|c|$ units up or down along the ordinat axis of the graph of the function $f(x)$, $x \in [a, b]$, then the equation of the function $F_1(x)$ has the form

$$F_1(x) \quad f(x) \pm |c|, \quad x \in [a, b]$$

Moreover, if the graph moves upward, you should take the “+” sign, and if downward, you should take the “-” sign.

2. If the graph of the function $F_2(x)$ is the graph of the function $f(x)$, $x \in [a, b]$ shifted by $|c|$ units to the left or right along the abscissa axis, then the equation of the function $F_2(x)$ has the form

$$F_2(x) - f(x \pm |c|), \quad x \in [a \mp |c|, b \mp |c|]$$

Moreover, the upper signs are taken when the graph moves to the left, and the lower ones - when it moves to the right.

3. If the graph of the function $F(x)$ is symmetrical with respect to the abscissa axis of the graph of the function $f(x)$, $x \in [a, b]$, then the equation $F(x)$ has the form

$$F(x) - f(x), \quad x \in [a, b]$$

Let's now look at some examples.

Fig. 1.

Fig. 2.

⟦folio none⟧

"Pill-shaped" direction

Let's try to use the above properties of function graphs to describe the “pill-shaped” direction (Fig. 1). a direction of this type is supplied, for example, to the deflection plates of an oscilloscope electron tube. It is characteristic of the “pill-shaped” direction that the time $T$ of its rise is long compared to the time of decline $t$. Therefore, graphically, the change in direction during time can be represented as a line shown in figure 2. However, in this case there is a need for points

$$t = \frac{T}{2} (2n + 1),$$

$n$ is an integer. To avoid ambiguity, let’s replace the “pill-shaped” line with a graph of a function that is not defined at all at points

$$t = \frac{T}{2} (2n + 1),$$

or the graph of the function defined at these points on the left or right (Fig. 3, $a$, $b$, $\theta$).

To obtain control of the periodic function $u(t)$ changed to figure 3, $a$, we study it when the argument changes within one period, for example, $\left(-\frac{T}{2}, \frac{T}{2}\right)$.

In this interval, the graph of the periodic function $u(t)$ coincides with the graph of the function $u_0 = f(t) = t^*$). Let us now shift the graph $u_0$ along the x-axis one period to the right (red line at figure). then we obtain a new function $u_1 = f(t - T) = t - T$, and the interval $\left(-\frac{T}{2}, \frac{T}{2}\right)$ will go into the interval $\left(\frac{T}{2}, \frac{3}{2} T\right)$. By shifting the graph of the function $u_0$ along the x-axis by an integer number $n$ periods, every

$$*) \text{Точнее, } f(t) = At, \text{ где } A = 1 \ \theta/c \text{-размерный коэффициент.}$$

times for a fixed $n$ we obtain a new function

$$u_n = f(t - nT) = t - nT,$$

$$t \in \left(\frac{T}{2} (2n - 1), \frac{T}{2} (2n + 1)\right).$$

The set of these functions at $n = 0, \pm 1, \pm 2, \dots$ constitutes the equation of the exclusive function $u(t)$.

If the period of the function is $T = \pi$ seconds, then its equation can be written differently:

⟦folio 56⟧

line segments parallel to the ordinat axis. Their equations are:

$$t(u) = \frac{T}{2}(2n+1),$$
$$u \in \left[-\frac{T}{2}, \frac{T}{2}\right], \quad n = 0, \pm 1, \pm 2, \ldots$$

Path equation

figure 4 shows a graph of the path traversed by a point moving in a straight line.
Let us construct the path equation *).

It is obvious that the graph $S(t)$ is composed of sections of the parabola $S_\alpha = at^2$, $t \in \left[0, \frac{T}{2}\right]^{**}$. Let's make the following transformations:

1) branch ($\alpha$) is cut symmetrically relative to the ordinat axis - we obtain branch ($\beta$): $S_\beta = at^2$, $t \in \left[-\frac{T}{2}, 0\right]$;

2) branch ($\beta$) is cut symmetrically relative to the abscissa axis - we obtain branch ($\gamma$): $S_\gamma = at^2$, $t \in \left[-\frac{T}{2}, 0\right]$;

3) move branch ($\gamma$) $T$ to the right and $\frac{aT^2}{2}$ up - we get branch ($\delta$): $S_\delta = -a(t-T)^2 + \frac{aT^2}{2}$, $t \in \left[\frac{T}{2}, T\right]$.

Moving the branch ($\alpha$) and ($\delta$) by $nT$ to the right and by $\frac{aT^2}{2}$ up, with variable $n = 0, 1, 2, \ldots$ we will have

$$S(t) = \begin{cases} a(t-nT)^2 + n\frac{aT^2}{2}, \\ t \in [nT, \frac{T}{2} + nT]; \\ -a[t-(n+1)T]^2 + (n+1)\frac{aT^2}{2}, \\ t \in \left[\frac{T}{2} + nT, (n+1)T\right]. \end{cases}$$

*) See «Kvant», 1973, No. 11, p. 60.
**) Here $a$ is the proportionality coefficient. If a point moves with acceleration $b$, then $a = b/2$

⟦folio 57⟧

⟦figure⟧
Fig. 5.

⟦figure⟧
Fig. 6.

⟦figure⟧
Fig. 7.

⟦figure⟧
Fig. 8.

⟦figure⟧
Fig. 9.

⟦column⟧
If we transform the second part like this:

$$--a\left[\left(t-nT-\frac{T}{2}\right)-\frac{T}{2}\right]^2+\frac{aT^2}{2}+$$

$$+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t--(2n+1)\frac{T}{2}\right]-\frac{aT^2}{4}+$$

$$+\frac{aT^2}{2}+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t-(2n+1)\frac{T}{2}\right]+\frac{aT^2}{4}(2n+1),$$

then the path equation can be written as follows:

$$S(t)=(-1)^m a\left(t-m\frac{T}{2}\right)^2+$$

$$+\frac{1-(-1)^m}{2}aT\left(t-m\frac{T}{2}\right)+m\frac{aT^2}{4},$$

$$t\in\left[m\frac{T}{2},(m+1)\frac{T}{2}\right], m=0,1,2,\dots$$

Exercises

1. Write the equations of the lines shown in Figures 5, 6 and 7. For the line shown in figure 5, write the equations of the functions defined at the points $t=n\pi$ on the left and right.
2. “Push-pull” (full-wave) rectification of alternating current is carried out using a circuit with two electron tube diodes. If the positive half-cycles of the current pass through one diode, and the negative half-cycles through the other, then the voltage waveform will look like the line shown in figure 8. Find the equation of this line.
3. Half-wave AC rectification can be achieved using a single diode circuit. Then half-cycles of one sign pass through the diode, but half-cycles of the other sign do not pass through. The voltage waveform is shown at figure 9. Find the equation of this function.
4. Construct an equation of a function whose graph (see Fig. 4) on sections $[nT,(n+1)T]$, $n=0,1,2,\dots$ is congruent to the graph of the function

$$y=A\sin x,\ x\in\left[-\frac{\pi}{2},\frac{\pi}{2}\right].$$
