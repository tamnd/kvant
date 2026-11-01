---
id: 1984-4-rozhdestvenskiy-umeete-li-vyi-schitat-a3eadc3e
issue: kvant_1984_4
year: 1984
number: "4"
title: Can you count?
authors:
  - Рождественский В. В.
rubric: osnovnye-stati
page_first: 13
page_last: 15
page_labels: 11-13
tag: HOZE
lang: en
source: kvant_digital
extraction: vision
content_sha256: d46c84273afab49fc3df1f6a095aa40d60a8e94171f1af5ea717b87da4184003
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/04_rozhdestvenskiy-umeete-li-vyi-schitat-a3eadc3e.md
source_content_sha256: 74653efd0c2b5cac79a83b502aa9922cbbf8861c1663823cbea369d8936c1429
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

Can you count?

V. V. ROZHDESTVENSKY

Recent decades have been characterized by rapid development and proliferation of computing technology. Electronic computers, desktop, pocket and other calculating devices can significantly reduce the time of all kinds of calculations. And sometimes you can hear from schoolchildren that “being able to count” is not necessary at all now. But paradoxically, technology provides the most effective assistance to those who can calculate correctly.

We will try to show the reader the difficulties that arise in practical

Puzzling Examples

Example 1. When calculating the expression $x=1/3\cdot 3/5\cdot 5/7\cdot 7/8\cdot 8$ on a real computer with an accuracy of two decimal places, together with the expected unit we get $x=0,88$. If $1/8\cdot 8/7 \times 7/5\cdot 5/3\cdot 3$ is calculated, the result is 0.90.

Example 2. When adding the numbers $1+1/2+1/3+1/4+\ldots+1/250\ 000$ with fifth decimal places on a computer from left to right, the result is 12.88777, and from right to left the result is 12.95821; we see that the difference in answers is greater than each of the majority terms.

Example 3: The approximate value of $\sqrt{290}$ is 17.029 (error less than 0.0004). When calculating the fraction $1/(\sqrt{290}-17)$ with the third decimal place, the result is 34.483. However, if the fraction is converted to the form $\sqrt{290}+17$, then the result of the addition will be 34.029, with an error of less than 0.0004. Therefore, the answer is 34,483 cities, which is rougher.

⟦folio 12⟧

Example 4. System solution
$$\begin{cases} x+5y=17, \\ 1,5x+7,501y=25,503 \end{cases}$$

is a pair of numbers (2; 3). If you change the number 25.503 by just 0.003 -
$$\begin{cases} x+5y=17, \\ 1,5x+7,501y=25,5, \end{cases}$$

then the solution will be the pair (17; 0). If in the original system the number 7.501 is replaced by 7.499 -
$$\begin{cases} x+5y=17, \\ 1,5x+7,499y=25,503, \end{cases}$$

then the solution will be (32; - 3).

Examples like these can confuse a beginner in computing. To correctly navigate positive situations, you need to know:
1) what are the errors and where do they come from?
2) how to characterize the error quantity,
3) how to organize calculations correctly.

Error classification

Errors can be divided into three types*).

1) Errors contained in the source information. The initial data in any problem are usually either frequently occurring constructs or values ​​obtained as a result of measurement. But any measuring device has a certain resolution. For example, on commercial scales it is impossible to detect a difference of 1 g, so if you pay for 100 g of oil, is there any harm in believing that you will get exactly 100 g, and not 101 g or 99 g? Measurement errors can also arise due to incorrect readings of the device or as a result of rough viewing.

Excluding the last two sources of errors caused by subjective principles, it remains, however, to accept the fact that errors in the original data are inevitable and due to the accuracy of the measuring instrument. Finally, manipulation of the original data does not guarantee that the result is more accurate than the data. A statement like the following: “the area drawn on paper

*) The various sources of errors that arose during the processing of experimental data, and what happens if they are avoided, are also described in the article by A. N. Zaidel “Deception or Delusion?” («Kvant», 1983, No. 5, p. 24).

of a circle whose radius is changed by a ruler is 3206.9569 mm²,” are at least naive.

2) Rounding errors. These are technology errors with the specifics of an approximate parity. The fact is that no computing “means”, be it a computer or a person, can perform arithmetic operations with infinite sequences. Thus, all data and intermediate results must be recorded using a limited set of numbers and are therefore generally imprecise.

3) Constraint errors. A lot of calculations are described as an endless or astronomically large sequence of refinement of the result. Naturally, one comes to process such a process at some point and be content with the last approximation obtained. An example is the process of calculating $\sqrt{a}$ using the method of successive approximations:

$$x_1 = (a+1)/2, \dots, x_{n+1} = (a/x_n + x_n)/2, \dots$$

So we see that mistakes are inevitable. This means that it is necessary to reduce their number to evaluate in order to obtain results with the required accuracy.

Propagation of errors

Since computing processes ultimately come down to performing four arithmetic operations, let's see what happens with errors when performing these actions.

For simplicity, we will assume that all the quantities under consideration (which can be initial data, intermediate or final results) are positive. Their exact values ​​will be denoted by $x, y, \dots$, and the corresponding approximate values ​​will be denoted by $x, y, \dots$.

Characteristics of the approximation accuracy are the absolute error (or error) $\Delta_x = x - x_i$ and the relative error $\omega_x = \Delta_x/x$. Table 1 contains formulas expressing the dependence of the absolute and relative errors of the results of arithmetic operations on data errors (check these formulas yourself!).

For practical changes in absolute value and calculations, the exact values ​​of absolute value and

⟦folio 13⟧

Absolute mistake
Relative error

$\Delta_{x+y} = \Delta_x + \Delta_y$
$\Delta_{x-y} = \Delta_x - \Delta_y$
$\Delta_{x\cdot y} = x\Delta_y + y\Delta_x + \Delta_x\Delta_y$
$\Delta_{x/y} = \left( \frac{\Delta x}{y} - \frac{x}{y} \right)\frac{\Delta y}{y}$
: $\left( 1 + \frac{\Delta y}{y} \right)$

relative errors are unknown (because the exact values ​​of the quantities under consideration are unknown). However, knowing the accuracy of the measuring instruments, the rules by which intermediate results were rounded, etc., it is usually possible to guarantee that the absolute or relative error does not exceed the absolute value of non-octoral values ​​- the limit of these errors. If the error limits for the values $x$ and $y$ are given, then from the formulas in Table 1 it is easy to obtain the error limits for $x+y$, $x-y$, $xy$ and $x/y$ (see Table 2, which assumes that $|\Delta_x| \leq \Delta_1$, $|\Delta_y| \leq \Delta_2$, $|\omega_x| \leq \omega_1$, $|\omega_y| \leq \omega_2$).

Table 2
Absolute Error Limit
Relative error limit

$|\Delta_{x+y}| \leq \Delta_1 + \Delta_2$
$|\Delta_{x-y}| \leq \Delta_1 + \Delta_2$
$|\Delta_{x\cdot y}| \leq x\Delta_2 + y\Delta_1 + \Delta_1\Delta_2$
$|\Delta_{x/y}| \leq \frac{y\Delta_1 + x\Delta_2}{y^2}$
: $\left( 1 + \frac{\Delta y}{y} \right)$

In this table, the formula for the absolute error of the quotient $\Delta_{x/y}$ stands out: it includes the error itself $\Delta_y$, and its boundary $\Delta_2$, therefore $|\Delta_{x/y}|$ can turn out to be large at $\Delta_y < 0$, even if $\Delta_1$ and $\Delta_2$ are small.

Analysis of examples

Let’s now try to understand what explains the “oddities” that we encountered in the examples given at the beginning of the article.

Example 1. According to the rules of general arithmetic in the product of fractions $\frac{1}{3} \cdot \frac{3}{5} \cdot \frac{5}{7} \cdot \frac{7}{8} \cdot \frac{8}{1}$, you can rearrange the numerators and denominators as you wish without changing the result. From our example it is clear that in the arithmetic of approximate calculations this is no longer true. To understand how the discrepancy in results arises, let's take a simple example - we calculate the expression $(1 \cdot 3)/3$ in two ways (accurate to two decimal places). We have
$$1,0 \times 3,0 = 3,0, \quad 3,0 \times 3,0 = 1,0,$$
but, on the other hand,
$$1,0/3,0 = 0,33, \quad 0,33 \times 3,0 = 0,99.$$
If there are a lot of arithmetic operations, then the difference in answers can be even greater.

Example 2 shows that the result of approximate addition of several numbers can depend on the order in which it occurs. Let's look at a more graphic example. Let us calculate the sum
$$100 + 0,1 + 0,1 + \dots + 0,1,$$
2000 times
rounding all results to the nearest three digits. (Recall that values ​​are all the digits in the notation of a number, starting with the first non-zero one from the left; say, in the numbers 0.017 and 1.7 there are two digits each, in the number 170 there are three.) If we add from left to right, we first get $100 + 0,1 = 100,1$ and after rounding again 100; This result, very nonlinear, will not change in the future. When adding from right to left, we get sequential: $0,1 + 0,1 = 0,2, \quad 0,2 + 0,1 = 0,3, \quad \dots \quad 99,9 + 0,1 = 100$. The next thousand terms will not change the result, but with the last addition we get $100 + 100 = 200$. This is already the best, but still far from the exact answer of 300, which can be obtained by adding up the number of numbers 0.1, therefore also the number 0.1 and then the three resulting hundreds. This example makes the following rule of thumb fairly clear:

the summation of a large number of terms must be organized in such a way that
