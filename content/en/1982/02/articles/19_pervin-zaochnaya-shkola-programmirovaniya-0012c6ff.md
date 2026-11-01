---
id: 1982-2-pervin-zaochnaya-shkola-programmirovaniya-0012c6ff
issue: kvant_1982_2
year: 1982
number: "2"
title: Correspondence School of Programming
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 55
page_labels: 48-53
tag: L620
lang: en
source: kvant_digital
extraction: vision
content_sha256: 48d7a238c50827062b3d999e4bfcff5ea1ebde4c0fa171c94b7ffade79f54829
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/19_pervin-zaochnaya-shkola-programmirovaniya-0012c6ff.md
source_content_sha256: 72eaa9ecc1670323d935947ee68d61bd2de8497fd8753bd829de453f07ff0da1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Correspondence School of Programming
Lesson 18: Files

What is a file?
A file is a small collection of elements of the same type, the number of which is not predetermined.

The file type is described by the following syntax diagram:

```
file of min
```

type is the general type of the file elements. We will call it basic. There is a standard (that is, existing for any program and not subject to description in it) file type called text. Its base type is char. Files of type text are called text files.

The elements of a file are considered to be arranged sequentially, that is, the same as the elements of a vector. A file differs from a vector, firstly, in that its size can change, and, secondly, in that the way of accessing its elements is completely different: it is impossible to access an arbitrary element of the file; its elements are viewed only in a row, from beginning to end, with only one element available each time. Each file f has an associated variable that denotes f↑; its type is the same as the base file type. It is called this file's buffer or buffer variable. The buffer can only hold one file element;

The value of this element serves as the buffer value. A buffer is like a window through which you can view a file, selecting elements one by one.

If the file is viewed to the end (or if it is completely empty), then we will consider it finished. If the file is finished, then the value of its buffer is undefined.

File handling procedures
You can check whether file f is finished by calling the standard logical function

eof(f)
It produces the value true if f is finished, and false otherwise*).

Let's say we need to look at file f. To do this, you must first call the standard procedure

reset(f)
(“reset” means “return”). As a result of its execution, the value of the buffer f↑ will become the first element of the file (if the file is not empty).

You can move from one file element to the next using standard procedure calls

get(f)
(“get” means “to take”). After its execution, f↑ will contain the value of this next element, if any. (If there is no next element, the file will become complete.) The get procedure cannot be applied to a file that has already been completed.

Let's look at an example. Let f1 and f2 be files with base type real, arovno and b be variables of type boolean. The variable equals needs to be set to true if the contents of f1 and f2 are the same (that is, these files have the same length, perhaps zero, and their corresponding elements are equal in pairs), and false otherwise.

*) eof is an abbreviation of the English words end of file.

⟦folio 49⟧

This task can be accomplished as follows:

```python
reset(f1); reset(f2); b:=true;
while b AND NOT eof(f1)
    AND NOT eof(f2)
do begin b:=f1↑=f2↑;
    get(f1); get(f2)
end;
if b then равно:=eof(f1)ANDeof(f2)
else равно:=false;
```

If both files are empty, then the body of the loop will not be executed even once and will receive the same value `true`. While the next elements of the file match in pairs, `b` receives the value `true` in the loop body and the loop operator continues working. The loop will stop if the next elements do not match or if one of the files is completed. In the first case, `b` has the value `false` upon exiting the loop, and the last statement will assign this value to the variable `равно`. If, upon exiting the loop, `b` has the value `true`, then this means that one of the files will coincide with the initial fragment of another file. In this case, the last statement checks whether the second file has also ended at the same time. If yes, then equal gets the value `true`, and if the other file is not yet finished, then false.

Let it now be known that the file `f1` contains at least 10 elements, and the first 10 of them need to be converted into an array `m`, the type of which is `array [1..10]` of `real`. This can be done as follows (i is a variable of type `integer`):

```python
reset(f1);
for i:=1 to 10 do
begin m[i]:=f1↑;get(f1) end;
```

The sequence of operators `v:=f↑; get(f)` (1) where `v` is a variable and `f` is a file is quite common. Therefore, in Pascal there is a standard procedure `read` such that calling `read(f,v)` is equivalent to the pale operators (1). Now our example can be rewritten shorter:

```python
reset(f1);
for i:=1 to 10 do read(f1, m[i]):
```

So, we have learned how to read from a file. Now let's see how to fill it out. There is a standard procedure `rewrite` (overwrite) such that after calling `rewrite(f)` the file `f` becomes empty and ready to be filled. To execute a file with the value of a certain expression `E`, you need to perform an assignment `f↑:=E`, and then call the standard procedure `put(f)` (“put” means “put”). This call will append the value `f↑;` to the end of the file, thus removing one element. Procedure `put` can only be used if the file is finished, and after calling it it continues to be finished: you cannot write new elements to the middle of the file. Pair of operators

```python
f↑:=E; put(f)
равносильна оператору
write(f, E)
```

where `write` is the standard procedure.

For example, you can fill the file `fi`, whose base type is `integer`, with integers from 1 to 100:

```python
rewrite(fi);
for i:=1 to 100 do write(fi, i)
```

Task 18.1. From two text files `x` and `y`, make one file `z` so that it contains first all the elements of file `x`, and then `y`.

What is especially special about text files is that using the procedure `write` you can fill them with values ​​not only of the base type `char`, but also other simple types, and using the procedure `read` you can send them to variables of any simple type. If, for example, the file `ft` is a text file, then `write(ft, 51)` will automatically convert the number 51 into a sequence of characters “5” and “1” and write them to the file `ft`. If, on the other hand, it is known that the next elements in the file `ft` are numbers, which can be preceded by spaces, then we can use the call `read(ft, i)`, where `i` is a variable of type `integer`. This call, skipping all the spaces preceding the first digit, will take all the digits in order until the next space is found, convert them into a number (for example, the sequence of digits “5” and “1” into the number 51) and assign this number to the variable `i`.

Task 18.2. It is known that the text file `f` contains real numbers separated by spaces. The end of this sequence is indicated by the number 0.

⟦folio 50⟧

then print the sum of the numbers in this sequence.

Files and I/O

It is easy to see that working with files is very similar to the I/O mechanism. We will now show what the connection is between them.

Calling a procedure
write (x)
with a simple type parameter, the value x is output to the printing device (see lesson 15). It is assumed that the standard text file output is associated with the printing device. Printing is nothing more than adding to this file, and write (x) is a shorthand for

write (output, x)
The device in turn was considered to be associated with a standard text file input, and
read (x)
There is an abbreviation for
read (input, x)
The input file cannot be replenished and the reset procedure cannot be applied to it. (This procedure seemed to have already checked at the beginning of the program execution). In the same way, reading and the rewrite procedure are not applicable to the output file. These two files do not need to be described in the program (that’s why they are standard), but, as you know from Lesson 15, they must be listed in the program header.

If a task requires some information to be stored in external memory, then additional external files are needed for this information. They must be described along with all other program variables and listed in the header along with input and output. If there is no file name in the header, then this file serves only to exchange information within the program.

Task 18.3. Some text is shown on the device. You need to place it in a text file f, placing a “/” after each “*” character.

Example for using external files

In the last lesson, we looked at examples that dealt with the description and processing of information about different countries of the world. These examples are simple illustrations of service tasks that deal with very large volumes of information. It is clear that this kind of information does not appear at the beginning of program execution and does not disappear at the end of it. On the contrary, it must be stored for a very long time, maybe for years: from time to time it is subject to changes and at any moment the necessary data can be changed from it. Information can also be stored in the external memory of the computer (on disks and tapes), and its reading and correction is carried out by special programs executed when there is a need for it.

Each such program considers information as the contents of some external file. Let in our case it be a file named arxiv. The elements of this file are records of type country. A custom processing program must work with the file. Its title looks like

program processing (input, output, arxiv);
the variable description section will contain a description
arxiv: file of
country;
In the last lesson, each record relating to a particular state was the value of a separate variable, the name of which coincided with the name of the corresponding state. It is clear that in practice it is inconvenient to describe and have one and a half hundred variables in a program. Therefore, now we will abandon the variables Australia, ..., Japan. The name of the country will be stored in the record itself; it contains another field of type array [1..60] of char (and assuming that sixty letters and spaces are enough for the name of any country in the world).

The description of the country type will now be like this:
country = record
name: array [1..60] of char;

⟦folio 51⟧

area, population: real;
device: boolean;
intro: date;
education: challenges end;
Let's say we need to find out which country has the most community. Let us describe the variables for this
name: array [1..60] of char;
area: real; i:integer;
and execute the following statements:
area:=0.0; reset(archive);
while NOT eof (archive) do
begin if arxiv↑.area>area
then begin
area:=arxiv↑.area
title:=arxiv↑.title
end;
get (archive)
end;
writeln(name, area);
Task 18.4. Begin the name of all countries with a population greater than 10 million.

Addendum to Lesson 18 A. Rahr
Sorting by text keys. Mergers

Sorting is an action that organizes a collection of data according to the values ​​of some characteristic. Thus, the elements of the ordered set are, to a certain extent, complex, multicomponent objects—of these structural types; As a rule, a feature is only one of the components of the elements being sorted. In the general literature on sorting methods, those characteristics, by the values ​​of which the ordered set of the sorted population is estimated, are more often called keys. Sorting becomes possible when an order relationship is established on a collection of key values.

Nibaulier states that the objects to which sorting is applied are collections of data of the same types. There are two types of such collections: arrays - collections of data with a known, fixed number of elements and files, the sizes of which, generally speaking, are unknown and can change during program execution. Accordingly, the ordering of arrays is carried out, as a rule, internally by sortings, applied only to data located in the computer's RAM, and for files, it is most often necessary to use external sortings, which can operate with data located on external storage devices - magnetic tapes, disks, peripherals.

The problem of organizing information comes up all the time. In the payroll sheet, its line elements can be ordered in ascending order of the tabular grade numbers. Here the keys are the table number, the order relation is the return of natural numbers. The final protocol performs a valid frequency control process based on the results shown to the competition participants. Here the keys are the real*) number of the result.

The list of schoolchildren of one class is also sorted. Here the last name keys are texts. Typically, texts are ordered like words in a dictionary - alphabetically, in an order called lexicographical: if the order of letters in the alphabet is fixed, then of the two key values k1 and k2 the sum is considered to be the one for which k1[1]→k2[1] in alphabetical order (the first letter of the first text represents the first letter of the second text), and if k1[1] = k2[1] is equal, then for which k1[2]→k2[2], etc. So, 'layer' → 'elephant', as in the dictionary.

The relative order of two letters or two words can thus be established and even indicated: the symbol “→” means “precedes.” However, for practical purposes - determining and establishing the lexicographic ordering of texts in a program written as an example in Pascal - it would be more useful to deal not with the relation “→”,

*) It is important to remember that real numbers are defined differently in programming and in mathematics. In the machine we will represent only numbers with a limited number of digits. Thus, “real” numbers, as programmers understand them, are fundamentally rational numbers.

⟦folio 52⟧

which cannot be implemented directly for texts in Pascal, but with the familiar relation “<”, which is well known from operations on numbers. For this purpose, a constant `alфавит` of type `array [1..64]` of `char` is stored in the machine’s memory. Its meaning is 'abv...i+ -...!'

Using this constant, each letter of the alphabet (and, more generally, each symbol) is associated with the number 1, the letter a with the number 2,..., the letter i with the number 34. The “highest” character is an exclamation point! — mapped to number 64. Note that space represents all characters in the alphabet.

Now the comparison of two characters is easy to implement, compare the numbers corresponding to them, if you have such a number function:

```javascript
function число(x:char):integer;
var i:integer;
begin
i:=1;
while i<=64 do
if x=alфавит[i]
then begin число:=i;
i:=65 end;
else i:=i+1
end
```

with the help of which, for example, the mentioned condition `κ1/2→κ2/2` can be reduced to the condition `число(κ1/2)<число(κ2/2)`

The function `число` was needed only because alphabetical ordering (1) turns out to be essential for us. If we are satisfied with the standard Pascal alphabet, which first lists the letters from `a` to `z`, then Russian letters that do not match them in style, then numbers and other symbols, then for the purpose of converting the letters `x` into a number equal to the number of this letter in the standard alphabet, we could use the standard Pascal function `ord(x)`.

Using relations of the form (2), one can determine the relative order of any two texts. For example, for ‘layer’ and ‘elephant’ you can perform a series of checks for the first letter `число('c')=число('c')` for the second letter `число('l')=число('l')` for the third letter `число('o')=число('o') но для четверых буквы имеет место `number('e')<number('n')`

from which it follows that ‘layer’ → ‘elephant’.

Such a series of checks can be performed for any two given texts using the function `сравнение` (x1, x2). This function produces the boolean value `true` if `x1→x2` or if the texts `x1` and `x2` are the same. If `x2→x1`, then the value generated by this function is `false`. Then, if in a program it is important to establish the truth of the condition `x1→x2`, then you can use the conditions `сравнения` (x1, x2) = `true` implemented in Pascal. If type `type` array =
`packed array [1...20] of char`
then the function `сравнение` is described as follows:

```javascript
function сравнение(x1,x2: массив):boolean;
var номер:integer;
begin
номер:=0
while номер<=20 do
begin
номер:=номер+1;
if число(x1|номер|)<>
    число(x2|номер|)
then сравнение:=true
else сравнение:=false
номер:=21
end
else if номер>20
then сравнение:=true
end
end;
```

As described here, function `сравнение` operates on the twenty-character word arrays `x1` and `x2`. The word length is chosen to allow this function to be used for last name comparisons: it is one of the most commonly used keywords in many sorting applications. The 20-liter limit can always be replaced, if desired, by a stronger or, conversely, weaker restriction. Of course, long comparative procedures that send each of the comparative array words to an array made up of 20 spaces. It is the result of this procedure, which, apparently, will not be difficult for the reader to describe, and serves as the actual parameter when accessing the function `сравнение` (x1, x2). Otherwise, such a preliminary procedure will not be necessary if the user of the program working with the function `сравнение` writes the key values ​​so that they occupy 20 characters, of which the latter are mostly random spaces. And one more note about the description of function `сравнение`: the parameter arrays of this function are of type `packed array` (packed array), not type `array`. Type `packed array` is used for arrays, when in one word you can place not one element of the array, but several, that is, pack them. This type

⟦folio 53⟧

often used when describing arrays of texts composed of letters.

So, sorting is also possible in cases where the keys take text values.

When choosing a sorting method, it is important to use any knowledge you have about the organization or ordering of the collections of data to be sorted. In this regard, the most characteristic is the spin method. It is used to order a collection of elements obtained by combining two or more collections already ordered by the same keys. Such situations occur frequently. For example, from the lists of all tenth grades of schools ordered “alphabetically” (that is, in lexicographic order), it is necessary to compile a general list of graduates while maintaining the lexicographic order. Let's consider a program for spinning two such list-files f1 and f2

Fig. 1.

(Fig. 1). We are therefore talking about external sorting. However, the spin method is used almost exclusively in external sortings. The reader can, having understood the spin method, run the spin program for internal sorting as an independent control - for ordering arrays, not files.

The method requires space in memory for another file f, in which the result will be placed. You can move through files f1 and f2, reading their elements sequentially. At the same time, at each step, the values ​​of the keys in the last read elements of the files f1 and f2 (in their buffer variables) are compared, and according to the result of the comparisons, the youngest element ends up at the end of the result file. Pay attention to an important detail: by moving through files f1 and f2, you can add to the end of one of the files when the other is not yet finished. In this case, you should, without unnecessary comparisons, rewrite the weight of the “tail” of the unread completely file as a result.

The procedure that checks the end of file f1 before moving on to reading its next record is called record1. If necessary, it rewrites the “tail” of the file as a result, which does not require further comparisons. (A similar procedure for file f2 is completely symmetrical - the description of the write2 procedure is obtained by replacing all having the write1 procedures by one with a two and vice versa.)

procedure record1;
begin
get(f1);
if eof(f1)
then
begin
while NOT(eof(f2)) do
begin write(f,ф2↑); get(f2) end
end:=true
end
end;

In order to free the program from unprincipled (and small) conditions, it is assumed that in the elements of both merged files the key is in first place. A program that includes spinal procedures must contain descriptions

type file=file of record
record=record
keys: array;
context: array [1..60] of char
end;

(the array type is described above, before (3)). Then the spin procedure takes the form

procedure back(var f1,f2,f: file);
var end:boolean
begin
end:false; newrite(f); neset(f1);
reset(f2);
while NOT (end) do
if f1↑.key-f2↑.key (4)
then
begin
write(f,f1↑); write(f,f2↑);
entry 1; entry 2
end
else
if comparison(f1↑key, f2↑.key)
then
