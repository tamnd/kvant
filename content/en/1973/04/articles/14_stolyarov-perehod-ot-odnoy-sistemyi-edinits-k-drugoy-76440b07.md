---
id: 1973-4-stolyarov-perehod-ot-odnoy-sistemyi-edinits-k-drugoy-76440b07
issue: kvant_1973_4
year: 1973
number: "4"
title: Transition from one system of units to another
authors:
  - Столяров И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 55
page_labels: 52-53
tag: 7PSP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 54094f27db47c6640c7bc8f2be242b055b5bd614bebb1aa066229c836ef87dd1
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/14_stolyarov-perehod-ot-odnoy-sistemyi-edinits-k-drugoy-76440b07.md
source_content_sha256: 69957247cc8c06f6da39e41ff151f3ea62cb421ea6967252d2260ac8479d2d34
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Transition from one system of units to another
I. A. Smolyarov

When solving problems in mechanics and molecular physics, the SI and CGS units are most often used, and when solving problems in electromagnetism, the SI system and the so-called Gaussian system of units, based on the mechanical units of the CGS system, are used. (For electrical units, the Gausscova system of units coincides with the SGSE system.)

In mechanics, the transition from one system of units to another is very simple. All equations of mechanics are written exactly the same in both systems of units. Therefore, as long as we do not substitute numerical values ​​of quantities into the formulas, there is no need to think about what system of units we will use when solving the problem. In order to express other quantities specified in one system of units in another system of units, you only need to know the correspondence between the basic units given in Table 1.

Table 1

| Basic units | in SI | in GHS | Relationship between SI and GHS units |
| :--- | :--- | :--- | :--- |
| Weight | $k_2$ (kilogramм) | $e$ (gram) | $1 \ k_2 = 10^3 \ e$ |
| Length | $m$ (meter) | $cm$ (centimeter) | $1 \ m = 10^2 \ cm$ |
| Time | $c$ (second) | $c$ (second) | |

Suppose the magnitude of the force is expressed in diah, but we need to express it in newtons. How to do this?

The connection between units and basic units (dimension of force) in the SI system and in the CGS system is the same: $\frac{ML}{T^2}$. Here $M$ stands for the unit of mass, $L$ for the unit of length and $T$ for the unit of time.

$$1 \ \partial h = 1 \ \frac{2 \ \text{cm}}{c^2}, \ a \ 1 \ h = 1 \ \frac{k_2 \ \text{m}}{c^2}.$$

Since $1 \ e = 10^{-3} \ k_2$ and $1 \ cm = 10^{-2} \ m$, then

$$1 \ \partial h = 1 \ \frac{10^{-3} \ k_2 \cdot 10^{-2} \ m}{c^2} = 10^{-5} \ h.$$

Another example. Let's find the connection between joyle and egro.

$$1 \ \partial jx = 1 \ \frac{k_2 \ m^2}{c^2}, \ a \ 1 \ эгром = 1 \ \frac{2 \ \text{cm}^2}{c^2}.$$

Since $1 \ k_2 = 10^3 \ e$ and $1 \ m = 10^2 \ cm$, then

$$1 \ \partial jx = 1 \ \frac{10^3 \ e \cdot (10^2 \ cm)^2}{c^2} = 10^7 \ эгром.$$

Neither the SI system nor the GHS system have special “thermal” quantities, except temperature, which in both systems is measured by the same unit. Therefore, the transition from one system of units to another in molecular physics is as simple as in mechanics. Sometimes, however, the amount of heat is calculated not in joyles or egres, but in external units - calories or

⟦folio 53⟧

kilocalorie:
$$1 \text{ кал} = 10^{-3} \text{ ккал} = 4.18 \text{ дж.}$$

When solving physical problems, no problem arises at all. They always use one system of units - SI. In it, the luminous intensity changes in candelas, illumination - in hatches, luminous flux - in lumens.

Much more difficult are transitions from one system to another in electromagnetic theory. The SI systems and the so-called Gaussian system of units, based on the mechanical units of the CGS system, are used here. For electrical quantities, it coincides with the SGSE system. In these systems, not only are the units of measurement of quantity different, but most of the formulas look different. These formulas include various numerical factors (see Table 2). For example, if you use the Gaussian system of units when solving a problem, then Coulomb’s law is written as follows:
$$F = \frac{q_1 q_2}{\varepsilon r^2},$$
and if you use the SI system, then like this:
$$F = \frac{1}{4 \pi \varepsilon_0} \frac{q_1 q_2}{\varepsilon r^2},$$
where $\varepsilon_0$ is the electrical constant. The writing of many other formulas is similarly different. Therefore, when solving a problem involving electricity or magnetism, it is necessary to determine from the very beginning in which system of units the problem will be solved. This is what different formulas look like in two systems of units:

| | SI | Gaussian |
| :--- | :--- | :--- |
| Coulomb's law | $F = \frac{q_1 q_2}{4 \pi \varepsilon_0 \varepsilon r^2}$ | $F = \frac{q_1 q_2}{\varepsilon r^2}$ |
| Intense fields of precise charge | $E = \frac{q}{4 \pi \varepsilon_0 \varepsilon r^2}$ | $E = \frac{q}{\varepsilon r^2}$ |
| Precise charge field potential | $\varphi = \frac{q}{4 \pi \varepsilon_0 \varepsilon r}$ (at $r \to \infty$ $\varphi \to 0$) | $\varphi = \frac{q}{\varepsilon r}$ |
| Capacitance of parallel plate capacitor | $C = \frac{q}{u} = \frac{\varepsilon_0 \varepsilon S}{d}$ | $C = \frac{q}{u} = \frac{\varepsilon S}{4 \pi d}$ |
| Lorentz force | $F = q v B \sin \alpha$ | $F = \frac{1}{c} q v B \sin \alpha$ |
| Force acting on a current-carrying conductor in a magnetic field | $F = I l B \sin \alpha$ | $F = \frac{1}{c} I l B \sin \alpha$ |
| Magnetic field induction at the center of a circular current | $B = \mu \mu_0 \frac{I}{2 r}$ | $B = \frac{1}{c} 2 \pi \mu \frac{I}{r}$ |
| Law of Electromagnetic Induction | $E_{\text{инд}} = - \frac{\Delta \Phi}{\Delta t}$ | $E_{\text{инд}} = - \frac{1}{c} \frac{\Delta \Phi}{\Delta t}$ |
| Magnetic field induction of an infinite rectilinear conductor with current | $B = \mu \mu_0 \frac{I}{2 \pi r}$ | $B = \frac{1}{c} 2 \mu \frac{I}{r}$ |
