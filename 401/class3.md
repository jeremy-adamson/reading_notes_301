# File IO and Exceptions

## Reading Notes

* File reading (and writing) in python is significantly easier than what it was in C++
* There are built in functions to get each character (if wanted), each full line, and a standard method for reading in an entire file as needed.
* While opening and closing files manually can be done, it is advised to use `with` statements which will automatically close a file once editing/reading is complete.
* Appending to files is just as straightforward but CR and end of line (/r/n) are needed when appending to denote next line and end of line respectively.

## Exceptions vs. Syntax

* Syntax errors will mean that the code won't compile
* Exception errors means that the code runs into an error post compiling or build in when the code should throw an error for whoever is running it (ie indicate invalid input)

## Readings/Media

* [Read & Write Files in Python](https://realpython.com/read-write-files-python/)
* [Exceptions in Python](https://realpython.com/python-exceptions/)
* [Read & Write Files in Python - Companion Video](https://realpython.com/courses/reading-and-writing-files-python/)
* [Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)
