---
id: 1988-8-chukova-raspredelenie-puassona-a0a70b83
issue: kvant_1988_8
year: 1988
number: "8"
title: Poisson distribution
authors:
  - Чукова Ю. П.
rubric: raznoe
page_first: 17
page_last: 19
page_labels: 15-17
tag: UNBE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 78a20b9e94cc961ecba515a7e723cda49633ba7caf65e354846652774ce87545
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/03_chukova-raspredelenie-puassona-a0a70b83.md
source_content_sha256: 0766eced676fac303cdf37f47b4b3590f3c09933de5c6dbdf47aec5ba4d16500
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 15⟧

POISSON DISTRIBUTION

Candidate of Physical and Mathematical Sciences
Y. P. CHUKOVA

1837 Paris. By Budvaar Saint
Michel is a professor at the Sorbonne,
member of all scientific societies and academician
of Europe and America Simeon Denis
Poisson. He's thinking about his last
work. Should I report her?
korists? or limit ourselves to mathematicians? The work was called “Research
information about the likelihood of criminal convictions
new and civil processes."
The material was legal, and the law
mathematical... The law described
the role of chance in litigation
processes in France in the 19th century.

Poisson knew the great generalization
the power of mathematical laws.
But even he did not suspect that he had received
the law given to them, which will be called ra-
Poisson limit, after one and a half
century will become a research tool for
scientists of various specialties
sta.

We will get acquainted with the distribution
Poisson in a simple and understandable way
example.

In the dining room they made a compote of $N$ cherries and poured it into $n$ glasses
(stirring thoroughly for the purity of the experiment). Question: what is the probability
Is it true that there are no cherries in this glass?

We will assume that all options
distribution of cherries into glasses
equal rights. Since each of
$N$ cherries can hit any of the $n$
glasses, the total number of options is equal to
but $n^N$ (n options for 1st cherry,
n - for the 2nd, etc.). Number of options
when there are no cherries in a given glass
palia, equal to $(n-1)^N$ (each cherry
“selects” any of the others $n-1$
glasses). Therefore, the required probability
probability $R_0$ of what will not be in the glass
cherries, is equal to $(n-1)^N/n^N$, i.e.

POISSON

⟦folio 16⟧

We can also derive a general formula for the limiting (at large $N$) probability $P_k$ of finding $k$ lice ($k=0, 1, 2, \dots$) in a glass:

$$P_k \approx \frac{\lambda^k e^{-\lambda}}{k!},$$

where $k! = 1 \cdot 2 \cdot \dots \cdot k$ at $k \geqslant 1$ and, by definition, $0! = 1$.

In general, suppose that in an experiment with random outcomes some quantity changes that takes on non-negative integer values. It is said to have a Poisson distribution if it takes the value $k$ with probability $p(k; \lambda) = \lambda^k e^{-\lambda}/k!$ (see (2)). figure 1 shows graphs of the probabilities $p(0; \lambda), p(2; \lambda)$ and $p(4; \lambda)$ as functions of $\lambda$. When $\lambda$ is fixed, the values ​​of $p(k; \lambda)$ are depicted as figure 2 (for $\lambda=10$).

The Poisson distribution occurs in a wide variety of situations. We will give only two typical examples of its use. The first is from physics. Experiments show that during the distribution of matter, the number of $\alpha$-particles emitted over a certain period of time $t$, with very high accuracy, obeys the Poisson distribution with an average value $\lambda t$, where $\lambda$ is a parameter characterizing the intensity of radiation. This example allows us to demonstrate how dangerous it is to disguise common sense. Indeed, at first glance it seems that the probabilities are generated

$$P_0 = \left(1 - \frac{1}{n}\right)^N.$$

Let $\lambda = \frac{N}{n}$ be the average number of lice in a glass, then

$$P_0 = \left(1 - \frac{\lambda}{N}\right)^N.$$

For large $N$ (and fixed $\lambda$) this value is approximately equal to $e^{-\lambda}$. So,

$$P_0 \approx e^{-\lambda}.$$

(1)

Similarly, we can calculate the probability $P_1$ that there will be exactly one cherry in a glass: this cherry can be selected in $N$ ways, and the remaining $N-1$ cherries must be distributed among $n-1$ glasses, therefore,

$$P_1 = \frac{N(n-1)^{N-1}}{n^N} = \frac{N}{n-1} \left(1 - \frac{\lambda}{N}\right)^N \approx \lambda e^{-\lambda}.$$

*) Indeed,

$$\lim_{N \to \infty} \left(1 - \frac{\lambda}{N}\right)^N = e^{\lim_{N \to \infty} N \ln(1-\lambda/N)},$$

and the limit in the indicator is equal to

$$\lim_{N \to \infty} N \ln \left(1 - \frac{\lambda}{N}\right) = \lim_{N \to \infty} \lambda \frac{\ln(1-\lambda/N) - \ln 1}{\lambda/N} = -\lambda \lim_{h \to 0} \frac{\ln(1+h) - \ln 1}{h} = -\lambda,$$

because the last limit is equal to an arbitrary function $\ln x$ for $x=1$, i.e. 1.

⟦folio 17⟧

10 α-particles in 5 seconds or 2 α-particles in 1 second must coincide. However, this is not true. Let us assume, for example, that the counter registers a particle with an average frequency of λ=1 particle per second. Then the number of particles registered in 1 second obeys the Poisson distribution with parameter 1, and in 5 seconds - with parameter 5. Therefore, the first probability is equal to

$$p(10; 5) = \frac{5^{10}e^{-5}}{10!} \approx 0,018,$$

and the second -

$$p(2; 1) = \frac{1^2 \cdot e^{-1}}{2!} \approx 0,18.$$

We see that these probabilities are not only not equal, but differ by a factor of 10!

The second example is from the life of viruses, more precisely bacterial viruses called bacteriophages, which were discovered in 1915. Bacteriophages are bacterial parasites. They are released only in bacterial cells. One of the most studied phages, phage T2, is released from Escherichia coli. The infection process occurs as follows. During Brownian motion, the phage encounters a bacterium and attaches to it at the end of its “tail” (Fig. 3). After attachment, the virus shell contracts, the core penetrates the cell surface and the phage DNA enters the bacterium. After about 20 minutes at a temperature of 37°, the bacterium is destroyed, and almost phages appear together with one phage. Rare level!

The death of bacteria under the influence of phages can be observed almost visually. The fact is that the nutrient solution with bacteria *E. coli* appears cloudy - the bacteria are about 1 micron in size, which is enough to scatter visible light. But if in a test tube with *E. coli* add one single T2 phage and press for 6-8 hours, then the solution in the test tube will become cloudy. The only explanation. Phage T2, rapidly multiplying, destroyed all *E. coli*, and there are no objects left in the test tube that can scatter light, since the size of the phages themselves (about 200 nm) is too small for this. All this is interesting, but you are right to ask what the Poisson distribution has to do with it.

It turns out that in an unexpected way it helps solve an important problem for molecular biology - determining the concentration of viral particles in a solution. In our example with compote, the analytical problem (find the average number of cherries in a glass) is solved simply: you can re-read the cherries in several glasses and divide their number by the number of glasses. But viruses are not re-read like vermin! And here we remember formula (1), which connects the probability of the absence of particles (whether lice or virus) in a certain volume of the composition containing them (in a glass or in a test tube) with their average number. Let's take, say, 100 test tubes with bacteria in a nutrient medium and add 1 ml of virus solution to each. After some incubation time, we count the number of test tubes that remain cloudy. Let's say there were 38 of them, and the other 62 glasses were clear. This means that not a single phage got into 38 test tubes, or phages are defrosted much faster than bacteria (over the elapsed time they destroyed all the bacteria in 62 test tubes). The proportion of turbid tubes gives an approximation of the probability value equal to
