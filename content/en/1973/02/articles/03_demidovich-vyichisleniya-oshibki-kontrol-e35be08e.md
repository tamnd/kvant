---
id: 1973-2-demidovich-vyichisleniya-oshibki-kontrol-e35be08e
issue: kvant_1973_2
year: 1973
number: "2"
title: Calculations, errors, control
authors:
  - Демидович Н. Б.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11-16
tag: KYHH
lang: en
source: kvant_digital
extraction: vision
content_sha256: be3a796b46605a373bbf6b658e690b5bff11aca890320db513b5ddc377e70256
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/03_demidovich-vyichisleniya-oshibki-kontrol-e35be08e.md
source_content_sha256: 9161f4fb26fdee153bf16871ebc42397b556d2a9c3802340442724bd4be546cf
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Calculations, errors, control
N. B. Demidovich

Observation errors
Counting accurately does not always mean counting correctly. Distance for an example of the following problem.
The side of a square piece of land is 1.4 m. What is its half-perimeter p and area S (Fig. 1)?
The solution is self-directed: $p = 1,4 + 1,4 = 2,8$ ($m$), $S = 1,4 \times 1,4 = 1,96$ ($m^2$). But how accurate is this answer? Absolutely accurate if the length of the side of the section is specified exactly. What if it is not specified, but, for example, measured with a decimeter measuring tape? Then it is natural to assume that 1.4 m is a division of the tape, close to the true length of the measured side of the site. From here it is only clear that the exact length differs from 1.4 m by no more than 0.05 m, that is, the absolute value of the observation error (it is called the absolute value)

Fig. 1.

of the measured value x and is designated $\Delta_x$) does not exceed 0.05 m.

A practical important question arises: with what accuracy can the area be determined at the specified preconditions? This and similar questions are dealt with by a special branch of mathematics - the theory of approximate calculations. Let us demonstrate its methods using this problem.

Let the true length of the side (hereinafter all lengths are measured in meters) equal to 1.4 + $\alpha$, where $|\alpha| \leq 0,05$, that is, $0,5 \leq \alpha \leq 0,05$. Then the half-perimeter of the section is equal to $p = (1,4 + \alpha) + (1,4 + \alpha) = 2,8 + 2\alpha$.

The absolute error $\Delta_p$ of the half-perimeter value of 2.8 does not exceed $2 \times 0,05 = 0,1$, that is $2,7 = 2,8 - 0,1 \leq p \leq 2,8 + 0,1 = 2,9$.

Easily Tested Formula
$$\left|(x_{\text{прибл.}} \pm y_{\text{прибл.}})\right| \leq \Delta_x + \Delta_y$$

shows that when adding and subtracting numbers, their absolute errors add up.

When multiplying numbers, it is more convenient to deal with relative error. The relative error $\Delta_x$ of the number x is called the ratio of the absolute error $\Delta_x$ to the absolute value of the number x: $\varepsilon_x = \frac{\Delta_x}{x_{\text{точн}}}$. Because $x_{\text{точн}}$ we

⟦folio 12⟧

we don’t know, we can replace $\varepsilon'_x$ with $\varepsilon_x$, where $\varepsilon_x = \frac{\Delta_x}{x_{\text{прибл}}}$. In this example $\varepsilon_x = \frac{0,05}{1,4} \approx 0,036 = 3,6\%$.

By replacing the values ​​of $\varepsilon'_x = \frac{\Delta_x}{x_{\text{точн}}}$ with $\varepsilon_x = \frac{\Delta_x}{x_{\text{прибл}}}$, we, of course, allow for some error, but it is usually so small that it is always neglected.

When multiplying and dividing numbers, their relative error is added. We leave the proof of this statement to the reader; then we just need to estimate the numbers

$$\varepsilon_{xy} = \left| \frac{(x + \alpha)(y + \beta) - xy}{xy} \right|$$

And

$$\varepsilon_{\frac{x}{y}} = \left| \frac{\frac{x + \alpha}{y + \beta} - \frac{x}{y}}{\frac{x}{y}} \right|.$$

Now let's get back to our task. The area of ​​the site is obtained as the product of the length of the sides, so its relative error is of the order of 7.2%. The accepted calculations give

$$S = (1,4 + \alpha)^2 = 1,96 + 2,8\alpha + \alpha^2.$$

Here 1.96 is our initial answer, and the other two terms are its deviations from the exact answer. Let us estimate the absolute error of the result:

$$\Delta_S \leq |2,8\alpha + \alpha^2| \leq |2,8\alpha| + \alpha^2 \leq |2,8 \cdot 0,05| + |0,05|^2 = 0,1425 < 0,15.$$

This means that the area $S$ lies within

$$1,81 = 1,96 - 0,15 < S < 1,96 + 0,15 = 2,11.$$

The last formula clearly shows that in the initial answer 1.96, containing two digits of the last one, there may not be a single correct digit.

Thus, the theory of approximate calculations frees us from the illusion that a larger number of accurately calculated digits always ensures a corresponding accuracy of the result itself. Moreover, it gives an answer to how the accuracy of the result depends on the accuracy of the initial data, their quantity and the type of action performed on them.

Rounding numbers

In the original example, we decided that the number 1.4 m was obtained by changing it with a decimeter measuring tape and therefore the error of the change does not exceed 7.2%. The accepted calculations give

$$S = (1,4 + \alpha)^2 = 1,96 + 2,8\alpha + \alpha^2.$$

Here 1.96 is our initial answer, and the other two terms are its deviations from the exact answer. Let us estimate the absolute error of the result:

$$\Delta_S \leq |2,8\alpha + \alpha^2| \leq |2,8\alpha| + \alpha^2 \leq |2,8 \cdot 0,05| + |0,05|^2 = 0,1425 < 0,15.$$

This means that the area $S$ lies within

$$1,81 = 1,96 - 0,15 < S < 1,96 + 0,15 = 2,11.$$

The last formula clearly shows that in the initial answer 1.96, containing two digits of the last one, there may not be a single correct digit.

Thus, the theory of approximate calculations frees us from the illusion that a larger number of accurately calculated digits always ensures a corresponding accuracy of the result itself. Moreover, it gives an answer to how the accuracy of the result depends on the accuracy of the initial data, their quantity and the type of action performed on them.

One example

In the theory of approximate calculations, in particular, calculation examples are also developed, which, while guaranteeing the achievement of the required accuracy of the result, reduce the number of operations to a minimum.

Consider, for example, the multiplication of positive $n$-bit proper decimal fractions, that is, numbers of the form

$$A = 0, a_1 a_2 \dots a_n,$$

where $0 \leq a_i \leq 9$ ($i = 1, 2, \dots, n$). It is known that the decimal fraction (1) is an abbreviation for the number

$$A = \frac{a_1}{10} + \dots + \frac{a_i}{10^i} + \dots + \frac{a_n}{10^n}.$$

⟦folio 13⟧

We will consider fraction (1) to be an approximate, correctly rounded number. Then it has an absolute error not exceeding $\frac{5}{10^{n+1}}$.

Let

$$A = 0, a_1 a_2 \dots a_n,$$
$$B = 0, b_1 b_2 \dots b_n$$

are two approximate numbers, and $\alpha$ and $\beta$ are their corresponding deviations from the exact numbers, and the same: $|\alpha| \leq 0,5 \cdot 10^{-n}, |\beta| \leq 0,5 \cdot 10^{-n}$. Let's calculate the absolute error of the product:

$$\Delta_{AB} = (A + \alpha) \cdot (B + \beta) - AB = \alpha \cdot B + \beta \cdot A + \alpha \cdot \beta.$$

Here $|\alpha \cdot \beta| = |\alpha| \cdot |\beta| \leq 0,5 \times 10^{-n} \cdot 0,5 \cdot 10^{-n} = 0,25 \cdot 10^{-2n}$, that is, this term in modulus does not exceed the last four possible digits of the result and therefore may not be taken into account. Let us estimate the sum of the two middle terms, taking into account that $A < 1$ and $B < 1$. We get $|\alpha \cdot B + \beta \cdot A| < |0,5 \cdot 10^{-n} \cdot 1| + 0,5 \cdot 10^{-n} \cdot 1| = 10^{-n}$.

This means that of the $2n$ digits of the product, only the first $n-1$ digits are guaranteed to be correct, the $n$th digit, by virtue of (2), already turns out to be componental (it may differ from the correct one by $\pm 1$). Formula (2) does not guarantee the correctness of numbers $(n+1)$ and further. Therefore, these numbers cannot be included in the final answer.

It follows that when multiplying approximate numbers in the school way - “ladder to the left” - we do half the work in vain. We ask, is it possible not to do this half of the work at all? It turns out that it is possible. To do this, you need to use a shortened method of multiplication - “ladder to the right”. Further, for the sake of clarity of presentation, we will limit ourselves to the example of multiplying approximate numbers $0,587 \times 0,736$.

As you know, multiplying decimals is similar to multiplying integers. Below are three ways to multiply

$$\times 0,587 \times 0,587 \times 0,587$$
$$\times 0,736 \times 0,736 \times 0,736$$
$$\times 4109 \times 4109 \times 4109$$
$$1761 + 1761 + 1761 + 1761$$
$$4109 \times 3522 \times 3522 \times 3522$$
$$0,4320 \times 0,4320 \times 0,4320$$

(a) - “ladder to the left” (school);

With method (6), unlike method (a), multiplication begins with the highest digits of the multiplicand and the multiplier; transfer units from the adjacent right digit of the multiplicand (less often from two adjacent ones) are taken into account immediately. After a little training, this method becomes no more difficult than method (a).

Method (c) is a shortened modification of method (6), in which partial products are not calculated to the end, but are immediately rounded. The rounding place provides one extra digit in the final answer, which is necessary for correct rounding of the last, componential, digit.

Ok, the final answer I found using all those methods of calculating it will be 0.432. To obtain it using method (c) it took half as much work and time as using methods (a) and (6). This approach was especially promoted by the outstanding Soviet mathematician, engineer and shipbuilder, Academician A. N. Krylov, whose book *) we recommend to our reader.

Successive approximations and control of calculations

The approximation of the source data (observation and change error) is not the only reason for the error in the result. Another source of error in the results is the approximate nature of the calculation process itself. The reasons for this phenomenon are

*) A. N. Krylov, Lectures on approximate calculations, M., FM, 1954.

⟦folio 14⟧

indicating either the fundamental need to check the exact calculation (for example, $\sqrt{2}$, sin $20^\circ$), or the inconvenience of using the exact formula of the result (for example, the exact simple fraction $1/7$, as a rule, is replaced by an approximate decimal fraction 0.143). The development of methods for calculating with a predetermined degree of accuracy is an important applied area of ​​classical mathematics calculations. The reader will get an idea of ​​these methods by looking at the last page of the Bradis table. There are formulas - the so-called infinite series - by which the values ​​of sine, tangent, logarithm and other tabular functions are calculated. Analysis of these formulas reveals the main methodological technique - replacing the calculation of the original function with the calculation of a polynomial, that is, another, simpler function, the values ​​of which, with a given degree of accuracy, are equal to the values ​​of the original function.

Another way to check a calculation with a given degree of accuracy is the method of successive approximations. Let's demonstrate it by calculating the square root of the number $A$.

As the zero approximation $\sqrt{A}$ we take an arbitrary positive number $x_0$.

Consider a segment on the number line (Fig. 2) bounded by points $x_0$ and $\frac{A}{x_0}$. Let's construct the second approximation $x_1$ as the arithmetic mean of $x_0$ and $\frac{A}{x_0}$:

$$x_1 = \frac{1}{2} \left( x_0 + \frac{A}{x_0} \right) :$$

By the property of the arithmetic mean we have $x_0 \leqslant x_1 \leqslant \frac{A}{x_0}$ and by the property of reciprocal quantities $\frac{A}{x_0} \geqslant \frac{A}{x_1} \geqslant x_0$. In other words, the segment

$$\left| \frac{A - x^2}{A + x^2} \right| < 1.$$

These segments contract to a single point $x$, which belongs to all segments. To calculate $x$, we substitute it into formula (3): $x = \frac{1}{2} \cdot \left( x + \frac{A}{x} \right), x = \frac{A}{x}, x = \sqrt{A}$.

The point $x = \sqrt{A}$ belongs to all segments, therefore $x_n$ tends to $x = \sqrt{A}$, that is, the method of successive approximations solves

⟦folio 15⟧

the assigned task. It remains to be noted that the calculation should stop after $x_{n+1}$ becomes equal to $x_n$ with a given number of decimal places.

The method of successive approximations has one great advantage: a random error in intermediate actions will not affect the magnitude of the result, but will only increase the time to obtain it.

In general, when performing calculations, the control should be given the utmost attention. Of course, the calculation process can be repeated again, but this will double the total running time. In particularly critical cases it is necessary to take this step, but other control methods are also possible, taking into account the specifics of a particular calculation. For example, if sin $x$ and cos $x$ are calculated from one argument $x$, then it is natural to then calculate $\sin^2 x + \cos^2 x$ and compare with unity.

Another example

Of particular interest is a technique that allows you to control each stage of the calculation. Let us demonstrate it using the example of solving a system of linear algebraic equations.

Let us be given a system of two equations with two unknowns:

$$\begin{align*}
5x + 2y &= 19, \\
3x + 7y &= 23.
\end{align*}$$

Let's write down its coefficients and free terms in the form of a table:

$$\begin{align*}
\frac{5}{3} &\frac{2}{7} \frac{19}{23} \\
\end{align*}$$

Let's replenish this table by controlling the sum of the elements of the corresponding row. We get a calculation table:

$$\begin{align*}
\frac{5}{3} &\frac{2}{7} \frac{19}{23} \frac{26}{33} \\
\end{align*}$$

In what follows, we will consider table (5) as an image of two systems with identical coefficients and different free terms: system (4) and system

$$\begin{align*}
\frac{5\tilde{x} + 2\tilde{y}}{3\tilde{x} + 7\tilde{y}} &= 26 \\
\frac{1}{3} \left| \frac{0,4}{7} \right| \frac{3,8}{23} \left| \frac{5,2}{33} \right| \\
\end{align*}$$

Solving systems (4) and (6) using the Gauss method, divide all elements of the first row by its first term. Let's get the table

$$\left| \frac{1}{3} \right| \frac{0,4}{7} \frac{3,8}{23} \left| \frac{5,2}{33} \right|$$

The control is that at any stage the sum of three numbers in any line must equal the fourth number; this is done here.

Next, multiply all the elements of the first row by the first term of the second row. We get

$$\left| \frac{3}{3} \right| \frac{1,2}{7} \left| \frac{11,4}{23} \right| \left| \frac{15,6}{33} \right|$$

Subtract term by term from the 2nd line the 1st:

$$\left| \frac{3}{0} \right| \frac{1,2}{5,8} \left| \frac{11,4}{11,6} \right| \left| \frac{15,6}{17,4} \right|$$

From the second line (8) we get

$$y = \frac{11,6}{5,8} = 2, \quad \tilde{y} = \frac{17,4}{5,8} = 3.$$

Finally, from the 1st row of the table (7) we find

$$x = 3,8 - 2 \cdot 0,4 = 3, \\
\tilde{x} = 5,2 - 3 \cdot 0,4 = 4.$$

Required solution: $x = 3, y = 2$; solution to system (6): $\tilde{x} = 4, \tilde{y} = 3$. There are equalities

$$\tilde{x} = x + 1, \quad \tilde{y} = y + 1,$$

This means the solution system is correct. Note that if in the final answer equalities (9) are not satisfied, then either when combining with a place, the rounding was too rough, or there was somewhere

⟦folio 16⟧

then a mistake was made. The presence of a control column at each stage of the calculation allows you to quickly find the location of an error or inaccuracy.

Equality (9) is the rationale for the control method. If we take system (6), the solutions of which are the solution of system (4), increased by one, $x = x + 1$, $y = y + 1$, then the free terms of system (6) will be equal to the sum of the coefficients of the rows of system (4). For example, for the first line of the system (4)

$$5(\tilde{x} - 1) + 2(\tilde{y} - 1) = 19,$$
$$5\tilde{x} - 5 + 2\tilde{y} - 2 = 19,$$
$$5\tilde{x} + 2\tilde{y} = 19 + 5 + 2 = 26.$$

This property can be easily verified in the general case. And since when solving we move to equivalent systems, then the sums of coefficients in them must be equal to the numbers in the control column.

Method errors

There is another group of reasons that lead to an error in the result. It's called a method error. It is checked, for example, in the case when, instead of an exact system of equations, a system of simpler equations that approximately describe the same process is considered. The reasons for such a replacement are very diverse: the lack of an exact equation system, the inability to prepare initial data for an exact system, the impossibility or greater complexity of accurately solving the existing exact system, and others. As an example, consider a problem from a physics textbook.

Plane plane horizontally at height $H$ with speed $v$. At what horizontal distance from the object must he drop the bomb to directly hit the object?

If we simplify the assumption, there is no resistance to the impact of the impact.

The required consideration $S$ is obtained from the formula $S = v \cdot t$ at $\frac{gt^2}{2} = H$, hence $S = v \cdot \sqrt{\frac{2H}{g}}$.

According to this assumption, the bomb's trajectory is parabolic (blue curve at Fig. 3).

But in reality, the impact resistance should be on a larger trajectory. It is called the “ballistic curve” (red curve at figure 3) and is built on the basis of experimental data and additional theoretical proposals. The ballistic curve significantly reduces the “method error”, but due to its experimental characteristics it slightly increases the “observation error” and “rounding error”.

Now we can draw some conclusions. The given examples and calculations show that the process of numerical calculation of any practical problem must be carefully planned.

The stages along this path are:

1) choosing a solution method with the error estimate it gives;
2) assessment of the accuracy of the source data;
3) selection of a scheme with assessment of the accuracy of rounding of intermediate values ​​and reasonable organization of control.

The further development of calculation methods is influenced by computer technology, especially electronic digital computers (EDC), which make it possible to perform calculations consisting of billions of arithmetic operations. This circumstance requires increased attention to the accumulation of errors and the selection of accounting schemes that are less “sensitive” to them.
