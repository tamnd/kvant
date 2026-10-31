---
id: 1975-11-nikolaev-ravnopravnyi-li-vse-tsifryi-db60be16
issue: kvant_1975_11
year: 1975
number: "11"
title: Are all numbers equal?
authors:
  - Николаев Е. Г.
rubric: osnovnye-stati
page_first: 18
page_last: 21
page_labels: 16-19
tag: UBUL
lang: en
source: kvant_digital
extraction: vision
content_sha256: a8b3bef36f7b1d547624b434d36b2d8110f7a418ba5049b2fb0afafbd11472ea
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/05_nikolaev-ravnopravnyi-li-vse-tsifryi-db60be16.md
source_content_sha256: 5e6850c52271cda7a5605717b82e78e0d152b1c3bb0ca6fb91817fa48ede0805
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Experimental results

The question in the title of this article looks strange: is any number really worthy of special attention? To check this, the author of the article repeated the experiment of the modern American mathematician Hamming. Both experiments consisted of the following. One hundred named constants were randomly selected from several reference books on chemistry and metallurgy. The resulting set included the height of the chimney of one of the types of open-hearth furnaces, the specific gravity of stone coli, the calorific value of propane, and even such an exotic parameter for non-specialists as the “rate constant of silk saponification” of one ester. In a word, it creates a “vinaigrette” of a wide variety of sizes.

To somehow order them, let's call the i-number any number in the most significant digit of which there is a digit i (i = 1, 2, ..., 9). So, the number 1 will be a 1-number, and 3.7 and 0.0371 will be 3-numbers.

At first glance, it seems that it is most natural to expect a uniform distribution of constants across nine groups, where the i-numbers fall into the i-th group. Since we have chosen constants, we should have approximately eleven i-numbers for each digit i. Of course, one cannot rely on the exact number 11 appearing for all digits i (this is impossible, since 9·11 ≠ 100). But here’s how the average constants were actually distributed (see table):

| i | Number of i-numbers |
| :--- | :--- |
| Hamming | Author | Theoretical* |
| 1 | 34 | 25 | 31 |
| 2 | 12 | 17 | 17 |
| 3 | 13 | 16 | 13 |
| 4 | 15 | 11 | 9 |
| 5 | 7 | 9 | 8 |
| 6 | 3 | 8 | 7 |
| 7 | 4 | 6 | 6 |
| 8 | 4 | 4 | 5 |
| 9 | 8 | 4 | 4 |

Total 100 100 100

As can be seen from the middle columns of this table, more 1-numbers were discovered in both experiments than, for example, 7-numbers. How can we explain this? Perhaps, during the experiments, there was an unconscious manifestation of “liberty” towards the number 1?

Hamming did not describe the method he used to select his numbers. The author chose an arbitrary one approximately like this. For some time, he wrote out the first six digits of the seven-digit numbers of his share notes; as a result, a certain list is formed

*) The “theoretical” number of i-numbers will be discussed below.

⟦folio 17⟧

“*random numbers*.” Based on the first digit of such a random number, a reference book was selected (the reference books were pre-numbered), and based on the next two digits, a page was selected; the remaining three digits corresponded to the row and column numbers from which the number was taken. Of course, it was not always possible to strictly follow this rule.
Therefore, we had to apply a number of clarifications, but we will not dwell on them. In any case, it is clear that the special position of the 1-numbers is based on something more important than just the arbitrariness of the experimenters.

**What's the matter?**

Every constant in the reference book is obtained as a result of some measurement. Measurement is a comparison with a standard (kilogram, meter, second). Do we take into account the use of specific standards anywhere, considering it natural to have a uniform distribution of $i$-numbers among the chosen constants? No. Therefore, we can expect that the form of this distribution will not change significantly if we select similar constants from American tables, which use, for example, not a meter, but a foot. Indeed, from the “American” point of view, the uniform distribution of $i$-numbers is just as natural.

As we will now see, we have no reason to expect that the distribution of $i$-numbers will turn out to be uniform precisely because *the uniform distribution is not preserved when the measurement scale changes*.

⟦column⟧

Let's illustrate this with the following example. Let's create a uniform distribution of $i$-numbers artificially. Let's take the number axis and apply a “comb” with $n$ teeth to it (black comb, Fig. 1).

Let the numbering of the comb teeth begin from zero, and the comb is such that if its zero tooth is placed opposite the number 1, then the last $((n-1)$) tooth will not “reach” the number 10 by the amount of one space between the teeth. Since there are $(n-1)$ spaces between the comb teeth, the size of one gap is $9/n$. Therefore, on the number axis the teeth of the comb correspond to numbers

$$x_k = 1 + \frac{9}{n}k, \ \ k = 0, 1, \ldots, n-1, \ (1)$$

forming an arithmetic progression. In this group of numbers, the $i$-numbers are distributed approximately evenly: the number of $i$-numbers among them for any $i$ digit is approximately equal to the ratio $n/9$ (possible error here $\pm 1$, why?).

Let us now change the scale by multiplying each number (1) by some number $a$, and

$$2 \leqslant a < 10. \qquad (2)$$

Let's see how this multiplication affects the number of 1-numbers. For them (only for them), we obviously have:

$$10 \leqslant a + a\,\frac{9}{n}\,k < 20.$$

Consequently, the numbers of the new 1-numbers are contained in the interval

$$\frac{10-a}{9a}\,n \leqslant k < \frac{20-a}{9a}\,n,$$

⟦figure⟧
Fig. 1.

2 «Kvant» № 11

⟦folio 18⟧

and, since $k$ is an integer, there will be approximately as many 1-numbers as the length of the inverval - about $10n/9a$. In other words, the number of 1-numbers will increase by approximately $10/a > 1$ times (and this estimate is more accurate, the larger the number $n$).

So, by changing the scale by $a$ times ($2 \leqslant a < 10$), we will increase the proportion of 1-numbers among the numbers of set (1), although in the old scale, by construction, 1-numbers did not stand out. This indicates that the assumption of a uniform distribution of $i$-numbers is unnatural.

"Logarithmic" scale

figure 2 shows two scales. Together they form, as it were, a “table of logarithms”: under any number on the upper scale (with uneven divisions) you can read the decimal logarithm of this number, and vice versa - using the logarithm marked on the lower scale, it is easy to find this number itself on the upper scale (which therefore would be logical to call the antipolagyrph scale, but we will call it a logarithmic scale).

The logarithmic scale has one extremely important property: the numbers depicted on it are very easy to multiply and divide. Let us recall the basic property of logarithms:

$$\lg ab = \lg a + \lg b.$$

Therefore, the multiplication of the numbers $a$ and $b$ can be done as follows: take these numbers

la on a logarithmic scale, find directly below them $\lg a$ and $\lg b$, then add the values ​​found (due to the uniformity of the lower scale, this means moving from the point $\lg b$ to a distance $\lg a$) and, finally, read the result on the logarithmic scale (Fig. 2). The direction of the shift is determined by the sign of the number $\lg a$: if $\lg a > 0$, the shift will occur to the right, if $\lg a < 0$ - to the left. (By the way, the device of a slide rule is based on this principle).

Let us return, however, to our comb. We will assume that the comb is applied to the lower scale, and the gap between the teeth is equal to $1/n$. The tooth with the number $k$ on the lower scale corresponds to the number $k/n$, and on the logarithmic (upper) scale - the number

$$y_h = 10^{k/n}, k = 0, 1, \dots, n - 1. \quad (3)$$

The numbers (3) form a geometric progression with the value $n/10$. The number of $i$-numbers among them now depends on $i$. Roughly speaking, it is equal to the ratio of the length of the interval of the lower scale, corresponding to the $i$-number of the logarithmic scale, to the length of the interval of the lower scale, which corresponds to the number $i$.

Let us now multiply all numbers (3) by $a$. To do this, we simply need to shift the entire comb by a distance of $\lg a$ (in lower scale units). If inequalities (2) are satisfied for $a$, then the 1-numbers obtained after such a shift will be on

logarithmic scale in the range from 10 to 20. But the length of this interval (in units of the lower scale) is equal to the mantissa of the number $\lg 20$, that is, it coincides with the length of the interval from one to two (see Fig. 2). Therefore, up to $\pm 1$, the number of 1-numbers will remain the same. In fact, with this shift, the number of $i$-numbers for any $i$ is preserved, and condition (2) by the value $a$ can be discarded. Try to prove it yourself (see task 2).

Even the converse statement is true (although it is not easy to give its exact formulation and proof): *any distribution of i-numbers that is preserved when multiplied by an arbitrary number $a > 0$ must be close to the “logarithmic” distribution* specified by the comb.

Let's use the “comb distribution” to answer the main question of the article. Let's remember our table (see p. 16). Its last column indicates exactly the number of $i$-numbers among those forming the geometric progression of numbers (3) at $n - 100$. We see that 1-numbers really predominate among them and, moreover, that all the data from this distribution agree quite well with the experimental ones. This observation allows us to assume that *the distribution of i-numbers among the numbers forming a geometric progression* (3) is *the most probable* (that’s why we called the last column of the table “theoretical”).

Have we, however, been able to prove the hypothesis that in an arbitrary table the distribution of $i$-numbers will correspond to a “logarithmic” distribution? Of course not. It is impossible to prove this in general terms. This requires additional assumptions about the nature of the randomness of the set of constants under consideration. Let us only note here that there are tables of named constants (for example, train schedules) with a completely different distribution of $i$-numbers.

⟦column⟧

**Preferred numbers**

A person planning production is faced with the task of planning the production of variants of the same product that differ in *standard sizes*. For example, electric lamps are needed with a power ranging from fractions of a watt (for illuminating instrument scales) to tens of kilowatts (for lighthouse lights). How to create a set of standard sizes to satisfactorily meet any need?

Of course, I would like the number of standard sizes not to be too large. To do this, the planned options must correspond well to the unknown distribution of possible needs. We know almost nothing about this distribution, but it is difficult to believe that it can depend greatly on the units of measurement used.

Here it is appropriate to recall the hypothesis we expressed at the end of the previous paragraph concerning the exclusivity of the “logarithmic” distribution of $i$-numbers among numbers (3).

It turns out that in our country, standard size options are fixed by a special legislative decree: *state standard* (GOST). Since 1957, GOST 8032-56 has been in force in the USSR, according to which in all industries, when introducing a new standard size, it is recommended to adhere to some very specific coefficients: *preferred numbers*.

These numbers represent the rounded values ​​of the logarithmic scale numbers defined by the “combs”, i.e. numbers (3), at $n - 5$, 10, 20, 40! The set of preferred numbers corresponding to one comb is called a *row* and is denoted by $Rn$. The letter $R$ is usually associated with the name of the French engineer Ch. Renard, who used such numbers to select the thickness of balloon cables at the end of the 19th century. Here's how

2\*

⟦folio 19⟧
