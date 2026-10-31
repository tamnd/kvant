---
id: 1970-11-kak-nayti-oshibku-65f9e002
issue: kvant_1970_11
year: 1970
number: "11"
title: How to find the error
rubric: smes
page_first: 28
page_last: 28
page_labels: "26"
tag: QVQB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 21d4e75a9af6235ad4a95ceda4306b92e9e1aac6bc9cbf78bb9f7b9ac2fef79c
prompt_sha256: draft-1
translated_from: content/ru/1970/11/articles/08_kak-nayti-oshibku-65f9e002.md
source_content_sha256: 047f0462fcc9fecaba27dc957dad934bd013ae2c96bb4df8bac4d0aab3cd3180
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

HOW TO FIND AN ERROR

You have multiplied two long polynomials. How to check if you made a mistake in your calculations?

We present two methods that allow us to find some possibilities of error (but, of course, do not provide a complete guarantee of the correctness of the verified calculations).

Method 1. Take the sum of the coefficients of the first polynomial and multiply it by the sum of the coefficients of the second. Should get the sum of the coefficients of the product. This will be the value of the polynomial at $x=1$.

The above method allows you to find errors in arithmetic (for example, if the “equality” $2 \cdot 3=5$ was used), but not in algebra. Let's say, if at some stage you wrote $2x^2 \cdot 3x^3=6x^4$, then this method will not produce an error.

Method 2. It differs from the first in that the coefficients for even powers $x$ are taken with a plane sign, and for odd ones with a minus sign. Otherwise, this method is the same as the first. Here we get the value of the polynomial at $x=-1$.

The second method is more complicated than the first; this also allows us to identify some algebraic errors. When checking for "equality" $2x^2 \cdot 3x^3=6x^4$ the result is $2 \cdot (-3)=6$. This equality is absurd, which means there was an error in the calculations.
