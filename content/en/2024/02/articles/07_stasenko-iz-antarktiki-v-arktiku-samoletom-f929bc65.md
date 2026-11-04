---
id: 2024-2-stasenko-iz-antarktiki-v-arktiku-samoletom-f929bc65
issue: kvant_2024_2
year: 2024
number: "2"
title: From Antarctica to the Arctic - by plane
authors:
  - Стасенко А. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 32
page_last: 32
lang: en
source: kvant_digital
extraction: vision
content_sha256: d0b35fefd7d6540ffea12df1f29bc9c6f2e2524b16432b05a9f994c4c1a4394b
prompt_sha256: draft-1
translated_from: content/ru/2024/02/articles/07_stasenko-iz-antarktiki-v-arktiku-samoletom-f929bc65.md
source_content_sha256: b4f6cde6e15df1e1e2e3b38f756083f8d617928c514f8e4438485a9383a1b6a1
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

FROM Antarctica to the Arctic - by plane
A.STASENKO

“We need to make them all friends with each other.”
- How to make them friends? - asked Cheburashka.

WHAT FEATS HAS NOT been demonstrated by aviation! Someone flew around the globe to check the time warp, someone landed a liner on the water of the Neva, someone... But the Society of Other Animals offered a grant to transport a pair of black penguins from Antarctica to the Arctic for their other meetings with polar bears.

According to the terms of the competition, delivery over the shortest distance should take exactly one day. A legal question arose: how will the flight trajectory be smoothed out in the system of the rotating Earth? – for timely processing of state permits “under the wing of an airplane.” To do this, it was necessary to maintain a spherical coordinate system: latitude $-\frac{\pi}{2} \leq \theta \leq \frac{\pi}{2}$, longitude $0 \leq \varphi \leq 360^\circ = 2\pi$, distance from the center of the Earth $r = R + h$, where $h$ is the flight altitude, $R \gg h$ is the radius of the Earth.

The shortest distance between the stripes in the system of “unstable stars” is $\pi R$, the day is $T = 3600$ s/hour $\cdot 24$ hours $= 8,6 \cdot 10^4$ s. This means that the average meridional speed of the aircraft is

$$v_\theta = \frac{\pi R}{2T} = \frac{\pi \cdot 6,2 \cdot 10^6 \text{ м}}{2 \cdot 8,6 \cdot 10^4 \text{ с}} \approx 113 \text{ м/с}.$$

But the Earth rotates under the plane trajectory of the aircraft, so the local value of its surface speed is (see figure)

$$v_\varphi = \omega R \cos \theta = \frac{R \cdot 2\pi}{T} \cos \theta = 4v_\theta \cos \theta.$$

DOI: https://doi.org/10.4213/kvant20240103

Therefore, the model speed of an airplane over a rotating Earth is

$$v = v_\theta \sqrt{1 + 16 \cos^2 \theta}.$$

It turns out that when crossing the equator ($\theta = 0$), the speed of the aircraft in the atmosphere, which rotates with the Earth, is equal to $v_{\max} = \sqrt{17}v_\theta \approx 460 \text{ м/с}$. And the parameters of the aircraft trajectory in the example under consideration have the form

$$\varphi = 2\theta + \pi, r = R + h.$$

At this point it finally became clear that we needed a supersonic aircraft, or a maximum Mach number, i.e. the ratio of flight speeds and sound in the air is equal to

$$M = \frac{v_{\max}}{v_{3B}} = \frac{460 \text{ м/с}}{300 \text{ м/с}} \approx 1,5.$$

Compared to the maximum speed of the aircraft, the change in trade winds and mousses (headwind or tailwind) seems insignificant.

Of course, here are the conditions that have arisen: after all, the Earth is not quite a ball and within a day it will slightly change the position of the relative stars, and together $R$ you can take $R + h$, and there is no need to transport the penguins to the southern stripes to begin with, and...

But even without these clarifications, isn’t it interesting to depict on a globe the projection of the trajectory of such an aircraft on the small area of ​​the country below it? For example, starting from the South lane S along the zero meridiana ($\varphi = 0$) due north N at a speed of $v_\theta$?
