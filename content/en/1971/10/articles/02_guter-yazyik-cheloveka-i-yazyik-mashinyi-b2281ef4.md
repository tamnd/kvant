---
id: 1971-10-guter-yazyik-cheloveka-i-yazyik-mashinyi-b2281ef4
issue: kvant_1971_10
year: 1971
number: "10"
title: The language of man and the language of machine
authors:
  - Гутер Р. С.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2, 4
tag: LDO3
lang: en
source: kvant_digital
extraction: vision
content_sha256: d4c27c73b66251f5c0b022394ff5354edfd83e078c0f720d20f358ea09e50def
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/02_guter-yazyik-cheloveka-i-yazyik-mashinyi-b2281ef4.md
source_content_sha256: dac18384c3a287fc9691be1f7ac8a1b2d4cdd061ca7d54f2fdf7aa6b9fc31515
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

binary bits, that is, it can contain a set of zeros and ones, the so-called machine word.

The arithmetic device of machines can perform a certain set of elements of operations. The algorithm for solving any problem must be written in the form of a sequence of such elements of operations, which are called programm. The program consists of separate commands, each of which contains information about one elementary operation.

The command (represented as a machine word) is divided into two parts: operational and address. The operational part of the command contains information about the nature of the operation being performed (add, multiply, etc.): the elementary operations of the machines are renumbered and the number of the required operation is written in the bits of the machine memory cell allocated for the operational part. This number is called the operation code (we will simply say code).

The address part of the command contains the addresses of the cells whose contents are involved in the operation. The number of addresses in a command may vary for different machines. We will limit ourselves to considering three-address machines, in the address part of which the addresses of three memory cells are indicated: the first, second and third addresses of the command. For an arithmetic operation (for example, addition), the numbers of cells containing the original numbers (addends) are written in the first and second addresses. The third address indicates the cell number where the result (that is, the amount) should be written. For other elements of operations, the address used may be different (in part, one, two or even all three addresses may turn out to be unnecessary for any command, then the corresponding address cells will be simply filled with zeros).

Let, for example, a system command (a set of elements of operations) of machines contain $64=2^6$ elementary operations.

ny operations. Then six double digits are enough to number them, that is, the operation code can be written in the machine memory as a six-digit double number. It is usually more convenient for the programmer to break this number into two “triads”, each of which is then written with one digit in the octal $(2^3=8)$ number system, thus obtaining a two-digit octal number. If, for example, $N=4096=2^{12}$, then in such a “binary-octal” system, to write any address you will need not a twelve-row, but only a four-row, easier to write and read number.

If, say, code 01 means addition and 04 means division, then the machine word

01 1254 3172 6314

means the command: add the numbers written in cells with addresses 1254 and 3172, and write the sum in cell with address 6314. Similarly, the word

04 4365 2710 5024

it is instructed to divide the number from cell 4365 by the number from cell 2710 and place the part in cell 5024.

The address of the cell from which the control device must extract the next command for execution is recorded in a special counter of commands that are part of the control device. If a certain address I is recorded in the counter, then they say that “the control is in cell I.” When a command corresponding to an arithmetic operation is executed, one is automatically added to the contents of the program counter, so that control is transferred to the cell with the next address. Therefore, if we want the machine to perform any sequence of arithmetic operations, it is necessary to place the corresponding instruction in memory cells in a row.

Let's write, for example, a program to calculate the value

$$y = \frac{a+bx}{ax+b}.$$

⟦folio 4⟧

numbers from cells $a$ and $R_1$ and write the sum in cell $R_1$), which, of course, should not be understood as “equality” $a=0$. By the way, often instead of the = sign, they write something like →; but we will use the arrows for other purposes.

As already mentioned, executing an arithmetic instruction automatically transfers control to the next cell, adding one to the program counter. But very often it is not possible to arrange all the necessary commands “in one column”. Thus, when solving a quadratic control $ax^2+bx+c=0$, depending on the sign of the discriminant $D=b^2-4ac$, it is necessary to calculate either real or minimal roots, which is done, as is known, in different ways.

To change the order of command execution, among the elements of machine operations, special control commands are provided (more precisely, control transfers), which do not perform operations on the contents of memory cells, but change the contents of the program counter.

The simplest command of this type is the unconditional transfer of control command, which always transfers control to the memory cell specified in it. When it is executed, the contents of the program counter are cleared and the address specified in the command is written to it, so that the next command will be called by the control device from the specified cell.

Since for this it is enough to comma one address in the command, and the other two addresses will remain free, they can be used by forcing the machine to perform some other action when executing the same command. Typically, control transfer is accomplished by transferring the contents of one memory cell to another. Assuming, for example, that the third address of the control transfer command is counted in the program counter, you can write it in the meaningful notation cell like this:

$$a \rightarrow b, c$$

(“send the contents of cell $a$ to cell $b$ and transfer control to cell $c$”).

The control transfer condition commands are more complex; they transfer control only when certain acceleration conditions are met. This is also what commands require when programming branching processes. Let's look at one of these commands:

$$a < b, c.$$

When it is executed, the numbers written in memory cells $a$ and $b$ are compared. If the inequality written in the command is true, then control is transferred to cell $c$, that is, instead of the contents of the program counter, the third address of the command is written to it (as with unconditional transfer of control). If $a \geq b$, then one is added to the contents of the counter, as in arithmetic operations.

Using the described commands, you can already request a solution to some non-computational problems. Suppose, for example, that cells $x_1$ and $x_2$ contain non-toric numbers, from which you need to select the larger one and write it in cell $x$. This can be done using the following program:

1) $x_1 < x_2$, 3,
2) $x_1 \rightarrow x$, 4,
3) $0 + x_2 = x,$
4) $cmon$

Its first command is a conditional transfer of control: if $x_2$ is greater than $x_1$, then control will be transferred to command 3). This is an arithmetic command that will result in the number $x_2$ being written in cell $x$. (Often the number 0 was encountered; it turned out to be convenient to “assign” to the cell numbered 0, which is done in almost all machines.) Then control is transferred to the next cell 4), which contains the command $cmon$.

If $x_1 \geq x_2$, then the command 1) transfers control to the next cell 2), where the unconditional control transfer command is located, sending more than the number $x_1$ to cell $x$ and transferring control immediately to $cmon$.

Instead of specifying the number or condition of the command that is transferring control, it is often just an arrow to the desired command. Here's what, for example, a similar program looks like, from which
