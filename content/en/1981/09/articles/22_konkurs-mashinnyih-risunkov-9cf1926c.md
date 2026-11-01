---
id: 1981-9-konkurs-mashinnyih-risunkov-9cf1926c
issue: kvant_1981_9
year: 1981
number: "9"
title: Machine competition figure
rubric: raznoe
rubric_sub: Разное
page_first: 57
page_last: 58
page_labels: 55-56
tag: Z9WV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 54ccf55c96bed811550360553897452026d2bc4edaec18031eca1b203a8f5e38
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/22_konkurs-mashinnyih-risunkov-9cf1926c.md
source_content_sha256: a1a4fb42f6c498aa53c2aa4805b97f0536bca719ef4068b7bb818d1637250e0b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

Data - sets*). The Pascal language has been selected for preliminary study in the following issues «Kvant».

The reader can become more thoroughly acquainted with the languages ​​discussed in this article in the following literature: Pervin Yu. A. “Fundamentals of Fortran” (M., “Nauka”, 1973).
Lavrov S. S. “Universal programming language (Algol-60)” (M., “Nauka”, 1972).

*) The rapier, which was slowly becoming responsible, took advantage of this novelty - see «Kvant», 1980, No. 3, ZShP, lesson 8.

Contest
machine
figure

The editors of the journal «Kvant» and the Computing Center of the Siberian Branch of the USSR Academy of Sciences announce a competition for the best figure, executed on a computer using computer graphics systems.

Schoolchildren and students of vocational schools can take part in the competition.

Realistic or stylized figure, ornaments, families of mathematical curves, images of surfaces, etc. Figure must be original (repetitions of figure published in our magazine are not accepted for the competition), ornaments and patterns of mathematical interest must be combined with natural merits.

To figure you must attach a complete printout of the program, a detailed commentary on it, explaining the mathematical idea and the order of operation of the program, detailed information about the author (authors) - last name, first name, patronymic, school and class number, full home address.

Students who do not have independent access to a computer with graphospace can send programs for constructing figure with an approximate excerpt attached. Programs can be executed in Rapier, Pascal or Algol using the Shpar system (see «Kvant», 1980, No. 1, p. 56) or in Fortran using the graphical system described below. The volume of the program is no more than 100 operators, size figure is no less than 100×100 mm and no more than 300×300 mm.

Carefully check the program manually before submitting it to the competition: errors in competition entries will not be corrected.

All sections of the competition (including students of the Correspondence School of Programming and its films) must submit their work no later than November 15, 1981 at the address: 630090, Novosibirsk, 90, Computing Center of the Siberian Branch of the USSR Academy of Sciences, School Information Group, for the competition.

We wish you good luck! We are waiting for figure and the program!

For beginners in Fortran
To access the graphical system from a Fortran program, you must follow the following rules:

1. At the beginning of the program there must be an initiating CALL SBROS statement, and before its logical completion there must be a CALL STR statement.

2. For rectilinear movements of the pen to specified points, the operator CALL LINX (X, Y) is used, where X, Y are the coordinates of the point in mm; if the pen is turned off, a cold stroke is carried out; if it is turned off, a segment is drawn. You can turn the pen on and off at the right moments using the CALL PERO and CALL VP operators.

3. To draw segments “with free ends”, you can also call the module CALL OTREZ (XN, YN, XK, YK),

⟦folio 56⟧

where the parameters are the coordinates of the start and end points of the segment; This model itself turns on the pen at the starting point of the segment and turns it on after drawing.

4. A whole circle can be drawn using the CALL OKR (XC, YC, R) operator, where XC, YC are the coordinates of the center, R is the radius, and the pen is also turned on and turned on automatically. A friend can be drawn by writing the line CALL OKRI (XC, YC, R, ALF, DALF); here ALF is the initial central angle, DALF is the corner vertex of the arc with a sign that determines the direction of the traversal. Angular dimensions are given in degrees, although degrees are not measured, of course. After drawing an arc, the pen itself does not turn on; if necessary, it can be enabled by the CALL VP operator; the pen turns on automatically at the beginning of the arc; if it was turned on before accessing this module, an additional segment is drawn from the processed point to the beginning of the arc.

5. To create a drawing in two or more colors or several line thicknesses, use the CALL NPERA (N) operator, where N can take values ​​0,1,2,3. This operator does not turn on the pen itself, but only remembers which pen should be used next. The main nib is considered to be nib number 0; it executes the drawing if the pen change operator is not in the program.

Already several subroutines that have been removed allow you to draw a variety of images; the necessary calculations, logical actions, one or two subroutines can be prepared by themselves using Fortran. Curved lines represent a sequence of small segments; The LINX model can work in a loop.

In general, the program should not be longer than 60-100 statements, it should include appearances - what pens should be installed, the expected size of the drawing, the initial position of the pen (but corresponds to the origin of the coordinate system).

As an example, here is a program for a simple drawing (of course, such a drawing is not suitable for a competition):

DIMENSION X (1Ø), Y (1Ø)
CALL SBROS
DO 1 K=1,9
CALL LINX (X (K), Y (K))
CALL PERO
CALL VP
DATA X/2Ø., 1Ø., 1Ø., 5Ø., 5Ø., 4Ø., 2Ø., 3Ø., 3Ø./, Y/36., 26, 8., 26., 36., 36., 26., 8./
CALL OTREZ (3Ø., 26, 5Ø., 26.)
CALL NPERA (1)
CALL OKR (2Ø., 26., 5.)
CALL LINX (15., 8.)
CALL PERO
CALL OKR 1(2Ø., 7., 5., 18Ø., —18Ø.)
CALL LINX (25., 8.)
CALL VP
CALL STP
END

Moreover. For EC series machines, the zeros must be crossed out.
