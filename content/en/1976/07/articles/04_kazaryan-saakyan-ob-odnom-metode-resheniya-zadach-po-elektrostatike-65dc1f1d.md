---
id: 1976-7-kazaryan-saakyan-ob-odnom-metode-resheniya-zadach-po-elektrostatike-65dc1f1d
issue: kvant_1976_7
year: 1976
number: "7"
title: About one method for solving problems in electrostatics
authors:
  - Казарян Э.
  - Саакян Р.
rubric: osnovnye-stati
page_first: 11
page_last: 15
page_labels: 9-13
tag: TUM2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8c4528ce4e3ddc04994a909a92837ad6ad064794882d99e0fe48662ca4b01ca4
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/04_kazaryan-saakyan-ob-odnom-metode-resheniya-zadach-po-elektrostatike-65dc1f1d.md
source_content_sha256: 71fcfba5ac6235dfdb298d44eaac82b6b97df84d7f7a056fb30e5a472be7a0f0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

When studying the constant (not changing with time) electric fields created by charged conductors, first of all it should be borne in mind that the direction of the electrical field inside the conductors is zero. It immediately follows that charges in conductors are distributed over their surface. Thus, the problems of electrical engineering are usually related to finding the electric field outside conductors and determining the distribution of charges on the surface of conductors.

Let's formulate several typical electrical grid problems.

Task 1. The exact charge q is located at a distance d from the surface of a substituted spherical conductor of radius r (Fig. 1). Determine the charge q' induced on this surface.

Task 2. A powerful charge q (Fig. 2) is placed between two substituted concentric spheres with calculated surfaces whose radii are r₁ and r₂. The distances from the charge to the spherical surfaces are equal to the corresponding d₁ and d₂. The charges induced on the spheres are q'₁ and q'₂.

Task 3. The exact charge q is located at a distance d₁ and d₂ from the conducting substituted infinite planes (Fig. 3). Namely the charges q'₁ and q'₂ induced on these planes.

Observe methods for solving such problems are studied in the corresponding section of mathematical physics, which is not included in the school curriculum. However, there are a number of relatively simple private methods that allow you to solve problems in electrical grids without going beyond the limits of elemental mathematics (for example, the image method, which was mentioned in G. Myakishev’s article “Electrical grid field”; see «Kvant», 1975, No. 4). Here we will look at one of

⟦folio 10⟧

such methods, based on the theorem (or principle) of reciprocity.

What is the essence of this theorem? It can be formulated as follows: if in a system of $n$ conductors, non-existent conductors $q_1, q_2, \dots, q_n$, there are charges $\varphi_1, \varphi_2, \dots, \varphi_n$, corresponding, and with charges $q'_1, q'_2, \dots, q'_n$ the conductors are equal to $\varphi'_1, \varphi'_2, \dots, \varphi'_n$, then the equality is true

$$\sum_{i=1}^{n} q_i \varphi'_i = \sum_{i=1}^{n} q'_i \varphi_i.$$ (1)

Let us show that this is indeed the case.

According to the principle of superposition, the potential of conductors is linearly dependent on charges. Or, conversely, charges on a conductor depend linearly on potentials. Let us first consider a special case—inside a grounded conducting surface there are two charged conductors 1 and 2 (Fig. 4). Let's connect the second conductor to a grounded conductor, then the potential of this conductor will go to zero (see Fig. 4, a). The potential of the first conductor is denoted by $\varphi_1$. The charges on each of the conductors must be proportional to $\varphi_1$, i.e.

$$\Delta q_1 = C_{11} \varphi_1 \quad \text{и} \quad \Delta q_2 = C_{21} \varphi_1.$$ (2)

Here $\Delta q_1$ and $\Delta q_2$ are the charges on the first and second conductor, respectively, and $C_{11}$ and $C_{21}$ are constant quantities called capacitance coefficients and depending on the shape and relative position of the conductors. $C_{11}$ and $C_{21}$ characterize the charges of the first

$$q_i = C_{i1} \varphi_1 + C_{i2} \varphi_2 + \dots + C_{in} \varphi_n = \sum_{k=1}^{n} C_{ik} \varphi_k \quad (i=1, 2, \dots, n).$$ (3)

Here, the capacitance coefficient $C_{ik}$ characterizes the charge of the $i$-th conductor, when all conductors except the $k$-th

⟦folio 11⟧

Fig. 5.

are grounded, and the potential of the $k$-th conductor is equal to unity. Let now the charge of the $i$-th conductor be equal to $q'_i$, and its potential $\varphi'_i$. Let us multiply equality (4) term by $\varphi'_i$:

$$q'_i \varphi'_i = \sum_{k=1}^{n} C_{ik} \varphi_k \varphi'_i,$$

and then sum both sides of the resulting equality over all values ​​of $i$ from 1 to $n$:

$$\sum_{i=1}^{n} q'_i \varphi'_i = \sum_{i,k=1}^{n} C_{ik} \varphi_k \varphi'_i.$$

But

$$\sum_{i,k=1}^{n} C_{ik} \varphi_k \varphi'_i = \sum_{i,k=1}^{n} C_{ik} \varphi'_i \varphi_k = \sum_{i=1}^{n} q'_i \varphi'_i$$

(since $i$ and $k$ take all values ​​from 1 to $n$), so we finally get

$$\sum_{i=1}^{n} q'_i \varphi'_i = \sum_{i=1}^{n} q'_i \varphi'_i.$$

Thus, the reciprocity theorem is proven, since equalities (1) and (5) are identical.

Before applying the reciprocity theorem to solve the problems formulated above, we consider two additional problems.

Additional problem 1. There is a system of conductors, all of which, except for the $i$-th, are grounded, and the $i$-th conductor has a potential of $\varphi'_i$ (Fig. 5). At some points $A$ of the system the powerusal is equal to $\varphi$. Determine the charge $q'_i$ induced

$$q \varphi + q'_i \varphi'_i = 0,$$

where

$$q'_i = -q \frac{\varphi}{\varphi'_i}.$$

Additional problem 2. In a closed conducting surface 1, we place the chest of drawers $\varphi_1$, we find conductor 2 (Fig. 6). We place this equal to $\varphi_2$, and we place the point $A$, located between the conductors, equal to $\varphi$. Find charges $q'_1$ and $q'_2$ induced on the conductors if the conductors are grounded, and place charge $q$ at point $A$.

⟦folio 12⟧

We have two states of the system:
a) the charge at point $A$ is zero, its potential is $q$, and the potential of the conductors is $\varphi_1$ and $\varphi_2$ (see Fig. 6, a);
b) the charge at point $A$ is equal to $q$, the potential of the conductors is zero, and the charges induced on them are equal to $q'_1$ and $q'_2$ (see Fig. 6, b).

For simplicity, here and further we will talk about charge and potential power $A$, implying that there is a conductor at this point (as was done in problem 1).

By the reciprocity theorem
$$q'_1 \varphi_1 + q'_2 \varphi_2 + q \varphi = 0. \tag{6}$$

From this equality alone it is, of course, impossible to find both induced charges. However, we can also use the condition that the conducting conductivity $1$ is replaced in the second case. This means that there is no electric field outside, which means that the algebraic sum of all charges located inside the substituted conductivity is equal to zero, i.e.
$$q'_1 + q'_2 + q = 0. \tag{7}$$

Solving equations (6) and (7) together, we obtain
$$q'_1 = q \frac{\varphi_2 - \varphi}{\varphi_1 - \varphi_2}$$
And
$$q_2 = -q \frac{\varphi_1 - \varphi}{\varphi_1 - \varphi_2}.$$

Now we can return to the main tasks. To solve them we will use the reciprocity theorem. The method based on the application of this theorem is somewhat formal, but very simple and convenient. The whole difficulty lies only in wisely selecting the two states of the system under consideration and writing equality (1) for them.

Solution of problem 1. According to the conditions of the problem, the exact charge $q$ is located at a certain distance from the replaced conducting sphere on which the charge $q'$ is located (correspondence 1).

Let us assume that the spherical surface is not replaced and has potential $\varphi_0$, but charge $q$ does not. Then in its place the field potential is equal to
$$\varphi = \varphi_0 \frac{r}{r + d} (r - \text{радис сферической поверхности}, d - \text{расстояние от заряда } q \text{ до этой поверхности}).$$ This is the second state of the system.

Let us write the reciprocity theorem for these two states of the system:
$$q \varphi + q' \varphi_0 = 0,$$
or
$$q' = -q \frac{\varphi}{\varphi_0} = -q \frac{r}{r + d}.$$

The obtained result can be applied to the case when the charge $q'$ is on an infinite conducting plane. Indeed, an infinite plane can be considered as a spherical surface with an infinitely large radius, i.e.
$$r \rightarrow \infty.$$ Therefore, in the limit at $r \rightarrow \infty$ we have
$$q' = -q \frac{r}{r + d} = -q \frac{1}{1 + d/r} = -q,$$
that is, the charge induced on an infinite plane is equal in value, but opposite in value from point to point, wherever this charge is located.

Solution to problem 2. According to the conditions of the problem, the first state of the system is as follows: the charge $q$ is located at a given point between the substituted spherical conductors on which the charge $q'_1$ and $q'_2$ are located.

As a second state, let us consider the case when the outer sphere is replaced, the inner sphere has a potential $\varphi_1$, the charge $q$ is absent, but in its place the field potential is $q$.

Based on the solution to additional problem 1, we obtain
$$q'_1 = -q \frac{\varphi}{\varphi_1}. \tag{8}$$

⟦folio 13⟧

Fig. 7.

We find the charge $q'_2$ induced on the outer sphere from the condition that the algebraic sum of the charges located inside the grounded surface is equal to zero:

$$q'_1 + q'_2 + q = 0.$$ (9)

Thus, we only have to find the relation $\varphi/\varphi_1$. Suppose that when the outer sphere is grounded and the inner sphere has potential $\varphi_1$, the charge on the inner sphere is $q_0$. It is obvious that in this case a charge $-q_0$ will be induced on the outer sphere. Let us express the potentials $\varphi$ and $\varphi_1$ in terms of charges $q_0$ and $-q_0$:

$$\varphi = \frac{q_0}{r_1 + d_1} + \frac{-q_0}{r_2},$$

$$\varphi_1 = \frac{q_0}{r_1} + \frac{-q_0}{r_2}.$$ (10)

Then finally from equalities (8) – (10) we obtain:

$$q'_1 = -q \frac{r_1 d_2}{(r_1 + d_1)(d_1 + d_2)},$$

$$q'_2 = -q \frac{r_2 d_1}{(r_1 + d_1)(d_1 + d_2)}.$$

The solution to problem 3. It follows directly from the solution to problem 2, since two parallel infinite planes can be

Fig. 8.

consider them as two concentric spheres with infinitely large radii.

Let us write the result of solving problem 2 in the form:

$$q'_1 = -q \frac{r_1 d_2}{(r_1 + d_1)(d_1 + d_2)} = -q \frac{d_2}{(1 + d_1/r_1)(d_1 + d_2)},$$

$$q'_2 = -q \frac{r_2 d_1}{(r_1 + d_1)(d_1 + d_2)} = -q \frac{d_1}{(1 - d_2/r_2)(d_1 + d_2)}.$$

If $r_1 \to \infty$ and $r_2 \to \infty$, then

$$q'_1 = -q \frac{d_2}{d_1 + d_2},$$

$$q'_2 = -q \frac{d_1}{d_1 + d_2}.$$

Exercises

1. The center of the non-existent ball $q$ is located at a distance $a$ from the center of the grounded spherical conductor of radius $r$ (Fig. 7). Determine the charge $q'$ induced on the grounded ball.

2. Of two concentric spherical conductors, the radii of which are $r_1$ and $r_2$ ($r_1 < r_2$), the inner one is grounded, and the outer one has a charge $q$ (Fig. 8). Find the charge $q'$ induced on the inner sphere.
