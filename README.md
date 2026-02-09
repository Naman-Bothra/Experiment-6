# Experiment-6
Experiment 6 : Study of conditional Statement in python
Naman Bothra
25070123078

### Aim : Study of conditional Statements in python

### Theory: Conditional statements in Python are used to make decisions in a program.

They allow the program to execute different blocks of code based on conditions.

Conditional statements help a program think and decide based on given conditions.

1. if statement

Executes code only if the condition is true.

Python checks the condition inside if

If the condition is True, the indented code runs

If the condition is False, the code is skipped

2.if–else statement

If the condition is True, the if block runs

If the condition is False, the else block runs

Executes one block if the condition is true, otherwise another.

Only one block (if or else) executes

else has no condition

Indentation is mandatory in Python

3. if–elif–else statement

Used to check multiple conditions.

### Algorithm : 

Question 1 : Check Whether a Number is Positive, Negative, or Zero

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Check if num is greater than 0.

If true, display "Number is positive".

Else, check if num is less than 0.

If true, display "Number is negative".

Else, display "Number is 0".

Stop

Question 2 : Check Whether a Number is Even or Odd

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Check whether num is divisible by 2.

If num % 2 == 0, display "Number is even".

Otherwise, display "Number is odd".

Stop

Question 3 : Find the Largest of Three Numbers

Start

Prompt the user to enter the first number and store it in variable a.

Prompt the user to enter the second number and store it in variable b.

Prompt the user to enter the third number and store it in variable c.

Compare the three numbers:

If a is greater than or equal to both b and c, display "A is largest" along with a.

Else if b is greater than or equal to both a and c, display "B is largest" along with b.

Else, display "C is largest" along with c.

Stop

Question 4 : Display Grade Based on Marks

Start

Prompt the user to enter the marks.

Read the input and store it in the variable num.

Check the range of marks using conditional statements:

If num is between 90 and 100, display "Grade A".

Else if num is between 75 and 89, display "Grade B".

Else if num is between 60 and 74, display "Grade C".

Else if num is between 40 and 59, display "Grade D".

Else, display "Fail".

Stop

Question 5 : Check Whether a Year is a Leap Year

Start

Prompt the user to enter a year.

Read the input and store it in the variable year.

Check leap year conditions:

If the year is divisible by 400,

OR

If the year is divisible by 4 but not divisible by 100,

then the year is a leap year.

If the above condition is true, display "The year is leap year".

Otherwise, display "The year is not a leap year".

Stop

Question 6 : Increment the Given Date by One Day

Start

Input the day, month, and year from the user.

Store the number of days in each month in a list.

Check whether the given year is a leap year:

If it is a leap year, set the number of days in February to 29.

Increment the day by 1.

Check if the incremented day exceeds the number of days in the given month:

If yes, set day to 1 and increment the month by 1.

Check if the incremented month exceeds 12:

If yes, set month to 1 and increment the year by 1.

Display the incremented date.

Stop


