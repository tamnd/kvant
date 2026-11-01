---
id: 1983-5-zaydel-obman-ili-zabluzhdenie-1bb916ae
issue: kvant_1983_5
year: 1983
number: "5"
title: Deception or delusion?
authors:
  - Зайдель А. Н.
rubric: osnovnye-stati
page_first: 26
page_last: 29
page_labels: 24-27
tag: KT16
lang: en
source: kvant_digital
extraction: vision
content_sha256: 15dcbabcd5c15614cf175a73b426a348116bf16c9664e6f7fe50386aedd5b968
prompt_sha256: draft-1
translated_from: content/ru/1983/05/articles/08_zaydel-obman-ili-zabluzhdenie-1bb916ae.md
source_content_sha256: 6a86551d9c571ae101b008550db578434a290af24149b9fe276508058f1a23b9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Deception or delusion?

(On one way to calculate π)

Doctor of Physical and Mathematical Sciences
A. N. ZAIDEL

How to determine the experimental numerical value of π? Probably the easiest way is to take a thread, use it to measure the length of a circle of known diameter and divide the result by the length of the diameter. It turns out that you can approximately find π using the equation... and probability theory. This method was invented by the French naturalist Jah. L. L. Buffon (1707-1788)*. Subsequently, Buffon's experiment was repeated more than once to test some of the conclusions of the theory of probability (or rather, their applicability in practice). This did not happen without one curious incident, which we will discuss later. But first, let's tell you what it is

Buffon's experience

To implement it, you need little: a flat horizontal surface with parallel equidistant lines and lines marked on it. The distance between the straight lines h and the illumination length l must satisfy the correspondence l≤h (Fig. 1). We will randomly throw the illu above such a surface, giving it a slight rotation each time so that the illu falls freely from a height

*) See also about this in the note by A. Vilenkin “The number “pi” and the theory of probability” (Kvant, 1977, No. 5).

Fig. 1.

⟦folio 25⟧

the implementation of one or another event in a fairly long series of experiments. Therefore, an approximate probability value can be obtained empirically by calculating the corresponding frequency. (The exact mathematical expression of the tendency of frequency observed in an experiment to some limiting value (probability) is the so-called law of large numbers, proven in its simplest form about three hundred years ago by Jacob Bernoulli.) On the other hand, the methods of probability theory in many cases make it possible to use experimental conditions to calculate probabilities theoretically.

At the end of the article we will show how Biofon's problem of finding the probability $p$ that the game will cross one of the lines is solved. The answer turns out to be replaceable:

$$p = \frac{2}{\pi} \frac{l}{h}!$$

And since the intersection frequency $m/n$ is approximately equal to this probability, for an approximate calculation of $n$ we have the formula

$$\pi \approx \frac{2l}{h} \frac{n}{m}.$$

(1)

What did the experiments show?

The accuracy of the approximation in formula (1) will be higher, the larger $n$, and at first glance it seems that by throwing the needle many times, you can get the exact angular value $n$. Try this experiment and you will easily see that it is quite easy to obtain the value 3.1 for $n$ using this method. Reliably obtaining the next decimal place - 4 - is already much more difficult.

In the past century, when the theory of probability was often viewed as a semi-serial science, such experiments had more significance and weight were carefully carried out by many scientists. Below is a table taken from the course on probability theory by B.V. Gnedenko.

The first column gives the names of the scientists who threw the needle, the second - the year of the experiment, the third - the number of throws from which $n$ was determined, and the last - the

the value obtained as a result of experiments. The bottom row of the table for a given value is $n$ with eight characters.

Let us compare the experimental values ​​with this number. The numbers in the first two lines differ from $n$ by 0.01–0.02. Fox's number is only 0.0003 larger than $n$, a surprising result, but Lazzarini's number is only 0.0000002 off the true value. This is already a real miracle, and miracles only happen in fairy tales.

The inevitability of mistakes

Let's try to figure out what makes us surprised and, frankly, not believe in the result of the latest experience. There are several such reasons. The first is measurement errors. In order to obtain the exact value of $n$ from (1), we need to know exactly the quantities $h$ and $l$, or rather, their ratio. We can only obtain this data as a result of measurements. And measurement errors will contribute to the error in determining $n$. Let's evaluate these errors. Let the needle length be 50 mm, the same distance between the lines. Using conventional measuring instruments, such as a caliper or a ruler with a nonus, it is relatively easy to change both desired lengths with an accuracy of 0.1 mm or 0.2%. We see that for any of the lengths we need, a distance of 0.1 mm is the limit of measurement accuracy*). However

*) In a small number of experiments (approximately 0.1-0.2% of the total number of throws), the distance from the end of the needle to the straight line will be less than 0.1 mm. In such cases, the eye does not know whether the intersection will occur or not. This circumstance may introduce its own truth, which is small compared to other errors.

⟦folio 26⟧

However, using more advanced instructions, all lengths can be changed with an error of 0.01 mm. This is already a practical limit - it is extremely difficult to reduce the error to 0.001 mm in such an experiment - a change in the temperature of the needle or the surface on which the lines are drawn by 1-2 degrees will already cause a change in size by about 0.001 mm. Deformation of the needle when it hits a surface, abrasion of its ends, deformation of the surface itself - all these principles make carrying out an experiment to an error level of 0.001 mm unrealistic. Therefore, even without making more detailed estimates, we can confidently say that in the experiments described, the number π could be determined with an error that did not change 0.2-0.02%. That is, in experiments with a simple changing instrument (with which they are usually carried out), one can expect the value π = 3.141 ± 0.006. With very carefully performed experiments, you can expect a result of π = 3.1416 ± 0.0006. And it is just as impossible to obtain values ​​for π from such experiments with an error of the eighth significant digit, just as it is impossible to cock a match on scales designed for weighing railway cars - slick loads are tools.

Of course, with any change, you should evaluate its accuracy and add the result with the number of characters that corresponds to it. If we get for each value A as a result of changes and calculations the value A = 2.474329, and the accuracy of the changing device is 1%, then we should write A = 2.47, cross out all subsequent numbers that reflect only the accuracy of our computing device (modern, even the simplest microcalculators always give 6-8 decimal places), and not the result of real experience. To write down in such cases all the signs that can be counted is a complete attempt to deceive oneself and others, exaggerating the accuracy of the experience.

However, there is no need for great precision changes at all:

In plan it is enough to change the lengths with an error of 0.1 mm. The reason is that accuracy is determined by the industry with perfect perfect others. The nature of obstruction is “probabilistic” - the inability to produce a sufficient number of throws so that the approximate equality (1) is reliably fulfilled with a relative error of less than 0.01. You can find out at what speed the difference |$\frac{m}{n}-p$| kills. between the frequency of a given event in a series of n trials and its probability given the occurrence of a number of trials. It turns out that in order to increase the accuracy of the approximate equality $\frac{m}{n} \approx p$ by N times, the number of tests must be increased by $N^2$ times, in other words, the error in the approximate determination of the probability is inversely proportional to the square root of the number of tests. A more accurate calculation for Buofon's experiment shows that for $h \approx l$ the error α of the value of π, which more or less reliably will not be exceeded with n throws of the needle, can be estimated as follows:

$$\alpha \approx \sqrt{\frac{5}{n}}.$$

If we require that α be no more than 0.02, then from formula (2) we obtain $n \approx 12000$. In the experiments listed in the table (except for Fox's experiment), from 3000 to 5000 throws were carried out. In accordance with (2), α turns out to be somewhat larger, that is, for example, 0.025–0.030. This is in good agreement with the results of Wolf and Smith. An example of the same error is obtained with errors in length changes of the order of 0.1 mm. Consequently, there is no reason to change them more precisely, since errors in each link of the test should not exist - there is no point in changing the length of the needle with an accuracy of 0.001% if the error associated with a limited number of tests leads to an error in the final result of 0.2%-0.3%. Selecting the number of throws from 3000 to 5000

⟦folio 27⟧

quite justified. However, the test should take about 5s (try throwing faster). In this case, 10,000 throws will take approximately 14 hours, that is, two full working days. If we want to get a result ten times more accurate, then, in accordance with the “law of 1/√n,” we need to throw 100 times longer—200 days, which is already a long time.

But in order to get Lazzarini’s result, the error of which is only 0.0000002, you need to throw the needle for about 4,000,000 years! (Of course, with the corresponding absolutely unrealistic accuracy of measuring all lengths.) So, having started his experiment in 1901 and stopping until the middle day, Lazzarini would have been as far from the result he published as on the day the experiment began.

Let us point out another source of errors in experiments of this kind. In order for the probability of intersection to really be equal to the theoretical value $p=2l/\pi h$, all positions of the fallen needle relative to the lines on the surface must be completely equal, that is, none of them should occur more often than others (we will give a more precise formulation of this requirement when calculating $p$). There is every reason to believe that this is difficult to achieve in a real experiment.

In connection with all that has been said, it should be noted that the number of characters given in the table is unreasonably large. It was necessary to leave 3.16 in the first two lines of the quadruple column, and 3.14 in the third.

And yet:
deception or delusion?

How can one explain the result obtained by Lazzarini? It is difficult to imagine an attempt to create deception. When Lazzarini was throwing the needle, the law of large numbers was well known and the calculations given here could be done by any mathematician. Probably, none of the scientists ever took this result seriously, although it was published more than once. When starting experiments, Lazzarini had to know in advance what could be expected from them. And, even having received the number he gave as a result of argumentative exercises, he should not have published such a fantastic result without confirming it with a repeated series of experiments. It seems to me that he really wanted to get something that no one else had been able to get before him. Such a list of strong desires sometimes captivates the researcher and makes him mistake what he wants for reality.

One can, of course, assume that, when throwing the needle, he calculated l after each test and stopped the experiments after 3408 throws precisely because after just such a number of tests he accidentally received the number he gave. Of course, even out of 10,000 tosses, it is very unlikely to obtain at least once values ​​with an accuracy of $2 \cdot 10^{-7}$ (the probability of this approximate is $10^{-3}$), but still the event could have happened with such a probability. If the matter was truly so, then Lazzarini does not deceive others, but deceived himself. Unfortunately, this also happens.

We will be satisfied that, although the result of Lazzarini’s experiment did not confirm the correctness of the conclusions of the theory of probability (and rather even came into conflict with it, if it is always accepted), he gave us another reason for discussing how the parties should treat the results obtained in the experiment and their statistical processing.

Solution of Buffon's problem

It remains for us to explain how the probability of intersection of a needle and one of the parallel lines is calculated in Buffon’s experiment. Let us denote the distance from the center of the needle to the nearest straight line by $a$ ($0 \leq a \leq h/2$), and the angle between the needle and the straight line by $\varphi$ ($0 \leq \varphi \leq \pi/2$). Then, as is clear from figure 1, $a$, the conditions for the intersection of the needle and the straight line can be
