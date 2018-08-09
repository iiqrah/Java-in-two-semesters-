
# Chapter 2: Building Blocks

## Date : 8/08/2018

### Data types: 

 - Programs become interesting only when they allow you to store, manipulate and play with data
 - Different programming languages offer different data types
 - The types of value that can be used in a program is called data types. 
 
### Simple/Scalar/Primitive Data types: 

  - Known as scalar because they can only hold a single piece of information, be it number or character
  - There are 8 simple data types in Java: 
  
      | Data Types | Kind of Value | Extra info |
      | :---         |     :---:      |     :---:      |
      | byte   | very small integer     | -128 to 127   |
      | short     | small integer       |   -    |
      | int   | big integer     |  normally picked for integer  |
      | long    | very big integer      |    -   |
      | float   | big real number    |  -   |
      | double    | very big real number      |   normally picked for real numbers / requires double the space of int  |
      | char   | character     | from unicode / requires half the space of int  |
      | boolean    | true or false     | two possible values: yes or no     |
      

### Declaring: 

  - To create named locations in the computer's memory to hold values while the program is runnning
  
### Variables: 

  - The named locations 
  - Known as variable because their value is allowed to be changed/varied while a program is running.
  
### Declaring of variables: 

  - selecting the appropriate data type that would be used to hold the value of the variable
  - choosing an appropriate name for the variable of your choice
  - same rule used as naming classes, convention to start with small letter and follow camelCase or name1_name2
  
 #### Declaring multiple variables:
 
  ```
  int variable1;
  int variable2;
  char variable3;
  ```
 
 #### Declaring multiple variables in same line: 
 
  ```
  int variable1, variable2;
  char variable3;
  ```

### Assignment: 

  - Putting/assigning values to the declared variables 
  - With the help of an assignment operator " = "
  - Two ways: 
  
  ```
  int variable1;
  variable1 = 10;
  ```
  
  ```
  char variable2 = 'I';
  ```
  
  ### Constants: 

  - named location where the value does not change after declaration. 
  - declared same as variable with the addition of preceeding it with "final"
  - convention to name constants in all CAPS
  
  ```
  final double PI = 3.1416;
  ```
  
  - variables are only declared once, however they can be assigned value any number of times in a program. 
  - constants are only declared and assigned a value once, the value cannot be changed later. 

