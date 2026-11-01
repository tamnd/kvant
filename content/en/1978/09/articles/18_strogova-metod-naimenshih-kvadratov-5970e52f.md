---
id: 1978-9-strogova-metod-naimenshih-kvadratov-5970e52f
issue: kvant_1978_9
year: 1978
number: "9"
title: Least squares method
authors:
  - Строгова А.
rubric: raznoe
page_first: 53
page_last: 53
page_labels: "51"
tag: 3IBN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9456d820939f9ca75d30e7525f32f1b3b3e9e573e525a479c598f993db79b219
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/18_strogova-metod-naimenshih-kvadratov-5970e52f.md
source_content_sha256: 904ad1796188bb454acc77149967eac6cf623f090b2365ff397f9aacea95d10c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

The least squares method is used when processing measurements to smooth out the “noise” of the experiment: this method allows you to correct random errors that inevitably arise during measurements in the case when the nature of the dependence of the measurement of a value on the independent variable is specified.

Let us consider the simplest situation, when the measured quantity $y$ depends on one variable $x$. Let $n$ measurements have been made and for the values ​​$x_1, x_2, \dots, x_n$ of the variable $x$ measurements $y_1, y_2, \dots, y_n$ have been obtained. The task consists of drawing a straight line $y=ax+b$ that is immediately applicable to the points $P(x_1; y_1), P(x_2; y_2), \dots, P(x_n; y_n)$.

The solution to the problem, of course, depends on the fact that the concept of the words “best adjacent” is that “best” is considered to be the straight line for which the sum of squared deviations takes the smallest value, i.e. the expression

$$A_n = \sum_{i=1}^{n} (y_i - (ax_i + b))^2. \tag{1}$$

On figure the desired line $y=ax+b$ and points $P_1, \dots, P_n$ are depicted. The difference $y_i - (ax_i + b)$ shows the deviation (along the ordinat axis) of the experimental point $P_i (x_i, y_i)$ from the original straight line.

How to find the value of $a$ and $b$ that minimize expressions (1)? Let's assume that such values ​​exist, and the parameter $a$ has already been found for us. To find $b$, we rewrite $A_n$ as

$$A_n = \sum_{i=1}^{n} (y_i - ax_i)^2 - \sum_{i=1}^{n} 2b (y_i - ax_i) + \sum_{i=1}^{n} b^2 - 2b \sum_{i=1}^{n} (y_i - ax_i) + \sum_{i=1}^{n} (y_i - ax_i)^2.$$

![Graph of $A_n$](image)

Consider $A_n$ as a (quadratic) function of $b$. It reached a minimum at

$$b = \frac{1}{n} \sum_{i=1}^{n} (y_i - ax_i) = \frac{1}{n} \sum_{i=1}^{n} y_i - \frac{a}{n} \sum_{i=1}^{n} x_i.$$

Putting

$$\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i; \bar{y} = \frac{1}{n} \sum_{i=1}^{n} y_i$$

we can write $b = \bar{y} - a\bar{x}$, from where for $A_n$ we get

$$A_n = \sum_{i=1}^{n} ((y_i - \bar{y}) - a (x_i - \bar{x}))^2 = a^2 \sum_{i=1}^{n} (x_i - \bar{x})^2 - 2a \sum_{i=1}^{n} (y_i - \bar{y}) (x_i - \bar{x}) + \sum_{i=1}^{n} (y_i - \bar{y})^2.$$

Let us now consider $A_n$ as a square function of $a$. She has very/no access minimum at

$$a = \sum_{i=1}^{n} (y_i - \bar{y}) (x_i - \bar{x}) / \sum_{i=1}^{n} (x_i - \bar{x})^2.$$

The best line turned out to be straight line $y=ax+b$, where

$$\frac{\sum_{i=1}^{n} (y_i - \bar{y}) (x_i - \bar{x})}{\sum_{i=1}^{n} (x_i - \bar{x})^2}, \frac{\bar{x} \sum_{i=1}^{n} (y_i - \bar{y}) (x_i - \bar{x})}{\sum_{i=1}^{n} (x_i - \bar{x})^2}, b = \bar{y} - \frac{\sum_{i=1}^{n} (y_i - \bar{y}) (x_i - \bar{x})}{\sum_{i=1}^{n} (x_i - \bar{x})^2}.$$

Exercise

1. Solve the problem of smoothing noise using the Gaussian method for the following non-linear functions of one variable
a) $y=ax^2+bx+c$;
b) $y=a \cdot \cos x+b \cdot \sin x$.
2. How does the Gaussian method “work” in space (for two independent variables)? Let us consider the problem for the plane $z=ax+by+c^*$.
3. Find the point for which
a) the sum of distances from three given points (not lying on the same straight line) is minimal;
b) the sum of the distances from three given circles is minimal.

A. Strojuva

*) A geometric illustration for this problem is given on the first page of the cover «Kvant» No. 8.
