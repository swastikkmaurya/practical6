# practical6
Aim : 

Theory :

1. Positive, Negative, or Zero
Theory: This is a basic trichotomy problem. In mathematics, every real number is either positive, negative, or exactly zero. We use comparison operators (> and <) to branch the logic. Algorithm:

Start.

Input a number num.

If num > 0, print "Positive".

Else if num < 0, print "Negative".

Else, print "Zero".

End.

2. Odd or Even
Theory: This relies on modular arithmetic. An even number is any integer divisible by 2 with a remainder of 0. Algorithm:

Start.

Input num.

Calculate remainder = num % 2.

If remainder is 0, print "Even".

Else, print "Odd".

End.

3. Largest of Three Numbers
Theory: This problem uses compound boolean expressions. To find the largest, we compare one number against all others using the and logical operator. Algorithm:

Start.

Input three numbers a, b, and c.

If a > b and a > c, a is the largest.

Else if b > a and b > c, b is the largest.

Else, c is the largest.

End.

4. Grade Calculation
Theory: This is a range-based classification. It maps a continuous numerical scale (0–100) into discrete categories (A, B, C, D, Fail) based on thresholds. Algorithm:

Start.

Input mark.

If mark >= 90, assign Grade A.

Else if mark >= 75, assign Grade B.

Else if mark >= 60, assign Grade C.

Else if mark >= 40, assign Grade D.

Else, assign Fail.

End.

5. Leap Year Check
Theory: A year is a leap year if it is divisible by 4, but not by 100, unless it is also divisible by 400. This handles the discrepancy in the solar year. Algorithm:

Start.

Input year.

If (year % 4 == 0 AND year % 100 != 0) OR (year % 400 == 0):

Print "Leap Year".

Else:

Print "Not a Leap Year".

End.

6. Next Day Date Logic
Theory: This involves sequence manipulation and conditional logic. It handles "overflow" where exceeding the max days in a month resets the day and increments the month. Algorithm:

Start.

Input date string and split into year, month, day.

Increment day by 1.

Check days_in_month list for current month.

If day > limit:

Set day = 1, increment month.

If month > 12:

Set month = 1, increment year.

Output formatted date.

End.

7. Vowel or Consonant
Theory: This uses membership testing. By checking if a character exists within a predefined set (vowels), we can categorize it. Algorithm:

Start.

Input letter.

Define a set of vowels: {a, e, i, o, u, A, E, I, O, U}.

If letter is in the set, print "Vowel".

Else, print "Consonant".

End.

8. Gross Salary Calculation
Theory: This simulates a basic payroll system. The Gross Salary is the sum of the Basic Pay plus allowances like HRA (House Rent Allowance) and DA (Dearness Allowance), which vary based on salary brackets. Algorithm:

Start.

Input basic salary.

If basic <= 10000, HRA = 20%, DA = 80%.

Else if basic <= 20000, HRA = 25%, DA = 90%.

Else, HRA = 30%, DA = 95%.

Gross = basic + HRA + DA.

End.

9. Income Tax Calculation
Theory: This uses a Progressive Tax System. Tax is calculated in "slabs"—you don't pay the highest rate on the whole amount, only on the portion that falls within that specific bracket. Algorithm:

Start.

Input income.

If income <= 250,000, tax = 0.

If income <= 500,000, tax = (income - 250,000) * 0.05.

If income <= 1,000,000, tax = 12,500 + (income - 500,000) * 0.20.

Else, tax = 112,500 + (income - 1,000,000) * 0.30.

Print tax.

End.

Conclusion

These programs demonstrate how Python uses control flow to handle decision-making. By combining arithmetic operators with if-elif-else structures, we can translate complex logical rules—like government tax laws or calendar systems—into functional code. The key takeaway is that the order of conditions matters; always check for the most specific or highest/lowest thresholds first to ensure the logic doesn't "leak" into the wrong branch.
