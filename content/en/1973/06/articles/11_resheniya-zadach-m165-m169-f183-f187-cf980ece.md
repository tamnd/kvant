---
id: 1973-6-resheniya-zadach-m165-m169-f183-f187-cf980ece
issue: kvant_1973_6
year: 1973
number: "6"
title: Solutions to problems M165—M169; F183—F187
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 54
page_labels: 44-52
tag: F68Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: e9362232f57b4d935dea03bb3cc4911b797f5d5dbd4db357c4c94daad6c38872
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/11_resheniya-zadach-m165-m169-f183-f187-cf980ece.md
source_content_sha256: c27ac7d37c7345d913d571d5d5fca2f9f5cdea260565c95707a66b7cdac3c235
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Problem solutions

M165. On the circle there is a set F power, consisting of 100 duets. It is known that for any rotation R of the circle of the set R (F) we have a common power with F. (In other words, for any α from 0° to 180° in the set F we can indicate two limits, the distance of the other from the other by α.) What is the smallest sum of lengths we can use for the volume of 100 duos forming the set F? What will be the answer if the number is not 100, but n?

Let's solve the problem for n arcs.
Let us denote the sum of the lengths of n arcs forming the set F by S*).
S can be arbitrarily close to $\frac{180^\circ}{n}$. It is enough to give an example: we place (n−1) arcs, the length of each of which is equal to $\frac{a^\circ}{n}$ so that the centers of any two neighboring ones are separated by $\frac{180^\circ}{n}$, and behind the (n−1)th we place the nth arcs with length $\frac{180^\circ}{n}$ so that the distance between their nearest ends is equal to $\frac{180^\circ}{n}$.

It is easy to check that the specified system

*) Since we are only interested in the relative arc length, we will measure it in degrees.

Fig. 1.

ma friend satisfies the conditions of the problem. With an appropriate choice of $a^\circ$, the sum of the lengths of the arcs will be as close as the angle to $\frac{180^\circ}{n}$.

If we consider a point on a circle to be an arc of zero length, then by replacing all arcs in the example except the last one with points, we obtain a set F with the sum of arc lengths equal to $\frac{180^\circ}{n}$ (Fig. 1).

Let us prove that the sum S of arc lengths cannot be less than this number. Let's imagine that we have two copies of our circle, on which the same n arcs are placed. Let's rotate one of the circles by an angle φ, 0 < φ < 360°. Let us consider the set $U_{ij}$ of all such values ​​of φ for which, with such rotation i−j, the arc of the rotating circle intersects with the jth arc of the fixed circle. Let’s draw a separate “control” circle (with the initial point φ = 0 (Fig. 2) selected on it) and mark the sets $U_{ij}$ on it for all i, j from 1 to n. It is clear that $U_{ij}$ is an arc with length equal to the sum of the lengths of the i−j and j−th arcs.

Fig. 2:

The marked sets $U_{ij}$ must fill the entire “control” circle, since with any rotation some two arcs of our set must intersect, therefore the sum of the lengths of all $U_{ij}$ is not less than 360°. On the other hand, this sum is equal to 2n. S, since each arc of the set appears in the sum 2n times.

From this we obtain that $S \geq \frac{360^\circ}{2n} = \frac{180^\circ}{n}$.

It is easy to see that the inequality must be strict (if individual points are not considered arcs), since any two regions $U_{ii}$ and $U_{jj}$ have a common section containing the beginning of the cutoff.

Yu. P. Lysov

M166. a) Single-class schoolchildren went on two Murista hikes in the semester. In the first approach, boys were less than 2/5 of the total number of participants in this trip, and in the second, less than 2/5. Prove that in this class boys make up less than 4/7 of the total number of sections, if it is known that

⟦folio 45⟧

Fig. 3.

Each of the students went on at least one trip.

6) Let the boys in the i-th hike ($i = 1, 2, \dots, n$) make up $\alpha_i$ hours of the total number of participants in this hike. What is the longest time the boys can make up at a general meeting of all tourists (everyone who has been on at least one of the hikes)?

a) In the first trip, as can be seen from the condition, the number of boys was less than 2/3 the number of girls participating in this trip. Moreover, it is less than 2/3 of the total number of girls in the class. There are also boys - participants in the second trip - less than 2/3 of the total number of girls in the class. Since each student was on at least one trip, the total number of boys in the class is less than 4/3 the number of girls. Consequently, boys in this class make up no more than 4/7 of the total number of students.

Using the notation that is clear from Fig. 3 ($b$ and $g$ are the first letters of the English words boy and girl), our solution can be written as follows.

According to the condition $5b_1 < 2(b_1 + g_1)$, we open $3b_1 < 2g_1 \leq 2g$. Tono also proves that $3b_2 < 2g_2 \leq 2g$. Since $b \leq b_1 + b_2$, we get $3b \leq 3b_1 + 3b_2 < 4g$, open $7b < 4(b + g)$.

6) This problem can be solved in a similar way. Let $b_i$ and $g_i$ be the number of boys and girls in the i-th campaign, $b$ and $g$ be the number of boys and girls at the general meeting. Then, by condition $b_i = \alpha_i(b_i + g_i)$, we open $(1 - \alpha_i)b_i = \alpha_i g_i \leq \alpha_i g$, so if $\alpha_i < 1$, then $b \leq \sum_{i=1}^{n} b_i \leq \sum_{i=1}^{n} \left(\frac{\alpha_i}{1 - \alpha_i} g\right) = g \sum_{i=1}^{n} \frac{\alpha_i}{1 - \alpha_i},$

from where $b \left(1 + \sum_{i=1}^{n} \frac{\alpha_i}{1 - \alpha_i}\right) \leq (b + g) \sum_{i=1}^{n} \frac{\alpha_i}{1 - \alpha_i}$

(here $\sum_{i=1}^{n} - \text{знак суммирования}$:

$$\sum_{i=1}^{n} x_i = x_1 + x_2 + \dots + x_i + \dots + x_n).$$

So, we have proven that if $\alpha_i < 1$ for all $i$, then the boys will make up no more than $\frac{c}{1 + c}$ of the total number of hike participants, where $c = \sum_{i=1}^{n} \frac{\alpha_i}{1 - \alpha_i}$.

We still need to make sure that this limit can be reached. This requires that all written inequalities be converted into equalities. It is easy to understand that this will be so if the girls in all campaigns were the same, and the boys were different, that is, each of the boys was on only one campaign. Let us show that this can happen for any $\alpha_i$. Let $\frac{\alpha_i}{1 - \alpha_i} = \frac{m_i}{N}$ (the numbers $\alpha_i$ and therefore $\frac{\alpha_i}{1 - \alpha_i}$ are rational; we can write $\frac{\alpha_i}{1 - \alpha_i}$ as fractions with the same value). Then, if in the i-th campaign there are $N$ (same) girls and $m_i$ (different) boys, then $M = \sum_{i=1}^{n} m_i$ boys and $N$ girls will come to the meeting; the ratio of $M$ to $N$ is exactly $c$, and the ratio of $M$ to $M + N$ is exactly $\frac{c}{1 + c}$.

Let us return to problem a) as an example.

If the number of trips is $n = 2$ and $\alpha_1 = \alpha_2 = \frac{2}{5}$, then the exact estimate should be the number $\frac{c}{1 + c}$, where $c = \frac{2}{5} + \frac{2}{5} + \frac{2}{5} = \frac{2}{3} + \frac{2}{3} = \frac{4}{3}$, that is, the number $\frac{c}{1 + c} = \frac{4}{7}$. Here $\alpha_1 = \frac{2}{3}$ ($i = 1, 2$), if in each trip there were 3 (same) girls and 2 boys (in the first trip - one, in the second - others), then there are only 7 participants, 4 of them are boys. (If you think that 7 is too small a number of students in the class, you can multiply all the numbers at the same time: 3, 2, 7 and 4, say, by 4 or 5; since only their ratios, this will not affect the result). Thus, the number 4/7 in the conditions of problem a) cannot be replaced by a smaller one.

⟦folio 46⟧

Returning again to Problem 6), we note that if $\alpha_j = 1$ for some $j$ (at least for one), then we can no longer give any (other than 1) upper estimate for the share of boys in the general meeting (without knowing how many participants are in each position). Indeed, if, regardless of other campaigns, we take the number of participants in the $j$th campaign to be very large (all of them are boys), then the share of boys at the general meeting can be made as close to 1 as desired.

M167. Prove that in any arithmetic progression $a, a + d, a + 2d, \dots, a + nd, \dots$, composed of natural numbers, there are infinite polynomials whose decomposition into prime factors includes monostmi one and the same prime numbers.

Many readers, as the letters show, did not understand the terms of the problem. Let's look at it in more detail.

As is known, any natural number $N$ can be factorized into prime factors:

$$N = \frac{\alpha_1}{\alpha_2} \frac{\alpha_r}{p_1 p_2 \dots p_r},$$

and such a decomposition is unique. In problem M167 it is required to prove that in any arithmetic progression from the natural numbers one can choose such an infinite set of terms that the prime factors $p_1, p_2, \dots, p_r$ in the expansion of each of them are the same for all these terms (and the powers $\alpha_1, \alpha_2, \dots, \alpha_r$ can, of course, be different). Let us now move on to solving the problem.

First of all, we note that if the first term $a$ and the difference $d$ of the progression have a common greatest divisor $q > 1$, then all terms of the progression can be divided by $q$. It is clear that it is enough to solve the problem for this new progression, since if some members of the new progression have the same prime factors. So, we can assume that $a$ and $d$ are prime. The following lemma is true: if $HOД(a, d) = 1$, then there is a maxim $k$ such that $a^k - a$ is divisible by $d$ (we will recall below how this is proved).

Then for any integer $m > 0$

$$a^{km} - a = (a^k - a)(a^{k(m-1)} + a^{k(m-2)} + \dots + 1)$$

is divisible by $d$, that is, $a^{km} - a = nd$, where $n$ is an integer. Thus, for every natural number $m$ the number $a^{km} = a + nd$ is included in our progression. Thus, there is an infinite progression polynomial, which is a certain degree of its first term $a$. It is clear that all these terms have the same prime factors.

Proof of the lemma. Consider the sequence of numbers $a, a^2,$

Fig. 4.

$a^3, \dots$. There are two numbers in it that give the same remainder when divided by $d$. Let it be $a^s$ and $a^t$ ($s < t$). Then their difference $a^t - a^s = a^s (a^{t-s} - 1)$ is divided by $d$. Since $a$ and $d$ are prime, then $a^{t-s} - 1$ is divisible by $d$, therefore $a^{t-s+1} - a$ is divisible by $d$, that is, $k$ can be taken equal to $t - s + 1$.

This reasoning has already been given in the article “Fermat’s Little Theorem” («Kvant» No. 10, 1972). It was also said there that in the role of $k$ we can take the number $\varphi(d)$ - the number of numbers less than $d$ and take primes with it. ("Euler's theorem": $a^{\varphi(d)} - 1$ is divisible by $d$ if $HOД(a, d) = 1$).

M168. In a regular truncated paramda (Fig. 4), one can K be the midpoint of some string $AB$ of the upper base, $L$ be the midpoint of some string $CD$ of the lower base. Prove that the projections of the segments $AB$ and $CD$ onto the line $KL$ are equal in length.

If $a$ and $b$ are two segments (on the plane or in space), then we will denote the projection of the segment $a$ onto the line on which the segment $b$ lies by $pr_ba$. Then (Fig. 5)

$$pr_ba = a \cos \alpha,$$

where $\alpha$ is the angle between the lines on which

⟦folio 47⟧

The segments $a$ and $b$ lie. (In this and the following formulas $a$, $p_r a$, etc., the lengths of the corresponding segments are introduced.) The named angle between straight lines does not exceed $\pi/2$, therefore $\cos \alpha \geq 0$. From (1) the equality follows
$$a p_r a = b p_r a,$$
(2)
which will be useful to us when solving the problem.

Let us denote by $P$ the center of the upper, and by $Q$ the center of the lower bases of the line. We will prove the following fact, which is somewhat more general than the statement problem M168 we need.

Let the planes of two similar equilibrium triangles ABP and CDQ with vertices $P$ and $Q$ be redistributed to the segment PQ (and, thereby, parallel to each other). Let us denote the segment connecting the midpoints $K$ and $L$ of the bases AB and CD by s. Then (Fig. 6).
$$\pi p_s k = \pi p_s l.$$
(3)
Using (2), together with (3) we can prove the following equality:
$$k \pi p_k s = l \pi p_l s.$$
(4)
Now let us take advantage of the fact that, as follows from (1), the length $p_r a$ does not change when the segments $a$ and $b$ are transferred in parallel. Therefore, we can project the segment $k = AB$ onto the plane of the triangle CDQ and get:
$$\pi p_{A' B'} K' L = \pi p_{A' B'} K L = \pi p_{AB} K L =$$
$$= \pi p_k s,$$
(5)

Fig. 7.

where $A', B'$ and $K'$ are the projections of points $A, B$ and $K$ onto the CDQ plane (Fig. 7). Thus, we have reduced the problem to the case when both triangles lie in the same plane (and have a common vertex).

If the segments $AB$ and $CD$ are parallel, then equality (4) is obvious, since both projections are equal to zero. If these segments are not parallel, then we get:
$$\frac{k}{l} = \frac{A' B'}{CD} = \frac{Q K'}{QL} = \frac{\sin \angle QL K'}{\sin \angle QK' L} =$$
$$= \frac{|\cos \rightarrow K' LC|}{|\cos \rightarrow LK' B'|} = \frac{\pi p_l s}{\pi p_k s},$$
whence follows (4).

M169. Let $k < n$ be natural numbers. The distance of the numbers 1, 2, 3, ..., $n^2$ in the table is $n \times n$ max, so that in each row the numbers or in ascending order and at the same time the sum of the numbers in the $k$ column is $a$) the smallest; b) the greatest.

Let's first solve problem a).

If we arrange the numbers as shown in Table 1, $a$ - first fill in the first $k$-columns, line by line, numbers from 1 to $kn$, and then leave the numbers to fill in the last ($n - k$) columns (as an angle, as long as the condition of increasing numbers in each line is met) - then the sum of the number

Table 1a

$$\begin{array}{c c c c c c c c c}
k & 1 & 2 & \dots & k - 1 & k & nk + 1 & \dots \\
k + 1 & k + 2 & \dots & 2k - 1 & 2k & 3k & 3k & \dots \\
2k + 1 & 2k + 2 & \dots & 3k - 1 & \dots & \dots & \dots & \dots \\
(n - 1)k + 1 & \dots & nk - 1 & nk & \dots & \dots & \dots & \dots \\
\end{array}$$

sat in the $k$ capital will be equal to
$$k(1 + 2 + \dots + n) = \frac{kn(n + 1)}{2}.$$
(1)

We will prove that this sum value is the smallest. First we prove that if $a_1, a_2, \dots, a_n$ are numbers of the $k$th column, imitated in ascending order:
$$a_1 < a_2 < \dots < a_i < \dots < a_n$$
(2)
That
$$a_i \geq ki.$$
(3)

Indeed, let us consider the numbers that appear in the same lines where $a_1, a_2, \dots, a_i$ are located, and in the first $k$ columns. From condition (2) and the condition that the numbers in the lines are in ascending order, it follows that these $ki$ numbers do not exceed the number $a_i$. Therefore, among the numbers 1, 2, 3, ..., $n^2$ there are at least $ki$ numbers not exceeding $a_i$. This implies (3). Adding inequalities (3) for all

⟦folio 48⟧

i = 1, 2, ..., n, we get the sum (1) on the right, so
$$a_1 + a_2 + \dots + a_n \geq \frac{kn(n+1)}{2}.$$

Problem 6) can be solved in a similar way, starting with the “largest” numbers and from the rightmost columns. But you can simply reduce it to already solved problem a). Let's replace each number a in the table with $(n^2 + 1 - a)$ and then rearrange the numbers in each row in reverse order. It is clear that this is a one-to-one transformation of a set of tables of numbers 1,2,..., $n^2$ that satisfy the conditions of the problem. In this case, the transformation of each number in the k-th column of the new table $A'$ is equal to the number in the same row and in the $(n+1 - k)$-th column of the old table $A$; therefore, the sum of the numbers in the kth column of the table $A'$ is equal to $n(n^2 + 1) - S$, where $S$ is the sum of the numbers in the $(n+1 - k)$th column $A$. So it is enough to solve problem a) for column number $(n+1 - k)$, and we will obtain a solution to problem 6) for column number $k$; the answer can be written as follows: the maximum sum in the kth column is
$$n(n^2 + 1) - \frac{(n+1 - k)n(n+1)}{2} = \frac{n[(n-1)^2 + k(n+1)]}{2}.$$

Table 16.

| n^2 - (n-k) | n^2 - (n+1-k) + 1 | n^2 - (n+1-k) + 1 |
| :--- | :--- | :--- |
| n^2 - 2(n+1-k) + 1 | n^2 - 2(n+1-k) + 1 | n^2 - 2(n+1-k) + 1 |
| n^2 - 3(n+1-k) + 1 | n^2 - 3(n+1-k) + 1 | n^2 - 3(n+1-k) + 1 |

Table 2a.

| 1 | 2 | 3 | 4 | 25 | 26 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 5 | 6 | 7 | 8 | 27 | 28 |
| 9 | 10 | 11 | 12 | 29 | 30 |
| 13 | 14 | 15 | 16 | 31 | 32 |
| 17 | 18 | 19 | 20 | 33 | 34 |
| 21 | 22 | 23 | 24 | 35 | 36 |

Amount: 84

Table 26.

| 16 | 17 | 18 | 34 | 35 | 26 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 13 | 14 | 15 | 31 | 32 | 33 |
| 10 | 11 | 12 | 28 | 29 | 30 |
| 7 | 8 | 9 | 25 | 26 | 27 |
| 4 | 5 | 6 | 22 | 23 | 24 |
| 1 | 2 | 3 | 19 | 20 | 21 |

Amount: 159

An example (resulting from the transformation $A \rightarrow A'$, $k \rightarrow n+1 - k$ from table 1a) is depicted in table 16. In tables 2, a and 2, b you see more clear numerical examples for $n = 6$ and column number $k = 4$.

N. B. Vasiliev

The correct solutions to some of the problems M160 - M169 were sent to us (the last digit of the solved problem numbers is indicated after the last name): P. Aeronov (Baku) 7; S. Akmertsev (Magnitogorsk) 3; P. Alizadeh (P. Jebrail AzSSR) 2; A. Asasyan (Kamo ArmSSR) 1; B. Ashavsky (Moscow) 3, 6, 7; P. Bankovsky (Uralsk) 3, 4, 7; G. Bayadyan (Kirovokan) 7; O. Bazlaryan (Sisan ArmSSR) 3, 7, 9; S. Belolipetsky (Kirichan) 7; A. Blokh (Kharkov) 2, 3, 6, 7, 9; S. Byshkin (Sevastopol) 3; A. Valkov (Tashkent) 2, 3, 6, 9; A. Volkov (Chelyabinsk) 1; G. Vyshochnaya (Krasnoirsk) 9; L. Generiinovich (Tashkent) 3, 4, 7; S. Geraskin (Voronezh) 7; L. and N. Gotman (Arzamas) 8; A. Gritsoryan (Baku) 1-4, 6-9; V. Griberg (Moscow) 6-9; E. Gurvits (Tashkent) 3, 4; E. Gusev (Pavlograd) 6; Kh. Huseynov (P. Jebrail AzSSR) 1; K. Danilenko (Volgograd) 2, 6; A. Danil (Leningrad) 7; V. Dachtsev (Anjan UzSSR) 7; N. Demchuk (Mytshchina, Moscow region) 8; N. Denisov (Teykovo, Ivanovo region) 3; M. Drachinsky (Tbinis) 3; N. Evlamitsev (Kazan) 2, 3; R. Yeuryan (Hrazdan) 3; V. Zhelezny (Leningrad) 2, 3; S. Zaitsev (Sudai village, Kostroma region) 2, 3; G. Zardaryan (Tbilis) 6, 7; V. Zarubin (Summer Otdykh village, Moscow region) 3; A. Zaslasky (Kalinin) 2—4, 7, 9; S. Zenovich (Tashkent) 3, 4, 7; L. Zilberman (Moscow) 9; E. Iltev (Ordzhonikidze) 7; A. Kaluchkin (Issyk, Alma-Ata region) 4; E. Kaluchina (Grozny) 3; A. Karnaukh (Belgorod) 3; V. Kvastsin (Korkin village, Chelyabinsk region) 3, 8; V. Kovtunets (Shostakov village, Rivne region) 1, 3, 7, 8; S. Konyashin (Saratov) 2, 3, 5; V. Kolosov (Kyiv) 1, 3, 4, 6—8; E. Krivonos (Chusovoy) 3; M. Levin (Vittebsk) 3; M. Leiderman (Mogilev) 3; B. Lembersky (Kyiv) 7; A. Litovchenko (Belokorovich, Zhytomyr region) 3, 4; A. Lukatsev (Moscow) 1-3; G. Lumintser (Chernivtsi) 6, 8; A. Makartsev (Lviv) 2, 3, 9; G. Maloshenok (Lviv) 1, 3, 4, 6-8; I. Medzhivovsky (Moscow) 3; A. Mekhovich (Vladivostok) 3; O. Myasnikova (Uman) 4; A. Nasakin (Kurgan) 3; A. Nikolaev (Moscow) 6, 7, 9; V. Palatnik (Baku) 2, 3, 7, 8; M. Panchenko (Brovary, Kyiv region) 4; P. Paramonov (Moscow) 1—3, 6, 7; M. Pastukhov (Sverdlovsk) 3; E. Pechatnikov 2, A. Pechkovsky (Moscow) 7; Yu. Pinelis (Kzyl-Orda) 3; A. Razulyaev (Klin, Moscow region) 2; A. Rayin (Moscow) 1, 2, 5, 9; S. Rodyunov (Saratov) 1—3, 5; P. Rozhkov (Ryazan) 2, 3; L. Rudtser (Kharkov) 2, 3, 6-8; M. Sapir (Sverdlovsk) 3, 6, 7; V. Sats (Kyiv) 7; A. Sboev (Medvedok village, Kirov region) 2;

⟦folio 49⟧

T. Sedredinov (village of New Kurush, Dag ASSR) 3; S. Sokovki (village Sokovki, Slobodskoy) 7; V. Blind (Frunze) 3; V. Slepenko (Chelyabinsk) 2, 3, 7–9; A. Slesarenko (Rubtsovsk, Altai Territory) 2, 3, 6–9; A. Slinkin (Moscow) 2, 3, 7–9; E. CLOBODOV (Armavir) 4; V. Smolko (Chisinau) 4; Y. Soibelman (Kyiv) 6, 7, 9; Yu. Stetsko (Chernivtsi) 7; A. Strukov (Teykovo, Ivanovo region) 3; S. Tabachinkov (Moscow) 1–4, 6, 8; A. Tatseyev (Baku) 3, 4; Y. Tener (Tashkent) 1, 3, 5–7; E. Turkevich (Chernivtsi) 0–2, 7–9;

F183. A dynamometer, which slides on a smooth horizontal table, mn with a constant force $F = 4$ n. What does the dynamometer show if the mass of its spring is equal to the mass of the body and the dynamometer was adjusted in a horizontal position?

The spring force that arises when the spring is stretched is proportional to the removal of the spring. Therefore, the dynamometer reading $T$ is equal to

$$T = k \Delta L,$$

(1)

where $k$ is the spring stiffness, $\Delta L$ is its elongation.

Under normal conditions, when the dynamometer is stationary, the spring force in any section of the spring is the same, that is, any equal sections of the spring are removed when stretched by the same amount.

This is not the case when moving the dynamometer. Consider the section of the spring that is located at a distance $x$ from the end of the spring attached to the dynamometer body (Fig. 8). The spring force $T_x$ creates an acceleration to the dynamometer body and a spring extension of length $x$. The mass of the spring extension with length $x$ is equal to

$$M_x = \frac{M}{L} x,$$

(2)

where $M$ is the mass and $L$ is the length of the spring.

Fig. 8.

If the acceleration of the dynamometer is equal to $a$, then, according to Newton’s second law, the spring force in the section $x$ can be written as follows:

$$T_x = \left( M + M \frac{x}{L} \right) a.$$

(3)

Since acceleration to the dynamometer is created by the force $F$, then

$$a = \frac{F}{M + M} = \frac{1}{2} \frac{F}{M}.$$

(4)

Therefore

$$T_x = \frac{1}{2} F \left( 1 + \frac{x}{L} \right).$$

(5)

So, the force $T_x$ is not constant and varies from section to section along the spring.

In order to find the elongation of the spring, let us mentally divide the unstretched spring into identical small springs of length $l$, so that the spring force throughout each of them can be considered constant. Let there be $n$ such springs (n» 1). Since the force acting on $n$ series-connected springs causes a deformation $n$ times greater than the deformation of one such spring $^*$), then the stiffness of the short spring is $n$ times greater than the stiffness of the dynamometer spring:

$$k' = kn.$$

We will count the springs from the end of the spring attached to the dynamometer body. The elongation of the $i$th spring is equal to

$$\Delta l_i = \frac{T_i}{k'} = \frac{T_i}{kn}.$$

But, as follows from formula (5),

$$T_i = \frac{1}{2} F \left( 1 + \frac{il}{nl} \right) = \frac{1}{2} F \left( 1 + \frac{i}{n} \right).$$

Therefore

$$\Delta l_i = \frac{1}{2kn} F \left( 1 + \frac{i}{n} \right).$$

The spring position is

$$\Delta L = \sum_{i=1}^{n} \Delta l_i = \frac{1}{2kn} F \sum_{i=1}^{n} \left( 1 + \frac{i}{n} \right).$$

Since $\sum_{i=1}^{n} \left( 1 + \frac{i}{n} \right)$ represents the sum of the terms of the arithmetic progression

$$^*)$$ This follows from the fact that the spring force of all springs with such a connection is the same.

⟦folio 50⟧

regression with progression difference $\frac{1}{n}$, then
$$\sum_{i=1}^{n} \left(1 + \frac{i}{n}\right) = \frac{3n+1}{2}.$$
And
$$\Delta L = \frac{F}{4k} \frac{3n+1}{n}.$$
But $n \gg 1$, therefore
$$\Delta L \approx \frac{F}{4k} \frac{3n}{n} = \frac{3}{4} \frac{F}{k}.$$
Substituting this expression for $\Delta L$ into formula (1), we find the dynamometer readings
$$T = k \cdot \frac{3F}{4k} = \frac{3}{4} F = 3n.$$
F184. When transmitting a television image on Earth, 25 frames are transmitted in one second. This means that one frame is transmitted in 1/25 of a second. At one time, as is known, the transmission of one frame of the Lun image to the Soviet automatic station “Luna” lasted 25 minutes. Why is there such a big difference in the transmission time of one image frame in general cases?

To transmit an image, it must first be converted into an electrical signal. This happens in the transmitting television tube. The image frame is projected onto a light-sensitive brain screen. Each of the screen cells is charged, and the more, the greater its illumination. This produces an electrical image of the transmitted object. Then the electron beam sequentially runs around different parts of this image, moving from left to right (along the line) and from top to bottom (along the lines); the electrical image is converted into an electrical signal.

Suppose we want to convey the picture shown in figure 9. The horizontal brightness of the picture changes according to the sinusoidal law. Let the number of brightness maxims be $m$; the number of lines on which the picture is divided is $n$, and the frame rate is $-f_k$. The electrical signal carrying information about the card has the form shown in figure 10.

Fig. 9.

Fig. 10.

During the transmission of one line, the signal has $m$ maximums, during the transmission of one frame - $nm$ maximums, and in 1 second - $nmf_k$ maximums. This means that the cyclic frequency of the signal $\Omega$ is equal to
$$\Omega = 2\pi f = 2\pi mnf_k.$$
Therefore, the frequency of the signal $\Omega$ is proportional to the frame rate
$$\Omega \sim f_k.$$
The magnitude of the signal changes over time according to the long-range law, which can be written as follows:
$$u_{\Omega} = U_0 + U_1 \sin \Omega t = U_0 (1 + k \sin \Omega t),$$
where $k = \frac{U_1}{U_0}$.
In order to transmit this low-frequency signal over long distances, it is modulated by a high-frequency signal $\omega$ ($\omega \gg \Omega$), the magnitude of which varies according to the law
$$u = U'_0 \sin \omega t.$$
As a result of amplitude modulation, the high-frequency signal is no longer constant, but changes over time in the same way as the modulating low-frequency signal (Fig. 11).

Fig. 11.

Thus,
$$u_M = U'_0 (1 + k \sin \Omega t) \sin \omega t$$
($u_M$ is the magnitude of the amplitude-modulated signal).

After simple trigonometric transformations we get
$$u_M = U'_0 \sin \omega t + \frac{1}{2} k U'_0 \sin (\omega + \Omega) t + \frac{1}{2} k U'_0 \sin (\omega - \Omega) t.$$

This means that in our case the amplitude-modulated signal represents

⟦folio 51⟧

It is the sum of three sinusoidal signals with frequencies $\omega$, $\omega + \Omega$ and $\omega - \Omega$. If the frame is more complex, then it is transmitted in a frequency interval of width $2\Omega$. The higher the frame rate, the wider the specified frequency interval. The television receiver, therefore, must receive signals in a certain frequency range.

But along with the signal carrying this information, there are always all kinds of random signals on the air, called noise. Noises have different frequencies and we can assume that in each frequency interval their energy is the same. The wider the frequency shelf perceived by the receiver, the stronger the noise or, as they say, the higher the noise level. If the main signal is weak, it may be filled with noise and we will not be able to recognize it.

On Earth, transmitting stations have sufficient power, and the signal level is much higher than the noise level. Therefore, the frame rate can be quite high (which is really necessary for normal visual perception of a television program).

It's a different matter in space. The transmitter powers on spacecraft are low, and the level of the main signal is low. By increasing the transmission time of one frame, that is, reducing the frequency band, you can significantly reduce the noise level, which will help to isolate the signal carrying information.

F185. A volleyball with a mass of 200 g and a volume of 8 liters is pumped to an excess pressure of 0.2 atm. The ball was thrown to a height of 20 m and after falling on a hard surface it jumped up to almost my same height. Estimate the maximum air temperature in the ball at the moment of impact with the ball. Outdoor air temperature $300^\circ\text{K}$, air temperature at constant volume $c_v = 0,16\text{ кал/л} \cdot \text{ град}$.

Since the ball, after hitting the ground, rose to almost the same height from which it fell, energy losses during impact can be ignored and we can assume that the air in the ball during the impact occurs advatically.

According to the law of conservation of energy (the first law of thermodynamics), the change in internal energy of the gas $\Delta U$ is equal to

$$\Delta U = Q + A,$$

where $Q$ is the amount of heat imparted to the gas, and $A$ is the work done on the gas as it rolls down. Since in this case $Q = 0$, then

$$\Delta U = A.$$

As is known, the change in the internal energy of a gas does not depend on the process and is equal to

$$\Delta U = c_v m \Delta T = c_v m (T_{\max} - T),$$

where $T$ is the initial temperature of the gas, $m$ is its mass.

The work of compressing air is done due to the mechanical energy of the ball. If you exceed the potential energy of deformation of the chamber and the soil at the moment of greatest slope (when the air temperature is maximum and the ball is over), then the work $A$ is equal to

$$A = Mgh,$$

where $M$ is the mass of the ball, $h$ is the height at which it was thrown.

Substituting the expressions for $\Delta U$ and $A$ into formula (2), we obtain

$$c_v m (T_{\max} - T) = Mgh.$$

The mass of air in the ball can be determined from the equation of gas state:

$$PV = \frac{m}{\mu} RT,$$

where $P = P_{\text{атм}} + P_{\text{и}}$ ($P_{\text{атм}} = 1\text{ атм}$ is atmospheric pressure, $P_{\text{и}}$ is excess pressure), $V$ is the volume of the ball. From here

$$m = \frac{(P_{\text{атм}} + P_{\text{и}}) V \mu}{RT}.$$

From (5) and (6) we find

$$T_{\max} = T \left[ 1 + \frac{Mgh R}{\mu (P_{\text{атм}} + P_{\text{и}}) V c_v} \right] \approx 1,02T = 306^\circ\text{K}.$$

F186. When the vehicle turns, the passenger is thrown back in a straight line by inertia. He does not fly out of the automatic machine only because he is held, for example, by the wall of the automatic machine, which imparts the necessary centripetal acceleration, or the passenger holds on to the handles. Let us calculate this holding force acting on the passenger of mass $m = 50\text{ кц}$, if the turning radius is $R = 20\text{ м}$ and the speed of the automatic vehicle is $v = 36\text{ км/ч}$.

According to Newton's second law

$$F = ma = m \frac{v^2}{R} = \frac{50\text{ кц} \cdot 100\text{ м}^2/c^2}{20\text{ м}} = 250\text{ кц},$$

which is half the passenger's weight.

Now let's look at what happens when the plane turns. On a horizontal flying aircraft, in a plane perpendicular to the direction of its flight, two forces act: the force of gravity $P$ and the aerodynamic lift force $N$. When the aircraft turns, the equal force $F$ of these forces must be directed towards the center of the circle along which the aircraft is moving. This means that the force $N$ is not vertical, but amounts to some

⟦folio 52⟧

angle α with the vertical (Fig. 12). But the force N is the sum of the lifting forces of the wings and it is perpendicular to the wings, therefore, the aircraft body is tilted in the direction of rotation *).

Force F imparts the required centripetal acceleration to the aircraft.

A passenger on an airplane moves in a circle of the same radius with the same centripetal acceleration. This acceleration is imparted to the passenger by the resultant force mg of gravity and the reaction force of the aircraft seat N₁. Moreover, the reaction force must also form an angle α with the vertical (tg α = a/g). It follows that the position of the passenger relative to the aircraft is exactly the same as during horizontal flight of the aircraft. When turning, only the magnitude and direction of the force N₁ changes. During horizontal flight, the force N₁ is vertical and equal in absolute value to the force of gravity; when turning, it makes an angle α with the vertical and is equal in absolute value to

$$\Delta N_1 = \sqrt{(mg)^2 + \left(\frac{mv^2}{R}\right)^2} - mg$$

(v - aircraft speed, R - turning radius). At m = 50 kW, v = 720 km/h and R = 10 km, this addition is

$$\Delta N_1 \approx 50 \text{ и.}$$

It is much less than the weight of the passenger and is almost not felt by him.

*) This tilt of the aircraft occurs due to the fact that when the rudder is turned, due to air pressure on the keel, the aircraft rotates around a vertical axis passing through the center of gravity of the aircraft. In this case, one of the aircraft’s wings moves faster than the other relative to the oncoming air flow. A large aerodynamic lift force acts on this wing (it is proportional to the speed of movement), and the plane tilts in the direction of the turn.

F187. A thin metal plate of area S is filled with a layer of liquid dielectric with density ρ and dielectric capacity ε so that the thickness of the layer is much less than the linear dimensions of the plate. What will happen to the liquid if the plate is given an electric field, the direction of which in a vacuum is equal to

$$E_0 = \frac{Q}{2\varepsilon_0 S},$$

and in a dielectric

$$E = \frac{Q}{2\varepsilon_0 \varepsilon S}.$$

The weakening of the field in the dielectric is associated with the polarization of the dielectric. In this case, a charge - Q₁ appears in a thin layer near the plate, and a charge + Q₁ appears on the free surface of the dielectric (Fig. 13). Inside the dielectric, the negative and positive charges of the dipoles compensate each other. The induced charges Q₁ and - Q₁ create a field with the direction emgoy

$$E_1 = 2 \frac{Q_1}{2\varepsilon_0 S} = \frac{Q_1}{\varepsilon_0 S},$$

directed against the plate field.

According to the principle of superposition

$$E = E_0 - E_1$$

or

$$\frac{Q}{2\varepsilon_0 \varepsilon S} = \frac{Q}{2\varepsilon_0 S} - \frac{Q_1}{\varepsilon_0 S}.$$

From this equation you can find the charge Q₁:

$$Q_1 = Q \frac{\varepsilon - 1}{2\varepsilon}.$$

Two electric forces act on the charge Q₁ of the free surface of the liquid: the force of attraction to the charge - Q₁, equal to

$$F_1 = Q_1 \cdot \frac{1}{2} E_1 = Q_1 \cdot \frac{Q_1}{2\varepsilon_0 S} =$$

$$= \frac{Q^2}{2\varepsilon_0 S} \left( \frac{\varepsilon - 1}{2\varepsilon} \right)^2,$$

and the repulsion force from the plate charge Q₁.
