---
id: 1981-10-sapich-chvanov-zadacha-dlya-issledovaniya-a84fada7
issue: kvant_1981_10
year: 1981
number: "10"
title: Research problem
authors:
  - Сапич В.
  - Чванов В. Г.
rubric: smes
page_first: 52
page_last: 57
page_labels: 50, 52, 53, 54, 55
tag: EAVY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 51963a958c2892663ea63862e7ee6b59b9c08c8a451c56bbc20cb8400e135e5a
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/16_sapich-chvanov-zadacha-dlya-issledovaniya-a84fada7.md
source_content_sha256: dc845b80cbbe4971f27d1fdb8e66e34436e7bcc6a9095d7a56dc43a1154540cb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

$$\varphi = \arcsin \frac{mg}{N} \sin \alpha.$$

Let us now find the radius of curvature of the point’s trajectory. As we have already said, in a fixed coordinate system, the speed of the point $\vec{v}$ is the sum of the velocities of its translational and rotational motion (see Fig. 4). According to the cosine theorem, the square of the velocity model is equal to
$$v^2 = v_0^2 + v_0^2 - 2v_0^2 \cos(180^\circ - \alpha) = 2v_0^2(1 + \cos \alpha).$$
The projection of the acceleration of a point onto the direction perpendicular to the velocity is equal to

Task
for research

Consider the following problem: The plane is tiled with congruent rectangles that do not have common internal points, and any of them can be combined with any other by moving the plane such that all other rectangles are combined. What is the number k of neighbors of each rectangle (that is, the number of rectangles that have at least one common point with the given one)? How many different types of such mosaics are there for each k?

Think about its solution and... its wording (the second question is formulated somewhat vaguely; before answering it, you need to clarify the meaning of the expression “different types”) and write to us. The most interesting answers will be published.

V. Sapich,
V. Chvanov

Tasks
our readers

1. From points A and B on a moline road, two automatic vehicles simultaneously start moving and move with the same constant acceleration $\vec{a}$. At some point C of the road there begins a section covered with an ice crust (where there is no trene). What is the distance from point B to point C if it is known that the first automatic vehicle, starting from point A, caught up with the second automatic vehicle after a time interval t after passing the first point C?

G. Levin

2. In which case do you think water will boil faster: if a glass with an electric boiler lowered into it is placed on a radiator or on a windowsill? It would seem - in the first one, since the air above the radiator is warmer than above the windowsill. However, it gives details. The effect of non-killing (about 10%), but reliable. What can cause it?

L. Ashkinzi

3. The remarkable Russian physicist P. N. Lebedev proved that light, when interacting with matter, exerts pressure on it. What mass can be controlled by a beamlaser with power N?

A. Royal

⟦folio 52⟧

efficient and can be used indefinitely. A Pascal program is written into the computer's memory in its entirety and only after that can it be used. Every Pascal program is a process called a main process. Like any processor, a Pascal program has a name, and its instructions are called operators.

The text of any Pascal program consists of several sections:

1. Program title
2. Tag description section
3. Constant description section
4. Data Type Description Section
5. Variable description section
6. Section describing functions and procedures
7. Operators section
The three sections in bold are required for any program. The beginning of the remaining sections in the program is optional. We will tell you about the purpose and rules for recording each section as we learn the language. Each section of the program begins with its own keyword. Sections are separated from each other by a semicolon (;). Key words are English. At the end of each lesson we will provide words - a list of key words that were first encountered in this lesson. We advise you to write down all the keywords (together with the translation) in a separate terdal. We will highlight keywords in bold*); When designing your works, they should be underlined with a straight line. For ease of reading, we will highlight names in programs in italics, and you should underline them with a wavy line.

Program title
Its syntax diagram looks like:

The name of the program and, in general, the name in Pascal can be anything.
*) Sometimes in printed publications they are highlighted in italics.

a sequence of letters and numbers starting with a letter. Names are distinguished by the first eight characters. The word output, indicated in the program header, tells the machine that the program is preset to print the result, and the word input indicates that some quantities will be assigned values ​​while using the program (this feature will be discussed below).

Operators section
The statements section is the main section of the program. Its syntax diagram looks like:

A section consists of a sequence of statements enclosed between the keywords begin and end, referred to hereafter as statement parentheses. Operators are separated from each other by a semicolon (;). At the end of the program there is a period (.). You can write any number of operators on one line.

Expressions
Pascal uses the following arithmetic symbols (the same as in Papir):
+ addition,
- subtraction,
* multiplication,
/ division.

The operation “exponentiation” is not provided in the language. But in Pascal there are two more arithmetic operations applied to integers:
div — integer division (the quotient of the division of two natural numbers is calculated),
mod — calculating the remainder of integer division*)
In this case, as usual, the presence of parentheses is taken into account. For example, what if

*) For example, 25 div 6=4, a 25 mod 6=1.

⟦folio 53⟧

When writing expressions in programming languages, you can only use parentheses to indicate the order of actions.

Assignment operator

The assignment operator is described by the following diagram:

For example, $x := 3$; reads: "name $x$ given value 3" (note that, compared to Rapier, the name and expression were swapped!).

Calculating the value of an expression
$$z = \frac{x^2 + y^2}{xy}$$ with $x = 3, y = 5$ can be accomplished using the following sequence of operators:
$$x := 3; y := 5;$$
$$z := (x*x + y*y) / (x*y);$$

Printing Procedures

For printing in Pascal there are two procedures `writeln*` and `write`. Each of them can have any number of parameters. As a result of using these procedures, the values ​​of all parameters will be printed on one line. The difference between these procedures is as follows: after executing procedure `writeln`, a transition to a new line occurs (as in the PRINT procedure in the Rapier language), and after executing procedure `write`, the transition to a new line does not occur and printing by subsequent printing procedures `writeln` or `write` will occur on the same line. When calling procedure `writeln` without parameters, a transition to a new line occurs, that is, now calling any of the print procedures will print from a new line.

For example, the result of executing a sequence of operators
$$a := 3; b := 6;$$
$$write ('A=', a, ' B=', b);$$
$$write (' BCE'); writeln;$$

will be the string $A = 3$ $B = 6$ $BCE$, and the result of the sequence of operators
$$a := 3; b := 6;$$
$$writeln ('A=', a, ' B=', b);$$
$$write (' BCE'); writeln;$$

will print two lines
$$A = 3 \quad B = 6$$
$$BCE$$

Note that in both examples there is a `writeln` at the end of the print sequence. This is not accidental: procedure `writeln` always completes the formation of the printed line and outputs it to the printing device. Without this procedure, in our example the last $BCE$ may turn out to be non-pretaate.

Data. Input procedures

As already noted, a Pascal program begins to execute only after it has been completely entered into the computer’s memory. But what if some names need to be assigned values ​​during program execution? In Rapier, a procedure `BVOД` was provided for this (see «Kvant», 1980, No. 7), with the help of which the required value could be set during the dialogue. In Pascal there may also be no dialogue. Therefore, it is necessary in advance, before the start of program execution, to “prepare” all the data (numbers, texts,...) that are necessary for its operation. But where to write this data and how will the machine know which names to assign certain values ​​to?

In most programming languages, including Pascal, data is written, as a rule, after the program in the so-called data list, and in the program itself a special operator is used, with the help of which the necessary data will be read and assigned to the necessary names.

In Pascal, procedures `BVOД` together apply procedures `read` and `readln*`. Each of them can have any number of parameters, which must be names. The mechanism of both

*) `writeln` is a “fusion” of two English words `write` and `line`.

*) `readln` is a “fusion” of two English words `read` and `line`.

⟦folio 54⟧

procedures is as follows: the first value specified in the data lists is “read” and assigned to the first name written in the procedure parameter list, then the next value will be “read” and assigned to the second name, etc., until all names have been assigned values. It is clear that the amount of data must correspond to the number of names specified when calling the input procedure (or at least not be less). Several calls of procedures `read` and `readln` can be recorded in one program. In this case, the data list must contain the data necessary for the successful operation of all input procedures.

The difference between the operation of procedures `read` and `readln` is as follows: after executing procedure `read` the value of the next given value is read from the same line, and after executing procedure `readln` - from a new line. (Compare with the operation of procedures `write` and `writeln!`) For example, if the program is written `read (a, b, c)`, and the data list consists of the numbers 5,7 and 13, then when using the program the addition will be performed: `a:=5; b:=7; c:=13`. Numeric data in the data list is separated from each other only by spaces. When preparing a program for entry into computer memory, the data list is separated from the main text of the program by writing a special line. We use a horizontal line to separate the list of data from the program text.

Let's look at an example. Suppose that three digits `a1, a2, a3`, which are consecutive digits of the decimal notation of a certain number, need to be entered into the machine memory, and a sequence of operators must be written to find and print this number.

**begin**
```pascal
read (a1, a2, a3);
x:=100*a1+10*a2+a3;
writeln ('X=', x)
end.
```

**507**

As a result of executing this sequence of operators, X=507 will be printed.

**Descriptions**

When studying the Robik language, we talked about the fact that each name used in the program is assigned a block of computer memory. This raises questions: when does this memory allocation occur? How much space should be allocated to store the values ​​of different names? How does the computer know what values ​​(for example, numbers or texts) a given name can take?

When writing a program in some programming languages ​​(for example, Robik or Rapier), the computer itself “answers” ​​these questions. To do this, she needs, for example, to look through the entire text of the program and track what values ​​each of the names can take and whether these values ​​change during program execution. This type of program analysis requires additional time and memory space.

In most programming languages, including Pascal, information about these and some other properties of a quantity is specified in special sections of the program, in its descriptions. All names used in the program must be listed in one of the description sections (see program structure on page 52).

 The quantities used in the program are divided into variables and constants. A value variable can take on any of a valid set of values ​​during program execution. You can use the value of a variable at the current moment in time by referring to it by name.

Constants are unchanging quantities. There are two categories of constant. One of them does not provide any additional description: the constant is defined by its image. For example, 5 is a numeric constant that, when used anywhere in a program, represents

⟦folio 55⟧

represents the number five; 'blue' is a text constant; Later we will get acquainted with constants of a different nature.

Another category of constants are the so-called named constants. Any constant can be given a name, and then in the program the use of this name will indicate access to the constant. If, for example, the values ​​3.1415926 are called by the name nu, then the programmer has the right to write

$$l := 2 * nu * r$$

where $l$ and $r$ are variables and $nu$ is a named constant. The correspondence between named constants and their names is established in the constant description section.

The constants description section can be described by a diagram:

![Diagram of a control system with inputs and outputs](image)

The most important property of names in Pascal is the concept of type. A type specifies some ordered set of values ​​and a set of permissible operations on these values.

The description of a scalar type is given by a diagram:

![Diagram of a control system with inputs and outputs](image)

The section describing data types itself can be specified by a diagram:

![Diagram of a control system with inputs and outputs](image)

Here const, type, var are the keywords of the sections describing constants, types and variables, respectively.

Now two questions arise: how to correctly set data types in the program and how conveniently can the data of each TOP be represented in the machine’s memory?

All data types can be divided into two large classes - scalar and structural. If the values ​​of variables of a given type are made up of individual components (as, for example, sets and tuples in Rapier), then this type is called structural, otherwise - scalar.

In this lesson we will only look at downloadable data types. The description of structural data types will be linked as follows.

For example, a section describing data types in a program might look like this:

$$\text{цвет} = (\text{красный, желтый, зеленый, голубой});$$

$$\text{физура} = (\text{треугольник, прямоугольник, круг});$$

Here red, circle,... are constants defined by their representation.

Let us now describe the variable x of the color type and the variable a of the physical type.

x: color; a: physical;

This means that the variable x can take one of the values ​​red, yellow, green, blue, and the variable a can take one of the values ​​triangle, rectangle, circle. Note that the type name can be omitted if we combine the variable description and the type definition, that is, we could describe the variables x and a like this:

x: (red, yellow, green, blue);
a: (triangle, rectangle, circle);

However, if there are several such descriptions (for example, in different procedures), then it is better to still describe the type and give it a name.

Types described in this way must not contain identical constants.

In addition to the types described in the program, there are standard τι-
