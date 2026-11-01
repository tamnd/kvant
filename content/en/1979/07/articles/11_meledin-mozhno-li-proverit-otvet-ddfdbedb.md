---
id: 1979-7-meledin-mozhno-li-proverit-otvet-ddfdbedb
issue: kvant_1979_7
year: 1979
number: "7"
title: Is it possible to check the answer?
authors:
  - Меледин Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 45
page_labels: 41-43
tag: B10X
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86bed21adfb63c777c719d786d3c83f6277ea1a7caae036aabba34024ebb5d5f
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/11_meledin-mozhno-li-proverit-otvet-ddfdbedb.md
source_content_sha256: 8e649bf525f222fd0a522b50b0e9547d642f8c79bb8ee4446e380458e00ec43a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

Is it possible to check the answer?

After solving a problem, especially a complex one, he always wants to make sure that the results obtained are correct or at least that there are no errors. There are many ways to quickly detect an error. For example, you can compare your answer with the answers of others or with the answers obtained by solving the same problem using other methods. However, it is also possible that this is not always the case.

Let's look at a few examples that physicists use. This is checking the answer for dimensionality, checking for symmetry, studying special (or limiting) cases and, finally, monitoring the range of acceptable values.

In order to check the answer using one of these methods, you need to get it in algebraic (literal) form.

1. Checking for dimensionality does not require special comments - when substituting the dimensions of a quantity included in the formula, the result should be the dimension of the original quantity. (Of course, all parameters must be expressed in the same system of units.) From the point of view of such verification, it is convenient to write the answer so that its dimension is immediately visible. For this purpose, either dimensionless ratios or stable dimensions of combinations of parameters such as $|v|^2/g$ (length dimension), $\rho gh$ (pressure dimension), $\sqrt{l/g}$ (time dimension), etc. are usually distinguished.

As an example, consider this well-known problem:

Problem 1. There is an unattached thread through a stationary block of peroxidum, with weights of mass $m_1$ and $m_2$ (Fig. 1) suspended at the ends of the thread. Find the tension of $|\vec{T}|$ threads when moving loads.

Answer: $|\vec{T}| = \frac{2m_1m_2}{m_1 + m_2} g$.

Let's check the size. The product of masses divided by their sum gives the dimension of mass, and multiplied by acceleration gives the dimension of force. Therefore, the dimensions of the left and right sides of the formula for thread tension are the same.

2. The symmetry test is less known. It will consist of the following. If some parameters of the same dimension are included in the problem statement in such a symmetrical way that when the indices numbering the parameters are rearranged, the problem does not change, then the same symmetry should be in the answer.

So, in task 1, the tension of the thread does not depend on whether the heavier load is to the left or to the right of the location block and which of the two indices - 1 or 2 - denotes its mass. This means that the answer should not change when replacing $m_1$ with $m_2$ and $m_1$. In other words, the expression for thread tension must be symmetrical with respect to $m_1$ and $m_2$. The given answer to this action is

Fig. 1.

⟦folio 42⟧

completely satisfies—both the product and the sum of masses are symmetrical combinations of the parameters $m_1$ and $m_2$.

Let's give another example where there is a similar symmetry.

Problem 2. Three capacitors of the same capacitance have charges $q_1, q_2$ and $q_3$, respectively. They are connected with help, as shown in figure 2. Find the established charges on the capacitor.

Answer: $q_1' = \frac{2q_1 - q_2 - q_3}{3}$;
$q_2' = \frac{2q_2 - q_1 - q_3}{3}$;
$q_3' = \frac{2q_3 - q_1 - q_2}{3}$.

It is clear that nothing will change if we successively change the numbering of charges ($q_1 \rightarrow q_2, q_2 \rightarrow q_3, q_3 \rightarrow q_1$) - this is just a rotation of the picture. The answer should show the same symmetry with respect to cyclic permutations. It is easy to verify that our answer has this property.

For convenience of controlROL, symmetry in the parameters in the answer must be preserved.

3. Testing on partial comparisons is carried out as follows. Select the simplest values ​​of the charge parameters for which the answer is very significant, and see whether the resulting general formula for these particular parameter values ​​gives the same result.

Let us turn once again to the block problem. If either mass - $m_1$ or $m_2$ - is zero, then the other mass is freely falling and the thread is not taut. The same zero result is obtained from the answer.

(Note that the resulting result turns to zero when one of the parameters is zero is usually due to the fact that this parameter enters the answer in the form of a multiplier, perhaps to some extent. In more complex problems, this happens only in x cases: for very large or very small values ​​of the selected parameter.)

Let us also consider the case of equal masses: $m_1 = m_2 = m$. In this case, the loads are either at rest or moving uniformly. Therefore, the tension must not be equal to the weight of one of the groups. It is easy to see that the formula gives the same result.

4. Sometimes, when checking on partial comparisons, a discrepancy between the result in a particular case and the result obtained from the general formula is discovered. Obviously this is explained by the fact that the particular value of the parameter taken at random did not fall within the range of acceptable values. Such a vague possibility suggests the need to accompany the answer with an indication of the range of acceptable parameter values.

Here is a typical example:

Problem 3. A force $\vec{F}$ directed downwards at an angle $\alpha$ to the horizon (Fig. 3) is applied to chalk of mass $m$, located on a horizontal surface. The time coefficient between chalk and surface is $k$. Find the acceleration of the body.

Typical answer:

$$\vec{a} = \frac{|\vec{F}| \cos \alpha - k (mg + |\vec{F}| \sin \alpha)}{m x}.$$

Fig. 3.

⟦folio 43⟧

Obviously, if the body is not pulled, it will not accelerate. Let's check this: at $|\vec{F}| = 0$ $|\vec{a}| = -kg \neq 0!$ What's the matter?

It turns out that the correct answer should be:

$$\begin{align*}
|\vec{a}| &= \frac{|\vec{F}| \cos \alpha - k (mg + |\vec{F}| \sin \alpha)}{m} \\
\text{при } |\vec{F}| > \frac{kmg}{\cos \alpha - k \sin \alpha}, \\
|\vec{a}| = 0 \text{ при } 0 \leq |\vec{F}| \leq \frac{kmg}{\cos \alpha - k \sin \alpha}.
\end{align*}$$

Thus, for $|\vec{F}| = 0$ you need to use not the first, but the second formula, and then no contradiction is observed.

In conclusion, we note that whenever a difference under the radical sign or a logarithm appears in the answer, it is imperative to find the range of acceptable values. Particular attention is required to the difference in the denominator; in this case, you need to quickly check at what values

$$x = \frac{m}{M} L \quad \text{или} \quad x = \frac{m}{M + m} L.$$

(Consider limiting cases.)

1. A boat with length $L$ and mass $M$ stands with its bow pressed to the shore. A man of mass $m$, wanting to go ashore, begins to walk from the far end of the boat. At what distance $x$ will the boat move away from the shore when a person reaches the bow of the boat? Without solving the problem, find out which of the two answers is correct:

$$x = \frac{m}{M} L \quad \text{или} \quad x = \frac{m}{M + m} L.$$

2. Draw approximately a graph of the dependence of the projection $f$ on the optical axis of the force of light pressure on the lens from the distance $x$ to the exact light source located on the main optical axis of the lens. Consider the dimensions of the lens to be unlimitedly large, and do not take into account the reflection and absorption of light by the lens. (As special cases, consider, for example, the following: $x=0$, $x=F$ (F-focal length of the lens), $x=2F$, $x \to \infty$.)

(For the beginning see pp. 20, 32)

27, 29a); A. Nursimov (Alma-Ata) 16a), 6), 21; I. Nyzhnik (Novosibirsk) 21; A. Okropidze (Tbilisi) 26; A. Oparin (Moscow) 16, 18, 19a), 21, 22, 236), 24, 26-29, 30a); A. Pavlychev (Riga) 26; A. Palandein (Yerevan) 26; E. Palosh (Voroshilovgrad) 16a), 21, 26; A. Pantelev (Rostovna-Don) 26; V. Pitenko (Pukhovnichiy district, Minsk region) 27, 28; A. Pizzevsky (Voronezh) 26; T. Podstritsan (Lviv) 19a), 21, 26-28, 30a); L. Polterovich (Moscow) 16, 24; A. Popelokhin (Kyiv) 16, 21, 22, 23a), 24, 26-28; S. Poshekhonov (Engels) 26; V. Protshin (Peschanoe village, Pavlodar region) 16a); Ch. Puritsashashili (Tbilisi) 16a), 26; A. Purzv (MPR) 26; S. Putintsev (Nevinnomysk) 16-25; V. Rabinovich (Tula) 16, 22, 26, 30a); D. Ramzaev (Tbilisi) 26; V. Rozozin (Shelkovo) 16a), 6); I. Roizman (town of Kaliinivka, Vinnytsia region) 27, 28, 30a); I. Savenkov (village Lysye Gory, Saratov region) 16, 27, 28, 30a); Yu. Saenko (Zhdanov) 26, 30a); I. Sanartsev (Ufa) 21; A. Sarimelia (Tbilisi) 26-28, 30; S. Sevastyuk (Nevinnomysk) 16a), 6); M. Sevryuk (Moscow) 16-24, 26-30; P. Selivanov (Semipalatin) 21, 22, 23a); A. Sivatsky (Leningrad) 16, 18, 19, 21, 22, 24, 26, 28, 30a); S. Sidorenko (Bryansk) 18; M. Sluts (Moscow) 21; A. Sromin (Leningrad) 21, 26, 28;

S. Stadichenko (Penza) 16a), 6), 21, 22, 24, 26, 28; M. Streshinsky (Donetsk) 21; F. Sukochev (Tashkent) 16-29; O. Tavets (Minsk) 16a), 27; R. Tatsev (Masalli district of AzSSR) 26; K. Tatalyan (Yerevan) 16, 19a), 21, 27-29, 30a); D. Timofeev (Gorky) 16a); M. Torosyan (Yerevan) 16a), 6), 18, 20-22, 24, 26, 27; N. Trifonov (Kansk) 16a), 6), 19a), 20-22, 25, 26, 28; V. Trofimov (Moscow) 27; Yu. Trofimuk (town of Kaliinivka, Vinnytsia region) 26; D. Turaev (Gorky) 18, 19a), 20, 26, 27, 30a); V. Umansky (Baku) 16a), 6), 21, 27, 28; A. Unayan (Sevan) 21, 22, 24; A. Famullayev (Baku) 26; S. Khosid (Alma-Ata) 16, 18, 19, 21, 24, 26, 28; K. Christmov (NRB) 16, 18, 19a); L. Tsalenko (Moscow) 16, 19a), 21, 22, 24, 26, 28; Z. Tsikhistavi (Telavi) 16a), 21; A. Chaplesin (Nikolaev) 16a), 6), 18, 19a); O. Chechel (Moscow) 26-28; V. Sharafyan (Yerevan) 18, 26; N. Sharomet (Moscow) 21, 28; G. Shakhbazyan (Leningrad) 19a); E. Shklarr (Gomel) 21; V. Shamenko (Angarsk) 26; M. Ereshev (Fergana) 16a), 6); A. Yalitsev (Tula) 16, 19a), 26, 30a); V. Yasinsky (Vinnitsa) 21.

Physics

V. Abadzhaev (Lviv) 28, 31; K. Abdukhalikov (Alma-Ata) 23, 24; E. Abramochkin (Kuibyshev) 24; E. Alexandrova (Glazov) 24, 26, 28, 29, 31; A. Ashkinazi (Moscow) (For the end, see p. 58)
