---
id: 1981-3-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-5a62a801
issue: kvant_1981_3
year: 1981
number: "3"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: UZ8P
lang: en
source: kvant_digital
extraction: vision
content_sha256: 29fb7f9d515ac99b3e7cf484e8f7cdbfaa5a264a4284acb70bd8d46661746f8a
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/18_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-5a62a801.md
source_content_sha256: 208803e39e6d84b143ebbd2c9e778e1089340a4dd8a1269de283ca5b97121e1e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

Correspondence School of Programming
Lesson 14: Working with graphs

The pages of «Kvant» have published many articles on graphs and related mathematical problems in recent years. Almost every article said that computers were widely used to solve such problems. Today we are talking about how to work with graphs on a computer using the capabilities of the Rapier language.
ZShP students who are not familiar with the basic definitions of graph theory can read them in the article by V. Evstigneev on p. 18 of this issue*).

*) To complete the tasks of the 14th lesson, there is no need to read the entire specified article: you only need the basic definitions given at the beginning. However, we strongly advise the student of the SLP to read and analyze the article in detail in a loop.

Discovered graphs

The structure of a wide variety of systems from which things come into practice can be described using graphs. Very often there are problems in which it is necessary to take into account not only the presence of connections between elements of the system, but also the properties of these connections, as well as the properties of the elements themselves. To describe the conditions of such problems, it comes to “loading” graphs, that is, assigning some numbers, texts or other objects to their edges or vertices (and sometimes both). For example, if the road system of the Shpagovsky village council (Fig. 1, a) needs to be represented in the form of a graph and does not require information about the length of each road, then the result will be a graph with loaded edges (Fig. 1, b).

Task 14.1. Draw in the form of a loaded graph a diagram of the avain lines between the capitals of the constitutive resources of the USSR, indicating the distances.

Graphs in computer memory

If, in the course of solving a problem, you need to write several sets in the computer memory and perform general mathematical operations on them,

to the city Videoton
village Robik
village Malaya Bzsmovka
village Quantum
Terminal rose
With. Big Shpadi
village Cool Juices
r. Information flow

Fig. 1.

⟦folio 58⟧

Fig. 2.

Ratsini, then in the Rapier language you will be able to do this without difficulty. But there are no special tools for working with graphs in Rapier, so you need to come up with a way to describe a graph in this programming language yourself.

Let's see what a machine must remember in order to know everything about a directed graph that is needed to solve problems. First, it must remember many vertices. To do this, of course, you need to somehow designate each vertex, for example, number it, as in figure 2. Secondly, you need to remember where each arc begins and ends. Most often, an arc is described using a tuple made up of the designations of its starting and ending vertices. For example, in the same figure, the arc connecting vertices 1 and 5 can be described by the tuple 〈1,5〉.

Information about all arcs of a digraph can be stored in the form of a set composed of such tuples. Finally, a tuple composed of two described sets - a set of vertices and a set of arcs - is a complete description of a digraph on Rapier. For example, the digraph depicted in figure 2 could be described as follows:

«*1,2,3,4,5,6,7*»
«*1,3», «1,5», «1,4», «2,1»
«2,3», «3,5», «5,3», «5,6»
«5,7», «6,5», «6,6», «7,1*»〉.

Task 14.2. Draw a directed graph, the description of which on Rapier looks like this:

«*1,2,3,4,5,6*», «*1,4», «2,1»
«3,1», «3,2», «3,4», «3,5», «4,5»
«5,6», «6,2», «6,3*»〉.

If you need to describe a digraph with loaded arcs, then a third element appears in the tuples describing the arcs—the load value. Task 14.3. The BOOKOVKA graph is described on Rapier as follows:

«*1,2,3,4,5,6*»
«*1,2',T'», «2,3',P'», «2,5'K'», «3,5',A'»
«4,1',H'», «4,4',T'», «5,6',B'», «6,4',A'*»〉
->LETTERS;

The outline of each arc is text. By moving along any path in the graph and writing out the texts corresponding to the arcs in a row, you can get different words.

a) What text corresponds to the path passing through vertices 2,5,6,4,1,2?

b) In what way do you need to stand out to get the word VATA?

b) Is there a path in the graph along which one could obtain the words CANCER? The word GRASS?

In order to make it easier to enter information about a graph into the computer's memory, it is convenient to describe a function that will promptly request all the necessary information. For a directed graph with numbered vertices and arcs with a numerical load, this function might look like this:

PERCENT REQUEST = >GRAPH;
"**" -> VERTICAS; "**" -> ARCS;
PRINT('HOW MANY VERTICAES IN THE GRAPH?');
ENTER(1) ->NUMBER;1 ->NUMBER;
BYE NUMBER = <CHIVER::
VERTEKS + “*NUMBER*”
->VERTICS;
NUMBER +1 ->NUMBER
ALL;
'YES' ->CONTINUATION;
BYE CONTINUATION = 'YES'::
PRINT('NAME STARTING VERTEX');
ENTER(1) ->START;
PRINT('NAME END VERTIC');
ENTER(1) ->LOAD;
IF (START FROM TOP)
AND (CONVERT FROM TOP) TO ARC + “*START,CONVERT, LOAD*” ->ARC;
PRINT('ARE THERE ANY ARCS?');
ENTER(0) ->CONTINUE
