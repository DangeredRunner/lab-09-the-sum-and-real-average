# lab-09-the-sum-and-real-average

##Problem- 
I needed a program that reads two integers a and b and computes outputs without integer division truncating fractional averages like 1.5 into 1.   

##What I built- 
A C program that reads two integers a and b, stores their sum in a double variable named summ, and prints the sum and real average formatted to two decimal places.   

##How it works- 
Read two integers a and b using scanf.Store a + b in a double variable summ so the division summ / 2 uses floating-point arithmetic rather than truncating integer division.Print summ and summ / 2.

##How I tested it- 
I tested the program with a = 5, b = -2 and with a = 7, b = 4 to check the outputs and confirm the average is not truncated to an integer.   

##What I learned- 
Using a floating-point type (double) for summ avoids integer division truncation so fractional averages like 1.5 are preserved instead of becoming 1.   
