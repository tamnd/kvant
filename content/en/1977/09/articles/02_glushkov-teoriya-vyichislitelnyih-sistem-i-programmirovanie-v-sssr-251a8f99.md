---
id: 1977-9-glushkov-teoriya-vyichislitelnyih-sistem-i-programmirovanie-v-sssr-251a8f99
issue: kvant_1977_9
year: 1977
number: "9"
title: Theory of computer systems and programming in the USSR
authors:
  - Глушков В. М.
rubric: raznoe
rubric_sub: Разное
page_first: 6
page_last: 11
page_labels: 4-9
tag: U8H7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 16532fff5f607c094c709df9b5b12ad5d559b6f30cb47b14ee7228031f51090e
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/02_glushkov-teoriya-vyichislitelnyih-sistem-i-programmirovanie-v-sssr-251a8f99.md
source_content_sha256: b211f30f484977189bc58301966c56f831ae86cef6cdc2cd34dda229676003f6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

This year our country will celebrate the 60th anniversary of the Great October Socialist Revolution. As the General Secretary of the CPSU Central Committee L.I. Brezhnev said, answering questions from the editor-in-chief of the Asahi newspaper S. Hata, “over the past 60 years, the Soviet people, under the leadership of the Communist Party, have walked a path that we are proud of for the first time. Within the lifetime of one generation there was, of course, centuries of backwardness. Our country has reached a high level of economic, scientific and technological development. If Russian trust accounts for only a little more than 4 percent of world industrial output, today the Soviet Union produces a fifth of it."

The new huge leap that our country is planning to make in the 10th Five-Year Plan requires further strengthening the pace of scientific and technological progress, rapid use of the achievements of the scientific and technological revolution to improve the quality and efficiency of work in all levels of the national economy. Modern electronic computing technology is one of the determining factors in the scientific and technological revolution, in the further progress of science, technology and production.

“The main directions of development of the national economy of the USSR for 1976-1980” provide for an increase in the production of computer equipment by 1.8 times, further development of the production of universal and control computer systems, and greater tasks for the further development of computer applications in scientific research, production and economics.

Computer technology itself, since the advent of the first electronic computer, is also in the process of rapid development. If the main function of first-generation machines is to implement a simple command system, then in modern machines devices must perform a whole range of new functions. Over the past five years, our industry has moved to the production of a unified system (EC) of third-generation computers. The transition to the EU computer radically changes the organization of the use of computer technology, including also elements of this organization, such as technical programming, data organization, organization of the computing process, the nature of user interaction with the computer, etc. The need for such a change in service is a completely definite and inevitable stage in the history of computers, namely, their transition from the category of obtaining scientific tools for solving particularly complex problems into the category of tools serving arrays (and very diverse) consumers.

Improving computers and methods of their use requires solving many specific problems of both fundamental and purely applied nature. The solution to some problems associated with the creation and use of computers is discussed in the article published below by the Chairman of the Scientific Council on Computer Science and Control Systems of the State Committee of the USSR Council of Ministers for Science and Technology and the Chairmanship of the USSR Academy of Sciences, Academician V. M. Glushkov.

The problem of automating complex calculations has attracted the attention of scientists for a long time. However, only about 30 years ago it first found a completely complete solution in connection with the creation of universal electronic computers - computers. We will consider the development of computing systems of this particular class, although in an earlier period of existence there were specialized computing devices, automated separate classes of computing processes.

The first Soviet computer (MESM) was created at the Academy of Sciences of the Ukrainian SSR in Kyiv under the leadership of academician S. A. Lebedev in 1951. During the creation of MESM, the basic principles on which the first American and British computers were built, the so-called von Neumann principles, were independently rediscovered.

⟦folio 5⟧

Firstly, this is the nationality of RAM, divided into identical cells. Each cell is designed to fill one machine word, which is an ordered set of double digits 0 and 1. Memory cells are equipped with addresses, which are consecutive non-negative integers 0, 1, ..., n - 1; the number of cells n is the amount of memory.

The next principle is the design of a special arithmetic unit (ALU), designed to perform simple operations on words, in particular, comparison operations with an integer to establish the coincidence or difference of two words. Another class of operations consists of arithmetic operations (addition, subtraction, multiplication and division) on words considered as numbers in the double number system.

In addition, there are information exchange operations (one machine word per exchange text) between the ALU and memory, as well as between the ALU and special input/output devices. An important factor under consideration is the simplicity and elementary nature of the system of machine operations.

Computational process control operations are associated with the third von Neumann principle - the command-and-address principle of management organization. A machine instruction consists of the opcode condition to be executed and the addresses of the operands (that is, the words on which the operation is performed and the result of that operation). For example, in the addition operation a + b = c there are 3 operands: a, b, c. If one or more operands are stored in predefined memory locations or in special storage locations called ALU resistors, then the addresses of the corresponding operands in the instruction may be omitted. There is also the possibility of storing in RAM not only the operands, but also the program of the computational process, represented in the form of a finite sequence of machine instructions written in double codes.

Program commands are usually located in sequential memory cells and are selected from it by a special control device (CU) sequentially one after another and used one at a time. However, this sequence of command execution can be disrupted by special jump commands, when the address of the next command is determined by the control command.

The fourth principle is the immutability of the communication structure between devices.

Along with the first computers, the problem of programming arose, that is, representing in the form of a sequence of machine commands certain computational processes or other processes for converting discrete information (sets of machine words).

Let's consider the programming problem for the simplest problem of finding the factoral n! given natural number n. To store the operands, we will need four memory cells, for which we will select cells with addresses 0, 1, 2, 3. For control, we will omit the program for entering the initial data and assume that by the time the program starts, the number n is stored in cell zero, and units are stored in the first, second and third cells. Then the program for calculating the factoral will be represented by the following program (numbers of the next message command); through (i) the contents of the cell with address i are indicated):

4. Compare(2) with(0) and, if “equal”, then by 8, otherwise by the next command.
5. Add (3) to (2), send the result to 2.
6. Multiply (2) by (1), send the result to 1.
7. Go to 4.
8. Stop.

The first command of the program (with address 4) is a so-called jump condition command, and the fourth (with address 7) is an unconditional jump command. Note that

⟦folio 6⟧

One jump command could have been saved, but for what follows, this notation is convenient for us. Representing each operation with double code:

comparison 001
addition 010
multiplication 011
transition 100
stop 101,

and the addresses of cells from 0 to 8 with the corresponding four-digit double codes, we write the program in encoded form (the ~ symbol indicates unused addresses):

001 0010 0000 1000
010 0011 0010 0010
011 0010 0001 0001
100 0100 ~ ~
101 ~ ~ ~

Note that the program will work correctly only when it is placed in the cells specified above (4th to 8th).

It is easy to understand that the described method of programming (in machine codes) is extremely cumbersome and tedious, due to which even experienced programs make many mistakes in somewhat complex programs. Errors are corrected in the process of debugging the program - a sequential (command by command) program for managing data sets (in this case, say, with n = 2 or n = 3), and controlling the operation of the machine.

The complexity of the control program task is aggravated by the beginning of various types of storage devices (3U) in computers: fast 3U relatively small exchange (internal) and slower 3U large exchange (external).

From 1951 to 1955, programs were executed in machine code. However, already during this period, research began on ways to manage the program by automating its various stages. An important step is the symbolic (alphabetic) addresses in the original program record, followed by the selection of specific numerical values ​​for these addresses by a special, one-time program. The structure of the mathematical formulation of the problem of minimizing the use of memory space has emerged. To solve them, special combinator methods were selected.

The introduction of symbolic addresses, together with the symbolic designation of machine operations, marked the emergence of the first programming languages ​​that were different from the machine code language and more convenient to use. Nevertheless, languages ​​of this class, which later received the name assembly languages, are machine-centered, since they use as elements of operators only those machine operations that are available in a particular machine.

An important factor in the development of programming was the introduction of the concept of subprograms and the introduction of an operator for accessing subprograms into assembly languages. The very inclusion of a subroutine in the main program was carried out in the process of translating the original recording of the program into the final (machine) representation using a special program, the so-called assembler.

A new step forward on the path of programming control was made as a result of the creation of process-oriented universal program languages ​​and corresponding translators. Such languages ​​are not tied to the specifics of program execution in specific machines; they widely use formulas of the algebra language. The first noted process-oriented language was the so-called address language, developed in 1955-1956 by V. S. Korolyuk and E. L. Yushenko. An important role in the development of programming theory was played by the operator language proposed by A. A. Lyapuny in 1954. A program in this language is represented as a finite sequence of operators $P_i$ and logical conditions $\alpha_j$, belonging to a given set of operators and conditions. Transitions resulting from checking logical conditions are indicated by arrows or special symbols. In the above pro-

⟦folio 7⟧

The calculation gram $n!$ involves the operators of addition $P_1$, multiplication $P_2$, stop $P_3$ and the logical condition $\alpha$ - the condition for the equality of the contents of the zero and second cells. The program in operator language will be written in the following form:

$$S = \prod_{i=1}^{n} P_1 P_2 \prod_{j=1}^{n} P_3.$$

The presence of a relatively simple form of writing a program raised the question of formal transformations of the program. Yu. I. Yanov, A. P. Ershov and other Soviet mathematicians contributed a lot and successfully to the development of the theory of such transformations.

An important step in the theory of computer systems was the emergence of the concept of a finite automaton in the early 50s. This device, which can be in only one of the states $a_i$, forming a finite set, can transition from one state to another under the influence of input signals $x_j$, which form a finite set, arriving at certain moments of time $t = 1, 2, \dots$, and can produce output signals $y_k$, which are functions of the pair $(a, x)$ of the state and the input signal.

Along with the apparatus of Boolean algebra, the theory of automata constituted a formal apparatus, with the help of which it became possible to formalize and subsequently automate a significant part of the work on designing computer systems. It turned out to be possible to represent any program (both machine and operator) in the form of a finite automaton.

In the 60s, there was further development of computing systems and programming. The idea of ​​increasing the level of machine language, expressed by the author back in 1958, found its way into the MIR-1 minicomputer (1965), and then in an even more advanced form in the MIR-2 machine (1969). In the MIR-2 machine, the internal language is especially rich. It allows you to operate not only with integers and decimal fractions, but also with common fractions, as well as with formulas using

⟦folio 8⟧

elementary functions (logarithm, snus, etc.) and operations of differentiation and integration.

Thanks to the richness of the internal language, the process of translating a program from the input language to the machine's practical output. A special polygonal control device provides quick interpretation of complex operators (for example, operators of analytical differentiation and interlining), thanks to which “MIR-2”, when performing formal transformations, is successfully compiled at the speed of working with much more powerful computers built according to the traditional Neumann scheme.

Increasing the level of machine language means effectively discovering von Neumann's second principle. After the MIR series machines, the American company Barrows followed this path, and in the 70s this direction became a generally accepted linear development of computing systems. Another direction, which received widespread development in the 60s, was the creation of special software systems (the so-called operating systems) for managing the computing process and managing programming in terms of the use of complex non-architectical memory systems.

Computers during this period evolved into complex computing systems integrating many different devices, including a variety of input/output devices and external memory devices. Organizes the effective coordination of the operation of all these devices by one of the most important programs of the operating system - the machine dispatcher. Each of the devices works at its own pace, while the dispatcher coordinates their work, organizes connections between devices and corresponding information exchanges. As a result, the possibility of multiprogramming has appeared, that is, the simultaneous loading of not just one, but many programs into the system and their parallel execution according to the dispatcher’s commands: while the central processor is counting one program, other programs can carry out input and output operations, search for information in external memory (which takes a particularly long time), etc.

Thus, it was possible to a certain extent to distinguish from von Neumann’s fourth principle - the immutability of the communication structure - due to the occurrence of operational disconnection and connection of various types of peripheral devices (input, output and external 3U). The programmer has the opportunity not to assign operations with peripheral devices to certain pieces of equipment: their selection and inclusion in the appropriate process is carried out by the operating system.

A special part of the operating system manages data. It not only places complex data systems in 3D of various types, but also searches for them and transfers them to RAM. In a number of operating system software systems, so-called virtual memory is organized. In this case, the programmer seems to have at his disposal each RAM equal to the sum of the power of all 3U of the system. The actual transfer of the necessary data and program blocks to actual RAM is carried out automatically.

Program and machine automation systems during this period included many input languages, so that it became possible to write individual blocks of the same program in different languages. The increasing international volume of the program has led to the need to create international universal process-oriented languages. The ALGOL-60 language received especially great attention. In modern automation systems, programs and machines widely accept other languages ​​(Fortran, PL-1, etc.).

Programmers who developed operating systems and programming automation systems are called general system programs, in contrast to programmers who developed applications.

⟦folio 9⟧

valuable programs in one or another specific subject area. If in the second case the main requirement is a good understanding of the program in the corresponding subject area, then in the first case the program is required to have a good command of all the secrets of programming skills and an understanding of the architecture of modern computing systems.

In the 60s, the USSR developed strong school system programs in Moscow, Novosibirsk, Kyiv and a number of other cities.

Although, in principle, many optimization problems for operating systems can be translated into precise mathematical formulations, modern mathematics, as a rule, cannot yet solve them. Therefore, when optimizing operating systems and the structure of computing systems, machine modeling methods are widely used. Special languages ​​oriented towards such modeling have been developed, for example, the language “SLANG” (1968), Nedis (1974), etc.

An important area of ​​programming since the second half of the 60s has been the creation of application software packages in various fields of application. A package is not just a mechanical combination of various programs, but also a set of special service programs that enable their use, that is, a small specialized operating system with a problem-oriented input language. The package for formal calculations allows formats in a human-readable form to be fed into the machine, for example: $x = \sqrt{5,26 + 7,32 \cdot 8,04}$, $y = \sin(\pi/16)$, etc.

In the theory of computer systems, the author in 1966 managed to find a new approach that made it possible to write programs in the form of a format in some special algebra algorithms. Unlike ordinary school algebra, in which the values ​​of variables belong to the domain of all real numbers, in algorithmic algebra there are two different subject areas. However, variables in Latin letters) are interpreted as operators mapping some given set $M$ into themselves. Other variables (denoted by Greek letters) are interpreted as logical conditions that take two values ​​on the set $M$: 0 and 1.

Both operators and conditions can be defined not on the entire set $M$, but on some part of it. The algebra of conditions (Boolean algebra) and the algebra of operators (semigroup) have been studied for a long time. The essence of the author's idea is the introduction of combined operations, in which both conditions and operators are involved. This is the following operation:

$$\alpha - \text{диизjonция} (P \vee Q),$$

$$\alpha - \text{итерация} \left\{ P \right\},$$

multiplication of conditions by the operator $P \cdot \alpha$.

Without going into a detailed definition of these operators, the program $S$ just discussed above can be written as a $\alpha$ iteration: $S = \left\{ P_1 P_2 \right\}$. It is proven that any program composed of operators $P_1, \dots, P_m$ and conditions $\alpha_1, \dots, \alpha_n$ can be written in the form of a formal algebra of algorithms with variables $P_1, \dots, P_m$ and $\alpha_1, \dots, \alpha_n$.

In the algebra of algorithms, as in ordinary school algebra, there are equivalent transformations of formulas, that is, transforming programs without changing the definition of its complex operator (transformation to a set of data). The use of such an algorithm allows in 1969-1973 to build an automated computer design system along with any program systems implemented on them, increasing labor productivity during design by 20-30 times.

In the 70s, the theory of programming and computing systems continued to develop at a rapid pace. Particularly great attention during this period was paid to the technology of compilation and methods of verifying legal
