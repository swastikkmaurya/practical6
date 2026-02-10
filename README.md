# practical6
Aim : 

Theory :

A) Positive, Negative, or Zero
Theory: This is a basic trichotomy problem. In mathematics, every real number is either positive, negative, or exactly zero. We use comparison operators (> and <) to branch the logic. Algorithm:

1)Start.

2)Input a number num.

3)If num > 0, print "Positive".

4)Else if num < 0, print "Negative".

5)Else, print "Zero".

6)End.

B) Odd or Even
Theory: This relies on modular arithmetic. An even number is any integer divisible by 2 with a remainder of 0. Algorithm:

1.Start.

2.Input num.

3.Calculate remainder = num % 2.

4.If remainder is 0, print "Even".

5.Else, print "Odd".

6.End.

C) Largest of Three Numbers
Theory: This problem uses compound boolean expressions. To find the largest, we compare one number against all others using the and logical operator. Algorithm:

1.Start.

2.Input three numbers a, b, and c.

3.If a > b and a > c, a is the largest.

4.Else if b > a and b > c, b is the largest.

5.Else, c is the largest.

6.End.

D) Grade Calculation
Theory: This is a range-based classification. It maps a continuous numerical scale (0–100) into discrete categories (A, B, C, D, Fail) based on thresholds. Algorithm:

1.Start.

2.Input mark.

3.If mark >= 90, assign Grade A.

4.Else if mark >= 75, assign Grade B.

5.Else if mark >= 60, assign Grade C.

6.Else if mark >= 40, assign Grade D.

7.Else, assign Fail.

8.End.

E) Leap Year Check
Theory: A year is a leap year if it is divisible by 4, but not by 100, unless it is also divisible by 400. This handles the discrepancy in the solar year. Algorithm:

1.Start.

2.Input year.

3.If (year % 4 == 0 AND year % 100 != 0) OR (year % 400 == 0):

 Print "Leap Year".

4.Else:

Print "Not a Leap Year".

5.End.

F) Next Day Date Logic
Theory: This involves sequence manipulation and conditional logic. It handles "overflow" where exceeding the max days in a month resets the day and increments the month. Algorithm:

1.Start.

2.Input date string and split into year, month, day.

3.Increment day by 1.

4.Check days_in_month list for current month.

5.If day > limit:

6.Set day = 1, increment month.

7.If month > 12:

8.Set month = 1, increment year.

9.Output formatted date.

10.End.

G) Vowel or Consonant
Theory: This uses membership testing. By checking if a character exists within a predefined set (vowels), we can categorize it. Algorithm:

1.Start.

2.Input letter.

3.Define a set of vowels: {a, e, i, o, u, A, E, I, O, U}.

4.If letter is in the set, print "Vowel".

5.Else, print "Consonant".

6.End.

H) Gross Salary Calculation
Theory: This simulates a basic payroll system. The Gross Salary is the sum of the Basic Pay plus allowances like HRA (House Rent Allowance) and DA (Dearness Allowance), which vary based on salary brackets. Algorithm:

1.Start.

2.Input basic salary.

3.If basic <= 10000, HRA = 20%, DA = 80%.

4.Else if basic <= 20000, HRA = 25%, DA = 90%.

5.Else, HRA = 30%, DA = 95%.

6.Gross = basic + HRA + DA.

7.End.

I) Income Tax Calculation
Theory: This uses a Progressive Tax System. Tax is calculated in "slabs"—you don't pay the highest rate on the whole amount, only on the portion that falls within that specific bracket. Algorithm:

1.Start.

2.Input income.

3.If income <= 250,000, tax = 0.

4.If income <= 500,000, tax = (income - 250,000) * 0.05.

5.If income <= 1,000,000, tax = 12,500 + (income - 500,000) * 0.20.

6.Else, tax = 112,500 + (income - 1,000,000) * 0.30.

 7.Print tax.

8.End.

Conclusion

These programs demonstrate how Python uses control flow to handle decision-making. By combining arithmetic operators with if-elif-else structures, we can translate complex logical rules—like government tax laws or calendar systems—into functional code. The key takeaway is that the order of conditions matters; always check for the most specific or highest/lowest thresholds first to ensure the logic doesn't "leak" into the wrong branch.
