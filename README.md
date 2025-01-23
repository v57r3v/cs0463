java c
Individual Assignment 
Weightage: 80%, 100 marks
Introduction to Computer Science - Part 1  (50 marks)
Construct a solution algorithm for the following   problems. Your   solution   should   contain:
A defining   problem
A   pseudo code   algorithm
A desk   check of the   algorithm
u   Three testcases for each question. Two valid   and   one   error test   case
Question 1 
The   Express   Delivery Service   provides the fastest doorstep collection   and   delivery within   2-hour   in   Singapore. The delivery charge   is calculated   based on the   zonal   classification   in   Singapore   and there   are   two   main   types   of   zones, one   is Central   Business   District   (CBD) with the   postal codes   starting with   01   to   08,   17   to   19,   22   and   23 and other one   is   NON-CBD for all other   areas   other than   CBD. The   postal   code   in   Singapore   contains   exactly   6   numeric digits.   Below   mapping table   is   used to calculate the delivery   charge, 
Category 
Delivery Charge 
Weight 
Within CBD 
$15.00 
Up to 5kg 
CBD to NON-CBD / NON-CBD to CBD 
$20.00 
Up to 5kg 
Outside CBD 
$25.00 
Up to 5kg 
Design an algorithm that will   prompt for   and   receive the   postal   code   for   both   pickup   and   delivery   location   and   calculate the delivery charge and   print   it. The   program will then   prompt   for “Do you want to calculate for another delivery (Yes/No)?” and   is to   repeat the   processing   until “No”   is entered.
Question 2 
An   Individual   income taxis   calculated   based on the total taxable income   of an   individual   in   a   year. The   tax   rate   is defined   based on the taxable   income table shown   below.

Taxable Income ($) 
Rate (%) 
On the first 
20,000 
0 
On the next 
20,000 
2.0 
On the next 
30,000 
3.5 
On the next 
40,000 
7.0 
Above 
110,000 
11.5 
For example,   if John’s taxable   income   is $65,000   in   2021,   his   income tax would   be   $1275   based on   the   below   calculation,
John’s   Income   Tax   for   2021 =   (20000 x 0%) +   (20000   x   2%)   +   (25000   x   3.5%)
                                                                                = 0   +   400   +   875
                                                            代 写Introduction to Computer ScienceJava
代做程序编程语言                    = $1275
Taxpayer’s details are   maintained   in a file that   contains   National   Identity   ID,   Full   Name   and Taxable   income for   the year 2021.   Design an algorithm that will   read the   taxpayer’s   details   and   calculate   the   income   tax   for   each taxpayer   in the file and   print the full   name and   income tax.
Question 3 
In an organisation,   Employee’s   bonus   is computed   based on the   company   performance   and   employee   performance.
Bonus   multiplier for employee’s   performance   rating   is defined   in the table   below.
Employee’s Performance Rating 
Description 
Bonus Multiplier 
1 
Require Improvement 
0.8 
2 
Achieved 
1 
3 
Exceed 
1.5 
4 
Exceptional 
2 
Bonus   multiplier for company   performance   is defined   in the table   below,
Company Performance 
Bonus Multiplier 
<100% 
0.8 
100-105% 
1 
>105% 
1.5 
Employee’s   bonus   is computed   using the formula   below,
Employee’s   Bonus             =          Employee’s Salary             X Bonus   Multiplier for Employee’s   Performance           X Bonus   Multiplier for Company   Performance 
Employees’   performance details are   maintained   in a file that   contains   employee   ID,   employee   name, employee salary, and employee   performance   rating   (1,   2, 3   or 4).   Design   an   algorithm   that   will   prompt   for   and   receive the company   performance   in   percentage and compute the   bonus for   each   employee   in the   file   and print the employee   ID, employee   name   and   bonus.
Introduction to Computer Science - Part 2                                                                                                                                                                                                                                                             (50 marks)
Implement the three questions algorithm   in   Part   1   into Java   programming. Your code   should   contain   appropriate validations and   must   focus on code optimisation.
You   need to submit:
Three Java code
For each question explain   (100-150 words)   how the   logic   works.
Three sample output screenshots
o   Two   normal   and   one   error   testcases







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
