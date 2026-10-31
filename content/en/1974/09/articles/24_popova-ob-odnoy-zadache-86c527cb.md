---
id: 1974-9-popova-ob-odnoy-zadache-86c527cb
issue: kvant_1974_9
year: 1974
number: "9"
title: About one task
authors:
  - Попова И.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 71
page_last: 71
page_labels: "69"
tag: FRYS
lang: en
source: kvant_digital
extraction: vision
content_sha256: f91df1e3198d8e0aa73164f097f308613432f7a10c796bdd33c586b3594731aa
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/24_popova-ob-odnoy-zadache-86c527cb.md
source_content_sha256: 020e629d8f5f4e945982d5dd0afc8dc4c67accb5f067d215a564df5fe9933811
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 69⟧

Ira Popova
About one task

I'll tell you about one problem that I came up with. Here it is: prove that the number $4^{2m} - 1$ with natural m is divisible by 15. I came up with it like this.

In 1973, when I was in the 7th grade, the following task was proposed at the regional Olympiad: prove that the number $4^{1973} - 1$ is composite. I decided it this way:

$$4^{1973} - 1 = (2^{1973})^2 - 1 = (2^{1973} + 1) \times (2^{1973} - 1),$$

therefore, $4^{1973} - 1$ is divisible by $(2^{1973} \pm 1)$. You can also notice that

$$4^1 - 1 = 3 \text{ делится на } 3,$$
$$4^2 - 1 = 15 \text{ делится на } 3$$

and so on, I checked up to the 14th power, the resulting numbers were always divisible by 3. But then I could not prove the statement that $4^n - 1$ is divisible by 3 for natural n. Then I finally proved it:

$$4^n - 1 = 4^n - 4 + 3 = 4(4^{n-1} - 1) + 3 = 4[4(4^{n-2} - 1) + 3] + 3 = 4^2(4^{n-2} - 1) + 3.4 + 3 = 4^2(4^{n-2} - 1) + 3(4 + 1) = \dots = 4^n(4^{n-n} - 1) + 3(4^{n-1} + 4^{n-2} + \dots + 4^2 + 4 + 1) = 3(4^{n-1} + 4^{n-2} + 4^{n-3} + \dots + 4^{n-n}).$$

In this way, you can prove many interesting statements, for example: if the exponent n is divisible by some number m, then, in addition to the divisor 3, the number $4^1 - 1$ also has a divisor $4^m - 1$. This could probably be proven more easily using the method of mathematical induction, but I didn’t succeed.

And now - the solution to the problem: prove that the number $4^{2m} - 1$ for natural m is divisible by 15.

Solution. The number 4 to an even power ends in the number 6, so $4^{2m} - 1$ ends in the number 5, and therefore is divisible by 5.

But the number $4^n - 1$ is also divisible by 3 - I have already proven this. Therefore, if n = 2m, then $4^n - 1$ is divisible by both 3 and 5, that is, by 15.
