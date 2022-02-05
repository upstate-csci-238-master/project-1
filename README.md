# project-1

You will submit this project's source code to your account in CodePost where it will be compiled and tested with several test files. Some of the test files are provided for you to look at in this repository. If your program fails to compile in CodePost you will receive a grade of 0. Be sure to test and be careful what you submit for the final version. You can submit multiple times to CodePost with a maximum of 10. 

Given a list of numbers, positive, negative, while numbers and decimal numbers, read them in as you are reading compute the following values:

```
Average of all
Average of positive (any number, integer or decimal; zero is considered positive)
Average of negative (any number, integer or decimal)
Average of odd numbers (any integer positive or negative that is odd)
Average of even numbers (any integer positive or negative that is even)
Average of whole numbers (any number that is postive, negative or zero and does not have a decimal point)
Average of real numbers (any number, positive, negative or zero with a necimal point)
Average of prime numbers(google to learn which numbers are prime)
```

The end of the list of numbers will be indicated with -10101010. DO NOT INCLUDE THIS NUMBER IN ANY AVERAGES. 

Following the end of the list of numbers will be a list of possible commands as follows:

```
ALL - print the average of ALL numbers
POS - print the average of only the positive numbers
NEG - print the average of only the negative numbers
ODD - print the average of only the odd numbers
EVEN - print the average of only the even numbers 
WHOLE - print the average of only the whole numbers, I am defining whole as ANY INTEGER, negative, positive or zero; sorry for the variation from normal math terms
REAL - print the average of only the decimal numbers (numbers with a decimal point, ie. floating point)
PRIME - print the average of only the prime numbers
STOP
```

For each command that you read, output a single line with the corresponding  average. Do NOT print anything else. Just the average. Points will be taken off for additional output. 

End the program when you read STOP.


For grade of C your program needs to handle integers plus these commands: ALL, POS, NEG, STOP

For grade of B your program needs to handle all of C plus real numbers and these commands: ODD, EVEN, WHOLE, REAL. In addition it must ignore invalid commands. 

For grade of A your program needs to handle all of C & B plus invalid numbers which are to be ignored and the PRIME command. In addition it must handle commands regardless of their casing (All, ALL, all, etc)


Submit your final source to CodePost using the file name averages.cpp.


