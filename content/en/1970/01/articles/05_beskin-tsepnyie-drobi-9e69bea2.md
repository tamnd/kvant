---
id: 1970-1-beskin-tsepnyie-drobi-9e69bea2
issue: kvant_1970_1
year: 1970
number: "1"
title: Continued fractions
authors:
  - Бескин Н. М.
rubric: osnovnye-stati
page_first: 18
page_last: 27
page_labels: 16-25
tag: M5Y4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 79ded8d487cb5945216430061f39caa8830bf8f024ee3a37403328888dc6d3e2
prompt_sha256: draft-1
translated_from: content/ru/1970/01/articles/05_beskin-tsepnyie-drobi-9e69bea2.md
source_content_sha256: 5133a60a2035394cfe48fbf2ff2d9f06902231372fdeaa00257398a4bb66d833
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

CHAIN ​​FIREWOOD

N. M. BESKIN

Even in ancient times, scientists were interested in
as for any non-integer number
find a good approximation of it
fractions with small values.
The article talks about the simplest
way to find such fractions.

$$\pi = \sqrt{2}$$

1. TWO RIDDLES

1. The riddle of Archimedes.
Many people believe that to find something extraordinary, you have to go very far, preferably into space. In everyday life around us, everything is well known, and there is nothing interesting.

What a misconception! We are surrounded by mysterious phenomena, but we don’t think about them because they are natural. Here we will talk about two mysterious facts from the history of mathematics.

All schoolchildren in the world “take” a course in geometry that Archimedes found an approximation for the number π

reading $$\frac{22}{7}$$). They are so accustomed to this fact that they do not suspect what secret is hidden in it. Meanwhile, one only has to ask a natural question: why did Archimedes prefer rural areas? Why not eighths? Trying to answer this question will take us into a new area of ​​arithmetic.

Let us clarify the problem “to give an approximation of the expression of the real number α in the form of a fraction with the value q.”
This means: of all fractions with value q, find the one closest to the number α. If all fractions with value q are plotted on the number axis, then the number α falls between two such neighboring fractions (the case when α coincides with one of them is uninteresting)

$$\frac{p-1}{q} < \alpha < \frac{p}{q}.$$

From these two fractions, choose the one that is close to α. For example, on Fig. 1 the point α is close to the right end of the segment $$\left[ \frac{p-1}{q}; \frac{p}{q} \right],$$ and therefore

*) In fact, Archimedes formulated this result slightly differently in his essay “On the Measurement of a Circle.” He indicated the limits for l:

$$3 \frac{10}{71} < \pi < 3 \frac{1}{7}.$$

The meaning $$3 \frac{1}{7},$$ has come into general use as a simpler value, although l is close to $$3 \frac{10}{71}.$$

⟦folio 17⟧

Should be accepted
$$\alpha \approx \frac{p}{q}.$$
If $\alpha$ is the middle of the segment $\left[ \frac{p-1}{q}, \frac{p}{q} \right]$, then to determine the conditions of the condition, choose its left end.

The process of replacing the number $\alpha$ with its approximate value is called approximation (approximation).

From the above it is clear that to approximate the number $\alpha$ you can use fractions with any value. The choice of meaning depends on our desire. For the sake of technical convenience, he almost always uses decimal fractions. However, at the time of finding decimal fractions, fractions had not yet been invented, and Archimedes could take out any fractions. He chose himself. Why? Patience, we'll figure it out soon.

When approximating the real number $\alpha$ by the fraction $\frac{p}{q}$ the need arises
$$\Delta = \alpha - \frac{p}{q}$$

(remember: need is almost the value minus the approximate value). If the approximation of the value is taken with a deficiency, then the need is positive, and if with an excess, then the need is negative.

An absolute great need is called an absolute need.

It is clear that with the chosen method of approximation, absolute consumption

ity cannot exceed $\frac{1}{2q}$ (see Fig. 1)

$$|\Lambda| \leqslant \frac{1}{2q}.$$

The number $\frac{1}{2q}$ is the upper limit of absolute need. With another approximation method, the upper limit may be different. For example, if we agreed to always take an approximation with a disadvantage, then it would be equal to $\frac{1}{q}$.

The absolute demand reaches the upper limit in the (most unfavorable) case when $\alpha$ is the middle of demand
$$\left[ \frac{p-1}{q}, \frac{p}{q} \right].$$

It is clear that the approximation is beneficial if it gives high power at a small value of $q$. In order to realize profitability, it is necessary to compare two values: 1) the actual absolute need, 2) the upper limit of the absolute need:

$$\frac{\text{абсолютная потребность}}{\text{верхняя граница абс. погр.}} = \left| \alpha - \frac{p}{q} \right| : \frac{1}{2q} = 2 \cdot |q\alpha - p|.$$

It is customary to consider the positive of this quantity. Let's take her by the given need
$$h = |q\alpha - p|$$

and remember: the reduced need $h$ is the ratio of the actual absolute need to the maximum possible.

Obviously,
$$0 < h \leqslant \frac{1}{2}$$

The smaller $h$, the more favorable the approximation. If $h$ is close to zero, then the number $\alpha$ is located close to one of the ends of the segment
$$\left[ \frac{p-1}{q}, \frac{p}{q} \right].$$ The more $h$ is to $\frac{1}{2}$, the closer $\alpha$ is to the middle of the segment.

⟦folio 18⟧

Size

$$\lambda = \frac{1}{2h} = \frac{1}{2 \cdot |q\alpha - p|}$$

Let's call it the profitability coefficient. Its meaning is very simple: the profitability coefficient shows how many times the actual absolute error is less than the maximum possible one. The larger $\lambda$, the more favorable the approximation. Obviously,

$$1 \leqslant \lambda < \infty,$$

$$\lambda h = \frac{1}{2}.$$

Don't assume that smaller fractions always give a better approximation! It can be concluded that when plotting eighths on the number axis, the number $\alpha$ occupies a less advantageous position than when plotting sevenths. Let's do an experiment with the number $\pi$, approximating it with different fractions - from first to tenths. Calculations are omitted; the reader can reproduce them himself.

Fig. 2.

the error did not exceed 0.0013, which shares would you choose? We would write down the conditions $\frac{1}{2q} \leqslant 0,0013$, from which $q \geqslant 385$, and Archimedes would achieve the same accuracy by taking the lowest denominator.

Now are you convinced, reader, that Archimedes did not choose sevenths by chance?

Many centuries later, the Dutch mathematician Adrian Mecius gave an approximation

$$\pi \approx \frac{355}{113}.$$

The Mecia number has the same amazing properties as the Archimedes number: the denominator is 113 goraed

*) The calculation gives $\lambda = \frac{1}{2 \cdot 0,0089} = 56,2$. To get the digits of tens correctly, you need to take $h$ with five digits after the decimal point

⟦folio 19⟧

more profitable than other nearby denominators. We recommend the reader to study the Meshchi number in the same way as the Archimedes number was studied above. For example, what is the selectivity coefficient?

2. The Riddle of Gregory XIII. Gregory XIII was not a mathematician. He was the Pope. Nevertheless, his name is associated with an important mathematical problem - the problem of the calendar.

Nature gave us two natural units of time: the year and the day (solar). As it is said in one old cosmography textbook *) “towards the end of the year, a year is not equal to a whole number of days.” One cannot but agree with this, since many inconveniences arise from the mentioned fact. But it gives rise to an interesting mathematical problem.

1 year =
= 365 days 5 hours. 48 min. 46 sec.
or

1 year = 365.242199 days.

It is impossible to legitimize such a length of year in civil life. What happens if you consider a year to be 365 days? Fig. 3 shows orthography, which is the same name for a school subject that contained general information on astronomy and physical geography.

*) Cosmography is the so-called academic subject that contained general information on astronomy and physical geography.

Fig. 3.

Earth bit. January 1, 1970 at 0 o'clock. The Earth is at point A. In 365 days it will not arrive at the same point in the orbit and, therefore, on January 1, 1971 at 0 o'clock. will be at point B, and January 1, 1972 - at point C, etc. It turns out that if you fix a certain date, the position of the Earth in orbit will be different every year (it will lag by almost 6 hours).

Over four years, the lag is almost a day, and the fixed date will fall on different seasons, i.e. January 1 will gradually move from winter to autumn, then to summer. This is inconvenient: periodic events (planting, the beginning of the school year) cannot be associated with specific calendar dates.

There is a way out of this situation. It is necessary to count some years by 365 days, and some by 366 days, through them so that the average length of the year is as close as possible to the true one. It is possible to reproduce the true length of the year with any accuracy, but this may involve a very complex law of the division of short (simple) and long (leap) years, which is undesirable. A compromise is needed: compare/no go through the law of passing through years, which gives the average length of the year quite close to the true one.

This problem was first solved by Julius Caesar. Of course, the correct word “allowed” can only be applied conditionally. This was done for him by the Alexandrian astronomer Sosigenes, who was summoned to Rome for this purpose. Julius Caesar will introduce the following system: three short years in a row, the fourth long.

Much later, when the Christian calendar was adopted, years whose number is divisible by 4 began to be considered leap years. This calendar is called the “Julian”. According to the Julian calendar, the average length of the year is

$$365 \frac{1}{4} \text{ суток} = 365 \text{ суток } 6 \text{ часов.}$$

⟦folio 20⟧

As you can see, the average length of the Julian year is 11 minutes longer than the true one. 14 sec. In the 16th century, Pope Gregory XIII wished to correct this inaccuracy. In 1582 he made the following reform of the calendar. The distinction between simple and high years is preserved, but it complements the rules: if the year number turns out to be two zeros, and the number of shifts is not divisible by 4, then this year is viewed. For example, according to this, the year 1700 was simple, but 1600 was high.

In addition, considering that from the beginning of the chronology (from the “birth of Christ”) an error of 10 days had already accumulated, Gregory XIII immediately added 10 days. Since then, 3 more days have accumulated (in 1700, 1800 and 1900). Therefore, at present, the discrepancy between the Julian calendar and the new (“Gregorian”) calendar is 13 days.

What is the average length of a Gregorian year? Out of 400 years according to the Julian calendar, 100 are high-grade, and according to the Gregorian calendar - 97. Therefore

average length of a Gregorian year =
= 365 $\frac{97}{400}$ days = 365.2425 days =
= 365 days 5 hours. 49 min. 12 sec.,

i.e. it is 26 seconds longer than the true one.
As you can see, very high accuracy has been achieved using simple means.

In Tsarist Russia, before the Great October Revolution, they used the Julian calendar. The Grigorian calendar was introduced by a special decree of the Council of People's Commissars in 1918. This is what we currently use. The extent to which it corresponds to the actual length of the solar year is sufficient for all practical purposes. Is it possible to say that the decision of the fall of Gregory XIII is the simplest and most natural? Please bear with your answer until the end of this article.

II. CHAIN ​​FIREWOOD

3. The concept of chain fraction and. Let's forget about the decimal number system. As the outstanding Russian mathematician Nikolai Nikolaevich Luzin (1883-1950) said, “the advantages of the decimal system are not mathematical, but zoological. If we had not ten fingers on our hands, but eight, then humans would use the octal system.” The decimal system is convenient for practical evaluation, but when studying theoretical questions of arithmetic, it only gets in the way.

So, let's open ourselves up to special number systems and ask ourselves the question: what is the most natural way to approximate the representation of positive numbers by fractions.

There can be no hesitation in the answer to this question: it is necessary first of all to indicate between which numbers it is concluded. For example,

$$\frac{61}{27} \text{ нахождение между } 2 \text{ и } 3,$$
$$\sqrt{2} \text{ » } 1 \text{ » } 2,$$
$$\pi \text{ » } 3 \text{ » } 4.$$

Of course, it is enough to indicate only the lesser of these numbers:

$$\frac{61}{27} = 2 + x \quad (0 < x < 1),$$
$$\sqrt{2} = 1 + y \quad (0 < y < 1),$$
$$\pi = 3 + z \quad (0 < z < 1).$$

⟦folio 21⟧

Note that such an estimate is not related to the way in which integers are notated, i.e., to any specific number system.

Will deal with the number $\frac{61}{27}$. Our estimate of “more than two” is too rough and is only suitable as a *first approximation*. If we want to take the second step, then we must evaluate the addition $x$. Since it is less than one, it is natural to represent it as a fraction with the numerator 1 (we again appeal to “naturalness”, but this is the last time)

$$\frac{61}{27} = 2 + \frac{1}{x_1}.$$

Now $x_1$ is greater than one, and we repeat the same steps again: select the whole part, etc., etc. We invite the reader to carefully follow the alternation of these two steps:

$$\frac{61}{27} = 2 + \frac{7}{27} = 2 + \frac{1}{27} =$$

$$= 2 + \frac{1}{3 + \frac{6}{7}} = 2 + \frac{1}{3 + \frac{1}{7}} =$$

$$= 2 + \frac{1}{3 + \frac{1}{1 + \frac{1}{6}}}.$$

Expression

$$a_0 + \frac{1}{a_1 + a_2 + a_s},$$

where $a_1, a_2, \dots, a_s$ are natural numbers and $a_0$ is a natural number or zero, is called a continued fraction.

The numbers $a_0, a_1, a_2, \dots, a_s$ are called elements *) of a continued fraction. We can say that we have represented the number $\frac{61}{27}$ as a continued fraction.

*) Sometimes they are called irreducible quotients.

Isn't the continued fraction notation too cumbersome? In our example, the result is a three-story fraction, but if it turns out to be a twenty-story fraction, then it cannot fit on a sheet of paper.

This is true, and therefore different notation conditions are used for continued fractions. We will use this:

$$a_0 + \frac{1}{a_1 + a_2 + a_s} =$$

$$+ \frac{1}{a_s}$$

$$= [a_0; a_1, a_2, \dots, a_s].$$

Note the semicolon. She emphasizes that the role of the whole part $a_0$ is special, not the same as other numbers (special does not mean more important, in this case, rather the opposite).

Is it possible to say that every real *) number can be represented by a continued fraction and, moreover, in a unique way?

First of all, let's think about this example:

$$\frac{1}{6 + \frac{1}{4}} = \frac{1}{6 + \frac{1}{3 + 1}} = \frac{1}{6 + \frac{1}{3 + \frac{1}{1}}}$$

or in abbreviated notations

$$[0; 6, 4] = [0; 6, 3, 1].$$

Such a transformation (separation of units from the last element) can be performed with any continued fraction in which the last element is distinguished from units. If the last element is equal to one, then it can be added to the penultimate one. For example,

$$[1; 10, 3, 7, 1] = [1; 10, 3, 8].$$

It is easy, however, to prove that this is the only reason for the ambiguity

*) For now we are talking about positive different numbers. The introduction of negative numbers does not change anything in the essence of the issue, but the introduction of irrational numbers changes a lot. This will be discussed below.

⟦folio 22⟧

representation of a rational number as an integer fraction.
It can be proven that:
1) The process of turning the rational number $\frac{p}{q}$ ($p$ and $q$ coprime natural numbers) into an integer fraction ends at some step. In other words, any positive rational number can be represented as $(\cdot)$. By virtue of what has just been said, such a representation is always possible and subject to the constraint $a_s > 1$.
2) Two whole fractions $|a_0; a_1, \dots, a_s|$ and $|b_0; b_1, \dots, b_t|$, which have $a_s > 1$ and $b_t > 1$, are equal to each other if and only if they have the same number of elements, i.e. $s = t$ and $a_i = b_i$ with $i = 1, 2, \dots, s$.
We will not prove this. The purpose of our article is to explain the main ideas and encourage the reader to more thoroughly study the issue in books *).
4. Infinite whole fractions. What about irrational numbers? Let's try to expand into a whole fraction $\sqrt{2} = 1,4142\dots$. Let's Polish:
$$\sqrt{2} = 1 + \frac{1}{x_1},$$
$$x_1 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1,$$
$$x_1 = 2 + \frac{1}{x_2}, \quad x_2 = \sqrt{2} + 1 = x_1.$$
It's clear that
$$\sqrt{2} = 1 + \frac{1}{x} = 1 + \frac{1}{2 + \frac{1}{x}}$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
where $x = \sqrt{2} + 1$

*) All the proofs missed here can be found, for example, in the book by A. Ya. Khinchin “Continued Fractions”, ed. 3, 1961.

I want to write right away
$$\sqrt{2} = 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{2 + \frac{1}{2 + \dots}}}},$$
$$= [1; 2, 2, 2, 2, \dots].$$

that is, represent $\sqrt{2}$ as an infinite whole fraction. But extreme caution is needed here: we have encountered a new concept of “infinite decimal fraction”, but we do not know what it is. It is easy to understand that each positive irrational number corresponds to the full definition of an infinite sequence
$$[a_0; a_1, a_2, \dots],$$
where $a_0$ is a non-negative integer, and all $a_i$ with number $i \geqslant 1$ are natural numbers. We’ll look into everything that applies here only later *), but for now let’s be satisfied with what we understand: how to use a positive number $\alpha$ to construct its formula decomposition
$$\alpha \sim [a_0, a_1, a_2, \dots]$$
to a finite or infinite whole fraction **).

5. Matching fractions. A continued fraction can be terminated by retaining the elements $a_0, a_1, \dots, a_n$ and discarding $a_{n+1}, \dots$. The result thus obtained is called the $n$th suitable fraction and is denoted by $\frac{p_n}{q_n}$. In particular, at $n = 0$ we have a zero suitable fraction $\frac{p_0}{q_0} = \frac{a_0}{1}$.

We will see that the smaller the $n$, the simpler the corresponding fraction is (i.e., it has a smaller denominator). At the same time, it can be used as an approximate value of a whole fraction.

*) This issue will be fully discussed in one of the next issues of the magazine.
**) “~” is a matching sign. We put an equal sign more until the meaning of the symbol on the right side is established.

⟦folio 23⟧

Example. Let us again take the decomposition of the number $\frac{61}{27}$ into a whole fraction and form suitable fractions

$$\frac{p_0}{q_0} = 2,$$

$$\frac{p_1}{q_1} = [2; 3] = 2 + \frac{1}{3} = \frac{7}{3},$$

$$\frac{p_2}{q_2} = [2; 3, 1] = 2 + \frac{1}{3 + \frac{1}{1}} = \frac{9}{4},$$

$$\frac{p_3}{q_3} = [2; 3, 1, 6] = \frac{61}{27}.$$

Of course, the last suitable fraction of the different number $\alpha$ is $\alpha$.

We have obtained several gradual approximations for the number $\frac{61}{27}$. To evaluate them, we replace them with $\frac{61}{27} \approx 2,259$.

1st approximation 2, $\Delta = 0,259$ *).

2nd $\frac{7}{3} = 2,333, \Delta = -0,074$.

3rd $\frac{9}{4} = 2,250, \Delta = 0,09$.

We replace that the error decreases (according to the abscid value) and has alternating signs. This is a general rule.

In the case of decomposition into a whole fraction of the number $\sqrt{2} = 1,4142$... we obtain

$$\frac{p_0}{q_0} = 1, \text{ погрешность } \Delta = 0,4142,$$

$$\frac{p_1}{q_1} = [1; 2] = \frac{3}{2} = 1,5, \Delta = -0,0858,$$

$$\frac{p_2}{q_2} = [1; 2, 2] = \frac{7}{5} = 1,4,$$

$$\Delta = 0,0142,$$

$$\frac{p_3}{q_3} = [1; 2, 2, 2] = \frac{17}{12} = 1,4167,$$

$$\Delta = -0,0025,$$

$$\frac{p_4}{q_4} = [1; 2, 2, 2, 2] = \frac{41}{29} = 1,4138,$$

$$\Delta = 0,0004.$$

We see the same picture here too.

*) $\Delta$-error (see page 17).

6. The main property of their suitable fractions. Let us now formulate without proof the basic property of suitable fractions, which will lead to the solution to our riddles.

If $\frac{p_n}{q_n}$ is a suitable fraction for the number $\alpha$, then the abscid error

$$|\alpha - \frac{p_n}{q_n}|$$

variable than when approximating the number $\alpha$ by any fraction with a smaller value *).

For example, having obtained a suitable fraction $\frac{p_3}{q_3}$ for $\sqrt{2}$, we can be sure that approximating $\sqrt{2}$ to any fraction with a value less than 12 will be worse.

### III. SOLUTIONS

7. The riddle of Archimedes. Let's try to decompose the number into a whole fraction

$$\pi = 3,14159265\ldots$$

$$\pi = 3 + 0,14159265\ldots =$$

$$= 3 + \frac{1}{7 + 0,00885145}.$$

*) Fitting fractions provide extremely high approximations in many respects. The property given here is not the only one and not the most important one. Other properties will be discussed in one of the next issues of the magazine.

⟦folio 24⟧

Already at this stage of calculations we see that the first suitable fraction will be

$$\frac{p_0}{q_0} = 3, \quad \frac{p_1}{q_1} = \frac{22}{7}.$$

Do the calculations yourself and make sure that

$$\pi \approx 13; \ 7, 15, 1, 288, 1, \dots.$$

$$\frac{p_2}{q_2} = \frac{333}{106}, \quad \frac{p_3}{q_3} = \frac{355}{113}$$

That's all. How simple! This table reveals the secret of Archimedes, and at the same time Mecius. From it you can see:

1st approximation: $\pi \approx 3$.

2nd approximation: $\pi \approx \frac{22}{7}$.

3rd approximation: $\pi \approx \frac{333}{106}$.

4th approximation: $\pi \approx \frac{355}{113}$

(odd approximations with a deficiency, even approximations with an excess).

Can we consider that Archimedes and Maecius have been exposed: they used continued fractions, Archimedes used the second suitable fraction, and Maecius the fourth?

No, this cannot be said about Archimedes.

It should be clearly understood that we have solved a mathematical problem, but not a historical one. We explained how you can arrive at the number $\frac{22}{7}$.

It is very possible that Archimedes used continued fractions, but this cannot be established from his works. The court would not accept our arguments. Historians have not reached a consensus. The advantage of the sevenths can also be found empirically by comparing them with various others.

Mecius is another matter. It is incredible to think that a fraction as complex as $\frac{355}{113}$ could be found without theory. It is very likely that Maecius used continued fractions. It is clear why he settled on the fourth suitable fraction: the next present is cumbersome, which is practically unusable.

8. The Riddle of Gregory XIII. First, let's think about how we ourselves would solve the problem of crossing leap years. We would represent the length of a year as a continued fraction.

$$1 \text{ год} = 365^2 5^4 48^3 46^2 = 365,242199^2 = 1365; 4,7,1,3,5,20,6,12]^2.$$

And not. L is an irrational number. It decomposes into an infinite whole fraction. The value of the year is empirical. Any empirical quantity changes only with a certain accuracy, and it makes no sense to talk about its rationality or irrationality. The above value for the year is a common one, and we should consider it accurate. It is expressed as a finite whole fraction.

Find the first few suitable fractions:

$$\frac{p_0}{q_0} = 365,$$

$$\frac{p_1}{q_1} = 365 + \frac{1}{4} = 365 \frac{1}{4},$$

$$\frac{p_2}{q_2} = 365 + \frac{1}{4 + \frac{1}{7}} = 365 \frac{7}{29},$$

$$\frac{p_3}{q_3} = 365 + \frac{1}{4 + \frac{1}{7 + \frac{1}{1}}} = 365 \frac{8}{33},$$

$$\frac{p_4}{q_4} = 365 + \frac{1}{4 + \frac{1}{7 + \frac{1}{1 + \frac{1}{3}}}} = 365 \frac{31}{128}.$$

What suitable fraction provides a solution to the calendar problem. For example, approximating $365 \frac{1}{4}$ leads to Julius Caesar's solution: one leap year out of every four. No one suggested using the $365 \frac{7}{29}$approximation, apparently because the next approximation

⟦folio 25⟧

365/33 is only slightly more complex, but significantly more accurate. The calendar, according to which eight years out of every thirty-three were to be considered high, was proposed by the Turkmen-Persian philosopher, mathematician, astronomer and therefore Omar Khayyam (1040-1123).

Information on the accuracy of the found approximations to the true dinegadana is in the following table.

| Approach No. | Alternation of high years | Average year length | Error |
| :--- | :--- | :--- | :--- |
| 1 | 1 high from every 4 | 365ᵃ 6ᵃ 00ᵃ 00ᵇ | -11ᵃ 14ᵇ |
| 2 | 7 》 》 》 29 | 365ᵃ 5ᵃ 47ᵃ 35ᵇ | +1ᵃ 11ᵇ |
| 3 | 8 》 》 》 33 | 365ᵃ 5ᵃ 49ᵃ 05ᵇ | -19ᵇ |
| 4 | 31 》 》 》 128 | 365ᵃ 5ᵃ 48ᵃ 45ᵇ | +1ᵇ |

In the “Error” column, the minus sign indicates that the average length of the year is greater than the true one.

The fourth option is extremely accurate. Error in 1 sec. has no practical significance. Therefore, there were proposals to use this calendar. For example, in 1864, the Russian astronomer Medler proposed introducing such a calendar in Russia from the 20th century. To do this, you need to introduce the following amendment to the Julian calendar: every 128 years, skip one high-rise year (because according to the Julian calendar, there are 32 high-rise years for every 128 years). However, this calendar was not adopted anywhere in the world, apparently because the 128 period is “non-circular.”

Having solved the mathematical problem, let us return to the historical problem. What were the messages of Gregory XIII (or his staff)?

At the beginning of the article it was said that the average length of the Gregorian year is 365 days 5 hours. 49 min. 12 sec.

This value differs from the true value by as much as 26 seconds. It turns out that Gregory XIII or his learned advisers came up with the idea of...

nomeus (it was not for nothing that he was given the name Alphonse the Astronomer). These tables were first published in Venice a hundred years after the death of their author. They give the following length of the year:

1 year = 365ᵃ 5ᵃ 49ᵃ 16ᵇ.

Using these tables, the commission should be able to come to the conclusion that the proposed average length of the calendar year differs only by four seconds from the true one. If the commission had been familiar with Omar Khayyam's proposal, it would have come to the conclusion that his calendar made an error of 11 seconds.

We add that there is no reason to assume that the commission of Gregory XIII used whole fractions. She painstakingly selected the desired match in NOTE faces.

As for Omar Khayyam, scientists think that he owned, if not a complete theory of whole fractions, then some similar fundamental approach to problems of the most rational approximations of fractions with small values. In his era, Eastern science was in many respects superior to European science.
