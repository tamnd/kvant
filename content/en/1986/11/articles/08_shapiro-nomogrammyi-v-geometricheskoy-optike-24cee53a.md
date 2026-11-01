---
id: 1986-11-shapiro-nomogrammyi-v-geometricheskoy-optike-24cee53a
issue: kvant_1986_11
year: 1986
number: "11"
title: Nomograms in geometric optics
authors:
  - Шапиро А. И.
rubric: shkola-v-kvante
page_first: 22
page_last: 23
page_labels: 20-21
tag: DFT7
lang: en
source: kvant_digital
extraction: vision
content_sha256: de3d5654b868f6dfd5a5107fa2b0acc5dc2fc4f2b00678c310cb9f53893f5887
prompt_sha256: draft-1
translated_from: content/ru/1986/11/articles/08_shapiro-nomogrammyi-v-geometricheskoy-optike-24cee53a.md
source_content_sha256: 8372cbdff32db06ee1a4bf39addb5f1febc5dcd3d67b1b0b2f0cac10921d7280
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

of an ideal refrigerator it is equal to (Fig. 2)

$$\eta_{\text{x max}} = \frac{Q_2}{A} = \frac{Q_2}{Q_1 - Q_2} = \frac{T_2}{T_1 - T_2} = \frac{1 - \eta_{\text{max}}}{\eta_{\text{max}}}$$

Note that, as follows from this formula, the cooling coefficient can be greater than unity.

And now it’s not difficult to prove how you can use a refrigerator to heat a room during the cold season - to do this, the refrigerator compartment needs to be taken outside (and all other parts of the “unit” left in the room!)! Then, having done the work $A$ (displaying the energy from the electrical network) and the amount of heat $Q_2$ from the street, we transfer the amount of heat $Q_1 = A + Q_2 > A$ to the room. It is clear that there is no contradiction with the law of conservation of energy - additional energy in the form of heat is taken from the cold load air.

A refrigeration machine operating in this way is called a “heat pump”, since heat is “pumped” from outside to inside the room. As a result of the operation of the heat pump, the room becomes warmer, and the street becomes even colder (the latter effect, of course, is absolutely perfect). The efficiency of a heat pump $\eta_{\text{h}}$ is determined by the ratio of the amount of heat received by the room to the external work required for this. Ideally it is equal to

$$\eta_{\text{h max}} = \frac{Q_1}{A} = \frac{Q_1}{Q_1 - Q_2} = \frac{T_1}{T_1 - T_2} = \frac{1}{\eta_{\text{max}}}$$

and always greater than one.

As an example, consider the case when the load air temperature is $-20^{\circ}\text{C}$ ($T_2 = 253\ \text{K}$), and the internal temperature must be maintained at $+20^{\circ}\text{C}$ ($T_1 = 293\ \text{K}$). Then

$$\eta_{\text{h}} = \frac{293}{40} \approx 7,3$$

that is, it uses electrical energy to operate a heat pump, we can get seven times more heat than with a custom device. Of course, the actual efficiency is always lower, and the heat pump engine also does not convert all the energy consumed into work. However, the use of a heat pump still turns out to be several times more cost-effective than the use of electric optics

From the school physics course you learned about how you can graphically solve various problems of geometric optics. For example, to find the position of the image of an exact light source in a thin face, it is enough to construct the path of two arbitrary rays that left the source and passed through the lens.

This note will tell you about another, somewhat untrained graphical method for solving such problems. At the same time, in the drawings offered to you, you will not see any light rays, or the optical axes of the lens, or even the lens itself. What kind of graphics are we talking about then?

In mathematics, there is a special section called nomography (from the Greek words pomos - law and grapho - food), which studies methods for constructing special drawings - nomography. With their help, you can, for example, not arbitrarily calculate, obtain approximate

⟦folio 21⟧

solving the equation or finding approximate values ​​of intersocial functions. We will also take advantage of this opportunity.

Let the luminous object be at a distance $d$ from a line with focal length $F$, and its image at a distance $f$. It can be shown (this is done in § 60 of Physics 10) that these three quantities are related by a simple relationship - the thin line formula:

$$\frac{1}{d} + \frac{1}{f} = \frac{1}{F}.$$

Note that each term included in the formula can be either positive or negative. If the object, or its image, or the focus of the line is real, the quantities $d$, or $f$, or $F$ are taken with a plus sign, but in the case of the object, or the image, or the focus of the line is minimal, the corresponding quantities are considered negative.

Let's build a nomogram for the line formula and show how it can be used to solve specific problems.

Let us depict a rectangular coordinate system $XOY$ (Fig. 1) on the plane. Along the $X$ axis we plot the segment $OA$ of length $d$, and along the $Y$ axis we plot the segment $OB$ of length $f$. For now, to determine $d$ and $f$, we will count the positive segments $KM$ and $KN$ through $F$. From the similarity of triangles $AOB$ and $AMK$ it follows that $$\frac{OB}{OA} = \frac{KM}{MA},$$ or $$\frac{f}{d} = \frac{F}{d-F},$$ whence

the familiar equation (*) is easily obtained.

Thus, we got that the lengths $d$, $f$ and $F$ are built on the drawing of the segments connecting each other with the equation of a thin line (that’s why when constructing we use such notations for the lengths of the segments). And this, in turn, means that we can build a nomogram for the line formula. Indeed, if distances $d$ from the object to the line are plotted along the horizontal axis of the rectangular coordinate system, and distances $f$ from the line to the image are plotted along the vertical axis, then all straight lines connecting the ends of the corresponding segments intersect at one point (Fig. 2). The projections of this point on the coordinate axes are identical and equal to the focal length $F$ of this line.

As you know, to determine a line on a plane, it is enough to know all the points belonging to it. Therefore, using the constructed nomogram, based on the known two of the three values ​​$d$, $f$ and $F$, it is always possible to graphically determine the missing third. So, for example, in the construction shown in figure 1, we actually determined the focal length of the line ($F$) from the known distances from the line to the object ($d$) and from the line to the image ($f$).

It is easy to verify that the proposed method is suitable not only for intrinsic lines, but also for scattering ones, as well as for any location of the object and image relative to the line. If, for example, the object or image is minimal, then the corresponding values ​​$d$ or $f$ are negative and, consequently,
