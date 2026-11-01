---
id: 1984-4-eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e
issue: kvant_1984_4
year: 1984
number: "4"
title: Differentiating a complex function
authors:
  - Эппель Б. С.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 28
page_last: 29
page_labels: 26-27
tag: XU9Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: a38f2ef9361f9d0ad6086fbc2e5807ba78a75371c21cfe92fc98b56d91493b00
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/07_eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e.md
source_content_sha256: a901df70b8c9497bdfa82aed0636d9ea30d927b5870358f5f205858c3bcbc399
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

filament waves, the intensity of which is proportional to the square of the acceleration.

This law also requires the emission of electromagnetic waves in the RENTEN tube. Electrons, passing in a deep vacuum in the space between the cathode and the anomer, are accelerated by the electric field to high speeds, and then sharply decelerated when they collide with the anomer. In this case, significant accelerations occur, and the electrons emit electromagnetic waves. This type of radiation is called bremsstrahlung.

It turns out that, as electrons decelerate, they emit a whole spectrum of electromagnetic waves with different frequencies (or wavelengths). This spectrum is continuous, but it is limited to a certain maximum frequency $v_{\text{max}}$ (such a frequency limitation can only be explained from the point of view of quantum theory).

The highest frequency (and, accordingly, the smallest wavelength) is determined from the condition that the kinetic energy of the electron $eU$ (U is the voltage between the anomer and the cathode) is equal to the energy of the emitted quantum:

$$eU = hv_{\text{max}},$$

where

$$v_{\text{max}} = \frac{eU}{h},$$

and, accordingly, the minimum wavelength

$$\lambda_{\text{min}} = \frac{c}{v_{\text{max}}} = \frac{ch}{eU} \cdot$$

where $h$ is Planck's constant and $c$ is the speed of light. With a potential difference of several tens of kilovolts, the minimum wavelength reaches fractions of an angstrom ($1\mathring{\mathrm{A}} = 10^{-10}\text{ m}$). Such short-volume radiation has a high penetrating ability and is called RENTen radiation.

(*) Having experimentally measured the minimum wavelength $\lambda_{\text{min}}$ and voltage $V$, we can determine the value of Planck’s constant $h$ from this equality. From such experiments the value $h = 6,62 \cdot 10^{-34}\text{Дж} \cdot \text{с}$ was obtained.

Differentiating a complex function

V. S. EPPEL

All applicants know that $(\sin x)' = \cos x$. However, equalities like $(\sin 2x)' = \cos 2x$ or $(\sin^3 x)' = \cos^3 x$, which applicants are guilty of, are grossly incorrect. The fact is that the function $\sin 2x$ and $\sin^3 x$ are complex and differentiated them - the task is also more complex. We will show here how to solve this problem practically.

Errors like $(\sin^3 x)' = \cos^3 x$ arise when applicants do not know how to decipher the entry $y = \sin^3 x$ and do not see in this simple expression a complex function - a composition of two functions (see “Algebra and the beginnings of analysis 9-10”, paragraph 20). In fact, the function $y = \sin^3 x$ is obtained by sequentially performing two operations: taking the blue of the angle $x$ and cubeing the resulting number $\sin x$:

$$x \rightarrow \sin x \rightarrow (\sin x)^3.$$

In the notation of the function $y = \sin^3 x$, you need to be able to see separately, one after the other, the two functions (sine and power) from which it is composed. This is easier to do if this function is written as $y = (\sin x)^3$.

For clarity, we will initially help the reader recognize complex functions using color. In our example

$$y = (\sin x)^3 \quad \text{или} \quad y = \sin^3 x$$

In the general case, to apply the rules of differentiation of a complex function (“Algebra and principles of analysis 9-10”, paragraph 21)

$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$

it is necessary to be able to “see” this function in the form $f(g(x))$. To do this, color will help us first. Distance between two examples.

Let's differentiate the function

$$y = \sin 2x = \sin u, u = 2x$$

(each function has its own color):

$$y' = (\sin u) \cdot (2x)' = (\cos u) \cdot 2 = 2\cos 2x.$$

⟦folio 27⟧

(But not cos 2x.)
Exactly the same
$$y = \sin^3 x = u^3, \quad u = \sin x;$$
$$y' = (u^3)' \cdot (\sin x)' = (3u^2) \cdot (\cos x) = 3 \sin^2 x \cos x.$$

(But not cos³ x.)
In practice, such differentiation of an arbitrary city is shorter and simpler, at least without introducing u into the notation.

The art of differentiating a complex function lies in the ability to see at the moment of differentiation only one function (namely, the one being differentiated at a given moment), while not noticing others - their vision is open until the moment of their differentiation.

Here are a few more demonstration examples, without introducing the intermediate “u”, in the way that differentiation of a complex function is usually carried out and written by those who have the fluent skill of such differentiation. Only, as before, we will write each differentiable function and its arbitrary one in the same color.

$$y = (2x^4 - 5x^2 + 6)^8;$$
$$y' = 8(2x^4 - 5x^2 + 6)^7 \cdot (8x^3 - 10x).$$
$$y = \sqrt{R^2 - x^2} = \left(R^2 - x^2\right)^{\frac{1}{2}};$$
$$y' = \frac{1}{2}\left(R^2 - x^2\right)^{-\frac{1}{2}} \cdot (-2x) = \frac{-x}{\sqrt{R^2 - x^2}}$$

The next complex function is
$$y = \sin^3 5x.$$

it is, as can be seen at least by the number of colors, a composition of three functions: 1) blue; 2) exponentiation; 3) multiplication by 5.

Let's differentiate it:
$$y = \sin^3 5x;$$
$$y' = \left(3 \sin^2 5x\right) \cdot \left(\cos 5x\right) \cdot \left(5\right) = 15 \left(\sin^2 5x\right) \cos 5x.$$

Since changing the places of the compound does not change the product, it goes without saying that you can sort through the functions for differentiation in any order.

A few more examples:
$$y = \mathrm{tg} x^3; \quad y' = \frac{3x^2}{\cos^2 x^3}.$$
Function

we differentiate as a product of a function using the formula $(uv)' = u'v + v'u$:
$$y' = \left(x^2\right)' \left(\ln x^3\right) + \left(x^2\right)' \cdot \left(\ln x^3\right)' = 2x \ln x^3 + x^2 \cdot \frac{1}{x^3} \cdot \left(3x^2\right) = 2x \ln x^3 + 3x.$$

$$y = 2x^3 - 5x;$$
$$y' = 2x^3 - 5x \ln 2 \cdot \left(3x^2 - 5\right)$$

At the difference. Differentiate using multi-color notation as necessary:
1. $y = (x^3 + 2)^4$; 2. $y = \sqrt{1 + 5x^2}$;
3. $y = e^{x^2 - 3x}$; 4. $y = \ln (2x^3 - 4x^2)$;
5. $y = \lg (2x^3 - 4x^2)$; 6. $y = 5^{\sin x}$;
7. $y = \log_{0.3}(8x^2 - 2x^3)$;
8. $y = \cos (2x - 1)$; 9. $y = \cos^2 3x$;
10. $y = \sqrt{\mathrm{tg} x}$; 11. $y = x \mathrm{tg}^2 x$;
12. $y = \sin \sqrt{ax}$; 13. $y = \ln \sin x$;
14. $y = 3^{\frac{1}{x}}$; 15. $y = \frac{1}{\cos 2x}$.

16. Prove that the function $y = c \sqrt{1 + x^2}$ serves as a solution to the differential equation $y' = xy / (1 + x^2)$.

Amendments
1) In «Kvant» No. 1 on p. 57 in the second equation of problem 1 of option 1, 15 was mistakenly printed together with 55.
2) In the last paragraph on p. 47 «Kvant» No. 2 above the 1st, 4th, 7th bold letters A and the 1st, 3rd, 5th, 6th, 8th bold letters B there should be a line (A, B), missed due to the fault of the printing house.
