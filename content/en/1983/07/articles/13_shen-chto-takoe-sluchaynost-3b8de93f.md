---
id: 1983-7-shen-chto-takoe-sluchaynost-3b8de93f
issue: kvant_1983_7
year: 1983
number: "7"
title: What is randomness?
authors:
  - Шень А. Х.
rubric: raznoe
page_first: 59
page_last: 59
page_labels: "57"
tag: G1S5
lang: en
source: kvant_digital
extraction: vision
content_sha256: ec7b3033f305f71104b194d00696f60d60dcf2d97717077cdabe1d3d627fda25
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/13_shen-chto-takoe-sluchaynost-3b8de93f.md
source_content_sha256: 18646f6031dd528f391b975005776398dfd9ecb27f60c12b0e2c8378cf328cd3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

What is service?

Having bought a ticket on the bus, you discover that its number consists of only sevens. Amazing, isn't it? Certainly! After all, this didn’t happen every day! Now imagine that the ticket number is 830877. You probably won’t find anything surprising in this. Why exactly? After all, both the number 777777 and the number 830877 occur equally often (it would be better to say equally rarely) - in one case out of a million. So why do we perceive their appearance differently?

Why is it that if our partner throws ten sixes in a row on a dice, we suspect something is wrong, but if he throws 2, 6, 2, 1, 2, 6, 4, 5, 1, 3, we don’t become suspicious?

Why is one sequence of each of the “servants”, but not the other (for example, sixes)? Is it possible to give an exact mathematical definition of service?

This definition was first proposed in 1919 by the German mathematician and physicist Richard Mises. We do not have the opportunity to present it in all details, but we will explain the idea.

For simplicity, let us consider sequences consisting only of “zeros” and “ones”. In what case do we agree to consider such a sequence to be a service sequence? For example, if we repeatedly add an ordinary coin and record the results (“heads” - 1, “tails” - 0), the resulting sequence should be a service one.

First of all, it is clear that in the case of a new sequence there must be approximately the same number of zeros and ones; therefore, a sequence of all zeros, like a sequence of all ones, is not useful.

Although the sequence
0101010101...
and contains an equal number of zeros and ones, hardly anyone considers it to be a service. What's wrong with it? For example, the fact that it never contains two consecutive zeros or two ones, while in the case of a new sequence the combinations 00, 01, 10, 11 should occur equally often. But the requirement for an equal share of the appearance of all combinations of the same length is not enough.

Let's write down the numbers 0, 1, 2, 3, ... in a row in the double system - we get the sequence
011011100101110111000...

It can be proven (try it!) that “in the limit” for any $n$ all combinations of zero and units of length $n$ will occur equally often in this sequence. But, despite this, it is unlikely that anyone will agree to consider her a servant.

So what is a service sequence? Mises suggested this approach to defining this concept. We will select some of its members from the sequence, guided by some rule. For example, you can select all members with four numbers or all members whose numbers are prime numbers. It is also allowed, when deciding whether or not to select a member, to take into account the values ​​of previous members of the sequence. For example, you can select those terms preceded by two ones in a row (No rule “select those terms that are themselves equal to one” is not allowed!) So, the von Mises sequence must be such that, under any rules for choosing zeros and ones, they occur equally often among the selected terms. (This requirement, as can be verified, prohibits the consideration of official references
