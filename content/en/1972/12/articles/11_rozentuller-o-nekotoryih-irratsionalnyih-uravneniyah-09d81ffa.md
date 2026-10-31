---
id: 1972-12-rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa
issue: kvant_1972_12
year: 1972
number: "12"
title: About some irrational equations
authors:
  - Розентуллер В. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 54
page_labels: 51-52
tag: C2O4
lang: en
source: kvant_digital
extraction: vision
content_sha256: b0c694fa0e3008c7fcdfdc7316fbc0363336d5ffe92216f36d560da608920e4f
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/11_rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa.md
source_content_sha256: 42fcb89791fdeccc9509e02bee6f43dd8ad4ad46dbef7f5e6db3002dcce41101
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

About some irrational equations

V. M. Rosentuller

Techniques for solving irrational equations were discussed in detail in the article by A. M. Grigoriev “Irrational Equations” («Kvant» No. 1, 1972). But the general example is not always the best. This article uses three examples to demonstrate one method that allows you to quickly and “beautifully” solve certain (in fact, not only irrational) equations.

Example 1. Solve the equation:

$$\sqrt{x - 30} + \sqrt{2x + 4} = 8.$$

Solution. ODZ is determined by a system of inequalities

$$\begin{cases} x - 30 \geq 0, \\ 2x + 4 \geq 0, \end{cases}$$

where

$$x \geq 30.$$

Then you can proceed like this. Let's square both sides and get:

$$x - 30 + 2x + 4 + 2\sqrt{2x^2 - 56x - 120} = 64,$$

$$2\sqrt{2x^2 - 56x - 120} = 90 - 3x.$$

We have to square both sides of this equation again*):

$$8x^2 - 224x - 480 = 8100 - 540x + 9x^2,$$

$$x^2 - 316x + 8580 = 0,$$

$$x_{1,2} = 158 \pm \sqrt{158^2 - 8580} = 158 \pm \sqrt{16884} = 158 \pm 128;$$

$$x_1 = 286, x_2 = 30.$$

*) In this case, it is already clear from the last equation that $x \leq 30$, and only $x = 30$ needs to be checked, but this is an accident.

The check shows that $x_1 = 286$ is a constructed root, and $x_2$ satisfies the conditions of the problem.

Answer: $x = 30$.

We solved the equation, which required squaring it twice and checking the roots. Isn't there a simpler solution?

We have already defined the ODZ: $x \geq 30$. Is it possible to immediately use this when solving this equation? Let's try.

ODZ allows: $x = 30$ and $x > 30$. Let's check $x = 30$. Let's substitute the value $x = 30$ into this equation:

$$\sqrt{30 - 30} + \sqrt{60 + 4} = 8,$$

$$0 + 8 = 8,$$

$$8 = 8.$$

We received the honor. Therefore, $x = 30$ is the root of this equation. Now all that remains is to check $x > 30$.

For $x > 30$ we have $\sqrt{x - 30} > 0,$

$$\sqrt{2x + 4} > 8,$$

where

$$\sqrt{x - 30} + \sqrt{2x + 4} > 8.$$

Therefore, any $x > 30$ does not satisfy the equation. The only answer left is $x = 30$.

Example 2. Solve the equation:

$$5\sqrt{2x - 24} + 3\sqrt{5x - 59} + \sqrt{x - 8} + \sqrt{3x - 20} + \sqrt{x + 13} + 2\sqrt{x + 24} = 26.$$

Solution. ADL is determined

⟦folio 52⟧

system of inequalities:

$$\begin{cases} x \geq 12, \\ x \geq 11,8, \\ x \geq 8, \\ x \geq 6\frac{2}{3}, \\ x \geq -13, \\ x \geq -24, \end{cases}$$

whence $x \geq 12$.

Thus, ODZ allows: $x=12$ and $x>12$.

Let's check $x=12$: $5\sqrt{24-24} + 3\sqrt{60-59} + \sqrt{12-8} + \sqrt{36-20} + \sqrt{12+13} + 2\sqrt{12+24} = 0 + 3 + 2 + 4 + 5 + 12 = 26$.

We received the honor. Therefore, $x=12$ is the root of the equation.

Now let's check $x>12$:

$$5\sqrt{2x-24} > 0,$$

$$3\sqrt{5x-59} > 3,$$

$$\sqrt{x-8} > 2,$$

$$\sqrt{3x-20} > 4,$$

$$\sqrt{x+13} > 5,$$

$$2\sqrt{x+24} > 12.$$

Hence $5\sqrt{2x-24} + 3\sqrt{5x-59} + \sqrt{x-8} + \sqrt{3x-20} + \sqrt{x+13} + 2\sqrt{x+24} > 26,$

which contradicts the conditions of the problem. The only answer left is $x=12$.

Example 3. Solve the equation:

$$\sqrt{x(x+1)} = \sqrt{x+3} - \sqrt{1 + \frac{1}{x^2}}.$$

Solution. Let's group the terms of the equation like this:

$$\sqrt{x^2+x} + \sqrt{1 + \frac{1}{x^2}} = \sqrt{x+3}.$$

Let's square both sides:

$$x^2+x+1 + \frac{1}{x^2} +$$

$$+ 2\sqrt{(x^2+x)\left(1 + \frac{1}{x^2}\right)} = x+3,$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = x+3 - x^2 - x - 1 - \frac{1}{x^2},$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = 2 - \left(x^2 + \frac{1}{x^2}\right).$$

It is known that $x^2 + \frac{1}{x^2} \geq 2$, but $\sqrt{x^2+x+1 + \frac{1}{x}} \geq 0$, so $x^2 + \frac{1}{x^2} = 2$ and $\sqrt{x^2+x+1 + \frac{1}{x}} = 0$.

The first equality is possible when $x^2=1$, whence $x_1=1; x_2=-1$, and the second $\sqrt{x^2+x+1 + \frac{1}{x}} = 0$ when $x=-1$. Checking shows that $x=-1$ is the root of the equation.

Answer to the crossword puzzle (see page 4 of the cover)

Horizontal:

8. Farad. 9. Apogee. 10. Shift. 11. Frequency. 12. Gauss. 15. Inertia. 16. Diameter. 18. Ebonite, 19. Boron. 20. Budker. 23. Segment. 25. Kelvin. 28. Quantum. 29. Calorie. 30. Photon. 33. Work. 34. Nucleon.

Vertical:

1. Dirac. 2. Pendant. 3. Spectrum. 4. Cato. 5. Vanadium. 6. Pendulum. 7. Descartes. 13. Archimedes. 14. Impulse. 17. Bsr. 21. Tokamak. 22. Medina. 24. Tantalum. 26. Isotope. 27. Lorenz. 31. Photon. 32. Jacobi.
