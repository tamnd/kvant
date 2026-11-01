---
id: 1986-1-tulaykov-vyichislenie-binomialnyih-koeffitsientov-na-kalkulyatore-bz-34-8fad7bb5
issue: kvant_1986_1
year: 1986
number: "1"
title: Calculation of binomial coefficients on the BZ-34 calculator
authors:
  - Тулайков А. И.
rubric: smes
page_first: 25
page_last: 25
page_labels: "23"
tag: RZKD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7dd8ae19e28a1230c65de97f62a4463bafa30bc565c359b424f460413beab7b5
prompt_sha256: draft-1
translated_from: content/ru/1986/01/articles/07_tulaykov-vyichislenie-binomialnyih-koeffitsientov-na-kalkulyatore-bz-34-8fad7bb5.md
source_content_sha256: 30fbe21ac83a92332dbff30341653dcfd0d3b328b03cb3593cd9cbb6b355fccb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

exponentiation and reduction of similar terms, that is, the sum of the probabilities of anagrams of the word kkkzz.

Interestingly, the case “2 red and 3 yellow” and “2 red, 2 yellow and 1 green” have the same probability

$$\frac{5!}{2!3!} \left( \frac{1}{2} \right)^3 \left( \frac{1}{3} \right)^2 = \frac{5!}{2!2!1!} \left( \frac{1}{2} \right)^2 \left( \frac{1}{3} \right)^2 \left( \frac{1}{6} \right) = \frac{5}{36}.$$

(These are the most likely combinations of 5 peppers at the probabilities we have chosen.)

Tasks

18. All three edges of a 6x6x6 cube emanating from vertex A were divided in the ratio 3:2:1, counting from vertex A, and planes parallel to the edges were drawn through the division points, cutting the cube into 21 pieces (Fig. 5).

a) How many of them will be 3x2x1 blocks?

b) How many more pieces and what kind will there be? What are their volumes?

b) Is there a connection between this problem and the pepper problem?

19. The machine composes 6-bead okerelles by randomly selecting them from a large pile of black, white, red and blue beads, shifted in a 1:2:3:4 ratio. What is the probability in such an environment

a) all beads are blue;

b) everything is the same color;

b) there will not be a single red bead;

d) will there be beads of all four colors?

d) Which okerelles will you come across most often?

e) What should be the ratio of beads in a large pile so that the most common beads with 2 red, 2 black, one white and one blue beads are found?

20. Let the probability of the sandwich falling with butter and visas be different 3/4. A random event occurred: a tray with seven sandwiches overturned. What is the probability that exactly k sandwiches will fall butter vis (for each k=0, 1, 2, ..., 7)?

Raise to the power (p+q)^7 and subtract each one year at p=3/4, q=1/4. You can use a microcalculator to calculate the coefficients. (See Appendix.)

Biominal coefficients

Above, we almost did not touch upon the simple and, please, the most important case of two letters. The coefficients of the polynomial (a+b)^n have a special designation C^k_n, and the formula (a+b)^n = C^0_n a^n + C^1_n a^{n-1} b + ... + C^n_n b^n

called Newton's biome formula. We know that C^k_n - the number of words of n letters, including k letters and n-k letter a - can be found using the formula

$$C^k_n = \frac{n!}{(n-k)! k!} = \frac{n(n-1)...(n-k+1)}{k!}.$$

For example,

$$(a+b)^4 = a^4 + 4a^3 b + 6a^2 b^2 + 4ab^3 + b^4,$$

because

$$C^0_4 = C^4_4 = \frac{4!}{4!0!} = 1,$$

$$C^1_4 = C^4_3 = \frac{4!}{3!1!} = 4,$$

$$C^2_4 = \frac{4!}{2!2!} = 6.$$

Biominal coefficients - numbers C^k_n - arise in a variety of problems in biomantorics, algebra, geometry, mathematical analysis, and probability theory. They are connected by polynomial red identities; for example, from the equality C^k_n + C^k_{n-1} = C^k_{n+1} (see Problem 5) it follows that for all natural n and k, 0≤k<n,

$$C^k_n + C^k_{n+1} + ... + C^k_n = C^k_{n+1}.$$

(for k=1 this is the formula with which we started the article). These remarkable numbers will be discussed in more detail in one of the next issues of the magazine.

Literature

1. V. A. Uspensky. Pascal's triangle. M.: Nauka, 1979.

2. M. I. Bashmakov, V. M. Bekker, V. M. Golkhovoy. Mathematics assignment: Algebra and analysis. M.: Nauka, 1982.— (Series: Biblutechka «Kvant», issue 22)

3. A. N. Kolmogorov, I. G. Zhurbenko, A. V. Prokorov. Introduction to probability theory. M.: Nauka, 1982.— (Series: Biblutechka «Kvant», issue 23)

4. D. Knut. The art of computer programming. M.: Mir, 1976, vol. 1.

5. F. Mosteller. Fifty challenging probability problems with solutions. M.: Nauka, 1985.

Appendix: Calculation of biominal coefficients using the B3-34 calculator.

For large n, calculating biominal coefficients manually is a very difficult task. Below is a program for the calculator B3-34*), which allows you to calculate the coefficients C^k_n for any n≤334 and all k≤n (in this case, the answers are obtained for n≤28; for large n the program gives approximate answers**)).

*) Minor modifications allow the program to be adapted to the MK-54 and MK-61 models.

**) The upper limit is 28 for n and the accuracy of the approximate values ​​of the coefficients of the polynomial is higher than for the program from the well-known reference books of V.P. Dyacon and A.N. Tsvetkov and V.A. Epanchnikov. (Note ped.)
