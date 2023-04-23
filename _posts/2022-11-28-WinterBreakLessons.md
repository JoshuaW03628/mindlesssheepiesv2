---
toc: false
layout: base
description: pre tree notes
categories: [Pre-Tree]
title:  Pre tree
permalink: /posts/Pre-Tree-Notes
---

# Lesson 3.1/2 Variables Assignments and Data Abstraction

## What is a variable

- A variable is an abstraction inside a program that can hold a value

- It organizes data by labeling it with a descriptive name

- It consists of three parts: name, value, and type

- Using meaningful variables names helps with readability of program code and understanding of what values are represented by the variables



## Naming Variables

- Keep the name simple but not too vague
- proper syntax, no spaces


## Types of data

- Integer; A number
- Text/String; A word
- Boolean; Data that determines if something is true or false


## What is Data Abstraction

- Method used in coding to represent data in a useful form, by taking away aspects of data that aren't being used in the situation

- Variables and lists are primary tools in data abstraction

- Provides a separation between the abstract properties of a data type and the concrete details of its representation


## Lists and Strings

- List = ordered sequence of elements.

- Element = individual value in a list that is assigned to a unique index.
- Index = a way to reference the elements in a list or string using natural numbers; each element of a string is referenced by an index.
- String = ordered sequence of characters (Letters, numbers, special characters).

## * AP Exam usage of Data Abstraction


With the properties of the AP Exam pseudocode, lists work differently from what we've learned in python so far, here are the two major differences:

- The index does not start at 0 but 1
- There is only one method of interchanging data between lists, and that is completely overwriting previous list data with the other list\n",


# 3.3/4 Lesson

## Algorithms

- Algorithms has 3 components

    - Sequencing: Algorithms do tasks in the order of specification.
    - Selection: Helps choose two different outcomes based off a decision.
    - Iteration: If a condition is true, then the code can repeat.

- Algorithms can be represented in two ways

    - Flowcharts or Psuedocode.

## Arithmetic Operations

- Basic

Subtraction:
Represented by “-"
num1 = 2 - 1

Addition:
Represented by "+"
num1 = 2 + 1

Multiplication:
Represented by “*”
num1 = 2 * 1

Division:
Represented by “/”
num1 = 2 / 1

Getting the Remainder:
Represented by “MOD” (% in python)
num1 = 5 % 2

- Order of Operations

Arithmetic operations in programming are performed in the same order as operations in mathematics:

- Operations in parentheses should be done first.

- Division and multiplication should be done before addition and subtraction.

- Modulus works similar to multiplication and division.

## Variables

- Different ways values can be stored in a variable
    - Numerical value stored in a variable
    - Value of another variable stored in a variable
    - Result of an operation stored in a variable

## Sequence

Changing the order of the steps changes the overall outcome, since every time the value assigned to a variable is changed, it overrides the last value which was assigned to the same variable. That is why it is important to track the value of variables, especially in code where the value is constantly changing.



## String

A String: A string is a collection of characters. What is a character as character can be anything from numbers, letters, spaces, special symbols, etc.

Certain procedures may be used with strings and they vary from programming language to language Python examples;

- len() to find the length of a string

- lower() to convert to lowercase
 
Pseudocode examples;

- len() returns the length of a string

- concat() returns a string made up of the concatenated strings ex. concat("string1", "string2") would return string1string2

- substring() returns the characters from the string beginning at the at the first position to the last so an example of this would be substring ("abcdefghijk", 2, 5) would print bcde (pseudocode starts at 1)

- SubString 

A substring is a part of and already existing string.

- In pseudocode substring() method is used for instance for concat("Mr.Mortenson is very handsome" 1, 2) the system would return Mr (remember that pseudocode starts at 1)


# Lesson 3.5 - 3.7  


## What is a Boolean

- A data type with two possible values: true or false

## What is the Difference between a Boolean and Binary

So similar yet so different.

- Boolean math and binary notation both use the same two ciphers: 1 and 0.
- However, please note that Boolean quantities are restricted to a singlular bit (can only be either 1, or 0)
- On the otherhand, binary numbers may be composed of many bits adding up in place-weighted form to any finite value, or size

## Logical Operators

These types of operators don't necessarily deal with equivalent/non-equivalent values, but they rather work on operands to produce a singular boolean result

- AND : returns TRUE if the operands around it are TRUE
- OR : returns TRUE if at least one operand is TRUE
- NOT : returns TRUE if the following boolean is FALSE


## Conditionals

- Selection: uses a condition that evaluates to true or false

- Selection determines which part of an algorithm are executed based on a condition being true or false

- Algorithm is a finite set of instructions that accomplish a specific task

CONDITIONAL STATEMENTS

- also known as if statements, and also else.

## Nested Conditionals


- If else statements within if else statement


# Lesson 3.8/3.10

## What is a list

Lists: a sequence of variables
- we can use lists to store multiple items into one variable
- used to store collections of data
- changeable, ordered, allow duplicates

### Lists are just one of four collection data types in Python
- Tuple: collection that is ordered, unchangeable, allows duplicates
- Set: collection that is unordered, unchangeable, doesn't allow duplicates
- Dictionary: collection that is ordered, changeable, doesn't allow duplicates

### Terms
- Index: a term used to sort data in order to reference to an element in a list (allows for duplicates)
- Elements: the values in the list assigned to an index

## Methods in Lists

| Method | Definition | Example |
|-|-|-|
| append() | adds element to the end of the list | fruits.append("watermelon") |
| index() | returns the index of the first element with the specified value | fruits.index("apple") |
| insert() | adds element at given position | fruits.insert(1, "watermelon")|
| remove() | removes the first item with the specified value | fruits.remove("strawberry") |
| reverse() | reverses the list order | fruits.reverse() |
| sort() | sorts the list | fruits.sort() |
| count() | returns the amount of elements with the specified value | fruits.count("apple") |
| copy() | returns a copy of the list | fruits.copy() |
| clear() | removes the elements from the list | fruits.clear() |


## What is Iteration
> Iteration is the repetition of a process or utterance applied to the result or taken from a previous statement.
> There's a lot of types of iteration though, what to use? How do we apply iteration to lists? 

> Some methods include using a "for loop", using a "for loop and range()", using a "while loop", and using comprehension 

### Usage
> Lists, tuples, dictionaries, and sets are iterable objects. They are the 'containers' that store the data to iterate. 

>Each of these containers are able to iterate with the iter() command. 

>There are 2 types of iteration: definite and indefinite. Definite iteration clarifies how many times the loop is going to run, while indefinite specifies a condition that must be met

### Iterator? Iterable? Iteration? 
- When an object is iterable it can be used in an iteration 
- When passed through the function iter() it returns an iterator 
- Strings, lists, dictionaries, sets and tuples are all examples of iterable objects.

#### Too time consuming?

- use the range function x=range( )

## 2D Arrays
- a list of lists, literally