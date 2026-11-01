---
id: 1987-8-golovolomki-dba2b091
issue: kvant_1987_8
year: 1987
number: "8"
title: Puzzles
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 35
page_last: 37
page_labels: 33, 35
tag: 5UCM
lang: en
source: kvant_digital
extraction: vision
content_sha256: e0aaefb08d672df25ea8b1348d29f691f9447ecc032a1c1fed85feecc22f273a
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/08_golovolomki-dba2b091.md
source_content_sha256: 60d48006094241fc88e5079b19b29cf353c0b1e47810833b4f06c429e48d7179
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

PUZZLES
1. The words “numbers” and “sima” consist of the same letters. Consider these letters in the empty cells of the square so that in each column, in each line and on each of the two diagonals of the square there are all five of these letters.
N. K. Antonovich

The designation $e$ was first introduced by Leonhard Euler (1707–1783). He also calculated the number $e$ with 23 digits, using the infinite number series representation of $e$: $e=1+\frac{1}{1!}+\frac{1}{2!}+\dots+\frac{1}{n!}+\dots$, derived by Daniel Vernoulli (1700–1782).

$e^{i\pi}+1=0$

2. Replace the letters with numbers so that there are numbers on each line. One letter should correspond to the same numbers, different numbers should correspond to different numbers.

L. Euler obtained a remarkable result associated with the definition of the function $w=e^2$ for complex values ​​$z$, which laid the foundation for the mathematical field in the complex domain - the theory of functions of a complex variable.

⟦folio 35⟧

measures, if $X_0 = Y_0 = A$, then, adding the laws of motion of flat matrices, we obtain a solution that describes a finite matrix rotating counterclockwise when viewed from above:

$$x = x_1 + x_4 = A \cos \omega_0 t,$$
$$y = y_1 + y_4 = A \sin \omega_0 t.$$

We can also describe a finite matrix rotating clockwise:

$$x = x_1 - x_4 = A \cos \omega_0 t,$$
$$y = y_1 - y_4 = -A \sin \omega_0 t.$$

And vice versa, adding these two solutions for matrices rotating in different directions, we again obtain oscillations lying in the same plane.

Now it is clear that the final matrix does not serve the same period as the matrix oscillating in the plane. This is a consequence of the linearity of the equation of motion!

All of the above is essentially a manifestation in mechanics of a general physical principle: if a physical system is described by linear equations, then the principle of superposition operates in it - the sum of solutions is also a solution.

Let us now consider the case $B_0 \neq 0$. Solutions (3), which describe vibrations of the matrix in one plane, no longer satisfy equations (1). However, they are satisfied with steep swings! Indeed, the law of motion $x = A \cos \omega t, y = A \sin \omega t$ satisfies the equations provided that $\omega^2 = \omega_0^2 - \omega_B^2$ (check!). Solving this quadratic equation, we find:

$$\omega_{1,2} = -\frac{\omega_B}{2} \pm \sqrt{\omega_0^2 + \omega_B^2} \approx -\frac{\omega_B}{2} \pm \omega_0$$

(since $\omega_B \ll \omega_0$). Thus, two solutions are obtained: a matrix rotating counterclockwise with a frequency of $\omega_1 = \omega_0 - \omega_B/2$, and a matrix rotating clockwise with a frequency of $|\omega_2| = \omega_0 + \omega_B/2$.

Amendment
In the Ion issue «Kvant» in the section “Problem «Kvant» on figure to problem F1062 the point $C$ has disappeared. The absence of a magnetic field leads to the fact that the final matrix rotates in different directions, we again get oscillations lying in the same plane.

At $B_0 = 0$, the addition of two solutions for matrices rotating in different directions gives oscillations in the same plane. With $B_0 \neq 0$ the result is a sum of steep vibrations with slightly different frequencies, a kind of “steep beat”:

$$x = A \cos \omega_1 t + A \cos \omega_2 t = 2A \cos \omega_0 t \cdot \cos \frac{\omega_B}{2} t,$$
$$y = A \sin \omega_1 t - A \sin \omega_2 t = -2A \cos \omega_0 t \cdot \sin \frac{\omega_B}{2} t.$$

This is nothing more than oscillations of the matrix with a frequency of $\omega_0$ in a plane, which itself slowly rotates with a frequency of $\omega_B/2$, i.e., exactly what we need. From here we immediately get the answer: the plane of the rubber matrix rotates with an angular velocity $\omega_B/2 = qB_0/2m$ and turns through an angle $2\pi$ in the time:

$$\tau = \frac{4\pi}{|\omega_B|} = \frac{4\pi m}{|qB_0|}.$$

The rotation of the matrix rubber plane is very similar to the behavior of the Foucault matrix. As we just found out, this movement is the sum of a clockwise and counterclockwise rotation at slightly different frequencies. Can this idea be applied to the Foucault matrix?

Let us imagine for simplicity that the matrix is ​​located at the north pole. Then an observer who does not rotate with the Earth, but maintains a constant orientation relative to the starry sky, will discover the following. If he deflects the matrix and releases it without any real speed, then the matrix oscillates in a fixed plane with a period of $T = 2\pi \sqrt{l/g}$. If he runs the matrix in a circle, it rotates with frequency, being able to bring the correct figure, we make a clarification in the problem condition: the device is located at the point $C$ such that $|AC|:|AB|:|BC| = 3:2:4,5$.

Having the opportunity to give the correct figure, we make a clarification in the problem statement: the device is located at the point $C$ such that $|AC|:|AB|:|BC| = 3:2:4,5$.

toya $\omega_0 = \sqrt{g/l}$ regardless of the direction of rotation. An observer standing on the Earth and rotating with it sees that the plane of the rubber Foucault matrix rotates clockwise (when viewed from above) at a speed of 1 revolution per day (synchronously with the starry sky, relative to which this plane is not visible). From the point of view of this observer, the finite matrices still perform circular motion, but their angular velocities have changed: when rotating counterclockwise $\omega_1 = \omega_0 - \omega_3$, and clockwise $\omega_2 = \omega_0 + \omega_3$, where $\omega_3 = 2\pi/cутки = 7,27 \cdot 10^{-5} c^{-1}$ is the angular velocity of the Earth's rotation. Adding these movements according to formulas (4), we obtain oscillations in a plane rotating clockwise with an angular velocity $\omega_3$, as it should be.

We see, therefore, that the movements of a charged matrix in a magnetic field and the Foucault matrix are extremely similar. In both cases, the rubber plane rotates, and clockwise and counterclockwise rotation occurs at different angular speeds. The physical reasons for this behavior are completely different: for a matrix in a magnetic field it is the Lorentz force, and for a Foucault matrix it is the force that we describe its movements from the point of view of an observer located on the Earth and rotating with it. For him, the Foucault matrix moves as if the ball, in addition to the gravity force and the tension force of the thread, was acted upon by an additional force, similar to Lorentz, which would be proportional to the speed and periodic to it. This force is combined with the Corollas force and represents a special case - additional forces that must be taken into account when using non-inertial (including rotating) reporting systems.

D. A. Kuptsov, M. M. Tsypin

We inform participants of the “Problem” competition that the deadline for sending a solution to this problem has been extended until October 1.
