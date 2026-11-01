---
id: 1986-1-levinshteyn-simin-elementarnyie-logicheskie-operatsii-79356fa6
issue: kvant_1986_1
year: 1986
number: "1"
title: Elementary logical operations
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 47
page_labels: 44-45
tag: 9CMH
lang: en
source: kvant_digital
extraction: vision
content_sha256: a56e62e4fa3a2d0f30a1dc3f14aa5ee926db3f0cf4881ed0698cfb8ed42a82de
prompt_sha256: draft-1
translated_from: content/ru/1986/01/articles/16_levinshteyn-simin-elementarnyie-logicheskie-operatsii-79356fa6.md
source_content_sha256: 27329a3b25528a2101c04577e9da0e54fb60c6d263b0a475f501a00ee2da84d0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

v. Elementary logical operations

Doctor of Physical and Mathematical Sciences M. E. LEVINSHTEIN, Candidate of Physical and Mathematical Sciences G. S. SIMIN

In previous notes in this section (see «Kvant», 1985, No. 9-12) we examined the structure, principles of operation and methods of manufacturing transistors - the basis of modern computers. In order to understand how processive actions are carried out in a computer with the help of transistors, today we need to talk about elementary logical operations.

...You enter the vestibule of a modern 16-story building. In front of you are the doors of two elevators and a single button in the wall. You press it and from the light display above the door you see how one of the elevators begins to descend towards you. On the way, the cabin is abandoned - the noise of doors opening and closing is heard - someone entered the elevator. Cabina resumes driving. Finally, the elevator doors open. Someone comes out... All this is so inspiring that it practically does not hold attention.

Now imagine being an engineer who must design an electronic circuit that controls the movement of an elevator. This circuit should be able to solve many problems.

“If the cabins are not occupied and only one button is pressed, then the cabin that is closest to the given floor is assigned. If there are cabins on the same floor, go after the one that consumes less energy.”

“If there is a passenger in the cabin and he pressed the button for a given floor, and a button is also pressed on another floor, and the elevator goes not up, but down, and the second elevator is not occupied, or if there is also a passenger in the second elevator...”

Try to imagine the whole range of logical problems that can be posed to an electronic circuit with 16 floors and two elevators, and you will see that even such a simple “processor” must be able to cope with very difficult problems.

If you try to design such a processor, you will sooner or later be convinced of the following. When drawing up a logical circuit, it is convenient to forget for a while about the properties of the device that serves as the elemental base of your processor, and assume that you have at your disposal elementary logical cells - elementary circuits, the ability to implement the logical functions “AND”, “NOT”, “OR”.

The more complex the function of the processor that needs to be designed, the more effective this approach is. For a computer that must solve problems thousands of times more complex than an elevator control device, it is the only one that is justified.

Of course, it was not possible to completely forget about the properties of the database. Sooner or later, many questions arise, the solutions of which are determined precisely by the parameters of that particular element - electromagnetic relay, transistor, switch, etc. - on which the logical circuits are built. How to quickly compare logic cells? What power are they

The very first ideas for creating a programmable automatic digital computer were developed more than 150 years ago. They belong to the Anglican C. Babidge, a man of phenomenal ability, whose ideas were years ahead of their time. For 30 years, starting in 1812, Babyju worked on the manufacture of such a machine. The “elemental base” of Babage’s machine was “digital” wheels with different numbers of teeth. Parts of Babage's machine are kept in a science museum in London. (You can read more about Ch. Babidge in «Kvant», 1985, No. 10 in the article “The History of the Birth of the Computer.”)

⟦folio 45⟧

The basis of this algebra, which is now called “Boolean”, is any quantity that takes only two values: “yes” - “no”, “0” - “1”, “on” - “off”, etc.

A deep and fundamental relationship between Boolean algebra and the dual nature of key electrical elements was established by the famous American mathematician J. von Neumann. Neumann's ideas laid the foundations for homogeneous computers, consisting of a large number of identical elements of logical circuits operating on a dual principle. Neumann proved that using the “NOT”, “OR”, “AND” circuits, it is possible to create all the main components of a computer.

A major contribution to the algebraic theory of automata was made by the famous Soviet mathematician Academician V. M. Glishkov. He obtained important results in the theory of digital automata, in the field of computer technology applications, and in the development of new methods for constructing small computers.

Boolean algebra operations

Logical addition
$$C = A + B \quad (A \text{ и } B)$$

Logical multiplication
$$C = A \cdot B \quad (A \text{ и } B)$$

Logical negation
$$B = \bar{A} \quad (\text{не } A)$$

Corresponding logic circuits

A+B
"OR" circuit

A B
Scheme “I”

A
A
"NOT" scheme

Logical operations table.

consume? How much does a logic circuit cost? How reliably is it protected from interference? Etc.

But while you are designing the logic of the process, you don’t have to think about all these issues. A logical circuit built using logical cells such as “AND”, “OR”, “NOT” is universal; it does not depend on which elements the logical cells are implemented on.

What are logical cells?

These are electronic circuits, at the inputs and outputs of which the directions can take only two fully defined values. One of these values ​​is called logical zero, the second is called logical one. These two direction values ​​denote, respectively, $U^0$ and $U'$ (“0” and “1”).

Logic OR cells (logical addition circuits) have two or more inputs and one output. If at least one of the inputs receives a “1” signal, a “1” also appears at the output. The OR circuit symbol is shown in the first row of the logical operations table. The inputs of the circuit are designated by the letters $A$ and $B$. The output signal is designated $(A + B)$.

Logic AND cells (logical multiplication circuits) also have one output and two or more inputs. A “1” signal appears at the cell output if and only if “1” signals are also active at all cell inputs. If at least one of the inputs has a “0” signal, then the “0” signal is set to the output.

Logic NOT cells (also called inverters or logic negation circuits) have one input and one output. If a “1” signal is applied to the input, a “0” appears at the output, and conversely, if a “0” is applied to the input, the output is set to “1”.

The logical operations of addition, multiplication and negation are subject to certain rules established by the so-called algebra of logic or Boolean algebra.

By manipulating only the logical operations “AND”, “OR”, “NOT” (sometimes in very complex combinations), it turns out that it is possible to carry out any actions that allow the computer to make decisions, manage, process information, etc.

We will look at examples of the simplest logic circuits built on transistors in the next article in our section.
