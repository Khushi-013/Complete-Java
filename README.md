# Complete-Java
This is complete java notes. Learn Java from Basics
Install Java
a)Install JDK - https://www.oracle.com/in/java/technologies/javase-downloads.html
b)Install Intellij - https://www.jetbrains.com/idea/download/#section=mac
c)Install Visual Studio Code - https://code.visualstudio.com/download

Functions
A function is a block of code which takes some input, performs some operations & returns some output. The function stored inside classes are called methods. The function we have used is called main.


Class
A class is a group of objects which have common properties. A class can have some properites & functions(called methods). The class we have used is Main.


Variables
A variable is a container (storage area) used to hold data. Each variable should be given a unique name (identifier).

package com.khushi;

Data Types
Data types are declarations for variables. This determines the type and size of data associated with variables which is essential to know since different data types occupy different sizes of memory.
There are 2 types of Data Types:-

1)Primitive Data Types: to store simple values
These are the data types of fixed size
Data Type                    Meaning                                Size(in Bytes)                       Range
byte                   2's complement integer                            1                            -128 to  127
short                  2's complement integer                            2                            -32 to 32K
int                    Integer numbers                                   4                            -2B to 2B
long                   2's complement integer (larger value)             8                            -9,223,372,036,854,775,808 to 9,223,372,036,854,775,808
float                  Floating-point                                    4                            Upto 7 decimal digits
double                 Double floating-point                             8                            Upto 16 decimal digits
char                   Character                                         2                            a,b,c,.....A,B,C,......@,#,$,....
bool                   Boolean                                           1                            True,False

2)Non-Primitive Data Types: to store complex values      
These are of variable size & are usually declared with a "new" keyword.
E.g. String, Arrays
String name=new String("Khushi")
int[] marks = new int[3];
              marks[0]=97;
              marks[1]=98;
              marks[2]=95;
              
Constants
A constant is a variable in Java which has a fixed value i.e. it cannot be assigned a different value once assigned
E.g. package com.khushi;
     public class Main{
     public static void main(String[] args){
     //constants
     final float PI=3.14F;
     }
     }

