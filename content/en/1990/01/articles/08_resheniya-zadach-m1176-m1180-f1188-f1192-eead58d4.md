---
id: 1990-1-resheniya-zadach-m1176-m1180-f1188-f1192-eead58d4
issue: kvant_1990_1
year: 1990
number: "1"
title: Solutions to problems M1176—M1180; F1188—F1192
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 48
page_labels: 40, 42, 43, 44, 45, 46
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3771df464920f56ae9e447162c5e8185526708bd7df9aab6222d0e23f2edf375
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/08_resheniya-zadach-m1176-m1180-f1188-f1192-eead58d4.md
source_content_sha256: f73d934cc7b8e981eb03629c6f98285b1758bc52673ebcc46fe0ad588e75d76a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Fig. 2.

Problem solutions
M1176 — M1180, F1188 — F1192

Let us denote by $PQ$ and $EF$ the midlines of the quadrilateral $ABCD$, as shown in figure 1; then its area $S$ is twice the area $PEQF$ (the total area of ​​the blue triangles is $S/2: S_{PAE} + S_{QCE} = S_{BAD}/4 + S_{BCD}/4 = S/4 = S_{PBF} + S_{QDE}$).

Thus,

$$S = 2S_{PEQF} = PQ \cdot EF \cdot \sin \alpha,$$

(1)

where $\alpha$ is the angle between lines $PQ$ and $EF$.
On the other side,

$$\frac{1}{4} (MN^2 - KL^2) = \frac{1}{4} (MN + KL) \cdot (MN - KL) = PQ \cdot \bar{v},$$

(2)

where $\bar{v} = (MK + LN)/2$, plane $MN + KL = (MP + PQ + QN) + (KP + PQ + QL) = 2PQ,$

(3)
$(KP = -MP, QL = -QN)$,

A
$$MN - KL = (MK + KN) - (KN + NL) = MK + LN.$$

Let us prove that the right-hand sides of formulas (1) and (2) are equal. Vectors $MK$ and $LN$ are obtained from $AB$ and $DC$, respectively, by rotating by $\pi/2$ in the same direction (by figure 2 - counterclockwise). Therefore, we get them $\bar{v}$ obtained by the same rotation from $(AB + DC)/2$. But we obtain the vectors connecting the ends of two segments equal to the vector connecting the midpoints of these segments - we have already proven this for the segments $MK$ and $NL$ (see (3)), i.e. $(AB + DC)/2 = EF$. So the vector $\bar{v}$ is equal to the vector $EF$ rotated by $\pi/2$. Therefore, the angle between the vectors $PQ$ and $\bar{v}$ is equal to $\pi/2 \pm \alpha$ (recall that $\alpha$ is the angle between the lines $PQ$ and $EF$). But according to the condition, the angle $KPQ$, that is, the angle between the vectors $PQ$ and $MK$, and the angle $PQL$ - between $PQ$ and $LN$ - are acute, therefore $PQ \cdot \bar{v} = (PQ \cdot MK + PQ \cdot LN)/2 > 0$, which means the angle between $PQ$ and $\bar{v}$ is acute and equal $\pi/2 - \alpha$. Now we get that $PQ \cdot \bar{v} = PQ \cdot |\bar{v}_1| \cdot \cos(\pi/2 - \alpha) = PQ \times EF \cdot \sin \alpha = S$, which is what was required.

Along the way, we propose to prove that the sum $(MN^2 + KL^2)$ is equal to the sum of the squares of the diagonals $AC^2 + BD^2$ of a given quadrilateral or twice the sum of the squares of the midlines $2(PQ^2 + EF^2)$.

N. Vasiliev, V. Dubrovsky

Let us use the well-known Bernulia inequality - $(1 + x)^\alpha \geq 1 + \alpha x$ for $\alpha > 1$, $x > -1$.

(To prove it, it is enough to note that the function

⟦folio 42⟧

---
running_head:
folio:
---

clutches it follows that to achieve equality it is necessary and sufficient that $\cos(\alpha - \beta) = 1$, that is, $\alpha = \beta$, and either $\cos \gamma = 0$, that is, $\gamma = 90^\circ$, or $\cos \alpha = \cos \beta = 1/2$, i.e. $\alpha = \beta = 60^\circ$.

E. Gotman

M1179. Find $a_{1000}$ if $a_1 = 0$ and for $n = 1, 2, 3, \dots$

a) $a_{n+1} = \frac{n}{n+1}(a_n+1)$;

b) $a_{n+1} = \frac{n(n+1)}{(n+2)(n+3)} \times (a_n+1)$;

c) $a_{n+1} = \frac{n(n+1)(n+2)}{(n+3)(n+4)(n+5)} \times (a_n+1)$.

Answer: a) 999/2, b) 999·2001/10010, c) 16650/167.

Let us prove by induction that the common terms of the sequences under consideration are expressed through the number $n$ by the following formulas:

a) $a_n = \frac{n-1}{2}$; b) $a_n = \frac{(n-1)(2n+1)}{10(n+1)}$; c) $a_n = \frac{n(n-1)}{10(n+2)}$.

For $n = 1$ all formulas give $a_n = 0$. Let us check that they are true for $a_{n+1}$, considering them true for $a_n$.

Case a): $a_{n+1} = \frac{n}{n+1}\left(\frac{n-1}{2} + 1\right) = \frac{n}{2} = \frac{(n+1)-1}{2}$.

Case b): $a_{n+1} = \frac{n(n+1)}{(n+2)(n+3)} \times \frac{2n^2 - n-1+10n+10}{10(n+1)} = \frac{n \cdot (n+3)(2n+3)}{10(n+2)(n+3)} = \frac{n(2n+3)}{10(n+2)}$.

Case c): $a_{n+1} = \frac{n(n+1)(n+2)}{(n+3)(n+4)(n+5)} \times \frac{n^2+9n+20}{10(n+2)} = \frac{n(n+1)}{10(n+3)}$.

It remains to substitute $n = 1000$ into the formulas for $a_n$.

V. Vergheim

M1180*. On one of the two data points $A$ and $B$ intersecting the sphere, on the other - $C$ and $D$. Segment AC passes through the common point of the sphere. The segment BD passes through another common point of the sphere and is parallel to the line containing the centers of the sphere. Prove that the projections of the segments $AB$ and $CD$ onto the line AC are equal.

Let $E$ and $F$ be common points of the sphere lying on $AC$ and $BD$, respectively, $O_1$ and $O_2$ the centers of the sphere, $G$ a point symmetrical to $F$ with respect to the straight line $O_1O_2$. Obviously, $G$ is also a common point of the sphere, and $BG$ and $DG$ are the diameters of the sphere (Fig. 1).

We will denote by $X'$ the projection of an arbitrary point $X$ onto $AC$. Then it is clear that $O'_1$ is the midpoint of the chord $AE$ of the sphere $O_1$, and $O'_2$ is the midpoint of the chord $EC$ of the sphere $O_2$. At the same time, $O'_1$ is the midpoint of the segment $B'G'$, since $O_1$ is the midpoint of $BG$, and $O'_2$ is the midpoint of the segment $G'D'$. From-

⟦folio 43⟧

---
running_head:
folio:
---

it follows here (see Fig. 2) that $AB' = G'E$, and $G'E = D'C$, that is, $AB' = D'C$.

I. Sharytsin

F1188. Between the bilingual heads and spiny walls there is a wheel pair (see figure) - two heavy disks weighing $M$, mounted rigidly on a light axle with a diameter of $L$ ($L \approx R_2 - R_1$). By applying a horizontally directed force to the axle, we force the wheelset to move in a circle without distortions (so that the axle is always directed along the radius). What is the minimum amount of work that needs to be done to move the weight around? Coefficient of wheel friction on the ground $k$; The wheels are considered narrow.

It is clear that in a given situation it is impossible to ensure that both wheels move without slipping. Therefore, the required work is equal to the work of the friction forces, taken with a minus sign.

When the wheelset moves slowly, the power of the friction force for each wheel is equal to $-F_{\text{тр}} |v_H| = -kMg |v - \omega r|$, where $v_H$ is the speed of the bottom point of the wheel relative to the ground, $r$ is the radius of the wheel, $v$ is the speed of the center of the wheel, $\omega$ is the angular speed of rotation of the wheel around its axis. The power of the friction forces acting on both wheels is equal to $-kMg(|v_1 - \omega r| + |v_2 - \omega r|)$, where $v_1$ and $v_2$ are the speeds of the centers of the first and second wheels. For fixed $v_1$ and $v_2$, the values ​​in brackets are minimal at $v_1 \leq \omega r \leq v_2$, which corresponds to the case when the wheels slip in opposite directions. In this case, the total power of the friction forces is

$$P_{\text{тр}} = -kMg(v_2 - v_1),$$

and the work of friction forces when passing a full circle is

$$A_{\text{тр}} = -kMg \cdot 2\pi(R_2 - R_1).$$

Hence the job you are looking for -

$$A = -A_{\text{тр}} = kMg \cdot 2\pi(R_2 - R_1) = 2\pi kMgL.$$

M. Tsypin

F1189. The large room is kept at a constant temperature $T_k = +15^\circ\text{C}$ in winter by three central heating radiators connected in series, through which hot water is pumped. In this case, the temperature of the first radiator is $T_1 = +75^\circ\text{C}$, and the last (third) is $T_3 = +30^\circ\text{C}$. What is the temperature of the second radiator? Consider that the heat is between the radiator and the room, so let’s designate the temperature of the water at the inlet and outlet of the radiators as shown in figure. The temperature of the water at the inlet of each radiator uniquely determines the temperature of the radiator itself and the temperature of the water at its outlet. The equilibrium condition is the equality of heat flows “water - radiator” and “radiator - room”.

We will count all temperatures from room temperature, i.e. from $T_k$. Let's assume that we changed all temperatures by a factor. Then both heat flows for each radiator change by the same amount, and the equilibrium will not be disturbed. This means that all three radiators have the same ratio of inlet temperature to radiator temperature:

$$\frac{t_1 - T_k}{T_1 - T_k} = \frac{t_2 - T_k}{T_2 - T_k} = \frac{t_3 - T_k}{T_3 - T_k},$$

⟦folio 44⟧

---
running_head:
folio:
---

and between hot water and radiator - proportional to the corresponding temperature difference.

F1190. Connect two identical capacitors in series to a battery with internal resistance $r=1$ Ohm. A resistor with a resistance of $R=1000$ Ohm is connected in parallel to one of them, and a certain amount of heat is released in the circuit. How much of this heat is generated at the battery's internal resistance?

So, through resistor $R$, it is the sum of the discharge current of the “lower” capacitor and the charging current of the “upper” capacitor (see figure). This means that the current flowing through resistor $r$ is at any moment less than the current flowing through resistor $R$. The maximum voltage across the large resistor does not exceed the voltage of the battery $U$, and the voltage across the small resistor depends less than 0.001 $U$, so we will neglect it and assume that the sum of the voltage across the capacitor is exactly equal to the voltage of the battery $U$.

Then the solution to the problem becomes quite simple: when an external resistor is connected, the voltage changes on the capacitors are the same in absolute value, only for the “lower” capacitor this change is negative, and for the “upper” capacitor it is positive. Capacitors have the same capacitances (we leave it to you to figure out the case of different capacitances yourself), therefore, the changes in the charges of the capacitors are also the same in absolute value. This means that at any given time the current through resistor $R$ is exactly twice the current through resistor $r$, and the ratio of the corresponding thermal powers is 4000:1.

So, approximately 1/4000 of the total amount of heat will be released at the internal resistance of the battery (at resistor $r$).

F1191. A thin-walled conducting sphere with radius $R$ is connected to the source by thin wires (Fig. 1), connected at points $A$ and $B$ (AO $\perp$ОВ, О is the center of the sphere). So through the source it is equal to $I_0$. In what direction are they moving?

First, let's consider a very simple connection of the sphere to the source - poles (Fig. 2). It is clear that the equivalent between marks located at a small distance $\Delta l$ from each other will be exactly the current

$$i = \frac{I_0}{2\pi R} \Delta l.$$

Now let's connect two sources (Fig. 3) to the sphere - one between the poles, and the other between the opposite ones.

⟦folio 45⟧

---
running_head:
folio:
---

What are the charges at point C(OS ⊥ OA, OC ⊥ OB)? Let's make two marks on the sphere near point C, so that the distance between them is R/1000, and the segment connecting them turns out to be perpendicular to the direction of the charges. What fraction of the total current flows through the sphere between these marks?

The positive points of the equator. Then the current at point C will be equal to the geometric sum of two mutually perpendicular currents. But this current is twice as large as the desired one.

Finally, we obtain that a current flows between given marks on the sphere

$$I = \frac{1}{2} \sqrt{2} \frac{I_0}{2\pi R} \frac{R}{1000} = \frac{\sqrt{2}}{4000\pi} I_0 \sim 0,0001I_0$$

in a direction at an angle of 45° to the equator.

L. Markovich

F1192. At the end of the cylindrical solenoid there is a thin sheet of cardboard, on it there is a small superconducting ring made of thin wire, the diameter of which $d_1$ is significantly smaller than the diameter of the ring D. When the solenode is connected to the source in series with the capacitor (see figure), the ring breaks down at $U > U_0$. What should be the direction of the source in a similar experiment with a ring of the same diameter, but made of wire $d_2$ thick? The inductance of such a loop, sufficient for practice, can be accurately estimated using the formula $L = kD \ln(1,4D/d)$. The solenoid resistance should be considered low.

Neglecting the active resistance of the solenoid, we write Ohm’s law for a closed solenoid circuit:

$$U - L_c \frac{\Delta I_c}{\Delta t} = \frac{q}{C},$$

where $L_c$ is the inductance of the solenode, $I_c$ is the current through the solenode, $q$ is the charge on the capacitor. Using the expression $I_c = \Delta q/\Delta t$, we obtain the equation

$$\frac{d^2 q}{dt^2} + \frac{q}{L_c C} = \frac{U}{L_c}.$$

Let us introduce the following notations: $1/(L_c C) = \omega_0^2$, $q - UC = q^*$. Then the equation describing the dependence of the charge $q^*$ on time will have the form

$$\frac{d^2 q^*}{dt^2} + \omega_0^2 q^* = 0.$$

This equation describes the harmonic oscillation of the charge $q^*$, which, up to the constant UC, is equal to the charge on the capacitor. We look for a solution to this equation in the form

$$q^*(t) = A \sin \omega_0 t + B \cos \omega_0 t,$$

where A and B are constants that are determined from the initial conditions. At the moment of closing the solenoid circuit ring

$$q^*(0) = q(0) - UC = -UC,$$

$$\frac{\Delta q^*}{\Delta t} = \frac{\Delta q}{\Delta t} = 0,$$

⟦folio 46⟧

---
running_head:
folio:
---

where is it from?
$$A = 0, B = -UC.$$
Hence,
$$q^*(t) = -UC \cos \omega_0 t, \quad q(t) = UC(1 - \cos \omega_0 t).$$
In the future we will be interested in the solenoid current:
$$I_c(t) = \frac{\Delta q(t)}{\Delta t} = UC \omega_0 \sin \omega_0 t.$$
Let us now write Ohm's law for a superconducting bulb:
$$-\frac{\Delta \Phi}{\Delta t} - L_k \frac{\Delta I_k}{\Delta t} = 0,$$
where $\Phi$ is the external flux of the magnetic induction vector, an arbitrary bulb, $I_k$ is the current in the bulb, and $L_k$ is the inductance of the bulb. The solution to this equation has the form
$$\Phi + L_k I_k = \text{const},$$
but at the initial moment of time this constant is equal to zero, therefore
$$I_k = -\frac{\Phi}{L_k}.$$
The flux $\Phi$ is proportional to the induction of the solenide, which, in turn, is proportional to $I_c$ and the area of ​​the bulb:
$$\Phi \sim I_c D^2 \sim UD^2.$$
Taking this relation into account, we obtain
$$I_k \sim \frac{D^2 U}{L_k}.$$
The maximum Ampere force $F$ acting in the vertical direction on the bulb, proportional to the length of the bulb, the current in the bulb and the current in the solenide:
$$F \sim DI_k I_c \sim \frac{D^3 U^2}{L_k}.$$
The ring will bounce if the force $F$ is greater than the gravity force of the flask, proportional to $Dd^2$. In the limiting case
$$\frac{D^3 U^2}{L_k} \sim Dd^2 \rightarrow U \sim \frac{L_k^{1/2} d}{D}.$$
For the first case
$$U_0 \sim (\ln(1,4D/d_1))^{1/2} d_1,$$
for the second -
$$U'_0 \sim (\ln(1,4D/d_2))^{1/2} d_2.$$
Hence,
$$U'_0 = U_0 \left( \frac{\ln(1,4D/d_2)}{\ln(1,4D/d_1)} \right)^{1/2} \frac{d_2}{d_1}.$$
The voltage at the source must be greater than $U'_0$.
V. Mozhaev
