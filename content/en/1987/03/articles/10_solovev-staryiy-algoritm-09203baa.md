---
id: 1987-3-solovev-staryiy-algoritm-09203baa
issue: kvant_1987_3
year: 1987
number: "3"
title: Old algorithm
authors:
  - Соловьёв Ю. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 39
page_labels: 34-37
tag: EURS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7905c16490357fc23e6775311b70bd79bb84be1f9113724e227fdf4eb360236c
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/10_solovev-staryiy-algoritm-09203baa.md
source_content_sha256: 16017a28ac0436ffeca98ae09957bbcf5bcb2095f3a1dfb7e27964ba06dfd0f3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

The other day my son Sasha (he is a seventh grader) came up to me:
— Buy ​​me a calculator like Vova’s!
- First of all, you have a calculator, but what did you turn it into? Now he shows some ceroglyphs together! Secondly, the student must be able to count without a calculator. Thirdly, so be it, I’ll take the calculator to get repaired this week.
“You don’t have to carry a calculator to the workshop,” Sasha answered me, “I can add, multiply and divide skillfully.” I need to solve a quadratic equation, and the root is what number: 16229! In the textbook, the largest number in the table is 10,000. But Vova’s calculator calculates square roots.
- Do you want me to teach you how to calculate roots without a calculator?
- Is it difficult?
- Not much more difficult than division. Listen here.

Various methods of extracting square roots “by hand” have existed since ancient times. I will tell you about one such method, which was created back in the 15th century and for many years served both schoolchildren and scientists.

To free up this method, it is enough to look at a few examples.

First, let's consider the case when the root is extracted entirely, that is, when the number is a perfect square. Let's find, for example, the root of the number 294,849.

The volume of the digits included in this number is divided from right to left into groups of two digits (Fig. 1, a). The leftmost group will be called the first, the next one - the second, etc. The total number of groups formed determines the number of digits of the exclusive root.

The first digit is found as the integer value of the root from the first group with the disadvantage. In our case, this is the number 5. We write it down as the answer, then square it, subtract it from the first group and the method to the result of subtracting the next group. (If the result of the subtraction is zero, then we simply remove the next group.) In the example under consideration, the number 448 (Fig. 1, b) will be obtained.

Let's move on to defining the second number. To do this, to the left of the resulting number 448, draw a vertical line and write behind it the place of tens, the doubled first digit: $2 \times 5 = 10$ (Fig. 1, s).

In place of units we put a sum greater than digit $a$, for which the difference $448 - 10a \cdot a$ is non-negative, i.e. positive or equal to zero. It is clear that in our case this is digit 4. We enter this digit in the answer (Fig. 1, ​​e).

Multiply 104 by 4 and write the result to the right of the vertical line. We calculate the difference $448 - 416 = 32$ and the method for it is as follows. In place of units we put a sum greater than digit $b$, for which the difference $3249 - 108b \cdot b$ is non-negative. By selection we are convinced that for $b = 3$ this difference is equal to

⟦folio 35⟧

zero. We enter $b=3$ in the answer (Fig. 1, e).

We multiply 1083 by 3, write the result to the right of the vertical line and subtract it from 3249 (Fig. 1, g).

Since the difference is zero, the process of calculating the root is completed.

Now, looking at figure 2 and 3, try to repeat all the steps required to calculate the square roots $\sqrt{212521}$ and $\sqrt{165649}$ on your own.

Until cxx we looked at numbers with four digits. If the total number of digits is odd, then the first group on the left will consist of only one digit (Fig. 4, 5).

Well, what to do if the number is not a perfect square? In this case, the algorithm does not change; you just need to prepare the number correctly. So, let $N$ be some number (not necessarily an integer) represented by a decimal fraction, and we want to calculate the root of it with precision

⟦folio 36⟧

to $\frac{1}{10^{10}}$, i.e. we want to find the numbers in the decimal representation of the original root up to the $m$ decimal place inclusive. Then we will build as follows. The digits included in the integer part of the number $N$ are divided into groups of two digits in each from right to left, and the digits forming the fractional part are divided into the same groups, but from left to right. If the total number of digits in the integer part is odd, then the first group on the left will consist of one digit, but if the number of digits in the fractional part is odd, then we assign a zero to the last digit on the left. When the number of groups in the fractional part is greater than $m$, we discard the extra groups on the right; when it is less than $m$, we make up the missing groups from zero. Now everyone is ready to use our algorithm. Figures 6 and 7 show the calculation

⟦folio 37⟧

square roots $\sqrt{2}$ and $\sqrt{12,5}$ up to $\frac{1}{1000}$.

To test whether you have mastered this algorithm, continue with the following exercises: Calculate, to the nearest $\frac{1}{1000}$, the square roots of $\sqrt{18769}, \sqrt{24336}, \sqrt{35721}, \sqrt{232324}, \sqrt{243049}, \sqrt{104,2441}, \sqrt{1867,1041}, \sqrt{7}, \sqrt{10}$.

We will not deal with the justification of the described algorithm. We only note that obtaining each new digit is associated with an increasing amount of calculation, so it is reasonable to use the algorithm when the required accuracy does not exceed three to four significant digits (which, as a rule, is sufficient for practical calculations).

The accuracy of calculations using the specified algorithm can be increased if you use the following statement:

If, after calculating the $n$ significant digits of the root, the remainder of the calcification is divided by twice the found value of the root, then the quotient gives $n-1$ of the next digits of the root.

Let's prove this statement. Let us first assume that the number $a$ from which the root is taken has an integer part of $n$ groups. Let $n$ of the first digits of the root forming the number $c$ be found. Then $\sqrt{a}=c+x$, where $x$ is the fractional part of the root that needs to be found. Hence,

$$a=c^2+2cx+x^2,$$
$$\frac{a-c^2}{2c}=x+\frac{x^2}{2c}.$$

The difference $a-c^2$ is the remainder that is obtained after finding the $n$ digits of the root. The fraction $\frac{a-c^2}{2c}$ represents the very quotient referred to in the statement.

That's why

$$x=\frac{a-c^2}{2c}-\frac{x^2}{2c}.$$

Counting $x \approx \frac{a-c^2}{2c}$, we allow an error equal to $\frac{x^2}{2c}$. Since $x<1$, $a \geq 10^{n-1}$, we have what was required. If the comma separating the integer and fractional parts in the number $a$ is not where we expected it to be, then it can always be transferred to the proper place by multiplying or dividing the number $a$ by some power $10$ with an even exponent, and then dividing or multiplying the found root by the power $10$ with an exponent half as large.

Let's look at an example. Let's calculate $\sqrt{2}$ with seven digit values, that is, with six digits after the decimal point. Previously we calculated $\sqrt{2}$ with decimal places (Fig. 6). Dividing the remainder by twice the root gives the following three (Fig.8).

Of course, in our time, when almost every first-grader carries a microcalculator in his briefcase, it is not easy to surprise a schoolchild with a manual method of extracting the square root. But we still hope. The famous American mathematician Academician Graham recalled that he first felt a strong interest in mathematics in elementary school, after seeing the very algorithm for knowing square roots that we have just talked about. He wondered if it was possible to do something similar for cube roots and higher degree roots. He found a similar solution, and since then mathematics has always entered his life.

List of readers who sent correct solutions

(Start p. on p. 29)

09, 11; S. Tyurin (p. Pravdinsk, Gorky region) 09, 11; A. Usinsky (village Ptichya, Rivne region) 09; D. Feldman (Chernogolovka village, Moscow region) 03, 05; D. Filatev (Alma-Ata) 99; G. Finkelshtein (Chernogolovka village, Moscow region) 03–05, 07–12; F. Fot (Tomsk) 03, 05; A. Furs (p/o Drichin, Minsk region) 09, 11; M. Kharaba (Nadrechnoye village, Ternovol region) 04; P. Khil (Ovidno-pol settlement, Odessa region) 03; D. Khodorovskaya (Kyiv) 04; I. Chaika (Kuznetsov village, Rivne region) 99, 05, 07, 08, 11; O. Chepikov (Mogilev) 03, 09, 11; I. Shekhtman (Kyiv) 04, 05, 09; A. Shshikin (Novy Urengoy) 09; A. Shulyak (Molodetskoye village, Cherkasy region) 11; N. Yudina (Maina settlement, Ulyanovsk region) 11; V. Yaylyan (Shostka) 03; I. Yakovleva (Kyiv) 04; Yu. Yarovoy (Kyiv) 99, 09.
