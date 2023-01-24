###   C-Printf
### THIS IS A PAIRED PROGRAMING PROJECT ON THE PRINTF FUNCTION IN C.

     AUTHORS: Ayan, Nicholas && Frankelly Ozonwu.

The printf function is the C language function to do formatted printing. printf in the most simplest case takes one argument: a string of characters to be printed. This string iscomposed of characters, each of which is printed ex-actly as it appears. So printf("xyz"); would sim-ply print an x, then a y, and ﬁnally a z.

The printf format string is a control parameter used by a class of functions in the input/output libraries of C and many other programming languages. The string is written in a simple template language: characters are usually copied literally into the function's output, but format specifiers, which start with a % character, indicate the location and method to translate a piece of data (such as a number) to characters.

#Syntax
 int printf (const char* c-string, ...);

Return Value: If the function successfully executes, it returns the total number of characters written to the standard output. If an error occurs, a negative number is returned.

Arguments: c-string is the string passed to the function. There can be additional arguments following c-string, if there exist format specifiers in the c-string.

# The Most Commonly Used Format Specifiers in C 

 %d (Decimal Integer) 

 %c (Character) 

 %f (Floating Point) 

 %e (Floating Pointer Number)

 %s (String) 

 %lf (Double) 

 %o (octal integer) 

 %x (Hexadecimal Integer) 

 %p (Prints Memory Address) 

"printf" is the name of one of the main C output functions, and stands for "print formatted".

Many languages other than C copy the printf format string syntax closely or exactly in their own I/O functions.

