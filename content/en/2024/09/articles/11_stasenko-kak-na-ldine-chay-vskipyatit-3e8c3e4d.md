---
id: 2024-9-stasenko-kak-na-ldine-chay-vskipyatit-3e8c3e4d
issue: kvant_2024_9
year: 2024
number: "9"
title: How to boil tea on an ice floe
authors:
  - Стасенко А. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 45
page_last: 46
page_labels: "44"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0c986996b4119a8fc6c9e857f3a3cc4eca5bca54b9d3c3fd0f939b2588cc64d7
prompt_sha256: draft-1
translated_from: content/ru/2024/09/articles/11_stasenko-kak-na-ldine-chay-vskipyatit-3e8c3e4d.md
source_content_sha256: 26f4305a7c49bdda9bfc2582d07067b284e893b76a4c0050538d038293f43d7a
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Like on an ice floe
boil the tea
A. STASENKO

There are so many powers in physics: the speed of a falling body is directly proportional to time, the distance traveled is the square of time, the volume of the ball is the cube of the radius, ..., and the flow of emitted energy, it turns out, is proportional to the fourth power of temperature! Yes, anyone can be convinced of this if they know such fundamental constants as Boltzmann’s constant $k$ (Ludwig Boltzmann, 1844–1906), Planck’s constant $h$ (Max Planck, 1858–1947), the speed of light $c$. Messages from the theory of dimensions and similarity will help here.

So, you need to obtain the dependence of the energy flux density $q$, its dimension $\frac{J}{\left(m^2 \cdot c\right)}$, on the temperature $T$, expressed in degrees Kelvin, K. It is immediately clear that the corresponding formula must contain $kT$, J, in some powers $m$, and to obtain J to the first power, this value should be divided by $h^{m-1}$, J·s. And opening the ligature $m^2$ in the denominator? Of course, divide by the square of the speed of light $c^2$, $m^2/c^2$. It turns out $q \sim \frac{(kT)^m}{c^2 h^{m-1}}$.

No since seconds should appear in the denominator, then there should be
$$\frac{1}{c^2} \cdot c^{m-1} = c^{m-3} = c$$,
whence $m = 4$. As a result we have
$$q \sim \frac{(kT)^4}{c^2 h^3} \sim T^4$$.

This is the famous Stefan-Boltzmann law (Josef Stefan, 1835–1893). The complex of fundamental constants, standing as a factor at $T^4$ and called the Stefan–Boltzmann constant, has the form
$$\sigma = \frac{2\pi^5}{15} \cdot \frac{k^4}{c^2 h^3} \approx 40 \cdot \frac{(1,4 \cdot 10^{-23})^4 \cdot Jx^4/K^4}{(3 \cdot 10^8)^2 m^2/c^2 \cdot (6,63 \cdot 10^{-34})^3 Jx^3 \cdot c^3} = 5,67 \cdot 10^{-8} \cdot Jx/\left(m^2 \cdot c \cdot K^4\right)$$.

DOI: https://doi.org/10.4213/kvant20240904

(Notice how well the numbers are lined up: 5, 6, 7, 8.) The resulting law describes the radiation of the so-called absolute black body. As a result, a blackness coefficient is introduced that is less than one.

For many purposes, only the fourth power of the temperature of the radiated body is important. For example, it is possible to estimate the temperature of the "surface" of the Sun, without sending a thermometer to it, based on the energy balance.

The entire energy emitted by the Sun is equal to $\sigma T_C^4 \cdot 4\pi R_C^2$, where $R_C$ is the radius of the Sun. Its part intercepted by the Earth's disk is equal to $\frac{\pi R_3^2}{4\pi L^2}$, here $L$ is the distance between the Sun and the Earth. The total energy emitted by the Earth is $\sigma T_3^4 \cdot 4\pi R_3^2$. Equating the energy flows incident on the Earth's disk and emitted by its surface, we obtain

$$\sigma T_C^4 \cdot 4\pi R_C^2 \cdot \frac{\pi R_3^2}{4\pi L^2} = \sigma T_3^4 \cdot 4\pi R_3^2.$$

It can be seen that both sides of this equation can be reduced by $\sigma \cdot 4\pi R_3^2$. This means that only the fourth degree of temperature is important. In addition, the resulting isisability is the same for all planets. Attitude plays a major role

$$\frac{R_C^2}{4L^2} = \frac{(2R_C)^2}{16L^2} = \left(\frac{\alpha_C}{16}\right)^2$$,

where $\alpha_C$ is the angular size of the diameter of the Sun when observed from Earth, equal to approximately $10^{-2}$ radians. As a result we have

$$\sqrt{\alpha_C} / 2 \cdot T_C = T_3, T_C = 20T_3.$$

Taking the average temperature of the Earth to be 300 K, we get $T_C = 6000$ K.

Note that the angular size of the diameter of the Moon is the same as for the Sun. This allows us to observe both the total eclipse of our star and its corona.

Doesn't allow it! - the fisherman exclaims, supporting his fishing rod over the ice hole, - if every body radiates energy, then it is possible, using a reflective surface of sufficient area $S$ night, to focus the radiation of ice on a kettle and boil it!? Let's check it out.

The solar radiation flux density at the Earth's surface is $q_C \approx 1000$ J/$\left(m^2 \cdot c\right)$. By focusing the radiation on the teapot,

⟦folio 44⟧

---
running_head:
folio:
---

affected by a screen with an area of ​​about a square meter, we have a kilowatt stove! Therefore, to obtain the same flux from an ice floe at a temperature of, say, −3 °C (270 K), a reflective surface area of ​​$S = \left(\frac{6000}{270}\right)^4 \cdot 1\text{m}^2 \approx 25 \cdot 10^4\text{ m}^2$ would be required. Hence the reflector radius $R = \sqrt{\frac{S}{\pi}} \approx 300\text{ m}$.

Of course, the response of a body by convection from a heated body increases when its temperature differs from the ambient temperature. This could be compensated for by adding reflector area. However, at what height is the teapot and the focus of such a device (a parabola or a spherical mirror)! - thought the fisherman, but then kleev went.

Happy catching!
