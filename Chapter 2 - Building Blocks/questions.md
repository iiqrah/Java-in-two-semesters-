# Chapter 2: Building Blocks

## Date : 9/08/2018

## Self-test Questions


### 1. Choose apt data type for the following: 

 - max no of people in a bus: int (Integer)
 - weight of a food item: double (Real number)
 - grade awared to student: char (Character)
 
 
### 2. Explain if any errors: 

```
int x = 75.5; 
double y = 75;
```
  - Compiling error for the first line
  - data type is decalred as integer and the value assigned is a real number
  - error: "Type mismatch: cannot convert from double to int"
  
  
 ### 3. Explain if any errors:  
 
 ```
import java.util.* ;

public class Assignment {
	public static void main (String[] args)
	{
		
		Scanner keyboard = new Scanner(System.in);
		
		final int YEAR;
		
		int age, bornIn;
		
		System.out.println("How old are you this year?");
		age = keyboard.nextDouble(); //ERROR type mismatch
		
		bornIn = YEAR-age; //ERROR variable not initialized 
		
		System.out.println("You were born in: " + bornIn);	
	}
}
  
```

Extra: program logic flawed as month is also taken into consideration of typing in the input. 

 ### 4. Pseudocode and implementation for area and perimeter of rectangle
 
 - START 
 - DISPLAY program title
 - DISPLAY prompt for rectangle length
 - ENTER and store length
 - DISPLAY prompt for rectangle height
 - ENTER and store height
 - CALCULATE area
 - CALCULATE perimeter
 - DISPLAY calculations
 - STOP
 
 ```
 import java.util.* ; 

public class Assignment {
	public static void main (String[] args)
	{		
		double length, height, area, perimeter;
		
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Calculate area and perimeter of rectangle");
		
		System.out.print("Enter length in cms: ");
		length = keyboard.nextDouble();
		
		System.out.print("Enter height in cms: ");
		height = keyboard.nextDouble();
		
		area = length*height;
		perimeter = 2*(length+height);
		
		System.out.println("Area of rectangle: " + area + " cms");
		System.out.println("Perimeter of rectangle: " + perimeter + " cms");
		
		
	}
}

 ```
 
  ### 5. Faulty number swap program
  
  ```
import java.util.* ;

public class Assignment {
	public static void main (String[] args)
	{		
		int num1, num2;
		
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Swap numbers");
		
		System.out.println("Enter first number: ");
		num1 = keyboard.nextInt();
		
		System.out.println("Enter second number: ");
		num2 = keyboard.nextInt();
		
		num1 = num2;
		num2 = num1;
		
		System.out.println("Value of first number: " + num1);
		System.out.println("Value of second number: " + num2);
		
	}
}
  ```
  
  
  - In this program num1 is assigned num2
  - Next num2 is assigned num1 which was already assigned num2 value previously, hence both get assigned the value of num2
  
  
  - Output for user input 10 and 20 would be: 
  
  ```
  Value of first number: 20
  Value of second number: 20
  ```
  
  - Corrected program
  
  - Include a temporary variable to store num1 value that is being lost in swapping
  
  ```
  import java.util.* ;

public class Assignment {
	public static void main (String[] args)
	{		
		int num1, num2, temp;
		
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Swap numbers");
		
		System.out.println("Enter first number: ");
		num1 = keyboard.nextInt();
		
		System.out.println("Enter second number: ");
		num2 = keyboard.nextInt();
		
		temp = num1;
		num1 = num2;
		num2 = temp;
		
		System.out.println("Value of first number: " + num1);
		System.out.println("Value of second number: " + num2);
		
	}
}

  
  ```
  
 ### Pseudocode and implementation of pounds to kgs program
 
 /*
 - START 
 - Prompt for values in pound
 - Enter value in pounds
 - Set value to old value / 2.2 (1 kg = 2.2 pounds)
 - Display value in kilo
 - STOP
 */

```
import java.util.* ; 

public class Assignment {
	public static void main (String[] args)
	{		
		double pounds, kilos;
		
		Scanner input = new Scanner(System.in);
		
		System.out.print("Enter weight in pounds: ");
		pounds = input.nextDouble();
		
		kilos = pounds/2.2;
		
		System.out.print(pounds + " lbs is equal to " + kilos + " kgs");
		
		
		
	}
}

```

 ### Pseudocode and implementation of forming teams
 
  - START
  - DISPLAY prompt for number of students
  - ENTER and store value
  - DISPLAY prompt for size of team
  - ENTER and store value
  - CALCULATE teams = number/size
  - CALCULATE remaining = number%size
  - DISPLAY calculations
  - STOP
  
  ```
  import java.util.* ;

public class Assignment {
	public static void main (String[] args)
	{	
		int numberOfStudents, teamSize , numberOfTeams, remainingStudents;
		
		Scanner keyboard = new Scanner(System.in);
		
		System.out.print("Enter total number of students: ");
		numberOfStudents = keyboard.nextInt();
		
		System.out.print("Enter desired team size: ");
		teamSize = keyboard.nextInt();
		
		numberOfTeams = numberOfStudents/teamSize;
		remainingStudents = numberOfStudents%teamSize;
		
		System.out.println("Number of teams: "+ numberOfTeams);
		System.out.println("Number of students remaining: "+ remainingStudents);
		
		
	}
}
  ```
  
 ### Pseudocode and implementation of area and circumference of circle
   
 - START 
 - DISPLAY program title
 - DISPLAY prompt for circle radius
 - ENTER and store radius
 - CALCULATE area
 - CALCULATE circumference
 - DISPLAY calculations
 - STOP
 
 ```
 import java.util.* ; 

public class Assignment {
	public static void main (String[] args)
	{		
		double radius, area, circumference;
		
		final double PI = 3.1416;
		
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Calculate area and circumference of circle");
		
		System.out.print("Enter radius in cms: ");
		radius = keyboard.nextDouble();
		
		
		area = PI*(radius*radius);
		circumference = 2*(PI*radius);
		
		System.out.println("Area of circle: " + area + " cms");
		System.out.println("Circumference of circle: " + circumference + " cms");
		
		
	}
}

 
 ```
   
  
 
