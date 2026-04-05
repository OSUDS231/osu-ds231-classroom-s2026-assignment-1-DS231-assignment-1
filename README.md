# DS231 Assignment 1


## Overview and Objectives
In this assignment, you will write a series of programs to practice concepts from Week 1, including Python objects, expressions, string manipulation, and input/output.  

The assignment begins with warm-up exercises that focus on individual concepts introduced in lecture. It then progresses to more comprehensive problems that integrate multiple concepts into practical and meaningful programs.

## Instructions
1. Create a separate Python file (`.py`) for each question. The filename must match the one specified in the question exactly (e.g., `q1.py`).
2. Ensure that each program runs without errors. If your code fails to execute, a flat 20% penalty will be applied, regardless of the nature of the error.
3. Your program output must match the expected format shown in the "Example output" of each question.


## Question 1. String Manipulation [16 Points]
Create a file named `q1.py`.

Write a program that asks the user for a word, and:

1. Stores the user input in a variable named `word`
2. Prints the string repeated 4 times in a row
3. Prints the first 3 characters of the string
4. Prints the string in reverse using slicing

***Example output.*** When you run your program, the format should match the following: 
```text
What is the word that you have in mind? Python
PythonPythonPythonPython
Pyt
nohtyP
```

***Hint.*** Your program must work for any word provided by the user. While the example above uses 'Python,' your output should adapt correctly to different inputs. Ensure you test your code with various words to verify its flexibility.


## Question 2. Rectangle Calculator [16 Points]
Create a file named `q2.py`.

Write a program that:

1. Asks the user to enter:
   - the length of a rectangle
   - the width of a rectangle
3. Computes and prints:
   - the area (rounded to 1 decimal place)
   - the perimeter (rounded to 1 decimal place)
   - the length of the diagonal (rounded to 2 decimal place)

***Example output.*** When you run your program, the format should match the following: 
```text
Enter the length: 5
Enter the width: 3

Rectangle summary:
Area: 15.0
Perimeter: 16.0
Diagonal: 5.83
```

***Hint.***
- Convert inputs to numbers and store them for later computation.
- The diagonal of a rectangle can be calculated as
```math
\text{Diagonal} = \sqrt{\text{Length}^2 + \text{Width}^2}.
```
- Mathematically, $\sqrt{a}$ is equivalent of $a^{0.5}$.
- Print Area and Perimeter rounded to 1 decimal place, and Diagonal rounded to 2 decimal places.  You can use the `round()` function to control how many decimal places are shown. The function works as `round(number, decimal_places)`. For example, `round(15.8792, 2)` gives `15.88`.

## Question 3. Total Seconds Converter [8 Points]
Create a file named `q3.py`.

Write a program that:

1. Asks the user to enter a number of seconds (integer)
2. Converts the total seconds into hours, minutes, and seconds, and prints the result.

***Example output.*** When you run your program, the format should match the following: 
```text
Please enter a number of seconds to convert into hours, minutes, seconds: 3671
3671 seconds = 1 hours, 1 minutes, 11 seconds
```
***Hint.***
- You may assume the user enters valid positive integers. Input validation will be introduced in future assignments.
- You may find floor (`//`) and remainder (`%`) useful.

## Question 4. Word Decoder [24 Points] 
Create a file named `q4.py`.

Write a program that:

1. Asks the user to enter a word
2. Prints:
   - the first character
   - the last character
   - the first 4 characters
   - every other character (starting from the first)
   - the word in reverse

***Example output.*** When you run your program, the format should match the following: 
```text
Please enter a word: datascience
First character: d
Last character: e
First four characters: data
Every other character: dtsine
Backward: ecneicsatad
```


## Question 5. Road Trip Planner [36 Points]
Create a file named `q5.py`.

You are planning a road trip and want to estimate how long the trip will take and how much it will cost for gas. Instead of doing the calculations by hand, you decide to write a Python program to help you quickly plan your trip.

### Part (a) [16 Points]
Ask the user to enter:
- total trip distance (in miles)
- average driving speed (in miles per hour)
- fuel efficiency (in miles per gallon)
- price of gas (per gallon)

### Part (b) [12 Points]
Compute:
- total driving time (in hours, rounded to 1 decimal place)
- total gallons of gas needed (rounded to 1 decimal place)
- total fuel cost (rounded to 1 decimal place)

### Part (c) [8 Points]
Print a clear and friendly summary of the trip as shown below. 

***Example output.*** When you run your program, the format should match the following: 
```text
Enter the trip distance (miles): 180
Enter the average speed (mph): 60
Enter the fuel efficiency (mpg): 30
Enter the gas price per gallon: 3.5

For a trip of 180.0 miles at an average speed of 60.0 mph, the driving time will be 3.0 hours.

Your car will use 6.0 gallons of gas, and the total fuel cost will be $21.0.
```

***Hint.*** 
- Use an empty `print()` statement to create blank lines for readability.
- Follow the example output and print all computed values in Question 5 rounded to 1 decimal place.
