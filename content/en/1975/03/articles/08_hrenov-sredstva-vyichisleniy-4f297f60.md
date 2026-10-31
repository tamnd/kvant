---
id: 1975-3-hrenov-sredstva-vyichisleniy-4f297f60
issue: kvant_1975_3
year: 1975
number: "3"
title: Computing tools
authors:
  - Хренов Л. С.
rubric: osnovnye-stati
page_first: 32
page_last: 37
page_labels: 30, 31, 34, 35
tag: O0F1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4aa6d1765868f328081ca792dfed0bbaea25278fc703b5ddc63de5820aaf9b2a
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/08_hrenov-sredstva-vyichisleniy-4f297f60.md
source_content_sha256: c8010fc9b674918b650874aa5b9da7276731ba0506c2136fa89238aa65db1946
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

## COMPUTING TOOLS
L.S. Khrenov

⟦figure⟧
EKVM "Iskra-110"

The desire to mechanize calculations using various means arose in ancient times. In Rus', various means of computing were already used during the construction of the first stone churches in Novgorod, Kyiv and other cities.

Over the past decades, large qualitative changes have occurred in computing tools, which are difficult to compare even with such a stage as the appearance of logarithms.

Such a qualitative leap in the development of computer technology, and especially calculating machines, was caused by the development of technical progress in all sectors of the national economy, which required carrying out various calculations in huge volumes.

Now, depending on the accuracy of the source data and the purpose of the calculations, they use various means - nomograms, tables, instruments and calculating machines.

**Nomograms**

Nomograms representing graphical images of functional dependence are constructed for any one formula or one equation. Therefore, the effectiveness of their use in calculations depends on the mass scale of computational operations using this formula. Nomograms are used to quickly

⟦column⟧

To perform calculations that do not require great accuracy (2-3 significant figures), or to control more accurate calculations. The main element of each nomogram is a functional scale, graphically depicting a certain function $y = f(x)$ on a line*).

**Tables**

A table is a collection of numerical values ​​of a given function corresponding to certain, sequentially located argument values.

In Babylon as early as 2,000 BC. e. tables were created containing the values ​​of $n^2$, $n^3$, $n^2 + n^3$, $1/n$ and other functions. Increasing requirements for calculation accuracy led to the creation of a large number of different tables in the 15th century.

The rapid development of astronomy in the 16th century placed increased demands on the accuracy of calculations, which led to the invention of logarithms. The logarithms we use now were proposed independently by the Scotsman J. Napier (1550-1617) and the Swiss I. Burgi (1552-1632).

In 1703, the “Table of logarithms for numbers from 1 to 1000 and sines, tangents, secants for the teaching of wise-loving meticulous people” was published in Russia.

The further development of science and technology necessitated the development and creation, especially from the middle of the 17th century, of tables containing the values ​​of a wide variety of

---
*) For example, see the article by Yu. V. Matiyasevich “First acquaintance with nomograms”, «Kvant», 1971, No. 5.

⟦folio 31⟧

personal functions. And in the first half of our century, several times more tables of all kinds were published than in all previous centuries.

In the practice of calculations, mathematical tables are widely used that represent functions mainly of one argument: $y = f(x)$, with a step for the argument allowing linear interpolation.

Of the tables containing the values ​​of elementary functions, the world-famous Barlow tables containing the values ​​of the functions $n^2, n^3, \sqrt{n}; \sqrt{10n}, \sqrt[3]{n}$, and $1/n$ for arguments $n$ from 1 to 15,000 in increments of one unit are widely used.

Of the logarithmic ones, the most commonly used are tables of decimal logarithms of numbers, their sums and differences, as well as logarithms of trigonometric functions; they are composed with a different number of decimal places in the mantissa, and the most common are 4-8.

When choosing logarithm tables for calculating tables, it is necessary to take into account the number of correct significant digits of logarithmic numbers, which usually represent approximate rather than exact values. Approximately, we can assume that the absolute error of a decimal logarithm is equal to half the relative error of the logarithm number, that is, one should use tables of decimal logarithms with the same number of decimal places in their mantissas as the number of correct significant digits the logarithm number has, or one more.

The widespread use of various calculating machines led to the replacement of logarithmic calculations with non-logarithmic ones. In this regard, tables containing natural values ​​of functions acquire special significance.

Unlike tables of logarithms, the number of decimal places after the decimal point in tables of natural values

⟦column⟧

of, say, trigonometric functions, does not fully characterize their accuracy. Such tables contain values ​​of trigonometric functions whose absolute error does not exceed $0,5 \times 10^{-n}$, where $n$ is the number of decimal places. Their relative error will change dramatically. The use of such tables leads to a loss of accuracy of results when calculating with functions of small angles.

So, for example, if in a right triangle $ABC$ we assume that its legs are respectively $AB = 0,45$ $\mathit{м}$, and $BC = 103,13$ $\mathit{м}$, then with these data, using five-valued tables of natural values ​​of trigonometric functions, we obtain

$$\mathrm{tg}\, \sphericalangle ACB = \frac{AB}{BC}; \quad \sphericalangle ACB = \alpha = 0°15',$$

and the hypotenuse

$$AC = \frac{BC}{\cos\alpha} = \frac{103,13}{0,99999} \approx 103,13\ \mathit{м};$$

on the other side,

$$AC = \frac{AB}{\sin\alpha} = \frac{0,45}{0,00436} \approx 103,21\ \mathit{м},$$

that is, the difference in the value of the side $AC$ by $0,08$ $\mathit{м}$ is obtained.

If you use tables with five significant figures, then the relative error will be within

$$0,5 \times 10^{-5} \leqslant \Delta\delta \leqslant 0,5 \times 10^{-4};$$

in them $\cos 0°15' = 0,99999$, and $\sin 0°15' = 0,0043633$, and

$$AC = \frac{0,45}{0,0043633} \approx 103,13\ \mathit{м},$$

that is, there will be no error in calculating side $A$.

When choosing to calculate tables of natural values ​​of trigonometric functions, you should *give preference to tables in which the values ​​of all six functions are given with the same number of significant figures* rather than with the same number of decimal places.

The first trigonometric tables that have come down to us were those compiled by C. Ptolemy (2nd century). They were placed in his famous work “Almogest” - the greatest monument to astronomy. The basis of modern tables of trigonometric functions are the fundamental tables compiled by Reti-

⟦folio 34⟧

work

$$y = \Delta y_1 \Delta y_2 \dots \Delta y_n,$$

here $y_i = e^{\Delta x_i}$.

The scale $DF$ on the body and the analogous scale $CF$ on the engine are ordinary logarithmic scales, but each is only scaled by values ​​$x$. Therefore, the number $x$ on the scale $C$ corresponds to the number $x$ on the scale $CF$.

The second gray scale $CI$ on the slider, like the scale $R$ on a normal slide rule, is a “reverse” scale, designed to calculate the values ​​$1/x$, that is, the reciprocal values ​​of the numbers $x$ plotted on the scale $C$.

The scale $CF$ is used to calculate the values ​​of quantity $1/x$. For example, to calculate $q=1/πx$ with $x=2,6$ do this. On the reverse side of the ruler, the initial strokes of the engine are combined with the initial strokes on the body, and in this position of the engine, the slider is set to look at the stroke corresponding to the given number $2,6$ on the scale $D$ and on the scale $CF$, using the gaze, the number $0,1224$ is read, which is the exclusive result, that is, $q=0,1224$.

On the front side of the slider there are (in addition to the main indicator of the visor) two short colored strokes. They are drawn so that the distance between the main sight and each of the outer rulers corresponds to the ratio $\pi/4 \approx 0,785$ on the scale $A$. Using these shadings you can quickly calculate, for example, the area of ​​a circle.

So, to calculate the area of ​​a circle $S$ with a diameter of $d=5$ m, the main line (any of the three lines on the slider can be used) is combined with line 5 on the main scale $D$ on the front side of the ruler body, and using the short left (red) line the value of the area $S=19,63 \ m^2$ is read on the square scale $A$.

Calculating machines

Several hundred types of different machines have now been created. However, all their diversity can be divided into two groups: machines of continuous action and machines of discrete action, but otherwise called “counting machines”. The first category of machines is characterized by a relatively limited accuracy of the results obtained; in them, mathematical quantities (input, intermediate and output) are depicted in the form of specific physical quantities, the quantitative characteristics of which correspond to the numbers depicted (for example, the length of a segment is depicted by tension, the area by displacement, etc.). The simplest example of a continuous computing device is a planometer, with the help of which the areas of figures are calculated on drawings *).

In discrete action machines, which in principle allow one to obtain a result with unlimited accuracy, solving a problem is reduced to the sequential execution of individual arithmetic operations. In such machines, all mathematical quantities (initial, intermediate and final) are depicted as sets of numbers in the positional number system. This is the basis for calling such devices discrete action machines. They come with manual and automatic installation of initial data.

Machines with manual installation of initial data are divided into summing machines, intended for adding and subtracting numbers, and small computers; the latter are divided into mechanical (lever "Felix") and keyboard "VK-1" arithmetries), electronic (automatic machine "BMM-2") and automatic machine "BMP-2"), solutions ("Vilhic", "Vyatka") and electronic. Of these, the most modern are electronic classical computers (ECVMs), which make it possible to automatically perform not only all arithmetic operations, but

*) See the article by L. E. Sadovsky, A. L. Sadovsky “How to measure area”, «Kvant», 1973, No. 10.

⟦folio 35⟧

and extract roots, calculate natural values ​​of trigonometric functions and perform a number of other actions.

The domestic industry mass-produces various computers: “Iskra”, “Electronics”, “Gelati”, “Rasa”, ten-key electronic machine “EDVM”.

"Iskra-110" allows you to perform (taking into account the sign and comma) four arithmetic operations, as well as calculations like $a^n + bp^n$ and others. On it, all operations are performed with 8-bit numbers; The position of the decimal point in the number is set by corresponding switching. On the Electronics-DD computer you can perform not only four arithmetic operations, but also calculations with percentages, extracting square roots and performing various combined calculations. To obtain calculation results with a certain number of correct decimal places, use the decimal position keys “0”, “2”, “4” and “6” located on the keyboard panel to the left of the number keys. And the presence of a memory block in this machine allows you to perform complex

⟦column⟧

calculations and semi-automatically (without recording intermediate results and re-typing numbers) extract square roots using an iterative formula

$$y_n = \left(\frac{x}{y_{n-1}} + y_{n-1}\right)/2,$$

where $x$ is the radical expression, $y_{n-1}$ is the approximation of the root. In this case, iterations in the calculation end when successive approximations are obtained that coincide in the required number of digits.

figure 5 shows an electronic ten-key adding machine “EDVM”. It can automatically perform various calculations with 16-bit numbers, as well as semi-automatically extract roots of the $n$th power, raise numbers to the $n$th power, and calculate the natural values ​​of tangent and cotangent with 10 correct signs.

Recently, the electronic computer “Electronics-70” has been produced, which also allows the calculation of decimal and natural logarithms, exponential functions, trigonometric and inverse trigonometric functions.

---

## Tips for beginning tutors

(see p. 24)

**How ​​to work with a client**

The most important task is the first one. You need to immediately win the unconditional trust of the applicant. To do this, stock up on some monograph designed specifically for graduate students. Pick out a question in it that scientists have been struggling with unsuccessfully for the past 15 years. As a result, you will clearly show the applicant that without your

⟦figure⟧

there is nothing he can count on for help.

Recently, there has been a clear tendency among parents to look for tutors from the university that their child intends to attend.

⟦column⟧

make happy. Meet them halfway. Accidentally dropping the name of the rector will create the desired effect. You can emphasize a closer relationship with the rector by noting that he is a very nice and intelligent person.

The technique for further training is extremely simple. The only task is to compact the groups as much as possible. Unite 10, 15 students, there are no limits. Looking ahead, we note that this method also has a certain financial incentive. If, say, you simultaneously teach not one, but thirteen students, then it is easy to calculate that your income for each hour increases 13 times!

*(Continued on page 43)*

3*

35
