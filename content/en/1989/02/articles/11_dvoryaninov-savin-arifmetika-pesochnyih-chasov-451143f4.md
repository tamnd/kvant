---
id: 1989-2-dvoryaninov-savin-arifmetika-pesochnyih-chasov-451143f4
issue: kvant_1989_2
year: 1989
number: "2"
title: Hourglass Arithmetic
authors:
  - Дворянинов С. В.
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 49
page_last: 50
page_labels: 47-48
tag: ZNX9
lang: en
source: kvant_digital
extraction: vision
content_sha256: cc39071d1f2c96a433b632737ab79f6153debce80f3c6f0758f12afdd9616802
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/11_dvoryaninov-savin-arifmetika-pesochnyih-chasov-451143f4.md
source_content_sha256: 5c0bce25ca8e9a764c5f0a7b124ede69a9dd3f3e125dd897388b81867306c638
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

ARITHMETIC
HOURGLASS

Candidate of Physical and Mathematical Sciences
S. V. DVORYANINOV,
Candidate of Physical and Mathematical Sciences
A. P. SAVIN

Over the course of history, man has invented many types of watches: solar, fire, water, sand, mechanical, electric, electronic, atomic...

The sundial can now be found on missions as a decoration. The candles on New Year's trees remind us of the fiery hours.
The waterglass and hourglass announce themselves in the exclamation: your time is up! True, in some places in the clinics there were still hourglasses for 3, 5 and 10 minutes. But even there they cannot compete with electric and electronic timers, which are replacing these thousand-year-old inventions, just as computers and microcalculators are replacing office abacus and arithmeters.

But still, let's think a little about the hourglass - a glass container with a hoist tied around the waist (Fig. 1), through which fine calcined sand is poured from one half of the clock to the other.

If it is a three-minute clock, then the sand is poured out in three minutes. If you turn them over immediately, you can measure 6 minutes. If you turn them over once when the sand is completely poured, you can wait until the end of the nine-minute interval. It is clear that in this way you can measure any integer number of minutes that is a multiple of trem.

Well, if we have a pair of hourglasses - a three-minute and a five-minute - then we can also measure time in multiples of 5 minutes. Thus, we can measure 3, 5, 6, 10 minutes... In addition, we can measure 8 minutes: first count-

melt for 5 minutes on one clock, and then 3 minutes on the other. And 11 minutes? This is also possible, because 11=2·3+5. And you can measure 12 minutes, since 12=4·3. Check that you can measure 13, 14, and 15 minutes.

Or maybe we can measure any integer number of minutes greater than 7? Of course! If we reduce the measurement to 8, 9 and 10 minutes, then by adding 3 minutes we get 11, 12 and 13 minutes, by adding another 3 minutes we get 14, 15 and 16 minutes, etc.

Let us note that at the same time we showed that any amount of an integer number of rubles, greater than seven rubles, can be paid in denominations of 3 and 5 rubles. On paper days, proof can also be carried out in real life.

Let us pay a certain number of rubles, more than seven; We will show that in this case we can pay the amount by 1 ruble more. From here - as they say, by induction - our statement will follow.

Fig. 1.

⟦folio 48⟧

Indeed, if the existing amount contains a kupora of 5 rubles, then by replacing it with two “three rubles”, we will increase the amount by 1 ruble. If there is not a single “five” in the total, then there are at least three “three rubles” (the sum is more than seven). By replacing three “three rubles” with two “fives”, in this case we will increase the amount by 1 ruble. The proof is over.

But let's return to the hourglass. If we have only five-minute and ten-minute watches on our hands, then, as is easy to understand, with their help we can only measure periods of time that are multiples of 5 minutes. And in general, if we have a $k$-minute and $m$-minute hourglass, then the time measured with their help will be a multiple of gcd $(k, m)$ - the most common divisor of the numbers $k$ and $m$. The numbers 3 and 5 are relatively prime, their most common divisor is 1; the numbers 3 and 10 are also relatively prime. It turns out that with the help of a three-minute and ten-minute hourglass you can measure any number of minutes, more than seventeen. Indeed, $18=6 \cdot 3, 19=10+3 \cdot 3, 20=2 \cdot 10$. And then, as before, we add the required number of three-minute intervals.

Well, in the general case? It turns out that if the numbers $k$ and $m$ are coprime, then using the $k$-minute and $m$-minute clocks you can measure any number of minutes greater than $km-k-m$. Let us note, by the way, that $3 \cdot 5-3-5=7$, and $3 \cdot 10-3-10=17$, i.e., three-minute and five-minute clocks can measure any integer time interval, more than seventeen minutes; and three-minute and ten-minute clocks are any integer time interval greater than seventeen minutes, which is what we saw before.

Let us prove that it is impossible to measure exactly $km-k-m$ minutes using $k$-minute and $m$-minute clocks with coprime numbers $k$ and $m$. In fact, we were able to do this by “running” a $k$-minute clock $x$ times, and a $m$-minute clock $y$ times. Then $km-k-m=xk+ym$, or $k(x+1)=m(k-1-y)$. Since $k$ and $m$ are coprime, the number $k-1-y$ must be divisible by $k$ (and $k-1-y>0$). But $k-1-y<k$. We got a contradiction.

Thus, we have proven that, using a three-minute and a five-minute hourglass, it is necessary to measure a period of time of 7 minutes. Now let's do the necessary thing - measure 7 minutes using this clock! What about our proof? The proof is correct, but only under the assumption that the next start of the clock will occur after the sand has completely poured out of the clock that was working before. This assumption is natural for one clock, since with their help we cannot mark periods of time less than the one for which this clock is designed. But having two watches gives us new opportunities.

Let's run a three-minute and a five-minute clock simultaneously. At the moment when the last grain of sand falls down on the three-minute clock, we will stop the five-minute clock. It's very simple to follow - is it worth trying them sideways (Fig. 2). Teler's five-minute clock is “tuned” to 2 minutes, that is, with its help we can measure two minutes, and therefore 7 minutes: $7=2+5$.

So, with the help of three-minute and five-minute clocks, we can measure periods of time of 2, 3, 5, 6, 7, 8 and any number of minutes more. The rest are at intervals of 1 and 4 minutes. Maybe they can be measured too? Certainly. Let's “start” our clocks simultaneously. At the moment when the sand on the three-minute clock runs out, we turn it over and, thereby, begin a new three-minute period, but we will finish it at the moment when the second clock measures its 5 minutes. A stopped three-minute clock will be “set” to 1 minute $(2 \cdot 3-5=1)$. Now it is not difficult to get 4 minutes, since $4=1+3$.

Now try on your own using a three-minute and ten-minute clock to get all the whole
