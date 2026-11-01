---
id: 1986-10-kaymin-reshenie-zadach-i-postroenie-algoritmov-84471188
issue: kvant_1986_10
year: 1986
number: "10"
title: Solving problems and building algorithms
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 52
page_labels: 47, 49, 50
tag: ND9D
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3a2c22bb68776e984edbd9145a2e659a4ab2992dcc509d6d4d709bb4c6e1462a
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/17_kaymin-reshenie-zadach-i-postroenie-algoritmov-84471188.md
source_content_sha256: d79888c33118941c0e71839c76bbd5ed962fb78d7a94c9e7c8662feef9d71cd7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Solving the problem and constructing algorithms

Candidate of Technical Sciences
V. A. KAIMIN

Tasks, tasks, tasks... Our studies, work and personal life are an everyday, daily solution to a problem - educational and arbitrary, engineering and scientific, organizational and personal. The qualifications and competence of the work, engineer and specialist are determined by his knowledge and ability to solve problems that arise in the work. The first step in solving a problem is its formulation.

The second stage of solving the problem is the selection of means and methods of solution. To solve complex problems, we draw up plans in which auxiliary nodtasks are identified, and then methods and means are selected to solve the allocated nodtasks. The last stage is the implementation of the selected plans and solution methods, ending in obtaining the required results.

When it comes to solving a problem using a computer, the selection of algorithms to solve the problem takes center stage. In this and the next note, we will talk about the systematic construction of algorithms in relation to those problems that are solved in the course “Fundamentals of Information and Computer Science” in the 9th and 10th grades.

The key steps in the systematic construction of algorithms can be illustrated by the following diagram (Fig. 1). Let's see how this production

⟦folio 49⟧

Given: $a$ — initial angle [rad],
$v_0$ — initial speed [m/s].
Required: $l$ — flight range [m].

Connection:
$l = v_{x_0} t$ — flight range,
$-g t^2/2 + v_{y_0} t = 0$ — flight equation,
$v_{x_0} = v_0 \cos \alpha$ — horizontal speed,
$v_{y_0} = v_0 \sin \alpha$ — vertical speed,
$g = 9,81$ — free fall acceleration.

At: $v_0 > 0$ and $0 < \alpha \leq \frac{\pi}{2}$.

Method
$$\begin{cases}
l = vx0 \cdot t, \\
t = 2vy0/g, \\
vx0 = v0 \cdot \cos \alpha, \\
vy0 = v0 \cdot \sin \alpha, \\
g = 9,81.
\end{cases}$$

Algorithm
alg range (weight $a, l, v0$)
arg $v0, a$
res $l$

start $g, vx0, vy0, t$
$g := 9,81$
$vx0 := v0 \cdot \cos \alpha$
$vy0 := v0 \cdot \sin \alpha$
$t := 2vy0/g$
$l := vx0 \cdot t$
con

***

For elementary problems, solution methods can be obtained in an exact analytical form. For complex problems, when an explicit system of calculation formulas cannot be obtained, methods of approximate solutions that require a large amount of calculation are used. To approximately calculate a certain value $y$, a certain sequence of approximations is determined: $y_0, y_1, y_2, \dots$, which in the limit tend to the desired value $y = \lim_{n \to \infty} y_n$. The sequence of approximations $y_k (k=0,1,2)$ is usually chosen so that the estimated value $y_k$ depends on the previous one

Fig. 2. Calculation of the area of ​​the bulb.

Fig. 3. The distance between the solution a) the initial moment, b) the current moment.

Fig. 4. Range of a thrown stone.

⟦folio 50⟧

I. V. Kurchatov:
first steps
at LPTI

(For the beginning, see p. 3)

(Kurchatov and Sinelnikov do not indicate what kind of liquid the tube with the piston was placed in; they write that they lowered “... the end of the tube with the foil attached into the vessel with the liquid and carefully blew in air.”) Under normal temperature conditions, σ for a number of liquids (ethyl ether, diethylamine, etc.) lies in the range of 0.015-0.020 J/m³. Let's put σ=0.015 J/m². Then, substituting this value of σ and d=0.5 μm into (*), we find the desired value Δp: Δp=1.2·10⁵ Pa (~1 atm) - a fairly high pressure! No wonder the authors wrote that they removed the air in a cylindrical tube “with caution.” It was necessary that the foil did not peel off from the end of the tube, and most importantly, did not tear. The foils used by Kurchatov and Sinelnikov were strong enough to withstand the applied pressure. The same follows from calculations (using known formulas for the resistance of materials for membranes), according to which the stress developing at the value of Δp considered by us is less than the strength limit of the algorithm.

(Note that Laplace’s formula for similar purposes was used in 1923 by none other than A. Einstein in joint experimental work with his friend, physician G. Muhsam. In this work, a technique was proposed for “experimentally determining the size of channels in filters” (that was the name of the corresponding article, which studied porous filters used for bacteriological and medical purposes). According to the minimum value of Δp, starting from which the effects through filter and formed bubbles in the vessel with liquid where this filter was placed, the maximum diameter of the pores (channels) in the filter was determined.)

As can be seen from the estimates, responses with a diameter of less than 0.5 microns could completely go unnoticed by Hartig. Meanwhile, the flow of electrons through such responses in the filter is more than enough to be recorded in experiments. The goal of the work of Kurchatov and Sinelnikov, achieved as a result of their simple and red control experiments, was to show the fallacy of the conclusions made by Hartig about the permeability of solid (defect-free) thin filters for slow electrons.
