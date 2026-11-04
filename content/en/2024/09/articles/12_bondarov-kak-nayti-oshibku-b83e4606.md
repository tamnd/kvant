---
id: 2024-9-bondarov-kak-nayti-oshibku-b83e4606
issue: kvant_2024_9
year: 2024
number: "9"
title: How to find the error
authors:
  - Бондаров М. Н.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 55
page_labels: 44-53
lang: en
source: kvant_digital
extraction: vision
content_sha256: 56000f77e62239d0172068f4c616a767b4139a565a0173e833c416024a909b29
prompt_sha256: draft-1
translated_from: content/ru/2024/09/articles/12_bondarov-kak-nayti-oshibku-b83e4606.md
source_content_sha256: 704ba09f388273a3a05225482504a6545c588fe692357a9e87933b7caa3fd7c0
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 44⟧

APPLICANT PRACTICUM

How to find the error
M.BONDAROV

As you know, no one is immune from mistakes. Even those who deeply understand physics, even quantities are scientists.

In 1905, in his doctoral dissertation, Albert Einstein proposed a new theoretical method for determining the radius of molecules and Avogadro's constant. The dissertation was approved, and Einstein became a doctor. As we later found out, neither Einstein himself nor his opponent noticed one serious error in the calculations. It was only a few years later that this, as one of Einstein’s biographers [1] writes, “elementary, but not trivial” error was discovered, because the results of the experiment diverged from the values ​​obtained from the equation derived in the dissertation.

This article will not talk about cases from the history of physics, but about errors that schoolchildren made when solving physics problems on the Unified State Exam, optimization and other tests. In this case, we will assume that the student was able to successfully understand the physical laws of the problem assigned to him, wrote out all the equations necessary for the solution, but in the process of reaching the final result made an error in mathematical transformations or calculations. And now his main problems are identifying and eliminating error assumptions. We will focus only on the analysis of letter answers. For each problem, several possible answers will be offered, among which there will certainly be a correct one.

So, our goal is to be able to recognize all the incorrect answers without solving the problem in a non-presidential manner, relying only on a deep understanding of the patterns of the processes described in the conditions. Here are the “names” of the main helpers in achieving this goal: dimension, symmetry, special case.

Let's start with a problem for which the knowledge of a seventh-grader is sufficient.

Task 1. Gonchik.edem is on the highway and is guided by the metegraph signs that ripple along the highway. The racer successively jumps to speed $v_1, v_2, v_3, v_4$ when we pass the mismo of the next block. What is the average speed $v_{\text{cp}}$metequivla?

The method for solving the problem is well known. Let the distance between the columns be $l$. Then the average speed $v_{\text{cp}}$ is defined as the ratio of the entire path $4l$ to the time $t$ of its passage, where $t = l/v_1 + l/v_2 + l/v_3 + l/v_4$. In other words, all that remains is to divide $4l$ by $(l/v_1 + l/v_2 + l/v_3 + l/v_4)$, reduce by $l$ and the goal is achieved:

$$v_{\text{cp}} = \frac{4}{\frac{1}{v_1} + \frac{1}{v_2} + \frac{1}{v_3} + \frac{1}{v_4}}.$$

⟦folio 45⟧

---
running_head:
folio:
---

Mathematical errors may appear if there is a desire to continue transformations in order to reduce the “story” of a fraction. Here are some of the possible answers, from which you need to choose the only correct one:

A. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1 + v_2 + v_3 + v_4}$;

V. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4}$;

C. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4 + v_2v_3v_4}$;

D. $v_{cp} = \frac{v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4 + v_2v_3v_4}$.

As a rule, answers A and B are usually discarded first. Obviously, answer A fails the dimensional test. In fact, the left side of this formula has the dimension of speed (m/s), and the right side has the dimension of the cube of speed (m/s)³. What is striking about answer B is its asymmetry. Note that in the denominator of this fraction the quantities $v_1$ appear 3 times, and the quantities $v_2$, $v_3$ and $v_4$ only 2 times. But in the conditions of the problem, all speeds are equal, so none of them should stand out in the answer. Let us generalize this observation: if there is some symmetry in the conditions of the task, then a certain symmetry must inevitably appear in the answer.¹ In case B, this is not observed, and this answer cannot be correct.

Thus, we are left with only two last answers, each of which successfully passed the test for dimensionality and symmetry. Let us now consider such a special case when the answer is very iden. Let the driver in all sections have the same speed $v_1 = v_2 = v_3 = v_4 = v$, which in this case is obviously equal to the average speed. Let's notice all the speeds in the answers C and D to the same and equal v. As a result, the correct expression is $v_{cp} = v$ for answer C and the counterintuitive expression is $v_{cp} = v/4$ for answer D.

¹ An honorable case with an experienced physics typist who discovered an error in the answer without solving tasks is described in article [2].

So, all erroneous answers have been discarded and we have found the correct answer C. Having carefully carried out mathematical transformations, we will make sure that the answer C is obtained from formula (*).

The observant reader will undoubtedly have noticed that among the possible answers, the most common incorrect answer is not:

E. $v_{cp} = \frac{v_1 + v_2 + v_3 + v_4}{4}$.

This is not accidental, because we are going to consider only those answers that were obtained not by chance (at random), but as a result of a deep understanding of the physical processes described in the problem, albeit in the presence of mathematical errors. It is obvious that the equations written in the solution can hardly lead to answer E.

And yet, let's try to check the analysis and make sure that answer E cannot be correct. Again, a special case will help us: let it remain constant in the first three sections of the pot: $v_1 = v_2 = v_3 = v$, and in the last one it is very small: $v_4 \rightarrow 0$. What should be the average speed of the motorcyclist along the entire journey? It is obvious that due to the low speed $v_4$ the time $t$ of movement becomes very large (in the limit of one tends towards infinity: $t \rightarrow \infty$). This means that from the definition of average speed ($v_{cp} = s/t$) it should be, like $v_4$, also very small. Please note that at $v_4 \rightarrow 0$ in the case of the correct answer C, the average speed also turns out to be very small. But answer E gives an implausible result in this case: $v_{cp} = 3v/4$. (It is clear that for the analysis it was possible to assume low speed in any other section.)

Let's consider another problem of calculating the average speed, where sections of the path have different lengths.

Problem 2. The third part of the entire path was automatically projected at a speed of $v_1$, and the rest at a speed of $v_2$. What was the average speed of $v_{cp}$ automatic?

Possible answers:

A. $v_{cp} = \frac{2v_1v_2}{v_1 + v_2}$;

B. $v_{cp} = \frac{v_1 + 2v_2}{3}$;

C. $v_{cp} = \frac{2v_1 + v_2}{3v_1v_2}$;

⟦folio 46⟧

---
running_head:
folio:
---

D. $v_{\text{cp}} = \frac{3v_1v_2}{2v_1 + v_2}$;
E. $v_{\text{cp}} = \frac{3v_1v_2}{v_1 + 2v_2}$.

We analyze the answers in this problem similarly to the previous one. Starting with checking the dimension, it is easy to notice that in case C, when solving the problem, in the final expression, apparently, they forgot to turn the fraction over. Pozny this answer cannot be correct. The only symmetrical answer A is not suitable because symmetry is not present in the conditions and therefore should not be in the answer. Answer B is discarded for the same reason as answer E in the previous problem: in the case of very low speed, for example in the first section, the average speed should also be very small. However, when substituting $v_1 \rightarrow 0$ into the formula, we have $v_{\text{cp}} = 2v_2/3$, not $v_{\text{cp}} \rightarrow 0$.

It remains to make a choice between two positions, answers D and E, which successfully passed all the tests that allowed the first three answers to come out erroneously. Alas, the special case of equality of speed, which helped us in the past problem, will not help us either. In fact, for $v_1 = v_2 = v$ both formulas give the correct result: $v_{\text{cp}} = v$. Well, let's try another special case: a very high speed in the second section (in the limiting case $v_2 \rightarrow \infty$). Then the denominator of formula D can be neglected by the small value $2v_1$ compared to the very large value $v_2$, which leads to the answer

$$v_{\text{cp}} = \frac{3v_1v_2}{2v_1 + v_2} \approx \frac{3v_1v_2}{v_2} = 3v_1.$$

Let's make sure that answer D should be correct in our particular case. A third of the route was automated, moving slowly, and then the next two thirds rushed almost instantly, spending almost no time on it. In other words, in this case, in the time that the automatic vehicle spends, marveling at the first section at a speed of $v_1$, to cover the first third of the path $l$, the automatic vehicle will be able to cover the entire path $3l$. For this, very indo, its speed $v_{\text{cp}}$ must be second greater than the speed $v_1$ in the first third of the way.

Do a similar reasoning for formula E yourself and show that this leads to the erroneous result $3v_1/2$.

Let us now check our conclusions based on the analysis of the answers by solving the problem. Let the weight of the path be equal to $3l$, and all the time equal to $t$. Then the average speed

$$v_{\text{cp}} = \frac{3l}{t} = \frac{3l}{\frac{l}{v_1} + \frac{2l}{v_2}} = \frac{3v_1v_2}{2v_1 + v_2}.$$

That's right.

So, we are convinced that the working instructions for detecting possible errors in answers (as well as in intermediate formulas too) are three main methods of verification: dimension, symmetry and a special case. Of course, the most important thing is the first one: dimension. With its help, most types of errors are detected.

And here, probably, it has the following meaning. Food Lily there is at least one student who began to lose his height and temperature. At the same time, when solving a problem, errors in dimensionality will occur quite often. Moreover, in some cases, no great conditions are required to detect them. Here are just a few similar expressions that almost everyone who checks students’ work has encountered:

1) $s + v/t$; 2) $m - M^2$;
3) $I + R/U$; 4) $(F - m)a$.

Obviously, dimensional checking should be your constant companion if you want to solve problems accurately.

Please note that passing all the checks discussed above does not guarantee the correctness of the answer. These checks only allow you to discard new responses. But, according to this one, it is also very useful.

Let's now move on to the problem for ninth graders.

Problem 3. Find the force $T$ of tension between loads 2 and 3 in the system shown in figure 1. The masses of the loads are known, neglect the mass of the block. There is no friction. The acceleration of free nadiya is $g$.

⟦folio 47⟧

---
running_head:
folio:
---

Possible answers:
A. $T = \frac{2m_1m_3g}{m_1 + m_2 + m_3}$;
V. $T = \frac{2m_1m_2g}{m_1 + m_2 + m_3}$;
C. $T = \frac{m_1m_3g}{m_1 + m_2 + m_3}$;
D. $T = \frac{(m_1 + m_2 + m_3)g}{2}$;
E. $T = \frac{2m_1m_3g}{m_1 - m_2 - m_3}$.

The first two verification methods, which we successfully used in previous tasks, this time, alas, do not help. There is only one hope left - for a well-chosen special case.

In what case will the thread between loads 2 and 3 cease to be tensioned? Firstly, if we remove gruz with mass $m_3$: then there is nothing to pull the thread with. Secondly, when gruz $m_1$ is removed, the second and third will begin to fall freely, and the thread will not be taut again. It turns out that $T = 0$ with $m_1 = 0$ and $m_3 = 0$; This means that the number of tremors must include the product $m_1m_3$. This check is contradicted by answers B and D - we discard them. In case E, let’s pay attention to the “minuses” in the denominator: they should always cause some third of the tester’s answer to the reliability. In fact, the path gruz to the left of the block has the same total mass as the gruz to the right, i.e. $m_2 + m_3 = m_1$. Then, according to expression E, the thread must be tensioned by an infinitely large force. As you know, there cannot be such forces in the load system - we delete another answer.

Again I stopped at two answers that differed just a little. What if we try guess $m_2 + m_3 = m_1$ again? In this case, there is no acceleration in the system, and the lower thread will be tense $T = m_3g$. This is exactly what answer A produces, while answer C produces the incorrect result $T = m_3g/2$. However, another technique could have been used. Let's imagine that a very heavy gruz ($m_1 \rightarrow \infty$) is suspended on the right. Then the light left loads will not be able to prevent him from practically freely falling with an acceleration of $g$. At the same time, they themselves will rise with the same acceleration in magnitude (the threads are inextensible). And so that

a load of mass $m_3$ was lifted by acceleration $g$, the thread should be tensioned with a force $T = 2m_3g$. Substituting $m_1 \rightarrow \infty$ into formulas A and C, we are convinced that this is true only for answer A.

To test our reasoning, let's solve the problem. Let $a$ be the acceleration of the load, $T^*$ be the tension of the second thread. Then according to Newton's second law $m_3a = m_3g - T$, $m_2a = m_2g + T - T^*$, $m_1a = T^* - m_3g$. Solving this system, we get the correct answer A.

We have not yet considered the specifics of electrical problems. Time to move on to one for 10th graders.

Problem 4: Two resistance resistors $R_1$ and $R_2$ and two capacitors $C_1$ and $C_2$ are connected to a constant voltage source $U$ as shown in figure 2.

What charge $\Delta q$ will flow through the conductor AB over a sufficiently large period of time after closing the switch, if the capacitors were initially discharged?

Possible answers:
A. $\Delta q = \frac{C_2R_2 + C_1R_1}{R_1 + R_2}U$;
V. $\Delta q = \frac{C_1R_2 + C_2R_1}{R_1 - R_2}U$;
C. $\Delta q = \frac{(C_2 - C_1)R_1R_2}{R_1 + R_2}U$;
D. $\Delta q = \frac{C_2R_2 - C_1R_1}{R_1 + R_2}U$;
E. $\Delta q = \frac{C_2R_1 - C_1R_2}{R_1 + R_2}U$.

As usual, we start by checking for dimensionality, and it immediately gives us the first of the variable answers: C. Next. Noteworthy is the “minus” in the denominator of answer B. It is clear that at $R_1 = R_2$ (and in no other case!) an infinitely large charge cannot flow through section AB.

In what case will the charge not be more accurate than the jumper AB? It's obvious that this

⟦folio 48⟧

---
running_head:
folio:
---

will happen if the chain turns out to be symmetrical, i.e. Both the resistance of the resistors and the capacitance of the capacitors will become the same. Then, when substituted into the final formula, $R_1 = R_2$ and $C_1 = C_2$ should result in $\Delta q = 0$. This is not satisfied by answer A - we discard it.

The last two answers remain: D and E. Let's replace the first resistor with an ideal wire ($R_1 = 0$). Then all the charge passing through it will proceed further through the conductor $AB$ to the capacitor capacitor $C_2$. Answer D satisfies this condition, since when we substitute $R_1 = 0$ into it we have $\Delta q = C_2U$. At the same time, a similar substitution in answer E gives the wrong result: $\Delta q = C_1U$.

Note that in circuits with resistors and capacitors it is also useful to use two other limiting cases: $C = 0$, when there is no capacitor, and $R \rightarrow \infty$, when there is no conductor. Try to use them yourself to choose the correct one from the last two answers.

Let us again be convinced of the correctness of our conclusions, based only on the analysis of the answers, by solving the problem. After charging is completed, the current will stop and charges $C_1U$ and $C_2U$ will accumulate on the parallel-connected capacitors. This means that the total charge $q = (C_1 + C_2)U$ will flow through the resistors. The resistors are connected in parallel, so the charges passing through them must be inversely proportional to the resistances: $q_1 = qR_2 / (R_1 + R_2)$ and $q_2 = qR_1 / (R_1 + R_2)$. Consequently, in the direction from point A to point B, charge will flow through the conductor

$$\Delta q = q_1 - C_1U = (C_2R_2 - C_1R_1)U / (R_1 + R_2),$$
which is the same as answer D.

The considered examples show that checks for dimensionality, symmetry and special cases can effectively serve to detect errors when solving various physical problems. These examples are really basic. True, sometimes only with their help it is not possible to detect all errors in the answers. Then other examples should appear in our arsenal of response analysis; It is useful to pay attention in your answers to the nature of the dependence, roots, and uncertainties.

Let's move on to considering similar problems and start with a problem for ninth graders.

Problem 5. A passenger in the first carriage of a train of length l is transported along the platform. When he was near the last carriage, the train began to accelerate a. The passenger immediately ran at speed v. After what time t does he reach his valon?

Possible answers:

A. $t = \frac{v}{a} \sqrt{1 - \frac{2al}{v^2}}$;

B. $t = \frac{v}{a} \sqrt{1 + \frac{2al}{v^2}}$;

C. $t = \frac{v}{a} \left(1 - \sqrt{1 - \frac{2al}{v^2}}\right)$;

D. $t = \frac{v}{a} \left(1 + \sqrt{1 - \frac{2al}{v^2}}\right)$;

E. $t = \frac{v}{a} \left(1 - \sqrt{1 + \frac{2al}{v^2}}\right)$;

F. $t = \frac{v}{a} \left(1 + \sqrt{1 + \frac{2al}{v^2}}\right)$.

The answers, at first glance, are very similar. Dimension and symmetry will not help us here. We will have to explore extreme situations. Under the conditions of the problem, the only physical quantities that can change are: train length l, its acceleration a, and passenger speed v. Let's try to work with one of them; for example, let's begin to mentally reduce the length of the train to zero ($l \rightarrow 0$). Then the passenger at the initial moment of time is already near his car, therefore, the required time is $t = 0$. This is contradicted by all the answers except C and E. We were very lucky and with the help of only one passage to the limit we were able to identify four incorrect answers at once.

Let's now take a closer look at the ascending word for the remaining answers. Answer E cannot be correct and here's why. First, let us pay attention to the nature of the dependence of the exceptional time t on the length of the train l. Obviously, with a decrease in l, t must necessarily decrease, but according to formula E, everything should be the other way around. Secondly, the radical expression is greater than 1, therefore, for any values ​​included in the conditions, the quantity will be negative.

So, all incorrect answers have been successfully found. However, let's not rush: there is still

⟦folio 49⟧

---
running_head:
folio:
---

some interesting points that are useful to mention. Let us note that in the radical expression the quantities $a$ and $l$ are nearby. What if we continue with the root $a$ in the same way as with the length $l$? If you start to reduce the root $a$, then the time will increase in all answers except $C$ and $E$. And this completely contradicts the physical meaning. Let us consider the formula $C$ for the passage to the limit $a \rightarrow 0$. After substitution, we obtain an expression called in mathematics an uncertainty of the form $0/0$.

Note that we would have to deal with another type of uncertainty if we began to study the dependence of the required time on the speed $v$ of the passenger. Let this speed begin to grow unlimitedly $(v \rightarrow \infty)$. Again, all answers except $C$ and $E$ would contradict the physical meaning of the answer $t \rightarrow \infty$ and should therefore be discarded. In the remaining answers, the expression in brackets tends to zero, and the set in front of the brackets tends to infinity. At the moment we are faced with so many other types of uncertainty: $\infty \cdot 0$. What to do in such a situation? You can use, for example, the well-known relation $\sqrt{1 \pm x} = 1 \pm \frac{x}{2}$, which is valid for small $x (x \rightarrow 0)$. Then in case of answer $C$ we get

$$t = \frac{v}{a} \left( 1 - \sqrt{1 - \frac{2al}{v^2}} \right) \approx \frac{v}{a} \left( 1 - \left( 1 - \frac{2al}{2v^2} \right) \right) = \frac{v}{a} \frac{al}{v^2} = \frac{l}{v}.$$

From here it is immediately clear that at a very high speed the time becomes very small, as it should be in the implementation. Note that, purely formally, the answer $D$ is also correct in this problem.

When solving the problem, you need to equate the coordinates of the passenger $x_1 = vt$ and the first car $x_2 = l + \frac{at^2}{2}$, after which you get a quadratic equation $\frac{at^2}{2} - vt + l = 0$, the solution of which will be two roots corresponding to the answers $C$ and $D$. It is clear that the time from the answer $D$ corresponds to the situation when the passenger runs through the door of the carriage, but then the carriage finishes it.

And one more important note. When solving the problem, we assumed that the passenger would definitely finish his valon. However, at the passenger speed $v < \sqrt{2al}$ this is not accidental. The final formula must necessarily reflect that only when a high speed is reached (in our case, at $v \geq \sqrt{2al}$) does the passenger contract his own valon.

Let's consider another task for tenth graders.

Problem 6. A vertically located felling of length $l$, open with a mark, is half immersed in a vessel with rutium. The tube is closed with a finger and removed from the rutui. What is the length $x$ of the amount of rutui remaining in the tube? Atmospheric pressure is balanced by so much.rutui height $H$. The process is considered isometric.

Possible answers:

A. $x = \frac{H + l - \sqrt{H^2 + l^2}}{2}$;

B. $x = \frac{H + l + \sqrt{H^2 + l^2}}{2}$;

C. $x = \frac{(H + l)^2 - \sqrt{(H + l)^3 - \frac{Hl}{2}}}{2}$;

D. $x = \frac{H + l - \sqrt{H^2 + \frac{l^2}{2}}}{2}$;

E. $x = \frac{H + l - \sqrt{H^2 + 2Hl + 2l^2}}{2}$.

This problem is for 10th grade students, but even a 7th grader will easily notice that the answer $C$ has a problem with dimensionality at the root. Of course, you cannot subtract square meters from cubic meters. Fortunately, the rest of the answers pass the dimensional check.

It is enough to simply establish that two more answers – $E$ and $B$ – are incorrect. Indeed, the answer $E$ is not suitable, since the length of $x$ is negative for so many rutui:

$$\sqrt{H^2 + 2Hl + 2l^2} = \sqrt{(H + l)^2 + l^2} > H + l.$$

And in the answer $B$ the length of $x$ was greater than the length of $l$.rutui:

$$\sqrt{H^2 + l^2} \geq l, \quad x = \frac{H + l + \sqrt{H^2 + l^2}}{2} > \frac{2l}{2} = l.$$

⟦folio 50⟧

---
running_head:
folio:
---

It remains to make a choice between answers A and D. We can conduct a mental experiment... on the Moon. Since there is no atmosphere, there is nothing to hold the rud in the tube, and it must flow out completely. In other words, at $H \rightarrow 0$ there must be $x \rightarrow 0$. This corresponds only to answer A, which is correct.

It is interesting that if one immediately agrees to use only the limit passage $H \rightarrow 0$, then only with its help can one discard all incorrect answers.

Let's turn to the solution to the problem. Let us denote $p$ – the air pressure in the tube after it is removed, $\rho$ – the density of mercury. The atmosphere has a pressure of $p_0 = \rho g H$. In the manufacturing process $p_0 l/2 = p(l - x)$. The equilibrium condition for so much mercury in the tube is: $p = p_0 - \rho g x$. This gives the correct answer A.

The problems discussed above show how fruitful researching the answer can be. However, sometimes this research can begin already when analyzing the very conditions of the problem. Let's look at this using an example of a problem from the Unified State Exam version.

Problem 7. Under the action of a constant horizontal force $\vec{F}$, a wedge of mass $M = 1$ kg moves along a smooth horizontal surface of the table (Fig. 3). According to Sherakhova-

Fig. 3

my surface of the wedge, making an angle $\alpha = 30^\circ$ with the horizon, slides evenly (relative to the wedge) with a block of mass $m = 0,2$ kg. The coefficient between the block and the wedge is $\mu = 0,6$. Find the model of acceleration a of the wedge. Neglect air resistance. Make figure indicating the forces acting on the block.

Possible answers:

A. $a = \frac{F - mg(\mu \cos \alpha - \sin \alpha)}{M + m}$;

B. $a = g \frac{\mu + tg \alpha}{\mu tg \alpha + 1}$;

C. $a = \frac{m}{M + m} \frac{\mu - tg \alpha}{\mu tg \alpha + 1} g$;

D. $a = g \frac{\mu - tg \alpha}{\mu tg \alpha + 1}$;

E. $a = g \frac{\mu + tg \alpha}{\mu tg \alpha - 1}$.

Some USE problems have an interesting feature: the presence of depicted data that should not be included in the answer. To successfully solve such problems, you must definitely learn to recognize this extra data.

Note that the conditions of this problem explicitly specify the numerical values ​​of four physical quantities ($M, m, \alpha$ and $\mu$) and the neutron acceleration of free fall ($g = 10 \text{ m/c}^2$). However, the numerical value of the force $F$ acting on the wedge is missing. Therefore, its value cannot be included in the answer, which means that answer A is incorrect. But what about the acceleration of the wedge without knowing the magnitude of the force $F$?

Here we will be helped by the fact that, according to the conditions of the problem, the block slides uniformly with the wedge. Consequently, the accelerations of the block and the wedge relative to the ground are the same. It turns out that we can not use Newton’s second law for the wedge and, therefore, the mass $M$ of the wedge should not be included in the answer. However, the observant reader probably noticed that the conditions require avoiding drawings indicating forces acting only on the block. This hint confirms our assumption that the mass of the wedge will not be included in the solution.

It is noteworthy that the answer should not include not only the mass $M$ of the wedge, but also the mass $m$ of the block. Indeed, analyzing the possibility of answers and relying again on the dimension, it is not difficult to understand that to determine the acceleration $a$ in our arrangement there is only one value of the same location - the acceleration of free fall $g$ and two dimensionless quantities - the friction coefficient $\mu$ and the angle $\alpha$. The answer could also include the mass ratio $m/M$, but, as we found out, the mass $M$ of the wedge should not enter it, which means the mass of the block cannot enter either.

We are left with three “massless” answers. One of them – EG – is discarded, since it is allocated as a “minus” in the denominator: at $\mu tg \alpha = 1$the acceleration of the wedge should tend to infinity. Finally, you need to choose between answers B and D. The only difference in these answers is the sign in the numerator of the fraction. Let's remember the problem about

⟦folio 51⟧

---
running_head:
folio:
---

block on an inclined plane. It is easy to show that at $\mu < tg\alpha$ the block slides downwards along the plane, at $\mu > tg\alpha$ it remains motionless relative to the plane, and at $\mu = tg\alpha$ it either lies on it (at $v_0 = 0$) or slides uniformly (at $v_0 \neq 0$). To further analyze the answer, we turn the moving wedge into a stationary inclined plane: $a = 0$. From answer D it follows that $\mu = tg\alpha$. Whereas answer B produces the absurd $\mu = -tg\alpha$. We invite the reader to find out for himself what the physical nature of the appearance of the minus sign is in the correct expression D for acceleration at $\mu < tg\alpha$.

Let us now give a brief solution to the problem. Since, according to the condition, the block moves uniformly relative to the wedge, the accelerations of the wedge and the block relative to the ground are the same. Let's direct the $x$ axis horizontally, and the $y$ axis vertically. Then, according to Newton’s second law for the block in projections onto these axes

$$ma = F_{\text{tp}} \cos \alpha - N \sin \alpha,$$
$$0 = F_{\text{tp}} \sin \alpha + N \cos \alpha - mg.$$

Taking into account that when sliding $F_{\text{tp}} = \mu N$, we obtain

$$ma = N (\mu \cos \alpha - \sin \alpha),$$
$$mg = N (\mu \sin \alpha + \cos \alpha).$$

Dividing the first equation by the second, we have

$$\frac{a}{g} = \frac{\mu \cos \alpha - \sin \alpha}{\mu \sin \alpha + \cos \alpha},$$

where

$$a = \frac{g (\mu - tg\alpha)}{\mu tg\alpha + 1} \approx 0,17 \text{ m/c}^2.$$

It is not so common to encounter cases when an answer goes through several stages of verification and seems very plausible, but one of the special cases contradicts the answer. This can work if we have not paid attention to the range of acceptable values. Here, for example, at first glance, is a somewhat challenging task.

Problem 8. A force $\vec{F}$ directed upward at an angle $\alpha$ to the horizon (Fig. 4) is applied to chalk of mass $m$, located on a horizontal surface. Coefficient of claim between body and surface $\mu$. Find the acceleration $a$ of the body.

Solving the problem, it would seem, is not difficult. Let's write the equation of Newton's second law in projections onto the horizontal and vertical axes:

$$F \cos \alpha - F_{\text{tp}} = ma,$$
$$N + F \sin \alpha - mg = 0.$$

We learn that when sliding $F_{\text{tp}} = \mu N$. Then the desired acceleration of the body

$$a = \frac{F \cos \alpha - \mu (mg - F \sin \alpha)}{m}.$$

The answer has been received, but... it is incorrect. Let's try to find the error by re-reading the conditions and analyzing our solution. Are there any inconsistencies in them? It is obvious that at small values ​​of force $F$ the body does not yet begin to move, remaining at rest. To determine the magnitude of the friction force, we used the formula $F_{\text{tp}} = \mu N$, assuming that the body is sliding. That is why, when substituting $F = 0$ into our answer, we get the awkward $a = -\mu g$.

But that's not all! And what will happen at large values ​​of force $F$? Please note that along with the growth of $F$ the force of the normal support reaction $N$ decreases and at $F = mg/\sin \alpha$ it becomes equal to zero, i.e. the body breaks away from the support. Two forces disappear simultaneously: $\vec{N}$ and $\vec{F}_{\text{tp}}$, and the body moves under the influence of the two remaining forces: $\vec{F}$ and $\vec{m}\vec{g}$. The acceleration can be found by writing the equation of Newton's second law in vector form: $\vec{F} + \vec{m}\vec{g} = m\vec{a}$. From figure 5 using the cosine theorem $(ma)^2 = F^2 + (mg)^2 - 2Fmg \sin \alpha$ one can easily find the body acceleration model:

$$a = \frac{\sqrt{F^2 + (mg)^2 - 2Fmg \sin \alpha}}{m}.$$

If desired, using the theorem of sines, one can find the angle at which the acceleration of the body is directed towards the horizon.

⟦folio 52⟧

---
running_head:
folio:
---

Now we can finally write down the correct answer:
$$a = 0 \text{ при } 0 \leq F \leq \frac{mg}{\cos \alpha + \mu \sin \alpha},$$
$$a = \frac{F \cos \alpha - \mu (mg - F \sin \alpha)}{m}$$
at $$\frac{mg}{\cos \alpha + \mu \sin \alpha} < F \leq \frac{mg}{\sin \alpha},$$
$$a = \frac{\sqrt{F^2 + (mg)^2 - 2Fmg \sin \alpha}}{m} \text{ при } F \geq \frac{mg}{\sin \alpha}.$$
When analyzing the answer, sometimes it happens involuntarily to come across a paradoxical situation. And only a deep understanding of the nature of the applicability of the laws of physics can help in part to get out of a difficult situation. Let's look at this using the following problem as an example.

Problem 9. A ball with a mass of $m_1 = 2$ kg, moving at a speed of $v = 3$ m/s, collides with a stationary ball with a mass of $m_2 = 3$ kg. Between the balls we make a central impact, as a result of which the attacking ball stops. How much broom $Q$ was released upon impact?

Solving this problem, as a rule, does not cause serious difficulties. Indeed, it is obvious that the standard application of the law of conservation of momentum
$$m_1v = m_2u$$
and the law of conservation of energy
$$Q = \frac{m_1v^2}{2} - \frac{m_2u^2}{2},$$
we quickly come to the answer
$$Q = \frac{m_1v^2}{2}\left(1 - \frac{m_1}{m_2}\right) = \frac{(m_2 - m_1)m_1v^2}{2m_2} = 3 \text{ Дж.}$$

If you have acquired the habit of analyzing the received answer, you will certainly pay attention to the “minus” in parentheses. It turns out a country of things: if the masses of the balls are equal, heat should not be released upon impact. Moreover, we obtain an even more external result if we assume that the incident ball will be heavier than the stationary one. Indeed, for $m_1 > m_2$ $Q < 0$. It turns out that in this case, upon impact, heat not only is not released, but is, as it were, “pumped” into the system of balls. There is a contradiction between the answer we received and the physical meaning.

Let's try to find out the reason. For this purpose, we cannot find better help than conservation laws. If the momentum of the incident ball was equal to $p$, then the second ball has the same momentum after the collision. The initial energy of the system is located at the first ball and was equal to $E_1 = p^2/(2m_1)$. After the collision, the energy transferred to the second ball: $E_2 = p^2/(2m_2)$. With this form of notation, it is immediately clear that if the masses of the balls are equal, their kinetic energies are equal, which means that the body is not released in the system. This is what should happen in an absolutely elastic impact of balls of the same mass. It is also obvious that if a heavier ball hits under the conditions, then it cannot remain (otherwise this would lead to a violation of the law of conservation of energy). Thus, the special case ($m_1 > m_2$) that causes our confusion in the analysis of the answer is simply impossible, since it contradicts the conditions of the problem, namely the leaving of the incoming ball immediately after the impact.

***

To summarize, we find that the examples discussed above have convinced the reader of the necessity and importance of analyzing the letter answer in physical problems. The following exercises are suggested as training. However, they should not be limited to just them. It is extremely important to develop the habit of not leaving an answer to a task without further analysis. This purpose can be served by various materials of the journal «Kvant», primarily [3] and [4].

Exercises

1. A third of the entire path is automated at a speed of $v_1$, then a quarter of the entire time at a speed of $v_2$, the rest at a speed of $v_3$. What was the average speed of the $v_{cp}$ automatic? Possible answers:
A. $v_{cp} = \frac{3v_1v_2v_3}{v_1v_2 + v_2v_3 + v_1v_3}$;
B. $v_{cp} = \frac{3v_1v_2v_3}{v_1 + v_2 + v_3}$;
C. $v_{cp} = \frac{3v_1(v_2 + 3v_3)}{2(4v_1 + v_3)}$;
D. $v_{cp} = \frac{3v_1(v_2 + 3v_3)}{4(2v_1 + v_3)}$.

2. A homogeneous cylinder of mass $m$ with a cross-sectional area $S$ floats on the boundary of immobile fluids with densities $\rho_1$ and $\rho_2$ (Fig. 6). Neglecting the resistance of the liquids, determine the period of small vertical oscillations of the cylinder. Possible answers:
A. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 + \rho_1\right)gS}}$;
B. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 - \rho_1\right)gS}}$;
C. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 \rho_1\right)gS}}$;

⟦folio 53⟧

---
running_head:
folio:
---

3. Two cars are approaching an intersection along mutually peredicular roads with constant speeds $v_1$ and $v_2$. At the moment of time when the first car reaches the intersection, the second one is at a distance of $l$ from it. Determine the minimum distance $d_{\min}$ between cars while they are moving. Possible answers:

A. $d_{\min} = l \frac{v_1^2 - v_2^2}{v_1^2}$;
B. $d_{\min} = l \frac{v_1^2 + v_2^2}{v_1}$;
C. $d_{\min} = l \frac{v_2}{\sqrt{v_1^2 + v_2^2}}$;
D. $d_{\min} = l \frac{v_1}{\sqrt{v_1^2 + v_2^2}}$.

4. In what time $t$ will a body of mass $m$ slide off an inclined plane of height $h$ with an angle of inclination $\beta$, if it moves down uniformly along an inclined plane with an angle of inclination $\alpha$? Possible answers:

A. $t = \sqrt{\frac{2h \cos \alpha \cos \beta}{g (\sin \alpha + \sin \beta)}}$;
B. $t = \sqrt{\frac{2gh}{\sin \beta \sin (\beta - \alpha)}}$;
C. $t = \sqrt{\frac{2h \cos \alpha}{g \sin \beta \sin (\beta - \alpha)}}$;
D. $t = \sqrt{\frac{2h \sin \alpha}{g (\cos \alpha + \sin \beta)}}$.

5. The heat-insulated cylinder is divided into two parts by a heat-insulating partition with a valve. With the valve closed, in one part of the cylinder with volume $V_1$ there is helium at pressure $p_1$ and temperature $T_1$, and in the other part of the cylinder with volume $V_2$ there is neon at pressure $p_2$ and temperature $T_2$. Find the temperature $T$ of the gas that will be established in the cylinder after opening the valve. Possible answers:

A. $T = \frac{T_1 T_2 (p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$;
B. $T = \frac{p_1 V_1 T_2 + p_2 V_2 T_1}{T_1 T_2 (p_1 V_1 + p_2 V_2)}$;
C. $T = \frac{T_1 T_2 (2 p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$;
D. $T = \frac{2 T_1 T_2 (p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$.

6. A current source with EMF $\varepsilon$ and internal resistance $r$ and three resistors with resistance $R_1, R_2$ and $R_3$ are connected according to the circuit shown in figure 7. Find the current flowing through resistor $R_1$. Possible answers:

A. $I_1 = \varepsilon R_1 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$;
B. $I_1 = \varepsilon R_2 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$;
C. $I_1 = \varepsilon R_2 / \left((R_3 + r)(R_1 + R_2) - R_1 R_2\right)$;
D. $I_1 = \varepsilon R_1 R_2 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$.

7. With what force does the wedge press on a vertical wall if a load of mass $m$ (Fig. 8) is placed on it? The angle at the base of the wedge is $\alpha$. The coefficient of friction between the load and the surface of the wedge is $\mu$, there is no friction between the floor and the wedge. Possible answers:

A. $F = mg \cos \alpha$;
B. $F = mg \cos \alpha (\sin \alpha + \mu \cos \alpha)$;
C. $F = mg \cos \alpha (\sin \alpha - \mu \cos \alpha)$;
D. $F = mg \cos \alpha (\mu \cos \alpha - \sin \alpha)$.

Let us warn the reader right away: none of these answers is correct. Try and add one of the proposed answers so that it becomes correct.

Literature

1. A. Pais. Scientific activities and life of Albert Einstein. - M.: Nauka, Main editorial office of physical and mathematical literature, 1989.
2. L. Tarasov. Symmetry in physics problems. - «Kvant», 1978, No. 6.
3. R. Mints. How to check the answer. - «Kvant», 1970, No. 12.
4. G. Meledin. Is it possible to check the answer? - «Kvant», 1979, No. 7.
