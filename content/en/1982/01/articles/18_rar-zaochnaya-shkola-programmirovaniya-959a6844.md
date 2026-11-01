---
id: 1982-1-rar-zaochnaya-shkola-programmirovaniya-959a6844
issue: kvant_1982_1
year: 1982
number: "1"
title: Correspondence School of Programming
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 51
page_last: 54
page_labels: 49, 51, 52
tag: DAIR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 77787fba8bff25d109a4ba25d460912d0f764998dd45b6ae992ddc8be603c168
prompt_sha256: draft-1
translated_from: content/ru/1982/01/articles/18_rar-zaochnaya-shkola-programmirovaniya-959a6844.md
source_content_sha256: bbd8ebccfbda4a299ffe25a1ff577f163ff92ef6276973d143e1858e9e633eae
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

The Art of Programming” we continue to publish lessons from the Correspondence School of Programming and articles on computer science, programming languages ​​and computer technology. The lesson of the correspondence school student, who will complete her third and final course in the first issues of this year, is unlikely to be accessible to new readers of the magazine. The remaining articles, we hope, will lift the veil of secrecy that is sometimes still surrounded by computers, and will explain why mastering computer technology is sometimes called “second literacy.”

Correspondence school of programming.

Lesson 17: Arrays and Records in Pascal

Further capabilities of Pascal are related to the presence of structural types in it, namely types for arrays, records and files. Let's start with arrays and records.

Arrays
An array is a collection of a certain number of elements; all these elements must be of the same type. In this case, one should imagine that the elements of the array are arranged in some regular way: like rows, like a rectangular table, like a rectangular spatial lattice, etc. These different cases correspond to arrays of different dimensions: one-dimensional (or vectors), two-dimensional (or matrices), three-dimensional, etc.

To specify an element of an array with dimension $n$, you need to specify $n$ coordinates that determine the location of this element in the array; We will call these coordinates indices. For example, an element of a matrix is ​​defined by two indices, one of which denotes the row of the matrix, and the other of which denotes the element in the row (that is, essentially the column of the matrix).

The values ​​that the index takes (for example, the values ​​denoting the rows of our matrix or its columns) constitute some kind of scalar type (that is, as we saw earlier, an ordered set). This scalar type can be anything except real, but it is most natural to use a segment of type integer in this capacity, and then it is clear that indices are simply numbers.

Let, for example, in a matrix the rows are numbers from 1 to 5, and the columns are numbers from 0 to 19. Then the type of the first index is 1..5, and the second is 0..19.

The array type is specified by the following syntax diagram:

In this diagram, “scalar types” are sequentially the types of the first, second, etc. indexes, and their number, naturally, is equal to the dimension of the array. The tun field contains the type of array elements (same for all elements).

A separate array element is represented in the program as a variable with indices. Its syntax diagram is also:

"Name" here is the name of the corresponding array. The number of expressions must be equal to the number of array indexes, and the types of expressions must match the types of the corresponding indexes.

Let's move on to examples. Let the type description section in the program have the form

⟦folio 51⟧

The list of fields, in turn, is specified by diagram

For now we will consider record types without a replaceable part. The record element is represented in the program as a selection of fields, the syntactic diagram of which is as follows:

"Name" here is the name of the corresponding entry.

Records are convenient to use for storing and processing various information about certain objects. In the following example, the records contain information about different countries around the world. Let the type description section in the program have the form

```text
type data = record
    год, месяц, день: integer
end;
вызы = record
    университеты, технические,
    прочее: integer
end;
страна = record
    плочадь, населенение:real;
    устройство:boolean;
    вступление:дата;
    образование:вызы
end;
```

Note that the data types and calls are different: although they specify a triple of integers, their field names are different.

Let further in the section describing the program variables have a description

australia, australia, albania, ...
japan:country;

Hidden under multi-point here is a list of all countries that are members of the UN. Information about each of them, stored in the corresponding fields, is as follows: area (in thousand sq. km.), population size (in million people), structural structure (republic - true, monarchy - false), data on joining the UN, number of different higher educational institutions.

Task 17.5 In our example, some fields have “extensive” entry types. Change the descriptions so that the index change ranges are as small as possible.

Let's assume that all fields in all records are already filled in. Then, for example, the operator writeln(ukraina.hapopulation/ukraina.area);
will print the population density in Ukraine.

Expanding the concept of a variable

Let our program describe a university variable of type integer.

This is acceptable: the same name (in our example, universities) in the same program can be used for a variable and for a record field (as well as for fields of different record types).

We want to assign to this variable the total number of universities in the Iberian Peninsula, for which we write the assignment operator universities: =spain. education.
 universities + portulation.
 education. universities;

Each of the terms is a sample, but not from a common variable, but from another sample.

So, from the variable Spain (type country), the field education (type call) is extracted, and from it the field universities (type integer).

To specify such constructs, we would need to introduce changes to some of our syntactic diagrams. But we will not do this, but simply stipulate that the concept of a variable covers not only general variables, but also variables with indexes and field selections. There are also conditions that any action performed in the program on a variable in the word sense mode (including field extraction) can also be performed on a variable in the extended sense.

Task 17.6. Write a procedure on the right with a country type parameter that prints for the corresponding country: a) whether it is a republic or a monarchy, b) how many inhabitants it has per institution of higher education.

Posts with variants

We believed until now that records belonging to the same

⟦folio 52⟧

type, organized in exactly the same way. Pascal, however, makes it possible to relax this restriction. By using a “replacement part” in the record type description (see the syntax diagram for this description), programs can define records with variants.

The replacement part has the following syntax diagram*)

between them (calculated in radians: 180° = π radian). For a triangle, we will also indicate whether the traversal from x to y is performed clockwise or counterclockwise (in the traversal field the traversal will be true or false, respectively). No additional fields are required for the circle.

Let us further describe a fcesure type variable f, and let it be with non-

The “name - type name” pair after case specifies a special field of the record: the attribute field. The value of this field will be called a sign. The sign (at any given moment of program execution) must be one of the following constants. The constant that serves as a sign specifies the variant of the record, that is, it determines what further fields of the record are: these are precisely those fields, the list of which appears in parentheses after this constant.

Let us consider a set of all possible triangles, parallelograms and circles located on a plane (and freely moving along it). Such a collection is specified by the fcesura type, which has the following description:

fcesura =
recordx:real;
casef:form of
triangle:(y, el:real);
bypass: boolean;
parallelogram: (y1, el1:real);
cool: ()
end

The type of shape is described as shape = (triangle, parallelogram, circle));

Field x is common to all three figures: for a triangle and a parallelogram it is one of the sides, for a circle it is the radius. For a triangle and a parallelogram, you need to determine the second, funny side and angle

*) Due to technical principles, it was not possible to correct the operation in this diagram: the bypass arrow should cover only one field, a list of fields, and not three fields: (, list of fields,).

Dictionary
array - array
record - record

A. Pap
