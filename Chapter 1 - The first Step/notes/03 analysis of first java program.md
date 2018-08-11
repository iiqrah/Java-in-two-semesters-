# Chapter 1: The First Step

## Date : 7/08/2018

## Notes - Analysis of First Java Program 


```

public class HelloHackers
{
  public static void main (String[] args)
  {
    System.out.println ("Hello Hackers!"); //This is a single line comment
    
    /* I am a multiple line comment
    All of this will get ignored
    But I am very important to you, human reading this
    */
    
  }
}

```


### Print command

```
System.out.println ("Hello Hackers!");
```
 - println stands for print line
 - prints whatever is in the bracket and moves the cursor to a new line

OR

```
System.out.print ("Hello Hackers!");
```
  - prints whatever is in the bracket and lets the cursor stay in the same position


### Header

```
public class HelloHackers
```

#### public

  - makes the class accesible to the outside world/other classes
  - name the file similar to the name of the public class, here file is called HelloHackers.java

#### class HelloHackers

- OOP languages require the program to be written in separate units called classes
- Always give a name to the class, here it is called HelloHackers
- This simple program, we created just one class however it interacts with other built-in classes

- Naming class conventions: 
  - not a keyword
  - does not have space
  - does not start with mathematical operators
  - starts with alphabet, underscore _ , or dollar sign $
  - starts with a capital letter 
  
### Main method

```
public static void main(String[] args)
```

  - main method where the program begins and goes sequentially
  - program ends when all instructions inside this main method is completed
  - each program should have this one main method
  
  
  ### Comments
  
  - Three ways of documenting/commenting your prgrans
    - single line comments : start with //
    - multiple line comments : start /* and end */
    - Javadoc for documenting your progarms: start /** and end */
    
  - Ignored by the comipler 
  - User for the programmer to keep track/put useful infromation, does not affect the program
  








