---
id: 1990-10-kelbert-piterbarg-mediannaya-filtratsiya-1fc66739
issue: kvant_1990_10
year: 1990
number: "10"
title: Median filtering
authors:
  - Кельберт М. Я.
  - Питербарг Л.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 12, 13
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4ebdf9660738f786310e6874b7ea0aa74d375777ff8f8793109c8930b8e061b3
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/04_kelbert-piterbarg-mediannaya-filtratsiya-1fc66739.md
source_content_sha256: 580ea2bb945c50a563f6201e05607e95fe7a7816d18a3cfcfd1f10764b93db5c
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 8⟧

---
running_head:
folio:
---

MEDIAN
FILTRATION
Candidate of Physical and Mathematical Sciences
M. KELEVERT,
Doctor of Physical and Mathematical Sciences
L. PITERSBARG

8

⟦folio 12⟧

---
running_head:
folio:
---

number of width $2k+1$ does not contain a single monotonic segment of length $k+1$, then the numbers $x_n$ can take only two values ​​(binary signal).

Thus, the “paradoxical” situation of example 2 arose only for biary signals.

Image processing

Interest in median filtering these days is caused, first of all, by the problem of processing photographs of the Earth's surface and celestial bodies obtained from space. Taking four photographs is often hampered by cloudiness, which in this case should be considered as noise. Of course, if a significant part of the object is covered by clouds, no mathematical procedure will help restore its true contours. But if cloudiness is rare, then median filtering comes to the rescue.

Divide a black and white photograph into small squares and match it with a rectangular table of numbers $x_{ij}$ brightness level in each square. Now, together with the images, we are dealing with a table of numbers. And you can apply the median filtering procedure to them. It's done like this. Let's select some shape (circle, square, cross, stake, etc.) - it's called a filter window - and apply it to the image. The brightness value in the center of the window is replaced by the median of the numbers $x_{ij}$ for all points included in this window.

For example, let $x_{ij}$ be equal to 100 if $i$ and $j$ are both divisible by 10, and equal to 0 otherwise. Check that after median filtering such an image will consist of only zeros. This means that when processing real images, very dark and very light spots should disappear. This can be seen in the photograph of one of the sections of the Pamirs, obtained by

Fig. 1.

⟦folio 13⟧

---
running_head:
folio:
---

noah from the Soyuz spacecraft. In the first, non-descript photo, dark spots on the snow cover are clearly visible. And in the second image, obtained after median filtering, these spots disappeared.

Median image filtering has the property, important from a practical point of view, of maintaining sharp boundaries of black and white objects. Let's take, for example, the simplest image: a black square on a white background. The brightness values ​​at the points of the square are 1, and outside it - 0 (Fig. 1). With median filtering with a window in the form of a square $3 \times 3$, the result will be a square with thrown out corner points, and if the window has the form of a cross from a spot of a point, then the black square will be invariant.

Exercise 12. On figure 2 there are five windows, and below them there are five images. Check that all images are invariant.

In conclusion, we note that the concept of median filtering is important only for discrete signals (i.e., sequences of numbers), but also for a continuous signal (i.e., a function that defines on a number line or on some segment of it). We will not give an exact definition - if you wish, you can come up with one yourself; Let’s just say that such filtering has the main property of discrete filtering: it destroys “outliers” while preserving the general appearance of the signal.

Fig. 2.

are variant with respect to median filtering with corresponding windows.

As in the one-dimensional case, median filtering successfully removes rare large samples, and the sliding device removes small interleaved errors. If there are large errors, then the sliding device is harmful, because, “smearing” the error, it creates gray spots on the photo.

Exercise 13. Subject the picture on figure 3 to median filtering with windows in the form of a square $3 \times 3$ and a cross of 5 cells, as well as a sliding device with the same windows. The blue color responds with a magnitude signal of 2, red with 0, and white with +2.

Hint: The first time you filter, the image will disappear.

In conclusion, we note that the concept of median filtering is important only for discrete signals (i.e., sequences of numbers), but also for a continuous signal (i.e., a function that defines on a number line or on some segment of it). We will not give an exact definition - if you wish, you can come up with one yourself; Let’s just say that such filtering has the main property of discrete filtering: it destroys “outliers” while preserving the general appearance of the signal.
