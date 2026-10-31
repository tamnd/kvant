---
id: 1989-12-kakoy-den-nedeli-6255f58a
issue: kvant_1989_12
year: 1989
number: "12"
title: What day of the week?
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 38
page_last: 41
page_labels: 36-39
tag: QTZ8
lang: en
source: kvant_digital
extraction: vision
content_sha256: cbc33279a07604ae54c7db608eb6d3b41507281cef9e9be95986691f081ce088
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/08_kakoy-den-nedeli-6255f58a.md
source_content_sha256: c4ee501e2d7cc6fd8dc6369a40ea0674568c032b922a25c49ca4397dfbcbc02e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

WHAT DAY
WEEKS?

The reader, of course, knows his birthday: year, month and day. What about the day of the week? Maybe it was Wednesday, or maybe Saturday or Monday? This article explains how to answer this question without resorting to the help of old calendars.

Let's finish the days

To do this, we’ll simply assign number 1 to some day, and we’ll number the further days in order: number 2, number 3, etc. Which day is taken as the first, it doesn’t matter, it’s empty, for example, it will be

January 1, 1st year.
Then January 2 of the 1st year will receive No. 2, January 3 of the 1st year - No. 3, etc., January 31 of the 1st year becomes No. 31, February 1 - day No. 32, March 1 - day No. 60 (in February of the 1st year there were 28 days, because the year is not a leap year). There were a total of 365 days in Year 1, so January 1 of Year 2 would be day #366, January 1 of Year 3 would be day #731, January 1 of Year 4 would be day #1096, and January 1 of Year 5 would be day #1462 (Year 4 contained 366 days). Thus, each day will receive its own number.

How to find out the day of the week, knowing the day number?

For example, what day of the week falls on the millionth day? We cannot yet answer this question. But if we knew the day of the week corresponding to a day with some number, then we could determine the day of the week corresponding to a day with any other number. Let's say

The article is based on materials sent to the editor by Doctor of Physical and Mathematical Sciences N. M. Veskin, and a chapter from the book by O. Ore “Invitation to Number Theory” (M.: Nauka, Library «Kvant», 1980).

⟦folio 37⟧

Zhem, day number 100,000. Between it and the millionth day, 1,000,000-100,000=900,000 days should pass. Let's divide 900,000 by 7 with the remainder: 900,000 = 128,571 7 + 3, that is, an integer number of weeks and three more days must pass between the days in question. The number of weeks is completely unimportant for us, only these three days matter. In particular, if the 100,000th day was Monday, then the 1,000,000th day is Thursday, if the 100,000th day is Tuesday, then the 1,000,000th day is Friday, etc.

Now the program of action is clear. First, we determine the number of each day for which the day of the week is known to us. This work can be done once and for all. Then we determine the number of the day we are interested in. By comparing the two received numbers, we determine the day of the week corresponding to the second.date - as explained above.

How to find the day number?

Let us be interested

k-th day of the m-th month of the N-th year.

As you know, there are leap and non-leap years. Non-leap years contain 365 days, non-leap years - 366 days. Non-leap years are, firstly, years whose numbers are not divisible by 4, and, secondly, years whose numbers are divisible by 100, but not divisible by 400. (Thus, the year 2000 will be a leap year, but the year 1900 was not a leap year, unlike, say, 1904. This clause distinguishes the “Gregorian calendar” or “new style”, from the “Julian calendar”, or “old style”. We will talk more about the old and new styles below.)

Let's return to the day in question. After day No. 1, i.e. January 1 of the 1st year, N-1 years, m-1 month and k-1 days have passed. Let the average N-1 years be N₁ leap years and N₂ non-leap years. Then we will think about what N₁ and N₂ are equal to, but for now we will write that these years contain 366N₁+365N₂ days. Number of days in 1st, ...,

We denote the 12th month by a₁, …, a₁₂. Thus, a₁=a₃=a₅=a₇=a₈=a₁₀=a₁₂=31, a₄=a₆=a₉=a₁₁=30, and a₂=29 or 28, depending on whether the Nth year is a leap year or a non-leap year. So our day number is

366N₁+365N₂+a₁+...+aₙ-1+k.

Now let's find N₁ and N₂. Let's imagine N-1 in the form 100P+R, where 0≤R≤99 (if N-1 is a four-digit number, as it was promised in practice, then P and R are binary numbers written as the first two and last two digits of the number N-1). Next, divide P and R by 4 with a remainder: P=4p+q, R=4r+s (0≤q≤3, 0≤s≤3). Our year was preceded by P full tables. Each has 99 years, the numbers of which are not divisible by 100, of which 24 are leap years and 75 are non-leap years. Of the P years with numbers divisible by 100, there were p leap years, and P−p=3p+q non-leap years. Finally, from the R of recent years there were r leap years and R−r=3r+s non-leap years. So,

N₁=24P+p+r=97p+24q+r,
N₂=75P+3p+q+3r+s=303p+
+76q+3r+s.

The final formula for our day number is:

366(97p+24q+r)+365(303p+76q+
+3r+s)+a₁+...+aₙ-1+k=
=146 097p+36 524q+1461r+365s+
+a₁+...+aₙ-1+k.

⟦folio 38⟧

For example, let the data we are interested in
March 1, 1989.
For this day $P=19, R=88, p=4, q=3, r=22, s=0, m=3, a_1=31, a_2=28, k=1$, and its number is 726,162.

We only need the remainder when divided by 7

The number of the day interests us only up to an accuracy of any number divisible by 7 (since the day interests us only up to an integer number of weeks). Therefore, it is appropriate to note that 146,097 = 20,871 7 is divisible by 7, so the first term in our sum can simply be discarded. Further, 36,524=5217·7+5, so together with the coefficient 36,524 we can take 5; in the same way, together 1461 and 365 we can take 5 and 1. Our huge sum will turn into
$$5(q+r)+s+a_1+\dots+a_{m-1}+k,$$
In addition, for $a_1,\dots,a_{12}$ the values ​​28, 29, 30, 31 can be painlessly replaced by the remainders of division by 7, i.e., the values ​​0, 1, 2, 3, respectively. Then for March 1, 1989 our number will be replaced by the number
$$5(3+22)+0+3+0+1=129,$$
which has the same remainder when divided by 7 as our day number (indeed, checking shows that for general numbers this remainder is 3). By the way, the most time-consuming part of the last calculation is finding the sum $a_1+\dots+a_{m-1}$, or rather the remainder when dividing this sum by 7. This remainder depends on $m$ and whether the year is a leap year. It makes sense to calculate it once and for all and record the result in Table 1.

For example, the sum corresponding to August of a leap year is 31+29+31+30+31+30+31, its remainder when divided by 7 will coincide with the remainder of the number 3+1+3+2+3+2+3=17, i.e. equal to 3; this is recorded in Table 1.

Now look at the calendar and make sure that March 1, 1989 is Wednesday. Above, we discovered that the remainder of dividing the number of this day by 7 is equal to 3. This means that if the remainder of dividing the number of the day by 7 is equal to 3, then the day is Wednesday. Matching, if the remainder is 4, 5, 6, 0, ..., then the day is Thursday, Friday, Saturday, Sunday, .... As you can see, we were a little lucky: the remainder from dividing the resulting number by 7 is simply equal to the number of the day of the week:

1 - Monday 4 - Thursday
2 - Tuesday 5 - Friday
3 — Wednesday 6 — Saturday
0 - Sunday.

(The luck is that the first day we took scientifically - January 1, 1st year - turned out to be a late day. If not for this, we would have had to make a blood amendment to the final formula.) Now we can write the final formula.

Formula
Let's consider

$$k-й день m-го месяца N-го года.$$
Let us denote by $R$ by two values ​​the number made up of the last two digits of the number $N-1$, and by $P$ the number made up of the remaining digits of the number $N-1$. Next, divide the numbers $P$ and $R$ with a remainder of 4: $P=4p+q, R=4r+s$. Then we find the number

$$D=5(q+r)+s+b+k,$$

Table 1

⟦folio 39⟧

where $b$ depends on the place and “leap year” of the $N$ year and is found from Table 1. The remainder when dividing the number $D$ by 7 is the number of the day of the week.

Example. The Great Patriotic War began on June 22, 1941. What day of the week was it? We calculate: $P=19=4\cdot 4+3$, $R=40=4\cdot 10+0$, $b=4$ (non-leap year),

$$D=5(3+10)+0+4+22=91,$$

The remainder when dividing the number $D$ by 7 is 0. So it was Sunday.

Old style and new style

The method for determining a leap year, outlined on p. 37, introduced in the 16th century; Before this, all years whose numbers were divisible by 4 were considered leap years. The need for correction was caused by the fact that the period of revolution of the Earth around the Sun is actually several minutes less than 365 $\frac{3}{4}$ days. Therefore, over the course of time, the New Year was approaching spring, and if not for the innovation, then by the year 12,000 it would have come at the time of snowdrop flowering. In Russia, the new style was introduced only in January 1918. Therefore, many historical events are usually called by the old style.

The difference between the old and new styles comes from the fact that the old style has dates from

Table 2

| Dates (new style, inclusive) | The number of days by which the new style is ahead of the old one |
| :--- | :--- |
| March 13, 1900 - March 13, 2100 | 13 |
| March 12, 1800 - March 12, 1900 | 12 |
| March 11, 1700 - March 11, 1800 | 11 |
| March 10, 1500 - March 10, 1700 | 10 |
| March 9, 1400 - March 9, 1500 | 9 |
