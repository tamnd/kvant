---
id: 1976-9-reznikov-formula-kardano-i-geometriya-fc02c5fd
issue: kvant_1976_9
year: 1976
number: "9"
title: Cardano formula and geometry
authors:
  - Резников А. Г.
rubric: osnovnye-stati
page_first: 19
page_last: 19
page_labels: "17"
tag: HDYH
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 0c3178c1a4202b32977f26ae9b15ee44f479ffaa1ee6371565b261b3f4e06f70
prompt_sha256: draft-1
translated_from: content/ru/1976/09/articles/04_reznikov-formula-kardano-i-geometriya-fc02c5fd.md
source_content_sha256: 9771af932d31ee2d0f12420d734bdb05ba936e40327e75025e65b0e1ed191ef5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦figure⟧

## Cardano formula and geometry

You are familiar with how to use the coefficients of a second-degree equation $x^2+px+q=0$ to determine how many real roots it has. If $p^2-4q\gt0$, then there are two roots, if $p^2-4q=0$, then there is one root, and finally, if $p^2-4q\lt0$, then there are no roots.

In this issue, a similar condition is derived for the third degree equation $x^3+px+q=0$. Using this condition, you can get one clever inequality connecting the elements of an arbitrary triangle. Here's how it's done.

Let $ABC$ be a triangle with sides $a$, $b$, $c$; $p$ is its semi-perimeter, $S$ is its area, and $R$, $r$, $r_a$, $r_b$, $r_c$ are the radii of the circumscribed, inscribed and excircle circles. It turns out that the following relationships are correct:
$$
r_a+r_b+r_c=4R+r,\quad r_ar_b+r_br_c+r_cr_a=p^2,\quad r_ar_br_c=pS.\tag1
$$

Equalities (1) mean that the numbers $r_a$, $r_b$, $r_c$ are the roots of the following cubic equation:
$$
x^3-(4R+r)x^2+p^2x-pS=0.\tag2
$$
This follows from the fact that $r_a$, $r_b$, $r_c$ are the roots of the polynomial
$$
(x-r_a)(x-r_b)(x-r_c)=x^3-(r_a+r_b+r_c)x^2+(r_ar_b+r_br_c+r_cr_a)a-r_ar_br_c.
$$

Having written down for equation (2) the condition for the validity of all three of its roots, we, after simple transformations and using the formula $S=pr$, arrive at the following inequality:
$$
[p^2-(2R^2+10Rr-r^2)]^2\le4R(R-2r)^3.\tag3
$$
From (3) it follows that $$
R\ge2r\tag4
$$
and what $$
|p^2-(2R^2+10Rr-r^2)|\le2\sqrt{R(R-2r)^3}.\tag5
$$
Equality in (3) and (5) is achieved when two of the numbers $r_a$, $r_b$, $r_c$ are equal, i.e. when the triangle is isosceles.

### Exercises

1. Prove formulas (1). To do this, print the following expressions for $S$:
$$
S=rp=r_a(p-a)=r_b(p-b)=r_c(p-c)=\dfrac{abc}{4R}=\sqrt{p(p-a)(p-b)(p-c)}.
$$
2. Find out the conditions for achieving equality in (4).
3. Prove that $16Rr-5r^2\le p^2\le4R^2+4Rr+3r^2$.
4. Investigate for which isosceles triangles the number $p^2-(2R^2+10Rr-r^2)$ is non-negative.
