# EXP-2
EXP 2 : Study of list in python

NAME : Aayush Vishwakarma
PRN : 25070123125

THEORY :-

A list in Python is an ordered, mutable collection of elements. Lists can store different data types such as integers, floats, strings, and booleans. Lists are written using square brackets [], and elements are separated by commas.

Creating and Printing Lists

Lists can contain homogeneous or heterogeneous data.

list1 = ["Apple", "Orange", "Cherry"] list2 = [2, 2.5, "Vivek", True]

Lists allow multiple data types in a single list.

print() displays the list elements.

Accessing List Elements (Indexing)

Indexing starts from 0.

Negative indexing starts from -1.

Slicing a List

Slicing is used to access a range of elements.

Length of a List

len(list)

len() returns the total number of elements in the list.

Modifying List Elements

Lists are mutable, meaning elements can be changed.

list4[1] = "mango"

The element at index 1 is replaced.

Adding Elements to a List

a) append()

Adds an element at the end of the list.

list5.append("mango")

b) insert()

Adds an element at a specific position.

list6.insert(1, "mango")

c) extend()

Adds elements of another list.

list7.extend(list8)

Duplicate Elements in Lists

Lists allow duplicate values.

list9 = ["apple", "orange", "apple", "cherry"]

Duplicate elements are stored and displayed as-is.

Student Marks Analysis

max() – finds the highest mark.

min() – finds the lowest mark.

sum() – calculates the total marks.

len() – counts the number of students.

sum() / len()- finds avg of marks.

sorted() – arranges the marks in ascending order

Grocery List Operations

append() – adds a new item at the end of the list.

remove() – removes a specific item from the list.

Algorithm :-

Student Marks Processing

Start

Create a list marks containing student marks.

Find the maximum mark using max().

Find the minimum mark using min().

Calculate the sum of marks using sum().

Count the number of students using len().

Calculate the average marks.

Sort the marks in ascending order using sorted().

Display all the results.

Stop.

Grocery List Modification

Start

Create a list grocery containing grocery items.

Add "potato" to the list using append().

Remove "milk" from the list using remove().

Remove "egg" from the list using remove().

Display the updated grocery list.

Stop

Conclusion :-

This experiment explains the concept of lists in Python and their operations such as creation, indexing, slicing, modification, and adding or removing elements. It also demonstrates practical applications of lists through student marks analysis and grocery list modification, helping to understand how lists are used for storing and processing data efficiently.
