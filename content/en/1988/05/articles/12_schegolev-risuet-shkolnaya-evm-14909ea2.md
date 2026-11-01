---
id: 1988-5-schegolev-risuet-shkolnaya-evm-14909ea2
issue: kvant_1988_5
year: 1988
number: "5"
title: School computer draws
authors:
  - Щёголев А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 54
page_labels: 51-52
tag: NDFP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6081f053ba432fb60026bb27be7fbbce392591409666560aa37c10fcfdfa5496
prompt_sha256: draft-1
translated_from: content/ru/1988/05/articles/12_schegolev-risuet-shkolnaya-evm-14909ea2.md
source_content_sha256: fdbb3ce50967fa17b70928af2ea97cd0a94a98e25765c39730696e3ce4a954a2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

School computer draws

A. G. SHEGOLEV

You can interact with a school computer equipped with a display in interactive mode according to a pre-preset scenario (see, for example, the articles of V. A. Kaimin in «Kvant», 1986, No. 10, 11). In this case, the computer and its user exchange fragments of texts and numerical data. Meanwhile, most school microcomputers allow not only “printing”, but also “drawing” on the screen, that is, they have graphic capabilities.

In order for an image to appear on the screen, we must indicate to the performer (the school computer) where and what needs to be drawn. Therefore, first of all, it is necessary to agree on a coordinate system.

The coordinate system adopted in the microcomputer differs from the one you know from your school mathematics course. The origin of coordinates (point O) is placed in the upper left corner, and the abscissa and ordinate axes are directed as shown in figure 1. The screen field is a set of points, each of which has a specific color, and the coordinates of any point are integers x, y within (for the Yamaha computer screen) 0≤x≤255, 0≤y≤191.

Just as a house is made of bricks, we will “build” any complex image from the simplest elements. To do this, let’s supplement the school algorithmic language familiar to you with the following graphical commands:

1) point (x, y), color — display a point of color color with coordinates (x, y);
2) segment from (x1, y1) to (x2, y2),

⟦folio 52⟧

color — draw a segment connecting points with coordinates (x1, y1) and (x2, y2) in color color;
3) circle(x, y), r, color — draw a circle of radius r with center at point (x, y) color color;
4) Buse (x, y), r, om α to β, color — draw arcs of a circle (x, y), r, color from angle α to angle β (Fig. 2);
5) paint over (x, y), color — color over the point (x, y) along with the circle within the closed line of the same color enclosed by this point (the screen border can be used as part of this line); if there is no such outline, the entire screen will be painted over.
It turns out that the listed commands are completely enough to depict quite intricate figures. For example, the image of a violin klion can be represented as a set of segments and arcs of different radii, smoothly turning into each other (Fig. 3).
To facilitate the construction of frequently repeated elements, we introduce two more commands:
6) frame from (x1, y1) to (x2, y2), color — draw a rectangular frame with sides parallel to the sides of the screen, color; the rectangle is defined by the coordinates of two diagonal vertices (x1, y1), (x2, y2) (Fig. 4);
7) frame - fill from (x1, y1) to (x2, y2), color - paint frame 6) and its inner area with color color.
Algorithms written using graphical commands can be translated into any programming language that has the appropriate tools. This is what the recording of operators 1) - 7) looks like in the MSX-BASIC language adopted on the Yamaha computer.
1) N PSET (X, Y), C (dot)
2) N LINE (X1, Y1) - (X2, Y2), C (segment)
3) N CIRCLE (X, Y), R, C (circle)
4) N CIRCLE (X, Y), R, C, A, B (arc; angles A and B - in radii)
5) N PAINT (X, Y), C (paint)
6) N LINE(X1, Y1) - (X2, Y2), C, B (frame)
7) N LINE(X1, Y1) - (X2, Y2), C, BF (filled frame).
The blue ones highlight changing elements, which can be numbers (constants), as well as variable names. N - number (numbering of operators in BASIC is required), C - an integer from 1 to 15, indicating the color that needs to be painted over this object:
1 - black, 6 - dark red,
2 - medium green, 7 - blue,
3 - light gray, 8 - medium red,
4 - dark blue, 9 - light red,
5 - light blue, 10 - dark yellow,
11 - light yellow,
12 - dark green,
13 - pink,
14 - gray,
15 - white.
For example, the BASIC operator 20 PSET(50, 100), 6 will result in a dark red dot appearing on the screen with coordinates x=50, y=100.
In addition, the computer is switched to graphics mode using the graphics command, which in BASIC will be written as SCREEN 2.
Will now take up the image of the picture placed at the beginning of the stat. The script in this case is figure done on paper. In general, a graphical script is a sequence of figure (scenes) and a description of their logic through
