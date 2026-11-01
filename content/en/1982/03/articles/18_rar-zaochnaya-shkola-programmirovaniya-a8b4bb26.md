---
id: 1982-3-rar-zaochnaya-shkola-programmirovaniya-a8b4bb26
issue: kvant_1982_3
year: 1982
number: "3"
title: Correspondence School of Programming
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 58
page_labels: 52, 55, 56
tag: AL95
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9e064ab8c7c1d65d6ecd8e980111f392b3e8cb4042f97a367f27a88127963a15
prompt_sha256: draft-1
translated_from: content/ru/1982/03/articles/18_rar-zaochnaya-shkola-programmirovaniya-a8b4bb26.md
source_content_sha256: 635ddf15ceb240dbf518964151bf160f5b2ba594dcc6e757e70004c0de716511
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

Correspondence school
programming
Lesson 19:
Dynamic structures

There are tasks in which it is convenient to have data structures that are more flexible than arrays, records, and files. For example, I would like to be able to change the order of elements of a data structure, insert new elements into it, and throw away elements that have become unnecessary. The point here is that the structure can change range while solving the problem (until now we have dealt in Pascal only with static structures that were determined once and for all at the time the program was written). Dynamic structures are not specifically defined in the language, as, for example, arrays are defined, but they can be built using some language tools, which we will now talk about.

Pointers and pointable variables
In Pascal programs, you can, for example, use pointer types with already known types. The pointer type is specified by the syntax diagram.

Thus, each type $t$, standard or described in the program, can be associated with a pointer type $\uparrow t$. A value of type $\uparrow t$ is a pointer (or, equivalently, a reference-reference) pointing to some value of type $t$.

It is most convenient to think of a pointer as the address of the location in machine memory where the value it points to is located.

Just as in mathematics you need the number 0 to denote the absence of objects, in programming you need to have a null pointer that would not point to anything (or, what is the same, point to nothing). The standard constant nil serves as such a pointer. Any pointer type has it among its values.

Let some variable $P$ (we call it a pointer variable) be of type $\uparrow t$. Calling a standard procedure

new(P)

will allocate space in memory for a new *) value of type $t$ and make the value of the variable $P$ a pointer to this new value, represented in the program as a pointed variable. The syntax diagram of the specified variable is as follows:

Break we can finally define what a variable is in the Pascal language: it is either a name described in the variable description section, or a variable with indices, or a field selection, or a buffer variable, or, finally, a pointed variable.

Chained lists
Let us apply the language tools we have just considered to the simplest form of range structures - a chain list. This list is a sequence of records of the same type $t$; Moreover, one of the fields in these records is of type $\uparrow t$. Through this field, records are concatenated into a list - each element contains a pointer to the next element of the list. In the last entry of the list, this field contains the nil pointer.

*)new in English - “new”.

⟦folio 55⟧

Fig. 3.
Warehouse
new
105 48
112 55
893 11 nil

Fig. 4.
new
changeover
after
105 48
112 55
893 11 nil

Fig. 5.
new
changeover
after
105 48
112 55
200 13
nil

Fig. 6.
new
changeover
after
105 48
112 55
893 11 nil

nil
after
new
200 13

Fig. 7.
changeover
after
105 48
112 55
893 11
900 13 nil

nil
after
new
Fig. 8.
105 48
112 55
893 11
900 13 nil

Fig. 9

55

⟦folio 56⟧

Fig. 10.

person = record firstnamelastname:
array [1..40] of char;
the following: ↑ face
end;
item = record address, organization:
array [1..30] of char;
student: ↑ face;
the following: ↑ point
end;

In the variable description section we will now place a description
structure: ↑ point;

We see that in each entry of the item type there are two pointers - the ↑ item type for connecting to the next item and the ↑ person type for connecting a list of persons assigned to this item.

The following operators will print the first and last names of all students with an indication of the advisor-

each individual point (the points variable is of type ↑ point, the persons variable is of type ↑ person):
points: = structure;
while items <> nil do
begin persons: = points ↑. students;
while persons <> nil do
begin
writeln (persons ↑. first name, last name,
points ↑ address, points ↑
organization);
faces: = faces ↑. following
end;
points: = points ↑. following
end;

Task 19.4. Write a program that determines how many students should apply for constructions at the address indicated first in the list of construction items.

A. Rahr

Moscow Textile Institute
them. A. N. Kosygina
(For the beginning, see p. 51)

3. At what altitude above the surface of the Earth will the strength of the body be half as strong as on the surface of the Earth?
4. A body of mass m=0.5 kg is placed in water at a depth of h=2 m. How long does it take for the body to float to the surface? Density of body matter q_T=0.7 g/cm³. Density of water q_B=1 g/cm³.
5. Two identical ice meteorites fly towards each other at equal speeds and turn into steam as they move away. What should be the minimum speed of meteorites if their temperature before collision is t=-20°C? The specific heats of ice and water are c_π=2100 J/(kg·K) and c_B=4190 J/(kg·K), respectively. Specific heat of vaporization of water r=23·10⁵ J/kg. Specific heat of melting of ice λ=3.35·10⁵ J/kg.
6. In a closed vessel there is a gas under pressure p=5·10⁵ Pa. What pressure is established in the vessel if, after opening the tap, 4/5 of the mass of gas leaves the vessel? The process can be considered manufacturing.
7. Balls with radii r₁=15 cm and r₂=10 cm are charged to potentials φ₁=20 kV and φ₂=40 kV, respectively. What will the potential be after the balls touch? What charge will transfer from one ball to another? Consider the case where the balls are charged with the same charge.
8. Two parallel-connected conductors are connected to the terminals of a current source with an internal resistance of r=10 Ohms, the resistances of which are R₁=10 Ohms and R₂=2 Ohms. Determine the ratio of currents flowing through the first conductor before and after an open circuit in the second conductor.
9. There is a sheet of paper on the table. A ray of light falling on paper at an angle α=45° produces a bright spot on it. How much will this spot shift if a glass plate of thickness d=2 cm is placed on the paper? Refractive index of the stack n=1.5.
10. At what distance in front of a diverging lens with optical power D = -2 dtr should an object be placed so that its minimum image appears at the middle of the distance between the lens and its minimum focus?

The publication was prepared
M. Boris, I. Turchin
