---
id: 1980-1-salihova-sokolova-graficheskaya-sistema-shpaga-fbbce7ea
issue: kvant_1980_1
year: 1980
number: "1"
title: Graphic system Epee
authors:
  - Салихова А.
  - Соколова Н.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 61
page_labels: 56-59
tag: RC9K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2cb33c583731027d65ade75255b64178683e9aa0eef69457e180ca66c0dc7e08
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/25_salihova-sokolova-graficheskaya-sistema-shpaga-fbbce7ea.md
source_content_sha256: 449689ef22805adabff52d1e02abafa6d9f6f0643860d28c039001ed69348449
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

A. Salikhova, N. Sokolova

Graphic system Epee

figure made by computer have been repeatedly published on the covers of our magazine. Programs for "computer hobbyists" compiled experimental programs using fairly complex programming languages ​​and computer graphics systems.

Many figure for the “Art of Programming” section were also made on computers, but using programs whose authors were between 8 and 15 years old. Our photo shows a group of young programmers working on a graphoprostrolet. The schoolgirl on the far left, a seventh-grader Asya Salikhova, and her friend, an eighth-grader Natasha Sokolova, developed a set of procedures for the Shpara graphic system, which is used to create our computer graphics program.

Articles about this system, written by its developers, open the “Tribune of a Young Programmer” subsection.

The Epee system is a set of procedures, each of which draws a line or performs an auxiliary action (for example, changing the coordinate system). Speech procedures can be used in a variety of programming languages, including Robic, Rapier, Algol, Poplan, and Pascal. The sword is, first of all, a training system, so the names and parameters of its procedures*) were chosen so that they were easy to remember and understand. By the way, the named systems themselves are deciphered as follows:

School Pack of Graphic Procedures, Adapted

Where does figure begin?

In order for the machine to draw a steamboat like the one on figure 1, it must be given a task.

First, you should determine the location for figure, i.e., set the frame of the desired size (for example, 100 by 100 mm). After this it is necessary

*) If the words “procedure” and “parameter” seem unfamiliar to you, look at the materials of the first lessons of the Correspondence School of Programming («Kvant», 1979, Nos. 9-11).

⟦folio 57⟧

Dimo bring a pen or other drawing tool to point A, draw a line to point B, to points C and D, again to point A. Then move the tool to point E and continue working.

To perform these actions, the intended basic procedures of the Epee are: FRAME, SUPPLY, BEAM, POINT, CIRCLE and others. For example, a program in Rapier to depict a paroxodic could look like this: FRAME (100, 100); SUPPLY (25, 30); BEAM(15.45); BEAM (85, 45); BEAM (75, 30); BEAM (25, 30); SUPPLY (35, 45); BEAM (35, 50); BEAM (60, 50); BEAM (60, 45); SUPPLY (45, 50); BEAM (45, 60); BEAM (50, 60); BEAM(50, 50); END;

Let us describe in more detail the operation of the graphical procedures found in this program.

The FRAME (D, C) procedure plays a very important role in our system; any program that uses the Sword procedures must begin with it. Parameters D and B in this procedure indicate the dimensions of the frame in millimeters (D - length, H - height). Using the FRAME procedure, the machine, firstly, draws a frame of the specified size, secondly, it will find above and below the frame some information about figure (the name of the graphic system, the date and time of use figure) and, thirdly, it will establish a standard rectangular coordinate system inside the frame: the scale unit is 1 mm, the origin of coordinates is in the lower left corner of the frame.

How the BEAM and SUPPLY procedures work, you have already proven; the SUPPLY (X, Y) procedure places the drawing tool (plotter pen) at point (X, Y), without leaving any traces on the paper. The RAY (X, Y) procedure draws a straight line segment from the point where the pen was previously located to the point (X, Y).

All drawing procedures of the Speech system work only within the established frame. For example, if, when executing the BEAM procedure, the start or end point of a segment (or both at once) ended up outside the frame due to a program error, then only that part of the segment that is inside the frame will be drawn.

The END procedure, which has no parameters, tells the machine that the program has finished working with the plotter. After completing any Sword procedures, you cannot use it.

The name of most system procedures can be abbreviated. In particular, the words FRAME, BEAM and SUPPLY can be abbreviated to one letter: R, L and P. In contrast, the name of the END procedure cannot be abbreviated.

In its abbreviated form, the program turns out to be very compact. For example, for an image of an airplane.

⟦folio 58⟧

Just write*):

P (120, 100); P (30, 46); L (15, 46);
L (15, 40); L (30, 40); P (20, 46);
L (20, 60); L (15, 60); L (15, 25);
L (20, 25); L (20, 40); P (40, 60);
L (40, 46); L (30, 46); L (40, 60);
L (78, 60); L (85, 80); L (100, 80);
L (100, 55); L (85, 30); L (30, 30);
L (30, 46); P (48, 60); L (60, 90);
L (80, 90); L (70, 60); P (50, 30);
L (50, 46); L (60, 46); L (60, 30);
P (70, 50); L (48, 50); L (38.20);
L (60, 20); L (70, 50); . END;

Fig. 4.

Dots, circles, arcs

The POINT (X, Y) procedure (abbreviated as T (X, Y)) allows you to draw a point figure at the desired location. After this, the pero remains at the point (X, Y).

The CIRCLE (R) procedure will draw a circle of radius R centered at the point where pero was previously located. After using the procedure, pero returns to the center. The abbreviated name for this procedure is K(R). For example, according to the program: P (100, 100); T(50, 50);
K (10); K (20); K (30); K (40);
K (50); END;

COMPUTER. will draw several concentric circles (something like a target) with a dot in the center.

For the image of a friend, four procedures are used: DUGAL, DUGAP, DUGAL, DUGAPB (abbreviated as DL, DP, DLB, DPB). Each of them has three parameters:

*) The program was compiled by the third class I. Afanasyeva.

Fig. 3.

(X, Y, R). X and Y are the coordinates of the point where the arc should end, R is the radius of the arc. Just like the segment in the URE BEAM procedure, the arc is drawn from the point where the pero was located before it.

From drawing 4 it can be seen that from one point to another with a given radius, as a rule, 4 different arcs can be checked: firstly, more or less than a semicircle and, secondly, clockwise or counterclockwise. These four REM cases correspond to four procedures. The letter B at the end of the name means that the arc must be larger than a semicircle; procedures DP and DPB draw an arc counterclockwise, that is, to the right of the vector drawn from the starting point of the arc to the end point (hence the name DP - “arc of the right”), procedures DL and DLB draw an arc to the left of the vector, that is, clockwise. As an example, here is a program for figure 4:

P(100, 100); P (70, 30);
L (30, 70); L (33, 70); L (30, 67);
L (30, 70); P (70, 30); DP (30, 70, 35);
P (70, 30); DL (30, 70, 35);
P (70, 30); DP (30, 70, 35);
P (70, 30); DLB (30, 70, 35);
.END;

If a small radius list is specified, then the arc will not be broken, and the system will print the message:

ERROR. RADIUS IS LESS THAN HALF THE DISTANCE BETWEEN POINTS.

⟦folio 59⟧

Inscriptions

Very often it is necessary to place some inscriptions on figure. For this purpose, the Speech system provides the procedures INCAPTION, NPN and LINE.

The INscription (T, V, D) procedure (abbreviated as NP (T, V, D)) allows you to depict a horizontal inscription in straight (vertical) letters. The first parameter of the procedure is the text to be written (or a name whose value is the text). The point where pERO ​​is located is considered the lower left corner of the inscription. From this point, penERO begins to draw. Parameter B specifies the height of the inscription, and parameter D specifies its length.

The NPN (T, V, D) procedure works in exactly the same way, but produces an inscription with a standard right slant.

The LINE (T, X1, Y1, X2, Y2, X3, Y3) procedure allows you to draw the text T in an arbitrary position. The remaining parameters of this procedure are the coordinates of three points: (X1, Y1), (X2, Y2) and (X3, Y3). The text fits into the parallelogram, the vertices of which are these points (the fourth vertex is easy to complete). The first of these points is considered the lower left vertex of the parallelogram, the second - the upper left and the third - the lower right. By manipulating these points, you can even get inverted and mirror-reflected inscriptions.

In all these procedures, the inscriptions are written in lowercase letters; if we want to get a capital letter, then we need to put a double in front of it in the text.

Examples of the described procedures are shown on figure 5, executed according to the following program:

`:QUANTUM' -> A;

P(100, 100); P (10, 85); NP (A, 10, 30); P (60, 85); NPN (A, 10, 30); ROW(A, 60, 40, 60, 47, 80, 20); ROW(A, 60, 50, 60, 67, 80, 70); ROW(A, 40, 40, 40, 47, 20, 20); ROW(A, 40, 57, 40, 50, 20, 77); .END;

Changing the coordinate system
The coordinate system established by the FRAME procedure can be changed. For this, the procedures SCALE, START, ROTATE and some others are used.

The procedure SCALE (A) (abbreviated as M (A)) sets a new scale unit equal to A mm.

The ORIGIN (X, Y) procedure (abbreviated as H (X, Y)) transfers the origin of coordinates to the point (X, Y) of the current system; the ROTATION (A) procedure rotates the coordinate system by angle A around the acting coordinates. The angle is specified in radians, when A>0 the rotation is performed counterclockwise, when A<0 - clockwise.

If the START and ROTATE procedures were used several times in the same program, then each of them was used in the coordinate system established by the procedure, and in the end it was difficult to determine which coordinate system was in effect at a given moment. Therefore, a parameterless RESET procedure (abbreviated as C) is provided, which restores the standard coordinate system.

You can move from the standard coordinate system to polar coordinates using the procedure without parameters POLAR. In this case, in all Speech procedures, the parameter X is considered to be the polar radius, and Y is the polar angle. To return to Cartesian (rectangular) coordinates, use the DECARTES procedure.

We have described here only the basic procedures of the Speech system. Using together with them the designs of various programming languages, cycles, descriptions of procedures, prescription conditions, etc., you can use the Speech system to obtain a wide variety of figure and drawings, build graphs of complex functions, produce cartoons and perform other graphic work.
