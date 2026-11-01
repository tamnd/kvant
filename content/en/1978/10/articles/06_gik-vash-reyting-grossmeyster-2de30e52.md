---
id: 1978-10-gik-vash-reyting-grossmeyster-2de30e52
issue: kvant_1978_10
year: 1978
number: "10"
title: What is your rating, grandmaster?
authors:
  - Гик Е. Я.
rubric: osnovnye-stati
page_first: 22
page_last: 25
page_labels: 20-23
tag: FACK
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd7395f7960a29ec8148129b125d40702c3dd65c3c74d3e42abc835c010eb907
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/06_gik-vash-reyting-grossmeyster-2de30e52.md
source_content_sha256: 579b67c8ba5426a1849418baeeaaa9461b617d9e0a1d77c700c6416c7ce10513
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

E. Gik

What is your rating, grandmaster?

On pages «Kvant» we have not written about the various connections that exist between mathematics and chess. In this article we will discuss the Elyu coefficient system, which is widely used to evaluate and predict the results of chess players in modern tournaments and matches.

In those distant times, when only a few ten masters competed in chess tournaments all over the world, it was not difficult to compare the results of chess players today. The question of which of the two masters plays stronger was resolved simply: for a certain period of time they met each other in tournaments, and if one regulator was stronger than the other, it meant that he was stronger; if there was only one in front, one could assume that their strength was approximately the same; in especially controversial cases, the match between them was eliminated.

Nowadays modern chess takes place simultaneously in several countries and even in several cities of one country. In the modern international qualifying tournaments alone (that is, those in which international values ​​are assigned), a good thousand chess players participate, of whom they know a lot about each other only by experience. Under such conditions, it became more difficult to compare the strength of masters.

The first attempts to construct a system for assessing the strengths of chess players date back to the beginning of the century. And at the end of the 50s, practical tests of several systems began, based on the fact that each chess is assigned an individual coefficient, varying from contemporary to modern, or, in other words, a rating (from the English word rating - “assessment”), calculated according to a certain formula and depending on the opponents’ coefficients and showing

⟦folio 21⟧

desired result. After many years of discussion of various coefficient systems (not fundamentally different from each other), the International Chess Federation (FIDE) in 1970 officially adopted the system of individual coefficients developed by the American mathematician Professor Arpad Elo.

Let us first show how coefficients are calculated using the Elo system, and then discuss a number of its features.

Let the “old” coefficient of a given participant (i.e., the coefficient before the start of the competition) be $K_{ct}$. The “new” coefficient (coefficient after the end of the competition) $K_{now}$ is found using the following formula:

$$K_{now} = K_{ct} + 10 (N - N_{ojk}),$$

(1) where $N$ is the number of points scored (the result of chess in the competition), and $N_{ojk}$ is the so-called window and the number of points given.

To calculate $N_{ojk}$, first of all, the average coefficient $K_{cp}$ of all opponents of a given chess game is calculated (in the case of a match, $K_{cp}$ coincides with his partner’s $K_{ct}$), which is then rounded to a whole number *).

*) “Borderline” numbers (like 2377.5) are rounded, by convention, in any direction - for example, towards smaller numbers.

Then we find the deviation of the coefficient $K_{ct}$ from $K_{cp}$:

$$\Delta K = K_{ct} - K_{cp}.$$

(2)

Now from table 1 to $|\Delta K|$ the window and the percentage of points given are determined:

$$h = \begin{cases} h_6, если \Delta K \geqslant 0. \\ h_m, если \Delta K < 0. \end{cases}$$

(3)

Finally, the expected number of points is obtained by rounding to the nearest 0.5 points using the following formula:

$$N_{ojk} = \frac{h}{100} \cdot m,$$

(4)

where $m$ is the number of games that chess will present in the competition. Informally speaking, $N_{ojk}$ is the most reliable chess result in the competition, and $h$ is the most reliable percentage of points scored; this explains the correspondence (4).

Note that in the USSR, when calculating the ratings of Soviet chess, the Elo system was officially used from January 1, 1977, with the only difference being that rounding in formula (4) is done to 0.1 points.

If before the start of the tour we want to find the $K_{i_{now}}$ of each participant in the tour, we must, in accordance with equality (2), calculate the average ratings $K_{i_{cp}}$ of the opponents of each participant ($i = 1, 2, ..., n$). It turns out that this work can be

⟦folio 22⟧

simplify. Let $K_{cT}^1, K_{cT}^2, \dots, K_{cT}^n$ be the ratings of the tournament participants before it started. Let's introduce the quantities

$$K_T = \frac{K_{cT}^1 + K_{cT}^2 + \dots + K_{cT}^n}{n}$$

(it is rounded to the nearest whole number), called the tournament coefficient. It's easy to prove that

$$\Delta K = \frac{n}{n-1} (K_{cT} - K_T),$$

(5)

where rounding will again be done to an integer (the rounding results in formulas (2) and (5) are the same). Thus, instead of calculating the coefficients $K_{cP}^i$ $n$ times, we only need to find the coefficient $K_T$ once, and then use formula (5) to determine $\Delta K$.

To qualify for an international tournament using the Elo system, it is necessary that: 1) at least 2/3 of its participants have a rating; 2) the tournament coefficient $K_T$ was at least 2250. If, before the start of such a tournament, one of the participants does not yet have a rating, then he receives an initial coefficient $K_0 = 2200$ (which, very conveniently, may decrease after the tournament). Since $K_0$ is an integer, and numbers $N_{ojk}$ are rounded to 0.5 or 0.1, the ratings of chess players are always integers, and for Elo they end in 0 or 5.

Taking a careful look at Table 1, we will notice that from row to row the percentage $h$ changes by 1 and upon reaching $h_6 = 100$ (respectively, $h_M = 0$) no longer changes (we will find ourselves in the “saturation zone”).

To better understand Table 1, we provide graphical images of $h$ from $\Delta K$, and $h$ will be perceived in accordance with the intuitive meaning of the words “expected eye process”.

If a given competitor's odds $K_{cT}$ coincide with his opponents' $K_{cp}$, then he should be expected to score $50\%$ points; therefore, the required curve must pass through the point with coordinates $\Delta K = 0$, $h = 50$. It is natural to consider it symmetrical relative to this point. If $K_{cT} > K_{cp}$, then, of course, $h > 50$, and if $K_{cT} < K_{cp}$, then $h < 50$. Since $h$ varies from 0 to 100, the curve should asymptotically tend to the line $h = 100$ at $\Delta K \rightarrow +\infty$ and to the x-axis at $\Delta K \rightarrow -\infty$.

Enormous statistics of accomplishments show that if out of two chess players playing a match, one says this, one rank better than the other, then on average he scores 75% of the points.

Elo took this circumstance into account when constructing the curve as follows: assuming that the difference between two adjacent steps in the chess nonarchy is 200 rating units, he drew the curve through the point with coordinates $\Delta K = 200$, $h = 75$ (and, accordingly, $\Delta K = -200$, $h = 25$).

So the shape of our curve is pretty clear (see figure), and it can be used to determine the values ​​of $h$ given $\Delta K$. However, this method of finding $h$ is inconvenient for several reasons. Firstly, the curve itself, despite the above properties, is not uniquely defined; secondly, there are infinitely many integer values ​​of $\Delta K$ and they cannot be tabulated; Finally, don’t change the values ​​of $h$ with a ruler every time! Therefore, the idea arises of dividing the abscissa axis into a finite number of segments (and two infinite half-intervals) with a constant $h$ on each of them so that the values ​​of $h$ on adjacent segments differ by 1.

As a result, together with our main curve we get a “ladder” (see figure). The height of its steps is the same and equal to 1, and their lengths increase as they move away from the center in accordance with the rise of the curve.

⟦folio 23⟧

Of course, Table 1, built using this “ladder”, could look somewhat different (if you choose slightly narrower or wider segments with a fixed $h$), but this has no fundamental significance - as long as the general nature of the dependence $h$ on $\Delta K$ is preserved.

Currently, before the start of any major tournament, the numbers $N_{ojk}$ are calculated for all its participants, which makes it possible to estimate the final results of the tournament and the most likely distribution of places in it. However, this popular forecasting method can be used not only before the start of northerning, but also before each of its turims. If we add the points scored by a participant in the already held tournaments with the points that “promise” him the Elue coefficients in the remaining tournaments, we will get the expected result in the tournament, taking into account the games already played. It is natural to believe that these forecasts more accurately characterize the position of the participants at a given moment than the number of points actually scored by him, since they take into account information about the remaining opponents.

The forecasting method in question has some technical difficulties. After all, let’s say, with 22 participants in the tour, to find the numbers $N_{ojk}$ before each tour, the calculation of the expected results will be given in the table 21 times. Manually, such work will require several hours of calculation, and it can only be started after the draw of the tournament. However, the computer copes with this task in just a minute!

When applying formula (1), a paradox arises, which is worth dwelling on in more detail. Imagine that you decide to play a match with your friend, say, from the 1000th party. You are both first-rate players and have the same rating of 2000. Let you win this mapphone with a score of 580:420. According to the forecast, you should have made the match a draw, i.e., score $N_{ojk} = 500$ points. A difference of 80 points will give you a rating increase of 800 units. So, by finishing this match, you will receive a rating of 2800 - more than the world champion himself!

It is not difficult to see that with an increase in the number of games in a match, the rating of one chess game can generally increase indefinitely, while the rating of another can decrease indefinitely.

Thus, the linear relationship between the result of chess in northerning and the increase in one’s rating is not entirely legitimate. They tried to get out of the situation in different ways. The most common of them is the introduction in formula (1) together with the coefficient 10 of the variable parameter $\alpha$, which depends on the number of the batch:

$$K_{нов} = K_{ст} + \alpha (N - N_{ojk}).$$

In this case, it is possible to get rid of the paradox, but the calculation of coefficients becomes noticeably more complicated.

The origin of the paradox is due to the fact that the coefficients of chess actually change not only at the end of northing, but also during it. So, in the mentioned match of 1000 games, soon after it starts, you will lead in the score, which should lead to an increase in your rating and a drop in rating. If you average 58% of points (according to the final score), then as soon as the difference in your rates reaches 60 units (2030 versus 1070), the odds will stabilize and will not change much in the future (a difference of 60 units of rate corresponds to 58% of points - see table 1).

From the above it follows that the Elyu system is corrected very simply - the coefficients should be crossed after each game! However, such a partial intersection, justified mathematically, will not suit anyone in practice. So, it is not suitable to calculate ratings either after a large number of games or after each game.

The truth, as always, lies after the definition. Formula (1) is simple and convenient, and I don’t want to give it up, but it is necessary to limit myself to the “average” number of the batch. Elyu himself believes that if $m \leq 25$, then there are no under-
