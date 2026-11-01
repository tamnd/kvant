---
id: 1980-12-chehlov-eti-kovarnyie-vektoryi-0c44aef9
issue: kvant_1980_12
year: 1980
number: "12"
title: These "insidious" vectors
authors:
  - Чехлов В. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 46
page_labels: 40, 42, 43, 44
tag: KANU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 11fa47c980362d6f0c9e77eea62442eac54b8aeec8a194c40627d286d47a98ec
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/18_chehlov-eti-kovarnyie-vektoryi-0c44aef9.md
source_content_sha256: e5111849d0c4099c441094159fd3a9621927bbef7137fa03666b83f0dc17b893
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

These "insidious" vectors

This note is devoted to some features of the application of vectors to solving geometric problems.

The use of vectors is based on the fact that various statements about the relative position of a point, lines and planes can be formed in a “vector language”, in particular using the concepts of collinearity and coplanarity. This allows us to reduce the geometric problem to a vector equality. In turn, a vector equality can be reduced (in particular, based on the uniqueness of decomposition theorem) to an algebraic equality or to a system of algebraic equalities.

Problem 1. Base of parallelogram ABCD. The plane intersects the side edges SA, SB, SC and SD of the corresponding parallelus at points M, N, P and Q so that |SM|:|SA|=a, |SN|:|SB|=b, |SP|:|SC|=c,

Fig. 1.

|SQ|:|SD|=d. Prove that $\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$.

Solution e. The segments NM, NP and NQ (Fig. 1) lie in the same plane. According to the definition of coplanar vectors, the vectors NM, NP and NQ are coplanar. The vectors NM and NP are obviously not collinear, therefore, by the theorem on the decomposition of coplanar vectors, there are numbers x and y such that $NQ = xNM + yNP$. (1)

Let us decompose these vectors into three non-complan vectors SA, SB and SC. We have SM=aSA, SN=bSB, SP=cSC, SQ=dSD, from where

$NM = SM - SN = aSA - bSB$, (2)
$NP = SP - SN = cSC - bSB$, (3)
$NQ = SQ - SN = dSD - bSB$. (4)

Since $SD = SA + AD$ and $AD = BC = SC - SB$, it follows from (4) that $NQ = dSA - (d + b)SB + dSC$. (5)

Substituting (2), (3), (5) into (1), we get

$NQ = dSA - (d + b)SB + dSC = axSA - b(x + y)SB + cySC$. (6)

Due to the uniqueness of the expansion, vector equality (6) is equivalent to the system

$$\begin{cases}
d = ax; \\
d + b = b(x + y), \\
d = cy.
\end{cases}$$

Hence $x + y = \frac{d}{a} + \frac{d}{c} = \frac{d + b}{b}$, or $\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$.

In the example considered, vector equality (6) was reduced to system (7). It should be remembered that equality for vectors in space is equivalent to a system of three algebraic equalities. Therefore, if at least one of the equalities of this system is false for any values ​​of the variables, then the vector equality is false, and the original geometric problem has no solutions. The following simple example confirms this.

⟦folio 42⟧

We press in the OAB plane. This means that the vectors $\vec{a}, \vec{b}$ and $\vec{c}$ are coplanar. With the exceptions above, the proof is even simpler, and we leave it to the reader.

Problem 3 (“Geometry 9-10”, No. 247). Point A is the common vertex of parallelograms ABCD and $AB_1C_1D_1$. Prove that the vectors $\vec{BB}_1, \vec{CC}_1, \vec{DD}_1$ are coplanar.

Solution. We have $\vec{CC}_1 = \vec{CB} + \vec{BB}_1 + \vec{B}_1\vec{C}_1$ (Fig. 4) and, since $\vec{CB} = \vec{DA}$ and $B_1\vec{C}_1 = \vec{AD}_1$, we get $\vec{CC}_1 = \vec{BB}_1 + (\vec{DA} + \vec{AD}_1)$. But $\vec{DA} + \vec{AD}_1 = \vec{DD}_1$, therefore $\vec{CC}_1 = \vec{BB}_1 + \vec{DD}_1$. It follows from (*) that the vectors $\vec{CC}_1, \vec{BB}_1$ and $\vec{DD}_1$ are coplanar.

Problem 4. Given three united vectors $\vec{a}, \vec{b}$ and $\vec{c}$ the same as $(\vec{a}, \vec{c}) = (\vec{b}, \vec{c}) = \frac{\pi}{3}, (\vec{a}, \vec{b}) = \frac{\pi}{2}$. Are these vectors coplanar?

We suggest first finding the error in the following reasoning:

“Let us prove that $\vec{a}, \vec{b}$ and $\vec{c}$ are coplanars. We will look for numbers $x$ and $y$ for which $\vec{c} = \vec{x}a + \vec{yb}$.

To do this, we multiply both sides of (11) scalarly by the vector $\vec{a}$. We get $\vec{c} \cdot \vec{a} = \vec{x}a \cdot \vec{a} + \vec{yb} \cdot \vec{a}$, from where $x = \frac{1}{2}$. Multiplying both sides of (11) by $\vec{b}$, we obtain $\vec{c} \cdot \vec{b} = \vec{x}a \cdot \vec{b} + \vec{yb} \cdot \vec{b}$, hence $y = \frac{1}{2}$. Means,

$$\vec{c} = \frac{1}{2} \vec{a} + \frac{1}{2} \vec{b},$$

that is, by (*) the vectors $\vec{a}, \vec{b}, \vec{c}$ are coplanar.”

It is easy to establish that this reasoning is erroneous. It is enough to try from some point the vectors $\vec{a}, \vec{b}, \vec{c}$ with given angles between them. Immediately making it clear that this is impossible. This means that the vectors $\vec{a}, \vec{b}$ and $\vec{c}$ are not coplanar.

In order to understand where the mistake was made, let's go back to the beginning of the argument. There the goal was expressed to find numbers $x$ and $y$ for which equality (11) is true. But this numbering was not carried out. Indeed, the following calculations prove only that from (11) follows (12), and nothing more. Neither the existence of numbers $x$ and $y$, for which (11) is true, nor equalities (12) have been proven. And this means that the conclusion “by (*) the vectors $\vec{a}, \vec{b}, \vec{c}$ are coplanar” is not justified.

The mistake here is that from the reasoning carried out a conclusion is drawn that does not correspond to the proven statement.

Let us now present the vector solution to Problem 4.

Let us prove by contradiction that the vectors $\vec{a}, \vec{b}, \vec{c}$ are not coplanar. Let us assume that there are numbers $x$ and $y$ such that equality (11) is true. Then, as before, we find that (12) is also true. Multiplying (12) scalarly by $\vec{c}$, we obtain that the equality $1 = \frac{1}{4} + \frac{1}{4}$ is true, that is, $1 = \frac{1}{2}$. This contradiction shows that (11) is not true for any $x$ and $y$, that is, the vectors $\vec{a}, \vec{b}, \vec{c}$ are not coplanar.

Let's consider another example of how incomplete translation of the conditions of a geometric problem into “vector language” can lead to an error.

Problem 5. At what length of the edge AD in the tetrahedron ABCD are satisfied the corresponding conditions:

$$\overrightarrow{ABC} = \frac{\pi}{2}, \overrightarrow{BCD} = (AB, CD) = \frac{5}{7},$$

$$|AB| = |BC| = |CD| = a?$$

⟦folio 43⟧

"Solution". Since $\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}$, we get $\vec{AD}^2 = \vec{AB}^2 + \vec{BC}^2 + \vec{CD}^2 + 2\vec{AB} \cdot \vec{BC} + 2\vec{AB} \times \vec{CD} + 2\vec{BC} \cdot \vec{CD}$. Here $\vec{AB}^2 = \vec{BC}^2 = \vec{CD}^2 = a^2$, $\vec{AB} \cdot \vec{BC} = 0$, $\vec{BC} \times \vec{CD} = a^2$ cos $(\pi - \vec{BCD}) = -\frac{5}{7} a^2$, $\vec{AB} \cdot \vec{CD} = a^2$ cos $(\vec{AB}, \vec{CD})$, and since two cases are possible: $(\vec{AB}, \vec{CD}) = \arccos \frac{5}{7}$ or $(\vec{AB}, \vec{CD}) = \pi - \arccos \frac{5}{7}$, we get either $\vec{AB} \times \vec{CD} = \frac{5}{7} a^2$ or $\vec{AB}, \cdot \vec{CD} = -\frac{5}{7} a^2$. It follows that either $\vec{AD}^2 = 3a^2$ or $\vec{AD}^2 = \frac{a^2}{7}$. So, $|\vec{AD}| = \sqrt{3} a$, or $|\vec{AD}| = \frac{a}{\sqrt{7}}$.

At first glance, there was no room for error in this decision. Nevertheless, there is an error in it. The fact is that the posed geometric problem was balanced with the problem of solving a vector system:
$$\begin{cases}
|\vec{AB}| = |\vec{BC}| = |\vec{CD}| = a, \\
\vec{AB} \cdot \vec{BC} = 0, \\
\vec{AB} \cdot \vec{CD} = \pm \frac{5}{7} a^2, \\
\vec{BC} \cdot \vec{CD} = -\frac{5}{7} a^2, \\
\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}.
\end{cases}$$

This is a system with four unknown vectors $\vec{AB}, \vec{BC}, \vec{CD}$ and $\vec{AD}$, and the geometric formulation of Problem 5 can now be replaced by an algebraic (vector) formulation: what is the length

Fig. 5.

⟦folio 44⟧

Multiplying both sides of (15) scalarly by $\vec{AB}$, we obtain that $x = \pm \frac{5}{7}$, and multiplying (15) by $\vec{BC}$, we find $y = -\frac{5}{7}$. Then

$$|\vec{CD}|^2 = (x^2 + y^2 + z^2)a^2 = \left(\frac{50}{49} + z^2\right)a^2 > a^2,$$

and this contradicts the condition $|\vec{CD}| = a$.

This means that system (14) has no solutions, and we get the same answer as before.

The problems attached to this note can be solved using vectors and geometric numbers.

Exercises
1. Given points $A, B, C$ that do not lie on the same line, and points $D$ and $O$, $O \neq D$. Prove that in order for the point $D$ to belong to the plane $ABC$, it is necessary and sufficient that $OD = xOA + yOB + zOC$, where $x + y + z = 1$.

2. The base of the lines $SABCD$ is the parallelogram $ABCD$. On edges $AB, AS$ and $SC$ there are points $M, N$ and $P$, respectively, so that $|BM| : |AB| = |AN| : |AS| = |SP| : |SC| = 2:3$. A straight line is drawn through the middle $Q$ of edge $BC$, parallel to the plane $MNP$ and intersecting the line $SD$ at point $R$. Find the ratio $|DR| : |DS|$.

3. All edges of a regular straight line $ABCA_1B_1C_1$ have length $a$. A line perpendicular to plane $BA_1C_1$ intersects lines $BC_1$ and $AB_1$, respectively, at points $M$ and $N$. Find $|MN|$.

4. Given three straight lines that do not lie in the same plane. How many lines are there that pass through a given point and make equal angles with the given lines $^2$.

5. In the tetrahedron $ABCD$ $|AB| = |BC| = |CD|$, $ABC = a$, $BCD = (AB, CD) = \beta$. Find the angle between lines $AD$ and $BC$. For what a and β problem a) has no solutions; b) has one solution; c) has two solutions?

List of readers who sent correct solutions to the problem from Zadanika «Kvant»
(For the beginning, see p. 34)

S. Doronin (Dnepropetrovsk) 17; A. Dremin (Chernogolovka village, Moscow region) 12; A. Durbak (Rohatyn) 16; S. Dymshakov (Shadrinsk) 16, 17; Yu. Eliseev (Velikiye Luki) 4; I. Eliseevich (Chernigov) 4, 6, 7; I. Elkanovich (Baku) 17; T. Enchev (Yambol, NRB) 9, 12; V. Zhordochki (Orsk) 4, 6-8; V. Zavarzin (Chimkent) 16; A. Zanevsky (Leningrad) 4, 6-9, 11, 16, 17; M. Zeifman (Vologda) 4, 6, 7, 9, 11, 12, 16; I. Zilberberg (Alma-Ata) 6; V. Zolotagevsky (p/o Berezovskoye, Kharkov region) 7; I. Zybtsev (Uzhur) 9, 11, 12, 17; T. Ivanov (Pleven, Belarus) 16, 17; A. Ivanov (Voronezh) 8, 12; V. Ivakhenko (Kyiv) 11; V. Izerenin (Novosibirsk) 7, 9, 11, 12, 16, 17; V. Izrailit (Dnepropetrovsk) 9, 16, 17; V. Kaazlovsky (Kharkov) 11, 12; S. Kalmykov (Kopeisk) 6, 12; A. Kaplan (Sumgant) 8, 17; D. Kaplan (Zelenograd) 7; A. Karsev (Belgorod) 7, 17; M. Kachkatsivili (Rustavi) 12; E. Kashanov (Ufa) 4; A. Kechedjyan (Yerevan) 6, 7, 9, 11, 12, 16; M. Kibirev (Tula) 8, 9, 12; Yu. Kirpach (Kyiv) 4, 6, 7, 11, 17; Yu. Kovernik (Zaporozhye) 6; E. Koran (Dnepropetrovsk) 8, 9, 11, 12; A. Kozhevnikov (Dnepropetrovsk) 8, 9, 12; V. Kozlovsky (Novolukoml) 8-12; T. Kozhoridze (Telvi) 12; D. Kolomotsev (Sumgant) 4, 6-9, 11; V. Komov (Aleksadrov) 4, 6-12, 16, 17; T. Kondratskaya (Kyiv) 4, 6-8; S. Konkin (Arzamas) 4, 9, 11, 12; V. Korobov (Kirovograd) 16; K. Korchazin (Yerevan) 16; M. Kostin (Saratov) 12; I. Kostyuevich (Leningrad) 4, 6, 9, 12, 17; D. Kotelnikov (Magnitogorsk) 4, 6, 7, 16, 17; M. Kravtsov (Kommunarsk) 16; K. Krapivnoy (Zaporozhye) 6, 7; I. Krasikov (Kyiv) 8, 9, 11, 12; A. Kreines (Kolchugino) 17; L. Kreminskaya (Rivne) 8; E. Krenzel (Moscow) 17; R. Chris (Kyiv) 4, 7, 8, 11, 12; I. Krolivets (Kramatorsk) 11, 12; E. Kuznetsov (CHISINAU) 6, 8, 11, 12; P. Kuznetsov (Kyiv) 4, 6, 8-12; A. Kuzmin (Alma-Ata) 6, 7, 11; D. Kuksenkov (Leningrad) 16, 17; S. Kurchatov (Saratov) 4, 7; B. Lapidus (Moscow) 11, 12, 17; M. Levenkov (Vereshchino) 17; V. Leites (Moscow) 4, 6, 7; I. Leonov (Voronezh) 6, 11, 12; D. Leshchinsky (Magnitogorsk) 16; F. Lomaya (Simferopol) 9, 12; I. Lukuyanchuk (Kyiv) 4, 6, 17; E. Lyubovitsky (Kostroma) 16; A. Lyapin (Gomel) 4, 6, 16, 17; A. Mazurkovich (Lytkarino) 6, 9, 11, 12; Z. Makimov (Tashkent) 16, 17; A. Maltsin (Gorky) 16; V. Maltsev (Ufa) 17; O. Manuilenko (Kyiv) 17; S. Maslennikov (Meshon village, Gomen region) 4; S. Makhortykh (Lisichansk) 9; A. Mikula (Zhidachkov) 4, 6, 12, 17; S. Milovanov (Zaporozhye) 17; S. Mikhailovsky (Vinogradovsky district, Arkhangelsk region) 7, 11, 12, 16; G. Molchanov (Saratov) 7-9, 11, 12; D. Myakshev (Angarsk) 11; R. Nabokov (Moscow) 4, 7; S. Nadtochiy (Moscow) 4, 6-9, 11, 12; A. Nazarenko (Kyiv) 6-9, 11; M. Nylovzen (Baku) 16; D. Nishinaidze (Kutansi) 8; D. Nozdrin (Saratov) 4, 6; S. Obochevets (Leningrad) 6, 7; D. Ovsyannikov (Leningrad) 4, 6-9, 12; S. Odintsova (Kyiv) 4, 6, 7, 11; A. Orlov (For the end see p. 55)
