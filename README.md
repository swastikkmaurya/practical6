# practical6
Aim:

Study of conditional statements in python

Theory:

Conditional statements in Python are used to make decisions based on certain conditions. These statements evaluate Boolean expressions (True or False) and execute specific blocks of code accordingly.
The primary decision-making constructs used in Python are if, if-else, and if-elif-else.
The modulus operator (%) checks the divisibility of a element.
Logical operators (and, or, not) to combine multiple conditions.
Relational operators (>, <, >=, <=, ==, !=) to compare values.
The if-elif-else ladder is used when multiple conditions need to be checked. Split is used for break a single string into a list of smaller strings (substrings) based on a specific separator.

Algorithm:

A)
1)Start

2)Input a using a = int(input("Enter a number:"))

3)If a > 0, print "Number is positive"

4)Else if a < 0, print "Number is negative"

5)Else, print "Number is zero"

6)Stop     

B)   
1)Start
2)Input a using a = int(input("Enter a number:"))
3)If a % 2 == 0, print "Number is Even"
4)Else, print "Number is Odd"
5)Stop    

C)   
Start
1)Input a using a = int(input("Enter a number a:"))
2)Input b using b = int(input("Enter a number b:"))
3)Input c using c = int(input("Enter a number c:"))
4)If a > b and a > c, print "a is the greatest number"
5)Else if b > a and b > c, print "b is the greatest number"
6)Else, print "c is the greatest number"
7)Stop     

D)   
1)Start
2)Input subject using subject = int(input("Enter a subject:"))
3)If subject >= 90, print "Grade A"
4)Else if subject >= 75, print "Grade B"
5)Else if subject >= 60, print "Grade C"
6)Else if subject >= 40, print "Grade D"
7)Else, print "Fail"
8)Stop     

E)   
1)Start
2)Input year using year = int(input("Enter a year:"))
3)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0, print "Leap year"
4)Else, print "Not a leap year"
5)Stop    

F)   
Start
1)Input Date using Date = int(input("Enter a date:"))
2)Input Month using Month = int(input("Enter a month:"))
3)Input Year using Year = int(input("Enter a year:"))
4)If Month in (1,3,5,7,8,10,12)
5)If Date == 31 and Month == 12
     Year += 1
     Date = 1
     Month = 1
6)Else if Date < 31
     Date += 1
7)Else
     Date = 1
     Month += 1
8)Else if Month in (4,6,9,11)
9)If Date == 30
     Date = 1
     Month += 1
10)Else if Date < 30
     Date += 1
11)Else if Month == 2
12)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0
  If Date == 29
     Date = 1
     Month += 1
  Else if Date < 29
     Date += 1
  Else
     If Date == 28
     Date = 1
     Month += 1
13)Print Date,"/",Month,"/",Year
14)Stop   

G)Calculate Gross Salary
Step 1: Start
Step 2: Input – Read the basic salary from the user.
Step 3: Condition 1 – If basic is less than or equal to 10,000:Set HRA = 20% of basicSet DA = 80% of basic
Step 4: Condition 2 – Else, if basic is less than or equal to 20,000:Set HRA = 25% of basicSet DA = 90% of basic
Step 5: Condition 3 – Else (if basic is greater than 20,000):Set HRA = 30% of basicSet DA = 95% of basic
Step 6: Calculation – Calculate gross salary using the formula: $$gross = basic + HRA + DA$$
Step 7: Output – Display the calculated gross salary.
Step 8: Stop   

H)Calculate Income Tax   
Step 1: Start
Step 2: Input – Read the income from the user.
Step 3: Bracket 1 (0% Tax)If income > 250,000:Set tax = 0
Step 4: Bracket 2 (5% Tax)Else, if income > 500,000:Calculate tax on the amount above 250,000: tax = (income - 250,000) * 0.05
Step 5: Bracket 3 (20% Tax)Else, if income $\le$ 1,000,000:Take the full tax from Bracket 2 (12,500) and add 20% of the amount above 500,000:tax = 12,500 + (income - 500,000) * 0.20
Step 6: Bracket 4 (30% Tax)Else (if income > 1,000,000):Take the full tax from Brackets 2 and 3 (12,500 + 100,000) and add 30% of the amount above 1,000,000:tax = 112,500 + (income - 1,000,000) * 0.30
Step 7: Output – Display the total calculated tax.
Step 8: Stop   

I)Check for Vowel or Consonant
Step 1: Start
Step 2: Input – Accept a single character from the user and store it in the variable lett.
Step 3: Membership Check – Check if the character stored in lett exists within the string constant 'aeiouAEIOU'.
Step 4: Branching (Condition True) – If the character is found in that string:
Print the message "Vowel". 
Step 5: Branching (Condition False) – Else (if the character is not found in the string): Print the message "Consonant".
Step 6: Stop

J)Increment Given Date
Step 1: Start
Step 2: Input & Parsing
        Accept a date string in dd/mm/yyyy format.
        Split the string by the / character and convert the day (dd), month (mm), and year (yy) into integers.
Step 3: Determine Maximum Days in Month
        If month is 1, 3, 5, 7, 8, 10, or 12: Set max1 = 31.
        Else, if month is 4, 6, 9, or 11: Set max1 = 30.
        Else, if the year is a Leap Year (divisible by 4 and not 100, or divisible by 400): Set max1 = 29.
        Otherwise: Set max1 = 28.
Step 4: Validate the Input Date
        If mm is not between 1 and 12, OR dd is not between 1 and max1: Print "Date is invalid" and stop.
Step 5: Increment Logic
        Case A (End of Month, not December): If dd == max1 and mm != 12:
        Set dd = 1, increment mm by 1.
        Case B (End of Year): If dd == 31 and mm == 12:
        Set dd = 1, mm = 1, and increment yy by 1.
        Case C (Standard Day): Otherwise:
        Increment dd by 1.
Step 6: Output – Display the incremented dd, mm, and yy.
Step 7: Stop
Conclusion:
Hence the conditional statements were successfully implemented in python and operations were dont using them.
