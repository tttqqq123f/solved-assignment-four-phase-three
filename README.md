Download Link: https://assignmentchef.com/product/solved-assignment-four-phase-three
<br>
<p class="ui header product-top-header" title="Assignment Four - Phase Three  Solution">Objective

To gain experience with the dynamic data structures (allocation, automatic expansion, deletion) and the “big three” concepts: Destructors, Copy constructors, and Assignment operator.

Project Description

In last two assignments (phase I &amp; phase II), we wrote a String class by using static array as the data member.  The purpose of this assignment is to replace the static array by dynamic array. You are required to modify the String class accordingly:

Data:  we wish to allow our String class to accommodate strings of different sizes. To that end, instead of storing a string’s characters in a fixed-size array, each String object should contain the following data as part of its internal representation:

(1) a character pointer meant to point to a dynamically-allocated array of characters.(2) a length field that will hold the current length of the string at any given moment.

Operations: same as the methods in String class – phase 2,  plus the “big three”( destructor, copy constructor, and assignment operator overloading).

Modularity: The String class code must be put in its own module, i.e., a file mystring.h (the header file) should hold the class definition (use conditional compilation directives) and a file mystring.cpp (the implementation file) should hold the method definitions.

Note: In your implementation of String’s methods, you may use the library functions provided by , which operate on the C style string. Our textbook contains good review about it  page 212 to 214, and Appendix D 5. However, the difference with the last assignment is that you need to allocate memory first in the implementations of constructors. Almost all the implementations of overloading operators (except +=, and = ) should not be changed.

Download Test Driver: We provide a driver (file Assign4driver.cpp ) that you can download and use to test your new class. You are not allowed to change it!

Upload your source code files (upload – do NOT zip them! – your two source files: mystring.h and mystring.cpp) for the assignment here.