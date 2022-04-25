# Week 4 Lab Report

## File that starts with a link
In the [Test File 1](testFIle.md), I put the link in front of the link name. It the output comes out with an infinite loop.
This happend because the MarkdownParse class wasn't able to find the starting point for this file. So that the for loop
will keep searching for the first argument and won't go to the next link. 



![image](week4one.JPG)


## File that uses `[]` but not `()`
In the [Test File 2](test1.md), instead of using `()`, I uses `[]`. And the output comes out with an infinite loop.
This happened because the MarkdownParse class found `[]`, but can't find the link with `()`. So that there won't have a 
starting point and the for loop will keep seaching for the first argument, and keep printing out the same number and cause a infinite loop.

![image](week4two.JPG)


## File that uses `()` but not `[]`
In the [Test File 3](test2.md), instead of using `[]`, I uses `()`. And the output comes out with `StringIndexOutOfBoundsException`.
This happened because the MarkdownParse class can't find the `[]`, and there are two `()`. So the for loop tried to find the link, but wasn't 
able to. So it will print out `StringIndexOutOfBoundsException` since an index is either negative or greater than the size of the string.

![image](week4three.JPG)
