# Chapter 2: Building Blocks

## Date : 9/08/2018

## Notes - Expression and Output

### Arithematic operators in order of precedenece:


  | Symbol | Name |
  | --- | --- |
  | /  | Division  |
  | *  | Multiplication  |
  | +  | Addition  |
  | -  | Subtraction  |
  | %  | Remainder/Modulus  |
          
          
### Overload in division:

 -  In Java, division has two built-in routines to follow
 - One to calculate an integer answer , when both numbers are integers
 - The other to calculate a real number answer, when at least one of them is a real number
 - Division operator said to be overloaded as it behaves in different ways  
 
 
 ### Output in Java:
 
  - We can use System.out.println(expression)
  - The expression is converted to a literal String before being printed out
  - To concatenate strings + expressions, enclose expressionsin brackets
  
  ```
  System.out.print("Sum of first four whole numbers: " + (0+1+2+3));
  ```
  
   ### User Input in Java:
   
   - Done through special Java class called Scanner
   - Scanner is a part of util package
   - Package: collection of pre compiled classes 
   - Access package by __import__ keyword for compiler to use
   - " * " makes all the pre compiled classes in util package to be avaialble to the compiler
   
   ```
   import java.util.*
   ```
   

   - Package > Classes > Methods
   - Util > Scanner > Input methods (nextInt(), nextDouble() etc)

   
   
   ```
   import java.util.*
   
   int num1;
   char firstInitial;
   
   Scanner keyboard = new Scanner(System.in)
   
   num1 = keyboard.nextInt();
   firstInitial = keyboard.next().charAt(0);
   
   ```
   
   - System.in represents keyboard
   - Always end methods with ()
   
   
   Import > Create class object with new instance > Use object with class method
   
   
  ### Program Design:
  
  - Designing: how to build, pseudocode. 
  - Implementation: build.
   
  
