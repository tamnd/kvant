---
id: 1972-6-lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1
issue: kvant_1972_6
year: 1972
number: "6"
title: Ohm's law for a non-uniform section of a circuit
authors:
  - Ланге В. Н.
rubric: ekzamenatsionnye-materialy
rubric_sub: Экзаменационные материалы
page_first: 61
page_last: 62
page_labels: 59-60
tag: B2MJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: c227166c3e489f0d4811dc398bd403243ebc02803970edea20d06b88c04e25d9
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/19_lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1.md
source_content_sha256: 54785fcab857f77c49d81c3625e0c43a2f7245a3b42b9ac8f87339b5d5aab225
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Ohm's law for a section of an electrical circuit, which allows one to expand the strength of the current flowing through it, has the following form:

$$I = \frac{U}{R}.$$

In this formula, $R$ is the resistance of the circuit section, $U$ is the difference between the potential starting and ending points of the section, that is

$$U = \varphi_1 - \varphi_2.$$

However, the law written in this form is not always applicable. To show this, consider the simplest circuit consisting of a source

$$\begin{array}{c}
I \\
R
\end{array}$$

Fig. 1.

current with electromotive force $E$ and internal resistance $r$ and resistance $R$ (Fig. 1). Divide this chain into two sections $ARB$ and $BEA$. When applied to section $ARB$, formula (1) gives:

$$I_R = \frac{U_{AB}}{R} = \frac{\varphi_A - \varphi_B}{R}.$$

Let's try to use the same formula (1) to calculate the current strength, searched for the section $BEA$. Its beginning and end are the corresponding points $B$ and $A$. That's why

$$I_E = \frac{U_{BA}}{r} = \frac{\varphi_B - \varphi_A}{r}.$$

If you do not pay attention to the sign, the numerators of expressions (2) and (3) coincide, while the denominator, generally speaking, is different. Therefore, we have to conclude that

$$I_R \neq I_E,$$

and this, of course, is not wrong, since in a non-recreational circuit the current strength must be the same everywhere. The reason for the error is that formula (1) is applied only to homogeneous sections of the circuit, that is, to sections that do not contain current sources (galvanic cells, batteries, dielectric machines, photocells, etc.). Section $BEA$ is inhomogeneous - it contains a current source with e. d. c.

What does the formula for Ohm's law look like for an inhomogeneous section of the circuit? It turns out that the desired expression can be easily obtained from Ohm’s law for a closed circuit

$$I = \frac{E}{R + r}.$$

Let us reduce equality (4) to a common denominator:

$$IR + Ir = E.$$

The first term includes quantities related to the homogeneous area $ARB$ (see Fig. 1), and based on equality (1) we can write

$$IR = U_{AB} = \varphi_A - \varphi_B.$$

Then expression (5) can be rewritten as follows:

$$Ir = E + (\varphi_B - \varphi_A),$$

where

$$I = \frac{E + (\varphi_B - \varphi_A)}{r} = \frac{E + U_{BA}}{r}.$$

When deriving formula (6), we considered a non-uniform section of the circuit, the resistance of which consists of the internal resistance of the source. In general

⟦folio 60⟧

a non-uniform section of the circuit may contain different resistances (in part, sometimes the resistance of the wires should be taken into account), and formula (6) is then written in the form

$$I = \frac{(\varphi_1 - \varphi_2) + E}{R_\pi},$$

where $R_\pi$ is the total resistance of the section.

From formula (7) Ohm’s laws for a closed circuit and for a homogeneous section of the chain follow as special cases.

Indeed, for a closed chain $\varphi_1 = \varphi_2$ (since in this case the beginning and end of the “section” coincide). Then from formula (7) we have

$$I = \frac{E}{R_\pi}.$$

In the case of a homogeneous section of the chain $E = 0$ and formula (7) takes the form

$$I = \frac{\varphi_1 - \varphi_2}{R}.$$

(Here $R$ no longer contains the internal resistance of the source.)

When using formula (7) to solve problems, you should remember that e. d.s. is considered positive if, when moving along a homogeneous section of the chain from its beginning to its end, we first pass the negative stripe and then the positive one. If, as a result of solving the magnitude of the current, a negative value is obtained, then this means that the current in the section of the circuit flows in the “reverse” direction, that is, from the end of the section to the beginning.

Let us now consider several problems that can be easily solved using formula (7).

Task 1. Determine the current flowing through the image to figure 2 section $AB$. E.m.f. source

Fig. 2.

nickname $E = 20 \text{ } \theta$, internal resistance $r = 1 \text{ } \omega$; potential of points $A$ and $B$ respectively $\varphi_A = 15 \text{ } \theta$, $\varphi_B = 5 \text{ } \theta$; wire resistance $R = 3 \text{ } \omega$.

Solution. Considering the point $A$ to be the beginning of the section, and the point $B$ to be the end, and therefore taking e. d.s. with a minus sign, we obtain from formula (7):

$$I = \frac{(15\theta - 5\theta) - 20\theta}{3\omega + 1\omega} = -2,5 \text{ } a.$$

A negative sign indicates that the current flows in the direction $B \rightarrow A$, that is, from a point with a lower potential to a point with a higher potential. By the way, this “unnatural” behavior of the current is usually observed inside all current sources.

Task 2. Two elements are connected “towards” each other (Fig. 3). Determine the difference between potential currents $A$ and $B$

Fig. 3.

(at battery terminals) if $E_1 = 1,4 \text{ } \theta$, $r_1 = 0,4 \text{ } \omega$; $E_2 = 1,8 \text{ } \theta$, $r_2 = 0,6 \text{ } \omega$.

Solution. Formula (7) applied to section $AE_2B$ gives

$$I = \frac{(\varphi_A - \varphi_B) + E_2}{r_2}.$$

For section $BE_1A$ we have

$$I = \frac{(\varphi_B - \varphi_A) - E_1}{r_1} = -\frac{(\varphi_A - \varphi_B) + E_1}{r_1}.$$

Since the current in both sections is the same (the target is unbranched), we can equate the right-hand sides of these expressions and solve the resulting equation:
