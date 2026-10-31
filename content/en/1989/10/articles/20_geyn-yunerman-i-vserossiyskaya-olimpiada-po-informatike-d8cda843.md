---
id: 1989-10-geyn-yunerman-i-vserossiyskaya-olimpiada-po-informatike-d8cda843
issue: kvant_1989_10
year: 1989
number: "10"
title: I All-Russian Olympiad in Informatics
authors:
  - Гейн А. Г.
  - Юнерман Н. А.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 72
page_last: 73
page_labels: 70-71
tag: JP98
lang: en
source: kvant_digital
extraction: vision
content_sha256: e9ed1b3d628927c37545ddd7586e5eabe105270cdcabcdac278c94a9da101b7f
prompt_sha256: draft-1
translated_from: content/ru/1989/10/articles/20_geyn-yunerman-i-vserossiyskaya-olimpiada-po-informatike-d8cda843.md
source_content_sha256: 302ac8d859cc5f2aa281a5199a65bb0b6b88c1ea081752ddee92a1c3730e534f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 70⟧

THERE ARE IDEAL, AND $E=3$ V, $L=0,09$ H, $C=100$ µF.

4. The single-lens camera lens has a focal length of $F=5$ cm. The shutter speed (the time during which each area of ​​the image on the film is exposed) is controlled in this camera using a click shutter. The principle of shutter operation is as follows: a slit moves along and near the photographic film at a constant speed of $u=1$ m/s, the width of which can be varied within wide limits to obtain the required shutter speed. Using a stationary camera, a vehicle whose length is 4 times its height is viewed from a distance of $a=20$ m. The car moves horizontally at a speed of $v=20$ m/s perpendicular to the direction camera - car mount. When shooting, the shutter slit was positioned vertically. What was the length-to-height ratio of the resulting sharp image on film automatically?

Experimental tour

8th grade
1. Determine the mass of the cylinder.
Equipment: cylinder, dynamometer, spool of thread, ballpoint pen refill.
2. Determine the focal length of the diverging lens.

I All-Russian Olympiad in Computer Science

From March 21 to March 25, 1989, the first All-Russian Olympiad in Informatics was held in Krasnoyarsk. Among its organizers, who hosted 143 schoolchildren from all regions of Russia, were Krasnoyarsk University, the Krasnoyarsk Pedagogical Institute, the Computing Center of the USSR Academy of Sciences (Krasnoyarsk) and the Main Directorate of Public Education of the Krasnoyarsk Regional Education Committee of the Krasnoyarsk Regional Committee.

The grand opening of the Olympiad took place on March 21 in the regional Palace of Pioneers and Schoolchildren, and on the morning of March 22 at Krasnoyarsk University, participants attended the solution of theoretical problems. 4 hours were allotted to complete the work. All tasks required creating an algorithm and writing it in some algorithmic language.

A day later, on March 24, a practical round took place, during which it was proposed to solve two problems using a personal computer within four hours. Computers such as “Yamaha”, “Corvette” and “BK-0010” were provided to the participants. This does not mean, unfortunately, that schoolchildren themselves could choose the type of computer on which they would like to work - the number of “Yamahas” was less than the number of people willing to perform a practical tour on them. Therefore, the distribution of participants among the cars was decided by lot. True, schoolchildren from one regional team were cut off by machines. BASIC was declared the official language of the practical type. In order to ensure the equality of all participants, the use of their floppy disks was not cut.

Here are the tasks for both days of the Olympiad.

Theoretical tour

1. The abbreviation ABCD is specified by the coordinates of its vertices. On opposite sides AB and CD there are sequences R1 and R2 of N partition points, and on sides BC and AD there are sequences R3 and R4 of M partition points. The numbering of the elements of the sequences R1 and R2 begins, respectively, from points A and D, and R3 and R4 - from B and A. By connecting points with the same numbers in the partitions R1 and R2, and then in the partitions R3 and R4, with segments, we obtain a partition Q of the ABCD primordial into a set of quadrangles. Construct an algorithm that determines a quadrilateral

⟦folio 71⟧

the pleasing partition $Q$ with the most fruit, provided that the segments connecting the partition points $R1$ and $R2$ are parallel to the side $AD$.

Sequences $R1, R2, R3, R4$ are specified as arrays of the lengths of the partition segments of the corresponding sides of the rectangle.

2. Construct an algorithm that models on the display screen the movement at a constant speed $V$ of two circles with radius $R$ inside the direct field of the cloud, specified by the coordinates of its vertices. At the moment the movement begins, the coordinates of the centers of the circles are $(X1; Y1)$ and $(X2; Y2)$, and the angles between the motion trajectories and the vertical coordinate axis are $A1$ and $A2$. The colliding circle with each other and with the boundaries of the clouds is elastic.

3. According to the rules of the game, the given $N$ domino tiles are laid out in a straight chain, starting with a tile chosen at random, in both ends as long as possible. Construct an algorithm that allows you to determine a variant of laying out the tiles in which by the time the chain cannot be continued, the maximum number of points remains “on hand.”

4. There are two identical disks. Each of them has a circular hole with radius $R$ touching the edge of the disk. The disc is located horizontally, pressed tightly against each other and fastened at the neck with an axis passing through their center of rotation. The upper disk is stationary, and the lower one rotates uniformly with a given angular velocity $W2$. Along the boundaries of the upper disk, $W1 N$ balls of radius $R$ roll with a constant given angular velocity. The balls are located tightly one after another and are numbered from 1 to $N$. If, when the holes on the disks coincide, the ball is drawn, then the density of the chain of balls is “instantly” restored. Construct an algorithm that allows you to determine the numbers of the first $M$ balls dropped out when the hole on the disks coincides, if at the moment of the start of movement between the centers of the hole of the upper and lower disks was equal to $A1$, and the angle between the centers of the hole of the upper disk and the first ball of the chain was $A2$. The angle of the sector along the arc of which the chain of balls is located is equal to $A3$.

**Practical tour**

1. On the interval (1000; 9999) find all prime numbers, each of which has the property that the sum of the first and second digits in the notation of this number is equal to the sum of the third and fourth digits.

2. Find the decimal notation of the number $3^{512}$.

Perhaps there will be a desire among readers to solve the problems of a practical tour. For them, we provide answers to these problems.

1. On a given interval there are 56 such prime numbers:
   1423, 1607, 1753, 1973, 2011, 2213, 2341, 2543, 2617, 2671, 2819, 2837, 3407, 3461, 3517, 3571, 3719, 3847, 4013, 4637, 4673, 4691, 4729, 4783, 4967, 5023, 5261, 5519, 5573, 5591, 5647, 5683, 5849, 5867, 6143, 6217, 6271, 6473, 6491, 6529, 6547, 7043, 7649, 7759, 8017, 8053, 8219, 8237, 8273, 8291, 8329, 8677, 9137, 9173, 9283, 9467.

2. The required number contains 245 digits:
   19323349832288915105454068722019581055401465761603328550184537628902466746415537000017939429786029354390082329294586119505153509101332940884098040478728639542560550133727399482778062322407372338121043399668242276591791504658985882995272436541441.

When checking the work of each task, first, regardless of the others, it is scored from 0 to 5 points. The criteria for assessing problems of a theoretical type are quite traditional, so they remain based on assessments of a practical type. The highest score was given if an effective program was created that gave the correct result; 4 points are given to those whose program was less effective, but also gave the correct result; 3 points were given for an ineffective correct program that gave an incomplete result (for example, in the first problem such a program did not have time to produce all 56 numbers in the optimal time allotted); 2 points were given for the correct program if there was no result; 1 point is given to those who, despite the correct algorithm, made errors in the program; a score of zero was given if the algorithm was incorrect.

After checking all the problems, the difficulty coefficient was displayed. The overall assessment of the work is equal to the sum of the products of assessments for the task corresponding to the difficulty coefficients.

How the participants coped with the optimization tasks can be judged from the following table, which shows the number of participants who scored a certain number of points for the task.

**Practical tour**

1. On the interval (1000; 9999) find all prime numbers, each of which has the property that the sum of the first and second digits in the notation of this number is equal to the sum of the third and fourth digits.

2. Find the decimal notation of the number $3^{512}$.

Perhaps there will be a desire among readers to solve the problems of a practical tour. For them, we provide answers to these problems.

1. On a given interval there are 56 such prime numbers:
   1423, 1607, 1753, 2011, 2213, 2341, 2543, 2617, 2671, 2819, 2837, 3407, 3461, 3517, 3571, 3719, 3847, 4013, 4637, 4673, 4691, 4729, 4783, 4967, 5023, 5261, 5519, 5573, 5591, 5647, 5683, 5849, 5867, 6143, 6217, 6271, 6473, 6491, 6529, 6547, 7043, 7649, 7759, 8017, 8053, 8219, 8237, 8273, 8291, 8329, 8677, 9137, 9173, 9283, 9467.
