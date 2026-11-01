---
id: 1985-10-ershov-algoritmicheskiy-yazyik-d36a5fb8
issue: kvant_1985_10
year: 1985
number: "10"
title: Algorithmic language
authors:
  - Ершов А. П.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 47
page_labels: 42, 43, 45
tag: DUUZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: d3105b69e4b13bb95322ceb2afd2c82d8bd8ea4080db42bb84e2ce0f03641aff
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/18_ershov-algoritmicheskiy-yazyik-d36a5fb8.md
source_content_sha256: 829c3f3b63f1d7194baff84e755ed8842b85752eefbd4d094271d1019e618094
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Algorithmic language

Academician A. P. ERSHOV

This article continues the conversation about the basic concepts of information sciences by the author in the previous issue «Kvant».
As before, you should pay attention to words typed in italics - these are informational terms. But short words printed in bold numbers are service words; they appear only in programs, performing certain functions in them that you should understand.

In the last article, we looked at several examples of algorithms. Now our goal is to learn how to write algorithms “according to all the rules of science.” But before you understand the rules for issuing an order, you should understand what orders can be used for. We will therefore begin by answering the following question:

What should the performer have?

1°. Count. The performer must not only quickly and accurately perform all four arithmetic operations, but also understand the order of their execution, “understand the parentheses,” and also find the numerical values ​​of the variables. For example, good use will almost immediately report that at $x=0,17$ and $y=1,32$ the expression $(x^2+3x)(y^3+5xy)/\sqrt{x^2+xy}$ is 3.66409... and will even quickly indicate that $\cos 0,29^\circ=0,99998719$... or $\sin(x^2+x)=0,003471$... at $x=0,17^\circ$. THERE ARE NO GREATER NUMBERS OR GREATER VOLUME OF COMPUTATIONS UNSTRAWS TO HIM.

2°. Remember. The performer can enter the data communicated to him into certain (known to him) places in his memory. Data can be either numeric or text (literal) values. In particular, he can enter some command or serial commands. If necessary, the contractor can destroy this data, replace or change it. In particular, variable numerical values ​​can be subject to repeated changes during the execution of the algorithm.

3°. Choose. The performer must be able to decide on his further actions depending on the situation. Namely, it checks whether some condition reported to it is satisfied, and if it is satisfied, it uses one serial command. This choice between two series of program commands is called command or branch conditions. Of course, the performer must also check it.

⟦folio 43⟧

4°. Repeat. The executor repeats (quickly and perhaps repeatedly) the same series of commands (loop) until a certain condition (loop condition) is met. He must check this condition before each execution of the series, and if he finds that it is violated, he must move on to the next one after the cycle of commands. A good performer - for example, a modern computer - is able to work in a cycle in this way at colossal speed.

5°. Recall. Among the texts recorded in the performer’s memory, there may be various data (numeric, literal), which he must be able to recall if necessary. In particular, auxiliary algorithms can be stored in memory. A good performer remembers (and executes) them one by one by completing their purpose (name), without requiring repetition of all the commands of the auxiliary algorithm. This example program is called a subroutine call.

6°. Seal. The performer prints (for example, with a pencil on paper, on a printing device or on a display screen) the solution to the problem (answer), that is, the results of executing the program, built educationally in the right places in his memory during the work process. (In other words, when working in interactive mode with the customer, the computer performer uses the print on the display not only at the end of the work, but also during the work in order to ask questions.)

Examples of writing algorithms

Below are examples of writing algorithms. These examples are performed in accordance with the rules of the algorithmic language adopted in your textbook. We propose to read them carefully and understand how they work, that is, to play the role of the executor of the algorithm (for the proposed initial data - the values ​​of the arguments). If this doesn’t work right away, you should look again at §§ 2-4 of your textbook, read the general notes below, and then return to executing the algorithms. A large detailed commentary is provided at the end of the article. After reading them, you will check whether you executed these algorithms correctly, and you will be ready to write simple programs in an algorithmic language.

In particular, you will be able to write algorithms that solve problems from the previous article in this section («Kvant» No. 9) in algorithmic language. In this type of participation (tasks about robots) are carried out on the next page, the rest will appear in one of the next issues «Kvant».

⟦folio 45⟧

General explanations

All of the above algorithm entries begin with a header (highlighted in blue). The title begins with the title or name of the algorithm (it is printed in capital letters after the service word algorithm)) and a list of parameters (the list of variable quantities is in parentheses after the name of the algorithm). Next (after the words of the arguments) these are the parameters that first need to be entered into the machine - it will fill them in). The header ends with a list of results (they are listed after the word res). We will assume that the machine will print their values ​​when the algorithm is used.

After the filling comes the body of the program. It starts with the service word "beginning", followed by all commands that end with the word "end".

Let's turn our attention first to those commands in which the machine counts. There are both very simple calculations (for example, added units) and more complex ones (skem (-b+\sqrt{d})/2a). These calculations are written in the most conventional way - the way you are taught in mathematics lessons. Therefore, this range of recording algorithms will not cause you any difficulties. However, it is worth paying attention to the assignment command (the := sign). The notation x:=a means that the machine assigns the value a to the parameter x (here a can be a number, a text, or another parameter). In this case, the machine will tell you that x equals a. If she now has to print x, then she will print not the letter x, but the number (text) a.

In the body of the program, for clarity, we have highlighted all branches and repetitions in color. The branches are shown here as separated by red arrows. The branch record begins with the service word if and ends with the service word all. After the word if there is a condition, then the service word then, followed by the first series of commands, then the service word value, and followed by the second series of commands. Let us recall that when branching, the machine checks the conditions, then executes either the first series of the command (if the conditions are met) or the second (otherwise). We can say that the machine selects the serial commands it needs. Having used it, the machine moves on to the next command.

Repetitions (or cycles) are highlighted here with yellow circles. Each cycle opens with the service word for now and ends with the word kts (end of cycle). After the word for now there are loop conditions, then a service word (the beginning of the loop), followed by a series of loop commands. Recall that when using a loop, the machine scurries around checking the conditions; if it is satisfied, the machine executes a series of loop commands and checks the conditions again; if it is fulfilled again, the machine scurries around checking the series and so on until the conditions are violated; then she moves on to the next command (after the word kts); if no conditions are violated, the machine will “work forever,” they say that it is in a loop. To avoid looping, you need to take care of exiting the loop, that is, to ensure that the conditions of the loop are violated.

The auxiliary algorithm (subroutine) is distinguished by its name, indicating a list of variables (in parentheses); specifies an argument and the result does not follow. The machine executes the subroutine and assigns the appropriate values ​​to the variables in its list. Therefore, it is important to correctly match the names of these variables with the names of variables from the main program.

When all the program commands are executed (before the final service word con), the machine prints in succession the received values ​​of those variables that appear in the header after the service word res (those variables that do not assign any values). Quotes representing the values ​​of literal variables are also not printed.
