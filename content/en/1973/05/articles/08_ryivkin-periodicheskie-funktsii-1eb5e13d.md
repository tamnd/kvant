---
id: 1973-5-ryivkin-periodicheskie-funktsii-1eb5e13d
issue: kvant_1973_5
year: 1973
number: "5"
title: Periodic functions
authors:
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 41
page_labels: 38-39
tag: 2AAY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 201fe5fdc2d254121a8e1acdc90030f5a4e744be40b5c484ad69b65a06d43e91
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/08_ryivkin-periodicheskie-funktsii-1eb5e13d.md
source_content_sha256: adf87a46f9e8b5062c38c196cc97f30b1b911651c28a4cf80153e0ffca2b3285
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Periodic functions

Definitions

You all apparently know what a periodic function is. However, in order to study its properties, it is still necessary to give its strict definition. It turns out that this is not so easy to do. Here, for example, is one definition and a “consequence” from it.

Definition. A function $y = f(x)$ is called periodic if there is a number $T \neq 0$ such that for all values ​​of $x$ from the domain of this function $f(x+T) = f(x)$.

Let us now prove Lemma 1:

If $T > 0$ is the period of the function $f(x)$, then $-T$ can be the period of this function.

The proof consists of writing out a chain of equalities:

$$f(x-T) = f[(x-T)+T] = f(x).$$

In fact, $T$ is the period of the function $f(x)$, and therefore, if it is added to the argument $x-T$, then the value of the function will not change (the first equality). All that remains is to open the brackets and get $f(x)$.

Before reading further, try to find the error in this proof.

All the reasoning carried out here is correct. Only they do not imply that $-T$ is the period of $f(x)$. If you haven't yet discovered the error in the proof, consider the function $\sin(\sqrt{x+2\pi})^2$. Its domain is $x \geq 0$, and for any $x$ from this domain

$$\sin(\sqrt{x+2\pi})^2 = \sin(\sqrt{x})^2,$$

that is, $2\pi$ from the point of view of the formulated definition is the period

functions. At the same time, $-2\pi$ will not be its period, since the left $x = 0$ function $\sin(\sqrt{x})^2$ is not defined and, for example, $\sin(\sqrt{0-2\pi})^2$ does not exist.

Now the error of the proof is also clear: before considering the value $f(x-T)$, you need to be sure that this value exists, and this is not the case. This is why it is possible to construct a refuting example.

In order for Lemma 1 to be proven, a different definition of a periodic function is necessary.

Definition 1. A function $f(x)$ defining at least one point is called periodic if there is a number $T \neq 0$ (called period) such that for any $x$ from the domain of definition of this function

a) the numbers $x-T$ and $x+T$ also belong to its domain of definition:

b) $f(x+T) = f(x)$.

With this definition, the above proof of Lemma 1 becomes true.

Using the definition of a periodic function, you can determine whether a particular function is periodic.

Example 1. Prove that the function $y = \sin lg x$ is not periodic.

It is easy to establish this fact - it is enough to note that this function is defined for all $x > 0$ and does not exist for all $x \leq 0$. Therefore, whatever $T > 0$ we choose, our function will be defined at $x = T/2$ and will not

⟦folio 39⟧

is defined at $x = \frac{T}{2} - T = -\frac{T}{2}$, that is, it is not periodic.

Example 2. Prove that the function
$$\cos x + \sin (x \sqrt{2})$$
- not periodic.

Let there be a number $T \neq 0$ such that
$$\cos (x + T) + \sin [\sqrt{2} (x + T)] \equiv \cos x + \sin (\sqrt{2} x)$$
for everyone $x$. Let us put $x = 0$ and $x = -T$ in this identity; then we get the following two equalities:
$$\begin{cases} \cos T + \sin (\sqrt{2} T) = 1 & (1) \\ \cos T - \sin (\sqrt{2} T) = 1. & (2) \end{cases}$$
From the correspondence of (1) and (2) it follows that $\cos T = 1$, and $\sin (\sqrt{2} T) = 0$, whence $T = 2\pi k$ and $T = \pi n/\sqrt{2}$. Equating these values ​​($T \neq 0$, and therefore $k \neq 0$, $n \neq 0$), we find $\sqrt{2} = n/2k$, that is, $\sqrt{2} - \text{рациональное число}.$. The resulting contradiction proves that the function $\cos x + \sin (\sqrt{2} x)$ is not periodic.

Example 3. Prove that the function $y = 3\sin x + \sin 2x$ is periodic.

Obviously they reason like this. Let $T$ be the period of this function. Then equality
$$3\sin (x + T) + \sin 2 (x + T) = 3\sin x + \sin 2x$$
must satisfy for all $x$, including $x = 0$. Using this, we arrive at an equation for $T$:
$$3\sin T + \sin 2T = 0,$$
(that is, $(3 + 2\cos T) \sin T = 0$. Since the expression in brackets does not go to zero, $\sin T = 0$, $T = k\pi$.
However, the values ​​$T$ found in this way are not at all intended to be periods of functions. By moving from correspondence (1) to correspondence (2), we relaxed the restrictions on $T$ contained in (1). After all, the first correspondence must be valid for all $x$, while the second ensures its validity only for $x = 0$. Thus, we have established that all periods of the function under consideration are contained among numbers of the form $x = k\pi$. However, this does not mean at all that all numbers of this type are its periods.

Next, because
$$3\sin \frac{\pi}{2} + \sin \left(2 \cdot \frac{\pi}{2}\right) = 3,$$
$$3\sin \left(\frac{\pi}{2} + \pi\right) + \sin 2 \left(\frac{\pi}{2} + \pi\right) = -3,$$
that is, $f\left(\frac{\pi}{2}\right) \neq f\left(\frac{\pi}{2} + \pi\right)$, then n will not be a period of the function. The number $2\pi$ and all numbers of the form $2k\pi$ are its periods, which is easy to verify by direct verification.

Main period

Definition 2. The smallest positive period of a periodic function $f(x)$ is called the fundamental one.

Some of the more attentive readers will probably immediately object: before giving something a name, it would be good to make sure of the existence of a certain object. We will investigate the existence of the main period after we have also proved the Snow property of periodic functions.

Lemma 2. If $T_1$ and $T_2$ are periods of the function $f(x)$, and $T_1 + T_2 \neq 0$, then $T_1 + T_2$ is the period of $f(x)$.

Proof. Let $y = x + T_1$. Since $T_1$ is the period of the function $f$, mo $f(y)$ exists simultaneously with $f(x)$. $T_2$ is also the period $f$. Therefore, $f(y + T_2)$ also exists $f(y + T_2) = f(y) = f(x + T_1) = f(x)$, that is, $f(x + T_1 + T_2) = f(x)$.

According to the conditions, $T_1 + T_2 \neq 0$. So
