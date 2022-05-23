# Week 8 Lab Report

* [link](https://github.com/Ppenguin215/markdown-parser) to my markdown-parse repository
* [link](https://github.com/colecarter96/markdown-parser) to the repository I reviewed

## Test for Snippet 1 (Implementation Reviewed)
* What markdown-parse should produce
![image](picture1.png)
* Test code 
![image](picture2.png)
* Test output
![image](picture3.png)

## Test for Snippet 2 (Implementation Reviewed)
* What markdown-parse should produce
![image](picture4.png)
* Test Code
![image](picture5.png)
* Test output
![image](picture6.png)

## ## Test for Snippet 3 (Implementation Reviewed)
* What markdown-parse should produce
![image](picture7.png)
* Test Code
![image](picture8.png)
* Test output
![image](picture9.png)

## Test for Snippet 1 (My Implementation)
* What markdown-parse should produce
![image](picture10.png)
* Test Code
![image](picture11.png)
* Test output
![image](picture12.png)

## Test for Snippet 2 (My Implementation)
* What markdown-parse should produce
![image](picture13.png)
* Test Code
![image](picture14.png)
* Test output
![image](picture15.png)

## Test for Snippet 3 (My Implementation)
* What markdown-parse should produce
![image](picture16.png)
* Test Code
![image](picture17.png)
* Test output
![image](picture18.png)

# Questions
* I think there is a small code change that will make my program work for snippet 1 and all related cases that use inline code with backticks. I can write a helper method that determines a valid link. In this case, if open bracket or open parenthesis occur between a pair of backticks, the method will determine this is an invalid link, so markdown-parse will not return the link.
* I think there is a small code change that will make my program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets. I can change the code of markdown-parse to make `closeParen` the index of the last close parenthesis, so markdown-parse will return the entire link in the parathesis. In this case, the program will reutrn `a.com(())` rather than `a.com((`.
* I think there is a small code change that will make my program work for snippet 3 and all related cases that have newlines in brackets and parentheses. I can write a helper method that returns a new string with the same content as Snippet 3, but it makes each link in the same line, so the output will not include new lines. For the link without close parenthesis, I can write a helper method that decides if a link has close parenthesis. If it doesn’t, the program will consider it as an invalid link and will not return it.
