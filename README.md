# project-1

You will submit this project's source code to your account in CodePost where it will be compiled and tested with several test files. Some of the test files are provided for you to look at in this repository. If your program fails to compile in CodePost you will receive a grade of 0. Be sure to test and be careful what you submit for the final version. You can submit multiple times to CodePost with a maximum of 10. 

Given a list of numbers, positive, negative, while numbers and decimal numbers, read them in as you are reading compute the following values:

```
Average of all
Average of positive
Average of negative
Average of odd numbers
Average of even numbers
Average of whole numbers
Average of real numbers
Average of prime numbers
```

The end of the list of numbers will be indicated with -10101010.

Following the end of the list of numbers will be a list of possible commands as follows:

```
ALL - print the average of ALL numbers
POS - print the average of only the positive numbers
NEG - print the average of only the negative numbers
ODD - print the average of only the odd numbers
EVEN - print the average of only the even numbers 
WHOLE - print the average of only the whole numbers
REAL - print the average of only the decimal numbers (floating point)
PRIME - print the average of only the prime numbers
STOP
```

For each command that you read, output a single line with the corresponding  average. Do NOT print anything else. Just the average. Points will be taken off for additional output. 

End the program when you read STOP.


For grade of C your program needs to handle integers plus these commands: ALL, POS, NEG STOP

For grade of B your program needs to handle all of C plus real numbers and these commands: ODD, EVEN, WHOLE, REAL, STOP. In addition is must ignore invalid commands. 

For grade of A your program needs to handle all of C&B plus invalid numbers which are to be ignored: PRIME, STOP, In addition it must handle commands regardless of their casing (All, ALL, all, etc)


Submit your final source to CodePost using the file name averages.cpp.


