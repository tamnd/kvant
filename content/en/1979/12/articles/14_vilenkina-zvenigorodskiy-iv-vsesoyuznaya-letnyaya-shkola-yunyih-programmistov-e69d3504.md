---
id: 1979-12-vilenkina-zvenigorodskiy-iv-vsesoyuznaya-letnyaya-shkola-yunyih-programmistov-e69d3504
issue: kvant_1979_12
year: 1979
number: "12"
title: IV All-Union Summer School for Young Programmers
authors:
  - Виленкина Л.
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 39
page_last: 46
page_labels: 37-44
tag: 7IH2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 967b198e79fa928c2c4300596559e4a654b151a845f91cb8e7eaa8c1985fa812
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/14_vilenkina-zvenigorodskiy-iv-vsesoyuznaya-letnyaya-shkola-yunyih-programmistov-e69d3504.md
source_content_sha256: a8b68e79f43d5e3258db4bcb2f3f99adca19cf02fe04cc269db5521531fa3a18
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

IV All-out summer school for young programmers

This article describes in detail the work of the school for young programmers, which took place in July - August in the Novosibirsk academic town. Our readers learned what problems modern programs can sometimes solve. Students of our Correspondence School of Programming will be ordered to master the Robik language and prepare for learning the Rapier language, which they will learn in «Kvant», 1980, No. 1.

From July 26 to August 10, 1979, the IV All-Russian Summer School for Young Programs was held in the Novosibirsk Academic Town, in which more than 120 schoolchildren took part. Among them were representatives of Kharkov and Nakhodka,iche

va and Angarsk, Leningrad and Moscow and many other cities of our country.

The grand opening of the School took place in the Small Hall of the House of Scientists of the Siberian Branch of the USSR Academy of Sciences, where scientific meetings, symposums and conferences are often held. The participants of the School were addressed by the representative of the Scientific Council on Educational Problems at the Predidum of the USSR Academy of Sciences, the rector of Novosibirsk University, Academician V. A. Koptyug, the head of the information department of the Computing Center of the USSR Academy of Sciences, the scientific director of the Summer School, corresponding member of the USSR Academy of Sciences A. P. Ershov and other scientists.

At lectures and seminars held at Novosibirsk University, schoolchildren became acquainted with modern languages ​​and programming systems (Rapier, Pascal, Settle, Poplan), with the Shpat computer graphics system, which allows executing various figure circuits on a computer

⟦folio 38⟧

drawings, making slides, making animated films. Young programmers were told about various methods and techniques of programming, they learned how to use computers to solve a wide variety of problems, work on various external devices, and use the Crab and Chameleon archiving systems.

Please, the practical classes were interesting: for several days, schoolchildren had the opportunity to work at the Computing Center of the Siberian Branch of the USSR Academy of Sciences - one of the best computing centers in the country, equipped with the most modern technology.

During the work of the School, two conferences were held at which schoolchildren talked about their work and learned about the results of the work of their comrades. Most of the works presented at the conference were carried out on orders from industrial enterprises, research institutes, and educational institutions. Such works have not only educational, but also more practical significance. The results of some of them were published in the scientific literature or recommended for publication based on the results of the School.

We will talk about some of the works that received first, second and third degree diplomas in this article.

How to teach a computer language?

At the Novosibirsk School of Young Programmers, as well as at the Correspondence School of Programming «Kvant», students using the main educational language Robik are able to study more complex programming languages ​​that have great capabilities and allow solving not only educational, but also practical, important applied problems. However, one of these languages ​​- the educational and production language Rapier - will be described in the upcoming lessons of the Correspondence School of Programming.

The task of Anatomy Veliko (Novosibirsk, 8th grade) is to teach this language to the BESM-6 computer. The program he compiled translates all Rapra constructions into the constructions of the Poplan language, which the BESM-6 machine understands. Please, the most difficult part of the work will be organizing the memory work.

During the Correspondence School lessons we already talked about how to work with memory in the Robik language. The assignment instructions available in this language allow you to write one number or one line of text to a memory block. In order to remember a table or list of numbers (for example, pages of a school journal with grades) in the computer memory, in Robik you need to allocate a separate block of memory for each cell of the table and come up with a new name for this block.

It is clear that it would be much more convenient to place the entire table in the same memory block. However, to work with a table stored in such a block, you need to be able to fill and read its individual cells, that is, work not only with the memory block as a whole, but also with its individual parts.

Most programming languages ​​provide the ability to work with tables, each cell of which contains a number. But multi-characteristics need to store different objects (numbers, texts, tables, etc.) alternately in one memory block. For example, information about each chemical element in the periodic table contains the element's atomic number (number), name (text line), designation (text line), and atomic weight (number) (Fig. 1). A finite set of volumes

⟦folio 39⟧

Objects arranged in a certain order are called a tuple in mathematics. For example, the image on figure can be represented by a cell of the periodic table with the following tuple:

"2, 'Helium', 'He', 4.00260"

To read an individual element of a tuple into memory, you need to name the block name and indicate the serial number of the desired element. For example, if the tuple shown here is stored in memory under the name A, then its first element (the number 2) denotes A[1], and the entry A[3] denotes the third element of the tuple, that is, the text 'Not'.

One tuple can be an element of another tuple. For example, if it is convenient to write the periodic table into one block of memory in the form of a large tuple, each element of which is a small tuple. describing a single cell:

"1, 'Hydrogen', 'H', 1.0079",
"2, 'Helium', 'He', 4.0026",...

In machine memory it is also necessary to store unordered sets of objects, that is, simply sets. The procedures for working with memory, developed by Anatoly Velichko when implementing the Rapier language, allow not only writing sets and tuples in computer memory and selecting individual elements from them, but also performing various mathematical operations on them, for example, finding the circled and intersection of a set, etc.

Yuri Shirman (Kharkov, 8th grade) solved a more specific problem: how to free a memory block if the information stored in it is no longer needed. Having this opportunity is very important. Quite often it happens that the entire memory of a machine is full and new information cannot be stored, although some of the old information is no longer needed and can be erased. In some languages ​​and systems this is quite easy to do, but in the EU DOS system, with which the Kharkov schoolchildren worked, this possibility is not provided. Yuri wrote a series of processors in the PL-1 language that allow the programmer to request a memory block of the required size at any time or free a occupied block.

Seventh-grader Natalya Glazoleva (Novosibirsk) was working on improving the Poplan language, one of the most common interactive programming languages. A significant drawback of this language is that the text of the procedure recorded in the computer’s memory cannot be checked or corrected: if an error is detected in the process, then all the procedures required to be filled in are reserved. The program developed by Natasha allows you to change and correct the text of procedures in much the same way as is done in Robik.

Belchonok leads Japanese

Interactive information systems provide great assistance to specialists in various branches of knowledge, allowing them to quickly find and analyze the necessary information. When developing such systems, it is important to store information in a form convenient for machines, and the general (dialogue) with the organization machine in a form convenient for humans. As a rule, these systems serve special systems and must be designed so that they are understandable to such a specialist. For example, a chemist may ask “What is the atomic weight?”, but the formulation “Name the four elements of such and such a tuple” will clearly not suit him - after all, he is not obliged to remember in which block and under what number the information he is interested in is stored. We discussed three information systems presented at the conference.

Undoubtedly, the dialogue system for analyzing the structure of protein compounds “Belchonok” aroused the most interest.

As you know, proteins consist of amino acids connected in chains, sometimes very long (from several tens to several thousand).

⟦folio 40⟧

There are only a few different amino acids - about twenty. The compositions of many proteins are known: they are listed in special catalogs in the form of amino acid tuples.

The task of the “Belchonok” system is to find out which proteins it could be part of by detecting a “snip” of a protein chain in the experimental bread. Of course, this can be done “manually” - going through all the right-hand pages and catalogs - but it will take a lot of time, and, most importantly, there is always a danger that something is missed.

By order of the Institute of Organization, chemists of the Siberian Branch of the Academy of Sciences, Novosibirsk eighth-graders Tatyana Vayshtein and Anamoly Veliko developed the Belchonok system, which performs this work much faster and with high quality. If earlier it sometimes took several days, now the machine is on the bottom and finds the necessary information in a few seconds.

The necessary information about proteins is constantly stored in the computer memory: protein structure, name, physical and chemical properties and a link to the literature in which it is described in detail.

Each amino acid is designated by a letter of the Latin alphabet, for example A - alanine, V - valine, etc.; the structure of each is presented as a sequence of letters, that is, as a line of text.

Under the influence of certain chemical reagents (enzymes) molecular model

Fig. 2.

*) Next, the machine prints all proteins containing the AV configuration and its position, according to the same scheme.

⟦folio 41⟧

I AM WAITING FOR YOUR INSTRUCTIONS
- SIGN
— WHAT PROTEIN ARE YOU INTERESTED IN?
— B1
— BREAKING SIGN?
— 1
— AV, VAA, AVA, VV
I AM WAITING FOR YOUR INSTRUCTIONS
- REFERENCE
— WHAT PROTEIN ARE YOU INTERESTED IN?
— B1
— WHAT ARE YOU INTERESTED: STRUCTURE, LITERATURE OR COMMENTARY?
— LITERATURE
— MAGAZINE QUANT No. 12
1979
I AM WAITING FOR YOUR INSTRUCTIONS
- END
— THE LITTLE SQUIRREL SYSTEM HAS FINISHED WORK, BYE!

Two other information systems were presented at the conference by Kharkov schoolchildren. Six-year-old Natalya Volfovskaya developed a program for working with scientific literature in libraries. The program allows you to quickly obtain a list of books and articles related to a given topic.

And the “Index” program, developed by Alexey Karnozhchiky and Igor Rosenberr (8-9 grades), is intended for obtaining information about almost all indexes. An interesting feature of the program is that it can be used from any home phone: just dial a number and the phone connects to the computer. After this, the machine is told the name of the desired city. It has to be encoded because the telephone dial is not very convenient for typing. You can, for example, type each letter together in alphabetical order, but this will take quite a lot of time.

A less time-consuming method was proposed: just dial the number of the first and last letters in the name of the city and the total number of letters in the name. In response to such a request, the computer turns on a tape from the place where the postal code of the desired city is recorded. This system was developed by order of the Kharkov post office.

Second grader teaches computer
A simple but beautiful program that allows you to simulate the simplest nuclear reactions on a computer,

⟦folio 42⟧

were developed by the most accomplished participants of the conference - second classicist Leonid Rabinovich and third classicist Sergei Gavrilenko from Novosibirsk.

It is known that in nuclear fusion reactions, the fusion of the nuclei of two atoms can produce the nucleus of a new chemical element. Its atomic number, that is, the number of protons in the nucleus, will be equal to the sum of the atomic numbers of the participants in the reaction of the elements. This is a simple rule and forms the basis of the program.

The periodic table is permanently stored in the computer's memory. The program interactively requests the designations and atomic weights of the participants in the reaction of nuclei, finds their atomic numbers from the table, calculates the atomic number of the element resulting from the reaction, and uses the same table to find its designation. Here is an example of dialogue from this program during the simulation of the gel synthesis reaction (Fig. 1):
— DESIGNATION OF THE FIRST ELEMENT?
— N
— ATOMIC WEIGHT?
— 1
— DESIGNATION OF THE SECOND ELEMENT?
— N
— ATOMIC WEIGHT?
— 3
— REACTION:
H+H=He
REACTION RESULT:
NAME - 'HELIUM',
DESIGNATION - 'Not',
ATOMIC WEIGHT – 4

After minor conditions, this program can be used in physics lessons when studying nuclear reactions and the structure of atoms.

Tyorig machine model

The program by Vitaly Tsikoba (Novosibirsk, 7th grade) is intended mainly for students studying the theory of algorithms and theoretical programming. In these disciplines, the concept of the so-called Tyorig machine is widely used - a universal logical device with a very simple command system.

In theoretical research, such a “machine” sometimes turns out to be more convenient than real computers. Vitaly prepared a program that simulates the operation of Tyorig machines on the BESM-6 computer. On the terminal screen you can see the entire “design” of the machine: a storage device in the form of a moving tape, a recording and reading head and a control device. Having compiled a program for machine computers, the student can watch on the screen the work of this program in all details (previously such programs had to be checked manually).

The computer creates cartoons

Please, the computer graphics section was of greatest interest to all participants and guests of the conference. Seventh-grader Asiya Salikhova (Novosibirsk) spoke about the structure of Shpar's educational graphic system, developed by him together with eighth-grader Natalya Sokolova, and about the features of working with this system in different programming languages ​​*).

The third classic, Anina Vaishtein (Novosibirsk), talked about how you can create a program using the Shpara and SMOG systems.

*) An article about the Shpara system, written by its developers, will be published in one of the upcoming issues of the magazine.

Fig. 3.

⟦folio 43⟧

We are for the production of animated films on a computer. After this report, the first cartoon in the USSR created by primary school students using a computer was shown. On figure 3 the screensaver of this cartoon is shown (a fish swims along the entire frame when shown) and two frames from the cartoon “The Rocket Neighs the Airplane”. Serdey Gavrilenko (3rd grade) and Voloda Fishelev (2nd grade) took part in compiling the program for individual frames of this film.

The work of Svetlana Uropina and Anna Filamova (Novosibirsk, 3-4th grade) was carried out by order of employees of the Institute of Chemical Kinetics and Combustion of the Siberian Branch of the USSR Academy of Sciences. The task was to build a series of graphs of fairly complex functions.

The students successfully completed the task, successfully using the basic constructs of various programming languages. For example, a coordinate grid, which should look the same on almost all graphs, was depicted using a separate procedure, within which several cyclic instructions were applied.

Functions, depending on two variables, were depicted in two ways for greater load: firstly, using an axonometric projection (Fig. 4), secondly, using a marking system that allows you to depict several graphs on one figure, each of which is marked with a special icon (marker) - figure 5. For the two most complex functions, cartoons were created showing how the graph changes with weakening of the magnetic field.

⟦folio 44⟧

In total, the girls compiled over forty procedures to construct eighty graphs.

Boris Slutsky (Novosibirsk, 7th grade) developed a program for depicting the spatial structure of protein molecules. The mutual arrangement of various amino acids in protein molecules plays a big role in biochemistry, and special people often need to visually represent the structure of a particular molecule. Boris not only “taught the machine” to draw individual molecules on paper (Fig. 6), but also developed a program for filming a cartoon showing how the molecule rotates.

The computer classifies
Much attention at the conference was paid to the problem of pattern recognition. The main difficulty of this problem is that the melting concepts of “close”, “similar”, etc. need to be made precise so that the corresponding problem can be formed and solved by machine.

The program by Mikhail Dun and Andrey Kaedal (Kharkov, 7th grade) groups parts into technologically similar groups. Each part has a so-called technological map, which describes how to perform each of the processing operations. If you numerate the ways of performing an operation, then together with the cards you can write a “technological number”, in which each digit tells how to perform the corresponding operation. For example:
1 - process with cutter No. 1;
2 - process with cutter No. 2;
1 — show in blue,
2 - show in gray.
Then 11 means that the part needs to be processed with cutter No. 1 and shown in blue. The task is to select technologically similar parts, that is, parts for which some processing operations are the same. The program allows you to solve this problem by selecting parts whose technological numbers have the same numbers in certain positions.

A more complex problem was solved by Galina Schwartz and Anna Besprozvannaya (Moscow, 9th grade). They developed a program that classifies objects in multidimensional spaces.

The general formulation of the problem is as follows. Each of the $n$ objects has $k$ attributes, the value of each attribute is a number (for example: the objects are various factories, and the attributes are the economic indicators of their work). Then each object can be imagined as a point in a multidimensional space: the values ​​of the features will be the coordinates of this point. In this case, points can be considered close if the distances between them are not too large. The program compiled by the Moscow Schoolgirls allows you to divide a given set of points into several groups of points that are close to each other, and the number of such groups is specified in advance. The program is intended for use in industrial economics when dividing the subject into groups according to size, volume and range of products.

Andrey Tarmakovsky (Kharkov, 8th grade) has developed a program that finds with the help of which affine transformation one drawing can be translated into another. This program is used by psychologists in the study of critical function.

Dmitry Gershun (Moscow, 9th grade) wrote a program that calculated the number of different voting systems. He managed to organize the operation of the machine in such a way that the search for $2^{15}$ options would happen in less than a minute.
